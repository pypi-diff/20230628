# Comparing `tmp/PyPowerStore-1.9.0.0.tar.gz` & `tmp/PyPowerStore-2.0.0.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "PyPowerStore-1.9.0.0.tar", last modified: Wed Dec 14 06:39:28 2022, max compression
+gzip compressed data, was "dist/PyPowerStore-2.0.0.0.tar", last modified: Wed Jun 28 12:02:19 2023, max compression
```

## Comparing `PyPowerStore-1.9.0.0.tar` & `PyPowerStore-2.0.0.0.tar`

### file list

```diff
@@ -1,24 +1,23 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2022-12-14 06:39:28.516466 PyPowerStore-1.9.0.0/
--rw-r--r--   0 root         (0) root         (0)    11357 2022-12-14 06:38:34.000000 PyPowerStore-1.9.0.0/LICENSE
--rw-r--r--   0 root         (0) root         (0)      276 2022-12-14 06:39:28.516466 PyPowerStore-1.9.0.0/PKG-INFO
-drwxr-xr-x   0 root         (0) root         (0)        0 2022-12-14 06:39:28.505466 PyPowerStore-1.9.0.0/PyPowerStore/
--rw-r--r--   0 root         (0) root         (0)      199 2022-12-14 06:38:34.000000 PyPowerStore-1.9.0.0/PyPowerStore/__init__.py
--rw-r--r--   0 root         (0) root         (0)    13125 2022-12-14 06:38:34.000000 PyPowerStore-1.9.0.0/PyPowerStore/client.py
--rw-r--r--   0 root         (0) root         (0)    83001 2022-12-14 06:38:34.000000 PyPowerStore-1.9.0.0/PyPowerStore/configuration.py
--rw-r--r--   0 root         (0) root         (0)     1886 2022-12-14 06:38:34.000000 PyPowerStore-1.9.0.0/PyPowerStore/powerstore_conn.py
--rw-r--r--   0 root         (0) root         (0)    59154 2022-12-14 06:38:34.000000 PyPowerStore-1.9.0.0/PyPowerStore/protection.py
--rw-r--r--   0 root         (0) root         (0)    98245 2022-12-14 06:38:34.000000 PyPowerStore-1.9.0.0/PyPowerStore/provisioning.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2022-12-14 06:39:28.514466 PyPowerStore-1.9.0.0/PyPowerStore/utils/
--rw-r--r--   0 root         (0) root         (0)        0 2022-12-14 06:38:34.000000 PyPowerStore-1.9.0.0/PyPowerStore/utils/__init__.py
--rw-r--r--   0 root         (0) root         (0)    29366 2022-12-14 06:38:34.000000 PyPowerStore-1.9.0.0/PyPowerStore/utils/constants.py
--rw-r--r--   0 root         (0) root         (0)      584 2022-12-14 06:38:34.000000 PyPowerStore-1.9.0.0/PyPowerStore/utils/exception.py
--rw-r--r--   0 root         (0) root         (0)     6322 2022-12-14 06:38:34.000000 PyPowerStore-1.9.0.0/PyPowerStore/utils/helpers.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2022-12-14 06:39:28.510466 PyPowerStore-1.9.0.0/PyPowerStore.egg-info/
--rw-r--r--   0 root         (0) root         (0)      276 2022-12-14 06:39:28.000000 PyPowerStore-1.9.0.0/PyPowerStore.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)      496 2022-12-14 06:39:28.000000 PyPowerStore-1.9.0.0/PyPowerStore.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2022-12-14 06:39:28.000000 PyPowerStore-1.9.0.0/PyPowerStore.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)       33 2022-12-14 06:39:28.000000 PyPowerStore-1.9.0.0/PyPowerStore.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)       13 2022-12-14 06:39:28.000000 PyPowerStore-1.9.0.0/PyPowerStore.egg-info/top_level.txt
--rw-r--r--   0 root         (0) root         (0)     1748 2022-12-14 06:38:34.000000 PyPowerStore-1.9.0.0/README.md
--rw-r--r--   0 root         (0) root         (0)       38 2022-12-14 06:39:28.517466 PyPowerStore-1.9.0.0/setup.cfg
--rw-r--r--   0 root         (0) root         (0)      595 2022-12-14 06:38:34.000000 PyPowerStore-1.9.0.0/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:02:19.000000 PyPowerStore-2.0.0.0/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:02:19.000000 PyPowerStore-2.0.0.0/PyPowerStore/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:02:19.000000 PyPowerStore-2.0.0.0/PyPowerStore/utils/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:02:15.000000 PyPowerStore-2.0.0.0/PyPowerStore/utils/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    35426 2023-06-28 12:02:15.000000 PyPowerStore-2.0.0.0/PyPowerStore/utils/constants.py
+-rw-r--r--   0 root         (0) root         (0)      584 2023-06-28 12:02:15.000000 PyPowerStore-2.0.0.0/PyPowerStore/utils/exception.py
+-rw-r--r--   0 root         (0) root         (0)     6718 2023-06-28 12:02:15.000000 PyPowerStore-2.0.0.0/PyPowerStore/utils/helpers.py
+-rw-r--r--   0 root         (0) root         (0)      199 2023-06-28 12:02:15.000000 PyPowerStore-2.0.0.0/PyPowerStore/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    13279 2023-06-28 12:02:15.000000 PyPowerStore-2.0.0.0/PyPowerStore/client.py
+-rw-r--r--   0 root         (0) root         (0)    94073 2023-06-28 12:02:15.000000 PyPowerStore-2.0.0.0/PyPowerStore/configuration.py
+-rw-r--r--   0 root         (0) root         (0)     1886 2023-06-28 12:02:15.000000 PyPowerStore-2.0.0.0/PyPowerStore/powerstore_conn.py
+-rw-r--r--   0 root         (0) root         (0)    61608 2023-06-28 12:02:15.000000 PyPowerStore-2.0.0.0/PyPowerStore/protection.py
+-rw-r--r--   0 root         (0) root         (0)   101096 2023-06-28 12:02:15.000000 PyPowerStore-2.0.0.0/PyPowerStore/provisioning.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:02:19.000000 PyPowerStore-2.0.0.0/PyPowerStore.egg-info/
+-rw-r--r--   0 root         (0) root         (0)      339 2023-06-28 12:02:18.000000 PyPowerStore-2.0.0.0/PyPowerStore.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)      488 2023-06-28 12:02:18.000000 PyPowerStore-2.0.0.0/PyPowerStore.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 12:02:18.000000 PyPowerStore-2.0.0.0/PyPowerStore.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)       33 2023-06-28 12:02:18.000000 PyPowerStore-2.0.0.0/PyPowerStore.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)       13 2023-06-28 12:02:18.000000 PyPowerStore-2.0.0.0/PyPowerStore.egg-info/top_level.txt
+-rw-r--r--   0 root         (0) root         (0)     1749 2023-06-28 12:02:15.000000 PyPowerStore-2.0.0.0/README.md
+-rw-r--r--   0 root         (0) root         (0)      705 2023-06-28 12:02:15.000000 PyPowerStore-2.0.0.0/setup.py
+-rw-r--r--   0 root         (0) root         (0)      339 2023-06-28 12:02:19.000000 PyPowerStore-2.0.0.0/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)       38 2023-06-28 12:02:19.000000 PyPowerStore-2.0.0.0/setup.cfg
```

### filetype from file(1)

```diff
@@ -1 +1 @@
-POSIX tar archive
+POSIX tar archive (GNU)
```

### Comparing `PyPowerStore-1.9.0.0/PyPowerStore/client.py` & `PyPowerStore-2.0.0.0/PyPowerStore/client.py`

 * *Files 2% similar despite different names*

```diff
@@ -243,15 +243,18 @@
 
             response = self.fetch_response(
                 http_method, url, payload=payload, querystring=querystring)
             try:
                 if self.is_valid_response(response):
                     response_json = None
                     if response.status_code != 204:
-                        response_json = response.json()
+                        if response.status_code == 201 and response.content == b'':
+                            pass
+                        else:
+                            response_json = response.json()
                     # check 'all_pages' required, response received is
                     # partial(code 206) and contains info about total size of
                     # the collection
                     content_range = response.headers.get('content-range')
                     if all_pages and response.status_code == 206 and\
                        content_range:
                         # 'content-range': '0-99/789'
```

### Comparing `PyPowerStore-1.9.0.0/PyPowerStore/configuration.py` & `PyPowerStore-2.0.0.0/PyPowerStore/configuration.py`

 * *Files 4% similar despite different names*

```diff
@@ -897,72 +897,123 @@
             constants.GET_IP_PORT_DETAILS_URL.format(self.server_ip,
                                                      ip_port_id),
             querystring=constants.IP_PORT_DETAILS_QUERY)
 
     # IP ports operations end
 
     # vCenter operations start
-
     def get_vcenters(self, filter_dict=None, all_pages=False):
         """Get all vcenters.
         :param filter_dict: (optional) Filter details
         :type filter_dict: dict
         :param all_pages: (optional) Indicates whether to return all vcenters
         :type all_pages: bool
         :return: List of vcenters
         :rtype: list[dict]
         """
         LOG.info("Getting vcenters with filter: '%s' and all_pages: '%s'" % (
             filter_dict, all_pages))
         querystring = helpers.prepare_querystring(
             constants.SELECT_ID, filter_dict)
         LOG.info("Querystring: '%s'" % querystring)
-        return self.config_client.request(
-            constants.GET,
-            constants.GET_VCENTER_LIST_URL.format(self.server_ip),
-            querystring=querystring, all_pages=all_pages
-        )
+        vcenter_list = self.config_client.\
+            request(constants.GET,
+                    constants.GET_VCENTER_LIST_URL.format(self.server_ip),
+                    querystring=querystring, all_pages=all_pages)
+
+        if vcenter_list:
+            resp_list = []
+            for vcenter in vcenter_list:
+                resp_dict = self.get_vcenter_details(vcenter['id'])
+                resp_list.append(resp_dict)
+            return resp_list
+        return vcenter_list
 
     def get_vcenter_details(self, vcenter_id):
         """Get vcenter details.
         :param vcenter_id: ID of the vcenter
         :type vcenter_id: str
         :return: Details of vcenter
         :rtype: dict
         """
         LOG.info("Getting vcenter details by ID: '%s'" % vcenter_id)
         querystring = constants.VCENTER_DETAILS_QUERY
-        if helpers.is_foot_hill_or_higher():
-            querystring = {
-                'select': 'id,instance_uuid,address,username,'
-                          'vendor_provider_status,'
-                          'vendor_provider_status_l10n'
-            }
+        if helpers.is_foot_hill_prime_or_higher():
+            querystring = constants.FHP_VCENTER_QUERY
+        elif helpers.is_foot_hill_or_higher():
+            querystring = constants.FHC_MALKA_VCENTER_QUERY
+
         return self.config_client.request(
             constants.GET,
             constants.GET_VCENTER_DETAILS_URL.format(self.server_ip,
                                                      vcenter_id),
             querystring=querystring
         )
 
     def modify_vcenter(self, vcenter_id, modify_param_dict):
-        """Register VASA provider.
+        """Modify vcenter attributes.
         :param vcenter_id: ID of the vcenter
         :type vcenter_id: str
-        :param modify_param_dict: Dict containing VASA provider credentials
+        :param modify_param_dict: Dict containing parameters for modification
         :type modify_param_dict: dict
         :return: Details of vcenter
         :rtype: dict
         """
-        LOG.info("Registering VASA provider: '%s'" % vcenter_id)
+        LOG.info("Modifying vCenter attributes: '%s'" % vcenter_id)
         self.config_client.request(constants.PATCH,
                                    constants.MODIFY_VCENTER_URL.format(
                                        self.server_ip, vcenter_id),
                                    payload=modify_param_dict)
         return self.get_vcenter_details(vcenter_id)
+
+    def add_vcenter(self, add_params):
+        """
+        Add a vcenter to the unified PowerStore model.
+        vcenter can not be added to unified+ deployment
+        :param add_params: the parameters to add vcenter
+        :type add_params:dict
+        :return: ID of the vcenter if addition is successful
+        :rtype: dict
+        """
+        LOG.info("Adding a vcenter.")
+
+        payload = dict()
+        if add_params:
+            for key, values in add_params.items():
+                payload[key] = values
+
+        return self.config_client.\
+            request(constants.POST,
+                    constants.ADD_VCENTER_URL.format(self.server_ip),
+                    payload=payload)
+
+    def remove_vcenter(self, vcenter_id, delete_vasa_provider=None):
+        """
+        Remove vcenter from Unified PowerStore model.
+        vcenter can not be removed from unified+ deployment
+        :param vcenter_id: ID of the vcenter
+        :type vcenter_id: str
+        :param delete_vasa_provider: whether to remove a VASA provider.
+                                     Removal will only happen if the provider
+                                     is not connected to any other PowerStore
+                                     system
+        :type delete_vasa_provider: bool
+        :return: None if success
+        :rtype: None
+        """
+        LOG.info("Removing vcenter: {0}.".format(vcenter_id))
+        payload = dict()
+        if delete_vasa_provider is not None:
+            payload['delete_vendor_provider'] = delete_vasa_provider
+
+        return self.config_client.\
+            request(constants.DELETE,
+                    constants.REMOVE_VCENTER_URL.format(self.server_ip,
+                                                        vcenter_id),
+                    payload=payload)
     # vCenter operations end
 
     # Appliance operations start
     def get_appliances(self, filter_dict=None, all_pages=False):
         """Get all appliances.
 
         :param filter_dict: (optional) Filter details
@@ -1757,15 +1808,14 @@
                                   remote support contact to be modified.
         :type modify_parameters: dict
         :return: None
         :rtype : None
         """
         LOG.info("Modifying remote support contact : '%s' with params '%s'" % (
             remote_support_contact_id, modify_parameters))
-        print(remote_support_contact_id)
         if helpers.is_foot_hill_or_higher():
             remote_support_contact_url = constants.MODIFY_REMOTE_SUPPORT_CONTACT_URL
             return self.config_client.request(
                 constants.PATCH,
                 remote_support_contact_url.format(self.server_ip, remote_support_contact_id),
                 payload=modify_parameters)
         raise Exception("Not supported for PowerStore versions less than 2.0.0.0")
@@ -1839,18 +1889,18 @@
         :rtype: dict
         """
         LOG.info("Getting ldap domain details by name")
 
         resp = self.config_client.request(
             constants.GET,
             constants.GET_LDAP_DOMAIN_LIST_URL.format(
-                self.server_ip, ldap_domain_name),
+                self.server_ip),
             querystring=helpers.prepare_querystring(
                 constants.LDAP_DOMAIN_DETAILS_QUERY,
-                name=constants.EQUALS + ldap_domain_name)
+                domain_name=constants.EQUALS + ldap_domain_name)
         )
 
         filterable_keys = ['domain_name', 'id', 'protocol', 'ldap_server_type']
         filter_dict = {'domain_name': 'eq.{0}'.format(ldap_domain_name)}
         resp = helpers.filtered_details(filterable_keys, filter_dict,
                                         resp, 'ldap_domain')
         if resp:
@@ -2040,15 +2090,217 @@
 
         return self.config_client.request(
             constants.DELETE,
             constants.DELETE_LDAP_ACCOUNT_URL.format(
                 self.server_ip, ldap_account_id))
 
 
-    # LDAP Account operations end    
+    # LDAP Account operations end
+
+    # Virtual volume operations begin
+
+    def get_virtual_volume_list(self, filter_dict=None, all_pages=None):
+        """Get all virtual volumes available on array.
+        :param filter_dict: (optional) Filter details
+        :type filter_dict: dict
+        :param all_pages: (optional) Indicates whether to return all
+                          virtual volumes or not
+        :type all_pages: bool
+        :return: List of virtual volumes on array
+        :rtype: list[dict]
+        """
+        LOG.info("Getting volumes with filter: '%s' and all_pages: %s"
+                 % (filter_dict, all_pages))
+        querystring = helpers.prepare_querystring(
+            constants.VIRTUAL_VOLUME_DETAILS_QUERY,
+            filter_dict)
+        if helpers.is_foot_hill_prime_or_higher():
+            querystring = helpers.prepare_querystring(
+            constants.VIRTUAL_VOLUME_FHP_DETAILS_QUERY,
+            filter_dict)
+        LOG.info("Querystring: '%s'" % querystring)
+        return self.config_client.request(constants.GET,
+                                   constants.GET_VIRTUAL_VOLUME_LIST_URL.format
+                                   (self.server_ip), payload=None,
+                                   querystring=querystring,
+                                   all_pages=all_pages)
+
+    # Virtual volume operations end
+
+    # Storage container operations begin
+
+    def get_storage_container_list(self, filter_dict=None, all_pages=None):
+        """Get all storage container available on array.
+        :param filter_dict: (optional) Filter details
+        :type filter_dict: dict
+        :param all_pages: (optional) Indicates whether to return all
+                          Storage containers or not
+        :type all_pages: bool
+        :return: List of storage containers on array
+        :rtype: list[dict]
+        """
+        LOG.info("Getting storage containers with filter: '%s' and all_pages: %s"
+                 % (filter_dict, all_pages))
+        querystring = helpers.prepare_querystring(
+            constants.STORAGE_CONTAINER_DETAILS_QUERY,
+            filter_dict)
+        LOG.info("Querystring: '%s'" % querystring)
+        return self.config_client.request(constants.GET,
+                                   constants.GET_STORAGE_CONTAINER_LIST_URL.format
+                                   (self.server_ip), payload=None,
+                                   querystring=querystring,
+                                   all_pages=all_pages)
+
+    def get_storage_container_details(self, storage_container_id):
+        """ Get details of a storage container instance.
+
+        :param storage_container_id: Unique identifier of the storage_container
+        :type storage_container_id: str
+        :return: storage container details
+        :rtype: dict
+        """
+        LOG.info("Getting storage container details by ID: '%s'" % storage_container_id)
+
+        return self.config_client.request(
+            constants.GET,
+            constants.GET_STORAGE_CONTAINER_DETAILS_URL.format(
+                self.server_ip, storage_container_id),
+            querystring=constants.STORAGE_CONTAINER_DETAILS_QUERY)
+
+    def get_storage_container_details_by_name(self, storage_container_name):
+        """ Get details of a storage container instance.
+
+        :param storage_container_name: storage container name
+        :type storage_container_name: str
+        :return: storage container details
+        :rtype: dict
+        """
+        LOG.info("Getting storage container details by name: '%s'" % storage_container_name)
+        resp = self.get_storage_container_list()
+
+        for container in resp:
+            if container['name'] == storage_container_name:
+                return self.get_storage_container_details(container['id'])
+
+    def create_storage_container(self, create_parameters):
+        """ Create a storage_container.
+
+        :param create_parameters: Parameters for creating a storage_container
+        :type create_parameters: dict
+        :return: Unique identifier of the new storage container instance created
+        :rtype: dict
+        """
+        LOG.info("creating storage container")
+
+        return self.config_client.request(
+            constants.POST,
+            constants.CREATE_STORAGE_CONTAINER_URL.format(
+                self.server_ip), payload=create_parameters)
+
+    def modify_storage_container_details(self, storage_container_id, modify_parameters):
+        """ Modifying storage container configuration.
+
+        :param storage_container_id: Unique ID of the storage container instance
+        :type storage_container_id: str
+        :param modify_parameters: Parameters for modifying storage container
+        :type modify_parameters: dict
+        :return: None
+        :rtype: None
+        """
+        LOG.info("Modifying storage containert id: '%s'" % storage_container_id)
+
+        return self.config_client.request(
+            constants.PATCH,
+            constants.MODIFY_STORAGE_CONTAINER_URL.format(
+                self.server_ip, storage_container_id), payload=modify_parameters)
+
+    def delete_storage_container(self, storage_container_id, delete_parameters):
+        """ Delete a storage container.
+
+        :param storage_container_id: Unique ID of the storage container instance
+        :type storage_container_id: str
+        :return: None
+        :rtype: None
+        """
+        LOG.info("Deleting storage container with id: '%s'" % storage_container_id)
+
+        return self.config_client.request(
+            constants.DELETE,
+            constants.DELETE_STORAGE_CONTAINER_URL.format(
+                self.server_ip, storage_container_id), payload=delete_parameters)
+    # Storage container operations end
+
+    # Storage container destination operations start
+    def get_storage_container_destination_list(self, filter_dict=None, all_pages=None):
+        """Get all storage container destination.
+        :param filter_dict: (optional) Filter details
+        :type filter_dict: dict
+        :param all_pages: (optional) Indicates whether to return all
+                          Storage containers destination or not
+        :type all_pages: bool
+        :return: List of storage containers destination
+        :rtype: list[dict]
+        """
+        LOG.info("Getting storage containers destination with filter: '%s' "
+                 "and all_pages: %s" % (filter_dict, all_pages))
+        querystring = helpers.prepare_querystring(
+            constants.STORAGE_CONTAINER_DETAILS_DESTINATION_QUERY, filter_dict)
+        LOG.info("Querystring: '%s'" % querystring)
+        return self.config_client.request(
+            constants.GET,
+            constants.GET_STORAGE_CONTAINER_DESTINATION_LIST_URL.format(
+                self.server_ip),
+            payload=None, querystring=querystring, all_pages=all_pages)
+
+    def get_storage_container_destination_details(self, storage_container_destination_id):
+        """ Get details of a storage container destination instance.
+
+        :param storage_container_destination_id: Unique identifier of the
+                                                 storage container destination
+        :type storage_container_destination_id: str
+        :return: storage container destination details
+        :rtype: dict
+        """
+        LOG.info("Getting storage container destination details by "
+                 "ID: '%s'" % storage_container_destination_id)
+
+        return self.config_client.request(
+            constants.GET,
+            constants.GET_STORAGE_CONTAINER_DESTINATION_DETAILS_URL.format(
+                self.server_ip, storage_container_destination_id),
+            querystring=constants.STORAGE_CONTAINER_DETAILS_DESTINATION_QUERY)
+
+    def create_storage_container_destination(self, create_destination_params):
+        """Create a Storage Container Destination
+        :param create_destination_params: parameter to create storage container
+                                          destination
+        :type create_destination_params: dict
+        :return: Unique identifier of newly created storage container destination
+        :rtype: dict
+        """
+        LOG.info("Creating storage container destination.")
+        return self.config_client.request(
+            constants.POST,
+            constants.CREATE_STORAGE_CONTAINER_DESTINATION_URL.format(
+                self.server_ip), payload=create_destination_params)
+
+    def delete_storage_container_destination(self, storage_container_destination_id):
+        """Delete a storage container destination
+        :param storage_container_destination_id: ID of storage container destination
+        :type storage_container_destination_id: str
+        :rtype: None
+        """
+        LOG.info("Deleting storage container destination with "
+                 "id: '%s'" % storage_container_destination_id)
+        return self.config_client.request(
+            constants.DELETE,
+            constants.DELETE_STORAGE_CONTAINER_DESTINATION_URL.format(
+                self.server_ip, storage_container_destination_id))
+
+    # Storage container destination operations end
 
     @staticmethod
     def _prepare_local_user_payload(**kwargs):
         """Prepare a local user request body using provided arguments.
 
         :return: Request body
         :rtype: dict
```

### Comparing `PyPowerStore-1.9.0.0/PyPowerStore/powerstore_conn.py` & `PyPowerStore-2.0.0.0/PyPowerStore/powerstore_conn.py`

 * *Files identical despite different names*

### Comparing `PyPowerStore-1.9.0.0/PyPowerStore/protection.py` & `PyPowerStore-2.0.0.0/PyPowerStore/protection.py`

 * *Files 2% similar despite different names*

```diff
@@ -1138,14 +1138,69 @@
             constants.PATCH,
             constants.MODIFY_REPLICATION_SESSION_URL.format(
                 self.server_ip, session_id), payload=payload
         )
 
     # Replication Session end
 
+    # Replication group start
+    def get_replication_groups(self, filter_dict=None, all_pages=False):
+        """Get all the replication groups
+        :param filter_dict: (optional) Filter details
+        :type filter_dict: dict
+        :param all_pages: (optional) Indicates whether to return all elements
+                          or not
+        :type all_pages: bool
+        :return: replication groups.
+        :rtype: list[dict]
+        """
+        LOG.info("Getting replication groups with filter: '%s' and "
+                 "all_pages: %s" % (filter_dict, all_pages))
+        querystring = helpers.prepare_querystring(
+            constants.REPLICATION_GROUP_QUERY, filter_dict)
+        LOG.info("Querystring: '%s'" % querystring)
+        return self.rest_client.request(
+            constants.GET, constants.REPLICATION_GROUP_DETAILS_LIST_URL.format(
+                self.server_ip), payload=None, querystring=querystring,
+            all_pages=all_pages)
+
+    def get_replication_group_details(self, replication_group_id):
+        """Getting the details of a replication group using ID
+        :param replication_group_id: ID of the replication group
+        :type replication_group_id: str
+        :return: replication session details
+        :rtype: dict
+        """
+        LOG.info("Getting replication session details by ID:"
+                 " '%s'" % replication_group_id)
+
+        return self.rest_client.request(
+            constants.GET,
+            constants.REPLICATION_GROUP_DETAILS_URL.format(
+                self.server_ip, replication_group_id),
+            querystring=constants.REPLICATION_GROUP_QUERY)
+
+    def get_replication_group_details_by_name(self, replication_group_name):
+        """Get details of the replication group details using name
+        :param replication_group_name: Name of the replication group
+        :type replication_group_name: str
+        :return: replication session details
+        :rtype: list of dict
+        """
+        LOG.info("Getting replication group details by name:"
+                 " '%s'" % replication_group_name)
+        return self.rest_client.request(
+            constants.GET,
+            constants.REPLICATION_GROUP_DETAILS_LIST_URL.format(
+                self.server_ip),
+            querystring=helpers.prepare_querystring(
+                constants.REPLICATION_GROUP_QUERY,
+                name=constants.EQUALS + replication_group_name))
+    # Replication group end
+
     # Remote System start
     def get_remote_systems(self, filter_dict=None, all_pages=False):
         """Get all remote systems.
 
         :param filter_dict: (optional) Filter details
         :type filter_dict: dict
         :param all_pages: (optional) Indicates whether to return all elements
```

### Comparing `PyPowerStore-1.9.0.0/PyPowerStore/provisioning.py` & `PyPowerStore-2.0.0.0/PyPowerStore/provisioning.py`

 * *Files 2% similar despite different names*

```diff
@@ -60,39 +60,54 @@
         version = None
         if sw_versions and len(sw_versions) >0:
             version =  sw_versions[0]['release_version']
         return version
 
     def create_volume(self, name, size, description=None,
                       volume_group_id=None, protection_policy_id=None,
-                      performance_policy_id=None):
+                      performance_policy_id=None, app_type=None,
+                      app_type_other=None, appliance_id=None):
         """Create a volume.
 
         :param name: The name of the volume
         :param size: The size of the volume
         :param description: (optional) The description given to the volume
         :param volume_group_id: (optional) The volume group ID
         :param protection_policy_id: (optional) The protection policy ID
         :param performance_policy_id: (optional) The performance policy ID
-        """
+        :param app_type: (optional) The application type
+        :param app_type_other: (optional) Describes application type when
+            app_type is set to other
+        :param appliance_id: (optional) The appliance ID
+        """
+        if app_type is not None and not helpers.is_malka_or_higher():
+            raise Exception("'app_type' parameter is supported only from "
+                            "Powerstore version 2.1.0.0 onwards")
+
         LOG.info("Creating volume: '%s'" % name)
         payload = self._prepare_create_volume_payload(name, size,
                                                       description,
                                                       volume_group_id,
                                                       protection_policy_id,
-                                                      performance_policy_id)
+                                                      performance_policy_id,
+                                                      app_type,
+                                                      app_type_other,
+                                                      appliance_id)
         self.client.request(constants.POST,
                             constants.VOLUME_CREATE_URL.format(
                                 self.server_ip), payload)
 
     def _prepare_create_volume_payload(self, name, size,
                                        description,
                                        volume_group_id,
                                        protection_policy_id,
-                                       performance_policy_id):
+                                       performance_policy_id,
+                                       app_type,
+                                       app_type_other,
+                                       appliance_id):
 
         create_volume_dict = dict()
         if name is not None:
             create_volume_dict['name'] = name
         if size is not None:
             create_volume_dict['size'] = size
         if description is not None:
@@ -100,14 +115,20 @@
         if volume_group_id is not None:
             create_volume_dict['volume_group_id'] = volume_group_id
         if protection_policy_id is not None:
             create_volume_dict['protection_policy_id'] = protection_policy_id
         if performance_policy_id is not None:
             create_volume_dict['performance_policy_id'] = \
                 performance_policy_id
+        if app_type is not None:
+            create_volume_dict['app_type'] = app_type
+        if app_type_other is not None:
+            create_volume_dict['app_type_other'] = app_type_other
+        if appliance_id is not None:
+            create_volume_dict['appliance_id'] = appliance_id
 
         return create_volume_dict
 
     def delete_volume(self, volume_id):
         """Delete a volume.
 
         :param volume_id: The Volume ID
@@ -118,62 +139,78 @@
         LOG.info("Deleting volume: '%s'" % volume_id)
         return self.client.request(
             constants.DELETE, constants.DELETE_VOLUME_URL.format(
                 self.server_ip, volume_id),
             payload=None)
 
     def modify_volume(self, volume_id, name=None, description=None, size=None,
-                      protection_policy_id=None,
-                      performance_policy_id=None):
+                      protection_policy_id=None, performance_policy_id=None,
+                      app_type=None, app_type_other=None):
         """Modify a volume.
 
         :param volume_id: The volume ID
         :type volume_id: str
         :param name: The name of the volume
         :type name: str
         :param description: The description of the volume
         :type description: str
         :param size: The size of the volume
         :type size: str
         :param protection_policy_id: The protection policy ID
         :type protection_policy_id: str
         :param performance_policy_id: The performance policy ID
         :type performance_policy_id: str
+        :param app_type: The application type
+        :type app_type: str
+        :param app_type_other: Describes application type when
+            app_type is set to other
         :return: None if success else raise exception
         :rtype: None
         """
+        if app_type is not None and not helpers.is_malka_or_higher():
+            raise Exception("'app_type' parameter is supported only from "
+                            "Powerstore version 2.1.0.0 onwards")
+
         LOG.info("Modifying volume: '%s'" % volume_id)
         payload = self.\
             _prepare_modify_volume_payload(name,
                                            description,
                                            size,
                                            protection_policy_id,
-                                           performance_policy_id)
+                                           performance_policy_id,
+                                           app_type,
+                                           app_type_other)
         return self.client.request(
             constants.PATCH, constants.MODIFY_VOLUME_URL.format(
                 self.server_ip, volume_id),
             payload)
 
     def _prepare_modify_volume_payload(self, name=None, description=None,
                                        size=None,
                                        protection_policy_id=None,
-                                       performance_policy_id=None):
+                                       performance_policy_id=None,
+                                       app_type=None,
+                                       app_type_other=None):
 
         modify_volume_dict = dict()
         if name is not None:
             modify_volume_dict['name'] = name
         if description is not None:
             modify_volume_dict['description'] = description
         if size is not None:
             modify_volume_dict['size'] = size
         if protection_policy_id is not None:
             modify_volume_dict['protection_policy_id'] = protection_policy_id
         if performance_policy_id is not None:
             modify_volume_dict['performance_policy_id'] = \
                 performance_policy_id
+        if app_type is not None:
+            modify_volume_dict['app_type'] = app_type
+        if app_type_other is not None:
+            modify_volume_dict['app_type_other'] = app_type_other
 
         return modify_volume_dict
 
     def clone_volume(self, volume_id, name=None,
                      description=None, host_id=None,
                      host_group_id=None,
                      logical_unit_number=None,
@@ -234,15 +271,15 @@
         if protection_policy_id is not None:
             clone_volume_dict['protection_policy_id'] = protection_policy_id
         if performance_policy_id is not None:
             clone_volume_dict['performance_policy_id'] = \
                 performance_policy_id
 
         return clone_volume_dict
-    
+
     def refresh_volume(self, volume_id, volume_id_to_refresh_from=None,
                        create_backup_snap=None,
                        backup_snap_name=None,
                        backup_snap_description=None,
                        backup_snap_expiration_timestamp=None,
                        backup_snap_performance_policy_id=None):
         """Refresh a volume.
@@ -299,15 +336,15 @@
             refresh_volume_dict['backup_snap_profile']['expiration_timestamp'] = \
                 backup_snap_expiration_timestamp
         if backup_snap_performance_policy_id is not None:
             refresh_volume_dict['backup_snap_profile']['performance_policy_id'] = \
                 backup_snap_performance_policy_id
 
         return refresh_volume_dict
-    
+
     def restore_volume(self, volume_id, snap_id_to_restore_from=None,
                        create_backup_snap=None,
                        backup_snap_name=None,
                        backup_snap_description=None,
                        backup_snap_expiration_timestamp=None,
                        backup_snap_performance_policy_id=None):
         """Restore a volume.
@@ -1159,15 +1196,15 @@
 
         :param volume_group_id: ID of the volume group to clone
         :type volume_group_id: str
         :param name: Unique name for the clone volume group.
         :type name: str
         :param description: (optional) Description for the clone volume group.
         :type description: str
-        :param protection_policy_id: (optional) Unique identifier of the protection 
+        :param protection_policy_id: (optional) Unique identifier of the protection
                                      policy to assign to the clone volume group
         :type protection_policy_id: str
         :return: Unique identifier of the new instance created if success else raise exception
         :rtype: dict
         """
         LOG.info("Cloning volumegroup: '%s'" % volume_group_id)
         payload = self._prepare_clone_vg_payload(name, description, protection_policy_id)
@@ -1489,15 +1526,15 @@
                 constants.SELECT_ALL_HOST_VOLUME_MAPPING,
                 volume_id=constants.EQUALS +
                 volume_id
             )
         )
 
     # NAS Server methods
- 
+
     def get_nas_servers(self, filter_dict=None, all_pages=False):
         """Get a list of nas servers.
 
         :param filter_dict: (optional) Filter detail
         :type filter_dict: dict
         :param all_pages: (optional) Indicates whether to return all element
                           or not
@@ -1616,37 +1653,43 @@
 
         :param filesystem_id: The File System ID
         :type filesystem_id: str
         :returns: File system details
         :rtype: dict
         """
         LOG.info("Getting filesystem details by ID: '%s'" % filesystem_id)
+        querystring=constants.SELECT_ALL_FILESYSTEM
+        if helpers.is_foot_hill_prime_or_higher():
+            querystring=constants.SELECT_ALL_FILESYSTEM_PRIME
         return self.client.request(
             constants.GET,
             constants.GET_FILESYSTEM_DETAILS_URL.format(self.server_ip,
                                                         filesystem_id),
             payload=None,
-            querystring=constants.SELECT_ALL_FILESYSTEM)
+            querystring=querystring)
 
     def get_filesystem_by_name(self, filesystem_name, nas_server_id):
         """Get details of a filesystem by name.
 
         :param filesystem_name: The name of the File System
         :type filesystem_name: str
         :returns: File system details
         :rtype: dict
         """
         LOG.info("Getting filesystem details by name: '%s' and NAS Server: "
                  "'%s'" % (filesystem_name, nas_server_id))
+        querystring=constants.SELECT_ALL_FILESYSTEM
+        if helpers.is_foot_hill_prime_or_higher():
+            querystring=constants.SELECT_ALL_FILESYSTEM_PRIME
         return self.client.request(
             constants.GET,
             constants.GET_FILESYSTEM_DETAILS_BY_NAME_URL.format(
                 self.server_ip),
             payload=None, querystring=helpers.prepare_querystring(
-                constants.SELECT_ALL_FILESYSTEM,
+                querystring,
                 nas_server_id=constants.EQUALS + nas_server_id,
                 name=constants.EQUALS + filesystem_name
             )
         )
 
     def create_filesystem(self, name, nas_server_id, size_total,
                           advance_parameters):
@@ -1667,14 +1710,18 @@
         payload = dict()
         payload['name'] = name
         payload['nas_server_id'] = nas_server_id
         payload['size_total'] = size_total
 
         if advance_parameters:
             for key, value in advance_parameters.items():
+                if key in constants.FILESYSTEM_PRIME and \
+                        not helpers.is_foot_hill_prime_or_higher():
+                    raise Exception( key + " is supported for PowerStore" \
+                        " version 3.0.0.0 and above.")
                 payload[key] = value
         return self.client.request(constants.POST,
                                    constants.CREATE_FILESYSTEM_URL.format(
                                        self.server_ip), payload=payload)
 
     def delete_filesystem(self, filesystem_id):
         """Delete a File System.
@@ -1718,14 +1765,18 @@
         :return: None if success else raise exception
         :rtype: None
         """
         LOG.info("Modifying filesystem: '%s'" % filesystem_id)
         if modify_parameters:
             payload = dict()
             for key, value in modify_parameters.items():
+                if key in constants.FILESYSTEM_PRIME and \
+                        not helpers.is_foot_hill_prime_or_higher():
+                    raise Exception( key + " is supported for PowerStore" \
+                        " version 3.0.0.0 and above.")
                 if value is not None:
                     payload[key] = value
 
             if payload:
                 return self.client.request(
                     constants.PATCH,
                     constants.MODIFY_FILESYSTEM_URL.format(
```

### Comparing `PyPowerStore-1.9.0.0/PyPowerStore/utils/constants.py` & `PyPowerStore-2.0.0.0/PyPowerStore/utils/constants.py`

 * *Files 14% similar despite different names*

```diff
@@ -56,36 +56,41 @@
               "mapped_volumes(id,logical_unit_number),nsid,nguid,"
               "node_affinity,node_affinity_l10n,metro_replication_session_id,"
               "is_host_access_available,app_type,app_type_other,app_type_l10n,"
               "migration_session_id"
 }
 
 # Host Query
-SELECT_ALL_HOST = {"select": "id,name,description,os_type,"
-                             "host_group_id,"
-                             "host_initiators,os_type_l10n,"
-                             "mapped_hosts(id,logical_unit_number,"
-                             "host_group(id,name),volume(id,name))"
+SELECT_ALL_HOST = {
+    "select": "id,name,description,os_type,"
+              "host_group_id,"
+              "host_initiators,os_type_l10n,"
+              "mapped_hosts(id,logical_unit_number,"
+              "host_group(id,name),volume(id,name)),"
+              "host_virtual_volume_mappings(id,host_id,host_group_id,virtual_volume_id)"
                    }
 FHC_HOST_DETAILS_QUERY = {
     "select": "id,name,description,os_type,host_group_id,host_initiators,"
               "os_type_l10n,mapped_hosts(id,logical_unit_number,"
-              "host_group(id,name),volume(id,name)),type,type_l10n"
+              "host_group(id,name),volume(id,name)),type,type_l10n,"
+              "host_virtual_volume_mappings(id,host_id,host_group_id,virtual_volume_id)"
 }
 FHP_HOST_DETAILS_QUERY = {
     "select": "id,name,description,type,os_type,host_group_id,"
               "host_connectivity,os_type_l10n,"
               "mapped_hosts(id,logical_unit_number,host_group(id,name),"
               "volume(id,name)),type_l10n,host_connectivity_l10n,"
               "initiators(id,port_name,port_type,chap_single_username,"
-              "chap_mutual_username,active_sessions),host_initiators"
+              "chap_mutual_username,active_sessions),host_initiators,"
+              "host_virtual_volume_mappings(id,host_id,host_group_id,virtual_volume_id)"
 }
 
 SELECT_ALL_HOST_GROUP = {"select": "name,id,description,hosts(id,name)"}
-FHP_HOST_GROUP_QUERY = {"select": "name,id,description,hosts(id,name),"
+FHP_HOST_GROUP_QUERY = {"select": "name,id,description,hosts(id,name,host_virtual_volume_mappings(id,"
+                                  "host_id,host_group_id,virtual_volume_id)),"
                                   "host_connectivity,host_connectivity_l10n,"
                                   "mapped_host_groups(id,volume_id,"
                                   "logical_unit_number)"}
 
 SELECT_ALL_VG = {"select": "id,name,description,creation_"
                            "timestamp, member_type,"
                            "is_protectable, protection_policy_id,"
@@ -132,14 +137,40 @@
                          "last_writable_timestamp, is_modified,access_type,"
                          "creator_type, filesystem_type_l10n,"
                          "access_policy_l10n, locking_policy_l10n,"
                          "folder_rename_policy_l10n, access_type_l10n,"
                          "creator_type_l10n,nas_server(name,id),"
                          "protection_policy(name,id)"}
 
+SELECT_ALL_FILESYSTEM_PRIME = {"select": "id,name, description,"
+                               "parent_id, filesystem_type, size_total,size_used,"
+                               "access_policy,locking_policy,"
+                               "folder_rename_policy, is_smb_sync_writes_enabled,"
+                               "is_smb_op_locks_enabled, is_smb_no_notify_enabled,"
+                               "is_smb_notify_on_access_enabled,"
+                               "is_smb_notify_on_write_enabled,"
+                               "smb_notify_on_change_dir_depth,"
+                               "is_async_MTime_enabled, is_quota_enabled,"
+                               "grace_period, default_hard_limit,"
+                               "default_soft_limit, creation_timestamp,"
+                               "expiration_timestamp, last_refresh_timestamp,"
+                               "last_writable_timestamp, is_modified,access_type,"
+                               "creator_type, filesystem_type_l10n,"
+                               "access_policy_l10n, locking_policy_l10n,"
+                               "folder_rename_policy_l10n, access_type_l10n,"
+                               "creator_type_l10n,nas_server(name,id),"
+                               "protection_policy(name,id),"
+                               "file_events_publishing_mode,"
+                               "file_events_publishing_mode_l10n,"
+                               "config_type, config_type_l10n,flr_attributes,"
+                               "host_io_size,host_io_size_l10n"}
+
+FILESYSTEM_PRIME = ['config_type', 'is_async_MTime_enabled',
+                    'file_events_publishing_mode', 'flr_attributes',
+                    'host_io_size']
 
 FHP_NAS_QUERYSTRING = {"select": "id,name, description, operational_status,"
                        "current_node_id,preferred_node_id,"
                        "default_unix_user,default_windows_user,"
                        "current_unix_directory_service,"
                        "is_username_translation_enabled,"
                        "is_auto_user_mapping_enabled,"
@@ -288,14 +319,28 @@
               'current_usages_l10n'
 }
 
 # vCenter details
 VCENTER_DETAILS_QUERY = {
     'select': 'id,instance_uuid,address,username'
 }
+FHC_MALKA_VCENTER_QUERY = {
+    'select': 'id,instance_uuid,address,username,vendor_provider_status,'
+              'vendor_provider_status_l10n,'
+              'virtual_machines(id,name,instance_uuid,type,status,'
+              'virtual_volumes,protection_policy_id)'
+}
+FHP_VCENTER_QUERY = {
+    'select': 'id,instance_uuid,address,username,version,'
+              'vendor_provider_status,vendor_provider_status_l10n,'
+              'virtual_machines(id,name,instance_uuid,type,status,'
+              'virtual_volumes,protection_policy_id),'
+              'datastores(id,instance_uuid,name,type,'
+              'storage_container_id),vsphere_hosts(id,name,version)'
+}
 
 # Appliance details
 APPLIANCE_DETAILS_QUERY = {
     'select': 'id,name,service_tag,express_service_code,model,nodes,'
               'veth_ports,maintenance_windows,fc_ports,sas_ports,eth_ports,'
               'software_installed,virtual_volumes,hardware,volumes,'
               'ip_pool_addresses'
@@ -318,24 +363,26 @@
               'discovery_chap_mode,session_chap_mode,data_network_latency,'
               'data_connections,capabilities,file_connection_address,'
               'file_connection_state,vnx_file_username,import_sessions,'
               'appliance_details,type_l10n,replication_sessions,'
               'state_l10n,data_connection_type_l10n,file_connection_state_l10n,'
               'data_connection_state_l10n,discovery_chap_mode_l10n,'
               'session_chap_mode_l10n,data_network_latency_l10n,'
-              'capabilities_l10n,storage_container_destinations'
+              'capabilities_l10n,storage_container_destinations(id,'
+              'storage_container_id,remote_system_id,remote_storage_container_id,'
+              'storage_container(id,name))'
 }
 
 # Certificate details
 CERTIFICATE_DETAILS_QUERY = {
     'select': 'id,type,type_l10n,service,service_l10n,scope,is_current,'
-               'is_valid,members(subject,serial_number,signature_algorithm,'
-               'issuer,valid_from,valid_to,public_key_algorithm,key_length,'
-               'thumbprint_algorithm,thumbprint_algorithm_l10n,thumbprint,'
-               'certificate,depth,subject_alternative_names)'
+              'is_valid,members(subject,serial_number,signature_algorithm,'
+              'issuer,valid_from,valid_to,public_key_algorithm,key_length,'
+              'thumbprint_algorithm,thumbprint_algorithm_l10n,thumbprint,'
+              'certificate,depth,subject_alternative_names)'
 }
 
 # Security config details
 SECURITY_CONFIG_DETAILS_QUERY = {
     'select': 'id,idle_timeout,protocol_mode,protocol_mode_l10n'
 }
 
@@ -374,14 +421,50 @@
 # LDAP Domain details
 LDAP_DOMAIN_DETAILS_QUERY = {
     'select': 'id,domain_name,ldap_servers,port,ldap_server_type,protocol,bind_user,ldap_timeout,'
               'is_global_catalog,user_id_attribute,user_object_class,user_search_path,'
               'group_name_attribute,group_member_attribute,group_object_class,'
               'group_search_path,group_search_level,ldap_server_type_l10n,protocol_l10n'
 }
+VIRTUAL_VOLUME_FHP_DETAILS_QUERY = {
+    'select': 'id,name,size,type,usage_type,appliance_id,storage_container_id,io_priority,profile_id,'
+              'replication_group_id,creator_type,is_readonly,migration_session_id,virtual_machine_uuid,'
+              'family_id,parent_id,source_id,source_timestamp,creation_timestamp,naa_name,'
+              'is_replication_destination,location_history,protection_policy_id,nsid,nguid,type_l10n,'
+              'usage_type_l10n,io_priority_l10n,creator_type_l10n,'
+              'host_virtual_volume_mappings(id,host_id,host_group_id,virtual_volume_id)'
+}
+VIRTUAL_VOLUME_DETAILS_QUERY = {
+    'select': 'id,name,size,type,usage_type,appliance_id,storage_container_id,io_priority,profile_id,'
+              'creator_type,is_readonly,migration_session_id,virtual_machine_uuid,'
+              'family_id,parent_id,source_id,source_timestamp,creation_timestamp,'
+              'location_history,type_l10n,usage_type_l10n,io_priority_l10n,creator_type_l10n,'
+              'host_virtual_volume_mappings(id,host_id,host_group_id,virtual_volume_id)'
+}
+
+STORAGE_CONTAINER_DETAILS_QUERY = {
+    'select': 'id,name,quota,storage_protocol,storage_protocol_l10n,'
+              'virtual_volumes(id,name),replication_groups(id,name),datastores(id,name),'
+              'destinations(id,remote_system_id,remote_storage_container_id)'
+}
+
+STORAGE_CONTAINER_DETAILS_DESTINATION_QUERY = {
+    'select': 'id,remote_system_id,storage_container_id,'
+              'storage_container(id,name),remote_storage_container_id,'
+              'remote_system(id,name,management_address)'
+}
+
+REPLICATION_GROUP_QUERY = {
+    'select': 'id,name,storage_container_id,description,creator_type,'
+              'creation_timestamp,is_replication_destination,creator_type_l10n'
+              ',virtual_volumes,storage_container,parent,source,'
+              'child_replication_groups,target_replication_groups,'
+              'virtual_machines'
+}
+
 # LDAP Account details
 LDAP_ACCOUNT_DETAILS_QUERY = {
     'select': 'id,role_id,domain_id,name,type,type_l10n,dn'
 }
 # Select all Snapshot
 
 EQUALS = 'eq.'
@@ -466,14 +549,18 @@
 REPLICATION_SESSION_SYNC_URL = 'https://{0}/api/rest/replication_session/{1}/sync'
 REPLICATION_SESSION_PAUSE_URL = 'https://{0}/api/rest/replication_session/{1}/pause'
 REPLICATION_SESSION_RESUME_URL = 'https://{0}/api/rest/replication_session/{1}/resume'
 REPLICATION_SESSION_FAILOVER_URL = 'https://{0}/api/rest/replication_session/{1}/failover'
 REPLICATION_SESSION_REPROTECT_URL = 'https://{0}/api/rest/replication_session/{1}/reprotect'
 MODIFY_REPLICATION_SESSION_URL = REPLICATION_SESSION_OBJECT_URL
 
+# Replication Group endpoints
+REPLICATION_GROUP_DETAILS_LIST_URL = 'https://{0}/api/rest/replication_group'
+REPLICATION_GROUP_DETAILS_URL = 'https://{0}/api/rest/replication_group/{1}'
+
 # Remote system endpoints
 GET_REMOTE_SYSTEM_LIST_URL = 'https://{0}/api/rest/remote_system'
 GET_REMOTE_SYSTEM_DETAILS_URL = 'https://{0}/api/rest/remote_system/{1}'
 CREATE_REMOTE_SYSTEM_URL = GET_REMOTE_SYSTEM_LIST_URL
 MODIFY_REMOTE_SYSTEM_URL = GET_REMOTE_SYSTEM_DETAILS_URL
 DELETE_REMOTE_SYSTEM_URL = GET_REMOTE_SYSTEM_DETAILS_URL
 GET_REMOTE_APPLIANCE_URL = 'https://{0}/api/rest/remote_system/{1}/query_appliances'
@@ -588,15 +675,17 @@
 
 # Job endpoints
 GET_JOB_DETAILS_URL = 'https://{0}/api/rest/job/{1}'
 
 # vCenter endpoints
 GET_VCENTER_LIST_URL = 'https://{0}/api/rest/vcenter'
 GET_VCENTER_DETAILS_URL = 'https://{0}/api/rest/vcenter/{1}'
+ADD_VCENTER_URL = GET_VCENTER_LIST_URL
 MODIFY_VCENTER_URL = GET_VCENTER_DETAILS_URL
+REMOVE_VCENTER_URL = GET_VCENTER_DETAILS_URL
 
 # Appliance endpoints
 GET_APPLIANCE_LIST_URL = 'https://{0}/api/rest/appliance'
 GET_APPLIANCE_DETAILS_URL = 'https://{0}/api/rest/appliance/{1}'
 
 # Certificate endpoints
 GET_CERTIFICATE_LIST_URL = 'https://{0}/api/rest/x509_certificate'
@@ -663,7 +752,24 @@
 
 # LDAP Account endpoints
 GET_LDAP_ACCOUNT_LIST_URL = 'https://{0}/api/rest/ldap_account'
 GET_LDAP_ACCOUNT_DETAILS_URL = 'https://{0}/api/rest/ldap_account/{1}'
 CREATE_LDAP_ACCOUNT_URL = GET_LDAP_ACCOUNT_LIST_URL
 MODIFY_LDAP_ACCOUNT_URL = GET_LDAP_ACCOUNT_DETAILS_URL
 DELETE_LDAP_ACCOUNT_URL = GET_LDAP_ACCOUNT_DETAILS_URL
+
+# virtual volume endpoints
+GET_VIRTUAL_VOLUME_LIST_URL = 'https://{0}/api/rest/virtual_volume'
+GET_VIRTUAL_VOLUME_DETAILS_URL = 'https://{0}/api/rest/virtual_volume/{1}'
+
+# Storage container endpoints
+GET_STORAGE_CONTAINER_LIST_URL = 'https://{0}/api/rest/storage_container'
+GET_STORAGE_CONTAINER_DETAILS_URL = 'https://{0}/api/rest/storage_container/{1}'
+CREATE_STORAGE_CONTAINER_URL = GET_STORAGE_CONTAINER_LIST_URL
+MODIFY_STORAGE_CONTAINER_URL = GET_STORAGE_CONTAINER_DETAILS_URL
+DELETE_STORAGE_CONTAINER_URL = GET_STORAGE_CONTAINER_DETAILS_URL
+
+# Storage container Destination endpoints
+GET_STORAGE_CONTAINER_DESTINATION_LIST_URL = "https://{0}/api/rest/storage_container_destination"
+GET_STORAGE_CONTAINER_DESTINATION_DETAILS_URL = "https://{0}/api/rest/storage_container_destination/{1}"
+CREATE_STORAGE_CONTAINER_DESTINATION_URL = GET_STORAGE_CONTAINER_DESTINATION_LIST_URL
+DELETE_STORAGE_CONTAINER_DESTINATION_URL = GET_STORAGE_CONTAINER_DESTINATION_DETAILS_URL
```

### Comparing `PyPowerStore-1.9.0.0/PyPowerStore/utils/exception.py` & `PyPowerStore-2.0.0.0/PyPowerStore/utils/exception.py`

 * *Files identical despite different names*

### Comparing `PyPowerStore-1.9.0.0/PyPowerStore/utils/helpers.py` & `PyPowerStore-2.0.0.0/PyPowerStore/utils/helpers.py`

 * *Files 5% similar despite different names*

```diff
@@ -44,29 +44,41 @@
         LOG.disabled = False
     else:
         LOG.disabled = True
     return LOG
 
 
 def is_foot_hill_or_higher():
-    """Return a true if the array version is foot hill or higher.
+    """Returns true if the array version is foot hill or higher.
 
     :return: True if foot hill or higher
     :rtype: bool
     """
     foot_hill_version = '2.0.0.0'
     array_version = provisioning_obj.get_array_version()
     if array_version and (
             parse_version(array_version[0:7]) >= parse_version(foot_hill_version)):
         return True
     return False
 
+def is_malka_or_higher():
+    """Returns true if the array version is Malka or higher.
+
+    :return: True if array version is Malka or higher
+    :rtype: bool
+    """
+    malka_version = '2.1.0.0'
+    array_version = provisioning_obj.get_array_version()
+    if array_version and (
+            parse_version(array_version[0:7]) >= parse_version(malka_version)):
+        return True
+    return False
 
 def is_foot_hill_prime_or_higher():
-    """Return a true if the array version is foothill prime or higher.
+    """Returns true if the array version is foothill prime or higher.
 
     :return: True if foothill prime or higher
     :rtype: bool
     """
     foot_hill_prime_version = '3.0.0.0'
     array_version = provisioning_obj.get_array_version()
     if array_version and (
```

### Comparing `PyPowerStore-1.9.0.0/README.md` & `PyPowerStore-2.0.0.0/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -42,15 +42,15 @@
 The library docs are available under 'docs' folder.
 
 
 ## Requirements
 
 This library uses python's "requests" library.
 
-PyPowerStore officially supports Python 3.8, 3.9 and 3.10.
+PyPowerStore officially supports Python 3.9, 3.10 and 3.11.
 
 
 ## Support
 
 PyPowerStore is supported by Dell and is provided under the terms of the license attached to the source code.
 For any setup, configuration issues, questions or feedback, join the [Dell Automation community](https://www.dell.com/community/Automation/bd-p/Automation).
 For any Dell storage issues, please contact Dell support at: https://www.dell.com/support.
```

### Comparing `PyPowerStore-1.9.0.0/setup.py` & `PyPowerStore-2.0.0.0/setup.py`

 * *Files 16% similar despite different names*

```diff
@@ -6,18 +6,20 @@
 try:
     from setuptools import setup
 except ImportError:
     from distutils.core import setup
 
 
 setup(name='PyPowerStore',
-      version='1.9.0.0',
+      version='2.0.0.0',
       description='Python Library for Dell PowerStore',
       author='Ansible Team at Dell',
       author_email='ansible.team@dell.com',
       install_requires=[
         'urllib3>=1.26.7',
         'requests>=2.23.0'
       ],
+      license_files = ('LICENSE',),
+      classifiers=['License :: OSI Approved :: Apache Software License'],
       url='https://github.com/dell/python-powerstore',
       packages=['PyPowerStore', 'PyPowerStore.utils'],
       )
```


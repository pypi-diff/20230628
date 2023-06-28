# Comparing `tmp/perun.proxy.utils-1.3.0.tar.gz` & `tmp/perun.proxy.utils-1.7.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "perun.proxy.utils-1.3.0.tar", last modified: Wed Jun  7 05:35:58 2023, max compression
+gzip compressed data, was "perun.proxy.utils-1.7.1.tar", last modified: Wed Jun 28 08:30:57 2023, max compression
```

## Comparing `perun.proxy.utils-1.3.0.tar` & `perun.proxy.utils-1.7.1.tar`

### file list

```diff
@@ -1,29 +1,35 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-07 05:35:58.356145 perun.proxy.utils-1.3.0/
--rw-rw-rw-   0 root         (0) root         (0)     1560 2023-06-05 07:53:45.000000 perun.proxy.utils-1.3.0/LICENSE
--rw-r--r--   0 root         (0) root         (0)      268 2023-06-07 05:35:58.356145 perun.proxy.utils-1.3.0/PKG-INFO
--rw-rw-rw-   0 root         (0) root         (0)     2273 2023-06-05 07:53:45.000000 perun.proxy.utils-1.3.0/README.md
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-07 05:35:58.240142 perun.proxy.utils-1.3.0/perun/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-07 05:35:58.240142 perun.proxy.utils-1.3.0/perun/proxy/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-07 05:35:58.296144 perun.proxy.utils-1.3.0/perun/proxy/utils/
--rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-05 07:53:45.000000 perun.proxy.utils-1.3.0/perun/proxy/utils/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)      502 2023-06-05 07:53:45.000000 perun.proxy.utils-1.3.0/perun/proxy/utils/metadata_expiration.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-07 05:35:58.352145 perun.proxy.utils-1.3.0/perun/proxy/utils/nagios/
--rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-05 07:53:45.000000 perun.proxy.utils-1.3.0/perun/proxy/utils/nagios/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)      709 2023-06-07 05:08:08.000000 perun.proxy.utils-1.3.0/perun/proxy/utils/nagios/check_custom_command.py
--rw-rw-rw-   0 root         (0) root         (0)     2436 2023-06-07 05:08:08.000000 perun.proxy.utils-1.3.0/perun/proxy/utils/nagios/check_ldap.py
--rw-rw-rw-   0 root         (0) root         (0)    72133 2023-06-05 07:53:45.000000 perun.proxy.utils-1.3.0/perun/proxy/utils/nagios/check_mongodb.py
--rw-rw-rw-   0 root         (0) root         (0)     1758 2023-06-06 15:06:34.000000 perun.proxy.utils-1.3.0/perun/proxy/utils/nagios/check_rpc_status.py
--rwxrwxrwx   0 root         (0) root         (0)    18134 2023-06-05 07:53:45.000000 perun.proxy.utils-1.3.0/perun/proxy/utils/nagios/check_saml.py
--rw-rw-rw-   0 root         (0) root         (0)     3193 2023-06-05 07:53:45.000000 perun.proxy.utils-1.3.0/perun/proxy/utils/nagios/check_user_logins.py
--rwxrwxrwx   0 root         (0) root         (0)     2322 2023-06-05 07:53:45.000000 perun.proxy.utils-1.3.0/perun/proxy/utils/print_docker_versions.py
--rw-rw-rw-   0 root         (0) root         (0)     3038 2023-06-05 07:53:45.000000 perun.proxy.utils-1.3.0/perun/proxy/utils/run_version_script.py
--rw-rw-rw-   0 root         (0) root         (0)     1890 2023-06-05 07:53:45.000000 perun.proxy.utils-1.3.0/perun/proxy/utils/separate_oidc_logs.py
--rwxrwxrwx   0 root         (0) root         (0)     2238 2023-06-05 07:53:45.000000 perun.proxy.utils-1.3.0/perun/proxy/utils/separate_ssp_logs.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-07 05:35:58.260143 perun.proxy.utils-1.3.0/perun.proxy.utils.egg-info/
--rw-r--r--   0 root         (0) root         (0)      268 2023-06-07 05:35:58.000000 perun.proxy.utils-1.3.0/perun.proxy.utils.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)      770 2023-06-07 05:35:58.000000 perun.proxy.utils-1.3.0/perun.proxy.utils.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-07 05:35:58.000000 perun.proxy.utils-1.3.0/perun.proxy.utils.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)      100 2023-06-07 05:35:58.000000 perun.proxy.utils-1.3.0/perun.proxy.utils.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)        6 2023-06-07 05:35:58.000000 perun.proxy.utils-1.3.0/perun.proxy.utils.egg-info/top_level.txt
--rw-rw-rw-   0 root         (0) root         (0)       90 2023-06-07 05:35:58.356145 perun.proxy.utils-1.3.0/setup.cfg
--rw-rw-rw-   0 root         (0) root         (0)      544 2023-06-07 05:08:08.000000 perun.proxy.utils-1.3.0/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 08:30:57.036198 perun.proxy.utils-1.7.1/
+-rw-rw-rw-   0 root         (0) root         (0)     1560 2023-06-05 07:53:45.000000 perun.proxy.utils-1.7.1/LICENSE
+-rw-r--r--   0 root         (0) root         (0)     3536 2023-06-28 08:30:57.036198 perun.proxy.utils-1.7.1/PKG-INFO
+-rw-rw-rw-   0 root         (0) root         (0)     2539 2023-06-20 12:40:41.000000 perun.proxy.utils-1.7.1/README.md
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 08:30:56.820193 perun.proxy.utils-1.7.1/perun/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 08:30:56.820193 perun.proxy.utils-1.7.1/perun/proxy/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 08:30:56.884195 perun.proxy.utils-1.7.1/perun/proxy/utils/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-05 07:53:45.000000 perun.proxy.utils-1.7.1/perun/proxy/utils/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)      502 2023-06-05 07:53:45.000000 perun.proxy.utils-1.7.1/perun/proxy/utils/metadata_expiration.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 08:30:57.036198 perun.proxy.utils-1.7.1/perun/proxy/utils/nagios/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-05 07:53:45.000000 perun.proxy.utils-1.7.1/perun/proxy/utils/nagios/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)      709 2023-06-07 12:28:41.000000 perun.proxy.utils-1.7.1/perun/proxy/utils/nagios/check_custom_command.py
+-rw-rw-rw-   0 root         (0) root         (0)     1399 2023-06-07 12:27:41.000000 perun.proxy.utils-1.7.1/perun/proxy/utils/nagios/check_dockers.py
+-rw-rw-rw-   0 root         (0) root         (0)      577 2023-06-07 12:27:41.000000 perun.proxy.utils-1.7.1/perun/proxy/utils/nagios/check_exabgp_propagation.py
+-rw-rw-rw-   0 root         (0) root         (0)     2436 2023-06-07 12:28:41.000000 perun.proxy.utils-1.7.1/perun/proxy/utils/nagios/check_ldap.py
+-rw-rw-rw-   0 root         (0) root         (0)      235 2023-06-07 12:27:41.000000 perun.proxy.utils-1.7.1/perun/proxy/utils/nagios/check_ldap_syncrepl.py
+-rw-rw-rw-   0 root         (0) root         (0)    72133 2023-06-05 07:53:45.000000 perun.proxy.utils-1.7.1/perun/proxy/utils/nagios/check_mongodb.py
+-rw-rw-rw-   0 root         (0) root         (0)      221 2023-06-12 08:06:47.000000 perun.proxy.utils-1.7.1/perun/proxy/utils/nagios/check_nginx.py
+-rw-rw-rw-   0 root         (0) root         (0)     1758 2023-06-07 12:28:41.000000 perun.proxy.utils-1.7.1/perun/proxy/utils/nagios/check_rpc_status.py
+-rwxrwxrwx   0 root         (0) root         (0)    18760 2023-06-15 10:37:02.000000 perun.proxy.utils-1.7.1/perun/proxy/utils/nagios/check_saml.py
+-rw-rw-rw-   0 root         (0) root         (0)     3193 2023-06-05 07:53:45.000000 perun.proxy.utils-1.7.1/perun/proxy/utils/nagios/check_user_logins.py
+-rwxrwxrwx   0 root         (0) root         (0)      930 2023-06-07 12:27:41.000000 perun.proxy.utils-1.7.1/perun/proxy/utils/nagios/webserver_availability.py
+-rwxrwxrwx   0 root         (0) root         (0)     2322 2023-06-05 07:53:45.000000 perun.proxy.utils-1.7.1/perun/proxy/utils/print_docker_versions.py
+-rw-rw-rw-   0 root         (0) root         (0)     1624 2023-06-20 12:40:41.000000 perun.proxy.utils-1.7.1/perun/proxy/utils/run_probes.py
+-rw-rw-rw-   0 root         (0) root         (0)     3038 2023-06-05 07:53:45.000000 perun.proxy.utils-1.7.1/perun/proxy/utils/run_version_script.py
+-rw-rw-rw-   0 root         (0) root         (0)     1890 2023-06-05 07:53:45.000000 perun.proxy.utils-1.7.1/perun/proxy/utils/separate_oidc_logs.py
+-rwxrwxrwx   0 root         (0) root         (0)     2238 2023-06-05 07:53:45.000000 perun.proxy.utils-1.7.1/perun/proxy/utils/separate_ssp_logs.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 08:30:56.836194 perun.proxy.utils-1.7.1/perun.proxy.utils.egg-info/
+-rw-r--r--   0 root         (0) root         (0)     3536 2023-06-28 08:30:56.000000 perun.proxy.utils-1.7.1/perun.proxy.utils.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     1036 2023-06-28 08:30:56.000000 perun.proxy.utils-1.7.1/perun.proxy.utils.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 08:30:56.000000 perun.proxy.utils-1.7.1/perun.proxy.utils.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)      169 2023-06-28 08:30:56.000000 perun.proxy.utils-1.7.1/perun.proxy.utils.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)        6 2023-06-28 08:30:56.000000 perun.proxy.utils-1.7.1/perun.proxy.utils.egg-info/top_level.txt
+-rw-rw-rw-   0 root         (0) root         (0)      171 2023-06-28 08:30:57.036198 perun.proxy.utils-1.7.1/setup.cfg
+-rw-rw-rw-   0 root         (0) root         (0)      646 2023-06-28 08:24:25.000000 perun.proxy.utils-1.7.1/setup.py
```

### Comparing `perun.proxy.utils-1.3.0/LICENSE` & `perun.proxy.utils-1.7.1/LICENSE`

 * *Files identical despite different names*

### Comparing `perun.proxy.utils-1.3.0/README.md` & `perun.proxy.utils-1.7.1/README.md`

 * *Files 8% similar despite different names*

```diff
@@ -1,11 +1,18 @@
-# ProxyIdP scripts
+# Perun proxy utils
 
 ## Scripts
 
+### run_probes.py
+
+- script designed to execute multiple monitoring probes
+- output is compatible with CheckMK
+- it is required to put configuration file to `/etc/run_probes_cfg.yaml`
+- for usage run: `./run_probes.py` or `python3 -m perun.proxy.utils.run_probes`
+
 ### separate_ssp_script.py
 
 - Script for remove all logs from test accounts from SimpleSAMLlogs
 
 - Params:
   - 1 - The file name
```

### Comparing `perun.proxy.utils-1.3.0/perun/proxy/utils/nagios/check_custom_command.py` & `perun.proxy.utils-1.7.1/perun/proxy/utils/nagios/check_custom_command.py`

 * *Files identical despite different names*

### Comparing `perun.proxy.utils-1.3.0/perun/proxy/utils/nagios/check_ldap.py` & `perun.proxy.utils-1.7.1/perun/proxy/utils/nagios/check_ldap.py`

 * *Files identical despite different names*

### Comparing `perun.proxy.utils-1.3.0/perun/proxy/utils/nagios/check_mongodb.py` & `perun.proxy.utils-1.7.1/perun/proxy/utils/nagios/check_mongodb.py`

 * *Files identical despite different names*

### Comparing `perun.proxy.utils-1.3.0/perun/proxy/utils/nagios/check_rpc_status.py` & `perun.proxy.utils-1.7.1/perun/proxy/utils/nagios/check_rpc_status.py`

 * *Files identical despite different names*

### Comparing `perun.proxy.utils-1.3.0/perun/proxy/utils/nagios/check_saml.py` & `perun.proxy.utils-1.7.1/perun/proxy/utils/nagios/check_saml.py`

 * *Files 2% similar despite different names*

```diff
@@ -110,36 +110,37 @@
         default="https://inet.muni.cz/sys/servertest",
     )
     parser.add_argument(
         "--string",
         help="string to expect after successful authentication",
         default="OSCIS",
     )
-    parser.add_argument("--idp-host", help="hostname of IdP", default="id.muni.cz")
     parser.add_argument(
-        "--hosts",
-        nargs="*",
-        default=[],
-        help="space separated list of hostname:ip or hostname:hostname pairs "
-        + "for replacing in all URLs",
+        "--logout-url",
+        help="URL to trigger logout",
+        default="https://inet.muni.cz/pub/appctl/logout",
     )
-    """
     parser.add_argument(
-        "--other-urls",
-        nargs="*",
-        default=[],
-        help="list of more services for testing single sign-on",
+        "--postlogout-string",
+        help="String to expect after successful logout",
+        default="successfully signed out",
+    )
+    parser.add_argument(
+        "--skip-logout-check",
+        action="store_true",
+        help="skip logout check",
     )
+    parser.add_argument("--idp-host", help="hostname of IdP", default="id.muni.cz")
     parser.add_argument(
-        "--other-urls-final",
+        "--hosts",
         nargs="*",
         default=[],
-        help="list of final URLs of the other services for testing single sign-on",
+        help="space separated list of hostname:ip or hostname:hostname pairs "
+        + "for replacing in all URLs",
     )
-    """
     parser.add_argument(
         "--warn-time",
         type=int,
         help="warning threshold in seconds",
         default=5,
     )
     parser.add_argument(
@@ -503,19 +504,32 @@
                 )
             if self.args.username not in login_form_html:
                 self.finish(
                     "Missing remembered username on the login page.",
                     "WARNING",
                 )
 
-        self.finish(
-            "Authentication took {:.2f} seconds".format(elapsed_seconds),
-            status,
-            auth_time=elapsed_seconds,
-        )
+        if not self.args.skip_logout_check:
+            # test logout
+            logout_html, logout_url = self.initial_request(self.args.logout_url)
+            if self.args.verbose >= 3:
+                print(logout_html)
+            if self.args.postlogout_string not in logout_html:
+                self.finish(
+                    "Missing the testing string {} in the logout response.".format(
+                        self.args.postlogout_string
+                    ),
+                    "CRITICAL",
+                )
+
+            self.finish(
+                "Authentication took {:.2f} seconds".format(elapsed_seconds),
+                status,
+                auth_time=elapsed_seconds,
+            )
 
     def __init__(self, args):
         self.args = args
         self.hosts = {
             host.split(":", 1)[0]: host.split(":", 1)[1]
             for host in (
                 self.args.hosts[0].strip("\"'").split(" ")
```

### Comparing `perun.proxy.utils-1.3.0/perun/proxy/utils/nagios/check_user_logins.py` & `perun.proxy.utils-1.7.1/perun/proxy/utils/nagios/check_user_logins.py`

 * *Files identical despite different names*

### Comparing `perun.proxy.utils-1.3.0/perun/proxy/utils/print_docker_versions.py` & `perun.proxy.utils-1.7.1/perun/proxy/utils/print_docker_versions.py`

 * *Files identical despite different names*

### Comparing `perun.proxy.utils-1.3.0/perun/proxy/utils/run_version_script.py` & `perun.proxy.utils-1.7.1/perun/proxy/utils/run_version_script.py`

 * *Files identical despite different names*

### Comparing `perun.proxy.utils-1.3.0/perun/proxy/utils/separate_oidc_logs.py` & `perun.proxy.utils-1.7.1/perun/proxy/utils/separate_oidc_logs.py`

 * *Files identical despite different names*

### Comparing `perun.proxy.utils-1.3.0/perun/proxy/utils/separate_ssp_logs.py` & `perun.proxy.utils-1.7.1/perun/proxy/utils/separate_ssp_logs.py`

 * *Files identical despite different names*

### Comparing `perun.proxy.utils-1.3.0/perun.proxy.utils.egg-info/SOURCES.txt` & `perun.proxy.utils-1.7.1/perun.proxy.utils.egg-info/SOURCES.txt`

 * *Files 8% similar despite different names*

```diff
@@ -6,17 +6,23 @@
 perun.proxy.utils.egg-info/SOURCES.txt
 perun.proxy.utils.egg-info/dependency_links.txt
 perun.proxy.utils.egg-info/requires.txt
 perun.proxy.utils.egg-info/top_level.txt
 perun/proxy/utils/__init__.py
 perun/proxy/utils/metadata_expiration.py
 perun/proxy/utils/print_docker_versions.py
+perun/proxy/utils/run_probes.py
 perun/proxy/utils/run_version_script.py
 perun/proxy/utils/separate_oidc_logs.py
 perun/proxy/utils/separate_ssp_logs.py
 perun/proxy/utils/nagios/__init__.py
 perun/proxy/utils/nagios/check_custom_command.py
+perun/proxy/utils/nagios/check_dockers.py
+perun/proxy/utils/nagios/check_exabgp_propagation.py
 perun/proxy/utils/nagios/check_ldap.py
+perun/proxy/utils/nagios/check_ldap_syncrepl.py
 perun/proxy/utils/nagios/check_mongodb.py
+perun/proxy/utils/nagios/check_nginx.py
 perun/proxy/utils/nagios/check_rpc_status.py
 perun/proxy/utils/nagios/check_saml.py
-perun/proxy/utils/nagios/check_user_logins.py
+perun/proxy/utils/nagios/check_user_logins.py
+perun/proxy/utils/nagios/webserver_availability.py
```

### Comparing `perun.proxy.utils-1.3.0/setup.py` & `perun.proxy.utils-1.7.1/setup.py`

 * *Files 16% similar despite different names*

```diff
@@ -11,9 +11,12 @@
         "setuptools",
         "pymongo~=4.3",
         "asyncssh~=2.13",
         "docker~=6.0",
         "beautifulsoup4~=4.12",
         "requests~=2.31",
         "ldap3~=2.9.1",
+        "PyYAML~=6.0",
+        "check_syncrepl_extended~=2020.13",
+        "check_nginx_status~=1.0",
     ],
 )
```


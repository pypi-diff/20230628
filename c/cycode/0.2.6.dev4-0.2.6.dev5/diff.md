# Comparing `tmp/cycode-0.2.6.dev4.tar.gz` & `tmp/cycode-0.2.6.dev5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "cycode-0.2.6.dev4.tar", max compression
+gzip compressed data, was "cycode-0.2.6.dev5.tar", max compression
```

## Comparing `cycode-0.2.6.dev4.tar` & `cycode-0.2.6.dev5.tar`

### file list

```diff
@@ -1,62 +1,62 @@
--rw-r--r--   0        0        0    32549 2023-06-27 21:07:53.987001 cycode-0.2.6.dev4/README.md
--rw-r--r--   0        0        0      115 2023-06-27 21:08:33.403399 cycode-0.2.6.dev4/cycode/__init__.py
--rw-r--r--   0        0        0        0 2023-06-27 21:07:53.987001 cycode-0.2.6.dev4/cycode/cli/__init__.py
--rw-r--r--   0        0        0        0 2023-06-27 21:07:53.987001 cycode-0.2.6.dev4/cycode/cli/auth/__init__.py
--rw-r--r--   0        0        0     2813 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/auth/auth_command.py
--rw-r--r--   0        0        0     4761 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/auth/auth_manager.py
--rw-r--r--   0        0        0     1652 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/ci_integrations.py
--rw-r--r--   0        0        0    47480 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/code_scanner.py
--rw-r--r--   0        0        0      453 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/config.py
--rw-r--r--   0        0        0      387 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/config.yaml
--rw-r--r--   0        0        0     5039 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/consts.py
--rw-r--r--   0        0        0        0 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/exceptions/__init__.py
--rw-r--r--   0        0        0     1698 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/exceptions/custom_exceptions.py
--rw-r--r--   0        0        0        0 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/helpers/__init__.py
--rw-r--r--   0        0        0        0 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/helpers/maven/__init__.py
--rw-r--r--   0        0        0     2196 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/helpers/maven/base_restore_maven_dependencies.py
--rw-r--r--   0        0        0      992 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/helpers/maven/restore_gradle_dependencies.py
--rw-r--r--   0        0        0     2993 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/helpers/maven/restore_maven_dependencies.py
--rw-r--r--   0        0        0     5835 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/helpers/sca_code_scanner.py
--rw-r--r--   0        0        0     7243 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/main.py
--rw-r--r--   0        0        0     1332 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/models.py
--rw-r--r--   0        0        0       93 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/printers/__init__.py
--rw-r--r--   0        0        0      626 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/printers/base_printer.py
--rw-r--r--   0        0        0     1483 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/printers/base_table_printer.py
--rw-r--r--   0        0        0     1891 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/printers/console_printer.py
--rw-r--r--   0        0        0     1537 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/printers/json_printer.py
--rw-r--r--   0        0        0     5838 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/printers/sca_table_printer.py
--rw-r--r--   0        0        0     2277 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/printers/table.py
--rw-r--r--   0        0        0      477 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/printers/table_models.py
--rw-r--r--   0        0        0     4701 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/printers/table_printer.py
--rw-r--r--   0        0        0     8955 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/printers/text_printer.py
--rw-r--r--   0        0        0        0 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/user_settings/__init__.py
--rw-r--r--   0        0        0      533 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/user_settings/base_file_manager.py
--rw-r--r--   0        0        0     4821 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/user_settings/config_file_manager.py
--rw-r--r--   0        0        0     6925 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/user_settings/configuration_manager.py
--rw-r--r--   0        0        0     1908 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/user_settings/credentials_manager.py
--rw-r--r--   0        0        0     6853 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/user_settings/user_settings_commands.py
--rw-r--r--   0        0        0        0 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/utils/__init__.py
--rw-r--r--   0        0        0     2162 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/utils/path_utils.py
--rw-r--r--   0        0        0      195 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/utils/scan_utils.py
--rw-r--r--   0        0        0      941 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/utils/shell_executor.py
--rw-r--r--   0        0        0     1346 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/utils/string_utils.py
--rw-r--r--   0        0        0     2700 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/utils/task_timer.py
--rw-r--r--   0        0        0      815 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/utils/yaml_utils.py
--rw-r--r--   0        0        0      929 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cli/zip_file.py
--rw-r--r--   0        0        0       57 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cyclient/__init__.py
--rw-r--r--   0        0        0     1708 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cyclient/auth_client.py
--rw-r--r--   0        0        0     2458 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cyclient/config.py
--rw-r--r--   0        0        0      126 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cyclient/config.yaml
--rw-r--r--   0        0        0      119 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cyclient/config_dev.py
--rw-r--r--   0        0        0      220 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cyclient/cycode_client.py
--rw-r--r--   0        0        0     3617 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cyclient/cycode_client_base.py
--rw-r--r--   0        0        0      543 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cyclient/cycode_dev_based_client.py
--rw-r--r--   0        0        0     1705 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cyclient/cycode_token_based_client.py
--rw-r--r--   0        0        0     9102 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cyclient/models.py
--rw-r--r--   0        0        0     6222 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cyclient/scan_client.py
--rw-r--r--   0        0        0        0 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cyclient/scan_config/__init__.py
--rw-r--r--   0        0        0     1090 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cyclient/scan_config/scan_config_base.py
--rw-r--r--   0        0        0     1021 2023-06-27 21:07:53.991001 cycode-0.2.6.dev4/cycode/cyclient/scan_config/scan_config_creator.py
--rw-r--r--   0        0        0      197 2023-06-27 21:07:53.995001 cycode-0.2.6.dev4/cycode/cyclient/utils.py
--rw-r--r--   0        0        0     2032 2023-06-27 21:08:33.403399 cycode-0.2.6.dev4/pyproject.toml
--rw-r--r--   0        0        0    34073 1970-01-01 00:00:00.000000 cycode-0.2.6.dev4/PKG-INFO
+-rw-r--r--   0        0        0    32549 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/README.md
+-rw-r--r--   0        0        0      115 2023-06-28 11:24:43.689310 cycode-0.2.6.dev5/cycode/__init__.py
+-rw-r--r--   0        0        0        0 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/__init__.py
+-rw-r--r--   0        0        0        0 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/auth/__init__.py
+-rw-r--r--   0        0        0     2813 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/auth/auth_command.py
+-rw-r--r--   0        0        0     4761 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/auth/auth_manager.py
+-rw-r--r--   0        0        0     1652 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/ci_integrations.py
+-rw-r--r--   0        0        0    47480 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/code_scanner.py
+-rw-r--r--   0        0        0      453 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/config.py
+-rw-r--r--   0        0        0      387 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/config.yaml
+-rw-r--r--   0        0        0     5245 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/consts.py
+-rw-r--r--   0        0        0        0 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/exceptions/__init__.py
+-rw-r--r--   0        0        0     1698 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/exceptions/custom_exceptions.py
+-rw-r--r--   0        0        0        0 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/helpers/__init__.py
+-rw-r--r--   0        0        0        0 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/helpers/maven/__init__.py
+-rw-r--r--   0        0        0     2196 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/helpers/maven/base_restore_maven_dependencies.py
+-rw-r--r--   0        0        0      992 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/helpers/maven/restore_gradle_dependencies.py
+-rw-r--r--   0        0        0     2993 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/helpers/maven/restore_maven_dependencies.py
+-rw-r--r--   0        0        0     5835 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/helpers/sca_code_scanner.py
+-rw-r--r--   0        0        0     7243 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/main.py
+-rw-r--r--   0        0        0     1332 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/models.py
+-rw-r--r--   0        0        0       93 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/printers/__init__.py
+-rw-r--r--   0        0        0      626 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/printers/base_printer.py
+-rw-r--r--   0        0        0     1483 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/printers/base_table_printer.py
+-rw-r--r--   0        0        0     1891 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/printers/console_printer.py
+-rw-r--r--   0        0        0     1537 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/printers/json_printer.py
+-rw-r--r--   0        0        0     5624 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/printers/sca_table_printer.py
+-rw-r--r--   0        0        0     2277 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/printers/table.py
+-rw-r--r--   0        0        0      477 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/printers/table_models.py
+-rw-r--r--   0        0        0     4701 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/printers/table_printer.py
+-rw-r--r--   0        0        0     8955 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/printers/text_printer.py
+-rw-r--r--   0        0        0        0 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/user_settings/__init__.py
+-rw-r--r--   0        0        0      533 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/user_settings/base_file_manager.py
+-rw-r--r--   0        0        0     4821 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/user_settings/config_file_manager.py
+-rw-r--r--   0        0        0     6925 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/user_settings/configuration_manager.py
+-rw-r--r--   0        0        0     1908 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/user_settings/credentials_manager.py
+-rw-r--r--   0        0        0     6853 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/user_settings/user_settings_commands.py
+-rw-r--r--   0        0        0        0 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/utils/__init__.py
+-rw-r--r--   0        0        0     2162 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/utils/path_utils.py
+-rw-r--r--   0        0        0      195 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/utils/scan_utils.py
+-rw-r--r--   0        0        0      941 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/utils/shell_executor.py
+-rw-r--r--   0        0        0     1989 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/utils/string_utils.py
+-rw-r--r--   0        0        0     2700 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/utils/task_timer.py
+-rw-r--r--   0        0        0      815 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/utils/yaml_utils.py
+-rw-r--r--   0        0        0      929 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cli/zip_file.py
+-rw-r--r--   0        0        0       57 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cyclient/__init__.py
+-rw-r--r--   0        0        0     1708 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cyclient/auth_client.py
+-rw-r--r--   0        0        0     2458 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cyclient/config.py
+-rw-r--r--   0        0        0      126 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cyclient/config.yaml
+-rw-r--r--   0        0        0      119 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cyclient/config_dev.py
+-rw-r--r--   0        0        0      220 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cyclient/cycode_client.py
+-rw-r--r--   0        0        0     3617 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cyclient/cycode_client_base.py
+-rw-r--r--   0        0        0      543 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cyclient/cycode_dev_based_client.py
+-rw-r--r--   0        0        0     1705 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cyclient/cycode_token_based_client.py
+-rw-r--r--   0        0        0     9102 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cyclient/models.py
+-rw-r--r--   0        0        0     6222 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cyclient/scan_client.py
+-rw-r--r--   0        0        0        0 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cyclient/scan_config/__init__.py
+-rw-r--r--   0        0        0     1090 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cyclient/scan_config/scan_config_base.py
+-rw-r--r--   0        0        0     1021 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cyclient/scan_config/scan_config_creator.py
+-rw-r--r--   0        0        0      197 2023-06-28 11:24:14.585321 cycode-0.2.6.dev5/cycode/cyclient/utils.py
+-rw-r--r--   0        0        0     2032 2023-06-28 11:24:43.689310 cycode-0.2.6.dev5/pyproject.toml
+-rw-r--r--   0        0        0    34073 1970-01-01 00:00:00.000000 cycode-0.2.6.dev5/PKG-INFO
```

### Comparing `cycode-0.2.6.dev4/README.md` & `cycode-0.2.6.dev5/README.md`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cli/auth/auth_command.py` & `cycode-0.2.6.dev5/cycode/cli/auth/auth_command.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cli/auth/auth_manager.py` & `cycode-0.2.6.dev5/cycode/cli/auth/auth_manager.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cli/ci_integrations.py` & `cycode-0.2.6.dev5/cycode/cli/ci_integrations.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cli/code_scanner.py` & `cycode-0.2.6.dev5/cycode/cli/code_scanner.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cli/consts.py` & `cycode-0.2.6.dev5/cycode/cli/consts.py`

 * *Files 2% similar despite different names*

```diff
@@ -122,7 +122,12 @@
 GIT_PUSH_OPTION_ENV_VAR_PREFIX = 'GIT_PUSH_OPTION_'
 
 SKIP_SCAN_FLAG = 'skip-cycode-scan'
 VERBOSE_SCAN_FLAG = 'verbose'
 
 LICENSE_COMPLIANCE_POLICY_ID = '8f681450-49e1-4f7e-85b7-0c8fe84b3a35'
 PACKAGE_VULNERABILITY_POLICY_ID = '9369d10a-9ac0-48d3-9921-5de7fe9a37a7'
+
+# Shortcut dependency paths by remove all middle depndencies between direct dependency and influence/vulnerable dependency.
+# Example: A -> B -> C
+# Result: A -> ... -> C
+SCA_SHORTCUT_DEPENDENCY_PATHS = 2
```

### Comparing `cycode-0.2.6.dev4/cycode/cli/exceptions/custom_exceptions.py` & `cycode-0.2.6.dev5/cycode/cli/exceptions/custom_exceptions.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cli/helpers/maven/base_restore_maven_dependencies.py` & `cycode-0.2.6.dev5/cycode/cli/helpers/maven/base_restore_maven_dependencies.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cli/helpers/maven/restore_gradle_dependencies.py` & `cycode-0.2.6.dev5/cycode/cli/helpers/maven/restore_gradle_dependencies.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cli/helpers/maven/restore_maven_dependencies.py` & `cycode-0.2.6.dev5/cycode/cli/helpers/maven/restore_maven_dependencies.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cli/helpers/sca_code_scanner.py` & `cycode-0.2.6.dev5/cycode/cli/helpers/sca_code_scanner.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cli/main.py` & `cycode-0.2.6.dev5/cycode/cli/main.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cli/models.py` & `cycode-0.2.6.dev5/cycode/cli/models.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cli/printers/base_printer.py` & `cycode-0.2.6.dev5/cycode/cli/printers/base_printer.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cli/printers/base_table_printer.py` & `cycode-0.2.6.dev5/cycode/cli/printers/base_table_printer.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cli/printers/console_printer.py` & `cycode-0.2.6.dev5/cycode/cli/printers/console_printer.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cli/printers/json_printer.py` & `cycode-0.2.6.dev5/cycode/cli/printers/json_printer.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cli/printers/sca_table_printer.py` & `cycode-0.2.6.dev5/cycode/cli/printers/sca_table_printer.py`

 * *Files 12% similar despite different names*

```diff
@@ -3,14 +3,15 @@
 
 import click
 from texttable import Texttable
 
 from cycode.cli.consts import LICENSE_COMPLIANCE_POLICY_ID, PACKAGE_VULNERABILITY_POLICY_ID
 from cycode.cli.models import DocumentDetections, Detection
 from cycode.cli.printers.base_table_printer import BaseTablePrinter
+from cycode.cli.utils.string_utils import shortcut_dependency_paths
 
 SEVERITY_COLUMN = 'Severity'
 LICENSE_COLUMN = 'License'
 UPGRADE_COLUMN = 'Upgrade'
 REPOSITORY_COLUMN = 'Repository'
 CVE_COLUMN = 'CVE'
 
@@ -104,36 +105,27 @@
                 header_width_size_cols.append(header_len)
         text_table.set_cols_width(header_width_size_cols)
 
     @staticmethod
     def _print_summary_issues(detections: List, title: str) -> None:
         click.echo(f'⛔ Found {len(detections)} issues of type: {click.style(title, bold=True)}')
 
-    @staticmethod
-    def _shortcut_dependency_paths(dependency_paths: str) -> str:
-        dependencies = dependency_paths.split(' -> ')
-
-        if len(dependencies) < 2:
-            return dependencies[0]
-
-        return f'{dependencies[0]} -> ... -> {dependencies[-1]}'
-
     def _get_common_detection_fields(self, detection: Detection) -> List[str]:
         dependency_paths = 'N/A'
         dependency_paths_raw = detection.detection_details.get('dependency_paths')
         if dependency_paths_raw:
-            dependency_paths = self._shortcut_dependency_paths(dependency_paths_raw)
+            dependency_paths = shortcut_dependency_paths(dependency_paths_raw)
 
         row = [
             detection.detection_details.get('file_name'),
             detection.detection_details.get('ecosystem'),
             detection.detection_details.get('package_name'),
             detection.detection_details.get('is_direct_dependency_str'),
             detection.detection_details.get('is_dev_dependency_str'),
-            dependency_paths,
+            dependency_paths
         ]
 
         if self._is_git_repository():
             row = [detection.detection_details.get('repository_name')] + row
 
         return row
```

### Comparing `cycode-0.2.6.dev4/cycode/cli/printers/table.py` & `cycode-0.2.6.dev5/cycode/cli/printers/table.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cli/printers/table_printer.py` & `cycode-0.2.6.dev5/cycode/cli/printers/table_printer.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cli/printers/text_printer.py` & `cycode-0.2.6.dev5/cycode/cli/printers/text_printer.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cli/user_settings/base_file_manager.py` & `cycode-0.2.6.dev5/cycode/cli/user_settings/base_file_manager.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cli/user_settings/config_file_manager.py` & `cycode-0.2.6.dev5/cycode/cli/user_settings/config_file_manager.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cli/user_settings/configuration_manager.py` & `cycode-0.2.6.dev5/cycode/cli/user_settings/configuration_manager.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cli/user_settings/credentials_manager.py` & `cycode-0.2.6.dev5/cycode/cli/user_settings/credentials_manager.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cli/user_settings/user_settings_commands.py` & `cycode-0.2.6.dev5/cycode/cli/user_settings/user_settings_commands.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cli/utils/path_utils.py` & `cycode-0.2.6.dev5/cycode/cli/utils/path_utils.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cli/utils/shell_executor.py` & `cycode-0.2.6.dev5/cycode/cli/utils/shell_executor.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cli/utils/task_timer.py` & `cycode-0.2.6.dev5/cycode/cli/utils/task_timer.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cli/utils/yaml_utils.py` & `cycode-0.2.6.dev5/cycode/cli/utils/yaml_utils.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cli/zip_file.py` & `cycode-0.2.6.dev5/cycode/cli/zip_file.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cyclient/auth_client.py` & `cycode-0.2.6.dev5/cycode/cyclient/auth_client.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cyclient/config.py` & `cycode-0.2.6.dev5/cycode/cyclient/config.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cyclient/cycode_client_base.py` & `cycode-0.2.6.dev5/cycode/cyclient/cycode_client_base.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cyclient/cycode_dev_based_client.py` & `cycode-0.2.6.dev5/cycode/cyclient/cycode_dev_based_client.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cyclient/cycode_token_based_client.py` & `cycode-0.2.6.dev5/cycode/cyclient/cycode_token_based_client.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cyclient/models.py` & `cycode-0.2.6.dev5/cycode/cyclient/models.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cyclient/scan_client.py` & `cycode-0.2.6.dev5/cycode/cyclient/scan_client.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cyclient/scan_config/scan_config_base.py` & `cycode-0.2.6.dev5/cycode/cyclient/scan_config/scan_config_base.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/cycode/cyclient/scan_config/scan_config_creator.py` & `cycode-0.2.6.dev5/cycode/cyclient/scan_config/scan_config_creator.py`

 * *Files identical despite different names*

### Comparing `cycode-0.2.6.dev4/pyproject.toml` & `cycode-0.2.6.dev5/pyproject.toml`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "cycode"
-version = "0.2.6.dev4" # DON'T TOUCH. Placeholder. Will be filled automatically on poetry build from Git Tag
+version = "0.2.6.dev5" # DON'T TOUCH. Placeholder. Will be filled automatically on poetry build from Git Tag
 description = "Perform secrets/iac scans for your sources using Cycode's engine"
 keywords=["secret-scan", "cycode", "devops", "token", "secret", "security", "cycode", "code"]
 authors = ["Cycode <support@cycode.com>"]
 license = "MIT"
 repository = "https://github.com/cycodehq-public/cycode-cli"
 readme = "README.md"
 classifiers = [
```

### Comparing `cycode-0.2.6.dev4/PKG-INFO` & `cycode-0.2.6.dev5/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: cycode
-Version: 0.2.6.dev4
+Version: 0.2.6.dev5
 Summary: Perform secrets/iac scans for your sources using Cycode's engine
 Home-page: https://github.com/cycodehq-public/cycode-cli
 License: MIT
 Keywords: secret-scan,cycode,devops,token,secret,security,cycode,code
 Author: Cycode
 Author-email: support@cycode.com
 Requires-Python: >=3.7,<3.12
```


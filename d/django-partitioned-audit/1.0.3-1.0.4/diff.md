# Comparing `tmp/django-partitioned-audit-1.0.3.tar.gz` & `tmp/django-partitioned-audit-1.0.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "django-partitioned-audit-1.0.3.tar", last modified: Fri Jun 23 11:14:14 2023, max compression
+gzip compressed data, was "django-partitioned-audit-1.0.4.tar", last modified: Wed Jun 28 15:23:50 2023, max compression
```

## Comparing `django-partitioned-audit-1.0.3.tar` & `django-partitioned-audit-1.0.4.tar`

### file list

```diff
@@ -1,99 +1,122 @@
-drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-23 11:14:14.472311 django-partitioned-audit-1.0.3/
--rw-rw-r--   0 horacio   (1000) horacio   (1000)      496 2023-06-23 11:14:12.000000 django-partitioned-audit-1.0.3/.bumpversion.cfg
--rw-rw-r--   0 horacio   (1000) horacio   (1000)      102 2023-06-23 10:21:10.000000 django-partitioned-audit-1.0.3/.gitignore
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     1721 2023-06-23 09:24:58.000000 django-partitioned-audit-1.0.3/.pre-commit-config.yaml
--rw-rw-r--   0 horacio   (1000) horacio   (1000)      375 2023-06-15 08:58:25.000000 django-partitioned-audit-1.0.3/.pylintrc
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     1510 2023-06-15 05:52:04.000000 django-partitioned-audit-1.0.3/LICENSE
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     6130 2023-06-23 11:13:37.000000 django-partitioned-audit-1.0.3/Makefile
--rw-rw-r--   0 horacio   (1000) horacio   (1000)    14316 2023-06-23 11:14:14.472311 django-partitioned-audit-1.0.3/PKG-INFO
--rw-rw-r--   0 horacio   (1000) horacio   (1000)    13177 2023-06-23 11:13:42.000000 django-partitioned-audit-1.0.3/README.rst
-drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-23 11:14:14.468311 django-partitioned-audit-1.0.3/django_partitioned_audit/
--rw-rw-r--   0 horacio   (1000) horacio   (1000)       81 2023-06-23 09:23:18.000000 django-partitioned-audit-1.0.3/django_partitioned_audit/__init__.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     1143 2023-06-19 14:27:17.000000 django-partitioned-audit-1.0.3/django_partitioned_audit/admin.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)      155 2023-06-23 09:23:18.000000 django-partitioned-audit-1.0.3/django_partitioned_audit/apps.py
-drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-23 11:14:14.468311 django-partitioned-audit-1.0.3/django_partitioned_audit/management/
--rw-rw-r--   0 horacio   (1000) horacio   (1000)        0 2023-06-19 14:27:17.000000 django-partitioned-audit-1.0.3/django_partitioned_audit/management/__init__.py
-drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-23 11:14:14.468311 django-partitioned-audit-1.0.3/django_partitioned_audit/management/commands/
--rw-rw-r--   0 horacio   (1000) horacio   (1000)        0 2023-06-19 14:27:17.000000 django-partitioned-audit-1.0.3/django_partitioned_audit/management/commands/__init__.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     5455 2023-06-23 09:23:18.000000 django-partitioned-audit-1.0.3/django_partitioned_audit/management/commands/manage_partition_tables.py
-drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-23 11:14:14.468311 django-partitioned-audit-1.0.3/django_partitioned_audit/migrations/
--rw-rw-r--   0 horacio   (1000) horacio   (1000)      984 2023-06-19 14:27:17.000000 django-partitioned-audit-1.0.3/django_partitioned_audit/migrations/0001_initial.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     1989 2023-06-23 09:23:18.000000 django-partitioned-audit-1.0.3/django_partitioned_audit/migrations/0002_trigger_audit_entry_creator_func_v2.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)        0 2023-06-14 07:42:31.000000 django-partitioned-audit-1.0.3/django_partitioned_audit/migrations/__init__.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     1418 2023-06-23 09:23:18.000000 django-partitioned-audit-1.0.3/django_partitioned_audit/models.py
-drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-23 11:14:14.468311 django-partitioned-audit-1.0.3/django_partitioned_audit/partitions/
--rw-rw-r--   0 horacio   (1000) horacio   (1000)        0 2023-06-19 14:27:17.000000 django-partitioned-audit-1.0.3/django_partitioned_audit/partitions/__init__.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     2966 2023-06-23 09:18:01.000000 django-partitioned-audit-1.0.3/django_partitioned_audit/partitions/partition_info.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     2997 2023-06-23 09:23:18.000000 django-partitioned-audit-1.0.3/django_partitioned_audit/partitions/partition_manager_base.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     5062 2023-06-23 09:23:18.000000 django-partitioned-audit-1.0.3/django_partitioned_audit/partitions/partition_manager_plan.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     1834 2023-06-23 09:23:18.000000 django-partitioned-audit-1.0.3/django_partitioned_audit/partitions/partition_manager_time_range.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     3011 2023-06-23 09:23:18.000000 django-partitioned-audit-1.0.3/django_partitioned_audit/partitions/time_range_partitioning.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     3373 2023-06-23 09:23:18.000000 django-partitioned-audit-1.0.3/django_partitioned_audit/signals.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)      278 2023-06-15 09:25:46.000000 django-partitioned-audit-1.0.3/django_partitioned_audit/utils.py
-drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-23 11:14:14.468311 django-partitioned-audit-1.0.3/django_partitioned_audit.egg-info/
--rw-rw-r--   0 horacio   (1000) horacio   (1000)    14316 2023-06-23 11:14:14.000000 django-partitioned-audit-1.0.3/django_partitioned_audit.egg-info/PKG-INFO
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     3086 2023-06-23 11:14:14.000000 django-partitioned-audit-1.0.3/django_partitioned_audit.egg-info/SOURCES.txt
--rw-rw-r--   0 horacio   (1000) horacio   (1000)        1 2023-06-23 11:14:14.000000 django-partitioned-audit-1.0.3/django_partitioned_audit.egg-info/dependency_links.txt
--rw-rw-r--   0 horacio   (1000) horacio   (1000)       25 2023-06-23 11:14:14.000000 django-partitioned-audit-1.0.3/django_partitioned_audit.egg-info/top_level.txt
--rw-rw-r--   0 horacio   (1000) horacio   (1000)       99 2023-06-23 10:10:50.000000 django-partitioned-audit-1.0.3/pyproject.toml
--rw-rw-r--   0 horacio   (1000) horacio   (1000)      211 2023-06-19 14:27:17.000000 django-partitioned-audit-1.0.3/pytest.ini
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     1058 2023-06-23 11:14:14.472311 django-partitioned-audit-1.0.3/setup.cfg
--rw-rw-r--   0 horacio   (1000) horacio   (1000)       38 2023-06-14 07:42:31.000000 django-partitioned-audit-1.0.3/setup.py
-drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-23 11:14:14.468311 django-partitioned-audit-1.0.3/tests/
-drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-23 11:14:14.468311 django-partitioned-audit-1.0.3/tests/app_django/
-drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-23 11:14:14.472311 django-partitioned-audit-1.0.3/tests/app_django/app/
--rw-rw-r--   0 horacio   (1000) horacio   (1000)        0 2023-06-19 12:19:35.000000 django-partitioned-audit-1.0.3/tests/app_django/app/__init__.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)      586 2023-06-23 09:23:39.000000 django-partitioned-audit-1.0.3/tests/app_django/app/admin.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)      174 2023-06-19 14:27:17.000000 django-partitioned-audit-1.0.3/tests/app_django/app/apps.py
-drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-23 11:14:14.464311 django-partitioned-audit-1.0.3/tests/app_django/app/management/
-drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-23 11:14:14.472311 django-partitioned-audit-1.0.3/tests/app_django/app/management/commands/
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     4013 2023-06-23 09:23:39.000000 django-partitioned-audit-1.0.3/tests/app_django/app/management/commands/stresstest.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     1314 2023-06-23 09:23:39.000000 django-partitioned-audit-1.0.3/tests/app_django/app/management/commands/update_customer.py
-drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-23 11:14:14.472311 django-partitioned-audit-1.0.3/tests/app_django/app/migrations/
--rw-rw-r--   0 horacio   (1000) horacio   (1000)      568 2023-06-19 12:19:35.000000 django-partitioned-audit-1.0.3/tests/app_django/app/migrations/0001_initial.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)      786 2023-06-19 14:27:17.000000 django-partitioned-audit-1.0.3/tests/app_django/app/migrations/0002_invoice_product.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)        0 2023-06-19 12:19:35.000000 django-partitioned-audit-1.0.3/tests/app_django/app/migrations/__init__.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)      451 2023-06-19 14:27:17.000000 django-partitioned-audit-1.0.3/tests/app_django/app/models.py
-drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-23 11:14:14.468311 django-partitioned-audit-1.0.3/tests/app_django/app/templates/
-drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-23 11:14:14.472311 django-partitioned-audit-1.0.3/tests/app_django/app/templates/app/
--rw-rw-r--   0 horacio   (1000) horacio   (1000)      271 2023-06-19 12:19:35.000000 django-partitioned-audit-1.0.3/tests/app_django/app/templates/app/customer_confirm_delete.html
--rw-rw-r--   0 horacio   (1000) horacio   (1000)      216 2023-06-19 12:19:35.000000 django-partitioned-audit-1.0.3/tests/app_django/app/templates/app/customer_form.html
--rw-rw-r--   0 horacio   (1000) horacio   (1000)      216 2023-06-19 14:27:17.000000 django-partitioned-audit-1.0.3/tests/app_django/app/templates/app/invoice_form.html
--rw-rw-r--   0 horacio   (1000) horacio   (1000)      216 2023-06-19 14:27:17.000000 django-partitioned-audit-1.0.3/tests/app_django/app/templates/app/product_form.html
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     1374 2023-06-19 14:27:17.000000 django-partitioned-audit-1.0.3/tests/app_django/app/views.py
-drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-23 11:14:14.472311 django-partitioned-audit-1.0.3/tests/app_django/config/
--rw-rw-r--   0 horacio   (1000) horacio   (1000)        0 2023-06-19 12:19:35.000000 django-partitioned-audit-1.0.3/tests/app_django/config/__init__.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)      389 2023-06-19 12:19:35.000000 django-partitioned-audit-1.0.3/tests/app_django/config/asgi.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)      521 2023-06-23 09:23:39.000000 django-partitioned-audit-1.0.3/tests/app_django/config/settings.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     1618 2023-06-19 14:27:17.000000 django-partitioned-audit-1.0.3/tests/app_django/config/settings_boilerplate.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)      481 2023-06-23 09:25:39.000000 django-partitioned-audit-1.0.3/tests/app_django/config/settings_postgres12.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)      481 2023-06-23 09:25:39.000000 django-partitioned-audit-1.0.3/tests/app_django/config/settings_postgres13.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)      481 2023-06-23 09:25:39.000000 django-partitioned-audit-1.0.3/tests/app_django/config/settings_postgres14.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)      481 2023-06-23 09:25:39.000000 django-partitioned-audit-1.0.3/tests/app_django/config/settings_postgres15.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)      652 2023-06-19 14:27:17.000000 django-partitioned-audit-1.0.3/tests/app_django/config/tox_settings.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)      582 2023-06-19 14:27:17.000000 django-partitioned-audit-1.0.3/tests/app_django/config/urls.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)      389 2023-06-19 12:19:35.000000 django-partitioned-audit-1.0.3/tests/app_django/config/wsgi.py
--rwxrwxr-x   0 horacio   (1000) horacio   (1000)      626 2023-06-19 12:19:35.000000 django-partitioned-audit-1.0.3/tests/app_django/manage.py
-drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-23 11:14:14.472311 django-partitioned-audit-1.0.3/tests/app_install_test/
-drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-23 11:14:14.472311 django-partitioned-audit-1.0.3/tests/app_install_test/app_install_test_config/
--rw-rw-r--   0 horacio   (1000) horacio   (1000)        0 2023-06-19 14:27:17.000000 django-partitioned-audit-1.0.3/tests/app_install_test/app_install_test_config/__init__.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)      581 2023-06-23 09:23:39.000000 django-partitioned-audit-1.0.3/tests/app_install_test/app_install_test_config/settings.py
--rwxrwxr-x   0 horacio   (1000) horacio   (1000)      643 2023-06-19 14:27:17.000000 django-partitioned-audit-1.0.3/tests/app_install_test/manage.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     3396 2023-06-23 09:23:39.000000 django-partitioned-audit-1.0.3/tests/conftest.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     1309 2023-06-23 09:47:22.000000 django-partitioned-audit-1.0.3/tests/docker-compose.yml
--rw-rw-r--   0 horacio   (1000) horacio   (1000)      292 2023-06-23 10:30:28.000000 django-partitioned-audit-1.0.3/tests/requirements.in
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     3839 2023-06-23 10:30:36.000000 django-partitioned-audit-1.0.3/tests/requirements.txt
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     2066 2023-06-23 09:23:39.000000 django-partitioned-audit-1.0.3/tests/test_audit_events_creation.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     2259 2023-06-23 09:23:39.000000 django-partitioned-audit-1.0.3/tests/test_concurrent.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     3357 2023-06-23 09:23:39.000000 django-partitioned-audit-1.0.3/tests/test_examples_on_readme.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     5966 2023-06-23 09:23:39.000000 django-partitioned-audit-1.0.3/tests/test_management_commands.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     1386 2023-06-23 09:23:39.000000 django-partitioned-audit-1.0.3/tests/test_non_standard_pk.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     2017 2023-06-23 09:23:39.000000 django-partitioned-audit-1.0.3/tests/test_partition_info.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     3022 2023-06-23 09:23:39.000000 django-partitioned-audit-1.0.3/tests/test_partition_manager_base.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     2442 2023-06-23 09:23:39.000000 django-partitioned-audit-1.0.3/tests/test_partition_manager_create.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     6558 2023-06-23 09:23:39.000000 django-partitioned-audit-1.0.3/tests/test_partition_manager_simulate.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     6172 2023-06-23 09:23:39.000000 django-partitioned-audit-1.0.3/tests/test_partition_manager_time_range.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     7551 2023-06-23 09:23:39.000000 django-partitioned-audit-1.0.3/tests/test_partition_manager_time_range_plan.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     1917 2023-06-23 09:23:39.000000 django-partitioned-audit-1.0.3/tests/test_partition_manager_truncate_63.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)     1971 2023-06-23 09:50:20.000000 django-partitioned-audit-1.0.3/tests/test_testing_app_without_audit.py
--rw-rw-r--   0 horacio   (1000) horacio   (1000)      449 2023-06-23 08:17:07.000000 django-partitioned-audit-1.0.3/tox.ini
+drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-28 15:23:50.869741 django-partitioned-audit-1.0.4/
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      496 2023-06-28 15:23:48.000000 django-partitioned-audit-1.0.4/.bumpversion.cfg
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      102 2023-06-23 10:21:10.000000 django-partitioned-audit-1.0.4/.gitignore
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     1493 2023-06-23 19:49:09.000000 django-partitioned-audit-1.0.4/.gitlab-ci.yml
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     1721 2023-06-23 09:24:58.000000 django-partitioned-audit-1.0.4/.pre-commit-config.yaml
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      375 2023-06-15 08:58:25.000000 django-partitioned-audit-1.0.4/.pylintrc
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     1510 2023-06-15 05:52:04.000000 django-partitioned-audit-1.0.4/LICENSE
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     6506 2023-06-23 19:45:17.000000 django-partitioned-audit-1.0.4/Makefile
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)    13857 2023-06-28 15:23:50.869741 django-partitioned-audit-1.0.4/PKG-INFO
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)    12718 2023-06-28 05:29:40.000000 django-partitioned-audit-1.0.4/README.rst
+drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-28 15:23:50.861741 django-partitioned-audit-1.0.4/django_partitioned_audit/
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)       81 2023-06-23 09:23:18.000000 django-partitioned-audit-1.0.4/django_partitioned_audit/__init__.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     1143 2023-06-19 14:27:17.000000 django-partitioned-audit-1.0.4/django_partitioned_audit/admin.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      155 2023-06-23 09:23:18.000000 django-partitioned-audit-1.0.4/django_partitioned_audit/apps.py
+drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-28 15:23:50.865741 django-partitioned-audit-1.0.4/django_partitioned_audit/audit_table/
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)        0 2023-06-25 08:11:44.000000 django-partitioned-audit-1.0.4/django_partitioned_audit/audit_table/__init__.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)    11819 2023-06-26 21:13:46.000000 django-partitioned-audit-1.0.4/django_partitioned_audit/audit_table/advanced_audit_table_manager.original.sql
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     4382 2023-06-28 13:11:05.000000 django-partitioned-audit-1.0.4/django_partitioned_audit/audit_table/advanced_audit_table_manager.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)    11482 2023-06-27 17:47:20.000000 django-partitioned-audit-1.0.4/django_partitioned_audit/audit_table/advanced_audit_table_manager.sql
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     1942 2023-06-28 07:05:28.000000 django-partitioned-audit-1.0.4/django_partitioned_audit/audit_table/audit_table_manager.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     5948 2023-06-28 13:11:06.000000 django-partitioned-audit-1.0.4/django_partitioned_audit/audit_table/simple_audit_table_manager.py
+drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-28 15:23:50.865741 django-partitioned-audit-1.0.4/django_partitioned_audit/management/
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)        0 2023-06-19 14:27:17.000000 django-partitioned-audit-1.0.4/django_partitioned_audit/management/__init__.py
+drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-28 15:23:50.865741 django-partitioned-audit-1.0.4/django_partitioned_audit/management/commands/
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)        0 2023-06-19 14:27:17.000000 django-partitioned-audit-1.0.4/django_partitioned_audit/management/commands/__init__.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     5142 2023-06-26 16:20:10.000000 django-partitioned-audit-1.0.4/django_partitioned_audit/management/commands/manage_partition_tables.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     7542 2023-06-27 21:45:51.000000 django-partitioned-audit-1.0.4/django_partitioned_audit/models.py
+drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-28 15:23:50.865741 django-partitioned-audit-1.0.4/django_partitioned_audit/partitions/
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)        0 2023-06-19 14:27:17.000000 django-partitioned-audit-1.0.4/django_partitioned_audit/partitions/__init__.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     2489 2023-06-26 21:07:39.000000 django-partitioned-audit-1.0.4/django_partitioned_audit/partitions/partition_info.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     3085 2023-06-27 10:15:53.000000 django-partitioned-audit-1.0.4/django_partitioned_audit/partitions/partition_manager_base.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     5062 2023-06-23 09:23:18.000000 django-partitioned-audit-1.0.4/django_partitioned_audit/partitions/partition_manager_plan.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     1834 2023-06-23 09:23:18.000000 django-partitioned-audit-1.0.4/django_partitioned_audit/partitions/partition_manager_time_range.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     3011 2023-06-23 09:23:18.000000 django-partitioned-audit-1.0.4/django_partitioned_audit/partitions/time_range_partitioning.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     2965 2023-06-27 08:12:39.000000 django-partitioned-audit-1.0.4/django_partitioned_audit/signals.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      476 2023-06-25 09:43:32.000000 django-partitioned-audit-1.0.4/django_partitioned_audit/utils.py
+drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-28 15:23:50.861741 django-partitioned-audit-1.0.4/django_partitioned_audit.egg-info/
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)    13857 2023-06-28 15:23:50.000000 django-partitioned-audit-1.0.4/django_partitioned_audit.egg-info/PKG-INFO
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     3906 2023-06-28 15:23:50.000000 django-partitioned-audit-1.0.4/django_partitioned_audit.egg-info/SOURCES.txt
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)        1 2023-06-28 15:23:50.000000 django-partitioned-audit-1.0.4/django_partitioned_audit.egg-info/dependency_links.txt
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)       25 2023-06-28 15:23:50.000000 django-partitioned-audit-1.0.4/django_partitioned_audit.egg-info/top_level.txt
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)       99 2023-06-23 10:10:50.000000 django-partitioned-audit-1.0.4/pyproject.toml
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      211 2023-06-19 14:27:17.000000 django-partitioned-audit-1.0.4/pytest.ini
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     1058 2023-06-28 15:23:50.873742 django-partitioned-audit-1.0.4/setup.cfg
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)       38 2023-06-14 07:42:31.000000 django-partitioned-audit-1.0.4/setup.py
+drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-28 15:23:50.869741 django-partitioned-audit-1.0.4/tests/
+drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-28 15:23:50.869741 django-partitioned-audit-1.0.4/tests/app_django/
+drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-28 15:23:50.869741 django-partitioned-audit-1.0.4/tests/app_django/app/
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)        0 2023-06-19 12:19:35.000000 django-partitioned-audit-1.0.4/tests/app_django/app/__init__.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      584 2023-06-27 16:52:51.000000 django-partitioned-audit-1.0.4/tests/app_django/app/admin.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      226 2023-06-25 09:49:52.000000 django-partitioned-audit-1.0.4/tests/app_django/app/apps.py
+drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-28 15:23:50.861741 django-partitioned-audit-1.0.4/tests/app_django/app/management/
+drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-28 15:23:50.869741 django-partitioned-audit-1.0.4/tests/app_django/app/management/commands/
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     4005 2023-06-28 14:11:26.000000 django-partitioned-audit-1.0.4/tests/app_django/app/management/commands/stresstest.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     1312 2023-06-27 16:52:51.000000 django-partitioned-audit-1.0.4/tests/app_django/app/management/commands/update_customer.py
+drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-28 15:23:50.869741 django-partitioned-audit-1.0.4/tests/app_django/app/migrations/
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      568 2023-06-19 12:19:35.000000 django-partitioned-audit-1.0.4/tests/app_django/app/migrations/0001_initial.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      786 2023-06-19 14:27:17.000000 django-partitioned-audit-1.0.4/tests/app_django/app/migrations/0002_invoice_product.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      532 2023-06-25 11:43:16.000000 django-partitioned-audit-1.0.4/tests/app_django/app/migrations/0003_invoiceitem.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)        0 2023-06-19 12:19:35.000000 django-partitioned-audit-1.0.4/tests/app_django/app/migrations/__init__.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      530 2023-06-25 09:49:52.000000 django-partitioned-audit-1.0.4/tests/app_django/app/models.py
+drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-28 15:23:50.861741 django-partitioned-audit-1.0.4/tests/app_django/app/templates/
+drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-28 15:23:50.869741 django-partitioned-audit-1.0.4/tests/app_django/app/templates/app/
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      271 2023-06-19 12:19:35.000000 django-partitioned-audit-1.0.4/tests/app_django/app/templates/app/customer_confirm_delete.html
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      216 2023-06-19 12:19:35.000000 django-partitioned-audit-1.0.4/tests/app_django/app/templates/app/customer_form.html
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      216 2023-06-19 14:27:17.000000 django-partitioned-audit-1.0.4/tests/app_django/app/templates/app/invoice_form.html
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      216 2023-06-19 14:27:17.000000 django-partitioned-audit-1.0.4/tests/app_django/app/templates/app/product_form.html
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     1374 2023-06-19 14:27:17.000000 django-partitioned-audit-1.0.4/tests/app_django/app/views.py
+drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-28 15:23:50.869741 django-partitioned-audit-1.0.4/tests/app_django/config/
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)        0 2023-06-19 12:19:35.000000 django-partitioned-audit-1.0.4/tests/app_django/config/__init__.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      389 2023-06-19 12:19:35.000000 django-partitioned-audit-1.0.4/tests/app_django/config/asgi.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      501 2023-06-23 12:03:47.000000 django-partitioned-audit-1.0.4/tests/app_django/config/ci_settings.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      772 2023-06-28 07:02:02.000000 django-partitioned-audit-1.0.4/tests/app_django/config/settings.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     1618 2023-06-19 14:27:17.000000 django-partitioned-audit-1.0.4/tests/app_django/config/settings_boilerplate.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      481 2023-06-23 09:25:39.000000 django-partitioned-audit-1.0.4/tests/app_django/config/settings_postgres12.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      481 2023-06-23 09:25:39.000000 django-partitioned-audit-1.0.4/tests/app_django/config/settings_postgres13.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      481 2023-06-23 09:25:39.000000 django-partitioned-audit-1.0.4/tests/app_django/config/settings_postgres14.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      481 2023-06-23 09:25:39.000000 django-partitioned-audit-1.0.4/tests/app_django/config/settings_postgres15.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      652 2023-06-19 14:27:17.000000 django-partitioned-audit-1.0.4/tests/app_django/config/tox_settings.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      582 2023-06-19 14:27:17.000000 django-partitioned-audit-1.0.4/tests/app_django/config/urls.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      389 2023-06-19 12:19:35.000000 django-partitioned-audit-1.0.4/tests/app_django/config/wsgi.py
+-rwxrwxr-x   0 horacio   (1000) horacio   (1000)      626 2023-06-19 12:19:35.000000 django-partitioned-audit-1.0.4/tests/app_django/manage.py
+drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-28 15:23:50.869741 django-partitioned-audit-1.0.4/tests/app_django/second_app/
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)        0 2023-06-19 12:19:35.000000 django-partitioned-audit-1.0.4/tests/app_django/second_app/__init__.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      190 2023-06-23 20:49:21.000000 django-partitioned-audit-1.0.4/tests/app_django/second_app/apps.py
+drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-28 15:23:50.869741 django-partitioned-audit-1.0.4/tests/app_django/second_app/migrations/
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     1115 2023-06-23 20:50:50.000000 django-partitioned-audit-1.0.4/tests/app_django/second_app/migrations/0001_initial.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)        0 2023-06-19 12:19:35.000000 django-partitioned-audit-1.0.4/tests/app_django/second_app/migrations/__init__.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      489 2023-06-23 20:50:50.000000 django-partitioned-audit-1.0.4/tests/app_django/second_app/models.py
+drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-28 15:23:50.869741 django-partitioned-audit-1.0.4/tests/app_install_test/
+drwxrwxr-x   0 horacio   (1000) horacio   (1000)        0 2023-06-28 15:23:50.869741 django-partitioned-audit-1.0.4/tests/app_install_test/app_install_test_config/
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)        0 2023-06-19 14:27:17.000000 django-partitioned-audit-1.0.4/tests/app_install_test/app_install_test_config/__init__.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      612 2023-06-27 13:41:17.000000 django-partitioned-audit-1.0.4/tests/app_install_test/app_install_test_config/settings.py
+-rwxrwxr-x   0 horacio   (1000) horacio   (1000)      643 2023-06-19 14:27:17.000000 django-partitioned-audit-1.0.4/tests/app_install_test/manage.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     6976 2023-06-28 14:18:09.000000 django-partitioned-audit-1.0.4/tests/conftest.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     1309 2023-06-23 09:47:22.000000 django-partitioned-audit-1.0.4/tests/docker-compose.yml
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     1060 2023-06-28 13:11:06.000000 django-partitioned-audit-1.0.4/tests/dummies.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)       37 2023-06-23 19:46:58.000000 django-partitioned-audit-1.0.4/tests/requirements-ci.in
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     1675 2023-06-23 19:47:05.000000 django-partitioned-audit-1.0.4/tests/requirements-ci.txt
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      150 2023-06-23 19:46:58.000000 django-partitioned-audit-1.0.4/tests/requirements-dev.in
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     4308 2023-06-23 19:47:07.000000 django-partitioned-audit-1.0.4/tests/requirements-dev.txt
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      145 2023-06-23 19:45:17.000000 django-partitioned-audit-1.0.4/tests/requirements-test.in
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      808 2023-06-23 19:47:04.000000 django-partitioned-audit-1.0.4/tests/requirements-test.txt
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     3055 2023-06-27 21:23:11.000000 django-partitioned-audit-1.0.4/tests/test_audit_events_creation.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     1315 2023-06-27 21:13:41.000000 django-partitioned-audit-1.0.4/tests/test_audit_events_deletion.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     6255 2023-06-28 14:30:14.000000 django-partitioned-audit-1.0.4/tests/test_audit_events_select.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     3437 2023-06-27 20:23:17.000000 django-partitioned-audit-1.0.4/tests/test_audit_table_manager.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     2308 2023-06-28 14:23:22.000000 django-partitioned-audit-1.0.4/tests/test_concurrent.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     3353 2023-06-23 22:10:36.000000 django-partitioned-audit-1.0.4/tests/test_examples_on_readme.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     6384 2023-06-26 16:29:10.000000 django-partitioned-audit-1.0.4/tests/test_management_commands.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     1435 2023-06-28 14:11:26.000000 django-partitioned-audit-1.0.4/tests/test_non_standard_pk.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     2013 2023-06-26 21:05:50.000000 django-partitioned-audit-1.0.4/tests/test_partition_info.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     3356 2023-06-28 13:48:17.000000 django-partitioned-audit-1.0.4/tests/test_partition_manager_base.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     2531 2023-06-26 16:06:22.000000 django-partitioned-audit-1.0.4/tests/test_partition_manager_create.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     6436 2023-06-28 13:49:38.000000 django-partitioned-audit-1.0.4/tests/test_partition_manager_simulate.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     6465 2023-06-26 16:06:22.000000 django-partitioned-audit-1.0.4/tests/test_partition_manager_time_range.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     7551 2023-06-23 09:23:39.000000 django-partitioned-audit-1.0.4/tests/test_partition_manager_time_range_plan.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     2033 2023-06-26 16:06:22.000000 django-partitioned-audit-1.0.4/tests/test_partition_manager_truncate_63.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     2021 2023-06-28 13:52:43.000000 django-partitioned-audit-1.0.4/tests/test_signals.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     1967 2023-06-28 14:05:13.000000 django-partitioned-audit-1.0.4/tests/test_testing_app_without_audit.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)     2645 2023-06-28 14:18:16.000000 django-partitioned-audit-1.0.4/tests/test_two_apps.py
+-rw-rw-r--   0 horacio   (1000) horacio   (1000)      627 2023-06-28 14:23:04.000000 django-partitioned-audit-1.0.4/tox.ini
```

### Comparing `django-partitioned-audit-1.0.3/.pre-commit-config.yaml` & `django-partitioned-audit-1.0.4/.pre-commit-config.yaml`

 * *Files identical despite different names*

### Comparing `django-partitioned-audit-1.0.3/LICENSE` & `django-partitioned-audit-1.0.4/LICENSE`

 * *Files identical despite different names*

### Comparing `django-partitioned-audit-1.0.3/Makefile` & `django-partitioned-audit-1.0.4/Makefile`

 * *Files 8% similar despite different names*

```diff
@@ -70,21 +70,25 @@
   	fi
 	$(VENVDIR)/bin/pip install --upgrade setuptools pip pip-tools
 	$(MAKE) pip-sync
 	# https://setuptools.readthedocs.io/en/latest/userguide/quickstart.html#development-mode
 	$(VENVDIR)/bin/pip install --editable .
 
 pip-compile:
-	$(VENVDIR)/bin/pip-compile -o tests/requirements.txt tests/requirements.in
+	$(VENVDIR)/bin/pip-compile -o tests/requirements-test.txt tests/requirements-test.in
+	$(VENVDIR)/bin/pip-compile -o tests/requirements-ci.txt tests/requirements-ci.in
+	$(VENVDIR)/bin/pip-compile -o tests/requirements-dev.txt tests/requirements-dev.in
 
 pip-compile-upgrade:
-	$(VENVDIR)/bin/pip-compile --upgrade -o tests/requirements.txt tests/requirements.in
+	$(VENVDIR)/bin/pip-compile --upgrade -o tests/requirements-test.txt tests/requirements-test.in
+	$(VENVDIR)/bin/pip-compile --upgrade -o tests/requirements-ci.txt tests/requirements-ci.in
+	$(VENVDIR)/bin/pip-compile --upgrade -o tests/requirements-dev.txt tests/requirements-dev.in
 
 pip-sync:
-	$(VENVDIR)/bin/pip-sync tests/requirements.txt
+	$(VENVDIR)/bin/pip-sync tests/requirements-dev.txt
 
 pip-compile-sync: pip-compile pip-sync
 
 pre-commit-all-files:
 	$(VENVDIR)/bin/pre-commit run --all-files
 
 pylint:
```

### Comparing `django-partitioned-audit-1.0.3/PKG-INFO` & `django-partitioned-audit-1.0.4/PKG-INFO`

 * *Files 11% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: django-partitioned-audit
-Version: 1.0.3
+Version: 1.0.4
 Summary: Keep audit log based on PostgreSql triggers and partitioned tables
 Home-page: https://gitlab.com/hgdeoro/django-partitioned-audit
 Author: Horacio G. de Oro
 Author-email: hgdeoro@gmail.com
 License: BSD-3-Clause
 Classifier: Development Status :: 4 - Beta
 Classifier: Environment :: Web Environment
@@ -28,48 +28,51 @@
 
 ========================
 django-partitioned-audit
 ========================
 
 Creates an audit log of the modifications made to models, by using triggers.
 
-* Only PostgreSql supported.
+* Only PostgreSql supported
 * Models to audit are configured in ``AppConfig``
-* Triggers are applied automatically when running ``python manage.py migrate``
-* The whole row is saved by the trigger by using PostgreSql's ``row_to_json()``
+* Triggers are created automatically when running ``python manage.py migrate``
+* The whole row is saved by the trigger
+* Two different implementations for audit tables (see `SimpleAuditTableManager` and `AdvancedAuditTableManager`)
 * The audit table is partitioned
+* There are 3 partition strategies: one partition per month, one per week, one per day
 * Management command `manage_partition_tables` creates required partitions
-* There are 3 partition strategies: one partition per month, one per week, one per day.
 
-Quick start
------------
+Quick start (SimpleAuditTableManager)
+-------------------------------------
 
 1. Add "django_partitioned_audit" to your INSTALLED_APPS setting like this::
 
     INSTALLED_APPS = [
         ...
         'django_partitioned_audit',
 
         'your.app1.App1Config',
         'your.app2.App2Config',
         'your.app3.App3Config',
     ]
 
 2. Run ``python manage.py migrate`` to create the partitioned table.
 
+There is no real migration to create the partitioned table. Instead, a `post_migrate` signal is used.
+
 3. Run ``manage.py manage_partition_tables create --extra-days=60`` to create the partitions::
 
     $ manage.py manage_partition_tables create --extra-days=60
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  table_name                                  |  from_date   |  to_date     |  status       |
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  trigger_audit_entries_v2_20220201_20220301  |  2022-02-01  |  2022-03-01  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220301_20220401  |  2022-03-01  |  2022-04-01  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220401_20220501  |  2022-04-01  |  2022-05-01  |  ⚠ to create  |
-    +----------------------------------------------+--------------+--------------+---------------+
+    +----------------------------------+--------------+--------------+---------------+
+    |  table_name                      |  from_date   |  to_date     |  status       |
+    +----------------------------------+--------------+--------------+---------------+
+    |  audit_simple_20220201_20220301  |  2022-02-01  |  2022-03-01  |  ⚠ to create  |
+    |  audit_simple_20220301_20220401  |  2022-03-01  |  2022-04-01  |  ⚠ to create  |
+    |  audit_simple_20220401_20220501  |  2022-04-01  |  2022-05-01  |  ⚠ to create  |
+    +----------------------------------+--------------+--------------+---------------+
 
 You should run that command periodically, to make sure the database always contains a partition where to insert data.
 
 4. Register the models you want to audit in your ``AppConfig`` instances::
 
     from django.apps import AppConfig
     class MyAppConfig(AppConfig):
@@ -79,14 +82,32 @@
             'Model2',
             'Model3',
         )
 
 5. Run ``python manage.py migrate`` to create the triggers.
 
 
+Quick start (AdvancedAuditTableManager)
+---------------------------------------
+
+There is a second implementation of the audit table that can be used, based on:
+
+- https://wiki.postgresql.org/wiki/Audit_trigger_91plus
+- https://github.com/2ndQuadrant/audit-trigger
+
+The code can be seen at `django_partitioned_audit.audit_table.advanced_audit_table_manager.AdvancedAuditTableManager`.
+
+To use this implementation, you can reference that class in `settings.py`::
+
+    DPA_AUDIT_TABLE_MANAGER = "django_partitioned_audit.audit_table.advanced_audit_table_manager.AdvancedAuditTableManager"
+
+and follow the steps described above, at `Quick start (SimpleAuditTableManager)`.
+
+This implementation also audit `TRUNCATE` operations.
+
 Security of audit entries
 +++++++++++++++++++++++++
 
 DBA should correctly configure permissions, in a way that the user used to
 connect to the database from Django has permissions to INSERT rows in the
 ``trigger_audit_entries`` table, but NO permissions to UPDATE / DELETE them.
 
@@ -132,29 +153,27 @@
                 object_payload  = row_to_json(NEW);
             ELSIF (TG_OP = 'DELETE') THEN
                 object_payload  = row_to_json(OLD);
             ELSE
                 RAISE EXCEPTION 'Unexpected TG_OP = %', TG_OP;
             END IF;
 
-            INSERT INTO trigger_audit_entries_v2 (
+            INSERT INTO audit_simple (
                     object_table,
                     object_payload,
                     audit_entry_created,
                     audit_txid_current,
-                    audit_operation,
-                    audit_version
+                    audit_operation
                 )
                 SELECT
                     TG_TABLE_NAME,
                     object_payload,
                     now(),
                     txid_current(),
-                    TG_OP,
-                    2;
+                    TG_OP;
             RETURN NULL;
         END;
     $scr$ LANGUAGE plpgsql;
 
 Management of partitions
 ------------------------
 
@@ -165,120 +184,116 @@
 
 If you want to have enough partition to handle next 90 days (around 3 months), you can use `--extra-days=90`.
 Because it's the first time we run the command, no partition exists, and the plan will report that all
 partitions need to be created::
 
 
     $ manage.py manage_partition_tables simulate --extra-days=90
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  table_name                                  |  from_date   |  to_date     |  status       |
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  trigger_audit_entries_v2_20220201_20220301  |  2022-02-01  |  2022-03-01  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220301_20220401  |  2022-03-01  |  2022-04-01  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220401_20220501  |  2022-04-01  |  2022-05-01  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220501_20220601  |  2022-05-01  |  2022-06-01  |  ⚠ to create  |
-    +----------------------------------------------+--------------+--------------+---------------+
+    +----------------------------------+--------------+--------------+---------------+
+    |  table_name                      |  from_date   |  to_date     |  status       |
+    +----------------------------------+--------------+--------------+---------------+
+    |  audit_simple_20220201_20220301  |  2022-02-01  |  2022-03-01  |  ⚠ to create  |
+    |  audit_simple_20220301_20220401  |  2022-03-01  |  2022-04-01  |  ⚠ to create  |
+    |  audit_simple_20220401_20220501  |  2022-04-01  |  2022-05-01  |  ⚠ to create  |
+    |  audit_simple_20220501_20220601  |  2022-05-01  |  2022-06-01  |  ⚠ to create  |
+    +----------------------------------+--------------+--------------+---------------+
 
 
 We can also see the plan if no extra days are requested (this way, we'll only create partitions for
 the current month::
 
 
     $ manage.py manage_partition_tables simulate --extra-days=0
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  table_name                                  |  from_date   |  to_date     |  status       |
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  trigger_audit_entries_v2_20220201_20220301  |  2022-02-01  |  2022-03-01  |  ⚠ to create  |
-    +----------------------------------------------+--------------+--------------+---------------+
+    +----------------------------------+--------------+--------------+---------------+
+    |  table_name                      |  from_date   |  to_date     |  status       |
+    +----------------------------------+--------------+--------------+---------------+
+    |  audit_simple_20220201_20220301  |  2022-02-01  |  2022-03-01  |  ⚠ to create  |
+    +----------------------------------+--------------+--------------+---------------+
 
 
 Now let's create the partitions::
 
 
     $ manage.py manage_partition_tables create --extra-days=0
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  table_name                                  |  from_date   |  to_date     |  status       |
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  trigger_audit_entries_v2_20220201_20220301  |  2022-02-01  |  2022-03-01  |  ⚠ to create  |
-    +----------------------------------------------+--------------+--------------+---------------+
-    sql: CREATE TABLE "trigger_audit_entries_v2_20220201_20220301" PARTITION OF "trigger_audit_entries_v2" FOR VALUES FROM (%s) TO (%s); / params: [datetime.date(2022, 2, 1), datetime.date(2022, 3, 1)]
+    +----------------------------------+--------------+--------------+---------------+
+    |  table_name                      |  from_date   |  to_date     |  status       |
+    +----------------------------------+--------------+--------------+---------------+
+    |  audit_simple_20220201_20220301  |  2022-02-01  |  2022-03-01  |  ⚠ to create  |
+    +----------------------------------+--------------+--------------+---------------+
 
 
 If we run the command and we pass `--extra-days=90`, the partition for the current month already exists, and
 only partitions for next months (to cover 90 days) will be created::
 
 
     $ manage.py manage_partition_tables create --extra-days=90
-    +----------------------------------------------+--------------+--------------+----------------+
-    |  table_name                                  |  from_date   |  to_date     |  status        |
-    +----------------------------------------------+--------------+--------------+----------------+
-    |  trigger_audit_entries_v2_20220201_20220301  |  2022-02-01  |  2022-03-01  |  ✓ exists      |
-    |  trigger_audit_entries_v2_20220301_20220401  |  2022-03-01  |  2022-04-01  |  ❌ to create  |
-    |  trigger_audit_entries_v2_20220401_20220501  |  2022-04-01  |  2022-05-01  |  ❌ to create  |
-    |  trigger_audit_entries_v2_20220501_20220601  |  2022-05-01  |  2022-06-01  |  ❌ to create  |
-    +----------------------------------------------+--------------+--------------+----------------+
-    sql: CREATE TABLE "trigger_audit_entries_v2_20220301_20220401" PARTITION OF "trigger_audit_entries_v2" FOR VALUES FROM (%s) TO (%s); / params: [datetime.date(2022, 3, 1), datetime.date(2022, 4, 1)]
-    sql: CREATE TABLE "trigger_audit_entries_v2_20220401_20220501" PARTITION OF "trigger_audit_entries_v2" FOR VALUES FROM (%s) TO (%s); / params: [datetime.date(2022, 4, 1), datetime.date(2022, 5, 1)]
-    sql: CREATE TABLE "trigger_audit_entries_v2_20220501_20220601" PARTITION OF "trigger_audit_entries_v2" FOR VALUES FROM (%s) TO (%s); / params: [datetime.date(2022, 5, 1), datetime.date(2022, 6, 1)]
+    +----------------------------------+--------------+--------------+----------------+
+    |  table_name                      |  from_date   |  to_date     |  status        |
+    +----------------------------------+--------------+--------------+----------------+
+    |  audit_simple_20220201_20220301  |  2022-02-01  |  2022-03-01  |  ✓ exists      |
+    |  audit_simple_20220301_20220401  |  2022-03-01  |  2022-04-01  |  ❌ to create  |
+    |  audit_simple_20220401_20220501  |  2022-04-01  |  2022-05-01  |  ❌ to create  |
+    |  audit_simple_20220501_20220601  |  2022-05-01  |  2022-06-01  |  ❌ to create  |
+    +----------------------------------+--------------+--------------+----------------+
 
 
 We can use `list` to list existing partitions::
 
 
     $ manage.py manage_partition_tables list
-    +----------------------------------------------+--------------+--------------+
-    |  table_name                                  |  from_date   |  to_date     |
-    +----------------------------------------------+--------------+--------------+
-    |  trigger_audit_entries_v2_20220201_20220301  |  2022-02-01  |  2022-03-01  |
-    |  trigger_audit_entries_v2_20220301_20220401  |  2022-03-01  |  2022-04-01  |
-    |  trigger_audit_entries_v2_20220401_20220501  |  2022-04-01  |  2022-05-01  |
-    |  trigger_audit_entries_v2_20220501_20220601  |  2022-05-01  |  2022-06-01  |
-    +----------------------------------------------+--------------+--------------+
+    +----------------------------------+--------------+--------------+
+    |  table_name                      |  from_date   |  to_date     |
+    +----------------------------------+--------------+--------------+
+    |  audit_simple_20220201_20220301  |  2022-02-01  |  2022-03-01  |
+    |  audit_simple_20220301_20220401  |  2022-03-01  |  2022-04-01  |
+    |  audit_simple_20220401_20220501  |  2022-04-01  |  2022-05-01  |
+    |  audit_simple_20220501_20220601  |  2022-05-01  |  2022-06-01  |
+    +----------------------------------+--------------+--------------+
 
 
 Partition per week
 ++++++++++++++++++
 
 We can use one partition per week::
 
 
     $ manage.py manage_partition_tables create --extra-days=30 --time-range-generator=WeeklyTimeRangeGenerator
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  table_name                                  |  from_date   |  to_date     |  status       |
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  trigger_audit_entries_v2_20220222_20220301  |  2022-02-22  |  2022-03-01  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220301_20220308  |  2022-03-01  |  2022-03-08  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220308_20220315  |  2022-03-08  |  2022-03-15  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220315_20220322  |  2022-03-15  |  2022-03-22  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220322_20220329  |  2022-03-22  |  2022-03-29  |  ⚠ to create  |
-    +----------------------------------------------+--------------+--------------+---------------+
+    +----------------------------------+--------------+--------------+---------------+
+    |  table_name                      |  from_date   |  to_date     |  status       |
+    +----------------------------------+--------------+--------------+---------------+
+    |  audit_simple_20220222_20220301  |  2022-02-22  |  2022-03-01  |  ⚠ to create  |
+    |  audit_simple_20220301_20220308  |  2022-03-01  |  2022-03-08  |  ⚠ to create  |
+    |  audit_simple_20220308_20220315  |  2022-03-08  |  2022-03-15  |  ⚠ to create  |
+    |  audit_simple_20220315_20220322  |  2022-03-15  |  2022-03-22  |  ⚠ to create  |
+    |  audit_simple_20220322_20220329  |  2022-03-22  |  2022-03-29  |  ⚠ to create  |
+    +----------------------------------+--------------+--------------+---------------+
 
 
 Partition per day
 +++++++++++++++++
 
 We can use one partition per day::
 
 
     $ manage.py manage_partition_tables create --extra-days=10 --time-range-generator=DailyTimeRangeGenerator
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  table_name                                  |  from_date   |  to_date     |  status       |
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  trigger_audit_entries_v2_20220222_20220223  |  2022-02-22  |  2022-02-23  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220223_20220224  |  2022-02-23  |  2022-02-24  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220224_20220225  |  2022-02-24  |  2022-02-25  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220225_20220226  |  2022-02-25  |  2022-02-26  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220226_20220227  |  2022-02-26  |  2022-02-27  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220227_20220228  |  2022-02-27  |  2022-02-28  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220228_20220301  |  2022-02-28  |  2022-03-01  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220301_20220302  |  2022-03-01  |  2022-03-02  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220302_20220303  |  2022-03-02  |  2022-03-03  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220303_20220304  |  2022-03-03  |  2022-03-04  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220304_20220305  |  2022-03-04  |  2022-03-05  |  ⚠ to create  |
-    +----------------------------------------------+--------------+--------------+---------------+
+    +----------------------------------+--------------+--------------+---------------+
+    |  table_name                      |  from_date   |  to_date     |  status       |
+    +----------------------------------+--------------+--------------+---------------+
+    |  audit_simple_20220222_20220223  |  2022-02-22  |  2022-02-23  |  ⚠ to create  |
+    |  audit_simple_20220223_20220224  |  2022-02-23  |  2022-02-24  |  ⚠ to create  |
+    |  audit_simple_20220224_20220225  |  2022-02-24  |  2022-02-25  |  ⚠ to create  |
+    |  audit_simple_20220225_20220226  |  2022-02-25  |  2022-02-26  |  ⚠ to create  |
+    |  audit_simple_20220226_20220227  |  2022-02-26  |  2022-02-27  |  ⚠ to create  |
+    |  audit_simple_20220227_20220228  |  2022-02-27  |  2022-02-28  |  ⚠ to create  |
+    |  audit_simple_20220228_20220301  |  2022-02-28  |  2022-03-01  |  ⚠ to create  |
+    |  audit_simple_20220301_20220302  |  2022-03-01  |  2022-03-02  |  ⚠ to create  |
+    |  audit_simple_20220302_20220303  |  2022-03-02  |  2022-03-03  |  ⚠ to create  |
+    |  audit_simple_20220303_20220304  |  2022-03-03  |  2022-03-04  |  ⚠ to create  |
+    |  audit_simple_20220304_20220305  |  2022-03-04  |  2022-03-05  |  ⚠ to create  |
+    +----------------------------------+--------------+--------------+---------------+
 
 
 Test
 ----
 
 Tested on:
 
@@ -286,11 +301,17 @@
 * Django 3.2, 4.1, 4.2
 * PostgreSql 12, 13, 14, 15
 
 
 Known issues
 ------------
 
+* JAdvancedAuditTableManager: SONB is used as intermediary format in the view & Django models, should be migrated to HSTORE
+* Audit table and other objects are not managed by using Django migrations
 * Not tested with psycopg3
 * Coupled to Django (would be nice if Django is supported but possible to use it without Django)
-* Only a single app can use it (will be solved when decoupled from Django)
 * Works only on default db schema
+* Lack feature: remove old partitions
+
+TODO
+----
+* Refactor responsibilities on `PartitionManager` and `AuditTableManager`
```

### Comparing `django-partitioned-audit-1.0.3/README.rst` & `django-partitioned-audit-1.0.4/README.rst`

 * *Files 15% similar despite different names*

```diff
@@ -1,47 +1,50 @@
 ========================
 django-partitioned-audit
 ========================
 
 Creates an audit log of the modifications made to models, by using triggers.
 
-* Only PostgreSql supported.
+* Only PostgreSql supported
 * Models to audit are configured in ``AppConfig``
-* Triggers are applied automatically when running ``python manage.py migrate``
-* The whole row is saved by the trigger by using PostgreSql's ``row_to_json()``
+* Triggers are created automatically when running ``python manage.py migrate``
+* The whole row is saved by the trigger
+* Two different implementations for audit tables (see `SimpleAuditTableManager` and `AdvancedAuditTableManager`)
 * The audit table is partitioned
+* There are 3 partition strategies: one partition per month, one per week, one per day
 * Management command `manage_partition_tables` creates required partitions
-* There are 3 partition strategies: one partition per month, one per week, one per day.
 
-Quick start
------------
+Quick start (SimpleAuditTableManager)
+-------------------------------------
 
 1. Add "django_partitioned_audit" to your INSTALLED_APPS setting like this::
 
     INSTALLED_APPS = [
         ...
         'django_partitioned_audit',
 
         'your.app1.App1Config',
         'your.app2.App2Config',
         'your.app3.App3Config',
     ]
 
 2. Run ``python manage.py migrate`` to create the partitioned table.
 
+There is no real migration to create the partitioned table. Instead, a `post_migrate` signal is used.
+
 3. Run ``manage.py manage_partition_tables create --extra-days=60`` to create the partitions::
 
     $ manage.py manage_partition_tables create --extra-days=60
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  table_name                                  |  from_date   |  to_date     |  status       |
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  trigger_audit_entries_v2_20220201_20220301  |  2022-02-01  |  2022-03-01  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220301_20220401  |  2022-03-01  |  2022-04-01  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220401_20220501  |  2022-04-01  |  2022-05-01  |  ⚠ to create  |
-    +----------------------------------------------+--------------+--------------+---------------+
+    +----------------------------------+--------------+--------------+---------------+
+    |  table_name                      |  from_date   |  to_date     |  status       |
+    +----------------------------------+--------------+--------------+---------------+
+    |  audit_simple_20220201_20220301  |  2022-02-01  |  2022-03-01  |  ⚠ to create  |
+    |  audit_simple_20220301_20220401  |  2022-03-01  |  2022-04-01  |  ⚠ to create  |
+    |  audit_simple_20220401_20220501  |  2022-04-01  |  2022-05-01  |  ⚠ to create  |
+    +----------------------------------+--------------+--------------+---------------+
 
 You should run that command periodically, to make sure the database always contains a partition where to insert data.
 
 4. Register the models you want to audit in your ``AppConfig`` instances::
 
     from django.apps import AppConfig
     class MyAppConfig(AppConfig):
@@ -51,14 +54,32 @@
             'Model2',
             'Model3',
         )
 
 5. Run ``python manage.py migrate`` to create the triggers.
 
 
+Quick start (AdvancedAuditTableManager)
+---------------------------------------
+
+There is a second implementation of the audit table that can be used, based on:
+
+- https://wiki.postgresql.org/wiki/Audit_trigger_91plus
+- https://github.com/2ndQuadrant/audit-trigger
+
+The code can be seen at `django_partitioned_audit.audit_table.advanced_audit_table_manager.AdvancedAuditTableManager`.
+
+To use this implementation, you can reference that class in `settings.py`::
+
+    DPA_AUDIT_TABLE_MANAGER = "django_partitioned_audit.audit_table.advanced_audit_table_manager.AdvancedAuditTableManager"
+
+and follow the steps described above, at `Quick start (SimpleAuditTableManager)`.
+
+This implementation also audit `TRUNCATE` operations.
+
 Security of audit entries
 +++++++++++++++++++++++++
 
 DBA should correctly configure permissions, in a way that the user used to
 connect to the database from Django has permissions to INSERT rows in the
 ``trigger_audit_entries`` table, but NO permissions to UPDATE / DELETE them.
 
@@ -104,29 +125,27 @@
                 object_payload  = row_to_json(NEW);
             ELSIF (TG_OP = 'DELETE') THEN
                 object_payload  = row_to_json(OLD);
             ELSE
                 RAISE EXCEPTION 'Unexpected TG_OP = %', TG_OP;
             END IF;
 
-            INSERT INTO trigger_audit_entries_v2 (
+            INSERT INTO audit_simple (
                     object_table,
                     object_payload,
                     audit_entry_created,
                     audit_txid_current,
-                    audit_operation,
-                    audit_version
+                    audit_operation
                 )
                 SELECT
                     TG_TABLE_NAME,
                     object_payload,
                     now(),
                     txid_current(),
-                    TG_OP,
-                    2;
+                    TG_OP;
             RETURN NULL;
         END;
     $scr$ LANGUAGE plpgsql;
 
 Management of partitions
 ------------------------
 
@@ -137,120 +156,116 @@
 
 If you want to have enough partition to handle next 90 days (around 3 months), you can use `--extra-days=90`.
 Because it's the first time we run the command, no partition exists, and the plan will report that all
 partitions need to be created::
 
 
     $ manage.py manage_partition_tables simulate --extra-days=90
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  table_name                                  |  from_date   |  to_date     |  status       |
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  trigger_audit_entries_v2_20220201_20220301  |  2022-02-01  |  2022-03-01  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220301_20220401  |  2022-03-01  |  2022-04-01  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220401_20220501  |  2022-04-01  |  2022-05-01  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220501_20220601  |  2022-05-01  |  2022-06-01  |  ⚠ to create  |
-    +----------------------------------------------+--------------+--------------+---------------+
+    +----------------------------------+--------------+--------------+---------------+
+    |  table_name                      |  from_date   |  to_date     |  status       |
+    +----------------------------------+--------------+--------------+---------------+
+    |  audit_simple_20220201_20220301  |  2022-02-01  |  2022-03-01  |  ⚠ to create  |
+    |  audit_simple_20220301_20220401  |  2022-03-01  |  2022-04-01  |  ⚠ to create  |
+    |  audit_simple_20220401_20220501  |  2022-04-01  |  2022-05-01  |  ⚠ to create  |
+    |  audit_simple_20220501_20220601  |  2022-05-01  |  2022-06-01  |  ⚠ to create  |
+    +----------------------------------+--------------+--------------+---------------+
 
 
 We can also see the plan if no extra days are requested (this way, we'll only create partitions for
 the current month::
 
 
     $ manage.py manage_partition_tables simulate --extra-days=0
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  table_name                                  |  from_date   |  to_date     |  status       |
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  trigger_audit_entries_v2_20220201_20220301  |  2022-02-01  |  2022-03-01  |  ⚠ to create  |
-    +----------------------------------------------+--------------+--------------+---------------+
+    +----------------------------------+--------------+--------------+---------------+
+    |  table_name                      |  from_date   |  to_date     |  status       |
+    +----------------------------------+--------------+--------------+---------------+
+    |  audit_simple_20220201_20220301  |  2022-02-01  |  2022-03-01  |  ⚠ to create  |
+    +----------------------------------+--------------+--------------+---------------+
 
 
 Now let's create the partitions::
 
 
     $ manage.py manage_partition_tables create --extra-days=0
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  table_name                                  |  from_date   |  to_date     |  status       |
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  trigger_audit_entries_v2_20220201_20220301  |  2022-02-01  |  2022-03-01  |  ⚠ to create  |
-    +----------------------------------------------+--------------+--------------+---------------+
-    sql: CREATE TABLE "trigger_audit_entries_v2_20220201_20220301" PARTITION OF "trigger_audit_entries_v2" FOR VALUES FROM (%s) TO (%s); / params: [datetime.date(2022, 2, 1), datetime.date(2022, 3, 1)]
+    +----------------------------------+--------------+--------------+---------------+
+    |  table_name                      |  from_date   |  to_date     |  status       |
+    +----------------------------------+--------------+--------------+---------------+
+    |  audit_simple_20220201_20220301  |  2022-02-01  |  2022-03-01  |  ⚠ to create  |
+    +----------------------------------+--------------+--------------+---------------+
 
 
 If we run the command and we pass `--extra-days=90`, the partition for the current month already exists, and
 only partitions for next months (to cover 90 days) will be created::
 
 
     $ manage.py manage_partition_tables create --extra-days=90
-    +----------------------------------------------+--------------+--------------+----------------+
-    |  table_name                                  |  from_date   |  to_date     |  status        |
-    +----------------------------------------------+--------------+--------------+----------------+
-    |  trigger_audit_entries_v2_20220201_20220301  |  2022-02-01  |  2022-03-01  |  ✓ exists      |
-    |  trigger_audit_entries_v2_20220301_20220401  |  2022-03-01  |  2022-04-01  |  ❌ to create  |
-    |  trigger_audit_entries_v2_20220401_20220501  |  2022-04-01  |  2022-05-01  |  ❌ to create  |
-    |  trigger_audit_entries_v2_20220501_20220601  |  2022-05-01  |  2022-06-01  |  ❌ to create  |
-    +----------------------------------------------+--------------+--------------+----------------+
-    sql: CREATE TABLE "trigger_audit_entries_v2_20220301_20220401" PARTITION OF "trigger_audit_entries_v2" FOR VALUES FROM (%s) TO (%s); / params: [datetime.date(2022, 3, 1), datetime.date(2022, 4, 1)]
-    sql: CREATE TABLE "trigger_audit_entries_v2_20220401_20220501" PARTITION OF "trigger_audit_entries_v2" FOR VALUES FROM (%s) TO (%s); / params: [datetime.date(2022, 4, 1), datetime.date(2022, 5, 1)]
-    sql: CREATE TABLE "trigger_audit_entries_v2_20220501_20220601" PARTITION OF "trigger_audit_entries_v2" FOR VALUES FROM (%s) TO (%s); / params: [datetime.date(2022, 5, 1), datetime.date(2022, 6, 1)]
+    +----------------------------------+--------------+--------------+----------------+
+    |  table_name                      |  from_date   |  to_date     |  status        |
+    +----------------------------------+--------------+--------------+----------------+
+    |  audit_simple_20220201_20220301  |  2022-02-01  |  2022-03-01  |  ✓ exists      |
+    |  audit_simple_20220301_20220401  |  2022-03-01  |  2022-04-01  |  ❌ to create  |
+    |  audit_simple_20220401_20220501  |  2022-04-01  |  2022-05-01  |  ❌ to create  |
+    |  audit_simple_20220501_20220601  |  2022-05-01  |  2022-06-01  |  ❌ to create  |
+    +----------------------------------+--------------+--------------+----------------+
 
 
 We can use `list` to list existing partitions::
 
 
     $ manage.py manage_partition_tables list
-    +----------------------------------------------+--------------+--------------+
-    |  table_name                                  |  from_date   |  to_date     |
-    +----------------------------------------------+--------------+--------------+
-    |  trigger_audit_entries_v2_20220201_20220301  |  2022-02-01  |  2022-03-01  |
-    |  trigger_audit_entries_v2_20220301_20220401  |  2022-03-01  |  2022-04-01  |
-    |  trigger_audit_entries_v2_20220401_20220501  |  2022-04-01  |  2022-05-01  |
-    |  trigger_audit_entries_v2_20220501_20220601  |  2022-05-01  |  2022-06-01  |
-    +----------------------------------------------+--------------+--------------+
+    +----------------------------------+--------------+--------------+
+    |  table_name                      |  from_date   |  to_date     |
+    +----------------------------------+--------------+--------------+
+    |  audit_simple_20220201_20220301  |  2022-02-01  |  2022-03-01  |
+    |  audit_simple_20220301_20220401  |  2022-03-01  |  2022-04-01  |
+    |  audit_simple_20220401_20220501  |  2022-04-01  |  2022-05-01  |
+    |  audit_simple_20220501_20220601  |  2022-05-01  |  2022-06-01  |
+    +----------------------------------+--------------+--------------+
 
 
 Partition per week
 ++++++++++++++++++
 
 We can use one partition per week::
 
 
     $ manage.py manage_partition_tables create --extra-days=30 --time-range-generator=WeeklyTimeRangeGenerator
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  table_name                                  |  from_date   |  to_date     |  status       |
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  trigger_audit_entries_v2_20220222_20220301  |  2022-02-22  |  2022-03-01  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220301_20220308  |  2022-03-01  |  2022-03-08  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220308_20220315  |  2022-03-08  |  2022-03-15  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220315_20220322  |  2022-03-15  |  2022-03-22  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220322_20220329  |  2022-03-22  |  2022-03-29  |  ⚠ to create  |
-    +----------------------------------------------+--------------+--------------+---------------+
+    +----------------------------------+--------------+--------------+---------------+
+    |  table_name                      |  from_date   |  to_date     |  status       |
+    +----------------------------------+--------------+--------------+---------------+
+    |  audit_simple_20220222_20220301  |  2022-02-22  |  2022-03-01  |  ⚠ to create  |
+    |  audit_simple_20220301_20220308  |  2022-03-01  |  2022-03-08  |  ⚠ to create  |
+    |  audit_simple_20220308_20220315  |  2022-03-08  |  2022-03-15  |  ⚠ to create  |
+    |  audit_simple_20220315_20220322  |  2022-03-15  |  2022-03-22  |  ⚠ to create  |
+    |  audit_simple_20220322_20220329  |  2022-03-22  |  2022-03-29  |  ⚠ to create  |
+    +----------------------------------+--------------+--------------+---------------+
 
 
 Partition per day
 +++++++++++++++++
 
 We can use one partition per day::
 
 
     $ manage.py manage_partition_tables create --extra-days=10 --time-range-generator=DailyTimeRangeGenerator
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  table_name                                  |  from_date   |  to_date     |  status       |
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  trigger_audit_entries_v2_20220222_20220223  |  2022-02-22  |  2022-02-23  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220223_20220224  |  2022-02-23  |  2022-02-24  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220224_20220225  |  2022-02-24  |  2022-02-25  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220225_20220226  |  2022-02-25  |  2022-02-26  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220226_20220227  |  2022-02-26  |  2022-02-27  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220227_20220228  |  2022-02-27  |  2022-02-28  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220228_20220301  |  2022-02-28  |  2022-03-01  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220301_20220302  |  2022-03-01  |  2022-03-02  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220302_20220303  |  2022-03-02  |  2022-03-03  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220303_20220304  |  2022-03-03  |  2022-03-04  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220304_20220305  |  2022-03-04  |  2022-03-05  |  ⚠ to create  |
-    +----------------------------------------------+--------------+--------------+---------------+
+    +----------------------------------+--------------+--------------+---------------+
+    |  table_name                      |  from_date   |  to_date     |  status       |
+    +----------------------------------+--------------+--------------+---------------+
+    |  audit_simple_20220222_20220223  |  2022-02-22  |  2022-02-23  |  ⚠ to create  |
+    |  audit_simple_20220223_20220224  |  2022-02-23  |  2022-02-24  |  ⚠ to create  |
+    |  audit_simple_20220224_20220225  |  2022-02-24  |  2022-02-25  |  ⚠ to create  |
+    |  audit_simple_20220225_20220226  |  2022-02-25  |  2022-02-26  |  ⚠ to create  |
+    |  audit_simple_20220226_20220227  |  2022-02-26  |  2022-02-27  |  ⚠ to create  |
+    |  audit_simple_20220227_20220228  |  2022-02-27  |  2022-02-28  |  ⚠ to create  |
+    |  audit_simple_20220228_20220301  |  2022-02-28  |  2022-03-01  |  ⚠ to create  |
+    |  audit_simple_20220301_20220302  |  2022-03-01  |  2022-03-02  |  ⚠ to create  |
+    |  audit_simple_20220302_20220303  |  2022-03-02  |  2022-03-03  |  ⚠ to create  |
+    |  audit_simple_20220303_20220304  |  2022-03-03  |  2022-03-04  |  ⚠ to create  |
+    |  audit_simple_20220304_20220305  |  2022-03-04  |  2022-03-05  |  ⚠ to create  |
+    +----------------------------------+--------------+--------------+---------------+
 
 
 Test
 ----
 
 Tested on:
 
@@ -258,11 +273,17 @@
 * Django 3.2, 4.1, 4.2
 * PostgreSql 12, 13, 14, 15
 
 
 Known issues
 ------------
 
+* JAdvancedAuditTableManager: SONB is used as intermediary format in the view & Django models, should be migrated to HSTORE
+* Audit table and other objects are not managed by using Django migrations
 * Not tested with psycopg3
 * Coupled to Django (would be nice if Django is supported but possible to use it without Django)
-* Only a single app can use it (will be solved when decoupled from Django)
 * Works only on default db schema
+* Lack feature: remove old partitions
+
+TODO
+----
+* Refactor responsibilities on `PartitionManager` and `AuditTableManager`
```

### Comparing `django-partitioned-audit-1.0.3/django_partitioned_audit/admin.py` & `django-partitioned-audit-1.0.4/django_partitioned_audit/admin.py`

 * *Files identical despite different names*

### Comparing `django-partitioned-audit-1.0.3/django_partitioned_audit/management/commands/manage_partition_tables.py` & `django-partitioned-audit-1.0.4/django_partitioned_audit/management/commands/manage_partition_tables.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,8 +1,9 @@
 import dataclasses
+import sys
 from typing import List
 
 from django.core.management.base import BaseCommand
 
 from django_partitioned_audit.partitions.partition_info import PartitionInfo
 from django_partitioned_audit.partitions.partition_manager_plan import Plan
 from django_partitioned_audit.partitions.partition_manager_plan import Status
@@ -40,29 +41,25 @@
 
 class Command(BaseCommand):
     help = "Makes sure all the required partition tables exists"
 
     def add_arguments(self, parser):
         parser.add_argument("actions", nargs="+", choices=ACTION_NAMES)
         parser.add_argument("--extra-days", type=int, default=PartitionManager.default_extra_days)
-        parser.add_argument("--schema", type=str, default=PartitionManager.default_schema)
-        parser.add_argument("--partitioned-table", type=str, default=PartitionManager.default_partitioned_table)
         parser.add_argument(
             "--time-range-generator",
             type=str,
             default="MonthlyTimeRangeGenerator",
             choices=list(TIME_RANGE_GENERATORS.keys()),
         )
 
     def handle(self, *args, **options):
         time_range_generator_class = TIME_RANGE_GENERATORS[options["time_range_generator"]]
         pm = PartitionManager(
             extra_days=options["extra_days"],
-            schema=options["schema"],
-            partitioned_table=options["partitioned_table"],
             time_range_generator=time_range_generator_class(),
         )
 
         for action in options["actions"]:
             if action == "list":
                 self._run_list(pm, **options)
             elif action == "list-all":
@@ -87,15 +84,15 @@
                 pretty.add_row([pi.partition, pi.from_date, pi.to_date])
             else:
                 if list_all:
                     pretty.add_row([table_name, "", ""])
 
         self.stdout.write(str(pretty))
 
-    def _run_simulate(self, pm: PartitionManager, exit_with_status=True, **options) -> Plan:
+    def _run_simulate(self, pm: PartitionManager, exit_with_status=False, **options) -> Plan:
         pretty = PrettyTable()
         pretty.field_names = ["table_name", "from_date", "to_date", "status"]
         pretty.padding_width = 2
         pretty.sortby = "table_name"
         pretty.align = "l"
         simulation = pm.generate_plan()
 
@@ -103,24 +100,24 @@
         for pi in simulation.existing_partitions:
             pretty.add_row([pi.partition, pi.from_date, pi.to_date, "✓ exists"])
         for pi in simulation.partitions_to_create:
             pretty.add_row([pi.partition, pi.from_date, pi.to_date, f"{status_prefix} to create"])
 
         self.stdout.write(str(pretty))
 
-        # if exit_with_status:
-        #     if simulation.status == Status.OK:
-        #         sys.exit(0)
-        #     elif simulation.status == Status.MISSING_CURRENT:
-        #         print("ERROR: required partition to store data for current period does not exists", file=self.stdout)
-        #         sys.exit(1)
-        #     elif simulation.status == Status.MISSING_NEXT:
-        #         sys.exit(0)
-        #     else:
-        #         raise NotImplementedError(f"Unexpected status: {simulation.status}")
+        if exit_with_status:
+            if simulation.status == Status.OK:
+                sys.exit(0)
+            elif simulation.status == Status.MISSING_CURRENT:
+                print("ERROR: required partition to store data for current period do not exist", file=self.stdout)
+                sys.exit(1)
+            elif simulation.status == Status.MISSING_NEXT:
+                sys.exit(0)
+            else:
+                raise NotImplementedError(f"Unexpected status: {simulation.status}")
 
         return simulation
 
     def _run_create(self, pm: PartitionManager, **options):
         plan = self._run_simulate(pm, exit_with_status=False)
 
         for pi in plan.partitions_to_create:
```

### Comparing `django-partitioned-audit-1.0.3/django_partitioned_audit/migrations/0001_initial.py` & `django-partitioned-audit-1.0.4/tests/app_django/app/migrations/0002_invoice_product.py`

 * *Files 27% similar despite different names*

```diff
@@ -1,29 +1,29 @@
-# Generated by Django 4.2.2 on 2023-06-18 10:53
+# Generated by Django 4.2.2 on 2023-06-19 10:19
+
+import uuid
 
 from django.db import migrations
 from django.db import models
 
 
 class Migration(migrations.Migration):
-    initial = True
-
-    dependencies = []
+    dependencies = [
+        ("app", "0001_initial"),
+    ]
 
     operations = [
         migrations.CreateModel(
-            name="TriggerAuditEntry",
+            name="Invoice",
+            fields=[
+                ("id", models.UUIDField(default=uuid.uuid4, editable=False, primary_key=True, serialize=False)),
+                ("name", models.CharField(max_length=100)),
+            ],
+        ),
+        migrations.CreateModel(
+            name="Product",
             fields=[
-                ("id", models.AutoField(auto_created=True, primary_key=True, serialize=False, verbose_name="ID")),
-                ("object_table", models.CharField(max_length=128)),
-                ("object_payload", models.TextField()),
-                ("audit_entry_created", models.DateTimeField(auto_now_add=True)),
-                ("audit_txid_current", models.BigIntegerField()),
-                ("audit_operation", models.CharField(max_length=32)),
-                ("audit_version", models.IntegerField()),
+                ("product_id", models.BigAutoField(primary_key=True, serialize=False)),
+                ("name", models.CharField(max_length=100)),
             ],
-            options={
-                "db_table": "trigger_audit_entries_v2_view",
-                "managed": False,
-            },
         ),
     ]
```

### Comparing `django-partitioned-audit-1.0.3/django_partitioned_audit/partitions/partition_manager_plan.py` & `django-partitioned-audit-1.0.4/django_partitioned_audit/partitions/partition_manager_plan.py`

 * *Files identical despite different names*

### Comparing `django-partitioned-audit-1.0.3/django_partitioned_audit/partitions/partition_manager_time_range.py` & `django-partitioned-audit-1.0.4/django_partitioned_audit/partitions/partition_manager_time_range.py`

 * *Files identical despite different names*

### Comparing `django-partitioned-audit-1.0.3/django_partitioned_audit/partitions/time_range_partitioning.py` & `django-partitioned-audit-1.0.4/django_partitioned_audit/partitions/time_range_partitioning.py`

 * *Files identical despite different names*

### Comparing `django-partitioned-audit-1.0.3/django_partitioned_audit.egg-info/PKG-INFO` & `django-partitioned-audit-1.0.4/django_partitioned_audit.egg-info/PKG-INFO`

 * *Files 11% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: django-partitioned-audit
-Version: 1.0.3
+Version: 1.0.4
 Summary: Keep audit log based on PostgreSql triggers and partitioned tables
 Home-page: https://gitlab.com/hgdeoro/django-partitioned-audit
 Author: Horacio G. de Oro
 Author-email: hgdeoro@gmail.com
 License: BSD-3-Clause
 Classifier: Development Status :: 4 - Beta
 Classifier: Environment :: Web Environment
@@ -28,48 +28,51 @@
 
 ========================
 django-partitioned-audit
 ========================
 
 Creates an audit log of the modifications made to models, by using triggers.
 
-* Only PostgreSql supported.
+* Only PostgreSql supported
 * Models to audit are configured in ``AppConfig``
-* Triggers are applied automatically when running ``python manage.py migrate``
-* The whole row is saved by the trigger by using PostgreSql's ``row_to_json()``
+* Triggers are created automatically when running ``python manage.py migrate``
+* The whole row is saved by the trigger
+* Two different implementations for audit tables (see `SimpleAuditTableManager` and `AdvancedAuditTableManager`)
 * The audit table is partitioned
+* There are 3 partition strategies: one partition per month, one per week, one per day
 * Management command `manage_partition_tables` creates required partitions
-* There are 3 partition strategies: one partition per month, one per week, one per day.
 
-Quick start
------------
+Quick start (SimpleAuditTableManager)
+-------------------------------------
 
 1. Add "django_partitioned_audit" to your INSTALLED_APPS setting like this::
 
     INSTALLED_APPS = [
         ...
         'django_partitioned_audit',
 
         'your.app1.App1Config',
         'your.app2.App2Config',
         'your.app3.App3Config',
     ]
 
 2. Run ``python manage.py migrate`` to create the partitioned table.
 
+There is no real migration to create the partitioned table. Instead, a `post_migrate` signal is used.
+
 3. Run ``manage.py manage_partition_tables create --extra-days=60`` to create the partitions::
 
     $ manage.py manage_partition_tables create --extra-days=60
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  table_name                                  |  from_date   |  to_date     |  status       |
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  trigger_audit_entries_v2_20220201_20220301  |  2022-02-01  |  2022-03-01  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220301_20220401  |  2022-03-01  |  2022-04-01  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220401_20220501  |  2022-04-01  |  2022-05-01  |  ⚠ to create  |
-    +----------------------------------------------+--------------+--------------+---------------+
+    +----------------------------------+--------------+--------------+---------------+
+    |  table_name                      |  from_date   |  to_date     |  status       |
+    +----------------------------------+--------------+--------------+---------------+
+    |  audit_simple_20220201_20220301  |  2022-02-01  |  2022-03-01  |  ⚠ to create  |
+    |  audit_simple_20220301_20220401  |  2022-03-01  |  2022-04-01  |  ⚠ to create  |
+    |  audit_simple_20220401_20220501  |  2022-04-01  |  2022-05-01  |  ⚠ to create  |
+    +----------------------------------+--------------+--------------+---------------+
 
 You should run that command periodically, to make sure the database always contains a partition where to insert data.
 
 4. Register the models you want to audit in your ``AppConfig`` instances::
 
     from django.apps import AppConfig
     class MyAppConfig(AppConfig):
@@ -79,14 +82,32 @@
             'Model2',
             'Model3',
         )
 
 5. Run ``python manage.py migrate`` to create the triggers.
 
 
+Quick start (AdvancedAuditTableManager)
+---------------------------------------
+
+There is a second implementation of the audit table that can be used, based on:
+
+- https://wiki.postgresql.org/wiki/Audit_trigger_91plus
+- https://github.com/2ndQuadrant/audit-trigger
+
+The code can be seen at `django_partitioned_audit.audit_table.advanced_audit_table_manager.AdvancedAuditTableManager`.
+
+To use this implementation, you can reference that class in `settings.py`::
+
+    DPA_AUDIT_TABLE_MANAGER = "django_partitioned_audit.audit_table.advanced_audit_table_manager.AdvancedAuditTableManager"
+
+and follow the steps described above, at `Quick start (SimpleAuditTableManager)`.
+
+This implementation also audit `TRUNCATE` operations.
+
 Security of audit entries
 +++++++++++++++++++++++++
 
 DBA should correctly configure permissions, in a way that the user used to
 connect to the database from Django has permissions to INSERT rows in the
 ``trigger_audit_entries`` table, but NO permissions to UPDATE / DELETE them.
 
@@ -132,29 +153,27 @@
                 object_payload  = row_to_json(NEW);
             ELSIF (TG_OP = 'DELETE') THEN
                 object_payload  = row_to_json(OLD);
             ELSE
                 RAISE EXCEPTION 'Unexpected TG_OP = %', TG_OP;
             END IF;
 
-            INSERT INTO trigger_audit_entries_v2 (
+            INSERT INTO audit_simple (
                     object_table,
                     object_payload,
                     audit_entry_created,
                     audit_txid_current,
-                    audit_operation,
-                    audit_version
+                    audit_operation
                 )
                 SELECT
                     TG_TABLE_NAME,
                     object_payload,
                     now(),
                     txid_current(),
-                    TG_OP,
-                    2;
+                    TG_OP;
             RETURN NULL;
         END;
     $scr$ LANGUAGE plpgsql;
 
 Management of partitions
 ------------------------
 
@@ -165,120 +184,116 @@
 
 If you want to have enough partition to handle next 90 days (around 3 months), you can use `--extra-days=90`.
 Because it's the first time we run the command, no partition exists, and the plan will report that all
 partitions need to be created::
 
 
     $ manage.py manage_partition_tables simulate --extra-days=90
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  table_name                                  |  from_date   |  to_date     |  status       |
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  trigger_audit_entries_v2_20220201_20220301  |  2022-02-01  |  2022-03-01  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220301_20220401  |  2022-03-01  |  2022-04-01  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220401_20220501  |  2022-04-01  |  2022-05-01  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220501_20220601  |  2022-05-01  |  2022-06-01  |  ⚠ to create  |
-    +----------------------------------------------+--------------+--------------+---------------+
+    +----------------------------------+--------------+--------------+---------------+
+    |  table_name                      |  from_date   |  to_date     |  status       |
+    +----------------------------------+--------------+--------------+---------------+
+    |  audit_simple_20220201_20220301  |  2022-02-01  |  2022-03-01  |  ⚠ to create  |
+    |  audit_simple_20220301_20220401  |  2022-03-01  |  2022-04-01  |  ⚠ to create  |
+    |  audit_simple_20220401_20220501  |  2022-04-01  |  2022-05-01  |  ⚠ to create  |
+    |  audit_simple_20220501_20220601  |  2022-05-01  |  2022-06-01  |  ⚠ to create  |
+    +----------------------------------+--------------+--------------+---------------+
 
 
 We can also see the plan if no extra days are requested (this way, we'll only create partitions for
 the current month::
 
 
     $ manage.py manage_partition_tables simulate --extra-days=0
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  table_name                                  |  from_date   |  to_date     |  status       |
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  trigger_audit_entries_v2_20220201_20220301  |  2022-02-01  |  2022-03-01  |  ⚠ to create  |
-    +----------------------------------------------+--------------+--------------+---------------+
+    +----------------------------------+--------------+--------------+---------------+
+    |  table_name                      |  from_date   |  to_date     |  status       |
+    +----------------------------------+--------------+--------------+---------------+
+    |  audit_simple_20220201_20220301  |  2022-02-01  |  2022-03-01  |  ⚠ to create  |
+    +----------------------------------+--------------+--------------+---------------+
 
 
 Now let's create the partitions::
 
 
     $ manage.py manage_partition_tables create --extra-days=0
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  table_name                                  |  from_date   |  to_date     |  status       |
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  trigger_audit_entries_v2_20220201_20220301  |  2022-02-01  |  2022-03-01  |  ⚠ to create  |
-    +----------------------------------------------+--------------+--------------+---------------+
-    sql: CREATE TABLE "trigger_audit_entries_v2_20220201_20220301" PARTITION OF "trigger_audit_entries_v2" FOR VALUES FROM (%s) TO (%s); / params: [datetime.date(2022, 2, 1), datetime.date(2022, 3, 1)]
+    +----------------------------------+--------------+--------------+---------------+
+    |  table_name                      |  from_date   |  to_date     |  status       |
+    +----------------------------------+--------------+--------------+---------------+
+    |  audit_simple_20220201_20220301  |  2022-02-01  |  2022-03-01  |  ⚠ to create  |
+    +----------------------------------+--------------+--------------+---------------+
 
 
 If we run the command and we pass `--extra-days=90`, the partition for the current month already exists, and
 only partitions for next months (to cover 90 days) will be created::
 
 
     $ manage.py manage_partition_tables create --extra-days=90
-    +----------------------------------------------+--------------+--------------+----------------+
-    |  table_name                                  |  from_date   |  to_date     |  status        |
-    +----------------------------------------------+--------------+--------------+----------------+
-    |  trigger_audit_entries_v2_20220201_20220301  |  2022-02-01  |  2022-03-01  |  ✓ exists      |
-    |  trigger_audit_entries_v2_20220301_20220401  |  2022-03-01  |  2022-04-01  |  ❌ to create  |
-    |  trigger_audit_entries_v2_20220401_20220501  |  2022-04-01  |  2022-05-01  |  ❌ to create  |
-    |  trigger_audit_entries_v2_20220501_20220601  |  2022-05-01  |  2022-06-01  |  ❌ to create  |
-    +----------------------------------------------+--------------+--------------+----------------+
-    sql: CREATE TABLE "trigger_audit_entries_v2_20220301_20220401" PARTITION OF "trigger_audit_entries_v2" FOR VALUES FROM (%s) TO (%s); / params: [datetime.date(2022, 3, 1), datetime.date(2022, 4, 1)]
-    sql: CREATE TABLE "trigger_audit_entries_v2_20220401_20220501" PARTITION OF "trigger_audit_entries_v2" FOR VALUES FROM (%s) TO (%s); / params: [datetime.date(2022, 4, 1), datetime.date(2022, 5, 1)]
-    sql: CREATE TABLE "trigger_audit_entries_v2_20220501_20220601" PARTITION OF "trigger_audit_entries_v2" FOR VALUES FROM (%s) TO (%s); / params: [datetime.date(2022, 5, 1), datetime.date(2022, 6, 1)]
+    +----------------------------------+--------------+--------------+----------------+
+    |  table_name                      |  from_date   |  to_date     |  status        |
+    +----------------------------------+--------------+--------------+----------------+
+    |  audit_simple_20220201_20220301  |  2022-02-01  |  2022-03-01  |  ✓ exists      |
+    |  audit_simple_20220301_20220401  |  2022-03-01  |  2022-04-01  |  ❌ to create  |
+    |  audit_simple_20220401_20220501  |  2022-04-01  |  2022-05-01  |  ❌ to create  |
+    |  audit_simple_20220501_20220601  |  2022-05-01  |  2022-06-01  |  ❌ to create  |
+    +----------------------------------+--------------+--------------+----------------+
 
 
 We can use `list` to list existing partitions::
 
 
     $ manage.py manage_partition_tables list
-    +----------------------------------------------+--------------+--------------+
-    |  table_name                                  |  from_date   |  to_date     |
-    +----------------------------------------------+--------------+--------------+
-    |  trigger_audit_entries_v2_20220201_20220301  |  2022-02-01  |  2022-03-01  |
-    |  trigger_audit_entries_v2_20220301_20220401  |  2022-03-01  |  2022-04-01  |
-    |  trigger_audit_entries_v2_20220401_20220501  |  2022-04-01  |  2022-05-01  |
-    |  trigger_audit_entries_v2_20220501_20220601  |  2022-05-01  |  2022-06-01  |
-    +----------------------------------------------+--------------+--------------+
+    +----------------------------------+--------------+--------------+
+    |  table_name                      |  from_date   |  to_date     |
+    +----------------------------------+--------------+--------------+
+    |  audit_simple_20220201_20220301  |  2022-02-01  |  2022-03-01  |
+    |  audit_simple_20220301_20220401  |  2022-03-01  |  2022-04-01  |
+    |  audit_simple_20220401_20220501  |  2022-04-01  |  2022-05-01  |
+    |  audit_simple_20220501_20220601  |  2022-05-01  |  2022-06-01  |
+    +----------------------------------+--------------+--------------+
 
 
 Partition per week
 ++++++++++++++++++
 
 We can use one partition per week::
 
 
     $ manage.py manage_partition_tables create --extra-days=30 --time-range-generator=WeeklyTimeRangeGenerator
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  table_name                                  |  from_date   |  to_date     |  status       |
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  trigger_audit_entries_v2_20220222_20220301  |  2022-02-22  |  2022-03-01  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220301_20220308  |  2022-03-01  |  2022-03-08  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220308_20220315  |  2022-03-08  |  2022-03-15  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220315_20220322  |  2022-03-15  |  2022-03-22  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220322_20220329  |  2022-03-22  |  2022-03-29  |  ⚠ to create  |
-    +----------------------------------------------+--------------+--------------+---------------+
+    +----------------------------------+--------------+--------------+---------------+
+    |  table_name                      |  from_date   |  to_date     |  status       |
+    +----------------------------------+--------------+--------------+---------------+
+    |  audit_simple_20220222_20220301  |  2022-02-22  |  2022-03-01  |  ⚠ to create  |
+    |  audit_simple_20220301_20220308  |  2022-03-01  |  2022-03-08  |  ⚠ to create  |
+    |  audit_simple_20220308_20220315  |  2022-03-08  |  2022-03-15  |  ⚠ to create  |
+    |  audit_simple_20220315_20220322  |  2022-03-15  |  2022-03-22  |  ⚠ to create  |
+    |  audit_simple_20220322_20220329  |  2022-03-22  |  2022-03-29  |  ⚠ to create  |
+    +----------------------------------+--------------+--------------+---------------+
 
 
 Partition per day
 +++++++++++++++++
 
 We can use one partition per day::
 
 
     $ manage.py manage_partition_tables create --extra-days=10 --time-range-generator=DailyTimeRangeGenerator
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  table_name                                  |  from_date   |  to_date     |  status       |
-    +----------------------------------------------+--------------+--------------+---------------+
-    |  trigger_audit_entries_v2_20220222_20220223  |  2022-02-22  |  2022-02-23  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220223_20220224  |  2022-02-23  |  2022-02-24  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220224_20220225  |  2022-02-24  |  2022-02-25  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220225_20220226  |  2022-02-25  |  2022-02-26  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220226_20220227  |  2022-02-26  |  2022-02-27  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220227_20220228  |  2022-02-27  |  2022-02-28  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220228_20220301  |  2022-02-28  |  2022-03-01  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220301_20220302  |  2022-03-01  |  2022-03-02  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220302_20220303  |  2022-03-02  |  2022-03-03  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220303_20220304  |  2022-03-03  |  2022-03-04  |  ⚠ to create  |
-    |  trigger_audit_entries_v2_20220304_20220305  |  2022-03-04  |  2022-03-05  |  ⚠ to create  |
-    +----------------------------------------------+--------------+--------------+---------------+
+    +----------------------------------+--------------+--------------+---------------+
+    |  table_name                      |  from_date   |  to_date     |  status       |
+    +----------------------------------+--------------+--------------+---------------+
+    |  audit_simple_20220222_20220223  |  2022-02-22  |  2022-02-23  |  ⚠ to create  |
+    |  audit_simple_20220223_20220224  |  2022-02-23  |  2022-02-24  |  ⚠ to create  |
+    |  audit_simple_20220224_20220225  |  2022-02-24  |  2022-02-25  |  ⚠ to create  |
+    |  audit_simple_20220225_20220226  |  2022-02-25  |  2022-02-26  |  ⚠ to create  |
+    |  audit_simple_20220226_20220227  |  2022-02-26  |  2022-02-27  |  ⚠ to create  |
+    |  audit_simple_20220227_20220228  |  2022-02-27  |  2022-02-28  |  ⚠ to create  |
+    |  audit_simple_20220228_20220301  |  2022-02-28  |  2022-03-01  |  ⚠ to create  |
+    |  audit_simple_20220301_20220302  |  2022-03-01  |  2022-03-02  |  ⚠ to create  |
+    |  audit_simple_20220302_20220303  |  2022-03-02  |  2022-03-03  |  ⚠ to create  |
+    |  audit_simple_20220303_20220304  |  2022-03-03  |  2022-03-04  |  ⚠ to create  |
+    |  audit_simple_20220304_20220305  |  2022-03-04  |  2022-03-05  |  ⚠ to create  |
+    +----------------------------------+--------------+--------------+---------------+
 
 
 Test
 ----
 
 Tested on:
 
@@ -286,11 +301,17 @@
 * Django 3.2, 4.1, 4.2
 * PostgreSql 12, 13, 14, 15
 
 
 Known issues
 ------------
 
+* JAdvancedAuditTableManager: SONB is used as intermediary format in the view & Django models, should be migrated to HSTORE
+* Audit table and other objects are not managed by using Django migrations
 * Not tested with psycopg3
 * Coupled to Django (would be nice if Django is supported but possible to use it without Django)
-* Only a single app can use it (will be solved when decoupled from Django)
 * Works only on default db schema
+* Lack feature: remove old partitions
+
+TODO
+----
+* Refactor responsibilities on `PartitionManager` and `AuditTableManager`
```

### Comparing `django-partitioned-audit-1.0.3/django_partitioned_audit.egg-info/SOURCES.txt` & `django-partitioned-audit-1.0.4/django_partitioned_audit.egg-info/SOURCES.txt`

 * *Files 19% similar despite different names*

```diff
@@ -1,9 +1,10 @@
 .bumpversion.cfg
 .gitignore
+.gitlab-ci.yml
 .pre-commit-config.yaml
 .pylintrc
 LICENSE
 Makefile
 README.rst
 pyproject.toml
 pytest.ini
@@ -16,65 +17,85 @@
 django_partitioned_audit/models.py
 django_partitioned_audit/signals.py
 django_partitioned_audit/utils.py
 django_partitioned_audit.egg-info/PKG-INFO
 django_partitioned_audit.egg-info/SOURCES.txt
 django_partitioned_audit.egg-info/dependency_links.txt
 django_partitioned_audit.egg-info/top_level.txt
+django_partitioned_audit/audit_table/__init__.py
+django_partitioned_audit/audit_table/advanced_audit_table_manager.original.sql
+django_partitioned_audit/audit_table/advanced_audit_table_manager.py
+django_partitioned_audit/audit_table/advanced_audit_table_manager.sql
+django_partitioned_audit/audit_table/audit_table_manager.py
+django_partitioned_audit/audit_table/simple_audit_table_manager.py
 django_partitioned_audit/management/__init__.py
 django_partitioned_audit/management/commands/__init__.py
 django_partitioned_audit/management/commands/manage_partition_tables.py
-django_partitioned_audit/migrations/0001_initial.py
-django_partitioned_audit/migrations/0002_trigger_audit_entry_creator_func_v2.py
-django_partitioned_audit/migrations/__init__.py
 django_partitioned_audit/partitions/__init__.py
 django_partitioned_audit/partitions/partition_info.py
 django_partitioned_audit/partitions/partition_manager_base.py
 django_partitioned_audit/partitions/partition_manager_plan.py
 django_partitioned_audit/partitions/partition_manager_time_range.py
 django_partitioned_audit/partitions/time_range_partitioning.py
 tests/conftest.py
 tests/docker-compose.yml
-tests/requirements.in
-tests/requirements.txt
+tests/dummies.py
+tests/requirements-ci.in
+tests/requirements-ci.txt
+tests/requirements-dev.in
+tests/requirements-dev.txt
+tests/requirements-test.in
+tests/requirements-test.txt
 tests/test_audit_events_creation.py
+tests/test_audit_events_deletion.py
+tests/test_audit_events_select.py
+tests/test_audit_table_manager.py
 tests/test_concurrent.py
 tests/test_examples_on_readme.py
 tests/test_management_commands.py
 tests/test_non_standard_pk.py
 tests/test_partition_info.py
 tests/test_partition_manager_base.py
 tests/test_partition_manager_create.py
 tests/test_partition_manager_simulate.py
 tests/test_partition_manager_time_range.py
 tests/test_partition_manager_time_range_plan.py
 tests/test_partition_manager_truncate_63.py
+tests/test_signals.py
 tests/test_testing_app_without_audit.py
+tests/test_two_apps.py
 tests/app_django/manage.py
 tests/app_django/app/__init__.py
 tests/app_django/app/admin.py
 tests/app_django/app/apps.py
 tests/app_django/app/models.py
 tests/app_django/app/views.py
 tests/app_django/app/management/commands/stresstest.py
 tests/app_django/app/management/commands/update_customer.py
 tests/app_django/app/migrations/0001_initial.py
 tests/app_django/app/migrations/0002_invoice_product.py
+tests/app_django/app/migrations/0003_invoiceitem.py
 tests/app_django/app/migrations/__init__.py
 tests/app_django/app/templates/app/customer_confirm_delete.html
 tests/app_django/app/templates/app/customer_form.html
 tests/app_django/app/templates/app/invoice_form.html
 tests/app_django/app/templates/app/product_form.html
 tests/app_django/config/__init__.py
 tests/app_django/config/asgi.py
+tests/app_django/config/ci_settings.py
 tests/app_django/config/settings.py
 tests/app_django/config/settings_boilerplate.py
 tests/app_django/config/settings_postgres12.py
 tests/app_django/config/settings_postgres13.py
 tests/app_django/config/settings_postgres14.py
 tests/app_django/config/settings_postgres15.py
 tests/app_django/config/tox_settings.py
 tests/app_django/config/urls.py
 tests/app_django/config/wsgi.py
+tests/app_django/second_app/__init__.py
+tests/app_django/second_app/apps.py
+tests/app_django/second_app/models.py
+tests/app_django/second_app/migrations/0001_initial.py
+tests/app_django/second_app/migrations/__init__.py
 tests/app_install_test/manage.py
 tests/app_install_test/app_install_test_config/__init__.py
 tests/app_install_test/app_install_test_config/settings.py
```

### Comparing `django-partitioned-audit-1.0.3/setup.cfg` & `django-partitioned-audit-1.0.4/setup.cfg`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [metadata]
 name = django-partitioned-audit
-version = 1.0.3
+version = 1.0.4
 description = Keep audit log based on PostgreSql triggers and partitioned tables
 long_description = file: README.rst
 url = https://gitlab.com/hgdeoro/django-partitioned-audit
 author = Horacio G. de Oro
 author_email = hgdeoro@gmail.com
 license = BSD-3-Clause
 classifiers =
```

### Comparing `django-partitioned-audit-1.0.3/tests/app_django/app/admin.py` & `django-partitioned-audit-1.0.4/tests/app_django/app/admin.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 from app.models import Customer
 from app.models import Invoice
 from app.models import Product
 from django.contrib import admin
 
 from django_partitioned_audit.admin import TriggerAuditEntryAdmin
-from django_partitioned_audit.models import TriggerAuditEntry
+from django_partitioned_audit.models import SimpleAuditEntry
 
 
 @admin.register(Customer)
 class CustomerAdmin(admin.ModelAdmin):
     pass
 
 
@@ -18,10 +18,10 @@
 
 
 @admin.register(Product)
 class ProductAdmin(admin.ModelAdmin):
     pass
 
 
-@admin.register(TriggerAuditEntry)
+@admin.register(SimpleAuditEntry)
 class CustomTriggerAuditEntryAdmin(TriggerAuditEntryAdmin):
     pass
```

### Comparing `django-partitioned-audit-1.0.3/tests/app_django/app/management/commands/stresstest.py` & `django-partitioned-audit-1.0.4/tests/app_django/app/management/commands/stresstest.py`

 * *Files 3% similar despite different names*

```diff
@@ -5,15 +5,15 @@
 from concurrent.futures.thread import ThreadPoolExecutor
 
 import requests
 from app.models import Customer
 from django.core.management.base import BaseCommand
 from django.urls import reverse
 
-from django_partitioned_audit.models import TriggerAuditEntry
+from django_partitioned_audit.models import SimpleAuditEntry
 
 
 class Command(BaseCommand):
     help = "Closes the specified poll for voting"
 
     def add_arguments(self, parser):
         parser.add_argument("--server-url", default="http://127.0.0.1:8011")
@@ -73,11 +73,11 @@
                     print("+", end="")
                     if count % 100 == 0:
                         print("")
 
         print("Finished. Now checking...")
 
         # Assert model was created and audit exists
-        assert TriggerAuditEntry.objects.all().count() == len(new_names)
-        names_in_payload = [audit_entry.object_payload_json["name"] for audit_entry in TriggerAuditEntry.objects.all()]
+        assert SimpleAuditEntry.objects.all().count() == len(new_names)
+        names_in_payload = [audit_entry.get_row_data()["name"] for audit_entry in SimpleAuditEntry.objects.all()]
         assert len(names_in_payload) == len(new_names)
         assert set(names_in_payload) == set(new_names)
```

### Comparing `django-partitioned-audit-1.0.3/tests/app_django/app/management/commands/update_customer.py` & `django-partitioned-audit-1.0.4/tests/app_django/app/management/commands/update_customer.py`

 * *Files 4% similar despite different names*

```diff
@@ -2,15 +2,15 @@
 import uuid
 
 import requests
 from app.models import Customer
 from django.core.management.base import BaseCommand
 from django.urls import reverse
 
-from django_partitioned_audit.models import TriggerAuditEntry
+from django_partitioned_audit.models import SimpleAuditEntry
 
 
 class Command(BaseCommand):
     help = "Closes the specified poll for voting"
 
     def add_arguments(self, parser):
         parser.add_argument("--server-url", default="http://127.0.0.1:8000")
@@ -25,13 +25,13 @@
         url = f"{server_url}{reverse('customer/update', args=[customer.pk])}"
         response = requests.post(url, data=dict(name=new_name))
         response.raise_for_status()
 
         print("Finished. Now checking...")
 
         # Assert model was created and audit exists
-        for audit in TriggerAuditEntry.objects.filter(object_table="app_customer"):
+        for audit in SimpleAuditEntry.objects.filter(object_table="app_customer"):
             # FIXME: filter by `id`
             # Before was possible just by `filter(object_pk=customer.pk)`
             print("-" * 120)
             print(f"Audit: {audit}")
             print(f"object_payload: {json.dumps(json.loads(audit.object_payload), indent=4)}")
```

### Comparing `django-partitioned-audit-1.0.3/tests/app_django/app/migrations/0001_initial.py` & `django-partitioned-audit-1.0.4/tests/app_django/app/migrations/0001_initial.py`

 * *Files identical despite different names*

### Comparing `django-partitioned-audit-1.0.3/tests/app_django/app/migrations/0002_invoice_product.py` & `django-partitioned-audit-1.0.4/tests/app_django/second_app/migrations/0001_initial.py`

 * *Files 18% similar despite different names*

```diff
@@ -1,22 +1,30 @@
-# Generated by Django 4.2.2 on 2023-06-19 10:19
+# Generated by Django 4.2.2 on 2023-06-23 20:49
 
 import uuid
 
 from django.db import migrations
 from django.db import models
 
 
 class Migration(migrations.Migration):
-    dependencies = [
-        ("app", "0001_initial"),
-    ]
+    initial = True
+
+    dependencies = []
 
     operations = [
         migrations.CreateModel(
+            name="Customer",
+            fields=[
+                ("id", models.AutoField(auto_created=True, primary_key=True, serialize=False, verbose_name="ID")),
+                ("name", models.CharField(max_length=100)),
+                ("active", models.BooleanField(default=False)),
+            ],
+        ),
+        migrations.CreateModel(
             name="Invoice",
             fields=[
                 ("id", models.UUIDField(default=uuid.uuid4, editable=False, primary_key=True, serialize=False)),
                 ("name", models.CharField(max_length=100)),
             ],
         ),
         migrations.CreateModel(
```

### Comparing `django-partitioned-audit-1.0.3/tests/app_django/app/views.py` & `django-partitioned-audit-1.0.4/tests/app_django/app/views.py`

 * *Files identical despite different names*

### Comparing `django-partitioned-audit-1.0.3/tests/app_django/config/settings.py` & `django-partitioned-audit-1.0.4/tests/app_django/config/settings.py`

 * *Files 22% similar despite different names*

```diff
@@ -1,23 +1,30 @@
+import os
+
 from .settings_boilerplate import *  # noqa
 
 # pylint: skip-file
 
 DEBUG = True
 
-AUDIT_DISABLE = False
+if "DPA_AUDIT_TABLE_MANAGER" in os.environ:
+    DPA_AUDIT_TABLE_MANAGER = os.environ["DPA_AUDIT_TABLE_MANAGER"]
 
 INSTALLED_APPS = [
+    # Django applications
     "django.contrib.admin",
     "django.contrib.auth",
     "django.contrib.contenttypes",
     "django.contrib.sessions",
     "django.contrib.messages",
     "django.contrib.staticfiles",
+    "django.contrib.postgres",
+    # django partitioned audit & test applications
     "django_partitioned_audit",
     "app.apps.AppConfig",
+    "second_app.apps.SecondaryAppConfig",
 ]
 
 # By default, let's import some db configuration, to make sure it will work
 # when using this file directly
 
 from .settings_postgres15 import *  # noqa
```

### Comparing `django-partitioned-audit-1.0.3/tests/app_django/config/settings_boilerplate.py` & `django-partitioned-audit-1.0.4/tests/app_django/config/settings_boilerplate.py`

 * *Files identical despite different names*

### Comparing `django-partitioned-audit-1.0.3/tests/app_django/config/tox_settings.py` & `django-partitioned-audit-1.0.4/tests/app_django/config/tox_settings.py`

 * *Files identical despite different names*

### Comparing `django-partitioned-audit-1.0.3/tests/app_django/config/urls.py` & `django-partitioned-audit-1.0.4/tests/app_django/config/urls.py`

 * *Files identical despite different names*

### Comparing `django-partitioned-audit-1.0.3/tests/app_django/manage.py` & `django-partitioned-audit-1.0.4/tests/app_django/manage.py`

 * *Files identical despite different names*

### Comparing `django-partitioned-audit-1.0.3/tests/app_install_test/app_install_test_config/settings.py` & `django-partitioned-audit-1.0.4/tests/app_install_test/app_install_test_config/settings.py`

 * *Files 22% similar despite different names*

```diff
@@ -1,12 +1,13 @@
 import psycopg2.extensions
 
 # pylint: skip-file
 
 INSTALLED_APPS = [
+    "django.contrib.postgres",
     "django.contrib.contenttypes",
     "django_partitioned_audit",
 ]
 
 DATABASES = {
     "default": {
         "NAME": "sdist_test_install",
```

### Comparing `django-partitioned-audit-1.0.3/tests/app_install_test/manage.py` & `django-partitioned-audit-1.0.4/tests/app_install_test/manage.py`

 * *Files identical despite different names*

### Comparing `django-partitioned-audit-1.0.3/tests/docker-compose.yml` & `django-partitioned-audit-1.0.4/tests/docker-compose.yml`

 * *Files identical despite different names*

### Comparing `django-partitioned-audit-1.0.3/tests/test_audit_events_creation.py` & `django-partitioned-audit-1.0.4/tests/test_testing_app_without_audit.py`

 * *Files 21% similar despite different names*

```diff
@@ -1,56 +1,54 @@
 import uuid
 
 import pytest
 import requests
 from app.models import Customer
+from app.models import Invoice
+from app.models import Product
 from django.urls import reverse
 
-from django_partitioned_audit.models import TriggerAuditEntry
-
 # pylint: skip-file
 
 
+"""
+These tests exist to make sure the application we use to test, actually works.
+These tests do not test `django-partitioned-audit` functionality.
+"""
+
+
 @pytest.mark.django_db(transaction=True)
-def test_create_is_audited(live_server, partition_created):
+def test_create_customer_works_with_audit_disabled(live_server, remove_auditing):
     name = str(uuid.uuid4())
-    data = dict(name=name)
-    response = requests.post(f"{live_server}{reverse('customer/create')}", data=data)
+    response = requests.post(f"{live_server}{reverse('customer/create')}", data=dict(name=name))
     response.raise_for_status()
     assert Customer.objects.filter(name=name).exists()
 
-    # Assert model was created and audit exists
-    audit_entry: TriggerAuditEntry = TriggerAuditEntry.objects.all().get()
-    assert audit_entry.is_insert()
-    assert audit_entry.object_payload_json["name"] == name
-
 
 @pytest.mark.django_db(transaction=True)
-def test_update_is_audited(live_server, partition_created):
-    original_name = str(uuid.uuid4())
-    customer = Customer.objects.create(name=original_name)
-
+def test_update_customer_works_with_audit_disabled(live_server, remove_auditing):
+    orig_name = str(uuid.uuid4())
     new_name = str(uuid.uuid4())
-    data = dict(name=new_name)
-    response = requests.post(f"{live_server}{reverse('customer/update', args=[customer.pk])}", data=data)
+    customer = Customer.objects.create(name=orig_name)
+    assert Customer.objects.filter(name=orig_name).exists()
+
+    request_url = f"{live_server}{reverse('customer/update', args=[customer.pk])}"
+    response = requests.post(request_url, data=dict(name=new_name))
     response.raise_for_status()
+    assert not Customer.objects.filter(name=orig_name).exists()
     assert Customer.objects.filter(name=new_name).exists()
 
-    # Assert model was created and audit exists
-    audit_entry: TriggerAuditEntry = TriggerAuditEntry.objects.filter(audit_operation="UPDATE").get()
-    assert audit_entry.is_update()
-    assert audit_entry.object_payload_json["name"] == new_name
-
 
 @pytest.mark.django_db(transaction=True)
-def test_delete_is_audited(live_server, partition_created):
+def test_create_invoice_works_with_audit_disabled(live_server, remove_auditing):
     name = str(uuid.uuid4())
-    customer = Customer.objects.create(name=name)
-
-    response = requests.post(f"{live_server}{reverse('customer/delete', args=[customer.pk])}")
+    response = requests.post(f"{live_server}{reverse('invoice/create')}", data=dict(name=name))
     response.raise_for_status()
-    assert not Customer.objects.filter(name=name).exists()
+    assert Invoice.objects.filter(name=name).exists()
+
 
-    # Assert model was created and audit exists
-    audit_entry: TriggerAuditEntry = TriggerAuditEntry.objects.filter(audit_operation="DELETE").get()
-    assert audit_entry.is_delete()
-    assert audit_entry.object_payload_json["name"] == name
+@pytest.mark.django_db(transaction=True)
+def test_create_product_works_with_audit_disabled(live_server, remove_auditing):
+    name = str(uuid.uuid4())
+    response = requests.post(f"{live_server}{reverse('product/create')}", data=dict(name=name))
+    response.raise_for_status()
+    assert Product.objects.filter(name=name).exists()
```

### Comparing `django-partitioned-audit-1.0.3/tests/test_concurrent.py` & `django-partitioned-audit-1.0.4/tests/test_concurrent.py`

 * *Files 8% similar despite different names*

```diff
@@ -6,19 +6,21 @@
 from typing import List
 
 import pytest
 import requests
 from app.models import Customer
 from django.urls import reverse
 
-from django_partitioned_audit.models import TriggerAuditEntry
+from django_partitioned_audit.models import SimpleAuditEntry
+from tests.conftest import skipifadvanced
 
 # pylint: skip-file
 
 
+@skipifadvanced
 @pytest.mark.skipif(os.environ.get("SKIP_SLOW"), reason="skipping slow tests")
 @pytest.mark.django_db(transaction=True)
 def test_concurrent_modifications(live_server, partition_created):
     customer = Customer.objects.create(name=str(uuid.uuid4()))
     urls = [
         f"{live_server}{reverse('customer/update', args=[customer.pk])}?pre-wait-ms=0&post-wait-ms=0",
         f"{live_server}{reverse('customer/update', args=[customer.pk])}?pre-wait-ms=100&post-wait-ms=0",
@@ -45,11 +47,11 @@
                 future.result()
             except Exception:
                 raise
             else:
                 print("+", end="")
 
     # We need one audit entry for creation, then 1 audit entry for each update
-    assert TriggerAuditEntry.objects.all().count() == len(new_names) + 1
-    audit_entries: List[TriggerAuditEntry] = TriggerAuditEntry.objects.all()
-    names_in_audit = [_.object_payload_json["name"] for _ in audit_entries]
+    assert SimpleAuditEntry.objects.all().count() == len(new_names) + 1
+    audit_entries: List[SimpleAuditEntry] = SimpleAuditEntry.objects.all()
+    names_in_audit = [_.get_row_data()["name"] for _ in audit_entries]
     assert set(names_in_audit) == set([customer.name] + new_names)
```

### Comparing `django-partitioned-audit-1.0.3/tests/test_examples_on_readme.py` & `django-partitioned-audit-1.0.4/tests/test_examples_on_readme.py`

 * *Files 14% similar despite different names*

```diff
@@ -33,21 +33,21 @@
         for line in lines:
             print(f"    {line}")
         print("")
 
 
 @pytest.mark.skipif(os.environ.get("TEST_README") != "1", reason="TEST_README")
 @pytest.mark.django_db(transaction=True)
-def test_simple_create(post_drop_partitions):
+def test_simple_create(truncate_partitions):
     run_command("create", "--extra-days=60")
 
 
 @pytest.mark.skipif(os.environ.get("TEST_README") != "1", reason="TEST_README")
 @pytest.mark.django_db(transaction=True)
-def test_sample_workflow(post_drop_partitions):
+def test_sample_workflow(truncate_partitions):
     print_unindented(
         """
     Sample usage
     ++++++++++++
 
     If you want to have enough partition to handle next 90 days (around 3 months), you can use `--extra-days=90`.
     Because it's the first time we run the command, no partition exists, and the plan will report that all
@@ -81,29 +81,29 @@
     """
     )
     run_command("list")
 
 
 @pytest.mark.skipif(os.environ.get("TEST_README") != "1", reason="TEST_README")
 @pytest.mark.django_db(transaction=True)
-def test_sample_workflow_weekly(post_drop_partitions):
+def test_sample_workflow_weekly(truncate_partitions):
     print_unindented(
         """
     Partition per week
     ++++++++++++++++++
 
     We can use one partition per week::
     """
     )
     run_command("create", "--extra-days=30", "--time-range-generator=WeeklyTimeRangeGenerator")
 
 
 @pytest.mark.skipif(os.environ.get("TEST_README") != "1", reason="TEST_README")
 @pytest.mark.django_db(transaction=True)
-def test_sample_workflow_daily(post_drop_partitions):
+def test_sample_workflow_daily(truncate_partitions):
     print_unindented(
         """
     Partition per day
     +++++++++++++++++
 
     We can use one partition per day::
     """
```

### Comparing `django-partitioned-audit-1.0.3/tests/test_management_commands.py` & `django-partitioned-audit-1.0.4/tests/test_management_commands.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,14 +5,15 @@
 from unittest.mock import Mock
 from unittest.mock import PropertyMock
 from unittest.mock import patch
 
 import pytest
 from django.core import management
 
+from django_partitioned_audit.audit_table.audit_table_manager import AuditTableManager
 from django_partitioned_audit.partitions.partition_manager_time_range import PartitionManager
 
 # pylint: skip-file
 
 
 @pytest.mark.django_db(transaction=True)
 def test_flush():
@@ -21,57 +22,62 @@
 
 @pytest.mark.django_db(transaction=True)
 def test_migrate():
     management.call_command("migrate", verbosity=0, interactive=False)
 
 
 @pytest.mark.django_db(transaction=True)
-def test_manage_partition_tables_create_monthly(post_drop_partitions):
+def test_manage_partition_tables_create_monthly(truncate_partitions, audit_table_manager: AuditTableManager):
+    partitioned_table = audit_table_manager.partitioned_table_name
     with patch.object(PartitionManager, "get_existing_partitions", new_callable=Mock) as mock_partitions:
         with patch.object(PartitionManager, "today", new_callable=PropertyMock) as mock_today:
             mock_partitions.return_value = []
             mock_today.return_value = date(1877, 3, 22)
             out = StringIO()
             management.call_command("manage_partition_tables", "create", verbosity=0, stdout=out)
             lines: List[str] = out.getvalue().splitlines()
             assert lines
 
-            lines_tables = [_ for _ in lines if re.search(r"trigger_audit_entries_v2.*to create", _)]
+            lines_tables = [_ for _ in lines if re.search(rf"{partitioned_table}.*to create", _)]
             assert len(lines_tables) == 2
-            assert any([re.search(r"trigger_audit_entries_v2_18770301_18770401.*to create", _) for _ in lines_tables])
-            assert any([re.search(r"trigger_audit_entries_v2_18770401_18770501.*to create", _) for _ in lines_tables])
+            assert any([re.search(rf"{partitioned_table}_18770301_18770401.*to create", _) for _ in lines_tables])
+            assert any([re.search(rf"{partitioned_table}_18770401_18770501.*to create", _) for _ in lines_tables])
 
 
 @pytest.mark.django_db(transaction=True)
-def test_manage_partition_tables_create_weekly(post_drop_partitions):
+def test_manage_partition_tables_create_weekly(truncate_partitions, audit_table_manager: AuditTableManager):
+    partitioned_table = audit_table_manager.partitioned_table_name
+
     with patch.object(PartitionManager, "today", new_callable=PropertyMock) as mock_today:
         mock_today.return_value = date(1877, 3, 22)
 
         out = StringIO()
         management.call_command(
             "manage_partition_tables",
             "create",
             "--time-range-generator=WeeklyTimeRangeGenerator",
             verbosity=0,
             stdout=out,
         )
         lines: List[str] = out.getvalue().splitlines()
         assert lines
 
-        lines_tables = [_ for _ in lines if re.search(r"trigger_audit_entries_v2.*to create", _)]
+        lines_tables = [_ for _ in lines if re.search(rf"{partitioned_table}.*to create", _)]
         assert len(lines_tables) == 5
-        assert any([re.search(r"trigger_audit_entries_v2_18770322_18770329.*to create", _) for _ in lines_tables])
-        assert any([re.search(r"trigger_audit_entries_v2_18770329_18770405.*to create", _) for _ in lines_tables])
-        assert any([re.search(r"trigger_audit_entries_v2_18770405_18770412.*to create", _) for _ in lines_tables])
-        assert any([re.search(r"trigger_audit_entries_v2_18770412_18770419.*to create", _) for _ in lines_tables])
-        assert any([re.search(r"trigger_audit_entries_v2_18770419_18770426.*to create", _) for _ in lines_tables])
+        assert any([re.search(rf"{partitioned_table}_18770322_18770329.*to create", _) for _ in lines_tables])
+        assert any([re.search(rf"{partitioned_table}_18770329_18770405.*to create", _) for _ in lines_tables])
+        assert any([re.search(rf"{partitioned_table}_18770405_18770412.*to create", _) for _ in lines_tables])
+        assert any([re.search(rf"{partitioned_table}_18770412_18770419.*to create", _) for _ in lines_tables])
+        assert any([re.search(rf"{partitioned_table}_18770419_18770426.*to create", _) for _ in lines_tables])
 
 
 @pytest.mark.django_db(transaction=True)
-def test_manage_partition_tables_create_daily(post_drop_partitions):
+def test_manage_partition_tables_create_daily(truncate_partitions, audit_table_manager: AuditTableManager):
+    partitioned_table = audit_table_manager.partitioned_table_name
+
     with patch.object(PartitionManager, "today", new_callable=PropertyMock) as mock_today:
         mock_today.return_value = date(1877, 3, 22)
 
         out = StringIO()
         management.call_command(
             "manage_partition_tables",
             "create",
@@ -79,45 +85,47 @@
             "--extra-days=6",
             verbosity=0,
             stdout=out,
         )
         lines: List[str] = out.getvalue().splitlines()
         assert lines
 
-        lines_tables = [_ for _ in lines if re.search(r"trigger_audit_entries_v2.*to create", _)]
+        lines_tables = [_ for _ in lines if re.search(rf"{partitioned_table}.*to create", _)]
         assert len(lines_tables) == 7
-        assert any([re.search(r"trigger_audit_entries_v2_18770322_18770323.*to create", _) for _ in lines_tables])
-        assert any([re.search(r"trigger_audit_entries_v2_18770323_18770324.*to create", _) for _ in lines_tables])
-        assert any([re.search(r"trigger_audit_entries_v2_18770324_18770325.*to create", _) for _ in lines_tables])
-        assert any([re.search(r"trigger_audit_entries_v2_18770325_18770326.*to create", _) for _ in lines_tables])
-        assert any([re.search(r"trigger_audit_entries_v2_18770326_18770327.*to create", _) for _ in lines_tables])
-        assert any([re.search(r"trigger_audit_entries_v2_18770327_18770328.*to create", _) for _ in lines_tables])
-        assert any([re.search(r"trigger_audit_entries_v2_18770328_18770329.*to create", _) for _ in lines_tables])
+        assert any([re.search(rf"{partitioned_table}_18770322_18770323.*to create", _) for _ in lines_tables])
+        assert any([re.search(rf"{partitioned_table}_18770323_18770324.*to create", _) for _ in lines_tables])
+        assert any([re.search(rf"{partitioned_table}_18770324_18770325.*to create", _) for _ in lines_tables])
+        assert any([re.search(rf"{partitioned_table}_18770325_18770326.*to create", _) for _ in lines_tables])
+        assert any([re.search(rf"{partitioned_table}_18770326_18770327.*to create", _) for _ in lines_tables])
+        assert any([re.search(rf"{partitioned_table}_18770327_18770328.*to create", _) for _ in lines_tables])
+        assert any([re.search(rf"{partitioned_table}_18770328_18770329.*to create", _) for _ in lines_tables])
 
 
 @pytest.mark.django_db(transaction=True)
-def test_manage_partition_tables_create_twice(post_drop_partitions):
+def test_manage_partition_tables_create_twice(truncate_partitions, audit_table_manager: AuditTableManager):
+    partitioned_table = audit_table_manager.partitioned_table_name
+
     with patch.object(PartitionManager, "today", new_callable=PropertyMock) as mock_today:
         mock_today.return_value = date(1877, 3, 22)
 
         out = StringIO()
         management.call_command("manage_partition_tables", "create", verbosity=0, stdout=out)
         lines: List[str] = out.getvalue().splitlines()
         assert lines
 
-        lines_tables = [_ for _ in lines if re.search(r"trigger_audit_entries_v2.*to create", _)]
+        lines_tables = [_ for _ in lines if re.search(rf"{partitioned_table}.*to create", _)]
         assert len(lines_tables) == 2
-        assert any([re.search(r"trigger_audit_entries_v2_18770301_18770401.*to create", _) for _ in lines_tables])
-        assert any([re.search(r"trigger_audit_entries_v2_18770401_18770501.*to create", _) for _ in lines_tables])
+        assert any([re.search(rf"{partitioned_table}_18770301_18770401.*to create", _) for _ in lines_tables])
+        assert any([re.search(rf"{partitioned_table}_18770401_18770501.*to create", _) for _ in lines_tables])
 
         out = StringIO()
         management.call_command("manage_partition_tables", "create", verbosity=0, stdout=out)
         lines: List[str] = out.getvalue().splitlines()
         assert lines
 
-        lines_tables = [_ for _ in lines if re.search(r"trigger_audit_entries_v2.*to create", _)]
+        lines_tables = [_ for _ in lines if re.search(rf"{partitioned_table}.*to create", _)]
         assert len(lines_tables) == 0
 
-        lines_tables = [_ for _ in lines if re.search(r"trigger_audit_entries_v2.*exists", _)]
+        lines_tables = [_ for _ in lines if re.search(rf"{partitioned_table}.*exists", _)]
         assert len(lines_tables) == 2
-        assert any([re.search(r"trigger_audit_entries_v2_18770301_18770401.*exists", _) for _ in lines_tables])
-        assert any([re.search(r"trigger_audit_entries_v2_18770401_18770501.*exists", _) for _ in lines_tables])
+        assert any([re.search(rf"{partitioned_table}_18770301_18770401.*exists", _) for _ in lines_tables])
+        assert any([re.search(rf"{partitioned_table}_18770401_18770501.*exists", _) for _ in lines_tables])
```

### Comparing `django-partitioned-audit-1.0.3/tests/test_non_standard_pk.py` & `django-partitioned-audit-1.0.4/tests/test_non_standard_pk.py`

 * *Files 14% similar despite different names*

```diff
@@ -2,38 +2,41 @@
 
 import pytest
 import requests
 from app.models import Invoice
 from app.models import Product
 from django.urls import reverse
 
-from django_partitioned_audit.models import TriggerAuditEntry
+from django_partitioned_audit.models import SimpleAuditEntry
+from tests.conftest import skipifadvanced
 
 # pylint: skip-file
 
 
+@skipifadvanced
 @pytest.mark.django_db(transaction=True)
 def test_pk_named_product_id(live_server, partition_created):
     name = str(uuid.uuid4())
     response = requests.post(f"{live_server}{reverse('product/create')}", data=dict(name=name))
     response.raise_for_status()
     assert Product.objects.filter(name=name).exists()
 
     # Assert model was created and audit exists
-    audit_entry: TriggerAuditEntry = TriggerAuditEntry.objects.all().get()
+    audit_entry: SimpleAuditEntry = SimpleAuditEntry.objects.all().get()
     assert audit_entry.is_insert()
-    assert audit_entry.object_payload_json["product_id"]
-    assert audit_entry.object_payload_json["name"] == name
+    assert audit_entry.get_row_data()["product_id"]
+    assert audit_entry.get_row_data()["name"] == name
 
 
+@skipifadvanced
 @pytest.mark.django_db(transaction=True)
 def test_pk_is_uuid(live_server, partition_created):
     name = str(uuid.uuid4())
     response = requests.post(f"{live_server}{reverse('invoice/create')}", data=dict(name=name))
     response.raise_for_status()
     assert Invoice.objects.filter(name=name).exists()
 
     # Assert model was created and audit exists
-    audit_entry: TriggerAuditEntry = TriggerAuditEntry.objects.all().get()
+    audit_entry: SimpleAuditEntry = SimpleAuditEntry.objects.all().get()
     assert audit_entry.is_insert()
-    assert audit_entry.object_payload_json["id"]
-    assert audit_entry.object_payload_json["name"] == name
+    assert audit_entry.get_row_data()["id"]
+    assert audit_entry.get_row_data()["name"] == name
```

### Comparing `django-partitioned-audit-1.0.3/tests/test_partition_info.py` & `django-partitioned-audit-1.0.4/tests/test_partition_info.py`

 * *Files 2% similar despite different names*

```diff
@@ -41,12 +41,12 @@
     sql_line = " ".join([_.strip() for _ in sql.splitlines() if _.strip()])
     sql_line = " ".join([_.strip() for _ in sql_line.split() if _.strip()])
     sql_line = sql_line.lower()
     sql_line = sql_line.replace("%s", "{}")
     # not exactly the same interpolation done by db driver, but usable for tests
     final_sql = sql_line.format(*params)
     expected_sql = (
-        """create table "foo_19980102_19990304" """
-        """partition of "foo" """
+        """create table foo_19980102_19990304 """
+        """partition of foo """
         """for values from (1998-01-02) to (1999-03-04);"""
     )
     assert final_sql == expected_sql
```

### Comparing `django-partitioned-audit-1.0.3/tests/test_partition_manager_base.py` & `django-partitioned-audit-1.0.4/tests/test_partition_manager_base.py`

 * *Files 22% similar despite different names*

```diff
@@ -1,38 +1,44 @@
 import pytest
 from django.db import connection
 
+from django_partitioned_audit.audit_table.audit_table_manager import AuditTableManager
 from django_partitioned_audit.partitions.partition_info import PartitionInfo
 from django_partitioned_audit.partitions.partition_manager_time_range import BasePartitionManager
 from django_partitioned_audit.partitions.partition_manager_time_range import PartitionManager
 from django_partitioned_audit.partitions.time_range_partitioning import MonthlyTimeRangeGenerator as MTRG
 from django_partitioned_audit.partitions.time_range_partitioning import NotImplementedTimeRangeGenerator
+from tests.dummies import DummyAuditTableManager
 
 
 @pytest.mark.django_db(transaction=True)
 @pytest.mark.parametrize("tmg_class", [MTRG, NotImplementedTimeRangeGenerator])
-def test_get_tables(tmg_class):
+def test_get_tables(tmg_class, audit_table_manager: AuditTableManager):
     pm = BasePartitionManager(time_range_generator=tmg_class())
     tables = pm.get_tables()
-    assert set(tables) == {
+    assert set(tables) >= {
         "app_customer",
         "app_invoice",
+        "app_invoiceitem",
         "app_product",
+        "second_app_customer",
+        "second_app_invoice",
+        "second_app_product",
         "auth_group",
         "auth_group_permissions",
         "auth_permission",
         "auth_user",
         "auth_user_groups",
         "auth_user_user_permissions",
         "django_admin_log",
         "django_content_type",
         "django_migrations",
         "django_session",
-        "trigger_audit_entries_v2",
-        "trigger_audit_entries_v2_view",
+        audit_table_manager.partitioned_table_name,
+        f"{audit_table_manager.partitioned_table_name}_view",
     }
 
 
 @pytest.mark.django_db(transaction=True)
 @pytest.mark.parametrize("tmg_class", [MTRG, NotImplementedTimeRangeGenerator])
 def test_get_existing_partitions_when_partitions_exists(partitioned_table: str, tmg_class):
     with connection.cursor() as cursor:
@@ -41,34 +47,34 @@
             PARTITION OF {partitioned_table}
             FOR VALUES FROM ('1999-01-01') TO ('1999-02-01');
         """
         cursor.execute(sql)
 
     partition = f"{partitioned_table}_19990101_19990201"
 
-    pm = PartitionManager(partitioned_table=partitioned_table, time_range_generator=tmg_class())
+    pm = PartitionManager(audit_manager=DummyAuditTableManager(partitioned_table), time_range_generator=tmg_class())
     assert partitioned_table in pm.get_tables()
     assert partition in pm.get_tables()
 
     assert set(pm.get_existing_partitions()) == {PartitionInfo.parse(partition)}
 
 
 @pytest.mark.django_db
 @pytest.mark.parametrize("tmg_class", [MTRG, NotImplementedTimeRangeGenerator])
 def test_get_existing_partitions_when_no_partitions(partitioned_table: str, tmg_class):
-    pm = PartitionManager(partitioned_table=partitioned_table, time_range_generator=tmg_class())
+    pm = PartitionManager(time_range_generator=tmg_class())
     assert partitioned_table in pm.get_tables()
     partitions = list(pm.get_existing_partitions())
     assert len(partitions) == 0
 
 
 @pytest.mark.django_db
 @pytest.mark.parametrize("tmg_class", [MTRG, NotImplementedTimeRangeGenerator])
 def test_create_partitions(partitioned_table: str, tmg_class):
-    pm = PartitionManager(partitioned_table=partitioned_table, time_range_generator=tmg_class())
+    pm = PartitionManager(audit_manager=DummyAuditTableManager(partitioned_table), time_range_generator=tmg_class())
 
     partition = f"{partitioned_table}_19990101_19990201"
     partition_info = PartitionInfo.parse(partition)
 
     assert partitioned_table in pm.get_tables()
     assert partition not in pm.get_tables()
```

### Comparing `django-partitioned-audit-1.0.3/tests/test_partition_manager_create.py` & `django-partitioned-audit-1.0.4/tests/test_partition_manager_create.py`

 * *Files 5% similar despite different names*

```diff
@@ -6,21 +6,22 @@
 
 import pytest
 from django.db import ProgrammingError
 
 from django_partitioned_audit.partitions.partition_info import PartitionInfo
 from django_partitioned_audit.partitions.partition_manager_time_range import PartitionManager
 from django_partitioned_audit.partitions.time_range_partitioning import MonthlyTimeRangeGenerator as MTRG
+from tests.dummies import DummyAuditTableManager
 
 # pylint: skip-file
 
 
 @pytest.mark.django_db(transaction=True)
 def test_create_partition(partitioned_table: str):
-    pm = PartitionManager(partitioned_table=partitioned_table, time_range_generator=MTRG())
+    pm = PartitionManager(audit_manager=DummyAuditTableManager(partitioned_table), time_range_generator=MTRG())
     assert not list(pm.get_existing_partitions())
 
     pm.create_partitions(
         [
             PartitionInfo.create(
                 partitioned_table=partitioned_table,
                 from_date=date(1999, 1, 1),
@@ -45,11 +46,11 @@
     bad = f"abcdefghi_{uuid4().hex[0:9]}_{uuid4().hex[0:9]}_{uuid4().hex[0:9]}_{uuid4().hex[0:9]}_abcdefgh"
     partition_1 = PartitionInfo.create(bad, date(1999, 1, 1), date(1999, 2, 1))
     partition_2 = PartitionInfo.create(bad, date(1999, 2, 1), date(1999, 3, 1))
 
     partitioned_table_create(bad)
 
     with patch.object(PartitionManager, "_validate_partitioned_table", new_callable=Mock):
-        pm = PartitionManager(partitioned_table=bad, time_range_generator=MTRG())
+        pm = PartitionManager(audit_manager=DummyAuditTableManager(bad), time_range_generator=MTRG())
         pm.create_partitions([partition_1])
         with pytest.raises(ProgrammingError, match=r'relation.*abcdefghi_[a-f0-9_]+_abcdefgh_1999" already exists'):
             pm.create_partitions([partition_2])
```

### Comparing `django-partitioned-audit-1.0.3/tests/test_partition_manager_simulate.py` & `django-partitioned-audit-1.0.4/tests/test_partition_manager_simulate.py`

 * *Files 14% similar despite different names*

```diff
@@ -10,44 +10,45 @@
 from django_partitioned_audit.partitions.partition_manager_plan import Plan
 from django_partitioned_audit.partitions.partition_manager_plan import Status
 from django_partitioned_audit.partitions.partition_manager_time_range import PartitionManager
 from django_partitioned_audit.partitions.time_range_partitioning import DailyTimeRangeGenerator
 from django_partitioned_audit.partitions.time_range_partitioning import MonthlyTimeRangeGenerator
 from django_partitioned_audit.partitions.time_range_partitioning import TimeRangeGenerator
 from django_partitioned_audit.partitions.time_range_partitioning import WeeklyTimeRangeGenerator
+from tests.conftest import skipifadvanced
 
 
 class MonthlyScenario:
-    prev2: PartitionInfo = PartitionInfo.parse("trigger_audit_entries_v2_18770101_18770201")
-    prev1: PartitionInfo = PartitionInfo.parse("trigger_audit_entries_v2_18770201_18770301")
-    cur: PartitionInfo = PartitionInfo.parse("trigger_audit_entries_v2_18770301_18770401")
-    next1: PartitionInfo = PartitionInfo.parse("trigger_audit_entries_v2_18770401_18770501")
-    next2: PartitionInfo = PartitionInfo.parse("trigger_audit_entries_v2_18770501_18770601")
+    prev2: PartitionInfo = PartitionInfo.parse("audit_simple_18770101_18770201")
+    prev1: PartitionInfo = PartitionInfo.parse("audit_simple_18770201_18770301")
+    cur: PartitionInfo = PartitionInfo.parse("audit_simple_18770301_18770401")
+    next1: PartitionInfo = PartitionInfo.parse("audit_simple_18770401_18770501")
+    next2: PartitionInfo = PartitionInfo.parse("audit_simple_18770501_18770601")
     extra_days: int = 45
     extra_days_current_time_range: int = 9  # `today=1877-03-22`, 9 days left in this month
     tmg_impl: Type[TimeRangeGenerator] = MonthlyTimeRangeGenerator
 
 
 class WeeklyScenario:
-    prev2: PartitionInfo = PartitionInfo.parse("trigger_audit_entries_v2_18770308_18770315")
-    prev1: PartitionInfo = PartitionInfo.parse("trigger_audit_entries_v2_18770315_18770322")
-    cur: PartitionInfo = PartitionInfo.parse("trigger_audit_entries_v2_18770322_18770329")
-    next1: PartitionInfo = PartitionInfo.parse("trigger_audit_entries_v2_18770329_18770405")
-    next2: PartitionInfo = PartitionInfo.parse("trigger_audit_entries_v2_18770405_18770412")
+    prev2: PartitionInfo = PartitionInfo.parse("audit_simple_18770308_18770315")
+    prev1: PartitionInfo = PartitionInfo.parse("audit_simple_18770315_18770322")
+    cur: PartitionInfo = PartitionInfo.parse("audit_simple_18770322_18770329")
+    next1: PartitionInfo = PartitionInfo.parse("audit_simple_18770329_18770405")
+    next2: PartitionInfo = PartitionInfo.parse("audit_simple_18770405_18770412")
     extra_days: int = 18
     extra_days_current_time_range: int = 6
     tmg_impl: Type[TimeRangeGenerator] = WeeklyTimeRangeGenerator
 
 
 class DailyScenario:
-    prev2: PartitionInfo = PartitionInfo.parse("trigger_audit_entries_v2_18770320_18770321")
-    prev1: PartitionInfo = PartitionInfo.parse("trigger_audit_entries_v2_18770321_18770322")
-    cur: PartitionInfo = PartitionInfo.parse("trigger_audit_entries_v2_18770322_18770323")
-    next1: PartitionInfo = PartitionInfo.parse("trigger_audit_entries_v2_18770323_18770324")
-    next2: PartitionInfo = PartitionInfo.parse("trigger_audit_entries_v2_18770324_18770325")
+    prev2: PartitionInfo = PartitionInfo.parse("audit_simple_18770320_18770321")
+    prev1: PartitionInfo = PartitionInfo.parse("audit_simple_18770321_18770322")
+    cur: PartitionInfo = PartitionInfo.parse("audit_simple_18770322_18770323")
+    next1: PartitionInfo = PartitionInfo.parse("audit_simple_18770323_18770324")
+    next2: PartitionInfo = PartitionInfo.parse("audit_simple_18770324_18770325")
     extra_days: int = 2
     extra_days_current_time_range: int = 0
     tmg_impl: Type[TimeRangeGenerator] = DailyTimeRangeGenerator
 
 
 def generate_scenarios():
     for scenario in [MonthlyScenario, WeeklyScenario, DailyScenario]:
@@ -136,14 +137,15 @@
             scenario.tmg_impl,
         )
 
 
 scenarios = list(generate_scenarios())
 
 
+@skipifadvanced
 @pytest.mark.parametrize("desc,existing_partitions,extra_days,exp_status,exp_new,trg_class", scenarios)
 def test_simulate_scenarios(desc, existing_partitions, extra_days, exp_status, exp_new, trg_class):
     assert all([isinstance(_, PartitionInfo) for _ in existing_partitions])
     assert isinstance(extra_days, int)
     assert 0 <= extra_days <= 365
     assert exp_status in {Status.OK, Status.MISSING_CURRENT, Status.MISSING_NEXT}
     assert all([isinstance(_, PartitionInfo) for _ in exp_new])
```

### Comparing `django-partitioned-audit-1.0.3/tests/test_partition_manager_time_range.py` & `django-partitioned-audit-1.0.4/tests/test_partition_manager_time_range.py`

 * *Files 12% similar despite different names*

```diff
@@ -3,29 +3,30 @@
 from typing import Union
 from unittest.mock import Mock
 from unittest.mock import PropertyMock
 from unittest.mock import patch
 
 import pytest
 
+from django_partitioned_audit.audit_table.audit_table_manager import AuditTableManager
 from django_partitioned_audit.partitions.partition_info import PartitionInfo
 from django_partitioned_audit.partitions.partition_manager_time_range import PartitionManager
 from django_partitioned_audit.partitions.time_range_partitioning import MonthlyTimeRangeGenerator
 
 
-def test_generate_partition_info_for_current_period():
+def test_generate_partition_info_for_current_period(audit_table_manager: AuditTableManager):
     pm = PartitionManager(time_range_generator=MonthlyTimeRangeGenerator())
     with patch.object(PartitionManager, "today", new_callable=PropertyMock) as mock:
         mock.return_value = date(1988, 3, 22)
         partition_info = pm.generate_partition_info_for_current_period()
-        assert partition_info.partition == "trigger_audit_entries_v2_19880301_19880401"
+        assert partition_info.partition == f"{audit_table_manager.partitioned_table_name}_19880301_19880401"
 
         mock.return_value = date(1988, 12, 22)
         partition_info = pm.generate_partition_info_for_current_period()
-        assert partition_info.partition == "trigger_audit_entries_v2_19881201_19890101"
+        assert partition_info.partition == f"{audit_table_manager.partitioned_table_name}_19881201_19890101"
 
 
 def test_new_partition():
     pm = PartitionManager(time_range_generator=MonthlyTimeRangeGenerator())
     previous = PartitionInfo.create("part", date(1991, 1, 1), date(1991, 2, 1))
 
     assert pm.new_partition(previous) == PartitionInfo.create("part", date(1991, 2, 1), date(1991, 3, 1))
@@ -46,84 +47,86 @@
 
     assert pm.new_partition(PartitionInfo.create("part", date(1991, 1, 1), date(1991, 1, 31))) == PartitionInfo.create(
         "part", date(1991, 1, 31), date(1991, 2, 1)
     )
 
 
 @pytest.mark.parametrize("params", [0, 1, 2, 30, [31], [32], [45], [55]])
-def test_generate_plan_when_no_partition_exists(params: Union[int, List[int]]):
+def test_generate_plan_when_no_partition_exists(params: Union[int, List[int]], audit_table_manager: AuditTableManager):
     if isinstance(params, int):
         extra_days = params
         expected_partitions_to_create = [
-            PartitionInfo.create(PartitionManager.default_partitioned_table, date(1991, 3, 1), date(1991, 4, 1)),
+            PartitionInfo.create(audit_table_manager.partitioned_table_name, date(1991, 3, 1), date(1991, 4, 1)),
         ]
     else:
         extra_days = params[0]
         expected_partitions_to_create = [
-            PartitionInfo.create(PartitionManager.default_partitioned_table, date(1991, 3, 1), date(1991, 4, 1)),
-            PartitionInfo.create(PartitionManager.default_partitioned_table, date(1991, 4, 1), date(1991, 5, 1)),
+            PartitionInfo.create(audit_table_manager.partitioned_table_name, date(1991, 3, 1), date(1991, 4, 1)),
+            PartitionInfo.create(audit_table_manager.partitioned_table_name, date(1991, 4, 1), date(1991, 5, 1)),
         ]
 
     pm = PartitionManager(extra_days=extra_days, time_range_generator=MonthlyTimeRangeGenerator())
     with patch.object(PartitionManager, "today", new_callable=PropertyMock) as mock_today:
         mock_today.return_value = date(1991, 3, 1)
         with patch.object(PartitionManager, "get_existing_partitions", new_callable=Mock) as mock_part:
             mock_part.return_value = []
 
             plan = pm.generate_plan()
             assert plan.existing_partitions == []
             assert plan.partitions_to_create == expected_partitions_to_create
 
 
 @pytest.mark.parametrize("params", [0, 1, 2, 30, [31], [32], [45], [55]])
-def test_generate_plan_when_partition_exists(params: Union[int, List[int]]):
+def test_generate_plan_when_partition_exists(params: Union[int, List[int]], audit_table_manager: AuditTableManager):
     if isinstance(params, int):
         extra_days = params
         expected_created = []
     else:
         extra_days = params[0]
         expected_created = [
-            PartitionInfo.create(PartitionManager.default_partitioned_table, date(1991, 4, 1), date(1991, 5, 1)),
+            PartitionInfo.create(audit_table_manager.partitioned_table_name, date(1991, 4, 1), date(1991, 5, 1)),
         ]
 
     pm = PartitionManager(extra_days=extra_days, time_range_generator=MonthlyTimeRangeGenerator())
     with patch.object(PartitionManager, "today", new_callable=PropertyMock) as mock_today:
         mock_today.return_value = date(1991, 3, 1)
         with patch.object(PartitionManager, "get_existing_partitions", new_callable=Mock) as mock_part:
             mock_part.return_value = [
-                PartitionInfo.create(PartitionManager.default_partitioned_table, date(1991, 3, 1), date(1991, 4, 1)),
+                PartitionInfo.create(audit_table_manager.partitioned_table_name, date(1991, 3, 1), date(1991, 4, 1)),
             ]
 
             plan = pm.generate_plan()
             assert plan.existing_partitions == [
-                PartitionInfo.create(PartitionManager.default_partitioned_table, date(1991, 3, 1), date(1991, 4, 1)),
+                PartitionInfo.create(audit_table_manager.partitioned_table_name, date(1991, 3, 1), date(1991, 4, 1)),
             ]
             assert plan.partitions_to_create == expected_created
 
 
 @pytest.mark.parametrize("params", [0, 1, 16, [17], [30]])
-def test_generate_plan_when_partition_exists_but_not_for_current(params: Union[int, List[int]]):
+def test_generate_plan_when_partition_exists_but_not_for_current(
+    params: Union[int, List[int]], audit_table_manager: AuditTableManager
+):
     if isinstance(params, int):
         extra_days = params
         expected_created = [
-            PartitionInfo.create(PartitionManager.default_partitioned_table, date(1991, 3, 1), date(1991, 4, 1)),
+            PartitionInfo.create(audit_table_manager.partitioned_table_name, date(1991, 3, 1), date(1991, 4, 1)),
         ]
     else:
         extra_days = params[0]
         expected_created = [
-            PartitionInfo.create(PartitionManager.default_partitioned_table, date(1991, 3, 1), date(1991, 4, 1)),
-            PartitionInfo.create(PartitionManager.default_partitioned_table, date(1991, 4, 1), date(1991, 5, 1)),
+            PartitionInfo.create(audit_table_manager.partitioned_table_name, date(1991, 3, 1), date(1991, 4, 1)),
+            PartitionInfo.create(audit_table_manager.partitioned_table_name, date(1991, 4, 1), date(1991, 5, 1)),
         ]
 
     pm = PartitionManager(extra_days=extra_days, time_range_generator=MonthlyTimeRangeGenerator())
     with patch.object(PartitionManager, "today", new_callable=PropertyMock) as mock_today:
         mock_today.return_value = date(1991, 3, 15)
         with patch.object(PartitionManager, "get_existing_partitions", new_callable=Mock) as mock_part:
             mock_part.return_value = [
-                PartitionInfo.create(PartitionManager.default_partitioned_table, date(1991, 2, 1), date(1991, 3, 1)),
+                PartitionInfo.create(audit_table_manager.partitioned_table_name, date(1991, 2, 1), date(1991, 3, 1)),
             ]
 
             plan = pm.generate_plan()
             assert plan.existing_partitions == [
-                PartitionInfo.create(PartitionManager.default_partitioned_table, date(1991, 2, 1), date(1991, 3, 1)),
+                PartitionInfo.create(audit_table_manager.partitioned_table_name, date(1991, 2, 1), date(1991, 3, 1)),
             ]
             assert plan.partitions_to_create == expected_created
```

### Comparing `django-partitioned-audit-1.0.3/tests/test_partition_manager_time_range_plan.py` & `django-partitioned-audit-1.0.4/tests/test_partition_manager_time_range_plan.py`

 * *Files identical despite different names*


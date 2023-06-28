# Comparing `tmp/port_ocean-0.1.0.dev1.tar.gz` & `tmp/port_ocean-0.1.0.dev2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "port_ocean-0.1.0.dev1.tar", max compression
+gzip compressed data, was "port_ocean-0.1.0.dev2.tar", max compression
```

## Comparing `port_ocean-0.1.0.dev1.tar` & `port_ocean-0.1.0.dev2.tar`

### file list

```diff
@@ -1,62 +1,67 @@
--rw-r--r--   0        0        0     3218 2023-06-26 14:41:58.550973 port_ocean-0.1.0.dev1/README.md
--rw-r--r--   0        0        0      440 2023-06-26 14:41:58.586973 port_ocean-0.1.0.dev1/port_ocean/__init__.py
--rw-r--r--   0        0        0        0 2023-06-26 14:41:58.586973 port_ocean-0.1.0.dev1/port_ocean/cli/__init__.py
--rw-r--r--   0        0        0      121 2023-06-26 14:41:58.586973 port_ocean-0.1.0.dev1/port_ocean/cli/cli.py
--rw-r--r--   0        0        0     3385 2023-06-26 14:41:58.586973 port_ocean-0.1.0.dev1/port_ocean/cli/commands.py
--rw-r--r--   0        0        0      429 2023-06-26 14:41:58.586973 port_ocean-0.1.0.dev1/port_ocean/cli/cookiecutter/cookiecutter.json
--rw-r--r--   0        0        0       54 2023-06-26 14:41:58.586973 port_ocean-0.1.0.dev1/port_ocean/cli/cookiecutter/{{cookiecutter.integration_slug}}/.dockerignore
--rw-r--r--   0        0        0      598 2023-06-26 14:41:58.586973 port_ocean-0.1.0.dev1/port_ocean/cli/cookiecutter/{{cookiecutter.integration_slug}}/Dockerfile
--rw-r--r--   0        0        0      751 2023-06-26 14:41:58.586973 port_ocean-0.1.0.dev1/port_ocean/cli/cookiecutter/{{cookiecutter.integration_slug}}/Makefile
--rw-r--r--   0        0        0      406 2023-06-26 14:41:58.586973 port_ocean-0.1.0.dev1/port_ocean/cli/cookiecutter/{{cookiecutter.integration_slug}}/README.md
--rw-r--r--   0        0        0     1091 2023-06-26 14:41:58.586973 port_ocean-0.1.0.dev1/port_ocean/cli/cookiecutter/{{cookiecutter.integration_slug}}/example.config.yaml
--rw-r--r--   0        0        0      404 2023-06-26 14:41:58.586973 port_ocean-0.1.0.dev1/port_ocean/cli/cookiecutter/{{cookiecutter.integration_slug}}/main.py
--rw-r--r--   0        0        0      640 2023-06-26 14:41:58.586973 port_ocean-0.1.0.dev1/port_ocean/cli/cookiecutter/{{cookiecutter.integration_slug}}/project.toml
--rw-r--r--   0        0        0        0 2023-06-26 14:41:58.586973 port_ocean-0.1.0.dev1/port_ocean/cli/cookiecutter/{{cookiecutter.integration_slug}}/tests/__init__.py
--rw-r--r--   0        0        0     1334 2023-06-26 14:41:58.586973 port_ocean-0.1.0.dev1/port_ocean/cli/download_git_folder.py
--rw-r--r--   0        0        0      766 2023-06-26 14:41:58.586973 port_ocean-0.1.0.dev1/port_ocean/cli/list_integrations.py
--rw-r--r--   0        0        0        0 2023-06-26 14:41:58.586973 port_ocean-0.1.0.dev1/port_ocean/clients/__init__.py
--rw-r--r--   0        0        0        0 2023-06-26 14:41:58.586973 port_ocean-0.1.0.dev1/port_ocean/clients/port/__init__.py
--rw-r--r--   0        0        0    11004 2023-06-26 14:41:58.586973 port_ocean-0.1.0.dev1/port_ocean/clients/port/client.py
--rw-r--r--   0        0        0      700 2023-06-26 14:41:58.586973 port_ocean-0.1.0.dev1/port_ocean/clients/port/types.py
--rw-r--r--   0        0        0        0 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/config/__init__.py
--rw-r--r--   0        0        0     1984 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/config/base.py
--rw-r--r--   0        0        0     1453 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/config/integration.py
--rw-r--r--   0        0        0        0 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/consumers/__init__.py
--rw-r--r--   0        0        0      125 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/consumers/base_consumer.py
--rw-r--r--   0        0        0     3785 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/consumers/kafka_consumer.py
--rw-r--r--   0        0        0        0 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/context/__init__.py
--rw-r--r--   0        0        0     1902 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/context/event.py
--rw-r--r--   0        0        0     3290 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/context/ocean.py
--rw-r--r--   0        0        0        0 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/core/__init__.py
--rw-r--r--   0        0        0      219 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/core/base.py
--rw-r--r--   0        0        0      300 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/core/handlers/__init__.py
--rw-r--r--   0        0        0        0 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/core/handlers/manipulation/__init__.py
--rw-r--r--   0        0        0      715 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/core/handlers/manipulation/base.py
--rw-r--r--   0        0        0     2822 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/core/handlers/manipulation/jq_manipulation.py
--rw-r--r--   0        0        0        0 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/core/handlers/port_app_config/__init__.py
--rw-r--r--   0        0        0      458 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/core/handlers/port_app_config/api.py
--rw-r--r--   0        0        0      657 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/core/handlers/port_app_config/base.py
--rw-r--r--   0        0        0     1438 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/core/handlers/port_app_config/models.py
--rw-r--r--   0        0        0        0 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/core/handlers/transport/__init__.py
--rw-r--r--   0        0        0      925 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/core/handlers/transport/base.py
--rw-r--r--   0        0        0        0 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/core/handlers/transport/port/__init__.py
--rw-r--r--   0        0        0     1205 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/core/handlers/transport/port/get_required_entities.py
--rw-r--r--   0        0        0     1062 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/core/handlers/transport/port/order_by_entities_dependencies.py
--rw-r--r--   0        0        0     4698 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/core/handlers/transport/port/transport.py
--rw-r--r--   0        0        0     1495 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/core/handlers/transport/port/validate_entity_relations.py
--rw-r--r--   0        0        0        0 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/core/integrations/__init__.py
--rw-r--r--   0        0        0     4283 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/core/integrations/base.py
--rw-r--r--   0        0        0     7212 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/core/integrations/mixins.py
--rw-r--r--   0        0        0      600 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/core/models.py
--rw-r--r--   0        0        0        0 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/core/trigger_channel/__init__.py
--rw-r--r--   0        0        0      444 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/core/trigger_channel/base_trigger_channel.py
--rw-r--r--   0        0        0     2106 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/core/trigger_channel/kafka_trigger_channel.py
--rw-r--r--   0        0        0     2657 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/core/trigger_channel/trigger_channel_factory.py
--rw-r--r--   0        0        0     1772 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/core/utils.py
--rw-r--r--   0        0        0      166 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/errors.py
--rw-r--r--   0        0        0      534 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/logging.py
--rw-r--r--   0        0        0     2815 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/middlewares.py
--rw-r--r--   0        0        0     4435 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/port_ocean.py
--rw-r--r--   0        0        0      583 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/port_ocean/types.py
--rw-r--r--   0        0        0     1845 2023-06-26 14:41:58.590973 port_ocean-0.1.0.dev1/pyproject.toml
--rw-r--r--   0        0        0     4247 1970-01-01 00:00:00.000000 port_ocean-0.1.0.dev1/PKG-INFO
+-rw-r--r--   0        0        0     3218 2023-06-28 11:41:00.486335 port_ocean-0.1.0.dev2/README.md
+-rw-r--r--   0        0        0      440 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/__init__.py
+-rw-r--r--   0        0        0        0 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/cli/__init__.py
+-rw-r--r--   0        0        0      121 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/cli/cli.py
+-rw-r--r--   0        0        0     3385 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/cli/commands.py
+-rw-r--r--   0        0        0      429 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/cli/cookiecutter/cookiecutter.json
+-rw-r--r--   0        0        0       54 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/cli/cookiecutter/{{cookiecutter.integration_slug}}/.dockerignore
+-rw-r--r--   0        0        0      598 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/cli/cookiecutter/{{cookiecutter.integration_slug}}/Dockerfile
+-rw-r--r--   0        0        0      751 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/cli/cookiecutter/{{cookiecutter.integration_slug}}/Makefile
+-rw-r--r--   0        0        0      406 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/cli/cookiecutter/{{cookiecutter.integration_slug}}/README.md
+-rw-r--r--   0        0        0     1091 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/cli/cookiecutter/{{cookiecutter.integration_slug}}/example.config.yaml
+-rw-r--r--   0        0        0      392 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/cli/cookiecutter/{{cookiecutter.integration_slug}}/main.py
+-rw-r--r--   0        0        0      640 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/cli/cookiecutter/{{cookiecutter.integration_slug}}/project.toml
+-rw-r--r--   0        0        0        0 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/cli/cookiecutter/{{cookiecutter.integration_slug}}/tests/__init__.py
+-rw-r--r--   0        0        0     1334 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/cli/download_git_folder.py
+-rw-r--r--   0        0        0      766 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/cli/list_integrations.py
+-rw-r--r--   0        0        0        0 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/clients/__init__.py
+-rw-r--r--   0        0        0        0 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/clients/port/__init__.py
+-rw-r--r--   0        0        0    10983 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/clients/port/client.py
+-rw-r--r--   0        0        0      593 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/clients/port/types.py
+-rw-r--r--   0        0        0        0 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/config/__init__.py
+-rw-r--r--   0        0        0     2592 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/config/base.py
+-rw-r--r--   0        0        0     1035 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/config/integration.py
+-rw-r--r--   0        0        0        0 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/consumers/__init__.py
+-rw-r--r--   0        0        0      125 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/consumers/base_consumer.py
+-rw-r--r--   0        0        0     3811 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/consumers/kafka_consumer.py
+-rw-r--r--   0        0        0        0 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/context/__init__.py
+-rw-r--r--   0        0        0     1896 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/context/event.py
+-rw-r--r--   0        0        0     3995 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/context/ocean.py
+-rw-r--r--   0        0        0        0 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/core/__init__.py
+-rw-r--r--   0        0        0      219 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/core/base.py
+-rw-r--r--   0        0        0      300 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/core/handlers/__init__.py
+-rw-r--r--   0        0        0        0 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/core/handlers/manipulation/__init__.py
+-rw-r--r--   0        0        0      685 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/core/handlers/manipulation/base.py
+-rw-r--r--   0        0        0     2516 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/core/handlers/manipulation/jq_manipulation.py
+-rw-r--r--   0        0        0        0 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/core/handlers/port_app_config/__init__.py
+-rw-r--r--   0        0        0      452 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/core/handlers/port_app_config/api.py
+-rw-r--r--   0        0        0      651 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/core/handlers/port_app_config/base.py
+-rw-r--r--   0        0        0     1426 2023-06-28 11:41:00.518336 port_ocean-0.1.0.dev2/port_ocean/core/handlers/port_app_config/models.py
+-rw-r--r--   0        0        0        0 2023-06-28 11:41:00.522336 port_ocean-0.1.0.dev2/port_ocean/core/handlers/transport/__init__.py
+-rw-r--r--   0        0        0      909 2023-06-28 11:41:00.522336 port_ocean-0.1.0.dev2/port_ocean/core/handlers/transport/base.py
+-rw-r--r--   0        0        0        0 2023-06-28 11:41:00.522336 port_ocean-0.1.0.dev2/port_ocean/core/handlers/transport/port/__init__.py
+-rw-r--r--   0        0        0     1173 2023-06-28 11:41:00.522336 port_ocean-0.1.0.dev2/port_ocean/core/handlers/transport/port/get_required_entities.py
+-rw-r--r--   0        0        0     1043 2023-06-28 11:41:00.522336 port_ocean-0.1.0.dev2/port_ocean/core/handlers/transport/port/order_by_entities_dependencies.py
+-rw-r--r--   0        0        0     4677 2023-06-28 11:41:00.522336 port_ocean-0.1.0.dev2/port_ocean/core/handlers/transport/port/transport.py
+-rw-r--r--   0        0        0     1495 2023-06-28 11:41:00.522336 port_ocean-0.1.0.dev2/port_ocean/core/handlers/transport/port/validate_entity_relations.py
+-rw-r--r--   0        0        0        0 2023-06-28 11:41:00.522336 port_ocean-0.1.0.dev2/port_ocean/core/integrations/__init__.py
+-rw-r--r--   0        0        0     3589 2023-06-28 11:41:00.522336 port_ocean-0.1.0.dev2/port_ocean/core/integrations/base.py
+-rw-r--r--   0        0        0        0 2023-06-28 11:41:00.522336 port_ocean-0.1.0.dev2/port_ocean/core/integrations/mixins/__init__.py
+-rw-r--r--   0        0        0      687 2023-06-28 11:41:00.522336 port_ocean-0.1.0.dev2/port_ocean/core/integrations/mixins/events.py
+-rw-r--r--   0        0        0     2393 2023-06-28 11:41:00.522336 port_ocean-0.1.0.dev2/port_ocean/core/integrations/mixins/handler.py
+-rw-r--r--   0        0        0     7018 2023-06-28 11:41:00.522336 port_ocean-0.1.0.dev2/port_ocean/core/integrations/mixins/sync.py
+-rw-r--r--   0        0        0      588 2023-06-28 11:41:00.522336 port_ocean-0.1.0.dev2/port_ocean/core/models.py
+-rw-r--r--   0        0        0        0 2023-06-28 11:41:00.522336 port_ocean-0.1.0.dev2/port_ocean/core/trigger_channel/__init__.py
+-rw-r--r--   0        0        0      448 2023-06-28 11:41:00.522336 port_ocean-0.1.0.dev2/port_ocean/core/trigger_channel/base.py
+-rw-r--r--   0        0        0     2616 2023-06-28 11:41:00.522336 port_ocean-0.1.0.dev2/port_ocean/core/trigger_channel/factory.py
+-rw-r--r--   0        0        0      817 2023-06-28 11:41:00.522336 port_ocean-0.1.0.dev2/port_ocean/core/trigger_channel/http.py
+-rw-r--r--   0        0        0     3229 2023-06-28 11:41:00.522336 port_ocean-0.1.0.dev2/port_ocean/core/trigger_channel/kafka.py
+-rw-r--r--   0        0        0      909 2023-06-28 11:41:00.522336 port_ocean-0.1.0.dev2/port_ocean/core/trigger_channel/settings.py
+-rw-r--r--   0        0        0     1957 2023-06-28 11:41:00.522336 port_ocean-0.1.0.dev2/port_ocean/core/utils.py
+-rw-r--r--   0        0        0      166 2023-06-28 11:41:00.522336 port_ocean-0.1.0.dev2/port_ocean/errors.py
+-rw-r--r--   0        0        0      534 2023-06-28 11:41:00.522336 port_ocean-0.1.0.dev2/port_ocean/logging.py
+-rw-r--r--   0        0        0     2064 2023-06-28 11:41:00.522336 port_ocean-0.1.0.dev2/port_ocean/middlewares.py
+-rw-r--r--   0        0        0     4421 2023-06-28 11:41:00.522336 port_ocean-0.1.0.dev2/port_ocean/port_ocean.py
+-rw-r--r--   0        0        0      563 2023-06-28 11:41:00.522336 port_ocean-0.1.0.dev2/port_ocean/types.py
+-rw-r--r--   0        0        0     1845 2023-06-28 11:41:00.522336 port_ocean-0.1.0.dev2/pyproject.toml
+-rw-r--r--   0        0        0     4247 1970-01-01 00:00:00.000000 port_ocean-0.1.0.dev2/PKG-INFO
```

### Comparing `port_ocean-0.1.0.dev1/README.md` & `port_ocean-0.1.0.dev2/README.md`

 * *Files identical despite different names*

### Comparing `port_ocean-0.1.0.dev1/port_ocean/cli/commands.py` & `port_ocean-0.1.0.dev2/port_ocean/cli/commands.py`

 * *Files identical despite different names*

### Comparing `port_ocean-0.1.0.dev1/port_ocean/cli/cookiecutter/{{cookiecutter.integration_slug}}/Dockerfile` & `port_ocean-0.1.0.dev2/port_ocean/cli/cookiecutter/{{cookiecutter.integration_slug}}/Dockerfile`

 * *Files identical despite different names*

### Comparing `port_ocean-0.1.0.dev1/port_ocean/cli/cookiecutter/{{cookiecutter.integration_slug}}/Makefile` & `port_ocean-0.1.0.dev2/port_ocean/cli/cookiecutter/{{cookiecutter.integration_slug}}/Makefile`

 * *Files identical despite different names*

### Comparing `port_ocean-0.1.0.dev1/port_ocean/cli/cookiecutter/{{cookiecutter.integration_slug}}/example.config.yaml` & `port_ocean-0.1.0.dev2/port_ocean/cli/cookiecutter/{{cookiecutter.integration_slug}}/example.config.yaml`

 * *Files identical despite different names*

### Comparing `port_ocean-0.1.0.dev1/port_ocean/cli/cookiecutter/{{cookiecutter.integration_slug}}/project.toml` & `port_ocean-0.1.0.dev2/port_ocean/cli/cookiecutter/{{cookiecutter.integration_slug}}/project.toml`

 * *Files identical despite different names*

### Comparing `port_ocean-0.1.0.dev1/port_ocean/cli/download_git_folder.py` & `port_ocean-0.1.0.dev2/port_ocean/cli/download_git_folder.py`

 * *Files identical despite different names*

### Comparing `port_ocean-0.1.0.dev1/port_ocean/cli/list_integrations.py` & `port_ocean-0.1.0.dev2/port_ocean/cli/list_integrations.py`

 * *Files identical despite different names*

### Comparing `port_ocean-0.1.0.dev1/port_ocean/clients/port/client.py` & `port_ocean-0.1.0.dev2/port_ocean/clients/port/client.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,17 +1,16 @@
 from datetime import datetime
-from typing import Dict, Any, List
+from typing import Any
 
 import httpx as httpx
 from loguru import logger
 from pydantic import BaseModel, Field, PrivateAttr
 
 from port_ocean.clients.port.types import (
     KafkaCreds,
-    ChangelogDestination,
     RequestOptions,
     UserAgentType,
 )
 from port_ocean.core.models import Entity, Blueprint
 
 
 class TokenResponse(BaseModel):
@@ -58,15 +57,15 @@
         if user_agent_type:
             user_agent += f"/{user_agent_type.value or UserAgentType.exporter.value}"
 
         return user_agent
 
     async def _headers(
         self, user_agent_type: UserAgentType | None = None
-    ) -> Dict[Any, Any]:
+    ) -> dict[Any, Any]:
         return {
             "Authorization": await self.token,
             "User-Agent": self._user_agent(user_agent_type),
         }
 
     @property
     async def token(self) -> str:
@@ -181,15 +180,15 @@
                 f"Error validating "
                 f"entity: {identifier} of "
                 f"blueprint: {blueprint}, "
                 f"error: {response.text}"
             )
         response.raise_for_status()
 
-    async def search_entities(self, user_agent_type: UserAgentType) -> List[Entity]:
+    async def search_entities(self, user_agent_type: UserAgentType) -> list[Entity]:
         query = {
             "combinator": "and",
             "rules": [
                 {
                     "property": "$datasource",
                     "operator": "=",
                     "value": self._user_agent(user_agent_type),
@@ -208,15 +207,15 @@
                 },
             )
             search_req.raise_for_status()
             return [
                 Entity.parse_obj(result) for result in search_req.json()["entities"]
             ]
 
-    async def search_dependent_entities(self, entity: Entity) -> List[Entity]:
+    async def search_dependent_entities(self, entity: Entity) -> list[Entity]:
         body = {
             "combinator": "and",
             "rules": [
                 {
                     "operator": "relatedTo",
                     "blueprint": entity.blueprint,
                     "value": entity.identifier,
@@ -247,47 +246,46 @@
                 "create_missing_related_entities": options.get(
                     "create_missing_related_entities", False
                 ),
                 "validation_only": True,
             },
         )
 
-    async def get_integration(self, identifier: str) -> Dict[str, Any]:
+    async def get_integration(self, identifier: str) -> dict[str, Any]:
         logger.info(f"Fetching integration with id: {identifier}")
         async with httpx.AsyncClient() as client:
             integration = await client.get(
                 f"{self.api_url}/integration/{identifier}",
                 headers=await self._headers(),
             )
         integration.raise_for_status()
         return integration.json()["integration"]
 
     async def initiate_integration(
-        self, _id: str, _type: str, changelog_destination: ChangelogDestination
+        self, _id: str, _type: str, changelog_destination: dict[str, Any]
     ) -> None:
         logger.info(f"Initiating integration with id: {_id}")
+        headers = await self._headers()
+        json = {
+            "installationId": _id,
+            "installationAppType": _type,
+            "changelogDestination": changelog_destination,
+        }
         async with httpx.AsyncClient() as client:
-            installation = await client.post(
-                f"{self.api_url}/integration",
-                headers=await self._headers(),
-                json={
-                    "installationId": _id,
-                    "installationAppType": _type,
-                    "changelogDestination": changelog_destination,
-                },
-            )
-
-        if installation.status_code == 409:
-            logger.info(
-                f"Integration with id: {_id} already exists, skipping registration"
+            installation = await client.patch(
+                f"{self.api_url}/integration/{_id}",
+                headers=headers,
+                json=json,
             )
+            if installation.status_code == 404:
+                installation = await client.post(
+                    f"{self.api_url}/integration", headers=headers, json=json
+                )
 
-            return
-
-        if not installation.status_code >= 400:
+        if installation.status_code >= 400:
             logger.error(
                 f"Error initiating integration with id: {_id}, error: {installation.text}"
             )
 
         installation.raise_for_status()
         logger.info(f"Integration with id: {_id} successfully registered")
```

### Comparing `port_ocean-0.1.0.dev1/port_ocean/clients/port/types.py` & `port_ocean-0.1.0.dev2/port_ocean/clients/port/types.py`

 * *Files 26% similar despite different names*

```diff
@@ -10,18 +10,15 @@
 KafkaCreds = TypedDict(
     "KafkaCreds",
     {
         "username": str,
         "password": str,
     },
 )
-ChangelogDestination = TypedDict(
-    "ChangelogDestination",
-    {"type": str, "url": NotRequired[str]},
-)
+
 RequestOptions = TypedDict(
     "RequestOptions",
     {
         "merge": NotRequired[bool],
         "create_missing_related_entities": NotRequired[bool],
         "delete_dependent_entities": NotRequired[bool],
         "validation_only": NotRequired[bool],
```

### Comparing `port_ocean-0.1.0.dev1/port_ocean/config/integration.py` & `port_ocean-0.1.0.dev2/port_ocean/config/integration.py`

 * *Files 22% similar despite different names*

```diff
@@ -1,53 +1,39 @@
 import warnings
-from typing import Dict, Any
+from typing import Any
 
 from pydantic import BaseModel, Field
-
-from port_ocean.config.base import BaseYamlSettings
 from pydantic import BaseSettings
 
+from port_ocean.config.base import BaseOceanSettings
+from port_ocean.core.trigger_channel.settings import (
+    HttpTriggerChannelSettings,
+    KafkaTriggerChannelSettings,
+)
 
 warnings.filterwarnings("ignore", category=FutureWarning)
 
 
 class PortSettings(BaseSettings):
     client_id: str = Field(alias="clientId")
     client_secret: str = Field(alias="clientSecret")
     base_url: str = Field(alias="baseUrl")
 
-    class Config(BaseSettings.Config):
-        env_prefix = "PORT__"
-
-
-class TriggerChannelSettings(BaseSettings):
-    type: str
-    brokers: str = ""
-    security_protocol: str = Field(alias="securityProtocol", default="SASL_SSL")
-    authentication_mechanism: str = Field(
-        alias="authenticationMechanism", default="SCRAM-SHA-512"
-    )
-    kafka_security_enabled: bool = Field(alias="kafkaSecurityEnabled", default=False)
-
-    class Config(BaseSettings.Config):
-        env_prefix = "TRIGGER__"
-
 
 class IntegrationSettings(BaseSettings):
     identifier: str
     type: str
-    config: Dict[str, Any]
+    config: dict[str, Any]
 
-    class Config(BaseSettings.Config):
-        env_prefix = "INTEGRATION__"
 
-
-class IntegrationConfiguration(BaseYamlSettings):
+class IntegrationConfiguration(BaseOceanSettings):
     port: PortSettings
-    trigger_channel: TriggerChannelSettings = Field(alias="triggerChannel")
+    trigger_channel: KafkaTriggerChannelSettings | HttpTriggerChannelSettings = Field(
+        alias="triggerChannel"
+    )
     batch_work_size: int | None = Field(alias="batchWorkSize", default=None)
     integration: IntegrationSettings
 
 
 class LoggerConfiguration(BaseModel):
     level: str = "DEBUG"
     serialize: bool = False
```

### Comparing `port_ocean-0.1.0.dev1/port_ocean/consumers/kafka_consumer.py` & `port_ocean-0.1.0.dev2/port_ocean/consumers/kafka_consumer.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,60 +1,60 @@
 import asyncio
 import json
 import signal
-from typing import Any, Callable, Awaitable, Dict
+from typing import Any, Callable, Awaitable
 
 from confluent_kafka import Consumer, KafkaException, Message  # type: ignore
 from loguru import logger
 from pydantic import BaseModel
 
 from port_ocean.consumers.base_consumer import BaseConsumer
 
 
 class KafkaConsumerConfig(BaseModel):
     brokers: str
-    username: str
-    password: str
+    username: str | None
+    password: str | None
     security_protocol: str
     authentication_mechanism: str
     kafka_security_enabled: bool
 
 
 class KafkaConsumer(BaseConsumer):
     def __init__(
         self,
-        msg_process: Callable[[Dict[Any, Any], str], Awaitable[None]],
+        msg_process: Callable[[dict[Any, Any], str], Awaitable[None]],
         config: KafkaConsumerConfig,
         org_id: str | None = None,
     ) -> None:
         self.running = False
         self.org_id = org_id
 
         signal.signal(signal.SIGINT, self.exit_gracefully)
         signal.signal(signal.SIGTERM, self.exit_gracefully)
 
         self.msg_process = msg_process
         if config.kafka_security_enabled:
-            config = {
+            kafka_config = {
                 "bootstrap.servers": config.brokers,
                 "security.protocol": config.security_protocol,
                 "sasl.mechanism": config.authentication_mechanism,
                 "sasl.username": config.username,
                 "sasl.password": config.password,
                 "group.id": config.username,
                 "enable.auto.commit": "false",
             }
         else:
-            config = {
+            kafka_config = {
                 "bootstrap.servers": config.brokers,
                 "group.id": "no-security",
                 "enable.auto.commit": "false",
             }
 
-        self.consumer = Consumer(config)
+        self.consumer = Consumer(kafka_config)
 
     def _handle_message(self, raw_msg: Message) -> None:
         message = json.loads(raw_msg.value().decode())
         topic = raw_msg.topic()
 
         async def try_wrapper() -> None:
             try:
```

### Comparing `port_ocean-0.1.0.dev1/port_ocean/context/event.py` & `port_ocean-0.1.0.dev2/port_ocean/context/event.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 from contextlib import asynccontextmanager
 from dataclasses import dataclass, field
-from typing import AsyncIterator, Literal, Any, Dict, TYPE_CHECKING, Optional
+from typing import AsyncIterator, Literal, Any, TYPE_CHECKING, Optional
 
 from werkzeug.local import LocalStack, LocalProxy
 
 from port_ocean.errors import EventContextNotFoundError
 
 if TYPE_CHECKING:
     from port_ocean.core.handlers.port_app_config.models import PortAppConfig
@@ -49,15 +49,15 @@
 event: EventContext = LocalProxy(lambda: _get_event_context())  # type: ignore
 
 
 @asynccontextmanager
 async def event_context(
     kind: str,
     trigger_type: TriggerType = "manual",
-    attributes: Dict[str, Any] | None = None,
+    attributes: dict[str, Any] | None = None,
 ) -> AsyncIterator[EventContext]:
     if attributes is None:
         attributes = {}
 
     _event_context_stack.push(
         EventContext(
             kind,
```

### Comparing `port_ocean-0.1.0.dev1/port_ocean/context/ocean.py` & `port_ocean-0.1.0.dev2/port_ocean/context/ocean.py`

 * *Files 22% similar despite different names*

```diff
@@ -1,23 +1,19 @@
 from dataclasses import dataclass
-from typing import Callable, TYPE_CHECKING, Any, Dict, List
+from typing import Callable, TYPE_CHECKING, Any
 
 from fastapi import APIRouter
 from werkzeug.local import LocalProxy, LocalStack
 
 from port_ocean.clients.port.client import PortClient
 from port_ocean.clients.port.types import UserAgentType
 from port_ocean.config.integration import IntegrationConfiguration
 from port_ocean.core.models import Entity
 from port_ocean.errors import PortOceanContextNotFoundError
-from port_ocean.types import (
-    RESYNC_EVENT_LISTENER,
-    START_EVENT_LISTENER,
-    EntityRawDiff,
-)
+from port_ocean.types import RESYNC_EVENT_LISTENER, START_EVENT_LISTENER, RawEntityDiff
 
 if TYPE_CHECKING:
     from port_ocean.core.integrations.base import BaseIntegration
     from port_ocean.port_ocean import Ocean
 
 
 @dataclass
@@ -33,15 +29,15 @@
         return self.app.integration_router
 
     @property
     def integration(self) -> "BaseIntegration":
         return self.app.integration
 
     @property
-    def integration_config(self) -> Dict[str, Any]:
+    def integration_config(self) -> dict[str, Any]:
         return self.app.config.integration.config
 
     @property
     def port_client(self) -> PortClient:
         return self.app.port_client
 
     def on_resync(
@@ -55,36 +51,59 @@
 
     def on_start(self) -> Callable[[START_EVENT_LISTENER], START_EVENT_LISTENER]:
         def wrapper(function: START_EVENT_LISTENER) -> START_EVENT_LISTENER:
             return self.integration.on_start(function)
 
         return wrapper
 
+    async def update_raw_diff(
+        self,
+        kind: str,
+        raw_diff: RawEntityDiff,
+        user_agent_type: UserAgentType = UserAgentType.exporter,
+    ) -> None:
+        await self.integration.update_raw_diff(kind, raw_diff, user_agent_type)
+
     async def register_raw(
         self,
         kind: str,
-        change: EntityRawDiff,
+        change: list[dict[str, Any]],
         user_agent_type: UserAgentType = UserAgentType.exporter,
     ) -> None:
         await self.integration.register_raw(kind, change, user_agent_type)
 
+    async def unregister_raw(
+        self,
+        kind: str,
+        change: list[dict[str, Any]],
+        user_agent_type: UserAgentType = UserAgentType.exporter,
+    ) -> None:
+        await self.integration.unregister_raw(kind, change, user_agent_type)
+
     async def register(
         self,
-        entities: List[Entity],
+        entities: list[Entity],
         user_agent_type: UserAgentType = UserAgentType.exporter,
     ) -> None:
         await self.integration.register(entities, user_agent_type)
 
+    async def unregister(
+        self,
+        entities: list[Entity],
+        user_agent_type: UserAgentType = UserAgentType.exporter,
+    ) -> None:
+        await self.integration.unregister(entities, user_agent_type)
+
     async def sync(
-        self, entities: List[Entity], user_agent_type: UserAgentType
+        self, entities: list[Entity], user_agent_type: UserAgentType
     ) -> None:
         await self.integration.sync(entities, user_agent_type)
 
-    async def trigger_resync(self) -> None:
-        await self.integration.trigger_resync(trigger_type="manual")
+    async def sync_all(self) -> None:
+        await self.integration.sync_all(trigger_type="manual")
 
 
 _port_ocean_context_stack: LocalStack[PortOceanContext] = LocalStack()
 
 
 def initialize_port_ocean_context(ocean_app: "Ocean") -> None:
     """
```

### Comparing `port_ocean-0.1.0.dev1/port_ocean/core/handlers/manipulation/base.py` & `port_ocean-0.1.0.dev2/port_ocean/core/handlers/manipulation/base.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,23 +1,22 @@
 from abc import abstractmethod
 from dataclasses import dataclass, field
-from typing import List
 
 from port_ocean.core.base import BaseWithContext
 from port_ocean.core.handlers.port_app_config.models import ResourceConfig
 from port_ocean.core.models import Entity
-from port_ocean.types import EntityRawDiff, EntityDiff
+from port_ocean.types import RawEntityDiff, EntityDiff
 
 
 @dataclass
 class EntityPortDiff:
-    deleted: List[Entity] = field(default_factory=list)
-    modified: List[Entity] = field(default_factory=list)
-    created: List[Entity] = field(default_factory=list)
+    deleted: list[Entity] = field(default_factory=list)
+    modified: list[Entity] = field(default_factory=list)
+    created: list[Entity] = field(default_factory=list)
 
 
 class BaseManipulation(BaseWithContext):
     @abstractmethod
     async def parse_items(
-        self, mapping: ResourceConfig, raw_data: List[EntityRawDiff]
+        self, mapping: ResourceConfig, raw_data: RawEntityDiff
     ) -> EntityDiff:
         pass
```

### Comparing `port_ocean-0.1.0.dev1/port_ocean/core/handlers/manipulation/jq_manipulation.py` & `port_ocean-0.1.0.dev2/port_ocean/core/handlers/manipulation/jq_manipulation.py`

 * *Files 11% similar despite different names*

```diff
@@ -1,54 +1,54 @@
 from functools import lru_cache
-from typing import List, Dict, Any
+from typing import Any
 
 import pyjq as jq  # type: ignore
 
 from port_ocean.core.handlers.manipulation.base import BaseManipulation
 from port_ocean.core.handlers.port_app_config.models import ResourceConfig
 from port_ocean.core.models import Entity
-from port_ocean.types import EntityRawDiff, EntityDiff
+from port_ocean.types import RawEntityDiff, EntityDiff
 
 
 class JQManipulation(BaseManipulation):
     @lru_cache
     def _compile(self, pattern: str) -> Any:
         return jq.compile(pattern)
 
-    def _search(self, data: Dict[str, Any], pattern: str) -> Any:
+    def _search(self, data: dict[str, Any], pattern: str) -> Any:
         try:
             return self._compile(pattern).first(data) or None
         except Exception:
             return None
 
-    def _search_as_bool(self, data: Dict[str, Any], pattern: str) -> bool:
+    def _search_as_bool(self, data: dict[str, Any], pattern: str) -> bool:
         value = self._compile(pattern).first(data)
 
         if isinstance(value, bool):
             return value
 
         raise Exception(f"Expected boolean value, got {type(value)} instead")
 
     def _search_as_object(
-        self, data: Dict[str, Any], obj: Dict[str, Any]
-    ) -> Dict[str, Any | None]:
-        result: Dict[str, Any | None] = {}
+        self, data: dict[str, Any], obj: dict[str, Any]
+    ) -> dict[str, Any | None]:
+        result: dict[str, Any | None] = {}
         for key, value in obj.items():
             try:
                 if isinstance(value, dict):
                     result[key] = self._search_as_object(data, value)
                 else:
                     result[key] = self._search(data, value)
             except Exception:
                 result[key] = None
         return result
 
     def _parse_items(
-        self, mapping: ResourceConfig, raw_data: List[Dict[str, Any]]
-    ) -> List[Entity]:
+        self, mapping: ResourceConfig, raw_data: list[dict[str, Any]]
+    ) -> list[Entity]:
         entities = []
         for data in raw_data:
             should_run = self._search_as_bool(data, mapping.selector.query)
 
             if should_run and mapping.port.entity:
                 entities.append(
                     self._search_as_object(data, mapping.port.entity.mappings.dict())
@@ -59,29 +59,18 @@
             for entity_data in filter(
                 lambda entity: entity.get("identifier") and entity.get("blueprint"),
                 entities,
             )
         ]
 
     async def parse_items(
-        self, mapping: ResourceConfig, raw_results: List[EntityRawDiff]
+        self, mapping: ResourceConfig, raw_results: RawEntityDiff
     ) -> EntityDiff:
-        parsed_results = [
-            (
-                self._parse_items(mapping, result["before"]),
-                self._parse_items(mapping, result["after"]),
-            )
-            for result in raw_results
-        ]
-        entities_before, entities_after = [], []
+        entities_before: list[Entity] = self._parse_items(
+            mapping, raw_results["before"]
+        )
+        entities_after: list[Entity] = self._parse_items(mapping, raw_results["after"])
 
-        if parsed_results:
-            entities_before, entities_after = tuple(
-                (sum(items, []) for items in zip(*parsed_results))
-            )
-
-        entities_diff: EntityDiff = {
+        return {
             "before": entities_before,
             "after": entities_after,
         }
-
-        return entities_diff
```

### Comparing `port_ocean-0.1.0.dev1/port_ocean/core/handlers/port_app_config/base.py` & `port_ocean-0.1.0.dev2/port_ocean/core/handlers/port_app_config/base.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,20 +1,20 @@
 from abc import abstractmethod
-from typing import Type, Any, Dict
+from typing import Type, Any
 
 from port_ocean.context.event import event
 from port_ocean.core.base import BaseWithContext
 from port_ocean.core.handlers.port_app_config.models import PortAppConfig
 
 
 class BasePortAppConfig(BaseWithContext):
     CONFIG_CLASS: Type[PortAppConfig] = PortAppConfig
 
     @abstractmethod
-    async def _get_port_app_config(self) -> Dict[str, Any]:
+    async def _get_port_app_config(self) -> dict[str, Any]:
         pass
 
     async def get_port_app_config(self) -> PortAppConfig:
         raw_config = await self._get_port_app_config()
         config = self.CONFIG_CLASS.parse_obj(raw_config)
         event.port_app_config = config
         return config
```

### Comparing `port_ocean-0.1.0.dev1/port_ocean/core/handlers/port_app_config/models.py` & `port_ocean-0.1.0.dev2/port_ocean/core/handlers/port_app_config/models.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,20 +1,20 @@
-from typing import List, Optional, Dict
+from typing import Optional
 
 from pydantic import BaseModel, Field
 
 from port_ocean.clients.port.types import RequestOptions
 
 
 class EntityMapping(BaseModel):
     identifier: str
     title: str
     blueprint: str
-    properties: Dict[str, str] = Field(default_factory=dict)
-    relations: Dict[str, str] = Field(default_factory=dict)
+    properties: dict[str, str] = Field(default_factory=dict)
+    relations: dict[str, str] = Field(default_factory=dict)
 
 
 class PortResourceConfig(BaseModel):
     class MappingsConfig(BaseModel):
         mappings: EntityMapping
 
     entity: Optional[MappingsConfig]
@@ -33,15 +33,15 @@
     enable_merge_entity: bool = Field(alias="enableMergeEntity", default=False)
     delete_dependent_entities: bool = Field(
         alias="deleteDependentEntities", default=False
     )
     create_missing_related_entities: bool = Field(
         alias="createMissingRelatedEntities", default=False
     )
-    resources: List[ResourceConfig] = Field(default_factory=list)
+    resources: list[ResourceConfig] = Field(default_factory=list)
 
     def get_port_request_options(self) -> RequestOptions:
         return {
             "delete_dependent_entities": self.delete_dependent_entities,
             "create_missing_related_entities": self.create_missing_related_entities,
             "merge": self.enable_merge_entity,
         }
```

### Comparing `port_ocean-0.1.0.dev1/port_ocean/core/handlers/transport/base.py` & `port_ocean-0.1.0.dev2/port_ocean/core/handlers/transport/base.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,9 +1,8 @@
 from abc import abstractmethod
-from typing import List
 
 from port_ocean.clients.port.types import UserAgentType
 from port_ocean.core.base import BaseWithContext
 from port_ocean.core.models import Entity
 from port_ocean.types import EntityDiff
 
 
@@ -16,22 +15,22 @@
         entities: EntityDiff,
         user_agent: UserAgentType | None = None,
     ) -> None:
         pass
 
     @abstractmethod
     async def upsert(
-        self, entities: List[Entity], user_agent_type: UserAgentType
+        self, entities: list[Entity], user_agent_type: UserAgentType
     ) -> None:
         pass
 
     @abstractmethod
     async def delete(
-        self, entities: List[Entity], user_agent_type: UserAgentType
+        self, entities: list[Entity], user_agent_type: UserAgentType
     ) -> None:
         pass
 
     @abstractmethod
-    async def delete_diff(
-        self, entities: List[Entity], user_agent: UserAgentType
+    async def delete_non_existing(
+        self, entities: list[Entity], user_agent: UserAgentType
     ) -> None:
         pass
```

### Comparing `port_ocean-0.1.0.dev1/port_ocean/core/handlers/transport/port/get_required_entities.py` & `port_ocean-0.1.0.dev2/port_ocean/core/handlers/transport/port/get_required_entities.py`

 * *Files 18% similar despite different names*

```diff
@@ -1,18 +1,16 @@
-from typing import List, Tuple
-
 from port_ocean.core.models import Entity, Blueprint
 from port_ocean.core.utils import is_same_entity
 
 
 def get_required_entities(
-    entity_to_blueprint: List[Tuple[Entity, Blueprint]],
-    forbidden_entities: List[Entity],
-    excluded_entities: List[Entity],
-) -> List[Entity]:
+    entity_to_blueprint: list[tuple[Entity, Blueprint]],
+    forbidden_entities: list[Entity],
+    excluded_entities: list[Entity],
+) -> list[Entity]:
     required_entities = []
     for entity, blueprint in entity_to_blueprint:
         for relation_name, relation in entity.relations.items():
             relation_blueprint = blueprint.relations[relation_name].target
             target_entity = Entity(identifier=relation, blueprint=relation_blueprint)
 
             if any(is_same_entity(item, target_entity) for item in forbidden_entities):
```

### Comparing `port_ocean-0.1.0.dev1/port_ocean/core/handlers/transport/port/order_by_entities_dependencies.py` & `port_ocean-0.1.0.dev2/port_ocean/core/handlers/transport/port/order_by_entities_dependencies.py`

 * *Files 21% similar despite different names*

```diff
@@ -1,17 +1,17 @@
 from graphlib import TopologicalSorter
-from typing import List, Dict, Set, Tuple
+from typing import Set
 
 from port_ocean.core.models import Entity
 
-Node = Tuple[str, str]
+Node = tuple[str, str]
 
 
-def order_by_entities_dependencies(entities: List[Entity]) -> List[Entity]:
-    nodes: Dict[Node, Set[Node]] = {}
+def order_by_entities_dependencies(entities: list[Entity]) -> list[Entity]:
+    nodes: dict[Node, Set[Node]] = {}
     entities_map = {}
 
     for entity in entities:
         nodes[(entity.identifier, entity.blueprint)] = set()
         entities_map[(entity.identifier, entity.blueprint)] = entity
 
     for entity in entities:
```

### Comparing `port_ocean-0.1.0.dev1/port_ocean/core/handlers/transport/port/transport.py` & `port_ocean-0.1.0.dev2/port_ocean/core/handlers/transport/port/transport.py`

 * *Files 16% similar despite different names*

```diff
@@ -1,10 +1,9 @@
 import asyncio
 from itertools import chain
-from typing import List
 
 from loguru import logger
 
 from port_ocean.clients.port.types import UserAgentType
 from port_ocean.context.event import event
 from port_ocean.core.handlers.manipulation.base import (
     EntityPortDiff,
@@ -22,40 +21,40 @@
     get_unique,
     get_port_diff,
 )
 from port_ocean.types import EntityDiff
 
 
 class HttpPortTransport(BaseTransport):
-    async def _validate_delete_dependent_entities(self, diff: EntityPortDiff) -> None:
+    async def _validate_delete_dependent_entities(self, entities: list[Entity]) -> None:
         logger.info("Validated deleted entities")
         if not event.port_app_config.delete_dependent_entities:
             deps = await asyncio.gather(
                 *[
                     self.context.port_client.search_dependent_entities(entity)
-                    for entity in diff.deleted
+                    for entity in entities
                 ]
             )
             new_dependent = get_unique(
                 [
                     entity
                     for entity in chain.from_iterable(deps)
-                    if not any([is_same_entity(item, entity) for item in diff.deleted])
+                    if not any([is_same_entity(item, entity) for item in entities])
                 ]
             )
 
             if new_dependent:
                 raise Exception(
                     f"Must enable delete_dependent_entities flag or delete also dependent entities:"
                     f" {[(dep.blueprint, dep.identifier) for dep in new_dependent]}"
                 )
 
     async def _validate_entity_diff(self, diff: EntityPortDiff) -> None:
         config = event.port_app_config
-        await self._validate_delete_dependent_entities(diff)
+        await self._validate_delete_dependent_entities(diff.deleted)
         modified_or_created_entities = diff.modified + diff.created
         logger.info("Validating modified or created entities")
 
         await asyncio.gather(
             *[
                 self.context.port_client.validate_entity_payload(
                     entity,
@@ -70,56 +69,57 @@
         await validate_entity_relations(diff, self.context.port_client)
 
     async def update_diff(
         self,
         entities: EntityDiff,
         user_agent_type: UserAgentType | None = None,
     ) -> None:
-        entities_diff = get_port_diff(entities["before"], entities["after"])
+        diff = get_port_diff(entities["before"], entities["after"])
 
         logger.info(
-            f"Registering entity diff (created: {len(entities_diff.created)}, deleted: {len(entities_diff.deleted)}, modified: {len(entities_diff.modified)})"
+            f"Registering entity diff (created: {len(diff.created)}, deleted: {len(diff.deleted)}, modified: {len(diff.modified)})"
         )
-        await self._validate_entity_diff(entities_diff)
+        await self._validate_entity_diff(diff)
 
         user_agent_type = user_agent_type or self.DEFAULT_USER_AGENT_TYPE
-        await self.delete(entities_diff.deleted, user_agent_type)
-        await self.upsert(entities_diff.created, user_agent_type)
-        await self.upsert(entities_diff.modified, user_agent_type)
+        await self.delete(diff.deleted, user_agent_type)
+        await self.upsert(diff.created, user_agent_type)
+        await self.upsert(diff.modified, user_agent_type)
 
     async def upsert(
-        self, entities: List[Entity], user_agent_type: UserAgentType
+        self, entities: list[Entity], user_agent_type: UserAgentType
     ) -> None:
         ordered_created_entities = reversed(order_by_entities_dependencies(entities))
         for entity in ordered_created_entities:
             await self.context.port_client.upsert_entity(
                 entity,
                 event.port_app_config.get_port_request_options(),
                 user_agent_type,
             )
 
     async def delete(
-        self, entities: List[Entity], user_agent_type: UserAgentType
+        self, entities: list[Entity], user_agent_type: UserAgentType
     ) -> None:
         ordered_deleted_entities = order_by_entities_dependencies(entities)
 
         await asyncio.gather(
             *[
                 self.context.port_client.delete_entity(entity, user_agent_type)
                 for entity in ordered_deleted_entities
             ]
         )
 
-    async def delete_diff(
-        self, entities: List[Entity], user_agent_type: UserAgentType
+    async def delete_non_existing(
+        self, excluded_entities: list[Entity], user_agent_type: UserAgentType
     ) -> None:
         entities_at_port = await self.context.port_client.search_entities(
             user_agent_type
         )
-        diff = get_port_diff(entities_at_port, entities)
+        diff = get_port_diff(entities_at_port, excluded_entities)
+        await self._validate_entity_diff(diff)
 
         ordered_deleted_entities = order_by_entities_dependencies(diff.deleted)
 
         await asyncio.gather(
             *[
                 self.context.port_client.delete_entity(entity, user_agent_type)
                 for entity in ordered_deleted_entities
```

### Comparing `port_ocean-0.1.0.dev1/port_ocean/core/handlers/transport/port/validate_entity_relations.py` & `port_ocean-0.1.0.dev2/port_ocean/core/handlers/transport/port/validate_entity_relations.py`

 * *Files identical despite different names*

### Comparing `port_ocean-0.1.0.dev1/port_ocean/core/integrations/base.py` & `port_ocean-0.1.0.dev2/port_ocean/core/integrations/base.py`

 * *Files 20% similar despite different names*

```diff
@@ -1,119 +1,91 @@
 import asyncio
 from typing import (
-    List,
-    Dict,
     Any,
 )
 
 from loguru import logger
 
 from port_ocean.clients.port.types import UserAgentType
 from port_ocean.context.event import (
     event_context,
     TriggerType,
 )
 from port_ocean.context.ocean import PortOceanContext
 from port_ocean.core.handlers.port_app_config.models import ResourceConfig
-from port_ocean.core.integrations.mixins import (
-    SyncMixin,
-)
+from port_ocean.core.integrations.mixins.sync import SyncRawMixin, SyncMixin
 from port_ocean.core.models import Entity
-from port_ocean.core.trigger_channel.trigger_channel_factory import (
+from port_ocean.core.trigger_channel.factory import (
     TriggerChannelFactory,
 )
 
 
-class BaseIntegration(SyncMixin):
+class BaseIntegration(SyncRawMixin, SyncMixin):
     def __init__(self, context: PortOceanContext):
+        SyncRawMixin.__init__(self)
         SyncMixin.__init__(self)
         self.started = False
         self.context = context
         self.trigger_channel = TriggerChannelFactory(
             context,
             self.context.config.integration.identifier,
-            self.context.config.trigger_channel.type,
-            {"on_action": self.trigger_action, "on_resync": self.trigger_resync},
+            {"on_action": self.trigger_action, "on_resync": self.sync_all},
         )
 
-    async def _calculate_and_register(
-        self,
-        resource: ResourceConfig,
-        results: List[Dict[Any, Any]],
-        user_agent_type: UserAgentType,
-    ) -> List[Entity]:
-        objects_diff = await self._calculate_raw(
-            [
-                (
-                    resource,
-                    [
-                        {
-                            "before": [],
-                            "after": results,
-                        }
-                    ],
-                )
-            ]
-        )
-
-        entities_after: List[Entity] = objects_diff[0]["after"]
-
-        await self.transport.upsert(entities_after, user_agent_type)
-        return entities_after
-
     async def _sync_new_in_batches(
         self, resource_config: ResourceConfig, user_agent_type: UserAgentType
-    ) -> List[Entity]:
-        resource, results = await self._run_resync(resource_config)
+    ) -> list[Entity]:
+        resource, results = await self._get_resource_raw_results(resource_config)
 
         tasks = []
 
         batch_size = self.context.config.batch_work_size or len(results)
         for batch in [
             results[i : i + batch_size] for i in range(0, len(results), batch_size)
         ]:
-            tasks.append(self._calculate_and_register(resource, batch, user_agent_type))
+            tasks.append(self._register_resource_raw(resource, batch, user_agent_type))
         entities = await asyncio.gather(*tasks)
         return sum(entities, [])
 
-    async def trigger_start(self) -> None:
+    async def start(self) -> None:
         logger.info("Starting integration")
         if self.started:
             raise Exception("Integration already started")
 
         if (
             not self.event_strategy["resync"]
             and self.__class__._on_resync == BaseIntegration._on_resync
         ):
             raise NotImplementedError("on_resync is not implemented")
 
         await self.initialize_handlers()
-        logger.info("Initializing trigger channel")
-        await self.trigger_channel.create_trigger_channel()
 
         logger.info("Initializing integration at port")
         await self.context.port_client.initiate_integration(
             self.context.config.integration.identifier,
             self.context.config.integration.type,
-            {"type": self.context.config.trigger_channel.type},
+            self.context.config.trigger_channel.to_request(),
         )
 
+        logger.info("Initializing trigger channel")
+        await self.trigger_channel.create_trigger_channel()
+
         self.started = True
 
         async with event_context("start", trigger_type="machine"):
             await asyncio.gather(
                 *(listener() for listener in self.event_strategy["start"])
             )
 
-    async def trigger_action(self, data: Dict[Any, Any]) -> None:
+    async def trigger_action(self, data: dict[Any, Any]) -> None:
         raise NotImplementedError("trigger_action is not implemented")
 
-    async def trigger_resync(
+    async def sync_all(
         self,
-        _: Dict[Any, Any] | None = None,
+        _: dict[Any, Any] | None = None,
         trigger_type: TriggerType = "machine",
         user_agent_type: UserAgentType = UserAgentType.exporter,
     ) -> None:
         logger.info("Resync was triggered")
 
         async with event_context("resync", trigger_type=trigger_type):
             app_config = await self.port_app_config_handler.get_port_app_config()
@@ -121,10 +93,12 @@
             created_entities = await asyncio.gather(
                 *(
                     self._sync_new_in_batches(resource, user_agent_type)
                     for resource in app_config.resources
                 )
             )
 
-            await self.transport.delete_diff(sum(created_entities, []), user_agent_type)
+            await self.transport.delete_non_existing(
+                sum(created_entities, []), user_agent_type
+            )
 
             logger.info("Resync was finished")
```

### Comparing `port_ocean-0.1.0.dev1/port_ocean/core/models.py` & `port_ocean-0.1.0.dev2/port_ocean/core/models.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,28 +1,28 @@
-from typing import Dict, Any, List
+from typing import Any
 
 from pydantic import BaseModel
 from pydantic.fields import Field
 
 
 class Entity(BaseModel):
     identifier: str
     blueprint: str
     title: str | None
-    team: str | List[str] = []
-    properties: Dict[str, Any] = {}
-    relations: Dict[str, str] = {}
+    team: str | list[str] = []
+    properties: dict[str, Any] = {}
+    relations: dict[str, str] = {}
 
 
 class BlueprintRelation(BaseModel):
     many: bool
     required: bool
     target: str
     title: str | None
 
 
 class Blueprint(BaseModel):
     identifier: str
     title: str | None
     team: str | None
-    properties_schema: Dict[str, Any] = Field(alias="schema")
-    relations: Dict[str, BlueprintRelation]
+    properties_schema: dict[str, Any] = Field(alias="schema")
+    relations: dict[str, BlueprintRelation]
```

### Comparing `port_ocean-0.1.0.dev1/port_ocean/core/trigger_channel/trigger_channel_factory.py` & `port_ocean-0.1.0.dev2/port_ocean/core/trigger_channel/factory.py`

 * *Files 18% similar despite different names*

```diff
@@ -1,68 +1,76 @@
-from typing import Callable, Dict, Any, Awaitable
+from typing import Callable, Any, Awaitable
 
-from port_ocean.consumers.kafka_consumer import KafkaConsumerConfig
+from port_ocean.context.ocean import PortOceanContext
 from port_ocean.core.base import BaseWithContext
-from port_ocean.core.trigger_channel.base_trigger_channel import (
+from port_ocean.core.trigger_channel.base import (
     BaseTriggerChannel,
-    TriggerEventEvents,
+    TriggerChannelEvents,
+)
+from port_ocean.core.trigger_channel.http import (
+    HttpTriggerChannel,
+)
+from port_ocean.core.trigger_channel.kafka import (
+    KafkaTriggerChannel,
+)
+from port_ocean.core.trigger_channel.settings import (
+    HttpTriggerChannelSettings,
+    KafkaTriggerChannelSettings,
 )
-from port_ocean.core.trigger_channel.kafka_trigger_channel import KafkaTriggerChannel
-
-from port_ocean.context.ocean import PortOceanContext
 
 
 class TriggerChannelFactory(BaseWithContext):
     def __init__(
         self,
         context: PortOceanContext,
         installation_id: str,
-        trigger_channel_type: str,
-        events: TriggerEventEvents,
+        events: TriggerChannelEvents,
     ):
         super().__init__(context)
         self.installation_id = installation_id
-        self.trigger_channel_type = trigger_channel_type
         self._trigger_channel: BaseTriggerChannel | None = None
         self.events = events
 
     def on_event(
-        self, callback: Callable[[Dict[Any, Any]], Awaitable[None]]
-    ) -> Callable[[Dict[Any, Any]], Awaitable[None]]:
-        async def wrapper(event: Dict[Any, Any]) -> None:
+        self, callback: Callable[[dict[Any, Any]], Awaitable[None]]
+    ) -> Callable[[dict[Any, Any]], Awaitable[None]]:
+        async def wrapper(event: dict[Any, Any]) -> None:
             integration_identifier = (
                 event.get("diff", {}).get("after", {}).get("identifier")
             )
 
             if integration_identifier == self.installation_id:
                 await callback(event)
 
         return wrapper
 
     async def create_trigger_channel(self) -> None:
-        if self.trigger_channel_type.lower() == "kafka":
-            kafka_creds = {
-                "username": "",
-                "password": "",
-            }  # await self.context.port_client.get_kafka_creds()
-            org_id = await self.context.port_client.get_org_id()
-            self._trigger_channel = KafkaTriggerChannel(
-                {
-                    "on_resync": self.on_event(self.events["on_resync"]),
-                    "on_action": self.on_event(self.events["on_action"]),
-                },
-                KafkaConsumerConfig(
-                    username=kafka_creds["username"],
-                    password=kafka_creds["password"],
-                    brokers=self.context.config.trigger_channel.brokers,
-                    security_protocol=self.context.config.trigger_channel.security_protocol,
-                    authentication_mechanism=self.context.config.trigger_channel.authentication_mechanism,
-                    kafka_security_enabled=self.context.config.trigger_channel.kafka_security_enabled,
-                ),
-                org_id,
-            )
-        else:
-            raise Exception(
-                f"Trigger channel {self.trigger_channel_type} not supported"
-            )
+        wrapped_events: TriggerChannelEvents = {
+            "on_resync": self.on_event(self.events["on_resync"]),
+            "on_action": self.on_event(self.events["on_action"]),
+        }
+        config = self.context.config.trigger_channel
+        _type = config.type.lower()
+        assert_message = "Invalid trigger channel config, expected KafkaTriggerChannelSettings and got {0}"
+
+        match _type:
+            case "kafka":
+                assert isinstance(
+                    config, KafkaTriggerChannelSettings
+                ), assert_message.format(type(config))
+                org_id = await self.context.port_client.get_org_id()
+                self._trigger_channel = KafkaTriggerChannel(
+                    wrapped_events,
+                    config,
+                    org_id,
+                )
+
+            case "webhook":
+                assert isinstance(
+                    config, HttpTriggerChannelSettings
+                ), assert_message.format(type(config))
+                self._trigger_channel = HttpTriggerChannel(wrapped_events, config)
+
+            case _:
+                raise Exception(f"Trigger channel {_type} not supported")
 
-        self._trigger_channel.start()
+        await self._trigger_channel.start()
```

### Comparing `port_ocean-0.1.0.dev1/port_ocean/core/utils.py` & `port_ocean-0.1.0.dev2/port_ocean/core/utils.py`

 * *Files 22% similar despite different names*

```diff
@@ -1,41 +1,48 @@
-from typing import List, Iterable, Any, Dict
+from typing import Iterable, Any, TypeVar
 
 from port_ocean.core.handlers.manipulation.base import EntityPortDiff
 from port_ocean.core.models import Entity
 
 
 def is_valid_diff_item(item: Any) -> bool:
     return isinstance(item, list) and all([isinstance(i, dict) for i in item] or [True])
 
 
-def validate_result(result: Any) -> List[Dict[Any, Any]]:
+def validate_result(result: Any) -> list[dict[Any, Any]]:
     if isinstance(result, list):
         if is_valid_diff_item(result):
             return result
     raise Exception(f"Expected dict, got {type(result)} instead")
 
 
 def is_same_entity(firs_entity: Entity, second_entity: Entity) -> bool:
     return (
         firs_entity.identifier == second_entity.identifier
         and firs_entity.blueprint == second_entity.blueprint
     )
 
 
-def get_unique(array: List[Entity]) -> List[Entity]:
-    seen: List[Entity] = []
+def get_unique(array: list[Entity]) -> list[Entity]:
+    seen: list[Entity] = []
     result = []
     for item in array:
         if all(not is_same_entity(item, seen_item) for seen_item in seen):
             seen.append(item)
             result.append(item)
     return result
 
 
+T = TypeVar("T", bound=list[Any])
+
+
+def zip_and_sum(collection: Iterable[tuple[T, ...]]) -> tuple[T, ...]:
+    return tuple(sum(items, []) for items in zip(*collection))  # type: ignore
+
+
 def get_port_diff(
     before: Iterable[Entity],
     after: Iterable[Entity],
 ) -> EntityPortDiff:
     return EntityPortDiff(
         deleted=get_unique(
             [
```

### Comparing `port_ocean-0.1.0.dev1/port_ocean/logging.py` & `port_ocean-0.1.0.dev2/port_ocean/logging.py`

 * *Files identical despite different names*

### Comparing `port_ocean-0.1.0.dev1/port_ocean/middlewares.py` & `port_ocean-0.1.0.dev2/port_ocean/middlewares.py`

 * *Files 15% similar despite different names*

```diff
@@ -1,15 +1,13 @@
 from time import time
 from typing import Callable, Awaitable
 from uuid import uuid4
 
 from fastapi import Request, Response
 
-# from .exceptions.api.base import BaseAPIException, InternalServerException
-# from .logger import logger
 from loguru import logger
 
 from .context.event import event_context
 from .context.ocean import ocean
 
 
 def get_time(seconds_precision: bool = True) -> float:
@@ -35,37 +33,22 @@
       or treat (and log) unexpected exceptions.
     """
     start_time = get_time(seconds_precision=False)
     request_id = get_uuid()
 
     with logger.contextualize(request_id=request_id):
         logger.bind(url=str(request.url), method=request.method).info("Request started")
+        response: Response
 
-        async with event_context(""):
-            await ocean.integration.port_app_config_handler.get_port_app_config()
-            # noinspection PyBroadException
-            # try:
-            response: Response = await call_next(request)
-
-            # except BaseAPIException as ex:
-            #     response = ex.response()
-            #     if response.status_code < 500:
-            #         logger.bind(exception=str(ex)).info(
-            #             "Request did not succeed due to client-side error"
-            #         )
-            #     else:
-            #         logger.opt(exception=True).warning(
-            #             "Request did not succeed due to server-side error"
-            #         )
-            #
-            # except Exception:
-            #     logger.opt(exception=True).error(
-            #         "Request failed due to unexpected error"
-            #     )
-            #     response = InternalServerException().response()
+        if request.url.path.startswith("integration"):
+            async with event_context(""):
+                await ocean.integration.port_app_config_handler.get_port_app_config()
+                response = await call_next(request)
+        else:
+            response = await call_next(request)
 
         end_time = get_time(seconds_precision=False)
         time_elapsed = round(end_time - start_time, 5)
         response.headers["X-Request-ID"] = request_id
         response.headers["X-Process-Time"] = str(time_elapsed)
         logger.bind(
             time_elapsed=time_elapsed, response_status=response.status_code
```

### Comparing `port_ocean-0.1.0.dev1/port_ocean/port_ocean.py` & `port_ocean-0.1.0.dev2/port_ocean/port_ocean.py`

 * *Files 2% similar despite different names*

```diff
@@ -60,15 +60,15 @@
     target_channel_router = APIRouter()
 
     @target_channel_router.post("/resync")
     async def resync() -> None:
         if _ocean.integration is None:
             raise Exception("Integration not set")
 
-        await _ocean.integration.trigger_resync()
+        await _ocean.integration.sync_all()
 
     app.include_router(target_channel_router)
 
 
 class Ocean:
     def __init__(
         self,
@@ -102,15 +102,15 @@
         self.fast_api_app.include_router(self.integration_router, prefix="/integration")
         if self.config.trigger_channel.type == "http":
             _include_target_channel_router(self.fast_api_app, ocean)
 
         @self.fast_api_app.on_event("startup")
         async def startup() -> None:
             try:
-                await self.integration.trigger_start()
+                await self.integration.start()
             except Exception as e:
                 logger.error(f"Failed to start integration with error: {e}")
                 sys.exit("Server stopped")
 
         await self.fast_api_app(scope, receive, send)
```

### Comparing `port_ocean-0.1.0.dev1/port_ocean/types.py` & `port_ocean-0.1.0.dev2/port_ocean/types.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,29 +1,27 @@
 from typing import (
     Awaitable,
     Callable,
     TypedDict,
-    List,
-    Dict,
     Any,
 )
 
 from port_ocean.core.models import Entity
 
 
-class EntityRawDiff(TypedDict):
-    before: List[Dict[Any, Any]]
-    after: List[Dict[Any, Any]]
+class RawEntityDiff(TypedDict):
+    before: list[dict[Any, Any]]
+    after: list[dict[Any, Any]]
 
 
 class EntityDiff(TypedDict):
-    before: List[Entity]
-    after: List[Entity]
+    before: list[Entity]
+    after: list[Entity]
 
 
-RESYNC_EVENT_LISTENER = Callable[[str], Awaitable[List[Dict[Any, Any]]]]
+RESYNC_EVENT_LISTENER = Callable[[str], Awaitable[list[dict[Any, Any]]]]
 START_EVENT_LISTENER = Callable[[], Awaitable]
 
 
 class IntegrationEventsCallbacks(TypedDict):
-    start: List[START_EVENT_LISTENER]
-    resync: Dict[str | None, List[RESYNC_EVENT_LISTENER]]
+    start: list[START_EVENT_LISTENER]
+    resync: dict[str | None, list[RESYNC_EVENT_LISTENER]]
```

### Comparing `port_ocean-0.1.0.dev1/pyproject.toml` & `port_ocean-0.1.0.dev2/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "port-ocean"
-version = "0.1.0.dev1"
+version = "0.1.0.dev2"
 description = "Port Ocean is a CLI tool for managing your Port projects."
 readme = "README.md"
 authors = ["Daniel Sinai <daniel@getport.io>", "Yair Siman-Tov <yair@getport.io>"]
 packages = [
     { include = "port_ocean", from = "." }
 ]
```

### Comparing `port_ocean-0.1.0.dev1/PKG-INFO` & `port_ocean-0.1.0.dev2/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: port-ocean
-Version: 0.1.0.dev1
+Version: 0.1.0.dev2
 Summary: Port Ocean is a CLI tool for managing your Port projects.
 Author: Daniel Sinai
 Author-email: daniel@getport.io
 Requires-Python: >=3.11,<4.0
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.11
 Provides-Extra: cli
```


# Comparing `tmp/petisco-2.0.0rc5.tar.gz` & `tmp/petisco-2.0.0rc6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "petisco-2.0.0rc5.tar", last modified: Tue Jun 27 09:47:10 2023, max compression
+gzip compressed data, was "petisco-2.0.0rc6.tar", last modified: Wed Jun 28 06:49:57 2023, max compression
```

## Comparing `petisco-2.0.0rc5.tar` & `petisco-2.0.0rc6.tar`

### file list

```diff
@@ -1,283 +1,283 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.320415 petisco-2.0.0rc5/
--rw-r--r--   0 runner    (1001) docker     (123)     1074 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)      102 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)     3369 2023-06-27 09:47:10.320415 petisco-2.0.0rc5/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2324 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.300415 petisco-2.0.0rc5/petisco/
--rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-27 09:47:04.000000 petisco-2.0.0rc5/petisco/VERSION
--rw-r--r--   0 runner    (1001) docker     (123)      238 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.300415 petisco-2.0.0rc5/petisco/base/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.300415 petisco-2.0.0rc5/petisco/base/application/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5672 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/application.py
--rw-r--r--   0 runner    (1001) docker     (123)      378 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/application_configurer.py
--rw-r--r--   0 runner    (1001) docker     (123)      687 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/application_info.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.300415 petisco-2.0.0rc5/petisco/base/application/chaos/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/chaos/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1413 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/chaos/chaos_config.py
--rw-r--r--   0 runner    (1001) docker     (123)      324 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/chaos/check_chaos.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.300415 petisco-2.0.0rc5/petisco/base/application/controller/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/controller/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1270 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/controller/async_controller.py
--rw-r--r--   0 runner    (1001) docker     (123)     2154 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/controller/controller.py
--rw-r--r--   0 runner    (1001) docker     (123)      211 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/controller/error_map.py
--rw-r--r--   0 runner    (1001) docker     (123)      474 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/controller/handlers.py
--rw-r--r--   0 runner    (1001) docker     (123)      584 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/controller/http_error.py
--rw-r--r--   0 runner    (1001) docker     (123)     1987 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/controller/meta_controller.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.300415 petisco-2.0.0rc5/petisco/base/application/dependency_injection/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/dependency_injection/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2900 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/dependency_injection/container.py
--rw-r--r--   0 runner    (1001) docker     (123)     3661 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/dependency_injection/dependency.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.300415 petisco-2.0.0rc5/petisco/base/application/handlers/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/handlers/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1784 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/handlers/message_handler.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.304415 petisco-2.0.0rc5/petisco/base/application/middleware/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/middleware/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      754 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/middleware/middleware.py
--rw-r--r--   0 runner    (1001) docker     (123)     2061 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/middleware/notifier_middleware.py
--rw-r--r--   0 runner    (1001) docker     (123)      404 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/middleware/print_middleware.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.304415 petisco-2.0.0rc5/petisco/base/application/notifier/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/notifier/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      485 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/notifier/not_implemented_notifier.py
--rw-r--r--   0 runner    (1001) docker     (123)      581 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/notifier/notifier.py
--rw-r--r--   0 runner    (1001) docker     (123)     1644 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/notifier/notifier_exception_message.py
--rw-r--r--   0 runner    (1001) docker     (123)      339 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/notifier/notifier_message.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.304415 petisco-2.0.0rc5/petisco/base/application/patterns/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/patterns/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      377 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/patterns/app_service.py
--rw-r--r--   0 runner    (1001) docker     (123)      394 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/patterns/async_app_service.py
--rw-r--r--   0 runner    (1001) docker     (123)     1119 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/patterns/crud_repository.py
--rw-r--r--   0 runner    (1001) docker     (123)     1868 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/patterns/inmemory_crud_repository.py
--rw-r--r--   0 runner    (1001) docker     (123)       89 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/patterns/repository.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.304415 petisco-2.0.0rc5/petisco/base/application/use_case/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/use_case/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      427 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/use_case/async_use_case.py
--rw-r--r--   0 runner    (1001) docker     (123)     3212 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/use_case/meta_use_case.py
--rw-r--r--   0 runner    (1001) docker     (123)      410 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/use_case/use_case.py
--rw-r--r--   0 runner    (1001) docker     (123)      123 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/application/use_case/use_case_uncontrolled_error.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.304415 petisco-2.0.0rc5/petisco/base/domain/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.304415 petisco-2.0.0rc5/petisco/base/domain/errors/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/errors/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      364 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/errors/critical_error.py
--rw-r--r--   0 runner    (1001) docker     (123)     1340 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/errors/default_http_error_map.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.304415 petisco-2.0.0rc5/petisco/base/domain/errors/defaults/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/errors/defaults/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      993 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/errors/defaults/already_exists.py
--rw-r--r--   0 runner    (1001) docker     (123)      106 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/errors/defaults/invalid_uuid.py
--rw-r--r--   0 runner    (1001) docker     (123)      113 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/errors/defaults/invalid_value_object.py
--rw-r--r--   0 runner    (1001) docker     (123)      183 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/errors/defaults/not_allowed.py
--rw-r--r--   0 runner    (1001) docker     (123)     1118 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/errors/defaults/not_found.py
--rw-r--r--   0 runner    (1001) docker     (123)     1099 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/errors/domain_error.py
--rw-r--r--   0 runner    (1001) docker     (123)     3307 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/errors/unknown_error.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.308415 petisco-2.0.0rc5/petisco/base/domain/message/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/message/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      468 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/message/all_message_subscriber.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.308415 petisco-2.0.0rc5/petisco/base/domain/message/chaos/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/message/chaos/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      466 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/message/chaos/message_chaos.py
--rw-r--r--   0 runner    (1001) docker     (123)       67 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/message/chaos/message_chaos_error.py
--rw-r--r--   0 runner    (1001) docker     (123)      662 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/message/chaos/not_implemented_message_chaos.py
--rw-r--r--   0 runner    (1001) docker     (123)     1208 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/message/command.py
--rw-r--r--   0 runner    (1001) docker     (123)     1023 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/message/command_bus.py
--rw-r--r--   0 runner    (1001) docker     (123)     1207 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/message/command_subscriber.py
--rw-r--r--   0 runner    (1001) docker     (123)      269 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/message/consumer_derived_action.py
--rw-r--r--   0 runner    (1001) docker     (123)     1202 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/message/domain_event.py
--rw-r--r--   0 runner    (1001) docker     (123)      950 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/message/domain_event_bus.py
--rw-r--r--   0 runner    (1001) docker     (123)      902 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/message/domain_event_subscriber.py
--rw-r--r--   0 runner    (1001) docker     (123)     6028 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/message/message.py
--rw-r--r--   0 runner    (1001) docker     (123)     1967 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/message/message_bus.py
--rw-r--r--   0 runner    (1001) docker     (123)      577 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/message/message_configurer.py
--rw-r--r--   0 runner    (1001) docker     (123)     1979 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/message/message_consumer.py
--rw-r--r--   0 runner    (1001) docker     (123)      555 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/message/message_handler_returns_none_error.py
--rw-r--r--   0 runner    (1001) docker     (123)     3302 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/message/message_subscriber.py
--rw-r--r--   0 runner    (1001) docker     (123)      580 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/message/message_subscriber_info.py
--rw-r--r--   0 runner    (1001) docker     (123)      549 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/message/not_implemented_command_bus.py
--rw-r--r--   0 runner    (1001) docker     (123)      963 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/message/not_implemented_domain_event_bus.py
--rw-r--r--   0 runner    (1001) docker     (123)      422 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/message/not_implemented_message_bus.py
--rw-r--r--   0 runner    (1001) docker     (123)      971 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/message/not_implemented_message_comsumer.py
--rw-r--r--   0 runner    (1001) docker     (123)      501 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/message/not_implemented_message_configurer.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.308415 petisco-2.0.0rc5/petisco/base/domain/model/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/model/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2442 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/model/aggregate_root.py
--rw-r--r--   0 runner    (1001) docker     (123)      635 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/model/uuid.py
--rw-r--r--   0 runner    (1001) docker     (123)     1371 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/model/value_object.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.308415 petisco-2.0.0rc5/petisco/base/domain/persistence/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/persistence/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      328 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/persistence/async_database.py
--rw-r--r--   0 runner    (1001) docker     (123)      561 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/persistence/async_fake_database.py
--rw-r--r--   0 runner    (1001) docker     (123)     1017 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/persistence/database.py
--rw-r--r--   0 runner    (1001) docker     (123)     5095 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/persistence/databases.py
--rw-r--r--   0 runner    (1001) docker     (123)      482 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/persistence/fake_database.py
--rw-r--r--   0 runner    (1001) docker     (123)      898 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/persistence/legacy_database.py
--rw-r--r--   0 runner    (1001) docker     (123)      902 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/persistence/legacy_fake_database.py
--rw-r--r--   0 runner    (1001) docker     (123)     6102 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/persistence/persistence.py
--rw-r--r--   0 runner    (1001) docker     (123)     4030 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/domain/persistence/persistence_models.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.308415 petisco-2.0.0rc5/petisco/base/misc/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/misc/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2017 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/misc/async_wrapper.py
--rw-r--r--   0 runner    (1001) docker     (123)     1136 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/misc/builder.py
--rw-r--r--   0 runner    (1001) docker     (123)      204 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/misc/interface.py
--rw-r--r--   0 runner    (1001) docker     (123)     1708 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/misc/result_mapper.py
--rw-r--r--   0 runner    (1001) docker     (123)      582 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/misc/singleton.py
--rw-r--r--   0 runner    (1001) docker     (123)     3621 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/misc/wrapper.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.308415 petisco-2.0.0rc5/petisco/base/testing/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/testing/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      319 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/base/testing/assert_http.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.308415 petisco-2.0.0rc5/petisco/cli/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/cli/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2872 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/cli/petisco.py
--rw-r--r--   0 runner    (1001) docker     (123)     7253 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/cli/petisco_dev.py
--rw-r--r--   0 runner    (1001) docker     (123)     5169 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/cli/petisco_rabbitmq.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.308415 petisco-2.0.0rc5/petisco/extra/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.312415 petisco-2.0.0rc5/petisco/extra/elastic/
--rw-r--r--   0 runner    (1001) docker     (123)      783 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/elastic/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2167 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/elastic/async_elastic_database.py
--rw-r--r--   0 runner    (1001) docker     (123)     1484 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/elastic/elastic_connection.py
--rw-r--r--   0 runner    (1001) docker     (123)     2046 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/elastic/elastic_database.py
--rw-r--r--   0 runner    (1001) docker     (123)      553 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/elastic/elastic_is_running_locally.py
--rw-r--r--   0 runner    (1001) docker     (123)      159 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/elastic/is_elastic_available.py
--rw-r--r--   0 runner    (1001) docker     (123)     1683 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/elastic/legacy_elastic_database.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.312415 petisco-2.0.0rc5/petisco/extra/elastic_apm/
--rw-r--r--   0 runner    (1001) docker     (123)      472 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/elastic_apm/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1060 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/elastic_apm/elastic_apm_monitoring_app_service.py
--rw-r--r--   0 runner    (1001) docker     (123)      160 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/elastic_apm/is_elastic_apm_available.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.312415 petisco-2.0.0rc5/petisco/extra/fastapi/
--rw-r--r--   0 runner    (1001) docker     (123)      760 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/fastapi/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.312415 petisco-2.0.0rc5/petisco/extra/fastapi/application/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/fastapi/application/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      282 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/fastapi/application/fastapi_application.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.312415 petisco-2.0.0rc5/petisco/extra/fastapi/controller/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/fastapi/controller/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      353 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/fastapi/controller/as_fastapi.py
--rw-r--r--   0 runner    (1001) docker     (123)      745 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/fastapi/controller/fastapi_controller.py
--rw-r--r--   0 runner    (1001) docker     (123)       45 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/fastapi/controller/fastapi_default_response.py
--rw-r--r--   0 runner    (1001) docker     (123)     2161 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/fastapi/controller/fastapi_failure_handler.py
--rw-r--r--   0 runner    (1001) docker     (123)     1112 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/fastapi/controller/fastapi_result_mapper.py
--rw-r--r--   0 runner    (1001) docker     (123)      481 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/fastapi/controller/fastapi_success_handler.py
--rw-r--r--   0 runner    (1001) docker     (123)      153 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/fastapi/is_fastapi_available.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.312415 petisco-2.0.0rc5/petisco/extra/fastapi/testing/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/fastapi/testing/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      512 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/fastapi/testing/assert_http_exception.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.312415 petisco-2.0.0rc5/petisco/extra/logger/
--rw-r--r--   0 runner    (1001) docker     (123)      531 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/logger/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      569 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/logger/log_message.py
--rw-r--r--   0 runner    (1001) docker     (123)      336 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/logger/logger.py
--rw-r--r--   0 runner    (1001) docker     (123)     2095 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/logger/logging_based_logger.py
--rw-r--r--   0 runner    (1001) docker     (123)     1380 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/logger/loguru_logger.py
--rw-r--r--   0 runner    (1001) docker     (123)      213 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/logger/not_implemented_logger.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.312415 petisco-2.0.0rc5/petisco/extra/rabbitmq/
--rw-r--r--   0 runner    (1001) docker     (123)     1966 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/rabbitmq/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.312415 petisco-2.0.0rc5/petisco/extra/rabbitmq/application/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/rabbitmq/application/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.312415 petisco-2.0.0rc5/petisco/extra/rabbitmq/application/chaos/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/rabbitmq/application/chaos/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5535 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/rabbitmq/application/chaos/rabbitmq_message_chaos.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.312415 petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.312415 petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/bus/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/bus/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3508 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/bus/rabbitmq_command_bus.py
--rw-r--r--   0 runner    (1001) docker     (123)     3527 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/bus/rabbitmq_domain_event_bus.py
--rw-r--r--   0 runner    (1001) docker     (123)     1105 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/bus/rabbitmq_message_publisher.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.316415 petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/configurer/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/configurer/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3085 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/configurer/rabbitmq_message_configurer.py
--rw-r--r--   0 runner    (1001) docker     (123)     5154 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/configurer/rabbitmq_message_store_configurer.py
--rw-r--r--   0 runner    (1001) docker     (123)     7210 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/configurer/rabbitmq_message_subscribers_configurer.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.316415 petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/consumer/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/consumer/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      485 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/consumer/rabbitmq_consumer_connector.py
--rw-r--r--   0 runner    (1001) docker     (123)     3643 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/consumer/rabbitmq_event_consumer_logger.py
--rw-r--r--   0 runner    (1001) docker     (123)     1679 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/consumer/rabbitmq_event_consumer_printer.py
--rw-r--r--   0 runner    (1001) docker     (123)    18674 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/consumer/rabbitmq_message_consumer.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.316415 petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/formatter/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/formatter/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1056 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/formatter/rabbitmq_message_queue_name_formatter.py
--rw-r--r--   0 runner    (1001) docker     (123)     1396 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/formatter/rabbitmq_message_subscriber_queue_name_formatter.py
--rw-r--r--   0 runner    (1001) docker     (123)     4007 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/rabbitmq/dependencies.py
--rw-r--r--   0 runner    (1001) docker     (123)      147 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/rabbitmq/is_pika_available.py
--rw-r--r--   0 runner    (1001) docker     (123)     1322 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/rabbitmq/rabbitmq_message_application_configurer.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.316415 petisco-2.0.0rc5/petisco/extra/rabbitmq/shared/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/rabbitmq/shared/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2156 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/rabbitmq/shared/queue_config.py
--rw-r--r--   0 runner    (1001) docker     (123)     4997 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/rabbitmq/shared/rabbitmq_connector.py
--rw-r--r--   0 runner    (1001) docker     (123)     2370 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/rabbitmq/shared/rabbitmq_declarer.py
--rw-r--r--   0 runner    (1001) docker     (123)      250 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/rabbitmq/shared/rabbitmq_exchange_name_formatter.py
--rw-r--r--   0 runner    (1001) docker     (123)      361 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/rabbitmq/shared/rabbitmq_is_running_locally.py
--rw-r--r--   0 runner    (1001) docker     (123)     1353 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/rabbitmq/shared/specific_queue_config.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.316415 petisco-2.0.0rc5/petisco/extra/redis/
--rw-r--r--   0 runner    (1001) docker     (123)      424 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/redis/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.316415 petisco-2.0.0rc5/petisco/extra/redis/application/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/redis/application/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.316415 petisco-2.0.0rc5/petisco/extra/redis/application/message/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/redis/application/message/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.316415 petisco-2.0.0rc5/petisco/extra/redis/application/message/bus/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/redis/application/message/bus/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      764 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/redis/application/message/bus/redis_command_bus.py
--rw-r--r--   0 runner    (1001) docker     (123)      832 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/redis/application/message/bus/redis_domain_event_bus.py
--rw-r--r--   0 runner    (1001) docker     (123)     1931 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/redis/application/message/bus/redis_message_bus.py
--rw-r--r--   0 runner    (1001) docker     (123)      149 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/redis/is_redis_available.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.316415 petisco-2.0.0rc5/petisco/extra/slack/
--rw-r--r--   0 runner    (1001) docker     (123)     1097 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/slack/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.316415 petisco-2.0.0rc5/petisco/extra/slack/application/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/slack/application/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.316415 petisco-2.0.0rc5/petisco/extra/slack/application/notifier/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/slack/application/notifier/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1751 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/slack/application/notifier/blocks_slack_notifier_message_converter.py
--rw-r--r--   0 runner    (1001) docker     (123)      246 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/slack/application/notifier/create_text_meta.py
--rw-r--r--   0 runner    (1001) docker     (123)     4763 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/slack/application/notifier/exception_blocks_slack_notifier_message_converter.py
--rw-r--r--   0 runner    (1001) docker     (123)     2145 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/slack/application/notifier/slack_notifier.py
--rw-r--r--   0 runner    (1001) docker     (123)      646 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/slack/application/notifier/slack_notifier_message_converter.py
--rw-r--r--   0 runner    (1001) docker     (123)     1054 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/slack/dependencies.py
--rw-r--r--   0 runner    (1001) docker     (123)      153 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/slack/is_slack_available.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.316415 petisco-2.0.0rc5/petisco/extra/sqlalchemy/
--rw-r--r--   0 runner    (1001) docker     (123)     1173 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/sqlalchemy/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      159 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/sqlalchemy/is_sqlalchemy_available.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.320415 petisco-2.0.0rc5/petisco/extra/sqlalchemy/sql/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/sqlalchemy/sql/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2955 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/sqlalchemy/sql/async_sql_database.py
--rw-r--r--   0 runner    (1001) docker     (123)      918 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/sqlalchemy/sql/async_sql_session_scope_provider.py
--rw-r--r--   0 runner    (1001) docker     (123)     1713 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/sqlalchemy/sql/base_sql_repository.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.320415 petisco-2.0.0rc5/petisco/extra/sqlalchemy/sql/mysql/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/sqlalchemy/sql/mysql/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3888 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/sqlalchemy/sql/mysql/legacy_mysql_database.py
--rw-r--r--   0 runner    (1001) docker     (123)     1700 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/sqlalchemy/sql/mysql/mysql_connection.py
--rw-r--r--   0 runner    (1001) docker     (123)      557 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/sqlalchemy/sql/mysql_is_running_locally.py
--rw-r--r--   0 runner    (1001) docker     (123)      855 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/sqlalchemy/sql/sql_base.py
--rw-r--r--   0 runner    (1001) docker     (123)     4673 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/sqlalchemy/sql/sql_database.py
--rw-r--r--   0 runner    (1001) docker     (123)     1013 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/sqlalchemy/sql/sql_executor.py
--rw-r--r--   0 runner    (1001) docker     (123)      810 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/sqlalchemy/sql/sql_session_scope_provider.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.320415 petisco-2.0.0rc5/petisco/extra/sqlalchemy/sql/sqlite/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/sqlalchemy/sql/sqlite/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3721 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/sqlalchemy/sql/sqlite/legacy_sqlite_database.py
--rw-r--r--   0 runner    (1001) docker     (123)      411 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/sqlalchemy/sql/sqlite/sqlite_connection.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.320415 petisco-2.0.0rc5/petisco/extra/sqlmodel/
--rw-r--r--   0 runner    (1001) docker     (123)      260 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/sqlmodel/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      155 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/sqlmodel/is_sqlmodel_available.py
--rw-r--r--   0 runner    (1001) docker     (123)     4078 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/sqlmodel/sqlmodel_crud_repository.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.320415 petisco-2.0.0rc5/petisco/extra/threading/
--rw-r--r--   0 runner    (1001) docker     (123)      140 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/threading/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1179 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/extra/threading/pool_executor.py
--rw-r--r--   0 runner    (1001) docker     (123)     6470 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/public_api.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/petisco/py.typed
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.300415 petisco-2.0.0rc5/petisco.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     3369 2023-06-27 09:47:10.000000 petisco-2.0.0rc5/petisco.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    10957 2023-06-27 09:47:10.000000 petisco-2.0.0rc5/petisco.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 09:47:10.000000 petisco-2.0.0rc5/petisco.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)      149 2023-06-27 09:47:10.000000 petisco-2.0.0rc5/petisco.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 09:47:10.000000 petisco-2.0.0rc5/petisco.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)      498 2023-06-27 09:47:10.000000 petisco-2.0.0rc5/petisco.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       14 2023-06-27 09:47:10.000000 petisco-2.0.0rc5/petisco.egg-info/top_level.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.320415 petisco-2.0.0rc5/requirements/
--rw-r--r--   0 runner    (1001) docker     (123)      165 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/requirements/requirements.txt
--rw-r--r--   0 runner    (1001) docker     (123)      677 2023-06-27 09:47:10.320415 petisco-2.0.0rc5/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2230 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.320415 petisco-2.0.0rc5/tests/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/tests/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/tests/conftest.py
--rw-r--r--   0 runner    (1001) docker     (123)      954 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/tests/fixtures.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:10.320415 petisco-2.0.0rc5/tests/modules/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 09:47:03.000000 petisco-2.0.0rc5/tests/modules/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.265428 petisco-2.0.0rc6/
+-rw-r--r--   0 runner    (1001) docker     (123)     1074 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)      102 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)     3369 2023-06-28 06:49:57.265428 petisco-2.0.0rc6/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2324 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.217429 petisco-2.0.0rc6/petisco/
+-rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/VERSION
+-rw-r--r--   0 runner    (1001) docker     (123)      238 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.221429 petisco-2.0.0rc6/petisco/base/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.221429 petisco-2.0.0rc6/petisco/base/application/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5672 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/application.py
+-rw-r--r--   0 runner    (1001) docker     (123)      378 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/application_configurer.py
+-rw-r--r--   0 runner    (1001) docker     (123)      687 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/application_info.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.221429 petisco-2.0.0rc6/petisco/base/application/chaos/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/chaos/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1413 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/chaos/chaos_config.py
+-rw-r--r--   0 runner    (1001) docker     (123)      324 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/chaos/check_chaos.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.225429 petisco-2.0.0rc6/petisco/base/application/controller/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/controller/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1270 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/controller/async_controller.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2154 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/controller/controller.py
+-rw-r--r--   0 runner    (1001) docker     (123)      211 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/controller/error_map.py
+-rw-r--r--   0 runner    (1001) docker     (123)      474 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/controller/handlers.py
+-rw-r--r--   0 runner    (1001) docker     (123)      584 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/controller/http_error.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1987 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/controller/meta_controller.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.225429 petisco-2.0.0rc6/petisco/base/application/dependency_injection/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/dependency_injection/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2900 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/dependency_injection/container.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3661 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/dependency_injection/dependency.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.225429 petisco-2.0.0rc6/petisco/base/application/handlers/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/handlers/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1784 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/handlers/message_handler.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.225429 petisco-2.0.0rc6/petisco/base/application/middleware/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/middleware/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      754 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/middleware/middleware.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2061 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/middleware/notifier_middleware.py
+-rw-r--r--   0 runner    (1001) docker     (123)      404 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/middleware/print_middleware.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.225429 petisco-2.0.0rc6/petisco/base/application/notifier/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/notifier/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      485 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/notifier/not_implemented_notifier.py
+-rw-r--r--   0 runner    (1001) docker     (123)      581 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/notifier/notifier.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1644 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/notifier/notifier_exception_message.py
+-rw-r--r--   0 runner    (1001) docker     (123)      339 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/notifier/notifier_message.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.229429 petisco-2.0.0rc6/petisco/base/application/patterns/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/patterns/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      377 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/patterns/app_service.py
+-rw-r--r--   0 runner    (1001) docker     (123)      394 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/patterns/async_app_service.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1119 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/patterns/crud_repository.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1868 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/patterns/inmemory_crud_repository.py
+-rw-r--r--   0 runner    (1001) docker     (123)       89 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/patterns/repository.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.229429 petisco-2.0.0rc6/petisco/base/application/use_case/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/use_case/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      427 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/use_case/async_use_case.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3212 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/use_case/meta_use_case.py
+-rw-r--r--   0 runner    (1001) docker     (123)      410 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/use_case/use_case.py
+-rw-r--r--   0 runner    (1001) docker     (123)      123 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/application/use_case/use_case_uncontrolled_error.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.229429 petisco-2.0.0rc6/petisco/base/domain/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.229429 petisco-2.0.0rc6/petisco/base/domain/errors/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/errors/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      364 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/errors/critical_error.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1340 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/errors/default_http_error_map.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.233429 petisco-2.0.0rc6/petisco/base/domain/errors/defaults/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/errors/defaults/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      993 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/errors/defaults/already_exists.py
+-rw-r--r--   0 runner    (1001) docker     (123)      106 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/errors/defaults/invalid_uuid.py
+-rw-r--r--   0 runner    (1001) docker     (123)      113 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/errors/defaults/invalid_value_object.py
+-rw-r--r--   0 runner    (1001) docker     (123)      183 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/errors/defaults/not_allowed.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1118 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/errors/defaults/not_found.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1099 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/errors/domain_error.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3307 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/errors/unknown_error.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.237429 petisco-2.0.0rc6/petisco/base/domain/message/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/message/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      468 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/message/all_message_subscriber.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.237429 petisco-2.0.0rc6/petisco/base/domain/message/chaos/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/message/chaos/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      466 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/message/chaos/message_chaos.py
+-rw-r--r--   0 runner    (1001) docker     (123)       67 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/message/chaos/message_chaos_error.py
+-rw-r--r--   0 runner    (1001) docker     (123)      662 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/message/chaos/not_implemented_message_chaos.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1208 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/message/command.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1023 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/message/command_bus.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1207 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/message/command_subscriber.py
+-rw-r--r--   0 runner    (1001) docker     (123)      269 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/message/consumer_derived_action.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1202 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/message/domain_event.py
+-rw-r--r--   0 runner    (1001) docker     (123)      950 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/message/domain_event_bus.py
+-rw-r--r--   0 runner    (1001) docker     (123)      902 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/message/domain_event_subscriber.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6028 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/message/message.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1967 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/message/message_bus.py
+-rw-r--r--   0 runner    (1001) docker     (123)      577 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/message/message_configurer.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1979 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/message/message_consumer.py
+-rw-r--r--   0 runner    (1001) docker     (123)      555 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/message/message_handler_returns_none_error.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3302 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/message/message_subscriber.py
+-rw-r--r--   0 runner    (1001) docker     (123)      580 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/message/message_subscriber_info.py
+-rw-r--r--   0 runner    (1001) docker     (123)      549 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/message/not_implemented_command_bus.py
+-rw-r--r--   0 runner    (1001) docker     (123)      963 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/message/not_implemented_domain_event_bus.py
+-rw-r--r--   0 runner    (1001) docker     (123)      422 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/message/not_implemented_message_bus.py
+-rw-r--r--   0 runner    (1001) docker     (123)      971 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/message/not_implemented_message_comsumer.py
+-rw-r--r--   0 runner    (1001) docker     (123)      501 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/message/not_implemented_message_configurer.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.237429 petisco-2.0.0rc6/petisco/base/domain/model/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/model/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2442 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/model/aggregate_root.py
+-rw-r--r--   0 runner    (1001) docker     (123)      635 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/model/uuid.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1371 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/model/value_object.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.241428 petisco-2.0.0rc6/petisco/base/domain/persistence/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/persistence/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      328 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/persistence/async_database.py
+-rw-r--r--   0 runner    (1001) docker     (123)      561 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/persistence/async_fake_database.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1017 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/persistence/database.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5936 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/persistence/databases.py
+-rw-r--r--   0 runner    (1001) docker     (123)      482 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/persistence/fake_database.py
+-rw-r--r--   0 runner    (1001) docker     (123)      898 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/persistence/legacy_database.py
+-rw-r--r--   0 runner    (1001) docker     (123)      902 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/persistence/legacy_fake_database.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6102 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/persistence/persistence.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4030 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/domain/persistence/persistence_models.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.241428 petisco-2.0.0rc6/petisco/base/misc/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/misc/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2017 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/misc/async_wrapper.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1136 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/misc/builder.py
+-rw-r--r--   0 runner    (1001) docker     (123)      204 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/misc/interface.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1708 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/misc/result_mapper.py
+-rw-r--r--   0 runner    (1001) docker     (123)      582 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/misc/singleton.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3621 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/misc/wrapper.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.241428 petisco-2.0.0rc6/petisco/base/testing/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/testing/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      319 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/base/testing/assert_http.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.241428 petisco-2.0.0rc6/petisco/cli/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/cli/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2872 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/cli/petisco.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7253 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/cli/petisco_dev.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5169 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/cli/petisco_rabbitmq.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.241428 petisco-2.0.0rc6/petisco/extra/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.245428 petisco-2.0.0rc6/petisco/extra/elastic/
+-rw-r--r--   0 runner    (1001) docker     (123)      783 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/elastic/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2167 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/elastic/async_elastic_database.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1484 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/elastic/elastic_connection.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2046 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/elastic/elastic_database.py
+-rw-r--r--   0 runner    (1001) docker     (123)      553 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/elastic/elastic_is_running_locally.py
+-rw-r--r--   0 runner    (1001) docker     (123)      159 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/elastic/is_elastic_available.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1683 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/elastic/legacy_elastic_database.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.245428 petisco-2.0.0rc6/petisco/extra/elastic_apm/
+-rw-r--r--   0 runner    (1001) docker     (123)      472 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/elastic_apm/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1060 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/elastic_apm/elastic_apm_monitoring_app_service.py
+-rw-r--r--   0 runner    (1001) docker     (123)      160 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/elastic_apm/is_elastic_apm_available.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.245428 petisco-2.0.0rc6/petisco/extra/fastapi/
+-rw-r--r--   0 runner    (1001) docker     (123)      760 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/fastapi/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.245428 petisco-2.0.0rc6/petisco/extra/fastapi/application/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/fastapi/application/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      282 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/fastapi/application/fastapi_application.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.249428 petisco-2.0.0rc6/petisco/extra/fastapi/controller/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/fastapi/controller/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      353 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/fastapi/controller/as_fastapi.py
+-rw-r--r--   0 runner    (1001) docker     (123)      745 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/fastapi/controller/fastapi_controller.py
+-rw-r--r--   0 runner    (1001) docker     (123)       45 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/fastapi/controller/fastapi_default_response.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2161 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/fastapi/controller/fastapi_failure_handler.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1112 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/fastapi/controller/fastapi_result_mapper.py
+-rw-r--r--   0 runner    (1001) docker     (123)      481 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/fastapi/controller/fastapi_success_handler.py
+-rw-r--r--   0 runner    (1001) docker     (123)      153 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/fastapi/is_fastapi_available.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.249428 petisco-2.0.0rc6/petisco/extra/fastapi/testing/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/fastapi/testing/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      512 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/fastapi/testing/assert_http_exception.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.249428 petisco-2.0.0rc6/petisco/extra/logger/
+-rw-r--r--   0 runner    (1001) docker     (123)      531 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/logger/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      569 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/logger/log_message.py
+-rw-r--r--   0 runner    (1001) docker     (123)      336 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/logger/logger.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2095 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/logger/logging_based_logger.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1380 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/logger/loguru_logger.py
+-rw-r--r--   0 runner    (1001) docker     (123)      213 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/logger/not_implemented_logger.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.249428 petisco-2.0.0rc6/petisco/extra/rabbitmq/
+-rw-r--r--   0 runner    (1001) docker     (123)     1966 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/rabbitmq/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.249428 petisco-2.0.0rc6/petisco/extra/rabbitmq/application/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/rabbitmq/application/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.249428 petisco-2.0.0rc6/petisco/extra/rabbitmq/application/chaos/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/rabbitmq/application/chaos/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5535 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/rabbitmq/application/chaos/rabbitmq_message_chaos.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.249428 petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.253428 petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/bus/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/bus/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3508 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/bus/rabbitmq_command_bus.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3527 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/bus/rabbitmq_domain_event_bus.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1105 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/bus/rabbitmq_message_publisher.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.253428 petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/configurer/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/configurer/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3085 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/configurer/rabbitmq_message_configurer.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5154 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/configurer/rabbitmq_message_store_configurer.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7210 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/configurer/rabbitmq_message_subscribers_configurer.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.253428 petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/consumer/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/consumer/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      485 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/consumer/rabbitmq_consumer_connector.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3643 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/consumer/rabbitmq_event_consumer_logger.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1679 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/consumer/rabbitmq_event_consumer_printer.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18674 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/consumer/rabbitmq_message_consumer.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.253428 petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/formatter/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/formatter/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1056 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/formatter/rabbitmq_message_queue_name_formatter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1396 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/formatter/rabbitmq_message_subscriber_queue_name_formatter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4007 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/rabbitmq/dependencies.py
+-rw-r--r--   0 runner    (1001) docker     (123)      147 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/rabbitmq/is_pika_available.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1322 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/rabbitmq/rabbitmq_message_application_configurer.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.257428 petisco-2.0.0rc6/petisco/extra/rabbitmq/shared/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/rabbitmq/shared/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2156 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/rabbitmq/shared/queue_config.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4997 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/rabbitmq/shared/rabbitmq_connector.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2370 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/rabbitmq/shared/rabbitmq_declarer.py
+-rw-r--r--   0 runner    (1001) docker     (123)      250 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/rabbitmq/shared/rabbitmq_exchange_name_formatter.py
+-rw-r--r--   0 runner    (1001) docker     (123)      361 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/rabbitmq/shared/rabbitmq_is_running_locally.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1353 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/rabbitmq/shared/specific_queue_config.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.257428 petisco-2.0.0rc6/petisco/extra/redis/
+-rw-r--r--   0 runner    (1001) docker     (123)      424 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/redis/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.257428 petisco-2.0.0rc6/petisco/extra/redis/application/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/redis/application/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.257428 petisco-2.0.0rc6/petisco/extra/redis/application/message/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/redis/application/message/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.257428 petisco-2.0.0rc6/petisco/extra/redis/application/message/bus/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/redis/application/message/bus/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      764 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/redis/application/message/bus/redis_command_bus.py
+-rw-r--r--   0 runner    (1001) docker     (123)      832 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/redis/application/message/bus/redis_domain_event_bus.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1931 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/redis/application/message/bus/redis_message_bus.py
+-rw-r--r--   0 runner    (1001) docker     (123)      149 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/redis/is_redis_available.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.257428 petisco-2.0.0rc6/petisco/extra/slack/
+-rw-r--r--   0 runner    (1001) docker     (123)     1097 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/slack/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.257428 petisco-2.0.0rc6/petisco/extra/slack/application/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/slack/application/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.261428 petisco-2.0.0rc6/petisco/extra/slack/application/notifier/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/slack/application/notifier/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1751 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/slack/application/notifier/blocks_slack_notifier_message_converter.py
+-rw-r--r--   0 runner    (1001) docker     (123)      246 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/slack/application/notifier/create_text_meta.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4847 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/slack/application/notifier/exception_blocks_slack_notifier_message_converter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2145 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/slack/application/notifier/slack_notifier.py
+-rw-r--r--   0 runner    (1001) docker     (123)      646 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/slack/application/notifier/slack_notifier_message_converter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1054 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/slack/dependencies.py
+-rw-r--r--   0 runner    (1001) docker     (123)      153 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/slack/is_slack_available.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.261428 petisco-2.0.0rc6/petisco/extra/sqlalchemy/
+-rw-r--r--   0 runner    (1001) docker     (123)     1173 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/sqlalchemy/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      159 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/sqlalchemy/is_sqlalchemy_available.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.265428 petisco-2.0.0rc6/petisco/extra/sqlalchemy/sql/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/sqlalchemy/sql/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2955 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/sqlalchemy/sql/async_sql_database.py
+-rw-r--r--   0 runner    (1001) docker     (123)      918 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/sqlalchemy/sql/async_sql_session_scope_provider.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1713 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/sqlalchemy/sql/base_sql_repository.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.265428 petisco-2.0.0rc6/petisco/extra/sqlalchemy/sql/mysql/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/sqlalchemy/sql/mysql/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3888 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/sqlalchemy/sql/mysql/legacy_mysql_database.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1700 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/sqlalchemy/sql/mysql/mysql_connection.py
+-rw-r--r--   0 runner    (1001) docker     (123)      557 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/sqlalchemy/sql/mysql_is_running_locally.py
+-rw-r--r--   0 runner    (1001) docker     (123)      855 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/sqlalchemy/sql/sql_base.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5145 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/sqlalchemy/sql/sql_database.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1013 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/sqlalchemy/sql/sql_executor.py
+-rw-r--r--   0 runner    (1001) docker     (123)      810 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/sqlalchemy/sql/sql_session_scope_provider.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.265428 petisco-2.0.0rc6/petisco/extra/sqlalchemy/sql/sqlite/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/sqlalchemy/sql/sqlite/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3721 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/sqlalchemy/sql/sqlite/legacy_sqlite_database.py
+-rw-r--r--   0 runner    (1001) docker     (123)      411 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/sqlalchemy/sql/sqlite/sqlite_connection.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.265428 petisco-2.0.0rc6/petisco/extra/sqlmodel/
+-rw-r--r--   0 runner    (1001) docker     (123)      260 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/sqlmodel/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      155 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/sqlmodel/is_sqlmodel_available.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4078 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/sqlmodel/sqlmodel_crud_repository.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.265428 petisco-2.0.0rc6/petisco/extra/threading/
+-rw-r--r--   0 runner    (1001) docker     (123)      140 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/threading/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1179 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/extra/threading/pool_executor.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6470 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/public_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/petisco/py.typed
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.221429 petisco-2.0.0rc6/petisco.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     3369 2023-06-28 06:49:57.000000 petisco-2.0.0rc6/petisco.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    10957 2023-06-28 06:49:57.000000 petisco-2.0.0rc6/petisco.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 06:49:57.000000 petisco-2.0.0rc6/petisco.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      149 2023-06-28 06:49:57.000000 petisco-2.0.0rc6/petisco.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 06:49:57.000000 petisco-2.0.0rc6/petisco.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)      498 2023-06-28 06:49:57.000000 petisco-2.0.0rc6/petisco.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       14 2023-06-28 06:49:57.000000 petisco-2.0.0rc6/petisco.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.265428 petisco-2.0.0rc6/requirements/
+-rw-r--r--   0 runner    (1001) docker     (123)      165 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/requirements/requirements.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      677 2023-06-28 06:49:57.265428 petisco-2.0.0rc6/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2230 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.265428 petisco-2.0.0rc6/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/tests/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/tests/conftest.py
+-rw-r--r--   0 runner    (1001) docker     (123)      954 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/tests/fixtures.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:57.265428 petisco-2.0.0rc6/tests/modules/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:49:53.000000 petisco-2.0.0rc6/tests/modules/__init__.py
```

### Comparing `petisco-2.0.0rc5/LICENSE` & `petisco-2.0.0rc6/LICENSE`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/PKG-INFO` & `petisco-2.0.0rc6/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: petisco
-Version: 2.0.0rc5
+Version: 2.0.0rc6
 Summary: Petisco is a framework for helping Python developers to build clean Applications
 Home-page: https://github.com/alice-biometrics/petisco
 Author: Alice Biometrics
 Author-email: support@alicebiometrics.com
 License: MIT
 Keywords: DDD,Use Case,Clean Architecture,REST,Applications
 Classifier: License :: OSI Approved :: MIT License
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: petisco Version: 2.0.0rc5 Summary: Petisco is a
+Metadata-Version: 2.1 Name: petisco Version: 2.0.0rc6 Summary: Petisco is a
 framework for helping Python developers to build clean Applications Home-page:
 https://github.com/alice-biometrics/petisco Author: Alice Biometrics Author-
 email: support@alicebiometrics.com License: MIT Keywords: DDD,Use Case,Clean
 Architecture,REST,Applications Classifier: License :: OSI Approved :: MIT
 License Classifier: Programming Language :: Python Classifier: Programming
 Language :: Python :: 3 Classifier: Programming Language :: Python :: 3 :: Only
 Classifier: Programming Language :: Python :: 3.7 Classifier: Programming
```

### Comparing `petisco-2.0.0rc5/README.md` & `petisco-2.0.0rc6/README.md`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/application/application.py` & `petisco-2.0.0rc6/petisco/base/application/application.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/application/application_info.py` & `petisco-2.0.0rc6/petisco/base/application/application_info.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/application/chaos/chaos_config.py` & `petisco-2.0.0rc6/petisco/base/application/chaos/chaos_config.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/application/controller/async_controller.py` & `petisco-2.0.0rc6/petisco/base/application/controller/async_controller.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/application/controller/controller.py` & `petisco-2.0.0rc6/petisco/base/application/controller/controller.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/application/controller/http_error.py` & `petisco-2.0.0rc6/petisco/base/application/controller/http_error.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/application/controller/meta_controller.py` & `petisco-2.0.0rc6/petisco/base/application/controller/meta_controller.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/application/dependency_injection/container.py` & `petisco-2.0.0rc6/petisco/base/application/dependency_injection/container.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/application/dependency_injection/dependency.py` & `petisco-2.0.0rc6/petisco/base/application/dependency_injection/dependency.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/application/handlers/message_handler.py` & `petisco-2.0.0rc6/petisco/base/application/handlers/message_handler.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/application/middleware/middleware.py` & `petisco-2.0.0rc6/petisco/base/application/middleware/middleware.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/application/middleware/notifier_middleware.py` & `petisco-2.0.0rc6/petisco/base/application/middleware/notifier_middleware.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/application/notifier/notifier.py` & `petisco-2.0.0rc6/petisco/base/application/notifier/notifier.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/application/notifier/notifier_exception_message.py` & `petisco-2.0.0rc6/petisco/base/application/notifier/notifier_exception_message.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/application/patterns/crud_repository.py` & `petisco-2.0.0rc6/petisco/base/application/patterns/crud_repository.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/application/patterns/inmemory_crud_repository.py` & `petisco-2.0.0rc6/petisco/base/application/patterns/inmemory_crud_repository.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/application/use_case/meta_use_case.py` & `petisco-2.0.0rc6/petisco/base/application/use_case/meta_use_case.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/domain/errors/default_http_error_map.py` & `petisco-2.0.0rc6/petisco/base/domain/errors/default_http_error_map.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/domain/errors/defaults/already_exists.py` & `petisco-2.0.0rc6/petisco/base/domain/errors/defaults/already_exists.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/domain/errors/defaults/not_found.py` & `petisco-2.0.0rc6/petisco/base/domain/errors/defaults/not_found.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/domain/errors/domain_error.py` & `petisco-2.0.0rc6/petisco/base/domain/errors/domain_error.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/domain/errors/unknown_error.py` & `petisco-2.0.0rc6/petisco/base/domain/errors/unknown_error.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/domain/message/chaos/not_implemented_message_chaos.py` & `petisco-2.0.0rc6/petisco/base/domain/message/chaos/not_implemented_message_chaos.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/domain/message/command.py` & `petisco-2.0.0rc6/petisco/base/domain/message/command.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/domain/message/command_bus.py` & `petisco-2.0.0rc6/petisco/base/domain/message/command_bus.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/domain/message/command_subscriber.py` & `petisco-2.0.0rc6/petisco/base/domain/message/command_subscriber.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/domain/message/domain_event.py` & `petisco-2.0.0rc6/petisco/base/domain/message/domain_event.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/domain/message/domain_event_bus.py` & `petisco-2.0.0rc6/petisco/base/domain/message/domain_event_bus.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/domain/message/domain_event_subscriber.py` & `petisco-2.0.0rc6/petisco/base/domain/message/domain_event_subscriber.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/domain/message/message.py` & `petisco-2.0.0rc6/petisco/base/domain/message/message.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/domain/message/message_bus.py` & `petisco-2.0.0rc6/petisco/base/domain/message/message_bus.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/domain/message/message_configurer.py` & `petisco-2.0.0rc6/petisco/base/domain/message/message_configurer.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/domain/message/message_consumer.py` & `petisco-2.0.0rc6/petisco/base/domain/message/message_consumer.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/domain/message/message_handler_returns_none_error.py` & `petisco-2.0.0rc6/petisco/base/domain/message/message_handler_returns_none_error.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/domain/message/message_subscriber.py` & `petisco-2.0.0rc6/petisco/base/domain/message/message_subscriber.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/domain/message/message_subscriber_info.py` & `petisco-2.0.0rc6/petisco/base/domain/message/message_subscriber_info.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/domain/message/not_implemented_command_bus.py` & `petisco-2.0.0rc6/petisco/base/domain/message/not_implemented_command_bus.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/domain/message/not_implemented_domain_event_bus.py` & `petisco-2.0.0rc6/petisco/base/domain/message/not_implemented_domain_event_bus.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/domain/message/not_implemented_message_comsumer.py` & `petisco-2.0.0rc6/petisco/base/domain/message/not_implemented_message_comsumer.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/domain/model/aggregate_root.py` & `petisco-2.0.0rc6/petisco/base/domain/model/aggregate_root.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/domain/model/uuid.py` & `petisco-2.0.0rc6/petisco/base/domain/model/uuid.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/domain/model/value_object.py` & `petisco-2.0.0rc6/petisco/base/domain/model/value_object.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/domain/persistence/async_fake_database.py` & `petisco-2.0.0rc6/petisco/base/domain/persistence/async_fake_database.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/domain/persistence/database.py` & `petisco-2.0.0rc6/petisco/base/domain/persistence/database.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/domain/persistence/databases.py` & `petisco-2.0.0rc6/petisco/base/domain/persistence/databases.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,18 +1,23 @@
 from __future__ import annotations
 
 from dataclasses import dataclass
-from typing import Any, TypeVar
+from typing import Any, TypedDict, TypeVar
 
 from petisco.base.domain.persistence.async_database import AsyncDatabase
 from petisco.base.domain.persistence.database import Database
 
 T = TypeVar("T")
 
 
+class InitializationArguments(TypedDict):
+    database_alias: str
+    arguments: dict[str, Any]
+
+
 def get_key(base_type: type[T], alias: str | None = None) -> str:
     return base_type.__name__ if not alias else alias
 
 
 @dataclass
 class _Databases:
     def __init__(self) -> None:
@@ -107,24 +112,44 @@
         if key in self._databases:
             self._databases[key].delete()
             del self._databases[key]
         else:
             if skip_if_not_exist is False:
                 raise IndexError(f"Database cannot be removed. {key} does not exists")
 
-    def initialize(self) -> None:
+    def initialize(
+        self, initialization_arguments: InitializationArguments | None = None
+    ) -> None:
         for database in self._databases.values():
             if isinstance(database, AsyncDatabase):
                 continue
-            database.initialize()
+            arguments = (
+                initialization_arguments.get(database.alias)
+                if initialization_arguments
+                else None
+            )
+            if arguments:
+                database.initialize(**arguments)
+            else:
+                database.initialize()
 
-    async def async_initialize(self) -> None:
+    async def async_initialize(
+        self, initialization_arguments: InitializationArguments | None = None
+    ) -> None:
         for database in self._databases.values():
             if isinstance(database, AsyncDatabase):
-                await database.initialize()
+                arguments = (
+                    initialization_arguments.get(database.alias)
+                    if initialization_arguments
+                    else None
+                )
+                if arguments:
+                    await database.initialize(**arguments)
+                else:
+                    await database.initialize()
 
     def delete(self) -> None:
         for database in self._databases.values():
             database.delete()
 
     def clear_database(self, base_type: type[T], *, alias: str | None = None) -> None:
         key = get_key(base_type, alias)
```

### Comparing `petisco-2.0.0rc5/petisco/base/domain/persistence/legacy_database.py` & `petisco-2.0.0rc6/petisco/base/domain/persistence/legacy_database.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/domain/persistence/legacy_fake_database.py` & `petisco-2.0.0rc6/petisco/base/domain/persistence/legacy_fake_database.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/domain/persistence/persistence.py` & `petisco-2.0.0rc6/petisco/base/domain/persistence/persistence.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/domain/persistence/persistence_models.py` & `petisco-2.0.0rc6/petisco/base/domain/persistence/persistence_models.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/misc/async_wrapper.py` & `petisco-2.0.0rc6/petisco/base/misc/async_wrapper.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/misc/builder.py` & `petisco-2.0.0rc6/petisco/base/misc/builder.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/misc/result_mapper.py` & `petisco-2.0.0rc6/petisco/base/misc/result_mapper.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/misc/singleton.py` & `petisco-2.0.0rc6/petisco/base/misc/singleton.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/base/misc/wrapper.py` & `petisco-2.0.0rc6/petisco/base/misc/wrapper.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/cli/petisco.py` & `petisco-2.0.0rc6/petisco/cli/petisco.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/cli/petisco_dev.py` & `petisco-2.0.0rc6/petisco/cli/petisco_dev.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/cli/petisco_rabbitmq.py` & `petisco-2.0.0rc6/petisco/cli/petisco_rabbitmq.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/elastic/__init__.py` & `petisco-2.0.0rc6/petisco/extra/elastic/__init__.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/elastic/async_elastic_database.py` & `petisco-2.0.0rc6/petisco/extra/elastic/async_elastic_database.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/elastic/elastic_connection.py` & `petisco-2.0.0rc6/petisco/extra/elastic/elastic_connection.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/elastic/elastic_database.py` & `petisco-2.0.0rc6/petisco/extra/elastic/elastic_database.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/elastic/elastic_is_running_locally.py` & `petisco-2.0.0rc6/petisco/extra/elastic/elastic_is_running_locally.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/elastic/legacy_elastic_database.py` & `petisco-2.0.0rc6/petisco/extra/elastic/legacy_elastic_database.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/elastic_apm/elastic_apm_monitoring_app_service.py` & `petisco-2.0.0rc6/petisco/extra/elastic_apm/elastic_apm_monitoring_app_service.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/fastapi/__init__.py` & `petisco-2.0.0rc6/petisco/extra/fastapi/__init__.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/fastapi/controller/fastapi_controller.py` & `petisco-2.0.0rc6/petisco/extra/fastapi/controller/fastapi_controller.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/fastapi/controller/fastapi_failure_handler.py` & `petisco-2.0.0rc6/petisco/extra/fastapi/controller/fastapi_failure_handler.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/fastapi/controller/fastapi_result_mapper.py` & `petisco-2.0.0rc6/petisco/extra/fastapi/controller/fastapi_result_mapper.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/fastapi/testing/assert_http_exception.py` & `petisco-2.0.0rc6/petisco/extra/fastapi/testing/assert_http_exception.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/logger/__init__.py` & `petisco-2.0.0rc6/petisco/extra/logger/__init__.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/logger/log_message.py` & `petisco-2.0.0rc6/petisco/extra/logger/log_message.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/logger/logging_based_logger.py` & `petisco-2.0.0rc6/petisco/extra/logger/logging_based_logger.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/logger/loguru_logger.py` & `petisco-2.0.0rc6/petisco/extra/logger/loguru_logger.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/rabbitmq/__init__.py` & `petisco-2.0.0rc6/petisco/extra/rabbitmq/__init__.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/rabbitmq/application/chaos/rabbitmq_message_chaos.py` & `petisco-2.0.0rc6/petisco/extra/rabbitmq/application/chaos/rabbitmq_message_chaos.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/bus/rabbitmq_command_bus.py` & `petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/bus/rabbitmq_command_bus.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/bus/rabbitmq_domain_event_bus.py` & `petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/bus/rabbitmq_domain_event_bus.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/bus/rabbitmq_message_publisher.py` & `petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/bus/rabbitmq_message_publisher.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/configurer/rabbitmq_message_configurer.py` & `petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/configurer/rabbitmq_message_configurer.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/configurer/rabbitmq_message_store_configurer.py` & `petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/configurer/rabbitmq_message_store_configurer.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/configurer/rabbitmq_message_subscribers_configurer.py` & `petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/configurer/rabbitmq_message_subscribers_configurer.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/consumer/rabbitmq_event_consumer_logger.py` & `petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/consumer/rabbitmq_event_consumer_logger.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/consumer/rabbitmq_event_consumer_printer.py` & `petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/consumer/rabbitmq_event_consumer_printer.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/consumer/rabbitmq_message_consumer.py` & `petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/consumer/rabbitmq_message_consumer.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/formatter/rabbitmq_message_queue_name_formatter.py` & `petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/formatter/rabbitmq_message_queue_name_formatter.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/rabbitmq/application/message/formatter/rabbitmq_message_subscriber_queue_name_formatter.py` & `petisco-2.0.0rc6/petisco/extra/rabbitmq/application/message/formatter/rabbitmq_message_subscriber_queue_name_formatter.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/rabbitmq/dependencies.py` & `petisco-2.0.0rc6/petisco/extra/rabbitmq/dependencies.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/rabbitmq/rabbitmq_message_application_configurer.py` & `petisco-2.0.0rc6/petisco/extra/rabbitmq/rabbitmq_message_application_configurer.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/rabbitmq/shared/queue_config.py` & `petisco-2.0.0rc6/petisco/extra/rabbitmq/shared/queue_config.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/rabbitmq/shared/rabbitmq_connector.py` & `petisco-2.0.0rc6/petisco/extra/rabbitmq/shared/rabbitmq_connector.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/rabbitmq/shared/rabbitmq_declarer.py` & `petisco-2.0.0rc6/petisco/extra/rabbitmq/shared/rabbitmq_declarer.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/rabbitmq/shared/specific_queue_config.py` & `petisco-2.0.0rc6/petisco/extra/rabbitmq/shared/specific_queue_config.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/redis/application/message/bus/redis_command_bus.py` & `petisco-2.0.0rc6/petisco/extra/redis/application/message/bus/redis_command_bus.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/redis/application/message/bus/redis_domain_event_bus.py` & `petisco-2.0.0rc6/petisco/extra/redis/application/message/bus/redis_domain_event_bus.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/redis/application/message/bus/redis_message_bus.py` & `petisco-2.0.0rc6/petisco/extra/redis/application/message/bus/redis_message_bus.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/slack/__init__.py` & `petisco-2.0.0rc6/petisco/extra/slack/__init__.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/slack/application/notifier/blocks_slack_notifier_message_converter.py` & `petisco-2.0.0rc6/petisco/extra/slack/application/notifier/blocks_slack_notifier_message_converter.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/slack/application/notifier/exception_blocks_slack_notifier_message_converter.py` & `petisco-2.0.0rc6/petisco/extra/slack/application/notifier/exception_blocks_slack_notifier_message_converter.py`

 * *Files 1% similar despite different names*

```diff
@@ -96,14 +96,16 @@
                 f"*Class*: {notifier_exception_message.exception.__class__}\n"
                 f">{str(notifier_exception_message.exception)[:500]}"
             )
             traceback_base_str = "\n```{}```"
             traceback_max_length = 3000 - len(text_error) - len(traceback_base_str)
             text_error += traceback_base_str.format(
                 notifier_exception_message.traceback[:traceback_max_length]
+                if notifier_exception_message.traceback
+                else "None"
             )
 
             error_block = {
                 "type": "section",
                 "text": {
                     "type": "mrkdwn",
                     "text": text_error,
```

### Comparing `petisco-2.0.0rc5/petisco/extra/slack/application/notifier/slack_notifier.py` & `petisco-2.0.0rc6/petisco/extra/slack/application/notifier/slack_notifier.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/slack/application/notifier/slack_notifier_message_converter.py` & `petisco-2.0.0rc6/petisco/extra/slack/application/notifier/slack_notifier_message_converter.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/slack/dependencies.py` & `petisco-2.0.0rc6/petisco/extra/slack/dependencies.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/sqlalchemy/__init__.py` & `petisco-2.0.0rc6/petisco/extra/sqlalchemy/__init__.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/sqlalchemy/sql/async_sql_database.py` & `petisco-2.0.0rc6/petisco/extra/sqlalchemy/sql/async_sql_database.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/sqlalchemy/sql/async_sql_session_scope_provider.py` & `petisco-2.0.0rc6/petisco/extra/sqlalchemy/sql/async_sql_session_scope_provider.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/sqlalchemy/sql/base_sql_repository.py` & `petisco-2.0.0rc6/petisco/extra/sqlalchemy/sql/base_sql_repository.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/sqlalchemy/sql/mysql/legacy_mysql_database.py` & `petisco-2.0.0rc6/petisco/extra/sqlalchemy/sql/mysql/legacy_mysql_database.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/sqlalchemy/sql/mysql/mysql_connection.py` & `petisco-2.0.0rc6/petisco/extra/sqlalchemy/sql/mysql/mysql_connection.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/sqlalchemy/sql/mysql_is_running_locally.py` & `petisco-2.0.0rc6/petisco/extra/sqlalchemy/sql/mysql_is_running_locally.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/sqlalchemy/sql/sql_base.py` & `petisco-2.0.0rc6/petisco/extra/sqlalchemy/sql/sql_base.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/sqlalchemy/sql/sql_database.py` & `petisco-2.0.0rc6/petisco/extra/sqlalchemy/sql/sql_database.py`

 * *Files 9% similar despite different names*

```diff
@@ -29,43 +29,51 @@
     def __init__(
         self,
         connection: SqliteConnection | MySqlConnection,
         *,
         alias: str | None = None,
         print_sql_statements: bool = False,
         use_scoped_session: bool = True,
-        initial_statements_filename: str = None,
+        before_initial_statements: Callable[[], None] | None = None,
+        initial_statements_filename: str | None = None,
+        after_initial_statements: Callable[[], None] | None = None,
     ):
         self.connection = connection
         self.print_sql_statements = print_sql_statements
         self.use_scoped_session = use_scoped_session
+        self.before_initial_statements = before_initial_statements
         self.initial_statements_filename = initial_statements_filename
+        self.after_initial_statements = after_initial_statements
         self._check_connection()
         super().__init__(alias)
 
     def _check_connection(self) -> None:
         if not self.connection or not isinstance(
             self.connection, (SqliteConnection, MySqlConnection)
         ):
             raise ConnectionError(
                 "SqlDatabase needs a valid SqliteConnection or MySqlConnection connection"
             )
 
-    def initialize(self, base: DeclarativeBase = SqlBase) -> None:
+    def initialize(self, base: type[DeclarativeBase] = SqlBase) -> None:
         engine = create_engine(
             self.connection.url,
             json_serializer=lambda obj: obj,
             json_deserializer=lambda obj: obj,
             echo=self.print_sql_statements,
         )
 
         if not database_exists(engine.url):
             create_database(engine.url)
             base.metadata.create_all(engine)
+            if self.before_initial_statements:
+                self.before_initial_statements()
             self._run_initial_statements(engine)
+            if self.after_initial_statements:
+                self.after_initial_statements()
 
         self.session_factory = sessionmaker(bind=engine)
 
     def _run_initial_statements(self, engine) -> None:
         if self.initial_statements_filename:
             try:
                 file = open(self.initial_statements_filename)
```

### Comparing `petisco-2.0.0rc5/petisco/extra/sqlalchemy/sql/sql_executor.py` & `petisco-2.0.0rc6/petisco/extra/sqlalchemy/sql/sql_executor.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/sqlalchemy/sql/sql_session_scope_provider.py` & `petisco-2.0.0rc6/petisco/extra/sqlalchemy/sql/sql_session_scope_provider.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/sqlalchemy/sql/sqlite/legacy_sqlite_database.py` & `petisco-2.0.0rc6/petisco/extra/sqlalchemy/sql/sqlite/legacy_sqlite_database.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/sqlmodel/sqlmodel_crud_repository.py` & `petisco-2.0.0rc6/petisco/extra/sqlmodel/sqlmodel_crud_repository.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/extra/threading/pool_executor.py` & `petisco-2.0.0rc6/petisco/extra/threading/pool_executor.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco/public_api.py` & `petisco-2.0.0rc6/petisco/public_api.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/petisco.egg-info/PKG-INFO` & `petisco-2.0.0rc6/petisco.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: petisco
-Version: 2.0.0rc5
+Version: 2.0.0rc6
 Summary: Petisco is a framework for helping Python developers to build clean Applications
 Home-page: https://github.com/alice-biometrics/petisco
 Author: Alice Biometrics
 Author-email: support@alicebiometrics.com
 License: MIT
 Keywords: DDD,Use Case,Clean Architecture,REST,Applications
 Classifier: License :: OSI Approved :: MIT License
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: petisco Version: 2.0.0rc5 Summary: Petisco is a
+Metadata-Version: 2.1 Name: petisco Version: 2.0.0rc6 Summary: Petisco is a
 framework for helping Python developers to build clean Applications Home-page:
 https://github.com/alice-biometrics/petisco Author: Alice Biometrics Author-
 email: support@alicebiometrics.com License: MIT Keywords: DDD,Use Case,Clean
 Architecture,REST,Applications Classifier: License :: OSI Approved :: MIT
 License Classifier: Programming Language :: Python Classifier: Programming
 Language :: Python :: 3 Classifier: Programming Language :: Python :: 3 :: Only
 Classifier: Programming Language :: Python :: 3.7 Classifier: Programming
```

### Comparing `petisco-2.0.0rc5/petisco.egg-info/SOURCES.txt` & `petisco-2.0.0rc6/petisco.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/setup.cfg` & `petisco-2.0.0rc6/setup.cfg`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/setup.py` & `petisco-2.0.0rc6/setup.py`

 * *Files identical despite different names*

### Comparing `petisco-2.0.0rc5/tests/fixtures.py` & `petisco-2.0.0rc6/tests/fixtures.py`

 * *Files identical despite different names*


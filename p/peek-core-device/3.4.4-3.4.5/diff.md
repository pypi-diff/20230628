# Comparing `tmp/peek-core-device-3.4.4.tar.gz` & `tmp/peek-core-device-3.4.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "peek-core-device-3.4.4.tar", last modified: Tue Jun 27 02:01:47 2023, max compression
+gzip compressed data, was "peek-core-device-3.4.5.tar", last modified: Wed Jun 28 07:26:13 2023, max compression
```

## Comparing `peek-core-device-3.4.4.tar` & `peek-core-device-3.4.5.tar`

### file list

```diff
@@ -1,231 +1,232 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.376525 peek-core-device-3.4.4/
--rw-r--r--   0 root         (0) root         (0)      407 2023-06-27 02:01:47.376525 peek-core-device-3.4.4/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)      138 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/README.rst
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.366525 peek-core-device-3.4.4/peek_core_device/
--rw-r--r--   0 root         (0) root         (0)      466 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/PlatformDependencyTest.py
--rw-r--r--   0 root         (0) root         (0)      692 2023-06-27 02:01:47.000000 peek-core-device-3.4.4/peek_core_device/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.367524 peek-core-device-3.4.4/peek_core_device/_private/
--rw-r--r--   0 root         (0) root         (0)      224 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/PluginNames.py
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.367524 peek-core-device-3.4.4/peek_core_device/_private/admin-app/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.367524 peek-core-device-3.4.4/peek_core_device/_private/admin-app/device-cache-status/
--rw-r--r--   0 root         (0) root         (0)     1644 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/admin-app/device-cache-status/device-cache-status.component.html
--rw-r--r--   0 root         (0) root         (0)       33 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/admin-app/device-cache-status/device-cache-status.component.scss
--rw-r--r--   0 root         (0) root         (0)     2443 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/admin-app/device-cache-status/device-cache-status.component.ts
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.367524 peek-core-device-3.4.4/peek_core_device/_private/admin-app/device-info-table/
--rw-r--r--   0 root         (0) root         (0)     5597 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/admin-app/device-info-table/device-info.component.html
--rw-r--r--   0 root         (0) root         (0)     5442 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/admin-app/device-info-table/device-info.component.ts
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.367524 peek-core-device-3.4.4/peek_core_device/_private/admin-app/device-update-table/
--rw-r--r--   0 root         (0) root         (0)     1741 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/admin-app/device-update-table/device-update.component.html
--rw-r--r--   0 root         (0) root         (0)     2504 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/admin-app/device-update-table/device-update.component.ts
--rw-r--r--   0 root         (0) root         (0)     2986 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/admin-app/device.component.html
--rw-r--r--   0 root         (0) root         (0)      209 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/admin-app/device.component.ts
--rw-r--r--   0 root         (0) root         (0)     3125 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/admin-app/device.module.ts
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.367524 peek-core-device-3.4.4/peek_core_device/_private/admin-app/edit-setting-table/
--rw-r--r--   0 root         (0) root         (0)     2595 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/admin-app/edit-setting-table/edit.component.html
--rw-r--r--   0 root         (0) root         (0)     1502 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/admin-app/edit-setting-table/edit.component.ts
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.367524 peek-core-device-3.4.4/peek_core_device/_private/admin-app/loading/
--rw-r--r--   0 root         (0) root         (0)      302 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/admin-app/loading/loading.component.ts
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.367524 peek-core-device-3.4.4/peek_core_device/_private/admin-app/tuples/
--rw-r--r--   0 root         (0) root         (0)      528 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/admin-app/tuples/DeviceCacheStatusTuple.ts
--rw-r--r--   0 root         (0) root         (0)     3278 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/admin-app/tuples/DeviceInfoTable.ts
--rw-r--r--   0 root         (0) root         (0)      469 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/admin-app/tuples/UpdateOfflineCacheSettingAction.ts
--rw-r--r--   0 root         (0) root         (0)       53 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/admin-app/tuples/index.ts
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.368524 peek-core-device-3.4.4/peek_core_device/_private/admin-app/upload-device-update/
--rw-r--r--   0 root         (0) root         (0)     3134 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/admin-app/upload-device-update/upload-device-update.component.html
--rw-r--r--   0 root         (0) root         (0)     4085 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/admin-app/upload-device-update/upload-device-update.component.ts
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.368524 peek-core-device-3.4.4/peek_core_device/_private/alembic/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/alembic/__init__.py
--rw-r--r--   0 root         (0) root         (0)      318 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/alembic/env.py
--rw-r--r--   0 root         (0) root         (0)      524 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/alembic/script.py.mako
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.368524 peek-core-device-3.4.4/peek_core_device/_private/alembic/versions/
--rw-r--r--   0 root         (0) root         (0)     1916 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/alembic/versions/02f9305f9e7f_added_gps_tracking.py
--rw-r--r--   0 root         (0) root         (0)     1681 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/alembic/versions/2561b7732a6c_gps_devicetoken_on_cascade.py
--rw-r--r--   0 root         (0) root         (0)      895 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/alembic/versions/4b0d6309e556_add_offline_cache_enable.py
--rw-r--r--   0 root         (0) root         (0)      800 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/alembic/versions/5dd43ff7ea8e_added_filesize_to_update_tuple.py
--rw-r--r--   0 root         (0) root         (0)     1313 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/alembic/versions/6bf6ecef3108_timezone_aware.py
--rw-r--r--   0 root         (0) root         (0)     1129 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/alembic/versions/7f628c121c4c_replaced_isonline_with_devicestatus.py
--rw-r--r--   0 root         (0) root         (0)      810 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/alembic/versions/97d44e5aeb18_add_lastbandwidthmetric.py
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/alembic/versions/__init__.py
--rw-r--r--   0 root         (0) root         (0)     4139 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/alembic/versions/d94277dd8aca_initial_table_creation.py
--rw-r--r--   0 root         (0) root         (0)       94 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/alembic.ini
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.369525 peek-core-device-3.4.4/peek_core_device/_private/both-app/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.369525 peek-core-device-3.4.4/peek_core_device/_private/both-app/connect/
--rw-r--r--   0 root         (0) root         (0)     3212 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/both-app/connect/connect.component.ts
--rw-r--r--   0 root         (0) root         (0)     2405 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/both-app/connect/connect.component.web.html
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.369525 peek-core-device-3.4.4/peek_core_device/_private/both-app/connecting/
--rw-r--r--   0 root         (0) root         (0)     1448 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/both-app/connecting/connecting.component.ts
--rw-r--r--   0 root         (0) root         (0)     1098 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/both-app/connecting/connecting.component.web.html
--rw-r--r--   0 root         (0) root         (0)      285 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/both-app/device.component.ts
--rw-r--r--   0 root         (0) root         (0)      471 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/both-app/device.component.web.html
--rw-r--r--   0 root         (0) root         (0)     2988 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/both-app/device.module.ts
--rw-r--r--   0 root         (0) root         (0)     1006 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/both-app/device.routes.ts
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.369525 peek-core-device-3.4.4/peek_core_device/_private/both-app/enroll/
--rw-r--r--   0 root         (0) root         (0)     3897 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/both-app/enroll/enroll.component.ts
--rw-r--r--   0 root         (0) root         (0)     1295 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/both-app/enroll/enroll.component.web.html
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.369525 peek-core-device-3.4.4/peek_core_device/_private/both-app/enrolling/
--rw-r--r--   0 root         (0) root         (0)     1536 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/both-app/enrolling/enrolling.component.ts
--rw-r--r--   0 root         (0) root         (0)      582 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/both-app/enrolling/enrolling.component.web.html
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.369525 peek-core-device-3.4.4/peek_core_device/_private/both-app/loading/
--rw-r--r--   0 root         (0) root         (0)      537 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/both-app/loading/loading.component.ts
--rw-r--r--   0 root         (0) root         (0)      489 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/both-app/loading/loading.component.web.html
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.369525 peek-core-device-3.4.4/peek_core_device/_private/both-cfg/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.369525 peek-core-device-3.4.4/peek_core_device/_private/both-cfg/connect/
--rw-r--r--   0 root         (0) root         (0)     2539 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/both-cfg/connect/connect.component.ts
--rw-r--r--   0 root         (0) root         (0)      305 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/both-cfg/connect/connect.component.web.html
--rw-r--r--   0 root         (0) root         (0)     1602 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/both-cfg/core-device-cfg.component.ts
--rw-r--r--   0 root         (0) root         (0)     1864 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/both-cfg/core-device-cfg.component.web.html
--rw-r--r--   0 root         (0) root         (0)     2798 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/both-cfg/core-device-cfg.module.ts
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.370525 peek-core-device-3.4.4/peek_core_device/_private/client/
--rw-r--r--   0 root         (0) root         (0)     3629 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/client/ClientEntryHook.py
--rw-r--r--   0 root         (0) root         (0)      527 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/client/DeviceTupleDataObservableProxy.py
--rw-r--r--   0 root         (0) root         (0)      496 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/client/DeviceTupleProcessorActionProxy.py
--rw-r--r--   0 root         (0) root         (0)     2175 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/client/UpdateDownloadHandler.py
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/client/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.370525 peek-core-device-3.4.4/peek_core_device/_private/client/controllers/
--rw-r--r--   0 root         (0) root         (0)     1893 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/client/controllers/BandwidthTestController.py
--rw-r--r--   0 root         (0) root         (0)     3949 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/client/controllers/DeviceOnlineController.py
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/client/controllers/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.370525 peek-core-device-3.4.4/peek_core_device/_private/server/
--rw-r--r--   0 root         (0) root         (0)     4271 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/server/DeviceApi.py
--rw-r--r--   0 root         (0) root         (0)     5495 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/server/LogicEntryHook.py
--rw-r--r--   0 root         (0) root         (0)      532 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/server/TupleActionProcessor.py
--rw-r--r--   0 root         (0) root         (0)     3688 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/server/TupleDataObservable.py
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/server/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.370525 peek-core-device-3.4.4/peek_core_device/_private/server/admin_backend/
--rw-r--r--   0 root         (0) root         (0)     2170 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/server/admin_backend/SettingPropertyHandler.py
--rw-r--r--   0 root         (0) root         (0)      318 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/server/admin_backend/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.371524 peek-core-device-3.4.4/peek_core_device/_private/server/controller/
--rw-r--r--   0 root         (0) root         (0)     2786 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/server/controller/BandwidthResultController.py
--rw-r--r--   0 root         (0) root         (0)     4319 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/server/controller/DeviceStatusController.py
--rw-r--r--   0 root         (0) root         (0)     4352 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/server/controller/EnrollmentController.py
--rw-r--r--   0 root         (0) root         (0)     5391 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/server/controller/GpsController.py
--rw-r--r--   0 root         (0) root         (0)     3978 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/server/controller/MainController.py
--rw-r--r--   0 root         (0) root         (0)     3238 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/server/controller/NotifierController.py
--rw-r--r--   0 root         (0) root         (0)     3701 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/server/controller/OfflineCacheController.py
--rw-r--r--   0 root         (0) root         (0)     5731 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/server/controller/UpdateController.py
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/server/controller/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.371524 peek-core-device-3.4.4/peek_core_device/_private/server/tuple_providers/
--rw-r--r--   0 root         (0) root         (0)     2984 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/server/tuple_providers/ClientSettingsTupleProvider.py
--rw-r--r--   0 root         (0) root         (0)     1240 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/server/tuple_providers/DeviceGpsLocationTupleProvider.py
--rw-r--r--   0 root         (0) root         (0)     3152 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/server/tuple_providers/DeviceInfoTableTupleProvider.py
--rw-r--r--   0 root         (0) root         (0)     3001 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/server/tuple_providers/DeviceInfoTupleProvider.py
--rw-r--r--   0 root         (0) root         (0)     2556 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/server/tuple_providers/DeviceUpdateTupleProvider.py
--rw-r--r--   0 root         (0) root         (0)     1348 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/server/tuple_providers/OfflineCacheCombinedStatusTupleProvider.py
--rw-r--r--   0 root         (0) root         (0)     1692 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/server/tuple_providers/OfflineCacheSettingTupleProvider.py
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/server/tuple_providers/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.371524 peek-core-device-3.4.4/peek_core_device/_private/server/update_resources/
--rw-r--r--   0 root         (0) root         (0)     2350 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/server/update_resources/DeviceUpdateUploadResource.py
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/server/update_resources/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.372525 peek-core-device-3.4.4/peek_core_device/_private/storage/
--rw-r--r--   0 root         (0) root         (0)      711 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/storage/DeclarativeBase.py
--rw-r--r--   0 root         (0) root         (0)     3713 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/storage/DeviceInfoTable.py
--rw-r--r--   0 root         (0) root         (0)     1431 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/storage/DeviceUpdateTuple.py
--rw-r--r--   0 root         (0) root         (0)     1005 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/storage/GpsLocationHistoryTable.py
--rw-r--r--   0 root         (0) root         (0)     1242 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/storage/GpsLocationTable.py
--rw-r--r--   0 root         (0) root         (0)     9117 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/storage/Setting.py
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/storage/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.373525 peek-core-device-3.4.4/peek_core_device/_private/tuples/
--rw-r--r--   0 root         (0) root         (0)      777 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/tuples/AlterDeviceUpdateAction.py
--rw-r--r--   0 root         (0) root         (0)      509 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/tuples/BandwidthTestResultTuple.py
--rw-r--r--   0 root         (0) root         (0)      342 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/tuples/BandwidthTestTuple.py
--rw-r--r--   0 root         (0) root         (0)      812 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/tuples/ClientSettingsTuple.py
--rw-r--r--   0 root         (0) root         (0)      602 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/tuples/CreateDeviceUpdateAction.py
--rw-r--r--   0 root         (0) root         (0)      414 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/tuples/DeviceBackgroundStateTupleAction.py
--rw-r--r--   0 root         (0) root         (0)      545 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/tuples/DeviceCacheStatusTuple.py
--rw-r--r--   0 root         (0) root         (0)      446 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/tuples/EnrolDeviceAction.py
--rw-r--r--   0 root         (0) root         (0)      847 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/tuples/OfflineCacheCombinedStatusTuple.py
--rw-r--r--   0 root         (0) root         (0)      691 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/tuples/OfflineCacheLoaderStatusTuple.py
--rw-r--r--   0 root         (0) root         (0)      447 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/tuples/OfflineCacheSettingTuple.py
--rw-r--r--   0 root         (0) root         (0)      890 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/tuples/OfflineCacheStatusAction.py
--rw-r--r--   0 root         (0) root         (0)     1459 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/tuples/OfflineCacheStatusTuple.py
--rw-r--r--   0 root         (0) root         (0)      506 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/tuples/UpdateAppliedAction.py
--rw-r--r--   0 root         (0) root         (0)      590 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/tuples/UpdateDeviceGpsLocationTupleAction.py
--rw-r--r--   0 root         (0) root         (0)      620 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/tuples/UpdateDeviceOnlineAction.py
--rw-r--r--   0 root         (0) root         (0)      587 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/tuples/UpdateEnrollmentAction.py
--rw-r--r--   0 root         (0) root         (0)      588 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/tuples/UpdateOfflineCacheSettingAction.py
--rw-r--r--   0 root         (0) root         (0)      637 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/tuples/WebClientVortexDetailsTuple.py
--rw-r--r--   0 root         (0) root         (0)      347 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/_private/tuples/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.373525 peek-core-device-3.4.4/peek_core_device/admin-doc/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.373525 peek-core-device-3.4.4/peek_core_device/admin-doc/admin_tasks/
--rw-r--r--   0 root         (0) root         (0)    64585 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/admin-doc/admin_tasks/admin_task_devices.png
--rw-r--r--   0 root         (0) root         (0)     1475 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/admin-doc/admin_tasks/admin_tasks.rst
--rw-r--r--   0 root         (0) root         (0)    62597 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/admin-doc/admin_tasks/device_search.png
--rw-r--r--   0 root         (0) root         (0)    25072 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/admin-doc/admin_tasks/offline_cache_info.png
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.373525 peek-core-device-3.4.4/peek_core_device/admin-doc/general_settings/
--rw-r--r--   0 root         (0) root         (0)   202788 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/admin-doc/general_settings/general_settings.png
--rw-r--r--   0 root         (0) root         (0)     1417 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/admin-doc/general_settings/general_settings.rst
--rw-r--r--   0 root         (0) root         (0)      433 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/admin-doc/index.rst
--rw-r--r--   0 root         (0) root         (0)      515 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/admin-doc/overview.rst
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.373525 peek-core-device-3.4.4/peek_core_device/both-doc/
--rw-r--r--   0 root         (0) root         (0)      848 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/both-doc/index.rst
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.374524 peek-core-device-3.4.4/peek_core_device/plugin-module/
--rw-r--r--   0 root         (0) root         (0)      552 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/DeviceGpsLocationTuple.ts
--rw-r--r--   0 root         (0) root         (0)     2952 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/DeviceInfoTuple.ts
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.374524 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/
--rw-r--r--   0 root         (0) root         (0)      333 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/PluginNames.ts
--rw-r--r--   0 root         (0) root         (0)     1051 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/device-background.service.ts
--rw-r--r--   0 root         (0) root         (0)     8054 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/device-bandwidth-test.service.ts
--rw-r--r--   0 root         (0) root         (0)      767 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/device-loading.module.ts
--rw-r--r--   0 root         (0) root         (0)     1180 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/device-nav.service.ts
--rw-r--r--   0 root         (0) root         (0)     1024 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/device-online.service.ts
--rw-r--r--   0 root         (0) root         (0)     7060 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/device-server.service.ts
--rw-r--r--   0 root         (0) root         (0)     2937 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/device-tuple.service.ts
--rw-r--r--   0 root         (0) root         (0)     5938 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/device-update.service.ts
--rw-r--r--   0 root         (0) root         (0)      592 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/device-update.service.web.ts
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.374524 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/gps/
--rw-r--r--   0 root         (0) root         (0)      711 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/gps/GpsLocationUpdateTupleAction.ts
--rw-r--r--   0 root         (0) root         (0)     6740 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/gps/private-gps-location.service.ts
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.375525 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/hardware-info/
--rw-r--r--   0 root         (0) root         (0)     2318 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/hardware-info/hardware-info.ts
--rw-r--r--   0 root         (0) root         (0)       30 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/hardware-info/is-field.dweb.ts
--rw-r--r--   0 root         (0) root         (0)       29 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/hardware-info/is-field.mweb.ts
--rw-r--r--   0 root         (0) root         (0)     1255 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/index.ts
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.375525 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/tuples/
--rw-r--r--   0 root         (0) root         (0)      497 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/tuples/BandwidthTestResultTuple.ts
--rw-r--r--   0 root         (0) root         (0)      383 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/tuples/BandwidthTestTuple.ts
--rw-r--r--   0 root         (0) root         (0)      789 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/tuples/ClientSettingsTuple.ts
--rw-r--r--   0 root         (0) root         (0)      451 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/tuples/DeviceBackgroundStateTupleAction.ts
--rw-r--r--   0 root         (0) root         (0)      662 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/tuples/DeviceUpdateLocalValuesTuple.ts
--rw-r--r--   0 root         (0) root         (0)      551 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/tuples/DeviceUpdateTuple.ts
--rw-r--r--   0 root         (0) root         (0)      438 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/tuples/EnrolDeviceAction.ts
--rw-r--r--   0 root         (0) root         (0)      670 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/tuples/OfflineCacheCombinedStatusTuple.ts
--rw-r--r--   0 root         (0) root         (0)      391 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/tuples/OfflineCacheSettingTuple.ts
--rw-r--r--   0 root         (0) root         (0)      477 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/tuples/OfflineCacheStatusAction.ts
--rw-r--r--   0 root         (0) root         (0)     3198 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/tuples/OfflineCacheStatusTuple.ts
--rw-r--r--   0 root         (0) root         (0)      470 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/tuples/UpdateAppliedAction.ts
--rw-r--r--   0 root         (0) root         (0)      641 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/tuples/UpdateDeviceOnlineAction.ts
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.376525 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/tuples/admin/
--rw-r--r--   0 root         (0) root         (0)      523 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/tuples/admin/AlterDeviceUpdateAction.ts
--rw-r--r--   0 root         (0) root         (0)      467 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/tuples/admin/CreateDeviceUpdateAction.ts
--rw-r--r--   0 root         (0) root         (0)      572 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/tuples/admin/SettingPropertyTuple.ts
--rw-r--r--   0 root         (0) root         (0)      455 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/tuples/admin/UpdateEnrollmentAction.ts
--rw-r--r--   0 root         (0) root         (0)      152 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/tuples/server-info-tuple-defaults.ts
--rw-r--r--   0 root         (0) root         (0)      731 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/_private/tuples/server-info-tuple.ts
--rw-r--r--   0 root         (0) root         (0)     2337 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/device-enrolled.guard.ts
--rw-r--r--   0 root         (0) root         (0)     3849 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/device-enrolment.service.ts
--rw-r--r--   0 root         (0) root         (0)    24494 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/device-offline-cache.service.ts
--rw-r--r--   0 root         (0) root         (0)     1553 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/device-status.service.ts
--rw-r--r--   0 root         (0) root         (0)      356 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/gps-location.service.ts
--rw-r--r--   0 root         (0) root         (0)      546 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/index.ts
--rw-r--r--   0 root         (0) root         (0)      301 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/package.json
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.376525 peek-core-device-3.4.4/peek_core_device/plugin-module/tuples/
--rw-r--r--   0 root         (0) root         (0)     1344 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/plugin-module/tuples/OfflineCacheLoaderStatusTuple.ts
--rw-r--r--   0 root         (0) root         (0)     6342 2023-06-27 02:01:47.000000 peek-core-device-3.4.4/peek_core_device/plugin_package.json
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.376525 peek-core-device-3.4.4/peek_core_device/server/
--rw-r--r--   0 root         (0) root         (0)     2404 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/server/DeviceApiABC.py
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/server/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.376525 peek-core-device-3.4.4/peek_core_device/tuples/
--rw-r--r--   0 root         (0) root         (0)     1312 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/tuples/DeviceDetailTuple.py
--rw-r--r--   0 root         (0) root         (0)      494 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/tuples/DeviceGpsLocationTuple.py
--rw-r--r--   0 root         (0) root         (0)     1479 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/tuples/DeviceInfoTuple.py
--rw-r--r--   0 root         (0) root         (0)      814 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/tuples/DeviceStatusTuple.py
--rw-r--r--   0 root         (0) root         (0)      344 2023-06-27 02:00:58.000000 peek-core-device-3.4.4/peek_core_device/tuples/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 02:01:47.366525 peek-core-device-3.4.4/peek_core_device.egg-info/
--rw-r--r--   0 root         (0) root         (0)      407 2023-06-27 02:01:47.000000 peek-core-device-3.4.4/peek_core_device.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)    11609 2023-06-27 02:01:47.000000 peek-core-device-3.4.4/peek_core_device.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-27 02:01:47.000000 peek-core-device-3.4.4/peek_core_device.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)       32 2023-06-27 02:01:47.000000 peek-core-device-3.4.4/peek_core_device.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)       17 2023-06-27 02:01:47.000000 peek-core-device-3.4.4/peek_core_device.egg-info/top_level.txt
--rw-r--r--   0 root         (0) root         (0)       38 2023-06-27 02:01:47.377524 peek-core-device-3.4.4/setup.cfg
--rw-r--r--   0 root         (0) root         (0)     2547 2023-06-27 02:01:47.000000 peek-core-device-3.4.4/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.726070 peek-core-device-3.4.5/
+-rw-r--r--   0 root         (0) root         (0)      407 2023-06-28 07:26:13.726070 peek-core-device-3.4.5/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)      138 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/README.rst
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.716070 peek-core-device-3.4.5/peek_core_device/
+-rw-r--r--   0 root         (0) root         (0)      466 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/PlatformDependencyTest.py
+-rw-r--r--   0 root         (0) root         (0)      692 2023-06-28 07:26:13.000000 peek-core-device-3.4.5/peek_core_device/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.716070 peek-core-device-3.4.5/peek_core_device/_private/
+-rw-r--r--   0 root         (0) root         (0)      224 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/PluginNames.py
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.716070 peek-core-device-3.4.5/peek_core_device/_private/admin-app/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.717070 peek-core-device-3.4.5/peek_core_device/_private/admin-app/device-cache-status/
+-rw-r--r--   0 root         (0) root         (0)     1644 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/admin-app/device-cache-status/device-cache-status.component.html
+-rw-r--r--   0 root         (0) root         (0)       33 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/admin-app/device-cache-status/device-cache-status.component.scss
+-rw-r--r--   0 root         (0) root         (0)     2443 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/admin-app/device-cache-status/device-cache-status.component.ts
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.717070 peek-core-device-3.4.5/peek_core_device/_private/admin-app/device-info-table/
+-rw-r--r--   0 root         (0) root         (0)     5597 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/admin-app/device-info-table/device-info.component.html
+-rw-r--r--   0 root         (0) root         (0)     5442 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/admin-app/device-info-table/device-info.component.ts
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.717070 peek-core-device-3.4.5/peek_core_device/_private/admin-app/device-update-table/
+-rw-r--r--   0 root         (0) root         (0)     1741 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/admin-app/device-update-table/device-update.component.html
+-rw-r--r--   0 root         (0) root         (0)     2504 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/admin-app/device-update-table/device-update.component.ts
+-rw-r--r--   0 root         (0) root         (0)     2986 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/admin-app/device.component.html
+-rw-r--r--   0 root         (0) root         (0)      209 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/admin-app/device.component.ts
+-rw-r--r--   0 root         (0) root         (0)     3125 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/admin-app/device.module.ts
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.717070 peek-core-device-3.4.5/peek_core_device/_private/admin-app/edit-setting-table/
+-rw-r--r--   0 root         (0) root         (0)     2595 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/admin-app/edit-setting-table/edit.component.html
+-rw-r--r--   0 root         (0) root         (0)     1502 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/admin-app/edit-setting-table/edit.component.ts
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.717070 peek-core-device-3.4.5/peek_core_device/_private/admin-app/loading/
+-rw-r--r--   0 root         (0) root         (0)      302 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/admin-app/loading/loading.component.ts
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.717070 peek-core-device-3.4.5/peek_core_device/_private/admin-app/tuples/
+-rw-r--r--   0 root         (0) root         (0)      528 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/admin-app/tuples/DeviceCacheStatusTuple.ts
+-rw-r--r--   0 root         (0) root         (0)     3278 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/admin-app/tuples/DeviceInfoTable.ts
+-rw-r--r--   0 root         (0) root         (0)      469 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/admin-app/tuples/UpdateOfflineCacheSettingAction.ts
+-rw-r--r--   0 root         (0) root         (0)       53 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/admin-app/tuples/index.ts
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.717070 peek-core-device-3.4.5/peek_core_device/_private/admin-app/upload-device-update/
+-rw-r--r--   0 root         (0) root         (0)     3134 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/admin-app/upload-device-update/upload-device-update.component.html
+-rw-r--r--   0 root         (0) root         (0)     4085 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/admin-app/upload-device-update/upload-device-update.component.ts
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.717070 peek-core-device-3.4.5/peek_core_device/_private/alembic/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/alembic/__init__.py
+-rw-r--r--   0 root         (0) root         (0)      318 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/alembic/env.py
+-rw-r--r--   0 root         (0) root         (0)      524 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/alembic/script.py.mako
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.718070 peek-core-device-3.4.5/peek_core_device/_private/alembic/versions/
+-rw-r--r--   0 root         (0) root         (0)     1916 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/alembic/versions/02f9305f9e7f_added_gps_tracking.py
+-rw-r--r--   0 root         (0) root         (0)     1681 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/alembic/versions/2561b7732a6c_gps_devicetoken_on_cascade.py
+-rw-r--r--   0 root         (0) root         (0)      895 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/alembic/versions/4b0d6309e556_add_offline_cache_enable.py
+-rw-r--r--   0 root         (0) root         (0)      800 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/alembic/versions/5dd43ff7ea8e_added_filesize_to_update_tuple.py
+-rw-r--r--   0 root         (0) root         (0)     1313 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/alembic/versions/6bf6ecef3108_timezone_aware.py
+-rw-r--r--   0 root         (0) root         (0)     1129 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/alembic/versions/7f628c121c4c_replaced_isonline_with_devicestatus.py
+-rw-r--r--   0 root         (0) root         (0)      810 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/alembic/versions/97d44e5aeb18_add_lastbandwidthmetric.py
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/alembic/versions/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     4139 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/alembic/versions/d94277dd8aca_initial_table_creation.py
+-rw-r--r--   0 root         (0) root         (0)       94 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/alembic.ini
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.718070 peek-core-device-3.4.5/peek_core_device/_private/both-app/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.718070 peek-core-device-3.4.5/peek_core_device/_private/both-app/connect/
+-rw-r--r--   0 root         (0) root         (0)     3212 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/both-app/connect/connect.component.ts
+-rw-r--r--   0 root         (0) root         (0)     2405 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/both-app/connect/connect.component.web.html
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.718070 peek-core-device-3.4.5/peek_core_device/_private/both-app/connecting/
+-rw-r--r--   0 root         (0) root         (0)     1448 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/both-app/connecting/connecting.component.ts
+-rw-r--r--   0 root         (0) root         (0)     1098 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/both-app/connecting/connecting.component.web.html
+-rw-r--r--   0 root         (0) root         (0)      285 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/both-app/device.component.ts
+-rw-r--r--   0 root         (0) root         (0)      471 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/both-app/device.component.web.html
+-rw-r--r--   0 root         (0) root         (0)     2988 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/both-app/device.module.ts
+-rw-r--r--   0 root         (0) root         (0)     1006 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/both-app/device.routes.ts
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.718070 peek-core-device-3.4.5/peek_core_device/_private/both-app/enroll/
+-rw-r--r--   0 root         (0) root         (0)     3897 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/both-app/enroll/enroll.component.ts
+-rw-r--r--   0 root         (0) root         (0)     1295 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/both-app/enroll/enroll.component.web.html
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.719070 peek-core-device-3.4.5/peek_core_device/_private/both-app/enrolling/
+-rw-r--r--   0 root         (0) root         (0)     1536 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/both-app/enrolling/enrolling.component.ts
+-rw-r--r--   0 root         (0) root         (0)      582 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/both-app/enrolling/enrolling.component.web.html
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.719070 peek-core-device-3.4.5/peek_core_device/_private/both-app/loading/
+-rw-r--r--   0 root         (0) root         (0)      537 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/both-app/loading/loading.component.ts
+-rw-r--r--   0 root         (0) root         (0)      489 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/both-app/loading/loading.component.web.html
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.719070 peek-core-device-3.4.5/peek_core_device/_private/both-cfg/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.719070 peek-core-device-3.4.5/peek_core_device/_private/both-cfg/connect/
+-rw-r--r--   0 root         (0) root         (0)     2539 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/both-cfg/connect/connect.component.ts
+-rw-r--r--   0 root         (0) root         (0)      305 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/both-cfg/connect/connect.component.web.html
+-rw-r--r--   0 root         (0) root         (0)     1997 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/both-cfg/core-device-cfg.component.ts
+-rw-r--r--   0 root         (0) root         (0)     2171 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/both-cfg/core-device-cfg.component.web.html
+-rw-r--r--   0 root         (0) root         (0)     2877 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/both-cfg/core-device-cfg.module.ts
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.719070 peek-core-device-3.4.5/peek_core_device/_private/client/
+-rw-r--r--   0 root         (0) root         (0)     3629 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/client/ClientEntryHook.py
+-rw-r--r--   0 root         (0) root         (0)      527 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/client/DeviceTupleDataObservableProxy.py
+-rw-r--r--   0 root         (0) root         (0)      496 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/client/DeviceTupleProcessorActionProxy.py
+-rw-r--r--   0 root         (0) root         (0)     2175 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/client/UpdateDownloadHandler.py
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/client/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.719070 peek-core-device-3.4.5/peek_core_device/_private/client/controllers/
+-rw-r--r--   0 root         (0) root         (0)     1893 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/client/controllers/BandwidthTestController.py
+-rw-r--r--   0 root         (0) root         (0)     3949 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/client/controllers/DeviceOnlineController.py
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/client/controllers/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.720070 peek-core-device-3.4.5/peek_core_device/_private/server/
+-rw-r--r--   0 root         (0) root         (0)     4271 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/server/DeviceApi.py
+-rw-r--r--   0 root         (0) root         (0)     5495 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/server/LogicEntryHook.py
+-rw-r--r--   0 root         (0) root         (0)      532 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/server/TupleActionProcessor.py
+-rw-r--r--   0 root         (0) root         (0)     3688 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/server/TupleDataObservable.py
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/server/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.720070 peek-core-device-3.4.5/peek_core_device/_private/server/admin_backend/
+-rw-r--r--   0 root         (0) root         (0)     2170 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/server/admin_backend/SettingPropertyHandler.py
+-rw-r--r--   0 root         (0) root         (0)      318 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/server/admin_backend/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.720070 peek-core-device-3.4.5/peek_core_device/_private/server/controller/
+-rw-r--r--   0 root         (0) root         (0)     2786 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/server/controller/BandwidthResultController.py
+-rw-r--r--   0 root         (0) root         (0)     4319 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/server/controller/DeviceStatusController.py
+-rw-r--r--   0 root         (0) root         (0)     4352 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/server/controller/EnrollmentController.py
+-rw-r--r--   0 root         (0) root         (0)     5391 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/server/controller/GpsController.py
+-rw-r--r--   0 root         (0) root         (0)     3978 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/server/controller/MainController.py
+-rw-r--r--   0 root         (0) root         (0)     3238 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/server/controller/NotifierController.py
+-rw-r--r--   0 root         (0) root         (0)     3701 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/server/controller/OfflineCacheController.py
+-rw-r--r--   0 root         (0) root         (0)     5731 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/server/controller/UpdateController.py
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/server/controller/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.721070 peek-core-device-3.4.5/peek_core_device/_private/server/tuple_providers/
+-rw-r--r--   0 root         (0) root         (0)     2984 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/server/tuple_providers/ClientSettingsTupleProvider.py
+-rw-r--r--   0 root         (0) root         (0)     1240 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/server/tuple_providers/DeviceGpsLocationTupleProvider.py
+-rw-r--r--   0 root         (0) root         (0)     3152 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/server/tuple_providers/DeviceInfoTableTupleProvider.py
+-rw-r--r--   0 root         (0) root         (0)     3001 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/server/tuple_providers/DeviceInfoTupleProvider.py
+-rw-r--r--   0 root         (0) root         (0)     2556 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/server/tuple_providers/DeviceUpdateTupleProvider.py
+-rw-r--r--   0 root         (0) root         (0)     1348 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/server/tuple_providers/OfflineCacheCombinedStatusTupleProvider.py
+-rw-r--r--   0 root         (0) root         (0)     1692 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/server/tuple_providers/OfflineCacheSettingTupleProvider.py
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/server/tuple_providers/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.721070 peek-core-device-3.4.5/peek_core_device/_private/server/update_resources/
+-rw-r--r--   0 root         (0) root         (0)     2350 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/server/update_resources/DeviceUpdateUploadResource.py
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/server/update_resources/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.721070 peek-core-device-3.4.5/peek_core_device/_private/storage/
+-rw-r--r--   0 root         (0) root         (0)      711 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/storage/DeclarativeBase.py
+-rw-r--r--   0 root         (0) root         (0)     3713 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/storage/DeviceInfoTable.py
+-rw-r--r--   0 root         (0) root         (0)     1431 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/storage/DeviceUpdateTuple.py
+-rw-r--r--   0 root         (0) root         (0)     1005 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/storage/GpsLocationHistoryTable.py
+-rw-r--r--   0 root         (0) root         (0)     1242 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/storage/GpsLocationTable.py
+-rw-r--r--   0 root         (0) root         (0)     9117 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/storage/Setting.py
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/storage/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.722070 peek-core-device-3.4.5/peek_core_device/_private/tuples/
+-rw-r--r--   0 root         (0) root         (0)      777 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/tuples/AlterDeviceUpdateAction.py
+-rw-r--r--   0 root         (0) root         (0)      509 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/tuples/BandwidthTestResultTuple.py
+-rw-r--r--   0 root         (0) root         (0)      342 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/tuples/BandwidthTestTuple.py
+-rw-r--r--   0 root         (0) root         (0)      812 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/tuples/ClientSettingsTuple.py
+-rw-r--r--   0 root         (0) root         (0)      602 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/tuples/CreateDeviceUpdateAction.py
+-rw-r--r--   0 root         (0) root         (0)      414 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/tuples/DeviceBackgroundStateTupleAction.py
+-rw-r--r--   0 root         (0) root         (0)      545 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/tuples/DeviceCacheStatusTuple.py
+-rw-r--r--   0 root         (0) root         (0)      446 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/tuples/EnrolDeviceAction.py
+-rw-r--r--   0 root         (0) root         (0)      847 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/tuples/OfflineCacheCombinedStatusTuple.py
+-rw-r--r--   0 root         (0) root         (0)      691 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/tuples/OfflineCacheLoaderStatusTuple.py
+-rw-r--r--   0 root         (0) root         (0)      447 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/tuples/OfflineCacheSettingTuple.py
+-rw-r--r--   0 root         (0) root         (0)      890 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/tuples/OfflineCacheStatusAction.py
+-rw-r--r--   0 root         (0) root         (0)     1459 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/tuples/OfflineCacheStatusTuple.py
+-rw-r--r--   0 root         (0) root         (0)      506 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/tuples/UpdateAppliedAction.py
+-rw-r--r--   0 root         (0) root         (0)      590 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/tuples/UpdateDeviceGpsLocationTupleAction.py
+-rw-r--r--   0 root         (0) root         (0)      620 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/tuples/UpdateDeviceOnlineAction.py
+-rw-r--r--   0 root         (0) root         (0)      587 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/tuples/UpdateEnrollmentAction.py
+-rw-r--r--   0 root         (0) root         (0)      588 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/tuples/UpdateOfflineCacheSettingAction.py
+-rw-r--r--   0 root         (0) root         (0)      637 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/tuples/WebClientVortexDetailsTuple.py
+-rw-r--r--   0 root         (0) root         (0)      347 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/_private/tuples/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.722070 peek-core-device-3.4.5/peek_core_device/admin-doc/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.722070 peek-core-device-3.4.5/peek_core_device/admin-doc/admin_tasks/
+-rw-r--r--   0 root         (0) root         (0)    64585 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/admin-doc/admin_tasks/admin_task_devices.png
+-rw-r--r--   0 root         (0) root         (0)     1475 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/admin-doc/admin_tasks/admin_tasks.rst
+-rw-r--r--   0 root         (0) root         (0)    62597 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/admin-doc/admin_tasks/device_search.png
+-rw-r--r--   0 root         (0) root         (0)    25072 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/admin-doc/admin_tasks/offline_cache_info.png
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.723070 peek-core-device-3.4.5/peek_core_device/admin-doc/general_settings/
+-rw-r--r--   0 root         (0) root         (0)   202788 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/admin-doc/general_settings/general_settings.png
+-rw-r--r--   0 root         (0) root         (0)     1417 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/admin-doc/general_settings/general_settings.rst
+-rw-r--r--   0 root         (0) root         (0)      433 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/admin-doc/index.rst
+-rw-r--r--   0 root         (0) root         (0)      515 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/admin-doc/overview.rst
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.723070 peek-core-device-3.4.5/peek_core_device/both-doc/
+-rw-r--r--   0 root         (0) root         (0)      848 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/both-doc/index.rst
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.723070 peek-core-device-3.4.5/peek_core_device/plugin-module/
+-rw-r--r--   0 root         (0) root         (0)      552 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/DeviceGpsLocationTuple.ts
+-rw-r--r--   0 root         (0) root         (0)     2952 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/DeviceInfoTuple.ts
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.724070 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/
+-rw-r--r--   0 root         (0) root         (0)      333 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/PluginNames.ts
+-rw-r--r--   0 root         (0) root         (0)     1051 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/device-background.service.ts
+-rw-r--r--   0 root         (0) root         (0)     8222 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/device-bandwidth-test.service.ts
+-rw-r--r--   0 root         (0) root         (0)      767 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/device-loading.module.ts
+-rw-r--r--   0 root         (0) root         (0)     1180 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/device-nav.service.ts
+-rw-r--r--   0 root         (0) root         (0)     1024 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/device-online.service.ts
+-rw-r--r--   0 root         (0) root         (0)     7060 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/device-server.service.ts
+-rw-r--r--   0 root         (0) root         (0)     2937 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/device-tuple.service.ts
+-rw-r--r--   0 root         (0) root         (0)     5938 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/device-update.service.ts
+-rw-r--r--   0 root         (0) root         (0)      592 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/device-update.service.web.ts
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.724070 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/gps/
+-rw-r--r--   0 root         (0) root         (0)      711 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/gps/GpsLocationUpdateTupleAction.ts
+-rw-r--r--   0 root         (0) root         (0)     6740 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/gps/private-gps-location.service.ts
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.724070 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/hardware-info/
+-rw-r--r--   0 root         (0) root         (0)     2318 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/hardware-info/hardware-info.ts
+-rw-r--r--   0 root         (0) root         (0)       30 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/hardware-info/is-field.dweb.ts
+-rw-r--r--   0 root         (0) root         (0)       29 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/hardware-info/is-field.mweb.ts
+-rw-r--r--   0 root         (0) root         (0)     1255 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/index.ts
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.725070 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/tuples/
+-rw-r--r--   0 root         (0) root         (0)      497 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/tuples/BandwidthTestResultTuple.ts
+-rw-r--r--   0 root         (0) root         (0)      383 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/tuples/BandwidthTestTuple.ts
+-rw-r--r--   0 root         (0) root         (0)      789 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/tuples/ClientSettingsTuple.ts
+-rw-r--r--   0 root         (0) root         (0)      451 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/tuples/DeviceBackgroundStateTupleAction.ts
+-rw-r--r--   0 root         (0) root         (0)      662 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/tuples/DeviceUpdateLocalValuesTuple.ts
+-rw-r--r--   0 root         (0) root         (0)      551 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/tuples/DeviceUpdateTuple.ts
+-rw-r--r--   0 root         (0) root         (0)      438 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/tuples/EnrolDeviceAction.ts
+-rw-r--r--   0 root         (0) root         (0)      670 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/tuples/OfflineCacheCombinedStatusTuple.ts
+-rw-r--r--   0 root         (0) root         (0)      391 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/tuples/OfflineCacheSettingTuple.ts
+-rw-r--r--   0 root         (0) root         (0)      477 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/tuples/OfflineCacheStatusAction.ts
+-rw-r--r--   0 root         (0) root         (0)     3198 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/tuples/OfflineCacheStatusTuple.ts
+-rw-r--r--   0 root         (0) root         (0)      470 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/tuples/UpdateAppliedAction.ts
+-rw-r--r--   0 root         (0) root         (0)      641 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/tuples/UpdateDeviceOnlineAction.ts
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.725070 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/tuples/admin/
+-rw-r--r--   0 root         (0) root         (0)      523 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/tuples/admin/AlterDeviceUpdateAction.ts
+-rw-r--r--   0 root         (0) root         (0)      467 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/tuples/admin/CreateDeviceUpdateAction.ts
+-rw-r--r--   0 root         (0) root         (0)      572 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/tuples/admin/SettingPropertyTuple.ts
+-rw-r--r--   0 root         (0) root         (0)      455 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/tuples/admin/UpdateEnrollmentAction.ts
+-rw-r--r--   0 root         (0) root         (0)      468 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/tuples/offline-cache-local-saved-state-tuple.ts
+-rw-r--r--   0 root         (0) root         (0)      152 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/tuples/server-info-tuple-defaults.ts
+-rw-r--r--   0 root         (0) root         (0)      731 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/_private/tuples/server-info-tuple.ts
+-rw-r--r--   0 root         (0) root         (0)     2337 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/device-enrolled.guard.ts
+-rw-r--r--   0 root         (0) root         (0)     3849 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/device-enrolment.service.ts
+-rw-r--r--   0 root         (0) root         (0)    27488 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/device-offline-cache.service.ts
+-rw-r--r--   0 root         (0) root         (0)     1553 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/device-status.service.ts
+-rw-r--r--   0 root         (0) root         (0)      356 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/gps-location.service.ts
+-rw-r--r--   0 root         (0) root         (0)      546 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/index.ts
+-rw-r--r--   0 root         (0) root         (0)      301 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/package.json
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.725070 peek-core-device-3.4.5/peek_core_device/plugin-module/tuples/
+-rw-r--r--   0 root         (0) root         (0)     1344 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/plugin-module/tuples/OfflineCacheLoaderStatusTuple.ts
+-rw-r--r--   0 root         (0) root         (0)     6342 2023-06-28 07:26:13.000000 peek-core-device-3.4.5/peek_core_device/plugin_package.json
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.725070 peek-core-device-3.4.5/peek_core_device/server/
+-rw-r--r--   0 root         (0) root         (0)     2404 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/server/DeviceApiABC.py
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/server/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.726070 peek-core-device-3.4.5/peek_core_device/tuples/
+-rw-r--r--   0 root         (0) root         (0)     1312 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/tuples/DeviceDetailTuple.py
+-rw-r--r--   0 root         (0) root         (0)      494 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/tuples/DeviceGpsLocationTuple.py
+-rw-r--r--   0 root         (0) root         (0)     1479 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/tuples/DeviceInfoTuple.py
+-rw-r--r--   0 root         (0) root         (0)      814 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/tuples/DeviceStatusTuple.py
+-rw-r--r--   0 root         (0) root         (0)      344 2023-06-28 07:25:23.000000 peek-core-device-3.4.5/peek_core_device/tuples/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:26:13.716070 peek-core-device-3.4.5/peek_core_device.egg-info/
+-rw-r--r--   0 root         (0) root         (0)      407 2023-06-28 07:26:13.000000 peek-core-device-3.4.5/peek_core_device.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)    11697 2023-06-28 07:26:13.000000 peek-core-device-3.4.5/peek_core_device.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 07:26:13.000000 peek-core-device-3.4.5/peek_core_device.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)       32 2023-06-28 07:26:13.000000 peek-core-device-3.4.5/peek_core_device.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)       17 2023-06-28 07:26:13.000000 peek-core-device-3.4.5/peek_core_device.egg-info/top_level.txt
+-rw-r--r--   0 root         (0) root         (0)       38 2023-06-28 07:26:13.727070 peek-core-device-3.4.5/setup.cfg
+-rw-r--r--   0 root         (0) root         (0)     2547 2023-06-28 07:26:13.000000 peek-core-device-3.4.5/setup.py
```

### Comparing `peek-core-device-3.4.4/peek_core_device/__init__.py` & `peek-core-device-3.4.5/peek_core_device/__init__.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 from typing import Type
 
 from peek_plugin_base.client.PluginClientEntryHookABC import \
     PluginClientEntryHookABC
 from peek_plugin_base.server.PluginLogicEntryHookABC import \
     PluginLogicEntryHookABC
 
-__version__ = '3.4.4'
+__version__ = '3.4.5'
 
 
 def peekLogicEntryHook() -> Type[PluginLogicEntryHookABC]:
     from ._private.server.LogicEntryHook import LogicEntryHook
 
     return LogicEntryHook
```

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/admin-app/device-cache-status/device-cache-status.component.html` & `peek-core-device-3.4.5/peek_core_device/_private/admin-app/device-cache-status/device-cache-status.component.html`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/admin-app/device-cache-status/device-cache-status.component.ts` & `peek-core-device-3.4.5/peek_core_device/_private/admin-app/device-cache-status/device-cache-status.component.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/admin-app/device-info-table/device-info.component.html` & `peek-core-device-3.4.5/peek_core_device/_private/admin-app/device-info-table/device-info.component.html`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/admin-app/device-info-table/device-info.component.ts` & `peek-core-device-3.4.5/peek_core_device/_private/admin-app/device-info-table/device-info.component.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/admin-app/device-update-table/device-update.component.html` & `peek-core-device-3.4.5/peek_core_device/_private/admin-app/device-update-table/device-update.component.html`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/admin-app/device-update-table/device-update.component.ts` & `peek-core-device-3.4.5/peek_core_device/_private/admin-app/device-update-table/device-update.component.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/admin-app/device.component.html` & `peek-core-device-3.4.5/peek_core_device/_private/admin-app/device.component.html`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/admin-app/device.module.ts` & `peek-core-device-3.4.5/peek_core_device/_private/admin-app/device.module.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/admin-app/edit-setting-table/edit.component.html` & `peek-core-device-3.4.5/peek_core_device/_private/admin-app/edit-setting-table/edit.component.html`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/admin-app/edit-setting-table/edit.component.ts` & `peek-core-device-3.4.5/peek_core_device/_private/admin-app/edit-setting-table/edit.component.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/admin-app/tuples/DeviceCacheStatusTuple.ts` & `peek-core-device-3.4.5/peek_core_device/_private/admin-app/tuples/DeviceCacheStatusTuple.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/admin-app/tuples/DeviceInfoTable.ts` & `peek-core-device-3.4.5/peek_core_device/_private/admin-app/tuples/DeviceInfoTable.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/admin-app/upload-device-update/upload-device-update.component.html` & `peek-core-device-3.4.5/peek_core_device/_private/admin-app/upload-device-update/upload-device-update.component.html`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/admin-app/upload-device-update/upload-device-update.component.ts` & `peek-core-device-3.4.5/peek_core_device/_private/admin-app/upload-device-update/upload-device-update.component.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/alembic/script.py.mako` & `peek-core-device-3.4.5/peek_core_device/_private/alembic/script.py.mako`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/alembic/versions/02f9305f9e7f_added_gps_tracking.py` & `peek-core-device-3.4.5/peek_core_device/_private/alembic/versions/02f9305f9e7f_added_gps_tracking.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/alembic/versions/2561b7732a6c_gps_devicetoken_on_cascade.py` & `peek-core-device-3.4.5/peek_core_device/_private/alembic/versions/2561b7732a6c_gps_devicetoken_on_cascade.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/alembic/versions/4b0d6309e556_add_offline_cache_enable.py` & `peek-core-device-3.4.5/peek_core_device/_private/alembic/versions/4b0d6309e556_add_offline_cache_enable.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/alembic/versions/5dd43ff7ea8e_added_filesize_to_update_tuple.py` & `peek-core-device-3.4.5/peek_core_device/_private/alembic/versions/5dd43ff7ea8e_added_filesize_to_update_tuple.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/alembic/versions/6bf6ecef3108_timezone_aware.py` & `peek-core-device-3.4.5/peek_core_device/_private/alembic/versions/6bf6ecef3108_timezone_aware.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/alembic/versions/7f628c121c4c_replaced_isonline_with_devicestatus.py` & `peek-core-device-3.4.5/peek_core_device/_private/alembic/versions/7f628c121c4c_replaced_isonline_with_devicestatus.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/alembic/versions/97d44e5aeb18_add_lastbandwidthmetric.py` & `peek-core-device-3.4.5/peek_core_device/_private/alembic/versions/97d44e5aeb18_add_lastbandwidthmetric.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/alembic/versions/d94277dd8aca_initial_table_creation.py` & `peek-core-device-3.4.5/peek_core_device/_private/alembic/versions/d94277dd8aca_initial_table_creation.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/both-app/connect/connect.component.ts` & `peek-core-device-3.4.5/peek_core_device/_private/both-app/connect/connect.component.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/both-app/connect/connect.component.web.html` & `peek-core-device-3.4.5/peek_core_device/_private/both-app/connect/connect.component.web.html`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/both-app/connecting/connecting.component.ts` & `peek-core-device-3.4.5/peek_core_device/_private/both-app/connecting/connecting.component.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/both-app/connecting/connecting.component.web.html` & `peek-core-device-3.4.5/peek_core_device/_private/both-app/connecting/connecting.component.web.html`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/both-app/device.module.ts` & `peek-core-device-3.4.5/peek_core_device/_private/both-app/device.module.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/both-app/device.routes.ts` & `peek-core-device-3.4.5/peek_core_device/_private/both-app/device.routes.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/both-app/enroll/enroll.component.ts` & `peek-core-device-3.4.5/peek_core_device/_private/both-app/enroll/enroll.component.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/both-app/enroll/enroll.component.web.html` & `peek-core-device-3.4.5/peek_core_device/_private/both-app/enroll/enroll.component.web.html`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/both-app/enrolling/enrolling.component.ts` & `peek-core-device-3.4.5/peek_core_device/_private/both-app/enrolling/enrolling.component.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/both-app/enrolling/enrolling.component.web.html` & `peek-core-device-3.4.5/peek_core_device/_private/both-app/enrolling/enrolling.component.web.html`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/both-app/loading/loading.component.ts` & `peek-core-device-3.4.5/peek_core_device/_private/both-app/loading/loading.component.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/both-cfg/connect/connect.component.ts` & `peek-core-device-3.4.5/peek_core_device/_private/both-cfg/connect/connect.component.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/both-cfg/core-device-cfg.component.web.html` & `peek-core-device-3.4.5/peek_core_device/_private/both-cfg/core-device-cfg.component.web.html`

 * *Files 11% similar despite different names*

```diff
@@ -40,8 +40,22 @@
         <p>
             Load Progress : <b>{{ status.percentCompleteString }}</b>, loading
             <b>{{ status.loadingQueueCount }}</b> chunks, server has
             <b>{{ status.totalLoadedCount || "?" }}</b> chunks, Has Completed
             Once : <b>{{status.initialFullLoadComplete }}</b><br />
         </p>
     </div>
+
+    <div
+        *ngIf="isForceCacheStartButtonEnabled"
+        class="peek-information-section"
+    >
+        <button
+            nz-button
+            nzType="dashed"
+            nzDanger
+            (click)="forceCacheStartClicked()"
+        >
+            Force Cache Start
+        </button>
+    </div>
 </div>
```

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/both-cfg/core-device-cfg.module.ts` & `peek-core-device-3.4.5/peek_core_device/_private/both-cfg/core-device-cfg.module.ts`

 * *Files 4% similar despite different names*

```diff
@@ -2,14 +2,15 @@
 import { NgModule } from "@angular/core";
 import { RouterModule, Routes } from "@angular/router";
 import { FormsModule } from "@angular/forms";
 import { HttpClientModule } from "@angular/common/http";
 import { NzIconModule } from "ng-zorro-antd/icon";
 import { CoreDeviceCfgComponent } from "./core-device-cfg.component";
 import { ConnectComponent } from "./connect/connect.component";
+import { NzButtonModule } from "ng-zorro-antd/button";
 import {
     TupleActionPushNameService,
     TupleActionPushOfflineService,
     TupleActionPushService,
     TupleDataObservableNameService,
     TupleDataObserverService,
     TupleDataOfflineObserverService,
@@ -56,14 +57,15 @@
 // When it first loads, it will look up the routes and then select the component to load.
 @NgModule({
     imports: [
         CommonModule,
         RouterModule.forChild(pluginRoutes),
         FormsModule,
         NzIconModule,
+        NzButtonModule,
         HttpClientModule,
     ],
     exports: [],
     providers: [
         TupleActionPushOfflineService,
         TupleActionPushService,
         {
```

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/client/ClientEntryHook.py` & `peek-core-device-3.4.5/peek_core_device/_private/client/ClientEntryHook.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/client/DeviceTupleDataObservableProxy.py` & `peek-core-device-3.4.5/peek_core_device/_private/client/DeviceTupleDataObservableProxy.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/client/UpdateDownloadHandler.py` & `peek-core-device-3.4.5/peek_core_device/_private/client/UpdateDownloadHandler.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/client/controllers/BandwidthTestController.py` & `peek-core-device-3.4.5/peek_core_device/_private/client/controllers/BandwidthTestController.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/client/controllers/DeviceOnlineController.py` & `peek-core-device-3.4.5/peek_core_device/_private/client/controllers/DeviceOnlineController.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/server/DeviceApi.py` & `peek-core-device-3.4.5/peek_core_device/_private/server/DeviceApi.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/server/LogicEntryHook.py` & `peek-core-device-3.4.5/peek_core_device/_private/server/LogicEntryHook.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/server/TupleActionProcessor.py` & `peek-core-device-3.4.5/peek_core_device/_private/server/TupleActionProcessor.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/server/TupleDataObservable.py` & `peek-core-device-3.4.5/peek_core_device/_private/server/TupleDataObservable.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/server/admin_backend/SettingPropertyHandler.py` & `peek-core-device-3.4.5/peek_core_device/_private/server/admin_backend/SettingPropertyHandler.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/server/controller/BandwidthResultController.py` & `peek-core-device-3.4.5/peek_core_device/_private/server/controller/BandwidthResultController.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/server/controller/DeviceStatusController.py` & `peek-core-device-3.4.5/peek_core_device/_private/server/controller/DeviceStatusController.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/server/controller/EnrollmentController.py` & `peek-core-device-3.4.5/peek_core_device/_private/server/controller/EnrollmentController.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/server/controller/GpsController.py` & `peek-core-device-3.4.5/peek_core_device/_private/server/controller/GpsController.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/server/controller/MainController.py` & `peek-core-device-3.4.5/peek_core_device/_private/server/controller/MainController.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/server/controller/NotifierController.py` & `peek-core-device-3.4.5/peek_core_device/_private/server/controller/NotifierController.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/server/controller/OfflineCacheController.py` & `peek-core-device-3.4.5/peek_core_device/_private/server/controller/OfflineCacheController.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/server/controller/UpdateController.py` & `peek-core-device-3.4.5/peek_core_device/_private/server/controller/UpdateController.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/server/tuple_providers/ClientSettingsTupleProvider.py` & `peek-core-device-3.4.5/peek_core_device/_private/server/tuple_providers/ClientSettingsTupleProvider.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/server/tuple_providers/DeviceGpsLocationTupleProvider.py` & `peek-core-device-3.4.5/peek_core_device/_private/server/tuple_providers/DeviceGpsLocationTupleProvider.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/server/tuple_providers/DeviceInfoTableTupleProvider.py` & `peek-core-device-3.4.5/peek_core_device/_private/server/tuple_providers/DeviceInfoTableTupleProvider.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/server/tuple_providers/DeviceInfoTupleProvider.py` & `peek-core-device-3.4.5/peek_core_device/_private/server/tuple_providers/DeviceInfoTupleProvider.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/server/tuple_providers/DeviceUpdateTupleProvider.py` & `peek-core-device-3.4.5/peek_core_device/_private/server/tuple_providers/DeviceUpdateTupleProvider.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/server/tuple_providers/OfflineCacheCombinedStatusTupleProvider.py` & `peek-core-device-3.4.5/peek_core_device/_private/server/tuple_providers/OfflineCacheCombinedStatusTupleProvider.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/server/tuple_providers/OfflineCacheSettingTupleProvider.py` & `peek-core-device-3.4.5/peek_core_device/_private/server/tuple_providers/OfflineCacheSettingTupleProvider.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/server/update_resources/DeviceUpdateUploadResource.py` & `peek-core-device-3.4.5/peek_core_device/_private/server/update_resources/DeviceUpdateUploadResource.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/storage/DeclarativeBase.py` & `peek-core-device-3.4.5/peek_core_device/_private/storage/DeclarativeBase.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/storage/DeviceInfoTable.py` & `peek-core-device-3.4.5/peek_core_device/_private/storage/DeviceInfoTable.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/storage/DeviceUpdateTuple.py` & `peek-core-device-3.4.5/peek_core_device/_private/storage/DeviceUpdateTuple.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/storage/GpsLocationHistoryTable.py` & `peek-core-device-3.4.5/peek_core_device/_private/storage/GpsLocationHistoryTable.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/storage/GpsLocationTable.py` & `peek-core-device-3.4.5/peek_core_device/_private/storage/GpsLocationTable.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/storage/Setting.py` & `peek-core-device-3.4.5/peek_core_device/_private/storage/Setting.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/tuples/AlterDeviceUpdateAction.py` & `peek-core-device-3.4.5/peek_core_device/_private/tuples/AlterDeviceUpdateAction.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/tuples/ClientSettingsTuple.py` & `peek-core-device-3.4.5/peek_core_device/_private/tuples/ClientSettingsTuple.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/tuples/CreateDeviceUpdateAction.py` & `peek-core-device-3.4.5/peek_core_device/_private/tuples/CreateDeviceUpdateAction.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/tuples/DeviceCacheStatusTuple.py` & `peek-core-device-3.4.5/peek_core_device/_private/tuples/DeviceCacheStatusTuple.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/tuples/OfflineCacheCombinedStatusTuple.py` & `peek-core-device-3.4.5/peek_core_device/_private/tuples/OfflineCacheCombinedStatusTuple.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/tuples/OfflineCacheLoaderStatusTuple.py` & `peek-core-device-3.4.5/peek_core_device/_private/tuples/OfflineCacheLoaderStatusTuple.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/tuples/OfflineCacheStatusAction.py` & `peek-core-device-3.4.5/peek_core_device/_private/tuples/OfflineCacheStatusAction.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/tuples/OfflineCacheStatusTuple.py` & `peek-core-device-3.4.5/peek_core_device/_private/tuples/OfflineCacheStatusTuple.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/tuples/UpdateDeviceGpsLocationTupleAction.py` & `peek-core-device-3.4.5/peek_core_device/_private/tuples/UpdateDeviceGpsLocationTupleAction.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/tuples/UpdateDeviceOnlineAction.py` & `peek-core-device-3.4.5/peek_core_device/_private/tuples/UpdateDeviceOnlineAction.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/tuples/UpdateEnrollmentAction.py` & `peek-core-device-3.4.5/peek_core_device/_private/tuples/UpdateEnrollmentAction.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/tuples/UpdateOfflineCacheSettingAction.py` & `peek-core-device-3.4.5/peek_core_device/_private/tuples/UpdateOfflineCacheSettingAction.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/_private/tuples/WebClientVortexDetailsTuple.py` & `peek-core-device-3.4.5/peek_core_device/_private/tuples/WebClientVortexDetailsTuple.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/admin-doc/admin_tasks/admin_task_devices.png` & `peek-core-device-3.4.5/peek_core_device/admin-doc/admin_tasks/admin_task_devices.png`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/admin-doc/admin_tasks/admin_tasks.rst` & `peek-core-device-3.4.5/peek_core_device/admin-doc/admin_tasks/admin_tasks.rst`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/admin-doc/admin_tasks/device_search.png` & `peek-core-device-3.4.5/peek_core_device/admin-doc/admin_tasks/device_search.png`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/admin-doc/admin_tasks/offline_cache_info.png` & `peek-core-device-3.4.5/peek_core_device/admin-doc/admin_tasks/offline_cache_info.png`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/admin-doc/general_settings/general_settings.png` & `peek-core-device-3.4.5/peek_core_device/admin-doc/general_settings/general_settings.png`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/admin-doc/general_settings/general_settings.rst` & `peek-core-device-3.4.5/peek_core_device/admin-doc/general_settings/general_settings.rst`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/admin-doc/overview.rst` & `peek-core-device-3.4.5/peek_core_device/admin-doc/overview.rst`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/both-doc/index.rst` & `peek-core-device-3.4.5/peek_core_device/both-doc/index.rst`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/plugin-module/DeviceGpsLocationTuple.ts` & `peek-core-device-3.4.5/peek_core_device/plugin-module/DeviceGpsLocationTuple.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/plugin-module/DeviceInfoTuple.ts` & `peek-core-device-3.4.5/peek_core_device/plugin-module/DeviceInfoTuple.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/plugin-module/_private/device-background.service.ts` & `peek-core-device-3.4.5/peek_core_device/plugin-module/_private/device-background.service.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/plugin-module/_private/device-bandwidth-test.service.ts` & `peek-core-device-3.4.5/peek_core_device/plugin-module/_private/device-bandwidth-test.service.ts`

 * *Files 3% similar despite different names*

```diff
@@ -52,14 +52,19 @@
     constructor(
         private vortexService: VortexService,
         private vortexStatusService: VortexStatusService,
         private tupleService: DeviceTupleService,
         private enrolmentService: DeviceEnrolmentService
     ) {
         super();
+        this.status$.next({
+            isSlowNetwork: this._isSlowNetwork,
+            lastMetric: this._lastMetric,
+        });
+
         this.bandwidthTestEndpoint = vortexService.createEndpoint(
             this,
             deviceBandwidthTestFilt,
             false
         );
 
         const ts = new TupleSelector(ClientSettingsTuple.tupleName, {});
@@ -127,37 +132,39 @@
         return this._lastMetric;
     }
 
     get isTestRunning(): boolean {
         return this._testRunning;
     }
 
-    startTest(): void {
+    startTest(): boolean {
         if (this._testRunning) {
             console.log("Subsequent call to start bandwidth test ignored");
-            return;
+            return false;
         }
         if (this._offlineCachingRunning) {
             console.log(
                 "Offline cache test skipped while offline caching is" +
                     " in progres"
             );
-            return;
+            return false;
         }
         console.log("Starting bandwidth test");
 
         this._testRunning = true;
 
         this._performBandwidthTest()
             .catch((e) => console.log(`ERROR _performBandwidthTest: ${e}`))
             .then(() => {
                 setTimeout(() => {
                     this._testRunning = false;
                 }, this.CHECK_BACKOFF_SECONDS * 1000);
             });
+
+        return true;
     }
 
     private _performBandwidthTest(): Promise<number | null> {
         if (this.enrolmentService.deviceInfo == null)
             throw new Error("We need a deviceInfo tuple set first");
 
         const startPoll = new Date().getTime();
```

### Comparing `peek-core-device-3.4.4/peek_core_device/plugin-module/_private/device-loading.module.ts` & `peek-core-device-3.4.5/peek_core_device/plugin-module/_private/device-loading.module.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/plugin-module/_private/device-nav.service.ts` & `peek-core-device-3.4.5/peek_core_device/plugin-module/_private/device-nav.service.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/plugin-module/_private/device-online.service.ts` & `peek-core-device-3.4.5/peek_core_device/plugin-module/_private/device-online.service.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/plugin-module/_private/device-server.service.ts` & `peek-core-device-3.4.5/peek_core_device/plugin-module/_private/device-server.service.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/plugin-module/_private/device-tuple.service.ts` & `peek-core-device-3.4.5/peek_core_device/plugin-module/_private/device-tuple.service.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/plugin-module/_private/device-update.service.ts` & `peek-core-device-3.4.5/peek_core_device/plugin-module/_private/device-update.service.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/plugin-module/_private/device-update.service.web.ts` & `peek-core-device-3.4.5/peek_core_device/plugin-module/_private/device-update.service.web.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/plugin-module/_private/gps/GpsLocationUpdateTupleAction.ts` & `peek-core-device-3.4.5/peek_core_device/plugin-module/_private/gps/GpsLocationUpdateTupleAction.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/plugin-module/_private/gps/private-gps-location.service.ts` & `peek-core-device-3.4.5/peek_core_device/plugin-module/_private/gps/private-gps-location.service.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/plugin-module/_private/hardware-info/hardware-info.ts` & `peek-core-device-3.4.5/peek_core_device/plugin-module/_private/hardware-info/hardware-info.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/plugin-module/_private/index.ts` & `peek-core-device-3.4.5/peek_core_device/plugin-module/_private/index.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/plugin-module/_private/tuples/ClientSettingsTuple.ts` & `peek-core-device-3.4.5/peek_core_device/plugin-module/_private/tuples/ClientSettingsTuple.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/plugin-module/_private/tuples/DeviceUpdateLocalValuesTuple.ts` & `peek-core-device-3.4.5/peek_core_device/plugin-module/_private/tuples/DeviceUpdateLocalValuesTuple.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/plugin-module/_private/tuples/DeviceUpdateTuple.ts` & `peek-core-device-3.4.5/peek_core_device/plugin-module/_private/tuples/DeviceUpdateTuple.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/plugin-module/_private/tuples/OfflineCacheCombinedStatusTuple.ts` & `peek-core-device-3.4.5/peek_core_device/plugin-module/_private/tuples/OfflineCacheCombinedStatusTuple.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/plugin-module/_private/tuples/OfflineCacheStatusTuple.ts` & `peek-core-device-3.4.5/peek_core_device/plugin-module/_private/tuples/OfflineCacheStatusTuple.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/plugin-module/_private/tuples/UpdateDeviceOnlineAction.ts` & `peek-core-device-3.4.5/peek_core_device/plugin-module/_private/tuples/UpdateDeviceOnlineAction.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/plugin-module/_private/tuples/admin/AlterDeviceUpdateAction.ts` & `peek-core-device-3.4.5/peek_core_device/plugin-module/_private/tuples/admin/AlterDeviceUpdateAction.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/plugin-module/_private/tuples/admin/SettingPropertyTuple.ts` & `peek-core-device-3.4.5/peek_core_device/plugin-module/_private/tuples/admin/SettingPropertyTuple.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/plugin-module/_private/tuples/server-info-tuple.ts` & `peek-core-device-3.4.5/peek_core_device/plugin-module/_private/tuples/server-info-tuple.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/plugin-module/device-enrolled.guard.ts` & `peek-core-device-3.4.5/peek_core_device/plugin-module/device-enrolled.guard.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/plugin-module/device-enrolment.service.ts` & `peek-core-device-3.4.5/peek_core_device/plugin-module/device-enrolment.service.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/plugin-module/device-offline-cache.service.ts` & `peek-core-device-3.4.5/peek_core_device/plugin-module/device-offline-cache.service.ts`

 * *Files 12% similar despite different names*

```diff
@@ -1,31 +1,32 @@
 import { BehaviorSubject, Observable, Subject } from "rxjs";
 import { Injectable } from "@angular/core";
 import { filter, first, takeUntil } from "rxjs/operators";
 import { Network } from "@capacitor/network";
 
 import {
     NgLifeCycleEvents,
+    Payload,
     TupleSelector,
     VortexService,
     VortexStatusService,
-    Payload,
 } from "@synerty/vortexjs";
 import { ClientSettingsTuple, DeviceTupleService } from "./_private";
 import { OfflineCacheSettingTuple } from "./_private/tuples/OfflineCacheSettingTuple";
 import { OfflineCacheLoaderStatusTuple } from "./tuples/OfflineCacheLoaderStatusTuple";
 import { DeviceEnrolmentService } from "./device-enrolment.service";
 import { DeviceInfoTuple } from "./DeviceInfoTuple";
 import { DeviceBandwidthTestService } from "./_private/device-bandwidth-test.service";
 import {
     OfflineCacheStatusTuple,
     StateMachineE,
 } from "./_private/tuples/OfflineCacheStatusTuple";
 import { OfflineCacheStatusAction } from "./_private/tuples/OfflineCacheStatusAction";
 import { OfflineCacheCombinedStatusTuple } from "@peek/peek_core_device/_private/tuples/OfflineCacheCombinedStatusTuple";
+import { OfflineCacheLocalSavedStateTuple } from "@peek/peek_core_device/_private/tuples/offline-cache-local-saved-state-tuple";
 
 class Timer {
     private _startTime: Date;
 
     // Default to a year, it will never time out
     constructor(private timeoutSeconds: number = 365 * 24 * 60 * 68) {
         this._startTime = new Date();
@@ -127,14 +128,21 @@
 
     // Run every 2 to 5 minutes, so we don't overload the server
     private readonly sendStateToServerTimer = new Timer();
 
     // Make note of the last network type
     private _lastNetworkType = "";
 
+    private readonly savedStateTupleSelector = new TupleSelector(
+        OfflineCacheLocalSavedStateTuple.tupleName,
+        {}
+    );
+
+    private savedStateTuple: OfflineCacheLocalSavedStateTuple | null = null;
+
     constructor(
         private vortexService: VortexService,
         private vortexStatusService: VortexStatusService,
         private tupleService: DeviceTupleService,
         private enrolmentService: DeviceEnrolmentService,
         private deviceBandwidthTestService: DeviceBandwidthTestService
     ) {
@@ -164,14 +172,70 @@
             if (!["wifi", "cellular"].includes(status.connectionType)) return;
 
             if (this._lastNetworkType !== status.connectionType) {
                 this._lastNetworkType = status.connectionType;
                 this.abortRetryTimer.expire();
             }
         });
+
+        // Load the saved state
+        this.loadSavedState();
+    }
+
+    private loadSavedState() {
+        // Restore the next start date, if it exists
+        // This subscription has to stay around, or the update will fail.
+        this.tupleService.offlineObserver
+            .subscribeToTupleSelector(
+                this.savedStateTupleSelector,
+                false,
+                false,
+                true
+            )
+            .pipe(takeUntil(this.onDestroyEvent))
+            .pipe(filter((t) => (t?.length || 0) === 1))
+            .subscribe((tuples: OfflineCacheLocalSavedStateTuple[] | null) => {
+                // We need to keep the subscription, but only want to
+                // process the update once
+                if (this.savedStateTuple != null) {
+                    return;
+                }
+                this.savedStateTuple = tuples[0];
+
+                this.status.lastCachingStartDate =
+                    this.savedStateTuple.lastCachingStartDate;
+
+                this.status.lastCachingCompleteDate =
+                    this.savedStateTuple.lastCachingCompleteDate;
+
+                console.log("Offline cache, loaded save state.");
+                this.processStateLoaded();
+            });
+    }
+
+    private saveSavedState() {
+        this.savedStateTuple.lastCachingStartDate =
+            this.status.lastCachingStartDate;
+
+        this.savedStateTuple.lastCachingCompleteDate =
+            this.status.lastCachingCompleteDate;
+
+        this.tupleService.offlineObserver
+            .updateOfflineState(this.savedStateTupleSelector, [
+                this.savedStateTuple,
+            ])
+            .catch((e) =>
+                console.error(
+                    "ERROR, Failed to save" +
+                        " OfflineCacheLocalSavedStateTuple"
+                )
+            )
+            .then(() => {
+                console.log("Offline cache, saved save state.");
+            });
     }
 
     private setupAllDevicesSettingsSubscription() {
         const ts = new TupleSelector(ClientSettingsTuple.tupleName, {});
         // noinspection TypeScriptValidateJSTypes
         this.tupleService.offlineObserver
             .subscribeToTupleSelector(ts)
@@ -243,14 +307,15 @@
             });
     }
 
     private processStateLoaded(
         lastSettings: OfflineCacheSettingTuple | null = null
     ) {
         if (
+            this.savedStateTuple == null ||
             this.settings == null ||
             this.status == null ||
             this.allCientsSettingsTuple == null
         )
             return;
 
         console.assert(
@@ -315,15 +380,15 @@
                 action.lastCachingStartDate = this.status.lastCachingStartDate;
                 return this.tupleService.tupleAction.pushAction(action);
             })
             .then(() => console.log("Offline cache status sent successfully"))
             .catch((e) => console.log(`ERROR: ${e}`));
     }
 
-    private get isRunning(): boolean {
+    get isInRunStates(): boolean {
         return (
             this.status.state === StateMachineE.StartRunning ||
             this.status.state === StateMachineE.Running ||
             this.status.state === StateMachineE.StartPausing ||
             this.status.state === StateMachineE.Pausing
         );
     }
@@ -333,15 +398,15 @@
 
         this.stateMachineLock.lock();
         // console.log(`StateMachine Start = ${this.status.stateString}`);
         this.tryRunStateMachine() //
             .catch((e) => console.log(`ERROR asyncStateMachine: ${e}`))
             .then(() => {
                 this.deviceBandwidthTestService.setOfflineCachingRunning(
-                    this.isRunning
+                    this.isInRunStates
                 );
                 // console.log(`StateMachine End = ${this.status.stateString}`);
 
                 setTimeout(() => {
                     try {
                         // Don't unlock it until we're going to run next
                         this.stateMachineLock.unlock();
@@ -377,14 +442,15 @@
             }
             case StateMachineE.ScheduleNextRun: {
                 // Ensure the caching does not start before it's due to.
                 if (this.status.lastCachingStartDate != null) {
                     this.scheduledNextCacheStartTimer.reset(
                         this.status.lastCachingStartDate
                     );
+                    this.saveSavedState();
                 }
                 this.status.state = StateMachineE.Enabled;
                 break;
             }
             case StateMachineE.Enabled: {
                 // If the cache was in progress, then restart it.
                 // It must finish first, before we start
@@ -437,14 +503,15 @@
                 break;
             }
             case StateMachineE.Running: {
                 // Check if the caching is finished, if so, mark it.
                 if (this.areAllLoadersComplete()) {
                     this.status.state = StateMachineE.ScheduleNextRun;
                     this.status.setCompleted();
+                    this.saveSavedState();
                     break;
                 }
 
                 // Are we due for a pause? If so, pause it and check
                 if (this.checkBandwidthTimer.expired) {
                     this.status.state = StateMachineE.StartPausing;
                     this.status.nextState = StateMachineE.StartBandwidthTest;
@@ -495,16 +562,24 @@
                 }
 
                 this.status.state = this.status.nextState;
                 this.status.nextState = null;
                 break;
             }
             case StateMachineE.StartBandwidthTest: {
+                // If the test is already running, then wait until it's
+                // finished to start one.
+                if (this.deviceBandwidthTestService.isTestRunning) {
+                    return;
+                }
+
                 // Trigger the start and move on.
-                this.deviceBandwidthTestService.startTest();
+                if (!this.deviceBandwidthTestService.startTest()) {
+                    console.log("ERROR:Failed to start bandwidth test");
+                }
                 this.status.state = StateMachineE.PausedForBandwidthTest;
                 break;
             }
             case StateMachineE.PausedForBandwidthTest: {
                 // While the test is running, Do nothing
                 // It has code to time its self out.
                 if (this.deviceBandwidthTestService.isTestRunning) {
@@ -617,22 +692,29 @@
 
     private triggerCachingStop(): void {
         this._isPaused = true;
         this._triggerCacheStart$.next(false);
     }
 
     private triggerCachingPause(): void {
+        // Don't emit the paused, the loaders will check this in their own time.
         this._isPaused = true;
     }
 
     private triggerCachingResume(): void {
         this._isPaused = false;
         this._triggerCacheResume$.next();
     }
 
+    forceStart(): void {
+        this.status.state = StateMachineE.StartRunning;
+        this.status.nextState = null;
+        this.triggerCachingStop();
+    }
+
     get triggerCachingStartObservable(): Observable<boolean> {
         return this._triggerCacheStart$.asObservable();
     }
 
     get triggerCachingResumeObservable(): Observable<void> {
         return this._triggerCacheResume$;
     }
```

### Comparing `peek-core-device-3.4.4/peek_core_device/plugin-module/device-status.service.ts` & `peek-core-device-3.4.5/peek_core_device/plugin-module/device-status.service.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/plugin-module/index.ts` & `peek-core-device-3.4.5/peek_core_device/plugin-module/index.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/plugin-module/tuples/OfflineCacheLoaderStatusTuple.ts` & `peek-core-device-3.4.5/peek_core_device/plugin-module/tuples/OfflineCacheLoaderStatusTuple.ts`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/plugin_package.json` & `peek-core-device-3.4.5/peek_core_device/plugin_package.json`

 * *Files 0% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.9964285714285716%*

 * *Differences: {"'plugin'": "{'version': '3.4.5'}"}*

```diff
@@ -179,15 +179,15 @@
     },
     "plugin": {
         "buildDate": "#BUILD_DATE#",
         "buildNumber": "#PLUGIN_BUILD#",
         "creator": "Synerty Pty Ltd",
         "packageName": "peek_core_device",
         "title": "Device",
-        "version": "3.4.4",
+        "version": "3.4.5",
         "website": "www.synerty.com"
     },
     "requiresServices": [
         "logic",
         "storage",
         "admin",
         "field",
```

### Comparing `peek-core-device-3.4.4/peek_core_device/server/DeviceApiABC.py` & `peek-core-device-3.4.5/peek_core_device/server/DeviceApiABC.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/tuples/DeviceDetailTuple.py` & `peek-core-device-3.4.5/peek_core_device/tuples/DeviceDetailTuple.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/tuples/DeviceInfoTuple.py` & `peek-core-device-3.4.5/peek_core_device/tuples/DeviceInfoTuple.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device/tuples/DeviceStatusTuple.py` & `peek-core-device-3.4.5/peek_core_device/tuples/DeviceStatusTuple.py`

 * *Files identical despite different names*

### Comparing `peek-core-device-3.4.4/peek_core_device.egg-info/SOURCES.txt` & `peek-core-device-3.4.5/peek_core_device.egg-info/SOURCES.txt`

 * *Files 1% similar despite different names*

```diff
@@ -165,14 +165,15 @@
 peek_core_device/plugin-module/_private/tuples/EnrolDeviceAction.ts
 peek_core_device/plugin-module/_private/tuples/OfflineCacheCombinedStatusTuple.ts
 peek_core_device/plugin-module/_private/tuples/OfflineCacheSettingTuple.ts
 peek_core_device/plugin-module/_private/tuples/OfflineCacheStatusAction.ts
 peek_core_device/plugin-module/_private/tuples/OfflineCacheStatusTuple.ts
 peek_core_device/plugin-module/_private/tuples/UpdateAppliedAction.ts
 peek_core_device/plugin-module/_private/tuples/UpdateDeviceOnlineAction.ts
+peek_core_device/plugin-module/_private/tuples/offline-cache-local-saved-state-tuple.ts
 peek_core_device/plugin-module/_private/tuples/server-info-tuple-defaults.ts
 peek_core_device/plugin-module/_private/tuples/server-info-tuple.ts
 peek_core_device/plugin-module/_private/tuples/admin/AlterDeviceUpdateAction.ts
 peek_core_device/plugin-module/_private/tuples/admin/CreateDeviceUpdateAction.ts
 peek_core_device/plugin-module/_private/tuples/admin/SettingPropertyTuple.ts
 peek_core_device/plugin-module/_private/tuples/admin/UpdateEnrollmentAction.ts
 peek_core_device/plugin-module/tuples/OfflineCacheLoaderStatusTuple.ts
```

### Comparing `peek-core-device-3.4.4/setup.py` & `peek-core-device-3.4.5/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -7,15 +7,15 @@
 #
 # Modify these values to fork a new plugin
 #
 author = "Synerty"
 author_email = "contact@synerty.com"
 py_package_name = "peek_core_device"
 pip_package_name = py_package_name.replace("_", "-")
-package_version = "3.4.4"
+package_version = "3.4.5"
 description = "Peek Core Device - Device management for the peek platform."
 
 download_url = "https://bitbucket.org/synerty/%s/get/%s.zip"
 download_url %= pip_package_name, package_version
 url = "https://bitbucket.org/synerty/%s" % pip_package_name
 
 #
```


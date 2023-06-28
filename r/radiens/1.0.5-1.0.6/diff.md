# Comparing `tmp/radiens-1.0.5.tar.gz` & `tmp/radiens-1.0.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "radiens-1.0.5.tar", last modified: Fri Jun 23 21:50:16 2023, max compression
+gzip compressed data, was "radiens-1.0.6.tar", last modified: Wed Jun 28 15:54:28 2023, max compression
```

## Comparing `radiens-1.0.5.tar` & `radiens-1.0.6.tar`

### file list

```diff
@@ -1,108 +1,108 @@
-drwxr-xr-x   0 akelly     (502) staff       (20)        0 2023-06-23 21:50:16.949265 radiens-1.0.5/
--rw-r--r--   0 akelly     (502) staff       (20)     1068 2023-04-19 19:30:07.000000 radiens-1.0.5/LICENSE
--rw-r--r--   0 akelly     (502) staff       (20)      610 2023-06-23 21:50:16.949051 radiens-1.0.5/PKG-INFO
--rw-r--r--   0 akelly     (502) staff       (20)      156 2023-04-26 15:20:22.000000 radiens-1.0.5/README.md
-drwxr-xr-x   0 akelly     (502) staff       (20)        0 2023-06-23 21:50:16.932307 radiens-1.0.5/radiens/
--rw-r--r--   0 akelly     (502) staff       (20)      372 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/__init__.py
--rw-r--r--   0 akelly     (502) staff       (20)    15861 2023-06-23 21:49:21.000000 radiens-1.0.5/radiens/allego_client.py
-drwxr-xr-x   0 akelly     (502) staff       (20)        0 2023-06-23 21:50:16.933626 radiens-1.0.5/radiens/api/
--rw-r--r--   0 akelly     (502) staff       (20)       10 2023-04-19 19:30:07.000000 radiens-1.0.5/radiens/api/__init__.py
--rw-r--r--   0 akelly     (502) staff       (20)    24215 2023-06-23 21:46:19.000000 radiens-1.0.5/radiens/api/api_allego.py
--rw-r--r--   0 akelly     (502) staff       (20)     4346 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/api/api_curate.py
-drwxr-xr-x   0 akelly     (502) staff       (20)        0 2023-06-23 21:50:16.934011 radiens-1.0.5/radiens/api/api_utils/
--rw-r--r--   0 akelly     (502) staff       (20)       19 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/api/api_utils/__init__.py
--rw-r--r--   0 akelly     (502) staff       (20)    12083 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/api/api_utils/protocols.py
--rw-r--r--   0 akelly     (502) staff       (20)    11040 2023-06-23 19:35:00.000000 radiens-1.0.5/radiens/api/api_utils/util.py
--rw-r--r--   0 akelly     (502) staff       (20)     9202 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/api/api_videre.py
-drwxr-xr-x   0 akelly     (502) staff       (20)        0 2023-06-23 21:50:16.934280 radiens-1.0.5/radiens/auth/
--rw-r--r--   0 akelly     (502) staff       (20)       83 2023-04-19 19:30:07.000000 radiens-1.0.5/radiens/auth/__init__.py
--rw-r--r--   0 akelly     (502) staff       (20)     3278 2023-04-19 19:30:07.000000 radiens-1.0.5/radiens/auth/interceptors.py
-drwxr-xr-x   0 akelly     (502) staff       (20)        0 2023-06-23 21:50:16.936762 radiens-1.0.5/radiens/cli/
--rw-r--r--   0 akelly     (502) staff       (20)       13 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/cli/__init__.py
--rw-r--r--   0 akelly     (502) staff       (20)     8519 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/cli/allego.py
--rw-r--r--   0 akelly     (502) staff       (20)     6359 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/cli/file_sys.py
--rw-r--r--   0 akelly     (502) staff       (20)     1890 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/cli/main.py
--rw-r--r--   0 akelly     (502) staff       (20)    11856 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/cli/signal_metrics.py
--rw-r--r--   0 akelly     (502) staff       (20)     5952 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/cli/signals.py
--rw-r--r--   0 akelly     (502) staff       (20)     8181 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/cli/spike_sorter.py
--rw-r--r--   0 akelly     (502) staff       (20)     1813 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/cli/sys.py
--rw-r--r--   0 akelly     (502) staff       (20)     5391 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/cli/videre.py
-drwxr-xr-x   0 akelly     (502) staff       (20)        0 2023-06-23 21:50:16.937112 radiens-1.0.5/radiens/common/
--rw-r--r--   0 akelly     (502) staff       (20)       16 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/common/__init__.py
--rw-r--r--   0 akelly     (502) staff       (20)     1450 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/common/constants.py
--rw-r--r--   0 akelly     (502) staff       (20)    31922 2023-06-23 19:35:00.000000 radiens-1.0.5/radiens/curate_client.py
-drwxr-xr-x   0 akelly     (502) staff       (20)        0 2023-06-23 21:50:16.937545 radiens-1.0.5/radiens/exceptions/
--rw-r--r--   0 akelly     (502) staff       (20)      117 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/exceptions/__init__.py
--rw-r--r--   0 akelly     (502) staff       (20)      813 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/exceptions/grpc_error.py
--rw-r--r--   0 akelly     (502) staff       (20)      138 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/exceptions/scan_for_server_error.py
--rw-r--r--   0 akelly     (502) staff       (20)    14187 2023-06-23 19:35:00.000000 radiens-1.0.5/radiens/file_sys_client.py
-drwxr-xr-x   0 akelly     (502) staff       (20)        0 2023-06-23 21:50:16.940724 radiens-1.0.5/radiens/grpc_radiens/
--rw-r--r--   0 akelly     (502) staff       (20)       22 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/grpc_radiens/__init__.py
--rw-r--r--   0 akelly     (502) staff       (20)    30662 2023-06-23 20:06:53.000000 radiens-1.0.5/radiens/grpc_radiens/allegoserver_pb2.py
--rw-r--r--   0 akelly     (502) staff       (20)   153371 2023-06-23 20:06:53.000000 radiens-1.0.5/radiens/grpc_radiens/allegoserver_pb2_grpc.py
--rw-r--r--   0 akelly     (502) staff       (20)    21909 2023-06-23 20:06:53.000000 radiens-1.0.5/radiens/grpc_radiens/biointerface_pb2.py
--rw-r--r--   0 akelly     (502) staff       (20)      159 2023-06-23 20:06:53.000000 radiens-1.0.5/radiens/grpc_radiens/biointerface_pb2_grpc.py
--rw-r--r--   0 akelly     (502) staff       (20)    75678 2023-06-23 20:06:53.000000 radiens-1.0.5/radiens/grpc_radiens/common_pb2.py
--rw-r--r--   0 akelly     (502) staff       (20)      159 2023-06-23 20:06:53.000000 radiens-1.0.5/radiens/grpc_radiens/common_pb2_grpc.py
--rw-r--r--   0 akelly     (502) staff       (20)     8186 2023-06-23 20:06:53.000000 radiens-1.0.5/radiens/grpc_radiens/datasource_pb2.py
--rw-r--r--   0 akelly     (502) staff       (20)      159 2023-06-23 20:06:53.000000 radiens-1.0.5/radiens/grpc_radiens/datasource_pb2_grpc.py
--rw-r--r--   0 akelly     (502) staff       (20)     5328 2023-06-23 20:06:53.000000 radiens-1.0.5/radiens/grpc_radiens/radiens_dev_pb2.py
--rw-r--r--   0 akelly     (502) staff       (20)      159 2023-06-23 20:06:53.000000 radiens-1.0.5/radiens/grpc_radiens/radiens_dev_pb2_grpc.py
--rw-r--r--   0 akelly     (502) staff       (20)    12488 2023-06-23 20:06:53.000000 radiens-1.0.5/radiens/grpc_radiens/radiensserver_pb2.py
--rw-r--r--   0 akelly     (502) staff       (20)   162939 2023-06-23 20:06:53.000000 radiens-1.0.5/radiens/grpc_radiens/radiensserver_pb2_grpc.py
--rw-r--r--   0 akelly     (502) staff       (20)    22386 2023-06-23 20:06:53.000000 radiens-1.0.5/radiens/grpc_radiens/spikesorter_pb2.py
--rw-r--r--   0 akelly     (502) staff       (20)      159 2023-06-23 20:06:53.000000 radiens-1.0.5/radiens/grpc_radiens/spikesorter_pb2_grpc.py
-drwxr-xr-x   0 akelly     (502) staff       (20)        0 2023-06-23 21:50:16.943446 radiens-1.0.5/radiens/lib/
--rw-r--r--   0 akelly     (502) staff       (20)       13 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/lib/__init__.py
--rw-r--r--   0 akelly     (502) staff       (20)     1479 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/lib/_obsolete_bokeh_graphics.py
--rw-r--r--   0 akelly     (502) staff       (20)     6168 2023-06-23 19:35:00.000000 radiens-1.0.5/radiens/lib/allego_lib.py
--rw-r--r--   0 akelly     (502) staff       (20)     1479 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/lib/bokeh_graphics.py
--rw-r--r--   0 akelly     (502) staff       (20)    14572 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/lib/channel_metadata.py
--rw-r--r--   0 akelly     (502) staff       (20)      169 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/lib/corelib.py
--rw-r--r--   0 akelly     (502) staff       (20)     9860 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/lib/dataset_metadata.py
--rw-r--r--   0 akelly     (502) staff       (20)     3611 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/lib/fsys.py
-drwxr-xr-x   0 akelly     (502) staff       (20)        0 2023-06-23 21:50:16.943856 radiens-1.0.5/radiens/lib/graphics/
--rw-r--r--   0 akelly     (502) staff       (20)       18 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/lib/graphics/__init__.py
-drwxr-xr-x   0 akelly     (502) staff       (20)        0 2023-06-23 21:50:16.946001 radiens-1.0.5/radiens/lib/graphics/_obsolete_dashboards/
--rw-r--r--   0 akelly     (502) staff       (20)       20 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/lib/graphics/_obsolete_dashboards/__init__.py
--rw-r--r--   0 akelly     (502) staff       (20)     5913 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/lib/graphics/_obsolete_dashboards/dash_datasets.py
--rw-r--r--   0 akelly     (502) staff       (20)    13168 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/lib/graphics/_obsolete_dashboards/dash_metrics.py
--rw-r--r--   0 akelly     (502) staff       (20)     5197 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/lib/graphics/_obsolete_dashboards/dash_psd.py
--rw-r--r--   0 akelly     (502) staff       (20)     5197 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/lib/graphics/_obsolete_dashboards/dash_snapshot.py
--rw-r--r--   0 akelly     (502) staff       (20)    11253 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/lib/graphics/_obsolete_dashboards/lib.py
--rw-r--r--   0 akelly     (502) staff       (20)      485 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/lib/graphics/_obsolete_dashboards/mock_stdout.py
-drwxr-xr-x   0 akelly     (502) staff       (20)        0 2023-06-23 21:50:16.948249 radiens-1.0.5/radiens/lib/graphics/dashboards/
--rw-r--r--   0 akelly     (502) staff       (20)       20 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/lib/graphics/dashboards/__init__.py
--rw-r--r--   0 akelly     (502) staff       (20)     9745 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/lib/graphics/dashboards/_obsolete_dash_sig_metrics.py
--rw-r--r--   0 akelly     (502) staff       (20)     5197 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/lib/graphics/dashboards/dash_psd.py
--rw-r--r--   0 akelly     (502) staff       (20)    10473 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/lib/graphics/dashboards/dash_sig_metrics.py
--rw-r--r--   0 akelly     (502) staff       (20)     5197 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/lib/graphics/dashboards/dash_snapshot.py
--rw-r--r--   0 akelly     (502) staff       (20)    10399 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/lib/graphics/dashboards/dash_t_range.py
--rw-r--r--   0 akelly     (502) staff       (20)     4960 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/lib/graphics/dashboards/lib.py
--rw-r--r--   0 akelly     (502) staff       (20)    17060 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/lib/graphics/graphics.py
--rw-r--r--   0 akelly     (502) staff       (20)     1472 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/lib/selector_tables.py
--rw-r--r--   0 akelly     (502) staff       (20)    10892 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/lib/sig_metrics.py
--rw-r--r--   0 akelly     (502) staff       (20)     4416 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/lib/signals_snapshot.py
--rw-r--r--   0 akelly     (502) staff       (20)     7459 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/lib/spike_sorter.py
--rw-r--r--   0 akelly     (502) staff       (20)    10661 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/lib/spikes.py
--rw-r--r--   0 akelly     (502) staff       (20)    24918 2023-06-23 19:35:00.000000 radiens-1.0.5/radiens/metrics_client.py
--rw-r--r--   0 akelly     (502) staff       (20)     9249 2023-06-23 19:35:00.000000 radiens-1.0.5/radiens/signals_client.py
--rw-r--r--   0 akelly     (502) staff       (20)    14749 2023-06-23 19:35:00.000000 radiens-1.0.5/radiens/spike_sorter.py
--rw-r--r--   0 akelly     (502) staff       (20)     8122 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/spikes_client.py
-drwxr-xr-x   0 akelly     (502) staff       (20)        0 2023-06-23 21:50:16.948817 radiens-1.0.5/radiens/utils/
--rw-r--r--   0 akelly     (502) staff       (20)       14 2023-04-19 19:30:07.000000 radiens-1.0.5/radiens/utils/__init__.py
--rw-r--r--   0 akelly     (502) staff       (20)     6982 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/utils/config.py
--rw-r--r--   0 akelly     (502) staff       (20)     6953 2023-06-23 19:35:00.000000 radiens-1.0.5/radiens/utils/constants.py
--rw-r--r--   0 akelly     (502) staff       (20)     8430 2023-06-08 19:08:16.000000 radiens-1.0.5/radiens/utils/util.py
--rw-r--r--   0 akelly     (502) staff       (20)       22 2023-06-23 21:50:16.000000 radiens-1.0.5/radiens/version.py
--rw-r--r--   0 akelly     (502) staff       (20)     9694 2023-06-23 19:35:00.000000 radiens-1.0.5/radiens/videre_client.py
--rw-r--r--   0 akelly     (502) staff       (20)     2937 2023-06-23 19:35:00.000000 radiens-1.0.5/radiens/workspace_client.py
-drwxr-xr-x   0 akelly     (502) staff       (20)        0 2023-06-23 21:50:16.933087 radiens-1.0.5/radiens.egg-info/
--rw-r--r--   0 akelly     (502) staff       (20)      610 2023-06-23 21:50:16.000000 radiens-1.0.5/radiens.egg-info/PKG-INFO
--rw-r--r--   0 akelly     (502) staff       (20)     2998 2023-06-23 21:50:16.000000 radiens-1.0.5/radiens.egg-info/SOURCES.txt
--rw-r--r--   0 akelly     (502) staff       (20)        1 2023-06-23 21:50:16.000000 radiens-1.0.5/radiens.egg-info/dependency_links.txt
--rw-r--r--   0 akelly     (502) staff       (20)       49 2023-06-23 21:50:16.000000 radiens-1.0.5/radiens.egg-info/entry_points.txt
--rw-r--r--   0 akelly     (502) staff       (20)       49 2023-06-23 21:50:16.000000 radiens-1.0.5/radiens.egg-info/requires.txt
--rw-r--r--   0 akelly     (502) staff       (20)        8 2023-06-23 21:50:16.000000 radiens-1.0.5/radiens.egg-info/top_level.txt
--rw-r--r--   0 akelly     (502) staff       (20)       38 2023-06-23 21:50:16.949337 radiens-1.0.5/setup.cfg
--rw-r--r--   0 akelly     (502) staff       (20)     1362 2023-06-08 19:08:16.000000 radiens-1.0.5/setup.py
+drwxr-xr-x   0 akelly     (502) staff       (20)        0 2023-06-28 15:54:28.225871 radiens-1.0.6/
+-rw-r--r--   0 akelly     (502) staff       (20)     1068 2023-04-19 19:30:07.000000 radiens-1.0.6/LICENSE
+-rw-r--r--   0 akelly     (502) staff       (20)      610 2023-06-28 15:54:28.225675 radiens-1.0.6/PKG-INFO
+-rw-r--r--   0 akelly     (502) staff       (20)      156 2023-04-26 15:20:22.000000 radiens-1.0.6/README.md
+drwxr-xr-x   0 akelly     (502) staff       (20)        0 2023-06-28 15:54:28.206695 radiens-1.0.6/radiens/
+-rw-r--r--   0 akelly     (502) staff       (20)      372 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/__init__.py
+-rw-r--r--   0 akelly     (502) staff       (20)    16221 2023-06-28 15:36:23.000000 radiens-1.0.6/radiens/allego_client.py
+drwxr-xr-x   0 akelly     (502) staff       (20)        0 2023-06-28 15:54:28.208849 radiens-1.0.6/radiens/api/
+-rw-r--r--   0 akelly     (502) staff       (20)       10 2023-04-19 19:30:07.000000 radiens-1.0.6/radiens/api/__init__.py
+-rw-r--r--   0 akelly     (502) staff       (20)    24210 2023-06-28 15:36:29.000000 radiens-1.0.6/radiens/api/api_allego.py
+-rw-r--r--   0 akelly     (502) staff       (20)     4346 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/api/api_curate.py
+drwxr-xr-x   0 akelly     (502) staff       (20)        0 2023-06-28 15:54:28.209664 radiens-1.0.6/radiens/api/api_utils/
+-rw-r--r--   0 akelly     (502) staff       (20)       19 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/api/api_utils/__init__.py
+-rw-r--r--   0 akelly     (502) staff       (20)    12083 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/api/api_utils/protocols.py
+-rw-r--r--   0 akelly     (502) staff       (20)    11040 2023-06-25 23:52:34.000000 radiens-1.0.6/radiens/api/api_utils/util.py
+-rw-r--r--   0 akelly     (502) staff       (20)     9202 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/api/api_videre.py
+drwxr-xr-x   0 akelly     (502) staff       (20)        0 2023-06-28 15:54:28.210069 radiens-1.0.6/radiens/auth/
+-rw-r--r--   0 akelly     (502) staff       (20)       83 2023-04-19 19:30:07.000000 radiens-1.0.6/radiens/auth/__init__.py
+-rw-r--r--   0 akelly     (502) staff       (20)     3278 2023-04-19 19:30:07.000000 radiens-1.0.6/radiens/auth/interceptors.py
+drwxr-xr-x   0 akelly     (502) staff       (20)        0 2023-06-28 15:54:28.212299 radiens-1.0.6/radiens/cli/
+-rw-r--r--   0 akelly     (502) staff       (20)       13 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/cli/__init__.py
+-rw-r--r--   0 akelly     (502) staff       (20)     8519 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/cli/allego.py
+-rw-r--r--   0 akelly     (502) staff       (20)     6359 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/cli/file_sys.py
+-rw-r--r--   0 akelly     (502) staff       (20)     1890 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/cli/main.py
+-rw-r--r--   0 akelly     (502) staff       (20)    11856 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/cli/signal_metrics.py
+-rw-r--r--   0 akelly     (502) staff       (20)     5952 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/cli/signals.py
+-rw-r--r--   0 akelly     (502) staff       (20)     8181 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/cli/spike_sorter.py
+-rw-r--r--   0 akelly     (502) staff       (20)     1813 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/cli/sys.py
+-rw-r--r--   0 akelly     (502) staff       (20)     5391 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/cli/videre.py
+drwxr-xr-x   0 akelly     (502) staff       (20)        0 2023-06-28 15:54:28.212735 radiens-1.0.6/radiens/common/
+-rw-r--r--   0 akelly     (502) staff       (20)       16 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/common/__init__.py
+-rw-r--r--   0 akelly     (502) staff       (20)     1450 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/common/constants.py
+-rw-r--r--   0 akelly     (502) staff       (20)    31922 2023-06-25 23:52:34.000000 radiens-1.0.6/radiens/curate_client.py
+drwxr-xr-x   0 akelly     (502) staff       (20)        0 2023-06-28 15:54:28.213341 radiens-1.0.6/radiens/exceptions/
+-rw-r--r--   0 akelly     (502) staff       (20)      117 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/exceptions/__init__.py
+-rw-r--r--   0 akelly     (502) staff       (20)      813 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/exceptions/grpc_error.py
+-rw-r--r--   0 akelly     (502) staff       (20)      138 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/exceptions/scan_for_server_error.py
+-rw-r--r--   0 akelly     (502) staff       (20)    14187 2023-06-25 23:52:34.000000 radiens-1.0.6/radiens/file_sys_client.py
+drwxr-xr-x   0 akelly     (502) staff       (20)        0 2023-06-28 15:54:28.216801 radiens-1.0.6/radiens/grpc_radiens/
+-rw-r--r--   0 akelly     (502) staff       (20)       22 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/grpc_radiens/__init__.py
+-rw-r--r--   0 akelly     (502) staff       (20)    30967 2023-06-28 15:53:04.000000 radiens-1.0.6/radiens/grpc_radiens/allegoserver_pb2.py
+-rw-r--r--   0 akelly     (502) staff       (20)   155034 2023-06-28 15:53:04.000000 radiens-1.0.6/radiens/grpc_radiens/allegoserver_pb2_grpc.py
+-rw-r--r--   0 akelly     (502) staff       (20)    21909 2023-06-28 15:53:04.000000 radiens-1.0.6/radiens/grpc_radiens/biointerface_pb2.py
+-rw-r--r--   0 akelly     (502) staff       (20)      159 2023-06-28 15:53:04.000000 radiens-1.0.6/radiens/grpc_radiens/biointerface_pb2_grpc.py
+-rw-r--r--   0 akelly     (502) staff       (20)    75678 2023-06-28 15:53:04.000000 radiens-1.0.6/radiens/grpc_radiens/common_pb2.py
+-rw-r--r--   0 akelly     (502) staff       (20)      159 2023-06-28 15:53:04.000000 radiens-1.0.6/radiens/grpc_radiens/common_pb2_grpc.py
+-rw-r--r--   0 akelly     (502) staff       (20)     8186 2023-06-28 15:53:04.000000 radiens-1.0.6/radiens/grpc_radiens/datasource_pb2.py
+-rw-r--r--   0 akelly     (502) staff       (20)      159 2023-06-28 15:53:04.000000 radiens-1.0.6/radiens/grpc_radiens/datasource_pb2_grpc.py
+-rw-r--r--   0 akelly     (502) staff       (20)     5328 2023-06-28 15:53:04.000000 radiens-1.0.6/radiens/grpc_radiens/radiens_dev_pb2.py
+-rw-r--r--   0 akelly     (502) staff       (20)      159 2023-06-28 15:53:04.000000 radiens-1.0.6/radiens/grpc_radiens/radiens_dev_pb2_grpc.py
+-rw-r--r--   0 akelly     (502) staff       (20)    12488 2023-06-28 15:53:04.000000 radiens-1.0.6/radiens/grpc_radiens/radiensserver_pb2.py
+-rw-r--r--   0 akelly     (502) staff       (20)   162939 2023-06-28 15:53:04.000000 radiens-1.0.6/radiens/grpc_radiens/radiensserver_pb2_grpc.py
+-rw-r--r--   0 akelly     (502) staff       (20)    22462 2023-06-28 15:53:04.000000 radiens-1.0.6/radiens/grpc_radiens/spikesorter_pb2.py
+-rw-r--r--   0 akelly     (502) staff       (20)      159 2023-06-28 15:53:04.000000 radiens-1.0.6/radiens/grpc_radiens/spikesorter_pb2_grpc.py
+drwxr-xr-x   0 akelly     (502) staff       (20)        0 2023-06-28 15:54:28.219702 radiens-1.0.6/radiens/lib/
+-rw-r--r--   0 akelly     (502) staff       (20)       13 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/lib/__init__.py
+-rw-r--r--   0 akelly     (502) staff       (20)     1479 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/lib/_obsolete_bokeh_graphics.py
+-rw-r--r--   0 akelly     (502) staff       (20)     6168 2023-06-25 23:52:34.000000 radiens-1.0.6/radiens/lib/allego_lib.py
+-rw-r--r--   0 akelly     (502) staff       (20)     1479 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/lib/bokeh_graphics.py
+-rw-r--r--   0 akelly     (502) staff       (20)    14820 2023-06-25 23:52:34.000000 radiens-1.0.6/radiens/lib/channel_metadata.py
+-rw-r--r--   0 akelly     (502) staff       (20)      169 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/lib/corelib.py
+-rw-r--r--   0 akelly     (502) staff       (20)     9860 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/lib/dataset_metadata.py
+-rw-r--r--   0 akelly     (502) staff       (20)     3611 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/lib/fsys.py
+drwxr-xr-x   0 akelly     (502) staff       (20)        0 2023-06-28 15:54:28.220471 radiens-1.0.6/radiens/lib/graphics/
+-rw-r--r--   0 akelly     (502) staff       (20)       18 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/lib/graphics/__init__.py
+drwxr-xr-x   0 akelly     (502) staff       (20)        0 2023-06-28 15:54:28.222388 radiens-1.0.6/radiens/lib/graphics/_obsolete_dashboards/
+-rw-r--r--   0 akelly     (502) staff       (20)       20 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/lib/graphics/_obsolete_dashboards/__init__.py
+-rw-r--r--   0 akelly     (502) staff       (20)     5913 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/lib/graphics/_obsolete_dashboards/dash_datasets.py
+-rw-r--r--   0 akelly     (502) staff       (20)    13168 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/lib/graphics/_obsolete_dashboards/dash_metrics.py
+-rw-r--r--   0 akelly     (502) staff       (20)     5197 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/lib/graphics/_obsolete_dashboards/dash_psd.py
+-rw-r--r--   0 akelly     (502) staff       (20)     5197 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/lib/graphics/_obsolete_dashboards/dash_snapshot.py
+-rw-r--r--   0 akelly     (502) staff       (20)    11253 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/lib/graphics/_obsolete_dashboards/lib.py
+-rw-r--r--   0 akelly     (502) staff       (20)      485 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/lib/graphics/_obsolete_dashboards/mock_stdout.py
+drwxr-xr-x   0 akelly     (502) staff       (20)        0 2023-06-28 15:54:28.224498 radiens-1.0.6/radiens/lib/graphics/dashboards/
+-rw-r--r--   0 akelly     (502) staff       (20)       20 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/lib/graphics/dashboards/__init__.py
+-rw-r--r--   0 akelly     (502) staff       (20)     9745 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/lib/graphics/dashboards/_obsolete_dash_sig_metrics.py
+-rw-r--r--   0 akelly     (502) staff       (20)     5197 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/lib/graphics/dashboards/dash_psd.py
+-rw-r--r--   0 akelly     (502) staff       (20)    10473 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/lib/graphics/dashboards/dash_sig_metrics.py
+-rw-r--r--   0 akelly     (502) staff       (20)     5197 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/lib/graphics/dashboards/dash_snapshot.py
+-rw-r--r--   0 akelly     (502) staff       (20)    10399 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/lib/graphics/dashboards/dash_t_range.py
+-rw-r--r--   0 akelly     (502) staff       (20)     4960 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/lib/graphics/dashboards/lib.py
+-rw-r--r--   0 akelly     (502) staff       (20)    17060 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/lib/graphics/graphics.py
+-rw-r--r--   0 akelly     (502) staff       (20)     1472 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/lib/selector_tables.py
+-rw-r--r--   0 akelly     (502) staff       (20)    10892 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/lib/sig_metrics.py
+-rw-r--r--   0 akelly     (502) staff       (20)     4416 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/lib/signals_snapshot.py
+-rw-r--r--   0 akelly     (502) staff       (20)     7459 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/lib/spike_sorter.py
+-rw-r--r--   0 akelly     (502) staff       (20)    10661 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/lib/spikes.py
+-rw-r--r--   0 akelly     (502) staff       (20)    24918 2023-06-25 23:52:34.000000 radiens-1.0.6/radiens/metrics_client.py
+-rw-r--r--   0 akelly     (502) staff       (20)     9363 2023-06-25 23:52:34.000000 radiens-1.0.6/radiens/signals_client.py
+-rw-r--r--   0 akelly     (502) staff       (20)    14749 2023-06-25 23:52:34.000000 radiens-1.0.6/radiens/spike_sorter.py
+-rw-r--r--   0 akelly     (502) staff       (20)     8122 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/spikes_client.py
+drwxr-xr-x   0 akelly     (502) staff       (20)        0 2023-06-28 15:54:28.225407 radiens-1.0.6/radiens/utils/
+-rw-r--r--   0 akelly     (502) staff       (20)       14 2023-04-19 19:30:07.000000 radiens-1.0.6/radiens/utils/__init__.py
+-rw-r--r--   0 akelly     (502) staff       (20)     6982 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/utils/config.py
+-rw-r--r--   0 akelly     (502) staff       (20)     6953 2023-06-25 23:52:34.000000 radiens-1.0.6/radiens/utils/constants.py
+-rw-r--r--   0 akelly     (502) staff       (20)     8430 2023-06-08 19:08:16.000000 radiens-1.0.6/radiens/utils/util.py
+-rw-r--r--   0 akelly     (502) staff       (20)       22 2023-06-28 15:54:27.000000 radiens-1.0.6/radiens/version.py
+-rw-r--r--   0 akelly     (502) staff       (20)     9694 2023-06-25 23:52:34.000000 radiens-1.0.6/radiens/videre_client.py
+-rw-r--r--   0 akelly     (502) staff       (20)     2937 2023-06-25 23:52:34.000000 radiens-1.0.6/radiens/workspace_client.py
+drwxr-xr-x   0 akelly     (502) staff       (20)        0 2023-06-28 15:54:28.207779 radiens-1.0.6/radiens.egg-info/
+-rw-r--r--   0 akelly     (502) staff       (20)      610 2023-06-28 15:54:28.000000 radiens-1.0.6/radiens.egg-info/PKG-INFO
+-rw-r--r--   0 akelly     (502) staff       (20)     2998 2023-06-28 15:54:28.000000 radiens-1.0.6/radiens.egg-info/SOURCES.txt
+-rw-r--r--   0 akelly     (502) staff       (20)        1 2023-06-28 15:54:28.000000 radiens-1.0.6/radiens.egg-info/dependency_links.txt
+-rw-r--r--   0 akelly     (502) staff       (20)       49 2023-06-28 15:54:28.000000 radiens-1.0.6/radiens.egg-info/entry_points.txt
+-rw-r--r--   0 akelly     (502) staff       (20)       49 2023-06-28 15:54:28.000000 radiens-1.0.6/radiens.egg-info/requires.txt
+-rw-r--r--   0 akelly     (502) staff       (20)        8 2023-06-28 15:54:28.000000 radiens-1.0.6/radiens.egg-info/top_level.txt
+-rw-r--r--   0 akelly     (502) staff       (20)       38 2023-06-28 15:54:28.226093 radiens-1.0.6/setup.cfg
+-rw-r--r--   0 akelly     (502) staff       (20)     1362 2023-06-08 19:08:16.000000 radiens-1.0.6/setup.py
```

### Comparing `radiens-1.0.5/LICENSE` & `radiens-1.0.6/LICENSE`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/PKG-INFO` & `radiens-1.0.6/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: radiens
-Version: 1.0.5
+Version: 1.0.6
 Summary: provides python API to RADIENS analytics platform
 Home-page: http://neuronexus.github.io
 Author: NeuroNexus
 Author-email: dkipke@neuronexus.com
 License: MIT
 Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python :: 3.10
```

### Comparing `radiens-1.0.5/radiens/allego_client.py` & `radiens-1.0.6/radiens/allego_client.py`

 * *Files 8% similar despite different names*

```diff
@@ -186,44 +186,44 @@
             'gain': 0,
             'high_pass': {'enable': False, 'cutoff_freq': 0.0}}
         """
         return api.get_dac_register(CORE_ADDR)
 
     def get_stim_params(self):
         """
-        returns current stimulation params
+        returns current stimulation params (see :py:meth:`set_stim_params`)
 
         Returns:
             stim_params (dict): a dictionary where the keys are the system channel indices and the values are dictionaries containing the stimulation parameters. Each dictionary associated with a channel will have the following key-value pairs:
 
-            - 'enabled': stimulation enabled on channel (bool)
-            - 'enable_amp_settle': amp settle enabled on channel (bool)
-            - 'enable_charge_recovery': charge recovery enabled on channel (bool)
-            - 'first_phase_amplitude_uA': Level of current in µA for the first phase of the stimulation waveform (type)
-            - 'first_phase_duration_us': # 0
-            - 'interphase_delay_us': # 0
-            - 'maintain_amp_settle_us': # 0
-            - 'number_of_stim_pulses': # 2
-            - 'post_stim_amp_settle_us': # 0
-            - 'post_stim_charge_recovery_off_us': # 0
-            - 'post_stim_charge_recovery_on_us': # 0
-            - 'post_trigger_delay_us': # 0
-            - 'pre_stim_amp_settle_us': # 0
-            - 'pulse_or_train': # 0 
-            - 'pulse_train_period_us': # 0
-            - 'refactory_period_ms': # 1
-            - 'second_phase_amplitude_uA': Level of current in µA for the second phase of the stimulation waveform (type)
-            - 'second_phase_duration_us': # 0
-            - 'stim_polarity': # 0
-            - 'stim_shape': # 0
-            - 'stim_sys_chan_idx': # 0
-            - 'trigger_edge_or_level': # 0
-            - 'trigger_high_or_low': # 0
-            - 'trigger_source_is_keypress': # 0
-            - 'trigger_source_idx': # 0
+                - 'enabled': stimulation enabled on channel (`bool`)
+                - 'enable_amp_settle': amp settle enabled on channel (`bool`)
+                - 'enable_charge_recovery': charge recovery enabled on channel (`bool`)
+                - 'first_phase_amplitude_uA': Level of current in µA for the first phase of the stimulation waveform (type)
+                - 'first_phase_duration_us': (`float`)
+                - 'interphase_delay_us': (`float`)
+                - 'maintain_amp_settle_us': (`float`) 
+                - 'number_of_stim_pulses': (`int`)
+                - 'post_stim_amp_settle_us': (`float`)
+                - 'post_stim_charge_recovery_off_us': (`float`)
+                - 'post_stim_charge_recovery_on_us': (`float`)
+                - 'post_trigger_delay_us': (`float`)
+                - 'pre_stim_amp_settle_us': (`float`)
+                - 'pulse_or_train': (`int`)
+                - 'pulse_train_period_us': (`float`)
+                - 'refactory_period_ms': (`float`)
+                - 'second_phase_amplitude_uA': Level of current in µA for the second phase of the stimulation waveform (type)
+                - 'second_phase_duration_us': (`float`)
+                - 'stim_polarity': (`int`)
+                - 'stim_shape': (`int`)
+                - 'stim_sys_chan_idx': (`int`)
+                - 'trigger_edge_or_level': (`int`)
+                - 'trigger_high_or_low': (`int`)
+                - 'trigger_source_is_keypress': (`bool`)
+                - 'trigger_source_idx': (`int`)
 
 
         Example:
             >>> get_stim_params()
             {6: # system idx
                 {'stim_shape': 0,
                 'stim_polarity': 0,
@@ -328,50 +328,51 @@
         Sets current time to most recent time point in signal cache.
 
         This should be called before the first call of :py:meth:`get_signals`. The first call of :py:meth:`get_signals` 
         will return the new signals since the last call to :py:meth:`set_time_to_cache_head` 
         """
         return api.set_time_to_cache_head(PCACHE_ADDR, PRIMARY_CACHE_STREAM_GROUP_ID)
 
-    def set_manual_stim_trigger(self, trigger: int, trigger_on: bool):
+    def set_manual_stim_trigger(self, trigger: int):
         """
         """
-        api.set_manual_stim_trigger(CORE_ADDR, trigger, trigger_on)
+        api.set_manual_stim_trigger(CORE_ADDR, trigger)
 
     def set_stim_params(self, param_dict: dict):
         """
-        Sets stimulation parameters to a stim channel. Any parameter not specified in the parameter `param_dict` will be kept as is, or set to default parameter, if not already set.
+        Sets stimulation parameters to a stim channel. Any parameter not specified in the parameter `param_dict` will be kept as is, or set to default parameter, if not already set (see :py:meth:`get_stim_params`).
 
-        Parameters: param_dict: has following key-value pairs (comments are defaults):
+        Parameters: 
+            param_dict: has following key-value pairs; comments are defaults:
 
-            - 'enabled': # False
-            - 'enable_amp_settle': # False
-            - 'enable_charge_recovery': # False
-            - 'first_phase_amplitude_uA': # 0
-            - 'first_phase_duration_us': # 0
-            - 'interphase_delay_us': # 0
-            - 'maintain_amp_settle_us': # 0
-            - 'number_of_stim_pulses': # 2
-            - 'post_stim_amp_settle_us': # 0
-            - 'post_stim_charge_recovery_off_us': # 0
-            - 'post_stim_charge_recovery_on_us': # 0
-            - 'post_trigger_delay_us': # 0
-            - 'pre_stim_amp_settle_us': # 0
-            - 'pulse_or_train': # 0 
-            - 'pulse_train_period_us': # 0
-            - 'refactory_period_ms': # 1
-            - 'second_phase_amplitude_uA': # 0
-            - 'second_phase_duration_us': # 0
-            - 'stim_polarity': # 0
-            - 'stim_shape': # 0
-            - 'stim_sys_chan_idx': # 0
-            - 'trigger_edge_or_level': # 0
-            - 'trigger_high_or_low': # 0
-            - 'trigger_source_is_keypress': # 0
-            - 'trigger_source_idx': # 0
+                - 'enabled': # False
+                - 'enable_amp_settle': # False
+                - 'enable_charge_recovery': # False
+                - 'first_phase_amplitude_uA': # 0
+                - 'first_phase_duration_us': # 0
+                - 'interphase_delay_us': # 0
+                - 'maintain_amp_settle_us': # 0
+                - 'number_of_stim_pulses': # 2
+                - 'post_stim_amp_settle_us': # 0
+                - 'post_stim_charge_recovery_off_us': # 0
+                - 'post_stim_charge_recovery_on_us': # 0
+                - 'post_trigger_delay_us': # 0
+                - 'pre_stim_amp_settle_us': # 0
+                - 'pulse_or_train': # 0 
+                - 'pulse_train_period_us': # 0
+                - 'refactory_period_ms': # 1
+                - 'second_phase_amplitude_uA': # 0
+                - 'second_phase_duration_us': # 0
+                - 'stim_polarity': # 0
+                - 'stim_shape': # 0
+                - 'stim_sys_chan_idx': # 0
+                - 'trigger_edge_or_level': # 0
+                - 'trigger_high_or_low': # 0
+                - 'trigger_source_is_keypress': # True
+                - 'trigger_source_idx': # 0
 
         """
         return api.set_stim_params(CORE_ADDR, param_dict)
 
     def set_stim_step(self, step: int):
         api.set_stim_step(CORE_ADDR, step)
```

### Comparing `radiens-1.0.5/radiens/api/api_allego.py` & `radiens-1.0.6/radiens/api/api_allego.py`

 * *Files 0% similar despite different names*

```diff
@@ -336,20 +336,20 @@
         try:
             stub.SetSensor(common_pb2.SetSensorRequest(streamGroupId=PRIMARY_CACHE_STREAM_GROUP_ID,
                                                        port=pb_port, headstageId=pb_hstage, probeId=pb_probe))
         except grpc.RpcError as ex:
             handle_grpc_error(ex, CLIENT_NAME)
 
 
-def set_manual_stim_trigger(addr, trigger: int, trigger_on: bool):
+def set_manual_stim_trigger(addr, trigger: int):
     with new_server_channel(addr) as chan:
         stub = allegoserver_pb2_grpc.AllegoCoreStub(chan)
         try:
-            stub.ManualStimTrigger(allegoserver_pb2.ManualStimTriggerRequest(
-                trigger=trigger, triggerOn=trigger_on))
+            stub.SetManualStimTriggerToggle(allegoserver_pb2.ManualStimTriggerToggleRequest(
+                trigger=trigger))
         except grpc.RpcError as ex:
             handle_grpc_error(ex, CLIENT_NAME)
 
 
 def set_stim_step(addr, stim_step_enum: int):
     with new_server_channel(addr) as chan:
         stub = allegoserver_pb2_grpc.AllegoCoreStub(chan)
@@ -383,14 +383,15 @@
             curr_chan_params = curr_params[stim_sys_chan_idx]
 
         for param, val in curr_chan_params.items():
             if param not in stim_params_req:
                 stim_params_req[param] = val
 
         req = stim_params_dict_to_req(stim_params_req)
+        pprint(req)
         try:
             stub = allegoserver_pb2_grpc.AllegoCoreStub(chan)
             stub.SetStimParams(req)
         except grpc.RpcError as ex:
             handle_grpc_error(ex, CLIENT_NAME)
```

### Comparing `radiens-1.0.5/radiens/api/api_curate.py` & `radiens-1.0.6/radiens/api/api_curate.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/api/api_utils/protocols.py` & `radiens-1.0.6/radiens/api/api_utils/protocols.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/api/api_utils/util.py` & `radiens-1.0.6/radiens/api/api_utils/util.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/api/api_videre.py` & `radiens-1.0.6/radiens/api/api_videre.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/auth/interceptors.py` & `radiens-1.0.6/radiens/auth/interceptors.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/cli/allego.py` & `radiens-1.0.6/radiens/cli/allego.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/cli/file_sys.py` & `radiens-1.0.6/radiens/cli/file_sys.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/cli/main.py` & `radiens-1.0.6/radiens/cli/main.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/cli/signal_metrics.py` & `radiens-1.0.6/radiens/cli/signal_metrics.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/cli/signals.py` & `radiens-1.0.6/radiens/cli/signals.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/cli/spike_sorter.py` & `radiens-1.0.6/radiens/cli/spike_sorter.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/cli/sys.py` & `radiens-1.0.6/radiens/cli/sys.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/cli/videre.py` & `radiens-1.0.6/radiens/cli/videre.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/common/constants.py` & `radiens-1.0.6/radiens/common/constants.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/curate_client.py` & `radiens-1.0.6/radiens/curate_client.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/exceptions/grpc_error.py` & `radiens-1.0.6/radiens/exceptions/grpc_error.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/file_sys_client.py` & `radiens-1.0.6/radiens/file_sys_client.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/grpc_radiens/allegoserver_pb2.py` & `radiens-1.0.6/radiens/grpc_radiens/allegoserver_pb2.py`

 * *Files 1% similar despite different names*

```diff
@@ -13,48 +13,48 @@
 
 from . import common_pb2 as common__pb2
 from . import datasource_pb2 as datasource__pb2
 from . import biointerface_pb2 as biointerface__pb2
 from . import spikesorter_pb2 as spikesorter__pb2
 
 
-DESCRIPTOR = _descriptor_pool.Default().AddSerializedFile(b'\n\x12\x61llegoserver.proto\x12\x06\x61llego\x1a\x0c\x63ommon.proto\x1a\x10\x64\x61tasource.proto\x1a\x12\x62iointerface.proto\x1a\x11spikesorter.proto\"4\n\x0eRestartRequest\x12\"\n\x04mode\x18\x01 \x02(\x0e\x32\x14.allego.BackboneMode\":\n\x11SetProfileRequest\x12\n\n\x02id\x18\x01 \x02(\t\x12\x0c\n\x04type\x18\x02 \x02(\t\x12\x0b\n\x03\x64ur\x18\x03 \x02(\x02\"\xe9\x02\n\x10LogSystemRequest\x12\x34\n\x04mode\x18\x01 \x02(\x0e\x32&.allego.LogSystemRequest.LogSystemMode\x12=\n\x07outMode\x18\x02 \x01(\x0e\x32,.allego.LogSystemRequest.LogSystemOutputMode\x12\x16\n\x0eoutPathAndFile\x18\x03 \x01(\t\"|\n\rLogSystemMode\x12\n\n\x06\x63onfig\x10\x00\x12\n\n\x06status\x10\x01\x12\x0c\n\x08port_map\x10\x02\x12\n\n\x06pcache\x10\x03\x12\x0c\n\x08sigstats\x10\x04\x12\x11\n\rneurons_stats\x10\x06\x12\x18\n\x14\x62\x61se_signalgroup_map\x10\x07\"J\n\x13LogSystemOutputMode\x12\x12\n\x0eLOG_OUT_STDERR\x10\x00\x12\x0f\n\x0bLOG_OUT_CSV\x10\x01\x12\x0e\n\nLOG_OUT_MD\x10\x02\"4\n\x10SetStreamRequest\x12 \n\x04mode\x18\x01 \x02(\x0e\x32\x12.allego.StreamMode\"4\n\x10SetRecordRequest\x12 \n\x04mode\x18\x01 \x02(\x0e\x32\x12.allego.RecordMode\"~\n\x14SetConfigCoreRequest\x12\x10\n\x08sampFreq\x18\x01 \x01(\x01\x12\x0f\n\x07loopDur\x18\x02 \x01(\x01\x12\x19\n\x11pcachePersistence\x18\x03 \x01(\x01\x12(\n\x0b\x63\x61\x62leLength\x18\x04 \x01(\x0b\x32\x13.allego.CableLength\">\n\x0b\x43\x61\x62leLength\x12\x1a\n\x04port\x18\x01 \x02(\x0e\x32\x0c.allego.Port\x12\x13\n\x0b\x63\x61\x62leLength\x18\x02 \x02(\x01\"f\n\x0c\x43\x61\x62leLengths\x12\t\n\x01\x41\x18\x01 \x02(\x01\x12\t\n\x01\x42\x18\x02 \x02(\x01\x12\t\n\x01\x43\x18\x03 \x02(\x01\x12\t\n\x01\x44\x18\x04 \x02(\x01\x12\t\n\x01\x45\x18\x05 \x02(\x01\x12\t\n\x01\x46\x18\x06 \x02(\x01\x12\t\n\x01G\x18\x07 \x02(\x01\x12\t\n\x01H\x18\x08 \x02(\x01\"\xb1\x01\n\nConfigCore\x12\x1c\n\x14\x61llegoCoreServerPort\x18\x01 \x02(\t\x12\x14\n\x0c\x62\x61seSampFreq\x18\x03 \x02(\x01\x12\x17\n\x0fstreamLoopDurMs\x18\x04 \x02(\x05\x12*\n\x0c\x63\x61\x62leLengths\x18\x05 \x02(\x0b\x32\x14.allego.CableLengths\x12*\n\x0c\x62\x61\x63kboneMode\x18\x06 \x02(\x0e\x32\x14.allego.BackboneMode\"r\n\x0fRecordingStatus\x12&\n\nrecordMode\x18\x01 \x02(\x0e\x32\x12.allego.RecordMode\x12\x16\n\x0e\x61\x63tiveFileName\x18\x02 \x02(\t\x12\x10\n\x08\x64uration\x18\x03 \x02(\x01\x12\r\n\x05\x65rror\x18\x04 \x02(\t\"r\n\x0fStreamingStatus\x12&\n\nstreamMode\x18\x01 \x02(\x0e\x32\x12.allego.StreamMode\x12\x1a\n\x12primaryCacheTRange\x18\x02 \x03(\x01\x12\x1b\n\x13hardwareMemoryLevel\x18\x03 \x02(\x01\"\xda\x01\n\x0e\x42\x61\x63kboneStatus\x12*\n\tstreaming\x18\x01 \x02(\x0b\x32\x17.allego.StreamingStatus\x12*\n\trecording\x18\x02 \x02(\x0b\x32\x17.allego.RecordingStatus\x12\'\n\x05ports\x18\x03 \x03(\x0b\x32\x18.allego.PortChannelCount\x12\x13\n\x0bisConnected\x18\x04 \x02(\x08\x12\x32\n\x10gpioChannelCount\x18\x05 \x02(\x0b\x32\x18.allego.GPIOChannelCount\"\xc9\x02\n\x0f\x43onfigAndStatus\x12*\n\tstreaming\x18\x01 \x02(\x0b\x32\x17.allego.StreamingStatus\x12*\n\trecording\x18\x02 \x02(\x0b\x32\x17.allego.RecordingStatus\x12\'\n\x05ports\x18\x03 \x03(\x0b\x32\x18.allego.PortChannelCount\x12\x13\n\x0bisConnected\x18\x04 \x02(\x08\x12\x32\n\x10gpioChannelCount\x18\x05 \x02(\x0b\x32\x18.allego.GPIOChannelCount\x12\x14\n\x0c\x62\x61seSampFreq\x18\x06 \x02(\x01\x12*\n\x0c\x63\x61\x62leLengths\x18\x07 \x02(\x0b\x32\x14.allego.CableLengths\x12*\n\x0c\x62\x61\x63kboneMode\x18\x08 \x02(\x0e\x32\x14.allego.BackboneMode\"g\n\x0f\x43onfigRecording\x12\x14\n\x0c\x62\x61seFileName\x18\x01 \x02(\t\x12\x14\n\x0c\x62\x61seFilePath\x18\x02 \x02(\t\x12\x15\n\rdataSourceIdx\x18\x03 \x01(\x05\x12\x11\n\ttimeStamp\x18\x04 \x01(\x08\"V\n\x14\x44IOModeEventsRequest\x12\x0f\n\x07\x63hanIdx\x18\x02 \x02(\x05\x12\x16\n\x0e\x65ventThreshold\x18\x03 \x02(\x01\x12\x15\n\reventPolarity\x18\x04 \x02(\x08\"6\n\x14\x44IOModeManualRequest\x12\x0f\n\x07\x63hanIdx\x18\x01 \x02(\x05\x12\r\n\x05state\x18\x02 \x02(\x08\"s\n\x19\x44igitalOutChannelRegister\x12\x13\n\x0bmanualState\x18\x01 \x02(\x08\x12\x16\n\x0e\x65ventThreshold\x18\x02 \x02(\x01\x12\x15\n\reventPolarity\x18\x03 \x02(\x08\x12\x12\n\nntvChanIdx\x18\x04 \x02(\x05\"q\n\x12\x44igitalOutRegister\x12\x1d\n\x04mode\x18\x01 \x02(\x0e\x32\x0f.allego.DIOMode\x12<\n\x11\x64outChanRegisters\x18\x02 \x03(\x0b\x32!.allego.DigitalOutChannelRegister\"\x1e\n\x0e\x44\x41\x43GainRequest\x12\x0c\n\x04gain\x18\x01 \x02(\x05\"9\n\x13\x44\x41\x43HighPassRegister\x12\x0e\n\x06\x65nable\x18\x01 \x02(\x08\x12\x12\n\ncutoffFreq\x18\x02 \x02(\x01\"w\n\x18\x41nalogOutChannelRegister\x12\x15\n\rPriNtvChanIdx\x18\x01 \x02(\x05\x12\x1b\n\x13\x41nalogOutNtvChanIdx\x18\x02 \x02(\x05\x12\x0e\n\x06Stream\x18\x03 \x02(\x05\x12\x17\n\x0fStreamOffsetIdx\x18\x04 \x02(\x05\"\x90\x01\n\x11\x41nalogOutRegister\x12;\n\x11\x61nalogOutChannels\x18\x01 \x03(\x0b\x32 .allego.AnalogOutChannelRegister\x12\x0c\n\x04gain\x18\x02 \x02(\x05\x12\x30\n\x0bhighpassReg\x18\x03 \x02(\x0b\x32\x1b.allego.DACHighPassRegister\"!\n\x0cSerialNumber\x12\x11\n\tserialNum\x18\x01 \x02(\t\"\x81\x01\n\x12SetSimPortsRequest\x12\x33\n\x07simPort\x18\x01 \x03(\x0b\x32\".allego.SetSimPortsRequest.SimPort\x1a\x36\n\x07SimPort\x12\x1a\n\x04port\x18\x01 \x02(\x0e\x32\x0c.allego.Port\x12\x0f\n\x07numChan\x18\x02 \x02(\x03\"\'\n\x14SetMuxChannelRequest\x12\x0f\n\x07\x63hannel\x18\x01 \x02(\x03\"\'\n\x14SetPotVoltageRequest\x12\x0f\n\x07voltage\x18\x01 \x02(\x02\"!\n\x10GetADCLevelReply\x12\r\n\x05level\x18\x01 \x02(\x02\"#\n\x12SetPotRangeRequest\x12\r\n\x05range\x18\x01 \x02(\x05\"!\n\x11SetPotModeRequest\x12\x0c\n\x04mode\x18\x01 \x02(\x08\")\n\x17SetPotCellEnableRequest\x12\x0e\n\x06\x65nable\x18\x01 \x02(\x08\",\n\x12ReadWireOutRequest\x12\x16\n\x0ewireOutAddress\x18\x01 \x02(\x03\"(\n\x10ReadWireOutReply\x12\x14\n\x0cwireOutValue\x18\x01 \x02(\x03\"\xc7\x02\n\x11LogsysConfigReply\x12(\n\nsystemMode\x18\x01 \x02(\x0e\x32\x14.allego.BackboneMode\x12\x14\n\x0c\x62\x61seSampFreq\x18\x02 \x02(\x01\x12\x17\n\x0fstreamLoopDurMs\x18\x03 \x02(\x05\x12\x1a\n\x12priCachePersistDur\x18\x04 \x02(\x01\x12!\n\x19priCacheStatsUpdatePeriod\x18\x05 \x02(\x01\x12\x12\n\nactiveSigs\x18\x06 \x02(\x05\x12\x10\n\x08priChans\x18\x07 \x02(\x05\x12\x10\n\x08\x61uxChans\x18\x08 \x02(\x05\x12\x10\n\x08\x64inChans\x18\t \x02(\x05\x12\x11\n\tdoutChans\x18\n \x02(\x05\x12\"\n\x08portSpec\x18\x0b \x03(\x0b\x32\x10.allego.PortInfo\x12\x19\n\x11numConnectedPorts\x18\x0c \x02(\x05\"Y\n\x08PortInfo\x12\x1a\n\x04port\x18\x01 \x02(\x0e\x32\x0c.allego.Port\x12\r\n\x05probe\x18\x02 \x02(\t\x12\x11\n\theadstage\x18\x03 \x02(\t\x12\x0f\n\x07numSigs\x18\x04 \x02(\x05\"c\n\x11LogsysStatusReply\x12\'\n\x07recStat\x18\x01 \x02(\x0b\x32\x16.allego.RecorderStatus\x12%\n\x07sysStat\x18\x02 \x02(\x0b\x32\x14.allego.SystemStatus\"\xba\x01\n\x0eRecorderStatus\x12&\n\nrecordMode\x18\x01 \x02(\x0e\x32\x12.allego.RecordMode\x12\x10\n\x08\x64uration\x18\x02 \x02(\x01\x12\x0c\n\x04\x62\x65ta\x18\x03 \x02(\x01\x12\x11\n\tsizeBytes\x18\x04 \x02(\x05\x12\x0c\n\x04path\x18\x05 \x02(\t\x12\x10\n\x08\x62\x61seName\x18\x06 \x02(\t\x12\x15\n\rdataSourceIdx\x18\x07 \x02(\x05\x12\x16\n\x0e\x61\x63tiveFileName\x18\x08 \x02(\t\"\x96\x03\n\x0cSystemStatus\x12&\n\nstreamMode\x18\x01 \x02(\x0e\x32\x12.allego.StreamMode\x12\x14\n\x0c\x62\x61seSampFreq\x18\x02 \x02(\x01\x12\x12\n\nnumPriSigs\x18\x03 \x02(\x05\x12\x12\n\nnumAuxSigs\x18\x04 \x02(\x05\x12\x12\n\nnumDinSigs\x18\x05 \x02(\x05\x12\x13\n\x0bnumDoutSigs\x18\x06 \x02(\x05\x12\x13\n\x0btStampRange\x18\x07 \x03(\x03\x12\x0e\n\x06tRange\x18\x08 \x03(\x01\x12\x11\n\tstreamDur\x18\t \x02(\x01\x12\x14\n\x0cmeanChunkDur\x18\n \x02(\x01\x12\x1c\n\x14meanHardwareMemLevel\x18\x0b \x02(\x02\x12\x1b\n\x13maxHardwareMemLevel\x18\x0c \x02(\x02\x12\x1b\n\x13minHardwareMemLevel\x18\r \x02(\x02\x12\x1c\n\x14lastHardwareMemLevel\x18\x0e \x02(\x02\x12\x19\n\x11meanStreamLoopDur\x18\x0f \x02(\x01\x12\x18\n\x10streamEfficiency\x18\x10 \x02(\x01\"\xd8\x02\n\x11LogsysPcacheReply\x12\x0c\n\x04name\x18\x01 \x02(\t\x12\x10\n\x08sampFreq\x18\x02 \x02(\x01\x12\x12\n\npersistDur\x18\x03 \x02(\x01\x12\x18\n\x10minNumDatablocks\x18\x04 \x02(\x05\x12\x11\n\tsizeBytes\x18\x05 \x02(\x03\x12 \n\x18totalDatablocksProcessed\x18\x06 \x02(\x04\x12\x16\n\x0enumTimeSamples\x18\x07 \x02(\x03\x12\x1f\n\x17\x61llTimeMeanDatablockDur\x18\x08 \x02(\x01\x12\x15\n\rnumDataBlocks\x18\t \x02(\x05\x12\x0e\n\x06tRange\x18\n \x03(\x01\x12\x0f\n\x07tsRange\x18\x0b \x03(\x03\x12\x12\n\nnumPriSigs\x18\x0c \x02(\x05\x12\x12\n\nnumAuxSigs\x18\r \x02(\x05\x12\x12\n\nnumDinSigs\x18\x0e \x02(\x05\x12\x13\n\x0bnumDoutSigs\x18\x0f \x02(\x05\"5\n\x10TriggerModeState\x12!\n\x04mode\x18\x01 \x02(\x0e\x32\x13.allego.TriggerMode\"*\n\x12LoadAllMosiRequest\x12\x14\n\x0cregisterVals\x18\x01 \x03(\x05\"\x15\n\x13TransmitMosiRequest\"5\n\x0f\x44umpMisoRequest\x12\x10\n\x08nSamples\x18\x01 \x02(\x05\x12\x10\n\x08\x66ileName\x18\x02 \x02(\t\"\x99\x03\n\x15SinapsStatusRegisters\x12\x18\n\x10\x63\x61librationState\x18\x01 \x02(\x08\x12\x1b\n\x13\x63\x61librationProgress\x18\x02 \x02(\x01\x12\x1d\n\x15numActivePixelsShank0\x18\x03 \x02(\x05\x12\x1d\n\x15numActivePixelsShank1\x18\x04 \x02(\x05\x12\x1d\n\x15numActivePixelsShank2\x18\x05 \x02(\x05\x12\x1d\n\x15numActivePixelsShank3\x18\x06 \x02(\x05\x12\x0f\n\x07vRefFFA\x18\x07 \x02(\x01\x12\x0f\n\x07vRefFFB\x18\x08 \x02(\x01\x12\x0f\n\x07vRefFFC\x18\t \x02(\x01\x12\x0f\n\x07vRefFFD\x18\n \x02(\x01\x12\x10\n\x08isError0\x18\x0b \x02(\x08\x12\x10\n\x08isError1\x18\x0c \x02(\x08\x12\x10\n\x08isError2\x18\r \x02(\x08\x12\x10\n\x08isError3\x18\x0e \x02(\x08\x12\x13\n\x0bhostCounter\x18\x0f \x02(\x05\x12\x13\n\x0b\x66pgaCounter\x18\x10 \x02(\x05\x12\x17\n\x0f\x66irmwareVersion\x18\x11 \x02(\t\"%\n\x12\x46lashSinapsRequest\x12\x0f\n\x07\x62itfile\x18\x01 \x02(\t\"3\n\x0cHALdashboard\x12#\n\x04mode\x18\x01 \x02(\x0e\x32\x15.allego.AllegoHALmode\"\xbc\x06\n\nStimParams\x12$\n\tstimShape\x18\x01 \x02(\x0e\x32\x11.allego.StimShape\x12*\n\x0cstimPolarity\x18\x02 \x02(\x0e\x32\x14.allego.StimPolarity\x12\x1a\n\x12\x66irstPhaseDuration\x18\x03 \x02(\x01\x12\x1b\n\x13secondPhaseDuration\x18\x04 \x02(\x01\x12\x17\n\x0finterphaseDelay\x18\x05 \x02(\x01\x12\x1b\n\x13\x66irstPhaseAmplitude\x18\x06 \x02(\x01\x12\x1c\n\x14secondPhaseAmplitude\x18\x07 \x02(\x01\x12\x17\n\x0f\x62\x61selineVoltage\x18\x08 \x02(\x01\x12:\n\x12triggerEdgeOrLevel\x18\n \x02(\x0e\x32\x1e.allego.StimTriggerEdgeOrLevel\x12\x36\n\x10triggerHighOrLow\x18\x0b \x02(\x0e\x32\x1c.allego.StimTriggerHighOrLow\x12\x0f\n\x07\x65nabled\x18\x0c \x02(\x08\x12\x18\n\x10postTriggerDelay\x18\r \x02(\x01\x12.\n\x0cpulseOrTrain\x18\x0e \x02(\x0e\x32\x18.allego.StimPulseOrTrain\x12\x1a\n\x12numberOfStimPulses\x18\x0f \x02(\x05\x12\x18\n\x10pulseTrainPeriod\x18\x10 \x02(\x01\x12\x18\n\x10refractoryPeriod\x18\x11 \x02(\x01\x12\x18\n\x10preStimAmpSettle\x18\x12 \x02(\x01\x12\x19\n\x11postStimAmpSettle\x18\x13 \x02(\x01\x12\x19\n\x11maintainAmpSettle\x18\x14 \x02(\x08\x12\x17\n\x0f\x65nableAmpSettle\x18\x15 \x02(\x08\x12\x1d\n\x15postStimChargeRecovOn\x18\x16 \x02(\x01\x12\x1e\n\x16postStimChargeRecovOff\x18\x17 \x02(\x01\x12\x1c\n\x14\x65nableChargeRecovery\x18\x18 \x02(\x08\x12\x1f\n\x17triggerSourceIsKeypress\x18\x19 \x02(\x08\x12\x18\n\x10triggerSourceIdx\x18\x1a \x02(\x05\x12\x16\n\x0estimSysChanIdx\x18\x1b \x02(\x05\"\x89\x01\n\x0fStimParamsReply\x12\x33\n\x06params\x18\x01 \x03(\x0b\x32#.allego.StimParamsReply.ParamsEntry\x1a\x41\n\x0bParamsEntry\x12\x0b\n\x03key\x18\x01 \x01(\x05\x12!\n\x05value\x18\x02 \x01(\x0b\x32\x12.allego.StimParams:\x02\x38\x01\">\n\x18ManualStimTriggerRequest\x12\x0f\n\x07trigger\x18\x01 \x02(\x05\x12\x11\n\ttriggerOn\x18\x02 \x02(\x08\"5\n\x0fStimStepMessage\x12\"\n\x08stimStep\x18\x01 \x02(\x0e\x32\x10.allego.StimStep*!\n\nStreamMode\x12\t\n\x05S_OFF\x10\x00\x12\x08\n\x04S_ON\x10\x01*!\n\nRecordMode\x12\t\n\x05R_OFF\x10\x00\x12\x08\n\x04R_ON\x10\x01*\x82\x04\n\x0c\x42\x61\x63kboneMode\x12\x10\n\x0cSMARTBOX_PRO\x10\x00\x12\x19\n\x15SMARTBOX_SIM_GEN_SINE\x10\x01\x12\x1b\n\x17SMARTBOX_SIM_GEN_SPIKES\x10\x02\x12\x1b\n\x17SMARTBOX_SIM_DATASOURCE\x10\x03\x12\x13\n\x0fOPEN_EPHYS_USB3\x10\x04\x12#\n\x1fINTAN_RECORDING_CONTROLLER_1024\x10\x05\x12\x14\n\x10SMARTBOX_CLASSIC\x10\x06\x12\"\n\x1eINTAN_RECORDING_CONTROLLER_512\x10\x07\x12\x13\n\x0fOPEN_EPHYS_USB2\x10\x08\x12\x0e\n\nINTAN_USB2\x10\t\x12 \n\x1cSMARTBOX_SIM_GEN_SINE_MAPPED\x10\n\x12#\n\x1fSMARTBOX_SIM_GEN_SINE_HIGH_FREQ\x10\x0b\x12$\n SMARTBOX_SIM_GEN_SINE_MULTI_BAND\x10\x0c\x12\x1b\n\x17SMARTBOX_PRO_SINAPS_256\x10\r\x12\x1c\n\x18SMARTBOX_PRO_SINAPS_1024\x10\x0e\x12\x10\n\x0cXDAQ_ONE_REC\x10\x0f\x12\x11\n\rXDAQ_ONE_STIM\x10\x10\x12\x11\n\rXDAQ_CORE_REC\x10\x11\x12\x12\n\x0eXDAQ_CORE_STIM\x10\x12*,\n\x07\x44IOMode\x12\n\n\x06manual\x10\x00\x12\n\n\x06\x65vents\x10\x01\x12\t\n\x05gated\x10\x02*O\n\x0bTriggerMode\x12\x0b\n\x07T_DIN_0\x10\x00\x12\x0b\n\x07T_DIN_1\x10\x01\x12\x0c\n\x08T_DOUT_0\x10\x02\x12\x0c\n\x08T_DOUT_1\x10\x03\x12\n\n\x06T_NONE\x10\x04*q\n\rAllegoHALmode\x12\x11\n\rA_HAL_GENERIC\x10\x00\x12\x13\n\x0f\x41_HAL_SPIKESORT\x10\x01\x12\x14\n\x10\x41_HAL_MULTISCALE\x10\x02\x12\"\n\x1e\x41_HAL_MULTISCALE_BIDIRECTIONAL\x10\x03*W\n\tStimShape\x12\x0c\n\x08\x42IPHASIC\x10\x00\x12\x1d\n\x19\x42IPHASIC_INTERPHASE_DELAY\x10\x01\x12\r\n\tTRIPHASIC\x10\x02\x12\x0e\n\nMONOPHASIC\x10\x03*4\n\x0cStimPolarity\x12\x12\n\x0e\x43\x41THODIC_FIRST\x10\x00\x12\x10\n\x0c\x41NODIC_FIRST\x10\x01*3\n\x16StimTriggerEdgeOrLevel\x12\x0b\n\x07ST_EDGE\x10\x00\x12\x0c\n\x08ST_LEVEL\x10\x01*/\n\x14StimTriggerHighOrLow\x12\x0b\n\x07ST_HIGH\x10\x00\x12\n\n\x06ST_LOW\x10\x01*5\n\x10StimPulseOrTrain\x12\x10\n\x0cSINGLE_PULSE\x10\x00\x12\x0f\n\x0bPULSE_TRAIN\x10\x01*\x90\x02\n\x08StimStep\x12\x13\n\x0fStimStepSizeMin\x10\x00\x12\x14\n\x10StimStepSize10nA\x10\x01\x12\x14\n\x10StimStepSize20nA\x10\x02\x12\x14\n\x10StimStepSize50nA\x10\x03\x12\x15\n\x11StimStepSize100nA\x10\x04\x12\x15\n\x11StimStepSize200nA\x10\x05\x12\x15\n\x11StimStepSize500nA\x10\x06\x12\x13\n\x0fStimStepSize1uA\x10\x07\x12\x13\n\x0fStimStepSize2uA\x10\x08\x12\x13\n\x0fStimStepSize5uA\x10\t\x12\x14\n\x10StimStepSize10uA\x10\n\x12\x13\n\x0fStimStepSizeMax\x10\x0b\x32\xbc(\n\nAllegoCore\x12?\n\x0bHealthcheck\x12\x17.allego.StandardRequest\x1a\x15.allego.StandardReply\"\x00\x12:\n\x07Restart\x12\x16.allego.RestartRequest\x1a\x15.allego.StandardReply\"\x00\x12\x39\n\x05\x43lose\x12\x17.allego.StandardRequest\x1a\x15.allego.StandardReply\"\x00\x12J\n\x13GetRadixEnvironment\x12\x17.allego.StandardRequest\x1a\x18.allego.RadixEnvironment\"\x00\x12L\n\x10WorkspaceControl\x12\x1f.allego.WorkspaceControlRequest\x1a\x15.allego.StandardReply\"\x00\x12T\n\x11GetRadiensServers\x12 .allego.GetRadiensServersRequest\x1a\x1b.allego.RadiensServersReply\"\x00\x12j\n\x1bGetStatusPollFieldsToUpdate\x12\'.allego.StatusPollFieldsToUpdateRequest\x1a .allego.StatusPollFieldsToUpdate\"\x00\x12\x46\n\rSetConfigCore\x12\x1c.allego.SetConfigCoreRequest\x1a\x15.allego.StandardReply\"\x00\x12\x45\n\x0fSetProfileState\x12\x19.allego.SetProfileRequest\x1a\x15.allego.StandardReply\"\x00\x12\x46\n\x12SetConfigRecording\x12\x17.allego.ConfigRecording\x1a\x15.allego.StandardReply\"\x00\x12\x43\n\x0eSetStreamState\x12\x18.allego.SetStreamRequest\x1a\x15.allego.StandardReply\"\x00\x12\x43\n\x0eSetRecordState\x12\x18.allego.SetRecordRequest\x1a\x15.allego.StandardReply\"\x00\x12\x45\n\x0cSetDIOEvents\x12\x1c.allego.DIOModeEventsRequest\x1a\x15.allego.StandardReply\"\x00\x12\x45\n\x0cSetDIOManual\x12\x1c.allego.DIOModeManualRequest\x1a\x15.allego.StandardReply\"\x00\x12?\n\x0bSetDIOGated\x12\x17.allego.StandardRequest\x1a\x15.allego.StandardReply\"\x00\x12=\n\nSetDACGain\x12\x16.allego.DACGainRequest\x1a\x15.allego.StandardReply\"\x00\x12\x41\n\x0cSetDACStream\x12\x18.allego.DACStreamRequest\x1a\x15.allego.StandardReply\"\x00\x12;\n\tSetDACOff\x12\x15.allego.DACOffRequest\x1a\x15.allego.StandardReply\"\x00\x12\x46\n\x0eSetDACHighPass\x12\x1b.allego.DACHighPassRegister\x1a\x15.allego.StandardReply\"\x00\x12\x42\n\x0bSetSimPorts\x12\x1a.allego.SetSimPortsRequest\x1a\x15.allego.StandardReply\"\x00\x12\x46\n\rSetMuxChannel\x12\x1c.allego.SetMuxChannelRequest\x1a\x15.allego.StandardReply\"\x00\x12\x43\n\x0eSetTriggerMode\x12\x18.allego.TriggerModeState\x1a\x15.allego.StandardReply\"\x00\x12\x46\n\rSetPotVoltage\x12\x1c.allego.SetPotVoltageRequest\x1a\x15.allego.StandardReply\"\x00\x12\x42\n\x0bSetPotRange\x12\x1a.allego.SetPotRangeRequest\x1a\x15.allego.StandardReply\"\x00\x12@\n\nSetPotMode\x12\x19.allego.SetPotModeRequest\x1a\x15.allego.StandardReply\"\x00\x12L\n\x10SetPotCellEnable\x12\x1f.allego.SetPotCellEnableRequest\x1a\x15.allego.StandardReply\"\x00\x12\x42\n\x0bSetDSPGroup\x12\x1a.allego.SetDSPGroupRequest\x1a\x15.allego.StandardReply\"\x00\x12<\n\rSetStimParams\x12\x12.allego.StimParams\x1a\x15.allego.StandardReply\"\x00\x12\x43\n\rGetStimParams\x12\x17.allego.StandardRequest\x1a\x17.allego.StimParamsReply\"\x00\x12?\n\x0bSetStimStep\x12\x17.allego.StimStepMessage\x1a\x15.allego.StandardReply\"\x00\x12\x41\n\x0bGetStimStep\x12\x17.allego.StandardRequest\x1a\x17.allego.StimStepMessage\"\x00\x12N\n\x11ManualStimTrigger\x12 .allego.ManualStimTriggerRequest\x1a\x15.allego.StandardReply\"\x00\x12:\n\tGetConfig\x12\x17.allego.StandardRequest\x1a\x12.allego.ConfigCore\"\x00\x12H\n\x0cGetWorkspace\x12\x1b.allego.GetWorkspaceRequest\x1a\x19.allego.GetWorkspaceReply\"\x00\x12H\n\x12GetConfigRecording\x12\x17.allego.StandardRequest\x1a\x17.allego.ConfigRecording\"\x00\x12>\n\tGetStatus\x12\x17.allego.StandardRequest\x1a\x16.allego.BackboneStatus\"\x00\x12H\n\x12GetConfigAndStatus\x12\x17.allego.StandardRequest\x1a\x17.allego.ConfigAndStatus\"\x00\x12O\n\x13GetDataSourceParams\x12\x1c.allego.SignalGroupIDRequest\x1a\x18.allego.DataSourceParams\"\x00\x12\x42\n\x11GetIntanImpedance\x12\x18.allego.ImpedanceRequest\x1a\x11.allego.Impedance\"\x00\x12?\n\x0bGetDSPGroup\x12\x1c.allego.SignalGroupIDRequest\x1a\x10.allego.DSPGroup\"\x00\x12\x42\n\tGetDIOReg\x12\x17.allego.StandardRequest\x1a\x1a.allego.DigitalOutRegister\"\x00\x12\x41\n\tGetDACReg\x12\x17.allego.StandardRequest\x1a\x19.allego.AnalogOutRegister\"\x00\x12<\n\tGetSerial\x12\x17.allego.StandardRequest\x1a\x14.allego.SerialNumber\"\x00\x12\x45\n\x0eGetTriggerMode\x12\x17.allego.StandardRequest\x1a\x18.allego.TriggerModeState\"\x00\x12\x42\n\x0bGetADCLevel\x12\x17.allego.StandardRequest\x1a\x18.allego.GetADCLevelReply\"\x00\x12\x45\n\x0bReadWireOut\x12\x1a.allego.ReadWireOutRequest\x1a\x18.allego.ReadWireOutReply\"\x00\x12O\n\x0fListSensorSpecs\x12\x1c.allego.SignalGroupIDRequest\x1a\x1c.allego.ListSensorSpecsReply\"\x00\x12N\n\x11GetSignalGroupIDs\x12\x17.allego.StandardRequest\x1a\x1e.allego.GetSignalGroupIDsReply\"\x00\x12H\n\x0eGetSorterIDMap\x12\x17.allego.StandardRequest\x1a\x1b.allego.GetSorterIDMapReply\"\x00\x12N\n\x11GetSpikeSorterIDs\x12\x17.allego.StandardRequest\x1a\x1e.allego.GetSpikeSorterIDsReply\"\x00\x12\x45\n\x0eGetSignalGroup\x12\x1c.allego.SignalGroupIDRequest\x1a\x13.allego.SignalGroup\"\x00\x12N\n\x11UpdateSignalGroup\x12 .allego.UpdateSignalGroupRequest\x1a\x15.allego.StandardReply\"\x00\x12;\n\tScanPorts\x12\x17.allego.StandardRequest\x1a\x13.allego.SignalGroup\"\x00\x12>\n\tSetSensor\x12\x18.allego.SetSensorRequest\x1a\x15.allego.StandardReply\"\x00\x12T\n\x14SetSensorPositionTcs\x12#.allego.SetSensorPositionTcsRequest\x1a\x15.allego.StandardReply\"\x00\x12R\n\x13SetSitePositionsTcs\x12\".allego.SetSitePositionsTcsRequest\x1a\x15.allego.StandardReply\"\x00\x12O\n\x13GetDataSourceStatus\x12\x1c.allego.SignalGroupIDRequest\x1a\x18.allego.DataSourceStatus\"\x00\x12H\n\x0c\x46\x65\x61tureStart\x12\x1f.allego.FeatureStartStopRequest\x1a\x15.allego.StandardReply\"\x00\x12G\n\x0b\x46\x65\x61tureStop\x12\x1f.allego.FeatureStartStopRequest\x1a\x15.allego.StandardReply\"\x00\x12=\n\nGetPrivacy\x12\x17.allego.StandardRequest\x1a\x14.allego.PrivacyReply\"\x00\x12@\n\nSetPrivacy\x12\x19.allego.SetPrivacyRequest\x1a\x15.allego.StandardReply\"\x00\x12\x42\n\x0bLoadAllMosi\x12\x1a.allego.LoadAllMosiRequest\x1a\x15.allego.StandardReply\"\x00\x12\x44\n\x0cTransmitMosi\x12\x1b.allego.TransmitMosiRequest\x1a\x15.allego.StandardReply\"\x00\x12<\n\x08\x44umpMiso\x12\x17.allego.DumpMisoRequest\x1a\x15.allego.StandardReply\"\x00\x12T\n\x18GetSinapsStatusRegisters\x12\x17.allego.StandardRequest\x1a\x1d.allego.SinapsStatusRegisters\"\x00\x12\x42\n\x0b\x46lashSinaps\x12\x1a.allego.FlashSinapsRequest\x1a\x15.allego.StandardReply\"\x00\x12L\n\x16GetOrCreateEventViewer\x12\x15.allego.EventViewerID\x1a\x19.allego.EventViewerConfig\"\x00\x12G\n\x11UpdateEventViewer\x12\x19.allego.EventViewerConfig\x1a\x15.allego.StandardReply\"\x00\x12T\n\x15ListEventViewerEvents\x12\x15.allego.EventViewerID\x1a\".allego.ListEventViewerEventsReply\"\x00\x12U\n\x13GetEventViewerEvent\x12\".allego.GetEventViewerEventRequest\x1a\x18.allego.EventViewerEvent\"\x00\x12L\n\x10ListEventViewers\x12\x17.allego.StandardRequest\x1a\x1d.allego.ListEventViewersReply\"\x00\x12\x42\n\x0fGetHALdashboard\x12\x17.allego.StandardRequest\x1a\x14.allego.HALdashboard\"\x00\x32\xe4\x02\n\x07Pcache1\x12?\n\x0bHealthcheck\x12\x17.allego.StandardRequest\x1a\x15.allego.StandardReply\"\x00\x12@\n\rGetHDSnapshot\x12\x19.allego.HDSnapshotRequest\x1a\x12.allego.HDSnapshot\"\x00\x12J\n\x15GetHDSnapshotFromHead\x12\x1a.allego.HDSnapshotRequest2\x1a\x13.allego.HDSnapshot2\"\x00\x12=\n\nGetSignals\x12\x19.allego.GetSignalsRequest\x1a\x12.allego.RawSignals\"\x00\x12K\n\x12SetTimeRangeToHead\x12\x1c.allego.SignalGroupIDRequest\x1a\x15.allego.StandardReply\"\x00\x32\x8d\x04\n\x04Kpi1\x12?\n\x0bHealthcheck\x12\x17.allego.StandardRequest\x1a\x15.allego.StandardReply\"\x00\x12H\n\rKpiGetMetrics\x12\x15.allego.KpiMetricsReq\x1a\x1e.allego.KpiBundlePacketMetrics\"\x00\x12\x45\n\x0cGetKpiStatus\x12\x1b.allego.GetKpiStatusRequest\x1a\x16.allego.KpiStatusReply\"\x00\x12K\n\x0bSetKpiParam\x12#.allego.SpikeSorterSetParamsRequest\x1a\x15.allego.StandardReply\"\x00\x12S\n\x0bGetKpiParam\x12\x19.allego.DataSourceRequest\x1a\'.allego.GetSpikeSorterParamCommandReply\"\x00\x12I\n\x12SetKpiUpdatePeriod\x12\x1a.allego.SetKpiParamRequest\x1a\x15.allego.StandardReply\"\x00\x12\x46\n\x0fSetKpiPacketDur\x12\x1a.allego.SetKpiParamRequest\x1a\x15.allego.StandardReply\"\x00\x32\xb6\t\n\x08Neurons1\x12?\n\x0bHealthcheck\x12\x17.allego.StandardRequest\x1a\x15.allego.StandardReply\"\x00\x12P\n\x12SpikeSorterCommand\x12!.allego.SpikeSorterCommandRequest\x1a\x15.allego.StandardReply\"\x00\x12R\n\x13SpikeSorterSetParam\x12\".allego.SpikeSorterSetParamRequest\x1a\x15.allego.StandardReply\"\x00\x12T\n\x14SpikeSorterSetParams\x12#.allego.SpikeSorterSetParamsRequest\x1a\x15.allego.StandardReply\"\x00\x12\x64\n\x13SpikeSorterGetParam\x12\".allego.SpikeSorterStandardRequest\x1a\'.allego.GetSpikeSorterParamCommandReply\"\x00\x12U\n\x13SpikeSorterGetState\x12\".allego.SpikeSorterStandardRequest\x1a\x18.allego.SpikeSorterState\"\x00\x12\x65\n\x17SpikeSorterGetDashboard\x12\".allego.SpikeSorterStandardRequest\x1a$.allego.SpikeSorterGetDashboardReply\"\x00\x12i\n\x18SpikeSorterGetRasterData\x12\'.allego.SpikeSorterGetRasterDataRequest\x1a\".allego.SpikeSorterRasterDataReply\"\x00\x12\x61\n\x1a\x42iointerfaceGetSpikesDense\x12\x1e.allego.SpikesGetSpikesRequest\x1a!.allego.SpikesSpikeDataDenseReply\"\x00\x12\x66\n\x16\x42iointerfaceGetNeurons\x12%.allego.BiointerfaceGetNeuronsRequest\x1a#.allego.BiointerfaceGetNeuronsReply\"\x00\x12p\n\"BiointerfaceSeekEndSpikeTimestamps\x12\x31.allego.BiointerfaceSeekEndSpikeTimestampsRequest\x1a\x15.allego.StandardReply\"\x00\x12N\n\rSpikesGetSpec\x12\".allego.SpikeSorterStandardRequest\x1a\x17.allego.SpikesSpecReply\"\x00\x12Q\n\x0f\x42iointerfaceViz\x12\x1e.allego.BiointerfaceVizRequest\x1a\x1c.allego.BiointerfaceVizReply\"\x00\x42\x15Z\x13internal/radix/grpc')
+DESCRIPTOR = _descriptor_pool.Default().AddSerializedFile(b'\n\x12\x61llegoserver.proto\x12\x06\x61llego\x1a\x0c\x63ommon.proto\x1a\x10\x64\x61tasource.proto\x1a\x12\x62iointerface.proto\x1a\x11spikesorter.proto\"4\n\x0eRestartRequest\x12\"\n\x04mode\x18\x01 \x02(\x0e\x32\x14.allego.BackboneMode\":\n\x11SetProfileRequest\x12\n\n\x02id\x18\x01 \x02(\t\x12\x0c\n\x04type\x18\x02 \x02(\t\x12\x0b\n\x03\x64ur\x18\x03 \x02(\x02\"\xe9\x02\n\x10LogSystemRequest\x12\x34\n\x04mode\x18\x01 \x02(\x0e\x32&.allego.LogSystemRequest.LogSystemMode\x12=\n\x07outMode\x18\x02 \x01(\x0e\x32,.allego.LogSystemRequest.LogSystemOutputMode\x12\x16\n\x0eoutPathAndFile\x18\x03 \x01(\t\"|\n\rLogSystemMode\x12\n\n\x06\x63onfig\x10\x00\x12\n\n\x06status\x10\x01\x12\x0c\n\x08port_map\x10\x02\x12\n\n\x06pcache\x10\x03\x12\x0c\n\x08sigstats\x10\x04\x12\x11\n\rneurons_stats\x10\x06\x12\x18\n\x14\x62\x61se_signalgroup_map\x10\x07\"J\n\x13LogSystemOutputMode\x12\x12\n\x0eLOG_OUT_STDERR\x10\x00\x12\x0f\n\x0bLOG_OUT_CSV\x10\x01\x12\x0e\n\nLOG_OUT_MD\x10\x02\"4\n\x10SetStreamRequest\x12 \n\x04mode\x18\x01 \x02(\x0e\x32\x12.allego.StreamMode\"4\n\x10SetRecordRequest\x12 \n\x04mode\x18\x01 \x02(\x0e\x32\x12.allego.RecordMode\"~\n\x14SetConfigCoreRequest\x12\x10\n\x08sampFreq\x18\x01 \x01(\x01\x12\x0f\n\x07loopDur\x18\x02 \x01(\x01\x12\x19\n\x11pcachePersistence\x18\x03 \x01(\x01\x12(\n\x0b\x63\x61\x62leLength\x18\x04 \x01(\x0b\x32\x13.allego.CableLength\">\n\x0b\x43\x61\x62leLength\x12\x1a\n\x04port\x18\x01 \x02(\x0e\x32\x0c.allego.Port\x12\x13\n\x0b\x63\x61\x62leLength\x18\x02 \x02(\x01\"f\n\x0c\x43\x61\x62leLengths\x12\t\n\x01\x41\x18\x01 \x02(\x01\x12\t\n\x01\x42\x18\x02 \x02(\x01\x12\t\n\x01\x43\x18\x03 \x02(\x01\x12\t\n\x01\x44\x18\x04 \x02(\x01\x12\t\n\x01\x45\x18\x05 \x02(\x01\x12\t\n\x01\x46\x18\x06 \x02(\x01\x12\t\n\x01G\x18\x07 \x02(\x01\x12\t\n\x01H\x18\x08 \x02(\x01\"\xb1\x01\n\nConfigCore\x12\x1c\n\x14\x61llegoCoreServerPort\x18\x01 \x02(\t\x12\x14\n\x0c\x62\x61seSampFreq\x18\x03 \x02(\x01\x12\x17\n\x0fstreamLoopDurMs\x18\x04 \x02(\x05\x12*\n\x0c\x63\x61\x62leLengths\x18\x05 \x02(\x0b\x32\x14.allego.CableLengths\x12*\n\x0c\x62\x61\x63kboneMode\x18\x06 \x02(\x0e\x32\x14.allego.BackboneMode\"r\n\x0fRecordingStatus\x12&\n\nrecordMode\x18\x01 \x02(\x0e\x32\x12.allego.RecordMode\x12\x16\n\x0e\x61\x63tiveFileName\x18\x02 \x02(\t\x12\x10\n\x08\x64uration\x18\x03 \x02(\x01\x12\r\n\x05\x65rror\x18\x04 \x02(\t\"r\n\x0fStreamingStatus\x12&\n\nstreamMode\x18\x01 \x02(\x0e\x32\x12.allego.StreamMode\x12\x1a\n\x12primaryCacheTRange\x18\x02 \x03(\x01\x12\x1b\n\x13hardwareMemoryLevel\x18\x03 \x02(\x01\"\xda\x01\n\x0e\x42\x61\x63kboneStatus\x12*\n\tstreaming\x18\x01 \x02(\x0b\x32\x17.allego.StreamingStatus\x12*\n\trecording\x18\x02 \x02(\x0b\x32\x17.allego.RecordingStatus\x12\'\n\x05ports\x18\x03 \x03(\x0b\x32\x18.allego.PortChannelCount\x12\x13\n\x0bisConnected\x18\x04 \x02(\x08\x12\x32\n\x10gpioChannelCount\x18\x05 \x02(\x0b\x32\x18.allego.GPIOChannelCount\"\xc9\x02\n\x0f\x43onfigAndStatus\x12*\n\tstreaming\x18\x01 \x02(\x0b\x32\x17.allego.StreamingStatus\x12*\n\trecording\x18\x02 \x02(\x0b\x32\x17.allego.RecordingStatus\x12\'\n\x05ports\x18\x03 \x03(\x0b\x32\x18.allego.PortChannelCount\x12\x13\n\x0bisConnected\x18\x04 \x02(\x08\x12\x32\n\x10gpioChannelCount\x18\x05 \x02(\x0b\x32\x18.allego.GPIOChannelCount\x12\x14\n\x0c\x62\x61seSampFreq\x18\x06 \x02(\x01\x12*\n\x0c\x63\x61\x62leLengths\x18\x07 \x02(\x0b\x32\x14.allego.CableLengths\x12*\n\x0c\x62\x61\x63kboneMode\x18\x08 \x02(\x0e\x32\x14.allego.BackboneMode\"g\n\x0f\x43onfigRecording\x12\x14\n\x0c\x62\x61seFileName\x18\x01 \x02(\t\x12\x14\n\x0c\x62\x61seFilePath\x18\x02 \x02(\t\x12\x15\n\rdataSourceIdx\x18\x03 \x01(\x05\x12\x11\n\ttimeStamp\x18\x04 \x01(\x08\"V\n\x14\x44IOModeEventsRequest\x12\x0f\n\x07\x63hanIdx\x18\x02 \x02(\x05\x12\x16\n\x0e\x65ventThreshold\x18\x03 \x02(\x01\x12\x15\n\reventPolarity\x18\x04 \x02(\x08\"6\n\x14\x44IOModeManualRequest\x12\x0f\n\x07\x63hanIdx\x18\x01 \x02(\x05\x12\r\n\x05state\x18\x02 \x02(\x08\"s\n\x19\x44igitalOutChannelRegister\x12\x13\n\x0bmanualState\x18\x01 \x02(\x08\x12\x16\n\x0e\x65ventThreshold\x18\x02 \x02(\x01\x12\x15\n\reventPolarity\x18\x03 \x02(\x08\x12\x12\n\nntvChanIdx\x18\x04 \x02(\x05\"q\n\x12\x44igitalOutRegister\x12\x1d\n\x04mode\x18\x01 \x02(\x0e\x32\x0f.allego.DIOMode\x12<\n\x11\x64outChanRegisters\x18\x02 \x03(\x0b\x32!.allego.DigitalOutChannelRegister\"\x1e\n\x0e\x44\x41\x43GainRequest\x12\x0c\n\x04gain\x18\x01 \x02(\x05\"9\n\x13\x44\x41\x43HighPassRegister\x12\x0e\n\x06\x65nable\x18\x01 \x02(\x08\x12\x12\n\ncutoffFreq\x18\x02 \x02(\x01\"w\n\x18\x41nalogOutChannelRegister\x12\x15\n\rPriNtvChanIdx\x18\x01 \x02(\x05\x12\x1b\n\x13\x41nalogOutNtvChanIdx\x18\x02 \x02(\x05\x12\x0e\n\x06Stream\x18\x03 \x02(\x05\x12\x17\n\x0fStreamOffsetIdx\x18\x04 \x02(\x05\"\x90\x01\n\x11\x41nalogOutRegister\x12;\n\x11\x61nalogOutChannels\x18\x01 \x03(\x0b\x32 .allego.AnalogOutChannelRegister\x12\x0c\n\x04gain\x18\x02 \x02(\x05\x12\x30\n\x0bhighpassReg\x18\x03 \x02(\x0b\x32\x1b.allego.DACHighPassRegister\"!\n\x0cSerialNumber\x12\x11\n\tserialNum\x18\x01 \x02(\t\"\x81\x01\n\x12SetSimPortsRequest\x12\x33\n\x07simPort\x18\x01 \x03(\x0b\x32\".allego.SetSimPortsRequest.SimPort\x1a\x36\n\x07SimPort\x12\x1a\n\x04port\x18\x01 \x02(\x0e\x32\x0c.allego.Port\x12\x0f\n\x07numChan\x18\x02 \x02(\x03\"\'\n\x14SetMuxChannelRequest\x12\x0f\n\x07\x63hannel\x18\x01 \x02(\x03\"\'\n\x14SetPotVoltageRequest\x12\x0f\n\x07voltage\x18\x01 \x02(\x02\"!\n\x10GetADCLevelReply\x12\r\n\x05level\x18\x01 \x02(\x02\"#\n\x12SetPotRangeRequest\x12\r\n\x05range\x18\x01 \x02(\x05\"!\n\x11SetPotModeRequest\x12\x0c\n\x04mode\x18\x01 \x02(\x08\")\n\x17SetPotCellEnableRequest\x12\x0e\n\x06\x65nable\x18\x01 \x02(\x08\",\n\x12ReadWireOutRequest\x12\x16\n\x0ewireOutAddress\x18\x01 \x02(\x03\"(\n\x10ReadWireOutReply\x12\x14\n\x0cwireOutValue\x18\x01 \x02(\x03\"\xc7\x02\n\x11LogsysConfigReply\x12(\n\nsystemMode\x18\x01 \x02(\x0e\x32\x14.allego.BackboneMode\x12\x14\n\x0c\x62\x61seSampFreq\x18\x02 \x02(\x01\x12\x17\n\x0fstreamLoopDurMs\x18\x03 \x02(\x05\x12\x1a\n\x12priCachePersistDur\x18\x04 \x02(\x01\x12!\n\x19priCacheStatsUpdatePeriod\x18\x05 \x02(\x01\x12\x12\n\nactiveSigs\x18\x06 \x02(\x05\x12\x10\n\x08priChans\x18\x07 \x02(\x05\x12\x10\n\x08\x61uxChans\x18\x08 \x02(\x05\x12\x10\n\x08\x64inChans\x18\t \x02(\x05\x12\x11\n\tdoutChans\x18\n \x02(\x05\x12\"\n\x08portSpec\x18\x0b \x03(\x0b\x32\x10.allego.PortInfo\x12\x19\n\x11numConnectedPorts\x18\x0c \x02(\x05\"Y\n\x08PortInfo\x12\x1a\n\x04port\x18\x01 \x02(\x0e\x32\x0c.allego.Port\x12\r\n\x05probe\x18\x02 \x02(\t\x12\x11\n\theadstage\x18\x03 \x02(\t\x12\x0f\n\x07numSigs\x18\x04 \x02(\x05\"c\n\x11LogsysStatusReply\x12\'\n\x07recStat\x18\x01 \x02(\x0b\x32\x16.allego.RecorderStatus\x12%\n\x07sysStat\x18\x02 \x02(\x0b\x32\x14.allego.SystemStatus\"\xba\x01\n\x0eRecorderStatus\x12&\n\nrecordMode\x18\x01 \x02(\x0e\x32\x12.allego.RecordMode\x12\x10\n\x08\x64uration\x18\x02 \x02(\x01\x12\x0c\n\x04\x62\x65ta\x18\x03 \x02(\x01\x12\x11\n\tsizeBytes\x18\x04 \x02(\x05\x12\x0c\n\x04path\x18\x05 \x02(\t\x12\x10\n\x08\x62\x61seName\x18\x06 \x02(\t\x12\x15\n\rdataSourceIdx\x18\x07 \x02(\x05\x12\x16\n\x0e\x61\x63tiveFileName\x18\x08 \x02(\t\"\x96\x03\n\x0cSystemStatus\x12&\n\nstreamMode\x18\x01 \x02(\x0e\x32\x12.allego.StreamMode\x12\x14\n\x0c\x62\x61seSampFreq\x18\x02 \x02(\x01\x12\x12\n\nnumPriSigs\x18\x03 \x02(\x05\x12\x12\n\nnumAuxSigs\x18\x04 \x02(\x05\x12\x12\n\nnumDinSigs\x18\x05 \x02(\x05\x12\x13\n\x0bnumDoutSigs\x18\x06 \x02(\x05\x12\x13\n\x0btStampRange\x18\x07 \x03(\x03\x12\x0e\n\x06tRange\x18\x08 \x03(\x01\x12\x11\n\tstreamDur\x18\t \x02(\x01\x12\x14\n\x0cmeanChunkDur\x18\n \x02(\x01\x12\x1c\n\x14meanHardwareMemLevel\x18\x0b \x02(\x02\x12\x1b\n\x13maxHardwareMemLevel\x18\x0c \x02(\x02\x12\x1b\n\x13minHardwareMemLevel\x18\r \x02(\x02\x12\x1c\n\x14lastHardwareMemLevel\x18\x0e \x02(\x02\x12\x19\n\x11meanStreamLoopDur\x18\x0f \x02(\x01\x12\x18\n\x10streamEfficiency\x18\x10 \x02(\x01\"\xd8\x02\n\x11LogsysPcacheReply\x12\x0c\n\x04name\x18\x01 \x02(\t\x12\x10\n\x08sampFreq\x18\x02 \x02(\x01\x12\x12\n\npersistDur\x18\x03 \x02(\x01\x12\x18\n\x10minNumDatablocks\x18\x04 \x02(\x05\x12\x11\n\tsizeBytes\x18\x05 \x02(\x03\x12 \n\x18totalDatablocksProcessed\x18\x06 \x02(\x04\x12\x16\n\x0enumTimeSamples\x18\x07 \x02(\x03\x12\x1f\n\x17\x61llTimeMeanDatablockDur\x18\x08 \x02(\x01\x12\x15\n\rnumDataBlocks\x18\t \x02(\x05\x12\x0e\n\x06tRange\x18\n \x03(\x01\x12\x0f\n\x07tsRange\x18\x0b \x03(\x03\x12\x12\n\nnumPriSigs\x18\x0c \x02(\x05\x12\x12\n\nnumAuxSigs\x18\r \x02(\x05\x12\x12\n\nnumDinSigs\x18\x0e \x02(\x05\x12\x13\n\x0bnumDoutSigs\x18\x0f \x02(\x05\"5\n\x10TriggerModeState\x12!\n\x04mode\x18\x01 \x02(\x0e\x32\x13.allego.TriggerMode\"*\n\x12LoadAllMosiRequest\x12\x14\n\x0cregisterVals\x18\x01 \x03(\x05\"\x15\n\x13TransmitMosiRequest\"5\n\x0f\x44umpMisoRequest\x12\x10\n\x08nSamples\x18\x01 \x02(\x05\x12\x10\n\x08\x66ileName\x18\x02 \x02(\t\"\x99\x03\n\x15SinapsStatusRegisters\x12\x18\n\x10\x63\x61librationState\x18\x01 \x02(\x08\x12\x1b\n\x13\x63\x61librationProgress\x18\x02 \x02(\x01\x12\x1d\n\x15numActivePixelsShank0\x18\x03 \x02(\x05\x12\x1d\n\x15numActivePixelsShank1\x18\x04 \x02(\x05\x12\x1d\n\x15numActivePixelsShank2\x18\x05 \x02(\x05\x12\x1d\n\x15numActivePixelsShank3\x18\x06 \x02(\x05\x12\x0f\n\x07vRefFFA\x18\x07 \x02(\x01\x12\x0f\n\x07vRefFFB\x18\x08 \x02(\x01\x12\x0f\n\x07vRefFFC\x18\t \x02(\x01\x12\x0f\n\x07vRefFFD\x18\n \x02(\x01\x12\x10\n\x08isError0\x18\x0b \x02(\x08\x12\x10\n\x08isError1\x18\x0c \x02(\x08\x12\x10\n\x08isError2\x18\r \x02(\x08\x12\x10\n\x08isError3\x18\x0e \x02(\x08\x12\x13\n\x0bhostCounter\x18\x0f \x02(\x05\x12\x13\n\x0b\x66pgaCounter\x18\x10 \x02(\x05\x12\x17\n\x0f\x66irmwareVersion\x18\x11 \x02(\t\"%\n\x12\x46lashSinapsRequest\x12\x0f\n\x07\x62itfile\x18\x01 \x02(\t\"3\n\x0cHALdashboard\x12#\n\x04mode\x18\x01 \x02(\x0e\x32\x15.allego.AllegoHALmode\"\xbc\x06\n\nStimParams\x12$\n\tstimShape\x18\x01 \x02(\x0e\x32\x11.allego.StimShape\x12*\n\x0cstimPolarity\x18\x02 \x02(\x0e\x32\x14.allego.StimPolarity\x12\x1a\n\x12\x66irstPhaseDuration\x18\x03 \x02(\x01\x12\x1b\n\x13secondPhaseDuration\x18\x04 \x02(\x01\x12\x17\n\x0finterphaseDelay\x18\x05 \x02(\x01\x12\x1b\n\x13\x66irstPhaseAmplitude\x18\x06 \x02(\x01\x12\x1c\n\x14secondPhaseAmplitude\x18\x07 \x02(\x01\x12\x17\n\x0f\x62\x61selineVoltage\x18\x08 \x02(\x01\x12:\n\x12triggerEdgeOrLevel\x18\n \x02(\x0e\x32\x1e.allego.StimTriggerEdgeOrLevel\x12\x36\n\x10triggerHighOrLow\x18\x0b \x02(\x0e\x32\x1c.allego.StimTriggerHighOrLow\x12\x0f\n\x07\x65nabled\x18\x0c \x02(\x08\x12\x18\n\x10postTriggerDelay\x18\r \x02(\x01\x12.\n\x0cpulseOrTrain\x18\x0e \x02(\x0e\x32\x18.allego.StimPulseOrTrain\x12\x1a\n\x12numberOfStimPulses\x18\x0f \x02(\x05\x12\x18\n\x10pulseTrainPeriod\x18\x10 \x02(\x01\x12\x18\n\x10refractoryPeriod\x18\x11 \x02(\x01\x12\x18\n\x10preStimAmpSettle\x18\x12 \x02(\x01\x12\x19\n\x11postStimAmpSettle\x18\x13 \x02(\x01\x12\x19\n\x11maintainAmpSettle\x18\x14 \x02(\x08\x12\x17\n\x0f\x65nableAmpSettle\x18\x15 \x02(\x08\x12\x1d\n\x15postStimChargeRecovOn\x18\x16 \x02(\x01\x12\x1e\n\x16postStimChargeRecovOff\x18\x17 \x02(\x01\x12\x1c\n\x14\x65nableChargeRecovery\x18\x18 \x02(\x08\x12\x1f\n\x17triggerSourceIsKeypress\x18\x19 \x02(\x08\x12\x18\n\x10triggerSourceIdx\x18\x1a \x02(\x05\x12\x16\n\x0estimSysChanIdx\x18\x1b \x02(\x05\"\x89\x01\n\x0fStimParamsReply\x12\x33\n\x06params\x18\x01 \x03(\x0b\x32#.allego.StimParamsReply.ParamsEntry\x1a\x41\n\x0bParamsEntry\x12\x0b\n\x03key\x18\x01 \x01(\x05\x12!\n\x05value\x18\x02 \x01(\x0b\x32\x12.allego.StimParams:\x02\x38\x01\">\n\x18ManualStimTriggerRequest\x12\x0f\n\x07trigger\x18\x01 \x02(\x05\x12\x11\n\ttriggerOn\x18\x02 \x02(\x08\"1\n\x1eManualStimTriggerToggleRequest\x12\x0f\n\x07trigger\x18\x01 \x02(\x05\"5\n\x0fStimStepMessage\x12\"\n\x08stimStep\x18\x01 \x02(\x0e\x32\x10.allego.StimStep*!\n\nStreamMode\x12\t\n\x05S_OFF\x10\x00\x12\x08\n\x04S_ON\x10\x01*!\n\nRecordMode\x12\t\n\x05R_OFF\x10\x00\x12\x08\n\x04R_ON\x10\x01*\x82\x04\n\x0c\x42\x61\x63kboneMode\x12\x10\n\x0cSMARTBOX_PRO\x10\x00\x12\x19\n\x15SMARTBOX_SIM_GEN_SINE\x10\x01\x12\x1b\n\x17SMARTBOX_SIM_GEN_SPIKES\x10\x02\x12\x1b\n\x17SMARTBOX_SIM_DATASOURCE\x10\x03\x12\x13\n\x0fOPEN_EPHYS_USB3\x10\x04\x12#\n\x1fINTAN_RECORDING_CONTROLLER_1024\x10\x05\x12\x14\n\x10SMARTBOX_CLASSIC\x10\x06\x12\"\n\x1eINTAN_RECORDING_CONTROLLER_512\x10\x07\x12\x13\n\x0fOPEN_EPHYS_USB2\x10\x08\x12\x0e\n\nINTAN_USB2\x10\t\x12 \n\x1cSMARTBOX_SIM_GEN_SINE_MAPPED\x10\n\x12#\n\x1fSMARTBOX_SIM_GEN_SINE_HIGH_FREQ\x10\x0b\x12$\n SMARTBOX_SIM_GEN_SINE_MULTI_BAND\x10\x0c\x12\x1b\n\x17SMARTBOX_PRO_SINAPS_256\x10\r\x12\x1c\n\x18SMARTBOX_PRO_SINAPS_1024\x10\x0e\x12\x10\n\x0cXDAQ_ONE_REC\x10\x0f\x12\x11\n\rXDAQ_ONE_STIM\x10\x10\x12\x11\n\rXDAQ_CORE_REC\x10\x11\x12\x12\n\x0eXDAQ_CORE_STIM\x10\x12*,\n\x07\x44IOMode\x12\n\n\x06manual\x10\x00\x12\n\n\x06\x65vents\x10\x01\x12\t\n\x05gated\x10\x02*O\n\x0bTriggerMode\x12\x0b\n\x07T_DIN_0\x10\x00\x12\x0b\n\x07T_DIN_1\x10\x01\x12\x0c\n\x08T_DOUT_0\x10\x02\x12\x0c\n\x08T_DOUT_1\x10\x03\x12\n\n\x06T_NONE\x10\x04*q\n\rAllegoHALmode\x12\x11\n\rA_HAL_GENERIC\x10\x00\x12\x13\n\x0f\x41_HAL_SPIKESORT\x10\x01\x12\x14\n\x10\x41_HAL_MULTISCALE\x10\x02\x12\"\n\x1e\x41_HAL_MULTISCALE_BIDIRECTIONAL\x10\x03*W\n\tStimShape\x12\x0c\n\x08\x42IPHASIC\x10\x00\x12\x1d\n\x19\x42IPHASIC_INTERPHASE_DELAY\x10\x01\x12\r\n\tTRIPHASIC\x10\x02\x12\x0e\n\nMONOPHASIC\x10\x03*4\n\x0cStimPolarity\x12\x12\n\x0e\x43\x41THODIC_FIRST\x10\x00\x12\x10\n\x0c\x41NODIC_FIRST\x10\x01*3\n\x16StimTriggerEdgeOrLevel\x12\x0b\n\x07ST_EDGE\x10\x00\x12\x0c\n\x08ST_LEVEL\x10\x01*/\n\x14StimTriggerHighOrLow\x12\x0b\n\x07ST_HIGH\x10\x00\x12\n\n\x06ST_LOW\x10\x01*5\n\x10StimPulseOrTrain\x12\x10\n\x0cSINGLE_PULSE\x10\x00\x12\x0f\n\x0bPULSE_TRAIN\x10\x01*\x90\x02\n\x08StimStep\x12\x13\n\x0fStimStepSizeMin\x10\x00\x12\x14\n\x10StimStepSize10nA\x10\x01\x12\x14\n\x10StimStepSize20nA\x10\x02\x12\x14\n\x10StimStepSize50nA\x10\x03\x12\x15\n\x11StimStepSize100nA\x10\x04\x12\x15\n\x11StimStepSize200nA\x10\x05\x12\x15\n\x11StimStepSize500nA\x10\x06\x12\x13\n\x0fStimStepSize1uA\x10\x07\x12\x13\n\x0fStimStepSize2uA\x10\x08\x12\x13\n\x0fStimStepSize5uA\x10\t\x12\x14\n\x10StimStepSize10uA\x10\n\x12\x13\n\x0fStimStepSizeMax\x10\x0b\x32\x9b)\n\nAllegoCore\x12?\n\x0bHealthcheck\x12\x17.allego.StandardRequest\x1a\x15.allego.StandardReply\"\x00\x12:\n\x07Restart\x12\x16.allego.RestartRequest\x1a\x15.allego.StandardReply\"\x00\x12\x39\n\x05\x43lose\x12\x17.allego.StandardRequest\x1a\x15.allego.StandardReply\"\x00\x12J\n\x13GetRadixEnvironment\x12\x17.allego.StandardRequest\x1a\x18.allego.RadixEnvironment\"\x00\x12L\n\x10WorkspaceControl\x12\x1f.allego.WorkspaceControlRequest\x1a\x15.allego.StandardReply\"\x00\x12T\n\x11GetRadiensServers\x12 .allego.GetRadiensServersRequest\x1a\x1b.allego.RadiensServersReply\"\x00\x12j\n\x1bGetStatusPollFieldsToUpdate\x12\'.allego.StatusPollFieldsToUpdateRequest\x1a .allego.StatusPollFieldsToUpdate\"\x00\x12\x46\n\rSetConfigCore\x12\x1c.allego.SetConfigCoreRequest\x1a\x15.allego.StandardReply\"\x00\x12\x45\n\x0fSetProfileState\x12\x19.allego.SetProfileRequest\x1a\x15.allego.StandardReply\"\x00\x12\x46\n\x12SetConfigRecording\x12\x17.allego.ConfigRecording\x1a\x15.allego.StandardReply\"\x00\x12\x43\n\x0eSetStreamState\x12\x18.allego.SetStreamRequest\x1a\x15.allego.StandardReply\"\x00\x12\x43\n\x0eSetRecordState\x12\x18.allego.SetRecordRequest\x1a\x15.allego.StandardReply\"\x00\x12\x45\n\x0cSetDIOEvents\x12\x1c.allego.DIOModeEventsRequest\x1a\x15.allego.StandardReply\"\x00\x12\x45\n\x0cSetDIOManual\x12\x1c.allego.DIOModeManualRequest\x1a\x15.allego.StandardReply\"\x00\x12?\n\x0bSetDIOGated\x12\x17.allego.StandardRequest\x1a\x15.allego.StandardReply\"\x00\x12=\n\nSetDACGain\x12\x16.allego.DACGainRequest\x1a\x15.allego.StandardReply\"\x00\x12\x41\n\x0cSetDACStream\x12\x18.allego.DACStreamRequest\x1a\x15.allego.StandardReply\"\x00\x12;\n\tSetDACOff\x12\x15.allego.DACOffRequest\x1a\x15.allego.StandardReply\"\x00\x12\x46\n\x0eSetDACHighPass\x12\x1b.allego.DACHighPassRegister\x1a\x15.allego.StandardReply\"\x00\x12\x42\n\x0bSetSimPorts\x12\x1a.allego.SetSimPortsRequest\x1a\x15.allego.StandardReply\"\x00\x12\x46\n\rSetMuxChannel\x12\x1c.allego.SetMuxChannelRequest\x1a\x15.allego.StandardReply\"\x00\x12\x43\n\x0eSetTriggerMode\x12\x18.allego.TriggerModeState\x1a\x15.allego.StandardReply\"\x00\x12\x46\n\rSetPotVoltage\x12\x1c.allego.SetPotVoltageRequest\x1a\x15.allego.StandardReply\"\x00\x12\x42\n\x0bSetPotRange\x12\x1a.allego.SetPotRangeRequest\x1a\x15.allego.StandardReply\"\x00\x12@\n\nSetPotMode\x12\x19.allego.SetPotModeRequest\x1a\x15.allego.StandardReply\"\x00\x12L\n\x10SetPotCellEnable\x12\x1f.allego.SetPotCellEnableRequest\x1a\x15.allego.StandardReply\"\x00\x12\x42\n\x0bSetDSPGroup\x12\x1a.allego.SetDSPGroupRequest\x1a\x15.allego.StandardReply\"\x00\x12<\n\rSetStimParams\x12\x12.allego.StimParams\x1a\x15.allego.StandardReply\"\x00\x12\x43\n\rGetStimParams\x12\x17.allego.StandardRequest\x1a\x17.allego.StimParamsReply\"\x00\x12?\n\x0bSetStimStep\x12\x17.allego.StimStepMessage\x1a\x15.allego.StandardReply\"\x00\x12\x41\n\x0bGetStimStep\x12\x17.allego.StandardRequest\x1a\x17.allego.StimStepMessage\"\x00\x12N\n\x11ManualStimTrigger\x12 .allego.ManualStimTriggerRequest\x1a\x15.allego.StandardReply\"\x00\x12]\n\x1aSetManualStimTriggerToggle\x12&.allego.ManualStimTriggerToggleRequest\x1a\x15.allego.StandardReply\"\x00\x12:\n\tGetConfig\x12\x17.allego.StandardRequest\x1a\x12.allego.ConfigCore\"\x00\x12H\n\x0cGetWorkspace\x12\x1b.allego.GetWorkspaceRequest\x1a\x19.allego.GetWorkspaceReply\"\x00\x12H\n\x12GetConfigRecording\x12\x17.allego.StandardRequest\x1a\x17.allego.ConfigRecording\"\x00\x12>\n\tGetStatus\x12\x17.allego.StandardRequest\x1a\x16.allego.BackboneStatus\"\x00\x12H\n\x12GetConfigAndStatus\x12\x17.allego.StandardRequest\x1a\x17.allego.ConfigAndStatus\"\x00\x12O\n\x13GetDataSourceParams\x12\x1c.allego.SignalGroupIDRequest\x1a\x18.allego.DataSourceParams\"\x00\x12\x42\n\x11GetIntanImpedance\x12\x18.allego.ImpedanceRequest\x1a\x11.allego.Impedance\"\x00\x12?\n\x0bGetDSPGroup\x12\x1c.allego.SignalGroupIDRequest\x1a\x10.allego.DSPGroup\"\x00\x12\x42\n\tGetDIOReg\x12\x17.allego.StandardRequest\x1a\x1a.allego.DigitalOutRegister\"\x00\x12\x41\n\tGetDACReg\x12\x17.allego.StandardRequest\x1a\x19.allego.AnalogOutRegister\"\x00\x12<\n\tGetSerial\x12\x17.allego.StandardRequest\x1a\x14.allego.SerialNumber\"\x00\x12\x45\n\x0eGetTriggerMode\x12\x17.allego.StandardRequest\x1a\x18.allego.TriggerModeState\"\x00\x12\x42\n\x0bGetADCLevel\x12\x17.allego.StandardRequest\x1a\x18.allego.GetADCLevelReply\"\x00\x12\x45\n\x0bReadWireOut\x12\x1a.allego.ReadWireOutRequest\x1a\x18.allego.ReadWireOutReply\"\x00\x12O\n\x0fListSensorSpecs\x12\x1c.allego.SignalGroupIDRequest\x1a\x1c.allego.ListSensorSpecsReply\"\x00\x12N\n\x11GetSignalGroupIDs\x12\x17.allego.StandardRequest\x1a\x1e.allego.GetSignalGroupIDsReply\"\x00\x12H\n\x0eGetSorterIDMap\x12\x17.allego.StandardRequest\x1a\x1b.allego.GetSorterIDMapReply\"\x00\x12N\n\x11GetSpikeSorterIDs\x12\x17.allego.StandardRequest\x1a\x1e.allego.GetSpikeSorterIDsReply\"\x00\x12\x45\n\x0eGetSignalGroup\x12\x1c.allego.SignalGroupIDRequest\x1a\x13.allego.SignalGroup\"\x00\x12N\n\x11UpdateSignalGroup\x12 .allego.UpdateSignalGroupRequest\x1a\x15.allego.StandardReply\"\x00\x12;\n\tScanPorts\x12\x17.allego.StandardRequest\x1a\x13.allego.SignalGroup\"\x00\x12>\n\tSetSensor\x12\x18.allego.SetSensorRequest\x1a\x15.allego.StandardReply\"\x00\x12T\n\x14SetSensorPositionTcs\x12#.allego.SetSensorPositionTcsRequest\x1a\x15.allego.StandardReply\"\x00\x12R\n\x13SetSitePositionsTcs\x12\".allego.SetSitePositionsTcsRequest\x1a\x15.allego.StandardReply\"\x00\x12O\n\x13GetDataSourceStatus\x12\x1c.allego.SignalGroupIDRequest\x1a\x18.allego.DataSourceStatus\"\x00\x12H\n\x0c\x46\x65\x61tureStart\x12\x1f.allego.FeatureStartStopRequest\x1a\x15.allego.StandardReply\"\x00\x12G\n\x0b\x46\x65\x61tureStop\x12\x1f.allego.FeatureStartStopRequest\x1a\x15.allego.StandardReply\"\x00\x12=\n\nGetPrivacy\x12\x17.allego.StandardRequest\x1a\x14.allego.PrivacyReply\"\x00\x12@\n\nSetPrivacy\x12\x19.allego.SetPrivacyRequest\x1a\x15.allego.StandardReply\"\x00\x12\x42\n\x0bLoadAllMosi\x12\x1a.allego.LoadAllMosiRequest\x1a\x15.allego.StandardReply\"\x00\x12\x44\n\x0cTransmitMosi\x12\x1b.allego.TransmitMosiRequest\x1a\x15.allego.StandardReply\"\x00\x12<\n\x08\x44umpMiso\x12\x17.allego.DumpMisoRequest\x1a\x15.allego.StandardReply\"\x00\x12T\n\x18GetSinapsStatusRegisters\x12\x17.allego.StandardRequest\x1a\x1d.allego.SinapsStatusRegisters\"\x00\x12\x42\n\x0b\x46lashSinaps\x12\x1a.allego.FlashSinapsRequest\x1a\x15.allego.StandardReply\"\x00\x12L\n\x16GetOrCreateEventViewer\x12\x15.allego.EventViewerID\x1a\x19.allego.EventViewerConfig\"\x00\x12G\n\x11UpdateEventViewer\x12\x19.allego.EventViewerConfig\x1a\x15.allego.StandardReply\"\x00\x12T\n\x15ListEventViewerEvents\x12\x15.allego.EventViewerID\x1a\".allego.ListEventViewerEventsReply\"\x00\x12U\n\x13GetEventViewerEvent\x12\".allego.GetEventViewerEventRequest\x1a\x18.allego.EventViewerEvent\"\x00\x12L\n\x10ListEventViewers\x12\x17.allego.StandardRequest\x1a\x1d.allego.ListEventViewersReply\"\x00\x12\x42\n\x0fGetHALdashboard\x12\x17.allego.StandardRequest\x1a\x14.allego.HALdashboard\"\x00\x32\xe4\x02\n\x07Pcache1\x12?\n\x0bHealthcheck\x12\x17.allego.StandardRequest\x1a\x15.allego.StandardReply\"\x00\x12@\n\rGetHDSnapshot\x12\x19.allego.HDSnapshotRequest\x1a\x12.allego.HDSnapshot\"\x00\x12J\n\x15GetHDSnapshotFromHead\x12\x1a.allego.HDSnapshotRequest2\x1a\x13.allego.HDSnapshot2\"\x00\x12=\n\nGetSignals\x12\x19.allego.GetSignalsRequest\x1a\x12.allego.RawSignals\"\x00\x12K\n\x12SetTimeRangeToHead\x12\x1c.allego.SignalGroupIDRequest\x1a\x15.allego.StandardReply\"\x00\x32\x8d\x04\n\x04Kpi1\x12?\n\x0bHealthcheck\x12\x17.allego.StandardRequest\x1a\x15.allego.StandardReply\"\x00\x12H\n\rKpiGetMetrics\x12\x15.allego.KpiMetricsReq\x1a\x1e.allego.KpiBundlePacketMetrics\"\x00\x12\x45\n\x0cGetKpiStatus\x12\x1b.allego.GetKpiStatusRequest\x1a\x16.allego.KpiStatusReply\"\x00\x12K\n\x0bSetKpiParam\x12#.allego.SpikeSorterSetParamsRequest\x1a\x15.allego.StandardReply\"\x00\x12S\n\x0bGetKpiParam\x12\x19.allego.DataSourceRequest\x1a\'.allego.GetSpikeSorterParamCommandReply\"\x00\x12I\n\x12SetKpiUpdatePeriod\x12\x1a.allego.SetKpiParamRequest\x1a\x15.allego.StandardReply\"\x00\x12\x46\n\x0fSetKpiPacketDur\x12\x1a.allego.SetKpiParamRequest\x1a\x15.allego.StandardReply\"\x00\x32\xb6\t\n\x08Neurons1\x12?\n\x0bHealthcheck\x12\x17.allego.StandardRequest\x1a\x15.allego.StandardReply\"\x00\x12P\n\x12SpikeSorterCommand\x12!.allego.SpikeSorterCommandRequest\x1a\x15.allego.StandardReply\"\x00\x12R\n\x13SpikeSorterSetParam\x12\".allego.SpikeSorterSetParamRequest\x1a\x15.allego.StandardReply\"\x00\x12T\n\x14SpikeSorterSetParams\x12#.allego.SpikeSorterSetParamsRequest\x1a\x15.allego.StandardReply\"\x00\x12\x64\n\x13SpikeSorterGetParam\x12\".allego.SpikeSorterStandardRequest\x1a\'.allego.GetSpikeSorterParamCommandReply\"\x00\x12U\n\x13SpikeSorterGetState\x12\".allego.SpikeSorterStandardRequest\x1a\x18.allego.SpikeSorterState\"\x00\x12\x65\n\x17SpikeSorterGetDashboard\x12\".allego.SpikeSorterStandardRequest\x1a$.allego.SpikeSorterGetDashboardReply\"\x00\x12i\n\x18SpikeSorterGetRasterData\x12\'.allego.SpikeSorterGetRasterDataRequest\x1a\".allego.SpikeSorterRasterDataReply\"\x00\x12\x61\n\x1a\x42iointerfaceGetSpikesDense\x12\x1e.allego.SpikesGetSpikesRequest\x1a!.allego.SpikesSpikeDataDenseReply\"\x00\x12\x66\n\x16\x42iointerfaceGetNeurons\x12%.allego.BiointerfaceGetNeuronsRequest\x1a#.allego.BiointerfaceGetNeuronsReply\"\x00\x12p\n\"BiointerfaceSeekEndSpikeTimestamps\x12\x31.allego.BiointerfaceSeekEndSpikeTimestampsRequest\x1a\x15.allego.StandardReply\"\x00\x12N\n\rSpikesGetSpec\x12\".allego.SpikeSorterStandardRequest\x1a\x17.allego.SpikesSpecReply\"\x00\x12Q\n\x0f\x42iointerfaceViz\x12\x1e.allego.BiointerfaceVizRequest\x1a\x1c.allego.BiointerfaceVizReply\"\x00\x42\x15Z\x13internal/radix/grpc')
 
 _builder.BuildMessageAndEnumDescriptors(DESCRIPTOR, globals())
 _builder.BuildTopDescriptorsAndMessages(DESCRIPTOR, 'allegoserver_pb2', globals())
 if _descriptor._USE_C_DESCRIPTORS == False:
 
   DESCRIPTOR._options = None
   DESCRIPTOR._serialized_options = b'Z\023internal/radix/grpc'
   _STIMPARAMSREPLY_PARAMSENTRY._options = None
   _STIMPARAMSREPLY_PARAMSENTRY._serialized_options = b'8\001'
-  _STREAMMODE._serialized_start=6513
-  _STREAMMODE._serialized_end=6546
-  _RECORDMODE._serialized_start=6548
-  _RECORDMODE._serialized_end=6581
-  _BACKBONEMODE._serialized_start=6584
-  _BACKBONEMODE._serialized_end=7098
-  _DIOMODE._serialized_start=7100
-  _DIOMODE._serialized_end=7144
-  _TRIGGERMODE._serialized_start=7146
-  _TRIGGERMODE._serialized_end=7225
-  _ALLEGOHALMODE._serialized_start=7227
-  _ALLEGOHALMODE._serialized_end=7340
-  _STIMSHAPE._serialized_start=7342
-  _STIMSHAPE._serialized_end=7429
-  _STIMPOLARITY._serialized_start=7431
-  _STIMPOLARITY._serialized_end=7483
-  _STIMTRIGGEREDGEORLEVEL._serialized_start=7485
-  _STIMTRIGGEREDGEORLEVEL._serialized_end=7536
-  _STIMTRIGGERHIGHORLOW._serialized_start=7538
-  _STIMTRIGGERHIGHORLOW._serialized_end=7585
-  _STIMPULSEORTRAIN._serialized_start=7587
-  _STIMPULSEORTRAIN._serialized_end=7640
-  _STIMSTEP._serialized_start=7643
-  _STIMSTEP._serialized_end=7915
+  _STREAMMODE._serialized_start=6564
+  _STREAMMODE._serialized_end=6597
+  _RECORDMODE._serialized_start=6599
+  _RECORDMODE._serialized_end=6632
+  _BACKBONEMODE._serialized_start=6635
+  _BACKBONEMODE._serialized_end=7149
+  _DIOMODE._serialized_start=7151
+  _DIOMODE._serialized_end=7195
+  _TRIGGERMODE._serialized_start=7197
+  _TRIGGERMODE._serialized_end=7276
+  _ALLEGOHALMODE._serialized_start=7278
+  _ALLEGOHALMODE._serialized_end=7391
+  _STIMSHAPE._serialized_start=7393
+  _STIMSHAPE._serialized_end=7480
+  _STIMPOLARITY._serialized_start=7482
+  _STIMPOLARITY._serialized_end=7534
+  _STIMTRIGGEREDGEORLEVEL._serialized_start=7536
+  _STIMTRIGGEREDGEORLEVEL._serialized_end=7587
+  _STIMTRIGGERHIGHORLOW._serialized_start=7589
+  _STIMTRIGGERHIGHORLOW._serialized_end=7636
+  _STIMPULSEORTRAIN._serialized_start=7638
+  _STIMPULSEORTRAIN._serialized_end=7691
+  _STIMSTEP._serialized_start=7694
+  _STIMSTEP._serialized_end=7966
   _RESTARTREQUEST._serialized_start=101
   _RESTARTREQUEST._serialized_end=153
   _SETPROFILEREQUEST._serialized_start=155
   _SETPROFILEREQUEST._serialized_end=213
   _LOGSYSTEMREQUEST._serialized_start=216
   _LOGSYSTEMREQUEST._serialized_end=577
   _LOGSYSTEMREQUEST_LOGSYSTEMMODE._serialized_start=377
@@ -151,18 +151,20 @@
   _STIMPARAMS._serialized_end=6252
   _STIMPARAMSREPLY._serialized_start=6255
   _STIMPARAMSREPLY._serialized_end=6392
   _STIMPARAMSREPLY_PARAMSENTRY._serialized_start=6327
   _STIMPARAMSREPLY_PARAMSENTRY._serialized_end=6392
   _MANUALSTIMTRIGGERREQUEST._serialized_start=6394
   _MANUALSTIMTRIGGERREQUEST._serialized_end=6456
-  _STIMSTEPMESSAGE._serialized_start=6458
-  _STIMSTEPMESSAGE._serialized_end=6511
-  _ALLEGOCORE._serialized_start=7918
-  _ALLEGOCORE._serialized_end=13098
-  _PCACHE1._serialized_start=13101
-  _PCACHE1._serialized_end=13457
-  _KPI1._serialized_start=13460
-  _KPI1._serialized_end=13985
-  _NEURONS1._serialized_start=13988
-  _NEURONS1._serialized_end=15194
+  _MANUALSTIMTRIGGERTOGGLEREQUEST._serialized_start=6458
+  _MANUALSTIMTRIGGERTOGGLEREQUEST._serialized_end=6507
+  _STIMSTEPMESSAGE._serialized_start=6509
+  _STIMSTEPMESSAGE._serialized_end=6562
+  _ALLEGOCORE._serialized_start=7969
+  _ALLEGOCORE._serialized_end=13244
+  _PCACHE1._serialized_start=13247
+  _PCACHE1._serialized_end=13603
+  _KPI1._serialized_start=13606
+  _KPI1._serialized_end=14131
+  _NEURONS1._serialized_start=14134
+  _NEURONS1._serialized_end=15340
 # @@protoc_insertion_point(module_scope)
```

### Comparing `radiens-1.0.5/radiens/grpc_radiens/allegoserver_pb2_grpc.py` & `radiens-1.0.6/radiens/grpc_radiens/allegoserver_pb2_grpc.py`

 * *Files 0% similar despite different names*

```diff
@@ -174,14 +174,19 @@
                 response_deserializer=allegoserver__pb2.StimStepMessage.FromString,
                 )
         self.ManualStimTrigger = channel.unary_unary(
                 '/allego.AllegoCore/ManualStimTrigger',
                 request_serializer=allegoserver__pb2.ManualStimTriggerRequest.SerializeToString,
                 response_deserializer=common__pb2.StandardReply.FromString,
                 )
+        self.SetManualStimTriggerToggle = channel.unary_unary(
+                '/allego.AllegoCore/SetManualStimTriggerToggle',
+                request_serializer=allegoserver__pb2.ManualStimTriggerToggleRequest.SerializeToString,
+                response_deserializer=common__pb2.StandardReply.FromString,
+                )
         self.GetConfig = channel.unary_unary(
                 '/allego.AllegoCore/GetConfig',
                 request_serializer=common__pb2.StandardRequest.SerializeToString,
                 response_deserializer=allegoserver__pb2.ConfigCore.FromString,
                 )
         self.GetWorkspace = channel.unary_unary(
                 '/allego.AllegoCore/GetWorkspace',
@@ -574,14 +579,20 @@
 
     def ManualStimTrigger(self, request, context):
         """Missing associated documentation comment in .proto file."""
         context.set_code(grpc.StatusCode.UNIMPLEMENTED)
         context.set_details('Method not implemented!')
         raise NotImplementedError('Method not implemented!')
 
+    def SetManualStimTriggerToggle(self, request, context):
+        """Missing associated documentation comment in .proto file."""
+        context.set_code(grpc.StatusCode.UNIMPLEMENTED)
+        context.set_details('Method not implemented!')
+        raise NotImplementedError('Method not implemented!')
+
     def GetConfig(self, request, context):
         """Getters
         """
         context.set_code(grpc.StatusCode.UNIMPLEMENTED)
         context.set_details('Method not implemented!')
         raise NotImplementedError('Method not implemented!')
 
@@ -983,14 +994,19 @@
                     response_serializer=allegoserver__pb2.StimStepMessage.SerializeToString,
             ),
             'ManualStimTrigger': grpc.unary_unary_rpc_method_handler(
                     servicer.ManualStimTrigger,
                     request_deserializer=allegoserver__pb2.ManualStimTriggerRequest.FromString,
                     response_serializer=common__pb2.StandardReply.SerializeToString,
             ),
+            'SetManualStimTriggerToggle': grpc.unary_unary_rpc_method_handler(
+                    servicer.SetManualStimTriggerToggle,
+                    request_deserializer=allegoserver__pb2.ManualStimTriggerToggleRequest.FromString,
+                    response_serializer=common__pb2.StandardReply.SerializeToString,
+            ),
             'GetConfig': grpc.unary_unary_rpc_method_handler(
                     servicer.GetConfig,
                     request_deserializer=common__pb2.StandardRequest.FromString,
                     response_serializer=allegoserver__pb2.ConfigCore.SerializeToString,
             ),
             'GetWorkspace': grpc.unary_unary_rpc_method_handler(
                     servicer.GetWorkspace,
@@ -1738,14 +1754,31 @@
         return grpc.experimental.unary_unary(request, target, '/allego.AllegoCore/ManualStimTrigger',
             allegoserver__pb2.ManualStimTriggerRequest.SerializeToString,
             common__pb2.StandardReply.FromString,
             options, channel_credentials,
             insecure, call_credentials, compression, wait_for_ready, timeout, metadata)
 
     @staticmethod
+    def SetManualStimTriggerToggle(request,
+            target,
+            options=(),
+            channel_credentials=None,
+            call_credentials=None,
+            insecure=False,
+            compression=None,
+            wait_for_ready=None,
+            timeout=None,
+            metadata=None):
+        return grpc.experimental.unary_unary(request, target, '/allego.AllegoCore/SetManualStimTriggerToggle',
+            allegoserver__pb2.ManualStimTriggerToggleRequest.SerializeToString,
+            common__pb2.StandardReply.FromString,
+            options, channel_credentials,
+            insecure, call_credentials, compression, wait_for_ready, timeout, metadata)
+
+    @staticmethod
     def GetConfig(request,
             target,
             options=(),
             channel_credentials=None,
             call_credentials=None,
             insecure=False,
             compression=None,
```

### Comparing `radiens-1.0.5/radiens/grpc_radiens/biointerface_pb2.py` & `radiens-1.0.6/radiens/grpc_radiens/biointerface_pb2.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/grpc_radiens/common_pb2.py` & `radiens-1.0.6/radiens/grpc_radiens/common_pb2.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/grpc_radiens/datasource_pb2.py` & `radiens-1.0.6/radiens/grpc_radiens/datasource_pb2.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/grpc_radiens/radiens_dev_pb2.py` & `radiens-1.0.6/radiens/grpc_radiens/radiens_dev_pb2.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/grpc_radiens/radiensserver_pb2.py` & `radiens-1.0.6/radiens/grpc_radiens/radiensserver_pb2.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/grpc_radiens/radiensserver_pb2_grpc.py` & `radiens-1.0.6/radiens/grpc_radiens/radiensserver_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/grpc_radiens/spikesorter_pb2.py` & `radiens-1.0.6/radiens/grpc_radiens/spikesorter_pb2.py`

 * *Files 1% similar despite different names*

```diff
@@ -11,15 +11,15 @@
 _sym_db = _symbol_database.Default()
 
 
 from . import common_pb2 as common__pb2
 from . import biointerface_pb2 as biointerface__pb2
 
 
-DESCRIPTOR = _descriptor_pool.Default().AddSerializedFile(b'\n\x11spikesorter.proto\x12\x06\x61llego\x1a\x0c\x63ommon.proto\x1a\x12\x62iointerface.proto\"\xbc\x02\n\x18SpikeSorterLaunchRequest\x12\x11\n\tdsourceID\x18\x01 \x01(\t\x12&\n\x06source\x18\x02 \x01(\x0b\x32\x16.allego.FileDescriptor\x12\x1b\n\x13maxNumSiteNeighbors\x18\x04 \x01(\x05\x12\x18\n\x10neighborRadiusUm\x18\x05 \x01(\x01\x12/\n\x07variant\x18\x06 \x03(\x0b\x32\x1e.allego.SpikeSorterVariantSpec\x12%\n\x04mode\x18\x07 \x01(\x0e\x32\x17.allego.SpikeSorterMode\x12\x0c\n\x04seed\x18\x08 \x01(\x03\x12\x10\n\x08isAutoOn\x18\t \x01(\x08\x12\x12\n\nnbrPattern\x18\n \x01(\x05\x12\x11\n\tnetworkID\x18\x0b \x01(\t\x12\x0f\n\x07release\x18\x0c \x01(\x03\"\x8a\x01\n\x19SpikeSorterCommandRequest\x12\x15\n\rspikeSorterID\x18\x01 \x02(\t\x12\'\n\x03\x63md\x18\x02 \x02(\x0e\x32\x1a.allego.SpikeSorterCommand\x12-\n\x06subCmd\x18\x03 \x02(\x0e\x32\x1d.allego.SpikeSorterSubCommand\"\x86\x02\n\x10SpikeSorterState\x12+\n\x03sys\x18\x01 \x02(\x0e\x32\x1e.allego.SpikeSorterStateSystem\x12\x14\n\x0c\x66racComplete\x18\x02 \x01(\x01\x12\x0b\n\x03msg\x18\x03 \x01(\t\x12\x12\n\nlaunchTime\x18\x04 \x01(\t\x12\x16\n\x0einitializeTime\x18\x05 \x01(\t\x12\x18\n\x10sessionStartTime\x18\x06 \x01(\t\x12\x17\n\x0fsessionStopTime\x18\x07 \x01(\t\x12\x0c\n\x04isOn\x18\x08 \x01(\x08\x12\x1a\n\x12kernelErrorMessage\x18\t \x01(\t\x12\x19\n\x11kernelWarnMessage\x18\n \x01(\t\"\x81\x01\n\x0cSpkSortIOreq\x12#\n\x04type\x18\x01 \x02(\x0e\x32\x15.allego.SpkSortIOtype\x12\'\n\x06target\x18\x02 \x02(\x0e\x32\x17.allego.SpkSortIOtarget\x12#\n\x04mode\x18\x03 \x02(\x0e\x32\x15.allego.SpkSortIOmode\"i\n\x16SpikeSorterLaunchReply\x12\x15\n\rspikeSorterID\x18\x01 \x02(\t\x12+\n\nsorterType\x18\x02 \x02(\x0e\x32\x17.allego.SpikeSorterType\x12\x0b\n\x03msg\x18\x03 \x01(\t\"0\n\x16GetSpikeSorterIDsReply\x12\x16\n\x0espikeSorterIDs\x18\x01 \x03(\t\"\xa1\x01\n\x1fSpikeSorterGetRasterDataRequest\x12\x15\n\rspikeSorterID\x18\x01 \x02(\t\x12\x12\n\nntvChanIdx\x18\x02 \x03(\x05\x12\x12\n\ntimeWindow\x18\x03 \x02(\x01\x12\x17\n\x0fplotWidthPoints\x18\x04 \x02(\x01\x12\x13\n\x0b\x63omponentID\x18\x05 \x02(\t\x12\x11\n\ttimeRange\x18\x06 \x03(\x01\"\xaa\x01\n\x1aSpikeSorterRasterDataReply\x12<\n\x18spikeTimestampsByChannel\x18\x02 \x03(\x0b\x32\x1a.allego.SpikeTimestampData\x12\x11\n\ttimeRange\x18\x03 \x03(\x01\x12\x16\n\x0etimeStampRange\x18\x04 \x03(\x03\x12\x10\n\x08GPIOData\x18\x05 \x02(\x0c\x12\x11\n\tGPIOShape\x18\x06 \x03(\x05\"3\n\x1aSpikeSorterStandardRequest\x12\x15\n\rspikeSorterID\x18\x01 \x02(\t\"\x86\x03\n\x12SpikeSorterDynamic\x12\x11\n\tisEnabled\x18\x01 \x01(\x08\x12\x43\n\x0fupdatePeriodSec\x18\x02 \x01(\x0b\x32*.allego.SpikeSorterDynamic.UpdatePeriodSec\x12\x35\n\x08\x63riteria\x18\x03 \x01(\x0b\x32#.allego.SpikeSorterDynamic.Criteria\x1a\xa0\x01\n\x08\x43riteria\x12\x31\n\x06\x64\x65tect\x18\x01 \x01(\x0e\x32!.allego.SpikeSorterCriterionLevel\x12\x30\n\x05train\x18\x02 \x01(\x0e\x32!.allego.SpikeSorterCriterionLevel\x12/\n\x04sort\x18\x03 \x01(\x0e\x32!.allego.SpikeSorterCriterionLevel\x1a>\n\x0fUpdatePeriodSec\x12\x0e\n\x06\x64\x65tect\x18\x01 \x01(\x01\x12\r\n\x05train\x18\x02 \x01(\x01\x12\x0c\n\x04sort\x18\x03 \x01(\x01\"\xc5\x01\n\x1cSpikeSorterSetDynamicRequest\x12\x15\n\rspikeSorterID\x18\x01 \x02(\t\x12\x42\n\x07variant\x18\x02 \x03(\x0b\x32\x31.allego.SpikeSorterSetDynamicRequest.VariantEntry\x1aJ\n\x0cVariantEntry\x12\x0b\n\x03key\x18\x01 \x01(\t\x12)\n\x05value\x18\x02 \x01(\x0b\x32\x1a.allego.SpikeSorterDynamic:\x02\x38\x01\"\xd8\x01\n\x1aSpikeSorterGetDynamicReply\x12\x15\n\rspikeSorterID\x18\x01 \x02(\t\x12\x15\n\rrootVariantID\x18\x02 \x02(\t\x12@\n\x07variant\x18\x03 \x03(\x0b\x32/.allego.SpikeSorterGetDynamicReply.VariantEntry\x1aJ\n\x0cVariantEntry\x12\x0b\n\x03key\x18\x01 \x01(\t\x12)\n\x05value\x18\x02 \x01(\x0b\x32\x1a.allego.SpikeSorterDynamic:\x02\x38\x01\"l\n\x1fGetSpikeSorterParamCommandReply\x12\x15\n\rspikeSorterID\x18\x01 \x02(\t\x12\x32\n\x03rec\x18\x02 \x03(\x0b\x32%.allego.SpikeSorterParamCommandRecord\"3\n\x12\x43lusterMapOutliers\x12\x0c\n\x04mild\x18\x01 \x03(\x01\x12\x0f\n\x07\x65xtreme\x18\x02 \x03(\x01\"9\n\x13\x43lusterMapQuartiles\x12\n\n\x02q1\x18\x01 \x02(\x01\x12\n\n\x02q2\x18\x02 \x02(\x01\x12\n\n\x02q3\x18\x03 \x02(\x01\"\x83\x01\n\x0f\x43lusterMapStats\x12\x16\n\x0e\x63\x65ntroidCenter\x18\x01 \x03(\x01\x12\x12\n\ncentroidSd\x18\x02 \x03(\x01\x12\x16\n\x0e\x63\x65ntroidSdNorm\x18\x03 \x02(\x01\x12\x19\n\x11intraCentroidDist\x18\x04 \x03(\x01\x12\x11\n\tnumSpikes\x18\x05 \x02(\x03\"f\n\x10\x43lusterMapRecord\x12\r\n\x05label\x18\x01 \x02(\x05\x12&\n\x05stats\x18\x03 \x02(\x0b\x32\x17.allego.ClusterMapStats\x12\x1b\n\x13numSpikesTrainCache\x18\x04 \x02(\x03\"\xa8\x01\n\x13SpikeSortSiteStatus\x12\x12\n\nntvChanIdx\x18\x01 \x02(\x05\x12\x15\n\rorderedLabels\x18\x02 \x03(\x05\x12)\n\x07\x63luster\x18\x03 \x03(\x0b\x32\x18.allego.ClusterMapRecord\x12\x11\n\tnumSpikes\x18\x04 \x03(\x03\x12\x0c\n\x04zeta\x18\x05 \x03(\x01\x12\x1a\n\x12\x61ggregateSpikeRate\x18\x06 \x02(\x01\"\x8f\x01\n\x14SpikeSortPhaseStatus\x12\x11\n\ttimeRange\x18\x01 \x03(\x01\x12\x12\n\nchunkIndex\x18\x02 \x02(\x03\x12\x14\n\x0cupdatePeriod\x18\x03 \x02(\x01\x12\x0c\n\x04\x62\x65ta\x18\x04 \x02(\x01\x12\x12\n\nisComplete\x18\x05 \x02(\x08\x12\x18\n\x10\x66ractionComplete\x18\x06 \x02(\x01\"*\n\x13SpikeSortNbrIdxList\x12\x13\n\x0bntvChanIdxs\x18\x01 \x03(\x05\"\xf2\x02\n\x16SpikeSorterStatusReply\x12\'\n\x05state\x18\x01 \x02(\x0b\x32\x18.allego.SpikeSorterState\x12\x16\n\x0e\x62iointerfaceID\x18\x03 \x02(\t\x12\x14\n\x0c\x64\x61tasourceID\x18\x04 \x02(\t\x12\x10\n\x08sampFreq\x18\x05 \x02(\x01\x12\x19\n\x11\x65nabledNtvChanIdx\x18\x06 \x03(\x05\x12+\n\x05phase\x18\x07 \x03(\x0b\x32\x1c.allego.SpikeSortPhaseStatus\x12\x30\n\x0b\x65nabledSite\x18\x08 \x03(\x0b\x32\x1b.allego.SpikeSortSiteStatus\x12\x12\n\nprobeYield\x18\t \x02(\x01\x12\x11\n\tsortStats\x18\n \x03(\x01\x12\x1b\n\x13\x64\x61tasourceTimeRange\x18\x0c \x03(\x01\x12\x1d\n\x15\x62iointerfaceTimeRange\x18\r \x03(\x01\x12\x12\n\nnumNeurons\x18\x0f \x02(\x03\"R\n\x1eSpikeSorterStatusVariantsReply\x12\x30\n\x08variants\x18\x01 \x03(\x0b\x32\x1e.allego.SpikeSorterStatusReply\"\xfd\x02\n\x19SpikeSorterClassifierSpec\x12\r\n\x05\x61lpha\x18\x01 \x02(\x01\x12\x11\n\talphaBias\x18\x02 \x02(\x01\x12\x16\n\x0e\x64imOutputLayer\x18\x03 \x02(\x05\x12\x16\n\x0e\x65rrorTolerance\x18\x04 \x02(\x01\x12\x19\n\x11hiddenLayerFactor\x18\x05 \x02(\x01\x12\n\n\x02iD\x18\x06 \x02(\t\x12\x16\n\x0einitBiasStdDev\x18\x07 \x02(\x01\x12\x18\n\x10initWeightStdDev\x18\x08 \x02(\x01\x12\x11\n\tisMasking\x18\t \x02(\x08\x12\x10\n\x08l1lambda\x18\n \x02(\x01\x12\x15\n\rminibatchSize\x18\x0b \x02(\x05\x12\x15\n\rmaxNumSamples\x18\x0c \x02(\x05\x12\x11\n\tnumEpochs\x18\r \x02(\x05\x12\x19\n\x11numSamplesTestMSE\x18\x0e \x02(\x05\x12\x1b\n\x13numConcurrentModels\x18\x0f \x02(\x05\x12\x17\n\x0flabelNoiseLevel\x18\x10 \x02(\x01\"u\n\x16SpikeSorterVariantSpec\x12\n\n\x02iD\x18\x01 \x02(\t\x12\x14\n\x0csiteConfigID\x18\x02 \x02(\t\x12\x39\n\x0e\x63lassifierSpec\x18\x03 \x02(\x0b\x32!.allego.SpikeSorterClassifierSpec\"\xcc\x01\n\x0fSpikeSorterSpec\x12\x15\n\rspikeSorterID\x18\x01 \x02(\t\x12\x14\n\x0c\x64\x61tasourceID\x18\x02 \x02(\t\x12\x16\n\x0e\x62iointerfaceID\x18\x03 \x02(\t\x12\x1b\n\x13maxNumSiteNeighbors\x18\x04 \x02(\x05\x12\x18\n\x10neighborRadiusUm\x18\x05 \x02(\x01\x12/\n\x07variant\x18\x06 \x03(\x0b\x32\x1e.allego.SpikeSorterVariantSpec\x12\x0c\n\x04seed\x18\x08 \x02(\x03\"\xc2\x01\n\x19SpikeSorterGetConfigReply\x12%\n\x04spec\x18\x01 \x02(\x0b\x32\x17.allego.SpikeSorterSpec\x12\x16\n\x0e\x61IupdatePeriod\x18\x02 \x02(\x01\x12\x19\n\x11orderedVariantIDs\x18\x03 \x03(\t\x12\x15\n\rrootVariantID\x18\x04 \x02(\t\x12\x34\n\x0csorterStatus\x18\x06 \x03(\x0b\x32\x1e.allego.SpikeSorterStatusReply\"\x90\x02\n\x15SpikeSorterVizRequest\x12\x15\n\rspikeSorterID\x18\x01 \x02(\t\x12\x11\n\tvariantID\x18\x02 \x02(\t\x12\x12\n\nntvChanIdx\x18\x03 \x03(\x05\x12\x13\n\x0bspikeLabels\x18\x04 \x03(\x05\x12\x34\n\x07vizType\x18\x05 \x02(\x0e\x32#.allego.SpikeSorterVizRequest.VType\x12\x14\n\x0cisYAutoScale\x18\x06 \x02(\x08\x12\x0c\n\x04yLim\x18\x07 \x03(\x01\x12\x0e\n\x06\x66igDir\x18\x08 \x02(\t\x12\x11\n\tnumSpikes\x18\t \x02(\x05\"\'\n\x05VType\x12\x1e\n\x1aVIZ_SPIKESORT_TRAIN_SPIKES\x10\x00\"\xc2\x05\n\x1cSpikeSorterGetDashboardReply\x12\"\n\x0c\x65nabledPorts\x18\x01 \x03(\x0e\x32\x0c.allego.Port\x12\x37\n\x07general\x18\x02 \x02(\x0b\x32&.allego.SpikeSorterDashboardGeneralRec\x12\x33\n\tsiteStats\x18\x03 \x02(\x0b\x32 .allego.IndicoDashboardSiteStats\x12\x46\n\tportStats\x18\x04 \x03(\x0b\x32\x33.allego.SpikeSorterGetDashboardReply.PortStatsEntry\x12\x46\n\tsitePanel\x18\x05 \x03(\x0b\x32\x33.allego.SpikeSorterGetDashboardReply.SitePanelEntry\x12J\n\x0bneuronPanel\x18\x06 \x03(\x0b\x32\x35.allego.SpikeSorterGetDashboardReply.NeuronPanelEntry\x12*\n\x02\x61I\x18\x07 \x01(\x0b\x32\x1e.allego.SpikeSorterDashboardAI\x1aR\n\x0ePortStatsEntry\x12\x0b\n\x03key\x18\x01 \x01(\t\x12/\n\x05value\x18\x02 \x01(\x0b\x32 .allego.IndicoDashboardPortStats:\x02\x38\x01\x1aW\n\x0eSitePanelEntry\x12\x0b\n\x03key\x18\x01 \x01(\t\x12\x34\n\x05value\x18\x02 \x01(\x0b\x32%.allego.IndicoDashboardSiteIndicators:\x02\x38\x01\x1a[\n\x10NeuronPanelEntry\x12\x0b\n\x03key\x18\x01 \x01(\t\x12\x36\n\x05value\x18\x02 \x01(\x0b\x32\'.allego.IndicoDashboardNeuronIndicators:\x02\x38\x01\"\xac\x03\n\x1eSpikeSorterDashboardGeneralRec\x12\'\n\x05state\x18\x01 \x02(\x0b\x32\x18.allego.SpikeSorterState\x12+\n\nsorterType\x18\x02 \x02(\x0e\x32\x17.allego.SpikeSorterType\x12\x10\n\x08sorterID\x18\x03 \x02(\t\x12\x14\n\x0c\x64\x61tasourceID\x18\x04 \x02(\t\x12\x11\n\ttimeRange\x18\x05 \x03(\x01\x12\x15\n\rnumTotalSites\x18\x06 \x02(\x03\x12\x17\n\x0fnumEnabledSites\x18\x07 \x02(\x03\x12\x16\n\x0enumActiveSites\x18\x08 \x02(\x03\x12\x12\n\nnumNeurons\x18\t \x02(\x03\x12\x12\n\nprobeYield\x18\n \x02(\x01\x12\x11\n\tsiteYield\x18\x0b \x02(\x01\x12\x1a\n\x12numSpikesProcessed\x18\x0c \x02(\x03\x12\x18\n\x10numSpikesLabeled\x18\r \x02(\x03\x12\x16\n\x0esortEfficiency\x18\x0e \x02(\x01\x12(\n\x08sinkDesc\x18\x0f \x02(\x0b\x32\x16.allego.FileDescriptor\"\xd5\x01\n\x16SpikeSorterDashboardAI\x12\x0c\n\x04\x62\x65ta\x18\x01 \x02(\x01\x12\"\n\x1a\x65stimatedReaderCompleteSec\x18\x02 \x02(\x01\x12\x1a\n\x12interSessionDurSec\x18\x03 \x02(\x01\x12\x19\n\x11interSessionStart\x18\x04 \x02(\t\x12\x15\n\rsessionDurSec\x18\x05 \x02(\x01\x12\x14\n\x0csessionStart\x18\x06 \x02(\t\x12\x12\n\nsessionIdx\x18\x07 \x02(\x03\x12\x11\n\tstartTime\x18\x08 \x02(\t\"_\n\x18IndicoDashboardSiteStats\x12\x0b\n\x03snr\x18\x01 \x03(\x01\x12\r\n\x05noise\x18\x02 \x03(\x01\x12\x13\n\x0bneuronYield\x18\x03 \x03(\x01\x12\x12\n\nnumNeurons\x18\x04 \x02(\x03\"\x90\x01\n\x18IndicoDashboardPortStats\x12\x0b\n\x03snr\x18\x01 \x03(\x01\x12\r\n\x05noise\x18\x02 \x03(\x01\x12\x13\n\x0bneuronYield\x18\x03 \x03(\x01\x12\x16\n\x0esortEfficiency\x18\x04 \x02(\x01\x12\x17\n\x0fnumEnabledSites\x18\x05 \x02(\x03\x12\x12\n\nnumNeurons\x18\x06 \x02(\x03\"\xd9\x01\n\x1dIndicoDashboardSiteIndicators\x12\x12\n\nntvChanIdx\x18\x01 \x03(\x05\x12\x0b\n\x03snr\x18\x02 \x03(\x01\x12\r\n\x05noise\x18\x03 \x03(\x01\x12\x13\n\x0bneuronYield\x18\x04 \x03(\x01\x12\x16\n\x0esortEfficiency\x18\x05 \x03(\x01\x12\x11\n\tspikeRate\x18\x06 \x03(\x01\x12\x11\n\tposProbeX\x18\x07 \x03(\x01\x12\x11\n\tposProbeY\x18\x08 \x03(\x01\x12\x11\n\tposProbeZ\x18\t \x03(\x01\x12\x0f\n\x07siteNum\x18\n \x03(\x05\"\xb1\x01\n\x1fIndicoDashboardNeuronIndicators\x12\x10\n\x08neuronID\x18\x01 \x03(\t\x12\x0b\n\x03snr\x18\x02 \x03(\x01\x12\x11\n\tspikeRate\x18\x03 \x03(\x01\x12\x11\n\tposProbeX\x18\x04 \x03(\x01\x12\x11\n\tposProbeY\x18\x05 \x03(\x01\x12\x11\n\tposProbeZ\x18\x06 \x03(\x01\x12\x0f\n\x07siteNum\x18\x07 \x03(\x05\x12\x12\n\nspikeLabel\x18\x08 \x03(\x05\"\xa7\x02\n\x1cSpikeSorterDashboardSiteDesc\x12\x1a\n\x04port\x18\x01 \x02(\x0e\x32\x0c.allego.Port\x12\x12\n\nntvChanIdx\x18\x02 \x02(\x05\x12\x10\n\x08posProbe\x18\x03 \x03(\x01\x12\x10\n\x08posBrain\x18\x04 \x03(\x01\x12\x0e\n\x06snrMax\x18\x05 \x02(\x01\x12\x0e\n\x06snrMin\x18\x06 \x02(\x01\x12\x12\n\nnoiseLevel\x18\x07 \x02(\x01\x12\x12\n\nnumNeurons\x18\x08 \x02(\x03\x12/\n\rindicoCluster\x18\n \x03(\x0b\x32\x18.allego.ClusterMapRecord\x12\x1c\n\x14pileWaveformMinValue\x18\r \x02(\x02\x12\x1c\n\x14pileWaveformMaxValue\x18\x0e \x02(\x02\"\xd2\x01\n\x1eSpikeSorterDashboardNeuronDesc\x12\x1a\n\x04port\x18\x01 \x02(\x0e\x32\x0c.allego.Port\x12&\n\x04\x64\x65sc\x18\x02 \x02(\x0b\x32\x18.allego.NeuronDescriptor\x12\x0b\n\x03snr\x18\x05 \x02(\x01\x12\x0f\n\x07IsihMax\x18\x06 \x02(\x01\x12\x15\n\rIsihArgmaxSec\x18\x07 \x02(\x01\x12\x15\n\rIsihArgmaxIdx\x18\x08 \x02(\x03\x12\x10\n\x08IsihMean\x18\t \x02(\x01\x12\x0e\n\x06IsihSd\x18\n \x02(\x01\"\xfa\x01\n SpikeSorterDashboardNeuronDetail\x12&\n\x04\x64\x65sc\x18\x01 \x02(\x0b\x32\x18.allego.NeuronDescriptor\x12\x18\n\x10templateWaveform\x18\x02 \x03(\x02\x12\x1a\n\x12templateSdWaveform\x18\x03 \x03(\x02\x12\x18\n\x10pileWaveformData\x18\x04 \x03(\x02\x12\x1e\n\x16numSamplesPileWaveform\x18\x05 \x02(\x05\x12\x18\n\x10numPileWaveforms\x18\x06 \x02(\x05\x12$\n\x04isih\x18\x0b \x02(\x0b\x32\x16.allego.NeuronHistData\"\xa9\x01\n\x1eSpikeSorterDashboardSiteDetail\x12\x32\n\x04\x64\x65sc\x18\x01 \x02(\x0b\x32$.allego.SpikeSorterDashboardSiteDesc\x12\x19\n\x11orderedSpikeLabel\x18\x02 \x03(\x05\x12\x38\n\x06neuron\x18\x03 \x03(\x0b\x32(.allego.SpikeSorterDashboardNeuronDetail*\x80\x01\n\x0fSpikeSorterType\x12\x0f\n\x0bSORTER_NULL\x10\x00\x12\x15\n\x11SORTER_VEX_STREAM\x10\x01\x12\x18\n\x14SORTER_SPIKES_STREAM\x10\x02\x12\x13\n\x0fSORTER_VEX_FILE\x10\x03\x12\x16\n\x12SORTER_SPIKES_FILE\x10\x04*\xb0\x01\n\x12SpikeSorterCommand\x12\x11\n\rSORTER_CMD_ON\x10\x00\x12\x12\n\x0eSORTER_CMD_OFF\x10\x01\x12\x19\n\x15SORTER_CMD_CLEAR_SORT\x10\x02\x12\x15\n\x11SORTER_CMD_REBASE\x10\x04\x12\x13\n\x0fSORTER_CMD_INIT\x10\x07\x12\x17\n\x13SORTER_CMD_LOCALIZE\x10\x08\x12\x13\n\x0fSORTER_CMD_SORT\x10\t*/\n\x15SpikeSorterSubCommand\x12\x16\n\x12SORTER_SUBCMD_NULL\x10\x00*@\n\x0fSpikeSorterMode\x12\x16\n\x12SORTER_MODE_STREAM\x10\x00\x12\x15\n\x11SORTER_MODE_BATCH\x10\x01*I\n\x16SpikeSorterStateSystem\x12\n\n\x06SYS_ON\x10\x00\x12\x0b\n\x07SYS_OFF\x10\x01\x12\x16\n\x12SYS_NOT_CONFIGURED\x10\x02*f\n\rSpkSortIOtype\x12\x17\n\x13SPK_SORT_IO_NETWORK\x10\x00\x12\x17\n\x13SPK_SORT_IO_TRAINER\x10\x01\x12#\n\x1fSPK_SORT_IO_NETWORK_AND_TRAINER\x10\x02*>\n\x0fSpkSortIOtarget\x12\x14\n\x10SPK_SORT_IO_FSYS\x10\x00\x12\x15\n\x11SPK_SORT_IO_CLOUD\x10\x01*;\n\rSpkSortIOmode\x12\x14\n\x10SPK_SORT_IO_SAVE\x10\x00\x12\x14\n\x10SPK_SORT_IO_LOAD\x10\x01*u\n\x19SpikeSorterCriterionLevel\x12\x10\n\x0cSORTER_LEAST\x10\x00\x12\x0f\n\x0bSORTER_LESS\x10\x01\x12\x13\n\x0fSORTER_BALANCED\x10\x02\x12\x0f\n\x0bSORTER_MORE\x10\x03\x12\x0f\n\x0bSORTER_MOST\x10\x04*\x84\x01\n\x07SS_STAT\x12\x08\n\x04MEAN\x10\x00\x12\x06\n\x02SD\x10\x01\x12\x08\n\x04MODE\x10\x02\x12\x07\n\x03MIN\x10\x03\x12\x07\n\x03MAX\x10\x04\x12\x0e\n\nMODE_COUNT\x10\x05\x12\n\n\x06MEDIAN\x10\x06\x12\x07\n\x03Q25\x10\x07\x12\x07\n\x03Q75\x10\x08\x12\x08\n\x04SKEW\x10\t\x12\x0c\n\x08KURTOSIS\x10\n\x12\x05\n\x01N\x10\x0b\x42\x15Z\x13internal/radix/grpc')
+DESCRIPTOR = _descriptor_pool.Default().AddSerializedFile(b'\n\x11spikesorter.proto\x12\x06\x61llego\x1a\x0c\x63ommon.proto\x1a\x12\x62iointerface.proto\"\xbc\x02\n\x18SpikeSorterLaunchRequest\x12\x11\n\tdsourceID\x18\x01 \x01(\t\x12&\n\x06source\x18\x02 \x01(\x0b\x32\x16.allego.FileDescriptor\x12\x1b\n\x13maxNumSiteNeighbors\x18\x04 \x01(\x05\x12\x18\n\x10neighborRadiusUm\x18\x05 \x01(\x01\x12/\n\x07variant\x18\x06 \x03(\x0b\x32\x1e.allego.SpikeSorterVariantSpec\x12%\n\x04mode\x18\x07 \x01(\x0e\x32\x17.allego.SpikeSorterMode\x12\x0c\n\x04seed\x18\x08 \x01(\x03\x12\x10\n\x08isAutoOn\x18\t \x01(\x08\x12\x12\n\nnbrPattern\x18\n \x01(\x05\x12\x11\n\tnetworkID\x18\x0b \x01(\t\x12\x0f\n\x07release\x18\x0c \x01(\x03\"\x8a\x01\n\x19SpikeSorterCommandRequest\x12\x15\n\rspikeSorterID\x18\x01 \x02(\t\x12\'\n\x03\x63md\x18\x02 \x02(\x0e\x32\x1a.allego.SpikeSorterCommand\x12-\n\x06subCmd\x18\x03 \x02(\x0e\x32\x1d.allego.SpikeSorterSubCommand\"\x86\x02\n\x10SpikeSorterState\x12+\n\x03sys\x18\x01 \x02(\x0e\x32\x1e.allego.SpikeSorterStateSystem\x12\x14\n\x0c\x66racComplete\x18\x02 \x01(\x01\x12\x0b\n\x03msg\x18\x03 \x01(\t\x12\x12\n\nlaunchTime\x18\x04 \x01(\t\x12\x16\n\x0einitializeTime\x18\x05 \x01(\t\x12\x18\n\x10sessionStartTime\x18\x06 \x01(\t\x12\x17\n\x0fsessionStopTime\x18\x07 \x01(\t\x12\x0c\n\x04isOn\x18\x08 \x01(\x08\x12\x1a\n\x12kernelErrorMessage\x18\t \x01(\t\x12\x19\n\x11kernelWarnMessage\x18\n \x01(\t\"\x81\x01\n\x0cSpkSortIOreq\x12#\n\x04type\x18\x01 \x02(\x0e\x32\x15.allego.SpkSortIOtype\x12\'\n\x06target\x18\x02 \x02(\x0e\x32\x17.allego.SpkSortIOtarget\x12#\n\x04mode\x18\x03 \x02(\x0e\x32\x15.allego.SpkSortIOmode\"\x8f\x01\n\x16SpikeSorterLaunchReply\x12\x15\n\rspikeSorterID\x18\x01 \x02(\t\x12+\n\nsorterType\x18\x02 \x02(\x0e\x32\x17.allego.SpikeSorterType\x12\x0b\n\x03msg\x18\x03 \x01(\t\x12$\n\x04\x64\x65sc\x18\x04 \x01(\x0b\x32\x16.allego.FileDescriptor\"0\n\x16GetSpikeSorterIDsReply\x12\x16\n\x0espikeSorterIDs\x18\x01 \x03(\t\"\xa1\x01\n\x1fSpikeSorterGetRasterDataRequest\x12\x15\n\rspikeSorterID\x18\x01 \x02(\t\x12\x12\n\nntvChanIdx\x18\x02 \x03(\x05\x12\x12\n\ntimeWindow\x18\x03 \x02(\x01\x12\x17\n\x0fplotWidthPoints\x18\x04 \x02(\x01\x12\x13\n\x0b\x63omponentID\x18\x05 \x02(\t\x12\x11\n\ttimeRange\x18\x06 \x03(\x01\"\xaa\x01\n\x1aSpikeSorterRasterDataReply\x12<\n\x18spikeTimestampsByChannel\x18\x02 \x03(\x0b\x32\x1a.allego.SpikeTimestampData\x12\x11\n\ttimeRange\x18\x03 \x03(\x01\x12\x16\n\x0etimeStampRange\x18\x04 \x03(\x03\x12\x10\n\x08GPIOData\x18\x05 \x02(\x0c\x12\x11\n\tGPIOShape\x18\x06 \x03(\x05\"3\n\x1aSpikeSorterStandardRequest\x12\x15\n\rspikeSorterID\x18\x01 \x02(\t\"\x86\x03\n\x12SpikeSorterDynamic\x12\x11\n\tisEnabled\x18\x01 \x01(\x08\x12\x43\n\x0fupdatePeriodSec\x18\x02 \x01(\x0b\x32*.allego.SpikeSorterDynamic.UpdatePeriodSec\x12\x35\n\x08\x63riteria\x18\x03 \x01(\x0b\x32#.allego.SpikeSorterDynamic.Criteria\x1a\xa0\x01\n\x08\x43riteria\x12\x31\n\x06\x64\x65tect\x18\x01 \x01(\x0e\x32!.allego.SpikeSorterCriterionLevel\x12\x30\n\x05train\x18\x02 \x01(\x0e\x32!.allego.SpikeSorterCriterionLevel\x12/\n\x04sort\x18\x03 \x01(\x0e\x32!.allego.SpikeSorterCriterionLevel\x1a>\n\x0fUpdatePeriodSec\x12\x0e\n\x06\x64\x65tect\x18\x01 \x01(\x01\x12\r\n\x05train\x18\x02 \x01(\x01\x12\x0c\n\x04sort\x18\x03 \x01(\x01\"\xc5\x01\n\x1cSpikeSorterSetDynamicRequest\x12\x15\n\rspikeSorterID\x18\x01 \x02(\t\x12\x42\n\x07variant\x18\x02 \x03(\x0b\x32\x31.allego.SpikeSorterSetDynamicRequest.VariantEntry\x1aJ\n\x0cVariantEntry\x12\x0b\n\x03key\x18\x01 \x01(\t\x12)\n\x05value\x18\x02 \x01(\x0b\x32\x1a.allego.SpikeSorterDynamic:\x02\x38\x01\"\xd8\x01\n\x1aSpikeSorterGetDynamicReply\x12\x15\n\rspikeSorterID\x18\x01 \x02(\t\x12\x15\n\rrootVariantID\x18\x02 \x02(\t\x12@\n\x07variant\x18\x03 \x03(\x0b\x32/.allego.SpikeSorterGetDynamicReply.VariantEntry\x1aJ\n\x0cVariantEntry\x12\x0b\n\x03key\x18\x01 \x01(\t\x12)\n\x05value\x18\x02 \x01(\x0b\x32\x1a.allego.SpikeSorterDynamic:\x02\x38\x01\"l\n\x1fGetSpikeSorterParamCommandReply\x12\x15\n\rspikeSorterID\x18\x01 \x02(\t\x12\x32\n\x03rec\x18\x02 \x03(\x0b\x32%.allego.SpikeSorterParamCommandRecord\"3\n\x12\x43lusterMapOutliers\x12\x0c\n\x04mild\x18\x01 \x03(\x01\x12\x0f\n\x07\x65xtreme\x18\x02 \x03(\x01\"9\n\x13\x43lusterMapQuartiles\x12\n\n\x02q1\x18\x01 \x02(\x01\x12\n\n\x02q2\x18\x02 \x02(\x01\x12\n\n\x02q3\x18\x03 \x02(\x01\"\x83\x01\n\x0f\x43lusterMapStats\x12\x16\n\x0e\x63\x65ntroidCenter\x18\x01 \x03(\x01\x12\x12\n\ncentroidSd\x18\x02 \x03(\x01\x12\x16\n\x0e\x63\x65ntroidSdNorm\x18\x03 \x02(\x01\x12\x19\n\x11intraCentroidDist\x18\x04 \x03(\x01\x12\x11\n\tnumSpikes\x18\x05 \x02(\x03\"f\n\x10\x43lusterMapRecord\x12\r\n\x05label\x18\x01 \x02(\x05\x12&\n\x05stats\x18\x03 \x02(\x0b\x32\x17.allego.ClusterMapStats\x12\x1b\n\x13numSpikesTrainCache\x18\x04 \x02(\x03\"\xa8\x01\n\x13SpikeSortSiteStatus\x12\x12\n\nntvChanIdx\x18\x01 \x02(\x05\x12\x15\n\rorderedLabels\x18\x02 \x03(\x05\x12)\n\x07\x63luster\x18\x03 \x03(\x0b\x32\x18.allego.ClusterMapRecord\x12\x11\n\tnumSpikes\x18\x04 \x03(\x03\x12\x0c\n\x04zeta\x18\x05 \x03(\x01\x12\x1a\n\x12\x61ggregateSpikeRate\x18\x06 \x02(\x01\"\x8f\x01\n\x14SpikeSortPhaseStatus\x12\x11\n\ttimeRange\x18\x01 \x03(\x01\x12\x12\n\nchunkIndex\x18\x02 \x02(\x03\x12\x14\n\x0cupdatePeriod\x18\x03 \x02(\x01\x12\x0c\n\x04\x62\x65ta\x18\x04 \x02(\x01\x12\x12\n\nisComplete\x18\x05 \x02(\x08\x12\x18\n\x10\x66ractionComplete\x18\x06 \x02(\x01\"*\n\x13SpikeSortNbrIdxList\x12\x13\n\x0bntvChanIdxs\x18\x01 \x03(\x05\"\xf2\x02\n\x16SpikeSorterStatusReply\x12\'\n\x05state\x18\x01 \x02(\x0b\x32\x18.allego.SpikeSorterState\x12\x16\n\x0e\x62iointerfaceID\x18\x03 \x02(\t\x12\x14\n\x0c\x64\x61tasourceID\x18\x04 \x02(\t\x12\x10\n\x08sampFreq\x18\x05 \x02(\x01\x12\x19\n\x11\x65nabledNtvChanIdx\x18\x06 \x03(\x05\x12+\n\x05phase\x18\x07 \x03(\x0b\x32\x1c.allego.SpikeSortPhaseStatus\x12\x30\n\x0b\x65nabledSite\x18\x08 \x03(\x0b\x32\x1b.allego.SpikeSortSiteStatus\x12\x12\n\nprobeYield\x18\t \x02(\x01\x12\x11\n\tsortStats\x18\n \x03(\x01\x12\x1b\n\x13\x64\x61tasourceTimeRange\x18\x0c \x03(\x01\x12\x1d\n\x15\x62iointerfaceTimeRange\x18\r \x03(\x01\x12\x12\n\nnumNeurons\x18\x0f \x02(\x03\"R\n\x1eSpikeSorterStatusVariantsReply\x12\x30\n\x08variants\x18\x01 \x03(\x0b\x32\x1e.allego.SpikeSorterStatusReply\"\xfd\x02\n\x19SpikeSorterClassifierSpec\x12\r\n\x05\x61lpha\x18\x01 \x02(\x01\x12\x11\n\talphaBias\x18\x02 \x02(\x01\x12\x16\n\x0e\x64imOutputLayer\x18\x03 \x02(\x05\x12\x16\n\x0e\x65rrorTolerance\x18\x04 \x02(\x01\x12\x19\n\x11hiddenLayerFactor\x18\x05 \x02(\x01\x12\n\n\x02iD\x18\x06 \x02(\t\x12\x16\n\x0einitBiasStdDev\x18\x07 \x02(\x01\x12\x18\n\x10initWeightStdDev\x18\x08 \x02(\x01\x12\x11\n\tisMasking\x18\t \x02(\x08\x12\x10\n\x08l1lambda\x18\n \x02(\x01\x12\x15\n\rminibatchSize\x18\x0b \x02(\x05\x12\x15\n\rmaxNumSamples\x18\x0c \x02(\x05\x12\x11\n\tnumEpochs\x18\r \x02(\x05\x12\x19\n\x11numSamplesTestMSE\x18\x0e \x02(\x05\x12\x1b\n\x13numConcurrentModels\x18\x0f \x02(\x05\x12\x17\n\x0flabelNoiseLevel\x18\x10 \x02(\x01\"u\n\x16SpikeSorterVariantSpec\x12\n\n\x02iD\x18\x01 \x02(\t\x12\x14\n\x0csiteConfigID\x18\x02 \x02(\t\x12\x39\n\x0e\x63lassifierSpec\x18\x03 \x02(\x0b\x32!.allego.SpikeSorterClassifierSpec\"\xcc\x01\n\x0fSpikeSorterSpec\x12\x15\n\rspikeSorterID\x18\x01 \x02(\t\x12\x14\n\x0c\x64\x61tasourceID\x18\x02 \x02(\t\x12\x16\n\x0e\x62iointerfaceID\x18\x03 \x02(\t\x12\x1b\n\x13maxNumSiteNeighbors\x18\x04 \x02(\x05\x12\x18\n\x10neighborRadiusUm\x18\x05 \x02(\x01\x12/\n\x07variant\x18\x06 \x03(\x0b\x32\x1e.allego.SpikeSorterVariantSpec\x12\x0c\n\x04seed\x18\x08 \x02(\x03\"\xc2\x01\n\x19SpikeSorterGetConfigReply\x12%\n\x04spec\x18\x01 \x02(\x0b\x32\x17.allego.SpikeSorterSpec\x12\x16\n\x0e\x61IupdatePeriod\x18\x02 \x02(\x01\x12\x19\n\x11orderedVariantIDs\x18\x03 \x03(\t\x12\x15\n\rrootVariantID\x18\x04 \x02(\t\x12\x34\n\x0csorterStatus\x18\x06 \x03(\x0b\x32\x1e.allego.SpikeSorterStatusReply\"\x90\x02\n\x15SpikeSorterVizRequest\x12\x15\n\rspikeSorterID\x18\x01 \x02(\t\x12\x11\n\tvariantID\x18\x02 \x02(\t\x12\x12\n\nntvChanIdx\x18\x03 \x03(\x05\x12\x13\n\x0bspikeLabels\x18\x04 \x03(\x05\x12\x34\n\x07vizType\x18\x05 \x02(\x0e\x32#.allego.SpikeSorterVizRequest.VType\x12\x14\n\x0cisYAutoScale\x18\x06 \x02(\x08\x12\x0c\n\x04yLim\x18\x07 \x03(\x01\x12\x0e\n\x06\x66igDir\x18\x08 \x02(\t\x12\x11\n\tnumSpikes\x18\t \x02(\x05\"\'\n\x05VType\x12\x1e\n\x1aVIZ_SPIKESORT_TRAIN_SPIKES\x10\x00\"\xc2\x05\n\x1cSpikeSorterGetDashboardReply\x12\"\n\x0c\x65nabledPorts\x18\x01 \x03(\x0e\x32\x0c.allego.Port\x12\x37\n\x07general\x18\x02 \x02(\x0b\x32&.allego.SpikeSorterDashboardGeneralRec\x12\x33\n\tsiteStats\x18\x03 \x02(\x0b\x32 .allego.IndicoDashboardSiteStats\x12\x46\n\tportStats\x18\x04 \x03(\x0b\x32\x33.allego.SpikeSorterGetDashboardReply.PortStatsEntry\x12\x46\n\tsitePanel\x18\x05 \x03(\x0b\x32\x33.allego.SpikeSorterGetDashboardReply.SitePanelEntry\x12J\n\x0bneuronPanel\x18\x06 \x03(\x0b\x32\x35.allego.SpikeSorterGetDashboardReply.NeuronPanelEntry\x12*\n\x02\x61I\x18\x07 \x01(\x0b\x32\x1e.allego.SpikeSorterDashboardAI\x1aR\n\x0ePortStatsEntry\x12\x0b\n\x03key\x18\x01 \x01(\t\x12/\n\x05value\x18\x02 \x01(\x0b\x32 .allego.IndicoDashboardPortStats:\x02\x38\x01\x1aW\n\x0eSitePanelEntry\x12\x0b\n\x03key\x18\x01 \x01(\t\x12\x34\n\x05value\x18\x02 \x01(\x0b\x32%.allego.IndicoDashboardSiteIndicators:\x02\x38\x01\x1a[\n\x10NeuronPanelEntry\x12\x0b\n\x03key\x18\x01 \x01(\t\x12\x36\n\x05value\x18\x02 \x01(\x0b\x32\'.allego.IndicoDashboardNeuronIndicators:\x02\x38\x01\"\xac\x03\n\x1eSpikeSorterDashboardGeneralRec\x12\'\n\x05state\x18\x01 \x02(\x0b\x32\x18.allego.SpikeSorterState\x12+\n\nsorterType\x18\x02 \x02(\x0e\x32\x17.allego.SpikeSorterType\x12\x10\n\x08sorterID\x18\x03 \x02(\t\x12\x14\n\x0c\x64\x61tasourceID\x18\x04 \x02(\t\x12\x11\n\ttimeRange\x18\x05 \x03(\x01\x12\x15\n\rnumTotalSites\x18\x06 \x02(\x03\x12\x17\n\x0fnumEnabledSites\x18\x07 \x02(\x03\x12\x16\n\x0enumActiveSites\x18\x08 \x02(\x03\x12\x12\n\nnumNeurons\x18\t \x02(\x03\x12\x12\n\nprobeYield\x18\n \x02(\x01\x12\x11\n\tsiteYield\x18\x0b \x02(\x01\x12\x1a\n\x12numSpikesProcessed\x18\x0c \x02(\x03\x12\x18\n\x10numSpikesLabeled\x18\r \x02(\x03\x12\x16\n\x0esortEfficiency\x18\x0e \x02(\x01\x12(\n\x08sinkDesc\x18\x0f \x02(\x0b\x32\x16.allego.FileDescriptor\"\xd5\x01\n\x16SpikeSorterDashboardAI\x12\x0c\n\x04\x62\x65ta\x18\x01 \x02(\x01\x12\"\n\x1a\x65stimatedReaderCompleteSec\x18\x02 \x02(\x01\x12\x1a\n\x12interSessionDurSec\x18\x03 \x02(\x01\x12\x19\n\x11interSessionStart\x18\x04 \x02(\t\x12\x15\n\rsessionDurSec\x18\x05 \x02(\x01\x12\x14\n\x0csessionStart\x18\x06 \x02(\t\x12\x12\n\nsessionIdx\x18\x07 \x02(\x03\x12\x11\n\tstartTime\x18\x08 \x02(\t\"_\n\x18IndicoDashboardSiteStats\x12\x0b\n\x03snr\x18\x01 \x03(\x01\x12\r\n\x05noise\x18\x02 \x03(\x01\x12\x13\n\x0bneuronYield\x18\x03 \x03(\x01\x12\x12\n\nnumNeurons\x18\x04 \x02(\x03\"\x90\x01\n\x18IndicoDashboardPortStats\x12\x0b\n\x03snr\x18\x01 \x03(\x01\x12\r\n\x05noise\x18\x02 \x03(\x01\x12\x13\n\x0bneuronYield\x18\x03 \x03(\x01\x12\x16\n\x0esortEfficiency\x18\x04 \x02(\x01\x12\x17\n\x0fnumEnabledSites\x18\x05 \x02(\x03\x12\x12\n\nnumNeurons\x18\x06 \x02(\x03\"\xd9\x01\n\x1dIndicoDashboardSiteIndicators\x12\x12\n\nntvChanIdx\x18\x01 \x03(\x05\x12\x0b\n\x03snr\x18\x02 \x03(\x01\x12\r\n\x05noise\x18\x03 \x03(\x01\x12\x13\n\x0bneuronYield\x18\x04 \x03(\x01\x12\x16\n\x0esortEfficiency\x18\x05 \x03(\x01\x12\x11\n\tspikeRate\x18\x06 \x03(\x01\x12\x11\n\tposProbeX\x18\x07 \x03(\x01\x12\x11\n\tposProbeY\x18\x08 \x03(\x01\x12\x11\n\tposProbeZ\x18\t \x03(\x01\x12\x0f\n\x07siteNum\x18\n \x03(\x05\"\xb1\x01\n\x1fIndicoDashboardNeuronIndicators\x12\x10\n\x08neuronID\x18\x01 \x03(\t\x12\x0b\n\x03snr\x18\x02 \x03(\x01\x12\x11\n\tspikeRate\x18\x03 \x03(\x01\x12\x11\n\tposProbeX\x18\x04 \x03(\x01\x12\x11\n\tposProbeY\x18\x05 \x03(\x01\x12\x11\n\tposProbeZ\x18\x06 \x03(\x01\x12\x0f\n\x07siteNum\x18\x07 \x03(\x05\x12\x12\n\nspikeLabel\x18\x08 \x03(\x05\"\xa7\x02\n\x1cSpikeSorterDashboardSiteDesc\x12\x1a\n\x04port\x18\x01 \x02(\x0e\x32\x0c.allego.Port\x12\x12\n\nntvChanIdx\x18\x02 \x02(\x05\x12\x10\n\x08posProbe\x18\x03 \x03(\x01\x12\x10\n\x08posBrain\x18\x04 \x03(\x01\x12\x0e\n\x06snrMax\x18\x05 \x02(\x01\x12\x0e\n\x06snrMin\x18\x06 \x02(\x01\x12\x12\n\nnoiseLevel\x18\x07 \x02(\x01\x12\x12\n\nnumNeurons\x18\x08 \x02(\x03\x12/\n\rindicoCluster\x18\n \x03(\x0b\x32\x18.allego.ClusterMapRecord\x12\x1c\n\x14pileWaveformMinValue\x18\r \x02(\x02\x12\x1c\n\x14pileWaveformMaxValue\x18\x0e \x02(\x02\"\xd2\x01\n\x1eSpikeSorterDashboardNeuronDesc\x12\x1a\n\x04port\x18\x01 \x02(\x0e\x32\x0c.allego.Port\x12&\n\x04\x64\x65sc\x18\x02 \x02(\x0b\x32\x18.allego.NeuronDescriptor\x12\x0b\n\x03snr\x18\x05 \x02(\x01\x12\x0f\n\x07IsihMax\x18\x06 \x02(\x01\x12\x15\n\rIsihArgmaxSec\x18\x07 \x02(\x01\x12\x15\n\rIsihArgmaxIdx\x18\x08 \x02(\x03\x12\x10\n\x08IsihMean\x18\t \x02(\x01\x12\x0e\n\x06IsihSd\x18\n \x02(\x01\"\xfa\x01\n SpikeSorterDashboardNeuronDetail\x12&\n\x04\x64\x65sc\x18\x01 \x02(\x0b\x32\x18.allego.NeuronDescriptor\x12\x18\n\x10templateWaveform\x18\x02 \x03(\x02\x12\x1a\n\x12templateSdWaveform\x18\x03 \x03(\x02\x12\x18\n\x10pileWaveformData\x18\x04 \x03(\x02\x12\x1e\n\x16numSamplesPileWaveform\x18\x05 \x02(\x05\x12\x18\n\x10numPileWaveforms\x18\x06 \x02(\x05\x12$\n\x04isih\x18\x0b \x02(\x0b\x32\x16.allego.NeuronHistData\"\xa9\x01\n\x1eSpikeSorterDashboardSiteDetail\x12\x32\n\x04\x64\x65sc\x18\x01 \x02(\x0b\x32$.allego.SpikeSorterDashboardSiteDesc\x12\x19\n\x11orderedSpikeLabel\x18\x02 \x03(\x05\x12\x38\n\x06neuron\x18\x03 \x03(\x0b\x32(.allego.SpikeSorterDashboardNeuronDetail*\x80\x01\n\x0fSpikeSorterType\x12\x0f\n\x0bSORTER_NULL\x10\x00\x12\x15\n\x11SORTER_VEX_STREAM\x10\x01\x12\x18\n\x14SORTER_SPIKES_STREAM\x10\x02\x12\x13\n\x0fSORTER_VEX_FILE\x10\x03\x12\x16\n\x12SORTER_SPIKES_FILE\x10\x04*\xb0\x01\n\x12SpikeSorterCommand\x12\x11\n\rSORTER_CMD_ON\x10\x00\x12\x12\n\x0eSORTER_CMD_OFF\x10\x01\x12\x19\n\x15SORTER_CMD_CLEAR_SORT\x10\x02\x12\x15\n\x11SORTER_CMD_REBASE\x10\x04\x12\x13\n\x0fSORTER_CMD_INIT\x10\x07\x12\x17\n\x13SORTER_CMD_LOCALIZE\x10\x08\x12\x13\n\x0fSORTER_CMD_SORT\x10\t*/\n\x15SpikeSorterSubCommand\x12\x16\n\x12SORTER_SUBCMD_NULL\x10\x00*@\n\x0fSpikeSorterMode\x12\x16\n\x12SORTER_MODE_STREAM\x10\x00\x12\x15\n\x11SORTER_MODE_BATCH\x10\x01*I\n\x16SpikeSorterStateSystem\x12\n\n\x06SYS_ON\x10\x00\x12\x0b\n\x07SYS_OFF\x10\x01\x12\x16\n\x12SYS_NOT_CONFIGURED\x10\x02*f\n\rSpkSortIOtype\x12\x17\n\x13SPK_SORT_IO_NETWORK\x10\x00\x12\x17\n\x13SPK_SORT_IO_TRAINER\x10\x01\x12#\n\x1fSPK_SORT_IO_NETWORK_AND_TRAINER\x10\x02*>\n\x0fSpkSortIOtarget\x12\x14\n\x10SPK_SORT_IO_FSYS\x10\x00\x12\x15\n\x11SPK_SORT_IO_CLOUD\x10\x01*;\n\rSpkSortIOmode\x12\x14\n\x10SPK_SORT_IO_SAVE\x10\x00\x12\x14\n\x10SPK_SORT_IO_LOAD\x10\x01*u\n\x19SpikeSorterCriterionLevel\x12\x10\n\x0cSORTER_LEAST\x10\x00\x12\x0f\n\x0bSORTER_LESS\x10\x01\x12\x13\n\x0fSORTER_BALANCED\x10\x02\x12\x0f\n\x0bSORTER_MORE\x10\x03\x12\x0f\n\x0bSORTER_MOST\x10\x04*\x84\x01\n\x07SS_STAT\x12\x08\n\x04MEAN\x10\x00\x12\x06\n\x02SD\x10\x01\x12\x08\n\x04MODE\x10\x02\x12\x07\n\x03MIN\x10\x03\x12\x07\n\x03MAX\x10\x04\x12\x0e\n\nMODE_COUNT\x10\x05\x12\n\n\x06MEDIAN\x10\x06\x12\x07\n\x03Q25\x10\x07\x12\x07\n\x03Q75\x10\x08\x12\x08\n\x04SKEW\x10\t\x12\x0c\n\x08KURTOSIS\x10\n\x12\x05\n\x01N\x10\x0b\x42\x15Z\x13internal/radix/grpc')
 
 _builder.BuildMessageAndEnumDescriptors(DESCRIPTOR, globals())
 _builder.BuildTopDescriptorsAndMessages(DESCRIPTOR, 'spikesorter_pb2', globals())
 if _descriptor._USE_C_DESCRIPTORS == False:
 
   DESCRIPTOR._options = None
   DESCRIPTOR._serialized_options = b'Z\023internal/radix/grpc'
@@ -29,120 +29,120 @@
   _SPIKESORTERGETDYNAMICREPLY_VARIANTENTRY._serialized_options = b'8\001'
   _SPIKESORTERGETDASHBOARDREPLY_PORTSTATSENTRY._options = None
   _SPIKESORTERGETDASHBOARDREPLY_PORTSTATSENTRY._serialized_options = b'8\001'
   _SPIKESORTERGETDASHBOARDREPLY_SITEPANELENTRY._options = None
   _SPIKESORTERGETDASHBOARDREPLY_SITEPANELENTRY._serialized_options = b'8\001'
   _SPIKESORTERGETDASHBOARDREPLY_NEURONPANELENTRY._options = None
   _SPIKESORTERGETDASHBOARDREPLY_NEURONPANELENTRY._serialized_options = b'8\001'
-  _SPIKESORTERTYPE._serialized_start=7676
-  _SPIKESORTERTYPE._serialized_end=7804
-  _SPIKESORTERCOMMAND._serialized_start=7807
-  _SPIKESORTERCOMMAND._serialized_end=7983
-  _SPIKESORTERSUBCOMMAND._serialized_start=7985
-  _SPIKESORTERSUBCOMMAND._serialized_end=8032
-  _SPIKESORTERMODE._serialized_start=8034
-  _SPIKESORTERMODE._serialized_end=8098
-  _SPIKESORTERSTATESYSTEM._serialized_start=8100
-  _SPIKESORTERSTATESYSTEM._serialized_end=8173
-  _SPKSORTIOTYPE._serialized_start=8175
-  _SPKSORTIOTYPE._serialized_end=8277
-  _SPKSORTIOTARGET._serialized_start=8279
-  _SPKSORTIOTARGET._serialized_end=8341
-  _SPKSORTIOMODE._serialized_start=8343
-  _SPKSORTIOMODE._serialized_end=8402
-  _SPIKESORTERCRITERIONLEVEL._serialized_start=8404
-  _SPIKESORTERCRITERIONLEVEL._serialized_end=8521
-  _SS_STAT._serialized_start=8524
-  _SS_STAT._serialized_end=8656
+  _SPIKESORTERTYPE._serialized_start=7715
+  _SPIKESORTERTYPE._serialized_end=7843
+  _SPIKESORTERCOMMAND._serialized_start=7846
+  _SPIKESORTERCOMMAND._serialized_end=8022
+  _SPIKESORTERSUBCOMMAND._serialized_start=8024
+  _SPIKESORTERSUBCOMMAND._serialized_end=8071
+  _SPIKESORTERMODE._serialized_start=8073
+  _SPIKESORTERMODE._serialized_end=8137
+  _SPIKESORTERSTATESYSTEM._serialized_start=8139
+  _SPIKESORTERSTATESYSTEM._serialized_end=8212
+  _SPKSORTIOTYPE._serialized_start=8214
+  _SPKSORTIOTYPE._serialized_end=8316
+  _SPKSORTIOTARGET._serialized_start=8318
+  _SPKSORTIOTARGET._serialized_end=8380
+  _SPKSORTIOMODE._serialized_start=8382
+  _SPKSORTIOMODE._serialized_end=8441
+  _SPIKESORTERCRITERIONLEVEL._serialized_start=8443
+  _SPIKESORTERCRITERIONLEVEL._serialized_end=8560
+  _SS_STAT._serialized_start=8563
+  _SS_STAT._serialized_end=8695
   _SPIKESORTERLAUNCHREQUEST._serialized_start=64
   _SPIKESORTERLAUNCHREQUEST._serialized_end=380
   _SPIKESORTERCOMMANDREQUEST._serialized_start=383
   _SPIKESORTERCOMMANDREQUEST._serialized_end=521
   _SPIKESORTERSTATE._serialized_start=524
   _SPIKESORTERSTATE._serialized_end=786
   _SPKSORTIOREQ._serialized_start=789
   _SPKSORTIOREQ._serialized_end=918
-  _SPIKESORTERLAUNCHREPLY._serialized_start=920
-  _SPIKESORTERLAUNCHREPLY._serialized_end=1025
-  _GETSPIKESORTERIDSREPLY._serialized_start=1027
-  _GETSPIKESORTERIDSREPLY._serialized_end=1075
-  _SPIKESORTERGETRASTERDATAREQUEST._serialized_start=1078
-  _SPIKESORTERGETRASTERDATAREQUEST._serialized_end=1239
-  _SPIKESORTERRASTERDATAREPLY._serialized_start=1242
-  _SPIKESORTERRASTERDATAREPLY._serialized_end=1412
-  _SPIKESORTERSTANDARDREQUEST._serialized_start=1414
-  _SPIKESORTERSTANDARDREQUEST._serialized_end=1465
-  _SPIKESORTERDYNAMIC._serialized_start=1468
-  _SPIKESORTERDYNAMIC._serialized_end=1858
-  _SPIKESORTERDYNAMIC_CRITERIA._serialized_start=1634
-  _SPIKESORTERDYNAMIC_CRITERIA._serialized_end=1794
-  _SPIKESORTERDYNAMIC_UPDATEPERIODSEC._serialized_start=1796
-  _SPIKESORTERDYNAMIC_UPDATEPERIODSEC._serialized_end=1858
-  _SPIKESORTERSETDYNAMICREQUEST._serialized_start=1861
-  _SPIKESORTERSETDYNAMICREQUEST._serialized_end=2058
-  _SPIKESORTERSETDYNAMICREQUEST_VARIANTENTRY._serialized_start=1984
-  _SPIKESORTERSETDYNAMICREQUEST_VARIANTENTRY._serialized_end=2058
-  _SPIKESORTERGETDYNAMICREPLY._serialized_start=2061
-  _SPIKESORTERGETDYNAMICREPLY._serialized_end=2277
-  _SPIKESORTERGETDYNAMICREPLY_VARIANTENTRY._serialized_start=1984
-  _SPIKESORTERGETDYNAMICREPLY_VARIANTENTRY._serialized_end=2058
-  _GETSPIKESORTERPARAMCOMMANDREPLY._serialized_start=2279
-  _GETSPIKESORTERPARAMCOMMANDREPLY._serialized_end=2387
-  _CLUSTERMAPOUTLIERS._serialized_start=2389
-  _CLUSTERMAPOUTLIERS._serialized_end=2440
-  _CLUSTERMAPQUARTILES._serialized_start=2442
-  _CLUSTERMAPQUARTILES._serialized_end=2499
-  _CLUSTERMAPSTATS._serialized_start=2502
-  _CLUSTERMAPSTATS._serialized_end=2633
-  _CLUSTERMAPRECORD._serialized_start=2635
-  _CLUSTERMAPRECORD._serialized_end=2737
-  _SPIKESORTSITESTATUS._serialized_start=2740
-  _SPIKESORTSITESTATUS._serialized_end=2908
-  _SPIKESORTPHASESTATUS._serialized_start=2911
-  _SPIKESORTPHASESTATUS._serialized_end=3054
-  _SPIKESORTNBRIDXLIST._serialized_start=3056
-  _SPIKESORTNBRIDXLIST._serialized_end=3098
-  _SPIKESORTERSTATUSREPLY._serialized_start=3101
-  _SPIKESORTERSTATUSREPLY._serialized_end=3471
-  _SPIKESORTERSTATUSVARIANTSREPLY._serialized_start=3473
-  _SPIKESORTERSTATUSVARIANTSREPLY._serialized_end=3555
-  _SPIKESORTERCLASSIFIERSPEC._serialized_start=3558
-  _SPIKESORTERCLASSIFIERSPEC._serialized_end=3939
-  _SPIKESORTERVARIANTSPEC._serialized_start=3941
-  _SPIKESORTERVARIANTSPEC._serialized_end=4058
-  _SPIKESORTERSPEC._serialized_start=4061
-  _SPIKESORTERSPEC._serialized_end=4265
-  _SPIKESORTERGETCONFIGREPLY._serialized_start=4268
-  _SPIKESORTERGETCONFIGREPLY._serialized_end=4462
-  _SPIKESORTERVIZREQUEST._serialized_start=4465
-  _SPIKESORTERVIZREQUEST._serialized_end=4737
-  _SPIKESORTERVIZREQUEST_VTYPE._serialized_start=4698
-  _SPIKESORTERVIZREQUEST_VTYPE._serialized_end=4737
-  _SPIKESORTERGETDASHBOARDREPLY._serialized_start=4740
-  _SPIKESORTERGETDASHBOARDREPLY._serialized_end=5446
-  _SPIKESORTERGETDASHBOARDREPLY_PORTSTATSENTRY._serialized_start=5182
-  _SPIKESORTERGETDASHBOARDREPLY_PORTSTATSENTRY._serialized_end=5264
-  _SPIKESORTERGETDASHBOARDREPLY_SITEPANELENTRY._serialized_start=5266
-  _SPIKESORTERGETDASHBOARDREPLY_SITEPANELENTRY._serialized_end=5353
-  _SPIKESORTERGETDASHBOARDREPLY_NEURONPANELENTRY._serialized_start=5355
-  _SPIKESORTERGETDASHBOARDREPLY_NEURONPANELENTRY._serialized_end=5446
-  _SPIKESORTERDASHBOARDGENERALREC._serialized_start=5449
-  _SPIKESORTERDASHBOARDGENERALREC._serialized_end=5877
-  _SPIKESORTERDASHBOARDAI._serialized_start=5880
-  _SPIKESORTERDASHBOARDAI._serialized_end=6093
-  _INDICODASHBOARDSITESTATS._serialized_start=6095
-  _INDICODASHBOARDSITESTATS._serialized_end=6190
-  _INDICODASHBOARDPORTSTATS._serialized_start=6193
-  _INDICODASHBOARDPORTSTATS._serialized_end=6337
-  _INDICODASHBOARDSITEINDICATORS._serialized_start=6340
-  _INDICODASHBOARDSITEINDICATORS._serialized_end=6557
-  _INDICODASHBOARDNEURONINDICATORS._serialized_start=6560
-  _INDICODASHBOARDNEURONINDICATORS._serialized_end=6737
-  _SPIKESORTERDASHBOARDSITEDESC._serialized_start=6740
-  _SPIKESORTERDASHBOARDSITEDESC._serialized_end=7035
-  _SPIKESORTERDASHBOARDNEURONDESC._serialized_start=7038
-  _SPIKESORTERDASHBOARDNEURONDESC._serialized_end=7248
-  _SPIKESORTERDASHBOARDNEURONDETAIL._serialized_start=7251
-  _SPIKESORTERDASHBOARDNEURONDETAIL._serialized_end=7501
-  _SPIKESORTERDASHBOARDSITEDETAIL._serialized_start=7504
-  _SPIKESORTERDASHBOARDSITEDETAIL._serialized_end=7673
+  _SPIKESORTERLAUNCHREPLY._serialized_start=921
+  _SPIKESORTERLAUNCHREPLY._serialized_end=1064
+  _GETSPIKESORTERIDSREPLY._serialized_start=1066
+  _GETSPIKESORTERIDSREPLY._serialized_end=1114
+  _SPIKESORTERGETRASTERDATAREQUEST._serialized_start=1117
+  _SPIKESORTERGETRASTERDATAREQUEST._serialized_end=1278
+  _SPIKESORTERRASTERDATAREPLY._serialized_start=1281
+  _SPIKESORTERRASTERDATAREPLY._serialized_end=1451
+  _SPIKESORTERSTANDARDREQUEST._serialized_start=1453
+  _SPIKESORTERSTANDARDREQUEST._serialized_end=1504
+  _SPIKESORTERDYNAMIC._serialized_start=1507
+  _SPIKESORTERDYNAMIC._serialized_end=1897
+  _SPIKESORTERDYNAMIC_CRITERIA._serialized_start=1673
+  _SPIKESORTERDYNAMIC_CRITERIA._serialized_end=1833
+  _SPIKESORTERDYNAMIC_UPDATEPERIODSEC._serialized_start=1835
+  _SPIKESORTERDYNAMIC_UPDATEPERIODSEC._serialized_end=1897
+  _SPIKESORTERSETDYNAMICREQUEST._serialized_start=1900
+  _SPIKESORTERSETDYNAMICREQUEST._serialized_end=2097
+  _SPIKESORTERSETDYNAMICREQUEST_VARIANTENTRY._serialized_start=2023
+  _SPIKESORTERSETDYNAMICREQUEST_VARIANTENTRY._serialized_end=2097
+  _SPIKESORTERGETDYNAMICREPLY._serialized_start=2100
+  _SPIKESORTERGETDYNAMICREPLY._serialized_end=2316
+  _SPIKESORTERGETDYNAMICREPLY_VARIANTENTRY._serialized_start=2023
+  _SPIKESORTERGETDYNAMICREPLY_VARIANTENTRY._serialized_end=2097
+  _GETSPIKESORTERPARAMCOMMANDREPLY._serialized_start=2318
+  _GETSPIKESORTERPARAMCOMMANDREPLY._serialized_end=2426
+  _CLUSTERMAPOUTLIERS._serialized_start=2428
+  _CLUSTERMAPOUTLIERS._serialized_end=2479
+  _CLUSTERMAPQUARTILES._serialized_start=2481
+  _CLUSTERMAPQUARTILES._serialized_end=2538
+  _CLUSTERMAPSTATS._serialized_start=2541
+  _CLUSTERMAPSTATS._serialized_end=2672
+  _CLUSTERMAPRECORD._serialized_start=2674
+  _CLUSTERMAPRECORD._serialized_end=2776
+  _SPIKESORTSITESTATUS._serialized_start=2779
+  _SPIKESORTSITESTATUS._serialized_end=2947
+  _SPIKESORTPHASESTATUS._serialized_start=2950
+  _SPIKESORTPHASESTATUS._serialized_end=3093
+  _SPIKESORTNBRIDXLIST._serialized_start=3095
+  _SPIKESORTNBRIDXLIST._serialized_end=3137
+  _SPIKESORTERSTATUSREPLY._serialized_start=3140
+  _SPIKESORTERSTATUSREPLY._serialized_end=3510
+  _SPIKESORTERSTATUSVARIANTSREPLY._serialized_start=3512
+  _SPIKESORTERSTATUSVARIANTSREPLY._serialized_end=3594
+  _SPIKESORTERCLASSIFIERSPEC._serialized_start=3597
+  _SPIKESORTERCLASSIFIERSPEC._serialized_end=3978
+  _SPIKESORTERVARIANTSPEC._serialized_start=3980
+  _SPIKESORTERVARIANTSPEC._serialized_end=4097
+  _SPIKESORTERSPEC._serialized_start=4100
+  _SPIKESORTERSPEC._serialized_end=4304
+  _SPIKESORTERGETCONFIGREPLY._serialized_start=4307
+  _SPIKESORTERGETCONFIGREPLY._serialized_end=4501
+  _SPIKESORTERVIZREQUEST._serialized_start=4504
+  _SPIKESORTERVIZREQUEST._serialized_end=4776
+  _SPIKESORTERVIZREQUEST_VTYPE._serialized_start=4737
+  _SPIKESORTERVIZREQUEST_VTYPE._serialized_end=4776
+  _SPIKESORTERGETDASHBOARDREPLY._serialized_start=4779
+  _SPIKESORTERGETDASHBOARDREPLY._serialized_end=5485
+  _SPIKESORTERGETDASHBOARDREPLY_PORTSTATSENTRY._serialized_start=5221
+  _SPIKESORTERGETDASHBOARDREPLY_PORTSTATSENTRY._serialized_end=5303
+  _SPIKESORTERGETDASHBOARDREPLY_SITEPANELENTRY._serialized_start=5305
+  _SPIKESORTERGETDASHBOARDREPLY_SITEPANELENTRY._serialized_end=5392
+  _SPIKESORTERGETDASHBOARDREPLY_NEURONPANELENTRY._serialized_start=5394
+  _SPIKESORTERGETDASHBOARDREPLY_NEURONPANELENTRY._serialized_end=5485
+  _SPIKESORTERDASHBOARDGENERALREC._serialized_start=5488
+  _SPIKESORTERDASHBOARDGENERALREC._serialized_end=5916
+  _SPIKESORTERDASHBOARDAI._serialized_start=5919
+  _SPIKESORTERDASHBOARDAI._serialized_end=6132
+  _INDICODASHBOARDSITESTATS._serialized_start=6134
+  _INDICODASHBOARDSITESTATS._serialized_end=6229
+  _INDICODASHBOARDPORTSTATS._serialized_start=6232
+  _INDICODASHBOARDPORTSTATS._serialized_end=6376
+  _INDICODASHBOARDSITEINDICATORS._serialized_start=6379
+  _INDICODASHBOARDSITEINDICATORS._serialized_end=6596
+  _INDICODASHBOARDNEURONINDICATORS._serialized_start=6599
+  _INDICODASHBOARDNEURONINDICATORS._serialized_end=6776
+  _SPIKESORTERDASHBOARDSITEDESC._serialized_start=6779
+  _SPIKESORTERDASHBOARDSITEDESC._serialized_end=7074
+  _SPIKESORTERDASHBOARDNEURONDESC._serialized_start=7077
+  _SPIKESORTERDASHBOARDNEURONDESC._serialized_end=7287
+  _SPIKESORTERDASHBOARDNEURONDETAIL._serialized_start=7290
+  _SPIKESORTERDASHBOARDNEURONDETAIL._serialized_end=7540
+  _SPIKESORTERDASHBOARDSITEDETAIL._serialized_start=7543
+  _SPIKESORTERDASHBOARDSITEDETAIL._serialized_end=7712
 # @@protoc_insertion_point(module_scope)
```

### Comparing `radiens-1.0.5/radiens/lib/_obsolete_bokeh_graphics.py` & `radiens-1.0.6/radiens/lib/_obsolete_bokeh_graphics.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/lib/allego_lib.py` & `radiens-1.0.6/radiens/lib/allego_lib.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/lib/bokeh_graphics.py` & `radiens-1.0.6/radiens/lib/bokeh_graphics.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/lib/channel_metadata.py` & `radiens-1.0.6/radiens/lib/channel_metadata.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,21 +1,24 @@
 from collections import namedtuple
-import pandas as pd
+
 import numpy as np
-from radiens.grpc_radiens import (common_pb2)
-from radiens.utils.constants import (KEY_IDXS, SignalType, ALL_SIGNAL_TYPES, PORT_ENUM)
+import pandas as pd
+from radiens.grpc_radiens import common_pb2
+from radiens.utils.constants import (ALL_SIGNAL_TYPES, KEY_IDXS, PORT_ENUM,
+                                     SignalType)
 
 
 class ChannelMetadata():
     '''
     Container for channel metadata.
     '''
 
     def __init__(self, raw: common_pb2.SignalGroup = None):
         """
+
         """
         self._d = {'dataset_uid': '', 'fs': 0.0, 'source_label': '',
                    'neighbor_max_radius_um': 0.0, 'signal_units': {}, 'has_discrete': False}
         if raw is not None:
             self._d = {'dataset_uid': raw.datasetUID, 'fs': raw.sampFreq, 'source_label': raw.sourceLabel,
                        'neighbor_max_radius_um': raw.neighborMaxRadius, 'signal_units': raw.signalUnits, 'has_discrete': raw.hasDiscrete}
 
@@ -25,36 +28,43 @@
         _df_din = self._df[self._df['chan_type'] == SignalType.DIN]
         _df_dout = self._df[self._df['chan_type'] == SignalType.DOUT]
         self._sig_map = {SignalType.AMP:
                          KEY_IDXS(ntv=_df_amp['ntv_key_idx'].to_list(),
                                   dset=_df_amp['dataset_key_idx'].to_list(),
                                   sys=_df_amp['sys_key_idx'].to_list()),
                          SignalType.AIN: KEY_IDXS(ntv=_df_ain['ntv_key_idx'].to_list(),
-                                                  dset=_df_ain['dataset_key_idx'].to_list(),
-                                                  sys=_df_ain['sys_key_idx'].to_list()),
+                                                  dset=_df_ain['dataset_key_idx'].to_list(
+                         ),
+                             sys=_df_ain['sys_key_idx'].to_list()),
                          SignalType.DIN: KEY_IDXS(ntv=_df_din['ntv_key_idx'].to_list(),
-                                                  dset=_df_din['dataset_key_idx'].to_list(),
-                                                  sys=_df_din['sys_key_idx'].to_list()),
+                                                  dset=_df_din['dataset_key_idx'].to_list(
+                         ),
+                             sys=_df_din['sys_key_idx'].to_list()),
                          SignalType.DOUT: KEY_IDXS(ntv=_df_dout['ntv_key_idx'].to_list(),
-                                                   dset=_df_dout['dataset_key_idx'].to_list(),
-                                                   sys=_df_dout['sys_key_idx'].to_list()),
+                                                   dset=_df_dout['dataset_key_idx'].to_list(
+                         ),
+                             sys=_df_dout['sys_key_idx'].to_list()),
                          }
         self._sel_sig_map = {SignalType.AMP:
                              KEY_IDXS(ntv=_df_amp[_df_amp['selected'] == True]['ntv_key_idx'].to_list(),
-                                      dset=_df_amp[_df_amp['selected'] == True]['dataset_key_idx'].to_list(),
+                                      dset=_df_amp[_df_amp['selected'] ==
+                                                   True]['dataset_key_idx'].to_list(),
                                       sys=_df_amp[_df_amp['selected'] == True]['sys_key_idx'].to_list()),
                              SignalType.AIN: KEY_IDXS(ntv=_df_ain[_df_ain['selected'] == True]['ntv_key_idx'].to_list(),
-                                                      dset=_df_ain[_df_ain['selected'] == True]['dataset_key_idx'].to_list(),
-                                                      sys=_df_ain[_df_ain['selected'] == True]['sys_key_idx'].to_list()),
+                                                      dset=_df_ain[_df_ain['selected'] == True]['dataset_key_idx'].to_list(
+                             ),
+                                 sys=_df_ain[_df_ain['selected'] == True]['sys_key_idx'].to_list()),
                              SignalType.DIN: KEY_IDXS(ntv=_df_din[_df_din['selected'] == True]['ntv_key_idx'].to_list(),
-                                                      dset=_df_din[_df_din['selected'] == True]['dataset_key_idx'].to_list(),
-                                                      sys=_df_din[_df_din['selected'] == True]['sys_key_idx'].to_list()),
+                                                      dset=_df_din[_df_din['selected'] == True]['dataset_key_idx'].to_list(
+                             ),
+                                 sys=_df_din[_df_din['selected'] == True]['sys_key_idx'].to_list()),
                              SignalType.DOUT: KEY_IDXS(ntv=_df_dout[_df_dout['selected'] == True]['ntv_key_idx'].to_list(),
-                                                       dset=_df_dout[_df_dout['selected'] == True]['dataset_key_idx'].to_list(),
-                                                       sys=_df_dout[_df_dout['selected'] == True]['sys_key_idx'].to_list()),
+                                                       dset=_df_dout[_df_dout['selected'] == True]['dataset_key_idx'].to_list(
+                             ),
+                                 sys=_df_dout[_df_dout['selected'] == True]['sys_key_idx'].to_list()),
                              }
         self._num_sigs = {}
         self._sel_num_sigs = {}
         for stype in ALL_SIGNAL_TYPES:
             self._num_sigs[stype] = len(self._sig_map[stype].ntv)
             self._sel_num_sigs[stype] = len(self._sel_sig_map[stype].ntv)
 
@@ -85,33 +95,30 @@
             >>> meta.index[SignalType.AIN]
             >>> KEY_IDXS(ntv=[3,2,0,1], dset=[0,1,2,3], sys=[35,34,32,33])  # signal has 32 AMP channels
 
         Notes:
 
         Index definitions:
           ``ntv`` is the position of the signal (channel) trace when the backing dataset
-        was created for each signal type.  For recording files, it is the position of the channels in the DAQ data stream or primary data file.
-        The ``ntv`` index starts at zero for each signal type.
+          was created for each signal type.  For recording files, it is the position of the channels in the DAQ data stream or primary data file. The ``ntv`` index starts at zero for each signal type.
 
-          ``dset`` is the position of a signal trace in the backing dataset for each signal type.  Unless the signal traces
-        in the dataset were re-ordered, ``dset`` will equal ``ntv``.
-         The ``dset`` index starts at zero for each signal type.
+          ``dset`` is the position of a signal trace in the backing dataset for each signal type.  Unless the signal traces in the dataset were re-ordered, ``dset`` will equal ``ntv``. The ``dset`` index starts at zero for each signal type.
 
           ``sys`` is the position of the signal (channel) trace when the backing dataset was created.
-        The ``sys`` index starts at zero and increases in natural order over all signal types alway in the following order: 'amp', 'gpio_ain', 'gpio_din', 'gpio_dout'.
+          The ``sys`` index starts at zero and increases in natural order over all signal types alway in the following order: 'amp', 'gpio_ain', 'gpio_din', 'gpio_dout'.
         """
         if stype not in self._sig_map:
             raise ValueError('stype not in signal map')
         return self._sig_map[stype]
 
     def sel_index(self, stype: SignalType) -> KEY_IDXS:
         """
         Selected signal indices by signal type and index type.
 
-        See ``'index'`` for more information on signal indices.
+        See :py:meth:`index` for more information on signal indices.
         """
         if stype not in self._sig_map:
             raise ValueError('stype not in signal map')
         return self._sel_sig_map[stype]
 
     def num_sigs(self, stype: SignalType) -> int:
         """
@@ -263,29 +270,37 @@
     _df.index.name = 'dyn_sort_idx'
 
     sensor_port_spec = {}
     for port in ['A', 'B', 'C', 'D', 'E', 'F', 'G', 'H']:
         sensor_port_spec[port] = []
     if raw_grpc is not None:
         for m, _ in enumerate(raw_grpc.sensorPortSpec.sensorA):
-            sensor_port_spec['A'].append(decode_grpc_sensor_port_spec(raw_grpc.sensorPortSpec.sensorA[m]))
+            sensor_port_spec['A'].append(decode_grpc_sensor_port_spec(
+                raw_grpc.sensorPortSpec.sensorA[m]))
         for m, _ in enumerate(raw_grpc.sensorPortSpec.sensorB):
-            sensor_port_spec['B'].append(decode_grpc_sensor_port_spec(raw_grpc.sensorPortSpec.sensorB[m]))
+            sensor_port_spec['B'].append(decode_grpc_sensor_port_spec(
+                raw_grpc.sensorPortSpec.sensorB[m]))
         for m, _ in enumerate(raw_grpc.sensorPortSpec.sensorC):
-            sensor_port_spec['C'].append(decode_grpc_sensor_port_spec(raw_grpc.sensorPortSpec.sensorC[m]))
+            sensor_port_spec['C'].append(decode_grpc_sensor_port_spec(
+                raw_grpc.sensorPortSpec.sensorC[m]))
         for m, _ in enumerate(raw_grpc.sensorPortSpec.sensorD):
-            sensor_port_spec['D'].append(decode_grpc_sensor_port_spec(raw_grpc.sensorPortSpec.sensorD[m]))
+            sensor_port_spec['D'].append(decode_grpc_sensor_port_spec(
+                raw_grpc.sensorPortSpec.sensorD[m]))
         for m, _ in enumerate(raw_grpc.sensorPortSpec.sensorE):
-            sensor_port_spec['E'].append(decode_grpc_sensor_port_spec(raw_grpc.sensorPortSpec.sensorE[m]))
+            sensor_port_spec['E'].append(decode_grpc_sensor_port_spec(
+                raw_grpc.sensorPortSpec.sensorE[m]))
         for m, _ in enumerate(raw_grpc.sensorPortSpec.sensorF):
-            sensor_port_spec['F'].append(decode_grpc_sensor_port_spec(raw_grpc.sensorPortSpec.sensorF[m]))
+            sensor_port_spec['F'].append(decode_grpc_sensor_port_spec(
+                raw_grpc.sensorPortSpec.sensorF[m]))
         for m, _ in enumerate(raw_grpc.sensorPortSpec.sensorG):
-            sensor_port_spec['G'].append(decode_grpc_sensor_port_spec(raw_grpc.sensorPortSpec.sensorG[m]))
+            sensor_port_spec['G'].append(decode_grpc_sensor_port_spec(
+                raw_grpc.sensorPortSpec.sensorG[m]))
         for m, _ in enumerate(raw_grpc.sensorPortSpec.sensorH):
-            sensor_port_spec['H'].append(decode_grpc_sensor_port_spec(raw_grpc.sensorPortSpec.sensorH[m]))
+            sensor_port_spec['H'].append(decode_grpc_sensor_port_spec(
+                raw_grpc.sensorPortSpec.sensorH[m]))
 
     return _df, sensor_port_spec
 
 
 def decode_grpc_sensor_port_spec(grpc_sensor):
     d = {'probe_id': grpc_sensor.probeId,
          'headstage_id': grpc_sensor.headstageId,
```

### Comparing `radiens-1.0.5/radiens/lib/dataset_metadata.py` & `radiens-1.0.6/radiens/lib/dataset_metadata.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/lib/fsys.py` & `radiens-1.0.6/radiens/lib/fsys.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/lib/graphics/_obsolete_dashboards/dash_datasets.py` & `radiens-1.0.6/radiens/lib/graphics/_obsolete_dashboards/dash_datasets.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/lib/graphics/_obsolete_dashboards/dash_metrics.py` & `radiens-1.0.6/radiens/lib/graphics/_obsolete_dashboards/dash_metrics.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/lib/graphics/_obsolete_dashboards/dash_psd.py` & `radiens-1.0.6/radiens/lib/graphics/_obsolete_dashboards/dash_psd.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/lib/graphics/_obsolete_dashboards/dash_snapshot.py` & `radiens-1.0.6/radiens/lib/graphics/_obsolete_dashboards/dash_snapshot.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/lib/graphics/_obsolete_dashboards/lib.py` & `radiens-1.0.6/radiens/lib/graphics/_obsolete_dashboards/lib.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/lib/graphics/dashboards/_obsolete_dash_sig_metrics.py` & `radiens-1.0.6/radiens/lib/graphics/dashboards/_obsolete_dash_sig_metrics.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/lib/graphics/dashboards/dash_psd.py` & `radiens-1.0.6/radiens/lib/graphics/dashboards/dash_psd.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/lib/graphics/dashboards/dash_sig_metrics.py` & `radiens-1.0.6/radiens/lib/graphics/dashboards/dash_sig_metrics.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/lib/graphics/dashboards/dash_snapshot.py` & `radiens-1.0.6/radiens/lib/graphics/dashboards/dash_snapshot.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/lib/graphics/dashboards/dash_t_range.py` & `radiens-1.0.6/radiens/lib/graphics/dashboards/dash_t_range.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/lib/graphics/dashboards/lib.py` & `radiens-1.0.6/radiens/lib/graphics/dashboards/lib.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/lib/graphics/graphics.py` & `radiens-1.0.6/radiens/lib/graphics/graphics.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/lib/selector_tables.py` & `radiens-1.0.6/radiens/lib/selector_tables.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/lib/sig_metrics.py` & `radiens-1.0.6/radiens/lib/sig_metrics.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/lib/signals_snapshot.py` & `radiens-1.0.6/radiens/lib/signals_snapshot.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/lib/spike_sorter.py` & `radiens-1.0.6/radiens/lib/spike_sorter.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/lib/spikes.py` & `radiens-1.0.6/radiens/lib/spikes.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/metrics_client.py` & `radiens-1.0.6/radiens/metrics_client.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/signals_client.py` & `radiens-1.0.6/radiens/signals_client.py`

 * *Files 4% similar despite different names*

```diff
@@ -43,26 +43,29 @@
         self.__parent: Union[AllegoClient,
                              VidereClient, CurateClient] = parent_client
 
     def get_signals(self,
                     time_range: TIME_RANGE = None,
                     sel_mode: TRS_MODE = None,
                     sig_sel: SIG_SELECT = None,
-                    dataset_metadata=None,
+                    dataset_metadata: DatasetMetadata = None,
                     hub_name=DEFAULT_HUB) -> Signals:
         """
         Gets the signals for specified time range
 
         Parameters:
-            dataset_id (str): dataset ID
-            time_range (list[float])
+            time_range (TIME_RANGE): see :py:meth:`~radiens.utils.util.make_time_range`
+            dataset_metadata: see :py:meth:`link_data_file` and :py:meth:`get_data_file_metadata`
+            sel_mode: optional (default :py:attr:`TRS_MODE.SUBSET`)
+            sig_sel: optional
+            hub_name: optional
+
 
         Returns:
-            sigarray (ndarray[numpy.float32]): raw signal data; the mapping contained in signal_group (see :py:meth:`get_signal_group`)
-            time_range (list[float])
+            signals (Signals)
         """
         if self.__parent.type not in ['allego'] and not isinstance(dataset_metadata, DatasetMetadata):
             raise ValueError(
                 'videre & curate: dataset_metadata must be provided')
         if not isinstance(time_range, TIME_RANGE):
             raise ValueError('time_range must be TIME_RANGE')
         if not isinstance(sel_mode, TRS_MODE):
```

### Comparing `radiens-1.0.5/radiens/spike_sorter.py` & `radiens-1.0.6/radiens/spike_sorter.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/spikes_client.py` & `radiens-1.0.6/radiens/spikes_client.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/utils/config.py` & `radiens-1.0.6/radiens/utils/config.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/utils/constants.py` & `radiens-1.0.6/radiens/utils/constants.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/utils/util.py` & `radiens-1.0.6/radiens/utils/util.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/videre_client.py` & `radiens-1.0.6/radiens/videre_client.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens/workspace_client.py` & `radiens-1.0.6/radiens/workspace_client.py`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/radiens.egg-info/PKG-INFO` & `radiens-1.0.6/radiens.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: radiens
-Version: 1.0.5
+Version: 1.0.6
 Summary: provides python API to RADIENS analytics platform
 Home-page: http://neuronexus.github.io
 Author: NeuroNexus
 Author-email: dkipke@neuronexus.com
 License: MIT
 Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python :: 3.10
```

### Comparing `radiens-1.0.5/radiens.egg-info/SOURCES.txt` & `radiens-1.0.6/radiens.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `radiens-1.0.5/setup.py` & `radiens-1.0.6/setup.py`

 * *Files identical despite different names*


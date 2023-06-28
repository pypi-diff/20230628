# Comparing `tmp/sparksampling-0.2.1.tar.gz` & `tmp/sparksampling-0.2.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "sparksampling-0.2.1.tar", last modified: Fri Mar 24 02:36:04 2023, max compression
+gzip compressed data, last modified: Sun Feb  2 00:00:00 2020, max compression
```

## Comparing `sparksampling-0.2.1.tar` & `sparksampling-0.2.2.tar`

### file list

```diff
@@ -1,63 +1,100 @@
-drwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)        0 2023-03-24 02:36:03.848186 sparksampling-0.2.1/
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)    11324 2022-09-06 14:22:04.000000 sparksampling-0.2.1/LICENSE
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)      250 2022-09-08 15:36:37.000000 sparksampling-0.2.1/MANIFEST.in
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)     1671 2023-03-24 02:36:03.846186 sparksampling-0.2.1/PKG-INFO
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)     1036 2022-09-08 15:36:37.000000 sparksampling-0.2.1/README.rst
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)       38 2023-03-24 02:36:03.848186 sparksampling-0.2.1/setup.cfg
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)     1549 2023-03-24 02:22:59.000000 sparksampling-0.2.1/setup.py
-drwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)        0 2023-03-24 02:36:03.342677 sparksampling-0.2.1/sparksampling/
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)        0 2022-09-12 04:14:09.000000 sparksampling-0.2.1/sparksampling/__init__.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)       22 2023-03-24 02:23:48.000000 sparksampling-0.2.1/sparksampling/_version.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)     3607 2023-01-16 07:53:55.000000 sparksampling-0.2.1/sparksampling/app.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)     6390 2022-09-08 15:36:37.000000 sparksampling-0.2.1/sparksampling/config.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)       60 2023-01-16 07:53:55.000000 sparksampling-0.2.1/sparksampling/default_app_config.py
-drwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)        0 2023-03-24 02:36:03.506839 sparksampling-0.2.1/sparksampling/engine/
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)      429 2023-01-16 07:53:55.000000 sparksampling-0.2.1/sparksampling/engine/__init__.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)     2619 2023-01-16 07:53:55.000000 sparksampling-0.2.1/sparksampling/engine/base_engine.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)      480 2023-01-16 07:53:55.000000 sparksampling-0.2.1/sparksampling/engine/dummy_engine.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)    11631 2023-01-16 07:53:55.000000 sparksampling-0.2.1/sparksampling/engine/rms_engine.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)     4552 2023-01-16 07:53:55.000000 sparksampling-0.2.1/sparksampling/engine/sms_engine.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)      398 2022-09-08 15:36:37.000000 sparksampling-0.2.1/sparksampling/engine/stop_engine.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)     1887 2023-01-16 07:53:55.000000 sparksampling-0.2.1/sparksampling/engine_factory.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)     1263 2023-01-16 07:53:55.000000 sparksampling-0.2.1/sparksampling/error.py
-drwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)        0 2023-03-24 02:36:03.581056 sparksampling-0.2.1/sparksampling/evaluation/
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)      937 2023-01-16 07:53:55.000000 sparksampling-0.2.1/sparksampling/evaluation/__init__.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)     1247 2023-01-16 07:53:55.000000 sparksampling-0.2.1/sparksampling/evaluation/base_hook.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)      215 2023-01-16 07:53:55.000000 sparksampling-0.2.1/sparksampling/evaluation/dummy_hook.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)      487 2023-01-16 07:53:55.000000 sparksampling-0.2.1/sparksampling/evaluation/hook_msg.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)      363 2023-01-16 07:53:55.000000 sparksampling-0.2.1/sparksampling/evaluation/warn_hook.py
-drwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)        0 2023-03-24 02:36:03.596058 sparksampling-0.2.1/sparksampling/evaluation_extension/
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)        0 2023-01-16 07:53:55.000000 sparksampling-0.2.1/sparksampling/evaluation_extension/__init__.py
-drwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)        0 2023-03-24 02:36:03.630054 sparksampling-0.2.1/sparksampling/evaluation_extension/dummy_extension/
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)       25 2023-01-16 07:53:55.000000 sparksampling-0.2.1/sparksampling/evaluation_extension/dummy_extension/__init__.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)      233 2023-01-16 07:53:55.000000 sparksampling-0.2.1/sparksampling/evaluation_extension/dummy_extension/dummy_hook.py
-drwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)        0 2023-03-24 02:36:03.704621 sparksampling-0.2.1/sparksampling/file_format/
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)      108 2022-09-08 15:36:37.000000 sparksampling-0.2.1/sparksampling/file_format/__init__.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)      731 2022-09-08 15:36:37.000000 sparksampling-0.2.1/sparksampling/file_format/base_file_format.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)     1364 2022-09-08 15:36:37.000000 sparksampling-0.2.1/sparksampling/file_format/csv_file_imp.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)     1006 2022-09-08 15:36:37.000000 sparksampling-0.2.1/sparksampling/file_format/file_factory.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)     5482 2022-12-05 15:01:39.000000 sparksampling-0.2.1/sparksampling/file_format/output_adapter.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)     3418 2022-09-08 15:36:37.000000 sparksampling-0.2.1/sparksampling/mixin.py
-drwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)        0 2023-03-24 02:36:03.747622 sparksampling-0.2.1/sparksampling/proto/
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)        0 2023-03-24 02:26:05.000000 sparksampling-0.2.1/sparksampling/proto/__init__.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)       55 2023-03-24 02:26:28.000000 sparksampling-0.2.1/sparksampling/proto/sampling_service_pb2.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)       60 2023-03-24 02:26:28.000000 sparksampling-0.2.1/sparksampling/proto/sampling_service_pb2_grpc.py
-drwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)        0 2023-03-24 02:36:03.835186 sparksampling-0.2.1/sparksampling/sample/
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)      103 2022-09-08 15:36:37.000000 sparksampling-0.2.1/sparksampling/sample/__init__.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)      622 2022-09-08 15:36:37.000000 sparksampling-0.2.1/sparksampling/sample/base_sampling.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)     2437 2022-09-08 15:36:37.000000 sparksampling-0.2.1/sparksampling/sample/cluster_sampling_imp.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)     1094 2022-09-08 15:36:37.000000 sparksampling-0.2.1/sparksampling/sample/random_sampling_imp.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)     1487 2022-09-08 15:36:37.000000 sparksampling-0.2.1/sparksampling/sample/sampling_factory.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)      869 2022-09-08 15:36:37.000000 sparksampling-0.2.1/sparksampling/sample/simple_sampling_imp.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)     3101 2022-10-20 09:11:56.000000 sparksampling-0.2.1/sparksampling/sample/stratified_sampling_imp.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)      163 2023-01-16 07:53:55.000000 sparksampling-0.2.1/sparksampling/sdk.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)     2797 2023-01-16 07:53:55.000000 sparksampling-0.2.1/sparksampling/service.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)     4821 2022-09-08 15:36:37.000000 sparksampling-0.2.1/sparksampling/utilities.py
-drwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)        0 2023-03-24 02:36:03.421262 sparksampling-0.2.1/sparksampling.egg-info/
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)     1671 2023-03-24 02:36:02.000000 sparksampling-0.2.1/sparksampling.egg-info/PKG-INFO
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)     1789 2023-03-24 02:36:03.000000 sparksampling-0.2.1/sparksampling.egg-info/SOURCES.txt
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)        1 2023-03-24 02:36:02.000000 sparksampling-0.2.1/sparksampling.egg-info/dependency_links.txt
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)       57 2023-03-24 02:36:02.000000 sparksampling-0.2.1/sparksampling.egg-info/entry_points.txt
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)        1 2022-11-04 16:10:28.000000 sparksampling-0.2.1/sparksampling.egg-info/not-zip-safe
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)      143 2023-03-24 02:36:02.000000 sparksampling-0.2.1/sparksampling.egg-info/requires.txt
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)       14 2023-03-24 02:36:02.000000 sparksampling-0.2.1/sparksampling.egg-info/top_level.txt
+-rw-r--r--   0        0        0      318 2020-02-02 00:00:00.000000 sparksampling-0.2.2/.editorconfig
+-rw-r--r--   0        0        0       66 2020-02-02 00:00:00.000000 sparksampling-0.2.2/.gitattributes
+-rw-r--r--   0        0        0      706 2020-02-02 00:00:00.000000 sparksampling-0.2.2/.pre-commit-config.yaml
+-rw-r--r--   0        0        0      296 2020-02-02 00:00:00.000000 sparksampling-0.2.2/.travis.yml
+-rw-r--r--   0        0        0      250 2020-02-02 00:00:00.000000 sparksampling-0.2.2/MANIFEST.in
+-rw-r--r--   0        0        0      773 2020-02-02 00:00:00.000000 sparksampling-0.2.2/RELEASE.md
+-rw-r--r--   0        0        0       62 2020-02-02 00:00:00.000000 sparksampling-0.2.2/pip.conf
+-rw-r--r--   0        0        0    11324 2020-02-02 00:00:00.000000 sparksampling-0.2.2/client/LICENSE
+-rw-r--r--   0        0        0      730 2020-02-02 00:00:00.000000 sparksampling-0.2.2/client/README.md
+-rw-r--r--   0        0        0      780 2020-02-02 00:00:00.000000 sparksampling-0.2.2/client/RELEASE.md
+-rw-r--r--   0        0        0     1159 2020-02-02 00:00:00.000000 sparksampling-0.2.2/client/pyproject.toml
+-rw-r--r--   0        0        0       46 2020-02-02 00:00:00.000000 sparksampling-0.2.2/client/dockerbuild/config.json
+-rw-r--r--   0        0        0      422 2020-02-02 00:00:00.000000 sparksampling-0.2.2/client/dockerbuild/ssc.Dockerfile
+-rw-r--r--   0        0        0       22 2020-02-02 00:00:00.000000 sparksampling-0.2.2/client/sparksampling_client/__init__.py
+-rw-r--r--   0        0        0      541 2020-02-02 00:00:00.000000 sparksampling-0.2.2/client/sparksampling_client/cli.py
+-rw-r--r--   0        0        0      716 2020-02-02 00:00:00.000000 sparksampling-0.2.2/client/sparksampling_client/config.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 sparksampling-0.2.2/client/sparksampling_client/logging.py
+-rw-r--r--   0        0        0      840 2020-02-02 00:00:00.000000 sparksampling-0.2.2/client/sparksampling_client/session.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 sparksampling-0.2.2/client/sparksampling_client/proto/__init__.py
+-rw-r--r--   0        0        0       55 2020-02-02 00:00:00.000000 sparksampling-0.2.2/client/sparksampling_client/proto/sampling_service_pb2.py
+-rw-r--r--   0        0        0       60 2020-02-02 00:00:00.000000 sparksampling-0.2.2/client/sparksampling_client/proto/sampling_service_pb2_grpc.py
+-rw-r--r--   0        0        0     1225 2020-02-02 00:00:00.000000 sparksampling-0.2.2/client/tests/test_apply.py
+-rw-r--r--   0        0        0  2988942 2020-02-02 00:00:00.000000 sparksampling-0.2.2/data/10w_x_10.csv
+-rw-r--r--   0        0        0       19 2020-02-02 00:00:00.000000 sparksampling-0.2.2/data/empty.csv
+-rw-r--r--   0        0        0     4026 2020-02-02 00:00:00.000000 sparksampling-0.2.2/data/iris.csv
+-rw-r--r--   0        0        0      101 2020-02-02 00:00:00.000000 sparksampling-0.2.2/data/relation-a.csv
+-rw-r--r--   0        0        0      205 2020-02-02 00:00:00.000000 sparksampling-0.2.2/data/relation-b.csv
+-rw-r--r--   0        0        0       80 2020-02-02 00:00:00.000000 sparksampling-0.2.2/data/relation-c.csv
+-rw-r--r--   0        0        0   943860 2020-02-02 00:00:00.000000 sparksampling-0.2.2/data/ten_million_top1k.csv
+-rw-r--r--   0        0        0    15359 2020-02-02 00:00:00.000000 sparksampling-0.2.2/data/unbalance_500v50_10.csv
+-rw-r--r--   0        0        0  1518641 2020-02-02 00:00:00.000000 sparksampling-0.2.2/data/unbalance_5w1k_10.csv
+-rw-r--r--   0        0        0  1634682 2020-02-02 00:00:00.000000 sparksampling-0.2.2/data/unbalance_5w5k_10.csv
+-rw-r--r--   0        0        0      354 2020-02-02 00:00:00.000000 sparksampling-0.2.2/dockerbuild/pysparksampling-dev.Dockerfile
+-rw-r--r--   0        0        0      332 2020-02-02 00:00:00.000000 sparksampling-0.2.2/dockerbuild/pysparksampling.Dockerfile
+-rw-r--r--   0        0        0     1902 2020-02-02 00:00:00.000000 sparksampling-0.2.2/example/extension-example/DEVELOP.md
+-rw-r--r--   0        0        0      939 2020-02-02 00:00:00.000000 sparksampling-0.2.2/example/extension-example/setup.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 sparksampling-0.2.2/example/extension-example/sparksampling/__init__.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 sparksampling-0.2.2/example/extension-example/sparksampling/evaluation_extension/__init__.py
+-rw-r--r--   0        0        0       32 2020-02-02 00:00:00.000000 sparksampling-0.2.2/example/extension-example/sparksampling/evaluation_extension/example_extension/__init__.py
+-rw-r--r--   0        0        0      237 2020-02-02 00:00:00.000000 sparksampling-0.2.2/example/extension-example/sparksampling/evaluation_extension/example_extension/example_extension.py
+-rw-r--r--   0        0        0      837 2020-02-02 00:00:00.000000 sparksampling-0.2.2/k8s/spark-sampling-deployment.yaml
+-rw-r--r--   0        0        0      167 2020-02-02 00:00:00.000000 sparksampling-0.2.2/k8s/spark-sampling-headless-service.yaml
+-rw-r--r--   0        0        0      404 2020-02-02 00:00:00.000000 sparksampling-0.2.2/k8s/spark-sampling-service.yaml
+-rwxr-xr-x   0        0        0      151 2020-02-02 00:00:00.000000 sparksampling-0.2.2/k8s/start.sh
+-rw-r--r--   0        0        0       22 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/__init__.py
+-rw-r--r--   0        0        0     3581 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/app.py
+-rw-r--r--   0        0        0     6601 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/config.py
+-rw-r--r--   0        0        0       60 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/default_app_config.py
+-rw-r--r--   0        0        0     1897 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/engine_factory.py
+-rw-r--r--   0        0        0     1263 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/error.py
+-rw-r--r--   0        0        0     3400 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/mixin.py
+-rw-r--r--   0        0        0      163 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/sdk.py
+-rw-r--r--   0        0        0     2684 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/service.py
+-rw-r--r--   0        0        0     4875 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/utilities.py
+-rw-r--r--   0        0        0      429 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/engine/__init__.py
+-rw-r--r--   0        0        0     2738 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/engine/base_engine.py
+-rw-r--r--   0        0        0      524 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/engine/dummy_engine.py
+-rw-r--r--   0        0        0    11737 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/engine/rms_engine.py
+-rw-r--r--   0        0        0     4650 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/engine/sms_engine.py
+-rw-r--r--   0        0        0      398 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/engine/stop_engine.py
+-rw-r--r--   0        0        0      937 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/evaluation/__init__.py
+-rw-r--r--   0        0        0     1224 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/evaluation/base_hook.py
+-rw-r--r--   0        0        0      215 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/evaluation/dummy_hook.py
+-rw-r--r--   0        0        0      487 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/evaluation/hook_msg.py
+-rw-r--r--   0        0        0      341 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/evaluation/warn_hook.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/evaluation_extension/__init__.py
+-rw-r--r--   0        0        0       25 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/evaluation_extension/dummy_extension/__init__.py
+-rw-r--r--   0        0        0      233 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/evaluation_extension/dummy_extension/dummy_hook.py
+-rw-r--r--   0        0        0      102 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/file_format/__init__.py
+-rw-r--r--   0        0        0      731 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/file_format/base_file_format.py
+-rw-r--r--   0        0        0     1394 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/file_format/csv_file_imp.py
+-rw-r--r--   0        0        0     1018 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/file_format/file_factory.py
+-rw-r--r--   0        0        0     5779 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/file_format/output_adapter.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/proto/__init__.py
+-rw-r--r--   0        0        0       55 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/proto/sampling_service_pb2.py
+-rw-r--r--   0        0        0       60 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/proto/sampling_service_pb2_grpc.py
+-rw-r--r--   0        0        0       97 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/sample/__init__.py
+-rw-r--r--   0        0        0      622 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/sample/base_sampling.py
+-rw-r--r--   0        0        0     2497 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/sample/cluster_sampling_imp.py
+-rw-r--r--   0        0        0     1095 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/sample/random_sampling_imp.py
+-rw-r--r--   0        0        0     1509 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/sample/sampling_factory.py
+-rw-r--r--   0        0        0      855 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/sample/simple_sampling_imp.py
+-rw-r--r--   0        0        0     3233 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling/sample/stratified_sampling_imp.py
+-rw-r--r--   0        0        0      417 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling_proto/README.md
+-rw-r--r--   0        0        0      659 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling_proto/pyproject.toml
+-rw-r--r--   0        0        0     7201 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling_proto/pb/sampling_service.proto
+-rw-r--r--   0        0        0       22 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling_proto/sparksampling_proto/__init__.py
+-rw-r--r--   0        0        0     7469 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling_proto/sparksampling_proto/sampling_service_pb2.py
+-rw-r--r--   0        0        0     5796 2020-02-02 00:00:00.000000 sparksampling-0.2.2/sparksampling_proto/sparksampling_proto/sampling_service_pb2_grpc.py
+-rw-r--r--   0        0        0     1289 2020-02-02 00:00:00.000000 sparksampling-0.2.2/tests/conftest.py
+-rw-r--r--   0        0        0     3302 2020-02-02 00:00:00.000000 sparksampling-0.2.2/tests/test_feature.py
+-rw-r--r--   0        0        0     6499 2020-02-02 00:00:00.000000 sparksampling-0.2.2/tests/test_rms_engine.py
+-rw-r--r--   0        0        0      874 2020-02-02 00:00:00.000000 sparksampling-0.2.2/tests/test_s3.py
+-rw-r--r--   0        0        0    13415 2020-02-02 00:00:00.000000 sparksampling-0.2.2/tests/test_sms_sampling.py
+-rw-r--r--   0        0        0      491 2020-02-02 00:00:00.000000 sparksampling-0.2.2/tests/utilities.py
+-rw-r--r--   0        0        0     8736 2020-02-02 00:00:00.000000 sparksampling-0.2.2/.gitignore
+-rw-r--r--   0        0        0    11324 2020-02-02 00:00:00.000000 sparksampling-0.2.2/LICENSE
+-rw-r--r--   0        0        0      972 2020-02-02 00:00:00.000000 sparksampling-0.2.2/README.md
+-rw-r--r--   0        0        0     1318 2020-02-02 00:00:00.000000 sparksampling-0.2.2/pyproject.toml
+-rw-r--r--   0        0        0     2117 2020-02-02 00:00:00.000000 sparksampling-0.2.2/PKG-INFO
```

### Comparing `sparksampling-0.2.1/LICENSE` & `sparksampling-0.2.2/client/LICENSE`

 * *Files identical despite different names*

### Comparing `sparksampling-0.2.1/README.rst` & `sparksampling-0.2.2/client/README.md`

 * *Files 22% similar despite different names*

```diff
@@ -1,41 +1,34 @@
-========================================
-sparksampling
-========================================
-``sparksampling`` is a PySpark-based sampling and data quality assessment GRPC service that supports containerized deployments and Spark on K8S
+This is a Python Grpc Stub for ``sparksampling``
 
+# sparksampling
+`sparksampling` is a PySpark-based sampling and data quality assessment GRPC service that supports containerized deployments and Spark on K8S
 
-Feature
-========================================
+
+## Feature
 
 - Common sampling methods: Random, Stratified, Simple
 - Relationship Sampling based on DAG and Topological sorting
 - Cloud Native and Spark on K8S support
 
 
-========================================
-QUICK START
-========================================
+# QUICK START
 
-Installation
-========================================
+## Installation
 
 The trial only requires direct installation using pypi
 
 ``pip install sparksampling``
 
 run as
 
 ``sparksampling``
 
 The service will start and listen on port 8530
 
-Docker
-========================================
+## Docker
 
 ``docker run -p 8530:8530 wh1isper/pysparksampling:latest``
 
-========================================
-MORE
-========================================
+# MORE
 
 For more, see our github page: https://github.com/Wh1isper/pyspark-sampling/
```

### Comparing `sparksampling-0.2.1/sparksampling/app.py` & `sparksampling-0.2.2/sparksampling/app.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,117 +1,115 @@
 import os
 
 import findspark
 
 findspark.init()
 
+import logging
 from concurrent import futures
+
+import grpc
 from pyspark import SparkConf
 from pyspark.sql import SparkSession
-import logging
-import grpc
+from traitlets import Instance, Integer, Unicode, default
+from traitlets.config import Application
+
+from sparksampling import __version__
 from sparksampling.config import SPARK_CONF
 from sparksampling.service import GRPCService
-from sparksampling._version import __version__
-from traitlets.config import Application
-from traitlets import (
-    Integer,
-    Unicode,
-    default,
-    Instance
-)
 
 
 class SparkSamplingAPP(Application):
-    name = 'sparksampling'
+    name = "sparksampling"
     description = """An application for starting a spark sampling server"""
     # the grpc server handle
     server = None
 
     ip = Unicode(
-        os.getenv('SERVICE_HOST', '0.0.0.0'), help="Host IP address for listening (default 0.0.0.0)."
+        os.getenv("SERVICE_HOST", "0.0.0.0"),
+        help="Host IP address for listening (default 0.0.0.0).",
     ).tag(config=True)
 
-    port = Integer(
-        int(os.getenv('SERVICE_PORT', 8530)), help="Port (default 8530)."
-    ).tag(config=True)
+    port = Integer(int(os.getenv("SERVICE_PORT", 8530)), help="Port (default 8530).").tag(
+        config=True
+    )
 
     spark_config = Instance(SparkConf)
     spark = Instance(SparkSession)
 
     config_file_path = Unicode(
-        os.path.expanduser('~/.ss/config.py'),
-        help="User defined app config path"
+        os.path.expanduser("~/.ss/config.py"), help="User defined app config path"
     ).tag(config=True)
 
-    @default('spark_config')
+    @default("spark_config")
     def _spark_config_default(self):
         return SPARK_CONF
 
-    @default('spark')
+    @default("spark")
     def _spark_default(self):
         return SparkSession.builder.config(conf=self.spark_config).getOrCreate()
 
-    @default('log_level')
+    @default("log_level")
     def _log_level_default(self):
         return logging.DEBUG
 
-    @default('log_datefmt')
+    @default("log_datefmt")
     def _log_datefmt_default(self):
         """Exclude date from default date format"""
         return "%Y-%m-%d %H:%M:%S"
 
-    @default('log_format')
+    @default("log_format")
     def _log_format_default(self):
         """override default log format to include time"""
         return "[%(levelname)1.1s %(asctime)s %(module)s:%(lineno)d] %(message)s"
 
     def load_config(self):
         dir_prefix = os.path.abspath(os.path.dirname(__file__))
-        self.load_config_file(os.path.join(dir_prefix, 'default_app_config.py'))
-        self.log.info(f'Loading user defined config from {self.config_file_path}')
+        self.load_config_file(os.path.join(dir_prefix, "default_app_config.py"))
+        self.log.info(f"Loading user defined config from {self.config_file_path}")
         self.load_config_file(self.config_file_path)
 
     def initialize(self, *args, **kwargs):
         self.load_config()
         super().initialize(*args, **kwargs)
         self.init_logger()
-        self.log.info(f'Current pyspark-sampling version: {__version__}')
+        self.log.info(f"Current pyspark-sampling version: {__version__}")
         self.init_spark()
 
     def init_logger(self):
-        logger = logging.getLogger('sparksampling')
+        logger = logging.getLogger("sparksampling")
         logger.propagate = True
         logger.parent = self.log
         logger.setLevel(self.log.level)
 
     def init_spark(self):
         self.log.info(f"Started SparkSession, Spark version: {self.spark.version}")
 
     def start(self, argv=None):
         self.initialize(argv)
         self._add_server()
-        self.server.add_insecure_port('%s:%d' % (self.ip, self.port))
+        self.server.add_insecure_port("%s:%d" % (self.ip, self.port))
         self.server.start()
-        self.log.info("Spark Sampling Server Listening On %s:%s..." %
-                      (self.ip, self.port))
+        self.log.info("Spark Sampling Server Listening On %s:%s..." % (self.ip, self.port))
         self.server.wait_for_termination()
 
     def _add_server(self):
         GRPCService.register_engine(self)
         engine_worker = GRPCService.get_worker_num()
         # need one reserve worker to reject request asap
         max_workers = engine_worker + 1
-        self.log.info(f'Service allocate {engine_worker} workers for engine and 1 reserve for response')
+        self.log.info(
+            f"Service allocate {engine_worker} workers for engine and 1 reserve for response"
+        )
         self.server = grpc.server(futures.ThreadPoolExecutor(max_workers=max_workers))
         GRPCService.add_to_server(self, self.server)
 
     @classmethod
     def launch(cls, argv=None):
         self = cls.instance()
         self.start(argv)
 
 
 main = SparkSamplingAPP.launch
 
-if __name__ == '__main__':
+if __name__ == "__main__":
     main()
```

### Comparing `sparksampling-0.2.1/sparksampling/config.py` & `sparksampling-0.2.2/sparksampling/config.py`

 * *Files 17% similar despite different names*

```diff
@@ -1,51 +1,51 @@
 import os
 import socket
 
 from kubernetes.config.incluster_config import SERVICE_TOKEN_FILENAME
 from pyspark import SparkConf
 from pyspark.sql import SparkSession
 
-DEPLOY_ON_K8S = os.environ.get('DEPLOY_ON_K8S', 'false') in ['true', 'True']
-INCLUSTER = os.path.exists('/var/run/secrets/kubernetes.io/serviceaccount/namespace')
+DEPLOY_ON_K8S = os.environ.get("DEPLOY_ON_K8S", "false") in ["true", "True"]
+INCLUSTER = os.path.exists("/var/run/secrets/kubernetes.io/serviceaccount/namespace")
 
 
 def get_namespace():
     if not INCLUSTER:
-        return 'spark-sampling'
-    if os.getenv('SPARK_EXECUTOR_NS'):
-        return os.getenv('SPARK_EXECUTOR_NS')
-    with open('/var/run/secrets/kubernetes.io/serviceaccount/namespace') as f:
+        return "spark-sampling"
+    if os.getenv("SPARK_EXECUTOR_NS"):
+        return os.getenv("SPARK_EXECUTOR_NS")
+    with open("/var/run/secrets/kubernetes.io/serviceaccount/namespace") as f:
         default_namespace = f.read()
     return default_namespace
 
 
 def get_k8s_config():
     from kubernetes import config
     from kubernetes.client import Configuration
 
     if INCLUSTER:
         config.load_incluster_config()
     else:
-        config.load_kube_config('/root/.kube/config')
+        config.load_kube_config("/root/.kube/config")
     k8s_config = Configuration.get_default_copy()
-    token = k8s_config.api_key.get('authorization')
+    token = k8s_config.api_key.get("authorization")
     host = k8s_config.host
     ca = k8s_config.ssl_ca_cert
     key_file = k8s_config.key_file
     cert_file = k8s_config.cert_file
 
     return host, token, ca, key_file, cert_file
 
 
 def get_host_ip():
     # only use for minikube debug
     try:
         s = socket.socket(socket.AF_INET, socket.SOCK_DGRAM)
-        s.connect(('8.8.8.8', 80))
+        s.connect(("8.8.8.8", 80))
         ip = s.getsockname()[0]
     finally:
         s.close()
     return ip
 
 
 def set_if_not_none(config_dict, k, v):
@@ -53,115 +53,128 @@
         config_dict[k] = v
 
 
 def get_platform_config():
     if DEPLOY_ON_K8S:
         url, token, ca, key_file, cert_file = get_k8s_config()
         master = f"k8s://{url}"
-        image = os.getenv('SPARK_EXECUTOR_IMAGE', 'wh1isper/pyspark-executor:latest')
+        image = os.getenv("SPARK_EXECUTOR_IMAGE", "wh1isper/pyspark-executor:latest")
 
-        label_names = os.getenv('SPARK_EXECUTOR_LABELS', '').split(',')
+        label_names = os.getenv("SPARK_EXECUTOR_LABELS", "").split(",")
         label_names = (label for label in label_names if label)
 
-        annotation_names = os.getenv('SPARK_EXECUTOR_ANNOTATIONS', '').split(',')
+        annotation_names = os.getenv("SPARK_EXECUTOR_ANNOTATIONS", "").split(",")
         annotation_names = (annotation for annotation in annotation_names if annotation)
 
         EXECUTOR_CONFIG = {
-            **{f'spark.kubernetes.executor.label.{label_name}': 'true' for label_name in label_names},
-            **{f'spark.kubernetes.executor.annotation.{annotation}': 'true' for annotation in annotation_names},
-            "spark.executor.instances": os.getenv('SPARK_EXECUTOR_NUMS', '3'),
+            **{
+                f"spark.kubernetes.executor.label.{label_name}": "true"
+                for label_name in label_names
+            },
+            **{
+                f"spark.kubernetes.executor.annotation.{annotation}": "true"
+                for annotation in annotation_names
+            },
+            "spark.executor.instances": os.getenv("SPARK_EXECUTOR_NUMS", "3"),
         }
 
         SCHEDULER_CONFIG = {
             "spark.master": master,
             "spark.kubernetes.authenticate.caCertFile": ca,
             "spark.kubernetes.authenticate.clientKeyFile": key_file,
             "spark.kubernetes.authenticate.clientCertFile": cert_file,
             "spark.kubernetes.container.image": image,
-            "spark.kubernetes.container.image.pullPolicy": 'IfNotPresent',
+            "spark.kubernetes.container.image.pullPolicy": "IfNotPresent",
             **EXECUTOR_CONFIG,
         }
 
         SCHEDULER_CONFIG = {k: v for k, v in SCHEDULER_CONFIG.items() if v is not None}
         if not INCLUSTER:
-            set_if_not_none(SCHEDULER_CONFIG, 'spark.driver.host', get_host_ip())
+            set_if_not_none(SCHEDULER_CONFIG, "spark.driver.host", get_host_ip())
         else:
-            SCHEDULER_CONFIG['spark.kubernetes.authenticate.oauthTokenFile'] = SERVICE_TOKEN_FILENAME
-            SCHEDULER_CONFIG['spark.driver.host'] = os.getenv('SPARK_DRIVER_HOST', 'spark-sampling-headless-service')
-            SCHEDULER_CONFIG['spark.driver.bindAddress'] = os.getenv('SPARK_DRIVER_BINDADDRESS', '0.0.0.0')
-            SCHEDULER_CONFIG['spark.kubernetes.driver.pod.name'] = os.getenv('SPARK_DRIVER_POD_NAME')
+            SCHEDULER_CONFIG[
+                "spark.kubernetes.authenticate.oauthTokenFile"
+            ] = SERVICE_TOKEN_FILENAME
+            SCHEDULER_CONFIG["spark.driver.host"] = os.getenv(
+                "SPARK_DRIVER_HOST", "spark-sampling-headless-service"
+            )
+            SCHEDULER_CONFIG["spark.driver.bindAddress"] = os.getenv(
+                "SPARK_DRIVER_BINDADDRESS", "0.0.0.0"
+            )
+            SCHEDULER_CONFIG["spark.kubernetes.driver.pod.name"] = os.getenv(
+                "SPARK_DRIVER_POD_NAME"
+            )
 
-        set_if_not_none(SCHEDULER_CONFIG, 'spark.kubernetes.namespace', get_namespace())
+        set_if_not_none(SCHEDULER_CONFIG, "spark.kubernetes.namespace", get_namespace())
     else:
         # as standalone
         SCHEDULER_CONFIG = {
-            "spark.master": os.environ.get('SPARK_MASTER', 'local[*]'),
-            "spark.driver.memory": os.environ.get('SPARK_DRIVER_MEMORY', '512m'),
+            "spark.master": os.environ.get("SPARK_MASTER", "local[*]"),
+            "spark.driver.memory": os.environ.get("SPARK_DRIVER_MEMORY", "512m"),
         }
     return SCHEDULER_CONFIG
 
 
 def get_s3_config():
-    AK = os.environ.get('S3_ACCESS_KEY', '')
-    SK = os.environ.get('S3_SECRET_KEY', '')
-    END_POINT = os.environ.get('S3_ENTRY_POINT', '')
+    AK = os.environ.get("S3_ACCESS_KEY", "")
+    SK = os.environ.get("S3_SECRET_KEY", "")
+    END_POINT = os.environ.get("S3_ENTRY_POINT", "")
     if not (AK and SK and END_POINT):
         return dict()
     return {
-        'spark.hadoop.fs.s3a.access.key': AK,
-        'spark.hadoop.fs.s3a.secret.key': SK,
-        'spark.hadoop.fs.s3a.endpoint': END_POINT,
-        "spark.hadoop.fs.s3a.path.style.access": os.environ.get('S3_PATH_STYLE_ACCESS', 'true'),
-
+        "spark.hadoop.fs.s3a.access.key": AK,
+        "spark.hadoop.fs.s3a.secret.key": SK,
+        "spark.hadoop.fs.s3a.endpoint": END_POINT,
+        "spark.hadoop.fs.s3a.path.style.access": os.environ.get("S3_PATH_STYLE_ACCESS", "true"),
         # write s3 improvement
-        'spark.hadoop.fs.s3a.bucket.all.committer.magic.enabled': 'true',
+        "spark.hadoop.fs.s3a.bucket.all.committer.magic.enabled": "true",
     }
 
 
 def get_nfs_mount_config():
-    volume_type = 'nfs'
-    volume_name = 'driver-nfs-mount'
-    mount_path = os.getenv('SPARK_EXECUTOR_VOLUNM_NFS_MOUNT_PATH')
-    remote_server = os.getenv('SPARK_EXECUTOR_VOLUNM_NFS_REMOTE_SERVER')
-    remote_path = os.getenv('SPARK_EXECUTOR_VOLUNM_NFS_REMOTE_PATH')
+    volume_type = "nfs"
+    volume_name = "driver-nfs-mount"
+    mount_path = os.getenv("SPARK_EXECUTOR_VOLUNM_NFS_MOUNT_PATH")
+    remote_server = os.getenv("SPARK_EXECUTOR_VOLUNM_NFS_REMOTE_SERVER")
+    remote_path = os.getenv("SPARK_EXECUTOR_VOLUNM_NFS_REMOTE_PATH")
     if not (mount_path and remote_path and remote_server):
         return dict()
 
     return {
-        f'spark.kubernetes.driver.volumes.{volume_type}.{volume_name}.mount.path': mount_path,
-        f'spark.kubernetes.driver.volumes.{volume_type}.{volume_name}.mount.readOnly': 'false',
-        f'spark.kubernetes.driver.volumes.{volume_type}.{volume_name}.options.server': remote_path,
-        f'spark.kubernetes.driver.volumes.{volume_type}.{volume_name}.options.path': remote_path,
+        f"spark.kubernetes.driver.volumes.{volume_type}.{volume_name}.mount.path": mount_path,
+        f"spark.kubernetes.driver.volumes.{volume_type}.{volume_name}.mount.readOnly": "false",
+        f"spark.kubernetes.driver.volumes.{volume_type}.{volume_name}.options.server": remote_path,
+        f"spark.kubernetes.driver.volumes.{volume_type}.{volume_name}.options.path": remote_path,
     }
 
 
 def get_pvc_mount_config():
-    pvc_name = os.getenv('SPARK_EXECUTOR_VOLUNM_PVC_NAME')
-    pvc_path = os.getenv('SPARK_EXECUTOR_VOLUNM_PVC_PATH')
+    pvc_name = os.getenv("SPARK_EXECUTOR_VOLUNM_PVC_NAME")
+    pvc_path = os.getenv("SPARK_EXECUTOR_VOLUNM_PVC_PATH")
     if not (pvc_name and pvc_path):
         return dict()
     return {
-        f'spark.kubernetes.executor.volumes.persistentVolumeClaim.{pvc_name}.mount.path': pvc_path,
-        f'spark.kubernetes.executor.volumes.persistentVolumeClaim.{pvc_name}.mount.readOnly': 'false',
+        f"spark.kubernetes.executor.volumes.persistentVolumeClaim.{pvc_name}.mount.path": pvc_path,
+        f"spark.kubernetes.executor.volumes.persistentVolumeClaim.{pvc_name}.mount.readOnly": "false",
     }
 
 
 def get_mount_config():
     return {
         **get_nfs_mount_config(),
         **get_pvc_mount_config(),
     }
 
 
 def get_spark_conf():
     all_config = {
-        "spark.submit.deployMode": 'client',
+        "spark.submit.deployMode": "client",
         **get_platform_config(),
-        "spark.app.name": os.environ.get('SPARK_APP_NAME', 'Spark Sampling APP'),
-        "spark.ui.port": os.environ.get('SPARK_UI_PORT', '12344'),
+        "spark.app.name": os.environ.get("SPARK_APP_NAME", "Spark Sampling APP"),
+        "spark.ui.port": os.environ.get("SPARK_UI_PORT", "12344"),
         **get_s3_config(),
         # scheduler as FAIR
         "spark.scheduler.mode": "FAIR",
     }
 
     config = []
     for k, v in all_config.items():
@@ -174,9 +187,9 @@
 SPARK_CONF = get_spark_conf()
 
 
 def get_spark():
     return SparkSession.builder.config(conf=SPARK_CONF).getOrCreate()
 
 
-if __name__ == '__main__':
+if __name__ == "__main__":
     spark = get_spark()
```

### Comparing `sparksampling-0.2.1/sparksampling/engine/base_engine.py` & `sparksampling-0.2.2/sparksampling/engine/base_engine.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,12 +1,12 @@
-import weakref
 import os
+import weakref
 
-from sparksampling.error import ProcessPreHookError, ProcessPostHookError
-from sparksampling.mixin import WorkerManagerMixin, SparkMixin
+from sparksampling.error import ProcessPostHookError, ProcessPreHookError
+from sparksampling.mixin import SparkMixin, WorkerManagerMixin
 
 
 class BaseEngine(WorkerManagerMixin):
     guarantee_worker = int(os.getenv("ENGINE_DEFAULT_WORKER_NUM", 10))
     evaluation_pre_hook = dict()
     evaluation_post_hook = dict()
     _cache_hook_instance = weakref.WeakValueDictionary()
@@ -27,54 +27,61 @@
         return False
 
     @classmethod
     def register_pre_hook(cls, hook):
         evaluation_pre_hook = cls.evaluation_pre_hook.setdefault(cls, set())
         if hook in evaluation_pre_hook:
             return
-        cls.log.info(f'Adding pre evaluation hook: {hook.__name__} to {cls.__name__}')
+        cls.log.info(f"Adding pre evaluation hook: {hook.__name__} to {cls.__name__}")
         evaluation_pre_hook.add(hook)
 
     @classmethod
     def register_post_hook(cls, hook):
         evaluation_post_hook = cls.evaluation_post_hook.setdefault(cls, set())
 
         if hook in evaluation_post_hook:
             return
-        cls.log.info(f'Adding post evaluation hook: {hook.__name__} to {cls.__name__}')
+        cls.log.info(f"Adding post evaluation hook: {hook.__name__} to {cls.__name__}")
         evaluation_post_hook.add(hook)
 
     @classmethod
     def _process_hook(cls, df, hooks, exception, period):
         metas = []
         for hook in hooks:
             try:
                 df, meta = cls.get_hook_instance(hook).process(df)
                 metas.append(meta.generate_proto_msg(period))
             except NotImplementedError:
-                raise exception(f'{period} hook raised, Not implemented hook:{hook} found in {hooks}')
+                raise exception(
+                    f"{period} hook raised, Not implemented hook:{hook} found in {hooks}"
+                )
             except Exception as e:
-                cls.log.info(f'Exception when processing df: {df} with hook: {hook} in period {period}')
+                cls.log.info(
+                    f"Exception when processing df: {df} with hook: {hook} in period {period}"
+                )
                 cls.logger.exception(e)
                 raise exception(str(e))
 
         return df, metas
 
     @classmethod
     def pre_hook(cls, df):
-        return cls._process_hook(df, cls.evaluation_pre_hook.get(cls, set()), ProcessPreHookError, 'pre')
+        return cls._process_hook(
+            df, cls.evaluation_pre_hook.get(cls, set()), ProcessPreHookError, "pre"
+        )
 
     @classmethod
     def post_hook(cls, df):
-        return cls._process_hook(df, cls.evaluation_post_hook.get(cls, set()), ProcessPostHookError, 'post')
+        return cls._process_hook(
+            df, cls.evaluation_post_hook.get(cls, set()), ProcessPostHookError, "post"
+        )
 
     @classmethod
     def get_hook_instance(cls, hook):
         return cls._cache_hook_instance.setdefault(hook, hook())
 
 
 class SparkBaseEngine(BaseEngine, SparkMixin):
-
     @classmethod
     def stop(cls, parent, job_id=None):
         # SparkStopEngine will cancel spark job
         return
```

### Comparing `sparksampling-0.2.1/sparksampling/engine/rms_engine.py` & `sparksampling-0.2.2/sparksampling/engine/rms_engine.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,73 +1,75 @@
 from concurrent.futures import ThreadPoolExecutor
+from graphlib import CycleError, TopologicalSorter
 from pprint import pformat
-from typing import List, Dict
-
-from graphlib import TopologicalSorter, CycleError
+from typing import Dict, List
 
 from sparksampling.engine.base_engine import SparkBaseEngine
 from sparksampling.engine_factory import EngineFactory
 from sparksampling.error import BadParamError
 from sparksampling.file_format import FileFormatFactory
-from sparksampling.mixin import acquire_worker, LogMixin, record_job_id
+from sparksampling.mixin import LogMixin, acquire_worker, record_job_id
 from sparksampling.proto.sampling_service_pb2 import RelationSamplingRequest
 from sparksampling.sample import SamplingFactory
 from sparksampling.utilities import check_spark_session
 
 
 def _check_param(conf):
     def check_duplicated_name(name):
         if name not in name_set:
             name_set.add(name)
         else:
-            raise BadParamError(f'Duplicated name: {name}')
+            raise BadParamError(f"Duplicated name: {name}")
 
     name_set = set()
-    for sampling_stage in conf.get('sampling_stages', []):
-        check_duplicated_name(sampling_stage['name'])
-        if not (sampling_stage.get('input_path') or sampling_stage.get('input_name')):
+    for sampling_stage in conf.get("sampling_stages", []):
+        check_duplicated_name(sampling_stage["name"])
+        if not (sampling_stage.get("input_path") or sampling_stage.get("input_name")):
             raise BadParamError(
-                f'Need at least one sampling source(input_path or input_name) for relation {pformat(sampling_stage)}')
+                f"Need at least one sampling source(input_path or input_name) for relation {pformat(sampling_stage)}"
+            )
 
-    for relation_stage in conf.get('relation_stage', []):
+    for relation_stage in conf.get("relation_stage", []):
         # check duplicate name
-        check_duplicated_name(relation_stage['name'])
-        for relation in relation_stage.get('relations', []):
-            if not (relation.get('relation_path') or relation.get('relation_name')):
+        check_duplicated_name(relation_stage["name"])
+        for relation in relation_stage.get("relations", []):
+            if not (relation.get("relation_path") or relation.get("relation_name")):
                 raise BadParamError(
-                    f'Need at least one relation source(relation_path or relation_name) for relation {pformat(relation_stage)}')
-            if not (relation.get('relation_col') or relation.get('input_col')):
+                    f"Need at least one relation source(relation_path or relation_name) for relation {pformat(relation_stage)}"
+                )
+            if not (relation.get("relation_col") or relation.get("input_col")):
                 raise BadParamError(
-                    f'Need at least one col(relation_col or input_col) for relation {pformat(relation_stage)}')
+                    f"Need at least one col(relation_col or input_col) for relation {pformat(relation_stage)}"
+                )
 
 
 def _set_default(conf):
     # allow empty stage for export or sampling only job
-    conf.setdefault('sampling_stages', [])
-    conf.setdefault('relation_stages', [])
+    conf.setdefault("sampling_stages", [])
+    conf.setdefault("relation_stages", [])
 
-    default_sampling_method = conf.get('default_sampling_method')
-    default_sampling_conf = conf.get('default_sampling_conf')
-    default_file_format = conf.get('default_file_format')
-    default_format_conf = conf.get('default_format_conf')
-    for sampling_stage in conf['sampling_stages']:
-        sampling_stage.setdefault('sampling_method', default_sampling_method)
-        sampling_stage.setdefault('sampling_conf', default_sampling_conf)
-        sampling_stage.setdefault('file_format', default_file_format)
-        sampling_stage.setdefault('format_conf', default_format_conf)
-    for relation_stage in conf['relation_stages']:
-        relation_stage.setdefault('file_format', default_file_format)
-        relation_stage.setdefault('format_conf', default_format_conf)
-        for relation in relation_stage.get('relations', []):
-            if not relation.get('relation_col'):
-                relation['relation_col'] = relation['input_col']
-            if not relation.get('input_col'):
-                relation['input_col'] = relation['relation_col']
-            relation.setdefault('file_format', default_file_format)
-            relation.setdefault('format_conf', default_format_conf)
+    default_sampling_method = conf.get("default_sampling_method")
+    default_sampling_conf = conf.get("default_sampling_conf")
+    default_file_format = conf.get("default_file_format")
+    default_format_conf = conf.get("default_format_conf")
+    for sampling_stage in conf["sampling_stages"]:
+        sampling_stage.setdefault("sampling_method", default_sampling_method)
+        sampling_stage.setdefault("sampling_conf", default_sampling_conf)
+        sampling_stage.setdefault("file_format", default_file_format)
+        sampling_stage.setdefault("format_conf", default_format_conf)
+    for relation_stage in conf["relation_stages"]:
+        relation_stage.setdefault("file_format", default_file_format)
+        relation_stage.setdefault("format_conf", default_format_conf)
+        for relation in relation_stage.get("relations", []):
+            if not relation.get("relation_col"):
+                relation["relation_col"] = relation["input_col"]
+            if not relation.get("input_col"):
+                relation["input_col"] = relation["relation_col"]
+            relation.setdefault("file_format", default_file_format)
+            relation.setdefault("format_conf", default_format_conf)
     return conf
 
 
 class JobStage(LogMixin):
     def __init__(self, spark, stage_config, name_df_map):
         self.spark = spark
         self.stage_config = stage_config
@@ -80,41 +82,44 @@
         self.pre_metas = []
         self.post_metas = []
 
         self._init_sample_imp()
         self._init_file_format()
 
     def _init_file_format(self):
-        self.file_format_imp = FileFormatFactory.get_file_imp(self.spark, self.file_format, self.format_conf)
+        self.file_format_imp = FileFormatFactory.get_file_imp(
+            self.spark, self.file_format, self.format_conf
+        )
 
     def _init_sample_imp(self):
         if not (self.sampling_method and self.sampling_conf):
             return
         self.sample_imp = SamplingFactory.get_sampling_imp(self.sampling_method, self.sampling_conf)
 
     def _build_relation_dataframe(self, input_df, relation):
-        relation_name = relation.get('relation_name')
+        relation_name = relation.get("relation_name")
         if relation_name:
             relation_df = self.name_df_map[relation_name]
         else:
             # using relation_path to construct dataframe
             relation_file_format = FileFormatFactory.get_file_imp(
-                self.spark,
-                relation['file_format'],
-                relation['format_conf']
+                self.spark, relation["file_format"], relation["format_conf"]
             )
             # no need to worry if spark read the same csv twice, spark only read once
-            relation_df = relation_file_format.read(relation['relation_path'])
+            relation_df = relation_file_format.read(relation["relation_path"])
 
         # python's way for self._df.join(relation_df, self._df.input_col == relation_df.relation_col, 'semi')
-        cond = [getattr(input_df, relation['input_col']) == getattr(relation_df, relation['relation_col'])]
-        return input_df.join(relation_df, cond, how='semi')
+        cond = [
+            getattr(input_df, relation["input_col"])
+            == getattr(relation_df, relation["relation_col"])
+        ]
+        return input_df.join(relation_df, cond, how="semi")
 
     def build_dataframe(self, pre_hook=None, post_hook=None):
-        self.log.debug(f'Starting building stage {self.name}')
+        self.log.debug(f"Starting building stage {self.name}")
         if self.input_name:
             self._df = self.name_df_map[self.input_name]
         else:
             self._df = self.file_format_imp.read(self.input_path)
 
         if pre_hook:
             self._df, self.pre_metas = pre_hook(self._df)
@@ -128,175 +133,180 @@
         if post_hook:
             self._df, self.post_metas = post_hook(self._df)
 
         self.name_df_map[self.name] = self._df
 
     @property
     def relations(self):
-        return self.stage_config.get('relations', [])
+        return self.stage_config.get("relations", [])
 
     @property
     def name(self):
-        return self.stage_config.get('name')
+        return self.stage_config.get("name")
 
     @property
     def sampling_method(self):
-        return self.stage_config.get('sampling_method')
+        return self.stage_config.get("sampling_method")
 
     @property
     def sampling_conf(self):
-        return self.stage_config.get('sampling_conf')
+        return self.stage_config.get("sampling_conf")
 
     @property
     def file_format(self):
-        return self.stage_config.get('file_format')
+        return self.stage_config.get("file_format")
 
     @property
     def format_conf(self):
-        return self.stage_config.get('format_conf')
+        return self.stage_config.get("format_conf")
 
     @property
     def output_path(self):
-        return self.stage_config.get('output_path')
+        return self.stage_config.get("output_path")
 
     @property
     def output_col(self):
-        return self.stage_config.get('output_col')
+        return self.stage_config.get("output_col")
 
     @property
     def input_name(self):
-        return self.stage_config.get('input_name')
+        return self.stage_config.get("input_name")
 
     @property
     def input_path(self):
-        return self.stage_config.get('input_path')
+        return self.stage_config.get("input_path")
 
     def export_dataframe(self):
         if self.output_path:
-            self.log.debug(f'Exporting stage {self.name} to {self.output_path}')
-            self.sampled_path = self.file_format_imp.write(self._df, self.output_path, self.output_col)
+            self.log.debug(f"Exporting stage {self.name} to {self.output_path}")
+            self.sampled_path = self.file_format_imp.write(
+                self._df, self.output_path, self.output_col
+            )
         else:
-            self.log.debug(f'Nothing to export for {self.name}')
+            self.log.debug(f"Nothing to export for {self.name}")
 
 
 class RMSEngine(SparkBaseEngine):
     # Relationship Mapping Sampling
-    def __init__(self,
-                 parent,
-                 sampling_stages: List[Dict],
-                 relation_stages: List[Dict],
-                 job_id: str,
-                 dry_run: bool,
-                 ):
+    def __init__(
+        self,
+        parent,
+        sampling_stages: List[Dict],
+        relation_stages: List[Dict],
+        job_id: str,
+        dry_run: bool,
+    ):
         super(RMSEngine, self).__init__()
         self.parent = parent
         self.sampling_stages = sampling_stages
         self.relation_stages = relation_stages
         self.job_id = job_id
         self.dry_run = dry_run
 
         self.name_stage_map = dict()
         self._init_name_stage_map()
 
     def _init_name_stage_map(self):
         for sampling_stage in self.sampling_stages:
-            self.name_stage_map[sampling_stage['name']] = sampling_stage
-            self.name_stage_map['type'] = 'sample'
+            self.name_stage_map[sampling_stage["name"]] = sampling_stage
+            self.name_stage_map["type"] = "sample"
         for relation_stages in self.relation_stages:
-            self.name_stage_map[relation_stages['name']] = relation_stages
-            self.name_stage_map['type'] = 'relation'
+            self.name_stage_map[relation_stages["name"]] = relation_stages
+            self.name_stage_map["type"] = "relation"
 
     @acquire_worker
     @check_spark_session
     @record_job_id
     def submit(self, *args, **kwargs):
         try:
             build_order = self._get_stage_order()
         except CycleError as e:
-            raise BadParamError(f'Loop detected: {str(e)}')
+            raise BadParamError(f"Loop detected: {str(e)}")
 
         spark_job_seq = self._process_spark_seq(build_order)
         result = self._get_seq_result(spark_job_seq)
         return result
 
     def _get_stage_order(self):
         topological_map = dict()
 
         for sampling_stage in self.sampling_stages:
-            rely_set = topological_map.setdefault(sampling_stage['name'], set())
-            rely_name = sampling_stage.get('input_name')
+            rely_set = topological_map.setdefault(sampling_stage["name"], set())
+            rely_name = sampling_stage.get("input_name")
             if rely_name:
                 rely_set.add(rely_name)
 
         for relation_stage in self.relation_stages:
-            rely_set = topological_map.setdefault(relation_stage['name'], set())
-            rely_name = relation_stage.get('input_name')
+            rely_set = topological_map.setdefault(relation_stage["name"], set())
+            rely_name = relation_stage.get("input_name")
             if rely_name:
                 rely_set.add(rely_name)
-            for relation in relation_stage.get('relations', []):
-                relation_name = relation.get('relation_name')
+            for relation in relation_stage.get("relations", []):
+                relation_name = relation.get("relation_name")
                 if relation_name:
                     rely_set.add(relation_name)
         self.log.debug(f"topological_map is {pformat(topological_map)}")
         build_order = list(TopologicalSorter(topological_map).static_order())
-        self.log.debug(f'topological sort result: {build_order}')
+        self.log.debug(f"topological sort result: {build_order}")
         return build_order
 
     def _process_spark_seq(self, build_order):
         job_seq = []
         name_df_map = dict()
         for name in build_order:
             stage = JobStage(self.spark, self.name_stage_map[name], name_df_map)
             stage.build_dataframe(self.pre_hook, self.post_hook)
             job_seq.append(stage)
         if self.dry_run:
-            self.log.info('Dry run, skip export dataframe')
+            self.log.info("Dry run, skip export dataframe")
             return
-        self.log.info('Generated spark job sequence, start exporting dataframe...')
+        self.log.info("Generated spark job sequence, start exporting dataframe...")
 
-        executors = int(self.spark.conf.get('spark.executor.instances', '1'))
+        executors = int(self.spark.conf.get("spark.executor.instances", "1"))
         with ThreadPoolExecutor(max_workers=executors) as executor:
             for stage in job_seq:
                 executor.submit(stage.export_dataframe)
         return job_seq
 
     def _get_seq_result(self, seq):
-        self.log.debug('Start collecting result...')
+        self.log.debug("Start collecting result...")
         if self.dry_run:
-            self.log.info('Dry run, nothing output')
+            self.log.info("Dry run, nothing output")
             return []
         result = []
         for job in seq:
             if job.sampled_path:
-                result.append({
-                    'name': job.name,
-                    'sampled_path': job.sampled_path,
-                    'hook_msg': job.pre_metas + job.post_metas
-                })
-        self.log.info(f'result collected: \n{pformat(result)}')
+                result.append(
+                    {
+                        "name": job.name,
+                        "sampled_path": job.sampled_path,
+                        "hook_msg": job.pre_metas + job.post_metas,
+                    }
+                )
+        self.log.info(f"result collected: \n{pformat(result)}")
         return result
 
     @classmethod
     def config(cls, kwargs):
         _check_param(kwargs)
         try:
             kwargs = _set_default(kwargs)
-            sampling_stages = kwargs.pop('sampling_stages')
-            relation_stages = kwargs.pop('relation_stages')
-            job_id = kwargs.pop('job_id')
-            dry_run = kwargs.pop('dry_run', False)
+            sampling_stages = kwargs.pop("sampling_stages")
+            relation_stages = kwargs.pop("relation_stages")
+            job_id = kwargs.pop("job_id")
+            dry_run = kwargs.pop("dry_run", False)
         except KeyError as e:
             cls.log.info(f"Missing required parameters {str(e)}")
             raise BadParamError(f"Missing required parameters {str(e)}")
 
         config_dict = {
-            'sampling_stages': sampling_stages,
-            'relation_stages': relation_stages,
-            'job_id': job_id,
-            'dry_run': dry_run,
+            "sampling_stages": sampling_stages,
+            "relation_stages": relation_stages,
+            "job_id": job_id,
+            "dry_run": dry_run,
         }
         cls.log.info(f"Initializing job conf... \n {pformat(config_dict)}")
         return config_dict
 
     @classmethod
     def is_matching(cls, request_type):
         return request_type == RelationSamplingRequest
```

### Comparing `sparksampling-0.2.1/sparksampling/engine/sms_engine.py` & `sparksampling-0.2.2/sparksampling/engine/sms_engine.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,35 +1,36 @@
-from os.path import abspath, join, exists, dirname, split
+from os.path import abspath, dirname, exists, join, split
 from pprint import pformat
 from typing import Dict
 from uuid import uuid4
 
 from sparksampling.engine.base_engine import SparkBaseEngine
 from sparksampling.engine_factory import EngineFactory
-from sparksampling.error import CustomErrorWithCode, BadParamError, ProcessError
+from sparksampling.error import BadParamError, CustomErrorWithCode, ProcessError
 from sparksampling.file_format.file_factory import FileFormatFactory
 from sparksampling.mixin import acquire_worker, record_job_id
 from sparksampling.proto.sampling_service_pb2 import SamplingRequest
 from sparksampling.sample import SamplingFactory
 from sparksampling.utilities import check_spark_session
 
 
 class SMSEngine(SparkBaseEngine):
     # Single Mapping Sampling
 
-    def __init__(self,
-                 parent,
-                 input_path: str,
-                 output_path: str,
-                 sampling_method: int,
-                 file_format: int,
-                 job_id: str,
-                 sampling_conf: Dict or None = None,
-                 format_conf: Dict or None = None
-                 ):
+    def __init__(
+        self,
+        parent,
+        input_path: str,
+        output_path: str,
+        sampling_method: int,
+        file_format: int,
+        job_id: str,
+        sampling_conf: Dict or None = None,
+        format_conf: Dict or None = None,
+    ):
         super(SMSEngine, self).__init__()
         self.parent = parent
         self.input_path = input_path
         self.output_path = output_path
         self.sampling_method = sampling_method
         self.file_format = file_format
         self.job_id = job_id
@@ -40,16 +41,20 @@
     @check_spark_session
     def submit(self, *args, **kwargs):
         sampling_imp, file_imp = self.get_spark_imp()
         return self.submit_spark_job(sampling_imp, file_imp)
 
     def get_spark_imp(self):
         try:
-            sampling_imp = SamplingFactory.get_sampling_imp(self.sampling_method, self.sampling_conf)
-            file_imp = FileFormatFactory.get_file_imp(self.spark, self.file_format, self.format_conf)
+            sampling_imp = SamplingFactory.get_sampling_imp(
+                self.sampling_method, self.sampling_conf
+            )
+            file_imp = FileFormatFactory.get_file_imp(
+                self.spark, self.file_format, self.format_conf
+            )
         except CustomErrorWithCode as e:
             raise e
         except (KeyError, ValueError) as e:
             self.log.info(f"Task initialization failed {e}")
             raise BadParamError(f"Check task configuration parameters {str(e)}")
         except Exception as e:
             self.log.exception(e)
@@ -65,44 +70,49 @@
         output_path = file_imp.write(df, self.output_path)
         self.log.info(f"The task is completed and the output file or directory is: {output_path}")
         return output_path, pre_metas + post_metas
 
     @classmethod
     def config(cls, kwargs):
         def _set_default_output_path(conf):
-            if exists(conf.get('input_path')):
+            if exists(conf.get("input_path")):
                 # when input_path = /{path_to_data}/{input_file_name}
                 # set default_output_path = /{path_to_data}/sampled/{input_file_name}-{uuid}
-                input_path = conf.get('input_path')
+                input_path = conf.get("input_path")
                 default_output_path = abspath(
-                    join(dirname(abspath(input_path)), "./sampled/", split(input_path)[-1] + '-' + str(uuid4())))
-                conf.setdefault('output_path', default_output_path)
+                    join(
+                        dirname(abspath(input_path)),
+                        "./sampled/",
+                        split(input_path)[-1] + "-" + str(uuid4()),
+                    )
+                )
+                conf.setdefault("output_path", default_output_path)
             else:
-                input_path = conf.get('input_path')
-                default_output_path = input_path.rstrip('/') + '-' + str(uuid4())
-                conf.setdefault('output_path', default_output_path)
+                input_path = conf.get("input_path")
+                default_output_path = input_path.rstrip("/") + "-" + str(uuid4())
+                conf.setdefault("output_path", default_output_path)
             return conf
 
         try:
             kwargs = _set_default_output_path(kwargs)
             required_conf = {
-                'input_path': kwargs.pop('input_path'),
-                'output_path': kwargs.pop('output_path'),
-                'sampling_method': kwargs.pop('sampling_method'),
-                'file_format': kwargs.pop('file_format'),
-                'job_id': kwargs.pop('job_id')
+                "input_path": kwargs.pop("input_path"),
+                "output_path": kwargs.pop("output_path"),
+                "sampling_method": kwargs.pop("sampling_method"),
+                "file_format": kwargs.pop("file_format"),
+                "job_id": kwargs.pop("job_id"),
             }
         except KeyError as e:
             cls.log.info(f"Missing required parameters {str(e)}")
             raise BadParamError(f"Missing required parameters {str(e)}")
 
         # Detailed configuration depends on the specific implementation
         conf = {
-            'sampling_conf': kwargs.get('sampling_conf', {}),
-            'format_conf': kwargs.get('format_conf', {}),
+            "sampling_conf": kwargs.get("sampling_conf", {}),
+            "format_conf": kwargs.get("format_conf", {}),
         }
         conf.update(required_conf)
         cls.log.info(f"Initializing job conf... \n {pformat(conf)}")
         return conf
 
     @classmethod
     def is_matching(cls, request_type):
```

### Comparing `sparksampling-0.2.1/sparksampling/engine_factory.py` & `sparksampling-0.2.2/sparksampling/engine_factory.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,9 +1,9 @@
-from pprint import pformat
 import importlib
+from pprint import pformat
 
 from google.protobuf.json_format import MessageToDict
 
 from sparksampling.error import BadParamError, ProcessError
 from sparksampling.mixin import LogMixin
 
 
@@ -12,45 +12,47 @@
 
     @classmethod
     def choose_engine(cls, request_type):
         engine_cls = None
         for engine in cls.engine_cls:
             if engine.is_matching(request_type):
                 if engine_cls:
-                    raise ProcessError(f"Duplicated Engine Found: {engine.__name__} and {engine_cls.__name__}")
+                    raise ProcessError(
+                        f"Duplicated Engine Found: {engine.__name__} and {engine_cls.__name__}"
+                    )
                 engine_cls = engine
         return engine_cls
 
     @classmethod
     def get_engine(cls, parent, request_type, **kwargs):
         engine_cls = cls.choose_engine(request_type)
         if not engine_cls:
-            raise BadParamError(f'No matching engine for this job, \n{pformat(kwargs, indent=2)}')
+            raise BadParamError(f"No matching engine for this job, \n{pformat(kwargs, indent=2)}")
         cls.log.info(f"Using {engine_cls.__name__}")
         return engine_cls(parent, **engine_cls.config(kwargs))
 
     @classmethod
     def message_to_dict(cls, message):
-        data = MessageToDict(message,
-                             use_integers_for_enums=True,
-                             preserving_proto_field_name=True)
+        data = MessageToDict(message, use_integers_for_enums=True, preserving_proto_field_name=True)
         return data
 
     @classmethod
     def cancel_job(cls, parent, job_id):
         for engine in cls.engine_cls:
             engine.stop(parent, job_id)
 
     @classmethod
     def register(cls, engine_class):
         if engine_class in cls.engine_cls:
             return
-        cls.log.info(f'Register engine: {engine_class.__name__}, allocate {engine_class.guarantee_worker} workers')
+        cls.log.info(
+            f"Register engine: {engine_class.__name__}, allocate {engine_class.guarantee_worker} workers"
+        )
         cls.engine_cls.add(engine_class)
 
     @staticmethod
     def register_all_engine():
-        importlib.import_module('sparksampling.engine')
+        importlib.import_module("sparksampling.engine")
 
     @classmethod
     def get_engine_total_worker(cls):
         return sum(engine.guarantee_worker for engine in cls.engine_cls)
```

### Comparing `sparksampling-0.2.1/sparksampling/error.py` & `sparksampling-0.2.2/sparksampling/error.py`

 * *Files 9% similar despite different names*

```diff
@@ -13,16 +13,16 @@
         self.errorinfo = error_info
 
     def __str__(self):
         return self.errorinfo
 
     def error_response(self):
         return {
-            'code': self.code,
-            'message': self.errorinfo,
+            "code": self.code,
+            "message": self.errorinfo,
         }
 
 
 class ExhaustedError(CustomErrorWithCode):
     def __init__(self, msg: str):
         super(ExhaustedError, self).__init__(EXHAUSTED_ERROR, msg)
```

### Comparing `sparksampling-0.2.1/sparksampling/evaluation/__init__.py` & `sparksampling-0.2.2/sparksampling/evaluation/__init__.py`

 * *Files 22% similar despite different names*

```diff
@@ -1,18 +1,18 @@
 # import all .py from in this dir
-import os
-from os.path import dirname, basename, isfile, join
 import glob
 import importlib
+import os
+from os.path import basename, dirname, isfile, join
 
 modules = glob.glob(join(dirname(__file__), "*.py"))
-sub_packages = (basename(f)[:-3] for f in modules if isfile(f) and not f.endswith('__init__.py'))
-packages = (str(__package__) + '.' + i for i in sub_packages)
+sub_packages = (basename(f)[:-3] for f in modules if isfile(f) and not f.endswith("__init__.py"))
+packages = (str(__package__) + "." + i for i in sub_packages)
 [importlib.import_module(p) for p in packages]
 
-evaluation_module_name = 'evaluation_extension'
-evaluation_extension_path = os.path.join(os.path.dirname(__file__), f'../{evaluation_module_name}')
+evaluation_module_name = "evaluation_extension"
+evaluation_extension_path = os.path.join(os.path.dirname(__file__), f"../{evaluation_module_name}")
 evaluation_sub_folders = (f.name for f in os.scandir(evaluation_extension_path) if f.is_dir())
-sub_packages = (f for f in evaluation_sub_folders if not (f.endswith('__') or f.startswith('__')))
-evaluation_package = '.'.join((str(__package__).split('.'))[:-1])
-packages = [evaluation_package + '.' + evaluation_module_name + '.' + i for i in sub_packages]
+sub_packages = (f for f in evaluation_sub_folders if not (f.endswith("__") or f.startswith("__")))
+evaluation_package = ".".join((str(__package__).split("."))[:-1])
+packages = [evaluation_package + "." + evaluation_module_name + "." + i for i in sub_packages]
 [importlib.import_module(p) for p in packages]
```

### Comparing `sparksampling-0.2.1/sparksampling/evaluation/base_hook.py` & `sparksampling-0.2.2/sparksampling/evaluation/base_hook.py`

 * *Files 6% similar despite different names*

```diff
@@ -2,15 +2,15 @@
 
 from pyspark.sql import DataFrame
 
 from sparksampling.engine_factory import EngineFactory
 from sparksampling.evaluation.hook_msg import HookMsg
 
 
-class BaseEvaluationHook():
+class BaseEvaluationHook:
     def process(self, df: DataFrame) -> (DataFrame, HookMsg):
         df, msg = self._process(df)
         return df, HookMsg(self, msg)
 
     def _process(self, df) -> (DataFrame, Dict):
         raise NotImplementedError
 
@@ -36,13 +36,12 @@
         for engine in cls._get_all_engine():
             cls.register_post_hook(engine)
 
 
 class ByPassEvaluationHook(BaseEvaluationHook):
     # this hook for test use
     def _process(self, df):
-        return df, {
-            'msg': 'bypass'
-        }
+        return df, {"msg": "bypass"}
+
 
 # ByPassEvaluationHook.register_pre_hook_all()
 # ByPassEvaluationHook.register_post_hook_all()
```

### Comparing `sparksampling-0.2.1/sparksampling/file_format/base_file_format.py` & `sparksampling-0.2.2/sparksampling/file_format/base_file_format.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,19 +1,19 @@
-from pyspark.sql import SparkSession, DataFrame
+from pyspark.sql import DataFrame, SparkSession
 
 from sparksampling.mixin import LogMixin
 
 
 class SparkBaseFileFormat(LogMixin):
     cls_args = []
 
     @classmethod
     def get_init_conf(cls, conf):
         if not cls.cls_args:
-            cls.log.warning('No parameters to initialize?')
+            cls.log.warning("No parameters to initialize?")
             return dict
         init_conf = dict()
         for arg in cls.cls_args:
             if conf.get(arg):
                 init_conf[arg] = conf.get(arg)
         return init_conf
```

### Comparing `sparksampling-0.2.1/sparksampling/file_format/csv_file_imp.py` & `sparksampling-0.2.2/sparksampling/file_format/csv_file_imp.py`

 * *Files 15% similar despite different names*

```diff
@@ -1,30 +1,32 @@
 import os
 
 from sparksampling.file_format.base_file_format import SparkBaseFileFormat
 from sparksampling.file_format.output_adapter import OutputAdapterMixin
 
 
 class CsvFileImpSpark(SparkBaseFileFormat, OutputAdapterMixin):
-    cls_args = ['with_header', 'sep']
+    cls_args = ["with_header", "sep"]
 
     def __init__(self, spark, *args, **kwargs):
         super(CsvFileImpSpark, self).__init__(spark, *args, **kwargs)
-        self.with_header = kwargs.pop('with_header', False)
-        default_sep = '\001' if not os.getenv('COMMA_SEP') else ','
-        self.sep = kwargs.pop('sep', default_sep)
+        self.with_header = kwargs.pop("with_header", False)
+        default_sep = "\001" if not os.getenv("COMMA_SEP") else ","
+        self.sep = kwargs.pop("sep", default_sep)
 
     def read(self, input_path):
         return self.spark.read.csv(input_path, sep=self.sep, header=self.with_header)
 
     def write(self, df, output_path, output_col=None):
         if output_col:
-            self.log.info(f'Write to the specified columns: {output_col}')
+            self.log.info(f"Write to the specified columns: {output_col}")
             df = df[output_col]
         # When repartition(1), spark will write to a single file
         # Usually this is better for other applications, but there is a performance penalty
-        if os.getenv('NO_REPARTITION'):
-            df.write.csv(output_path, sep=self.sep, header=self.with_header, mode='overwrite')
+        if os.getenv("NO_REPARTITION"):
+            df.write.csv(output_path, sep=self.sep, header=self.with_header, mode="overwrite")
         else:
-            df.repartition(1).write.csv(output_path, sep=self.sep, header=self.with_header, mode='overwrite')
+            df.repartition(1).write.csv(
+                output_path, sep=self.sep, header=self.with_header, mode="overwrite"
+            )
 
         return self._get_sampled_file(output_path, sep=self.sep, spark=self.spark)
```

### Comparing `sparksampling-0.2.1/sparksampling/file_format/file_factory.py` & `sparksampling-0.2.2/sparksampling/file_format/file_factory.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,16 +1,12 @@
 from sparksampling.error import BadParamError
-
-from sparksampling.proto.sampling_service_pb2 import (
-    FILE_FORMAT_CSV
-)
 from sparksampling.file_format.base_file_format import SparkBaseFileFormat
 from sparksampling.file_format.csv_file_imp import CsvFileImpSpark
-
 from sparksampling.mixin import LogMixin
+from sparksampling.proto.sampling_service_pb2 import FILE_FORMAT_CSV
 
 
 class FileFormatFactory(LogMixin):
     format_map = {
         FILE_FORMAT_CSV: CsvFileImpSpark,
     }
 
@@ -23,8 +19,10 @@
 
     @classmethod
     def _get_format_conf(cls, file_format, format_conf):
         return cls.format_map[file_format].get_init_conf(format_conf)
 
     @classmethod
     def get_file_imp(cls, spark, file_format, format_conf) -> SparkBaseFileFormat:
-        return cls._get_imp_class(file_format)(spark, **cls._get_format_conf(file_format, format_conf))
+        return cls._get_imp_class(file_format)(
+            spark, **cls._get_format_conf(file_format, format_conf)
+        )
```

### Comparing `sparksampling-0.2.1/sparksampling/file_format/output_adapter.py` & `sparksampling-0.2.2/sparksampling/file_format/output_adapter.py`

 * *Files 11% similar despite different names*

```diff
@@ -1,14 +1,14 @@
-import os
 import errno
+import os
 from concurrent.futures import ThreadPoolExecutor as PoolExecutor
 
-from sparksampling.error import ProcessError
 import pandas as pd
 
+from sparksampling.error import ProcessError
 from sparksampling.mixin import LogMixin
 
 
 def fsync_dir(dir_path):
     """
     Execute fsync on a directory ensuring it is synced to disk
 
@@ -34,107 +34,130 @@
     @staticmethod
     def _merge_local_csv(dir_prefix, csv_files: list, sep):
         merge_file_name = csv_files.pop(0)
         merged_csv_path = os.path.join(dir_prefix, merge_file_name)
 
         def append_to_file(chunk_file):
             chunk_file_path = os.path.join(dir_prefix, chunk_file)
-            with pd.read_csv(chunk_file_path, sep=sep, chunksize=100000, dtype='string') as reader:
+            with pd.read_csv(chunk_file_path, sep=sep, chunksize=100000, dtype="string") as reader:
                 for chunk in reader:
-                    chunk.to_csv(merged_csv_path, sep=sep, mode='a', index=False, )
+                    chunk.to_csv(
+                        merged_csv_path,
+                        sep=sep,
+                        mode="a",
+                        index=False,
+                    )
             os.remove(chunk_file_path)
 
         list(map(append_to_file, csv_files))
         return merge_file_name
 
     @classmethod
     def _merge_local_csv_parallel(cls, abs_output_path, merge_file_names, sep):
         if len(merge_file_names) == 1:
             return os.path.join(abs_output_path, merge_file_names[0])
         pool = []
         for i in range(0, len(merge_file_names), cls.MERGE_CHUNK_SIZE):
-            p = cls.executor.submit(cls._merge_local_csv,
-                                    abs_output_path=abs_output_path,
-                                    csv_files=merge_file_names[i:i + cls.MERGE_CHUNK_SIZE],
-                                    sep=sep)
+            p = cls.executor.submit(
+                cls._merge_local_csv,
+                abs_output_path=abs_output_path,
+                csv_files=merge_file_names[i : i + cls.MERGE_CHUNK_SIZE],
+                sep=sep,
+            )
             pool.append(p)
 
         merge_file_names = [p.result() for p in pool]
 
         return cls._merge_local_csv_parallel(abs_output_path, merge_file_names, sep)
 
     @classmethod
     def _merge_local_file(cls, abs_output_path, csv_files, sep):
 
         if not cls.MERGE_CHUNK_SIZE or cls.MERGE_CHUNK_SIZE == 1:
-            return os.path.join(abs_output_path,
-                                cls._merge_local_csv(dir_prefix=abs_output_path, csv_files=csv_files, sep=sep))
+            return os.path.join(
+                abs_output_path,
+                cls._merge_local_csv(dir_prefix=abs_output_path, csv_files=csv_files, sep=sep),
+            )
         else:
             return cls._merge_local_csv_parallel(abs_output_path, csv_files, sep)
 
     @classmethod
     def _get_local_sampled_file(cls, output_path, sep):
         abs_dir = os.path.abspath(output_path)
-        csv_files = sorted([filename for filename in os.listdir(abs_dir) if filename.endswith('.csv')])
+        csv_files = sorted(
+            [filename for filename in os.listdir(abs_dir) if filename.endswith(".csv")]
+        )
         if not csv_files:
-            raise ProcessError('csv file not found')
+            raise ProcessError("csv file not found")
         if len(csv_files) > 1:
-            if os.getenv('NO_REPARTITION'):
-                cls.log.info(f"No repartition and no merge for files:  {csv_files[:10]}...(only show top 10)")
+            if os.getenv("NO_REPARTITION"):
+                cls.log.info(
+                    f"No repartition and no merge for files:  {csv_files[:10]}...(only show top 10)"
+                )
                 return abs_dir
-            cls.log.info(f"Start merging sampling files {len(csv_files)}: {csv_files[:10]}...(only show top 10)", )
+            cls.log.info(
+                f"Start merging sampling files {len(csv_files)}: {csv_files[:10]}...(only show top 10)",
+            )
             csv_file = cls._merge_local_file(abs_dir, csv_files, sep)
         else:
             csv_file = csv_files[0]
         cls.log.debug(f"Output one file: {csv_file}")
         fsync_dir(abs_dir)
         return os.path.join(abs_dir, csv_file)
 
 
 class S3OutputAdapterMixin(LogMixin):
     MERGE_CHUNK_SIZE = 0
     executor = PoolExecutor(os.cpu_count() or 1)
-    s3_theme = 's3a://'
+    s3_theme = "s3a://"
 
     @classmethod
     def _get_s3_sampled_file(cls, output_path, sep, spark):
         def get_s3_conf():
             spark_conf = spark.sparkContext.getConf()
             return {
-                'aws_access_key_id': spark_conf.get('spark.hadoop.fs.s3a.access.key'),
-                'aws_secret_access_key': spark_conf.get('spark.hadoop.fs.s3a.secret.key'),
-                'endpoint_url': spark_conf.get('spark.hadoop.fs.s3a.endpoint')
+                "aws_access_key_id": spark_conf.get("spark.hadoop.fs.s3a.access.key"),
+                "aws_secret_access_key": spark_conf.get("spark.hadoop.fs.s3a.secret.key"),
+                "endpoint_url": spark_conf.get("spark.hadoop.fs.s3a.endpoint"),
             }
 
         # Experimental function, no need for now
         import boto3
-        session = boto3.resource('s3', **get_s3_conf(), verify=False)
-        s3_path = output_path.replace(cls.s3_theme, '')
-        bucket_name, dir_path = s3_path.split('/', 1)
+
+        session = boto3.resource("s3", **get_s3_conf(), verify=False)
+        s3_path = output_path.replace(cls.s3_theme, "")
+        bucket_name, dir_path = s3_path.split("/", 1)
         bucket = session.Bucket(bucket_name)
 
-        csv_files = sorted([
-            object_summary.key for object_summary in bucket.objects.filter(Prefix=dir_path)
-            if object_summary.key.endswith('.csv')
-        ])
+        csv_files = sorted(
+            [
+                object_summary.key
+                for object_summary in bucket.objects.filter(Prefix=dir_path)
+                if object_summary.key.endswith(".csv")
+            ]
+        )
 
         if len(csv_files) > 1:
-            cls.log.info(f"Generate multiple csv files, s3 does not support automatic merging yet: {csv_files}", )
+            cls.log.info(
+                f"Generate multiple csv files, s3 does not support automatic merging yet: {csv_files}",
+            )
             return output_path
         else:
             csv_file = csv_files[0]
         cls.log.debug(f"Output one file: {csv_file}")
-        return cls.s3_theme + '/'.join([bucket_name, csv_file])
+        return cls.s3_theme + "/".join([bucket_name, csv_file])
 
 
 class OutputAdapterMixin(LocalAdapterMixin, S3OutputAdapterMixin):
     MERGE_CHUNK_SIZE = 0
     executor = PoolExecutor(os.cpu_count() or 1)
 
     @classmethod
     def _get_sampled_file(cls, output_path, sep, spark=None):
         if output_path.startswith(cls.s3_theme):
             return cls._get_s3_sampled_file(output_path, sep, spark)
         if os.path.exists(output_path):
             return cls._get_local_sampled_file(output_path, sep)
-        cls.log.info(f"Unsupported file path conversion method, returns the original path: {output_path}")
+        cls.log.info(
+            f"Unsupported file path conversion method, returns the original path: {output_path}"
+        )
         return output_path
```

### Comparing `sparksampling-0.2.1/sparksampling/mixin.py` & `sparksampling-0.2.2/sparksampling/mixin.py`

 * *Files 4% similar despite different names*

```diff
@@ -87,20 +87,21 @@
     """
     Decorate methods
     Set job_id to Engine, Currently supports spark
     """
 
     @functools.wraps(method)
     def wrapper(self, *args, **kwargs):
-        job_id = kwargs.get('job_id', getattr(self, 'job_id', None))
+        job_id = kwargs.get("job_id", getattr(self, "job_id", None))
         if isinstance(self, SparkMixin) and job_id:
-            self.log.info(f'Setting Spark job group: {job_id}')
-            self.spark.sparkContext.setLogLevel('ERROR')
-            self.spark.sparkContext.setJobGroup(job_id, f'Submitted by {self.__class__.__name__}',
-                                                interruptOnCancel=True)
+            self.log.info(f"Setting Spark job group: {job_id}")
+            self.spark.sparkContext.setLogLevel("ERROR")
+            self.spark.sparkContext.setJobGroup(
+                job_id, f"Submitted by {self.__class__.__name__}", interruptOnCancel=True
+            )
             # config for scheduler.mode: FAIR
             self.spark.sparkContext.setLocalProperty("spark.scheduler.pool", job_id)
         result = method(self, *args, **kwargs)
         return result
 
     return wrapper
 
@@ -109,16 +110,16 @@
     _spark = None
 
     @property
     def spark(self) -> SparkSession:
         if self._spark:
             return self._spark
 
-        if not hasattr(self, 'parent'):
+        if not hasattr(self, "parent"):
             return SparkSession.builder.config(conf=SPARK_CONF).getOrCreate()
-        spark = getattr(self.parent, 'spark')
+        spark = getattr(self.parent, "spark")
         if not spark:
-            conf = getattr(self.parent, 'spark_config', SPARK_CONF)
+            conf = getattr(self.parent, "spark_config", SPARK_CONF)
             spark = SparkSession.builder.config(conf=conf).getOrCreate()
 
         self._spark = spark
         return spark
```

### Comparing `sparksampling-0.2.1/sparksampling/sample/cluster_sampling_imp.py` & `sparksampling-0.2.2/sparksampling/sample/cluster_sampling_imp.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,57 +1,59 @@
 import math
+import random
 
 from sparksampling.sample.base_sampling import SparkBaseSamplingJob
-import random
 
 
 class ClusterSamplingImp(SparkBaseSamplingJob):
-    cls_args = ['fraction', 'seed', 'count', 'sampling_col', 'group_by', 'group_num']
+    cls_args = ["fraction", "seed", "count", "sampling_col", "group_by", "group_num"]
 
     def __init__(self, *args, **kwargs):
         super(ClusterSamplingImp, self).__init__(*args, **kwargs)
-        self.fraction = float(kwargs.pop('fraction', 0))
-        self.seed = kwargs.pop('seed', random.randint(1, 65535))
-        self.count = kwargs.pop('count', 0)
-        self.sampling_col = list(kwargs.pop('sampling_col', []))
-        self.group_by = str(kwargs.pop('group_by'))
-        self.group_num = int(kwargs.pop('group_num', 0))
+        self.fraction = float(kwargs.pop("fraction", 0))
+        self.seed = kwargs.pop("seed", random.randint(1, 65535))
+        self.count = kwargs.pop("count", 0)
+        self.sampling_col = list(kwargs.pop("sampling_col", []))
+        self.group_by = str(kwargs.pop("group_by"))
+        self.group_num = int(kwargs.pop("group_num", 0))
 
     def run(self, df):
         if self.sampling_col:
             df = df[self.sampling_col]
 
         # https://stackoverflow.com/questions/44367019/column-name-with-dot-spark
         # Prevent .(dot) breaking select
         group = df.select(f"`{self.group_by}`").distinct()
         group_sampled = self.get_group_sampled(group)
 
         # equal to df.join(group_sampled, df.group_by == group_sampled.group_by, 'semi'), this will keep column in order
         cond = [getattr(df, self.group_by) == getattr(group_sampled, self.group_by)]
-        df = df.join(
-            group_sampled,
-            cond,
-            how='semi'
-        )
+        df = df.join(group_sampled, cond, how="semi")
         if self.count:
             df = df.limit(self.count)
 
         return df
 
     def get_group_sampled(self, group):
         if self.fraction:
             self.log.info(f"Using fraction:{self.fraction} to sample group")
             group_df = group.sample(fraction=self.fraction, withReplacement=False, seed=self.seed)
             if self.group_num:
-                self.log.info(f"Fraction with group_num, limit group as group_num: {self.group_num}")
+                self.log.info(
+                    f"Fraction with group_num, limit group as group_num: {self.group_num}"
+                )
                 group_df = group_df.limit(self.group_num)
         else:
             # Cluster sampling expects to get the exact number of groups
-            self.log.info(f'No fraction specified, using rdd.takeSample to get the exact number of groups')
+            self.log.info(
+                f"No fraction specified, using rdd.takeSample to get the exact number of groups"
+            )
             subset = group.rdd.takeSample(False, self.group_num, seed=self.seed)
             try:
                 group_df = self.spark.sparkContext.parallelize(subset).toDF()
             except ValueError as e:
-                self.log.info(f'Exception when rdd -> df, {e}, will use group df without being sampled')
+                self.log.info(
+                    f"Exception when rdd -> df, {e}, will use group df without being sampled"
+                )
                 self.log.exception(e)
                 group_df = group
         return group_df
```

### Comparing `sparksampling-0.2.1/sparksampling/sample/random_sampling_imp.py` & `sparksampling-0.2.2/sparksampling/sample/random_sampling_imp.py`

 * *Files 16% similar despite different names*

```diff
@@ -1,26 +1,27 @@
-from sparksampling.sample.base_sampling import SparkBaseSamplingJob
 import random
 
+from sparksampling.sample.base_sampling import SparkBaseSamplingJob
+
 
 class RandomSamplingImp(SparkBaseSamplingJob):
-    cls_args = ['fraction', 'with_replacement', 'seed', 'count', 'sampling_col']
+    cls_args = ["fraction", "with_replacement", "seed", "count", "sampling_col"]
 
     def __init__(self, *args, **kwargs):
         super(RandomSamplingImp, self).__init__(*args, **kwargs)
-        self.fraction = float(kwargs.pop('fraction', 0))
-        self.with_replacement = kwargs.pop('with_replacement', False)
-        self.seed = kwargs.pop('seed', random.randint(1, 65535))
-        self.count = kwargs.pop('count', 0)
-        self.sampling_col = list(kwargs.pop('sampling_col', []))
+        self.fraction = float(kwargs.pop("fraction", 0))
+        self.with_replacement = kwargs.pop("with_replacement", False)
+        self.seed = kwargs.pop("seed", random.randint(1, 65535))
+        self.count = kwargs.pop("count", 0)
+        self.sampling_col = list(kwargs.pop("sampling_col", []))
 
     def run(self, df):
         if self.sampling_col:
             df = df[self.sampling_col]
 
         # Obtain 5% more samples to meet count requirements
         fraction = min(self.fraction or 1.05 * (self.count / df.count()), 1.0)
-        self.log.info(f'Start sampling as fraction: {fraction}')
+        self.log.info(f"Start sampling as fraction: {fraction}")
         df = df.sample(fraction=fraction, seed=self.seed, withReplacement=self.with_replacement)
         if self.count:
             df = df.limit(self.count)
         return df
```

### Comparing `sparksampling-0.2.1/sparksampling/sample/sampling_factory.py` & `sparksampling-0.2.2/sparksampling/sample/sampling_factory.py`

 * *Files 15% similar despite different names*

```diff
@@ -1,33 +1,34 @@
 from sparksampling.error import BadParamError
-
 from sparksampling.proto.sampling_service_pb2 import (
+    CLUSTER_SAMPLING_METHOD,
     RANDOM_SAMPLING_METHOD,
-    STRATIFIED_SAMPLING_METHOD,
     SIMPLE_SAMPLING_METHOD,
-    CLUSTER_SAMPLING_METHOD
+    STRATIFIED_SAMPLING_METHOD,
 )
 from sparksampling.sample.base_sampling import SparkBaseSamplingJob
+from sparksampling.sample.cluster_sampling_imp import ClusterSamplingImp
 from sparksampling.sample.random_sampling_imp import RandomSamplingImp
 from sparksampling.sample.simple_sampling_imp import SimpleSamplingImp
 from sparksampling.sample.stratified_sampling_imp import StratifiedSamplingImp
-from sparksampling.sample.cluster_sampling_imp import ClusterSamplingImp
 
 
 class SamplingFactory(object):
     method_map = {
         RANDOM_SAMPLING_METHOD: RandomSamplingImp,
         STRATIFIED_SAMPLING_METHOD: StratifiedSamplingImp,
         SIMPLE_SAMPLING_METHOD: SimpleSamplingImp,
         CLUSTER_SAMPLING_METHOD: ClusterSamplingImp,
     }
 
     @classmethod
     def get_sampling_imp(cls, sampling_method, sampling_conf) -> SparkBaseSamplingJob:
-        return cls._get_imp_class(sampling_method)(**cls._get_sampling_conf(sampling_method, sampling_conf))
+        return cls._get_imp_class(sampling_method)(
+            **cls._get_sampling_conf(sampling_method, sampling_conf)
+        )
 
     @classmethod
     def _get_imp_class(cls, sampling_method):
         imp_class = cls.method_map.get(sampling_method, None)
         if not imp_class:
             raise BadParamError(f"No matching sampling method: {sampling_method}")
         return imp_class
```

### Comparing `sparksampling-0.2.1/sparksampling/sample/stratified_sampling_imp.py` & `sparksampling-0.2.2/sparksampling/sample/stratified_sampling_imp.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,30 +1,41 @@
 import json
 import os
 import random
 from typing import Dict
+
+from pyspark.sql.functions import col, rand, row_number
 from pyspark.sql.window import Window
-from pyspark.sql.functions import col, row_number, rand
 
 from sparksampling.sample.base_sampling import SparkBaseSamplingJob
 
 
 class StratifiedSamplingImp(SparkBaseSamplingJob):
-    cls_args = ['fraction', 'with_replacement', 'stratified_key', 'seed', 'count', 'sampling_col', 'ensure_col']
+    cls_args = [
+        "fraction",
+        "with_replacement",
+        "stratified_key",
+        "seed",
+        "count",
+        "sampling_col",
+        "ensure_col",
+    ]
 
     def __init__(self, *args, **kwargs):
         super(StratifiedSamplingImp, self).__init__(*args, **kwargs)
-        self.fraction = self._init_fraction(kwargs.pop('fraction'))
-        self.stratified_key = kwargs.pop('stratified_key')
-        self.with_replacement = kwargs.pop('with_replacement', False)
-        self.seed = kwargs.pop('seed', random.randint(1, 65535))
-        self.count = kwargs.pop('count', 0)
-        self.sampling_col = list(kwargs.pop('sampling_col', []))
-        self.ensure_col = os.environ.get('FORCE_STRATIFILED_ENSURE_COL') in ['True', 'true'] or \
-                          kwargs.pop('ensure_col', False)
+        self.fraction = self._init_fraction(kwargs.pop("fraction"))
+        self.stratified_key = kwargs.pop("stratified_key")
+        self.with_replacement = kwargs.pop("with_replacement", False)
+        self.seed = kwargs.pop("seed", random.randint(1, 65535))
+        self.count = kwargs.pop("count", 0)
+        self.sampling_col = list(kwargs.pop("sampling_col", []))
+        self.ensure_col = os.environ.get("FORCE_STRATIFILED_ENSURE_COL") in [
+            "True",
+            "true",
+        ] or kwargs.pop("ensure_col", False)
 
     @staticmethod
     def _init_fraction(fraction_str):
         fraction = json.loads(fraction_str)
         if isinstance(fraction, int):
             fraction = float(fraction)
         if not isinstance(fraction, (Dict, float)):
@@ -33,15 +44,15 @@
 
     def run(self, df):
         fraction = self._convert_fraction_to_dict(df, self.stratified_key, self.fraction)
         if self.sampling_col:
             df = df[self.sampling_col]
         sampled_df = df.sampleBy(col=self.stratified_key, fractions=fraction, seed=self.seed)
         if self.ensure_col:
-            self.log.info('ensure every layer in result, ignore count')
+            self.log.info("ensure every layer in result, ignore count")
             sampled_df = self.sample_full_layer_df(sampled_df, df, self.stratified_key)
         if self.count:
             sampled_df = sampled_df.limit(self.count)
         return sampled_df
 
     @staticmethod
     def _convert_fraction_to_dict(df, stratified_key, fraction) -> Dict:
@@ -54,14 +65,19 @@
         y = df.select(f"`{stratified_key}`")
         convert_fraction = {label[0]: fraction for label in y.distinct().toLocalIterator()}
         return convert_fraction
 
     @staticmethod
     def sample_full_layer_df(sampled_df, origin_df, stratified_key):
         sampled_layer_key = sampled_df.select(f"`{stratified_key}`").distinct()
-        missing_layer_key = origin_df.select(f"`{stratified_key}`").distinct().exceptAll(sampled_layer_key)
+        missing_layer_key = (
+            origin_df.select(f"`{stratified_key}`").distinct().exceptAll(sampled_layer_key)
+        )
 
-        missing_df = origin_df.join(missing_layer_key, stratified_key, 'semi')
+        missing_df = origin_df.join(missing_layer_key, stratified_key, "semi")
         stratified_window = Window.partitionBy(f"`{stratified_key}`").orderBy(rand())
-        missing_layer = missing_df.withColumn("_", row_number().over(stratified_window)).filter(col("_") == 1).drop(
-            "_")
+        missing_layer = (
+            missing_df.withColumn("_", row_number().over(stratified_window))
+            .filter(col("_") == 1)
+            .drop("_")
+        )
         return sampled_df.unionByName(missing_layer, allowMissingColumns=True)
```

### Comparing `sparksampling-0.2.1/sparksampling/service.py` & `sparksampling-0.2.2/sparksampling/service.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,67 +1,76 @@
 from sparksampling.engine_factory import EngineFactory
 from sparksampling.mixin import LogMixin
 from sparksampling.proto import sampling_service_pb2_grpc
 from sparksampling.proto.sampling_service_pb2 import (
-    SamplingResponse,
-    SamplingRequest,
+    CancelRequest,
+    CancelResponse,
     RelationSamplingRequest,
     RelationSamplingResponse,
-    CancelRequest,
-    CancelResponse
+    SamplingRequest,
+    SamplingResponse,
 )
 from sparksampling.utilities import throw_exception
 
 
 class GRPCService(sampling_service_pb2_grpc.SparkSamplingServiceServicer, LogMixin):
-
     def __init__(self, parent):
         self.parent = parent
 
     @staticmethod
     def register_engine(parent):
         EngineFactory.register_all_engine()
 
     @staticmethod
     def get_worker_num():
         return EngineFactory.get_engine_total_worker()
 
     @staticmethod
     def add_to_server(parent, server):
-        """ Register the service to the GRPC Server
+        """Register the service to the GRPC Server
         :param parent: application instance
         :param server: server instance
         :return:
         """
-        GRPCService.logger.info('Add GRPCService Service to server')
+        GRPCService.logger.info("Add GRPCService Service to server")
         sampling_service_pb2_grpc.add_SparkSamplingServiceServicer_to_server(
-            GRPCService(parent), server)
+            GRPCService(parent), server
+        )
 
     @throw_exception
     def SamplingJob(self, request: SamplingRequest, context) -> SamplingResponse:
         data = EngineFactory.message_to_dict(request)
         parent_request = SamplingRequest(**data)
         engine = EngineFactory.get_engine(self.parent, SamplingRequest, **data)
         output_path, hook_msg = engine.submit()
-        return SamplingResponse(code=0, message='',
-                                data=SamplingResponse.ResponseData(parent_request=parent_request,
-                                                                   sampled_path=output_path,
-                                                                   hook_msg=hook_msg))
+        return SamplingResponse(
+            code=0,
+            message="",
+            data=SamplingResponse.ResponseData(
+                parent_request=parent_request, sampled_path=output_path, hook_msg=hook_msg
+            ),
+        )
 
     @throw_exception
-    def RelationSamplingJob(self, request: RelationSamplingRequest, context) -> RelationSamplingResponse:
+    def RelationSamplingJob(
+        self, request: RelationSamplingRequest, context
+    ) -> RelationSamplingResponse:
         data = EngineFactory.message_to_dict(request)
         parent_request = RelationSamplingRequest(**data)
         engine = EngineFactory.get_engine(self.parent, RelationSamplingRequest, **data)
         results = engine.submit()
 
-        return RelationSamplingResponse(code=0, message='',
-                                        data=RelationSamplingResponse.ResponseData(parent_request=parent_request,
-                                                                                   results=results))
+        return RelationSamplingResponse(
+            code=0,
+            message="",
+            data=RelationSamplingResponse.ResponseData(
+                parent_request=parent_request, results=results
+            ),
+        )
 
     def CancelJob(self, request: CancelRequest, context) -> CancelResponse:
         try:
             EngineFactory.cancel_job(self.parent, request.job_id)
         except Exception as e:
             self.logger.exception(e)
             return CancelResponse(code=5000, message=str(e))
-        return CancelResponse(code=0, message='ok')
+        return CancelResponse(code=0, message="ok")
```

### Comparing `sparksampling-0.2.1/sparksampling/utilities.py` & `sparksampling-0.2.2/sparksampling/utilities.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,136 +1,144 @@
 import logging
 import os
 import re
 import signal
 import time
-from functools import wraps, partial
+from functools import partial, wraps
 
 import requests
 from google.protobuf.json_format import MessageToDict
 from pyspark.sql import SparkSession
 
-from sparksampling.error import CustomErrorWithCode, SERVER_ERROR
+from sparksampling.error import SERVER_ERROR, CustomErrorWithCode
 
 logger = logging.getLogger("sparksampling")
 
 
 def hump2underline(hunp_str):
-    p = re.compile(r'([a-z]|\d)([A-Z])')
-    sub = re.sub(p, r'\1_\2', hunp_str).lower()
+    p = re.compile(r"([a-z]|\d)([A-Z])")
+    sub = re.sub(p, r"\1_\2", hunp_str).lower()
     return sub
 
 
 def hump2underline_dict(data):
     keys = list(data.keys())
     for key in keys:
         underline_key = hump2underline(key)
         if type(data[key]) is dict:
             data[underline_key] = hump2underline_dict(data[key])
         data[underline_key] = data.pop(key)
     return data
 
 
 def underline2hump(underline_str):
-    sub = re.sub(r'(_\w)', lambda x: x.group(1)[1].upper(), underline_str)
+    sub = re.sub(r"(_\w)", lambda x: x.group(1)[1].upper(), underline_str)
     return sub
 
 
 def throw_exception(func=None, *, request_type=None, response_type=None):
     if func is None:
         return partial(throw_exception, request_type=request_type, response_type=response_type)
 
     if not request_type:
-        request_type = func.__annotations__['request']
+        request_type = func.__annotations__["request"]
 
     if not response_type:
-        response_type = func.__annotations__['return']
+        response_type = func.__annotations__["return"]
 
     @wraps(func)
     def wrapper(self, request, context):
         data = MessageToDict(request, preserving_proto_field_name=True)
         parent_request = request_type(**data)
         start_time = time.time()
         try:
             return func(self, request, context)
         except CustomErrorWithCode as e:
             logger.exception(e)
-            return response_type(**e.error_response(),
-                                 data=response_type.ResponseData(parent_request=parent_request))
+            return response_type(
+                **e.error_response(), data=response_type.ResponseData(parent_request=parent_request)
+            )
         except Exception as e:
             logger.exception(e)
-            return response_type(code=SERVER_ERROR, message=str(e),
-                                 data=response_type.ResponseData(parent_request=parent_request))
+            return response_type(
+                code=SERVER_ERROR,
+                message=str(e),
+                data=response_type.ResponseData(parent_request=parent_request),
+            )
         finally:
             end_time = time.time()
-            cls_logger = getattr(self, 'logger', logger)
+            cls_logger = getattr(self, "logger", logger)
             cls_logger.debug(f"execute in {str(end_time - start_time).split('.')[0]} seconds")
 
     return wrapper
 
 
 def async_throw_exception(func=None, *, request_type=None, response_type=None):
     if func is None:
         return partial(throw_exception, request_type=request_type, response_type=response_type)
 
     if not request_type:
-        request_type = func.__annotations__['request']
+        request_type = func.__annotations__["request"]
 
     if not response_type:
-        response_type = func.__annotations__['return']
+        response_type = func.__annotations__["return"]
 
     @wraps(func)
     async def wrapper(self, request, context):
         data = MessageToDict(request, preserving_proto_field_name=True)
         parent_request = request_type(**data)
         start_time = time.time()
         try:
             return await func(self, request, context)
         except CustomErrorWithCode as e:
             logger.exception(e)
-            return response_type(**e.error_response(),
-                                 data=response_type.ResponseData(parent_request=parent_request))
+            return response_type(
+                **e.error_response(), data=response_type.ResponseData(parent_request=parent_request)
+            )
         except Exception as e:
             logger.exception(e)
-            return response_type(code=SERVER_ERROR, message=str(e),
-                                 data=response_type.ResponseData(parent_request=parent_request))
+            return response_type(
+                code=SERVER_ERROR,
+                message=str(e),
+                data=response_type.ResponseData(parent_request=parent_request),
+            )
         finally:
             end_time = time.time()
-            cls_logger = getattr(self, 'logger', logger)
+            cls_logger = getattr(self, "logger", logger)
             cls_logger.debug(f"execute in {str(end_time - start_time).split('.')[0]} seconds")
 
     return wrapper
 
 
 def check_spark_session(func):
     # Check the spark driver status and exit if it is not responding
     # Server will be redeployed under K8S deployment
     def _check_spark_ui(logger, spark: SparkSession):
         try:
-            if not spark.conf.get('spark.submit.deployMode') == 'client':
+            if not spark.conf.get("spark.submit.deployMode") == "client":
                 return True
         except Exception as e:
             logger.exception(e)
             logger.warning(f"can't access spark.conf")
             return False
 
-        ui_port = spark.conf.get('spark.ui.port')
+        ui_port = spark.conf.get("spark.ui.port")
         url = f"http://localhost:{ui_port}"
         logger.debug(f"Check Spark is alive: {url}")
         try:
             response = requests.get(url)
         except Exception as e:
             logger.exception(e)
             logger.warning(f"Can't access Spark ui: {url}")
             return False
         return response.status_code == 200
 
     def exit_if_spark_dead(self):
         if not _check_spark_ui(self.logger, self.spark):
-            cls_logger = getattr(self, 'logger') or logger
+            cls_logger = getattr(self, "logger") or logger
             cls_logger.critical("Spark is dead, exiting...")
             os.kill(os.getpid(), signal.SIGINT)
 
     @wraps(func)
     def wrapper(self, *args, **kwargs):
         try:
             r = func(self, *args, **kwargs)
```


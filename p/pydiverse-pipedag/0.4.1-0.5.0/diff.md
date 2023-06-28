# Comparing `tmp/pydiverse_pipedag-0.4.1.tar.gz` & `tmp/pydiverse_pipedag-0.5.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pydiverse_pipedag-0.4.1.tar", max compression
+gzip compressed data, was "pydiverse_pipedag-0.5.0.tar", max compression
```

## Comparing `pydiverse_pipedag-0.4.1.tar` & `pydiverse_pipedag-0.5.0.tar`

### file list

```diff
@@ -1,57 +1,61 @@
--rw-r--r--   0        0        0     1517 2023-06-17 05:57:06.114336 pydiverse_pipedag-0.4.1/LICENSE
--rw-r--r--   0        0        0     7229 2023-06-17 05:57:06.114336 pydiverse_pipedag-0.4.1/docs/package/README.md
--rw-r--r--   0        0        0     3037 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/pyproject.toml
--rw-r--r--   0        0        0       13 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/.gitignore
--rw-r--r--   0        0        0      355 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/__init__.py
--rw-r--r--   0        0        0      749 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/_typing.py
--rw-r--r--   0        0        0       88 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/backend/__init__.py
--rw-r--r--   0        0        0     5334 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/backend/blob.py
--rw-r--r--   0        0        0      357 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/backend/lock/__init__.py
--rw-r--r--   0        0        0     6097 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/backend/lock/base.py
--rw-r--r--   0        0        0    11773 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/backend/lock/database.py
--rw-r--r--   0        0        0     2541 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/backend/lock/filelock.py
--rw-r--r--   0        0        0      768 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/backend/lock/nolock.py
--rw-r--r--   0        0        0     3671 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/backend/lock/zookeeper.py
--rw-r--r--   0        0        0        0 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/backend/lock.py
--rw-r--r--   0        0        0      177 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/backend/table/__init__.py
--rw-r--r--   0        0        0    20296 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/backend/table/base.py
--rw-r--r--   0        0        0     7267 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/backend/table/dict.py
--rw-r--r--   0        0        0    83022 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/backend/table/sql.py
--rw-r--r--   0        0        0       45 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/backend/table/util/__init__.py
--rw-r--r--   0        0        0     1274 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/backend/table/util/engine_dispatch.py
--rw-r--r--   0        0        0      456 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/backend/table/util/pandas.py
--rw-r--r--   0        0        0    40457 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/backend/table/util/sql_ddl.py
--rw-r--r--   0        0        0    12122 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/backend/table_cache.py
--rw-r--r--   0        0        0      342 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/context/__init__.py
--rw-r--r--   0        0        0     8231 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/context/context.py
--rw-r--r--   0        0        0    25913 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/context/run_context.py
--rw-r--r--   0        0        0      219 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/core/__init__.py
--rw-r--r--   0        0        0    13669 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/core/config.py
--rw-r--r--   0        0        0     9325 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/core/flow.py
--rw-r--r--   0        0        0     2551 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/core/result.py
--rw-r--r--   0        0        0     5626 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/core/stage.py
--rw-r--r--   0        0        0     6568 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/core/task.py
--rw-r--r--   0        0        0      332 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/engine/__init__.py
--rw-r--r--   0        0        0      648 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/engine/base.py
--rw-r--r--   0        0        0     2818 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/engine/dask.py
--rw-r--r--   0        0        0     6516 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/engine/prefect.py
--rw-r--r--   0        0        0     1380 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/engine/sequential.py
--rw-r--r--   0        0        0     1079 2023-06-17 05:57:06.118336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/errors/__init__.py
--rw-r--r--   0        0        0      124 2023-06-17 05:57:06.122336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/materialize/__init__.py
--rw-r--r--   0        0        0     8908 2023-06-17 05:57:06.122336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/materialize/cache.py
--rw-r--r--   0        0        0     5422 2023-06-17 05:57:06.122336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/materialize/container.py
--rw-r--r--   0        0        0     7855 2023-06-17 05:57:06.122336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/materialize/core.py
--rw-r--r--   0        0        0     2039 2023-06-17 05:57:06.122336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/materialize/metadata.py
--rw-r--r--   0        0        0    17644 2023-06-17 05:57:06.122336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/materialize/store.py
--rw-r--r--   0        0        0       37 2023-06-17 05:57:06.122336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/materialize/util/__init__.py
--rw-r--r--   0        0        0     1104 2023-06-17 05:57:06.122336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/materialize/util/cache.py
--rw-r--r--   0        0        0     4222 2023-06-17 05:57:06.122336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/materialize/util/json.py
--rw-r--r--   0        0        0      177 2023-06-17 05:57:06.122336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/util/__init__.py
--rw-r--r--   0        0        0     2061 2023-06-17 05:57:06.122336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/util/deep_map.py
--rw-r--r--   0        0        0     1435 2023-06-17 05:57:06.122336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/util/deep_merge.py
--rw-r--r--   0        0        0      880 2023-06-17 05:57:06.122336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/util/disposable.py
--rw-r--r--   0        0        0     2927 2023-06-17 05:57:06.122336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/util/import_.py
--rw-r--r--   0        0        0     7992 2023-06-17 05:57:06.122336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/util/ipc.py
--rw-r--r--   0        0        0     1553 2023-06-17 05:57:06.122336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/util/naming.py
--rw-r--r--   0        0        0     2811 2023-06-17 05:57:06.122336 pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/util/structlog.py
--rw-r--r--   0        0        0     8788 1970-01-01 00:00:00.000000 pydiverse_pipedag-0.4.1/PKG-INFO
+-rw-r--r--   0        0        0     1517 2023-06-28 08:54:22.346858 pydiverse_pipedag-0.5.0/LICENSE
+-rw-r--r--   0        0        0     7229 2023-06-28 08:54:22.346858 pydiverse_pipedag-0.5.0/docs/package/README.md
+-rw-r--r--   0        0        0     3212 2023-06-28 08:54:22.350858 pydiverse_pipedag-0.5.0/pyproject.toml
+-rw-r--r--   0        0        0       13 2023-06-28 08:54:22.350858 pydiverse_pipedag-0.5.0/src/pydiverse/.gitignore
+-rw-r--r--   0        0        0      355 2023-06-28 08:54:22.350858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/__init__.py
+-rw-r--r--   0        0        0      749 2023-06-28 08:54:22.350858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/_typing.py
+-rw-r--r--   0        0        0       88 2023-06-28 08:54:22.350858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/backend/__init__.py
+-rw-r--r--   0        0        0     5334 2023-06-28 08:54:22.350858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/backend/blob.py
+-rw-r--r--   0        0        0      357 2023-06-28 08:54:22.350858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/backend/lock/__init__.py
+-rw-r--r--   0        0        0     6097 2023-06-28 08:54:22.350858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/backend/lock/base.py
+-rw-r--r--   0        0        0    11773 2023-06-28 08:54:22.350858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/backend/lock/database.py
+-rw-r--r--   0        0        0     2541 2023-06-28 08:54:22.350858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/backend/lock/filelock.py
+-rw-r--r--   0        0        0      768 2023-06-28 08:54:22.350858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/backend/lock/nolock.py
+-rw-r--r--   0        0        0     3671 2023-06-28 08:54:22.350858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/backend/lock/zookeeper.py
+-rw-r--r--   0        0        0        0 2023-06-28 08:54:22.350858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/backend/lock.py
+-rw-r--r--   0        0        0      177 2023-06-28 08:54:22.350858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/backend/table/__init__.py
+-rw-r--r--   0        0        0    21262 2023-06-28 08:54:22.350858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/backend/table/base.py
+-rw-r--r--   0        0        0     7661 2023-06-28 08:54:22.350858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/backend/table/dict.py
+-rw-r--r--   0        0        0    63798 2023-06-28 08:54:22.350858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/backend/table/sql.py
+-rw-r--r--   0        0        0    24570 2023-06-28 08:54:22.350858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/backend/table/sql_hooks.py
+-rw-r--r--   0        0        0      171 2023-06-28 08:54:22.350858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/backend/table/util/__init__.py
+-rw-r--r--   0        0        0     8461 2023-06-28 08:54:22.350858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/backend/table/util/dtype.py
+-rw-r--r--   0        0        0     2257 2023-06-28 08:54:22.350858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/backend/table/util/engine_dispatch.py
+-rw-r--r--   0        0        0    43657 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/backend/table/util/sql_ddl.py
+-rw-r--r--   0        0        0    12122 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/backend/table_cache.py
+-rw-r--r--   0        0        0      397 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/context/__init__.py
+-rw-r--r--   0        0        0     8094 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/context/context.py
+-rw-r--r--   0        0        0    26404 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/context/run_context.py
+-rw-r--r--   0        0        0      243 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/core/__init__.py
+-rw-r--r--   0        0        0    13669 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/core/config.py
+-rw-r--r--   0        0        0    16460 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/core/flow.py
+-rw-r--r--   0        0        0     3501 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/core/result.py
+-rw-r--r--   0        0        0     5626 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/core/stage.py
+-rw-r--r--   0        0        0     7731 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/core/task.py
+-rw-r--r--   0        0        0      332 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/engine/__init__.py
+-rw-r--r--   0        0        0      654 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/engine/base.py
+-rw-r--r--   0        0        0     2789 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/engine/dask.py
+-rw-r--r--   0        0        0     6536 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/engine/prefect.py
+-rw-r--r--   0        0        0     1447 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/engine/sequential.py
+-rw-r--r--   0        0        0     1079 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/errors/__init__.py
+-rw-r--r--   0        0        0        0 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/management/__init__.py
+-rw-r--r--   0        0        0      620 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/management/cli.py
+-rw-r--r--   0        0        0        0 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/management/commands/__init__.py
+-rw-r--r--   0        0        0     1703 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/management/commands/clear_metadata.py
+-rw-r--r--   0        0        0      124 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/materialize/__init__.py
+-rw-r--r--   0        0        0     8938 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/materialize/cache.py
+-rw-r--r--   0        0        0     5422 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/materialize/container.py
+-rw-r--r--   0        0        0     9875 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/materialize/core.py
+-rw-r--r--   0        0        0     2062 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/materialize/metadata.py
+-rw-r--r--   0        0        0    17445 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/materialize/store.py
+-rw-r--r--   0        0        0      177 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/util/__init__.py
+-rw-r--r--   0        0        0     2061 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/util/deep_map.py
+-rw-r--r--   0        0        0     1435 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/util/deep_merge.py
+-rw-r--r--   0        0        0      880 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/util/disposable.py
+-rw-r--r--   0        0        0     1093 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/util/hashing.py
+-rw-r--r--   0        0        0     2927 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/util/import_.py
+-rw-r--r--   0        0        0     7992 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/util/ipc.py
+-rw-r--r--   0        0        0     4349 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/util/json.py
+-rw-r--r--   0        0        0     1553 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/util/naming.py
+-rw-r--r--   0        0        0     2811 2023-06-28 08:54:22.354858 pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/util/structlog.py
+-rw-r--r--   0        0        0     8857 1970-01-01 00:00:00.000000 pydiverse_pipedag-0.5.0/PKG-INFO
```

### Comparing `pydiverse_pipedag-0.4.1/LICENSE` & `pydiverse_pipedag-0.5.0/LICENSE`

 * *Files identical despite different names*

### Comparing `pydiverse_pipedag-0.4.1/docs/package/README.md` & `pydiverse_pipedag-0.5.0/docs/package/README.md`

 * *Files identical despite different names*

### Comparing `pydiverse_pipedag-0.4.1/pyproject.toml` & `pydiverse_pipedag-0.5.0/pyproject.toml`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "pydiverse-pipedag"
-version = "0.4.1"
+version = "0.5.0"
 description = "A pipeline orchestration library executing tasks within one python session. It takes care of SQL table (de)materialization, caching and cache invalidation. Blob storage is supported as well for example for storing model files."
 authors = [
   "QuantCo, Inc.",
   "Nicolas Camenisch <garnele007@gmail.com>",
   "Martin Trautmann <windiana@users.sf.net>",
 ]
 license = "BSD-3-Clause"
@@ -31,14 +31,16 @@
 pynng = ">=0.7.1"
 msgpack = ">=1.0.4"
 packaging = ">=21.3"
 python-box = ">=6.1.0"
 PyYAML = ">=6.0"
 pyarrow = ">=11.0.0"
 cryptography = ">=41.0.1"
+pydot = ">=1.4.2"
+click = "^8.1.3"
 
 filelock = { version = ">=3.7.1", optional = true }
 kazoo = { version = ">=2.8.0", optional = true }
 dask = { version = ">=2022.1.0", optional = true }
 
 
 [tool.poetry.extras]
@@ -55,22 +57,23 @@
 isort = "^5.10.1"
 ruff = "^0.0.270"
 pre-commit = ">=2.20.0"
 
 kazoo = ">=2.8.0"
 dask = ">=2022.1.0"
 psycopg2 = ">=2.9.3"
-pydot = ">=1.4.2"
+duckdb = "^0.8.1"
+duckdb-engine = "^0.7.3"
 
 [tool.poetry.group.tests]
 optional = true
 
 [tool.poetry.group.tests.dependencies]
 # Table Hooks
-pydiverse-transform = "^0.1.0"
+pydiverse-transform = "^0.1.3"
 ibis = ">=3.2.0"
 ibis-framework = { version = ">=5.1.0", extras = ["mssql", "postgres"] }
 polars = ">=0.16.18"
 tidypolars = { version = "^0.2.19", python = "<3.11" }
 connectorx = [
     { version = ">=0.3.1", python = "<3.11" },
     { version = "0.3.2a5", python = "==3.11" }  # Latest full release is broken - unpin when 0.3.2 released
@@ -89,14 +92,17 @@
 optional = true
 
 [tool.poetry.group.docs.dependencies]
 Sphinx = "^5.1.1"
 sphinx-rtd-theme = "^1.0.0"
 sphinxcontrib-apidoc = "^0.3.0"
 
+[tool.poetry.plugins."console_scripts"]
+pipedag-manage = "pydiverse.pipedag.management.cli:cli"
+
 [tool.black]
 exclude = '''
 /(
     \.eggs
   | \.git
   | \.venv
   | build
@@ -113,22 +119,23 @@
     "I001",
     "B",
     "A",
 ]
 ignore = [
     "B028",
 ]
-extend-exclude = ["tests/*", "docs/*"]
+extend-exclude = ["docs/*"]
 ignore-init-module-imports = true
 fix = true
 target-version = "py38"
 
 [tool.ruff.per-file-ignores]
 "__init__.py" = ["F401", "F403"]
 "src/pydiverse/pipedag/backend/table/util/sql_ddl.py" = ["F811"]
+"tests/*" = ["F403", "F405"]
 
 [tool.ruff.isort]
 known-first-party = ["pydiverse"]
 
 [build-system]
 requires = ["poetry-core>=1.0.0"]
 build-backend = "poetry.core.masonry.api"
```

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/_typing.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/_typing.py`

 * *Files identical despite different names*

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/backend/blob.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/backend/blob.py`

 * *Files identical despite different names*

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/backend/lock/base.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/backend/lock/base.py`

 * *Files identical despite different names*

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/backend/lock/database.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/backend/lock/database.py`

 * *Files identical despite different names*

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/backend/lock/filelock.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/backend/lock/filelock.py`

 * *Files identical despite different names*

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/backend/lock/nolock.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/backend/lock/nolock.py`

 * *Files identical despite different names*

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/backend/lock/zookeeper.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/backend/lock/zookeeper.py`

 * *Files identical despite different names*

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/backend/table/base.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/backend/table/base.py`

 * *Files 3% similar despite different names*

```diff
@@ -3,24 +3,24 @@
 from abc import ABC, ABCMeta, abstractmethod
 from typing import TYPE_CHECKING, Any, Generic
 
 import structlog
 from typing_extensions import Self
 
 from pydiverse.pipedag._typing import StoreT, T
-from pydiverse.pipedag.context import RunContext
+from pydiverse.pipedag.context import RunContext, TaskContext
 from pydiverse.pipedag.materialize.cache import CacheManager
 from pydiverse.pipedag.materialize.container import RawSql, Table
 from pydiverse.pipedag.materialize.metadata import (
     LazyTableMetadata,
     RawSqlMetadata,
     TaskMetadata,
 )
-from pydiverse.pipedag.materialize.util import compute_cache_key
 from pydiverse.pipedag.util import Disposable, requires
+from pydiverse.pipedag.util.hashing import stable_hash
 from pydiverse.pipedag.util.naming import NameDisambiguator
 
 if TYPE_CHECKING:
     from pydiverse.pipedag import Stage
     from pydiverse.pipedag.materialize.core import MaterializingTask, TaskInfo
 
 
@@ -92,16 +92,21 @@
             return self._M_TABLE_CACHE[type_]
         for hook in self._REGISTERED_TABLES:
             if hook.can_materialize(type_):
                 self._M_TABLE_CACHE[type_] = hook
                 return hook
         raise TypeError(f"Can't materialize Table with underlying type {type_}")
 
-    def get_r_table_hook(self: Self, type_: type[T]) -> TableHook[Self]:
+    def get_r_table_hook(self: Self, type_: type[T] | tuple | dict) -> TableHook[Self]:
         """Get a table hook that can retrieve the specified type"""
+        if isinstance(type_, tuple):
+            type_ = type_[0]
+        elif isinstance(type_, dict):
+            type_ = type_["type"]
+
         if type_ in self._R_TABLE_CACHE:
             return self._R_TABLE_CACHE[type_]
         for hook in self._REGISTERED_TABLES:
             if hook.can_retrieve(type_):
                 self._R_TABLE_CACHE[type_] = hook
                 return hook
         raise TypeError(f"Can't retrieve Table as type {type_}")
@@ -263,24 +268,25 @@
 
         Used when `lazy = True` is set for a materializing task.
         """
         _ = task
         try:
             hook = self.get_m_table_hook(type(table.obj))
             query_str = hook.lazy_query_str(self, table.obj)
-            query_hash = compute_cache_key("LAZY-TABLE", query_str)
+            query_hash = stable_hash("LAZY-TABLE", query_str)
         except TypeError:
             # This table type doesn't provide a query string
             # -> Fallback to default implementation
             return self.store_table(table, task, task_info)
 
         table_cache_info = CacheManager.lazy_table_cache_lookup(
             self, task_info.task_cache_info, table, query_hash
         )
         if not table_cache_info.is_cache_valid():
+            TaskContext.get().is_cache_valid = False
             self.store_table(table, task, task_info)
 
         # At this point we MUST also update the cache info, so that any downstream
         # tasks get invalidated if the sql query string changed.
         table.cache_key = CacheManager.lazy_table_cache_key(
             task_info.task_cache_info.get_task_cache_key(), query_hash
         )
@@ -292,20 +298,32 @@
 
         The same as `store_table()`, with the difference being that the store first
         checks if the same query with the same input (based on `raw_sql.cache_key`)
         has already been executed before. If yes, instead of evaluating
         the query, it just copies the previous result to the commit stage.
         """
         _ = task
-        query_hash = compute_cache_key("RAW-SQL", raw_sql.sql)
+
+        # hacky way to canonicalize query (despite __tmp/__even/__odd suffixes
+        # and alias resolution)
+        import re
+
+        query_str = raw_sql.sql
+        query_str = re.sub(r'["\[\]]', "", query_str)
+        query_str = re.sub(
+            r'(__tmp|__even|__odd)(?=[ \t\n.;"]|$)', "", query_str.lower()
+        )
+
+        query_hash = stable_hash("RAW-SQL", query_str)
 
         table_cache_info = CacheManager.raw_sql_cache_lookup(
             self, task_info.task_cache_info, raw_sql, query_hash
         )
         if not table_cache_info.is_cache_valid():
+            TaskContext.get().is_cache_valid = False
             RunContext.get().set_stage_has_changed(task.stage)
             prev_tables = self.list_tables(raw_sql.stage, include_everything=True)
             self.execute_raw_sql(raw_sql)
             post_tables = self.list_tables(raw_sql.stage, include_everything=True)
             table_cache_info.store_raw_sql_metadata(self, prev_tables, post_tables)
 
         # At this point we MUST also update the cache info, so that any downstream
@@ -373,14 +391,22 @@
         self, task: MaterializingTask, input_hash: str, cache_fn_hash: str
     ) -> TaskMetadata:
         """Retrieve a task's metadata from the store
 
         :raises CacheError: if no metadata for this task can be found.
         """
 
+    @abstractmethod
+    def retrieve_all_task_metadata(self, task: MaterializingTask) -> list[TaskMetadata]:
+        """Retrieves all metadata objects associated with a task from the store
+
+        As long as a metadata entry has the same task and stage name, as well
+        as the same position hash as the `task` object, it should get returned.
+        """
+
     # Lazy Table Metadata
 
     @abstractmethod
     def store_lazy_table_metadata(self, metadata: LazyTableMetadata):
         """Stores the metadata of a lazy table
 
         The metadata must always be stored in such a way that it is
@@ -504,15 +530,15 @@
     @classmethod
     @abstractmethod
     def retrieve(
         cls,
         store: StoreT,
         table: Table,
         stage_name: str,
-        as_type: type[T],
+        as_type: type[T] | tuple | dict[str, Any],
         namer: NameDisambiguator | None = None,
     ) -> T:
         """Retrieve a table from the store
 
         :param store: The store in which the table is stored
         :param table: The table which should get retrieved
         :param stage_name: The name of the stage from which te table should
```

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/backend/table/dict.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/backend/table/dict.py`

 * *Files 12% similar despite different names*

```diff
@@ -93,14 +93,24 @@
             return self.metadata[task.stage][cache_key]
         except KeyError:
             raise CacheError(
                 "There is no metadata for task "
                 f"'{task.name}' with cache key '{task.input_hash}', yet"
             ) from None
 
+    def retrieve_all_task_metadata(self, task: MaterializingTask) -> list[TaskMetadata]:
+        task_metadata = []
+        for m in (
+            *self.metadata[task.stage].values(),
+            *self.t_metadata[task.stage].values(),
+        ):
+            if m.name == task.name and m.position_hash == task.position_hash:
+                task_metadata.append(m)
+        return task_metadata
+
     def store_lazy_table_metadata(self, metadata: LazyTableMetadata):
         cache_key = metadata.query_hash + metadata.task_hash
         self.t_lazy_table_metadata[metadata.stage][cache_key] = metadata
 
     def retrieve_lazy_table_metadata(
         self, query_hash: str, task_hash: str, stage: Stage
     ) -> LazyTableMetadata:
```

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/backend/table/sql.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/backend/table/sql.py`

 * *Files 18% similar despite different names*

```diff
@@ -1,39 +1,34 @@
 from __future__ import annotations
 
 import itertools
 import json
 import re
 import textwrap
 import time
-import warnings
 from collections.abc import Iterable
 from contextlib import contextmanager
 from typing import Any
 
-import pandas as pd
 import sqlalchemy as sa
 import sqlalchemy.exc
 import sqlalchemy.sql.elements
-from sqlalchemy.dialects.mssql import DATETIME2
 
 from pydiverse.pipedag import Stage, Table
-from pydiverse.pipedag._typing import T
-from pydiverse.pipedag.backend.table.base import BaseTableStore, TableHook
+from pydiverse.pipedag.backend.table.base import BaseTableStore
 from pydiverse.pipedag.backend.table.util import engine_dispatch
 from pydiverse.pipedag.backend.table.util.sql_ddl import (
     AddIndex,
     AddPrimaryKey,
     ChangeColumnNullable,
     ChangeColumnTypes,
     CopyTable,
     CreateAlias,
     CreateDatabase,
     CreateSchema,
-    CreateTableAsSelect,
     CreateViewAsSelect,
     DropAlias,
     DropFunction,
     DropProcedure,
     DropSchema,
     DropTable,
     DropView,
@@ -44,22 +39,21 @@
     split_ddl_statement,
 )
 from pydiverse.pipedag.context import RunContext
 from pydiverse.pipedag.context.context import ConfigContext, StageCommitTechnique
 from pydiverse.pipedag.context.run_context import DeferredTableStoreOp
 from pydiverse.pipedag.errors import CacheError
 from pydiverse.pipedag.materialize.container import RawSql
-from pydiverse.pipedag.materialize.core import MaterializingTask, TaskInfo
+from pydiverse.pipedag.materialize.core import MaterializingTask
 from pydiverse.pipedag.materialize.metadata import (
     LazyTableMetadata,
     RawSqlMetadata,
     TaskMetadata,
 )
-from pydiverse.pipedag.materialize.util import compute_cache_key
-from pydiverse.pipedag.util.naming import NameDisambiguator
+from pydiverse.pipedag.util.hashing import stable_hash
 
 
 class SQLTableStore(BaseTableStore):
     """Table store that materializes tables to a SQL database
 
     Uses schema swapping for transactions:
     Creates a schema for each stage and a temporary schema for each
@@ -75,23 +69,25 @@
         config = config.copy()
         engine_url = config.pop("url")
         return cls(engine_url, **config)
 
     def __init__(
         self,
         engine_url: str,
+        *,
         create_database_if_not_exists: bool = False,
         schema_prefix: str = "",
         schema_suffix: str = "",
         avoid_drop_create_schema: bool = False,
         disable_pytsql: bool = False,
         pytsql_isolate_top_level_statements: bool = True,
         print_materialize: bool = False,
         print_sql: bool = False,
         no_db_locking: bool = True,
+        unlogged_tables: bool = False,
     ):
         """
         Construct table store.
 
         :param engine_url:
             URL for SQLAlchemy engine
         :param create_database_if_not_exists:
@@ -108,207 +104,236 @@
             forward pytsql executes() parameter
         :param print_materialize:
             whether to print select statements before materialization
         :param print_sql:
             whether to print final SQL statements (except for metadata)
         :param no_db_locking:
             speed up database by telling it we will not rely on it's locking mechanisms
+        :param unlogged_tables:
+            whether to use UNLOGGED tables or not (dialect postgresql only)
         """
         super().__init__()
 
         self.create_database_if_not_exists = create_database_if_not_exists
         self.schema_prefix = schema_prefix
         self.schema_suffix = schema_suffix
         self.disable_pytsql = disable_pytsql
         self.avoid_drop_create_schema = avoid_drop_create_schema
         self.pytsql_isolate_top_level_statements = pytsql_isolate_top_level_statements
         self.print_materialize = print_materialize
         self.print_sql = print_sql
         self.no_db_locking = no_db_locking
+        self.unlogged_tables = unlogged_tables
         self.metadata_schema = self.get_schema(self.METADATA_SCHEMA)
 
-        self._init_database(engine_url, create_database_if_not_exists)
         self.engine_url = sa.engine.make_url(engine_url)
-        self.engine = self._connect(engine_url, self.schema_prefix, self.schema_suffix)
+        self.engine = self._create_engine()
         self.engines_other = dict()  # i.e. for IBIS connection
 
+        self._init_database()
+
         # Set up metadata tables and schema
         from sqlalchemy import CLOB, BigInteger, Boolean, Column, DateTime, String
 
         if self.engine.dialect.name == "ibm_db_sa":
             clob_type = CLOB  # VARCHAR(MAX) does not exist
         else:
             clob_type = String  # VARCHAR(MAX)s
 
         self.sql_metadata = sa.MetaData()
 
         # Stage Table is unique for stage
         # (we currently cannot version changes of this metadata table when using
         # stage_commit_tequnique=read_views)
+
+        def autoincrement_pk(name: str, seq_name: str):
+            if self.engine.dialect.name == "duckdb":
+                sequence = sqlalchemy.Sequence(
+                    f"{seq_name}_{name}_seq", schema=self.metadata_schema.get()
+                )
+                return Column(
+                    name,
+                    BigInteger,
+                    sequence,
+                    server_default=sequence.next_value(),
+                    primary_key=True,
+                )
+
+            return Column(name, BigInteger, primary_key=True, autoincrement=True)
+
         self.stage_table = sa.Table(
             "stages",
             self.sql_metadata,
-            Column("id", BigInteger, primary_key=True, autoincrement=True),
+            autoincrement_pk("id", "stages"),
             Column("stage", String(64)),
             Column("cur_transaction_name", String(256)),
             schema=self.metadata_schema.get(),
         )
 
         # Store version number for metadata table schema evolution.
         # We disable caching in case of version mismatch.
         self.disable_caching = False
-        self.metadata_version = "0.2.0"  # Increase version if metadata table changes
+        self.metadata_version = "0.3.0"  # Increase version if metadata table changes
         self.version_table = sa.Table(
             "metadata_version",
             self.sql_metadata,
             Column("version", String(32)),
             schema=self.metadata_schema.get(),
         )
 
         # Task Table is unique for stage * in_transaction_schema
         self.tasks_table = sa.Table(
             "tasks",
             self.sql_metadata,
-            Column("id", BigInteger, primary_key=True, autoincrement=True),
+            autoincrement_pk("id", "tasks"),
             Column("name", String(128)),
             Column("stage", String(64)),
             Column("version", String(64)),
             Column("timestamp", DateTime),
-            Column("run_id", String(32)),
-            Column("input_hash", String(32)),
-            Column("cache_fn_hash", String(32)),
+            Column("run_id", String(20)),
+            Column("position_hash", String(20)),
+            Column("input_hash", String(20)),
+            Column("cache_fn_hash", String(20)),
             Column("output_json", clob_type),
             Column("in_transaction_schema", Boolean),
             schema=self.metadata_schema.get(),
         )
 
         # Lazy Cache Table is unique for stage * in_transaction_schema
         self.lazy_cache_table = sa.Table(
             "lazy_tables",
             self.sql_metadata,
-            Column("id", BigInteger, primary_key=True, autoincrement=True),
+            autoincrement_pk("id", "lazy_tables"),
             Column("name", String(128)),
             Column("stage", String(64)),
-            Column("query_hash", String(32)),
-            Column("task_hash", String(32)),
+            Column("query_hash", String(20)),
+            Column("task_hash", String(20)),
             Column("in_transaction_schema", Boolean),
             schema=self.metadata_schema.get(),
         )
 
         # Sql Cache Table is unique for stage * in_transaction_schema
         self.raw_sql_cache_table = sa.Table(
             "raw_sql_tables",
             self.sql_metadata,
-            Column("id", BigInteger, primary_key=True, autoincrement=True),
+            autoincrement_pk("id", "raw_sql_tables"),
             Column("prev_tables", String(256)),
             Column("tables", String(256)),
             Column("stage", String(64)),
-            Column("query_hash", String(32)),
-            Column("task_hash", String(32)),
+            Column("query_hash", String(20)),
+            Column("task_hash", String(20)),
             Column("in_transaction_schema", Boolean),
             schema=self.metadata_schema.get(),
         )
 
         self.logger.info(
             "Initialized SQL Table Store",
             engine_url=self.engine_url.render_as_string(hide_password=True),
             schema_prefix=self.schema_prefix,
             schema_suffix=self.schema_suffix,
         )
 
-    @staticmethod
-    def _init_database(engine_url: str, create_database_if_not_exists: bool):
-        if not create_database_if_not_exists:
+    @engine_dispatch
+    def _init_database(self):
+        if not self.create_database_if_not_exists:
             return
 
-        engine = sa.create_engine(engine_url)
-        if engine.dialect.name in ["mssql", "ibm_db_sa"]:
-            engine.dispose()
-            return
+        raise NotImplementedError(
+            "create_database_if_not_exists is only implemented for this engine"
+        )
 
-        # Attention: This is a really hacky way to create a generic engine for
-        #            creating a database before one can open a connection to
-        #            self.engine_url which references a database and will fail
-        #            if the database does not exist
-        url = sa.engine.make_url(engine_url)
+    @_init_database.dialect("postgresql")
+    def _init_database_postgresql(self):
+        if not self.create_database_if_not_exists:
+            return
 
-        if engine.dialect.name == "postgresql":
-            try:
-                with engine.connect() as conn:
-                    # try whether connection with database in connect string works
-                    conn.execute(sa.text("SELECT 1"))
-            except sa.exc.DBAPIError:
-                postgres_db_url = url.set(database="postgres")
-                tmp_engine = sa.create_engine(postgres_db_url)
-                try:
-                    with tmp_engine.connect() as conn:
-                        conn.execute(sa.text("COMMIT"))
-                        conn.execute(CreateDatabase(url.database))
-                except sa.exc.DBAPIError:
-                    # This happens if multiple instances try to create the database
-                    # at the same time.
-                    with engine.connect() as conn:
-                        # Verify database actually exists
-                        conn.execute(sa.text("SELECT 1"))
-        else:
-            raise NotImplementedError(
-                "create_database_if_not_exists is only implemented for postgres, yet"
-            )
-        engine.dispose()
+        try:
+            # Check if database exists
+            with self.engine.connect() as conn:
+                conn.execute(sa.text("SELECT 1"))
+            return
+        except sa.exc.DBAPIError:
+            # Database doesn't exist
+            pass
+
+        # Create new database using temporary engine object
+        postgres_db_url = self.engine_url.set(database="postgres")
+        tmp_engine = sa.create_engine(postgres_db_url)
 
-    @staticmethod
-    def _connect(engine_url, schema_prefix, schema_suffix):
-        engine = sa.create_engine(engine_url)
+        try:
+            with tmp_engine.connect() as conn:
+                conn.execute(sa.text("COMMIT"))
+                conn.execute(CreateDatabase(self.engine_url.database))
+        except sa.exc.DBAPIError:
+            # This happens if multiple instances try to create the database
+            # at the same time.
+            with self.engine.connect() as conn:
+                # Verify database actually exists
+                conn.execute(sa.text("SELECT 1"))
+
+    @_init_database.dialect("duckdb")
+    def _init_database_duckdb(self):
+        # Duckdb already creates the database file automatically
+        pass
 
-        # if engine.dialect.name == "ibm_db_sa":
-        #     engine.dispose()
-        #     # switch to READ STABILITY isolation level to avoid unnecessary deadlock
-        #     # victims in case of background operations when reflecting columns
-        #     engine = sa.create_engine(
-        #         engine_url, execution_options={"isolation_level": "RS"}
-        #     )
-        # sqlalchemy 2 has create_engine().execution_options()
+    def _create_engine(self):
+        engine = sa.create_engine(self.engine_url)
 
         if engine.dialect.name == "mssql":
             engine.dispose()
             # this is needed to allow for CREATE DATABASE statements
             # (we don't rely on database transactions anyways)
-            engine = sa.create_engine(engine_url, connect_args={"autocommit": True})
+            engine = sa.create_engine(
+                self.engine_url, connect_args={"autocommit": True}
+            )
 
-        if engine.dialect.name == "mssql":
-            if "." in schema_prefix and "." in schema_suffix:
+            if "." in self.schema_prefix and "." in self.schema_suffix:
                 raise AttributeError(
                     "Config Error: It is not allowed to have a dot in both"
                     " schema_prefix and schema_suffix for SQL Server / mssql database:"
-                    f' schema_prefix="{schema_prefix}", schema_suffix="{schema_suffix}"'
+                    f' schema_prefix="{self.schema_prefix}","'
+                    f' schema_suffix="{self.schema_suffix}"'
                 )
 
-            if (schema_prefix + schema_suffix).count(".") != 1:
+            if (self.schema_prefix + self.schema_suffix).count(".") != 1:
                 raise AttributeError(
                     "Config Error: There must be exactly dot in both schema_prefix and"
                     " schema_suffix together for SQL Server / mssql database:"
-                    f' schema_prefix="{schema_prefix}", schema_suffix="{schema_suffix}"'
+                    f' schema_prefix="{self.schema_prefix}",'
+                    f' schema_suffix="{self.schema_suffix}"'
                 )
+
+        # if engine.dialect.name == "ibm_db_sa":
+        #     engine.dispose()
+        #     # switch to READ STABILITY isolation level to avoid unnecessary deadlock
+        #     # victims in case of background operations when reflecting columns
+        #     engine = sa.create_engine(
+        #         engine_url, execution_options={"isolation_level": "RS"}
+        #     )
+        # sqlalchemy 2 has create_engine().execution_options()
+
         return engine
 
     @contextmanager
-    def engine_connect(self):
+    @engine_dispatch
+    def engine_connect(self) -> sa.Connection:
         if self.engine.dialect.name == "ibm_db_sa":
             conn = self.engine.connect()
         else:
             # sqlalchemy 2.0 uses this (except for dialect ibm_db_sa)
-            conn = self.engine.connect().execution_options(isolation_level="AUTOCOMMIT")
+            conn = (
+                self.engine.connect()
+            )  # .execution_options(isolation_level="AUTOCOMMIT")
         try:
             yield conn
         finally:
             try:
                 # sqlalchemy 2.0 + ibm_db_sa needs this
                 conn.commit()
             except AttributeError:
-                # sqlalchemy 1.x does not have this function and does not need it
                 pass
 
     def get_schema(self, name):
         return Schema(name, self.schema_prefix, self.schema_suffix)
 
     def _execute(self, query, conn: sa.engine.Connection):
         if self.print_sql:
@@ -385,17 +410,14 @@
         schema: Schema,
         key_columns: list[str],
         *,
         name: str | None = None,
         early_not_null_possible: bool = False,
     ):
         _ = early_not_null_possible  # only used for some dialects
-        self.execute(
-            ChangeColumnNullable(table_name, schema, key_columns, nullable=False)
-        )
         self.execute(AddPrimaryKey(table_name, schema, key_columns, name))
 
     @engine_dispatch
     def add_index(
         self,
         table_name: str,
         schema: Schema,
@@ -1263,14 +1285,15 @@
                 conn.execute(
                     self.tasks_table.insert().values(
                         name=metadata.name,
                         stage=metadata.stage,
                         version=metadata.version,
                         timestamp=metadata.timestamp,
                         run_id=metadata.run_id,
+                        position_hash=metadata.position_hash,
                         input_hash=metadata.input_hash,
                         cache_fn_hash=metadata.cache_fn_hash,
                         output_json=metadata.output_json,
                         in_transaction_schema=True,
                     )
                 )
 
@@ -1311,19 +1334,48 @@
 
         return TaskMetadata(
             name=result.name,
             stage=result.stage,
             version=result.version,
             timestamp=result.timestamp,
             run_id=result.run_id,
+            position_hash=result.position_hash,
             input_hash=result.input_hash,
             cache_fn_hash=result.cache_fn_hash,
             output_json=result.output_json,
         )
 
+    def retrieve_all_task_metadata(self, task: MaterializingTask) -> list[TaskMetadata]:
+        with self.engine_connect() as conn:
+            results = (
+                conn.execute(
+                    self.tasks_table.select()
+                    .where(self.tasks_table.c.name == task.name)
+                    .where(self.tasks_table.c.stage == task.stage.name)
+                    .where(self.tasks_table.c.position_hash == task.position_hash)
+                )
+                .mappings()
+                .all()
+            )
+
+        return [
+            TaskMetadata(
+                name=result.name,
+                stage=result.stage,
+                version=result.version,
+                timestamp=result.timestamp,
+                run_id=result.run_id,
+                position_hash=result.position_hash,
+                input_hash=result.input_hash,
+                cache_fn_hash=result.cache_fn_hash,
+                output_json=result.output_json,
+            )
+            for result in results
+        ]
+
     def store_lazy_table_metadata(self, metadata: LazyTableMetadata):
         if not self.disable_caching:
             with self.engine_connect() as conn:
                 conn.execute(
                     self.lazy_cache_table.insert().values(
                         name=metadata.name,
                         stage=metadata.stage,
@@ -1479,117 +1531,25 @@
             result = conn.execute(
                 sa.select(self.tasks_table.c.output_json)
                 .where(self.tasks_table.c.stage == stage.name)
                 .where(self.tasks_table.c.in_transaction_schema.in_([False]))
                 .order_by(self.tasks_table.c.output_json)
             ).all()
             result = [row[0] for row in result]
-        return compute_cache_key(*result)
+        return stable_hash(*result)
 
     # DatabaseLockManager
 
     def get_engine_for_locking(self) -> sa.Engine:
-        return self._connect(self.engine_url, self.schema_prefix, self.schema_suffix)
+        return self._create_engine()
 
     def get_lock_schema(self) -> Schema:
         return self.get_schema(self.LOCK_SCHEMA)
 
 
-@SQLTableStore.register_table()
-class SQLAlchemyTableHook(TableHook[SQLTableStore]):
-    @classmethod
-    def can_materialize(cls, type_) -> bool:
-        return issubclass(
-            type_, (sa.sql.elements.TextClause, sa.sql.selectable.Selectable)
-        )
-
-    @classmethod
-    def can_retrieve(cls, type_) -> bool:
-        return type_ == sa.Table
-
-    @classmethod
-    def materialize(
-        cls,
-        store,
-        table: Table[sa.sql.elements.TextClause | sa.Text],
-        stage_name,
-        task_info: TaskInfo | None,
-    ):
-        obj = table.obj
-        if isinstance(table.obj, (sa.Table, sa.sql.selectable.Alias)):
-            obj = sa.select("*").select_from(table.obj)
-
-        source_tables = [
-            dict(
-                name=tbl.name,
-                schema=store.get_schema(
-                    tbl.stage.transaction_name
-                    if tbl.stage in task_info.open_stages
-                    else tbl.stage.name
-                ).get(),
-            )
-            for tbl in task_info.input_tables
-        ]
-        schema = store.get_schema(stage_name)
-        store.execute(
-            CreateTableAsSelect(
-                table.name,
-                schema,
-                obj,
-                early_not_null=table.primary_key,
-                source_tables=source_tables,
-            )
-        )
-        store.add_indexes(table, schema, early_not_null_possible=True)
-
-    @classmethod
-    def retrieve(
-        cls, store, table, stage_name, as_type: type[sa.Table], namer=None
-    ) -> sa.sql.selectable.Selectable:
-        table_name = table.name
-        schema = store.get_schema(stage_name).get()
-        table_name, schema = store.resolve_aliases(table_name, schema)
-        tbl = None
-        for retry_iteration in range(4):
-            # retry operation since it might have been terminated as a deadlock victim
-            try:
-                alias_name = (
-                    namer.get_name(table_name) if namer is not None else table_name
-                )
-                tbl = sa.Table(
-                    table_name,
-                    sa.MetaData(),
-                    schema=schema,
-                    autoload_with=store.engine,
-                ).alias(alias_name)
-                break
-            except (sa.exc.SQLAlchemyError, sa.exc.DBAPIError):
-                if retry_iteration == 3:
-                    raise
-                time.sleep(retry_iteration * retry_iteration * 1.2)
-        return tbl
-
-    @classmethod
-    def lazy_query_str(cls, store, obj) -> str:
-        if isinstance(obj, sa.sql.selectable.FromClause):
-            query = sa.select("*").select_from(obj)
-        else:
-            query = obj
-        query_str = str(
-            query.compile(store.engine, compile_kwargs={"literal_binds": True})
-        )
-        # hacky way to canonicalize query (despite __tmp/__even/__odd suffixes
-        # and alias resolution)
-        query_str = re.sub(r'["\[\]]', "", query_str)
-        query_str = re.sub(
-            r'(__tmp|__even|__odd)(?=[ \t\n.;"]|$)', "", query_str.lower()
-        )
-        return query_str
-
-
 def _resolve_alias_ibm_db_sa(conn, table_name: str, schema: str, *, _iteration=0):
     # TODO: consider speeding this up by caching information for complete schemas
     #  instead of running at least two queries per source table; Ultimately problem can
     #  also be fixed by upstream contribution to ibm_db_sa
 
     # we need to resolve aliases since pandas.read_sql_table does not work for them
     # and sa.Table does not auto-reflect columns
@@ -1652,496 +1612,9 @@
         table_name = parts[2]
         table_name, schema = _resolve_alias_mssql(
             conn, table_name, schema, _iteration=_iteration + 1
         )
     return table_name, schema
 
 
-@SQLTableStore.register_table(pd)
-class PandasTableHook(TableHook[SQLTableStore]):
-    """
-    Materalize pandas->sql and retrieve sql->pandas.
-
-    We like to limit the use of types, so operations can be implemented reliably
-    without the use of pandas dtype=object where every row can have different type:
-      - string/varchar/clob: pd.StringDType
-      - date: datetime64[ns] (we cap year in 1900..2199 and save original year
-            in separate column)
-      - datetime: datetime64[ns] (we cap year in 1900..2199 and save original year
-            in separate column)
-      - int: pd.Int64DType
-      - boolean: pd.BooleanDType
-
-    Dialect specific aspects:
-      * ibm_db_sa:
-        - DB2 does not support boolean type -> integer
-        - We limit string columns to 256 characters since larger columns have
-          trouble with adding indexes/primary keys
-    """
-
-    @classmethod
-    def can_materialize(cls, type_) -> bool:
-        return issubclass(type_, pd.DataFrame)
-
-    @classmethod
-    def can_retrieve(cls, type_) -> bool:
-        return type_ == pd.DataFrame
-
-    @classmethod
-    def materialize(
-        cls,
-        store,
-        table: Table[pd.DataFrame],
-        stage_name,
-        task_info: TaskInfo | None,
-    ):
-        # we might try to avoid this copy for speedup / saving RAM
-        df = table.obj.copy()
-        schema = store.get_schema(stage_name)
-        if store.print_materialize:
-            store.logger.info(
-                f"Writing table '{schema.get()}.{table.name}'",
-                table_obj=table.obj,
-            )
-        dtype_map = {}
-        table_name = table.name
-        str_type = sa.String()
-        if store.engine.dialect.name == "ibm_db_sa":
-            # Default string target is CLOB which can't be used for indexing.
-            # We could use VARCHAR(32000), but if we change this to VARCHAR(256)
-            # for indexed columns, DB2 hangs.
-            str_type = sa.VARCHAR(256)
-            table_name = ibm_db_sa_fix_name(table_name)
-        # force dtype=object to string (we require dates to be stored in datetime64[ns])
-        for col in df.dtypes.loc[lambda x: x == object].index:
-            if table.type_map is None or col not in table.type_map:
-                df[col] = df[col].astype(str)
-                dtype_map[col] = str_type
-        for col in df.dtypes.loc[
-            lambda x: (x != object) & x.isin([pd.Int32Dtype, pd.UInt16Dtype])
-        ].index:
-            dtype_map[col] = sa.INTEGER()
-        for col in df.dtypes.loc[
-            lambda x: (x != object)
-            & x.isin([pd.Int16Dtype, pd.Int8Dtype, pd.UInt8Dtype])
-        ].index:
-            dtype_map[col] = sa.SMALLINT()
-        if table.type_map is not None:
-            dtype_map.update(table.type_map)
-        # Todo: do better abstraction of dialect specific code
-        if store.engine.dialect.name == "mssql":
-            for col, _type in dtype_map.items():
-                if _type == sa.DateTime:
-                    dtype_map[col] = DATETIME2()
-        df.to_sql(
-            table_name,
-            store.engine,
-            schema=schema.get(),
-            index=False,
-            dtype=dtype_map,
-            chunksize=100_000,
-        )
-        store.add_indexes(table, schema)
-
-    @staticmethod
-    def _pandas_type(sql_type):
-        if isinstance(sql_type, sa.SmallInteger):
-            return pd.Int16Dtype()
-        elif isinstance(sql_type, sa.BigInteger):
-            return pd.Int64Dtype()
-        elif isinstance(sql_type, sa.Integer):
-            return pd.Int32Dtype()
-        elif isinstance(sql_type, sa.Boolean):
-            return pd.BooleanDtype()
-        elif isinstance(sql_type, sa.String):
-            return pd.StringDtype()
-        elif isinstance(sql_type, sa.Date):
-            return "datetime64[ns]"
-        elif isinstance(sql_type, sa.DateTime):
-            return "datetime64[ns]"
-
-    @staticmethod
-    def _fix_cols(cols: dict[str, Any], dialect_name):
-        cols = cols.copy()
-        year_cols = []
-        min_date = "1900-01-01"
-        max_date = "2199-12-31"
-        for name, col in list(cols.items()):
-            if isinstance(col.type, sa.Date) or isinstance(col.type, sa.DateTime):
-                if name + "_year" not in cols:
-                    cols[name + "_year"] = sa.cast(
-                        sa.func.extract("year", cols[name]), sa.Integer
-                    ).label(name + "_year")
-                    year_cols.append(name + "_year")
-                # Todo: do better abstraction of dialect specific code
-                if dialect_name == "mssql":
-                    cap_min = sa.func.iif(cols[name] < min_date, min_date, cols[name])
-                    cols[name] = sa.func.iif(
-                        cap_min > max_date, max_date, cap_min
-                    ).label(name)
-                else:
-                    cols[name] = sa.func.least(
-                        max_date, sa.func.greatest(min_date, cols[name])
-                    ).label(name)
-        return cols, year_cols
-
-    @classmethod
-    def retrieve(
-        cls,
-        store: SQLTableStore,
-        table: Table,
-        stage_name: str,
-        as_type: type[pd.DataFrame],
-        namer: NameDisambiguator | None = None,
-    ) -> pd.DataFrame:
-        schema = store.get_schema(stage_name).get()
-        with store.engine.connect() as conn:
-            table_name = table.name
-            table_name, schema = store.resolve_aliases(table_name, schema)
-            for retry_iteration in range(4):
-                # retry operation since it might have been terminated as a
-                # deadlock victim
-                try:
-                    sql_table = sa.Table(
-                        table_name,
-                        sa.MetaData(),
-                        schema=schema,
-                        autoload_with=store.engine,
-                    ).alias("tbl")
-                    dtype_map = {c.name: cls._pandas_type(c.type) for c in sql_table.c}
-                    cols, year_cols = cls._fix_cols(
-                        {c.name: c for c in sql_table.c}, store.engine.dialect.name
-                    )
-                    dtype_map.update({col: pd.Int16Dtype() for col in year_cols})
-                    query = sa.select(*cols.values()).select_from(sql_table)
-                    try:
-                        # works only from pandas 2.0.0 on
-                        df = pd.read_sql(
-                            query,
-                            con=conn,
-                            dtype=dtype_map,
-                        )
-                    except TypeError:
-                        df = pd.read_sql(query, con=conn)
-                        for col, _type in dtype_map.items():
-                            df[col] = df[col].astype(_type)
-                    break
-                except (sa.exc.SQLAlchemyError, sa.exc.DBAPIError):
-                    if retry_iteration == 3:
-                        raise
-                    time.sleep(retry_iteration * retry_iteration * 1.3)
-            return df
-
-    @classmethod
-    def auto_table(cls, obj: pd.DataFrame):
-        if name := obj.attrs.get("name"):
-            return Table(obj, name)
-        return super().auto_table(obj)
-
-
-try:
-    # optional dependency to polars
-    import connectorx
-    import polars
-except ImportError as e:
-    warnings.warn(str(e), ImportWarning)
-    polars = None
-    connectorx = None
-
-
-@SQLTableStore.register_table(polars, connectorx)
-class PolarsTableHook(TableHook[SQLTableStore]):
-    @classmethod
-    def can_materialize(cls, type_) -> bool:
-        # attention: tidypolars.Tibble is subclass of polars DataFrame
-        return type_ == polars.dataframe.DataFrame
-
-    @classmethod
-    def can_retrieve(cls, type_) -> bool:
-        return type_ == polars.dataframe.DataFrame
-
-    @classmethod
-    def materialize(
-        cls,
-        store,
-        table: Table[polars.dataframe.DataFrame],
-        stage_name,
-        task_info: TaskInfo | None,
-    ):
-        schema = store.get_schema(stage_name)
-        if store.print_materialize:
-            store.logger.info(
-                f"Writing table '{schema.get()}.{table.name}'",
-                table_obj=table.obj,
-            )
-        table_name = table.name
-        # TODO:
-        # dtype_map = {}
-        # if store.engine.dialect.name == "ibm_db_sa":
-        #     # Default string target is CLOB which can't be used for indexing.
-        #     # We could use VARCHAR(32000), but if we change this to VARCHAR(256)
-        #     # for indexed columns, DB2 hangs.
-        #     dtype_map = {
-        #         col: sa.VARCHAR(256)
-        #         for col in table.obj.dtypes.loc[lambda x: x == object].index
-        #     }
-        #     table_name = ibm_db_sa_fix_name(table_name)
-        table.obj.to_pandas(use_pyarrow_extension_array=True).to_sql(
-            name=table_name, con=store.engine, schema=schema.get(), index=False
-        )
-        store.add_indexes(table, schema)
-
-    @classmethod
-    def retrieve(
-        cls,
-        store: SQLTableStore,
-        table: Table,
-        stage_name: str,
-        as_type: type[polars.dataframe.DataFrame],
-        namer: NameDisambiguator | None = None,
-    ) -> polars.dataframe.DataFrame:
-        schema = store.get_schema(stage_name).get()
-        table_name = table.name
-        table_name, schema = store.resolve_aliases(table_name, schema)
-        connection_uri = store.engine_url.render_as_string(hide_password=False)
-        df = polars.read_database(
-            f'SELECT * FROM {schema}."{table_name}"', connection_uri
-        )
-        return df
-
-    @classmethod
-    def auto_table(cls, obj: polars.dataframe.DataFrame):
-        # currently, we don't know how to store a table name inside polars dataframe
-        return super().auto_table(obj)
-
-
-try:
-    # optional dependency to polars
-    import tidypolars
-except ImportError as e:
-    warnings.warn(str(e), ImportWarning)
-    tidypolars = None
-
-
-@SQLTableStore.register_table(tidypolars, polars, connectorx)
-class TidyPolarsTableHook(TableHook[SQLTableStore]):
-    @classmethod
-    def can_materialize(cls, type_) -> bool:
-        return issubclass(type_, tidypolars.Tibble)
-
-    @classmethod
-    def can_retrieve(cls, type_) -> bool:
-        return type_ == tidypolars.Tibble
-
-    @classmethod
-    def materialize(
-        cls,
-        store,
-        table: Table[tidypolars.Tibble],
-        stage_name,
-        task_info: TaskInfo | None,
-    ):
-        t = table.obj
-        table = table.copy_without_obj()
-        table.obj = t.to_polars()
-        PolarsTableHook.materialize(store, table, stage_name, task_info)
-
-    @classmethod
-    def retrieve(
-        cls,
-        store: SQLTableStore,
-        table: Table,
-        stage_name: str,
-        as_type: type[tidypolars.Tibble],
-        namer: NameDisambiguator | None = None,
-    ) -> tidypolars.Tibble:
-        df = PolarsTableHook.retrieve(store, table, stage_name, as_type, namer)
-        return tidypolars.from_polars(df)
-
-    @classmethod
-    def auto_table(cls, obj: tidypolars.Tibble):
-        # currently, we don't know how to store a table name inside tidypolars tibble
-        return super().auto_table(obj)
-
-
-try:
-    # optional dependency to pydiverse-transform
-    import pydiverse.transform as pdt
-except ImportError as e:
-    warnings.warn(str(e), ImportWarning)
-    pdt = None
-
-
-# noinspection PyUnresolvedReferences, PyProtectedMember
-@SQLTableStore.register_table(pdt)
-class PydiverseTransformTableHook(TableHook[SQLTableStore]):
-    @classmethod
-    def can_materialize(cls, type_) -> bool:
-        return issubclass(type_, pdt.Table)
-
-    @classmethod
-    def can_retrieve(cls, type_) -> bool:
-        from pydiverse.transform.eager import PandasTableImpl
-        from pydiverse.transform.lazy import SQLTableImpl
-
-        return issubclass(type_, (PandasTableImpl, SQLTableImpl))
-
-    @classmethod
-    def materialize(
-        cls, store, table: Table[pdt.Table], stage_name, task_info: TaskInfo | None
-    ):
-        from pydiverse.transform.eager import PandasTableImpl
-        from pydiverse.transform.lazy import SQLTableImpl
-
-        t = table.obj
-        table = table.copy_without_obj()
-        if isinstance(t._impl, PandasTableImpl):
-            from pydiverse.transform.core.verbs import collect
-
-            table.obj = t >> collect()
-            # noinspection PyTypeChecker
-            return PandasTableHook.materialize(store, table, stage_name, task_info)
-        if isinstance(t._impl, SQLTableImpl):
-            table.obj = t._impl.build_select()
-            # noinspection PyTypeChecker
-            return SQLAlchemyTableHook.materialize(store, table, stage_name, task_info)
-        raise NotImplementedError
-
-    @classmethod
-    def retrieve(
-        cls,
-        store: SQLTableStore,
-        table: Table,
-        stage_name: str,
-        as_type: type[T],
-        namer: NameDisambiguator | None = None,
-    ) -> T:
-        from pydiverse.transform.eager import PandasTableImpl
-        from pydiverse.transform.lazy import SQLTableImpl
-
-        if issubclass(as_type, PandasTableImpl):
-            df = PandasTableHook.retrieve(store, table, stage_name, pd.DataFrame, namer)
-            return pdt.Table(PandasTableImpl(table.name, df))
-        if issubclass(as_type, SQLTableImpl):
-            sa_tbl = SQLAlchemyTableHook.retrieve(
-                store, table, stage_name, sa.Table, namer
-            )
-            return pdt.Table(SQLTableImpl(store.engine, sa_tbl))
-        raise NotImplementedError
-
-    @classmethod
-    def auto_table(cls, obj: pdt.Table):
-        return Table(obj, obj._impl.name)
-
-    @classmethod
-    def lazy_query_str(cls, store, obj: pdt.Table) -> str:
-        from pydiverse.transform.core.verbs import build_query
-
-        query = obj >> build_query()
-
-        if query is not None:
-            return str(query)
-        return super().lazy_query_str(store, obj)
-
-
-try:
-    # optional dependency to ibis
-    import ibis
-except ImportError as e:
-    warnings.warn(str(e), ImportWarning)
-    ibis = None
-
-
-@SQLTableStore.register_table(ibis)
-class IbisTableHook(TableHook[SQLTableStore]):
-    @staticmethod
-    def get_con(store):
-        # TODO: move this function to a better ibis specific place
-        con = store.engines_other.get("ibis")
-        if con is None:
-            url = store.engine_url
-            dialect = store.engine.dialect.name
-            if dialect == "postgresql":
-                con = ibis.postgres.connect(
-                    host=url.host,
-                    user=url.username,
-                    password=url.password,
-                    port=url.port,
-                    database=url.database,
-                )
-            elif dialect == "mssql":
-                con = ibis.mssql.connect(
-                    host=url.host,
-                    user=url.username,
-                    password=url.password,
-                    port=url.port,
-                    database=url.database,
-                )
-            else:
-                raise RuntimeError(
-                    f"initializing ibis for {dialect} is not supported, yet "
-                    "-- supported: postgresql, mssql"
-                )
-            store.engines_other["ibis"] = con
-        return con
-
-    @classmethod
-    def can_materialize(cls, type_) -> bool:
-        # Operations on a table like mutate() or join() don't change the type
-        return issubclass(type_, ibis.expr.types.Table)
-
-    @classmethod
-    def can_retrieve(cls, type_) -> bool:
-        return issubclass(type_, ibis.expr.types.Table)
-
-    @classmethod
-    def materialize(
-        cls,
-        store,
-        table: Table[ibis.expr.types.Table],
-        stage_name,
-        task_info: TaskInfo | None,
-    ):
-        t = table.obj
-        table = table.copy_without_obj()
-        table.obj = sa.text(cls.lazy_query_str(store, t))
-        return SQLAlchemyTableHook.materialize(store, table, stage_name, task_info)
-
-    @classmethod
-    def retrieve(
-        cls,
-        store: SQLTableStore,
-        table: Table,
-        stage_name: str,
-        as_type: type[ibis.expr.types.Table],
-        namer: NameDisambiguator | None = None,
-    ) -> ibis.expr.types.Table:
-        con = cls.get_con(store)
-        table_name = table.name
-        schema = store.get_schema(stage_name).get()
-        table_name, schema = store.resolve_aliases(table_name, schema)
-        for retry_iteration in range(4):
-            # retry operation since it might have been terminated as a deadlock victim
-            try:
-                tbl = con.table(
-                    table_name,
-                    schema=schema,
-                )
-                break
-            except (sa.exc.SQLAlchemyError, sa.exc.DBAPIError):
-                if retry_iteration == 3:
-                    raise
-                time.sleep(retry_iteration * retry_iteration * 1.2)
-        else:
-            raise Exception
-        return tbl
-
-    @classmethod
-    def auto_table(cls, obj: ibis.expr.types.Table):
-        if obj.has_name():
-            return Table(obj, obj.get_name())
-        else:
-            return super().auto_table(obj)
-
-    @classmethod
-    def lazy_query_str(cls, store, obj: ibis.expr.types.Table) -> str:
-        return str(ibis.to_sql(obj, cls.get_con(store).name))
+# Load SQLTableStore Hooks
+from pydiverse.pipedag.backend.table.sql_hooks import *  # noqa
```

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/backend/table/util/engine_dispatch.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/backend/table/util/engine_dispatch.py`

 * *Files 19% similar despite different names*

```diff
@@ -1,36 +1,69 @@
 from __future__ import annotations
 
 import functools
+import inspect
 import warnings
 from typing import TYPE_CHECKING, Callable, Protocol
 
 from pydiverse.pipedag._typing import CallableT
 
 if TYPE_CHECKING:
 
     class EngineDispatchedFn(Protocol):
         dialect: Callable[[str], Callable[[CallableT], CallableT]]
         original: CallableT
 
 
 __all__ = [
     "engine_dispatch",
+    "engine_argument_dispatch",
+    "classmethod_engine_argument_dispatch",
 ]
 
 
 def engine_dispatch(fn: CallableT) -> CallableT | EngineDispatchedFn:
     """Dispatch a function based on `self.engine.dialect.name`."""
+
+    def get_dialect(*args, **kwargs):
+        self_or_cls = args[0]
+        return self_or_cls.engine.dialect
+
+    return _engine_dispatch_generator(fn, get_dialect)
+
+
+def engine_argument_dispatch(fn: CallableT) -> CallableT | EngineDispatchedFn:
+    """Dispatch a function based on argument named `engine`"""
+    signature = inspect.signature(fn)
+
+    def get_dialect(*args, **kwargs):
+        bound = signature.bind(*args, **kwargs)
+        engine = bound.arguments["engine"]
+        return engine.dialect
+
+    return _engine_dispatch_generator(fn, get_dialect)
+
+
+def classmethod_engine_argument_dispatch(
+    fn: CallableT,
+) -> CallableT | EngineDispatchedFn | classmethod:
+    dispatched = engine_argument_dispatch(fn)
+    cm_dispatched = classmethod(dispatched)
+    cm_dispatched.dialect = dispatched.dialect
+    cm_dispatched.original = fn
+    return cm_dispatched
+
+
+def _engine_dispatch_generator(fn, dialect_getter):
     fn_variants = {}
 
     @functools.wraps(fn)
     def wrapped(*args, **kwargs):
-        self_or_cls = args[0]
-        dialect_name = self_or_cls.engine.dialect.name
-        dispatched_fn = fn_variants.get(dialect_name, fn)
+        dialect = dialect_getter(*args, **kwargs)
+        dispatched_fn = fn_variants.get(dialect.name, fn)
         return dispatched_fn(*args, **kwargs)
 
     def dialect_decorator(dialect):
         def decorate(dialect_fn):
             if dialect in fn_variants:
                 msg = (
                     f"Already defined a variant of function '{fn.__name__}'"
```

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/backend/table/util/sql_ddl.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/backend/table/util/sql_ddl.py`

 * *Files 3% similar despite different names*

```diff
@@ -90,23 +90,27 @@
         self,
         name: str,
         schema: Schema,
         query: Select | TextClause | sa.Text,
         *,
         early_not_null: None | str | list[str] = None,
         source_tables: None | list[dict[str, str]] = None,
+        unlogged: bool = False,
     ):
         self.name = name
         self.schema = schema
         self.query = query
         # some dialects may choose to set NOT-NULL constraint in the middle of
         # create table as select
         self.early_not_null = early_not_null
-        # some dialects may lock source and destimation tables
+        # some dialects may lock source and destination tables
         self.source_tables = source_tables
+        # Postgres supports creating unlogged tables. Flag should get ignored by
+        # other dialects
+        self.unlogged = unlogged
 
 
 class CreateViewAsSelect(DDLElement):
     def __init__(self, name: str, schema: Schema, query: Select | TextClause | sa.Text):
         self.name = name
         self.schema = schema
         self.query = query
@@ -272,14 +276,34 @@
             nullable = [nullable for _ in column_names]
         self.table_name = table_name
         self.schema = schema
         self.column_names = column_names
         self.nullable = nullable
 
 
+class ChangeTableLogged(DDLElement):
+    """Changes a postgres table from LOGGED to UNLOGGED (or vice-versa)
+
+    This reduces safety in case of a crash or unclean shutdown, but can significantly
+    increase write performance:
+
+    https://www.postgresql.org/docs/9.5/sql-createtable.html#SQL-CREATETABLE-UNLOGGED
+    """
+
+    def __init__(
+        self,
+        table_name: str,
+        schema: Schema,
+        logged: bool,
+    ):
+        self.table_name = table_name
+        self.schema = schema
+        self.logged = logged
+
+
 @compiles(CreateSchema)
 def visit_create_schema(create: CreateSchema, compiler, **kw):
     _ = kw
     schema = compiler.preparer.format_schema(create.schema.get())
     text = ["CREATE SCHEMA"]
     if create.if_not_exists:
         text.append("IF NOT EXISTS")
@@ -498,14 +522,24 @@
 
 
 @compiles(CreateTableAsSelect)
 def visit_create_table_as_select(create: CreateTableAsSelect, compiler, **kw):
     return _visit_create_obj_as_select(create, compiler, "TABLE", kw)
 
 
+@compiles(CreateTableAsSelect, "postgresql")
+def visit_create_table_as_select_postgresql(
+    create: CreateTableAsSelect, compiler, **kw
+):
+    if create.unlogged:
+        return _visit_create_obj_as_select(create, compiler, "UNLOGGED TABLE", kw)
+    else:
+        return _visit_create_obj_as_select(create, compiler, "TABLE", kw)
+
+
 @compiles(CreateTableAsSelect, "mssql")
 def visit_create_table_as_select_mssql(create: CreateTableAsSelect, compiler, **kw):
     name = compiler.preparer.quote_identifier(create.name)
     full_name = create.schema.get()
     # it was already checked that there is exactly one dot in schema prefix + suffix
     database_name, schema_name = full_name.split(".")
     database = compiler.preparer.format_schema(database_name)
@@ -897,14 +931,34 @@
     cols = ",".join(
         [compiler.preparer.quote_identifier(col) for col in add_primary_key.key]
     )
     return f"ALTER TABLE {schema}.{table} ADD CONSTRAINT {pk_name} PRIMARY KEY ({cols})"
 
 
 # noinspection SqlDialectInspection
+@compiles(AddPrimaryKey, "duckdb")
+def visit_add_primary_key(add_primary_key: AddPrimaryKey, compiler, **kw):
+    _ = kw
+    table = compiler.preparer.quote_identifier(add_primary_key.table_name)
+    schema = compiler.preparer.format_schema(add_primary_key.schema.get())
+    pk_name = compiler.preparer.quote_identifier(
+        add_primary_key.name
+        if add_primary_key.name is not None
+        else "pk_"
+        + "_".join([c.lower() for c in add_primary_key.key])
+        + "_"
+        + add_primary_key.table_name.lower()
+    )
+    cols = ",".join(
+        [compiler.preparer.quote_identifier(col) for col in add_primary_key.key]
+    )
+    return f"CREATE UNIQUE INDEX {pk_name} ON {schema}.{table} ({cols})"
+
+
+# noinspection SqlDialectInspection
 @compiles(AddPrimaryKey, "mssql")
 def visit_add_primary_key(add_primary_key: AddPrimaryKey, compiler, **kw):
     _ = kw
     database, schema = _get_mssql_database_schema(add_primary_key.schema, compiler)
 
     table = compiler.preparer.quote_identifier(add_primary_key.table_name)
     pk_name = compiler.preparer.quote_identifier(
@@ -1015,14 +1069,15 @@
             compiler.preparer.quote_identifier(ibm_db_sa_fix_name(col))
             for col in add_index.index
         ]
     )
     return f"CREATE INDEX {schema}.{index_name} ON {schema}.{table} ({cols})"
 
 
+# noinspection SqlDialectInspection
 @compiles(ChangeColumnTypes)
 def visit_change_column_types(change: ChangeColumnTypes, compiler, **kw):
     _ = kw
     table = compiler.preparer.quote_identifier(change.table_name)
     schema = compiler.preparer.format_schema(change.schema.get())
     alter_columns = ",".join(
         [
@@ -1040,14 +1095,38 @@
             if nullable is not None
         ]
     )
     return f"ALTER TABLE {schema}.{table} {alter_columns}"
 
 
 # noinspection SqlDialectInspection
+@compiles(ChangeColumnTypes, "duckdb")
+def visit_change_column_types_duckdb(change: ChangeColumnTypes, compiler, **kw):
+    table = compiler.preparer.quote_identifier(change.table_name)
+    schema = compiler.preparer.format_schema(change.schema.get())
+    alter_columns = [
+        f"ALTER COLUMN {compiler.preparer.quote_identifier(col)} SET DATA TYPE"
+        f" {compiler.type_compiler.process(_type)}"
+        for col, _type, nullable in zip(
+            change.column_names, change.column_types, change.nullable
+        )
+    ] + [
+        "ALTER COLUMN"
+        f" {compiler.preparer.quote_identifier(col)}"
+        f" {'SET' if not nullable else 'DROP'} NOT NULL"
+        for col, nullable in zip(change.column_names, change.nullable)
+        if nullable is not None
+    ]
+    statements = [
+        f"ALTER TABLE {schema}.{table} {statement}" for statement in alter_columns
+    ]
+    return join_ddl_statements(statements, compiler, **kw)
+
+
+# noinspection SqlDialectInspection
 @compiles(ChangeColumnTypes, "mssql")
 def visit_change_column_types(change: ChangeColumnTypes, compiler, **kw):
     _ = kw
     database, schema = _get_mssql_database_schema(change.schema, compiler)
 
     table = compiler.preparer.quote_identifier(change.table_name)
 
@@ -1109,15 +1188,15 @@
     ]
     statements.append(f"call sysproc.admin_cmd('REORG TABLE {schema}.{table}')")
     return join_ddl_statements(statements, compiler, **kw)
 
 
 # noinspection SqlDialectInspection
 @compiles(ChangeColumnNullable)
-def visit_change_column_types(change: ChangeColumnNullable, compiler, **kw):
+def visit_change_column_nullable(change: ChangeColumnNullable, compiler, **kw):
     _ = kw
     table = compiler.preparer.quote_identifier(change.table_name)
     schema = compiler.preparer.format_schema(change.schema.get())
     alter_columns = ",".join(
         [
             "ALTER COLUMN"
             f" {compiler.preparer.quote_identifier(col)}"
@@ -1126,24 +1205,33 @@
         ]
     )
     return f"ALTER TABLE {schema}.{table} {alter_columns}"
 
 
 # noinspection SqlDialectInspection
 @compiles(ChangeColumnNullable, "ibm_db_sa")
-def visit_change_column_types_db2(change: ChangeColumnNullable, compiler, **kw):
+def visit_change_column_nullable(change: ChangeColumnNullable, compiler, **kw):
     _ = kw
     # DB2 stores capitalized table names but sqlalchemy reflects them lowercase
     change = copy.deepcopy(change)
     change.table_name = ibm_db_sa_fix_name(change.table_name)
 
     statements = _get_nullable_change_statements(change, compiler)
     return join_ddl_statements(statements, compiler, **kw)
 
 
+@compiles(ChangeTableLogged, "postgresql")
+def visit_change_table_logged(change: ChangeTableLogged, compiler, **kw):
+    _ = kw
+    table_name = compiler.preparer.quote_identifier(change.table_name)
+    schema = compiler.preparer.format_schema(change.schema.get())
+    logged = "LOGGED" if change.logged else "UNLOGGED"
+    return f"ALTER TABLE {schema}.{table_name} SET {logged}"
+
+
 def _get_nullable_change_statements(change, compiler):
     table = compiler.preparer.quote_identifier(change.table_name)
     schema = compiler.preparer.format_schema(change.schema.get())
     statements = [
         f"ALTER TABLE {schema}.{table} ALTER COLUMN"
         f" {compiler.preparer.quote_identifier(ibm_db_sa_fix_name(col))}"
         f" {'SET' if not nullable else 'DROP'} NOT NULL"
```

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/backend/table_cache.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/backend/table_cache.py`

 * *Files identical despite different names*

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/context/context.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/context/context.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,27 +1,27 @@
 from __future__ import annotations
 
 from contextvars import ContextVar, Token
 from enum import Enum
 from functools import cached_property
 from threading import Lock
-from typing import TYPE_CHECKING, Any, ClassVar
+from typing import TYPE_CHECKING, ClassVar
+
+import structlog
+from attrs import define, evolve, frozen
+from box import Box
 
 from pydiverse.pipedag.util.import_ import import_object, load_object
 
 if TYPE_CHECKING:
     from pydiverse.pipedag._typing import T
     from pydiverse.pipedag.backend import BaseLockManager
     from pydiverse.pipedag.context.run_context import StageLockStateHandler
     from pydiverse.pipedag.core import Flow, Stage, Task
     from pydiverse.pipedag.engine.base import OrchestrationEngine
-    from pydiverse.pipedag.materialize.metadata import TaskMetadata
-
-import structlog
-from attrs import define, evolve, frozen
 
 
 class BaseContext:
     _context_var: ClassVar[ContextVar]
     _token: Token = None
     _enter_counter: int = 0
     _lock: Lock = Lock()
@@ -81,19 +81,15 @@
     """Context used while executing a task
 
     It is used to retrieve a reference to the task object from within a running task.
     It also serves as a place to store temporary state while processing a task.
     """
 
     task: Task
-
-    # Temporary state associated with a task during materialization
-    input_hash: str = None
-    cache_fn_hash: str = None
-    cache_metadata: TaskMetadata = None
+    is_cache_valid: bool | None = None
 
     _context_var = ContextVar("task_context")
 
 
 class StageCommitTechnique(Enum):
     SCHEMA_SWAP = 0
     READ_VIEWS = 1
@@ -112,61 +108,63 @@
     accessed by multi-threaded / multi-processed / multi-node way of orchestrating
     functions in the pipedag. Since they don't keep real state, they can be
     thrown away while pickling and will be reloaded on first access of the
     @cached_property store. Calling ConfigContext.dispose() will close all
     connections and render this object unusable afterwards.
     """
 
-    config_dict: dict
+    _config_dict: dict
 
     # names
     pipedag_name: str
-    flow_name: str
+    flow_name: str | None
     instance_name: str
 
     # per instance attributes
     fail_fast: bool
     strict_result_get_locking: bool
     ignore_task_version: bool
     instance_id: str  # may be used as database name or locking ID
     stage_commit_technique: StageCommitTechnique
     network_interface: str
-    attrs: dict[str, Any]
+    attrs: Box
 
     # other configuration options
     ignore_fresh_input: bool = False
 
     # INTERNAL FLAGS - ONLY FOR PIPEDAG USE
     # When set to True, exceptions raised in a flow don't get logged
     _swallow_exceptions: bool = False
 
     @cached_property
     def auto_table(self) -> tuple[type, ...]:
-        return tuple(map(import_object, self.config_dict.get("auto_table", ())))
+        return tuple(map(import_object, self._config_dict.get("auto_table", ())))
 
     @cached_property
     def auto_blob(self) -> tuple[type, ...]:
-        return tuple(map(import_object, self.config_dict.get("auto_blob", ())))
+        return tuple(map(import_object, self._config_dict.get("auto_blob", ())))
 
     @cached_property
     def store(self):
+        from pydiverse.pipedag.backend.table_cache import LocalTableCache
+        from pydiverse.pipedag.materialize.store import PipeDAGStore
+
         # Load objects referenced in config
         try:
-            from pydiverse.pipedag.backend.table_cache import LocalTableCache
-
-            table_store = load_object(self.config_dict["table_store"])
-            if "local_table_cache" in self.config_dict["table_store"]:
-                local_cache_cfg = self.config_dict["table_store"]["local_table_cache"]
+            table_store_config = self._config_dict["table_store"]
+            table_store = load_object(table_store_config)
+            if "local_table_cache" in table_store_config:
+                local_cache_config = table_store_config["local_table_cache"]
                 local_table_cache = LocalTableCache(
-                    load_object(local_cache_cfg),
-                    local_cache_cfg.get("store_input", True),
-                    local_cache_cfg.get("store_output", False),
-                    local_cache_cfg.get("use_stored_input_as_cache", True),
+                    load_object(local_cache_config),
+                    local_cache_config.get("store_input", True),
+                    local_cache_config.get("store_output", False),
+                    local_cache_config.get("use_stored_input_as_cache", True),
                 )
-                unknown_attributes = set(local_cache_cfg.keys()) - {
+                unknown_attributes = set(local_cache_config.keys()) - {
                     "class",
                     "args",
                     "store_input",
                     "store_output",
                     "use_stored_input_as_cache",
                 }
                 if len(unknown_attributes) > 0:
@@ -183,34 +181,33 @@
                     store_output=False,
                     use_stored_input_as_cache=False,
                 )
         except Exception as e:
             raise RuntimeError("Failed loading table_store") from e
 
         try:
-            blob_store = load_object(self.config_dict["blob_store"])
+            blob_store = load_object(self._config_dict["blob_store"])
         except Exception as e:
             raise RuntimeError("Failed loading blob_store") from e
-        from pydiverse.pipedag.materialize.store import PipeDAGStore
 
         return PipeDAGStore(
             table=table_store,
             blob=blob_store,
             local_table_cache=local_table_cache,
         )
 
     def evolve(self, **changes) -> ConfigContext:
         """Create a new instance with the changes applied; Wrapper for attrs.evolve"""
         return evolve(self, **changes)
 
     def create_lock_manager(self) -> BaseLockManager:
-        return load_object(self.config_dict["lock_manager"])
+        return load_object(self._config_dict["lock_manager"])
 
     def create_orchestration_engine(self) -> OrchestrationEngine:
-        return load_object(self.config_dict["orchestration"])
+        return load_object(self._config_dict["orchestration"])
 
     def close(self):
         # If the store has been initialized (and thus cached in the __dict__),
         # dispose of it, and remove it from the cache.
         if store := self.__dict__.get("store", None):
             store.dispose()
             self.__dict__.pop("store")
```

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/context/run_context.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/context/run_context.py`

 * *Files 3% similar despite different names*

```diff
@@ -23,18 +23,17 @@
     StageLockContext,
 )
 from pydiverse.pipedag.errors import LockError, RemoteProcessError, StageError
 from pydiverse.pipedag.util import Disposable
 from pydiverse.pipedag.util.ipc import IPCServer
 
 if TYPE_CHECKING:
-    from pydiverse.pipedag import Flow, Stage
     from pydiverse.pipedag._typing import T
     from pydiverse.pipedag.backend import BaseLockManager, LockState
-    from pydiverse.pipedag.core import Task
+    from pydiverse.pipedag.core import Stage, Subflow, Task
     from pydiverse.pipedag.materialize import Blob, Table
 
 
 def synchronized(lock_attr: str):
     def decorator(func: T) -> T:
         @functools.wraps(func)
         def synced_func(self, *args, **kwargs):
@@ -61,37 +60,39 @@
     RunContextServer spawns a thread in __enter__(). The actual context is managed
     in RunContext class. The constructor of RunContext() spawns the thread by
     calling RunContextServer.get_client(). The returned IPCClient object
     supports __getstate__() / __setstate__() methods, so they support serialization
     and deserialization in case of multi-node execution of tasks in pipedag graph.
     """
 
-    def __init__(self, flow: Flow):
+    def __init__(self, subflow: Subflow):
         config_ctx = ConfigContext.get()
         interface = config_ctx.network_interface
 
         super().__init__(
             listen=f"tcp://{interface}:0",
             msg_default=_msg_default,
             msg_ext_hook=_msg_ext_hook,
         )
 
-        self.flow = flow
+        self.flow = subflow.flow
+        self.subflow = subflow
         self.config_ctx = config_ctx
         self.run_id = uuid.uuid4().hex[:20]
 
         self.stages = list(self.flow.stages.values())
         self.tasks = list(self.flow.tasks)
         self.stages.sort(key=lambda s: s.id)
         self.tasks.sort(key=lambda t: t.id)
 
         num_stages = len(self.stages)
 
         # STATE
         self.ref_count = [0] * num_stages
+        self.task_state = [FinalTaskState.UNKNOWN] * len(self.tasks)
         self.stage_state = [StageState.UNINITIALIZED] * num_stages
 
         self.table_names = [set() for _ in range(num_stages)]
         self.blob_names = [set() for _ in range(num_stages)]
 
         self.task_memo: defaultdict[Any, Any] = defaultdict(lambda: MemoState.NONE)
 
@@ -380,22 +381,20 @@
             stage_id, DeferredTableStoreOp.Condition.ON_STAGE_ABORT
         )
         self._await_deferred_ts_ops(stage_id)
 
     # TASK
 
     def did_finish_task(self, task_id: int, final_state_value: int):
-        # TODO: Do something with the final state.
-        #       For example: The object returned by flow.run could have a list
-        #       of tasks and their final states.
-        _final_state = FinalTaskState(final_state_value)
+        final_state = FinalTaskState(final_state_value)
         task = self.tasks[task_id]
 
-        stages_to_release = []
+        self.task_state[task_id] = final_state
 
+        stages_to_release = []
         with self.ref_count_lock:
             for stage in task.upstream_stages:
                 self.ref_count[stage.id] -= 1
                 rc = self.ref_count[stage.id]
 
                 if rc == 0:
                     stages_to_release.append(stage)
@@ -406,14 +405,17 @@
                         stage=stage,
                     )
 
         if not self.keep_stages_locked:
             for stage in stages_to_release:
                 self.lock_manager.release(stage)
 
+    def get_task_states(self) -> list[int]:
+        return [state.value for state in self.task_state]
+
     def enter_task_memo(self, task_id: int, cache_key: str) -> tuple[bool, Any]:
         task = self.tasks[task_id]
         memo_key = (task.stage.id, cache_key)
 
         with self.task_memo_lock:
             memo = self.task_memo[memo_key]
             if memo is MemoState.NONE:
@@ -590,14 +592,18 @@
         return self._request("set_stage_has_changed", stage.id)
 
     # TASK
 
     def did_finish_task(self, task: Task, final_state: FinalTaskState):
         self._request("did_finish_task", task.id, final_state.value)
 
+    def get_task_states(self) -> dict[Task, FinalTaskState]:
+        states = [FinalTaskState(value) for value in self._request("get_task_states")]
+        return {task: states[task.id] for task in self.flow.tasks}
+
     @contextmanager
     def task_memo(self, task: Task, cache_key: str):
         success, memo = self._request("enter_task_memo", task.id, cache_key)
 
         try:
             yield success, memo
         except Exception as e:
@@ -736,16 +742,23 @@
     FAILED = 127
 
 
 class FinalTaskState(Enum):
     UNKNOWN = 0
 
     COMPLETED = 1
-    FAILED = 2
-    SKIPPED = 3
+    CACHE_VALID = 2
+    FAILED = 10
+    SKIPPED = 20
+
+    def is_successful(self) -> bool:
+        return self in (FinalTaskState.COMPLETED, FinalTaskState.CACHE_VALID)
+
+    def is_failure(self) -> bool:
+        return self in (FinalTaskState.FAILED,)
 
 
 class MemoState(Enum):
     NONE = 0
     WAITING = 1
 
     FAILED = 127
```

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/core/config.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/core/config.py`

 * *Files identical despite different names*

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/core/stage.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/core/stage.py`

 * *Files identical despite different names*

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/core/task.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/core/task.py`

 * *Files 12% similar despite different names*

```diff
@@ -6,14 +6,15 @@
 
 import structlog
 
 from pydiverse.pipedag.context import ConfigContext, DAGContext, RunContext, TaskContext
 from pydiverse.pipedag.context.run_context import FinalTaskState
 from pydiverse.pipedag.errors import FlowError, StageError
 from pydiverse.pipedag.util import deep_map
+from pydiverse.pipedag.util.hashing import stable_hash
 
 if TYPE_CHECKING:
     from pydiverse.pipedag.core import Flow, Stage
 
 
 class Task:
     """Main building block of flows
@@ -52,14 +53,15 @@
         self.flow: Flow = None  # type: ignore
         self.stage: Stage = None  # type: ignore
         self.upstream_stages: list[Stage] = None  # type: ignore
         self.input_tasks: dict[int, Task] = None  # type: ignore
 
         self._signature = inspect.signature(fn)
         self._bound_args: inspect.BoundArguments = None  # type: ignore
+        self.position_hash: str = None  # type: ignore
 
         self.logger = structlog.get_logger(logger_name=f"Task '{self.name}'", task=self)
         self._visualize_hidden = False
 
     def __repr__(self):
         return f"<Task '{self.name}' {hex(id(self))} (id: {self.id})>"
 
@@ -87,14 +89,15 @@
 
         new = copy.copy(self_)
         new.flow = ctx.flow
         new.stage = ctx.stage
         new.logger = new.logger.bind(logger_name=f"Task '{new.name}'", task=new)
 
         new._bound_args = new._signature.bind(*args, **kwargs)
+        new.position_hash = new.__compute_position_hash()
 
         new.flow.add_task(new)
         new.stage.tasks.append(new)
 
         # Compute input tasks
         new.input_tasks = {}
 
@@ -130,28 +133,31 @@
         if run_context is None:
             run_context = RunContext.get()
         if config_context is None:
             config_context = ConfigContext.get()
 
         with run_context, config_context:
             try:
-                result = self._run(inputs)
+                result, task_context = self._run(inputs)
             except Exception as e:
                 if config_context._swallow_exceptions:
                     # PIPEDAG INTERNAL
                     self.logger.info("Task failed (raised an exception)", cause=str(e))
                 else:
                     self.logger.exception("Task failed (raised an exception)")
                 self.did_finish(FinalTaskState.FAILED)
                 raise e
             else:
-                self.did_finish(FinalTaskState.COMPLETED)
+                if task_context.is_cache_valid:
+                    self.did_finish(FinalTaskState.CACHE_VALID)
+                else:
+                    self.did_finish(FinalTaskState.COMPLETED)
                 return result
 
-    def _run(self, inputs: [int, Any]):
+    def _run(self, inputs: [int, Any]) -> tuple[Any, TaskContext]:
         args = self._bound_args.args
         kwargs = self._bound_args.kwargs
 
         # Because tasks don't contain any state, we must retrieve the value
         # it returned from the inputs dictionary. This is especially important
         # because with multiprocessing it is impossible to even share state.
         def task_result_mapper(x):
@@ -160,21 +166,40 @@
             if isinstance(x, TaskGetItem):
                 return x.resolve_value(inputs[x.task.id])
             return x
 
         args = deep_map(args, task_result_mapper)
         kwargs = deep_map(kwargs, task_result_mapper)
 
-        with TaskContext(task=self):
+        with TaskContext(task=self) as task_context:
             result = self.fn(*args, **kwargs)
 
-        return result
+        return result, task_context
+
+    def __compute_position_hash(self) -> str:
+        """
+        The position hash encodes the position & wiring of a task within a flow.
+        If two tasks have the same position hash, this means that their inputs are
+        derived in the same way.
+        """
+
+        from pydiverse.pipedag.util.json import PipedagJSONEncoder
+
+        def visitor(x):
+            if isinstance(x, (Task, TaskGetItem)):
+                return x.position_hash
+            return x
+
+        arguments = deep_map(self._bound_args.arguments, visitor)
+        input_json = PipedagJSONEncoder().encode(arguments)
+
+        return stable_hash("POS_TASK", self.name, self.stage.name, input_json)
 
     def did_finish(self, state: FinalTaskState):
-        if state == FinalTaskState.COMPLETED:
+        if state.is_successful():
             self.logger.info("Task finished successfully", state=state)
         RunContext.get().did_finish_task(self, state)
 
     def resolve_value(self, task_value: Any):
         return task_value
 
 
@@ -184,14 +209,18 @@
     """
 
     def __init__(self, task: Task, parent: Task | TaskGetItem, item: Any):
         self.task = task
         self.parent = parent
         self.item = item
 
+        self.position_hash = stable_hash(
+            "POS_GET_ITEM", parent.position_hash, repr(self.item)
+        )
+
     def __getitem__(self, item):
         return TaskGetItem(self.task, self, item)
 
     def resolve_value(self, task_value: Any):
         parent_value = self.parent.resolve_value(task_value)
         if parent_value is None:
             raise TypeError(f"Parent ({self.parent}) value is None.")
```

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/engine/base.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/engine/base.py`

 * *Files 19% similar despite different names*

```diff
@@ -2,22 +2,22 @@
 
 from abc import ABC, abstractmethod
 from typing import TYPE_CHECKING
 
 from pydiverse.pipedag.util import Disposable
 
 if TYPE_CHECKING:
-    from pydiverse.pipedag.core import Flow, Result
+    from pydiverse.pipedag.core import Result, Subflow
 
 
 class OrchestrationEngine(Disposable, ABC):
     """Flow orchestration engine base class"""
 
     @abstractmethod
-    def run(self, flow: Flow, **kwargs) -> Result:
+    def run(self, flow: Subflow, **kwargs) -> Result:
         """Execute a flow
 
         :param flow: the pipedag flow to execute
         :param kwargs: Optional keyword arguments. How they get used is
             engine specific.
         :return: A result instance wrapping the flow execution result.
         """
```

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/engine/dask.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/engine/dask.py`

 * *Files 20% similar despite different names*

```diff
@@ -8,15 +8,15 @@
 
 from pydiverse.pipedag.context import ConfigContext, RunContext
 from pydiverse.pipedag.core import Result
 from pydiverse.pipedag.engine.base import OrchestrationEngine
 from pydiverse.pipedag.util import requires
 
 if TYPE_CHECKING:
-    from pydiverse.pipedag.core import Flow, Task
+    from pydiverse.pipedag.core import Subflow, Task
 
 try:
     import dask
 except ImportError as e:
     warnings.warn(str(e), ImportWarning)
     dask = None
 
@@ -33,16 +33,15 @@
             # Scheduler kwargs
             num_workers=None,
             chunksize=1,
         )
 
         self.dask_compute_kwargs.update(dask_compute_kwargs)
 
-    def run(self, flow: Flow, **run_kwargs):
-        g = flow.explicit_graph
+    def run(self, flow: Subflow, **run_kwargs):
         run_context = RunContext.get()
         config_context = ConfigContext.get()
 
         results = {}
         exception = None
 
         def bind_run(t: Task):
@@ -60,18 +59,18 @@
 
                 with structlog.contextvars.bound_contextvars(**structlog_context):
                     return t.run(**kwargs)
 
             run.__name__ = t.name
             return dask.delayed(run, pure=False)
 
-        for task in flow.tasks:
+        for task in flow.get_tasks():
             results[task] = bind_run(task)(
                 parent_futures=[
-                    results[parent_task] for parent_task, _ in g.in_edges(task)
+                    results[parent] for parent in flow.get_parent_tasks(task)
                 ],
                 inputs={
                     in_id: results[in_t] for in_id, in_t in task.input_tasks.items()
                 },
                 run_context=run_context,
                 config_context=config_context,
             )
@@ -79,14 +78,14 @@
         try:
             results = dask.compute(results, **self.dask_compute_kwargs)[0]
         except Exception as e:
             if run_kwargs.get("fail_fast", False):
                 raise e
             exception = e
 
-        return Result(
+        return Result.init_from(
+            subflow=flow,
             underlying=results,
             successful=(exception is None),
-            config_context=config_context,
             task_values=results,
             exception=exception,
         )
```

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/engine/prefect.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/engine/prefect.py`

 * *Files 7% similar despite different names*

```diff
@@ -9,15 +9,15 @@
 
 from pydiverse.pipedag.context import ConfigContext, RunContext
 from pydiverse.pipedag.core.result import Result
 from pydiverse.pipedag.engine.base import OrchestrationEngine
 from pydiverse.pipedag.util import requires
 
 if TYPE_CHECKING:
-    from pydiverse.pipedag.core import Flow, Task
+    from pydiverse.pipedag.core import Subflow, Task
 
 try:
     import prefect
 
     prefect_version = Version(prefect.__version__)
 except ImportError as e:
     warnings.warn(str(e), ImportWarning)
@@ -34,28 +34,27 @@
 class PrefectOneEngine(OrchestrationEngine):
     """Flow execution engine using prefect version 1.x"""
 
     def __init__(self, flow_kwargs: dict[str, Any] = None):
         self.flow_kwargs = flow_kwargs or {}
         self.logger = structlog.get_logger(stage=self)
 
-    def construct_prefect_flow(self, f: Flow):
-        g = f.explicit_graph
+    def construct_prefect_flow(self, f: Subflow):
         run_context = RunContext.get()
         config_context = ConfigContext.get()
 
         flow_kwargs = {
             "name": f.name,
             **self.flow_kwargs,
         }
 
         flow = prefect.Flow(**flow_kwargs)
         tasks: dict[Task, prefect.Task] = {}
 
-        for t in f.tasks:
+        for t in f.get_tasks():
             task = prefect.task(name=t.name)(t.run)
             tasks[t] = task
 
             flow.add_task(task)
             flow.set_dependencies(
                 task,
                 keyword_tasks=dict(
@@ -63,26 +62,27 @@
                         in_id: tasks[in_t] for in_id, in_t in t.input_tasks.items()
                     },
                     run_context=run_context,
                     config_context=config_context,
                 ),
             )
 
-        for u, v in g.edges:
-            flow.add_edge(tasks[u], tasks[v])
+        for task in f.get_tasks():
+            for parent in f.get_parent_tasks(task):
+                flow.add_edge(tasks[parent], tasks[task])
 
         project_name = config_context.pipedag_name + "-" + config_context.instance_id
         try:
             flow.register(project_name=project_name)
         except ValueError as _e:
             self.logger.warning(f"Please make sure project {project_name} exists: {_e}")
 
         return flow, tasks
 
-    def run(self, flow: Flow, **run_kwargs):
+    def run(self, flow: Subflow, **run_kwargs):
         prefect_flow, tasks_map = self.construct_prefect_flow(flow)
         result = prefect_flow.run(**run_kwargs)
 
         # Compute task_values
         task_values = {}
         for task, prefect_task in tasks_map.items():
             task_values[task] = result.result[prefect_task].result
@@ -96,18 +96,18 @@
                     break
             else:
                 # Generic Fallback
                 exception = Exception(
                     f"Prefect run failed with message: {result.message}"
                 )
 
-        return Result(
+        return Result.init_from(
+            subflow=flow,
             underlying=result,
             successful=result.is_successful(),
-            config_context=ConfigContext.get(),
             task_values=task_values,
             exception=exception,
         )
 
 
 @requires(prefect, ImportError("Module 'prefect' not installed"))
 @requires(
@@ -116,52 +116,51 @@
 )
 class PrefectTwoEngine(OrchestrationEngine):
     """Flow execution engine using prefect version 2.x"""
 
     def __init__(self, flow_kwargs: dict[str, Any] = None):
         self.flow_kwargs = flow_kwargs or {}
 
-    def construct_prefect_flow(self, f: Flow):
+    def construct_prefect_flow(self, f: Subflow):
         from pydiverse.pipedag.materialize.core import MaterializingTask
 
-        g = f.explicit_graph
         run_context = RunContext.get()
         config_context = ConfigContext.get()
 
         flow_kwargs = {
             "name": f.name,
             "validate_parameters": False,
             **self.flow_kwargs,
         }
 
         @prefect.flow(**flow_kwargs)
         def pipedag_flow():
             futures: dict[Task, prefect.futures.PrefectFuture] = {}
 
-            for t in f.tasks:
+            for t in f.get_tasks():
                 task_kwargs = {"name": t.name}
                 if isinstance(t, MaterializingTask):
                     task_kwargs["version"] = t.version
 
                 task = prefect.task(**task_kwargs)(t.run)
 
-                parents = [futures[p] for p, _ in g.in_edges(t)]
+                parents = [futures[p] for p in f.get_parent_tasks(t)]
                 inputs = {in_id: futures[in_t] for in_id, in_t in t.input_tasks.items()}
                 futures[t] = task.submit(
                     inputs=inputs,
                     run_context=run_context,
                     config_context=config_context,
                     wait_for=parents,
                 )
 
             return futures
 
         return pipedag_flow
 
-    def run(self, flow: Flow, **kwargs):
+    def run(self, flow: Subflow, **kwargs):
         if kwargs:
             raise TypeError(f"{type(self).__name__}.run doesn't take kwargs.")
         prefect_flow = self.construct_prefect_flow(flow)
         result = prefect_flow(return_state=True)
 
         # Compute task_values
         task_values = {}
@@ -174,18 +173,18 @@
         exception = None
         if not successful:
             for state in result.data.values():
                 if state.is_failed() or state.is_crashed():
                     exception = prefect.states.get_state_exception(state)
                     break
 
-        return Result(
+        return Result.init_from(
+            subflow=flow,
             underlying=result,
             successful=successful,
-            config_context=ConfigContext.get(),
             task_values=result,
             exception=exception,
         )
 
 
 # Automatic Prefect Version Selection
```

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/engine/sequential.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/engine/sequential.py`

 * *Files 20% similar despite different names*

```diff
@@ -3,46 +3,48 @@
 from typing import TYPE_CHECKING
 
 from pydiverse.pipedag.context import ConfigContext, RunContext
 from pydiverse.pipedag.core.result import Result
 from pydiverse.pipedag.engine.base import OrchestrationEngine
 
 if TYPE_CHECKING:
-    from pydiverse.pipedag.core import Flow
+    from pydiverse.pipedag.core import Subflow
 
 
 class SequentialEngine(OrchestrationEngine):
     """Execute flow sequentially
 
     This engine executes all tasks in a flow sequentially in the order
     that they were defined in.
     """
 
-    def run(self, flow: Flow, **run_kwargs):
+    def run(self, flow: Subflow, **run_kwargs):
         run_context = RunContext.get()
         config_context = ConfigContext.get()
 
         results = {}
         exception = None
 
         try:
-            for task in flow.tasks:
+            for task in flow.get_tasks():
                 results[task] = task.run(
                     inputs={
-                        in_id: results[in_t] for in_id, in_t in task.input_tasks.items()
+                        in_id: results[in_t]
+                        for in_id, in_t in task.input_tasks.items()
+                        if in_t in results
                     },
                     run_context=run_context,
                     config_context=config_context,
                 )
 
         except Exception as e:
             if run_kwargs.get("fail_fast", False):
                 raise e
             exception = e
 
-        return Result(
+        return Result.init_from(
+            subflow=flow,
             underlying=results,
             successful=(exception is None),
-            config_context=ConfigContext.get(),
             task_values=results,
             exception=exception,
         )
```

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/errors/__init__.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/errors/__init__.py`

 * *Files identical despite different names*

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/materialize/cache.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/materialize/cache.py`

 * *Files 2% similar despite different names*

```diff
@@ -10,15 +10,15 @@
 from pydiverse.pipedag.errors import CacheError
 from pydiverse.pipedag.materialize.container import RawSql
 from pydiverse.pipedag.materialize.metadata import (
     LazyTableMetadata,
     RawSqlMetadata,
     TaskMetadata,
 )
-from pydiverse.pipedag.materialize.util import compute_cache_key
+from pydiverse.pipedag.util.hashing import stable_hash
 
 if TYPE_CHECKING:
     from pydiverse.pipedag import Stage, Table
     from pydiverse.pipedag.backend import BaseTableStore
     from pydiverse.pipedag.materialize.core import MaterializingTask
 
 
@@ -53,14 +53,15 @@
         ctx = RunContext.get()
         metadata = TaskMetadata(
             name=self._task.name,
             stage=stage.name,
             version=self._task.version,
             timestamp=datetime.now(),
             run_id=ctx.run_id,
+            position_hash=self._task.position_hash,
             input_hash=self._input_hash,
             cache_fn_hash=self._cache_fn_hash,
             output_json=output_json,
         )
         table_store.store_task_metadata(metadata, stage)
 
 
@@ -227,22 +228,22 @@
         :param input_hash: hash used for checking whether task is cache invalid due
             to changing input.
         :param cache_fn_hash: same as input_hash but for external inputs which need
             manual cache invalidation function.
         :return: The hash / cache key (str).
         """
 
-        return compute_cache_key(
+        return stable_hash(
             "TASK",
             task.name,
             task.version,
             input_hash,
             cache_fn_hash,
         )
 
     @staticmethod
     def lazy_table_cache_key(task_hash: str, query_hash: str):
-        return compute_cache_key(
+        return stable_hash(
             "LAZY_TABLE",
             task_hash,
             query_hash,
         )
```

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/materialize/container.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/materialize/container.py`

 * *Files identical despite different names*

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/materialize/core.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/materialize/core.py`

 * *Files 16% similar despite different names*

```diff
@@ -1,32 +1,33 @@
 from __future__ import annotations
 
 import functools
 import inspect
 from dataclasses import dataclass
 from functools import partial
-from typing import TYPE_CHECKING, Callable
+from typing import TYPE_CHECKING, Any, Callable
 
 from pydiverse.pipedag._typing import CallableT
 from pydiverse.pipedag.context import ConfigContext, RunContext, TaskContext
 from pydiverse.pipedag.core.task import Task
+from pydiverse.pipedag.errors import CacheError
 from pydiverse.pipedag.materialize.cache import CacheManager, TaskCacheInfo
 from pydiverse.pipedag.materialize.container import Blob, Table
-from pydiverse.pipedag.materialize.util import compute_cache_key
 from pydiverse.pipedag.util import deep_map
+from pydiverse.pipedag.util.hashing import stable_hash
 
 if TYPE_CHECKING:
     from pydiverse.pipedag import Stage
 
 
 def materialize(
     fn: CallableT = None,
     *,
     name: str = None,
-    input_type: type = None,
+    input_type: type | tuple | dict[str, Any] = None,
     version: str = None,
     cache: Callable = None,
     lazy: bool = False,
     nout: int = 1,
 ) -> CallableT | MaterializingTask:
     if fn is None:
         return partial(
@@ -112,14 +113,53 @@
         )
 
         self.input_type = input_type
         self.version = version
         self.cache = cache
         self.lazy = lazy
 
+    def run(self, inputs: dict[int, Any], **kwargs):
+        # When running only a subset of an entire flow, not all inputs
+        # get calculated during flow execution. As a consequence, we must load
+        # those inputs from the cache.
+
+        for in_id, in_task in self.input_tasks.items():
+            if in_id in inputs:
+                continue
+
+            # This returns all metadata objects with the same name, stage, AND position
+            # hash as `in_task`. We utilize the position hash to identify a specific
+            # task instance, if the same task appears multiple times in a stage.
+            store = ConfigContext.get().store
+            metadata = store.table_store.retrieve_all_task_metadata(in_task)
+
+            if not metadata:
+                raise CacheError(
+                    f"Couldn't find cached output for task {in_task}"
+                    " with matching position hash."
+                )
+
+            output_json = {m.output_json for m in metadata}
+            if len(output_json) > 1:
+                raise RuntimeError(
+                    f"Found multiple matching cached versions of task '{in_task.name}'"
+                    f" in stage '{in_task.stage}' with different outputs."
+                    f" Couldn't determine which one to use for loading"
+                    f" inputs for task {self}."
+                )
+
+            # Choose newest entry
+            metadata = sorted(metadata, key=lambda m: m.timestamp)[-1]
+            cached_output = store.json_decode(metadata.output_json)
+
+            # Load inputs from database
+            inputs[in_id] = cached_output
+
+        return super().run(inputs, **kwargs)
+
 
 @dataclass
 class TaskInfo:
     task_cache_info: TaskCacheInfo
     input_tables: list[Table]
     open_stages: set[Stage]
 
@@ -161,20 +201,20 @@
         outer_stage = task.stage.outer_stage
         while outer_stage is not None:
             open_stages.add(outer_stage)
             outer_stage = outer_stage.outer_stage
 
         # Compute the cache key for the task inputs
         input_json = store.json_encode(bound.arguments)
-        input_hash = compute_cache_key("INPUT", input_json)
+        input_hash = stable_hash("INPUT", input_json)
 
         cache_fn_hash = ""
         if task.cache is not None:
             cache_fn_output = store.json_encode(task.cache(*args, **kwargs))
-            cache_fn_hash = compute_cache_key("CACHE_FN", cache_fn_output)
+            cache_fn_hash = stable_hash("CACHE_FN", cache_fn_output)
 
         memo_cache_key = CacheManager.task_cache_key(task, input_hash, cache_fn_hash)
 
         # Check if this task has already been run with the same inputs
         # If yes, return memoized result. This prevents DuplicateNameExceptions
         ctx = RunContext.get()
         with ctx.task_memo(task, memo_cache_key) as (success, memo):
@@ -187,20 +227,25 @@
                 return memo
 
             task_cache_info = CacheManager.cache_lookup(
                 store, task, input_hash, cache_fn_hash
             )
             if not task.lazy:
                 ctx = RunContext.get()
+                TaskContext.get().is_cache_valid = task_cache_info.is_cache_valid()
                 if task_cache_info.is_cache_valid():
                     ctx.store_task_memo(
                         task, memo_cache_key, task_cache_info.get_cached_output()
                     )
                     # Task isn't lazy -> copy cache to transaction stage
                     return task_cache_info.get_cached_output()
+            else:
+                # For lazy tasks, is_cache_valid gets set to false during the
+                # store.materialize_task procedure
+                TaskContext.get().is_cache_valid = True
 
             # Not found in cache / lazy -> Evaluate Function
             args, kwargs, input_tables = store.dematerialize_task_inputs(
                 task, bound.args, bound.kwargs
             )
 
             result = self.fn(*args, **kwargs)
```

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/materialize/metadata.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/materialize/metadata.py`

 * *Files 4% similar despite different names*

```diff
@@ -15,14 +15,15 @@
     """
 
     name: str
     stage: str
     version: str | None
     timestamp: datetime.datetime
     run_id: str
+    position_hash: str
     input_hash: str
     cache_fn_hash: str
     output_json: str
 
 
 @dataclass
 class LazyTableMetadata:
```

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/materialize/store.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/materialize/store.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,25 +1,23 @@
 from __future__ import annotations
 
 import itertools
-import json
 from typing import Any, Callable
 
 import structlog
 
 from pydiverse.pipedag import Blob, Stage, Table, backend
 from pydiverse.pipedag._typing import Materializable, T
 from pydiverse.pipedag.context import ConfigContext, RunContext
 from pydiverse.pipedag.context.run_context import StageState
 from pydiverse.pipedag.core.config import PipedagConfig
 from pydiverse.pipedag.errors import DuplicateNameError, StageError
 from pydiverse.pipedag.materialize.container import RawSql
 from pydiverse.pipedag.materialize.core import MaterializingTask, TaskInfo
 from pydiverse.pipedag.materialize.metadata import TaskMetadata
-from pydiverse.pipedag.materialize.util import json as json_util
 from pydiverse.pipedag.util import Disposable, deep_map
 from pydiverse.pipedag.util.naming import NameDisambiguator
 
 
 class PipeDAGStore(Disposable):
     """Main storage interface for materializing tasks
 
@@ -38,22 +36,19 @@
         local_table_cache: backend.table_cache.LocalTableCache,
     ):
         self.table_store = table
         self.blob_store = blob
         self.local_table_cache = local_table_cache
 
         self.logger = structlog.get_logger()
-        self.json_encoder = json.JSONEncoder(
-            ensure_ascii=False,
-            allow_nan=False,
-            separators=(",", ":"),
-            sort_keys=True,
-            default=json_util.json_default,
-        )
-        self.json_decoder = json.JSONDecoder(object_hook=json_util.json_object_hook)
+
+        from pydiverse.pipedag.util.json import PipedagJSONDecoder, PipedagJSONEncoder
+
+        self.json_encoder = PipedagJSONEncoder()
+        self.json_decoder = PipedagJSONDecoder()
 
     def dispose(self):
         """
         Clean up and close all open resources.
 
         Don't use the store object any more after disposal!
         """
```

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/materialize/util/cache.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/util/hashing.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 import base64
 import hashlib
 
 
-def compute_cache_key(*args: str) -> str:
-    """Compute a cache key given some inputs
+def stable_hash(*args: str) -> str:
+    """Compute a hash over a set of strings
 
     :param args: Some strings from which to compute the cache key
     :return: A sha256 base32 digest, trimmed to 20 char length
     """
 
     combined_hash = hashlib.sha256(b"PIPEDAG")
     for arg in args:
@@ -15,15 +15,15 @@
         arg_bytes_len = len(arg_bytes).to_bytes(length=8, byteorder="big")
 
         combined_hash.update(arg_bytes_len)
         combined_hash.update(arg_bytes)
 
     # Only take first 20 characters of base32 digest (100 bits). This
     # provides 50 bits of collision resistance, which is more than enough.
-    # To illustrate: If you were to generate 1k cache keys per second,
+    # To illustrate: If you were to generate 1k hashes per second,
     # you still would have to wait over 800k years until you encounter
     # a collision.
 
     # NOTE: Can't use base64 because it contains lower and upper case
     #       letters; identifiers in pipedag are all lowercase
     hash_digest = combined_hash.digest()
     hash_str = base64.b32encode(hash_digest).decode("ascii").lower()
```

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/util/deep_map.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/util/deep_map.py`

 * *Files identical despite different names*

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/util/deep_merge.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/util/deep_merge.py`

 * *Files identical despite different names*

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/util/disposable.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/util/disposable.py`

 * *Files identical despite different names*

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/util/import_.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/util/import_.py`

 * *Files identical despite different names*

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/util/ipc.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/util/ipc.py`

 * *Files identical despite different names*

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/util/naming.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/util/naming.py`

 * *Files identical despite different names*

### Comparing `pydiverse_pipedag-0.4.1/src/pydiverse/pipedag/util/structlog.py` & `pydiverse_pipedag-0.5.0/src/pydiverse/pipedag/util/structlog.py`

 * *Files identical despite different names*

### Comparing `pydiverse_pipedag-0.4.1/PKG-INFO` & `pydiverse_pipedag-0.5.0/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pydiverse-pipedag
-Version: 0.4.1
+Version: 0.5.0
 Summary: A pipeline orchestration library executing tasks within one python session. It takes care of SQL table (de)materialization, caching and cache invalidation. Blob storage is supported as well for example for storing model files.
 License: BSD-3-Clause
 Author: QuantCo, Inc.
 Requires-Python: >=3.9,<4.0
 Classifier: Development Status :: 3 - Alpha
 Classifier: Intended Audience :: Developers
 Classifier: Intended Audience :: Science/Research
@@ -17,23 +17,25 @@
 Classifier: Topic :: Database
 Provides-Extra: dask
 Provides-Extra: filelock
 Provides-Extra: zookeeper
 Requires-Dist: PyYAML (>=6.0)
 Requires-Dist: SQLAlchemy (>=1.4.39)
 Requires-Dist: attrs (>=22.1.0)
+Requires-Dist: click (>=8.1.3,<9.0.0)
 Requires-Dist: cryptography (>=41.0.1)
 Requires-Dist: dask (>=2022.1.0) ; extra == "dask"
 Requires-Dist: filelock (>=3.7.1) ; extra == "filelock"
 Requires-Dist: kazoo (>=2.8.0) ; extra == "zookeeper"
 Requires-Dist: msgpack (>=1.0.4)
 Requires-Dist: networkx (>=2.8)
 Requires-Dist: packaging (>=21.3)
 Requires-Dist: pandas (>=1.4.3)
 Requires-Dist: pyarrow (>=11.0.0)
+Requires-Dist: pydot (>=1.4.2)
 Requires-Dist: pynng (>=0.7.1)
 Requires-Dist: python-box (>=6.1.0)
 Requires-Dist: structlog (>=22.1.0)
 Requires-Dist: typing-extensions (>=4.1.0,<5.0.0)
 Description-Content-Type: text/markdown
 
 # pydiverse.pipedag
```


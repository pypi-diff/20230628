# Comparing `tmp/redshift_client-2.0.0.tar.gz` & `tmp/redshift_client-3.0.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "redshift_client-2.0.0.tar", last modified: Tue Jan  1 00:00:00 1980, max compression
+gzip compressed data, was "redshift_client-3.0.0.tar", last modified: Tue Jan  1 00:00:00 1980, max compression
```

## Comparing `redshift_client-2.0.0.tar` & `redshift_client-3.0.0.tar`

### file list

```diff
@@ -1,58 +1,58 @@
--rw-r--r--   0        0        0       83 1980-01-01 00:00:00.000000 redshift_client-2.0.0/.envrc
--rw-r--r--   0        0        0       47 1980-01-01 00:00:00.000000 redshift_client-2.0.0/.gitignore
--rw-r--r--   0        0        0     2106 1980-01-01 00:00:00.000000 redshift_client-2.0.0/.gitlab-ci.yml
--rw-r--r--   0        0        0      262 1980-01-01 00:00:00.000000 redshift_client-2.0.0/build/ci/check.nix
--rw-r--r--   0        0        0      191 1980-01-01 00:00:00.000000 redshift_client-2.0.0/build/ci/utils.sh
--rw-r--r--   0        0        0      780 1980-01-01 00:00:00.000000 redshift_client-2.0.0/build/default.nix
--rw-r--r--   0        0        0      984 1980-01-01 00:00:00.000000 redshift_client-2.0.0/build/deps/default.nix
--rw-r--r--   0        0        0      217 1980-01-01 00:00:00.000000 redshift_client-2.0.0/build/deps/deprecated/stubs.nix
--rw-r--r--   0        0        0      251 1980-01-01 00:00:00.000000 redshift_client-2.0.0/build/deps/networkx.nix
--rw-r--r--   0        0        0     1368 1980-01-01 00:00:00.000000 redshift_client-2.0.0/build/deps/override_utils.nix
--rw-r--r--   0        0        0      202 1980-01-01 00:00:00.000000 redshift_client-2.0.0/build/deps/psycopg2/stubs.nix
--rw-r--r--   0        0        0      182 1980-01-01 00:00:00.000000 redshift_client-2.0.0/build/dev_env/default.nix
--rwxr-xr-x   0        0        0      131 1980-01-01 00:00:00.000000 redshift_client-2.0.0/build/dev_env/hook.sh
--rw-r--r--   0        0        0     1482 1980-01-01 00:00:00.000000 redshift_client-2.0.0/build/dev_env/vs_settings.py
--rw-r--r--   0        0        0      210 1980-01-01 00:00:00.000000 redshift_client-2.0.0/build/generic_builder/check.nix
--rw-r--r--   0        0        0      341 1980-01-01 00:00:00.000000 redshift_client-2.0.0/build/generic_builder/default.nix
--rw-r--r--   0        0        0      245 1980-01-01 00:00:00.000000 redshift_client-2.0.0/build/generic_builder/env.nix
--rw-r--r--   0        0        0      309 1980-01-01 00:00:00.000000 redshift_client-2.0.0/build/generic_builder/metadata.nix
--rwxr-xr-x   0        0        0      127 1980-01-01 00:00:00.000000 redshift_client-2.0.0/build/generic_builder/pkg/check/tests.sh
--rwxr-xr-x   0        0        0      160 1980-01-01 00:00:00.000000 redshift_client-2.0.0/build/generic_builder/pkg/check/types.sh
--rw-r--r--   0        0        0      625 1980-01-01 00:00:00.000000 redshift_client-2.0.0/build/generic_builder/pkg/default.nix
--rw-r--r--   0        0        0     3034 1980-01-01 00:00:00.000000 redshift_client-2.0.0/flake.lock
--rw-r--r--   0        0        0     1672 1980-01-01 00:00:00.000000 redshift_client-2.0.0/flake.nix
--rw-r--r--   0        0        0      122 1980-01-01 00:00:00.000000 redshift_client-2.0.0/makes.lock.nix
--rw-r--r--   0        0        0      674 1980-01-01 00:00:00.000000 redshift_client-2.0.0/makes.nix
--rw-r--r--   0        0        0      714 1980-01-01 00:00:00.000000 redshift_client-2.0.0/mypy.ini
--rw-r--r--   0        0        0      260 1980-01-01 00:00:00.000000 redshift_client-2.0.0/nix.conf
--rw-r--r--   0        0        0      514 1980-01-01 00:00:00.000000 redshift_client-2.0.0/pyproject.toml
--rw-r--r--   0        0        0       22 1980-01-01 00:00:00.000000 redshift_client-2.0.0/redshift_client/__init__.py
--rw-r--r--   0        0        0       82 1980-01-01 00:00:00.000000 redshift_client-2.0.0/redshift_client/client/__init__.py
--rw-r--r--   0        0        0     7120 1980-01-01 00:00:00.000000 redshift_client-2.0.0/redshift_client/client/schema.py
--rw-r--r--   0        0        0    10682 1980-01-01 00:00:00.000000 redshift_client-2.0.0/redshift_client/client/table/__init__.py
--rw-r--r--   0        0        0     1575 1980-01-01 00:00:00.000000 redshift_client-2.0.0/redshift_client/client/table/_assert.py
--rw-r--r--   0        0        0      283 1980-01-01 00:00:00.000000 redshift_client-2.0.0/redshift_client/client/table/_encode.py
--rw-r--r--   0        0        0     1925 1980-01-01 00:00:00.000000 redshift_client-2.0.0/redshift_client/client/table/_new.py
--rw-r--r--   0        0        0        0 1980-01-01 00:00:00.000000 redshift_client-2.0.0/redshift_client/core/__init__.py
--rw-r--r--   0        0        0      508 1980-01-01 00:00:00.000000 redshift_client-2.0.0/redshift_client/core/column.py
--rw-r--r--   0        0        0        0 1980-01-01 00:00:00.000000 redshift_client-2.0.0/redshift_client/core/data_type/__init__.py
--rw-r--r--   0        0        0     1589 1980-01-01 00:00:00.000000 redshift_client-2.0.0/redshift_client/core/data_type/alias.py
--rw-r--r--   0        0        0     1585 1980-01-01 00:00:00.000000 redshift_client-2.0.0/redshift_client/core/data_type/core.py
--rw-r--r--   0        0        0     1565 1980-01-01 00:00:00.000000 redshift_client-2.0.0/redshift_client/core/data_type/decode.py
--rw-r--r--   0        0        0      843 1980-01-01 00:00:00.000000 redshift_client-2.0.0/redshift_client/core/id_objs.py
--rw-r--r--   0        0        0      589 1980-01-01 00:00:00.000000 redshift_client-2.0.0/redshift_client/core/schema.py
--rw-r--r--   0        0        0     5401 1980-01-01 00:00:00.000000 redshift_client-2.0.0/redshift_client/core/table.py
--rw-r--r--   0        0        0        0 1980-01-01 00:00:00.000000 redshift_client-2.0.0/redshift_client/py.typed
--rw-r--r--   0        0        0     4410 1980-01-01 00:00:00.000000 redshift_client-2.0.0/redshift_client/sql_client/__init__.py
--rw-r--r--   0        0        0     1046 1980-01-01 00:00:00.000000 redshift_client-2.0.0/redshift_client/sql_client/_assert.py
--rw-r--r--   0        0        0     2381 1980-01-01 00:00:00.000000 redshift_client-2.0.0/redshift_client/sql_client/connection.py
--rw-r--r--   0        0        0     1534 1980-01-01 00:00:00.000000 redshift_client-2.0.0/redshift_client/sql_client/primitive.py
--rw-r--r--   0        0        0     1236 1980-01-01 00:00:00.000000 redshift_client-2.0.0/redshift_client/sql_client/query.py
--rw-r--r--   0        0        0     1022 1980-01-01 00:00:00.000000 redshift_client-2.0.0/redshift_client/utils.py
--rw-r--r--   0        0        0        0 1980-01-01 00:00:00.000000 redshift_client-2.0.0/tests/__init__.py
--rw-r--r--   0        0        0        0 1980-01-01 00:00:00.000000 redshift_client-2.0.0/tests/arch/__init__.py
--rw-r--r--   0        0        0     1655 1980-01-01 00:00:00.000000 redshift_client-2.0.0/tests/arch/arch.py
--rw-r--r--   0        0        0     1055 1980-01-01 00:00:00.000000 redshift_client-2.0.0/tests/arch/test_arch.py
--rw-r--r--   0        0        0        0 1980-01-01 00:00:00.000000 redshift_client-2.0.0/tests/py.typed
--rw-r--r--   0        0        0      233 1980-01-01 00:00:00.000000 redshift_client-2.0.0/tests/test_column.py
--rw-r--r--   0        0        0      394 1970-01-01 00:00:00.000000 redshift_client-2.0.0/PKG-INFO
+-rw-r--r--   0        0        0       83 1980-01-01 00:00:00.000000 redshift_client-3.0.0/.envrc
+-rw-r--r--   0        0        0       47 1980-01-01 00:00:00.000000 redshift_client-3.0.0/.gitignore
+-rw-r--r--   0        0        0     2106 1980-01-01 00:00:00.000000 redshift_client-3.0.0/.gitlab-ci.yml
+-rw-r--r--   0        0        0      262 1980-01-01 00:00:00.000000 redshift_client-3.0.0/build/ci/check.nix
+-rw-r--r--   0        0        0      191 1980-01-01 00:00:00.000000 redshift_client-3.0.0/build/ci/utils.sh
+-rw-r--r--   0        0        0      780 1980-01-01 00:00:00.000000 redshift_client-3.0.0/build/default.nix
+-rw-r--r--   0        0        0      984 1980-01-01 00:00:00.000000 redshift_client-3.0.0/build/deps/default.nix
+-rw-r--r--   0        0        0      217 1980-01-01 00:00:00.000000 redshift_client-3.0.0/build/deps/deprecated/stubs.nix
+-rw-r--r--   0        0        0      251 1980-01-01 00:00:00.000000 redshift_client-3.0.0/build/deps/networkx.nix
+-rw-r--r--   0        0        0     1368 1980-01-01 00:00:00.000000 redshift_client-3.0.0/build/deps/override_utils.nix
+-rw-r--r--   0        0        0      206 1980-01-01 00:00:00.000000 redshift_client-3.0.0/build/deps/psycopg2/stubs.nix
+-rw-r--r--   0        0        0      182 1980-01-01 00:00:00.000000 redshift_client-3.0.0/build/dev_env/default.nix
+-rwxr-xr-x   0        0        0      131 1980-01-01 00:00:00.000000 redshift_client-3.0.0/build/dev_env/hook.sh
+-rw-r--r--   0        0        0     1482 1980-01-01 00:00:00.000000 redshift_client-3.0.0/build/dev_env/vs_settings.py
+-rw-r--r--   0        0        0      210 1980-01-01 00:00:00.000000 redshift_client-3.0.0/build/generic_builder/check.nix
+-rw-r--r--   0        0        0      341 1980-01-01 00:00:00.000000 redshift_client-3.0.0/build/generic_builder/default.nix
+-rw-r--r--   0        0        0      245 1980-01-01 00:00:00.000000 redshift_client-3.0.0/build/generic_builder/env.nix
+-rw-r--r--   0        0        0      309 1980-01-01 00:00:00.000000 redshift_client-3.0.0/build/generic_builder/metadata.nix
+-rwxr-xr-x   0        0        0      127 1980-01-01 00:00:00.000000 redshift_client-3.0.0/build/generic_builder/pkg/check/tests.sh
+-rwxr-xr-x   0        0        0      160 1980-01-01 00:00:00.000000 redshift_client-3.0.0/build/generic_builder/pkg/check/types.sh
+-rw-r--r--   0        0        0      625 1980-01-01 00:00:00.000000 redshift_client-3.0.0/build/generic_builder/pkg/default.nix
+-rw-r--r--   0        0        0     3034 1980-01-01 00:00:00.000000 redshift_client-3.0.0/flake.lock
+-rw-r--r--   0        0        0     1672 1980-01-01 00:00:00.000000 redshift_client-3.0.0/flake.nix
+-rw-r--r--   0        0        0      122 1980-01-01 00:00:00.000000 redshift_client-3.0.0/makes.lock.nix
+-rw-r--r--   0        0        0      674 1980-01-01 00:00:00.000000 redshift_client-3.0.0/makes.nix
+-rw-r--r--   0        0        0      714 1980-01-01 00:00:00.000000 redshift_client-3.0.0/mypy.ini
+-rw-r--r--   0        0        0      260 1980-01-01 00:00:00.000000 redshift_client-3.0.0/nix.conf
+-rw-r--r--   0        0        0      556 1980-01-01 00:00:00.000000 redshift_client-3.0.0/pyproject.toml
+-rw-r--r--   0        0        0       22 1980-01-01 00:00:00.000000 redshift_client-3.0.0/redshift_client/__init__.py
+-rw-r--r--   0        0        0       82 1980-01-01 00:00:00.000000 redshift_client-3.0.0/redshift_client/client/__init__.py
+-rw-r--r--   0        0        0     7120 1980-01-01 00:00:00.000000 redshift_client-3.0.0/redshift_client/client/schema.py
+-rw-r--r--   0        0        0    10682 1980-01-01 00:00:00.000000 redshift_client-3.0.0/redshift_client/client/table/__init__.py
+-rw-r--r--   0        0        0     1575 1980-01-01 00:00:00.000000 redshift_client-3.0.0/redshift_client/client/table/_assert.py
+-rw-r--r--   0        0        0      283 1980-01-01 00:00:00.000000 redshift_client-3.0.0/redshift_client/client/table/_encode.py
+-rw-r--r--   0        0        0     1925 1980-01-01 00:00:00.000000 redshift_client-3.0.0/redshift_client/client/table/_new.py
+-rw-r--r--   0        0        0        0 1980-01-01 00:00:00.000000 redshift_client-3.0.0/redshift_client/core/__init__.py
+-rw-r--r--   0        0        0      508 1980-01-01 00:00:00.000000 redshift_client-3.0.0/redshift_client/core/column.py
+-rw-r--r--   0        0        0        0 1980-01-01 00:00:00.000000 redshift_client-3.0.0/redshift_client/core/data_type/__init__.py
+-rw-r--r--   0        0        0     1589 1980-01-01 00:00:00.000000 redshift_client-3.0.0/redshift_client/core/data_type/alias.py
+-rw-r--r--   0        0        0     1585 1980-01-01 00:00:00.000000 redshift_client-3.0.0/redshift_client/core/data_type/core.py
+-rw-r--r--   0        0        0     1565 1980-01-01 00:00:00.000000 redshift_client-3.0.0/redshift_client/core/data_type/decode.py
+-rw-r--r--   0        0        0      843 1980-01-01 00:00:00.000000 redshift_client-3.0.0/redshift_client/core/id_objs.py
+-rw-r--r--   0        0        0      589 1980-01-01 00:00:00.000000 redshift_client-3.0.0/redshift_client/core/schema.py
+-rw-r--r--   0        0        0     5401 1980-01-01 00:00:00.000000 redshift_client-3.0.0/redshift_client/core/table.py
+-rw-r--r--   0        0        0        0 1980-01-01 00:00:00.000000 redshift_client-3.0.0/redshift_client/py.typed
+-rw-r--r--   0        0        0     4410 1980-01-01 00:00:00.000000 redshift_client-3.0.0/redshift_client/sql_client/__init__.py
+-rw-r--r--   0        0        0     1046 1980-01-01 00:00:00.000000 redshift_client-3.0.0/redshift_client/sql_client/_assert.py
+-rw-r--r--   0        0        0     3113 1980-01-01 00:00:00.000000 redshift_client-3.0.0/redshift_client/sql_client/connection.py
+-rw-r--r--   0        0        0     1534 1980-01-01 00:00:00.000000 redshift_client-3.0.0/redshift_client/sql_client/primitive.py
+-rw-r--r--   0        0        0     1203 1980-01-01 00:00:00.000000 redshift_client-3.0.0/redshift_client/sql_client/query.py
+-rw-r--r--   0        0        0     1022 1980-01-01 00:00:00.000000 redshift_client-3.0.0/redshift_client/utils.py
+-rw-r--r--   0        0        0        0 1980-01-01 00:00:00.000000 redshift_client-3.0.0/tests/__init__.py
+-rw-r--r--   0        0        0        0 1980-01-01 00:00:00.000000 redshift_client-3.0.0/tests/arch/__init__.py
+-rw-r--r--   0        0        0     1655 1980-01-01 00:00:00.000000 redshift_client-3.0.0/tests/arch/arch.py
+-rw-r--r--   0        0        0     1055 1980-01-01 00:00:00.000000 redshift_client-3.0.0/tests/arch/test_arch.py
+-rw-r--r--   0        0        0        0 1980-01-01 00:00:00.000000 redshift_client-3.0.0/tests/py.typed
+-rw-r--r--   0        0        0      233 1980-01-01 00:00:00.000000 redshift_client-3.0.0/tests/test_column.py
+-rw-r--r--   0        0        0      444 1970-01-01 00:00:00.000000 redshift_client-3.0.0/PKG-INFO
```

### Comparing `redshift_client-2.0.0/.gitlab-ci.yml` & `redshift_client-3.0.0/.gitlab-ci.yml`

 * *Files identical despite different names*

### Comparing `redshift_client-2.0.0/build/default.nix` & `redshift_client-3.0.0/build/default.nix`

 * *Files identical despite different names*

### Comparing `redshift_client-2.0.0/build/deps/default.nix` & `redshift_client-3.0.0/build/deps/default.nix`

 * *Files identical despite different names*

### Comparing `redshift_client-2.0.0/build/deps/override_utils.nix` & `redshift_client-3.0.0/build/deps/override_utils.nix`

 * *Files identical despite different names*

### Comparing `redshift_client-2.0.0/build/dev_env/vs_settings.py` & `redshift_client-3.0.0/build/dev_env/vs_settings.py`

 * *Files identical despite different names*

### Comparing `redshift_client-2.0.0/build/generic_builder/pkg/default.nix` & `redshift_client-3.0.0/build/generic_builder/pkg/default.nix`

 * *Files identical despite different names*

### Comparing `redshift_client-2.0.0/flake.lock` & `redshift_client-3.0.0/flake.lock`

 * *Files identical despite different names*

### Comparing `redshift_client-2.0.0/flake.nix` & `redshift_client-3.0.0/flake.nix`

 * *Files identical despite different names*

### Comparing `redshift_client-2.0.0/makes.nix` & `redshift_client-3.0.0/makes.nix`

 * *Files identical despite different names*

### Comparing `redshift_client-2.0.0/mypy.ini` & `redshift_client-3.0.0/mypy.ini`

 * *Files identical despite different names*

### Comparing `redshift_client-2.0.0/pyproject.toml` & `redshift_client-3.0.0/pyproject.toml`

 * *Files 13% similar despite different names*

```diff
@@ -8,14 +8,15 @@
 ]
 requires-python = ">=3.8"
 dependencies = [
     "Deprecated >=1.2.12, <2.0.0",
     "psycopg2 >=2.8.6, <3.0.0",
     "fa-purity >=1.33.2 , <2.0.0",
     "types-Deprecated >=1.2.1, <2.0.0",
+    "types-psycopg2 >=2.9.21.10, <3.0.0",
 ]
 description = "Redshift client-SDK"
 dynamic = ["version"]
 
 [build-system]
 requires = ["flit_core >=3.2,<4"]
 build-backend = "flit_core.buildapi"
```

### Comparing `redshift_client-2.0.0/redshift_client/client/schema.py` & `redshift_client-3.0.0/redshift_client/client/schema.py`

 * *Files identical despite different names*

### Comparing `redshift_client-2.0.0/redshift_client/client/table/__init__.py` & `redshift_client-3.0.0/redshift_client/client/table/__init__.py`

 * *Files identical despite different names*

### Comparing `redshift_client-2.0.0/redshift_client/client/table/_assert.py` & `redshift_client-3.0.0/redshift_client/client/table/_assert.py`

 * *Files identical despite different names*

### Comparing `redshift_client-2.0.0/redshift_client/client/table/_new.py` & `redshift_client-3.0.0/redshift_client/client/table/_new.py`

 * *Files identical despite different names*

### Comparing `redshift_client-2.0.0/redshift_client/core/data_type/alias.py` & `redshift_client-3.0.0/redshift_client/core/data_type/alias.py`

 * *Files identical despite different names*

### Comparing `redshift_client-2.0.0/redshift_client/core/data_type/core.py` & `redshift_client-3.0.0/redshift_client/core/data_type/core.py`

 * *Files identical despite different names*

### Comparing `redshift_client-2.0.0/redshift_client/core/data_type/decode.py` & `redshift_client-3.0.0/redshift_client/core/data_type/decode.py`

 * *Files identical despite different names*

### Comparing `redshift_client-2.0.0/redshift_client/core/id_objs.py` & `redshift_client-3.0.0/redshift_client/core/id_objs.py`

 * *Files identical despite different names*

### Comparing `redshift_client-2.0.0/redshift_client/core/schema.py` & `redshift_client-3.0.0/redshift_client/core/schema.py`

 * *Files identical despite different names*

### Comparing `redshift_client-2.0.0/redshift_client/core/table.py` & `redshift_client-3.0.0/redshift_client/core/table.py`

 * *Files identical despite different names*

### Comparing `redshift_client-2.0.0/redshift_client/sql_client/__init__.py` & `redshift_client-3.0.0/redshift_client/sql_client/__init__.py`

 * *Files identical despite different names*

### Comparing `redshift_client-2.0.0/redshift_client/sql_client/_assert.py` & `redshift_client-3.0.0/redshift_client/sql_client/_assert.py`

 * *Files identical despite different names*

### Comparing `redshift_client-2.0.0/redshift_client/sql_client/connection.py` & `redshift_client-3.0.0/redshift_client/sql_client/connection.py`

 * *Files 16% similar despite different names*

```diff
@@ -9,31 +9,38 @@
     deprecated,
 )
 from enum import (
     Enum,
 )
 from fa_purity.cmd import (
     Cmd,
+    CmdUnwrapper,
 )
 import psycopg2 as postgres
 import psycopg2.extensions as postgres_extensions
 from typing import (
     Any,
+    Callable,
     cast,
+    NoReturn,
     TYPE_CHECKING,
+    TypeVar,
 )
 
 if TYPE_CHECKING:
     from psycopg2 import (
         connection as ConnectionStub,
     )
 else:
     ConnectionStub = Any
 
 
+_T = TypeVar("_T")
+
+
 @dataclass(frozen=True)
 class DatabaseId:
     db_name: str
     host: str
     port: int
 
 
@@ -43,55 +50,84 @@
     password: str
 
     def __repr__(self) -> str:
         return f"Creds(user={self.user})"
 
 
 class IsolationLvl(Enum):
-    AUTOCOMMIT = postgres_extensions.ISOLATION_LEVEL_AUTOCOMMIT
     READ_UNCOMMITTED = postgres_extensions.ISOLATION_LEVEL_READ_UNCOMMITTED
     READ_COMMITTED = postgres_extensions.ISOLATION_LEVEL_READ_COMMITTED
     REPEATABLE_READ = postgres_extensions.ISOLATION_LEVEL_REPEATABLE_READ
     SERIALIZABLE = postgres_extensions.ISOLATION_LEVEL_SERIALIZABLE
 
 
 @dataclass(frozen=True)
 class _DbConnection:
     _connection: ConnectionStub
 
-
-@dataclass(frozen=True)
-class DbConnection:
-    _inner: _DbConnection
-
-    def close(self) -> Cmd[None]:
-        return Cmd.from_cmd(lambda: cast(None, self._inner._connection.close()))  # type: ignore[no-untyped-call]
-
-    def commit(self) -> Cmd[None]:
-        return Cmd.from_cmd(lambda: cast(None, self._inner._connection.commit()))  # type: ignore[no-untyped-call]
-
     @staticmethod
     def connect(
         db_id: DatabaseId,
         creds: Credentials,
         readonly: bool,
         isolation: IsolationLvl,
-    ) -> Cmd[DbConnection]:
-        def _action() -> DbConnection:
+        autocommit: bool,
+    ) -> Cmd[_DbConnection]:
+        def _action() -> _DbConnection:
             connection = postgres.connect(
                 dbname=db_id.db_name,
                 user=creds.user,
                 password=creds.password,
                 host=db_id.host,
                 port=db_id.port,
             )
-            connection.set_session(readonly=readonly)  # type: ignore[no-untyped-call]
-            connection.set_isolation_level(isolation.value)  # type: ignore[no-untyped-call]
-            draft = _DbConnection(connection)
-            return DbConnection(draft)
+            connection.set_session(
+                isolation_level=isolation.value,
+                readonly=readonly,
+                autocommit=autocommit,
+            )
+            return _DbConnection(connection)
 
         return Cmd.from_cmd(_action)
 
 
-connect = deprecated(reason="Use DbConnection.connect instead")(
-    DbConnection.connect
-)
+@dataclass(frozen=True)
+class DbConnection:
+    _inner: _DbConnection
+
+    def close(self) -> Cmd[None]:
+        return Cmd.from_cmd(lambda: self._inner._connection.close())
+
+    def commit(self) -> Cmd[None]:
+        return Cmd.from_cmd(lambda: self._inner._connection.commit())
+
+    @staticmethod
+    def connect_and_execute(
+        db_id: DatabaseId,
+        creds: Credentials,
+        readonly: bool,
+        isolation: IsolationLvl,
+        autocommit: bool,
+        action: Callable[[DbConnection], Cmd[_T | NoReturn]],
+    ) -> Cmd[_T]:
+        """Ensures that connection is closed regardless of action errors"""
+
+        def _inner(connection: DbConnection) -> Cmd[_T]:
+            def _action(unwrapper: CmdUnwrapper) -> _T:
+                try:
+                    return unwrapper.act(action(connection))
+                finally:
+                    unwrapper.act(connection.close())
+
+            return Cmd.new_cmd(_action)
+
+        return (
+            _DbConnection.connect(
+                db_id,
+                creds,
+                readonly,
+                isolation,
+                autocommit,
+            )
+            .map(DbConnection)
+            .bind(_inner)
+        )
```

### Comparing `redshift_client-2.0.0/redshift_client/sql_client/primitive.py` & `redshift_client-3.0.0/redshift_client/sql_client/primitive.py`

 * *Files identical despite different names*

### Comparing `redshift_client-2.0.0/redshift_client/sql_client/query.py` & `redshift_client-3.0.0/redshift_client/sql_client/query.py`

 * *Files 8% similar despite different names*

```diff
@@ -21,15 +21,15 @@
 
 
 def _purifier(statement: str, identifiers: FrozenDict[str, str]) -> SQL:
     raw_sql = SQL(statement)
     safe_args = FrozenDict(
         {key: Identifier(value) for key, value in identifiers.items()}
     )
-    return cast(SQL, raw_sql.format(**safe_args))  # type: ignore[no-untyped-call]
+    return cast(SQL, raw_sql.format(**safe_args))
 
 
 def _pretty(raw: str) -> str:
     return " ".join(raw.strip(" \n\t").split())
 
 
 @dataclass(frozen=True)
```

### Comparing `redshift_client-2.0.0/redshift_client/utils.py` & `redshift_client-3.0.0/redshift_client/utils.py`

 * *Files identical despite different names*

### Comparing `redshift_client-2.0.0/tests/arch/arch.py` & `redshift_client-3.0.0/tests/arch/arch.py`

 * *Files identical despite different names*

### Comparing `redshift_client-2.0.0/tests/arch/test_arch.py` & `redshift_client-3.0.0/tests/arch/test_arch.py`

 * *Files identical despite different names*


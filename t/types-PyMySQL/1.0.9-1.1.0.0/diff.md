# Comparing `tmp/types-PyMySQL-1.0.9.tar.gz` & `tmp/types-PyMySQL-1.1.0.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-PyMySQL-1.0.9.tar", last modified: Fri Jan  7 11:28:21 2022, max compression
+gzip compressed data, was "types-PyMySQL-1.1.0.0.tar", last modified: Wed Jun 28 12:35:47 2023, max compression
```

## Comparing `types-PyMySQL-1.0.9.tar` & `types-PyMySQL-1.1.0.0.tar`

### file list

```diff
@@ -1,29 +1,30 @@
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-01-07 11:28:21.770980 types-PyMySQL-1.0.9/
--rw-r--r--   0 runner    (1001) docker     (121)     1051 2022-01-07 11:28:21.000000 types-PyMySQL-1.0.9/CHANGELOG.md
--rw-r--r--   0 runner    (1001) docker     (121)       21 2022-01-07 11:28:21.000000 types-PyMySQL-1.0.9/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (121)      859 2022-01-07 11:28:21.770980 types-PyMySQL-1.0.9/PKG-INFO
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-01-07 11:28:21.770980 types-PyMySQL-1.0.9/pymysql-stubs/
--rw-r--r--   0 runner    (1001) docker     (121)       18 2022-01-07 11:28:21.000000 types-PyMySQL-1.0.9/pymysql-stubs/METADATA.toml
--rw-r--r--   0 runner    (1001) docker     (121)     1582 2022-01-07 11:27:57.000000 types-PyMySQL-1.0.9/pymysql-stubs/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (121)      327 2022-01-07 11:27:57.000000 types-PyMySQL-1.0.9/pymysql-stubs/charset.pyi
--rw-r--r--   0 runner    (1001) docker     (121)     7495 2022-01-07 11:27:57.000000 types-PyMySQL-1.0.9/pymysql-stubs/connections.pyi
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-01-07 11:28:21.770980 types-PyMySQL-1.0.9/pymysql-stubs/constants/
--rw-r--r--   0 runner    (1001) docker     (121)      308 2022-01-07 11:27:57.000000 types-PyMySQL-1.0.9/pymysql-stubs/constants/CLIENT.pyi
--rw-r--r--   0 runner    (1001) docker     (121)      407 2022-01-07 11:27:57.000000 types-PyMySQL-1.0.9/pymysql-stubs/constants/COMMAND.pyi
--rw-r--r--   0 runner    (1001) docker     (121)    11280 2022-01-07 11:27:57.000000 types-PyMySQL-1.0.9/pymysql-stubs/constants/ER.pyi
--rw-r--r--   0 runner    (1001) docker     (121)      354 2022-01-07 11:27:57.000000 types-PyMySQL-1.0.9/pymysql-stubs/constants/FIELD_TYPE.pyi
--rw-r--r--   0 runner    (1001) docker     (121)      226 2022-01-07 11:27:57.000000 types-PyMySQL-1.0.9/pymysql-stubs/constants/FLAG.pyi
--rw-r--r--   0 runner    (1001) docker     (121)      331 2022-01-07 11:27:57.000000 types-PyMySQL-1.0.9/pymysql-stubs/constants/SERVER_STATUS.pyi
--rw-r--r--   0 runner    (1001) docker     (121)        0 2022-01-07 11:27:57.000000 types-PyMySQL-1.0.9/pymysql-stubs/constants/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (121)     2241 2022-01-07 11:27:57.000000 types-PyMySQL-1.0.9/pymysql-stubs/converters.pyi
--rw-r--r--   0 runner    (1001) docker     (121)     2161 2022-01-07 11:27:57.000000 types-PyMySQL-1.0.9/pymysql-stubs/cursors.pyi
--rw-r--r--   0 runner    (1001) docker     (121)      600 2022-01-07 11:27:57.000000 types-PyMySQL-1.0.9/pymysql-stubs/err.pyi
--rw-r--r--   0 runner    (1001) docker     (121)      170 2022-01-07 11:27:57.000000 types-PyMySQL-1.0.9/pymysql-stubs/times.pyi
--rw-r--r--   0 runner    (1001) docker     (121)       66 2022-01-07 11:27:57.000000 types-PyMySQL-1.0.9/pymysql-stubs/util.pyi
--rw-r--r--   0 runner    (1001) docker     (121)       38 2022-01-07 11:28:21.770980 types-PyMySQL-1.0.9/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (121)     1458 2022-01-07 11:28:21.000000 types-PyMySQL-1.0.9/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-01-07 11:28:21.770980 types-PyMySQL-1.0.9/types_PyMySQL.egg-info/
--rw-r--r--   0 runner    (1001) docker     (121)      859 2022-01-07 11:28:21.000000 types-PyMySQL-1.0.9/types_PyMySQL.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (121)      669 2022-01-07 11:28:21.000000 types-PyMySQL-1.0.9/types_PyMySQL.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (121)        1 2022-01-07 11:28:21.000000 types-PyMySQL-1.0.9/types_PyMySQL.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (121)       14 2022-01-07 11:28:21.000000 types-PyMySQL-1.0.9/types_PyMySQL.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:35:47.619991 types-PyMySQL-1.1.0.0/
+-rw-r--r--   0 runner    (1001) docker     (123)     4030 2023-06-28 12:35:44.000000 types-PyMySQL-1.1.0.0/CHANGELOG.md
+-rw-r--r--   0 runner    (1001) docker     (123)       21 2023-06-28 12:35:44.000000 types-PyMySQL-1.1.0.0/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)     1554 2023-06-28 12:35:47.619991 types-PyMySQL-1.1.0.0/PKG-INFO
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:35:47.615991 types-PyMySQL-1.1.0.0/pymysql-stubs/
+-rw-r--r--   0 runner    (1001) docker     (123)       82 2023-06-28 12:35:44.000000 types-PyMySQL-1.1.0.0/pymysql-stubs/METADATA.toml
+-rw-r--r--   0 runner    (1001) docker     (123)     1491 2023-06-28 12:35:28.000000 types-PyMySQL-1.1.0.0/pymysql-stubs/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      322 2023-06-28 12:35:28.000000 types-PyMySQL-1.1.0.0/pymysql-stubs/charset.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8061 2023-06-28 12:35:28.000000 types-PyMySQL-1.1.0.0/pymysql-stubs/connections.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:35:47.619991 types-PyMySQL-1.1.0.0/pymysql-stubs/constants/
+-rw-r--r--   0 runner    (1001) docker     (123)      470 2023-06-28 12:35:28.000000 types-PyMySQL-1.1.0.0/pymysql-stubs/constants/CLIENT.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      615 2023-06-28 12:35:28.000000 types-PyMySQL-1.1.0.0/pymysql-stubs/constants/COMMAND.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     1771 2023-06-28 12:35:28.000000 types-PyMySQL-1.1.0.0/pymysql-stubs/constants/CR.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    11303 2023-06-28 12:35:28.000000 types-PyMySQL-1.1.0.0/pymysql-stubs/constants/ER.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      364 2023-06-28 12:35:28.000000 types-PyMySQL-1.1.0.0/pymysql-stubs/constants/FIELD_TYPE.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      202 2023-06-28 12:35:28.000000 types-PyMySQL-1.1.0.0/pymysql-stubs/constants/FLAG.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      331 2023-06-28 12:35:28.000000 types-PyMySQL-1.1.0.0/pymysql-stubs/constants/SERVER_STATUS.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:35:28.000000 types-PyMySQL-1.1.0.0/pymysql-stubs/constants/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     2319 2023-06-28 12:35:28.000000 types-PyMySQL-1.1.0.0/pymysql-stubs/converters.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     2177 2023-06-28 12:35:28.000000 types-PyMySQL-1.1.0.0/pymysql-stubs/cursors.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      594 2023-06-28 12:35:28.000000 types-PyMySQL-1.1.0.0/pymysql-stubs/err.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      170 2023-06-28 12:35:28.000000 types-PyMySQL-1.1.0.0/pymysql-stubs/times.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       66 2023-06-28 12:35:28.000000 types-PyMySQL-1.1.0.0/pymysql-stubs/util.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 12:35:47.619991 types-PyMySQL-1.1.0.0/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2244 2023-06-28 12:35:44.000000 types-PyMySQL-1.1.0.0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:35:47.619991 types-PyMySQL-1.1.0.0/types_PyMySQL.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     1554 2023-06-28 12:35:47.000000 types-PyMySQL-1.1.0.0/types_PyMySQL.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      700 2023-06-28 12:35:47.000000 types-PyMySQL-1.1.0.0/types_PyMySQL.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 12:35:47.000000 types-PyMySQL-1.1.0.0/types_PyMySQL.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       14 2023-06-28 12:35:47.000000 types-PyMySQL-1.1.0.0/types_PyMySQL.egg-info/top_level.txt
```

### Comparing `types-PyMySQL-1.0.9/PKG-INFO` & `types-PyMySQL-1.1.0.0/PKG-INFO`

 * *Files 26% similar despite different names*

```diff
@@ -1,23 +1,35 @@
 Metadata-Version: 2.1
 Name: types-PyMySQL
-Version: 1.0.9
+Version: 1.1.0.0
 Summary: Typing stubs for PyMySQL
 Home-page: https://github.com/python/typeshed
 License: Apache-2.0 license
-Platform: UNKNOWN
+Project-URL: GitHub, https://github.com/python/typeshed
+Project-URL: Changes, https://github.com/typeshed-internal/stub_uploader/blob/main/data/changelogs/PyMySQL.md
+Project-URL: Issue tracker, https://github.com/python/typeshed/issues
+Project-URL: Chat, https://gitter.im/python/typing
 Classifier: License :: OSI Approved :: Apache Software License
+Classifier: Programming Language :: Python :: 3
 Classifier: Typing :: Stubs Only
 Description-Content-Type: text/markdown
 
 ## Typing stubs for PyMySQL
 
-This is a PEP 561 type stub package for the `PyMySQL` package.
-It can be used by type-checking tools like mypy, PyCharm, pytype etc. to check code
-that uses `PyMySQL`. The source for this package can be found at
-https://github.com/python/typeshed/tree/master/stubs/PyMySQL. All fixes for
+This is a PEP 561 type stub package for the `PyMySQL` package. It
+can be used by type-checking tools like
+[mypy](https://github.com/python/mypy/),
+[pyright](https://github.com/microsoft/pyright),
+[pytype](https://github.com/google/pytype/),
+PyCharm, etc. to check code that uses
+`PyMySQL`. The source for this package can be found at
+https://github.com/python/typeshed/tree/main/stubs/PyMySQL. All fixes for
 types and metadata should be contributed there.
 
-See https://github.com/python/typeshed/blob/master/README.md for more details.
-This package was generated from typeshed commit `032e6ee90cbb938259a2aa2183966502de19108e`.
+This stub package is marked as [partial](https://peps.python.org/pep-0561/#partial-stub-packages).
+If you find that annotations are missing, feel free to contribute and help complete them.
 
 
+See https://github.com/python/typeshed/blob/main/README.md for more details.
+This package was generated from typeshed commit `0869b430d644b0580ca1d590b075a1db1d73677d` and was tested
+with mypy 1.4.1, pyright 1.1.315, and
+pytype 2023.6.2.
```

### Comparing `types-PyMySQL-1.0.9/pymysql-stubs/__init__.pyi` & `types-PyMySQL-1.1.0.0/pymysql-stubs/__init__.pyi`

 * *Files 7% similar despite different names*

```diff
@@ -1,9 +1,7 @@
-import sys
-
 from .connections import Connection as Connection
 from .constants import FIELD_TYPE as FIELD_TYPE
 from .converters import escape_dict as escape_dict, escape_sequence as escape_sequence, escape_string as escape_string
 from .err import (
     DatabaseError as DatabaseError,
     DataError as DataError,
     Error as Error,
@@ -39,20 +37,15 @@
 NUMBER: DBAPISet
 DATE: DBAPISet
 TIME: DBAPISet
 TIMESTAMP: DBAPISet
 DATETIME: DBAPISet
 ROWID: DBAPISet
 
-if sys.version_info >= (3, 0):
-    def Binary(x) -> bytes: ...
-
-else:
-    def Binary(x) -> bytearray: ...
-
+def Binary(x) -> bytes: ...
 def get_client_info() -> str: ...
 
 __version__: str
 version_info: tuple[int, int, int, str, int]
 NULL: str
 
 # pymysql/__init__.py says "Connect = connect = Connection = connections.Connection"
```

### Comparing `types-PyMySQL-1.0.9/pymysql-stubs/connections.pyi` & `types-PyMySQL-1.1.0.0/pymysql-stubs/connections.pyi`

 * *Files 12% similar despite different names*

```diff
@@ -1,9 +1,12 @@
+from _typeshed import Incomplete
+from collections.abc import Mapping
 from socket import socket as _socket
-from typing import Any, AnyStr, Generic, Mapping, Type, TypeVar, overload
+from typing import Any, AnyStr, Generic, TypeVar, overload
+from typing_extensions import Self
 
 from .charset import charset_by_id as charset_by_id, charset_by_name as charset_by_name
 from .constants import CLIENT as CLIENT, COMMAND as COMMAND, FIELD_TYPE as FIELD_TYPE, SERVER_STATUS as SERVER_STATUS
 from .cursors import Cursor
 from .util import byte2int as byte2int, int2byte as int2byte
 
 SSL_ENABLED: Any
@@ -21,16 +24,16 @@
 class MysqlPacket:
     connection: Any
     def __init__(self, data, encoding): ...
     def get_all_data(self): ...
     def read(self, size): ...
     def read_all(self): ...
     def advance(self, length): ...
-    def rewind(self, position: int = ...): ...
-    def get_bytes(self, position, length: int = ...): ...
+    def rewind(self, position: int = 0): ...
+    def get_bytes(self, position, length: int = 1): ...
     def read_string(self) -> bytes: ...
     def read_uint8(self) -> Any: ...
     def read_uint16(self) -> Any: ...
     def read_uint24(self) -> Any: ...
     def read_uint32(self) -> Any: ...
     def read_uint64(self) -> Any: ...
     def read_length_encoded_integer(self) -> int: ...
@@ -56,16 +59,17 @@
     ssl: Any
     host: Any
     port: Any
     user: Any
     password: Any
     db: Any
     unix_socket: Any
+    charset: str
+    collation: str | None
     bind_address: Any
-    charset: Any
     use_unicode: Any
     client_flag: Any
     cursorclass: Any
     connect_timeout: Any
     messages: Any
     encoders: Any
     decoders: Any
@@ -74,131 +78,135 @@
     init_command: Any
     max_allowed_packet: int
     server_public_key: bytes
     @overload
     def __init__(
         self: Connection[Cursor],  # different between overloads
         *,
-        host: str | None = ...,
-        user: Any | None = ...,
-        password: str = ...,
-        database: Any | None = ...,
-        port: int = ...,
-        unix_socket: Any | None = ...,
-        charset: str = ...,
-        sql_mode: Any | None = ...,
-        read_default_file: Any | None = ...,
-        conv=...,
-        use_unicode: bool | None = ...,
-        client_flag: int = ...,
-        cursorclass: None = ...,  # different between overloads
-        init_command: Any | None = ...,
-        connect_timeout: int | None = ...,
-        ssl: Mapping[Any, Any] | None = ...,
-        ssl_ca=...,
-        ssl_cert=...,
-        ssl_disabled=...,
-        ssl_key=...,
-        ssl_verify_cert=...,
-        ssl_verify_identity=...,
-        read_default_group: Any | None = ...,
-        compress: Any | None = ...,
-        named_pipe: Any | None = ...,
-        autocommit: bool | None = ...,
-        db: Any | None = ...,
-        passwd: Any | None = ...,
-        local_infile: Any | None = ...,
-        max_allowed_packet: int = ...,
-        defer_connect: bool | None = ...,
-        auth_plugin_map: Mapping[Any, Any] | None = ...,
-        read_timeout: float | None = ...,
-        write_timeout: float | None = ...,
-        bind_address: Any | None = ...,
-        binary_prefix: bool | None = ...,
-        program_name: Any | None = ...,
-        server_public_key: bytes | None = ...,
-    ): ...
+        host: str | None = None,
+        user: Incomplete | None = None,
+        password: str = "",
+        database: Incomplete | None = None,
+        port: int = 0,
+        unix_socket: Incomplete | None = None,
+        charset: str = "",
+        collation: str | None = None,
+        sql_mode: Incomplete | None = None,
+        read_default_file: Incomplete | None = None,
+        conv=None,
+        use_unicode: bool | None = True,
+        client_flag: int = 0,
+        cursorclass: None = None,  # different between overloads
+        init_command: Incomplete | None = None,
+        connect_timeout: int | None = 10,
+        ssl: Mapping[Any, Any] | None = None,
+        ssl_ca=None,
+        ssl_cert=None,
+        ssl_disabled=None,
+        ssl_key=None,
+        ssl_verify_cert=None,
+        ssl_verify_identity=None,
+        read_default_group: Incomplete | None = None,
+        compress: Incomplete | None = None,
+        named_pipe: Incomplete | None = None,
+        autocommit: bool | None = False,
+        db: Incomplete | None = None,
+        passwd: Incomplete | None = None,
+        local_infile: Incomplete | None = False,
+        max_allowed_packet: int = 16777216,
+        defer_connect: bool | None = False,
+        auth_plugin_map: Mapping[Any, Any] | None = None,
+        read_timeout: float | None = None,
+        write_timeout: float | None = None,
+        bind_address: Incomplete | None = None,
+        binary_prefix: bool | None = False,
+        program_name: Incomplete | None = None,
+        server_public_key: bytes | None = None,
+    ) -> None: ...
     @overload
     def __init__(
         self: Connection[_C],  # different between overloads
         *,
-        host: str | None = ...,
-        user: Any | None = ...,
-        password: str = ...,
-        database: Any | None = ...,
-        port: int = ...,
-        unix_socket: Any | None = ...,
-        charset: str = ...,
-        sql_mode: Any | None = ...,
-        read_default_file: Any | None = ...,
-        conv=...,
-        use_unicode: bool | None = ...,
-        client_flag: int = ...,
-        cursorclass: Type[_C] = ...,  # different between overloads
-        init_command: Any | None = ...,
-        connect_timeout: int | None = ...,
-        ssl: Mapping[Any, Any] | None = ...,
-        ssl_ca=...,
-        ssl_cert=...,
-        ssl_disabled=...,
-        ssl_key=...,
-        ssl_verify_cert=...,
-        ssl_verify_identity=...,
-        read_default_group: Any | None = ...,
-        compress: Any | None = ...,
-        named_pipe: Any | None = ...,
-        autocommit: bool | None = ...,
-        db: Any | None = ...,
-        passwd: Any | None = ...,
-        local_infile: Any | None = ...,
-        max_allowed_packet: int = ...,
-        defer_connect: bool | None = ...,
-        auth_plugin_map: Mapping[Any, Any] | None = ...,
-        read_timeout: float | None = ...,
-        write_timeout: float | None = ...,
-        bind_address: Any | None = ...,
-        binary_prefix: bool | None = ...,
-        program_name: Any | None = ...,
-        server_public_key: bytes | None = ...,
-    ): ...
+        host: str | None = None,
+        user: Incomplete | None = None,
+        password: str = "",
+        database: Incomplete | None = None,
+        port: int = 0,
+        unix_socket: Incomplete | None = None,
+        charset: str = "",
+        collation: str | None = None,
+        sql_mode: Incomplete | None = None,
+        read_default_file: Incomplete | None = None,
+        conv=None,
+        use_unicode: bool | None = True,
+        client_flag: int = 0,
+        cursorclass: type[_C] = ...,  # different between overloads
+        init_command: Incomplete | None = None,
+        connect_timeout: int | None = 10,
+        ssl: Mapping[Any, Any] | None = None,
+        ssl_ca=None,
+        ssl_cert=None,
+        ssl_disabled=None,
+        ssl_key=None,
+        ssl_verify_cert=None,
+        ssl_verify_identity=None,
+        read_default_group: Incomplete | None = None,
+        compress: Incomplete | None = None,
+        named_pipe: Incomplete | None = None,
+        autocommit: bool | None = False,
+        db: Incomplete | None = None,
+        passwd: Incomplete | None = None,
+        local_infile: Incomplete | None = False,
+        max_allowed_packet: int = 16777216,
+        defer_connect: bool | None = False,
+        auth_plugin_map: Mapping[Any, Any] | None = None,
+        read_timeout: float | None = None,
+        write_timeout: float | None = None,
+        bind_address: Incomplete | None = None,
+        binary_prefix: bool | None = False,
+        program_name: Incomplete | None = None,
+        server_public_key: bytes | None = None,
+    ) -> None: ...
     socket: Any
     rfile: Any
     wfile: Any
     def close(self) -> None: ...
     @property
     def open(self) -> bool: ...
     def autocommit(self, value) -> None: ...
     def get_autocommit(self) -> bool: ...
     def commit(self) -> None: ...
     def begin(self) -> None: ...
     def rollback(self) -> None: ...
     def select_db(self, db) -> None: ...
-    def escape(self, obj, mapping: Mapping[Any, Any] | None = ...): ...
+    def escape(self, obj, mapping: Mapping[Any, Any] | None = None): ...
     def literal(self, obj): ...
     def escape_string(self, s: AnyStr) -> AnyStr: ...
     @overload
-    def cursor(self, cursor: None = ...) -> _C: ...
+    def cursor(self, cursor: None = None) -> _C: ...
     @overload
-    def cursor(self, cursor: Type[_C2]) -> _C2: ...
-    def query(self, sql, unbuffered: bool = ...) -> int: ...
-    def next_result(self, unbuffered: bool = ...) -> int: ...
+    def cursor(self, cursor: type[_C2]) -> _C2: ...
+    def query(self, sql, unbuffered: bool = False) -> int: ...
+    def next_result(self, unbuffered: bool = False) -> int: ...
     def affected_rows(self): ...
     def kill(self, thread_id): ...
-    def ping(self, reconnect: bool = ...) -> None: ...
+    def ping(self, reconnect: bool = True) -> None: ...
     def set_charset(self, charset) -> None: ...
-    def connect(self, sock: _socket | None = ...) -> None: ...
+    def connect(self, sock: _socket | None = None) -> None: ...
     def write_packet(self, payload) -> None: ...
     def _read_packet(self, packet_type=...): ...
     def insert_id(self): ...
     def thread_id(self): ...
     def character_set_name(self): ...
     def get_host_info(self): ...
     def get_proto_info(self): ...
     def get_server_info(self): ...
     def show_warnings(self): ...
+    def __enter__(self) -> Self: ...
+    def __exit__(self, *exc_info: object) -> None: ...
     Warning: Any
     Error: Any
     InterfaceError: Any
     DatabaseError: Any
     DataError: Any
     OperationalError: Any
     IntegrityError: Any
```

### Comparing `types-PyMySQL-1.0.9/pymysql-stubs/constants/ER.pyi` & `types-PyMySQL-1.1.0.0/pymysql-stubs/constants/ER.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -465,7 +465,8 @@
 NON_GROUPING_FIELD_USED: int
 TABLE_CANT_HANDLE_SPKEYS: int
 NO_TRIGGERS_ON_SYSTEM_SCHEMA: int
 USERNAME: int
 HOSTNAME: int
 WRONG_STRING_LENGTH: int
 ERROR_LAST: int
+CONSTRAINT_FAILED: int
```

### Comparing `types-PyMySQL-1.0.9/pymysql-stubs/converters.pyi` & `types-PyMySQL-1.1.0.0/pymysql-stubs/converters.pyi`

 * *Files 21% similar despite different names*

```diff
@@ -1,39 +1,41 @@
 import datetime
 import time
+from _typeshed import Unused
 from collections.abc import Callable, Mapping, Sequence
 from decimal import Decimal
-from typing import Any, Optional, Type, TypeVar
+from typing import Any, TypeVar
+from typing_extensions import TypeAlias
 
-_EscaperMapping = Optional[Mapping[Type[object], Callable[..., str]]]
+_EscaperMapping: TypeAlias = Mapping[type[object], Callable[..., str]] | None
 _T = TypeVar("_T")
 
-def escape_item(val: object, charset: object, mapping: _EscaperMapping = ...) -> str: ...
-def escape_dict(val: Mapping[str, object], charset: object, mapping: _EscaperMapping = ...) -> dict[str, str]: ...
-def escape_sequence(val: Sequence[object], charset: object, mapping: _EscaperMapping = ...) -> str: ...
-def escape_set(val: set[object], charset: object, mapping: _EscaperMapping = ...) -> str: ...
-def escape_bool(value: bool, mapping: _EscaperMapping = ...) -> str: ...
-def escape_int(value: int, mapping: _EscaperMapping = ...) -> str: ...
-def escape_float(value: float, mapping: _EscaperMapping = ...) -> str: ...
-def escape_string(value: str, mapping: _EscaperMapping = ...) -> str: ...
-def escape_bytes_prefixed(value: bytes, mapping: _EscaperMapping = ...) -> str: ...
-def escape_bytes(value: bytes, mapping: _EscaperMapping = ...) -> str: ...
-def escape_str(value: str, mapping: _EscaperMapping = ...) -> str: ...
-def escape_None(value: None, mapping: _EscaperMapping = ...) -> str: ...
-def escape_timedelta(obj: datetime.timedelta, mapping: _EscaperMapping = ...) -> str: ...
-def escape_time(obj: datetime.time, mapping: _EscaperMapping = ...) -> str: ...
-def escape_datetime(obj: datetime.datetime, mapping: _EscaperMapping = ...) -> str: ...
-def escape_date(obj: datetime.date, mapping: _EscaperMapping = ...) -> str: ...
-def escape_struct_time(obj: time.struct_time, mapping: _EscaperMapping = ...) -> str: ...
-def Decimal2Literal(o: Decimal, d: object) -> str: ...
+def escape_item(val: object, charset: object, mapping: _EscaperMapping = None) -> str: ...
+def escape_dict(val: Mapping[str, object], charset: object, mapping: _EscaperMapping = None) -> dict[str, str]: ...
+def escape_sequence(val: Sequence[object], charset: object, mapping: _EscaperMapping = None) -> str: ...
+def escape_set(val: set[object], charset: object, mapping: _EscaperMapping = None) -> str: ...
+def escape_bool(value: bool, mapping: _EscaperMapping = None) -> str: ...
+def escape_int(value: int, mapping: _EscaperMapping = None) -> str: ...
+def escape_float(value: float, mapping: _EscaperMapping = None) -> str: ...
+def escape_string(value: str, mapping: _EscaperMapping = None) -> str: ...
+def escape_bytes_prefixed(value: bytes, mapping: _EscaperMapping = None) -> str: ...
+def escape_bytes(value: bytes, mapping: _EscaperMapping = None) -> str: ...
+def escape_str(value: str, mapping: _EscaperMapping = None) -> str: ...
+def escape_None(value: None, mapping: _EscaperMapping = None) -> str: ...
+def escape_timedelta(obj: datetime.timedelta, mapping: _EscaperMapping = None) -> str: ...
+def escape_time(obj: datetime.time, mapping: _EscaperMapping = None) -> str: ...
+def escape_datetime(obj: datetime.datetime, mapping: _EscaperMapping = None) -> str: ...
+def escape_date(obj: datetime.date, mapping: _EscaperMapping = None) -> str: ...
+def escape_struct_time(obj: time.struct_time, mapping: _EscaperMapping = None) -> str: ...
+def Decimal2Literal(o: Decimal, d: Unused) -> str: ...
 def convert_datetime(obj: str | bytes) -> datetime.datetime | str: ...
 def convert_timedelta(obj: str | bytes) -> datetime.timedelta | str: ...
 def convert_time(obj: str | bytes) -> datetime.time | str: ...
 def convert_date(obj: str | bytes) -> datetime.date | str: ...
 def through(x: _T) -> _T: ...
 
 convert_bit = through
 
-encoders: dict[Type[object], Callable[..., str]]
+encoders: dict[type[object], Callable[..., str]]
 decoders: dict[int, Callable[[str | bytes], Any]]
-conversions: dict[Type[object] | int, Callable[..., Any]]
+conversions: dict[type[object] | int, Callable[..., Any]]
 Thing2Literal = escape_str
```

### Comparing `types-PyMySQL-1.0.9/pymysql-stubs/cursors.pyi` & `types-PyMySQL-1.1.0.0/pymysql-stubs/cursors.pyi`

 * *Files 20% similar despite different names*

```diff
@@ -1,50 +1,50 @@
-from typing import Any, Iterable, Iterator, Text, TypeVar
+from collections.abc import Iterable, Iterator
+from typing import Any
+from typing_extensions import Self
 
 from .connections import Connection
 
-_SelfT = TypeVar("_SelfT")
-
 class Cursor:
     connection: Connection[Any]
-    description: tuple[Text, ...]
+    description: tuple[str, ...]
     rownumber: int
     rowcount: int
     arraysize: int
     messages: Any
     errorhandler: Any
     lastrowid: int
     def __init__(self, connection: Connection[Any]) -> None: ...
     def __del__(self) -> None: ...
     def close(self) -> None: ...
     def setinputsizes(self, *args) -> None: ...
     def setoutputsizes(self, *args) -> None: ...
     def nextset(self) -> bool | None: ...
-    def mogrify(self, query: Text, args: object = ...) -> str: ...
-    def execute(self, query: Text, args: object = ...) -> int: ...
-    def executemany(self, query: Text, args: Iterable[object]) -> int | None: ...
-    def callproc(self, procname: Text, args: Iterable[Any] = ...) -> Any: ...
-    def scroll(self, value: int, mode: Text = ...) -> None: ...
-    def __enter__(self: _SelfT) -> _SelfT: ...
-    def __exit__(self, *exc_info: Any) -> None: ...
+    def mogrify(self, query: str, args: object = None) -> str: ...
+    def execute(self, query: str, args: object = None) -> int: ...
+    def executemany(self, query: str, args: Iterable[object]) -> int | None: ...
+    def callproc(self, procname: str, args: Iterable[Any] = ()) -> Any: ...
+    def scroll(self, value: int, mode: str = "relative") -> None: ...
+    def __enter__(self) -> Self: ...
+    def __exit__(self, *exc_info: object) -> None: ...
     # Methods returning result tuples are below.
     def fetchone(self) -> tuple[Any, ...] | None: ...
-    def fetchmany(self, size: int | None = ...) -> tuple[tuple[Any, ...], ...]: ...
+    def fetchmany(self, size: int | None = None) -> tuple[tuple[Any, ...], ...]: ...
     def fetchall(self) -> tuple[tuple[Any, ...], ...]: ...
     def __iter__(self) -> Iterator[tuple[Any, ...]]: ...
 
 class DictCursorMixin:
     dict_type: Any  # TODO: add support if someone needs this
-    def fetchone(self) -> dict[Text, Any] | None: ...
-    def fetchmany(self, size: int | None = ...) -> tuple[dict[Text, Any], ...]: ...
-    def fetchall(self) -> tuple[dict[Text, Any], ...]: ...
-    def __iter__(self) -> Iterator[dict[Text, Any]]: ...
+    def fetchone(self) -> dict[str, Any] | None: ...
+    def fetchmany(self, size: int | None = ...) -> tuple[dict[str, Any], ...]: ...
+    def fetchall(self) -> tuple[dict[str, Any], ...]: ...
+    def __iter__(self) -> Iterator[dict[str, Any]]: ...
 
 class SSCursor(Cursor):
     def fetchall(self) -> list[tuple[Any, ...]]: ...  # type: ignore[override]
     def fetchall_unbuffered(self) -> Iterator[tuple[Any, ...]]: ...
-    def scroll(self, value: int, mode: Text = ...) -> None: ...
+    def scroll(self, value: int, mode: str = "relative") -> None: ...
 
 class DictCursor(DictCursorMixin, Cursor): ...  # type: ignore[misc]
 
 class SSDictCursor(DictCursorMixin, SSCursor):  # type: ignore[misc]
-    def fetchall_unbuffered(self) -> Iterator[dict[Text, Any]]: ...  # type: ignore[override]
+    def fetchall_unbuffered(self) -> Iterator[dict[str, Any]]: ...  # type: ignore[override]
```

### Comparing `types-PyMySQL-1.0.9/setup.py` & `types-PyMySQL-1.1.0.0/setup.py`

 * *Files 26% similar despite different names*

```diff
@@ -1,32 +1,49 @@
 from setuptools import setup
 
 name = "types-PyMySQL"
 description = "Typing stubs for PyMySQL"
 long_description = '''
 ## Typing stubs for PyMySQL
 
-This is a PEP 561 type stub package for the `PyMySQL` package.
-It can be used by type-checking tools like mypy, PyCharm, pytype etc. to check code
-that uses `PyMySQL`. The source for this package can be found at
-https://github.com/python/typeshed/tree/master/stubs/PyMySQL. All fixes for
+This is a PEP 561 type stub package for the `PyMySQL` package. It
+can be used by type-checking tools like
+[mypy](https://github.com/python/mypy/),
+[pyright](https://github.com/microsoft/pyright),
+[pytype](https://github.com/google/pytype/),
+PyCharm, etc. to check code that uses
+`PyMySQL`. The source for this package can be found at
+https://github.com/python/typeshed/tree/main/stubs/PyMySQL. All fixes for
 types and metadata should be contributed there.
 
-See https://github.com/python/typeshed/blob/master/README.md for more details.
-This package was generated from typeshed commit `032e6ee90cbb938259a2aa2183966502de19108e`.
+This stub package is marked as [partial](https://peps.python.org/pep-0561/#partial-stub-packages).
+If you find that annotations are missing, feel free to contribute and help complete them.
+
+
+See https://github.com/python/typeshed/blob/main/README.md for more details.
+This package was generated from typeshed commit `0869b430d644b0580ca1d590b075a1db1d73677d` and was tested
+with mypy 1.4.1, pyright 1.1.315, and
+pytype 2023.6.2.
 '''.lstrip()
 
 setup(name=name,
-      version="1.0.9",
+      version="1.1.0.0",
       description=description,
       long_description=long_description,
       long_description_content_type="text/markdown",
       url="https://github.com/python/typeshed",
+      project_urls={
+          "GitHub": "https://github.com/python/typeshed",
+          "Changes": "https://github.com/typeshed-internal/stub_uploader/blob/main/data/changelogs/PyMySQL.md",
+          "Issue tracker": "https://github.com/python/typeshed/issues",
+          "Chat": "https://gitter.im/python/typing",
+      },
       install_requires=[],
       packages=['pymysql-stubs'],
-      package_data={'pymysql-stubs': ['__init__.pyi', 'charset.pyi', 'connections.pyi', 'constants/CLIENT.pyi', 'constants/COMMAND.pyi', 'constants/ER.pyi', 'constants/FIELD_TYPE.pyi', 'constants/FLAG.pyi', 'constants/SERVER_STATUS.pyi', 'constants/__init__.pyi', 'converters.pyi', 'cursors.pyi', 'err.pyi', 'times.pyi', 'util.pyi', 'METADATA.toml']},
+      package_data={'pymysql-stubs': ['__init__.pyi', 'charset.pyi', 'connections.pyi', 'constants/CLIENT.pyi', 'constants/COMMAND.pyi', 'constants/CR.pyi', 'constants/ER.pyi', 'constants/FIELD_TYPE.pyi', 'constants/FLAG.pyi', 'constants/SERVER_STATUS.pyi', 'constants/__init__.pyi', 'converters.pyi', 'cursors.pyi', 'err.pyi', 'times.pyi', 'util.pyi', 'METADATA.toml', 'py.typed']},
       license="Apache-2.0 license",
       classifiers=[
           "License :: OSI Approved :: Apache Software License",
+          "Programming Language :: Python :: 3",
           "Typing :: Stubs Only",
       ]
 )
```

### Comparing `types-PyMySQL-1.0.9/types_PyMySQL.egg-info/PKG-INFO` & `types-PyMySQL-1.1.0.0/types_PyMySQL.egg-info/PKG-INFO`

 * *Files 26% similar despite different names*

```diff
@@ -1,23 +1,35 @@
 Metadata-Version: 2.1
 Name: types-PyMySQL
-Version: 1.0.9
+Version: 1.1.0.0
 Summary: Typing stubs for PyMySQL
 Home-page: https://github.com/python/typeshed
 License: Apache-2.0 license
-Platform: UNKNOWN
+Project-URL: GitHub, https://github.com/python/typeshed
+Project-URL: Changes, https://github.com/typeshed-internal/stub_uploader/blob/main/data/changelogs/PyMySQL.md
+Project-URL: Issue tracker, https://github.com/python/typeshed/issues
+Project-URL: Chat, https://gitter.im/python/typing
 Classifier: License :: OSI Approved :: Apache Software License
+Classifier: Programming Language :: Python :: 3
 Classifier: Typing :: Stubs Only
 Description-Content-Type: text/markdown
 
 ## Typing stubs for PyMySQL
 
-This is a PEP 561 type stub package for the `PyMySQL` package.
-It can be used by type-checking tools like mypy, PyCharm, pytype etc. to check code
-that uses `PyMySQL`. The source for this package can be found at
-https://github.com/python/typeshed/tree/master/stubs/PyMySQL. All fixes for
+This is a PEP 561 type stub package for the `PyMySQL` package. It
+can be used by type-checking tools like
+[mypy](https://github.com/python/mypy/),
+[pyright](https://github.com/microsoft/pyright),
+[pytype](https://github.com/google/pytype/),
+PyCharm, etc. to check code that uses
+`PyMySQL`. The source for this package can be found at
+https://github.com/python/typeshed/tree/main/stubs/PyMySQL. All fixes for
 types and metadata should be contributed there.
 
-See https://github.com/python/typeshed/blob/master/README.md for more details.
-This package was generated from typeshed commit `032e6ee90cbb938259a2aa2183966502de19108e`.
+This stub package is marked as [partial](https://peps.python.org/pep-0561/#partial-stub-packages).
+If you find that annotations are missing, feel free to contribute and help complete them.
 
 
+See https://github.com/python/typeshed/blob/main/README.md for more details.
+This package was generated from typeshed commit `0869b430d644b0580ca1d590b075a1db1d73677d` and was tested
+with mypy 1.4.1, pyright 1.1.315, and
+pytype 2023.6.2.
```

### Comparing `types-PyMySQL-1.0.9/types_PyMySQL.egg-info/SOURCES.txt` & `types-PyMySQL-1.1.0.0/types_PyMySQL.egg-info/SOURCES.txt`

 * *Files 5% similar despite different names*

```diff
@@ -8,14 +8,15 @@
 pymysql-stubs/converters.pyi
 pymysql-stubs/cursors.pyi
 pymysql-stubs/err.pyi
 pymysql-stubs/times.pyi
 pymysql-stubs/util.pyi
 pymysql-stubs/constants/CLIENT.pyi
 pymysql-stubs/constants/COMMAND.pyi
+pymysql-stubs/constants/CR.pyi
 pymysql-stubs/constants/ER.pyi
 pymysql-stubs/constants/FIELD_TYPE.pyi
 pymysql-stubs/constants/FLAG.pyi
 pymysql-stubs/constants/SERVER_STATUS.pyi
 pymysql-stubs/constants/__init__.pyi
 types_PyMySQL.egg-info/PKG-INFO
 types_PyMySQL.egg-info/SOURCES.txt
```


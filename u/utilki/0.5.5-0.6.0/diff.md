# Comparing `tmp/utilki-0.5.5.tar.gz` & `tmp/utilki-0.6.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "utilki-0.5.5.tar", max compression
+gzip compressed data, was "utilki-0.6.0.tar", max compression
```

## Comparing `utilki-0.5.5.tar` & `utilki-0.6.0.tar`

### file list

```diff
@@ -1,7 +1,7 @@
--rw-r--r--   0        0        0     1064 2023-06-28 14:59:26.559605 utilki-0.5.5/README.md
--rw-r--r--   0        0        0      525 2023-06-28 14:59:26.559605 utilki-0.5.5/pyproject.toml
--rw-r--r--   0        0        0      368 2023-06-28 14:59:26.559605 utilki-0.5.5/utilki/__init__.py
--rw-r--r--   0        0        0     2184 2023-06-28 14:59:26.559605 utilki-0.5.5/utilki/cli.py
--rw-r--r--   0        0        0     5872 2023-06-28 14:59:26.559605 utilki-0.5.5/utilki/log_utils.py
--rw-r--r--   0        0        0     7325 2023-06-28 14:59:26.559605 utilki-0.5.5/utilki/task_mixin.py
--rw-r--r--   0        0        0     1659 1970-01-01 00:00:00.000000 utilki-0.5.5/PKG-INFO
+-rw-r--r--   0        0        0     1064 2023-06-28 16:04:44.770285 utilki-0.6.0/README.md
+-rw-r--r--   0        0        0      525 2023-06-28 16:04:44.770285 utilki-0.6.0/pyproject.toml
+-rw-r--r--   0        0        0       98 2023-06-28 16:04:44.770285 utilki-0.6.0/utilki/__init__.py
+-rw-r--r--   0        0        0     2184 2023-06-28 16:04:44.770285 utilki-0.6.0/utilki/cli.py
+-rw-r--r--   0        0        0     6411 2023-06-28 16:04:44.770285 utilki-0.6.0/utilki/log_utils.py
+-rw-r--r--   0        0        0     7325 2023-06-28 16:04:44.770285 utilki-0.6.0/utilki/task_mixin.py
+-rw-r--r--   0        0        0     1659 1970-01-01 00:00:00.000000 utilki-0.6.0/PKG-INFO
```

### Comparing `utilki-0.5.5/README.md` & `utilki-0.6.0/README.md`

 * *Files identical despite different names*

### Comparing `utilki-0.5.5/pyproject.toml` & `utilki-0.6.0/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "utilki"
-version = "0.5.5"
+version = "0.6.0"
 description = "A collection of useful utilities"
 readme = "README.md"
 authors = ["Khaidar Bikmaev <khaidar@bikmaev.com>"]
 
 [tool.poetry.dependencies]
 python = ">=3.7"
 click = "^8.1.3"
```

### Comparing `utilki-0.5.5/utilki/cli.py` & `utilki-0.6.0/utilki/cli.py`

 * *Files identical despite different names*

### Comparing `utilki-0.5.5/utilki/log_utils.py` & `utilki-0.6.0/utilki/log_utils.py`

 * *Files 22% similar despite different names*

```diff
@@ -4,148 +4,155 @@
 from typing import Any, Callable, Optional, TypeVar, Generic, Iterable
 
 
 def set_global(name: str, value: Any):
     globals()[name] = value
 
 
-def get_global(name: str, default=None) -> Optional[Any]:
+def get_global(name: str, default=None) -> Any:
     try:
         return globals()[name]
     except KeyError:
         return None if default is None else default
 
 
-def set_logger_name(name: str):
-    globals()["_logger_name"] = name
+class _logger:
+    def __init__(self, name) -> None:
+        set_global("_logger_name", name)
+        self._hide_level_name = False
 
+    def level(self, level: int):
+        _get_logger().setLevel(level)
+        return self
 
-def _get_logger_name() -> Optional[str]:
-    try:
-        logger_name = globals()["_logger_name"]
-    except KeyError:
-        logger_name = None
-    return logger_name
-
-
-def set_use_print(use_print: bool):
-    globals()["_use_print"] = use_print
-
-
-def _get_use_print() -> bool:
-    try:
-        use_print = globals()["_use_print"]
-    except KeyError:
-        use_print = False
-    return use_print
-
+    def debug(self):
+        return self.level(logging.DEBUG)
 
-def set_callback(callback: Callable):
-    globals()["_callback"] = callback
+    def info(self):
+        return self.level(logging.INFO)
 
+    def warn(self):
+        return self.level(logging.WARNING)
 
-def _get_callback() -> Optional[Callable]:
-    try:
-        callback = globals()["_callback"]
-    except KeyError:
-        callback = None
-    return callback
+    def error(self):
+        return self.level(logging.ERROR)
 
+    def critical(self):
+        return self.level(logging.CRITICAL)
 
-def _get_logger() -> logging.Logger:
-    logger_name = _get_logger_name()
-    return logging.getLogger(logger_name)
-
-
-def set_logger_level(level: int):
-    logger = _get_logger()
-    logger.setLevel(level)
+    def use_print(self, use_print: bool):
+        set_global("_use_print", use_print)
+        return self
 
+    def callback(self, callback: Callable):
+        set_global("_callback", callback)
+        return self
 
-def set_log_info():
-    set_logger_level(logging.INFO)
+    def hide_level_name(self):
+        self._hide_level_name = True
 
+    def basic_config(self, level: int = logging.WARN):
+        logging.basicConfig(
+            format="%(asctime)s %(message)s"
+            if self._hide_level_name
+            else "%(asctime)s %(levelname)s %(message)s",
+            datefmt="%Y-%m-%d %H:%M:%S",
+            # NB: this is the default level of the root logger
+            level=level,
+            stream=sys.stdout,
+        )
+        return self
 
-def set_log_debug():
-    set_logger_level(logging.DEBUG)
+    def fn_level(self, level: int):
+        """
+        Set the level of the `log(message: str)` function.
+        """
+        set_global("_log_fn_level", level)
+        return self
 
 
-def set_log_warn():
-    set_logger_level(logging.WARNING)
+def logger(name: str) -> _logger:
+    return _logger(name)
 
 
-def if_level(level: int, message: str):
-    _use_print = _get_use_print()
-    _callback = _get_callback()
+def __log_fn(level: int) -> Callable[[str], None]:
+    logger = _get_logger()
+    if level == logging.DEBUG:
+        return logger.debug
+    elif level == logging.INFO:
+        return logger.info
+    elif level == logging.WARNING:
+        return logger.warning
+    elif level == logging.ERROR:
+        return logger.error
+    elif level == logging.CRITICAL:
+        return logger.critical
+    else:
+        return logging.info
+
+
+def _if_level(level: int, message: str):
+    _use_print = get_global("_use_print", False)
+    _callback = get_global("_callback", None)
     _logger = _get_logger()
 
     if _logger.level <= level:
         if _use_print:
             print(f"{message}", flush=True)
         if _callback:
             _callback(message)
 
 
-def set_log_fn_level(level: int):
-    globals()["_log_fn_level"] = level
+def _get_logger() -> logging.Logger:
+    logger_name = get_global("_logger_name")
+    return logging.getLogger(logger_name)
 
 
-def _get_log_fn_level() -> int:
-    try:
-        log_fn_level = globals()["_log_fn_level"]
-    except KeyError:
-        log_fn_level = logging.CRITICAL
-    return log_fn_level
+def log(message: Any):
+    message = str(message)
+    level: int = get_global("_log_fn_level", logging.INFO)
+    _if_level(level, message)
+    __log_fn(level)(message)
 
 
-def log(message: Any):
+def dbg(message: Any):
     message = str(message)
     logger = _get_logger()
-    if_level(_get_log_fn_level(), message)
-    logger.info(message)
+    _if_level(logging.DEBUG, message)
+    logger.debug(message)
 
 
-def dbg(message: Any):
+def debug(message: Any):
     message = str(message)
     logger = _get_logger()
-    if_level(logging.DEBUG, message)
+    _if_level(logging.DEBUG, message)
     logger.debug(message)
 
 
 def info(message: Any):
     message = str(message)
     logger = _get_logger()
-    if_level(logging.INFO, message)
+    _if_level(logging.INFO, message)
     logger.info(message)
 
 
 def warn(message: Any):
     message = str(message)
     logger = _get_logger()
-    if_level(logging.WARNING, message)
+    _if_level(logging.WARNING, message)
     logger.warning(message)
 
 
 def err(message: Any):
     message = str(message)
     logger = _get_logger()
-    if_level(logging.ERROR, message)
+    _if_level(logging.ERROR, message)
     logger.error(message)
 
 
-def basic_config(level=logging.CRITICAL):
-    logging.basicConfig(
-        format="%(asctime)s %(levelname)s %(message)s",
-        datefmt="%Y-%m-%d %H:%M:%S",
-        # NB: this is the default level of the root logger
-        level=level,
-        stream=sys.stdout,
-    )
-
-
 A = TypeVar("A")
 
 
 class progress(Generic[A]):
     def __init__(
         self,
         iterator: Iterable[A],
@@ -199,20 +206,22 @@
             raise StopIteration
         else:
             self.index += 1
             return next(self.iterator)
 
 
 if __name__ == "__main__":
-    import time
 
-    set_logger_name("progress")
+    def rev(msg):
+        print(msg[::-1])
+        pass
 
-    # setup basic logging format
-    basic_config()
+    import time
+
+    logger("test").info().basic_config()
 
     # too lazy rn to make a proper test suite
     for i in progress(range(101), name="test1"):
         time.sleep(0.001)
 
     for i in progress(
         range(7),
@@ -226,25 +235,18 @@
     for idx, i in enumerate(progress(["a", "b", "c"], name="test3")):
         time.sleep(0.001)
 
     for i in progress([0.1, 0.2, 0.3], name="test4"):
         log(i)
         time.sleep(0.001)
 
-    def rev(msg):
-        print(msg[::-1])
-        pass
-
-    set_use_print(True)
-    set_logger_name("ayy")
-    set_callback(rev)
     log("hello world")
 
-    logging.getLogger("ayy").setLevel(logging.INFO)
-    dbg("debug message")
+    # logging.getLogger("ayy").setLevel(logging.INFO)
+    logger("ayy").info().fn_level(logging.CRITICAL).basic_config()
 
     set_global("ayy", "lmao")
     value = get_global("ayy")
     log(value)
 
     from datetime import datetime
```

### Comparing `utilki-0.5.5/utilki/task_mixin.py` & `utilki-0.6.0/utilki/task_mixin.py`

 * *Files identical despite different names*

### Comparing `utilki-0.5.5/PKG-INFO` & `utilki-0.6.0/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: utilki
-Version: 0.5.5
+Version: 0.6.0
 Summary: A collection of useful utilities
 Author: Khaidar Bikmaev
 Author-email: khaidar@bikmaev.com
 Requires-Python: >=3.7
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
```


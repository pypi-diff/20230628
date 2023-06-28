# Comparing `tmp/robocorp_log-1.2.0.tar.gz` & `tmp/robocorp_log-2.0.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "robocorp_log-1.2.0.tar", max compression
+gzip compressed data, was "robocorp_log-2.0.0.tar", max compression
```

## Comparing `robocorp_log-1.2.0.tar` & `robocorp_log-2.0.0.tar`

### file list

```diff
@@ -1,28 +1,28 @@
--rw-r--r--   0        0        0    10142 2023-06-23 17:29:03.372146 robocorp_log-1.2.0/LICENSE
--rw-r--r--   0        0        0     5607 2023-06-23 17:29:03.372146 robocorp_log-1.2.0/README.md
--rw-r--r--   0        0        0     1297 2023-06-23 17:29:03.380146 robocorp_log-1.2.0/pyproject.toml
--rw-r--r--   0        0        0    31972 2023-06-23 17:29:03.380146 robocorp_log-1.2.0/src/robocorp/log/__init__.py
--rw-r--r--   0        0        0    17958 2023-06-23 17:29:03.380146 robocorp_log-1.2.0/src/robocorp/log/_ast_utils.py
--rw-r--r--   0        0        0    15276 2023-06-23 17:29:03.380146 robocorp_log-1.2.0/src/robocorp/log/_auto_logging_setup.py
--rw-r--r--   0        0        0     5999 2023-06-23 17:29:03.380146 robocorp_log-1.2.0/src/robocorp/log/_config.py
--rw-r--r--   0        0        0      696 2023-06-23 17:29:03.380146 robocorp_log-1.2.0/src/robocorp/log/_convert_units.py
--rw-r--r--   0        0        0     7103 2023-06-23 17:29:03.380146 robocorp_log-1.2.0/src/robocorp/log/_decoder.py
--rw-r--r--   0        0        0     7193 2023-06-23 17:29:03.380146 robocorp_log-1.2.0/src/robocorp/log/_decoder_spec.py
--rw-r--r--   0        0        0   793089 2023-06-23 17:30:15.623056 robocorp_log-1.2.0/src/robocorp/log/_index_v3.py
--rw-r--r--   0        0        0     7067 2023-06-23 17:29:03.380146 robocorp_log-1.2.0/src/robocorp/log/_lifecycle_hooks.py
--rw-r--r--   0        0        0     1128 2023-06-23 17:29:03.380146 robocorp_log-1.2.0/src/robocorp/log/_logger_instances.py
--rw-r--r--   0        0        0     1208 2023-06-23 17:29:03.380146 robocorp_log-1.2.0/src/robocorp/log/_null.py
--rw-r--r--   0        0        0      591 2023-06-23 17:29:03.380146 robocorp_log-1.2.0/src/robocorp/log/_obj_info_repr.py
--rw-r--r--   0        0        0      206 2023-06-23 17:29:03.380146 robocorp_log-1.2.0/src/robocorp/log/_on_exit_context_manager.py
--rw-r--r--   0        0        0    33694 2023-06-23 17:29:03.380146 robocorp_log-1.2.0/src/robocorp/log/_rewrite_ast_add_callbacks.py
--rw-r--r--   0        0        0     9217 2023-06-23 17:29:03.380146 robocorp_log-1.2.0/src/robocorp/log/_rewrite_filtering.py
--rw-r--r--   0        0        0    12650 2023-06-23 17:29:03.380146 robocorp_log-1.2.0/src/robocorp/log/_rewrite_importhook.py
--rw-r--r--   0        0        0    11686 2023-06-23 17:29:03.380146 robocorp_log-1.2.0/src/robocorp/log/_robo_logger.py
--rw-r--r--   0        0        0    67424 2023-06-23 17:29:03.380146 robocorp_log-1.2.0/src/robocorp/log/_robo_output_impl.py
--rw-r--r--   0        0        0     1436 2023-06-23 17:29:03.380146 robocorp_log-1.2.0/src/robocorp/log/_sensitive_variable_names.py
--rw-r--r--   0        0        0     1915 2023-06-23 17:29:03.380146 robocorp_log-1.2.0/src/robocorp/log/_suppress_helper.py
--rw-r--r--   0        0        0     7802 2023-06-23 17:29:03.380146 robocorp_log-1.2.0/src/robocorp/log/console.py
--rw-r--r--   0        0        0     1147 2023-06-23 17:29:03.380146 robocorp_log-1.2.0/src/robocorp/log/protocols.py
--rw-r--r--   0        0        0        0 2023-06-23 17:29:03.380146 robocorp_log-1.2.0/src/robocorp/log/py.typed
--rw-r--r--   0        0        0     8025 2023-06-23 17:29:03.380146 robocorp_log-1.2.0/src/robocorp/log/redirect.py
--rw-r--r--   0        0        0     6474 1970-01-01 00:00:00.000000 robocorp_log-1.2.0/PKG-INFO
+-rw-r--r--   0        0        0    10142 2023-06-28 12:07:29.574393 robocorp_log-2.0.0/LICENSE
+-rw-r--r--   0        0        0     5592 2023-06-28 12:07:29.574393 robocorp_log-2.0.0/README.md
+-rw-r--r--   0        0        0     1297 2023-06-28 12:07:29.582393 robocorp_log-2.0.0/pyproject.toml
+-rw-r--r--   0        0        0    31800 2023-06-28 12:07:29.582393 robocorp_log-2.0.0/src/robocorp/log/__init__.py
+-rw-r--r--   0        0        0    17958 2023-06-28 12:07:29.582393 robocorp_log-2.0.0/src/robocorp/log/_ast_utils.py
+-rw-r--r--   0        0        0    15297 2023-06-28 12:07:29.582393 robocorp_log-2.0.0/src/robocorp/log/_auto_logging_setup.py
+-rw-r--r--   0        0        0    10147 2023-06-28 12:07:29.582393 robocorp_log-2.0.0/src/robocorp/log/_config.py
+-rw-r--r--   0        0        0      696 2023-06-28 12:07:29.582393 robocorp_log-2.0.0/src/robocorp/log/_convert_units.py
+-rw-r--r--   0        0        0     7103 2023-06-28 12:07:29.582393 robocorp_log-2.0.0/src/robocorp/log/_decoder.py
+-rw-r--r--   0        0        0     7193 2023-06-28 12:07:29.582393 robocorp_log-2.0.0/src/robocorp/log/_decoder_spec.py
+-rw-r--r--   0        0        0   793089 2023-06-28 12:08:23.751030 robocorp_log-2.0.0/src/robocorp/log/_index_v3.py
+-rw-r--r--   0        0        0     7067 2023-06-28 12:07:29.582393 robocorp_log-2.0.0/src/robocorp/log/_lifecycle_hooks.py
+-rw-r--r--   0        0        0     1128 2023-06-28 12:07:29.582393 robocorp_log-2.0.0/src/robocorp/log/_logger_instances.py
+-rw-r--r--   0        0        0     1208 2023-06-28 12:07:29.582393 robocorp_log-2.0.0/src/robocorp/log/_null.py
+-rw-r--r--   0        0        0      759 2023-06-28 12:07:29.582393 robocorp_log-2.0.0/src/robocorp/log/_obj_info_repr.py
+-rw-r--r--   0        0        0      206 2023-06-28 12:07:29.582393 robocorp_log-2.0.0/src/robocorp/log/_on_exit_context_manager.py
+-rw-r--r--   0        0        0    32012 2023-06-28 12:07:29.582393 robocorp_log-2.0.0/src/robocorp/log/_rewrite_ast_add_callbacks.py
+-rw-r--r--   0        0        0     9217 2023-06-28 12:07:29.582393 robocorp_log-2.0.0/src/robocorp/log/_rewrite_filtering.py
+-rw-r--r--   0        0        0    12726 2023-06-28 12:07:29.582393 robocorp_log-2.0.0/src/robocorp/log/_rewrite_importhook.py
+-rw-r--r--   0        0        0    11686 2023-06-28 12:07:29.582393 robocorp_log-2.0.0/src/robocorp/log/_robo_logger.py
+-rw-r--r--   0        0        0    67823 2023-06-28 12:07:29.582393 robocorp_log-2.0.0/src/robocorp/log/_robo_output_impl.py
+-rw-r--r--   0        0        0     1436 2023-06-28 12:07:29.582393 robocorp_log-2.0.0/src/robocorp/log/_sensitive_variable_names.py
+-rw-r--r--   0        0        0     1915 2023-06-28 12:07:29.582393 robocorp_log-2.0.0/src/robocorp/log/_suppress_helper.py
+-rw-r--r--   0        0        0     7802 2023-06-28 12:07:29.582393 robocorp_log-2.0.0/src/robocorp/log/console.py
+-rw-r--r--   0        0        0     1147 2023-06-28 12:07:29.582393 robocorp_log-2.0.0/src/robocorp/log/protocols.py
+-rw-r--r--   0        0        0        0 2023-06-28 12:07:29.582393 robocorp_log-2.0.0/src/robocorp/log/py.typed
+-rw-r--r--   0        0        0     8025 2023-06-28 12:07:29.582393 robocorp_log-2.0.0/src/robocorp/log/redirect.py
+-rw-r--r--   0        0        0     6459 1970-01-01 00:00:00.000000 robocorp_log-2.0.0/PKG-INFO
```

### Comparing `robocorp_log-1.2.0/LICENSE` & `robocorp_log-2.0.0/LICENSE`

 * *Files identical despite different names*

### Comparing `robocorp_log-1.2.0/README.md` & `robocorp_log-2.0.0/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -65,16 +65,15 @@
 many places even if such code isn't in the source code (you may want to configure 
 the debugger you're using to skip calls into `robocorp.log` as that's usually
 just an implementation detail).
 
 2. The logging needs to be fully setup prior to importing any module that should 
 be automatically logged.
 
-3. `async` and `await` are not currently well supported (although it's already in
-the plans).
+3. Working with coroutines (`async`, `await` and `greenlet`) is not supported.
 
 
 ## Dealing with sensitive data in the logs
 
 By default `Robocorp Log` will show information for all method calls in user
 code as well as some selected libraries automatically.
```

### Comparing `robocorp_log-1.2.0/pyproject.toml` & `robocorp_log-2.0.0/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "robocorp-log"
-version = "1.2.0"
+version = "2.0.0"
 description = "Automatic trace logging for Python"
 authors = [
     "Fabio Zadrozny <fabio@robocorp.com>",
 ]
 readme = "README.md"
 repository = "https://github.com/robocorp/robo/"
 license = "Apache-2.0"
```

### Comparing `robocorp_log-1.2.0/src/robocorp/log/__init__.py` & `robocorp_log-2.0.0/src/robocorp/log/__init__.py`

 * *Files 2% similar despite different names*

```diff
@@ -29,36 +29,32 @@
 from ._logger_instances import _get_logger_instances
 from ._suppress_helper import SuppressHelper as _SuppressHelper
 from .protocols import IReadLines, LogHTMLStyle, OptExcInfo, Status
 
 if typing.TYPE_CHECKING:
     from ._robo_logger import _RoboLogger
 
-__version__ = "1.2.0"
+__version__ = "2.0.0"
 version_info = [int(x) for x in __version__.split(".")]
 
 from . import _config
 
 # --- Export parts of the public API below (imports above aren't part of
 # the public API).
 
 Filter = _config.Filter
 FilterKind = _config.FilterKind
 
-# TODO: BaseConfig isn't a good name. This should be something as
-# 'AutoLogBaseConfig`. Maybe rename and keep alias as backward compatibility?
-#
 # Note: clients are not meant to instance this class, it's just meant to be
 # available for typing.
-BaseConfig = _config.BaseConfig
+AutoLogConfigBase = _config.AutoLogConfigBase
 
-# Subclass of the BaseConfig. Clients are expected to instance it to
-# configure auto-logging. Maybe a better name would've been
-# 'DefaultAutoLogConfig'?.
-ConfigFilesFiltering = _config.ConfigFilesFiltering
+# Subclass of the AutoLogConfigBase. Clients are expected to instance it to
+# configure auto-logging.
+DefaultAutoLogConfig = _config.DefaultAutoLogConfig
 
 
 # --- Logging methods for custom messaging.
 
 
 def _log(level, message: Sequence[Any], html: bool = False) -> None:
     back_frame = sys._getframe(2)
@@ -874,15 +870,15 @@
         for k, v in prev_values.items():
             setattr(_config._general_log_config, k, v)
 
     return OnExitContextManager(on_exit)
 
 
 def setup_auto_logging(
-    config: Optional[BaseConfig] = None, add_rewrite_hook: bool = True
+    config: Optional[AutoLogConfigBase] = None, add_rewrite_hook: bool = True
 ):
     """
     Sets up automatic logging.
 
     This must be called prior to actually importing the modules which should
     be automatically logged.
 
@@ -896,18 +892,18 @@
 
     Returns a context manager which will stop applying the auto-logging to new
     loaded modules. Note that modules which are already being tracked won't
     stop being tracked.
     """
     from ._auto_logging_setup import register_auto_logging_callbacks
 
-    use_config: BaseConfig
+    use_config: AutoLogConfigBase
     if config is None:
         # If not passed, use default.
-        use_config = ConfigFilesFiltering()
+        use_config = DefaultAutoLogConfig()
     else:
         use_config = config
 
     return register_auto_logging_callbacks(use_config, add_rewrite_hook)
 
 
 def add_log_output(
```

### Comparing `robocorp_log-1.2.0/src/robocorp/log/_ast_utils.py` & `robocorp_log-2.0.0/src/robocorp/log/_ast_utils.py`

 * *Files identical despite different names*

### Comparing `robocorp_log-1.2.0/src/robocorp/log/_auto_logging_setup.py` & `robocorp_log-2.0.0/src/robocorp/log/_auto_logging_setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 import sys
 import threading
 from typing import Any, List, Optional, Sequence, Tuple
 
 from robocorp.log import critical, is_sensitive_variable_name
 
-from ._config import BaseConfig
+from ._config import AutoLogConfigBase
 from ._logger_instances import _get_logger_instances
 from ._obj_info_repr import get_obj_type_and_repr
 from ._on_exit_context_manager import OnExitContextManager
 from .protocols import LogElementType, OptExcInfo, Status
 
 
 def _get_obj_type_and_repr_and_hide_if_needed(key, val):
@@ -34,15 +34,15 @@
 
 class _AutoLogging:
     """
     Class responsible for listening for callbacks and then dispatching those
     to the logger.
     """
 
-    def __init__(self, rewrite_hook_config: BaseConfig) -> None:
+    def __init__(self, rewrite_hook_config: AutoLogConfigBase) -> None:
         from ._rewrite_importhook import RewriteHook
 
         self.tid = threading.get_ident()
         self.status_stack: List[_StackEntry] = []
         self._rewrite_hook_config = rewrite_hook_config
         self._hook: Optional[RewriteHook] = None
 
@@ -434,15 +434,15 @@
                 robo_logger.log_method_except(exc_info, unhandled=False)
 
     call_iterate_except = call_method_except
     call_iterate_step_except = call_method_except
 
 
 def register_auto_logging_callbacks(
-    rewrite_hook_config: BaseConfig, add_rewrite_hook: bool = True
+    rewrite_hook_config: AutoLogConfigBase, add_rewrite_hook: bool = True
 ):
     # Make sure that this method should be called only once.
     registered = getattr(register_auto_logging_callbacks, "registered", False)
     if registered:
         import warnings
 
         warnings.warn("Auto logging is already setup. 2nd call has no effect.")
```

### Comparing `robocorp_log-1.2.0/src/robocorp/log/_convert_units.py` & `robocorp_log-2.0.0/src/robocorp/log/_convert_units.py`

 * *Files identical despite different names*

### Comparing `robocorp_log-1.2.0/src/robocorp/log/_decoder.py` & `robocorp_log-2.0.0/src/robocorp/log/_decoder.py`

 * *Files identical despite different names*

### Comparing `robocorp_log-1.2.0/src/robocorp/log/_decoder_spec.py` & `robocorp_log-2.0.0/src/robocorp/log/_decoder_spec.py`

 * *Files identical despite different names*

### Comparing `robocorp_log-1.2.0/src/robocorp/log/_index_v3.py` & `robocorp_log-2.0.0/src/robocorp/log/_index_v3.py`

 * *Files identical despite different names*

### Comparing `robocorp_log-1.2.0/src/robocorp/log/_lifecycle_hooks.py` & `robocorp_log-2.0.0/src/robocorp/log/_lifecycle_hooks.py`

 * *Files 4% similar despite different names*

```diff
@@ -104,21 +104,21 @@
 iterate_step_except = Callback()
 
 # Called as: after_iterate(log_element_type, __name__, filename, name, lineno)
 after_iterate = Callback()
 
 
 def iter_all_callbacks() -> Iterator[Callback]:
-    for _key, val in tuple(globals().items()):
+    for _key, val in globals().copy().items():
         if isinstance(val, Callback):
             yield val
 
 
 def iter_all_name_and_callback() -> Iterator[Tuple[str, Callback]]:
-    for key, val in tuple(globals().items()):
+    for key, val in globals().copy().items():
         if isinstance(val, Callback):
             yield (key, val)
 
 
 _name_to_callback = {}
 for k, v in iter_all_name_and_callback():
     _name_to_callback[k] = v
```

### Comparing `robocorp_log-1.2.0/src/robocorp/log/_logger_instances.py` & `robocorp_log-2.0.0/src/robocorp/log/_logger_instances.py`

 * *Files identical despite different names*

### Comparing `robocorp_log-1.2.0/src/robocorp/log/_null.py` & `robocorp_log-2.0.0/src/robocorp/log/_null.py`

 * *Files identical despite different names*

### Comparing `robocorp_log-1.2.0/src/robocorp/log/_rewrite_ast_add_callbacks.py` & `robocorp_log-2.0.0/src/robocorp/log/_rewrite_ast_add_callbacks.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 import ast
 import types
 from typing import Any, Callable, Dict, List, Optional, Tuple, Union, Literal
 
 from ._ast_utils import ASTRewriter
-from ._config import BaseConfig, FilterKind
+from ._config import AutoLogConfigBase, FilterKind
 from .protocols import LogElementType
 
 DEBUG = False
 
 
 def is_rewrite_disabled(docstring: str) -> bool:
     return "NO_LOG" in docstring
@@ -163,83 +163,14 @@
             )
         ],
         body=function_body,
     )
     return with_stmt
 
 
-def _create_except_handler_ast(
-    rewrite_ctx: ASTRewriter,
-    factory,
-    class_name: str,
-    function: ast.FunctionDef,
-    last_body_lineno,
-    filter_kind: FilterKind,
-    log_method_type: LogElementType = "METHOD",
-    name: Optional[ast.Str] = None,
-    except_callback_name="method_except",
-) -> ast.ExceptHandler:
-    # Target code:
-    #     import sys as @py_sys
-    #     method_except(@py_sys.exc_info())
-    #     raise
-    #
-    # ExceptHandler
-    #   Import
-    #   Expr
-    #     Call
-    #       Name
-    #         Load
-    #       Call
-    #         Attribute
-    #           Name
-    #             Load
-    #           Load
-    #   Raise
-    aliases = [
-        ast.alias("sys", "@py_sys", lineno=last_body_lineno, col_offset=0),
-    ]
-
-    imports = [
-        ast.Import([alias], lineno=last_body_lineno, col_offset=0) for alias in aliases
-    ]
-
-    except_handler = factory.ExceptHandler()
-
-    if filter_kind == FilterKind.log_on_project_call:
-        if_stmt = factory.If(factory.NameLoad("@caller_in_proj"))
-        add_to_body = if_stmt.body = []
-        if_stmt.orelse = []
-        except_handler.body.append(if_stmt)
-    else:
-        add_to_body = except_handler.body
-
-    call_exc_info = factory.Call(
-        factory.Attribute(factory.NameLoad("@py_sys"), "exc_info")
-    )
-
-    call_method_except = factory.Call(
-        factory.NameLoadRewriteCallback(except_callback_name)
-    )
-    call_method_except.args.append(factory.Str(log_method_type))
-    call_method_except.args.append(factory.NameLoad("__name__"))
-    call_method_except.args.append(factory.NameLoad("__file__"))
-    call_method_except.args.append(
-        name if name is not None else factory.Str(f"{class_name}{function.name}")
-    )
-    call_method_except.args.append(factory.LineConstant())
-    call_method_except.args.append(call_exc_info)
-
-    add_to_body.extend(imports)
-    add_to_body.append(factory.Expr(call_method_except))
-
-    except_handler.body.append(factory.Raise())
-    return except_handler
-
-
 AcceptedCases = Literal[
     # Only when full logging is available for a function.
     "full_log",
     # Can be used on external libraries when the function is called from the user code.
     "log_on_project_call",
     # Can be used for generators being tracked (used for things which don't add to the stack internally)
     # i.e.: for loop can't use it but an assign can.
@@ -349,15 +280,15 @@
 
 
 def rewrite_ast_add_callbacks(
     mod: ast.Module,
     filter_kind: FilterKind,
     source: bytes,
     module_path: str,
-    config: BaseConfig,
+    config: AutoLogConfigBase,
 ) -> None:
     """Rewrite the module as needed so that the logging is done automatically."""
 
     if not mod.body:
         # Nothing to do.
         return
 
@@ -504,15 +435,22 @@
             node.value = factory.NameLoad(store_name.id)
 
             result.append(assign)
             call.args.append(factory.NameLoad(store_name.id))
         else:
             call.args.append(factory.NoneConstant())
 
-        result.append(factory.Expr(call))
+        if filter_kind == FilterKind.log_on_project_call:
+            result.append(
+                factory.AndExpr(
+                    factory.Attribute(factory.NameLoad("@ctx"), "_accept"), call
+                )
+            )
+        else:
+            result.append(factory.Expr(call))
         result.append(node)
         return result
     except Exception:
         raise RuntimeError(
             f"Error when rewriting function return: {function.name} line: {node.lineno} at: {module_path}"
         )
 
@@ -578,15 +516,20 @@
     except Exception:
         raise RuntimeError(
             f"Error when rewriting function return: {function.name} line: {node.lineno} at: {module_path}"
         )
 
 
 def _handle_assign(
-    rewrite_ctx: ASTRewriter, config: BaseConfig, module_path, stack, filter_kind, node
+    rewrite_ctx: ASTRewriter,
+    config: AutoLogConfigBase,
+    module_path,
+    stack,
+    filter_kind,
+    node,
 ):
     if filter_kind != FilterKind.full_log or not config.get_rewrite_assigns():
         return None
 
     func_and_class_name = _get_function_and_class_name(stack)
     if not func_and_class_name:
         return None
@@ -1047,20 +990,24 @@
         raise RuntimeError(
             f"Error when rewriting yield: {function.name} line: {node.lineno} at: {module_path}"
         )
 
 
 _dispatch_before: Dict[
     type,
-    Callable[[ASTRewriter, BaseConfig, str, list, FilterKind, Any], Optional[list]],
+    Callable[
+        [ASTRewriter, AutoLogConfigBase, str, list, FilterKind, Any], Optional[list]
+    ],
 ] = {}
 
 _dispatch_after: Dict[
     type,
-    Callable[[ASTRewriter, BaseConfig, str, list, FilterKind, Any], Optional[list]],
+    Callable[
+        [ASTRewriter, AutoLogConfigBase, str, list, FilterKind, Any], Optional[list]
+    ],
 ] = {}
 
 _dispatch_after[ast.Return] = _handle_return
 _dispatch_after[ast.Assign] = _handle_assign
 _dispatch_after[ast.FunctionDef] = _handle_funcdef
 _dispatch_after[ast.Yield] = _handle_yield
 _dispatch_after[ast.YieldFrom] = _handle_yield
```

### Comparing `robocorp_log-1.2.0/src/robocorp/log/_rewrite_filtering.py` & `robocorp_log-2.0.0/src/robocorp/log/_rewrite_filtering.py`

 * *Files identical despite different names*

### Comparing `robocorp_log-1.2.0/src/robocorp/log/_rewrite_importhook.py` & `robocorp_log-2.0.0/src/robocorp/log/_rewrite_importhook.py`

 * *Files 2% similar despite different names*

```diff
@@ -30,15 +30,15 @@
 import os
 import struct
 import sys
 import types
 from pathlib import Path
 from typing import IO, Callable, Dict, Optional, Sequence, Tuple, Union
 
-from ._config import BaseConfig, FilterKind
+from ._config import AutoLogConfigBase, FilterKind
 
 # caches rewritten pycs in pycache dirs
 # 0.0.1: Initial version
 # 0.0.2: Bugfix: docstrings must be kept as the first statement
 # 0.0.3: Support for exception handlers
 # 0.0.4: Add __name__
 # 0.0.5: Renames of internal modules.
@@ -50,15 +50,16 @@
 # 0.0.12: Changed to use robocorp namespace.
 # 0.0.13: Changed to use robocorp.log name.
 # 0.0.14: Rewrite yield from
 # 0.0.15: Rewrite for
 # 0.0.16: Rewrite for without try..except
 # 0.0.17: Rewrite while
 # 0.0.18: Fixes in generation based on scoping (generator/untracked_generator,full_log,log_on_project_call).
-version = "0.0.18"
+# 0.0.19: Fixed return with log_on_project_call.
+version = "0.0.19"
 NAME_WITH_TAG = f"{sys.implementation.cache_tag}-log-{version}"
 PYC_EXT = ".py" + (__debug__ and "c" or "o")
 PYC_TAIL = "." + NAME_WITH_TAG + PYC_EXT
 
 FORCE_CODE_GENERATION = False
 DEBUG = False
 
@@ -73,15 +74,15 @@
     def trace(msg):
         pass
 
 
 class RewriteHook(importlib.abc.MetaPathFinder, importlib.abc.Loader):
     """PEP302/PEP451 import hook which rewrites asserts."""
 
-    def __init__(self, config: BaseConfig) -> None:
+    def __init__(self, config: AutoLogConfigBase) -> None:
         self.config = config
         self._rewritten_names: Dict[str, Path] = {}
         # flag to guard against trying to rewrite a pyc file while we are already writing another pyc file,
         # which might result in infinite recursion (#3506)
         self._writing_pyc = False
 
     # Indirection so we can mock calls to find_spec originated from the hook during testing
@@ -163,15 +164,15 @@
                 write = False
                 trace(f"read only directory: {cache_dir}")
 
         filter_kind: FilterKind = self.config.get_filter_kind_by_module_name_and_path(
             module.__name__, module.__spec__.origin
         )
 
-        cache_name = fn.name[:-3] + filter_kind.value + PYC_TAIL
+        cache_name = fn.name[:-3] + "-" + filter_kind.value + PYC_TAIL
 
         pyc = cache_dir / cache_name
         # Notice that even if we're in a read-only directory, I'm going
         # to check for a cached pyc. This may not be optimal...
         if FORCE_CODE_GENERATION:
             co = None
         else:
@@ -250,15 +251,15 @@
         # there are many reasons, permission-denied, pycache dir being a
         # file etc.
         return False
     return True
 
 
 def _rewrite(
-    fn: Path, config: BaseConfig, filter_kind: FilterKind
+    fn: Path, config: AutoLogConfigBase, filter_kind: FilterKind
 ) -> Tuple[os.stat_result, types.CodeType, ast.AST]:
     """Read and rewrite *fn* and return the code object."""
     from ._rewrite_ast_add_callbacks import rewrite_ast_add_callbacks
 
     stat = os.stat(fn)
     source = fn.read_bytes()
     strfn = str(fn)
```

### Comparing `robocorp_log-1.2.0/src/robocorp/log/_robo_logger.py` & `robocorp_log-2.0.0/src/robocorp/log/_robo_logger.py`

 * *Files identical despite different names*

### Comparing `robocorp_log-1.2.0/src/robocorp/log/_robo_output_impl.py` & `robocorp_log-2.0.0/src/robocorp/log/_robo_output_impl.py`

 * *Files 0% similar despite different names*

```diff
@@ -646,14 +646,16 @@
                 [
                     oid("Process snapshot"),
                     robot_impl._number(self.time_delta),
                 ],
             ),
 
     def process_snapshot(self, hide_vars: bool) -> None:
+        from robocorp import log
+
         self._rotate_if_needed()
 
         entry_id = f"ps_{self._next_int()}"
         entry_type = "process_snapshot"
 
         self._stack_handler.push_record(
             entry_type,
@@ -661,79 +663,83 @@
             "SPS",
             "RPS",
             False,
             self._WriteProcessSnapshot(self.get_time_delta()),
         )
 
         try:
-            try:
-                import psutil
-                from psutil import AccessDenied, NoSuchProcess, ZombieProcess
-            except ImportError:
-                pass
-            else:
-                curr_process = psutil.Process()
-
-                def log_info(message):
-                    self.log_message(
-                        "I", message, False, "", "", "", 0, self.get_time_delta()
-                    )
+            with log.suppress():
+                # We don't want to see calls from psutil in case it's
+                # being tracked.
 
-                memory_info = "<unknown>"
                 try:
-                    memory_info = format_memory_info(psutil.virtual_memory())
-                    memory_info = format_memory_info(psutil.virtual_memory())
-                except:
+                    import psutil
+                    from psutil import AccessDenied, NoSuchProcess, ZombieProcess
+                except ImportError:
                     pass
+                else:
+                    curr_process = psutil.Process()
+
+                    def log_info(message):
+                        self.log_message(
+                            "I", message, False, "", "", "", 0, self.get_time_delta()
+                        )
+
+                    memory_info = "<unknown>"
+                    try:
+                        memory_info = format_memory_info(psutil.virtual_memory())
+                        memory_info = format_memory_info(psutil.virtual_memory())
+                    except:
+                        pass
 
-                log_info(
-                    f"""System information:
+                    log_info(
+                        f"""System information:
 Memory: {memory_info}
 CPUs: {os.cpu_count()}"""
-                )
-
-                for child_i, child in enumerate(
-                    itertools.chain(
-                        [curr_process], curr_process.children(recursive=True)
                     )
-                ):
-                    name = "<unknown>"
-                    status = "<unknown>"
-                    create_time = "<unknown>"
-                    ppid = "<unknown>"
-                    cmdline = "<unknown>"
-                    rss = "<unknown>"
-                    vms = "<unknown>"
 
-                    try:
-                        with child.oneshot():
-                            try:
-                                name = child.name()
-                                status = child.status()
+                    for child_i, child in enumerate(
+                        itertools.chain(
+                            [curr_process], curr_process.children(recursive=True)
+                        )
+                    ):
+                        name = "<unknown>"
+                        status = "<unknown>"
+                        create_time = "<unknown>"
+                        ppid = "<unknown>"
+                        cmdline = "<unknown>"
+                        rss = "<unknown>"
+                        vms = "<unknown>"
+
+                        try:
+                            with child.oneshot():
                                 try:
-                                    create_time = _pprint_secs(child.create_time())
-                                except:
+                                    name = child.name()
+                                    status = child.status()
+                                    try:
+                                        create_time = _pprint_secs(child.create_time())
+                                    except:
+                                        pass
+                                    ppid = str(child.ppid())
+                                    cmdline = " ".join(child.cmdline())
+                                    proc_memory_info = child.memory_info()
+                                    rss = bytes2human(proc_memory_info.rss)
+                                    vms = bytes2human(proc_memory_info.vms)
+                                except ZombieProcess:
+                                    status = "zombie"
+                                except NoSuchProcess:
+                                    status = "terminated"
+                                except AccessDenied:
                                     pass
-                                ppid = str(child.ppid())
-                                cmdline = " ".join(child.cmdline())
-                                proc_memory_info = child.memory_info()
-                                rss = bytes2human(proc_memory_info.rss)
-                                vms = bytes2human(proc_memory_info.vms)
-                            except ZombieProcess:
-                                status = "zombie"
-                            except NoSuchProcess:
-                                status = "terminated"
-                            except AccessDenied:
-                                pass
-                            except Exception:
-                                pass
-                    except:
-                        pass
+                                except Exception:
+                                    pass
+                        except:
+                            pass
 
-                    message = f"""{"Subprocess" if child_i > 0 else "Current Process"}: {name} (pid: {child.pid}, status: {status})
+                        message = f"""{"Subprocess" if child_i > 0 else "Current Process"}: {name} (pid: {child.pid}, status: {status})
 Command Line: {cmdline}
 Started: {create_time}
 Parent pid: {ppid}
 Resident Set Size: {rss}
 Virtual Memory Size: {vms}"""
                     log_info(message)
```

### Comparing `robocorp_log-1.2.0/src/robocorp/log/_sensitive_variable_names.py` & `robocorp_log-2.0.0/src/robocorp/log/_sensitive_variable_names.py`

 * *Files identical despite different names*

### Comparing `robocorp_log-1.2.0/src/robocorp/log/_suppress_helper.py` & `robocorp_log-2.0.0/src/robocorp/log/_suppress_helper.py`

 * *Files identical despite different names*

### Comparing `robocorp_log-1.2.0/src/robocorp/log/console.py` & `robocorp_log-2.0.0/src/robocorp/log/console.py`

 * *Files identical despite different names*

### Comparing `robocorp_log-1.2.0/src/robocorp/log/protocols.py` & `robocorp_log-2.0.0/src/robocorp/log/protocols.py`

 * *Files identical despite different names*

### Comparing `robocorp_log-1.2.0/src/robocorp/log/redirect.py` & `robocorp_log-2.0.0/src/robocorp/log/redirect.py`

 * *Files identical despite different names*

### Comparing `robocorp_log-1.2.0/PKG-INFO` & `robocorp_log-2.0.0/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: robocorp-log
-Version: 1.2.0
+Version: 2.0.0
 Summary: Automatic trace logging for Python
 Home-page: https://github.com/robocorp/robo/
 License: Apache-2.0
 Author: Fabio Zadrozny
 Author-email: fabio@robocorp.com
 Requires-Python: >=3.9,<4.0
 Classifier: Development Status :: 4 - Beta
@@ -87,16 +87,15 @@
 many places even if such code isn't in the source code (you may want to configure 
 the debugger you're using to skip calls into `robocorp.log` as that's usually
 just an implementation detail).
 
 2. The logging needs to be fully setup prior to importing any module that should 
 be automatically logged.
 
-3. `async` and `await` are not currently well supported (although it's already in
-the plans).
+3. Working with coroutines (`async`, `await` and `greenlet`) is not supported.
 
 
 ## Dealing with sensitive data in the logs
 
 By default `Robocorp Log` will show information for all method calls in user
 code as well as some selected libraries automatically.
```


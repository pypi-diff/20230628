# Comparing `tmp/tritondse-0.1.3.tar.gz` & `tmp/tritondse-0.1.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "tritondse-0.1.3.tar", last modified: Tue May 16 08:02:40 2023, max compression
+gzip compressed data, was "tritondse-0.1.4.tar", last modified: Wed Jun 28 14:11:11 2023, max compression
```

## Comparing `tritondse-0.1.3.tar` & `tritondse-0.1.4.tar`

### file list

```diff
@@ -1,43 +1,43 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-16 08:02:40.786338 tritondse-0.1.3/
--rwxr-xr-x   0 runner    (1001) docker     (123)    11357 2023-05-16 08:02:33.000000 tritondse-0.1.3/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     3202 2023-05-16 08:02:40.786338 tritondse-0.1.3/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2613 2023-05-16 08:02:33.000000 tritondse-0.1.3/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-05-16 08:02:40.786338 tritondse-0.1.3/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     1137 2023-05-16 08:02:33.000000 tritondse-0.1.3/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-16 08:02:40.786338 tritondse-0.1.3/tritondse/
--rw-r--r--   0 runner    (1001) docker     (123)     1136 2023-05-16 08:02:33.000000 tritondse-0.1.3/tritondse/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4986 2023-05-16 08:02:33.000000 tritondse-0.1.3/tritondse/arch.py
--rw-r--r--   0 runner    (1001) docker     (123)    36097 2023-05-16 08:02:33.000000 tritondse-0.1.3/tritondse/callbacks.py
--rw-r--r--   0 runner    (1001) docker     (123)     8020 2023-05-16 08:02:33.000000 tritondse-0.1.3/tritondse/config.py
--rw-r--r--   0 runner    (1001) docker     (123)    29656 2023-05-16 08:02:33.000000 tritondse-0.1.3/tritondse/coverage.py
--rw-r--r--   0 runner    (1001) docker     (123)     1147 2023-05-16 08:02:33.000000 tritondse-0.1.3/tritondse/exception.py
--rw-r--r--   0 runner    (1001) docker     (123)     4605 2023-05-16 08:02:33.000000 tritondse-0.1.3/tritondse/heap_allocator.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-16 08:02:40.786338 tritondse-0.1.3/tritondse/loaders/
--rw-r--r--   0 runner    (1001) docker     (123)      148 2023-05-16 08:02:33.000000 tritondse-0.1.3/tritondse/loaders/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     7844 2023-05-16 08:02:33.000000 tritondse-0.1.3/tritondse/loaders/cle_loader.py
--rw-r--r--   0 runner    (1001) docker     (123)     6381 2023-05-16 08:02:33.000000 tritondse-0.1.3/tritondse/loaders/loader.py
--rw-r--r--   0 runner    (1001) docker     (123)     9260 2023-05-16 08:02:33.000000 tritondse-0.1.3/tritondse/loaders/program.py
--rw-r--r--   0 runner    (1001) docker     (123)     4297 2023-05-16 08:02:33.000000 tritondse-0.1.3/tritondse/loaders/quokkaprogram.py
--rw-r--r--   0 runner    (1001) docker     (123)    22801 2023-05-16 08:02:33.000000 tritondse-0.1.3/tritondse/memory.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-16 08:02:40.786338 tritondse-0.1.3/tritondse/probes/
--rwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-16 08:02:33.000000 tritondse-0.1.3/tritondse/probes/__init__.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     2008 2023-05-16 08:02:33.000000 tritondse-0.1.3/tritondse/probes/basic_trace.py
--rw-r--r--   0 runner    (1001) docker     (123)    50962 2023-05-16 08:02:33.000000 tritondse-0.1.3/tritondse/process_state.py
--rw-r--r--   0 runner    (1001) docker     (123)     6867 2023-05-16 08:02:33.000000 tritondse-0.1.3/tritondse/qbdi_trace.py
--rw-r--r--   0 runner    (1001) docker     (123)    75538 2023-05-16 08:02:33.000000 tritondse-0.1.3/tritondse/routines.py
--rw-r--r--   0 runner    (1001) docker     (123)    12351 2023-05-16 08:02:33.000000 tritondse-0.1.3/tritondse/sanitizers.py
--rw-r--r--   0 runner    (1001) docker     (123)     9055 2023-05-16 08:02:33.000000 tritondse-0.1.3/tritondse/seed.py
--rw-r--r--   0 runner    (1001) docker     (123)    18501 2023-05-16 08:02:33.000000 tritondse-0.1.3/tritondse/seeds_manager.py
--rw-r--r--   0 runner    (1001) docker     (123)    35948 2023-05-16 08:02:33.000000 tritondse-0.1.3/tritondse/symbolic_executor.py
--rw-r--r--   0 runner    (1001) docker     (123)    10759 2023-05-16 08:02:33.000000 tritondse-0.1.3/tritondse/symbolic_explorator.py
--rw-r--r--   0 runner    (1001) docker     (123)     3939 2023-05-16 08:02:33.000000 tritondse-0.1.3/tritondse/thread_context.py
--rw-r--r--   0 runner    (1001) docker     (123)     6881 2023-05-16 08:02:33.000000 tritondse-0.1.3/tritondse/trace.py
--rw-r--r--   0 runner    (1001) docker     (123)     6149 2023-05-16 08:02:33.000000 tritondse-0.1.3/tritondse/types.py
--rw-r--r--   0 runner    (1001) docker     (123)    11555 2023-05-16 08:02:33.000000 tritondse-0.1.3/tritondse/worklist.py
--rw-r--r--   0 runner    (1001) docker     (123)     7754 2023-05-16 08:02:33.000000 tritondse-0.1.3/tritondse/workspace.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-16 08:02:40.786338 tritondse-0.1.3/tritondse.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     3202 2023-05-16 08:02:40.000000 tritondse-0.1.3/tritondse.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      898 2023-05-16 08:02:40.000000 tritondse-0.1.3/tritondse.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-05-16 08:02:40.000000 tritondse-0.1.3/tritondse.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       57 2023-05-16 08:02:40.000000 tritondse-0.1.3/tritondse.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       10 2023-05-16 08:02:40.000000 tritondse-0.1.3/tritondse.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:11:11.890111 tritondse-0.1.4/
+-rw-r--r--   0 runner    (1001) docker     (123)    11357 2023-06-28 14:11:06.000000 tritondse-0.1.4/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     3202 2023-06-28 14:11:11.890111 tritondse-0.1.4/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2613 2023-06-28 14:11:06.000000 tritondse-0.1.4/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 14:11:11.890111 tritondse-0.1.4/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1137 2023-06-28 14:11:06.000000 tritondse-0.1.4/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:11:11.890111 tritondse-0.1.4/tritondse/
+-rw-r--r--   0 runner    (1001) docker     (123)     1136 2023-06-28 14:11:06.000000 tritondse-0.1.4/tritondse/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4986 2023-06-28 14:11:06.000000 tritondse-0.1.4/tritondse/arch.py
+-rw-r--r--   0 runner    (1001) docker     (123)    36097 2023-06-28 14:11:06.000000 tritondse-0.1.4/tritondse/callbacks.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8020 2023-06-28 14:11:06.000000 tritondse-0.1.4/tritondse/config.py
+-rw-r--r--   0 runner    (1001) docker     (123)    29656 2023-06-28 14:11:06.000000 tritondse-0.1.4/tritondse/coverage.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1147 2023-06-28 14:11:06.000000 tritondse-0.1.4/tritondse/exception.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4605 2023-06-28 14:11:06.000000 tritondse-0.1.4/tritondse/heap_allocator.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:11:11.890111 tritondse-0.1.4/tritondse/loaders/
+-rw-r--r--   0 runner    (1001) docker     (123)      148 2023-06-28 14:11:06.000000 tritondse-0.1.4/tritondse/loaders/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7844 2023-06-28 14:11:06.000000 tritondse-0.1.4/tritondse/loaders/cle_loader.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6381 2023-06-28 14:11:06.000000 tritondse-0.1.4/tritondse/loaders/loader.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9260 2023-06-28 14:11:06.000000 tritondse-0.1.4/tritondse/loaders/program.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4297 2023-06-28 14:11:06.000000 tritondse-0.1.4/tritondse/loaders/quokkaprogram.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22801 2023-06-28 14:11:06.000000 tritondse-0.1.4/tritondse/memory.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:11:11.890111 tritondse-0.1.4/tritondse/probes/
+-rwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:11:06.000000 tritondse-0.1.4/tritondse/probes/__init__.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     2008 2023-06-28 14:11:06.000000 tritondse-0.1.4/tritondse/probes/basic_trace.py
+-rw-r--r--   0 runner    (1001) docker     (123)    50962 2023-06-28 14:11:06.000000 tritondse-0.1.4/tritondse/process_state.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8302 2023-06-28 14:11:06.000000 tritondse-0.1.4/tritondse/qbdi_trace.py
+-rw-r--r--   0 runner    (1001) docker     (123)    75538 2023-06-28 14:11:06.000000 tritondse-0.1.4/tritondse/routines.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12351 2023-06-28 14:11:06.000000 tritondse-0.1.4/tritondse/sanitizers.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9055 2023-06-28 14:11:06.000000 tritondse-0.1.4/tritondse/seed.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18501 2023-06-28 14:11:06.000000 tritondse-0.1.4/tritondse/seeds_manager.py
+-rw-r--r--   0 runner    (1001) docker     (123)    35948 2023-06-28 14:11:06.000000 tritondse-0.1.4/tritondse/symbolic_executor.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10759 2023-06-28 14:11:06.000000 tritondse-0.1.4/tritondse/symbolic_explorator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3939 2023-06-28 14:11:06.000000 tritondse-0.1.4/tritondse/thread_context.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6829 2023-06-28 14:11:06.000000 tritondse-0.1.4/tritondse/trace.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6149 2023-06-28 14:11:06.000000 tritondse-0.1.4/tritondse/types.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11555 2023-06-28 14:11:06.000000 tritondse-0.1.4/tritondse/worklist.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7754 2023-06-28 14:11:06.000000 tritondse-0.1.4/tritondse/workspace.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:11:11.890111 tritondse-0.1.4/tritondse.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     3202 2023-06-28 14:11:11.000000 tritondse-0.1.4/tritondse.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      898 2023-06-28 14:11:11.000000 tritondse-0.1.4/tritondse.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 14:11:11.000000 tritondse-0.1.4/tritondse.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       57 2023-06-28 14:11:11.000000 tritondse-0.1.4/tritondse.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       10 2023-06-28 14:11:11.000000 tritondse-0.1.4/tritondse.egg-info/top_level.txt
```

### Comparing `tritondse-0.1.3/LICENSE` & `tritondse-0.1.4/LICENSE`

 * *Files identical despite different names*

### Comparing `tritondse-0.1.3/PKG-INFO` & `tritondse-0.1.4/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: tritondse
-Version: 0.1.3
+Version: 0.1.4
 Summary: A library of Dynamic Symbolic Exploration based the Triton library
 Home-page: https://github.com/quarkslab/tritondse
 Author: Quarkslab
 License: AGPL-3.0
 Project-URL: Documentation, https://quarkslab.github.io/tritondse/
 Project-URL: Bug Tracker, https://github.com/quarkslab/tritondse/issues
 Project-URL: Source, https://github.com/quarkslab/tritondse
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: tritondse Version: 0.1.3 Summary: A library of
+Metadata-Version: 2.1 Name: tritondse Version: 0.1.4 Summary: A library of
 Dynamic Symbolic Exploration based the Triton library Home-page: https://
 github.com/quarkslab/tritondse Author: Quarkslab License: AGPL-3.0 Project-URL:
 Documentation, https://quarkslab.github.io/tritondse/ Project-URL: Bug Tracker,
 https://github.com/quarkslab/tritondse/issues Project-URL: Source, https://
 github.com/quarkslab/tritondse Classifier: Topic :: Security Classifier:
 Environment :: Console Classifier: Operating System :: OS Independent
 Description-Content-Type: text/markdown License-File: LICENSE # TritonDSE
```

### Comparing `tritondse-0.1.3/README.md` & `tritondse-0.1.4/README.md`

 * *Files identical despite different names*

### Comparing `tritondse-0.1.3/setup.py` & `tritondse-0.1.4/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -9,15 +9,15 @@
 
 with open("README.md") as f:
     README = f.read()
 
 
 setup(
     name="tritondse",
-    version="0.1.3",
+    version="0.1.4",
     description="A library of Dynamic Symbolic Exploration based the Triton library",
     packages=find_packages(),
     long_description=README,
     long_description_content_type='text/markdown',
     url="https://github.com/quarkslab/tritondse",
     project_urls={
         "Documentation": "https://quarkslab.github.io/tritondse/",
```

### Comparing `tritondse-0.1.3/tritondse/__init__.py` & `tritondse-0.1.4/tritondse/__init__.py`

 * *Files identical despite different names*

### Comparing `tritondse-0.1.3/tritondse/arch.py` & `tritondse-0.1.4/tritondse/arch.py`

 * *Files identical despite different names*

### Comparing `tritondse-0.1.3/tritondse/callbacks.py` & `tritondse-0.1.4/tritondse/callbacks.py`

 * *Files identical despite different names*

### Comparing `tritondse-0.1.3/tritondse/config.py` & `tritondse-0.1.4/tritondse/config.py`

 * *Files identical despite different names*

### Comparing `tritondse-0.1.3/tritondse/coverage.py` & `tritondse-0.1.4/tritondse/coverage.py`

 * *Files identical despite different names*

### Comparing `tritondse-0.1.3/tritondse/exception.py` & `tritondse-0.1.4/tritondse/exception.py`

 * *Files identical despite different names*

### Comparing `tritondse-0.1.3/tritondse/heap_allocator.py` & `tritondse-0.1.4/tritondse/heap_allocator.py`

 * *Files identical despite different names*

### Comparing `tritondse-0.1.3/tritondse/loaders/cle_loader.py` & `tritondse-0.1.4/tritondse/loaders/cle_loader.py`

 * *Files identical despite different names*

### Comparing `tritondse-0.1.3/tritondse/loaders/loader.py` & `tritondse-0.1.4/tritondse/loaders/loader.py`

 * *Files identical despite different names*

### Comparing `tritondse-0.1.3/tritondse/loaders/program.py` & `tritondse-0.1.4/tritondse/loaders/program.py`

 * *Files identical despite different names*

### Comparing `tritondse-0.1.3/tritondse/loaders/quokkaprogram.py` & `tritondse-0.1.4/tritondse/loaders/quokkaprogram.py`

 * *Files identical despite different names*

### Comparing `tritondse-0.1.3/tritondse/memory.py` & `tritondse-0.1.4/tritondse/memory.py`

 * *Files identical despite different names*

### Comparing `tritondse-0.1.3/tritondse/probes/basic_trace.py` & `tritondse-0.1.4/tritondse/probes/basic_trace.py`

 * *Files identical despite different names*

### Comparing `tritondse-0.1.3/tritondse/process_state.py` & `tritondse-0.1.4/tritondse/process_state.py`

 * *Files identical despite different names*

### Comparing `tritondse-0.1.3/tritondse/qbdi_trace.py` & `tritondse-0.1.4/tritondse/qbdi_trace.py`

 * *Files 16% similar despite different names*

```diff
@@ -1,37 +1,104 @@
 # This script is used by pyqbdipreload to generate a json file that can be parsed with CoverageSingleRun.from_json
 # This needs to be fast which is why we cannot import tritondse and generate the CoverageSingleRun directly 
 # (`import tritondse` adds ~0.3 s to the execution time of the script in my experience).
 
 # built-in modules
 import atexit
 import bisect
-import os
+import ctypes
+import ctypes.util
 import json
+import lief
+import os
+import sys
 import time
-import ctypes
-from pathlib import Path
-from typing import List, Optional, Tuple, Dict
+
 from collections import Counter
 from dataclasses import dataclass
-import lief
-import sys
+from typing import List, Optional, Tuple, Dict
 
 # Third-party modules
 import pyqbdi
 
 
+setjmp_data = {}
+libdl = None
+
+
+class Dl_info(ctypes.Structure):
+    _fields_ = [
+        ('dli_fname', ctypes.c_char_p),
+        ('dli_fbase', ctypes.c_void_p),
+        ('dli_sname', ctypes.c_char_p),
+        ('dli_saddr', ctypes.c_void_p)
+    ]
+
+
+def dladdr(addr):
+    res = Dl_info()
+    libdl.dladdr(ctypes.cast(addr, ctypes.c_void_p), ctypes.byref(res))
+
+    return res.dli_sname
+
+
+def is_symbol(name, addr):
+    sname = dladdr(addr)
+    sname = sname.decode() if sname else ""
+
+    return sname == name
+
+
+def hook_post_setjmp(vm, state, gpr, fpr, data):
+    setjmp_data[data]['rip'] = gpr.rip
+
+    if setjmp_data[data]['setjmp_cbk_id'] is not None:
+        vm.deleteInstrumentation(setjmp_data[data]['setjmp_cbk_id'])
+        setjmp_data[data]['setjmp_cbk_id'] = None
+
+    return pyqbdi.CONTINUE
+
+
+def hook_post_longjmp(vm, state, gpr, fpr, data):
+    if data in setjmp_data:
+        gpr.rip = setjmp_data[data]['rip']
+    else:
+        print(f'[FATAL] longjmp arg ({data:x}) not found!')
+        sys.exit(-1)
+
+    if setjmp_data[data]['longjmp_cbk_id'] is not None:
+        vm.deleteInstrumentation(setjmp_data[data]['longjmp_cbk_id'])
+        setjmp_data[data]['longjmp_cbk_id'] = None
+
+    return pyqbdi.CONTINUE
+
+
+def handle_exec_transfer_call(vm, state, gpr, fpr, data):
+    if is_symbol("_setjmp", gpr.rip):
+        arg1 = gpr.rdi      # get env argument.
+
+        setjmp_data[arg1] = {}
+        setjmp_data[arg1]['setjmp_cbk_id'] = vm.addVMEventCB(pyqbdi.EXEC_TRANSFER_RETURN, hook_post_setjmp, arg1)
+    elif is_symbol("longjmp", gpr.rip):
+        arg1 = gpr.rdi      # get env argument.
+
+        setjmp_data[arg1]['longjmp_cbk_id'] = vm.addVMEventCB(pyqbdi.EXEC_TRANSFER_RETURN, hook_post_longjmp, arg1)
+
+    return pyqbdi.CONTINUE
+
+
 @dataclass
 class CoverageTrace:
     strategy: str  # BLOCK, EDGE, etc..
     covered_instructions: Counter
     covered_items: List[Tuple[int, int, Optional[int]]]
     modules: Dict[str, int]
     trace: List[int]
 
+
 @dataclass
 class CoverageData:
     strategy: str  # BLOCK, EDGE, etc..
     branch_data: Optional[Tuple[int, int, int, bool, bool]]  # (temporary data): branch pc, true-branch, false-branch, is_taken, is_dynamic
     trace: CoverageTrace
     modules_base: List[int]
     pie: bool
@@ -40,26 +107,26 @@
     def to_relative(self, addr: int) -> int:
         if self.pie:
             return addr - self.modules_base[bisect.bisect_right(self.modules_base, addr)-1]
         else:
             return addr
 
 
-
 def get_modules() -> Dict[str, int]:
     """ Retrieve modules base address to remove ASLR. """
     modules = {}
     for m in pyqbdi.getCurrentProcessMaps(True):
         if m.name in modules:
             modules[m.name] = min(m.range[0], modules[m.name])
         else:
             modules[m.name] = m.range[0]
         # print(f"{m.name}: {m.range}, {m.permission}")
     return modules
 
+
 def get_module_bases() -> List[int]:
     """ Retrieve modules base address to remove ASLR. """
     return sorted(get_modules().values())
 
 
 def write_coverage(covdata: CoverageData, output_file: str):
     """Write coverage into a file.
@@ -132,17 +199,26 @@
 
     # Save current branch data
     data.branch_data = (branch_addr, true_branch_addr, false_branch_addr, None, False)
 
     return pyqbdi.CONTINUE
 
 
-
 def pyqbdipreload_on_run(vm, start, stop):
+    global libdl
+
     s = time.time()
+
+    # Load dl library.
+    libdl_path = ctypes.util.find_library('dl')
+    if libdl_path is None:
+        raise Exception('Unable to found dl library')
+    libdl = ctypes.cdll.LoadLibrary(libdl_path)
+    libdl.dladdr.argtypes = (ctypes.c_void_p, ctypes.POINTER(Dl_info))
+
     # Read parameters.
     strat = os.getenv('PYQBDIPRELOAD_COVERAGE_STRATEGY', 'BLOCK')
     output = os.getenv('PYQBDIPRELOAD_OUTPUT_FILEPATH', 'a.cov')
     bool_trace = os.getenv('PYQBDIPRELOAD_DUMP_TRACE', 'False')
     bool_trace = True if bool_trace in ['true', 'True'] else False
 
     mods = get_modules()
@@ -168,28 +244,14 @@
     # Add callback on the JCC mnemonic.
     vm.addMnemonicCB('JCC', pyqbdi.InstPosition.POSTINST, register_branch_coverage, coverage_data)
 
     # Write coverage on exit.
     # TODO This does not work with bins that crash.
     atexit.register(write_coverage, coverage_data, output)
 
-    # TODO Find a better way
-    # There is no generic way to do that with LIEF https://github.com/lief-project/LIEF/issues/762
-    longjmp_plt = int(os.getenv("PYQBDIPRELOAD_LONGJMP_ADDR", default="0"))
-
-    print(f"in qbdi_trace [longjmp:{longjmp_plt}]")
-    if longjmp_plt != 0:
-        def longjmp_callback(vm, gpr, fpr, data):
-            print("in longjmp callback")
-            return pyqbdi.STOP
-        vm.addCodeAddrCB(longjmp_plt, pyqbdi.PREINST, longjmp_callback, None)
-
-#    def showInstruction(vm, gpr, fpr, data):
-#        instAnalysis = vm.getInstAnalysis()
-#        print("0x{:x}: {}".format(instAnalysis.address, instAnalysis.disassembly))
-#        return pyqbdi.CONTINUE    
-#    vm.addCodeCB(pyqbdi.PREINST, showInstruction, None)
+    # Add callback for handling calls to functions setjmp and longjmp.
+    vm.addVMEventCB(pyqbdi.EXEC_TRANSFER_CALL, handle_exec_transfer_call, None)
 
     # Run program.
     print("Run start")
     vm.run(start, stop)
     print(f"Run finished: {time.time() - s:.02f}s")
```

### Comparing `tritondse-0.1.3/tritondse/routines.py` & `tritondse-0.1.4/tritondse/routines.py`

 * *Files identical despite different names*

### Comparing `tritondse-0.1.3/tritondse/sanitizers.py` & `tritondse-0.1.4/tritondse/sanitizers.py`

 * *Files identical despite different names*

### Comparing `tritondse-0.1.3/tritondse/seed.py` & `tritondse-0.1.4/tritondse/seed.py`

 * *Files identical despite different names*

### Comparing `tritondse-0.1.3/tritondse/seeds_manager.py` & `tritondse-0.1.4/tritondse/seeds_manager.py`

 * *Files identical despite different names*

### Comparing `tritondse-0.1.3/tritondse/symbolic_executor.py` & `tritondse-0.1.4/tritondse/symbolic_executor.py`

 * *Files identical despite different names*

### Comparing `tritondse-0.1.3/tritondse/symbolic_explorator.py` & `tritondse-0.1.4/tritondse/symbolic_explorator.py`

 * *Files identical despite different names*

### Comparing `tritondse-0.1.3/tritondse/thread_context.py` & `tritondse-0.1.4/tritondse/thread_context.py`

 * *Files identical despite different names*

### Comparing `tritondse-0.1.3/tritondse/trace.py` & `tritondse-0.1.4/tritondse/trace.py`

 * *Files 4% similar despite different names*

```diff
@@ -134,16 +134,16 @@
 
         logging.debug(f'Command line: {" ".join(cmdlne)}')
 
         # Set environment variables.
         environ = {
             'PYQBDIPRELOAD_COVERAGE_STRATEGY': strategy.name,
             'PYQBDIPRELOAD_OUTPUT_FILEPATH': output_path,
-            'PYQBDIPRELOAD_LONGJMP_ADDR': os.getenv("TT_LONGJMP_ADDR", default="0"),
-            'PYQBDIPRELOAD_DUMP_TRACE': str(dump_trace)
+            'PYQBDIPRELOAD_DUMP_TRACE': str(dump_trace),
+            'LD_BIND_NOW': '1',
         }
         environ.update(os.environ)
 
         # Open stdin file if it is present.
         stdin_fp = open(stdin_file, 'rb') if stdin_file else None
 
         # Run QBDI tool.
```

### Comparing `tritondse-0.1.3/tritondse/types.py` & `tritondse-0.1.4/tritondse/types.py`

 * *Files identical despite different names*

### Comparing `tritondse-0.1.3/tritondse/worklist.py` & `tritondse-0.1.4/tritondse/worklist.py`

 * *Files identical despite different names*

### Comparing `tritondse-0.1.3/tritondse/workspace.py` & `tritondse-0.1.4/tritondse/workspace.py`

 * *Files identical despite different names*

### Comparing `tritondse-0.1.3/tritondse.egg-info/PKG-INFO` & `tritondse-0.1.4/tritondse.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: tritondse
-Version: 0.1.3
+Version: 0.1.4
 Summary: A library of Dynamic Symbolic Exploration based the Triton library
 Home-page: https://github.com/quarkslab/tritondse
 Author: Quarkslab
 License: AGPL-3.0
 Project-URL: Documentation, https://quarkslab.github.io/tritondse/
 Project-URL: Bug Tracker, https://github.com/quarkslab/tritondse/issues
 Project-URL: Source, https://github.com/quarkslab/tritondse
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: tritondse Version: 0.1.3 Summary: A library of
+Metadata-Version: 2.1 Name: tritondse Version: 0.1.4 Summary: A library of
 Dynamic Symbolic Exploration based the Triton library Home-page: https://
 github.com/quarkslab/tritondse Author: Quarkslab License: AGPL-3.0 Project-URL:
 Documentation, https://quarkslab.github.io/tritondse/ Project-URL: Bug Tracker,
 https://github.com/quarkslab/tritondse/issues Project-URL: Source, https://
 github.com/quarkslab/tritondse Classifier: Topic :: Security Classifier:
 Environment :: Console Classifier: Operating System :: OS Independent
 Description-Content-Type: text/markdown License-File: LICENSE # TritonDSE
```

### Comparing `tritondse-0.1.3/tritondse.egg-info/SOURCES.txt` & `tritondse-0.1.4/tritondse.egg-info/SOURCES.txt`

 * *Files identical despite different names*


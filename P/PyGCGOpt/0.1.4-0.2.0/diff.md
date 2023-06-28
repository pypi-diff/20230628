# Comparing `tmp/PyGCGOpt-0.1.4.tar.gz` & `tmp/PyGCGOpt-0.2.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "PyGCGOpt-0.1.4.tar", last modified: Sat Feb  5 04:26:18 2022, max compression
+gzip compressed data, was "PyGCGOpt-0.2.0.tar", last modified: Wed Jun 28 14:50:30 2023, max compression
```

## Comparing `PyGCGOpt-0.1.4.tar` & `PyGCGOpt-0.2.0.tar`

### file list

```diff
@@ -1,24 +1,24 @@
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-02-05 04:26:18.655666 PyGCGOpt-0.1.4/
--rw-r--r--   0 runner    (1001) docker     (121)     1100 2022-02-05 04:26:01.000000 PyGCGOpt-0.1.4/LICENSE
--rw-r--r--   0 runner    (1001) docker     (121)     1294 2022-02-05 04:26:18.659666 PyGCGOpt-0.1.4/PKG-INFO
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-02-05 04:26:18.655666 PyGCGOpt-0.1.4/PyGCGOpt.egg-info/
--rw-r--r--   0 runner    (1001) docker     (121)     1294 2022-02-05 04:26:18.000000 PyGCGOpt-0.1.4/PyGCGOpt.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (121)      449 2022-02-05 04:26:18.000000 PyGCGOpt-0.1.4/PyGCGOpt.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (121)        1 2022-02-05 04:26:18.000000 PyGCGOpt-0.1.4/PyGCGOpt.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (121)       23 2022-02-05 04:26:18.000000 PyGCGOpt-0.1.4/PyGCGOpt.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (121)        9 2022-02-05 04:26:18.000000 PyGCGOpt-0.1.4/PyGCGOpt.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (121)      608 2022-02-05 04:26:01.000000 PyGCGOpt-0.1.4/README.md
--rw-r--r--   0 runner    (1001) docker     (121)      122 2022-02-05 04:26:18.659666 PyGCGOpt-0.1.4/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (121)     4747 2022-02-05 04:26:01.000000 PyGCGOpt-0.1.4/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-02-05 04:26:18.651666 PyGCGOpt-0.1.4/src/
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-02-05 04:26:18.655666 PyGCGOpt-0.1.4/src/pygcgopt/
--rw-r--r--   0 runner    (1001) docker     (121)     1471 2022-02-05 04:26:01.000000 PyGCGOpt-0.1.4/src/pygcgopt/__init__.py
--rw-r--r--   0 runner    (1001) docker     (121)    76160 2022-02-05 04:26:01.000000 PyGCGOpt-0.1.4/src/pygcgopt/decomposition.pxi
--rw-r--r--   0 runner    (1001) docker     (121)     6554 2022-02-05 04:26:01.000000 PyGCGOpt-0.1.4/src/pygcgopt/detector.pxi
--rw-r--r--   0 runner    (1001) docker     (121)    27373 2022-02-05 04:26:01.000000 PyGCGOpt-0.1.4/src/pygcgopt/detprobdata.pxi
--rw-r--r--   0 runner    (1001) docker     (121)  2338105 2022-02-05 04:26:18.000000 PyGCGOpt-0.1.4/src/pygcgopt/gcg.cpp
--rw-r--r--   0 runner    (1001) docker     (121)    22375 2022-02-05 04:26:01.000000 PyGCGOpt-0.1.4/src/pygcgopt/gcg.pxd
--rw-r--r--   0 runner    (1001) docker     (121)    18345 2022-02-05 04:26:01.000000 PyGCGOpt-0.1.4/src/pygcgopt/gcg.pyx
--rw-r--r--   0 runner    (1001) docker     (121)     8384 2022-02-05 04:26:01.000000 PyGCGOpt-0.1.4/src/pygcgopt/partition.pxi
--rw-r--r--   0 runner    (1001) docker     (121)     3259 2022-02-05 04:26:01.000000 PyGCGOpt-0.1.4/src/pygcgopt/pricing_solver.pxi
--rw-r--r--   0 runner    (1001) docker     (121)      127 2022-02-05 04:26:01.000000 PyGCGOpt-0.1.4/src/pygcgopt/util.py
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 14:50:30.161102 PyGCGOpt-0.2.0/
+-rw-r--r--   0 runner    (1001) docker     (122)     1100 2023-06-28 14:50:08.000000 PyGCGOpt-0.2.0/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (122)     1776 2023-06-28 14:50:30.161102 PyGCGOpt-0.2.0/PKG-INFO
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 14:50:30.157102 PyGCGOpt-0.2.0/PyGCGOpt.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (122)     1776 2023-06-28 14:50:30.000000 PyGCGOpt-0.2.0/PyGCGOpt.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (122)      449 2023-06-28 14:50:30.000000 PyGCGOpt-0.2.0/PyGCGOpt.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (122)        1 2023-06-28 14:50:30.000000 PyGCGOpt-0.2.0/PyGCGOpt.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (122)       23 2023-06-28 14:50:30.000000 PyGCGOpt-0.2.0/PyGCGOpt.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (122)        9 2023-06-28 14:50:30.000000 PyGCGOpt-0.2.0/PyGCGOpt.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (122)     1071 2023-06-28 14:50:08.000000 PyGCGOpt-0.2.0/README.md
+-rw-r--r--   0 runner    (1001) docker     (122)      122 2023-06-28 14:50:30.161102 PyGCGOpt-0.2.0/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (122)     4766 2023-06-28 14:50:08.000000 PyGCGOpt-0.2.0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 14:50:30.157102 PyGCGOpt-0.2.0/src/
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 14:50:30.161102 PyGCGOpt-0.2.0/src/pygcgopt/
+-rw-r--r--   0 runner    (1001) docker     (122)     1471 2023-06-28 14:50:08.000000 PyGCGOpt-0.2.0/src/pygcgopt/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (122)    76160 2023-06-28 14:50:08.000000 PyGCGOpt-0.2.0/src/pygcgopt/decomposition.pxi
+-rw-r--r--   0 runner    (1001) docker     (122)     6554 2023-06-28 14:50:08.000000 PyGCGOpt-0.2.0/src/pygcgopt/detector.pxi
+-rw-r--r--   0 runner    (1001) docker     (122)    27373 2023-06-28 14:50:08.000000 PyGCGOpt-0.2.0/src/pygcgopt/detprobdata.pxi
+-rw-r--r--   0 runner    (1001) docker     (122)  2364467 2023-06-28 14:50:29.000000 PyGCGOpt-0.2.0/src/pygcgopt/gcg.cpp
+-rw-r--r--   0 runner    (1001) docker     (122)    22588 2023-06-28 14:50:08.000000 PyGCGOpt-0.2.0/src/pygcgopt/gcg.pxd
+-rw-r--r--   0 runner    (1001) docker     (122)    19283 2023-06-28 14:50:08.000000 PyGCGOpt-0.2.0/src/pygcgopt/gcg.pyx
+-rw-r--r--   0 runner    (1001) docker     (122)     8384 2023-06-28 14:50:08.000000 PyGCGOpt-0.2.0/src/pygcgopt/partition.pxi
+-rw-r--r--   0 runner    (1001) docker     (122)     3259 2023-06-28 14:50:08.000000 PyGCGOpt-0.2.0/src/pygcgopt/pricing_solver.pxi
+-rw-r--r--   0 runner    (1001) docker     (122)      127 2023-06-28 14:50:08.000000 PyGCGOpt-0.2.0/src/pygcgopt/util.py
```

### Comparing `PyGCGOpt-0.1.4/LICENSE` & `PyGCGOpt-0.2.0/LICENSE`

 * *Files identical despite different names*

### Comparing `PyGCGOpt-0.1.4/setup.py` & `PyGCGOpt-0.2.0/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -102,28 +102,28 @@
 
 setup(
     name='PyGCGOpt',
     version=version,
     description='Python interface and modeling environment for GCG',
     long_description=long_description,
     long_description_content_type='text/markdown',
-    url='https://git.or.rwth-aachen.de/gcg/PyGCGOpt',
+    url='https://github.com/scipopt/PyGCGOpt',
     author='Lehrstuhl für Operations Research - RWTH Aachen University',
-    author_email='',
+    author_email='gcg-bugs@or.rwth-aachen.de',
     license='MIT',
     classifiers=[
         'Development Status :: 2 - Pre-Alpha',
         'Intended Audience :: Science/Research',
         'Intended Audience :: Education',
         'License :: OSI Approved :: MIT License',
         'Programming Language :: Python :: 3',
         'Programming Language :: Cython',
         'Topic :: Scientific/Engineering :: Mathematics'],
     ext_modules=extensions,
     install_requires=[
         'wheel',
-        'pyscipopt>=3.3.0'
+        'pyscipopt>=4.0.0'
     ],
     packages=['pygcgopt'],
     package_dir={'pygcgopt': packagedir},
     package_data = {'pygcgopt': ['gcg.pyx', 'gcg.pxd', '*.pxi']}
 )
```

### Comparing `PyGCGOpt-0.1.4/src/pygcgopt/__init__.py` & `PyGCGOpt-0.2.0/src/pygcgopt/__init__.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-__version__ = '0.1.4'
+__version__ = '0.2.0'
 
 # required for Python 3.8 on Windows
 import os
 if hasattr(os, 'add_dll_directory'):
     if os.getenv('SCIPOPTDIR'):
         os.add_dll_directory(os.path.join(os.getenv('SCIPOPTDIR').strip('"'), 'bin'))
```

### Comparing `PyGCGOpt-0.1.4/src/pygcgopt/decomposition.pxi` & `PyGCGOpt-0.2.0/src/pygcgopt/decomposition.pxi`

 * *Files identical despite different names*

### Comparing `PyGCGOpt-0.1.4/src/pygcgopt/detector.pxi` & `PyGCGOpt-0.2.0/src/pygcgopt/detector.pxi`

 * *Files identical despite different names*

### Comparing `PyGCGOpt-0.1.4/src/pygcgopt/detprobdata.pxi` & `PyGCGOpt-0.2.0/src/pygcgopt/detprobdata.pxi`

 * *Files identical despite different names*

### Comparing `PyGCGOpt-0.1.4/src/pygcgopt/gcg.cpp` & `PyGCGOpt-0.2.0/src/pygcgopt/gcg.cpp`

 * *Files 0% similar despite different names*

```diff
@@ -1,19 +1,19 @@
-/* Generated by Cython 0.29.24 */
+/* Generated by Cython 0.29.35 */
 
 /* BEGIN: Cython Metadata
 {
     "distutils": {
         "depends": [],
         "extra_link_args": [
             "-Wl,-rpath,/home/runner/work/PyGCGOpt/PyGCGOpt/lib"
         ],
         "include_dirs": [
-            "/home/runner/work/PyGCGOpt/PyGCGOpt/src",
-            "/usr/include/gcg"
+            "/usr/include/gcg",
+            "/home/runner/work/PyGCGOpt/PyGCGOpt/src"
         ],
         "language": "c++",
         "libraries": [
             "scip",
             "gcg"
         ],
         "library_dirs": [
@@ -33,16 +33,16 @@
 #endif /* PY_SSIZE_T_CLEAN */
 #include "Python.h"
 #ifndef Py_PYTHON_H
     #error Python headers needed to compile C extensions, please install development version of Python.
 #elif PY_VERSION_HEX < 0x02060000 || (0x03000000 <= PY_VERSION_HEX && PY_VERSION_HEX < 0x03030000)
     #error Cython requires Python 2.6+ or Python 3.3+.
 #else
-#define CYTHON_ABI "0_29_24"
-#define CYTHON_HEX_VERSION 0x001D18F0
+#define CYTHON_ABI "0_29_35"
+#define CYTHON_HEX_VERSION 0x001D23F0
 #define CYTHON_FUTURE_DIVISION 1
 #include <stddef.h>
 #ifndef offsetof
   #define offsetof(type, member) ( (size_t) & ((type*)0) -> member )
 #endif
 #if !defined(WIN32) && !defined(MS_WINDOWS)
   #ifndef __stdcall
@@ -73,14 +73,15 @@
 #ifndef Py_HUGE_VAL
   #define Py_HUGE_VAL HUGE_VAL
 #endif
 #ifdef PYPY_VERSION
   #define CYTHON_COMPILING_IN_PYPY 1
   #define CYTHON_COMPILING_IN_PYSTON 0
   #define CYTHON_COMPILING_IN_CPYTHON 0
+  #define CYTHON_COMPILING_IN_NOGIL 0
   #undef CYTHON_USE_TYPE_SLOTS
   #define CYTHON_USE_TYPE_SLOTS 0
   #undef CYTHON_USE_PYTYPE_LOOKUP
   #define CYTHON_USE_PYTYPE_LOOKUP 0
   #if PY_VERSION_HEX < 0x03050000
     #undef CYTHON_USE_ASYNC_SLOTS
     #define CYTHON_USE_ASYNC_SLOTS 0
@@ -101,26 +102,34 @@
   #define CYTHON_ASSUME_SAFE_MACROS 0
   #undef CYTHON_UNPACK_METHODS
   #define CYTHON_UNPACK_METHODS 0
   #undef CYTHON_FAST_THREAD_STATE
   #define CYTHON_FAST_THREAD_STATE 0
   #undef CYTHON_FAST_PYCALL
   #define CYTHON_FAST_PYCALL 0
-  #undef CYTHON_PEP489_MULTI_PHASE_INIT
-  #define CYTHON_PEP489_MULTI_PHASE_INIT 0
+  #if PY_VERSION_HEX < 0x03090000
+    #undef CYTHON_PEP489_MULTI_PHASE_INIT
+    #define CYTHON_PEP489_MULTI_PHASE_INIT 0
+  #elif !defined(CYTHON_PEP489_MULTI_PHASE_INIT)
+    #define CYTHON_PEP489_MULTI_PHASE_INIT 1
+  #endif
   #undef CYTHON_USE_TP_FINALIZE
   #define CYTHON_USE_TP_FINALIZE 0
   #undef CYTHON_USE_DICT_VERSIONS
   #define CYTHON_USE_DICT_VERSIONS 0
   #undef CYTHON_USE_EXC_INFO_STACK
   #define CYTHON_USE_EXC_INFO_STACK 0
+  #ifndef CYTHON_UPDATE_DESCRIPTOR_DOC
+    #define CYTHON_UPDATE_DESCRIPTOR_DOC 0
+  #endif
 #elif defined(PYSTON_VERSION)
   #define CYTHON_COMPILING_IN_PYPY 0
   #define CYTHON_COMPILING_IN_PYSTON 1
   #define CYTHON_COMPILING_IN_CPYTHON 0
+  #define CYTHON_COMPILING_IN_NOGIL 0
   #ifndef CYTHON_USE_TYPE_SLOTS
     #define CYTHON_USE_TYPE_SLOTS 1
   #endif
   #undef CYTHON_USE_PYTYPE_LOOKUP
   #define CYTHON_USE_PYTYPE_LOOKUP 0
   #undef CYTHON_USE_ASYNC_SLOTS
   #define CYTHON_USE_ASYNC_SLOTS 0
@@ -150,18 +159,67 @@
   #define CYTHON_PEP489_MULTI_PHASE_INIT 0
   #undef CYTHON_USE_TP_FINALIZE
   #define CYTHON_USE_TP_FINALIZE 0
   #undef CYTHON_USE_DICT_VERSIONS
   #define CYTHON_USE_DICT_VERSIONS 0
   #undef CYTHON_USE_EXC_INFO_STACK
   #define CYTHON_USE_EXC_INFO_STACK 0
+  #ifndef CYTHON_UPDATE_DESCRIPTOR_DOC
+    #define CYTHON_UPDATE_DESCRIPTOR_DOC 0
+  #endif
+#elif defined(PY_NOGIL)
+  #define CYTHON_COMPILING_IN_PYPY 0
+  #define CYTHON_COMPILING_IN_PYSTON 0
+  #define CYTHON_COMPILING_IN_CPYTHON 0
+  #define CYTHON_COMPILING_IN_NOGIL 1
+  #ifndef CYTHON_USE_TYPE_SLOTS
+    #define CYTHON_USE_TYPE_SLOTS 1
+  #endif
+  #undef CYTHON_USE_PYTYPE_LOOKUP
+  #define CYTHON_USE_PYTYPE_LOOKUP 0
+  #ifndef CYTHON_USE_ASYNC_SLOTS
+    #define CYTHON_USE_ASYNC_SLOTS 1
+  #endif
+  #undef CYTHON_USE_PYLIST_INTERNALS
+  #define CYTHON_USE_PYLIST_INTERNALS 0
+  #ifndef CYTHON_USE_UNICODE_INTERNALS
+    #define CYTHON_USE_UNICODE_INTERNALS 1
+  #endif
+  #undef CYTHON_USE_UNICODE_WRITER
+  #define CYTHON_USE_UNICODE_WRITER 0
+  #undef CYTHON_USE_PYLONG_INTERNALS
+  #define CYTHON_USE_PYLONG_INTERNALS 0
+  #ifndef CYTHON_AVOID_BORROWED_REFS
+    #define CYTHON_AVOID_BORROWED_REFS 0
+  #endif
+  #ifndef CYTHON_ASSUME_SAFE_MACROS
+    #define CYTHON_ASSUME_SAFE_MACROS 1
+  #endif
+  #ifndef CYTHON_UNPACK_METHODS
+    #define CYTHON_UNPACK_METHODS 1
+  #endif
+  #undef CYTHON_FAST_THREAD_STATE
+  #define CYTHON_FAST_THREAD_STATE 0
+  #undef CYTHON_FAST_PYCALL
+  #define CYTHON_FAST_PYCALL 0
+  #ifndef CYTHON_PEP489_MULTI_PHASE_INIT
+    #define CYTHON_PEP489_MULTI_PHASE_INIT 1
+  #endif
+  #ifndef CYTHON_USE_TP_FINALIZE
+    #define CYTHON_USE_TP_FINALIZE 1
+  #endif
+  #undef CYTHON_USE_DICT_VERSIONS
+  #define CYTHON_USE_DICT_VERSIONS 0
+  #undef CYTHON_USE_EXC_INFO_STACK
+  #define CYTHON_USE_EXC_INFO_STACK 0
 #else
   #define CYTHON_COMPILING_IN_PYPY 0
   #define CYTHON_COMPILING_IN_PYSTON 0
   #define CYTHON_COMPILING_IN_CPYTHON 1
+  #define CYTHON_COMPILING_IN_NOGIL 0
   #ifndef CYTHON_USE_TYPE_SLOTS
     #define CYTHON_USE_TYPE_SLOTS 1
   #endif
   #if PY_VERSION_HEX < 0x02070000
     #undef CYTHON_USE_PYTYPE_LOOKUP
     #define CYTHON_USE_PYTYPE_LOOKUP 0
   #elif !defined(CYTHON_USE_PYTYPE_LOOKUP)
@@ -173,61 +231,72 @@
   #elif !defined(CYTHON_USE_ASYNC_SLOTS)
     #define CYTHON_USE_ASYNC_SLOTS 1
   #endif
   #if PY_VERSION_HEX < 0x02070000
     #undef CYTHON_USE_PYLONG_INTERNALS
     #define CYTHON_USE_PYLONG_INTERNALS 0
   #elif !defined(CYTHON_USE_PYLONG_INTERNALS)
-    #define CYTHON_USE_PYLONG_INTERNALS 1
+    #define CYTHON_USE_PYLONG_INTERNALS (PY_VERSION_HEX < 0x030C00A5)
   #endif
   #ifndef CYTHON_USE_PYLIST_INTERNALS
     #define CYTHON_USE_PYLIST_INTERNALS 1
   #endif
   #ifndef CYTHON_USE_UNICODE_INTERNALS
     #define CYTHON_USE_UNICODE_INTERNALS 1
   #endif
-  #if PY_VERSION_HEX < 0x030300F0
+  #if PY_VERSION_HEX < 0x030300F0 || PY_VERSION_HEX >= 0x030B00A2
     #undef CYTHON_USE_UNICODE_WRITER
     #define CYTHON_USE_UNICODE_WRITER 0
   #elif !defined(CYTHON_USE_UNICODE_WRITER)
     #define CYTHON_USE_UNICODE_WRITER 1
   #endif
   #ifndef CYTHON_AVOID_BORROWED_REFS
     #define CYTHON_AVOID_BORROWED_REFS 0
   #endif
   #ifndef CYTHON_ASSUME_SAFE_MACROS
     #define CYTHON_ASSUME_SAFE_MACROS 1
   #endif
   #ifndef CYTHON_UNPACK_METHODS
     #define CYTHON_UNPACK_METHODS 1
   #endif
-  #ifndef CYTHON_FAST_THREAD_STATE
+  #if PY_VERSION_HEX >= 0x030B00A4
+    #undef CYTHON_FAST_THREAD_STATE
+    #define CYTHON_FAST_THREAD_STATE 0
+  #elif !defined(CYTHON_FAST_THREAD_STATE)
     #define CYTHON_FAST_THREAD_STATE 1
   #endif
   #ifndef CYTHON_FAST_PYCALL
-    #define CYTHON_FAST_PYCALL 1
+    #define CYTHON_FAST_PYCALL (PY_VERSION_HEX < 0x030A0000)
   #endif
   #ifndef CYTHON_PEP489_MULTI_PHASE_INIT
     #define CYTHON_PEP489_MULTI_PHASE_INIT (PY_VERSION_HEX >= 0x03050000)
   #endif
   #ifndef CYTHON_USE_TP_FINALIZE
     #define CYTHON_USE_TP_FINALIZE (PY_VERSION_HEX >= 0x030400a1)
   #endif
   #ifndef CYTHON_USE_DICT_VERSIONS
-    #define CYTHON_USE_DICT_VERSIONS (PY_VERSION_HEX >= 0x030600B1)
+    #define CYTHON_USE_DICT_VERSIONS ((PY_VERSION_HEX >= 0x030600B1) && (PY_VERSION_HEX < 0x030C00A5))
   #endif
-  #ifndef CYTHON_USE_EXC_INFO_STACK
+  #if PY_VERSION_HEX >= 0x030B00A4
+    #undef CYTHON_USE_EXC_INFO_STACK
+    #define CYTHON_USE_EXC_INFO_STACK 0
+  #elif !defined(CYTHON_USE_EXC_INFO_STACK)
     #define CYTHON_USE_EXC_INFO_STACK (PY_VERSION_HEX >= 0x030700A3)
   #endif
+  #ifndef CYTHON_UPDATE_DESCRIPTOR_DOC
+    #define CYTHON_UPDATE_DESCRIPTOR_DOC 1
+  #endif
 #endif
 #if !defined(CYTHON_FAST_PYCCALL)
 #define CYTHON_FAST_PYCCALL  (CYTHON_FAST_PYCALL && PY_VERSION_HEX >= 0x030600B1)
 #endif
 #if CYTHON_USE_PYLONG_INTERNALS
-  #include "longintrepr.h"
+  #if PY_MAJOR_VERSION < 3
+    #include "longintrepr.h"
+  #endif
   #undef SHIFT
   #undef BASE
   #undef MASK
   #ifdef SIZEOF_VOID_P
     enum { __pyx_check_sizeof_voidp = 1 / (int)(SIZEOF_VOID_P == sizeof(void*)) };
   #endif
 #endif
@@ -350,17 +419,76 @@
 #if PY_MAJOR_VERSION < 3
   #define __Pyx_BUILTIN_MODULE_NAME "__builtin__"
   #define __Pyx_PyCode_New(a, k, l, s, f, code, c, n, v, fv, cell, fn, name, fline, lnos)\
           PyCode_New(a+k, l, s, f, code, c, n, v, fv, cell, fn, name, fline, lnos)
   #define __Pyx_DefaultClassType PyClass_Type
 #else
   #define __Pyx_BUILTIN_MODULE_NAME "builtins"
-#if PY_VERSION_HEX >= 0x030800A4 && PY_VERSION_HEX < 0x030800B2
-  #define __Pyx_PyCode_New(a, k, l, s, f, code, c, n, v, fv, cell, fn, name, fline, lnos)\
-          PyCode_New(a, 0, k, l, s, f, code, c, n, v, fv, cell, fn, name, fline, lnos)
+  #define __Pyx_DefaultClassType PyType_Type
+#if PY_VERSION_HEX >= 0x030B00A1
+    static CYTHON_INLINE PyCodeObject* __Pyx_PyCode_New(int a, int k, int l, int s, int f,
+                                                    PyObject *code, PyObject *c, PyObject* n, PyObject *v,
+                                                    PyObject *fv, PyObject *cell, PyObject* fn,
+                                                    PyObject *name, int fline, PyObject *lnos) {
+        PyObject *kwds=NULL, *argcount=NULL, *posonlyargcount=NULL, *kwonlyargcount=NULL;
+        PyObject *nlocals=NULL, *stacksize=NULL, *flags=NULL, *replace=NULL, *call_result=NULL, *empty=NULL;
+        const char *fn_cstr=NULL;
+        const char *name_cstr=NULL;
+        PyCodeObject* co=NULL;
+        PyObject *type, *value, *traceback;
+        PyErr_Fetch(&type, &value, &traceback);
+        if (!(kwds=PyDict_New())) goto end;
+        if (!(argcount=PyLong_FromLong(a))) goto end;
+        if (PyDict_SetItemString(kwds, "co_argcount", argcount) != 0) goto end;
+        if (!(posonlyargcount=PyLong_FromLong(0))) goto end;
+        if (PyDict_SetItemString(kwds, "co_posonlyargcount", posonlyargcount) != 0) goto end;
+        if (!(kwonlyargcount=PyLong_FromLong(k))) goto end;
+        if (PyDict_SetItemString(kwds, "co_kwonlyargcount", kwonlyargcount) != 0) goto end;
+        if (!(nlocals=PyLong_FromLong(l))) goto end;
+        if (PyDict_SetItemString(kwds, "co_nlocals", nlocals) != 0) goto end;
+        if (!(stacksize=PyLong_FromLong(s))) goto end;
+        if (PyDict_SetItemString(kwds, "co_stacksize", stacksize) != 0) goto end;
+        if (!(flags=PyLong_FromLong(f))) goto end;
+        if (PyDict_SetItemString(kwds, "co_flags", flags) != 0) goto end;
+        if (PyDict_SetItemString(kwds, "co_code", code) != 0) goto end;
+        if (PyDict_SetItemString(kwds, "co_consts", c) != 0) goto end;
+        if (PyDict_SetItemString(kwds, "co_names", n) != 0) goto end;
+        if (PyDict_SetItemString(kwds, "co_varnames", v) != 0) goto end;
+        if (PyDict_SetItemString(kwds, "co_freevars", fv) != 0) goto end;
+        if (PyDict_SetItemString(kwds, "co_cellvars", cell) != 0) goto end;
+        if (PyDict_SetItemString(kwds, "co_linetable", lnos) != 0) goto end;
+        if (!(fn_cstr=PyUnicode_AsUTF8AndSize(fn, NULL))) goto end;
+        if (!(name_cstr=PyUnicode_AsUTF8AndSize(name, NULL))) goto end;
+        if (!(co = PyCode_NewEmpty(fn_cstr, name_cstr, fline))) goto end;
+        if (!(replace = PyObject_GetAttrString((PyObject*)co, "replace"))) goto cleanup_code_too;
+        if (!(empty = PyTuple_New(0))) goto cleanup_code_too; // unfortunately __pyx_empty_tuple isn't available here
+        if (!(call_result = PyObject_Call(replace, empty, kwds))) goto cleanup_code_too;
+        Py_XDECREF((PyObject*)co);
+        co = (PyCodeObject*)call_result;
+        call_result = NULL;
+        if (0) {
+            cleanup_code_too:
+            Py_XDECREF((PyObject*)co);
+            co = NULL;
+        }
+        end:
+        Py_XDECREF(kwds);
+        Py_XDECREF(argcount);
+        Py_XDECREF(posonlyargcount);
+        Py_XDECREF(kwonlyargcount);
+        Py_XDECREF(nlocals);
+        Py_XDECREF(stacksize);
+        Py_XDECREF(replace);
+        Py_XDECREF(call_result);
+        Py_XDECREF(empty);
+        if (type) {
+            PyErr_Restore(type, value, traceback);
+        }
+        return co;
+    }
 #else
   #define __Pyx_PyCode_New(a, k, l, s, f, code, c, n, v, fv, cell, fn, name, fline, lnos)\
           PyCode_New(a, k, l, s, f, code, c, n, v, fv, cell, fn, name, fline, lnos)
 #endif
   #define __Pyx_DefaultClassType PyType_Type
 #endif
 #ifndef Py_TPFLAGS_CHECKTYPES
@@ -466,35 +594,35 @@
 #if CYTHON_COMPILING_IN_CPYTHON && PY_VERSION_HEX >= 0x030500A1 && CYTHON_USE_UNICODE_INTERNALS
 #define __Pyx_PyDict_GetItemStr(dict, name)  _PyDict_GetItem_KnownHash(dict, name, ((PyASCIIObject *) name)->hash)
 #else
 #define __Pyx_PyDict_GetItemStr(dict, name)  PyDict_GetItem(dict, name)
 #endif
 #if PY_VERSION_HEX > 0x03030000 && defined(PyUnicode_KIND)
   #define CYTHON_PEP393_ENABLED 1
-  #if defined(PyUnicode_IS_READY)
-  #define __Pyx_PyUnicode_READY(op)       (likely(PyUnicode_IS_READY(op)) ?\
-                                              0 : _PyUnicode_Ready((PyObject *)(op)))
+  #if PY_VERSION_HEX >= 0x030C0000
+    #define __Pyx_PyUnicode_READY(op)       (0)
   #else
-  #define __Pyx_PyUnicode_READY(op)       (0)
+    #define __Pyx_PyUnicode_READY(op)       (likely(PyUnicode_IS_READY(op)) ?\
+                                                0 : _PyUnicode_Ready((PyObject *)(op)))
   #endif
   #define __Pyx_PyUnicode_GET_LENGTH(u)   PyUnicode_GET_LENGTH(u)
   #define __Pyx_PyUnicode_READ_CHAR(u, i) PyUnicode_READ_CHAR(u, i)
   #define __Pyx_PyUnicode_MAX_CHAR_VALUE(u)   PyUnicode_MAX_CHAR_VALUE(u)
   #define __Pyx_PyUnicode_KIND(u)         PyUnicode_KIND(u)
   #define __Pyx_PyUnicode_DATA(u)         PyUnicode_DATA(u)
   #define __Pyx_PyUnicode_READ(k, d, i)   PyUnicode_READ(k, d, i)
   #define __Pyx_PyUnicode_WRITE(k, d, i, ch)  PyUnicode_WRITE(k, d, i, ch)
-  #if defined(PyUnicode_IS_READY) && defined(PyUnicode_GET_SIZE)
-  #if CYTHON_COMPILING_IN_CPYTHON && PY_VERSION_HEX >= 0x03090000
-  #define __Pyx_PyUnicode_IS_TRUE(u)      (0 != (likely(PyUnicode_IS_READY(u)) ? PyUnicode_GET_LENGTH(u) : ((PyCompactUnicodeObject *)(u))->wstr_length))
+  #if PY_VERSION_HEX >= 0x030C0000
+    #define __Pyx_PyUnicode_IS_TRUE(u)      (0 != PyUnicode_GET_LENGTH(u))
   #else
-  #define __Pyx_PyUnicode_IS_TRUE(u)      (0 != (likely(PyUnicode_IS_READY(u)) ? PyUnicode_GET_LENGTH(u) : PyUnicode_GET_SIZE(u)))
-  #endif
-  #else
-  #define __Pyx_PyUnicode_IS_TRUE(u)      (0 != PyUnicode_GET_LENGTH(u))
+    #if CYTHON_COMPILING_IN_CPYTHON && PY_VERSION_HEX >= 0x03090000
+    #define __Pyx_PyUnicode_IS_TRUE(u)      (0 != (likely(PyUnicode_IS_READY(u)) ? PyUnicode_GET_LENGTH(u) : ((PyCompactUnicodeObject *)(u))->wstr_length))
+    #else
+    #define __Pyx_PyUnicode_IS_TRUE(u)      (0 != (likely(PyUnicode_IS_READY(u)) ? PyUnicode_GET_LENGTH(u) : PyUnicode_GET_SIZE(u)))
+    #endif
   #endif
 #else
   #define CYTHON_PEP393_ENABLED 0
   #define PyUnicode_1BYTE_KIND  1
   #define PyUnicode_2BYTE_KIND  2
   #define PyUnicode_4BYTE_KIND  4
   #define __Pyx_PyUnicode_READY(op)       (0)
@@ -590,18 +718,18 @@
   #ifndef PyUnicode_InternFromString
     #define PyUnicode_InternFromString(s) PyUnicode_FromString(s)
   #endif
 #endif
 #if PY_VERSION_HEX < 0x030200A4
   typedef long Py_hash_t;
   #define __Pyx_PyInt_FromHash_t PyInt_FromLong
-  #define __Pyx_PyInt_AsHash_t   PyInt_AsLong
+  #define __Pyx_PyInt_AsHash_t   __Pyx_PyIndex_AsHash_t
 #else
   #define __Pyx_PyInt_FromHash_t PyInt_FromSsize_t
-  #define __Pyx_PyInt_AsHash_t   PyInt_AsSsize_t
+  #define __Pyx_PyInt_AsHash_t   __Pyx_PyIndex_AsSsize_t
 #endif
 #if PY_MAJOR_VERSION >= 3
   #define __Pyx_PyMethod_New(func, self, klass) ((self) ? ((void)(klass), PyMethod_New(func, self)) : __Pyx_NewRef(func))
 #else
   #define __Pyx_PyMethod_New(func, self, klass) PyMethod_New(func, self, klass)
 #endif
 #if CYTHON_USE_ASYNC_SLOTS
@@ -618,16 +746,18 @@
     typedef struct {
         unaryfunc am_await;
         unaryfunc am_aiter;
         unaryfunc am_anext;
     } __Pyx_PyAsyncMethodsStruct;
 #endif
 
-#if defined(WIN32) || defined(MS_WINDOWS)
-  #define _USE_MATH_DEFINES
+#if defined(_WIN32) || defined(WIN32) || defined(MS_WINDOWS)
+  #if !defined(_USE_MATH_DEFINES)
+    #define _USE_MATH_DEFINES
+  #endif
 #endif
 #include <math.h>
 #ifdef NAN
 #define __PYX_NAN() ((float) NAN)
 #else
 static CYTHON_INLINE float __PYX_NAN() {
   float value;
@@ -675,14 +805,15 @@
 #include "scip/expr_var.h"
 #include "scip/expr_varidx.h"
 #include "scip/expr_value.h"
 #include "scip/expr_sum.h"
 #include "scip/expr_abs.h"
 #include "scip/expr_exp.h"
 #include "scip/expr_log.h"
+#include "scip/expr_trig.h"
 #include "scip/expr_product.h"
 #include "scip/expr_pow.h"
 #include "scip/pub_nlp.h"
 #include "scip/scip_nlp.h"
 #include "scip/cons_cardinality.h"
 #include "scip/cons_indicator.h"
 #include "scip/cons_countsols.h"
@@ -696,15 +827,16 @@
 #include "stdexcept"
 #include "typeinfo"
 #include <vector>
 #include <string.h>
 #include <string>
 #include <utility>
 
-    #if __cplusplus > 199711L
+    #if __cplusplus >= 201103L || (defined(_MSC_VER) && _MSC_VER >= 1600)
+    // move should be defined for these versions of MSVC, but __cplusplus isn't set usefully
     #include <type_traits>
 
     namespace cython_std {
     template <typename T> typename std::remove_reference<T>::type&& move(T& t) noexcept { return std::move(t); }
     template <typename T> typename std::remove_reference<T>::type&& move(T&& t) noexcept { return std::move(t); }
     }
 
@@ -818,14 +950,15 @@
 static CYTHON_INLINE int __Pyx_PyObject_IsTrue(PyObject*);
 static CYTHON_INLINE int __Pyx_PyObject_IsTrueAndDecref(PyObject*);
 static CYTHON_INLINE PyObject* __Pyx_PyNumber_IntOrLong(PyObject* x);
 #define __Pyx_PySequence_Tuple(obj)\
     (likely(PyTuple_CheckExact(obj)) ? __Pyx_NewRef(obj) : PySequence_Tuple(obj))
 static CYTHON_INLINE Py_ssize_t __Pyx_PyIndex_AsSsize_t(PyObject*);
 static CYTHON_INLINE PyObject * __Pyx_PyInt_FromSize_t(size_t);
+static CYTHON_INLINE Py_hash_t __Pyx_PyIndex_AsHash_t(PyObject*);
 #if CYTHON_ASSUME_SAFE_MACROS
 #define __pyx_PyFloat_AsDouble(x) (PyFloat_CheckExact(x) ? PyFloat_AS_DOUBLE(x) : PyFloat_AsDouble(x))
 #else
 #define __pyx_PyFloat_AsDouble(x) PyFloat_AsDouble(x)
 #endif
 #define __pyx_PyFloat_AsFloat(x) ((float) __pyx_PyFloat_AsDouble(x))
 #if PY_MAJOR_VERSION >= 3
@@ -981,88 +1114,88 @@
  *         if format not in ["svg", "png"]:
  */
 struct __pyx_opt_args_8pygcgopt_3gcg_20PartialDecomposition___generate_visualization {
   int __pyx_n;
   PyObject *format;
 };
 
-/* "pyscipopt/scip.pxd":1738
+/* "pyscipopt/scip.pxd":1792
  *     int SCIPtpiGetNumThreads()
  * 
  * cdef class Expr:             # <<<<<<<<<<<<<<
  *     cdef public terms
  * 
  */
 struct __pyx_obj_9pyscipopt_4scip_Expr {
   PyObject_HEAD
   PyObject *terms;
 };
 
 
-/* "pyscipopt/scip.pxd":1741
+/* "pyscipopt/scip.pxd":1795
  *     cdef public terms
  * 
  * cdef class Event:             # <<<<<<<<<<<<<<
  *     cdef SCIP_EVENT* event
  *     # can be used to store problem data
  */
 struct __pyx_obj_9pyscipopt_4scip_Event {
   PyObject_HEAD
   struct __pyx_vtabstruct_9pyscipopt_4scip_Event *__pyx_vtab;
   SCIP_EVENT *event;
   PyObject *data;
 };
 
 
-/* "pyscipopt/scip.pxd":1748
+/* "pyscipopt/scip.pxd":1802
  *     cdef create(SCIP_EVENT* scip_event)
  * 
  * cdef class Column:             # <<<<<<<<<<<<<<
  *     cdef SCIP_COL* scip_col
  *     # can be used to store problem data
  */
 struct __pyx_obj_9pyscipopt_4scip_Column {
   PyObject_HEAD
   struct __pyx_vtabstruct_9pyscipopt_4scip_Column *__pyx_vtab;
   SCIP_COL *scip_col;
   PyObject *data;
 };
 
 
-/* "pyscipopt/scip.pxd":1756
+/* "pyscipopt/scip.pxd":1810
  *     cdef create(SCIP_COL* scipcol)
  * 
  * cdef class Row:             # <<<<<<<<<<<<<<
  *     cdef SCIP_ROW* scip_row
  *     # can be used to store problem data
  */
 struct __pyx_obj_9pyscipopt_4scip_Row {
   PyObject_HEAD
   struct __pyx_vtabstruct_9pyscipopt_4scip_Row *__pyx_vtab;
   SCIP_ROW *scip_row;
   PyObject *data;
 };
 
 
-/* "pyscipopt/scip.pxd":1764
+/* "pyscipopt/scip.pxd":1818
  *     cdef create(SCIP_ROW* sciprow)
  * 
  * cdef class NLRow:             # <<<<<<<<<<<<<<
  *     cdef SCIP_NLROW* scip_nlrow
  *     # can be used to store problem data
  */
 struct __pyx_obj_9pyscipopt_4scip_NLRow {
   PyObject_HEAD
   struct __pyx_vtabstruct_9pyscipopt_4scip_NLRow *__pyx_vtab;
   SCIP_NLROW *scip_nlrow;
   PyObject *data;
 };
 
 
-/* "pyscipopt/scip.pxd":1772
+/* "pyscipopt/scip.pxd":1826
  *     cdef create(SCIP_NLROW* scipnlrow)
  * 
  * cdef class Solution:             # <<<<<<<<<<<<<<
  *     cdef SCIP_SOL* sol
  *     cdef SCIP* scip
  */
 struct __pyx_obj_9pyscipopt_4scip_Solution {
@@ -1070,88 +1203,88 @@
   struct __pyx_vtabstruct_9pyscipopt_4scip_Solution *__pyx_vtab;
   SCIP_SOL *sol;
   SCIP *scip;
   PyObject *data;
 };
 
 
-/* "pyscipopt/scip.pxd":1781
+/* "pyscipopt/scip.pxd":1835
  *     cdef create(SCIP* scip, SCIP_SOL* scip_sol)
  * 
  * cdef class DomainChanges:             # <<<<<<<<<<<<<<
  *     cdef SCIP_DOMCHG* scip_domchg
  * 
  */
 struct __pyx_obj_9pyscipopt_4scip_DomainChanges {
   PyObject_HEAD
   struct __pyx_vtabstruct_9pyscipopt_4scip_DomainChanges *__pyx_vtab;
   SCIP_DOMCHG *scip_domchg;
 };
 
 
-/* "pyscipopt/scip.pxd":1787
+/* "pyscipopt/scip.pxd":1841
  *     cdef create(SCIP_DOMCHG* scip_domchg)
  * 
  * cdef class BoundChange:             # <<<<<<<<<<<<<<
  *     cdef SCIP_BOUNDCHG* scip_boundchg
  * 
  */
 struct __pyx_obj_9pyscipopt_4scip_BoundChange {
   PyObject_HEAD
   struct __pyx_vtabstruct_9pyscipopt_4scip_BoundChange *__pyx_vtab;
   SCIP_BOUNDCHG *scip_boundchg;
 };
 
 
-/* "pyscipopt/scip.pxd":1793
+/* "pyscipopt/scip.pxd":1847
  *     cdef create(SCIP_BOUNDCHG* scip_boundchg)
  * 
  * cdef class Node:             # <<<<<<<<<<<<<<
  *     cdef SCIP_NODE* scip_node
  *     # can be used to store problem data
  */
 struct __pyx_obj_9pyscipopt_4scip_Node {
   PyObject_HEAD
   struct __pyx_vtabstruct_9pyscipopt_4scip_Node *__pyx_vtab;
   SCIP_NODE *scip_node;
   PyObject *data;
 };
 
 
-/* "pyscipopt/scip.pxd":1801
+/* "pyscipopt/scip.pxd":1855
  *     cdef create(SCIP_NODE* scipnode)
  * 
  * cdef class Variable(Expr):             # <<<<<<<<<<<<<<
  *     cdef SCIP_VAR* scip_var
  *     # can be used to store problem data
  */
 struct __pyx_obj_9pyscipopt_4scip_Variable {
   struct __pyx_obj_9pyscipopt_4scip_Expr __pyx_base;
   struct __pyx_vtabstruct_9pyscipopt_4scip_Variable *__pyx_vtab;
   SCIP_VAR *scip_var;
   PyObject *data;
 };
 
 
-/* "pyscipopt/scip.pxd":1809
+/* "pyscipopt/scip.pxd":1863
  *     cdef create(SCIP_VAR* scipvar)
  * 
  * cdef class Constraint:             # <<<<<<<<<<<<<<
  *     cdef SCIP_CONS* scip_cons
  *     # can be used to store problem data
  */
 struct __pyx_obj_9pyscipopt_4scip_Constraint {
   PyObject_HEAD
   struct __pyx_vtabstruct_9pyscipopt_4scip_Constraint *__pyx_vtab;
   SCIP_CONS *scip_cons;
   PyObject *data;
 };
 
 
-/* "pyscipopt/scip.pxd":1817
+/* "pyscipopt/scip.pxd":1871
  *     cdef create(SCIP_CONS* scipcons)
  * 
  * cdef class Model:             # <<<<<<<<<<<<<<
  *     cdef SCIP* _scip
  *     cdef SCIP_Bool* _valid
  */
 struct __pyx_obj_9pyscipopt_4scip_Model {
@@ -1163,15 +1296,15 @@
   PyObject *data;
   PyObject *__weakref__;
   SCIP_Bool _freescip;
   PyObject *_modelvars;
 };
 
 
-/* "pygcgopt/gcg.pxd":429
+/* "pygcgopt/gcg.pxd":434
  * 
  * 
  * cdef class GCGColumn:             # <<<<<<<<<<<<<<
  *     cdef GCG_COL* gcg_col
  * 
  */
 struct __pyx_obj_8pygcgopt_3gcg_GCGColumn {
@@ -1283,194 +1416,194 @@
  * 
  */
 struct __pyx_obj_8pygcgopt_3gcg_Model {
   struct __pyx_obj_9pyscipopt_4scip_Model __pyx_base;
 };
 
 
-/* "pygcgopt/gcg.pyx":352
+/* "pygcgopt/gcg.pyx":362
  * 
  * 
  * cdef class GCGPricingModel(SCIPModel):             # <<<<<<<<<<<<<<
  *     @staticmethod
  *     cdef create(SCIP* scip):
  */
 struct __pyx_obj_8pygcgopt_3gcg_GCGPricingModel {
   struct __pyx_obj_9pyscipopt_4scip_Model __pyx_base;
 };
 
 
-/* "pygcgopt/gcg.pyx":392
+/* "pygcgopt/gcg.pyx":402
  * 
  * 
  * cdef class GCGMasterModel(SCIPModel):             # <<<<<<<<<<<<<<
  *     @staticmethod
  *     cdef create(SCIP* scip):
  */
 struct __pyx_obj_8pygcgopt_3gcg_GCGMasterModel {
   struct __pyx_obj_9pyscipopt_4scip_Model __pyx_base;
 };
 
 
 
-/* "pyscipopt/scip.pxd":1741
+/* "pyscipopt/scip.pxd":1795
  *     cdef public terms
  * 
  * cdef class Event:             # <<<<<<<<<<<<<<
  *     cdef SCIP_EVENT* event
  *     # can be used to store problem data
  */
 
 struct __pyx_vtabstruct_9pyscipopt_4scip_Event {
   PyObject *(*create)(SCIP_EVENT *);
 };
 static struct __pyx_vtabstruct_9pyscipopt_4scip_Event *__pyx_vtabptr_9pyscipopt_4scip_Event;
 
 
-/* "pyscipopt/scip.pxd":1748
+/* "pyscipopt/scip.pxd":1802
  *     cdef create(SCIP_EVENT* scip_event)
  * 
  * cdef class Column:             # <<<<<<<<<<<<<<
  *     cdef SCIP_COL* scip_col
  *     # can be used to store problem data
  */
 
 struct __pyx_vtabstruct_9pyscipopt_4scip_Column {
   PyObject *(*create)(SCIP_COL *);
 };
 static struct __pyx_vtabstruct_9pyscipopt_4scip_Column *__pyx_vtabptr_9pyscipopt_4scip_Column;
 
 
-/* "pyscipopt/scip.pxd":1756
+/* "pyscipopt/scip.pxd":1810
  *     cdef create(SCIP_COL* scipcol)
  * 
  * cdef class Row:             # <<<<<<<<<<<<<<
  *     cdef SCIP_ROW* scip_row
  *     # can be used to store problem data
  */
 
 struct __pyx_vtabstruct_9pyscipopt_4scip_Row {
   PyObject *(*create)(SCIP_ROW *);
 };
 static struct __pyx_vtabstruct_9pyscipopt_4scip_Row *__pyx_vtabptr_9pyscipopt_4scip_Row;
 
 
-/* "pyscipopt/scip.pxd":1764
+/* "pyscipopt/scip.pxd":1818
  *     cdef create(SCIP_ROW* sciprow)
  * 
  * cdef class NLRow:             # <<<<<<<<<<<<<<
  *     cdef SCIP_NLROW* scip_nlrow
  *     # can be used to store problem data
  */
 
 struct __pyx_vtabstruct_9pyscipopt_4scip_NLRow {
   PyObject *(*create)(SCIP_NLROW *);
 };
 static struct __pyx_vtabstruct_9pyscipopt_4scip_NLRow *__pyx_vtabptr_9pyscipopt_4scip_NLRow;
 
 
-/* "pyscipopt/scip.pxd":1772
+/* "pyscipopt/scip.pxd":1826
  *     cdef create(SCIP_NLROW* scipnlrow)
  * 
  * cdef class Solution:             # <<<<<<<<<<<<<<
  *     cdef SCIP_SOL* sol
  *     cdef SCIP* scip
  */
 
 struct __pyx_vtabstruct_9pyscipopt_4scip_Solution {
   PyObject *(*create)(SCIP *, SCIP_SOL *);
 };
 static struct __pyx_vtabstruct_9pyscipopt_4scip_Solution *__pyx_vtabptr_9pyscipopt_4scip_Solution;
 
 
-/* "pyscipopt/scip.pxd":1781
+/* "pyscipopt/scip.pxd":1835
  *     cdef create(SCIP* scip, SCIP_SOL* scip_sol)
  * 
  * cdef class DomainChanges:             # <<<<<<<<<<<<<<
  *     cdef SCIP_DOMCHG* scip_domchg
  * 
  */
 
 struct __pyx_vtabstruct_9pyscipopt_4scip_DomainChanges {
   PyObject *(*create)(SCIP_DOMCHG *);
 };
 static struct __pyx_vtabstruct_9pyscipopt_4scip_DomainChanges *__pyx_vtabptr_9pyscipopt_4scip_DomainChanges;
 
 
-/* "pyscipopt/scip.pxd":1787
+/* "pyscipopt/scip.pxd":1841
  *     cdef create(SCIP_DOMCHG* scip_domchg)
  * 
  * cdef class BoundChange:             # <<<<<<<<<<<<<<
  *     cdef SCIP_BOUNDCHG* scip_boundchg
  * 
  */
 
 struct __pyx_vtabstruct_9pyscipopt_4scip_BoundChange {
   PyObject *(*create)(SCIP_BOUNDCHG *);
 };
 static struct __pyx_vtabstruct_9pyscipopt_4scip_BoundChange *__pyx_vtabptr_9pyscipopt_4scip_BoundChange;
 
 
-/* "pyscipopt/scip.pxd":1793
+/* "pyscipopt/scip.pxd":1847
  *     cdef create(SCIP_BOUNDCHG* scip_boundchg)
  * 
  * cdef class Node:             # <<<<<<<<<<<<<<
  *     cdef SCIP_NODE* scip_node
  *     # can be used to store problem data
  */
 
 struct __pyx_vtabstruct_9pyscipopt_4scip_Node {
   PyObject *(*create)(SCIP_NODE *);
 };
 static struct __pyx_vtabstruct_9pyscipopt_4scip_Node *__pyx_vtabptr_9pyscipopt_4scip_Node;
 
 
-/* "pyscipopt/scip.pxd":1801
+/* "pyscipopt/scip.pxd":1855
  *     cdef create(SCIP_NODE* scipnode)
  * 
  * cdef class Variable(Expr):             # <<<<<<<<<<<<<<
  *     cdef SCIP_VAR* scip_var
  *     # can be used to store problem data
  */
 
 struct __pyx_vtabstruct_9pyscipopt_4scip_Variable {
   PyObject *(*create)(SCIP_VAR *);
 };
 static struct __pyx_vtabstruct_9pyscipopt_4scip_Variable *__pyx_vtabptr_9pyscipopt_4scip_Variable;
 
 
-/* "pyscipopt/scip.pxd":1809
+/* "pyscipopt/scip.pxd":1863
  *     cdef create(SCIP_VAR* scipvar)
  * 
  * cdef class Constraint:             # <<<<<<<<<<<<<<
  *     cdef SCIP_CONS* scip_cons
  *     # can be used to store problem data
  */
 
 struct __pyx_vtabstruct_9pyscipopt_4scip_Constraint {
   PyObject *(*create)(SCIP_CONS *);
 };
 static struct __pyx_vtabstruct_9pyscipopt_4scip_Constraint *__pyx_vtabptr_9pyscipopt_4scip_Constraint;
 
 
-/* "pyscipopt/scip.pxd":1817
+/* "pyscipopt/scip.pxd":1871
  *     cdef create(SCIP_CONS* scipcons)
  * 
  * cdef class Model:             # <<<<<<<<<<<<<<
  *     cdef SCIP* _scip
  *     cdef SCIP_Bool* _valid
  */
 
 struct __pyx_vtabstruct_9pyscipopt_4scip_Model {
   PyObject *(*create)(SCIP *);
 };
 static struct __pyx_vtabstruct_9pyscipopt_4scip_Model *__pyx_vtabptr_9pyscipopt_4scip_Model;
 
 
-/* "pygcgopt/gcg.pyx":408
+/* "pygcgopt/gcg.pyx":428
  * 
  * 
  * cdef class GCGColumn:             # <<<<<<<<<<<<<<
  *     """Base class holding a pointer to corresponding GCG_COL"""
  * 
  */
 
@@ -1541,29 +1674,29 @@
 
 struct __pyx_vtabstruct_8pygcgopt_3gcg_Model {
   struct __pyx_vtabstruct_9pyscipopt_4scip_Model __pyx_base;
 };
 static struct __pyx_vtabstruct_8pygcgopt_3gcg_Model *__pyx_vtabptr_8pygcgopt_3gcg_Model;
 
 
-/* "pygcgopt/gcg.pyx":352
+/* "pygcgopt/gcg.pyx":362
  * 
  * 
  * cdef class GCGPricingModel(SCIPModel):             # <<<<<<<<<<<<<<
  *     @staticmethod
  *     cdef create(SCIP* scip):
  */
 
 struct __pyx_vtabstruct_8pygcgopt_3gcg_GCGPricingModel {
   struct __pyx_vtabstruct_9pyscipopt_4scip_Model __pyx_base;
 };
 static struct __pyx_vtabstruct_8pygcgopt_3gcg_GCGPricingModel *__pyx_vtabptr_8pygcgopt_3gcg_GCGPricingModel;
 
 
-/* "pygcgopt/gcg.pyx":392
+/* "pygcgopt/gcg.pyx":402
  * 
  * 
  * cdef class GCGMasterModel(SCIPModel):             # <<<<<<<<<<<<<<
  *     @staticmethod
  *     cdef create(SCIP* scip):
  */
 
@@ -1735,26 +1868,26 @@
 #define __PYX_GET_DICT_VERSION(dict)  (0)
 #define __PYX_UPDATE_DICT_CACHE(dict, value, cache_var, version_var)
 #define __PYX_PY_DICT_LOOKUP_IF_MODIFIED(VAR, DICT, LOOKUP)  (VAR) = (LOOKUP);
 #endif
 
 /* GetModuleGlobalName.proto */
 #if CYTHON_USE_DICT_VERSIONS
-#define __Pyx_GetModuleGlobalName(var, name)  {\
+#define __Pyx_GetModuleGlobalName(var, name)  do {\
     static PY_UINT64_T __pyx_dict_version = 0;\
     static PyObject *__pyx_dict_cached_value = NULL;\
     (var) = (likely(__pyx_dict_version == __PYX_GET_DICT_VERSION(__pyx_d))) ?\
         (likely(__pyx_dict_cached_value) ? __Pyx_NewRef(__pyx_dict_cached_value) : __Pyx_GetBuiltinName(name)) :\
         __Pyx__GetModuleGlobalName(name, &__pyx_dict_version, &__pyx_dict_cached_value);\
-}
-#define __Pyx_GetModuleGlobalNameUncached(var, name)  {\
+} while(0)
+#define __Pyx_GetModuleGlobalNameUncached(var, name)  do {\
     PY_UINT64_T __pyx_dict_version;\
     PyObject *__pyx_dict_cached_value;\
     (var) = __Pyx__GetModuleGlobalName(name, &__pyx_dict_version, &__pyx_dict_cached_value);\
-}
+} while(0)
 static PyObject *__Pyx__GetModuleGlobalName(PyObject *name, PY_UINT64_T *dict_version, PyObject **dict_cached_value);
 #else
 #define __Pyx_GetModuleGlobalName(var, name)  (var) = __Pyx__GetModuleGlobalName(name)
 #define __Pyx_GetModuleGlobalNameUncached(var, name)  (var) = __Pyx__GetModuleGlobalName(name)
 static CYTHON_INLINE PyObject *__Pyx__GetModuleGlobalName(PyObject *name);
 #endif
 
@@ -1768,21 +1901,29 @@
 #define __Pyx_PyFunction_FastCallDict(func, args, nargs, kwargs) _PyFunction_FastCallDict(func, args, nargs, kwargs)
 #endif
 #define __Pyx_BUILD_ASSERT_EXPR(cond)\
     (sizeof(char [1 - 2*!(cond)]) - 1)
 #ifndef Py_MEMBER_SIZE
 #define Py_MEMBER_SIZE(type, member) sizeof(((type *)0)->member)
 #endif
+#if CYTHON_FAST_PYCALL
   static size_t __pyx_pyframe_localsplus_offset = 0;
   #include "frameobject.h"
+#if PY_VERSION_HEX >= 0x030b00a6
+  #ifndef Py_BUILD_CORE
+    #define Py_BUILD_CORE 1
+  #endif
+  #include "internal/pycore_frame.h"
+#endif
   #define __Pxy_PyFrame_Initialize_Offsets()\
     ((void)__Pyx_BUILD_ASSERT_EXPR(sizeof(PyFrameObject) == offsetof(PyFrameObject, f_localsplus) + Py_MEMBER_SIZE(PyFrameObject, f_localsplus)),\
      (void)(__pyx_pyframe_localsplus_offset = ((size_t)PyFrame_Type.tp_basicsize) - Py_MEMBER_SIZE(PyFrameObject, f_localsplus)))
   #define __Pyx_PyFrame_GetLocalsplus(frame)\
     (assert(__pyx_pyframe_localsplus_offset), (PyObject **)(((char *)(frame)) + __pyx_pyframe_localsplus_offset))
+#endif // CYTHON_FAST_PYCALL
 #endif
 
 /* PyCFunctionFastCall.proto */
 #if CYTHON_FAST_PYCCALL
 static CYTHON_INLINE PyObject *__Pyx_PyCFunction_FastCall(PyObject *func, PyObject **args, Py_ssize_t nargs);
 #else
 #define __Pyx_PyCFunction_FastCall(func, args, nargs)  (assert(0), NULL)
@@ -2097,22 +2238,30 @@
 /* PyObjectGetAttrStrNoError.proto */
 static CYTHON_INLINE PyObject* __Pyx_PyObject_GetAttrStrNoError(PyObject* obj, PyObject* attr_name);
 
 /* SetupReduce.proto */
 static int __Pyx_setup_reduce(PyObject* type_obj);
 
 /* TypeImport.proto */
-#ifndef __PYX_HAVE_RT_ImportType_proto
-#define __PYX_HAVE_RT_ImportType_proto
-enum __Pyx_ImportType_CheckSize {
-   __Pyx_ImportType_CheckSize_Error = 0,
-   __Pyx_ImportType_CheckSize_Warn = 1,
-   __Pyx_ImportType_CheckSize_Ignore = 2
+#ifndef __PYX_HAVE_RT_ImportType_proto_0_29_35
+#define __PYX_HAVE_RT_ImportType_proto_0_29_35
+#if __STDC_VERSION__ >= 201112L
+#include <stdalign.h>
+#endif
+#if __STDC_VERSION__ >= 201112L || __cplusplus >= 201103L
+#define __PYX_GET_STRUCT_ALIGNMENT_0_29_35(s) alignof(s)
+#else
+#define __PYX_GET_STRUCT_ALIGNMENT_0_29_35(s) sizeof(void*)
+#endif
+enum __Pyx_ImportType_CheckSize_0_29_35 {
+   __Pyx_ImportType_CheckSize_Error_0_29_35 = 0,
+   __Pyx_ImportType_CheckSize_Warn_0_29_35 = 1,
+   __Pyx_ImportType_CheckSize_Ignore_0_29_35 = 2
 };
-static PyTypeObject *__Pyx_ImportType(PyObject* module, const char *module_name, const char *class_name, size_t size, enum __Pyx_ImportType_CheckSize check_size);
+static PyTypeObject *__Pyx_ImportType_0_29_35(PyObject* module, const char *module_name, const char *class_name, size_t size, size_t alignment, enum __Pyx_ImportType_CheckSize_0_29_35 check_size);
 #endif
 
 /* GetVTable.proto */
 static void* __Pyx_GetVtable(PyObject *dict);
 
 /* CLineInTraceback.proto */
 #ifdef CYTHON_CLINE_IN_TRACEBACK
@@ -2663,45 +2812,45 @@
 static const char __pyx_k_detection_detectors_enabled[] = "detection/detectors/{}/enabled";
 static const char __pyx_k_PartialDecomposition_nBlocks[] = "<PartialDecomposition: nBlocks=";
 static const char __pyx_k_setPricingSolverExactEnabled[] = "setPricingSolverExactEnabled";
 static const char __pyx_k_pyx_unpickle_PY_GCG_PRICINGSTA[] = "__pyx_unpickle_PY_GCG_PRICINGSTATUS";
 static const char __pyx_k_is_not_supported_Only_svg_and_p[] = " is not supported. Only \"svg\" and \"png\" are supported.";
 static const char __pyx_k_Detector_callback_returned_of_ty[] = "Detector callback returned '{}' of type '{}'. Expected a dictionary with optional keys 'newpartialdecs' and 'result'.";
 static const char __pyx_k_Expected_iterable_as_first_argum[] = "Expected iterable as first argument. Got '{}' instead.";
-static const char __pyx_k_Incompatible_checksums_s_vs_0x7a[] = "Incompatible checksums (%s vs 0x7a6ef99 = (model, solvername))";
-static const char __pyx_k_Incompatible_checksums_s_vs_0xd4[] = "Incompatible checksums (%s vs 0xd41d8cd = ())";
-static const char __pyx_k_Incompatible_checksums_s_vs_0xf7[] = "Incompatible checksums (%s vs 0xf7f977a = (detectorname, model))";
+static const char __pyx_k_Incompatible_checksums_0x_x_vs_0[] = "Incompatible checksums (0x%x vs (0xf7f977a, 0xdad04ef, 0x67e9880) = (detectorname, model))";
 static const char __pyx_k_Length_of_value_for_decchar_must[] = "Length of value for 'decchar' must be 1";
 static const char __pyx_k_The_value_of_the_key_newpartiald[] = "The value of the key 'newpartialdecs' is '{}' of type '{}'. Expected a list of 'PartialDecomposition' objects.";
 static const char __pyx_k_cannot_create_Column_with_GCG_CO[] = "cannot create Column with GCG_COL* == NULL";
 static const char __pyx_k_cannot_create_ConsPart_with_Cons[] = "cannot create ConsPart with ConsPartition* == NULL";
 static const char __pyx_k_cannot_create_DetProbData_with_D[] = "cannot create DetProbData with DETPROBDATA* == NULL";
 static const char __pyx_k_cannot_create_Model_with_SCIP_NU[] = "cannot create Model with SCIP* == NULL";
 static const char __pyx_k_cannot_create_PartialDecompositi[] = "cannot create PartialDecomposition with PARTIALDECOMP* == NULL";
 static const char __pyx_k_cannot_create_VarPart_with_VarPa[] = "cannot create VarPart with VarPartition* == NULL";
 static const char __pyx_k_detection_detectors_finishingena[] = "detection/detectors/{}/finishingenabled";
 static const char __pyx_k_detection_detectors_postprocessi[] = "detection/detectors/{}/postprocessingenabled";
 static const char __pyx_k_no_default___reduce___due_to_non[] = "no default __reduce__ due to non-trivial __cinit__";
 static const char __pyx_k_self__scip_self__valid_cannot_be[] = "self._scip,self._valid cannot be converted to a Python object for pickling";
 static const char __pyx_k_self_gcg_col_cannot_be_converted[] = "self.gcg_col cannot be converted to a Python object for pickling";
 static const char __pyx_k_setPricingSolverHeuristicEnabled[] = "setPricingSolverHeuristicEnabled";
+static const char __pyx_k_Incompatible_checksums_0x_x_vs_0_2[] = "Incompatible checksums (0x%x vs (0x7a6ef99, 0x9896ff5, 0x8734839) = (model, solvername))";
+static const char __pyx_k_Incompatible_checksums_0x_x_vs_0_3[] = "Incompatible checksums (0x%x vs (0xd41d8cd, 0xe3b0c44, 0xda39a3e) = ())";
 static PyObject *__pyx_n_s_ConsPart;
 static PyObject *__pyx_kp_u_ConsPart_name;
 static PyObject *__pyx_n_s_DetProbData;
 static PyObject *__pyx_n_s_Detector;
 static PyObject *__pyx_kp_u_Detector_callback_returned_of_ty;
 static PyObject *__pyx_kp_u_Expected_iterable_as_first_argum;
 static PyObject *__pyx_kp_u_Format;
 static PyObject *__pyx_n_s_GCGColumn;
 static PyObject *__pyx_n_s_GCGMasterModel;
 static PyObject *__pyx_n_s_GCGPricingModel;
 static PyObject *__pyx_n_s_INFEASIBLE;
-static PyObject *__pyx_kp_s_Incompatible_checksums_s_vs_0x7a;
-static PyObject *__pyx_kp_s_Incompatible_checksums_s_vs_0xd4;
-static PyObject *__pyx_kp_s_Incompatible_checksums_s_vs_0xf7;
+static PyObject *__pyx_kp_s_Incompatible_checksums_0x_x_vs_0;
+static PyObject *__pyx_kp_s_Incompatible_checksums_0x_x_vs_0_2;
+static PyObject *__pyx_kp_s_Incompatible_checksums_0x_x_vs_0_3;
 static PyObject *__pyx_n_s_Iterable;
 static PyObject *__pyx_kp_u_Length_of_value_for_decchar_must;
 static PyObject *__pyx_n_s_List;
 static PyObject *__pyx_n_s_Model;
 static PyObject *__pyx_n_s_NOTAPPLICABLE;
 static PyObject *__pyx_n_s_NotImplementedError;
 static PyObject *__pyx_n_s_OPTIMAL;
@@ -3282,22 +3431,24 @@
 static PyObject *__pyx_pf_8pygcgopt_3gcg_5Model_40listDetectors(struct __pyx_obj_8pygcgopt_3gcg_Model *__pyx_v_self); /* proto */
 static PyObject *__pyx_pf_8pygcgopt_3gcg_5Model_42setDetectorEnabled(struct __pyx_obj_8pygcgopt_3gcg_Model *__pyx_v_self, PyObject *__pyx_v_detector_name, PyObject *__pyx_v_is_enabled); /* proto */
 static PyObject *__pyx_pf_8pygcgopt_3gcg_5Model_44setDetectorFinishingEnabled(struct __pyx_obj_8pygcgopt_3gcg_Model *__pyx_v_self, PyObject *__pyx_v_detector_name, PyObject *__pyx_v_is_enabled); /* proto */
 static PyObject *__pyx_pf_8pygcgopt_3gcg_5Model_46setDetectorPostprocessingEnabled(struct __pyx_obj_8pygcgopt_3gcg_Model *__pyx_v_self, PyObject *__pyx_v_detector_name, PyObject *__pyx_v_is_enabled); /* proto */
 static PyObject *__pyx_pf_8pygcgopt_3gcg_5Model_48getMasterProb(struct __pyx_obj_8pygcgopt_3gcg_Model *__pyx_v_self); /* proto */
 static PyObject *__pyx_pf_8pygcgopt_3gcg_5Model_50setGCGSeparating(struct __pyx_obj_8pygcgopt_3gcg_Model *__pyx_v_self, PyObject *__pyx_v_setting); /* proto */
 static PyObject *__pyx_pf_8pygcgopt_3gcg_5Model_52writeAllDecomps(struct __pyx_obj_8pygcgopt_3gcg_Model *__pyx_v_self, PyObject *__pyx_v_directory, PyObject *__pyx_v_extension, bool __pyx_v_original, bool __pyx_v_presolved, PyObject *__pyx_v_createDirectory); /* proto */
-static PyObject *__pyx_pf_8pygcgopt_3gcg_5Model_54__reduce_cython__(CYTHON_UNUSED struct __pyx_obj_8pygcgopt_3gcg_Model *__pyx_v_self); /* proto */
-static PyObject *__pyx_pf_8pygcgopt_3gcg_5Model_56__setstate_cython__(CYTHON_UNUSED struct __pyx_obj_8pygcgopt_3gcg_Model *__pyx_v_self, CYTHON_UNUSED PyObject *__pyx_v___pyx_state); /* proto */
+static PyObject *__pyx_pf_8pygcgopt_3gcg_5Model_54getMastervars(CYTHON_UNUSED struct __pyx_obj_8pygcgopt_3gcg_Model *__pyx_v_self, PyObject *__pyx_v_var); /* proto */
+static PyObject *__pyx_pf_8pygcgopt_3gcg_5Model_56__reduce_cython__(CYTHON_UNUSED struct __pyx_obj_8pygcgopt_3gcg_Model *__pyx_v_self); /* proto */
+static PyObject *__pyx_pf_8pygcgopt_3gcg_5Model_58__setstate_cython__(CYTHON_UNUSED struct __pyx_obj_8pygcgopt_3gcg_Model *__pyx_v_self, CYTHON_UNUSED PyObject *__pyx_v___pyx_state); /* proto */
 static PyObject *__pyx_pf_8pygcgopt_3gcg_15GCGPricingModel_createGcgCol(struct __pyx_obj_8pygcgopt_3gcg_GCGPricingModel *__pyx_v_self, PyObject *__pyx_v_probnr, PyObject *__pyx_v_variables, PyObject *__pyx_v_vals, bool __pyx_v_isray, PyObject *__pyx_v_redcost); /* proto */
 static PyObject *__pyx_pf_8pygcgopt_3gcg_15GCGPricingModel_2__reduce_cython__(CYTHON_UNUSED struct __pyx_obj_8pygcgopt_3gcg_GCGPricingModel *__pyx_v_self); /* proto */
 static PyObject *__pyx_pf_8pygcgopt_3gcg_15GCGPricingModel_4__setstate_cython__(CYTHON_UNUSED struct __pyx_obj_8pygcgopt_3gcg_GCGPricingModel *__pyx_v_self, CYTHON_UNUSED PyObject *__pyx_v___pyx_state); /* proto */
 static PyObject *__pyx_pf_8pygcgopt_3gcg_14GCGMasterModel_addCol(struct __pyx_obj_8pygcgopt_3gcg_GCGMasterModel *__pyx_v_self, struct __pyx_obj_8pygcgopt_3gcg_GCGColumn *__pyx_v_col); /* proto */
-static PyObject *__pyx_pf_8pygcgopt_3gcg_14GCGMasterModel_2__reduce_cython__(CYTHON_UNUSED struct __pyx_obj_8pygcgopt_3gcg_GCGMasterModel *__pyx_v_self); /* proto */
-static PyObject *__pyx_pf_8pygcgopt_3gcg_14GCGMasterModel_4__setstate_cython__(CYTHON_UNUSED struct __pyx_obj_8pygcgopt_3gcg_GCGMasterModel *__pyx_v_self, CYTHON_UNUSED PyObject *__pyx_v___pyx_state); /* proto */
+static PyObject *__pyx_pf_8pygcgopt_3gcg_14GCGMasterModel_2getOrigvars(CYTHON_UNUSED struct __pyx_obj_8pygcgopt_3gcg_GCGMasterModel *__pyx_v_self, PyObject *__pyx_v_var); /* proto */
+static PyObject *__pyx_pf_8pygcgopt_3gcg_14GCGMasterModel_4__reduce_cython__(CYTHON_UNUSED struct __pyx_obj_8pygcgopt_3gcg_GCGMasterModel *__pyx_v_self); /* proto */
+static PyObject *__pyx_pf_8pygcgopt_3gcg_14GCGMasterModel_6__setstate_cython__(CYTHON_UNUSED struct __pyx_obj_8pygcgopt_3gcg_GCGMasterModel *__pyx_v_self, CYTHON_UNUSED PyObject *__pyx_v___pyx_state); /* proto */
 static Py_hash_t __pyx_pf_8pygcgopt_3gcg_9GCGColumn___hash__(struct __pyx_obj_8pygcgopt_3gcg_GCGColumn *__pyx_v_self); /* proto */
 static PyObject *__pyx_pf_8pygcgopt_3gcg_9GCGColumn_2__eq__(struct __pyx_obj_8pygcgopt_3gcg_GCGColumn *__pyx_v_self, PyObject *__pyx_v_other); /* proto */
 static PyObject *__pyx_pf_8pygcgopt_3gcg_9GCGColumn_4__reduce_cython__(CYTHON_UNUSED struct __pyx_obj_8pygcgopt_3gcg_GCGColumn *__pyx_v_self); /* proto */
 static PyObject *__pyx_pf_8pygcgopt_3gcg_9GCGColumn_6__setstate_cython__(CYTHON_UNUSED struct __pyx_obj_8pygcgopt_3gcg_GCGColumn *__pyx_v_self, CYTHON_UNUSED PyObject *__pyx_v___pyx_state); /* proto */
 static PyObject *__pyx_pf_8pygcgopt_3gcg___pyx_unpickle_Detector(CYTHON_UNUSED PyObject *__pyx_self, PyObject *__pyx_v___pyx_type, long __pyx_v___pyx_checksum, PyObject *__pyx_v___pyx_state); /* proto */
 static PyObject *__pyx_pf_8pygcgopt_3gcg_2__pyx_unpickle_PricingSolver(CYTHON_UNUSED PyObject *__pyx_self, PyObject *__pyx_v___pyx_type, long __pyx_v___pyx_checksum, PyObject *__pyx_v___pyx_state); /* proto */
 static PyObject *__pyx_pf_8pygcgopt_3gcg_4__pyx_unpickle_PY_GCG_PRICINGSTATUS(CYTHON_UNUSED PyObject *__pyx_self, PyObject *__pyx_v___pyx_type, long __pyx_v___pyx_checksum, PyObject *__pyx_v___pyx_state); /* proto */
@@ -3310,16 +3461,22 @@
 static PyObject *__pyx_tp_new_8pygcgopt_3gcg_DetProbData(PyTypeObject *t, PyObject *a, PyObject *k); /*proto*/
 static PyObject *__pyx_tp_new_8pygcgopt_3gcg_PY_GCG_PRICINGSTATUS(PyTypeObject *t, PyObject *a, PyObject *k); /*proto*/
 static PyObject *__pyx_tp_new_8pygcgopt_3gcg_Model(PyTypeObject *t, PyObject *a, PyObject *k); /*proto*/
 static PyObject *__pyx_tp_new_8pygcgopt_3gcg_GCGPricingModel(PyTypeObject *t, PyObject *a, PyObject *k); /*proto*/
 static PyObject *__pyx_tp_new_8pygcgopt_3gcg_GCGMasterModel(PyTypeObject *t, PyObject *a, PyObject *k); /*proto*/
 static PyObject *__pyx_int_0;
 static PyObject *__pyx_int_1;
+static PyObject *__pyx_int_108959872;
 static PyObject *__pyx_int_128380825;
+static PyObject *__pyx_int_141772857;
+static PyObject *__pyx_int_160002037;
 static PyObject *__pyx_int_222419149;
+static PyObject *__pyx_int_228825662;
+static PyObject *__pyx_int_229442799;
+static PyObject *__pyx_int_238750788;
 static PyObject *__pyx_int_260020090;
 static gcg::USERGIVEN __pyx_k__10;
 static PyObject *__pyx_k__18;
 static PyObject *__pyx_k__19;
 static PyObject *__pyx_tuple_;
 static PyObject *__pyx_tuple__2;
 static PyObject *__pyx_tuple__4;
@@ -3342,19 +3499,22 @@
 static PyObject *__pyx_tuple__25;
 static PyObject *__pyx_tuple__26;
 static PyObject *__pyx_tuple__27;
 static PyObject *__pyx_tuple__28;
 static PyObject *__pyx_tuple__29;
 static PyObject *__pyx_tuple__30;
 static PyObject *__pyx_tuple__31;
+static PyObject *__pyx_tuple__32;
 static PyObject *__pyx_tuple__33;
-static PyObject *__pyx_tuple__35;
-static PyObject *__pyx_codeobj__32;
-static PyObject *__pyx_codeobj__34;
-static PyObject *__pyx_codeobj__36;
+static PyObject *__pyx_tuple__34;
+static PyObject *__pyx_tuple__36;
+static PyObject *__pyx_tuple__38;
+static PyObject *__pyx_codeobj__35;
+static PyObject *__pyx_codeobj__37;
+static PyObject *__pyx_codeobj__39;
 /* Late includes */
 
 /* "src/pygcgopt/detector.pxi":6
  *     cdef public str detectorname
  * 
  *     def freeDetector(self):             # <<<<<<<<<<<<<<
  *         '''calls destructor and frees memory of detector'''
@@ -4064,15 +4224,15 @@
   int __pyx_r;
   __Pyx_RefNannyDeclarations
   PyObject *__pyx_t_1 = NULL;
   int __pyx_lineno = 0;
   const char *__pyx_filename = NULL;
   int __pyx_clineno = 0;
   __Pyx_RefNannySetupContext("__set__", 0);
-  if (!(likely(PyUnicode_CheckExact(__pyx_v_value))||((__pyx_v_value) == Py_None)||(PyErr_Format(PyExc_TypeError, "Expected %.16s, got %.200s", "unicode", Py_TYPE(__pyx_v_value)->tp_name), 0))) __PYX_ERR(0, 4, __pyx_L1_error)
+  if (!(likely(PyUnicode_CheckExact(__pyx_v_value))||((__pyx_v_value) == Py_None)||((void)PyErr_Format(PyExc_TypeError, "Expected %.16s, got %.200s", "unicode", Py_TYPE(__pyx_v_value)->tp_name), 0))) __PYX_ERR(0, 4, __pyx_L1_error)
   __pyx_t_1 = __pyx_v_value;
   __Pyx_INCREF(__pyx_t_1);
   __Pyx_GIVEREF(__pyx_t_1);
   __Pyx_GOTREF(__pyx_v_self->detectorname);
   __Pyx_DECREF(__pyx_v_self->detectorname);
   __pyx_v_self->detectorname = ((PyObject*)__pyx_t_1);
   __pyx_t_1 = 0;
@@ -4398,15 +4558,15 @@
   __Pyx_RefNannySetupContext("__setstate_cython__", 0);
 
   /* "(tree fragment)":17
  *         return __pyx_unpickle_Detector, (type(self), 0xf7f977a, state)
  * def __setstate_cython__(self, __pyx_state):
  *     __pyx_unpickle_Detector__set_state(self, __pyx_state)             # <<<<<<<<<<<<<<
  */
-  if (!(likely(PyTuple_CheckExact(__pyx_v___pyx_state))||((__pyx_v___pyx_state) == Py_None)||(PyErr_Format(PyExc_TypeError, "Expected %.16s, got %.200s", "tuple", Py_TYPE(__pyx_v___pyx_state)->tp_name), 0))) __PYX_ERR(4, 17, __pyx_L1_error)
+  if (!(likely(PyTuple_CheckExact(__pyx_v___pyx_state))||((__pyx_v___pyx_state) == Py_None)||((void)PyErr_Format(PyExc_TypeError, "Expected %.16s, got %.200s", "tuple", Py_TYPE(__pyx_v___pyx_state)->tp_name), 0))) __PYX_ERR(4, 17, __pyx_L1_error)
   __pyx_t_1 = __pyx_f_8pygcgopt_3gcg___pyx_unpickle_Detector__set_state(__pyx_v_self, ((PyObject*)__pyx_v___pyx_state)); if (unlikely(!__pyx_t_1)) __PYX_ERR(4, 17, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_1);
   __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
 
   /* "(tree fragment)":16
  *     else:
  *         return __pyx_unpickle_Detector, (type(self), 0xf7f977a, state)
@@ -7262,15 +7422,15 @@
   int __pyx_r;
   __Pyx_RefNannyDeclarations
   PyObject *__pyx_t_1 = NULL;
   int __pyx_lineno = 0;
   const char *__pyx_filename = NULL;
   int __pyx_clineno = 0;
   __Pyx_RefNannySetupContext("__set__", 0);
-  if (!(likely(PyUnicode_CheckExact(__pyx_v_value))||((__pyx_v_value) == Py_None)||(PyErr_Format(PyExc_TypeError, "Expected %.16s, got %.200s", "unicode", Py_TYPE(__pyx_v_value)->tp_name), 0))) __PYX_ERR(5, 5, __pyx_L1_error)
+  if (!(likely(PyUnicode_CheckExact(__pyx_v_value))||((__pyx_v_value) == Py_None)||((void)PyErr_Format(PyExc_TypeError, "Expected %.16s, got %.200s", "unicode", Py_TYPE(__pyx_v_value)->tp_name), 0))) __PYX_ERR(5, 5, __pyx_L1_error)
   __pyx_t_1 = __pyx_v_value;
   __Pyx_INCREF(__pyx_t_1);
   __Pyx_GIVEREF(__pyx_t_1);
   __Pyx_GOTREF(__pyx_v_self->solvername);
   __Pyx_DECREF(__pyx_v_self->solvername);
   __pyx_v_self->solvername = ((PyObject*)__pyx_t_1);
   __pyx_t_1 = 0;
@@ -7596,15 +7756,15 @@
   __Pyx_RefNannySetupContext("__setstate_cython__", 0);
 
   /* "(tree fragment)":17
  *         return __pyx_unpickle_PricingSolver, (type(self), 0x7a6ef99, state)
  * def __setstate_cython__(self, __pyx_state):
  *     __pyx_unpickle_PricingSolver__set_state(self, __pyx_state)             # <<<<<<<<<<<<<<
  */
-  if (!(likely(PyTuple_CheckExact(__pyx_v___pyx_state))||((__pyx_v___pyx_state) == Py_None)||(PyErr_Format(PyExc_TypeError, "Expected %.16s, got %.200s", "tuple", Py_TYPE(__pyx_v___pyx_state)->tp_name), 0))) __PYX_ERR(4, 17, __pyx_L1_error)
+  if (!(likely(PyTuple_CheckExact(__pyx_v___pyx_state))||((__pyx_v___pyx_state) == Py_None)||((void)PyErr_Format(PyExc_TypeError, "Expected %.16s, got %.200s", "tuple", Py_TYPE(__pyx_v___pyx_state)->tp_name), 0))) __PYX_ERR(4, 17, __pyx_L1_error)
   __pyx_t_1 = __pyx_f_8pygcgopt_3gcg___pyx_unpickle_PricingSolver__set_state(__pyx_v_self, ((PyObject*)__pyx_v___pyx_state)); if (unlikely(!__pyx_t_1)) __PYX_ERR(4, 17, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_1);
   __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
 
   /* "(tree fragment)":16
  *     else:
  *         return __pyx_unpickle_PricingSolver, (type(self), 0x7a6ef99, state)
@@ -30317,15 +30477,15 @@
   int __pyx_r;
   __Pyx_RefNannyDeclarations
   PyObject *__pyx_t_1 = NULL;
   int __pyx_lineno = 0;
   const char *__pyx_filename = NULL;
   int __pyx_clineno = 0;
   __Pyx_RefNannySetupContext("__set__", 0);
-  if (!(likely(PyDict_CheckExact(__pyx_v_value))||((__pyx_v_value) == Py_None)||(PyErr_Format(PyExc_TypeError, "Expected %.16s, got %.200s", "dict", Py_TYPE(__pyx_v_value)->tp_name), 0))) __PYX_ERR(2, 10, __pyx_L1_error)
+  if (!(likely(PyDict_CheckExact(__pyx_v_value))||((__pyx_v_value) == Py_None)||((void)PyErr_Format(PyExc_TypeError, "Expected %.16s, got %.200s", "dict", Py_TYPE(__pyx_v_value)->tp_name), 0))) __PYX_ERR(2, 10, __pyx_L1_error)
   __pyx_t_1 = __pyx_v_value;
   __Pyx_INCREF(__pyx_t_1);
   __Pyx_GIVEREF(__pyx_t_1);
   __Pyx_GOTREF(__pyx_v_self->_visualizations);
   __Pyx_DECREF(__pyx_v_self->_visualizations);
   __pyx_v_self->_visualizations = ((PyObject*)__pyx_t_1);
   __pyx_t_1 = 0;
@@ -37804,15 +37964,15 @@
   __Pyx_RefNannySetupContext("__setstate_cython__", 0);
 
   /* "(tree fragment)":17
  *         return __pyx_unpickle_PY_GCG_PRICINGSTATUS, (type(self), 0xd41d8cd, state)
  * def __setstate_cython__(self, __pyx_state):
  *     __pyx_unpickle_PY_GCG_PRICINGSTATUS__set_state(self, __pyx_state)             # <<<<<<<<<<<<<<
  */
-  if (!(likely(PyTuple_CheckExact(__pyx_v___pyx_state))||((__pyx_v___pyx_state) == Py_None)||(PyErr_Format(PyExc_TypeError, "Expected %.16s, got %.200s", "tuple", Py_TYPE(__pyx_v___pyx_state)->tp_name), 0))) __PYX_ERR(4, 17, __pyx_L1_error)
+  if (!(likely(PyTuple_CheckExact(__pyx_v___pyx_state))||((__pyx_v___pyx_state) == Py_None)||((void)PyErr_Format(PyExc_TypeError, "Expected %.16s, got %.200s", "tuple", Py_TYPE(__pyx_v___pyx_state)->tp_name), 0))) __PYX_ERR(4, 17, __pyx_L1_error)
   __pyx_t_1 = __pyx_f_8pygcgopt_3gcg___pyx_unpickle_PY_GCG_PRICINGSTATUS__set_state(__pyx_v_self, ((PyObject*)__pyx_v___pyx_state)); if (unlikely(!__pyx_t_1)) __PYX_ERR(4, 17, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_1);
   __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
 
   /* "(tree fragment)":16
  *     else:
  *         return __pyx_unpickle_PY_GCG_PRICINGSTATUS, (type(self), 0xd41d8cd, state)
@@ -39817,15 +39977,15 @@
   /* "pygcgopt/gcg.pyx":192
  * 
  *         pricingSolver.model = <SCIPModel>weakref.proxy(self)
  *         pricingSolver.solvername = solvername             # <<<<<<<<<<<<<<
  *         Py_INCREF(pricingSolver)
  * 
  */
-  if (!(likely(PyUnicode_CheckExact(__pyx_v_solvername))||((__pyx_v_solvername) == Py_None)||(PyErr_Format(PyExc_TypeError, "Expected %.16s, got %.200s", "unicode", Py_TYPE(__pyx_v_solvername)->tp_name), 0))) __PYX_ERR(3, 192, __pyx_L1_error)
+  if (!(likely(PyUnicode_CheckExact(__pyx_v_solvername))||((__pyx_v_solvername) == Py_None)||((void)PyErr_Format(PyExc_TypeError, "Expected %.16s, got %.200s", "unicode", Py_TYPE(__pyx_v_solvername)->tp_name), 0))) __PYX_ERR(3, 192, __pyx_L1_error)
   __pyx_t_4 = __pyx_v_solvername;
   __Pyx_INCREF(__pyx_t_4);
   __Pyx_GIVEREF(__pyx_t_4);
   __Pyx_GOTREF(__pyx_v_pricingSolver->solvername);
   __Pyx_DECREF(__pyx_v_pricingSolver->solvername);
   __pyx_v_pricingSolver->solvername = ((PyObject*)__pyx_t_4);
   __pyx_t_4 = 0;
@@ -41130,15 +41290,15 @@
   /* "pygcgopt/gcg.pyx":262
  * 
  *         detector.model = <SCIPModel>weakref.proxy(self)
  *         detector.detectorname = detectorname             # <<<<<<<<<<<<<<
  *         Py_INCREF(detector)
  * 
  */
-  if (!(likely(PyUnicode_CheckExact(__pyx_v_detectorname))||((__pyx_v_detectorname) == Py_None)||(PyErr_Format(PyExc_TypeError, "Expected %.16s, got %.200s", "unicode", Py_TYPE(__pyx_v_detectorname)->tp_name), 0))) __PYX_ERR(3, 262, __pyx_L1_error)
+  if (!(likely(PyUnicode_CheckExact(__pyx_v_detectorname))||((__pyx_v_detectorname) == Py_None)||((void)PyErr_Format(PyExc_TypeError, "Expected %.16s, got %.200s", "unicode", Py_TYPE(__pyx_v_detectorname)->tp_name), 0))) __PYX_ERR(3, 262, __pyx_L1_error)
   __pyx_t_5 = __pyx_v_detectorname;
   __Pyx_INCREF(__pyx_t_5);
   __Pyx_GIVEREF(__pyx_t_5);
   __Pyx_GOTREF(__pyx_v_detector->detectorname);
   __Pyx_DECREF(__pyx_v_detector->detectorname);
   __pyx_v_detector->detectorname = ((PyObject*)__pyx_t_5);
   __pyx_t_5 = 0;
@@ -42271,15 +42431,15 @@
   __pyx_t_4 = 0;
 
   /* "pygcgopt/gcg.pyx":349
  *         c_directory = str_conversion(directory)
  *         c_extension = str_conversion(extension)
  *         PY_SCIP_CALL(DECwriteAllDecomps(self._scip, c_directory, c_extension, original, presolved))             # <<<<<<<<<<<<<<
  * 
- * 
+ *     def getMastervars(self, var):
  */
   __Pyx_GetModuleGlobalName(__pyx_t_2, __pyx_n_s_PY_SCIP_CALL); if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 349, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_2);
   __pyx_t_5 = __Pyx_PyObject_AsWritableString(__pyx_v_c_directory); if (unlikely((!__pyx_t_5) && PyErr_Occurred())) __PYX_ERR(3, 349, __pyx_L1_error)
   __pyx_t_6 = __Pyx_PyObject_AsWritableString(__pyx_v_c_extension); if (unlikely((!__pyx_t_6) && PyErr_Occurred())) __PYX_ERR(3, 349, __pyx_L1_error)
   __pyx_t_3 = __Pyx_PyInt_From_SCIP_RETCODE(DECwriteAllDecomps(__pyx_v_self->__pyx_base._scip, __pyx_t_5, __pyx_t_6, __pyx_v_original, __pyx_v_presolved)); if (unlikely(!__pyx_t_3)) __PYX_ERR(3, 349, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_3);
@@ -42323,35 +42483,136 @@
   __Pyx_XDECREF(__pyx_v_c_directory);
   __Pyx_XDECREF(__pyx_v_c_extension);
   __Pyx_XGIVEREF(__pyx_r);
   __Pyx_RefNannyFinishContext();
   return __pyx_r;
 }
 
+/* "pygcgopt/gcg.pyx":351
+ *         PY_SCIP_CALL(DECwriteAllDecomps(self._scip, c_directory, c_extension, original, presolved))
+ * 
+ *     def getMastervars(self, var):             # <<<<<<<<<<<<<<
+ *         """Returns the master variables corresponding to the variable of original problem
+ * 
+ */
+
+/* Python wrapper */
+static PyObject *__pyx_pw_8pygcgopt_3gcg_5Model_55getMastervars(PyObject *__pyx_v_self, PyObject *__pyx_v_var); /*proto*/
+static char __pyx_doc_8pygcgopt_3gcg_5Model_54getMastervars[] = "Model.getMastervars(self, var)\nReturns the master variables corresponding to the variable of original problem\n\n        :param var: Variable of original problem\n        :return: List of master variables\n        ";
+static PyObject *__pyx_pw_8pygcgopt_3gcg_5Model_55getMastervars(PyObject *__pyx_v_self, PyObject *__pyx_v_var) {
+  PyObject *__pyx_r = 0;
+  __Pyx_RefNannyDeclarations
+  __Pyx_RefNannySetupContext("getMastervars (wrapper)", 0);
+  __pyx_r = __pyx_pf_8pygcgopt_3gcg_5Model_54getMastervars(((struct __pyx_obj_8pygcgopt_3gcg_Model *)__pyx_v_self), ((PyObject *)__pyx_v_var));
+
+  /* function exit code */
+  __Pyx_RefNannyFinishContext();
+  return __pyx_r;
+}
+
+static PyObject *__pyx_pf_8pygcgopt_3gcg_5Model_54getMastervars(CYTHON_UNUSED struct __pyx_obj_8pygcgopt_3gcg_Model *__pyx_v_self, PyObject *__pyx_v_var) {
+  int __pyx_v_n_vars;
+  SCIP_VAR **__pyx_v_mastervars;
+  int __pyx_9genexpr15__pyx_v_i;
+  PyObject *__pyx_r = NULL;
+  __Pyx_RefNannyDeclarations
+  PyObject *__pyx_t_1 = NULL;
+  int __pyx_t_2;
+  int __pyx_t_3;
+  int __pyx_t_4;
+  PyObject *__pyx_t_5 = NULL;
+  int __pyx_lineno = 0;
+  const char *__pyx_filename = NULL;
+  int __pyx_clineno = 0;
+  __Pyx_RefNannySetupContext("getMastervars", 0);
+
+  /* "pygcgopt/gcg.pyx":357
+ *         :return: List of master variables
+ *         """
+ *         cdef int n_vars = GCGoriginalVarGetNMastervars((<Variable>var).scip_var)             # <<<<<<<<<<<<<<
+ *         cdef SCIP_VAR** mastervars = GCGoriginalVarGetMastervars((<Variable>var).scip_var)
+ *         return [Variable.create(mastervars[i]) for i in range(n_vars)]
+ */
+  __pyx_v_n_vars = GCGoriginalVarGetNMastervars(((struct __pyx_obj_9pyscipopt_4scip_Variable *)__pyx_v_var)->scip_var);
+
+  /* "pygcgopt/gcg.pyx":358
+ *         """
+ *         cdef int n_vars = GCGoriginalVarGetNMastervars((<Variable>var).scip_var)
+ *         cdef SCIP_VAR** mastervars = GCGoriginalVarGetMastervars((<Variable>var).scip_var)             # <<<<<<<<<<<<<<
+ *         return [Variable.create(mastervars[i]) for i in range(n_vars)]
+ * 
+ */
+  __pyx_v_mastervars = GCGoriginalVarGetMastervars(((struct __pyx_obj_9pyscipopt_4scip_Variable *)__pyx_v_var)->scip_var);
+
+  /* "pygcgopt/gcg.pyx":359
+ *         cdef int n_vars = GCGoriginalVarGetNMastervars((<Variable>var).scip_var)
+ *         cdef SCIP_VAR** mastervars = GCGoriginalVarGetMastervars((<Variable>var).scip_var)
+ *         return [Variable.create(mastervars[i]) for i in range(n_vars)]             # <<<<<<<<<<<<<<
+ * 
+ * 
+ */
+  __Pyx_XDECREF(__pyx_r);
+  { /* enter inner scope */
+    __pyx_t_1 = PyList_New(0); if (unlikely(!__pyx_t_1)) __PYX_ERR(3, 359, __pyx_L1_error)
+    __Pyx_GOTREF(__pyx_t_1);
+    __pyx_t_2 = __pyx_v_n_vars;
+    __pyx_t_3 = __pyx_t_2;
+    for (__pyx_t_4 = 0; __pyx_t_4 < __pyx_t_3; __pyx_t_4+=1) {
+      __pyx_9genexpr15__pyx_v_i = __pyx_t_4;
+      __pyx_t_5 = __pyx_vtabptr_9pyscipopt_4scip_Variable->create((__pyx_v_mastervars[__pyx_9genexpr15__pyx_v_i])); if (unlikely(!__pyx_t_5)) __PYX_ERR(3, 359, __pyx_L1_error)
+      __Pyx_GOTREF(__pyx_t_5);
+      if (unlikely(__Pyx_ListComp_Append(__pyx_t_1, (PyObject*)__pyx_t_5))) __PYX_ERR(3, 359, __pyx_L1_error)
+      __Pyx_DECREF(__pyx_t_5); __pyx_t_5 = 0;
+    }
+  } /* exit inner scope */
+  __pyx_r = __pyx_t_1;
+  __pyx_t_1 = 0;
+  goto __pyx_L0;
+
+  /* "pygcgopt/gcg.pyx":351
+ *         PY_SCIP_CALL(DECwriteAllDecomps(self._scip, c_directory, c_extension, original, presolved))
+ * 
+ *     def getMastervars(self, var):             # <<<<<<<<<<<<<<
+ *         """Returns the master variables corresponding to the variable of original problem
+ * 
+ */
+
+  /* function exit code */
+  __pyx_L1_error:;
+  __Pyx_XDECREF(__pyx_t_1);
+  __Pyx_XDECREF(__pyx_t_5);
+  __Pyx_AddTraceback("pygcgopt.gcg.Model.getMastervars", __pyx_clineno, __pyx_lineno, __pyx_filename);
+  __pyx_r = NULL;
+  __pyx_L0:;
+  __Pyx_XGIVEREF(__pyx_r);
+  __Pyx_RefNannyFinishContext();
+  return __pyx_r;
+}
+
 /* "(tree fragment)":1
  * def __reduce_cython__(self):             # <<<<<<<<<<<<<<
  *     raise TypeError("self._scip,self._valid cannot be converted to a Python object for pickling")
  * def __setstate_cython__(self, __pyx_state):
  */
 
 /* Python wrapper */
-static PyObject *__pyx_pw_8pygcgopt_3gcg_5Model_55__reduce_cython__(PyObject *__pyx_v_self, CYTHON_UNUSED PyObject *unused); /*proto*/
-static char __pyx_doc_8pygcgopt_3gcg_5Model_54__reduce_cython__[] = "Model.__reduce_cython__(self)";
-static PyObject *__pyx_pw_8pygcgopt_3gcg_5Model_55__reduce_cython__(PyObject *__pyx_v_self, CYTHON_UNUSED PyObject *unused) {
+static PyObject *__pyx_pw_8pygcgopt_3gcg_5Model_57__reduce_cython__(PyObject *__pyx_v_self, CYTHON_UNUSED PyObject *unused); /*proto*/
+static char __pyx_doc_8pygcgopt_3gcg_5Model_56__reduce_cython__[] = "Model.__reduce_cython__(self)";
+static PyObject *__pyx_pw_8pygcgopt_3gcg_5Model_57__reduce_cython__(PyObject *__pyx_v_self, CYTHON_UNUSED PyObject *unused) {
   PyObject *__pyx_r = 0;
   __Pyx_RefNannyDeclarations
   __Pyx_RefNannySetupContext("__reduce_cython__ (wrapper)", 0);
-  __pyx_r = __pyx_pf_8pygcgopt_3gcg_5Model_54__reduce_cython__(((struct __pyx_obj_8pygcgopt_3gcg_Model *)__pyx_v_self));
+  __pyx_r = __pyx_pf_8pygcgopt_3gcg_5Model_56__reduce_cython__(((struct __pyx_obj_8pygcgopt_3gcg_Model *)__pyx_v_self));
 
   /* function exit code */
   __Pyx_RefNannyFinishContext();
   return __pyx_r;
 }
 
-static PyObject *__pyx_pf_8pygcgopt_3gcg_5Model_54__reduce_cython__(CYTHON_UNUSED struct __pyx_obj_8pygcgopt_3gcg_Model *__pyx_v_self) {
+static PyObject *__pyx_pf_8pygcgopt_3gcg_5Model_56__reduce_cython__(CYTHON_UNUSED struct __pyx_obj_8pygcgopt_3gcg_Model *__pyx_v_self) {
   PyObject *__pyx_r = NULL;
   __Pyx_RefNannyDeclarations
   PyObject *__pyx_t_1 = NULL;
   int __pyx_lineno = 0;
   const char *__pyx_filename = NULL;
   int __pyx_clineno = 0;
   __Pyx_RefNannySetupContext("__reduce_cython__", 0);
@@ -42388,28 +42649,28 @@
  * def __reduce_cython__(self):
  *     raise TypeError("self._scip,self._valid cannot be converted to a Python object for pickling")
  * def __setstate_cython__(self, __pyx_state):             # <<<<<<<<<<<<<<
  *     raise TypeError("self._scip,self._valid cannot be converted to a Python object for pickling")
  */
 
 /* Python wrapper */
-static PyObject *__pyx_pw_8pygcgopt_3gcg_5Model_57__setstate_cython__(PyObject *__pyx_v_self, PyObject *__pyx_v___pyx_state); /*proto*/
-static char __pyx_doc_8pygcgopt_3gcg_5Model_56__setstate_cython__[] = "Model.__setstate_cython__(self, __pyx_state)";
-static PyObject *__pyx_pw_8pygcgopt_3gcg_5Model_57__setstate_cython__(PyObject *__pyx_v_self, PyObject *__pyx_v___pyx_state) {
+static PyObject *__pyx_pw_8pygcgopt_3gcg_5Model_59__setstate_cython__(PyObject *__pyx_v_self, PyObject *__pyx_v___pyx_state); /*proto*/
+static char __pyx_doc_8pygcgopt_3gcg_5Model_58__setstate_cython__[] = "Model.__setstate_cython__(self, __pyx_state)";
+static PyObject *__pyx_pw_8pygcgopt_3gcg_5Model_59__setstate_cython__(PyObject *__pyx_v_self, PyObject *__pyx_v___pyx_state) {
   PyObject *__pyx_r = 0;
   __Pyx_RefNannyDeclarations
   __Pyx_RefNannySetupContext("__setstate_cython__ (wrapper)", 0);
-  __pyx_r = __pyx_pf_8pygcgopt_3gcg_5Model_56__setstate_cython__(((struct __pyx_obj_8pygcgopt_3gcg_Model *)__pyx_v_self), ((PyObject *)__pyx_v___pyx_state));
+  __pyx_r = __pyx_pf_8pygcgopt_3gcg_5Model_58__setstate_cython__(((struct __pyx_obj_8pygcgopt_3gcg_Model *)__pyx_v_self), ((PyObject *)__pyx_v___pyx_state));
 
   /* function exit code */
   __Pyx_RefNannyFinishContext();
   return __pyx_r;
 }
 
-static PyObject *__pyx_pf_8pygcgopt_3gcg_5Model_56__setstate_cython__(CYTHON_UNUSED struct __pyx_obj_8pygcgopt_3gcg_Model *__pyx_v_self, CYTHON_UNUSED PyObject *__pyx_v___pyx_state) {
+static PyObject *__pyx_pf_8pygcgopt_3gcg_5Model_58__setstate_cython__(CYTHON_UNUSED struct __pyx_obj_8pygcgopt_3gcg_Model *__pyx_v_self, CYTHON_UNUSED PyObject *__pyx_v___pyx_state) {
   PyObject *__pyx_r = NULL;
   __Pyx_RefNannyDeclarations
   PyObject *__pyx_t_1 = NULL;
   int __pyx_lineno = 0;
   const char *__pyx_filename = NULL;
   int __pyx_clineno = 0;
   __Pyx_RefNannySetupContext("__setstate_cython__", 0);
@@ -42438,15 +42699,15 @@
   __Pyx_AddTraceback("pygcgopt.gcg.Model.__setstate_cython__", __pyx_clineno, __pyx_lineno, __pyx_filename);
   __pyx_r = NULL;
   __Pyx_XGIVEREF(__pyx_r);
   __Pyx_RefNannyFinishContext();
   return __pyx_r;
 }
 
-/* "pygcgopt/gcg.pyx":354
+/* "pygcgopt/gcg.pyx":364
  * cdef class GCGPricingModel(SCIPModel):
  *     @staticmethod
  *     cdef create(SCIP* scip):             # <<<<<<<<<<<<<<
  *         """Creates a pricing problem model and appropriately assigns the scip and bestsol parameters
  *         """
  */
 
@@ -42458,100 +42719,100 @@
   PyObject *__pyx_t_2 = NULL;
   PyObject *__pyx_t_3 = NULL;
   int __pyx_lineno = 0;
   const char *__pyx_filename = NULL;
   int __pyx_clineno = 0;
   __Pyx_RefNannySetupContext("create", 0);
 
-  /* "pygcgopt/gcg.pyx":357
+  /* "pygcgopt/gcg.pyx":367
  *         """Creates a pricing problem model and appropriately assigns the scip and bestsol parameters
  *         """
  *         if scip == NULL:             # <<<<<<<<<<<<<<
  *             raise Warning("cannot create Model with SCIP* == NULL")
  *         model = GCGPricingModel(createscip=False)
  */
   __pyx_t_1 = ((__pyx_v_scip == NULL) != 0);
   if (unlikely(__pyx_t_1)) {
 
-    /* "pygcgopt/gcg.pyx":358
+    /* "pygcgopt/gcg.pyx":368
  *         """
  *         if scip == NULL:
  *             raise Warning("cannot create Model with SCIP* == NULL")             # <<<<<<<<<<<<<<
  *         model = GCGPricingModel(createscip=False)
  *         model._scip = scip
  */
-    __pyx_t_2 = __Pyx_PyObject_Call(__pyx_builtin_Warning, __pyx_tuple__23, NULL); if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 358, __pyx_L1_error)
+    __pyx_t_2 = __Pyx_PyObject_Call(__pyx_builtin_Warning, __pyx_tuple__23, NULL); if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 368, __pyx_L1_error)
     __Pyx_GOTREF(__pyx_t_2);
     __Pyx_Raise(__pyx_t_2, 0, 0, 0);
     __Pyx_DECREF(__pyx_t_2); __pyx_t_2 = 0;
-    __PYX_ERR(3, 358, __pyx_L1_error)
+    __PYX_ERR(3, 368, __pyx_L1_error)
 
-    /* "pygcgopt/gcg.pyx":357
+    /* "pygcgopt/gcg.pyx":367
  *         """Creates a pricing problem model and appropriately assigns the scip and bestsol parameters
  *         """
  *         if scip == NULL:             # <<<<<<<<<<<<<<
  *             raise Warning("cannot create Model with SCIP* == NULL")
  *         model = GCGPricingModel(createscip=False)
  */
   }
 
-  /* "pygcgopt/gcg.pyx":359
+  /* "pygcgopt/gcg.pyx":369
  *         if scip == NULL:
  *             raise Warning("cannot create Model with SCIP* == NULL")
  *         model = GCGPricingModel(createscip=False)             # <<<<<<<<<<<<<<
  *         model._scip = scip
  *         model._bestSol = Solution.create(scip, SCIPgetBestSol(scip))
  */
-  __pyx_t_2 = __Pyx_PyDict_NewPresized(1); if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 359, __pyx_L1_error)
+  __pyx_t_2 = __Pyx_PyDict_NewPresized(1); if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 369, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_2);
-  if (PyDict_SetItem(__pyx_t_2, __pyx_n_s_createscip, Py_False) < 0) __PYX_ERR(3, 359, __pyx_L1_error)
-  __pyx_t_3 = __Pyx_PyObject_Call(((PyObject *)__pyx_ptype_8pygcgopt_3gcg_GCGPricingModel), __pyx_empty_tuple, __pyx_t_2); if (unlikely(!__pyx_t_3)) __PYX_ERR(3, 359, __pyx_L1_error)
+  if (PyDict_SetItem(__pyx_t_2, __pyx_n_s_createscip, Py_False) < 0) __PYX_ERR(3, 369, __pyx_L1_error)
+  __pyx_t_3 = __Pyx_PyObject_Call(((PyObject *)__pyx_ptype_8pygcgopt_3gcg_GCGPricingModel), __pyx_empty_tuple, __pyx_t_2); if (unlikely(!__pyx_t_3)) __PYX_ERR(3, 369, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_3);
   __Pyx_DECREF(__pyx_t_2); __pyx_t_2 = 0;
   __pyx_v_model = ((struct __pyx_obj_8pygcgopt_3gcg_GCGPricingModel *)__pyx_t_3);
   __pyx_t_3 = 0;
 
-  /* "pygcgopt/gcg.pyx":360
+  /* "pygcgopt/gcg.pyx":370
  *             raise Warning("cannot create Model with SCIP* == NULL")
  *         model = GCGPricingModel(createscip=False)
  *         model._scip = scip             # <<<<<<<<<<<<<<
  *         model._bestSol = Solution.create(scip, SCIPgetBestSol(scip))
  *         return model
  */
   __pyx_v_model->__pyx_base._scip = __pyx_v_scip;
 
-  /* "pygcgopt/gcg.pyx":361
+  /* "pygcgopt/gcg.pyx":371
  *         model = GCGPricingModel(createscip=False)
  *         model._scip = scip
  *         model._bestSol = Solution.create(scip, SCIPgetBestSol(scip))             # <<<<<<<<<<<<<<
  *         return model
  * 
  */
-  __pyx_t_3 = __pyx_vtabptr_9pyscipopt_4scip_Solution->create(__pyx_v_scip, SCIPgetBestSol(__pyx_v_scip)); if (unlikely(!__pyx_t_3)) __PYX_ERR(3, 361, __pyx_L1_error)
+  __pyx_t_3 = __pyx_vtabptr_9pyscipopt_4scip_Solution->create(__pyx_v_scip, SCIPgetBestSol(__pyx_v_scip)); if (unlikely(!__pyx_t_3)) __PYX_ERR(3, 371, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_3);
-  if (!(likely(((__pyx_t_3) == Py_None) || likely(__Pyx_TypeTest(__pyx_t_3, __pyx_ptype_9pyscipopt_4scip_Solution))))) __PYX_ERR(3, 361, __pyx_L1_error)
+  if (!(likely(((__pyx_t_3) == Py_None) || likely(__Pyx_TypeTest(__pyx_t_3, __pyx_ptype_9pyscipopt_4scip_Solution))))) __PYX_ERR(3, 371, __pyx_L1_error)
   __Pyx_GIVEREF(__pyx_t_3);
   __Pyx_GOTREF(__pyx_v_model->__pyx_base._bestSol);
   __Pyx_DECREF(((PyObject *)__pyx_v_model->__pyx_base._bestSol));
   __pyx_v_model->__pyx_base._bestSol = ((struct __pyx_obj_9pyscipopt_4scip_Solution *)__pyx_t_3);
   __pyx_t_3 = 0;
 
-  /* "pygcgopt/gcg.pyx":362
+  /* "pygcgopt/gcg.pyx":372
  *         model._scip = scip
  *         model._bestSol = Solution.create(scip, SCIPgetBestSol(scip))
  *         return model             # <<<<<<<<<<<<<<
  * 
  *     def createGcgCol(self, probnr, variables, vals, bool isray, redcost):
  */
   __Pyx_XDECREF(__pyx_r);
   __Pyx_INCREF(((PyObject *)__pyx_v_model));
   __pyx_r = ((PyObject *)__pyx_v_model);
   goto __pyx_L0;
 
-  /* "pygcgopt/gcg.pyx":354
+  /* "pygcgopt/gcg.pyx":364
  * cdef class GCGPricingModel(SCIPModel):
  *     @staticmethod
  *     cdef create(SCIP* scip):             # <<<<<<<<<<<<<<
  *         """Creates a pricing problem model and appropriately assigns the scip and bestsol parameters
  *         """
  */
 
@@ -42564,15 +42825,15 @@
   __pyx_L0:;
   __Pyx_XDECREF((PyObject *)__pyx_v_model);
   __Pyx_XGIVEREF(__pyx_r);
   __Pyx_RefNannyFinishContext();
   return __pyx_r;
 }
 
-/* "pygcgopt/gcg.pyx":364
+/* "pygcgopt/gcg.pyx":374
  *         return model
  * 
  *     def createGcgCol(self, probnr, variables, vals, bool isray, redcost):             # <<<<<<<<<<<<<<
  *         """create a gcg column
  * 
  */
 
@@ -42616,56 +42877,56 @@
         case  0:
         if (likely((values[0] = __Pyx_PyDict_GetItemStr(__pyx_kwds, __pyx_n_s_probnr)) != 0)) kw_args--;
         else goto __pyx_L5_argtuple_error;
         CYTHON_FALLTHROUGH;
         case  1:
         if (likely((values[1] = __Pyx_PyDict_GetItemStr(__pyx_kwds, __pyx_n_s_variables)) != 0)) kw_args--;
         else {
-          __Pyx_RaiseArgtupleInvalid("createGcgCol", 1, 5, 5, 1); __PYX_ERR(3, 364, __pyx_L3_error)
+          __Pyx_RaiseArgtupleInvalid("createGcgCol", 1, 5, 5, 1); __PYX_ERR(3, 374, __pyx_L3_error)
         }
         CYTHON_FALLTHROUGH;
         case  2:
         if (likely((values[2] = __Pyx_PyDict_GetItemStr(__pyx_kwds, __pyx_n_s_vals)) != 0)) kw_args--;
         else {
-          __Pyx_RaiseArgtupleInvalid("createGcgCol", 1, 5, 5, 2); __PYX_ERR(3, 364, __pyx_L3_error)
+          __Pyx_RaiseArgtupleInvalid("createGcgCol", 1, 5, 5, 2); __PYX_ERR(3, 374, __pyx_L3_error)
         }
         CYTHON_FALLTHROUGH;
         case  3:
         if (likely((values[3] = __Pyx_PyDict_GetItemStr(__pyx_kwds, __pyx_n_s_isray)) != 0)) kw_args--;
         else {
-          __Pyx_RaiseArgtupleInvalid("createGcgCol", 1, 5, 5, 3); __PYX_ERR(3, 364, __pyx_L3_error)
+          __Pyx_RaiseArgtupleInvalid("createGcgCol", 1, 5, 5, 3); __PYX_ERR(3, 374, __pyx_L3_error)
         }
         CYTHON_FALLTHROUGH;
         case  4:
         if (likely((values[4] = __Pyx_PyDict_GetItemStr(__pyx_kwds, __pyx_n_s_redcost)) != 0)) kw_args--;
         else {
-          __Pyx_RaiseArgtupleInvalid("createGcgCol", 1, 5, 5, 4); __PYX_ERR(3, 364, __pyx_L3_error)
+          __Pyx_RaiseArgtupleInvalid("createGcgCol", 1, 5, 5, 4); __PYX_ERR(3, 374, __pyx_L3_error)
         }
       }
       if (unlikely(kw_args > 0)) {
-        if (unlikely(__Pyx_ParseOptionalKeywords(__pyx_kwds, __pyx_pyargnames, 0, values, pos_args, "createGcgCol") < 0)) __PYX_ERR(3, 364, __pyx_L3_error)
+        if (unlikely(__Pyx_ParseOptionalKeywords(__pyx_kwds, __pyx_pyargnames, 0, values, pos_args, "createGcgCol") < 0)) __PYX_ERR(3, 374, __pyx_L3_error)
       }
     } else if (PyTuple_GET_SIZE(__pyx_args) != 5) {
       goto __pyx_L5_argtuple_error;
     } else {
       values[0] = PyTuple_GET_ITEM(__pyx_args, 0);
       values[1] = PyTuple_GET_ITEM(__pyx_args, 1);
       values[2] = PyTuple_GET_ITEM(__pyx_args, 2);
       values[3] = PyTuple_GET_ITEM(__pyx_args, 3);
       values[4] = PyTuple_GET_ITEM(__pyx_args, 4);
     }
     __pyx_v_probnr = values[0];
     __pyx_v_variables = values[1];
     __pyx_v_vals = values[2];
-    __pyx_v_isray = __Pyx_PyObject_IsTrue(values[3]); if (unlikely((__pyx_v_isray == ((bool)-1)) && PyErr_Occurred())) __PYX_ERR(3, 364, __pyx_L3_error)
+    __pyx_v_isray = __Pyx_PyObject_IsTrue(values[3]); if (unlikely((__pyx_v_isray == ((bool)-1)) && PyErr_Occurred())) __PYX_ERR(3, 374, __pyx_L3_error)
     __pyx_v_redcost = values[4];
   }
   goto __pyx_L4_argument_unpacking_done;
   __pyx_L5_argtuple_error:;
-  __Pyx_RaiseArgtupleInvalid("createGcgCol", 1, 5, 5, PyTuple_GET_SIZE(__pyx_args)); __PYX_ERR(3, 364, __pyx_L3_error)
+  __Pyx_RaiseArgtupleInvalid("createGcgCol", 1, 5, 5, PyTuple_GET_SIZE(__pyx_args)); __PYX_ERR(3, 374, __pyx_L3_error)
   __pyx_L3_error:;
   __Pyx_AddTraceback("pygcgopt.gcg.GCGPricingModel.createGcgCol", __pyx_clineno, __pyx_lineno, __pyx_filename);
   __Pyx_RefNannyFinishContext();
   return NULL;
   __pyx_L4_argument_unpacking_done:;
   __pyx_r = __pyx_pf_8pygcgopt_3gcg_15GCGPricingModel_createGcgCol(((struct __pyx_obj_8pygcgopt_3gcg_GCGPricingModel *)__pyx_v_self), __pyx_v_probnr, __pyx_v_variables, __pyx_v_vals, __pyx_v_isray, __pyx_v_redcost);
 
@@ -42694,204 +42955,204 @@
   int __pyx_t_9;
   int __pyx_t_10;
   int __pyx_lineno = 0;
   const char *__pyx_filename = NULL;
   int __pyx_clineno = 0;
   __Pyx_RefNannySetupContext("createGcgCol", 0);
 
-  /* "pygcgopt/gcg.pyx":374
+  /* "pygcgopt/gcg.pyx":384
  *         """
  *         cdef GCG_COL * gcg_col
  *         nvars = len(variables)             # <<<<<<<<<<<<<<
  *         cdef SCIP_VAR ** c_vars = <SCIP_VAR**>malloc(nvars * sizeof(SCIP_VAR*))
  *         cdef SCIP_Real * c_vals = <SCIP_Real*>malloc(nvars * sizeof(SCIP_Real))
  */
-  __pyx_t_1 = PyObject_Length(__pyx_v_variables); if (unlikely(__pyx_t_1 == ((Py_ssize_t)-1))) __PYX_ERR(3, 374, __pyx_L1_error)
-  __pyx_t_2 = PyInt_FromSsize_t(__pyx_t_1); if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 374, __pyx_L1_error)
+  __pyx_t_1 = PyObject_Length(__pyx_v_variables); if (unlikely(__pyx_t_1 == ((Py_ssize_t)-1))) __PYX_ERR(3, 384, __pyx_L1_error)
+  __pyx_t_2 = PyInt_FromSsize_t(__pyx_t_1); if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 384, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_2);
   __pyx_v_nvars = __pyx_t_2;
   __pyx_t_2 = 0;
 
-  /* "pygcgopt/gcg.pyx":375
+  /* "pygcgopt/gcg.pyx":385
  *         cdef GCG_COL * gcg_col
  *         nvars = len(variables)
  *         cdef SCIP_VAR ** c_vars = <SCIP_VAR**>malloc(nvars * sizeof(SCIP_VAR*))             # <<<<<<<<<<<<<<
  *         cdef SCIP_Real * c_vals = <SCIP_Real*>malloc(nvars * sizeof(SCIP_Real))
  * 
  */
-  __pyx_t_2 = __Pyx_PyInt_FromSize_t((sizeof(SCIP_VAR *))); if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 375, __pyx_L1_error)
+  __pyx_t_2 = __Pyx_PyInt_FromSize_t((sizeof(SCIP_VAR *))); if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 385, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_2);
-  __pyx_t_3 = PyNumber_Multiply(__pyx_v_nvars, __pyx_t_2); if (unlikely(!__pyx_t_3)) __PYX_ERR(3, 375, __pyx_L1_error)
+  __pyx_t_3 = PyNumber_Multiply(__pyx_v_nvars, __pyx_t_2); if (unlikely(!__pyx_t_3)) __PYX_ERR(3, 385, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_3);
   __Pyx_DECREF(__pyx_t_2); __pyx_t_2 = 0;
-  __pyx_t_4 = __Pyx_PyInt_As_size_t(__pyx_t_3); if (unlikely((__pyx_t_4 == (size_t)-1) && PyErr_Occurred())) __PYX_ERR(3, 375, __pyx_L1_error)
+  __pyx_t_4 = __Pyx_PyInt_As_size_t(__pyx_t_3); if (unlikely((__pyx_t_4 == (size_t)-1) && PyErr_Occurred())) __PYX_ERR(3, 385, __pyx_L1_error)
   __Pyx_DECREF(__pyx_t_3); __pyx_t_3 = 0;
   __pyx_v_c_vars = ((SCIP_VAR **)malloc(__pyx_t_4));
 
-  /* "pygcgopt/gcg.pyx":376
+  /* "pygcgopt/gcg.pyx":386
  *         nvars = len(variables)
  *         cdef SCIP_VAR ** c_vars = <SCIP_VAR**>malloc(nvars * sizeof(SCIP_VAR*))
  *         cdef SCIP_Real * c_vals = <SCIP_Real*>malloc(nvars * sizeof(SCIP_Real))             # <<<<<<<<<<<<<<
  * 
  *         for i in range(nvars):
  */
-  __pyx_t_3 = __Pyx_PyInt_FromSize_t((sizeof(SCIP_Real))); if (unlikely(!__pyx_t_3)) __PYX_ERR(3, 376, __pyx_L1_error)
+  __pyx_t_3 = __Pyx_PyInt_FromSize_t((sizeof(SCIP_Real))); if (unlikely(!__pyx_t_3)) __PYX_ERR(3, 386, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_3);
-  __pyx_t_2 = PyNumber_Multiply(__pyx_v_nvars, __pyx_t_3); if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 376, __pyx_L1_error)
+  __pyx_t_2 = PyNumber_Multiply(__pyx_v_nvars, __pyx_t_3); if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 386, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_2);
   __Pyx_DECREF(__pyx_t_3); __pyx_t_3 = 0;
-  __pyx_t_4 = __Pyx_PyInt_As_size_t(__pyx_t_2); if (unlikely((__pyx_t_4 == (size_t)-1) && PyErr_Occurred())) __PYX_ERR(3, 376, __pyx_L1_error)
+  __pyx_t_4 = __Pyx_PyInt_As_size_t(__pyx_t_2); if (unlikely((__pyx_t_4 == (size_t)-1) && PyErr_Occurred())) __PYX_ERR(3, 386, __pyx_L1_error)
   __Pyx_DECREF(__pyx_t_2); __pyx_t_2 = 0;
   __pyx_v_c_vals = ((SCIP_Real *)malloc(__pyx_t_4));
 
-  /* "pygcgopt/gcg.pyx":378
+  /* "pygcgopt/gcg.pyx":388
  *         cdef SCIP_Real * c_vals = <SCIP_Real*>malloc(nvars * sizeof(SCIP_Real))
  * 
  *         for i in range(nvars):             # <<<<<<<<<<<<<<
  *             c_vars[i] = (<Variable>variables[i]).scip_var
  *             c_vals[i] = vals[i]
  */
-  __pyx_t_2 = __Pyx_PyObject_CallOneArg(__pyx_builtin_range, __pyx_v_nvars); if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 378, __pyx_L1_error)
+  __pyx_t_2 = __Pyx_PyObject_CallOneArg(__pyx_builtin_range, __pyx_v_nvars); if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 388, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_2);
   if (likely(PyList_CheckExact(__pyx_t_2)) || PyTuple_CheckExact(__pyx_t_2)) {
     __pyx_t_3 = __pyx_t_2; __Pyx_INCREF(__pyx_t_3); __pyx_t_1 = 0;
     __pyx_t_5 = NULL;
   } else {
-    __pyx_t_1 = -1; __pyx_t_3 = PyObject_GetIter(__pyx_t_2); if (unlikely(!__pyx_t_3)) __PYX_ERR(3, 378, __pyx_L1_error)
+    __pyx_t_1 = -1; __pyx_t_3 = PyObject_GetIter(__pyx_t_2); if (unlikely(!__pyx_t_3)) __PYX_ERR(3, 388, __pyx_L1_error)
     __Pyx_GOTREF(__pyx_t_3);
-    __pyx_t_5 = Py_TYPE(__pyx_t_3)->tp_iternext; if (unlikely(!__pyx_t_5)) __PYX_ERR(3, 378, __pyx_L1_error)
+    __pyx_t_5 = Py_TYPE(__pyx_t_3)->tp_iternext; if (unlikely(!__pyx_t_5)) __PYX_ERR(3, 388, __pyx_L1_error)
   }
   __Pyx_DECREF(__pyx_t_2); __pyx_t_2 = 0;
   for (;;) {
     if (likely(!__pyx_t_5)) {
       if (likely(PyList_CheckExact(__pyx_t_3))) {
         if (__pyx_t_1 >= PyList_GET_SIZE(__pyx_t_3)) break;
         #if CYTHON_ASSUME_SAFE_MACROS && !CYTHON_AVOID_BORROWED_REFS
-        __pyx_t_2 = PyList_GET_ITEM(__pyx_t_3, __pyx_t_1); __Pyx_INCREF(__pyx_t_2); __pyx_t_1++; if (unlikely(0 < 0)) __PYX_ERR(3, 378, __pyx_L1_error)
+        __pyx_t_2 = PyList_GET_ITEM(__pyx_t_3, __pyx_t_1); __Pyx_INCREF(__pyx_t_2); __pyx_t_1++; if (unlikely(0 < 0)) __PYX_ERR(3, 388, __pyx_L1_error)
         #else
-        __pyx_t_2 = PySequence_ITEM(__pyx_t_3, __pyx_t_1); __pyx_t_1++; if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 378, __pyx_L1_error)
+        __pyx_t_2 = PySequence_ITEM(__pyx_t_3, __pyx_t_1); __pyx_t_1++; if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 388, __pyx_L1_error)
         __Pyx_GOTREF(__pyx_t_2);
         #endif
       } else {
         if (__pyx_t_1 >= PyTuple_GET_SIZE(__pyx_t_3)) break;
         #if CYTHON_ASSUME_SAFE_MACROS && !CYTHON_AVOID_BORROWED_REFS
-        __pyx_t_2 = PyTuple_GET_ITEM(__pyx_t_3, __pyx_t_1); __Pyx_INCREF(__pyx_t_2); __pyx_t_1++; if (unlikely(0 < 0)) __PYX_ERR(3, 378, __pyx_L1_error)
+        __pyx_t_2 = PyTuple_GET_ITEM(__pyx_t_3, __pyx_t_1); __Pyx_INCREF(__pyx_t_2); __pyx_t_1++; if (unlikely(0 < 0)) __PYX_ERR(3, 388, __pyx_L1_error)
         #else
-        __pyx_t_2 = PySequence_ITEM(__pyx_t_3, __pyx_t_1); __pyx_t_1++; if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 378, __pyx_L1_error)
+        __pyx_t_2 = PySequence_ITEM(__pyx_t_3, __pyx_t_1); __pyx_t_1++; if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 388, __pyx_L1_error)
         __Pyx_GOTREF(__pyx_t_2);
         #endif
       }
     } else {
       __pyx_t_2 = __pyx_t_5(__pyx_t_3);
       if (unlikely(!__pyx_t_2)) {
         PyObject* exc_type = PyErr_Occurred();
         if (exc_type) {
           if (likely(__Pyx_PyErr_GivenExceptionMatches(exc_type, PyExc_StopIteration))) PyErr_Clear();
-          else __PYX_ERR(3, 378, __pyx_L1_error)
+          else __PYX_ERR(3, 388, __pyx_L1_error)
         }
         break;
       }
       __Pyx_GOTREF(__pyx_t_2);
     }
     __Pyx_XDECREF_SET(__pyx_v_i, __pyx_t_2);
     __pyx_t_2 = 0;
 
-    /* "pygcgopt/gcg.pyx":379
+    /* "pygcgopt/gcg.pyx":389
  * 
  *         for i in range(nvars):
  *             c_vars[i] = (<Variable>variables[i]).scip_var             # <<<<<<<<<<<<<<
  *             c_vals[i] = vals[i]
  * 
  */
-    __pyx_t_2 = __Pyx_PyObject_GetItem(__pyx_v_variables, __pyx_v_i); if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 379, __pyx_L1_error)
+    __pyx_t_2 = __Pyx_PyObject_GetItem(__pyx_v_variables, __pyx_v_i); if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 389, __pyx_L1_error)
     __Pyx_GOTREF(__pyx_t_2);
     __pyx_t_6 = ((struct __pyx_obj_9pyscipopt_4scip_Variable *)__pyx_t_2)->scip_var;
     __Pyx_DECREF(__pyx_t_2); __pyx_t_2 = 0;
-    __pyx_t_7 = __Pyx_PyIndex_AsSsize_t(__pyx_v_i); if (unlikely((__pyx_t_7 == (Py_ssize_t)-1) && PyErr_Occurred())) __PYX_ERR(3, 379, __pyx_L1_error)
+    __pyx_t_7 = __Pyx_PyIndex_AsSsize_t(__pyx_v_i); if (unlikely((__pyx_t_7 == (Py_ssize_t)-1) && PyErr_Occurred())) __PYX_ERR(3, 389, __pyx_L1_error)
     (__pyx_v_c_vars[__pyx_t_7]) = __pyx_t_6;
 
-    /* "pygcgopt/gcg.pyx":380
+    /* "pygcgopt/gcg.pyx":390
  *         for i in range(nvars):
  *             c_vars[i] = (<Variable>variables[i]).scip_var
  *             c_vals[i] = vals[i]             # <<<<<<<<<<<<<<
  * 
  *         GCGcreateGcgCol(self._scip, &gcg_col, probnr, c_vars, c_vals, nvars, isray, redcost)
  */
-    __pyx_t_2 = __Pyx_PyObject_GetItem(__pyx_v_vals, __pyx_v_i); if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 380, __pyx_L1_error)
+    __pyx_t_2 = __Pyx_PyObject_GetItem(__pyx_v_vals, __pyx_v_i); if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 390, __pyx_L1_error)
     __Pyx_GOTREF(__pyx_t_2);
-    __pyx_t_8 = __pyx_PyFloat_AsDouble(__pyx_t_2); if (unlikely((__pyx_t_8 == ((SCIP_Real)-1)) && PyErr_Occurred())) __PYX_ERR(3, 380, __pyx_L1_error)
+    __pyx_t_8 = __pyx_PyFloat_AsDouble(__pyx_t_2); if (unlikely((__pyx_t_8 == ((SCIP_Real)-1)) && PyErr_Occurred())) __PYX_ERR(3, 390, __pyx_L1_error)
     __Pyx_DECREF(__pyx_t_2); __pyx_t_2 = 0;
-    __pyx_t_7 = __Pyx_PyIndex_AsSsize_t(__pyx_v_i); if (unlikely((__pyx_t_7 == (Py_ssize_t)-1) && PyErr_Occurred())) __PYX_ERR(3, 380, __pyx_L1_error)
+    __pyx_t_7 = __Pyx_PyIndex_AsSsize_t(__pyx_v_i); if (unlikely((__pyx_t_7 == (Py_ssize_t)-1) && PyErr_Occurred())) __PYX_ERR(3, 390, __pyx_L1_error)
     (__pyx_v_c_vals[__pyx_t_7]) = __pyx_t_8;
 
-    /* "pygcgopt/gcg.pyx":378
+    /* "pygcgopt/gcg.pyx":388
  *         cdef SCIP_Real * c_vals = <SCIP_Real*>malloc(nvars * sizeof(SCIP_Real))
  * 
  *         for i in range(nvars):             # <<<<<<<<<<<<<<
  *             c_vars[i] = (<Variable>variables[i]).scip_var
  *             c_vals[i] = vals[i]
  */
   }
   __Pyx_DECREF(__pyx_t_3); __pyx_t_3 = 0;
 
-  /* "pygcgopt/gcg.pyx":382
+  /* "pygcgopt/gcg.pyx":392
  *             c_vals[i] = vals[i]
  * 
  *         GCGcreateGcgCol(self._scip, &gcg_col, probnr, c_vars, c_vals, nvars, isray, redcost)             # <<<<<<<<<<<<<<
  * 
  *         pyGCGCol = GCGColumn.create(gcg_col)
  */
-  __pyx_t_9 = __Pyx_PyInt_As_int(__pyx_v_probnr); if (unlikely((__pyx_t_9 == (int)-1) && PyErr_Occurred())) __PYX_ERR(3, 382, __pyx_L1_error)
-  __pyx_t_10 = __Pyx_PyInt_As_int(__pyx_v_nvars); if (unlikely((__pyx_t_10 == (int)-1) && PyErr_Occurred())) __PYX_ERR(3, 382, __pyx_L1_error)
-  __pyx_t_8 = __pyx_PyFloat_AsDouble(__pyx_v_redcost); if (unlikely((__pyx_t_8 == ((SCIP_Real)-1)) && PyErr_Occurred())) __PYX_ERR(3, 382, __pyx_L1_error)
+  __pyx_t_9 = __Pyx_PyInt_As_int(__pyx_v_probnr); if (unlikely((__pyx_t_9 == (int)-1) && PyErr_Occurred())) __PYX_ERR(3, 392, __pyx_L1_error)
+  __pyx_t_10 = __Pyx_PyInt_As_int(__pyx_v_nvars); if (unlikely((__pyx_t_10 == (int)-1) && PyErr_Occurred())) __PYX_ERR(3, 392, __pyx_L1_error)
+  __pyx_t_8 = __pyx_PyFloat_AsDouble(__pyx_v_redcost); if (unlikely((__pyx_t_8 == ((SCIP_Real)-1)) && PyErr_Occurred())) __PYX_ERR(3, 392, __pyx_L1_error)
   (void)(GCGcreateGcgCol(__pyx_v_self->__pyx_base._scip, (&__pyx_v_gcg_col), __pyx_t_9, __pyx_v_c_vars, __pyx_v_c_vals, __pyx_t_10, __pyx_v_isray, __pyx_t_8));
 
-  /* "pygcgopt/gcg.pyx":384
+  /* "pygcgopt/gcg.pyx":394
  *         GCGcreateGcgCol(self._scip, &gcg_col, probnr, c_vars, c_vals, nvars, isray, redcost)
  * 
  *         pyGCGCol = GCGColumn.create(gcg_col)             # <<<<<<<<<<<<<<
  * 
  *         free(c_vars)
  */
-  __pyx_t_3 = __pyx_f_8pygcgopt_3gcg_9GCGColumn_create(__pyx_v_gcg_col); if (unlikely(!__pyx_t_3)) __PYX_ERR(3, 384, __pyx_L1_error)
+  __pyx_t_3 = __pyx_f_8pygcgopt_3gcg_9GCGColumn_create(__pyx_v_gcg_col); if (unlikely(!__pyx_t_3)) __PYX_ERR(3, 394, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_3);
   __pyx_v_pyGCGCol = __pyx_t_3;
   __pyx_t_3 = 0;
 
-  /* "pygcgopt/gcg.pyx":386
+  /* "pygcgopt/gcg.pyx":396
  *         pyGCGCol = GCGColumn.create(gcg_col)
  * 
  *         free(c_vars)             # <<<<<<<<<<<<<<
  *         free(c_vals)
  * 
  */
   free(__pyx_v_c_vars);
 
-  /* "pygcgopt/gcg.pyx":387
+  /* "pygcgopt/gcg.pyx":397
  * 
  *         free(c_vars)
  *         free(c_vals)             # <<<<<<<<<<<<<<
  * 
  *         return pyGCGCol
  */
   free(__pyx_v_c_vals);
 
-  /* "pygcgopt/gcg.pyx":389
+  /* "pygcgopt/gcg.pyx":399
  *         free(c_vals)
  * 
  *         return pyGCGCol             # <<<<<<<<<<<<<<
  * 
  * 
  */
   __Pyx_XDECREF(__pyx_r);
   __Pyx_INCREF(__pyx_v_pyGCGCol);
   __pyx_r = __pyx_v_pyGCGCol;
   goto __pyx_L0;
 
-  /* "pygcgopt/gcg.pyx":364
+  /* "pygcgopt/gcg.pyx":374
  *         return model
  * 
  *     def createGcgCol(self, probnr, variables, vals, bool isray, redcost):             # <<<<<<<<<<<<<<
  *         """create a gcg column
  * 
  */
 
@@ -43021,15 +43282,15 @@
   __Pyx_AddTraceback("pygcgopt.gcg.GCGPricingModel.__setstate_cython__", __pyx_clineno, __pyx_lineno, __pyx_filename);
   __pyx_r = NULL;
   __Pyx_XGIVEREF(__pyx_r);
   __Pyx_RefNannyFinishContext();
   return __pyx_r;
 }
 
-/* "pygcgopt/gcg.pyx":394
+/* "pygcgopt/gcg.pyx":404
  * cdef class GCGMasterModel(SCIPModel):
  *     @staticmethod
  *     cdef create(SCIP* scip):             # <<<<<<<<<<<<<<
  *         """Creates a pricing problem model and appropriately assigns the scip and bestsol parameters
  *         """
  */
 
@@ -43041,100 +43302,100 @@
   PyObject *__pyx_t_2 = NULL;
   PyObject *__pyx_t_3 = NULL;
   int __pyx_lineno = 0;
   const char *__pyx_filename = NULL;
   int __pyx_clineno = 0;
   __Pyx_RefNannySetupContext("create", 0);
 
-  /* "pygcgopt/gcg.pyx":397
+  /* "pygcgopt/gcg.pyx":407
  *         """Creates a pricing problem model and appropriately assigns the scip and bestsol parameters
  *         """
  *         if scip == NULL:             # <<<<<<<<<<<<<<
  *             raise Warning("cannot create Model with SCIP* == NULL")
  *         model = GCGMasterModel(createscip=False)
  */
   __pyx_t_1 = ((__pyx_v_scip == NULL) != 0);
   if (unlikely(__pyx_t_1)) {
 
-    /* "pygcgopt/gcg.pyx":398
+    /* "pygcgopt/gcg.pyx":408
  *         """
  *         if scip == NULL:
  *             raise Warning("cannot create Model with SCIP* == NULL")             # <<<<<<<<<<<<<<
  *         model = GCGMasterModel(createscip=False)
  *         model._scip = scip
  */
-    __pyx_t_2 = __Pyx_PyObject_Call(__pyx_builtin_Warning, __pyx_tuple__23, NULL); if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 398, __pyx_L1_error)
+    __pyx_t_2 = __Pyx_PyObject_Call(__pyx_builtin_Warning, __pyx_tuple__23, NULL); if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 408, __pyx_L1_error)
     __Pyx_GOTREF(__pyx_t_2);
     __Pyx_Raise(__pyx_t_2, 0, 0, 0);
     __Pyx_DECREF(__pyx_t_2); __pyx_t_2 = 0;
-    __PYX_ERR(3, 398, __pyx_L1_error)
+    __PYX_ERR(3, 408, __pyx_L1_error)
 
-    /* "pygcgopt/gcg.pyx":397
+    /* "pygcgopt/gcg.pyx":407
  *         """Creates a pricing problem model and appropriately assigns the scip and bestsol parameters
  *         """
  *         if scip == NULL:             # <<<<<<<<<<<<<<
  *             raise Warning("cannot create Model with SCIP* == NULL")
  *         model = GCGMasterModel(createscip=False)
  */
   }
 
-  /* "pygcgopt/gcg.pyx":399
+  /* "pygcgopt/gcg.pyx":409
  *         if scip == NULL:
  *             raise Warning("cannot create Model with SCIP* == NULL")
  *         model = GCGMasterModel(createscip=False)             # <<<<<<<<<<<<<<
  *         model._scip = scip
  *         model._bestSol = Solution.create(scip, SCIPgetBestSol(scip))
  */
-  __pyx_t_2 = __Pyx_PyDict_NewPresized(1); if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 399, __pyx_L1_error)
+  __pyx_t_2 = __Pyx_PyDict_NewPresized(1); if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 409, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_2);
-  if (PyDict_SetItem(__pyx_t_2, __pyx_n_s_createscip, Py_False) < 0) __PYX_ERR(3, 399, __pyx_L1_error)
-  __pyx_t_3 = __Pyx_PyObject_Call(((PyObject *)__pyx_ptype_8pygcgopt_3gcg_GCGMasterModel), __pyx_empty_tuple, __pyx_t_2); if (unlikely(!__pyx_t_3)) __PYX_ERR(3, 399, __pyx_L1_error)
+  if (PyDict_SetItem(__pyx_t_2, __pyx_n_s_createscip, Py_False) < 0) __PYX_ERR(3, 409, __pyx_L1_error)
+  __pyx_t_3 = __Pyx_PyObject_Call(((PyObject *)__pyx_ptype_8pygcgopt_3gcg_GCGMasterModel), __pyx_empty_tuple, __pyx_t_2); if (unlikely(!__pyx_t_3)) __PYX_ERR(3, 409, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_3);
   __Pyx_DECREF(__pyx_t_2); __pyx_t_2 = 0;
   __pyx_v_model = ((struct __pyx_obj_8pygcgopt_3gcg_GCGMasterModel *)__pyx_t_3);
   __pyx_t_3 = 0;
 
-  /* "pygcgopt/gcg.pyx":400
+  /* "pygcgopt/gcg.pyx":410
  *             raise Warning("cannot create Model with SCIP* == NULL")
  *         model = GCGMasterModel(createscip=False)
  *         model._scip = scip             # <<<<<<<<<<<<<<
  *         model._bestSol = Solution.create(scip, SCIPgetBestSol(scip))
  *         return model
  */
   __pyx_v_model->__pyx_base._scip = __pyx_v_scip;
 
-  /* "pygcgopt/gcg.pyx":401
+  /* "pygcgopt/gcg.pyx":411
  *         model = GCGMasterModel(createscip=False)
  *         model._scip = scip
  *         model._bestSol = Solution.create(scip, SCIPgetBestSol(scip))             # <<<<<<<<<<<<<<
  *         return model
  * 
  */
-  __pyx_t_3 = __pyx_vtabptr_9pyscipopt_4scip_Solution->create(__pyx_v_scip, SCIPgetBestSol(__pyx_v_scip)); if (unlikely(!__pyx_t_3)) __PYX_ERR(3, 401, __pyx_L1_error)
+  __pyx_t_3 = __pyx_vtabptr_9pyscipopt_4scip_Solution->create(__pyx_v_scip, SCIPgetBestSol(__pyx_v_scip)); if (unlikely(!__pyx_t_3)) __PYX_ERR(3, 411, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_3);
-  if (!(likely(((__pyx_t_3) == Py_None) || likely(__Pyx_TypeTest(__pyx_t_3, __pyx_ptype_9pyscipopt_4scip_Solution))))) __PYX_ERR(3, 401, __pyx_L1_error)
+  if (!(likely(((__pyx_t_3) == Py_None) || likely(__Pyx_TypeTest(__pyx_t_3, __pyx_ptype_9pyscipopt_4scip_Solution))))) __PYX_ERR(3, 411, __pyx_L1_error)
   __Pyx_GIVEREF(__pyx_t_3);
   __Pyx_GOTREF(__pyx_v_model->__pyx_base._bestSol);
   __Pyx_DECREF(((PyObject *)__pyx_v_model->__pyx_base._bestSol));
   __pyx_v_model->__pyx_base._bestSol = ((struct __pyx_obj_9pyscipopt_4scip_Solution *)__pyx_t_3);
   __pyx_t_3 = 0;
 
-  /* "pygcgopt/gcg.pyx":402
+  /* "pygcgopt/gcg.pyx":412
  *         model._scip = scip
  *         model._bestSol = Solution.create(scip, SCIPgetBestSol(scip))
  *         return model             # <<<<<<<<<<<<<<
  * 
  *     def addCol(self, GCGColumn col):
  */
   __Pyx_XDECREF(__pyx_r);
   __Pyx_INCREF(((PyObject *)__pyx_v_model));
   __pyx_r = ((PyObject *)__pyx_v_model);
   goto __pyx_L0;
 
-  /* "pygcgopt/gcg.pyx":394
+  /* "pygcgopt/gcg.pyx":404
  * cdef class GCGMasterModel(SCIPModel):
  *     @staticmethod
  *     cdef create(SCIP* scip):             # <<<<<<<<<<<<<<
  *         """Creates a pricing problem model and appropriately assigns the scip and bestsol parameters
  *         """
  */
 
@@ -43147,15 +43408,15 @@
   __pyx_L0:;
   __Pyx_XDECREF((PyObject *)__pyx_v_model);
   __Pyx_XGIVEREF(__pyx_r);
   __Pyx_RefNannyFinishContext();
   return __pyx_r;
 }
 
-/* "pygcgopt/gcg.pyx":404
+/* "pygcgopt/gcg.pyx":414
  *         return model
  * 
  *     def addCol(self, GCGColumn col):             # <<<<<<<<<<<<<<
  *         PY_SCIP_CALL(GCGpricerAddCol(self._scip, col.gcg_col))
  * 
  */
 
@@ -43165,15 +43426,15 @@
 static PyObject *__pyx_pw_8pygcgopt_3gcg_14GCGMasterModel_1addCol(PyObject *__pyx_v_self, PyObject *__pyx_v_col) {
   int __pyx_lineno = 0;
   const char *__pyx_filename = NULL;
   int __pyx_clineno = 0;
   PyObject *__pyx_r = 0;
   __Pyx_RefNannyDeclarations
   __Pyx_RefNannySetupContext("addCol (wrapper)", 0);
-  if (unlikely(!__Pyx_ArgTypeTest(((PyObject *)__pyx_v_col), __pyx_ptype_8pygcgopt_3gcg_GCGColumn, 1, "col", 0))) __PYX_ERR(3, 404, __pyx_L1_error)
+  if (unlikely(!__Pyx_ArgTypeTest(((PyObject *)__pyx_v_col), __pyx_ptype_8pygcgopt_3gcg_GCGColumn, 1, "col", 0))) __PYX_ERR(3, 414, __pyx_L1_error)
   __pyx_r = __pyx_pf_8pygcgopt_3gcg_14GCGMasterModel_addCol(((struct __pyx_obj_8pygcgopt_3gcg_GCGMasterModel *)__pyx_v_self), ((struct __pyx_obj_8pygcgopt_3gcg_GCGColumn *)__pyx_v_col));
 
   /* function exit code */
   goto __pyx_L0;
   __pyx_L1_error:;
   __pyx_r = NULL;
   __pyx_L0:;
@@ -43189,44 +43450,44 @@
   PyObject *__pyx_t_3 = NULL;
   PyObject *__pyx_t_4 = NULL;
   int __pyx_lineno = 0;
   const char *__pyx_filename = NULL;
   int __pyx_clineno = 0;
   __Pyx_RefNannySetupContext("addCol", 0);
 
-  /* "pygcgopt/gcg.pyx":405
+  /* "pygcgopt/gcg.pyx":415
  * 
  *     def addCol(self, GCGColumn col):
  *         PY_SCIP_CALL(GCGpricerAddCol(self._scip, col.gcg_col))             # <<<<<<<<<<<<<<
  * 
- * 
+ *     def getOrigvars(self, var):
  */
-  __Pyx_GetModuleGlobalName(__pyx_t_2, __pyx_n_s_PY_SCIP_CALL); if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 405, __pyx_L1_error)
+  __Pyx_GetModuleGlobalName(__pyx_t_2, __pyx_n_s_PY_SCIP_CALL); if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 415, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_2);
-  __pyx_t_3 = __Pyx_PyInt_From_SCIP_RETCODE(GCGpricerAddCol(__pyx_v_self->__pyx_base._scip, __pyx_v_col->gcg_col)); if (unlikely(!__pyx_t_3)) __PYX_ERR(3, 405, __pyx_L1_error)
+  __pyx_t_3 = __Pyx_PyInt_From_SCIP_RETCODE(GCGpricerAddCol(__pyx_v_self->__pyx_base._scip, __pyx_v_col->gcg_col)); if (unlikely(!__pyx_t_3)) __PYX_ERR(3, 415, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_3);
   __pyx_t_4 = NULL;
   if (CYTHON_UNPACK_METHODS && unlikely(PyMethod_Check(__pyx_t_2))) {
     __pyx_t_4 = PyMethod_GET_SELF(__pyx_t_2);
     if (likely(__pyx_t_4)) {
       PyObject* function = PyMethod_GET_FUNCTION(__pyx_t_2);
       __Pyx_INCREF(__pyx_t_4);
       __Pyx_INCREF(function);
       __Pyx_DECREF_SET(__pyx_t_2, function);
     }
   }
   __pyx_t_1 = (__pyx_t_4) ? __Pyx_PyObject_Call2Args(__pyx_t_2, __pyx_t_4, __pyx_t_3) : __Pyx_PyObject_CallOneArg(__pyx_t_2, __pyx_t_3);
   __Pyx_XDECREF(__pyx_t_4); __pyx_t_4 = 0;
   __Pyx_DECREF(__pyx_t_3); __pyx_t_3 = 0;
-  if (unlikely(!__pyx_t_1)) __PYX_ERR(3, 405, __pyx_L1_error)
+  if (unlikely(!__pyx_t_1)) __PYX_ERR(3, 415, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_1);
   __Pyx_DECREF(__pyx_t_2); __pyx_t_2 = 0;
   __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
 
-  /* "pygcgopt/gcg.pyx":404
+  /* "pygcgopt/gcg.pyx":414
  *         return model
  * 
  *     def addCol(self, GCGColumn col):             # <<<<<<<<<<<<<<
  *         PY_SCIP_CALL(GCGpricerAddCol(self._scip, col.gcg_col))
  * 
  */
 
@@ -43242,35 +43503,136 @@
   __pyx_r = NULL;
   __pyx_L0:;
   __Pyx_XGIVEREF(__pyx_r);
   __Pyx_RefNannyFinishContext();
   return __pyx_r;
 }
 
+/* "pygcgopt/gcg.pyx":417
+ *         PY_SCIP_CALL(GCGpricerAddCol(self._scip, col.gcg_col))
+ * 
+ *     def getOrigvars(self, var):             # <<<<<<<<<<<<<<
+ *         """Returns the original variables corresponding to the variable of master problem
+ * 
+ */
+
+/* Python wrapper */
+static PyObject *__pyx_pw_8pygcgopt_3gcg_14GCGMasterModel_3getOrigvars(PyObject *__pyx_v_self, PyObject *__pyx_v_var); /*proto*/
+static char __pyx_doc_8pygcgopt_3gcg_14GCGMasterModel_2getOrigvars[] = "GCGMasterModel.getOrigvars(self, var)\nReturns the original variables corresponding to the variable of master problem\n\n        :param var: Variable of master problem\n        :return: List of original variables\n        ";
+static PyObject *__pyx_pw_8pygcgopt_3gcg_14GCGMasterModel_3getOrigvars(PyObject *__pyx_v_self, PyObject *__pyx_v_var) {
+  PyObject *__pyx_r = 0;
+  __Pyx_RefNannyDeclarations
+  __Pyx_RefNannySetupContext("getOrigvars (wrapper)", 0);
+  __pyx_r = __pyx_pf_8pygcgopt_3gcg_14GCGMasterModel_2getOrigvars(((struct __pyx_obj_8pygcgopt_3gcg_GCGMasterModel *)__pyx_v_self), ((PyObject *)__pyx_v_var));
+
+  /* function exit code */
+  __Pyx_RefNannyFinishContext();
+  return __pyx_r;
+}
+
+static PyObject *__pyx_pf_8pygcgopt_3gcg_14GCGMasterModel_2getOrigvars(CYTHON_UNUSED struct __pyx_obj_8pygcgopt_3gcg_GCGMasterModel *__pyx_v_self, PyObject *__pyx_v_var) {
+  int __pyx_v_n_vars;
+  SCIP_VAR **__pyx_v_originalvars;
+  int __pyx_9genexpr16__pyx_v_i;
+  PyObject *__pyx_r = NULL;
+  __Pyx_RefNannyDeclarations
+  PyObject *__pyx_t_1 = NULL;
+  int __pyx_t_2;
+  int __pyx_t_3;
+  int __pyx_t_4;
+  PyObject *__pyx_t_5 = NULL;
+  int __pyx_lineno = 0;
+  const char *__pyx_filename = NULL;
+  int __pyx_clineno = 0;
+  __Pyx_RefNannySetupContext("getOrigvars", 0);
+
+  /* "pygcgopt/gcg.pyx":423
+ *         :return: List of original variables
+ *         """
+ *         cdef int n_vars = GCGmasterVarGetNOrigvars((<Variable>var).scip_var)             # <<<<<<<<<<<<<<
+ *         cdef SCIP_VAR** originalvars = GCGmasterVarGetOrigvars((<Variable>var).scip_var)
+ *         return [Variable.create(originalvars[i]) for i in range(n_vars)]
+ */
+  __pyx_v_n_vars = GCGmasterVarGetNOrigvars(((struct __pyx_obj_9pyscipopt_4scip_Variable *)__pyx_v_var)->scip_var);
+
+  /* "pygcgopt/gcg.pyx":424
+ *         """
+ *         cdef int n_vars = GCGmasterVarGetNOrigvars((<Variable>var).scip_var)
+ *         cdef SCIP_VAR** originalvars = GCGmasterVarGetOrigvars((<Variable>var).scip_var)             # <<<<<<<<<<<<<<
+ *         return [Variable.create(originalvars[i]) for i in range(n_vars)]
+ * 
+ */
+  __pyx_v_originalvars = GCGmasterVarGetOrigvars(((struct __pyx_obj_9pyscipopt_4scip_Variable *)__pyx_v_var)->scip_var);
+
+  /* "pygcgopt/gcg.pyx":425
+ *         cdef int n_vars = GCGmasterVarGetNOrigvars((<Variable>var).scip_var)
+ *         cdef SCIP_VAR** originalvars = GCGmasterVarGetOrigvars((<Variable>var).scip_var)
+ *         return [Variable.create(originalvars[i]) for i in range(n_vars)]             # <<<<<<<<<<<<<<
+ * 
+ * 
+ */
+  __Pyx_XDECREF(__pyx_r);
+  { /* enter inner scope */
+    __pyx_t_1 = PyList_New(0); if (unlikely(!__pyx_t_1)) __PYX_ERR(3, 425, __pyx_L1_error)
+    __Pyx_GOTREF(__pyx_t_1);
+    __pyx_t_2 = __pyx_v_n_vars;
+    __pyx_t_3 = __pyx_t_2;
+    for (__pyx_t_4 = 0; __pyx_t_4 < __pyx_t_3; __pyx_t_4+=1) {
+      __pyx_9genexpr16__pyx_v_i = __pyx_t_4;
+      __pyx_t_5 = __pyx_vtabptr_9pyscipopt_4scip_Variable->create((__pyx_v_originalvars[__pyx_9genexpr16__pyx_v_i])); if (unlikely(!__pyx_t_5)) __PYX_ERR(3, 425, __pyx_L1_error)
+      __Pyx_GOTREF(__pyx_t_5);
+      if (unlikely(__Pyx_ListComp_Append(__pyx_t_1, (PyObject*)__pyx_t_5))) __PYX_ERR(3, 425, __pyx_L1_error)
+      __Pyx_DECREF(__pyx_t_5); __pyx_t_5 = 0;
+    }
+  } /* exit inner scope */
+  __pyx_r = __pyx_t_1;
+  __pyx_t_1 = 0;
+  goto __pyx_L0;
+
+  /* "pygcgopt/gcg.pyx":417
+ *         PY_SCIP_CALL(GCGpricerAddCol(self._scip, col.gcg_col))
+ * 
+ *     def getOrigvars(self, var):             # <<<<<<<<<<<<<<
+ *         """Returns the original variables corresponding to the variable of master problem
+ * 
+ */
+
+  /* function exit code */
+  __pyx_L1_error:;
+  __Pyx_XDECREF(__pyx_t_1);
+  __Pyx_XDECREF(__pyx_t_5);
+  __Pyx_AddTraceback("pygcgopt.gcg.GCGMasterModel.getOrigvars", __pyx_clineno, __pyx_lineno, __pyx_filename);
+  __pyx_r = NULL;
+  __pyx_L0:;
+  __Pyx_XGIVEREF(__pyx_r);
+  __Pyx_RefNannyFinishContext();
+  return __pyx_r;
+}
+
 /* "(tree fragment)":1
  * def __reduce_cython__(self):             # <<<<<<<<<<<<<<
  *     raise TypeError("self._scip,self._valid cannot be converted to a Python object for pickling")
  * def __setstate_cython__(self, __pyx_state):
  */
 
 /* Python wrapper */
-static PyObject *__pyx_pw_8pygcgopt_3gcg_14GCGMasterModel_3__reduce_cython__(PyObject *__pyx_v_self, CYTHON_UNUSED PyObject *unused); /*proto*/
-static char __pyx_doc_8pygcgopt_3gcg_14GCGMasterModel_2__reduce_cython__[] = "GCGMasterModel.__reduce_cython__(self)";
-static PyObject *__pyx_pw_8pygcgopt_3gcg_14GCGMasterModel_3__reduce_cython__(PyObject *__pyx_v_self, CYTHON_UNUSED PyObject *unused) {
+static PyObject *__pyx_pw_8pygcgopt_3gcg_14GCGMasterModel_5__reduce_cython__(PyObject *__pyx_v_self, CYTHON_UNUSED PyObject *unused); /*proto*/
+static char __pyx_doc_8pygcgopt_3gcg_14GCGMasterModel_4__reduce_cython__[] = "GCGMasterModel.__reduce_cython__(self)";
+static PyObject *__pyx_pw_8pygcgopt_3gcg_14GCGMasterModel_5__reduce_cython__(PyObject *__pyx_v_self, CYTHON_UNUSED PyObject *unused) {
   PyObject *__pyx_r = 0;
   __Pyx_RefNannyDeclarations
   __Pyx_RefNannySetupContext("__reduce_cython__ (wrapper)", 0);
-  __pyx_r = __pyx_pf_8pygcgopt_3gcg_14GCGMasterModel_2__reduce_cython__(((struct __pyx_obj_8pygcgopt_3gcg_GCGMasterModel *)__pyx_v_self));
+  __pyx_r = __pyx_pf_8pygcgopt_3gcg_14GCGMasterModel_4__reduce_cython__(((struct __pyx_obj_8pygcgopt_3gcg_GCGMasterModel *)__pyx_v_self));
 
   /* function exit code */
   __Pyx_RefNannyFinishContext();
   return __pyx_r;
 }
 
-static PyObject *__pyx_pf_8pygcgopt_3gcg_14GCGMasterModel_2__reduce_cython__(CYTHON_UNUSED struct __pyx_obj_8pygcgopt_3gcg_GCGMasterModel *__pyx_v_self) {
+static PyObject *__pyx_pf_8pygcgopt_3gcg_14GCGMasterModel_4__reduce_cython__(CYTHON_UNUSED struct __pyx_obj_8pygcgopt_3gcg_GCGMasterModel *__pyx_v_self) {
   PyObject *__pyx_r = NULL;
   __Pyx_RefNannyDeclarations
   PyObject *__pyx_t_1 = NULL;
   int __pyx_lineno = 0;
   const char *__pyx_filename = NULL;
   int __pyx_clineno = 0;
   __Pyx_RefNannySetupContext("__reduce_cython__", 0);
@@ -43307,28 +43669,28 @@
  * def __reduce_cython__(self):
  *     raise TypeError("self._scip,self._valid cannot be converted to a Python object for pickling")
  * def __setstate_cython__(self, __pyx_state):             # <<<<<<<<<<<<<<
  *     raise TypeError("self._scip,self._valid cannot be converted to a Python object for pickling")
  */
 
 /* Python wrapper */
-static PyObject *__pyx_pw_8pygcgopt_3gcg_14GCGMasterModel_5__setstate_cython__(PyObject *__pyx_v_self, PyObject *__pyx_v___pyx_state); /*proto*/
-static char __pyx_doc_8pygcgopt_3gcg_14GCGMasterModel_4__setstate_cython__[] = "GCGMasterModel.__setstate_cython__(self, __pyx_state)";
-static PyObject *__pyx_pw_8pygcgopt_3gcg_14GCGMasterModel_5__setstate_cython__(PyObject *__pyx_v_self, PyObject *__pyx_v___pyx_state) {
+static PyObject *__pyx_pw_8pygcgopt_3gcg_14GCGMasterModel_7__setstate_cython__(PyObject *__pyx_v_self, PyObject *__pyx_v___pyx_state); /*proto*/
+static char __pyx_doc_8pygcgopt_3gcg_14GCGMasterModel_6__setstate_cython__[] = "GCGMasterModel.__setstate_cython__(self, __pyx_state)";
+static PyObject *__pyx_pw_8pygcgopt_3gcg_14GCGMasterModel_7__setstate_cython__(PyObject *__pyx_v_self, PyObject *__pyx_v___pyx_state) {
   PyObject *__pyx_r = 0;
   __Pyx_RefNannyDeclarations
   __Pyx_RefNannySetupContext("__setstate_cython__ (wrapper)", 0);
-  __pyx_r = __pyx_pf_8pygcgopt_3gcg_14GCGMasterModel_4__setstate_cython__(((struct __pyx_obj_8pygcgopt_3gcg_GCGMasterModel *)__pyx_v_self), ((PyObject *)__pyx_v___pyx_state));
+  __pyx_r = __pyx_pf_8pygcgopt_3gcg_14GCGMasterModel_6__setstate_cython__(((struct __pyx_obj_8pygcgopt_3gcg_GCGMasterModel *)__pyx_v_self), ((PyObject *)__pyx_v___pyx_state));
 
   /* function exit code */
   __Pyx_RefNannyFinishContext();
   return __pyx_r;
 }
 
-static PyObject *__pyx_pf_8pygcgopt_3gcg_14GCGMasterModel_4__setstate_cython__(CYTHON_UNUSED struct __pyx_obj_8pygcgopt_3gcg_GCGMasterModel *__pyx_v_self, CYTHON_UNUSED PyObject *__pyx_v___pyx_state) {
+static PyObject *__pyx_pf_8pygcgopt_3gcg_14GCGMasterModel_6__setstate_cython__(CYTHON_UNUSED struct __pyx_obj_8pygcgopt_3gcg_GCGMasterModel *__pyx_v_self, CYTHON_UNUSED PyObject *__pyx_v___pyx_state) {
   PyObject *__pyx_r = NULL;
   __Pyx_RefNannyDeclarations
   PyObject *__pyx_t_1 = NULL;
   int __pyx_lineno = 0;
   const char *__pyx_filename = NULL;
   int __pyx_clineno = 0;
   __Pyx_RefNannySetupContext("__setstate_cython__", 0);
@@ -43357,15 +43719,15 @@
   __Pyx_AddTraceback("pygcgopt.gcg.GCGMasterModel.__setstate_cython__", __pyx_clineno, __pyx_lineno, __pyx_filename);
   __pyx_r = NULL;
   __Pyx_XGIVEREF(__pyx_r);
   __Pyx_RefNannyFinishContext();
   return __pyx_r;
 }
 
-/* "pygcgopt/gcg.pyx":412
+/* "pygcgopt/gcg.pyx":432
  * 
  *     @staticmethod
  *     cdef create(GCG_COL* gcgcol):             # <<<<<<<<<<<<<<
  *         if gcgcol == NULL:
  *             raise Warning("cannot create Column with GCG_COL* == NULL")
  */
 
@@ -43376,80 +43738,80 @@
   int __pyx_t_1;
   PyObject *__pyx_t_2 = NULL;
   int __pyx_lineno = 0;
   const char *__pyx_filename = NULL;
   int __pyx_clineno = 0;
   __Pyx_RefNannySetupContext("create", 0);
 
-  /* "pygcgopt/gcg.pyx":413
+  /* "pygcgopt/gcg.pyx":433
  *     @staticmethod
  *     cdef create(GCG_COL* gcgcol):
  *         if gcgcol == NULL:             # <<<<<<<<<<<<<<
  *             raise Warning("cannot create Column with GCG_COL* == NULL")
  *         col = GCGColumn()
  */
   __pyx_t_1 = ((__pyx_v_gcgcol == NULL) != 0);
   if (unlikely(__pyx_t_1)) {
 
-    /* "pygcgopt/gcg.pyx":414
+    /* "pygcgopt/gcg.pyx":434
  *     cdef create(GCG_COL* gcgcol):
  *         if gcgcol == NULL:
  *             raise Warning("cannot create Column with GCG_COL* == NULL")             # <<<<<<<<<<<<<<
  *         col = GCGColumn()
  *         col.gcg_col = gcgcol
  */
-    __pyx_t_2 = __Pyx_PyObject_Call(__pyx_builtin_Warning, __pyx_tuple__28, NULL); if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 414, __pyx_L1_error)
+    __pyx_t_2 = __Pyx_PyObject_Call(__pyx_builtin_Warning, __pyx_tuple__28, NULL); if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 434, __pyx_L1_error)
     __Pyx_GOTREF(__pyx_t_2);
     __Pyx_Raise(__pyx_t_2, 0, 0, 0);
     __Pyx_DECREF(__pyx_t_2); __pyx_t_2 = 0;
-    __PYX_ERR(3, 414, __pyx_L1_error)
+    __PYX_ERR(3, 434, __pyx_L1_error)
 
-    /* "pygcgopt/gcg.pyx":413
+    /* "pygcgopt/gcg.pyx":433
  *     @staticmethod
  *     cdef create(GCG_COL* gcgcol):
  *         if gcgcol == NULL:             # <<<<<<<<<<<<<<
  *             raise Warning("cannot create Column with GCG_COL* == NULL")
  *         col = GCGColumn()
  */
   }
 
-  /* "pygcgopt/gcg.pyx":415
+  /* "pygcgopt/gcg.pyx":435
  *         if gcgcol == NULL:
  *             raise Warning("cannot create Column with GCG_COL* == NULL")
  *         col = GCGColumn()             # <<<<<<<<<<<<<<
  *         col.gcg_col = gcgcol
  *         return col
  */
-  __pyx_t_2 = __Pyx_PyObject_CallNoArg(((PyObject *)__pyx_ptype_8pygcgopt_3gcg_GCGColumn)); if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 415, __pyx_L1_error)
+  __pyx_t_2 = __Pyx_PyObject_CallNoArg(((PyObject *)__pyx_ptype_8pygcgopt_3gcg_GCGColumn)); if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 435, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_2);
   __pyx_v_col = ((struct __pyx_obj_8pygcgopt_3gcg_GCGColumn *)__pyx_t_2);
   __pyx_t_2 = 0;
 
-  /* "pygcgopt/gcg.pyx":416
+  /* "pygcgopt/gcg.pyx":436
  *             raise Warning("cannot create Column with GCG_COL* == NULL")
  *         col = GCGColumn()
  *         col.gcg_col = gcgcol             # <<<<<<<<<<<<<<
  *         return col
  * 
  */
   __pyx_v_col->gcg_col = __pyx_v_gcgcol;
 
-  /* "pygcgopt/gcg.pyx":417
+  /* "pygcgopt/gcg.pyx":437
  *         col = GCGColumn()
  *         col.gcg_col = gcgcol
  *         return col             # <<<<<<<<<<<<<<
  * 
  *     def __hash__(self):
  */
   __Pyx_XDECREF(__pyx_r);
   __Pyx_INCREF(((PyObject *)__pyx_v_col));
   __pyx_r = ((PyObject *)__pyx_v_col);
   goto __pyx_L0;
 
-  /* "pygcgopt/gcg.pyx":412
+  /* "pygcgopt/gcg.pyx":432
  * 
  *     @staticmethod
  *     cdef create(GCG_COL* gcgcol):             # <<<<<<<<<<<<<<
  *         if gcgcol == NULL:
  *             raise Warning("cannot create Column with GCG_COL* == NULL")
  */
 
@@ -43461,15 +43823,15 @@
   __pyx_L0:;
   __Pyx_XDECREF((PyObject *)__pyx_v_col);
   __Pyx_XGIVEREF(__pyx_r);
   __Pyx_RefNannyFinishContext();
   return __pyx_r;
 }
 
-/* "pygcgopt/gcg.pyx":419
+/* "pygcgopt/gcg.pyx":439
  *         return col
  * 
  *     def __hash__(self):             # <<<<<<<<<<<<<<
  *         return hash(<size_t>self.gcg_col)
  * 
  */
 
@@ -43492,29 +43854,29 @@
   PyObject *__pyx_t_1 = NULL;
   Py_hash_t __pyx_t_2;
   int __pyx_lineno = 0;
   const char *__pyx_filename = NULL;
   int __pyx_clineno = 0;
   __Pyx_RefNannySetupContext("__hash__", 0);
 
-  /* "pygcgopt/gcg.pyx":420
+  /* "pygcgopt/gcg.pyx":440
  * 
  *     def __hash__(self):
  *         return hash(<size_t>self.gcg_col)             # <<<<<<<<<<<<<<
  * 
  *     def __eq__(self, other):
  */
-  __pyx_t_1 = __Pyx_PyInt_FromSize_t(((size_t)__pyx_v_self->gcg_col)); if (unlikely(!__pyx_t_1)) __PYX_ERR(3, 420, __pyx_L1_error)
+  __pyx_t_1 = __Pyx_PyInt_FromSize_t(((size_t)__pyx_v_self->gcg_col)); if (unlikely(!__pyx_t_1)) __PYX_ERR(3, 440, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_1);
-  __pyx_t_2 = PyObject_Hash(__pyx_t_1); if (unlikely(__pyx_t_2 == ((Py_hash_t)-1))) __PYX_ERR(3, 420, __pyx_L1_error)
+  __pyx_t_2 = PyObject_Hash(__pyx_t_1); if (unlikely(__pyx_t_2 == ((Py_hash_t)-1))) __PYX_ERR(3, 440, __pyx_L1_error)
   __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
   __pyx_r = __pyx_t_2;
   goto __pyx_L0;
 
-  /* "pygcgopt/gcg.pyx":419
+  /* "pygcgopt/gcg.pyx":439
  *         return col
  * 
  *     def __hash__(self):             # <<<<<<<<<<<<<<
  *         return hash(<size_t>self.gcg_col)
  * 
  */
 
@@ -43525,15 +43887,15 @@
   __pyx_r = -1;
   __pyx_L0:;
   if (unlikely(__pyx_r == -1) && !PyErr_Occurred()) __pyx_r = -2;
   __Pyx_RefNannyFinishContext();
   return __pyx_r;
 }
 
-/* "pygcgopt/gcg.pyx":422
+/* "pygcgopt/gcg.pyx":442
  *         return hash(<size_t>self.gcg_col)
  * 
  *     def __eq__(self, other):             # <<<<<<<<<<<<<<
  *         return (self.__class__ == other.__class__ and self.gcg_col == (<GCGColumn>other).gcg_col)
  */
 
 /* Python wrapper */
@@ -43558,47 +43920,47 @@
   PyObject *__pyx_t_4 = NULL;
   int __pyx_t_5;
   int __pyx_lineno = 0;
   const char *__pyx_filename = NULL;
   int __pyx_clineno = 0;
   __Pyx_RefNannySetupContext("__eq__", 0);
 
-  /* "pygcgopt/gcg.pyx":423
+  /* "pygcgopt/gcg.pyx":443
  * 
  *     def __eq__(self, other):
  *         return (self.__class__ == other.__class__ and self.gcg_col == (<GCGColumn>other).gcg_col)             # <<<<<<<<<<<<<<
  */
   __Pyx_XDECREF(__pyx_r);
-  __pyx_t_2 = __Pyx_PyObject_GetAttrStr(((PyObject *)__pyx_v_self), __pyx_n_s_class); if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 423, __pyx_L1_error)
+  __pyx_t_2 = __Pyx_PyObject_GetAttrStr(((PyObject *)__pyx_v_self), __pyx_n_s_class); if (unlikely(!__pyx_t_2)) __PYX_ERR(3, 443, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_2);
-  __pyx_t_3 = __Pyx_PyObject_GetAttrStr(__pyx_v_other, __pyx_n_s_class); if (unlikely(!__pyx_t_3)) __PYX_ERR(3, 423, __pyx_L1_error)
+  __pyx_t_3 = __Pyx_PyObject_GetAttrStr(__pyx_v_other, __pyx_n_s_class); if (unlikely(!__pyx_t_3)) __PYX_ERR(3, 443, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_3);
-  __pyx_t_4 = PyObject_RichCompare(__pyx_t_2, __pyx_t_3, Py_EQ); __Pyx_XGOTREF(__pyx_t_4); if (unlikely(!__pyx_t_4)) __PYX_ERR(3, 423, __pyx_L1_error)
+  __pyx_t_4 = PyObject_RichCompare(__pyx_t_2, __pyx_t_3, Py_EQ); __Pyx_XGOTREF(__pyx_t_4); if (unlikely(!__pyx_t_4)) __PYX_ERR(3, 443, __pyx_L1_error)
   __Pyx_DECREF(__pyx_t_2); __pyx_t_2 = 0;
   __Pyx_DECREF(__pyx_t_3); __pyx_t_3 = 0;
-  __pyx_t_5 = __Pyx_PyObject_IsTrue(__pyx_t_4); if (unlikely(__pyx_t_5 < 0)) __PYX_ERR(3, 423, __pyx_L1_error)
+  __pyx_t_5 = __Pyx_PyObject_IsTrue(__pyx_t_4); if (unlikely(__pyx_t_5 < 0)) __PYX_ERR(3, 443, __pyx_L1_error)
   if (__pyx_t_5) {
     __Pyx_DECREF(__pyx_t_4); __pyx_t_4 = 0;
   } else {
     __Pyx_INCREF(__pyx_t_4);
     __pyx_t_1 = __pyx_t_4;
     __Pyx_DECREF(__pyx_t_4); __pyx_t_4 = 0;
     goto __pyx_L3_bool_binop_done;
   }
   __pyx_t_5 = (__pyx_v_self->gcg_col == ((struct __pyx_obj_8pygcgopt_3gcg_GCGColumn *)__pyx_v_other)->gcg_col);
-  __pyx_t_4 = __Pyx_PyBool_FromLong(__pyx_t_5); if (unlikely(!__pyx_t_4)) __PYX_ERR(3, 423, __pyx_L1_error)
+  __pyx_t_4 = __Pyx_PyBool_FromLong(__pyx_t_5); if (unlikely(!__pyx_t_4)) __PYX_ERR(3, 443, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_4);
   __pyx_t_1 = __pyx_t_4;
   __pyx_t_4 = 0;
   __pyx_L3_bool_binop_done:;
   __pyx_r = __pyx_t_1;
   __pyx_t_1 = 0;
   goto __pyx_L0;
 
-  /* "pygcgopt/gcg.pyx":422
+  /* "pygcgopt/gcg.pyx":442
  *         return hash(<size_t>self.gcg_col)
  * 
  *     def __eq__(self, other):             # <<<<<<<<<<<<<<
  *         return (self.__class__ == other.__class__ and self.gcg_col == (<GCGColumn>other).gcg_col)
  */
 
   /* function exit code */
@@ -43814,151 +44176,155 @@
 }
 
 static PyObject *__pyx_pf_8pygcgopt_3gcg___pyx_unpickle_Detector(CYTHON_UNUSED PyObject *__pyx_self, PyObject *__pyx_v___pyx_type, long __pyx_v___pyx_checksum, PyObject *__pyx_v___pyx_state) {
   PyObject *__pyx_v___pyx_PickleError = 0;
   PyObject *__pyx_v___pyx_result = 0;
   PyObject *__pyx_r = NULL;
   __Pyx_RefNannyDeclarations
-  int __pyx_t_1;
-  PyObject *__pyx_t_2 = NULL;
-  PyObject *__pyx_t_3 = NULL;
+  PyObject *__pyx_t_1 = NULL;
+  int __pyx_t_2;
+  int __pyx_t_3;
   PyObject *__pyx_t_4 = NULL;
   PyObject *__pyx_t_5 = NULL;
-  int __pyx_t_6;
+  PyObject *__pyx_t_6 = NULL;
   int __pyx_lineno = 0;
   const char *__pyx_filename = NULL;
   int __pyx_clineno = 0;
   __Pyx_RefNannySetupContext("__pyx_unpickle_Detector", 0);
 
   /* "(tree fragment)":4
  *     cdef object __pyx_PickleError
  *     cdef object __pyx_result
- *     if __pyx_checksum != 0xf7f977a:             # <<<<<<<<<<<<<<
+ *     if __pyx_checksum not in (0xf7f977a, 0xdad04ef, 0x67e9880):             # <<<<<<<<<<<<<<
  *         from pickle import PickleError as __pyx_PickleError
- *         raise __pyx_PickleError("Incompatible checksums (%s vs 0xf7f977a = (detectorname, model))" % __pyx_checksum)
+ *         raise __pyx_PickleError("Incompatible checksums (0x%x vs (0xf7f977a, 0xdad04ef, 0x67e9880) = (detectorname, model))" % __pyx_checksum)
  */
-  __pyx_t_1 = ((__pyx_v___pyx_checksum != 0xf7f977a) != 0);
-  if (__pyx_t_1) {
+  __pyx_t_1 = __Pyx_PyInt_From_long(__pyx_v___pyx_checksum); if (unlikely(!__pyx_t_1)) __PYX_ERR(4, 4, __pyx_L1_error)
+  __Pyx_GOTREF(__pyx_t_1);
+  __pyx_t_2 = (__Pyx_PySequence_ContainsTF(__pyx_t_1, __pyx_tuple__31, Py_NE)); if (unlikely(__pyx_t_2 < 0)) __PYX_ERR(4, 4, __pyx_L1_error)
+  __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
+  __pyx_t_3 = (__pyx_t_2 != 0);
+  if (__pyx_t_3) {
 
     /* "(tree fragment)":5
  *     cdef object __pyx_result
- *     if __pyx_checksum != 0xf7f977a:
+ *     if __pyx_checksum not in (0xf7f977a, 0xdad04ef, 0x67e9880):
  *         from pickle import PickleError as __pyx_PickleError             # <<<<<<<<<<<<<<
- *         raise __pyx_PickleError("Incompatible checksums (%s vs 0xf7f977a = (detectorname, model))" % __pyx_checksum)
+ *         raise __pyx_PickleError("Incompatible checksums (0x%x vs (0xf7f977a, 0xdad04ef, 0x67e9880) = (detectorname, model))" % __pyx_checksum)
  *     __pyx_result = Detector.__new__(__pyx_type)
  */
-    __pyx_t_2 = PyList_New(1); if (unlikely(!__pyx_t_2)) __PYX_ERR(4, 5, __pyx_L1_error)
-    __Pyx_GOTREF(__pyx_t_2);
+    __pyx_t_1 = PyList_New(1); if (unlikely(!__pyx_t_1)) __PYX_ERR(4, 5, __pyx_L1_error)
+    __Pyx_GOTREF(__pyx_t_1);
     __Pyx_INCREF(__pyx_n_s_PickleError);
     __Pyx_GIVEREF(__pyx_n_s_PickleError);
-    PyList_SET_ITEM(__pyx_t_2, 0, __pyx_n_s_PickleError);
-    __pyx_t_3 = __Pyx_Import(__pyx_n_s_pickle, __pyx_t_2, 0); if (unlikely(!__pyx_t_3)) __PYX_ERR(4, 5, __pyx_L1_error)
-    __Pyx_GOTREF(__pyx_t_3);
-    __Pyx_DECREF(__pyx_t_2); __pyx_t_2 = 0;
-    __pyx_t_2 = __Pyx_ImportFrom(__pyx_t_3, __pyx_n_s_PickleError); if (unlikely(!__pyx_t_2)) __PYX_ERR(4, 5, __pyx_L1_error)
-    __Pyx_GOTREF(__pyx_t_2);
-    __Pyx_INCREF(__pyx_t_2);
-    __pyx_v___pyx_PickleError = __pyx_t_2;
-    __Pyx_DECREF(__pyx_t_2); __pyx_t_2 = 0;
-    __Pyx_DECREF(__pyx_t_3); __pyx_t_3 = 0;
+    PyList_SET_ITEM(__pyx_t_1, 0, __pyx_n_s_PickleError);
+    __pyx_t_4 = __Pyx_Import(__pyx_n_s_pickle, __pyx_t_1, 0); if (unlikely(!__pyx_t_4)) __PYX_ERR(4, 5, __pyx_L1_error)
+    __Pyx_GOTREF(__pyx_t_4);
+    __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
+    __pyx_t_1 = __Pyx_ImportFrom(__pyx_t_4, __pyx_n_s_PickleError); if (unlikely(!__pyx_t_1)) __PYX_ERR(4, 5, __pyx_L1_error)
+    __Pyx_GOTREF(__pyx_t_1);
+    __Pyx_INCREF(__pyx_t_1);
+    __pyx_v___pyx_PickleError = __pyx_t_1;
+    __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
+    __Pyx_DECREF(__pyx_t_4); __pyx_t_4 = 0;
 
     /* "(tree fragment)":6
- *     if __pyx_checksum != 0xf7f977a:
+ *     if __pyx_checksum not in (0xf7f977a, 0xdad04ef, 0x67e9880):
  *         from pickle import PickleError as __pyx_PickleError
- *         raise __pyx_PickleError("Incompatible checksums (%s vs 0xf7f977a = (detectorname, model))" % __pyx_checksum)             # <<<<<<<<<<<<<<
+ *         raise __pyx_PickleError("Incompatible checksums (0x%x vs (0xf7f977a, 0xdad04ef, 0x67e9880) = (detectorname, model))" % __pyx_checksum)             # <<<<<<<<<<<<<<
  *     __pyx_result = Detector.__new__(__pyx_type)
  *     if __pyx_state is not None:
  */
-    __pyx_t_2 = __Pyx_PyInt_From_long(__pyx_v___pyx_checksum); if (unlikely(!__pyx_t_2)) __PYX_ERR(4, 6, __pyx_L1_error)
-    __Pyx_GOTREF(__pyx_t_2);
-    __pyx_t_4 = __Pyx_PyString_Format(__pyx_kp_s_Incompatible_checksums_s_vs_0xf7, __pyx_t_2); if (unlikely(!__pyx_t_4)) __PYX_ERR(4, 6, __pyx_L1_error)
-    __Pyx_GOTREF(__pyx_t_4);
-    __Pyx_DECREF(__pyx_t_2); __pyx_t_2 = 0;
+    __pyx_t_1 = __Pyx_PyInt_From_long(__pyx_v___pyx_checksum); if (unlikely(!__pyx_t_1)) __PYX_ERR(4, 6, __pyx_L1_error)
+    __Pyx_GOTREF(__pyx_t_1);
+    __pyx_t_5 = __Pyx_PyString_Format(__pyx_kp_s_Incompatible_checksums_0x_x_vs_0, __pyx_t_1); if (unlikely(!__pyx_t_5)) __PYX_ERR(4, 6, __pyx_L1_error)
+    __Pyx_GOTREF(__pyx_t_5);
+    __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
     __Pyx_INCREF(__pyx_v___pyx_PickleError);
-    __pyx_t_2 = __pyx_v___pyx_PickleError; __pyx_t_5 = NULL;
-    if (CYTHON_UNPACK_METHODS && unlikely(PyMethod_Check(__pyx_t_2))) {
-      __pyx_t_5 = PyMethod_GET_SELF(__pyx_t_2);
-      if (likely(__pyx_t_5)) {
-        PyObject* function = PyMethod_GET_FUNCTION(__pyx_t_2);
-        __Pyx_INCREF(__pyx_t_5);
+    __pyx_t_1 = __pyx_v___pyx_PickleError; __pyx_t_6 = NULL;
+    if (CYTHON_UNPACK_METHODS && unlikely(PyMethod_Check(__pyx_t_1))) {
+      __pyx_t_6 = PyMethod_GET_SELF(__pyx_t_1);
+      if (likely(__pyx_t_6)) {
+        PyObject* function = PyMethod_GET_FUNCTION(__pyx_t_1);
+        __Pyx_INCREF(__pyx_t_6);
         __Pyx_INCREF(function);
-        __Pyx_DECREF_SET(__pyx_t_2, function);
+        __Pyx_DECREF_SET(__pyx_t_1, function);
       }
     }
-    __pyx_t_3 = (__pyx_t_5) ? __Pyx_PyObject_Call2Args(__pyx_t_2, __pyx_t_5, __pyx_t_4) : __Pyx_PyObject_CallOneArg(__pyx_t_2, __pyx_t_4);
-    __Pyx_XDECREF(__pyx_t_5); __pyx_t_5 = 0;
+    __pyx_t_4 = (__pyx_t_6) ? __Pyx_PyObject_Call2Args(__pyx_t_1, __pyx_t_6, __pyx_t_5) : __Pyx_PyObject_CallOneArg(__pyx_t_1, __pyx_t_5);
+    __Pyx_XDECREF(__pyx_t_6); __pyx_t_6 = 0;
+    __Pyx_DECREF(__pyx_t_5); __pyx_t_5 = 0;
+    if (unlikely(!__pyx_t_4)) __PYX_ERR(4, 6, __pyx_L1_error)
+    __Pyx_GOTREF(__pyx_t_4);
+    __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
+    __Pyx_Raise(__pyx_t_4, 0, 0, 0);
     __Pyx_DECREF(__pyx_t_4); __pyx_t_4 = 0;
-    if (unlikely(!__pyx_t_3)) __PYX_ERR(4, 6, __pyx_L1_error)
-    __Pyx_GOTREF(__pyx_t_3);
-    __Pyx_DECREF(__pyx_t_2); __pyx_t_2 = 0;
-    __Pyx_Raise(__pyx_t_3, 0, 0, 0);
-    __Pyx_DECREF(__pyx_t_3); __pyx_t_3 = 0;
     __PYX_ERR(4, 6, __pyx_L1_error)
 
     /* "(tree fragment)":4
  *     cdef object __pyx_PickleError
  *     cdef object __pyx_result
- *     if __pyx_checksum != 0xf7f977a:             # <<<<<<<<<<<<<<
+ *     if __pyx_checksum not in (0xf7f977a, 0xdad04ef, 0x67e9880):             # <<<<<<<<<<<<<<
  *         from pickle import PickleError as __pyx_PickleError
- *         raise __pyx_PickleError("Incompatible checksums (%s vs 0xf7f977a = (detectorname, model))" % __pyx_checksum)
+ *         raise __pyx_PickleError("Incompatible checksums (0x%x vs (0xf7f977a, 0xdad04ef, 0x67e9880) = (detectorname, model))" % __pyx_checksum)
  */
   }
 
   /* "(tree fragment)":7
  *         from pickle import PickleError as __pyx_PickleError
- *         raise __pyx_PickleError("Incompatible checksums (%s vs 0xf7f977a = (detectorname, model))" % __pyx_checksum)
+ *         raise __pyx_PickleError("Incompatible checksums (0x%x vs (0xf7f977a, 0xdad04ef, 0x67e9880) = (detectorname, model))" % __pyx_checksum)
  *     __pyx_result = Detector.__new__(__pyx_type)             # <<<<<<<<<<<<<<
  *     if __pyx_state is not None:
  *         __pyx_unpickle_Detector__set_state(<Detector> __pyx_result, __pyx_state)
  */
-  __pyx_t_2 = __Pyx_PyObject_GetAttrStr(((PyObject *)__pyx_ptype_8pygcgopt_3gcg_Detector), __pyx_n_s_new); if (unlikely(!__pyx_t_2)) __PYX_ERR(4, 7, __pyx_L1_error)
-  __Pyx_GOTREF(__pyx_t_2);
-  __pyx_t_4 = NULL;
-  if (CYTHON_UNPACK_METHODS && likely(PyMethod_Check(__pyx_t_2))) {
-    __pyx_t_4 = PyMethod_GET_SELF(__pyx_t_2);
-    if (likely(__pyx_t_4)) {
-      PyObject* function = PyMethod_GET_FUNCTION(__pyx_t_2);
-      __Pyx_INCREF(__pyx_t_4);
+  __pyx_t_1 = __Pyx_PyObject_GetAttrStr(((PyObject *)__pyx_ptype_8pygcgopt_3gcg_Detector), __pyx_n_s_new); if (unlikely(!__pyx_t_1)) __PYX_ERR(4, 7, __pyx_L1_error)
+  __Pyx_GOTREF(__pyx_t_1);
+  __pyx_t_5 = NULL;
+  if (CYTHON_UNPACK_METHODS && likely(PyMethod_Check(__pyx_t_1))) {
+    __pyx_t_5 = PyMethod_GET_SELF(__pyx_t_1);
+    if (likely(__pyx_t_5)) {
+      PyObject* function = PyMethod_GET_FUNCTION(__pyx_t_1);
+      __Pyx_INCREF(__pyx_t_5);
       __Pyx_INCREF(function);
-      __Pyx_DECREF_SET(__pyx_t_2, function);
+      __Pyx_DECREF_SET(__pyx_t_1, function);
     }
   }
-  __pyx_t_3 = (__pyx_t_4) ? __Pyx_PyObject_Call2Args(__pyx_t_2, __pyx_t_4, __pyx_v___pyx_type) : __Pyx_PyObject_CallOneArg(__pyx_t_2, __pyx_v___pyx_type);
-  __Pyx_XDECREF(__pyx_t_4); __pyx_t_4 = 0;
-  if (unlikely(!__pyx_t_3)) __PYX_ERR(4, 7, __pyx_L1_error)
-  __Pyx_GOTREF(__pyx_t_3);
-  __Pyx_DECREF(__pyx_t_2); __pyx_t_2 = 0;
-  __pyx_v___pyx_result = __pyx_t_3;
-  __pyx_t_3 = 0;
+  __pyx_t_4 = (__pyx_t_5) ? __Pyx_PyObject_Call2Args(__pyx_t_1, __pyx_t_5, __pyx_v___pyx_type) : __Pyx_PyObject_CallOneArg(__pyx_t_1, __pyx_v___pyx_type);
+  __Pyx_XDECREF(__pyx_t_5); __pyx_t_5 = 0;
+  if (unlikely(!__pyx_t_4)) __PYX_ERR(4, 7, __pyx_L1_error)
+  __Pyx_GOTREF(__pyx_t_4);
+  __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
+  __pyx_v___pyx_result = __pyx_t_4;
+  __pyx_t_4 = 0;
 
   /* "(tree fragment)":8
- *         raise __pyx_PickleError("Incompatible checksums (%s vs 0xf7f977a = (detectorname, model))" % __pyx_checksum)
+ *         raise __pyx_PickleError("Incompatible checksums (0x%x vs (0xf7f977a, 0xdad04ef, 0x67e9880) = (detectorname, model))" % __pyx_checksum)
  *     __pyx_result = Detector.__new__(__pyx_type)
  *     if __pyx_state is not None:             # <<<<<<<<<<<<<<
  *         __pyx_unpickle_Detector__set_state(<Detector> __pyx_result, __pyx_state)
  *     return __pyx_result
  */
-  __pyx_t_1 = (__pyx_v___pyx_state != Py_None);
-  __pyx_t_6 = (__pyx_t_1 != 0);
-  if (__pyx_t_6) {
+  __pyx_t_3 = (__pyx_v___pyx_state != Py_None);
+  __pyx_t_2 = (__pyx_t_3 != 0);
+  if (__pyx_t_2) {
 
     /* "(tree fragment)":9
  *     __pyx_result = Detector.__new__(__pyx_type)
  *     if __pyx_state is not None:
  *         __pyx_unpickle_Detector__set_state(<Detector> __pyx_result, __pyx_state)             # <<<<<<<<<<<<<<
  *     return __pyx_result
  * cdef __pyx_unpickle_Detector__set_state(Detector __pyx_result, tuple __pyx_state):
  */
-    if (!(likely(PyTuple_CheckExact(__pyx_v___pyx_state))||((__pyx_v___pyx_state) == Py_None)||(PyErr_Format(PyExc_TypeError, "Expected %.16s, got %.200s", "tuple", Py_TYPE(__pyx_v___pyx_state)->tp_name), 0))) __PYX_ERR(4, 9, __pyx_L1_error)
-    __pyx_t_3 = __pyx_f_8pygcgopt_3gcg___pyx_unpickle_Detector__set_state(((struct __pyx_obj_8pygcgopt_3gcg_Detector *)__pyx_v___pyx_result), ((PyObject*)__pyx_v___pyx_state)); if (unlikely(!__pyx_t_3)) __PYX_ERR(4, 9, __pyx_L1_error)
-    __Pyx_GOTREF(__pyx_t_3);
-    __Pyx_DECREF(__pyx_t_3); __pyx_t_3 = 0;
+    if (!(likely(PyTuple_CheckExact(__pyx_v___pyx_state))||((__pyx_v___pyx_state) == Py_None)||((void)PyErr_Format(PyExc_TypeError, "Expected %.16s, got %.200s", "tuple", Py_TYPE(__pyx_v___pyx_state)->tp_name), 0))) __PYX_ERR(4, 9, __pyx_L1_error)
+    __pyx_t_4 = __pyx_f_8pygcgopt_3gcg___pyx_unpickle_Detector__set_state(((struct __pyx_obj_8pygcgopt_3gcg_Detector *)__pyx_v___pyx_result), ((PyObject*)__pyx_v___pyx_state)); if (unlikely(!__pyx_t_4)) __PYX_ERR(4, 9, __pyx_L1_error)
+    __Pyx_GOTREF(__pyx_t_4);
+    __Pyx_DECREF(__pyx_t_4); __pyx_t_4 = 0;
 
     /* "(tree fragment)":8
- *         raise __pyx_PickleError("Incompatible checksums (%s vs 0xf7f977a = (detectorname, model))" % __pyx_checksum)
+ *         raise __pyx_PickleError("Incompatible checksums (0x%x vs (0xf7f977a, 0xdad04ef, 0x67e9880) = (detectorname, model))" % __pyx_checksum)
  *     __pyx_result = Detector.__new__(__pyx_type)
  *     if __pyx_state is not None:             # <<<<<<<<<<<<<<
  *         __pyx_unpickle_Detector__set_state(<Detector> __pyx_result, __pyx_state)
  *     return __pyx_result
  */
   }
 
@@ -43978,18 +44344,18 @@
  * def __pyx_unpickle_Detector(__pyx_type, long __pyx_checksum, __pyx_state):             # <<<<<<<<<<<<<<
  *     cdef object __pyx_PickleError
  *     cdef object __pyx_result
  */
 
   /* function exit code */
   __pyx_L1_error:;
-  __Pyx_XDECREF(__pyx_t_2);
-  __Pyx_XDECREF(__pyx_t_3);
+  __Pyx_XDECREF(__pyx_t_1);
   __Pyx_XDECREF(__pyx_t_4);
   __Pyx_XDECREF(__pyx_t_5);
+  __Pyx_XDECREF(__pyx_t_6);
   __Pyx_AddTraceback("pygcgopt.gcg.__pyx_unpickle_Detector", __pyx_clineno, __pyx_lineno, __pyx_filename);
   __pyx_r = NULL;
   __pyx_L0:;
   __Pyx_XDECREF(__pyx_v___pyx_PickleError);
   __Pyx_XDECREF(__pyx_v___pyx_result);
   __Pyx_XGIVEREF(__pyx_r);
   __Pyx_RefNannyFinishContext();
@@ -44029,15 +44395,15 @@
  */
   if (unlikely(__pyx_v___pyx_state == Py_None)) {
     PyErr_SetString(PyExc_TypeError, "'NoneType' object is not subscriptable");
     __PYX_ERR(4, 12, __pyx_L1_error)
   }
   __pyx_t_1 = __Pyx_GetItemInt_Tuple(__pyx_v___pyx_state, 0, long, 1, __Pyx_PyInt_From_long, 0, 0, 1); if (unlikely(!__pyx_t_1)) __PYX_ERR(4, 12, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_1);
-  if (!(likely(PyUnicode_CheckExact(__pyx_t_1))||((__pyx_t_1) == Py_None)||(PyErr_Format(PyExc_TypeError, "Expected %.16s, got %.200s", "unicode", Py_TYPE(__pyx_t_1)->tp_name), 0))) __PYX_ERR(4, 12, __pyx_L1_error)
+  if (!(likely(PyUnicode_CheckExact(__pyx_t_1))||((__pyx_t_1) == Py_None)||((void)PyErr_Format(PyExc_TypeError, "Expected %.16s, got %.200s", "unicode", Py_TYPE(__pyx_t_1)->tp_name), 0))) __PYX_ERR(4, 12, __pyx_L1_error)
   __Pyx_GIVEREF(__pyx_t_1);
   __Pyx_GOTREF(__pyx_v___pyx_result->detectorname);
   __Pyx_DECREF(__pyx_v___pyx_result->detectorname);
   __pyx_v___pyx_result->detectorname = ((PyObject*)__pyx_t_1);
   __pyx_t_1 = 0;
   if (unlikely(__pyx_v___pyx_state == Py_None)) {
     PyErr_SetString(PyExc_TypeError, "'NoneType' object is not subscriptable");
@@ -44225,151 +44591,155 @@
 }
 
 static PyObject *__pyx_pf_8pygcgopt_3gcg_2__pyx_unpickle_PricingSolver(CYTHON_UNUSED PyObject *__pyx_self, PyObject *__pyx_v___pyx_type, long __pyx_v___pyx_checksum, PyObject *__pyx_v___pyx_state) {
   PyObject *__pyx_v___pyx_PickleError = 0;
   PyObject *__pyx_v___pyx_result = 0;
   PyObject *__pyx_r = NULL;
   __Pyx_RefNannyDeclarations
-  int __pyx_t_1;
-  PyObject *__pyx_t_2 = NULL;
-  PyObject *__pyx_t_3 = NULL;
+  PyObject *__pyx_t_1 = NULL;
+  int __pyx_t_2;
+  int __pyx_t_3;
   PyObject *__pyx_t_4 = NULL;
   PyObject *__pyx_t_5 = NULL;
-  int __pyx_t_6;
+  PyObject *__pyx_t_6 = NULL;
   int __pyx_lineno = 0;
   const char *__pyx_filename = NULL;
   int __pyx_clineno = 0;
   __Pyx_RefNannySetupContext("__pyx_unpickle_PricingSolver", 0);
 
   /* "(tree fragment)":4
  *     cdef object __pyx_PickleError
  *     cdef object __pyx_result
- *     if __pyx_checksum != 0x7a6ef99:             # <<<<<<<<<<<<<<
+ *     if __pyx_checksum not in (0x7a6ef99, 0x9896ff5, 0x8734839):             # <<<<<<<<<<<<<<
  *         from pickle import PickleError as __pyx_PickleError
- *         raise __pyx_PickleError("Incompatible checksums (%s vs 0x7a6ef99 = (model, solvername))" % __pyx_checksum)
+ *         raise __pyx_PickleError("Incompatible checksums (0x%x vs (0x7a6ef99, 0x9896ff5, 0x8734839) = (model, solvername))" % __pyx_checksum)
  */
-  __pyx_t_1 = ((__pyx_v___pyx_checksum != 0x7a6ef99) != 0);
-  if (__pyx_t_1) {
+  __pyx_t_1 = __Pyx_PyInt_From_long(__pyx_v___pyx_checksum); if (unlikely(!__pyx_t_1)) __PYX_ERR(4, 4, __pyx_L1_error)
+  __Pyx_GOTREF(__pyx_t_1);
+  __pyx_t_2 = (__Pyx_PySequence_ContainsTF(__pyx_t_1, __pyx_tuple__32, Py_NE)); if (unlikely(__pyx_t_2 < 0)) __PYX_ERR(4, 4, __pyx_L1_error)
+  __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
+  __pyx_t_3 = (__pyx_t_2 != 0);
+  if (__pyx_t_3) {
 
     /* "(tree fragment)":5
  *     cdef object __pyx_result
- *     if __pyx_checksum != 0x7a6ef99:
+ *     if __pyx_checksum not in (0x7a6ef99, 0x9896ff5, 0x8734839):
  *         from pickle import PickleError as __pyx_PickleError             # <<<<<<<<<<<<<<
- *         raise __pyx_PickleError("Incompatible checksums (%s vs 0x7a6ef99 = (model, solvername))" % __pyx_checksum)
+ *         raise __pyx_PickleError("Incompatible checksums (0x%x vs (0x7a6ef99, 0x9896ff5, 0x8734839) = (model, solvername))" % __pyx_checksum)
  *     __pyx_result = PricingSolver.__new__(__pyx_type)
  */
-    __pyx_t_2 = PyList_New(1); if (unlikely(!__pyx_t_2)) __PYX_ERR(4, 5, __pyx_L1_error)
-    __Pyx_GOTREF(__pyx_t_2);
+    __pyx_t_1 = PyList_New(1); if (unlikely(!__pyx_t_1)) __PYX_ERR(4, 5, __pyx_L1_error)
+    __Pyx_GOTREF(__pyx_t_1);
     __Pyx_INCREF(__pyx_n_s_PickleError);
     __Pyx_GIVEREF(__pyx_n_s_PickleError);
-    PyList_SET_ITEM(__pyx_t_2, 0, __pyx_n_s_PickleError);
-    __pyx_t_3 = __Pyx_Import(__pyx_n_s_pickle, __pyx_t_2, 0); if (unlikely(!__pyx_t_3)) __PYX_ERR(4, 5, __pyx_L1_error)
-    __Pyx_GOTREF(__pyx_t_3);
-    __Pyx_DECREF(__pyx_t_2); __pyx_t_2 = 0;
-    __pyx_t_2 = __Pyx_ImportFrom(__pyx_t_3, __pyx_n_s_PickleError); if (unlikely(!__pyx_t_2)) __PYX_ERR(4, 5, __pyx_L1_error)
-    __Pyx_GOTREF(__pyx_t_2);
-    __Pyx_INCREF(__pyx_t_2);
-    __pyx_v___pyx_PickleError = __pyx_t_2;
-    __Pyx_DECREF(__pyx_t_2); __pyx_t_2 = 0;
-    __Pyx_DECREF(__pyx_t_3); __pyx_t_3 = 0;
+    PyList_SET_ITEM(__pyx_t_1, 0, __pyx_n_s_PickleError);
+    __pyx_t_4 = __Pyx_Import(__pyx_n_s_pickle, __pyx_t_1, 0); if (unlikely(!__pyx_t_4)) __PYX_ERR(4, 5, __pyx_L1_error)
+    __Pyx_GOTREF(__pyx_t_4);
+    __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
+    __pyx_t_1 = __Pyx_ImportFrom(__pyx_t_4, __pyx_n_s_PickleError); if (unlikely(!__pyx_t_1)) __PYX_ERR(4, 5, __pyx_L1_error)
+    __Pyx_GOTREF(__pyx_t_1);
+    __Pyx_INCREF(__pyx_t_1);
+    __pyx_v___pyx_PickleError = __pyx_t_1;
+    __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
+    __Pyx_DECREF(__pyx_t_4); __pyx_t_4 = 0;
 
     /* "(tree fragment)":6
- *     if __pyx_checksum != 0x7a6ef99:
+ *     if __pyx_checksum not in (0x7a6ef99, 0x9896ff5, 0x8734839):
  *         from pickle import PickleError as __pyx_PickleError
- *         raise __pyx_PickleError("Incompatible checksums (%s vs 0x7a6ef99 = (model, solvername))" % __pyx_checksum)             # <<<<<<<<<<<<<<
+ *         raise __pyx_PickleError("Incompatible checksums (0x%x vs (0x7a6ef99, 0x9896ff5, 0x8734839) = (model, solvername))" % __pyx_checksum)             # <<<<<<<<<<<<<<
  *     __pyx_result = PricingSolver.__new__(__pyx_type)
  *     if __pyx_state is not None:
  */
-    __pyx_t_2 = __Pyx_PyInt_From_long(__pyx_v___pyx_checksum); if (unlikely(!__pyx_t_2)) __PYX_ERR(4, 6, __pyx_L1_error)
-    __Pyx_GOTREF(__pyx_t_2);
-    __pyx_t_4 = __Pyx_PyString_Format(__pyx_kp_s_Incompatible_checksums_s_vs_0x7a, __pyx_t_2); if (unlikely(!__pyx_t_4)) __PYX_ERR(4, 6, __pyx_L1_error)
-    __Pyx_GOTREF(__pyx_t_4);
-    __Pyx_DECREF(__pyx_t_2); __pyx_t_2 = 0;
+    __pyx_t_1 = __Pyx_PyInt_From_long(__pyx_v___pyx_checksum); if (unlikely(!__pyx_t_1)) __PYX_ERR(4, 6, __pyx_L1_error)
+    __Pyx_GOTREF(__pyx_t_1);
+    __pyx_t_5 = __Pyx_PyString_Format(__pyx_kp_s_Incompatible_checksums_0x_x_vs_0_2, __pyx_t_1); if (unlikely(!__pyx_t_5)) __PYX_ERR(4, 6, __pyx_L1_error)
+    __Pyx_GOTREF(__pyx_t_5);
+    __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
     __Pyx_INCREF(__pyx_v___pyx_PickleError);
-    __pyx_t_2 = __pyx_v___pyx_PickleError; __pyx_t_5 = NULL;
-    if (CYTHON_UNPACK_METHODS && unlikely(PyMethod_Check(__pyx_t_2))) {
-      __pyx_t_5 = PyMethod_GET_SELF(__pyx_t_2);
-      if (likely(__pyx_t_5)) {
-        PyObject* function = PyMethod_GET_FUNCTION(__pyx_t_2);
-        __Pyx_INCREF(__pyx_t_5);
+    __pyx_t_1 = __pyx_v___pyx_PickleError; __pyx_t_6 = NULL;
+    if (CYTHON_UNPACK_METHODS && unlikely(PyMethod_Check(__pyx_t_1))) {
+      __pyx_t_6 = PyMethod_GET_SELF(__pyx_t_1);
+      if (likely(__pyx_t_6)) {
+        PyObject* function = PyMethod_GET_FUNCTION(__pyx_t_1);
+        __Pyx_INCREF(__pyx_t_6);
         __Pyx_INCREF(function);
-        __Pyx_DECREF_SET(__pyx_t_2, function);
+        __Pyx_DECREF_SET(__pyx_t_1, function);
       }
     }
-    __pyx_t_3 = (__pyx_t_5) ? __Pyx_PyObject_Call2Args(__pyx_t_2, __pyx_t_5, __pyx_t_4) : __Pyx_PyObject_CallOneArg(__pyx_t_2, __pyx_t_4);
-    __Pyx_XDECREF(__pyx_t_5); __pyx_t_5 = 0;
+    __pyx_t_4 = (__pyx_t_6) ? __Pyx_PyObject_Call2Args(__pyx_t_1, __pyx_t_6, __pyx_t_5) : __Pyx_PyObject_CallOneArg(__pyx_t_1, __pyx_t_5);
+    __Pyx_XDECREF(__pyx_t_6); __pyx_t_6 = 0;
+    __Pyx_DECREF(__pyx_t_5); __pyx_t_5 = 0;
+    if (unlikely(!__pyx_t_4)) __PYX_ERR(4, 6, __pyx_L1_error)
+    __Pyx_GOTREF(__pyx_t_4);
+    __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
+    __Pyx_Raise(__pyx_t_4, 0, 0, 0);
     __Pyx_DECREF(__pyx_t_4); __pyx_t_4 = 0;
-    if (unlikely(!__pyx_t_3)) __PYX_ERR(4, 6, __pyx_L1_error)
-    __Pyx_GOTREF(__pyx_t_3);
-    __Pyx_DECREF(__pyx_t_2); __pyx_t_2 = 0;
-    __Pyx_Raise(__pyx_t_3, 0, 0, 0);
-    __Pyx_DECREF(__pyx_t_3); __pyx_t_3 = 0;
     __PYX_ERR(4, 6, __pyx_L1_error)
 
     /* "(tree fragment)":4
  *     cdef object __pyx_PickleError
  *     cdef object __pyx_result
- *     if __pyx_checksum != 0x7a6ef99:             # <<<<<<<<<<<<<<
+ *     if __pyx_checksum not in (0x7a6ef99, 0x9896ff5, 0x8734839):             # <<<<<<<<<<<<<<
  *         from pickle import PickleError as __pyx_PickleError
- *         raise __pyx_PickleError("Incompatible checksums (%s vs 0x7a6ef99 = (model, solvername))" % __pyx_checksum)
+ *         raise __pyx_PickleError("Incompatible checksums (0x%x vs (0x7a6ef99, 0x9896ff5, 0x8734839) = (model, solvername))" % __pyx_checksum)
  */
   }
 
   /* "(tree fragment)":7
  *         from pickle import PickleError as __pyx_PickleError
- *         raise __pyx_PickleError("Incompatible checksums (%s vs 0x7a6ef99 = (model, solvername))" % __pyx_checksum)
+ *         raise __pyx_PickleError("Incompatible checksums (0x%x vs (0x7a6ef99, 0x9896ff5, 0x8734839) = (model, solvername))" % __pyx_checksum)
  *     __pyx_result = PricingSolver.__new__(__pyx_type)             # <<<<<<<<<<<<<<
  *     if __pyx_state is not None:
  *         __pyx_unpickle_PricingSolver__set_state(<PricingSolver> __pyx_result, __pyx_state)
  */
-  __pyx_t_2 = __Pyx_PyObject_GetAttrStr(((PyObject *)__pyx_ptype_8pygcgopt_3gcg_PricingSolver), __pyx_n_s_new); if (unlikely(!__pyx_t_2)) __PYX_ERR(4, 7, __pyx_L1_error)
-  __Pyx_GOTREF(__pyx_t_2);
-  __pyx_t_4 = NULL;
-  if (CYTHON_UNPACK_METHODS && likely(PyMethod_Check(__pyx_t_2))) {
-    __pyx_t_4 = PyMethod_GET_SELF(__pyx_t_2);
-    if (likely(__pyx_t_4)) {
-      PyObject* function = PyMethod_GET_FUNCTION(__pyx_t_2);
-      __Pyx_INCREF(__pyx_t_4);
+  __pyx_t_1 = __Pyx_PyObject_GetAttrStr(((PyObject *)__pyx_ptype_8pygcgopt_3gcg_PricingSolver), __pyx_n_s_new); if (unlikely(!__pyx_t_1)) __PYX_ERR(4, 7, __pyx_L1_error)
+  __Pyx_GOTREF(__pyx_t_1);
+  __pyx_t_5 = NULL;
+  if (CYTHON_UNPACK_METHODS && likely(PyMethod_Check(__pyx_t_1))) {
+    __pyx_t_5 = PyMethod_GET_SELF(__pyx_t_1);
+    if (likely(__pyx_t_5)) {
+      PyObject* function = PyMethod_GET_FUNCTION(__pyx_t_1);
+      __Pyx_INCREF(__pyx_t_5);
       __Pyx_INCREF(function);
-      __Pyx_DECREF_SET(__pyx_t_2, function);
+      __Pyx_DECREF_SET(__pyx_t_1, function);
     }
   }
-  __pyx_t_3 = (__pyx_t_4) ? __Pyx_PyObject_Call2Args(__pyx_t_2, __pyx_t_4, __pyx_v___pyx_type) : __Pyx_PyObject_CallOneArg(__pyx_t_2, __pyx_v___pyx_type);
-  __Pyx_XDECREF(__pyx_t_4); __pyx_t_4 = 0;
-  if (unlikely(!__pyx_t_3)) __PYX_ERR(4, 7, __pyx_L1_error)
-  __Pyx_GOTREF(__pyx_t_3);
-  __Pyx_DECREF(__pyx_t_2); __pyx_t_2 = 0;
-  __pyx_v___pyx_result = __pyx_t_3;
-  __pyx_t_3 = 0;
+  __pyx_t_4 = (__pyx_t_5) ? __Pyx_PyObject_Call2Args(__pyx_t_1, __pyx_t_5, __pyx_v___pyx_type) : __Pyx_PyObject_CallOneArg(__pyx_t_1, __pyx_v___pyx_type);
+  __Pyx_XDECREF(__pyx_t_5); __pyx_t_5 = 0;
+  if (unlikely(!__pyx_t_4)) __PYX_ERR(4, 7, __pyx_L1_error)
+  __Pyx_GOTREF(__pyx_t_4);
+  __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
+  __pyx_v___pyx_result = __pyx_t_4;
+  __pyx_t_4 = 0;
 
   /* "(tree fragment)":8
- *         raise __pyx_PickleError("Incompatible checksums (%s vs 0x7a6ef99 = (model, solvername))" % __pyx_checksum)
+ *         raise __pyx_PickleError("Incompatible checksums (0x%x vs (0x7a6ef99, 0x9896ff5, 0x8734839) = (model, solvername))" % __pyx_checksum)
  *     __pyx_result = PricingSolver.__new__(__pyx_type)
  *     if __pyx_state is not None:             # <<<<<<<<<<<<<<
  *         __pyx_unpickle_PricingSolver__set_state(<PricingSolver> __pyx_result, __pyx_state)
  *     return __pyx_result
  */
-  __pyx_t_1 = (__pyx_v___pyx_state != Py_None);
-  __pyx_t_6 = (__pyx_t_1 != 0);
-  if (__pyx_t_6) {
+  __pyx_t_3 = (__pyx_v___pyx_state != Py_None);
+  __pyx_t_2 = (__pyx_t_3 != 0);
+  if (__pyx_t_2) {
 
     /* "(tree fragment)":9
  *     __pyx_result = PricingSolver.__new__(__pyx_type)
  *     if __pyx_state is not None:
  *         __pyx_unpickle_PricingSolver__set_state(<PricingSolver> __pyx_result, __pyx_state)             # <<<<<<<<<<<<<<
  *     return __pyx_result
  * cdef __pyx_unpickle_PricingSolver__set_state(PricingSolver __pyx_result, tuple __pyx_state):
  */
-    if (!(likely(PyTuple_CheckExact(__pyx_v___pyx_state))||((__pyx_v___pyx_state) == Py_None)||(PyErr_Format(PyExc_TypeError, "Expected %.16s, got %.200s", "tuple", Py_TYPE(__pyx_v___pyx_state)->tp_name), 0))) __PYX_ERR(4, 9, __pyx_L1_error)
-    __pyx_t_3 = __pyx_f_8pygcgopt_3gcg___pyx_unpickle_PricingSolver__set_state(((struct __pyx_obj_8pygcgopt_3gcg_PricingSolver *)__pyx_v___pyx_result), ((PyObject*)__pyx_v___pyx_state)); if (unlikely(!__pyx_t_3)) __PYX_ERR(4, 9, __pyx_L1_error)
-    __Pyx_GOTREF(__pyx_t_3);
-    __Pyx_DECREF(__pyx_t_3); __pyx_t_3 = 0;
+    if (!(likely(PyTuple_CheckExact(__pyx_v___pyx_state))||((__pyx_v___pyx_state) == Py_None)||((void)PyErr_Format(PyExc_TypeError, "Expected %.16s, got %.200s", "tuple", Py_TYPE(__pyx_v___pyx_state)->tp_name), 0))) __PYX_ERR(4, 9, __pyx_L1_error)
+    __pyx_t_4 = __pyx_f_8pygcgopt_3gcg___pyx_unpickle_PricingSolver__set_state(((struct __pyx_obj_8pygcgopt_3gcg_PricingSolver *)__pyx_v___pyx_result), ((PyObject*)__pyx_v___pyx_state)); if (unlikely(!__pyx_t_4)) __PYX_ERR(4, 9, __pyx_L1_error)
+    __Pyx_GOTREF(__pyx_t_4);
+    __Pyx_DECREF(__pyx_t_4); __pyx_t_4 = 0;
 
     /* "(tree fragment)":8
- *         raise __pyx_PickleError("Incompatible checksums (%s vs 0x7a6ef99 = (model, solvername))" % __pyx_checksum)
+ *         raise __pyx_PickleError("Incompatible checksums (0x%x vs (0x7a6ef99, 0x9896ff5, 0x8734839) = (model, solvername))" % __pyx_checksum)
  *     __pyx_result = PricingSolver.__new__(__pyx_type)
  *     if __pyx_state is not None:             # <<<<<<<<<<<<<<
  *         __pyx_unpickle_PricingSolver__set_state(<PricingSolver> __pyx_result, __pyx_state)
  *     return __pyx_result
  */
   }
 
@@ -44389,18 +44759,18 @@
  * def __pyx_unpickle_PricingSolver(__pyx_type, long __pyx_checksum, __pyx_state):             # <<<<<<<<<<<<<<
  *     cdef object __pyx_PickleError
  *     cdef object __pyx_result
  */
 
   /* function exit code */
   __pyx_L1_error:;
-  __Pyx_XDECREF(__pyx_t_2);
-  __Pyx_XDECREF(__pyx_t_3);
+  __Pyx_XDECREF(__pyx_t_1);
   __Pyx_XDECREF(__pyx_t_4);
   __Pyx_XDECREF(__pyx_t_5);
+  __Pyx_XDECREF(__pyx_t_6);
   __Pyx_AddTraceback("pygcgopt.gcg.__pyx_unpickle_PricingSolver", __pyx_clineno, __pyx_lineno, __pyx_filename);
   __pyx_r = NULL;
   __pyx_L0:;
   __Pyx_XDECREF(__pyx_v___pyx_PickleError);
   __Pyx_XDECREF(__pyx_v___pyx_result);
   __Pyx_XGIVEREF(__pyx_r);
   __Pyx_RefNannyFinishContext();
@@ -44452,15 +44822,15 @@
   __pyx_t_1 = 0;
   if (unlikely(__pyx_v___pyx_state == Py_None)) {
     PyErr_SetString(PyExc_TypeError, "'NoneType' object is not subscriptable");
     __PYX_ERR(4, 12, __pyx_L1_error)
   }
   __pyx_t_1 = __Pyx_GetItemInt_Tuple(__pyx_v___pyx_state, 1, long, 1, __Pyx_PyInt_From_long, 0, 0, 1); if (unlikely(!__pyx_t_1)) __PYX_ERR(4, 12, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_1);
-  if (!(likely(PyUnicode_CheckExact(__pyx_t_1))||((__pyx_t_1) == Py_None)||(PyErr_Format(PyExc_TypeError, "Expected %.16s, got %.200s", "unicode", Py_TYPE(__pyx_t_1)->tp_name), 0))) __PYX_ERR(4, 12, __pyx_L1_error)
+  if (!(likely(PyUnicode_CheckExact(__pyx_t_1))||((__pyx_t_1) == Py_None)||((void)PyErr_Format(PyExc_TypeError, "Expected %.16s, got %.200s", "unicode", Py_TYPE(__pyx_t_1)->tp_name), 0))) __PYX_ERR(4, 12, __pyx_L1_error)
   __Pyx_GIVEREF(__pyx_t_1);
   __Pyx_GOTREF(__pyx_v___pyx_result->solvername);
   __Pyx_DECREF(__pyx_v___pyx_result->solvername);
   __pyx_v___pyx_result->solvername = ((PyObject*)__pyx_t_1);
   __pyx_t_1 = 0;
 
   /* "(tree fragment)":13
@@ -44636,151 +45006,155 @@
 }
 
 static PyObject *__pyx_pf_8pygcgopt_3gcg_4__pyx_unpickle_PY_GCG_PRICINGSTATUS(CYTHON_UNUSED PyObject *__pyx_self, PyObject *__pyx_v___pyx_type, long __pyx_v___pyx_checksum, PyObject *__pyx_v___pyx_state) {
   PyObject *__pyx_v___pyx_PickleError = 0;
   PyObject *__pyx_v___pyx_result = 0;
   PyObject *__pyx_r = NULL;
   __Pyx_RefNannyDeclarations
-  int __pyx_t_1;
-  PyObject *__pyx_t_2 = NULL;
-  PyObject *__pyx_t_3 = NULL;
+  PyObject *__pyx_t_1 = NULL;
+  int __pyx_t_2;
+  int __pyx_t_3;
   PyObject *__pyx_t_4 = NULL;
   PyObject *__pyx_t_5 = NULL;
-  int __pyx_t_6;
+  PyObject *__pyx_t_6 = NULL;
   int __pyx_lineno = 0;
   const char *__pyx_filename = NULL;
   int __pyx_clineno = 0;
   __Pyx_RefNannySetupContext("__pyx_unpickle_PY_GCG_PRICINGSTATUS", 0);
 
   /* "(tree fragment)":4
  *     cdef object __pyx_PickleError
  *     cdef object __pyx_result
- *     if __pyx_checksum != 0xd41d8cd:             # <<<<<<<<<<<<<<
+ *     if __pyx_checksum not in (0xd41d8cd, 0xe3b0c44, 0xda39a3e):             # <<<<<<<<<<<<<<
  *         from pickle import PickleError as __pyx_PickleError
- *         raise __pyx_PickleError("Incompatible checksums (%s vs 0xd41d8cd = ())" % __pyx_checksum)
+ *         raise __pyx_PickleError("Incompatible checksums (0x%x vs (0xd41d8cd, 0xe3b0c44, 0xda39a3e) = ())" % __pyx_checksum)
  */
-  __pyx_t_1 = ((__pyx_v___pyx_checksum != 0xd41d8cd) != 0);
-  if (__pyx_t_1) {
+  __pyx_t_1 = __Pyx_PyInt_From_long(__pyx_v___pyx_checksum); if (unlikely(!__pyx_t_1)) __PYX_ERR(4, 4, __pyx_L1_error)
+  __Pyx_GOTREF(__pyx_t_1);
+  __pyx_t_2 = (__Pyx_PySequence_ContainsTF(__pyx_t_1, __pyx_tuple__33, Py_NE)); if (unlikely(__pyx_t_2 < 0)) __PYX_ERR(4, 4, __pyx_L1_error)
+  __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
+  __pyx_t_3 = (__pyx_t_2 != 0);
+  if (__pyx_t_3) {
 
     /* "(tree fragment)":5
  *     cdef object __pyx_result
- *     if __pyx_checksum != 0xd41d8cd:
+ *     if __pyx_checksum not in (0xd41d8cd, 0xe3b0c44, 0xda39a3e):
  *         from pickle import PickleError as __pyx_PickleError             # <<<<<<<<<<<<<<
- *         raise __pyx_PickleError("Incompatible checksums (%s vs 0xd41d8cd = ())" % __pyx_checksum)
+ *         raise __pyx_PickleError("Incompatible checksums (0x%x vs (0xd41d8cd, 0xe3b0c44, 0xda39a3e) = ())" % __pyx_checksum)
  *     __pyx_result = PY_GCG_PRICINGSTATUS.__new__(__pyx_type)
  */
-    __pyx_t_2 = PyList_New(1); if (unlikely(!__pyx_t_2)) __PYX_ERR(4, 5, __pyx_L1_error)
-    __Pyx_GOTREF(__pyx_t_2);
+    __pyx_t_1 = PyList_New(1); if (unlikely(!__pyx_t_1)) __PYX_ERR(4, 5, __pyx_L1_error)
+    __Pyx_GOTREF(__pyx_t_1);
     __Pyx_INCREF(__pyx_n_s_PickleError);
     __Pyx_GIVEREF(__pyx_n_s_PickleError);
-    PyList_SET_ITEM(__pyx_t_2, 0, __pyx_n_s_PickleError);
-    __pyx_t_3 = __Pyx_Import(__pyx_n_s_pickle, __pyx_t_2, 0); if (unlikely(!__pyx_t_3)) __PYX_ERR(4, 5, __pyx_L1_error)
-    __Pyx_GOTREF(__pyx_t_3);
-    __Pyx_DECREF(__pyx_t_2); __pyx_t_2 = 0;
-    __pyx_t_2 = __Pyx_ImportFrom(__pyx_t_3, __pyx_n_s_PickleError); if (unlikely(!__pyx_t_2)) __PYX_ERR(4, 5, __pyx_L1_error)
-    __Pyx_GOTREF(__pyx_t_2);
-    __Pyx_INCREF(__pyx_t_2);
-    __pyx_v___pyx_PickleError = __pyx_t_2;
-    __Pyx_DECREF(__pyx_t_2); __pyx_t_2 = 0;
-    __Pyx_DECREF(__pyx_t_3); __pyx_t_3 = 0;
+    PyList_SET_ITEM(__pyx_t_1, 0, __pyx_n_s_PickleError);
+    __pyx_t_4 = __Pyx_Import(__pyx_n_s_pickle, __pyx_t_1, 0); if (unlikely(!__pyx_t_4)) __PYX_ERR(4, 5, __pyx_L1_error)
+    __Pyx_GOTREF(__pyx_t_4);
+    __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
+    __pyx_t_1 = __Pyx_ImportFrom(__pyx_t_4, __pyx_n_s_PickleError); if (unlikely(!__pyx_t_1)) __PYX_ERR(4, 5, __pyx_L1_error)
+    __Pyx_GOTREF(__pyx_t_1);
+    __Pyx_INCREF(__pyx_t_1);
+    __pyx_v___pyx_PickleError = __pyx_t_1;
+    __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
+    __Pyx_DECREF(__pyx_t_4); __pyx_t_4 = 0;
 
     /* "(tree fragment)":6
- *     if __pyx_checksum != 0xd41d8cd:
+ *     if __pyx_checksum not in (0xd41d8cd, 0xe3b0c44, 0xda39a3e):
  *         from pickle import PickleError as __pyx_PickleError
- *         raise __pyx_PickleError("Incompatible checksums (%s vs 0xd41d8cd = ())" % __pyx_checksum)             # <<<<<<<<<<<<<<
+ *         raise __pyx_PickleError("Incompatible checksums (0x%x vs (0xd41d8cd, 0xe3b0c44, 0xda39a3e) = ())" % __pyx_checksum)             # <<<<<<<<<<<<<<
  *     __pyx_result = PY_GCG_PRICINGSTATUS.__new__(__pyx_type)
  *     if __pyx_state is not None:
  */
-    __pyx_t_2 = __Pyx_PyInt_From_long(__pyx_v___pyx_checksum); if (unlikely(!__pyx_t_2)) __PYX_ERR(4, 6, __pyx_L1_error)
-    __Pyx_GOTREF(__pyx_t_2);
-    __pyx_t_4 = __Pyx_PyString_Format(__pyx_kp_s_Incompatible_checksums_s_vs_0xd4, __pyx_t_2); if (unlikely(!__pyx_t_4)) __PYX_ERR(4, 6, __pyx_L1_error)
-    __Pyx_GOTREF(__pyx_t_4);
-    __Pyx_DECREF(__pyx_t_2); __pyx_t_2 = 0;
+    __pyx_t_1 = __Pyx_PyInt_From_long(__pyx_v___pyx_checksum); if (unlikely(!__pyx_t_1)) __PYX_ERR(4, 6, __pyx_L1_error)
+    __Pyx_GOTREF(__pyx_t_1);
+    __pyx_t_5 = __Pyx_PyString_Format(__pyx_kp_s_Incompatible_checksums_0x_x_vs_0_3, __pyx_t_1); if (unlikely(!__pyx_t_5)) __PYX_ERR(4, 6, __pyx_L1_error)
+    __Pyx_GOTREF(__pyx_t_5);
+    __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
     __Pyx_INCREF(__pyx_v___pyx_PickleError);
-    __pyx_t_2 = __pyx_v___pyx_PickleError; __pyx_t_5 = NULL;
-    if (CYTHON_UNPACK_METHODS && unlikely(PyMethod_Check(__pyx_t_2))) {
-      __pyx_t_5 = PyMethod_GET_SELF(__pyx_t_2);
-      if (likely(__pyx_t_5)) {
-        PyObject* function = PyMethod_GET_FUNCTION(__pyx_t_2);
-        __Pyx_INCREF(__pyx_t_5);
+    __pyx_t_1 = __pyx_v___pyx_PickleError; __pyx_t_6 = NULL;
+    if (CYTHON_UNPACK_METHODS && unlikely(PyMethod_Check(__pyx_t_1))) {
+      __pyx_t_6 = PyMethod_GET_SELF(__pyx_t_1);
+      if (likely(__pyx_t_6)) {
+        PyObject* function = PyMethod_GET_FUNCTION(__pyx_t_1);
+        __Pyx_INCREF(__pyx_t_6);
         __Pyx_INCREF(function);
-        __Pyx_DECREF_SET(__pyx_t_2, function);
+        __Pyx_DECREF_SET(__pyx_t_1, function);
       }
     }
-    __pyx_t_3 = (__pyx_t_5) ? __Pyx_PyObject_Call2Args(__pyx_t_2, __pyx_t_5, __pyx_t_4) : __Pyx_PyObject_CallOneArg(__pyx_t_2, __pyx_t_4);
-    __Pyx_XDECREF(__pyx_t_5); __pyx_t_5 = 0;
+    __pyx_t_4 = (__pyx_t_6) ? __Pyx_PyObject_Call2Args(__pyx_t_1, __pyx_t_6, __pyx_t_5) : __Pyx_PyObject_CallOneArg(__pyx_t_1, __pyx_t_5);
+    __Pyx_XDECREF(__pyx_t_6); __pyx_t_6 = 0;
+    __Pyx_DECREF(__pyx_t_5); __pyx_t_5 = 0;
+    if (unlikely(!__pyx_t_4)) __PYX_ERR(4, 6, __pyx_L1_error)
+    __Pyx_GOTREF(__pyx_t_4);
+    __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
+    __Pyx_Raise(__pyx_t_4, 0, 0, 0);
     __Pyx_DECREF(__pyx_t_4); __pyx_t_4 = 0;
-    if (unlikely(!__pyx_t_3)) __PYX_ERR(4, 6, __pyx_L1_error)
-    __Pyx_GOTREF(__pyx_t_3);
-    __Pyx_DECREF(__pyx_t_2); __pyx_t_2 = 0;
-    __Pyx_Raise(__pyx_t_3, 0, 0, 0);
-    __Pyx_DECREF(__pyx_t_3); __pyx_t_3 = 0;
     __PYX_ERR(4, 6, __pyx_L1_error)
 
     /* "(tree fragment)":4
  *     cdef object __pyx_PickleError
  *     cdef object __pyx_result
- *     if __pyx_checksum != 0xd41d8cd:             # <<<<<<<<<<<<<<
+ *     if __pyx_checksum not in (0xd41d8cd, 0xe3b0c44, 0xda39a3e):             # <<<<<<<<<<<<<<
  *         from pickle import PickleError as __pyx_PickleError
- *         raise __pyx_PickleError("Incompatible checksums (%s vs 0xd41d8cd = ())" % __pyx_checksum)
+ *         raise __pyx_PickleError("Incompatible checksums (0x%x vs (0xd41d8cd, 0xe3b0c44, 0xda39a3e) = ())" % __pyx_checksum)
  */
   }
 
   /* "(tree fragment)":7
  *         from pickle import PickleError as __pyx_PickleError
- *         raise __pyx_PickleError("Incompatible checksums (%s vs 0xd41d8cd = ())" % __pyx_checksum)
+ *         raise __pyx_PickleError("Incompatible checksums (0x%x vs (0xd41d8cd, 0xe3b0c44, 0xda39a3e) = ())" % __pyx_checksum)
  *     __pyx_result = PY_GCG_PRICINGSTATUS.__new__(__pyx_type)             # <<<<<<<<<<<<<<
  *     if __pyx_state is not None:
  *         __pyx_unpickle_PY_GCG_PRICINGSTATUS__set_state(<PY_GCG_PRICINGSTATUS> __pyx_result, __pyx_state)
  */
-  __pyx_t_2 = __Pyx_PyObject_GetAttrStr(((PyObject *)__pyx_ptype_8pygcgopt_3gcg_PY_GCG_PRICINGSTATUS), __pyx_n_s_new); if (unlikely(!__pyx_t_2)) __PYX_ERR(4, 7, __pyx_L1_error)
-  __Pyx_GOTREF(__pyx_t_2);
-  __pyx_t_4 = NULL;
-  if (CYTHON_UNPACK_METHODS && likely(PyMethod_Check(__pyx_t_2))) {
-    __pyx_t_4 = PyMethod_GET_SELF(__pyx_t_2);
-    if (likely(__pyx_t_4)) {
-      PyObject* function = PyMethod_GET_FUNCTION(__pyx_t_2);
-      __Pyx_INCREF(__pyx_t_4);
+  __pyx_t_1 = __Pyx_PyObject_GetAttrStr(((PyObject *)__pyx_ptype_8pygcgopt_3gcg_PY_GCG_PRICINGSTATUS), __pyx_n_s_new); if (unlikely(!__pyx_t_1)) __PYX_ERR(4, 7, __pyx_L1_error)
+  __Pyx_GOTREF(__pyx_t_1);
+  __pyx_t_5 = NULL;
+  if (CYTHON_UNPACK_METHODS && likely(PyMethod_Check(__pyx_t_1))) {
+    __pyx_t_5 = PyMethod_GET_SELF(__pyx_t_1);
+    if (likely(__pyx_t_5)) {
+      PyObject* function = PyMethod_GET_FUNCTION(__pyx_t_1);
+      __Pyx_INCREF(__pyx_t_5);
       __Pyx_INCREF(function);
-      __Pyx_DECREF_SET(__pyx_t_2, function);
+      __Pyx_DECREF_SET(__pyx_t_1, function);
     }
   }
-  __pyx_t_3 = (__pyx_t_4) ? __Pyx_PyObject_Call2Args(__pyx_t_2, __pyx_t_4, __pyx_v___pyx_type) : __Pyx_PyObject_CallOneArg(__pyx_t_2, __pyx_v___pyx_type);
-  __Pyx_XDECREF(__pyx_t_4); __pyx_t_4 = 0;
-  if (unlikely(!__pyx_t_3)) __PYX_ERR(4, 7, __pyx_L1_error)
-  __Pyx_GOTREF(__pyx_t_3);
-  __Pyx_DECREF(__pyx_t_2); __pyx_t_2 = 0;
-  __pyx_v___pyx_result = __pyx_t_3;
-  __pyx_t_3 = 0;
+  __pyx_t_4 = (__pyx_t_5) ? __Pyx_PyObject_Call2Args(__pyx_t_1, __pyx_t_5, __pyx_v___pyx_type) : __Pyx_PyObject_CallOneArg(__pyx_t_1, __pyx_v___pyx_type);
+  __Pyx_XDECREF(__pyx_t_5); __pyx_t_5 = 0;
+  if (unlikely(!__pyx_t_4)) __PYX_ERR(4, 7, __pyx_L1_error)
+  __Pyx_GOTREF(__pyx_t_4);
+  __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
+  __pyx_v___pyx_result = __pyx_t_4;
+  __pyx_t_4 = 0;
 
   /* "(tree fragment)":8
- *         raise __pyx_PickleError("Incompatible checksums (%s vs 0xd41d8cd = ())" % __pyx_checksum)
+ *         raise __pyx_PickleError("Incompatible checksums (0x%x vs (0xd41d8cd, 0xe3b0c44, 0xda39a3e) = ())" % __pyx_checksum)
  *     __pyx_result = PY_GCG_PRICINGSTATUS.__new__(__pyx_type)
  *     if __pyx_state is not None:             # <<<<<<<<<<<<<<
  *         __pyx_unpickle_PY_GCG_PRICINGSTATUS__set_state(<PY_GCG_PRICINGSTATUS> __pyx_result, __pyx_state)
  *     return __pyx_result
  */
-  __pyx_t_1 = (__pyx_v___pyx_state != Py_None);
-  __pyx_t_6 = (__pyx_t_1 != 0);
-  if (__pyx_t_6) {
+  __pyx_t_3 = (__pyx_v___pyx_state != Py_None);
+  __pyx_t_2 = (__pyx_t_3 != 0);
+  if (__pyx_t_2) {
 
     /* "(tree fragment)":9
  *     __pyx_result = PY_GCG_PRICINGSTATUS.__new__(__pyx_type)
  *     if __pyx_state is not None:
  *         __pyx_unpickle_PY_GCG_PRICINGSTATUS__set_state(<PY_GCG_PRICINGSTATUS> __pyx_result, __pyx_state)             # <<<<<<<<<<<<<<
  *     return __pyx_result
  * cdef __pyx_unpickle_PY_GCG_PRICINGSTATUS__set_state(PY_GCG_PRICINGSTATUS __pyx_result, tuple __pyx_state):
  */
-    if (!(likely(PyTuple_CheckExact(__pyx_v___pyx_state))||((__pyx_v___pyx_state) == Py_None)||(PyErr_Format(PyExc_TypeError, "Expected %.16s, got %.200s", "tuple", Py_TYPE(__pyx_v___pyx_state)->tp_name), 0))) __PYX_ERR(4, 9, __pyx_L1_error)
-    __pyx_t_3 = __pyx_f_8pygcgopt_3gcg___pyx_unpickle_PY_GCG_PRICINGSTATUS__set_state(((struct __pyx_obj_8pygcgopt_3gcg_PY_GCG_PRICINGSTATUS *)__pyx_v___pyx_result), ((PyObject*)__pyx_v___pyx_state)); if (unlikely(!__pyx_t_3)) __PYX_ERR(4, 9, __pyx_L1_error)
-    __Pyx_GOTREF(__pyx_t_3);
-    __Pyx_DECREF(__pyx_t_3); __pyx_t_3 = 0;
+    if (!(likely(PyTuple_CheckExact(__pyx_v___pyx_state))||((__pyx_v___pyx_state) == Py_None)||((void)PyErr_Format(PyExc_TypeError, "Expected %.16s, got %.200s", "tuple", Py_TYPE(__pyx_v___pyx_state)->tp_name), 0))) __PYX_ERR(4, 9, __pyx_L1_error)
+    __pyx_t_4 = __pyx_f_8pygcgopt_3gcg___pyx_unpickle_PY_GCG_PRICINGSTATUS__set_state(((struct __pyx_obj_8pygcgopt_3gcg_PY_GCG_PRICINGSTATUS *)__pyx_v___pyx_result), ((PyObject*)__pyx_v___pyx_state)); if (unlikely(!__pyx_t_4)) __PYX_ERR(4, 9, __pyx_L1_error)
+    __Pyx_GOTREF(__pyx_t_4);
+    __Pyx_DECREF(__pyx_t_4); __pyx_t_4 = 0;
 
     /* "(tree fragment)":8
- *         raise __pyx_PickleError("Incompatible checksums (%s vs 0xd41d8cd = ())" % __pyx_checksum)
+ *         raise __pyx_PickleError("Incompatible checksums (0x%x vs (0xd41d8cd, 0xe3b0c44, 0xda39a3e) = ())" % __pyx_checksum)
  *     __pyx_result = PY_GCG_PRICINGSTATUS.__new__(__pyx_type)
  *     if __pyx_state is not None:             # <<<<<<<<<<<<<<
  *         __pyx_unpickle_PY_GCG_PRICINGSTATUS__set_state(<PY_GCG_PRICINGSTATUS> __pyx_result, __pyx_state)
  *     return __pyx_result
  */
   }
 
@@ -44800,18 +45174,18 @@
  * def __pyx_unpickle_PY_GCG_PRICINGSTATUS(__pyx_type, long __pyx_checksum, __pyx_state):             # <<<<<<<<<<<<<<
  *     cdef object __pyx_PickleError
  *     cdef object __pyx_result
  */
 
   /* function exit code */
   __pyx_L1_error:;
-  __Pyx_XDECREF(__pyx_t_2);
-  __Pyx_XDECREF(__pyx_t_3);
+  __Pyx_XDECREF(__pyx_t_1);
   __Pyx_XDECREF(__pyx_t_4);
   __Pyx_XDECREF(__pyx_t_5);
+  __Pyx_XDECREF(__pyx_t_6);
   __Pyx_AddTraceback("pygcgopt.gcg.__pyx_unpickle_PY_GCG_PRICINGSTATUS", __pyx_clineno, __pyx_lineno, __pyx_filename);
   __pyx_r = NULL;
   __pyx_L0:;
   __Pyx_XDECREF(__pyx_v___pyx_PickleError);
   __Pyx_XDECREF(__pyx_v___pyx_result);
   __Pyx_XGIVEREF(__pyx_r);
   __Pyx_RefNannyFinishContext();
@@ -46150,20 +46524,23 @@
   0, /*tp_subclasses*/
   0, /*tp_weaklist*/
   0, /*tp_del*/
   0, /*tp_version_tag*/
   #if PY_VERSION_HEX >= 0x030400a1
   0, /*tp_finalize*/
   #endif
-  #if PY_VERSION_HEX >= 0x030800b1
+  #if PY_VERSION_HEX >= 0x030800b1 && (!CYTHON_COMPILING_IN_PYPY || PYPY_VERSION_NUM >= 0x07030800)
   0, /*tp_vectorcall*/
   #endif
   #if PY_VERSION_HEX >= 0x030800b4 && PY_VERSION_HEX < 0x03090000
   0, /*tp_print*/
   #endif
+  #if CYTHON_COMPILING_IN_PYPY && PY_VERSION_HEX >= 0x03090000 && PY_VERSION_HEX < 0x030a0000
+  0, /*tp_pypy_flags*/
+  #endif
 };
 
 static PyObject *__pyx_tp_new_8pygcgopt_3gcg_Detector(PyTypeObject *t, CYTHON_UNUSED PyObject *a, CYTHON_UNUSED PyObject *k) {
   struct __pyx_obj_8pygcgopt_3gcg_Detector *p;
   PyObject *o;
   if (likely((t->tp_flags & Py_TPFLAGS_IS_ABSTRACT) == 0)) {
     o = (*t->tp_alloc)(t, 0);
@@ -46312,20 +46689,23 @@
   0, /*tp_subclasses*/
   0, /*tp_weaklist*/
   0, /*tp_del*/
   0, /*tp_version_tag*/
   #if PY_VERSION_HEX >= 0x030400a1
   0, /*tp_finalize*/
   #endif
-  #if PY_VERSION_HEX >= 0x030800b1
+  #if PY_VERSION_HEX >= 0x030800b1 && (!CYTHON_COMPILING_IN_PYPY || PYPY_VERSION_NUM >= 0x07030800)
   0, /*tp_vectorcall*/
   #endif
   #if PY_VERSION_HEX >= 0x030800b4 && PY_VERSION_HEX < 0x03090000
   0, /*tp_print*/
   #endif
+  #if CYTHON_COMPILING_IN_PYPY && PY_VERSION_HEX >= 0x03090000 && PY_VERSION_HEX < 0x030a0000
+  0, /*tp_pypy_flags*/
+  #endif
 };
 
 static PyObject *__pyx_tp_new_8pygcgopt_3gcg_PricingSolver(PyTypeObject *t, CYTHON_UNUSED PyObject *a, CYTHON_UNUSED PyObject *k) {
   struct __pyx_obj_8pygcgopt_3gcg_PricingSolver *p;
   PyObject *o;
   if (likely((t->tp_flags & Py_TPFLAGS_IS_ABSTRACT) == 0)) {
     o = (*t->tp_alloc)(t, 0);
@@ -46473,20 +46853,23 @@
   0, /*tp_subclasses*/
   0, /*tp_weaklist*/
   0, /*tp_del*/
   0, /*tp_version_tag*/
   #if PY_VERSION_HEX >= 0x030400a1
   0, /*tp_finalize*/
   #endif
-  #if PY_VERSION_HEX >= 0x030800b1
+  #if PY_VERSION_HEX >= 0x030800b1 && (!CYTHON_COMPILING_IN_PYPY || PYPY_VERSION_NUM >= 0x07030800)
   0, /*tp_vectorcall*/
   #endif
   #if PY_VERSION_HEX >= 0x030800b4 && PY_VERSION_HEX < 0x03090000
   0, /*tp_print*/
   #endif
+  #if CYTHON_COMPILING_IN_PYPY && PY_VERSION_HEX >= 0x03090000 && PY_VERSION_HEX < 0x030a0000
+  0, /*tp_pypy_flags*/
+  #endif
 };
 static struct __pyx_vtabstruct_8pygcgopt_3gcg_ConsPart __pyx_vtable_8pygcgopt_3gcg_ConsPart;
 
 static PyObject *__pyx_tp_new_8pygcgopt_3gcg_ConsPart(PyTypeObject *t, CYTHON_UNUSED PyObject *a, CYTHON_UNUSED PyObject *k) {
   struct __pyx_obj_8pygcgopt_3gcg_ConsPart *p;
   PyObject *o;
   if (likely((t->tp_flags & Py_TPFLAGS_IS_ABSTRACT) == 0)) {
@@ -46615,20 +46998,23 @@
   0, /*tp_subclasses*/
   0, /*tp_weaklist*/
   0, /*tp_del*/
   0, /*tp_version_tag*/
   #if PY_VERSION_HEX >= 0x030400a1
   0, /*tp_finalize*/
   #endif
-  #if PY_VERSION_HEX >= 0x030800b1
+  #if PY_VERSION_HEX >= 0x030800b1 && (!CYTHON_COMPILING_IN_PYPY || PYPY_VERSION_NUM >= 0x07030800)
   0, /*tp_vectorcall*/
   #endif
   #if PY_VERSION_HEX >= 0x030800b4 && PY_VERSION_HEX < 0x03090000
   0, /*tp_print*/
   #endif
+  #if CYTHON_COMPILING_IN_PYPY && PY_VERSION_HEX >= 0x03090000 && PY_VERSION_HEX < 0x030a0000
+  0, /*tp_pypy_flags*/
+  #endif
 };
 static struct __pyx_vtabstruct_8pygcgopt_3gcg_VarPart __pyx_vtable_8pygcgopt_3gcg_VarPart;
 
 static PyObject *__pyx_tp_new_8pygcgopt_3gcg_VarPart(PyTypeObject *t, CYTHON_UNUSED PyObject *a, CYTHON_UNUSED PyObject *k) {
   struct __pyx_obj_8pygcgopt_3gcg_VarPart *p;
   PyObject *o;
   if (likely((t->tp_flags & Py_TPFLAGS_IS_ABSTRACT) == 0)) {
@@ -46734,20 +47120,23 @@
   0, /*tp_subclasses*/
   0, /*tp_weaklist*/
   0, /*tp_del*/
   0, /*tp_version_tag*/
   #if PY_VERSION_HEX >= 0x030400a1
   0, /*tp_finalize*/
   #endif
-  #if PY_VERSION_HEX >= 0x030800b1
+  #if PY_VERSION_HEX >= 0x030800b1 && (!CYTHON_COMPILING_IN_PYPY || PYPY_VERSION_NUM >= 0x07030800)
   0, /*tp_vectorcall*/
   #endif
   #if PY_VERSION_HEX >= 0x030800b4 && PY_VERSION_HEX < 0x03090000
   0, /*tp_print*/
   #endif
+  #if CYTHON_COMPILING_IN_PYPY && PY_VERSION_HEX >= 0x03090000 && PY_VERSION_HEX < 0x030a0000
+  0, /*tp_pypy_flags*/
+  #endif
 };
 static struct __pyx_vtabstruct_8pygcgopt_3gcg_PartialDecomposition __pyx_vtable_8pygcgopt_3gcg_PartialDecomposition;
 
 static PyObject *__pyx_tp_new_8pygcgopt_3gcg_PartialDecomposition(PyTypeObject *t, CYTHON_UNUSED PyObject *a, CYTHON_UNUSED PyObject *k) {
   struct __pyx_obj_8pygcgopt_3gcg_PartialDecomposition *p;
   PyObject *o;
   if (likely((t->tp_flags & Py_TPFLAGS_IS_ABSTRACT) == 0)) {
@@ -47244,20 +47633,23 @@
   0, /*tp_subclasses*/
   0, /*tp_weaklist*/
   0, /*tp_del*/
   0, /*tp_version_tag*/
   #if PY_VERSION_HEX >= 0x030400a1
   0, /*tp_finalize*/
   #endif
-  #if PY_VERSION_HEX >= 0x030800b1
+  #if PY_VERSION_HEX >= 0x030800b1 && (!CYTHON_COMPILING_IN_PYPY || PYPY_VERSION_NUM >= 0x07030800)
   0, /*tp_vectorcall*/
   #endif
   #if PY_VERSION_HEX >= 0x030800b4 && PY_VERSION_HEX < 0x03090000
   0, /*tp_print*/
   #endif
+  #if CYTHON_COMPILING_IN_PYPY && PY_VERSION_HEX >= 0x03090000 && PY_VERSION_HEX < 0x030a0000
+  0, /*tp_pypy_flags*/
+  #endif
 };
 static struct __pyx_vtabstruct_8pygcgopt_3gcg_DetProbData __pyx_vtable_8pygcgopt_3gcg_DetProbData;
 
 static PyObject *__pyx_tp_new_8pygcgopt_3gcg_DetProbData(PyTypeObject *t, CYTHON_UNUSED PyObject *a, CYTHON_UNUSED PyObject *k) {
   struct __pyx_obj_8pygcgopt_3gcg_DetProbData *p;
   PyObject *o;
   if (likely((t->tp_flags & Py_TPFLAGS_IS_ABSTRACT) == 0)) {
@@ -47519,20 +47911,23 @@
   0, /*tp_subclasses*/
   0, /*tp_weaklist*/
   0, /*tp_del*/
   0, /*tp_version_tag*/
   #if PY_VERSION_HEX >= 0x030400a1
   0, /*tp_finalize*/
   #endif
-  #if PY_VERSION_HEX >= 0x030800b1
+  #if PY_VERSION_HEX >= 0x030800b1 && (!CYTHON_COMPILING_IN_PYPY || PYPY_VERSION_NUM >= 0x07030800)
   0, /*tp_vectorcall*/
   #endif
   #if PY_VERSION_HEX >= 0x030800b4 && PY_VERSION_HEX < 0x03090000
   0, /*tp_print*/
   #endif
+  #if CYTHON_COMPILING_IN_PYPY && PY_VERSION_HEX >= 0x03090000 && PY_VERSION_HEX < 0x030a0000
+  0, /*tp_pypy_flags*/
+  #endif
 };
 
 static PyObject *__pyx_tp_new_8pygcgopt_3gcg_PY_GCG_PRICINGSTATUS(PyTypeObject *t, CYTHON_UNUSED PyObject *a, CYTHON_UNUSED PyObject *k) {
   PyObject *o;
   if (likely((t->tp_flags & Py_TPFLAGS_IS_ABSTRACT) == 0)) {
     o = (*t->tp_alloc)(t, 0);
   } else {
@@ -47614,20 +48009,23 @@
   0, /*tp_subclasses*/
   0, /*tp_weaklist*/
   0, /*tp_del*/
   0, /*tp_version_tag*/
   #if PY_VERSION_HEX >= 0x030400a1
   0, /*tp_finalize*/
   #endif
-  #if PY_VERSION_HEX >= 0x030800b1
+  #if PY_VERSION_HEX >= 0x030800b1 && (!CYTHON_COMPILING_IN_PYPY || PYPY_VERSION_NUM >= 0x07030800)
   0, /*tp_vectorcall*/
   #endif
   #if PY_VERSION_HEX >= 0x030800b4 && PY_VERSION_HEX < 0x03090000
   0, /*tp_print*/
   #endif
+  #if CYTHON_COMPILING_IN_PYPY && PY_VERSION_HEX >= 0x03090000 && PY_VERSION_HEX < 0x030a0000
+  0, /*tp_pypy_flags*/
+  #endif
 };
 static struct __pyx_vtabstruct_8pygcgopt_3gcg_Model __pyx_vtable_8pygcgopt_3gcg_Model;
 
 static PyObject *__pyx_tp_new_8pygcgopt_3gcg_Model(PyTypeObject *t, PyObject *a, PyObject *k) {
   struct __pyx_obj_8pygcgopt_3gcg_Model *p;
   PyObject *o = __pyx_ptype_9pyscipopt_4scip_Model->tp_new(t, a, k);
   if (unlikely(!o)) return 0;
@@ -47682,16 +48080,17 @@
   {"listDetectors", (PyCFunction)__pyx_pw_8pygcgopt_3gcg_5Model_41listDetectors, METH_NOARGS, __pyx_doc_8pygcgopt_3gcg_5Model_40listDetectors},
   {"setDetectorEnabled", (PyCFunction)(void*)(PyCFunctionWithKeywords)__pyx_pw_8pygcgopt_3gcg_5Model_43setDetectorEnabled, METH_VARARGS|METH_KEYWORDS, __pyx_doc_8pygcgopt_3gcg_5Model_42setDetectorEnabled},
   {"setDetectorFinishingEnabled", (PyCFunction)(void*)(PyCFunctionWithKeywords)__pyx_pw_8pygcgopt_3gcg_5Model_45setDetectorFinishingEnabled, METH_VARARGS|METH_KEYWORDS, __pyx_doc_8pygcgopt_3gcg_5Model_44setDetectorFinishingEnabled},
   {"setDetectorPostprocessingEnabled", (PyCFunction)(void*)(PyCFunctionWithKeywords)__pyx_pw_8pygcgopt_3gcg_5Model_47setDetectorPostprocessingEnabled, METH_VARARGS|METH_KEYWORDS, __pyx_doc_8pygcgopt_3gcg_5Model_46setDetectorPostprocessingEnabled},
   {"getMasterProb", (PyCFunction)__pyx_pw_8pygcgopt_3gcg_5Model_49getMasterProb, METH_NOARGS, __pyx_doc_8pygcgopt_3gcg_5Model_48getMasterProb},
   {"setGCGSeparating", (PyCFunction)__pyx_pw_8pygcgopt_3gcg_5Model_51setGCGSeparating, METH_O, __pyx_doc_8pygcgopt_3gcg_5Model_50setGCGSeparating},
   {"writeAllDecomps", (PyCFunction)(void*)(PyCFunctionWithKeywords)__pyx_pw_8pygcgopt_3gcg_5Model_53writeAllDecomps, METH_VARARGS|METH_KEYWORDS, __pyx_doc_8pygcgopt_3gcg_5Model_52writeAllDecomps},
-  {"__reduce_cython__", (PyCFunction)__pyx_pw_8pygcgopt_3gcg_5Model_55__reduce_cython__, METH_NOARGS, __pyx_doc_8pygcgopt_3gcg_5Model_54__reduce_cython__},
-  {"__setstate_cython__", (PyCFunction)__pyx_pw_8pygcgopt_3gcg_5Model_57__setstate_cython__, METH_O, __pyx_doc_8pygcgopt_3gcg_5Model_56__setstate_cython__},
+  {"getMastervars", (PyCFunction)__pyx_pw_8pygcgopt_3gcg_5Model_55getMastervars, METH_O, __pyx_doc_8pygcgopt_3gcg_5Model_54getMastervars},
+  {"__reduce_cython__", (PyCFunction)__pyx_pw_8pygcgopt_3gcg_5Model_57__reduce_cython__, METH_NOARGS, __pyx_doc_8pygcgopt_3gcg_5Model_56__reduce_cython__},
+  {"__setstate_cython__", (PyCFunction)__pyx_pw_8pygcgopt_3gcg_5Model_59__setstate_cython__, METH_O, __pyx_doc_8pygcgopt_3gcg_5Model_58__setstate_cython__},
   {0, 0, 0, 0}
 };
 
 static PyTypeObject __pyx_type_8pygcgopt_3gcg_Model = {
   PyVarObject_HEAD_INIT(0, 0)
   "pygcgopt.gcg.Model", /*tp_name*/
   sizeof(struct __pyx_obj_8pygcgopt_3gcg_Model), /*tp_basicsize*/
@@ -47748,20 +48147,23 @@
   0, /*tp_subclasses*/
   0, /*tp_weaklist*/
   0, /*tp_del*/
   0, /*tp_version_tag*/
   #if PY_VERSION_HEX >= 0x030400a1
   0, /*tp_finalize*/
   #endif
-  #if PY_VERSION_HEX >= 0x030800b1
+  #if PY_VERSION_HEX >= 0x030800b1 && (!CYTHON_COMPILING_IN_PYPY || PYPY_VERSION_NUM >= 0x07030800)
   0, /*tp_vectorcall*/
   #endif
   #if PY_VERSION_HEX >= 0x030800b4 && PY_VERSION_HEX < 0x03090000
   0, /*tp_print*/
   #endif
+  #if CYTHON_COMPILING_IN_PYPY && PY_VERSION_HEX >= 0x03090000 && PY_VERSION_HEX < 0x030a0000
+  0, /*tp_pypy_flags*/
+  #endif
 };
 static struct __pyx_vtabstruct_8pygcgopt_3gcg_GCGPricingModel __pyx_vtable_8pygcgopt_3gcg_GCGPricingModel;
 
 static PyObject *__pyx_tp_new_8pygcgopt_3gcg_GCGPricingModel(PyTypeObject *t, PyObject *a, PyObject *k) {
   struct __pyx_obj_8pygcgopt_3gcg_GCGPricingModel *p;
   PyObject *o = __pyx_ptype_9pyscipopt_4scip_Model->tp_new(t, a, k);
   if (unlikely(!o)) return 0;
@@ -47856,20 +48258,23 @@
   0, /*tp_subclasses*/
   0, /*tp_weaklist*/
   0, /*tp_del*/
   0, /*tp_version_tag*/
   #if PY_VERSION_HEX >= 0x030400a1
   0, /*tp_finalize*/
   #endif
-  #if PY_VERSION_HEX >= 0x030800b1
+  #if PY_VERSION_HEX >= 0x030800b1 && (!CYTHON_COMPILING_IN_PYPY || PYPY_VERSION_NUM >= 0x07030800)
   0, /*tp_vectorcall*/
   #endif
   #if PY_VERSION_HEX >= 0x030800b4 && PY_VERSION_HEX < 0x03090000
   0, /*tp_print*/
   #endif
+  #if CYTHON_COMPILING_IN_PYPY && PY_VERSION_HEX >= 0x03090000 && PY_VERSION_HEX < 0x030a0000
+  0, /*tp_pypy_flags*/
+  #endif
 };
 static struct __pyx_vtabstruct_8pygcgopt_3gcg_GCGMasterModel __pyx_vtable_8pygcgopt_3gcg_GCGMasterModel;
 
 static PyObject *__pyx_tp_new_8pygcgopt_3gcg_GCGMasterModel(PyTypeObject *t, PyObject *a, PyObject *k) {
   struct __pyx_obj_8pygcgopt_3gcg_GCGMasterModel *p;
   PyObject *o = __pyx_ptype_9pyscipopt_4scip_Model->tp_new(t, a, k);
   if (unlikely(!o)) return 0;
@@ -47898,16 +48303,17 @@
 static int __pyx_tp_clear_8pygcgopt_3gcg_GCGMasterModel(PyObject *o) {
   if (likely(__pyx_ptype_9pyscipopt_4scip_Model)) { if (__pyx_ptype_9pyscipopt_4scip_Model->tp_clear) __pyx_ptype_9pyscipopt_4scip_Model->tp_clear(o); } else __Pyx_call_next_tp_clear(o, __pyx_tp_clear_8pygcgopt_3gcg_GCGMasterModel);
   return 0;
 }
 
 static PyMethodDef __pyx_methods_8pygcgopt_3gcg_GCGMasterModel[] = {
   {"addCol", (PyCFunction)__pyx_pw_8pygcgopt_3gcg_14GCGMasterModel_1addCol, METH_O, __pyx_doc_8pygcgopt_3gcg_14GCGMasterModel_addCol},
-  {"__reduce_cython__", (PyCFunction)__pyx_pw_8pygcgopt_3gcg_14GCGMasterModel_3__reduce_cython__, METH_NOARGS, __pyx_doc_8pygcgopt_3gcg_14GCGMasterModel_2__reduce_cython__},
-  {"__setstate_cython__", (PyCFunction)__pyx_pw_8pygcgopt_3gcg_14GCGMasterModel_5__setstate_cython__, METH_O, __pyx_doc_8pygcgopt_3gcg_14GCGMasterModel_4__setstate_cython__},
+  {"getOrigvars", (PyCFunction)__pyx_pw_8pygcgopt_3gcg_14GCGMasterModel_3getOrigvars, METH_O, __pyx_doc_8pygcgopt_3gcg_14GCGMasterModel_2getOrigvars},
+  {"__reduce_cython__", (PyCFunction)__pyx_pw_8pygcgopt_3gcg_14GCGMasterModel_5__reduce_cython__, METH_NOARGS, __pyx_doc_8pygcgopt_3gcg_14GCGMasterModel_4__reduce_cython__},
+  {"__setstate_cython__", (PyCFunction)__pyx_pw_8pygcgopt_3gcg_14GCGMasterModel_7__setstate_cython__, METH_O, __pyx_doc_8pygcgopt_3gcg_14GCGMasterModel_6__setstate_cython__},
   {0, 0, 0, 0}
 };
 
 static PyTypeObject __pyx_type_8pygcgopt_3gcg_GCGMasterModel = {
   PyVarObject_HEAD_INIT(0, 0)
   "pygcgopt.gcg.GCGMasterModel", /*tp_name*/
   sizeof(struct __pyx_obj_8pygcgopt_3gcg_GCGMasterModel), /*tp_basicsize*/
@@ -47964,20 +48370,23 @@
   0, /*tp_subclasses*/
   0, /*tp_weaklist*/
   0, /*tp_del*/
   0, /*tp_version_tag*/
   #if PY_VERSION_HEX >= 0x030400a1
   0, /*tp_finalize*/
   #endif
-  #if PY_VERSION_HEX >= 0x030800b1
+  #if PY_VERSION_HEX >= 0x030800b1 && (!CYTHON_COMPILING_IN_PYPY || PYPY_VERSION_NUM >= 0x07030800)
   0, /*tp_vectorcall*/
   #endif
   #if PY_VERSION_HEX >= 0x030800b4 && PY_VERSION_HEX < 0x03090000
   0, /*tp_print*/
   #endif
+  #if CYTHON_COMPILING_IN_PYPY && PY_VERSION_HEX >= 0x03090000 && PY_VERSION_HEX < 0x030a0000
+  0, /*tp_pypy_flags*/
+  #endif
 };
 
 static PyMethodDef __pyx_methods[] = {
   {0, 0, 0, 0}
 };
 
 #if PY_MAJOR_VERSION >= 3
@@ -48029,17 +48438,17 @@
   {&__pyx_kp_u_Detector_callback_returned_of_ty, __pyx_k_Detector_callback_returned_of_ty, sizeof(__pyx_k_Detector_callback_returned_of_ty), 0, 1, 0, 0},
   {&__pyx_kp_u_Expected_iterable_as_first_argum, __pyx_k_Expected_iterable_as_first_argum, sizeof(__pyx_k_Expected_iterable_as_first_argum), 0, 1, 0, 0},
   {&__pyx_kp_u_Format, __pyx_k_Format, sizeof(__pyx_k_Format), 0, 1, 0, 0},
   {&__pyx_n_s_GCGColumn, __pyx_k_GCGColumn, sizeof(__pyx_k_GCGColumn), 0, 0, 1, 1},
   {&__pyx_n_s_GCGMasterModel, __pyx_k_GCGMasterModel, sizeof(__pyx_k_GCGMasterModel), 0, 0, 1, 1},
   {&__pyx_n_s_GCGPricingModel, __pyx_k_GCGPricingModel, sizeof(__pyx_k_GCGPricingModel), 0, 0, 1, 1},
   {&__pyx_n_s_INFEASIBLE, __pyx_k_INFEASIBLE, sizeof(__pyx_k_INFEASIBLE), 0, 0, 1, 1},
-  {&__pyx_kp_s_Incompatible_checksums_s_vs_0x7a, __pyx_k_Incompatible_checksums_s_vs_0x7a, sizeof(__pyx_k_Incompatible_checksums_s_vs_0x7a), 0, 0, 1, 0},
-  {&__pyx_kp_s_Incompatible_checksums_s_vs_0xd4, __pyx_k_Incompatible_checksums_s_vs_0xd4, sizeof(__pyx_k_Incompatible_checksums_s_vs_0xd4), 0, 0, 1, 0},
-  {&__pyx_kp_s_Incompatible_checksums_s_vs_0xf7, __pyx_k_Incompatible_checksums_s_vs_0xf7, sizeof(__pyx_k_Incompatible_checksums_s_vs_0xf7), 0, 0, 1, 0},
+  {&__pyx_kp_s_Incompatible_checksums_0x_x_vs_0, __pyx_k_Incompatible_checksums_0x_x_vs_0, sizeof(__pyx_k_Incompatible_checksums_0x_x_vs_0), 0, 0, 1, 0},
+  {&__pyx_kp_s_Incompatible_checksums_0x_x_vs_0_2, __pyx_k_Incompatible_checksums_0x_x_vs_0_2, sizeof(__pyx_k_Incompatible_checksums_0x_x_vs_0_2), 0, 0, 1, 0},
+  {&__pyx_kp_s_Incompatible_checksums_0x_x_vs_0_3, __pyx_k_Incompatible_checksums_0x_x_vs_0_3, sizeof(__pyx_k_Incompatible_checksums_0x_x_vs_0_3), 0, 0, 1, 0},
   {&__pyx_n_s_Iterable, __pyx_k_Iterable, sizeof(__pyx_k_Iterable), 0, 0, 1, 1},
   {&__pyx_kp_u_Length_of_value_for_decchar_must, __pyx_k_Length_of_value_for_decchar_must, sizeof(__pyx_k_Length_of_value_for_decchar_must), 0, 1, 0, 0},
   {&__pyx_n_s_List, __pyx_k_List, sizeof(__pyx_k_List), 0, 0, 1, 1},
   {&__pyx_n_s_Model, __pyx_k_Model, sizeof(__pyx_k_Model), 0, 0, 1, 1},
   {&__pyx_n_s_NOTAPPLICABLE, __pyx_k_NOTAPPLICABLE, sizeof(__pyx_k_NOTAPPLICABLE), 0, 0, 1, 1},
   {&__pyx_n_s_NotImplementedError, __pyx_k_NotImplementedError, sizeof(__pyx_k_NotImplementedError), 0, 0, 1, 1},
   {&__pyx_n_s_OPTIMAL, __pyx_k_OPTIMAL, sizeof(__pyx_k_OPTIMAL), 0, 0, 1, 1},
@@ -48459,22 +48868,22 @@
  * def __setstate_cython__(self, __pyx_state):
  *     raise TypeError("self._scip,self._valid cannot be converted to a Python object for pickling")             # <<<<<<<<<<<<<<
  */
   __pyx_tuple__22 = PyTuple_Pack(1, __pyx_kp_s_self__scip_self__valid_cannot_be); if (unlikely(!__pyx_tuple__22)) __PYX_ERR(4, 4, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_tuple__22);
   __Pyx_GIVEREF(__pyx_tuple__22);
 
-  /* "pygcgopt/gcg.pyx":358
+  /* "pygcgopt/gcg.pyx":368
  *         """
  *         if scip == NULL:
  *             raise Warning("cannot create Model with SCIP* == NULL")             # <<<<<<<<<<<<<<
  *         model = GCGPricingModel(createscip=False)
  *         model._scip = scip
  */
-  __pyx_tuple__23 = PyTuple_Pack(1, __pyx_kp_u_cannot_create_Model_with_SCIP_NU); if (unlikely(!__pyx_tuple__23)) __PYX_ERR(3, 358, __pyx_L1_error)
+  __pyx_tuple__23 = PyTuple_Pack(1, __pyx_kp_u_cannot_create_Model_with_SCIP_NU); if (unlikely(!__pyx_tuple__23)) __PYX_ERR(3, 368, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_tuple__23);
   __Pyx_GIVEREF(__pyx_tuple__23);
 
   /* "(tree fragment)":2
  * def __reduce_cython__(self):
  *     raise TypeError("self._scip,self._valid cannot be converted to a Python object for pickling")             # <<<<<<<<<<<<<<
  * def __setstate_cython__(self, __pyx_state):
@@ -48508,22 +48917,22 @@
  * def __setstate_cython__(self, __pyx_state):
  *     raise TypeError("self._scip,self._valid cannot be converted to a Python object for pickling")             # <<<<<<<<<<<<<<
  */
   __pyx_tuple__27 = PyTuple_Pack(1, __pyx_kp_s_self__scip_self__valid_cannot_be); if (unlikely(!__pyx_tuple__27)) __PYX_ERR(4, 4, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_tuple__27);
   __Pyx_GIVEREF(__pyx_tuple__27);
 
-  /* "pygcgopt/gcg.pyx":414
+  /* "pygcgopt/gcg.pyx":434
  *     cdef create(GCG_COL* gcgcol):
  *         if gcgcol == NULL:
  *             raise Warning("cannot create Column with GCG_COL* == NULL")             # <<<<<<<<<<<<<<
  *         col = GCGColumn()
  *         col.gcg_col = gcgcol
  */
-  __pyx_tuple__28 = PyTuple_Pack(1, __pyx_kp_u_cannot_create_Column_with_GCG_CO); if (unlikely(!__pyx_tuple__28)) __PYX_ERR(3, 414, __pyx_L1_error)
+  __pyx_tuple__28 = PyTuple_Pack(1, __pyx_kp_u_cannot_create_Column_with_GCG_CO); if (unlikely(!__pyx_tuple__28)) __PYX_ERR(3, 434, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_tuple__28);
   __Pyx_GIVEREF(__pyx_tuple__28);
 
   /* "(tree fragment)":2
  * def __reduce_cython__(self):
  *     raise TypeError("self.gcg_col cannot be converted to a Python object for pickling")             # <<<<<<<<<<<<<<
  * def __setstate_cython__(self, __pyx_state):
@@ -48537,45 +48946,60 @@
  *     raise TypeError("self.gcg_col cannot be converted to a Python object for pickling")
  * def __setstate_cython__(self, __pyx_state):
  *     raise TypeError("self.gcg_col cannot be converted to a Python object for pickling")             # <<<<<<<<<<<<<<
  */
   __pyx_tuple__30 = PyTuple_Pack(1, __pyx_kp_s_self_gcg_col_cannot_be_converted); if (unlikely(!__pyx_tuple__30)) __PYX_ERR(4, 4, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_tuple__30);
   __Pyx_GIVEREF(__pyx_tuple__30);
+  __pyx_tuple__31 = PyTuple_Pack(3, __pyx_int_260020090, __pyx_int_229442799, __pyx_int_108959872); if (unlikely(!__pyx_tuple__31)) __PYX_ERR(4, 4, __pyx_L1_error)
+  __Pyx_GOTREF(__pyx_tuple__31);
+  __Pyx_GIVEREF(__pyx_tuple__31);
+  __pyx_tuple__32 = PyTuple_Pack(3, __pyx_int_128380825, __pyx_int_160002037, __pyx_int_141772857); if (unlikely(!__pyx_tuple__32)) __PYX_ERR(4, 4, __pyx_L1_error)
+  __Pyx_GOTREF(__pyx_tuple__32);
+  __Pyx_GIVEREF(__pyx_tuple__32);
+  __pyx_tuple__33 = PyTuple_Pack(3, __pyx_int_222419149, __pyx_int_238750788, __pyx_int_228825662); if (unlikely(!__pyx_tuple__33)) __PYX_ERR(4, 4, __pyx_L1_error)
+  __Pyx_GOTREF(__pyx_tuple__33);
+  __Pyx_GIVEREF(__pyx_tuple__33);
 
   /* "(tree fragment)":1
  * def __pyx_unpickle_Detector(__pyx_type, long __pyx_checksum, __pyx_state):             # <<<<<<<<<<<<<<
  *     cdef object __pyx_PickleError
  *     cdef object __pyx_result
  */
-  __pyx_tuple__31 = PyTuple_Pack(5, __pyx_n_s_pyx_type, __pyx_n_s_pyx_checksum, __pyx_n_s_pyx_state, __pyx_n_s_pyx_PickleError, __pyx_n_s_pyx_result); if (unlikely(!__pyx_tuple__31)) __PYX_ERR(4, 1, __pyx_L1_error)
-  __Pyx_GOTREF(__pyx_tuple__31);
-  __Pyx_GIVEREF(__pyx_tuple__31);
-  __pyx_codeobj__32 = (PyObject*)__Pyx_PyCode_New(3, 0, 5, 0, CO_OPTIMIZED|CO_NEWLOCALS, __pyx_empty_bytes, __pyx_empty_tuple, __pyx_empty_tuple, __pyx_tuple__31, __pyx_empty_tuple, __pyx_empty_tuple, __pyx_kp_s_stringsource, __pyx_n_s_pyx_unpickle_Detector, 1, __pyx_empty_bytes); if (unlikely(!__pyx_codeobj__32)) __PYX_ERR(4, 1, __pyx_L1_error)
-  __pyx_tuple__33 = PyTuple_Pack(5, __pyx_n_s_pyx_type, __pyx_n_s_pyx_checksum, __pyx_n_s_pyx_state, __pyx_n_s_pyx_PickleError, __pyx_n_s_pyx_result); if (unlikely(!__pyx_tuple__33)) __PYX_ERR(4, 1, __pyx_L1_error)
-  __Pyx_GOTREF(__pyx_tuple__33);
-  __Pyx_GIVEREF(__pyx_tuple__33);
-  __pyx_codeobj__34 = (PyObject*)__Pyx_PyCode_New(3, 0, 5, 0, CO_OPTIMIZED|CO_NEWLOCALS, __pyx_empty_bytes, __pyx_empty_tuple, __pyx_empty_tuple, __pyx_tuple__33, __pyx_empty_tuple, __pyx_empty_tuple, __pyx_kp_s_stringsource, __pyx_n_s_pyx_unpickle_PricingSolver, 1, __pyx_empty_bytes); if (unlikely(!__pyx_codeobj__34)) __PYX_ERR(4, 1, __pyx_L1_error)
-  __pyx_tuple__35 = PyTuple_Pack(5, __pyx_n_s_pyx_type, __pyx_n_s_pyx_checksum, __pyx_n_s_pyx_state, __pyx_n_s_pyx_PickleError, __pyx_n_s_pyx_result); if (unlikely(!__pyx_tuple__35)) __PYX_ERR(4, 1, __pyx_L1_error)
-  __Pyx_GOTREF(__pyx_tuple__35);
-  __Pyx_GIVEREF(__pyx_tuple__35);
-  __pyx_codeobj__36 = (PyObject*)__Pyx_PyCode_New(3, 0, 5, 0, CO_OPTIMIZED|CO_NEWLOCALS, __pyx_empty_bytes, __pyx_empty_tuple, __pyx_empty_tuple, __pyx_tuple__35, __pyx_empty_tuple, __pyx_empty_tuple, __pyx_kp_s_stringsource, __pyx_n_s_pyx_unpickle_PY_GCG_PRICINGSTA, 1, __pyx_empty_bytes); if (unlikely(!__pyx_codeobj__36)) __PYX_ERR(4, 1, __pyx_L1_error)
+  __pyx_tuple__34 = PyTuple_Pack(5, __pyx_n_s_pyx_type, __pyx_n_s_pyx_checksum, __pyx_n_s_pyx_state, __pyx_n_s_pyx_PickleError, __pyx_n_s_pyx_result); if (unlikely(!__pyx_tuple__34)) __PYX_ERR(4, 1, __pyx_L1_error)
+  __Pyx_GOTREF(__pyx_tuple__34);
+  __Pyx_GIVEREF(__pyx_tuple__34);
+  __pyx_codeobj__35 = (PyObject*)__Pyx_PyCode_New(3, 0, 5, 0, CO_OPTIMIZED|CO_NEWLOCALS, __pyx_empty_bytes, __pyx_empty_tuple, __pyx_empty_tuple, __pyx_tuple__34, __pyx_empty_tuple, __pyx_empty_tuple, __pyx_kp_s_stringsource, __pyx_n_s_pyx_unpickle_Detector, 1, __pyx_empty_bytes); if (unlikely(!__pyx_codeobj__35)) __PYX_ERR(4, 1, __pyx_L1_error)
+  __pyx_tuple__36 = PyTuple_Pack(5, __pyx_n_s_pyx_type, __pyx_n_s_pyx_checksum, __pyx_n_s_pyx_state, __pyx_n_s_pyx_PickleError, __pyx_n_s_pyx_result); if (unlikely(!__pyx_tuple__36)) __PYX_ERR(4, 1, __pyx_L1_error)
+  __Pyx_GOTREF(__pyx_tuple__36);
+  __Pyx_GIVEREF(__pyx_tuple__36);
+  __pyx_codeobj__37 = (PyObject*)__Pyx_PyCode_New(3, 0, 5, 0, CO_OPTIMIZED|CO_NEWLOCALS, __pyx_empty_bytes, __pyx_empty_tuple, __pyx_empty_tuple, __pyx_tuple__36, __pyx_empty_tuple, __pyx_empty_tuple, __pyx_kp_s_stringsource, __pyx_n_s_pyx_unpickle_PricingSolver, 1, __pyx_empty_bytes); if (unlikely(!__pyx_codeobj__37)) __PYX_ERR(4, 1, __pyx_L1_error)
+  __pyx_tuple__38 = PyTuple_Pack(5, __pyx_n_s_pyx_type, __pyx_n_s_pyx_checksum, __pyx_n_s_pyx_state, __pyx_n_s_pyx_PickleError, __pyx_n_s_pyx_result); if (unlikely(!__pyx_tuple__38)) __PYX_ERR(4, 1, __pyx_L1_error)
+  __Pyx_GOTREF(__pyx_tuple__38);
+  __Pyx_GIVEREF(__pyx_tuple__38);
+  __pyx_codeobj__39 = (PyObject*)__Pyx_PyCode_New(3, 0, 5, 0, CO_OPTIMIZED|CO_NEWLOCALS, __pyx_empty_bytes, __pyx_empty_tuple, __pyx_empty_tuple, __pyx_tuple__38, __pyx_empty_tuple, __pyx_empty_tuple, __pyx_kp_s_stringsource, __pyx_n_s_pyx_unpickle_PY_GCG_PRICINGSTA, 1, __pyx_empty_bytes); if (unlikely(!__pyx_codeobj__39)) __PYX_ERR(4, 1, __pyx_L1_error)
   __Pyx_RefNannyFinishContext();
   return 0;
   __pyx_L1_error:;
   __Pyx_RefNannyFinishContext();
   return -1;
 }
 
 static CYTHON_SMALL_CODE int __Pyx_InitGlobals(void) {
-  if (__Pyx_InitStrings(__pyx_string_tab) < 0) __PYX_ERR(3, 1, __pyx_L1_error);
+  if (__Pyx_InitStrings(__pyx_string_tab) < 0) __PYX_ERR(3, 1, __pyx_L1_error)
   __pyx_int_0 = PyInt_FromLong(0); if (unlikely(!__pyx_int_0)) __PYX_ERR(3, 1, __pyx_L1_error)
   __pyx_int_1 = PyInt_FromLong(1); if (unlikely(!__pyx_int_1)) __PYX_ERR(3, 1, __pyx_L1_error)
+  __pyx_int_108959872 = PyInt_FromLong(108959872L); if (unlikely(!__pyx_int_108959872)) __PYX_ERR(3, 1, __pyx_L1_error)
   __pyx_int_128380825 = PyInt_FromLong(128380825L); if (unlikely(!__pyx_int_128380825)) __PYX_ERR(3, 1, __pyx_L1_error)
+  __pyx_int_141772857 = PyInt_FromLong(141772857L); if (unlikely(!__pyx_int_141772857)) __PYX_ERR(3, 1, __pyx_L1_error)
+  __pyx_int_160002037 = PyInt_FromLong(160002037L); if (unlikely(!__pyx_int_160002037)) __PYX_ERR(3, 1, __pyx_L1_error)
   __pyx_int_222419149 = PyInt_FromLong(222419149L); if (unlikely(!__pyx_int_222419149)) __PYX_ERR(3, 1, __pyx_L1_error)
+  __pyx_int_228825662 = PyInt_FromLong(228825662L); if (unlikely(!__pyx_int_228825662)) __PYX_ERR(3, 1, __pyx_L1_error)
+  __pyx_int_229442799 = PyInt_FromLong(229442799L); if (unlikely(!__pyx_int_229442799)) __PYX_ERR(3, 1, __pyx_L1_error)
+  __pyx_int_238750788 = PyInt_FromLong(238750788L); if (unlikely(!__pyx_int_238750788)) __PYX_ERR(3, 1, __pyx_L1_error)
   __pyx_int_260020090 = PyInt_FromLong(260020090L); if (unlikely(!__pyx_int_260020090)) __PYX_ERR(3, 1, __pyx_L1_error)
   return 0;
   __pyx_L1_error:;
   return -1;
 }
 
 static CYTHON_SMALL_CODE int __Pyx_modinit_global_init_code(void); /*proto*/
@@ -48616,24 +49040,24 @@
   int __pyx_lineno = 0;
   const char *__pyx_filename = NULL;
   int __pyx_clineno = 0;
   __Pyx_RefNannySetupContext("__Pyx_modinit_type_init_code", 0);
   /*--- Type init code ---*/
   __pyx_vtabptr_8pygcgopt_3gcg_GCGColumn = &__pyx_vtable_8pygcgopt_3gcg_GCGColumn;
   __pyx_vtable_8pygcgopt_3gcg_GCGColumn.create = (PyObject *(*)(GCG_COL *))__pyx_f_8pygcgopt_3gcg_9GCGColumn_create;
-  if (PyType_Ready(&__pyx_type_8pygcgopt_3gcg_GCGColumn) < 0) __PYX_ERR(3, 408, __pyx_L1_error)
+  if (PyType_Ready(&__pyx_type_8pygcgopt_3gcg_GCGColumn) < 0) __PYX_ERR(3, 428, __pyx_L1_error)
   #if PY_VERSION_HEX < 0x030800B1
   __pyx_type_8pygcgopt_3gcg_GCGColumn.tp_print = 0;
   #endif
   if ((CYTHON_USE_TYPE_SLOTS && CYTHON_USE_PYTYPE_LOOKUP) && likely(!__pyx_type_8pygcgopt_3gcg_GCGColumn.tp_dictoffset && __pyx_type_8pygcgopt_3gcg_GCGColumn.tp_getattro == PyObject_GenericGetAttr)) {
     __pyx_type_8pygcgopt_3gcg_GCGColumn.tp_getattro = __Pyx_PyObject_GenericGetAttr;
   }
-  if (__Pyx_SetVtable(__pyx_type_8pygcgopt_3gcg_GCGColumn.tp_dict, __pyx_vtabptr_8pygcgopt_3gcg_GCGColumn) < 0) __PYX_ERR(3, 408, __pyx_L1_error)
-  if (PyObject_SetAttr(__pyx_m, __pyx_n_s_GCGColumn, (PyObject *)&__pyx_type_8pygcgopt_3gcg_GCGColumn) < 0) __PYX_ERR(3, 408, __pyx_L1_error)
-  if (__Pyx_setup_reduce((PyObject*)&__pyx_type_8pygcgopt_3gcg_GCGColumn) < 0) __PYX_ERR(3, 408, __pyx_L1_error)
+  if (__Pyx_SetVtable(__pyx_type_8pygcgopt_3gcg_GCGColumn.tp_dict, __pyx_vtabptr_8pygcgopt_3gcg_GCGColumn) < 0) __PYX_ERR(3, 428, __pyx_L1_error)
+  if (PyObject_SetAttr(__pyx_m, __pyx_n_s_GCGColumn, (PyObject *)&__pyx_type_8pygcgopt_3gcg_GCGColumn) < 0) __PYX_ERR(3, 428, __pyx_L1_error)
+  if (__Pyx_setup_reduce((PyObject*)&__pyx_type_8pygcgopt_3gcg_GCGColumn) < 0) __PYX_ERR(3, 428, __pyx_L1_error)
   __pyx_ptype_8pygcgopt_3gcg_GCGColumn = &__pyx_type_8pygcgopt_3gcg_GCGColumn;
   if (PyType_Ready(&__pyx_type_8pygcgopt_3gcg_Detector) < 0) __PYX_ERR(0, 1, __pyx_L1_error)
   #if PY_VERSION_HEX < 0x030800B1
   __pyx_type_8pygcgopt_3gcg_Detector.tp_print = 0;
   #endif
   if ((CYTHON_USE_TYPE_SLOTS && CYTHON_USE_PYTYPE_LOOKUP) && likely(!__pyx_type_8pygcgopt_3gcg_Detector.tp_dictoffset && __pyx_type_8pygcgopt_3gcg_Detector.tp_getattro == PyObject_GenericGetAttr)) {
     __pyx_type_8pygcgopt_3gcg_Detector.tp_getattro = __Pyx_PyObject_GenericGetAttr;
@@ -48713,16 +49137,15 @@
     __pyx_type_8pygcgopt_3gcg_PY_GCG_PRICINGSTATUS.tp_getattro = __Pyx_PyObject_GenericGetAttr;
   }
   if (PyObject_SetAttr(__pyx_m, __pyx_n_s_PY_GCG_PRICINGSTATUS, (PyObject *)&__pyx_type_8pygcgopt_3gcg_PY_GCG_PRICINGSTATUS) < 0) __PYX_ERR(3, 45, __pyx_L1_error)
   if (__Pyx_setup_reduce((PyObject*)&__pyx_type_8pygcgopt_3gcg_PY_GCG_PRICINGSTATUS) < 0) __PYX_ERR(3, 45, __pyx_L1_error)
   __pyx_ptype_8pygcgopt_3gcg_PY_GCG_PRICINGSTATUS = &__pyx_type_8pygcgopt_3gcg_PY_GCG_PRICINGSTATUS;
   __pyx_t_1 = PyImport_ImportModule("pyscipopt.scip"); if (unlikely(!__pyx_t_1)) __PYX_ERR(3, 1, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_1);
-  __pyx_ptype_9pyscipopt_4scip_Model = __Pyx_ImportType(__pyx_t_1, "pyscipopt.scip", "Model", sizeof(struct __pyx_obj_9pyscipopt_4scip_Model), __Pyx_ImportType_CheckSize_Warn);
-   if (!__pyx_ptype_9pyscipopt_4scip_Model) __PYX_ERR(3, 1, __pyx_L1_error)
+  __pyx_ptype_9pyscipopt_4scip_Model = __Pyx_ImportType_0_29_35(__pyx_t_1, "pyscipopt.scip", "Model", sizeof(struct __pyx_obj_9pyscipopt_4scip_Model), __PYX_GET_STRUCT_ALIGNMENT_0_29_35(struct __pyx_obj_9pyscipopt_4scip_Model),__Pyx_ImportType_CheckSize_Warn_0_29_35); if (!__pyx_ptype_9pyscipopt_4scip_Model) __PYX_ERR(3, 1, __pyx_L1_error)
   __pyx_vtabptr_9pyscipopt_4scip_Model = (struct __pyx_vtabstruct_9pyscipopt_4scip_Model*)__Pyx_GetVtable(__pyx_ptype_9pyscipopt_4scip_Model->tp_dict); if (unlikely(!__pyx_vtabptr_9pyscipopt_4scip_Model)) __PYX_ERR(3, 1, __pyx_L1_error)
   __pyx_vtabptr_8pygcgopt_3gcg_Model = &__pyx_vtable_8pygcgopt_3gcg_Model;
   __pyx_vtable_8pygcgopt_3gcg_Model.__pyx_base = *__pyx_vtabptr_9pyscipopt_4scip_Model;
   __pyx_type_8pygcgopt_3gcg_Model.tp_base = __pyx_ptype_9pyscipopt_4scip_Model;
   if (PyType_Ready(&__pyx_type_8pygcgopt_3gcg_Model) < 0) __PYX_ERR(3, 54, __pyx_L1_error)
   #if PY_VERSION_HEX < 0x030800B1
   __pyx_type_8pygcgopt_3gcg_Model.tp_print = 0;
@@ -48735,41 +49158,41 @@
   if (__pyx_type_8pygcgopt_3gcg_Model.tp_weaklistoffset == 0) __pyx_type_8pygcgopt_3gcg_Model.tp_weaklistoffset = offsetof(struct __pyx_obj_8pygcgopt_3gcg_Model, __pyx_base.__weakref__);
   if (__Pyx_setup_reduce((PyObject*)&__pyx_type_8pygcgopt_3gcg_Model) < 0) __PYX_ERR(3, 54, __pyx_L1_error)
   __pyx_ptype_8pygcgopt_3gcg_Model = &__pyx_type_8pygcgopt_3gcg_Model;
   __pyx_vtabptr_8pygcgopt_3gcg_GCGPricingModel = &__pyx_vtable_8pygcgopt_3gcg_GCGPricingModel;
   __pyx_vtable_8pygcgopt_3gcg_GCGPricingModel.__pyx_base = *__pyx_vtabptr_9pyscipopt_4scip_Model;
   __pyx_vtable_8pygcgopt_3gcg_GCGPricingModel.__pyx_base.create = (PyObject *(*)(SCIP *))__pyx_f_8pygcgopt_3gcg_15GCGPricingModel_create;
   __pyx_type_8pygcgopt_3gcg_GCGPricingModel.tp_base = __pyx_ptype_9pyscipopt_4scip_Model;
-  if (PyType_Ready(&__pyx_type_8pygcgopt_3gcg_GCGPricingModel) < 0) __PYX_ERR(3, 352, __pyx_L1_error)
+  if (PyType_Ready(&__pyx_type_8pygcgopt_3gcg_GCGPricingModel) < 0) __PYX_ERR(3, 362, __pyx_L1_error)
   #if PY_VERSION_HEX < 0x030800B1
   __pyx_type_8pygcgopt_3gcg_GCGPricingModel.tp_print = 0;
   #endif
   if ((CYTHON_USE_TYPE_SLOTS && CYTHON_USE_PYTYPE_LOOKUP) && likely(!__pyx_type_8pygcgopt_3gcg_GCGPricingModel.tp_dictoffset && __pyx_type_8pygcgopt_3gcg_GCGPricingModel.tp_getattro == PyObject_GenericGetAttr)) {
     __pyx_type_8pygcgopt_3gcg_GCGPricingModel.tp_getattro = __Pyx_PyObject_GenericGetAttr;
   }
-  if (__Pyx_SetVtable(__pyx_type_8pygcgopt_3gcg_GCGPricingModel.tp_dict, __pyx_vtabptr_8pygcgopt_3gcg_GCGPricingModel) < 0) __PYX_ERR(3, 352, __pyx_L1_error)
-  if (PyObject_SetAttr(__pyx_m, __pyx_n_s_GCGPricingModel, (PyObject *)&__pyx_type_8pygcgopt_3gcg_GCGPricingModel) < 0) __PYX_ERR(3, 352, __pyx_L1_error)
+  if (__Pyx_SetVtable(__pyx_type_8pygcgopt_3gcg_GCGPricingModel.tp_dict, __pyx_vtabptr_8pygcgopt_3gcg_GCGPricingModel) < 0) __PYX_ERR(3, 362, __pyx_L1_error)
+  if (PyObject_SetAttr(__pyx_m, __pyx_n_s_GCGPricingModel, (PyObject *)&__pyx_type_8pygcgopt_3gcg_GCGPricingModel) < 0) __PYX_ERR(3, 362, __pyx_L1_error)
   if (__pyx_type_8pygcgopt_3gcg_GCGPricingModel.tp_weaklistoffset == 0) __pyx_type_8pygcgopt_3gcg_GCGPricingModel.tp_weaklistoffset = offsetof(struct __pyx_obj_8pygcgopt_3gcg_GCGPricingModel, __pyx_base.__weakref__);
-  if (__Pyx_setup_reduce((PyObject*)&__pyx_type_8pygcgopt_3gcg_GCGPricingModel) < 0) __PYX_ERR(3, 352, __pyx_L1_error)
+  if (__Pyx_setup_reduce((PyObject*)&__pyx_type_8pygcgopt_3gcg_GCGPricingModel) < 0) __PYX_ERR(3, 362, __pyx_L1_error)
   __pyx_ptype_8pygcgopt_3gcg_GCGPricingModel = &__pyx_type_8pygcgopt_3gcg_GCGPricingModel;
   __pyx_vtabptr_8pygcgopt_3gcg_GCGMasterModel = &__pyx_vtable_8pygcgopt_3gcg_GCGMasterModel;
   __pyx_vtable_8pygcgopt_3gcg_GCGMasterModel.__pyx_base = *__pyx_vtabptr_9pyscipopt_4scip_Model;
   __pyx_vtable_8pygcgopt_3gcg_GCGMasterModel.__pyx_base.create = (PyObject *(*)(SCIP *))__pyx_f_8pygcgopt_3gcg_14GCGMasterModel_create;
   __pyx_type_8pygcgopt_3gcg_GCGMasterModel.tp_base = __pyx_ptype_9pyscipopt_4scip_Model;
-  if (PyType_Ready(&__pyx_type_8pygcgopt_3gcg_GCGMasterModel) < 0) __PYX_ERR(3, 392, __pyx_L1_error)
+  if (PyType_Ready(&__pyx_type_8pygcgopt_3gcg_GCGMasterModel) < 0) __PYX_ERR(3, 402, __pyx_L1_error)
   #if PY_VERSION_HEX < 0x030800B1
   __pyx_type_8pygcgopt_3gcg_GCGMasterModel.tp_print = 0;
   #endif
   if ((CYTHON_USE_TYPE_SLOTS && CYTHON_USE_PYTYPE_LOOKUP) && likely(!__pyx_type_8pygcgopt_3gcg_GCGMasterModel.tp_dictoffset && __pyx_type_8pygcgopt_3gcg_GCGMasterModel.tp_getattro == PyObject_GenericGetAttr)) {
     __pyx_type_8pygcgopt_3gcg_GCGMasterModel.tp_getattro = __Pyx_PyObject_GenericGetAttr;
   }
-  if (__Pyx_SetVtable(__pyx_type_8pygcgopt_3gcg_GCGMasterModel.tp_dict, __pyx_vtabptr_8pygcgopt_3gcg_GCGMasterModel) < 0) __PYX_ERR(3, 392, __pyx_L1_error)
-  if (PyObject_SetAttr(__pyx_m, __pyx_n_s_GCGMasterModel, (PyObject *)&__pyx_type_8pygcgopt_3gcg_GCGMasterModel) < 0) __PYX_ERR(3, 392, __pyx_L1_error)
+  if (__Pyx_SetVtable(__pyx_type_8pygcgopt_3gcg_GCGMasterModel.tp_dict, __pyx_vtabptr_8pygcgopt_3gcg_GCGMasterModel) < 0) __PYX_ERR(3, 402, __pyx_L1_error)
+  if (PyObject_SetAttr(__pyx_m, __pyx_n_s_GCGMasterModel, (PyObject *)&__pyx_type_8pygcgopt_3gcg_GCGMasterModel) < 0) __PYX_ERR(3, 402, __pyx_L1_error)
   if (__pyx_type_8pygcgopt_3gcg_GCGMasterModel.tp_weaklistoffset == 0) __pyx_type_8pygcgopt_3gcg_GCGMasterModel.tp_weaklistoffset = offsetof(struct __pyx_obj_8pygcgopt_3gcg_GCGMasterModel, __pyx_base.__weakref__);
-  if (__Pyx_setup_reduce((PyObject*)&__pyx_type_8pygcgopt_3gcg_GCGMasterModel) < 0) __PYX_ERR(3, 392, __pyx_L1_error)
+  if (__Pyx_setup_reduce((PyObject*)&__pyx_type_8pygcgopt_3gcg_GCGMasterModel) < 0) __PYX_ERR(3, 402, __pyx_L1_error)
   __pyx_ptype_8pygcgopt_3gcg_GCGMasterModel = &__pyx_type_8pygcgopt_3gcg_GCGMasterModel;
   __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
   __Pyx_RefNannyFinishContext();
   return 0;
   __pyx_L1_error:;
   __Pyx_XDECREF(__pyx_t_1);
   __Pyx_RefNannyFinishContext();
@@ -48780,69 +49203,55 @@
   __Pyx_RefNannyDeclarations
   PyObject *__pyx_t_1 = NULL;
   int __pyx_lineno = 0;
   const char *__pyx_filename = NULL;
   int __pyx_clineno = 0;
   __Pyx_RefNannySetupContext("__Pyx_modinit_type_import_code", 0);
   /*--- Type import code ---*/
-  __pyx_t_1 = PyImport_ImportModule("pyscipopt.scip"); if (unlikely(!__pyx_t_1)) __PYX_ERR(7, 1738, __pyx_L1_error)
+  __pyx_t_1 = PyImport_ImportModule("pyscipopt.scip"); if (unlikely(!__pyx_t_1)) __PYX_ERR(7, 1792, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_1);
-  __pyx_ptype_9pyscipopt_4scip_Expr = __Pyx_ImportType(__pyx_t_1, "pyscipopt.scip", "Expr", sizeof(struct __pyx_obj_9pyscipopt_4scip_Expr), __Pyx_ImportType_CheckSize_Warn);
-   if (!__pyx_ptype_9pyscipopt_4scip_Expr) __PYX_ERR(7, 1738, __pyx_L1_error)
-  __pyx_ptype_9pyscipopt_4scip_Event = __Pyx_ImportType(__pyx_t_1, "pyscipopt.scip", "Event", sizeof(struct __pyx_obj_9pyscipopt_4scip_Event), __Pyx_ImportType_CheckSize_Warn);
-   if (!__pyx_ptype_9pyscipopt_4scip_Event) __PYX_ERR(7, 1741, __pyx_L1_error)
-  __pyx_vtabptr_9pyscipopt_4scip_Event = (struct __pyx_vtabstruct_9pyscipopt_4scip_Event*)__Pyx_GetVtable(__pyx_ptype_9pyscipopt_4scip_Event->tp_dict); if (unlikely(!__pyx_vtabptr_9pyscipopt_4scip_Event)) __PYX_ERR(7, 1741, __pyx_L1_error)
-  __pyx_ptype_9pyscipopt_4scip_Column = __Pyx_ImportType(__pyx_t_1, "pyscipopt.scip", "Column", sizeof(struct __pyx_obj_9pyscipopt_4scip_Column), __Pyx_ImportType_CheckSize_Warn);
-   if (!__pyx_ptype_9pyscipopt_4scip_Column) __PYX_ERR(7, 1748, __pyx_L1_error)
-  __pyx_vtabptr_9pyscipopt_4scip_Column = (struct __pyx_vtabstruct_9pyscipopt_4scip_Column*)__Pyx_GetVtable(__pyx_ptype_9pyscipopt_4scip_Column->tp_dict); if (unlikely(!__pyx_vtabptr_9pyscipopt_4scip_Column)) __PYX_ERR(7, 1748, __pyx_L1_error)
-  __pyx_ptype_9pyscipopt_4scip_Row = __Pyx_ImportType(__pyx_t_1, "pyscipopt.scip", "Row", sizeof(struct __pyx_obj_9pyscipopt_4scip_Row), __Pyx_ImportType_CheckSize_Warn);
-   if (!__pyx_ptype_9pyscipopt_4scip_Row) __PYX_ERR(7, 1756, __pyx_L1_error)
-  __pyx_vtabptr_9pyscipopt_4scip_Row = (struct __pyx_vtabstruct_9pyscipopt_4scip_Row*)__Pyx_GetVtable(__pyx_ptype_9pyscipopt_4scip_Row->tp_dict); if (unlikely(!__pyx_vtabptr_9pyscipopt_4scip_Row)) __PYX_ERR(7, 1756, __pyx_L1_error)
-  __pyx_ptype_9pyscipopt_4scip_NLRow = __Pyx_ImportType(__pyx_t_1, "pyscipopt.scip", "NLRow", sizeof(struct __pyx_obj_9pyscipopt_4scip_NLRow), __Pyx_ImportType_CheckSize_Warn);
-   if (!__pyx_ptype_9pyscipopt_4scip_NLRow) __PYX_ERR(7, 1764, __pyx_L1_error)
-  __pyx_vtabptr_9pyscipopt_4scip_NLRow = (struct __pyx_vtabstruct_9pyscipopt_4scip_NLRow*)__Pyx_GetVtable(__pyx_ptype_9pyscipopt_4scip_NLRow->tp_dict); if (unlikely(!__pyx_vtabptr_9pyscipopt_4scip_NLRow)) __PYX_ERR(7, 1764, __pyx_L1_error)
-  __pyx_ptype_9pyscipopt_4scip_Solution = __Pyx_ImportType(__pyx_t_1, "pyscipopt.scip", "Solution", sizeof(struct __pyx_obj_9pyscipopt_4scip_Solution), __Pyx_ImportType_CheckSize_Warn);
-   if (!__pyx_ptype_9pyscipopt_4scip_Solution) __PYX_ERR(7, 1772, __pyx_L1_error)
-  __pyx_vtabptr_9pyscipopt_4scip_Solution = (struct __pyx_vtabstruct_9pyscipopt_4scip_Solution*)__Pyx_GetVtable(__pyx_ptype_9pyscipopt_4scip_Solution->tp_dict); if (unlikely(!__pyx_vtabptr_9pyscipopt_4scip_Solution)) __PYX_ERR(7, 1772, __pyx_L1_error)
-  __pyx_ptype_9pyscipopt_4scip_DomainChanges = __Pyx_ImportType(__pyx_t_1, "pyscipopt.scip", "DomainChanges", sizeof(struct __pyx_obj_9pyscipopt_4scip_DomainChanges), __Pyx_ImportType_CheckSize_Warn);
-   if (!__pyx_ptype_9pyscipopt_4scip_DomainChanges) __PYX_ERR(7, 1781, __pyx_L1_error)
-  __pyx_vtabptr_9pyscipopt_4scip_DomainChanges = (struct __pyx_vtabstruct_9pyscipopt_4scip_DomainChanges*)__Pyx_GetVtable(__pyx_ptype_9pyscipopt_4scip_DomainChanges->tp_dict); if (unlikely(!__pyx_vtabptr_9pyscipopt_4scip_DomainChanges)) __PYX_ERR(7, 1781, __pyx_L1_error)
-  __pyx_ptype_9pyscipopt_4scip_BoundChange = __Pyx_ImportType(__pyx_t_1, "pyscipopt.scip", "BoundChange", sizeof(struct __pyx_obj_9pyscipopt_4scip_BoundChange), __Pyx_ImportType_CheckSize_Warn);
-   if (!__pyx_ptype_9pyscipopt_4scip_BoundChange) __PYX_ERR(7, 1787, __pyx_L1_error)
-  __pyx_vtabptr_9pyscipopt_4scip_BoundChange = (struct __pyx_vtabstruct_9pyscipopt_4scip_BoundChange*)__Pyx_GetVtable(__pyx_ptype_9pyscipopt_4scip_BoundChange->tp_dict); if (unlikely(!__pyx_vtabptr_9pyscipopt_4scip_BoundChange)) __PYX_ERR(7, 1787, __pyx_L1_error)
-  __pyx_ptype_9pyscipopt_4scip_Node = __Pyx_ImportType(__pyx_t_1, "pyscipopt.scip", "Node", sizeof(struct __pyx_obj_9pyscipopt_4scip_Node), __Pyx_ImportType_CheckSize_Warn);
-   if (!__pyx_ptype_9pyscipopt_4scip_Node) __PYX_ERR(7, 1793, __pyx_L1_error)
-  __pyx_vtabptr_9pyscipopt_4scip_Node = (struct __pyx_vtabstruct_9pyscipopt_4scip_Node*)__Pyx_GetVtable(__pyx_ptype_9pyscipopt_4scip_Node->tp_dict); if (unlikely(!__pyx_vtabptr_9pyscipopt_4scip_Node)) __PYX_ERR(7, 1793, __pyx_L1_error)
-  __pyx_ptype_9pyscipopt_4scip_Variable = __Pyx_ImportType(__pyx_t_1, "pyscipopt.scip", "Variable", sizeof(struct __pyx_obj_9pyscipopt_4scip_Variable), __Pyx_ImportType_CheckSize_Warn);
-   if (!__pyx_ptype_9pyscipopt_4scip_Variable) __PYX_ERR(7, 1801, __pyx_L1_error)
-  __pyx_vtabptr_9pyscipopt_4scip_Variable = (struct __pyx_vtabstruct_9pyscipopt_4scip_Variable*)__Pyx_GetVtable(__pyx_ptype_9pyscipopt_4scip_Variable->tp_dict); if (unlikely(!__pyx_vtabptr_9pyscipopt_4scip_Variable)) __PYX_ERR(7, 1801, __pyx_L1_error)
-  __pyx_ptype_9pyscipopt_4scip_Constraint = __Pyx_ImportType(__pyx_t_1, "pyscipopt.scip", "Constraint", sizeof(struct __pyx_obj_9pyscipopt_4scip_Constraint), __Pyx_ImportType_CheckSize_Warn);
-   if (!__pyx_ptype_9pyscipopt_4scip_Constraint) __PYX_ERR(7, 1809, __pyx_L1_error)
-  __pyx_vtabptr_9pyscipopt_4scip_Constraint = (struct __pyx_vtabstruct_9pyscipopt_4scip_Constraint*)__Pyx_GetVtable(__pyx_ptype_9pyscipopt_4scip_Constraint->tp_dict); if (unlikely(!__pyx_vtabptr_9pyscipopt_4scip_Constraint)) __PYX_ERR(7, 1809, __pyx_L1_error)
+  __pyx_ptype_9pyscipopt_4scip_Expr = __Pyx_ImportType_0_29_35(__pyx_t_1, "pyscipopt.scip", "Expr", sizeof(struct __pyx_obj_9pyscipopt_4scip_Expr), __PYX_GET_STRUCT_ALIGNMENT_0_29_35(struct __pyx_obj_9pyscipopt_4scip_Expr),__Pyx_ImportType_CheckSize_Warn_0_29_35); if (!__pyx_ptype_9pyscipopt_4scip_Expr) __PYX_ERR(7, 1792, __pyx_L1_error)
+  __pyx_ptype_9pyscipopt_4scip_Event = __Pyx_ImportType_0_29_35(__pyx_t_1, "pyscipopt.scip", "Event", sizeof(struct __pyx_obj_9pyscipopt_4scip_Event), __PYX_GET_STRUCT_ALIGNMENT_0_29_35(struct __pyx_obj_9pyscipopt_4scip_Event),__Pyx_ImportType_CheckSize_Warn_0_29_35); if (!__pyx_ptype_9pyscipopt_4scip_Event) __PYX_ERR(7, 1795, __pyx_L1_error)
+  __pyx_vtabptr_9pyscipopt_4scip_Event = (struct __pyx_vtabstruct_9pyscipopt_4scip_Event*)__Pyx_GetVtable(__pyx_ptype_9pyscipopt_4scip_Event->tp_dict); if (unlikely(!__pyx_vtabptr_9pyscipopt_4scip_Event)) __PYX_ERR(7, 1795, __pyx_L1_error)
+  __pyx_ptype_9pyscipopt_4scip_Column = __Pyx_ImportType_0_29_35(__pyx_t_1, "pyscipopt.scip", "Column", sizeof(struct __pyx_obj_9pyscipopt_4scip_Column), __PYX_GET_STRUCT_ALIGNMENT_0_29_35(struct __pyx_obj_9pyscipopt_4scip_Column),__Pyx_ImportType_CheckSize_Warn_0_29_35); if (!__pyx_ptype_9pyscipopt_4scip_Column) __PYX_ERR(7, 1802, __pyx_L1_error)
+  __pyx_vtabptr_9pyscipopt_4scip_Column = (struct __pyx_vtabstruct_9pyscipopt_4scip_Column*)__Pyx_GetVtable(__pyx_ptype_9pyscipopt_4scip_Column->tp_dict); if (unlikely(!__pyx_vtabptr_9pyscipopt_4scip_Column)) __PYX_ERR(7, 1802, __pyx_L1_error)
+  __pyx_ptype_9pyscipopt_4scip_Row = __Pyx_ImportType_0_29_35(__pyx_t_1, "pyscipopt.scip", "Row", sizeof(struct __pyx_obj_9pyscipopt_4scip_Row), __PYX_GET_STRUCT_ALIGNMENT_0_29_35(struct __pyx_obj_9pyscipopt_4scip_Row),__Pyx_ImportType_CheckSize_Warn_0_29_35); if (!__pyx_ptype_9pyscipopt_4scip_Row) __PYX_ERR(7, 1810, __pyx_L1_error)
+  __pyx_vtabptr_9pyscipopt_4scip_Row = (struct __pyx_vtabstruct_9pyscipopt_4scip_Row*)__Pyx_GetVtable(__pyx_ptype_9pyscipopt_4scip_Row->tp_dict); if (unlikely(!__pyx_vtabptr_9pyscipopt_4scip_Row)) __PYX_ERR(7, 1810, __pyx_L1_error)
+  __pyx_ptype_9pyscipopt_4scip_NLRow = __Pyx_ImportType_0_29_35(__pyx_t_1, "pyscipopt.scip", "NLRow", sizeof(struct __pyx_obj_9pyscipopt_4scip_NLRow), __PYX_GET_STRUCT_ALIGNMENT_0_29_35(struct __pyx_obj_9pyscipopt_4scip_NLRow),__Pyx_ImportType_CheckSize_Warn_0_29_35); if (!__pyx_ptype_9pyscipopt_4scip_NLRow) __PYX_ERR(7, 1818, __pyx_L1_error)
+  __pyx_vtabptr_9pyscipopt_4scip_NLRow = (struct __pyx_vtabstruct_9pyscipopt_4scip_NLRow*)__Pyx_GetVtable(__pyx_ptype_9pyscipopt_4scip_NLRow->tp_dict); if (unlikely(!__pyx_vtabptr_9pyscipopt_4scip_NLRow)) __PYX_ERR(7, 1818, __pyx_L1_error)
+  __pyx_ptype_9pyscipopt_4scip_Solution = __Pyx_ImportType_0_29_35(__pyx_t_1, "pyscipopt.scip", "Solution", sizeof(struct __pyx_obj_9pyscipopt_4scip_Solution), __PYX_GET_STRUCT_ALIGNMENT_0_29_35(struct __pyx_obj_9pyscipopt_4scip_Solution),__Pyx_ImportType_CheckSize_Warn_0_29_35); if (!__pyx_ptype_9pyscipopt_4scip_Solution) __PYX_ERR(7, 1826, __pyx_L1_error)
+  __pyx_vtabptr_9pyscipopt_4scip_Solution = (struct __pyx_vtabstruct_9pyscipopt_4scip_Solution*)__Pyx_GetVtable(__pyx_ptype_9pyscipopt_4scip_Solution->tp_dict); if (unlikely(!__pyx_vtabptr_9pyscipopt_4scip_Solution)) __PYX_ERR(7, 1826, __pyx_L1_error)
+  __pyx_ptype_9pyscipopt_4scip_DomainChanges = __Pyx_ImportType_0_29_35(__pyx_t_1, "pyscipopt.scip", "DomainChanges", sizeof(struct __pyx_obj_9pyscipopt_4scip_DomainChanges), __PYX_GET_STRUCT_ALIGNMENT_0_29_35(struct __pyx_obj_9pyscipopt_4scip_DomainChanges),__Pyx_ImportType_CheckSize_Warn_0_29_35); if (!__pyx_ptype_9pyscipopt_4scip_DomainChanges) __PYX_ERR(7, 1835, __pyx_L1_error)
+  __pyx_vtabptr_9pyscipopt_4scip_DomainChanges = (struct __pyx_vtabstruct_9pyscipopt_4scip_DomainChanges*)__Pyx_GetVtable(__pyx_ptype_9pyscipopt_4scip_DomainChanges->tp_dict); if (unlikely(!__pyx_vtabptr_9pyscipopt_4scip_DomainChanges)) __PYX_ERR(7, 1835, __pyx_L1_error)
+  __pyx_ptype_9pyscipopt_4scip_BoundChange = __Pyx_ImportType_0_29_35(__pyx_t_1, "pyscipopt.scip", "BoundChange", sizeof(struct __pyx_obj_9pyscipopt_4scip_BoundChange), __PYX_GET_STRUCT_ALIGNMENT_0_29_35(struct __pyx_obj_9pyscipopt_4scip_BoundChange),__Pyx_ImportType_CheckSize_Warn_0_29_35); if (!__pyx_ptype_9pyscipopt_4scip_BoundChange) __PYX_ERR(7, 1841, __pyx_L1_error)
+  __pyx_vtabptr_9pyscipopt_4scip_BoundChange = (struct __pyx_vtabstruct_9pyscipopt_4scip_BoundChange*)__Pyx_GetVtable(__pyx_ptype_9pyscipopt_4scip_BoundChange->tp_dict); if (unlikely(!__pyx_vtabptr_9pyscipopt_4scip_BoundChange)) __PYX_ERR(7, 1841, __pyx_L1_error)
+  __pyx_ptype_9pyscipopt_4scip_Node = __Pyx_ImportType_0_29_35(__pyx_t_1, "pyscipopt.scip", "Node", sizeof(struct __pyx_obj_9pyscipopt_4scip_Node), __PYX_GET_STRUCT_ALIGNMENT_0_29_35(struct __pyx_obj_9pyscipopt_4scip_Node),__Pyx_ImportType_CheckSize_Warn_0_29_35); if (!__pyx_ptype_9pyscipopt_4scip_Node) __PYX_ERR(7, 1847, __pyx_L1_error)
+  __pyx_vtabptr_9pyscipopt_4scip_Node = (struct __pyx_vtabstruct_9pyscipopt_4scip_Node*)__Pyx_GetVtable(__pyx_ptype_9pyscipopt_4scip_Node->tp_dict); if (unlikely(!__pyx_vtabptr_9pyscipopt_4scip_Node)) __PYX_ERR(7, 1847, __pyx_L1_error)
+  __pyx_ptype_9pyscipopt_4scip_Variable = __Pyx_ImportType_0_29_35(__pyx_t_1, "pyscipopt.scip", "Variable", sizeof(struct __pyx_obj_9pyscipopt_4scip_Variable), __PYX_GET_STRUCT_ALIGNMENT_0_29_35(struct __pyx_obj_9pyscipopt_4scip_Variable),__Pyx_ImportType_CheckSize_Warn_0_29_35); if (!__pyx_ptype_9pyscipopt_4scip_Variable) __PYX_ERR(7, 1855, __pyx_L1_error)
+  __pyx_vtabptr_9pyscipopt_4scip_Variable = (struct __pyx_vtabstruct_9pyscipopt_4scip_Variable*)__Pyx_GetVtable(__pyx_ptype_9pyscipopt_4scip_Variable->tp_dict); if (unlikely(!__pyx_vtabptr_9pyscipopt_4scip_Variable)) __PYX_ERR(7, 1855, __pyx_L1_error)
+  __pyx_ptype_9pyscipopt_4scip_Constraint = __Pyx_ImportType_0_29_35(__pyx_t_1, "pyscipopt.scip", "Constraint", sizeof(struct __pyx_obj_9pyscipopt_4scip_Constraint), __PYX_GET_STRUCT_ALIGNMENT_0_29_35(struct __pyx_obj_9pyscipopt_4scip_Constraint),__Pyx_ImportType_CheckSize_Warn_0_29_35); if (!__pyx_ptype_9pyscipopt_4scip_Constraint) __PYX_ERR(7, 1863, __pyx_L1_error)
+  __pyx_vtabptr_9pyscipopt_4scip_Constraint = (struct __pyx_vtabstruct_9pyscipopt_4scip_Constraint*)__Pyx_GetVtable(__pyx_ptype_9pyscipopt_4scip_Constraint->tp_dict); if (unlikely(!__pyx_vtabptr_9pyscipopt_4scip_Constraint)) __PYX_ERR(7, 1863, __pyx_L1_error)
   __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
   __pyx_t_1 = PyImport_ImportModule(__Pyx_BUILTIN_MODULE_NAME); if (unlikely(!__pyx_t_1)) __PYX_ERR(8, 9, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_1);
-  __pyx_ptype_7cpython_4type_type = __Pyx_ImportType(__pyx_t_1, __Pyx_BUILTIN_MODULE_NAME, "type", 
+  __pyx_ptype_7cpython_4type_type = __Pyx_ImportType_0_29_35(__pyx_t_1, __Pyx_BUILTIN_MODULE_NAME, "type", 
   #if defined(PYPY_VERSION_NUM) && PYPY_VERSION_NUM < 0x050B0000
-  sizeof(PyTypeObject),
+  sizeof(PyTypeObject), __PYX_GET_STRUCT_ALIGNMENT_0_29_35(PyTypeObject),
   #else
-  sizeof(PyHeapTypeObject),
+  sizeof(PyHeapTypeObject), __PYX_GET_STRUCT_ALIGNMENT_0_29_35(PyHeapTypeObject),
   #endif
-  __Pyx_ImportType_CheckSize_Warn);
-   if (!__pyx_ptype_7cpython_4type_type) __PYX_ERR(8, 9, __pyx_L1_error)
+  __Pyx_ImportType_CheckSize_Warn_0_29_35); if (!__pyx_ptype_7cpython_4type_type) __PYX_ERR(8, 9, __pyx_L1_error)
   __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
   __pyx_t_1 = PyImport_ImportModule(__Pyx_BUILTIN_MODULE_NAME); if (unlikely(!__pyx_t_1)) __PYX_ERR(9, 8, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_1);
-  __pyx_ptype_7cpython_4bool_bool = __Pyx_ImportType(__pyx_t_1, __Pyx_BUILTIN_MODULE_NAME, "bool", sizeof(PyBoolObject), __Pyx_ImportType_CheckSize_Warn);
-   if (!__pyx_ptype_7cpython_4bool_bool) __PYX_ERR(9, 8, __pyx_L1_error)
+  __pyx_ptype_7cpython_4bool_bool = __Pyx_ImportType_0_29_35(__pyx_t_1, __Pyx_BUILTIN_MODULE_NAME, "bool", sizeof(PyBoolObject), __PYX_GET_STRUCT_ALIGNMENT_0_29_35(PyBoolObject),__Pyx_ImportType_CheckSize_Warn_0_29_35); if (!__pyx_ptype_7cpython_4bool_bool) __PYX_ERR(9, 8, __pyx_L1_error)
   __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
   __pyx_t_1 = PyImport_ImportModule(__Pyx_BUILTIN_MODULE_NAME); if (unlikely(!__pyx_t_1)) __PYX_ERR(10, 15, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_1);
-  __pyx_ptype_7cpython_7complex_complex = __Pyx_ImportType(__pyx_t_1, __Pyx_BUILTIN_MODULE_NAME, "complex", sizeof(PyComplexObject), __Pyx_ImportType_CheckSize_Warn);
-   if (!__pyx_ptype_7cpython_7complex_complex) __PYX_ERR(10, 15, __pyx_L1_error)
+  __pyx_ptype_7cpython_7complex_complex = __Pyx_ImportType_0_29_35(__pyx_t_1, __Pyx_BUILTIN_MODULE_NAME, "complex", sizeof(PyComplexObject), __PYX_GET_STRUCT_ALIGNMENT_0_29_35(PyComplexObject),__Pyx_ImportType_CheckSize_Warn_0_29_35); if (!__pyx_ptype_7cpython_7complex_complex) __PYX_ERR(10, 15, __pyx_L1_error)
   __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
   __Pyx_RefNannyFinishContext();
   return 0;
   __pyx_L1_error:;
   __Pyx_XDECREF(__pyx_t_1);
   __Pyx_RefNannyFinishContext();
   return -1;
@@ -49027,15 +49436,15 @@
   #endif
   __pyx_d = PyModule_GetDict(__pyx_m); if (unlikely(!__pyx_d)) __PYX_ERR(3, 1, __pyx_L1_error)
   Py_INCREF(__pyx_d);
   __pyx_b = PyImport_AddModule(__Pyx_BUILTIN_MODULE_NAME); if (unlikely(!__pyx_b)) __PYX_ERR(3, 1, __pyx_L1_error)
   Py_INCREF(__pyx_b);
   __pyx_cython_runtime = PyImport_AddModule((char *) "cython_runtime"); if (unlikely(!__pyx_cython_runtime)) __PYX_ERR(3, 1, __pyx_L1_error)
   Py_INCREF(__pyx_cython_runtime);
-  if (PyObject_SetAttrString(__pyx_m, "__builtins__", __pyx_b) < 0) __PYX_ERR(3, 1, __pyx_L1_error);
+  if (PyObject_SetAttrString(__pyx_m, "__builtins__", __pyx_b) < 0) __PYX_ERR(3, 1, __pyx_L1_error)
   /*--- Initialize various global constants etc. ---*/
   if (__Pyx_InitGlobals() < 0) __PYX_ERR(3, 1, __pyx_L1_error)
   #if PY_MAJOR_VERSION < 3 && (__PYX_DEFAULT_STRING_ENCODING_IS_ASCII || __PYX_DEFAULT_STRING_ENCODING_IS_DEFAULT)
   if (__Pyx_init_sys_getdefaultencoding_params() < 0) __PYX_ERR(3, 1, __pyx_L1_error)
   #endif
   if (__pyx_module_is_main_pygcgopt__gcg) {
     if (PyObject_SetAttr(__pyx_m, __pyx_n_s_name, __pyx_n_s_main) < 0) __PYX_ERR(3, 1, __pyx_L1_error)
@@ -50089,28 +50498,28 @@
                             "BaseException");
             goto bad;
         }
         PyException_SetCause(value, fixed_cause);
     }
     PyErr_SetObject(type, value);
     if (tb) {
-#if CYTHON_COMPILING_IN_PYPY
-        PyObject *tmp_type, *tmp_value, *tmp_tb;
-        PyErr_Fetch(&tmp_type, &tmp_value, &tmp_tb);
-        Py_INCREF(tb);
-        PyErr_Restore(tmp_type, tmp_value, tb);
-        Py_XDECREF(tmp_tb);
-#else
+#if CYTHON_FAST_THREAD_STATE
         PyThreadState *tstate = __Pyx_PyThreadState_Current;
         PyObject* tmp_tb = tstate->curexc_traceback;
         if (tb != tmp_tb) {
             Py_INCREF(tb);
             tstate->curexc_traceback = tb;
             Py_XDECREF(tmp_tb);
         }
+#else
+        PyObject *tmp_type, *tmp_value, *tmp_tb;
+        PyErr_Fetch(&tmp_type, &tmp_value, &tmp_tb);
+        Py_INCREF(tb);
+        PyErr_Restore(tmp_type, tmp_value, tb);
+        Py_XDECREF(tmp_tb);
 #endif
     }
 bad:
     Py_XDECREF(owned_instance);
     return;
 }
 #endif
@@ -50201,15 +50610,15 @@
 #endif
     return __Pyx_GetItemInt_Generic(o, PyInt_FromSsize_t(i));
 }
 
 /* ObjectGetItem */
 #if CYTHON_USE_TYPE_SLOTS
 static PyObject *__Pyx_PyObject_GetIndex(PyObject *obj, PyObject* index) {
-    PyObject *runerr;
+    PyObject *runerr = NULL;
     Py_ssize_t key_value;
     PySequenceMethods *m = Py_TYPE(obj)->tp_as_sequence;
     if (unlikely(!(m && m->sq_item))) {
         PyErr_Format(PyExc_TypeError, "'%.200s' object is not subscriptable", Py_TYPE(obj)->tp_name);
         return NULL;
     }
     key_value = __Pyx_PyIndex_AsSsize_t(index);
@@ -50235,15 +50644,15 @@
 #if CYTHON_COMPILING_IN_CPYTHON
 static CYTHON_INLINE PyObject* __Pyx_PyObject_CallNoArg(PyObject *func) {
 #if CYTHON_FAST_PYCALL
     if (PyFunction_Check(func)) {
         return __Pyx_PyFunction_FastCall(func, NULL, 0);
     }
 #endif
-#ifdef __Pyx_CyFunction_USED
+#if defined(__Pyx_CyFunction_USED) && defined(NDEBUG)
     if (likely(PyCFunction_Check(func) || __Pyx_CyFunction_Check(func)))
 #else
     if (likely(PyCFunction_Check(func)))
 #endif
     {
         if (likely(PyCFunction_GET_FLAGS(func) & METH_NOARGS)) {
             return __Pyx_PyObject_CallMethO(func, NULL);
@@ -50289,17 +50698,15 @@
     PyObject *old_exc, *old_val, *old_tb;
     PyObject *ctx;
     __Pyx_PyThreadState_declare
 #ifdef WITH_THREAD
     PyGILState_STATE state;
     if (nogil)
         state = PyGILState_Ensure();
-#ifdef _MSC_VER
-    else state = (PyGILState_STATE)-1;
-#endif
+    else state = (PyGILState_STATE)0;
 #endif
     __Pyx_PyThreadState_assign
     __Pyx_ErrFetch(&old_exc, &old_val, &old_tb);
     if (full_traceback) {
         Py_XINCREF(old_exc);
         Py_XINCREF(old_val);
         Py_XINCREF(old_tb);
@@ -50514,15 +50921,15 @@
         ps2 = PyBytes_AS_STRING(s2);
         if (ps1[0] != ps2[0]) {
             return (equals == Py_NE);
         } else if (length == 1) {
             return (equals == Py_EQ);
         } else {
             int result;
-#if CYTHON_USE_UNICODE_INTERNALS
+#if CYTHON_USE_UNICODE_INTERNALS && (PY_VERSION_HEX < 0x030B0000)
             Py_hash_t hash1, hash2;
             hash1 = ((PyBytesObject*)s1)->ob_shash;
             hash2 = ((PyBytesObject*)s2)->ob_shash;
             if (hash1 != hash2 && hash1 != -1 && hash2 != -1) {
                 return (equals == Py_NE);
             }
 #endif
@@ -51124,18 +51531,16 @@
 
 /* UnpackItemEndCheck */
 static int __Pyx_IternextUnpackEndCheck(PyObject *retval, Py_ssize_t expected) {
     if (unlikely(retval)) {
         Py_DECREF(retval);
         __Pyx_RaiseTooManyValuesError(expected);
         return -1;
-    } else {
-        return __Pyx_IterFinish();
     }
-    return 0;
+    return __Pyx_IterFinish();
 }
 
 /* CallNextTpDealloc */
 static void __Pyx_call_next_tp_dealloc(PyObject* obj, destructor current_tp_dealloc) {
     PyTypeObject* type = Py_TYPE(obj);
     while (type && type->tp_dealloc != current_tp_dealloc)
         type = type->tp_base;
@@ -51274,25 +51679,43 @@
   }
   Py_XDECREF(name_attr);
   return ret;
 }
 static int __Pyx_setup_reduce(PyObject* type_obj) {
     int ret = 0;
     PyObject *object_reduce = NULL;
+    PyObject *object_getstate = NULL;
     PyObject *object_reduce_ex = NULL;
     PyObject *reduce = NULL;
     PyObject *reduce_ex = NULL;
     PyObject *reduce_cython = NULL;
     PyObject *setstate = NULL;
     PyObject *setstate_cython = NULL;
+    PyObject *getstate = NULL;
 #if CYTHON_USE_PYTYPE_LOOKUP
-    if (_PyType_Lookup((PyTypeObject*)type_obj, __pyx_n_s_getstate)) goto __PYX_GOOD;
+    getstate = _PyType_Lookup((PyTypeObject*)type_obj, __pyx_n_s_getstate);
 #else
-    if (PyObject_HasAttr(type_obj, __pyx_n_s_getstate)) goto __PYX_GOOD;
+    getstate = __Pyx_PyObject_GetAttrStrNoError(type_obj, __pyx_n_s_getstate);
+    if (!getstate && PyErr_Occurred()) {
+        goto __PYX_BAD;
+    }
 #endif
+    if (getstate) {
+#if CYTHON_USE_PYTYPE_LOOKUP
+        object_getstate = _PyType_Lookup(&PyBaseObject_Type, __pyx_n_s_getstate);
+#else
+        object_getstate = __Pyx_PyObject_GetAttrStrNoError((PyObject*)&PyBaseObject_Type, __pyx_n_s_getstate);
+        if (!object_getstate && PyErr_Occurred()) {
+            goto __PYX_BAD;
+        }
+#endif
+        if (object_getstate != getstate) {
+            goto __PYX_GOOD;
+        }
+    }
 #if CYTHON_USE_PYTYPE_LOOKUP
     object_reduce_ex = _PyType_Lookup(&PyBaseObject_Type, __pyx_n_s_reduce_ex); if (!object_reduce_ex) goto __PYX_BAD;
 #else
     object_reduce_ex = __Pyx_PyObject_GetAttrStr((PyObject*)&PyBaseObject_Type, __pyx_n_s_reduce_ex); if (!object_reduce_ex) goto __PYX_BAD;
 #endif
     reduce_ex = __Pyx_PyObject_GetAttrStr(type_obj, __pyx_n_s_reduce_ex); if (unlikely(!reduce_ex)) goto __PYX_BAD;
     if (reduce_ex == object_reduce_ex) {
@@ -51329,71 +51752,91 @@
     if (!PyErr_Occurred())
         PyErr_Format(PyExc_RuntimeError, "Unable to initialize pickling for %s", ((PyTypeObject*)type_obj)->tp_name);
     ret = -1;
 __PYX_GOOD:
 #if !CYTHON_USE_PYTYPE_LOOKUP
     Py_XDECREF(object_reduce);
     Py_XDECREF(object_reduce_ex);
+    Py_XDECREF(object_getstate);
+    Py_XDECREF(getstate);
 #endif
     Py_XDECREF(reduce);
     Py_XDECREF(reduce_ex);
     Py_XDECREF(reduce_cython);
     Py_XDECREF(setstate);
     Py_XDECREF(setstate_cython);
     return ret;
 }
 
 /* TypeImport */
-#ifndef __PYX_HAVE_RT_ImportType
-#define __PYX_HAVE_RT_ImportType
-static PyTypeObject *__Pyx_ImportType(PyObject *module, const char *module_name, const char *class_name,
-    size_t size, enum __Pyx_ImportType_CheckSize check_size)
+#ifndef __PYX_HAVE_RT_ImportType_0_29_35
+#define __PYX_HAVE_RT_ImportType_0_29_35
+static PyTypeObject *__Pyx_ImportType_0_29_35(PyObject *module, const char *module_name, const char *class_name,
+    size_t size, size_t alignment, enum __Pyx_ImportType_CheckSize_0_29_35 check_size)
 {
     PyObject *result = 0;
     char warning[200];
     Py_ssize_t basicsize;
+    Py_ssize_t itemsize;
 #ifdef Py_LIMITED_API
     PyObject *py_basicsize;
+    PyObject *py_itemsize;
 #endif
     result = PyObject_GetAttrString(module, class_name);
     if (!result)
         goto bad;
     if (!PyType_Check(result)) {
         PyErr_Format(PyExc_TypeError,
             "%.200s.%.200s is not a type object",
             module_name, class_name);
         goto bad;
     }
 #ifndef Py_LIMITED_API
     basicsize = ((PyTypeObject *)result)->tp_basicsize;
+    itemsize = ((PyTypeObject *)result)->tp_itemsize;
 #else
     py_basicsize = PyObject_GetAttrString(result, "__basicsize__");
     if (!py_basicsize)
         goto bad;
     basicsize = PyLong_AsSsize_t(py_basicsize);
     Py_DECREF(py_basicsize);
     py_basicsize = 0;
     if (basicsize == (Py_ssize_t)-1 && PyErr_Occurred())
         goto bad;
+    py_itemsize = PyObject_GetAttrString(result, "__itemsize__");
+    if (!py_itemsize)
+        goto bad;
+    itemsize = PyLong_AsSsize_t(py_itemsize);
+    Py_DECREF(py_itemsize);
+    py_itemsize = 0;
+    if (itemsize == (Py_ssize_t)-1 && PyErr_Occurred())
+        goto bad;
 #endif
-    if ((size_t)basicsize < size) {
+    if (itemsize) {
+        if (size % alignment) {
+            alignment = size % alignment;
+        }
+        if (itemsize < (Py_ssize_t)alignment)
+            itemsize = (Py_ssize_t)alignment;
+    }
+    if ((size_t)(basicsize + itemsize) < size) {
         PyErr_Format(PyExc_ValueError,
             "%.200s.%.200s size changed, may indicate binary incompatibility. "
             "Expected %zd from C header, got %zd from PyObject",
             module_name, class_name, size, basicsize);
         goto bad;
     }
-    if (check_size == __Pyx_ImportType_CheckSize_Error && (size_t)basicsize != size) {
+    if (check_size == __Pyx_ImportType_CheckSize_Error_0_29_35 && (size_t)basicsize != size) {
         PyErr_Format(PyExc_ValueError,
             "%.200s.%.200s size changed, may indicate binary incompatibility. "
             "Expected %zd from C header, got %zd from PyObject",
             module_name, class_name, size, basicsize);
         goto bad;
     }
-    else if (check_size == __Pyx_ImportType_CheckSize_Warn && (size_t)basicsize > size) {
+    else if (check_size == __Pyx_ImportType_CheckSize_Warn_0_29_35 && (size_t)basicsize > size) {
         PyOS_snprintf(warning, sizeof(warning),
             "%s.%s size changed, may indicate binary incompatibility. "
             "Expected %zd from C header, got %zd from PyObject",
             module_name, class_name, size, basicsize);
         if (PyErr_WarnEx(NULL, warning, 0) < 0) goto bad;
     }
     return (PyTypeObject *)result;
@@ -51421,15 +51864,15 @@
 bad:
     Py_XDECREF(ob);
     return NULL;
 }
 
 /* CLineInTraceback */
 #ifndef CYTHON_CLINE_IN_TRACEBACK
-static int __Pyx_CLineForTraceback(CYTHON_NCP_UNUSED PyThreadState *tstate, int c_line) {
+static int __Pyx_CLineForTraceback(CYTHON_UNUSED PyThreadState *tstate, int c_line) {
     PyObject *use_cline;
     PyObject *ptype, *pvalue, *ptraceback;
 #if CYTHON_COMPILING_IN_CPYTHON
     PyObject **cython_runtime_dict;
 #endif
     if (unlikely(!__pyx_cython_runtime)) {
         return c_line;
@@ -51451,15 +51894,15 @@
       } else {
         PyErr_Clear();
         use_cline = NULL;
       }
     }
     if (!use_cline) {
         c_line = 0;
-        PyObject_SetAttr(__pyx_cython_runtime, __pyx_n_s_cline_in_traceback, Py_False);
+        (void) PyObject_SetAttr(__pyx_cython_runtime, __pyx_n_s_cline_in_traceback, Py_False);
     }
     else if (use_cline == Py_False || (use_cline != Py_True && PyObject_Not(use_cline) != 0)) {
         c_line = 0;
     }
     __Pyx_ErrRestoreInState(tstate, ptype, pvalue, ptraceback);
     return c_line;
 }
@@ -51545,41 +51988,48 @@
     Py_INCREF(code_object);
 }
 
 /* AddTraceback */
 #include "compile.h"
 #include "frameobject.h"
 #include "traceback.h"
+#if PY_VERSION_HEX >= 0x030b00a6
+  #ifndef Py_BUILD_CORE
+    #define Py_BUILD_CORE 1
+  #endif
+  #include "internal/pycore_frame.h"
+#endif
 static PyCodeObject* __Pyx_CreateCodeObjectForTraceback(
             const char *funcname, int c_line,
             int py_line, const char *filename) {
-    PyCodeObject *py_code = 0;
-    PyObject *py_srcfile = 0;
-    PyObject *py_funcname = 0;
+    PyCodeObject *py_code = NULL;
+    PyObject *py_funcname = NULL;
     #if PY_MAJOR_VERSION < 3
+    PyObject *py_srcfile = NULL;
     py_srcfile = PyString_FromString(filename);
-    #else
-    py_srcfile = PyUnicode_FromString(filename);
-    #endif
     if (!py_srcfile) goto bad;
+    #endif
     if (c_line) {
         #if PY_MAJOR_VERSION < 3
         py_funcname = PyString_FromFormat( "%s (%s:%d)", funcname, __pyx_cfilenm, c_line);
+        if (!py_funcname) goto bad;
         #else
         py_funcname = PyUnicode_FromFormat( "%s (%s:%d)", funcname, __pyx_cfilenm, c_line);
+        if (!py_funcname) goto bad;
+        funcname = PyUnicode_AsUTF8(py_funcname);
+        if (!funcname) goto bad;
         #endif
     }
     else {
         #if PY_MAJOR_VERSION < 3
         py_funcname = PyString_FromString(funcname);
-        #else
-        py_funcname = PyUnicode_FromString(funcname);
+        if (!py_funcname) goto bad;
         #endif
     }
-    if (!py_funcname) goto bad;
+    #if PY_MAJOR_VERSION < 3
     py_code = __Pyx_PyCode_New(
         0,
         0,
         0,
         0,
         0,
         __pyx_empty_bytes, /*PyObject *code,*/
@@ -51590,34 +52040,49 @@
         __pyx_empty_tuple, /*PyObject *cellvars,*/
         py_srcfile,   /*PyObject *filename,*/
         py_funcname,  /*PyObject *name,*/
         py_line,
         __pyx_empty_bytes  /*PyObject *lnotab*/
     );
     Py_DECREF(py_srcfile);
-    Py_DECREF(py_funcname);
+    #else
+    py_code = PyCode_NewEmpty(filename, funcname, py_line);
+    #endif
+    Py_XDECREF(py_funcname);  // XDECREF since it's only set on Py3 if cline
     return py_code;
 bad:
-    Py_XDECREF(py_srcfile);
     Py_XDECREF(py_funcname);
+    #if PY_MAJOR_VERSION < 3
+    Py_XDECREF(py_srcfile);
+    #endif
     return NULL;
 }
 static void __Pyx_AddTraceback(const char *funcname, int c_line,
                                int py_line, const char *filename) {
     PyCodeObject *py_code = 0;
     PyFrameObject *py_frame = 0;
     PyThreadState *tstate = __Pyx_PyThreadState_Current;
+    PyObject *ptype, *pvalue, *ptraceback;
     if (c_line) {
         c_line = __Pyx_CLineForTraceback(tstate, c_line);
     }
     py_code = __pyx_find_code_object(c_line ? -c_line : py_line);
     if (!py_code) {
+        __Pyx_ErrFetchInState(tstate, &ptype, &pvalue, &ptraceback);
         py_code = __Pyx_CreateCodeObjectForTraceback(
             funcname, c_line, py_line, filename);
-        if (!py_code) goto bad;
+        if (!py_code) {
+            /* If the code object creation fails, then we should clear the
+               fetched exception references and propagate the new exception */
+            Py_XDECREF(ptype);
+            Py_XDECREF(pvalue);
+            Py_XDECREF(ptraceback);
+            goto bad;
+        }
+        __Pyx_ErrRestoreInState(tstate, ptype, pvalue, ptraceback);
         __pyx_insert_code_object(c_line ? -c_line : py_line, py_code);
     }
     py_frame = PyFrame_New(
         tstate,            /*PyThreadState *tstate,*/
         py_code,           /*PyCodeObject *code,*/
         __pyx_d,    /*PyObject *globals,*/
         0                  /*PyObject *locals*/
@@ -51708,15 +52173,15 @@
                         } else if (8 * sizeof(int) >= 4 * PyLong_SHIFT) {
                             return (int) (((((((((int)digits[3]) << PyLong_SHIFT) | (int)digits[2]) << PyLong_SHIFT) | (int)digits[1]) << PyLong_SHIFT) | (int)digits[0]));
                         }
                     }
                     break;
             }
 #endif
-#if CYTHON_COMPILING_IN_CPYTHON
+#if CYTHON_COMPILING_IN_CPYTHON && PY_VERSION_HEX < 0x030C00A7
             if (unlikely(Py_SIZE(x) < 0)) {
                 goto raise_neg_overflow;
             }
 #else
             {
                 int result = PyObject_RichCompareBool(x, Py_False, Py_LT);
                 if (unlikely(result < 0))
@@ -51904,15 +52369,15 @@
                         } else if (8 * sizeof(gcg::USERGIVEN) >= 4 * PyLong_SHIFT) {
                             return (gcg::USERGIVEN) (((((((((gcg::USERGIVEN)digits[3]) << PyLong_SHIFT) | (gcg::USERGIVEN)digits[2]) << PyLong_SHIFT) | (gcg::USERGIVEN)digits[1]) << PyLong_SHIFT) | (gcg::USERGIVEN)digits[0]));
                         }
                     }
                     break;
             }
 #endif
-#if CYTHON_COMPILING_IN_CPYTHON
+#if CYTHON_COMPILING_IN_CPYTHON && PY_VERSION_HEX < 0x030C00A7
             if (unlikely(Py_SIZE(x) < 0)) {
                 goto raise_neg_overflow;
             }
 #else
             {
                 int result = PyObject_RichCompareBool(x, Py_False, Py_LT);
                 if (unlikely(result < 0))
@@ -52176,15 +52641,15 @@
                         } else if (8 * sizeof(long) >= 4 * PyLong_SHIFT) {
                             return (long) (((((((((long)digits[3]) << PyLong_SHIFT) | (long)digits[2]) << PyLong_SHIFT) | (long)digits[1]) << PyLong_SHIFT) | (long)digits[0]));
                         }
                     }
                     break;
             }
 #endif
-#if CYTHON_COMPILING_IN_CPYTHON
+#if CYTHON_COMPILING_IN_CPYTHON && PY_VERSION_HEX < 0x030C00A7
             if (unlikely(Py_SIZE(x) < 0)) {
                 goto raise_neg_overflow;
             }
 #else
             {
                 int result = PyObject_RichCompareBool(x, Py_False, Py_LT);
                 if (unlikely(result < 0))
@@ -52372,15 +52837,15 @@
                         } else if (8 * sizeof(size_t) >= 4 * PyLong_SHIFT) {
                             return (size_t) (((((((((size_t)digits[3]) << PyLong_SHIFT) | (size_t)digits[2]) << PyLong_SHIFT) | (size_t)digits[1]) << PyLong_SHIFT) | (size_t)digits[0]));
                         }
                     }
                     break;
             }
 #endif
-#if CYTHON_COMPILING_IN_CPYTHON
+#if CYTHON_COMPILING_IN_CPYTHON && PY_VERSION_HEX < 0x030C00A7
             if (unlikely(Py_SIZE(x) < 0)) {
                 goto raise_neg_overflow;
             }
 #else
             {
                 int result = PyObject_RichCompareBool(x, Py_False, Py_LT);
                 if (unlikely(result < 0))
@@ -52606,15 +53071,15 @@
                         } else if (8 * sizeof(SCIP_RESULT) >= 4 * PyLong_SHIFT) {
                             return (SCIP_RESULT) (((((((((SCIP_RESULT)digits[3]) << PyLong_SHIFT) | (SCIP_RESULT)digits[2]) << PyLong_SHIFT) | (SCIP_RESULT)digits[1]) << PyLong_SHIFT) | (SCIP_RESULT)digits[0]));
                         }
                     }
                     break;
             }
 #endif
-#if CYTHON_COMPILING_IN_CPYTHON
+#if CYTHON_COMPILING_IN_CPYTHON && PY_VERSION_HEX < 0x030C00A7
             if (unlikely(Py_SIZE(x) < 0)) {
                 goto raise_neg_overflow;
             }
 #else
             {
                 int result = PyObject_RichCompareBool(x, Py_False, Py_LT);
                 if (unlikely(result < 0))
@@ -52802,15 +53267,15 @@
                         } else if (8 * sizeof(GCG_PRICINGSTATUS) >= 4 * PyLong_SHIFT) {
                             return (GCG_PRICINGSTATUS) (((((((((GCG_PRICINGSTATUS)digits[3]) << PyLong_SHIFT) | (GCG_PRICINGSTATUS)digits[2]) << PyLong_SHIFT) | (GCG_PRICINGSTATUS)digits[1]) << PyLong_SHIFT) | (GCG_PRICINGSTATUS)digits[0]));
                         }
                     }
                     break;
             }
 #endif
-#if CYTHON_COMPILING_IN_CPYTHON
+#if CYTHON_COMPILING_IN_CPYTHON && PY_VERSION_HEX < 0x030C00A7
             if (unlikely(Py_SIZE(x) < 0)) {
                 goto raise_neg_overflow;
             }
 #else
             {
                 int result = PyObject_RichCompareBool(x, Py_False, Py_LT);
                 if (unlikely(result < 0))
@@ -53150,15 +53615,15 @@
                         } else if (8 * sizeof(SCIP_PARAMSETTING) >= 4 * PyLong_SHIFT) {
                             return (SCIP_PARAMSETTING) (((((((((SCIP_PARAMSETTING)digits[3]) << PyLong_SHIFT) | (SCIP_PARAMSETTING)digits[2]) << PyLong_SHIFT) | (SCIP_PARAMSETTING)digits[1]) << PyLong_SHIFT) | (SCIP_PARAMSETTING)digits[0]));
                         }
                     }
                     break;
             }
 #endif
-#if CYTHON_COMPILING_IN_CPYTHON
+#if CYTHON_COMPILING_IN_CPYTHON && PY_VERSION_HEX < 0x030C00A7
             if (unlikely(Py_SIZE(x) < 0)) {
                 goto raise_neg_overflow;
             }
 #else
             {
                 int result = PyObject_RichCompareBool(x, Py_False, Py_LT);
                 if (unlikely(result < 0))
@@ -53426,19 +53891,41 @@
     }
     return (PyErr_GivenExceptionMatches(err, exc_type1) || PyErr_GivenExceptionMatches(err, exc_type2));
 }
 #endif
 
 /* CheckBinaryVersion */
 static int __Pyx_check_binary_version(void) {
-    char ctversion[4], rtversion[4];
-    PyOS_snprintf(ctversion, 4, "%d.%d", PY_MAJOR_VERSION, PY_MINOR_VERSION);
-    PyOS_snprintf(rtversion, 4, "%s", Py_GetVersion());
-    if (ctversion[0] != rtversion[0] || ctversion[2] != rtversion[2]) {
+    char ctversion[5];
+    int same=1, i, found_dot;
+    const char* rt_from_call = Py_GetVersion();
+    PyOS_snprintf(ctversion, 5, "%d.%d", PY_MAJOR_VERSION, PY_MINOR_VERSION);
+    found_dot = 0;
+    for (i = 0; i < 4; i++) {
+        if (!ctversion[i]) {
+            same = (rt_from_call[i] < '0' || rt_from_call[i] > '9');
+            break;
+        }
+        if (rt_from_call[i] != ctversion[i]) {
+            same = 0;
+            break;
+        }
+    }
+    if (!same) {
+        char rtversion[5] = {'\0'};
         char message[200];
+        for (i=0; i<4; ++i) {
+            if (rt_from_call[i] == '.') {
+                if (found_dot) break;
+                found_dot = 1;
+            } else if (rt_from_call[i] < '0' || rt_from_call[i] > '9') {
+                break;
+            }
+            rtversion[i] = rt_from_call[i];
+        }
         PyOS_snprintf(message, sizeof(message),
                       "compiletime version %s of module '%.100s' "
                       "does not match runtime version %s",
                       ctversion, __Pyx_MODULE_NAME, rtversion);
         return PyErr_WarnEx(NULL, message, 1);
     }
     return 0;
@@ -53688,14 +54175,31 @@
   }
   x = PyNumber_Index(b);
   if (!x) return -1;
   ival = PyInt_AsSsize_t(x);
   Py_DECREF(x);
   return ival;
 }
+static CYTHON_INLINE Py_hash_t __Pyx_PyIndex_AsHash_t(PyObject* o) {
+  if (sizeof(Py_hash_t) == sizeof(Py_ssize_t)) {
+    return (Py_hash_t) __Pyx_PyIndex_AsSsize_t(o);
+#if PY_MAJOR_VERSION < 3
+  } else if (likely(PyInt_CheckExact(o))) {
+    return PyInt_AS_LONG(o);
+#endif
+  } else {
+    Py_ssize_t ival;
+    PyObject *x;
+    x = PyNumber_Index(o);
+    if (!x) return -1;
+    ival = PyInt_AsLong(x);
+    Py_DECREF(x);
+    return ival;
+  }
+}
 static CYTHON_INLINE PyObject * __Pyx_PyBool_FromLong(long b) {
   return b ? __Pyx_NewRef(Py_True) : __Pyx_NewRef(Py_False);
 }
 static CYTHON_INLINE PyObject * __Pyx_PyInt_FromSize_t(size_t ival) {
     return PyInt_FromSize_t(ival);
 }
```

### Comparing `PyGCGOpt-0.1.4/src/pygcgopt/gcg.pxd` & `PyGCGOpt-0.2.0/src/pygcgopt/gcg.pxd`

 * *Files 2% similar despite different names*

```diff
@@ -45,14 +45,19 @@
     SCIP* GCGgetMasterprob(SCIP* scip)
 
     ctypedef enum GP_OUTPUT_FORMAT:
         GP_OUTPUT_FORMAT_PDF
         GP_OUTPUT_FORMAT_PNG
         GP_OUTPUT_FORMAT_SVG
 
+    SCIP_VAR** GCGoriginalVarGetMastervars(SCIP_VAR* var)
+    int GCGoriginalVarGetNMastervars(SCIP_VAR* var)
+    SCIP_VAR** GCGmasterVarGetOrigvars(SCIP_VAR* var)
+    int GCGmasterVarGetNOrigvars(SCIP_VAR* var)
+
 
 cdef extern from "gcg/pub_gcgsepa.h":
     SCIP_RETCODE GCGsetSeparators(SCIP* scip, SCIP_PARAMSETTING paramsetting)
 
 
 cdef extern from "gcg/gcgplugins.h":
     SCIP_RETCODE SCIPincludeGcgPlugins(SCIP* scip)
```

### Comparing `PyGCGOpt-0.1.4/src/pygcgopt/gcg.pyx` & `PyGCGOpt-0.2.0/src/pygcgopt/gcg.pyx`

 * *Files 3% similar despite different names*

```diff
@@ -344,14 +344,24 @@
         """
         if createDirectory:
             Path(directory).mkdir(exist_ok=True, parents=True)
         c_directory = str_conversion(directory)
         c_extension = str_conversion(extension)
         PY_SCIP_CALL(DECwriteAllDecomps(self._scip, c_directory, c_extension, original, presolved))
 
+    def getMastervars(self, var):
+        """Returns the master variables corresponding to the variable of original problem
+
+        :param var: Variable of original problem
+        :return: List of master variables
+        """
+        cdef int n_vars = GCGoriginalVarGetNMastervars((<Variable>var).scip_var)
+        cdef SCIP_VAR** mastervars = GCGoriginalVarGetMastervars((<Variable>var).scip_var)
+        return [Variable.create(mastervars[i]) for i in range(n_vars)]
+
 
 cdef class GCGPricingModel(SCIPModel):
     @staticmethod
     cdef create(SCIP* scip):
         """Creates a pricing problem model and appropriately assigns the scip and bestsol parameters
         """
         if scip == NULL:
@@ -400,14 +410,24 @@
         model._scip = scip
         model._bestSol = Solution.create(scip, SCIPgetBestSol(scip))
         return model
 
     def addCol(self, GCGColumn col):
         PY_SCIP_CALL(GCGpricerAddCol(self._scip, col.gcg_col))
 
+    def getOrigvars(self, var):
+        """Returns the original variables corresponding to the variable of master problem
+
+        :param var: Variable of master problem
+        :return: List of original variables
+        """
+        cdef int n_vars = GCGmasterVarGetNOrigvars((<Variable>var).scip_var)
+        cdef SCIP_VAR** originalvars = GCGmasterVarGetOrigvars((<Variable>var).scip_var)
+        return [Variable.create(originalvars[i]) for i in range(n_vars)]
+
 
 cdef class GCGColumn:
     """Base class holding a pointer to corresponding GCG_COL"""
 
     @staticmethod
     cdef create(GCG_COL* gcgcol):
         if gcgcol == NULL:
```

### Comparing `PyGCGOpt-0.1.4/src/pygcgopt/partition.pxi` & `PyGCGOpt-0.2.0/src/pygcgopt/partition.pxi`

 * *Files identical despite different names*

### Comparing `PyGCGOpt-0.1.4/src/pygcgopt/pricing_solver.pxi` & `PyGCGOpt-0.2.0/src/pygcgopt/pricing_solver.pxi`

 * *Files identical despite different names*


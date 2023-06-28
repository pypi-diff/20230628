# Comparing `tmp/ch5mpy-0.2.1.tar.gz` & `tmp/ch5mpy-0.2.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ch5mpy-0.2.1.tar", last modified: Tue Jun 27 18:18:59 2023, max compression
+gzip compressed data, was "ch5mpy-0.2.2.tar", last modified: Wed Jun 28 08:08:54 2023, max compression
```

## Comparing `ch5mpy-0.2.1.tar` & `ch5mpy-0.2.2.tar`

### file list

```diff
@@ -1,74 +1,75 @@
-drwxrwxr-x   0 mbouvier  (1001) mbouvier  (1001)        0 2023-06-27 18:18:59.332002 ch5mpy-0.2.1/
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)    21392 2023-02-10 13:26:33.000000 ch5mpy-0.2.1/LICENSE
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)    39515 2023-06-27 18:18:59.328003 ch5mpy-0.2.1/PKG-INFO
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)    12814 2023-06-27 15:55:49.000000 ch5mpy-0.2.1/README.md
-drwxrwxr-x   0 mbouvier  (1001) mbouvier  (1001)        0 2023-06-27 18:18:59.324003 ch5mpy-0.2.1/ch5mpy/
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     1098 2023-06-27 16:02:51.000000 ch5mpy-0.2.1/ch5mpy/__init__.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)      420 2023-06-11 21:11:04.000000 ch5mpy-0.2.1/ch5mpy/_typing.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     2083 2023-05-24 14:37:45.000000 ch5mpy-0.2.1/ch5mpy/attributes.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     5268 2023-06-27 16:01:57.000000 ch5mpy-0.2.1/ch5mpy/dict.py
-drwxrwxr-x   0 mbouvier  (1001) mbouvier  (1001)        0 2023-06-27 18:18:59.328003 ch5mpy-0.2.1/ch5mpy/h5array/
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)       64 2023-05-30 07:23:40.000000 ch5mpy-0.2.1/ch5mpy/h5array/__init__.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)    11759 2023-06-27 15:26:53.000000 ch5mpy-0.2.1/ch5mpy/h5array/array.py
-drwxrwxr-x   0 mbouvier  (1001) mbouvier  (1001)        0 2023-06-27 18:18:59.328003 ch5mpy-0.2.1/ch5mpy/h5array/chunks/
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)      145 2023-03-03 16:51:50.000000 ch5mpy-0.2.1/ch5mpy/h5array/chunks/__init__.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     5921 2023-05-24 13:08:59.000000 ch5mpy-0.2.1/ch5mpy/h5array/chunks/iter.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     3092 2023-04-17 15:18:01.000000 ch5mpy-0.2.1/ch5mpy/h5array/chunks/repeated_array.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)      424 2023-03-03 23:04:08.000000 ch5mpy-0.2.1/ch5mpy/h5array/chunks/utils.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     5181 2023-04-28 12:16:43.000000 ch5mpy-0.2.1/ch5mpy/h5array/creation_routines.py
-drwxrwxr-x   0 mbouvier  (1001) mbouvier  (1001)        0 2023-06-27 18:18:59.328003 ch5mpy-0.2.1/ch5mpy/h5array/functions/
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)      242 2023-04-17 14:55:50.000000 ch5mpy-0.2.1/ch5mpy/h5array/functions/__init__.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)    10050 2023-06-06 14:08:06.000000 ch5mpy-0.2.1/ch5mpy/h5array/functions/apply.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     1216 2023-04-17 14:55:50.000000 ch5mpy-0.2.1/ch5mpy/h5array/functions/creation_routines.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     7997 2023-04-26 10:00:28.000000 ch5mpy-0.2.1/ch5mpy/h5array/functions/element_wise.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     1150 2023-03-14 10:11:16.000000 ch5mpy-0.2.1/ch5mpy/h5array/functions/implement.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)    10474 2023-06-13 09:17:20.000000 ch5mpy-0.2.1/ch5mpy/h5array/functions/routines.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)    16164 2023-04-17 15:18:02.000000 ch5mpy-0.2.1/ch5mpy/h5array/functions/two_arrays.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     2172 2023-06-27 13:11:28.000000 ch5mpy-0.2.1/ch5mpy/h5array/io.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     3776 2023-04-17 15:18:01.000000 ch5mpy-0.2.1/ch5mpy/h5array/repr.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     4629 2023-06-22 09:17:13.000000 ch5mpy-0.2.1/ch5mpy/h5array/view.py
-drwxrwxr-x   0 mbouvier  (1001) mbouvier  (1001)        0 2023-06-27 18:18:59.328003 ch5mpy-0.2.1/ch5mpy/indexing/
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)      210 2023-05-04 09:56:15.000000 ch5mpy-0.2.1/ch5mpy/indexing/__init__.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)      403 2023-05-04 09:53:30.000000 ch5mpy-0.2.1/ch5mpy/indexing/_typing.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     3193 2023-05-09 13:33:47.000000 ch5mpy-0.2.1/ch5mpy/indexing/list.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)    16101 2023-06-09 16:37:50.000000 ch5mpy-0.2.1/ch5mpy/indexing/selection.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     4565 2023-06-07 09:35:55.000000 ch5mpy-0.2.1/ch5mpy/indexing/slice.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     1385 2023-05-04 09:54:41.000000 ch5mpy-0.2.1/ch5mpy/indexing/special.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     3734 2023-06-16 14:11:05.000000 ch5mpy-0.2.1/ch5mpy/list.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)      939 2023-06-27 16:02:51.000000 ch5mpy-0.2.1/ch5mpy/memory_size.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)      725 2023-06-27 13:11:28.000000 ch5mpy-0.2.1/ch5mpy/names.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)      648 2023-04-17 14:55:50.000000 ch5mpy-0.2.1/ch5mpy/np.py
-drwxrwxr-x   0 mbouvier  (1001) mbouvier  (1001)        0 2023-06-27 18:18:59.328003 ch5mpy-0.2.1/ch5mpy/objects/
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)      203 2023-05-30 07:23:40.000000 ch5mpy-0.2.1/ch5mpy/objects/__init__.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     8185 2023-06-20 13:23:29.000000 ch5mpy-0.2.1/ch5mpy/objects/dataset.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     6874 2023-06-20 13:23:29.000000 ch5mpy-0.2.1/ch5mpy/objects/group.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     2122 2023-06-06 14:12:48.000000 ch5mpy-0.2.1/ch5mpy/objects/object.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     1144 2023-05-30 07:25:38.000000 ch5mpy-0.2.1/ch5mpy/objects/pickle.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     1533 2023-06-27 16:02:51.000000 ch5mpy-0.2.1/ch5mpy/options.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     2016 2023-05-24 13:11:19.000000 ch5mpy-0.2.1/ch5mpy/read.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)      658 2023-04-17 14:55:50.000000 ch5mpy-0.2.1/ch5mpy/utils.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     5529 2023-05-30 07:34:03.000000 ch5mpy-0.2.1/ch5mpy/write.py
-drwxrwxr-x   0 mbouvier  (1001) mbouvier  (1001)        0 2023-06-27 18:18:59.324003 ch5mpy-0.2.1/ch5mpy.egg-info/
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)    39515 2023-06-27 18:18:59.000000 ch5mpy-0.2.1/ch5mpy.egg-info/PKG-INFO
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     1611 2023-06-27 18:18:59.000000 ch5mpy-0.2.1/ch5mpy.egg-info/SOURCES.txt
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)        1 2023-06-27 18:18:59.000000 ch5mpy-0.2.1/ch5mpy.egg-info/dependency_links.txt
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)       93 2023-06-27 18:18:59.000000 ch5mpy-0.2.1/ch5mpy.egg-info/requires.txt
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)        7 2023-06-27 18:18:59.000000 ch5mpy-0.2.1/ch5mpy.egg-info/top_level.txt
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     1830 2023-06-27 18:16:30.000000 ch5mpy-0.2.1/pyproject.toml
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)       38 2023-06-27 18:18:59.332002 ch5mpy-0.2.1/setup.cfg
-drwxrwxr-x   0 mbouvier  (1001) mbouvier  (1001)        0 2023-06-27 18:18:59.328003 ch5mpy-0.2.1/tests/
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)      517 2023-03-15 09:19:15.000000 ch5mpy-0.2.1/tests/test_array_creation.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     2169 2023-02-15 17:14:15.000000 ch5mpy-0.2.1/tests/test_array_repr.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)      556 2023-03-15 09:55:44.000000 ch5mpy-0.2.1/tests/test_chunked_array.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     1145 2023-02-16 18:29:12.000000 ch5mpy-0.2.1/tests/test_complex_object_h5array.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)      532 2023-05-04 09:54:46.000000 ch5mpy-0.2.1/tests/test_full_slice.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)    12118 2023-06-27 16:01:14.000000 ch5mpy-0.2.1/tests/test_functions.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)    12729 2023-05-04 09:56:16.000000 ch5mpy-0.2.1/tests/test_get_chunks.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     1955 2023-06-19 12:44:35.000000 ch5mpy-0.2.1/tests/test_h5_list.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)    13534 2023-06-27 15:59:21.000000 ch5mpy-0.2.1/tests/test_h5array.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     4479 2023-05-30 07:36:37.000000 ch5mpy-0.2.1/tests/test_h5dict.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)      802 2023-02-15 17:14:15.000000 ch5mpy-0.2.1/tests/test_pickle.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)      562 2023-03-03 23:51:35.000000 ch5mpy-0.2.1/tests/test_repeated_array.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     5051 2023-05-11 14:31:16.000000 ch5mpy-0.2.1/tests/test_selection.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     1418 2023-03-15 16:13:04.000000 ch5mpy-0.2.1/tests/test_str_h5array.py
--rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     2230 2023-05-24 09:14:55.000000 ch5mpy-0.2.1/tests/test_write.py
+drwxrwxr-x   0 mbouvier  (1001) mbouvier  (1001)        0 2023-06-28 08:08:54.747446 ch5mpy-0.2.2/
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)    21392 2023-02-10 13:26:33.000000 ch5mpy-0.2.2/LICENSE
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)    39515 2023-06-28 08:08:54.747446 ch5mpy-0.2.2/PKG-INFO
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)    12814 2023-06-27 15:55:49.000000 ch5mpy-0.2.2/README.md
+drwxrwxr-x   0 mbouvier  (1001) mbouvier  (1001)        0 2023-06-28 08:08:54.743446 ch5mpy-0.2.2/ch5mpy/
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     1098 2023-06-27 16:02:51.000000 ch5mpy-0.2.2/ch5mpy/__init__.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)      420 2023-06-11 21:11:04.000000 ch5mpy-0.2.2/ch5mpy/_typing.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     2083 2023-05-24 14:37:45.000000 ch5mpy-0.2.2/ch5mpy/attributes.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     5268 2023-06-27 16:01:57.000000 ch5mpy-0.2.2/ch5mpy/dict.py
+drwxrwxr-x   0 mbouvier  (1001) mbouvier  (1001)        0 2023-06-28 08:08:54.743446 ch5mpy-0.2.2/ch5mpy/h5array/
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)       64 2023-05-30 07:23:40.000000 ch5mpy-0.2.2/ch5mpy/h5array/__init__.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)    11759 2023-06-27 15:26:53.000000 ch5mpy-0.2.2/ch5mpy/h5array/array.py
+drwxrwxr-x   0 mbouvier  (1001) mbouvier  (1001)        0 2023-06-28 08:08:54.743446 ch5mpy-0.2.2/ch5mpy/h5array/chunks/
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)      145 2023-03-03 16:51:50.000000 ch5mpy-0.2.2/ch5mpy/h5array/chunks/__init__.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     5921 2023-05-24 13:08:59.000000 ch5mpy-0.2.2/ch5mpy/h5array/chunks/iter.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     3092 2023-04-17 15:18:01.000000 ch5mpy-0.2.2/ch5mpy/h5array/chunks/repeated_array.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)      424 2023-03-03 23:04:08.000000 ch5mpy-0.2.2/ch5mpy/h5array/chunks/utils.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     5181 2023-04-28 12:16:43.000000 ch5mpy-0.2.2/ch5mpy/h5array/creation_routines.py
+drwxrwxr-x   0 mbouvier  (1001) mbouvier  (1001)        0 2023-06-28 08:08:54.743446 ch5mpy-0.2.2/ch5mpy/h5array/functions/
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)      242 2023-04-17 14:55:50.000000 ch5mpy-0.2.2/ch5mpy/h5array/functions/__init__.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)    10050 2023-06-06 14:08:06.000000 ch5mpy-0.2.2/ch5mpy/h5array/functions/apply.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     1216 2023-04-17 14:55:50.000000 ch5mpy-0.2.2/ch5mpy/h5array/functions/creation_routines.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     7997 2023-04-26 10:00:28.000000 ch5mpy-0.2.2/ch5mpy/h5array/functions/element_wise.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     1150 2023-03-14 10:11:16.000000 ch5mpy-0.2.2/ch5mpy/h5array/functions/implement.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)    10474 2023-06-13 09:17:20.000000 ch5mpy-0.2.2/ch5mpy/h5array/functions/routines.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)    16164 2023-04-17 15:18:02.000000 ch5mpy-0.2.2/ch5mpy/h5array/functions/two_arrays.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     2172 2023-06-27 13:11:28.000000 ch5mpy-0.2.2/ch5mpy/h5array/io.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     3776 2023-04-17 15:18:01.000000 ch5mpy-0.2.2/ch5mpy/h5array/repr.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     4629 2023-06-22 09:17:13.000000 ch5mpy-0.2.2/ch5mpy/h5array/view.py
+drwxrwxr-x   0 mbouvier  (1001) mbouvier  (1001)        0 2023-06-28 08:08:54.743446 ch5mpy-0.2.2/ch5mpy/indexing/
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)      210 2023-05-04 09:56:15.000000 ch5mpy-0.2.2/ch5mpy/indexing/__init__.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)      403 2023-05-04 09:53:30.000000 ch5mpy-0.2.2/ch5mpy/indexing/_typing.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     3193 2023-05-09 13:33:47.000000 ch5mpy-0.2.2/ch5mpy/indexing/list.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)    16101 2023-06-09 16:37:50.000000 ch5mpy-0.2.2/ch5mpy/indexing/selection.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     4565 2023-06-07 09:35:55.000000 ch5mpy-0.2.2/ch5mpy/indexing/slice.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     1385 2023-05-04 09:54:41.000000 ch5mpy-0.2.2/ch5mpy/indexing/special.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     3734 2023-06-16 14:11:05.000000 ch5mpy-0.2.2/ch5mpy/list.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)      939 2023-06-27 16:02:51.000000 ch5mpy-0.2.2/ch5mpy/memory_size.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)      725 2023-06-27 13:11:28.000000 ch5mpy-0.2.2/ch5mpy/names.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)      648 2023-04-17 14:55:50.000000 ch5mpy-0.2.2/ch5mpy/np.py
+drwxrwxr-x   0 mbouvier  (1001) mbouvier  (1001)        0 2023-06-28 08:08:54.743446 ch5mpy-0.2.2/ch5mpy/objects/
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)      203 2023-05-30 07:23:40.000000 ch5mpy-0.2.2/ch5mpy/objects/__init__.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     8185 2023-06-20 13:23:29.000000 ch5mpy-0.2.2/ch5mpy/objects/dataset.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     6874 2023-06-20 13:23:29.000000 ch5mpy-0.2.2/ch5mpy/objects/group.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     2122 2023-06-06 14:12:48.000000 ch5mpy-0.2.2/ch5mpy/objects/object.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     1144 2023-05-30 07:25:38.000000 ch5mpy-0.2.2/ch5mpy/objects/pickle.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     1533 2023-06-27 16:02:51.000000 ch5mpy-0.2.2/ch5mpy/options.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)        0 2023-06-07 15:06:06.000000 ch5mpy-0.2.2/ch5mpy/py.typed
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     2016 2023-05-24 13:11:19.000000 ch5mpy-0.2.2/ch5mpy/read.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)      658 2023-04-17 14:55:50.000000 ch5mpy-0.2.2/ch5mpy/utils.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     5529 2023-05-30 07:34:03.000000 ch5mpy-0.2.2/ch5mpy/write.py
+drwxrwxr-x   0 mbouvier  (1001) mbouvier  (1001)        0 2023-06-28 08:08:54.743446 ch5mpy-0.2.2/ch5mpy.egg-info/
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)    39515 2023-06-28 08:08:54.000000 ch5mpy-0.2.2/ch5mpy.egg-info/PKG-INFO
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     1627 2023-06-28 08:08:54.000000 ch5mpy-0.2.2/ch5mpy.egg-info/SOURCES.txt
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)        1 2023-06-28 08:08:54.000000 ch5mpy-0.2.2/ch5mpy.egg-info/dependency_links.txt
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)       93 2023-06-28 08:08:54.000000 ch5mpy-0.2.2/ch5mpy.egg-info/requires.txt
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)        7 2023-06-28 08:08:54.000000 ch5mpy-0.2.2/ch5mpy.egg-info/top_level.txt
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     1886 2023-06-28 08:07:53.000000 ch5mpy-0.2.2/pyproject.toml
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)       38 2023-06-28 08:08:54.747446 ch5mpy-0.2.2/setup.cfg
+drwxrwxr-x   0 mbouvier  (1001) mbouvier  (1001)        0 2023-06-28 08:08:54.747446 ch5mpy-0.2.2/tests/
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)      517 2023-03-15 09:19:15.000000 ch5mpy-0.2.2/tests/test_array_creation.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     2169 2023-02-15 17:14:15.000000 ch5mpy-0.2.2/tests/test_array_repr.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)      556 2023-03-15 09:55:44.000000 ch5mpy-0.2.2/tests/test_chunked_array.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     1145 2023-02-16 18:29:12.000000 ch5mpy-0.2.2/tests/test_complex_object_h5array.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)      532 2023-05-04 09:54:46.000000 ch5mpy-0.2.2/tests/test_full_slice.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)    12118 2023-06-27 16:01:14.000000 ch5mpy-0.2.2/tests/test_functions.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)    12729 2023-05-04 09:56:16.000000 ch5mpy-0.2.2/tests/test_get_chunks.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     1955 2023-06-19 12:44:35.000000 ch5mpy-0.2.2/tests/test_h5_list.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)    13534 2023-06-27 15:59:21.000000 ch5mpy-0.2.2/tests/test_h5array.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     4479 2023-05-30 07:36:37.000000 ch5mpy-0.2.2/tests/test_h5dict.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)      802 2023-02-15 17:14:15.000000 ch5mpy-0.2.2/tests/test_pickle.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)      562 2023-03-03 23:51:35.000000 ch5mpy-0.2.2/tests/test_repeated_array.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     5051 2023-05-11 14:31:16.000000 ch5mpy-0.2.2/tests/test_selection.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     1418 2023-03-15 16:13:04.000000 ch5mpy-0.2.2/tests/test_str_h5array.py
+-rw-rw-r--   0 mbouvier  (1001) mbouvier  (1001)     2230 2023-05-24 09:14:55.000000 ch5mpy-0.2.2/tests/test_write.py
```

### Comparing `ch5mpy-0.2.1/LICENSE` & `ch5mpy-0.2.2/LICENSE`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/PKG-INFO` & `ch5mpy-0.2.2/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ch5mpy
-Version: 0.2.1
+Version: 0.2.2
 Summary: Collection of helper tools for reading or writing to h5 files using the h5py library.
 Author-email: Matteo Bouvier <m.bouvier@vidium-solutions.com>
 Maintainer-email: Matteo Bouvier <m.bouvier@vidium-solutions.com>
 License: CeCILL-B FREE SOFTWARE LICENSE AGREEMENT
         
         
             Notice
```

### Comparing `ch5mpy-0.2.1/README.md` & `ch5mpy-0.2.2/README.md`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy/__init__.py` & `ch5mpy-0.2.2/ch5mpy/__init__.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy/attributes.py` & `ch5mpy-0.2.2/ch5mpy/attributes.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy/dict.py` & `ch5mpy-0.2.2/ch5mpy/dict.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy/h5array/array.py` & `ch5mpy-0.2.2/ch5mpy/h5array/array.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy/h5array/chunks/iter.py` & `ch5mpy-0.2.2/ch5mpy/h5array/chunks/iter.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy/h5array/chunks/repeated_array.py` & `ch5mpy-0.2.2/ch5mpy/h5array/chunks/repeated_array.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy/h5array/creation_routines.py` & `ch5mpy-0.2.2/ch5mpy/h5array/creation_routines.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy/h5array/functions/apply.py` & `ch5mpy-0.2.2/ch5mpy/h5array/functions/apply.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy/h5array/functions/creation_routines.py` & `ch5mpy-0.2.2/ch5mpy/h5array/functions/creation_routines.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy/h5array/functions/element_wise.py` & `ch5mpy-0.2.2/ch5mpy/h5array/functions/element_wise.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy/h5array/functions/implement.py` & `ch5mpy-0.2.2/ch5mpy/h5array/functions/implement.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy/h5array/functions/routines.py` & `ch5mpy-0.2.2/ch5mpy/h5array/functions/routines.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy/h5array/functions/two_arrays.py` & `ch5mpy-0.2.2/ch5mpy/h5array/functions/two_arrays.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy/h5array/io.py` & `ch5mpy-0.2.2/ch5mpy/h5array/io.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy/h5array/repr.py` & `ch5mpy-0.2.2/ch5mpy/h5array/repr.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy/h5array/view.py` & `ch5mpy-0.2.2/ch5mpy/h5array/view.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy/indexing/list.py` & `ch5mpy-0.2.2/ch5mpy/indexing/list.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy/indexing/selection.py` & `ch5mpy-0.2.2/ch5mpy/indexing/selection.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy/indexing/slice.py` & `ch5mpy-0.2.2/ch5mpy/indexing/slice.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy/indexing/special.py` & `ch5mpy-0.2.2/ch5mpy/indexing/special.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy/list.py` & `ch5mpy-0.2.2/ch5mpy/list.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy/memory_size.py` & `ch5mpy-0.2.2/ch5mpy/memory_size.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy/names.py` & `ch5mpy-0.2.2/ch5mpy/names.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy/np.py` & `ch5mpy-0.2.2/ch5mpy/np.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy/objects/dataset.py` & `ch5mpy-0.2.2/ch5mpy/objects/dataset.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy/objects/group.py` & `ch5mpy-0.2.2/ch5mpy/objects/group.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy/objects/object.py` & `ch5mpy-0.2.2/ch5mpy/objects/object.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy/objects/pickle.py` & `ch5mpy-0.2.2/ch5mpy/objects/pickle.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy/options.py` & `ch5mpy-0.2.2/ch5mpy/options.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy/read.py` & `ch5mpy-0.2.2/ch5mpy/read.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy/utils.py` & `ch5mpy-0.2.2/ch5mpy/utils.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy/write.py` & `ch5mpy-0.2.2/ch5mpy/write.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/ch5mpy.egg-info/PKG-INFO` & `ch5mpy-0.2.2/ch5mpy.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ch5mpy
-Version: 0.2.1
+Version: 0.2.2
 Summary: Collection of helper tools for reading or writing to h5 files using the h5py library.
 Author-email: Matteo Bouvier <m.bouvier@vidium-solutions.com>
 Maintainer-email: Matteo Bouvier <m.bouvier@vidium-solutions.com>
 License: CeCILL-B FREE SOFTWARE LICENSE AGREEMENT
         
         
             Notice
```

### Comparing `ch5mpy-0.2.1/ch5mpy.egg-info/SOURCES.txt` & `ch5mpy-0.2.2/ch5mpy.egg-info/SOURCES.txt`

 * *Files 2% similar despite different names*

```diff
@@ -6,14 +6,15 @@
 ch5mpy/attributes.py
 ch5mpy/dict.py
 ch5mpy/list.py
 ch5mpy/memory_size.py
 ch5mpy/names.py
 ch5mpy/np.py
 ch5mpy/options.py
+ch5mpy/py.typed
 ch5mpy/read.py
 ch5mpy/utils.py
 ch5mpy/write.py
 ch5mpy.egg-info/PKG-INFO
 ch5mpy.egg-info/SOURCES.txt
 ch5mpy.egg-info/dependency_links.txt
 ch5mpy.egg-info/requires.txt
```

### Comparing `ch5mpy-0.2.1/pyproject.toml` & `ch5mpy-0.2.2/pyproject.toml`

 * *Files 4% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 [build-system]
 requires = ["setuptools"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "ch5mpy"
 description = "Collection of helper tools for reading or writing to h5 files using the h5py library."
-version = "0.2.1"
+version = "0.2.2"
 requires-python = ">=3.7"
 license = {file = "LICENSE"}
 authors = [
     {name = "Matteo Bouvier", email = "m.bouvier@vidium-solutions.com"}
 ]
 maintainers = [
     {name = "Matteo Bouvier", email = "m.bouvier@vidium-solutions.com"}
@@ -55,14 +55,17 @@
 
 [tool.setuptools.packages.find]
 include = [
     "ch5mpy*",
     "ch5mpy.indexing"
 ]
 
+[tool.setuptools.package-data]
+"ch5mpy" = ["py.typed"]
+
 [tool.vulture]
 exclude = ["np.py"]
 ignore_decorators = ["@implements"]
 paths = ["ch5mpy", "vulture_whitelist.py"]
 
 [tool.ruff]
 line-length = 120
```

### Comparing `ch5mpy-0.2.1/tests/test_array_creation.py` & `ch5mpy-0.2.2/tests/test_array_creation.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/tests/test_array_repr.py` & `ch5mpy-0.2.2/tests/test_array_repr.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/tests/test_chunked_array.py` & `ch5mpy-0.2.2/tests/test_chunked_array.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/tests/test_complex_object_h5array.py` & `ch5mpy-0.2.2/tests/test_complex_object_h5array.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/tests/test_full_slice.py` & `ch5mpy-0.2.2/tests/test_full_slice.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/tests/test_functions.py` & `ch5mpy-0.2.2/tests/test_functions.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/tests/test_get_chunks.py` & `ch5mpy-0.2.2/tests/test_get_chunks.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/tests/test_h5_list.py` & `ch5mpy-0.2.2/tests/test_h5_list.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/tests/test_h5array.py` & `ch5mpy-0.2.2/tests/test_h5array.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/tests/test_h5dict.py` & `ch5mpy-0.2.2/tests/test_h5dict.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/tests/test_pickle.py` & `ch5mpy-0.2.2/tests/test_pickle.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/tests/test_repeated_array.py` & `ch5mpy-0.2.2/tests/test_repeated_array.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/tests/test_selection.py` & `ch5mpy-0.2.2/tests/test_selection.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/tests/test_str_h5array.py` & `ch5mpy-0.2.2/tests/test_str_h5array.py`

 * *Files identical despite different names*

### Comparing `ch5mpy-0.2.1/tests/test_write.py` & `ch5mpy-0.2.2/tests/test_write.py`

 * *Files identical despite different names*


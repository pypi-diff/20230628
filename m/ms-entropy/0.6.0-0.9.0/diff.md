# Comparing `tmp/ms_entropy-0.6.0.tar.gz` & `tmp/ms_entropy-0.9.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ms_entropy-0.6.0.tar", last modified: Wed Jun  7 06:59:45 2023, max compression
+gzip compressed data, was "ms_entropy-0.9.0.tar", last modified: Wed Jun 28 06:34:13 2023, max compression
```

## Comparing `ms_entropy-0.6.0.tar` & `ms_entropy-0.9.0.tar`

### file list

```diff
@@ -1,36 +1,92 @@
-drwxrwxr-x   0 yli       (1000) yli       (1000)        0 2023-06-07 06:59:45.333669 ms_entropy-0.6.0/
--rw-rw-r--   0 yli       (1000) yli       (1000)    11357 2023-05-28 06:20:24.000000 ms_entropy-0.6.0/LICENSE
--rw-rw-r--   0 yli       (1000) yli       (1000)       68 2023-05-28 06:20:24.000000 ms_entropy-0.6.0/MANIFEST.in
--rw-rw-r--   0 yli       (1000) yli       (1000)      402 2023-06-07 06:59:45.333669 ms_entropy-0.6.0/PKG-INFO
--rw-rw-r--   0 yli       (1000) yli       (1000)     3503 2023-06-01 01:18:58.000000 ms_entropy-0.6.0/README.md
-drwxrwxr-x   0 yli       (1000) yli       (1000)        0 2023-06-07 06:59:45.329669 ms_entropy-0.6.0/ms_entropy/
--rw-rw-r--   0 yli       (1000) yli       (1000)      177 2023-05-28 06:20:24.000000 ms_entropy-0.6.0/ms_entropy/__init__.py
-drwxrwxr-x   0 yli       (1000) yli       (1000)        0 2023-06-07 06:59:45.329669 ms_entropy-0.6.0/ms_entropy/entropy_search/
--rw-rw-r--   0 yli       (1000) yli       (1000)      196 2023-05-28 06:20:24.000000 ms_entropy-0.6.0/ms_entropy/entropy_search/__init__.py
--rw-rw-r--   0 yli       (1000) yli       (1000)    20160 2023-05-28 06:20:24.000000 ms_entropy-0.6.0/ms_entropy/entropy_search/flash_entropy_search.py
--rw-rw-r--   0 yli       (1000) yli       (1000)    28753 2023-06-07 06:56:23.000000 ms_entropy-0.6.0/ms_entropy/entropy_search/flash_entropy_search_core.py
--rw-rw-r--   0 yli       (1000) yli       (1000)    17592 2023-06-07 06:58:09.000000 ms_entropy-0.6.0/ms_entropy/entropy_search/flash_entropy_search_core_low_memory.py
-drwxrwxr-x   0 yli       (1000) yli       (1000)        0 2023-06-07 06:59:45.333669 ms_entropy-0.6.0/ms_entropy/file_io/
--rw-rw-r--   0 yli       (1000) yli       (1000)       62 2023-05-28 06:20:24.000000 ms_entropy-0.6.0/ms_entropy/file_io/__init__.py
--rw-rw-r--   0 yli       (1000) yli       (1000)     2047 2023-05-28 06:20:24.000000 ms_entropy-0.6.0/ms_entropy/file_io/lbm2_file.py
--rw-rw-r--   0 yli       (1000) yli       (1000)     1728 2023-05-28 06:20:51.000000 ms_entropy-0.6.0/ms_entropy/file_io/mgf_file.py
--rw-rw-r--   0 yli       (1000) yli       (1000)     1930 2023-05-28 06:20:24.000000 ms_entropy-0.6.0/ms_entropy/file_io/msp_file.py
--rw-rw-r--   0 yli       (1000) yli       (1000)     3916 2023-05-28 06:20:24.000000 ms_entropy-0.6.0/ms_entropy/file_io/mzml_file.py
--rw-rw-r--   0 yli       (1000) yli       (1000)      920 2023-05-28 06:20:24.000000 ms_entropy-0.6.0/ms_entropy/file_io/shared.py
--rw-rw-r--   0 yli       (1000) yli       (1000)     5722 2023-05-28 06:20:24.000000 ms_entropy-0.6.0/ms_entropy/file_io/spec_file.py
-drwxrwxr-x   0 yli       (1000) yli       (1000)        0 2023-06-07 06:59:45.333669 ms_entropy-0.6.0/ms_entropy/tools/
--rw-rw-r--   0 yli       (1000) yli       (1000)      118 2023-05-28 06:20:24.000000 ms_entropy-0.6.0/ms_entropy/tools/__init__.py
--rw-rw-r--   0 yli       (1000) yli       (1000)   903746 2023-05-28 06:20:24.000000 ms_entropy-0.6.0/ms_entropy/tools/fast_entropy.c
--rw-rw-r--   0 yli       (1000) yli       (1000)     3183 2023-05-28 06:20:24.000000 ms_entropy-0.6.0/ms_entropy/tools/fast_entropy.pyx
--rw-rw-r--   0 yli       (1000) yli       (1000)   895888 2023-05-28 06:20:24.000000 ms_entropy-0.6.0/ms_entropy/tools/fast_spectrum.c
--rw-rw-r--   0 yli       (1000) yli       (1000)     4978 2023-05-28 06:20:24.000000 ms_entropy-0.6.0/ms_entropy/tools/fast_spectrum.pyx
--rw-rw-r--   0 yli       (1000) yli       (1000)     4318 2023-05-28 06:20:24.000000 ms_entropy-0.6.0/ms_entropy/tools/tools.py
-drwxrwxr-x   0 yli       (1000) yli       (1000)        0 2023-06-07 06:59:45.333669 ms_entropy-0.6.0/ms_entropy.egg-info/
--rw-rw-r--   0 yli       (1000) yli       (1000)      402 2023-06-07 06:59:45.000000 ms_entropy-0.6.0/ms_entropy.egg-info/PKG-INFO
--rw-rw-r--   0 yli       (1000) yli       (1000)     1404 2023-06-07 06:59:45.000000 ms_entropy-0.6.0/ms_entropy.egg-info/SOURCES.txt
--rw-rw-r--   0 yli       (1000) yli       (1000)        1 2023-06-07 06:59:45.000000 ms_entropy-0.6.0/ms_entropy.egg-info/dependency_links.txt
--rw-rw-r--   0 yli       (1000) yli       (1000)       86 2023-06-07 06:59:45.000000 ms_entropy-0.6.0/ms_entropy.egg-info/requires.txt
--rw-rw-r--   0 yli       (1000) yli       (1000)       11 2023-06-07 06:59:45.000000 ms_entropy-0.6.0/ms_entropy.egg-info/top_level.txt
--rw-rw-r--   0 yli       (1000) yli       (1000)      111 2023-05-28 06:20:24.000000 ms_entropy-0.6.0/pyproject.toml
--rw-rw-r--   0 yli       (1000) yli       (1000)      128 2023-06-07 06:59:45.333669 ms_entropy-0.6.0/setup.cfg
--rw-rw-r--   0 yli       (1000) yli       (1000)     1683 2023-06-07 06:59:13.000000 ms_entropy-0.6.0/setup.py
+drwxrwxr-x   0 yli       (1000) yli       (1000)        0 2023-06-28 06:34:13.229867 ms_entropy-0.9.0/
+-rw-rw-r--   0 yli       (1000) yli       (1000)    11357 2023-06-03 23:52:00.000000 ms_entropy-0.9.0/LICENSE
+-rw-rw-r--   0 yli       (1000) yli       (1000)      134 2023-06-26 23:08:47.000000 ms_entropy-0.9.0/MANIFEST.in
+-rw-rw-r--   0 yli       (1000) yli       (1000)    18594 2023-06-28 06:34:13.229867 ms_entropy-0.9.0/PKG-INFO
+-rw-rw-r--   0 yli       (1000) yli       (1000)     4796 2023-06-27 21:19:08.000000 ms_entropy-0.9.0/README.md
+drwxrwxr-x   0 yli       (1000) yli       (1000)        0 2023-06-28 06:34:13.217867 ms_entropy-0.9.0/docs/
+drwxrwxr-x   0 yli       (1000) yli       (1000)        0 2023-06-28 06:34:13.221867 ms_entropy-0.9.0/docs/source/
+-rw-rw-r--   0 yli       (1000) yli       (1000)     1466 2023-06-27 00:52:28.000000 ms_entropy-0.9.0/docs/source/conf.py
+drwxrwxr-x   0 yli       (1000) yli       (1000)        0 2023-06-28 06:34:13.221867 ms_entropy-0.9.0/examples/
+-rw-rw-r--   0 yli       (1000) yli       (1000)     3135 2023-06-27 16:58:06.000000 ms_entropy-0.9.0/examples/example-2.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)     1935 2023-06-27 16:58:06.000000 ms_entropy-0.9.0/examples/example-multiple_cores.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)     9619 2023-06-27 16:58:06.000000 ms_entropy-0.9.0/examples/example-search_mona-with_pickle_functions.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)     9931 2023-06-27 16:58:41.000000 ms_entropy-0.9.0/examples/example-search_mona-with_read_write_functions-low_memory_usage.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)     9932 2023-06-27 16:58:06.000000 ms_entropy-0.9.0/examples/example-search_mona-with_read_write_functions.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)     3200 2023-06-27 16:58:06.000000 ms_entropy-0.9.0/examples/example-with_individual_search_function.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)     1491 2023-06-27 16:58:06.000000 ms_entropy-0.9.0/examples/example.py
+drwxrwxr-x   0 yli       (1000) yli       (1000)        0 2023-06-28 06:34:13.221867 ms_entropy-0.9.0/ms_entropy/
+-rw-rw-r--   0 yli       (1000) yli       (1000)      291 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/ms_entropy/__init__.py
+drwxrwxr-x   0 yli       (1000) yli       (1000)        0 2023-06-28 06:34:13.229867 ms_entropy-0.9.0/ms_entropy/entropy_search/
+-rw-rw-r--   0 yli       (1000) yli       (1000)      196 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/ms_entropy/entropy_search/__init__.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)     1514 2023-06-23 05:11:55.000000 ms_entropy-0.9.0/ms_entropy/entropy_search/fast_flash_entropy_search.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)   878020 2023-06-26 23:43:24.000000 ms_entropy-0.9.0/ms_entropy/entropy_search/fast_flash_entropy_search_cpython.c
+-rw-rw-r--   0 yli       (1000) yli       (1000)     1538 2023-06-23 05:36:10.000000 ms_entropy-0.9.0/ms_entropy/entropy_search/fast_flash_entropy_search_cpython.pyx
+-rw-rw-r--   0 yli       (1000) yli       (1000)    20160 2023-06-24 00:32:13.000000 ms_entropy-0.9.0/ms_entropy/entropy_search/flash_entropy_search.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)    29246 2023-06-24 00:31:43.000000 ms_entropy-0.9.0/ms_entropy/entropy_search/flash_entropy_search_core.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)    17592 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/ms_entropy/entropy_search/flash_entropy_search_core_low_memory.py
+drwxrwxr-x   0 yli       (1000) yli       (1000)        0 2023-06-28 06:34:13.225867 ms_entropy-0.9.0/ms_entropy/file_io/
+-rw-rw-r--   0 yli       (1000) yli       (1000)       62 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/ms_entropy/file_io/__init__.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)     2047 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/ms_entropy/file_io/lbm2_file.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)     1728 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/ms_entropy/file_io/mgf_file.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)     1930 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/ms_entropy/file_io/msp_file.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)     3916 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/ms_entropy/file_io/mzml_file.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)      920 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/ms_entropy/file_io/shared.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)     5722 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/ms_entropy/file_io/spec_file.py
+drwxrwxr-x   0 yli       (1000) yli       (1000)        0 2023-06-28 06:34:13.225867 ms_entropy-0.9.0/ms_entropy/pipe/
+-rw-rw-r--   0 yli       (1000) yli       (1000)      498 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/ms_entropy/pipe/__init__.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)      200 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/ms_entropy/pipe/df.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)     4241 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/ms_entropy/pipe/entropy.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)     1324 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/ms_entropy/pipe/functions.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)      153 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/ms_entropy/pipe/pandas.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)      974 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/ms_entropy/pipe/pipe.py
+drwxrwxr-x   0 yli       (1000) yli       (1000)        0 2023-06-28 06:34:13.229867 ms_entropy-0.9.0/ms_entropy/spectra/
+-rw-rw-r--   0 yli       (1000) yli       (1000)    10932 2023-06-22 23:38:30.000000 ms_entropy-0.9.0/ms_entropy/spectra/CleanSpectrum.c
+-rw-rw-r--   0 yli       (1000) yli       (1000)     3394 2023-06-22 23:23:29.000000 ms_entropy-0.9.0/ms_entropy/spectra/CleanSpectrum.h
+-rw-rw-r--   0 yli       (1000) yli       (1000)     5571 2023-06-22 22:43:47.000000 ms_entropy-0.9.0/ms_entropy/spectra/SpectralEntropy.c
+-rw-rw-r--   0 yli       (1000) yli       (1000)     4812 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/ms_entropy/spectra/SpectralEntropy.h
+-rw-rw-r--   0 yli       (1000) yli       (1000)      487 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/ms_entropy/spectra/__init__.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)    10465 2023-06-27 21:28:00.000000 ms_entropy-0.9.0/ms_entropy/spectra/entropy.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)   341244 2023-06-26 23:43:24.000000 ms_entropy-0.9.0/ms_entropy/spectra/entropy_cython.c
+-rw-rw-r--   0 yli       (1000) yli       (1000)    11187 2023-06-22 23:00:47.000000 ms_entropy-0.9.0/ms_entropy/spectra/entropy_cython.pyx
+-rw-rw-r--   0 yli       (1000) yli       (1000)    11241 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/ms_entropy/spectra/entropy_numba.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)     8756 2023-06-24 00:27:09.000000 ms_entropy-0.9.0/ms_entropy/spectra/tools.py
+drwxrwxr-x   0 yli       (1000) yli       (1000)        0 2023-06-28 06:34:13.229867 ms_entropy-0.9.0/ms_entropy.egg-info/
+-rw-rw-r--   0 yli       (1000) yli       (1000)    18594 2023-06-28 06:34:13.000000 ms_entropy-0.9.0/ms_entropy.egg-info/PKG-INFO
+-rw-rw-r--   0 yli       (1000) yli       (1000)     3582 2023-06-28 06:34:13.000000 ms_entropy-0.9.0/ms_entropy.egg-info/SOURCES.txt
+-rw-rw-r--   0 yli       (1000) yli       (1000)        1 2023-06-28 06:34:13.000000 ms_entropy-0.9.0/ms_entropy.egg-info/dependency_links.txt
+-rw-rw-r--   0 yli       (1000) yli       (1000)       81 2023-06-28 06:34:13.000000 ms_entropy-0.9.0/ms_entropy.egg-info/requires.txt
+-rw-rw-r--   0 yli       (1000) yli       (1000)       53 2023-06-28 06:34:13.000000 ms_entropy-0.9.0/ms_entropy.egg-info/top_level.txt
+-rw-rw-r--   0 yli       (1000) yli       (1000)     1142 2023-06-28 05:44:44.000000 ms_entropy-0.9.0/pyproject.toml
+-rw-rw-r--   0 yli       (1000) yli       (1000)       63 2023-06-28 06:34:13.229867 ms_entropy-0.9.0/setup.cfg
+-rw-rw-r--   0 yli       (1000) yli       (1000)     1108 2023-06-27 00:22:29.000000 ms_entropy-0.9.0/setup.py
+drwxrwxr-x   0 yli       (1000) yli       (1000)        0 2023-06-28 06:34:13.225867 ms_entropy-0.9.0/tests/
+drwxrwxr-x   0 yli       (1000) yli       (1000)        0 2023-06-28 06:34:13.225867 ms_entropy-0.9.0/tests/ms_entropy/
+-rw-rw-r--   0 yli       (1000) yli       (1000)      291 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/tests/ms_entropy/__init__.py
+drwxrwxr-x   0 yli       (1000) yli       (1000)        0 2023-06-28 06:34:13.225867 ms_entropy-0.9.0/tests/ms_entropy/entropy_search/
+-rw-rw-r--   0 yli       (1000) yli       (1000)      196 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/tests/ms_entropy/entropy_search/__init__.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)     1514 2023-06-23 05:11:55.000000 ms_entropy-0.9.0/tests/ms_entropy/entropy_search/fast_flash_entropy_search.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)    20160 2023-06-24 00:32:13.000000 ms_entropy-0.9.0/tests/ms_entropy/entropy_search/flash_entropy_search.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)    29246 2023-06-24 00:31:43.000000 ms_entropy-0.9.0/tests/ms_entropy/entropy_search/flash_entropy_search_core.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)    17592 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/tests/ms_entropy/entropy_search/flash_entropy_search_core_low_memory.py
+drwxrwxr-x   0 yli       (1000) yli       (1000)        0 2023-06-28 06:34:13.225867 ms_entropy-0.9.0/tests/ms_entropy/file_io/
+-rw-rw-r--   0 yli       (1000) yli       (1000)       62 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/tests/ms_entropy/file_io/__init__.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)     2047 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/tests/ms_entropy/file_io/lbm2_file.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)     1728 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/tests/ms_entropy/file_io/mgf_file.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)     1930 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/tests/ms_entropy/file_io/msp_file.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)     3916 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/tests/ms_entropy/file_io/mzml_file.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)      920 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/tests/ms_entropy/file_io/shared.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)     5722 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/tests/ms_entropy/file_io/spec_file.py
+drwxrwxr-x   0 yli       (1000) yli       (1000)        0 2023-06-28 06:34:13.225867 ms_entropy-0.9.0/tests/ms_entropy/pipe/
+-rw-rw-r--   0 yli       (1000) yli       (1000)      498 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/tests/ms_entropy/pipe/__init__.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)      200 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/tests/ms_entropy/pipe/df.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)     4241 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/tests/ms_entropy/pipe/entropy.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)     1324 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/tests/ms_entropy/pipe/functions.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)      153 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/tests/ms_entropy/pipe/pandas.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)      974 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/tests/ms_entropy/pipe/pipe.py
+drwxrwxr-x   0 yli       (1000) yli       (1000)        0 2023-06-28 06:34:13.225867 ms_entropy-0.9.0/tests/ms_entropy/spectra/
+-rw-rw-r--   0 yli       (1000) yli       (1000)      487 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/tests/ms_entropy/spectra/__init__.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)    10465 2023-06-27 21:28:00.000000 ms_entropy-0.9.0/tests/ms_entropy/spectra/entropy.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)    11241 2023-06-21 04:52:11.000000 ms_entropy-0.9.0/tests/ms_entropy/spectra/entropy_numba.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)     8756 2023-06-24 00:27:09.000000 ms_entropy-0.9.0/tests/ms_entropy/spectra/tools.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)     9010 2023-06-22 23:01:26.000000 ms_entropy-0.9.0/tests/test_entropy.py
+-rw-rw-r--   0 yli       (1000) yli       (1000)     4977 2023-06-27 08:09:27.000000 ms_entropy-0.9.0/tests/test_entropy_search.py
```

### Comparing `ms_entropy-0.6.0/LICENSE` & `ms_entropy-0.9.0/LICENSE`

 * *Files identical despite different names*

### Comparing `ms_entropy-0.6.0/ms_entropy/entropy_search/flash_entropy_search.py` & `ms_entropy-0.9.0/ms_entropy/entropy_search/flash_entropy_search.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,15 +1,14 @@
 #!/usr/bin/env python3
 import numpy as np
-import copy
 import pickle
 from pathlib import Path
 from .flash_entropy_search_core import FlashEntropySearchCore
 from .flash_entropy_search_core_low_memory import FlashEntropySearchCoreLowMemory
-from ..tools import clean_spectrum
+from ..spectra import clean_spectrum
 
 
 class FlashEntropySearch:
     def __init__(self,  max_ms2_tolerance_in_da=0.024, mz_index_step=0.0001, low_memory=False, path_data=None):
         self.precursor_mz_array = np.zeros(0, dtype=np.float32)
         self.low_memory = low_memory
         if low_memory:
@@ -85,33 +84,33 @@
 
     def clean_spectrum_for_search(self,
                                   precursor_mz,
                                   peaks,
                                   precursor_ions_removal_da: float = 1.6,
                                   noise_threshold=0.01,
                                   min_ms2_difference_in_da: float = 0.05,
-                                  max_peak_num: int = None):
+                                  max_peak_num: int = 0):
         """
         Clean the MS/MS spectrum, need to be called before any search.
 
         :param precursor_mz:    The precursor m/z of the spectrum.
         :param peaks:           The peaks of the spectrum, should be a list or numpy array with shape (N, 2), N is the number of peaks. The format of the peaks is [[mz1, intensity1], [mz2, intensity2], ...].
         :param precursor_ions_removal_da:   The ions with m/z larger than precursor_mz - precursor_ions_removal_da will be removed.
                                             Default is 1.6.
         :param noise_threshold: The intensity threshold for removing the noise peaks. The peaks with intensity smaller than noise_threshold * max(intensity)
                                 will be removed. Default is 0.01.
         :param min_ms2_difference_in_da:    The minimum difference between two peaks in the MS/MS spectrum. Default is 0.05.
-        :param max_peak_num:    The maximum number of peaks in the MS/MS spectrum. Default is None, which means no limit.
+        :param max_peak_num:    The maximum number of peaks in the MS/MS spectrum. Default is 0, which means no limit.
         """
         if precursor_ions_removal_da is not None:
             max_mz = precursor_mz - precursor_ions_removal_da
         else:
             max_mz = None
-        return clean_spectrum(spectrum=peaks,
-                              min_mz=None,
+        return clean_spectrum(peaks=peaks,
+                              min_mz=-1,
                               max_mz=max_mz,
                               noise_threshold=noise_threshold,
                               min_ms2_difference_in_da=min_ms2_difference_in_da,
                               max_peak_num=max_peak_num,
                               normalize_intensity=True)
 
     def search(self,
@@ -142,15 +141,15 @@
 
         :return:    A dictionary with the search results. The keys are "identity_search", "open_search", "neutral_loss_search", "hybrid_search", and the values are the search results for each method.
         """
         if precursor_ions_removal_da is not None:
             max_mz = precursor_mz - precursor_ions_removal_da
         else:
             max_mz = None
-        peaks = clean_spectrum(spectrum=peaks,
+        peaks = clean_spectrum(peaks=peaks,
                                min_mz=None,
                                max_mz=max_mz,
                                noise_threshold=noise_threshold,
                                min_ms2_difference_in_da=min_ms2_difference_in_da,
                                max_peak_num=max_peak_num,
                                normalize_intensity=True)
         if method == "all":
@@ -183,15 +182,15 @@
 
     def build_index(self,
                     all_spectra_list: list = None,
                     max_indexed_mz: float = 1500.00005,
                     precursor_ions_removal_da: float = 1.6,
                     noise_threshold=0.01,
                     min_ms2_difference_in_da: float = 0.05,
-                    max_peak_num: int = None,
+                    max_peak_num: int = 0,
                     clean_spectra: bool = True):
         """
         Set the library spectra for entropy search.
 
         The `all_spectra_list` must be a list of dictionaries, with each dictionary containing at least two keys: "precursor_mz" and "peaks". 
         The dictionary should be in the format of {"precursor_mz": precursor_mz, "peaks": peaks, ...}, All keys in the dictionary, except "peaks,"
         will be saved as the metadata and can be accessed using the  __getitem__ function (e.g. entropy_search[0] returns the metadata for the
@@ -207,15 +206,15 @@
 
         :param max_indexed_mz: The maximum m/z value that will be indexed. Default is 1500.00005.
         :param precursor_ions_removal_da:   The ions with m/z larger than precursor_mz - precursor_ions_removal_da will be removed.
                                             Default is 1.6.
         :param noise_threshold: The intensity threshold for removing the noise peaks. The peaks with intensity smaller than noise_threshold * max(intensity)
                                 will be removed. Default is 0.01.
         :param min_ms2_difference_in_da:    The minimum difference between two peaks in the MS/MS spectrum. Default is 0.05.
-        :param max_peak_num:    The maximum number of peaks in the MS/MS spectrum. Default is None, which means no limit.
+        :param max_peak_num:    The maximum number of peaks in the MS/MS spectrum. Default is 0, which means no limit.
         :param clean_spectra:   If True, the spectra will be cleaned before indexing. Default is True. If ALL spectra in the library are pre-cleaned with the
                                 function `clean_spectrum` or `clean_spectrum_for_search`, set this parameter to False. ALWAYS set this parameter to true if
                                 the spectra are not pre-prepossessed with the function `clean_spectrum` or `clean_spectrum_for_search`.
 
         :return:    If the all_spectra_list is provided, this function will return the sorted spectra list.
         """
 
@@ -300,17 +299,17 @@
             path_data = self.entropy_search.path_data
         else:
             path_data = Path(path_data)
 
         path_data = Path(path_data)
         path_data.mkdir(parents=True, exist_ok=True)
 
-        self.precursor_mz_array.tofile(path_data/"precursor_mz.npy")
-        self.metadata.tofile(path_data/"metadata.npy")
-        self.metadata_loc.tofile(path_data/"metadata_loc.npy")
+        self.precursor_mz_array.tofile(str(path_data/"precursor_mz.npy"))
+        self.metadata.tofile(str(path_data/"metadata.npy"))
+        self.metadata_loc.tofile(str(path_data/"metadata_loc.npy"))
 
         self.entropy_search.write(path_data)
 
     def read(self, path_data=None):
         """
         Read the MS/MS spectral library from a file.
 
@@ -323,17 +322,17 @@
             path_data = Path(path_data)
 
         if self.low_memory:
             self.precursor_mz_array = np.memmap(path_data/"precursor_mz.npy", dtype=np.float32, mode="r")
             self.metadata = np.memmap(path_data/"metadata.npy", dtype=np.uint8, mode="r")
             self.metadata_loc = np.memmap(path_data/"metadata_loc.npy", dtype=np.uint64, mode="r")
         else:
-            self.precursor_mz_array = np.fromfile(path_data/"precursor_mz.npy", dtype=np.float32)
-            self.metadata = np.fromfile(path_data/"metadata.npy", dtype=np.uint8)
-            self.metadata_loc = np.fromfile(path_data/"metadata_loc.npy", dtype=np.uint64)
+            self.precursor_mz_array = np.fromfile(str(path_data/"precursor_mz.npy"), dtype=np.float32)
+            self.metadata = np.fromfile(str(path_data/"metadata.npy"), dtype=np.uint8)
+            self.metadata_loc = np.fromfile(str(path_data/"metadata_loc.npy"), dtype=np.uint64)
 
         return self.entropy_search.read(path_data)
 
     def save_memory_for_multiprocessing(self):
         """
         Save the memory for multiprocessing. This function will move the numpy array in the index to shared memory in order to save memory.
```

### Comparing `ms_entropy-0.6.0/ms_entropy/entropy_search/flash_entropy_search_core.py` & `ms_entropy-0.9.0/ms_entropy/entropy_search/flash_entropy_search_core.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,23 +1,24 @@
 #!/usr/bin/env python3
 import json
 import numpy as np
 from pathlib import Path
 from functools import reduce
 import multiprocessing
-from ..tools import apply_weight_to_intensity, entropy_similarity_search_fast
+from ..spectra import apply_weight_to_intensity
+from .fast_flash_entropy_search import entropy_similarity_search_identity
 
 
 class FlashEntropySearchCore:
     def __init__(self, path_data=None, max_ms2_tolerance_in_da=0.024, mz_index_step=0.0001) -> None:
         """
         Initialize the EntropySearch class.
         :param path_array: The path array of the index files.
         :param max_ms2_tolerance_in_da: The maximum MS2 tolerance used when searching the MS/MS spectra, in Dalton. Default is 0.024.
-        :param mz_index_step:   The step size of the m/z index, in Dalton. Default is 0.0001. 
+        :param mz_index_step:   The step size of the m/z index, in Dalton. Default is 0.0001.
                                 The smaller the step size, the faster the search, but the larger the index size and longer the index building time.
         """
         self.mz_index_step = mz_index_step
         self._init_for_multiprocessing = False
         self.max_ms2_tolerance_in_da = max_ms2_tolerance_in_da
 
         self.total_spectra_num = 0
@@ -25,55 +26,86 @@
         self.index = []
 
         if path_data:
             self.path_data = Path(path_data)
         else:
             self.path_data = None
 
-        self.index_names = ['all_ions_mz_idx_start', 'all_ions_mz', 'all_ions_intensity', 'all_ions_spec_idx',
-                            'all_nl_mass_idx_start', 'all_nl_mass', 'all_nl_intensity', 'all_nl_spec_idx', 'all_ions_idx_for_nl']
+        self.index_names = [
+            "all_ions_mz_idx_start",
+            "all_ions_mz",
+            "all_ions_intensity",
+            "all_ions_spec_idx",
+            "all_nl_mass_idx_start",
+            "all_nl_mass",
+            "all_nl_intensity",
+            "all_nl_spec_idx",
+            "all_ions_idx_for_nl",
+        ]
         self.index_dtypes = {
-            'all_ions_mz_idx_start': np.int64, 'all_ions_mz': np.float32, 'all_ions_intensity': np.float32, 'all_ions_spec_idx': np.uint32,
-            'all_nl_mass_idx_start': np.int64, 'all_nl_mass': np.float32, 'all_nl_intensity': np.float32, 'all_nl_spec_idx': np.uint32,
-            'all_ions_idx_for_nl': np.uint64}
-
-    def search(self,
-               method="open", target="cpu",
-               precursor_mz=None, peaks=None, ms2_tolerance_in_da=0.02,
-               search_type=0, search_spectra_idx_min=0, search_spectra_idx_max=0, search_array=None):
+            "all_ions_mz_idx_start": np.int64,
+            "all_ions_mz": np.float32,
+            "all_ions_intensity": np.float32,
+            "all_ions_spec_idx": np.uint32,
+            "all_nl_mass_idx_start": np.int64,
+            "all_nl_mass": np.float32,
+            "all_nl_intensity": np.float32,
+            "all_nl_spec_idx": np.uint32,
+            "all_ions_idx_for_nl": np.uint64,
+        }
+
+    def search(
+        self,
+        method="open",
+        target="cpu",
+        precursor_mz=None,
+        peaks=None,
+        ms2_tolerance_in_da=0.02,
+        search_type=0,
+        search_spectra_idx_min=0,
+        search_spectra_idx_max=0,
+    ):
         """
         Perform identity-, open- or neutral loss search on the MS/MS spectra library.
 
-        :param method:  The search method, can be "open" or "neutral_loss". 
+        :param method:  The search method, can be "open" or "neutral_loss".
                         Set it to "open" for identity search and open search, set it to "neutral_loss" for neutral loss search.
         :param target:  The target to search, can be "cpu" or "gpu".
         :param precursor_mz:    The precursor m/z of the query MS/MS spectrum, required for neutral loss search.
         :param peaks:   The peaks of the query MS/MS spectrum. The peaks need to be precleaned by "clean_spectrum" function.
         :param ms2_tolerance_in_da: The MS2 tolerance used when searching the MS/MS spectra, in Dalton. Default is 0.02.
-        :param search_type: The search type, can be 0, 1 or 2. 
+        :param search_type: The search type, can be 0, 1 or 2.
                             Set it to 0 for searching the whole MS/MS spectra library.
-                            Set it to 1 for searching a range of the MS/MS spectra library, 
-                            set it to 2 for searching only when search_array is True (or 1).
+                            Set it to 1 for searching a range of the MS/MS spectra library,
         :param search_spectra_idx_min:  The minimum index of the MS/MS spectra to search, required when search_type is 1.
         :param search_spectra_idx_max:  The maximum index of the MS/MS spectra to search, required when search_type is 1.
-        :param search_array:    The array of the MS/MS spectra to search, required when search_type is 2.
         """
         if not self.index:
             return np.zeros(0, dtype=np.float32)
         if len(peaks) == 0:
             return np.zeros(self.total_spectra_num, dtype=np.float32)
 
         # Check peaks
         assert ms2_tolerance_in_da <= self.max_ms2_tolerance_in_da, "The MS2 tolerance is larger than the maximum MS2 tolerance."
-        assert abs(np.sum(peaks[:, 1])-1) < 1e-4, "The peaks are not normalized to sum to 1."
-        assert peaks.shape[0] <= 1 or np.min(peaks[1:, 0] - peaks[:-1, 0]) > self.max_ms2_tolerance_in_da * 2, \
-            "The peaks array should be sorted by m/z, and the m/z difference between two adjacent peaks should be larger than 2 * max_ms2_tolerance_in_da."
-        all_ions_mz_idx_start, all_ions_mz, all_ions_intensity, all_ions_spec_idx, \
-            all_nl_mass_idx_start, all_nl_mass, all_nl_intensity, all_nl_spec_idx, all_ions_idx_for_nl = self.index
-        index_number_in_one_da = int(1/self.mz_index_step)
+        assert abs(np.sum(peaks[:, 1]) - 1) < 1e-4, "The peaks are not normalized to sum to 1."
+        assert (
+            peaks.shape[0] <= 1 or np.min(peaks[1:, 0] - peaks[:-1, 0]) > self.max_ms2_tolerance_in_da * 2
+        ), "The peaks array should be sorted by m/z, and the m/z difference between two adjacent peaks should be larger than 2 * max_ms2_tolerance_in_da."
+        (
+            all_ions_mz_idx_start,
+            all_ions_mz,
+            all_ions_intensity,
+            all_ions_spec_idx,
+            all_nl_mass_idx_start,
+            all_nl_mass,
+            all_nl_intensity,
+            all_nl_spec_idx,
+            all_ions_idx_for_nl,
+        ) = self.index
+        index_number_in_one_da = int(1 / self.mz_index_step)
 
         # Prepare the query spectrum
         peaks = self._preprocess_peaks(peaks)
 
         # Prepare the library
         if method == "open":
             library_mz_idx_start = all_ions_mz_idx_start
@@ -88,53 +120,61 @@
             peaks[:, 0] = precursor_mz - peaks[:, 0]
 
         # Start searching
         if target == "cpu":
             entropy_similarity = np.zeros(self.total_spectra_num, dtype=np.float32)
         else:
             import cupy as cp
+
             entropy_transform = cp.ElementwiseKernel(
-                'T intensity_a, T intensity_b',
-                'T similarity',
-                '''T intensity_ab = intensity_a + intensity_b;
-                similarity = intensity_ab * log2f(intensity_ab) - intensity_a * log2f(intensity_a) - intensity_b * log2f(intensity_b);'''
+                "T intensity_a, T intensity_b",
+                "T similarity",
+                """T intensity_ab = intensity_a + intensity_b;
+                similarity = intensity_ab * log2f(intensity_ab) - intensity_a * log2f(intensity_a) - intensity_b * log2f(intensity_b);""",
             )
             entropy_similarity = cp.zeros(self.total_spectra_num, dtype=np.float32)
 
         # Go through all the peaks in the spectrum
         for mz_query, intensity_query in peaks:
             # Determine the mz index range
             product_mz_idx_min = self._find_location_from_array_with_index(
-                mz_query - ms2_tolerance_in_da, library_mz, library_mz_idx_start, 'left', index_number_in_one_da)
+                mz_query - ms2_tolerance_in_da, library_mz, library_mz_idx_start, "left", index_number_in_one_da
+            )
             product_mz_idx_max = self._find_location_from_array_with_index(
-                mz_query + ms2_tolerance_in_da, library_mz, library_mz_idx_start, 'right', index_number_in_one_da)
+                mz_query + ms2_tolerance_in_da, library_mz, library_mz_idx_start, "right", index_number_in_one_da
+            )
 
             if target == "cpu" and search_type == 0:
-                intensity_library = library_peaks_intensity[product_mz_idx_min: product_mz_idx_max]
-                modified_idx = library_spec_idx[product_mz_idx_min: product_mz_idx_max]
+                intensity_library = library_peaks_intensity[product_mz_idx_min:product_mz_idx_max]
+                modified_idx = library_spec_idx[product_mz_idx_min:product_mz_idx_max]
                 entropy_similarity[modified_idx] += self._score_peaks_with_cpu(intensity_query, intensity_library)
-            elif target == "cpu" and search_type != 0:
-                entropy_similarity_search_fast(product_mz_idx_min, product_mz_idx_max, intensity_query, entropy_similarity,
-                                               library_peaks_intensity, library_spec_idx,
-                                               search_type, search_spectra_idx_min, search_spectra_idx_max, search_array)
+            elif target == "cpu" and search_type == 1:
+                entropy_similarity_search_identity(
+                    product_mz_idx_min,
+                    product_mz_idx_max,
+                    intensity_query,
+                    entropy_similarity,
+                    library_peaks_intensity,
+                    library_spec_idx,
+                    search_spectra_idx_min,
+                    search_spectra_idx_max,
+                )
             elif target == "gpu":
-                intensity_library = cp.array(library_peaks_intensity[product_mz_idx_min: product_mz_idx_max])
+                intensity_library = cp.array(library_peaks_intensity[product_mz_idx_min:product_mz_idx_max])
                 modified_value = entropy_transform(intensity_library, intensity_query)
-                modified_idx = cp.array(library_spec_idx[product_mz_idx_min: product_mz_idx_max])
+                modified_idx = cp.array(library_spec_idx[product_mz_idx_min:product_mz_idx_max])
                 entropy_similarity.scatter_add(modified_idx, modified_value)
 
         if target == "cpu":
             return entropy_similarity
-        else:
+        elif target == "gpu":
             entropy_similarity = entropy_similarity.get()
             if search_type == 1:
                 entropy_similarity[:search_spectra_idx_min] = 0
                 entropy_similarity[search_spectra_idx_max:] = 0
-            elif search_type == 2:
-                entropy_similarity[np.bitwise_not(search_array)] = 0
             return entropy_similarity
 
     def search_hybrid(self, target="cpu", precursor_mz=None, peaks=None, ms2_tolerance_in_da=0.02):
         """
         Perform the hybrid search for the MS/MS spectra.
 
         :param target: The target to perform the search. "cpu" for CPU, "gpu" for GPU.
@@ -145,123 +185,142 @@
         if not self.index:
             return np.zeros(0, dtype=np.float32)
         if len(peaks) == 0:
             return np.zeros(self.total_spectra_num, dtype=np.float32)
 
         # Check peaks
         assert ms2_tolerance_in_da <= self.max_ms2_tolerance_in_da, "The MS2 tolerance is larger than the maximum MS2 tolerance."
-        assert abs(np.sum(peaks[:, 1])-1) < 1e-4, "The peaks are not normalized to sum to 1."
-        assert peaks.shape[0] <= 1 or np.min(peaks[1:, 0] - peaks[:-1, 0]) > self.max_ms2_tolerance_in_da * 2, \
-            "The peaks array should be sorted by m/z, and the m/z difference between two adjacent peaks should be larger than 2 * max_ms2_tolerance_in_da."
-        all_ions_mz_idx_start, all_ions_mz, all_ions_intensity, all_ions_spec_idx, \
-            all_nl_mass_idx_start, all_nl_mass, all_nl_intensity, all_nl_spec_idx, all_ions_idx_for_nl = self.index
-        index_number_in_one_da = int(1/self.mz_index_step)
+        assert abs(np.sum(peaks[:, 1]) - 1) < 1e-4, "The peaks are not normalized to sum to 1."
+        assert (
+            peaks.shape[0] <= 1 or np.min(peaks[1:, 0] - peaks[:-1, 0]) > self.max_ms2_tolerance_in_da * 2
+        ), "The peaks array should be sorted by m/z, and the m/z difference between two adjacent peaks should be larger than 2 * max_ms2_tolerance_in_da."
+        (
+            all_ions_mz_idx_start,
+            all_ions_mz,
+            all_ions_intensity,
+            all_ions_spec_idx,
+            all_nl_mass_idx_start,
+            all_nl_mass,
+            all_nl_intensity,
+            all_nl_spec_idx,
+            all_ions_idx_for_nl,
+        ) = self.index
+        index_number_in_one_da = int(1 / self.mz_index_step)
 
         # Prepare the query spectrum
         peaks = self._preprocess_peaks(peaks)
 
         # Go through all peak in the spectrum and determine the mz index range
         product_peak_match_idx_min = np.zeros(peaks.shape[0], dtype=np.uint64)
         product_peak_match_idx_max = np.zeros(peaks.shape[0], dtype=np.uint64)
         for peak_idx, (mz_query, _) in enumerate(peaks):
             # Determine the mz index range
             product_mz_idx_min = self._find_location_from_array_with_index(
-                mz_query - ms2_tolerance_in_da, all_ions_mz, all_ions_mz_idx_start, 'left', index_number_in_one_da)
+                mz_query - ms2_tolerance_in_da, all_ions_mz, all_ions_mz_idx_start, "left", index_number_in_one_da
+            )
             product_mz_idx_max = self._find_location_from_array_with_index(
-                mz_query + ms2_tolerance_in_da, all_ions_mz, all_ions_mz_idx_start, 'right', index_number_in_one_da)
+                mz_query + ms2_tolerance_in_da, all_ions_mz, all_ions_mz_idx_start, "right", index_number_in_one_da
+            )
 
             product_peak_match_idx_min[peak_idx] = product_mz_idx_min
             product_peak_match_idx_max[peak_idx] = product_mz_idx_max
 
         if target == "cpu":
             entropy_similarity = np.zeros(self.total_spectra_num, dtype=np.float32)
             # Go through all the peaks in the spectrum and calculate the entropy similarity
             for peak_idx, (mz, intensity) in enumerate(peaks):
                 ###############################################################
                 # Match the original product ion
                 product_mz_idx_min = product_peak_match_idx_min[peak_idx]
                 product_mz_idx_max = product_peak_match_idx_max[peak_idx]
 
                 # Calculate the entropy similarity for this matched peak
-                modified_idx_product = all_ions_spec_idx[product_mz_idx_min: product_mz_idx_max]
-                modified_value_product = self._score_peaks_with_cpu(intensity, all_ions_intensity[product_mz_idx_min: product_mz_idx_max])
+                modified_idx_product = all_ions_spec_idx[product_mz_idx_min:product_mz_idx_max]
+                modified_value_product = self._score_peaks_with_cpu(intensity, all_ions_intensity[product_mz_idx_min:product_mz_idx_max])
 
                 entropy_similarity[modified_idx_product] += modified_value_product
 
                 ###############################################################
                 # Match the neutral loss ions
-                mz_nl = precursor_mz-mz
+                mz_nl = precursor_mz - mz
                 # Determine the mz index range
                 neutral_loss_mz_idx_min = self._find_location_from_array_with_index(
-                    mz_nl - ms2_tolerance_in_da, all_nl_mass, all_nl_mass_idx_start, 'left', index_number_in_one_da)
+                    mz_nl - ms2_tolerance_in_da, all_nl_mass, all_nl_mass_idx_start, "left", index_number_in_one_da
+                )
                 neutral_loss_mz_idx_max = self._find_location_from_array_with_index(
-                    mz_nl + ms2_tolerance_in_da, all_nl_mass, all_nl_mass_idx_start, 'right', index_number_in_one_da)
+                    mz_nl + ms2_tolerance_in_da, all_nl_mass, all_nl_mass_idx_start, "right", index_number_in_one_da
+                )
 
                 # Calculate the entropy similarity for this matched peak
-                modified_idx_nl = all_nl_spec_idx[neutral_loss_mz_idx_min: neutral_loss_mz_idx_max]
-                modified_value_nl = self._score_peaks_with_cpu(intensity, all_nl_intensity[neutral_loss_mz_idx_min: neutral_loss_mz_idx_max])
+                modified_idx_nl = all_nl_spec_idx[neutral_loss_mz_idx_min:neutral_loss_mz_idx_max]
+                modified_value_nl = self._score_peaks_with_cpu(intensity, all_nl_intensity[neutral_loss_mz_idx_min:neutral_loss_mz_idx_max])
 
                 # Check if the neutral loss ion is already matched to other query peak as a product ion
-                nl_matched_product_ion_idx = all_ions_idx_for_nl[neutral_loss_mz_idx_min: neutral_loss_mz_idx_max]
-                s1 = np.searchsorted(product_peak_match_idx_min, nl_matched_product_ion_idx, side='right')
-                s2 = np.searchsorted(product_peak_match_idx_max-1, nl_matched_product_ion_idx, side='left')
+                nl_matched_product_ion_idx = all_ions_idx_for_nl[neutral_loss_mz_idx_min:neutral_loss_mz_idx_max]
+                s1 = np.searchsorted(product_peak_match_idx_min, nl_matched_product_ion_idx, side="right")
+                s2 = np.searchsorted(product_peak_match_idx_max - 1, nl_matched_product_ion_idx, side="left")
                 modified_value_nl[s1 > s2] = 0
 
                 # Check if this query peak is already matched to a product ion in the same library spectrum
                 duplicate_idx_in_nl = self._remove_duplicate_with_cpu(modified_idx_product, modified_idx_nl, self.total_spectra_num)
                 modified_value_nl[duplicate_idx_in_nl] = 0
 
                 entropy_similarity[modified_idx_nl] += modified_value_nl
             return entropy_similarity
 
         elif target == "gpu":
             import cupy as cp
+
             entropy_transform = cp.ElementwiseKernel(
-                'T intensity_a, T intensity_b',
-                'T similarity',
-                '''T intensity_ab = intensity_a + intensity_b;
-                similarity = intensity_ab * log2f(intensity_ab) - intensity_a * log2f(intensity_a) - intensity_b * log2f(intensity_b);'''
+                "T intensity_a, T intensity_b",
+                "T similarity",
+                """T intensity_ab = intensity_a + intensity_b;
+                similarity = intensity_ab * log2f(intensity_ab) - intensity_a * log2f(intensity_a) - intensity_b * log2f(intensity_b);""",
             )
             product_peak_match_idx_min_gpu = cp.array(product_peak_match_idx_min)
-            product_peak_match_idx_max_gpu = cp.array(product_peak_match_idx_max-1)
+            product_peak_match_idx_max_gpu = cp.array(product_peak_match_idx_max - 1)
 
             entropy_similarity_modification_list = []
             # Go through all the peaks in the spectrum and calculate the entropy similarity
             for peak_idx, (mz, intensity) in enumerate(peaks):
                 ###############################################################
                 # Match the original product ion
                 product_mz_idx_min = product_peak_match_idx_min[peak_idx]
                 product_mz_idx_max = product_peak_match_idx_max[peak_idx]
 
                 # Calculate the entropy similarity for this matched peak
-                modified_idx_product = all_ions_spec_idx[product_mz_idx_min: product_mz_idx_max]
-                modified_value_product = self._score_peaks_gpu(entropy_transform, intensity, cp.array(
-                    all_ions_intensity[product_mz_idx_min: product_mz_idx_max]))
+                modified_idx_product = all_ions_spec_idx[product_mz_idx_min:product_mz_idx_max]
+                modified_value_product = self._score_peaks_gpu(
+                    entropy_transform, intensity, cp.array(all_ions_intensity[product_mz_idx_min:product_mz_idx_max])
+                )
 
                 entropy_similarity_modification_list.append((modified_idx_product, modified_value_product.get()))
                 del modified_value_product
 
                 ###############################################################
                 # Match the neutral loss ions
-                mz_nl = precursor_mz-mz
+                mz_nl = precursor_mz - mz
                 # Determine the mz index range
                 neutral_loss_mz_idx_min = self._find_location_from_array_with_index(
-                    mz_nl - ms2_tolerance_in_da, all_nl_mass, all_nl_mass_idx_start, 'left', index_number_in_one_da)
+                    mz_nl - ms2_tolerance_in_da, all_nl_mass, all_nl_mass_idx_start, "left", index_number_in_one_da
+                )
                 neutral_loss_mz_idx_max = self._find_location_from_array_with_index(
-                    mz_nl + ms2_tolerance_in_da, all_nl_mass, all_nl_mass_idx_start, 'right', index_number_in_one_da)
+                    mz_nl + ms2_tolerance_in_da, all_nl_mass, all_nl_mass_idx_start, "right", index_number_in_one_da
+                )
 
                 # Calculate the entropy similarity for this matched peak
-                modified_idx_nl = all_nl_spec_idx[neutral_loss_mz_idx_min: neutral_loss_mz_idx_max]
-                modified_value_nl = self._score_peaks_gpu(entropy_transform, intensity, cp.array(
-                    all_nl_intensity[neutral_loss_mz_idx_min: neutral_loss_mz_idx_max]))
+                modified_idx_nl = all_nl_spec_idx[neutral_loss_mz_idx_min:neutral_loss_mz_idx_max]
+                modified_value_nl = self._score_peaks_gpu(
+                    entropy_transform, intensity, cp.array(all_nl_intensity[neutral_loss_mz_idx_min:neutral_loss_mz_idx_max])
+                )
 
                 # Check if the neutral loss ion is already matched to other query peak as a product ion
-                nl_matched_product_ion_idx = cp.array(all_ions_idx_for_nl[neutral_loss_mz_idx_min: neutral_loss_mz_idx_max])
-                s1 = cp.searchsorted(product_peak_match_idx_min_gpu, nl_matched_product_ion_idx, side='right')
-                s2 = cp.searchsorted(product_peak_match_idx_max_gpu, nl_matched_product_ion_idx, side='left')
+                nl_matched_product_ion_idx = cp.array(all_ions_idx_for_nl[neutral_loss_mz_idx_min:neutral_loss_mz_idx_max])
+                s1 = cp.searchsorted(product_peak_match_idx_min_gpu, nl_matched_product_ion_idx, side="right")
+                s2 = cp.searchsorted(product_peak_match_idx_max_gpu, nl_matched_product_ion_idx, side="left")
                 modified_value_nl[s1 > s2] = 0
 
                 # Check if this query peak is already matched to a product ion in the same library spectrum
                 duplicate_idx_in_nl = self._remove_duplicate_with_gpu(modified_idx_product, modified_idx_nl, self.total_spectra_num)
                 modified_value_nl[duplicate_idx_in_nl] = 0
 
                 entropy_similarity_modification_list.append((modified_idx_nl, modified_value_nl.get()))
@@ -285,17 +344,17 @@
         else:
             # When len(array_1) + len(array_2) > 4_000_000, this method is faster than sort method
             note = np.zeros(max_element, dtype=np.int8)
             note[array_1] = 1
             duplicate_idx = np.where(note[array_2] == 1)[0]
             return duplicate_idx
 
-
     def _remove_duplicate_with_gpu(self, array_1, array_2, max_element):
         import cupy as cp
+
         if len(array_1) + len(array_2) < 4_000_000:
             # When len(array_1) + len(array_2) < 4_000_000, this method is faster than array method
             aux = cp.array(np.concatenate((array_1, array_2)))
             aux_sort_indices = cp.argsort(aux)
             aux = aux[aux_sort_indices]
             mask = aux[1:] == aux[:-1]
             ar2_indices = aux_sort_indices[1:][mask] - array_1.size
@@ -304,15 +363,15 @@
         else:
             # When len(array_1) + len(array_2) > 4_000_000, this method is faster than sort method
             note = cp.zeros(max_element, dtype=np.int8)
             note[array_1] = 1
             duplicate_idx = cp.where(note[array_2] == 1)[0]
             return duplicate_idx
 
-    def build_index(self, all_spectra_list: list,  max_indexed_mz: float = 1500.00005):
+    def build_index(self, all_spectra_list: list, max_indexed_mz: float = 1500.00005):
         """
         Build the index for the MS/MS spectra library.
 
         The spectra provided to this function should be a dictionary in the format of {"precursor_mz": precursor_mz, "peaks": peaks}.
         The precursor_mz is the precursor m/z value of the MS/MS spectrum;
         The peaks is a numpy array which has been processed by the function "clean_spectrum".
 
@@ -321,46 +380,52 @@
         :param max_indexed_mz: The maximum m/z value that will be indexed. Default is 1500.00005.
         """
 
         # Get the total number of spectra and peaks
         total_peaks_num = np.sum([spectrum["peaks"].shape[0] for spectrum in all_spectra_list])
         total_spectra_num = len(all_spectra_list)
         # total_spectra_num can not be bigger than 2^32-1 (uint32), total_peak_num can not be bigger than 2^63-1 (int64)
-        assert total_spectra_num < 2 ** 32 - 1, "The total spectra number is too big."
-        assert total_peaks_num < 2 ** 63 - 1, "The total peaks number is too big."
+        assert total_spectra_num < 2**32 - 1, "The total spectra number is too big."
+        assert total_peaks_num < 2**63 - 1, "The total peaks number is too big."
         self.total_spectra_num = total_spectra_num
         self.total_peaks_num = total_peaks_num
 
         ############## Step 1: Collect the precursor m/z and peaks information. ##############
-        dtype_peak_data = np.dtype([("ion_mz", np.float32),  # The m/z of the fragment ion.
-                                    ("nl_mass", np.float32),  # The neutral loss mass of the fragment ion.
-                                    ("intensity", np.float32),  # The intensity of the fragment ion.
-                                    ("spec_idx", np.uint32),  # The index of the MS/MS spectra.
-                                    ("peak_idx", np.uint64)], align=True)  # The index of the fragment ion.
+        dtype_peak_data = np.dtype(
+            [
+                ("ion_mz", np.float32),  # The m/z of the fragment ion.
+                ("nl_mass", np.float32),  # The neutral loss mass of the fragment ion.
+                ("intensity", np.float32),  # The intensity of the fragment ion.
+                ("spec_idx", np.uint32),  # The index of the MS/MS spectra.
+                ("peak_idx", np.uint64),
+            ],
+            align=True,
+        )  # The index of the fragment ion.
 
         # Initialize the peak data array.
         peak_data = np.zeros(total_peaks_num, dtype=dtype_peak_data)
         peak_idx = 0
 
         # Adding the precursor m/z and peaks information to the peak data array.
         for idx, spectrum in enumerate(all_spectra_list):
             precursor_mz, peaks = spectrum["precursor_mz"], spectrum["peaks"]
             # Check the peaks array.
             assert peaks.ndim == 2, "The peaks array should be a 2D numpy array."
             assert peaks.shape[1] == 2, "The peaks array should be a 2D numpy array with the shape of [n, 2]."
             assert peaks.shape[0] > 0, "The peaks array should not be empty."
-            assert abs(np.sum(peaks[:, 1])-1) < 1e-4, "The peaks array should be normalized to sum to 1."
-            assert peaks.shape[0] <= 1 or np.min(peaks[1:, 0] - peaks[:-1, 0]) > self.max_ms2_tolerance_in_da * 2, \
-                "The peaks array should be sorted by m/z, and the m/z difference between two adjacent peaks should be larger than 2 * max_ms2_tolerance_in_da."
+            assert abs(np.sum(peaks[:, 1]) - 1) < 1e-4, "The peaks array should be normalized to sum to 1."
+            assert (
+                peaks.shape[0] <= 1 or np.min(peaks[1:, 0] - peaks[:-1, 0]) > self.max_ms2_tolerance_in_da * 2
+            ), "The peaks array should be sorted by m/z, and the m/z difference between two adjacent peaks should be larger than 2 * max_ms2_tolerance_in_da."
 
             # Preprocess the peaks array.
             peaks = self._preprocess_peaks(peaks)
 
             # Assign the product ion m/z
-            peak_data_item = peak_data[peak_idx:(peak_idx + peaks.shape[0])]
+            peak_data_item = peak_data[peak_idx: (peak_idx + peaks.shape[0])]
             peak_data_item["ion_mz"] = peaks[:, 0]
             # Assign the neutral loss mass
             peak_data_item["nl_mass"] = precursor_mz - peaks[:, 0]
             # Assign the intensity
             peak_data_item["intensity"] = peaks[:, 1]
             # Assign the spectrum index
             peak_data_item["spec_idx"] = idx
@@ -381,73 +446,81 @@
         all_ions_spec_idx = np.copy(peak_data["spec_idx"])
 
         # Assign the index of the product ions.
         peak_data["peak_idx"] = np.arange(0, self.total_peaks_num, dtype=np.uint64)
 
         # Build index for fast access to the ion's m/z.
         max_mz = min(np.max(all_ions_mz), max_indexed_mz)
-        search_array = np.arange(0., max_mz, self.mz_index_step)
-        all_ions_mz_idx_start = np.searchsorted(all_ions_mz, search_array, side='left').astype(np.int64)
+        search_array = np.arange(0.0, max_mz, self.mz_index_step)
+        all_ions_mz_idx_start = np.searchsorted(all_ions_mz, search_array, side="left").astype(np.int64)
 
         ############## Step 3: Build the index by sort with neutral loss mass. ##############
         # Sort with the neutral loss mass.
         peak_data.sort(order="nl_mass")
 
         # Record the m/z, intensity, spectrum index, and product ions index information for neutral loss ions.
         all_nl_mass = peak_data["nl_mass"]
         all_nl_intensity = peak_data["intensity"]
         all_nl_spec_idx = peak_data["spec_idx"]
         all_ions_idx_for_nl = peak_data["peak_idx"]
 
         # Build the index for fast access to the neutral loss mass.
         max_mz = min(np.max(all_nl_mass), max_indexed_mz)
-        search_array = np.arange(0., max_mz, self.mz_index_step)
-        all_nl_mass_idx_start = np.searchsorted(all_nl_mass, search_array, side='left').astype(np.int64)
+        search_array = np.arange(0.0, max_mz, self.mz_index_step)
+        all_nl_mass_idx_start = np.searchsorted(all_nl_mass, search_array, side="left").astype(np.int64)
 
         ############## Step 4: Save the index. ##############
-        index = [all_ions_mz_idx_start, all_ions_mz, all_ions_intensity, all_ions_spec_idx,
-                 all_nl_mass_idx_start, all_nl_mass, all_nl_intensity, all_nl_spec_idx, all_ions_idx_for_nl]
+        index = [
+            all_ions_mz_idx_start,
+            all_ions_mz,
+            all_ions_intensity,
+            all_ions_spec_idx,
+            all_nl_mass_idx_start,
+            all_nl_mass,
+            all_nl_intensity,
+            all_nl_spec_idx,
+            all_ions_idx_for_nl,
+        ]
         return index
 
     def _preprocess_peaks(self, peaks):
         """
         Preprocess the peaks.
         """
         peaks_clean = np.asarray(apply_weight_to_intensity(peaks))
         peaks_clean[:, 1] /= 2
         return peaks_clean
 
     def _score_peaks_with_cpu(self, intensity_query, intensity_library):
         intensity_mix = intensity_library + intensity_query
-        modified_value = intensity_mix * np.log2(intensity_mix) \
-            - intensity_library * np.log2(intensity_library) - intensity_query * np.log2(intensity_query)
+        modified_value = intensity_mix * np.log2(intensity_mix) - intensity_library * np.log2(intensity_library) - intensity_query * np.log2(intensity_query)
         return modified_value
 
     def _score_peaks_gpu(self, entropy_transform, intensity_query, intensity_library):
         return entropy_transform(intensity_library, intensity_query)
 
     def _find_location_from_array_with_index(self, wanted_mz, mz_array, mz_idx_start_array, side, index_number):
-        mz_min_int = (np.floor(wanted_mz*index_number)).astype(int)
+        mz_min_int = (np.floor(wanted_mz * index_number)).astype(int)
         mz_max_int = mz_min_int + 1
 
         if mz_min_int >= len(mz_idx_start_array):
             mz_idx_search_start = mz_idx_start_array[-1]
         else:
             mz_idx_search_start = mz_idx_start_array[mz_min_int].astype(int)
 
         if mz_max_int >= len(mz_idx_start_array):
             mz_idx_search_end = len(mz_array)
         else:
-            mz_idx_search_end = mz_idx_start_array[mz_max_int].astype(int)+1
+            mz_idx_search_end = mz_idx_start_array[mz_max_int].astype(int) + 1
 
         return mz_idx_search_start + np.searchsorted(mz_array[mz_idx_search_start:mz_idx_search_end], wanted_mz, side=side)
 
     def save_memory_for_multiprocessing(self):
         """
-        Move the numpy array in the index to shared memory in order to save memory. 
+        Move the numpy array in the index to shared memory in order to save memory.
         This function is not required when you only use one thread to search the MS/MS spectra.
         When use multiple threads, this function is also not required but highly recommended, as it avoids the memory copy and saves a lot of memory and time.
         """
         if self._init_for_multiprocessing:
             return
 
         for i, array in enumerate(self.index):
@@ -461,17 +534,17 @@
         try:
             if path_data is None:
                 path_data = self.path_data
 
             path_data = Path(path_data)
             self.index = []
             for name in self.index_names:
-                self.index.append(np.fromfile(path_data / f'{name}.npy', dtype=self.index_dtypes[name]))
+                self.index.append(np.fromfile(path_data / f"{name}.npy", dtype=self.index_dtypes[name]))
 
-            with open(path_data / 'information.json', 'r') as f:
+            with open(path_data / "information.json", "r") as f:
                 information = json.load(f)
             self.mz_index_step = information["mz_index_step"]
             self.total_spectra_num = information["total_spectra_num"]
             self.total_peaks_num = information["total_peaks_num"]
             self.max_ms2_tolerance_in_da = information["max_ms2_tolerance_in_da"]
             return True
         except:
@@ -483,24 +556,25 @@
         """
         if path_data is None:
             path_data = self.path_data
 
         path_data = Path(path_data)
         path_data.mkdir(parents=True, exist_ok=True)
         for i, name in enumerate(self.index_names):
-            self.index[i].tofile(path_data / f'{name}.npy')
+            self.index[i].tofile(str(path_data / f"{name}.npy"))
         information = {
             "mz_index_step": float(self.mz_index_step),
             "total_spectra_num": int(self.total_spectra_num),
-            'total_peaks_num': int(self.total_peaks_num),
+            "total_peaks_num": int(self.total_peaks_num),
             "max_ms2_tolerance_in_da": float(self.max_ms2_tolerance_in_da),
         }
-        with open(path_data / 'information.json', 'w') as f:
+        with open(path_data / "information.json", "w") as f:
             json.dump(information, f)
 
+
 def _convert_numpy_array_to_shared_memory(np_array, array_c_type=None):
     """
     The char table of shared memory can be find at:
     https://docs.python.org/3/library/struct.html#format-characters
     https://docs.python.org/3/library/array.html#module-array (This one is wrong!)
     The documentation of numpy.frombuffer can be find at:
     https://docs.scipy.org/doc/numpy/reference/generated/numpy.frombuffer.html
@@ -510,8 +584,7 @@
     num = reduce(lambda x, y: x * y, dim)
     if array_c_type is None:
         array_c_type = np_array.dtype.char
     base = multiprocessing.Array(array_c_type, num, lock=False)
     np_array_new = np.frombuffer(base, dtype=np_array.dtype).reshape(dim)
     np_array_new[:] = np_array
     return np_array_new
-
```

### Comparing `ms_entropy-0.6.0/ms_entropy/entropy_search/flash_entropy_search_core_low_memory.py` & `ms_entropy-0.9.0/ms_entropy/entropy_search/flash_entropy_search_core_low_memory.py`

 * *Files identical despite different names*

### Comparing `ms_entropy-0.6.0/ms_entropy/file_io/lbm2_file.py` & `ms_entropy-0.9.0/ms_entropy/file_io/lbm2_file.py`

 * *Files identical despite different names*

### Comparing `ms_entropy-0.6.0/ms_entropy/file_io/mgf_file.py` & `ms_entropy-0.9.0/ms_entropy/file_io/mgf_file.py`

 * *Files identical despite different names*

### Comparing `ms_entropy-0.6.0/ms_entropy/file_io/msp_file.py` & `ms_entropy-0.9.0/ms_entropy/file_io/msp_file.py`

 * *Files identical despite different names*

### Comparing `ms_entropy-0.6.0/ms_entropy/file_io/mzml_file.py` & `ms_entropy-0.9.0/ms_entropy/file_io/mzml_file.py`

 * *Files identical despite different names*

### Comparing `ms_entropy-0.6.0/ms_entropy/file_io/shared.py` & `ms_entropy-0.9.0/ms_entropy/file_io/shared.py`

 * *Files identical despite different names*

### Comparing `ms_entropy-0.6.0/ms_entropy/file_io/spec_file.py` & `ms_entropy-0.9.0/ms_entropy/file_io/spec_file.py`

 * *Files identical despite different names*

### Comparing `ms_entropy-0.6.0/ms_entropy/tools/fast_entropy.c` & `ms_entropy-0.9.0/ms_entropy/entropy_search/fast_flash_entropy_search_cpython.c`

 * *Files 1% similar despite different names*

```diff
@@ -1,33 +1,33 @@
-/* Generated by Cython 0.29.33 */
+/* Generated by Cython 0.29.35 */
 
 /* BEGIN: Cython Metadata
 {
     "distutils": {
         "depends": [],
-        "name": "ms_entropy.tools.fast_entropy",
+        "name": "ms_entropy.entropy_search.fast_flash_entropy_search_cpython",
         "sources": [
-            "ms_entropy/tools/fast_entropy.pyx"
+            "ms_entropy/entropy_search/fast_flash_entropy_search_cpython.pyx"
         ]
     },
-    "module_name": "ms_entropy.tools.fast_entropy"
+    "module_name": "ms_entropy.entropy_search.fast_flash_entropy_search_cpython"
 }
 END: Cython Metadata */
 
 #ifndef PY_SSIZE_T_CLEAN
 #define PY_SSIZE_T_CLEAN
 #endif /* PY_SSIZE_T_CLEAN */
 #include "Python.h"
 #ifndef Py_PYTHON_H
     #error Python headers needed to compile C extensions, please install development version of Python.
 #elif PY_VERSION_HEX < 0x02060000 || (0x03000000 <= PY_VERSION_HEX && PY_VERSION_HEX < 0x03030000)
     #error Cython requires Python 2.6+ or Python 3.3+.
 #else
-#define CYTHON_ABI "0_29_33"
-#define CYTHON_HEX_VERSION 0x001D21F0
+#define CYTHON_ABI "0_29_35"
+#define CYTHON_HEX_VERSION 0x001D23F0
 #define CYTHON_FUTURE_DIVISION 1
 #include <stddef.h>
 #ifndef offsetof
   #define offsetof(type, member) ( (size_t) & ((type*)0) -> member )
 #endif
 #if !defined(WIN32) && !defined(MS_WINDOWS)
   #ifndef __stdcall
@@ -87,16 +87,20 @@
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
   #ifndef CYTHON_UPDATE_DESCRIPTOR_DOC
@@ -212,15 +216,15 @@
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
@@ -251,15 +255,15 @@
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
   #if PY_VERSION_HEX >= 0x030B00A4
     #undef CYTHON_USE_EXC_INFO_STACK
     #define CYTHON_USE_EXC_INFO_STACK 0
   #elif !defined(CYTHON_USE_EXC_INFO_STACK)
     #define CYTHON_USE_EXC_INFO_STACK (PY_VERSION_HEX >= 0x030700A3)
   #endif
@@ -747,16 +751,16 @@
   #ifdef __cplusplus
     #define __PYX_EXTERN_C extern "C"
   #else
     #define __PYX_EXTERN_C extern
   #endif
 #endif
 
-#define __PYX_HAVE__ms_entropy__tools__fast_entropy
-#define __PYX_HAVE_API__ms_entropy__tools__fast_entropy
+#define __PYX_HAVE__ms_entropy__entropy_search__fast_flash_entropy_search_cpython
+#define __PYX_HAVE_API__ms_entropy__entropy_search__fast_flash_entropy_search_cpython
 /* Early includes */
 #include <string.h>
 #include <stdio.h>
 #include "numpy/arrayobject.h"
 #include "numpy/ndarrayobject.h"
 #include "numpy/ndarraytypes.h"
 #include "numpy/arrayscalars.h"
@@ -995,15 +999,15 @@
 #if CYTHON_CCOMPLEX && !defined(__cplusplus) && defined(__sun__) && defined(__GNUC__)
   #undef _Complex_I
   #define _Complex_I 1.0fj
 #endif
 
 
 static const char *__pyx_f[] = {
-  "ms_entropy/tools/fast_entropy.pyx",
+  "ms_entropy/entropy_search/fast_flash_entropy_search_cpython.pyx",
   "__init__.pxd",
   "stringsource",
   "type.pxd",
 };
 /* MemviewSliceStruct.proto */
 struct __pyx_memoryview_obj;
 typedef struct {
@@ -1105,238 +1109,238 @@
   char enc_type;
   char new_packmode;
   char enc_packmode;
   char is_valid_array;
 } __Pyx_BufFmt_Context;
 
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":689
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":689
  * # in Cython to enable them only on the right systems.
  * 
  * ctypedef npy_int8       int8_t             # <<<<<<<<<<<<<<
  * ctypedef npy_int16      int16_t
  * ctypedef npy_int32      int32_t
  */
 typedef npy_int8 __pyx_t_5numpy_int8_t;
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":690
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":690
  * 
  * ctypedef npy_int8       int8_t
  * ctypedef npy_int16      int16_t             # <<<<<<<<<<<<<<
  * ctypedef npy_int32      int32_t
  * ctypedef npy_int64      int64_t
  */
 typedef npy_int16 __pyx_t_5numpy_int16_t;
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":691
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":691
  * ctypedef npy_int8       int8_t
  * ctypedef npy_int16      int16_t
  * ctypedef npy_int32      int32_t             # <<<<<<<<<<<<<<
  * ctypedef npy_int64      int64_t
  * #ctypedef npy_int96      int96_t
  */
 typedef npy_int32 __pyx_t_5numpy_int32_t;
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":692
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":692
  * ctypedef npy_int16      int16_t
  * ctypedef npy_int32      int32_t
  * ctypedef npy_int64      int64_t             # <<<<<<<<<<<<<<
  * #ctypedef npy_int96      int96_t
  * #ctypedef npy_int128     int128_t
  */
 typedef npy_int64 __pyx_t_5numpy_int64_t;
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":696
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":696
  * #ctypedef npy_int128     int128_t
  * 
  * ctypedef npy_uint8      uint8_t             # <<<<<<<<<<<<<<
  * ctypedef npy_uint16     uint16_t
  * ctypedef npy_uint32     uint32_t
  */
 typedef npy_uint8 __pyx_t_5numpy_uint8_t;
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":697
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":697
  * 
  * ctypedef npy_uint8      uint8_t
  * ctypedef npy_uint16     uint16_t             # <<<<<<<<<<<<<<
  * ctypedef npy_uint32     uint32_t
  * ctypedef npy_uint64     uint64_t
  */
 typedef npy_uint16 __pyx_t_5numpy_uint16_t;
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":698
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":698
  * ctypedef npy_uint8      uint8_t
  * ctypedef npy_uint16     uint16_t
  * ctypedef npy_uint32     uint32_t             # <<<<<<<<<<<<<<
  * ctypedef npy_uint64     uint64_t
  * #ctypedef npy_uint96     uint96_t
  */
 typedef npy_uint32 __pyx_t_5numpy_uint32_t;
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":699
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":699
  * ctypedef npy_uint16     uint16_t
  * ctypedef npy_uint32     uint32_t
  * ctypedef npy_uint64     uint64_t             # <<<<<<<<<<<<<<
  * #ctypedef npy_uint96     uint96_t
  * #ctypedef npy_uint128    uint128_t
  */
 typedef npy_uint64 __pyx_t_5numpy_uint64_t;
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":703
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":703
  * #ctypedef npy_uint128    uint128_t
  * 
  * ctypedef npy_float32    float32_t             # <<<<<<<<<<<<<<
  * ctypedef npy_float64    float64_t
  * #ctypedef npy_float80    float80_t
  */
 typedef npy_float32 __pyx_t_5numpy_float32_t;
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":704
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":704
  * 
  * ctypedef npy_float32    float32_t
  * ctypedef npy_float64    float64_t             # <<<<<<<<<<<<<<
  * #ctypedef npy_float80    float80_t
  * #ctypedef npy_float128   float128_t
  */
 typedef npy_float64 __pyx_t_5numpy_float64_t;
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":713
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":713
  * # The int types are mapped a bit surprising --
  * # numpy.int corresponds to 'l' and numpy.long to 'q'
  * ctypedef npy_long       int_t             # <<<<<<<<<<<<<<
  * ctypedef npy_longlong   long_t
  * ctypedef npy_longlong   longlong_t
  */
 typedef npy_long __pyx_t_5numpy_int_t;
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":714
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":714
  * # numpy.int corresponds to 'l' and numpy.long to 'q'
  * ctypedef npy_long       int_t
  * ctypedef npy_longlong   long_t             # <<<<<<<<<<<<<<
  * ctypedef npy_longlong   longlong_t
  * 
  */
 typedef npy_longlong __pyx_t_5numpy_long_t;
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":715
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":715
  * ctypedef npy_long       int_t
  * ctypedef npy_longlong   long_t
  * ctypedef npy_longlong   longlong_t             # <<<<<<<<<<<<<<
  * 
  * ctypedef npy_ulong      uint_t
  */
 typedef npy_longlong __pyx_t_5numpy_longlong_t;
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":717
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":717
  * ctypedef npy_longlong   longlong_t
  * 
  * ctypedef npy_ulong      uint_t             # <<<<<<<<<<<<<<
  * ctypedef npy_ulonglong  ulong_t
  * ctypedef npy_ulonglong  ulonglong_t
  */
 typedef npy_ulong __pyx_t_5numpy_uint_t;
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":718
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":718
  * 
  * ctypedef npy_ulong      uint_t
  * ctypedef npy_ulonglong  ulong_t             # <<<<<<<<<<<<<<
  * ctypedef npy_ulonglong  ulonglong_t
  * 
  */
 typedef npy_ulonglong __pyx_t_5numpy_ulong_t;
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":719
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":719
  * ctypedef npy_ulong      uint_t
  * ctypedef npy_ulonglong  ulong_t
  * ctypedef npy_ulonglong  ulonglong_t             # <<<<<<<<<<<<<<
  * 
  * ctypedef npy_intp       intp_t
  */
 typedef npy_ulonglong __pyx_t_5numpy_ulonglong_t;
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":721
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":721
  * ctypedef npy_ulonglong  ulonglong_t
  * 
  * ctypedef npy_intp       intp_t             # <<<<<<<<<<<<<<
  * ctypedef npy_uintp      uintp_t
  * 
  */
 typedef npy_intp __pyx_t_5numpy_intp_t;
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":722
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":722
  * 
  * ctypedef npy_intp       intp_t
  * ctypedef npy_uintp      uintp_t             # <<<<<<<<<<<<<<
  * 
  * ctypedef npy_double     float_t
  */
 typedef npy_uintp __pyx_t_5numpy_uintp_t;
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":724
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":724
  * ctypedef npy_uintp      uintp_t
  * 
  * ctypedef npy_double     float_t             # <<<<<<<<<<<<<<
  * ctypedef npy_double     double_t
  * ctypedef npy_longdouble longdouble_t
  */
 typedef npy_double __pyx_t_5numpy_float_t;
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":725
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":725
  * 
  * ctypedef npy_double     float_t
  * ctypedef npy_double     double_t             # <<<<<<<<<<<<<<
  * ctypedef npy_longdouble longdouble_t
  * 
  */
 typedef npy_double __pyx_t_5numpy_double_t;
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":726
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":726
  * ctypedef npy_double     float_t
  * ctypedef npy_double     double_t
  * ctypedef npy_longdouble longdouble_t             # <<<<<<<<<<<<<<
  * 
  * ctypedef npy_cfloat      cfloat_t
  */
 typedef npy_longdouble __pyx_t_5numpy_longdouble_t;
 
-/* "ms_entropy/tools/fast_entropy.pyx":4
+/* "ms_entropy/entropy_search/fast_flash_entropy_search_cpython.pyx":4
  * cimport numpy as np
  * 
  * ctypedef np.float32_t float32             # <<<<<<<<<<<<<<
  * ctypedef np.int64_t int_64
  * ctypedef np.int8_t int_8
  */
-typedef __pyx_t_5numpy_float32_t __pyx_t_10ms_entropy_5tools_12fast_entropy_float32;
+typedef __pyx_t_5numpy_float32_t __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_float32;
 
-/* "ms_entropy/tools/fast_entropy.pyx":5
+/* "ms_entropy/entropy_search/fast_flash_entropy_search_cpython.pyx":5
  * 
  * ctypedef np.float32_t float32
  * ctypedef np.int64_t int_64             # <<<<<<<<<<<<<<
  * ctypedef np.int8_t int_8
  * ctypedef np.uint32_t uint_32
  */
-typedef __pyx_t_5numpy_int64_t __pyx_t_10ms_entropy_5tools_12fast_entropy_int_64;
+typedef __pyx_t_5numpy_int64_t __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_int_64;
 
-/* "ms_entropy/tools/fast_entropy.pyx":6
+/* "ms_entropy/entropy_search/fast_flash_entropy_search_cpython.pyx":6
  * ctypedef np.float32_t float32
  * ctypedef np.int64_t int_64
  * ctypedef np.int8_t int_8             # <<<<<<<<<<<<<<
  * ctypedef np.uint32_t uint_32
- * from libc.math cimport log2,log,pow
+ * from libc.math cimport log2
  */
-typedef __pyx_t_5numpy_int8_t __pyx_t_10ms_entropy_5tools_12fast_entropy_int_8;
+typedef __pyx_t_5numpy_int8_t __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_int_8;
 
-/* "ms_entropy/tools/fast_entropy.pyx":7
+/* "ms_entropy/entropy_search/fast_flash_entropy_search_cpython.pyx":7
  * ctypedef np.int64_t int_64
  * ctypedef np.int8_t int_8
  * ctypedef np.uint32_t uint_32             # <<<<<<<<<<<<<<
- * from libc.math cimport log2,log,pow
+ * from libc.math cimport log2
  * 
  */
-typedef __pyx_t_5numpy_uint32_t __pyx_t_10ms_entropy_5tools_12fast_entropy_uint_32;
+typedef __pyx_t_5numpy_uint32_t __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_uint_32;
 /* Declarations.proto */
 #if CYTHON_CCOMPLEX
   #ifdef __cplusplus
     typedef ::std::complex< float > __pyx_t_float_complex;
   #else
     typedef float _Complex __pyx_t_float_complex;
   #endif
@@ -1360,42 +1364,42 @@
 
 /*--- Type declarations ---*/
 struct __pyx_array_obj;
 struct __pyx_MemviewEnum_obj;
 struct __pyx_memoryview_obj;
 struct __pyx_memoryviewslice_obj;
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":728
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":728
  * ctypedef npy_longdouble longdouble_t
  * 
  * ctypedef npy_cfloat      cfloat_t             # <<<<<<<<<<<<<<
  * ctypedef npy_cdouble     cdouble_t
  * ctypedef npy_clongdouble clongdouble_t
  */
 typedef npy_cfloat __pyx_t_5numpy_cfloat_t;
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":729
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":729
  * 
  * ctypedef npy_cfloat      cfloat_t
  * ctypedef npy_cdouble     cdouble_t             # <<<<<<<<<<<<<<
  * ctypedef npy_clongdouble clongdouble_t
  * 
  */
 typedef npy_cdouble __pyx_t_5numpy_cdouble_t;
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":730
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":730
  * ctypedef npy_cfloat      cfloat_t
  * ctypedef npy_cdouble     cdouble_t
  * ctypedef npy_clongdouble clongdouble_t             # <<<<<<<<<<<<<<
  * 
  * ctypedef npy_cdouble     complex_t
  */
 typedef npy_clongdouble __pyx_t_5numpy_clongdouble_t;
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":732
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":732
  * ctypedef npy_clongdouble clongdouble_t
  * 
  * ctypedef npy_cdouble     complex_t             # <<<<<<<<<<<<<<
  * 
  * cdef inline object PyArray_MultiIterNew1(a):
  */
 typedef npy_cdouble __pyx_t_5numpy_complex_t;
@@ -1636,117 +1640,14 @@
 #define __pyx_get_slice_count_pointer(memview) (memview->acquisition_count_aligned_p)
 #define __pyx_get_slice_count(memview) (*__pyx_get_slice_count_pointer(memview))
 #define __PYX_INC_MEMVIEW(slice, have_gil) __Pyx_INC_MEMVIEW(slice, have_gil, __LINE__)
 #define __PYX_XDEC_MEMVIEW(slice, have_gil) __Pyx_XDEC_MEMVIEW(slice, have_gil, __LINE__)
 static CYTHON_INLINE void __Pyx_INC_MEMVIEW(__Pyx_memviewslice *, int, int);
 static CYTHON_INLINE void __Pyx_XDEC_MEMVIEW(__Pyx_memviewslice *, int, int);
 
-/* PyDictVersioning.proto */
-#if CYTHON_USE_DICT_VERSIONS && CYTHON_USE_TYPE_SLOTS
-#define __PYX_DICT_VERSION_INIT  ((PY_UINT64_T) -1)
-#define __PYX_GET_DICT_VERSION(dict)  (((PyDictObject*)(dict))->ma_version_tag)
-#define __PYX_UPDATE_DICT_CACHE(dict, value, cache_var, version_var)\
-    (version_var) = __PYX_GET_DICT_VERSION(dict);\
-    (cache_var) = (value);
-#define __PYX_PY_DICT_LOOKUP_IF_MODIFIED(VAR, DICT, LOOKUP) {\
-    static PY_UINT64_T __pyx_dict_version = 0;\
-    static PyObject *__pyx_dict_cached_value = NULL;\
-    if (likely(__PYX_GET_DICT_VERSION(DICT) == __pyx_dict_version)) {\
-        (VAR) = __pyx_dict_cached_value;\
-    } else {\
-        (VAR) = __pyx_dict_cached_value = (LOOKUP);\
-        __pyx_dict_version = __PYX_GET_DICT_VERSION(DICT);\
-    }\
-}
-static CYTHON_INLINE PY_UINT64_T __Pyx_get_tp_dict_version(PyObject *obj);
-static CYTHON_INLINE PY_UINT64_T __Pyx_get_object_dict_version(PyObject *obj);
-static CYTHON_INLINE int __Pyx_object_dict_version_matches(PyObject* obj, PY_UINT64_T tp_dict_version, PY_UINT64_T obj_dict_version);
-#else
-#define __PYX_GET_DICT_VERSION(dict)  (0)
-#define __PYX_UPDATE_DICT_CACHE(dict, value, cache_var, version_var)
-#define __PYX_PY_DICT_LOOKUP_IF_MODIFIED(VAR, DICT, LOOKUP)  (VAR) = (LOOKUP);
-#endif
-
-/* GetModuleGlobalName.proto */
-#if CYTHON_USE_DICT_VERSIONS
-#define __Pyx_GetModuleGlobalName(var, name)  do {\
-    static PY_UINT64_T __pyx_dict_version = 0;\
-    static PyObject *__pyx_dict_cached_value = NULL;\
-    (var) = (likely(__pyx_dict_version == __PYX_GET_DICT_VERSION(__pyx_d))) ?\
-        (likely(__pyx_dict_cached_value) ? __Pyx_NewRef(__pyx_dict_cached_value) : __Pyx_GetBuiltinName(name)) :\
-        __Pyx__GetModuleGlobalName(name, &__pyx_dict_version, &__pyx_dict_cached_value);\
-} while(0)
-#define __Pyx_GetModuleGlobalNameUncached(var, name)  do {\
-    PY_UINT64_T __pyx_dict_version;\
-    PyObject *__pyx_dict_cached_value;\
-    (var) = __Pyx__GetModuleGlobalName(name, &__pyx_dict_version, &__pyx_dict_cached_value);\
-} while(0)
-static PyObject *__Pyx__GetModuleGlobalName(PyObject *name, PY_UINT64_T *dict_version, PyObject **dict_cached_value);
-#else
-#define __Pyx_GetModuleGlobalName(var, name)  (var) = __Pyx__GetModuleGlobalName(name)
-#define __Pyx_GetModuleGlobalNameUncached(var, name)  (var) = __Pyx__GetModuleGlobalName(name)
-static CYTHON_INLINE PyObject *__Pyx__GetModuleGlobalName(PyObject *name);
-#endif
-
-/* PyCFunctionFastCall.proto */
-#if CYTHON_FAST_PYCCALL
-static CYTHON_INLINE PyObject *__Pyx_PyCFunction_FastCall(PyObject *func, PyObject **args, Py_ssize_t nargs);
-#else
-#define __Pyx_PyCFunction_FastCall(func, args, nargs)  (assert(0), NULL)
-#endif
-
-/* PyFunctionFastCall.proto */
-#if CYTHON_FAST_PYCALL
-#define __Pyx_PyFunction_FastCall(func, args, nargs)\
-    __Pyx_PyFunction_FastCallDict((func), (args), (nargs), NULL)
-#if 1 || PY_VERSION_HEX < 0x030600B1
-static PyObject *__Pyx_PyFunction_FastCallDict(PyObject *func, PyObject **args, Py_ssize_t nargs, PyObject *kwargs);
-#else
-#define __Pyx_PyFunction_FastCallDict(func, args, nargs, kwargs) _PyFunction_FastCallDict(func, args, nargs, kwargs)
-#endif
-#define __Pyx_BUILD_ASSERT_EXPR(cond)\
-    (sizeof(char [1 - 2*!(cond)]) - 1)
-#ifndef Py_MEMBER_SIZE
-#define Py_MEMBER_SIZE(type, member) sizeof(((type *)0)->member)
-#endif
-#if CYTHON_FAST_PYCALL
-  static size_t __pyx_pyframe_localsplus_offset = 0;
-  #include "frameobject.h"
-#if PY_VERSION_HEX >= 0x030b00a6
-  #ifndef Py_BUILD_CORE
-    #define Py_BUILD_CORE 1
-  #endif
-  #include "internal/pycore_frame.h"
-#endif
-  #define __Pxy_PyFrame_Initialize_Offsets()\
-    ((void)__Pyx_BUILD_ASSERT_EXPR(sizeof(PyFrameObject) == offsetof(PyFrameObject, f_localsplus) + Py_MEMBER_SIZE(PyFrameObject, f_localsplus)),\
-     (void)(__pyx_pyframe_localsplus_offset = ((size_t)PyFrame_Type.tp_basicsize) - Py_MEMBER_SIZE(PyFrameObject, f_localsplus)))
-  #define __Pyx_PyFrame_GetLocalsplus(frame)\
-    (assert(__pyx_pyframe_localsplus_offset), (PyObject **)(((char *)(frame)) + __pyx_pyframe_localsplus_offset))
-#endif // CYTHON_FAST_PYCALL
-#endif
-
-/* PyObjectCall.proto */
-#if CYTHON_COMPILING_IN_CPYTHON
-static CYTHON_INLINE PyObject* __Pyx_PyObject_Call(PyObject *func, PyObject *arg, PyObject *kw);
-#else
-#define __Pyx_PyObject_Call(func, arg, kw) PyObject_Call(func, arg, kw)
-#endif
-
-/* PyObjectCall2Args.proto */
-static CYTHON_UNUSED PyObject* __Pyx_PyObject_Call2Args(PyObject* function, PyObject* arg1, PyObject* arg2);
-
-/* PyObjectCallMethO.proto */
-#if CYTHON_COMPILING_IN_CPYTHON
-static CYTHON_INLINE PyObject* __Pyx_PyObject_CallMethO(PyObject *func, PyObject *arg);
-#endif
-
-/* PyObjectCallOneArg.proto */
-static CYTHON_INLINE PyObject* __Pyx_PyObject_CallOneArg(PyObject *func, PyObject *arg);
-
 /* GetTopmostException.proto */
 #if CYTHON_USE_EXC_INFO_STACK
 static _PyErr_StackItem * __Pyx_PyErr_GetTopmostException(PyThreadState *tstate);
 #endif
 
 /* PyThreadStateGet.proto */
 #if CYTHON_FAST_THREAD_STATE
@@ -1782,14 +1683,21 @@
 #if CYTHON_FAST_THREAD_STATE
 #define __Pyx_GetException(type, value, tb)  __Pyx__GetException(__pyx_tstate, type, value, tb)
 static int __Pyx__GetException(PyThreadState *tstate, PyObject **type, PyObject **value, PyObject **tb);
 #else
 static int __Pyx_GetException(PyObject **type, PyObject **value, PyObject **tb);
 #endif
 
+/* PyObjectCall.proto */
+#if CYTHON_COMPILING_IN_CPYTHON
+static CYTHON_INLINE PyObject* __Pyx_PyObject_Call(PyObject *func, PyObject *arg, PyObject *kw);
+#else
+#define __Pyx_PyObject_Call(func, arg, kw) PyObject_Call(func, arg, kw)
+#endif
+
 /* PyErrFetchRestore.proto */
 #if CYTHON_FAST_THREAD_STATE
 #define __Pyx_PyErr_Clear() __Pyx_ErrRestore(NULL, NULL, NULL)
 #define __Pyx_ErrRestoreWithState(type, value, tb)  __Pyx_ErrRestoreInState(PyThreadState_GET(), type, value, tb)
 #define __Pyx_ErrFetchWithState(type, value, tb)    __Pyx_ErrFetchInState(PyThreadState_GET(), type, value, tb)
 #define __Pyx_ErrRestore(type, value, tb)  __Pyx_ErrRestoreInState(__pyx_tstate, type, value, tb)
 #define __Pyx_ErrFetch(type, value, tb)    __Pyx_ErrFetchInState(__pyx_tstate, type, value, tb)
@@ -1816,14 +1724,63 @@
 
 /* ArgTypeTest.proto */
 #define __Pyx_ArgTypeTest(obj, type, none_allowed, name, exact)\
     ((likely((Py_TYPE(obj) == type) | (none_allowed && (obj == Py_None)))) ? 1 :\
         __Pyx__ArgTypeTest(obj, type, name, exact))
 static int __Pyx__ArgTypeTest(PyObject *obj, PyTypeObject *type, const char *name, int exact);
 
+/* PyCFunctionFastCall.proto */
+#if CYTHON_FAST_PYCCALL
+static CYTHON_INLINE PyObject *__Pyx_PyCFunction_FastCall(PyObject *func, PyObject **args, Py_ssize_t nargs);
+#else
+#define __Pyx_PyCFunction_FastCall(func, args, nargs)  (assert(0), NULL)
+#endif
+
+/* PyFunctionFastCall.proto */
+#if CYTHON_FAST_PYCALL
+#define __Pyx_PyFunction_FastCall(func, args, nargs)\
+    __Pyx_PyFunction_FastCallDict((func), (args), (nargs), NULL)
+#if 1 || PY_VERSION_HEX < 0x030600B1
+static PyObject *__Pyx_PyFunction_FastCallDict(PyObject *func, PyObject **args, Py_ssize_t nargs, PyObject *kwargs);
+#else
+#define __Pyx_PyFunction_FastCallDict(func, args, nargs, kwargs) _PyFunction_FastCallDict(func, args, nargs, kwargs)
+#endif
+#define __Pyx_BUILD_ASSERT_EXPR(cond)\
+    (sizeof(char [1 - 2*!(cond)]) - 1)
+#ifndef Py_MEMBER_SIZE
+#define Py_MEMBER_SIZE(type, member) sizeof(((type *)0)->member)
+#endif
+#if CYTHON_FAST_PYCALL
+  static size_t __pyx_pyframe_localsplus_offset = 0;
+  #include "frameobject.h"
+#if PY_VERSION_HEX >= 0x030b00a6
+  #ifndef Py_BUILD_CORE
+    #define Py_BUILD_CORE 1
+  #endif
+  #include "internal/pycore_frame.h"
+#endif
+  #define __Pxy_PyFrame_Initialize_Offsets()\
+    ((void)__Pyx_BUILD_ASSERT_EXPR(sizeof(PyFrameObject) == offsetof(PyFrameObject, f_localsplus) + Py_MEMBER_SIZE(PyFrameObject, f_localsplus)),\
+     (void)(__pyx_pyframe_localsplus_offset = ((size_t)PyFrame_Type.tp_basicsize) - Py_MEMBER_SIZE(PyFrameObject, f_localsplus)))
+  #define __Pyx_PyFrame_GetLocalsplus(frame)\
+    (assert(__pyx_pyframe_localsplus_offset), (PyObject **)(((char *)(frame)) + __pyx_pyframe_localsplus_offset))
+#endif // CYTHON_FAST_PYCALL
+#endif
+
+/* PyObjectCall2Args.proto */
+static CYTHON_UNUSED PyObject* __Pyx_PyObject_Call2Args(PyObject* function, PyObject* arg1, PyObject* arg2);
+
+/* PyObjectCallMethO.proto */
+#if CYTHON_COMPILING_IN_CPYTHON
+static CYTHON_INLINE PyObject* __Pyx_PyObject_CallMethO(PyObject *func, PyObject *arg);
+#endif
+
+/* PyObjectCallOneArg.proto */
+static CYTHON_INLINE PyObject* __Pyx_PyObject_CallOneArg(PyObject *func, PyObject *arg);
+
 /* IncludeStringH.proto */
 #include <string.h>
 
 /* BytesEquals.proto */
 static CYTHON_INLINE int __Pyx_PyBytes_Equals(PyObject* s1, PyObject* s2, int equals);
 
 /* UnicodeEquals.proto */
@@ -1893,14 +1850,61 @@
          const char* cstring, Py_ssize_t start, Py_ssize_t stop,
          const char* encoding, const char* errors,
          PyObject* (*decode_func)(const char *s, Py_ssize_t size, const char *errors));
 
 /* GetAttr3.proto */
 static CYTHON_INLINE PyObject *__Pyx_GetAttr3(PyObject *, PyObject *, PyObject *);
 
+/* PyDictVersioning.proto */
+#if CYTHON_USE_DICT_VERSIONS && CYTHON_USE_TYPE_SLOTS
+#define __PYX_DICT_VERSION_INIT  ((PY_UINT64_T) -1)
+#define __PYX_GET_DICT_VERSION(dict)  (((PyDictObject*)(dict))->ma_version_tag)
+#define __PYX_UPDATE_DICT_CACHE(dict, value, cache_var, version_var)\
+    (version_var) = __PYX_GET_DICT_VERSION(dict);\
+    (cache_var) = (value);
+#define __PYX_PY_DICT_LOOKUP_IF_MODIFIED(VAR, DICT, LOOKUP) {\
+    static PY_UINT64_T __pyx_dict_version = 0;\
+    static PyObject *__pyx_dict_cached_value = NULL;\
+    if (likely(__PYX_GET_DICT_VERSION(DICT) == __pyx_dict_version)) {\
+        (VAR) = __pyx_dict_cached_value;\
+    } else {\
+        (VAR) = __pyx_dict_cached_value = (LOOKUP);\
+        __pyx_dict_version = __PYX_GET_DICT_VERSION(DICT);\
+    }\
+}
+static CYTHON_INLINE PY_UINT64_T __Pyx_get_tp_dict_version(PyObject *obj);
+static CYTHON_INLINE PY_UINT64_T __Pyx_get_object_dict_version(PyObject *obj);
+static CYTHON_INLINE int __Pyx_object_dict_version_matches(PyObject* obj, PY_UINT64_T tp_dict_version, PY_UINT64_T obj_dict_version);
+#else
+#define __PYX_GET_DICT_VERSION(dict)  (0)
+#define __PYX_UPDATE_DICT_CACHE(dict, value, cache_var, version_var)
+#define __PYX_PY_DICT_LOOKUP_IF_MODIFIED(VAR, DICT, LOOKUP)  (VAR) = (LOOKUP);
+#endif
+
+/* GetModuleGlobalName.proto */
+#if CYTHON_USE_DICT_VERSIONS
+#define __Pyx_GetModuleGlobalName(var, name)  do {\
+    static PY_UINT64_T __pyx_dict_version = 0;\
+    static PyObject *__pyx_dict_cached_value = NULL;\
+    (var) = (likely(__pyx_dict_version == __PYX_GET_DICT_VERSION(__pyx_d))) ?\
+        (likely(__pyx_dict_cached_value) ? __Pyx_NewRef(__pyx_dict_cached_value) : __Pyx_GetBuiltinName(name)) :\
+        __Pyx__GetModuleGlobalName(name, &__pyx_dict_version, &__pyx_dict_cached_value);\
+} while(0)
+#define __Pyx_GetModuleGlobalNameUncached(var, name)  do {\
+    PY_UINT64_T __pyx_dict_version;\
+    PyObject *__pyx_dict_cached_value;\
+    (var) = __Pyx__GetModuleGlobalName(name, &__pyx_dict_version, &__pyx_dict_cached_value);\
+} while(0)
+static PyObject *__Pyx__GetModuleGlobalName(PyObject *name, PY_UINT64_T *dict_version, PyObject **dict_cached_value);
+#else
+#define __Pyx_GetModuleGlobalName(var, name)  (var) = __Pyx__GetModuleGlobalName(name)
+#define __Pyx_GetModuleGlobalNameUncached(var, name)  (var) = __Pyx__GetModuleGlobalName(name)
+static CYTHON_INLINE PyObject *__Pyx__GetModuleGlobalName(PyObject *name);
+#endif
+
 /* RaiseTooManyValuesToUnpack.proto */
 static CYTHON_INLINE void __Pyx_RaiseTooManyValuesError(Py_ssize_t expected);
 
 /* RaiseNeedMoreValuesToUnpack.proto */
 static CYTHON_INLINE void __Pyx_RaiseNeedMoreValuesError(Py_ssize_t index);
 
 /* RaiseNoneIterError.proto */
@@ -2021,22 +2025,30 @@
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
 
 /* CLineInTraceback.proto */
 #ifdef CYTHON_CLINE_IN_TRACEBACK
 #define __Pyx_CLineForTraceback(tstate, c_line)  (((CYTHON_CLINE_IN_TRACEBACK)) ? c_line : 0)
 #else
 static int __Pyx_CLineForTraceback(PyThreadState *tstate, int c_line);
@@ -2120,31 +2132,21 @@
                 int ndim,
                 __Pyx_TypeInfo *dtype,
                 __Pyx_BufFmt_StackElem stack[],
                 __Pyx_memviewslice *memviewslice,
                 PyObject *original_obj);
 
 /* ObjectToMemviewSlice.proto */
-static CYTHON_INLINE __Pyx_memviewslice __Pyx_PyObject_to_MemoryviewSlice_ds_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_float32(PyObject *, int writable_flag);
-
-/* ObjectToMemviewSlice.proto */
-static CYTHON_INLINE __Pyx_memviewslice __Pyx_PyObject_to_MemoryviewSlice_ds_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_float32__const__(PyObject *, int writable_flag);
-
-/* ObjectToMemviewSlice.proto */
-static CYTHON_INLINE __Pyx_memviewslice __Pyx_PyObject_to_MemoryviewSlice_ds_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_uint_32__const__(PyObject *, int writable_flag);
+static CYTHON_INLINE __Pyx_memviewslice __Pyx_PyObject_to_MemoryviewSlice_ds_nn___pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_float32(PyObject *, int writable_flag);
 
 /* ObjectToMemviewSlice.proto */
-static CYTHON_INLINE __Pyx_memviewslice __Pyx_PyObject_to_MemoryviewSlice_ds_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_int_8__const__(PyObject *, int writable_flag);
+static CYTHON_INLINE __Pyx_memviewslice __Pyx_PyObject_to_MemoryviewSlice_ds_nn___pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_float32__const__(PyObject *, int writable_flag);
 
 /* ObjectToMemviewSlice.proto */
-static CYTHON_INLINE __Pyx_memviewslice __Pyx_PyObject_to_MemoryviewSlice_d_dc_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_float32(PyObject *, int writable_flag);
-
-/* MemviewDtypeToObject.proto */
-static CYTHON_INLINE PyObject *__pyx_memview_get_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_float32(const char *itemp);
-static CYTHON_INLINE int __pyx_memview_set_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_float32(const char *itemp, PyObject *obj);
+static CYTHON_INLINE __Pyx_memviewslice __Pyx_PyObject_to_MemoryviewSlice_ds_nn___pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_uint_32__const__(PyObject *, int writable_flag);
 
 /* RealImag.proto */
 #if CYTHON_CCOMPLEX
   #ifdef __cplusplus
     #define __Pyx_CREAL(z) ((z).real())
     #define __Pyx_CIMAG(z) ((z).imag())
   #else
@@ -2246,22 +2248,19 @@
                                  const char *mode, int ndim,
                                  size_t sizeof_dtype, int contig_flag,
                                  int dtype_is_object);
 
 /* CIntFromPy.proto */
 static CYTHON_INLINE npy_int64 __Pyx_PyInt_As_npy_int64(PyObject *);
 
-/* CIntFromPy.proto */
-static CYTHON_INLINE int __Pyx_PyInt_As_int(PyObject *);
-
 /* CIntToPy.proto */
 static CYTHON_INLINE PyObject* __Pyx_PyInt_From_npy_int64(npy_int64 value);
 
-/* CIntToPy.proto */
-static CYTHON_INLINE PyObject* __Pyx_PyInt_From_npy_int8(npy_int8 value);
+/* CIntFromPy.proto */
+static CYTHON_INLINE int __Pyx_PyInt_As_int(PyObject *);
 
 /* CIntFromPy.proto */
 static CYTHON_INLINE long __Pyx_PyInt_As_long(PyObject *);
 
 /* CIntToPy.proto */
 static CYTHON_INLINE PyObject* __Pyx_PyInt_From_int(int value);
 
@@ -2324,29 +2323,27 @@
 static PyTypeObject *__pyx_ptype_5numpy_complexfloating = 0;
 static PyTypeObject *__pyx_ptype_5numpy_flexible = 0;
 static PyTypeObject *__pyx_ptype_5numpy_character = 0;
 static PyTypeObject *__pyx_ptype_5numpy_ufunc = 0;
 
 /* Module declarations from 'libc.math' */
 
-/* Module declarations from 'ms_entropy.tools.fast_entropy' */
+/* Module declarations from 'ms_entropy.entropy_search.fast_flash_entropy_search_cpython' */
 static PyTypeObject *__pyx_array_type = 0;
 static PyTypeObject *__pyx_MemviewEnum_type = 0;
 static PyTypeObject *__pyx_memoryview_type = 0;
 static PyTypeObject *__pyx_memoryviewslice_type = 0;
 static PyObject *generic = 0;
 static PyObject *strided = 0;
 static PyObject *indirect = 0;
 static PyObject *contiguous = 0;
 static PyObject *indirect_contiguous = 0;
 static int __pyx_memoryview_thread_locks_used;
 static PyThread_type_lock __pyx_memoryview_thread_locks[8];
-static void __pyx_f_10ms_entropy_5tools_12fast_entropy_entropy_similarity_search_fast(__pyx_t_10ms_entropy_5tools_12fast_entropy_int_64, __pyx_t_10ms_entropy_5tools_12fast_entropy_int_64, __pyx_t_10ms_entropy_5tools_12fast_entropy_float32, __Pyx_memviewslice, __Pyx_memviewslice, __Pyx_memviewslice, int, __pyx_t_10ms_entropy_5tools_12fast_entropy_int_64, __pyx_t_10ms_entropy_5tools_12fast_entropy_int_64, __Pyx_memviewslice, int __pyx_skip_dispatch); /*proto*/
-static PyObject *__pyx_f_10ms_entropy_5tools_12fast_entropy_apply_weight_to_intensity(__Pyx_memviewslice, int __pyx_skip_dispatch); /*proto*/
-static double __pyx_f_10ms_entropy_5tools_12fast_entropy_spectral_entropy(__Pyx_memviewslice, int __pyx_skip_dispatch); /*proto*/
+static void __pyx_f_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_cy_entropy_similarity_identity_search(__pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_int_64, __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_int_64, __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_float32, __Pyx_memviewslice, __Pyx_memviewslice, __Pyx_memviewslice, __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_int_64, __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_int_64, int __pyx_skip_dispatch); /*proto*/
 static struct __pyx_array_obj *__pyx_array_new(PyObject *, Py_ssize_t, char *, char *, char *); /*proto*/
 static void *__pyx_align_pointer(void *, size_t); /*proto*/
 static PyObject *__pyx_memoryview_new(PyObject *, int, int, __Pyx_TypeInfo *); /*proto*/
 static CYTHON_INLINE int __pyx_memoryview_check(PyObject *); /*proto*/
 static PyObject *_unellipsify(PyObject *, int); /*proto*/
 static PyObject *assert_direct_dimensions(Py_ssize_t *, int); /*proto*/
 static struct __pyx_memoryview_obj *__pyx_memview_slice(struct __pyx_memoryview_obj *, PyObject *); /*proto*/
@@ -2372,23 +2369,22 @@
 static void __pyx_memoryview_broadcast_leading(__Pyx_memviewslice *, int, int); /*proto*/
 static void __pyx_memoryview_refcount_copying(__Pyx_memviewslice *, int, int, int); /*proto*/
 static void __pyx_memoryview_refcount_objects_in_slice_with_gil(char *, Py_ssize_t *, Py_ssize_t *, int, int); /*proto*/
 static void __pyx_memoryview_refcount_objects_in_slice(char *, Py_ssize_t *, Py_ssize_t *, int, int); /*proto*/
 static void __pyx_memoryview_slice_assign_scalar(__Pyx_memviewslice *, int, size_t, void *, int); /*proto*/
 static void __pyx_memoryview__slice_assign_scalar(char *, Py_ssize_t *, Py_ssize_t *, int, size_t, void *); /*proto*/
 static PyObject *__pyx_unpickle_Enum__set_state(struct __pyx_MemviewEnum_obj *, PyObject *); /*proto*/
-static __Pyx_TypeInfo __Pyx_TypeInfo_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_float32 = { "float32", NULL, sizeof(__pyx_t_10ms_entropy_5tools_12fast_entropy_float32), { 0 }, 0, 'R', 0, 0 };
-static __Pyx_TypeInfo __Pyx_TypeInfo_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_float32__const__ = { "const float32", NULL, sizeof(__pyx_t_10ms_entropy_5tools_12fast_entropy_float32 const ), { 0 }, 0, 'R', 0, 0 };
-static __Pyx_TypeInfo __Pyx_TypeInfo_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_uint_32__const__ = { "const uint_32", NULL, sizeof(__pyx_t_10ms_entropy_5tools_12fast_entropy_uint_32 const ), { 0 }, 0, IS_UNSIGNED(__pyx_t_10ms_entropy_5tools_12fast_entropy_uint_32 const ) ? 'U' : 'I', IS_UNSIGNED(__pyx_t_10ms_entropy_5tools_12fast_entropy_uint_32 const ), 0 };
-static __Pyx_TypeInfo __Pyx_TypeInfo_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_int_8__const__ = { "const int_8", NULL, sizeof(__pyx_t_10ms_entropy_5tools_12fast_entropy_int_8 const ), { 0 }, 0, IS_UNSIGNED(__pyx_t_10ms_entropy_5tools_12fast_entropy_int_8 const ) ? 'U' : 'I', IS_UNSIGNED(__pyx_t_10ms_entropy_5tools_12fast_entropy_int_8 const ), 0 };
-#define __Pyx_MODULE_NAME "ms_entropy.tools.fast_entropy"
-extern int __pyx_module_is_main_ms_entropy__tools__fast_entropy;
-int __pyx_module_is_main_ms_entropy__tools__fast_entropy = 0;
+static __Pyx_TypeInfo __Pyx_TypeInfo_nn___pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_float32 = { "float32", NULL, sizeof(__pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_float32), { 0 }, 0, 'R', 0, 0 };
+static __Pyx_TypeInfo __Pyx_TypeInfo_nn___pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_float32__const__ = { "const float32", NULL, sizeof(__pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_float32 const ), { 0 }, 0, 'R', 0, 0 };
+static __Pyx_TypeInfo __Pyx_TypeInfo_nn___pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_uint_32__const__ = { "const uint_32", NULL, sizeof(__pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_uint_32 const ), { 0 }, 0, IS_UNSIGNED(__pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_uint_32 const ) ? 'U' : 'I', IS_UNSIGNED(__pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_uint_32 const ), 0 };
+#define __Pyx_MODULE_NAME "ms_entropy.entropy_search.fast_flash_entropy_search_cpython"
+extern int __pyx_module_is_main_ms_entropy__entropy_search__fast_flash_entropy_search_cpython;
+int __pyx_module_is_main_ms_entropy__entropy_search__fast_flash_entropy_search_cpython = 0;
 
-/* Implementation of 'ms_entropy.tools.fast_entropy' */
+/* Implementation of 'ms_entropy.entropy_search.fast_flash_entropy_search_cpython' */
 static PyObject *__pyx_builtin_range;
 static PyObject *__pyx_builtin_ImportError;
 static PyObject *__pyx_builtin_ValueError;
 static PyObject *__pyx_builtin_MemoryError;
 static PyObject *__pyx_builtin_enumerate;
 static PyObject *__pyx_builtin_TypeError;
 static PyObject *__pyx_builtin_Ellipsis;
@@ -2397,15 +2393,14 @@
 static const char __pyx_k_O[] = "O";
 static const char __pyx_k_c[] = "c";
 static const char __pyx_k_id[] = "id";
 static const char __pyx_k_np[] = "np";
 static const char __pyx_k_new[] = "__new__";
 static const char __pyx_k_obj[] = "obj";
 static const char __pyx_k_base[] = "base";
-static const char __pyx_k_copy[] = "copy";
 static const char __pyx_k_dict[] = "__dict__";
 static const char __pyx_k_main[] = "__main__";
 static const char __pyx_k_mode[] = "mode";
 static const char __pyx_k_name[] = "name";
 static const char __pyx_k_ndim[] = "ndim";
 static const char __pyx_k_pack[] = "pack";
 static const char __pyx_k_size[] = "size";
@@ -2444,33 +2439,31 @@
 static const char __pyx_k_IndexError[] = "IndexError";
 static const char __pyx_k_ValueError[] = "ValueError";
 static const char __pyx_k_pyx_result[] = "__pyx_result";
 static const char __pyx_k_pyx_vtable[] = "__pyx_vtable__";
 static const char __pyx_k_ImportError[] = "ImportError";
 static const char __pyx_k_MemoryError[] = "MemoryError";
 static const char __pyx_k_PickleError[] = "PickleError";
-static const char __pyx_k_search_type[] = "search_type";
 static const char __pyx_k_pyx_checksum[] = "__pyx_checksum";
-static const char __pyx_k_search_array[] = "search_array";
 static const char __pyx_k_stringsource[] = "stringsource";
 static const char __pyx_k_pyx_getbuffer[] = "__pyx_getbuffer";
 static const char __pyx_k_reduce_cython[] = "__reduce_cython__";
 static const char __pyx_k_View_MemoryView[] = "View.MemoryView";
 static const char __pyx_k_allocate_buffer[] = "allocate_buffer";
 static const char __pyx_k_dtype_is_object[] = "dtype_is_object";
 static const char __pyx_k_pyx_PickleError[] = "__pyx_PickleError";
 static const char __pyx_k_setstate_cython[] = "__setstate_cython__";
 static const char __pyx_k_pyx_unpickle_Enum[] = "__pyx_unpickle_Enum";
 static const char __pyx_k_cline_in_traceback[] = "cline_in_traceback";
+static const char __pyx_k_entropy_similarity[] = "entropy_similarity";
 static const char __pyx_k_product_mz_idx_max[] = "product_mz_idx_max";
 static const char __pyx_k_product_mz_idx_min[] = "product_mz_idx_min";
 static const char __pyx_k_strided_and_direct[] = "<strided and direct>";
 static const char __pyx_k_strided_and_indirect[] = "<strided and indirect>";
 static const char __pyx_k_contiguous_and_direct[] = "<contiguous and direct>";
-static const char __pyx_k_mixed_spectra_entropy[] = "mixed_spectra_entropy";
 static const char __pyx_k_MemoryView_of_r_object[] = "<MemoryView of %r object>";
 static const char __pyx_k_library_spec_idx_array[] = "library_spec_idx_array";
 static const char __pyx_k_search_spectra_idx_max[] = "search_spectra_idx_max";
 static const char __pyx_k_search_spectra_idx_min[] = "search_spectra_idx_min";
 static const char __pyx_k_MemoryView_of_r_at_0x_x[] = "<MemoryView of %r at 0x%x>";
 static const char __pyx_k_contiguous_and_indirect[] = "<contiguous and indirect>";
 static const char __pyx_k_library_peaks_intensity[] = "library_peaks_intensity";
@@ -2522,18 +2515,18 @@
 static PyObject *__pyx_n_s_base;
 static PyObject *__pyx_n_s_c;
 static PyObject *__pyx_n_u_c;
 static PyObject *__pyx_n_s_class;
 static PyObject *__pyx_n_s_cline_in_traceback;
 static PyObject *__pyx_kp_s_contiguous_and_direct;
 static PyObject *__pyx_kp_s_contiguous_and_indirect;
-static PyObject *__pyx_n_s_copy;
 static PyObject *__pyx_n_s_dict;
 static PyObject *__pyx_n_s_dtype_is_object;
 static PyObject *__pyx_n_s_encode;
+static PyObject *__pyx_n_s_entropy_similarity;
 static PyObject *__pyx_n_s_enumerate;
 static PyObject *__pyx_n_s_error;
 static PyObject *__pyx_n_s_flags;
 static PyObject *__pyx_n_s_format;
 static PyObject *__pyx_n_s_fortran;
 static PyObject *__pyx_n_u_fortran;
 static PyObject *__pyx_n_s_getstate;
@@ -2543,15 +2536,14 @@
 static PyObject *__pyx_n_s_intensity;
 static PyObject *__pyx_n_s_itemsize;
 static PyObject *__pyx_kp_s_itemsize_0_for_cython_array;
 static PyObject *__pyx_n_s_library_peaks_intensity;
 static PyObject *__pyx_n_s_library_spec_idx_array;
 static PyObject *__pyx_n_s_main;
 static PyObject *__pyx_n_s_memview;
-static PyObject *__pyx_n_s_mixed_spectra_entropy;
 static PyObject *__pyx_n_s_mode;
 static PyObject *__pyx_n_s_name;
 static PyObject *__pyx_n_s_name_2;
 static PyObject *__pyx_n_s_ndim;
 static PyObject *__pyx_n_s_new;
 static PyObject *__pyx_kp_s_no_default___reduce___due_to_non;
 static PyObject *__pyx_n_s_np;
@@ -2571,18 +2563,16 @@
 static PyObject *__pyx_n_s_pyx_type;
 static PyObject *__pyx_n_s_pyx_unpickle_Enum;
 static PyObject *__pyx_n_s_pyx_vtable;
 static PyObject *__pyx_n_s_range;
 static PyObject *__pyx_n_s_reduce;
 static PyObject *__pyx_n_s_reduce_cython;
 static PyObject *__pyx_n_s_reduce_ex;
-static PyObject *__pyx_n_s_search_array;
 static PyObject *__pyx_n_s_search_spectra_idx_max;
 static PyObject *__pyx_n_s_search_spectra_idx_min;
-static PyObject *__pyx_n_s_search_type;
 static PyObject *__pyx_n_s_setstate;
 static PyObject *__pyx_n_s_setstate_cython;
 static PyObject *__pyx_n_s_shape;
 static PyObject *__pyx_n_s_size;
 static PyObject *__pyx_n_s_start;
 static PyObject *__pyx_n_s_step;
 static PyObject *__pyx_n_s_stop;
@@ -2592,17 +2582,15 @@
 static PyObject *__pyx_kp_s_stringsource;
 static PyObject *__pyx_n_s_struct;
 static PyObject *__pyx_n_s_test;
 static PyObject *__pyx_kp_s_unable_to_allocate_array_data;
 static PyObject *__pyx_kp_s_unable_to_allocate_shape_and_str;
 static PyObject *__pyx_n_s_unpack;
 static PyObject *__pyx_n_s_update;
-static PyObject *__pyx_pf_10ms_entropy_5tools_12fast_entropy_entropy_similarity_search_fast(CYTHON_UNUSED PyObject *__pyx_self, __pyx_t_10ms_entropy_5tools_12fast_entropy_int_64 __pyx_v_product_mz_idx_min, __pyx_t_10ms_entropy_5tools_12fast_entropy_int_64 __pyx_v_product_mz_idx_max, __pyx_t_10ms_entropy_5tools_12fast_entropy_float32 __pyx_v_intensity, __Pyx_memviewslice __pyx_v_mixed_spectra_entropy, __Pyx_memviewslice __pyx_v_library_peaks_intensity, __Pyx_memviewslice __pyx_v_library_spec_idx_array, int __pyx_v_search_type, __pyx_t_10ms_entropy_5tools_12fast_entropy_int_64 __pyx_v_search_spectra_idx_min, __pyx_t_10ms_entropy_5tools_12fast_entropy_int_64 __pyx_v_search_spectra_idx_max, __Pyx_memviewslice __pyx_v_search_array); /* proto */
-static PyObject *__pyx_pf_10ms_entropy_5tools_12fast_entropy_2apply_weight_to_intensity(CYTHON_UNUSED PyObject *__pyx_self, __Pyx_memviewslice __pyx_v_spectrum); /* proto */
-static PyObject *__pyx_pf_10ms_entropy_5tools_12fast_entropy_4spectral_entropy(CYTHON_UNUSED PyObject *__pyx_self, __Pyx_memviewslice __pyx_v_spectrum); /* proto */
+static PyObject *__pyx_pf_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_cy_entropy_similarity_identity_search(CYTHON_UNUSED PyObject *__pyx_self, __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_int_64 __pyx_v_product_mz_idx_min, __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_int_64 __pyx_v_product_mz_idx_max, __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_float32 __pyx_v_intensity, __Pyx_memviewslice __pyx_v_entropy_similarity, __Pyx_memviewslice __pyx_v_library_peaks_intensity, __Pyx_memviewslice __pyx_v_library_spec_idx_array, __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_int_64 __pyx_v_search_spectra_idx_min, __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_int_64 __pyx_v_search_spectra_idx_max); /* proto */
 static int __pyx_array___pyx_pf_15View_dot_MemoryView_5array___cinit__(struct __pyx_array_obj *__pyx_v_self, PyObject *__pyx_v_shape, Py_ssize_t __pyx_v_itemsize, PyObject *__pyx_v_format, PyObject *__pyx_v_mode, int __pyx_v_allocate_buffer); /* proto */
 static int __pyx_array___pyx_pf_15View_dot_MemoryView_5array_2__getbuffer__(struct __pyx_array_obj *__pyx_v_self, Py_buffer *__pyx_v_info, int __pyx_v_flags); /* proto */
 static void __pyx_array___pyx_pf_15View_dot_MemoryView_5array_4__dealloc__(struct __pyx_array_obj *__pyx_v_self); /* proto */
 static PyObject *__pyx_pf_15View_dot_MemoryView_5array_7memview___get__(struct __pyx_array_obj *__pyx_v_self); /* proto */
 static Py_ssize_t __pyx_array___pyx_pf_15View_dot_MemoryView_5array_6__len__(struct __pyx_array_obj *__pyx_v_self); /* proto */
 static PyObject *__pyx_array___pyx_pf_15View_dot_MemoryView_5array_8__getattr__(struct __pyx_array_obj *__pyx_v_self, PyObject *__pyx_v_attr); /* proto */
 static PyObject *__pyx_array___pyx_pf_15View_dot_MemoryView_5array_10__getitem__(struct __pyx_array_obj *__pyx_v_self, PyObject *__pyx_v_item); /* proto */
@@ -2677,215 +2665,161 @@
 static PyObject *__pyx_tuple__24;
 static PyObject *__pyx_tuple__25;
 static PyObject *__pyx_tuple__26;
 static PyObject *__pyx_tuple__27;
 static PyObject *__pyx_codeobj__28;
 /* Late includes */
 
-/* "ms_entropy/tools/fast_entropy.pyx":11
+/* "ms_entropy/entropy_search/fast_flash_entropy_search_cpython.pyx":11
  * 
  * 
- * cpdef void entropy_similarity_search_fast(int_64 product_mz_idx_min, int_64 product_mz_idx_max,             # <<<<<<<<<<<<<<
- *                                     float32 intensity, float32[:] mixed_spectra_entropy,
- *                                     const float32[:] library_peaks_intensity, const uint_32[:] library_spec_idx_array,
- */
-
-static PyObject *__pyx_pw_10ms_entropy_5tools_12fast_entropy_1entropy_similarity_search_fast(PyObject *__pyx_self, PyObject *__pyx_args, PyObject *__pyx_kwds); /*proto*/
-static void __pyx_f_10ms_entropy_5tools_12fast_entropy_entropy_similarity_search_fast(__pyx_t_10ms_entropy_5tools_12fast_entropy_int_64 __pyx_v_product_mz_idx_min, __pyx_t_10ms_entropy_5tools_12fast_entropy_int_64 __pyx_v_product_mz_idx_max, __pyx_t_10ms_entropy_5tools_12fast_entropy_float32 __pyx_v_intensity, __Pyx_memviewslice __pyx_v_mixed_spectra_entropy, __Pyx_memviewslice __pyx_v_library_peaks_intensity, __Pyx_memviewslice __pyx_v_library_spec_idx_array, int __pyx_v_search_type, __pyx_t_10ms_entropy_5tools_12fast_entropy_int_64 __pyx_v_search_spectra_idx_min, __pyx_t_10ms_entropy_5tools_12fast_entropy_int_64 __pyx_v_search_spectra_idx_max, __Pyx_memviewslice __pyx_v_search_array, CYTHON_UNUSED int __pyx_skip_dispatch) {
-  __pyx_t_10ms_entropy_5tools_12fast_entropy_uint_32 __pyx_v_library_spec_idx;
-  __pyx_t_10ms_entropy_5tools_12fast_entropy_float32 __pyx_v_library_peak_intensity;
-  __pyx_t_10ms_entropy_5tools_12fast_entropy_float32 __pyx_v_intensity_ab;
-  __pyx_t_10ms_entropy_5tools_12fast_entropy_float32 __pyx_v_intensity_xlog2x;
-  __pyx_t_10ms_entropy_5tools_12fast_entropy_int_64 __pyx_v_idx;
-  __pyx_t_10ms_entropy_5tools_12fast_entropy_int_64 __pyx_t_1;
-  __pyx_t_10ms_entropy_5tools_12fast_entropy_int_64 __pyx_t_2;
-  __pyx_t_10ms_entropy_5tools_12fast_entropy_int_64 __pyx_t_3;
-  __pyx_t_10ms_entropy_5tools_12fast_entropy_int_64 __pyx_t_4;
+ * cpdef void cy_entropy_similarity_identity_search(int_64 product_mz_idx_min, int_64 product_mz_idx_max,             # <<<<<<<<<<<<<<
+ *                                                     float32 intensity, float32[:] entropy_similarity,
+ *                                                     const float32[:] library_peaks_intensity, const uint_32[:] library_spec_idx_array,
+ */
+
+static PyObject *__pyx_pw_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_1cy_entropy_similarity_identity_search(PyObject *__pyx_self, PyObject *__pyx_args, PyObject *__pyx_kwds); /*proto*/
+static void __pyx_f_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_cy_entropy_similarity_identity_search(__pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_int_64 __pyx_v_product_mz_idx_min, __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_int_64 __pyx_v_product_mz_idx_max, __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_float32 __pyx_v_intensity, __Pyx_memviewslice __pyx_v_entropy_similarity, __Pyx_memviewslice __pyx_v_library_peaks_intensity, __Pyx_memviewslice __pyx_v_library_spec_idx_array, __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_int_64 __pyx_v_search_spectra_idx_min, __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_int_64 __pyx_v_search_spectra_idx_max, CYTHON_UNUSED int __pyx_skip_dispatch) {
+  __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_uint_32 __pyx_v_library_spec_idx;
+  __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_float32 __pyx_v_library_peak_intensity;
+  __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_float32 __pyx_v_intensity_ab;
+  __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_float32 __pyx_v_intensity_xlog2x;
+  __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_int_64 __pyx_v_idx;
+  __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_int_64 __pyx_t_1;
+  __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_int_64 __pyx_t_2;
+  __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_int_64 __pyx_t_3;
+  __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_int_64 __pyx_t_4;
   int __pyx_t_5;
   int __pyx_t_6;
   size_t __pyx_t_7;
 
-  /* "ms_entropy/tools/fast_entropy.pyx":25
+  /* "ms_entropy/entropy_search/fast_flash_entropy_search_cpython.pyx":22
  *     cdef uint_32 library_spec_idx
  *     cdef float32 library_peak_intensity, intensity_ab
  *     cdef float32 intensity_xlog2x = intensity * log2(intensity)             # <<<<<<<<<<<<<<
  * 
  *     for idx in range(product_mz_idx_min, product_mz_idx_max):
  */
   __pyx_v_intensity_xlog2x = (__pyx_v_intensity * log2(__pyx_v_intensity));
 
-  /* "ms_entropy/tools/fast_entropy.pyx":27
+  /* "ms_entropy/entropy_search/fast_flash_entropy_search_cpython.pyx":24
  *     cdef float32 intensity_xlog2x = intensity * log2(intensity)
  * 
  *     for idx in range(product_mz_idx_min, product_mz_idx_max):             # <<<<<<<<<<<<<<
  *         library_spec_idx = library_spec_idx_array[idx]
- *         if (search_type == 0) or \
+ *         if  search_spectra_idx_min <= library_spec_idx and library_spec_idx < search_spectra_idx_max:
  */
   __pyx_t_1 = __pyx_v_product_mz_idx_max;
   __pyx_t_2 = __pyx_t_1;
   for (__pyx_t_3 = __pyx_v_product_mz_idx_min; __pyx_t_3 < __pyx_t_2; __pyx_t_3+=1) {
     __pyx_v_idx = __pyx_t_3;
 
-    /* "ms_entropy/tools/fast_entropy.pyx":28
+    /* "ms_entropy/entropy_search/fast_flash_entropy_search_cpython.pyx":25
  * 
  *     for idx in range(product_mz_idx_min, product_mz_idx_max):
  *         library_spec_idx = library_spec_idx_array[idx]             # <<<<<<<<<<<<<<
- *         if (search_type == 0) or \
- *                 (search_type == 1 and search_spectra_idx_min <= library_spec_idx and library_spec_idx < search_spectra_idx_max) or \
+ *         if  search_spectra_idx_min <= library_spec_idx and library_spec_idx < search_spectra_idx_max:
+ *             # Match this peak
  */
     __pyx_t_4 = __pyx_v_idx;
-    __pyx_v_library_spec_idx = (*((__pyx_t_10ms_entropy_5tools_12fast_entropy_uint_32 const  *) ( /* dim=0 */ (__pyx_v_library_spec_idx_array.data + __pyx_t_4 * __pyx_v_library_spec_idx_array.strides[0]) )));
+    __pyx_v_library_spec_idx = (*((__pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_uint_32 const  *) ( /* dim=0 */ (__pyx_v_library_spec_idx_array.data + __pyx_t_4 * __pyx_v_library_spec_idx_array.strides[0]) )));
 
-    /* "ms_entropy/tools/fast_entropy.pyx":29
+    /* "ms_entropy/entropy_search/fast_flash_entropy_search_cpython.pyx":26
  *     for idx in range(product_mz_idx_min, product_mz_idx_max):
  *         library_spec_idx = library_spec_idx_array[idx]
- *         if (search_type == 0) or \             # <<<<<<<<<<<<<<
- *                 (search_type == 1 and search_spectra_idx_min <= library_spec_idx and library_spec_idx < search_spectra_idx_max) or \
- *                 (search_type == 2 and search_array[library_spec_idx]):
- */
-    __pyx_t_6 = ((__pyx_v_search_type == 0) != 0);
-    if (!__pyx_t_6) {
-    } else {
-      __pyx_t_5 = __pyx_t_6;
-      goto __pyx_L6_bool_binop_done;
-    }
-
-    /* "ms_entropy/tools/fast_entropy.pyx":30
- *         library_spec_idx = library_spec_idx_array[idx]
- *         if (search_type == 0) or \
- *                 (search_type == 1 and search_spectra_idx_min <= library_spec_idx and library_spec_idx < search_spectra_idx_max) or \             # <<<<<<<<<<<<<<
- *                 (search_type == 2 and search_array[library_spec_idx]):
- *             # Match this peak
- */
-    __pyx_t_6 = ((__pyx_v_search_type == 1) != 0);
-    if (!__pyx_t_6) {
-      goto __pyx_L8_next_or;
-    } else {
-    }
-    __pyx_t_6 = ((__pyx_v_search_spectra_idx_min <= __pyx_v_library_spec_idx) != 0);
-    if (!__pyx_t_6) {
-      goto __pyx_L8_next_or;
-    } else {
-    }
-    __pyx_t_6 = ((__pyx_v_library_spec_idx < __pyx_v_search_spectra_idx_max) != 0);
-    if (!__pyx_t_6) {
-    } else {
-      __pyx_t_5 = __pyx_t_6;
-      goto __pyx_L6_bool_binop_done;
-    }
-    __pyx_L8_next_or:;
-
-    /* "ms_entropy/tools/fast_entropy.pyx":31
- *         if (search_type == 0) or \
- *                 (search_type == 1 and search_spectra_idx_min <= library_spec_idx and library_spec_idx < search_spectra_idx_max) or \
- *                 (search_type == 2 and search_array[library_spec_idx]):             # <<<<<<<<<<<<<<
+ *         if  search_spectra_idx_min <= library_spec_idx and library_spec_idx < search_spectra_idx_max:             # <<<<<<<<<<<<<<
  *             # Match this peak
  *             library_peak_intensity = library_peaks_intensity[idx]
  */
-    __pyx_t_6 = ((__pyx_v_search_type == 2) != 0);
+    __pyx_t_6 = ((__pyx_v_search_spectra_idx_min <= __pyx_v_library_spec_idx) != 0);
     if (__pyx_t_6) {
     } else {
       __pyx_t_5 = __pyx_t_6;
       goto __pyx_L6_bool_binop_done;
     }
-    __pyx_t_7 = __pyx_v_library_spec_idx;
-    __pyx_t_6 = ((*((__pyx_t_10ms_entropy_5tools_12fast_entropy_int_8 const  *) ( /* dim=0 */ (__pyx_v_search_array.data + __pyx_t_7 * __pyx_v_search_array.strides[0]) ))) != 0);
+    __pyx_t_6 = ((__pyx_v_library_spec_idx < __pyx_v_search_spectra_idx_max) != 0);
     __pyx_t_5 = __pyx_t_6;
     __pyx_L6_bool_binop_done:;
-
-    /* "ms_entropy/tools/fast_entropy.pyx":29
- *     for idx in range(product_mz_idx_min, product_mz_idx_max):
- *         library_spec_idx = library_spec_idx_array[idx]
- *         if (search_type == 0) or \             # <<<<<<<<<<<<<<
- *                 (search_type == 1 and search_spectra_idx_min <= library_spec_idx and library_spec_idx < search_spectra_idx_max) or \
- *                 (search_type == 2 and search_array[library_spec_idx]):
- */
     if (__pyx_t_5) {
 
-      /* "ms_entropy/tools/fast_entropy.pyx":33
- *                 (search_type == 2 and search_array[library_spec_idx]):
+      /* "ms_entropy/entropy_search/fast_flash_entropy_search_cpython.pyx":28
+ *         if  search_spectra_idx_min <= library_spec_idx and library_spec_idx < search_spectra_idx_max:
  *             # Match this peak
  *             library_peak_intensity = library_peaks_intensity[idx]             # <<<<<<<<<<<<<<
  *             intensity_ab = intensity + library_peak_intensity
  * 
  */
       __pyx_t_4 = __pyx_v_idx;
-      __pyx_v_library_peak_intensity = (*((__pyx_t_10ms_entropy_5tools_12fast_entropy_float32 const  *) ( /* dim=0 */ (__pyx_v_library_peaks_intensity.data + __pyx_t_4 * __pyx_v_library_peaks_intensity.strides[0]) )));
+      __pyx_v_library_peak_intensity = (*((__pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_float32 const  *) ( /* dim=0 */ (__pyx_v_library_peaks_intensity.data + __pyx_t_4 * __pyx_v_library_peaks_intensity.strides[0]) )));
 
-      /* "ms_entropy/tools/fast_entropy.pyx":34
+      /* "ms_entropy/entropy_search/fast_flash_entropy_search_cpython.pyx":29
  *             # Match this peak
  *             library_peak_intensity = library_peaks_intensity[idx]
  *             intensity_ab = intensity + library_peak_intensity             # <<<<<<<<<<<<<<
  * 
- *             mixed_spectra_entropy[library_spec_idx] += \
+ *             entropy_similarity[library_spec_idx] += \
  */
       __pyx_v_intensity_ab = (__pyx_v_intensity + __pyx_v_library_peak_intensity);
 
-      /* "ms_entropy/tools/fast_entropy.pyx":36
+      /* "ms_entropy/entropy_search/fast_flash_entropy_search_cpython.pyx":31
  *             intensity_ab = intensity + library_peak_intensity
  * 
- *             mixed_spectra_entropy[library_spec_idx] += \             # <<<<<<<<<<<<<<
+ *             entropy_similarity[library_spec_idx] += \             # <<<<<<<<<<<<<<
  *                 intensity_ab * log2(intensity_ab) - \
  *                 intensity_xlog2x - \
  */
       __pyx_t_7 = __pyx_v_library_spec_idx;
-      *((__pyx_t_10ms_entropy_5tools_12fast_entropy_float32 *) ( /* dim=0 */ (__pyx_v_mixed_spectra_entropy.data + __pyx_t_7 * __pyx_v_mixed_spectra_entropy.strides[0]) )) += (((__pyx_v_intensity_ab * log2(__pyx_v_intensity_ab)) - __pyx_v_intensity_xlog2x) - (__pyx_v_library_peak_intensity * log2(__pyx_v_library_peak_intensity)));
+      *((__pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_float32 *) ( /* dim=0 */ (__pyx_v_entropy_similarity.data + __pyx_t_7 * __pyx_v_entropy_similarity.strides[0]) )) += (((__pyx_v_intensity_ab * log2(__pyx_v_intensity_ab)) - __pyx_v_intensity_xlog2x) - (__pyx_v_library_peak_intensity * log2(__pyx_v_library_peak_intensity)));
 
-      /* "ms_entropy/tools/fast_entropy.pyx":29
+      /* "ms_entropy/entropy_search/fast_flash_entropy_search_cpython.pyx":26
  *     for idx in range(product_mz_idx_min, product_mz_idx_max):
  *         library_spec_idx = library_spec_idx_array[idx]
- *         if (search_type == 0) or \             # <<<<<<<<<<<<<<
- *                 (search_type == 1 and search_spectra_idx_min <= library_spec_idx and library_spec_idx < search_spectra_idx_max) or \
- *                 (search_type == 2 and search_array[library_spec_idx]):
+ *         if  search_spectra_idx_min <= library_spec_idx and library_spec_idx < search_spectra_idx_max:             # <<<<<<<<<<<<<<
+ *             # Match this peak
+ *             library_peak_intensity = library_peaks_intensity[idx]
  */
     }
   }
 
-  /* "ms_entropy/tools/fast_entropy.pyx":11
+  /* "ms_entropy/entropy_search/fast_flash_entropy_search_cpython.pyx":11
  * 
  * 
- * cpdef void entropy_similarity_search_fast(int_64 product_mz_idx_min, int_64 product_mz_idx_max,             # <<<<<<<<<<<<<<
- *                                     float32 intensity, float32[:] mixed_spectra_entropy,
- *                                     const float32[:] library_peaks_intensity, const uint_32[:] library_spec_idx_array,
+ * cpdef void cy_entropy_similarity_identity_search(int_64 product_mz_idx_min, int_64 product_mz_idx_max,             # <<<<<<<<<<<<<<
+ *                                                     float32 intensity, float32[:] entropy_similarity,
+ *                                                     const float32[:] library_peaks_intensity, const uint_32[:] library_spec_idx_array,
  */
 
   /* function exit code */
 }
 
 /* Python wrapper */
-static PyObject *__pyx_pw_10ms_entropy_5tools_12fast_entropy_1entropy_similarity_search_fast(PyObject *__pyx_self, PyObject *__pyx_args, PyObject *__pyx_kwds); /*proto*/
-static char __pyx_doc_10ms_entropy_5tools_12fast_entropy_entropy_similarity_search_fast[] = "\n    The mixed_spectra_entropy will be modified in this function.\n    search_type is 0: search all spectra.\n    search_type is 1: search spectra in the range [search_spectra_idx_min, search_spectra_idx_max).\n    search_type is 2: search spectra in the array search_array with entry equals 1, the length of search_array should be equal to the self.total_spectra_num\n\n    Note: the intensity here should be half of the original intensity.\n    ";
-static PyObject *__pyx_pw_10ms_entropy_5tools_12fast_entropy_1entropy_similarity_search_fast(PyObject *__pyx_self, PyObject *__pyx_args, PyObject *__pyx_kwds) {
-  __pyx_t_10ms_entropy_5tools_12fast_entropy_int_64 __pyx_v_product_mz_idx_min;
-  __pyx_t_10ms_entropy_5tools_12fast_entropy_int_64 __pyx_v_product_mz_idx_max;
-  __pyx_t_10ms_entropy_5tools_12fast_entropy_float32 __pyx_v_intensity;
-  __Pyx_memviewslice __pyx_v_mixed_spectra_entropy = { 0, 0, { 0 }, { 0 }, { 0 } };
+static PyObject *__pyx_pw_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_1cy_entropy_similarity_identity_search(PyObject *__pyx_self, PyObject *__pyx_args, PyObject *__pyx_kwds); /*proto*/
+static char __pyx_doc_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_cy_entropy_similarity_identity_search[] = "\n    The entropy_similarity will be modified in this function.\n\n    Note: the intensity here should be half of the original intensity.\n    ";
+static PyObject *__pyx_pw_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_1cy_entropy_similarity_identity_search(PyObject *__pyx_self, PyObject *__pyx_args, PyObject *__pyx_kwds) {
+  __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_int_64 __pyx_v_product_mz_idx_min;
+  __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_int_64 __pyx_v_product_mz_idx_max;
+  __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_float32 __pyx_v_intensity;
+  __Pyx_memviewslice __pyx_v_entropy_similarity = { 0, 0, { 0 }, { 0 }, { 0 } };
   __Pyx_memviewslice __pyx_v_library_peaks_intensity = { 0, 0, { 0 }, { 0 }, { 0 } };
   __Pyx_memviewslice __pyx_v_library_spec_idx_array = { 0, 0, { 0 }, { 0 }, { 0 } };
-  int __pyx_v_search_type;
-  __pyx_t_10ms_entropy_5tools_12fast_entropy_int_64 __pyx_v_search_spectra_idx_min;
-  __pyx_t_10ms_entropy_5tools_12fast_entropy_int_64 __pyx_v_search_spectra_idx_max;
-  __Pyx_memviewslice __pyx_v_search_array = { 0, 0, { 0 }, { 0 }, { 0 } };
+  __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_int_64 __pyx_v_search_spectra_idx_min;
+  __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_int_64 __pyx_v_search_spectra_idx_max;
   int __pyx_lineno = 0;
   const char *__pyx_filename = NULL;
   int __pyx_clineno = 0;
   PyObject *__pyx_r = 0;
   __Pyx_RefNannyDeclarations
-  __Pyx_RefNannySetupContext("entropy_similarity_search_fast (wrapper)", 0);
+  __Pyx_RefNannySetupContext("cy_entropy_similarity_identity_search (wrapper)", 0);
   {
-    static PyObject **__pyx_pyargnames[] = {&__pyx_n_s_product_mz_idx_min,&__pyx_n_s_product_mz_idx_max,&__pyx_n_s_intensity,&__pyx_n_s_mixed_spectra_entropy,&__pyx_n_s_library_peaks_intensity,&__pyx_n_s_library_spec_idx_array,&__pyx_n_s_search_type,&__pyx_n_s_search_spectra_idx_min,&__pyx_n_s_search_spectra_idx_max,&__pyx_n_s_search_array,0};
-    PyObject* values[10] = {0,0,0,0,0,0,0,0,0,0};
+    static PyObject **__pyx_pyargnames[] = {&__pyx_n_s_product_mz_idx_min,&__pyx_n_s_product_mz_idx_max,&__pyx_n_s_intensity,&__pyx_n_s_entropy_similarity,&__pyx_n_s_library_peaks_intensity,&__pyx_n_s_library_spec_idx_array,&__pyx_n_s_search_spectra_idx_min,&__pyx_n_s_search_spectra_idx_max,0};
+    PyObject* values[8] = {0,0,0,0,0,0,0,0};
     if (unlikely(__pyx_kwds)) {
       Py_ssize_t kw_args;
       const Py_ssize_t pos_args = PyTuple_GET_SIZE(__pyx_args);
       switch (pos_args) {
-        case 10: values[9] = PyTuple_GET_ITEM(__pyx_args, 9);
-        CYTHON_FALLTHROUGH;
-        case  9: values[8] = PyTuple_GET_ITEM(__pyx_args, 8);
-        CYTHON_FALLTHROUGH;
         case  8: values[7] = PyTuple_GET_ITEM(__pyx_args, 7);
         CYTHON_FALLTHROUGH;
         case  7: values[6] = PyTuple_GET_ITEM(__pyx_args, 6);
         CYTHON_FALLTHROUGH;
         case  6: values[5] = PyTuple_GET_ITEM(__pyx_args, 5);
         CYTHON_FALLTHROUGH;
         case  5: values[4] = PyTuple_GET_ITEM(__pyx_args, 4);
@@ -2906,592 +2840,125 @@
         case  0:
         if (likely((values[0] = __Pyx_PyDict_GetItemStr(__pyx_kwds, __pyx_n_s_product_mz_idx_min)) != 0)) kw_args--;
         else goto __pyx_L5_argtuple_error;
         CYTHON_FALLTHROUGH;
         case  1:
         if (likely((values[1] = __Pyx_PyDict_GetItemStr(__pyx_kwds, __pyx_n_s_product_mz_idx_max)) != 0)) kw_args--;
         else {
-          __Pyx_RaiseArgtupleInvalid("entropy_similarity_search_fast", 1, 10, 10, 1); __PYX_ERR(0, 11, __pyx_L3_error)
+          __Pyx_RaiseArgtupleInvalid("cy_entropy_similarity_identity_search", 1, 8, 8, 1); __PYX_ERR(0, 11, __pyx_L3_error)
         }
         CYTHON_FALLTHROUGH;
         case  2:
         if (likely((values[2] = __Pyx_PyDict_GetItemStr(__pyx_kwds, __pyx_n_s_intensity)) != 0)) kw_args--;
         else {
-          __Pyx_RaiseArgtupleInvalid("entropy_similarity_search_fast", 1, 10, 10, 2); __PYX_ERR(0, 11, __pyx_L3_error)
+          __Pyx_RaiseArgtupleInvalid("cy_entropy_similarity_identity_search", 1, 8, 8, 2); __PYX_ERR(0, 11, __pyx_L3_error)
         }
         CYTHON_FALLTHROUGH;
         case  3:
-        if (likely((values[3] = __Pyx_PyDict_GetItemStr(__pyx_kwds, __pyx_n_s_mixed_spectra_entropy)) != 0)) kw_args--;
+        if (likely((values[3] = __Pyx_PyDict_GetItemStr(__pyx_kwds, __pyx_n_s_entropy_similarity)) != 0)) kw_args--;
         else {
-          __Pyx_RaiseArgtupleInvalid("entropy_similarity_search_fast", 1, 10, 10, 3); __PYX_ERR(0, 11, __pyx_L3_error)
+          __Pyx_RaiseArgtupleInvalid("cy_entropy_similarity_identity_search", 1, 8, 8, 3); __PYX_ERR(0, 11, __pyx_L3_error)
         }
         CYTHON_FALLTHROUGH;
         case  4:
         if (likely((values[4] = __Pyx_PyDict_GetItemStr(__pyx_kwds, __pyx_n_s_library_peaks_intensity)) != 0)) kw_args--;
         else {
-          __Pyx_RaiseArgtupleInvalid("entropy_similarity_search_fast", 1, 10, 10, 4); __PYX_ERR(0, 11, __pyx_L3_error)
+          __Pyx_RaiseArgtupleInvalid("cy_entropy_similarity_identity_search", 1, 8, 8, 4); __PYX_ERR(0, 11, __pyx_L3_error)
         }
         CYTHON_FALLTHROUGH;
         case  5:
         if (likely((values[5] = __Pyx_PyDict_GetItemStr(__pyx_kwds, __pyx_n_s_library_spec_idx_array)) != 0)) kw_args--;
         else {
-          __Pyx_RaiseArgtupleInvalid("entropy_similarity_search_fast", 1, 10, 10, 5); __PYX_ERR(0, 11, __pyx_L3_error)
+          __Pyx_RaiseArgtupleInvalid("cy_entropy_similarity_identity_search", 1, 8, 8, 5); __PYX_ERR(0, 11, __pyx_L3_error)
         }
         CYTHON_FALLTHROUGH;
         case  6:
-        if (likely((values[6] = __Pyx_PyDict_GetItemStr(__pyx_kwds, __pyx_n_s_search_type)) != 0)) kw_args--;
+        if (likely((values[6] = __Pyx_PyDict_GetItemStr(__pyx_kwds, __pyx_n_s_search_spectra_idx_min)) != 0)) kw_args--;
         else {
-          __Pyx_RaiseArgtupleInvalid("entropy_similarity_search_fast", 1, 10, 10, 6); __PYX_ERR(0, 11, __pyx_L3_error)
+          __Pyx_RaiseArgtupleInvalid("cy_entropy_similarity_identity_search", 1, 8, 8, 6); __PYX_ERR(0, 11, __pyx_L3_error)
         }
         CYTHON_FALLTHROUGH;
         case  7:
-        if (likely((values[7] = __Pyx_PyDict_GetItemStr(__pyx_kwds, __pyx_n_s_search_spectra_idx_min)) != 0)) kw_args--;
+        if (likely((values[7] = __Pyx_PyDict_GetItemStr(__pyx_kwds, __pyx_n_s_search_spectra_idx_max)) != 0)) kw_args--;
         else {
-          __Pyx_RaiseArgtupleInvalid("entropy_similarity_search_fast", 1, 10, 10, 7); __PYX_ERR(0, 11, __pyx_L3_error)
-        }
-        CYTHON_FALLTHROUGH;
-        case  8:
-        if (likely((values[8] = __Pyx_PyDict_GetItemStr(__pyx_kwds, __pyx_n_s_search_spectra_idx_max)) != 0)) kw_args--;
-        else {
-          __Pyx_RaiseArgtupleInvalid("entropy_similarity_search_fast", 1, 10, 10, 8); __PYX_ERR(0, 11, __pyx_L3_error)
-        }
-        CYTHON_FALLTHROUGH;
-        case  9:
-        if (likely((values[9] = __Pyx_PyDict_GetItemStr(__pyx_kwds, __pyx_n_s_search_array)) != 0)) kw_args--;
-        else {
-          __Pyx_RaiseArgtupleInvalid("entropy_similarity_search_fast", 1, 10, 10, 9); __PYX_ERR(0, 11, __pyx_L3_error)
+          __Pyx_RaiseArgtupleInvalid("cy_entropy_similarity_identity_search", 1, 8, 8, 7); __PYX_ERR(0, 11, __pyx_L3_error)
         }
       }
       if (unlikely(kw_args > 0)) {
-        if (unlikely(__Pyx_ParseOptionalKeywords(__pyx_kwds, __pyx_pyargnames, 0, values, pos_args, "entropy_similarity_search_fast") < 0)) __PYX_ERR(0, 11, __pyx_L3_error)
+        if (unlikely(__Pyx_ParseOptionalKeywords(__pyx_kwds, __pyx_pyargnames, 0, values, pos_args, "cy_entropy_similarity_identity_search") < 0)) __PYX_ERR(0, 11, __pyx_L3_error)
       }
-    } else if (PyTuple_GET_SIZE(__pyx_args) != 10) {
+    } else if (PyTuple_GET_SIZE(__pyx_args) != 8) {
       goto __pyx_L5_argtuple_error;
     } else {
       values[0] = PyTuple_GET_ITEM(__pyx_args, 0);
       values[1] = PyTuple_GET_ITEM(__pyx_args, 1);
       values[2] = PyTuple_GET_ITEM(__pyx_args, 2);
       values[3] = PyTuple_GET_ITEM(__pyx_args, 3);
       values[4] = PyTuple_GET_ITEM(__pyx_args, 4);
       values[5] = PyTuple_GET_ITEM(__pyx_args, 5);
       values[6] = PyTuple_GET_ITEM(__pyx_args, 6);
       values[7] = PyTuple_GET_ITEM(__pyx_args, 7);
-      values[8] = PyTuple_GET_ITEM(__pyx_args, 8);
-      values[9] = PyTuple_GET_ITEM(__pyx_args, 9);
     }
     __pyx_v_product_mz_idx_min = __Pyx_PyInt_As_npy_int64(values[0]); if (unlikely((__pyx_v_product_mz_idx_min == ((npy_int64)-1)) && PyErr_Occurred())) __PYX_ERR(0, 11, __pyx_L3_error)
     __pyx_v_product_mz_idx_max = __Pyx_PyInt_As_npy_int64(values[1]); if (unlikely((__pyx_v_product_mz_idx_max == ((npy_int64)-1)) && PyErr_Occurred())) __PYX_ERR(0, 11, __pyx_L3_error)
     __pyx_v_intensity = __pyx_PyFloat_AsFloat(values[2]); if (unlikely((__pyx_v_intensity == ((npy_float32)-1)) && PyErr_Occurred())) __PYX_ERR(0, 12, __pyx_L3_error)
-    __pyx_v_mixed_spectra_entropy = __Pyx_PyObject_to_MemoryviewSlice_ds_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_float32(values[3], PyBUF_WRITABLE); if (unlikely(!__pyx_v_mixed_spectra_entropy.memview)) __PYX_ERR(0, 12, __pyx_L3_error)
-    __pyx_v_library_peaks_intensity = __Pyx_PyObject_to_MemoryviewSlice_ds_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_float32__const__(values[4], 0); if (unlikely(!__pyx_v_library_peaks_intensity.memview)) __PYX_ERR(0, 13, __pyx_L3_error)
-    __pyx_v_library_spec_idx_array = __Pyx_PyObject_to_MemoryviewSlice_ds_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_uint_32__const__(values[5], 0); if (unlikely(!__pyx_v_library_spec_idx_array.memview)) __PYX_ERR(0, 13, __pyx_L3_error)
-    __pyx_v_search_type = __Pyx_PyInt_As_int(values[6]); if (unlikely((__pyx_v_search_type == (int)-1) && PyErr_Occurred())) __PYX_ERR(0, 14, __pyx_L3_error)
-    __pyx_v_search_spectra_idx_min = __Pyx_PyInt_As_npy_int64(values[7]); if (unlikely((__pyx_v_search_spectra_idx_min == ((npy_int64)-1)) && PyErr_Occurred())) __PYX_ERR(0, 14, __pyx_L3_error)
-    __pyx_v_search_spectra_idx_max = __Pyx_PyInt_As_npy_int64(values[8]); if (unlikely((__pyx_v_search_spectra_idx_max == ((npy_int64)-1)) && PyErr_Occurred())) __PYX_ERR(0, 14, __pyx_L3_error)
-    __pyx_v_search_array = __Pyx_PyObject_to_MemoryviewSlice_ds_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_int_8__const__(values[9], 0); if (unlikely(!__pyx_v_search_array.memview)) __PYX_ERR(0, 14, __pyx_L3_error)
+    __pyx_v_entropy_similarity = __Pyx_PyObject_to_MemoryviewSlice_ds_nn___pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_float32(values[3], PyBUF_WRITABLE); if (unlikely(!__pyx_v_entropy_similarity.memview)) __PYX_ERR(0, 12, __pyx_L3_error)
+    __pyx_v_library_peaks_intensity = __Pyx_PyObject_to_MemoryviewSlice_ds_nn___pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_float32__const__(values[4], 0); if (unlikely(!__pyx_v_library_peaks_intensity.memview)) __PYX_ERR(0, 13, __pyx_L3_error)
+    __pyx_v_library_spec_idx_array = __Pyx_PyObject_to_MemoryviewSlice_ds_nn___pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_uint_32__const__(values[5], 0); if (unlikely(!__pyx_v_library_spec_idx_array.memview)) __PYX_ERR(0, 13, __pyx_L3_error)
+    __pyx_v_search_spectra_idx_min = __Pyx_PyInt_As_npy_int64(values[6]); if (unlikely((__pyx_v_search_spectra_idx_min == ((npy_int64)-1)) && PyErr_Occurred())) __PYX_ERR(0, 14, __pyx_L3_error)
+    __pyx_v_search_spectra_idx_max = __Pyx_PyInt_As_npy_int64(values[7]); if (unlikely((__pyx_v_search_spectra_idx_max == ((npy_int64)-1)) && PyErr_Occurred())) __PYX_ERR(0, 14, __pyx_L3_error)
   }
   goto __pyx_L4_argument_unpacking_done;
   __pyx_L5_argtuple_error:;
-  __Pyx_RaiseArgtupleInvalid("entropy_similarity_search_fast", 1, 10, 10, PyTuple_GET_SIZE(__pyx_args)); __PYX_ERR(0, 11, __pyx_L3_error)
+  __Pyx_RaiseArgtupleInvalid("cy_entropy_similarity_identity_search", 1, 8, 8, PyTuple_GET_SIZE(__pyx_args)); __PYX_ERR(0, 11, __pyx_L3_error)
   __pyx_L3_error:;
-  __Pyx_AddTraceback("ms_entropy.tools.fast_entropy.entropy_similarity_search_fast", __pyx_clineno, __pyx_lineno, __pyx_filename);
+  __Pyx_AddTraceback("ms_entropy.entropy_search.fast_flash_entropy_search_cpython.cy_entropy_similarity_identity_search", __pyx_clineno, __pyx_lineno, __pyx_filename);
   __Pyx_RefNannyFinishContext();
   return NULL;
   __pyx_L4_argument_unpacking_done:;
-  __pyx_r = __pyx_pf_10ms_entropy_5tools_12fast_entropy_entropy_similarity_search_fast(__pyx_self, __pyx_v_product_mz_idx_min, __pyx_v_product_mz_idx_max, __pyx_v_intensity, __pyx_v_mixed_spectra_entropy, __pyx_v_library_peaks_intensity, __pyx_v_library_spec_idx_array, __pyx_v_search_type, __pyx_v_search_spectra_idx_min, __pyx_v_search_spectra_idx_max, __pyx_v_search_array);
+  __pyx_r = __pyx_pf_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_cy_entropy_similarity_identity_search(__pyx_self, __pyx_v_product_mz_idx_min, __pyx_v_product_mz_idx_max, __pyx_v_intensity, __pyx_v_entropy_similarity, __pyx_v_library_peaks_intensity, __pyx_v_library_spec_idx_array, __pyx_v_search_spectra_idx_min, __pyx_v_search_spectra_idx_max);
 
   /* function exit code */
   __Pyx_RefNannyFinishContext();
   return __pyx_r;
 }
 
-static PyObject *__pyx_pf_10ms_entropy_5tools_12fast_entropy_entropy_similarity_search_fast(CYTHON_UNUSED PyObject *__pyx_self, __pyx_t_10ms_entropy_5tools_12fast_entropy_int_64 __pyx_v_product_mz_idx_min, __pyx_t_10ms_entropy_5tools_12fast_entropy_int_64 __pyx_v_product_mz_idx_max, __pyx_t_10ms_entropy_5tools_12fast_entropy_float32 __pyx_v_intensity, __Pyx_memviewslice __pyx_v_mixed_spectra_entropy, __Pyx_memviewslice __pyx_v_library_peaks_intensity, __Pyx_memviewslice __pyx_v_library_spec_idx_array, int __pyx_v_search_type, __pyx_t_10ms_entropy_5tools_12fast_entropy_int_64 __pyx_v_search_spectra_idx_min, __pyx_t_10ms_entropy_5tools_12fast_entropy_int_64 __pyx_v_search_spectra_idx_max, __Pyx_memviewslice __pyx_v_search_array) {
+static PyObject *__pyx_pf_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_cy_entropy_similarity_identity_search(CYTHON_UNUSED PyObject *__pyx_self, __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_int_64 __pyx_v_product_mz_idx_min, __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_int_64 __pyx_v_product_mz_idx_max, __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_float32 __pyx_v_intensity, __Pyx_memviewslice __pyx_v_entropy_similarity, __Pyx_memviewslice __pyx_v_library_peaks_intensity, __Pyx_memviewslice __pyx_v_library_spec_idx_array, __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_int_64 __pyx_v_search_spectra_idx_min, __pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_int_64 __pyx_v_search_spectra_idx_max) {
   PyObject *__pyx_r = NULL;
   __Pyx_RefNannyDeclarations
   PyObject *__pyx_t_1 = NULL;
   int __pyx_lineno = 0;
   const char *__pyx_filename = NULL;
   int __pyx_clineno = 0;
-  __Pyx_RefNannySetupContext("entropy_similarity_search_fast", 0);
+  __Pyx_RefNannySetupContext("cy_entropy_similarity_identity_search", 0);
   __Pyx_XDECREF(__pyx_r);
-  if (unlikely(!__pyx_v_mixed_spectra_entropy.memview)) { __Pyx_RaiseUnboundLocalError("mixed_spectra_entropy"); __PYX_ERR(0, 11, __pyx_L1_error) }
+  if (unlikely(!__pyx_v_entropy_similarity.memview)) { __Pyx_RaiseUnboundLocalError("entropy_similarity"); __PYX_ERR(0, 11, __pyx_L1_error) }
   if (unlikely(!__pyx_v_library_peaks_intensity.memview)) { __Pyx_RaiseUnboundLocalError("library_peaks_intensity"); __PYX_ERR(0, 11, __pyx_L1_error) }
   if (unlikely(!__pyx_v_library_spec_idx_array.memview)) { __Pyx_RaiseUnboundLocalError("library_spec_idx_array"); __PYX_ERR(0, 11, __pyx_L1_error) }
-  if (unlikely(!__pyx_v_search_array.memview)) { __Pyx_RaiseUnboundLocalError("search_array"); __PYX_ERR(0, 11, __pyx_L1_error) }
-  __pyx_t_1 = __Pyx_void_to_None(__pyx_f_10ms_entropy_5tools_12fast_entropy_entropy_similarity_search_fast(__pyx_v_product_mz_idx_min, __pyx_v_product_mz_idx_max, __pyx_v_intensity, __pyx_v_mixed_spectra_entropy, __pyx_v_library_peaks_intensity, __pyx_v_library_spec_idx_array, __pyx_v_search_type, __pyx_v_search_spectra_idx_min, __pyx_v_search_spectra_idx_max, __pyx_v_search_array, 0)); if (unlikely(!__pyx_t_1)) __PYX_ERR(0, 11, __pyx_L1_error)
+  __pyx_t_1 = __Pyx_void_to_None(__pyx_f_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_cy_entropy_similarity_identity_search(__pyx_v_product_mz_idx_min, __pyx_v_product_mz_idx_max, __pyx_v_intensity, __pyx_v_entropy_similarity, __pyx_v_library_peaks_intensity, __pyx_v_library_spec_idx_array, __pyx_v_search_spectra_idx_min, __pyx_v_search_spectra_idx_max, 0)); if (unlikely(!__pyx_t_1)) __PYX_ERR(0, 11, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_1);
   __pyx_r = __pyx_t_1;
   __pyx_t_1 = 0;
   goto __pyx_L0;
 
   /* function exit code */
   __pyx_L1_error:;
   __Pyx_XDECREF(__pyx_t_1);
-  __Pyx_AddTraceback("ms_entropy.tools.fast_entropy.entropy_similarity_search_fast", __pyx_clineno, __pyx_lineno, __pyx_filename);
+  __Pyx_AddTraceback("ms_entropy.entropy_search.fast_flash_entropy_search_cpython.cy_entropy_similarity_identity_search", __pyx_clineno, __pyx_lineno, __pyx_filename);
   __pyx_r = NULL;
   __pyx_L0:;
-  __PYX_XDEC_MEMVIEW(&__pyx_v_mixed_spectra_entropy, 1);
+  __PYX_XDEC_MEMVIEW(&__pyx_v_entropy_similarity, 1);
   __PYX_XDEC_MEMVIEW(&__pyx_v_library_peaks_intensity, 1);
   __PYX_XDEC_MEMVIEW(&__pyx_v_library_spec_idx_array, 1);
-  __PYX_XDEC_MEMVIEW(&__pyx_v_search_array, 1);
-  __Pyx_XGIVEREF(__pyx_r);
-  __Pyx_RefNannyFinishContext();
-  return __pyx_r;
-}
-
-/* "ms_entropy/tools/fast_entropy.pyx":42
- * 
- * 
- * cpdef apply_weight_to_intensity(float32[:,::1] spectrum):             # <<<<<<<<<<<<<<
- *     """
- *     Apply the weight to the intensity.
- */
-
-static PyObject *__pyx_pw_10ms_entropy_5tools_12fast_entropy_3apply_weight_to_intensity(PyObject *__pyx_self, PyObject *__pyx_arg_spectrum); /*proto*/
-static PyObject *__pyx_f_10ms_entropy_5tools_12fast_entropy_apply_weight_to_intensity(__Pyx_memviewslice __pyx_v_spectrum, CYTHON_UNUSED int __pyx_skip_dispatch) {
-  double __pyx_v_entropy;
-  double __pyx_v_weight;
-  double __pyx_v_intensity_sum;
-  __Pyx_memviewslice __pyx_v_spectrum_weighted = { 0, 0, { 0 }, { 0 }, { 0 } };
-  Py_ssize_t __pyx_v_i;
-  PyObject *__pyx_r = NULL;
-  __Pyx_RefNannyDeclarations
-  PyObject *__pyx_t_1 = NULL;
-  PyObject *__pyx_t_2 = NULL;
-  PyObject *__pyx_t_3 = NULL;
-  PyObject *__pyx_t_4 = NULL;
-  __Pyx_memviewslice __pyx_t_5 = { 0, 0, { 0 }, { 0 }, { 0 } };
-  int __pyx_t_6;
-  Py_ssize_t __pyx_t_7;
-  Py_ssize_t __pyx_t_8;
-  Py_ssize_t __pyx_t_9;
-  Py_ssize_t __pyx_t_10;
-  Py_ssize_t __pyx_t_11;
-  Py_ssize_t __pyx_t_12;
-  Py_ssize_t __pyx_t_13;
-  int __pyx_lineno = 0;
-  const char *__pyx_filename = NULL;
-  int __pyx_clineno = 0;
-  __Pyx_RefNannySetupContext("apply_weight_to_intensity", 0);
-
-  /* "ms_entropy/tools/fast_entropy.pyx":47
- *     The spectrum is a 2D array like: [[m/z, intensity], [m/z, intensity], ...]
- *     """
- *     cdef double entropy=spectral_entropy(spectrum)             # <<<<<<<<<<<<<<
- *     cdef double weight, intensity_sum
- *     cdef float32[:,::1] spectrum_weighted = np.copy(spectrum)
- */
-  __pyx_v_entropy = __pyx_f_10ms_entropy_5tools_12fast_entropy_spectral_entropy(__pyx_v_spectrum, 0);
-
-  /* "ms_entropy/tools/fast_entropy.pyx":49
- *     cdef double entropy=spectral_entropy(spectrum)
- *     cdef double weight, intensity_sum
- *     cdef float32[:,::1] spectrum_weighted = np.copy(spectrum)             # <<<<<<<<<<<<<<
- *     if entropy<3:
- *         weight = 0.25 + 0.25 * entropy
- */
-  __Pyx_GetModuleGlobalName(__pyx_t_2, __pyx_n_s_np); if (unlikely(!__pyx_t_2)) __PYX_ERR(0, 49, __pyx_L1_error)
-  __Pyx_GOTREF(__pyx_t_2);
-  __pyx_t_3 = __Pyx_PyObject_GetAttrStr(__pyx_t_2, __pyx_n_s_copy); if (unlikely(!__pyx_t_3)) __PYX_ERR(0, 49, __pyx_L1_error)
-  __Pyx_GOTREF(__pyx_t_3);
-  __Pyx_DECREF(__pyx_t_2); __pyx_t_2 = 0;
-  __pyx_t_2 = __pyx_memoryview_fromslice(__pyx_v_spectrum, 2, (PyObject *(*)(char *)) __pyx_memview_get_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_float32, (int (*)(char *, PyObject *)) __pyx_memview_set_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_float32, 0);; if (unlikely(!__pyx_t_2)) __PYX_ERR(0, 49, __pyx_L1_error)
-  __Pyx_GOTREF(__pyx_t_2);
-  __pyx_t_4 = NULL;
-  if (CYTHON_UNPACK_METHODS && unlikely(PyMethod_Check(__pyx_t_3))) {
-    __pyx_t_4 = PyMethod_GET_SELF(__pyx_t_3);
-    if (likely(__pyx_t_4)) {
-      PyObject* function = PyMethod_GET_FUNCTION(__pyx_t_3);
-      __Pyx_INCREF(__pyx_t_4);
-      __Pyx_INCREF(function);
-      __Pyx_DECREF_SET(__pyx_t_3, function);
-    }
-  }
-  __pyx_t_1 = (__pyx_t_4) ? __Pyx_PyObject_Call2Args(__pyx_t_3, __pyx_t_4, __pyx_t_2) : __Pyx_PyObject_CallOneArg(__pyx_t_3, __pyx_t_2);
-  __Pyx_XDECREF(__pyx_t_4); __pyx_t_4 = 0;
-  __Pyx_DECREF(__pyx_t_2); __pyx_t_2 = 0;
-  if (unlikely(!__pyx_t_1)) __PYX_ERR(0, 49, __pyx_L1_error)
-  __Pyx_GOTREF(__pyx_t_1);
-  __Pyx_DECREF(__pyx_t_3); __pyx_t_3 = 0;
-  __pyx_t_5 = __Pyx_PyObject_to_MemoryviewSlice_d_dc_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_float32(__pyx_t_1, PyBUF_WRITABLE); if (unlikely(!__pyx_t_5.memview)) __PYX_ERR(0, 49, __pyx_L1_error)
-  __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
-  __pyx_v_spectrum_weighted = __pyx_t_5;
-  __pyx_t_5.memview = NULL;
-  __pyx_t_5.data = NULL;
-
-  /* "ms_entropy/tools/fast_entropy.pyx":50
- *     cdef double weight, intensity_sum
- *     cdef float32[:,::1] spectrum_weighted = np.copy(spectrum)
- *     if entropy<3:             # <<<<<<<<<<<<<<
- *         weight = 0.25 + 0.25 * entropy
- *         intensity_sum = 0.
- */
-  __pyx_t_6 = ((__pyx_v_entropy < 3.0) != 0);
-  if (__pyx_t_6) {
-
-    /* "ms_entropy/tools/fast_entropy.pyx":51
- *     cdef float32[:,::1] spectrum_weighted = np.copy(spectrum)
- *     if entropy<3:
- *         weight = 0.25 + 0.25 * entropy             # <<<<<<<<<<<<<<
- *         intensity_sum = 0.
- *         for i in range(spectrum_weighted.shape[0]):
- */
-    __pyx_v_weight = (0.25 + (0.25 * __pyx_v_entropy));
-
-    /* "ms_entropy/tools/fast_entropy.pyx":52
- *     if entropy<3:
- *         weight = 0.25 + 0.25 * entropy
- *         intensity_sum = 0.             # <<<<<<<<<<<<<<
- *         for i in range(spectrum_weighted.shape[0]):
- *             spectrum_weighted[i,1] = pow(spectrum_weighted[i,1],weight)
- */
-    __pyx_v_intensity_sum = 0.;
-
-    /* "ms_entropy/tools/fast_entropy.pyx":53
- *         weight = 0.25 + 0.25 * entropy
- *         intensity_sum = 0.
- *         for i in range(spectrum_weighted.shape[0]):             # <<<<<<<<<<<<<<
- *             spectrum_weighted[i,1] = pow(spectrum_weighted[i,1],weight)
- *             intensity_sum += spectrum_weighted[i,1]
- */
-    __pyx_t_7 = (__pyx_v_spectrum_weighted.shape[0]);
-    __pyx_t_8 = __pyx_t_7;
-    for (__pyx_t_9 = 0; __pyx_t_9 < __pyx_t_8; __pyx_t_9+=1) {
-      __pyx_v_i = __pyx_t_9;
-
-      /* "ms_entropy/tools/fast_entropy.pyx":54
- *         intensity_sum = 0.
- *         for i in range(spectrum_weighted.shape[0]):
- *             spectrum_weighted[i,1] = pow(spectrum_weighted[i,1],weight)             # <<<<<<<<<<<<<<
- *             intensity_sum += spectrum_weighted[i,1]
- * 
- */
-      __pyx_t_10 = __pyx_v_i;
-      __pyx_t_11 = 1;
-      __pyx_t_12 = __pyx_v_i;
-      __pyx_t_13 = 1;
-      *((__pyx_t_10ms_entropy_5tools_12fast_entropy_float32 *) ( /* dim=1 */ ((char *) (((__pyx_t_10ms_entropy_5tools_12fast_entropy_float32 *) ( /* dim=0 */ (__pyx_v_spectrum_weighted.data + __pyx_t_12 * __pyx_v_spectrum_weighted.strides[0]) )) + __pyx_t_13)) )) = pow((*((__pyx_t_10ms_entropy_5tools_12fast_entropy_float32 *) ( /* dim=1 */ ((char *) (((__pyx_t_10ms_entropy_5tools_12fast_entropy_float32 *) ( /* dim=0 */ (__pyx_v_spectrum_weighted.data + __pyx_t_10 * __pyx_v_spectrum_weighted.strides[0]) )) + __pyx_t_11)) ))), __pyx_v_weight);
-
-      /* "ms_entropy/tools/fast_entropy.pyx":55
- *         for i in range(spectrum_weighted.shape[0]):
- *             spectrum_weighted[i,1] = pow(spectrum_weighted[i,1],weight)
- *             intensity_sum += spectrum_weighted[i,1]             # <<<<<<<<<<<<<<
- * 
- *         if intensity_sum>0:
- */
-      __pyx_t_11 = __pyx_v_i;
-      __pyx_t_10 = 1;
-      __pyx_v_intensity_sum = (__pyx_v_intensity_sum + (*((__pyx_t_10ms_entropy_5tools_12fast_entropy_float32 *) ( /* dim=1 */ ((char *) (((__pyx_t_10ms_entropy_5tools_12fast_entropy_float32 *) ( /* dim=0 */ (__pyx_v_spectrum_weighted.data + __pyx_t_11 * __pyx_v_spectrum_weighted.strides[0]) )) + __pyx_t_10)) ))));
-    }
-
-    /* "ms_entropy/tools/fast_entropy.pyx":57
- *             intensity_sum += spectrum_weighted[i,1]
- * 
- *         if intensity_sum>0:             # <<<<<<<<<<<<<<
- *             for i in range(spectrum_weighted.shape[0]):
- *                 spectrum_weighted[i,1] /= intensity_sum
- */
-    __pyx_t_6 = ((__pyx_v_intensity_sum > 0.0) != 0);
-    if (__pyx_t_6) {
-
-      /* "ms_entropy/tools/fast_entropy.pyx":58
- * 
- *         if intensity_sum>0:
- *             for i in range(spectrum_weighted.shape[0]):             # <<<<<<<<<<<<<<
- *                 spectrum_weighted[i,1] /= intensity_sum
- * 
- */
-      __pyx_t_7 = (__pyx_v_spectrum_weighted.shape[0]);
-      __pyx_t_8 = __pyx_t_7;
-      for (__pyx_t_9 = 0; __pyx_t_9 < __pyx_t_8; __pyx_t_9+=1) {
-        __pyx_v_i = __pyx_t_9;
-
-        /* "ms_entropy/tools/fast_entropy.pyx":59
- *         if intensity_sum>0:
- *             for i in range(spectrum_weighted.shape[0]):
- *                 spectrum_weighted[i,1] /= intensity_sum             # <<<<<<<<<<<<<<
- * 
- *     return spectrum_weighted
- */
-        __pyx_t_10 = __pyx_v_i;
-        __pyx_t_11 = 1;
-        *((__pyx_t_10ms_entropy_5tools_12fast_entropy_float32 *) ( /* dim=1 */ ((char *) (((__pyx_t_10ms_entropy_5tools_12fast_entropy_float32 *) ( /* dim=0 */ (__pyx_v_spectrum_weighted.data + __pyx_t_10 * __pyx_v_spectrum_weighted.strides[0]) )) + __pyx_t_11)) )) /= __pyx_v_intensity_sum;
-      }
-
-      /* "ms_entropy/tools/fast_entropy.pyx":57
- *             intensity_sum += spectrum_weighted[i,1]
- * 
- *         if intensity_sum>0:             # <<<<<<<<<<<<<<
- *             for i in range(spectrum_weighted.shape[0]):
- *                 spectrum_weighted[i,1] /= intensity_sum
- */
-    }
-
-    /* "ms_entropy/tools/fast_entropy.pyx":50
- *     cdef double weight, intensity_sum
- *     cdef float32[:,::1] spectrum_weighted = np.copy(spectrum)
- *     if entropy<3:             # <<<<<<<<<<<<<<
- *         weight = 0.25 + 0.25 * entropy
- *         intensity_sum = 0.
- */
-  }
-
-  /* "ms_entropy/tools/fast_entropy.pyx":61
- *                 spectrum_weighted[i,1] /= intensity_sum
- * 
- *     return spectrum_weighted             # <<<<<<<<<<<<<<
- * 
- * cpdef double spectral_entropy(float32[:,::1] spectrum) nogil:
- */
-  __Pyx_XDECREF(__pyx_r);
-  __pyx_t_1 = __pyx_memoryview_fromslice(__pyx_v_spectrum_weighted, 2, (PyObject *(*)(char *)) __pyx_memview_get_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_float32, (int (*)(char *, PyObject *)) __pyx_memview_set_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_float32, 0);; if (unlikely(!__pyx_t_1)) __PYX_ERR(0, 61, __pyx_L1_error)
-  __Pyx_GOTREF(__pyx_t_1);
-  __pyx_r = __pyx_t_1;
-  __pyx_t_1 = 0;
-  goto __pyx_L0;
-
-  /* "ms_entropy/tools/fast_entropy.pyx":42
- * 
- * 
- * cpdef apply_weight_to_intensity(float32[:,::1] spectrum):             # <<<<<<<<<<<<<<
- *     """
- *     Apply the weight to the intensity.
- */
-
-  /* function exit code */
-  __pyx_L1_error:;
-  __Pyx_XDECREF(__pyx_t_1);
-  __Pyx_XDECREF(__pyx_t_2);
-  __Pyx_XDECREF(__pyx_t_3);
-  __Pyx_XDECREF(__pyx_t_4);
-  __PYX_XDEC_MEMVIEW(&__pyx_t_5, 1);
-  __Pyx_AddTraceback("ms_entropy.tools.fast_entropy.apply_weight_to_intensity", __pyx_clineno, __pyx_lineno, __pyx_filename);
-  __pyx_r = 0;
-  __pyx_L0:;
-  __PYX_XDEC_MEMVIEW(&__pyx_v_spectrum_weighted, 1);
-  __Pyx_XGIVEREF(__pyx_r);
-  __Pyx_RefNannyFinishContext();
-  return __pyx_r;
-}
-
-/* Python wrapper */
-static PyObject *__pyx_pw_10ms_entropy_5tools_12fast_entropy_3apply_weight_to_intensity(PyObject *__pyx_self, PyObject *__pyx_arg_spectrum); /*proto*/
-static char __pyx_doc_10ms_entropy_5tools_12fast_entropy_2apply_weight_to_intensity[] = "\n    Apply the weight to the intensity.\n    The spectrum is a 2D array like: [[m/z, intensity], [m/z, intensity], ...]\n    ";
-static PyObject *__pyx_pw_10ms_entropy_5tools_12fast_entropy_3apply_weight_to_intensity(PyObject *__pyx_self, PyObject *__pyx_arg_spectrum) {
-  __Pyx_memviewslice __pyx_v_spectrum = { 0, 0, { 0 }, { 0 }, { 0 } };
-  int __pyx_lineno = 0;
-  const char *__pyx_filename = NULL;
-  int __pyx_clineno = 0;
-  PyObject *__pyx_r = 0;
-  __Pyx_RefNannyDeclarations
-  __Pyx_RefNannySetupContext("apply_weight_to_intensity (wrapper)", 0);
-  assert(__pyx_arg_spectrum); {
-    __pyx_v_spectrum = __Pyx_PyObject_to_MemoryviewSlice_d_dc_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_float32(__pyx_arg_spectrum, PyBUF_WRITABLE); if (unlikely(!__pyx_v_spectrum.memview)) __PYX_ERR(0, 42, __pyx_L3_error)
-  }
-  goto __pyx_L4_argument_unpacking_done;
-  __pyx_L3_error:;
-  __Pyx_AddTraceback("ms_entropy.tools.fast_entropy.apply_weight_to_intensity", __pyx_clineno, __pyx_lineno, __pyx_filename);
-  __Pyx_RefNannyFinishContext();
-  return NULL;
-  __pyx_L4_argument_unpacking_done:;
-  __pyx_r = __pyx_pf_10ms_entropy_5tools_12fast_entropy_2apply_weight_to_intensity(__pyx_self, __pyx_v_spectrum);
-
-  /* function exit code */
-  __Pyx_RefNannyFinishContext();
-  return __pyx_r;
-}
-
-static PyObject *__pyx_pf_10ms_entropy_5tools_12fast_entropy_2apply_weight_to_intensity(CYTHON_UNUSED PyObject *__pyx_self, __Pyx_memviewslice __pyx_v_spectrum) {
-  PyObject *__pyx_r = NULL;
-  __Pyx_RefNannyDeclarations
-  PyObject *__pyx_t_1 = NULL;
-  int __pyx_lineno = 0;
-  const char *__pyx_filename = NULL;
-  int __pyx_clineno = 0;
-  __Pyx_RefNannySetupContext("apply_weight_to_intensity", 0);
-  __Pyx_XDECREF(__pyx_r);
-  if (unlikely(!__pyx_v_spectrum.memview)) { __Pyx_RaiseUnboundLocalError("spectrum"); __PYX_ERR(0, 42, __pyx_L1_error) }
-  __pyx_t_1 = __pyx_f_10ms_entropy_5tools_12fast_entropy_apply_weight_to_intensity(__pyx_v_spectrum, 0); if (unlikely(!__pyx_t_1)) __PYX_ERR(0, 42, __pyx_L1_error)
-  __Pyx_GOTREF(__pyx_t_1);
-  __pyx_r = __pyx_t_1;
-  __pyx_t_1 = 0;
-  goto __pyx_L0;
-
-  /* function exit code */
-  __pyx_L1_error:;
-  __Pyx_XDECREF(__pyx_t_1);
-  __Pyx_AddTraceback("ms_entropy.tools.fast_entropy.apply_weight_to_intensity", __pyx_clineno, __pyx_lineno, __pyx_filename);
-  __pyx_r = NULL;
-  __pyx_L0:;
-  __PYX_XDEC_MEMVIEW(&__pyx_v_spectrum, 1);
-  __Pyx_XGIVEREF(__pyx_r);
-  __Pyx_RefNannyFinishContext();
-  return __pyx_r;
-}
-
-/* "ms_entropy/tools/fast_entropy.pyx":63
- *     return spectrum_weighted
- * 
- * cpdef double spectral_entropy(float32[:,::1] spectrum) nogil:             # <<<<<<<<<<<<<<
- *     """
- *     Compute the spectral entropy of a spectrum. The intensity need to be pre-normalized, the function will not do it.
- */
-
-static PyObject *__pyx_pw_10ms_entropy_5tools_12fast_entropy_5spectral_entropy(PyObject *__pyx_self, PyObject *__pyx_arg_spectrum); /*proto*/
-static double __pyx_f_10ms_entropy_5tools_12fast_entropy_spectral_entropy(__Pyx_memviewslice __pyx_v_spectrum, CYTHON_UNUSED int __pyx_skip_dispatch) {
-  double __pyx_v_entropy;
-  __pyx_t_10ms_entropy_5tools_12fast_entropy_float32 __pyx_v_intensity;
-  Py_ssize_t __pyx_v_i;
-  double __pyx_r;
-  Py_ssize_t __pyx_t_1;
-  Py_ssize_t __pyx_t_2;
-  Py_ssize_t __pyx_t_3;
-  Py_ssize_t __pyx_t_4;
-  Py_ssize_t __pyx_t_5;
-  int __pyx_t_6;
-
-  /* "ms_entropy/tools/fast_entropy.pyx":67
- *     Compute the spectral entropy of a spectrum. The intensity need to be pre-normalized, the function will not do it.
- *     """
- *     cdef double entropy=0.             # <<<<<<<<<<<<<<
- *     cdef float32 intensity
- *     for i in range(spectrum.shape[0]):
- */
-  __pyx_v_entropy = 0.;
-
-  /* "ms_entropy/tools/fast_entropy.pyx":69
- *     cdef double entropy=0.
- *     cdef float32 intensity
- *     for i in range(spectrum.shape[0]):             # <<<<<<<<<<<<<<
- *         intensity=spectrum[i,1]
- *         if intensity>0:
- */
-  __pyx_t_1 = (__pyx_v_spectrum.shape[0]);
-  __pyx_t_2 = __pyx_t_1;
-  for (__pyx_t_3 = 0; __pyx_t_3 < __pyx_t_2; __pyx_t_3+=1) {
-    __pyx_v_i = __pyx_t_3;
-
-    /* "ms_entropy/tools/fast_entropy.pyx":70
- *     cdef float32 intensity
- *     for i in range(spectrum.shape[0]):
- *         intensity=spectrum[i,1]             # <<<<<<<<<<<<<<
- *         if intensity>0:
- *             entropy+=-intensity*log(intensity)
- */
-    __pyx_t_4 = __pyx_v_i;
-    __pyx_t_5 = 1;
-    __pyx_v_intensity = (*((__pyx_t_10ms_entropy_5tools_12fast_entropy_float32 *) ( /* dim=1 */ ((char *) (((__pyx_t_10ms_entropy_5tools_12fast_entropy_float32 *) ( /* dim=0 */ (__pyx_v_spectrum.data + __pyx_t_4 * __pyx_v_spectrum.strides[0]) )) + __pyx_t_5)) )));
-
-    /* "ms_entropy/tools/fast_entropy.pyx":71
- *     for i in range(spectrum.shape[0]):
- *         intensity=spectrum[i,1]
- *         if intensity>0:             # <<<<<<<<<<<<<<
- *             entropy+=-intensity*log(intensity)
- *     return entropy
- */
-    __pyx_t_6 = ((__pyx_v_intensity > 0.0) != 0);
-    if (__pyx_t_6) {
-
-      /* "ms_entropy/tools/fast_entropy.pyx":72
- *         intensity=spectrum[i,1]
- *         if intensity>0:
- *             entropy+=-intensity*log(intensity)             # <<<<<<<<<<<<<<
- *     return entropy
- * 
- */
-      __pyx_v_entropy = (__pyx_v_entropy + ((-__pyx_v_intensity) * log(__pyx_v_intensity)));
-
-      /* "ms_entropy/tools/fast_entropy.pyx":71
- *     for i in range(spectrum.shape[0]):
- *         intensity=spectrum[i,1]
- *         if intensity>0:             # <<<<<<<<<<<<<<
- *             entropy+=-intensity*log(intensity)
- *     return entropy
- */
-    }
-  }
-
-  /* "ms_entropy/tools/fast_entropy.pyx":73
- *         if intensity>0:
- *             entropy+=-intensity*log(intensity)
- *     return entropy             # <<<<<<<<<<<<<<
- * 
- */
-  __pyx_r = __pyx_v_entropy;
-  goto __pyx_L0;
-
-  /* "ms_entropy/tools/fast_entropy.pyx":63
- *     return spectrum_weighted
- * 
- * cpdef double spectral_entropy(float32[:,::1] spectrum) nogil:             # <<<<<<<<<<<<<<
- *     """
- *     Compute the spectral entropy of a spectrum. The intensity need to be pre-normalized, the function will not do it.
- */
-
-  /* function exit code */
-  __pyx_L0:;
-  return __pyx_r;
-}
-
-/* Python wrapper */
-static PyObject *__pyx_pw_10ms_entropy_5tools_12fast_entropy_5spectral_entropy(PyObject *__pyx_self, PyObject *__pyx_arg_spectrum); /*proto*/
-static char __pyx_doc_10ms_entropy_5tools_12fast_entropy_4spectral_entropy[] = "\n    Compute the spectral entropy of a spectrum. The intensity need to be pre-normalized, the function will not do it.\n    ";
-static PyObject *__pyx_pw_10ms_entropy_5tools_12fast_entropy_5spectral_entropy(PyObject *__pyx_self, PyObject *__pyx_arg_spectrum) {
-  __Pyx_memviewslice __pyx_v_spectrum = { 0, 0, { 0 }, { 0 }, { 0 } };
-  int __pyx_lineno = 0;
-  const char *__pyx_filename = NULL;
-  int __pyx_clineno = 0;
-  PyObject *__pyx_r = 0;
-  __Pyx_RefNannyDeclarations
-  __Pyx_RefNannySetupContext("spectral_entropy (wrapper)", 0);
-  assert(__pyx_arg_spectrum); {
-    __pyx_v_spectrum = __Pyx_PyObject_to_MemoryviewSlice_d_dc_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_float32(__pyx_arg_spectrum, PyBUF_WRITABLE); if (unlikely(!__pyx_v_spectrum.memview)) __PYX_ERR(0, 63, __pyx_L3_error)
-  }
-  goto __pyx_L4_argument_unpacking_done;
-  __pyx_L3_error:;
-  __Pyx_AddTraceback("ms_entropy.tools.fast_entropy.spectral_entropy", __pyx_clineno, __pyx_lineno, __pyx_filename);
-  __Pyx_RefNannyFinishContext();
-  return NULL;
-  __pyx_L4_argument_unpacking_done:;
-  __pyx_r = __pyx_pf_10ms_entropy_5tools_12fast_entropy_4spectral_entropy(__pyx_self, __pyx_v_spectrum);
-
-  /* function exit code */
-  __Pyx_RefNannyFinishContext();
-  return __pyx_r;
-}
-
-static PyObject *__pyx_pf_10ms_entropy_5tools_12fast_entropy_4spectral_entropy(CYTHON_UNUSED PyObject *__pyx_self, __Pyx_memviewslice __pyx_v_spectrum) {
-  PyObject *__pyx_r = NULL;
-  __Pyx_RefNannyDeclarations
-  PyObject *__pyx_t_1 = NULL;
-  int __pyx_lineno = 0;
-  const char *__pyx_filename = NULL;
-  int __pyx_clineno = 0;
-  __Pyx_RefNannySetupContext("spectral_entropy", 0);
-  __Pyx_XDECREF(__pyx_r);
-  if (unlikely(!__pyx_v_spectrum.memview)) { __Pyx_RaiseUnboundLocalError("spectrum"); __PYX_ERR(0, 63, __pyx_L1_error) }
-  __pyx_t_1 = PyFloat_FromDouble(__pyx_f_10ms_entropy_5tools_12fast_entropy_spectral_entropy(__pyx_v_spectrum, 0)); if (unlikely(!__pyx_t_1)) __PYX_ERR(0, 63, __pyx_L1_error)
-  __Pyx_GOTREF(__pyx_t_1);
-  __pyx_r = __pyx_t_1;
-  __pyx_t_1 = 0;
-  goto __pyx_L0;
-
-  /* function exit code */
-  __pyx_L1_error:;
-  __Pyx_XDECREF(__pyx_t_1);
-  __Pyx_AddTraceback("ms_entropy.tools.fast_entropy.spectral_entropy", __pyx_clineno, __pyx_lineno, __pyx_filename);
-  __pyx_r = NULL;
-  __pyx_L0:;
-  __PYX_XDEC_MEMVIEW(&__pyx_v_spectrum, 1);
   __Pyx_XGIVEREF(__pyx_r);
   __Pyx_RefNannyFinishContext();
   return __pyx_r;
 }
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":734
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":734
  * ctypedef npy_cdouble     complex_t
  * 
  * cdef inline object PyArray_MultiIterNew1(a):             # <<<<<<<<<<<<<<
  *     return PyArray_MultiIterNew(1, <void*>a)
  * 
  */
 
@@ -3500,29 +2967,29 @@
   __Pyx_RefNannyDeclarations
   PyObject *__pyx_t_1 = NULL;
   int __pyx_lineno = 0;
   const char *__pyx_filename = NULL;
   int __pyx_clineno = 0;
   __Pyx_RefNannySetupContext("PyArray_MultiIterNew1", 0);
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":735
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":735
  * 
  * cdef inline object PyArray_MultiIterNew1(a):
  *     return PyArray_MultiIterNew(1, <void*>a)             # <<<<<<<<<<<<<<
  * 
  * cdef inline object PyArray_MultiIterNew2(a, b):
  */
   __Pyx_XDECREF(__pyx_r);
   __pyx_t_1 = PyArray_MultiIterNew(1, ((void *)__pyx_v_a)); if (unlikely(!__pyx_t_1)) __PYX_ERR(1, 735, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_1);
   __pyx_r = __pyx_t_1;
   __pyx_t_1 = 0;
   goto __pyx_L0;
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":734
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":734
  * ctypedef npy_cdouble     complex_t
  * 
  * cdef inline object PyArray_MultiIterNew1(a):             # <<<<<<<<<<<<<<
  *     return PyArray_MultiIterNew(1, <void*>a)
  * 
  */
 
@@ -3533,15 +3000,15 @@
   __pyx_r = 0;
   __pyx_L0:;
   __Pyx_XGIVEREF(__pyx_r);
   __Pyx_RefNannyFinishContext();
   return __pyx_r;
 }
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":737
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":737
  *     return PyArray_MultiIterNew(1, <void*>a)
  * 
  * cdef inline object PyArray_MultiIterNew2(a, b):             # <<<<<<<<<<<<<<
  *     return PyArray_MultiIterNew(2, <void*>a, <void*>b)
  * 
  */
 
@@ -3550,29 +3017,29 @@
   __Pyx_RefNannyDeclarations
   PyObject *__pyx_t_1 = NULL;
   int __pyx_lineno = 0;
   const char *__pyx_filename = NULL;
   int __pyx_clineno = 0;
   __Pyx_RefNannySetupContext("PyArray_MultiIterNew2", 0);
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":738
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":738
  * 
  * cdef inline object PyArray_MultiIterNew2(a, b):
  *     return PyArray_MultiIterNew(2, <void*>a, <void*>b)             # <<<<<<<<<<<<<<
  * 
  * cdef inline object PyArray_MultiIterNew3(a, b, c):
  */
   __Pyx_XDECREF(__pyx_r);
   __pyx_t_1 = PyArray_MultiIterNew(2, ((void *)__pyx_v_a), ((void *)__pyx_v_b)); if (unlikely(!__pyx_t_1)) __PYX_ERR(1, 738, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_1);
   __pyx_r = __pyx_t_1;
   __pyx_t_1 = 0;
   goto __pyx_L0;
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":737
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":737
  *     return PyArray_MultiIterNew(1, <void*>a)
  * 
  * cdef inline object PyArray_MultiIterNew2(a, b):             # <<<<<<<<<<<<<<
  *     return PyArray_MultiIterNew(2, <void*>a, <void*>b)
  * 
  */
 
@@ -3583,15 +3050,15 @@
   __pyx_r = 0;
   __pyx_L0:;
   __Pyx_XGIVEREF(__pyx_r);
   __Pyx_RefNannyFinishContext();
   return __pyx_r;
 }
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":740
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":740
  *     return PyArray_MultiIterNew(2, <void*>a, <void*>b)
  * 
  * cdef inline object PyArray_MultiIterNew3(a, b, c):             # <<<<<<<<<<<<<<
  *     return PyArray_MultiIterNew(3, <void*>a, <void*>b, <void*> c)
  * 
  */
 
@@ -3600,29 +3067,29 @@
   __Pyx_RefNannyDeclarations
   PyObject *__pyx_t_1 = NULL;
   int __pyx_lineno = 0;
   const char *__pyx_filename = NULL;
   int __pyx_clineno = 0;
   __Pyx_RefNannySetupContext("PyArray_MultiIterNew3", 0);
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":741
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":741
  * 
  * cdef inline object PyArray_MultiIterNew3(a, b, c):
  *     return PyArray_MultiIterNew(3, <void*>a, <void*>b, <void*> c)             # <<<<<<<<<<<<<<
  * 
  * cdef inline object PyArray_MultiIterNew4(a, b, c, d):
  */
   __Pyx_XDECREF(__pyx_r);
   __pyx_t_1 = PyArray_MultiIterNew(3, ((void *)__pyx_v_a), ((void *)__pyx_v_b), ((void *)__pyx_v_c)); if (unlikely(!__pyx_t_1)) __PYX_ERR(1, 741, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_1);
   __pyx_r = __pyx_t_1;
   __pyx_t_1 = 0;
   goto __pyx_L0;
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":740
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":740
  *     return PyArray_MultiIterNew(2, <void*>a, <void*>b)
  * 
  * cdef inline object PyArray_MultiIterNew3(a, b, c):             # <<<<<<<<<<<<<<
  *     return PyArray_MultiIterNew(3, <void*>a, <void*>b, <void*> c)
  * 
  */
 
@@ -3633,15 +3100,15 @@
   __pyx_r = 0;
   __pyx_L0:;
   __Pyx_XGIVEREF(__pyx_r);
   __Pyx_RefNannyFinishContext();
   return __pyx_r;
 }
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":743
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":743
  *     return PyArray_MultiIterNew(3, <void*>a, <void*>b, <void*> c)
  * 
  * cdef inline object PyArray_MultiIterNew4(a, b, c, d):             # <<<<<<<<<<<<<<
  *     return PyArray_MultiIterNew(4, <void*>a, <void*>b, <void*>c, <void*> d)
  * 
  */
 
@@ -3650,29 +3117,29 @@
   __Pyx_RefNannyDeclarations
   PyObject *__pyx_t_1 = NULL;
   int __pyx_lineno = 0;
   const char *__pyx_filename = NULL;
   int __pyx_clineno = 0;
   __Pyx_RefNannySetupContext("PyArray_MultiIterNew4", 0);
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":744
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":744
  * 
  * cdef inline object PyArray_MultiIterNew4(a, b, c, d):
  *     return PyArray_MultiIterNew(4, <void*>a, <void*>b, <void*>c, <void*> d)             # <<<<<<<<<<<<<<
  * 
  * cdef inline object PyArray_MultiIterNew5(a, b, c, d, e):
  */
   __Pyx_XDECREF(__pyx_r);
   __pyx_t_1 = PyArray_MultiIterNew(4, ((void *)__pyx_v_a), ((void *)__pyx_v_b), ((void *)__pyx_v_c), ((void *)__pyx_v_d)); if (unlikely(!__pyx_t_1)) __PYX_ERR(1, 744, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_1);
   __pyx_r = __pyx_t_1;
   __pyx_t_1 = 0;
   goto __pyx_L0;
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":743
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":743
  *     return PyArray_MultiIterNew(3, <void*>a, <void*>b, <void*> c)
  * 
  * cdef inline object PyArray_MultiIterNew4(a, b, c, d):             # <<<<<<<<<<<<<<
  *     return PyArray_MultiIterNew(4, <void*>a, <void*>b, <void*>c, <void*> d)
  * 
  */
 
@@ -3683,15 +3150,15 @@
   __pyx_r = 0;
   __pyx_L0:;
   __Pyx_XGIVEREF(__pyx_r);
   __Pyx_RefNannyFinishContext();
   return __pyx_r;
 }
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":746
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":746
  *     return PyArray_MultiIterNew(4, <void*>a, <void*>b, <void*>c, <void*> d)
  * 
  * cdef inline object PyArray_MultiIterNew5(a, b, c, d, e):             # <<<<<<<<<<<<<<
  *     return PyArray_MultiIterNew(5, <void*>a, <void*>b, <void*>c, <void*> d, <void*> e)
  * 
  */
 
@@ -3700,29 +3167,29 @@
   __Pyx_RefNannyDeclarations
   PyObject *__pyx_t_1 = NULL;
   int __pyx_lineno = 0;
   const char *__pyx_filename = NULL;
   int __pyx_clineno = 0;
   __Pyx_RefNannySetupContext("PyArray_MultiIterNew5", 0);
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":747
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":747
  * 
  * cdef inline object PyArray_MultiIterNew5(a, b, c, d, e):
  *     return PyArray_MultiIterNew(5, <void*>a, <void*>b, <void*>c, <void*> d, <void*> e)             # <<<<<<<<<<<<<<
  * 
  * cdef inline tuple PyDataType_SHAPE(dtype d):
  */
   __Pyx_XDECREF(__pyx_r);
   __pyx_t_1 = PyArray_MultiIterNew(5, ((void *)__pyx_v_a), ((void *)__pyx_v_b), ((void *)__pyx_v_c), ((void *)__pyx_v_d), ((void *)__pyx_v_e)); if (unlikely(!__pyx_t_1)) __PYX_ERR(1, 747, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_1);
   __pyx_r = __pyx_t_1;
   __pyx_t_1 = 0;
   goto __pyx_L0;
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":746
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":746
  *     return PyArray_MultiIterNew(4, <void*>a, <void*>b, <void*>c, <void*> d)
  * 
  * cdef inline object PyArray_MultiIterNew5(a, b, c, d, e):             # <<<<<<<<<<<<<<
  *     return PyArray_MultiIterNew(5, <void*>a, <void*>b, <void*>c, <void*> d, <void*> e)
  * 
  */
 
@@ -3733,212 +3200,212 @@
   __pyx_r = 0;
   __pyx_L0:;
   __Pyx_XGIVEREF(__pyx_r);
   __Pyx_RefNannyFinishContext();
   return __pyx_r;
 }
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":749
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":749
  *     return PyArray_MultiIterNew(5, <void*>a, <void*>b, <void*>c, <void*> d, <void*> e)
  * 
  * cdef inline tuple PyDataType_SHAPE(dtype d):             # <<<<<<<<<<<<<<
  *     if PyDataType_HASSUBARRAY(d):
  *         return <tuple>d.subarray.shape
  */
 
 static CYTHON_INLINE PyObject *__pyx_f_5numpy_PyDataType_SHAPE(PyArray_Descr *__pyx_v_d) {
   PyObject *__pyx_r = NULL;
   __Pyx_RefNannyDeclarations
   int __pyx_t_1;
   __Pyx_RefNannySetupContext("PyDataType_SHAPE", 0);
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":750
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":750
  * 
  * cdef inline tuple PyDataType_SHAPE(dtype d):
  *     if PyDataType_HASSUBARRAY(d):             # <<<<<<<<<<<<<<
  *         return <tuple>d.subarray.shape
  *     else:
  */
   __pyx_t_1 = (PyDataType_HASSUBARRAY(__pyx_v_d) != 0);
   if (__pyx_t_1) {
 
-    /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":751
+    /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":751
  * cdef inline tuple PyDataType_SHAPE(dtype d):
  *     if PyDataType_HASSUBARRAY(d):
  *         return <tuple>d.subarray.shape             # <<<<<<<<<<<<<<
  *     else:
  *         return ()
  */
     __Pyx_XDECREF(__pyx_r);
     __Pyx_INCREF(((PyObject*)__pyx_v_d->subarray->shape));
     __pyx_r = ((PyObject*)__pyx_v_d->subarray->shape);
     goto __pyx_L0;
 
-    /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":750
+    /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":750
  * 
  * cdef inline tuple PyDataType_SHAPE(dtype d):
  *     if PyDataType_HASSUBARRAY(d):             # <<<<<<<<<<<<<<
  *         return <tuple>d.subarray.shape
  *     else:
  */
   }
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":753
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":753
  *         return <tuple>d.subarray.shape
  *     else:
  *         return ()             # <<<<<<<<<<<<<<
  * 
  * 
  */
   /*else*/ {
     __Pyx_XDECREF(__pyx_r);
     __Pyx_INCREF(__pyx_empty_tuple);
     __pyx_r = __pyx_empty_tuple;
     goto __pyx_L0;
   }
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":749
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":749
  *     return PyArray_MultiIterNew(5, <void*>a, <void*>b, <void*>c, <void*> d, <void*> e)
  * 
  * cdef inline tuple PyDataType_SHAPE(dtype d):             # <<<<<<<<<<<<<<
  *     if PyDataType_HASSUBARRAY(d):
  *         return <tuple>d.subarray.shape
  */
 
   /* function exit code */
   __pyx_L0:;
   __Pyx_XGIVEREF(__pyx_r);
   __Pyx_RefNannyFinishContext();
   return __pyx_r;
 }
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":928
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":928
  *     int _import_umath() except -1
  * 
  * cdef inline void set_array_base(ndarray arr, object base):             # <<<<<<<<<<<<<<
  *     Py_INCREF(base) # important to do this before stealing the reference below!
  *     PyArray_SetBaseObject(arr, base)
  */
 
 static CYTHON_INLINE void __pyx_f_5numpy_set_array_base(PyArrayObject *__pyx_v_arr, PyObject *__pyx_v_base) {
   __Pyx_RefNannyDeclarations
   __Pyx_RefNannySetupContext("set_array_base", 0);
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":929
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":929
  * 
  * cdef inline void set_array_base(ndarray arr, object base):
  *     Py_INCREF(base) # important to do this before stealing the reference below!             # <<<<<<<<<<<<<<
  *     PyArray_SetBaseObject(arr, base)
  * 
  */
   Py_INCREF(__pyx_v_base);
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":930
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":930
  * cdef inline void set_array_base(ndarray arr, object base):
  *     Py_INCREF(base) # important to do this before stealing the reference below!
  *     PyArray_SetBaseObject(arr, base)             # <<<<<<<<<<<<<<
  * 
  * cdef inline object get_array_base(ndarray arr):
  */
   (void)(PyArray_SetBaseObject(__pyx_v_arr, __pyx_v_base));
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":928
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":928
  *     int _import_umath() except -1
  * 
  * cdef inline void set_array_base(ndarray arr, object base):             # <<<<<<<<<<<<<<
  *     Py_INCREF(base) # important to do this before stealing the reference below!
  *     PyArray_SetBaseObject(arr, base)
  */
 
   /* function exit code */
   __Pyx_RefNannyFinishContext();
 }
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":932
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":932
  *     PyArray_SetBaseObject(arr, base)
  * 
  * cdef inline object get_array_base(ndarray arr):             # <<<<<<<<<<<<<<
  *     base = PyArray_BASE(arr)
  *     if base is NULL:
  */
 
 static CYTHON_INLINE PyObject *__pyx_f_5numpy_get_array_base(PyArrayObject *__pyx_v_arr) {
   PyObject *__pyx_v_base;
   PyObject *__pyx_r = NULL;
   __Pyx_RefNannyDeclarations
   int __pyx_t_1;
   __Pyx_RefNannySetupContext("get_array_base", 0);
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":933
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":933
  * 
  * cdef inline object get_array_base(ndarray arr):
  *     base = PyArray_BASE(arr)             # <<<<<<<<<<<<<<
  *     if base is NULL:
  *         return None
  */
   __pyx_v_base = PyArray_BASE(__pyx_v_arr);
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":934
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":934
  * cdef inline object get_array_base(ndarray arr):
  *     base = PyArray_BASE(arr)
  *     if base is NULL:             # <<<<<<<<<<<<<<
  *         return None
  *     return <object>base
  */
   __pyx_t_1 = ((__pyx_v_base == NULL) != 0);
   if (__pyx_t_1) {
 
-    /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":935
+    /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":935
  *     base = PyArray_BASE(arr)
  *     if base is NULL:
  *         return None             # <<<<<<<<<<<<<<
  *     return <object>base
  * 
  */
     __Pyx_XDECREF(__pyx_r);
     __pyx_r = Py_None; __Pyx_INCREF(Py_None);
     goto __pyx_L0;
 
-    /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":934
+    /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":934
  * cdef inline object get_array_base(ndarray arr):
  *     base = PyArray_BASE(arr)
  *     if base is NULL:             # <<<<<<<<<<<<<<
  *         return None
  *     return <object>base
  */
   }
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":936
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":936
  *     if base is NULL:
  *         return None
  *     return <object>base             # <<<<<<<<<<<<<<
  * 
  * # Versions of the import_* functions which are more suitable for
  */
   __Pyx_XDECREF(__pyx_r);
   __Pyx_INCREF(((PyObject *)__pyx_v_base));
   __pyx_r = ((PyObject *)__pyx_v_base);
   goto __pyx_L0;
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":932
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":932
  *     PyArray_SetBaseObject(arr, base)
  * 
  * cdef inline object get_array_base(ndarray arr):             # <<<<<<<<<<<<<<
  *     base = PyArray_BASE(arr)
  *     if base is NULL:
  */
 
   /* function exit code */
   __pyx_L0:;
   __Pyx_XGIVEREF(__pyx_r);
   __Pyx_RefNannyFinishContext();
   return __pyx_r;
 }
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":940
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":940
  * # Versions of the import_* functions which are more suitable for
  * # Cython code.
  * cdef inline int import_array() except -1:             # <<<<<<<<<<<<<<
  *     try:
  *         __pyx_import_array()
  */
 
@@ -3954,15 +3421,15 @@
   PyObject *__pyx_t_7 = NULL;
   PyObject *__pyx_t_8 = NULL;
   int __pyx_lineno = 0;
   const char *__pyx_filename = NULL;
   int __pyx_clineno = 0;
   __Pyx_RefNannySetupContext("import_array", 0);
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":941
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":941
  * # Cython code.
  * cdef inline int import_array() except -1:
  *     try:             # <<<<<<<<<<<<<<
  *         __pyx_import_array()
  *     except Exception:
  */
   {
@@ -3970,53 +3437,53 @@
     __Pyx_PyThreadState_assign
     __Pyx_ExceptionSave(&__pyx_t_1, &__pyx_t_2, &__pyx_t_3);
     __Pyx_XGOTREF(__pyx_t_1);
     __Pyx_XGOTREF(__pyx_t_2);
     __Pyx_XGOTREF(__pyx_t_3);
     /*try:*/ {
 
-      /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":942
+      /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":942
  * cdef inline int import_array() except -1:
  *     try:
  *         __pyx_import_array()             # <<<<<<<<<<<<<<
  *     except Exception:
  *         raise ImportError("numpy.core.multiarray failed to import")
  */
       __pyx_t_4 = _import_array(); if (unlikely(__pyx_t_4 == ((int)-1))) __PYX_ERR(1, 942, __pyx_L3_error)
 
-      /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":941
+      /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":941
  * # Cython code.
  * cdef inline int import_array() except -1:
  *     try:             # <<<<<<<<<<<<<<
  *         __pyx_import_array()
  *     except Exception:
  */
     }
     __Pyx_XDECREF(__pyx_t_1); __pyx_t_1 = 0;
     __Pyx_XDECREF(__pyx_t_2); __pyx_t_2 = 0;
     __Pyx_XDECREF(__pyx_t_3); __pyx_t_3 = 0;
     goto __pyx_L8_try_end;
     __pyx_L3_error:;
 
-    /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":943
+    /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":943
  *     try:
  *         __pyx_import_array()
  *     except Exception:             # <<<<<<<<<<<<<<
  *         raise ImportError("numpy.core.multiarray failed to import")
  * 
  */
     __pyx_t_4 = __Pyx_PyErr_ExceptionMatches(((PyObject *)(&((PyTypeObject*)PyExc_Exception)[0])));
     if (__pyx_t_4) {
       __Pyx_AddTraceback("numpy.import_array", __pyx_clineno, __pyx_lineno, __pyx_filename);
       if (__Pyx_GetException(&__pyx_t_5, &__pyx_t_6, &__pyx_t_7) < 0) __PYX_ERR(1, 943, __pyx_L5_except_error)
       __Pyx_GOTREF(__pyx_t_5);
       __Pyx_GOTREF(__pyx_t_6);
       __Pyx_GOTREF(__pyx_t_7);
 
-      /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":944
+      /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":944
  *         __pyx_import_array()
  *     except Exception:
  *         raise ImportError("numpy.core.multiarray failed to import")             # <<<<<<<<<<<<<<
  * 
  * cdef inline int import_umath() except -1:
  */
       __pyx_t_8 = __Pyx_PyObject_Call(__pyx_builtin_ImportError, __pyx_tuple_, NULL); if (unlikely(!__pyx_t_8)) __PYX_ERR(1, 944, __pyx_L5_except_error)
@@ -4024,30 +3491,30 @@
       __Pyx_Raise(__pyx_t_8, 0, 0, 0);
       __Pyx_DECREF(__pyx_t_8); __pyx_t_8 = 0;
       __PYX_ERR(1, 944, __pyx_L5_except_error)
     }
     goto __pyx_L5_except_error;
     __pyx_L5_except_error:;
 
-    /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":941
+    /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":941
  * # Cython code.
  * cdef inline int import_array() except -1:
  *     try:             # <<<<<<<<<<<<<<
  *         __pyx_import_array()
  *     except Exception:
  */
     __Pyx_XGIVEREF(__pyx_t_1);
     __Pyx_XGIVEREF(__pyx_t_2);
     __Pyx_XGIVEREF(__pyx_t_3);
     __Pyx_ExceptionReset(__pyx_t_1, __pyx_t_2, __pyx_t_3);
     goto __pyx_L1_error;
     __pyx_L8_try_end:;
   }
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":940
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":940
  * # Versions of the import_* functions which are more suitable for
  * # Cython code.
  * cdef inline int import_array() except -1:             # <<<<<<<<<<<<<<
  *     try:
  *         __pyx_import_array()
  */
 
@@ -4062,15 +3529,15 @@
   __Pyx_AddTraceback("numpy.import_array", __pyx_clineno, __pyx_lineno, __pyx_filename);
   __pyx_r = -1;
   __pyx_L0:;
   __Pyx_RefNannyFinishContext();
   return __pyx_r;
 }
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":946
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":946
  *         raise ImportError("numpy.core.multiarray failed to import")
  * 
  * cdef inline int import_umath() except -1:             # <<<<<<<<<<<<<<
  *     try:
  *         _import_umath()
  */
 
@@ -4086,15 +3553,15 @@
   PyObject *__pyx_t_7 = NULL;
   PyObject *__pyx_t_8 = NULL;
   int __pyx_lineno = 0;
   const char *__pyx_filename = NULL;
   int __pyx_clineno = 0;
   __Pyx_RefNannySetupContext("import_umath", 0);
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":947
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":947
  * 
  * cdef inline int import_umath() except -1:
  *     try:             # <<<<<<<<<<<<<<
  *         _import_umath()
  *     except Exception:
  */
   {
@@ -4102,53 +3569,53 @@
     __Pyx_PyThreadState_assign
     __Pyx_ExceptionSave(&__pyx_t_1, &__pyx_t_2, &__pyx_t_3);
     __Pyx_XGOTREF(__pyx_t_1);
     __Pyx_XGOTREF(__pyx_t_2);
     __Pyx_XGOTREF(__pyx_t_3);
     /*try:*/ {
 
-      /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":948
+      /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":948
  * cdef inline int import_umath() except -1:
  *     try:
  *         _import_umath()             # <<<<<<<<<<<<<<
  *     except Exception:
  *         raise ImportError("numpy.core.umath failed to import")
  */
       __pyx_t_4 = _import_umath(); if (unlikely(__pyx_t_4 == ((int)-1))) __PYX_ERR(1, 948, __pyx_L3_error)
 
-      /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":947
+      /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":947
  * 
  * cdef inline int import_umath() except -1:
  *     try:             # <<<<<<<<<<<<<<
  *         _import_umath()
  *     except Exception:
  */
     }
     __Pyx_XDECREF(__pyx_t_1); __pyx_t_1 = 0;
     __Pyx_XDECREF(__pyx_t_2); __pyx_t_2 = 0;
     __Pyx_XDECREF(__pyx_t_3); __pyx_t_3 = 0;
     goto __pyx_L8_try_end;
     __pyx_L3_error:;
 
-    /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":949
+    /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":949
  *     try:
  *         _import_umath()
  *     except Exception:             # <<<<<<<<<<<<<<
  *         raise ImportError("numpy.core.umath failed to import")
  * 
  */
     __pyx_t_4 = __Pyx_PyErr_ExceptionMatches(((PyObject *)(&((PyTypeObject*)PyExc_Exception)[0])));
     if (__pyx_t_4) {
       __Pyx_AddTraceback("numpy.import_umath", __pyx_clineno, __pyx_lineno, __pyx_filename);
       if (__Pyx_GetException(&__pyx_t_5, &__pyx_t_6, &__pyx_t_7) < 0) __PYX_ERR(1, 949, __pyx_L5_except_error)
       __Pyx_GOTREF(__pyx_t_5);
       __Pyx_GOTREF(__pyx_t_6);
       __Pyx_GOTREF(__pyx_t_7);
 
-      /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":950
+      /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":950
  *         _import_umath()
  *     except Exception:
  *         raise ImportError("numpy.core.umath failed to import")             # <<<<<<<<<<<<<<
  * 
  * cdef inline int import_ufunc() except -1:
  */
       __pyx_t_8 = __Pyx_PyObject_Call(__pyx_builtin_ImportError, __pyx_tuple__2, NULL); if (unlikely(!__pyx_t_8)) __PYX_ERR(1, 950, __pyx_L5_except_error)
@@ -4156,30 +3623,30 @@
       __Pyx_Raise(__pyx_t_8, 0, 0, 0);
       __Pyx_DECREF(__pyx_t_8); __pyx_t_8 = 0;
       __PYX_ERR(1, 950, __pyx_L5_except_error)
     }
     goto __pyx_L5_except_error;
     __pyx_L5_except_error:;
 
-    /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":947
+    /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":947
  * 
  * cdef inline int import_umath() except -1:
  *     try:             # <<<<<<<<<<<<<<
  *         _import_umath()
  *     except Exception:
  */
     __Pyx_XGIVEREF(__pyx_t_1);
     __Pyx_XGIVEREF(__pyx_t_2);
     __Pyx_XGIVEREF(__pyx_t_3);
     __Pyx_ExceptionReset(__pyx_t_1, __pyx_t_2, __pyx_t_3);
     goto __pyx_L1_error;
     __pyx_L8_try_end:;
   }
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":946
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":946
  *         raise ImportError("numpy.core.multiarray failed to import")
  * 
  * cdef inline int import_umath() except -1:             # <<<<<<<<<<<<<<
  *     try:
  *         _import_umath()
  */
 
@@ -4194,15 +3661,15 @@
   __Pyx_AddTraceback("numpy.import_umath", __pyx_clineno, __pyx_lineno, __pyx_filename);
   __pyx_r = -1;
   __pyx_L0:;
   __Pyx_RefNannyFinishContext();
   return __pyx_r;
 }
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":952
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":952
  *         raise ImportError("numpy.core.umath failed to import")
  * 
  * cdef inline int import_ufunc() except -1:             # <<<<<<<<<<<<<<
  *     try:
  *         _import_umath()
  */
 
@@ -4218,15 +3685,15 @@
   PyObject *__pyx_t_7 = NULL;
   PyObject *__pyx_t_8 = NULL;
   int __pyx_lineno = 0;
   const char *__pyx_filename = NULL;
   int __pyx_clineno = 0;
   __Pyx_RefNannySetupContext("import_ufunc", 0);
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":953
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":953
  * 
  * cdef inline int import_ufunc() except -1:
  *     try:             # <<<<<<<<<<<<<<
  *         _import_umath()
  *     except Exception:
  */
   {
@@ -4234,53 +3701,53 @@
     __Pyx_PyThreadState_assign
     __Pyx_ExceptionSave(&__pyx_t_1, &__pyx_t_2, &__pyx_t_3);
     __Pyx_XGOTREF(__pyx_t_1);
     __Pyx_XGOTREF(__pyx_t_2);
     __Pyx_XGOTREF(__pyx_t_3);
     /*try:*/ {
 
-      /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":954
+      /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":954
  * cdef inline int import_ufunc() except -1:
  *     try:
  *         _import_umath()             # <<<<<<<<<<<<<<
  *     except Exception:
  *         raise ImportError("numpy.core.umath failed to import")
  */
       __pyx_t_4 = _import_umath(); if (unlikely(__pyx_t_4 == ((int)-1))) __PYX_ERR(1, 954, __pyx_L3_error)
 
-      /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":953
+      /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":953
  * 
  * cdef inline int import_ufunc() except -1:
  *     try:             # <<<<<<<<<<<<<<
  *         _import_umath()
  *     except Exception:
  */
     }
     __Pyx_XDECREF(__pyx_t_1); __pyx_t_1 = 0;
     __Pyx_XDECREF(__pyx_t_2); __pyx_t_2 = 0;
     __Pyx_XDECREF(__pyx_t_3); __pyx_t_3 = 0;
     goto __pyx_L8_try_end;
     __pyx_L3_error:;
 
-    /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":955
+    /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":955
  *     try:
  *         _import_umath()
  *     except Exception:             # <<<<<<<<<<<<<<
  *         raise ImportError("numpy.core.umath failed to import")
  * 
  */
     __pyx_t_4 = __Pyx_PyErr_ExceptionMatches(((PyObject *)(&((PyTypeObject*)PyExc_Exception)[0])));
     if (__pyx_t_4) {
       __Pyx_AddTraceback("numpy.import_ufunc", __pyx_clineno, __pyx_lineno, __pyx_filename);
       if (__Pyx_GetException(&__pyx_t_5, &__pyx_t_6, &__pyx_t_7) < 0) __PYX_ERR(1, 955, __pyx_L5_except_error)
       __Pyx_GOTREF(__pyx_t_5);
       __Pyx_GOTREF(__pyx_t_6);
       __Pyx_GOTREF(__pyx_t_7);
 
-      /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":956
+      /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":956
  *         _import_umath()
  *     except Exception:
  *         raise ImportError("numpy.core.umath failed to import")             # <<<<<<<<<<<<<<
  * 
  * cdef extern from *:
  */
       __pyx_t_8 = __Pyx_PyObject_Call(__pyx_builtin_ImportError, __pyx_tuple__2, NULL); if (unlikely(!__pyx_t_8)) __PYX_ERR(1, 956, __pyx_L5_except_error)
@@ -4288,30 +3755,30 @@
       __Pyx_Raise(__pyx_t_8, 0, 0, 0);
       __Pyx_DECREF(__pyx_t_8); __pyx_t_8 = 0;
       __PYX_ERR(1, 956, __pyx_L5_except_error)
     }
     goto __pyx_L5_except_error;
     __pyx_L5_except_error:;
 
-    /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":953
+    /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":953
  * 
  * cdef inline int import_ufunc() except -1:
  *     try:             # <<<<<<<<<<<<<<
  *         _import_umath()
  *     except Exception:
  */
     __Pyx_XGIVEREF(__pyx_t_1);
     __Pyx_XGIVEREF(__pyx_t_2);
     __Pyx_XGIVEREF(__pyx_t_3);
     __Pyx_ExceptionReset(__pyx_t_1, __pyx_t_2, __pyx_t_3);
     goto __pyx_L1_error;
     __pyx_L8_try_end:;
   }
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":952
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":952
  *         raise ImportError("numpy.core.umath failed to import")
  * 
  * cdef inline int import_ufunc() except -1:             # <<<<<<<<<<<<<<
  *     try:
  *         _import_umath()
  */
 
@@ -4326,176 +3793,176 @@
   __Pyx_AddTraceback("numpy.import_ufunc", __pyx_clineno, __pyx_lineno, __pyx_filename);
   __pyx_r = -1;
   __pyx_L0:;
   __Pyx_RefNannyFinishContext();
   return __pyx_r;
 }
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":966
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":966
  * 
  * 
  * cdef inline bint is_timedelta64_object(object obj):             # <<<<<<<<<<<<<<
  *     """
  *     Cython equivalent of `isinstance(obj, np.timedelta64)`
  */
 
 static CYTHON_INLINE int __pyx_f_5numpy_is_timedelta64_object(PyObject *__pyx_v_obj) {
   int __pyx_r;
   __Pyx_RefNannyDeclarations
   __Pyx_RefNannySetupContext("is_timedelta64_object", 0);
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":978
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":978
  *     bool
  *     """
  *     return PyObject_TypeCheck(obj, &PyTimedeltaArrType_Type)             # <<<<<<<<<<<<<<
  * 
  * 
  */
   __pyx_r = PyObject_TypeCheck(__pyx_v_obj, (&PyTimedeltaArrType_Type));
   goto __pyx_L0;
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":966
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":966
  * 
  * 
  * cdef inline bint is_timedelta64_object(object obj):             # <<<<<<<<<<<<<<
  *     """
  *     Cython equivalent of `isinstance(obj, np.timedelta64)`
  */
 
   /* function exit code */
   __pyx_L0:;
   __Pyx_RefNannyFinishContext();
   return __pyx_r;
 }
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":981
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":981
  * 
  * 
  * cdef inline bint is_datetime64_object(object obj):             # <<<<<<<<<<<<<<
  *     """
  *     Cython equivalent of `isinstance(obj, np.datetime64)`
  */
 
 static CYTHON_INLINE int __pyx_f_5numpy_is_datetime64_object(PyObject *__pyx_v_obj) {
   int __pyx_r;
   __Pyx_RefNannyDeclarations
   __Pyx_RefNannySetupContext("is_datetime64_object", 0);
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":993
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":993
  *     bool
  *     """
  *     return PyObject_TypeCheck(obj, &PyDatetimeArrType_Type)             # <<<<<<<<<<<<<<
  * 
  * 
  */
   __pyx_r = PyObject_TypeCheck(__pyx_v_obj, (&PyDatetimeArrType_Type));
   goto __pyx_L0;
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":981
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":981
  * 
  * 
  * cdef inline bint is_datetime64_object(object obj):             # <<<<<<<<<<<<<<
  *     """
  *     Cython equivalent of `isinstance(obj, np.datetime64)`
  */
 
   /* function exit code */
   __pyx_L0:;
   __Pyx_RefNannyFinishContext();
   return __pyx_r;
 }
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":996
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":996
  * 
  * 
  * cdef inline npy_datetime get_datetime64_value(object obj) nogil:             # <<<<<<<<<<<<<<
  *     """
  *     returns the int64 value underlying scalar numpy datetime64 object
  */
 
 static CYTHON_INLINE npy_datetime __pyx_f_5numpy_get_datetime64_value(PyObject *__pyx_v_obj) {
   npy_datetime __pyx_r;
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":1003
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":1003
  *     also needed.  That can be found using `get_datetime64_unit`.
  *     """
  *     return (<PyDatetimeScalarObject*>obj).obval             # <<<<<<<<<<<<<<
  * 
  * 
  */
   __pyx_r = ((PyDatetimeScalarObject *)__pyx_v_obj)->obval;
   goto __pyx_L0;
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":996
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":996
  * 
  * 
  * cdef inline npy_datetime get_datetime64_value(object obj) nogil:             # <<<<<<<<<<<<<<
  *     """
  *     returns the int64 value underlying scalar numpy datetime64 object
  */
 
   /* function exit code */
   __pyx_L0:;
   return __pyx_r;
 }
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":1006
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":1006
  * 
  * 
  * cdef inline npy_timedelta get_timedelta64_value(object obj) nogil:             # <<<<<<<<<<<<<<
  *     """
  *     returns the int64 value underlying scalar numpy timedelta64 object
  */
 
 static CYTHON_INLINE npy_timedelta __pyx_f_5numpy_get_timedelta64_value(PyObject *__pyx_v_obj) {
   npy_timedelta __pyx_r;
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":1010
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":1010
  *     returns the int64 value underlying scalar numpy timedelta64 object
  *     """
  *     return (<PyTimedeltaScalarObject*>obj).obval             # <<<<<<<<<<<<<<
  * 
  * 
  */
   __pyx_r = ((PyTimedeltaScalarObject *)__pyx_v_obj)->obval;
   goto __pyx_L0;
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":1006
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":1006
  * 
  * 
  * cdef inline npy_timedelta get_timedelta64_value(object obj) nogil:             # <<<<<<<<<<<<<<
  *     """
  *     returns the int64 value underlying scalar numpy timedelta64 object
  */
 
   /* function exit code */
   __pyx_L0:;
   return __pyx_r;
 }
 
-/* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":1013
+/* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":1013
  * 
  * 
  * cdef inline NPY_DATETIMEUNIT get_datetime64_unit(object obj) nogil:             # <<<<<<<<<<<<<<
  *     """
  *     returns the unit part of the dtype for a numpy datetime64 object.
  */
 
 static CYTHON_INLINE NPY_DATETIMEUNIT __pyx_f_5numpy_get_datetime64_unit(PyObject *__pyx_v_obj) {
   NPY_DATETIMEUNIT __pyx_r;
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":1017
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":1017
  *     returns the unit part of the dtype for a numpy datetime64 object.
  *     """
  *     return <NPY_DATETIMEUNIT>(<PyDatetimeScalarObject*>obj).obmeta.base             # <<<<<<<<<<<<<<
  */
   __pyx_r = ((NPY_DATETIMEUNIT)((PyDatetimeScalarObject *)__pyx_v_obj)->obmeta.base);
   goto __pyx_L0;
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":1013
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":1013
  * 
  * 
  * cdef inline NPY_DATETIMEUNIT get_datetime64_unit(object obj) nogil:             # <<<<<<<<<<<<<<
  *     """
  *     returns the unit part of the dtype for a numpy datetime64 object.
  */
 
@@ -17663,15 +17130,15 @@
   #endif
   __pyx_array_getbuffer, /*bf_getbuffer*/
   0, /*bf_releasebuffer*/
 };
 
 static PyTypeObject __pyx_type___pyx_array = {
   PyVarObject_HEAD_INIT(0, 0)
-  "ms_entropy.tools.fast_entropy.array", /*tp_name*/
+  "ms_entropy.entropy_search.fast_flash_entropy_search_cpython.array", /*tp_name*/
   sizeof(struct __pyx_array_obj), /*tp_basicsize*/
   0, /*tp_itemsize*/
   __pyx_tp_dealloc_array, /*tp_dealloc*/
   #if PY_VERSION_HEX < 0x030800b4
   0, /*tp_print*/
   #endif
   #if PY_VERSION_HEX >= 0x030800b4
@@ -17728,15 +17195,15 @@
   #endif
   #if PY_VERSION_HEX >= 0x030800b1 && (!CYTHON_COMPILING_IN_PYPY || PYPY_VERSION_NUM >= 0x07030800)
   0, /*tp_vectorcall*/
   #endif
   #if PY_VERSION_HEX >= 0x030800b4 && PY_VERSION_HEX < 0x03090000
   0, /*tp_print*/
   #endif
-  #if CYTHON_COMPILING_IN_PYPY && PY_VERSION_HEX >= 0x03090000
+  #if CYTHON_COMPILING_IN_PYPY && PY_VERSION_HEX >= 0x03090000 && PY_VERSION_HEX < 0x030a0000
   0, /*tp_pypy_flags*/
   #endif
 };
 
 static PyObject *__pyx_tp_new_Enum(PyTypeObject *t, CYTHON_UNUSED PyObject *a, CYTHON_UNUSED PyObject *k) {
   struct __pyx_MemviewEnum_obj *p;
   PyObject *o;
@@ -17785,15 +17252,15 @@
   {"__reduce_cython__", (PyCFunction)__pyx_pw___pyx_MemviewEnum_1__reduce_cython__, METH_NOARGS, 0},
   {"__setstate_cython__", (PyCFunction)__pyx_pw___pyx_MemviewEnum_3__setstate_cython__, METH_O, 0},
   {0, 0, 0, 0}
 };
 
 static PyTypeObject __pyx_type___pyx_MemviewEnum = {
   PyVarObject_HEAD_INIT(0, 0)
-  "ms_entropy.tools.fast_entropy.Enum", /*tp_name*/
+  "ms_entropy.entropy_search.fast_flash_entropy_search_cpython.Enum", /*tp_name*/
   sizeof(struct __pyx_MemviewEnum_obj), /*tp_basicsize*/
   0, /*tp_itemsize*/
   __pyx_tp_dealloc_Enum, /*tp_dealloc*/
   #if PY_VERSION_HEX < 0x030800b4
   0, /*tp_print*/
   #endif
   #if PY_VERSION_HEX >= 0x030800b4
@@ -17850,15 +17317,15 @@
   #endif
   #if PY_VERSION_HEX >= 0x030800b1 && (!CYTHON_COMPILING_IN_PYPY || PYPY_VERSION_NUM >= 0x07030800)
   0, /*tp_vectorcall*/
   #endif
   #if PY_VERSION_HEX >= 0x030800b4 && PY_VERSION_HEX < 0x03090000
   0, /*tp_print*/
   #endif
-  #if CYTHON_COMPILING_IN_PYPY && PY_VERSION_HEX >= 0x03090000
+  #if CYTHON_COMPILING_IN_PYPY && PY_VERSION_HEX >= 0x03090000 && PY_VERSION_HEX < 0x030a0000
   0, /*tp_pypy_flags*/
   #endif
 };
 static struct __pyx_vtabstruct_memoryview __pyx_vtable_memoryview;
 
 static PyObject *__pyx_tp_new_memoryview(PyTypeObject *t, PyObject *a, PyObject *k) {
   struct __pyx_memoryview_obj *p;
@@ -18049,15 +17516,15 @@
   #endif
   __pyx_memoryview_getbuffer, /*bf_getbuffer*/
   0, /*bf_releasebuffer*/
 };
 
 static PyTypeObject __pyx_type___pyx_memoryview = {
   PyVarObject_HEAD_INIT(0, 0)
-  "ms_entropy.tools.fast_entropy.memoryview", /*tp_name*/
+  "ms_entropy.entropy_search.fast_flash_entropy_search_cpython.memoryview", /*tp_name*/
   sizeof(struct __pyx_memoryview_obj), /*tp_basicsize*/
   0, /*tp_itemsize*/
   __pyx_tp_dealloc_memoryview, /*tp_dealloc*/
   #if PY_VERSION_HEX < 0x030800b4
   0, /*tp_print*/
   #endif
   #if PY_VERSION_HEX >= 0x030800b4
@@ -18114,15 +17581,15 @@
   #endif
   #if PY_VERSION_HEX >= 0x030800b1 && (!CYTHON_COMPILING_IN_PYPY || PYPY_VERSION_NUM >= 0x07030800)
   0, /*tp_vectorcall*/
   #endif
   #if PY_VERSION_HEX >= 0x030800b4 && PY_VERSION_HEX < 0x03090000
   0, /*tp_print*/
   #endif
-  #if CYTHON_COMPILING_IN_PYPY && PY_VERSION_HEX >= 0x03090000
+  #if CYTHON_COMPILING_IN_PYPY && PY_VERSION_HEX >= 0x03090000 && PY_VERSION_HEX < 0x030a0000
   0, /*tp_pypy_flags*/
   #endif
 };
 static struct __pyx_vtabstruct__memoryviewslice __pyx_vtable__memoryviewslice;
 
 static PyObject *__pyx_tp_new__memoryviewslice(PyTypeObject *t, PyObject *a, PyObject *k) {
   struct __pyx_memoryviewslice_obj *p;
@@ -18190,15 +17657,15 @@
 static struct PyGetSetDef __pyx_getsets__memoryviewslice[] = {
   {(char *)"base", __pyx_getprop___pyx_memoryviewslice_base, 0, (char *)0, 0},
   {0, 0, 0, 0, 0}
 };
 
 static PyTypeObject __pyx_type___pyx_memoryviewslice = {
   PyVarObject_HEAD_INIT(0, 0)
-  "ms_entropy.tools.fast_entropy._memoryviewslice", /*tp_name*/
+  "ms_entropy.entropy_search.fast_flash_entropy_search_cpython._memoryviewslice", /*tp_name*/
   sizeof(struct __pyx_memoryviewslice_obj), /*tp_basicsize*/
   0, /*tp_itemsize*/
   __pyx_tp_dealloc__memoryviewslice, /*tp_dealloc*/
   #if PY_VERSION_HEX < 0x030800b4
   0, /*tp_print*/
   #endif
   #if PY_VERSION_HEX >= 0x030800b4
@@ -18263,40 +17730,38 @@
   #endif
   #if PY_VERSION_HEX >= 0x030800b1 && (!CYTHON_COMPILING_IN_PYPY || PYPY_VERSION_NUM >= 0x07030800)
   0, /*tp_vectorcall*/
   #endif
   #if PY_VERSION_HEX >= 0x030800b4 && PY_VERSION_HEX < 0x03090000
   0, /*tp_print*/
   #endif
-  #if CYTHON_COMPILING_IN_PYPY && PY_VERSION_HEX >= 0x03090000
+  #if CYTHON_COMPILING_IN_PYPY && PY_VERSION_HEX >= 0x03090000 && PY_VERSION_HEX < 0x030a0000
   0, /*tp_pypy_flags*/
   #endif
 };
 
 static PyMethodDef __pyx_methods[] = {
-  {"entropy_similarity_search_fast", (PyCFunction)(void*)(PyCFunctionWithKeywords)__pyx_pw_10ms_entropy_5tools_12fast_entropy_1entropy_similarity_search_fast, METH_VARARGS|METH_KEYWORDS, __pyx_doc_10ms_entropy_5tools_12fast_entropy_entropy_similarity_search_fast},
-  {"apply_weight_to_intensity", (PyCFunction)__pyx_pw_10ms_entropy_5tools_12fast_entropy_3apply_weight_to_intensity, METH_O, __pyx_doc_10ms_entropy_5tools_12fast_entropy_2apply_weight_to_intensity},
-  {"spectral_entropy", (PyCFunction)__pyx_pw_10ms_entropy_5tools_12fast_entropy_5spectral_entropy, METH_O, __pyx_doc_10ms_entropy_5tools_12fast_entropy_4spectral_entropy},
+  {"cy_entropy_similarity_identity_search", (PyCFunction)(void*)(PyCFunctionWithKeywords)__pyx_pw_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_1cy_entropy_similarity_identity_search, METH_VARARGS|METH_KEYWORDS, __pyx_doc_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_cy_entropy_similarity_identity_search},
   {0, 0, 0, 0}
 };
 
 #if PY_MAJOR_VERSION >= 3
 #if CYTHON_PEP489_MULTI_PHASE_INIT
 static PyObject* __pyx_pymod_create(PyObject *spec, PyModuleDef *def); /*proto*/
-static int __pyx_pymod_exec_fast_entropy(PyObject* module); /*proto*/
+static int __pyx_pymod_exec_fast_flash_entropy_search_cpython(PyObject* module); /*proto*/
 static PyModuleDef_Slot __pyx_moduledef_slots[] = {
   {Py_mod_create, (void*)__pyx_pymod_create},
-  {Py_mod_exec, (void*)__pyx_pymod_exec_fast_entropy},
+  {Py_mod_exec, (void*)__pyx_pymod_exec_fast_flash_entropy_search_cpython},
   {0, NULL}
 };
 #endif
 
 static struct PyModuleDef __pyx_moduledef = {
     PyModuleDef_HEAD_INIT,
-    "fast_entropy",
+    "fast_flash_entropy_search_cpython",
     0, /* m_doc */
   #if CYTHON_PEP489_MULTI_PHASE_INIT
     0, /* m_size */
   #else
     -1, /* m_size */
   #endif
     __pyx_methods /* m_methods */,
@@ -18349,18 +17814,18 @@
   {&__pyx_n_s_base, __pyx_k_base, sizeof(__pyx_k_base), 0, 0, 1, 1},
   {&__pyx_n_s_c, __pyx_k_c, sizeof(__pyx_k_c), 0, 0, 1, 1},
   {&__pyx_n_u_c, __pyx_k_c, sizeof(__pyx_k_c), 0, 1, 0, 1},
   {&__pyx_n_s_class, __pyx_k_class, sizeof(__pyx_k_class), 0, 0, 1, 1},
   {&__pyx_n_s_cline_in_traceback, __pyx_k_cline_in_traceback, sizeof(__pyx_k_cline_in_traceback), 0, 0, 1, 1},
   {&__pyx_kp_s_contiguous_and_direct, __pyx_k_contiguous_and_direct, sizeof(__pyx_k_contiguous_and_direct), 0, 0, 1, 0},
   {&__pyx_kp_s_contiguous_and_indirect, __pyx_k_contiguous_and_indirect, sizeof(__pyx_k_contiguous_and_indirect), 0, 0, 1, 0},
-  {&__pyx_n_s_copy, __pyx_k_copy, sizeof(__pyx_k_copy), 0, 0, 1, 1},
   {&__pyx_n_s_dict, __pyx_k_dict, sizeof(__pyx_k_dict), 0, 0, 1, 1},
   {&__pyx_n_s_dtype_is_object, __pyx_k_dtype_is_object, sizeof(__pyx_k_dtype_is_object), 0, 0, 1, 1},
   {&__pyx_n_s_encode, __pyx_k_encode, sizeof(__pyx_k_encode), 0, 0, 1, 1},
+  {&__pyx_n_s_entropy_similarity, __pyx_k_entropy_similarity, sizeof(__pyx_k_entropy_similarity), 0, 0, 1, 1},
   {&__pyx_n_s_enumerate, __pyx_k_enumerate, sizeof(__pyx_k_enumerate), 0, 0, 1, 1},
   {&__pyx_n_s_error, __pyx_k_error, sizeof(__pyx_k_error), 0, 0, 1, 1},
   {&__pyx_n_s_flags, __pyx_k_flags, sizeof(__pyx_k_flags), 0, 0, 1, 1},
   {&__pyx_n_s_format, __pyx_k_format, sizeof(__pyx_k_format), 0, 0, 1, 1},
   {&__pyx_n_s_fortran, __pyx_k_fortran, sizeof(__pyx_k_fortran), 0, 0, 1, 1},
   {&__pyx_n_u_fortran, __pyx_k_fortran, sizeof(__pyx_k_fortran), 0, 1, 0, 1},
   {&__pyx_n_s_getstate, __pyx_k_getstate, sizeof(__pyx_k_getstate), 0, 0, 1, 1},
@@ -18370,15 +17835,14 @@
   {&__pyx_n_s_intensity, __pyx_k_intensity, sizeof(__pyx_k_intensity), 0, 0, 1, 1},
   {&__pyx_n_s_itemsize, __pyx_k_itemsize, sizeof(__pyx_k_itemsize), 0, 0, 1, 1},
   {&__pyx_kp_s_itemsize_0_for_cython_array, __pyx_k_itemsize_0_for_cython_array, sizeof(__pyx_k_itemsize_0_for_cython_array), 0, 0, 1, 0},
   {&__pyx_n_s_library_peaks_intensity, __pyx_k_library_peaks_intensity, sizeof(__pyx_k_library_peaks_intensity), 0, 0, 1, 1},
   {&__pyx_n_s_library_spec_idx_array, __pyx_k_library_spec_idx_array, sizeof(__pyx_k_library_spec_idx_array), 0, 0, 1, 1},
   {&__pyx_n_s_main, __pyx_k_main, sizeof(__pyx_k_main), 0, 0, 1, 1},
   {&__pyx_n_s_memview, __pyx_k_memview, sizeof(__pyx_k_memview), 0, 0, 1, 1},
-  {&__pyx_n_s_mixed_spectra_entropy, __pyx_k_mixed_spectra_entropy, sizeof(__pyx_k_mixed_spectra_entropy), 0, 0, 1, 1},
   {&__pyx_n_s_mode, __pyx_k_mode, sizeof(__pyx_k_mode), 0, 0, 1, 1},
   {&__pyx_n_s_name, __pyx_k_name, sizeof(__pyx_k_name), 0, 0, 1, 1},
   {&__pyx_n_s_name_2, __pyx_k_name_2, sizeof(__pyx_k_name_2), 0, 0, 1, 1},
   {&__pyx_n_s_ndim, __pyx_k_ndim, sizeof(__pyx_k_ndim), 0, 0, 1, 1},
   {&__pyx_n_s_new, __pyx_k_new, sizeof(__pyx_k_new), 0, 0, 1, 1},
   {&__pyx_kp_s_no_default___reduce___due_to_non, __pyx_k_no_default___reduce___due_to_non, sizeof(__pyx_k_no_default___reduce___due_to_non), 0, 0, 1, 0},
   {&__pyx_n_s_np, __pyx_k_np, sizeof(__pyx_k_np), 0, 0, 1, 1},
@@ -18398,18 +17862,16 @@
   {&__pyx_n_s_pyx_type, __pyx_k_pyx_type, sizeof(__pyx_k_pyx_type), 0, 0, 1, 1},
   {&__pyx_n_s_pyx_unpickle_Enum, __pyx_k_pyx_unpickle_Enum, sizeof(__pyx_k_pyx_unpickle_Enum), 0, 0, 1, 1},
   {&__pyx_n_s_pyx_vtable, __pyx_k_pyx_vtable, sizeof(__pyx_k_pyx_vtable), 0, 0, 1, 1},
   {&__pyx_n_s_range, __pyx_k_range, sizeof(__pyx_k_range), 0, 0, 1, 1},
   {&__pyx_n_s_reduce, __pyx_k_reduce, sizeof(__pyx_k_reduce), 0, 0, 1, 1},
   {&__pyx_n_s_reduce_cython, __pyx_k_reduce_cython, sizeof(__pyx_k_reduce_cython), 0, 0, 1, 1},
   {&__pyx_n_s_reduce_ex, __pyx_k_reduce_ex, sizeof(__pyx_k_reduce_ex), 0, 0, 1, 1},
-  {&__pyx_n_s_search_array, __pyx_k_search_array, sizeof(__pyx_k_search_array), 0, 0, 1, 1},
   {&__pyx_n_s_search_spectra_idx_max, __pyx_k_search_spectra_idx_max, sizeof(__pyx_k_search_spectra_idx_max), 0, 0, 1, 1},
   {&__pyx_n_s_search_spectra_idx_min, __pyx_k_search_spectra_idx_min, sizeof(__pyx_k_search_spectra_idx_min), 0, 0, 1, 1},
-  {&__pyx_n_s_search_type, __pyx_k_search_type, sizeof(__pyx_k_search_type), 0, 0, 1, 1},
   {&__pyx_n_s_setstate, __pyx_k_setstate, sizeof(__pyx_k_setstate), 0, 0, 1, 1},
   {&__pyx_n_s_setstate_cython, __pyx_k_setstate_cython, sizeof(__pyx_k_setstate_cython), 0, 0, 1, 1},
   {&__pyx_n_s_shape, __pyx_k_shape, sizeof(__pyx_k_shape), 0, 0, 1, 1},
   {&__pyx_n_s_size, __pyx_k_size, sizeof(__pyx_k_size), 0, 0, 1, 1},
   {&__pyx_n_s_start, __pyx_k_start, sizeof(__pyx_k_start), 0, 0, 1, 1},
   {&__pyx_n_s_step, __pyx_k_step, sizeof(__pyx_k_step), 0, 0, 1, 1},
   {&__pyx_n_s_stop, __pyx_k_stop, sizeof(__pyx_k_stop), 0, 0, 1, 1},
@@ -18422,15 +17884,15 @@
   {&__pyx_kp_s_unable_to_allocate_array_data, __pyx_k_unable_to_allocate_array_data, sizeof(__pyx_k_unable_to_allocate_array_data), 0, 0, 1, 0},
   {&__pyx_kp_s_unable_to_allocate_shape_and_str, __pyx_k_unable_to_allocate_shape_and_str, sizeof(__pyx_k_unable_to_allocate_shape_and_str), 0, 0, 1, 0},
   {&__pyx_n_s_unpack, __pyx_k_unpack, sizeof(__pyx_k_unpack), 0, 0, 1, 1},
   {&__pyx_n_s_update, __pyx_k_update, sizeof(__pyx_k_update), 0, 0, 1, 1},
   {0, 0, 0, 0, 0, 0, 0}
 };
 static CYTHON_SMALL_CODE int __Pyx_InitCachedBuiltins(void) {
-  __pyx_builtin_range = __Pyx_GetBuiltinName(__pyx_n_s_range); if (!__pyx_builtin_range) __PYX_ERR(0, 27, __pyx_L1_error)
+  __pyx_builtin_range = __Pyx_GetBuiltinName(__pyx_n_s_range); if (!__pyx_builtin_range) __PYX_ERR(0, 24, __pyx_L1_error)
   __pyx_builtin_ImportError = __Pyx_GetBuiltinName(__pyx_n_s_ImportError); if (!__pyx_builtin_ImportError) __PYX_ERR(1, 944, __pyx_L1_error)
   __pyx_builtin_ValueError = __Pyx_GetBuiltinName(__pyx_n_s_ValueError); if (!__pyx_builtin_ValueError) __PYX_ERR(2, 134, __pyx_L1_error)
   __pyx_builtin_MemoryError = __Pyx_GetBuiltinName(__pyx_n_s_MemoryError); if (!__pyx_builtin_MemoryError) __PYX_ERR(2, 149, __pyx_L1_error)
   __pyx_builtin_enumerate = __Pyx_GetBuiltinName(__pyx_n_s_enumerate); if (!__pyx_builtin_enumerate) __PYX_ERR(2, 152, __pyx_L1_error)
   __pyx_builtin_TypeError = __Pyx_GetBuiltinName(__pyx_n_s_TypeError); if (!__pyx_builtin_TypeError) __PYX_ERR(2, 2, __pyx_L1_error)
   __pyx_builtin_Ellipsis = __Pyx_GetBuiltinName(__pyx_n_s_Ellipsis); if (!__pyx_builtin_Ellipsis) __PYX_ERR(2, 406, __pyx_L1_error)
   __pyx_builtin_id = __Pyx_GetBuiltinName(__pyx_n_s_id); if (!__pyx_builtin_id) __PYX_ERR(2, 615, __pyx_L1_error)
@@ -18440,26 +17902,26 @@
   return -1;
 }
 
 static CYTHON_SMALL_CODE int __Pyx_InitCachedConstants(void) {
   __Pyx_RefNannyDeclarations
   __Pyx_RefNannySetupContext("__Pyx_InitCachedConstants", 0);
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":944
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":944
  *         __pyx_import_array()
  *     except Exception:
  *         raise ImportError("numpy.core.multiarray failed to import")             # <<<<<<<<<<<<<<
  * 
  * cdef inline int import_umath() except -1:
  */
   __pyx_tuple_ = PyTuple_Pack(1, __pyx_kp_u_numpy_core_multiarray_failed_to); if (unlikely(!__pyx_tuple_)) __PYX_ERR(1, 944, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_tuple_);
   __Pyx_GIVEREF(__pyx_tuple_);
 
-  /* "../../../home/yli/Software/anaconda3/envs/py39/lib/python3.9/site-packages/numpy/__init__.pxd":950
+  /* "../../tmp/build-env-rbi0c3ul/lib/python3.8/site-packages/numpy/__init__.pxd":950
  *         _import_umath()
  *     except Exception:
  *         raise ImportError("numpy.core.umath failed to import")             # <<<<<<<<<<<<<<
  * 
  * cdef inline int import_ufunc() except -1:
  */
   __pyx_tuple__2 = PyTuple_Pack(1, __pyx_kp_u_numpy_core_umath_failed_to_impor); if (unlikely(!__pyx_tuple__2)) __PYX_ERR(1, 950, __pyx_L1_error)
@@ -18853,55 +18315,39 @@
   int __pyx_lineno = 0;
   const char *__pyx_filename = NULL;
   int __pyx_clineno = 0;
   __Pyx_RefNannySetupContext("__Pyx_modinit_type_import_code", 0);
   /*--- Type import code ---*/
   __pyx_t_1 = PyImport_ImportModule(__Pyx_BUILTIN_MODULE_NAME); if (unlikely(!__pyx_t_1)) __PYX_ERR(3, 9, __pyx_L1_error)
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
-   if (!__pyx_ptype_7cpython_4type_type) __PYX_ERR(3, 9, __pyx_L1_error)
+  __Pyx_ImportType_CheckSize_Warn_0_29_35); if (!__pyx_ptype_7cpython_4type_type) __PYX_ERR(3, 9, __pyx_L1_error)
   __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
   __pyx_t_1 = PyImport_ImportModule("numpy"); if (unlikely(!__pyx_t_1)) __PYX_ERR(1, 199, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_1);
-  __pyx_ptype_5numpy_dtype = __Pyx_ImportType(__pyx_t_1, "numpy", "dtype", sizeof(PyArray_Descr), __Pyx_ImportType_CheckSize_Ignore);
-   if (!__pyx_ptype_5numpy_dtype) __PYX_ERR(1, 199, __pyx_L1_error)
-  __pyx_ptype_5numpy_flatiter = __Pyx_ImportType(__pyx_t_1, "numpy", "flatiter", sizeof(PyArrayIterObject), __Pyx_ImportType_CheckSize_Ignore);
-   if (!__pyx_ptype_5numpy_flatiter) __PYX_ERR(1, 222, __pyx_L1_error)
-  __pyx_ptype_5numpy_broadcast = __Pyx_ImportType(__pyx_t_1, "numpy", "broadcast", sizeof(PyArrayMultiIterObject), __Pyx_ImportType_CheckSize_Ignore);
-   if (!__pyx_ptype_5numpy_broadcast) __PYX_ERR(1, 226, __pyx_L1_error)
-  __pyx_ptype_5numpy_ndarray = __Pyx_ImportType(__pyx_t_1, "numpy", "ndarray", sizeof(PyArrayObject), __Pyx_ImportType_CheckSize_Ignore);
-   if (!__pyx_ptype_5numpy_ndarray) __PYX_ERR(1, 238, __pyx_L1_error)
-  __pyx_ptype_5numpy_generic = __Pyx_ImportType(__pyx_t_1, "numpy", "generic", sizeof(PyObject), __Pyx_ImportType_CheckSize_Warn);
-   if (!__pyx_ptype_5numpy_generic) __PYX_ERR(1, 770, __pyx_L1_error)
-  __pyx_ptype_5numpy_number = __Pyx_ImportType(__pyx_t_1, "numpy", "number", sizeof(PyObject), __Pyx_ImportType_CheckSize_Warn);
-   if (!__pyx_ptype_5numpy_number) __PYX_ERR(1, 772, __pyx_L1_error)
-  __pyx_ptype_5numpy_integer = __Pyx_ImportType(__pyx_t_1, "numpy", "integer", sizeof(PyObject), __Pyx_ImportType_CheckSize_Warn);
-   if (!__pyx_ptype_5numpy_integer) __PYX_ERR(1, 774, __pyx_L1_error)
-  __pyx_ptype_5numpy_signedinteger = __Pyx_ImportType(__pyx_t_1, "numpy", "signedinteger", sizeof(PyObject), __Pyx_ImportType_CheckSize_Warn);
-   if (!__pyx_ptype_5numpy_signedinteger) __PYX_ERR(1, 776, __pyx_L1_error)
-  __pyx_ptype_5numpy_unsignedinteger = __Pyx_ImportType(__pyx_t_1, "numpy", "unsignedinteger", sizeof(PyObject), __Pyx_ImportType_CheckSize_Warn);
-   if (!__pyx_ptype_5numpy_unsignedinteger) __PYX_ERR(1, 778, __pyx_L1_error)
-  __pyx_ptype_5numpy_inexact = __Pyx_ImportType(__pyx_t_1, "numpy", "inexact", sizeof(PyObject), __Pyx_ImportType_CheckSize_Warn);
-   if (!__pyx_ptype_5numpy_inexact) __PYX_ERR(1, 780, __pyx_L1_error)
-  __pyx_ptype_5numpy_floating = __Pyx_ImportType(__pyx_t_1, "numpy", "floating", sizeof(PyObject), __Pyx_ImportType_CheckSize_Warn);
-   if (!__pyx_ptype_5numpy_floating) __PYX_ERR(1, 782, __pyx_L1_error)
-  __pyx_ptype_5numpy_complexfloating = __Pyx_ImportType(__pyx_t_1, "numpy", "complexfloating", sizeof(PyObject), __Pyx_ImportType_CheckSize_Warn);
-   if (!__pyx_ptype_5numpy_complexfloating) __PYX_ERR(1, 784, __pyx_L1_error)
-  __pyx_ptype_5numpy_flexible = __Pyx_ImportType(__pyx_t_1, "numpy", "flexible", sizeof(PyObject), __Pyx_ImportType_CheckSize_Warn);
-   if (!__pyx_ptype_5numpy_flexible) __PYX_ERR(1, 786, __pyx_L1_error)
-  __pyx_ptype_5numpy_character = __Pyx_ImportType(__pyx_t_1, "numpy", "character", sizeof(PyObject), __Pyx_ImportType_CheckSize_Warn);
-   if (!__pyx_ptype_5numpy_character) __PYX_ERR(1, 788, __pyx_L1_error)
-  __pyx_ptype_5numpy_ufunc = __Pyx_ImportType(__pyx_t_1, "numpy", "ufunc", sizeof(PyUFuncObject), __Pyx_ImportType_CheckSize_Ignore);
-   if (!__pyx_ptype_5numpy_ufunc) __PYX_ERR(1, 826, __pyx_L1_error)
+  __pyx_ptype_5numpy_dtype = __Pyx_ImportType_0_29_35(__pyx_t_1, "numpy", "dtype", sizeof(PyArray_Descr), __PYX_GET_STRUCT_ALIGNMENT_0_29_35(PyArray_Descr),__Pyx_ImportType_CheckSize_Ignore_0_29_35); if (!__pyx_ptype_5numpy_dtype) __PYX_ERR(1, 199, __pyx_L1_error)
+  __pyx_ptype_5numpy_flatiter = __Pyx_ImportType_0_29_35(__pyx_t_1, "numpy", "flatiter", sizeof(PyArrayIterObject), __PYX_GET_STRUCT_ALIGNMENT_0_29_35(PyArrayIterObject),__Pyx_ImportType_CheckSize_Ignore_0_29_35); if (!__pyx_ptype_5numpy_flatiter) __PYX_ERR(1, 222, __pyx_L1_error)
+  __pyx_ptype_5numpy_broadcast = __Pyx_ImportType_0_29_35(__pyx_t_1, "numpy", "broadcast", sizeof(PyArrayMultiIterObject), __PYX_GET_STRUCT_ALIGNMENT_0_29_35(PyArrayMultiIterObject),__Pyx_ImportType_CheckSize_Ignore_0_29_35); if (!__pyx_ptype_5numpy_broadcast) __PYX_ERR(1, 226, __pyx_L1_error)
+  __pyx_ptype_5numpy_ndarray = __Pyx_ImportType_0_29_35(__pyx_t_1, "numpy", "ndarray", sizeof(PyArrayObject), __PYX_GET_STRUCT_ALIGNMENT_0_29_35(PyArrayObject),__Pyx_ImportType_CheckSize_Ignore_0_29_35); if (!__pyx_ptype_5numpy_ndarray) __PYX_ERR(1, 238, __pyx_L1_error)
+  __pyx_ptype_5numpy_generic = __Pyx_ImportType_0_29_35(__pyx_t_1, "numpy", "generic", sizeof(PyObject), __PYX_GET_STRUCT_ALIGNMENT_0_29_35(PyObject),__Pyx_ImportType_CheckSize_Warn_0_29_35); if (!__pyx_ptype_5numpy_generic) __PYX_ERR(1, 770, __pyx_L1_error)
+  __pyx_ptype_5numpy_number = __Pyx_ImportType_0_29_35(__pyx_t_1, "numpy", "number", sizeof(PyObject), __PYX_GET_STRUCT_ALIGNMENT_0_29_35(PyObject),__Pyx_ImportType_CheckSize_Warn_0_29_35); if (!__pyx_ptype_5numpy_number) __PYX_ERR(1, 772, __pyx_L1_error)
+  __pyx_ptype_5numpy_integer = __Pyx_ImportType_0_29_35(__pyx_t_1, "numpy", "integer", sizeof(PyObject), __PYX_GET_STRUCT_ALIGNMENT_0_29_35(PyObject),__Pyx_ImportType_CheckSize_Warn_0_29_35); if (!__pyx_ptype_5numpy_integer) __PYX_ERR(1, 774, __pyx_L1_error)
+  __pyx_ptype_5numpy_signedinteger = __Pyx_ImportType_0_29_35(__pyx_t_1, "numpy", "signedinteger", sizeof(PyObject), __PYX_GET_STRUCT_ALIGNMENT_0_29_35(PyObject),__Pyx_ImportType_CheckSize_Warn_0_29_35); if (!__pyx_ptype_5numpy_signedinteger) __PYX_ERR(1, 776, __pyx_L1_error)
+  __pyx_ptype_5numpy_unsignedinteger = __Pyx_ImportType_0_29_35(__pyx_t_1, "numpy", "unsignedinteger", sizeof(PyObject), __PYX_GET_STRUCT_ALIGNMENT_0_29_35(PyObject),__Pyx_ImportType_CheckSize_Warn_0_29_35); if (!__pyx_ptype_5numpy_unsignedinteger) __PYX_ERR(1, 778, __pyx_L1_error)
+  __pyx_ptype_5numpy_inexact = __Pyx_ImportType_0_29_35(__pyx_t_1, "numpy", "inexact", sizeof(PyObject), __PYX_GET_STRUCT_ALIGNMENT_0_29_35(PyObject),__Pyx_ImportType_CheckSize_Warn_0_29_35); if (!__pyx_ptype_5numpy_inexact) __PYX_ERR(1, 780, __pyx_L1_error)
+  __pyx_ptype_5numpy_floating = __Pyx_ImportType_0_29_35(__pyx_t_1, "numpy", "floating", sizeof(PyObject), __PYX_GET_STRUCT_ALIGNMENT_0_29_35(PyObject),__Pyx_ImportType_CheckSize_Warn_0_29_35); if (!__pyx_ptype_5numpy_floating) __PYX_ERR(1, 782, __pyx_L1_error)
+  __pyx_ptype_5numpy_complexfloating = __Pyx_ImportType_0_29_35(__pyx_t_1, "numpy", "complexfloating", sizeof(PyObject), __PYX_GET_STRUCT_ALIGNMENT_0_29_35(PyObject),__Pyx_ImportType_CheckSize_Warn_0_29_35); if (!__pyx_ptype_5numpy_complexfloating) __PYX_ERR(1, 784, __pyx_L1_error)
+  __pyx_ptype_5numpy_flexible = __Pyx_ImportType_0_29_35(__pyx_t_1, "numpy", "flexible", sizeof(PyObject), __PYX_GET_STRUCT_ALIGNMENT_0_29_35(PyObject),__Pyx_ImportType_CheckSize_Warn_0_29_35); if (!__pyx_ptype_5numpy_flexible) __PYX_ERR(1, 786, __pyx_L1_error)
+  __pyx_ptype_5numpy_character = __Pyx_ImportType_0_29_35(__pyx_t_1, "numpy", "character", sizeof(PyObject), __PYX_GET_STRUCT_ALIGNMENT_0_29_35(PyObject),__Pyx_ImportType_CheckSize_Warn_0_29_35); if (!__pyx_ptype_5numpy_character) __PYX_ERR(1, 788, __pyx_L1_error)
+  __pyx_ptype_5numpy_ufunc = __Pyx_ImportType_0_29_35(__pyx_t_1, "numpy", "ufunc", sizeof(PyUFuncObject), __PYX_GET_STRUCT_ALIGNMENT_0_29_35(PyUFuncObject),__Pyx_ImportType_CheckSize_Ignore_0_29_35); if (!__pyx_ptype_5numpy_ufunc) __PYX_ERR(1, 826, __pyx_L1_error)
   __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
   __Pyx_RefNannyFinishContext();
   return 0;
   __pyx_L1_error:;
   __Pyx_XDECREF(__pyx_t_1);
   __Pyx_RefNannyFinishContext();
   return -1;
@@ -18938,19 +18384,19 @@
 #else
 #define __Pyx_PyMODINIT_FUNC PyObject *
 #endif
 #endif
 
 
 #if PY_MAJOR_VERSION < 3
-__Pyx_PyMODINIT_FUNC initfast_entropy(void) CYTHON_SMALL_CODE; /*proto*/
-__Pyx_PyMODINIT_FUNC initfast_entropy(void)
+__Pyx_PyMODINIT_FUNC initfast_flash_entropy_search_cpython(void) CYTHON_SMALL_CODE; /*proto*/
+__Pyx_PyMODINIT_FUNC initfast_flash_entropy_search_cpython(void)
 #else
-__Pyx_PyMODINIT_FUNC PyInit_fast_entropy(void) CYTHON_SMALL_CODE; /*proto*/
-__Pyx_PyMODINIT_FUNC PyInit_fast_entropy(void)
+__Pyx_PyMODINIT_FUNC PyInit_fast_flash_entropy_search_cpython(void) CYTHON_SMALL_CODE; /*proto*/
+__Pyx_PyMODINIT_FUNC PyInit_fast_flash_entropy_search_cpython(void)
 #if CYTHON_PEP489_MULTI_PHASE_INIT
 {
   return PyModuleDef_Init(&__pyx_moduledef);
 }
 static CYTHON_SMALL_CODE int __Pyx_check_single_interpreter(void) {
     #if PY_VERSION_HEX >= 0x030700A1
     static PY_INT64_T main_interpreter_id = -1;
@@ -19009,43 +18455,43 @@
     return module;
 bad:
     Py_XDECREF(module);
     return NULL;
 }
 
 
-static CYTHON_SMALL_CODE int __pyx_pymod_exec_fast_entropy(PyObject *__pyx_pyinit_module)
+static CYTHON_SMALL_CODE int __pyx_pymod_exec_fast_flash_entropy_search_cpython(PyObject *__pyx_pyinit_module)
 #endif
 #endif
 {
   PyObject *__pyx_t_1 = NULL;
   static PyThread_type_lock __pyx_t_2[8];
   int __pyx_lineno = 0;
   const char *__pyx_filename = NULL;
   int __pyx_clineno = 0;
   __Pyx_RefNannyDeclarations
   #if CYTHON_PEP489_MULTI_PHASE_INIT
   if (__pyx_m) {
     if (__pyx_m == __pyx_pyinit_module) return 0;
-    PyErr_SetString(PyExc_RuntimeError, "Module 'fast_entropy' has already been imported. Re-initialisation is not supported.");
+    PyErr_SetString(PyExc_RuntimeError, "Module 'fast_flash_entropy_search_cpython' has already been imported. Re-initialisation is not supported.");
     return -1;
   }
   #elif PY_MAJOR_VERSION >= 3
   if (__pyx_m) return __Pyx_NewRef(__pyx_m);
   #endif
   #if CYTHON_REFNANNY
 __Pyx_RefNanny = __Pyx_RefNannyImportAPI("refnanny");
 if (!__Pyx_RefNanny) {
   PyErr_Clear();
   __Pyx_RefNanny = __Pyx_RefNannyImportAPI("Cython.Runtime.refnanny");
   if (!__Pyx_RefNanny)
       Py_FatalError("failed to import 'refnanny' module");
 }
 #endif
-  __Pyx_RefNannySetupContext("__Pyx_PyMODINIT_FUNC PyInit_fast_entropy(void)", 0);
+  __Pyx_RefNannySetupContext("__Pyx_PyMODINIT_FUNC PyInit_fast_flash_entropy_search_cpython(void)", 0);
   if (__Pyx_check_binary_version() < 0) __PYX_ERR(0, 1, __pyx_L1_error)
   #ifdef __Pxy_PyFrame_Initialize_Offsets
   __Pxy_PyFrame_Initialize_Offsets();
   #endif
   __pyx_empty_tuple = PyTuple_New(0); if (unlikely(!__pyx_empty_tuple)) __PYX_ERR(0, 1, __pyx_L1_error)
   __pyx_empty_bytes = PyBytes_FromStringAndSize("", 0); if (unlikely(!__pyx_empty_bytes)) __PYX_ERR(0, 1, __pyx_L1_error)
   __pyx_empty_unicode = PyUnicode_FromStringAndSize("", 0); if (unlikely(!__pyx_empty_unicode)) __PYX_ERR(0, 1, __pyx_L1_error)
@@ -19074,15 +18520,15 @@
   #endif
   /*--- Module creation code ---*/
   #if CYTHON_PEP489_MULTI_PHASE_INIT
   __pyx_m = __pyx_pyinit_module;
   Py_INCREF(__pyx_m);
   #else
   #if PY_MAJOR_VERSION < 3
-  __pyx_m = Py_InitModule4("fast_entropy", __pyx_methods, 0, 0, PYTHON_API_VERSION); Py_XINCREF(__pyx_m);
+  __pyx_m = Py_InitModule4("fast_flash_entropy_search_cpython", __pyx_methods, 0, 0, PYTHON_API_VERSION); Py_XINCREF(__pyx_m);
   #else
   __pyx_m = PyModule_Create(&__pyx_moduledef);
   #endif
   if (unlikely(!__pyx_m)) __PYX_ERR(0, 1, __pyx_L1_error)
   #endif
   __pyx_d = PyModule_GetDict(__pyx_m); if (unlikely(!__pyx_d)) __PYX_ERR(0, 1, __pyx_L1_error)
   Py_INCREF(__pyx_d);
@@ -19092,22 +18538,22 @@
   Py_INCREF(__pyx_cython_runtime);
   if (PyObject_SetAttrString(__pyx_m, "__builtins__", __pyx_b) < 0) __PYX_ERR(0, 1, __pyx_L1_error)
   /*--- Initialize various global constants etc. ---*/
   if (__Pyx_InitGlobals() < 0) __PYX_ERR(0, 1, __pyx_L1_error)
   #if PY_MAJOR_VERSION < 3 && (__PYX_DEFAULT_STRING_ENCODING_IS_ASCII || __PYX_DEFAULT_STRING_ENCODING_IS_DEFAULT)
   if (__Pyx_init_sys_getdefaultencoding_params() < 0) __PYX_ERR(0, 1, __pyx_L1_error)
   #endif
-  if (__pyx_module_is_main_ms_entropy__tools__fast_entropy) {
+  if (__pyx_module_is_main_ms_entropy__entropy_search__fast_flash_entropy_search_cpython) {
     if (PyObject_SetAttr(__pyx_m, __pyx_n_s_name_2, __pyx_n_s_main) < 0) __PYX_ERR(0, 1, __pyx_L1_error)
   }
   #if PY_MAJOR_VERSION >= 3
   {
     PyObject *modules = PyImport_GetModuleDict(); if (unlikely(!modules)) __PYX_ERR(0, 1, __pyx_L1_error)
-    if (!PyDict_GetItemString(modules, "ms_entropy.tools.fast_entropy")) {
-      if (unlikely(PyDict_SetItemString(modules, "ms_entropy.tools.fast_entropy", __pyx_m) < 0)) __PYX_ERR(0, 1, __pyx_L1_error)
+    if (!PyDict_GetItemString(modules, "ms_entropy.entropy_search.fast_flash_entropy_search_cpython")) {
+      if (unlikely(PyDict_SetItemString(modules, "ms_entropy.entropy_search.fast_flash_entropy_search_cpython", __pyx_m) < 0)) __PYX_ERR(0, 1, __pyx_L1_error)
     }
   }
   #endif
   /*--- Builtin init code ---*/
   if (__Pyx_InitCachedBuiltins() < 0) __PYX_ERR(0, 1, __pyx_L1_error)
   /*--- Constants init code ---*/
   if (__Pyx_InitCachedConstants() < 0) __PYX_ERR(0, 1, __pyx_L1_error)
@@ -19120,30 +18566,30 @@
   (void)__Pyx_modinit_variable_import_code();
   (void)__Pyx_modinit_function_import_code();
   /*--- Execution code ---*/
   #if defined(__Pyx_Generator_USED) || defined(__Pyx_Coroutine_USED)
   if (__Pyx_patch_abc() < 0) __PYX_ERR(0, 1, __pyx_L1_error)
   #endif
 
-  /* "ms_entropy/tools/fast_entropy.pyx":1
+  /* "ms_entropy/entropy_search/fast_flash_entropy_search_cpython.pyx":1
  * import numpy as np             # <<<<<<<<<<<<<<
  * cimport numpy as np
  * 
  */
   __pyx_t_1 = __Pyx_Import(__pyx_n_s_numpy, 0, 0); if (unlikely(!__pyx_t_1)) __PYX_ERR(0, 1, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_1);
   if (PyDict_SetItem(__pyx_d, __pyx_n_s_np, __pyx_t_1) < 0) __PYX_ERR(0, 1, __pyx_L1_error)
   __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
 
-  /* "ms_entropy/tools/fast_entropy.pyx":63
- *     return spectrum_weighted
+  /* "ms_entropy/entropy_search/fast_flash_entropy_search_cpython.pyx":11
  * 
- * cpdef double spectral_entropy(float32[:,::1] spectrum) nogil:             # <<<<<<<<<<<<<<
- *     """
- *     Compute the spectral entropy of a spectrum. The intensity need to be pre-normalized, the function will not do it.
+ * 
+ * cpdef void cy_entropy_similarity_identity_search(int_64 product_mz_idx_min, int_64 product_mz_idx_max,             # <<<<<<<<<<<<<<
+ *                                                     float32 intensity, float32[:] entropy_similarity,
+ *                                                     const float32[:] library_peaks_intensity, const uint_32[:] library_spec_idx_array,
  */
   __pyx_t_1 = __Pyx_PyDict_NewPresized(0); if (unlikely(!__pyx_t_1)) __PYX_ERR(0, 1, __pyx_L1_error)
   __Pyx_GOTREF(__pyx_t_1);
   if (PyDict_SetItem(__pyx_d, __pyx_n_s_test, __pyx_t_1) < 0) __PYX_ERR(0, 1, __pyx_L1_error)
   __Pyx_DECREF(__pyx_t_1); __pyx_t_1 = 0;
 
   /* "View.MemoryView":210
@@ -19302,19 +18748,19 @@
   /*--- Wrapped vars code ---*/
 
   goto __pyx_L0;
   __pyx_L1_error:;
   __Pyx_XDECREF(__pyx_t_1);
   if (__pyx_m) {
     if (__pyx_d) {
-      __Pyx_AddTraceback("init ms_entropy.tools.fast_entropy", __pyx_clineno, __pyx_lineno, __pyx_filename);
+      __Pyx_AddTraceback("init ms_entropy.entropy_search.fast_flash_entropy_search_cpython", __pyx_clineno, __pyx_lineno, __pyx_filename);
     }
     Py_CLEAR(__pyx_m);
   } else if (!PyErr_Occurred()) {
-    PyErr_SetString(PyExc_ImportError, "init ms_entropy.tools.fast_entropy");
+    PyErr_SetString(PyExc_ImportError, "init ms_entropy.entropy_search.fast_flash_entropy_search_cpython");
   }
   __pyx_L0:;
   __Pyx_RefNannyFinishContext();
   #if CYTHON_PEP489_MULTI_PHASE_INIT
   return (__pyx_m != NULL) ? 0 : -1;
   #elif PY_MAJOR_VERSION >= 3
   return __pyx_m;
@@ -19644,326 +19090,14 @@
             PyGILState_Release(_gilstate);
         }
     } else {
         memslice->memview = NULL;
     }
 }
 
-/* PyDictVersioning */
-#if CYTHON_USE_DICT_VERSIONS && CYTHON_USE_TYPE_SLOTS
-static CYTHON_INLINE PY_UINT64_T __Pyx_get_tp_dict_version(PyObject *obj) {
-    PyObject *dict = Py_TYPE(obj)->tp_dict;
-    return likely(dict) ? __PYX_GET_DICT_VERSION(dict) : 0;
-}
-static CYTHON_INLINE PY_UINT64_T __Pyx_get_object_dict_version(PyObject *obj) {
-    PyObject **dictptr = NULL;
-    Py_ssize_t offset = Py_TYPE(obj)->tp_dictoffset;
-    if (offset) {
-#if CYTHON_COMPILING_IN_CPYTHON
-        dictptr = (likely(offset > 0)) ? (PyObject **) ((char *)obj + offset) : _PyObject_GetDictPtr(obj);
-#else
-        dictptr = _PyObject_GetDictPtr(obj);
-#endif
-    }
-    return (dictptr && *dictptr) ? __PYX_GET_DICT_VERSION(*dictptr) : 0;
-}
-static CYTHON_INLINE int __Pyx_object_dict_version_matches(PyObject* obj, PY_UINT64_T tp_dict_version, PY_UINT64_T obj_dict_version) {
-    PyObject *dict = Py_TYPE(obj)->tp_dict;
-    if (unlikely(!dict) || unlikely(tp_dict_version != __PYX_GET_DICT_VERSION(dict)))
-        return 0;
-    return obj_dict_version == __Pyx_get_object_dict_version(obj);
-}
-#endif
-
-/* GetModuleGlobalName */
-#if CYTHON_USE_DICT_VERSIONS
-static PyObject *__Pyx__GetModuleGlobalName(PyObject *name, PY_UINT64_T *dict_version, PyObject **dict_cached_value)
-#else
-static CYTHON_INLINE PyObject *__Pyx__GetModuleGlobalName(PyObject *name)
-#endif
-{
-    PyObject *result;
-#if !CYTHON_AVOID_BORROWED_REFS
-#if CYTHON_COMPILING_IN_CPYTHON && PY_VERSION_HEX >= 0x030500A1
-    result = _PyDict_GetItem_KnownHash(__pyx_d, name, ((PyASCIIObject *) name)->hash);
-    __PYX_UPDATE_DICT_CACHE(__pyx_d, result, *dict_cached_value, *dict_version)
-    if (likely(result)) {
-        return __Pyx_NewRef(result);
-    } else if (unlikely(PyErr_Occurred())) {
-        return NULL;
-    }
-#else
-    result = PyDict_GetItem(__pyx_d, name);
-    __PYX_UPDATE_DICT_CACHE(__pyx_d, result, *dict_cached_value, *dict_version)
-    if (likely(result)) {
-        return __Pyx_NewRef(result);
-    }
-#endif
-#else
-    result = PyObject_GetItem(__pyx_d, name);
-    __PYX_UPDATE_DICT_CACHE(__pyx_d, result, *dict_cached_value, *dict_version)
-    if (likely(result)) {
-        return __Pyx_NewRef(result);
-    }
-    PyErr_Clear();
-#endif
-    return __Pyx_GetBuiltinName(name);
-}
-
-/* PyCFunctionFastCall */
-#if CYTHON_FAST_PYCCALL
-static CYTHON_INLINE PyObject * __Pyx_PyCFunction_FastCall(PyObject *func_obj, PyObject **args, Py_ssize_t nargs) {
-    PyCFunctionObject *func = (PyCFunctionObject*)func_obj;
-    PyCFunction meth = PyCFunction_GET_FUNCTION(func);
-    PyObject *self = PyCFunction_GET_SELF(func);
-    int flags = PyCFunction_GET_FLAGS(func);
-    assert(PyCFunction_Check(func));
-    assert(METH_FASTCALL == (flags & ~(METH_CLASS | METH_STATIC | METH_COEXIST | METH_KEYWORDS | METH_STACKLESS)));
-    assert(nargs >= 0);
-    assert(nargs == 0 || args != NULL);
-    /* _PyCFunction_FastCallDict() must not be called with an exception set,
-       because it may clear it (directly or indirectly) and so the
-       caller loses its exception */
-    assert(!PyErr_Occurred());
-    if ((PY_VERSION_HEX < 0x030700A0) || unlikely(flags & METH_KEYWORDS)) {
-        return (*((__Pyx_PyCFunctionFastWithKeywords)(void*)meth)) (self, args, nargs, NULL);
-    } else {
-        return (*((__Pyx_PyCFunctionFast)(void*)meth)) (self, args, nargs);
-    }
-}
-#endif
-
-/* PyFunctionFastCall */
-#if CYTHON_FAST_PYCALL
-static PyObject* __Pyx_PyFunction_FastCallNoKw(PyCodeObject *co, PyObject **args, Py_ssize_t na,
-                                               PyObject *globals) {
-    PyFrameObject *f;
-    PyThreadState *tstate = __Pyx_PyThreadState_Current;
-    PyObject **fastlocals;
-    Py_ssize_t i;
-    PyObject *result;
-    assert(globals != NULL);
-    /* XXX Perhaps we should create a specialized
-       PyFrame_New() that doesn't take locals, but does
-       take builtins without sanity checking them.
-       */
-    assert(tstate != NULL);
-    f = PyFrame_New(tstate, co, globals, NULL);
-    if (f == NULL) {
-        return NULL;
-    }
-    fastlocals = __Pyx_PyFrame_GetLocalsplus(f);
-    for (i = 0; i < na; i++) {
-        Py_INCREF(*args);
-        fastlocals[i] = *args++;
-    }
-    result = PyEval_EvalFrameEx(f,0);
-    ++tstate->recursion_depth;
-    Py_DECREF(f);
-    --tstate->recursion_depth;
-    return result;
-}
-#if 1 || PY_VERSION_HEX < 0x030600B1
-static PyObject *__Pyx_PyFunction_FastCallDict(PyObject *func, PyObject **args, Py_ssize_t nargs, PyObject *kwargs) {
-    PyCodeObject *co = (PyCodeObject *)PyFunction_GET_CODE(func);
-    PyObject *globals = PyFunction_GET_GLOBALS(func);
-    PyObject *argdefs = PyFunction_GET_DEFAULTS(func);
-    PyObject *closure;
-#if PY_MAJOR_VERSION >= 3
-    PyObject *kwdefs;
-#endif
-    PyObject *kwtuple, **k;
-    PyObject **d;
-    Py_ssize_t nd;
-    Py_ssize_t nk;
-    PyObject *result;
-    assert(kwargs == NULL || PyDict_Check(kwargs));
-    nk = kwargs ? PyDict_Size(kwargs) : 0;
-    if (Py_EnterRecursiveCall((char*)" while calling a Python object")) {
-        return NULL;
-    }
-    if (
-#if PY_MAJOR_VERSION >= 3
-            co->co_kwonlyargcount == 0 &&
-#endif
-            likely(kwargs == NULL || nk == 0) &&
-            co->co_flags == (CO_OPTIMIZED | CO_NEWLOCALS | CO_NOFREE)) {
-        if (argdefs == NULL && co->co_argcount == nargs) {
-            result = __Pyx_PyFunction_FastCallNoKw(co, args, nargs, globals);
-            goto done;
-        }
-        else if (nargs == 0 && argdefs != NULL
-                 && co->co_argcount == Py_SIZE(argdefs)) {
-            /* function called with no arguments, but all parameters have
-               a default value: use default values as arguments .*/
-            args = &PyTuple_GET_ITEM(argdefs, 0);
-            result =__Pyx_PyFunction_FastCallNoKw(co, args, Py_SIZE(argdefs), globals);
-            goto done;
-        }
-    }
-    if (kwargs != NULL) {
-        Py_ssize_t pos, i;
-        kwtuple = PyTuple_New(2 * nk);
-        if (kwtuple == NULL) {
-            result = NULL;
-            goto done;
-        }
-        k = &PyTuple_GET_ITEM(kwtuple, 0);
-        pos = i = 0;
-        while (PyDict_Next(kwargs, &pos, &k[i], &k[i+1])) {
-            Py_INCREF(k[i]);
-            Py_INCREF(k[i+1]);
-            i += 2;
-        }
-        nk = i / 2;
-    }
-    else {
-        kwtuple = NULL;
-        k = NULL;
-    }
-    closure = PyFunction_GET_CLOSURE(func);
-#if PY_MAJOR_VERSION >= 3
-    kwdefs = PyFunction_GET_KW_DEFAULTS(func);
-#endif
-    if (argdefs != NULL) {
-        d = &PyTuple_GET_ITEM(argdefs, 0);
-        nd = Py_SIZE(argdefs);
-    }
-    else {
-        d = NULL;
-        nd = 0;
-    }
-#if PY_MAJOR_VERSION >= 3
-    result = PyEval_EvalCodeEx((PyObject*)co, globals, (PyObject *)NULL,
-                               args, (int)nargs,
-                               k, (int)nk,
-                               d, (int)nd, kwdefs, closure);
-#else
-    result = PyEval_EvalCodeEx(co, globals, (PyObject *)NULL,
-                               args, (int)nargs,
-                               k, (int)nk,
-                               d, (int)nd, closure);
-#endif
-    Py_XDECREF(kwtuple);
-done:
-    Py_LeaveRecursiveCall();
-    return result;
-}
-#endif
-#endif
-
-/* PyObjectCall */
-#if CYTHON_COMPILING_IN_CPYTHON
-static CYTHON_INLINE PyObject* __Pyx_PyObject_Call(PyObject *func, PyObject *arg, PyObject *kw) {
-    PyObject *result;
-    ternaryfunc call = Py_TYPE(func)->tp_call;
-    if (unlikely(!call))
-        return PyObject_Call(func, arg, kw);
-    if (unlikely(Py_EnterRecursiveCall((char*)" while calling a Python object")))
-        return NULL;
-    result = (*call)(func, arg, kw);
-    Py_LeaveRecursiveCall();
-    if (unlikely(!result) && unlikely(!PyErr_Occurred())) {
-        PyErr_SetString(
-            PyExc_SystemError,
-            "NULL result without error in PyObject_Call");
-    }
-    return result;
-}
-#endif
-
-/* PyObjectCall2Args */
-static CYTHON_UNUSED PyObject* __Pyx_PyObject_Call2Args(PyObject* function, PyObject* arg1, PyObject* arg2) {
-    PyObject *args, *result = NULL;
-    #if CYTHON_FAST_PYCALL
-    if (PyFunction_Check(function)) {
-        PyObject *args[2] = {arg1, arg2};
-        return __Pyx_PyFunction_FastCall(function, args, 2);
-    }
-    #endif
-    #if CYTHON_FAST_PYCCALL
-    if (__Pyx_PyFastCFunction_Check(function)) {
-        PyObject *args[2] = {arg1, arg2};
-        return __Pyx_PyCFunction_FastCall(function, args, 2);
-    }
-    #endif
-    args = PyTuple_New(2);
-    if (unlikely(!args)) goto done;
-    Py_INCREF(arg1);
-    PyTuple_SET_ITEM(args, 0, arg1);
-    Py_INCREF(arg2);
-    PyTuple_SET_ITEM(args, 1, arg2);
-    Py_INCREF(function);
-    result = __Pyx_PyObject_Call(function, args, NULL);
-    Py_DECREF(args);
-    Py_DECREF(function);
-done:
-    return result;
-}
-
-/* PyObjectCallMethO */
-#if CYTHON_COMPILING_IN_CPYTHON
-static CYTHON_INLINE PyObject* __Pyx_PyObject_CallMethO(PyObject *func, PyObject *arg) {
-    PyObject *self, *result;
-    PyCFunction cfunc;
-    cfunc = PyCFunction_GET_FUNCTION(func);
-    self = PyCFunction_GET_SELF(func);
-    if (unlikely(Py_EnterRecursiveCall((char*)" while calling a Python object")))
-        return NULL;
-    result = cfunc(self, arg);
-    Py_LeaveRecursiveCall();
-    if (unlikely(!result) && unlikely(!PyErr_Occurred())) {
-        PyErr_SetString(
-            PyExc_SystemError,
-            "NULL result without error in PyObject_Call");
-    }
-    return result;
-}
-#endif
-
-/* PyObjectCallOneArg */
-#if CYTHON_COMPILING_IN_CPYTHON
-static PyObject* __Pyx__PyObject_CallOneArg(PyObject *func, PyObject *arg) {
-    PyObject *result;
-    PyObject *args = PyTuple_New(1);
-    if (unlikely(!args)) return NULL;
-    Py_INCREF(arg);
-    PyTuple_SET_ITEM(args, 0, arg);
-    result = __Pyx_PyObject_Call(func, args, NULL);
-    Py_DECREF(args);
-    return result;
-}
-static CYTHON_INLINE PyObject* __Pyx_PyObject_CallOneArg(PyObject *func, PyObject *arg) {
-#if CYTHON_FAST_PYCALL
-    if (PyFunction_Check(func)) {
-        return __Pyx_PyFunction_FastCall(func, &arg, 1);
-    }
-#endif
-    if (likely(PyCFunction_Check(func))) {
-        if (likely(PyCFunction_GET_FLAGS(func) & METH_O)) {
-            return __Pyx_PyObject_CallMethO(func, arg);
-#if CYTHON_FAST_PYCCALL
-        } else if (__Pyx_PyFastCFunction_Check(func)) {
-            return __Pyx_PyCFunction_FastCall(func, &arg, 1);
-#endif
-        }
-    }
-    return __Pyx__PyObject_CallOneArg(func, arg);
-}
-#else
-static CYTHON_INLINE PyObject* __Pyx_PyObject_CallOneArg(PyObject *func, PyObject *arg) {
-    PyObject *result;
-    PyObject *args = PyTuple_Pack(1, arg);
-    if (unlikely(!args)) return NULL;
-    result = __Pyx_PyObject_Call(func, args, NULL);
-    Py_DECREF(args);
-    return result;
-}
-#endif
-
 /* GetTopmostException */
 #if CYTHON_USE_EXC_INFO_STACK
 static _PyErr_StackItem *
 __Pyx_PyErr_GetTopmostException(PyThreadState *tstate)
 {
     _PyErr_StackItem *exc_info = tstate->exc_info;
     while ((exc_info->exc_type == NULL || exc_info->exc_type == Py_None) &&
@@ -20111,14 +19245,34 @@
     *tb = 0;
     Py_XDECREF(local_type);
     Py_XDECREF(local_value);
     Py_XDECREF(local_tb);
     return -1;
 }
 
+/* PyObjectCall */
+#if CYTHON_COMPILING_IN_CPYTHON
+static CYTHON_INLINE PyObject* __Pyx_PyObject_Call(PyObject *func, PyObject *arg, PyObject *kw) {
+    PyObject *result;
+    ternaryfunc call = Py_TYPE(func)->tp_call;
+    if (unlikely(!call))
+        return PyObject_Call(func, arg, kw);
+    if (unlikely(Py_EnterRecursiveCall((char*)" while calling a Python object")))
+        return NULL;
+    result = (*call)(func, arg, kw);
+    Py_LeaveRecursiveCall();
+    if (unlikely(!result) && unlikely(!PyErr_Occurred())) {
+        PyErr_SetString(
+            PyExc_SystemError,
+            "NULL result without error in PyObject_Call");
+    }
+    return result;
+}
+#endif
+
 /* PyErrFetchRestore */
 #if CYTHON_FAST_THREAD_STATE
 static CYTHON_INLINE void __Pyx_ErrRestoreInState(PyThreadState *tstate, PyObject *type, PyObject *value, PyObject *tb) {
     PyObject *tmp_type, *tmp_value, *tmp_tb;
     tmp_type = tstate->curexc_type;
     tmp_value = tstate->curexc_value;
     tmp_tb = tstate->curexc_traceback;
@@ -20272,28 +19426,28 @@
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
@@ -20315,14 +19469,245 @@
     }
     PyErr_Format(PyExc_TypeError,
         "Argument '%.200s' has incorrect type (expected %.200s, got %.200s)",
         name, type->tp_name, Py_TYPE(obj)->tp_name);
     return 0;
 }
 
+/* PyCFunctionFastCall */
+#if CYTHON_FAST_PYCCALL
+static CYTHON_INLINE PyObject * __Pyx_PyCFunction_FastCall(PyObject *func_obj, PyObject **args, Py_ssize_t nargs) {
+    PyCFunctionObject *func = (PyCFunctionObject*)func_obj;
+    PyCFunction meth = PyCFunction_GET_FUNCTION(func);
+    PyObject *self = PyCFunction_GET_SELF(func);
+    int flags = PyCFunction_GET_FLAGS(func);
+    assert(PyCFunction_Check(func));
+    assert(METH_FASTCALL == (flags & ~(METH_CLASS | METH_STATIC | METH_COEXIST | METH_KEYWORDS | METH_STACKLESS)));
+    assert(nargs >= 0);
+    assert(nargs == 0 || args != NULL);
+    /* _PyCFunction_FastCallDict() must not be called with an exception set,
+       because it may clear it (directly or indirectly) and so the
+       caller loses its exception */
+    assert(!PyErr_Occurred());
+    if ((PY_VERSION_HEX < 0x030700A0) || unlikely(flags & METH_KEYWORDS)) {
+        return (*((__Pyx_PyCFunctionFastWithKeywords)(void*)meth)) (self, args, nargs, NULL);
+    } else {
+        return (*((__Pyx_PyCFunctionFast)(void*)meth)) (self, args, nargs);
+    }
+}
+#endif
+
+/* PyFunctionFastCall */
+#if CYTHON_FAST_PYCALL
+static PyObject* __Pyx_PyFunction_FastCallNoKw(PyCodeObject *co, PyObject **args, Py_ssize_t na,
+                                               PyObject *globals) {
+    PyFrameObject *f;
+    PyThreadState *tstate = __Pyx_PyThreadState_Current;
+    PyObject **fastlocals;
+    Py_ssize_t i;
+    PyObject *result;
+    assert(globals != NULL);
+    /* XXX Perhaps we should create a specialized
+       PyFrame_New() that doesn't take locals, but does
+       take builtins without sanity checking them.
+       */
+    assert(tstate != NULL);
+    f = PyFrame_New(tstate, co, globals, NULL);
+    if (f == NULL) {
+        return NULL;
+    }
+    fastlocals = __Pyx_PyFrame_GetLocalsplus(f);
+    for (i = 0; i < na; i++) {
+        Py_INCREF(*args);
+        fastlocals[i] = *args++;
+    }
+    result = PyEval_EvalFrameEx(f,0);
+    ++tstate->recursion_depth;
+    Py_DECREF(f);
+    --tstate->recursion_depth;
+    return result;
+}
+#if 1 || PY_VERSION_HEX < 0x030600B1
+static PyObject *__Pyx_PyFunction_FastCallDict(PyObject *func, PyObject **args, Py_ssize_t nargs, PyObject *kwargs) {
+    PyCodeObject *co = (PyCodeObject *)PyFunction_GET_CODE(func);
+    PyObject *globals = PyFunction_GET_GLOBALS(func);
+    PyObject *argdefs = PyFunction_GET_DEFAULTS(func);
+    PyObject *closure;
+#if PY_MAJOR_VERSION >= 3
+    PyObject *kwdefs;
+#endif
+    PyObject *kwtuple, **k;
+    PyObject **d;
+    Py_ssize_t nd;
+    Py_ssize_t nk;
+    PyObject *result;
+    assert(kwargs == NULL || PyDict_Check(kwargs));
+    nk = kwargs ? PyDict_Size(kwargs) : 0;
+    if (Py_EnterRecursiveCall((char*)" while calling a Python object")) {
+        return NULL;
+    }
+    if (
+#if PY_MAJOR_VERSION >= 3
+            co->co_kwonlyargcount == 0 &&
+#endif
+            likely(kwargs == NULL || nk == 0) &&
+            co->co_flags == (CO_OPTIMIZED | CO_NEWLOCALS | CO_NOFREE)) {
+        if (argdefs == NULL && co->co_argcount == nargs) {
+            result = __Pyx_PyFunction_FastCallNoKw(co, args, nargs, globals);
+            goto done;
+        }
+        else if (nargs == 0 && argdefs != NULL
+                 && co->co_argcount == Py_SIZE(argdefs)) {
+            /* function called with no arguments, but all parameters have
+               a default value: use default values as arguments .*/
+            args = &PyTuple_GET_ITEM(argdefs, 0);
+            result =__Pyx_PyFunction_FastCallNoKw(co, args, Py_SIZE(argdefs), globals);
+            goto done;
+        }
+    }
+    if (kwargs != NULL) {
+        Py_ssize_t pos, i;
+        kwtuple = PyTuple_New(2 * nk);
+        if (kwtuple == NULL) {
+            result = NULL;
+            goto done;
+        }
+        k = &PyTuple_GET_ITEM(kwtuple, 0);
+        pos = i = 0;
+        while (PyDict_Next(kwargs, &pos, &k[i], &k[i+1])) {
+            Py_INCREF(k[i]);
+            Py_INCREF(k[i+1]);
+            i += 2;
+        }
+        nk = i / 2;
+    }
+    else {
+        kwtuple = NULL;
+        k = NULL;
+    }
+    closure = PyFunction_GET_CLOSURE(func);
+#if PY_MAJOR_VERSION >= 3
+    kwdefs = PyFunction_GET_KW_DEFAULTS(func);
+#endif
+    if (argdefs != NULL) {
+        d = &PyTuple_GET_ITEM(argdefs, 0);
+        nd = Py_SIZE(argdefs);
+    }
+    else {
+        d = NULL;
+        nd = 0;
+    }
+#if PY_MAJOR_VERSION >= 3
+    result = PyEval_EvalCodeEx((PyObject*)co, globals, (PyObject *)NULL,
+                               args, (int)nargs,
+                               k, (int)nk,
+                               d, (int)nd, kwdefs, closure);
+#else
+    result = PyEval_EvalCodeEx(co, globals, (PyObject *)NULL,
+                               args, (int)nargs,
+                               k, (int)nk,
+                               d, (int)nd, closure);
+#endif
+    Py_XDECREF(kwtuple);
+done:
+    Py_LeaveRecursiveCall();
+    return result;
+}
+#endif
+#endif
+
+/* PyObjectCall2Args */
+static CYTHON_UNUSED PyObject* __Pyx_PyObject_Call2Args(PyObject* function, PyObject* arg1, PyObject* arg2) {
+    PyObject *args, *result = NULL;
+    #if CYTHON_FAST_PYCALL
+    if (PyFunction_Check(function)) {
+        PyObject *args[2] = {arg1, arg2};
+        return __Pyx_PyFunction_FastCall(function, args, 2);
+    }
+    #endif
+    #if CYTHON_FAST_PYCCALL
+    if (__Pyx_PyFastCFunction_Check(function)) {
+        PyObject *args[2] = {arg1, arg2};
+        return __Pyx_PyCFunction_FastCall(function, args, 2);
+    }
+    #endif
+    args = PyTuple_New(2);
+    if (unlikely(!args)) goto done;
+    Py_INCREF(arg1);
+    PyTuple_SET_ITEM(args, 0, arg1);
+    Py_INCREF(arg2);
+    PyTuple_SET_ITEM(args, 1, arg2);
+    Py_INCREF(function);
+    result = __Pyx_PyObject_Call(function, args, NULL);
+    Py_DECREF(args);
+    Py_DECREF(function);
+done:
+    return result;
+}
+
+/* PyObjectCallMethO */
+#if CYTHON_COMPILING_IN_CPYTHON
+static CYTHON_INLINE PyObject* __Pyx_PyObject_CallMethO(PyObject *func, PyObject *arg) {
+    PyObject *self, *result;
+    PyCFunction cfunc;
+    cfunc = PyCFunction_GET_FUNCTION(func);
+    self = PyCFunction_GET_SELF(func);
+    if (unlikely(Py_EnterRecursiveCall((char*)" while calling a Python object")))
+        return NULL;
+    result = cfunc(self, arg);
+    Py_LeaveRecursiveCall();
+    if (unlikely(!result) && unlikely(!PyErr_Occurred())) {
+        PyErr_SetString(
+            PyExc_SystemError,
+            "NULL result without error in PyObject_Call");
+    }
+    return result;
+}
+#endif
+
+/* PyObjectCallOneArg */
+#if CYTHON_COMPILING_IN_CPYTHON
+static PyObject* __Pyx__PyObject_CallOneArg(PyObject *func, PyObject *arg) {
+    PyObject *result;
+    PyObject *args = PyTuple_New(1);
+    if (unlikely(!args)) return NULL;
+    Py_INCREF(arg);
+    PyTuple_SET_ITEM(args, 0, arg);
+    result = __Pyx_PyObject_Call(func, args, NULL);
+    Py_DECREF(args);
+    return result;
+}
+static CYTHON_INLINE PyObject* __Pyx_PyObject_CallOneArg(PyObject *func, PyObject *arg) {
+#if CYTHON_FAST_PYCALL
+    if (PyFunction_Check(func)) {
+        return __Pyx_PyFunction_FastCall(func, &arg, 1);
+    }
+#endif
+    if (likely(PyCFunction_Check(func))) {
+        if (likely(PyCFunction_GET_FLAGS(func) & METH_O)) {
+            return __Pyx_PyObject_CallMethO(func, arg);
+#if CYTHON_FAST_PYCCALL
+        } else if (__Pyx_PyFastCFunction_Check(func)) {
+            return __Pyx_PyCFunction_FastCall(func, &arg, 1);
+#endif
+        }
+    }
+    return __Pyx__PyObject_CallOneArg(func, arg);
+}
+#else
+static CYTHON_INLINE PyObject* __Pyx_PyObject_CallOneArg(PyObject *func, PyObject *arg) {
+    PyObject *result;
+    PyObject *args = PyTuple_Pack(1, arg);
+    if (unlikely(!args)) return NULL;
+    result = __Pyx_PyObject_Call(func, args, NULL);
+    Py_DECREF(args);
+    return result;
+}
+#endif
+
 /* BytesEquals */
 static CYTHON_INLINE int __Pyx_PyBytes_Equals(PyObject* s1, PyObject* s2, int equals) {
 #if CYTHON_COMPILING_IN_PYPY
     return PyObject_RichCompareBool(s1, s2, equals);
 #else
     if (s1 == s2) {
         return (equals == Py_EQ);
@@ -20641,14 +20026,75 @@
     return d;
 }
 static CYTHON_INLINE PyObject *__Pyx_GetAttr3(PyObject *o, PyObject *n, PyObject *d) {
     PyObject *r = __Pyx_GetAttr(o, n);
     return (likely(r)) ? r : __Pyx_GetAttr3Default(d);
 }
 
+/* PyDictVersioning */
+#if CYTHON_USE_DICT_VERSIONS && CYTHON_USE_TYPE_SLOTS
+static CYTHON_INLINE PY_UINT64_T __Pyx_get_tp_dict_version(PyObject *obj) {
+    PyObject *dict = Py_TYPE(obj)->tp_dict;
+    return likely(dict) ? __PYX_GET_DICT_VERSION(dict) : 0;
+}
+static CYTHON_INLINE PY_UINT64_T __Pyx_get_object_dict_version(PyObject *obj) {
+    PyObject **dictptr = NULL;
+    Py_ssize_t offset = Py_TYPE(obj)->tp_dictoffset;
+    if (offset) {
+#if CYTHON_COMPILING_IN_CPYTHON
+        dictptr = (likely(offset > 0)) ? (PyObject **) ((char *)obj + offset) : _PyObject_GetDictPtr(obj);
+#else
+        dictptr = _PyObject_GetDictPtr(obj);
+#endif
+    }
+    return (dictptr && *dictptr) ? __PYX_GET_DICT_VERSION(*dictptr) : 0;
+}
+static CYTHON_INLINE int __Pyx_object_dict_version_matches(PyObject* obj, PY_UINT64_T tp_dict_version, PY_UINT64_T obj_dict_version) {
+    PyObject *dict = Py_TYPE(obj)->tp_dict;
+    if (unlikely(!dict) || unlikely(tp_dict_version != __PYX_GET_DICT_VERSION(dict)))
+        return 0;
+    return obj_dict_version == __Pyx_get_object_dict_version(obj);
+}
+#endif
+
+/* GetModuleGlobalName */
+#if CYTHON_USE_DICT_VERSIONS
+static PyObject *__Pyx__GetModuleGlobalName(PyObject *name, PY_UINT64_T *dict_version, PyObject **dict_cached_value)
+#else
+static CYTHON_INLINE PyObject *__Pyx__GetModuleGlobalName(PyObject *name)
+#endif
+{
+    PyObject *result;
+#if !CYTHON_AVOID_BORROWED_REFS
+#if CYTHON_COMPILING_IN_CPYTHON && PY_VERSION_HEX >= 0x030500A1
+    result = _PyDict_GetItem_KnownHash(__pyx_d, name, ((PyASCIIObject *) name)->hash);
+    __PYX_UPDATE_DICT_CACHE(__pyx_d, result, *dict_cached_value, *dict_version)
+    if (likely(result)) {
+        return __Pyx_NewRef(result);
+    } else if (unlikely(PyErr_Occurred())) {
+        return NULL;
+    }
+#else
+    result = PyDict_GetItem(__pyx_d, name);
+    __PYX_UPDATE_DICT_CACHE(__pyx_d, result, *dict_cached_value, *dict_version)
+    if (likely(result)) {
+        return __Pyx_NewRef(result);
+    }
+#endif
+#else
+    result = PyObject_GetItem(__pyx_d, name);
+    __PYX_UPDATE_DICT_CACHE(__pyx_d, result, *dict_cached_value, *dict_version)
+    if (likely(result)) {
+        return __Pyx_NewRef(result);
+    }
+    PyErr_Clear();
+#endif
+    return __Pyx_GetBuiltinName(name);
+}
+
 /* RaiseTooManyValuesToUnpack */
 static CYTHON_INLINE void __Pyx_RaiseTooManyValuesError(Py_ssize_t expected) {
     PyErr_Format(PyExc_ValueError,
                  "too many values to unpack (expected %" CYTHON_FORMAT_SSIZE_T "d)", expected);
 }
 
 /* RaiseNeedMoreValuesToUnpack */
@@ -21223,61 +20669,79 @@
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
@@ -22363,140 +21827,82 @@
     retval = -1;
 no_fail:
     __Pyx_RefNannyFinishContext();
     return retval;
 }
 
 /* ObjectToMemviewSlice */
-  static CYTHON_INLINE __Pyx_memviewslice __Pyx_PyObject_to_MemoryviewSlice_ds_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_float32(PyObject *obj, int writable_flag) {
-    __Pyx_memviewslice result = { 0, 0, { 0 }, { 0 }, { 0 } };
-    __Pyx_BufFmt_StackElem stack[1];
-    int axes_specs[] = { (__Pyx_MEMVIEW_DIRECT | __Pyx_MEMVIEW_STRIDED) };
-    int retcode;
-    if (obj == Py_None) {
-        result.memview = (struct __pyx_memoryview_obj *) Py_None;
-        return result;
-    }
-    retcode = __Pyx_ValidateAndInit_memviewslice(axes_specs, 0,
-                                                 PyBUF_RECORDS_RO | writable_flag, 1,
-                                                 &__Pyx_TypeInfo_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_float32, stack,
-                                                 &result, obj);
-    if (unlikely(retcode == -1))
-        goto __pyx_fail;
-    return result;
-__pyx_fail:
-    result.memview = NULL;
-    result.data = NULL;
-    return result;
-}
-
-/* ObjectToMemviewSlice */
-  static CYTHON_INLINE __Pyx_memviewslice __Pyx_PyObject_to_MemoryviewSlice_ds_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_float32__const__(PyObject *obj, int writable_flag) {
+  static CYTHON_INLINE __Pyx_memviewslice __Pyx_PyObject_to_MemoryviewSlice_ds_nn___pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_float32(PyObject *obj, int writable_flag) {
     __Pyx_memviewslice result = { 0, 0, { 0 }, { 0 }, { 0 } };
     __Pyx_BufFmt_StackElem stack[1];
     int axes_specs[] = { (__Pyx_MEMVIEW_DIRECT | __Pyx_MEMVIEW_STRIDED) };
     int retcode;
     if (obj == Py_None) {
         result.memview = (struct __pyx_memoryview_obj *) Py_None;
         return result;
     }
     retcode = __Pyx_ValidateAndInit_memviewslice(axes_specs, 0,
                                                  PyBUF_RECORDS_RO | writable_flag, 1,
-                                                 &__Pyx_TypeInfo_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_float32__const__, stack,
+                                                 &__Pyx_TypeInfo_nn___pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_float32, stack,
                                                  &result, obj);
     if (unlikely(retcode == -1))
         goto __pyx_fail;
     return result;
 __pyx_fail:
     result.memview = NULL;
     result.data = NULL;
     return result;
 }
 
 /* ObjectToMemviewSlice */
-  static CYTHON_INLINE __Pyx_memviewslice __Pyx_PyObject_to_MemoryviewSlice_ds_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_uint_32__const__(PyObject *obj, int writable_flag) {
+  static CYTHON_INLINE __Pyx_memviewslice __Pyx_PyObject_to_MemoryviewSlice_ds_nn___pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_float32__const__(PyObject *obj, int writable_flag) {
     __Pyx_memviewslice result = { 0, 0, { 0 }, { 0 }, { 0 } };
     __Pyx_BufFmt_StackElem stack[1];
     int axes_specs[] = { (__Pyx_MEMVIEW_DIRECT | __Pyx_MEMVIEW_STRIDED) };
     int retcode;
     if (obj == Py_None) {
         result.memview = (struct __pyx_memoryview_obj *) Py_None;
         return result;
     }
     retcode = __Pyx_ValidateAndInit_memviewslice(axes_specs, 0,
                                                  PyBUF_RECORDS_RO | writable_flag, 1,
-                                                 &__Pyx_TypeInfo_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_uint_32__const__, stack,
+                                                 &__Pyx_TypeInfo_nn___pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_float32__const__, stack,
                                                  &result, obj);
     if (unlikely(retcode == -1))
         goto __pyx_fail;
     return result;
 __pyx_fail:
     result.memview = NULL;
     result.data = NULL;
     return result;
 }
 
 /* ObjectToMemviewSlice */
-  static CYTHON_INLINE __Pyx_memviewslice __Pyx_PyObject_to_MemoryviewSlice_ds_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_int_8__const__(PyObject *obj, int writable_flag) {
+  static CYTHON_INLINE __Pyx_memviewslice __Pyx_PyObject_to_MemoryviewSlice_ds_nn___pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_uint_32__const__(PyObject *obj, int writable_flag) {
     __Pyx_memviewslice result = { 0, 0, { 0 }, { 0 }, { 0 } };
     __Pyx_BufFmt_StackElem stack[1];
     int axes_specs[] = { (__Pyx_MEMVIEW_DIRECT | __Pyx_MEMVIEW_STRIDED) };
     int retcode;
     if (obj == Py_None) {
         result.memview = (struct __pyx_memoryview_obj *) Py_None;
         return result;
     }
     retcode = __Pyx_ValidateAndInit_memviewslice(axes_specs, 0,
                                                  PyBUF_RECORDS_RO | writable_flag, 1,
-                                                 &__Pyx_TypeInfo_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_int_8__const__, stack,
+                                                 &__Pyx_TypeInfo_nn___pyx_t_10ms_entropy_14entropy_search_33fast_flash_entropy_search_cpython_uint_32__const__, stack,
                                                  &result, obj);
     if (unlikely(retcode == -1))
         goto __pyx_fail;
     return result;
 __pyx_fail:
     result.memview = NULL;
     result.data = NULL;
     return result;
 }
 
-/* ObjectToMemviewSlice */
-  static CYTHON_INLINE __Pyx_memviewslice __Pyx_PyObject_to_MemoryviewSlice_d_dc_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_float32(PyObject *obj, int writable_flag) {
-    __Pyx_memviewslice result = { 0, 0, { 0 }, { 0 }, { 0 } };
-    __Pyx_BufFmt_StackElem stack[1];
-    int axes_specs[] = { (__Pyx_MEMVIEW_DIRECT | __Pyx_MEMVIEW_FOLLOW), (__Pyx_MEMVIEW_DIRECT | __Pyx_MEMVIEW_CONTIG) };
-    int retcode;
-    if (obj == Py_None) {
-        result.memview = (struct __pyx_memoryview_obj *) Py_None;
-        return result;
-    }
-    retcode = __Pyx_ValidateAndInit_memviewslice(axes_specs, __Pyx_IS_C_CONTIG,
-                                                 (PyBUF_C_CONTIGUOUS | PyBUF_FORMAT) | writable_flag, 2,
-                                                 &__Pyx_TypeInfo_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_float32, stack,
-                                                 &result, obj);
-    if (unlikely(retcode == -1))
-        goto __pyx_fail;
-    return result;
-__pyx_fail:
-    result.memview = NULL;
-    result.data = NULL;
-    return result;
-}
-
-/* MemviewDtypeToObject */
-  static CYTHON_INLINE PyObject *__pyx_memview_get_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_float32(const char *itemp) {
-    return (PyObject *) PyFloat_FromDouble(*(__pyx_t_10ms_entropy_5tools_12fast_entropy_float32 *) itemp);
-}
-static CYTHON_INLINE int __pyx_memview_set_nn___pyx_t_10ms_entropy_5tools_12fast_entropy_float32(const char *itemp, PyObject *obj) {
-    __pyx_t_10ms_entropy_5tools_12fast_entropy_float32 value = __pyx_PyFloat_AsFloat(obj);
-    if ((value == ((npy_float32)-1)) && PyErr_Occurred())
-        return 0;
-    *(__pyx_t_10ms_entropy_5tools_12fast_entropy_float32 *) itemp = value;
-    return 1;
-}
-
 /* Declarations */
   #if CYTHON_CCOMPLEX
   #ifdef __cplusplus
     static CYTHON_INLINE __pyx_t_float_complex __pyx_t_float_complex_from_parts(float x, float y) {
       return ::std::complex< float >(x, y);
     }
   #else
@@ -22924,15 +22330,15 @@
                         } else if (8 * sizeof(npy_int64) >= 4 * PyLong_SHIFT) {
                             return (npy_int64) (((((((((npy_int64)digits[3]) << PyLong_SHIFT) | (npy_int64)digits[2]) << PyLong_SHIFT) | (npy_int64)digits[1]) << PyLong_SHIFT) | (npy_int64)digits[0]));
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
@@ -23060,14 +22466,52 @@
     return (npy_int64) -1;
 raise_neg_overflow:
     PyErr_SetString(PyExc_OverflowError,
         "can't convert negative value to npy_int64");
     return (npy_int64) -1;
 }
 
+/* CIntToPy */
+  static CYTHON_INLINE PyObject* __Pyx_PyInt_From_npy_int64(npy_int64 value) {
+#ifdef __Pyx_HAS_GCC_DIAGNOSTIC
+#pragma GCC diagnostic push
+#pragma GCC diagnostic ignored "-Wconversion"
+#endif
+    const npy_int64 neg_one = (npy_int64) -1, const_zero = (npy_int64) 0;
+#ifdef __Pyx_HAS_GCC_DIAGNOSTIC
+#pragma GCC diagnostic pop
+#endif
+    const int is_unsigned = neg_one > const_zero;
+    if (is_unsigned) {
+        if (sizeof(npy_int64) < sizeof(long)) {
+            return PyInt_FromLong((long) value);
+        } else if (sizeof(npy_int64) <= sizeof(unsigned long)) {
+            return PyLong_FromUnsignedLong((unsigned long) value);
+#ifdef HAVE_LONG_LONG
+        } else if (sizeof(npy_int64) <= sizeof(unsigned PY_LONG_LONG)) {
+            return PyLong_FromUnsignedLongLong((unsigned PY_LONG_LONG) value);
+#endif
+        }
+    } else {
+        if (sizeof(npy_int64) <= sizeof(long)) {
+            return PyInt_FromLong((long) value);
+#ifdef HAVE_LONG_LONG
+        } else if (sizeof(npy_int64) <= sizeof(PY_LONG_LONG)) {
+            return PyLong_FromLongLong((PY_LONG_LONG) value);
+#endif
+        }
+    }
+    {
+        int one = 1; int little = (int)*(unsigned char *)&one;
+        unsigned char *bytes = (unsigned char *)&value;
+        return _PyLong_FromByteArray(bytes, sizeof(npy_int64),
+                                     little, !is_unsigned);
+    }
+}
+
 /* CIntFromPy */
   static CYTHON_INLINE int __Pyx_PyInt_As_int(PyObject *x) {
 #ifdef __Pyx_HAS_GCC_DIAGNOSTIC
 #pragma GCC diagnostic push
 #pragma GCC diagnostic ignored "-Wconversion"
 #endif
     const int neg_one = (int) -1, const_zero = (int) 0;
@@ -23120,15 +22564,15 @@
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
@@ -23256,90 +22700,14 @@
     return (int) -1;
 raise_neg_overflow:
     PyErr_SetString(PyExc_OverflowError,
         "can't convert negative value to int");
     return (int) -1;
 }
 
-/* CIntToPy */
-  static CYTHON_INLINE PyObject* __Pyx_PyInt_From_npy_int64(npy_int64 value) {
-#ifdef __Pyx_HAS_GCC_DIAGNOSTIC
-#pragma GCC diagnostic push
-#pragma GCC diagnostic ignored "-Wconversion"
-#endif
-    const npy_int64 neg_one = (npy_int64) -1, const_zero = (npy_int64) 0;
-#ifdef __Pyx_HAS_GCC_DIAGNOSTIC
-#pragma GCC diagnostic pop
-#endif
-    const int is_unsigned = neg_one > const_zero;
-    if (is_unsigned) {
-        if (sizeof(npy_int64) < sizeof(long)) {
-            return PyInt_FromLong((long) value);
-        } else if (sizeof(npy_int64) <= sizeof(unsigned long)) {
-            return PyLong_FromUnsignedLong((unsigned long) value);
-#ifdef HAVE_LONG_LONG
-        } else if (sizeof(npy_int64) <= sizeof(unsigned PY_LONG_LONG)) {
-            return PyLong_FromUnsignedLongLong((unsigned PY_LONG_LONG) value);
-#endif
-        }
-    } else {
-        if (sizeof(npy_int64) <= sizeof(long)) {
-            return PyInt_FromLong((long) value);
-#ifdef HAVE_LONG_LONG
-        } else if (sizeof(npy_int64) <= sizeof(PY_LONG_LONG)) {
-            return PyLong_FromLongLong((PY_LONG_LONG) value);
-#endif
-        }
-    }
-    {
-        int one = 1; int little = (int)*(unsigned char *)&one;
-        unsigned char *bytes = (unsigned char *)&value;
-        return _PyLong_FromByteArray(bytes, sizeof(npy_int64),
-                                     little, !is_unsigned);
-    }
-}
-
-/* CIntToPy */
-  static CYTHON_INLINE PyObject* __Pyx_PyInt_From_npy_int8(npy_int8 value) {
-#ifdef __Pyx_HAS_GCC_DIAGNOSTIC
-#pragma GCC diagnostic push
-#pragma GCC diagnostic ignored "-Wconversion"
-#endif
-    const npy_int8 neg_one = (npy_int8) -1, const_zero = (npy_int8) 0;
-#ifdef __Pyx_HAS_GCC_DIAGNOSTIC
-#pragma GCC diagnostic pop
-#endif
-    const int is_unsigned = neg_one > const_zero;
-    if (is_unsigned) {
-        if (sizeof(npy_int8) < sizeof(long)) {
-            return PyInt_FromLong((long) value);
-        } else if (sizeof(npy_int8) <= sizeof(unsigned long)) {
-            return PyLong_FromUnsignedLong((unsigned long) value);
-#ifdef HAVE_LONG_LONG
-        } else if (sizeof(npy_int8) <= sizeof(unsigned PY_LONG_LONG)) {
-            return PyLong_FromUnsignedLongLong((unsigned PY_LONG_LONG) value);
-#endif
-        }
-    } else {
-        if (sizeof(npy_int8) <= sizeof(long)) {
-            return PyInt_FromLong((long) value);
-#ifdef HAVE_LONG_LONG
-        } else if (sizeof(npy_int8) <= sizeof(PY_LONG_LONG)) {
-            return PyLong_FromLongLong((PY_LONG_LONG) value);
-#endif
-        }
-    }
-    {
-        int one = 1; int little = (int)*(unsigned char *)&one;
-        unsigned char *bytes = (unsigned char *)&value;
-        return _PyLong_FromByteArray(bytes, sizeof(npy_int8),
-                                     little, !is_unsigned);
-    }
-}
-
 /* CIntFromPy */
   static CYTHON_INLINE long __Pyx_PyInt_As_long(PyObject *x) {
 #ifdef __Pyx_HAS_GCC_DIAGNOSTIC
 #pragma GCC diagnostic push
 #pragma GCC diagnostic ignored "-Wconversion"
 #endif
     const long neg_one = (long) -1, const_zero = (long) 0;
@@ -23392,15 +22760,15 @@
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
@@ -23664,15 +23032,15 @@
                         } else if (8 * sizeof(char) >= 4 * PyLong_SHIFT) {
                             return (char) (((((((((char)digits[3]) << PyLong_SHIFT) | (char)digits[2]) << PyLong_SHIFT) | (char)digits[1]) << PyLong_SHIFT) | (char)digits[0]));
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
```


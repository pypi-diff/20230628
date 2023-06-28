# Comparing `tmp/wavelet-buffer-0.6.0.tar.gz` & `tmp/wavelet-buffer-0.7.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "wavelet-buffer-0.6.0.tar", last modified: Wed Apr  5 15:36:41 2023, max compression
+gzip compressed data, was "wavelet-buffer-0.7.0.tar", last modified: Wed Jun 28 13:03:12 2023, max compression
```

## Comparing `wavelet-buffer-0.6.0.tar` & `wavelet-buffer-0.7.0.tar`

### file list

```diff
@@ -1,76 +1,81 @@
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-04-05 15:36:41.596051 wavelet-buffer-0.6.0/
--rw-r--r--   0 runner    (1001) docker     (122)      360 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/AUTHORS.md
--rw-r--r--   0 runner    (1001) docker     (122)     5710 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/CHANGELOG.md
--rw-r--r--   0 runner    (1001) docker     (122)     5597 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/CMakeLists.txt
--rw-r--r--   0 runner    (1001) docker     (122)    16725 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/LICENSE
--rw-r--r--   0 runner    (1001) docker     (122)     4723 2023-04-05 15:36:41.596051 wavelet-buffer-0.6.0/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (122)     3682 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/README.md
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-04-05 15:36:41.588050 wavelet-buffer-0.6.0/cmake/
--rw-r--r--   0 runner    (1001) docker     (122)      226 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/cmake/wavelet_buffer-config.cmake.in
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-04-05 15:36:41.588050 wavelet-buffer-0.6.0/conan/
--rw-r--r--   0 runner    (1001) docker     (122)     2577 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/conan/conanfile.py
--rw-r--r--   0 runner    (1001) docker     (122)      509 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/pyproject.toml
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-04-05 15:36:41.588050 wavelet-buffer-0.6.0/python/
--rw-r--r--   0 runner    (1001) docker     (122)     1254 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/python/CMakeLists.txt
--rw-r--r--   0 runner    (1001) docker     (122)     1065 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/python/README.md
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-04-05 15:36:41.592050 wavelet-buffer-0.6.0/python/src/
--rw-r--r--   0 runner    (1001) docker     (122)     4581 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/python/src/blaze_utils.cc
--rw-r--r--   0 runner    (1001) docker     (122)     1119 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/python/src/blaze_utils.h
--rw-r--r--   0 runner    (1001) docker     (122)      776 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/python/src/denoise.cc
--rw-r--r--   0 runner    (1001) docker     (122)      231 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/python/src/denoise.h
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-04-05 15:36:41.592050 wavelet-buffer-0.6.0/python/src/img/
--rw-r--r--   0 runner    (1001) docker     (122)     2170 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/python/src/img/codecs.cc
--rw-r--r--   0 runner    (1001) docker     (122)      282 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/python/src/img/codecs.h
--rw-r--r--   0 runner    (1001) docker     (122)     4547 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/python/src/img/wavelet_image.cc
--rw-r--r--   0 runner    (1001) docker     (122)      251 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/python/src/img/wavelet_image.h
--rw-r--r--   0 runner    (1001) docker     (122)      455 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/python/src/main.cc
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-04-05 15:36:41.592050 wavelet-buffer-0.6.0/python/src/wavelet_buffer/
--rw-r--r--   0 runner    (1001) docker     (122)      216 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/python/src/wavelet_buffer/__init__.py
--rw-r--r--   0 runner    (1001) docker     (122)      817 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/python/src/wavelet_buffer/denoise.py
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-04-05 15:36:41.592050 wavelet-buffer-0.6.0/python/src/wavelet_buffer/img/
--rw-r--r--   0 runner    (1001) docker     (122)      134 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/python/src/wavelet_buffer/img/__init__.py
--rw-r--r--   0 runner    (1001) docker     (122)     2804 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/python/src/wavelet_buffer/img/codecs.py
--rw-r--r--   0 runner    (1001) docker     (122)     4181 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/python/src/wavelet_buffer/img/wavelet_image.py
--rw-r--r--   0 runner    (1001) docker     (122)      739 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/python/src/wavelet_buffer/utils.py
--rw-r--r--   0 runner    (1001) docker     (122)     4115 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/python/src/wavelet_buffer/wavelet_buffer.py
--rw-r--r--   0 runner    (1001) docker     (122)     1178 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/python/src/wavelet_buffer/wavelet_buffer_view.py
--rw-r--r--   0 runner    (1001) docker     (122)     7806 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/python/src/wavelet_buffer.cc
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-04-05 15:36:41.592050 wavelet-buffer-0.6.0/python/src/wavelet_buffer.egg-info/
--rw-r--r--   0 runner    (1001) docker     (122)     4723 2023-04-05 15:36:41.000000 wavelet-buffer-0.6.0/python/src/wavelet_buffer.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (122)     1823 2023-04-05 15:36:41.000000 wavelet-buffer-0.6.0/python/src/wavelet_buffer.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (122)        1 2023-04-05 15:36:41.000000 wavelet-buffer-0.6.0/python/src/wavelet_buffer.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (122)       15 2023-04-05 15:36:41.000000 wavelet-buffer-0.6.0/python/src/wavelet_buffer.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (122)      243 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/python/src/wavelet_buffer.h
--rw-r--r--   0 runner    (1001) docker     (122)     2971 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/python/src/wavelet_buffer_view.cc
--rw-r--r--   0 runner    (1001) docker     (122)      262 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/python/src/wavelet_buffer_view.h
--rw-r--r--   0 runner    (1001) docker     (122)      569 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/python/src/wavelet_buffer_view_proxy.h
--rw-r--r--   0 runner    (1001) docker     (122)     2208 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/python/src/wavelet_parameters.cc
--rw-r--r--   0 runner    (1001) docker     (122)      563 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/python/src/wavelet_parameters.h
--rw-r--r--   0 runner    (1001) docker     (122)       38 2023-04-05 15:36:41.596051 wavelet-buffer-0.6.0/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (122)     2398 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-04-05 15:36:41.592050 wavelet-buffer-0.6.0/sources/
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-04-05 15:36:41.596051 wavelet-buffer-0.6.0/sources/img/
--rw-r--r--   0 runner    (1001) docker     (122)     4377 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/sources/img/color_space.cc
--rw-r--r--   0 runner    (1001) docker     (122)     7628 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/sources/img/jpeg_codecs.cc
--rw-r--r--   0 runner    (1001) docker     (122)     5651 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/sources/img/wavelet_image.cc
--rw-r--r--   0 runner    (1001) docker     (122)     5251 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/sources/padding.cc
--rw-r--r--   0 runner    (1001) docker     (122)    13312 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/sources/wavelet.cc
--rw-r--r--   0 runner    (1001) docker     (122)    13385 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/sources/wavelet_buffer.cc
--rw-r--r--   0 runner    (1001) docker     (122)     6457 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/sources/wavelet_buffer_serializer.cc
--rw-r--r--   0 runner    (1001) docker     (122)     3110 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/sources/wavelet_buffer_view.cc
--rw-r--r--   0 runner    (1001) docker     (122)    17354 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/sources/wavelet_utils.cc
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-04-05 15:36:41.596051 wavelet-buffer-0.6.0/wavelet_buffer/
--rw-r--r--   0 runner    (1001) docker     (122)     5933 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/wavelet_buffer/denoise_algorithms.h
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-04-05 15:36:41.596051 wavelet-buffer-0.6.0/wavelet_buffer/img/
--rw-r--r--   0 runner    (1001) docker     (122)     1403 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/wavelet_buffer/img/color_space.h
--rw-r--r--   0 runner    (1001) docker     (122)     1333 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/wavelet_buffer/img/image_codec.h
--rw-r--r--   0 runner    (1001) docker     (122)     2589 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/wavelet_buffer/img/jpeg_codecs.h
--rw-r--r--   0 runner    (1001) docker     (122)     3351 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/wavelet_buffer/img/wavelet_image.h
--rw-r--r--   0 runner    (1001) docker     (122)     1828 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/wavelet_buffer/padding.h
--rw-r--r--   0 runner    (1001) docker     (122)      488 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/wavelet_buffer/primitives.h
--rw-r--r--   0 runner    (1001) docker     (122)     2494 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/wavelet_buffer/wavelet.h
--rw-r--r--   0 runner    (1001) docker     (122)     5692 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/wavelet_buffer/wavelet_buffer.h
--rw-r--r--   0 runner    (1001) docker     (122)     2644 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/wavelet_buffer/wavelet_buffer_serializer.h
--rw-r--r--   0 runner    (1001) docker     (122)     1617 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/wavelet_buffer/wavelet_buffer_view.h
--rw-r--r--   0 runner    (1001) docker     (122)     4279 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/wavelet_buffer/wavelet_parameters.h
--rw-r--r--   0 runner    (1001) docker     (122)     5196 2023-04-05 15:36:12.000000 wavelet-buffer-0.6.0/wavelet_buffer/wavelet_utils.h
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 13:03:12.418997 wavelet-buffer-0.7.0/
+-rw-r--r--   0 runner    (1001) docker     (122)      360 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/AUTHORS.md
+-rw-r--r--   0 runner    (1001) docker     (122)     5948 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/CHANGELOG.md
+-rw-r--r--   0 runner    (1001) docker     (122)     6077 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/CMakeLists.txt
+-rw-r--r--   0 runner    (1001) docker     (122)    16725 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (122)     4730 2023-06-28 13:03:12.418997 wavelet-buffer-0.7.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (122)     3689 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/README.md
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 13:03:12.410997 wavelet-buffer-0.7.0/cmake/
+-rw-r--r--   0 runner    (1001) docker     (122)      226 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/cmake/wavelet_buffer-config.cmake.in
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 13:03:12.410997 wavelet-buffer-0.7.0/conan/
+-rw-r--r--   0 runner    (1001) docker     (122)     2515 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/conan/conanfile.py
+-rw-r--r--   0 runner    (1001) docker     (122)      509 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/pyproject.toml
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 13:03:12.410997 wavelet-buffer-0.7.0/python/
+-rw-r--r--   0 runner    (1001) docker     (122)     1254 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/python/CMakeLists.txt
+-rw-r--r--   0 runner    (1001) docker     (122)     1065 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/python/README.md
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 13:03:12.410997 wavelet-buffer-0.7.0/python/src/
+-rw-r--r--   0 runner    (1001) docker     (122)     4581 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/python/src/blaze_utils.cc
+-rw-r--r--   0 runner    (1001) docker     (122)     1119 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/python/src/blaze_utils.h
+-rw-r--r--   0 runner    (1001) docker     (122)      776 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/python/src/denoise.cc
+-rw-r--r--   0 runner    (1001) docker     (122)      231 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/python/src/denoise.h
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 13:03:12.414997 wavelet-buffer-0.7.0/python/src/img/
+-rw-r--r--   0 runner    (1001) docker     (122)     2170 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/python/src/img/codecs.cc
+-rw-r--r--   0 runner    (1001) docker     (122)      282 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/python/src/img/codecs.h
+-rw-r--r--   0 runner    (1001) docker     (122)     4547 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/python/src/img/wavelet_image.cc
+-rw-r--r--   0 runner    (1001) docker     (122)      251 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/python/src/img/wavelet_image.h
+-rw-r--r--   0 runner    (1001) docker     (122)      455 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/python/src/main.cc
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 13:03:12.414997 wavelet-buffer-0.7.0/python/src/wavelet_buffer/
+-rw-r--r--   0 runner    (1001) docker     (122)      216 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/python/src/wavelet_buffer/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (122)      817 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/python/src/wavelet_buffer/denoise.py
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 13:03:12.414997 wavelet-buffer-0.7.0/python/src/wavelet_buffer/img/
+-rw-r--r--   0 runner    (1001) docker     (122)      134 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/python/src/wavelet_buffer/img/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (122)     2804 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/python/src/wavelet_buffer/img/codecs.py
+-rw-r--r--   0 runner    (1001) docker     (122)     4181 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/python/src/wavelet_buffer/img/wavelet_image.py
+-rw-r--r--   0 runner    (1001) docker     (122)      739 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/python/src/wavelet_buffer/utils.py
+-rw-r--r--   0 runner    (1001) docker     (122)     4115 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/python/src/wavelet_buffer/wavelet_buffer.py
+-rw-r--r--   0 runner    (1001) docker     (122)     1178 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/python/src/wavelet_buffer/wavelet_buffer_view.py
+-rw-r--r--   0 runner    (1001) docker     (122)     7806 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/python/src/wavelet_buffer.cc
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 13:03:12.414997 wavelet-buffer-0.7.0/python/src/wavelet_buffer.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (122)     4730 2023-06-28 13:03:12.000000 wavelet-buffer-0.7.0/python/src/wavelet_buffer.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (122)     1965 2023-06-28 13:03:12.000000 wavelet-buffer-0.7.0/python/src/wavelet_buffer.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (122)        1 2023-06-28 13:03:12.000000 wavelet-buffer-0.7.0/python/src/wavelet_buffer.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (122)       15 2023-06-28 13:03:12.000000 wavelet-buffer-0.7.0/python/src/wavelet_buffer.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (122)      243 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/python/src/wavelet_buffer.h
+-rw-r--r--   0 runner    (1001) docker     (122)     2971 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/python/src/wavelet_buffer_view.cc
+-rw-r--r--   0 runner    (1001) docker     (122)      262 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/python/src/wavelet_buffer_view.h
+-rw-r--r--   0 runner    (1001) docker     (122)      569 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/python/src/wavelet_buffer_view_proxy.h
+-rw-r--r--   0 runner    (1001) docker     (122)     2208 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/python/src/wavelet_parameters.cc
+-rw-r--r--   0 runner    (1001) docker     (122)      563 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/python/src/wavelet_parameters.h
+-rw-r--r--   0 runner    (1001) docker     (122)       38 2023-06-28 13:03:12.418997 wavelet-buffer-0.7.0/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (122)     2398 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 13:03:12.414997 wavelet-buffer-0.7.0/sources/
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 13:03:12.414997 wavelet-buffer-0.7.0/sources/img/
+-rw-r--r--   0 runner    (1001) docker     (122)     4377 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/sources/img/color_space.cc
+-rw-r--r--   0 runner    (1001) docker     (122)     7628 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/sources/img/jpeg_codecs.cc
+-rw-r--r--   0 runner    (1001) docker     (122)     5651 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/sources/img/wavelet_image.cc
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 13:03:12.414997 wavelet-buffer-0.7.0/sources/internal/
+-rw-r--r--   0 runner    (1001) docker     (122)     5261 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/sources/internal/matrix_compressor.cc
+-rw-r--r--   0 runner    (1001) docker     (122)     2383 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/sources/internal/matrix_compressor.h
+-rw-r--r--   0 runner    (1001) docker     (122)    37747 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/sources/internal/sf_compressor.cc
+-rw-r--r--   0 runner    (1001) docker     (122)     1361 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/sources/internal/sf_compressor.h
+-rw-r--r--   0 runner    (1001) docker     (122)     5251 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/sources/padding.cc
+-rw-r--r--   0 runner    (1001) docker     (122)    13312 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/sources/wavelet.cc
+-rw-r--r--   0 runner    (1001) docker     (122)    13388 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/sources/wavelet_buffer.cc
+-rw-r--r--   0 runner    (1001) docker     (122)     6572 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/sources/wavelet_buffer_serializer.cc
+-rw-r--r--   0 runner    (1001) docker     (122)     3110 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/sources/wavelet_buffer_view.cc
+-rw-r--r--   0 runner    (1001) docker     (122)    17354 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/sources/wavelet_utils.cc
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 13:03:12.418997 wavelet-buffer-0.7.0/wavelet_buffer/
+-rw-r--r--   0 runner    (1001) docker     (122)     5933 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/wavelet_buffer/denoise_algorithms.h
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 13:03:12.418997 wavelet-buffer-0.7.0/wavelet_buffer/img/
+-rw-r--r--   0 runner    (1001) docker     (122)     1403 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/wavelet_buffer/img/color_space.h
+-rw-r--r--   0 runner    (1001) docker     (122)     1333 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/wavelet_buffer/img/image_codec.h
+-rw-r--r--   0 runner    (1001) docker     (122)     2589 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/wavelet_buffer/img/jpeg_codecs.h
+-rw-r--r--   0 runner    (1001) docker     (122)     3351 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/wavelet_buffer/img/wavelet_image.h
+-rw-r--r--   0 runner    (1001) docker     (122)     1828 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/wavelet_buffer/padding.h
+-rw-r--r--   0 runner    (1001) docker     (122)      488 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/wavelet_buffer/primitives.h
+-rw-r--r--   0 runner    (1001) docker     (122)     2494 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/wavelet_buffer/wavelet.h
+-rw-r--r--   0 runner    (1001) docker     (122)     5692 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/wavelet_buffer/wavelet_buffer.h
+-rw-r--r--   0 runner    (1001) docker     (122)     2644 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/wavelet_buffer/wavelet_buffer_serializer.h
+-rw-r--r--   0 runner    (1001) docker     (122)     1617 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/wavelet_buffer/wavelet_buffer_view.h
+-rw-r--r--   0 runner    (1001) docker     (122)     4279 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/wavelet_buffer/wavelet_parameters.h
+-rw-r--r--   0 runner    (1001) docker     (122)     5196 2023-06-28 13:02:43.000000 wavelet-buffer-0.7.0/wavelet_buffer/wavelet_utils.h
```

### Comparing `wavelet-buffer-0.6.0/CHANGELOG.md` & `wavelet-buffer-0.7.0/CHANGELOG.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,12 +1,22 @@
 [keep a changelog](https://keepachangelog.com/)
 
 ## Unreleased
 
-### 0.6.0 - 2023-04-05
+## 0.7.0 - 2023-06-28
+
+### Changed
+
+* DRIFT-683: Consolidated dependencies, [PR-60](https://github.com/panda-official/WaveletBuffer/pull/60)
+
+## Fixed
+
+* Python 3.11 build, [PR-60](https://github.com/panda-official/WaveletBuffer/pull/60)
+
+## 0.6.0 - 2023-04-05
 
 **IMPORTANT**: We have changed serialization of subbands. The current version of the serialization is 3. We support
 de-serialization of version 2 and 3. However, the serialization of version 2 is not supported anymore and to parse
 archives you have to update to version 0.6.0.
 
 ### Added
```

### Comparing `wavelet-buffer-0.6.0/CMakeLists.txt` & `wavelet-buffer-0.7.0/CMakeLists.txt`

 * *Files 24% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 cmake_minimum_required(VERSION 3.16)
 
 if(${CMAKE_VERSION} VERSION_GREATER_EQUAL "3.24")
     cmake_policy(SET CMP0135 NEW)
 endif()
 
-project(wavelet_buffer VERSION 0.6.0)
+project(wavelet_buffer VERSION 0.7.0)
 
 option(WB_BUILD_TESTS "Enable unit tests" OFF)
 option(WB_BUILD_EXAMPLES "Enable examples" OFF)
 option(WB_BUILD_BENCHMARKS "Enable benchmarks" OFF)
 
 # Conan
 if(CONAN_EXPORTED)
@@ -35,15 +35,15 @@
 
     include(${CMAKE_BINARY_DIR}/conan.cmake)
 
     conan_cmake_configure(REQUIRES
             blaze/3.8
             libjpeg-turbo/2.1.3
             cimg/3.0.2
-	        catch2/3.2.1
+            catch2/3.2.1
             OPTIONS
             cimg:enable_fftw=False
             cimg:enable_jpeg=False # To avoid conflict with libjpeg-turbo
             cimg:enable_openexr=False
             cimg:enable_png=False
             cimg:enable_tiff=False
             cimg:enable_ffmpeg=False
@@ -59,57 +59,64 @@
 endif()
 
 find_package(blaze REQUIRED)
 find_package(libjpeg-turbo REQUIRED)
 find_package(cimg REQUIRED)
 find_package(Catch2 REQUIRED)
 
-# Dependencies
-include(FetchContent)
-
-# SFCompressor
-fetchcontent_declare(
-    SFCompressor
-    GIT_REPOSITORY https://github.com/panda-official/SfCompressor.git
-    GIT_TAG drift-507
-)
-
-fetchcontent_makeavailable(SFCompressor)
-
-# MatrixCompressor
-fetchcontent_declare(
-    matrix_compressor
-    GIT_REPOSITORY https://github.com/panda-official/MatrixCompressor
-    GIT_TAG v0.2.0
-)
-
-fetchcontent_makeavailable(matrix_compressor)
-
 # Create wb target
 set(WB_TARGET_NAME ${PROJECT_NAME})
 add_library(
     ${WB_TARGET_NAME}
     sources/wavelet_buffer.cc
     sources/wavelet_buffer_serializer.cc
     sources/wavelet_utils.cc
     sources/wavelet_buffer_view.cc
     sources/padding.cc
     sources/wavelet.cc
     sources/img/wavelet_image.cc
     sources/img/color_space.cc
     sources/img/jpeg_codecs.cc
+    # Internal
+    sources/internal/sf_compressor.cc
+    sources/internal/matrix_compressor.cc
 )
 
+include(FetchContent)
+
+fetchcontent_declare(
+    streamvbyte
+    URL https://github.com/lemire/streamvbyte/archive/refs/tags/v1.0.0.zip
+    URL_HASH MD5=3d1a01cfb704947fa6498944082aeed1
+)
+
+fetchcontent_declare(
+    fpzip
+    URL https://github.com/LLNL/fpzip/releases/download/1.3.0/fpzip-1.3.0.zip
+    URL_HASH MD5=933ed7628de406a24fe2de61c8c3356c
+)
+
+fetchcontent_makeavailable(streamvbyte)
+
+fetchcontent_getproperties(fpzip)
+
+if(NOT fpzip_POPULATED)
+    fetchcontent_populate(fpzip)
+    # Make subproject to use 'BUILD_SHARED_LIBS=ON' setting.
+    set(BUILD_SHARED_LIBS OFF CACHE INTERNAL "Build SHARED libraries")
+    add_subdirectory(${fpzip_SOURCE_DIR} ${fpzip_BINARY_DIR})
+endif()
+
 # Add alias
 add_library(${WB_TARGET_NAME}::${WB_TARGET_NAME} ALIAS ${WB_TARGET_NAME})
 
 # Set fPIC
 set_target_properties(${WB_TARGET_NAME} PROPERTIES POSITION_INDEPENDENT_CODE ON)
-set_target_properties(sf_compressor PROPERTIES POSITION_INDEPENDENT_CODE ON)
-set_target_properties(matrix_compressor PROPERTIES POSITION_INDEPENDENT_CODE ON)
+set_target_properties(streamvbyte PROPERTIES POSITION_INDEPENDENT_CODE ON)
+set_target_properties(fpzip PROPERTIES POSITION_INDEPENDENT_CODE ON)
 
 # Turn off parallelization in blaze
 target_compile_definitions(
     ${WB_TARGET_NAME}
     PUBLIC BLAZE_USE_SHARED_MEMORY_PARALLELIZATION=0
 )
 
@@ -127,20 +134,26 @@
 target_include_directories(
     ${WB_TARGET_NAME}
     PUBLIC
         $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}>
         $<INSTALL_INTERFACE:${CMAKE_INSTALL_INCLUDEDIR}>
 )
 
+target_include_directories(
+    ${WB_TARGET_NAME}
+    PRIVATE $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}>/sources
+)
+
 # Link dependencies
-target_link_libraries(${WB_TARGET_NAME} sf_compressor)
-target_link_libraries(${WB_TARGET_NAME} matrix_compressor::matrix_compressor)
-target_link_libraries(${WB_TARGET_NAME} blaze::blaze)
-target_link_libraries(${WB_TARGET_NAME} libjpeg-turbo::libjpeg-turbo)
-target_link_libraries(${WB_TARGET_NAME} cimg::cimg)
+target_link_libraries(${WB_TARGET_NAME} PRIVATE streamvbyte)
+target_link_libraries(${WB_TARGET_NAME} PRIVATE fpzip)
+target_link_libraries(${WB_TARGET_NAME} PRIVATE libjpeg-turbo::libjpeg-turbo)
+target_link_libraries(${WB_TARGET_NAME} PRIVATE cimg::cimg)
+
+target_link_libraries(${WB_TARGET_NAME} PUBLIC blaze::blaze)
 
 # Catch2 installation
 if(WB_BUILD_TESTS OR WB_BUILD_BENCHMARKS)
     include(CTest)
     include(Catch)
 endif()
 
@@ -162,15 +175,15 @@
     add_subdirectory(examples)
 endif()
 
 # Install rules
 include(GNUInstallDirs)
 
 # Create package targets file
-install(TARGETS ${WB_TARGET_NAME} EXPORT ${WB_TARGET_NAME}-target)
+install(TARGETS ${WB_TARGET_NAME} streamvbyte EXPORT ${WB_TARGET_NAME}-target)
 install(
     EXPORT ${WB_TARGET_NAME}-target
     FILE ${WB_TARGET_NAME}-targets.cmake
     NAMESPACE ${WB_TARGET_NAME}::
     DESTINATION ${CMAKE_INSTALL_DATAROOTDIR}/${PROJECT_NAME}/cmake
 )
```

### Comparing `wavelet-buffer-0.6.0/LICENSE` & `wavelet-buffer-0.7.0/LICENSE`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/PKG-INFO` & `wavelet-buffer-0.7.0/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: wavelet-buffer
-Version: 0.6.0
+Version: 0.7.0
 Summary: A universal C++ compression library based on wavelet transformation
 Home-page: https://github.com/panda-official/WaveletBuffer
 Author: PANDA, GmbH
 Author-email: info@panda.technology
 License: MPL-2.0
 Classifier: Development Status :: 4 - Beta
 Classifier: Intended Audience :: Science/Research
@@ -29,25 +29,25 @@
 
 # WaveletBuffer
 A universal  C++ compression library based on wavelet transformation
 
 ## Features
 
 - Written in Modern C++
-- One-side wavelet decomposition for vectors and matrixes
+- One-side wavelet decomposition for vectors and matrices
 - 5 Daubechies Wavelets DB1-DB5
 - Different denoising algorithms
 - Fast and efficient compression with [MatrixCompressor](https://github.com/panda-official/MatrixCompressor)
 - Cross-platform
 
 ## Requirements
 
 * CMake >= 3.16
 * C++20 compiler
-* conan >= 1.56
+* conan >= 1.56, < 2.0
 
 ## Bindings
 
 * [Python](python/README.md)
 
 
 ## Usage Example
```

### Comparing `wavelet-buffer-0.6.0/README.md` & `wavelet-buffer-0.7.0/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -3,25 +3,25 @@
 
 # WaveletBuffer
 A universal  C++ compression library based on wavelet transformation
 
 ## Features
 
 - Written in Modern C++
-- One-side wavelet decomposition for vectors and matrixes
+- One-side wavelet decomposition for vectors and matrices
 - 5 Daubechies Wavelets DB1-DB5
 - Different denoising algorithms
 - Fast and efficient compression with [MatrixCompressor](https://github.com/panda-official/MatrixCompressor)
 - Cross-platform
 
 ## Requirements
 
 * CMake >= 3.16
 * C++20 compiler
-* conan >= 1.56
+* conan >= 1.56, < 2.0
 
 ## Bindings
 
 * [Python](python/README.md)
 
 
 ## Usage Example
```

### Comparing `wavelet-buffer-0.6.0/conan/conanfile.py` & `wavelet-buffer-0.7.0/conan/conanfile.py`

 * *Files 2% similar despite different names*

```diff
@@ -6,15 +6,15 @@
 from conan.tools.cmake import CMake, CMakeToolchain, cmake_layout
 
 required_conan_version = ">=1.58"
 
 
 class WaveletBufferConan(ConanFile):
     name = "wavelet_buffer"
-    version = "0.6.0"
+    version = "0.7.0"
     license = "MPL-2.0"
     author = "PANDA GmbH"
     description = "An universal C++ compression library based on wavelet transformation"
     url = "https://github.com/panda-official/WaveletBuffer"
     requires = "blaze/3.8", "libjpeg-turbo/2.1.4", "cimg/3.0.2", "catch2/3.2.1"
     default_options = {
         "cimg:enable_fftw": False,
@@ -80,12 +80,10 @@
     def package(self):
         cmake = CMake(self)
         cmake.install()
 
     def package_info(self):
         self.cpp_info.libs = [
             "wavelet_buffer",
-            "sf_compressor",
-            "matrix_compressor",
             "fpzip",
             "streamvbyte",
         ]
```

### Comparing `wavelet-buffer-0.6.0/python/CMakeLists.txt` & `wavelet-buffer-0.7.0/python/CMakeLists.txt`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/python/README.md` & `wavelet-buffer-0.7.0/python/README.md`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/python/src/blaze_utils.cc` & `wavelet-buffer-0.7.0/python/src/blaze_utils.cc`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/python/src/blaze_utils.h` & `wavelet-buffer-0.7.0/python/src/blaze_utils.h`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/python/src/denoise.cc` & `wavelet-buffer-0.7.0/python/src/denoise.cc`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/python/src/img/codecs.cc` & `wavelet-buffer-0.7.0/python/src/img/codecs.cc`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/python/src/img/wavelet_image.cc` & `wavelet-buffer-0.7.0/python/src/img/wavelet_image.cc`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/python/src/wavelet_buffer/denoise.py` & `wavelet-buffer-0.7.0/python/src/wavelet_buffer/denoise.py`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/python/src/wavelet_buffer/img/codecs.py` & `wavelet-buffer-0.7.0/python/src/wavelet_buffer/img/codecs.py`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/python/src/wavelet_buffer/img/wavelet_image.py` & `wavelet-buffer-0.7.0/python/src/wavelet_buffer/img/wavelet_image.py`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/python/src/wavelet_buffer/utils.py` & `wavelet-buffer-0.7.0/python/src/wavelet_buffer/utils.py`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/python/src/wavelet_buffer/wavelet_buffer.py` & `wavelet-buffer-0.7.0/python/src/wavelet_buffer/wavelet_buffer.py`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/python/src/wavelet_buffer/wavelet_buffer_view.py` & `wavelet-buffer-0.7.0/python/src/wavelet_buffer/wavelet_buffer_view.py`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/python/src/wavelet_buffer.cc` & `wavelet-buffer-0.7.0/python/src/wavelet_buffer.cc`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/python/src/wavelet_buffer.egg-info/PKG-INFO` & `wavelet-buffer-0.7.0/python/src/wavelet_buffer.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: wavelet-buffer
-Version: 0.6.0
+Version: 0.7.0
 Summary: A universal C++ compression library based on wavelet transformation
 Home-page: https://github.com/panda-official/WaveletBuffer
 Author: PANDA, GmbH
 Author-email: info@panda.technology
 License: MPL-2.0
 Classifier: Development Status :: 4 - Beta
 Classifier: Intended Audience :: Science/Research
@@ -29,25 +29,25 @@
 
 # WaveletBuffer
 A universal  C++ compression library based on wavelet transformation
 
 ## Features
 
 - Written in Modern C++
-- One-side wavelet decomposition for vectors and matrixes
+- One-side wavelet decomposition for vectors and matrices
 - 5 Daubechies Wavelets DB1-DB5
 - Different denoising algorithms
 - Fast and efficient compression with [MatrixCompressor](https://github.com/panda-official/MatrixCompressor)
 - Cross-platform
 
 ## Requirements
 
 * CMake >= 3.16
 * C++20 compiler
-* conan >= 1.56
+* conan >= 1.56, < 2.0
 
 ## Bindings
 
 * [Python](python/README.md)
 
 
 ## Usage Example
```

### Comparing `wavelet-buffer-0.6.0/python/src/wavelet_buffer.egg-info/SOURCES.txt` & `wavelet-buffer-0.7.0/python/src/wavelet_buffer.egg-info/SOURCES.txt`

 * *Files 10% similar despite different names*

```diff
@@ -42,14 +42,18 @@
 sources/wavelet_buffer.cc
 sources/wavelet_buffer_serializer.cc
 sources/wavelet_buffer_view.cc
 sources/wavelet_utils.cc
 sources/img/color_space.cc
 sources/img/jpeg_codecs.cc
 sources/img/wavelet_image.cc
+sources/internal/matrix_compressor.cc
+sources/internal/matrix_compressor.h
+sources/internal/sf_compressor.cc
+sources/internal/sf_compressor.h
 wavelet_buffer/denoise_algorithms.h
 wavelet_buffer/padding.h
 wavelet_buffer/primitives.h
 wavelet_buffer/wavelet.h
 wavelet_buffer/wavelet_buffer.h
 wavelet_buffer/wavelet_buffer_serializer.h
 wavelet_buffer/wavelet_buffer_view.h
```

### Comparing `wavelet-buffer-0.6.0/python/src/wavelet_buffer_view.cc` & `wavelet-buffer-0.7.0/python/src/wavelet_buffer_view.cc`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/python/src/wavelet_buffer_view_proxy.h` & `wavelet-buffer-0.7.0/python/src/wavelet_buffer_view_proxy.h`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/python/src/wavelet_parameters.cc` & `wavelet-buffer-0.7.0/python/src/wavelet_parameters.cc`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/python/src/wavelet_parameters.h` & `wavelet-buffer-0.7.0/python/src/wavelet_parameters.h`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/setup.py` & `wavelet-buffer-0.7.0/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -9,15 +9,15 @@
 
 from pathlib import Path
 
 this_directory = Path(__file__).parent
 long_description = (this_directory / "README.md").read_text()
 
 MAJOR_VERSION = 0
-MINOR_VERSION = 6
+MINOR_VERSION = 7
 PATCH_VERSION = 0
 
 PACKAGE_NAME = "wavelet-buffer"
 
 VERSION_SUFFIX = os.getenv("VERSION_SUFFIX")
```

### Comparing `wavelet-buffer-0.6.0/sources/img/color_space.cc` & `wavelet-buffer-0.7.0/sources/img/color_space.cc`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/sources/img/jpeg_codecs.cc` & `wavelet-buffer-0.7.0/sources/img/jpeg_codecs.cc`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/sources/img/wavelet_image.cc` & `wavelet-buffer-0.7.0/sources/img/wavelet_image.cc`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/sources/padding.cc` & `wavelet-buffer-0.7.0/sources/padding.cc`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/sources/wavelet.cc` & `wavelet-buffer-0.7.0/sources/wavelet.cc`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/sources/wavelet_buffer.cc` & `wavelet-buffer-0.7.0/sources/wavelet_buffer.cc`

 * *Files 1% similar despite different names*

```diff
@@ -365,15 +365,15 @@
 }
 
 bool WaveletBuffer::operator==(const WaveletBuffer& rhs) const {
   return *impl_ == *(rhs.impl_);
 }
 
 bool WaveletBuffer::operator!=(const WaveletBuffer& rhs) const {
-  return rhs != *this;
+  return !(rhs == *this);
 }
 
 WaveletBuffer& WaveletBuffer::operator=(const WaveletBuffer& buffer) {
   impl_ = std::make_unique<Impl>(*buffer.impl_);
   return *this;
 }
```

### Comparing `wavelet-buffer-0.6.0/sources/wavelet_buffer_serializer.cc` & `wavelet-buffer-0.7.0/sources/wavelet_buffer_serializer.cc`

 * *Files 5% similar despite different names*

```diff
@@ -1,16 +1,15 @@
-// Copyright 2021-2022 PANDA GmbH
+// Copyright 2021-2023 PANDA GmbH
 
 #include "wavelet_buffer/wavelet_buffer_serializer.h"
 
-#include <matrix_compressor/matrix_compressor.h>
-#include <sf_compressor/sf_compressor.h>
-
 #include <iostream>
 
+#include "internal/matrix_compressor.h"
+#include "internal/sf_compressor.h"
 #include "wavelet_buffer/wavelet_buffer.h"
 
 namespace drift {
 /**
  * We need to allocate data for SfComprressor depending on subband size
  * @param signal_shape
  * @param sub_number number of suuband, if 0 it is the original signal
@@ -61,14 +60,17 @@
 [[nodiscard]] bool WaveletBufferSerializerLegacy::Serialize(
     const WaveletBuffer& buffer, std::string* blob, uint8_t sf_compression) {
   return false;
 }
 
 [[nodiscard]] std::unique_ptr<WaveletBuffer> WaveletBufferSerializer::Parse(
     const std::string& blob) {
+  using wavelet::internal::ArchivedMatrix;
+  using wavelet::internal::BlazeCompressor;
+
   try {
     /* Create archive */
     std::istringstream ss(blob);
     blaze::Archive archive(ss);
 
     /* Load version and parameters */
     uint8_t serialization_version;
@@ -79,38 +81,39 @@
     auto buffer = std::make_unique<WaveletBuffer>(params);
     /* Load subbands */
     for (auto& signal : buffer->decompositions()) {
       for (auto& subband : signal) {
         if (sf_compression == 0) {
           archive >> subband;
         } else {
-          matrix_compressor::ArchivedMatrix data;
+          ArchivedMatrix data;
           data.is_valid = true;
           archive >> data.nonzero >> data.rows_number >> data.cols_number;
 
           blaze::DynamicVector<uint8_t> indexes, values;
           archive >> indexes >> values;
           data.indexes = std::vector<uint8_t>(indexes.begin(), indexes.end());
           data.values = std::vector<uint8_t>(values.begin(), values.end());
 
-          subband = matrix_compressor::BlazeCompressor().Decompress(data);
+          subband = BlazeCompressor().Decompress(data);
         }
       }
     }
     return buffer;
   } catch (std::exception& e) {
     std::cerr << "Failed parse data: " << e.what() << std::endl;
     return nullptr;
   }
 }
 
 [[nodiscard]] bool WaveletBufferSerializer::Serialize(
     const WaveletBuffer& buffer, std::string* blob, uint8_t sf_compression) {
-  std::stringstream ss;
+  using wavelet::internal::BlazeCompressor;
 
+  std::stringstream ss;
   try {
     blaze::Archive arch(ss);
 
     sf_compression = std::min<uint8_t>(31, sf_compression);
     if (buffer.IsEmpty()) {
       sf_compression = 0;
     }
@@ -120,16 +123,15 @@
 
     /* Serialize subbands */
     for (const auto& signal : buffer.decompositions()) {
       for (const auto& subband : signal) {
         if (sf_compression == 0) {
           arch << subband;
         } else {
-          auto data = matrix_compressor::BlazeCompressor().Compress(
-              subband, 33 - sf_compression);
+          auto data = BlazeCompressor().Compress(subband, 33 - sf_compression);
           if (!data.is_valid) {
             return false;
           }
 
           /* Serialize compressed data */
           arch << data.nonzero;
           arch << data.rows_number;
@@ -160,31 +162,32 @@
   const auto divisor =
       is_one_dim ? std::pow(2, sub_number) : std::pow(4, sub_number / 3);
   return static_cast<size_t>(static_cast<double>(max_size) / divisor * 1.5);
 }
 
 bool ParseCompressedSubbands(blaze::Archive<std::istringstream>* archive,
                              WaveletBuffer* buffer) {
+  using drift::wavelet::internal::SfCompressor;
+
   /* Iterate through sabbands */
   for (int n = 0; n < buffer->parameters().signal_number; ++n) {
     for (int s = 0; s < buffer->decompositions()[n].size(); ++s) {
       blaze::DynamicVector<uint8_t> compressed_subband;
       *archive >> compressed_subband;
 
       std::vector<uint8_t> data(compressed_subband.begin(),
                                 compressed_subband.end());
 
       size_t expected_points =
           GetMemorySizeForSfCompressor(buffer->parameters().signal_shape, s);
-      sf::SfCompressor compressor(
-          expected_points);  // TODO(Alexey Timin): Should
-                             // reallocate memory because of a
-                             // bug in SfCompressor
+      SfCompressor compressor(expected_points);  // TODO(Alexey Timin): Should
+                                                 // reallocate memory because of
+                                                 // a bug in SfCompressor
 
-      sf::SfCompressor::OriginalData out_data;
+      SfCompressor::OriginalData out_data;
       if (!compressor.Decompress(data, &out_data)) {
         return false;
       }
 
       auto subband = Subband(out_data.rows, out_data.columns, 0);
       for (int i = 0; i < out_data.indexes.size(); ++i) {
         subband(out_data.indexes[i] / out_data.columns,
```

### Comparing `wavelet-buffer-0.6.0/sources/wavelet_buffer_view.cc` & `wavelet-buffer-0.7.0/sources/wavelet_buffer_view.cc`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/sources/wavelet_utils.cc` & `wavelet-buffer-0.7.0/sources/wavelet_utils.cc`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/wavelet_buffer/denoise_algorithms.h` & `wavelet-buffer-0.7.0/wavelet_buffer/denoise_algorithms.h`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/wavelet_buffer/img/color_space.h` & `wavelet-buffer-0.7.0/wavelet_buffer/img/color_space.h`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/wavelet_buffer/img/image_codec.h` & `wavelet-buffer-0.7.0/wavelet_buffer/img/image_codec.h`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/wavelet_buffer/img/jpeg_codecs.h` & `wavelet-buffer-0.7.0/wavelet_buffer/img/jpeg_codecs.h`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/wavelet_buffer/img/wavelet_image.h` & `wavelet-buffer-0.7.0/wavelet_buffer/img/wavelet_image.h`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/wavelet_buffer/padding.h` & `wavelet-buffer-0.7.0/wavelet_buffer/padding.h`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/wavelet_buffer/wavelet.h` & `wavelet-buffer-0.7.0/wavelet_buffer/wavelet.h`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/wavelet_buffer/wavelet_buffer.h` & `wavelet-buffer-0.7.0/wavelet_buffer/wavelet_buffer.h`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/wavelet_buffer/wavelet_buffer_serializer.h` & `wavelet-buffer-0.7.0/wavelet_buffer/wavelet_buffer_serializer.h`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/wavelet_buffer/wavelet_buffer_view.h` & `wavelet-buffer-0.7.0/wavelet_buffer/wavelet_buffer_view.h`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/wavelet_buffer/wavelet_parameters.h` & `wavelet-buffer-0.7.0/wavelet_buffer/wavelet_parameters.h`

 * *Files identical despite different names*

### Comparing `wavelet-buffer-0.6.0/wavelet_buffer/wavelet_utils.h` & `wavelet-buffer-0.7.0/wavelet_buffer/wavelet_utils.h`

 * *Files identical despite different names*


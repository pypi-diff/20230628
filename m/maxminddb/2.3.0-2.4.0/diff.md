# Comparing `tmp/maxminddb-2.3.0.tar.gz` & `tmp/maxminddb-2.4.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "maxminddb-2.3.0.tar", last modified: Tue May  9 20:11:13 2023, max compression
+gzip compressed data, was "maxminddb-2.4.0.tar", last modified: Wed Jun 28 15:58:29 2023, max compression
```

## Comparing `maxminddb-2.3.0.tar` & `maxminddb-2.4.0.tar`

### file list

```diff
@@ -1,106 +1,106 @@
-drwxr-xr-x   0 greg      (1000) greg      (1000)        0 2023-05-09 20:11:13.279801 maxminddb-2.3.0/
--rw-r--r--   0 greg      (1000) greg      (1000)     8792 2023-05-09 20:03:29.000000 maxminddb-2.3.0/HISTORY.rst
--rw-r--r--   0 greg      (1000) greg      (1000)    11358 2019-01-09 22:21:10.000000 maxminddb-2.3.0/LICENSE
--rw-r--r--   0 greg      (1000) greg      (1000)      141 2021-09-21 15:14:38.000000 maxminddb-2.3.0/MANIFEST.in
--rw-r--r--   0 greg      (1000) greg      (1000)     5055 2023-05-09 20:11:13.279801 maxminddb-2.3.0/PKG-INFO
--rw-r--r--   0 greg      (1000) greg      (1000)     3852 2023-01-17 17:58:57.000000 maxminddb-2.3.0/README.rst
-drwxr-xr-x   0 greg      (1000) greg      (1000)        0 2023-05-09 20:11:13.263800 maxminddb-2.3.0/docs/
-drwxr-xr-x   0 greg      (1000) greg      (1000)        0 2023-05-09 20:11:13.267800 maxminddb-2.3.0/docs/html/
--rw-r--r--   0 greg      (1000) greg      (1000)      230 2023-05-09 20:10:58.000000 maxminddb-2.3.0/docs/html/.buildinfo
-drwxr-xr-x   0 greg      (1000) greg      (1000)        0 2023-05-09 20:11:13.267800 maxminddb-2.3.0/docs/html/_sources/
--rw-r--r--   0 greg      (1000) greg      (1000)      762 2021-09-21 15:14:38.000000 maxminddb-2.3.0/docs/html/_sources/index.rst.txt
-drwxr-xr-x   0 greg      (1000) greg      (1000)        0 2023-05-09 20:11:13.271801 maxminddb-2.3.0/docs/html/_static/
--rw-r--r--   0 greg      (1000) greg      (1000)    14692 2023-05-09 20:10:58.000000 maxminddb-2.3.0/docs/html/_static/basic.css
--rw-r--r--   0 greg      (1000) greg      (1000)      107 2022-03-28 19:26:41.000000 maxminddb-2.3.0/docs/html/_static/contents.png
--rw-r--r--   0 greg      (1000) greg      (1000)    10766 2022-03-28 19:26:41.000000 maxminddb-2.3.0/docs/html/_static/doctools.js
--rw-r--r--   0 greg      (1000) greg      (1000)      422 2023-05-09 20:10:58.000000 maxminddb-2.3.0/docs/html/_static/documentation_options.js
--rw-r--r--   0 greg      (1000) greg      (1000)      286 2022-03-28 19:26:41.000000 maxminddb-2.3.0/docs/html/_static/file.png
--rw-r--r--   0 greg      (1000) greg      (1000)   287630 2022-03-28 19:26:41.000000 maxminddb-2.3.0/docs/html/_static/jquery-3.5.1.js
--rw-r--r--   0 greg      (1000) greg      (1000)    89476 2022-03-28 19:26:41.000000 maxminddb-2.3.0/docs/html/_static/jquery.js
--rw-r--r--   0 greg      (1000) greg      (1000)    10854 2023-05-09 20:10:58.000000 maxminddb-2.3.0/docs/html/_static/language_data.js
--rw-r--r--   0 greg      (1000) greg      (1000)       90 2022-03-28 19:26:41.000000 maxminddb-2.3.0/docs/html/_static/minus.png
--rw-r--r--   0 greg      (1000) greg      (1000)      120 2022-03-28 19:26:41.000000 maxminddb-2.3.0/docs/html/_static/navigation.png
--rw-r--r--   0 greg      (1000) greg      (1000)       90 2022-03-28 19:26:41.000000 maxminddb-2.3.0/docs/html/_static/plus.png
--rw-r--r--   0 greg      (1000) greg      (1000)     4846 2023-05-09 20:10:58.000000 maxminddb-2.3.0/docs/html/_static/pygments.css
--rw-r--r--   0 greg      (1000) greg      (1000)    16634 2022-03-28 19:26:41.000000 maxminddb-2.3.0/docs/html/_static/searchtools.js
--rw-r--r--   0 greg      (1000) greg      (1000)     6236 2023-05-09 20:10:58.000000 maxminddb-2.3.0/docs/html/_static/sphinxdoc.css
--rw-r--r--   0 greg      (1000) greg      (1000)    68420 2022-03-28 19:26:41.000000 maxminddb-2.3.0/docs/html/_static/underscore-1.13.1.js
--rw-r--r--   0 greg      (1000) greg      (1000)    19530 2022-03-28 19:26:41.000000 maxminddb-2.3.0/docs/html/_static/underscore.js
--rw-r--r--   0 greg      (1000) greg      (1000)     9401 2023-05-09 20:10:58.000000 maxminddb-2.3.0/docs/html/genindex.html
--rw-r--r--   0 greg      (1000) greg      (1000)    49839 2023-05-09 20:10:58.000000 maxminddb-2.3.0/docs/html/index.html
--rw-r--r--   0 greg      (1000) greg      (1000)      522 2023-05-09 20:10:58.000000 maxminddb-2.3.0/docs/html/objects.inv
--rw-r--r--   0 greg      (1000) greg      (1000)     4016 2023-05-09 20:10:58.000000 maxminddb-2.3.0/docs/html/py-modindex.html
--rw-r--r--   0 greg      (1000) greg      (1000)     3367 2023-05-09 20:10:58.000000 maxminddb-2.3.0/docs/html/search.html
--rw-r--r--   0 greg      (1000) greg      (1000)     3916 2023-05-09 20:10:58.000000 maxminddb-2.3.0/docs/html/searchindex.js
-drwxr-xr-x   0 greg      (1000) greg      (1000)        0 2023-05-09 20:11:13.271801 maxminddb-2.3.0/extension/
--rw-r--r--   0 greg      (1000) greg      (1000)    23421 2023-01-17 17:58:57.000000 maxminddb-2.3.0/extension/maxminddb.c
-drwxr-xr-x   0 greg      (1000) greg      (1000)        0 2023-05-09 20:11:13.271801 maxminddb-2.3.0/maxminddb/
--rw-r--r--   0 greg      (1000) greg      (1000)     2557 2023-05-09 20:09:31.000000 maxminddb-2.3.0/maxminddb/__init__.py
--rw-r--r--   0 greg      (1000) greg      (1000)      122 2019-01-09 22:21:10.000000 maxminddb-2.3.0/maxminddb/const.py
--rw-r--r--   0 greg      (1000) greg      (1000)     7005 2022-07-09 23:43:59.000000 maxminddb-2.3.0/maxminddb/decoder.py
--rw-r--r--   0 greg      (1000) greg      (1000)      226 2019-01-09 22:21:10.000000 maxminddb-2.3.0/maxminddb/errors.py
--rw-r--r--   0 greg      (1000) greg      (1000)     1447 2021-09-24 17:10:54.000000 maxminddb-2.3.0/maxminddb/extension.pyi
--rw-r--r--   0 greg      (1000) greg      (1000)     2153 2021-06-01 17:36:58.000000 maxminddb-2.3.0/maxminddb/file.py
--rw-r--r--   0 greg      (1000) greg      (1000)        0 2020-07-28 17:36:22.000000 maxminddb-2.3.0/maxminddb/py.typed
--rw-r--r--   0 greg      (1000) greg      (1000)    11002 2022-06-09 15:23:43.000000 maxminddb-2.3.0/maxminddb/reader.py
--rw-r--r--   0 greg      (1000) greg      (1000)      558 2020-07-10 20:06:17.000000 maxminddb-2.3.0/maxminddb/types.py
-drwxr-xr-x   0 greg      (1000) greg      (1000)        0 2023-05-09 20:11:13.271801 maxminddb-2.3.0/maxminddb.egg-info/
--rw-r--r--   0 greg      (1000) greg      (1000)     5055 2023-05-09 20:11:13.000000 maxminddb-2.3.0/maxminddb.egg-info/PKG-INFO
--rw-r--r--   0 greg      (1000) greg      (1000)     3511 2023-05-09 20:11:13.000000 maxminddb-2.3.0/maxminddb.egg-info/SOURCES.txt
--rw-r--r--   0 greg      (1000) greg      (1000)        1 2023-05-09 20:11:13.000000 maxminddb-2.3.0/maxminddb.egg-info/dependency_links.txt
--rw-r--r--   0 greg      (1000) greg      (1000)       10 2023-05-09 20:11:13.000000 maxminddb-2.3.0/maxminddb.egg-info/top_level.txt
--rw-r--r--   0 greg      (1000) greg      (1000)      169 2023-05-09 19:53:37.000000 maxminddb-2.3.0/pyproject.toml
--rw-r--r--   0 greg      (1000) greg      (1000)      703 2023-05-09 20:11:13.279801 maxminddb-2.3.0/setup.cfg
--rw-r--r--   0 greg      (1000) greg      (1000)     5192 2023-01-17 17:58:57.000000 maxminddb-2.3.0/setup.py
-drwxr-xr-x   0 greg      (1000) greg      (1000)        0 2023-05-09 20:11:13.271801 maxminddb-2.3.0/tests/
-drwxr-xr-x   0 greg      (1000) greg      (1000)        0 2023-05-09 20:11:13.263800 maxminddb-2.3.0/tests/data/
-drwxr-xr-x   0 greg      (1000) greg      (1000)        0 2023-05-09 20:11:13.263800 maxminddb-2.3.0/tests/data/bad-data/
-drwxr-xr-x   0 greg      (1000) greg      (1000)        0 2023-05-09 20:11:13.271801 maxminddb-2.3.0/tests/data/bad-data/libmaxminddb/
--rw-r--r--   0 greg      (1000) greg      (1000)      412 2019-09-20 16:04:16.000000 maxminddb-2.3.0/tests/data/bad-data/libmaxminddb/libmaxminddb-offset-integer-overflow.mmdb
-drwxr-xr-x   0 greg      (1000) greg      (1000)        0 2023-05-09 20:11:13.275801 maxminddb-2.3.0/tests/data/bad-data/maxminddb-golang/
--rw-r--r--   0 greg      (1000) greg      (1000)     2731 2019-09-20 16:04:16.000000 maxminddb-2.3.0/tests/data/bad-data/maxminddb-golang/cyclic-data-structure.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)       32 2019-09-20 16:04:16.000000 maxminddb-2.3.0/tests/data/bad-data/maxminddb-golang/invalid-bytes-length.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)      327 2019-09-20 16:04:16.000000 maxminddb-2.3.0/tests/data/bad-data/maxminddb-golang/invalid-data-record-offset.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)     2731 2019-09-20 16:04:16.000000 maxminddb-2.3.0/tests/data/bad-data/maxminddb-golang/invalid-map-key-length.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)      187 2019-09-20 16:04:16.000000 maxminddb-2.3.0/tests/data/bad-data/maxminddb-golang/invalid-string-length.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)       16 2019-09-20 16:04:16.000000 maxminddb-2.3.0/tests/data/bad-data/maxminddb-golang/metadata-is-an-uint128.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)     2333 2019-09-20 16:04:16.000000 maxminddb-2.3.0/tests/data/bad-data/maxminddb-golang/unexpected-bytes.mmdb
-drwxr-xr-x   0 greg      (1000) greg      (1000)        0 2023-05-09 20:11:13.275801 maxminddb-2.3.0/tests/data/bad-data/maxminddb-python/
--rw-r--r--   0 greg      (1000) greg      (1000)     3535 2020-05-04 15:42:59.000000 maxminddb-2.3.0/tests/data/bad-data/maxminddb-python/bad-unicode-in-map-key.mmdb
-drwxr-xr-x   0 greg      (1000) greg      (1000)        0 2023-05-09 20:11:13.279801 maxminddb-2.3.0/tests/data/test-data/
--rw-r--r--   0 greg      (1000) greg      (1000)     4382 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/GeoIP2-Anonymous-IP-Test.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)    20620 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/GeoIP2-City-Test-Broken-Double-Format.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)    21016 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/GeoIP2-City-Test-Invalid-Node-Count.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)    20996 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/GeoIP2-City-Test.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)     3779 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/GeoIP2-Connection-Type-Test.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)    19394 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/GeoIP2-Country-Test.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)     3065 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/GeoIP2-DensityIncome-Test.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)     6326 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/GeoIP2-Domain-Test.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)     7983 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/GeoIP2-Enterprise-Test.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)    76417 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/GeoIP2-ISP-Test.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)    16438 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/GeoIP2-Precision-Enterprise-Test.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)     9750 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/GeoIP2-Static-IP-Score-Test.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)     4818 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/GeoIP2-User-Count-Test.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)    12358 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/GeoLite2-ASN-Test.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)    20809 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/GeoLite2-City-Test.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)    17952 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/GeoLite2-Country-Test.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)      618 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-no-ipv4-search-tree.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)     1341 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-string-value-entries.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)     1289 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-test-broken-pointers-24.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)     1298 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-test-broken-search-tree-24.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)     3191 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-test-decoder.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)     1298 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-test-ipv4-24.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)     1462 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-test-ipv4-28.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)     1626 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-test-ipv4-32.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)     2806 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-test-ipv6-24.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)     3222 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-test-ipv6-28.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)     3638 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-test-ipv6-32.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)     2258 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-test-metadata-pointers.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)     3066 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-test-mixed-24.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)     3511 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-test-mixed-28.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)     3956 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-test-mixed-32.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)     3802 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-test-nested.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)     1737 2021-06-01 17:37:15.000000 maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-test-pointer-decoder.mmdb
--rw-r--r--   0 greg      (1000) greg      (1000)       59 2019-01-09 22:21:44.000000 maxminddb-2.3.0/tests/data/test-data/maps-with-pointers.raw
--rw-r--r--   0 greg      (1000) greg      (1000)     7819 2023-05-09 19:53:37.000000 maxminddb-2.3.0/tests/decoder_test.py
--rw-r--r--   0 greg      (1000) greg      (1000)    21598 2021-09-24 17:10:57.000000 maxminddb-2.3.0/tests/reader_test.py
+drwxr-xr-x   0 greg      (1000) greg      (1000)        0 2023-06-28 15:58:29.827378 maxminddb-2.4.0/
+-rw-r--r--   0 greg      (1000) greg      (1000)     9125 2023-06-28 15:51:14.000000 maxminddb-2.4.0/HISTORY.rst
+-rw-r--r--   0 greg      (1000) greg      (1000)    11358 2019-01-09 22:21:10.000000 maxminddb-2.4.0/LICENSE
+-rw-r--r--   0 greg      (1000) greg      (1000)      141 2021-09-21 15:14:38.000000 maxminddb-2.4.0/MANIFEST.in
+-rw-r--r--   0 greg      (1000) greg      (1000)     5035 2023-06-28 15:58:29.827378 maxminddb-2.4.0/PKG-INFO
+-rw-r--r--   0 greg      (1000) greg      (1000)     3852 2023-01-17 17:58:57.000000 maxminddb-2.4.0/README.rst
+drwxr-xr-x   0 greg      (1000) greg      (1000)        0 2023-06-28 15:58:29.811378 maxminddb-2.4.0/docs/
+drwxr-xr-x   0 greg      (1000) greg      (1000)        0 2023-06-28 15:58:29.815378 maxminddb-2.4.0/docs/html/
+-rw-r--r--   0 greg      (1000) greg      (1000)      230 2023-05-09 20:10:58.000000 maxminddb-2.4.0/docs/html/.buildinfo
+drwxr-xr-x   0 greg      (1000) greg      (1000)        0 2023-06-28 15:58:29.815378 maxminddb-2.4.0/docs/html/_sources/
+-rw-r--r--   0 greg      (1000) greg      (1000)      762 2021-09-21 15:14:38.000000 maxminddb-2.4.0/docs/html/_sources/index.rst.txt
+drwxr-xr-x   0 greg      (1000) greg      (1000)        0 2023-06-28 15:58:29.815378 maxminddb-2.4.0/docs/html/_static/
+-rw-r--r--   0 greg      (1000) greg      (1000)    14692 2023-05-09 20:10:58.000000 maxminddb-2.4.0/docs/html/_static/basic.css
+-rw-r--r--   0 greg      (1000) greg      (1000)      107 2022-03-28 19:26:41.000000 maxminddb-2.4.0/docs/html/_static/contents.png
+-rw-r--r--   0 greg      (1000) greg      (1000)    10766 2022-03-28 19:26:41.000000 maxminddb-2.4.0/docs/html/_static/doctools.js
+-rw-r--r--   0 greg      (1000) greg      (1000)      422 2023-05-09 20:10:58.000000 maxminddb-2.4.0/docs/html/_static/documentation_options.js
+-rw-r--r--   0 greg      (1000) greg      (1000)      286 2022-03-28 19:26:41.000000 maxminddb-2.4.0/docs/html/_static/file.png
+-rw-r--r--   0 greg      (1000) greg      (1000)   287630 2022-03-28 19:26:41.000000 maxminddb-2.4.0/docs/html/_static/jquery-3.5.1.js
+-rw-r--r--   0 greg      (1000) greg      (1000)    89476 2022-03-28 19:26:41.000000 maxminddb-2.4.0/docs/html/_static/jquery.js
+-rw-r--r--   0 greg      (1000) greg      (1000)    10854 2023-05-09 20:10:58.000000 maxminddb-2.4.0/docs/html/_static/language_data.js
+-rw-r--r--   0 greg      (1000) greg      (1000)       90 2022-03-28 19:26:41.000000 maxminddb-2.4.0/docs/html/_static/minus.png
+-rw-r--r--   0 greg      (1000) greg      (1000)      120 2022-03-28 19:26:41.000000 maxminddb-2.4.0/docs/html/_static/navigation.png
+-rw-r--r--   0 greg      (1000) greg      (1000)       90 2022-03-28 19:26:41.000000 maxminddb-2.4.0/docs/html/_static/plus.png
+-rw-r--r--   0 greg      (1000) greg      (1000)     4846 2023-05-09 20:10:58.000000 maxminddb-2.4.0/docs/html/_static/pygments.css
+-rw-r--r--   0 greg      (1000) greg      (1000)    16634 2022-03-28 19:26:41.000000 maxminddb-2.4.0/docs/html/_static/searchtools.js
+-rw-r--r--   0 greg      (1000) greg      (1000)     6236 2023-05-09 20:10:58.000000 maxminddb-2.4.0/docs/html/_static/sphinxdoc.css
+-rw-r--r--   0 greg      (1000) greg      (1000)    68420 2022-03-28 19:26:41.000000 maxminddb-2.4.0/docs/html/_static/underscore-1.13.1.js
+-rw-r--r--   0 greg      (1000) greg      (1000)    19530 2022-03-28 19:26:41.000000 maxminddb-2.4.0/docs/html/_static/underscore.js
+-rw-r--r--   0 greg      (1000) greg      (1000)     9401 2023-05-09 20:10:58.000000 maxminddb-2.4.0/docs/html/genindex.html
+-rw-r--r--   0 greg      (1000) greg      (1000)    49839 2023-05-09 20:10:58.000000 maxminddb-2.4.0/docs/html/index.html
+-rw-r--r--   0 greg      (1000) greg      (1000)      522 2023-05-09 20:10:58.000000 maxminddb-2.4.0/docs/html/objects.inv
+-rw-r--r--   0 greg      (1000) greg      (1000)     4016 2023-05-09 20:10:58.000000 maxminddb-2.4.0/docs/html/py-modindex.html
+-rw-r--r--   0 greg      (1000) greg      (1000)     3367 2023-05-09 20:10:58.000000 maxminddb-2.4.0/docs/html/search.html
+-rw-r--r--   0 greg      (1000) greg      (1000)     3916 2023-05-09 20:10:58.000000 maxminddb-2.4.0/docs/html/searchindex.js
+drwxr-xr-x   0 greg      (1000) greg      (1000)        0 2023-06-28 15:58:29.815378 maxminddb-2.4.0/extension/
+-rw-r--r--   0 greg      (1000) greg      (1000)    23452 2023-06-28 15:38:05.000000 maxminddb-2.4.0/extension/maxminddb.c
+drwxr-xr-x   0 greg      (1000) greg      (1000)        0 2023-06-28 15:58:29.819378 maxminddb-2.4.0/maxminddb/
+-rw-r--r--   0 greg      (1000) greg      (1000)     2557 2023-06-28 15:56:17.000000 maxminddb-2.4.0/maxminddb/__init__.py
+-rw-r--r--   0 greg      (1000) greg      (1000)      122 2019-01-09 22:21:10.000000 maxminddb-2.4.0/maxminddb/const.py
+-rw-r--r--   0 greg      (1000) greg      (1000)     7005 2022-07-09 23:43:59.000000 maxminddb-2.4.0/maxminddb/decoder.py
+-rw-r--r--   0 greg      (1000) greg      (1000)      226 2019-01-09 22:21:10.000000 maxminddb-2.4.0/maxminddb/errors.py
+-rw-r--r--   0 greg      (1000) greg      (1000)     1447 2021-09-24 17:10:54.000000 maxminddb-2.4.0/maxminddb/extension.pyi
+-rw-r--r--   0 greg      (1000) greg      (1000)     2153 2021-06-01 17:36:58.000000 maxminddb-2.4.0/maxminddb/file.py
+-rw-r--r--   0 greg      (1000) greg      (1000)        0 2020-07-28 17:36:22.000000 maxminddb-2.4.0/maxminddb/py.typed
+-rw-r--r--   0 greg      (1000) greg      (1000)    11002 2022-06-09 15:23:43.000000 maxminddb-2.4.0/maxminddb/reader.py
+-rw-r--r--   0 greg      (1000) greg      (1000)      558 2020-07-10 20:06:17.000000 maxminddb-2.4.0/maxminddb/types.py
+drwxr-xr-x   0 greg      (1000) greg      (1000)        0 2023-06-28 15:58:29.819378 maxminddb-2.4.0/maxminddb.egg-info/
+-rw-r--r--   0 greg      (1000) greg      (1000)     5035 2023-06-28 15:58:29.000000 maxminddb-2.4.0/maxminddb.egg-info/PKG-INFO
+-rw-r--r--   0 greg      (1000) greg      (1000)     3511 2023-06-28 15:58:29.000000 maxminddb-2.4.0/maxminddb.egg-info/SOURCES.txt
+-rw-r--r--   0 greg      (1000) greg      (1000)        1 2023-06-28 15:58:29.000000 maxminddb-2.4.0/maxminddb.egg-info/dependency_links.txt
+-rw-r--r--   0 greg      (1000) greg      (1000)       10 2023-06-28 15:58:29.000000 maxminddb-2.4.0/maxminddb.egg-info/top_level.txt
+-rw-r--r--   0 greg      (1000) greg      (1000)      169 2023-05-09 19:53:37.000000 maxminddb-2.4.0/pyproject.toml
+-rw-r--r--   0 greg      (1000) greg      (1000)     1839 2023-06-28 15:58:29.827378 maxminddb-2.4.0/setup.cfg
+-rw-r--r--   0 greg      (1000) greg      (1000)     3470 2023-06-28 15:38:05.000000 maxminddb-2.4.0/setup.py
+drwxr-xr-x   0 greg      (1000) greg      (1000)        0 2023-06-28 15:58:29.819378 maxminddb-2.4.0/tests/
+drwxr-xr-x   0 greg      (1000) greg      (1000)        0 2023-06-28 15:58:29.811378 maxminddb-2.4.0/tests/data/
+drwxr-xr-x   0 greg      (1000) greg      (1000)        0 2023-06-28 15:58:29.811378 maxminddb-2.4.0/tests/data/bad-data/
+drwxr-xr-x   0 greg      (1000) greg      (1000)        0 2023-06-28 15:58:29.819378 maxminddb-2.4.0/tests/data/bad-data/libmaxminddb/
+-rw-r--r--   0 greg      (1000) greg      (1000)      412 2019-09-20 16:04:16.000000 maxminddb-2.4.0/tests/data/bad-data/libmaxminddb/libmaxminddb-offset-integer-overflow.mmdb
+drwxr-xr-x   0 greg      (1000) greg      (1000)        0 2023-06-28 15:58:29.819378 maxminddb-2.4.0/tests/data/bad-data/maxminddb-golang/
+-rw-r--r--   0 greg      (1000) greg      (1000)     2731 2019-09-20 16:04:16.000000 maxminddb-2.4.0/tests/data/bad-data/maxminddb-golang/cyclic-data-structure.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)       32 2019-09-20 16:04:16.000000 maxminddb-2.4.0/tests/data/bad-data/maxminddb-golang/invalid-bytes-length.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)      327 2019-09-20 16:04:16.000000 maxminddb-2.4.0/tests/data/bad-data/maxminddb-golang/invalid-data-record-offset.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)     2731 2019-09-20 16:04:16.000000 maxminddb-2.4.0/tests/data/bad-data/maxminddb-golang/invalid-map-key-length.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)      187 2019-09-20 16:04:16.000000 maxminddb-2.4.0/tests/data/bad-data/maxminddb-golang/invalid-string-length.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)       16 2019-09-20 16:04:16.000000 maxminddb-2.4.0/tests/data/bad-data/maxminddb-golang/metadata-is-an-uint128.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)     2333 2019-09-20 16:04:16.000000 maxminddb-2.4.0/tests/data/bad-data/maxminddb-golang/unexpected-bytes.mmdb
+drwxr-xr-x   0 greg      (1000) greg      (1000)        0 2023-06-28 15:58:29.819378 maxminddb-2.4.0/tests/data/bad-data/maxminddb-python/
+-rw-r--r--   0 greg      (1000) greg      (1000)     3535 2020-05-04 15:42:59.000000 maxminddb-2.4.0/tests/data/bad-data/maxminddb-python/bad-unicode-in-map-key.mmdb
+drwxr-xr-x   0 greg      (1000) greg      (1000)        0 2023-06-28 15:58:29.827378 maxminddb-2.4.0/tests/data/test-data/
+-rw-r--r--   0 greg      (1000) greg      (1000)     4382 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/GeoIP2-Anonymous-IP-Test.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)    20620 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/GeoIP2-City-Test-Broken-Double-Format.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)    21016 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/GeoIP2-City-Test-Invalid-Node-Count.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)    20996 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/GeoIP2-City-Test.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)     3779 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/GeoIP2-Connection-Type-Test.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)    19394 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/GeoIP2-Country-Test.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)     3065 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/GeoIP2-DensityIncome-Test.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)     6326 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/GeoIP2-Domain-Test.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)     7983 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/GeoIP2-Enterprise-Test.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)    76417 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/GeoIP2-ISP-Test.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)    16438 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/GeoIP2-Precision-Enterprise-Test.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)     9750 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/GeoIP2-Static-IP-Score-Test.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)     4818 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/GeoIP2-User-Count-Test.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)    12358 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/GeoLite2-ASN-Test.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)    20809 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/GeoLite2-City-Test.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)    17952 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/GeoLite2-Country-Test.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)      618 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-no-ipv4-search-tree.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)     1341 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-string-value-entries.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)     1289 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-test-broken-pointers-24.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)     1298 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-test-broken-search-tree-24.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)     3191 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-test-decoder.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)     1298 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-test-ipv4-24.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)     1462 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-test-ipv4-28.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)     1626 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-test-ipv4-32.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)     2806 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-test-ipv6-24.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)     3222 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-test-ipv6-28.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)     3638 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-test-ipv6-32.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)     2258 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-test-metadata-pointers.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)     3066 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-test-mixed-24.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)     3511 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-test-mixed-28.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)     3956 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-test-mixed-32.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)     3802 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-test-nested.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)     1737 2021-06-01 17:37:15.000000 maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-test-pointer-decoder.mmdb
+-rw-r--r--   0 greg      (1000) greg      (1000)       59 2019-01-09 22:21:44.000000 maxminddb-2.4.0/tests/data/test-data/maps-with-pointers.raw
+-rw-r--r--   0 greg      (1000) greg      (1000)     7819 2023-05-09 19:53:37.000000 maxminddb-2.4.0/tests/decoder_test.py
+-rw-r--r--   0 greg      (1000) greg      (1000)    21598 2021-09-24 17:10:57.000000 maxminddb-2.4.0/tests/reader_test.py
```

### Comparing `maxminddb-2.3.0/HISTORY.rst` & `maxminddb-2.4.0/HISTORY.rst`

 * *Files 2% similar despite different names*

```diff
@@ -1,12 +1,21 @@
 .. :changelog:
 
 History
 -------
 
+2.4.0 (2023-06-28)
+++++++++++++++++++
+
+* Package metadata was migrated from ``setup.py`` to ``setup.cfg``. GitHub
+  #113.
+* The C extension now decrements the reference count on an object
+  containing the database filename after its use in an error message rather
+  than before. Pull request by Lumír 'Frenzy' Balhar. GitHub #114.
+
 2.3.0 (2023-05-09)
 ++++++++++++++++++
 
 * IMPORTANT: Python 3.7 or greater is required. If you are using an older
   version, please use an earlier release.
 * ``distutils`` is no longer used for building the C extension.
 * Missing ``Py_INCREF`` was added to module initialization for the C
```

### Comparing `maxminddb-2.3.0/LICENSE` & `maxminddb-2.4.0/LICENSE`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/PKG-INFO` & `maxminddb-2.4.0/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,19 +1,18 @@
 Metadata-Version: 2.1
 Name: maxminddb
-Version: 2.3.0
+Version: 2.4.0
 Summary: Reader for the MaxMind DB format
 Home-page: http://www.maxmind.com/
 Author: Gregory Oschwald
 Author-email: goschwald@maxmind.com
 License: Apache License, Version 2.0
 Project-URL: Documentation, https://maxminddb.readthedocs.org/
 Project-URL: Source Code, https://github.com/maxmind/MaxMind-DB-Reader-python
 Project-URL: Issue Tracker, https://github.com/maxmind/MaxMind-DB-Reader-python/issues
-Platform: UNKNOWN
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Environment :: Web Environment
 Classifier: Intended Audience :: Developers
 Classifier: Intended Audience :: System Administrators
 Classifier: License :: OSI Approved :: Apache Software License
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.7
@@ -136,9 +135,7 @@
 
 Please report all issues with this code using the `GitHub issue tracker
 <https://github.com/maxmind/MaxMind-DB-Reader-python/issues>`_
 
 If you are having an issue with a MaxMind service that is not specific to this
 API, please contact `MaxMind support <https://www.maxmind.com/en/support>`_ for
 assistance.
-
-
```

### Comparing `maxminddb-2.3.0/README.rst` & `maxminddb-2.4.0/README.rst`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/docs/html/_sources/index.rst.txt` & `maxminddb-2.4.0/docs/html/_sources/index.rst.txt`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/docs/html/_static/basic.css` & `maxminddb-2.4.0/docs/html/_static/basic.css`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/docs/html/_static/doctools.js` & `maxminddb-2.4.0/docs/html/_static/doctools.js`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/docs/html/_static/jquery-3.5.1.js` & `maxminddb-2.4.0/docs/html/_static/jquery-3.5.1.js`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/docs/html/_static/jquery.js` & `maxminddb-2.4.0/docs/html/_static/jquery.js`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/docs/html/_static/language_data.js` & `maxminddb-2.4.0/docs/html/_static/language_data.js`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/docs/html/_static/pygments.css` & `maxminddb-2.4.0/docs/html/_static/pygments.css`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/docs/html/_static/searchtools.js` & `maxminddb-2.4.0/docs/html/_static/searchtools.js`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/docs/html/_static/sphinxdoc.css` & `maxminddb-2.4.0/docs/html/_static/sphinxdoc.css`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/docs/html/_static/underscore-1.13.1.js` & `maxminddb-2.4.0/docs/html/_static/underscore-1.13.1.js`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/docs/html/_static/underscore.js` & `maxminddb-2.4.0/docs/html/_static/underscore.js`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/docs/html/genindex.html` & `maxminddb-2.4.0/docs/html/genindex.html`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/docs/html/index.html` & `maxminddb-2.4.0/docs/html/index.html`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/docs/html/objects.inv` & `maxminddb-2.4.0/docs/html/objects.inv`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/docs/html/py-modindex.html` & `maxminddb-2.4.0/docs/html/py-modindex.html`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/docs/html/search.html` & `maxminddb-2.4.0/docs/html/search.html`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/docs/html/searchindex.js` & `maxminddb-2.4.0/docs/html/searchindex.js`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/extension/maxminddb.c` & `maxminddb-2.4.0/extension/maxminddb.c`

 * *Files 0% similar despite different names*

```diff
@@ -96,25 +96,27 @@
         Py_XDECREF(filepath);
         free(mmdb);
         PyErr_NoMemory();
         return -1;
     }
 
     int const status = MMDB_open(filename, MMDB_MODE_MMAP, mmdb);
-    Py_XDECREF(filepath);
 
     if (MMDB_SUCCESS != status) {
         free(mmdb);
         PyErr_Format(MaxMindDB_error,
                      "Error opening database file (%s). Is this a valid "
                      "MaxMind DB file?",
                      filename);
+        Py_XDECREF(filepath);
         return -1;
     }
 
+    Py_XDECREF(filepath);
+
     mmdb_obj->mmdb = mmdb;
     mmdb_obj->closed = Py_False;
     return 0;
 }
 
 static PyObject *Reader_get(PyObject *self, PyObject *args) {
     PyObject *record = NULL;
```

### Comparing `maxminddb-2.3.0/maxminddb/__init__.py` & `maxminddb-2.4.0/maxminddb/__init__.py`

 * *Files 8% similar despite different names*

```diff
@@ -77,11 +77,11 @@
     # checking purposes, pretend it is one. (Ideally this would be a subclass
     # of, or share a common parent class with, the Python Reader
     # implementation.)
     return cast(Reader, _extension.Reader(database, mode))
 
 
 __title__ = "maxminddb"
-__version__ = "2.3.0"
+__version__ = "2.4.0"
 __author__ = "Gregory Oschwald"
 __license__ = "Apache License, Version 2.0"
-__copyright__ = "Copyright 2013-2021 MaxMind, Inc."
+__copyright__ = "Copyright 2013-2023 MaxMind, Inc."
```

### Comparing `maxminddb-2.3.0/maxminddb/decoder.py` & `maxminddb-2.4.0/maxminddb/decoder.py`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/maxminddb/extension.pyi` & `maxminddb-2.4.0/maxminddb/extension.pyi`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/maxminddb/file.py` & `maxminddb-2.4.0/maxminddb/file.py`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/maxminddb/reader.py` & `maxminddb-2.4.0/maxminddb/reader.py`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/maxminddb/types.py` & `maxminddb-2.4.0/maxminddb/types.py`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/maxminddb.egg-info/PKG-INFO` & `maxminddb-2.4.0/maxminddb.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,19 +1,18 @@
 Metadata-Version: 2.1
 Name: maxminddb
-Version: 2.3.0
+Version: 2.4.0
 Summary: Reader for the MaxMind DB format
 Home-page: http://www.maxmind.com/
 Author: Gregory Oschwald
 Author-email: goschwald@maxmind.com
 License: Apache License, Version 2.0
 Project-URL: Documentation, https://maxminddb.readthedocs.org/
 Project-URL: Source Code, https://github.com/maxmind/MaxMind-DB-Reader-python
 Project-URL: Issue Tracker, https://github.com/maxmind/MaxMind-DB-Reader-python/issues
-Platform: UNKNOWN
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Environment :: Web Environment
 Classifier: Intended Audience :: Developers
 Classifier: Intended Audience :: System Administrators
 Classifier: License :: OSI Approved :: Apache Software License
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.7
@@ -136,9 +135,7 @@
 
 Please report all issues with this code using the `GitHub issue tracker
 <https://github.com/maxmind/MaxMind-DB-Reader-python/issues>`_
 
 If you are having an issue with a MaxMind service that is not specific to this
 API, please contact `MaxMind support <https://www.maxmind.com/en/support>`_ for
 assistance.
-
-
```

### Comparing `maxminddb-2.3.0/maxminddb.egg-info/SOURCES.txt` & `maxminddb-2.4.0/maxminddb.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/bad-data/maxminddb-golang/cyclic-data-structure.mmdb` & `maxminddb-2.4.0/tests/data/bad-data/maxminddb-golang/cyclic-data-structure.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/bad-data/maxminddb-golang/invalid-map-key-length.mmdb` & `maxminddb-2.4.0/tests/data/bad-data/maxminddb-golang/invalid-map-key-length.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/bad-data/maxminddb-golang/unexpected-bytes.mmdb` & `maxminddb-2.4.0/tests/data/bad-data/maxminddb-golang/unexpected-bytes.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/bad-data/maxminddb-python/bad-unicode-in-map-key.mmdb` & `maxminddb-2.4.0/tests/data/bad-data/maxminddb-python/bad-unicode-in-map-key.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/GeoIP2-Anonymous-IP-Test.mmdb` & `maxminddb-2.4.0/tests/data/test-data/GeoIP2-Anonymous-IP-Test.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/GeoIP2-City-Test-Broken-Double-Format.mmdb` & `maxminddb-2.4.0/tests/data/test-data/GeoIP2-City-Test-Broken-Double-Format.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/GeoIP2-City-Test-Invalid-Node-Count.mmdb` & `maxminddb-2.4.0/tests/data/test-data/GeoIP2-City-Test-Invalid-Node-Count.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/GeoIP2-City-Test.mmdb` & `maxminddb-2.4.0/tests/data/test-data/GeoIP2-City-Test.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/GeoIP2-Connection-Type-Test.mmdb` & `maxminddb-2.4.0/tests/data/test-data/GeoIP2-Connection-Type-Test.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/GeoIP2-Country-Test.mmdb` & `maxminddb-2.4.0/tests/data/test-data/GeoIP2-Country-Test.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/GeoIP2-DensityIncome-Test.mmdb` & `maxminddb-2.4.0/tests/data/test-data/GeoIP2-DensityIncome-Test.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/GeoIP2-Domain-Test.mmdb` & `maxminddb-2.4.0/tests/data/test-data/GeoIP2-Domain-Test.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/GeoIP2-Enterprise-Test.mmdb` & `maxminddb-2.4.0/tests/data/test-data/GeoIP2-Enterprise-Test.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/GeoIP2-ISP-Test.mmdb` & `maxminddb-2.4.0/tests/data/test-data/GeoIP2-ISP-Test.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/GeoIP2-Precision-Enterprise-Test.mmdb` & `maxminddb-2.4.0/tests/data/test-data/GeoIP2-Precision-Enterprise-Test.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/GeoIP2-Static-IP-Score-Test.mmdb` & `maxminddb-2.4.0/tests/data/test-data/GeoIP2-Static-IP-Score-Test.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/GeoIP2-User-Count-Test.mmdb` & `maxminddb-2.4.0/tests/data/test-data/GeoIP2-User-Count-Test.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/GeoLite2-ASN-Test.mmdb` & `maxminddb-2.4.0/tests/data/test-data/GeoLite2-ASN-Test.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/GeoLite2-City-Test.mmdb` & `maxminddb-2.4.0/tests/data/test-data/GeoLite2-City-Test.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/GeoLite2-Country-Test.mmdb` & `maxminddb-2.4.0/tests/data/test-data/GeoLite2-Country-Test.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-no-ipv4-search-tree.mmdb` & `maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-no-ipv4-search-tree.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-string-value-entries.mmdb` & `maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-string-value-entries.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-test-broken-pointers-24.mmdb` & `maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-test-broken-pointers-24.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-test-broken-search-tree-24.mmdb` & `maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-test-broken-search-tree-24.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-test-decoder.mmdb` & `maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-test-decoder.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-test-ipv4-24.mmdb` & `maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-test-ipv4-24.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-test-ipv4-28.mmdb` & `maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-test-ipv4-28.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-test-ipv4-32.mmdb` & `maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-test-ipv4-32.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-test-ipv6-24.mmdb` & `maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-test-ipv6-24.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-test-ipv6-28.mmdb` & `maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-test-ipv6-28.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-test-ipv6-32.mmdb` & `maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-test-ipv6-32.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-test-metadata-pointers.mmdb` & `maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-test-metadata-pointers.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-test-mixed-24.mmdb` & `maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-test-mixed-24.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-test-mixed-28.mmdb` & `maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-test-mixed-28.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-test-mixed-32.mmdb` & `maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-test-mixed-32.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-test-nested.mmdb` & `maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-test-nested.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/data/test-data/MaxMind-DB-test-pointer-decoder.mmdb` & `maxminddb-2.4.0/tests/data/test-data/MaxMind-DB-test-pointer-decoder.mmdb`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/decoder_test.py` & `maxminddb-2.4.0/tests/decoder_test.py`

 * *Files identical despite different names*

### Comparing `maxminddb-2.3.0/tests/reader_test.py` & `maxminddb-2.4.0/tests/reader_test.py`

 * *Files identical despite different names*


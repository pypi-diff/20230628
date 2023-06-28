# Comparing `tmp/tilecloud-1.9.2.tar.gz` & `tmp/tilecloud-1.9.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "tilecloud-1.9.2.tar", max compression
+gzip compressed data, was "tilecloud-1.9.3.tar", max compression
```

## Comparing `tilecloud-1.9.2.tar` & `tilecloud-1.9.3.tar`

### file list

```diff
@@ -1,82 +1,82 @@
--rw-r--r--   0        0        0    14936 2023-01-19 12:31:32.639212 tilecloud-1.9.2/README.md
--rw-r--r--   0        0        0     3203 2023-01-19 12:35:48.129063 tilecloud-1.9.2/pyproject.toml
--rw-r--r--   0        0        0    24767 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/__init__.py
--rw-r--r--   0        0        0        0 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/filter/__init__.py
--rw-r--r--   0        0        0     2481 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/filter/benchmark.py
--rw-r--r--   0        0        0      660 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/filter/consistenthash.py
--rw-r--r--   0        0        0      994 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/filter/contenttype.py
--rw-r--r--   0        0        0     3472 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/filter/error.py
--rw-r--r--   0        0        0     1092 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/filter/gzip_.py
--rw-r--r--   0        0        0     3430 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/filter/image.py
--rw-r--r--   0        0        0      656 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/filter/inboundingpyramid.py
--rw-r--r--   0        0        0      674 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/filter/logger.py
--rw-r--r--   0        0        0      879 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/filter/optipng.py
--rw-r--r--   0        0        0      571 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/filter/rate.py
--rw-r--r--   0        0        0        0 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/grid/__init__.py
--rw-r--r--   0        0        0     4344 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/grid/free.py
--rw-r--r--   0        0        0      164 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/grid/google.py
--rw-r--r--   0        0        0     3615 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/grid/quad.py
--rw-r--r--   0        0        0        0 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/layout/__init__.py
--rw-r--r--   0        0        0     1410 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/layout/i3d.py
--rw-r--r--   0        0        0      666 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/layout/osm.py
--rw-r--r--   0        0        0      651 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/layout/re_.py
--rw-r--r--   0        0        0     1434 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/layout/template.py
--rw-r--r--   0        0        0     1010 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/layout/tilecache.py
--rw-r--r--   0        0        0     1635 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/layout/wms.py
--rw-r--r--   0        0        0     2227 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/layout/wmts.py
--rw-r--r--   0        0        0     1227 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/layout/wrapped.py
--rw-r--r--   0        0        0       68 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/lib/PIL_.py
--rw-r--r--   0        0        0        0 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/lib/__init__.py
--rw-r--r--   0        0        0     2373 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/lib/memcached.py
--rw-r--r--   0        0        0     3214 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/lib/sqlite3_.py
--rw-r--r--   0        0        0     3597 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/lib/wmts.py
--rw-r--r--   0        0        0     2665 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/lib/wmts_get_capabilities_template.py
--rw-r--r--   0        0        0        0 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/py.typed
--rw-r--r--   0        0        0        0 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/scripts/__init__.py
--rwxr-xr-x   0        0        0     6457 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/scripts/tc_copy.py
--rwxr-xr-x   0        0        0     1288 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/scripts/tc_delete.py
--rwxr-xr-x   0        0        0     3225 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/scripts/tc_info.py
--rwxr-xr-x   0        0        0     1468 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/scripts/tc_mask.py
--rwxr-xr-x   0        0        0     2926 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/scripts/tc_mbtiles_create.py
--rwxr-xr-x   0        0        0     1857 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/scripts/tc_mbtiles_info.py
--rwxr-xr-x   0        0        0     2181 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/scripts/tc_refine_bounds.py
--rwxr-xr-x   0        0        0     5559 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/scripts/tc_viewer.py
--rw-r--r--   0        0        0        0 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/store/__init__.py
--rw-r--r--   0        0        0     3844 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/store/azure_storage_blob.py
--rw-r--r--   0        0        0      851 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/store/boundingpyramid.py
--rw-r--r--   0        0        0     1371 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/store/bsddb.py
--rw-r--r--   0        0        0     1068 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/store/debug.py
--rw-r--r--   0        0        0     1030 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/store/dict.py
--rw-r--r--   0        0        0     2362 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/store/filesystem.py
--rw-r--r--   0        0        0      655 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/store/filtered.py
--rw-r--r--   0        0        0      419 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/store/findfirst.py
--rw-r--r--   0        0        0     1004 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/store/log.py
--rw-r--r--   0        0        0     3047 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/store/mapnik_.py
--rw-r--r--   0        0        0     2432 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/store/mask.py
--rw-r--r--   0        0        0     5498 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/store/mbtiles.py
--rw-r--r--   0        0        0     1489 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/store/memcached.py
--rw-r--r--   0        0        0     2056 2023-01-19 12:31:32.643213 tilecloud-1.9.2/tilecloud/store/metatile.py
--rw-r--r--   0        0        0      474 2023-01-19 12:31:32.647213 tilecloud-1.9.2/tilecloud/store/null.py
--rw-r--r--   0        0        0      806 2023-01-19 12:31:32.647213 tilecloud-1.9.2/tilecloud/store/queue.py
--rw-r--r--   0        0        0    14070 2023-01-19 12:31:32.647213 tilecloud-1.9.2/tilecloud/store/redis.py
--rw-r--r--   0        0        0     1220 2023-01-19 12:31:32.647213 tilecloud-1.9.2/tilecloud/store/renderingtheworld.py
--rw-r--r--   0        0        0     4080 2023-01-19 12:31:32.647213 tilecloud-1.9.2/tilecloud/store/s3.py
--rw-r--r--   0        0        0      980 2023-01-19 12:31:32.647213 tilecloud-1.9.2/tilecloud/store/searchup.py
--rw-r--r--   0        0        0     4614 2023-01-19 12:31:32.647213 tilecloud-1.9.2/tilecloud/store/sqs.py
--rw-r--r--   0        0        0      482 2023-01-19 12:31:32.647213 tilecloud-1.9.2/tilecloud/store/tilecache.py
--rw-r--r--   0        0        0     2088 2023-01-19 12:31:32.647213 tilecloud-1.9.2/tilecloud/store/tilejson.py
--rw-r--r--   0        0        0     2288 2023-01-19 12:31:32.647213 tilecloud-1.9.2/tilecloud/store/url.py
--rw-r--r--   0        0        0      614 2023-01-19 12:31:32.647213 tilecloud-1.9.2/tilecloud/store/wmts.py
--rw-r--r--   0        0        0     2585 2023-01-19 12:31:32.647213 tilecloud-1.9.2/tilecloud/store/zip.py
--rw-r--r--   0        0        0      176 2023-01-19 12:31:32.647213 tilecloud-1.9.2/tilecloud/tests/__init__.py
--rw-r--r--   0        0        0     5787 2023-01-19 12:31:32.647213 tilecloud-1.9.2/tilecloud/tests/test_boundingpyramid.py
--rw-r--r--   0        0        0     2282 2023-01-19 12:31:32.647213 tilecloud-1.9.2/tilecloud/tests/test_bounds.py
--rw-r--r--   0        0        0     3322 2023-01-19 12:31:32.647213 tilecloud-1.9.2/tilecloud/tests/test_metatile.py
--rw-r--r--   0        0        0     4197 2023-01-19 12:31:32.647213 tilecloud-1.9.2/tilecloud/tests/test_redis.py
--rw-r--r--   0        0        0      491 2023-01-19 12:31:32.647213 tilecloud-1.9.2/tilecloud/tests/test_tile.py
--rw-r--r--   0        0        0     2321 2023-01-19 12:31:32.647213 tilecloud-1.9.2/tilecloud/tests/test_tilecoord.py
--rw-r--r--   0        0        0    11932 2023-01-19 12:31:32.647213 tilecloud-1.9.2/tilecloud/tests/test_tilegrid.py
--rw-r--r--   0        0        0    11922 2023-01-19 12:31:32.647213 tilecloud-1.9.2/tilecloud/tests/test_tilelayout.py
--rw-r--r--   0        0        0     7654 2023-01-19 12:31:32.647213 tilecloud-1.9.2/tilecloud/tests/test_tilestore.py
--rw-r--r--   0        0        0    17154 1970-01-01 00:00:00.000000 tilecloud-1.9.2/setup.py
--rw-r--r--   0        0        0    16626 1970-01-01 00:00:00.000000 tilecloud-1.9.2/PKG-INFO
+-rw-r--r--   0        0        0    14936 2023-01-19 12:56:22.896127 tilecloud-1.9.3/README.md
+-rw-r--r--   0        0        0     3203 2023-01-19 12:59:45.670234 tilecloud-1.9.3/pyproject.toml
+-rw-r--r--   0        0        0    24767 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/__init__.py
+-rw-r--r--   0        0        0        0 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/filter/__init__.py
+-rw-r--r--   0        0        0     2481 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/filter/benchmark.py
+-rw-r--r--   0        0        0      660 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/filter/consistenthash.py
+-rw-r--r--   0        0        0      994 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/filter/contenttype.py
+-rw-r--r--   0        0        0     3472 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/filter/error.py
+-rw-r--r--   0        0        0     1092 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/filter/gzip_.py
+-rw-r--r--   0        0        0     3430 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/filter/image.py
+-rw-r--r--   0        0        0      656 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/filter/inboundingpyramid.py
+-rw-r--r--   0        0        0      674 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/filter/logger.py
+-rw-r--r--   0        0        0      879 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/filter/optipng.py
+-rw-r--r--   0        0        0      571 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/filter/rate.py
+-rw-r--r--   0        0        0        0 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/grid/__init__.py
+-rw-r--r--   0        0        0     4344 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/grid/free.py
+-rw-r--r--   0        0        0      164 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/grid/google.py
+-rw-r--r--   0        0        0     3615 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/grid/quad.py
+-rw-r--r--   0        0        0        0 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/layout/__init__.py
+-rw-r--r--   0        0        0     1410 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/layout/i3d.py
+-rw-r--r--   0        0        0      666 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/layout/osm.py
+-rw-r--r--   0        0        0      651 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/layout/re_.py
+-rw-r--r--   0        0        0     1434 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/layout/template.py
+-rw-r--r--   0        0        0     1010 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/layout/tilecache.py
+-rw-r--r--   0        0        0     1635 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/layout/wms.py
+-rw-r--r--   0        0        0     2227 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/layout/wmts.py
+-rw-r--r--   0        0        0     1227 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/layout/wrapped.py
+-rw-r--r--   0        0        0       68 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/lib/PIL_.py
+-rw-r--r--   0        0        0        0 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/lib/__init__.py
+-rw-r--r--   0        0        0     2373 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/lib/memcached.py
+-rw-r--r--   0        0        0     3214 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/lib/sqlite3_.py
+-rw-r--r--   0        0        0     3597 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/lib/wmts.py
+-rw-r--r--   0        0        0     2665 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/lib/wmts_get_capabilities_template.py
+-rw-r--r--   0        0        0        0 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/py.typed
+-rw-r--r--   0        0        0        0 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/scripts/__init__.py
+-rwxr-xr-x   0        0        0     6457 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/scripts/tc_copy.py
+-rwxr-xr-x   0        0        0     1288 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/scripts/tc_delete.py
+-rwxr-xr-x   0        0        0     3225 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/scripts/tc_info.py
+-rwxr-xr-x   0        0        0     1468 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/scripts/tc_mask.py
+-rwxr-xr-x   0        0        0     2926 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/scripts/tc_mbtiles_create.py
+-rwxr-xr-x   0        0        0     1857 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/scripts/tc_mbtiles_info.py
+-rwxr-xr-x   0        0        0     2181 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/scripts/tc_refine_bounds.py
+-rwxr-xr-x   0        0        0     5559 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/scripts/tc_viewer.py
+-rw-r--r--   0        0        0        0 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/store/__init__.py
+-rw-r--r--   0        0        0     3844 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/store/azure_storage_blob.py
+-rw-r--r--   0        0        0      851 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/store/boundingpyramid.py
+-rw-r--r--   0        0        0     1371 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/store/bsddb.py
+-rw-r--r--   0        0        0     1068 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/store/debug.py
+-rw-r--r--   0        0        0     1030 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/store/dict.py
+-rw-r--r--   0        0        0     2362 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/store/filesystem.py
+-rw-r--r--   0        0        0      655 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/store/filtered.py
+-rw-r--r--   0        0        0      419 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/store/findfirst.py
+-rw-r--r--   0        0        0     1004 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/store/log.py
+-rw-r--r--   0        0        0     3047 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/store/mapnik_.py
+-rw-r--r--   0        0        0     2432 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/store/mask.py
+-rw-r--r--   0        0        0     5498 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/store/mbtiles.py
+-rw-r--r--   0        0        0     1489 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/store/memcached.py
+-rw-r--r--   0        0        0     2056 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/store/metatile.py
+-rw-r--r--   0        0        0      474 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/store/null.py
+-rw-r--r--   0        0        0      806 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/store/queue.py
+-rw-r--r--   0        0        0    14070 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/store/redis.py
+-rw-r--r--   0        0        0     1220 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/store/renderingtheworld.py
+-rw-r--r--   0        0        0     4080 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/store/s3.py
+-rw-r--r--   0        0        0      980 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/store/searchup.py
+-rw-r--r--   0        0        0     4614 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/store/sqs.py
+-rw-r--r--   0        0        0      482 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/store/tilecache.py
+-rw-r--r--   0        0        0     2088 2023-01-19 12:56:22.896127 tilecloud-1.9.3/tilecloud/store/tilejson.py
+-rw-r--r--   0        0        0     2288 2023-01-19 12:56:22.900127 tilecloud-1.9.3/tilecloud/store/url.py
+-rw-r--r--   0        0        0      614 2023-01-19 12:56:22.900127 tilecloud-1.9.3/tilecloud/store/wmts.py
+-rw-r--r--   0        0        0     2585 2023-01-19 12:56:22.900127 tilecloud-1.9.3/tilecloud/store/zip.py
+-rw-r--r--   0        0        0      176 2023-01-19 12:56:22.900127 tilecloud-1.9.3/tilecloud/tests/__init__.py
+-rw-r--r--   0        0        0     5787 2023-01-19 12:56:22.900127 tilecloud-1.9.3/tilecloud/tests/test_boundingpyramid.py
+-rw-r--r--   0        0        0     2282 2023-01-19 12:56:22.900127 tilecloud-1.9.3/tilecloud/tests/test_bounds.py
+-rw-r--r--   0        0        0     3322 2023-01-19 12:56:22.900127 tilecloud-1.9.3/tilecloud/tests/test_metatile.py
+-rw-r--r--   0        0        0     4197 2023-01-19 12:56:22.900127 tilecloud-1.9.3/tilecloud/tests/test_redis.py
+-rw-r--r--   0        0        0      491 2023-01-19 12:56:22.900127 tilecloud-1.9.3/tilecloud/tests/test_tile.py
+-rw-r--r--   0        0        0     2321 2023-01-19 12:56:22.900127 tilecloud-1.9.3/tilecloud/tests/test_tilecoord.py
+-rw-r--r--   0        0        0    11932 2023-01-19 12:56:22.900127 tilecloud-1.9.3/tilecloud/tests/test_tilegrid.py
+-rw-r--r--   0        0        0    11922 2023-01-19 12:56:22.900127 tilecloud-1.9.3/tilecloud/tests/test_tilelayout.py
+-rw-r--r--   0        0        0     7654 2023-01-19 12:56:22.900127 tilecloud-1.9.3/tilecloud/tests/test_tilestore.py
+-rw-r--r--   0        0        0    17154 1970-01-01 00:00:00.000000 tilecloud-1.9.3/setup.py
+-rw-r--r--   0        0        0    16626 1970-01-01 00:00:00.000000 tilecloud-1.9.3/PKG-INFO
```

### Comparing `tilecloud-1.9.2/README.md` & `tilecloud-1.9.3/README.md`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/pyproject.toml` & `tilecloud-1.9.3/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -13,15 +13,15 @@
 [tool.isort]
 known_first_party = "tilecloud"
 profile = "black"
 line_length = 110
 
 [tool.poetry]
 name = "tilecloud"
-version = "1.9.2"
+version = "1.9.3"
 description = "Tools for managing tiles"
 readme = "README.md"
 authors = ["Camptocamp <info@camptocamp.com>"]
 repository = "https://github.com/camptocamp/tilecloud"
 license = "BSD"
 keywords = ["gis", "tilecloud"]
 packages = [{ include = "tilecloud" }]
@@ -45,15 +45,15 @@
 tc-copy = "tilecloud.scripts.tc_copy:main"
 tc-delete = "tilecloud.scripts.tc_delete:main"
 tc-info = "tilecloud.scripts.tc_info:main"
 tc-mask = "tilecloud.scripts.tc_mask:main"
 tc-mbtiles = "tilecloud.scripts.tc_mbtiles_create:main"
 tc-mbtiles-info = "tilecloud.scripts.tc_mbtiles_info:main"
 tc-redifined-bounds = "tilecloud.scripts.tc_refine_bounds:main"
-tc-viewer = "tilecloud.scripts.tc-viewer:main"
+tc-viewer = "tilecloud.scripts.tc_viewer:main"
 
 [tool.poetry.dependencies]
 python = ">=3.8,<3.11"
 azure-storage-blob = { version = "12.14.1", optional = true }
 azure-identity = { version = "1.12.0", optional = true }
 boto3 = { version = "1.26.41", optional = true }
 bottle = "0.12.23"
```

### Comparing `tilecloud-1.9.2/tilecloud/__init__.py` & `tilecloud-1.9.3/tilecloud/__init__.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/filter/benchmark.py` & `tilecloud-1.9.3/tilecloud/filter/benchmark.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/filter/consistenthash.py` & `tilecloud-1.9.3/tilecloud/filter/consistenthash.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/filter/contenttype.py` & `tilecloud-1.9.3/tilecloud/filter/contenttype.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/filter/error.py` & `tilecloud-1.9.3/tilecloud/filter/error.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/filter/gzip_.py` & `tilecloud-1.9.3/tilecloud/filter/gzip_.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/filter/image.py` & `tilecloud-1.9.3/tilecloud/filter/image.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/filter/inboundingpyramid.py` & `tilecloud-1.9.3/tilecloud/filter/inboundingpyramid.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/filter/logger.py` & `tilecloud-1.9.3/tilecloud/filter/logger.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/filter/optipng.py` & `tilecloud-1.9.3/tilecloud/filter/optipng.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/filter/rate.py` & `tilecloud-1.9.3/tilecloud/filter/rate.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/grid/free.py` & `tilecloud-1.9.3/tilecloud/grid/free.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/grid/quad.py` & `tilecloud-1.9.3/tilecloud/grid/quad.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/layout/i3d.py` & `tilecloud-1.9.3/tilecloud/layout/i3d.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/layout/osm.py` & `tilecloud-1.9.3/tilecloud/layout/osm.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/layout/re_.py` & `tilecloud-1.9.3/tilecloud/layout/re_.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/layout/template.py` & `tilecloud-1.9.3/tilecloud/layout/template.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/layout/tilecache.py` & `tilecloud-1.9.3/tilecloud/layout/tilecache.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/layout/wms.py` & `tilecloud-1.9.3/tilecloud/layout/wms.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/layout/wmts.py` & `tilecloud-1.9.3/tilecloud/layout/wmts.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/layout/wrapped.py` & `tilecloud-1.9.3/tilecloud/layout/wrapped.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/lib/memcached.py` & `tilecloud-1.9.3/tilecloud/lib/memcached.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/lib/sqlite3_.py` & `tilecloud-1.9.3/tilecloud/lib/sqlite3_.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/lib/wmts.py` & `tilecloud-1.9.3/tilecloud/lib/wmts.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/lib/wmts_get_capabilities_template.py` & `tilecloud-1.9.3/tilecloud/lib/wmts_get_capabilities_template.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/scripts/tc_copy.py` & `tilecloud-1.9.3/tilecloud/scripts/tc_copy.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/scripts/tc_delete.py` & `tilecloud-1.9.3/tilecloud/scripts/tc_delete.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/scripts/tc_info.py` & `tilecloud-1.9.3/tilecloud/scripts/tc_info.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/scripts/tc_mask.py` & `tilecloud-1.9.3/tilecloud/scripts/tc_mask.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/scripts/tc_mbtiles_create.py` & `tilecloud-1.9.3/tilecloud/scripts/tc_mbtiles_create.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/scripts/tc_mbtiles_info.py` & `tilecloud-1.9.3/tilecloud/scripts/tc_mbtiles_info.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/scripts/tc_refine_bounds.py` & `tilecloud-1.9.3/tilecloud/scripts/tc_refine_bounds.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/scripts/tc_viewer.py` & `tilecloud-1.9.3/tilecloud/scripts/tc_viewer.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/store/azure_storage_blob.py` & `tilecloud-1.9.3/tilecloud/store/azure_storage_blob.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/store/boundingpyramid.py` & `tilecloud-1.9.3/tilecloud/store/boundingpyramid.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/store/bsddb.py` & `tilecloud-1.9.3/tilecloud/store/bsddb.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/store/debug.py` & `tilecloud-1.9.3/tilecloud/store/debug.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/store/dict.py` & `tilecloud-1.9.3/tilecloud/store/dict.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/store/filesystem.py` & `tilecloud-1.9.3/tilecloud/store/filesystem.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/store/filtered.py` & `tilecloud-1.9.3/tilecloud/store/filtered.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/store/log.py` & `tilecloud-1.9.3/tilecloud/store/log.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/store/mapnik_.py` & `tilecloud-1.9.3/tilecloud/store/mapnik_.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/store/mask.py` & `tilecloud-1.9.3/tilecloud/store/mask.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/store/mbtiles.py` & `tilecloud-1.9.3/tilecloud/store/mbtiles.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/store/memcached.py` & `tilecloud-1.9.3/tilecloud/store/memcached.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/store/metatile.py` & `tilecloud-1.9.3/tilecloud/store/metatile.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/store/queue.py` & `tilecloud-1.9.3/tilecloud/store/queue.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/store/redis.py` & `tilecloud-1.9.3/tilecloud/store/redis.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/store/renderingtheworld.py` & `tilecloud-1.9.3/tilecloud/store/renderingtheworld.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/store/s3.py` & `tilecloud-1.9.3/tilecloud/store/s3.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/store/searchup.py` & `tilecloud-1.9.3/tilecloud/store/searchup.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/store/sqs.py` & `tilecloud-1.9.3/tilecloud/store/sqs.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/store/tilejson.py` & `tilecloud-1.9.3/tilecloud/store/tilejson.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/store/url.py` & `tilecloud-1.9.3/tilecloud/store/url.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/store/wmts.py` & `tilecloud-1.9.3/tilecloud/store/wmts.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/store/zip.py` & `tilecloud-1.9.3/tilecloud/store/zip.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/tests/test_boundingpyramid.py` & `tilecloud-1.9.3/tilecloud/tests/test_boundingpyramid.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/tests/test_bounds.py` & `tilecloud-1.9.3/tilecloud/tests/test_bounds.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/tests/test_metatile.py` & `tilecloud-1.9.3/tilecloud/tests/test_metatile.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/tests/test_redis.py` & `tilecloud-1.9.3/tilecloud/tests/test_redis.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/tests/test_tilecoord.py` & `tilecloud-1.9.3/tilecloud/tests/test_tilecoord.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/tests/test_tilegrid.py` & `tilecloud-1.9.3/tilecloud/tests/test_tilegrid.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/tests/test_tilelayout.py` & `tilecloud-1.9.3/tilecloud/tests/test_tilelayout.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/tilecloud/tests/test_tilestore.py` & `tilecloud-1.9.3/tilecloud/tests/test_tilestore.py`

 * *Files identical despite different names*

### Comparing `tilecloud-1.9.2/setup.py` & `tilecloud-1.9.3/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -35,19 +35,19 @@
                      'tc-delete = tilecloud.scripts.tc_delete:main',
                      'tc-info = tilecloud.scripts.tc_info:main',
                      'tc-mask = tilecloud.scripts.tc_mask:main',
                      'tc-mbtiles = tilecloud.scripts.tc_mbtiles_create:main',
                      'tc-mbtiles-info = tilecloud.scripts.tc_mbtiles_info:main',
                      'tc-redifined-bounds = '
                      'tilecloud.scripts.tc_refine_bounds:main',
-                     'tc-viewer = tilecloud.scripts.tc-viewer:main']}
+                     'tc-viewer = tilecloud.scripts.tc_viewer:main']}
 
 setup_kwargs = {
     'name': 'tilecloud',
-    'version': '1.9.2',
+    'version': '1.9.3',
     'description': 'Tools for managing tiles',
     'long_description': '# TileCloud\n\nA powerful utility for generating, managing, transforming, and visualizing map tiles in multiple formats.\n\n## Introduction\n\nTileCloud is a powerful utility for generating, managing, transforming, visualizing and map tiles in multiple\nformats. It can create, read update, delete tiles in multiple back ends, called TileStores. Existing\nTileStores include:\n\n- HTTP/REST in any layout\n- WMTS\n- Amazon [S3](http://aws.amazon.com/s3/) and [SQS](http://aws.amazon.com/sqs/)\n- [MBTiles](https://github.com/mapbox/mbtiles-spec)\n- [TileJSON](https://github.com/mapbox/TileJSON)\n- [Mapnik](http://mapnik.org/) (via [mapnik2](http://pypi.python.org/pypi/mapnik2))\n- [Memcached](http://memcached.org/)\n- Local file system\n- Log files in any format\n\nTileCloud is not limited to image tiles, it can also handle other tile data such as\n[UTFGrid](https://github.com/mapbox/utfgrid-spec), or elevation data in JSON format.\n\nTileCloud uses Python\'s generators and iterators to efficiently stream tens of millions of tiles, and can\nhandle multiple tiles in parallel using Python\'s\n[multiprocessing](http://docs.python.org/library/multiprocessing.html) library.\n\nExample tasks that TileCloud makes easy include:\n\n- Visualize tiles stored in any TileStore with [OpenLayers](http://www.openlayers.org/), [Google\n  Maps](http://maps.google.com/), [jQuery Geo](http://www.jquerygeo.com/),\n  [Leaflet](http://leaflet.cloudmade.com/), [Polymaps](http://polymaps.org/), [Modest\n  Maps](http://www.modestmaps.com/), and [OpenWebGlobe](http://www.openwebglobe.org/).\n- Convert sixty million PNG tiles stored in S3 to JPEG format with different quality settings at different\n  zoom levels.\n- Transform image formats and perform arbitrary image transformations on the fly, including PNG\n  optimization.\n- Generate semi-transparent tiles with embedded tile coordinates for debugging.\n- Pack multiple tile layers into a single tile on the server.\n- Efficiently calculate bounding boxes and detect missing tiles in existing tile datasets.\n- Simulate fast and slow tile servers.\n- Efficiently delete millions of tiles in S3.\n- Read JSON tiles from a tarball, compress them, and upload them.\n\n## Getting started\n\nTileCloud depends on some Python modules. It\'s easiest to install them with `pip` in a `virtualenv`:\n\n    $ python3 -m venv .venv\n    $ . .venv/bin/activate\n    $ pip install -r requirements.txt\n\nFor a quick demo, run\n\n    $ ./tc-viewer --root=3/4/2 \'http://gsp2.apple.com/tile?api=1&style=slideshow&layers=default&lang=en_GB&z=%(z)d&x=%(x)d&y=%(y)d&v=9\'\n\nand point your browser at <http://localhost:8080/>. Type `Ctrl-C` to terminate `tc-viewer`.\n\nNext, download an example MBTiles file from [MapBox](http://mapbox.com/), such as [Geography\nClass](http://tiles.mapbox.com/mapbox/map/geography-class). We can quickly find out more about this tile set\nwith the `tc-info` command. For example, to count the number of tiles:\n\n    $ ./tc-info -t count geography-class.mbtiles\n    87381\n\nTo calculate the bounding pyramid:\n\n    $ ./tc-info -t bounding-pyramid -r geography-class.mbtiles\n    0/0/0:+1/+1\n    1/0/0:+2/+2\n    2/0/0:+4/+4\n    3/0/0:+8/+8\n    4/0/0:+16/+16\n    5/0/0:+32/+32\n    6/0/0:+64/+64\n    7/0/0:+128/+128\n    8/0/0:+256/+256\n\nTo check for missing tiles against a bounding pyramid:\n\n    $ ./tc-info -b 0/0/0:8/*/* -t completion geography-class.mbtiles\n    0 1/1 (100%)\n    1 4/4 (100%)\n    2 16/16 (100%)\n    3 64/64 (100%)\n    4 256/256 (100%)\n    5 1024/1024 (100%)\n    6 4096/4096 (100%)\n    7 16384/16384 (100%)\n    8 65536/65536 (100%)\n\nThis shows, for each zoom level, the number of tiles at that zoom level, the total number of tiles expected at\nthat zoom level for the specified bounding pyramid (`0/0/0:8/*/*` means all tiles from level 0 to level 8),\nand a percentage completion. This can be useful for checking that a tile set is complete.\n\nNow, display this MBTiles tile set on top of the [OpenStreetMap](http://www.openstreetmap.org/) tiles and a\ndebug tile layer:\n\n    $ ./tc-viewer tiles.openstreetmap_org geography-class.mbtiles tiles.debug.black\n\nYou\'ll need to point your browser at <http://localhost:8080/> and choose your favorite library.\n\n`tc-info` and `tc-viewer` are utility programs. Normally you use TileCloud by writing short Python programs\nthat connect the TileCloud\'s modules to perform the action that you want.\n\nAs a first example, run the following:\n\n    $ PYTHONPATH=. examples/download.py\n\nThis will download a few tiles from [OpenStreetMap](http://www.openstreetmap.org/) and save them in a local\nMBTiles file called `local.mbtiles`. Look at the source code to `examples/download.py` to see how it works. If\nthere are problems with the download, just interrupt it with `Ctrl-C` and re-run it: the program will\nautomatically resume where it left off.\n\nOnce you have downloaded a few tiles, you can view them directly with `tc-viewer`:\n\n    $ ./tc-viewer --root=4/8/5 local.mbtiles tiles.debug.black\n\nPoint your browser at <http://localhost:8080> as usual. The `--root` option to `tc-viewer` instructs the\nviewer to start at a defined tile, rather than at 0/0/0, so you don\'t have to zoom in to find the tiles that\nyou downloaded.\n\n## Changelog\n\n### 1.9.0\n\n- Add the following extra dependencies `azure`, `aws`, `wsgi`, `redis`, `all`.\n\n## Tile coordinates, tile layouts, tile grids and bounding pyramids\n\nTileCloud always represents tile coordinates as strings like `z/x/y`. TileCloud primarily works in tile\ncoordinates, although geographic coordinates can be used in some places.\n\nTile layouts convert tile coordinates to and from strings for use in paths, URLs, keys, etc.\n\nTile grids are used to convert tile coordinates to and from geographic coordinates, and to relate tiles with\ndifferent z values.\n\nBounding pyramids represent a range of tiles in the x, y and z directions. The format is basically\n`minz/minx/miny:maxz/maxx/maxy` but `maxz` is optional and `maxz`, `maxx` and `maxy` can be prefixed with an\n`+` sign to indicate that they are relative to the corresponding `min` value. This is probably best\ndemonstrated by a few examples:\n\n`4/10/20:15/25`\n\n: This corresponds to a range of tiles with z=4, x=10..15 and y=20..25\n\n`4/10/20:+5/+5`\n\n: This is the same range (z=4, x=10..15, y=20..25) but expressed using relative sizes.\n\n`4/10/20:5/15/20`\n\n: This is the same range of tiles above, but also includes all the tiles at level z=5 which overlap the\nabove range. TileCloud uses the tile grid to calculate which tiles from level z=5 to include.\n\n`4/10/20:+1/+5/+5`\n\n: This represents the range same as the previous example using a relative `maxz`.\n\n## Quick tile generation\n\nThe `tc-copy` command can be used to copy tiles between different TileStores. If a TileStore has the side\neffect of generating tiles, then it functions as a quick tile generation utility. First, some quick examples.\n\nTo convert from one tile format to another, just copy from source to destination. For example, to convert an\nMBTiles file in to a ZIP file, just run:\n\n    $ ./tc-copy geography-class.mbtiles geography-class.zip\n\nYou can check this worked with `unzip`:\n\n    $ unzip -t geography-class.zip\n\nEqually, `tc-copy` can be used to download multiple tiles:\n\n    $ ./tc-copy --bounding-pyramid 4/0/0:0/16/16 tiles.openstreetmap_org osm-up-to-z4.mbtiles\n\nHere we downloaded zoom levels 0 to 4 of the OpenStreetMap tiles into a local MBTiles file. The\n`--bounding-pyramid` option is required because otherwise we would download _all_ OpenStreetMap tiles -- which\nmight take some time (and also contravene OpenStreetMap\'s tile usage policy). Note that, by default, `tc-copy`\nwon\'t overwrite tiles if they already exist in the destination. This means that you can interrupt the above\ncommand and restart it, and it will resume where it was interrupted. If you want to overwrite tiles in the\ndestination then pass the `--overwrite` option to `tc-copy`.\n\nIn the same way, `tc-copy` can also be used to upload tiles. For example, to upload an MBTiles file to S3,\njust use:\n\n    $ ./tc-copy osm-up-to-z4.mbtiles s3://bucket/prefix/%(z)d/%(x)d/%(y)d.jpg\n\n`bucket` is the name of your S3 bucket. You\'ll need to have set the `AWS_ACCESS_KEY_ID` and\n`AWS_SECRET_ACCESS_KEY` environment variables to have permission to upload to S3. The rest of the destination\n(`prefix/%(z)d/%(x)d/%(y)d.jpg`) is a template describing the layout of the tiles in S3. It\'s a normal Python\nformat string: `%(x)d` means substitute the tile\'s `x` coordinate as a decimal integer.\n\nYou can pass the same `s3://` URL to `tc-viewer`. This allows you to visualize your tiles stored in S3 with\nyour favorite mapping library. For example:\n\n    $ ./tc-viewer s3://bucket/prefix/%(z)d/%(x)d/%(y)d.jpg\n\nHere, `tc-viewer` is acting as a proxy, serving tiles stored in S3 over HTTP, bypassing any caches or access\ncontrols (assuming you have the correct credentials, of course). This allows you to visualize the exact tiles\nthat you\'ve stored.\n\n## Rendering the World\n\nAt [FOSS4G-NA](http://foss4g-na.org/), [MapBox](http://mapbox.com/) presented an excellent strategy for\n[rendering the world](http://mapbox.com/blog/rendering-the-world/). TileCloud supports the subdivision\nstrategy. To run the demo, execute:\n\n    $ python examples/renderingtheworld.py\n\nThis will generate tiles from a WMTS tile server and save them in a local MBTiles tiles. When the above\ncommand is complete, you can see the bounding pyramid of the generated tiles:\n\n    $ ./tc-info -t bounding-pyramid -r medford_buildings.mbtiles\n    0/0/0:+1/+1\n    1/0/0:+1/+1\n    2/0/1:+1/+1\n    3/1/2:+1/+1\n    4/2/5:+1/+1\n    5/5/11:+1/+1\n    6/10/23:+1/+1\n    7/20/47:+1/+1\n    8/40/94:+2/+2\n    9/80/189:+2/+1\n    10/162/378:+1/+2\n    11/324/757:+2/+2\n    12/649/1514:+3/+3\n    13/1299/3028:+4/+5\n    14/2598/6057:+7/+8\n    15/5196/12114:+13/+15\n\nYou can look at these tiles (which show buildings in Medford, OR) with the command:\n\n    ./tc-viewer --root=7/20/47 tiles.openstreetmap_org medford_buildings.mbtiles\n\n## A cheap-and-cheerful tile server\n\n`tc-viewer` can be used as a lightweight tile server, which can be useful for development, debugging and\noff-line demos. The TileStores passed as arguments to `tc-viewer` are available at the URL:\n\n    http://localhost:8080/tiles/{index}/tiles/{z}/{x}/{y}\n\nwhere `{index}` is the index of the TileStore on the command line (starting from 0 for the first tile store),\nand `{z}`, `{x}` and `{y}` are the components of the tile coordinate. The second `tiles` in the URL is present\nto work around assumptions made by OpenWebGlobe. This layout is directly usable by most mapping libraries, see\nthe code in `views/*.tpl` for examples. The host and port can be set with the `--host` and `--port` command\nline options, respectively.\n\nNote that there is no file extension. `tc-viewer` will automatically set the correct content type and content\nencoding headers if it can determine them, and, failing this, most browsers will figure it out for themselves.\n\nFor convenience, `tc-viewer` serves everything in the `static` directory under the URL `/static`. This can be\nused to serve your favorite mapping library and/or application code directly for testing purposes.\n\nBy default, `tc-viewer` will use [Tornado](http://www.tornadoweb.org/) as a web server, if it is available,\notherwise it will fall back to [WSGIRef](http://docs.python.org/library/wsgiref.html). Tornado has reasonably\ngood performance, and is adequate for local development and off-line demos, especially when used with a\nMBTiles TileStore. WSGIRef has very poor performance (it handles only one request at a time) and as such can\nbe used as a "slow" tile server, ideal for debugging tile loading code or testing how your web application\nperforms over a slow network connection. `tc-viewer` is particularly slow when used to proxy tiles being\nserved by a remote server. You can set the server explicitly with the `--server` option.\n\n`tc-viewer` sets the `Access-Control-Allow-Origin` header to `*` for all the tiles it serves, this allows the\ntiles to be used as textures for WebGL applications running on different hosts/ports. For more information,\nsee [Cross-Domain Textures](https://developer.mozilla.org/en/WebGL/Cross-Domain_Textures).\n\n`tc-viewer` is designed as a development tool, and the power that it offers comes at the expense of fragility.\nIt makes many assumptions - including the benevolence of the user - that make it entirely unsuitable as a\ngeneric tile server. It should only be used in development or demonstration environments.\n\n## Comparing mapping libraries\n\n`tc-viewer` supports most popular web mapping libraries out-of-the box. This can be very useful for quick,\npractical comparisons. If your favorite mapping library is missing, please submit an\n[issue](https://github.com/camptocamp/tilecloud/issues), or, even better, a [pull\nrequest](https://github.com/camptocamp/tilecloud/pulls).\n\n## Contributing\n\nPlease report bugs and feature requests using the [GitHub issue\ntracker](https://github.com/camptocamp/tilecloud/issues).\n\nIf you\'d like to contribute to TileCloud, please install the development requirements:\n\n    $ pip install -r dev-requirements.txt\n\nTileCloud comes with unit tests in the `tilecloud/tests` directory. You can run these with the command:\n\n    $ make test\n\nThis is equivalent to:\n\n    $ python setup.py nosetests\n\nFor pull requests, it is very much appreciated if your code passes `prospector` without warnings. You can run\nprospector on the codebase with the command:\n\n    $ make prospector\n\n## License\n\nCopyright (c) 2012, Tom Payne <twpayne@gmail.com> All rights reserved.\nCopyright (c) 2012, Camptocamp All rights reserved.\n\nRedistribution and use in source and binary forms, with or without modification, are permitted provided that\nthe following conditions are met:\n\n- Redistributions of source code must retain the above copyright notice, this list of conditions and the\n  following disclaimer.\n- Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the\n  following disclaimer in the documentation and/or other materials provided with the distribution.\n\nTHIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED\nWARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A\nPARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY\nDIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,\nPROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER\nCAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR\nOTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH\nDAMAGE.\n\nvim: set filetype=rst spell spelllang=en textwidth=0:\n',
     'author': 'Camptocamp',
     'author_email': 'info@camptocamp.com',
     'maintainer': 'None',
     'maintainer_email': 'None',
     'url': 'https://github.com/camptocamp/tilecloud',
```

### Comparing `tilecloud-1.9.2/PKG-INFO` & `tilecloud-1.9.3/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: tilecloud
-Version: 1.9.2
+Version: 1.9.3
 Summary: Tools for managing tiles
 Home-page: https://github.com/camptocamp/tilecloud
 License: BSD
 Keywords: gis,tilecloud
 Author: Camptocamp
 Author-email: info@camptocamp.com
 Requires-Python: >=3.8,<3.11
```


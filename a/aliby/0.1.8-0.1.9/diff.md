# Comparing `tmp/aliby-0.1.8.tar.gz` & `tmp/aliby-0.1.9.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "aliby-0.1.8.tar", max compression
+gzip compressed data, was "aliby-0.1.9.tar", max compression
```

## Comparing `aliby-0.1.8.tar` & `aliby-0.1.9.tar`

### file list

```diff
@@ -1,89 +1,89 @@
--rw-r--r--   0        0        0        0 2021-12-17 11:45:48.817283 aliby-0.1.8/aliby/__init__.py
--rw-r--r--   0        0        0     8369 2022-01-07 20:20:48.263260 aliby-0.1.8/aliby/baby_client.py
--rw-r--r--   0        0        0     8733 2021-12-20 14:42:19.602790 aliby-0.1.8/aliby/errors.txt
--rw-r--r--   0        0        0    17187 2022-01-10 12:03:27.952780 aliby-0.1.8/aliby/experiment.py
--rw-r--r--   0        0        0    10751 2021-12-17 11:45:48.825283 aliby-0.1.8/aliby/extract.py
--rw-r--r--   0        0        0     3100 2022-01-07 17:42:57.502877 aliby-0.1.8/aliby/haystack.py
--rw-r--r--   0        0        0        0 2021-12-17 11:45:48.817283 aliby-0.1.8/aliby/io/__init__.py
--rw-r--r--   0        0        0      143 2021-12-18 13:36:49.586868 aliby-0.1.8/aliby/io/__pycache__/__init__.cpython-37.pyc
--rw-r--r--   0        0        0     6717 2021-12-18 13:36:49.590868 aliby-0.1.8/aliby/io/__pycache__/base.cpython-37.pyc
--rw-r--r--   0        0        0    19198 2021-12-18 13:36:49.662871 aliby-0.1.8/aliby/io/__pycache__/matlab.cpython-37.pyc
--rw-r--r--   0        0        0     2220 2021-12-20 15:57:54.355267 aliby-0.1.8/aliby/io/__pycache__/metadata_parser.cpython-37.pyc
--rw-r--r--   0        0        0     5324 2022-01-10 14:47:50.046216 aliby-0.1.8/aliby/io/__pycache__/omero.cpython-37.pyc
--rw-r--r--   0        0        0     8397 2021-12-18 13:36:49.610869 aliby-0.1.8/aliby/io/__pycache__/signal.cpython-37.pyc
--rw-r--r--   0        0        0     1787 2021-12-18 13:36:49.670872 aliby-0.1.8/aliby/io/__pycache__/utils.cpython-37.pyc
--rw-r--r--   0        0        0    14589 2021-12-18 13:36:49.590868 aliby-0.1.8/aliby/io/__pycache__/writer.cpython-37.pyc
--rw-r--r--   0        0        0    19352 2021-12-17 11:45:48.825283 aliby-0.1.8/aliby/io/matlab.py
--rw-r--r--   0        0        0     3807 2022-01-10 12:03:27.952780 aliby-0.1.8/aliby/io/omero.py
--rw-r--r--   0        0        0     1122 2021-12-17 11:45:48.825283 aliby-0.1.8/aliby/io/utils.py
--rw-r--r--   0        0        0      721 2021-12-17 11:45:48.817283 aliby-0.1.8/aliby/multiexperiment.py
--rw-r--r--   0        0        0    12150 2022-01-11 12:05:01.883625 aliby-0.1.8/aliby/pipeline.py
--rw-r--r--   0        0        0     6424 2021-12-17 11:45:48.825283 aliby-0.1.8/aliby/post_processing.py
--rw-r--r--   0        0        0     1010 2021-12-17 11:45:48.825283 aliby-0.1.8/aliby/results.py
--rw-r--r--   0        0        0      146 2022-01-06 19:37:05.746488 aliby-0.1.8/aliby/tests/__pycache__/__init__.cpython-37.pyc
--rw-r--r--   0        0        0     1370 2022-01-06 19:37:05.746488 aliby-0.1.8/aliby/tests/__pycache__/test_integration.cpython-37-pytest-6.2.5.pyc
--rw-r--r--   0        0        0     5780 2022-01-06 19:37:05.750488 aliby-0.1.8/aliby/tests/__pycache__/test_units.cpython-37-pytest-6.2.5.pyc
--rw-r--r--   0        0        0    11308 2022-01-10 13:18:24.055659 aliby-0.1.8/aliby/tile/__pycache__/tiler.cpython-37.pyc
--rw-r--r--   0        0        0    12736 2022-01-10 13:11:51.700211 aliby-0.1.8/aliby/tile/__pycache__/traps.cpython-37.pyc
--rw-r--r--   0        0        0    10709 2022-01-10 13:18:15.279224 aliby-0.1.8/aliby/tile/tiler.py
--rw-r--r--   0        0        0    16800 2022-01-10 13:11:34.479358 aliby-0.1.8/aliby/tile/traps.py
--rw-r--r--   0        0        0    14122 2022-01-07 20:20:39.086806 aliby-0.1.8/aliby/timelapse.py
--rw-r--r--   0        0        0     8578 2021-11-19 13:06:34.814672 aliby-0.1.8/aliby/trap_templates/trap_bg_1.npy
--rw-r--r--   0        0        0     8578 2021-11-19 13:06:34.814672 aliby-0.1.8/aliby/trap_templates/trap_bm_1.npy
--rw-r--r--   0        0        0     8708 2021-11-19 13:06:34.814672 aliby-0.1.8/aliby/trap_templates/trap_bm_2.npy
--rw-r--r--   0        0        0    27506 2021-11-19 13:06:34.814672 aliby-0.1.8/aliby/trap_templates/trap_prime.npy
--rw-r--r--   0        0        0        0 2021-11-19 13:16:59.982275 aliby-0.1.8/aliby/utils/__init__.py
--rw-r--r--   0        0        0    14668 2022-01-03 20:32:57.363983 aliby-0.1.8/aliby/utils/argo.py
--rw-r--r--   0        0        0     3607 2022-01-10 12:03:27.952780 aliby-0.1.8/aliby/utils/cache.py
--rw-r--r--   0        0        0     3344 2021-12-20 13:10:35.150048 aliby-0.1.8/aliby/xaa
--rw-r--r--   0        0        0        0 2022-01-04 18:49:24.660646 aliby-0.1.8/extraction/__init__.py
--rw-r--r--   0        0        0       23 2022-01-04 18:49:24.660646 aliby-0.1.8/extraction/core/__init__.py
--rw-r--r--   0        0        0      150 2022-01-10 13:51:07.517139 aliby-0.1.8/extraction/core/__pycache__/__init__.cpython-37.pyc
--rw-r--r--   0        0        0    16782 2022-01-10 13:51:08.413183 aliby-0.1.8/extraction/core/__pycache__/extractor.cpython-37.pyc
--rw-r--r--   0        0        0     1277 2022-01-10 15:50:49.142198 aliby-0.1.8/extraction/core/__pycache__/lineage.cpython-37-pytest-6.2.5.pyc
--rw-r--r--   0        0        0     1256 2022-01-10 16:11:41.064443 aliby-0.1.8/extraction/core/__pycache__/lineage.cpython-37.pyc
--rw-r--r--   0        0        0    14916 2022-01-10 13:51:07.521139 aliby-0.1.8/extraction/core/__pycache__/tracks.cpython-37.pyc
--rw-r--r--   0        0        0    16773 2022-01-10 12:03:27.952780 aliby-0.1.8/extraction/core/extractor.py
--rw-r--r--   0        0        0       23 2022-01-04 18:49:24.660646 aliby-0.1.8/extraction/core/functions/__init__.py
--rw-r--r--   0        0        0      160 2022-01-10 13:51:08.481186 aliby-0.1.8/extraction/core/functions/__pycache__/__init__.cpython-37.pyc
--rw-r--r--   0        0        0     3858 2022-01-10 13:51:08.481186 aliby-0.1.8/extraction/core/functions/__pycache__/cell.cpython-37.pyc
--rw-r--r--   0        0        0     1766 2022-01-10 13:51:08.553190 aliby-0.1.8/extraction/core/functions/__pycache__/defaults.cpython-37.pyc
--rw-r--r--   0        0        0     1136 2022-01-10 13:51:08.553190 aliby-0.1.8/extraction/core/functions/__pycache__/distributors.cpython-37.pyc
--rw-r--r--   0        0        0     2962 2022-01-10 13:51:08.481186 aliby-0.1.8/extraction/core/functions/__pycache__/loaders.cpython-37.pyc
--rw-r--r--   0        0        0      588 2022-01-10 13:51:08.549190 aliby-0.1.8/extraction/core/functions/__pycache__/math.cpython-37.pyc
--rw-r--r--   0        0        0      596 2022-01-10 13:51:08.541189 aliby-0.1.8/extraction/core/functions/__pycache__/trap.cpython-37.pyc
--rw-r--r--   0        0        0      772 2022-01-10 13:51:08.553190 aliby-0.1.8/extraction/core/functions/__pycache__/utils.cpython-37.pyc
--rw-r--r--   0        0        0     3454 2022-01-04 18:49:24.660646 aliby-0.1.8/extraction/core/functions/cell.py
--rw-r--r--   0        0        0       23 2022-01-04 18:49:24.660646 aliby-0.1.8/extraction/core/functions/custom/__init__.py
--rw-r--r--   0        0        0      167 2022-01-10 13:51:08.545189 aliby-0.1.8/extraction/core/functions/custom/__pycache__/__init__.cpython-37.pyc
--rw-r--r--   0        0        0     3778 2022-01-10 13:51:08.545189 aliby-0.1.8/extraction/core/functions/custom/__pycache__/localisation.cpython-37.pyc
--rw-r--r--   0        0        0     4308 2022-01-04 18:49:24.660646 aliby-0.1.8/extraction/core/functions/custom/localisation.py
--rw-r--r--   0        0        0     1721 2022-01-05 18:13:41.854033 aliby-0.1.8/extraction/core/functions/defaults.py
--rw-r--r--   0        0        0      803 2022-01-04 18:49:24.660646 aliby-0.1.8/extraction/core/functions/distributors.py
--rw-r--r--   0        0        0      227 2022-01-04 18:49:24.660646 aliby-0.1.8/extraction/core/functions/io.py
--rw-r--r--   0        0        0     1841 2022-01-04 18:49:24.660646 aliby-0.1.8/extraction/core/functions/loaders.py
--rw-r--r--   0        0        0      400 2022-01-04 18:49:24.660646 aliby-0.1.8/extraction/core/functions/math.py
--rw-r--r--   0        0        0      444 2022-01-04 18:49:24.660646 aliby-0.1.8/extraction/core/functions/trap.py
--rw-r--r--   0        0        0      472 2022-01-04 18:49:24.660646 aliby-0.1.8/extraction/core/functions/utils.py
--rw-r--r--   0        0        0      236 2022-01-04 18:49:24.660646 aliby-0.1.8/extraction/core/functions/versioning.py
--rw-r--r--   0        0        0     1037 2022-01-10 16:45:19.204712 aliby-0.1.8/extraction/core/lineage.py
--rw-r--r--   0        0        0      622 2022-01-04 18:49:24.660646 aliby-0.1.8/extraction/core/omero.py
--rw-r--r--   0        0        0    16231 2022-01-10 12:03:27.952780 aliby-0.1.8/extraction/core/tracks.py
--rw-r--r--   0        0        0     4443 2022-01-10 16:11:40.496415 aliby-0.1.8/extraction/examples/__pycache__/data.cpython-37.pyc
--rw-r--r--   0        0        0     1043 2022-01-07 20:00:29.030929 aliby-0.1.8/extraction/examples/argo.py
--rw-r--r--   0        0        0     3250 2022-01-04 18:49:24.660646 aliby-0.1.8/extraction/examples/data.py
--rw-r--r--   0        0        0   105676 2022-01-04 18:49:24.660646 aliby-0.1.8/extraction/examples/pairs_data/pos010_trap001_tp0001_Brightfield.png
--rw-r--r--   0        0        0    50315 2022-01-04 18:49:24.660646 aliby-0.1.8/extraction/examples/pairs_data/pos010_trap001_tp0001_GFP.png
--rw-r--r--   0        0        0      334 2022-01-04 18:49:24.660646 aliby-0.1.8/extraction/examples/pairs_data/pos010_trap001_tp0001_segoutlines.png
--rw-r--r--   0        0        0   105956 2022-01-04 18:49:24.660646 aliby-0.1.8/extraction/examples/pairs_data/pos010_trap050_tp0001_Brightfield.png
--rw-r--r--   0        0        0    50326 2022-01-04 18:49:24.660646 aliby-0.1.8/extraction/examples/pairs_data/pos010_trap050_tp0001_GFP.png
--rw-r--r--   0        0        0      520 2022-01-04 18:49:24.660646 aliby-0.1.8/extraction/examples/pairs_data/pos010_trap050_tp0001_segoutlines.png
--rw-r--r--   0        0        0   106877 2022-01-04 18:49:24.660646 aliby-0.1.8/extraction/examples/pairs_data/pos010_trap081_tp0001_Brightfield.png
--rw-r--r--   0        0        0    51273 2022-01-04 18:49:24.660646 aliby-0.1.8/extraction/examples/pairs_data/pos010_trap081_tp0001_GFP.png
--rw-r--r--   0        0        0      651 2022-01-04 18:49:24.660646 aliby-0.1.8/extraction/examples/pairs_data/pos010_trap081_tp0001_segoutlines.png
--rw-r--r--   0        0        0      559 2022-01-04 18:49:24.660646 aliby-0.1.8/extraction/examples/pos_example.py
--rw-r--r--   0        0        0      951 2022-01-04 18:49:24.660646 aliby-0.1.8/extraction/examples/test_pipeline.py
--rw-r--r--   0        0        0     1030 2022-01-04 18:49:24.660646 aliby-0.1.8/extraction/examples/tiler_error.py
--rw-r--r--   0        0        0      985 2022-01-13 18:11:07.394917 aliby-0.1.8/pyproject.toml
--rw-r--r--   0        0        0     1393 2022-01-13 18:30:56.097908 aliby-0.1.8/setup.py
--rw-r--r--   0        0        0     1244 2022-01-13 18:30:56.098155 aliby-0.1.8/PKG-INFO
+-rw-r--r--   0        0        0        0 2021-12-17 11:45:48.817283 aliby-0.1.9/aliby/__init__.py
+-rw-r--r--   0        0        0     8369 2022-01-07 20:20:48.263260 aliby-0.1.9/aliby/baby_client.py
+-rw-r--r--   0        0        0     8733 2021-12-20 14:42:19.602790 aliby-0.1.9/aliby/errors.txt
+-rw-r--r--   0        0        0    17187 2022-01-10 12:03:27.952780 aliby-0.1.9/aliby/experiment.py
+-rw-r--r--   0        0        0    10751 2021-12-17 11:45:48.825283 aliby-0.1.9/aliby/extract.py
+-rw-r--r--   0        0        0     3100 2022-01-07 17:42:57.502877 aliby-0.1.9/aliby/haystack.py
+-rw-r--r--   0        0        0        0 2021-12-17 11:45:48.817283 aliby-0.1.9/aliby/io/__init__.py
+-rw-r--r--   0        0        0      143 2021-12-18 13:36:49.586868 aliby-0.1.9/aliby/io/__pycache__/__init__.cpython-37.pyc
+-rw-r--r--   0        0        0     6717 2021-12-18 13:36:49.590868 aliby-0.1.9/aliby/io/__pycache__/base.cpython-37.pyc
+-rw-r--r--   0        0        0    19198 2021-12-18 13:36:49.662871 aliby-0.1.9/aliby/io/__pycache__/matlab.cpython-37.pyc
+-rw-r--r--   0        0        0     2220 2021-12-20 15:57:54.355267 aliby-0.1.9/aliby/io/__pycache__/metadata_parser.cpython-37.pyc
+-rw-r--r--   0        0        0     5324 2022-01-10 14:47:50.046216 aliby-0.1.9/aliby/io/__pycache__/omero.cpython-37.pyc
+-rw-r--r--   0        0        0     8397 2021-12-18 13:36:49.610869 aliby-0.1.9/aliby/io/__pycache__/signal.cpython-37.pyc
+-rw-r--r--   0        0        0     1787 2021-12-18 13:36:49.670872 aliby-0.1.9/aliby/io/__pycache__/utils.cpython-37.pyc
+-rw-r--r--   0        0        0    14589 2021-12-18 13:36:49.590868 aliby-0.1.9/aliby/io/__pycache__/writer.cpython-37.pyc
+-rw-r--r--   0        0        0    19352 2021-12-17 11:45:48.825283 aliby-0.1.9/aliby/io/matlab.py
+-rw-r--r--   0        0        0     3807 2022-01-10 12:03:27.952780 aliby-0.1.9/aliby/io/omero.py
+-rw-r--r--   0        0        0     1122 2021-12-17 11:45:48.825283 aliby-0.1.9/aliby/io/utils.py
+-rw-r--r--   0        0        0      721 2021-12-17 11:45:48.817283 aliby-0.1.9/aliby/multiexperiment.py
+-rw-r--r--   0        0        0    12150 2022-01-11 12:05:01.883625 aliby-0.1.9/aliby/pipeline.py
+-rw-r--r--   0        0        0     6424 2021-12-17 11:45:48.825283 aliby-0.1.9/aliby/post_processing.py
+-rw-r--r--   0        0        0     1010 2021-12-17 11:45:48.825283 aliby-0.1.9/aliby/results.py
+-rw-r--r--   0        0        0      146 2022-01-06 19:37:05.746488 aliby-0.1.9/aliby/tests/__pycache__/__init__.cpython-37.pyc
+-rw-r--r--   0        0        0     1370 2022-01-06 19:37:05.746488 aliby-0.1.9/aliby/tests/__pycache__/test_integration.cpython-37-pytest-6.2.5.pyc
+-rw-r--r--   0        0        0     5780 2022-01-06 19:37:05.750488 aliby-0.1.9/aliby/tests/__pycache__/test_units.cpython-37-pytest-6.2.5.pyc
+-rw-r--r--   0        0        0    11308 2022-01-10 13:18:24.055659 aliby-0.1.9/aliby/tile/__pycache__/tiler.cpython-37.pyc
+-rw-r--r--   0        0        0    12736 2022-01-10 13:11:51.700211 aliby-0.1.9/aliby/tile/__pycache__/traps.cpython-37.pyc
+-rw-r--r--   0        0        0    10709 2022-01-10 13:18:15.279224 aliby-0.1.9/aliby/tile/tiler.py
+-rw-r--r--   0        0        0    16800 2022-01-10 13:11:34.479358 aliby-0.1.9/aliby/tile/traps.py
+-rw-r--r--   0        0        0    14122 2022-01-07 20:20:39.086806 aliby-0.1.9/aliby/timelapse.py
+-rw-r--r--   0        0        0     8578 2021-11-19 13:06:34.814672 aliby-0.1.9/aliby/trap_templates/trap_bg_1.npy
+-rw-r--r--   0        0        0     8578 2021-11-19 13:06:34.814672 aliby-0.1.9/aliby/trap_templates/trap_bm_1.npy
+-rw-r--r--   0        0        0     8708 2021-11-19 13:06:34.814672 aliby-0.1.9/aliby/trap_templates/trap_bm_2.npy
+-rw-r--r--   0        0        0    27506 2021-11-19 13:06:34.814672 aliby-0.1.9/aliby/trap_templates/trap_prime.npy
+-rw-r--r--   0        0        0        0 2021-11-19 13:16:59.982275 aliby-0.1.9/aliby/utils/__init__.py
+-rw-r--r--   0        0        0    14668 2022-01-03 20:32:57.363983 aliby-0.1.9/aliby/utils/argo.py
+-rw-r--r--   0        0        0     3607 2022-01-10 12:03:27.952780 aliby-0.1.9/aliby/utils/cache.py
+-rw-r--r--   0        0        0     3344 2021-12-20 13:10:35.150048 aliby-0.1.9/aliby/xaa
+-rw-r--r--   0        0        0        0 2022-01-04 18:49:24.660646 aliby-0.1.9/extraction/__init__.py
+-rw-r--r--   0        0        0       23 2022-01-04 18:49:24.660646 aliby-0.1.9/extraction/core/__init__.py
+-rw-r--r--   0        0        0      150 2022-01-10 13:51:07.517139 aliby-0.1.9/extraction/core/__pycache__/__init__.cpython-37.pyc
+-rw-r--r--   0        0        0    16782 2022-01-10 13:51:08.413183 aliby-0.1.9/extraction/core/__pycache__/extractor.cpython-37.pyc
+-rw-r--r--   0        0        0     1277 2022-01-10 15:50:49.142198 aliby-0.1.9/extraction/core/__pycache__/lineage.cpython-37-pytest-6.2.5.pyc
+-rw-r--r--   0        0        0     1256 2022-01-10 16:11:41.064443 aliby-0.1.9/extraction/core/__pycache__/lineage.cpython-37.pyc
+-rw-r--r--   0        0        0    14916 2022-01-10 13:51:07.521139 aliby-0.1.9/extraction/core/__pycache__/tracks.cpython-37.pyc
+-rw-r--r--   0        0        0    16773 2022-01-10 12:03:27.952780 aliby-0.1.9/extraction/core/extractor.py
+-rw-r--r--   0        0        0       23 2022-01-04 18:49:24.660646 aliby-0.1.9/extraction/core/functions/__init__.py
+-rw-r--r--   0        0        0      160 2022-01-10 13:51:08.481186 aliby-0.1.9/extraction/core/functions/__pycache__/__init__.cpython-37.pyc
+-rw-r--r--   0        0        0     3858 2022-01-10 13:51:08.481186 aliby-0.1.9/extraction/core/functions/__pycache__/cell.cpython-37.pyc
+-rw-r--r--   0        0        0     1766 2022-01-10 13:51:08.553190 aliby-0.1.9/extraction/core/functions/__pycache__/defaults.cpython-37.pyc
+-rw-r--r--   0        0        0     1136 2022-01-10 13:51:08.553190 aliby-0.1.9/extraction/core/functions/__pycache__/distributors.cpython-37.pyc
+-rw-r--r--   0        0        0     2962 2022-01-10 13:51:08.481186 aliby-0.1.9/extraction/core/functions/__pycache__/loaders.cpython-37.pyc
+-rw-r--r--   0        0        0      588 2022-01-10 13:51:08.549190 aliby-0.1.9/extraction/core/functions/__pycache__/math.cpython-37.pyc
+-rw-r--r--   0        0        0      596 2022-01-10 13:51:08.541189 aliby-0.1.9/extraction/core/functions/__pycache__/trap.cpython-37.pyc
+-rw-r--r--   0        0        0      772 2022-01-10 13:51:08.553190 aliby-0.1.9/extraction/core/functions/__pycache__/utils.cpython-37.pyc
+-rw-r--r--   0        0        0     3454 2022-01-04 18:49:24.660646 aliby-0.1.9/extraction/core/functions/cell.py
+-rw-r--r--   0        0        0       23 2022-01-04 18:49:24.660646 aliby-0.1.9/extraction/core/functions/custom/__init__.py
+-rw-r--r--   0        0        0      167 2022-01-10 13:51:08.545189 aliby-0.1.9/extraction/core/functions/custom/__pycache__/__init__.cpython-37.pyc
+-rw-r--r--   0        0        0     3778 2022-01-10 13:51:08.545189 aliby-0.1.9/extraction/core/functions/custom/__pycache__/localisation.cpython-37.pyc
+-rw-r--r--   0        0        0     4308 2022-01-04 18:49:24.660646 aliby-0.1.9/extraction/core/functions/custom/localisation.py
+-rw-r--r--   0        0        0     1721 2022-01-05 18:13:41.854033 aliby-0.1.9/extraction/core/functions/defaults.py
+-rw-r--r--   0        0        0      803 2022-01-04 18:49:24.660646 aliby-0.1.9/extraction/core/functions/distributors.py
+-rw-r--r--   0        0        0      227 2022-01-04 18:49:24.660646 aliby-0.1.9/extraction/core/functions/io.py
+-rw-r--r--   0        0        0     1841 2022-01-04 18:49:24.660646 aliby-0.1.9/extraction/core/functions/loaders.py
+-rw-r--r--   0        0        0      400 2022-01-04 18:49:24.660646 aliby-0.1.9/extraction/core/functions/math.py
+-rw-r--r--   0        0        0      444 2022-01-04 18:49:24.660646 aliby-0.1.9/extraction/core/functions/trap.py
+-rw-r--r--   0        0        0      472 2022-01-04 18:49:24.660646 aliby-0.1.9/extraction/core/functions/utils.py
+-rw-r--r--   0        0        0      236 2022-01-04 18:49:24.660646 aliby-0.1.9/extraction/core/functions/versioning.py
+-rw-r--r--   0        0        0     1037 2022-01-10 16:45:19.204712 aliby-0.1.9/extraction/core/lineage.py
+-rw-r--r--   0        0        0      622 2022-01-04 18:49:24.660646 aliby-0.1.9/extraction/core/omero.py
+-rw-r--r--   0        0        0    16231 2022-01-10 12:03:27.952780 aliby-0.1.9/extraction/core/tracks.py
+-rw-r--r--   0        0        0     4443 2022-01-10 16:11:40.496415 aliby-0.1.9/extraction/examples/__pycache__/data.cpython-37.pyc
+-rw-r--r--   0        0        0     1043 2022-01-07 20:00:29.030929 aliby-0.1.9/extraction/examples/argo.py
+-rw-r--r--   0        0        0     3250 2022-01-04 18:49:24.660646 aliby-0.1.9/extraction/examples/data.py
+-rw-r--r--   0        0        0   105676 2022-01-04 18:49:24.660646 aliby-0.1.9/extraction/examples/pairs_data/pos010_trap001_tp0001_Brightfield.png
+-rw-r--r--   0        0        0    50315 2022-01-04 18:49:24.660646 aliby-0.1.9/extraction/examples/pairs_data/pos010_trap001_tp0001_GFP.png
+-rw-r--r--   0        0        0      334 2022-01-04 18:49:24.660646 aliby-0.1.9/extraction/examples/pairs_data/pos010_trap001_tp0001_segoutlines.png
+-rw-r--r--   0        0        0   105956 2022-01-04 18:49:24.660646 aliby-0.1.9/extraction/examples/pairs_data/pos010_trap050_tp0001_Brightfield.png
+-rw-r--r--   0        0        0    50326 2022-01-04 18:49:24.660646 aliby-0.1.9/extraction/examples/pairs_data/pos010_trap050_tp0001_GFP.png
+-rw-r--r--   0        0        0      520 2022-01-04 18:49:24.660646 aliby-0.1.9/extraction/examples/pairs_data/pos010_trap050_tp0001_segoutlines.png
+-rw-r--r--   0        0        0   106877 2022-01-04 18:49:24.660646 aliby-0.1.9/extraction/examples/pairs_data/pos010_trap081_tp0001_Brightfield.png
+-rw-r--r--   0        0        0    51273 2022-01-04 18:49:24.660646 aliby-0.1.9/extraction/examples/pairs_data/pos010_trap081_tp0001_GFP.png
+-rw-r--r--   0        0        0      651 2022-01-04 18:49:24.660646 aliby-0.1.9/extraction/examples/pairs_data/pos010_trap081_tp0001_segoutlines.png
+-rw-r--r--   0        0        0      559 2022-01-04 18:49:24.660646 aliby-0.1.9/extraction/examples/pos_example.py
+-rw-r--r--   0        0        0      951 2022-01-04 18:49:24.660646 aliby-0.1.9/extraction/examples/test_pipeline.py
+-rw-r--r--   0        0        0     1030 2022-01-04 18:49:24.660646 aliby-0.1.9/extraction/examples/tiler_error.py
+-rw-r--r--   0        0        0      985 2022-01-18 12:06:18.691325 aliby-0.1.9/pyproject.toml
+-rw-r--r--   0        0        0     1393 2022-01-18 12:06:24.857478 aliby-0.1.9/setup.py
+-rw-r--r--   0        0        0     1244 2022-01-18 12:06:24.857744 aliby-0.1.9/PKG-INFO
```

### Comparing `aliby-0.1.8/aliby/baby_client.py` & `aliby-0.1.9/aliby/baby_client.py`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/aliby/errors.txt` & `aliby-0.1.9/aliby/errors.txt`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/aliby/experiment.py` & `aliby-0.1.9/aliby/experiment.py`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/aliby/extract.py` & `aliby-0.1.9/aliby/extract.py`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/aliby/haystack.py` & `aliby-0.1.9/aliby/haystack.py`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/aliby/io/__pycache__/base.cpython-37.pyc` & `aliby-0.1.9/aliby/io/__pycache__/base.cpython-37.pyc`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/aliby/io/__pycache__/matlab.cpython-37.pyc` & `aliby-0.1.9/aliby/io/__pycache__/matlab.cpython-37.pyc`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/aliby/io/__pycache__/metadata_parser.cpython-37.pyc` & `aliby-0.1.9/aliby/io/__pycache__/metadata_parser.cpython-37.pyc`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/aliby/io/__pycache__/omero.cpython-37.pyc` & `aliby-0.1.9/aliby/io/__pycache__/omero.cpython-37.pyc`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/aliby/io/__pycache__/signal.cpython-37.pyc` & `aliby-0.1.9/aliby/io/__pycache__/signal.cpython-37.pyc`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/aliby/io/__pycache__/utils.cpython-37.pyc` & `aliby-0.1.9/aliby/io/__pycache__/utils.cpython-37.pyc`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/aliby/io/__pycache__/writer.cpython-37.pyc` & `aliby-0.1.9/aliby/io/__pycache__/writer.cpython-37.pyc`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/aliby/io/matlab.py` & `aliby-0.1.9/aliby/io/matlab.py`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/aliby/io/omero.py` & `aliby-0.1.9/aliby/io/omero.py`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/aliby/io/utils.py` & `aliby-0.1.9/aliby/io/utils.py`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/aliby/multiexperiment.py` & `aliby-0.1.9/aliby/multiexperiment.py`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/aliby/pipeline.py` & `aliby-0.1.9/aliby/pipeline.py`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/aliby/post_processing.py` & `aliby-0.1.9/aliby/post_processing.py`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/aliby/results.py` & `aliby-0.1.9/aliby/results.py`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/aliby/tests/__pycache__/test_integration.cpython-37-pytest-6.2.5.pyc` & `aliby-0.1.9/aliby/tests/__pycache__/test_integration.cpython-37-pytest-6.2.5.pyc`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/aliby/tests/__pycache__/test_units.cpython-37-pytest-6.2.5.pyc` & `aliby-0.1.9/aliby/tests/__pycache__/test_units.cpython-37-pytest-6.2.5.pyc`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/aliby/tile/__pycache__/tiler.cpython-37.pyc` & `aliby-0.1.9/aliby/tile/__pycache__/tiler.cpython-37.pyc`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/aliby/tile/__pycache__/traps.cpython-37.pyc` & `aliby-0.1.9/aliby/tile/__pycache__/traps.cpython-37.pyc`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/aliby/tile/tiler.py` & `aliby-0.1.9/aliby/tile/tiler.py`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/aliby/tile/traps.py` & `aliby-0.1.9/aliby/tile/traps.py`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/aliby/timelapse.py` & `aliby-0.1.9/aliby/timelapse.py`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/aliby/trap_templates/trap_bg_1.npy` & `aliby-0.1.9/aliby/trap_templates/trap_bg_1.npy`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/aliby/trap_templates/trap_bm_1.npy` & `aliby-0.1.9/aliby/trap_templates/trap_bm_1.npy`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/aliby/trap_templates/trap_bm_2.npy` & `aliby-0.1.9/aliby/trap_templates/trap_bm_2.npy`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/aliby/trap_templates/trap_prime.npy` & `aliby-0.1.9/aliby/trap_templates/trap_prime.npy`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/aliby/utils/argo.py` & `aliby-0.1.9/aliby/utils/argo.py`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/aliby/utils/cache.py` & `aliby-0.1.9/aliby/utils/cache.py`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/aliby/xaa` & `aliby-0.1.9/aliby/xaa`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/core/__pycache__/extractor.cpython-37.pyc` & `aliby-0.1.9/extraction/core/__pycache__/extractor.cpython-37.pyc`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/core/__pycache__/lineage.cpython-37-pytest-6.2.5.pyc` & `aliby-0.1.9/extraction/core/__pycache__/lineage.cpython-37-pytest-6.2.5.pyc`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/core/__pycache__/lineage.cpython-37.pyc` & `aliby-0.1.9/extraction/core/__pycache__/lineage.cpython-37.pyc`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/core/__pycache__/tracks.cpython-37.pyc` & `aliby-0.1.9/extraction/core/__pycache__/tracks.cpython-37.pyc`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/core/extractor.py` & `aliby-0.1.9/extraction/core/extractor.py`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/core/functions/__pycache__/cell.cpython-37.pyc` & `aliby-0.1.9/extraction/core/functions/__pycache__/cell.cpython-37.pyc`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/core/functions/__pycache__/defaults.cpython-37.pyc` & `aliby-0.1.9/extraction/core/functions/__pycache__/defaults.cpython-37.pyc`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/core/functions/__pycache__/distributors.cpython-37.pyc` & `aliby-0.1.9/extraction/core/functions/__pycache__/distributors.cpython-37.pyc`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/core/functions/__pycache__/loaders.cpython-37.pyc` & `aliby-0.1.9/extraction/core/functions/__pycache__/loaders.cpython-37.pyc`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/core/functions/__pycache__/math.cpython-37.pyc` & `aliby-0.1.9/extraction/core/functions/__pycache__/math.cpython-37.pyc`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/core/functions/__pycache__/trap.cpython-37.pyc` & `aliby-0.1.9/extraction/core/functions/__pycache__/trap.cpython-37.pyc`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/core/functions/__pycache__/utils.cpython-37.pyc` & `aliby-0.1.9/extraction/core/functions/__pycache__/utils.cpython-37.pyc`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/core/functions/cell.py` & `aliby-0.1.9/extraction/core/functions/cell.py`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/core/functions/custom/__pycache__/localisation.cpython-37.pyc` & `aliby-0.1.9/extraction/core/functions/custom/__pycache__/localisation.cpython-37.pyc`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/core/functions/custom/localisation.py` & `aliby-0.1.9/extraction/core/functions/custom/localisation.py`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/core/functions/defaults.py` & `aliby-0.1.9/extraction/core/functions/defaults.py`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/core/functions/distributors.py` & `aliby-0.1.9/extraction/core/functions/distributors.py`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/core/functions/loaders.py` & `aliby-0.1.9/extraction/core/functions/loaders.py`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/core/lineage.py` & `aliby-0.1.9/extraction/core/lineage.py`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/core/omero.py` & `aliby-0.1.9/extraction/core/omero.py`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/core/tracks.py` & `aliby-0.1.9/extraction/core/tracks.py`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/examples/__pycache__/data.cpython-37.pyc` & `aliby-0.1.9/extraction/examples/__pycache__/data.cpython-37.pyc`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/examples/argo.py` & `aliby-0.1.9/extraction/examples/argo.py`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/examples/data.py` & `aliby-0.1.9/extraction/examples/data.py`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/examples/pairs_data/pos010_trap001_tp0001_Brightfield.png` & `aliby-0.1.9/extraction/examples/pairs_data/pos010_trap001_tp0001_Brightfield.png`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/examples/pairs_data/pos010_trap001_tp0001_GFP.png` & `aliby-0.1.9/extraction/examples/pairs_data/pos010_trap001_tp0001_GFP.png`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/examples/pairs_data/pos010_trap050_tp0001_Brightfield.png` & `aliby-0.1.9/extraction/examples/pairs_data/pos010_trap050_tp0001_Brightfield.png`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/examples/pairs_data/pos010_trap050_tp0001_GFP.png` & `aliby-0.1.9/extraction/examples/pairs_data/pos010_trap050_tp0001_GFP.png`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/examples/pairs_data/pos010_trap050_tp0001_segoutlines.png` & `aliby-0.1.9/extraction/examples/pairs_data/pos010_trap050_tp0001_segoutlines.png`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/examples/pairs_data/pos010_trap081_tp0001_Brightfield.png` & `aliby-0.1.9/extraction/examples/pairs_data/pos010_trap081_tp0001_Brightfield.png`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/examples/pairs_data/pos010_trap081_tp0001_GFP.png` & `aliby-0.1.9/extraction/examples/pairs_data/pos010_trap081_tp0001_GFP.png`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/examples/pairs_data/pos010_trap081_tp0001_segoutlines.png` & `aliby-0.1.9/extraction/examples/pairs_data/pos010_trap081_tp0001_segoutlines.png`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/examples/pos_example.py` & `aliby-0.1.9/extraction/examples/pos_example.py`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/examples/test_pipeline.py` & `aliby-0.1.9/extraction/examples/test_pipeline.py`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/extraction/examples/tiler_error.py` & `aliby-0.1.9/extraction/examples/tiler_error.py`

 * *Files identical despite different names*

### Comparing `aliby-0.1.8/pyproject.toml` & `aliby-0.1.9/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "aliby"
-version = "0.1.8"
+version = "0.1.9"
 description = ""
 authors = ["Alan Munoz <alan.munoz@ed.ac.uk>"]
 packages = [
     { include = "aliby" },
     { include = "extraction" },
 ]
 
@@ -27,15 +27,15 @@
 imageio = "2.8.0"
 omero-py = ">=5.6.2"
 zeroc-ice = "3.6.5"
 tensorflow = ">=1.15,<=2.3"
 aliby-agora = "^0.2.4"
 aliby-baby = "^0.1.2"
 omni-gaussian = "^0.1.1"
-aliby-post = "^0.1.2"
+aliby-post = "^0.1.4"
 
 
 [tool.poetry.dev-dependencies]
 data-science-types = "^0.2.23"
 black = "^21.12b0"
 Sphinx = "^4.3.2"
 pytest = "^6.2.5"
```

### Comparing `aliby-0.1.8/setup.py` & `aliby-0.1.9/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -16,15 +16,15 @@
 {'': ['*'],
  'aliby': ['trap_templates/*'],
  'extraction.examples': ['pairs_data/*']}
 
 install_requires = \
 ['aliby-agora>=0.2.4,<0.3.0',
  'aliby-baby>=0.1.2,<0.2.0',
- 'aliby-post>=0.1.2,<0.2.0',
+ 'aliby-post>=0.1.4,<0.2.0',
  'dask>=2021.12.0,<2022.0.0',
  'h5py==2.10',
  'imageio==2.8.0',
  'more-itertools>=8.12.0,<9.0.0',
  'numpy>=1.21.4,<2.0.0',
  'omero-py>=5.6.2',
  'omni-gaussian>=0.1.1,<0.2.0',
@@ -39,15 +39,15 @@
  'tables>=3.6.1,<4.0.0',
  'tensorflow>=1.15,<=2.3',
  'tqdm>=4.62.3,<5.0.0',
  'zeroc-ice==3.6.5']
 
 setup_kwargs = {
     'name': 'aliby',
-    'version': '0.1.8',
+    'version': '0.1.9',
     'description': '',
     'long_description': None,
     'author': 'Alan Munoz',
     'author_email': 'alan.munoz@ed.ac.uk',
     'maintainer': None,
     'maintainer_email': None,
     'url': None,
```

### Comparing `aliby-0.1.8/PKG-INFO` & `aliby-0.1.9/PKG-INFO`

 * *Files 7% similar despite different names*

```diff
@@ -1,21 +1,21 @@
 Metadata-Version: 2.1
 Name: aliby
-Version: 0.1.8
+Version: 0.1.9
 Summary: 
 Author: Alan Munoz
 Author-email: alan.munoz@ed.ac.uk
 Requires-Python: >=3.7.1,<3.11
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Requires-Dist: aliby-agora (>=0.2.4,<0.3.0)
 Requires-Dist: aliby-baby (>=0.1.2,<0.2.0)
-Requires-Dist: aliby-post (>=0.1.2,<0.2.0)
+Requires-Dist: aliby-post (>=0.1.4,<0.2.0)
 Requires-Dist: dask (>=2021.12.0,<2022.0.0)
 Requires-Dist: h5py (==2.10)
 Requires-Dist: imageio (==2.8.0)
 Requires-Dist: more-itertools (>=8.12.0,<9.0.0)
 Requires-Dist: numpy (>=1.21.4,<2.0.0)
 Requires-Dist: omero-py (>=5.6.2)
 Requires-Dist: omni-gaussian (>=0.1.1,<0.2.0)
```


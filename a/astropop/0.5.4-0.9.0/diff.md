# Comparing `tmp/astropop-0.5.4.tar.gz` & `tmp/astropop-0.9.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "astropop-0.5.4.tar", last modified: Mon Aug 15 01:47:59 2022, max compression
+gzip compressed data, was "astropop-0.9.0.tar", last modified: Wed Jun 28 00:38:02 2023, max compression
```

## Comparing `astropop-0.5.4.tar` & `astropop-0.9.0.tar`

### file list

```diff
@@ -1,145 +1,167 @@
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-08-15 01:47:59.689330 astropop-0.5.4/
--rw-r--r--   0 runner    (1001) docker     (121)      179 2022-08-15 01:47:47.000000 astropop-0.5.4/.codacy.yml
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-08-15 01:47:59.657330 astropop-0.5.4/.github/
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-08-15 01:47:59.661330 astropop-0.5.4/.github/workflows/
--rw-r--r--   0 runner    (1001) docker     (121)     1101 2022-08-15 01:47:47.000000 astropop-0.5.4/.github/workflows/build-n-publish.yml
--rw-r--r--   0 runner    (1001) docker     (121)     4460 2022-08-15 01:47:47.000000 astropop-0.5.4/.github/workflows/code_quality_analysis.yml
--rw-r--r--   0 runner    (1001) docker     (121)     4926 2022-08-15 01:47:47.000000 astropop-0.5.4/.github/workflows/unit-tests.yml
--rw-r--r--   0 runner    (1001) docker     (121)     1916 2022-08-15 01:47:47.000000 astropop-0.5.4/.gitignore
--rw-r--r--   0 runner    (1001) docker     (121)      170 2022-08-15 01:47:47.000000 astropop-0.5.4/.readthedocs.yml
--rw-r--r--   0 runner    (1001) docker     (121)      298 2022-08-15 01:47:47.000000 astropop-0.5.4/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (121)     5438 2022-08-15 01:47:59.689330 astropop-0.5.4/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (121)     5033 2022-08-15 01:47:47.000000 astropop-0.5.4/README.rst
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-08-15 01:47:59.665330 astropop-0.5.4/astropop/
--rw-r--r--   0 runner    (1001) docker     (121)      370 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/__init__.py
--rw-r--r--   0 runner    (1001) docker     (121)     1635 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/_astropy_init.py
--rw-r--r--   0 runner    (1001) docker     (121)    33131 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/_db.py
--rw-r--r--   0 runner    (1001) docker     (121)      677 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/_unit_property.py
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-08-15 01:47:59.665330 astropop-0.5.4/astropop/astrometry/
--rw-r--r--   0 runner    (1001) docker     (121)      646 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/astrometry/__init__.py
--rw-r--r--   0 runner    (1001) docker     (121)    15043 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/astrometry/astrometrynet.py
--rw-r--r--   0 runner    (1001) docker     (121)     1475 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/astrometry/coords_utils.py
--rw-r--r--   0 runner    (1001) docker     (121)     2351 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/astrometry/manual_wcs.py
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-08-15 01:47:59.665330 astropop-0.5.4/astropop/catalogs/
--rw-r--r--   0 runner    (1001) docker     (121)     1096 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/catalogs/__init__.py
--rw-r--r--   0 runner    (1001) docker     (121)     3493 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/catalogs/_online_tools.py
--rw-r--r--   0 runner    (1001) docker     (121)     7039 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/catalogs/base_catalog.py
--rw-r--r--   0 runner    (1001) docker     (121)     5878 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/catalogs/local.py
--rw-r--r--   0 runner    (1001) docker     (121)     6375 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/catalogs/simbad.py
--rw-r--r--   0 runner    (1001) docker     (121)     1800 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/catalogs/utils.py
--rw-r--r--   0 runner    (1001) docker     (121)     8280 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/catalogs/vizier.py
--rw-r--r--   0 runner    (1001) docker     (121)    11015 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/file_collection.py
--rw-r--r--   0 runner    (1001) docker     (121)     1840 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/fits_utils.py
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-08-15 01:47:59.669330 astropop-0.5.4/astropop/framedata/
--rw-r--r--   0 runner    (1001) docker     (121)      419 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/framedata/__init__.py
--rw-r--r--   0 runner    (1001) docker     (121)     9543 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/framedata/compat.py
--rw-r--r--   0 runner    (1001) docker     (121)    19047 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/framedata/framedata.py
--rw-r--r--   0 runner    (1001) docker     (121)    12356 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/framedata/memmap.py
--rw-r--r--   0 runner    (1001) docker     (121)     2520 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/framedata/util.py
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-08-15 01:47:59.669330 astropop-0.5.4/astropop/image/
--rw-r--r--   0 runner    (1001) docker     (121)      223 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/image/__init__.py
--rw-r--r--   0 runner    (1001) docker     (121)     4408 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/image/imarith.py
--rw-r--r--   0 runner    (1001) docker     (121)    25977 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/image/imcombine.py
--rw-r--r--   0 runner    (1001) docker     (121)    11038 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/image/processing.py
--rw-r--r--   0 runner    (1001) docker     (121)    19316 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/image/register.py
--rw-r--r--   0 runner    (1001) docker     (121)     2287 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/logger.py
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-08-15 01:47:59.669330 astropop-0.5.4/astropop/math/
--rw-r--r--   0 runner    (1001) docker     (121)      161 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/math/__init__.py
--rw-r--r--   0 runner    (1001) docker     (121)     7082 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/math/_deriv.py
--rw-r--r--   0 runner    (1001) docker     (121)     1479 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/math/array.py
--rw-r--r--   0 runner    (1001) docker     (121)     2895 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/math/gaussian.py
--rw-r--r--   0 runner    (1001) docker     (121)      528 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/math/hasher.py
--rw-r--r--   0 runner    (1001) docker     (121)     2808 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/math/moffat.py
--rw-r--r--   0 runner    (1001) docker     (121)    33073 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/math/physical.py
--rw-r--r--   0 runner    (1001) docker     (121)     1657 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/math/reproject.py
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-08-15 01:47:59.673330 astropop-0.5.4/astropop/photometry/
--rw-r--r--   0 runner    (1001) docker     (121)      901 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/photometry/__init__.py
--rw-r--r--   0 runner    (1001) docker     (121)      638 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/photometry/_utils.py
--rw-r--r--   0 runner    (1001) docker     (121)     7089 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/photometry/aperture.py
--rw-r--r--   0 runner    (1001) docker     (121)    27048 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/photometry/detection.py
--rw-r--r--   0 runner    (1001) docker     (121)     4888 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/photometry/solve_photometry.py
--rw-r--r--   0 runner    (1001) docker     (121)    24846 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/pipelines.py
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-08-15 01:47:59.673330 astropop-0.5.4/astropop/polarimetry/
--rw-r--r--   0 runner    (1001) docker     (121)      306 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/polarimetry/__init__.py
--rw-r--r--   0 runner    (1001) docker     (121)    14936 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/polarimetry/dualbeam.py
--rw-r--r--   0 runner    (1001) docker     (121)     8662 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/py_utils.py
--rw-r--r--   0 runner    (1001) docker     (121)     5966 2022-08-15 01:47:47.000000 astropop-0.5.4/astropop/testing.py
--rw-r--r--   0 runner    (1001) docker     (121)      337 2022-08-15 01:47:59.000000 astropop-0.5.4/astropop/version.py
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-08-15 01:47:59.665330 astropop-0.5.4/astropop.egg-info/
--rw-r--r--   0 runner    (1001) docker     (121)     5438 2022-08-15 01:47:59.000000 astropop-0.5.4/astropop.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (121)     3081 2022-08-15 01:47:59.000000 astropop-0.5.4/astropop.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (121)        1 2022-08-15 01:47:59.000000 astropop-0.5.4/astropop.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (121)        1 2022-08-15 01:47:59.000000 astropop-0.5.4/astropop.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (121)      309 2022-08-15 01:47:59.000000 astropop-0.5.4/astropop.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (121)        9 2022-08-15 01:47:59.000000 astropop-0.5.4/astropop.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (121)       89 2022-08-15 01:47:47.000000 astropop-0.5.4/codecov.yml
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-08-15 01:47:59.677330 astropop-0.5.4/docs/
--rw-r--r--   0 runner    (1001) docker     (121)     4581 2022-08-15 01:47:47.000000 astropop-0.5.4/docs/Makefile
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-08-15 01:47:59.657330 astropop-0.5.4/docs/_templates/
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-08-15 01:47:59.677330 astropop-0.5.4/docs/_templates/autosummary/
--rw-r--r--   0 runner    (1001) docker     (121)      160 2022-08-15 01:47:47.000000 astropop-0.5.4/docs/_templates/autosummary/base.rst
--rw-r--r--   0 runner    (1001) docker     (121)      637 2022-08-15 01:47:47.000000 astropop-0.5.4/docs/_templates/autosummary/class.rst
--rw-r--r--   0 runner    (1001) docker     (121)      157 2022-08-15 01:47:47.000000 astropop-0.5.4/docs/_templates/autosummary/exception.rst
--rw-r--r--   0 runner    (1001) docker     (121)      208 2022-08-15 01:47:47.000000 astropop-0.5.4/docs/_templates/autosummary/function.rst
--rw-r--r--   0 runner    (1001) docker     (121)      781 2022-08-15 01:47:47.000000 astropop-0.5.4/docs/_templates/autosummary/module.rst
--rw-r--r--   0 runner    (1001) docker     (121)     1791 2022-08-15 01:47:47.000000 astropop-0.5.4/docs/api.rst
--rw-r--r--   0 runner    (1001) docker     (121)      178 2022-08-15 01:47:47.000000 astropop-0.5.4/docs/astrometry.rst
--rw-r--r--   0 runner    (1001) docker     (121)      132 2022-08-15 01:47:47.000000 astropop-0.5.4/docs/catalogs.rst
--rw-r--r--   0 runner    (1001) docker     (121)      163 2022-08-15 01:47:47.000000 astropop-0.5.4/docs/ccdprocessing.rst
--rw-r--r--   0 runner    (1001) docker     (121)     1919 2022-08-15 01:47:47.000000 astropop-0.5.4/docs/conf.py
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-08-15 01:47:59.677330 astropop-0.5.4/docs/dev/
--rw-r--r--   0 runner    (1001) docker     (121)     1682 2022-08-15 01:47:47.000000 astropop-0.5.4/docs/dev/pixel_convention.rst
--rw-r--r--   0 runner    (1001) docker     (121)      162 2022-08-15 01:47:47.000000 astropop-0.5.4/docs/files.rst
--rw-r--r--   0 runner    (1001) docker     (121)      150 2022-08-15 01:47:47.000000 astropop-0.5.4/docs/fits_utils.rst
--rw-r--r--   0 runner    (1001) docker     (121)      909 2022-08-15 01:47:47.000000 astropop-0.5.4/docs/framedata.rst
--rw-r--r--   0 runner    (1001) docker     (121)     1222 2022-08-15 01:47:47.000000 astropop-0.5.4/docs/imarith.rst
--rw-r--r--   0 runner    (1001) docker     (121)     1084 2022-08-15 01:47:47.000000 astropop-0.5.4/docs/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-08-15 01:47:59.677330 astropop-0.5.4/docs/ipynb/
--rw-r--r--   0 runner    (1001) docker     (121)    15966 2022-08-15 01:47:47.000000 astropop-0.5.4/docs/ipynb/diy_reduction_script.ipynb
--rw-r--r--   0 runner    (1001) docker     (121)     1807 2022-08-15 01:47:47.000000 astropop-0.5.4/docs/logger.rst
--rw-r--r--   0 runner    (1001) docker     (121)     4549 2022-08-15 01:47:47.000000 astropop-0.5.4/docs/make.bat
--rw-r--r--   0 runner    (1001) docker     (121)     2200 2022-08-15 01:47:47.000000 astropop-0.5.4/docs/memmap.rst
--rw-r--r--   0 runner    (1001) docker     (121)      154 2022-08-15 01:47:47.000000 astropop-0.5.4/docs/photometry.rst
--rw-r--r--   0 runner    (1001) docker     (121)    14933 2022-08-15 01:47:47.000000 astropop-0.5.4/docs/physical.rst
--rw-r--r--   0 runner    (1001) docker     (121)      138 2022-08-15 01:47:47.000000 astropop-0.5.4/docs/pipelines.rst
--rw-r--r--   0 runner    (1001) docker     (121)      158 2022-08-15 01:47:47.000000 astropop-0.5.4/docs/polarimetry.rst
--rw-r--r--   0 runner    (1001) docker     (121)      152 2022-08-15 01:47:47.000000 astropop-0.5.4/docs/py_utils.rst
--rw-r--r--   0 runner    (1001) docker     (121)      878 2022-08-15 01:47:47.000000 astropop-0.5.4/docs/references.txt
--rw-r--r--   0 runner    (1001) docker     (121)      177 2022-08-15 01:47:47.000000 astropop-0.5.4/docs/registering.rst
--rw-r--r--   0 runner    (1001) docker     (121)     2080 2022-08-15 01:47:47.000000 astropop-0.5.4/docs/testing.rst
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-08-15 01:47:59.677330 astropop-0.5.4/licenses/
--rw-r--r--   0 runner    (1001) docker     (121)     1481 2022-08-15 01:47:47.000000 astropop-0.5.4/licenses/LICENSE.rst
--rw-r--r--   0 runner    (1001) docker     (121)     1659 2022-08-15 01:47:47.000000 astropop-0.5.4/licenses/TEMPLATE_LICENCE.rst
--rw-r--r--   0 runner    (1001) docker     (121)      198 2022-08-15 01:47:47.000000 astropop-0.5.4/pyproject.toml
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-08-15 01:47:59.677330 astropop-0.5.4/scripts/
--rw-r--r--   0 runner    (1001) docker     (121)      989 2022-08-15 01:47:47.000000 astropop-0.5.4/scripts/fitsheader_set
--rw-r--r--   0 runner    (1001) docker     (121)     1850 2022-08-15 01:47:59.689330 astropop-0.5.4/setup.cfg
--rwxr-xr-x   0 runner    (1001) docker     (121)     2052 2022-08-15 01:47:47.000000 astropop-0.5.4/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-08-15 01:47:59.689330 astropop-0.5.4/tests/
--rw-r--r--   0 runner    (1001) docker     (121)        0 2022-08-15 01:47:47.000000 astropop-0.5.4/tests/__init__.py
--rw-r--r--   0 runner    (1001) docker     (121)       49 2022-08-15 01:47:47.000000 astropop-0.5.4/tests/conftest.py
--rw-r--r--   0 runner    (1001) docker     (121)     2775 2022-08-15 01:47:47.000000 astropop-0.5.4/tests/test_aperture.py
--rw-r--r--   0 runner    (1001) docker     (121)    11976 2022-08-15 01:47:47.000000 astropop-0.5.4/tests/test_astrometry.py
--rw-r--r--   0 runner    (1001) docker     (121)       64 2022-08-15 01:47:47.000000 astropop-0.5.4/tests/test_catalog_local.py
--rw-r--r--   0 runner    (1001) docker     (121)    12268 2022-08-15 01:47:47.000000 astropop-0.5.4/tests/test_catalog_online.py
--rw-r--r--   0 runner    (1001) docker     (121)     6295 2022-08-15 01:47:47.000000 astropop-0.5.4/tests/test_ccdprocessing.py
--rw-r--r--   0 runner    (1001) docker     (121)    58233 2022-08-15 01:47:47.000000 astropop-0.5.4/tests/test_db.py
--rw-r--r--   0 runner    (1001) docker     (121)    34194 2022-08-15 01:47:47.000000 astropop-0.5.4/tests/test_detection.py
--rw-r--r--   0 runner    (1001) docker     (121)    15099 2022-08-15 01:47:47.000000 astropop-0.5.4/tests/test_filecollection.py
--rw-r--r--   0 runner    (1001) docker     (121)    42654 2022-08-15 01:47:47.000000 astropop-0.5.4/tests/test_framedata.py
--rw-r--r--   0 runner    (1001) docker     (121)    17407 2022-08-15 01:47:47.000000 astropop-0.5.4/tests/test_framedata_compat.py
--rw-r--r--   0 runner    (1001) docker     (121)    20858 2022-08-15 01:47:47.000000 astropop-0.5.4/tests/test_imarith.py
--rw-r--r--   0 runner    (1001) docker     (121)     4103 2022-08-15 01:47:47.000000 astropop-0.5.4/tests/test_imarith2.py
--rw-r--r--   0 runner    (1001) docker     (121)    33272 2022-08-15 01:47:47.000000 astropop-0.5.4/tests/test_imcombine.py
--rw-r--r--   0 runner    (1001) docker     (121)     4543 2022-08-15 01:47:47.000000 astropop-0.5.4/tests/test_logger.py
--rw-r--r--   0 runner    (1001) docker     (121)     6045 2022-08-15 01:47:47.000000 astropop-0.5.4/tests/test_math.py
--rw-r--r--   0 runner    (1001) docker     (121)    26039 2022-08-15 01:47:47.000000 astropop-0.5.4/tests/test_memmap.py
--rw-r--r--   0 runner    (1001) docker     (121)    73426 2022-08-15 01:47:47.000000 astropop-0.5.4/tests/test_physical.py
--rw-r--r--   0 runner    (1001) docker     (121)    64745 2022-08-15 01:47:47.000000 astropop-0.5.4/tests/test_physical_numpyfuncs.py
--rw-r--r--   0 runner    (1001) docker     (121)     4223 2022-08-15 01:47:47.000000 astropop-0.5.4/tests/test_pipeline.py
--rw-r--r--   0 runner    (1001) docker     (121)    18343 2022-08-15 01:47:47.000000 astropop-0.5.4/tests/test_polarimetry.py
--rw-r--r--   0 runner    (1001) docker     (121)    11304 2022-08-15 01:47:47.000000 astropop-0.5.4/tests/test_pyutils.py
--rw-r--r--   0 runner    (1001) docker     (121)    20072 2022-08-15 01:47:47.000000 astropop-0.5.4/tests/test_register.py
--rw-r--r--   0 runner    (1001) docker     (121)     5261 2022-08-15 01:47:47.000000 astropop-0.5.4/tests/test_testing.py
--rw-r--r--   0 runner    (1001) docker     (121)     1175 2022-08-15 01:47:47.000000 astropop-0.5.4/tests/test_unit_property.py
--rw-r--r--   0 runner    (1001) docker     (121)     2682 2022-08-15 01:47:47.000000 astropop-0.5.4/tox.ini
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:38:02.003424 astropop-0.9.0/
+-rw-r--r--   0 runner    (1001) docker     (123)      179 2023-06-28 00:37:50.000000 astropop-0.9.0/.codacy.yml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:38:01.979424 astropop-0.9.0/.github/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:38:01.983424 astropop-0.9.0/.github/workflows/
+-rw-r--r--   0 runner    (1001) docker     (123)     1101 2023-06-28 00:37:50.000000 astropop-0.9.0/.github/workflows/build-n-publish.yml
+-rw-r--r--   0 runner    (1001) docker     (123)     5046 2023-06-28 00:37:50.000000 astropop-0.9.0/.github/workflows/code_quality_analysis.yml
+-rw-r--r--   0 runner    (1001) docker     (123)     6610 2023-06-28 00:37:50.000000 astropop-0.9.0/.github/workflows/unit-tests.yml
+-rw-r--r--   0 runner    (1001) docker     (123)     1929 2023-06-28 00:37:50.000000 astropop-0.9.0/.gitignore
+-rw-r--r--   0 runner    (1001) docker     (123)      245 2023-06-28 00:37:50.000000 astropop-0.9.0/.readthedocs.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      298 2023-06-28 00:37:50.000000 astropop-0.9.0/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)     6658 2023-06-28 00:38:02.003424 astropop-0.9.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     6253 2023-06-28 00:37:50.000000 astropop-0.9.0/README.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:38:01.983424 astropop-0.9.0/astropop/
+-rw-r--r--   0 runner    (1001) docker     (123)      370 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1635 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/_astropy_init.py
+-rw-r--r--   0 runner    (1001) docker     (123)    36090 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/_db.py
+-rw-r--r--   0 runner    (1001) docker     (123)      677 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/_unit_property.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:38:01.983424 astropop-0.9.0/astropop/astrometry/
+-rw-r--r--   0 runner    (1001) docker     (123)      903 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/astrometry/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    29774 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/astrometry/astrometrynet.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1475 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/astrometry/coords_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2351 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/astrometry/manual_wcs.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:38:01.987424 astropop-0.9.0/astropop/catalogs/
+-rw-r--r--   0 runner    (1001) docker     (123)      175 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/catalogs/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3874 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/catalogs/_online_tools.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14725 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/catalogs/_sources_catalog.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6348 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/catalogs/gaia.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5737 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/catalogs/simbad.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9014 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/catalogs/vizier.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:38:01.987424 astropop-0.9.0/astropop/catalogs/vizier_catalogs/
+-rw-r--r--   0 runner    (1001) docker     (123)     1006 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/catalogs/vizier_catalogs/allwise.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      587 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/catalogs/vizier_catalogs/apass9.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      111 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/catalogs/vizier_catalogs/denis.yml
+-rw-r--r--   0 runner    (1001) docker     (123)     1565 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/catalogs/vizier_catalogs/gsc242.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      114 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/catalogs/vizier_catalogs/hip.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      503 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/catalogs/vizier_catalogs/twomass.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      519 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/catalogs/vizier_catalogs/tycho2.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      745 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/catalogs/vizier_catalogs/ucac4.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      602 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/catalogs/vizier_catalogs/ucac5.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      301 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/catalogs/vizier_catalogs/vsx.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      934 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/catalogs/vizier_catalogs/wise.yml
+-rw-r--r--   0 runner    (1001) docker     (123)    14499 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/file_collection.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1060 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/fits_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1742 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/flags.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:38:01.987424 astropop-0.9.0/astropop/framedata/
+-rw-r--r--   0 runner    (1001) docker     (123)      324 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/framedata/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11084 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/framedata/_compat.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3224 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/framedata/_memmap.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24273 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/framedata/framedata.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2452 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/framedata/util.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:38:01.991424 astropop-0.9.0/astropop/image/
+-rw-r--r--   0 runner    (1001) docker     (123)      483 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/image/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3619 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/image/_tools.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5287 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/image/imarith.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25093 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/image/imcombine.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10837 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/image/processing.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21687 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/image/register.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2287 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/logger.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:38:01.991424 astropop-0.9.0/astropop/math/
+-rw-r--r--   0 runner    (1001) docker     (123)      161 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/math/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7082 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/math/_deriv.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1479 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/math/array.py
+-rw-r--r--   0 runner    (1001) docker     (123)      528 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/math/hasher.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11217 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/math/models.py
+-rw-r--r--   0 runner    (1001) docker     (123)    33883 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/math/physical.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1657 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/math/reproject.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:38:01.991424 astropop-0.9.0/astropop/photometry/
+-rw-r--r--   0 runner    (1001) docker     (123)      315 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/photometry/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15961 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/photometry/aperture.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3491 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/photometry/background.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24060 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/photometry/detection.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:38:01.991424 astropop-0.9.0/astropop/polarimetry/
+-rw-r--r--   0 runner    (1001) docker     (123)    22901 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/polarimetry/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12072 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/py_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5966 2023-06-28 00:37:50.000000 astropop-0.9.0/astropop/testing.py
+-rw-r--r--   0 runner    (1001) docker     (123)      337 2023-06-28 00:38:01.000000 astropop-0.9.0/astropop/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:38:01.983424 astropop-0.9.0/astropop.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     6658 2023-06-28 00:38:01.000000 astropop-0.9.0/astropop.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     3849 2023-06-28 00:38:01.000000 astropop-0.9.0/astropop.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 00:38:01.000000 astropop-0.9.0/astropop.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 00:38:01.000000 astropop-0.9.0/astropop.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)      319 2023-06-28 00:38:01.000000 astropop-0.9.0/astropop.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-28 00:38:01.000000 astropop-0.9.0/astropop.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       15 2023-06-28 00:37:50.000000 astropop-0.9.0/codecov.yml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:38:01.991424 astropop-0.9.0/docs/
+-rw-r--r--   0 runner    (1001) docker     (123)     4595 2023-06-28 00:37:50.000000 astropop-0.9.0/docs/Makefile
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:38:01.991424 astropop-0.9.0/docs/_static/
+-rw-r--r--   0 runner    (1001) docker     (123)    59146 2023-06-28 00:37:50.000000 astropop-0.9.0/docs/_static/le2pol.jpeg
+-rw-r--r--   0 runner    (1001) docker     (123)     2357 2023-06-28 00:37:50.000000 astropop-0.9.0/docs/conf.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:38:01.995424 astropop-0.9.0/docs/data_structures/
+-rw-r--r--   0 runner    (1001) docker     (123)      939 2023-06-28 00:37:50.000000 astropop-0.9.0/docs/data_structures/framedata.rst
+-rw-r--r--   0 runner    (1001) docker     (123)    14863 2023-06-28 00:37:50.000000 astropop-0.9.0/docs/data_structures/physical.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      173 2023-06-28 00:37:50.000000 astropop-0.9.0/docs/data_structures.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:38:01.995424 astropop-0.9.0/docs/dev/
+-rw-r--r--   0 runner    (1001) docker     (123)     1682 2023-06-28 00:37:50.000000 astropop-0.9.0/docs/dev/pixel_convention.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      783 2023-06-28 00:37:50.000000 astropop-0.9.0/docs/index.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:38:01.995424 astropop-0.9.0/docs/ipynb/
+-rw-r--r--   0 runner    (1001) docker     (123)     5228 2023-06-28 00:37:50.000000 astropop-0.9.0/docs/ipynb/astrometry_example.ipynb
+-rw-r--r--   0 runner    (1001) docker     (123)    15966 2023-06-28 00:37:50.000000 astropop-0.9.0/docs/ipynb/diy_reduction_script.ipynb
+-rw-r--r--   0 runner    (1001) docker     (123)    35271 2023-06-28 00:37:50.000000 astropop-0.9.0/docs/ipynb/online_catalogs.ipynb
+-rw-r--r--   0 runner    (1001) docker     (123)     4549 2023-06-28 00:37:50.000000 astropop-0.9.0/docs/make.bat
+-rw-r--r--   0 runner    (1001) docker     (123)      311 2023-06-28 00:37:50.000000 astropop-0.9.0/docs/reducing.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:38:01.995424 astropop-0.9.0/docs/reduction/
+-rw-r--r--   0 runner    (1001) docker     (123)    13076 2023-06-28 00:37:50.000000 astropop-0.9.0/docs/reduction/astrometry.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      230 2023-06-28 00:37:50.000000 astropop-0.9.0/docs/reduction/ccdprocessing.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1312 2023-06-28 00:37:50.000000 astropop-0.9.0/docs/reduction/imarith.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      215 2023-06-28 00:37:50.000000 astropop-0.9.0/docs/reduction/photometry.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      185 2023-06-28 00:37:50.000000 astropop-0.9.0/docs/reduction/pipelines.rst
+-rw-r--r--   0 runner    (1001) docker     (123)    26036 2023-06-28 00:37:50.000000 astropop-0.9.0/docs/reduction/polarimetry.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      242 2023-06-28 00:37:50.000000 astropop-0.9.0/docs/reduction/registering.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1759 2023-06-28 00:37:50.000000 astropop-0.9.0/docs/references.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:38:01.995424 astropop-0.9.0/docs/tools/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:38:01.995424 astropop-0.9.0/docs/tools/catalog/
+-rw-r--r--   0 runner    (1001) docker     (123)     3367 2023-06-28 00:37:50.000000 astropop-0.9.0/docs/tools/catalog/gaia.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     3984 2023-06-28 00:37:50.000000 astropop-0.9.0/docs/tools/catalog/simbad.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     5110 2023-06-28 00:37:50.000000 astropop-0.9.0/docs/tools/catalog/vizier.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     8301 2023-06-28 00:37:50.000000 astropop-0.9.0/docs/tools/catalogs.rst
+-rw-r--r--   0 runner    (1001) docker     (123)    14140 2023-06-28 00:37:50.000000 astropop-0.9.0/docs/tools/files.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      211 2023-06-28 00:37:50.000000 astropop-0.9.0/docs/tools/fits_utils.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1932 2023-06-28 00:37:50.000000 astropop-0.9.0/docs/tools/logger.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      211 2023-06-28 00:37:50.000000 astropop-0.9.0/docs/tools/py_utils.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1109 2023-06-28 00:37:50.000000 astropop-0.9.0/docs/tools/testing.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      220 2023-06-28 00:37:50.000000 astropop-0.9.0/docs/tools.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      643 2023-06-28 00:37:50.000000 astropop-0.9.0/docs/user_guide.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:38:01.995424 astropop-0.9.0/licenses/
+-rw-r--r--   0 runner    (1001) docker     (123)     1481 2023-06-28 00:37:50.000000 astropop-0.9.0/licenses/LICENSE.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1659 2023-06-28 00:37:50.000000 astropop-0.9.0/licenses/TEMPLATE_LICENCE.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      198 2023-06-28 00:37:50.000000 astropop-0.9.0/pyproject.toml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:38:01.995424 astropop-0.9.0/scripts/
+-rw-r--r--   0 runner    (1001) docker     (123)      989 2023-06-28 00:37:50.000000 astropop-0.9.0/scripts/fitsheader_set
+-rw-r--r--   0 runner    (1001) docker     (123)     1877 2023-06-28 00:38:02.003424 astropop-0.9.0/setup.cfg
+-rwxr-xr-x   0 runner    (1001) docker     (123)     2052 2023-06-28 00:37:50.000000 astropop-0.9.0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:38:02.003424 astropop-0.9.0/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)       49 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/conftest.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8682 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/test_aperture.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23444 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/test_astrometry.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15686 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/test_catalogs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    43853 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/test_catalogs_online.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6687 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/test_ccdprocessing.py
+-rw-r--r--   0 runner    (1001) docker     (123)    62811 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/test_db.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26953 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/test_detection.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15993 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/test_filecollection.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1413 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/test_fits_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2135 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/test_flags.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19680 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/test_framedata.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20997 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/test_framedata_compat.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11320 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/test_framedata_getset.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7305 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/test_framedata_io.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5609 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/test_framedata_memmap.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1536 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/test_framedata_meta.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6757 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/test_framedata_tools.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11826 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/test_framedata_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6742 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/test_image_mergers.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24788 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/test_imarith.py
+-rw-r--r--   0 runner    (1001) docker     (123)    34096 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/test_imcombine.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4543 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/test_logger.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5148 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/test_math.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6643 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/test_math_models.py
+-rw-r--r--   0 runner    (1001) docker     (123)    76457 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/test_physical.py
+-rw-r--r--   0 runner    (1001) docker     (123)    65074 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/test_physical_numpyfuncs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    29905 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/test_polarimetry.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11701 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/test_pyutils.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20662 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/test_register.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5261 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/test_testing.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1175 2023-06-28 00:37:50.000000 astropop-0.9.0/tests/test_unit_property.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2339 2023-06-28 00:37:50.000000 astropop-0.9.0/tox.ini
```

### Comparing `astropop-0.5.4/.github/workflows/build-n-publish.yml` & `astropop-0.9.0/.github/workflows/build-n-publish.yml`

 * *Files identical despite different names*

### Comparing `astropop-0.5.4/.github/workflows/code_quality_analysis.yml` & `astropop-0.9.0/.github/workflows/code_quality_analysis.yml`

 * *Files 10% similar despite different names*

```diff
@@ -12,115 +12,125 @@
 jobs:
   codestyle:
     name: codestyle
     runs-on: ubuntu-latest
     if: github.event_name != 'pull_request'
 
     steps:
-    - uses: actions/checkout@v2
+    - uses: actions/checkout@v3
       with:
         fetch-depth: 0
     - name: Set up Python 3.10
-      uses: actions/setup-python@v2
+      uses: actions/setup-python@v4
       with:
         python-version: '3.10'
+        cache: 'pip'
+        cache-dependency-path: '**/setup.cfg'
     - name: Install base dependencies
       run: |
         python -m pip install --upgrade pip
         python -m pip install tox
     - name: Code Analyse
       run: tox -e codestyle
 
   docstyle:
     name: pydocstyle
     runs-on: ubuntu-latest
     if: github.event_name != 'pull_request'
 
     steps:
-    - uses: actions/checkout@v2
+    - uses: actions/checkout@v3
       with:
         fetch-depth: 0
     - name: Set up Python 3.10
-      uses: actions/setup-python@v2
+      uses: actions/setup-python@v4
       with:
         python-version: '3.10'
+        cache: 'pip'
+        cache-dependency-path: '**/setup.cfg'
     - name: Install base dependencies
       run: |
         python -m pip install --upgrade pip
         python -m pip install pydocstyle
     - name: Code Analyse
       continue-on-error: true
       run: pydocstyle astropop
 
-  prospector:
-    name: prospector
-    runs-on: ubuntu-latest
-    if: github.event_name != 'pull_request'
-
-    steps:
-    - uses: actions/checkout@v2
-      with:
-        fetch-depth: 0
-    - name: Set up Python 3.10
-      uses: actions/setup-python@v2
-      with:
-        python-version: '3.10'
-    - name: Install base dependencies
-      run: |
-        python -m pip install --upgrade pip
-        python -m pip install prospector pylint pyflakes bandit
-        python -m pip install .[all]
-    - name: Code Analyse
-      continue-on-error: true
-      run: prospector -w pyflakes -w bandit --doc-warnings -F astropop
+  # prospector:
+  #   name: prospector
+  #   runs-on: ubuntu-latest
+  #   if: github.event_name != 'pull_request'
+
+  #   steps:
+  #   - uses: actions/checkout@v3
+  #     with:
+  #       fetch-depth: 0
+  #   - name: Set up Python 3.10
+  #     uses: actions/setup-python@v4
+  #     with:
+  #       python-version: '3.10'
+  #       cache: 'pip'
+  #       cache-dependency-path: '**/setup.cfg'
+  #   - name: Install base dependencies
+  #     run: |
+  #       python -m pip install --upgrade pip
+  #       python -m pip install prospector pylint pyflakes bandit
+  #       python -m pip install .[all]
+  #       python -m pip install pydocstyle pycodestyle prospector pylint pyflakes bandit
+  #   - name: Run pycodestyle
+  #     run: pycodestyle --statistics astropop
+  #   # - name: Run pydocstyle
+  #   #   run: pydocstyle astropop
+  #   - name: Run prospector
+  #     run: prospector -w pyflakes -w bandit --doc-warnings -F astropop
 
   codestyle_pull_request:
     name: codestyle-pull-request
     runs-on: ubuntu-latest
     if: github.event_name == 'pull_request'
 
     steps:
-    - uses: actions/checkout@v2
+    - uses: actions/checkout@v3
       with:
         fetch-depth: 0
     - name: Set up Python 3.10
-      uses: actions/setup-python@v2
+      uses: actions/setup-python@v4
       with:
         python-version: '3.10'
+        cache: pip
+        cache-dependency-path: '**/setup.cfg'
     - uses: technote-space/get-diff-action@v6
       with:
         PATTERNS: |
           astropop/**/*.py
           tests/*.py
-    - name: Print DIFF
-      run: |
-        echo "GIT_DIFF: ${{ env.GIT_DIFF }}"
-        echo "GIT_DIFF_FILTERED: ${{ env.GIT_DIFF_FILTERED }}"
-
     - name: Install base dependencies
       run: |
         python -m pip install --upgrade pip
-        python -m pip install pycodestyle
-    - name: Code Analyse
+        python -m pip install pycodestyle pydocstyle prospector pylint pyflakes bandit
+        python -m pip install .[all]
+    - name: Run pycodestyle
       run: pycodestyle --statistics ${{ env.GIT_DIFF_FILTERED}}
       if: env.GIT_DIFF_FILTERED
 
   docstyle_pull_request:
     name: pydocstyle-pull-request
     runs-on: ubuntu-latest
     if: github.event_name == 'pull_request'
 
     steps:
-    - uses: actions/checkout@v2
+    - uses: actions/checkout@v3
       with:
         fetch-depth: 0
     - name: Set up Python 3.10
-      uses: actions/setup-python@v2
+      uses: actions/setup-python@v4
       with:
         python-version: '3.10'
+        cache: 'pip'
+        cache-dependency-path: '**/setup.cfg'
     - uses: technote-space/get-diff-action@v6
       with:
         PATTERNS: |
           astropop/**/*.py
           !tests/*.py
     - name: Print DIFF
       run: |
@@ -137,21 +147,23 @@
 
   prospector_pull_request:
     name: prospector-pull-request
     runs-on: ubuntu-latest
     if: github.event_name == 'pull_request'
 
     steps:
-    - uses: actions/checkout@v2
+    - uses: actions/checkout@v3
       with:
         fetch-depth: 0
     - name: Set up Python 3.10
-      uses: actions/setup-python@v2
+      uses: actions/setup-python@v4
       with:
         python-version: '3.10'
+        cache: 'pip'
+        cache-dependency-path: '**/setup.cfg'
     - uses: technote-space/get-diff-action@v6
       with:
         PATTERNS: |
           astropop/**/*.py
           !tests/*.py
     - name: Print DIFF
       run: |
```

### Comparing `astropop-0.5.4/.gitignore` & `astropop-0.9.0/.gitignore`

 * *Files 2% similar despite different names*

```diff
@@ -23,14 +23,15 @@
 MANIFEST
 .ipynb_checkpoints
 
 # Sphinx
 docs/api
 docs/_api
 docs/_build
+docs/savefig
 
 # Eclipse editor project files
 .project
 .pydevproject
 .settings
 
 # Pycharm editor project files
```

### Comparing `astropop-0.5.4/PKG-INFO` & `astropop-0.9.0/README.rst`

 * *Files 18% similar despite different names*

```diff
@@ -1,28 +1,13 @@
-Metadata-Version: 2.1
-Name: astropop
-Version: 0.5.4
-Summary: Astronomical Polarimetry and Photometry Pipeline
-Home-page: https://github.com/sparc4-dev/astropop
-Author: Julio Campagnolo
-Author-email: juliocampagnolo@gmail.com
-License: BSD 3-Clause
-Requires-Python: >=3.7
-Description-Content-Type: text/x-rst
-Provides-Extra: all
-Provides-Extra: test
-Provides-Extra: docs
-License-File: licenses/LICENSE.rst
-
 AstroPoP
 ========
 
 |GHAction Status| |Codecov Status| |RTD Status| |CODACY|
 
-The (non) famous ASTROnomical POlarimetry and Photometry pipeline. Developed for work with IAGPOL polarimeter at Observatório Pico dos Dias (Brazil), but suitable to be used in other image polarimeters around the world.
+The ASTROnomical POlarimetry and Photometry pipeline. Developed for work with IAGPOL and SPARC4 polarimeters at Observatório Pico dos Dias (Brazil), but suitable to be used in other image polarimeters around the world.
 
 Features
 ^^^^^^^^
 
 This software is intended to provide a full pipeline to reduce raw polarimetry and photometry data taken with common CCD telescope cameras. It can do:
 
 - Create calibrate frames;
@@ -39,20 +24,26 @@
 
 - Calcite polarimeters;
 
   - Automatic pairs of stars identification;
 
 - Automatic photometry calibration using online catalogs.
 
+Support and Community
+^^^^^^^^^^^^^^^^^^^^^
+
+We have a community of people using astropop to perform data reduction. Also, we use this community to offer support for astropop users. Join the community at `astropop-users Google-Groups <https://groups.google.com/g/astropop-users>`_
 
 Dependencies
 ^^^^^^^^^^^^
 
 Some of astropop dependencies (numpy, astropy, scipy, astroscrappy) need gcc to get build. Make sure gcc is installed properly in your system.
 
+There is nothing that prevent astropop itself to run on Windows. However, due to problems that comes from dependencies, mainly numpy and astrometry.net, astropop is currently supported only on Linux and Mac.
+
 Bellow we list all the necessary dependencies for the good working of the code. Note that this can be changed with the time.
 
 - astroalign;
 
 - astropy >= 4.3;
 
 - astroquery;
@@ -67,44 +58,65 @@
 
 - scipy;
 
 - sep.
 
 Installation
 ^^^^^^^^^^^^
-Astropop can be downloaded from https://github.com/sparc4-dev/astropop. For this, type in the terminal:
+
+Astropop can be downloaded from `gh/sparc4-dev/astropop <https://github.com/sparc4-dev/astropop>`_. It follows the stadard python package install procedure. All requirements can be installed with `pip` or `conda`.
+
+Anaconda Environment
+--------------------
+
+We recomend to use a `anaconda <https://www.anaconda.com/>`_ environment to use astropop. Having the anaconda installed, use the following command to install a new `<environment name>` with conda dependencies:
+
+.. code-block::
+
+    conda create -n <environment name> -c conda-forge python=3.10 astroalign astropy astroquery astroscrappy matplotlib numpy pyyaml reproject scikit-image scikit-learn scipy sep
+
+Once the environment is created, you can `activate the environment <https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#activating-an-environment>`_ and install the astropop with `pip`.
 
 .. code-block::
 
-    git clone https://github.com/sparc4-dev/astropop
+   conda activate <environment name>
 
-To install Astropop, you should go to the directory where Astropop was cloned, open the terminal in the Astropop directory and follow one of the options bellow:
+Stable Version
+--------------
 
-1 – Install using pip:
+The stable version of astropop is available in `PyPi <https://pypi.org/>`_ and can be installed directly with `pip` command.
 
 .. code-block::
 
-    pip install -U .
+   pip install astropop
+
+Development Version
+-------------------
 
-2 – Or, without the pip packet control:
+The development (unstable) version can be installed from the github code. With `pip`, can be done in any of the 3 ways:
 
 .. code-block::
 
-    python setup.py install
+    pip install -U git+https://github.com/sparc4-dev/astropop
+
+or
+
+.. code-block::
 
-3 – Install using anaconda:
+   pip install -U https://github.com/sparc4-dev/astropop/archive/refs/heads/main.zip
 
-If you do not have anaconda, please visit https://www.anaconda.com/.
-Once the anaconda is installed you can create an Astropop enviroment using:
+or
 
 .. code-block::
 
-    conda create -n <environment name> -c conda-forge python=3.9 astroalign astropy astroquery astroscrappy matplotlib numpy pyyaml reproject scikit-image scikit-learn scipy sep
+   git clone https://github.com/sparc4-dev/astropop
+   cd astropop
+   pip install -U .
 
-Citating
+Citing
 ^^^^^^^^
 
 |ADS|  |PASP|  |arXiv|  |ASCL|
 
 An article was published in `Publications of the Astronomical Society of the Pacific, vol.131, n.996, pp.024501 <https://iopscience.iop.org/article/10.1088/1538-3873/aaecc2>`_,
 which is the main reference to this work. If you do not have access to PASP, the preprint was uploaded to `arXiv:1811.01408 <https://arxiv.org/abs/1811.01408>`_.
```

### Comparing `astropop-0.5.4/README.rst` & `astropop-0.9.0/PKG-INFO`

 * *Files 26% similar despite different names*

```diff
@@ -1,13 +1,28 @@
+Metadata-Version: 2.1
+Name: astropop
+Version: 0.9.0
+Summary: Astronomical Polarimetry and Photometry Pipeline
+Home-page: https://github.com/sparc4-dev/astropop
+Author: Julio Campagnolo
+Author-email: juliocampagnolo@gmail.com
+License: BSD 3-Clause
+Requires-Python: >=3.8
+Description-Content-Type: text/x-rst
+Provides-Extra: all
+Provides-Extra: test
+Provides-Extra: docs
+License-File: licenses/LICENSE.rst
+
 AstroPoP
 ========
 
 |GHAction Status| |Codecov Status| |RTD Status| |CODACY|
 
-The (non) famous ASTROnomical POlarimetry and Photometry pipeline. Developed for work with IAGPOL polarimeter at Observatório Pico dos Dias (Brazil), but suitable to be used in other image polarimeters around the world.
+The ASTROnomical POlarimetry and Photometry pipeline. Developed for work with IAGPOL and SPARC4 polarimeters at Observatório Pico dos Dias (Brazil), but suitable to be used in other image polarimeters around the world.
 
 Features
 ^^^^^^^^
 
 This software is intended to provide a full pipeline to reduce raw polarimetry and photometry data taken with common CCD telescope cameras. It can do:
 
 - Create calibrate frames;
@@ -24,20 +39,26 @@
 
 - Calcite polarimeters;
 
   - Automatic pairs of stars identification;
 
 - Automatic photometry calibration using online catalogs.
 
+Support and Community
+^^^^^^^^^^^^^^^^^^^^^
+
+We have a community of people using astropop to perform data reduction. Also, we use this community to offer support for astropop users. Join the community at `astropop-users Google-Groups <https://groups.google.com/g/astropop-users>`_
 
 Dependencies
 ^^^^^^^^^^^^
 
 Some of astropop dependencies (numpy, astropy, scipy, astroscrappy) need gcc to get build. Make sure gcc is installed properly in your system.
 
+There is nothing that prevent astropop itself to run on Windows. However, due to problems that comes from dependencies, mainly numpy and astrometry.net, astropop is currently supported only on Linux and Mac.
+
 Bellow we list all the necessary dependencies for the good working of the code. Note that this can be changed with the time.
 
 - astroalign;
 
 - astropy >= 4.3;
 
 - astroquery;
@@ -52,44 +73,65 @@
 
 - scipy;
 
 - sep.
 
 Installation
 ^^^^^^^^^^^^
-Astropop can be downloaded from https://github.com/sparc4-dev/astropop. For this, type in the terminal:
+
+Astropop can be downloaded from `gh/sparc4-dev/astropop <https://github.com/sparc4-dev/astropop>`_. It follows the stadard python package install procedure. All requirements can be installed with `pip` or `conda`.
+
+Anaconda Environment
+--------------------
+
+We recomend to use a `anaconda <https://www.anaconda.com/>`_ environment to use astropop. Having the anaconda installed, use the following command to install a new `<environment name>` with conda dependencies:
+
+.. code-block::
+
+    conda create -n <environment name> -c conda-forge python=3.10 astroalign astropy astroquery astroscrappy matplotlib numpy pyyaml reproject scikit-image scikit-learn scipy sep
+
+Once the environment is created, you can `activate the environment <https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#activating-an-environment>`_ and install the astropop with `pip`.
 
 .. code-block::
 
-    git clone https://github.com/sparc4-dev/astropop
+   conda activate <environment name>
 
-To install Astropop, you should go to the directory where Astropop was cloned, open the terminal in the Astropop directory and follow one of the options bellow:
+Stable Version
+--------------
 
-1 – Install using pip:
+The stable version of astropop is available in `PyPi <https://pypi.org/>`_ and can be installed directly with `pip` command.
 
 .. code-block::
 
-    pip install -U .
+   pip install astropop
+
+Development Version
+-------------------
 
-2 – Or, without the pip packet control:
+The development (unstable) version can be installed from the github code. With `pip`, can be done in any of the 3 ways:
 
 .. code-block::
 
-    python setup.py install
+    pip install -U git+https://github.com/sparc4-dev/astropop
+
+or
+
+.. code-block::
 
-3 – Install using anaconda:
+   pip install -U https://github.com/sparc4-dev/astropop/archive/refs/heads/main.zip
 
-If you do not have anaconda, please visit https://www.anaconda.com/.
-Once the anaconda is installed you can create an Astropop enviroment using:
+or
 
 .. code-block::
 
-    conda create -n <environment name> -c conda-forge python=3.9 astroalign astropy astroquery astroscrappy matplotlib numpy pyyaml reproject scikit-image scikit-learn scipy sep
+   git clone https://github.com/sparc4-dev/astropop
+   cd astropop
+   pip install -U .
 
-Citating
+Citing
 ^^^^^^^^
 
 |ADS|  |PASP|  |arXiv|  |ASCL|
 
 An article was published in `Publications of the Astronomical Society of the Pacific, vol.131, n.996, pp.024501 <https://iopscience.iop.org/article/10.1088/1538-3873/aaecc2>`_,
 which is the main reference to this work. If you do not have access to PASP, the preprint was uploaded to `arXiv:1811.01408 <https://arxiv.org/abs/1811.01408>`_.
```

### Comparing `astropop-0.5.4/astropop/_astropy_init.py` & `astropop-0.9.0/astropop/_astropy_init.py`

 * *Files identical despite different names*

### Comparing `astropop-0.5.4/astropop/_db.py` & `astropop-0.9.0/astropop/_db.py`

 * *Files 2% similar despite different names*

```diff
@@ -11,15 +11,45 @@
 
 __all__ = ['SQLDatabase', 'SQLTable', 'SQLRow', 'SQLColumn', 'SQLColumnMap']
 
 
 _ID_KEY = '__id__'
 
 
-class SQLColumnMap:
+class _SQLViewerBase:
+    """Memview for SQL data. Not allowed to copy."""
+
+    def __copy__(self):
+        raise NotImplementedError('Cannot copy SQL viewing classes.')
+
+    def __deepcopy__(self, memo):
+        raise NotImplementedError('Cannot copy SQL viewing classes.')
+
+
+class _SQLRowIndexer(_SQLViewerBase):
+    """A class for indexing SQL rows. Safer method while removing rows.
+
+    Index is obtained by indexof(self).
+
+    Parameters
+    ----------
+    row_list: list
+        The list of `_SQLRowIndexer` to get the index of.
+    """
+
+    def __init__(self, row_list):
+        self._row_list = row_list
+
+    @property
+    def index(self):
+        """Get the index of the row."""
+        return self._row_list.index(self)
+
+
+class SQLColumnMap():
     """Map keywords to SQL columns."""
 
     def __init__(self, db, map_table, map_key, map_column):
         self.db = db
         self.map = db[map_table]
         self.key = map_key
         self.col = map_column
@@ -100,15 +130,15 @@
     def parse_where(self, where):
         """Parse a where clause using column mappring."""
         if isinstance(where, dict):
             return {self.get_column_name(k): v for k, v in where.items()}
         raise TypeError('Only dict is supported')
 
 
-class SQLTable:
+class SQLTable(_SQLViewerBase):
     """Handle an SQL table operations interfacing with the DB."""
 
     def __init__(self, db, name, colmap=None):
         """Initialize the table.
 
         Parameters
         ----------
@@ -194,14 +224,24 @@
 
     def set_row(self, row, data):
         """Set a given row in the table."""
         if self._colmap is not None:
             data = self._colmap.map_row(data)
         self._db.set_row(self._name, row, data)
 
+    def delete_column(self, column):
+        """Delete a given column from the table."""
+        if self._colmap is not None:
+            column = self._colmap.get_column_name(column)
+        self._db.delete_column(self._name, column)
+
+    def delete_row(self, row):
+        """Delete all rows from the table."""
+        self._db.delete_row(self._name, row)
+
     def index_of(self, where):
         """Get the index of the rows that match the given condition."""
         if self._colmap is not None:
             where = self._colmap.parse_where(where)
         return self._db.index_of(self._name, where)
 
     def _resolve_tuple(self, key):
@@ -273,15 +313,15 @@
         s = f"{self.__class__.__name__} '{self.name}'"
         s += f" in database '{self.db}':"
         s += f"({len(self.column_names)} columns x {len(self)} rows)\n"
         s += '\n'.join(self.as_table().__repr__().split('\n')[1:])
         return s
 
 
-class SQLColumn:
+class SQLColumn(_SQLViewerBase):
     """Handle an SQL column operations interfacing with the DB."""
 
     def __init__(self, db, table, name):
         """Initialize the column.
 
         Parameters
         ----------
@@ -348,32 +388,32 @@
     def __repr__(self):
         """Get a string representation of the column."""
         s = f"{self.__class__.__name__} {self._name} in table '{self._table}'"
         s += f" ({len(self)} rows)"
         return s
 
 
-class SQLRow:
+class SQLRow(_SQLViewerBase):
     """Handle and SQL table row interfacing with the DB."""
 
-    def __init__(self, db, table, row, colmap=None):
+    def __init__(self, db, table, row_indexer, colmap=None):
         """Initialize the row.
 
         Parameters
         ----------
         db : SQLDatabase
             The parent database object.
         table : str
             The name of the table in the database.
-        row : int
+        row_indexer : `~astropop._db._SQLRowIndexer`
             The row index in the table.
         """
         self._db = db
         self._table = table
-        self._row = row
+        self._row_indexer = row_indexer
         self._colmap = colmap
 
     @property
     def column_names(self):
         """Get the column names of the current table."""
         names = self._db.column_names(self._table)
         if self._colmap is not None:
@@ -389,15 +429,15 @@
     def values(self):
         """Get the values of the current row."""
         return self._db.select(self._table, where={_ID_KEY: self.index+1})[0]
 
     @property
     def index(self):
         """Get the index of the current row."""
-        return self._row
+        return self._row_indexer.index
 
     @property
     def keys(self):
         """Get the keys of the current row."""
         return self.column_names
 
     @property
@@ -412,15 +452,15 @@
     def __getitem__(self, key):
         """Get a column from the row."""
         if isinstance(key, (str, np.str_)):
             column = key
             if self._colmap is not None:
                 column = self._colmap.get_column_name(key)
             try:
-                return self._db.get_item(self._table, column, self._row)
+                return self._db.get_item(self._table, column, self.index)
             except ValueError:
                 raise KeyError(f'{key}')
         if isinstance(key, (int, np.int_)):
             return self.values[key]
         raise KeyError(f'{key}')
 
     def __setitem__(self, key, value):
@@ -442,15 +482,15 @@
 
     def __contains__(self, item):
         """Check if the row contains a given value."""
         return item in self.values
 
     def __repr__(self):
         """Get a string representation of the row."""
-        s = f"{self.__class__.__name__} {self._row} in table '{self._table}' "
+        s = f"{self.__class__.__name__} {self.index} in table '{self._table}' "
         s += self.as_dict().__repr__()
         return s
 
 
 def _sanitize_colnames(data):
     """Sanitize the colnames to avoid invalid characteres like '-'."""
     def _sanitize(key):
@@ -554,14 +594,17 @@
             Defaults to True.
         """
         self._db = db
         self._con = sql.connect(self._db)
         self._cur = self._con.cursor()
         self.autocommit = autocommit
 
+        self._row_indexes = {}
+        self._build_row_indexes()
+
     def execute(self, command, arguments=None):
         """Execute a SQL command in the database."""
         logger.debug('executing sql command: "%s"',
                      str.replace(command, '\n', ' '))
         try:
             if arguments is None:
                 self._cur.execute(command)
@@ -731,14 +774,40 @@
         if not skip_sanitize:
             data = [tuple(map(_sanitize_value, d)) for d in data]
         comm = f"INSERT INTO {table} VALUES "
         comm += f"(NULL, {', '.join(['?']*len(data[0]))})"
         comm += ';'
         self.executemany(comm, data)
 
+        # Update the row indexes
+        rl = self._row_indexes[table]
+        rl.extend([_SQLRowIndexer(rl) for i in range(len(data))])
+
+    def _get_indexes(self, table):
+        """Get the indexes of the table."""
+        comm = f"SELECT {_ID_KEY} FROM {table};"
+        return [i[0] for i in self.execute(comm)]
+
+    def _update_indexes(self, table):
+        """Update the indexes of the table."""
+        rows = list(range(1, self.count(table) + 1))
+        origin = self._get_indexes(table)
+        comm = f"UPDATE {table} SET {_ID_KEY} = ? WHERE {_ID_KEY} = ?;"
+        self.executemany(comm, zip(rows, origin))
+
+    def _build_row_indexes(self):
+        """Build the row indexes."""
+        for table in self.table_names:
+            size = self.count(table)
+            # Create the list that must be passed to _SQLRowIndexer
+            rl = [None]*size
+            self._row_indexes[table] = rl
+            for i in range(size):
+                self._row_indexes[table][i] = _SQLRowIndexer(rl)
+
     def add_table(self, table, columns=None, data=None):
         """Create a table in database."""
         logger.debug('Initializing "%s" table.', table)
         if table in self.table_names:
             raise ValueError('table {table} already exists.')
 
         comm = f"CREATE TABLE '{table}'"
@@ -752,14 +821,17 @@
                 comm += f"\t'{name}'"
                 if i != len(columns) - 1:
                     comm += ",\n"
         comm += "\n);"
 
         self.execute(comm)
 
+        # Add the row indexer list
+        self._row_indexes[table] = []
+
         if data is not None:
             self.add_rows(table, data, add_columns=True)
 
     def add_column(self, table, column, data=None):
         """Add a column to a table."""
         self._check_table(table)
 
@@ -776,14 +848,27 @@
         logger.debug('adding column "%s" to table "%s"', col, table)
         self.execute(comm)
 
         # adding the data to the table
         if data is not None:
             self.set_column(table, column, data)
 
+    def delete_column(self, table, column):
+        """Delete a column from a table."""
+        self._check_table(table)
+
+        if column in (_ID_KEY, 'table', 'default'):
+            raise ValueError(f"{column} is a protected name.")
+        if column not in self.column_names(table):
+            raise KeyError(f'Column "{column}" does not exist.')
+
+        comm = f"ALTER TABLE {table} DROP COLUMN '{column}' ;"
+        logger.debug('deleting column "%s" from table "%s"', column, table)
+        self.execute(comm)
+
     def add_rows(self, table, data, add_columns=False, skip_sanitize=False):
         """Add a dict row to a table.
 
         Parameters
         ----------
         data : dict, list or `~numpy.ndarray`
             Data to add to the table. If dict, keys are column names,
@@ -813,30 +898,41 @@
             data = {c: list(data[c]) for c in data.colnames}
             return self._add_data_dict(table, data, add_columns=add_columns,
                                        skip_sanitize=skip_sanitize)
 
         raise TypeError('data must be a dict, list, or numpy array. '
                         f'Not {type(data)}.')
 
+    def delete_row(self, table, index):
+        """Delete a row from the table."""
+        self._check_table(table)
+        row = _fix_row_index(index, len(self[table]))
+        comm = f"DELETE FROM {table} WHERE {_ID_KEY}={row+1};"
+        self.execute(comm)
+        self._row_indexes[table].pop(row)
+        self._update_indexes(table)
+
     def drop_table(self, table):
         """Drop a table from the database."""
         self._check_table(table)
         comm = f"DROP TABLE {table};"
         self.execute(comm)
+        del self._row_indexes[table]
 
     def get_table(self, table, column_map=None):
         """Get a table from the database."""
         self._check_table(table)
         return SQLTable(self, table, colmap=column_map)
 
     def get_row(self, table, index, column_map=None):
         """Get a row from the table."""
         self._check_table(table)
         index = _fix_row_index(index, len(self[table]))
-        return SQLRow(self, table, index, colmap=column_map)
+        row = self._row_indexes[table][index]
+        return SQLRow(self, table, row, colmap=column_map)
 
     def get_column(self, table, column):
         """Get a column from the table."""
         column = column.lower()
         if column not in self.column_names(table):
             raise KeyError(f"column {column} does not exist.")
         return SQLColumn(self, table, column)
@@ -959,25 +1055,16 @@
             A copy of the database.
         """
         def _get_data(table, indx=None):
             if indx is None:
                 return self.select(table)
             if len(indx) == 0:
                 return None
-            if len(indx) >= 10000:
-                # too many rows must be divided
-                indx = np.array_split(indx, np.ceil(len(indx)/10000))
-                d = None
-                for i in indx:
-                    if d is None:
-                        d = _get_data(table, i)
-                    else:
-                        np.vstack([d, _get_data(table, i)])
-                return d
-            where = " OR ".join(f"{_ID_KEY}={v+1}" for v in indx)
+            indx = np.array(np.array(indx, dtype=int)+1, dtype=str)
+            where = f"{_ID_KEY} in ({','.join(indx)})"
             return self.select(table, where=where)
 
         # when copying, always copy to memory
         db = SQLDatabase(':memory:')
         if indexes is None:
             indexes = {}
         for i in self.table_names:
```

### Comparing `astropop-0.5.4/astropop/_unit_property.py` & `astropop-0.9.0/astropop/_unit_property.py`

 * *Files identical despite different names*

### Comparing `astropop-0.5.4/astropop/astrometry/coords_utils.py` & `astropop-0.9.0/astropop/astrometry/coords_utils.py`

 * *Files identical despite different names*

### Comparing `astropop-0.5.4/astropop/astrometry/manual_wcs.py` & `astropop-0.9.0/astropop/astrometry/manual_wcs.py`

 * *Files identical despite different names*

### Comparing `astropop-0.5.4/astropop/catalogs/_online_tools.py` & `astropop-0.9.0/astropop/catalogs/_online_tools.py`

 * *Files 11% similar despite different names*

```diff
@@ -1,36 +1,37 @@
 # Licensed under a 3-clause BSD style license - see LICENSE.rst
 """Module to handle online catalog queries."""
 
 import numpy as np
 from astroquery.simbad import Simbad
 from astroquery.exceptions import TableParseError
 from astropy.coordinates import SkyCoord, Angle
+from astropy.units import UnitTypeError
 from ..astrometry.coords_utils import guess_coordinates
 from ..py_utils import string_fix, process_list
 
 
 MAX_PARALLEL_QUERY = 30
 MAX_RETRIES_TIMEOUT = 10
 
 
 def _timeout_retry(func, *args, **kwargs):
     """Retry a function until MAX_RETRIES_TIMEOUT is reached."""
     tried = kwargs.pop('_____retires', 0)
     try:
         q = func(*args, **kwargs)
-    except (TimeoutError, TableParseError):
+    except (TimeoutError, TableParseError) as exc:
         if tried >= MAX_RETRIES_TIMEOUT:
             raise TimeoutError(f'TimeOut obtained in {MAX_RETRIES_TIMEOUT}'
-                               ' tries, aborting.')
+                               ' tries, aborting.') from exc
         return _timeout_retry(func, *args, **kwargs, _____retires=tried+1)
     return q
 
 
-def _wrap_query_table(table):
+def _fix_query_table(table):
     """Fix bytes and objects columns to strings."""
     for i in table.columns:
         tdtype = table[i].dtype.char
         if tdtype in ('b', 'B', 'S', 'a', 'O'):
             row = process_list(string_fix, table[i])
             table[i] = np.array(row, dtype=str)
     return table
@@ -75,31 +76,41 @@
             if simbad is None:
                 simbad = Simbad()
             t = simbad.query_object(center)
             if t is None:
                 raise ValueError(f'Coordinates {center} could not be'
                                  ' resolved.')
             return guess_coordinates(t['RA'][0], t['DEC'][0], skycoord=True)
-    elif isinstance(center, (tuple, list, np.ndarray)) and len(center) == 2:
+    if isinstance(center, (tuple, list, np.ndarray)) and len(center) == 2:
         return guess_coordinates(center[0], center[1], skycoord=True)
-    elif isinstance(center, SkyCoord):
+    if isinstance(center, SkyCoord):
         return center
 
     raise ValueError(f'Center coordinates {center} not undertood.')
 
 
 def astroquery_radius(radius):
-    """Convert several types of values to decimal degree angle radius.
+    """Convert several types of values to angle radius.
 
     Notes
     -----
     - Current supported types are:
-      - Any instance that can be converted to `float`.
+      - Numbers (float or int) are interpreted as decimal degree
       - `str` or `bytes` that can be converted to `astropy.coordinates.Angle`.
     """
-    if isinstance(radius, (str, bytes)):
+    try:
         radius = Angle(radius)
+    except UnitTypeError:
+        if isinstance(radius, (int, float)):
+            radius = Angle(radius, unit='deg')
+        else:
+            raise TypeError(f'{radius.__class__} not supported.')
+
+    return radius
 
-    if isinstance(radius, Angle):
-        radius = radius.degree
 
-    return f"{float(radius)}d"
+def astroquery_query(querier, *args, **kwargs):
+    """Query an region using astroquery."""
+    query = _timeout_retry(querier, *args, **kwargs)
+    if query is None:
+        raise RuntimeError("No online catalog result found.")
+    return query
```

### Comparing `astropop-0.5.4/astropop/file_collection.py` & `astropop-0.9.0/astropop/file_collection.py`

 * *Files 18% similar despite different names*

```diff
@@ -12,15 +12,15 @@
 from ._db import SQLDatabase, _ID_KEY, sql, SQLTable, SQLColumnMap
 from .fits_utils import _fits_extensions, \
                         _fits_extensions_with_compress
 from .framedata import check_framedata
 from .py_utils import check_iterable
 from .logger import logger
 
-__all__ = ['list_fits_files', 'FitsFileGroup']
+__all__ = ['FitsFileGroup']
 
 
 def list_fits_files(location, fits_extensions=None,
                     glob_include=None, glob_exclude=None):
     """List all fist files in a directory, if compressed or not."""
     if fits_extensions is None:
         fits_extensions = _fits_extensions
@@ -56,22 +56,54 @@
 _files_col = '__file'
 _keycolstable = 'astropop_keyword2column'
 _keywords_col = 'keyword'
 _columns_col = 'column'
 
 
 class FitsFileGroup():
-    """Easy handle groups of fits files."""
+    """Easy handle groups of fits files.
+
+    Parameters
+    ----------
+    location : str, optional
+        Location of the fits files. If not specified, the files must be
+        specified in the files parameter.
+    files : list, optional
+        List of files to be included in the group. If not specified, the
+        location parameter must be specified.
+    ext : int, optional
+        FITS extension to be used. Default is 0.
+    compression : bool, optional
+        If True, add compression file name extensions to the list of
+        extensions to be searched. Default is False.
+    database : str, optional
+        SQLite database to be used to store the information. Default is
+        ':memory:', which means that the database will be stored in memory.
+    glob_include : str, optional
+        Glob pattern to include files. Default is None.
+    glob_exclude : str, optional
+        Glob pattern to exclude files. Default is None.
+    fits_ext : str, optional
+        FITS file name extension to be used. Default is None, wich means
+        that the default extensions will be used.
+    show_progress_bar : bool, optional
+        If True, show a progress bar while reading the files. Default is
+        False. Requires ``tqdm`` module. May not be compatible with every mod.
+    """
 
     def __init__(self, location=None, files=None, ext=0,
                  compression=False, database=':memory:', **kwargs):
         self._ext = ext
-        self._extensions = kwargs.get('fits_ext', None)
-        self._include = kwargs.get('glob_include')
-        self._exclude = kwargs.get('glob_exclude')
+        self._extensions = kwargs.pop('fits_ext', None)
+        self._include = kwargs.pop('glob_include', None)
+        self._exclude = kwargs.pop('glob_exclude', None)
+        self._progress = kwargs.pop('show_progress_bar', False)
+
+        for i in kwargs.keys():
+            raise ValueError('Unknown parameter: {}'.format(i))
 
         self._db = SQLDatabase(database)
         if database == ':memory:':
             self._db_dir = None
         else:
             self._db_dir = Path(database).resolve().parent
 
@@ -128,15 +160,15 @@
 
         if update or not initialized:
             self.update(files, location, compression)
 
     @property
     def files(self):
         """List files in the group."""
-        return [self.full_path(i) for i in range(len(self))]
+        return [self.full_path(i) for i in self.values(_files_col)]
 
     @property
     def summary(self):
         """Get a readonly table with summary of the fits files."""
         return self._table.as_table()
 
     def __copy__(self, indexes=None):
@@ -153,27 +185,53 @@
         return nfg
 
     def __len__(self):
         """Get the number of files in the group."""
         return len(self._table)
 
     def filtered(self, keywords):
-        """Create a new FitsFileGroup with only filtered files."""
+        """Create a new FitsFileGroup with only filtered files.
+
+        Parameters
+        ----------
+        keywords : dict
+            Dictionary with the keywords to be used to filter the files.
+            The keys are the column names and the values are the values
+            to be used to filter the files.
+
+        Returns
+        -------
+        FitsFileGroup
+            A new FitsFileGroup with only the files that match the
+            keywords.
+        """
         try:
             indexes = self._table.select(columns=[_ID_KEY],
                                          where=keywords)
         except sql.OperationalError:
             indexes = []
         if len(indexes) == 0:
             return self.__copy__(indexes=[])
         indexes = np.array(indexes).ravel() - 1
         return self.__copy__(indexes)
 
     def group_by(self, keywords):
-        """Create FitsFileGroups grouped by keywords."""
+        """Create FitsFileGroups grouped by keywords.
+
+        Parameters
+        ----------
+        keywords : list
+            List of column names to be used to group the files.
+
+        Yields
+        ------
+        FitsFileGroup
+            A new FitsFileGroup with only the files that match the
+            keywords.
+        """
         summary = self.summary
         id_key = 'id'
         while id_key in summary.colnames:
             id_key += '_'
         summary.add_column(Column(np.arange(len(summary))),
                            name=id_key)
 
@@ -186,48 +244,98 @@
         if _headers in self._db.table_names:
             self._db.drop_table(_headers)
 
         self._db.add_table(_headers)
         location = location or self._location
         compression = compression or self._compression
         files = self._list_files(files, location, compression)
-        for i, f in enumerate(files):
-            logger.info('reading file %i from %i: %s', i, len(files), f)
+        if self._progress:
+            from tqdm.contrib import tenumerate as enum
+        else:
+            enum = enumerate
+        for i, f in enum(files):
             try:
                 self.add_file(f)
             except Exception as e:
                 # just log error instead of raise an exception
                 logger.error('Error reading file %s: %s', f, e)
 
     def values(self, keyword, unique=False):
         """Return the values of a keyword in the summary.
 
-        If unique, only unique values returned.
+        Parameters
+        ----------
+        keyword : str
+            Name of the keyword to be used to filter the files.
+        unique : bool, optional
+            If unique, only unique values returned.
+
+        Returns
+        -------
+        list
+            List of values for the keyword.
         """
         vals = self._table[keyword].values
         if unique:
             vals = list(set(vals))
         return vals
 
     def add_column(self, name, values=None):
-        """Add a new column to the summary."""
+        """Add a new column to the summary.
+
+        Parameters
+        ----------
+        name : str
+            Name of the column.
+        values : list, optional
+            List of values for the column. If None, the column is
+            initialized with null values.
+        """
         self._table.add_column(name, data=values)
 
     def add_file(self, file):
-        """Add a new file to the group."""
+        """Add a new file to the group.
+
+        Parameters
+        ----------
+        file : str
+            File name with absolute path or relative to the filegroup
+            location.
+        """
         header = fits.open(file)[self._ext].header
         logger.debug('reading file %s', file)
         file = self.relative_path(file)
         hdr = {_files_col: file}
         hdr.update(dict(header))
+
+        # get rid of comments, history and empty keys
         hdr.pop('COMMENT', None)
         hdr.pop('HISTORY', None)
         hdr.pop('', None)
+
         self._table.add_rows(hdr, add_columns=True)
 
+    def remove_file(self, file):
+        """Remove a file from the group.
+
+        Parameters
+        ----------
+        file : str or int
+            If string, the file name with absolute path or relative to the
+            filegroup location. If int, the index of the file.
+        """
+        if isinstance(file, int):
+            index = file
+        else:
+            file = self.relative_path(file)
+            if file not in self._table[_files_col]:
+                raise ValueError(f'{file} file not in group')
+            index = self._table.index_of({_files_col: file})
+        self._table.delete_row(index)
+
     def full_path(self, file):
         """Get the full path of a file in the group.
 
         Parameters
         ----------
         file : str or int
             If string, the file name. If int, the index of the file.
@@ -236,15 +344,15 @@
         -------
         path : str
             Full path of the file.
         """
         if isinstance(file, int):
             file = self._table[_files_col][file]
         if self._db_dir is not None:
-            return os.path.join(self._db_dir, file)
+            return os.path.abspath(os.path.join(self._db_dir, file))
         return file
 
     def relative_path(self, file):
         """Get the relative path of a file.
 
         Parameters
         ----------
```

### Comparing `astropop-0.5.4/astropop/framedata/compat.py` & `astropop-0.9.0/astropop/framedata/_compat.py`

 * *Files 17% similar despite different names*

```diff
@@ -12,26 +12,27 @@
 from astropy.nddata.ccddata import CCDData
 from astropy.nddata import StdDevUncertainty, VarianceUncertainty, \
                            InverseVariance
 from astropy import units as u
 
 
 from ..logger import logger
-from ..fits_utils import imhdus
-from ..py_utils import broadcast
-
-
-__all__ = ['imhdus', 'EmptyDataError']
+from ..fits_utils import imhdus, string_to_header_key
 
 
 _PCs = set(['PC1_1', 'PC1_2', 'PC2_1', 'PC2_2'])
 _CDs = set(['CD1_1', 'CD1_2', 'CD2_1', 'CD2_2'])
 _KEEP = set(['JD-OBS', 'MJD-OBS', 'DATE-OBS'])
+_PROCTECTED = ["SIMPLE", "XTENSION", "BITPIX", "NAXIS", "EXTEND", "PCOUNT",
+               "GCOUNT", "GROUPS", "BSCALE", "BZERO", "TFIELDS"]
+_PROTECTED_N = ["TFORM", "TSCAL", "TZERO", "TNULL", "TTYPE", "TUNIT", "TDISP",
+                "TDIM", "THEAP", "TBCOL"]
 _HDU_UNCERT = 'UNCERT'
 _HDU_MASK = 'MASK'
+_HDU_FLAGS = 'PIXFLAGS'
 _UNIT_KEY = 'BUNIT'
 
 
 def _remove_sip_keys(header, wcs):
     """Remove the SIP keys. (Too complex fixing)."""
     kwd = '{}_{}_{}'
     pol = ['A', 'B', 'AP', 'BP']
@@ -95,64 +96,96 @@
         # Check and remove remaining SIP coefficients
         if wcs.sip is not None:
             header = _remove_sip_keys(header, wcs)
 
     return (header, wcs)
 
 
-def _merge_and_clean_header(meta, header, wcs):
-    """Merge meta and header and clean the WCS and spurious keys."""
-    for i in (meta, header, wcs):
-        if not isinstance(i, (dict, fits.Header, WCS)) and i is not None:
-            raise TypeError(f'{i} is not a compatible format.')
-
-    if header is not None:
-        header = fits.Header(header)
-        header.strip()
-    else:
-        header = fits.Header()
-
-    if meta is not None:
-        meta = fits.Header(meta)
-        meta.strip()
-    else:
-        meta = fits.Header()
+def _normalize_and_strip_dict(meta):
+    """Normalize meta keys and remove the protected ones."""
+    if meta is None:
+        return {}, [], []
+
+    nmeta = {}
+    history = []
+    comment = []
+
+    for k, v in meta.items():
+        k = string_to_header_key(k)
+        # pop history and comment
+        if k == 'HISTORY':
+            if np.isscalar(v):
+                history.append(v)
+            else:
+                history.extend(v)
+            continue
+        if k == 'COMMENT':
+            if np.isscalar(v):
+                comment.append(v)
+            else:
+                comment.extend(v)
+            continue
 
-    meta.update(header)
+        if k in nmeta:
+            # as dicts are case sensitive, this can happen. Raise error
+            raise KeyError(f'Duplicated key {k}. Only dictionaries with '
+                           'unique keys are allowed.')
+        if k not in _PROCTECTED and k != '':
+            # remove protected keys
+            nmeta[k] = v
+
+    # remove protected keys with number
+    naxis = nmeta.get('NAXIS', 0)
+    tfields = nmeta.get('TFIELDS', 0)
+    for i in range(1, naxis+1):
+        if f'NAXIS{i}' in meta:
+            meta.pop(f'NAXIS{i}')
+    for i in range(1, tfields+1):
+        for k in _PROTECTED_N:
+            if f'{k}{i}' in meta:
+                meta.pop(f'{k}{i}')
 
-    # strip blank cards
-    meta.remove('', ignore_missing=True)
+    return nmeta, history, comment
 
-    # extract history and comments from meta
-    if 'history' in meta:
-        history = meta['history']
-        history = list(broadcast(history).iters[0])
-        del meta['history']
-    else:
-        history = []
 
-    if 'comment' in meta:
-        comment = meta['comment']
-        comment = list(broadcast(comment).iters[0])
-        del meta['comment']
-    else:
-        comment = []
+def _merge_and_clean_header(meta, header, wcs):
+    """Merge meta and header and clean the WCS and spurious keys."""
+    if not isinstance(meta, (dict, fits.Header)) and meta is not None:
+        raise TypeError('meta must be a dict or fits.Header. '
+                        f'Got {type(meta)}')
+    if not isinstance(header, fits.Header) and header is not None:
+        raise TypeError('header must be a fits.Header. '
+                        f'Got {type(header)}')
+    if not isinstance(wcs, WCS) and wcs is not None:
+        raise TypeError('wcs must be a astropy.wcs.WCS. '
+                        f'Got {type(wcs)}')
+
+    history = []
+    comment = []
+    fmeta = fits.Header()
+
+    for m in [meta, header]:
+        m, h, c = _normalize_and_strip_dict(m)
+        # extract history and comments from meta
+        history.extend(h)
+        comment.extend(c)
+        # merge meta and header
+        fmeta.update(m)
 
     # extract wcs from header
-    meta, wcs_ = extract_header_wcs(meta)
+    meta, wcs_ = extract_header_wcs(fmeta)
+    if wcs_ and wcs:
+        raise ValueError('meta and wcs offer a WCS. Use only one.')
     wcs = wcs_ if wcs is None else wcs
     return meta, wcs, history, comment
 
 
-class EmptyDataError(ValueError):
-    """Operation not handled by empty MemMapArray containers."""
-
-
 def _extract_fits(obj, hdu=0, unit=None, hdu_uncertainty=_HDU_UNCERT,
-                  hdu_mask=_HDU_MASK, unit_key=_UNIT_KEY):
+                  hdu_flags=_HDU_FLAGS, hdu_mask=_HDU_MASK,
+                  unit_key=_UNIT_KEY):
     """Extract data and meta from FITS files and HDUs."""
     if isinstance(obj, (str, bytes, PathLike)):
         hdul = fits.open(obj)
     elif isinstance(obj, imhdus):
         hdul = fits.HDUList([obj])
     elif isinstance(obj, fits.HDUList):
         hdul = obj
@@ -204,14 +237,16 @@
     if hdu_mask in hdul:
         hdu_mask = hdul[hdu_mask]
         res['mask'] = hdu_mask.data
 
     if isinstance(obj, (str, bytes, PathLike)):
         hdul.close()
 
+    # TODO: extract flags
+
     return res
 
 
 def _extract_ccddata(ccd):
     """Extract data and meta from CCDData objects."""
     res = {}
     for i in ('data', 'unit', 'meta', 'mask'):
@@ -244,66 +279,66 @@
 def _to_ccddata(frame):
     """Translate a FrameData to a CCDData."""
     data = np.array(frame.data)
     unit = frame.unit
     meta = dict(frame.header)
     wcs = frame.wcs
     uncertainty = frame._unct
-    if uncertainty.empty:
-        uncertainty = None
-    else:
+    if uncertainty is not None:
         uncertainty = StdDevUncertainty(uncertainty, unit=unit)
     mask = np.array(frame.mask)
 
     return CCDData(data, unit=unit, meta=meta, wcs=wcs,
                    uncertainty=uncertainty, mask=mask)
 
 
-def _to_hdu(frame, hdu_uncertainty=_HDU_UNCERT, hdu_mask=_HDU_MASK,
-            unit_key=_UNIT_KEY, wcs_relax=True, **kwargs):
+def _to_hdu(frame, hdu_uncertainty=_HDU_UNCERT, hdu_flags=_HDU_FLAGS,
+            hdu_mask=_HDU_MASK, unit_key=_UNIT_KEY, wcs_relax=True, **kwargs):
     """Translate a FrameData to an HDUList."""
     data = frame.data.copy()
 
     # Clean header
     header = fits.Header(frame.header)
-    no_fits_std = kwargs.pop('no_fits_standard_units', False)
 
     if frame.wcs is not None:
         header.extend(frame.wcs.to_header(relax=wcs_relax),
                       update=True)
 
+    # using bare string avoids astropy complaining about electrons
+    no_fits_std = kwargs.pop('no_fits_standard_units', True)
     if no_fits_std:
         unit_string = frame.unit.to_string()
     else:
         unit_string = u.format.Fits.to_string(frame.unit)
-
     header[unit_key] = unit_string
 
     for i in frame.history:
         header['history'] = i
+    for i in frame.comment:
+        header['comment'] = i
     hdul = fits.HDUList(fits.PrimaryHDU(data, header=header))
 
-    if hdu_uncertainty and not frame._unct.empty:
+    if hdu_uncertainty and frame._unct is not None:
         uncert = frame.uncertainty
         uncert_h = fits.Header()
         uncert_h[unit_key] = unit_string
         hdul.append(fits.ImageHDU(uncert, header=uncert_h,
                                   name=hdu_uncertainty))
 
-    if hdu_mask is not None and not frame._mask.empty:
-        mask = frame.mask
-        if np.issubdtype(mask.dtype, np.bool):
-            # Fits do not support bool
-            mask = mask.astype('uint8')
-        hdul.append(fits.ImageHDU(mask, name=hdu_mask))
+    if hdu_mask:
+        mask = frame.mask.astype(np.uint8)
+        if mask is not None:
+            mask_h = fits.Header()
+            hdul.append(fits.ImageHDU(mask, header=mask_h, name=hdu_mask))
+
+    # TODO: add flags
 
     return hdul
 
 
 def _write_fits(frame, filename, overwrite=True, **kwargs):
     """Write a framedata to a fits file."""
-    # FIXME: electron unit is not compatible with fits standards
     with warnings.catch_warnings():
         # silent hierarch warnings
         warnings.filterwarnings("ignore", category=VerifyWarning)
         frame.to_hdu(**kwargs).writeto(filename, overwrite=overwrite,
                                        output_verify='silentfix')
```

### Comparing `astropop-0.5.4/astropop/framedata/framedata.py` & `astropop-0.9.0/astropop/framedata/framedata.py`

 * *Files 16% similar despite different names*

```diff
@@ -1,70 +1,60 @@
-# Licensed under a 3-clause BSD style license - see LICENSE.rst
-"""Custom frame class to support memmapping."""
+"""Custom frame class to support memmapping.
 
-# Important: We reimplemented and renamed astropy's frame to better
-# handle disk memmap and an easier unit/uncertainty workflow
+We reimplemented and renamed astropy's frame to better handle disk memmap and
+an easier unit/uncertainty workflow
+"""
+
+# Important:
 
 import os
-import numpy as np
 import copy as cp
+import numpy as np
 import tempfile
+from enum import Flag
 from astropy import units as u
 from astropy.io import fits
 from astropy.wcs import WCS
 
-from ..py_utils import check_iterable
-from .memmap import MemMapArray
-from .compat import _to_ccddata, _to_hdu, _merge_and_clean_header, _write_fits
+from ..flags import mask_from_flags
+from ._memmap import create_array_memmap, delete_array_memmap, \
+                     reset_memmap_array
+from ._compat import _merge_and_clean_header, _to_hdu, _to_ccddata, _write_fits
 from .._unit_property import unit_property
 
 
-__all__ = ['FrameData']
+__all__ = ['FrameData', 'PixelMaskFlags']
 
 
-def _get_shape(d):
-    if hasattr(d, 'shape'):
-        ds = d.shape
-    else:
-        ds = np.array(d).shape
-    return ds
-
-
-def shape_consistency(data=None, uncertainty=None, mask=None):
+def shape_consistency(data=None, uncertainty=None, mask=None, flags=None):
     """Check shape consistency across `data`, `uncertaitny` and `mask`."""
-    if data is None and uncertainty is not None:
-        raise ValueError('Uncertainty set for an empty data.')
-    if data is None and mask not in (None, False):
-        raise ValueError('Mask set for an empty data.')
-
-    dshape = _get_shape(data)
-
-    if uncertainty is not None:
-        ushape = _get_shape(uncertainty)
-
-        if ushape == ():
-            uncertainty = np.ones(dshape)*uncertainty
-            ushape = uncertainty.shape
-
-        if ushape != dshape:
-            raise ValueError(f'Uncertainty shape {ushape} don\'t match'
-                             f' Data shape {dshape}.')
-
-    if mask is not None:
-        mshape = _get_shape(mask)
+    dshape = np.shape(data)
 
-        if mshape == ():
-            mask = np.logical_or(np.zeros(dshape), mask)
-            mshape = mask.shape
+    def _check(arr, name, replicate=False):
+        if arr is None:
+            return
+        if arr is not None and data is None:
+            raise ValueError(f'{name} set for an empty data.')
+        ashape = np.shape(arr)
+
+        # if replicate, create an array full of value
+        if ashape == () and replicate:
+            arr = np.full(dshape, fill_value=arr)
+            ashape = arr.shape
 
-        if mask.shape != dshape:
-            raise ValueError(f'Mask shape {mshape} don\'t match'
+        if ashape != dshape:
+            raise ValueError(f'{name} shape {ashape} don\'t match'
                              f' Data shape {dshape}.')
+        return arr
 
-    return data, uncertainty, mask
+    uncertainty = _check(uncertainty, 'Uncertainty', replicate=True)
+    mask = _check(mask, 'Mask', replicate=False)
+    flags = _check(flags, 'Flags', replicate=False)
+
+    return data, uncertainty, mask, flags
 
 
 def extract_units(data, unit):
     """Extract and compare units if they are consistent."""
     if hasattr(data, 'unit'):
         dunit = u.Unit(data.unit)
     else:
@@ -142,180 +132,160 @@
 
     frame.cache_folder = cache_folder
     frame.cache_filename = filename
 
     return os.path.join(cache_folder, filename)
 
 
+class PixelMaskFlags(Flag):
+    """Flags for pixel masking."""
+    # Type of Masking
+    INTERPOLATED = 1 << 0  # pixel interpolated from neighbors
+    MASKED = 1 << 1  # pixel value removed
+    REMOVED = 1 << 1  # same of masked. Both are equal
+    # Cause of problem
+    DEAD = 1 << 2  # dead pixel
+    BAD = 1 << 3  # bad pixel
+    SATURATED = 1 << 4  # saturated pixel, above a threshold level
+    COSMIC_RAY = 1 << 5  # cosmic ray
+    OUT_OF_BOUNDS = 1 << 6  # registered image. Pixel is out of the bounds
+    UNSPECIFIED = 1 << 7  # not specified
+
+
+# Store this flags as uint8
+PixelMaskFlags.dtype = np.uint8
+
+
 @unit_property
 class FrameData:
     """Data container for image frame to handle memmapping data from disk.
 
     The main difference from Astropy's `~astropy.nddata.CCDData` is the
     memmapping itself. However it handles uncertainties in a totally different
     way. It stores only StdDev uncertainty arrays. It also stores the unit.
 
     Parameters
     ----------
     data : array_like or `~astropy.units.Quantity`
         The main data values. If `~astropy.units.Quantity`, unit will be set
-        automatically.
+        automatically. If using any quantity with masks, you must set the mask
+        in a separate parameter.
     unit : `~astropy.units.Unit` or string (optional)
         The data unit. Must be `~astropy.units.Unit` compliant.
     dtype : string or `~numpy.dtype` (optional)
         Mandatory dtype of the data.
     uncertainty : array_like or `~astropy.nddata.Uncertanty` or `None` \
                     (optional)
         Uncertainty of the data.
-    u_dtype : string or `~numpy.dtype` (optional)
-        Mandatory dtype of uncertainty.
     mask : array_like or `None` (optional)
-        Frame mask.
-    m_dtype : string or `~numpy.dtype` (optional)
-        Mandatory dtype of mask. Default `bool`compilant
+        Frame mask. All the masked pixels will be flagged as
+        `PixelMaskFlags.MASKED` and `PixelMaskFlags.UNSPECIFIED`.
+    flags : array_like or `None` (optional)
+        Pixel flags for the frame. See `~astropop.FrameData.PixelMaskFlags`.
+        for values.
     wcs : `dict`, `~astropy.fits.Header` or `~astropy.wcs.WCS` (optional)
         World Coordinate System of the image.
     meta or header: `dict` or `astropy.fits.Header` (optional)
         Metadata (header) of the frame. If both set, they will be merged.
         `header` priority.
     cache_folder : string, `~pathlib.Path` or `None` (optional)
         Place to store the cached `FrameData`
     cache_filename : string, `~pathlib.Path` or `None` (optional)
         Base file name to store the cached `FrameData`.
+    origin_filename : string, `~pathlib.Path` or `None` (optional)
+        Original file name of the data. If set, it will be stored in the
+        `FrameData` metadata.
     use_memmap_backend : `bool` (optional)
         True if enable memmap in constructor.
 
     Notes
     -----
     - The physical unit is assumed to be the same for data and uncertainty.
       So, we droped the support for data with data with different uncertainty
       unit, like `~astropy.nddata.ccddata.CCDData` does.
     - As this is intended to be a safe container for data, it do not handle
       builtin math operations. For math operations using FrameData, check
       `~astropop.ccd_processing.imarith` module.
     """
 
-    # TODO: write_fits
-
     _memmapping = False
     _unit = None
     _data = None
-    _mask = None
+    _flags = None
     _unct = None
     _wcs = None
     _meta = None
     _origin = None
     _history = None
     _comments = None
+    cache_folder = None
+    cache_filename = None
 
-    def __init__(self, data, unit=None, dtype=None,
-                 uncertainty=None, u_dtype=None,
-                 mask=None, m_dtype=bool,
-                 wcs=None, meta=None, header=None,
-                 cache_folder=None, cache_filename=None,
-                 use_memmap_backend=False, origin_filename=None):
-
-        self.cache_folder = cache_folder
-        self.cache_filename = cache_filename
+    def __init__(self, data, unit=None, dtype=None, uncertainty=None,
+                 mask=None, flags=None, wcs=None, meta=None, header=None,
+                 cache_folder=None, cache_filename=None, origin_filename=None,
+                 use_memmap_backend=False):
+        # setup names
+        setup_filename(self, cache_folder, cache_filename)
         self._origin = origin_filename
 
-        # Setup MemMapArray instances
-        cache_file = setup_filename(self, self.cache_folder,
-                                    self.cache_filename)
-        self._update_cache_files(cache_file)
-
-        # Check for memmapping.
-        self._memmapping = False
-        if use_memmap_backend:
-            self.enable_memmap()
-
-        # Masking handle
-        if hasattr(data, 'mask'):
-            dmask = data.mask
-            if mask is not None:
-                mask = np.logical_or(dmask, mask)
-            else:
-                mask = dmask
-        if mask is None:  # Default do not mask anything
-            mask = False
+        # Ensure data is not None
+        if len(np.shape(data)) != 2:
+            raise ValueError('Data must be 2D array.')
+        if dtype is not None:
+            dtype = np.dtype(dtype)
+            if dtype.kind != 'f':
+                raise ValueError('Data dtype must be float.')
+        else:
+            dtype = np.dtype('f8')
 
         # raise errors if incompatible shapes
-        data, uncertainty, mask = shape_consistency(data, uncertainty, mask)
+        data, uncertainty, mask, flags = shape_consistency(data, uncertainty,
+                                                           mask, flags)
         # raise errors if incompatible units
         unit = extract_units(data, unit)
         self.unit = unit
-        self._data.reset_data(data, dtype)
-        self._unct.reset_data(uncertainty, u_dtype)
-        # Masks can also be flags (uint8)
-        self._mask.reset_data(mask, m_dtype)
+
+        # setup flags and mask
+        if flags is None:
+            flags = np.zeros_like(data, dtype=PixelMaskFlags.dtype)
+
+        # set data to the variables
+        self._data = np.asarray(data, dtype=dtype)
+        self.flags = np.asarray(flags, dtype=PixelMaskFlags.dtype)
+        self.uncertainty = uncertainty
+        # create flag for masked pixels
+        if mask is not None:
+            mask = np.asarray(mask, dtype=bool)
+            self.add_flags(PixelMaskFlags.MASKED | PixelMaskFlags.UNSPECIFIED,
+                           mask)
+
+        # Check for memmapping.
+        self._memmapping = False
+        if use_memmap_backend:
+            self.enable_memmap()
 
         # avoiding security problems
         self._history = []
         self._comments = []
         self._meta = fits.Header()
         self._header_update(header, meta, wcs)
 
     def _header_update(self, header, meta=None, wcs=None):
         # merge header and meta. meta with higher priority
         meta, wcs, history, comment = _merge_and_clean_header(meta, header,
                                                               wcs)
         if len(history) > 0:
             self.history = history
         if len(comment) > 0:
-            self.comments = comment
+            self.comment = comment
         if wcs is not None:
             self._wcs = wcs
         self._meta = meta
 
-    def _update_cache_files(self, cache_file):
-        # TODO: if cache folder is changing, remove it
-        if self._data is not None:
-            self._data.disable_memmap(remove=True)
-            nd = self._data._contained
-        else:
-            nd = None
-        if self._unct is not None:
-            self._unct.disable_memmap(remove=True)
-            nu = self._unct._contained
-        else:
-            nu = None
-        if self._mask is not None:
-            self._mask.disable_memmap(remove=True)
-            nm = self._mask._contained
-        else:
-            nm = None
-
-        self._data = MemMapArray(nd, filename=cache_file + '.data')
-        self._unct = MemMapArray(nu, filename=cache_file + '.unct')
-        self._mask = MemMapArray(nm, filename=cache_file + '.mask')
-
-    @property
-    def history(self):
-        """Get the FrameData stored history."""
-        return self._history
-
-    @history.setter
-    def history(self, value):
-        if check_iterable(value):
-            self._history = self._history + list(value)
-        else:
-            self._history.append(value)
-
-    @property
-    def comment(self):
-        """Get the FrameData stored comments."""
-        return self._comments
-
-    @comment.setter
-    def comment(self, value):
-        if check_iterable(value):
-            self._comments = self._comments + list(value)
-        else:
-            self._comments.append(value)
-
     @property
     def origin_filename(self):
         """Get the original filename of the data."""
         return self._origin
 
     @property
     def shape(self):
@@ -323,14 +293,18 @@
         return self._data.shape
 
     @property
     def dtype(self):
         """Get the dta type of the data. `FrameData.data.dtype`."""
         return self._data.dtype
 
+    def astype(self, dtype):
+        """Return a copy of the current FrameData with new dtype in data."""
+        return self.copy(dtype)
+
     @property
     def size(self):
         """Get the size of the data. `FrameData.data.size`."""
         return self._data.size
 
     @property
     def wcs(self):
@@ -347,46 +321,91 @@
     @property
     def meta(self):
         """Get the metadata (header) of the frame."""
         return self._meta
 
     @meta.setter
     def meta(self, value):
-        self._header_update(value)
+        self._header_update(None, value)
 
     @property
     def header(self):
         """Get the header (metadata) of the frame."""
         return self._meta
 
     @property
+    def history(self):
+        """Get the FrameData stored history."""
+        return self._history
+
+    @history.setter
+    def history(self, value):
+        if not np.isscalar(value):
+            self._history = self._history + list(value)
+        else:
+            self._history.append(value)
+
+    @property
+    def comment(self):
+        """Get the FrameData stored comments."""
+        return self._comments
+
+    @comment.setter
+    def comment(self, value):
+        if not np.isscalar(value):
+            self._comments = self._comments + list(value)
+        else:
+            self._comments.append(value)
+
+    @property
     def data(self):
         """Get the main data container."""
         return self._data
 
     @data.setter
     def data(self, value):
         if hasattr(value, 'unit'):
             dunit = extract_units(value, None)
             self.unit = dunit
-        self._data.reset_data(value)
+        self._data = reset_memmap_array(self._data, value)
+
+    def get_masked_data(self, fill_value=np.nan):
+        """Return a copy of the data with masked pixels as `fill_value`."""
+        d = self.data.copy()
+        d[self.mask] = fill_value
+        return d
 
     @property
     def uncertainty(self):
         """Get the uncertainty frame container."""
         return self._unct
 
     @uncertainty.setter
     def uncertainty(self, value):
         if value is None:
-            self._unct.reset_data(value)
+            self._unct = None
+            # do not delete earlier to avoid security issues if other parts of
+            # the code raises error
+            delete_array_memmap(self._unct, read=False, remove=True)
+            return
+
+        # Put is valid containers
+        if np.isscalar(value):
+            value = float(value)
         else:
-            _, value, _ = shape_consistency(self.data, value, None)
-            value = uncertainty_unit_consistency(self.unit, value)
-            self._unct.reset_data(value)
+            value = np.asarray(value, dtype=self.dtype)
+
+        # units and shape must be consistent
+        value = uncertainty_unit_consistency(self.unit, value)
+        _, value, _, _ = shape_consistency(self.data, uncertainty=value)
+
+        # ensure that the memmap is removed
+        self._unct = delete_array_memmap(self._unct, read=False, remove=True)
+        self._unct = value
+        self._update_memmaps()
 
     def get_uncertainty(self, return_none=True):
         """Get the uncertainty frame in a safer way.
 
         In some cases, like interfacing with QFloat, the uncertainty cannot be
         None or an empty container. So, in cases like this, is prefered to get
         a whole matrix containing zeroes. This method is responsible for this
@@ -396,158 +415,203 @@
         Parameters
         ----------
         - return_none: bool (optional)
           If True, an empty uncertainty frame will return only None. Else, a
           matrix filled with zeroes will be returned.
           Default: True
         """
-        if self._unct.empty and return_none:
+        if self._unct is None and return_none:
             return None
-        if self._unct.empty:
-            return np.zeros_like(self._data, dtype=self.dtype)
+        elif self._unct is None:
+            return np.zeros_like(self.data)
         return np.array(self._unct, dtype=self.dtype)
 
     @property
-    def mask(self):
-        """Access mask data."""
-        return self._mask
+    def flags(self):
+        """Get the flags frame container."""
+        return self._flags
 
-    @mask.setter
-    def mask(self, value):
-        _, _, value = shape_consistency(self.data, None, value)
-        self._mask.reset_data(value)
+    @flags.setter
+    def flags(self, value):
+        if value is None:
+            self._flags = None
+            # do not delete earlier to avoid security issues if other parts of
+            # the code raises error
+            delete_array_memmap(self._flags, read=False, remove=True)
+            return
+
+        # Put is valid containers
+        if np.isscalar(value):
+            raise ValueError('Flags cannot be scalar.')
+        elif hasattr(value, 'unit'):
+            raise ValueError('Flags cannot have units.')
+        else:
+            value = np.asarray(value, dtype=PixelMaskFlags.dtype)
+        _, _, _, flags = shape_consistency(self.data, flags=value)
 
-    def astype(self, dtype):
-        """Return a copy of the current FrameData with new dtype in data."""
-        return self.copy(dtype)
+        self._flags = value
+        self._update_memmaps()
 
-    def copy(self, dtype=None):
-        """Copy the current FrameData to a new instance.
+    def add_flags(self, flag, where):
+        """Add a given flag to the pixels in the given positions.
 
         Parameters
         ----------
-        - dtype: `~numpy.dtype` (optional)
-            Data type for the copied FrameData. If `None`, the data type will
-            be the same as the original Framedata.
-            Default: `None`
+        flag : `PixelMaskFlags`
+            Flag to be added.
+        where : `~numpy.ndarray`
+            Positions where the flag will be added.
         """
-        data = np.array(self._data) if not self._data.empty else None
-        mask = np.array(self._mask) if not self._mask.empty else None
-        unct = np.array(self._unct) if not self._unct.empty else None
-        unit = self._unit
-        wcs = cp.copy(self._wcs)
-        meta = fits.Header(self._meta, copy=True)
-        hist = cp.copy(self._history)
-        comm = cp.copy(self._comments)
-        fname = self._origin
-        cache_folder = self.cache_folder
-        cache_fname = self.cache_filename
+        if not isinstance(flag, PixelMaskFlags):
+            raise TypeError('Flag must be a PixelMaskFlags instance.')
+        self._flags[where] |= flag.value
 
-        if dtype is not None:
-            data = data.astype(dtype) if data is not None else data
-            unct = unct.astype(dtype) if unct is not None else unct
+    @property
+    def mask(self):
+        """Mask all flagged pixels. True for all masked/removed pixels."""
+        return self.mask_flags(PixelMaskFlags.MASKED)
 
-        if cache_fname is not None:
-            cache_fname = cache_fname + '_copy'
+    def mask_flags(self, flags):
+        """Get a mask pixels with an specific flag.
+
+        Parameters
+        ----------
+        flags: list of `PixelMaskFlags` or `PixelMaskFlags`
+
+        Returns
+        -------
+        mask: `~numpy.ndarray`
+            Masked pixels. True for masked pixels.
+        """
+        return mask_from_flags(self._flags, flags,
+                               allowed_flags_class=PixelMaskFlags)
+
+    def mask_pixels(self, pixels):
+        """Mask pixels.
 
-        nframe = FrameData(data, unit=unit, mask=mask, uncertainty=unct,
-                           meta=meta, cache_folder=cache_folder,
-                           cache_filename=cache_fname, origin_filename=fname)
-        nframe.history = hist
-        nframe.comments = comm
-        nframe.wcs = wcs
-        return nframe
+        Parameters
+        ----------
+        pixels: `~numpy.ndarray` or tuple
+            Pixels to be masked. Can be a tuple of (y, x) positions or a
+            boolean array where True means masked. Uses the same standard as
+            `~numpy.ndarray`[pixels] access.
+        """
+        self._flags[pixels] |= PixelMaskFlags.MASKED.value
 
     def enable_memmap(self, filename=None, cache_folder=None):
         """Enable array file memmapping.
 
         Parameters
         ----------
         filename : str, optional
             Custom memmap file name.
         cache_folder : str, optional
             Custom folder to cache data.
         """
-        if filename is None and cache_folder is None:
-            self._data.enable_memmap()
-            self._unct.enable_memmap()
-            self._mask.enable_memmap()
-        else:
-            cache_file = setup_filename(self, cache_folder, filename)
-            self._update_cache_files(cache_file)
-            self._data.enable_memmap(cache_file + '.data')
-            self._mask.enable_memmap(cache_file + '.mask')
-            self._unct.enable_memmap(cache_file + '.unct')
+        # early return for already memmapped
+        if self._memmapping:
+            return
+
+        # get the default files if names are not provided
+        if filename is None:
+            filename = self.cache_filename
+        if cache_folder is None:
+            cache_folder = self.cache_folder
+
+        # delete the old memmap files if they are memmaps
+        self.disable_memmap()
+
+        # setup the new filenames
+        cache_file = setup_filename(self, cache_folder, filename)
+
+        # create the memmap files
         self._memmapping = True
+        self._update_memmaps(cache_file)
 
     def disable_memmap(self):
         """Disable frame file memmapping (load to memory)."""
-        self._data.disable_memmap(remove=True)
-        self._mask.disable_memmap(remove=True)
-        self._unct.disable_memmap(remove=True)
+        self._data = delete_array_memmap(self._data, read=True, remove=True)
+        self._flags = delete_array_memmap(self._flags, read=True, remove=True)
+        self._unct = delete_array_memmap(self._unct, read=True, remove=True)
         self._memmapping = False
 
-    def to_hdu(self, **kwargs):
-        """Generate an HDUList from this FrameData.
+    def _update_memmaps(self, cache_file=None):
+        """Update the memmap files."""
+        if cache_file is None:
+            cache_file = setup_filename(self)
+        if self._memmapping:
+            if not isinstance(self._data, np.memmap):
+                self._data = create_array_memmap(cache_file + '.data',
+                                                 self._data)
+            if not isinstance(self._flags, np.memmap) and \
+               self._flags is not None:
+                self._flags = create_array_memmap(cache_file + '.flags',
+                                                  self._flags)
+            if not isinstance(self._unct, np.memmap) and \
+               self._unct is not None:
+                self._unct = create_array_memmap(cache_file + '.unct',
+                                                 self._unct)
+
+    def copy(self, dtype=None):
+        """Copy the current FrameData to a new instance.
 
         Parameters
         ----------
-        hdu_uncertainty: string, optional
-            Extension name to store the uncertainty. If None,
-            no uncertainty will be stored.
-        hdu_mask: string, optional
-            Extension name to store the mask. If None, no mask
-            will be saved.
-        unit_key: string, optional
-            Header key for physical unit.
-        wcs_relax: `bool`, optional.
-            Allow non-standard WCS keys.
-            Default: `True`
-        no_fits_standard_units: `bool`, optional
-            Skip FITS units standard for units. If this options is choose,
-            the units will be printed in header as `~astropy.units.Unit`
-            compatible string.
-            Default: `False`
-
-        Returns
-        -------
-        `~astropy.fits.HDUList` :
-            HDU storing all FrameData informations.
+        - dtype: `~numpy.dtype` (optional)
+            Data type for the copied FrameData. If `None`, the data type will
+            be the same as the original Framedata.
+            Default: `None`
         """
-        return _to_hdu(self, **kwargs)
+        nf = object.__new__(FrameData)
+        # copy metadata
+        nf._history = cp.deepcopy(self._history)
+        nf._comments = cp.deepcopy(self._comments)
+        nf._meta = cp.deepcopy(self._meta)
+        nf._wcs = cp.deepcopy(self._wcs)
+        nf._unit = self._unit
+
+        # file naming
+        cache_fname = self.cache_filename
+        if cache_fname is not None:
+            cache_fname = cache_fname + '_copy'
+        nf._origin = self._origin
+        nf.cache_folder = self.cache_folder
+        nf.cache_filename = cache_fname
+
+        # copy data
+        nf._data = delete_array_memmap(self._data, read=True, remove=False)
+        if dtype is not None:
+            nf._data = nf._data.astype(dtype)
+        nf._flags = delete_array_memmap(self._flags, read=True, remove=False)
+        if self._unct is not None:
+            nf._unct = delete_array_memmap(self._unct, read=True, remove=False)
+            if dtype is not None:
+                nf._unct = nf._unct.astype(dtype)
+
+        # copy memmapping
+        if self._memmapping:
+            nf.enable_memmap()
+
+        return nf
+
+    def __copy__(self):
+        """Copy the current instance to a new one."""
+        return self.copy()
 
     def __del__(self):
         """Safe destruction of the container."""
         # ensure all files are removed when exit
         self.disable_memmap()
         # remove tmp folder if empty
         try:
             if len(os.listdir(self.cache_folder)) == 0:
                 os.rmdir(self.cache_folder)
-        except FileNotFoundError:
+        except (FileNotFoundError, TypeError):
             pass
 
-    def to_ccddata(self):
-        """Convert actual FrameData to CCDData.
-
-        Returns
-        -------
-        `~astropy.nddata.CCDData` :
-            CCDData instance with actual FrameData informations.
-        """
-        return _to_ccddata(self)
-
-    def write(self, filename, overwrite=False, **kwargs):
-        """Write frame to a fits file."""
-        _write_fits(self, filename, overwrite, **kwargs)
-
-    def __copy__(self):
-        """Copy the current instance to a new one."""
-        return self.copy()
-
     def median(self, **kwargs):
         """Compute and return the median of the data."""
         med = np.median(self._data, **kwargs)
         if self._unit is None:
             return med
         return med * self.unit
 
@@ -578,7 +642,78 @@
     def statistics(self):
         """Compute general statistics ofthe image."""
         return {'min': self.min(),
                 'max': self.max(),
                 'mean': self.mean(),
                 'median': self.median(),
                 'std': self.std()}
+
+    def to_hdu(self, wcs_relax=True, no_fits_standard_units=True, **kwargs):
+        """Generate an HDUList from this FrameData.
+
+        Parameters
+        ----------
+        wcs_relax: `bool`, optional.
+            Allow non-standard WCS keys.
+            Default: `True`
+        no_fits_standard_units: `bool`, optional
+            Skip FITS units standard for units. If this options is choose,
+            the units will be printed in header as `~astropy.units.Unit`
+            compatible string.
+            Default: `True`
+        **kwargs:
+            hdu_uncertainty: string, optional
+                Extension name to store the uncertainty in 2D image format.
+            hdu_flags: string, optional
+                Extension name to store the pixel list flags in table format.
+            unit_key: string, optional
+                Header key for physical unit.
+
+
+        Returns
+        -------
+        `~astropy.fits.HDUList` :
+            HDU storing all FrameData informations.
+        """
+        return _to_hdu(self, wcs_relax=wcs_relax,
+                       no_fits_standard_units=no_fits_standard_units,
+                       **kwargs)
+
+    def to_ccddata(self):
+        """Convert actual FrameData to CCDData.
+
+        Returns
+        -------
+        `~astropy.nddata.CCDData` :
+            CCDData instance with actual FrameData informations.
+        """
+        return _to_ccddata(self)
+
+    def write(self, filename, overwrite=False, no_fits_standard_units=True,
+              **kwargs):
+        """Write frame to a fits file.
+
+        Parameters
+        ----------
+        filename: str
+            Name of the file to write.
+        overwrite: bool, optional
+            If True, overwrite the file if it exists.
+        wcs_relax: `bool`, optional.
+            Allow non-standard WCS keys.
+            Default: `True`
+        no_fits_standard_units: `bool`, optional
+            Skip FITS units standard for units. If this options is choose,
+            the units will be printed in header as `~astropy.units.Unit`
+            compatible string.
+            Default: `True`
+        **kwargs:
+            hdu_uncertainty: string, optional
+                Extension name to store the uncertainty in 2D image format.
+            hdu_flags: string, optional
+                Extension name to store the pixel list flags in table format.
+            unit_key: string, optional
+                Header key for physical unit.
+        """
+        _write_fits(self, filename, overwrite,
+                    no_fits_standard_units=no_fits_standard_units,
+                    **kwargs)
```

### Comparing `astropop-0.5.4/astropop/framedata/util.py` & `astropop-0.9.0/astropop/framedata/util.py`

 * *Files 13% similar despite different names*

```diff
@@ -1,19 +1,18 @@
 # Licensed under a 3-clause BSD style license - see LICENSE.rst
 """Utilities for loading data as FrameData."""
 
 import os
 import numpy as np
 from astropy.io import fits
+from astropy.units import Quantity
 from astropy.nddata import CCDData
-from astropy import units as u
 
 from .framedata import FrameData
-from .compat import _extract_ccddata, _extract_fits, imhdus
-from .memmap import MemMapArray
+from ._compat import _extract_ccddata, _extract_fits, imhdus
 
 
 __all__ = ['check_framedata', 'read_framedata']
 
 
 _fits_kwargs = ['hdu', 'unit', 'hdu_uncertainty',
                 'hdu_mask', 'unit_key']
@@ -55,19 +54,18 @@
     elif isinstance(obj, (str, bytes, os.PathLike, fits.HDUList, *imhdus)):
         # separate kwargs to be sent to extractors
         fits_kwargs = {}
         for k in _fits_kwargs:
             if k in kwargs.keys():
                 fits_kwargs[k] = kwargs.pop(k)
         obj = FrameData(**_extract_fits(obj, **fits_kwargs), **kwargs)
-    elif isinstance(obj, (np.ndarray, MemMapArray)):
-        if isinstance(obj, u.Quantity):
-            obj = FrameData(obj.value, unit=obj.unit, **kwargs)
-        else:
-            obj = FrameData(obj, **kwargs)
+    elif isinstance(obj, Quantity):
+        obj = FrameData(obj.value, unit=obj.unit, **kwargs)
+    elif isinstance(obj, np.ndarray):
+        obj = FrameData(obj, **kwargs)
     elif obj.__class__.__name__ == "QFloat":
         # if not do this, a cyclic dependency breaks the code.
         obj = FrameData(obj.nominal, unit=obj.unit,
                         uncertainty=obj.uncertainty, **kwargs)
     else:
         raise TypeError(f'Object {obj} is not compatible with FrameData.')
```

### Comparing `astropop-0.5.4/astropop/image/imarith.py` & `astropop-0.9.0/astropop/image/imarith.py`

 * *Files 24% similar despite different names*

```diff
@@ -1,13 +1,15 @@
 # Licensed under a 3-clause BSD style license - see LICENSE.rst
 """Perform math operations with astronomical images in FrameData contianer."""
 
 import numpy as np
 from astropy.units.core import UnitConversionError
 
+from ._tools import merge_header
+from ._tools import merge_flag
 from ..framedata import FrameData
 from ..math.physical import QFloat, convert_to_qfloat, UnitsError
 from ..logger import logger, log_to_list
 
 
 __all__ = ['imarith']
 
@@ -24,48 +26,24 @@
 def _qf_or_framedata(data, alternative=convert_to_qfloat):
     """Check if the data is QFloat or FrameData. Else, convert it."""
     if isinstance(data, (QFloat, FrameData)):
         return data
     return alternative(data)
 
 
-def _arith_mask(operand1, operand2):
-    """Handle the arithmatics of the masks."""
-    def _extract(operand):
-        if hasattr(operand, 'mask'):
-            return operand.mask
-        return False
-
-    mask1 = _extract(operand1)
-    mask2 = _extract(operand2)
-
-    old_n = np.count_nonzero(mask1)
-    nmask = np.logical_or(mask1, mask2)
-    new_n = np.count_nonzero(nmask)
-    logger.debug('Updating mask in math operation. '
-                 'From %i to %i masked elements.', old_n, new_n)
-    return nmask
-
-
 def _arith(operand1, operand2, operation):
     """Perform the math operation itself using QFloats."""
     qf1 = convert_to_qfloat(operand1)
     qf2 = convert_to_qfloat(operand2)
 
     return _arith_funcs[operation](qf1, qf2)
 
 
-def _join_headers(operand1, operand2, operation):  # noqa
-    """Join the headers to result."""
-    # TODO: Think if this is the best behavior
-    return operand1.header.copy()
-
-
 def imarith(operand1, operand2, operation, inplace=False,
-            join_masks=False):
+            merge_flags='or', merge_headers='only_equal', **kwargs):
     """Perform arithmetic operations using `~astropop.framedata.FrameData`.
 
     Notes
     -----
     * Keeps the header of the first image.
 
     * If ``operand1`` is not a `~astropop.framedata.FrameData` instance,
@@ -87,34 +65,49 @@
         Values to perform the operation. `~astropop.math.physical.QFloat`
         `~astropy.units.Quantity`, numerical values and
         `~astropy.nddata.CCDData` are also suported.
     operation: {``+``, ``-``, ``*``, ``/``, ``**``, ``%``, ``//``}
         Math operation.
     inplace: bool, optional
         If True, the operations will be performed inplace in the operand 1.
-    join_masks: bool, optional
-        Join masks in the end of the operation.
+    merge_flags: {'or', 'and', 'no_merge'}, optional
+        How to join the masks of the operands. If ``'or'``, the resulting mask
+        will be the union of the masks of the operands. If ``'and'``, the
+        resulting mask will be the intersection of the masks of the operands.
+        If ``'no_merge'``, the resulting mask will be only zeroes.
+    merge_headers: {'no_merge', 'first', 'only_equal', 'selected_keys'}
+        How to merge the headers of the operands. If ``'no_merge'``, the
+        resulting header will be ``None``. If ``'first'``, the resulting
+        header will be the header of the first operand. If ``'only_equal'``,
+        the resulting header will be the header of the first operand, but only
+        the keys that are equal in both operands. If ``'selected_keys'``, the
+        resulting header will be the header of the first operand, but only the
+        keys in ``selected_keys``.
+    **kwargs:
+        Additional arguments:
+            selected_keys: list, optional
+                List of keys to be merged in the header. Only used if
+                ``merge_headers='selected_keys'``.
 
     Returns
     -------
     `~astropop.framedata.FrameData`:
         new `FrameData` instance if not ``inplace``, else the ``operand1``
         `~astropop.framedata.FrameData` instance.
     """
-    # TODO: handle WCS
     if operation not in _arith_funcs.keys():
         raise ValueError(f"Operation {operation} not supported.")
 
     operand1 = _qf_or_framedata(operand1)
     operand2 = _qf_or_framedata(operand2)
 
     if isinstance(operand1, FrameData) and inplace:
         ccd = operand1
     else:
-        ccd = FrameData(None)
+        ccd = object.__new__(FrameData)
 
     # Add the operation entry to the ccd history.
     lh = log_to_list(logger, ccd.history)
     logger.debug('Operation %s between %s and %s',
                  operation, operand1, operand2)
 
     # Perform data, mask and uncertainty operations
@@ -124,17 +117,22 @@
         raise UnitsError(f'Units {operand1.unit} and {operand2.unit} are'
                          f' incompatible for {operation} operation.')
 
     ccd.data = result.nominal
     ccd.unit = result.unit
     ccd.uncertainty = result.uncertainty
 
-    if join_masks:
-        ccd.mask = _arith_mask(operand1, operand2)
-    else:
-        ccd.mask = False
-
-    ccd.meta = _join_headers(operand1, operand2, operation)
+    # Perform merging flags operation only if both operands have flags
+    f1 = getattr(operand1, 'flags',
+                 np.zeros_like(operand1.data, dtype=np.uint8))
+    f2 = getattr(operand2, 'flags',
+                 np.zeros_like(operand1.data, dtype=np.uint8))
+    ccd.flags = merge_flag(f1, f2, method=merge_flags)
+
+    # Perform merging headers operation only if both operands have headers
+    h1 = getattr(operand1, 'header', {})
+    h2 = getattr(operand2, 'header', {})
+    keys = kwargs.get('selected_keys', None)
+    ccd.meta = merge_header(h1, h2, method=merge_headers, selected_keys=keys)
 
     logger.removeHandler(lh)
-
     return ccd
```

### Comparing `astropop-0.5.4/astropop/image/imcombine.py` & `astropop-0.9.0/astropop/image/imcombine.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,18 +5,15 @@
 from tempfile import mkdtemp
 import numpy as np
 from astropy.stats import mad_std
 
 from ..framedata import FrameData, check_framedata
 from ..py_utils import check_iterable, check_number
 from ..logger import logger
-from ..math.array import all_equal
-
-
-# TODO: verify why cache_folder is not being used
+from ._tools import merge_header
 
 
 # bottleneck has faster median
 try:
     import bottleneck as bn
     _funcs = {
         'median': bn.nanmedian,
@@ -134,14 +131,36 @@
 
     logger.debug('Rejected %i pixels by minmax method.',
                  np.sum(mask))
 
     return mask
 
 
+def _yield_slices(shape, n_chunks):
+    """Yield slices for a given shape and number of chunks."""
+    if n_chunks == 1:
+        # values ust be specified for later in code
+        yield slice(0, shape[0]), slice(0, shape[1])
+    else:
+        y_shp, x_shp = shape
+        # split in y (rows) first
+        ystep = int(max(1, np.floor(y_shp/n_chunks)))
+        ychunks = int(np.ceil(y_shp/ystep))
+        if ychunks >= n_chunks:
+            xstep = x_shp
+        else:
+            # divide in x if needed
+            xchunks = int(n_chunks/ychunks) + 1
+            xstep = int(max(1, np.floor(x_shp/xchunks)))
+        for y in range(0, y_shp, ystep):
+            for x in range(0, x_shp, xstep):
+                yield (slice(y, min(y_shp, y+ystep)),
+                       slice(x, min(x_shp, x+xstep)))
+
+
 class ImCombiner:
     """Process the combining operation of images, like the IRAF imcombine."""
 
     _sigma_clip = None  # sigmaclip thresholds
     _sigma_cen_func = None  # sigmaclip central function
     _sigma_dev_func = None  # sigmaclip deviation function
     _minmax = None  # minmax clipping parameters
@@ -361,70 +380,59 @@
                 raise ValueError(f"Image {i} has a unit incompatible with "
                                  "the others")
         self._shape = base_shape
         self._unit = base_unit
 
     def _chunk_yielder(self, method):
         """Split the data in chuncks according to the method."""
-        # sum needs uncertainties
-        unct = None
+        # sum needs uncertainties, others ignore it
+        unct = False
         if method == 'sum':
-            if not np.any([i.uncertainty.empty for i in self._images]):
+            if not np.any([i.uncertainty is None for i in self._images]):
                 unct = True
             else:
-                logger.info('One or more frames have empty uncertainty. '
-                            'Some features are disabled.')
+                logger.debug('One or more frames have empty uncertainty. '
+                             'Some features are disabled.')
 
+        # flags and uncertainty are ignored
         shape = self._images[0].shape
         tot_size = self._images[0].data.nbytes
-        tot_size += self._images[0].mask.nbytes
         tot_size *= len(self._images)
         # uncertainty is ignored
 
         # adjust memory usage for numpy and bottleneck, based on ccdproc
         if method == 'median':
             tot_size *= 4.5
         else:
             tot_size *= 3
 
         n_chunks = np.ceil(tot_size/self._max_memory)
-
-        # compute x and y steps
-        xstep = max(1, int(shape[0]/n_chunks))
-        if shape[0] >= n_chunks:
-            ystep = shape[1]
-        else:
-            ystep = max(1, int(np.ceil(shape[1]/(n_chunks/shape[0]))))
-
-        n_chunks = np.ceil(shape[0]/xstep)*np.ceil(shape[1]/ystep)
+        slices = list(_yield_slices(shape, n_chunks))
         if n_chunks > 1:
-            logger.debug('Splitting the images into %i chunks.', n_chunks)
+            logger.debug('Splitting the images into %i chunks.', len(slices))
 
-        for x in range(0, shape[0], xstep):
-            for y in range(0, shape[1], ystep):
-                slc_x = slice(x, min(x+xstep, shape[0]))
-                slc_y = slice(y, min(y+ystep, shape[1]))
-                shp = slc_x.stop-slc_x.start, slc_y.stop-slc_y.start
-                slc = (slc_x, slc_y)
-                buffer = np.full((len(self._images), shp[0], shp[1]),
-                                 fill_value=np.nan, dtype=self._dtype)
+        for slc_y, slc_x in slices:
+            buff_shp = (len(self._images),
+                        slc_y.stop-slc_y.start,
+                        slc_x.stop-slc_x.start)
+            buffer = np.full(buff_shp, fill_value=np.nan, dtype=self._dtype)
+            if unct:
+                unct_buffer = np.full(buff_shp, fill_value=np.nan,
+                                      dtype=self._dtype)
+            else:
+                unct_buffer = None
+
+            for i, frame in enumerate(self._images):
+                buffer[i] = frame.data[slc_y, slc_x]
+                buffer[i][frame.mask[slc_y, slc_x]] = np.nan
                 if unct:
-                    unct_buffer = np.full((len(self._images), shp[0], shp[1]),
-                                          fill_value=np.nan, dtype=self._dtype)
-                else:
-                    unct_buffer = None
-
-                for i in range(len(self._images)):
-                    buffer[i] = self._images[i].data[slc]
-                    buffer[i][self._images[i].mask[slc]] = np.nan
-                    if unct:
-                        unct_buffer[i] = self._images[i].uncertainty[slc]
-                        unct_buffer[i][self._images[i].mask[slc]] = np.nan
+                    unct_buffer[i] = frame.uncertainty[slc_y, slc_x]
+                    unct_buffer[i][frame.mask[slc_y, slc_x]] = np.nan
 
-                yield buffer, unct_buffer, (slc_x, slc_y)
+            yield buffer, unct_buffer, (slc_y, slc_x)
 
     def _apply_rejection(self):
         mask = np.zeros(self._buffer[0].shape)
         if self._sigma_clip is not None:
             mask = _sigma_clip(self._buffer,
                                threshold=self._sigma_clip,
                                cen_func=self._sigma_cen_func,
@@ -438,15 +446,15 @@
 
         mask = np.logical_or(np.isnan(self._buffer), mask)
         self._buffer[mask] = np.nan
 
     def _combine(self, method, **kwargs):
         """Process the combine and compute the uncertainty."""
         # number of masked pixels for each position
-        n_masked = np.sum([np.isnan(i) for i in self._buffer], axis=0)
+        n_masked = np.sum(np.isnan(self._buffer), axis=0)
         # number of images
         n = float(len(self._buffer))
         # number of not masked pixels for each position
         n_no_mask = n - n_masked
 
         if method == 'sum':
             data = _funcs['sum'](self._buffer, axis=0)
@@ -455,15 +463,15 @@
                             ' approximation to compute the sum uncertainty.')
                 # we consider, here, that the deviation in each pixel (x, y) is
                 # the error of each image in that position. So
                 # unct = stddev*sqrt(n)
                 unct = _funcs['std'](self._buffer, axis=0)*np.sqrt(n_no_mask)
             else:
                 # direct propagate the errors in the sum
-                # unct = sqrt(sigma1^2 + sigma2^2 + ...)
+                # unct = sqrt(sigma1^2 + ) for i in sigma2^2 + ...)
                 unct = _funcs['sum'](np.square(self._unct_bf), axis=0)
                 unct = np.sqrt(unct)
 
             if kwargs.get('sum_normalize', True):
                 norm = n/n_no_mask
                 data *= norm
                 unct *= norm
@@ -472,50 +480,14 @@
             data = _funcs[method](self._buffer, axis=0)
             # uncertainty = sigma/sqrt(n)
             unct = _funcs['std'](self._buffer, axis=0)
             unct /= np.sqrt(n_no_mask)
 
         return data, unct
 
-    def _merge_header(self):
-        """Merge headers."""
-        meta = {}
-        if self._header_strategy == 'no_merge':
-            return meta
-
-        logger.debug('Merging headers with %s strategy.',
-                     self._header_strategy)
-
-        if self._header_strategy == 'first':
-            return self._images[0].header
-
-        summary = {h: [] for h in self._images[0].header.keys()}
-        for i in self._images:
-            hdr = i.header
-            for key in hdr.keys():
-                if key not in summary.keys():
-                    summary[key] = []
-                if hdr[key] not in summary[key]:
-                    summary[key].append(hdr[key])
-
-        if self._header_strategy == 'selected_keys':
-            keys = self._header_merge_keys
-        else:
-            keys = summary.keys()
-
-        for k in keys:
-            if all_equal(np.array(summary[k])):
-                meta[k] = summary[k][0]
-            elif self._header_strategy == 'selected_keys':
-                logger.debug('Keyword %s is different across headers. '
-                             'Unsing first one.', k)
-                meta[k] = summary[k][0]
-
-        return meta
-
     def combine(self, image_list, method, **kwargs):
         """Perform the image combining.
 
         Parameters
         ----------
         image_list: `list` or `tuple`
             List containing the images to be combined. The values in the list
@@ -556,33 +528,32 @@
 
         logger.info('Combining %i images with %s method.',
                     len(self._images), method)
 
         # temp combined data, mask and uncertainty
         data = np.zeros(self._shape, dtype=self._dtype)
         data.fill(np.nan)
-        mask = np.zeros(self._shape, dtype=bool)
         unct = np.zeros(self._shape, dtype=self._dtype)
+        mask = np.zeros(self._shape, dtype=bool)
 
         for self._buffer, self._unct_bf, slc in self._chunk_yielder(method):
             # perform the masking: first with minmax, after sigma_clip
             # the clippings interfere in each other.
             self._apply_rejection()
 
             # combine the images and compute the uncertainty
             data[slc], unct[slc] = self._combine(method, **kwargs)
-
-            # combine masks
-            mask[slc] = np.all([np.isnan(i) for i in self._buffer], axis=0)
-            # TODO: flag pixels with NaN as pixels with rejection
+            mask[slc] = np.isnan(data[slc])
 
         n = len(self._images)
-        combined = FrameData(data, unit=self._unit, mask=mask,
-                             uncertainty=unct)
-        combined.meta = self._merge_header()
+        combined = FrameData(data, unit=self._unit, uncertainty=unct,
+                             mask=mask)
+        combined.meta = merge_header(*[i.header for i in self._images],
+                                     method=self._header_strategy,
+                                     selected_keys=self._header_merge_keys)
         combined.meta['HIERARCH astropop imcombine nimages'] = n
         combined.meta['HIERARCH astropop imcombine method'] = method
 
         # after, clear all buffers
         self._clear()
         return combined
```

### Comparing `astropop-0.5.4/astropop/image/processing.py` & `astropop-0.9.0/astropop/image/processing.py`

 * *Files 6% similar despite different names*

```diff
@@ -3,20 +3,19 @@
 import os
 import numpy as np
 import astroscrappy
 
 from ..logger import logger
 from .imarith import imarith
 from ..math.physical import convert_to_qfloat
-from ..framedata import check_framedata
+from ..framedata import check_framedata, PixelMaskFlags
 
 
 __all__ = ['cosmics_lacosmic', 'gain_correct', 'subtract_bias',
-           'subtract_dark', 'flat_correct', 'process_image',
-           'trim_image']
+           'subtract_dark', 'flat_correct', 'trim_image']
 
 
 # TODO: replace ccdproc functions by built-in, skiping units
 # block_reduce = ccdproc.block_reduce
 # block_replicate = ccdproc.block_replicate
 
 
@@ -48,24 +47,24 @@
     -------
     `~astropop.framedata.FrameData`
         New cosmic-rays corrected `FrameData` instance if not `inplace`,
         else the `image` `~astropop.framedata.FrameData` instance.
     """
     # As lacosmic removes and replace the cosmics pixels, no need to
     # update the mask
-    _, dat = astroscrappy.detect_cosmics(frame.data, **lacosmic_kwargs)
+    mask, dat = astroscrappy.detect_cosmics(frame.data, **lacosmic_kwargs)
 
     if inplace:
         ccd = frame
     else:
         ccd = frame.copy()
 
     ccd.data = dat
-    # Do not update mask, astroscrappy replace the pixels
-    # ccd.mask &= mask
+    ccd.add_flags(PixelMaskFlags.INTERPOLATED | PixelMaskFlags.COSMIC_RAY,
+                  where=mask)
     ccd.header['HIERARCH astropop lacosmic'] = True
     return ccd
 
 
 def gain_correct(image, gain, inplace=False):
     """
     Process the gain correction of an image.
@@ -91,15 +90,16 @@
     Returns
     -------
     `~astropop.framedata.FrameData`:
         New gain corrected `FrameData` instance if not ``inplace``, else the
         ``image`` `~astropop.framedata.FrameData` instance.
     """
     gain = convert_to_qfloat(gain)
-    nim = imarith(image, gain, '*', inplace=inplace)
+    nim = imarith(image, gain, '*', inplace=inplace, merge_headers='first',
+                  merge_flags='no_merge')
     nim.header['HIERARCH astropop gain_corrected'] = True
     nim.header['HIERARCH astropop gain_corrected_value'] = gain.nominal
     nim.header['HIERARCH astropop gain_corrected_unit'] = str(gain.unit)
 
     return nim
 
 
@@ -130,15 +130,16 @@
     Returns
     -------
     `~astropop.framedata.FrameData`:
         New bias corrrected `FrameData` instance if ``inplace``, else the
         ``image`` `~astropop.framedata.FrameData` instance.
     """
     master_bias = check_framedata(master_bias)
-    nim = imarith(image, master_bias, '-', inplace=inplace)
+    nim = imarith(image, master_bias, '-', inplace=inplace,
+                  merge_headers='first', merge_flags='no_merge')
 
     nim.header['HIERARCH astropop bias_corrected'] = True
     name = master_bias.origin_filename
     if name is not None:
         nim.header['HIERARCH astropop bias_corrected_file'] = name
 
     return nim
@@ -186,15 +187,16 @@
     master_dark = check_framedata(master_dark)
     scale = image_exposure/dark_exposure
     if scale != 1:
         logger.debug('Scaling dark by %s factor to match image'
                      ' exposure.', scale)
         master_dark = imarith(master_dark, scale, "*", inplace=False)
 
-    nim = imarith(image, master_dark, '-', inplace=inplace)
+    nim = imarith(image, master_dark, '-', inplace=inplace,
+                  merge_headers='first', merge_flags='no_merge')
 
     nim.header['HIERARCH astropop dark_corrected'] = True
     nim.header['HIERARCH astropop dark_corrected_scale'] = scale
     name = master_dark.origin_filename
     if name is not None:
         name = os.path.basename(name)
         nim.header['HIERARCH astropop dark_corrected_file'] = name
@@ -233,15 +235,16 @@
         mask = master_flat.data < min_value
         master_flat.data[np.where(mask)] = min_value
 
     if norm_value is not None:
         logger.debug('Normalizing flat with %s value.', norm_value)
         master_flat = imarith(master_flat, norm_value, '/', inplace=False)
 
-    nim = imarith(image, master_flat, '/', inplace=inplace)
+    nim = imarith(image, master_flat, '/', inplace=inplace,
+                  merge_headers='first', merge_flags='no_merge')
 
     nim.header['HIERARCH astropop flat_corrected'] = True
 
     name = master_flat.origin_filename
     if name is not None:
         name = os.path.basename(name)
         nim.header['HIERARCH astropop flat_corrected_file'] = name
@@ -274,20 +277,21 @@
     # shape is always (y, x)
     x_slice = slice(0, image.shape[1]) if x_slice is None else x_slice
     y_slice = slice(0, image.shape[0]) if y_slice is None else y_slice
 
     section = (y_slice, x_slice)
 
     # trim the arrays
-    data, uncertainty, mask = (image.data, image.get_uncertainty(False),
-                               image.mask)
-    image.data = data[section]
-    image.uncertainty = uncertainty[section]
-    if not mask.empty:
-        image.mask = mask[section]
+    data = image.data[section]
+    uncertainty = image.get_uncertainty(False)[section]
+    flags = image.flags[section]
+
+    image.data = data
+    image.uncertainty = uncertainty
+    image.flags = flags
 
     # fix WCS if existing
     if image.wcs is not None:
         wcs = image.wcs.copy()
         wcs.wcs.crpix[0] -= x_slice.start
         wcs.wcs.crpix[1] -= y_slice.start
         # FIXME: this should work but is getting wrong results
@@ -299,17 +303,7 @@
         str_slice += ':'.join(str(i) if i is not None else ''
                               for i in [s.start, s.stop])
         str_slice += ','
     str_slice = str_slice[:-1]
     image.meta['HIERARCH astropop trimmed_section'] = str_slice
 
     return image
-
-
-def process_image(framedata, master_bias=None, master_dark=None,
-                  master_flat=None, gain=None, image_exposure=None,
-                  dark_exposure=None, trim=None,
-                  lacosmic=False, rebin_func=np.sum,
-                  rebin_size=None, readnoise=None, badpixmask=None,
-                  overscan=None):
-    """Process all the default steps of CCD calibration."""
-    raise NotImplementedError
```

### Comparing `astropop-0.5.4/astropop/image/register.py` & `astropop-0.9.0/astropop/image/register.py`

 * *Files 8% similar despite different names*

```diff
@@ -4,15 +4,15 @@
 import abc
 from functools import partial
 from skimage import transform
 import numpy as np
 
 from .processing import trim_image
 from ..logger import logger
-from ..framedata import check_framedata, FrameData
+from ..framedata import check_framedata, FrameData, PixelMaskFlags
 
 
 __all__ = ['CrossCorrelationRegister', 'AsterismRegister',
            'register_framedata_list', 'compute_shift_list']
 
 
 def _algorithm_check(algorithm, kwargs):
@@ -62,18 +62,23 @@
 
 class _BaseRegister(abc.ABC):
     """Base class for Registers."""
 
     _name = None
 
     @staticmethod
-    def _apply_transform_image(image, tform, cval=0):
+    def _apply_transform_image(image, tform, cval=0, order=3):
         """Apply the transform to an image."""
+        # ensure correct data types
+        image = np.array(image)
+        cval = float(cval)
+
+        # apply the transform
         return transform.warp(image, tform, mode='constant', cval=cval,
-                              preserve_range=True)
+                              preserve_range=True, order=order)
 
     @abc.abstractmethod
     def _compute_transform(self, image1, image2, mask1=None, mask2=None):
         """Compute the transform to register image2 to image1."""
 
     def compute_transform(self, image1, image2, mask1=None, mask2=None):
         """Compute the transform to register image2 to image1.
@@ -121,31 +126,36 @@
             Mask for the registered image.
         tfrom : `~skimage.transform.AffineTransform`
             Transform computed to project image2 in image2.
         """
         # equal images are just returned
         if np.all(image1 == image2):
             logger.info('Images are equal, skipping registering.')
-            return image1, np.zeros_like(image1), transform.AffineTransform()
+            return (image1, np.zeros_like(image1, dtype=bool),
+                    transform.AffineTransform(translation=(0, 0)))
 
         tform = self._compute_transform(image1, image2, mask1, mask2)
         if mask2 is None:
             mask2 = np.zeros_like(image2)
 
+        # TODO: consider the mask here
         if cval == 'median':
             cval = np.nanmedian(image2)
         if cval == 'mean':
             cval = np.nanmean(image2)
 
         reg_image = self._apply_transform_image(image2, tform, cval=cval)
         logger.info('Filling registered image with cval=%.2f', cval)
         logger.info('Registering image with: '
                     'translation=%s, rotation=%.2f°',
                     tform.translation, np.rad2deg(tform.rotation))
-        mask = self._apply_transform_image(mask2, tform, cval=1)
+
+        # use float to get partial covered pixels and mask them
+        mask = self._apply_transform_image(mask2.astype('f8'), tform, cval=1,
+                                           order=0)
         mask = mask > 0
         return reg_image, mask, tform
 
     def register_framedata(self, frame1, frame2, cval='median',
                            inplace=False):
         """Align and transform a frame2 to match frame1.
 
@@ -169,33 +179,37 @@
             Registered frame.
         """
         frame1 = check_framedata(frame1)
         frame2 = check_framedata(frame2)
 
         im1 = np.array(frame1.data)
         im2 = np.array(frame2.data)
-        msk1 = frame1.mask if frame1.mask is None else np.array(frame1.mask)
-        msk2 = frame2.mask if frame2.mask is None else np.array(frame2.mask)
+        msk1 = frame1.mask
+        msk2 = frame2.mask
 
         data, mask, tform = self.register_image(im1, im2, msk1, msk2,
                                                 cval=cval)
 
         if inplace:
             reg_frame = frame2
         else:
             # Copy the frame to mantain the memmap caching behavior
             reg_frame = frame2.copy()
 
         reg_frame.data = data
-        reg_frame.mask = mask
+        flags = frame2.flags
+        flags = self._apply_transform_image(flags, tform, cval=0, order=0)
+        reg_frame.add_flags(PixelMaskFlags.OUT_OF_BOUNDS |
+                            PixelMaskFlags.MASKED,
+                            mask)
 
-        if not frame2.uncertainty.empty:
+        if frame2.uncertainty is not None:
             unct = frame2.get_uncertainty(return_none=False)
-            unct = self._apply_transform_image(unct,
-                                               tform, cval=np.nan)
+            unct = self._apply_transform_image(unct, tform, cval=np.nan,
+                                               order=1)
             reg_frame.uncertainty = unct
 
         sx, sy = tform.translation
         theta = np.rad2deg(tform.rotation)
         reg_frame.meta[_keywords['method']] = self._name
         reg_frame.meta[_keywords['shift_x']] = sx
         reg_frame.meta[_keywords['shift_y']] = sy
@@ -206,52 +220,81 @@
                         ' will be erased.')
             reg_frame.wcs = None
 
         return reg_frame
 
 
 class CrossCorrelationRegister(_BaseRegister):
-    """Register images usgin `~skimage.Register.phase_cross_correlation`.
+    """Register images using `~skimage.registration.phase_cross_correlation`.
 
     It uses cross-correlation to find a translation-only transform between
     two images. It obtains an initial estimate of the cross-correlation
     peak by an FFT and then refines the shift estimation by upsampling
     the DFT only in a small neighborhood of that estimate by means of a
     matrix-multiply DFT[1]_.
 
     Parameters
     ----------
-    upsample_factor : int (optional)
-        Upsampling image factor. Images will be Registered to within
-        ``1 / upsample_factor`` of a pixel.
-        Default: 1 (no upsampling)
-    space : {'real', 'fourier'} (optional)
+    upsample_factor : int, optional
+        Upsampling factor. Images will be registered to within
+        ``1 / upsample_factor`` of a pixel. For example
+        ``upsample_factor == 20`` means the images will be registered
+        within 1/20th of a pixel. Default is 1 (no upsampling).
+        Not used if any of ``reference_mask`` or ``moving_mask`` is not None.
+    space : string, one of "real" or "fourier", optional
         Defines how the algorithm interprets input data. "real" means
         data will be FFT'd to compute the correlation, while "fourier"
-        data will bypass FFT of input data. Case insensitive.
+        data will bypass FFT of input data. Case insensitive. Not
+        used if any of ``reference_mask`` or ``moving_mask`` is not
+        None.
+    disambiguate : bool
+        The shift returned by this function is only accurate *modulo* the
+        image shape, due to the periodic nature of the Fourier transform. If
+        this parameter is set to ``True``, the *real* space cross-correlation
+        is computed for each possible shift, and the shift with the highest
+        cross-correlation within the overlapping area is returned.
+    return_error : bool, {"always"}, optional
+        Returns error and phase difference if "always" is given. If False, or
+        either ``reference_mask`` or ``moving_mask`` are given, only the shift
+        is returned.
+    overlap_ratio : float, optional
+        Minimum allowed overlap ratio between images. The correlation for
+        translations corresponding with an overlap ratio lower than this
+        threshold will be ignored. A lower `overlap_ratio` leads to smaller
+        maximum translation, while a higher `overlap_ratio` leads to greater
+        robustness against spurious matches due to small overlap between
+        masked images. Used only if one of ``reference_mask`` or
+        ``moving_mask`` is not None.
+
+    Notes
+    -----
+    - Due to a bug in the `~skimage.registration.phase_cross_correlation`
+      normalization is automatically disabled.
+    - ``return_error`` is set to ``'always'`` to avoid keep compatibility.
 
     References
     ----------
-    .. [1] :DOI:`10.1364/OL.33.000156`
+    .. [1] :doi:`10.1364/OL.33.000156`
     """
 
     _name = 'cross-correlation'
 
-    def __init__(self, upsample_factor=1, space='real'):
+    def __init__(self, **kwargs):
+        import skimage
         from skimage.registration import phase_cross_correlation
-
-        self._pcc = partial(phase_cross_correlation, space=space,
-                            upsample_factor=upsample_factor,
-                            return_error=False)
+        if skimage.__version__ >= '0.19':
+            kwargs['normalization'] = None
+        kwargs['return_error'] = 'always'
+        self._pcc = partial(phase_cross_correlation, **kwargs)
 
     def _compute_transform(self, image1, image2, mask1=None, mask2=None):
         if mask1 is not None or mask2 is not None:
             logger.debug("Masks are ignored in CrossCorrelationRegister.")
         # Masks are ignored by default
-        dy, dx = self._pcc(image1, image2)
+        dy, dx = self._pcc(image1, image2)[0]
         return transform.AffineTransform(translation=(-dx, -dy))
 
 
 class AsterismRegister(_BaseRegister):
     """Register images using asterism matching. Based on astroalign [1]_.
 
     This Register algorith compute the transform between 2 images based
@@ -282,29 +325,29 @@
 
     Raises
     ------
     ImportError: if astroalign is not installed
 
     References
     ----------
-    .. [1] :DOI:`10.1016/j.ascom.2020.100384`
+    .. [1] :doi:`10.1016/j.ascom.2020.100384`
     """
 
     _name = 'asterism-matching'
 
     def __init__(self, max_control_points=50, detection_threshold=5,
-                 detection_function='sepfind', **detection_kwargs):
+                 detection_function='segfind', **detection_kwargs):
         try:
             import astroalign
         except ImportError:
             raise ImportError('AsterismRegister requires astroalign tools.')
 
-        from ..photometry import sepfind, starfind, daofind, background
+        from ..photometry import segfind, starfind, daofind, background
 
-        funcs = {'sepfind': sepfind, 'starfind': starfind, 'daofind': daofind}
+        funcs = {'segfind': segfind, 'starfind': starfind, 'daofind': daofind}
         self._aa = astroalign
         self._sf = partial(funcs[detection_function], **detection_kwargs)
         self._bkg = background
         self._max_cntl_pts = max_control_points
         self._threshold = detection_threshold
 
     def _compute_transform(self, image1, image2, mask1=None, mask2=None):
@@ -456,15 +499,17 @@
             if cval == 'median':
                 icval = np.median(reg_list[i].data)
             elif cval == 'mean':
                 icval = np.mean(reg_list[i].data)
             else:
                 icval = cval
             reg_list[i].data[:] = icval
-            reg_list[i].mask[:] = True
+            reg_list[i].add_flags(PixelMaskFlags.MASKED |
+                                  PixelMaskFlags.OUT_OF_BOUNDS,
+                                  np.ones_like(reg_list[i].data, dtype=bool))
             reg_list[i].meta[_keywords['method']] = 'failed'
             reg_list[i].meta[_keywords['shift_x']] = None
             reg_list[i].meta[_keywords['shift_y']] = None
             reg_list[i].meta[_keywords['rotation']] = None
 
     if clip_output:
         shifts = [(i.meta[_keywords['shift_x']], i.meta[_keywords['shift_y']])
```

### Comparing `astropop-0.5.4/astropop/logger.py` & `astropop-0.9.0/astropop/logger.py`

 * *Files identical despite different names*

### Comparing `astropop-0.5.4/astropop/math/_deriv.py` & `astropop-0.9.0/astropop/math/_deriv.py`

 * *Files identical despite different names*

### Comparing `astropop-0.5.4/astropop/math/array.py` & `astropop-0.9.0/astropop/math/array.py`

 * *Files identical despite different names*

### Comparing `astropop-0.5.4/astropop/math/hasher.py` & `astropop-0.9.0/astropop/math/hasher.py`

 * *Files identical despite different names*

### Comparing `astropop-0.5.4/astropop/math/physical.py` & `astropop-0.9.0/astropop/math/physical.py`

 * *Files 6% similar despite different names*

```diff
@@ -91,81 +91,66 @@
     """Require qfloat as argument decorator."""
     def decorator(self, *others):
         others = [convert_to_qfloat(i) for i in others]
         return func(self, *others)
     return decorator
 
 
-class _QFloatFormatter():
-    """Simple store for numbers that can be rounded to first digit.
+def _get_round_digit(std, sig):
+    """Get the number of digits to round the error."""
+    return -np.int_(np.floor(np.log10(np.abs(std)))) + sig - 1
 
-    Used mainly for speedup repr and str.
-    """
-    _rounded = False
-
-    def __init__(self, nominal, std):
-        self._n = nominal
-        self._s = std
-        self._d = np.nan
-
-    @property
-    def nominal(self):
-        if not self._rounded:
-            self.round()
-        return self._n
 
-    @property
-    def std_dev(self):
-        if not self._rounded:
-            self.round()
-        return self._s
-
-    @property
-    def digits(self):
-        if not self._rounded:
-            self.round()
-        return self._d
-
-    def round(self):
-        try:
-            first_digit = -np.int(np.floor(np.log10(np.abs(self._s))))
-            self._n = np.around(self._n, first_digit)
-            self._s = np.around(self._s, first_digit)
-            self._d = first_digit
-        except (ValueError, ZeroDivisionError, OverflowError):
-            # Do not change the values
-            pass
-
-    def __format__(self, format_spec):
-        # For not, format do not matter
-        # Positive digits, decimals. Negative digits, integers.
-        nominal = self.nominal
-        std = self.std_dev
-        digits = self.digits
-
-        if not np.isnan(digits):
-            if digits > 0:
-                n_part = f"{nominal:.{int(digits)}f}"
-                s_part = f"{std:.{int(digits)}f}"
-            else:
-                n_part = f"{nominal:.0f}"
-                s_part = f"{std:.0f}"
-            return f"{n_part}+-{s_part}"
-
-        return f"{nominal}+-{std}"
+def _round_to_error(nom, std, sdig):
+    """Round the numbers to the first digit of the error."""
+    try:
+        dig = _get_round_digit(std, sdig)
+        std = np.round(std, dig)
+        # repeat the process for handle std>5 in the first digit cases
+        dig = _get_round_digit(std, sdig)
+        nom = np.round(nom, dig)
+        std = np.round(std, dig)
+    except (ValueError, ZeroDivisionError, OverflowError, RuntimeWarning):
+        # Do not change the values
+        dig = np.nan
+    return nom, std, dig
+
+
+def _format_qfloat(nominal, std_dev, sig_digits, pm_sign='+-'):
+    """Format a qfloat number."""
+    # TODO: scientific notation?
+    # the numbers need to be rounded for larger than one error.
+    nom, std, dig = _round_to_error(nominal, std_dev, sig_digits)
+    if not np.isnan(dig):
+        if dig > 0:
+            return f"{nom:.{int(dig)}f}{pm_sign}{std:.{int(dig)}f}"
+        return f"{nom:.0f}{pm_sign}{std:.0f}"
+    return f"{nom}{pm_sign}{std}"
+
+
+class _FormaterElement:
+    """Class to format a QFloat array."""
+
+    __slots__ = ('_value', '_std', '_sig_digits')
+
+    def __init__(self, value, std, sig_digits):
+        self._value = value
+        self._std = std
+        self._sig_digits = sig_digits
 
     def __repr__(self):
-        return f"{self}"
+        return _format_qfloat(self._value, self._std, self._sig_digits)
 
 
-def _create_formater(nominal, std):
-    """Create _QFloatFormater handling lists."""
-    if check_iterable(nominal):
-        return [_create_formater(n, s) for n, s in zip(nominal, std)]
-    return _QFloatFormatter(nominal, std)
+def _create_formater_array(n, s, digits):
+    """Create an array of _FormaterElements."""
+    if np.isscalar(n):
+        return _FormaterElement(n, s, digits)
+    else:
+        return [_create_formater_array(ni, si, digits) for ni, si in zip(n, s)]
 
 
 def same_unit(qfloat1, qfloat2, func=None):
     """Put 2 qfloats in the same unit."""
     # both units must be the same
     def convert(converter, qf, unit):
         if converter is None:
@@ -262,14 +247,15 @@
     - Units are handled by `~astropy.units`.
     - Math operations cares about units and uncertainties.
     """
 
     _nominal = None
     _uncert = None
     _unit = None
+    _sig_digits = 1
 
     def __init__(self, value, uncertainty=None, unit=None):
         value, uncertainty, unit = self._check_inputs(value, uncertainty, unit)
         self._nominal = value
         self._set_uncert(uncertainty)
         self.unit = unit
 
@@ -286,15 +272,18 @@
             unit = qf.unit
         if np.any(np.array(value) == None):  # noqa: E711
             raise TypeError('value must be not None.')
         for i in value, uncertainty:
             if not np.any(np.isreal(i)):
                 raise TypeError('value and uncertainty must be real numbers, '
                                 'or arrays of real numbers.')
-        value = np.array(value) if check_iterable(value) else float(value)
+        if check_iterable(value):
+            value = np.array(value, dtype=float)
+        else:
+            value = float(value)
         return value, uncertainty, unit
 
     def _set_uncert(self, value):
         if value is None:
             if check_iterable(self._nominal):
                 self._uncert = np.zeros_like(self._nominal)
             else:
@@ -354,20 +343,33 @@
 
     @std_dev.setter
     def std_dev(self, value):
         self.uncertainty = value
 
     @property
     def shape(self):
+        """Shape of the quantity."""
         return np.shape(self.nominal)
 
     @property
     def size(self):
+        """Number of elements in the quantity."""
         return np.size(self.nominal)
 
+    @property
+    def sig_digits(self):
+        """Number of significant digits."""
+        return self._sig_digits
+
+    @sig_digits.setter
+    def sig_digits(self, value):
+        if not np.isreal(value):
+            raise TypeError('sig_digits must be a real number.')
+        self._sig_digits = int(value)
+
     def reset(self, value, uncertainty=None, unit=None):
         """Reset all the data.
 
         Parameters
         ----------
         value : number or array_like
             Nominal value(s) of the quantity.
@@ -405,28 +407,35 @@
 
     @property
     def value(self):
         """Same as nominal. For Astropy compatibility."""
         return self.nominal
 
     def __repr__(self):
-        # FIXME: repr can be very slow for mutch large arrays
-        # repr for arrays
-        if check_iterable(self.nominal):
-            ret = "<QFloat\n"
-            ret2 = _create_formater(self.nominal, self.std_dev)
-            ret2 = np.array(ret2).__repr__()
-            ret2 += f'\nunit={str(self.unit)}'
-        # repr for single values
+        i = hex(id(self))
+        return f'<QFloat at {i}>\n{self.__str__()}'
+
+    def __str__(self):
+        if np.isscalar(self.nominal):
+            s = _format_qfloat(self.nominal, self.uncertainty, self.sig_digits)
         else:
-            ret = "<QFloat "
-            ret2 = f"{_QFloatFormatter(self.nominal, self.std_dev)}"
-            ret2 += f' {str(self.unit)}'
-        ret += ret2 + '>'
-        return ret
+            opt = np.get_printoptions()
+            a = _create_formater_array(self.nominal, self.uncertainty,
+                                       self.sig_digits)
+            s = np.array2string(np.array(a), separator=', ',
+                                max_line_width=opt['linewidth'],
+                                edgeitems=opt['edgeitems'],
+                                threshold=50)
+        if self.unit != units.dimensionless_unscaled:
+            if not np.isscalar(self.nominal):
+                s += ' unit='
+            else:
+                s += ' '
+            s += f'{self.unit}'
+        return s
 
     def __getitem__(self, index):
         """Get one item of given index IF this is iterable."""
         v = self.nominal[index]
         s = self.uncertainty[index]
         return QFloat(v, s, self.unit)
 
@@ -701,19 +710,19 @@
 
     @require_qfloat
     def __abs__(self):
         return QFloat(np.abs(self.nominal), self.uncertainty, self.unit)
 
     @require_qfloat
     def __int__(self):
-        return np.int(self.nominal)
+        return int(self.nominal)
 
     @require_qfloat
     def __float__(self):
-        return np.float(self.nominal)
+        return float(self.nominal)
 
 
 # TODO:
 # Array functions:
 #             - copyto, broadcast, broadcast_to
 #             - sum, prod, nanprod, nansum, cumprod, cumsum, nancumprod,
 #             - nancumsum, diff, ediff1d, cross
@@ -819,14 +828,20 @@
     # error of average = std_dev/sqrt(N)
     std = np.std(qf.nominal, axis=axis)
     # N is determined by the number of elements in the axis
     std /= np.sqrt(np.sum(np.ones_like(qf.nominal), axis=axis))
     return QFloat(nominal, std, qf.unit)
 
 
+@_implements_array_func(np.std)
+def _qfloat_std(qf, axis=None):
+    """Implement np.std for qfloats."""
+    return np.std(qf.nominal, axis=axis)
+
+
 def _implements_ufunc_on_nominal(func):
     """Wraps ufuncs only on the nominal value and don't return QFloat."""
     def wrapper(qf, *args, **kwargs):
         return func(qf.nominal, *args, **kwargs)
     _implements_ufunc(func)(wrapper)
```

### Comparing `astropop-0.5.4/astropop/math/reproject.py` & `astropop-0.9.0/astropop/math/reproject.py`

 * *Files identical despite different names*

### Comparing `astropop-0.5.4/astropop/testing.py` & `astropop-0.9.0/astropop/testing.py`

 * *Files identical despite different names*

### Comparing `astropop-0.5.4/astropop.egg-info/PKG-INFO` & `astropop-0.9.0/astropop.egg-info/PKG-INFO`

 * *Files 20% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 Metadata-Version: 2.1
 Name: astropop
-Version: 0.5.4
+Version: 0.9.0
 Summary: Astronomical Polarimetry and Photometry Pipeline
 Home-page: https://github.com/sparc4-dev/astropop
 Author: Julio Campagnolo
 Author-email: juliocampagnolo@gmail.com
 License: BSD 3-Clause
-Requires-Python: >=3.7
+Requires-Python: >=3.8
 Description-Content-Type: text/x-rst
 Provides-Extra: all
 Provides-Extra: test
 Provides-Extra: docs
 License-File: licenses/LICENSE.rst
 
 AstroPoP
 ========
 
 |GHAction Status| |Codecov Status| |RTD Status| |CODACY|
 
-The (non) famous ASTROnomical POlarimetry and Photometry pipeline. Developed for work with IAGPOL polarimeter at Observatório Pico dos Dias (Brazil), but suitable to be used in other image polarimeters around the world.
+The ASTROnomical POlarimetry and Photometry pipeline. Developed for work with IAGPOL and SPARC4 polarimeters at Observatório Pico dos Dias (Brazil), but suitable to be used in other image polarimeters around the world.
 
 Features
 ^^^^^^^^
 
 This software is intended to provide a full pipeline to reduce raw polarimetry and photometry data taken with common CCD telescope cameras. It can do:
 
 - Create calibrate frames;
@@ -39,20 +39,26 @@
 
 - Calcite polarimeters;
 
   - Automatic pairs of stars identification;
 
 - Automatic photometry calibration using online catalogs.
 
+Support and Community
+^^^^^^^^^^^^^^^^^^^^^
+
+We have a community of people using astropop to perform data reduction. Also, we use this community to offer support for astropop users. Join the community at `astropop-users Google-Groups <https://groups.google.com/g/astropop-users>`_
 
 Dependencies
 ^^^^^^^^^^^^
 
 Some of astropop dependencies (numpy, astropy, scipy, astroscrappy) need gcc to get build. Make sure gcc is installed properly in your system.
 
+There is nothing that prevent astropop itself to run on Windows. However, due to problems that comes from dependencies, mainly numpy and astrometry.net, astropop is currently supported only on Linux and Mac.
+
 Bellow we list all the necessary dependencies for the good working of the code. Note that this can be changed with the time.
 
 - astroalign;
 
 - astropy >= 4.3;
 
 - astroquery;
@@ -67,44 +73,65 @@
 
 - scipy;
 
 - sep.
 
 Installation
 ^^^^^^^^^^^^
-Astropop can be downloaded from https://github.com/sparc4-dev/astropop. For this, type in the terminal:
+
+Astropop can be downloaded from `gh/sparc4-dev/astropop <https://github.com/sparc4-dev/astropop>`_. It follows the stadard python package install procedure. All requirements can be installed with `pip` or `conda`.
+
+Anaconda Environment
+--------------------
+
+We recomend to use a `anaconda <https://www.anaconda.com/>`_ environment to use astropop. Having the anaconda installed, use the following command to install a new `<environment name>` with conda dependencies:
 
 .. code-block::
 
-    git clone https://github.com/sparc4-dev/astropop
+    conda create -n <environment name> -c conda-forge python=3.10 astroalign astropy astroquery astroscrappy matplotlib numpy pyyaml reproject scikit-image scikit-learn scipy sep
+
+Once the environment is created, you can `activate the environment <https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#activating-an-environment>`_ and install the astropop with `pip`.
 
-To install Astropop, you should go to the directory where Astropop was cloned, open the terminal in the Astropop directory and follow one of the options bellow:
+.. code-block::
 
-1 – Install using pip:
+   conda activate <environment name>
+
+Stable Version
+--------------
+
+The stable version of astropop is available in `PyPi <https://pypi.org/>`_ and can be installed directly with `pip` command.
 
 .. code-block::
 
-    pip install -U .
+   pip install astropop
+
+Development Version
+-------------------
 
-2 – Or, without the pip packet control:
+The development (unstable) version can be installed from the github code. With `pip`, can be done in any of the 3 ways:
 
 .. code-block::
 
-    python setup.py install
+    pip install -U git+https://github.com/sparc4-dev/astropop
+
+or
+
+.. code-block::
 
-3 – Install using anaconda:
+   pip install -U https://github.com/sparc4-dev/astropop/archive/refs/heads/main.zip
 
-If you do not have anaconda, please visit https://www.anaconda.com/.
-Once the anaconda is installed you can create an Astropop enviroment using:
+or
 
 .. code-block::
 
-    conda create -n <environment name> -c conda-forge python=3.9 astroalign astropy astroquery astroscrappy matplotlib numpy pyyaml reproject scikit-image scikit-learn scipy sep
+   git clone https://github.com/sparc4-dev/astropop
+   cd astropop
+   pip install -U .
 
-Citating
+Citing
 ^^^^^^^^
 
 |ADS|  |PASP|  |arXiv|  |ASCL|
 
 An article was published in `Publications of the Astronomical Society of the Pacific, vol.131, n.996, pp.024501 <https://iopscience.iop.org/article/10.1088/1538-3873/aaecc2>`_,
 which is the main reference to this work. If you do not have access to PASP, the preprint was uploaded to `arXiv:1811.01408 <https://arxiv.org/abs/1811.01408>`_.
```

### Comparing `astropop-0.5.4/docs/Makefile` & `astropop-0.9.0/docs/Makefile`

 * *Files 2% similar despite different names*

```diff
@@ -34,14 +34,15 @@
 	@echo "  man        to make manual pages"
 	@echo "  changes    to make an overview of all changed/added/deprecated items"
 	@echo "  linkcheck  to check all external links for integrity"
 
 clean:
 	-rm -rf $(BUILDDIR)
 	-rm -rf api
+	-rm -rf _api
 	-rm -rf generated
 
 html:
 	$(SPHINXBUILD) -b html $(ALLSPHINXOPTS) $(BUILDDIR)/html
 	@echo
 	@echo "Build finished. The HTML pages are in $(BUILDDIR)/html."
```

### Comparing `astropop-0.5.4/docs/dev/pixel_convention.rst` & `astropop-0.9.0/docs/dev/pixel_convention.rst`

 * *Files identical despite different names*

### Comparing `astropop-0.5.4/docs/framedata.rst` & `astropop-0.9.0/docs/data_structures/framedata.rst`

 * *Files 24% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-.. include:: references.txt
+.. include:: ../references.txt
 
 FramaData Container
 ===================
 
 |FrameData| is a special container to store important data of astronomical images, just like |CCDData| instances. It is designed to handle data, uncertainties, masks, phyisical units, metadata, memmapping, and other things. However, it is not fully compatible with |CCDData| due to important design differences that are needed to Astropop.
 
 FrameData Usage
@@ -29,8 +29,9 @@
 -------
 
 .. TODO:: Data IO (FITS, |CCDData|, |HDUList|, HDUs, etc.)
 
 FrameData API
 ---------------
 
-.. TODO:: Put properly API link here
+.. automodapi:: astropop.framedata
+    :no-inheritance-diagram:
```

### Comparing `astropop-0.5.4/docs/imarith.rst` & `astropop-0.9.0/docs/reduction/imarith.rst`

 * *Files 10% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-.. include:: references.txt
+.. include:: ../references.txt
 
 
 Image Arithmetics and Combining
 ===============================
 
 Image Arithmetics (|imarith|)
 -----------------------------
@@ -23,21 +23,25 @@
 The current rejection methods are:
 - ``minmax_clip``
 - ``sigma_clip``
 
 Math Details
 ````````````
 
-.. TODO: describe the error computing here
+.. TODO:: describe the error computing here
 
 Sum Combine
 '''''''''''
 
 Sigma Clipping
 ''''''''''''''
 
 To perform sigma clipping, it is recomended to use ``median`` as central tendency and ``mad_std`` as deviation estimation. These two estimators handle outliers better then the mean and standard deviation of the distribution, so produce much better results in sigma clipping. A detailed analysis can be found on the `CCD Data Reduction Guide <https://mwcraig.github.io/ccd-as-book/01-06-Image-combination.html#The-solution:-average-combine,-but-clip-the-extreme-values>`_.
 
-Imarith API
------------
+API
+---
 
-.. TODO:: Put properly API link here
+.. automodapi:: astropop.image.imarith
+    :no-inheritance-diagram:
+
+.. automodapi:: astropop.image.imcombine
+    :no-inheritance-diagram:
```

### Comparing `astropop-0.5.4/docs/ipynb/diy_reduction_script.ipynb` & `astropop-0.9.0/docs/ipynb/diy_reduction_script.ipynb`

 * *Files identical despite different names*

### Comparing `astropop-0.5.4/docs/logger.rst` & `astropop-0.9.0/docs/tools/logger.rst`

 * *Files 7% similar despite different names*

```diff
@@ -1,42 +1,48 @@
+.. include:: ../references.txt
+
 Logging System
 ==============
 
 
 Astropop has its own logger, with special abillities, by default.
 
 It hierits Python's default logger module (not Astropy's one), due to bugs found in Astropy. It allows multiple childres, like for pipeline products, and have the special abillity to log to a list, for after use.
 
-Using logger are far recommended over simple ``print()`` funtions, due to level filtering, storing, properly displaying, etc. The log levels are:
+Using logger are far recommended over simple `print` funtions, due to level filtering, storing, properly displaying, etc. The log levels are:
 
 =============  =======  =======================================================
 ``DEBUG``       ``10``  Diagnostic informations. Very verbose level.
 -------------  -------  -------------------------------------------------------
 ``INFO``        ``20``  Important diagnostic informations. Low verbosity level.
 -------------  -------  -------------------------------------------------------
 ``WARNING``     ``30``  Something is possibly wrong, but not a properly error.
 -------------  -------  -------------------------------------------------------
 ``ERROR``       ``40``  Error.
 -------------  -------  -------------------------------------------------------
 ``CRITICAL``    ``50``  Very serious error.
 =============  =======  =======================================================
 
+The function `~astropop.logger.resolve_level_string` can be used to convert a string to an integer log level.
+
 Using Logger
 ------------
 
-To use the logger, just import it and set a log level::
+To use the logger, just import it and set a log level:
 
-    >>> from astropop.logger import logger
-    >>> logger.setLevel('WARN')
+.. ipython:: python
 
-You are now read to print simple logging::
+    from astropop.logger import logger
+    logger.setLevel('WARN')
 
-    >>> logger.error('Matrix error. Agents needeed.')   # doctest: +SKIP
-    ERROR: Matrix error. Agents needeed. [unknown]
+You are now read to print simple logging:
 
-The general behavior of Astropop logger is the same of Python default logger, very well documentated in `Python Log docs <https://docs.python.org/3/library/logging.html>`_.
+.. ipython:: python
 
+    logger.error('Matrix error. Agents needeed.')
+
+The general behavior of Astropop logger is the same of Python default logger, very well documentated in `Python Log docs <https://docs.python.org/3/library/logging.html>`_.
 
-Logger API
-----------
+.. TODO:: log_to_list doc
 
-.. TODO:: Put properly API link here
+.. automodapi:: astropop.logger
+    :no-inheritance-diagram:
```

### Comparing `astropop-0.5.4/docs/make.bat` & `astropop-0.9.0/docs/make.bat`

 * *Files identical despite different names*

### Comparing `astropop-0.5.4/docs/physical.rst` & `astropop-0.9.0/docs/data_structures/physical.rst`

 * *Files 23% similar despite different names*

```diff
@@ -1,91 +1,110 @@
-.. include:: references.txt
+.. include:: ../references.txt
+
+.. |QFloat.uncertainty| replace:: `~astropop.math.physical.QFloat.uncertainty`
+.. |QFloat.nominal| replace:: `~astropop.math.physical.QFloat.nominal`
+.. |QFloat.unit| replace:: `~astropop.math.physical.QFloat.unit`
 
 Physical Quantities and Uncertanties
 ====================================
 
 Any physical measurement is not a simple number. It is a number, but have a physical unit and an uncertainty related to it.
 
 |astropy| has a very useful module called `~astropy.units`, that handles physical units and |Quantity|, a container intended to store physical measurements with units.. But it doesn't perform any error propagation.
 
-To handle this and make the things a lot easier in ASTROPOP, we created a new class, called |QFloat| to handle both uncertainties and physical units at once. By |QFloat| we mean "Quantity Float", relating it to physical measurements. This class mainly wraps `~astropy.units` methods to handle units and perform error propagation in a coherent way. This module is used in a lot of places inside ASTROPOP, mainly in `~astropop.image_processing` and |Framedata| to ensure correct processing in terms of units and errors propagation.
+To handle this and make the things a lot easier in |astropop|, we created a new class, called |QFloat| to handle both uncertainties and physical units at once. By |QFloat| we mean "Quantity Float", relating it to physical measurements. This class mainly wraps `~astropy.units` methods to handle units and perform error propagation in a coherent way. This module is used in a lot of places inside |astropop|, mainly in `~astropop.image.processing` and |Framedata| to ensure correct processing in terms of units and errors propagation.
 
 .. WARNING:: In the actual state, |QFloat| assumes all uncertainties are standard deviation errors, performing the standard error propagation method. The error propagation also assumes that the uncertainties are uncorelated. This is fine for our usage, but may present problems if used out of this context.
 
 The |QFloat| Class
 ------------------
 
 The |QFloat| class stores basically 3 variables: the nominal value, the uncertainty and the physical unit. To create this class, just pass these values in the class constructor and you can access it using the proper properties.
 
-    >>> from astropop.math import QFloat
-    >>> import numpy as np
-    >>> # A physical measure of 1.000+/-0.001 meters
-    >>> qf = QFloat(1.0, 0.001, 'm')
-    >>> print(qf.nominal) # the nominal value, must be 1.0
-    1.0
-    >>> print(qf.uncertainty) # the uncertainty, 0.001
-    0.001
-    >>> print(qf.unit) # astropy's physical unit, meter
-    m
-    >>> print(qf) # full representation.
-    <QFloat 1.000+-0.001 m>
+.. ipython:: python
+
+    from astropop.math import QFloat
+    import numpy as np
+    # A physical measure of 1.000+/-0.001 meters
+    qf = QFloat(1.0, 0.001, 'm')
+    qf.nominal # the nominal value, must be 1.0
+    qf.uncertainty # the uncertainty, 0.001
+    qf.unit # astropy's physical unit, meter
+    qf # full representation.
 
 Note that, for the full representation of the quantity, the nominal and the uncertainty values are rounded to the first non-zero error decimal. Internally, the number is stored with all the computed decimal places and this rounding just appears in the string representation.
 
-    >>> qf = QFloat(1.0583225, 0.0031495756, 'cm')
-    >>> print(qf.nominal)
-    1.0583225
-    >>> print(qf.uncertainty)
-    0.0031495756
-    >>> print(qf)
-    <QFloat 1.058+-0.003 cm>
+.. ipython:: python
+
+    qf = QFloat(1.0583225, 0.0031495756, 'cm')
+    qf.nominal
+    qf.uncertainty
+    qf
 
 |QFloat| also can store arrays of data, using the exactly same behavior.
 
-    >>> qf = QFloat([1.0, 2.0, 3.0], [0.1, 0.2, 0.3], 'm/s')
-    >>> print(qf)
-    <QFloat
-    array([1.0+-0.1, 2.0+-0.2, 3.0+-0.3], dtype=object)
-    unit=m / s>
+.. ipython:: python
+
+    qf = QFloat([1.0, 2.0, 3.0], [0.1, 0.2, 0.3], 'm/s')
+    qf
 
-During the creation, you can omit `uncertainty` or `unit` arguments, but not the nominal value. We decided to don't make possible create empty |QFloat| instances. Omiting arguments, the code interprets it as:
+During the creation, you can omit |QFloat.uncertainty| or |QFloat.unit| arguments, but not the nominal value. We decided to don't make possible create empty |QFloat| instances. Omiting arguments, the code interprets it as:
 
-- `unit`: setting `None` unit, or omiting it, the class automatically interpret it as `~astropy.units.dimensionless_unscaled`. This means: a number without physical unit.
+- |QFloat.unit|: setting `None` unit, or omiting it, the class automatically interpret it as |dimensionless_unscaled|. This means: a number without physical unit.
 
-    >>> qf_nounit = QFloat(1.0, 0.1)
-    >>> print(qf_nounit)
-    <QFloat 1.0+-0.1 >
+.. ipython:: python
 
-- `uncertainty`: setting uncertainties as `None`, or omiting it, the code consider automatically the uncertainty as 0.0.
+    qf_nounit = QFloat(1.0, 0.1)
+    qf_nounit
 
-    >>> qf_nostd = QFloat(1.0, unit='m')
-    >>> print(qf_nostd)
-    <QFloat 1.0+-0.0 m>
+- |QFloat.uncertainty|: setting uncertainties as `None`, or omiting it, the code consider automatically the uncertainty as 0.0.
+
+.. ipython:: python
+    :okwarning:
+
+    qf_nostd = QFloat(1.0, unit='m')
+    qf_nostd
 
 You also can omit both, like converting a single dimensionless number to QFloat.
 
-    >>> qf = QFloat(1.0)
-    >>> print(qf)
-    <QFloat 1.0+-0.0 >
+.. ipython:: python
+    :okwarning:
+
+    qf = QFloat(1.0)
+    qf
+
+Printing and String Representation
+^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
+
+By default, the |QFloat| shows the numbers rounded to the first significant digit of the uncertainty (rounded). This is done to make the representation more readable. But you can set the number of significant digits to show by setting the `~astropop.math.physical.QFloat.sig_digits` property.
+
+.. ipython:: python
+
+    qf = QFloat(1.0583225, 0.0031495756, 'cm')
+    print(qf)
+    qf.sig_digits = 2
+    print(qf)
+    qf.sig_digits = 3
+    print(qf)
 
 Units and Conversion
 --------------------
 
 Physical units are fully handled with `~astropy.units` module. But we don't use |Quantity| class to store the files. Instead, the code perform itself the units checking and conversions. This is needed to make it compatible with uncertainties, but reduces the compatibility with |astropy| functions directly.
 
 Internal conversion of units for math operations are made automatically and don't need manual intervention. But manual conversions are also possible using the ``<<`` operator or `~astropop.math.physical.QFloat.to` function. The same do the same thing: convert the actual |QFloat| to a new one, with the ne unit. Both accept `~astropy.units.UnitBase` instance or string for conversion.
 
-    >>> from astropop.math import QFloat
-    >>> from astropy import units
-    >>> # One kilometer with 1 cm uncertainty
-    >>> qf = QFloat(1000, 0.01, 'm')
-    >>> qf << 'km'
-    <QFloat 1.00000+-0.00001 km>
-    >>> qf << units.cm
-    <QFloat 100000+-1 cm>
+.. ipython:: python
+
+    from astropop.math import QFloat
+    from astropy import units
+    # One kilometer with 1 cm uncertainty
+    qf = QFloat(1000, 0.01, 'm')
+    qf << 'km'
+    qf << units.cm
 
 If improper conversion (incompatible units), an `~astropy.units.UnitConversionError` is raised.
 
 Math Operations and Error Propagation
 -------------------------------------
 
 As the main porpouse of this module, mathematical operations using physical quantities are performed between |QFloat| and compatible classes. We ensure a basic set of math operations to work, specially all the basic and trigonometric operations needed for basic data reduction. The code also support some basic |numpy| array functions, but not all of them.
@@ -100,46 +119,53 @@
 Supported Math Operations
 ^^^^^^^^^^^^^^^^^^^^^^^^^
 
 Since the math operations are the main reason of the |QFloat| to exist, they have a special focus in the implementation. All builtin Python math operations, with the exception of matrix multiplication, is implemented for |QFloat|. This makes possible to perform direct math operations with |QFloat|.
 
 As example, to sum two |QFloat|, you just need to use the ``+`` operator.
 
-    >>> qf1 = QFloat(1.0, 0.1, 'm')
-    >>> qf2 = QFloat(2.0, 0.1, 'm')
-    >>> qf1 + qf2
-    <QFloat 3.0+-0.1 m>
-
-ASTROPOP handles all the needed units checking and conversions and the result is dimensionality correct. For example:
-
-    >>> qf1 = QFloat(60, 0.5, 'km')
-    >>> qf2 = QFloat(7000, 700, 'm')
-    >>> qf1 + qf2
-    <QFloat 67.0+-0.9 km>
-    >>> t = QFloat(2.0, 0.1, 'h')
-    >>> qf1/t
-    <QFloat 30+-2 km / h>
+.. ipython:: python
+
+    qf1 = QFloat(1.0, 0.1, 'm')
+    qf2 = QFloat(2.0, 0.1, 'm')
+    qf1 + qf2
+
+|astropop| handles all the needed units checking and conversions and the result is dimensionality correct. For example:
+
+.. ipython:: python
+
+    qf1 = QFloat(60, 0.5, 'km')
+    qf2 = QFloat(7000, 700, 'm')
+    qf1 + qf2
+    t = QFloat(2.0, 0.1, 'h')
+    qf1/t
 
 Incorrect dimensionality in operations will raise |UnitsError|.
 
-    >>> qf1 = QFloat(3.0, 0.01, 'kg')
-    >>> qf2 = QFloat(5.0, 0.2, 'K')
-    >>> qf1 + qf2   # doctest: +SKIP
-    UnitConversionError:
+.. ipython::
+    :verbatim:
+
+    In [2]: qf1 = QFloat(3.0, 0.01, 'kg')
+
+    In [3]: qf2 = QFloat(5.0, 0.2, 'K')
+
+    In [4]: qf1 + qf2
+    UnitConversionError: Can only apply 'decorator' function to quantities with compatible dimensions
 
 Supported Numpy Array Operations
 ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
 
 Some `Numpy array functions <https://numpy.org/doc/1.19/reference/routines.array-manipulation.html>`_ are supported built-in by the |QFloat|, but not all of them. These functions are intended to perform array manipulations, like append, reshape, transpose, etc. With this compatibility you can use the Numpy functions directly with |QFloat| objects, like:
 
-    >>> qf = QFloat(np.zeros((100, 100)), np.zeros((100, 100)))
-    >>> np.shape(qf)
-    (100, 100)
+.. ipython:: python
 
-One big difference from our compatibility to default Numpy is that for some functions, Numpy return the view of the array, for bigger performance. Our method, however, just return copies of the |QFloat|s with applied functions. The impact im performance is not so big and the memory usage will not be a problem, unless you use a very very large array.
+    qf = QFloat(np.zeros((100, 100)), np.zeros((100, 100)))
+    np.shape(qf)
+
+One big difference from our compatibility to default Numpy is that for some functions, Numpy return the view of the array, for bigger performance. Our method, however, just return copies of the |QFloat| with applied functions. The impact im performance is not so big and the memory usage will not be a problem, unless you use a very very large array.
 
 The current Numpy array functions supported for this class are:
 
 - `~numpy.append`
 - `~numpy.around`
 - `~numpy.clip`
 - `~numpy.delete`
@@ -164,15 +190,15 @@
 - `~numpy.take`
 - `~numpy.tile`
 - `~numpy.transpose`
 
 Supported Numpy Universal Functions (UFuncs)
 ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
 
-To simplify the way we perform some math operations, we also support some important `Numpy Universal Functions <https://numpy.org/doc/stable/reference/ufuncs.html>`_, also named `~numpy.ufunc`. However, we had to simplify the implementation to get it running properly. So, the traditional ``kwargs`` passed to the `~numpy.ufunc`, like ``out``, ``where`` and others are ignored in our implementation.
+To simplify the way we perform some math operations, we also support some important `Numpy Universal Functions <https://numpy.org/doc/stable/reference/ufuncs.html>`_, also named |ufunc|. However, we had to simplify the implementation to get it running properly. So, the traditional ``kwargs`` passed to the |ufunc|, like ``out``, ``where`` and others are ignored in our implementation.
 
 The current supported ufuncs are:
 
 - `~numpy.absolute` (`~numpy.abs`)
 - `~numpy.add`
 - `~numpy.arccos`
 - `~numpy.arccosh`
@@ -204,128 +230,125 @@
 - `~numpy.sinh`
 - `~numpy.square`
 - `~numpy.sqrt`
 - `~numpy.subtract`
 - `~numpy.tan`
 - `~numpy.tanh`
 
-All the units checking is automatically performed by ASTROPOP. In fact, most of these functions just wrap standart operations of |QFloat|, since this class perform the operations in a way very similar to the `~numpy.ufunc`.
+All the units checking is automatically performed by |astropop|. In fact, most of these functions just wrap standart operations of |QFloat|, since this class perform the operations in a way very similar to the |ufunc|.
 
 Trigonometric Math
 ^^^^^^^^^^^^^^^^^^
 
-For trigonometric functions, like sines, cosines and tangents, the code is able to check the dimensionality of the numbers before perform the operation. So, only dimensionless numbers are accepted, being `~astropy.units.dimensionless_unscaled` or `~astropy.units.dimensionless_angles`. Any number with pyshical dimension don't make any sense inside trigonometric operations, which will raise an |UnitsError|.
+For trigonometric functions, like sines, cosines and tangents, the code is able to check the dimensionality of the numbers before perform the operation. So, only dimensionless numbers are accepted, being |dimensionless_unscaled| or |dimensionless_angles|. Any number with pyshical dimension don't make any sense inside trigonometric operations, which will raise an |UnitsError|.
+
+To avoid an additional module containing trigonometric functions inside |astropop|, these operations are performed using the |ufunc| described earlier. The main difference here is the unit checking performed by |astropop|.
+
+.. ipython:: python
 
-To avoid an additional module containing trigonometric functions inside ASTROPOP, these operations are performed using the `~numpy.ufunc`s described earlier. The main difference here is the unit checking performed by ASTROPOP.
+    qf = QFloat(30, 0.1, 'deg')
+    np.cos(qf)
+    np.sin(qf)
 
-    >>> qf = QFloat(30, 0.1, 'deg')
-    >>> np.cos(qf)
-    <QFloat 0.8660+-0.0009 >
-    >>> np.sin(qf)
-    <QFloat 0.500+-0.002 >
+For trionometric (and hyperbolic) functions, like `~numpy.sin` and `~numpy.sinh`, only angle are accepted. So, only |QFloat| with `~astropy.units.degree` or `~astropy.units.radians` will not raise |UnitsError|. Also, all these functions will result in |dimensionless_unscaled| values.
 
-For trionometric (and hyperbolic) functions, like `~numpy.sin` and `~numpy.sinh`, only angle are accepted. So, only |QFloat| with `~astropy.units.degree` or `~astropy.units.radians` will not raise |UnitsError|. Also, all these functions will result in `~astropy.units.dimensionless_unscaled` values.
+For inverse trigonometric functions, like `~numpy.arcsin`, the inverse happens. The input must be a |dimensionless_unscaled| |QFloat|, and output will be in units of `~astropy.units.radians`.
 
-For inverse trigonometric functions, like `~numpy.arcsin`, the inverse happens. The input must be a `~astropy.units.dimensionless_unscaled` |QFloat|, and output will be in units of `~astropy.units.radians`.
+.. ipython:: python
 
-    >>> qf = QFloat(0.5, 0.01)
-    >>> np.arcsin(qf)
-    <QFloat 0.52+-0.01 rad>
+    qf = QFloat(0.5, 0.01)
+    np.arcsin(qf)
 
 Comparisons Notes
 -----------------
 
 Comparing two numbers with units and uncertainties is an ambiguous thing. There are multiple ways to consider two numbers equal or different, or even greater or smaller. Due to this, we had to assume some conventions in the processing.
 
 Equality
 ^^^^^^^^
 
 We consider two numbers equal if they have the same nominal and standard deviation values in the same unit. This means, they are exactly equal in everything, meaning a more programing-like approach. Like:
 
-    >>> # 1.0+/-0.1 meters
-    >>> qf1 = QFloat(1.0, 0.1, 'm')
-    >>> # same as above, but in cm
-    >>> qf2 = QFloat(100, 10, 'cm')
-    >>> print(qf1 == qf2)
-    True
+.. ipython:: python
+
+    # 1.0+/-0.1 meters
+    qf1 = QFloat(1.0, 0.1, 'm')
+    # same as above, but in cm
+    qf2 = QFloat(100, 10, 'cm')
+    qf1 == qf2
 
 So, the simple fact that two numers have different error bars imply that they are different.
 
-    >>> # 1.0+/-0.2 meters. Same number, with different error
-    >>> qf3 = QFloat(1.0, 0.2, 'm')
-    >>> print(qf1 == qf3)
-    False
-    >>> # 0.5+/-0.1 meters
-    >>> qf4 = QFloat(0.5, 0.1, 'm')
-    >>> print(qf1 == qf4)
-    False
+.. ipython:: python
+
+    # 1.0+/-0.2 meters. Same number, with different error
+    qf3 = QFloat(1.0, 0.2, 'm')
+    qf1 == qf3
+    # 0.5+/-0.1 meters
+    qf4 = QFloat(0.5, 0.1, 'm')
+    qf1 == qf4
 
 Of course, the different operator works in the exactly same way.
 
-    >>> print(qf1 != qf2)
-    False
-    >>> print(qf1 != qf3)
-    True
-    >>> print(qf1 != qf4)
-    True
+.. ipython:: python
+
+    qf1 != qf2
+    qf1 != qf3
+    qf1 != qf4
 
 When comparing numbers with same dimension units, the code automatically converts if to compare. But, if incompatible units (different dimensions) are compared, they automatically are considered different. In physical terms, 1 second is different from 1 meter.
 
-    >>> # Same nominal values of qf1, but in seconds
-    >>> qf5 = (1.0, 0.1, 's')
-    >>> print(qf1 == qf5)
-    False
-    >>> print(qf1 != qf5)
-    True
+.. ipython:: python
+    :okwarning:
+
+    # Same nominal values of qf1, but in seconds
+    qf5 = (1.0, 0.1, 's')
+    qf1 == qf5
+    qf1 != qf5
 
 Equality considering errors
 ^^^^^^^^^^^^^^^^^^^^^^^^^^^
 
 To check physical equality, which consider if the numbers are equal inside the error bars, we created the `~astropop.math.physical.equal_within_errors` method. In this method we assume two numbers (:math:`a` and :math:`b`) are equal if their different is smaller than the sum of the errors (:math:`\sigma_a` and :math:`\sigma_b`).
 
 .. math::
     | a - b | <= \sigma_a + \sigma_b
 
 In other words, these two numbers are equal if they intercept each other, considering error bars. Or, within the errors, they have ate least one value in common.
 
 So, for a proper physical check of equalities, use `~astropop.math.physical.equal_within_errors` instead of ``==`` operator. For example:
 
-    >>> from astropop.math.physical import QFloat, equal_within_errors
-    >>> qf1 = QFloat(1.1, 0.1, 'm')
-    >>> qf2 = QFloat(1.15, 0.05, 'm')
-    >>> print(equal_within_errors(qf1, qf2))
-    True
+.. ipython:: python
+
+    from astropop.math.physical import QFloat, equal_within_errors
+    qf1 = QFloat(1.1, 0.1, 'm')
+    qf2 = QFloat(1.15, 0.05, 'm')
+    equal_within_errors(qf1, qf2)
 
 Inequalities
 ^^^^^^^^^^^^
 
 Inequality handling is more ambiguous then equality to define. To avoid a complex API and keep the things in a coherent way, we perform greater, greater or equal, smaller and smaller or equal operations just comparing the nominal values of the numbers. For example:
 
-    >>> qf1 = QFloat(1.1, 0.1, 'm')
-    >>> qf2 = QFloat(1.15, 0.05, 'm')
-    >>> print(qf1 < qf2)
-    True
-    >>> print(qf2 >= qf1)
-    True
-    >>> print(qf2 < qf1)
-    False
+.. ipython:: python
+
+    qf1 = QFloat(1.1, 0.1, 'm')
+    qf2 = QFloat(1.15, 0.05, 'm')
+    qf1 < qf2
+    qf2 >= qf1
+    qf2 < qf1
 
 Note that errors are note being considered in operations. However, this operation perfmors full handling of physical units. So:
 
-    >>> qf1 = QFloat(1.0, 0.1, 'm')
-    >>> qf2 = QFloat(50, 10, 'cm')
-    >>> print(qf1 >= qf2)
-    True
+.. ipython:: python
+
+    qf1 = QFloat(1.0, 0.1, 'm')
+    qf2 = QFloat(50, 10, 'cm')
+    qf1 >= qf2
 
 These comparisons can only be performed by same dimension measurements. If incompatible units are used, |UnitsError| is raised.
 
 Physical Quantities API
 -----------------------
 
-.. autoclass:: astropop.math.physical.QFloat
-    :members:
-    :undoc-members:
-    :show-inheritance:
-    :inherited-members:
-.. autofunction:: astropop.math.physical.equal_within_errors
-.. autofunction:: astropop.math.physical.qfloat
-.. autofunction:: astropop.math.physical.same_unit
+.. automodapi:: astropop.math.physical
+    :no-inheritance-diagram:
```

### Comparing `astropop-0.5.4/licenses/LICENSE.rst` & `astropop-0.9.0/licenses/LICENSE.rst`

 * *Files identical despite different names*

### Comparing `astropop-0.5.4/licenses/TEMPLATE_LICENCE.rst` & `astropop-0.9.0/licenses/TEMPLATE_LICENCE.rst`

 * *Files identical despite different names*

### Comparing `astropop-0.5.4/scripts/fitsheader_set` & `astropop-0.9.0/scripts/fitsheader_set`

 * *Files identical despite different names*

### Comparing `astropop-0.5.4/setup.cfg` & `astropop-0.9.0/setup.cfg`

 * *Files 16% similar despite different names*

```diff
@@ -10,49 +10,51 @@
 long_description_content_type = text/x-rst
 edit_on_github = False
 github_project = sparc4-dev/astropop
 
 [options]
 zip_safe = False
 packages = find:
-python_requires = >=3.7
+python_requires = >=3.8
 setup_requires = setuptools_scm
 install_requires = 
 	astropy>=4.3
 	numpy>=1.17
 	scipy>=1.6
 	astroquery
 	scikit-image
 	scikit-learn
+	photutils>=1.7
 	pytz
 	pyyaml
 	astroscrappy
 	astroalign
-	sep
+	tqdm
+	nest-asyncio
 
 [options.extras_require]
 all = 
 	matplotlib
 test = 
 	pytest-astropy
 	pytest-remotedata
 	testfixtures
-	flaky  # for online flaky tests
+	pytest-rerunfailures
 docs = 
 	ipython
 	ipykernel
 	sphinx-astropy
-	sphinx-rtd-theme
-	sphinxcontrib-apidoc
-	sphinxcontrib-napoleon
+	sphinx-book-theme
+	numpydoc
 	nbsphinx
 	pandoc
 
 [options.package_data]
 astropop = data/*
+astropop.catalogs = vizier_catalogs/*.yml
 
 [options.packages.find]
 exclude = 
 	tests
 
 [tool:pytest]
 testpaths = "tests" "docs"
```

### Comparing `astropop-0.5.4/setup.py` & `astropop-0.9.0/setup.py`

 * *Files identical despite different names*

### Comparing `astropop-0.5.4/tests/test_ccdprocessing.py` & `astropop-0.9.0/tests/test_ccdprocessing.py`

 * *Files 6% similar despite different names*

```diff
@@ -8,40 +8,41 @@
 from astropy.wcs import WCS
 from astropop.image.processing import cosmics_lacosmic, \
                                       gain_correct, \
                                       subtract_bias, \
                                       subtract_dark, \
                                       flat_correct, \
                                       trim_image
-from astropop.framedata import FrameData
+from astropop.framedata import FrameData, PixelMaskFlags
 from astropop.testing import *
 
 
 class Test_Processing_Cosmics():
     @pytest.mark.parametrize('inplace', [True, False])
     def test_cosmics_lacosmic(self, inplace):
         image = FrameData(np.ones((20, 20))*3, unit=u.adu,
                           mask=np.zeros((20, 20)))
         # Add cosmics
         image.data[10, 10] = 35000
         image.data[10, 11] = 35000
         image.data[11, 10] = 35000
-        image.mask[15, 18] = 1
+        image.flags[15, 18] = PixelMaskFlags.MASKED.value
 
-        expect_mask = np.zeros((20, 20))
-        # currently we are not updating the mask
-        # expect_mask[10, 10] = 1
-        # expect_mask[10, 11] = 1
-        # expect_mask[11, 10] = 1
-        expect_mask[15, 18] = 1
+        expect_flags = np.zeros((20, 20))
+        cosmic_val = (PixelMaskFlags.COSMIC_RAY |
+                      PixelMaskFlags.INTERPOLATED).value
+        expect_flags[10, 10] = cosmic_val
+        expect_flags[10, 11] = cosmic_val
+        expect_flags[11, 10] = cosmic_val
+        expect_flags[15, 18] = PixelMaskFlags.REMOVED.value
 
         # Run the cosmics removal
         res = cosmics_lacosmic(image, inplace=inplace)
         assert_equal(res.data, np.ones((20, 20))*3)
-        assert_equal(res.mask, expect_mask)
+        assert_equal(res.flags, expect_flags)
         assert_equal(res.meta['astropop lacosmic'], True)
 
         if inplace:
             assert_is(res, image)
         else:
             assert_is_not(res, image)
 
@@ -53,14 +54,15 @@
                           uncertainty=5, mask=np.zeros((20, 20)))
         gain = 1.5*u.Unit('electron')/u.adu
         res = gain_correct(image, gain, inplace=inplace)
 
         assert_equal(res.data, np.ones((20, 20))*3*1.5)
         assert_equal(res.uncertainty, np.ones((20, 20))*5*1.5)
         assert_equal(res.unit, u.Unit('electron'))
+        assert_equal(res.flags, np.zeros((20, 20)))
 
         assert_equal(res.meta['astropop gain_corrected'], True)
         assert_equal(res.meta['astropop gain_corrected_value'], 1.5)
         assert_equal(res.meta['astropop gain_corrected_unit'],
                      'electron / adu')
 
         if inplace:
@@ -82,14 +84,16 @@
         master_flat_dimless.data[0:5, 0:5] = 0.5
 
         res1 = flat_correct(frame1, master_flat_dimless, inplace=inplace)
 
         assert_is_instance(res1, FrameData)
         assert_equal(res1.data, expect)
         assert_equal(res1.header['astropop flat_corrected'], True)
+        assert_equal(res1.flags, np.zeros((20, 20)))
+        assert_equal(res1.unit, u.adu)
 
         if inplace:
             assert_is(res1.data, frame1.data)
         else:
             assert_is_not(res1.data, frame1.data)
 
 
@@ -105,14 +109,16 @@
         master_bias.data[0:5, 0:5] = 0.5
 
         res4 = subtract_bias(frame4bias, master_bias, inplace=inplace)
 
         assert_is_instance(res4, FrameData)
         assert_equal(res4.data, expected)
         assert_equal(res4.header['astropop bias_corrected'], True)
+        assert_equal(res4.flags, np.zeros((20, 20)))
+        assert_equal(res4.unit, u.adu)
 
         if inplace:
             assert_is(res4.data, frame4bias.data)
         else:
             assert_is_not(res4.data, frame4bias.data)
```

### Comparing `astropop-0.5.4/tests/test_db.py` & `astropop-0.9.0/tests/test_db.py`

 * *Files 1% similar despite different names*

```diff
@@ -5,14 +5,15 @@
 from astropop._db import SQLColumn, SQLRow, SQLTable, _ID_KEY, \
                          SQLDatabase, _sanitize_colnames, \
                          SQLColumnMap
 import numpy as np
 from astropy.table import Table
 from astropop.testing import *
 import sqlite3
+import copy
 
 
 def test_sanitize_string():
     for i in ['test-2', 'test!2', 'test@2', 'test#2', 'test$2',
               'test&2', 'test*2', 'test(2)', 'test)2', 'test[2]', 'test]2',
               'test{2}', 'test}2', 'test|2', 'test\\2', 'test^2', 'test~2'
               'test"2', 'test\'2', 'test`2', 'test<2', 'test>2', 'test=2',
@@ -258,15 +259,15 @@
         assert_equal(db.table_names, ['test'])
         assert_equal(db.column_names('test'), ['a', 'b', 'd'])
 
     def test_sql_add_row_superpass_64_limit(self):
         db = SQLDatabase(':memory:')
         db.add_table('test')
         db.add_rows('test', {f'col{i}': np.arange(10) for i in range(128)},
-                     add_columns=True)
+                    add_columns=True)
         assert_equal(db.column_names('test'), [f'col{i}' for i in range(128)])
 
         for i, v in enumerate(db.select('test')):
             assert_equal(v, [i]*128)
 
     def test_sqltable_add_column(self):
         db = SQLDatabase(':memory:')
@@ -406,14 +407,72 @@
 
         db2 = db.copy(indexes={'test': [30, 24, 32, 11]})
         assert_equal(db2.table_names, ['test'])
         assert_equal(db2.column_names('test'), ['a', 'b'])
         assert_equal(db2.get_column('test', 'a').values, [23, 49, 61, 65])
         assert_equal(db2.get_column('test', 'b').values, [24, 50, 62, 66])
 
+    def test_sql_copy_more_than_1000(self):
+        db = SQLDatabase(':memory:')
+        db.add_table('test')
+        db.add_column('test', 'a', np.arange(1, 5001, 1))
+        db.add_column('test', 'b', np.arange(2, 5002, 1))
+
+        db2 = db.copy()
+        assert_equal(db2.table_names, ['test'])
+        assert_equal(db2.column_names('test'), ['a', 'b'])
+        assert_equal(db2.get_column('test', 'a').values,
+                     np.arange(1, 5001, 1))
+        assert_equal(db2.get_column('test', 'b').values,
+                     np.arange(2, 5002, 1))
+
+    def test_sql_copy_more_than_1000_indexes(self):
+        db = SQLDatabase(':memory:')
+        db.add_table('test')
+        db.add_column('test', 'a', np.arange(1, 5001, 1))
+        db.add_column('test', 'b', np.arange(2, 5002, 1))
+
+        db2 = db.copy(indexes={'test': np.arange(1000, 2500, 1)})
+        assert_equal(db2.table_names, ['test'])
+        assert_equal(db2.column_names('test'), ['a', 'b'])
+        assert_equal(db2.get_column('test', 'a').values,
+                     np.arange(1001, 2501, 1))
+        assert_equal(db2.get_column('test', 'b').values,
+                     np.arange(1002, 2502, 1))
+
+    def test_sql_delete_row(self):
+        db = SQLDatabase(':memory:')
+        db.add_table('test')
+        db.add_column('test', 'a', [1, 3, 5])
+        db.add_column('test', 'b', [2, 4, 6])
+
+        db.delete_row('test', 1)
+        assert_equal(db.get_column('test', 'a').values, [1, 5])
+        assert_equal(db.get_column('test', 'b').values, [2, 6])
+
+        with pytest.raises(IndexError):
+            db.delete_row('test', 2)
+        with pytest.raises(IndexError):
+            db.delete_row('test', -4)
+
+    def test_sql_delete_column(self):
+        db = SQLDatabase(':memory:')
+        db.add_table('test')
+        db.add_column('test', 'a', [1, 3, 5])
+        db.add_column('test', 'b', [2, 4, 6])
+
+        db.delete_column('test', 'b')
+        assert_equal(db.column_names('test'), ['a'])
+        assert_equal(db.get_column('test', 'a').values, [1, 3, 5])
+
+        with pytest.raises(KeyError, match='does not exist'):
+            db.delete_column('test', 'b')
+        with pytest.raises(ValueError, match='protected name'):
+            db.delete_column('test', 'table')
+
 
 class Test_SQLDatabase_Access:
     def test_sql_get_table(self):
         db = SQLDatabase(':memory:')
         db.add_table('test')
         db.add_column('test', 'a', data=np.arange(10, 20))
         db.add_column('test', 'b', data=np.arange(20, 30))
@@ -618,15 +677,14 @@
 
         a = db.select('test', order='b', limit=2, offset=2)
         assert_equal(a, [(17, 22), (16, 23)])
 
         a = db.select('test', order='b', where='a < 15')
         assert_equal(a, [(14, 25), (13, 26), (12, 27), (11, 28), (10, 29)])
 
-
         a = db.select('test', order='b', where='a < 15', limit=3)
         assert_equal(a, [(14, 25), (13, 26), (12, 27)])
 
         a = db.select('test', order='b', where='a < 15', limit=3, offset=2)
         assert_equal(a, [(12, 27), (11, 28), (10, 29)])
 
     def test_sql_count(self):
@@ -704,14 +762,22 @@
     def db(self):
         db = SQLDatabase(':memory:')
         db.add_table('test')
         db.add_column('test', 'a', data=np.arange(10, 20))
         db.add_column('test', 'b', data=np.arange(20, 30))
         return db
 
+    def test_row_copy_error(self):
+        db = self.db
+        row = db['test'][1]
+        with pytest.raises(NotImplementedError, match='Cannot copy'):
+            copy.copy(row)
+        with pytest.raises(NotImplementedError, match='Cannot copy'):
+            copy.deepcopy(row)
+
     def test_row_basic_properties(self):
         db = self.db
         row = db['test'][0]
         assert_is_instance(row, SQLRow)
         assert_equal(row.table, 'test')
         assert_equal(row.index, 0)
         assert_equal(row.column_names, ['a', 'b'])
@@ -792,14 +858,22 @@
     def db(self):
         db = SQLDatabase(':memory:')
         db.add_table('test')
         db.add_column('test', 'a', data=np.arange(10, 20))
         db.add_column('test', 'b', data=np.arange(20, 30))
         return db
 
+    def test_table_copy_error(self):
+        db = self.db
+        table = db['test']
+        with pytest.raises(NotImplementedError, match='Cannot copy'):
+            copy.copy(table)
+        with pytest.raises(NotImplementedError, match='Cannot copy'):
+            copy.deepcopy(table)
+
     def test_table_basic_properties(self):
         db = self.db
         table = db['test']
         assert_equal(table.name, 'test')
         assert_equal(table.db, db.db)
         assert_equal(table.column_names, ['a', 'b'])
         assert_equal(table.values, list(zip(np.arange(10, 20),
@@ -1188,24 +1262,77 @@
     def test_table_indexof(self):
         db = self.db
         table = db['test']
         assert_equal(table.index_of({'a': 15}), 5)
         assert_equal(table.index_of({'a': 50}), [])
         assert_equal(table.index_of('a < 13'), [0, 1, 2])
 
+    def test_table_delete_row(self):
+        db = self.db
+        table = db['test']
+        assert_is_instance(table, SQLTable)
+
+        table.delete_row(0)
+        expect = np.transpose([np.arange(11, 20), np.arange(21, 30)])
+        assert_equal(table.column_names, ['a', 'b'])
+        assert_equal(table.values, expect)
+
+        table.delete_row(-1)
+        expect = np.transpose([np.arange(11, 19), np.arange(21, 29)])
+        assert_equal(table.column_names, ['a', 'b'])
+        assert_equal(table.values, expect)
+
+        with pytest.raises(IndexError):
+            table.delete_row(10)
+        with pytest.raises(IndexError):
+            table.delete_row(-11)
+
+    def test_table_delete_rows_indexer_robustness(self):
+        db = self.db
+        table = db['test']
+
+        # Test that the row index is updated correctly after deleting rows
+        row = table[5]
+        table.delete_row(4)
+        assert_equal(row.index, 4)
+        assert_equal(table[4].values, row.values)
+
+    def test_table_delete_column(self):
+        db = self.db
+        table = db['test']
+        assert_is_instance(table, SQLTable)
+
+        table.delete_column('a')
+        expect = np.transpose([np.arange(20, 30)])
+        assert_equal(table.column_names, ['b'])
+        assert_equal(table.values, expect)
+
+        with pytest.raises(KeyError):
+            table.delete_column('a')
+        with pytest.raises(KeyError):
+            table.delete_column('c')
+
 
 class Test_SQLColumn:
     @property
     def db(self):
         db = SQLDatabase(':memory:')
         db.add_table('test')
         db.add_column('test', 'a', data=np.arange(10, 20))
         db.add_column('test', 'b', data=np.arange(20, 30))
         return db
 
+    def test_column_copy_error(self):
+        db = self.db
+        col = db['test']['a']
+        with pytest.raises(NotImplementedError, match='Cannot copy'):
+            copy.copy(col)
+        with pytest.raises(NotImplementedError, match='Cannot copy'):
+            copy.deepcopy(col)
+
     def test_column_basic_properties(self):
         db = self.db
         table = db['test']
         column = table['a']
 
         assert_equal(column.name, 'a')
         assert_equal(column.table, 'test')
@@ -1304,14 +1431,15 @@
         column = table['a']
 
         column[:] = -1
         assert_equal(db.get_column('test', 'a').values, [-1]*10)
         column[[2, 4]] = 2
         assert_equal(db.get_column('test', 'a').values, [-1, -1, 2, -1, 2,
                                                          -1, -1, -1, -1, -1])
+
     def test_column_setitem_invalid(self):
         db = self.db
         table = db['test']
         column = table['a']
 
         with pytest.raises(IndexError):
             column[10] = 10
```

### Comparing `astropop-0.5.4/tests/test_detection.py` & `astropop-0.9.0/tests/test_detection.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,62 +1,64 @@
 # Licensed under a 3-clause BSD style license - see LICENSE.rst
 # flake8: noqa: F403, F405
 
 import pytest
 import numpy as np
 
-from astropop.photometry import (background, sepfind, daofind, starfind,
-                                 calc_fwhm, recenter_sources)
-from astropop.photometry.detection import gen_filter_kernel, DAOFind, \
-                                          _sep_fix_byte_order
-from astropop.framedata import MemMapArray
-from astropop.math.moffat import moffat_2d
-from astropop.math.gaussian import gaussian_2d
+from astropop.photometry import (background, segfind, daofind, starfind,
+                                 median_fwhm)
+from astropop.photometry.detection import sepfind  # sepfind is deprecated, but keep tests
+from astropop.math.models import MoffatEquations, GaussianEquations
 from astropop.math.array import trim_array
 from astropy.utils import NumpyRNGContext
 from astropy.stats import gaussian_fwhm_to_sigma
 
 from astropop.testing import *
 
+
 def gen_bkg(size, level, rdnoise, rng_seed=123, dtype='f8'):
     """Generate a simple background image."""
     # create a level image
     im = np.ones(size[::-1], dtype)*level
 
     # reate the gaussian read noise image to sum
     with NumpyRNGContext(rng_seed):
         noise = np.random.normal(loc=0, scale=rdnoise, size=size[::-1])
     im += noise
 
     # poisonic not needed?
     return im
 
 
-def gen_position_flux(size, number, low, high, rng_seed=123):
+def gen_position_flux(size, number, low, high, rng_seed=123, fwhm=5):
     """Generate x, y, and flux lists for stars."""
     for i in range(number):
         with NumpyRNGContext(rng_seed):
-            x = np.random.randint(0, size[0], number)
+            x = np.random.randint(fwhm, size[0]-fwhm, number)
         with NumpyRNGContext(rng_seed+i):
-            y = np.random.randint(0, size[1], number)
-            flux = np.random.randint(low, high, number)
-    return x, y, flux
+            y = np.random.randint(fwhm, size[1]-fwhm, number)
+    # lets sample the flux in the range. Avoid tests flakinness
+    step = float(high-low)/number
+    flux = np.arange(number)*step + low
+    return np.array(x), np.array(y), np.sort(flux)[::-1]
 
 
 def gen_stars_moffat(size, x, y, flux, fwhm):
     """Generate stars image to add to background."""
-    beta = 1.5
-    alpha = fwhm/np.sqrt(2**(1/beta)-1)
+    power = 1.5
+    width = 0.5*fwhm/np.sqrt(2**(1/power)-1)
+
     im = np.zeros(size[::-1])
     grid_y, grid_x = np.indices(size[::-1])
     for xi, yi, fi in zip(x, y, flux):
         imi, gxi, gyi = trim_array(np.zeros_like(im), box_size=5*fwhm,
                                    position=(xi, yi),
                                    indices=(grid_y, grid_x))
-        imi += moffat_2d(gxi, gyi, xi, yi, alpha, beta, fi, 0)
+        imi += MoffatEquations.model_2d(gxi, gyi, xi, yi, flux=fi,
+                                        width=width, power=power, sky=0)
         im[gyi.min():gyi.max()+1, gxi.min():gxi.max()+1] += imi
 
     return im
 
 
 def gen_stars_gaussian(size, x, y, flux, sigma, theta):
     """Generate stars image to add to background."""
@@ -64,29 +66,33 @@
     grid_y, grid_x = np.indices(size[::-1])
 
     try:
         sigma_x, sigma_y = sigma
     except (TypeError, ValueError):
         sigma_x = sigma_y = sigma
 
-    bc = np.broadcast(x, y, flux, sigma_x, sigma_y, theta)
+    bc = np.broadcast_arrays(x, y, flux, sigma_x, sigma_y, theta)
 
-    for xi, yi, fi, sxi, syi, ti in zip(*bc.iters):
-        imi, gxi, gyi = trim_array(np.zeros_like(im), box_size=10*sxi,
+    for xi, yi, fi, sx, sy, ti in zip(*bc):
+        imi, gxi, gyi = trim_array(np.zeros_like(im), box_size=5*max(sx, sy),
                                    position=(xi, yi),
                                    indices=(grid_y, grid_x))
-        imi += gaussian_2d(gxi, gyi, xi, yi, sxi, syi, ti, fi, 0)
+        imi += GaussianEquations.model_2d(gxi, gyi, xi, yi, flux=fi,
+                                          sigma_x=sx, sigma_y=sy, theta=ti,
+                                          sky=0)
         im[gyi.min():gyi.max()+1, gxi.min():gxi.max()+1] += imi
 
     return im
 
 
 def gen_image(size, x, y, flux, sky, rdnoise, model='gaussian', **kwargs):
     """Generate a full image of stars with noise."""
-    im = gen_bkg(size, sky, rdnoise)
+    im = np.ones(size)*sky
+    if rdnoise > 0:
+        im = gen_bkg(size, sky, rdnoise)
 
     if model == 'moffat':
         fwhm = kwargs.pop('fwhm')
         im += gen_stars_moffat(size, x, y, flux, fwhm)
     if model == 'gaussian':
         sigma = kwargs.pop('sigma', 2.0)
         theta = kwargs.pop('theta', 0)
@@ -98,94 +104,15 @@
         negatives = np.where(im < 0)
         im = np.random.poisson(np.absolute(im))
         # restore the negatives
         im[negatives] = -im[negatives]
     return im
 
 
-class Test_Detection_Conformance():
-    # Conformance of secondary functions.
-    def test_gen_kernel(self):
-        assert_equal(gen_filter_kernel(3), [[0, 1, 0],
-                                            [1, 4, 1],
-                                            [0, 1, 0]])
-
-        assert_equal(gen_filter_kernel(5), [[1, 2, 3, 2, 1],
-                                            [2, 4, 6, 4, 2],
-                                            [3, 6, 9, 6, 3],
-                                            [2, 4, 6, 4, 2],
-                                            [1, 2, 3, 2, 1]])
-
-        assert_equal(gen_filter_kernel(7), [[1, 2, 3, 4, 3, 2, 1],
-                                            [2, 4, 6, 8, 6, 4, 2],
-                                            [3, 6, 9, 12, 9, 6, 3],
-                                            [4, 8, 12, 16, 12, 8, 4],
-                                            [3, 6, 9, 12, 9, 6, 3],
-                                            [2, 4, 6, 8, 6, 4, 2],
-                                            [1, 2, 3, 4, 3, 2, 1]])
-
-    @pytest.mark.skip
-    def test_sources_mask(self):
-        pass
-
-
-class Test_SepFixByteOrder():
-    def test_sep_fix_byte_order_memmaparray(self):
-        arr = MemMapArray(np.arange(10).reshape(2, 5))
-        arr1 = _sep_fix_byte_order(arr)
-        assert_equal(arr1, arr)
-        assert_is_instance(arr1, np.ndarray)
-        assert_true(arr1.dtype.isnative)
-        assert_true(arr1.flags['C_CONTIGUOUS'])
-        assert_equal(arr1.dtype, np.dtype('float64'))
-
-    def test_sep_fix_byte_order_f4(self):
-        arr = np.arange(10, dtype='f4').reshape(2, 5)
-        arr1 = _sep_fix_byte_order(arr)
-        assert_equal(arr1, arr)
-        assert_is_instance(arr1, np.ndarray)
-        assert_true(arr1.dtype.isnative)
-        assert_true(arr1.flags['C_CONTIGUOUS'])
-        assert_equal(arr1.dtype, np.dtype('float32'))
-
-    @pytest.mark.parametrize('dtype', ['i1', 'i2', 'i4', 'i8',
-                                       'u1', 'u2', 'u4', 'u8'])
-    def test_sep_fix_byte_order_dtypes(self, dtype):
-        arr = np.arange(10, dtype=dtype).reshape(2, 5)
-        arr1 = _sep_fix_byte_order(arr)
-        assert_equal(arr1, arr)
-        assert_is_instance(arr1, np.ndarray)
-        assert_true(arr1.dtype.isnative)
-        assert_true(arr1.flags['C_CONTIGUOUS'])
-        assert_equal(arr1.dtype, np.dtype('float64'))
-
-    @pytest.mark.parametrize('byteorder', ['>', '<'])
-    @pytest.mark.parametrize('dtype', ['i1', 'i2', 'i4', 'i8',
-                                       'u1', 'u2', 'u4', 'u8',
-                                       'f8'])
-    def test_sep_fix_byte_order_byteorder(self, byteorder, dtype):
-        dtype = f"{byteorder}{dtype}"
-        arr = np.arange(10, dtype=dtype).reshape(2, 5)
-        arr1 = _sep_fix_byte_order(arr)
-        assert_equal(arr1, arr)
-        assert_is_instance(arr1, np.ndarray)
-        assert_true(arr1.dtype.isnative)
-        assert_true(arr1.flags['C_CONTIGUOUS'])
-        assert_equal(arr1.dtype, np.dtype('float64'))
-
-    def test_sep_fix_byte_order_contiguous(self):
-        arr = np.arange(10, dtype='f4').reshape(2, 5).T
-        arr1 = _sep_fix_byte_order(arr)
-        assert_equal(arr1, arr)
-        assert_is_instance(arr1, np.ndarray)
-        assert_true(arr1.dtype.isnative)
-        assert_true(arr1.flags['C_CONTIGUOUS'])
-        assert_equal(arr1.dtype, np.dtype('float32'))
-
-
+@pytest.mark.flaky(reruns=5, reruns_delay=0.1)
 class Test_Background():
     def test_background_simple_nocosmic(self):
         size = (2048, 2048)
         level = 800
         rdnoise = 20
         image_test = gen_bkg(size, level, rdnoise)
 
@@ -259,50 +186,14 @@
         assert_almost_equal(global_rms, rdnoise, decimal=0)
 
         assert_equal(bkg.shape, size)
         assert_equal(rms.shape, size)
         assert_almost_equal(bkg, np.ones(size)*level, decimal=0)
         assert_almost_equal(rms, np.ones(size)*rdnoise, decimal=0)
 
-    def test_background_variablelevel_cosmics(self):
-        size = (1024, 1024)
-        y_i, x_i = np.indices(size)
-        level = x_i*y_i/500  # level from 0 to 2000
-        rdnoise = 20
-        image_test = gen_bkg(size, level, rdnoise)
-
-        # add some cosmics
-        for i in range(100):  # 100 single pixel cosmics
-            x = np.random.randint(0, size[0]-1)
-            y = np.random.randint(0, size[1]-1)
-            image_test[x, y] = np.random.randint(16000, 64000)
-
-        for i in range(4):  # 4 square block cosmics
-            x = np.random.randint(0, size[0]-3)
-            y = np.random.randint(0, size[1]-3)
-            image_test[x:x+2, y:y+2] = np.random.randint(16000, 64000)
-
-        box_size = 64
-        filter_size = 3
-        global_bkg, global_rms = background(image_test, box_size, filter_size,
-                                            mask=None, global_bkg=True)
-        bkg, rms = background(image_test, box_size, filter_size,
-                              mask=None, global_bkg=False)
-
-        assert_equal(type(global_bkg), float)
-        assert_equal(type(global_rms), float)
-        assert_almost_equal(global_bkg, 389, decimal=0)
-        assert_almost_equal(global_rms, 36, decimal=0)
-
-        assert_equal(bkg.shape, size)
-        assert_equal(rms.shape, size)
-        # with stars, the dispersion increases
-        assert_almost_equal(bkg, np.ones(size)*level, decimal=-1)
-        # assert_almost_equal(rms, np.ones(size)*rdnoise, decimal=-1)
-
     def test_background_stars(self):
         size = (1024, 1024)
         stars_n = 50
         flux_low = 1500
         flux_high = 25000
         fwhm = 5
         level = 800
@@ -325,56 +216,18 @@
 
         assert_equal(bkg.shape, size)
         assert_equal(rms.shape, size)
         # with stars, the dispersion increases
         assert_almost_equal(bkg, np.ones(size)*level, decimal=-1)
         assert_almost_equal(rms, np.ones(size)*rdnoise, decimal=-1)
 
-    def test_background_stars_variablelevel(self):
-        size = (1024, 1024)
-        stars_n = 50
-        flux_low = 1500
-        flux_high = 25000
-        fwhm = 5
-        y_i, x_i = np.indices(size)
-        level = x_i*y_i/500  # level from 0 to 2000
-        rdnoise = 20
-        x, y, f = gen_position_flux(size, stars_n, flux_low, flux_high)
-        image_test = gen_bkg(size, level, rdnoise)
-        image_test += gen_stars_moffat(size, x, y, f, fwhm)
-
-        box_size = 64
-        filter_size = 3
-        global_bkg, global_rms = background(image_test, box_size, filter_size,
-                                            mask=None, global_bkg=True)
-        bkg, rms = background(image_test, box_size, filter_size,
-                              mask=None, global_bkg=False)
-
-        assert_equal(type(global_bkg), float)
-        assert_equal(type(global_rms), float)
-        assert_almost_equal(global_bkg, 389, decimal=0)
-        assert_almost_equal(global_rms, 36, decimal=0)
 
-        assert_equal(bkg.shape, size)
-        assert_equal(rms.shape, size)
-        # with stars, the dispersion increases
-        assert_almost_equal(bkg, np.ones(size)*level, decimal=-1)
-        # here the rms goes bigger with the level
-        # assert_almost_equal(rms, np.ones(size)*rdnoise, decimal=-1)
-
-
-@pytest.mark.flaky(max_runs=10, min_passes=1)
+@pytest.mark.flaky(reruns=5, reruns_delay=0.1)
 class Test_SEP_Detection():
-    # segmentation detection. Must detect all shapes of sources
-
-    def resort_sources(self, x, y, f):
-        """Random sources are random. We must resort to compare."""
-        # For SEP, resort using x order
-        order = np.argsort(y)
-        return x[order], y[order], f[order]
+    # sepfind is deprecated, but lets keep the tests until it is removed
 
     def test_sepfind_one_star(self):
         size = (128, 128)
         pos = (64, 64)
         sky = 20
         sky = 800
         rdnoise = 20
@@ -412,63 +265,58 @@
 
     def test_sepfind_strong_and_weak(self):
         size = (128, 128)
         posx = (60, 90)
         posy = (20, 90)
         sky = 800
         rdnoise = 20
-        flux = (32000, 600)
+        flux = (32000, 3000)
         sigma = 1.5
         theta = 0
         im = gen_image(size, posx, posy, flux, sky, rdnoise,
                        model='gaussian', sigma=sigma, theta=theta)
 
-        sources = sepfind(im, 3, sky, rdnoise)
+        sources = sepfind(im, 5, sky, rdnoise)
 
-        assert_equal(len(sources), 2)
         assert_almost_equal(sources['x'], posx, decimal=0)
         assert_almost_equal(sources['y'], posy, decimal=0)
 
     def test_sepfind_four_stars_fixed_position(self):
         size = (1024, 1024)
         posx = (10, 120, 500, 1000)
         posy = (20, 200, 600, 800)
         sky = 800
         rdnoise = 20
-        flux = (15000, 1500, 1500, 35000)
-        sigma = 3
+        flux = (35000, 15000, 10000, 5000)
+        sigma = 1.5
         theta = 0
         im = gen_image(size, posx, posy, flux, sky, rdnoise,
                        model='gaussian', sigma=sigma, theta=theta)
 
-        sources = sepfind(im, 3, sky, rdnoise)
+        sources = sepfind(im, 10, sky, rdnoise)
 
-        assert_equal(len(sources), 4)
         assert_almost_equal(sources['x'], posx, decimal=0)
         assert_almost_equal(sources['y'], posy, decimal=0)
 
     def test_sepfind_multiple_stars(self):
         size = (1024, 1024)
         number = 15
-        low = 2000
+        low = 5000
         high = 30000
         sky = 800
         rdnoise = 20
-        sigma = 3
+        sigma = 1.5
         theta = 0
 
         x, y, f = gen_position_flux(size, number, low, high, rng_seed=456)
         im = gen_image(size, x, y, f, sky, rdnoise,
                        model='gaussian', sigma=sigma, theta=theta)
 
-        sources = sepfind(im, 5, sky, rdnoise)
-
-        x, y, f = self.resort_sources(x, y, f)
+        sources = sepfind(im, 8, sky, rdnoise)
 
-        assert_equal(len(sources), number)
         assert_almost_equal(sources['x'], x, decimal=0)
         assert_almost_equal(sources['y'], y, decimal=0)
 
     def test_sepfind_one_star_subpixel(self):
         size = (128, 128)
         pos = (54.32, 47.86)
 
@@ -477,158 +325,166 @@
         sources = sepfind(im, 5, 800, 10)
         assert_equal(len(sources), 1)
         # no error, 2 decimals ok!
         assert_almost_equal(sources[0]['x'], pos[0], decimal=2)
         assert_almost_equal(sources[0]['y'], pos[1], decimal=2)
 
 
-@pytest.mark.flaky(max_runs=10, min_passes=1)
+@pytest.mark.flaky(reruns=5, reruns_delay=0.1)
+class Test_Segmentation_Detection():
+    # segmentation detection. Must detect all shapes of sources
+
+    def test_segfind_one_star(self):
+        size = (128, 128)
+        pos = (64, 64)
+        sky = 20
+        sky = 800
+        rdnoise = 20
+        flux = 32000
+        sigma = 3
+        theta = 0
+        threshold = 10
+        im = gen_image(size, [pos[0]], [pos[1]], [flux], sky, rdnoise,
+                       model='gaussian', sigma=sigma, theta=theta)
+
+        sources = segfind(im, threshold, sky, rdnoise)
+
+        assert_equal(len(sources), 1)
+        assert_almost_equal(sources['x'][0], 64, decimal=0)
+        assert_almost_equal(sources['y'][0], 64, decimal=0)
+
+    def test_segfind_negative_sky(self):
+        size = (128, 128)
+        pos = (64, 64)
+        sky = 0
+        rdnoise = 20
+        flux = 32000
+        sigma = 3
+        theta = 0
+        threshold = 10
+
+        im = gen_image(size, [pos[0]], [pos[1]], [flux], sky, rdnoise,
+                       model='gaussian', sigma=sigma, theta=theta)
+
+        sources = segfind(im, threshold, sky, rdnoise)
+
+        assert_equal(len(sources), 1)
+        assert_almost_equal(sources['x'][0], 64, decimal=0)
+        assert_almost_equal(sources['y'][0], 64, decimal=0)
+
+    def test_segfind_strong_and_weak(self):
+        size = (128, 128)
+        posx = (60, 90)
+        posy = (20, 90)
+        sky = 800
+        rdnoise = 20
+        flux = (32000, 3000)
+        sigma = 1.5
+        theta = 0
+        im = gen_image(size, posx, posy, flux, sky, rdnoise,
+                       model='gaussian', sigma=sigma, theta=theta)
+
+        sources = segfind(im, 5, sky, rdnoise)
+
+        assert_almost_equal(sources['x'], posx, decimal=0)
+        assert_almost_equal(sources['y'], posy, decimal=0)
+
+    def test_segfind_four_stars_fixed_position(self):
+        size = (1024, 1024)
+        posx = (10, 120, 500, 1000)
+        posy = (20, 200, 600, 800)
+        sky = 800
+        rdnoise = 20
+        flux = (35000, 15000, 10000, 5000)
+        sigma = 1.5
+        theta = 0
+        im = gen_image(size, posx, posy, flux, sky, rdnoise,
+                       model='gaussian', sigma=sigma, theta=theta)
+
+        sources = segfind(im, 10, sky, rdnoise)
+
+        assert_almost_equal(sources['x'], posx, decimal=0)
+        assert_almost_equal(sources['y'], posy, decimal=0)
+
+    def test_segfind_multiple_stars(self):
+        size = (1024, 1024)
+        number = 15
+        low = 5000
+        high = 30000
+        sky = 800
+        rdnoise = 20
+        sigma = 1.5
+        theta = 0
+
+        x, y, f = gen_position_flux(size, number, low, high, rng_seed=456)
+        im = gen_image(size, x, y, f, sky, rdnoise,
+                       model='gaussian', sigma=sigma, theta=theta)
+
+        sources = segfind(im, 8, sky, rdnoise)
+
+        assert_almost_equal(sources['x'], x, decimal=0)
+        assert_almost_equal(sources['y'], y, decimal=0)
+
+    def test_segfind_one_star_subpixel(self):
+        size = (128, 128)
+        pos = (54.32, 47.86)
+
+        im = gen_image(size, [pos[0]], [pos[1]], [45000], 800, 0,
+                       sigma=[3], skip_poisson=True)
+        sources = segfind(im, 5, 800, 10)
+        assert_equal(len(sources), 1)
+        # no error, 2 decimals ok!
+        assert_almost_equal(sources[0]['x'], pos[0], decimal=2)
+        assert_almost_equal(sources[0]['y'], pos[1], decimal=2)
+
+
+@pytest.mark.flaky(reruns=5, rerun_delay=0.1)
 class Test_DAOFind_Detection():
     # DAOFind detection. Only round unsturaded stars
 
-    def resort_sources(self, x, y, f):
-        """Random sources are random. We must resort to compare."""
-        # For SEP, resort using x order
-        order = np.argsort(y)
-        return x[order], y[order], f[order]
-
-    @pytest.mark.parametrize('fwhm', np.arange(1, 9, 1))
-    def test_daofind_constants_calc(self, fwhm):
-        # Compare our constants with D.Jones daofind
-        dao = DAOFind(fwhm)
-
-        maxbox = 13  # Maximum size of convolution box in pixels
-        assert_equal(dao._maxbox, maxbox)
-        radius = np.max([0.637*fwhm, 2.001])
-        assert_equal(dao._radius, radius)
-        radsq = radius**2
-        nhalf = np.min([int(radius), int((maxbox-1)/2.)])
-        assert_equal(dao._nhalf, nhalf)
-        nbox = 2*nhalf + 1  # number of pixels in side of convolution box
-        assert_equal(dao._nbox, nbox)
-
-        sigsq = (fwhm*gaussian_fwhm_to_sigma)**2
-        assert_equal(dao._sigma2, sigsq)
-
-        mask = np.zeros([nbox, nbox], dtype='int8')
-        g = np.zeros([nbox, nbox])  # Gaussian convolution kernel
-        row2 = (np.arange(nbox)-nhalf)**2
-        for i in range(nhalf+1):
-            temp = row2 + i**2
-            g[nhalf-i, :] = temp
-            g[nhalf+i, :] = temp
-        g_row = np.where(g <= radsq)
-        # MASK is complementary to SKIP in Stetson's Fortran
-        mask[g_row[0], g_row[1]] = 1
-        assert_equal(dao._conv_mask, mask)
-        good = np.where(mask)  # Value of c are now equal to distance to center
-        pixels = len(good[0])
-
-        # Compute quantities for centroid computations that can be used for all
-        # stars
-        g = np.exp(-0.5*g/sigsq)
-        assert_equal(dao._g, g)
-
-        xwt = np.zeros([nbox, nbox])
-        wt = nhalf - np.abs(np.arange(nbox)-nhalf) + 1
-        assert_equal(dao._wt, wt)
-        for i in range(nbox):
-            xwt[i, :] = wt
-        assert_equal(dao._xwt, xwt)
-        ywt = np.transpose(xwt)
-        assert_equal(dao._ywt, ywt)
-        sgx = np.sum(g*xwt, 1)
-        assert_equal(dao._sgx, sgx)
-        p = np.sum(wt)
-        assert_equal(dao._p, p)
-        sgy = np.sum(g*ywt, 0)
-        assert_equal(dao._sgy, sgy)
-        sumgx = np.sum(wt*sgy)
-        assert_equal(dao._sumgx, sumgx)
-        sumgy = np.sum(wt*sgx)
-        assert_equal(dao._sumgy, sumgy)
-        sumgsqy = np.sum(wt*sgy*sgy)
-        assert_equal(dao._sumgsqy, sumgsqy)
-        sumgsqx = np.sum(wt*sgx*sgx)
-        assert_equal(dao._sumgsqx, sumgsqx)
-        vec = nhalf - np.arange(nbox)
-        assert_equal(dao._vec, vec)
-        dgdx = sgy*vec
-        assert_equal(dao._dgdx, dgdx)
-        dgdy = sgx*vec
-        assert_equal(dao._dgdy, dgdy)
-        sdgdxs = np.sum(wt*dgdx**2)
-        assert_equal(dao._sdgdxs, sdgdxs)
-        sdgdx = np.sum(wt*dgdx)
-        assert_equal(dao._sdgdx, sdgdx)
-        sdgdys = np.sum(wt*dgdy**2)
-        assert_equal(dao._sdgdys, sdgdys)
-        sdgdy = np.sum(wt*dgdy)
-        assert_equal(dao._sdgdy, sdgdy)
-        sgdgdx = np.sum(wt*sgy*dgdx)
-        assert_equal(dao._sgdgdx, sgdgdx)
-        sgdgdy = np.sum(wt*sgx*dgdy)
-        assert_equal(dao._sgdgdy, sgdgdy)
-
-        c = g*mask  # Convolution kernel now in c
-        sumc = np.sum(c)
-        sumcsq = np.sum(c**2) - sumc**2/pixels
-        sumc = sumc/pixels
-        c[good[0], good[1]] = (c[good[0], good[1]] - sumc)/sumcsq
-        assert_equal(dao._kernel, c)
-        c1 = np.exp(-.5*row2/sigsq)
-        sumc1 = np.sum(c1)/nbox
-        sumc1sq = np.sum(c1**2) - sumc1
-        c1 = (c1-sumc1)/sumc1sq
-        assert_equal(dao._c1, c1)
-
     def test_daofind_sharpness(self):
         # compare my implementation with D.Jones PythonPhot
         # without filtering, both have to output the same round/sharp and
         # the same coordinates for all stars, because use the same algorithm
 
         image_size = (525, 200)
         xpos = np.arange(10)*50 + 25
         ypos = np.ones_like(xpos)*30 + np.arange(len(xpos))*10
         sky = 800
         rdnoise = 50
         threshold = 50
 
         fwhm = 5
-        sigma = np.array([0.1, 0.5, 0.8, 1.0, 1.2, 1.5, 2.0, 3.5, 3.0, 3.5])
+        sigma = np.array([0.1, 0.5, 0.8, 1.0, 1.2, 1.5, 2.0, 2.5, 3.0, 3.5])
         sigma *= fwhm*gaussian_fwhm_to_sigma
-        flux = (np.ones_like(xpos)*sigma)*80000
-        expect_sharp = [3.55, 0.76, 0.50, 0.45, 0.43,
-                        0.41, 0.39, 0.39, 0.39, 0.39]
+        sigma = sigma[::-1]
+        flux = np.ones_like(xpos)*80000/GaussianEquations.normalize_2d(sigma,
+                                                                       sigma)
+        expect_sharp = [3.5, 0.8, 0.5, 0.5, 0.4, 0.4, 0.4, 0.4, 0.4, 0.4][::-1]
 
         im = gen_image(image_size, xpos, ypos, flux, sky, rdnoise,
                        model='gaussian', sigma=sigma)
 
         sources = daofind(im, threshold, sky, rdnoise, fwhm,
                           sharp_limit=None, round_limit=None)
 
-        assert_equal(len(sources), len(xpos))
         assert_almost_equal(sources['x'], xpos, decimal=1)
         assert_almost_equal(sources['y'], ypos, decimal=1)
-        assert_almost_equal(sources['sharp'], expect_sharp, decimal=1)
+        assert_almost_equal(sources['sharpness'], expect_sharp, decimal=1)
 
     def test_daofind_roundness(self):
-        # compare my implementation with D.Jones PythonPhot
-        # without filtering, both have to output the same round/sharp and
-        # the same coordinates for all stars, because use the same algorithm
-
         image_size = (525, 200)
         xpos = np.arange(10)*50 + 25
         ypos = np.ones_like(xpos)*30 + np.arange(len(xpos))*10
         sky = 800
         rdnoise = 50
         threshold = 50
 
         e = (np.arange(len(xpos)))*0.1
-        flux = np.sqrt(np.arange(len(xpos))+1)*80000
+        flux = (np.sqrt(np.arange(len(xpos))+1)*80000)[::-1]
         sigma_x = np.sqrt(1/(1-e**2))*2
         sigma_y = np.ones_like(xpos)*2
         fwhm = 5
         theta = np.zeros_like(xpos)
         sky = 800
         rdnoise = 20  # very low noise
         expect_round = np.array([0.0, 0.02, 0.03, 0.08, 0.15, 0.25,
@@ -640,15 +496,15 @@
 
         sources = daofind(im, threshold, sky, rdnoise, fwhm,
                           sharp_limit=None, round_limit=None)
 
         assert_equal(len(sources), len(xpos))
         assert_almost_equal(sources['x'], xpos, decimal=0)
         assert_almost_equal(sources['y'], ypos, decimal=0)
-        assert_almost_equal(sources['round'], -expect_round, decimal=1)
+        assert_almost_equal(sources['roundness'], expect_round, decimal=1)
 
     def test_daofind_one_star(self):
         size = (128, 128)
         pos = (64, 64)
         sky = 70
         rdnoise = 20
         flux = 32000
@@ -688,15 +544,15 @@
 
     def test_daofind_four_stars_fixed_position(self):
         size = (128, 128)
         posx = (45, 90, 45, 90)
         posy = (45, 50, 90, 100)
         sky = 800
         rdnoise = 20
-        flux = (15000, 3000, 5000, 35000)
+        flux = (35000, 15000, 10000, 5000)
         fwhm = 3
         sigma = fwhm*gaussian_fwhm_to_sigma
         theta = 0
         threshold = 10
 
         im = gen_image(size, posx, posy, flux, sky, rdnoise,
                        model='gaussian', sigma=sigma, theta=theta)
@@ -706,46 +562,43 @@
         assert_equal(len(sources), 4)
         assert_almost_equal(sources['x'], posx, decimal=0)
         assert_almost_equal(sources['y'], posy, decimal=0)
 
     def test_daofind_multiple_stars(self):
         size = (512, 512)
         number = 15
-        low = 2000
+        low = 5000
         high = 30000
         sky = 800
         rdnoise = 20
         fwhm = 5
         sigma = fwhm*gaussian_fwhm_to_sigma
         theta = 0
         threshold = 10
         x, y, f = gen_position_flux(size, number, low, high, rng_seed=456)
 
         im = gen_image(size, x, y, f, sky, rdnoise,
                        model='gaussian', sigma=sigma, theta=theta)
 
         sources = daofind(im, threshold, sky, rdnoise, fwhm)
 
-        x, y, f = self.resort_sources(x, y, f)
-
-        assert_equal(len(sources), number)
         assert_almost_equal(sources['x'], x, decimal=0)
         assert_almost_equal(sources['y'], y, decimal=0)
 
     def test_daofind_reject_roundness(self):
         size = (128, 128)
         pos_x = [20, 60, 100, 40, 80]
         pos_y = [20, 30, 40, 50, 60]
         sky = 70
         rdnoise = 20
         flux = [30000]*5
         theta = 0
         fwhm = 3
-        sigma_x = np.array([1, 0.5, 1, 2.0, 0.1])*gaussian_fwhm_to_sigma*fwhm
-        sigma_y = np.array([1, 1.0, 1, 0.5, 0.1])*gaussian_fwhm_to_sigma*fwhm
+        sigma_x = np.array([1, 0.5, 0.9, 2.0, 0.1])*gaussian_fwhm_to_sigma*fwhm
+        sigma_y = np.array([1, 1.0, 0.9, 0.5, 0.1])*gaussian_fwhm_to_sigma*fwhm
         threshold = 10
         # stars 0, 2 -> passed
         # star 4 -> rejected by sharpness
         # stars 1, 3 -> rejected by roundness
 
         im = gen_image(size, pos_x, pos_y, flux, sky, rdnoise,
                        model='gaussian', sigma=(sigma_x, sigma_y),
@@ -768,24 +621,18 @@
         sources = daofind(im, 5, 800, 10, 5)
         assert_equal(len(sources), 1)
         # no error, 2 decimals ok!
         assert_almost_equal(sources[0]['x'], pos[0], decimal=2)
         assert_almost_equal(sources[0]['y'], pos[1], decimal=2)
 
 
-@pytest.mark.flaky(max_runs=10, min_passes=1)
+@pytest.mark.flaky(reruns=5, rerun_delay=0.1)
 class Test_StarFind():
     # Our combined iterative method
 
-    def resort_sources(self, x, y, f):
-        """Random sources are random. We must resort to compare."""
-        # For SEP, resort using x order
-        order = np.argsort(y)
-        return x[order], y[order], f[order]
-
     def test_starfind_calc_fwhm(self):
         size = (512, 512)
         number = 15
         sky = 70
         rdnoise = 20
         low = 120000
         high = 320000
@@ -793,67 +640,56 @@
         theta = 0
 
         x, y, f = gen_position_flux(size, number, low, high, rng_seed=456)
 
         im = gen_image(size, x, y, f, sky, rdnoise,
                        model='gaussian', sigma=sigma, theta=theta)
 
-        fwhm = calc_fwhm(im, x, y, box_size=25, model='gaussian', min_fwhm=3.0)
+        fwhm = median_fwhm(im, x, y, box_size=25, model='gaussian',
+                           min_fwhm=3.0)
         assert_almost_equal(fwhm, 2.35*sigma, decimal=0)
 
-    pytest.mark.skip('Wrong new centers?')
-    def test_starfind_recenter_sources(self):
-        size = (256, 256)
-        number = 10
+    def test_starfind_calc_fwhm_moffat(self):
+        size = (512, 512)
+        number = 15
         sky = 70
         rdnoise = 20
         low = 120000
         high = 320000
-        sigma = 5
-        theta = 0
+        fwhm_true = 5
 
         x, y, f = gen_position_flux(size, number, low, high, rng_seed=456)
 
         im = gen_image(size, x, y, f, sky, rdnoise,
-                       model='gaussian', sigma=sigma, theta=theta)
+                       model='moffat', fwhm=fwhm_true)
 
-        nx, ny = recenter_sources(im,
-                                  x+np.random.normal(loc=0, scale=1,
-                                                     size=len(x)),
-                                  y+np.random.normal(loc=0, scale=1,
-                                                     size=len(x)),
-                                  box_size=15, model='gaussian')
-
-        assert_equal(len(nx), number)
-        assert_equal(len(ny), number)
-        # TODO: this seems unprecise. Investigate it.
-        assert_almost_equal(nx, x, decimal=-1)
-        assert_almost_equal(ny, y, decimal=-1)
+        fwhm = median_fwhm(im, x, y, box_size=25, model='moffat',
+                           min_fwhm=3.0)
+        assert_almost_equal(fwhm, fwhm_true, decimal=0)
 
     def test_starfind_one_star(self):
         size = (128, 128)
         x, y = (64, 64)
         f = 80000
         sky = 70
         rdnoise = 20
         sigma = 5
         theta = 0
-        fwhm = 5  # dummy low value
         threshold = 10
 
         im = gen_image(size, [x], [y], [f], sky, rdnoise,
                        model='gaussian', sigma=sigma, theta=theta)
 
-        sources = starfind(im, threshold, sky, rdnoise, fwhm)
+        sources = starfind(im, threshold, sky, rdnoise, fwhm=3.0)
 
         assert_equal(len(sources), 1)
         assert_almost_equal(sources['x'], x, decimal=0)
         assert_almost_equal(sources['y'], y, decimal=0)
         assert_almost_equal(sources.meta['astropop fwhm'], sigma*2.355,
-                            decimal=1)
+                            decimal=0)
 
     def test_starfind_strong_weak(self):
         size = (200, 100)
         posx = (50, 150)
         posy = (40, 60)
         sky = 800
         rdnoise = 20
@@ -867,69 +703,69 @@
 
         sources = starfind(im, threshold, sky, rdnoise, fwhm)
 
         assert_equal(len(sources), 2)
         assert_almost_equal(sources['x'], posx, decimal=1)
         assert_almost_equal(sources['y'], posy, decimal=1)
         assert_almost_equal(sources.meta['astropop fwhm'], sigma*2.355,
-                            decimal=1)
+                            decimal=0)
 
     def test_starfind_blind_fwhm(self):
         size = (512, 512)
         number = 12
         low, high = (15000, 60000)
         sky = 800
         rdnoise = 20
         sigma = 2
         theta = 0
-        threshold = 8
+        threshold = 10
 
         x, y, f = gen_position_flux(size, number, low, high, rng_seed=456)
-        x, y, f = self.resort_sources(x, y, f)
 
         im = gen_image(size, x, y, f, sky, rdnoise,
                        model='gaussian', sigma=sigma, theta=theta)
 
         sources = starfind(im, threshold, sky, rdnoise)
 
         assert_equal(len(sources), number)
         assert_almost_equal(sources['x'], x, decimal=1)
         assert_almost_equal(sources['y'], y, decimal=1)
         assert_almost_equal(sources.meta['astropop fwhm'], sigma*2.355,
-                            decimal=2)
+                            decimal=0)
 
     def test_starfind_rejection(self):
         size = (128, 128)
-        pos_x = [20, 60, 100, 40, 80, 50]
-        pos_y = [20, 30, 40, 50, 60, 85]
+        pos_x = np.array([20, 60, 100, 40, 80, 50])
+        pos_y = np.array([20, 30, 40, 50, 60, 85])
         sky = 70
-        rdnoise = 20
-        flux = [30000]*6
+        rdnoise = 5
+        flux = np.arange(6)*500+30000
         theta = 0
         fwhm = 3
         sig_base = gaussian_fwhm_to_sigma*fwhm
-        sigma_x = np.array([1, 0.5, 1, 2.0, 0.1, 1])*sig_base
-        sigma_y = np.array([1, 1.0, 1, 0.5, 0.1, 1])*sig_base
+        sigma_x = np.array([1, 0.5, 1.2, 2.0, 0.1, 0.8])*sig_base
+        sigma_y = np.array([1, 1.0, 1.2, 0.5, 0.1, 0.9])*sig_base
         threshold = 10
-        # stars 0, 2 -> passed
+        # stars 0, 2, 5 -> passed
         # star 4 -> rejected by sharpness
         # stars 1, 3 -> rejected by roundness
+        order = [5, 2, 0]  # flux encreases in order, peak not
 
         im = gen_image(size, pos_x, pos_y, flux, sky, rdnoise,
                        model='gaussian', sigma=(sigma_x, sigma_y),
                        theta=theta)
 
         sources = starfind(im, threshold, sky, rdnoise,
                            sharp_limit=(0.3, 0.6), round_limit=(-0.5, 0.5))
 
         assert_equal(len(sources), 3)
-        assert_almost_equal(sources['x'], [20, 100, 50], decimal=0)
-        assert_almost_equal(sources['y'], [20, 40, 85], decimal=0)
+        assert_almost_equal(sources['x'], pos_x[order], decimal=0)
+        assert_almost_equal(sources['y'], pos_y[order], decimal=0)
         assert_almost_equal(sources.meta['astropop fwhm'], fwhm,
-                            decimal=1)
+                            decimal=0)
 
     def test_starfind_one_star_subpixel(self):
         size = (128, 128)
         pos = (54.32, 47.86)
 
         im = gen_image(size, [pos[0]], [pos[1]], [45000], 800, 0,
                        sigma=[5*gaussian_fwhm_to_sigma],
```

### Comparing `astropop-0.5.4/tests/test_filecollection.py` & `astropop-0.9.0/tests/test_filecollection.py`

 * *Files 2% similar despite different names*

```diff
@@ -126,15 +126,15 @@
     def test_fg_create_filegroup_without_compression(self, tmpdir):
         tmpdir, flist = tmpdir
         fg = FitsFileGroup(location=tmpdir/'fits', compression=False)
         assert_is_instance(fg, FitsFileGroup)
         assert_equal(len(fg), 30)
         assert_equal(sorted(fg.files), sorted(flist['fits']))
 
-        #Default is False
+        # Default is False
         fg = FitsFileGroup(location=tmpdir/'fits')
         assert_is_instance(fg, FitsFileGroup)
         assert_equal(len(fg), 30)
         assert_equal(sorted(fg.files), sorted(flist['fits']))
 
     def test_fg_creation_files(self, tmpdir):
         tmpdir, flist = tmpdir
@@ -320,14 +320,42 @@
         for i in fg.group_by('object'):
             assert_is_instance(i, FitsFileGroup)
             assert_equal(len(i.values('object', unique=True)), 1)
             assert_in(i.values('object', unique=True)[0],
                       ['bias', 'flat', 'Moon'])
             assert_equal(len(i), 10)
 
+    def test_fg_remove_file_int(self, tmpdir):
+        tmpdir, flist = tmpdir
+        fg = FitsFileGroup(location=tmpdir/'fits', compression=False)
+
+        fg.remove_file(0)
+        assert_equal(len(fg), 29)
+        assert_equal(fg.files, flist['fits'][1:])
+
+        fg.remove_file(-1)
+        assert_equal(len(fg), 28)
+        assert_equal(fg.files, flist['fits'][1:-1])
+
+    def test_fg_remove_file_str(self, tmpdir):
+        tmpdir, flist = tmpdir
+        fg = FitsFileGroup(location=tmpdir/'fits', compression=False)
+
+        fg.remove_file(flist['fits'][0])
+        assert_equal(len(fg), 29)
+        assert_equal(fg.files, flist['fits'][1:])
+
+        fg.remove_file(flist['fits'][-1])
+        assert_equal(len(fg), 28)
+        assert_equal(fg.files, flist['fits'][1:-1])
+
+        with pytest.raises(ValueError, match='file not in group'):
+            fg.remove_file('NonExistingFile')
+
+
 class Test_ListFitsFiles():
     def test_list_custom_extension(self, tmpdir):
         tmpdir, flist = tmpdir
         found_files = list_fits_files(tmpdir/'custom',
                                       fits_extensions='.myfits')
         assert_equal(sorted(found_files), sorted(flist['myfits']))
```

### Comparing `astropop-0.5.4/tests/test_framedata_compat.py` & `astropop-0.9.0/tests/test_framedata_compat.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 # Licensed under a 3-clause BSD style license - see LICENSE.rst
 # flake8: noqa: F403, F405
 
 import pytest
 import numpy as np
-from astropop.framedata.compat import extract_header_wcs, _extract_ccddata, \
+from astropop.framedata._compat import extract_header_wcs, _extract_ccddata, \
                                       _extract_fits, _merge_and_clean_header
 from astropy.io import fits
 from astropy.wcs import WCS
 from astropy.table import Table
 from astropy.nddata import StdDevUncertainty, InverseVariance, \
                            VarianceUncertainty, UnknownUncertainty, \
                            CCDData
@@ -15,15 +15,16 @@
 from astropop.logger import logger, log_to_list
 from astropop.testing import *
 
 
 _comon_wcs_keys = ('CTYPE', 'CRVAL', 'CRPIX', 'CD1_', 'CD2_', 'PC1_', 'PC2_')
 
 
-_base_header = """SIMPLE  =                    T / Fits standard
+_base_header = """
+SIMPLE  =                    T / Fits standard
 BITPIX  =                  -32 / FOUR-BYTE SINGLE PRECISION FLOATING POINT
 NAXIS   =                    2 / STANDARD FITS FORMAT
 NAXIS1  =                  256 / STANDARD FITS FORMAT
 NAXIS2  =                  256 / STANDARD FITS FORMAT
 DATE-OBS= '1996-10-14T10:14:36.123' / Date and time of start of obs. in UTC.
 """
 
@@ -118,15 +119,100 @@
 HISTORY Second line of history
 HISTORY Third line of history
 COMMENT This is a first comment
 COMMENT This is a second comment
 COMMENT This is a third comment
 """
 
-class Test_ExtractHeader():
+
+class Test_MergeAndCleanHeader():
+    def test_types_meta_dict(self):
+        meta = {'META1': 1, 'META2': 2}
+        meta, wcs, history, comments = _merge_and_clean_header(meta, None,
+                                                               None)
+        assert_is_instance(meta, fits.Header)
+        assert_equal(meta['META1'], 1)
+        assert_equal(meta['META2'], 2)
+        assert_is_none(wcs)
+        assert_equal(history, [])
+        assert_equal(comments, [])
+
+    def test_types_meta_header(self):
+        meta = fits.Header()
+        meta['META1'] = 1
+        meta['META2'] = 2
+        meta, wcs, history, comments = _merge_and_clean_header(meta, None,
+                                                               None)
+        assert_is_instance(meta, fits.Header)
+        assert_equal(meta['META1'], 1)
+        assert_equal(meta['META2'], 2)
+        assert_is_none(wcs)
+        assert_equal(history, [])
+        assert_equal(comments, [])
+
+    def test_types_meta_invalid(self):
+        meta = 'invalid'
+        with pytest.raises(TypeError):
+            _merge_and_clean_header(meta, None, None)
+
+    def test_types_header(self):
+        header = fits.Header()
+        header['META1'] = 1
+        header['META2'] = 2
+        meta, wcs, history, comments = _merge_and_clean_header(None, header,
+                                                               None)
+        assert_is_instance(meta, fits.Header)
+        assert_equal(meta['META1'], 1)
+        assert_equal(meta['META2'], 2)
+        assert_is_none(wcs)
+        assert_equal(history, [])
+        assert_equal(comments, [])
+
+    def test_types_invalid(self):
+        header = 'invalid'
+        with pytest.raises(TypeError):
+            _merge_and_clean_header(None, header, None)
+
+    def test_types_wcs(self):
+        wcs = WCS(naxis=2)
+        wcs.wcs.ctype = ['RA---TAN', 'DEC--TAN']
+        meta, wcs, history, comments = _merge_and_clean_header(None, None,
+                                                               wcs)
+        assert_is_instance(meta, fits.Header)
+        assert_is_instance(wcs, WCS)
+        assert_equal(history, [])
+        assert_equal(comments, [])
+
+    def test_types_invalid_wcs(self):
+        wcs = 'invalid'
+        with pytest.raises(TypeError):
+            _merge_and_clean_header(None, None, wcs)
+
+    def test_dict_meta_history(self):
+        meta = {'META1': 1, 'META2': 2, 'history': ['test a', 'test b']}
+        meta, wcs, history, comments = _merge_and_clean_header(meta, None,
+                                                               None)
+        assert_is_instance(meta, fits.Header)
+        assert_equal(meta['META1'], 1)
+        assert_equal(meta['META2'], 2)
+        assert_is_none(wcs)
+        assert_equal(history, ['test a', 'test b'])
+        assert_equal(comments, [])
+
+    def test_dict_meta_comment(self):
+        meta = {'META1': 1, 'META2': 2, 'comment': ['test a', 'test b']}
+        meta, wcs, history, comments = _merge_and_clean_header(meta, None,
+                                                               None)
+        assert_is_instance(meta, fits.Header)
+        assert_equal(meta['META1'], 1)
+        assert_equal(meta['META2'], 2)
+        assert_is_none(wcs)
+        assert_equal(history, [])
+        assert_equal(comments, ['test a', 'test b'])
+
     def test_merge_and_clean_header(self):
         strhdr = _base_header+_wcs_no_sip+_hist_comm_blank
         header = fits.Header.fromstring(strhdr, sep='\n')
         header['TEST'] = ('value', 'comment')
 
         meta = {'META1': 1, 'META2': 2}
         meta, wcs, history, comments = _merge_and_clean_header(meta, header,
@@ -151,14 +237,22 @@
         assert_equal(history, ['First line of history',
                                'Second line of history',
                                'Third line of history'])
         assert_equal(comments, ['This is a first comment',
                                 'This is a second comment',
                                 'This is a third comment'])
 
+    def test_extract_wcs_meta_conflict(self):
+        header = fits.Header.fromstring(_base_header+_wcs_no_sip, sep='\n')
+        wcs = WCS(header)
+        with pytest.raises(ValueError, match='meta and wcs'):
+            _merge_and_clean_header(header, None, wcs=wcs)
+
+
+class Test_ExtractHeader():
     def test_extract_header_nowcs(self):
         header = fits.Header.fromstring(_base_header, sep='\n')
         h, wcs = extract_header_wcs(header)
         assert_is_none(wcs)
         assert_is_instance(h, fits.Header)
         assert_equal(h, header)
         assert_false(h is header)
@@ -297,29 +391,29 @@
     def mask(self):
         mask = np.zeros(self.shape, dtype=bool)
         mask[1:3, 1:3] = 1
         return mask
 
     def create_hdu(self, uncert=False, mask=False,
                    unit='adu', unit_key='BUNIT'):
-        l = []
+        li = []
         data = 100*np.ones(self.shape)
         header = self.create_header(unit=unit, unit_key=unit_key)
         data_hdu = fits.PrimaryHDU(data, header=header)
-        l.append(data_hdu)
+        li.append(data_hdu)
 
         if uncert:
             uncert_hdu = fits.ImageHDU(np.ones(self.shape), name='UNCERT')
-            l.append(uncert_hdu)
+            li.append(uncert_hdu)
 
         if mask:
             mask_hdu = fits.ImageHDU(self.mask.astype('uint8'), name='MASK')
-            l.append(mask_hdu)
+            li.append(mask_hdu)
 
-        hdul = fits.HDUList(l)
+        hdul = fits.HDUList(li)
         return hdul
 
     def create_header(self, unit=None, unit_key=None):
         header = fits.Header()
         if unit is not None:
             header[unit_key] = unit
         return header
```

### Comparing `astropop-0.5.4/tests/test_imcombine.py` & `astropop-0.9.0/tests/test_imcombine.py`

 * *Files 3% similar despite different names*

```diff
@@ -4,15 +4,15 @@
 import os
 import numpy as np
 import pytest
 
 from astropy.io import fits
 
 from astropy.utils import NumpyRNGContext
-from astropop.framedata import FrameData
+from astropop.framedata import FrameData, PixelMaskFlags
 from astropop.logger import logger, log_to_list
 from astropop.image.imcombine import imcombine, _sigma_clip, \
                                      _minmax_clip, ImCombiner
 from astropop.testing import *
 
 
 class Test_MinMaxClip():
@@ -219,15 +219,15 @@
 
         f = ImCombiner(dtype=np.float32)
         assert_equal(f._dtype, np.float32)
 
     def test_creation_error_dtype(self):
         msg = "Only float dtypes are allowed in ImCombiner."
         with pytest.raises(ValueError, match=msg):
-            ImCombiner(dtype=np.int)
+            ImCombiner(dtype=np.int_)
         with pytest.raises(ValueError, match=msg):
             ImCombiner(dtype=np.int16)
 
         with pytest.raises(ValueError, match=msg):
             ImCombiner(dtype=np.int32)
 
         with pytest.raises(ValueError, match=msg):
@@ -364,21 +364,21 @@
         # not numbers should fail
         with pytest.raises(ValueError):
             c.set_minmax_clip(0, [1, 2])
 
     def test_check_consistency(self):
         n = 10
         d = np.ones((10, 10))
-        l = [FrameData(d, unit='adu') for i in range(n)]
+        li = [FrameData(d, unit='adu') for i in range(n)]
         comb = ImCombiner()
         # empty should raise
         with pytest.raises(ValueError, match='Combiner have no images.'):
             comb._check_consistency()
 
-        comb._load_images(l)
+        comb._load_images(li)
         # nothing should raise
         comb._check_consistency()
 
         # incompatible unit should raise
         comb._images[3].unit = 'm'
         with pytest.raises(ValueError, match='.* unit incompatible .*'):
             comb._check_consistency()
@@ -388,64 +388,67 @@
         comb._images[4].data = np.ones((2, 2))
         with pytest.raises(ValueError, match='.* shape incompatible .*'):
             comb._check_consistency()
 
     def test_invalid_method(self):
         n = 10
         d = np.ones((10, 10))
-        l = [FrameData(d, unit='adu') for i in range(n)]
+        li = [FrameData(d, unit='adu') for i in range(n)]
         comb = ImCombiner()
         with pytest.raises(ValueError, match='hulk-smash is not a valid '
                            'combining method.'):
-            comb.combine(l, method='hulk-smash')
+            comb.combine(li, method='hulk-smash')
 
 
 class Test_ImCombiner_ChunkYielder():
     @pytest.mark.parametrize('method', ['mean', 'median', 'sum'])
     def test_chunk_yielder_f64(self, method):
         n = 100
         d = np.random.random((100, 100)).astype(np.float64)
-        l = [FrameData(d, unit='adu') for i in range(n)]
+        li = [FrameData(d, unit='adu') for i in range(n)]
         # data size = 8 000 000 = 8 bytes * 100 * 100 * 100
-        # mask size = 1 000 000 = 1 bytes * 100 * 100 * 100
-        # total size = 9 000 000
+        # total size = 8M
 
         comb = ImCombiner(max_memory=1e6, dtype=np.float64)
-        comb._load_images(l)
+        comb._load_images(li)
 
         logs = []
         lh = log_to_list(logger, logs, False)
         level = logger.getEffectiveLevel()
         logger.setLevel('DEBUG')
 
         if method == 'median':
-            # for median, tot_size=9*4.5=41
-            # xstep = 2, so n_chuks=50
+            # for median, tot_size=8M*4.5=36M
+            # n_chunks=36M/1M=36
+            # xstep = 100/36 = 2.777 => 2
+            # so n_chunks=100/2 = 50
             nchunk = 50
             shape = [(n, 2, 100)]
         elif method in ['mean', 'sum']:
-            # for mean and sum, tot_size=9*3=27
-            # xstep = 3, so n_chunks=33+1
-            nchunk = 34
-            shape = [(n, 3, 100), (n, 1, 100)]
+            # for mean and sum, tot_size=8M*3=24M
+            # n_chunks=24M/1M=24
+            # xstep = 100/24 = 4.166 => 4
+            # so n_chunks=100/4 = 25
+            nchunk = 25
+            shape = [(n, 4, 100)]
 
         i = 0
         for chunk, unct, slc in comb._chunk_yielder(method=method):
             i += 1
             assert_in(chunk.shape, shape)
             assert_equal(chunk[0], d[slc])
             assert_is_none(unct)
             assert_is_instance(chunk, np.ndarray)
         assert_equal(i, nchunk)
         assert_in(f'Splitting the images into {nchunk} chunks.', logs)
         logs.clear()
 
         # this should not split into chunks
         comb = ImCombiner(max_memory=1e8)
-        comb._load_images(l)
+        comb._load_images(li)
 
         i = 0
         for chunk, unct, slc in comb._chunk_yielder(method=method):
             i += 1
             assert_equal(chunk.shape, (n, 100, 100))
             assert_equal(chunk[0], d)
             assert_is_none(unct)
@@ -453,156 +456,178 @@
         assert_equal(i, 1)
 
     @pytest.mark.parametrize('method', ['mean', 'median', 'sum'])
     def test_chunk_yielder_f32(self, method):
         # using float32, the number of chunks are almost halved
         n = 100
         d = np.random.random((100, 100)).astype(np.float64)
-        l = [FrameData(d, unit='adu') for i in range(n)]
+        li = [FrameData(d, unit='adu') for i in range(n)]
         # data size = 4 000 000 = 4 bytes * 100 * 100 * 100
-        # mask size = 1 000 000 = 1 bytes * 100 * 100 * 100
-        # total size = 5 000 000
+        # total size = 4 000 000 = 4M
 
         comb = ImCombiner(max_memory=1e6, dtype=np.float32)
-        comb._load_images(l)
+        comb._load_images(li)
 
         logs = []
         lh = log_to_list(logger, logs, False)
         level = logger.getEffectiveLevel()
         logger.setLevel('DEBUG')
 
         if method == 'median':
-            # for median, tot_size=5*4.5=22.5
-            # xstep = 4, so n_chuks=25
-            nchunk = 25
-            shape = [(n, 4, 100)]
+            # for median, tot_size=4M*4.5=18M
+            # n_chunks=18M/1M=18
+            # xstep = 100/18 = 5.55 => 5
+            # so n_chunks=100/5=20
+            nchunk = 20
+            shape = [(n, 5, 100)]
         elif method in ['mean', 'sum']:
-            # for mean and sum, tot_size=5*3=15
-            # xstep = 6, so n_chunks=16+1
-            nchunk = 17
-            shape = [(n, 6, 100), (n, 4, 100)]
+            # for mean and sum, tot_size=4*3=12M
+            # n_chunks=12M/1M=12
+            # xstep = 100/12 = 8.33 => 8
+            # so n_chunks=100/8 = 13
+            nchunk = 13
+            shape = [(n, 8, 100), (n, 4, 100)]
 
         i = 0
         for chunk, unct, slc in comb._chunk_yielder(method=method):
             i += 1
             assert_in(chunk.shape, shape)
-            assert_almost_equal(chunk[0], d[slc])
+            assert_almost_equal(chunk[0], d[slc], decimal=5)
             assert_is_none(unct)
             assert_is_instance(chunk, np.ndarray)
         assert_equal(i, nchunk)
         assert_in(f'Splitting the images into {nchunk} chunks.', logs)
         logs.clear()
 
         # this should not split into chunks
         comb = ImCombiner(max_memory=1e8)
-        comb._load_images(l)
+        comb._load_images(li)
 
         i = 0
         for chunk, unct, slc in comb._chunk_yielder(method=method):
             i += 1
             assert_equal(chunk.shape, (n, 100, 100))
-            assert_equal(chunk[0], d)
+            assert_almost_equal(chunk[0], d, decimal=5)
             assert_is_none(unct)
             assert_is_instance(chunk, np.ndarray)
         assert_equal(i, 1)
         logs.clear()
 
     def test_chunk_yielder_ysplit(self):
         # using float32, the number of chunks are almost halved
         n = 100
         d = np.random.random((100, 100)).astype(np.float64)
-        l = [FrameData(d, unit='adu') for i in range(n)]
+        li = [FrameData(d, unit='adu') for i in range(n)]
         # data size = 4 000 000 = 4 bytes * 100 * 100 * 100
-        # mask size = 1 000 000 = 1 bytes * 100 * 100 * 100
-        # total size = 5 000 000
+        # total size = 4 000 000 = 4M
 
         logs = []
         lh = log_to_list(logger, logs, False)
         level = logger.getEffectiveLevel()
         logger.setLevel('DEBUG')
 
-        # this should split in 300 chunks!
-        # total_size = 4.5*5e6=22.5e6 = 225 chunks
-        # x_step = 1
-        # y_step = 45
+        # this should split in 200 chunks!
+        # total_size = 4.5*4M = 18M
+        # num_chunks = 18M/0.1M = 180
+        # x_step = 100/180 = 0.55 => 1
+        # y_step = 50
         comb = ImCombiner(max_memory=1e5, dtype=np.float32)
-        comb._load_images(l)
+        comb._load_images(li)
         i = 0
         for chunk, unct, slc in comb._chunk_yielder(method='median'):
             i += 1
             for k in chunk:
-                assert_in(k.shape, ((1, 45), (1, 10)))
+                assert_equal(k.shape, (1, 50))
                 assert_almost_equal(k, d[slc])
                 assert_is_none(unct)
                 assert_is_instance(k, np.ndarray)
-        assert_equal(i, 300)
-        assert_in('Splitting the images into 300 chunks.', logs)
+        assert_equal(i, 200)
+        assert_in('Splitting the images into 200 chunks.', logs)
         logs.clear()
 
         logger.setLevel(level)
         logger.removeHandler(lh)
 
     def test_chunk_yielder_uncertainty(self):
         n = 100
         d = np.random.random((100, 100)).astype(np.float64)
         u = np.random.random((100, 100)).astype(np.float64)
-        l = [FrameData(d, uncertainty=u, unit='adu') for i in range(n)]
+        li = [FrameData(d, uncertainty=u, unit='adu') for i in range(n)]
 
         # simple sum with uncertainties
         comb = ImCombiner(max_memory=2e6, dtype=np.float64)
-        comb._load_images(l)
+        comb._load_images(li)
         i = 0
         for chunk, unct, slc in comb._chunk_yielder(method='sum'):
             i += 1
-            for k,un in zip(chunk, unct):
-                assert_in(k.shape, ((7, 100), (2, 100)))
+            for k, un in zip(chunk, unct):
+                assert_in(k.shape, ((8, 100), (4, 100)))
                 assert_almost_equal(k, d[slc])
                 assert_almost_equal(un, u[slc])
                 assert_is_instance(un, np.ndarray)
-        assert_equal(i, 15)
+        assert_equal(i, 13)
 
         # if a single uncertainty is empty, disable it
         logs = []
         lh = log_to_list(logger, logs, False)
         level = logger.getEffectiveLevel()
         logger.setLevel('DEBUG')
 
-        l[5].uncertainty = None
+        li[5].uncertainty = None
         comb = ImCombiner(max_memory=2e6, dtype=np.float64)
-        comb._load_images(l)
+        comb._load_images(li)
         i = 0
         for chunk, unct, slc in comb._chunk_yielder(method='sum'):
             i += 1
             for k in chunk:
-                assert_in(k.shape, ((7, 100), (2, 100)))
+                assert_in(k.shape, ((8, 100), (4, 100)))
                 assert_almost_equal(k, d[slc])
                 assert_equal(unct, None)
-        assert_equal(i, 15)
+        assert_equal(i, 13)
         assert_in('One or more frames have empty uncertainty. '
                   'Some features are disabled.',
                   logs)
         logs.clear()
         logger.setLevel(level)
         logger.removeHandler(lh)
 
+    def test_chunk_yielder_mask_nan(self):
+        n = 100
+        d = np.random.random((100, 100)).astype(np.float64)
+        m = np.zeros((100, 100), dtype=bool)
+        # all these pixels should be masked at the end
+        m[90:] = True
+        m[50:60, 50:60] = True
+        m[1, 1] = True
+        li = [FrameData(d, mask=m, unit='adu') for i in range(n)]
+
+        d_masked = d.copy()
+        d_masked[m] = np.nan
+
+        comb = ImCombiner(max_memory=2e6, dtype=np.float64)
+        comb._load_images(li)
+        for chunk, unct, slc in comb._chunk_yielder(method='sum'):
+            for k in chunk:
+                assert_equal(np.isnan(k), m[slc])
+
 
 class Test_ImCombiner_LoadImages():
     @pytest.mark.parametrize('disk_cache', [True, False])
     def test_image_loading_framedata(self, tmpdir, disk_cache):
         tmp = tmpdir.strpath
         n = 10
         d = np.ones((10, 10))
-        l = [FrameData(d, unit='adu', uncertainty=d, cache_folder=tmp,
-                       cache_filename=f'test{i}') for i in range(n)]
+        li = [FrameData(d, unit='adu', uncertainty=d, cache_folder=tmp,
+                        cache_filename=f'test{i}') for i in range(n)]
 
         comb = ImCombiner(use_disk_cache=disk_cache)
         # must start empty
         assert_equal(len(comb._images), 0)
         assert_is_none(comb._buffer)
-        comb._load_images(l)
+        comb._load_images(li)
         assert_equal(len(comb._images), n)
         assert_is_none(comb._buffer)
         for i, v in enumerate(comb._images):
             fil = os.path.join(tmp, f'test{i}')
             assert_is_instance(v, FrameData)
             if disk_cache:
                 assert_true(v._memmapping)
@@ -624,20 +649,20 @@
                 assert_path_not_exists(fil+'_copy_copy.mask')
 
     @pytest.mark.parametrize('disk_cache', [True, False])
     def test_image_loading_fitsfile(self, tmpdir, disk_cache):
         tmp = tmpdir.strpath
         n = 10
         d = np.ones((10, 10))
-        l = [os.path.join(tmp, f'fits_test{i}') for i in range(n)]
-        for f in l:
+        li = [os.path.join(tmp, f'fits_test{i}') for i in range(n)]
+        for f in li:
             fits.PrimaryHDU(d).writeto(f)
 
         comb = ImCombiner(use_disk_cache=disk_cache)
-        comb._load_images(l)
+        comb._load_images(li)
 
         assert_equal(len(comb._images), n)
         assert_is_none(comb._buffer)
         for i, v in enumerate(comb._images):
             assert_is_instance(v, FrameData)
             if disk_cache:
                 assert_true(v._memmapping)
@@ -647,18 +672,18 @@
         assert_equal(len(comb._images), 0)
         assert_is_none(comb._buffer)
 
     @pytest.mark.parametrize('disk_cache', [True, False])
     def test_image_loading_fitshdu(self, disk_cache):
         n = 10
         d = np.ones((10, 10))
-        l = [fits.PrimaryHDU(d) for i in range(n)]
+        li = [fits.PrimaryHDU(d) for i in range(n)]
 
         comb = ImCombiner(use_disk_cache=disk_cache)
-        comb._load_images(l)
+        comb._load_images(li)
 
         assert_equal(len(comb._images), n)
         assert_is_none(comb._buffer)
         for i, v in enumerate(comb._images):
             assert_is_instance(v, FrameData)
             if disk_cache:
                 assert_true(v._memmapping)
@@ -769,15 +794,15 @@
             mask[2, 5] = 1
             images[i] = FrameData(np.ones(shape), unit='adu', mask=mask)
 
         # these points in result must no be masked
         images[5].mask[7, 7] = 1
         images[2].mask[7, 7] = 1
         images[8].mask[8, 8] = 1
-        expect = np.zeros(shape)
+        expect = np.zeros(shape, dtype=bool)
         expect[2, 5] = 1
 
         # with ImCombiner
         comb = ImCombiner()
         res = comb.combine(images, method)
         assert_equal(res.mask, expect)
 
@@ -812,45 +837,43 @@
     @pytest.mark.parametrize('method', ['sum', 'median', 'mean'])
     def test_combine_masked(self, method):
         values = [0.8, 1.0, 0.9, 1.1, 1.2, 1.1, 1.0, 0.8, 0.9]
         n = len(values)
         shape = (10, 10)
         images = [FrameData(np.ones(shape)*i, unit='adu') for i in values]
 
-        # this pixel is masked and must be ignored
-        images[0].mask[0, 0] = 1
-        images[0].data[0, 0] = 1000
+        images[0].mask_pixels((1, 0))
+        images[0].data[1, 0] = 100000
 
         if method == 'median':
             med = np.ones(shape)*np.median(values)
             std = np.ones(shape)*np.std(values)/np.sqrt(n)
-            med[0, 0] = np.median(values[1:])
-            std[0, 0] = np.std(values[1:])/np.sqrt(n-1)
+            med[1, 0] = np.median(values[1:])
+            std[1, 0] = np.std(values[1:])/np.sqrt(n-1)
         elif method == 'mean':
             med = np.ones(shape)*np.mean(values)
             std = np.ones(shape)*np.std(values)/np.sqrt(n)
-            med[0, 0] = np.mean(values[1:])
-            std[0, 0] = np.std(values[1:])/np.sqrt(n-1)
+            med[1, 0] = np.mean(values[1:])
+            std[1, 0] = np.std(values[1:])/np.sqrt(n-1)
         elif method == 'sum':
             med = np.ones(shape)*np.sum(values)
             std = np.ones(shape)*np.std(values)*np.sqrt(n)
-            med[0, 0] = np.sum(values[1:])*float(n)/(n-1)
-            std[0, 0] = np.std(values[1:])*np.sqrt(n-1)*float(n)/(n-1)
+            med[1, 0] = np.sum(values[1:])*float(n)/(n-1)
+            std[1, 0] = np.std(values[1:])*np.sqrt(n-1)*float(n)/(n-1)
 
         comb = ImCombiner()
         res1 = comb.combine(images, method=method)
         res2 = imcombine(images, method=method)
         for res in (res1, res2):
             assert_almost_equal(res.data, med)
             assert_almost_equal(res.uncertainty, std)
             assert_equal(res.meta['astropop imcombine nimages'], n)
             assert_equal(res.meta['astropop imcombine method'], method)
 
 
-
 class Test_ImCombiner_HeaderMerging():
     def create_images(self):
         images = []
         for i in range(30):
             meta = {'first_equal': 1,
                     'second_equal': 2,
                     'first_differ': i,
```

### Comparing `astropop-0.5.4/tests/test_logger.py` & `astropop-0.9.0/tests/test_logger.py`

 * *Files identical despite different names*

### Comparing `astropop-0.5.4/tests/test_physical.py` & `astropop-0.9.0/tests/test_physical.py`

 * *Files 6% similar despite different names*

```diff
@@ -162,55 +162,133 @@
     def test_qfloat_init_qfloat_conflicts(self):
         qf = QFloat(1.0, 0.1, 'm')
         with pytest.raises(ValueError):
             QFloat(qf, unit='m')
         with pytest.raises(ValueError):
             QFloat(qf, uncertainty=0.1)
 
+    def test_qfloat_set_sig_digits(self):
+        qf = QFloat(1.0, 0.1, 'm')
+        qf.sig_digits = 2
+        assert_equal(qf.nominal, 1.0)
+        assert_equal(qf.uncertainty, 0.1)
+        assert_equal(qf.unit, units.m)
+        assert_equal(qf.sig_digits, 2)
+
+    def test_qfloat_set_sig_digits_error(self):
+        qf = QFloat(1.0, 0.1, 'm')
+        with pytest.raises(TypeError,
+                           match='sig_digits must be a real number.'):
+            qf.sig_digits = 'k'
+
 
 class Test_QFloat_Repr:
-    def test_qfloat_repr(self):
-        assert_equal(repr(QFloat(1.0, 0.1, 'm')), '<QFloat 1.0+-0.1 m>')
-        assert_equal(repr(QFloat(1, 0.1, 'm')), '<QFloat 1.0+-0.1 m>')
-        assert_equal(repr(QFloat(1, 0.01, 'm')), '<QFloat 1.00+-0.01 m>')
-        assert_equal(repr(QFloat(1.00, 0.01, 'm')), '<QFloat 1.00+-0.01 m>')
-        assert_equal(repr(QFloat(1.00, 0.012, 'm')), '<QFloat 1.00+-0.01 m>')
-        assert_equal(repr(QFloat(1.00, 0.016, 'm')), '<QFloat 1.00+-0.02 m>')
-        assert_equal(repr(QFloat(1.002, 0.016, 'm')), '<QFloat 1.00+-0.02 m>')
-        assert_equal(repr(QFloat(1.006, 0.016, 'm')), '<QFloat 1.01+-0.02 m>')
-        assert_equal(repr(QFloat(1.000005, 0.01, 'm')), '<QFloat 1.00+-0.01 m>')
-        assert_equal(repr(QFloat(9999, 1, 'm')), '<QFloat 9999+-1 m>')
-        assert_equal(repr(QFloat(9999, 10, 'm')), '<QFloat 10000+-10 m>')
+    def test_qfloat_repr_default(self):
+        for qf, rep in [(QFloat(1.0, 0.1, 'm'), '1.0+-0.1 m'),
+                        (QFloat(1.0, 0.01, 'm'), '1.00+-0.01 m'),
+                        (QFloat(1.00, 0.01, 'm'), '1.00+-0.01 m'),
+                        (QFloat(1.00, 0.012, 'm'), '1.00+-0.01 m'),
+                        (QFloat(1.00, 0.016, 'm'), '1.00+-0.02 m'),
+                        (QFloat(1.002, 0.016, 'm'), '1.00+-0.02 m'),
+                        (QFloat(1.006, 0.016, 'm'), '1.01+-0.02 m'),
+                        (QFloat(1.000005, 0.01, 'm'), '1.00+-0.01 m'),
+                        (QFloat(1.000005, 0.001, 'm'), '1.000+-0.001 m'),
+                        (QFloat(98, 0.98, 'm'), '98+-1 m'),
+                        (QFloat(98.7, 0.98, 'm'), '99+-1 m'),
+                        (QFloat(9999, 1, 'm'), '9999+-1 m'),
+                        (QFloat(9999, 10, 'm'), '10000+-10 m')]:
+            i = hex(id(qf))
+            assert_equal(repr(qf), f'<QFloat at {i}>\n{rep}')
+
+    def test_qfloat_repr_sig_digits(self):
+        for qf, rep in [(QFloat(1.0, 0.1, 'm'), '1.00+-0.10 m'),
+                        (QFloat(1.0, 0.01, 'm'), '1.000+-0.010 m'),
+                        (QFloat(1.00, 0.01, 'm'), '1.000+-0.010 m'),
+                        (QFloat(1.00, 0.012, 'm'), '1.000+-0.012 m'),
+                        (QFloat(1.00, 0.016, 'm'), '1.000+-0.016 m'),
+                        (QFloat(1.002, 0.016, 'm'), '1.002+-0.016 m'),
+                        (QFloat(1.006, 0.016, 'm'), '1.006+-0.016 m'),
+                        (QFloat(1.000005, 0.01, 'm'), '1.000+-0.010 m'),
+                        (QFloat(1.000005, 0.001, 'm'), '1.0000+-0.0010 m'),
+                        (QFloat(9999, 1, 'm'), '9999.0+-1.0 m'),
+                        (QFloat(9999, 10, 'm'), '9999+-10 m')]:
+            qf.sig_digits = 2
+            i = hex(id(qf))
+            assert_equal(repr(qf), f'<QFloat at {i}>\n{rep}')
 
     def test_qfloat_repr_array(self):
         n = np.array([1, 1, 1, 1.01, 1.001, 1.006])
         s = np.array([0.1, 0.01, 1.0, 0.01, 0.01, 0.01])
-        assert_equal(repr(QFloat(n, s, 'm')),
-                     '<QFloat\narray([1.0+-0.1, 1.00+-0.01, 1+-1, 1.01+-0.01,'
-                     ' 1.00+-0.01, 1.01+-0.01],\n      dtype=object)\nunit=m>')
-
-        qf = QFloat([1, 2, 3, 4, 5], [0.1, 0.2, 0.3, 0.4, 0.5], 'm')
+        qf = QFloat(n, s, 'm')
+        i = hex(id(qf))
+        assert_equal(repr(qf),
+                     f'<QFloat at {i}>\n'
+                     '[1.0+-0.1, 1.00+-0.01, 1+-1, 1.01+-0.01, '
+                     '1.00+-0.01, 1.01+-0.01] unit=m')
+
+        # 1D very large array
+        qf = QFloat(np.arange(1, 601), np.arange(1, 601)*0.01, 'm')
+        i = hex(id(qf))
         assert_equal(repr(qf),
-                     '<QFloat\narray([1.0+-0.1, 2.0+-0.2, 3.0+-0.3, 4.0+-0.4, 5.0'
-                     '+-0.5], dtype=object)\nunit=m>')
+                     f'<QFloat at {i}>\n'
+                     '[1.00+-0.01, 2.00+-0.02, 3.00+-0.03, ..., 598+-6, '
+                     '599+-6, 600+-6] unit=m')
 
-        # very large array
-        n = np.arange(0, 10000).reshape((100, 100))
+        # very large 2D array
+        n = np.arange(1, 10001).reshape((100, 100))
         s = n*0.01
         qf = QFloat(n, s, 's')
+        i = hex(id(qf))
+        assert_equal(repr(qf),
+                     f'<QFloat at {i}>\n'
+                     '[[1.00+-0.01, 2.00+-0.02, 3.00+-0.03, ..., 98+-1, 99+-1,'
+                     ' 100+-1],\n [101+-1, 102+-1, 103+-1, ..., 198+-2, '
+                     '199+-2, 200+-2],\n [201+-2, 202+-2, 203+-2, ..., '
+                     '298+-3, 299+-3, 300+-3],\n ...,\n [9700+-100, 9700+-100,'
+                     ' 9700+-100, ..., 9800+-100, 9800+-100, 9800+-100],\n'
+                     ' [9800+-100, 9800+-100, 9800+-100, ..., 9900+-100, '
+                     '9900+-100, 9900+-100],\n [9900+-100, 9900+-100, '
+                     '9900+-100, ..., 10000+-100, 10000+-100,\n  10000+-100]] '
+                     'unit=s')
+
+    def test_qfloat_repr_array_sig_digits(self):
+        n = np.array([1, 1, 1, 1.01, 1.001, 1.006])
+        s = np.array([0.12, 0.018, 1.08, 0.0126, 0.01, 0.01])
+        qf = QFloat(n, s, 'm')
+        i = hex(id(qf))
+        qf.sig_digits = 2
         assert_equal(repr(qf),
-                     '<QFloat\narray([[0+-0.0, 1.00+-0.01, 2.00+-0.02, ..., 97+-1'
-                     ', 98+-1, 99+-1],\n       [100+-1, 101+-1, 102+-1, ..., 197+'
-                     '-2, 198+-2, 199+-2],\n       [200+-2, 201+-2, 202+-2, ..., '
-                     '297+-3, 298+-3, 299+-3],\n       ...,\n       [9700+-100, 9'
-                     '700+-100, 9700+-100, ..., 9800+-100, 9800+-100,\n        98'
-                     '00+-100],\n       [9800+-100, 9800+-100, 9800+-100, ..., 99'
-                     '00+-100, 9900+-100,\n        9900+-100],\n       [9900+-100'
-                     ', 9900+-100, 9900+-100, ..., 10000+-100, 10000+-100,\n     '
-                     '   10000+-100]], dtype=object)\nunit=s>')
+                     f'<QFloat at {i}>\n'
+                     '[1.00+-0.12, 1.000+-0.018, 1.0+-1.1, 1.010+-0.013, '
+                     '1.001+-0.010,\n 1.006+-0.010] unit=m')
+
+    def test_qfloat_str_no_unit(self):
+        qf = QFloat(1.0, 0.1)
+        # must not have space after uncertainty
+        assert_equal(str(qf), '1.0+-0.1')
+
+    def test_qfloat_str(self):
+        qf = QFloat(1.0, 0.1, 'm')
+        assert_equal(str(qf), '1.0+-0.1 m')
+
+    def test_qfloat_str_array(self):
+        n = np.array([1, 1, 1, 1.01, 1.001, 1.006])
+        s = np.array([0.1, 0.01, 1.0, 0.01, 0.01, 0.01])
+        qf = QFloat(n, s, 'm')
+        assert_equal(str(qf),
+                     '[1.0+-0.1, 1.00+-0.01, 1+-1, 1.01+-0.01, 1.00+-0.01, '
+                     '1.01+-0.01] unit=m')
+
+    def test_qfloat_str_array_no_unit(self):
+        n = np.array([1, 1, 1, 1.01, 1.001, 1.006])
+        s = np.array([0.1, 0.01, 1.0, 0.01, 0.01, 0.01])
+        qf = QFloat(n, s)
+        assert_equal(str(qf),
+                     '[1.0+-0.1, 1.00+-0.01, 1+-1, 1.01+-0.01, 1.00+-0.01, '
+                     '1.01+-0.01]')
 
 
 class Test_QFloat_Operators:
     def test_qfloat_properties_getset(self):
         # access all important properties
         qf = QFloat(5.0, 0.025, 'm')
         assert_equal(qf.uncertainty, 0.025)
@@ -369,15 +447,15 @@
     @pytest.mark.parametrize('value,expect', [(QFloat(1.0, 0.1, 'm'), QFloat(1.0, 0.1, 'm')),
                                               (1, QFloat(1.0, 0, None)),
                                               (np.array([1, 2, 3]), QFloat([1, 2, 3], unit=None)),
                                               ('string', 'raise'),
                                               (None, 'raise'),
                                               (UnitsError, 'raise'),
                                               (1.0*units.m, QFloat(1.0, 0.0, 'm')),
-                                              (FrameData(1.0, 'm', 'f8', 0.1), QFloat(1.0, 0.1, 'm'))])
+                                              (FrameData([[1.0]], 'm', 'f8', 0.1), QFloat([[1.0]], [[0.1]], 'm'))])
     def test_qfloat_converttoqfloat(self, value, expect):
         if expect == 'raise':
             with pytest.raises(Exception):
                 convert_to_qfloat(value)
         else:
             conv = convert_to_qfloat(value)
             assert_equal(conv.nominal, expect.nominal)
@@ -1927,13 +2005,13 @@
         qf2 = QFloat([1.4, 2.5, 3.6], [0.2, 0.3, 0.4], 's')
 
         assert_equal(float(qf1), 1.5)
         with pytest.raises(TypeError):
             float(qf2)
 
     def test_qfloat_math_int(self):
-        qf1 = QFloat(1.5, 0.4, 'm')
+        qf1 = QFloat(1.0, 0.4, 'm')
         qf2 = QFloat([1.4, 2.5, 3.6], [0.2, 0.3, 0.4], 's')
 
         assert_equal(int(qf1), 1)
         with pytest.raises(TypeError):
             int(qf2)
```

### Comparing `astropop-0.5.4/tests/test_physical_numpyfuncs.py` & `astropop-0.9.0/tests/test_physical_numpyfuncs.py`

 * *Files 1% similar despite different names*

```diff
@@ -584,14 +584,22 @@
 
         res = np.squeeze(qf, axis=2)
         assert_equal(res.shape, (1, 3))
         assert_almost_equal(res.nominal, [[0, 1, 2]])
         assert_almost_equal(res.std_dev, [[0, 0.01, 0.02]])
         assert_equal(res.unit, qf.unit)
 
+    def test_qfloat_np_std(self):
+        qf = QFloat(np.arange(10), uncertainty=np.arange(10)*0.1)
+        assert_almost_equal(np.std(qf), 2.87228, decimal=4)
+
+        # errors do not enter in the account
+        qf = QFloat(np.arange(10), uncertainty=np.arange(10))
+        assert_almost_equal(np.std(qf), 2.87228, decimal=4)
+
     def test_qfloat_np_sum(self):
         arr = np.ones(10).reshape((2, 5))
         qf = QFloat(arr, arr*0.1, "m")
 
         res = np.sum(qf)
         assert_equal(res.nominal, 10)
         assert_equal(res.std_dev, 0.1*np.sqrt(10))
```

### Comparing `astropop-0.5.4/tests/test_polarimetry.py` & `astropop-0.9.0/tests/test_polarimetry.py`

 * *Files 27% similar despite different names*

```diff
@@ -1,18 +1,18 @@
 # Licensed under a 3-clause BSD style license - see LICENSE.rst
 # flake8: noqa: F403, F405
 
 import pytest
 import numpy as np
-from astropop.polarimetry.dualbeam import match_pairs, estimate_dxdy, \
-                                          _compute_theta, quarterwave_model, \
-                                          halfwave_model, \
-                                          _DualBeamPolarimetry, \
-                                          SLSDualBeamPolarimetry, \
-                                          StokesParameters
+from astropop.polarimetry import match_pairs, estimate_dxdy, \
+                                 _compute_theta, quarterwave_model, \
+                                 halfwave_model, \
+                                 _DualBeamPolarimetry, \
+                                 SLSDualBeamPolarimetry, \
+                                 StokesParameters
 from astropop.math import QFloat
 from astropy import units
 from astropop.testing import *
 from scipy.optimize import curve_fit
 from functools import partial
 
 
@@ -245,14 +245,21 @@
                            'together.'):
             DummyPolarimeter('halfwave', k=1.2, compute_k=True)
 
     def test_initialize_error_retarder(self):
         with pytest.raises(ValueError, match="Retarder dummy unknown."):
             DummyPolarimeter('dummy')
 
+    def test_initialize_zero_range(self):
+        pol = DummyPolarimeter('halfwave', zero_range=(0, 180))
+        assert_equal(pol.zero_range, (0, 180))
+
+        with pytest.raises(ValueError, match='a list with two elements.'):
+            DummyPolarimeter('halfwave', zero_range=[0])
+
     def test_initialize_zero_quantity(self):
         pol = DummyPolarimeter('halfwave', zero=60*units.degree)
         assert_equal(pol.zero, 60)
 
     def test_initialize_n_pos(self):
         pol = DummyPolarimeter('halfwave')
         assert_equal(pol._n_pos, 4)
@@ -314,122 +321,308 @@
                                      u=-0.021, zero=60)
         expect = halfwave_model(psi, q=0.0130, u=-0.021, zero=60)
         zi = pol._calc_zi(flux_o, flux_e, k=1.2)
         assert_almost_equal(zi, expect)
 
 
 class Test_StokesParameters:
+    def test_stokes_invalid_retarder(self):
+        with pytest.raises(ValueError, match='retarder must be'):
+            StokesParameters('thirdwave', 0, 1)
+
+    def test_stokes_invalid_angles(self):
+        with pytest.raises(ValueError,
+                           match='Psi and Zero have different units.'):
+            StokesParameters('halfwave', 0, 1,
+                             psi=np.arange(0, 360, 22.5)*units.deg,
+                             zero=60*units.rad)
+
     def test_initialize_halfwave(self):
         q = QFloat(0.0130, 0.001)
         u = QFloat(-0.021, 0.001)
 
         # V is not needed
         pol = StokesParameters(retarder='halfwave', q=q, u=u)
         assert_equal(pol.q, q)
         assert_equal(pol.u, u)
         assert_is_none(pol.v)
         assert_equal(pol.retarder, 'halfwave')
         assert_equal(pol.k, 1.0)
-        assert_equal(pol.zero, 0.0)
+        assert_equal(pol.zero, QFloat(0.0, unit='deg'))
 
     def test_initialize_halfwave_kzero(self):
         q = QFloat(0.0130, 0.001)
         u = QFloat(-0.021, 0.001)
         k = QFloat(1.2, 0.001)
-        zero = QFloat(60, 0.001)
+        zero = QFloat(60, 0.001, unit='deg')
 
         # V is not needed
         pol = StokesParameters(retarder='halfwave', q=q, u=u, k=k, zero=zero)
         assert_equal(pol.q, q)
         assert_equal(pol.u, u)
         assert_is_none(pol.v)
         assert_equal(pol.retarder, 'halfwave')
-        assert_equal(pol.k, k)
+        assert_equal(pol.k, k.nominal)
         assert_equal(pol.zero, zero)
 
     def test_initialize_quarterwave(self):
         q = QFloat(0.0130, 0.001)
         u = QFloat(-0.021, 0.001)
         v = QFloat(0.021, 0.001)
 
         # V is needed
         pol = StokesParameters(retarder='quarterwave', q=q, u=u, v=v)
         assert_equal(pol.q, q)
         assert_equal(pol.u, u)
         assert_equal(pol.v, v)
         assert_equal(pol.retarder, 'quarterwave')
         assert_equal(pol.k, 1.0)
-        assert_equal(pol.zero, 0.0)
+        assert_equal(pol.zero, QFloat(0.0, unit='deg'))
 
     def test_initialize_quarterwave_kzero(self):
         q = QFloat(0.0130, 0.001)
         u = QFloat(-0.021, 0.001)
         v = QFloat(0.021, 0.001)
         k = QFloat(1.2, 0.001)
-        zero = QFloat(60, 0.001)
+        zero = QFloat(60, 0.001, unit='deg')
 
         # V is needed
         pol = StokesParameters(retarder='quarterwave', q=q, u=u, v=v, k=k,
                                zero=zero)
         assert_equal(pol.q, q)
         assert_equal(pol.u, u)
         assert_equal(pol.v, v)
         assert_equal(pol.retarder, 'quarterwave')
-        assert_equal(pol.k, k)
+        assert_equal(pol.k, k.nominal)
         assert_equal(pol.zero, zero)
 
     def test_stokes_properties(self):
         q = QFloat(0.0130, 0.001)
         u = QFloat(-0.021, 0.001)
         v = QFloat(0.021, 0.001)
         pol = StokesParameters(retarder='quarterwave', q=q, u=u, v=v)
 
         assert_almost_equal(pol.p.nominal, 0.0246981, decimal=3)
         assert_almost_equal(pol.theta.nominal, 150.8797, decimal=3)
 
+    def test_stokes_rms(self):
+        q = QFloat(0.0130, 0.001)
+        u = QFloat(-0.021, 0.001)
+        v = QFloat(0.021, 0.001)
+        zero = 0
+        psi = np.arange(0, 360, 22.5)
+        zi = QFloat([0.01285947, -0.01919851, -0.02003721, 0.00249653,
+                     0.01413347, 0.0106049, 0.01869019, 0.03220446,
+                     0.01172209, -0.01887455, -0.01867554, 0.00309657,
+                     0.0109851, 0.01100691, 0.02298037, 0.03058262],
+                    uncertainty=[0.001]*16)
+        pol = StokesParameters(retarder='quarterwave', q=q, u=u, v=v,
+                               zero=zero, zi=zi, psi=psi)
+
+        assert_almost_equal(pol.rms, 0.00125, decimal=4)
+
+    def test_stokes_rms_no_zi_psi(self):
+        with pytest.raises(ValueError, match='without zi and psi data'):
+            p = StokesParameters('halfwave', 0, 1)
+            p.rms
+        with pytest.raises(ValueError, match='without zi and psi data'):
+            p = StokesParameters('halfwave', 0, 1, psi=[0]*16)
+            p.rms
+        with pytest.raises(ValueError, match='without zi and psi data'):
+            p = StokesParameters('halfwave', 0, 1, zi=[0]*16)
+            p.rms
+
+    def test_stokes_sigma_theor(self):
+        flux = QFloat([1]*16, [0.001]*16)
+
+        p = StokesParameters('halfwave', 0, 1, flux=flux)
+        # sqrt(2)*0.001/sqrt(16)
+        assert_almost_equal(p.theor_sigma['p'], np.sqrt(2)*0.00025)
+        assert_almost_equal(p.theor_sigma['q'], np.sqrt(2)*0.00025)
+        assert_almost_equal(p.theor_sigma['u'], np.sqrt(2)*0.00025)
+
+        p = StokesParameters('quarterwave', q=0.1, u=0.1, v=0.1, flux=flux)
+        assert_almost_equal(p.theor_sigma['q'], 0.0003972760)
+        assert_almost_equal(p.theor_sigma['u'], 0.0006533854)
+        assert_almost_equal(p.theor_sigma['v'], 0.0003697723)
+        assert_almost_equal(p.theor_sigma['p'], 0.0005407128)
+
+        flux = QFloat([1]*8, [0.001]*8)
+        p = StokesParameters('halfwave', 0, 1, flux=flux)
+        # 0.001/sqrt(8)
+        assert_almost_equal(p.theor_sigma['p'], np.sqrt(2)*0.001/np.sqrt(8))
+        assert_almost_equal(p.theor_sigma['q'], np.sqrt(2)*0.001/np.sqrt(8))
+        assert_almost_equal(p.theor_sigma['u'], np.sqrt(2)*0.001/np.sqrt(8))
+
+        p = StokesParameters('quarterwave', q=0.1, u=0.1, v=0.1, flux=flux)
+        assert_almost_equal(p.theor_sigma['q'], np.sqrt(2)*0.0003972760)
+        assert_almost_equal(p.theor_sigma['u'], np.sqrt(2)*0.0006533854)
+        assert_almost_equal(p.theor_sigma['v'], np.sqrt(2)*0.0003697723)
+        assert_almost_equal(p.theor_sigma['p'], np.sqrt(2)*0.0005407128)
+
+    def test_stokes_sigma_theor_no_flux(self):
+        p = StokesParameters('halfwave', 0, 1)
+        with pytest.raises(ValueError,
+                           match='theoretical sigma is only available when'):
+            p.theor_sigma
+
+    def test_stokes_model_halfwave(self):
+        p = StokesParameters('halfwave', 0, 0.1)
+        psi = np.arange(0, 360, 22.5)*units.degree
+        assert_almost_equal(p.model(psi).nominal, halfwave_model(psi, 0, 0.1))
+
+    def test_stokes_model_quarterwave(self):
+        p = StokesParameters('quarterwave', 0, 0.1, 0.05)
+        psi = np.arange(0, 360, 22.5)*units.degree
+        assert_almost_equal(p.model(psi), quarterwave_model(psi, 0, 0.1, 0.05))
+
+    def test_stokes_parameters_error_dimensions(self):
+        psi = np.arange(0, 360, 22.5)*units.degree
+        zi = quarterwave_model(psi, 0, 0.1, 0.05)
+        flux = [1e5]*len(psi)
+
+        p = StokesParameters('quarterwave', 0, 0.1, flux=flux, psi=psi, zi=zi)
+        p = StokesParameters('quarterwave', 0, 0.1, flux=flux, psi=psi)
+        p = StokesParameters('quarterwave', 0, 0.1, psi=psi, zi=zi)
+        p = StokesParameters('quarterwave', 0, 0.1, flux=flux, zi=zi)
+        p = StokesParameters('quarterwave', 0, 0.1, flux=flux)
+        p = StokesParameters('quarterwave', 0, 0.1, psi=psi)
+        p = StokesParameters('quarterwave', 0, 0.1, zi=zi)
+
+        with pytest.raises(ValueError, match='same dimensions'):
+            StokesParameters('quarterwave', 0, 0.1, flux=flux, psi=psi,
+                             zi=zi[:14])
+        with pytest.raises(ValueError, match='same dimensions'):
+            StokesParameters('quarterwave', 0, 0.1, flux=flux[:10], psi=psi,
+                             zi=zi)
+        with pytest.raises(ValueError, match='same dimensions'):
+            StokesParameters('quarterwave', 0, 0.1, flux=flux, psi=psi[:10],
+                             zi=zi)
+
+    def test_repr(self):
+        p = StokesParameters('halfwave', 0, 0.1)
+        i = id(p)
+        assert_equal(repr(p), "<astropop.polarimetry.StokesParameters object "
+                     f"at {hex(i)}>\nq=0.0+-0.0, u=0.1+-0.0")
+
+    def test_repr_with_v(self):
+        p = StokesParameters('quarterwave', 0, 0.1, 0.05)
+        i = id(p)
+        assert_equal(repr(p), "<astropop.polarimetry.StokesParameters object "
+                     f"at {hex(i)}>\nq=0.0+-0.0, u=0.1+-0.0, v=0.05+-0.0")
+
+    def test_str(self):
+        p = StokesParameters('halfwave', 0, 0.1)
+        assert_equal(str(p), "q=0.0+-0.0, u=0.1+-0.0")
+
+    def test_str_with_v(self):
+        p = StokesParameters('quarterwave', 0, 0.1, 0.05)
+        assert_equal(str(p), "q=0.0+-0.0, u=0.1+-0.0, v=0.05+-0.0")
+
 
 class Test_SLSPolarimetry:
     def test_fit_half(self):
         q = 0.0130
         u = -0.021
         psi = np.arange(0, 360, 22.5)
         flux_o, flux_e = get_flux_oe(1e5, psi, k=1.0, q=q, u=u, zero=0)
         pol = SLSDualBeamPolarimetry(retarder='halfwave', k=1.0)
         p = pol.compute(psi, flux_o, flux_e,
                         f_ord_error=[50]*16, f_ext_error=[50]*16)
         assert_almost_equal(p.q.nominal, q)
         assert_almost_equal(p.u.nominal, u)
+        for i in (p.q, p.u):
+            assert_equal(i.unit, units.dimensionless_unscaled)
         assert_almost_equal(p.k, 1.0)
         assert_is_none(p.zero)
 
+        assert_almost_equal(p.psi.nominal, psi)
+        assert_equal(p.psi.unit, units.degree)
+        assert_almost_equal(p.zi.nominal, (flux_o-flux_e)/(flux_o+flux_e))
+        assert_equal(p.zi.unit, units.dimensionless_unscaled)
+        assert_almost_equal(p.flux.nominal, [1e5]*len(psi))
+
     def test_fit_half_no_errors(self):
         q = 0.0130
         u = -0.021
         psi = np.arange(0, 360, 22.5)
         flux_o, flux_e = get_flux_oe(1e5, psi, k=1.0, q=q, u=u, zero=0)
+        zi = (flux_o-flux_e)/(flux_o+flux_e)
         pol = SLSDualBeamPolarimetry(retarder='halfwave', k=1.0)
         p = pol.compute(psi, flux_o, flux_e)
         assert_almost_equal(p.q.nominal, q)
         assert_almost_equal(p.u.nominal, u)
+        for i in (p.q, p.u):
+            assert_equal(i.unit, units.dimensionless_unscaled)
         assert_almost_equal(p.k, 1.0)
         assert_is_none(p.zero)
 
+        assert_almost_equal(p.psi.nominal, psi)
+        assert_equal(p.psi.unit, units.degree)
+        assert_almost_equal(p.zi.nominal, (flux_o-flux_e)/(flux_o+flux_e))
+        assert_equal(p.zi.unit, units.dimensionless_unscaled)
+
     def test_fit_half_estimate_k(self):
         q = 0.0130
         u = -0.021
         psi = np.arange(0, 360, 22.5)
-        flux_o, flux_e = get_flux_oe(1e5, psi, k=1.2, q=q, u=u, zero=0)
+        k = 1.2
+        flux_o, flux_e = get_flux_oe(1e5, psi, k=k, q=q, u=u, zero=0)
+        zi = (flux_o-flux_e*k)/(flux_o+flux_e*k)
         pol = SLSDualBeamPolarimetry(retarder='halfwave', compute_k=True)
         p = pol.compute(psi, flux_o, flux_e,
                         f_ord_error=[50]*16, f_ext_error=[50]*16)
         assert_almost_equal(p.q.nominal, q)
         assert_almost_equal(p.u.nominal, u)
-        assert_almost_equal(p.k.nominal, 1.2)
+        for i in (p.q, p.u):
+            assert_equal(i.unit, units.dimensionless_unscaled)
+        assert_almost_equal(p.k, k)
         assert_is_none(p.zero)
 
+        assert_almost_equal(p.psi.nominal, psi)
+        assert_equal(p.psi.unit, units.degree)
+        assert_almost_equal(p.zi.nominal, zi)
+        assert_equal(p.zi.unit, units.dimensionless_unscaled)
+
+    def test_fit_half_no_k(self):
+        q = 0.02
+        u = 0.01
+        psi = np.arange(0, 360, 22.5)
+        flux_o, flux_e = get_flux_oe(1e5, psi, k=1, q=q, u=u, zero=0)
+        zi = (flux_o-flux_e)/(flux_o+flux_e)
+        pol = SLSDualBeamPolarimetry(retarder='halfwave', compute_k=False)
+        p = pol.compute(psi, flux_o, flux_e,
+                        f_ord_error=[50]*16, f_ext_error=[50]*16)
+        # k must default to 1
+        assert_almost_equal(p.q.nominal, q)
+        assert_almost_equal(p.u.nominal, u)
+        for i in (p.q, p.u):
+            assert_equal(i.unit, units.dimensionless_unscaled)
+        assert_almost_equal(p.k, 1.0)
+        assert_is_none(p.zero)
+
+    def test_fit_half_zero(self):
+        q = 0.02
+        u = 0.01
+        psi = np.arange(0, 360, 22.5)
+        zero = 60
+        flux_o, flux_e = get_flux_oe(1e5, psi, k=1, q=q, u=u, zero=60)
+        zi = (flux_o-flux_e)/(flux_o+flux_e)
+        pol = SLSDualBeamPolarimetry(retarder='halfwave', compute_k=True,
+                                     zero=60)
+        p = pol.compute(psi, flux_o, flux_e,
+                        f_ord_error=[50]*16, f_ext_error=[50]*16)
+        # k must default to 1
+        assert_almost_equal(p.q.nominal, q)
+        assert_almost_equal(p.u.nominal, u)
+        for i in (p.q, p.u):
+            assert_equal(i.unit, units.dimensionless_unscaled)
+        assert_almost_equal(p.k, 1.0)
+        assert_equal(p.zero, QFloat(60, 0, 'degree'))
+
     def test_fit_quarter(self):
         q = 0.0130
         u = -0.027
         v = 0.021
         zero = 60
 
         psi = np.arange(0, 360, 22.5)
@@ -438,16 +631,25 @@
                                      compute_k=True)
         p = pol.compute(psi, flux_o, flux_e,
                         f_ord_error=[50]*16, f_ext_error=[50]*16)
 
         assert_almost_equal(p.q.nominal, q)
         assert_almost_equal(p.u.nominal, u)
         assert_almost_equal(p.v.nominal, v)
-        assert_almost_equal(p.k.nominal, 1.0, decimal=2)
-        assert_almost_equal(p.zero, zero)
+        for i in (p.q, p.u, p.v):
+            assert_equal(i.unit, units.dimensionless_unscaled)
+        assert_almost_equal(p.k, 1.0, decimal=2)
+        assert_almost_equal(p.zero.nominal, zero)
+        assert_equal(p.zero.unit, units.degree)
+
+        assert_almost_equal(p.psi.nominal, psi)
+        assert_equal(p.psi.unit, units.degree)
+        assert_almost_equal(p.zi.nominal, (flux_o-flux_e)/(flux_o+flux_e))
+        assert_equal(p.zi.unit, units.dimensionless_unscaled)
+        assert_almost_equal(p.flux.nominal, [1e5]*len(psi))
 
     def test_fit_quarter_no_errors(self):
         q = 0.0130
         u = -0.027
         v = 0.021
         zero = 60
 
@@ -456,35 +658,74 @@
         pol = SLSDualBeamPolarimetry(retarder='quarterwave', zero=60,
                                      compute_k=True)
         p = pol.compute(psi, flux_o, flux_e)
 
         assert_almost_equal(p.q.nominal, q)
         assert_almost_equal(p.u.nominal, u)
         assert_almost_equal(p.v.nominal, v)
-        assert_almost_equal(p.k.nominal, 1.0, decimal=2)
-        assert_almost_equal(p.zero, zero)
+        for i in (p.q, p.u, p.v):
+            assert_equal(i.unit, units.dimensionless_unscaled)
+        assert_almost_equal(p.k, 1.0, decimal=2)
+        assert_almost_equal(p.zero.nominal, zero)
+        assert_equal(p.zero.unit, units.degree)
+
+        assert_almost_equal(p.psi.nominal, psi)
+        assert_equal(p.psi.unit, units.degree)
+        assert_almost_equal(p.zi.nominal, (flux_o-flux_e)/(flux_o+flux_e))
+        assert_equal(p.zi.unit, units.dimensionless_unscaled)
 
     @pytest.mark.parametrize('k', [0.99, 1.01, 1.03, 0.97])
     def test_fit_quarter_estimate_k(self, k):
         q = 0.130
         u = -0.027
         v = 0.021
         zero = 60
 
         psi = np.arange(0, 360, 22.5)
         flux_o, flux_e = get_flux_oe(1e5, psi, k=k, q=q, u=u, v=v, zero=zero)
         pol = SLSDualBeamPolarimetry(retarder='quarterwave', zero=60,
                                      compute_k=True)
+        zi = (flux_o-flux_e*k)/(flux_o+flux_e*k)
         p = pol.compute(psi, flux_o, flux_e)
 
         assert_almost_equal(p.q.nominal, q, decimal=3)
         assert_almost_equal(p.u.nominal, u, decimal=3)
         assert_almost_equal(p.v.nominal, v, decimal=3)
-        assert_almost_equal(p.k.nominal, k, decimal=2)
-        assert_almost_equal(p.zero, zero, decimal=3)
+        for i in (p.q, p.u, p.v):
+            assert_equal(i.unit, units.dimensionless_unscaled)
+        assert_almost_equal(p.k, k, decimal=2)
+        assert_almost_equal(p.zero.nominal, zero, decimal=3)
+        assert_equal(p.zero.unit, units.degree)
+
+        assert_almost_equal(p.psi.nominal, psi)
+        assert_equal(p.psi.unit, units.degree)
+        assert_almost_equal(p.zi.nominal, zi, decimal=4)
+        assert_equal(p.zi.unit, units.dimensionless_unscaled)
+
+    def test_fit_quarter_no_k(self):
+        q = 0.0130
+        u = -0.027
+        v = 0.021
+        zero = 60
+
+        psi = np.arange(0, 360, 22.5)
+        flux_o, flux_e = get_flux_oe(1e5, psi, k=1.0, q=q, u=u, v=v, zero=zero)
+        pol = SLSDualBeamPolarimetry(retarder='quarterwave', zero=60,
+                                     compute_k=False)
+        p = pol.compute(psi, flux_o, flux_e,
+                        f_ord_error=[50]*16, f_ext_error=[50]*16)
+
+        assert_almost_equal(p.q.nominal, q)
+        assert_almost_equal(p.u.nominal, u)
+        assert_almost_equal(p.v.nominal, v)
+        for i in (p.q, p.u, p.v):
+            assert_equal(i.unit, units.dimensionless_unscaled)
+        assert_almost_equal(p.k, 1.0)
+        assert_almost_equal(p.zero.nominal, zero)
+        assert_equal(p.zero.unit, units.degree)
 
     def test_fit_quarter_estimate_zero(self):
         q = 0.130
         u = -0.027
         v = 0.021
         zero = 60
 
@@ -492,9 +733,29 @@
         flux_o, flux_e = get_flux_oe(1e5, psi, k=1.0, q=q, u=u, v=v, zero=zero)
         pol = SLSDualBeamPolarimetry(retarder='quarterwave', compute_k=True)
         p = pol.compute(psi, flux_o, flux_e)
 
         assert_almost_equal(p.q.nominal, q, decimal=3)
         assert_almost_equal(p.u.nominal, u, decimal=3)
         assert_almost_equal(p.v.nominal, v, decimal=3)
-        assert_almost_equal(p.k.nominal, 1.0, decimal=2)
+        for i in (p.q, p.u, p.v):
+            assert_equal(i.unit, units.dimensionless_unscaled)
+        assert_almost_equal(p.k, 1.0, decimal=2)
         assert_almost_equal(p.zero.nominal, zero, decimal=3)
+        assert_equal(p.zero.unit, units.degree)
+
+        assert_almost_equal(p.psi.nominal, psi)
+        assert_equal(p.psi.unit, units.degree)
+        assert_almost_equal(p.zi.nominal, (flux_o-flux_e)/(flux_o+flux_e))
+        assert_equal(p.zi.unit, units.dimensionless_unscaled)
+
+    def test_fit_quarter_no_converge(self):
+        q = 0.02
+        u = 0.0
+        v = 0.0
+        zero = 60
+        psi = np.arange(0, 360, 22.5)
+        flux_o, flux_e = get_flux_oe(1e5, psi, k=1.0, q=q, u=u, v=v, zero=zero)
+        pol = SLSDualBeamPolarimetry(retarder='quarterwave', compute_k=True,
+                                     zero=None, max_iters=1)
+        with pytest.raises(RuntimeError, match='Could not converge after'):
+            p = pol.compute(psi, flux_o, flux_e)
```

### Comparing `astropop-0.5.4/tests/test_pyutils.py` & `astropop-0.9.0/tests/test_pyutils.py`

 * *Files 3% similar despite different names*

```diff
@@ -19,16 +19,16 @@
                                     ('2.5', False),
                                     (1+3j, False),
                                     (5j, False),
                                     ('A', False),
                                     ('AB', False),
                                     ([1, 2, 3], False),
                                     (np.array([1, 2]), False),
-                                    (np.int('3'), True),
-                                    (np.float(3), True),
+                                    (np.int_('3'), True),
+                                    (np.float_(3), True),
                                     (False, False),
                                     ((1, 2, 3), False)])
 def test_check_number(v, exp):
     if exp:
         assert_true(check_number(v))
     else:
         assert_false(check_number(v))
@@ -49,14 +49,27 @@
 
 class Test_RunCommand():
     com = (["bash", "-c", 'for i in {1..10}; do echo "$i"; sleep 0.1; done'],
            "bash -c 'for i in {1..10}; do echo \"$i\"; sleep 0.1; done'")
     com2 = ("bash -c 'echo \"this is an error\" 1>&2'",
             ["bash", "-c", 'echo "this is an error" 1>&2'])
 
+    # This test break all the others
+    # def test_nested_async(self):
+    #     import asyncio
+    #     async def async_func():
+    #         run_command(['ls', '/'])
+
+    #     asyncio.run(async_func())
+
+    def test_process_error(self):
+        import subprocess
+        with pytest.raises(subprocess.CalledProcessError):
+            run_command('python -c "import sys; sys.exit(1000)"')
+
     @pytest.mark.parametrize('com', com)
     def test_run_command(self, com):
         stdout = []
         stderr = []
         _, out, err = run_command(com, stdout=stdout, stderr=stderr,
                                   stdout_loglevel='WARN')
         assert_is(out, stdout)
@@ -243,14 +256,15 @@
         assert_equal(bc.iters, [[1], [2], [3]])
 
     def test_broadcast_iters(self):
         bc = broadcast(np.arange(10), 3, 2)
 
         assert_equal(bc.iters, [np.arange(10), [3]*10, [2]*10])
 
+
 class Test_IndexedDict():
     def test_indexeddict_create(self):
         d = dict(a=1, b=2, c=3)
         i = IndexedDict(a=1, b=2, c=3)
         assert_is_instance(i, dict)
         assert_equal(len(d), len(i))
         # Python 3.6 and above ensure items order
```

### Comparing `astropop-0.5.4/tests/test_register.py` & `astropop-0.9.0/tests/test_register.py`

 * *Files 3% similar despite different names*

```diff
@@ -3,15 +3,15 @@
 
 import pytest
 import numpy as np
 from astropop.image.register import AsterismRegister, \
                                     CrossCorrelationRegister, \
                                     register_framedata_list, \
                                     compute_shift_list
-from astropop.framedata import FrameData
+from astropop.framedata import FrameData, PixelMaskFlags
 from astropop.testing import *
 
 from .test_detection import gen_position_flux, gen_image
 
 
 def gen_positions_transformed(x, y, flux, dx, dy, limits,
                               rotation=None, rotation_center=None):
@@ -192,22 +192,31 @@
         expect[0, :] = fill
         expect[:, -2:] = fill
 
         mask = np.zeros_like(im2, dtype=bool)
         mask[0, :] = 1
         mask[:, -2:] = 1
 
+        flags = np.zeros_like(im2, dtype='u1')
+        flags[5, 5] = 5
+        exp_flags = np.zeros_like(im2, dtype='u1')
+        exp_flags[3, 6] = 5
+        exp_flags[0, :] = (PixelMaskFlags.REMOVED |
+                           PixelMaskFlags.OUT_OF_BOUNDS).value
+        exp_flags[:, -2:] = (PixelMaskFlags.REMOVED |
+                             PixelMaskFlags.OUT_OF_BOUNDS).value
+
         expect_unct = np.ones_like(im2, dtype='f8')
         expect_unct[0, :] = np.nan
         expect_unct[:, -2:] = np.nan
 
-        frame1 = FrameData(im1, dtype='f8')
+        frame1 = FrameData(im1, dtype='f8', flags=flags)
         frame1.meta['moving'] = False
         frame1.uncertainty = np.ones_like(im1)
-        frame2 = FrameData(im2, dtype='f8')
+        frame2 = FrameData(im2, dtype='f8', flags=flags)
         frame2.meta['moving'] = True
         frame2.uncertainty = np.ones_like(im2)
 
         ar = CrossCorrelationRegister()
         frame_reg = ar.register_framedata(frame1, frame2,
                                           cval=cval, inplace=inplace)
 
@@ -234,22 +243,26 @@
         assert_equal(mask_reg, np.zeros_like(im))
         assert_equal(tform.translation, [0, 0])
 
     @pytest.mark.parametrize('inplace', [True, False])
     def test_register_frame_equal(self, inplace):
         im = gen_image((50, 50), [25], [25], [10000], 10, 0, sigma=3)
         im = FrameData(im)
+        flags = np.zeros((50, 50), dtype=np.uint8)
+        flags[25, 25] = 5
+        im.flags = flags
         ar = CrossCorrelationRegister()
         im_reg = ar.register_framedata(im, im, inplace=inplace)
         if inplace:
             assert_is(im_reg, im)
         else:
             assert_is_not(im_reg, im)
         assert_equal(im_reg.data, im.data)
         assert_equal(im_reg.mask, np.zeros_like(im))
+        assert_equal(im_reg.flags, flags)
         assert_equal(im_reg.meta['astropop registration_shift_x'], 0)
         assert_equal(im_reg.meta['astropop registration_shift_y'], 0)
 
 
 class Test_Register_FrameData_List:
     _shifts = [(0, 0), (-1, 22.4), (15.5, 3.2), (2.2, -1.75), (-5.4, 0.5)]
 
@@ -270,18 +283,18 @@
                                          'test expect_shift_y': shift[1]})
             frame_list.append(frame)
 
         return frame_list
 
     def test_error_unkown_algorithm(self):
         with pytest.raises(ValueError, match='Algorithm noexisting unknown.'):
-            register_framedata_list([FrameData(None) for i in range(10)],
+            register_framedata_list([FrameData([[1]]) for i in range(10)],
                                     algorithm='noexisting')
         with pytest.raises(ValueError, match='Algorithm noexisting unknown.'):
-            compute_shift_list([FrameData(None) for i in range(10)],
+            compute_shift_list([FrameData([[1]]) for i in range(10)],
                                algorithm='noexisting')
 
     def test_error_non_framedata(self):
         with pytest.raises(TypeError, match='Only a list of FrameData'):
             register_framedata_list([np.zeros((10, 10)) for i in range(10)])
         with pytest.raises(TypeError, match='Only a list of FrameData'):
             compute_shift_list([np.zeros((10, 10)) for i in range(10)])
@@ -397,29 +410,29 @@
             assert_false(np.any(reg.mask))
 
     def test_register_framedata_list_skip_failure_default(self):
         # defult behavior is raise error
         frame_list = self.gen_frame_list((512, 1024))
         frame_list[2].data = np.ones((1024, 512))
 
-        with pytest.raises(TypeError):
+        with pytest.raises(ValueError):
             register_framedata_list(frame_list, algorithm='asterism-matching')
 
-        with pytest.raises(TypeError):
+        with pytest.raises(ValueError):
             compute_shift_list(frame_list, algorithm='asterism-matching')
 
     def test_register_framedata_list_skip_failure_false(self):
         frame_list = self.gen_frame_list((512, 1024))
         frame_list[2].data = np.ones((1024, 512))
 
-        with pytest.raises(TypeError):
+        with pytest.raises(ValueError):
             register_framedata_list(frame_list, algorithm='asterism-matching',
                                     skip_failure=False)
 
-        with pytest.raises(TypeError):
+        with pytest.raises(ValueError):
             compute_shift_list(frame_list, algorithm='asterism-matching',
                                skip_failure=False)
 
     @pytest.mark.parametrize('cval,expct_cval', [(np.nan, np.nan),
                                                  ('median', 1),
                                                  ('mean', 1),
                                                  (0, 0)])
```

### Comparing `astropop-0.5.4/tests/test_testing.py` & `astropop-0.9.0/tests/test_testing.py`

 * *Files identical despite different names*

### Comparing `astropop-0.5.4/tests/test_unit_property.py` & `astropop-0.9.0/tests/test_unit_property.py`

 * *Files identical despite different names*

### Comparing `astropop-0.5.4/tox.ini` & `astropop-0.9.0/tox.ini`

 * *Files 16% similar despite different names*

```diff
@@ -1,85 +1,69 @@
 [tox]
 envlist =
-    py{37,38,39,310}-test{,-alldeps,-devdeps,-olddeps,-ltsdps,-stabledeps}{,-cov}{,-cat}
+    py{38,39,310,311}-test{,-alldeps,-devdeps,-olddeps,-ltsdps,-stabledeps}{,-cov}{,-online}
     build_docs
-    linkcheck
-    codestyle
 requires =
     setuptools >= 30.3.0
     pip >= 19.3.1
-    tox-pypi-filter >= 0.12
 isolated_build = true
 
 [testenv]
 setenv =
     MPLBACKEND=agg
-    cat: ASTROPOP_TEST_CATALOGS=1
+    PYTEST_ARGS = ''
+    online: PYTEST_ARGS = --remote-data=any
 
-passenv = HOME WINDIR LC_ALL LC_CTYPE CC CI TRAVIS
+passenv = HOME,WINDIR,LC_ALL,LC_CTYPE,CC,CI,TRAVIS
 
 changedir = .tmp/{envname}
 
 description =
     run tests
     alldeps: with all optional dependencies
     devdeps: with the latest developer version of key dependencies
     olddeps: with the oldest supported version of key dependencies
     ltsdeps: with the LTS version of key dependencies
     stabledeps: with the latest stable version of key dependencies
     cov: and test coverage
-    astropystable: with the latest stable astropy
 
 deps =
     stabledeps: astropy
     stabledeps: numpy  # keep it free
 
-    olddeps: astropy==4.3.*
-    olddeps: numpy==1.17.*
+    olddeps: astropy==5.0.*
+    olddeps: numpy==1.18.*
     olddeps: scipy==1.6.*
+    olddeps: photutils==1.4.*
 
     ltsdeps: astropy==5.0.*
     ltsdeps: numpy==1.21.*
     ltsdeps: scipy==1.7.*
+    ltsdeps: photutils==1.6.*
 
     build_docs: matplotlib
-    
+
     devdeps: git+https://github.com/astropy/astroscrappy.git#egg=astroscrappy
-    devdeps: git+https://github.com/kbarbary/sep.git#egg=sep
     devdeps: git+https://github.com/astropy/astroquery.git#egg=astroquery
+    devdeps: git+https://github.com/astropy/photutils.git#egg=photutils
 
 extras =
     test
     alldeps: all
 
 commands =
     devdeps: pip install -U --pre --only-binary :all: -i https://pypi.anaconda.org/scipy-wheels-nightly/simple numpy
     devdeps: pip install -U --pre --only-binary :all: -i https://pypi.anaconda.org/scipy-wheels-nightly/simple scipy
     devdeps: pip install -U --pre --only-binary :all: -i https://pypi.anaconda.org/scipy-wheels-nightly/simple scikit-image
     devdeps: pip install -U --pre --only-binary :all: -i https://pypi.anaconda.org/scipy-wheels-nightly/simple scikit-learn
     devdeps: pip install -U --pre --only-binary :all: -i https://pypi.anaconda.org/astropy/simple astropy
     pip freeze
-    !cov: pytest --pyargs {toxinidir}/tests {toxinidir}/docs --remote-data {posargs}
-    cov: pytest --pyargs {toxinidir}/tests {toxinidir}/docs --remote-data --cov astropop --cov-config={toxinidir}/setup.cfg {posargs}
+    !cov: pytest --pyargs {toxinidir}/tests {toxinidir}/docs {env:PYTEST_ARGS} {posargs}
+    cov: pytest --pyargs {toxinidir}/tests {toxinidir}/docs {env:PYTEST_ARGS} --cov astropop --cov-config={toxinidir}/setup.cfg {posargs}
 
 [testenv:build_docs]
 changedir = docs
 description = invoke sphinx-build to build the HTML docs
 extras = docs
 commands =
     pip freeze
     sphinx-build -b html . _build/html
-
-[testenv:linkcheck]
-changedir = docs
-description = check the links in the HTML docs
-extras = docs
-commands =
-    pip freeze
-    sphinx-build -W -b linkcheck . _build/html
-
-[testenv:codestyle]
-skip_install = true
-changedir = .
-description = check code style, e.g. with flake8
-deps = flake8
-commands = flake8 astropop --count --max-line-length=100
```


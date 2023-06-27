# Comparing `tmp/dune-iga-0.1.8.dev20230618204354.tar.gz` & `tmp/dune-iga-0.1.8.dev20230627230825.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dune-iga-0.1.8.dev20230618204354.tar", last modified: Sun Jun 18 20:43:55 2023, max compression
+gzip compressed data, was "dune-iga-0.1.8.dev20230627230825.tar", last modified: Tue Jun 27 23:08:26 2023, max compression
```

## Comparing `dune-iga-0.1.8.dev20230618204354.tar` & `dune-iga-0.1.8.dev20230627230825.tar`

### file list

```diff
@@ -1,151 +1,151 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-18 20:43:55.581983 dune-iga-0.1.8.dev20230618204354/
--rw-r--r--   0 root         (0) root         (0)     1025 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/.clang-format
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-18 20:43:55.553983 dune-iga-0.1.8.dev20230618204354/.github/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-18 20:43:55.561983 dune-iga-0.1.8.dev20230618204354/.github/workflows/
--rw-r--r--   0 root         (0) root         (0)      435 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/.github/workflows/codespell.yml
--rw-r--r--   0 root         (0) root         (0)     1384 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/.github/workflows/createRelease.yml
--rw-r--r--   0 root         (0) root         (0)     1758 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/.github/workflows/debian-coverage.yml
--rw-r--r--   0 root         (0) root         (0)     2245 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/.github/workflows/debian.yml
--rw-r--r--   0 root         (0) root         (0)     1728 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/.github/workflows/releasePythonPackage.yml
--rw-r--r--   0 root         (0) root         (0)      317 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/.github/workflows/reuseLint.yml
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-18 20:43:55.561983 dune-iga-0.1.8.dev20230618204354/.github/workflows/scripts/
--rw-r--r--   0 root         (0) root         (0)     3200 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/.github/workflows/scripts/release.py
--rw-r--r--   0 root         (0) root         (0)     1152 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/.github/workflows/style.yml
--rw-r--r--   0 root         (0) root         (0)      226 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/.gitignore
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-18 20:43:55.561983 dune-iga-0.1.8.dev20230618204354/.reuse/
--rw-r--r--   0 root         (0) root         (0)      507 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/.reuse/dep5
--rw-r--r--   0 root         (0) root         (0)      239 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/CHANGELOG.md
--rw-r--r--   0 root         (0) root         (0)     1332 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/CMakeLists.txt
--rw-r--r--   0 root         (0) root         (0)      251 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/LICENSE.md
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-18 20:43:55.561983 dune-iga-0.1.8.dev20230618204354/LICENSES/
--rw-r--r--   0 root         (0) root         (0)     7048 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/LICENSES/CC0-1.0.txt
--rw-r--r--   0 root         (0) root         (0)    42098 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/LICENSES/LGPL-3.0-or-later.txt
--rw-r--r--   0 root         (0) root         (0)     3129 2023-06-18 20:43:55.581983 dune-iga-0.1.8.dev20230618204354/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)     2718 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/README.md
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-18 20:43:55.561983 dune-iga-0.1.8.dev20230618204354/cmake/
--rw-r--r--   0 root         (0) root         (0)      186 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/cmake/CMakeLists.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-18 20:43:55.561983 dune-iga-0.1.8.dev20230618204354/cmake/FormatTarget/
--rw-r--r--   0 root         (0) root         (0)     1052 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/cmake/FormatTarget/CMakeLists.txt
--rw-r--r--   0 root         (0) root         (0)      989 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/cmake/FormatTarget/CPM.cmake
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-18 20:43:55.565983 dune-iga-0.1.8.dev20230618204354/cmake/modules/
--rw-r--r--   0 root         (0) root         (0)      753 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/cmake/modules/AddAutoDiffFlags.cmake
--rw-r--r--   0 root         (0) root         (0)      843 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/cmake/modules/AddClipperLibFlags.cmake
--rw-r--r--   0 root         (0) root         (0)      826 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/cmake/modules/AddEarCutFlags.cmake
--rw-r--r--   0 root         (0) root         (0)      715 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/cmake/modules/AddEigenFlags.cmake
--rw-r--r--   0 root         (0) root         (0)      824 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/cmake/modules/AddnLohmannJsonFlags.cmake
--rw-r--r--   0 root         (0) root         (0)      226 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/cmake/modules/CMakeLists.txt
--rw-r--r--   0 root         (0) root         (0)      450 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/cmake/modules/DuneIgaMacros.cmake
--rw-r--r--   0 root         (0) root         (0)      158 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/codespellignore
--rw-r--r--   0 root         (0) root         (0)     1421 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/config.h.cmake
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-18 20:43:55.565983 dune-iga-0.1.8.dev20230618204354/dune/
--rw-r--r--   0 root         (0) root         (0)      219 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/CMakeLists.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-18 20:43:55.565983 dune-iga-0.1.8.dev20230618204354/dune/iga/
--rw-r--r--   0 root         (0) root         (0)      808 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/CMakeLists.txt
--rw-r--r--   0 root         (0) root         (0)     9152 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/bsplinealgorithms.hh
--rw-r--r--   0 root         (0) root         (0)     2017 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/controlpoint.hh
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-18 20:43:55.569983 dune-iga-0.1.8.dev20230618204354/dune/iga/geometry/
--rw-r--r--   0 root         (0) root         (0)      268 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/geometry/CMakeLists.txt
--rw-r--r--   0 root         (0) root         (0)     6122 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/geometry/closestpointprojection.hh
--rw-r--r--   0 root         (0) root         (0)     2825 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/geometry/geohelper.hh
--rw-r--r--   0 root         (0) root         (0)     2785 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/gridcapabilities.hh
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-18 20:43:55.569983 dune-iga-0.1.8.dev20230618204354/dune/iga/io/
--rw-r--r--   0 root         (0) root         (0)      267 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/io/CMakeLists.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-18 20:43:55.569983 dune-iga-0.1.8.dev20230618204354/dune/iga/io/ibra/
--rw-r--r--   0 root         (0) root         (0)      258 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/io/ibra/CMakeLists.txt
--rw-r--r--   0 root         (0) root         (0)    10369 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/io/ibra/ibrageometry.hh
--rw-r--r--   0 root         (0) root         (0)     7806 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/io/ibra/ibrareader.hh
--rw-r--r--   0 root         (0) root         (0)     8239 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/io/igadatacollector.hh
--rw-r--r--   0 root         (0) root         (0)    30655 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/nurbsalgorithms.hh
--rw-r--r--   0 root         (0) root         (0)    29306 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/nurbsbasis.hh
--rw-r--r--   0 root         (0) root         (0)    18305 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/nurbsgeometry.hh
--rw-r--r--   0 root         (0) root         (0)    11629 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/nurbsgrid.hh
--rw-r--r--   0 root         (0) root         (0)    13111 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/nurbsgridentity.hh
--rw-r--r--   0 root         (0) root         (0)     3063 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/nurbsgridindexsets.hh
--rw-r--r--   0 root         (0) root         (0)     3957 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/nurbsgridleafiterator.hh
--rw-r--r--   0 root         (0) root         (0)     5805 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/nurbsgridtraits.hh
--rw-r--r--   0 root         (0) root         (0)     1285 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/nurbsidset.hh
--rw-r--r--   0 root         (0) root         (0)     7979 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/nurbsintersection.hh
--rw-r--r--   0 root         (0) root         (0)     9302 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/nurbsleafgridview.hh
--rw-r--r--   0 root         (0) root         (0)     9447 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/nurbslocalgeometry.hh
--rw-r--r--   0 root         (0) root         (0)    36685 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/nurbspatch.hh
--rw-r--r--   0 root         (0) root         (0)     1454 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/nurbspatchdata.hh
--rw-r--r--   0 root         (0) root         (0)     9061 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/nurbspatchgeometry.h
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-18 20:43:55.569983 dune-iga-0.1.8.dev20230618204354/dune/iga/test/
--rw-r--r--   0 root         (0) root         (0)     1347 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/test/CMakeLists.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-18 20:43:55.573983 dune-iga-0.1.8.dev20230618204354/dune/iga/test/auxiliaryFiles/
--rw-r--r--   0 root         (0) root         (0)     5772 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/test/auxiliaryFiles/element.ibra
--rw-r--r--   0 root         (0) root         (0)     7222 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/test/auxiliaryFiles/element_trim.ibra
--rw-r--r--   0 root         (0) root         (0)     7396 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/test/auxiliaryFiles/element_trim_xb.ibra
--rw-r--r--   0 root         (0) root         (0)     7665 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/test/auxiliaryFiles/infty_pwh.ibra
--rw-r--r--   0 root         (0) root         (0)     6209 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/test/auxiliaryFiles/nurbs_1.ibra
--rw-r--r--   0 root         (0) root         (0)     6704 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/test/auxiliaryFiles/pipe_trim.ibra
--rw-r--r--   0 root         (0) root         (0)     7048 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/test/auxiliaryFiles/plate_quarter.ibra
--rw-r--r--   0 root         (0) root         (0)    10170 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/test/auxiliaryFiles/schale_trim.ibra
--rw-r--r--   0 root         (0) root         (0)    12176 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/test/auxiliaryFiles/shell-hole.ibra
--rw-r--r--   0 root         (0) root         (0)     7146 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/test/auxiliaryFiles/shell.ibra
--rw-r--r--   0 root         (0) root         (0)     7688 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/test/auxiliaryFiles/surface-hole.ibra
--rw-r--r--   0 root         (0) root         (0)    60433 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/test/auxiliaryFiles/surface-multihole.ibra
--rw-r--r--   0 root         (0) root         (0)    45902 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/test/gridTests.cc
--rw-r--r--   0 root         (0) root         (0)    17532 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/test/trimmedGridTests.cc
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-18 20:43:55.573983 dune-iga-0.1.8.dev20230618204354/dune/iga/trim/
--rw-r--r--   0 root         (0) root         (0)      308 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/trim/CMakeLists.txt
--rw-r--r--   0 root         (0) root         (0)     4636 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/trim/nurbstrimboundary.hh
--rw-r--r--   0 root         (0) root         (0)    37350 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/trim/nurbstrimmer.hh
--rw-r--r--   0 root         (0) root         (0)    14597 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/trim/trimmedelementrepresentation.hh
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-18 20:43:55.573983 dune-iga-0.1.8.dev20230618204354/dune/iga/utils/
--rw-r--r--   0 root         (0) root         (0)      328 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/utils/CMakeLists.txt
--rw-r--r--   0 root         (0) root         (0)     2224 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/utils/concepts.hh
--rw-r--r--   0 root         (0) root         (0)     1782 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/utils/fillquadraturerule.hh
--rw-r--r--   0 root         (0) root         (0)     2372 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/utils/igahelpers.hh
--rw-r--r--   0 root         (0) root         (0)      716 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/utils/linearalgebra.hh
--rw-r--r--   0 root         (0) root         (0)    22274 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/utils/mdnet.hh
--rw-r--r--   0 root         (0) root         (0)      402 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/iga/utils/typetraits.hh
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-18 20:43:55.573983 dune-iga-0.1.8.dev20230618204354/dune/python/
--rw-r--r--   0 root         (0) root         (0)      175 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/python/CMakeLists.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-18 20:43:55.573983 dune-iga-0.1.8.dev20230618204354/dune/python/iga/
--rw-r--r--   0 root         (0) root         (0)      290 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/python/iga/CMakeLists.txt
--rw-r--r--   0 root         (0) root         (0)     1538 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/python/iga/boundarypatch.hh
--rw-r--r--   0 root         (0) root         (0)     6540 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/python/iga/grid.hh
--rw-r--r--   0 root         (0) root         (0)      248 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/python/iga/gridenums.hh
--rw-r--r--   0 root         (0) root         (0)     5102 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/python/iga/nurbspatchdata.hh
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-18 20:43:55.573983 dune-iga-0.1.8.dev20230618204354/dune/python/test/
--rw-r--r--   0 root         (0) root         (0)      461 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/python/test/CMakeLists.txt
--rw-r--r--   0 root         (0) root         (0)     5136 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/python/test/poisson.py
--rw-r--r--   0 root         (0) root         (0)     5501 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/python/test/readGrid.py
--rw-r--r--   0 root         (0) root         (0)      853 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune/python/test/setpath.py.in
--rw-r--r--   0 root         (0) root         (0)      431 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune-iga.pc.in
--rw-r--r--   0 root         (0) root         (0)      336 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/dune.module
--rw-r--r--   0 root         (0) root         (0)      385 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/pyproject.toml
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-18 20:43:55.577983 dune-iga-0.1.8.dev20230618204354/python/
--rw-r--r--   0 root         (0) root         (0)      381 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/python/CMakeLists.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-18 20:43:55.577983 dune-iga-0.1.8.dev20230618204354/python/dune/
--rw-r--r--   0 root         (0) root         (0)      179 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/python/dune/CMakeLists.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-18 20:43:55.577983 dune-iga-0.1.8.dev20230618204354/python/dune/iga/
--rw-r--r--   0 root         (0) root         (0)      675 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/python/dune/iga/CMakeLists.txt
--rw-r--r--   0 root         (0) root         (0)      409 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/python/dune/iga/__init__.py
--rw-r--r--   0 root         (0) root         (0)      726 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/python/dune/iga/_boundarypatch.py
--rw-r--r--   0 root         (0) root         (0)      367 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/python/dune/iga/_iga.cc
--rw-r--r--   0 root         (0) root         (0)     2168 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/python/dune/iga/_igagrids.py
--rw-r--r--   0 root         (0) root         (0)     3110 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/python/dune/iga/_nurbsAlgorithms.py
--rw-r--r--   0 root         (0) root         (0)     2978 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/python/dune/iga/_nurbspatchdata.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-18 20:43:55.577983 dune-iga-0.1.8.dev20230618204354/python/dune/iga/basis/
--rw-r--r--   0 root         (0) root         (0)      165 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/python/dune/iga/basis/CMakeLists.txt
--rw-r--r--   0 root         (0) root         (0)     3577 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/python/dune/iga/basis/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-18 20:43:55.577983 dune-iga-0.1.8.dev20230618204354/python/dune_iga.egg-info/
--rw-r--r--   0 root         (0) root         (0)     3129 2023-06-18 20:43:55.000000 dune-iga-0.1.8.dev20230618204354/python/dune_iga.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)     3671 2023-06-18 20:43:55.000000 dune-iga-0.1.8.dev20230618204354/python/dune_iga.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-18 20:43:55.000000 dune-iga-0.1.8.dev20230618204354/python/dune_iga.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)       85 2023-06-18 20:43:55.000000 dune-iga-0.1.8.dev20230618204354/python/dune_iga.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)        5 2023-06-18 20:43:55.000000 dune-iga-0.1.8.dev20230618204354/python/dune_iga.egg-info/top_level.txt
--rw-r--r--   0 root         (0) root         (0)       38 2023-06-18 20:43:55.581983 dune-iga-0.1.8.dev20230618204354/setup.cfg
--rw-r--r--   0 root         (0) root         (0)      889 2023-06-18 20:43:54.000000 dune-iga-0.1.8.dev20230618204354/setup.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-18 20:43:55.577983 dune-iga-0.1.8.dev20230618204354/src/
--rw-r--r--   0 root         (0) root         (0)     1399 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/src/CMakeLists.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-18 20:43:55.581983 dune-iga-0.1.8.dev20230618204354/src/auxiliaryFiles/
--rw-r--r--   0 root         (0) root         (0)      228 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/src/auxiliaryFiles/kirchhoff_plate.parset
--rw-r--r--   0 root         (0) root         (0)      216 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/src/auxiliaryFiles/linear2dsolid.parset
--rw-r--r--   0 root         (0) root         (0)     7688 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/src/auxiliaryFiles/surface-hole.ibra
--rw-r--r--   0 root         (0) root         (0)     6609 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/src/kirchhoff_plate.cc
--rw-r--r--   0 root         (0) root         (0)    13589 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/src/kirchhoffplate.hh
--rw-r--r--   0 root         (0) root         (0)     6968 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/src/linear2dsolid.cc
--rw-r--r--   0 root         (0) root         (0)    15691 2023-06-18 20:43:47.000000 dune-iga-0.1.8.dev20230618204354/src/linearElastic.hh
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.291960 dune-iga-0.1.8.dev20230627230825/
+-rw-r--r--   0 root         (0) root         (0)     1025 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/.clang-format
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.271960 dune-iga-0.1.8.dev20230627230825/.github/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.275960 dune-iga-0.1.8.dev20230627230825/.github/workflows/
+-rw-r--r--   0 root         (0) root         (0)      435 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/.github/workflows/codespell.yml
+-rw-r--r--   0 root         (0) root         (0)     1384 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/.github/workflows/createRelease.yml
+-rw-r--r--   0 root         (0) root         (0)     1758 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/.github/workflows/debian-coverage.yml
+-rw-r--r--   0 root         (0) root         (0)     2245 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/.github/workflows/debian.yml
+-rw-r--r--   0 root         (0) root         (0)     1728 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/.github/workflows/releasePythonPackage.yml
+-rw-r--r--   0 root         (0) root         (0)      317 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/.github/workflows/reuseLint.yml
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.275960 dune-iga-0.1.8.dev20230627230825/.github/workflows/scripts/
+-rw-r--r--   0 root         (0) root         (0)     3200 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/.github/workflows/scripts/release.py
+-rw-r--r--   0 root         (0) root         (0)     1152 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/.github/workflows/style.yml
+-rw-r--r--   0 root         (0) root         (0)      226 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/.gitignore
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.275960 dune-iga-0.1.8.dev20230627230825/.reuse/
+-rw-r--r--   0 root         (0) root         (0)      507 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/.reuse/dep5
+-rw-r--r--   0 root         (0) root         (0)      239 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/CHANGELOG.md
+-rw-r--r--   0 root         (0) root         (0)     1332 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/CMakeLists.txt
+-rw-r--r--   0 root         (0) root         (0)      251 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/LICENSE.md
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.275960 dune-iga-0.1.8.dev20230627230825/LICENSES/
+-rw-r--r--   0 root         (0) root         (0)     7048 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/LICENSES/CC0-1.0.txt
+-rw-r--r--   0 root         (0) root         (0)    42098 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/LICENSES/LGPL-3.0-or-later.txt
+-rw-r--r--   0 root         (0) root         (0)     3129 2023-06-27 23:08:26.291960 dune-iga-0.1.8.dev20230627230825/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     2718 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/README.md
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.275960 dune-iga-0.1.8.dev20230627230825/cmake/
+-rw-r--r--   0 root         (0) root         (0)      186 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/cmake/CMakeLists.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.279960 dune-iga-0.1.8.dev20230627230825/cmake/FormatTarget/
+-rw-r--r--   0 root         (0) root         (0)     1052 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/cmake/FormatTarget/CMakeLists.txt
+-rw-r--r--   0 root         (0) root         (0)      989 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/cmake/FormatTarget/CPM.cmake
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.279960 dune-iga-0.1.8.dev20230627230825/cmake/modules/
+-rw-r--r--   0 root         (0) root         (0)      753 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/cmake/modules/AddAutoDiffFlags.cmake
+-rw-r--r--   0 root         (0) root         (0)      843 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/cmake/modules/AddClipperLibFlags.cmake
+-rw-r--r--   0 root         (0) root         (0)      826 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/cmake/modules/AddEarCutFlags.cmake
+-rw-r--r--   0 root         (0) root         (0)      715 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/cmake/modules/AddEigenFlags.cmake
+-rw-r--r--   0 root         (0) root         (0)      824 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/cmake/modules/AddnLohmannJsonFlags.cmake
+-rw-r--r--   0 root         (0) root         (0)      226 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/cmake/modules/CMakeLists.txt
+-rw-r--r--   0 root         (0) root         (0)      450 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/cmake/modules/DuneIgaMacros.cmake
+-rw-r--r--   0 root         (0) root         (0)      158 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/codespellignore
+-rw-r--r--   0 root         (0) root         (0)     1421 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/config.h.cmake
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.279960 dune-iga-0.1.8.dev20230627230825/dune/
+-rw-r--r--   0 root         (0) root         (0)      219 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/CMakeLists.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.279960 dune-iga-0.1.8.dev20230627230825/dune/iga/
+-rw-r--r--   0 root         (0) root         (0)      808 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/CMakeLists.txt
+-rw-r--r--   0 root         (0) root         (0)     9152 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/bsplinealgorithms.hh
+-rw-r--r--   0 root         (0) root         (0)     2017 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/controlpoint.hh
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.283960 dune-iga-0.1.8.dev20230627230825/dune/iga/geometry/
+-rw-r--r--   0 root         (0) root         (0)      268 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/geometry/CMakeLists.txt
+-rw-r--r--   0 root         (0) root         (0)     6122 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/geometry/closestpointprojection.hh
+-rw-r--r--   0 root         (0) root         (0)     2825 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/geometry/geohelper.hh
+-rw-r--r--   0 root         (0) root         (0)     2785 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/gridcapabilities.hh
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.283960 dune-iga-0.1.8.dev20230627230825/dune/iga/io/
+-rw-r--r--   0 root         (0) root         (0)      267 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/io/CMakeLists.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.283960 dune-iga-0.1.8.dev20230627230825/dune/iga/io/ibra/
+-rw-r--r--   0 root         (0) root         (0)      258 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/io/ibra/CMakeLists.txt
+-rw-r--r--   0 root         (0) root         (0)    10369 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/io/ibra/ibrageometry.hh
+-rw-r--r--   0 root         (0) root         (0)     7806 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/io/ibra/ibrareader.hh
+-rw-r--r--   0 root         (0) root         (0)     8239 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/io/igadatacollector.hh
+-rw-r--r--   0 root         (0) root         (0)    30655 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsalgorithms.hh
+-rw-r--r--   0 root         (0) root         (0)    29306 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsbasis.hh
+-rw-r--r--   0 root         (0) root         (0)    18305 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsgeometry.hh
+-rw-r--r--   0 root         (0) root         (0)    11629 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsgrid.hh
+-rw-r--r--   0 root         (0) root         (0)    13111 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsgridentity.hh
+-rw-r--r--   0 root         (0) root         (0)     3063 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsgridindexsets.hh
+-rw-r--r--   0 root         (0) root         (0)     3957 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsgridleafiterator.hh
+-rw-r--r--   0 root         (0) root         (0)     5805 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsgridtraits.hh
+-rw-r--r--   0 root         (0) root         (0)     1285 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsidset.hh
+-rw-r--r--   0 root         (0) root         (0)     7979 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsintersection.hh
+-rw-r--r--   0 root         (0) root         (0)     9302 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsleafgridview.hh
+-rw-r--r--   0 root         (0) root         (0)     9447 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/nurbslocalgeometry.hh
+-rw-r--r--   0 root         (0) root         (0)    36685 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/nurbspatch.hh
+-rw-r--r--   0 root         (0) root         (0)     1454 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/nurbspatchdata.hh
+-rw-r--r--   0 root         (0) root         (0)     9061 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/nurbspatchgeometry.h
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.283960 dune-iga-0.1.8.dev20230627230825/dune/iga/test/
+-rw-r--r--   0 root         (0) root         (0)     1347 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/test/CMakeLists.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.283960 dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/
+-rw-r--r--   0 root         (0) root         (0)     5772 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/element.ibra
+-rw-r--r--   0 root         (0) root         (0)     7222 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/element_trim.ibra
+-rw-r--r--   0 root         (0) root         (0)     7396 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/element_trim_xb.ibra
+-rw-r--r--   0 root         (0) root         (0)     7665 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/infty_pwh.ibra
+-rw-r--r--   0 root         (0) root         (0)     6209 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/nurbs_1.ibra
+-rw-r--r--   0 root         (0) root         (0)     6704 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/pipe_trim.ibra
+-rw-r--r--   0 root         (0) root         (0)     7048 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/plate_quarter.ibra
+-rw-r--r--   0 root         (0) root         (0)    10170 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/schale_trim.ibra
+-rw-r--r--   0 root         (0) root         (0)    12176 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/shell-hole.ibra
+-rw-r--r--   0 root         (0) root         (0)     7146 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/shell.ibra
+-rw-r--r--   0 root         (0) root         (0)     7688 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/surface-hole.ibra
+-rw-r--r--   0 root         (0) root         (0)    60433 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/surface-multihole.ibra
+-rw-r--r--   0 root         (0) root         (0)    45902 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/test/gridTests.cc
+-rw-r--r--   0 root         (0) root         (0)    17503 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/test/trimmedGridTests.cc
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.287960 dune-iga-0.1.8.dev20230627230825/dune/iga/trim/
+-rw-r--r--   0 root         (0) root         (0)      308 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/trim/CMakeLists.txt
+-rw-r--r--   0 root         (0) root         (0)     4636 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/trim/nurbstrimboundary.hh
+-rw-r--r--   0 root         (0) root         (0)    37367 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/trim/nurbstrimmer.hh
+-rw-r--r--   0 root         (0) root         (0)    14597 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/trim/trimmedelementrepresentation.hh
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.287960 dune-iga-0.1.8.dev20230627230825/dune/iga/utils/
+-rw-r--r--   0 root         (0) root         (0)      328 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/utils/CMakeLists.txt
+-rw-r--r--   0 root         (0) root         (0)     2224 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/utils/concepts.hh
+-rw-r--r--   0 root         (0) root         (0)     1782 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/utils/fillquadraturerule.hh
+-rw-r--r--   0 root         (0) root         (0)     2372 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/utils/igahelpers.hh
+-rw-r--r--   0 root         (0) root         (0)      716 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/utils/linearalgebra.hh
+-rw-r--r--   0 root         (0) root         (0)    22274 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/utils/mdnet.hh
+-rw-r--r--   0 root         (0) root         (0)      402 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/utils/typetraits.hh
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.287960 dune-iga-0.1.8.dev20230627230825/dune/python/
+-rw-r--r--   0 root         (0) root         (0)      175 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/python/CMakeLists.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.287960 dune-iga-0.1.8.dev20230627230825/dune/python/iga/
+-rw-r--r--   0 root         (0) root         (0)      290 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/python/iga/CMakeLists.txt
+-rw-r--r--   0 root         (0) root         (0)     1538 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/python/iga/boundarypatch.hh
+-rw-r--r--   0 root         (0) root         (0)     6540 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/python/iga/grid.hh
+-rw-r--r--   0 root         (0) root         (0)      248 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/python/iga/gridenums.hh
+-rw-r--r--   0 root         (0) root         (0)     5102 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/python/iga/nurbspatchdata.hh
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.287960 dune-iga-0.1.8.dev20230627230825/dune/python/test/
+-rw-r--r--   0 root         (0) root         (0)      461 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/python/test/CMakeLists.txt
+-rw-r--r--   0 root         (0) root         (0)     5136 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/python/test/poisson.py
+-rw-r--r--   0 root         (0) root         (0)     5501 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/python/test/readGrid.py
+-rw-r--r--   0 root         (0) root         (0)      853 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/python/test/setpath.py.in
+-rw-r--r--   0 root         (0) root         (0)      431 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune-iga.pc.in
+-rw-r--r--   0 root         (0) root         (0)      336 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune.module
+-rw-r--r--   0 root         (0) root         (0)      385 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/pyproject.toml
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.287960 dune-iga-0.1.8.dev20230627230825/python/
+-rw-r--r--   0 root         (0) root         (0)      381 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/python/CMakeLists.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.287960 dune-iga-0.1.8.dev20230627230825/python/dune/
+-rw-r--r--   0 root         (0) root         (0)      179 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/python/dune/CMakeLists.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.287960 dune-iga-0.1.8.dev20230627230825/python/dune/iga/
+-rw-r--r--   0 root         (0) root         (0)      675 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/python/dune/iga/CMakeLists.txt
+-rw-r--r--   0 root         (0) root         (0)      409 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/python/dune/iga/__init__.py
+-rw-r--r--   0 root         (0) root         (0)      726 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/python/dune/iga/_boundarypatch.py
+-rw-r--r--   0 root         (0) root         (0)      367 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/python/dune/iga/_iga.cc
+-rw-r--r--   0 root         (0) root         (0)     2168 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/python/dune/iga/_igagrids.py
+-rw-r--r--   0 root         (0) root         (0)     3110 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/python/dune/iga/_nurbsAlgorithms.py
+-rw-r--r--   0 root         (0) root         (0)     2978 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/python/dune/iga/_nurbspatchdata.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.287960 dune-iga-0.1.8.dev20230627230825/python/dune/iga/basis/
+-rw-r--r--   0 root         (0) root         (0)      165 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/python/dune/iga/basis/CMakeLists.txt
+-rw-r--r--   0 root         (0) root         (0)     3577 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/python/dune/iga/basis/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.291960 dune-iga-0.1.8.dev20230627230825/python/dune_iga.egg-info/
+-rw-r--r--   0 root         (0) root         (0)     3129 2023-06-27 23:08:26.000000 dune-iga-0.1.8.dev20230627230825/python/dune_iga.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     3671 2023-06-27 23:08:26.000000 dune-iga-0.1.8.dev20230627230825/python/dune_iga.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-27 23:08:26.000000 dune-iga-0.1.8.dev20230627230825/python/dune_iga.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)       85 2023-06-27 23:08:26.000000 dune-iga-0.1.8.dev20230627230825/python/dune_iga.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)        5 2023-06-27 23:08:26.000000 dune-iga-0.1.8.dev20230627230825/python/dune_iga.egg-info/top_level.txt
+-rw-r--r--   0 root         (0) root         (0)       38 2023-06-27 23:08:26.291960 dune-iga-0.1.8.dev20230627230825/setup.cfg
+-rw-r--r--   0 root         (0) root         (0)      889 2023-06-27 23:08:25.000000 dune-iga-0.1.8.dev20230627230825/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.291960 dune-iga-0.1.8.dev20230627230825/src/
+-rw-r--r--   0 root         (0) root         (0)     1399 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/src/CMakeLists.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.291960 dune-iga-0.1.8.dev20230627230825/src/auxiliaryFiles/
+-rw-r--r--   0 root         (0) root         (0)      228 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/src/auxiliaryFiles/kirchhoff_plate.parset
+-rw-r--r--   0 root         (0) root         (0)      216 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/src/auxiliaryFiles/linear2dsolid.parset
+-rw-r--r--   0 root         (0) root         (0)     7688 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/src/auxiliaryFiles/surface-hole.ibra
+-rw-r--r--   0 root         (0) root         (0)     6609 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/src/kirchhoff_plate.cc
+-rw-r--r--   0 root         (0) root         (0)    13589 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/src/kirchhoffplate.hh
+-rw-r--r--   0 root         (0) root         (0)     6968 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/src/linear2dsolid.cc
+-rw-r--r--   0 root         (0) root         (0)    15691 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/src/linearElastic.hh
```

### Comparing `dune-iga-0.1.8.dev20230618204354/.clang-format` & `dune-iga-0.1.8.dev20230627230825/.clang-format`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/.github/workflows/createRelease.yml` & `dune-iga-0.1.8.dev20230627230825/.github/workflows/createRelease.yml`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/.github/workflows/debian-coverage.yml` & `dune-iga-0.1.8.dev20230627230825/.github/workflows/debian-coverage.yml`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/.github/workflows/debian.yml` & `dune-iga-0.1.8.dev20230627230825/.github/workflows/debian.yml`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/.github/workflows/releasePythonPackage.yml` & `dune-iga-0.1.8.dev20230627230825/.github/workflows/releasePythonPackage.yml`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/.github/workflows/scripts/release.py` & `dune-iga-0.1.8.dev20230627230825/.github/workflows/scripts/release.py`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/.github/workflows/style.yml` & `dune-iga-0.1.8.dev20230627230825/.github/workflows/style.yml`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/CMakeLists.txt` & `dune-iga-0.1.8.dev20230627230825/CMakeLists.txt`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/LICENSES/CC0-1.0.txt` & `dune-iga-0.1.8.dev20230627230825/LICENSES/CC0-1.0.txt`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/LICENSES/LGPL-3.0-or-later.txt` & `dune-iga-0.1.8.dev20230627230825/LICENSES/LGPL-3.0-or-later.txt`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/PKG-INFO` & `dune-iga-0.1.8.dev20230627230825/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: dune-iga
-Version: 0.1.8.dev20230618204354
+Version: 0.1.8.dev20230627230825
 Home-page: 
 Author: mueller@ibb.uni-stuttgart.de
 Author-email: mueller@ibb.uni-stuttgart.de
 Classifier: Programming Language :: C++
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: GNU General Public License (GPL)
 Requires-Python: >=3.4
```

### Comparing `dune-iga-0.1.8.dev20230618204354/README.md` & `dune-iga-0.1.8.dev20230627230825/README.md`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/cmake/FormatTarget/CMakeLists.txt` & `dune-iga-0.1.8.dev20230627230825/cmake/FormatTarget/CMakeLists.txt`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/cmake/FormatTarget/CPM.cmake` & `dune-iga-0.1.8.dev20230627230825/cmake/FormatTarget/CPM.cmake`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/cmake/modules/AddAutoDiffFlags.cmake` & `dune-iga-0.1.8.dev20230627230825/cmake/modules/AddAutoDiffFlags.cmake`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/cmake/modules/AddClipperLibFlags.cmake` & `dune-iga-0.1.8.dev20230627230825/cmake/modules/AddClipperLibFlags.cmake`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/cmake/modules/AddEarCutFlags.cmake` & `dune-iga-0.1.8.dev20230627230825/cmake/modules/AddEarCutFlags.cmake`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/cmake/modules/AddEigenFlags.cmake` & `dune-iga-0.1.8.dev20230627230825/cmake/modules/AddEigenFlags.cmake`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/cmake/modules/AddnLohmannJsonFlags.cmake` & `dune-iga-0.1.8.dev20230627230825/cmake/modules/AddnLohmannJsonFlags.cmake`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/config.h.cmake` & `dune-iga-0.1.8.dev20230627230825/config.h.cmake`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/CMakeLists.txt` & `dune-iga-0.1.8.dev20230627230825/dune/iga/CMakeLists.txt`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/bsplinealgorithms.hh` & `dune-iga-0.1.8.dev20230627230825/dune/iga/bsplinealgorithms.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/controlpoint.hh` & `dune-iga-0.1.8.dev20230627230825/dune/iga/controlpoint.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/geometry/closestpointprojection.hh` & `dune-iga-0.1.8.dev20230627230825/dune/iga/geometry/closestpointprojection.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/geometry/geohelper.hh` & `dune-iga-0.1.8.dev20230627230825/dune/iga/geometry/geohelper.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/gridcapabilities.hh` & `dune-iga-0.1.8.dev20230627230825/dune/iga/gridcapabilities.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/io/ibra/ibrageometry.hh` & `dune-iga-0.1.8.dev20230627230825/dune/iga/io/ibra/ibrageometry.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/io/ibra/ibrareader.hh` & `dune-iga-0.1.8.dev20230627230825/dune/iga/io/ibra/ibrareader.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/io/igadatacollector.hh` & `dune-iga-0.1.8.dev20230627230825/dune/iga/io/igadatacollector.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/nurbsalgorithms.hh` & `dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsalgorithms.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/nurbsbasis.hh` & `dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsbasis.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/nurbsgeometry.hh` & `dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsgeometry.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/nurbsgrid.hh` & `dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsgrid.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/nurbsgridentity.hh` & `dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsgridentity.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/nurbsgridindexsets.hh` & `dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsgridindexsets.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/nurbsgridleafiterator.hh` & `dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsgridleafiterator.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/nurbsgridtraits.hh` & `dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsgridtraits.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/nurbsidset.hh` & `dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsidset.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/nurbsintersection.hh` & `dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsintersection.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/nurbsleafgridview.hh` & `dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsleafgridview.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/nurbslocalgeometry.hh` & `dune-iga-0.1.8.dev20230627230825/dune/iga/nurbslocalgeometry.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/nurbspatch.hh` & `dune-iga-0.1.8.dev20230627230825/dune/iga/nurbspatch.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/nurbspatchdata.hh` & `dune-iga-0.1.8.dev20230627230825/dune/iga/nurbspatchdata.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/nurbspatchgeometry.h` & `dune-iga-0.1.8.dev20230627230825/dune/iga/nurbspatchgeometry.h`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/test/CMakeLists.txt` & `dune-iga-0.1.8.dev20230627230825/dune/iga/test/CMakeLists.txt`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/test/auxiliaryFiles/element.ibra` & `dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/element.ibra`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/test/auxiliaryFiles/element_trim.ibra` & `dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/element_trim.ibra`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/test/auxiliaryFiles/element_trim_xb.ibra` & `dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/element_trim_xb.ibra`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/test/auxiliaryFiles/infty_pwh.ibra` & `dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/infty_pwh.ibra`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/test/auxiliaryFiles/nurbs_1.ibra` & `dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/nurbs_1.ibra`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/test/auxiliaryFiles/pipe_trim.ibra` & `dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/pipe_trim.ibra`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/test/auxiliaryFiles/plate_quarter.ibra` & `dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/plate_quarter.ibra`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/test/auxiliaryFiles/schale_trim.ibra` & `dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/schale_trim.ibra`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/test/auxiliaryFiles/shell-hole.ibra` & `dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/shell-hole.ibra`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/test/auxiliaryFiles/shell.ibra` & `dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/shell.ibra`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/test/auxiliaryFiles/surface-hole.ibra` & `dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/surface-hole.ibra`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/test/auxiliaryFiles/surface-multihole.ibra` & `dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/surface-multihole.ibra`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/test/gridTests.cc` & `dune-iga-0.1.8.dev20230627230825/dune/iga/test/gridTests.cc`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/test/trimmedGridTests.cc` & `dune-iga-0.1.8.dev20230627230825/dune/iga/test/trimmedGridTests.cc`

 * *Files 0% similar despite different names*

```diff
@@ -252,15 +252,15 @@
   grid = IbraReader<2, 2>::read("auxiliaryFiles/plate_quarter.ibra");
   testLoop(grid, 4, "plate_quarter");
 
   grid = IbraReader<2, 2>::read("auxiliaryFiles/pipe_trim.ibra");
   testLoop(grid, 4, "pipe_trim");
 
   grid = IbraReader<2, 2>::read("auxiliaryFiles/element_trim_xb.ibra");
-  testLoop(grid, 4, "Element_trim_Xb");  // this test fails with a 6
+  testLoop(grid, 6, "Element_trim_Xb");
 
   grid = IbraReader<2, 2>::read("auxiliaryFiles/nurbs_1.ibra");
   testLoop(grid, 4, "nurbs_1");
 
   grid          = IbraReader<2, 2>::read("auxiliaryFiles/surface-multihole.ibra");
   const auto gv = grid->leafGridView();
   Dune::Vtk::DiscontinuousIgaDataCollector dataCollector1(gv);
```

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/trim/nurbstrimboundary.hh` & `dune-iga-0.1.8.dev20230627230825/dune/iga/trim/nurbstrimboundary.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/trim/nurbstrimmer.hh` & `dune-iga-0.1.8.dev20230627230825/dune/iga/trim/nurbstrimmer.hh`

 * *Files 0% similar despite different names*

```diff
@@ -151,20 +151,22 @@
 
     void clipElement(const auto& element) {
       auto index        = indexSet_.index(element);
       auto corners      = getElementCorners(index);
       auto elementEdges = getElementEdgesFromElementCorners(corners);
 
       ClipperPaths clippedEdges;
-      // Rule NonZero to ensure that inner boundaries are defined clockwise and outer boundaries counter-clockwuse
+      // Rule NonZero to ensure that inner boundaries are defined clockwise and outer boundaries counter-clockwise
+      /*
       if (clip_.size() == 1) {
         Clipper2Lib::Rect<intType> elementRect{corners[0][0], corners[1][1], corners[1][0], corners[3][1]};
         clippedEdges = Clipper2Lib::RectClip(elementRect, clip_);
       } else
-        clippedEdges = Clipper2Lib::Intersect(ClipperPaths{elementEdges}, clip_, Clipper2Lib::FillRule::NonZero);
+       */
+      clippedEdges = Clipper2Lib::Intersect(ClipperPaths{elementEdges}, clip_, Clipper2Lib::FillRule::NonZero);
 
       // At the moment there is no hole, if there are more than 2 Paths, then there is a hole
       std::optional<InnerLoops> innerLoops = std::nullopt;
       if (clippedEdges.size() > 1) {
         findInnerLoops(innerLoops, clippedEdges);
       }
```

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/trim/trimmedelementrepresentation.hh` & `dune-iga-0.1.8.dev20230627230825/dune/iga/trim/trimmedelementrepresentation.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/utils/concepts.hh` & `dune-iga-0.1.8.dev20230627230825/dune/iga/utils/concepts.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/utils/fillquadraturerule.hh` & `dune-iga-0.1.8.dev20230627230825/dune/iga/utils/fillquadraturerule.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/utils/igahelpers.hh` & `dune-iga-0.1.8.dev20230627230825/dune/iga/utils/igahelpers.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/utils/linearalgebra.hh` & `dune-iga-0.1.8.dev20230627230825/dune/iga/utils/linearalgebra.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/iga/utils/mdnet.hh` & `dune-iga-0.1.8.dev20230627230825/dune/iga/utils/mdnet.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/python/iga/boundarypatch.hh` & `dune-iga-0.1.8.dev20230627230825/dune/python/iga/boundarypatch.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/python/iga/grid.hh` & `dune-iga-0.1.8.dev20230627230825/dune/python/iga/grid.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/python/iga/nurbspatchdata.hh` & `dune-iga-0.1.8.dev20230627230825/dune/python/iga/nurbspatchdata.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/python/test/poisson.py` & `dune-iga-0.1.8.dev20230627230825/dune/python/test/poisson.py`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/python/test/readGrid.py` & `dune-iga-0.1.8.dev20230627230825/dune/python/test/readGrid.py`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/dune/python/test/setpath.py.in` & `dune-iga-0.1.8.dev20230627230825/dune/python/test/setpath.py.in`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/python/dune/iga/CMakeLists.txt` & `dune-iga-0.1.8.dev20230627230825/python/dune/iga/CMakeLists.txt`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/python/dune/iga/_boundarypatch.py` & `dune-iga-0.1.8.dev20230627230825/python/dune/iga/_boundarypatch.py`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/python/dune/iga/_igagrids.py` & `dune-iga-0.1.8.dev20230627230825/python/dune/iga/_igagrids.py`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/python/dune/iga/_nurbsAlgorithms.py` & `dune-iga-0.1.8.dev20230627230825/python/dune/iga/_nurbsAlgorithms.py`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/python/dune/iga/_nurbspatchdata.py` & `dune-iga-0.1.8.dev20230627230825/python/dune/iga/_nurbspatchdata.py`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/python/dune/iga/basis/__init__.py` & `dune-iga-0.1.8.dev20230627230825/python/dune/iga/basis/__init__.py`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/python/dune_iga.egg-info/PKG-INFO` & `dune-iga-0.1.8.dev20230627230825/python/dune_iga.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: dune-iga
-Version: 0.1.8.dev20230618204354
+Version: 0.1.8.dev20230627230825
 Home-page: 
 Author: mueller@ibb.uni-stuttgart.de
 Author-email: mueller@ibb.uni-stuttgart.de
 Classifier: Programming Language :: C++
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: GNU General Public License (GPL)
 Requires-Python: >=3.4
```

### Comparing `dune-iga-0.1.8.dev20230618204354/python/dune_iga.egg-info/SOURCES.txt` & `dune-iga-0.1.8.dev20230627230825/python/dune_iga.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/setup.py` & `dune-iga-0.1.8.dev20230627230825/setup.py`

 * *Files 16% similar despite different names*

```diff
@@ -12,14 +12,14 @@
 # build _iga
 # cd /tmp/dune-iga
 # /dune/dune-common/build-cmake/run-in-dune-env pip install twine scikit-build
 # git config --global --add safe.directory /tmp/dune-iga
 # /dune/dune-common/build-cmake/run-in-dune-env python setup.py sdist
 # /dune/dune-common/build-cmake/run-in-dune-env python -m twine upload dist/* --verbose
 
-duneigaVersion = "0.1.8.dev20230618204354"
+duneigaVersion = "0.1.8.dev20230627230825"
 duneVersion = "2.9.0"
 
 metadata = metaData(duneVersion)[1]
 metadata["version"] = duneigaVersion
 
 setup(**metadata)
```

### Comparing `dune-iga-0.1.8.dev20230618204354/src/CMakeLists.txt` & `dune-iga-0.1.8.dev20230627230825/src/CMakeLists.txt`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/src/auxiliaryFiles/surface-hole.ibra` & `dune-iga-0.1.8.dev20230627230825/src/auxiliaryFiles/surface-hole.ibra`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/src/kirchhoff_plate.cc` & `dune-iga-0.1.8.dev20230627230825/src/kirchhoff_plate.cc`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/src/kirchhoffplate.hh` & `dune-iga-0.1.8.dev20230627230825/src/kirchhoffplate.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/src/linear2dsolid.cc` & `dune-iga-0.1.8.dev20230627230825/src/linear2dsolid.cc`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230618204354/src/linearElastic.hh` & `dune-iga-0.1.8.dev20230627230825/src/linearElastic.hh`

 * *Files identical despite different names*


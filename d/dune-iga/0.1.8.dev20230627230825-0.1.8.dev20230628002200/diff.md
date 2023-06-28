# Comparing `tmp/dune-iga-0.1.8.dev20230627230825.tar.gz` & `tmp/dune-iga-0.1.8.dev20230628002200.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dune-iga-0.1.8.dev20230627230825.tar", last modified: Tue Jun 27 23:08:26 2023, max compression
+gzip compressed data, was "dune-iga-0.1.8.dev20230628002200.tar", last modified: Wed Jun 28 00:22:00 2023, max compression
```

## Comparing `dune-iga-0.1.8.dev20230627230825.tar` & `dune-iga-0.1.8.dev20230628002200.tar`

### file list

```diff
@@ -1,151 +1,151 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.291960 dune-iga-0.1.8.dev20230627230825/
--rw-r--r--   0 root         (0) root         (0)     1025 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/.clang-format
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.271960 dune-iga-0.1.8.dev20230627230825/.github/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.275960 dune-iga-0.1.8.dev20230627230825/.github/workflows/
--rw-r--r--   0 root         (0) root         (0)      435 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/.github/workflows/codespell.yml
--rw-r--r--   0 root         (0) root         (0)     1384 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/.github/workflows/createRelease.yml
--rw-r--r--   0 root         (0) root         (0)     1758 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/.github/workflows/debian-coverage.yml
--rw-r--r--   0 root         (0) root         (0)     2245 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/.github/workflows/debian.yml
--rw-r--r--   0 root         (0) root         (0)     1728 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/.github/workflows/releasePythonPackage.yml
--rw-r--r--   0 root         (0) root         (0)      317 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/.github/workflows/reuseLint.yml
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.275960 dune-iga-0.1.8.dev20230627230825/.github/workflows/scripts/
--rw-r--r--   0 root         (0) root         (0)     3200 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/.github/workflows/scripts/release.py
--rw-r--r--   0 root         (0) root         (0)     1152 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/.github/workflows/style.yml
--rw-r--r--   0 root         (0) root         (0)      226 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/.gitignore
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.275960 dune-iga-0.1.8.dev20230627230825/.reuse/
--rw-r--r--   0 root         (0) root         (0)      507 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/.reuse/dep5
--rw-r--r--   0 root         (0) root         (0)      239 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/CHANGELOG.md
--rw-r--r--   0 root         (0) root         (0)     1332 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/CMakeLists.txt
--rw-r--r--   0 root         (0) root         (0)      251 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/LICENSE.md
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.275960 dune-iga-0.1.8.dev20230627230825/LICENSES/
--rw-r--r--   0 root         (0) root         (0)     7048 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/LICENSES/CC0-1.0.txt
--rw-r--r--   0 root         (0) root         (0)    42098 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/LICENSES/LGPL-3.0-or-later.txt
--rw-r--r--   0 root         (0) root         (0)     3129 2023-06-27 23:08:26.291960 dune-iga-0.1.8.dev20230627230825/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)     2718 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/README.md
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.275960 dune-iga-0.1.8.dev20230627230825/cmake/
--rw-r--r--   0 root         (0) root         (0)      186 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/cmake/CMakeLists.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.279960 dune-iga-0.1.8.dev20230627230825/cmake/FormatTarget/
--rw-r--r--   0 root         (0) root         (0)     1052 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/cmake/FormatTarget/CMakeLists.txt
--rw-r--r--   0 root         (0) root         (0)      989 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/cmake/FormatTarget/CPM.cmake
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.279960 dune-iga-0.1.8.dev20230627230825/cmake/modules/
--rw-r--r--   0 root         (0) root         (0)      753 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/cmake/modules/AddAutoDiffFlags.cmake
--rw-r--r--   0 root         (0) root         (0)      843 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/cmake/modules/AddClipperLibFlags.cmake
--rw-r--r--   0 root         (0) root         (0)      826 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/cmake/modules/AddEarCutFlags.cmake
--rw-r--r--   0 root         (0) root         (0)      715 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/cmake/modules/AddEigenFlags.cmake
--rw-r--r--   0 root         (0) root         (0)      824 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/cmake/modules/AddnLohmannJsonFlags.cmake
--rw-r--r--   0 root         (0) root         (0)      226 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/cmake/modules/CMakeLists.txt
--rw-r--r--   0 root         (0) root         (0)      450 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/cmake/modules/DuneIgaMacros.cmake
--rw-r--r--   0 root         (0) root         (0)      158 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/codespellignore
--rw-r--r--   0 root         (0) root         (0)     1421 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/config.h.cmake
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.279960 dune-iga-0.1.8.dev20230627230825/dune/
--rw-r--r--   0 root         (0) root         (0)      219 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/CMakeLists.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.279960 dune-iga-0.1.8.dev20230627230825/dune/iga/
--rw-r--r--   0 root         (0) root         (0)      808 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/CMakeLists.txt
--rw-r--r--   0 root         (0) root         (0)     9152 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/bsplinealgorithms.hh
--rw-r--r--   0 root         (0) root         (0)     2017 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/controlpoint.hh
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.283960 dune-iga-0.1.8.dev20230627230825/dune/iga/geometry/
--rw-r--r--   0 root         (0) root         (0)      268 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/geometry/CMakeLists.txt
--rw-r--r--   0 root         (0) root         (0)     6122 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/geometry/closestpointprojection.hh
--rw-r--r--   0 root         (0) root         (0)     2825 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/geometry/geohelper.hh
--rw-r--r--   0 root         (0) root         (0)     2785 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/gridcapabilities.hh
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.283960 dune-iga-0.1.8.dev20230627230825/dune/iga/io/
--rw-r--r--   0 root         (0) root         (0)      267 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/io/CMakeLists.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.283960 dune-iga-0.1.8.dev20230627230825/dune/iga/io/ibra/
--rw-r--r--   0 root         (0) root         (0)      258 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/io/ibra/CMakeLists.txt
--rw-r--r--   0 root         (0) root         (0)    10369 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/io/ibra/ibrageometry.hh
--rw-r--r--   0 root         (0) root         (0)     7806 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/io/ibra/ibrareader.hh
--rw-r--r--   0 root         (0) root         (0)     8239 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/io/igadatacollector.hh
--rw-r--r--   0 root         (0) root         (0)    30655 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsalgorithms.hh
--rw-r--r--   0 root         (0) root         (0)    29306 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsbasis.hh
--rw-r--r--   0 root         (0) root         (0)    18305 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsgeometry.hh
--rw-r--r--   0 root         (0) root         (0)    11629 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsgrid.hh
--rw-r--r--   0 root         (0) root         (0)    13111 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsgridentity.hh
--rw-r--r--   0 root         (0) root         (0)     3063 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsgridindexsets.hh
--rw-r--r--   0 root         (0) root         (0)     3957 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsgridleafiterator.hh
--rw-r--r--   0 root         (0) root         (0)     5805 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsgridtraits.hh
--rw-r--r--   0 root         (0) root         (0)     1285 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsidset.hh
--rw-r--r--   0 root         (0) root         (0)     7979 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsintersection.hh
--rw-r--r--   0 root         (0) root         (0)     9302 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsleafgridview.hh
--rw-r--r--   0 root         (0) root         (0)     9447 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/nurbslocalgeometry.hh
--rw-r--r--   0 root         (0) root         (0)    36685 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/nurbspatch.hh
--rw-r--r--   0 root         (0) root         (0)     1454 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/nurbspatchdata.hh
--rw-r--r--   0 root         (0) root         (0)     9061 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/nurbspatchgeometry.h
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.283960 dune-iga-0.1.8.dev20230627230825/dune/iga/test/
--rw-r--r--   0 root         (0) root         (0)     1347 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/test/CMakeLists.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.283960 dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/
--rw-r--r--   0 root         (0) root         (0)     5772 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/element.ibra
--rw-r--r--   0 root         (0) root         (0)     7222 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/element_trim.ibra
--rw-r--r--   0 root         (0) root         (0)     7396 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/element_trim_xb.ibra
--rw-r--r--   0 root         (0) root         (0)     7665 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/infty_pwh.ibra
--rw-r--r--   0 root         (0) root         (0)     6209 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/nurbs_1.ibra
--rw-r--r--   0 root         (0) root         (0)     6704 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/pipe_trim.ibra
--rw-r--r--   0 root         (0) root         (0)     7048 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/plate_quarter.ibra
--rw-r--r--   0 root         (0) root         (0)    10170 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/schale_trim.ibra
--rw-r--r--   0 root         (0) root         (0)    12176 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/shell-hole.ibra
--rw-r--r--   0 root         (0) root         (0)     7146 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/shell.ibra
--rw-r--r--   0 root         (0) root         (0)     7688 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/surface-hole.ibra
--rw-r--r--   0 root         (0) root         (0)    60433 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/surface-multihole.ibra
--rw-r--r--   0 root         (0) root         (0)    45902 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/test/gridTests.cc
--rw-r--r--   0 root         (0) root         (0)    17503 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/test/trimmedGridTests.cc
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.287960 dune-iga-0.1.8.dev20230627230825/dune/iga/trim/
--rw-r--r--   0 root         (0) root         (0)      308 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/trim/CMakeLists.txt
--rw-r--r--   0 root         (0) root         (0)     4636 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/trim/nurbstrimboundary.hh
--rw-r--r--   0 root         (0) root         (0)    37367 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/trim/nurbstrimmer.hh
--rw-r--r--   0 root         (0) root         (0)    14597 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/trim/trimmedelementrepresentation.hh
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.287960 dune-iga-0.1.8.dev20230627230825/dune/iga/utils/
--rw-r--r--   0 root         (0) root         (0)      328 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/utils/CMakeLists.txt
--rw-r--r--   0 root         (0) root         (0)     2224 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/utils/concepts.hh
--rw-r--r--   0 root         (0) root         (0)     1782 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/utils/fillquadraturerule.hh
--rw-r--r--   0 root         (0) root         (0)     2372 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/utils/igahelpers.hh
--rw-r--r--   0 root         (0) root         (0)      716 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/utils/linearalgebra.hh
--rw-r--r--   0 root         (0) root         (0)    22274 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/utils/mdnet.hh
--rw-r--r--   0 root         (0) root         (0)      402 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/iga/utils/typetraits.hh
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.287960 dune-iga-0.1.8.dev20230627230825/dune/python/
--rw-r--r--   0 root         (0) root         (0)      175 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/python/CMakeLists.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.287960 dune-iga-0.1.8.dev20230627230825/dune/python/iga/
--rw-r--r--   0 root         (0) root         (0)      290 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/python/iga/CMakeLists.txt
--rw-r--r--   0 root         (0) root         (0)     1538 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/python/iga/boundarypatch.hh
--rw-r--r--   0 root         (0) root         (0)     6540 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/python/iga/grid.hh
--rw-r--r--   0 root         (0) root         (0)      248 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/python/iga/gridenums.hh
--rw-r--r--   0 root         (0) root         (0)     5102 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/python/iga/nurbspatchdata.hh
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.287960 dune-iga-0.1.8.dev20230627230825/dune/python/test/
--rw-r--r--   0 root         (0) root         (0)      461 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/python/test/CMakeLists.txt
--rw-r--r--   0 root         (0) root         (0)     5136 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/python/test/poisson.py
--rw-r--r--   0 root         (0) root         (0)     5501 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/python/test/readGrid.py
--rw-r--r--   0 root         (0) root         (0)      853 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune/python/test/setpath.py.in
--rw-r--r--   0 root         (0) root         (0)      431 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune-iga.pc.in
--rw-r--r--   0 root         (0) root         (0)      336 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/dune.module
--rw-r--r--   0 root         (0) root         (0)      385 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/pyproject.toml
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.287960 dune-iga-0.1.8.dev20230627230825/python/
--rw-r--r--   0 root         (0) root         (0)      381 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/python/CMakeLists.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.287960 dune-iga-0.1.8.dev20230627230825/python/dune/
--rw-r--r--   0 root         (0) root         (0)      179 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/python/dune/CMakeLists.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.287960 dune-iga-0.1.8.dev20230627230825/python/dune/iga/
--rw-r--r--   0 root         (0) root         (0)      675 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/python/dune/iga/CMakeLists.txt
--rw-r--r--   0 root         (0) root         (0)      409 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/python/dune/iga/__init__.py
--rw-r--r--   0 root         (0) root         (0)      726 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/python/dune/iga/_boundarypatch.py
--rw-r--r--   0 root         (0) root         (0)      367 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/python/dune/iga/_iga.cc
--rw-r--r--   0 root         (0) root         (0)     2168 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/python/dune/iga/_igagrids.py
--rw-r--r--   0 root         (0) root         (0)     3110 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/python/dune/iga/_nurbsAlgorithms.py
--rw-r--r--   0 root         (0) root         (0)     2978 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/python/dune/iga/_nurbspatchdata.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.287960 dune-iga-0.1.8.dev20230627230825/python/dune/iga/basis/
--rw-r--r--   0 root         (0) root         (0)      165 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/python/dune/iga/basis/CMakeLists.txt
--rw-r--r--   0 root         (0) root         (0)     3577 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/python/dune/iga/basis/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.291960 dune-iga-0.1.8.dev20230627230825/python/dune_iga.egg-info/
--rw-r--r--   0 root         (0) root         (0)     3129 2023-06-27 23:08:26.000000 dune-iga-0.1.8.dev20230627230825/python/dune_iga.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)     3671 2023-06-27 23:08:26.000000 dune-iga-0.1.8.dev20230627230825/python/dune_iga.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-27 23:08:26.000000 dune-iga-0.1.8.dev20230627230825/python/dune_iga.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)       85 2023-06-27 23:08:26.000000 dune-iga-0.1.8.dev20230627230825/python/dune_iga.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)        5 2023-06-27 23:08:26.000000 dune-iga-0.1.8.dev20230627230825/python/dune_iga.egg-info/top_level.txt
--rw-r--r--   0 root         (0) root         (0)       38 2023-06-27 23:08:26.291960 dune-iga-0.1.8.dev20230627230825/setup.cfg
--rw-r--r--   0 root         (0) root         (0)      889 2023-06-27 23:08:25.000000 dune-iga-0.1.8.dev20230627230825/setup.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.291960 dune-iga-0.1.8.dev20230627230825/src/
--rw-r--r--   0 root         (0) root         (0)     1399 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/src/CMakeLists.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 23:08:26.291960 dune-iga-0.1.8.dev20230627230825/src/auxiliaryFiles/
--rw-r--r--   0 root         (0) root         (0)      228 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/src/auxiliaryFiles/kirchhoff_plate.parset
--rw-r--r--   0 root         (0) root         (0)      216 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/src/auxiliaryFiles/linear2dsolid.parset
--rw-r--r--   0 root         (0) root         (0)     7688 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/src/auxiliaryFiles/surface-hole.ibra
--rw-r--r--   0 root         (0) root         (0)     6609 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/src/kirchhoff_plate.cc
--rw-r--r--   0 root         (0) root         (0)    13589 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/src/kirchhoffplate.hh
--rw-r--r--   0 root         (0) root         (0)     6968 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/src/linear2dsolid.cc
--rw-r--r--   0 root         (0) root         (0)    15691 2023-06-27 23:08:18.000000 dune-iga-0.1.8.dev20230627230825/src/linearElastic.hh
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:00.709578 dune-iga-0.1.8.dev20230628002200/
+-rw-r--r--   0 root         (0) root         (0)     1025 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/.clang-format
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:00.681577 dune-iga-0.1.8.dev20230628002200/.github/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:00.685577 dune-iga-0.1.8.dev20230628002200/.github/workflows/
+-rw-r--r--   0 root         (0) root         (0)      435 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/.github/workflows/codespell.yml
+-rw-r--r--   0 root         (0) root         (0)     1384 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/.github/workflows/createRelease.yml
+-rw-r--r--   0 root         (0) root         (0)     1758 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/.github/workflows/debian-coverage.yml
+-rw-r--r--   0 root         (0) root         (0)     2245 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/.github/workflows/debian.yml
+-rw-r--r--   0 root         (0) root         (0)     1728 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/.github/workflows/releasePythonPackage.yml
+-rw-r--r--   0 root         (0) root         (0)      317 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/.github/workflows/reuseLint.yml
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:00.685577 dune-iga-0.1.8.dev20230628002200/.github/workflows/scripts/
+-rw-r--r--   0 root         (0) root         (0)     3200 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/.github/workflows/scripts/release.py
+-rw-r--r--   0 root         (0) root         (0)     1152 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/.github/workflows/style.yml
+-rw-r--r--   0 root         (0) root         (0)      226 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/.gitignore
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:00.689577 dune-iga-0.1.8.dev20230628002200/.reuse/
+-rw-r--r--   0 root         (0) root         (0)      507 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/.reuse/dep5
+-rw-r--r--   0 root         (0) root         (0)      239 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/CHANGELOG.md
+-rw-r--r--   0 root         (0) root         (0)     1332 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/CMakeLists.txt
+-rw-r--r--   0 root         (0) root         (0)      251 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/LICENSE.md
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:00.689577 dune-iga-0.1.8.dev20230628002200/LICENSES/
+-rw-r--r--   0 root         (0) root         (0)     7048 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/LICENSES/CC0-1.0.txt
+-rw-r--r--   0 root         (0) root         (0)    42098 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/LICENSES/LGPL-3.0-or-later.txt
+-rw-r--r--   0 root         (0) root         (0)     3129 2023-06-28 00:22:00.709578 dune-iga-0.1.8.dev20230628002200/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     2718 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/README.md
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:00.689577 dune-iga-0.1.8.dev20230628002200/cmake/
+-rw-r--r--   0 root         (0) root         (0)      186 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/cmake/CMakeLists.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:00.689577 dune-iga-0.1.8.dev20230628002200/cmake/FormatTarget/
+-rw-r--r--   0 root         (0) root         (0)     1052 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/cmake/FormatTarget/CMakeLists.txt
+-rw-r--r--   0 root         (0) root         (0)      989 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/cmake/FormatTarget/CPM.cmake
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:00.689577 dune-iga-0.1.8.dev20230628002200/cmake/modules/
+-rw-r--r--   0 root         (0) root         (0)      753 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/cmake/modules/AddAutoDiffFlags.cmake
+-rw-r--r--   0 root         (0) root         (0)      843 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/cmake/modules/AddClipperLibFlags.cmake
+-rw-r--r--   0 root         (0) root         (0)      826 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/cmake/modules/AddEarCutFlags.cmake
+-rw-r--r--   0 root         (0) root         (0)      715 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/cmake/modules/AddEigenFlags.cmake
+-rw-r--r--   0 root         (0) root         (0)      824 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/cmake/modules/AddnLohmannJsonFlags.cmake
+-rw-r--r--   0 root         (0) root         (0)      226 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/cmake/modules/CMakeLists.txt
+-rw-r--r--   0 root         (0) root         (0)      450 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/cmake/modules/DuneIgaMacros.cmake
+-rw-r--r--   0 root         (0) root         (0)      158 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/codespellignore
+-rw-r--r--   0 root         (0) root         (0)     1421 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/config.h.cmake
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:00.689577 dune-iga-0.1.8.dev20230628002200/dune/
+-rw-r--r--   0 root         (0) root         (0)      219 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/CMakeLists.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:00.693578 dune-iga-0.1.8.dev20230628002200/dune/iga/
+-rw-r--r--   0 root         (0) root         (0)      808 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/CMakeLists.txt
+-rw-r--r--   0 root         (0) root         (0)     8776 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/bsplinealgorithms.hh
+-rw-r--r--   0 root         (0) root         (0)     2017 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/controlpoint.hh
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:00.693578 dune-iga-0.1.8.dev20230628002200/dune/iga/geometry/
+-rw-r--r--   0 root         (0) root         (0)      268 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/geometry/CMakeLists.txt
+-rw-r--r--   0 root         (0) root         (0)     6370 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/geometry/closestpointprojection.hh
+-rw-r--r--   0 root         (0) root         (0)     2825 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/geometry/geohelper.hh
+-rw-r--r--   0 root         (0) root         (0)     2785 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/gridcapabilities.hh
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:00.693578 dune-iga-0.1.8.dev20230628002200/dune/iga/io/
+-rw-r--r--   0 root         (0) root         (0)      267 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/io/CMakeLists.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:00.697578 dune-iga-0.1.8.dev20230628002200/dune/iga/io/ibra/
+-rw-r--r--   0 root         (0) root         (0)      258 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/io/ibra/CMakeLists.txt
+-rw-r--r--   0 root         (0) root         (0)    10369 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/io/ibra/ibrageometry.hh
+-rw-r--r--   0 root         (0) root         (0)     7806 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/io/ibra/ibrareader.hh
+-rw-r--r--   0 root         (0) root         (0)     8239 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/io/igadatacollector.hh
+-rw-r--r--   0 root         (0) root         (0)    30645 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/nurbsalgorithms.hh
+-rw-r--r--   0 root         (0) root         (0)    29306 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/nurbsbasis.hh
+-rw-r--r--   0 root         (0) root         (0)    18305 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/nurbsgeometry.hh
+-rw-r--r--   0 root         (0) root         (0)    12542 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/nurbsgrid.hh
+-rw-r--r--   0 root         (0) root         (0)    13111 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/nurbsgridentity.hh
+-rw-r--r--   0 root         (0) root         (0)     3063 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/nurbsgridindexsets.hh
+-rw-r--r--   0 root         (0) root         (0)     3957 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/nurbsgridleafiterator.hh
+-rw-r--r--   0 root         (0) root         (0)     5805 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/nurbsgridtraits.hh
+-rw-r--r--   0 root         (0) root         (0)     1285 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/nurbsidset.hh
+-rw-r--r--   0 root         (0) root         (0)     7979 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/nurbsintersection.hh
+-rw-r--r--   0 root         (0) root         (0)     9409 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/nurbsleafgridview.hh
+-rw-r--r--   0 root         (0) root         (0)     9447 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/nurbslocalgeometry.hh
+-rw-r--r--   0 root         (0) root         (0)    36685 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/nurbspatch.hh
+-rw-r--r--   0 root         (0) root         (0)     1454 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/nurbspatchdata.hh
+-rw-r--r--   0 root         (0) root         (0)     9061 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/nurbspatchgeometry.h
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:00.697578 dune-iga-0.1.8.dev20230628002200/dune/iga/test/
+-rw-r--r--   0 root         (0) root         (0)     1347 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/test/CMakeLists.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:00.697578 dune-iga-0.1.8.dev20230628002200/dune/iga/test/auxiliaryFiles/
+-rw-r--r--   0 root         (0) root         (0)     5772 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/test/auxiliaryFiles/element.ibra
+-rw-r--r--   0 root         (0) root         (0)     7222 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/test/auxiliaryFiles/element_trim.ibra
+-rw-r--r--   0 root         (0) root         (0)     7396 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/test/auxiliaryFiles/element_trim_xb.ibra
+-rw-r--r--   0 root         (0) root         (0)     7665 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/test/auxiliaryFiles/infty_pwh.ibra
+-rw-r--r--   0 root         (0) root         (0)     6209 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/test/auxiliaryFiles/nurbs_1.ibra
+-rw-r--r--   0 root         (0) root         (0)     6704 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/test/auxiliaryFiles/pipe_trim.ibra
+-rw-r--r--   0 root         (0) root         (0)     7048 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/test/auxiliaryFiles/plate_quarter.ibra
+-rw-r--r--   0 root         (0) root         (0)    10170 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/test/auxiliaryFiles/schale_trim.ibra
+-rw-r--r--   0 root         (0) root         (0)    12176 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/test/auxiliaryFiles/shell-hole.ibra
+-rw-r--r--   0 root         (0) root         (0)     7146 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/test/auxiliaryFiles/shell.ibra
+-rw-r--r--   0 root         (0) root         (0)     7688 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/test/auxiliaryFiles/surface-hole.ibra
+-rw-r--r--   0 root         (0) root         (0)    60433 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/test/auxiliaryFiles/surface-multihole.ibra
+-rw-r--r--   0 root         (0) root         (0)    58550 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/test/gridTests.cc
+-rw-r--r--   0 root         (0) root         (0)    18074 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/test/trimmedGridTests.cc
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:00.697578 dune-iga-0.1.8.dev20230628002200/dune/iga/trim/
+-rw-r--r--   0 root         (0) root         (0)      308 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/trim/CMakeLists.txt
+-rw-r--r--   0 root         (0) root         (0)     4636 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/trim/nurbstrimboundary.hh
+-rw-r--r--   0 root         (0) root         (0)    37367 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/trim/nurbstrimmer.hh
+-rw-r--r--   0 root         (0) root         (0)    14597 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/trim/trimmedelementrepresentation.hh
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:00.701578 dune-iga-0.1.8.dev20230628002200/dune/iga/utils/
+-rw-r--r--   0 root         (0) root         (0)      328 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/utils/CMakeLists.txt
+-rw-r--r--   0 root         (0) root         (0)     2224 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/utils/concepts.hh
+-rw-r--r--   0 root         (0) root         (0)     1782 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/utils/fillquadraturerule.hh
+-rw-r--r--   0 root         (0) root         (0)     2372 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/utils/igahelpers.hh
+-rw-r--r--   0 root         (0) root         (0)      716 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/utils/linearalgebra.hh
+-rw-r--r--   0 root         (0) root         (0)    22274 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/utils/mdnet.hh
+-rw-r--r--   0 root         (0) root         (0)      402 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/iga/utils/typetraits.hh
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:00.701578 dune-iga-0.1.8.dev20230628002200/dune/python/
+-rw-r--r--   0 root         (0) root         (0)      175 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/python/CMakeLists.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:00.701578 dune-iga-0.1.8.dev20230628002200/dune/python/iga/
+-rw-r--r--   0 root         (0) root         (0)      290 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/python/iga/CMakeLists.txt
+-rw-r--r--   0 root         (0) root         (0)     1538 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/python/iga/boundarypatch.hh
+-rw-r--r--   0 root         (0) root         (0)     6540 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/python/iga/grid.hh
+-rw-r--r--   0 root         (0) root         (0)      248 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/python/iga/gridenums.hh
+-rw-r--r--   0 root         (0) root         (0)     5102 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/python/iga/nurbspatchdata.hh
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:00.701578 dune-iga-0.1.8.dev20230628002200/dune/python/test/
+-rw-r--r--   0 root         (0) root         (0)      461 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/python/test/CMakeLists.txt
+-rw-r--r--   0 root         (0) root         (0)     5136 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/python/test/poisson.py
+-rw-r--r--   0 root         (0) root         (0)     5501 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/python/test/readGrid.py
+-rw-r--r--   0 root         (0) root         (0)      853 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune/python/test/setpath.py.in
+-rw-r--r--   0 root         (0) root         (0)      431 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune-iga.pc.in
+-rw-r--r--   0 root         (0) root         (0)      336 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/dune.module
+-rw-r--r--   0 root         (0) root         (0)      385 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/pyproject.toml
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:00.701578 dune-iga-0.1.8.dev20230628002200/python/
+-rw-r--r--   0 root         (0) root         (0)      381 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/python/CMakeLists.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:00.701578 dune-iga-0.1.8.dev20230628002200/python/dune/
+-rw-r--r--   0 root         (0) root         (0)      179 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/python/dune/CMakeLists.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:00.705578 dune-iga-0.1.8.dev20230628002200/python/dune/iga/
+-rw-r--r--   0 root         (0) root         (0)      675 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/python/dune/iga/CMakeLists.txt
+-rw-r--r--   0 root         (0) root         (0)      409 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/python/dune/iga/__init__.py
+-rw-r--r--   0 root         (0) root         (0)      726 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/python/dune/iga/_boundarypatch.py
+-rw-r--r--   0 root         (0) root         (0)      367 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/python/dune/iga/_iga.cc
+-rw-r--r--   0 root         (0) root         (0)     2168 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/python/dune/iga/_igagrids.py
+-rw-r--r--   0 root         (0) root         (0)     3110 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/python/dune/iga/_nurbsAlgorithms.py
+-rw-r--r--   0 root         (0) root         (0)     2978 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/python/dune/iga/_nurbspatchdata.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:00.705578 dune-iga-0.1.8.dev20230628002200/python/dune/iga/basis/
+-rw-r--r--   0 root         (0) root         (0)      165 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/python/dune/iga/basis/CMakeLists.txt
+-rw-r--r--   0 root         (0) root         (0)     3577 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/python/dune/iga/basis/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:00.705578 dune-iga-0.1.8.dev20230628002200/python/dune_iga.egg-info/
+-rw-r--r--   0 root         (0) root         (0)     3129 2023-06-28 00:22:00.000000 dune-iga-0.1.8.dev20230628002200/python/dune_iga.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     3671 2023-06-28 00:22:00.000000 dune-iga-0.1.8.dev20230628002200/python/dune_iga.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 00:22:00.000000 dune-iga-0.1.8.dev20230628002200/python/dune_iga.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)       85 2023-06-28 00:22:00.000000 dune-iga-0.1.8.dev20230628002200/python/dune_iga.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)        5 2023-06-28 00:22:00.000000 dune-iga-0.1.8.dev20230628002200/python/dune_iga.egg-info/top_level.txt
+-rw-r--r--   0 root         (0) root         (0)       38 2023-06-28 00:22:00.709578 dune-iga-0.1.8.dev20230628002200/setup.cfg
+-rw-r--r--   0 root         (0) root         (0)      889 2023-06-28 00:22:00.000000 dune-iga-0.1.8.dev20230628002200/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:00.705578 dune-iga-0.1.8.dev20230628002200/src/
+-rw-r--r--   0 root         (0) root         (0)     1399 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/src/CMakeLists.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:00.705578 dune-iga-0.1.8.dev20230628002200/src/auxiliaryFiles/
+-rw-r--r--   0 root         (0) root         (0)      228 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/src/auxiliaryFiles/kirchhoff_plate.parset
+-rw-r--r--   0 root         (0) root         (0)      216 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/src/auxiliaryFiles/linear2dsolid.parset
+-rw-r--r--   0 root         (0) root         (0)     7688 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/src/auxiliaryFiles/surface-hole.ibra
+-rw-r--r--   0 root         (0) root         (0)     6609 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/src/kirchhoff_plate.cc
+-rw-r--r--   0 root         (0) root         (0)    13589 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/src/kirchhoffplate.hh
+-rw-r--r--   0 root         (0) root         (0)     6968 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/src/linear2dsolid.cc
+-rw-r--r--   0 root         (0) root         (0)    15691 2023-06-28 00:21:52.000000 dune-iga-0.1.8.dev20230628002200/src/linearElastic.hh
```

### Comparing `dune-iga-0.1.8.dev20230627230825/.clang-format` & `dune-iga-0.1.8.dev20230628002200/.clang-format`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/.github/workflows/createRelease.yml` & `dune-iga-0.1.8.dev20230628002200/.github/workflows/createRelease.yml`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/.github/workflows/debian-coverage.yml` & `dune-iga-0.1.8.dev20230628002200/.github/workflows/debian-coverage.yml`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/.github/workflows/debian.yml` & `dune-iga-0.1.8.dev20230628002200/.github/workflows/debian.yml`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/.github/workflows/releasePythonPackage.yml` & `dune-iga-0.1.8.dev20230628002200/.github/workflows/releasePythonPackage.yml`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/.github/workflows/scripts/release.py` & `dune-iga-0.1.8.dev20230628002200/.github/workflows/scripts/release.py`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/.github/workflows/style.yml` & `dune-iga-0.1.8.dev20230628002200/.github/workflows/style.yml`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/CMakeLists.txt` & `dune-iga-0.1.8.dev20230628002200/CMakeLists.txt`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/LICENSES/CC0-1.0.txt` & `dune-iga-0.1.8.dev20230628002200/LICENSES/CC0-1.0.txt`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/LICENSES/LGPL-3.0-or-later.txt` & `dune-iga-0.1.8.dev20230628002200/LICENSES/LGPL-3.0-or-later.txt`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/PKG-INFO` & `dune-iga-0.1.8.dev20230628002200/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: dune-iga
-Version: 0.1.8.dev20230627230825
+Version: 0.1.8.dev20230628002200
 Home-page: 
 Author: mueller@ibb.uni-stuttgart.de
 Author-email: mueller@ibb.uni-stuttgart.de
 Classifier: Programming Language :: C++
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: GNU General Public License (GPL)
 Requires-Python: >=3.4
```

### Comparing `dune-iga-0.1.8.dev20230627230825/README.md` & `dune-iga-0.1.8.dev20230628002200/README.md`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/cmake/FormatTarget/CMakeLists.txt` & `dune-iga-0.1.8.dev20230628002200/cmake/FormatTarget/CMakeLists.txt`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/cmake/FormatTarget/CPM.cmake` & `dune-iga-0.1.8.dev20230628002200/cmake/FormatTarget/CPM.cmake`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/cmake/modules/AddAutoDiffFlags.cmake` & `dune-iga-0.1.8.dev20230628002200/cmake/modules/AddAutoDiffFlags.cmake`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/cmake/modules/AddClipperLibFlags.cmake` & `dune-iga-0.1.8.dev20230628002200/cmake/modules/AddClipperLibFlags.cmake`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/cmake/modules/AddEarCutFlags.cmake` & `dune-iga-0.1.8.dev20230628002200/cmake/modules/AddEarCutFlags.cmake`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/cmake/modules/AddEigenFlags.cmake` & `dune-iga-0.1.8.dev20230628002200/cmake/modules/AddEigenFlags.cmake`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/cmake/modules/AddnLohmannJsonFlags.cmake` & `dune-iga-0.1.8.dev20230628002200/cmake/modules/AddnLohmannJsonFlags.cmake`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/config.h.cmake` & `dune-iga-0.1.8.dev20230628002200/config.h.cmake`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/CMakeLists.txt` & `dune-iga-0.1.8.dev20230628002200/dune/iga/CMakeLists.txt`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/bsplinealgorithms.hh` & `dune-iga-0.1.8.dev20230628002200/dune/iga/bsplinealgorithms.hh`

 * *Files 4% similar despite different names*

```diff
@@ -138,43 +138,35 @@
      */
     static auto basisFunctionDerivatives(ScalarType u, const std::vector<ScalarType>& knots, const int p,
                                          const int derivativeOrder, std::optional<int> spIndex = std::nullopt) {
       assert(spIndex < knots.size() - p - 1);
       const int order = p + 1;
       const int sp    = spIndex ? spIndex.value() : findSpanCorrected(p, u, knots);
       using namespace std::ranges;
-      auto lDiff = transform_view(reverse_view(std::views::counted(begin(knots) + sp + 1 - p, p)),
-                                  [&u](auto& kn) { return u - kn; });
-      auto rDiff = transform_view(std::views::counted(begin(knots) + sp + 1, p), [&u](auto& kn) { return kn - u; });
 
       DynamicMatrixType dN(derivativeOrder + 1, order);
 
       std::vector<ScalarType> left(order);
       std::vector<ScalarType> right(order);
       DynamicMatrixType ndu(order, order);
 
       ndu[0][0] = 1.0;
-      {
-        int j = 0;
-        for (auto lDp = lDiff.begin(); lDp != lDiff.end(); lDp += j + 2, ++j) {
-          ScalarType saved{};
-          for (int r = 0; auto&& rD : rDiff | std::views::take(j + 1)) {
-            const auto& lD = (*lDp);
-            /* Lower triangle */
-            ndu[j + 1][r]  = rD + lD;
-            ScalarType tmp = ndu[r][j] / ndu[j + 1][r];
-            /* Upper triangle */
-            ndu[r++][j + 1] = saved + rD * tmp;
-            saved           = lD * tmp;
-            --lDp;
-          }
-          ndu[j + 1][j + 1] = saved;
+      for (int j = 1; j <= p; j++) {
+        left[j]      = u - knots[sp + 1 - j];
+        right[j]     = knots[sp + j] - u;
+        double saved = 0.0;
+        for (int r = 0; r < j; r++) { /* Lower triangle */
+          ndu[j][r]   = right[r + 1] + left[j - r];
+          double temp = ndu[r][j - 1] / ndu[j][r];
+          ndu[r][j]   = saved + right[r + 1] * temp;
+          saved       = left[j - r] * temp;
         }
+        ndu[j][j] = saved;
       }
-      for (int j = p; j >= 0; --j)
+      for (int j = 0; j <= p; ++j)
         dN[0][j] = ndu[j][p];
 
       // Compute the derivatives
       RowFixedMatrix a;
       a[0].resize(p + 1);
       a[1].resize(p + 1);
       auto& a1Row = a[0];
@@ -185,15 +177,15 @@
         // Compute the k-th derivative
         for (int k = 1; k <= derivativeOrder; ++k) {
           const int rk = r - k;
           const int pk = p - k;
 
           auto& nduRowpk1 = ndu[pk + 1];
           auto& dNcur     = dN[k][r];
-
+          dNcur           = 0.0;
           if (r >= k) {
             a2Row[0] = a1Row[0] / nduRowpk1[rk];
             dNcur    = a2Row[0] * ndu[rk][pk];
           }
 
           const int j1 = (rk >= -1) ? 1 : -rk;
           const int j2 = (r - 1 <= pk) ? k - 1 : p - r;
@@ -209,17 +201,17 @@
           }
           std::swap(a2Row, a1Row);  // Switch rows
         }
       }
       /* Multiply through by the correct factors */
       /* (Eq. [2.9])                             */
       for (int r = p, k = 1; k <= derivativeOrder; ++k) {
-        for (int j = p; j >= 0; --j)
+        for (int j = 0; j <= p; ++j)
           dN[k][j] *= r;
-        r *= p - k;
+        r *= (p - k);
       }
       return dN;
     }
 
    private:
     std::vector<ScalarType> knots_;
     int degree_;
```

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/controlpoint.hh` & `dune-iga-0.1.8.dev20230628002200/dune/iga/controlpoint.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/geometry/closestpointprojection.hh` & `dune-iga-0.1.8.dev20230628002200/dune/iga/geometry/closestpointprojection.hh`

 * *Files 7% similar despite different names*

```diff
@@ -70,34 +70,36 @@
     double domainFractionFactor = 4;
     ctype domainFraction        = 1;
     for (int j = 0; j < dim; ++j)
       domainFraction *= domain[j].size();
     domainFraction /= domainFractionFactor;
     int i;
     auto [oldEnergy, R, H] = energyGradAndHess(u);
+    energyVal              = oldEnergy;
     for (i = 0; i < maxiter; ++i) {
       Dune::FieldVector<ctype, dim> du;
       H.solve(du, -R);
+      Rnorm = R.two_norm();
 
       // if the increment is too large, we tend to overshoot, thus, we limit it to a fraction of the total domain
       ctype duNorm = du.two_norm();
       if (duNorm > domainFraction) du *= domainFraction / duNorm;
 
       const bool isPositiveDef = isPositiveDefiniteInDirection(H, du);
       auto uold                = u;
       oldEnergy                = energy(u);
       u += du;
       if (Utilities::clampToBoundaryAndCheckIfIsAtAllBoundaries(u, domain)) break;
 
-      int testSteps = 10;
+      int testSteps = 20;
       for (int j = 0; j < testSteps; ++j) {
         energyVal = energy(u);
-        if (energyVal > oldEnergy) {
+        if (energyVal > oldEnergy and duNorm > 1e-8) {  // we directly accept very small steps
           u                 = uold;
-          ctype scaleFactor = Dune::power(10.0, j + 1);
+          ctype scaleFactor = Dune::power(2.0, j + 1);
           // If our new step didn't move in an energy-decreasing direction, we have to modify
           if (isPositiveDef) {
             // If our model m(du)= oldEnergy+ dot(R,du) + 0.5*(du^T*H*du) has a positive curvature du^T*Hessian*du, we
             // got
             //  as du the minimizer of the parabola. Since we got energy increase, our model is bad in comparison to
             //  the real energy(u). Thus, we decrease our step size and hope for the best, at least in some (small)
             //  neighborhood our model is good
@@ -120,25 +122,26 @@
       Rnorm = R.two_norm();
       if (Rnorm < tol) break;
     }
     // If we end up at the boundary, and the residual is non-zero, we restart at the opposite domain boundary
     // If this does also not help we return the point at the boundary with smaller energy(distance)
     for (int j = 0; j < dim; ++j)
       u[j] = clampToDomain(u[j], domain[j]);
-    auto uRestart = u;
-    if (Rnorm > tol and not start) {
-      for (int j = 0; j < dim; ++j)
-        if (abs(domain[j].left() - uRestart[j]) < tol)
-          uRestart[j] = domain[j].right();
-        else if (abs(domain[j].right() - uRestart[j]) < tol)
-          uRestart[j] = domain[j].left();
-
-      auto [u2, Rnorm2, energyVal2, gap] = closestPointProjectionByTrustRegion(geo, point, uRestart);
-
-      return energyVal2 > energyVal ? std::make_tuple(u, Rnorm, energyVal, (geo.global(u) - point).two_norm())
-                                    : std::make_tuple(u2, Rnorm2, energyVal2, (geo.global(u2) - point).two_norm());
-    }
+    //    auto uRestart = u;
+    //    if (Rnorm > tol and not start) {
+    //      for (int j = 0; j < dim; ++j)
+    //        if (abs(domain[j].left() - uRestart[j]) < tol)
+    //          uRestart[j] = domain[j].right();
+    //        else if (abs(domain[j].right() - uRestart[j]) < tol)
+    //          uRestart[j] = domain[j].left();
+    //
+    //      auto [u2, Rnorm2, energyVal2, gap] = closestPointProjectionByTrustRegion(geo, point, uRestart);
+    //
+    //      return energyVal2 > energyVal ? std::make_tuple(u, Rnorm, energyVal, (geo.global(u) - point).two_norm())
+    //                                    : std::make_tuple(u2, Rnorm2, energyVal2, (geo.global(u2) -
+    //                                    point).two_norm());
+    //    }
     //    std::cout << "u " << u << " Rnorm " << Rnorm << " energyVal " << energyVal << "geo " << geo.global(u) <<
     //    std::endl;
     return std::make_tuple(u, Rnorm, energyVal, (geo.global(u) - point).two_norm());
   }
 }  // namespace Dune::IGA
```

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/geometry/geohelper.hh` & `dune-iga-0.1.8.dev20230628002200/dune/iga/geometry/geohelper.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/gridcapabilities.hh` & `dune-iga-0.1.8.dev20230628002200/dune/iga/gridcapabilities.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/io/ibra/ibrageometry.hh` & `dune-iga-0.1.8.dev20230628002200/dune/iga/io/ibra/ibrageometry.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/io/ibra/ibrareader.hh` & `dune-iga-0.1.8.dev20230628002200/dune/iga/io/ibra/ibrareader.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/io/igadatacollector.hh` & `dune-iga-0.1.8.dev20230628002200/dune/iga/io/igadatacollector.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsalgorithms.hh` & `dune-iga-0.1.8.dev20230628002200/dune/iga/nurbsalgorithms.hh`

 * *Files 0% similar despite different names*

```diff
@@ -261,28 +261,28 @@
       for (int j = std::max(0, i - t); j <= std::min(p, i); ++j)
         bezalfs[i][j] = inv * Dune::binomial(p, j) * Dune::binomial(t, i - j);
     }
     for (int i = ph2 + 1; i <= ph - 1; ++i)
       for (int j = std::max(0, i - t); j <= std::min(p, i); ++j)
         bezalfs[i][j] = bezalfs[ph - i][p - j];
 
-    double ua = oldData.knotSpans[refinementDirection][0];
     ControlPointNetType newCPv(oldData.controlPoints.strideSizes());
 
     auto oldCPs = oldData.controlPoints;
 
     auto scaleCPWithW = [](const auto& cp) -> ControlPointType { return {.p = cp.w * cp.p, .w = cp.w}; };
     std::ranges::transform(oldCPs.directGetAll(), oldCPs.directGetAll().begin(), scaleCPWithW);
 
     std::vector<ControlPointType> bpts(p + 1), ebpts(ph + 1), nextbpts(p - 1);
 
     NURBSPatchData newData;
     newData.degree = oldData.degree;
     newData.degree[refinementDirection] += t;
     const auto& U = oldData.knotSpans[refinementDirection];
+    double ua     = U[0];
     std::vector<ScalarType> Uh;
     for (int j = 0, i = 0; i < U.size(); ++i)  // insert knot t times for each unique knot
       if (j < U.size()) {
         do {
           Uh.push_back(U[j]);
           ++j;
         } while (j != U.size() && Dune::FloatCmp::eq(U[j - 1], U[j]));
@@ -326,14 +326,15 @@
         return newCPs.get(multiIndex);
       };
       return std::make_pair(oldCurve, newCurve);
     };
 
     for (auto [oldCurve, newCurve] :
          std::ranges::iota_view(0, totalCurvesInPatch) | std::views::transform(newAndOldCurve)) {
+      ua       = U[0];
       int kind = ph + 1;
       int r    = -1;
       int a    = p;
       int b    = p + 1;
       int cind = 1;
 
       newCurve(0) = oldCurve(0);
```

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsbasis.hh` & `dune-iga-0.1.8.dev20230628002200/dune/iga/nurbsbasis.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsgeometry.hh` & `dune-iga-0.1.8.dev20230628002200/dune/iga/nurbsgeometry.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsgrid.hh` & `dune-iga-0.1.8.dev20230628002200/dune/iga/nurbsgrid.hh`

 * *Files 11% similar despite different names*

```diff
@@ -126,23 +126,38 @@
     void globalRefineInDirection(const int dir, const int refinementLevel, bool omitTrim = false) {
       if (refinementLevel == 0) return;
       auto additionalKnots        = generateRefinedKnots(currentPatchRepresentation_.knotSpans, dir, refinementLevel);
       currentPatchRepresentation_ = knotRefinement<dim>(currentPatchRepresentation_, additionalKnots, dir);
       updateStateAfterRefinement(omitTrim);
     }
 
+    void degreeElevateInDirection(const int dir, const int elevationFactor, bool omitTrim = false) {
+      if (elevationFactor == 0) return;
+      currentPatchRepresentation_ = degreeElevate(currentPatchRepresentation_, dir, elevationFactor);
+      updateStateAfterRefinement(omitTrim);
+    }
+
+    void globalDegreeElevate(const int elevationFactor, bool omitTrim = false) {
+      if (elevationFactor == 0) return;
+      oldPatchRepresentation_.push_back(currentPatchRepresentation_);
+      for (int refDirection = 0; refDirection < dim; ++refDirection)
+        currentPatchRepresentation_ = degreeElevate(currentPatchRepresentation_, refDirection, elevationFactor);
+      updateStateAfterRefinement(omitTrim);
+    }
+
     void globalMultiRefine(const int global, const int uDir, const int vDir) {
       this->globalRefine(global, uDir > 0 or vDir > 0);
       this->globalRefineInDirection(0, uDir, vDir > 0);
       this->globalRefineInDirection(1, vDir);
     }
 
     int size(int codim) const { return leafPatches_.get()->front().size(codim); }
 
     const auto& patchData(int i = 0) const { return currentPatchRepresentation_; }
+    const auto& lowerOrderPatchData(int i = 0) const { return oldPatchRepresentation_.at(i); }
 
     bool reportTrimError() const {
       for (const auto& patch : *leafPatches_)
         if (patch.reportTrimError()) return true;
       return false;
     }
 
@@ -208,14 +223,15 @@
    public:
     using EntityVectorType
         = decltype(gridEntityTupleGenerator<NURBSGrid, dimension>(std::make_integer_sequence<int, dimension + 1>()));
     std::unique_ptr<EntityVectorType> entityVector{};
     typename Traits::CollectiveCommunication ccobj;
     NURBSPatchData<(size_t)dim, (size_t)dimworld, ScalarType> coarsestPatchRepresentation_;
     NURBSPatchData<(size_t)dim, (size_t)dimworld, ScalarType> currentPatchRepresentation_;
+    std::vector<NURBSPatchData<(size_t)dim, (size_t)dimworld, ScalarType>> oldPatchRepresentation_;
     std::shared_ptr<std::vector<NURBSPatch<dim, dimworld, ScalarType>>> leafPatches_;
     std::shared_ptr<GridView> leafGridView_;
     std::unique_ptr<NURBSGridLeafIndexSet<const NURBSGrid>> indexSet_;
     std::unique_ptr<IgaIdSet<const NURBSGrid>> idSet_;
     std::optional<std::shared_ptr<TrimData>> trimData_ = std::nullopt;
 
     auto& getPatch() const { return leafPatches_->front(); }
```

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsgridentity.hh` & `dune-iga-0.1.8.dev20230628002200/dune/iga/nurbsgridentity.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsgridindexsets.hh` & `dune-iga-0.1.8.dev20230628002200/dune/iga/nurbsgridindexsets.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsgridleafiterator.hh` & `dune-iga-0.1.8.dev20230628002200/dune/iga/nurbsgridleafiterator.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsgridtraits.hh` & `dune-iga-0.1.8.dev20230628002200/dune/iga/nurbsgridtraits.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsidset.hh` & `dune-iga-0.1.8.dev20230628002200/dune/iga/nurbsidset.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsintersection.hh` & `dune-iga-0.1.8.dev20230628002200/dune/iga/nurbsintersection.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/nurbsleafgridview.hh` & `dune-iga-0.1.8.dev20230628002200/dune/iga/nurbsleafgridview.hh`

 * *Files 2% similar despite different names*

```diff
@@ -126,14 +126,15 @@
           return getPatch().n_fullElement;
         else
           return 0;
       }
     }
 
     const auto &getPatchData(int patchID = 0) const { return *(grid_->leafPatches_->at(patchID).getPatchData()); }
+    const auto &lowerOrderPatchData(int patchID = 0) const { return grid_->lowerOrderPatchData(patchID); }
     const auto &getPatch(int patchID = 0) const { return grid_->leafPatches_->at(patchID); }
 
     template <int cd, Dune::PartitionIteratorType ptype = Dune::All_Partition>
     using LeafIteratorImpl = NURBSGridLeafIterator<cd, ptype, const GridImpl>;
 
     template <int cd>
     typename Codim<cd>::LeafIterator begin() const {
```

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/nurbslocalgeometry.hh` & `dune-iga-0.1.8.dev20230628002200/dune/iga/nurbslocalgeometry.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/nurbspatch.hh` & `dune-iga-0.1.8.dev20230628002200/dune/iga/nurbspatch.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/nurbspatchdata.hh` & `dune-iga-0.1.8.dev20230628002200/dune/iga/nurbspatchdata.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/nurbspatchgeometry.h` & `dune-iga-0.1.8.dev20230628002200/dune/iga/nurbspatchgeometry.h`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/test/CMakeLists.txt` & `dune-iga-0.1.8.dev20230628002200/dune/iga/test/CMakeLists.txt`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/element.ibra` & `dune-iga-0.1.8.dev20230628002200/dune/iga/test/auxiliaryFiles/element.ibra`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/element_trim.ibra` & `dune-iga-0.1.8.dev20230628002200/dune/iga/test/auxiliaryFiles/element_trim.ibra`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/element_trim_xb.ibra` & `dune-iga-0.1.8.dev20230628002200/dune/iga/test/auxiliaryFiles/element_trim_xb.ibra`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/infty_pwh.ibra` & `dune-iga-0.1.8.dev20230628002200/dune/iga/test/auxiliaryFiles/infty_pwh.ibra`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/nurbs_1.ibra` & `dune-iga-0.1.8.dev20230628002200/dune/iga/test/auxiliaryFiles/nurbs_1.ibra`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/pipe_trim.ibra` & `dune-iga-0.1.8.dev20230628002200/dune/iga/test/auxiliaryFiles/pipe_trim.ibra`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/plate_quarter.ibra` & `dune-iga-0.1.8.dev20230628002200/dune/iga/test/auxiliaryFiles/plate_quarter.ibra`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/schale_trim.ibra` & `dune-iga-0.1.8.dev20230628002200/dune/iga/test/auxiliaryFiles/schale_trim.ibra`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/shell-hole.ibra` & `dune-iga-0.1.8.dev20230628002200/dune/iga/test/auxiliaryFiles/shell-hole.ibra`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/shell.ibra` & `dune-iga-0.1.8.dev20230628002200/dune/iga/test/auxiliaryFiles/shell.ibra`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/surface-hole.ibra` & `dune-iga-0.1.8.dev20230628002200/dune/iga/test/auxiliaryFiles/surface-hole.ibra`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/test/auxiliaryFiles/surface-multihole.ibra` & `dune-iga-0.1.8.dev20230628002200/dune/iga/test/auxiliaryFiles/surface-multihole.ibra`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/test/gridTests.cc` & `dune-iga-0.1.8.dev20230628002200/dune/iga/test/gridTests.cc`

 * *Files 21% similar despite different names*

```diff
@@ -292,55 +292,61 @@
   auto circle          = makeCircularArc(r);
   auto nurbsPatchData  = makeSurfaceOfRevolution(circle, {R, 0, 0}, {0, 1, 0}, 360.0);
   nurbsPatchData       = degreeElevate(nurbsPatchData, 0, 1);
   nurbsPatchData       = degreeElevate(nurbsPatchData, 1, 2);
   auto additionalKnots = std::vector<double>(1);
   additionalKnots[0]   = 0.1;
   nurbsPatchData       = knotRefinement<2>(nurbsPatchData, additionalKnots, 1);
+  for (int refDirection = 0; refDirection < 2; ++refDirection)
+    nurbsPatchData = degreeElevate(nurbsPatchData, refDirection, 1);
 
   IGA::NURBSGrid<2, 3> grid(nurbsPatchData);
   grid.globalRefine(1);
   grid.globalRefineInDirection(1, 1);
   grid.globalRefineInDirection(0, 2);
+  grid.globalDegreeElevate(2);
 
   auto gridView = grid.leafGridView();
 
   const int subSampling = 2;
   Dune::RefinementIntervals refinementIntervals1(subSampling);
   SubsamplingVTKWriter vtkWriter(gridView, refinementIntervals1);
   vtkWriter.write("NURBSGridTest-SurfaceRevolutionFLAT");
 
   TestSuite test;
   Dune::GeometryChecker<IGA::NURBSGrid<2UL, 3UL>> geometryChecker;
-  //  geometryChecker.checkGeometry(gridView);
+  geometryChecker.checkGeometry(gridView);
   Dune::checkIndexSet(grid, gridView, std::cout);
 
   double area = 0.0;
   for (auto&& ele : elements(gridView)) {
     area += ele.geometry().volume();
   }
   const double pi                        = std::numbers::pi_v<double>;
   const double referenceTorusSurfaceArea = 4.0 * pi * pi * r * R;
-  test.check(area - referenceTorusSurfaceArea < 1e-4, "The integrated area of the torus hyperSurface is wrong!");
+  test.check(area - referenceTorusSurfaceArea < 1e-4)
+      << "The integrated area of the torus surface is wrong! Expected: " << referenceTorusSurfaceArea
+      << " Computed: " << area;
 
   double gaussBonnet = 0.0;
   for (auto& ele : elements(gridView)) {
     const auto rule
-        = Dune::QuadratureRules<double, 2>::rule(ele.type(), 2 * (*std::ranges::max_element(nurbsPatchData.degree)));
+        = Dune::QuadratureRules<double, 2>::rule(ele.type(), 2 * (*std::ranges::max_element(grid.patchData().degree)));
     for (auto& gp : rule) {
       const auto Kinc = ele.geometry().impl().gaussianCurvature(gp.position());
       const auto Kmax = 1 / (r * (R + r));
       const auto Kmin = -1 / (r * (R - r));
-      test.check(Kinc < Kmax && Kinc > Kmin, "The Gaussian curvature should be within bounds");
+      test.check(Kinc < Kmax && Kinc > Kmin)
+          << "The Gaussian curvature should be within bounds " << Kmin << " < " << Kinc << " < " << Kmax << std::endl;
       gaussBonnet += Kinc * gp.weight() * ele.geometry().integrationElement(gp.position());
     }
   }
 
-  test.check(std::abs(gaussBonnet) < 1e-5,
-             "Gauss-Bonnet theorem dictates a vanishing integrated Gaussian curvature for the torus!");
+  test.check(std::abs(gaussBonnet) < 1e-5)
+      << "Gauss-Bonnet theorem dictates a vanishing integrated Gaussian curvature for the torus! It is " << gaussBonnet;
   checkEntityLifetime(gridView, gridView.size(0));
 
   for (auto&& elegeo : elements(gridView) | std::views::transform([](const auto& ele) { return ele.geometry(); }))
     checkJacobians(elegeo);
 
   checkIterators(gridView);
 
@@ -506,14 +512,15 @@
          //          {{.p = {rad*2, 0,   0}, .w =       1},  {.p = {rad*2, l*2,   0}, .w = 1     }},
          {{.p = {rad, 0, 0}, .w = 1}, {.p = {rad, l, 0}, .w = 1}}};
   nurbsPatchData.degree = order;
 
   IGA::NURBSGrid<dim, dimworld> grid(nurbsPatchData);
   //  grid.globalRefine(1);
   grid.globalRefineInDirection(0, 2);
+  grid.globalDegreeElevate(2);
   //  grid.globalRefineInDirection(1, 3);
   auto gridView        = grid.leafGridView();
   const auto& indexSet = gridView.indexSet();
 
   TestSuite test;
 
   //! Test code for VTKWriter, please uncomment to inspect the remaining errors
@@ -524,16 +531,17 @@
   using GridView = decltype(gridView);
   Dune::Functions::NurbsBasis<GridView> basis(gridView, gridView.impl().getPatchData());
 
   // Test open knot vectors
   std::cout << "  Testing B-spline basis with open knot vectors" << std::endl;
 
   {
+    using namespace Functions::BasisFactory;
     // Check basis created via its constructor
-    Functions::NurbsBasis<GridView> basis2(gridView, gridView.impl().getPatchData());
+    Functions::NurbsBasis<GridView> basis2(gridView, nurbs());
     test.subTest(checkBasis(basis2, EnableContinuityCheck(), EnableContinuityCheck()));
   }
 
   {
     // Check basis created via its constructor
     Functions::NurbsBasis<GridView> basis2(gridView);
     test.subTest(checkBasis(basis2, EnableContinuityCheck(), EnableContinuityCheck()));
@@ -548,14 +556,22 @@
 
   {
     // Check whether a B-Spline basis can be combined with other bases.
     using namespace Functions::BasisFactory;
     auto basis2 = makeBasis(gridView, power<2>(nurbs()));
     test.subTest(checkBasis(basis2, EnableContinuityCheck(), EnableContinuityCheck()));
   }
+
+  {
+    grid.globalDegreeElevate(1);
+    auto gridViewNew = grid.leafGridView();
+    // Check lower order basis created via its constructor
+    Functions::NurbsBasis<GridView> basis2(gridViewNew, gridViewNew.impl().lowerOrderPatchData());
+    test.subTest(checkBasis(basis2, EnableContinuityCheck(), EnableContinuityCheck()));
+  }
   return test;
 }
 
 auto testBsplineBasisFunctions() {
   std::vector<double> knots = {0, 0, 0, 0.5, 0.5, 2, 2, 3, 3, 3};
   int degree                = 2;
   TestSuite test;
@@ -894,59 +910,64 @@
   return true;
 };
 
 template <typename C>
 bool checkIfZero(const C& v) {
   for (auto& vi : v) {
     if constexpr (std::is_arithmetic_v<std::remove_cvref_t<decltype(vi)>>) {
-      if (Dune::FloatCmp::ne(vi, 0.0)) return false;
+      if (std::abs(vi) > 1e-13) return false;
     } else {
       return checkIfZero(vi);
     }
   }
   return true;
 };
 
 auto testPlate() {
   constexpr int gridDim                = 2;
-  constexpr auto dimworld              = 2;
+  constexpr auto dimworld              = 3;
   const std::array<int, gridDim> order = {2, 2};
   TestSuite t;
 
   const std::array<std::vector<double>, gridDim> knotSpans = {{{0, 0, 0, 1, 1, 1}, {0, 0, 0, 1, 1, 1}}};
 
   using ControlPoint = Dune::IGA::NURBSPatchData<gridDim, dimworld>::ControlPointType;
 
   const std::vector<std::vector<ControlPoint>> controlPoints
-      = {{{.p = {0, 0}, .w = 1}, {.p = {0.5, 0}, .w = 1}, {.p = {1, 0}, .w = 1}},
-         {{.p = {0, 0.5}, .w = 1}, {.p = {0.5, 0.5}, .w = 1}, {.p = {1, 0.5}, .w = 1}},
-         {{.p = {0, 1}, .w = 1}, {.p = {0.5, 1}, .w = 1}, {.p = {1, 1}, .w = 1}}};
+      = {{{.p = {0, 0, 0}, .w = 1}, {.p = {0.5, 0, 0}, .w = 1}, {.p = {1, 0, 0}, .w = 1}},
+         {{.p = {0, 0.5, 0}, .w = 1}, {.p = {0.5, 0.5, 0}, .w = 3}, {.p = {1, 0.5, 0}, .w = 1}},
+         {{.p = {0, 1, 0}, .w = 1}, {.p = {0.5, 1, 0}, .w = 1}, {.p = {1, 1, 0}, .w = 1}}};
 
   std::array<int, gridDim> dimsize = {(int)(controlPoints.size()), (int)(controlPoints[0].size())};
 
   auto controlNet = Dune::IGA::NURBSPatchData<gridDim, dimworld>::ControlPointNetType(dimsize, controlPoints);
   using Grid      = Dune::IGA::NURBSGrid<gridDim, dimworld>;
 
   Dune::IGA::NURBSPatchData<gridDim, dimworld> patchData;
   patchData.knotSpans     = knotSpans;
   patchData.degree        = order;
   patchData.controlPoints = controlNet;
   auto grid               = std::make_shared<Grid>(patchData);
-  grid->globalRefine(0);
+  //  grid->globalRefine(1);
+  //
+  grid->globalDegreeElevate(4);
+  //  grid->globalRefine(1);
   auto gridView = grid->leafGridView();
   Dune::GeometryChecker<decltype(grid)> geometryChecker;
   geometryChecker.checkGeometry(gridView);
   Dune::checkIndexSet(*grid, gridView, std::cout);
 
   checkEntityLifetime(gridView, gridView.size(0));
-
+  std::cout << "checkJacobians Start" << std::endl;
   for (auto&& elegeo : elements(gridView) | std::views::transform([](const auto& ele) { return ele.geometry(); }))
     checkJacobians(elegeo);
-
+  std::cout << "checkJacobians End" << std::endl;
+  std::cout << "checkIterators Start" << std::endl;
   checkIterators(gridView);
+  std::cout << "checkIterators End" << std::endl;
   auto basis     = Dune::Functions::BasisFactory::makeBasis(gridView, Dune::Functions::BasisFactory::nurbs());
   auto localView = basis.localView();
   std::vector<Dune::FieldVector<double, 1>> N;
   std::vector<Dune::FieldVector<double, 1>> ddNi02;
   std::vector<Dune::FieldVector<double, 1>> ddNi20;
   std::vector<Dune::FieldVector<double, 1>> ddNi11;
   std::vector<Dune::FieldMatrix<double, 1, 2>> dN;
@@ -954,51 +975,271 @@
     localView.bind(element);
     const auto& fe     = localView.tree().finiteElement();
     auto& localBasis   = fe.localBasis();
     auto referenceEle  = referenceElement(element);
     auto geo           = element.geometry();
     auto localGeometry = referenceEle.template geometry<0>(0);
     for (int i = 0; i < localGeometry.corners(); ++i) {
-      auto local  = localGeometry.corner(i);
-      auto global = geo.global(local);
-      auto J      = geo.jacobianTransposed(local);
-      auto J2     = geo.impl().secondDerivativeOfPosition(local);
-
-      t.check(checkIfFinite(global));
-      t.check(checkIfFinite(J));
-      t.check(checkIfZero(J2));  // J2 should be zero since the grid is linearly parametrized
-
-      localBasis.evaluateFunction(local, N);
-      localBasis.evaluateJacobian(local, dN);
-      localBasis.partial({2, 0}, local, ddNi20);
-      localBasis.partial({1, 1}, local, ddNi11);
-      localBasis.partial({0, 2}, local, ddNi02);
-
-      t.check(checkIfFinite(N));
-      t.check(checkIfFinite(dN));
-      t.check(checkIfFinite(ddNi20));
-      t.check(checkIfFinite(ddNi11));
-      t.check(checkIfFinite(ddNi02));
+      auto localV = localGeometry.corner(i);
+      auto global = geo.global(localV);
+      auto localT = geo.local(global);
+      for (int j = 0; j < gridDim; ++j) {
+        t.check(std::abs(localV[j] - localT[j]) < 1e-14)
+            << "Dune::FloatCmp:eq(localV[i],localT[i]) failed Local " << localV << " Calculated: " << localT;
+      }
+      auto J  = geo.jacobianTransposed(localV);
+      auto J2 = geo.impl().secondDerivativeOfPosition(localV);
+
+      t.check(checkIfFinite(global)) << "checkIfFinite(global) failed";
+      t.check(checkIfFinite(J)) << "checkIfFinite(J) failed";
+      //      t.check(checkIfZero(J2))<<"checkIfZero(J2) "<<J2;  // J2 should be zero since the grid is linearly
+      //      parametrized
+      t.check(std::abs(J2[0][2]) < 1e-14)
+          << "checkIfZero(J2[0][2])" << J2;  // The grid is plane, therefore, the curvature should be also inplane
+      t.check(std::abs(J2[1][2]) < 1e-14)
+          << "checkIfZero(J2[1][2])" << J2;  // The grid is plane, therefore, the curvature should be also inplane
+
+      localBasis.evaluateFunction(localV, N);
+      localBasis.evaluateJacobian(localV, dN);
+      localBasis.partial({2, 0}, localV, ddNi20);
+      localBasis.partial({1, 1}, localV, ddNi11);
+      localBasis.partial({0, 2}, localV, ddNi02);
+
+      t.check(checkIfFinite(N)) << "checkIfFinite(N) failed";
+      t.check(checkIfFinite(dN)) << "checkIfFinite(dN) failed";
+      t.check(checkIfFinite(ddNi20)) << "checkIfFinite(ddNi20) failed";
+      t.check(checkIfFinite(ddNi11)) << "checkIfFinite(ddNi11) failed";
+      t.check(checkIfFinite(ddNi02)) << "checkIfFinite(ddNi02) failed";
     }
   }
   t.subTest(checkUniqueEdges(gridView));
   return t;
 }
 
+auto testCurveHigherOrderDerivatives() {
+  constexpr auto gridDim               = 1;
+  constexpr auto dimworld              = 3;
+  const std::array<int, gridDim> order = {2};
+  TestSuite t;
+  // parameters
+
+  const std::array<std::vector<double>, gridDim> knotSpans = {{{0, 0, 0, 0.5, 1, 1, 1}}};
+  //  const std::array<std::vector<double>, dim> knotSpans = {{{ 0, 0, 1,1}}};
+  using ControlPoint = Dune::IGA::NURBSPatchData<gridDim, dimworld>::ControlPointType;
+
+  const std::vector<ControlPoint> controlPoints
+      = {{.p = {0.086956521739130, -0.434782608695652, 0}, .w = 11.5},
+         {.p = {0.200000000000000, 5.400000000000000, 0.200000000000000}, .w = 5},
+         {.p = {1.857142857142857, 0.142857142857143, 0}, .w = 7},
+         {.p = {3.714285714285714, 0.285714285714286, 2.000000000000000}, .w = 3.5}};
+
+  std::array<int, gridDim> dimsize = {static_cast<int>(controlPoints.size())};
+  auto controlNet = Dune::IGA::NURBSPatchData<gridDim, dimworld>::ControlPointNetType(dimsize, controlPoints);
+
+  Dune::IGA::NURBSPatchData<gridDim, dimworld> patchData;
+  patchData.knotSpans     = knotSpans;
+  patchData.degree        = order;
+  patchData.controlPoints = controlNet;
+
+  std::vector<Dune::FieldVector<double, 3>> expectedControlPoints
+      = {{0.086956521739130, -0.434782608695652, 0},
+         {0.121212121212121, 1.333333333333333, 0.060606060606061},
+         {0.320000000000000, 3.120000000000000, 0.120000000000000},
+         {0.727272727272727, 3.727272727272727, 0.136363636363636},
+         {1.538461538461539, 1.153846153846154, 0.038461538461538},
+         {1.920000000000000, 0.506666666666667, 0.200000000000000},
+         {2.476190476190476, 0.190476190476190, 0.666666666666667},
+         {3.714285714285714, 0.285714285714286, 2.000000000000000}};
+
+  std::vector<double> expectedWeights = {11.5, 8.25, 6.25, 5.5, 6.5, 6.25, 5.25, 3.5};
+
+  auto patchDataP = std::make_shared<Dune::IGA::NURBSPatchData<gridDim, dimworld>>(patchData);
+
+  NURBSPatchGeometry<gridDim, dimworld> geo(patchDataP);
+  double vol  = geo.volume();
+  int samples = 20;
+  std::vector<Dune::FieldVector<double, 3>> evaluatedPoints;
+  std::vector<Dune::FieldMatrix<double, 1, 3>> evaluatedJacobians;
+  std::vector<Dune::FieldMatrix<double, 1, 3>> evaluatedHessians;
+
+  for (int i = 0; i < samples + 1; ++i) {
+    const Dune::FieldVector<double, 1> u = {i / static_cast<double>(samples)};
+    std::cout << geo.global(u) << std::endl;
+    evaluatedPoints.push_back(geo.global(u));
+    const auto [pos, J, H] = geo.zeroFirstAndSecondDerivativeOfPosition(u);
+    evaluatedHessians.push_back(H);
+    evaluatedJacobians.push_back(geo.jacobianTransposed(u));
+  }
+
+  for (int i = 1; i < 5; ++i) {
+    auto patchDataN  = degreeElevate(patchData, 0, i);
+    auto patchDataPN = std::make_shared<Dune::IGA::NURBSPatchData<gridDim, dimworld>>(patchDataN);
+    NURBSPatchGeometry<gridDim, dimworld> geo2(patchDataPN);
+    //    t.check(Dune::FloatCmp::eq(geo2.volume(),vol,1e-10))<<"vol "<<vol<<" is "<<geo2.volume();
+    for (int j = 0; j < samples + 1; ++j) {
+      const Dune::FieldVector<double, 1> u = {j / static_cast<double>(samples)};
+      t.check(Dune::FloatCmp::eq(geo2.global(u), evaluatedPoints[j], 1e-10))
+          << "evaluatedPoints[i] " << evaluatedPoints[j] << " is " << geo2.global(u);
+      const auto [pos, J, H] = geo.zeroFirstAndSecondDerivativeOfPosition(u);
+      t.check(Dune::FloatCmp::eq(geo2.jacobianTransposed(u)[0], evaluatedJacobians[j][0], 1e-10))
+          << "evaluatedJacobians[i] " << evaluatedJacobians[j] << " is " << geo2.jacobianTransposed(u);
+      t.check(Dune::FloatCmp::eq(H[0], evaluatedHessians[j][0], 1e-10))
+          << "evaluatedJacobians[i] " << evaluatedHessians[j] << " is " << H;
+    }
+  }
+
+  patchData = degreeElevate(patchData, 0, 2);
+  t.check(expectedControlPoints.size() == patchData.controlPoints.directGetAll().size())
+      << "Size mismatch " << expectedControlPoints.size() << "is " << patchData.controlPoints.directGetAll().size();
+  t.check(expectedWeights.size() == patchData.controlPoints.directGetAll().size())
+      << "Size mismatch" << expectedWeights.size() << "is " << patchData.controlPoints.directGetAll().size();
+  t.check(patchData.degree[0] == 4) << "Size mismatch";
+
+  std::cout << "Knots:" << std::endl;
+  for (int i = 0; auto kn : patchData.knotSpans[0]) {
+    std::cout << kn << " ";
+  }
+  std::cout << std::endl;
+  for (int i = 0; auto cp : patchData.controlPoints.directGetAll()) {
+    std::cout << cp.p << " w: " << cp.w << std::endl;
+    t.check(Dune::FloatCmp::eq(cp.p, expectedControlPoints[i], 1e-10))
+        << "expectedControlPoints[i] " << expectedControlPoints[i] << " is " << cp.p;
+    t.check(Dune::FloatCmp::eq(cp.w, expectedWeights[i], 1e-10))
+        << "expectedWeights[i] " << expectedWeights[i] << " is " << cp.w;
+    ++i;
+  }
+
+  return t;
+}
+
+auto testSurfaceHigherOrderDerivatives() {
+  TestSuite t;
+
+  constexpr int gridDim                = 2;
+  constexpr auto dimworld              = 3;
+  const std::array<int, gridDim> order = {2, 2};
+
+  const std::array<std::vector<double>, gridDim> knotSpans = {{{0, 0, 0, 1, 1, 1}, {0, 0, 0, 1, 1, 1}}};
+
+  using ControlPoint = Dune::IGA::NURBSPatchData<gridDim, dimworld>::ControlPointType;
+
+  //  const std::vector<std::vector<ControlPoint>> controlPoints
+  //      = {{{.p = {0, 0,0}, .w = 1}, {.p = {0, 0.5,0}, .w = 1}},
+  //         {{.p = {0.5, 0,0}, .w = 1}, {.p = {0.5, 0.5,0}, .w = 1}},
+  //         {{.p = {1, 0,0}, .w = 1}, {.p = {1, 0.5,0}, .w = 1}}};
+
+  const std::vector<std::vector<ControlPoint>> controlPoints
+      = {{{.p = {0, 0, 0}, .w = 1}, {.p = {0, 0.5, 0}, .w = 1}, {.p = {0, 1, 0}, .w = 1}},
+         {{.p = {0.5, 0, 0}, .w = 1}, {.p = {0.5, 0.5, 0}, .w = 3}, {.p = {0.5, 1, 0}, .w = 1}},
+         {{.p = {1, 0, 0}, .w = 1}, {.p = {1, 0.5, 0}, .w = 1}, {.p = {1, 1, 0}, .w = 1}}};
+
+  //  const std::vector<std::vector<ControlPoint>> controlPoints
+  //      = {{{.p = {0, 0,0}, .w = 1}, {.p = {}, .w = 1}, {.p = {}, .w = 1}},
+  //         {{.p = {}, .w = 1}, {.p = {}, .w = 1}, {.p = {}, .w = 1}},
+  //         {{.p = {}, .w = 1}, {.p = {}, .w = 1}, {.p = {}, .w = 1}}};
+  std::array<int, gridDim> dimsize = {(int)(controlPoints.size()), (int)(controlPoints[0].size())};
+
+  auto controlNet = Dune::IGA::NURBSPatchData<gridDim, dimworld>::ControlPointNetType(dimsize, controlPoints);
+
+  Dune::IGA::NURBSPatchData<gridDim, dimworld> patchData;
+  patchData.knotSpans     = knotSpans;
+  patchData.degree        = order;
+  patchData.controlPoints = controlNet;
+  auto additionalKnots    = std::vector<double>(1);
+  additionalKnots[0]      = 0.5;
+  patchData               = knotRefinement<2>(patchData, additionalKnots, 1);
+  //  const double R       = 2.0;
+  //  const double r       = 1.0;
+  //  auto circle          = makeCircularArc(r);
+  //  auto patchData  = makeSurfaceOfRevolution(circle, {R, 0, 0}, {0, 1, 0}, 10.0);
+  //  patchData       = degreeElevate(patchData, 0, 2);
+  //  patchData       = degreeElevate(patchData, 1, 2);
+  //  auto additionalKnots = std::vector<double>(1);
+  ////  additionalKnots[0]   = 0.1;
+  ////  patchData       = knotRefinement<2>(patchData, additionalKnots, 1);
+
+  auto patchDataP = std::make_shared<Dune::IGA::NURBSPatchData<gridDim, dimworld>>(patchData);
+
+  NURBSPatchGeometry<gridDim, dimworld> geo(patchDataP);
+  double vol  = geo.volume();
+  int samples = 2;
+  std::vector<Dune::FieldVector<double, 3>> evaluatedPoints;
+  std::vector<Dune::FieldMatrix<double, 2, 3>> evaluatedJacobians;
+  std::vector<Dune::FieldMatrix<double, 3, 3>> evaluatedHessians;
+  //  std::vector<double> evaluatedJacobians;
+  for (int i = 0; i < samples + 1; ++i) {
+    for (int j = 0; j < samples + 1; ++j) {
+      const Dune::FieldVector<double, 2> u = {i / static_cast<double>(samples), j / static_cast<double>(samples)};
+      std::cout << geo.global(u) << std::endl;
+      evaluatedPoints.push_back(geo.global(u));
+      const auto [pos, J, H] = geo.zeroFirstAndSecondDerivativeOfPosition(u);
+      evaluatedHessians.push_back(H);
+      evaluatedJacobians.push_back(geo.jacobianTransposed(u));
+      //    evaluatedJacobians.push_back(geo.impl()(u));
+    }
+  }
+
+  for (int i = 1; i < 2; ++i) {
+    std::cout << "degree elevate " << i << std::endl;
+    //    auto patchDataN= degreeElevate(patchData,0,i);
+    auto patchDataN = degreeElevate(patchData, 1, i);
+    std::cout << "KnotsU:" << std::endl;
+    for (auto kn : patchDataN.knotSpans[0])
+      std::cout << kn << " ";
+    std::cout << "KnotsV:" << std::endl;
+    for (auto kn : patchDataN.knotSpans[1])
+      std::cout << kn << " ";
+    auto patchDataPN = std::make_shared<Dune::IGA::NURBSPatchData<gridDim, dimworld>>(patchDataN);
+    for (auto cp : patchDataN.controlPoints.directGetAll())
+      std::cout << cp.p << " w: " << cp.w << std::endl;
+    NURBSPatchGeometry<gridDim, dimworld> geo2(patchDataPN);
+    //    t.check(Dune::FloatCmp::eq(geo2.volume(),vol,1e-10))<<"vol "<<vol<<" is "<<geo2.volume();
+    for (int j = 0, index = 0; j < samples + 1; ++j) {
+      for (int k = 0; k < samples + 1; ++k) {
+        const Dune::FieldVector<double, 2> u = {j / static_cast<double>(samples), k / static_cast<double>(samples)};
+        t.check(Dune::FloatCmp::eq(geo2.global(u), evaluatedPoints[index], 1e-10))
+            << "evaluatedPoints[i] " << evaluatedPoints[index] << " is " << geo2.global(u);
+        const auto [pos, J, H] = geo.zeroFirstAndSecondDerivativeOfPosition(u);
+        t.check((geo2.jacobianTransposed(u)[0] - evaluatedJacobians[index][0]).two_norm() < 1e-8)
+            << "evaluatedJacobians[i][0] \n"
+            << evaluatedJacobians[index] << "\n is \n"
+            << geo2.jacobianTransposed(u)
+            << "\n norm:" << (geo2.jacobianTransposed(u)[0] - evaluatedJacobians[index][0]).two_norm();
+        t.check((geo2.jacobianTransposed(u)[1] - evaluatedJacobians[index][1]).two_norm() < 1e-8)
+            << "evaluatedJacobians[i][1] \n"
+            << evaluatedJacobians[index] << "\n is \n"
+            << geo2.jacobianTransposed(u)
+            << "\n norm:" << (geo2.jacobianTransposed(u)[1] - evaluatedJacobians[index][1]).two_norm();
+        t.check(Dune::FloatCmp::eq(H[0], evaluatedHessians[index][0], 1e-10))
+            << "evaluatedJacobians[i][0] " << evaluatedHessians[index][0] << " is " << H;
+        t.check(Dune::FloatCmp::eq(H[1], evaluatedHessians[index][1], 1e-10))
+            << "evaluatedJacobians[i][1] " << evaluatedHessians[index] << " is " << H;
+        t.check(Dune::FloatCmp::eq(H[2], evaluatedHessians[index][2], 1e-10))
+            << "evaluatedJacobians[i][2] " << evaluatedHessians[index] << " is " << H;
+        ++index;
+      }
+    }
+  }
+
+  return t;
+}
+
 int main(int argc, char** argv) try {
   // Initialize MPI, if necessary
   MPIHelper::instance(argc, argv);
   TestSuite t;
   t.subTest(test3DGrid());
   t.subTest(testNURBSGridCurve());
   t.subTest(testPlate());
   testNurbsGridCylinder();
   t.subTest(testTorusGeometry());
-
+  std::cout << " t.subTest(testNurbsBasis());" << std::endl;
   t.subTest(testNurbsBasis());
+  t.subTest(testCurveHigherOrderDerivatives());
+  t.subTest(testSurfaceHigherOrderDerivatives());
 
   gridCheck();
   t.subTest(testBsplineBasisFunctions());
 
   t.report();
 
   return t.exit();
```

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/test/trimmedGridTests.cc` & `dune-iga-0.1.8.dev20230628002200/dune/iga/test/trimmedGridTests.cc`

 * *Files 4% similar despite different names*

```diff
@@ -99,15 +99,15 @@
   for (int i = 0; i < 2; ++i)
     t.check(Dune::FloatCmp::eq(geometry.corner(i), expectedCorners[i]));
 
   return t;
 }
 
 auto testPatchGeometrySurface() {
-  TestSuite t;
+  TestSuite t("", TestSuite::ThrowPolicy::AlwaysThrow);
 
   const auto dim                   = 2;
   const auto dimworld              = 3;
   const std::array<int, dim> order = {2, 2};
 
   const std::array<std::vector<double>, dim> knotSpans = {{{0, 0, 0, 1, 1, 1}, {0, 0, 0, 1, 1, 1}}};
 
@@ -127,49 +127,53 @@
   patchData.degree        = order;
   patchData.controlPoints = controlNet;
 
   // Make Geometry
   NURBSPatchGeometry<dim, dimworld> geometry(std::make_shared<Dune::IGA::NURBSPatchData<dim, dimworld>>(patchData));
 
   auto p1 = geometry.global(FieldVector<double, 2>{0.5, 0.5});
-  t.check(Dune::FloatCmp::eq(p1, {1.0, 1.0, 0.75}));
+  t.check(Dune::FloatCmp::eq(p1, {1.0, 1.0, 0.75})) << "p1 check failed " << p1;
 
   auto p2 = geometry.global(FieldVector<double, 2>{0, 0});
-  t.check(Dune::FloatCmp::eq(p2, {0, 0, 1}));
+  t.check(Dune::FloatCmp::eq(p2, {0, 0, 1})) << "p2 check failed " << p2;
 
   auto p3 = geometry.global(FieldVector<double, 2>{0, 1});
-  t.check(Dune::FloatCmp::eq(p3, {2, 0, 2}));
+  t.check(Dune::FloatCmp::eq(p3, {2, 0, 2})) << "p3 check failed " << p3;
 
   // Check derivative
   auto jc1 = geometry.jacobianTransposed({0.5, 0.5});
-  t.check(Dune::FloatCmp::eq(jc1[0], {0.0, 2.0, 0.5}));
-  t.check(Dune::FloatCmp::eq(jc1[1], {2.0, 0.0, 0.5}));
+  t.check(Dune::FloatCmp::eq(jc1[0], {0.0, 2.0, 0.5})) << "jc1[0] check failed " << jc1[0];
+  t.check(Dune::FloatCmp::eq(jc1[1], {2.0, 0.0, 0.5})) << "jc1[1] check failed " << jc1[1];
 
   // Check local function
   auto u1 = geometry.local({1.0, 1.0, 0.75});
-  t.check(Dune::FloatCmp::eq(u1, {0.5, 0.5}));
+  t.check(Dune::FloatCmp::eq(u1, {0.5, 0.5})) << "u1 check failed " << u1;
 
   auto u2 = geometry.local({2, 0, 2});
-  t.check(Dune::FloatCmp::eq(u2, {0, 1}));
+  t.check(Dune::FloatCmp::eq(u2, {0, 1})) << "u2 check failed " << u2;
 
   // Check corners
   t.check(geometry.corners() == 4);
 
   std::array<FieldVector<double, 3>, 4> expectedCorners{
       {FieldVector<double, 3>{0, 0, 1}, FieldVector<double, 3>{0, 2, 1}, FieldVector<double, 3>{2, 0, 2},
        FieldVector<double, 3>{2, 2, 2}}};
   for (int i = 0; i < 4; ++i)
-    t.check(Dune::FloatCmp::eq(geometry.corner(i), expectedCorners[i]));
+    t.check(Dune::FloatCmp::eq(geometry.corner(i), expectedCorners[i]))
+        << "u2 check failed " << geometry.corner(i) << " Expected: " << expectedCorners[i];
 
   // Check domain
-  t.check(Dune::FloatCmp::eq(geometry.domain()[0].left(), 0.0));
-  t.check(Dune::FloatCmp::eq(geometry.domain()[0].right(), 1.0));
+  t.check(Dune::FloatCmp::eq(geometry.domain()[0].left(), 0.0))
+      << "Domaincheck failed check failed " << geometry.domain()[0].left();
+  t.check(Dune::FloatCmp::eq(geometry.domain()[0].right(), 1.0))
+      << "Domaincheck failed check failed " << geometry.domain()[0].right();
 
   // Check domain midpoint
-  t.check(Dune::FloatCmp::eq(geometry.domainMidPoint()[0], 0.5));
+  t.check(Dune::FloatCmp::eq(geometry.domainMidPoint()[0], 0.5))
+      << "Domaincheck failed check failed " << geometry.domainMidPoint()[0];
 
   return t;
 }
 
 auto testIbraReader() {
   TestSuite t;
```

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/trim/nurbstrimboundary.hh` & `dune-iga-0.1.8.dev20230628002200/dune/iga/trim/nurbstrimboundary.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/trim/nurbstrimmer.hh` & `dune-iga-0.1.8.dev20230628002200/dune/iga/trim/nurbstrimmer.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/trim/trimmedelementrepresentation.hh` & `dune-iga-0.1.8.dev20230628002200/dune/iga/trim/trimmedelementrepresentation.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/utils/concepts.hh` & `dune-iga-0.1.8.dev20230628002200/dune/iga/utils/concepts.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/utils/fillquadraturerule.hh` & `dune-iga-0.1.8.dev20230628002200/dune/iga/utils/fillquadraturerule.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/utils/igahelpers.hh` & `dune-iga-0.1.8.dev20230628002200/dune/iga/utils/igahelpers.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/utils/linearalgebra.hh` & `dune-iga-0.1.8.dev20230628002200/dune/iga/utils/linearalgebra.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/iga/utils/mdnet.hh` & `dune-iga-0.1.8.dev20230628002200/dune/iga/utils/mdnet.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/python/iga/boundarypatch.hh` & `dune-iga-0.1.8.dev20230628002200/dune/python/iga/boundarypatch.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/python/iga/grid.hh` & `dune-iga-0.1.8.dev20230628002200/dune/python/iga/grid.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/python/iga/nurbspatchdata.hh` & `dune-iga-0.1.8.dev20230628002200/dune/python/iga/nurbspatchdata.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/python/test/poisson.py` & `dune-iga-0.1.8.dev20230628002200/dune/python/test/poisson.py`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/python/test/readGrid.py` & `dune-iga-0.1.8.dev20230628002200/dune/python/test/readGrid.py`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/dune/python/test/setpath.py.in` & `dune-iga-0.1.8.dev20230628002200/dune/python/test/setpath.py.in`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/python/dune/iga/CMakeLists.txt` & `dune-iga-0.1.8.dev20230628002200/python/dune/iga/CMakeLists.txt`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/python/dune/iga/_boundarypatch.py` & `dune-iga-0.1.8.dev20230628002200/python/dune/iga/_boundarypatch.py`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/python/dune/iga/_igagrids.py` & `dune-iga-0.1.8.dev20230628002200/python/dune/iga/_igagrids.py`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/python/dune/iga/_nurbsAlgorithms.py` & `dune-iga-0.1.8.dev20230628002200/python/dune/iga/_nurbsAlgorithms.py`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/python/dune/iga/_nurbspatchdata.py` & `dune-iga-0.1.8.dev20230628002200/python/dune/iga/_nurbspatchdata.py`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/python/dune/iga/basis/__init__.py` & `dune-iga-0.1.8.dev20230628002200/python/dune/iga/basis/__init__.py`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/python/dune_iga.egg-info/PKG-INFO` & `dune-iga-0.1.8.dev20230628002200/python/dune_iga.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: dune-iga
-Version: 0.1.8.dev20230627230825
+Version: 0.1.8.dev20230628002200
 Home-page: 
 Author: mueller@ibb.uni-stuttgart.de
 Author-email: mueller@ibb.uni-stuttgart.de
 Classifier: Programming Language :: C++
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: GNU General Public License (GPL)
 Requires-Python: >=3.4
```

### Comparing `dune-iga-0.1.8.dev20230627230825/python/dune_iga.egg-info/SOURCES.txt` & `dune-iga-0.1.8.dev20230628002200/python/dune_iga.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/setup.py` & `dune-iga-0.1.8.dev20230628002200/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -12,14 +12,14 @@
 # build _iga
 # cd /tmp/dune-iga
 # /dune/dune-common/build-cmake/run-in-dune-env pip install twine scikit-build
 # git config --global --add safe.directory /tmp/dune-iga
 # /dune/dune-common/build-cmake/run-in-dune-env python setup.py sdist
 # /dune/dune-common/build-cmake/run-in-dune-env python -m twine upload dist/* --verbose
 
-duneigaVersion = "0.1.8.dev20230627230825"
+duneigaVersion = "0.1.8.dev20230628002200"
 duneVersion = "2.9.0"
 
 metadata = metaData(duneVersion)[1]
 metadata["version"] = duneigaVersion
 
 setup(**metadata)
```

### Comparing `dune-iga-0.1.8.dev20230627230825/src/CMakeLists.txt` & `dune-iga-0.1.8.dev20230628002200/src/CMakeLists.txt`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/src/auxiliaryFiles/surface-hole.ibra` & `dune-iga-0.1.8.dev20230628002200/src/auxiliaryFiles/surface-hole.ibra`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/src/kirchhoff_plate.cc` & `dune-iga-0.1.8.dev20230628002200/src/kirchhoff_plate.cc`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/src/kirchhoffplate.hh` & `dune-iga-0.1.8.dev20230628002200/src/kirchhoffplate.hh`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/src/linear2dsolid.cc` & `dune-iga-0.1.8.dev20230628002200/src/linear2dsolid.cc`

 * *Files identical despite different names*

### Comparing `dune-iga-0.1.8.dev20230627230825/src/linearElastic.hh` & `dune-iga-0.1.8.dev20230628002200/src/linearElastic.hh`

 * *Files identical despite different names*


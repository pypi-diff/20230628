# Comparing `tmp/dionysus-2.0.8.tar.gz` & `tmp/dionysus-2.0.9.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/dionysus-2.0.8.tar", last modified: Tue Nov 24 19:12:52 2020, max compression
+gzip compressed data, was "dionysus-2.0.9.tar", last modified: Tue Feb 21 15:00:41 2023, max compression
```

## Comparing `dionysus-2.0.8.tar` & `dionysus-2.0.9.tar`

### file list

```diff
@@ -1,507 +1,509 @@
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.387208 dionysus-2.0.8/
--rw-r--r--   0 dmitriy    (501) staff       (20)      660 2020-11-24 18:48:01.000000 dionysus-2.0.8/.build.yml
--rw-r--r--   0 dmitriy    (501) staff       (20)       48 2020-11-24 18:48:01.000000 dionysus-2.0.8/.hgignore
--rw-r--r--   0 dmitriy    (501) staff       (20)      343 2020-11-24 18:48:01.000000 dionysus-2.0.8/.hgsubtree
--rw-r--r--   0 dmitriy    (501) staff       (20)      416 2020-11-24 18:48:01.000000 dionysus-2.0.8/.travis.yml
--rw-r--r--   0 dmitriy    (501) staff       (20)     2909 2020-11-24 18:52:39.000000 dionysus-2.0.8/CMakeLists.txt
--rw-r--r--   0 dmitriy    (501) staff       (20)      850 2020-11-24 18:48:01.000000 dionysus-2.0.8/LEGAL.txt
--rw-r--r--   0 dmitriy    (501) staff       (20)     2419 2020-11-24 18:48:01.000000 dionysus-2.0.8/LICENSE.txt
--rw-r--r--   0 dmitriy    (501) staff       (20)      389 2020-11-24 19:12:35.000000 dionysus-2.0.8/MANIFEST.in
--rw-r--r--   0 dmitriy    (501) staff       (20)     7527 2020-11-24 18:48:01.000000 dionysus-2.0.8/NOTICES.txt
--rw-r--r--   0 dmitriy    (501) staff       (20)     5145 2020-11-24 19:12:52.387468 dionysus-2.0.8/PKG-INFO
--rw-r--r--   0 dmitriy    (501) staff       (20)      231 2019-05-14 21:01:14.000000 dionysus-2.0.8/Pipfile
--rw-r--r--   0 dmitriy    (501) staff       (20)    32995 2019-05-14 17:09:43.000000 dionysus-2.0.8/Pipfile.lock
--rw-r--r--   0 dmitriy    (501) staff       (20)     3552 2020-11-24 18:48:01.000000 dionysus-2.0.8/README.rst
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.151416 dionysus-2.0.8/bindings/
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.190763 dionysus-2.0.8/bindings/python/
--rw-r--r--   0 dmitriy    (501) staff       (20)     1665 2020-11-24 18:48:01.000000 dionysus-2.0.8/bindings/python/CMakeLists.txt
--rw-r--r--   0 dmitriy    (501) staff       (20)      640 2020-11-24 18:48:01.000000 dionysus-2.0.8/bindings/python/bottleneck-distance.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     2897 2020-11-24 18:48:01.000000 dionysus-2.0.8/bindings/python/chain.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     4071 2020-11-24 18:48:01.000000 dionysus-2.0.8/bindings/python/cohomology-persistence.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)      207 2020-11-24 18:48:01.000000 dionysus-2.0.8/bindings/python/cohomology-persistence.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     3481 2020-11-24 18:48:01.000000 dionysus-2.0.8/bindings/python/diagram.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)      158 2020-11-24 18:48:01.000000 dionysus-2.0.8/bindings/python/diagram.h
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.192245 dionysus-2.0.8/bindings/python/dionysus/
--rw-r--r--   0 dmitriy    (501) staff       (20)     2769 2020-11-24 18:48:01.000000 dionysus-2.0.8/bindings/python/dionysus/__init__.py
--rw-r--r--   0 dmitriy    (501) staff       (20)       72 2020-11-24 19:09:59.000000 dionysus-2.0.8/bindings/python/dionysus/_version.py
--rw-r--r--   0 dmitriy    (501) staff       (20)     4580 2020-11-24 18:48:01.000000 dionysus-2.0.8/bindings/python/dionysus/plot.py
--rw-r--r--   0 dmitriy    (501) staff       (20)      915 2020-11-24 18:48:01.000000 dionysus-2.0.8/bindings/python/dionysus.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)      370 2020-11-24 18:48:01.000000 dionysus-2.0.8/bindings/python/field.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)      147 2020-11-24 18:48:01.000000 dionysus-2.0.8/bindings/python/field.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     3837 2020-11-24 18:48:01.000000 dionysus-2.0.8/bindings/python/filtration.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)      176 2020-11-24 18:48:01.000000 dionysus-2.0.8/bindings/python/filtration.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     4477 2020-11-24 18:48:01.000000 dionysus-2.0.8/bindings/python/freudenthal.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     3400 2020-11-24 18:48:01.000000 dionysus-2.0.8/bindings/python/omni-field-persistence.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)      112 2020-11-24 18:48:01.000000 dionysus-2.0.8/bindings/python/omni-field-persistence.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     6199 2020-11-24 18:48:01.000000 dionysus-2.0.8/bindings/python/persistence.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)      142 2020-11-24 18:48:01.000000 dionysus-2.0.8/bindings/python/persistence.h
--rw-r--r--   0 dmitriy    (501) staff       (20)      751 2020-11-24 18:48:01.000000 dionysus-2.0.8/bindings/python/progress.h
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.197963 dionysus-2.0.8/bindings/python/pybind11/
--rw-r--r--   0 dmitriy    (501) staff       (20)     1289 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/.appveyor.yml
--rw-r--r--   0 dmitriy    (501) staff       (20)      242 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/.clang-tidy
--rw-r--r--   0 dmitriy    (501) staff       (20)     2196 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/.cmake-format.yaml
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.200280 dionysus-2.0.8/bindings/python/pybind11/.github/
--rw-r--r--   0 dmitriy    (501) staff       (20)    12897 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/.github/CONTRIBUTING.md
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.202169 dionysus-2.0.8/bindings/python/pybind11/.github/ISSUE_TEMPLATE/
--rw-r--r--   0 dmitriy    (501) staff       (20)     1270 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/.github/ISSUE_TEMPLATE/bug-report.md
--rw-r--r--   0 dmitriy    (501) staff       (20)      172 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/.github/ISSUE_TEMPLATE/config.yml
--rw-r--r--   0 dmitriy    (501) staff       (20)      669 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/.github/ISSUE_TEMPLATE/feature-request.md
--rw-r--r--   0 dmitriy    (501) staff       (20)     1180 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/.github/ISSUE_TEMPLATE/question.md
--rw-r--r--   0 dmitriy    (501) staff       (20)      559 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/.github/dependabot.yml
--rw-r--r--   0 dmitriy    (501) staff       (20)      116 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/.github/labeler.yml
--rw-r--r--   0 dmitriy    (501) staff       (20)       50 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/.github/labeler_merged.yml
--rw-r--r--   0 dmitriy    (501) staff       (20)      306 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/.github/pull_request_template.md
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.205543 dionysus-2.0.8/bindings/python/pybind11/.github/workflows/
--rw-r--r--   0 dmitriy    (501) staff       (20)    19228 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/.github/workflows/ci.yml
--rw-r--r--   0 dmitriy    (501) staff       (20)     2117 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/.github/workflows/configure.yml
--rw-r--r--   0 dmitriy    (501) staff       (20)     1090 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/.github/workflows/format.yml
--rw-r--r--   0 dmitriy    (501) staff       (20)      333 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/.github/workflows/labeler.yml
--rw-r--r--   0 dmitriy    (501) staff       (20)     2497 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/.github/workflows/pip.yml
--rw-r--r--   0 dmitriy    (501) staff       (20)      452 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/.gitignore
--rw-r--r--   0 dmitriy    (501) staff       (20)     2460 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/.pre-commit-config.yaml
--rw-r--r--   0 dmitriy    (501) staff       (20)       62 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/.readthedocs.yml
--rw-r--r--   0 dmitriy    (501) staff       (20)     9996 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/CMakeLists.txt
--rw-r--r--   0 dmitriy    (501) staff       (20)     1684 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/LICENSE
--rw-r--r--   0 dmitriy    (501) staff       (20)      256 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/MANIFEST.in
--rw-r--r--   0 dmitriy    (501) staff       (20)     8077 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/README.rst
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.216707 dionysus-2.0.8/bindings/python/pybind11/docs/
--rw-r--r--   0 dmitriy    (501) staff       (20)      705 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/Doxyfile
--rw-r--r--   0 dmitriy    (501) staff       (20)     7417 2020-11-24 18:47:11.000000 dionysus-2.0.8/bindings/python/pybind11/docs/Makefile
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.217211 dionysus-2.0.8/bindings/python/pybind11/docs/_static/
--rw-r--r--   0 dmitriy    (501) staff       (20)      254 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/_static/theme_overrides.css
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.219951 dionysus-2.0.8/bindings/python/pybind11/docs/advanced/
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.223380 dionysus-2.0.8/bindings/python/pybind11/docs/advanced/cast/
--rw-r--r--   0 dmitriy    (501) staff       (20)     3937 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/advanced/cast/chrono.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)     3398 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/advanced/cast/custom.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)    14288 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/advanced/cast/eigen.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)     3889 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/advanced/cast/functional.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)     1556 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/advanced/cast/index.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)    11680 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/advanced/cast/overview.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)     9030 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/advanced/cast/stl.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)     9372 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/advanced/cast/strings.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)    45877 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/advanced/classes.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)     8420 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/advanced/embedding.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)    14169 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/advanced/exceptions.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)    25052 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/advanced/functions.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)    12444 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/advanced/misc.rst
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.225387 dionysus-2.0.8/bindings/python/pybind11/docs/advanced/pycpp/
--rw-r--r--   0 dmitriy    (501) staff       (20)      278 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/advanced/pycpp/index.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)    16364 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/advanced/pycpp/numpy.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)     7878 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/advanced/pycpp/object.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)     5125 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/advanced/pycpp/utilities.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)     6366 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/advanced/smart_ptrs.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)     9084 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/basics.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)     2974 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/benchmark.py
--rw-r--r--   0 dmitriy    (501) staff       (20)     3168 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/benchmark.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)    69200 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/changelog.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)    16122 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/classes.rst
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.225970 dionysus-2.0.8/bindings/python/pybind11/docs/cmake/
--rw-r--r--   0 dmitriy    (501) staff       (20)      273 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/cmake/index.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)    25261 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/compiling.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)    11960 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/conf.py
--rw-r--r--   0 dmitriy    (501) staff       (20)    14592 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/faq.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)      613 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/index.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)     3248 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/installing.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)     3062 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/limitations.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)    58510 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/pybind11-logo.png
--rw-r--r--   0 dmitriy    (501) staff       (20)    44653 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/pybind11_vs_boost_python1.png
--rw-r--r--   0 dmitriy    (501) staff       (20)    87708 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/pybind11_vs_boost_python1.svg
--rw-r--r--   0 dmitriy    (501) staff       (20)    41121 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/pybind11_vs_boost_python2.png
--rw-r--r--   0 dmitriy    (501) staff       (20)    85853 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/pybind11_vs_boost_python2.svg
--rw-r--r--   0 dmitriy    (501) staff       (20)     2113 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/reference.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)     3936 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/release.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)      168 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/requirements.txt
--rw-r--r--   0 dmitriy    (501) staff       (20)    21940 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/docs/upgrade.rst
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.154141 dionysus-2.0.8/bindings/python/pybind11/include/
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.235979 dionysus-2.0.8/bindings/python/pybind11/include/pybind11/
--rw-r--r--   0 dmitriy    (501) staff       (20)    21396 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/include/pybind11/attr.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     6118 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/include/pybind11/buffer_info.h
--rw-r--r--   0 dmitriy    (501) staff       (20)    94188 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/include/pybind11/cast.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     8185 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/include/pybind11/chrono.h
--rw-r--r--   0 dmitriy    (501) staff       (20)      120 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/include/pybind11/common.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     2037 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/include/pybind11/complex.h
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.240695 dionysus-2.0.8/bindings/python/pybind11/include/pybind11/detail/
--rw-r--r--   0 dmitriy    (501) staff       (20)    27803 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/include/pybind11/detail/class.h
--rw-r--r--   0 dmitriy    (501) staff       (20)    40043 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/include/pybind11/detail/common.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     3602 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/include/pybind11/detail/descr.h
--rw-r--r--   0 dmitriy    (501) staff       (20)    16397 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/include/pybind11/detail/init.h
--rw-r--r--   0 dmitriy    (501) staff       (20)    16373 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/include/pybind11/detail/internals.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     1486 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/include/pybind11/detail/typeid.h
--rw-r--r--   0 dmitriy    (501) staff       (20)    29086 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/include/pybind11/eigen.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     7843 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/include/pybind11/embed.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     5079 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/include/pybind11/eval.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     3709 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/include/pybind11/functional.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     6002 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/include/pybind11/iostream.h
--rw-r--r--   0 dmitriy    (501) staff       (20)    69310 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/include/pybind11/numpy.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     9085 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/include/pybind11/operators.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     2049 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/include/pybind11/options.h
--rw-r--r--   0 dmitriy    (501) staff       (20)   107501 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/include/pybind11/pybind11.h
--rw-r--r--   0 dmitriy    (501) staff       (20)    65764 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/include/pybind11/pytypes.h
--rw-r--r--   0 dmitriy    (501) staff       (20)    14136 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/include/pybind11/stl.h
--rw-r--r--   0 dmitriy    (501) staff       (20)    23356 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/include/pybind11/stl_bind.h
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.243987 dionysus-2.0.8/bindings/python/pybind11/pybind11/
--rw-r--r--   0 dmitriy    (501) staff       (20)      217 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/pybind11/__init__.py
--rw-r--r--   0 dmitriy    (501) staff       (20)     1158 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/pybind11/__main__.py
--rw-r--r--   0 dmitriy    (501) staff       (20)      207 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/pybind11/_version.py
--rw-r--r--   0 dmitriy    (501) staff       (20)      137 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/pybind11/_version.pyi
--rw-r--r--   0 dmitriy    (501) staff       (20)      663 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/pybind11/commands.py
--rw-r--r--   0 dmitriy    (501) staff       (20)        0 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/pybind11/py.typed
--rw-r--r--   0 dmitriy    (501) staff       (20)    15073 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/pybind11/setup_helpers.py
--rw-r--r--   0 dmitriy    (501) staff       (20)     1899 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/pybind11/setup_helpers.pyi
--rw-r--r--   0 dmitriy    (501) staff       (20)      118 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/pyproject.toml
--rw-r--r--   0 dmitriy    (501) staff       (20)     1824 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/setup.cfg
--rw-r--r--   0 dmitriy    (501) staff       (20)     3499 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/setup.py
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.284458 dionysus-2.0.8/bindings/python/pybind11/tests/
--rw-r--r--   0 dmitriy    (501) staff       (20)    14353 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/CMakeLists.txt
--rw-r--r--   0 dmitriy    (501) staff       (20)     4841 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/conftest.py
--rw-r--r--   0 dmitriy    (501) staff       (20)    11157 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/constructor_stats.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     1819 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/cross_module_gil_utils.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)      376 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/env.py
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.285317 dionysus-2.0.8/bindings/python/pybind11/tests/extra_python_package/
--rw-r--r--   0 dmitriy    (501) staff       (20)        0 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/extra_python_package/pytest.ini
--rw-r--r--   0 dmitriy    (501) staff       (20)     7074 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/extra_python_package/test_files.py
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.286158 dionysus-2.0.8/bindings/python/pybind11/tests/extra_setuptools/
--rw-r--r--   0 dmitriy    (501) staff       (20)        0 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/extra_setuptools/pytest.ini
--rw-r--r--   0 dmitriy    (501) staff       (20)     2581 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/extra_setuptools/test_setuphelper.py
--rw-r--r--   0 dmitriy    (501) staff       (20)     2144 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/local_bindings.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     5389 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/object.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     5285 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/pybind11_cross_module_tests.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     3647 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/pybind11_tests.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     2272 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/pybind11_tests.h
--rw-r--r--   0 dmitriy    (501) staff       (20)      626 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/pytest.ini
--rw-r--r--   0 dmitriy    (501) staff       (20)      683 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/requirements.txt
--rw-r--r--   0 dmitriy    (501) staff       (20)      864 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_async.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)      558 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_async.py
--rw-r--r--   0 dmitriy    (501) staff       (20)     8048 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_buffers.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     4869 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_buffers.py
--rw-r--r--   0 dmitriy    (501) staff       (20)    10160 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_builtin_casters.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)    14343 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_builtin_casters.py
--rw-r--r--   0 dmitriy    (501) staff       (20)     3702 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_call_policies.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     5728 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_call_policies.py
--rw-r--r--   0 dmitriy    (501) staff       (20)     6339 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_callbacks.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     4405 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_callbacks.py
--rw-r--r--   0 dmitriy    (501) staff       (20)     3406 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_chrono.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     6276 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_chrono.py
--rw-r--r--   0 dmitriy    (501) staff       (20)    20916 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_class.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)    14273 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_class.py
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.288052 dionysus-2.0.8/bindings/python/pybind11/tests/test_cmake_build/
--rw-r--r--   0 dmitriy    (501) staff       (20)     2459 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_cmake_build/CMakeLists.txt
--rw-r--r--   0 dmitriy    (501) staff       (20)      656 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_cmake_build/embed.cpp
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.288679 dionysus-2.0.8/bindings/python/pybind11/tests/test_cmake_build/installed_embed/
--rw-r--r--   0 dmitriy    (501) staff       (20)     1175 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_cmake_build/installed_embed/CMakeLists.txt
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.289155 dionysus-2.0.8/bindings/python/pybind11/tests/test_cmake_build/installed_function/
--rw-r--r--   0 dmitriy    (501) staff       (20)     1259 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_cmake_build/installed_function/CMakeLists.txt
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.289553 dionysus-2.0.8/bindings/python/pybind11/tests/test_cmake_build/installed_target/
--rw-r--r--   0 dmitriy    (501) staff       (20)     1653 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_cmake_build/installed_target/CMakeLists.txt
--rw-r--r--   0 dmitriy    (501) staff       (20)      152 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_cmake_build/main.cpp
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.289946 dionysus-2.0.8/bindings/python/pybind11/tests/test_cmake_build/subdirectory_embed/
--rw-r--r--   0 dmitriy    (501) staff       (20)     1354 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_cmake_build/subdirectory_embed/CMakeLists.txt
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.290402 dionysus-2.0.8/bindings/python/pybind11/tests/test_cmake_build/subdirectory_function/
--rw-r--r--   0 dmitriy    (501) staff       (20)     1127 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_cmake_build/subdirectory_function/CMakeLists.txt
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.290828 dionysus-2.0.8/bindings/python/pybind11/tests/test_cmake_build/subdirectory_target/
--rw-r--r--   0 dmitriy    (501) staff       (20)     1332 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_cmake_build/subdirectory_target/CMakeLists.txt
--rw-r--r--   0 dmitriy    (501) staff       (20)      166 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_cmake_build/test.py
--rw-r--r--   0 dmitriy    (501) staff       (20)     4147 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_constants_and_functions.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     1200 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_constants_and_functions.py
--rw-r--r--   0 dmitriy    (501) staff       (20)     9475 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_copy_move.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     4645 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_copy_move.py
--rw-r--r--   0 dmitriy    (501) staff       (20)     5446 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_custom_type_casters.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     4015 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_custom_type_casters.py
--rw-r--r--   0 dmitriy    (501) staff       (20)     2331 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_docstring_options.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     1489 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_docstring_options.py
--rw-r--r--   0 dmitriy    (501) staff       (20)    16772 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_eigen.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)    28282 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_eigen.py
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.292919 dionysus-2.0.8/bindings/python/pybind11/tests/test_embed/
--rw-r--r--   0 dmitriy    (501) staff       (20)     1639 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_embed/CMakeLists.txt
--rw-r--r--   0 dmitriy    (501) staff       (20)      637 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_embed/catch.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)      554 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_embed/external_module.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)    10209 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_embed/test_interpreter.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)      219 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_embed/test_interpreter.py
--rw-r--r--   0 dmitriy    (501) staff       (20)     2610 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_enum.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     7023 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_enum.py
--rw-r--r--   0 dmitriy    (501) staff       (20)     2628 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_eval.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)      768 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_eval.py
--rw-r--r--   0 dmitriy    (501) staff       (20)      143 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_eval_call.py
--rw-r--r--   0 dmitriy    (501) staff       (20)     7862 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_exceptions.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     6346 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_exceptions.py
--rw-r--r--   0 dmitriy    (501) staff       (20)    16193 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_factory_constructors.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)    16637 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_factory_constructors.py
--rw-r--r--   0 dmitriy    (501) staff       (20)     1760 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_gil_scoped.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     3128 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_gil_scoped.py
--rw-r--r--   0 dmitriy    (501) staff       (20)     3381 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_iostream.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     5799 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_iostream.py
--rw-r--r--   0 dmitriy    (501) staff       (20)     6489 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_kwargs_and_defaults.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)    10048 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_kwargs_and_defaults.py
--rw-r--r--   0 dmitriy    (501) staff       (20)     4333 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_local_bindings.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     8107 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_local_bindings.py
--rw-r--r--   0 dmitriy    (501) staff       (20)    19364 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_methods_and_attributes.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)    17310 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_methods_and_attributes.py
--rw-r--r--   0 dmitriy    (501) staff       (20)     3742 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_modules.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     2425 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_modules.py
--rw-r--r--   0 dmitriy    (501) staff       (20)     8863 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_multiple_inheritance.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     9495 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_multiple_inheritance.py
--rw-r--r--   0 dmitriy    (501) staff       (20)    17727 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_numpy_array.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)    18647 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_numpy_array.py
--rw-r--r--   0 dmitriy    (501) staff       (20)    17721 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_numpy_dtypes.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)    13484 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_numpy_dtypes.py
--rw-r--r--   0 dmitriy    (501) staff       (20)     3832 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_numpy_vectorize.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     9709 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_numpy_vectorize.py
--rw-r--r--   0 dmitriy    (501) staff       (20)     2731 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_opaque_types.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     1906 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_opaque_types.py
--rw-r--r--   0 dmitriy    (501) staff       (20)     8431 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_operator_overloading.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     4136 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_operator_overloading.py
--rw-r--r--   0 dmitriy    (501) staff       (20)     4609 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_pickling.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     1191 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_pickling.py
--rw-r--r--   0 dmitriy    (501) staff       (20)    13106 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_pytypes.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)    13633 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_pytypes.py
--rw-r--r--   0 dmitriy    (501) staff       (20)    13120 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_sequences_and_iterators.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     5966 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_sequences_and_iterators.py
--rw-r--r--   0 dmitriy    (501) staff       (20)    16921 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_smart_ptr.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     9465 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_smart_ptr.py
--rw-r--r--   0 dmitriy    (501) staff       (20)    12793 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_stl.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     8557 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_stl.py
--rw-r--r--   0 dmitriy    (501) staff       (20)     4655 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_stl_binders.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     7182 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_stl_binders.py
--rw-r--r--   0 dmitriy    (501) staff       (20)     4458 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_tagbased_polymorphic.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)      765 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_tagbased_polymorphic.py
--rw-r--r--   0 dmitriy    (501) staff       (20)      603 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_union.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)      172 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_union.py
--rw-r--r--   0 dmitriy    (501) staff       (20)    18454 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_virtual_functions.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)    11664 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tests/test_virtual_functions.py
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.299355 dionysus-2.0.8/bindings/python/pybind11/tools/
--rw-r--r--   0 dmitriy    (501) staff       (20)     2295 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tools/FindCatch.cmake
--rw-r--r--   0 dmitriy    (501) staff       (20)     3031 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tools/FindEigen3.cmake
--rw-r--r--   0 dmitriy    (501) staff       (20)     9942 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tools/FindPythonLibsNew.cmake
--rwxr-xr-x   0 dmitriy    (501) staff       (20)     1427 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tools/check-style.sh
--rw-r--r--   0 dmitriy    (501) staff       (20)      952 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tools/cmake_uninstall.cmake.in
--rw-r--r--   0 dmitriy    (501) staff       (20)     1121 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tools/libsize.py
--rw-r--r--   0 dmitriy    (501) staff       (20)    14003 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tools/pybind11Common.cmake
--rw-r--r--   0 dmitriy    (501) staff       (20)     7011 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tools/pybind11Config.cmake.in
--rw-r--r--   0 dmitriy    (501) staff       (20)     8179 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tools/pybind11NewTools.cmake
--rw-r--r--   0 dmitriy    (501) staff       (20)     6592 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tools/pybind11Tools.cmake
--rw-r--r--   0 dmitriy    (501) staff       (20)       94 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tools/pyproject.toml
--rw-r--r--   0 dmitriy    (501) staff       (20)     1822 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tools/setup_global.py.in
--rw-r--r--   0 dmitriy    (501) staff       (20)      915 2020-11-24 18:48:09.000000 dionysus-2.0.8/bindings/python/pybind11/tools/setup_main.py.in
--rw-r--r--   0 dmitriy    (501) staff       (20)     4136 2020-11-24 18:48:01.000000 dionysus-2.0.8/bindings/python/rips.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     2369 2020-11-24 18:48:01.000000 dionysus-2.0.8/bindings/python/simplex.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)      511 2020-11-24 18:48:01.000000 dionysus-2.0.8/bindings/python/simplex.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     1295 2020-11-24 18:48:01.000000 dionysus-2.0.8/bindings/python/wasserstein-distance.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)    10795 2020-11-24 18:48:01.000000 dionysus-2.0.8/bindings/python/zigzag-persistence.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)      135 2020-11-24 18:48:01.000000 dionysus-2.0.8/bindings/python/zigzag-persistence.h
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.305039 dionysus-2.0.8/dionysus/
--rw-r--r--   0 dmitriy    (501) staff       (20)     2769 2019-05-15 17:40:38.000000 dionysus-2.0.8/dionysus/__init__.py
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.308372 dionysus-2.0.8/dionysus/__pycache__/
--rw-r--r--   0 dmitriy    (501) staff       (20)     2986 2019-09-14 15:36:31.000000 dionysus-2.0.8/dionysus/__pycache__/__init__.cpython-37.pyc
--rw-r--r--   0 dmitriy    (501) staff       (20)      233 2019-09-14 15:36:31.000000 dionysus-2.0.8/dionysus/__pycache__/_version.cpython-37.pyc
--rw-r--r--   0 dmitriy    (501) staff       (20)     5131 2019-09-14 15:36:31.000000 dionysus-2.0.8/dionysus/__pycache__/plot.cpython-37.pyc
--rwxr-xr-x   0 dmitriy    (501) staff       (20)   947616 2019-05-14 20:48:27.000000 dionysus-2.0.8/dionysus/_dionysus.cpython-37m-darwin.so
--rw-r--r--   0 dmitriy    (501) staff       (20)       80 2020-11-24 19:09:20.000000 dionysus-2.0.8/dionysus/_version.py
--rw-r--r--   0 dmitriy    (501) staff       (20)      310 2019-05-15 17:40:38.000000 dionysus-2.0.8/dionysus/_version.pyc
--rw-r--r--   0 dmitriy    (501) staff       (20)     4580 2019-05-15 17:40:38.000000 dionysus-2.0.8/dionysus/plot.py
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.307028 dionysus-2.0.8/dionysus.egg-info/
--rw-r--r--   0 dmitriy    (501) staff       (20)     5145 2020-11-24 19:12:51.000000 dionysus-2.0.8/dionysus.egg-info/PKG-INFO
--rw-r--r--   0 dmitriy    (501) staff       (20)    20253 2020-11-24 19:12:52.000000 dionysus-2.0.8/dionysus.egg-info/SOURCES.txt
--rw-r--r--   0 dmitriy    (501) staff       (20)        1 2020-11-24 19:12:51.000000 dionysus-2.0.8/dionysus.egg-info/dependency_links.txt
--rw-r--r--   0 dmitriy    (501) staff       (20)        1 2019-05-07 14:07:09.000000 dionysus-2.0.8/dionysus.egg-info/not-zip-safe
--rw-r--r--   0 dmitriy    (501) staff       (20)        9 2020-11-24 19:12:51.000000 dionysus-2.0.8/dionysus.egg-info/top_level.txt
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.310196 dionysus-2.0.8/doc/
--rw-r--r--   0 dmitriy    (501) staff       (20)     2530 2020-11-24 18:48:01.000000 dionysus-2.0.8/doc/API.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)      605 2020-11-24 18:48:01.000000 dionysus-2.0.8/doc/Makefile
--rw-r--r--   0 dmitriy    (501) staff       (20)     4907 2020-11-24 18:48:01.000000 dionysus-2.0.8/doc/conf.py
--rw-r--r--   0 dmitriy    (501) staff       (20)     3584 2020-11-24 18:48:01.000000 dionysus-2.0.8/doc/index.rst
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.315560 dionysus-2.0.8/doc/tutorial/
--rw-r--r--   0 dmitriy    (501) staff       (20)      291 2020-11-24 18:48:01.000000 dionysus-2.0.8/doc/tutorial/alpha-shapes.rst_
--rw-r--r--   0 dmitriy    (501) staff       (20)     7455 2020-11-24 18:48:01.000000 dionysus-2.0.8/doc/tutorial/basics.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)     3752 2020-11-24 18:48:01.000000 dionysus-2.0.8/doc/tutorial/cohomology.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)      611 2020-11-24 18:48:01.000000 dionysus-2.0.8/doc/tutorial/diagnostics.rst
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.318372 dionysus-2.0.8/doc/tutorial/figures/
--rw-r--r--   0 dmitriy    (501) staff       (20)    57629 2020-11-24 18:48:01.000000 dionysus-2.0.8/doc/tutorial/figures/alpha-shape.png
--rw-r--r--   0 dmitriy    (501) staff       (20)    16785 2020-11-24 18:48:01.000000 dionysus-2.0.8/doc/tutorial/figures/barcode.png
--rw-r--r--   0 dmitriy    (501) staff       (20)    24440 2020-11-24 18:48:01.000000 dionysus-2.0.8/doc/tutorial/figures/filtration.png
--rw-r--r--   0 dmitriy    (501) staff       (20)    79459 2020-11-24 18:48:01.000000 dionysus-2.0.8/doc/tutorial/figures/lower-star.png
--rw-r--r--   0 dmitriy    (501) staff       (20)    17515 2020-11-24 18:48:01.000000 dionysus-2.0.8/doc/tutorial/figures/vietoris-rips.png
--rw-r--r--   0 dmitriy    (501) staff       (20)       96 2020-11-24 18:48:01.000000 dionysus-2.0.8/doc/tutorial/filtrations.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)      177 2020-11-24 18:48:01.000000 dionysus-2.0.8/doc/tutorial/index.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)     2118 2020-11-24 18:48:01.000000 dionysus-2.0.8/doc/tutorial/lower-star.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)     3033 2020-11-24 18:48:01.000000 dionysus-2.0.8/doc/tutorial/omni-field.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)       96 2020-11-24 18:48:01.000000 dionysus-2.0.8/doc/tutorial/persistence.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)     1411 2020-11-24 18:48:01.000000 dionysus-2.0.8/doc/tutorial/plotting.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)     2080 2020-11-24 18:48:01.000000 dionysus-2.0.8/doc/tutorial/rips.rst
--rw-r--r--   0 dmitriy    (501) staff       (20)     4241 2020-11-24 18:48:01.000000 dionysus-2.0.8/doc/tutorial/zigzags.rst
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.318881 dionysus-2.0.8/examples/
--rw-r--r--   0 dmitriy    (501) staff       (20)      170 2020-11-24 18:48:01.000000 dionysus-2.0.8/examples/CMakeLists.txt
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.320280 dionysus-2.0.8/examples/filtration/
--rw-r--r--   0 dmitriy    (501) staff       (20)      330 2020-11-24 18:48:01.000000 dionysus-2.0.8/examples/filtration/CMakeLists.txt
--rw-r--r--   0 dmitriy    (501) staff       (20)     1885 2020-11-24 18:48:01.000000 dionysus-2.0.8/examples/filtration/filtration-persistence.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     1994 2020-11-24 18:48:01.000000 dionysus-2.0.8/examples/filtration/zigzag-filtration-persistence.cpp
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.321425 dionysus-2.0.8/examples/include/
--rw-r--r--   0 dmitriy    (501) staff       (20)     9906 2020-11-24 18:48:01.000000 dionysus-2.0.8/examples/include/cnpy.h
--rw-r--r--   0 dmitriy    (501) staff       (20)      683 2020-11-24 18:48:01.000000 dionysus-2.0.8/examples/include/common.h
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.322455 dionysus-2.0.8/examples/include/format/
--rw-r--r--   0 dmitriy    (501) staff       (20)    34701 2020-11-24 18:48:01.000000 dionysus-2.0.8/examples/include/format/format.cc
--rw-r--r--   0 dmitriy    (501) staff       (20)    76882 2020-11-24 18:48:01.000000 dionysus-2.0.8/examples/include/format/format.h
--rw-r--r--   0 dmitriy    (501) staff       (20)      113 2020-11-24 18:48:01.000000 dionysus-2.0.8/examples/include/format.h
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.324768 dionysus-2.0.8/examples/include/grid/
--rw-r--r--   0 dmitriy    (501) staff       (20)     7201 2020-11-24 18:48:01.000000 dionysus-2.0.8/examples/include/grid/box.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     3686 2020-11-24 18:48:01.000000 dionysus-2.0.8/examples/include/grid/box.hpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     5308 2020-11-24 18:48:01.000000 dionysus-2.0.8/examples/include/grid/grid.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     5348 2020-11-24 18:48:01.000000 dionysus-2.0.8/examples/include/grid/point.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     3028 2020-11-24 18:48:01.000000 dionysus-2.0.8/examples/include/grid/vertices.h
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.325216 dionysus-2.0.8/examples/include/opts/
--rw-r--r--   0 dmitriy    (501) staff       (20)    14740 2020-11-24 18:48:01.000000 dionysus-2.0.8/examples/include/opts/opts.h
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.328310 dionysus-2.0.8/examples/lzz/
--rw-r--r--   0 dmitriy    (501) staff       (20)      460 2020-11-24 18:48:01.000000 dionysus-2.0.8/examples/lzz/CMakeLists.txt
--rw-r--r--   0 dmitriy    (501) staff       (20)     6020 2020-11-24 18:48:01.000000 dionysus-2.0.8/examples/lzz/extended-persistence.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     4403 2020-11-24 18:48:01.000000 dionysus-2.0.8/examples/lzz/grid-topology.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     2616 2020-11-24 18:48:01.000000 dionysus-2.0.8/examples/lzz/relative-lzz.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     2685 2020-11-24 18:48:01.000000 dionysus-2.0.8/examples/lzz/relative-lzz.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     5329 2020-11-24 18:48:01.000000 dionysus-2.0.8/examples/lzz/relative-lzz.hpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     1858 2020-11-24 18:48:01.000000 dionysus-2.0.8/examples/lzz/relative-zz-filtration.cpp
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.329199 dionysus-2.0.8/examples/omni-field/
--rw-r--r--   0 dmitriy    (501) staff       (20)      154 2020-11-24 18:48:01.000000 dionysus-2.0.8/examples/omni-field/CMakeLists.txt
--rw-r--r--   0 dmitriy    (501) staff       (20)     3465 2020-11-24 18:48:01.000000 dionysus-2.0.8/examples/omni-field/omni-field-persistence.cpp
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.330946 dionysus-2.0.8/examples/rips/
--rw-r--r--   0 dmitriy    (501) staff       (20)      326 2020-11-24 18:48:01.000000 dionysus-2.0.8/examples/rips/CMakeLists.txt
--rw-r--r--   0 dmitriy    (501) staff       (20)     2341 2020-11-24 18:48:01.000000 dionysus-2.0.8/examples/rips/rips-basic.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     4754 2020-11-24 18:48:01.000000 dionysus-2.0.8/examples/rips/rips-pairwise.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)    11527 2020-11-24 18:48:01.000000 dionysus-2.0.8/examples/rips/rips-zigzag.cpp
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.331456 dionysus-2.0.8/examples/src/
--rw-r--r--   0 dmitriy    (501) staff       (20)     8222 2020-11-24 18:48:01.000000 dionysus-2.0.8/examples/src/cnpy.cpp
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.162392 dionysus-2.0.8/ext/
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.331889 dionysus-2.0.8/ext/hera/
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.332733 dionysus-2.0.8/ext/hera/bottleneck/
--rw-r--r--   0 dmitriy    (501) staff       (20)     1472 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/bottleneck/CMakeLists.txt
--rw-r--r--   0 dmitriy    (501) staff       (20)     3344 2020-03-09 18:10:21.000000 dionysus-2.0.8/ext/hera/bottleneck/README
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.333608 dionysus-2.0.8/ext/hera/bottleneck/example/
--rw-r--r--   0 dmitriy    (501) staff       (20)      822 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/bottleneck/example/CMakeLists.txt
--rw-r--r--   0 dmitriy    (501) staff       (20)     4726 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/bottleneck/example/bottleneck_dist.cpp
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.339860 dionysus-2.0.8/ext/hera/bottleneck/include/
--rw-r--r--   0 dmitriy    (501) staff       (20)    18619 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/bottleneck/include/basic_defs_bt.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     7327 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/bottleneck/include/bottleneck.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     4513 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/bottleneck/include/bottleneck_detail.h
--rw-r--r--   0 dmitriy    (501) staff       (20)    27907 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/bottleneck/include/bottleneck_detail.hpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     4708 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/bottleneck/include/bound_match.h
--rw-r--r--   0 dmitriy    (501) staff       (20)    20759 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/bottleneck/include/bound_match.hpp
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.340310 dionysus-2.0.8/ext/hera/bottleneck/include/catch/
--rw-r--r--   0 dmitriy    (501) staff       (20)   420570 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/bottleneck/include/catch/catch.hpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     2540 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/bottleneck/include/def_debug_bt.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     7861 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/bottleneck/include/diagram_reader.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     1360 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/bottleneck/include/diagram_traits.h
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.341684 dionysus-2.0.8/ext/hera/bottleneck/include/dnn/
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.342156 dionysus-2.0.8/ext/hera/bottleneck/include/dnn/geometry/
--rw-r--r--   0 dmitriy    (501) staff       (20)     7659 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/bottleneck/include/dnn/geometry/euclidean-fixed.h
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.343468 dionysus-2.0.8/ext/hera/bottleneck/include/dnn/local/
--rw-r--r--   0 dmitriy    (501) staff       (20)     4606 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/bottleneck/include/dnn/local/kd-tree.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     8941 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/bottleneck/include/dnn/local/kd-tree.hpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     4051 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/bottleneck/include/dnn/local/search-functors.h
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.344347 dionysus-2.0.8/ext/hera/bottleneck/include/dnn/parallel/
--rw-r--r--   0 dmitriy    (501) staff       (20)     7252 2020-02-19 20:48:17.000000 dionysus-2.0.8/ext/hera/bottleneck/include/dnn/parallel/tbb.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     3192 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/bottleneck/include/dnn/parallel/utils.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     1251 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/bottleneck/include/dnn/utils.h
--rw-r--r--   0 dmitriy    (501) staff       (20)    10452 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/bottleneck/include/neighb_oracle.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     2162 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/license.txt
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.345272 dionysus-2.0.8/ext/hera/wasserstein/
--rw-r--r--   0 dmitriy    (501) staff       (20)     2772 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/CMakeLists.txt
--rw-r--r--   0 dmitriy    (501) staff       (20)     3453 2020-03-09 18:10:21.000000 dionysus-2.0.8/ext/hera/wasserstein/README
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.346635 dionysus-2.0.8/ext/hera/wasserstein/example/
--rw-r--r--   0 dmitriy    (501) staff       (20)     7020 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/example/wasserstein_dist.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     5925 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/example/wasserstein_dist_dipha.cpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     6848 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/example/wasserstein_dist_point_cloud.cpp
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.360601 dionysus-2.0.8/ext/hera/wasserstein/include/
--rw-r--r--   0 dmitriy    (501) staff       (20)     2533 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/include/auction_oracle.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     3990 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/include/auction_oracle_base.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     4195 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/include/auction_oracle_base.hpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     4074 2020-11-24 18:48:09.000000 dionysus-2.0.8/ext/hera/wasserstein/include/auction_oracle_kdtree_pure_geom.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     8571 2020-11-24 18:48:09.000000 dionysus-2.0.8/ext/hera/wasserstein/include/auction_oracle_kdtree_pure_geom.hpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     5099 2020-11-24 18:48:09.000000 dionysus-2.0.8/ext/hera/wasserstein/include/auction_oracle_kdtree_restricted.h
--rw-r--r--   0 dmitriy    (501) staff       (20)    21858 2020-11-24 18:48:09.000000 dionysus-2.0.8/ext/hera/wasserstein/include/auction_oracle_kdtree_restricted.hpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     8598 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/include/auction_oracle_kdtree_single_diag.h
--rw-r--r--   0 dmitriy    (501) staff       (20)    27574 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/include/auction_oracle_kdtree_single_diag.hpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     6762 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/include/auction_oracle_lazy_heap.h
--rw-r--r--   0 dmitriy    (501) staff       (20)    23570 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/include/auction_oracle_lazy_heap.hpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     4885 2020-11-24 18:48:09.000000 dionysus-2.0.8/ext/hera/wasserstein/include/auction_oracle_stupid_sparse_restricted.h
--rw-r--r--   0 dmitriy    (501) staff       (20)    21677 2020-11-24 18:48:09.000000 dionysus-2.0.8/ext/hera/wasserstein/include/auction_oracle_stupid_sparse_restricted.hpp
--rw-r--r--   0 dmitriy    (501) staff       (20)    10597 2020-11-24 18:48:09.000000 dionysus-2.0.8/ext/hera/wasserstein/include/auction_runner_fr.h
--rw-r--r--   0 dmitriy    (501) staff       (20)    44124 2020-11-24 18:48:09.000000 dionysus-2.0.8/ext/hera/wasserstein/include/auction_runner_fr.hpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     5464 2020-11-24 18:48:09.000000 dionysus-2.0.8/ext/hera/wasserstein/include/auction_runner_gs.h
--rw-r--r--   0 dmitriy    (501) staff       (20)    19767 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/include/auction_runner_gs.hpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     6676 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/include/auction_runner_gs_single_diag.h
--rw-r--r--   0 dmitriy    (501) staff       (20)    31403 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/include/auction_runner_gs_single_diag.hpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     8692 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/include/auction_runner_jac.h
--rw-r--r--   0 dmitriy    (501) staff       (20)    34787 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/include/auction_runner_jac.hpp
--rw-r--r--   0 dmitriy    (501) staff       (20)    11024 2020-11-24 18:48:09.000000 dionysus-2.0.8/ext/hera/wasserstein/include/basic_defs_ws.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     6570 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/include/basic_defs_ws.hpp
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.361067 dionysus-2.0.8/ext/hera/wasserstein/include/catch/
--rw-r--r--   0 dmitriy    (501) staff       (20)   420570 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/include/catch/catch.hpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     2620 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/include/def_debug_ws.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     4920 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/include/diagonal_heap.h
--rw-r--r--   0 dmitriy    (501) staff       (20)    15007 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/include/diagram_reader.h
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.362371 dionysus-2.0.8/ext/hera/wasserstein/include/dnn/
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.363263 dionysus-2.0.8/ext/hera/wasserstein/include/dnn/geometry/
--rw-r--r--   0 dmitriy    (501) staff       (20)    11518 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/include/dnn/geometry/euclidean-dynamic.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     8510 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/include/dnn/geometry/euclidean-fixed.h
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.364708 dionysus-2.0.8/ext/hera/wasserstein/include/dnn/local/
--rw-r--r--   0 dmitriy    (501) staff       (20)     4044 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/include/dnn/local/kd-tree.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     8909 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/include/dnn/local/kd-tree.hpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     3322 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/include/dnn/local/search-functors.h
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.365573 dionysus-2.0.8/ext/hera/wasserstein/include/dnn/parallel/
--rw-r--r--   0 dmitriy    (501) staff       (20)     7228 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/include/dnn/parallel/tbb.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     3213 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/include/dnn/parallel/utils.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     1251 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/include/dnn/utils.h
--rw-r--r--   0 dmitriy    (501) staff       (20)      528 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/include/hera_infinity.h
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.366001 dionysus-2.0.8/ext/hera/wasserstein/include/opts/
--rwxr-xr-x   0 dmitriy    (501) staff       (20)     9533 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/include/opts/opts.h
--rw-r--r--   0 dmitriy    (501) staff       (20)    13180 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/include/wasserstein.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     2913 2020-02-19 19:15:56.000000 dionysus-2.0.8/ext/hera/wasserstein/include/wasserstein_pure_geom.hpp
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.366409 dionysus-2.0.8/include/
--rw-r--r--   0 dmitriy    (501) staff       (20)    57327 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/backward.hpp
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.381984 dionysus-2.0.8/include/dionysus/
--rw-r--r--   0 dmitriy    (501) staff       (20)     4281 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/chain.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     5278 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/chain.hpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     1459 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/clearing-reduction.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     2120 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/clearing-reduction.hpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     4746 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/cohomology-persistence.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     2469 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/cohomology-persistence.hpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     3394 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/diagram.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     3463 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/distances.h
--rw-r--r--   0 dmitriy    (501) staff       (20)      992 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/distances.hpp
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.382482 dionysus-2.0.8/include/dionysus/dlog/
--rw-r--r--   0 dmitriy    (501) staff       (20)     1688 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/dlog/progress.h
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.383724 dionysus-2.0.8/include/dionysus/fields/
--rw-r--r--   0 dmitriy    (501) staff       (20)     2660 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/fields/q.h
--rw-r--r--   0 dmitriy    (501) staff       (20)      946 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/fields/z2.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     1633 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/fields/zp.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     6013 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/filtration.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     5814 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/omni-field-persistence.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     6877 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/omni-field-persistence.hpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     2148 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/ordinary-persistence.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     2188 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/pair-recorder.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     7912 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/reduced-matrix.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     2231 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/reduced-matrix.hpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     3147 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/reduction.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     3445 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/relative-homology-zigzag.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     3323 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/relative-homology-zigzag.hpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     6759 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/rips.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     5735 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/rips.hpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     2098 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/row-reduction.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     3765 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/row-reduction.hpp
--rw-r--r--   0 dmitriy    (501) staff       (20)    11806 2020-11-24 18:52:58.000000 dionysus-2.0.8/include/dionysus/simplex.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     8269 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/sparse-row-matrix.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     3398 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/sparse-row-matrix.hpp
--rw-r--r--   0 dmitriy    (501) staff       (20)     1543 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/standard-reduction.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     1771 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/standard-reduction.hpp
--rw-r--r--   0 dmitriy    (501) staff       (20)      433 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/trails-chains.h
--rw-r--r--   0 dmitriy    (501) staff       (20)     5676 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/zigzag-persistence.h
--rw-r--r--   0 dmitriy    (501) staff       (20)    21366 2020-11-24 18:48:01.000000 dionysus-2.0.8/include/dionysus/zigzag-persistence.hpp
--rw-r--r--   0 dmitriy    (501) staff       (20)      425 2020-11-24 18:48:09.000000 dionysus-2.0.8/peru.yaml
--rw-r--r--   0 dmitriy    (501) staff       (20)       80 2020-11-24 19:12:52.388227 dionysus-2.0.8/setup.cfg
--rw-r--r--   0 dmitriy    (501) staff       (20)     3848 2020-11-24 18:48:01.000000 dionysus-2.0.8/setup.py
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.384193 dionysus-2.0.8/src/
--rw-r--r--   0 dmitriy    (501) staff       (20)      757 2020-11-24 18:48:01.000000 dionysus-2.0.8/src/backward.cpp
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.385095 dionysus-2.0.8/tests/
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.168041 dionysus-2.0.8/tests/data/
-drwxr-xr-x   0 dmitriy    (501) staff       (20)        0 2020-11-24 19:12:52.386110 dionysus-2.0.8/tests/data/issue39/
--rw-r--r--   0 dmitriy    (501) staff       (20)    35793 2020-11-24 18:48:01.000000 dionysus-2.0.8/tests/data/issue39/dgm1.txt
--rw-r--r--   0 dmitriy    (501) staff       (20)    36478 2020-11-24 18:48:01.000000 dionysus-2.0.8/tests/data/issue39/dgm2.txt
--rw-r--r--   0 dmitriy    (501) staff       (20)      222 2020-11-24 18:48:01.000000 dionysus-2.0.8/tests/test_distances.py
--rw-r--r--   0 dmitriy    (501) staff       (20)      288 2020-11-24 18:48:01.000000 dionysus-2.0.8/tests/test_issue39.py
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.161193 dionysus-2.0.9/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      660 2021-01-19 17:30:02.000000 dionysus-2.0.9/.build.yml
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)       48 2020-11-24 18:48:01.000000 dionysus-2.0.9/.hgignore
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      343 2020-11-24 18:48:01.000000 dionysus-2.0.9/.hgsubtree
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      416 2020-11-24 18:48:01.000000 dionysus-2.0.9/.travis.yml
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2909 2021-01-19 17:30:02.000000 dionysus-2.0.9/CMakeLists.txt
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      850 2020-11-24 18:48:01.000000 dionysus-2.0.9/LEGAL.txt
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2419 2020-11-24 18:48:01.000000 dionysus-2.0.9/LICENSE.txt
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      389 2021-01-19 17:30:02.000000 dionysus-2.0.9/MANIFEST.in
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     7527 2020-11-24 18:48:01.000000 dionysus-2.0.9/NOTICES.txt
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4559 2023-02-21 15:00:41.161193 dionysus-2.0.9/PKG-INFO
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      231 2019-05-14 21:01:14.000000 dionysus-2.0.9/Pipfile
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    32995 2019-05-14 17:09:43.000000 dionysus-2.0.9/Pipfile.lock
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3553 2021-01-19 17:30:02.000000 dionysus-2.0.9/README.rst
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.111194 dionysus-2.0.9/bindings/
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.117860 dionysus-2.0.9/bindings/python/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1665 2020-11-24 18:48:01.000000 dionysus-2.0.9/bindings/python/CMakeLists.txt
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      640 2020-11-24 18:48:01.000000 dionysus-2.0.9/bindings/python/bottleneck-distance.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2897 2020-11-24 18:48:01.000000 dionysus-2.0.9/bindings/python/chain.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4071 2020-11-24 18:48:01.000000 dionysus-2.0.9/bindings/python/cohomology-persistence.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      207 2020-11-24 18:48:01.000000 dionysus-2.0.9/bindings/python/cohomology-persistence.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4016 2022-06-24 21:35:37.000000 dionysus-2.0.9/bindings/python/diagram.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      158 2020-11-24 18:48:01.000000 dionysus-2.0.9/bindings/python/diagram.h
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.121194 dionysus-2.0.9/bindings/python/dionysus/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2769 2020-11-24 18:48:01.000000 dionysus-2.0.9/bindings/python/dionysus/__init__.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)       72 2023-02-21 15:00:37.000000 dionysus-2.0.9/bindings/python/dionysus/_version.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4789 2022-06-24 21:35:37.000000 dionysus-2.0.9/bindings/python/dionysus/plot.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      915 2020-11-24 18:48:01.000000 dionysus-2.0.9/bindings/python/dionysus.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      370 2020-11-24 18:48:01.000000 dionysus-2.0.9/bindings/python/field.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      147 2020-11-24 18:48:01.000000 dionysus-2.0.9/bindings/python/field.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3837 2020-11-24 18:48:01.000000 dionysus-2.0.9/bindings/python/filtration.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      176 2020-11-24 18:48:01.000000 dionysus-2.0.9/bindings/python/filtration.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4477 2020-11-24 18:48:01.000000 dionysus-2.0.9/bindings/python/freudenthal.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3400 2020-11-24 18:48:01.000000 dionysus-2.0.9/bindings/python/omni-field-persistence.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      112 2020-11-24 18:48:01.000000 dionysus-2.0.9/bindings/python/omni-field-persistence.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     6199 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/persistence.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      142 2020-11-24 18:48:01.000000 dionysus-2.0.9/bindings/python/persistence.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      751 2020-11-24 18:48:01.000000 dionysus-2.0.9/bindings/python/progress.h
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.121194 dionysus-2.0.9/bindings/python/pybind11/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1289 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/.appveyor.yml
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      242 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/.clang-tidy
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2196 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/.cmake-format.yaml
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.121194 dionysus-2.0.9/bindings/python/pybind11/.github/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    12897 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/.github/CONTRIBUTING.md
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.121194 dionysus-2.0.9/bindings/python/pybind11/.github/ISSUE_TEMPLATE/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1270 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/.github/ISSUE_TEMPLATE/bug-report.md
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      172 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/.github/ISSUE_TEMPLATE/config.yml
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      669 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/.github/ISSUE_TEMPLATE/feature-request.md
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1180 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/.github/ISSUE_TEMPLATE/question.md
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      559 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/.github/dependabot.yml
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      116 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/.github/labeler.yml
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)       50 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/.github/labeler_merged.yml
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      306 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/.github/pull_request_template.md
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.121194 dionysus-2.0.9/bindings/python/pybind11/.github/workflows/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    19228 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/.github/workflows/ci.yml
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2117 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/.github/workflows/configure.yml
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1090 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/.github/workflows/format.yml
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      333 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/.github/workflows/labeler.yml
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2497 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/.github/workflows/pip.yml
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      452 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/.gitignore
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2460 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/.pre-commit-config.yaml
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)       62 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/.readthedocs.yml
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     9996 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/CMakeLists.txt
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1684 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/LICENSE
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      256 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/MANIFEST.in
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     8077 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/README.rst
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.124527 dionysus-2.0.9/bindings/python/pybind11/docs/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      705 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/Doxyfile
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     7417 2020-11-24 18:47:11.000000 dionysus-2.0.9/bindings/python/pybind11/docs/Makefile
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.124527 dionysus-2.0.9/bindings/python/pybind11/docs/_static/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      254 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/_static/theme_overrides.css
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.124527 dionysus-2.0.9/bindings/python/pybind11/docs/advanced/
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.124527 dionysus-2.0.9/bindings/python/pybind11/docs/advanced/cast/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3937 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/advanced/cast/chrono.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3398 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/advanced/cast/custom.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    14288 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/advanced/cast/eigen.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3889 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/advanced/cast/functional.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1556 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/advanced/cast/index.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    11680 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/advanced/cast/overview.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     9030 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/advanced/cast/stl.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     9372 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/advanced/cast/strings.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    45877 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/advanced/classes.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     8420 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/advanced/embedding.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    14169 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/advanced/exceptions.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    25052 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/advanced/functions.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    12444 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/advanced/misc.rst
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.124527 dionysus-2.0.9/bindings/python/pybind11/docs/advanced/pycpp/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      278 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/advanced/pycpp/index.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    16364 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/advanced/pycpp/numpy.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     7878 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/advanced/pycpp/object.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     5125 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/advanced/pycpp/utilities.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     6366 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/advanced/smart_ptrs.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     9084 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/basics.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2974 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/benchmark.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3168 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/benchmark.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    69200 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/changelog.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    16122 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/classes.rst
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.124527 dionysus-2.0.9/bindings/python/pybind11/docs/cmake/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      273 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/cmake/index.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    25261 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/compiling.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    11960 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/conf.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    14592 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/faq.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      613 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/index.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3248 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/installing.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3062 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/limitations.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    58510 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/pybind11-logo.png
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    44653 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/pybind11_vs_boost_python1.png
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    87708 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/pybind11_vs_boost_python1.svg
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    41121 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/pybind11_vs_boost_python2.png
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    85853 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/pybind11_vs_boost_python2.svg
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2113 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/reference.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3936 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/release.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      168 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/requirements.txt
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    21940 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/docs/upgrade.rst
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.111194 dionysus-2.0.9/bindings/python/pybind11/include/
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.127860 dionysus-2.0.9/bindings/python/pybind11/include/pybind11/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    21396 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/include/pybind11/attr.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     6118 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/include/pybind11/buffer_info.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    94188 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/include/pybind11/cast.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     8185 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/include/pybind11/chrono.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      120 2020-11-24 18:48:09.000000 dionysus-2.0.9/bindings/python/pybind11/include/pybind11/common.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2037 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/include/pybind11/complex.h
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.127860 dionysus-2.0.9/bindings/python/pybind11/include/pybind11/detail/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    27803 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/include/pybind11/detail/class.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    40043 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/include/pybind11/detail/common.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3602 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/include/pybind11/detail/descr.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    16397 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/include/pybind11/detail/init.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    16373 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/include/pybind11/detail/internals.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1486 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/include/pybind11/detail/typeid.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    29086 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/include/pybind11/eigen.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     7843 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/include/pybind11/embed.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     5079 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/include/pybind11/eval.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3709 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/include/pybind11/functional.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     6002 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/include/pybind11/iostream.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    69310 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/include/pybind11/numpy.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     9085 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/include/pybind11/operators.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2049 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/include/pybind11/options.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)   107501 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/include/pybind11/pybind11.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    65764 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/include/pybind11/pytypes.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    14136 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/include/pybind11/stl.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    23356 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/include/pybind11/stl_bind.h
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.127860 dionysus-2.0.9/bindings/python/pybind11/pybind11/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      217 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/pybind11/__init__.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1158 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/pybind11/__main__.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      207 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/pybind11/_version.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      137 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/pybind11/_version.pyi
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      663 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/pybind11/commands.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)        0 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/pybind11/py.typed
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    15073 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/pybind11/setup_helpers.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1899 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/pybind11/setup_helpers.pyi
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      118 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/pyproject.toml
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1824 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/setup.cfg
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3499 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/setup.py
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.134527 dionysus-2.0.9/bindings/python/pybind11/tests/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    14353 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/CMakeLists.txt
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4841 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/conftest.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    11157 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/constructor_stats.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1819 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/cross_module_gil_utils.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      376 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/env.py
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.134527 dionysus-2.0.9/bindings/python/pybind11/tests/extra_python_package/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)        0 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/extra_python_package/pytest.ini
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     7074 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/extra_python_package/test_files.py
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.137860 dionysus-2.0.9/bindings/python/pybind11/tests/extra_setuptools/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)        0 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/extra_setuptools/pytest.ini
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2581 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/extra_setuptools/test_setuphelper.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2144 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/local_bindings.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     5389 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/object.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     5285 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/pybind11_cross_module_tests.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3647 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/pybind11_tests.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2272 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/pybind11_tests.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      626 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/pytest.ini
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      683 2022-06-24 21:35:37.000000 dionysus-2.0.9/bindings/python/pybind11/tests/requirements.txt
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      864 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_async.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      558 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_async.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     8048 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_buffers.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4869 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_buffers.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    10160 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_builtin_casters.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    14343 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_builtin_casters.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3702 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_call_policies.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     5728 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_call_policies.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     6339 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_callbacks.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4405 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_callbacks.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3406 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_chrono.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     6276 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_chrono.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    20916 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_class.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    14273 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_class.py
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.137860 dionysus-2.0.9/bindings/python/pybind11/tests/test_cmake_build/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2459 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_cmake_build/CMakeLists.txt
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      656 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_cmake_build/embed.cpp
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.137860 dionysus-2.0.9/bindings/python/pybind11/tests/test_cmake_build/installed_embed/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1175 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_cmake_build/installed_embed/CMakeLists.txt
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.137860 dionysus-2.0.9/bindings/python/pybind11/tests/test_cmake_build/installed_function/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1259 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_cmake_build/installed_function/CMakeLists.txt
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.137860 dionysus-2.0.9/bindings/python/pybind11/tests/test_cmake_build/installed_target/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1653 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_cmake_build/installed_target/CMakeLists.txt
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      152 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_cmake_build/main.cpp
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.137860 dionysus-2.0.9/bindings/python/pybind11/tests/test_cmake_build/subdirectory_embed/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1354 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_cmake_build/subdirectory_embed/CMakeLists.txt
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.137860 dionysus-2.0.9/bindings/python/pybind11/tests/test_cmake_build/subdirectory_function/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1127 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_cmake_build/subdirectory_function/CMakeLists.txt
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.137860 dionysus-2.0.9/bindings/python/pybind11/tests/test_cmake_build/subdirectory_target/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1332 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_cmake_build/subdirectory_target/CMakeLists.txt
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      166 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_cmake_build/test.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4147 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_constants_and_functions.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1200 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_constants_and_functions.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     9475 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_copy_move.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4645 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_copy_move.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     5446 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_custom_type_casters.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4015 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_custom_type_casters.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2331 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_docstring_options.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1489 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_docstring_options.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    16772 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_eigen.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    28282 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_eigen.py
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.137860 dionysus-2.0.9/bindings/python/pybind11/tests/test_embed/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1639 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_embed/CMakeLists.txt
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      637 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_embed/catch.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      554 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_embed/external_module.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    10209 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_embed/test_interpreter.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      219 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_embed/test_interpreter.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2610 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_enum.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     7023 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_enum.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2628 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_eval.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      768 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_eval.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      143 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_eval_call.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     7862 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_exceptions.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     6346 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_exceptions.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    16193 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_factory_constructors.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    16637 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_factory_constructors.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1760 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_gil_scoped.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3128 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_gil_scoped.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3381 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_iostream.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     5799 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_iostream.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     6489 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_kwargs_and_defaults.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    10048 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_kwargs_and_defaults.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4333 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_local_bindings.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     8107 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_local_bindings.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    19364 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_methods_and_attributes.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    17310 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_methods_and_attributes.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3742 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_modules.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2425 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_modules.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     8863 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_multiple_inheritance.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     9495 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_multiple_inheritance.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    17727 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_numpy_array.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    18647 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_numpy_array.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    17721 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_numpy_dtypes.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    13484 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_numpy_dtypes.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3832 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_numpy_vectorize.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     9709 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_numpy_vectorize.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2731 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_opaque_types.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1906 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_opaque_types.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     8431 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_operator_overloading.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4136 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_operator_overloading.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4609 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_pickling.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1191 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_pickling.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    13106 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_pytypes.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    13633 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_pytypes.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    13120 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_sequences_and_iterators.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     5966 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_sequences_and_iterators.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    16921 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_smart_ptr.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     9465 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_smart_ptr.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    12793 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_stl.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     8557 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_stl.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4655 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_stl_binders.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     7182 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_stl_binders.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4458 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_tagbased_polymorphic.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      765 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_tagbased_polymorphic.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      603 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_union.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      172 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_union.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    18454 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_virtual_functions.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    11664 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tests/test_virtual_functions.py
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.137860 dionysus-2.0.9/bindings/python/pybind11/tools/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2295 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tools/FindCatch.cmake
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3031 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tools/FindEigen3.cmake
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     9942 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tools/FindPythonLibsNew.cmake
+-rwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)     1427 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tools/check-style.sh
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      952 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tools/cmake_uninstall.cmake.in
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1121 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tools/libsize.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    14003 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tools/pybind11Common.cmake
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     7011 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tools/pybind11Config.cmake.in
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     8179 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tools/pybind11NewTools.cmake
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     6592 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tools/pybind11Tools.cmake
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)       94 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tools/pyproject.toml
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1822 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tools/setup_global.py.in
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      915 2021-01-19 17:30:02.000000 dionysus-2.0.9/bindings/python/pybind11/tools/setup_main.py.in
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4136 2020-11-24 18:48:01.000000 dionysus-2.0.9/bindings/python/rips.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2369 2020-11-24 18:48:01.000000 dionysus-2.0.9/bindings/python/simplex.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      511 2020-11-24 18:48:01.000000 dionysus-2.0.9/bindings/python/simplex.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1295 2020-11-24 18:48:01.000000 dionysus-2.0.9/bindings/python/wasserstein-distance.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    10795 2020-11-24 18:48:01.000000 dionysus-2.0.9/bindings/python/zigzag-persistence.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      135 2020-11-24 18:48:01.000000 dionysus-2.0.9/bindings/python/zigzag-persistence.h
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.137860 dionysus-2.0.9/dionysus/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2769 2019-05-15 17:40:38.000000 dionysus-2.0.9/dionysus/__init__.py
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.141193 dionysus-2.0.9/dionysus/__pycache__/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2986 2019-09-14 15:36:31.000000 dionysus-2.0.9/dionysus/__pycache__/__init__.cpython-37.pyc
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      233 2019-09-14 15:36:31.000000 dionysus-2.0.9/dionysus/__pycache__/_version.cpython-37.pyc
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     5131 2019-09-14 15:36:31.000000 dionysus-2.0.9/dionysus/__pycache__/plot.cpython-37.pyc
+-rwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)   947616 2019-05-14 20:48:27.000000 dionysus-2.0.9/dionysus/_dionysus.cpython-37m-darwin.so
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)       80 2020-11-24 19:09:20.000000 dionysus-2.0.9/dionysus/_version.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      310 2019-05-15 17:40:38.000000 dionysus-2.0.9/dionysus/_version.pyc
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4580 2019-05-15 17:40:38.000000 dionysus-2.0.9/dionysus/plot.py
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.141193 dionysus-2.0.9/dionysus.egg-info/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4559 2023-02-21 15:00:40.000000 dionysus-2.0.9/dionysus.egg-info/PKG-INFO
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    38754 2023-02-21 15:00:41.000000 dionysus-2.0.9/dionysus.egg-info/SOURCES.txt
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)        1 2023-02-21 15:00:40.000000 dionysus-2.0.9/dionysus.egg-info/dependency_links.txt
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)        1 2019-05-07 14:07:09.000000 dionysus-2.0.9/dionysus.egg-info/not-zip-safe
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)        9 2023-02-21 15:00:40.000000 dionysus-2.0.9/dionysus.egg-info/top_level.txt
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.141193 dionysus-2.0.9/doc/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2530 2020-11-24 18:48:01.000000 dionysus-2.0.9/doc/API.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      605 2020-11-24 18:48:01.000000 dionysus-2.0.9/doc/Makefile
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4907 2023-02-21 14:58:29.000000 dionysus-2.0.9/doc/conf.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3585 2021-01-19 17:30:02.000000 dionysus-2.0.9/doc/index.rst
+-rwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)       91 2022-06-24 21:44:41.000000 dionysus-2.0.9/doc/publish.sh
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.141193 dionysus-2.0.9/doc/tutorial/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      291 2020-11-24 18:48:01.000000 dionysus-2.0.9/doc/tutorial/alpha-shapes.rst_
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     7455 2020-11-24 18:48:01.000000 dionysus-2.0.9/doc/tutorial/basics.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3752 2020-11-24 18:48:01.000000 dionysus-2.0.9/doc/tutorial/cohomology.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      611 2021-01-19 17:30:02.000000 dionysus-2.0.9/doc/tutorial/diagnostics.rst
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.141193 dionysus-2.0.9/doc/tutorial/figures/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    57629 2020-11-24 18:48:01.000000 dionysus-2.0.9/doc/tutorial/figures/alpha-shape.png
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    16785 2020-11-24 18:48:01.000000 dionysus-2.0.9/doc/tutorial/figures/barcode.png
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    24440 2020-11-24 18:48:01.000000 dionysus-2.0.9/doc/tutorial/figures/filtration.png
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    79459 2020-11-24 18:48:01.000000 dionysus-2.0.9/doc/tutorial/figures/lower-star.png
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    17515 2020-11-24 18:48:01.000000 dionysus-2.0.9/doc/tutorial/figures/vietoris-rips.png
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)       96 2020-11-24 18:48:01.000000 dionysus-2.0.9/doc/tutorial/filtrations.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      177 2020-11-24 18:48:01.000000 dionysus-2.0.9/doc/tutorial/index.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2118 2020-11-24 18:48:01.000000 dionysus-2.0.9/doc/tutorial/lower-star.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3033 2020-11-24 18:48:01.000000 dionysus-2.0.9/doc/tutorial/omni-field.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)       96 2020-11-24 18:48:01.000000 dionysus-2.0.9/doc/tutorial/persistence.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1411 2020-11-24 18:48:01.000000 dionysus-2.0.9/doc/tutorial/plotting.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2080 2020-11-24 18:48:01.000000 dionysus-2.0.9/doc/tutorial/rips.rst
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4241 2020-11-24 18:48:01.000000 dionysus-2.0.9/doc/tutorial/zigzags.rst
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.141193 dionysus-2.0.9/examples/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      170 2020-11-24 18:48:01.000000 dionysus-2.0.9/examples/CMakeLists.txt
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.141193 dionysus-2.0.9/examples/filtration/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      330 2020-11-24 18:48:01.000000 dionysus-2.0.9/examples/filtration/CMakeLists.txt
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1885 2020-11-24 18:48:01.000000 dionysus-2.0.9/examples/filtration/filtration-persistence.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1994 2020-11-24 18:48:01.000000 dionysus-2.0.9/examples/filtration/zigzag-filtration-persistence.cpp
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.141193 dionysus-2.0.9/examples/include/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     9906 2020-11-24 18:48:01.000000 dionysus-2.0.9/examples/include/cnpy.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      683 2020-11-24 18:48:01.000000 dionysus-2.0.9/examples/include/common.h
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.141193 dionysus-2.0.9/examples/include/format/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    34701 2020-11-24 18:48:01.000000 dionysus-2.0.9/examples/include/format/format.cc
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    76882 2020-11-24 18:48:01.000000 dionysus-2.0.9/examples/include/format/format.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      113 2020-11-24 18:48:01.000000 dionysus-2.0.9/examples/include/format.h
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.144527 dionysus-2.0.9/examples/include/grid/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     7201 2020-11-24 18:48:01.000000 dionysus-2.0.9/examples/include/grid/box.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3686 2020-11-24 18:48:01.000000 dionysus-2.0.9/examples/include/grid/box.hpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     5308 2020-11-24 18:48:01.000000 dionysus-2.0.9/examples/include/grid/grid.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     5348 2020-11-24 18:48:01.000000 dionysus-2.0.9/examples/include/grid/point.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3028 2020-11-24 18:48:01.000000 dionysus-2.0.9/examples/include/grid/vertices.h
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.144527 dionysus-2.0.9/examples/include/opts/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    14740 2020-11-24 18:48:01.000000 dionysus-2.0.9/examples/include/opts/opts.h
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.144527 dionysus-2.0.9/examples/lzz/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      460 2020-11-24 18:48:01.000000 dionysus-2.0.9/examples/lzz/CMakeLists.txt
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     6020 2020-11-24 18:48:01.000000 dionysus-2.0.9/examples/lzz/extended-persistence.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4403 2020-11-24 18:48:01.000000 dionysus-2.0.9/examples/lzz/grid-topology.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2616 2020-11-24 18:48:01.000000 dionysus-2.0.9/examples/lzz/relative-lzz.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2685 2020-11-24 18:48:01.000000 dionysus-2.0.9/examples/lzz/relative-lzz.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     5329 2020-11-24 18:48:01.000000 dionysus-2.0.9/examples/lzz/relative-lzz.hpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1858 2020-11-24 18:48:01.000000 dionysus-2.0.9/examples/lzz/relative-zz-filtration.cpp
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.144527 dionysus-2.0.9/examples/omni-field/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      154 2020-11-24 18:48:01.000000 dionysus-2.0.9/examples/omni-field/CMakeLists.txt
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3465 2020-11-24 18:48:01.000000 dionysus-2.0.9/examples/omni-field/omni-field-persistence.cpp
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.144527 dionysus-2.0.9/examples/rips/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      326 2020-11-24 18:48:01.000000 dionysus-2.0.9/examples/rips/CMakeLists.txt
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2341 2020-11-24 18:48:01.000000 dionysus-2.0.9/examples/rips/rips-basic.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4754 2020-11-24 18:48:01.000000 dionysus-2.0.9/examples/rips/rips-pairwise.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    11527 2020-11-24 18:48:01.000000 dionysus-2.0.9/examples/rips/rips-zigzag.cpp
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.144527 dionysus-2.0.9/examples/src/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     8222 2020-11-24 18:48:01.000000 dionysus-2.0.9/examples/src/cnpy.cpp
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.114527 dionysus-2.0.9/ext/
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.144527 dionysus-2.0.9/ext/hera/
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.144527 dionysus-2.0.9/ext/hera/bottleneck/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1472 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/bottleneck/CMakeLists.txt
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3344 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/bottleneck/README
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.144527 dionysus-2.0.9/ext/hera/bottleneck/example/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      822 2020-02-19 19:15:56.000000 dionysus-2.0.9/ext/hera/bottleneck/example/CMakeLists.txt
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4726 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/bottleneck/example/bottleneck_dist.cpp
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.144527 dionysus-2.0.9/ext/hera/bottleneck/include/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    18619 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/bottleneck/include/basic_defs_bt.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     7327 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/bottleneck/include/bottleneck.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4513 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/bottleneck/include/bottleneck_detail.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    27907 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/bottleneck/include/bottleneck_detail.hpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4708 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/bottleneck/include/bound_match.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    20759 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/bottleneck/include/bound_match.hpp
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.144527 dionysus-2.0.9/ext/hera/bottleneck/include/catch/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)   420570 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/bottleneck/include/catch/catch.hpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2540 2020-02-19 19:15:56.000000 dionysus-2.0.9/ext/hera/bottleneck/include/def_debug_bt.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     7861 2020-02-19 19:15:56.000000 dionysus-2.0.9/ext/hera/bottleneck/include/diagram_reader.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1360 2020-02-19 19:15:56.000000 dionysus-2.0.9/ext/hera/bottleneck/include/diagram_traits.h
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.144527 dionysus-2.0.9/ext/hera/bottleneck/include/dnn/
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.144527 dionysus-2.0.9/ext/hera/bottleneck/include/dnn/geometry/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     7659 2020-02-19 19:15:56.000000 dionysus-2.0.9/ext/hera/bottleneck/include/dnn/geometry/euclidean-fixed.h
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.147860 dionysus-2.0.9/ext/hera/bottleneck/include/dnn/local/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4606 2020-02-19 19:15:56.000000 dionysus-2.0.9/ext/hera/bottleneck/include/dnn/local/kd-tree.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     8941 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/bottleneck/include/dnn/local/kd-tree.hpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4051 2020-02-19 19:15:56.000000 dionysus-2.0.9/ext/hera/bottleneck/include/dnn/local/search-functors.h
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.147860 dionysus-2.0.9/ext/hera/bottleneck/include/dnn/parallel/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     7252 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/bottleneck/include/dnn/parallel/tbb.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3192 2020-02-19 19:15:56.000000 dionysus-2.0.9/ext/hera/bottleneck/include/dnn/parallel/utils.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1251 2020-02-19 19:15:56.000000 dionysus-2.0.9/ext/hera/bottleneck/include/dnn/utils.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    10452 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/bottleneck/include/neighb_oracle.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2162 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/license.txt
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.147860 dionysus-2.0.9/ext/hera/wasserstein/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2772 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/wasserstein/CMakeLists.txt
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3453 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/wasserstein/README
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.147860 dionysus-2.0.9/ext/hera/wasserstein/example/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     7020 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/wasserstein/example/wasserstein_dist.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     5925 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/wasserstein/example/wasserstein_dist_dipha.cpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     6848 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/wasserstein/example/wasserstein_dist_point_cloud.cpp
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.147860 dionysus-2.0.9/ext/hera/wasserstein/include/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2533 2020-02-19 19:15:56.000000 dionysus-2.0.9/ext/hera/wasserstein/include/auction_oracle.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3990 2020-02-19 19:15:56.000000 dionysus-2.0.9/ext/hera/wasserstein/include/auction_oracle_base.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4195 2020-02-19 19:15:56.000000 dionysus-2.0.9/ext/hera/wasserstein/include/auction_oracle_base.hpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4074 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/wasserstein/include/auction_oracle_kdtree_pure_geom.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     8571 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/wasserstein/include/auction_oracle_kdtree_pure_geom.hpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     5099 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/wasserstein/include/auction_oracle_kdtree_restricted.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    21858 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/wasserstein/include/auction_oracle_kdtree_restricted.hpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     8598 2020-02-19 19:15:56.000000 dionysus-2.0.9/ext/hera/wasserstein/include/auction_oracle_kdtree_single_diag.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    27574 2020-02-19 19:15:56.000000 dionysus-2.0.9/ext/hera/wasserstein/include/auction_oracle_kdtree_single_diag.hpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     6762 2020-02-19 19:15:56.000000 dionysus-2.0.9/ext/hera/wasserstein/include/auction_oracle_lazy_heap.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    23570 2020-02-19 19:15:56.000000 dionysus-2.0.9/ext/hera/wasserstein/include/auction_oracle_lazy_heap.hpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4885 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/wasserstein/include/auction_oracle_stupid_sparse_restricted.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    21677 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/wasserstein/include/auction_oracle_stupid_sparse_restricted.hpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    10597 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/wasserstein/include/auction_runner_fr.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    44124 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/wasserstein/include/auction_runner_fr.hpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     5464 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/wasserstein/include/auction_runner_gs.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    19767 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/wasserstein/include/auction_runner_gs.hpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     6676 2020-02-19 19:15:56.000000 dionysus-2.0.9/ext/hera/wasserstein/include/auction_runner_gs_single_diag.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    31403 2020-02-19 19:15:56.000000 dionysus-2.0.9/ext/hera/wasserstein/include/auction_runner_gs_single_diag.hpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     8692 2020-02-19 19:15:56.000000 dionysus-2.0.9/ext/hera/wasserstein/include/auction_runner_jac.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    34787 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/wasserstein/include/auction_runner_jac.hpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    11024 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/wasserstein/include/basic_defs_ws.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     6570 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/wasserstein/include/basic_defs_ws.hpp
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.147860 dionysus-2.0.9/ext/hera/wasserstein/include/catch/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)   420570 2020-02-19 19:15:56.000000 dionysus-2.0.9/ext/hera/wasserstein/include/catch/catch.hpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2620 2020-02-19 19:15:56.000000 dionysus-2.0.9/ext/hera/wasserstein/include/def_debug_ws.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4920 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/wasserstein/include/diagonal_heap.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    15007 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/wasserstein/include/diagram_reader.h
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.151193 dionysus-2.0.9/ext/hera/wasserstein/include/dnn/
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.151193 dionysus-2.0.9/ext/hera/wasserstein/include/dnn/geometry/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    11518 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/wasserstein/include/dnn/geometry/euclidean-dynamic.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     8510 2020-02-19 19:15:56.000000 dionysus-2.0.9/ext/hera/wasserstein/include/dnn/geometry/euclidean-fixed.h
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.151193 dionysus-2.0.9/ext/hera/wasserstein/include/dnn/local/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4044 2020-02-19 19:15:56.000000 dionysus-2.0.9/ext/hera/wasserstein/include/dnn/local/kd-tree.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     8909 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/wasserstein/include/dnn/local/kd-tree.hpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3322 2020-02-19 19:15:56.000000 dionysus-2.0.9/ext/hera/wasserstein/include/dnn/local/search-functors.h
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.151193 dionysus-2.0.9/ext/hera/wasserstein/include/dnn/parallel/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     7228 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/wasserstein/include/dnn/parallel/tbb.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3213 2020-02-19 19:15:56.000000 dionysus-2.0.9/ext/hera/wasserstein/include/dnn/parallel/utils.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1251 2020-02-19 19:15:56.000000 dionysus-2.0.9/ext/hera/wasserstein/include/dnn/utils.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      528 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/wasserstein/include/hera_infinity.h
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.151193 dionysus-2.0.9/ext/hera/wasserstein/include/opts/
+-rwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)     9533 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/wasserstein/include/opts/opts.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    13180 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/wasserstein/include/wasserstein.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2913 2021-01-19 17:30:02.000000 dionysus-2.0.9/ext/hera/wasserstein/include/wasserstein_pure_geom.hpp
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.151193 dionysus-2.0.9/include/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    57327 2020-11-24 18:48:01.000000 dionysus-2.0.9/include/backward.hpp
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.154527 dionysus-2.0.9/include/dionysus/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4281 2020-11-24 18:48:01.000000 dionysus-2.0.9/include/dionysus/chain.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     5278 2020-11-24 18:48:01.000000 dionysus-2.0.9/include/dionysus/chain.hpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1459 2020-11-24 18:48:01.000000 dionysus-2.0.9/include/dionysus/clearing-reduction.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2120 2020-11-24 18:48:01.000000 dionysus-2.0.9/include/dionysus/clearing-reduction.hpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     4746 2020-11-24 18:48:01.000000 dionysus-2.0.9/include/dionysus/cohomology-persistence.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2469 2020-11-24 18:48:01.000000 dionysus-2.0.9/include/dionysus/cohomology-persistence.hpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3394 2020-11-24 18:48:01.000000 dionysus-2.0.9/include/dionysus/diagram.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3463 2020-11-24 18:48:01.000000 dionysus-2.0.9/include/dionysus/distances.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      992 2020-11-24 18:48:01.000000 dionysus-2.0.9/include/dionysus/distances.hpp
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.154527 dionysus-2.0.9/include/dionysus/dlog/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1688 2020-11-24 18:48:01.000000 dionysus-2.0.9/include/dionysus/dlog/progress.h
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.154527 dionysus-2.0.9/include/dionysus/fields/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2660 2020-11-24 18:48:01.000000 dionysus-2.0.9/include/dionysus/fields/q.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      946 2020-11-24 18:48:01.000000 dionysus-2.0.9/include/dionysus/fields/z2.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1633 2020-11-24 18:48:01.000000 dionysus-2.0.9/include/dionysus/fields/zp.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     6013 2020-11-24 18:48:01.000000 dionysus-2.0.9/include/dionysus/filtration.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     5814 2020-11-24 18:48:01.000000 dionysus-2.0.9/include/dionysus/omni-field-persistence.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     6877 2020-11-24 18:48:01.000000 dionysus-2.0.9/include/dionysus/omni-field-persistence.hpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2148 2020-11-24 18:48:01.000000 dionysus-2.0.9/include/dionysus/ordinary-persistence.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2188 2020-11-24 18:48:01.000000 dionysus-2.0.9/include/dionysus/pair-recorder.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     7912 2020-11-24 18:48:01.000000 dionysus-2.0.9/include/dionysus/reduced-matrix.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2231 2020-11-24 18:48:01.000000 dionysus-2.0.9/include/dionysus/reduced-matrix.hpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3147 2020-11-24 18:48:01.000000 dionysus-2.0.9/include/dionysus/reduction.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3445 2020-11-24 18:48:01.000000 dionysus-2.0.9/include/dionysus/relative-homology-zigzag.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3323 2020-11-24 18:48:01.000000 dionysus-2.0.9/include/dionysus/relative-homology-zigzag.hpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     6634 2023-02-21 14:58:34.000000 dionysus-2.0.9/include/dionysus/rips.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     5735 2020-11-24 18:48:01.000000 dionysus-2.0.9/include/dionysus/rips.hpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     2098 2020-11-24 18:48:01.000000 dionysus-2.0.9/include/dionysus/row-reduction.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3765 2020-11-24 18:48:01.000000 dionysus-2.0.9/include/dionysus/row-reduction.hpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    11828 2023-02-21 14:58:34.000000 dionysus-2.0.9/include/dionysus/simplex.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     8269 2020-11-24 18:48:01.000000 dionysus-2.0.9/include/dionysus/sparse-row-matrix.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3398 2020-11-24 18:48:01.000000 dionysus-2.0.9/include/dionysus/sparse-row-matrix.hpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1543 2020-11-24 18:48:01.000000 dionysus-2.0.9/include/dionysus/standard-reduction.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     1771 2020-11-24 18:48:01.000000 dionysus-2.0.9/include/dionysus/standard-reduction.hpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      433 2020-11-24 18:48:01.000000 dionysus-2.0.9/include/dionysus/trails-chains.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     5693 2023-02-21 14:58:34.000000 dionysus-2.0.9/include/dionysus/zigzag-persistence.h
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    21382 2023-02-21 14:58:34.000000 dionysus-2.0.9/include/dionysus/zigzag-persistence.hpp
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      425 2021-01-19 17:30:02.000000 dionysus-2.0.9/peru.yaml
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)       80 2023-02-21 15:00:41.161193 dionysus-2.0.9/setup.cfg
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)     3848 2021-01-19 17:30:02.000000 dionysus-2.0.9/setup.py
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.154527 dionysus-2.0.9/src/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      757 2020-11-24 18:48:01.000000 dionysus-2.0.9/src/backward.cpp
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.154527 dionysus-2.0.9/tests/
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.114527 dionysus-2.0.9/tests/data/
+drwxr-xr-x   0 dmitriy   (1000) dmitriy   (1000)        0 2023-02-21 15:00:41.154527 dionysus-2.0.9/tests/data/issue39/
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    35793 2021-01-19 17:30:02.000000 dionysus-2.0.9/tests/data/issue39/dgm1.txt
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)    36478 2021-01-19 17:30:02.000000 dionysus-2.0.9/tests/data/issue39/dgm2.txt
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      222 2020-11-24 18:48:01.000000 dionysus-2.0.9/tests/test_distances.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      288 2021-01-19 17:30:02.000000 dionysus-2.0.9/tests/test_issue39.py
+-rw-r--r--   0 dmitriy   (1000) dmitriy   (1000)      558 2022-06-24 21:35:37.000000 dionysus-2.0.9/tests/test_issue47.py
```

### Comparing `dionysus-2.0.8/.build.yml` & `dionysus-2.0.9/.build.yml`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/CMakeLists.txt` & `dionysus-2.0.9/CMakeLists.txt`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/LEGAL.txt` & `dionysus-2.0.9/LEGAL.txt`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/LICENSE.txt` & `dionysus-2.0.9/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/NOTICES.txt` & `dionysus-2.0.9/NOTICES.txt`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/PKG-INFO` & `dionysus-2.0.9/PKG-INFO`

 * *Files 26% similar despite different names*

```diff
@@ -1,93 +1,15 @@
-Metadata-Version: 1.1
+Metadata-Version: 2.1
 Name: dionysus
-Version: 2.0.8
+Version: 2.0.9
 Summary: Library for computing persistent homology
 Home-page: http://mrzv.org/software/dionysus2
 Author: Dmitriy Morozov
 Author-email: dmitriy@mrzv.org
 License: BSD
-Description: Dionysus 2
-        ==========
-        
-        Dionysus is a computational topology package focused on
-        persistent homology. It is written in C++, with Python bindings.
-        The second version (`previous version <http://mrzv.org/software/dionysus/>`_)
-        is re-written from scratch, which helps it accomplish a few goals:
-        
-          * `Modified BSD license <https://github.com/mrzv/dionysus/blob/master/LICENSE.txt>`_ (because GPL causes too many problems in academic software).
-          * No dependency on Boost.Python; Dionysus 2 uses (and includes) `PyBind11 <https://github.com/pybind/pybind11>`_ instead, which greatly simplifies installation.
-          * Cleaner, more consistent internal design (for example, all algorithms support arbitrary fields).
-          * Some new algorithms, e.g., `omni-field persistence <http://mrzv.org/software/dionysus2/tutorial/omni-field.html#omni-field>`_ and Wasserstein and bottleneck `distance computation <http://mrzv.org/software/dionysus2/tutorial/basics.html#diagram-distances>`_ from `Hera <https://bitbucket.org/grey_narn/hera>`_.
-          * A few `plotting <http://mrzv.org/software/dionysus2/tutorial/plotting.html#plotting>`_ routines, based on `Matplotlib <https://matplotlib.org/>`_.
-          * Better integration with `NumPy <http://www.numpy.org/>`_.
-        
-        Features that haven't (yet) made it over from `Dionysus 1 <http://mrzv.org/software/dionysus>`_ include vineyards.
-        Alpha shape filtrations are available via `DioDe <https://github.com/mrzv/diode>`_.
-        
-        **Dependencies:**
-          * `Boost <http://www.boost.org/>`_, although Dionysus 2 doesn't link any of its libraries, so it's considerably easier to build the project.
-          * (Optional) `SciPy <https://www.scipy.org/>`_ for the LSQR routine used in `circular coordinates <http://mrzv.org/software/dionysus2/tutorial/cohomology.html#circular>`_.
-          * (Optional) `Maplotlib <https://matplotlib.org/>`_ for plotting.
-        
-        **Requirements:**
-          * Boost needs to be at least version 1.55.
-          * If you are using GCC, the oldest supported version is 5.4.
-        
-        **Contact:**
-          * please use the `dionysus mailing list <https://groups.io/g/dionysus/>`_
-            for all questions and discussion related to the library;
-          * GitHub's `issue tracker <https://github.com/mrzv/dionysus/issues>`_
-            is a central location for bug reports and feature requests.
-        
-        Get, Build, Install
-        -------------------
-        
-        The simplest way to install Dionysus, as a Python package, is from `PyPI <https://pypi.org/project/dionysus/>`_:
-        
-        .. parsed-literal::
-        
-            pip install --verbose dionysus
-        
-        Pass ``--upgrade`` to ``pip``, if you have already installed some version of Dionysus.
-        
-        Alternatively, you can install it directly from the development repository (this gives you the latest version):
-        
-        .. parsed-literal::
-        
-            pip install --verbose `git+https://github.com/mrzv/dionysus.git <https://github.com/mrzv/dionysus.git>`_
-        
-        Alternatively, you can clone and build everything by hand.
-        To get Dionysus 2, either clone its `repository <https://github.com/mrzv/dionysus>`_:
-        
-        .. parsed-literal::
-        
-            git clone `<https://github.com/mrzv/dionysus.git>`_
-        
-        or download it as a `Zip archive <https://github.com/mrzv/dionysus/archive/master.zip>`_.
-        
-        To build the project::
-        
-            mkdir build
-            cd build
-            cmake ..
-            make
-        
-        To use the Python bindings, either launch Python from ``.../build/bindings/python`` or add this directory to your ``PYTHONPATH`` variable, by adding::
-        
-            export PYTHONPATH=.../build/bindings/python:$PYTHONPATH
-        
-        to your ``~/.bashrc`` or ``~/.zshrc``.
-        
-        Documentation
-        -------------
-        
-        Documentation for Dionysus can be found `here <http://mrzv.org/software/dionysus2/>`_.
-        
-Platform: UNKNOWN
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Intended Audience :: Developers
 Classifier: Intended Audience :: Education
 Classifier: Intended Audience :: Science/Research
 Classifier: Topic :: Software Development :: Libraries :: Python Modules
 Classifier: Topic :: Utilities
 Classifier: Programming Language :: C++
@@ -95,7 +17,86 @@
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.2
 Classifier: Programming Language :: Python :: 3.3
 Classifier: Programming Language :: Python :: 3.4
 Classifier: Programming Language :: Python :: 3.5
 Classifier: Programming Language :: Python :: 3.6
 Classifier: License :: OSI Approved :: BSD License
+License-File: LICENSE.txt
+License-File: NOTICES.txt
+
+Dionysus 2
+==========
+
+Dionysus is a computational topology package focused on
+persistent homology. It is written in C++, with Python bindings.
+The second version (`previous version <http://mrzv.org/software/dionysus/>`_)
+is re-written from scratch, which helps it accomplish a few goals:
+
+  * `Modified BSD license <https://github.com/mrzv/dionysus/blob/master/LICENSE.txt>`_ (because GPL causes too many problems in academic software).
+  * No dependency on Boost.Python; Dionysus 2 uses (and includes) `PyBind11 <https://github.com/pybind/pybind11>`_ instead, which greatly simplifies installation.
+  * Cleaner, more consistent internal design (for example, all algorithms support arbitrary fields).
+  * Some new algorithms, e.g., `omni-field persistence <http://mrzv.org/software/dionysus2/tutorial/omni-field.html#omni-field>`_ and Wasserstein and bottleneck `distance computation <http://mrzv.org/software/dionysus2/tutorial/basics.html#diagram-distances>`_ from `Hera <https://bitbucket.org/grey_narn/hera>`_.
+  * A few `plotting <http://mrzv.org/software/dionysus2/tutorial/plotting.html#plotting>`_ routines, based on `Matplotlib <https://matplotlib.org/>`_.
+  * Better integration with `NumPy <http://www.numpy.org/>`_.
+
+Features that haven't (yet) made it over from `Dionysus 1 <http://mrzv.org/software/dionysus>`_ include vineyards.
+Alpha shape filtrations are available via `DioDe <https://github.com/mrzv/diode>`_.
+
+**Dependencies:**
+  * `Boost <http://www.boost.org/>`_, although Dionysus 2 doesn't link any of its libraries, so it's considerably easier to build the project.
+  * (Optional) `SciPy <https://www.scipy.org/>`_ for the LSQR routine used in `circular coordinates <http://mrzv.org/software/dionysus2/tutorial/cohomology.html#circular>`_.
+  * (Optional) `Matplotlib <https://matplotlib.org/>`_ for plotting.
+
+**Requirements:**
+  * Boost needs to be at least version 1.55.
+  * If you are using GCC, the oldest supported version is 5.4.
+
+**Contact:**
+  * please use the `dionysus mailing list <https://groups.io/g/dionysus/>`_
+    for all questions and discussion related to the library;
+  * GitHub's `issue tracker <https://github.com/mrzv/dionysus/issues>`_
+    is a central location for bug reports and feature requests.
+
+Get, Build, Install
+-------------------
+
+The simplest way to install Dionysus, as a Python package, is from `PyPI <https://pypi.org/project/dionysus/>`_:
+
+.. parsed-literal::
+
+    pip install --verbose dionysus
+
+Pass ``--upgrade`` to ``pip``, if you have already installed some version of Dionysus.
+
+Alternatively, you can install it directly from the development repository (this gives you the latest version):
+
+.. parsed-literal::
+
+    pip install --verbose `git+https://github.com/mrzv/dionysus.git <https://github.com/mrzv/dionysus.git>`_
+
+Alternatively, you can clone and build everything by hand.
+To get Dionysus 2, either clone its `repository <https://github.com/mrzv/dionysus>`_:
+
+.. parsed-literal::
+
+    git clone `<https://github.com/mrzv/dionysus.git>`_
+
+or download it as a `Zip archive <https://github.com/mrzv/dionysus/archive/master.zip>`_.
+
+To build the project::
+
+    mkdir build
+    cd build
+    cmake ..
+    make
+
+To use the Python bindings, either launch Python from ``.../build/bindings/python`` or add this directory to your ``PYTHONPATH`` variable, by adding::
+
+    export PYTHONPATH=.../build/bindings/python:$PYTHONPATH
+
+to your ``~/.bashrc`` or ``~/.zshrc``.
+
+Documentation
+-------------
+
+Documentation for Dionysus can be found `here <http://mrzv.org/software/dionysus2/>`_.
```

### Comparing `dionysus-2.0.8/Pipfile.lock` & `dionysus-2.0.9/Pipfile.lock`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/README.rst` & `dionysus-2.0.9/README.rst`

 * *Files 1% similar despite different names*

```diff
@@ -15,15 +15,15 @@
 
 Features that haven't (yet) made it over from `Dionysus 1 <http://mrzv.org/software/dionysus>`_ include vineyards.
 Alpha shape filtrations are available via `DioDe <https://github.com/mrzv/diode>`_.
 
 **Dependencies:**
   * `Boost <http://www.boost.org/>`_, although Dionysus 2 doesn't link any of its libraries, so it's considerably easier to build the project.
   * (Optional) `SciPy <https://www.scipy.org/>`_ for the LSQR routine used in `circular coordinates <http://mrzv.org/software/dionysus2/tutorial/cohomology.html#circular>`_.
-  * (Optional) `Maplotlib <https://matplotlib.org/>`_ for plotting.
+  * (Optional) `Matplotlib <https://matplotlib.org/>`_ for plotting.
 
 **Requirements:**
   * Boost needs to be at least version 1.55.
   * If you are using GCC, the oldest supported version is 5.4.
 
 **Contact:**
   * please use the `dionysus mailing list <https://groups.io/g/dionysus/>`_
```

### Comparing `dionysus-2.0.8/bindings/python/CMakeLists.txt` & `dionysus-2.0.9/bindings/python/CMakeLists.txt`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/bottleneck-distance.cpp` & `dionysus-2.0.9/bindings/python/bottleneck-distance.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/chain.h` & `dionysus-2.0.9/bindings/python/chain.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/cohomology-persistence.cpp` & `dionysus-2.0.9/bindings/python/cohomology-persistence.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/diagram.cpp` & `dionysus-2.0.9/bindings/python/diagram.cpp`

 * *Files 18% similar despite different names*

```diff
@@ -24,14 +24,17 @@
                       {
                           PyDiagram* dgm = new PyDiagram;
                           for (auto& pt : pts)
                               dgm->emplace_back(std::get<0>(pt), std::get<1>(pt), 0);
                           return dgm;
                       }), "initialize diagram from a list of (birth,death) points")
         .def("append",          &PyDiagram::push_back, "p"_a,   "append point to the diagram")
+        .def("append",          [](PyDiagram& dgm, PyDiagram::Value birth, PyDiagram::Value death) { dgm.emplace_back(birth, death, 0); },
+                                "birth"_a, "death"_a,
+                                 "append point to the diagram")
         .def("__getitem__",     &PyDiagram::operator[],         "access `i`-th point")
         .def("__len__",         &PyDiagram::size,               "size of the diagram")
         .def("__iter__",        [](const PyDiagram& dgm) { return py::make_iterator(dgm.begin(), dgm.end()); },
                                 py::keep_alive<0, 1>() /* Essential: keep object alive while iterator exists */,
                                 "iterate over the points of the diagram")
         .def("__repr__",        [](const PyDiagram& dgm)        { std::ostringstream oss; oss << "Diagram with " << dgm.size() << " points"; return oss.str(); })
         .def(py::pickle(
@@ -56,14 +59,19 @@
                 return dgm;
             }
         ));
     ;
 
     using Point = PyDiagram::Point;
     py::class_<Point>(m, "DiagramPoint", "persistence diagram point")
+        .def(py::init([](PyDiagram::Value birth, PyDiagram::Value death)
+                      {
+                          Point* p = new Point(birth, death, 0);
+                          return p;
+                      }), "initialize diagram point from (birth,death) values")
         .def_property_readonly("birth",  &Point::birth, "birth value")
         .def_property_readonly("death",  &Point::death, "death value")
         .def_readwrite("data",           &Point::data,  "auxiliary data associated to the point (e.g., birth index)")
         .def(py::self == py::self)
         .def("__hash__",        [](const Point& p)              { return boost::hash<Point::Parent>()(p); },        "hash of the point")
         .def("__repr__",        [](const Point& p)              { std::ostringstream oss; oss << '(' << p.birth() << ',' << p.death() << ')'; return oss.str(); })
     ;
```

### Comparing `dionysus-2.0.8/bindings/python/dionysus/__init__.py` & `dionysus-2.0.9/bindings/python/dionysus/__init__.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/dionysus/plot.py` & `dionysus-2.0.9/dionysus/plot.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/dionysus.cpp` & `dionysus-2.0.9/bindings/python/dionysus.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/filtration.cpp` & `dionysus-2.0.9/bindings/python/filtration.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/freudenthal.cpp` & `dionysus-2.0.9/bindings/python/freudenthal.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/omni-field-persistence.cpp` & `dionysus-2.0.9/bindings/python/omni-field-persistence.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/persistence.cpp` & `dionysus-2.0.9/bindings/python/persistence.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/progress.h` & `dionysus-2.0.9/bindings/python/progress.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/.appveyor.yml` & `dionysus-2.0.9/bindings/python/pybind11/.appveyor.yml`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/.cmake-format.yaml` & `dionysus-2.0.9/bindings/python/pybind11/.cmake-format.yaml`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/.github/CONTRIBUTING.md` & `dionysus-2.0.9/bindings/python/pybind11/.github/CONTRIBUTING.md`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/.github/ISSUE_TEMPLATE/bug-report.md` & `dionysus-2.0.9/bindings/python/pybind11/.github/ISSUE_TEMPLATE/bug-report.md`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/.github/ISSUE_TEMPLATE/feature-request.md` & `dionysus-2.0.9/bindings/python/pybind11/.github/ISSUE_TEMPLATE/feature-request.md`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/.github/ISSUE_TEMPLATE/question.md` & `dionysus-2.0.9/bindings/python/pybind11/.github/ISSUE_TEMPLATE/question.md`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/.github/dependabot.yml` & `dionysus-2.0.9/bindings/python/pybind11/.github/dependabot.yml`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/.github/workflows/ci.yml` & `dionysus-2.0.9/bindings/python/pybind11/.github/workflows/ci.yml`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/.github/workflows/configure.yml` & `dionysus-2.0.9/bindings/python/pybind11/.github/workflows/configure.yml`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/.github/workflows/format.yml` & `dionysus-2.0.9/bindings/python/pybind11/.github/workflows/format.yml`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/.github/workflows/pip.yml` & `dionysus-2.0.9/bindings/python/pybind11/.github/workflows/pip.yml`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/.pre-commit-config.yaml` & `dionysus-2.0.9/bindings/python/pybind11/.pre-commit-config.yaml`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/CMakeLists.txt` & `dionysus-2.0.9/bindings/python/pybind11/CMakeLists.txt`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/LICENSE` & `dionysus-2.0.9/bindings/python/pybind11/LICENSE`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/README.rst` & `dionysus-2.0.9/bindings/python/pybind11/README.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/Doxyfile` & `dionysus-2.0.9/bindings/python/pybind11/docs/Doxyfile`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/Makefile` & `dionysus-2.0.9/bindings/python/pybind11/docs/Makefile`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/advanced/cast/chrono.rst` & `dionysus-2.0.9/bindings/python/pybind11/docs/advanced/cast/chrono.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/advanced/cast/custom.rst` & `dionysus-2.0.9/bindings/python/pybind11/docs/advanced/cast/custom.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/advanced/cast/eigen.rst` & `dionysus-2.0.9/bindings/python/pybind11/docs/advanced/cast/eigen.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/advanced/cast/functional.rst` & `dionysus-2.0.9/bindings/python/pybind11/docs/advanced/cast/functional.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/advanced/cast/index.rst` & `dionysus-2.0.9/bindings/python/pybind11/docs/advanced/cast/index.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/advanced/cast/overview.rst` & `dionysus-2.0.9/bindings/python/pybind11/docs/advanced/cast/overview.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/advanced/cast/stl.rst` & `dionysus-2.0.9/bindings/python/pybind11/docs/advanced/cast/stl.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/advanced/cast/strings.rst` & `dionysus-2.0.9/bindings/python/pybind11/docs/advanced/cast/strings.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/advanced/classes.rst` & `dionysus-2.0.9/bindings/python/pybind11/docs/advanced/classes.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/advanced/embedding.rst` & `dionysus-2.0.9/bindings/python/pybind11/docs/advanced/embedding.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/advanced/exceptions.rst` & `dionysus-2.0.9/bindings/python/pybind11/docs/advanced/exceptions.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/advanced/functions.rst` & `dionysus-2.0.9/bindings/python/pybind11/docs/advanced/functions.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/advanced/misc.rst` & `dionysus-2.0.9/bindings/python/pybind11/docs/advanced/misc.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/advanced/pycpp/numpy.rst` & `dionysus-2.0.9/bindings/python/pybind11/docs/advanced/pycpp/numpy.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/advanced/pycpp/object.rst` & `dionysus-2.0.9/bindings/python/pybind11/docs/advanced/pycpp/object.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/advanced/pycpp/utilities.rst` & `dionysus-2.0.9/bindings/python/pybind11/docs/advanced/pycpp/utilities.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/advanced/smart_ptrs.rst` & `dionysus-2.0.9/bindings/python/pybind11/docs/advanced/smart_ptrs.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/basics.rst` & `dionysus-2.0.9/bindings/python/pybind11/docs/basics.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/benchmark.py` & `dionysus-2.0.9/bindings/python/pybind11/docs/benchmark.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/benchmark.rst` & `dionysus-2.0.9/bindings/python/pybind11/docs/benchmark.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/changelog.rst` & `dionysus-2.0.9/bindings/python/pybind11/docs/changelog.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/classes.rst` & `dionysus-2.0.9/bindings/python/pybind11/docs/classes.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/compiling.rst` & `dionysus-2.0.9/bindings/python/pybind11/docs/compiling.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/conf.py` & `dionysus-2.0.9/bindings/python/pybind11/docs/conf.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/faq.rst` & `dionysus-2.0.9/bindings/python/pybind11/docs/faq.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/index.rst` & `dionysus-2.0.9/bindings/python/pybind11/docs/index.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/installing.rst` & `dionysus-2.0.9/bindings/python/pybind11/docs/installing.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/limitations.rst` & `dionysus-2.0.9/bindings/python/pybind11/docs/limitations.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/pybind11-logo.png` & `dionysus-2.0.9/bindings/python/pybind11/docs/pybind11-logo.png`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/pybind11_vs_boost_python1.png` & `dionysus-2.0.9/bindings/python/pybind11/docs/pybind11_vs_boost_python1.png`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/pybind11_vs_boost_python1.svg` & `dionysus-2.0.9/bindings/python/pybind11/docs/pybind11_vs_boost_python1.svg`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/pybind11_vs_boost_python2.png` & `dionysus-2.0.9/bindings/python/pybind11/docs/pybind11_vs_boost_python2.png`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/pybind11_vs_boost_python2.svg` & `dionysus-2.0.9/bindings/python/pybind11/docs/pybind11_vs_boost_python2.svg`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/reference.rst` & `dionysus-2.0.9/bindings/python/pybind11/docs/reference.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/release.rst` & `dionysus-2.0.9/bindings/python/pybind11/docs/release.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/docs/upgrade.rst` & `dionysus-2.0.9/bindings/python/pybind11/docs/upgrade.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/include/pybind11/attr.h` & `dionysus-2.0.9/bindings/python/pybind11/include/pybind11/attr.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/include/pybind11/buffer_info.h` & `dionysus-2.0.9/bindings/python/pybind11/include/pybind11/buffer_info.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/include/pybind11/cast.h` & `dionysus-2.0.9/bindings/python/pybind11/include/pybind11/cast.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/include/pybind11/chrono.h` & `dionysus-2.0.9/bindings/python/pybind11/include/pybind11/chrono.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/include/pybind11/complex.h` & `dionysus-2.0.9/bindings/python/pybind11/include/pybind11/complex.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/include/pybind11/detail/class.h` & `dionysus-2.0.9/bindings/python/pybind11/include/pybind11/detail/class.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/include/pybind11/detail/common.h` & `dionysus-2.0.9/bindings/python/pybind11/include/pybind11/detail/common.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/include/pybind11/detail/descr.h` & `dionysus-2.0.9/bindings/python/pybind11/include/pybind11/detail/descr.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/include/pybind11/detail/init.h` & `dionysus-2.0.9/bindings/python/pybind11/include/pybind11/detail/init.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/include/pybind11/detail/internals.h` & `dionysus-2.0.9/bindings/python/pybind11/include/pybind11/detail/internals.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/include/pybind11/detail/typeid.h` & `dionysus-2.0.9/bindings/python/pybind11/include/pybind11/detail/typeid.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/include/pybind11/eigen.h` & `dionysus-2.0.9/bindings/python/pybind11/include/pybind11/eigen.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/include/pybind11/embed.h` & `dionysus-2.0.9/bindings/python/pybind11/include/pybind11/embed.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/include/pybind11/eval.h` & `dionysus-2.0.9/bindings/python/pybind11/include/pybind11/eval.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/include/pybind11/functional.h` & `dionysus-2.0.9/bindings/python/pybind11/include/pybind11/functional.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/include/pybind11/iostream.h` & `dionysus-2.0.9/bindings/python/pybind11/include/pybind11/iostream.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/include/pybind11/numpy.h` & `dionysus-2.0.9/bindings/python/pybind11/include/pybind11/numpy.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/include/pybind11/operators.h` & `dionysus-2.0.9/bindings/python/pybind11/include/pybind11/operators.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/include/pybind11/options.h` & `dionysus-2.0.9/bindings/python/pybind11/include/pybind11/options.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/include/pybind11/pybind11.h` & `dionysus-2.0.9/bindings/python/pybind11/include/pybind11/pybind11.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/include/pybind11/pytypes.h` & `dionysus-2.0.9/bindings/python/pybind11/include/pybind11/pytypes.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/include/pybind11/stl.h` & `dionysus-2.0.9/bindings/python/pybind11/include/pybind11/stl.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/include/pybind11/stl_bind.h` & `dionysus-2.0.9/bindings/python/pybind11/include/pybind11/stl_bind.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/pybind11/__main__.py` & `dionysus-2.0.9/bindings/python/pybind11/pybind11/__main__.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/pybind11/commands.py` & `dionysus-2.0.9/bindings/python/pybind11/pybind11/commands.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/pybind11/setup_helpers.py` & `dionysus-2.0.9/bindings/python/pybind11/pybind11/setup_helpers.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/pybind11/setup_helpers.pyi` & `dionysus-2.0.9/bindings/python/pybind11/pybind11/setup_helpers.pyi`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/setup.cfg` & `dionysus-2.0.9/bindings/python/pybind11/setup.cfg`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/setup.py` & `dionysus-2.0.9/bindings/python/pybind11/setup.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/CMakeLists.txt` & `dionysus-2.0.9/bindings/python/pybind11/tests/CMakeLists.txt`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/conftest.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/conftest.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/constructor_stats.h` & `dionysus-2.0.9/bindings/python/pybind11/tests/constructor_stats.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/cross_module_gil_utils.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/cross_module_gil_utils.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/extra_python_package/test_files.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/extra_python_package/test_files.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/extra_setuptools/test_setuphelper.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/extra_setuptools/test_setuphelper.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/local_bindings.h` & `dionysus-2.0.9/bindings/python/pybind11/tests/local_bindings.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/object.h` & `dionysus-2.0.9/bindings/python/pybind11/tests/object.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/pybind11_cross_module_tests.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/pybind11_cross_module_tests.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/pybind11_tests.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/pybind11_tests.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/pybind11_tests.h` & `dionysus-2.0.9/bindings/python/pybind11/tests/pybind11_tests.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/pytest.ini` & `dionysus-2.0.9/bindings/python/pybind11/tests/pytest.ini`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/requirements.txt` & `dionysus-2.0.9/bindings/python/pybind11/tests/requirements.txt`

 * *Files 1% similar despite different names*

```diff
@@ -1,8 +1,8 @@
 --extra-index-url https://antocuni.github.io/pypy-wheels/manylinux2010/
 numpy==1.16.6; python_version<"3.6" and sys_platform!="win32"
-numpy==1.18.0; platform_python_implementation=="PyPy" and sys_platform=="darwin" and python_version>="3.6"
+numpy==1.22.0; platform_python_implementation=="PyPy" and sys_platform=="darwin" and python_version>="3.6"
 numpy==1.19.3; (platform_python_implementation!="PyPy" or sys_platform=="linux") and python_version>="3.6" and python_version<"3.10"
 pytest==4.6.9; python_version<"3.5"
 pytest==5.4.3; python_version>="3.5"
 scipy==1.2.3; (platform_python_implementation!="PyPy" or sys_platform=="linux") and python_version<"3.6"
 scipy==1.5.2; (platform_python_implementation!="PyPy" or sys_platform=="linux") and python_version>="3.6" and python_version<"3.9"
```

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_async.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_async.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_async.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_async.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_buffers.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_buffers.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_buffers.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_buffers.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_builtin_casters.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_builtin_casters.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_builtin_casters.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_builtin_casters.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_call_policies.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_call_policies.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_call_policies.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_call_policies.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_callbacks.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_callbacks.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_callbacks.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_callbacks.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_chrono.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_chrono.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_chrono.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_chrono.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_class.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_class.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_class.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_class.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_cmake_build/CMakeLists.txt` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_cmake_build/CMakeLists.txt`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_cmake_build/embed.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_cmake_build/embed.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_cmake_build/installed_embed/CMakeLists.txt` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_cmake_build/installed_embed/CMakeLists.txt`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_cmake_build/installed_function/CMakeLists.txt` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_cmake_build/installed_function/CMakeLists.txt`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_cmake_build/installed_target/CMakeLists.txt` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_cmake_build/installed_target/CMakeLists.txt`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_cmake_build/subdirectory_embed/CMakeLists.txt` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_cmake_build/subdirectory_embed/CMakeLists.txt`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_cmake_build/subdirectory_function/CMakeLists.txt` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_cmake_build/subdirectory_function/CMakeLists.txt`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_cmake_build/subdirectory_target/CMakeLists.txt` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_cmake_build/subdirectory_target/CMakeLists.txt`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_constants_and_functions.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_constants_and_functions.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_constants_and_functions.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_constants_and_functions.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_copy_move.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_copy_move.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_copy_move.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_copy_move.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_custom_type_casters.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_custom_type_casters.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_custom_type_casters.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_custom_type_casters.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_docstring_options.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_docstring_options.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_docstring_options.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_docstring_options.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_eigen.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_eigen.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_eigen.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_eigen.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_embed/CMakeLists.txt` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_embed/CMakeLists.txt`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_embed/catch.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_embed/catch.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_embed/external_module.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_embed/external_module.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_embed/test_interpreter.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_embed/test_interpreter.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_enum.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_enum.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_enum.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_enum.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_eval.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_eval.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_eval.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_eval.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_exceptions.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_exceptions.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_exceptions.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_exceptions.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_factory_constructors.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_factory_constructors.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_factory_constructors.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_factory_constructors.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_gil_scoped.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_gil_scoped.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_gil_scoped.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_gil_scoped.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_iostream.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_iostream.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_iostream.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_iostream.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_kwargs_and_defaults.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_kwargs_and_defaults.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_kwargs_and_defaults.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_kwargs_and_defaults.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_local_bindings.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_local_bindings.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_local_bindings.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_local_bindings.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_methods_and_attributes.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_methods_and_attributes.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_methods_and_attributes.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_methods_and_attributes.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_modules.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_modules.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_modules.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_modules.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_multiple_inheritance.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_multiple_inheritance.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_multiple_inheritance.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_multiple_inheritance.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_numpy_array.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_numpy_array.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_numpy_array.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_numpy_array.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_numpy_dtypes.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_numpy_dtypes.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_numpy_dtypes.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_numpy_dtypes.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_numpy_vectorize.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_numpy_vectorize.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_numpy_vectorize.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_numpy_vectorize.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_opaque_types.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_opaque_types.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_opaque_types.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_opaque_types.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_operator_overloading.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_operator_overloading.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_operator_overloading.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_operator_overloading.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_pickling.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_pickling.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_pickling.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_pickling.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_pytypes.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_pytypes.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_pytypes.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_pytypes.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_sequences_and_iterators.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_sequences_and_iterators.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_sequences_and_iterators.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_sequences_and_iterators.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_smart_ptr.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_smart_ptr.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_smart_ptr.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_smart_ptr.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_stl.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_stl.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_stl.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_stl.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_stl_binders.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_stl_binders.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_stl_binders.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_stl_binders.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_tagbased_polymorphic.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_tagbased_polymorphic.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_tagbased_polymorphic.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_tagbased_polymorphic.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_union.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_union.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_virtual_functions.cpp` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_virtual_functions.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tests/test_virtual_functions.py` & `dionysus-2.0.9/bindings/python/pybind11/tests/test_virtual_functions.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tools/FindCatch.cmake` & `dionysus-2.0.9/bindings/python/pybind11/tools/FindCatch.cmake`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tools/FindEigen3.cmake` & `dionysus-2.0.9/bindings/python/pybind11/tools/FindEigen3.cmake`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tools/FindPythonLibsNew.cmake` & `dionysus-2.0.9/bindings/python/pybind11/tools/FindPythonLibsNew.cmake`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tools/check-style.sh` & `dionysus-2.0.9/bindings/python/pybind11/tools/check-style.sh`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tools/cmake_uninstall.cmake.in` & `dionysus-2.0.9/bindings/python/pybind11/tools/cmake_uninstall.cmake.in`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tools/libsize.py` & `dionysus-2.0.9/bindings/python/pybind11/tools/libsize.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tools/pybind11Common.cmake` & `dionysus-2.0.9/bindings/python/pybind11/tools/pybind11Common.cmake`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tools/pybind11Config.cmake.in` & `dionysus-2.0.9/bindings/python/pybind11/tools/pybind11Config.cmake.in`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tools/pybind11NewTools.cmake` & `dionysus-2.0.9/bindings/python/pybind11/tools/pybind11NewTools.cmake`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tools/pybind11Tools.cmake` & `dionysus-2.0.9/bindings/python/pybind11/tools/pybind11Tools.cmake`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tools/setup_global.py.in` & `dionysus-2.0.9/bindings/python/pybind11/tools/setup_global.py.in`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/pybind11/tools/setup_main.py.in` & `dionysus-2.0.9/bindings/python/pybind11/tools/setup_main.py.in`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/rips.cpp` & `dionysus-2.0.9/bindings/python/rips.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/simplex.cpp` & `dionysus-2.0.9/bindings/python/simplex.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/wasserstein-distance.cpp` & `dionysus-2.0.9/bindings/python/wasserstein-distance.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/bindings/python/zigzag-persistence.cpp` & `dionysus-2.0.9/bindings/python/zigzag-persistence.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/dionysus/__init__.py` & `dionysus-2.0.9/dionysus/__init__.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/dionysus/__pycache__/__init__.cpython-37.pyc` & `dionysus-2.0.9/dionysus/__pycache__/__init__.cpython-37.pyc`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/dionysus/__pycache__/plot.cpython-37.pyc` & `dionysus-2.0.9/dionysus/__pycache__/plot.cpython-37.pyc`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/dionysus/_dionysus.cpython-37m-darwin.so` & `dionysus-2.0.9/dionysus/_dionysus.cpython-37m-darwin.so`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/dionysus/plot.py` & `dionysus-2.0.9/bindings/python/dionysus/plot.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,9 +1,10 @@
 def plot_diagram(dgm, show=False, labels=False, ax=None,
-                 line_style=None, pt_style=None):
+                 line_style=None, pt_style=None,
+                 limits = None):
     """
     Plot the persistence diagram.
 
     Arguments:
         dgm (Diagram): See for example `init_diagrams`.
 
     Keyword Arguments:
@@ -20,19 +21,22 @@
     pt_kwargs = {}
     if pt_style is not None:
         pt_kwargs.update(pt_style)
     if line_style is not None:
         line_kwargs.update(line_style)
 
 
-    inf = float('inf')
-    min_birth = min(p.birth for p in dgm if p.birth != inf)
-    max_birth = max(p.birth for p in dgm if p.birth != inf)
-    min_death = min(p.death for p in dgm if p.death != inf)
-    max_death = max(p.death for p in dgm if p.death != inf)
+    if not limits:
+        inf = float('inf')
+        min_birth = min((p.birth for p in dgm if p.birth != inf), default=0)
+        max_birth = max((p.birth for p in dgm if p.birth != inf), default=1)
+        min_death = min((p.death for p in dgm if p.death != inf), default=min_birth)
+        max_death = max((p.death for p in dgm if p.death != inf), default=max_birth)
+    else:
+        min_birth, max_birth, min_death, max_death = limits
 
     if ax is None:
         ax = plt.axes()
     ax.set_aspect('equal', 'datalim')
 
     min_diag = min(min_birth, min_death)
     max_diag = max(max_birth, max_death)
```

### Comparing `dionysus-2.0.8/dionysus.egg-info/PKG-INFO` & `dionysus-2.0.9/dionysus.egg-info/PKG-INFO`

 * *Files 26% similar despite different names*

```diff
@@ -1,93 +1,15 @@
-Metadata-Version: 1.1
+Metadata-Version: 2.1
 Name: dionysus
-Version: 2.0.8
+Version: 2.0.9
 Summary: Library for computing persistent homology
 Home-page: http://mrzv.org/software/dionysus2
 Author: Dmitriy Morozov
 Author-email: dmitriy@mrzv.org
 License: BSD
-Description: Dionysus 2
-        ==========
-        
-        Dionysus is a computational topology package focused on
-        persistent homology. It is written in C++, with Python bindings.
-        The second version (`previous version <http://mrzv.org/software/dionysus/>`_)
-        is re-written from scratch, which helps it accomplish a few goals:
-        
-          * `Modified BSD license <https://github.com/mrzv/dionysus/blob/master/LICENSE.txt>`_ (because GPL causes too many problems in academic software).
-          * No dependency on Boost.Python; Dionysus 2 uses (and includes) `PyBind11 <https://github.com/pybind/pybind11>`_ instead, which greatly simplifies installation.
-          * Cleaner, more consistent internal design (for example, all algorithms support arbitrary fields).
-          * Some new algorithms, e.g., `omni-field persistence <http://mrzv.org/software/dionysus2/tutorial/omni-field.html#omni-field>`_ and Wasserstein and bottleneck `distance computation <http://mrzv.org/software/dionysus2/tutorial/basics.html#diagram-distances>`_ from `Hera <https://bitbucket.org/grey_narn/hera>`_.
-          * A few `plotting <http://mrzv.org/software/dionysus2/tutorial/plotting.html#plotting>`_ routines, based on `Matplotlib <https://matplotlib.org/>`_.
-          * Better integration with `NumPy <http://www.numpy.org/>`_.
-        
-        Features that haven't (yet) made it over from `Dionysus 1 <http://mrzv.org/software/dionysus>`_ include vineyards.
-        Alpha shape filtrations are available via `DioDe <https://github.com/mrzv/diode>`_.
-        
-        **Dependencies:**
-          * `Boost <http://www.boost.org/>`_, although Dionysus 2 doesn't link any of its libraries, so it's considerably easier to build the project.
-          * (Optional) `SciPy <https://www.scipy.org/>`_ for the LSQR routine used in `circular coordinates <http://mrzv.org/software/dionysus2/tutorial/cohomology.html#circular>`_.
-          * (Optional) `Maplotlib <https://matplotlib.org/>`_ for plotting.
-        
-        **Requirements:**
-          * Boost needs to be at least version 1.55.
-          * If you are using GCC, the oldest supported version is 5.4.
-        
-        **Contact:**
-          * please use the `dionysus mailing list <https://groups.io/g/dionysus/>`_
-            for all questions and discussion related to the library;
-          * GitHub's `issue tracker <https://github.com/mrzv/dionysus/issues>`_
-            is a central location for bug reports and feature requests.
-        
-        Get, Build, Install
-        -------------------
-        
-        The simplest way to install Dionysus, as a Python package, is from `PyPI <https://pypi.org/project/dionysus/>`_:
-        
-        .. parsed-literal::
-        
-            pip install --verbose dionysus
-        
-        Pass ``--upgrade`` to ``pip``, if you have already installed some version of Dionysus.
-        
-        Alternatively, you can install it directly from the development repository (this gives you the latest version):
-        
-        .. parsed-literal::
-        
-            pip install --verbose `git+https://github.com/mrzv/dionysus.git <https://github.com/mrzv/dionysus.git>`_
-        
-        Alternatively, you can clone and build everything by hand.
-        To get Dionysus 2, either clone its `repository <https://github.com/mrzv/dionysus>`_:
-        
-        .. parsed-literal::
-        
-            git clone `<https://github.com/mrzv/dionysus.git>`_
-        
-        or download it as a `Zip archive <https://github.com/mrzv/dionysus/archive/master.zip>`_.
-        
-        To build the project::
-        
-            mkdir build
-            cd build
-            cmake ..
-            make
-        
-        To use the Python bindings, either launch Python from ``.../build/bindings/python`` or add this directory to your ``PYTHONPATH`` variable, by adding::
-        
-            export PYTHONPATH=.../build/bindings/python:$PYTHONPATH
-        
-        to your ``~/.bashrc`` or ``~/.zshrc``.
-        
-        Documentation
-        -------------
-        
-        Documentation for Dionysus can be found `here <http://mrzv.org/software/dionysus2/>`_.
-        
-Platform: UNKNOWN
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Intended Audience :: Developers
 Classifier: Intended Audience :: Education
 Classifier: Intended Audience :: Science/Research
 Classifier: Topic :: Software Development :: Libraries :: Python Modules
 Classifier: Topic :: Utilities
 Classifier: Programming Language :: C++
@@ -95,7 +17,86 @@
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.2
 Classifier: Programming Language :: Python :: 3.3
 Classifier: Programming Language :: Python :: 3.4
 Classifier: Programming Language :: Python :: 3.5
 Classifier: Programming Language :: Python :: 3.6
 Classifier: License :: OSI Approved :: BSD License
+License-File: LICENSE.txt
+License-File: NOTICES.txt
+
+Dionysus 2
+==========
+
+Dionysus is a computational topology package focused on
+persistent homology. It is written in C++, with Python bindings.
+The second version (`previous version <http://mrzv.org/software/dionysus/>`_)
+is re-written from scratch, which helps it accomplish a few goals:
+
+  * `Modified BSD license <https://github.com/mrzv/dionysus/blob/master/LICENSE.txt>`_ (because GPL causes too many problems in academic software).
+  * No dependency on Boost.Python; Dionysus 2 uses (and includes) `PyBind11 <https://github.com/pybind/pybind11>`_ instead, which greatly simplifies installation.
+  * Cleaner, more consistent internal design (for example, all algorithms support arbitrary fields).
+  * Some new algorithms, e.g., `omni-field persistence <http://mrzv.org/software/dionysus2/tutorial/omni-field.html#omni-field>`_ and Wasserstein and bottleneck `distance computation <http://mrzv.org/software/dionysus2/tutorial/basics.html#diagram-distances>`_ from `Hera <https://bitbucket.org/grey_narn/hera>`_.
+  * A few `plotting <http://mrzv.org/software/dionysus2/tutorial/plotting.html#plotting>`_ routines, based on `Matplotlib <https://matplotlib.org/>`_.
+  * Better integration with `NumPy <http://www.numpy.org/>`_.
+
+Features that haven't (yet) made it over from `Dionysus 1 <http://mrzv.org/software/dionysus>`_ include vineyards.
+Alpha shape filtrations are available via `DioDe <https://github.com/mrzv/diode>`_.
+
+**Dependencies:**
+  * `Boost <http://www.boost.org/>`_, although Dionysus 2 doesn't link any of its libraries, so it's considerably easier to build the project.
+  * (Optional) `SciPy <https://www.scipy.org/>`_ for the LSQR routine used in `circular coordinates <http://mrzv.org/software/dionysus2/tutorial/cohomology.html#circular>`_.
+  * (Optional) `Matplotlib <https://matplotlib.org/>`_ for plotting.
+
+**Requirements:**
+  * Boost needs to be at least version 1.55.
+  * If you are using GCC, the oldest supported version is 5.4.
+
+**Contact:**
+  * please use the `dionysus mailing list <https://groups.io/g/dionysus/>`_
+    for all questions and discussion related to the library;
+  * GitHub's `issue tracker <https://github.com/mrzv/dionysus/issues>`_
+    is a central location for bug reports and feature requests.
+
+Get, Build, Install
+-------------------
+
+The simplest way to install Dionysus, as a Python package, is from `PyPI <https://pypi.org/project/dionysus/>`_:
+
+.. parsed-literal::
+
+    pip install --verbose dionysus
+
+Pass ``--upgrade`` to ``pip``, if you have already installed some version of Dionysus.
+
+Alternatively, you can install it directly from the development repository (this gives you the latest version):
+
+.. parsed-literal::
+
+    pip install --verbose `git+https://github.com/mrzv/dionysus.git <https://github.com/mrzv/dionysus.git>`_
+
+Alternatively, you can clone and build everything by hand.
+To get Dionysus 2, either clone its `repository <https://github.com/mrzv/dionysus>`_:
+
+.. parsed-literal::
+
+    git clone `<https://github.com/mrzv/dionysus.git>`_
+
+or download it as a `Zip archive <https://github.com/mrzv/dionysus/archive/master.zip>`_.
+
+To build the project::
+
+    mkdir build
+    cd build
+    cmake ..
+    make
+
+To use the Python bindings, either launch Python from ``.../build/bindings/python`` or add this directory to your ``PYTHONPATH`` variable, by adding::
+
+    export PYTHONPATH=.../build/bindings/python:$PYTHONPATH
+
+to your ``~/.bashrc`` or ``~/.zshrc``.
+
+Documentation
+-------------
+
+Documentation for Dionysus can be found `here <http://mrzv.org/software/dionysus2/>`_.
```

### Comparing `dionysus-2.0.8/doc/API.rst` & `dionysus-2.0.9/doc/API.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/doc/Makefile` & `dionysus-2.0.9/doc/Makefile`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/doc/conf.py` & `dionysus-2.0.9/doc/conf.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/doc/index.rst` & `dionysus-2.0.9/doc/index.rst`

 * *Files 1% similar despite different names*

```diff
@@ -27,15 +27,15 @@
 
 Features that haven't (yet) made it over from `Dionysus 1 <http://mrzv.org/software/dionysus>`_ include vineyards.
 Alpha shape filtrations are available via `DioDe <https://github.com/mrzv/diode>`_.
 
 **Dependencies:**
   * `Boost <http://www.boost.org/>`_, although Dionysus 2 doesn't link any of its libraries, so it's considerably easier to build the project.
   * (Optional) `SciPy <https://www.scipy.org/>`_ for the LSQR routine used in :ref:`circular`.
-  * (Optional) `Maplotlib <https://matplotlib.org/>`_ for :ref:`plotting`.
+  * (Optional) `Matplotlib <https://matplotlib.org/>`_ for :ref:`plotting`.
 
 **Requirements:**
   * Boost needs to be at least version 1.55.
   * If you are using GCC, the oldest supported version is 5.4.
 
 **Contact:**
   * please use the `dionysus mailing list <https://groups.io/g/dionysus/>`_
```

### Comparing `dionysus-2.0.8/doc/tutorial/basics.rst` & `dionysus-2.0.9/doc/tutorial/basics.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/doc/tutorial/cohomology.rst` & `dionysus-2.0.9/doc/tutorial/cohomology.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/doc/tutorial/diagnostics.rst` & `dionysus-2.0.9/doc/tutorial/diagnostics.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/doc/tutorial/figures/alpha-shape.png` & `dionysus-2.0.9/doc/tutorial/figures/alpha-shape.png`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/doc/tutorial/figures/barcode.png` & `dionysus-2.0.9/doc/tutorial/figures/barcode.png`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/doc/tutorial/figures/filtration.png` & `dionysus-2.0.9/doc/tutorial/figures/filtration.png`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/doc/tutorial/figures/lower-star.png` & `dionysus-2.0.9/doc/tutorial/figures/lower-star.png`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/doc/tutorial/figures/vietoris-rips.png` & `dionysus-2.0.9/doc/tutorial/figures/vietoris-rips.png`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/doc/tutorial/lower-star.rst` & `dionysus-2.0.9/doc/tutorial/lower-star.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/doc/tutorial/omni-field.rst` & `dionysus-2.0.9/doc/tutorial/omni-field.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/doc/tutorial/plotting.rst` & `dionysus-2.0.9/doc/tutorial/plotting.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/doc/tutorial/rips.rst` & `dionysus-2.0.9/doc/tutorial/rips.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/doc/tutorial/zigzags.rst` & `dionysus-2.0.9/doc/tutorial/zigzags.rst`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/examples/filtration/filtration-persistence.cpp` & `dionysus-2.0.9/examples/filtration/filtration-persistence.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/examples/filtration/zigzag-filtration-persistence.cpp` & `dionysus-2.0.9/examples/filtration/zigzag-filtration-persistence.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/examples/include/cnpy.h` & `dionysus-2.0.9/examples/include/cnpy.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/examples/include/common.h` & `dionysus-2.0.9/examples/include/common.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/examples/include/format/format.cc` & `dionysus-2.0.9/examples/include/format/format.cc`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/examples/include/format/format.h` & `dionysus-2.0.9/examples/include/format/format.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/examples/include/grid/box.h` & `dionysus-2.0.9/examples/include/grid/box.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/examples/include/grid/box.hpp` & `dionysus-2.0.9/examples/include/grid/box.hpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/examples/include/grid/grid.h` & `dionysus-2.0.9/examples/include/grid/grid.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/examples/include/grid/point.h` & `dionysus-2.0.9/examples/include/grid/point.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/examples/include/grid/vertices.h` & `dionysus-2.0.9/examples/include/grid/vertices.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/examples/include/opts/opts.h` & `dionysus-2.0.9/examples/include/opts/opts.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/examples/lzz/extended-persistence.cpp` & `dionysus-2.0.9/examples/lzz/extended-persistence.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/examples/lzz/grid-topology.h` & `dionysus-2.0.9/examples/lzz/grid-topology.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/examples/lzz/relative-lzz.cpp` & `dionysus-2.0.9/examples/lzz/relative-lzz.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/examples/lzz/relative-lzz.h` & `dionysus-2.0.9/examples/lzz/relative-lzz.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/examples/lzz/relative-lzz.hpp` & `dionysus-2.0.9/examples/lzz/relative-lzz.hpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/examples/lzz/relative-zz-filtration.cpp` & `dionysus-2.0.9/examples/lzz/relative-zz-filtration.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/examples/omni-field/omni-field-persistence.cpp` & `dionysus-2.0.9/examples/omni-field/omni-field-persistence.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/examples/rips/rips-basic.cpp` & `dionysus-2.0.9/examples/rips/rips-basic.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/examples/rips/rips-pairwise.cpp` & `dionysus-2.0.9/examples/rips/rips-pairwise.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/examples/rips/rips-zigzag.cpp` & `dionysus-2.0.9/examples/rips/rips-zigzag.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/examples/src/cnpy.cpp` & `dionysus-2.0.9/examples/src/cnpy.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/bottleneck/CMakeLists.txt` & `dionysus-2.0.9/ext/hera/bottleneck/CMakeLists.txt`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/bottleneck/README` & `dionysus-2.0.9/ext/hera/bottleneck/README`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/bottleneck/example/CMakeLists.txt` & `dionysus-2.0.9/ext/hera/bottleneck/example/CMakeLists.txt`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/bottleneck/example/bottleneck_dist.cpp` & `dionysus-2.0.9/ext/hera/bottleneck/example/bottleneck_dist.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/bottleneck/include/basic_defs_bt.h` & `dionysus-2.0.9/ext/hera/bottleneck/include/basic_defs_bt.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/bottleneck/include/bottleneck.h` & `dionysus-2.0.9/ext/hera/bottleneck/include/bottleneck.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/bottleneck/include/bottleneck_detail.h` & `dionysus-2.0.9/ext/hera/bottleneck/include/bottleneck_detail.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/bottleneck/include/bottleneck_detail.hpp` & `dionysus-2.0.9/ext/hera/bottleneck/include/bottleneck_detail.hpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/bottleneck/include/bound_match.h` & `dionysus-2.0.9/ext/hera/bottleneck/include/bound_match.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/bottleneck/include/bound_match.hpp` & `dionysus-2.0.9/ext/hera/bottleneck/include/bound_match.hpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/bottleneck/include/catch/catch.hpp` & `dionysus-2.0.9/ext/hera/bottleneck/include/catch/catch.hpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/bottleneck/include/def_debug_bt.h` & `dionysus-2.0.9/ext/hera/bottleneck/include/def_debug_bt.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/bottleneck/include/diagram_reader.h` & `dionysus-2.0.9/ext/hera/bottleneck/include/diagram_reader.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/bottleneck/include/diagram_traits.h` & `dionysus-2.0.9/ext/hera/bottleneck/include/diagram_traits.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/bottleneck/include/dnn/geometry/euclidean-fixed.h` & `dionysus-2.0.9/ext/hera/bottleneck/include/dnn/geometry/euclidean-fixed.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/bottleneck/include/dnn/local/kd-tree.h` & `dionysus-2.0.9/ext/hera/bottleneck/include/dnn/local/kd-tree.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/bottleneck/include/dnn/local/kd-tree.hpp` & `dionysus-2.0.9/ext/hera/bottleneck/include/dnn/local/kd-tree.hpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/bottleneck/include/dnn/local/search-functors.h` & `dionysus-2.0.9/ext/hera/bottleneck/include/dnn/local/search-functors.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/bottleneck/include/dnn/parallel/tbb.h` & `dionysus-2.0.9/ext/hera/bottleneck/include/dnn/parallel/tbb.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/bottleneck/include/dnn/parallel/utils.h` & `dionysus-2.0.9/ext/hera/bottleneck/include/dnn/parallel/utils.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/bottleneck/include/dnn/utils.h` & `dionysus-2.0.9/ext/hera/bottleneck/include/dnn/utils.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/bottleneck/include/neighb_oracle.h` & `dionysus-2.0.9/ext/hera/bottleneck/include/neighb_oracle.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/license.txt` & `dionysus-2.0.9/ext/hera/license.txt`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/CMakeLists.txt` & `dionysus-2.0.9/ext/hera/wasserstein/CMakeLists.txt`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/README` & `dionysus-2.0.9/ext/hera/wasserstein/README`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/example/wasserstein_dist.cpp` & `dionysus-2.0.9/ext/hera/wasserstein/example/wasserstein_dist.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/example/wasserstein_dist_dipha.cpp` & `dionysus-2.0.9/ext/hera/wasserstein/example/wasserstein_dist_dipha.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/example/wasserstein_dist_point_cloud.cpp` & `dionysus-2.0.9/ext/hera/wasserstein/example/wasserstein_dist_point_cloud.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/auction_oracle.h` & `dionysus-2.0.9/ext/hera/wasserstein/include/auction_oracle.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/auction_oracle_base.h` & `dionysus-2.0.9/ext/hera/wasserstein/include/auction_oracle_base.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/auction_oracle_base.hpp` & `dionysus-2.0.9/ext/hera/wasserstein/include/auction_oracle_base.hpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/auction_oracle_kdtree_pure_geom.h` & `dionysus-2.0.9/ext/hera/wasserstein/include/auction_oracle_kdtree_pure_geom.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/auction_oracle_kdtree_pure_geom.hpp` & `dionysus-2.0.9/ext/hera/wasserstein/include/auction_oracle_kdtree_pure_geom.hpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/auction_oracle_kdtree_restricted.h` & `dionysus-2.0.9/ext/hera/wasserstein/include/auction_oracle_kdtree_restricted.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/auction_oracle_kdtree_restricted.hpp` & `dionysus-2.0.9/ext/hera/wasserstein/include/auction_oracle_kdtree_restricted.hpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/auction_oracle_kdtree_single_diag.h` & `dionysus-2.0.9/ext/hera/wasserstein/include/auction_oracle_kdtree_single_diag.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/auction_oracle_kdtree_single_diag.hpp` & `dionysus-2.0.9/ext/hera/wasserstein/include/auction_oracle_kdtree_single_diag.hpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/auction_oracle_lazy_heap.h` & `dionysus-2.0.9/ext/hera/wasserstein/include/auction_oracle_lazy_heap.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/auction_oracle_lazy_heap.hpp` & `dionysus-2.0.9/ext/hera/wasserstein/include/auction_oracle_lazy_heap.hpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/auction_oracle_stupid_sparse_restricted.h` & `dionysus-2.0.9/ext/hera/wasserstein/include/auction_oracle_stupid_sparse_restricted.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/auction_oracle_stupid_sparse_restricted.hpp` & `dionysus-2.0.9/ext/hera/wasserstein/include/auction_oracle_stupid_sparse_restricted.hpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/auction_runner_fr.h` & `dionysus-2.0.9/ext/hera/wasserstein/include/auction_runner_fr.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/auction_runner_fr.hpp` & `dionysus-2.0.9/ext/hera/wasserstein/include/auction_runner_fr.hpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/auction_runner_gs.h` & `dionysus-2.0.9/ext/hera/wasserstein/include/auction_runner_gs.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/auction_runner_gs.hpp` & `dionysus-2.0.9/ext/hera/wasserstein/include/auction_runner_gs.hpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/auction_runner_gs_single_diag.h` & `dionysus-2.0.9/ext/hera/wasserstein/include/auction_runner_gs_single_diag.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/auction_runner_gs_single_diag.hpp` & `dionysus-2.0.9/ext/hera/wasserstein/include/auction_runner_gs_single_diag.hpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/auction_runner_jac.h` & `dionysus-2.0.9/ext/hera/wasserstein/include/auction_runner_jac.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/auction_runner_jac.hpp` & `dionysus-2.0.9/ext/hera/wasserstein/include/auction_runner_jac.hpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/basic_defs_ws.h` & `dionysus-2.0.9/ext/hera/wasserstein/include/basic_defs_ws.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/basic_defs_ws.hpp` & `dionysus-2.0.9/ext/hera/wasserstein/include/basic_defs_ws.hpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/catch/catch.hpp` & `dionysus-2.0.9/ext/hera/wasserstein/include/catch/catch.hpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/def_debug_ws.h` & `dionysus-2.0.9/ext/hera/wasserstein/include/def_debug_ws.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/diagonal_heap.h` & `dionysus-2.0.9/ext/hera/wasserstein/include/diagonal_heap.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/diagram_reader.h` & `dionysus-2.0.9/ext/hera/wasserstein/include/diagram_reader.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/dnn/geometry/euclidean-dynamic.h` & `dionysus-2.0.9/ext/hera/wasserstein/include/dnn/geometry/euclidean-dynamic.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/dnn/geometry/euclidean-fixed.h` & `dionysus-2.0.9/ext/hera/wasserstein/include/dnn/geometry/euclidean-fixed.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/dnn/local/kd-tree.h` & `dionysus-2.0.9/ext/hera/wasserstein/include/dnn/local/kd-tree.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/dnn/local/kd-tree.hpp` & `dionysus-2.0.9/ext/hera/wasserstein/include/dnn/local/kd-tree.hpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/dnn/local/search-functors.h` & `dionysus-2.0.9/ext/hera/wasserstein/include/dnn/local/search-functors.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/dnn/parallel/tbb.h` & `dionysus-2.0.9/ext/hera/wasserstein/include/dnn/parallel/tbb.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/dnn/parallel/utils.h` & `dionysus-2.0.9/ext/hera/wasserstein/include/dnn/parallel/utils.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/dnn/utils.h` & `dionysus-2.0.9/ext/hera/wasserstein/include/dnn/utils.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/hera_infinity.h` & `dionysus-2.0.9/ext/hera/wasserstein/include/hera_infinity.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/opts/opts.h` & `dionysus-2.0.9/ext/hera/wasserstein/include/opts/opts.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/wasserstein.h` & `dionysus-2.0.9/ext/hera/wasserstein/include/wasserstein.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/ext/hera/wasserstein/include/wasserstein_pure_geom.hpp` & `dionysus-2.0.9/ext/hera/wasserstein/include/wasserstein_pure_geom.hpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/include/backward.hpp` & `dionysus-2.0.9/include/backward.hpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/include/dionysus/chain.h` & `dionysus-2.0.9/include/dionysus/chain.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/include/dionysus/chain.hpp` & `dionysus-2.0.9/include/dionysus/chain.hpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/include/dionysus/clearing-reduction.h` & `dionysus-2.0.9/include/dionysus/clearing-reduction.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/include/dionysus/clearing-reduction.hpp` & `dionysus-2.0.9/include/dionysus/clearing-reduction.hpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/include/dionysus/cohomology-persistence.h` & `dionysus-2.0.9/include/dionysus/cohomology-persistence.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/include/dionysus/cohomology-persistence.hpp` & `dionysus-2.0.9/include/dionysus/cohomology-persistence.hpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/include/dionysus/diagram.h` & `dionysus-2.0.9/include/dionysus/diagram.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/include/dionysus/distances.h` & `dionysus-2.0.9/include/dionysus/distances.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/include/dionysus/distances.hpp` & `dionysus-2.0.9/include/dionysus/distances.hpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/include/dionysus/dlog/progress.h` & `dionysus-2.0.9/include/dionysus/dlog/progress.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/include/dionysus/fields/q.h` & `dionysus-2.0.9/include/dionysus/fields/q.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/include/dionysus/fields/z2.h` & `dionysus-2.0.9/include/dionysus/fields/z2.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/include/dionysus/fields/zp.h` & `dionysus-2.0.9/include/dionysus/fields/zp.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/include/dionysus/filtration.h` & `dionysus-2.0.9/include/dionysus/filtration.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/include/dionysus/omni-field-persistence.h` & `dionysus-2.0.9/include/dionysus/omni-field-persistence.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/include/dionysus/omni-field-persistence.hpp` & `dionysus-2.0.9/include/dionysus/omni-field-persistence.hpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/include/dionysus/ordinary-persistence.h` & `dionysus-2.0.9/include/dionysus/ordinary-persistence.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/include/dionysus/pair-recorder.h` & `dionysus-2.0.9/include/dionysus/pair-recorder.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/include/dionysus/reduced-matrix.h` & `dionysus-2.0.9/include/dionysus/reduced-matrix.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/include/dionysus/reduced-matrix.hpp` & `dionysus-2.0.9/include/dionysus/reduced-matrix.hpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/include/dionysus/reduction.h` & `dionysus-2.0.9/include/dionysus/reduction.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/include/dionysus/relative-homology-zigzag.h` & `dionysus-2.0.9/include/dionysus/relative-homology-zigzag.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/include/dionysus/relative-homology-zigzag.hpp` & `dionysus-2.0.9/include/dionysus/relative-homology-zigzag.hpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/include/dionysus/rips.h` & `dionysus-2.0.9/include/dionysus/rips.h`

 * *Files 8% similar despite different names*

```diff
@@ -99,30 +99,30 @@
                                           bool                                      check_initial = true);
 
     protected:
         const Distances&    distances_;
 };
 
 template<class Distances_, class Simplex_>
-class Rips<Distances_, Simplex_>::Evaluator: public std::unary_function<const Simplex&, DistanceType>
+class Rips<Distances_, Simplex_>::Evaluator
 {
     public:
         typedef             Simplex_                                        Simplex;
 
                             Evaluator(const Distances& distances):
                                 distances_(distances)                       {}
 
         DistanceType        operator()(const Simplex& s) const;
 
     protected:
         const Distances&    distances_;
 };
 
 template<class Distances_, class Simplex_>
-class Rips<Distances_, Simplex_>::Comparison: public std::binary_function<const Simplex&, const Simplex&, bool>
+class Rips<Distances_, Simplex_>::Comparison
 {
     public:
         typedef             Simplex_                                        Simplex;
 
                             Comparison(const Distances& distances):
                                 eval_(distances)                            {}
```

### Comparing `dionysus-2.0.8/include/dionysus/rips.hpp` & `dionysus-2.0.9/include/dionysus/rips.hpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/include/dionysus/row-reduction.h` & `dionysus-2.0.9/include/dionysus/row-reduction.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/include/dionysus/row-reduction.hpp` & `dionysus-2.0.9/include/dionysus/row-reduction.hpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/include/dionysus/simplex.h` & `dionysus-2.0.9/include/dionysus/simplex.h`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,12 @@
 #ifndef DIONYSUS_SIMPLEX_H
 #define DIONYSUS_SIMPLEX_H
 
 #include <algorithm>
+#include <functional>
 
 //#include <boost/compressed_pair.hpp>
 #include <boost/range/iterator_range.hpp>
 #include <boost/functional/hash.hpp>
 #include <boost/iterator/filter_iterator.hpp>
 
 #include "chain.h"
```

### Comparing `dionysus-2.0.8/include/dionysus/sparse-row-matrix.h` & `dionysus-2.0.9/include/dionysus/sparse-row-matrix.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/include/dionysus/sparse-row-matrix.hpp` & `dionysus-2.0.9/include/dionysus/sparse-row-matrix.hpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/include/dionysus/standard-reduction.h` & `dionysus-2.0.9/include/dionysus/standard-reduction.h`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/include/dionysus/standard-reduction.hpp` & `dionysus-2.0.9/include/dionysus/standard-reduction.hpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/include/dionysus/zigzag-persistence.h` & `dionysus-2.0.9/include/dionysus/zigzag-persistence.h`

 * *Files 2% similar despite different names*

```diff
@@ -1,12 +1,13 @@
 #ifndef DIONYSUS_ZIGZAG_PERSISTENCE_H
 #define DIONYSUS_ZIGZAG_PERSISTENCE_H
 
 #include <tuple>
 #include <type_traits>
+#include <deque>
 
 #include <boost/range/adaptor/filtered.hpp>
 #include <boost/range/adaptor/map.hpp>
 
 #include "sparse-row-matrix.h"
 
 namespace dionysus
```

### Comparing `dionysus-2.0.8/include/dionysus/zigzag-persistence.hpp` & `dionysus-2.0.9/include/dionysus/zigzag-persistence.hpp`

 * *Files 0% similar despite different names*

```diff
@@ -1,7 +1,9 @@
+#include <map>
+
 template<class F, class I, class C>
 template<class ChainRange>
 typename dionysus::ZigzagPersistence<F,I,C>::Index
 dionysus::ZigzagPersistence<F,I,C>::
 add_impl(const ChainRange& chain_)
 {
     //std::cout << "add(" << cell_indices << ")" << std::endl;
```

### Comparing `dionysus-2.0.8/setup.py` & `dionysus-2.0.9/setup.py`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/src/backward.cpp` & `dionysus-2.0.9/src/backward.cpp`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/tests/data/issue39/dgm1.txt` & `dionysus-2.0.9/tests/data/issue39/dgm1.txt`

 * *Files identical despite different names*

### Comparing `dionysus-2.0.8/tests/data/issue39/dgm2.txt` & `dionysus-2.0.9/tests/data/issue39/dgm2.txt`

 * *Files identical despite different names*


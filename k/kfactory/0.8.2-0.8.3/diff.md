# Comparing `tmp/kfactory-0.8.2.tar.gz` & `tmp/kfactory-0.8.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "kfactory-0.8.2.tar", last modified: Fri Jun 16 19:57:19 2023, max compression
+gzip compressed data, was "kfactory-0.8.3.tar", last modified: Wed Jun 28 12:48:08 2023, max compression
```

## Comparing `kfactory-0.8.2.tar` & `kfactory-0.8.3.tar`

### file list

```diff
@@ -1,124 +1,124 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-16 19:57:19.391002 kfactory-0.8.2/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-16 19:57:19.371002 kfactory-0.8.2/.github/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-16 19:57:19.371002 kfactory-0.8.2/.github/ISSUE_TEMPLATE/
--rw-r--r--   0 runner    (1001) docker     (123)      834 2023-06-16 19:56:58.000000 kfactory-0.8.2/.github/ISSUE_TEMPLATE/bug_report.md
--rw-r--r--   0 runner    (1001) docker     (123)      595 2023-06-16 19:56:58.000000 kfactory-0.8.2/.github/ISSUE_TEMPLATE/feature_request.md
--rw-r--r--   0 runner    (1001) docker     (123)      232 2023-06-16 19:56:58.000000 kfactory-0.8.2/.github/dependabot.yml
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-16 19:57:19.371002 kfactory-0.8.2/.github/workflows/
--rw-r--r--   0 runner    (1001) docker     (123)     1031 2023-06-16 19:56:58.000000 kfactory-0.8.2/.github/workflows/pages.yml
--rw-r--r--   0 runner    (1001) docker     (123)      670 2023-06-16 19:56:58.000000 kfactory-0.8.2/.github/workflows/release.yml
--rw-r--r--   0 runner    (1001) docker     (123)     1902 2023-06-16 19:56:58.000000 kfactory-0.8.2/.github/workflows/test_code.yml
--rw-r--r--   0 runner    (1001) docker     (123)      329 2023-06-16 19:56:58.000000 kfactory-0.8.2/.gitignore
--rw-r--r--   0 runner    (1001) docker     (123)     5036 2023-06-16 19:56:58.000000 kfactory-0.8.2/.pre-commit-config.yaml
--rw-r--r--   0 runner    (1001) docker     (123)       35 2023-06-16 19:56:58.000000 kfactory-0.8.2/.sourcery.yaml
--rw-r--r--   0 runner    (1001) docker     (123)     3496 2023-06-16 19:56:58.000000 kfactory-0.8.2/CHANGELOG.md
--rw-r--r--   0 runner    (1001) docker     (123)     1072 2023-06-16 19:56:58.000000 kfactory-0.8.2/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     1486 2023-06-16 19:56:58.000000 kfactory-0.8.2/Makefile
--rw-r--r--   0 runner    (1001) docker     (123)     2617 2023-06-16 19:57:19.391002 kfactory-0.8.2/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2170 2023-06-16 19:56:58.000000 kfactory-0.8.2/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-16 19:57:19.371002 kfactory-0.8.2/changelog.d/
--rw-r--r--   0 runner    (1001) docker     (123)      309 2023-06-16 19:56:58.000000 kfactory-0.8.2/changelog.d/changelog_template.jinja
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-16 19:57:19.371002 kfactory-0.8.2/docs/
--rw-r--r--   0 runner    (1001) docker     (123)     2153 2023-06-16 19:56:58.000000 kfactory-0.8.2/docs/mkdocs.yml
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-16 19:57:19.371002 kfactory-0.8.2/docs/overrides/
--rw-r--r--   0 runner    (1001) docker     (123)      274 2023-06-16 19:56:58.000000 kfactory-0.8.2/docs/overrides/main.html
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-16 19:57:19.375002 kfactory-0.8.2/docs/source/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-16 19:57:19.375002 kfactory-0.8.2/docs/source/_static/
--rw-r--r--   0 runner    (1001) docker     (123)   138035 2023-06-16 19:56:58.000000 kfactory-0.8.2/docs/source/_static/complex.png
--rw-r--r--   0 runner    (1001) docker     (123)   985194 2023-06-16 19:56:58.000000 kfactory-0.8.2/docs/source/_static/klive.webm
--rw-r--r--   0 runner    (1001) docker     (123)   129785 2023-06-16 19:56:58.000000 kfactory-0.8.2/docs/source/_static/waveguide.png
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-16 19:56:58.000000 kfactory-0.8.2/docs/source/changelog.md
--rw-r--r--   0 runner    (1001) docker     (123)      968 2023-06-16 19:56:58.000000 kfactory-0.8.2/docs/source/complex_cell.py
--rw-r--r--   0 runner    (1001) docker     (123)     4547 2023-06-16 19:56:58.000000 kfactory-0.8.2/docs/source/config.md
--rw-r--r--   0 runner    (1001) docker     (123)     9803 2023-06-16 19:56:58.000000 kfactory-0.8.2/docs/source/gdsfactory.md
--rw-r--r--   0 runner    (1001) docker     (123)     2072 2023-06-16 19:56:58.000000 kfactory-0.8.2/docs/source/gen_ref_pages.py
--rw-r--r--   0 runner    (1001) docker     (123)       19 2023-06-16 19:56:58.000000 kfactory-0.8.2/docs/source/index.md
--rw-r--r--   0 runner    (1001) docker     (123)     4046 2023-06-16 19:56:58.000000 kfactory-0.8.2/docs/source/intro.md
--rw-r--r--   0 runner    (1001) docker     (123)      458 2023-06-16 19:56:58.000000 kfactory-0.8.2/docs/source/layers.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-16 19:57:19.375002 kfactory-0.8.2/docs/source/notebooks/
--rw-r--r--   0 runner    (1001) docker     (123)    11375 2023-06-16 19:56:58.000000 kfactory-0.8.2/docs/source/notebooks/00_geometry.py
--rw-r--r--   0 runner    (1001) docker     (123)    10554 2023-06-16 19:56:58.000000 kfactory-0.8.2/docs/source/notebooks/01_references.py
--rw-r--r--   0 runner    (1001) docker     (123)     3455 2023-06-16 19:56:58.000000 kfactory-0.8.2/docs/source/notebooks/02_DRC.py
--rw-r--r--   0 runner    (1001) docker     (123)     1509 2023-06-16 19:56:58.000000 kfactory-0.8.2/docs/source/notebooks/03_Enclosures.py
--rw-r--r--   0 runner    (1001) docker     (123)     2307 2023-06-16 19:56:58.000000 kfactory-0.8.2/docs/source/pre.md
--rw-r--r--   0 runner    (1001) docker     (123)     2420 2023-06-16 19:56:58.000000 kfactory-0.8.2/docs/source/star.py
--rw-r--r--   0 runner    (1001) docker     (123)      757 2023-06-16 19:56:58.000000 kfactory-0.8.2/docs/source/waveguide.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-16 19:57:19.367002 kfactory-0.8.2/gds/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-16 19:57:19.379002 kfactory-0.8.2/gds/gds_ref/
--rw-r--r--   0 runner    (1001) docker     (123)     1742 2023-06-16 19:56:58.000000 kfactory-0.8.2/gds/gds_ref/bend_circular.gds
--rw-r--r--   0 runner    (1001) docker     (123)     9006 2023-06-16 19:56:58.000000 kfactory-0.8.2/gds/gds_ref/bend_circular_W1_R10_LWG_EWGSTD_A180_AS1.gds
--rw-r--r--   0 runner    (1001) docker     (123)     4686 2023-06-16 19:56:58.000000 kfactory-0.8.2/gds/gds_ref/bend_circular_W1_R10_LWG_EWGSTD_A90_AS1.gds
--rw-r--r--   0 runner    (1001) docker     (123)     9006 2023-06-16 19:56:58.000000 kfactory-0.8.2/gds/gds_ref/bend_circular_W1_R10_LWG_EWGSTD_T180_TS1.gds
--rw-r--r--   0 runner    (1001) docker     (123)     4686 2023-06-16 19:56:58.000000 kfactory-0.8.2/gds/gds_ref/bend_circular_W1_R10_LWG_EWGSTD_T90_TS1.gds
--rw-r--r--   0 runner    (1001) docker     (123)     2142 2023-06-16 19:56:58.000000 kfactory-0.8.2/gds/gds_ref/bend_euler.gds
--rw-r--r--   0 runner    (1001) docker     (123)    11278 2023-06-16 19:56:58.000000 kfactory-0.8.2/gds/gds_ref/bend_euler_W1_R10_LWG_EWGSTD_A180_R150.gds
--rw-r--r--   0 runner    (1001) docker     (123)     5902 2023-06-16 19:56:58.000000 kfactory-0.8.2/gds/gds_ref/bend_euler_W1_R10_LWG_EWGSTD_A90_R150.gds
--rw-r--r--   0 runner    (1001) docker     (123)    11278 2023-06-16 19:56:58.000000 kfactory-0.8.2/gds/gds_ref/bend_euler_W1_R10_LWG_EWGSTD_T180_R150.gds
--rw-r--r--   0 runner    (1001) docker     (123)     5902 2023-06-16 19:56:58.000000 kfactory-0.8.2/gds/gds_ref/bend_euler_W1_R10_LWG_EWGSTD_T90_R150.gds
--rw-r--r--   0 runner    (1001) docker     (123)     1866 2023-06-16 19:56:58.000000 kfactory-0.8.2/gds/gds_ref/bend_s.gds
--rw-r--r--   0 runner    (1001) docker     (123)     1474 2023-06-16 19:56:58.000000 kfactory-0.8.2/gds/gds_ref/bend_s_euler.gds
--rw-r--r--   0 runner    (1001) docker     (123)      460 2023-06-16 19:56:58.000000 kfactory-0.8.2/gds/gds_ref/straight_W500_L1000_LWG_EWGSTD.gds
--rw-r--r--   0 runner    (1001) docker     (123)      300 2023-06-16 19:56:58.000000 kfactory-0.8.2/gds/gds_ref/taper.gds
--rw-r--r--   0 runner    (1001) docker     (123)      338 2023-06-16 19:56:58.000000 kfactory-0.8.2/gds/gds_ref/waveguide.gds
--rw-r--r--   0 runner    (1001) docker     (123)      462 2023-06-16 19:56:58.000000 kfactory-0.8.2/gds/gds_ref/waveguide_W500_L1000_LWG_EWGSTD.gds
--rw-r--r--   0 runner    (1001) docker     (123)     5507 2023-06-16 19:56:58.000000 kfactory-0.8.2/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-16 19:57:19.391002 kfactory-0.8.2/setup.cfg
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-16 19:57:19.367002 kfactory-0.8.2/src/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-16 19:57:19.383002 kfactory-0.8.2/src/kfactory/
--rw-r--r--   0 runner    (1001) docker     (123)      968 2023-06-16 19:56:58.000000 kfactory-0.8.2/src/kfactory/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-16 19:57:19.383002 kfactory-0.8.2/src/kfactory/cells/
--rw-r--r--   0 runner    (1001) docker     (123)       75 2023-06-16 19:56:58.000000 kfactory-0.8.2/src/kfactory/cells/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2344 2023-06-16 19:56:58.000000 kfactory-0.8.2/src/kfactory/cells/bezier.py
--rw-r--r--   0 runner    (1001) docker     (123)     1586 2023-06-16 19:56:58.000000 kfactory-0.8.2/src/kfactory/cells/circular.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-16 19:57:19.383002 kfactory-0.8.2/src/kfactory/cells/dbu/
--rw-r--r--   0 runner    (1001) docker     (123)       89 2023-06-16 19:56:58.000000 kfactory-0.8.2/src/kfactory/cells/dbu/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2643 2023-06-16 19:56:58.000000 kfactory-0.8.2/src/kfactory/cells/dbu/straight.py
--rw-r--r--   0 runner    (1001) docker     (123)     1784 2023-06-16 19:56:58.000000 kfactory-0.8.2/src/kfactory/cells/dbu/taper.py
--rw-r--r--   0 runner    (1001) docker     (123)     6857 2023-06-16 19:56:58.000000 kfactory-0.8.2/src/kfactory/cells/euler.py
--rw-r--r--   0 runner    (1001) docker     (123)     2111 2023-06-16 19:56:58.000000 kfactory-0.8.2/src/kfactory/cells/straight.py
--rw-r--r--   0 runner    (1001) docker     (123)     1159 2023-06-16 19:56:58.000000 kfactory-0.8.2/src/kfactory/cells/taper.py
--rw-r--r--   0 runner    (1001) docker     (123)     3463 2023-06-16 19:56:58.000000 kfactory-0.8.2/src/kfactory/conf.py
--rw-r--r--   0 runner    (1001) docker     (123)   113176 2023-06-16 19:56:58.000000 kfactory-0.8.2/src/kfactory/kcell.py
--rw-r--r--   0 runner    (1001) docker     (123)     8722 2023-06-16 19:56:58.000000 kfactory-0.8.2/src/kfactory/pdk.py
--rw-r--r--   0 runner    (1001) docker     (123)     4074 2023-06-16 19:56:58.000000 kfactory-0.8.2/src/kfactory/placer.py
--rw-r--r--   0 runner    (1001) docker     (123)     5392 2023-06-16 19:56:58.000000 kfactory-0.8.2/src/kfactory/port.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-16 19:56:58.000000 kfactory-0.8.2/src/kfactory/py.typed
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-16 19:57:19.383002 kfactory-0.8.2/src/kfactory/routing/
--rw-r--r--   0 runner    (1001) docker     (123)      164 2023-06-16 19:56:58.000000 kfactory-0.8.2/src/kfactory/routing/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     9940 2023-06-16 19:56:58.000000 kfactory-0.8.2/src/kfactory/routing/electrical.py
--rw-r--r--   0 runner    (1001) docker     (123)    12507 2023-06-16 19:56:58.000000 kfactory-0.8.2/src/kfactory/routing/manhattan.py
--rw-r--r--   0 runner    (1001) docker     (123)    20414 2023-06-16 19:56:58.000000 kfactory-0.8.2/src/kfactory/routing/optical.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-16 19:57:19.383002 kfactory-0.8.2/src/kfactory/technology/
--rw-r--r--   0 runner    (1001) docker     (123)      371 2023-06-16 19:56:58.000000 kfactory-0.8.2/src/kfactory/technology/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    11945 2023-06-16 19:56:58.000000 kfactory-0.8.2/src/kfactory/technology/layer_map.py
--rw-r--r--   0 runner    (1001) docker     (123)      549 2023-06-16 19:56:58.000000 kfactory-0.8.2/src/kfactory/typings.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-16 19:57:19.387002 kfactory-0.8.2/src/kfactory/utils/
--rw-r--r--   0 runner    (1001) docker     (123)     1017 2023-06-16 19:56:58.000000 kfactory-0.8.2/src/kfactory/utils/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    55806 2023-06-16 19:56:58.000000 kfactory-0.8.2/src/kfactory/utils/enclosure.py
--rw-r--r--   0 runner    (1001) docker     (123)     6781 2023-06-16 19:56:58.000000 kfactory-0.8.2/src/kfactory/utils/fill.py
--rw-r--r--   0 runner    (1001) docker     (123)     1111 2023-06-16 19:56:58.000000 kfactory-0.8.2/src/kfactory/utils/simplify.py
--rw-r--r--   0 runner    (1001) docker     (123)     9316 2023-06-16 19:56:58.000000 kfactory-0.8.2/src/kfactory/utils/violations.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-16 19:57:19.387002 kfactory-0.8.2/src/kfactory/widgets/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-16 19:56:58.000000 kfactory-0.8.2/src/kfactory/widgets/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    14853 2023-06-16 19:56:58.000000 kfactory-0.8.2/src/kfactory/widgets/interactive.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-16 19:57:19.383002 kfactory-0.8.2/src/kfactory.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     2617 2023-06-16 19:57:19.000000 kfactory-0.8.2/src/kfactory.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2930 2023-06-16 19:57:19.000000 kfactory-0.8.2/src/kfactory.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-16 19:57:19.000000 kfactory-0.8.2/src/kfactory.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)      599 2023-06-16 19:57:19.000000 kfactory-0.8.2/src/kfactory.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-16 19:57:19.000000 kfactory-0.8.2/src/kfactory.egg-info/top_level.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-16 19:57:19.391002 kfactory-0.8.2/tests/
--rw-r--r--   0 runner    (1001) docker     (123)     2850 2023-06-16 19:56:58.000000 kfactory-0.8.2/tests/conftest.py
--rw-r--r--   0 runner    (1001) docker     (123)      900 2023-06-16 19:56:58.000000 kfactory-0.8.2/tests/test_cell.py
--rw-r--r--   0 runner    (1001) docker     (123)     3737 2023-06-16 19:56:58.000000 kfactory-0.8.2/tests/test_cells.py
--rw-r--r--   0 runner    (1001) docker     (123)      952 2023-06-16 19:56:58.000000 kfactory-0.8.2/tests/test_cplxcells.py
--rw-r--r--   0 runner    (1001) docker     (123)     3954 2023-06-16 19:56:58.000000 kfactory-0.8.2/tests/test_enclosure.py
--rw-r--r--   0 runner    (1001) docker     (123)     1655 2023-06-16 19:56:58.000000 kfactory-0.8.2/tests/test_extrude.py
--rw-r--r--   0 runner    (1001) docker     (123)     1462 2023-06-16 19:56:58.000000 kfactory-0.8.2/tests/test_meta.py
--rw-r--r--   0 runner    (1001) docker     (123)     2566 2023-06-16 19:56:58.000000 kfactory-0.8.2/tests/test_netlist.py
--rw-r--r--   0 runner    (1001) docker     (123)      665 2023-06-16 19:56:58.000000 kfactory-0.8.2/tests/test_pdk.py
--rw-r--r--   0 runner    (1001) docker     (123)     3379 2023-06-16 19:56:58.000000 kfactory-0.8.2/tests/test_ports.py
--rw-r--r--   0 runner    (1001) docker     (123)     3121 2023-06-16 19:56:58.000000 kfactory-0.8.2/tests/test_rename.py
--rw-r--r--   0 runner    (1001) docker     (123)     2731 2023-06-16 19:56:58.000000 kfactory-0.8.2/tests/test_routing.py
--rw-r--r--   0 runner    (1001) docker     (123)      162 2023-06-16 19:56:58.000000 kfactory-0.8.2/tests/test_shapes.py
--rw-r--r--   0 runner    (1001) docker     (123)     4045 2023-06-16 19:56:58.000000 kfactory-0.8.2/tests/test_spiral.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:48:08.180720 kfactory-0.8.3/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:48:08.168721 kfactory-0.8.3/.github/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:48:08.168721 kfactory-0.8.3/.github/ISSUE_TEMPLATE/
+-rw-r--r--   0 runner    (1001) docker     (123)      834 2023-06-28 12:47:48.000000 kfactory-0.8.3/.github/ISSUE_TEMPLATE/bug_report.md
+-rw-r--r--   0 runner    (1001) docker     (123)      595 2023-06-28 12:47:48.000000 kfactory-0.8.3/.github/ISSUE_TEMPLATE/feature_request.md
+-rw-r--r--   0 runner    (1001) docker     (123)      232 2023-06-28 12:47:48.000000 kfactory-0.8.3/.github/dependabot.yml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:48:08.168721 kfactory-0.8.3/.github/workflows/
+-rw-r--r--   0 runner    (1001) docker     (123)     1031 2023-06-28 12:47:48.000000 kfactory-0.8.3/.github/workflows/pages.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      670 2023-06-28 12:47:48.000000 kfactory-0.8.3/.github/workflows/release.yml
+-rw-r--r--   0 runner    (1001) docker     (123)     1902 2023-06-28 12:47:48.000000 kfactory-0.8.3/.github/workflows/test_code.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      329 2023-06-28 12:47:48.000000 kfactory-0.8.3/.gitignore
+-rw-r--r--   0 runner    (1001) docker     (123)     5036 2023-06-28 12:47:48.000000 kfactory-0.8.3/.pre-commit-config.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)       35 2023-06-28 12:47:48.000000 kfactory-0.8.3/.sourcery.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)     3598 2023-06-28 12:47:48.000000 kfactory-0.8.3/CHANGELOG.md
+-rw-r--r--   0 runner    (1001) docker     (123)     1072 2023-06-28 12:47:48.000000 kfactory-0.8.3/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     1486 2023-06-28 12:47:48.000000 kfactory-0.8.3/Makefile
+-rw-r--r--   0 runner    (1001) docker     (123)     2617 2023-06-28 12:48:08.180720 kfactory-0.8.3/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2170 2023-06-28 12:47:48.000000 kfactory-0.8.3/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:48:08.168721 kfactory-0.8.3/changelog.d/
+-rw-r--r--   0 runner    (1001) docker     (123)      309 2023-06-28 12:47:48.000000 kfactory-0.8.3/changelog.d/changelog_template.jinja
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:48:08.168721 kfactory-0.8.3/docs/
+-rw-r--r--   0 runner    (1001) docker     (123)     2153 2023-06-28 12:47:48.000000 kfactory-0.8.3/docs/mkdocs.yml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:48:08.168721 kfactory-0.8.3/docs/overrides/
+-rw-r--r--   0 runner    (1001) docker     (123)      274 2023-06-28 12:47:48.000000 kfactory-0.8.3/docs/overrides/main.html
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:48:08.168721 kfactory-0.8.3/docs/source/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:48:08.172721 kfactory-0.8.3/docs/source/_static/
+-rw-r--r--   0 runner    (1001) docker     (123)   138035 2023-06-28 12:47:48.000000 kfactory-0.8.3/docs/source/_static/complex.png
+-rw-r--r--   0 runner    (1001) docker     (123)   985194 2023-06-28 12:47:48.000000 kfactory-0.8.3/docs/source/_static/klive.webm
+-rw-r--r--   0 runner    (1001) docker     (123)   129785 2023-06-28 12:47:48.000000 kfactory-0.8.3/docs/source/_static/waveguide.png
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 12:47:48.000000 kfactory-0.8.3/docs/source/changelog.md
+-rw-r--r--   0 runner    (1001) docker     (123)      968 2023-06-28 12:47:48.000000 kfactory-0.8.3/docs/source/complex_cell.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4547 2023-06-28 12:47:48.000000 kfactory-0.8.3/docs/source/config.md
+-rw-r--r--   0 runner    (1001) docker     (123)     9803 2023-06-28 12:47:48.000000 kfactory-0.8.3/docs/source/gdsfactory.md
+-rw-r--r--   0 runner    (1001) docker     (123)     2072 2023-06-28 12:47:48.000000 kfactory-0.8.3/docs/source/gen_ref_pages.py
+-rw-r--r--   0 runner    (1001) docker     (123)       19 2023-06-28 12:47:48.000000 kfactory-0.8.3/docs/source/index.md
+-rw-r--r--   0 runner    (1001) docker     (123)     4046 2023-06-28 12:47:48.000000 kfactory-0.8.3/docs/source/intro.md
+-rw-r--r--   0 runner    (1001) docker     (123)      458 2023-06-28 12:47:48.000000 kfactory-0.8.3/docs/source/layers.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:48:08.172721 kfactory-0.8.3/docs/source/notebooks/
+-rw-r--r--   0 runner    (1001) docker     (123)    11375 2023-06-28 12:47:48.000000 kfactory-0.8.3/docs/source/notebooks/00_geometry.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10554 2023-06-28 12:47:48.000000 kfactory-0.8.3/docs/source/notebooks/01_references.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3455 2023-06-28 12:47:48.000000 kfactory-0.8.3/docs/source/notebooks/02_DRC.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1509 2023-06-28 12:47:48.000000 kfactory-0.8.3/docs/source/notebooks/03_Enclosures.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2307 2023-06-28 12:47:48.000000 kfactory-0.8.3/docs/source/pre.md
+-rw-r--r--   0 runner    (1001) docker     (123)     2420 2023-06-28 12:47:48.000000 kfactory-0.8.3/docs/source/star.py
+-rw-r--r--   0 runner    (1001) docker     (123)      757 2023-06-28 12:47:48.000000 kfactory-0.8.3/docs/source/waveguide.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:48:08.164721 kfactory-0.8.3/gds/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:48:08.172721 kfactory-0.8.3/gds/gds_ref/
+-rw-r--r--   0 runner    (1001) docker     (123)     1742 2023-06-28 12:47:48.000000 kfactory-0.8.3/gds/gds_ref/bend_circular.gds
+-rw-r--r--   0 runner    (1001) docker     (123)     9006 2023-06-28 12:47:48.000000 kfactory-0.8.3/gds/gds_ref/bend_circular_W1_R10_LWG_EWGSTD_A180_AS1.gds
+-rw-r--r--   0 runner    (1001) docker     (123)     4686 2023-06-28 12:47:48.000000 kfactory-0.8.3/gds/gds_ref/bend_circular_W1_R10_LWG_EWGSTD_A90_AS1.gds
+-rw-r--r--   0 runner    (1001) docker     (123)     9006 2023-06-28 12:47:48.000000 kfactory-0.8.3/gds/gds_ref/bend_circular_W1_R10_LWG_EWGSTD_T180_TS1.gds
+-rw-r--r--   0 runner    (1001) docker     (123)     4686 2023-06-28 12:47:48.000000 kfactory-0.8.3/gds/gds_ref/bend_circular_W1_R10_LWG_EWGSTD_T90_TS1.gds
+-rw-r--r--   0 runner    (1001) docker     (123)     2142 2023-06-28 12:47:48.000000 kfactory-0.8.3/gds/gds_ref/bend_euler.gds
+-rw-r--r--   0 runner    (1001) docker     (123)    11278 2023-06-28 12:47:48.000000 kfactory-0.8.3/gds/gds_ref/bend_euler_W1_R10_LWG_EWGSTD_A180_R150.gds
+-rw-r--r--   0 runner    (1001) docker     (123)     5902 2023-06-28 12:47:48.000000 kfactory-0.8.3/gds/gds_ref/bend_euler_W1_R10_LWG_EWGSTD_A90_R150.gds
+-rw-r--r--   0 runner    (1001) docker     (123)    11278 2023-06-28 12:47:48.000000 kfactory-0.8.3/gds/gds_ref/bend_euler_W1_R10_LWG_EWGSTD_T180_R150.gds
+-rw-r--r--   0 runner    (1001) docker     (123)     5902 2023-06-28 12:47:48.000000 kfactory-0.8.3/gds/gds_ref/bend_euler_W1_R10_LWG_EWGSTD_T90_R150.gds
+-rw-r--r--   0 runner    (1001) docker     (123)     1866 2023-06-28 12:47:48.000000 kfactory-0.8.3/gds/gds_ref/bend_s.gds
+-rw-r--r--   0 runner    (1001) docker     (123)     1474 2023-06-28 12:47:48.000000 kfactory-0.8.3/gds/gds_ref/bend_s_euler.gds
+-rw-r--r--   0 runner    (1001) docker     (123)      460 2023-06-28 12:47:48.000000 kfactory-0.8.3/gds/gds_ref/straight_W500_L1000_LWG_EWGSTD.gds
+-rw-r--r--   0 runner    (1001) docker     (123)      300 2023-06-28 12:47:48.000000 kfactory-0.8.3/gds/gds_ref/taper.gds
+-rw-r--r--   0 runner    (1001) docker     (123)      338 2023-06-28 12:47:48.000000 kfactory-0.8.3/gds/gds_ref/waveguide.gds
+-rw-r--r--   0 runner    (1001) docker     (123)      462 2023-06-28 12:47:48.000000 kfactory-0.8.3/gds/gds_ref/waveguide_W500_L1000_LWG_EWGSTD.gds
+-rw-r--r--   0 runner    (1001) docker     (123)     5507 2023-06-28 12:47:48.000000 kfactory-0.8.3/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 12:48:08.180720 kfactory-0.8.3/setup.cfg
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:48:08.168721 kfactory-0.8.3/src/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:48:08.172721 kfactory-0.8.3/src/kfactory/
+-rw-r--r--   0 runner    (1001) docker     (123)      968 2023-06-28 12:47:48.000000 kfactory-0.8.3/src/kfactory/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:48:08.176720 kfactory-0.8.3/src/kfactory/cells/
+-rw-r--r--   0 runner    (1001) docker     (123)       75 2023-06-28 12:47:48.000000 kfactory-0.8.3/src/kfactory/cells/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2344 2023-06-28 12:47:48.000000 kfactory-0.8.3/src/kfactory/cells/bezier.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1586 2023-06-28 12:47:48.000000 kfactory-0.8.3/src/kfactory/cells/circular.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:48:08.176720 kfactory-0.8.3/src/kfactory/cells/dbu/
+-rw-r--r--   0 runner    (1001) docker     (123)       89 2023-06-28 12:47:48.000000 kfactory-0.8.3/src/kfactory/cells/dbu/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2643 2023-06-28 12:47:48.000000 kfactory-0.8.3/src/kfactory/cells/dbu/straight.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1784 2023-06-28 12:47:48.000000 kfactory-0.8.3/src/kfactory/cells/dbu/taper.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6857 2023-06-28 12:47:48.000000 kfactory-0.8.3/src/kfactory/cells/euler.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2111 2023-06-28 12:47:48.000000 kfactory-0.8.3/src/kfactory/cells/straight.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1159 2023-06-28 12:47:48.000000 kfactory-0.8.3/src/kfactory/cells/taper.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3463 2023-06-28 12:47:48.000000 kfactory-0.8.3/src/kfactory/conf.py
+-rw-r--r--   0 runner    (1001) docker     (123)   113234 2023-06-28 12:47:48.000000 kfactory-0.8.3/src/kfactory/kcell.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8722 2023-06-28 12:47:48.000000 kfactory-0.8.3/src/kfactory/pdk.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4074 2023-06-28 12:47:48.000000 kfactory-0.8.3/src/kfactory/placer.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5392 2023-06-28 12:47:48.000000 kfactory-0.8.3/src/kfactory/port.py
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:48.000000 kfactory-0.8.3/src/kfactory/py.typed
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:48:08.176720 kfactory-0.8.3/src/kfactory/routing/
+-rw-r--r--   0 runner    (1001) docker     (123)      164 2023-06-28 12:47:48.000000 kfactory-0.8.3/src/kfactory/routing/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9940 2023-06-28 12:47:48.000000 kfactory-0.8.3/src/kfactory/routing/electrical.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12507 2023-06-28 12:47:48.000000 kfactory-0.8.3/src/kfactory/routing/manhattan.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20414 2023-06-28 12:47:48.000000 kfactory-0.8.3/src/kfactory/routing/optical.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:48:08.176720 kfactory-0.8.3/src/kfactory/technology/
+-rw-r--r--   0 runner    (1001) docker     (123)      371 2023-06-28 12:47:48.000000 kfactory-0.8.3/src/kfactory/technology/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11945 2023-06-28 12:47:48.000000 kfactory-0.8.3/src/kfactory/technology/layer_map.py
+-rw-r--r--   0 runner    (1001) docker     (123)      549 2023-06-28 12:47:48.000000 kfactory-0.8.3/src/kfactory/typings.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:48:08.176720 kfactory-0.8.3/src/kfactory/utils/
+-rw-r--r--   0 runner    (1001) docker     (123)     1017 2023-06-28 12:47:48.000000 kfactory-0.8.3/src/kfactory/utils/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    55682 2023-06-28 12:47:48.000000 kfactory-0.8.3/src/kfactory/utils/enclosure.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6781 2023-06-28 12:47:48.000000 kfactory-0.8.3/src/kfactory/utils/fill.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1111 2023-06-28 12:47:48.000000 kfactory-0.8.3/src/kfactory/utils/simplify.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9316 2023-06-28 12:47:48.000000 kfactory-0.8.3/src/kfactory/utils/violations.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:48:08.176720 kfactory-0.8.3/src/kfactory/widgets/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:48.000000 kfactory-0.8.3/src/kfactory/widgets/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14853 2023-06-28 12:47:48.000000 kfactory-0.8.3/src/kfactory/widgets/interactive.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:48:08.176720 kfactory-0.8.3/src/kfactory.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     2617 2023-06-28 12:48:08.000000 kfactory-0.8.3/src/kfactory.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2930 2023-06-28 12:48:08.000000 kfactory-0.8.3/src/kfactory.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 12:48:08.000000 kfactory-0.8.3/src/kfactory.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      599 2023-06-28 12:48:08.000000 kfactory-0.8.3/src/kfactory.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-28 12:48:08.000000 kfactory-0.8.3/src/kfactory.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:48:08.176720 kfactory-0.8.3/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)     2850 2023-06-28 12:47:48.000000 kfactory-0.8.3/tests/conftest.py
+-rw-r--r--   0 runner    (1001) docker     (123)      900 2023-06-28 12:47:48.000000 kfactory-0.8.3/tests/test_cell.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3737 2023-06-28 12:47:48.000000 kfactory-0.8.3/tests/test_cells.py
+-rw-r--r--   0 runner    (1001) docker     (123)      952 2023-06-28 12:47:48.000000 kfactory-0.8.3/tests/test_cplxcells.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3954 2023-06-28 12:47:48.000000 kfactory-0.8.3/tests/test_enclosure.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1655 2023-06-28 12:47:48.000000 kfactory-0.8.3/tests/test_extrude.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1462 2023-06-28 12:47:48.000000 kfactory-0.8.3/tests/test_meta.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2566 2023-06-28 12:47:48.000000 kfactory-0.8.3/tests/test_netlist.py
+-rw-r--r--   0 runner    (1001) docker     (123)      665 2023-06-28 12:47:48.000000 kfactory-0.8.3/tests/test_pdk.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3379 2023-06-28 12:47:48.000000 kfactory-0.8.3/tests/test_ports.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3121 2023-06-28 12:47:48.000000 kfactory-0.8.3/tests/test_rename.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2731 2023-06-28 12:47:48.000000 kfactory-0.8.3/tests/test_routing.py
+-rw-r--r--   0 runner    (1001) docker     (123)      162 2023-06-28 12:47:48.000000 kfactory-0.8.3/tests/test_shapes.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4045 2023-06-28 12:47:48.000000 kfactory-0.8.3/tests/test_spiral.py
```

### Comparing `kfactory-0.8.2/.github/ISSUE_TEMPLATE/bug_report.md` & `kfactory-0.8.3/.github/ISSUE_TEMPLATE/bug_report.md`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/.github/ISSUE_TEMPLATE/feature_request.md` & `kfactory-0.8.3/.github/ISSUE_TEMPLATE/feature_request.md`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/.github/workflows/pages.yml` & `kfactory-0.8.3/.github/workflows/pages.yml`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/.github/workflows/release.yml` & `kfactory-0.8.3/.github/workflows/release.yml`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/.github/workflows/test_code.yml` & `kfactory-0.8.3/.github/workflows/test_code.yml`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/.pre-commit-config.yaml` & `kfactory-0.8.3/.pre-commit-config.yaml`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/CHANGELOG.md` & `kfactory-0.8.3/CHANGELOG.md`

 * *Files 2% similar despite different names*

```diff
@@ -4,14 +4,19 @@
 
 The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).
 
 This project uses [*towncrier*](https://towncrier.readthedocs.io/) and the changes for the upcoming release can be found in <https://github.com/gdsfactory/kfactory/tree/main/changelog.d/>.
 
 <!-- towncrier release notes start -->
 
+## [0.8.3](https://github.com/gdsfactory/kfactory/tree/0.8.3) - 2023-06-28
+
+No significant changes.
+
+
 ## [0.8.2](https://github.com/gdsfactory/kfactory/tree/0.8.2) - 2023-06-16
 
 
 ### Fixed
 
 - fix info settings
```

### Comparing `kfactory-0.8.2/LICENSE` & `kfactory-0.8.3/LICENSE`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/Makefile` & `kfactory-0.8.3/Makefile`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/PKG-INFO` & `kfactory-0.8.3/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,31 +1,31 @@
 Metadata-Version: 2.1
 Name: kfactory
-Version: 0.8.2
+Version: 0.8.3
 Summary: KLayout API implementation of gdsfactory
 Author-email: gdsfactory community <contact@gdsfactory.com>
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Operating System :: OS Independent
 Requires-Python: >=3.10
 Description-Content-Type: text/markdown
 Provides-Extra: git
 Provides-Extra: dev
 Provides-Extra: docs
 Provides-Extra: ci
 Provides-Extra: ipy
 License-File: LICENSE
 
-# KFactory 0.8.2
+# KFactory 0.8.3
 
 Kfactory is a [gdsfactory](https://github.com/gdsfactory/gdsfactory)-like tool. It is built with [KLayout](https://klayout.de) as a backend instead of gdstk, but aims to offer the similar featuers.
 
 | :exclamation:  KFactory is still experimental, expect API changes without notice (even though we try to keep it to a minimum!)   |
 |---------------------------------------------------------------------------------------------------------------------------------|
 
-It is suggest to pin the version of KFactory in `requirements.txt` or `pyproject.toml` with `kfactory==0.8.2` for example.
+It is suggest to pin the version of KFactory in `requirements.txt` or `pyproject.toml` with `kfactory==0.8.3` for example.
 
 Features similar to gdsfactory:
 
 - [x] Cells & decorator for caching & storing cells
 - [x] Simple routing (point to point and simpl bundle routes for electrical routes)
 - [x] Basic cells like euler/circular bends, taper, waveguide
 - [x] Path extrusion (no interface with CrossSections)
```

### Comparing `kfactory-0.8.2/README.md` & `kfactory-0.8.3/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
-# KFactory 0.8.2
+# KFactory 0.8.3
 
 Kfactory is a [gdsfactory](https://github.com/gdsfactory/gdsfactory)-like tool. It is built with [KLayout](https://klayout.de) as a backend instead of gdstk, but aims to offer the similar featuers.
 
 | :exclamation:  KFactory is still experimental, expect API changes without notice (even though we try to keep it to a minimum!)   |
 |---------------------------------------------------------------------------------------------------------------------------------|
 
-It is suggest to pin the version of KFactory in `requirements.txt` or `pyproject.toml` with `kfactory==0.8.2` for example.
+It is suggest to pin the version of KFactory in `requirements.txt` or `pyproject.toml` with `kfactory==0.8.3` for example.
 
 Features similar to gdsfactory:
 
 - [x] Cells & decorator for caching & storing cells
 - [x] Simple routing (point to point and simpl bundle routes for electrical routes)
 - [x] Basic cells like euler/circular bends, taper, waveguide
 - [x] Path extrusion (no interface with CrossSections)
```

### Comparing `kfactory-0.8.2/docs/mkdocs.yml` & `kfactory-0.8.3/docs/mkdocs.yml`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/docs/source/_static/complex.png` & `kfactory-0.8.3/docs/source/_static/complex.png`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/docs/source/_static/klive.webm` & `kfactory-0.8.3/docs/source/_static/klive.webm`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/docs/source/_static/waveguide.png` & `kfactory-0.8.3/docs/source/_static/waveguide.png`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/docs/source/complex_cell.py` & `kfactory-0.8.3/docs/source/complex_cell.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/docs/source/config.md` & `kfactory-0.8.3/docs/source/config.md`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/docs/source/gdsfactory.md` & `kfactory-0.8.3/docs/source/gdsfactory.md`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/docs/source/gen_ref_pages.py` & `kfactory-0.8.3/docs/source/gen_ref_pages.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/docs/source/intro.md` & `kfactory-0.8.3/docs/source/intro.md`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/docs/source/notebooks/00_geometry.py` & `kfactory-0.8.3/docs/source/notebooks/00_geometry.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/docs/source/notebooks/01_references.py` & `kfactory-0.8.3/docs/source/notebooks/01_references.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/docs/source/notebooks/02_DRC.py` & `kfactory-0.8.3/docs/source/notebooks/02_DRC.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/docs/source/notebooks/03_Enclosures.py` & `kfactory-0.8.3/docs/source/notebooks/03_Enclosures.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/docs/source/pre.md` & `kfactory-0.8.3/docs/source/pre.md`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/docs/source/star.py` & `kfactory-0.8.3/docs/source/star.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/docs/source/waveguide.py` & `kfactory-0.8.3/docs/source/waveguide.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/gds/gds_ref/bend_circular.gds` & `kfactory-0.8.3/gds/gds_ref/bend_circular.gds`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/gds/gds_ref/bend_circular_W1_R10_LWG_EWGSTD_A180_AS1.gds` & `kfactory-0.8.3/gds/gds_ref/bend_circular_W1_R10_LWG_EWGSTD_A180_AS1.gds`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/gds/gds_ref/bend_circular_W1_R10_LWG_EWGSTD_A90_AS1.gds` & `kfactory-0.8.3/gds/gds_ref/bend_circular_W1_R10_LWG_EWGSTD_A90_AS1.gds`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/gds/gds_ref/bend_circular_W1_R10_LWG_EWGSTD_T180_TS1.gds` & `kfactory-0.8.3/gds/gds_ref/bend_circular_W1_R10_LWG_EWGSTD_T180_TS1.gds`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/gds/gds_ref/bend_circular_W1_R10_LWG_EWGSTD_T90_TS1.gds` & `kfactory-0.8.3/gds/gds_ref/bend_circular_W1_R10_LWG_EWGSTD_T90_TS1.gds`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/gds/gds_ref/bend_euler.gds` & `kfactory-0.8.3/gds/gds_ref/bend_euler.gds`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/gds/gds_ref/bend_euler_W1_R10_LWG_EWGSTD_A180_R150.gds` & `kfactory-0.8.3/gds/gds_ref/bend_euler_W1_R10_LWG_EWGSTD_A180_R150.gds`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/gds/gds_ref/bend_euler_W1_R10_LWG_EWGSTD_A90_R150.gds` & `kfactory-0.8.3/gds/gds_ref/bend_euler_W1_R10_LWG_EWGSTD_A90_R150.gds`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/gds/gds_ref/bend_euler_W1_R10_LWG_EWGSTD_T180_R150.gds` & `kfactory-0.8.3/gds/gds_ref/bend_euler_W1_R10_LWG_EWGSTD_T180_R150.gds`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/gds/gds_ref/bend_euler_W1_R10_LWG_EWGSTD_T90_R150.gds` & `kfactory-0.8.3/gds/gds_ref/bend_euler_W1_R10_LWG_EWGSTD_T90_R150.gds`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/gds/gds_ref/bend_s.gds` & `kfactory-0.8.3/gds/gds_ref/bend_s.gds`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/gds/gds_ref/bend_s_euler.gds` & `kfactory-0.8.3/gds/gds_ref/bend_s_euler.gds`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/pyproject.toml` & `kfactory-0.8.3/pyproject.toml`

 * *Files 4% similar despite different names*

```diff
@@ -9,15 +9,15 @@
 classifiers = [
 	"Programming Language :: Python :: 3.10",
 	"Operating System :: OS Independent",
 ]
 requires-python = ">=3.10"
 
 
-version = "0.8.2"
+version = "0.8.3"
 authors = [
     {name = "gdsfactory community", email = "contact@gdsfactory.com"},
 ]
 dependencies = [
 	"klayout >= 0.28.9.post2",
 	"scipy",
 	"ruamel.yaml",
@@ -232,15 +232,15 @@
 
 
 [tool.tbump]
 # Uncomment this if your project is hosted on GitHub:
 # github_url = "https://github.com/<user or organization>/<project>/"
 
 [tool.tbump.version]
-current = "0.8.2"
+current = "0.8.3"
 
 # Example of a semver regexp.
 # Make sure this matches current_version before
 # using tbump
 regex = '''
   (?P<major>\d+)
   \.
```

### Comparing `kfactory-0.8.2/src/kfactory/__init__.py` & `kfactory-0.8.3/src/kfactory/__init__.py`

 * *Files 0% similar despite different names*

```diff
@@ -24,15 +24,15 @@
     dpolygon_from_array,
 )
 from . import cells, placer, routing, utils, port, pdk, technology
 from .conf import config
 
 # from .pdk import Pdk
 
-__version__ = "0.8.2"
+__version__ = "0.8.3"
 
 logger = config.logger
 
 __all__ = [
     "KCell",
     "Instance",
     "Port",
```

### Comparing `kfactory-0.8.2/src/kfactory/cells/bezier.py` & `kfactory-0.8.3/src/kfactory/cells/bezier.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/src/kfactory/cells/circular.py` & `kfactory-0.8.3/src/kfactory/cells/circular.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/src/kfactory/cells/dbu/straight.py` & `kfactory-0.8.3/src/kfactory/cells/dbu/straight.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/src/kfactory/cells/dbu/taper.py` & `kfactory-0.8.3/src/kfactory/cells/dbu/taper.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/src/kfactory/cells/euler.py` & `kfactory-0.8.3/src/kfactory/cells/euler.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/src/kfactory/cells/straight.py` & `kfactory-0.8.3/src/kfactory/cells/straight.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/src/kfactory/cells/taper.py` & `kfactory-0.8.3/src/kfactory/cells/taper.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/src/kfactory/conf.py` & `kfactory-0.8.3/src/kfactory/conf.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/src/kfactory/kcell.py` & `kfactory-0.8.3/src/kfactory/kcell.py`

 * *Files 0% similar despite different names*

```diff
@@ -318,15 +318,17 @@
                 kcl.kcells[i] = KCell(
                     name=kc.name,
                     kcl=kcl,
                     kdb_cell=kcl.cell(kc.name),
                     ports=kc.ports,
                 )
                 kcl.kcells[i]._settings = kc.settings.model_copy()
-                kcl.kcells[i].info = kc.info.model_copy()
+                kcl.kcells[i].info = kc.info.model_copy(
+                    update={n: v for n, v in kc.info}
+                )
         kcl.rename_function = self.rename_function
         return kcl
 
     def create_cell(  # type: ignore[override]
         self,
         name: str,
         *args: str,
@@ -1812,15 +1814,15 @@
                         f"kfactory:ports:{i}:info:{name}",
                         value,
                         None,
                         True,
                     )
                 )
 
-        for name, setting in self.settings.model_copy().model_dump().items():
+        for name, setting in self.settings.model_dump().items():
             self.add_meta_info(
                 kdb.LayoutMetaInfo(f"kfactory:settings:{name}", setting, None, True)
             )
         for name, info in self.info.model_dump().items():
             self.add_meta_info(
                 kdb.LayoutMetaInfo(f"kfactory:info:{name}", info, None, True)
             )
```

### Comparing `kfactory-0.8.2/src/kfactory/pdk.py` & `kfactory-0.8.3/src/kfactory/pdk.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/src/kfactory/placer.py` & `kfactory-0.8.3/src/kfactory/placer.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/src/kfactory/port.py` & `kfactory-0.8.3/src/kfactory/port.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/src/kfactory/routing/electrical.py` & `kfactory-0.8.3/src/kfactory/routing/electrical.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/src/kfactory/routing/manhattan.py` & `kfactory-0.8.3/src/kfactory/routing/manhattan.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/src/kfactory/routing/optical.py` & `kfactory-0.8.3/src/kfactory/routing/optical.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/src/kfactory/technology/layer_map.py` & `kfactory-0.8.3/src/kfactory/technology/layer_map.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/src/kfactory/typings.py` & `kfactory-0.8.3/src/kfactory/typings.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/src/kfactory/utils/__init__.py` & `kfactory-0.8.3/src/kfactory/utils/__init__.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/src/kfactory/utils/enclosure.py` & `kfactory-0.8.3/src/kfactory/utils/enclosure.py`

 * *Files 0% similar despite different names*

```diff
@@ -323,18 +323,15 @@
                 layer_list[layer].add_section(section)
     if is_callable_widths(widths):
         for layer, layer_sec in layer_list.items():
             reg = kdb.Region()
             for section in layer_sec.sections:
 
                 def w_max(x: float) -> float:
-                    return (
-                        widths(x)  # type: ignore[operator]
-                        + 2 * section.d_max * target.kcl.dbu
-                    )
+                    return widths(x) + 2 * section.d_max * target.kcl.dbu
 
                 _r = kdb.Region(
                     path_pts_to_polygon(
                         *extrude_path_dynamic_points(
                             path,
                             w_max,
                             start_angle,
@@ -342,15 +339,15 @@
                         )
                     ).to_itype(target.kcl.dbu)
                 )
                 if section.d_min is not None:
 
                     def w_min(x: float) -> float:
                         return (
-                            widths(x)  # type: ignore[operator]
+                            widths(x)
                             + 2  # type: ignore[operator]
                             * section.d_min
                             * target.kcl.dbu
                         )
 
                     _r -= kdb.Region(
                         path_pts_to_polygon(
```

### Comparing `kfactory-0.8.2/src/kfactory/utils/fill.py` & `kfactory-0.8.3/src/kfactory/utils/fill.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/src/kfactory/utils/simplify.py` & `kfactory-0.8.3/src/kfactory/utils/simplify.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/src/kfactory/utils/violations.py` & `kfactory-0.8.3/src/kfactory/utils/violations.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/src/kfactory/widgets/interactive.py` & `kfactory-0.8.3/src/kfactory/widgets/interactive.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/src/kfactory.egg-info/PKG-INFO` & `kfactory-0.8.3/src/kfactory.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,31 +1,31 @@
 Metadata-Version: 2.1
 Name: kfactory
-Version: 0.8.2
+Version: 0.8.3
 Summary: KLayout API implementation of gdsfactory
 Author-email: gdsfactory community <contact@gdsfactory.com>
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Operating System :: OS Independent
 Requires-Python: >=3.10
 Description-Content-Type: text/markdown
 Provides-Extra: git
 Provides-Extra: dev
 Provides-Extra: docs
 Provides-Extra: ci
 Provides-Extra: ipy
 License-File: LICENSE
 
-# KFactory 0.8.2
+# KFactory 0.8.3
 
 Kfactory is a [gdsfactory](https://github.com/gdsfactory/gdsfactory)-like tool. It is built with [KLayout](https://klayout.de) as a backend instead of gdstk, but aims to offer the similar featuers.
 
 | :exclamation:  KFactory is still experimental, expect API changes without notice (even though we try to keep it to a minimum!)   |
 |---------------------------------------------------------------------------------------------------------------------------------|
 
-It is suggest to pin the version of KFactory in `requirements.txt` or `pyproject.toml` with `kfactory==0.8.2` for example.
+It is suggest to pin the version of KFactory in `requirements.txt` or `pyproject.toml` with `kfactory==0.8.3` for example.
 
 Features similar to gdsfactory:
 
 - [x] Cells & decorator for caching & storing cells
 - [x] Simple routing (point to point and simpl bundle routes for electrical routes)
 - [x] Basic cells like euler/circular bends, taper, waveguide
 - [x] Path extrusion (no interface with CrossSections)
```

### Comparing `kfactory-0.8.2/src/kfactory.egg-info/SOURCES.txt` & `kfactory-0.8.3/src/kfactory.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/src/kfactory.egg-info/requires.txt` & `kfactory-0.8.3/src/kfactory.egg-info/requires.txt`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/tests/conftest.py` & `kfactory-0.8.3/tests/conftest.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/tests/test_cell.py` & `kfactory-0.8.3/tests/test_cell.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/tests/test_cells.py` & `kfactory-0.8.3/tests/test_cells.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/tests/test_cplxcells.py` & `kfactory-0.8.3/tests/test_cplxcells.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/tests/test_enclosure.py` & `kfactory-0.8.3/tests/test_enclosure.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/tests/test_extrude.py` & `kfactory-0.8.3/tests/test_extrude.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/tests/test_meta.py` & `kfactory-0.8.3/tests/test_meta.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/tests/test_netlist.py` & `kfactory-0.8.3/tests/test_netlist.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/tests/test_pdk.py` & `kfactory-0.8.3/tests/test_pdk.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/tests/test_ports.py` & `kfactory-0.8.3/tests/test_ports.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/tests/test_rename.py` & `kfactory-0.8.3/tests/test_rename.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/tests/test_routing.py` & `kfactory-0.8.3/tests/test_routing.py`

 * *Files identical despite different names*

### Comparing `kfactory-0.8.2/tests/test_spiral.py` & `kfactory-0.8.3/tests/test_spiral.py`

 * *Files identical despite different names*


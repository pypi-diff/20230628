# Comparing `tmp/cadquery-2.3.0.tar.gz` & `tmp/cadquery-2.3.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "cadquery-2.3.0.tar", last modified: Tue Jun 27 20:17:25 2023, max compression
+gzip compressed data, was "cadquery-2.3.1.tar", last modified: Wed Jun 28 13:05:10 2023, max compression
```

## Comparing `cadquery-2.3.0.tar` & `cadquery-2.3.1.tar`

### file list

```diff
@@ -1,207 +1,207 @@
-drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-27 20:17:25.713999 cadquery-2.3.0/
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      151 2023-04-08 16:04:46.000000 cadquery-2.3.0/.coveragerc
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      271 2023-04-08 16:04:46.000000 cadquery-2.3.0/.gitattributes
-drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-27 20:17:25.645998 cadquery-2.3.0/.github/
-drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-27 20:17:25.653998 cadquery-2.3.0/.github/ISSUE_TEMPLATE/
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      270 2023-04-08 16:04:46.000000 cadquery-2.3.0/.github/ISSUE_TEMPLATE/00-generic-issue.md
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      396 2023-04-08 16:04:46.000000 cadquery-2.3.0/.github/ISSUE_TEMPLATE/config.yml
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     1140 2023-04-08 16:04:46.000000 cadquery-2.3.0/.github/ISSUE_TEMPLATE/exception_crash_report.md
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     1087 2023-04-08 16:04:46.000000 cadquery-2.3.0/.github/ISSUE_TEMPLATE/modelling-question.md
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      338 2023-04-08 16:04:46.000000 cadquery-2.3.0/.github/ISSUE_TEMPLATE/occt-feature-request.md
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      337 2023-06-15 00:40:35.000000 cadquery-2.3.0/.gitignore
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      118 2023-04-08 16:04:46.000000 cadquery-2.3.0/.readthedocs.yaml
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    11582 2023-04-08 16:04:46.000000 cadquery-2.3.0/LICENSE
--rw-rw-r--   0 jwright   (1000) jwright   (1000)       44 2023-04-08 16:04:46.000000 cadquery-2.3.0/MANIFEST.in
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    15946 2023-06-27 20:17:25.713999 cadquery-2.3.0/PKG-INFO
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    14839 2023-06-15 00:40:43.000000 cadquery-2.3.0/README.md
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     1509 2023-06-15 00:40:35.000000 cadquery-2.3.0/appveyor.yml
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      510 2023-06-15 00:31:54.000000 cadquery-2.3.0/azure-pipelines.yml
--rwxrwxr-x   0 jwright   (1000) jwright   (1000)       60 2023-04-08 16:04:46.000000 cadquery-2.3.0/build-docs.sh
-drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-27 20:17:25.657998 cadquery-2.3.0/cadquery/
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      238 2023-04-08 16:04:46.000000 cadquery-2.3.0/cadquery/README.txt
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     1568 2023-06-27 20:15:43.000000 cadquery-2.3.0/cadquery/__init__.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    16664 2023-06-15 00:40:35.000000 cadquery-2.3.0/cadquery/assembly.py
-drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-27 20:17:25.657998 cadquery-2.3.0/cadquery/contrib/
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      786 2023-04-08 16:04:46.000000 cadquery-2.3.0/cadquery/contrib/__init__.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)   163068 2023-06-26 13:17:13.000000 cadquery-2.3.0/cadquery/cq.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     9855 2023-06-22 20:40:20.000000 cadquery-2.3.0/cadquery/cq_directive.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    17535 2023-04-08 16:04:46.000000 cadquery-2.3.0/cadquery/cqgi.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     9319 2023-04-08 16:04:46.000000 cadquery-2.3.0/cadquery/hull.py
-drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-27 20:17:25.661998 cadquery-2.3.0/cadquery/occ_impl/
--rw-rw-r--   0 jwright   (1000) jwright   (1000)       37 2023-04-08 16:04:46.000000 cadquery-2.3.0/cadquery/occ_impl/README.txt
--rw-rw-r--   0 jwright   (1000) jwright   (1000)        0 2023-04-08 16:04:46.000000 cadquery-2.3.0/cadquery/occ_impl/__init__.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    12712 2023-06-15 00:40:35.000000 cadquery-2.3.0/cadquery/occ_impl/assembly.py
-drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-27 20:17:25.665998 cadquery-2.3.0/cadquery/occ_impl/exporters/
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     6458 2023-06-26 13:17:13.000000 cadquery-2.3.0/cadquery/occ_impl/exporters/__init__.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     1335 2023-04-08 16:04:46.000000 cadquery-2.3.0/cadquery/occ_impl/exporters/amf.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     6883 2023-06-15 00:40:35.000000 cadquery-2.3.0/cadquery/occ_impl/exporters/assembly.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    10908 2023-06-15 00:31:54.000000 cadquery-2.3.0/cadquery/occ_impl/exporters/dxf.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     1878 2023-04-08 16:04:46.000000 cadquery-2.3.0/cadquery/occ_impl/exporters/json.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     9480 2023-06-22 20:40:17.000000 cadquery-2.3.0/cadquery/occ_impl/exporters/svg.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     5019 2023-04-08 16:04:46.000000 cadquery-2.3.0/cadquery/occ_impl/exporters/threemf.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      202 2023-04-08 16:04:46.000000 cadquery-2.3.0/cadquery/occ_impl/exporters/utils.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      656 2023-04-08 16:04:46.000000 cadquery-2.3.0/cadquery/occ_impl/exporters/vtk.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    31346 2023-04-08 16:04:46.000000 cadquery-2.3.0/cadquery/occ_impl/geom.py
-drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-27 20:17:25.665998 cadquery-2.3.0/cadquery/occ_impl/importers/
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     2411 2023-04-08 16:04:46.000000 cadquery-2.3.0/cadquery/occ_impl/importers/__init__.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     5213 2023-04-08 16:04:46.000000 cadquery-2.3.0/cadquery/occ_impl/importers/dxf.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     5733 2023-04-08 16:04:46.000000 cadquery-2.3.0/cadquery/occ_impl/jupyter_tools.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)   111494 2023-06-15 00:40:35.000000 cadquery-2.3.0/cadquery/occ_impl/shapes.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     9363 2023-06-22 20:40:20.000000 cadquery-2.3.0/cadquery/occ_impl/sketch_solver.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    18100 2023-04-08 16:04:46.000000 cadquery-2.3.0/cadquery/occ_impl/solver.py
-drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-27 20:17:25.665998 cadquery-2.3.0/cadquery/plugins/
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      841 2023-04-08 16:04:46.000000 cadquery-2.3.0/cadquery/plugins/__init__.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)        0 2023-04-08 16:04:46.000000 cadquery-2.3.0/cadquery/py.typed
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    26129 2023-04-08 16:04:46.000000 cadquery-2.3.0/cadquery/selectors.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    26884 2023-04-08 16:04:46.000000 cadquery-2.3.0/cadquery/sketch.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)       51 2023-04-08 16:04:46.000000 cadquery-2.3.0/cadquery/types.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)       59 2023-04-08 16:04:46.000000 cadquery-2.3.0/cadquery/units.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     1671 2023-04-08 16:04:46.000000 cadquery-2.3.0/cadquery/utils.py
-drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-27 20:17:25.657998 cadquery-2.3.0/cadquery.egg-info/
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    15946 2023-06-27 20:17:25.000000 cadquery-2.3.0/cadquery.egg-info/PKG-INFO
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     5279 2023-06-27 20:17:25.000000 cadquery-2.3.0/cadquery.egg-info/SOURCES.txt
--rw-rw-r--   0 jwright   (1000) jwright   (1000)        1 2023-06-27 20:17:25.000000 cadquery-2.3.0/cadquery.egg-info/dependency_links.txt
--rw-rw-r--   0 jwright   (1000) jwright   (1000)        1 2023-04-08 16:06:38.000000 cadquery-2.3.0/cadquery.egg-info/not-zip-safe
--rw-rw-r--   0 jwright   (1000) jwright   (1000)       78 2023-06-27 20:17:25.000000 cadquery-2.3.0/cadquery.egg-info/requires.txt
--rw-rw-r--   0 jwright   (1000) jwright   (1000)        9 2023-06-27 20:17:25.000000 cadquery-2.3.0/cadquery.egg-info/top_level.txt
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    31014 2023-06-27 20:15:43.000000 cadquery-2.3.0/changes.md
-drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-27 20:17:25.665998 cadquery-2.3.0/conda/
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      705 2023-06-15 00:31:54.000000 cadquery-2.3.0/conda/meta.yaml
-drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-27 20:17:25.669998 cadquery-2.3.0/conda/web-installer/
--rw-rw-r--   0 jwright   (1000) jwright   (1000)       96 2023-04-08 16:04:46.000000 cadquery-2.3.0/conda/web-installer/.gitignore
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      886 2023-04-08 16:04:46.000000 cadquery-2.3.0/conda/web-installer/Readme.md
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     2106 2023-04-08 16:04:46.000000 cadquery-2.3.0/conda/web-installer/build.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      591 2023-04-08 16:04:46.000000 cadquery-2.3.0/conda/web-installer/construct.yaml.jinja2
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      239 2023-04-08 16:04:46.000000 cadquery-2.3.0/conda/web-installer/post-install.bat.jinja2
--rwxrwxr-x   0 jwright   (1000) jwright   (1000)      270 2023-04-08 16:04:46.000000 cadquery-2.3.0/conda/web-installer/post-install.sh.jinja2
--rw-rw-r--   0 jwright   (1000) jwright   (1000)       73 2023-04-08 16:04:46.000000 cadquery-2.3.0/conda_build.bat
--rw-rw-r--   0 jwright   (1000) jwright   (1000)       73 2023-04-08 16:04:46.000000 cadquery-2.3.0/conda_build.sh
--rw-rw-r--   0 jwright   (1000) jwright   (1000)       17 2023-04-08 16:04:46.000000 cadquery-2.3.0/conda_build_config.yaml
-drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-27 20:17:25.673998 cadquery-2.3.0/doc/
--rw-rw-r--   0 jwright   (1000) jwright   (1000)       76 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/README
-drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-27 20:17:25.681998 cadquery-2.3.0/doc/_static/
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    59186 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/ParametricPulley.PNG
--rw-rw-r--   0 jwright   (1000) jwright   (1000)   139192 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/assy.png
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     9385 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/block.png
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    27453 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/cadquery_cheatsheet.html
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    40378 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/door_assy.png
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    39775 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/door_assy_freecad.png
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    27301 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/hyOzd-cablefix.png
--rw-rw-r--   0 jwright   (1000) jwright   (1000)   149415 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/hyOzd-finished.jpg
-drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-27 20:17:25.685998 cadquery-2.3.0/doc/_static/importexport/
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     1528 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/importexport/box_custom_options.svg
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     1484 2023-06-15 00:31:54.000000 cadquery-2.3.0/doc/_static/importexport/box_custom_options_perspective.svg
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     2405 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/importexport/box_default_options.svg
-drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-27 20:17:25.685998 cadquery-2.3.0/doc/_static/logo/
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      121 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/logo/README.md
-drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-27 20:17:25.689998 cadquery-2.3.0/doc/_static/logo/Roboto_Font/
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    11560 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/logo/Roboto_Font/LICENSE.txt
--rw-rw-r--   0 jwright   (1000) jwright   (1000)   170760 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/logo/Roboto_Font/Roboto-Bold.ttf
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     3965 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/logo/cadquery_logo_dark.svg
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     2783 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/logo/cadquery_logo_dark_inkscape.svg
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     3973 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/logo/cadquery_logo_light.svg
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     2785 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/logo/cadquery_logo_light_inkscape.svg
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     3163 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/new_badge.png
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    66208 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/parametric-cup-screencap.PNG
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    59428 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/parametric-pillowblock-screencap.png
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    17582 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/pillowblock.png
-drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-27 20:17:25.689998 cadquery-2.3.0/doc/_static/quickstart/
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    36021 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/quickstart/000.png
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    38803 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/quickstart/001.png
--rw-rw-r--   0 jwright   (1000) jwright   (1000)   125731 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/quickstart/002.png
--rw-rw-r--   0 jwright   (1000) jwright   (1000)   147791 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/quickstart/003.png
--rw-rw-r--   0 jwright   (1000) jwright   (1000)   185063 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/quickstart/004.png
--rw-rw-r--   0 jwright   (1000) jwright   (1000)   192146 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/quickstart/005.png
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     6162 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/quickstart-1.png
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     6162 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/quickstart-2.png
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     7084 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/quickstart-3.png
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     7095 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/quickstart-4.png
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    11703 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/quickstart-5.png
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    17947 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/quickstart.png
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    21577 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/simple_assy.png
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     8698 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/simpleblock.png
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      138 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/tables.css
--rw-rw-r--   0 jwright   (1000) jwright   (1000)  2398290 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/_static/vtk.js
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     5355 2023-06-15 00:31:54.000000 cadquery-2.3.0/doc/apireference.rst
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    92272 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/assy.rst
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     1874 2023-06-15 00:31:54.000000 cadquery-2.3.0/doc/classreference.rst
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    10681 2023-06-27 20:15:43.000000 cadquery-2.3.0/doc/conf.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     7750 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/cqgi.rst
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     3299 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/designprinciples.rst
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    49613 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/examples.rst
-drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-27 20:17:25.689998 cadquery-2.3.0/doc/ext/
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    11026 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/ext/sphinx_autodoc_multimethod.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     7714 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/extending.rst
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      862 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/fileformat.rst
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     1873 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/gen_colors.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    17965 2023-06-22 20:40:17.000000 cadquery-2.3.0/doc/importexport.rst
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     1588 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/index.rst
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     8789 2023-06-15 00:40:43.000000 cadquery-2.3.0/doc/installation.rst
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     4150 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/intro.rst
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    36905 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/primer.rst
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     9113 2023-06-15 00:40:35.000000 cadquery-2.3.0/doc/quickstart.rst
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     1993 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/roadmap.rst
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     6878 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/selectors.rst
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     7323 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/sketch.rst
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    56566 2023-04-08 16:04:46.000000 cadquery-2.3.0/doc/vslot-2020_1.dxf
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      458 2023-06-22 20:40:20.000000 cadquery-2.3.0/environment.yml
-drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-27 20:17:25.705999 cadquery-2.3.0/examples/
--rw-rw-r--   0 jwright   (1000) jwright   (1000)  4570724 2023-04-08 16:04:46.000000 cadquery-2.3.0/examples/CQ examples.ipynb
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      754 2023-04-08 16:04:46.000000 cadquery-2.3.0/examples/Ex001_Simple_Block.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      954 2023-04-08 16:04:46.000000 cadquery-2.3.0/examples/Ex002_Block_With_Bored_Center_Hole.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     1932 2023-04-08 16:04:46.000000 cadquery-2.3.0/examples/Ex003_Pillow_Block_With_Counterbored_Holes.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     1420 2023-04-08 16:04:46.000000 cadquery-2.3.0/examples/Ex004_Extruded_Cylindrical_Plate.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     2451 2023-04-08 16:04:46.000000 cadquery-2.3.0/examples/Ex005_Extruded_Lines_and_Arcs.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     1680 2023-04-08 16:04:46.000000 cadquery-2.3.0/examples/Ex006_Moving_the_Current_Working_Point.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     1422 2023-04-08 16:04:46.000000 cadquery-2.3.0/examples/Ex007_Using_Point_Lists.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     2073 2023-04-08 16:04:46.000000 cadquery-2.3.0/examples/Ex008_Polygon_Creation.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     1541 2023-04-08 16:04:46.000000 cadquery-2.3.0/examples/Ex009_Polylines.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      730 2023-04-08 16:04:46.000000 cadquery-2.3.0/examples/Ex010_Defining_an_Edge_with_a_Spline.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      786 2023-04-08 16:04:46.000000 cadquery-2.3.0/examples/Ex011_Mirroring_Symmetric_Geometry.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      625 2023-04-08 16:04:46.000000 cadquery-2.3.0/examples/Ex012_Creating_Workplanes_on_Faces.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      953 2023-04-08 16:04:46.000000 cadquery-2.3.0/examples/Ex013_Locating_a_Workplane_on_a_Vertex.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      811 2023-04-08 16:04:46.000000 cadquery-2.3.0/examples/Ex014_Offset_Workplanes.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     1067 2023-04-08 16:04:46.000000 cadquery-2.3.0/examples/Ex015_Rotated_Workplanes.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      960 2023-04-08 16:04:46.000000 cadquery-2.3.0/examples/Ex016_Using_Construction_Geometry.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      631 2023-04-08 16:04:46.000000 cadquery-2.3.0/examples/Ex017_Shelling_to_Create_Thin_Features.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      937 2023-04-08 16:04:46.000000 cadquery-2.3.0/examples/Ex018_Making_Lofts.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      940 2023-04-08 16:04:46.000000 cadquery-2.3.0/examples/Ex019_Counter_Sunk_Holes.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      630 2023-04-08 16:04:46.000000 cadquery-2.3.0/examples/Ex020_Rounding_Corners_with_Fillets.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     1259 2023-04-08 16:04:46.000000 cadquery-2.3.0/examples/Ex021_Splitting_an_Object.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     1054 2023-04-08 16:04:46.000000 cadquery-2.3.0/examples/Ex022_Revolution.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     1538 2023-04-08 16:04:46.000000 cadquery-2.3.0/examples/Ex023_Sweep.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     2232 2023-04-08 16:04:46.000000 cadquery-2.3.0/examples/Ex024_Sweep_With_Multiple_Sections.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      620 2023-04-08 16:04:46.000000 cadquery-2.3.0/examples/Ex025_Swept_Helix.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     1274 2023-04-08 16:04:46.000000 cadquery-2.3.0/examples/Ex026_Case_Seam_Lip.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     1634 2023-04-08 16:04:46.000000 cadquery-2.3.0/examples/Ex100_Lego_Brick.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     5427 2023-04-08 16:04:46.000000 cadquery-2.3.0/examples/Ex101_InterpPlate.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      623 2023-04-08 16:04:46.000000 cadquery-2.3.0/mypy.ini
--rw-rw-r--   0 jwright   (1000) jwright   (1000)       38 2023-06-27 20:17:25.713999 cadquery-2.3.0/setup.cfg
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     2927 2023-06-27 20:15:43.000000 cadquery-2.3.0/setup.py
-drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-27 20:17:25.709999 cadquery-2.3.0/tests/
--rw-rw-r--   0 jwright   (1000) jwright   (1000)       67 2023-04-08 16:04:46.000000 cadquery-2.3.0/tests/README.txt
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     1409 2023-04-08 16:04:46.000000 cadquery-2.3.0/tests/__init__.py
--rwxrwxr-x   0 jwright   (1000) jwright   (1000)     2128 2023-04-08 16:04:46.000000 cadquery-2.3.0/tests/naca.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    45440 2023-06-15 00:40:35.000000 cadquery-2.3.0/tests/test_assembly.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    24915 2023-04-08 16:04:46.000000 cadquery-2.3.0/tests/test_cad_objects.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)   186495 2023-06-26 13:17:13.000000 cadquery-2.3.0/tests/test_cadquery.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     6525 2023-04-08 16:04:46.000000 cadquery-2.3.0/tests/test_cqgi.py
--rwxrwxr-x   0 jwright   (1000) jwright   (1000)     1751 2023-04-08 16:04:46.000000 cadquery-2.3.0/tests/test_examples.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    27003 2023-06-26 13:17:13.000000 cadquery-2.3.0/tests/test_exporters.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      806 2023-04-08 16:04:46.000000 cadquery-2.3.0/tests/test_hull.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     6111 2023-04-08 16:04:46.000000 cadquery-2.3.0/tests/test_importers.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      746 2023-04-08 16:04:46.000000 cadquery-2.3.0/tests/test_jupyter.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    41524 2023-04-08 16:04:46.000000 cadquery-2.3.0/tests/test_selectors.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    17973 2023-06-22 20:40:20.000000 cadquery-2.3.0/tests/test_sketch.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)      580 2023-04-08 16:04:46.000000 cadquery-2.3.0/tests/test_utils.py
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     9975 2023-04-08 16:04:46.000000 cadquery-2.3.0/tests/test_workplanes.py
-drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-27 20:17:25.713999 cadquery-2.3.0/tests/testdata/
--rw-rw-r--   0 jwright   (1000) jwright   (1000)   184298 2023-04-08 16:04:46.000000 cadquery-2.3.0/tests/testdata/1001.dxf
--rw-rw-r--   0 jwright   (1000) jwright   (1000)   267838 2023-04-08 16:04:46.000000 cadquery-2.3.0/tests/testdata/MC 12x31.dxf
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    96932 2023-04-08 16:04:46.000000 cadquery-2.3.0/tests/testdata/OpenSans-Regular.ttf
--rw-rw-r--   0 jwright   (1000) jwright   (1000)   108437 2023-04-08 16:04:46.000000 cadquery-2.3.0/tests/testdata/gear.dxf
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     7428 2023-04-08 16:04:46.000000 cadquery-2.3.0/tests/testdata/genshi.dxf
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    13267 2023-04-08 16:04:46.000000 cadquery-2.3.0/tests/testdata/rational_spline.dxf
--rw-rw-r--   0 jwright   (1000) jwright   (1000)    18322 2023-04-08 16:04:46.000000 cadquery-2.3.0/tests/testdata/red_cube_blue_cylinder.step
--rw-rw-r--   0 jwright   (1000) jwright   (1000)     5135 2023-04-08 16:04:46.000000 cadquery-2.3.0/tests/testdata/spline.dxf
--rw-rw-r--   0 jwright   (1000) jwright   (1000)   135695 2023-04-08 16:04:46.000000 cadquery-2.3.0/tests/testdata/three_layers.dxf
+drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-28 13:05:10.966484 cadquery-2.3.1/
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      151 2023-04-08 16:04:46.000000 cadquery-2.3.1/.coveragerc
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      271 2023-04-08 16:04:46.000000 cadquery-2.3.1/.gitattributes
+drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-28 13:05:10.898483 cadquery-2.3.1/.github/
+drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-28 13:05:10.910483 cadquery-2.3.1/.github/ISSUE_TEMPLATE/
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      270 2023-04-08 16:04:46.000000 cadquery-2.3.1/.github/ISSUE_TEMPLATE/00-generic-issue.md
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      396 2023-04-08 16:04:46.000000 cadquery-2.3.1/.github/ISSUE_TEMPLATE/config.yml
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     1140 2023-04-08 16:04:46.000000 cadquery-2.3.1/.github/ISSUE_TEMPLATE/exception_crash_report.md
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     1087 2023-04-08 16:04:46.000000 cadquery-2.3.1/.github/ISSUE_TEMPLATE/modelling-question.md
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      338 2023-04-08 16:04:46.000000 cadquery-2.3.1/.github/ISSUE_TEMPLATE/occt-feature-request.md
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      337 2023-06-15 00:40:35.000000 cadquery-2.3.1/.gitignore
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      118 2023-04-08 16:04:46.000000 cadquery-2.3.1/.readthedocs.yaml
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    11582 2023-04-08 16:04:46.000000 cadquery-2.3.1/LICENSE
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)       44 2023-04-08 16:04:46.000000 cadquery-2.3.1/MANIFEST.in
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    15946 2023-06-28 13:05:10.966484 cadquery-2.3.1/PKG-INFO
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    14839 2023-06-15 00:40:43.000000 cadquery-2.3.1/README.md
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     1509 2023-06-15 00:40:35.000000 cadquery-2.3.1/appveyor.yml
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      510 2023-06-15 00:31:54.000000 cadquery-2.3.1/azure-pipelines.yml
+-rwxrwxr-x   0 jwright   (1000) jwright   (1000)       60 2023-04-08 16:04:46.000000 cadquery-2.3.1/build-docs.sh
+drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-28 13:05:10.910483 cadquery-2.3.1/cadquery/
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      238 2023-04-08 16:04:46.000000 cadquery-2.3.1/cadquery/README.txt
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     1568 2023-06-28 13:04:28.000000 cadquery-2.3.1/cadquery/__init__.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    16664 2023-06-15 00:40:35.000000 cadquery-2.3.1/cadquery/assembly.py
+drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-28 13:05:10.914483 cadquery-2.3.1/cadquery/contrib/
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      786 2023-04-08 16:04:46.000000 cadquery-2.3.1/cadquery/contrib/__init__.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)   163068 2023-06-26 13:17:13.000000 cadquery-2.3.1/cadquery/cq.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     9855 2023-06-22 20:40:20.000000 cadquery-2.3.1/cadquery/cq_directive.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    17535 2023-04-08 16:04:46.000000 cadquery-2.3.1/cadquery/cqgi.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     9319 2023-04-08 16:04:46.000000 cadquery-2.3.1/cadquery/hull.py
+drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-28 13:05:10.914483 cadquery-2.3.1/cadquery/occ_impl/
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)       37 2023-04-08 16:04:46.000000 cadquery-2.3.1/cadquery/occ_impl/README.txt
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)        0 2023-04-08 16:04:46.000000 cadquery-2.3.1/cadquery/occ_impl/__init__.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    12712 2023-06-15 00:40:35.000000 cadquery-2.3.1/cadquery/occ_impl/assembly.py
+drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-28 13:05:10.914483 cadquery-2.3.1/cadquery/occ_impl/exporters/
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     6458 2023-06-26 13:17:13.000000 cadquery-2.3.1/cadquery/occ_impl/exporters/__init__.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     1335 2023-04-08 16:04:46.000000 cadquery-2.3.1/cadquery/occ_impl/exporters/amf.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     6883 2023-06-15 00:40:35.000000 cadquery-2.3.1/cadquery/occ_impl/exporters/assembly.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    10908 2023-06-15 00:31:54.000000 cadquery-2.3.1/cadquery/occ_impl/exporters/dxf.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     1878 2023-04-08 16:04:46.000000 cadquery-2.3.1/cadquery/occ_impl/exporters/json.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     9480 2023-06-22 20:40:17.000000 cadquery-2.3.1/cadquery/occ_impl/exporters/svg.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     5019 2023-04-08 16:04:46.000000 cadquery-2.3.1/cadquery/occ_impl/exporters/threemf.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      202 2023-04-08 16:04:46.000000 cadquery-2.3.1/cadquery/occ_impl/exporters/utils.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      656 2023-04-08 16:04:46.000000 cadquery-2.3.1/cadquery/occ_impl/exporters/vtk.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    31346 2023-04-08 16:04:46.000000 cadquery-2.3.1/cadquery/occ_impl/geom.py
+drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-28 13:05:10.914483 cadquery-2.3.1/cadquery/occ_impl/importers/
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     2411 2023-04-08 16:04:46.000000 cadquery-2.3.1/cadquery/occ_impl/importers/__init__.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     5213 2023-04-08 16:04:46.000000 cadquery-2.3.1/cadquery/occ_impl/importers/dxf.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     5733 2023-04-08 16:04:46.000000 cadquery-2.3.1/cadquery/occ_impl/jupyter_tools.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)   111494 2023-06-15 00:40:35.000000 cadquery-2.3.1/cadquery/occ_impl/shapes.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     9363 2023-06-22 20:40:20.000000 cadquery-2.3.1/cadquery/occ_impl/sketch_solver.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    18100 2023-04-08 16:04:46.000000 cadquery-2.3.1/cadquery/occ_impl/solver.py
+drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-28 13:05:10.914483 cadquery-2.3.1/cadquery/plugins/
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      841 2023-04-08 16:04:46.000000 cadquery-2.3.1/cadquery/plugins/__init__.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)        0 2023-04-08 16:04:46.000000 cadquery-2.3.1/cadquery/py.typed
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    26129 2023-04-08 16:04:46.000000 cadquery-2.3.1/cadquery/selectors.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    26884 2023-04-08 16:04:46.000000 cadquery-2.3.1/cadquery/sketch.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)       51 2023-04-08 16:04:46.000000 cadquery-2.3.1/cadquery/types.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)       59 2023-04-08 16:04:46.000000 cadquery-2.3.1/cadquery/units.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     1671 2023-04-08 16:04:46.000000 cadquery-2.3.1/cadquery/utils.py
+drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-28 13:05:10.914483 cadquery-2.3.1/cadquery.egg-info/
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    15946 2023-06-28 13:05:10.000000 cadquery-2.3.1/cadquery.egg-info/PKG-INFO
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     5279 2023-06-28 13:05:10.000000 cadquery-2.3.1/cadquery.egg-info/SOURCES.txt
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)        1 2023-06-28 13:05:10.000000 cadquery-2.3.1/cadquery.egg-info/dependency_links.txt
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)        1 2023-04-08 16:06:38.000000 cadquery-2.3.1/cadquery.egg-info/not-zip-safe
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      174 2023-06-28 13:05:10.000000 cadquery-2.3.1/cadquery.egg-info/requires.txt
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)        9 2023-06-28 13:05:10.000000 cadquery-2.3.1/cadquery.egg-info/top_level.txt
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    31084 2023-06-28 13:04:14.000000 cadquery-2.3.1/changes.md
+drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-28 13:05:10.918483 cadquery-2.3.1/conda/
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      705 2023-06-15 00:31:54.000000 cadquery-2.3.1/conda/meta.yaml
+drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-28 13:05:10.918483 cadquery-2.3.1/conda/web-installer/
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)       96 2023-04-08 16:04:46.000000 cadquery-2.3.1/conda/web-installer/.gitignore
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      886 2023-04-08 16:04:46.000000 cadquery-2.3.1/conda/web-installer/Readme.md
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     2106 2023-04-08 16:04:46.000000 cadquery-2.3.1/conda/web-installer/build.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      591 2023-04-08 16:04:46.000000 cadquery-2.3.1/conda/web-installer/construct.yaml.jinja2
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      239 2023-04-08 16:04:46.000000 cadquery-2.3.1/conda/web-installer/post-install.bat.jinja2
+-rwxrwxr-x   0 jwright   (1000) jwright   (1000)      270 2023-04-08 16:04:46.000000 cadquery-2.3.1/conda/web-installer/post-install.sh.jinja2
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)       73 2023-04-08 16:04:46.000000 cadquery-2.3.1/conda_build.bat
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)       73 2023-04-08 16:04:46.000000 cadquery-2.3.1/conda_build.sh
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)       17 2023-04-08 16:04:46.000000 cadquery-2.3.1/conda_build_config.yaml
+drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-28 13:05:10.926483 cadquery-2.3.1/doc/
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)       76 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/README
+drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-28 13:05:10.930483 cadquery-2.3.1/doc/_static/
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    59186 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/ParametricPulley.PNG
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)   139192 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/assy.png
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     9385 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/block.png
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    27453 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/cadquery_cheatsheet.html
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    40378 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/door_assy.png
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    39775 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/door_assy_freecad.png
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    27301 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/hyOzd-cablefix.png
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)   149415 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/hyOzd-finished.jpg
+drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-28 13:05:10.934483 cadquery-2.3.1/doc/_static/importexport/
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     1528 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/importexport/box_custom_options.svg
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     1484 2023-06-15 00:31:54.000000 cadquery-2.3.1/doc/_static/importexport/box_custom_options_perspective.svg
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     2405 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/importexport/box_default_options.svg
+drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-28 13:05:10.934483 cadquery-2.3.1/doc/_static/logo/
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      121 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/logo/README.md
+drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-28 13:05:10.938483 cadquery-2.3.1/doc/_static/logo/Roboto_Font/
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    11560 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/logo/Roboto_Font/LICENSE.txt
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)   170760 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/logo/Roboto_Font/Roboto-Bold.ttf
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     3965 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/logo/cadquery_logo_dark.svg
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     2783 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/logo/cadquery_logo_dark_inkscape.svg
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     3973 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/logo/cadquery_logo_light.svg
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     2785 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/logo/cadquery_logo_light_inkscape.svg
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     3163 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/new_badge.png
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    66208 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/parametric-cup-screencap.PNG
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    59428 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/parametric-pillowblock-screencap.png
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    17582 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/pillowblock.png
+drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-28 13:05:10.942484 cadquery-2.3.1/doc/_static/quickstart/
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    36021 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/quickstart/000.png
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    38803 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/quickstart/001.png
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)   125731 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/quickstart/002.png
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)   147791 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/quickstart/003.png
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)   185063 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/quickstart/004.png
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)   192146 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/quickstart/005.png
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     6162 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/quickstart-1.png
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     6162 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/quickstart-2.png
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     7084 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/quickstart-3.png
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     7095 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/quickstart-4.png
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    11703 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/quickstart-5.png
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    17947 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/quickstart.png
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    21577 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/simple_assy.png
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     8698 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/simpleblock.png
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      138 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/tables.css
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)  2398290 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/_static/vtk.js
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     5355 2023-06-15 00:31:54.000000 cadquery-2.3.1/doc/apireference.rst
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    92272 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/assy.rst
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     1874 2023-06-15 00:31:54.000000 cadquery-2.3.1/doc/classreference.rst
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    10681 2023-06-28 13:04:33.000000 cadquery-2.3.1/doc/conf.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     7750 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/cqgi.rst
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     3299 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/designprinciples.rst
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    49613 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/examples.rst
+drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-28 13:05:10.942484 cadquery-2.3.1/doc/ext/
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    11026 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/ext/sphinx_autodoc_multimethod.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     7714 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/extending.rst
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      862 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/fileformat.rst
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     1873 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/gen_colors.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    17965 2023-06-22 20:40:17.000000 cadquery-2.3.1/doc/importexport.rst
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     1588 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/index.rst
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     8789 2023-06-15 00:40:43.000000 cadquery-2.3.1/doc/installation.rst
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     4150 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/intro.rst
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    36905 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/primer.rst
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     9113 2023-06-15 00:40:35.000000 cadquery-2.3.1/doc/quickstart.rst
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     1993 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/roadmap.rst
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     6878 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/selectors.rst
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     7323 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/sketch.rst
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    56566 2023-04-08 16:04:46.000000 cadquery-2.3.1/doc/vslot-2020_1.dxf
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      458 2023-06-22 20:40:20.000000 cadquery-2.3.1/environment.yml
+drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-28 13:05:10.962484 cadquery-2.3.1/examples/
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)  4570724 2023-04-08 16:04:46.000000 cadquery-2.3.1/examples/CQ examples.ipynb
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      754 2023-04-08 16:04:46.000000 cadquery-2.3.1/examples/Ex001_Simple_Block.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      954 2023-04-08 16:04:46.000000 cadquery-2.3.1/examples/Ex002_Block_With_Bored_Center_Hole.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     1932 2023-04-08 16:04:46.000000 cadquery-2.3.1/examples/Ex003_Pillow_Block_With_Counterbored_Holes.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     1420 2023-04-08 16:04:46.000000 cadquery-2.3.1/examples/Ex004_Extruded_Cylindrical_Plate.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     2451 2023-04-08 16:04:46.000000 cadquery-2.3.1/examples/Ex005_Extruded_Lines_and_Arcs.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     1680 2023-04-08 16:04:46.000000 cadquery-2.3.1/examples/Ex006_Moving_the_Current_Working_Point.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     1422 2023-04-08 16:04:46.000000 cadquery-2.3.1/examples/Ex007_Using_Point_Lists.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     2073 2023-04-08 16:04:46.000000 cadquery-2.3.1/examples/Ex008_Polygon_Creation.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     1541 2023-04-08 16:04:46.000000 cadquery-2.3.1/examples/Ex009_Polylines.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      730 2023-04-08 16:04:46.000000 cadquery-2.3.1/examples/Ex010_Defining_an_Edge_with_a_Spline.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      786 2023-04-08 16:04:46.000000 cadquery-2.3.1/examples/Ex011_Mirroring_Symmetric_Geometry.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      625 2023-04-08 16:04:46.000000 cadquery-2.3.1/examples/Ex012_Creating_Workplanes_on_Faces.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      953 2023-04-08 16:04:46.000000 cadquery-2.3.1/examples/Ex013_Locating_a_Workplane_on_a_Vertex.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      811 2023-04-08 16:04:46.000000 cadquery-2.3.1/examples/Ex014_Offset_Workplanes.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     1067 2023-04-08 16:04:46.000000 cadquery-2.3.1/examples/Ex015_Rotated_Workplanes.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      960 2023-04-08 16:04:46.000000 cadquery-2.3.1/examples/Ex016_Using_Construction_Geometry.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      631 2023-04-08 16:04:46.000000 cadquery-2.3.1/examples/Ex017_Shelling_to_Create_Thin_Features.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      937 2023-04-08 16:04:46.000000 cadquery-2.3.1/examples/Ex018_Making_Lofts.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      940 2023-04-08 16:04:46.000000 cadquery-2.3.1/examples/Ex019_Counter_Sunk_Holes.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      630 2023-04-08 16:04:46.000000 cadquery-2.3.1/examples/Ex020_Rounding_Corners_with_Fillets.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     1259 2023-04-08 16:04:46.000000 cadquery-2.3.1/examples/Ex021_Splitting_an_Object.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     1054 2023-04-08 16:04:46.000000 cadquery-2.3.1/examples/Ex022_Revolution.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     1538 2023-04-08 16:04:46.000000 cadquery-2.3.1/examples/Ex023_Sweep.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     2232 2023-04-08 16:04:46.000000 cadquery-2.3.1/examples/Ex024_Sweep_With_Multiple_Sections.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      620 2023-04-08 16:04:46.000000 cadquery-2.3.1/examples/Ex025_Swept_Helix.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     1274 2023-04-08 16:04:46.000000 cadquery-2.3.1/examples/Ex026_Case_Seam_Lip.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     1634 2023-04-08 16:04:46.000000 cadquery-2.3.1/examples/Ex100_Lego_Brick.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     5427 2023-04-08 16:04:46.000000 cadquery-2.3.1/examples/Ex101_InterpPlate.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      623 2023-04-08 16:04:46.000000 cadquery-2.3.1/mypy.ini
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)       38 2023-06-28 13:05:10.966484 cadquery-2.3.1/setup.cfg
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     2927 2023-06-28 13:04:23.000000 cadquery-2.3.1/setup.py
+drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-28 13:05:10.966484 cadquery-2.3.1/tests/
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)       67 2023-04-08 16:04:46.000000 cadquery-2.3.1/tests/README.txt
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     1409 2023-04-08 16:04:46.000000 cadquery-2.3.1/tests/__init__.py
+-rwxrwxr-x   0 jwright   (1000) jwright   (1000)     2128 2023-04-08 16:04:46.000000 cadquery-2.3.1/tests/naca.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    45440 2023-06-15 00:40:35.000000 cadquery-2.3.1/tests/test_assembly.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    24915 2023-04-08 16:04:46.000000 cadquery-2.3.1/tests/test_cad_objects.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)   186495 2023-06-26 13:17:13.000000 cadquery-2.3.1/tests/test_cadquery.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     6525 2023-04-08 16:04:46.000000 cadquery-2.3.1/tests/test_cqgi.py
+-rwxrwxr-x   0 jwright   (1000) jwright   (1000)     1751 2023-04-08 16:04:46.000000 cadquery-2.3.1/tests/test_examples.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    27003 2023-06-26 13:17:13.000000 cadquery-2.3.1/tests/test_exporters.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      806 2023-04-08 16:04:46.000000 cadquery-2.3.1/tests/test_hull.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     6111 2023-04-08 16:04:46.000000 cadquery-2.3.1/tests/test_importers.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      746 2023-04-08 16:04:46.000000 cadquery-2.3.1/tests/test_jupyter.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    41524 2023-04-08 16:04:46.000000 cadquery-2.3.1/tests/test_selectors.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    17973 2023-06-22 20:40:20.000000 cadquery-2.3.1/tests/test_sketch.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)      580 2023-04-08 16:04:46.000000 cadquery-2.3.1/tests/test_utils.py
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     9975 2023-04-08 16:04:46.000000 cadquery-2.3.1/tests/test_workplanes.py
+drwxrwxr-x   0 jwright   (1000) jwright   (1000)        0 2023-06-28 13:05:10.966484 cadquery-2.3.1/tests/testdata/
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)   184298 2023-04-08 16:04:46.000000 cadquery-2.3.1/tests/testdata/1001.dxf
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)   267838 2023-04-08 16:04:46.000000 cadquery-2.3.1/tests/testdata/MC 12x31.dxf
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    96932 2023-04-08 16:04:46.000000 cadquery-2.3.1/tests/testdata/OpenSans-Regular.ttf
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)   108437 2023-04-08 16:04:46.000000 cadquery-2.3.1/tests/testdata/gear.dxf
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     7428 2023-04-08 16:04:46.000000 cadquery-2.3.1/tests/testdata/genshi.dxf
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    13267 2023-04-08 16:04:46.000000 cadquery-2.3.1/tests/testdata/rational_spline.dxf
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)    18322 2023-04-08 16:04:46.000000 cadquery-2.3.1/tests/testdata/red_cube_blue_cylinder.step
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)     5135 2023-04-08 16:04:46.000000 cadquery-2.3.1/tests/testdata/spline.dxf
+-rw-rw-r--   0 jwright   (1000) jwright   (1000)   135695 2023-04-08 16:04:46.000000 cadquery-2.3.1/tests/testdata/three_layers.dxf
```

### Comparing `cadquery-2.3.0/.github/ISSUE_TEMPLATE/exception_crash_report.md` & `cadquery-2.3.1/.github/ISSUE_TEMPLATE/exception_crash_report.md`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/.github/ISSUE_TEMPLATE/modelling-question.md` & `cadquery-2.3.1/.github/ISSUE_TEMPLATE/modelling-question.md`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/LICENSE` & `cadquery-2.3.1/LICENSE`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/PKG-INFO` & `cadquery-2.3.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: cadquery
-Version: 2.3.0
+Version: 2.3.1
 Summary: CadQuery is a parametric  scripting language for creating and traversing CAD models
 Home-page: https://github.com/CadQuery/cadquery
 Author: David Cowden
 Author-email: dave.cowden@gmail.com
 License: Apache Public License 2.0
 Platform: any
 Classifier: Development Status :: 5 - Production/Stable
```

### Comparing `cadquery-2.3.0/README.md` & `cadquery-2.3.1/README.md`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/appveyor.yml` & `cadquery-2.3.1/appveyor.yml`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/cadquery/__init__.py` & `cadquery-2.3.1/cadquery/__init__.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 from importlib.metadata import version, PackageNotFoundError
 
 try:
     __version__ = version("cadquery")
 except PackageNotFoundError:
     # package is not installed
-    __version__ = "2.3.0"
+    __version__ = "2.3.1"
 
 # these items point to the OCC implementation
 from .occ_impl.geom import Plane, BoundBox, Vector, Matrix, Location
 from .occ_impl.shapes import (
     Shape,
     Vertex,
     Edge,
```

### Comparing `cadquery-2.3.0/cadquery/assembly.py` & `cadquery-2.3.1/cadquery/assembly.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/cadquery/contrib/__init__.py` & `cadquery-2.3.1/cadquery/contrib/__init__.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/cadquery/cq.py` & `cadquery-2.3.1/cadquery/cq.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/cadquery/cq_directive.py` & `cadquery-2.3.1/cadquery/cq_directive.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/cadquery/cqgi.py` & `cadquery-2.3.1/cadquery/cqgi.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/cadquery/hull.py` & `cadquery-2.3.1/cadquery/hull.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/cadquery/occ_impl/assembly.py` & `cadquery-2.3.1/cadquery/occ_impl/assembly.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/cadquery/occ_impl/exporters/__init__.py` & `cadquery-2.3.1/cadquery/occ_impl/exporters/__init__.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/cadquery/occ_impl/exporters/amf.py` & `cadquery-2.3.1/cadquery/occ_impl/exporters/amf.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/cadquery/occ_impl/exporters/assembly.py` & `cadquery-2.3.1/cadquery/occ_impl/exporters/assembly.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/cadquery/occ_impl/exporters/dxf.py` & `cadquery-2.3.1/cadquery/occ_impl/exporters/dxf.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/cadquery/occ_impl/exporters/json.py` & `cadquery-2.3.1/cadquery/occ_impl/exporters/json.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/cadquery/occ_impl/exporters/svg.py` & `cadquery-2.3.1/cadquery/occ_impl/exporters/svg.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/cadquery/occ_impl/exporters/threemf.py` & `cadquery-2.3.1/cadquery/occ_impl/exporters/threemf.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/cadquery/occ_impl/exporters/vtk.py` & `cadquery-2.3.1/cadquery/occ_impl/exporters/vtk.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/cadquery/occ_impl/geom.py` & `cadquery-2.3.1/cadquery/occ_impl/geom.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/cadquery/occ_impl/importers/__init__.py` & `cadquery-2.3.1/cadquery/occ_impl/importers/__init__.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/cadquery/occ_impl/importers/dxf.py` & `cadquery-2.3.1/cadquery/occ_impl/importers/dxf.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/cadquery/occ_impl/jupyter_tools.py` & `cadquery-2.3.1/cadquery/occ_impl/jupyter_tools.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/cadquery/occ_impl/shapes.py` & `cadquery-2.3.1/cadquery/occ_impl/shapes.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/cadquery/occ_impl/sketch_solver.py` & `cadquery-2.3.1/cadquery/occ_impl/sketch_solver.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/cadquery/occ_impl/solver.py` & `cadquery-2.3.1/cadquery/occ_impl/solver.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/cadquery/plugins/__init__.py` & `cadquery-2.3.1/cadquery/plugins/__init__.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/cadquery/selectors.py` & `cadquery-2.3.1/cadquery/selectors.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/cadquery/sketch.py` & `cadquery-2.3.1/cadquery/sketch.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/cadquery/utils.py` & `cadquery-2.3.1/cadquery/utils.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/cadquery.egg-info/PKG-INFO` & `cadquery-2.3.1/cadquery.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: cadquery
-Version: 2.3.0
+Version: 2.3.1
 Summary: CadQuery is a parametric  scripting language for creating and traversing CAD models
 Home-page: https://github.com/CadQuery/cadquery
 Author: David Cowden
 Author-email: dave.cowden@gmail.com
 License: Apache Public License 2.0
 Platform: any
 Classifier: Development Status :: 5 - Production/Stable
```

### Comparing `cadquery-2.3.0/cadquery.egg-info/SOURCES.txt` & `cadquery-2.3.1/cadquery.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/changes.md` & `cadquery-2.3.1/changes.md`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,15 @@
 Changes
 =======
 
-2.3.0 (latest release)
+2.3.1 (latest release)
+
+This was an incremental release to fix a broken PyPI package.
+
+2.3.0
 ------
 
 ### Highlights
    * Explicit Python 3.11 support [#1247](https://github.com/CadQuery/cadquery/pull/1247) [#1280](https://github.com/CadQuery/cadquery/pull/1280)
 
  ### Experimental Features
    * Constraint-based sketches are still being worked on and improved, and are not production ready. There have been fixes, but multiple issues are still open including [#959](https://github.com/CadQuery/cadquery/issues/959), [#968](https://github.com/CadQuery/cadquery/issues/968) and [#960](https://github.com/CadQuery/cadquery/issues/960).
```

### Comparing `cadquery-2.3.0/conda/meta.yaml` & `cadquery-2.3.1/conda/meta.yaml`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/conda/web-installer/Readme.md` & `cadquery-2.3.1/conda/web-installer/Readme.md`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/conda/web-installer/build.py` & `cadquery-2.3.1/conda/web-installer/build.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/conda/web-installer/construct.yaml.jinja2` & `cadquery-2.3.1/conda/web-installer/construct.yaml.jinja2`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/ParametricPulley.PNG` & `cadquery-2.3.1/doc/_static/ParametricPulley.PNG`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/assy.png` & `cadquery-2.3.1/doc/_static/assy.png`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/block.png` & `cadquery-2.3.1/doc/_static/block.png`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/cadquery_cheatsheet.html` & `cadquery-2.3.1/doc/_static/cadquery_cheatsheet.html`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/door_assy.png` & `cadquery-2.3.1/doc/_static/door_assy.png`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/door_assy_freecad.png` & `cadquery-2.3.1/doc/_static/door_assy_freecad.png`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/hyOzd-cablefix.png` & `cadquery-2.3.1/doc/_static/hyOzd-cablefix.png`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/hyOzd-finished.jpg` & `cadquery-2.3.1/doc/_static/hyOzd-finished.jpg`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/importexport/box_custom_options.svg` & `cadquery-2.3.1/doc/_static/importexport/box_custom_options.svg`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/importexport/box_custom_options_perspective.svg` & `cadquery-2.3.1/doc/_static/importexport/box_custom_options_perspective.svg`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/importexport/box_default_options.svg` & `cadquery-2.3.1/doc/_static/importexport/box_default_options.svg`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/logo/Roboto_Font/LICENSE.txt` & `cadquery-2.3.1/doc/_static/logo/Roboto_Font/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/logo/Roboto_Font/Roboto-Bold.ttf` & `cadquery-2.3.1/doc/_static/logo/Roboto_Font/Roboto-Bold.ttf`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/logo/cadquery_logo_dark.svg` & `cadquery-2.3.1/doc/_static/logo/cadquery_logo_dark.svg`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/logo/cadquery_logo_dark_inkscape.svg` & `cadquery-2.3.1/doc/_static/logo/cadquery_logo_dark_inkscape.svg`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/logo/cadquery_logo_light.svg` & `cadquery-2.3.1/doc/_static/logo/cadquery_logo_light.svg`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/logo/cadquery_logo_light_inkscape.svg` & `cadquery-2.3.1/doc/_static/logo/cadquery_logo_light_inkscape.svg`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/new_badge.png` & `cadquery-2.3.1/doc/_static/new_badge.png`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/parametric-cup-screencap.PNG` & `cadquery-2.3.1/doc/_static/parametric-cup-screencap.PNG`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/parametric-pillowblock-screencap.png` & `cadquery-2.3.1/doc/_static/parametric-pillowblock-screencap.png`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/pillowblock.png` & `cadquery-2.3.1/doc/_static/pillowblock.png`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/quickstart/000.png` & `cadquery-2.3.1/doc/_static/quickstart/000.png`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/quickstart/001.png` & `cadquery-2.3.1/doc/_static/quickstart/001.png`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/quickstart/002.png` & `cadquery-2.3.1/doc/_static/quickstart/002.png`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/quickstart/003.png` & `cadquery-2.3.1/doc/_static/quickstart/003.png`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/quickstart/004.png` & `cadquery-2.3.1/doc/_static/quickstart/004.png`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/quickstart/005.png` & `cadquery-2.3.1/doc/_static/quickstart/005.png`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/quickstart-1.png` & `cadquery-2.3.1/doc/_static/quickstart-1.png`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/quickstart-2.png` & `cadquery-2.3.1/doc/_static/quickstart-2.png`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/quickstart-3.png` & `cadquery-2.3.1/doc/_static/quickstart-3.png`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/quickstart-4.png` & `cadquery-2.3.1/doc/_static/quickstart-4.png`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/quickstart-5.png` & `cadquery-2.3.1/doc/_static/quickstart-5.png`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/quickstart.png` & `cadquery-2.3.1/doc/_static/quickstart.png`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/simple_assy.png` & `cadquery-2.3.1/doc/_static/simple_assy.png`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/simpleblock.png` & `cadquery-2.3.1/doc/_static/simpleblock.png`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/_static/vtk.js` & `cadquery-2.3.1/doc/_static/vtk.js`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/apireference.rst` & `cadquery-2.3.1/doc/apireference.rst`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/assy.rst` & `cadquery-2.3.1/doc/assy.rst`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/classreference.rst` & `cadquery-2.3.1/doc/classreference.rst`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/conf.py` & `cadquery-2.3.1/doc/conf.py`

 * *Files 2% similar despite different names*

```diff
@@ -66,15 +66,15 @@
 # The version info for the project you're documenting, acts as replacement for
 # |version| and |release|, also used in various other places throughout the
 # built documents.
 #
 # The short X.Y version.
 version = "2.3"
 # The full version, including alpha/beta/rc tags.
-release = "2.3.0"
+release = "2.3.1"
 
 # The language for content autogenerated by Sphinx. Refer to documentation
 # for a list of supported languages.
 # language = None
 
 # There are two options for replacing |today|: either, you set today to some
 # non-false value, then it is used:
```

### Comparing `cadquery-2.3.0/doc/cqgi.rst` & `cadquery-2.3.1/doc/cqgi.rst`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/designprinciples.rst` & `cadquery-2.3.1/doc/designprinciples.rst`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/examples.rst` & `cadquery-2.3.1/doc/examples.rst`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/ext/sphinx_autodoc_multimethod.py` & `cadquery-2.3.1/doc/ext/sphinx_autodoc_multimethod.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/extending.rst` & `cadquery-2.3.1/doc/extending.rst`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/fileformat.rst` & `cadquery-2.3.1/doc/fileformat.rst`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/gen_colors.py` & `cadquery-2.3.1/doc/gen_colors.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/importexport.rst` & `cadquery-2.3.1/doc/importexport.rst`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/index.rst` & `cadquery-2.3.1/doc/index.rst`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/installation.rst` & `cadquery-2.3.1/doc/installation.rst`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/intro.rst` & `cadquery-2.3.1/doc/intro.rst`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/primer.rst` & `cadquery-2.3.1/doc/primer.rst`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/quickstart.rst` & `cadquery-2.3.1/doc/quickstart.rst`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/roadmap.rst` & `cadquery-2.3.1/doc/roadmap.rst`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/selectors.rst` & `cadquery-2.3.1/doc/selectors.rst`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/sketch.rst` & `cadquery-2.3.1/doc/sketch.rst`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/doc/vslot-2020_1.dxf` & `cadquery-2.3.1/doc/vslot-2020_1.dxf`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/examples/CQ examples.ipynb` & `cadquery-2.3.1/examples/CQ examples.ipynb`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/examples/Ex001_Simple_Block.py` & `cadquery-2.3.1/examples/Ex001_Simple_Block.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/examples/Ex002_Block_With_Bored_Center_Hole.py` & `cadquery-2.3.1/examples/Ex002_Block_With_Bored_Center_Hole.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/examples/Ex003_Pillow_Block_With_Counterbored_Holes.py` & `cadquery-2.3.1/examples/Ex003_Pillow_Block_With_Counterbored_Holes.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/examples/Ex004_Extruded_Cylindrical_Plate.py` & `cadquery-2.3.1/examples/Ex004_Extruded_Cylindrical_Plate.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/examples/Ex005_Extruded_Lines_and_Arcs.py` & `cadquery-2.3.1/examples/Ex005_Extruded_Lines_and_Arcs.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/examples/Ex006_Moving_the_Current_Working_Point.py` & `cadquery-2.3.1/examples/Ex006_Moving_the_Current_Working_Point.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/examples/Ex007_Using_Point_Lists.py` & `cadquery-2.3.1/examples/Ex007_Using_Point_Lists.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/examples/Ex008_Polygon_Creation.py` & `cadquery-2.3.1/examples/Ex008_Polygon_Creation.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/examples/Ex009_Polylines.py` & `cadquery-2.3.1/examples/Ex009_Polylines.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/examples/Ex010_Defining_an_Edge_with_a_Spline.py` & `cadquery-2.3.1/examples/Ex010_Defining_an_Edge_with_a_Spline.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/examples/Ex011_Mirroring_Symmetric_Geometry.py` & `cadquery-2.3.1/examples/Ex011_Mirroring_Symmetric_Geometry.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/examples/Ex012_Creating_Workplanes_on_Faces.py` & `cadquery-2.3.1/examples/Ex012_Creating_Workplanes_on_Faces.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/examples/Ex013_Locating_a_Workplane_on_a_Vertex.py` & `cadquery-2.3.1/examples/Ex013_Locating_a_Workplane_on_a_Vertex.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/examples/Ex014_Offset_Workplanes.py` & `cadquery-2.3.1/examples/Ex014_Offset_Workplanes.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/examples/Ex015_Rotated_Workplanes.py` & `cadquery-2.3.1/examples/Ex015_Rotated_Workplanes.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/examples/Ex016_Using_Construction_Geometry.py` & `cadquery-2.3.1/examples/Ex016_Using_Construction_Geometry.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/examples/Ex017_Shelling_to_Create_Thin_Features.py` & `cadquery-2.3.1/examples/Ex017_Shelling_to_Create_Thin_Features.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/examples/Ex018_Making_Lofts.py` & `cadquery-2.3.1/examples/Ex018_Making_Lofts.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/examples/Ex019_Counter_Sunk_Holes.py` & `cadquery-2.3.1/examples/Ex019_Counter_Sunk_Holes.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/examples/Ex020_Rounding_Corners_with_Fillets.py` & `cadquery-2.3.1/examples/Ex020_Rounding_Corners_with_Fillets.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/examples/Ex021_Splitting_an_Object.py` & `cadquery-2.3.1/examples/Ex021_Splitting_an_Object.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/examples/Ex022_Revolution.py` & `cadquery-2.3.1/examples/Ex022_Revolution.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/examples/Ex023_Sweep.py` & `cadquery-2.3.1/examples/Ex023_Sweep.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/examples/Ex024_Sweep_With_Multiple_Sections.py` & `cadquery-2.3.1/examples/Ex024_Sweep_With_Multiple_Sections.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/examples/Ex025_Swept_Helix.py` & `cadquery-2.3.1/examples/Ex025_Swept_Helix.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/examples/Ex026_Case_Seam_Lip.py` & `cadquery-2.3.1/examples/Ex026_Case_Seam_Lip.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/examples/Ex100_Lego_Brick.py` & `cadquery-2.3.1/examples/Ex100_Lego_Brick.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/examples/Ex101_InterpPlate.py` & `cadquery-2.3.1/examples/Ex101_InterpPlate.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/mypy.ini` & `cadquery-2.3.1/mypy.ini`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/setup.py` & `cadquery-2.3.1/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -35,15 +35,15 @@
         "casadi",
         "path",
     ]
 
 
 setup(
     name="cadquery",
-    version="2.3.0",  # Update this for the next release
+    version="2.3.1",  # Update this for the next release
     url="https://github.com/CadQuery/cadquery",
     license="Apache Public License 2.0",
     author="David Cowden",
     author_email="dave.cowden@gmail.com",
     description="CadQuery is a parametric  scripting language for creating and traversing CAD models",
     long_description=open("README.md").read(),
     long_description_content_type="text/markdown",
```

### Comparing `cadquery-2.3.0/tests/__init__.py` & `cadquery-2.3.1/tests/__init__.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/tests/naca.py` & `cadquery-2.3.1/tests/naca.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/tests/test_assembly.py` & `cadquery-2.3.1/tests/test_assembly.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/tests/test_cad_objects.py` & `cadquery-2.3.1/tests/test_cad_objects.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/tests/test_cadquery.py` & `cadquery-2.3.1/tests/test_cadquery.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/tests/test_cqgi.py` & `cadquery-2.3.1/tests/test_cqgi.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/tests/test_examples.py` & `cadquery-2.3.1/tests/test_examples.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/tests/test_exporters.py` & `cadquery-2.3.1/tests/test_exporters.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/tests/test_hull.py` & `cadquery-2.3.1/tests/test_hull.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/tests/test_importers.py` & `cadquery-2.3.1/tests/test_importers.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/tests/test_jupyter.py` & `cadquery-2.3.1/tests/test_jupyter.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/tests/test_selectors.py` & `cadquery-2.3.1/tests/test_selectors.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/tests/test_sketch.py` & `cadquery-2.3.1/tests/test_sketch.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/tests/test_utils.py` & `cadquery-2.3.1/tests/test_utils.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/tests/test_workplanes.py` & `cadquery-2.3.1/tests/test_workplanes.py`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/tests/testdata/1001.dxf` & `cadquery-2.3.1/tests/testdata/1001.dxf`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/tests/testdata/MC 12x31.dxf` & `cadquery-2.3.1/tests/testdata/MC 12x31.dxf`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/tests/testdata/OpenSans-Regular.ttf` & `cadquery-2.3.1/tests/testdata/OpenSans-Regular.ttf`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/tests/testdata/gear.dxf` & `cadquery-2.3.1/tests/testdata/gear.dxf`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/tests/testdata/genshi.dxf` & `cadquery-2.3.1/tests/testdata/genshi.dxf`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/tests/testdata/rational_spline.dxf` & `cadquery-2.3.1/tests/testdata/rational_spline.dxf`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/tests/testdata/red_cube_blue_cylinder.step` & `cadquery-2.3.1/tests/testdata/red_cube_blue_cylinder.step`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/tests/testdata/spline.dxf` & `cadquery-2.3.1/tests/testdata/spline.dxf`

 * *Files identical despite different names*

### Comparing `cadquery-2.3.0/tests/testdata/three_layers.dxf` & `cadquery-2.3.1/tests/testdata/three_layers.dxf`

 * *Files identical despite different names*


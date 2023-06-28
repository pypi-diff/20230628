# Comparing `tmp/shiny_mdc-1.5.3.tar.gz` & `tmp/shiny_mdc-1.6.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "shiny_mdc-1.5.3.tar", max compression
+gzip compressed data, was "shiny_mdc-1.6.0.tar", max compression
```

## Comparing `shiny_mdc-1.5.3.tar` & `shiny_mdc-1.6.0.tar`

### file list

```diff
@@ -1,64 +1,64 @@
--rw-r--r--   0        0        0     5704 2023-05-23 20:19:44.402311 shiny_mdc-1.5.3/CHANGELOG.md
--rw-r--r--   0        0        0     1082 2023-05-23 20:19:44.402311 shiny_mdc-1.5.3/LICENSE
--rw-r--r--   0        0        0       78 2023-05-23 20:19:44.402311 shiny_mdc-1.5.3/README.md
--rw-r--r--   0        0        0     2297 2023-05-23 20:20:04.330340 shiny_mdc-1.5.3/pyproject.toml
--rw-r--r--   0        0        0       34 2023-05-23 20:19:44.402311 shiny_mdc-1.5.3/shinymdc/__init__.py
--rw-r--r--   0        0        0     1061 2023-05-23 20:19:44.402311 shiny_mdc-1.5.3/shinymdc/_latexmk.py
--rw-r--r--   0        0        0     1867 2023-05-23 20:19:44.402311 shiny_mdc-1.5.3/shinymdc/_liquid.py
--rw-r--r--   0        0        0     4643 2023-05-23 20:19:44.402311 shiny_mdc-1.5.3/shinymdc/_pandoc.py
--rw-r--r--   0        0        0     5084 2023-05-23 20:19:44.402311 shiny_mdc-1.5.3/shinymdc/_templates.py
--rw-r--r--   0        0        0       64 2023-05-23 20:20:04.334340 shiny_mdc-1.5.3/shinymdc/_version.py
--rw-r--r--   0        0        0      410 2023-05-23 20:19:44.402311 shiny_mdc-1.5.3/shinymdc/resources/dynamic/addappendices.tex
--rw-r--r--   0        0        0      879 2023-05-23 20:19:44.402311 shiny_mdc-1.5.3/shinymdc/resources/dynamic/authsetup.tex
--rw-r--r--   0        0        0      316 2023-05-23 20:19:44.402311 shiny_mdc-1.5.3/shinymdc/resources/dynamic/authsetupshort.tex
--rw-r--r--   0        0        0      572 2023-05-23 20:19:44.402311 shiny_mdc-1.5.3/shinymdc/resources/dynamic/dblfloatsetup.tex
--rw-r--r--   0        0        0      491 2023-05-23 20:19:44.402311 shiny_mdc-1.5.3/shinymdc/resources/static/bibnonatsetup.tex
--rw-r--r--   0        0        0      324 2023-05-23 20:19:44.402311 shiny_mdc-1.5.3/shinymdc/resources/static/bibnosupersetup.tex
--rw-r--r--   0        0        0      745 2023-05-23 20:19:44.402311 shiny_mdc-1.5.3/shinymdc/resources/static/bibsupersetup.tex
--rw-r--r--   0        0        0     3359 2023-05-23 20:19:44.402311 shiny_mdc-1.5.3/shinymdc/resources/static/floatsetup.tex
--rw-r--r--   0        0        0    19901 2023-05-23 20:19:44.402311 shiny_mdc-1.5.3/shinymdc/resources/static/iccv/bibstyle.bst
--rw-r--r--   0        0        0     9433 2023-05-23 20:19:44.402311 shiny_mdc-1.5.3/shinymdc/resources/static/iccv/esopic.sty
--rw-r--r--   0        0        0     3869 2023-05-23 20:19:44.402311 shiny_mdc-1.5.3/shinymdc/resources/static/iccv/everyshi.sty
--rw-r--r--   0        0        0     8276 2023-05-23 20:19:44.406311 shiny_mdc-1.5.3/shinymdc/resources/static/iccv/iccv.sty
--rw-r--r--   0        0        0    26973 2023-05-23 20:19:44.406311 shiny_mdc-1.5.3/shinymdc/resources/static/iclr/bibstyle.bst
--rw-r--r--   0        0        0     9153 2023-05-23 20:19:44.406311 shiny_mdc-1.5.3/shinymdc/resources/static/iclr/iclr.sty
--rw-r--r--   0        0        0    12284 2023-05-23 20:19:44.406311 shiny_mdc-1.5.3/shinymdc/resources/static/iclr/mathcommands.tex
--rw-r--r--   0        0        0    27146 2023-05-23 20:19:44.406311 shiny_mdc-1.5.3/shinymdc/resources/static/icml/bibstyle.bst
--rw-r--r--   0        0        0    27887 2023-05-23 20:19:44.406311 shiny_mdc-1.5.3/shinymdc/resources/static/icml/icml.sty
--rw-r--r--   0        0        0      735 2023-05-23 20:19:44.406311 shiny_mdc-1.5.3/shinymdc/resources/static/mathsetup.tex
--rw-r--r--   0        0        0     1237 2023-05-23 20:19:44.406311 shiny_mdc-1.5.3/shinymdc/resources/static/miscsetup.tex
--rw-r--r--   0        0        0    11306 2023-05-23 20:19:44.406311 shiny_mdc-1.5.3/shinymdc/resources/static/neurips/neurips.sty
--rw-r--r--   0        0        0      406 2023-05-23 20:19:44.406311 shiny_mdc-1.5.3/shinymdc/resources/static/reqsetup.tex
--rw-r--r--   0        0        0    19438 2023-05-23 20:19:44.406311 shiny_mdc-1.5.3/shinymdc/shinymdc.py
--rw-r--r--   0        0        0      945 2023-05-23 20:19:44.406311 shiny_mdc-1.5.3/shinymdc/templates/basic.tex
--rw-r--r--   0        0        0     1302 2023-05-23 20:19:44.406311 shiny_mdc-1.5.3/shinymdc/templates/iccv.tex
--rw-r--r--   0        0        0     1423 2023-05-23 20:19:44.406311 shiny_mdc-1.5.3/shinymdc/templates/iclr.tex
--rw-r--r--   0        0        0     2170 2023-05-23 20:19:44.406311 shiny_mdc-1.5.3/shinymdc/templates/icml.tex
--rw-r--r--   0        0        0      916 2023-05-23 20:19:44.406311 shiny_mdc-1.5.3/shinymdc/templates/neurips.tex
--rw-r--r--   0        0        0     3064 2023-05-23 20:19:44.406311 shiny_mdc-1.5.3/shinymdc/templates/spacious.tex
--rw-r--r--   0        0        0      464 2023-05-23 20:19:44.406311 shiny_mdc-1.5.3/shinymdc/templates/standalone.tex
--rw-r--r--   0        0        0     2281 2023-05-23 20:19:44.406311 shiny_mdc-1.5.3/shinymdc/templates/stylish.tex
--rw-r--r--   0        0        0    15953 2023-05-23 20:19:44.406311 shiny_mdc-1.5.3/test/figures/anscombe.pdf
--rw-r--r--   0        0        0    40892 2023-05-23 20:19:44.406311 shiny_mdc-1.5.3/test/figures/densities.pdf
--rw-r--r--   0        0        0    10736 2023-05-23 20:19:44.406311 shiny_mdc-1.5.3/test/figures/diamonds.pdf
--rw-r--r--   0        0        0   197017 2023-05-23 20:19:44.406311 shiny_mdc-1.5.3/test/figures/gaussian2d.pdf
--rw-r--r--   0        0        0    28282 2023-05-23 20:19:44.406311 shiny_mdc-1.5.3/test/figures/lines.png
--rw-r--r--   0        0        0     2971 2023-05-23 20:19:44.406311 shiny_mdc-1.5.3/test/main.md
--rwxr-xr-x   0        0        0      315 2023-05-23 20:19:44.406311 shiny_mdc-1.5.3/test/make.sh
--rw-r--r--   0        0        0     1166 2023-05-23 20:19:44.406311 shiny_mdc-1.5.3/test/references.bib
--rw-r--r--   0        0        0   690901 2023-05-23 20:19:44.410311 shiny_mdc-1.5.3/test/samples/basic.pdf
--rw-r--r--   0        0        0   414185 2023-05-23 20:19:44.414311 shiny_mdc-1.5.3/test/samples/iccv.pdf
--rw-r--r--   0        0        0   407653 2023-05-23 20:19:44.414311 shiny_mdc-1.5.3/test/samples/iclr.pdf
--rw-r--r--   0        0        0   446740 2023-05-23 20:19:44.418311 shiny_mdc-1.5.3/test/samples/icml.pdf
--rw-r--r--   0        0        0   451322 2023-05-23 20:19:44.418311 shiny_mdc-1.5.3/test/samples/neurips.pdf
--rw-r--r--   0        0        0   600276 2023-05-23 20:19:44.422311 shiny_mdc-1.5.3/test/samples/spacious.pdf
--rw-r--r--   0        0        0   555527 2023-05-23 20:19:44.426311 shiny_mdc-1.5.3/test/samples/standalone.pdf
--rw-r--r--   0        0        0   425326 2023-05-23 20:19:44.426311 shiny_mdc-1.5.3/test/samples/stylish.pdf
--rw-r--r--   0        0        0     1535 2023-05-23 20:19:44.426311 shiny_mdc-1.5.3/test/sections/appendix1.md
--rw-r--r--   0        0        0     1624 2023-05-23 20:19:44.426311 shiny_mdc-1.5.3/test/sections/appendix2.md
--rw-r--r--   0        0        0        0 2023-05-23 20:19:44.426311 shiny_mdc-1.5.3/test/sections/empty.md
--rw-r--r--   0        0        0     2326 2023-05-23 20:19:44.426311 shiny_mdc-1.5.3/test/sections/main1.md
--rw-r--r--   0        0        0     1351 2023-05-23 20:19:44.426311 shiny_mdc-1.5.3/test/sections/main2.md
--rw-r--r--   0        0        0      992 2023-05-23 20:19:44.426311 shiny_mdc-1.5.3/test/utils/commands.md
--rw-r--r--   0        0        0       41 2023-05-23 20:19:44.426311 shiny_mdc-1.5.3/test/utils/ext.md
--rw-r--r--   0        0        0     1008 1970-01-01 00:00:00.000000 shiny_mdc-1.5.3/PKG-INFO
+-rw-r--r--   0        0        0     6737 2023-06-28 15:49:22.555811 shiny_mdc-1.6.0/CHANGELOG.md
+-rw-r--r--   0        0        0     1082 2023-06-28 15:49:22.555811 shiny_mdc-1.6.0/LICENSE
+-rw-r--r--   0        0        0       78 2023-06-28 15:49:22.555811 shiny_mdc-1.6.0/README.md
+-rw-r--r--   0        0        0     2297 2023-06-28 15:49:42.927765 shiny_mdc-1.6.0/pyproject.toml
+-rw-r--r--   0        0        0       34 2023-06-28 15:49:22.555811 shiny_mdc-1.6.0/shinymdc/__init__.py
+-rw-r--r--   0        0        0     1061 2023-06-28 15:49:22.555811 shiny_mdc-1.6.0/shinymdc/_latexmk.py
+-rw-r--r--   0        0        0     1867 2023-06-28 15:49:22.555811 shiny_mdc-1.6.0/shinymdc/_liquid.py
+-rw-r--r--   0        0        0     4782 2023-06-28 15:49:22.555811 shiny_mdc-1.6.0/shinymdc/_pandoc.py
+-rw-r--r--   0        0        0     5084 2023-06-28 15:49:22.555811 shiny_mdc-1.6.0/shinymdc/_templates.py
+-rw-r--r--   0        0        0       64 2023-06-28 15:49:42.927765 shiny_mdc-1.6.0/shinymdc/_version.py
+-rw-r--r--   0        0        0      410 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/shinymdc/resources/dynamic/addappendices.tex
+-rw-r--r--   0        0        0      879 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/shinymdc/resources/dynamic/authsetup.tex
+-rw-r--r--   0        0        0      316 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/shinymdc/resources/dynamic/authsetupshort.tex
+-rw-r--r--   0        0        0      572 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/shinymdc/resources/dynamic/dblfloatsetup.tex
+-rw-r--r--   0        0        0      491 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/shinymdc/resources/static/bibnonatsetup.tex
+-rw-r--r--   0        0        0      324 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/shinymdc/resources/static/bibnosupersetup.tex
+-rw-r--r--   0        0        0      745 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/shinymdc/resources/static/bibsupersetup.tex
+-rw-r--r--   0        0        0     3266 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/shinymdc/resources/static/floatsetup.tex
+-rw-r--r--   0        0        0    19901 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/shinymdc/resources/static/iccv/bibstyle.bst
+-rw-r--r--   0        0        0     9433 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/shinymdc/resources/static/iccv/esopic.sty
+-rw-r--r--   0        0        0     3869 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/shinymdc/resources/static/iccv/everyshi.sty
+-rw-r--r--   0        0        0     8276 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/shinymdc/resources/static/iccv/iccv.sty
+-rw-r--r--   0        0        0    26973 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/shinymdc/resources/static/iclr/bibstyle.bst
+-rw-r--r--   0        0        0     9153 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/shinymdc/resources/static/iclr/iclr.sty
+-rw-r--r--   0        0        0    12284 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/shinymdc/resources/static/iclr/mathcommands.tex
+-rw-r--r--   0        0        0    27146 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/shinymdc/resources/static/icml/bibstyle.bst
+-rw-r--r--   0        0        0    27887 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/shinymdc/resources/static/icml/icml.sty
+-rw-r--r--   0        0        0      735 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/shinymdc/resources/static/mathsetup.tex
+-rw-r--r--   0        0        0     1202 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/shinymdc/resources/static/miscsetup.tex
+-rw-r--r--   0        0        0    11306 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/shinymdc/resources/static/neurips/neurips.sty
+-rw-r--r--   0        0        0      503 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/shinymdc/resources/static/reqsetup.tex
+-rw-r--r--   0        0        0    19497 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/shinymdc/shinymdc.py
+-rw-r--r--   0        0        0      945 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/shinymdc/templates/basic.tex
+-rw-r--r--   0        0        0     1302 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/shinymdc/templates/iccv.tex
+-rw-r--r--   0        0        0     1423 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/shinymdc/templates/iclr.tex
+-rw-r--r--   0        0        0     2170 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/shinymdc/templates/icml.tex
+-rw-r--r--   0        0        0      916 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/shinymdc/templates/neurips.tex
+-rw-r--r--   0        0        0     3064 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/shinymdc/templates/spacious.tex
+-rw-r--r--   0        0        0      464 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/shinymdc/templates/standalone.tex
+-rw-r--r--   0        0        0     2411 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/shinymdc/templates/stylish.tex
+-rw-r--r--   0        0        0    15953 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/test/figures/anscombe.pdf
+-rw-r--r--   0        0        0    40892 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/test/figures/densities.pdf
+-rw-r--r--   0        0        0    10736 2023-06-28 15:49:22.559811 shiny_mdc-1.6.0/test/figures/diamonds.pdf
+-rw-r--r--   0        0        0   197017 2023-06-28 15:49:22.563811 shiny_mdc-1.6.0/test/figures/gaussian2d.pdf
+-rw-r--r--   0        0        0    28282 2023-06-28 15:49:22.563811 shiny_mdc-1.6.0/test/figures/lines.png
+-rw-r--r--   0        0        0     2971 2023-06-28 15:49:22.563811 shiny_mdc-1.6.0/test/main.md
+-rwxr-xr-x   0        0        0      315 2023-06-28 15:49:22.563811 shiny_mdc-1.6.0/test/make.sh
+-rw-r--r--   0        0        0     1166 2023-06-28 15:49:22.563811 shiny_mdc-1.6.0/test/references.bib
+-rw-r--r--   0        0        0   690901 2023-06-28 15:49:22.563811 shiny_mdc-1.6.0/test/samples/basic.pdf
+-rw-r--r--   0        0        0   414185 2023-06-28 15:49:22.567811 shiny_mdc-1.6.0/test/samples/iccv.pdf
+-rw-r--r--   0        0        0   407653 2023-06-28 15:49:22.567811 shiny_mdc-1.6.0/test/samples/iclr.pdf
+-rw-r--r--   0        0        0   446740 2023-06-28 15:49:22.571811 shiny_mdc-1.6.0/test/samples/icml.pdf
+-rw-r--r--   0        0        0   451322 2023-06-28 15:49:22.575811 shiny_mdc-1.6.0/test/samples/neurips.pdf
+-rw-r--r--   0        0        0   600276 2023-06-28 15:49:22.575811 shiny_mdc-1.6.0/test/samples/spacious.pdf
+-rw-r--r--   0        0        0   555527 2023-06-28 15:49:22.579811 shiny_mdc-1.6.0/test/samples/standalone.pdf
+-rw-r--r--   0        0        0   425326 2023-06-28 15:49:22.579811 shiny_mdc-1.6.0/test/samples/stylish.pdf
+-rw-r--r--   0        0        0     1535 2023-06-28 15:49:22.579811 shiny_mdc-1.6.0/test/sections/appendix1.md
+-rw-r--r--   0        0        0     1624 2023-06-28 15:49:22.579811 shiny_mdc-1.6.0/test/sections/appendix2.md
+-rw-r--r--   0        0        0        0 2023-06-28 15:49:22.579811 shiny_mdc-1.6.0/test/sections/empty.md
+-rw-r--r--   0        0        0     2326 2023-06-28 15:49:22.579811 shiny_mdc-1.6.0/test/sections/main1.md
+-rw-r--r--   0        0        0     1351 2023-06-28 15:49:22.579811 shiny_mdc-1.6.0/test/sections/main2.md
+-rw-r--r--   0        0        0      992 2023-06-28 15:49:22.579811 shiny_mdc-1.6.0/test/utils/commands.md
+-rw-r--r--   0        0        0       41 2023-06-28 15:49:22.579811 shiny_mdc-1.6.0/test/utils/ext.md
+-rw-r--r--   0        0        0     1008 1970-01-01 00:00:00.000000 shiny_mdc-1.6.0/PKG-INFO
```

### Comparing `shiny_mdc-1.5.3/CHANGELOG.md` & `shiny_mdc-1.6.0/CHANGELOG.md`

 * *Files 6% similar despite different names*

```diff
@@ -1,11 +1,27 @@
 # Changelog
 
 All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.
 
+## [1.6.0](https://github.com/jayanthkoushik/shiny-mdc/compare/v1.5.3...v1.6.0) (2023-06-28)
+
+
+### Features
+
+* increase float counters in `dblfloatsetup` ([a349e2f](https://github.com/jayanthkoushik/shiny-mdc/commit/a349e2f8c4843a557c4d3d83d15244a51b7feaae))
+* move pgf/tikz/svg packages to `reqsetup` ([a8dbf83](https://github.com/jayanthkoushik/shiny-mdc/commit/a8dbf8325b9e3a8101b9e1a780637a63042c8acb))
+* remove default value for `default_img_ext` parameter ([22b1baa](https://github.com/jayanthkoushik/shiny-mdc/commit/22b1baa38947179722fddf7b2f58c7a947b75416))
+* remove redundancy from captions ([43dbe87](https://github.com/jayanthkoushik/shiny-mdc/commit/43dbe876a8152d576f50c816d24913b43b9be0af))
+* use `newtxmath` in `stylish` template ([a3a0b6b](https://github.com/jayanthkoushik/shiny-mdc/commit/a3a0b6baea57f0985cb77f6762317508dcc2532f))
+
+
+### Bug Fixes
+
+* remove default placement settings for figures and tables ([5a6300c](https://github.com/jayanthkoushik/shiny-mdc/commit/5a6300cb32aa0de000d0abe27632d2dc8480cc74))
+
 ### [1.5.3](https://github.com/jayanthkoushik/shiny-mdc/compare/v1.5.2...v1.5.3) (2023-05-23)
 
 
 ### Bug Fixes
 
 * handle header being absent ([dfc1173](https://github.com/jayanthkoushik/shiny-mdc/commit/dfc1173e2b250c61db50a2815dd8a95760f15745))
```

### Comparing `shiny_mdc-1.5.3/LICENSE` & `shiny_mdc-1.6.0/LICENSE`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/pyproject.toml` & `shiny_mdc-1.6.0/pyproject.toml`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "shiny-mdc"
-version = "1.5.3"  # managed by `poetry-dynamic-versioning`
+version = "1.6.0"  # managed by `poetry-dynamic-versioning`
 description = "Tool to compile markdown files to tex/pdf using pandoc, latexmk"
 readme = "README.md"
 authors = ["Jayanth Koushik <mail@jkoushik.me>"]
 license = "MIT"
 repository = "https://github.com/jayanthkoushik/shinymdc"
 packages = [
   { include = "shinymdc" }
```

### Comparing `shiny_mdc-1.5.3/shinymdc/_latexmk.py` & `shiny_mdc-1.6.0/shinymdc/_latexmk.py`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/shinymdc/_liquid.py` & `shiny_mdc-1.6.0/shinymdc/_liquid.py`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/shinymdc/_pandoc.py` & `shiny_mdc-1.6.0/shinymdc/_pandoc.py`

 * *Files 3% similar despite different names*

```diff
@@ -134,14 +134,16 @@
 
         # First extract the subfloats. Each subfloat is on a single line.
         subfloats = re.findall(r"\\subfloat.*\n", match_str)
         # Remove the subfloats from the match string.
         match_str = re.sub(r"\\subfloat.*\n", "", match_str)
         # Clean up the match string.
         match_str = match_str.strip().replace("\n\n", "\n")
+        # Change '\caption[x]{x}' to '\caption{x}'.
+        match_str = re.sub(r"\\caption(\[.*\])?\{(.*)\}", r"\\caption{\2}", match_str)
 
         # Add '\quad' between the subfloats.
         subfloats = "\\quad\n".join(subfloats)
         # Wrap the subfloats and the rest of the figure in a 'figure' environment.
         return "\\begin{figure}\n" + subfloats + match_str + "\n\\end{figure}"
 
     _env = "pandoccrossrefsubfigures"
```

### Comparing `shiny_mdc-1.5.3/shinymdc/_templates.py` & `shiny_mdc-1.6.0/shinymdc/_templates.py`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/shinymdc/resources/dynamic/authsetup.tex` & `shiny_mdc-1.6.0/shinymdc/resources/dynamic/authsetup.tex`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/shinymdc/resources/dynamic/dblfloatsetup.tex` & `shiny_mdc-1.6.0/shinymdc/resources/dynamic/dblfloatsetup.tex`

 * *Files 2% similar despite different names*

```diff
@@ -1,19 +1,19 @@
 $if(nonidan)$
 \usepackage{stfloats}
 $else$
 \usepackage{nidanfloat}
 \renewcommand{\dblbotfraction}{0.8}
 $endif$
 
-\setcounter{topnumber}{1}
+\setcounter{topnumber}{4}
 \setcounter{dbltopnumber}{2}
-\setcounter{bottomnumber}{1}
-\setcounter{dblbotnumber}{1}
-\setcounter{totalnumber}{4}
+\setcounter{bottomnumber}{4}
+\setcounter{dblbotnumber}{2}
+\setcounter{totalnumber}{8}
 
 \renewcommand{\topfraction}{0.85}
 \renewcommand{\dbltopfraction}{0.8}
 \renewcommand{\bottomfraction}{0.85}
 \renewcommand{\textfraction}{0.15}
 \renewcommand{\floatpagefraction}{0.85}
 \renewcommand{\dblfloatpagefraction}{0.8}
```

### Comparing `shiny_mdc-1.5.3/shinymdc/resources/static/bibsupersetup.tex` & `shiny_mdc-1.6.0/shinymdc/resources/static/bibsupersetup.tex`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/shinymdc/resources/static/floatsetup.tex` & `shiny_mdc-1.6.0/shinymdc/resources/static/floatsetup.tex`

 * *Files 8% similar despite different names*

```diff
@@ -16,19 +16,14 @@
 \setlength{\intextsep}{2em plus 1ex minus 1ex}
 
 \makeatletter
 \setlength{\@fptop}{0pt}
 \setlength{\@fpbot}{0pt plus 1fil}
 \makeatother
 
-\makeatletter
-\def\fps@figure{htbp}
-\def\fps@table{htbp}
-\makeatother
-
 % Maximum width/height for figures and tables.
 \newcommand{\maxfigwidth}{\textwidth}
 \newcommand{\maxfigheight}{\textheight}
 \newcommand{\maxtabwidth}{\textwidth}
 \newcommand{\maxtabheight}{\textheight}
 
 % Maintain aspect ratio of figures.
@@ -73,17 +68,17 @@
 
   \let\setcaptionsubtype\oldsetcaptionsubtype
 
   % Save the linewidth to a constant (the macro will change depending on environment).
   \xdef\thelinew{\the\linewidth}
 
   \ifdim\wd0>\thelinew
-    \begin{figure*}[tbp]
+    \begin{figure*}
   \else
-    \begin{oldfigure}[htbp]
+    \begin{oldfigure}
   \fi
 
       \setlength{\FrameRule}{0pt}
       \setlength{\FrameSep}{0pt}
 
       \begin{framed}
       \begin{adjustbox}{center}
@@ -118,17 +113,17 @@
   \renewcommand{\caption}[2][]{\global\def\mdccap{##2}}
 
   \sbox{0}{\BODY}
 
   \xdef\thelinew{\the\linewidth}
 
   \ifdim\wd0>\thelinew
-    \begin{table*}[tbp]
+    \begin{table*}
   \else
-    \begin{oldtable}[htbp]
+    \begin{oldtable}
   \fi
 
       \begin{adjustbox}{center}
         \maxsizebox{\maxtabwidth}{\maxtabheight}{\BODY}
       \end{adjustbox}
 
       \oldcaption{\mdccap}
```

### Comparing `shiny_mdc-1.5.3/shinymdc/resources/static/iccv/bibstyle.bst` & `shiny_mdc-1.6.0/shinymdc/resources/static/iccv/bibstyle.bst`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/shinymdc/resources/static/iccv/esopic.sty` & `shiny_mdc-1.6.0/shinymdc/resources/static/iccv/esopic.sty`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/shinymdc/resources/static/iccv/everyshi.sty` & `shiny_mdc-1.6.0/shinymdc/resources/static/iccv/everyshi.sty`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/shinymdc/resources/static/iccv/iccv.sty` & `shiny_mdc-1.6.0/shinymdc/resources/static/iccv/iccv.sty`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/shinymdc/resources/static/iclr/bibstyle.bst` & `shiny_mdc-1.6.0/shinymdc/resources/static/iclr/bibstyle.bst`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/shinymdc/resources/static/iclr/iclr.sty` & `shiny_mdc-1.6.0/shinymdc/resources/static/iclr/iclr.sty`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/shinymdc/resources/static/iclr/mathcommands.tex` & `shiny_mdc-1.6.0/shinymdc/resources/static/iclr/mathcommands.tex`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/shinymdc/resources/static/icml/bibstyle.bst` & `shiny_mdc-1.6.0/shinymdc/resources/static/icml/bibstyle.bst`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/shinymdc/resources/static/icml/icml.sty` & `shiny_mdc-1.6.0/shinymdc/resources/static/icml/icml.sty`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/shinymdc/resources/static/mathsetup.tex` & `shiny_mdc-1.6.0/shinymdc/resources/static/mathsetup.tex`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/shinymdc/resources/static/miscsetup.tex` & `shiny_mdc-1.6.0/shinymdc/resources/static/miscsetup.tex`

 * *Files 4% similar despite different names*

```diff
@@ -3,17 +3,15 @@
 \usepackage{babel}
 \usepackage[title]{appendix}
 \usepackage[bottom]{footmisc}
 \usepackage{footnote}
 \usepackage{acronym}
 \usepackage{relsize}
 \usepackage{xcolor}
-\usepackage{tikz}
 \usepackage{fancyvrb}
-\usepackage{pgf}
 \usepackage{nowidow}
 
 % Handle footnotes inside tables, figures.
 \makesavenoteenv{table}
 \makesavenoteenv{table*}
 \makesavenoteenv{figure}
 \makesavenoteenv{figure*}
```

### Comparing `shiny_mdc-1.5.3/shinymdc/resources/static/neurips/neurips.sty` & `shiny_mdc-1.6.0/shinymdc/resources/static/neurips/neurips.sty`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/shinymdc/shinymdc.py` & `shiny_mdc-1.6.0/shinymdc/shinymdc.py`

 * *Files 1% similar despite different names*

```diff
@@ -51,17 +51,17 @@
     meta: NotRequired[
         Annotated[
             KeyValuePairs,
             "extra metadata to update the document metadata with",
             ["-m", "--meta"],
         ]
     ]
-    default_img_ext: Annotated[
-        str, "default image extension", ["-x", "--default-img-ext"]
-    ] = "pdf"
+    default_img_ext: NotRequired[
+        Annotated[str, "default image extension", ["-x", "--default-img-ext"]]
+    ]
     natbib: Annotated[bool, "whether to use 'natbib' for bibliography"] = True
 
     build_dir: Annotated[
         Path,
         "directory for storing intermediate files and dependencies",
         ["-d", "--build-dir"],
     ] = Path(".shinymdc")
@@ -326,15 +326,15 @@
             stub_template_path = Path(stub_template_file.name)
             stub_template_path.write_text("$body$")
             combined_tex = run_pandoc(
                 combined_liquified_md_path,
                 stub_template_path,
                 bib_path,
                 None,  # metadata_path
-                self.default_img_ext,
+                getattr(self, "default_img_ext", None),
                 self.natbib,
                 hasattr(self, "verbose"),
                 **self.meta,
             )
 
         # Split compiled latex into constituent parts.
         parts = combined_tex.split(primary_sep.strip())
@@ -429,15 +429,15 @@
             # Process dynamic resources with pandoc.
             for resc_name, resc_path in dynamic_resc_paths.items():
                 processed_resc_tex = run_pandoc(
                     Path(os.devnull),
                     resc_path,
                     bib_path,
                     metadata_path,
-                    self.default_img_ext,
+                    getattr(self, "default_img_ext", None),
                     self.natbib,
                     hasattr(self, "verbose"),
                     **self.meta,
                 )
                 processed_resc_path = rescs_dir / f"{resc_name}{resc_path.suffix}"
                 print(f"+ write '{processed_resc_path}'", file=sys.stderr)
                 processed_resc_path.write_text(processed_resc_tex)
@@ -449,15 +449,15 @@
 
             # Process main tex with pandoc.
             main_tex = run_pandoc(
                 Path(os.devnull),
                 template_path,
                 bib_path,
                 metadata_path,
-                self.default_img_ext,
+                getattr(self, "default_img_ext", None),
                 self.natbib,
                 hasattr(self, "verbose"),
                 **self.meta,
             )
 
         # Write main tex to file.
         print(f"+ write '{self.main_tex_path}'", file=sys.stderr)
```

### Comparing `shiny_mdc-1.5.3/shinymdc/templates/basic.tex` & `shiny_mdc-1.6.0/shinymdc/templates/basic.tex`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/shinymdc/templates/iccv.tex` & `shiny_mdc-1.6.0/shinymdc/templates/iccv.tex`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/shinymdc/templates/iclr.tex` & `shiny_mdc-1.6.0/shinymdc/templates/iclr.tex`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/shinymdc/templates/icml.tex` & `shiny_mdc-1.6.0/shinymdc/templates/icml.tex`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/shinymdc/templates/neurips.tex` & `shiny_mdc-1.6.0/shinymdc/templates/neurips.tex`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/shinymdc/templates/spacious.tex` & `shiny_mdc-1.6.0/shinymdc/templates/spacious.tex`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/shinymdc/templates/stylish.tex` & `shiny_mdc-1.6.0/shinymdc/templates/stylish.tex`

 * *Files 14% similar despite different names*

```diff
@@ -1,7 +1,9 @@
+\RequirePackage{amssymb}
+\RequirePackage{amsthm}
 \PassOptionsToPackage{hidelinks}{hyperref}
 
 \documentclass[%
   letterpaper,%
   twocolumn,%
   $if(lang)$$lang$$else$english$endif$%
 ]{article}
@@ -11,15 +13,15 @@
   textheight=624pt,%
   columnsep=12pt,%
   footskip=50pt,%
   footnotesep=50pt%
 ]{geometry}
 \usepackage[sf,big,raggedright,compact]{titlesec}
 \usepackage{fancyhdr}
-\usepackage{newtxtext}
+\usepackage{newtx}
 \usepackage{etoolbox}
 
 \def\nobibcompress{TRUE}
 \input{$reqsetup$}
 \input{$floatsetup$}
 \input{$dblfloatsetup$}
 \input{$mathsetup$}
@@ -28,14 +30,17 @@
 
 $if(smalltabs)$
 % Use small font for tables.
 \AtBeginEnvironment{tabular}{\smaller}
 $else$
 $endif$
 
+% Don't use smallcaps for acronyms.
+\renewcommand*{\acsfont}[1]{{\textsmaller{#1}}}
+
 % Configure caption font.
 \captionsetup{justification=raggedright,font={sf,small}}
 
 % Add periods after section numbers.
 \titlelabel{\thetitle.\enskip}
 
 % Configure page no.
```

### Comparing `shiny_mdc-1.5.3/test/figures/anscombe.pdf` & `shiny_mdc-1.6.0/test/figures/anscombe.pdf`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/test/figures/densities.pdf` & `shiny_mdc-1.6.0/test/figures/densities.pdf`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/test/figures/diamonds.pdf` & `shiny_mdc-1.6.0/test/figures/diamonds.pdf`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/test/figures/gaussian2d.pdf` & `shiny_mdc-1.6.0/test/figures/gaussian2d.pdf`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/test/figures/lines.png` & `shiny_mdc-1.6.0/test/figures/lines.png`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/test/main.md` & `shiny_mdc-1.6.0/test/main.md`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/test/references.bib` & `shiny_mdc-1.6.0/test/references.bib`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/test/samples/basic.pdf` & `shiny_mdc-1.6.0/test/samples/basic.pdf`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/test/samples/iccv.pdf` & `shiny_mdc-1.6.0/test/samples/iccv.pdf`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/test/samples/iclr.pdf` & `shiny_mdc-1.6.0/test/samples/iclr.pdf`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/test/samples/icml.pdf` & `shiny_mdc-1.6.0/test/samples/icml.pdf`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/test/samples/neurips.pdf` & `shiny_mdc-1.6.0/test/samples/neurips.pdf`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/test/samples/spacious.pdf` & `shiny_mdc-1.6.0/test/samples/spacious.pdf`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/test/samples/standalone.pdf` & `shiny_mdc-1.6.0/test/samples/standalone.pdf`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/test/samples/stylish.pdf` & `shiny_mdc-1.6.0/test/samples/stylish.pdf`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/test/sections/appendix1.md` & `shiny_mdc-1.6.0/test/sections/appendix1.md`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/test/sections/appendix2.md` & `shiny_mdc-1.6.0/test/sections/appendix2.md`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/test/sections/main1.md` & `shiny_mdc-1.6.0/test/sections/main1.md`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/test/sections/main2.md` & `shiny_mdc-1.6.0/test/sections/main2.md`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/test/utils/commands.md` & `shiny_mdc-1.6.0/test/utils/commands.md`

 * *Files identical despite different names*

### Comparing `shiny_mdc-1.5.3/PKG-INFO` & `shiny_mdc-1.6.0/PKG-INFO`

 * *Files 16% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: shiny-mdc
-Version: 1.5.3
+Version: 1.6.0
 Summary: Tool to compile markdown files to tex/pdf using pandoc, latexmk
 Home-page: https://github.com/jayanthkoushik/shinymdc
 License: MIT
 Author: Jayanth Koushik
 Author-email: mail@jkoushik.me
 Requires-Python: >=3.9,<4.0
 Classifier: Development Status :: 4 - Beta
```


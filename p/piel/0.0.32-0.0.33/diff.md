# Comparing `tmp/piel-0.0.32.tar.gz` & `tmp/piel-0.0.33.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "piel-0.0.32.tar", last modified: Tue Jun 27 21:04:44 2023, max compression
+gzip compressed data, was "piel-0.0.33.tar", last modified: Wed Jun 28 09:50:33 2023, max compression
```

## Comparing `piel-0.0.32.tar` & `piel-0.0.33.tar`

### file list

```diff
@@ -1,266 +1,139 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.256233 piel-0.0.32/
--rw-r--r--   0 runner    (1001) docker     (123)     3478 2023-06-27 21:04:28.000000 piel-0.0.32/CONTRIBUTING.rst
--rw-r--r--   0 runner    (1001) docker     (123)     1073 2023-06-27 21:04:28.000000 piel-0.0.32/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)      262 2023-06-27 21:04:28.000000 piel-0.0.32/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)     3210 2023-06-27 21:04:44.256233 piel-0.0.32/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2385 2023-06-27 21:04:28.000000 piel-0.0.32/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.240233 piel-0.0.32/docs/
--rw-r--r--   0 runner    (1001) docker     (123)      605 2023-06-27 21:04:28.000000 piel-0.0.32/docs/Makefile
--rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-27 21:04:28.000000 piel-0.0.32/docs/authors.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.240233 piel-0.0.32/docs/autoapi/
--rw-r--r--   0 runner    (1001) docker     (123)      241 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.240233 piel-0.0.32/docs/autoapi/piel/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.240233 piel-0.0.32/docs/autoapi/piel/cli/
--rw-r--r--   0 runner    (1001) docker     (123)      282 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/cli/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.240233 piel-0.0.32/docs/autoapi/piel/cocotb/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.240233 piel-0.0.32/docs/autoapi/piel/cocotb/core/
--rw-r--r--   0 runner    (1001) docker     (123)     3925 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/cocotb/core/index.rst
--rw-r--r--   0 runner    (1001) docker     (123)     2936 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/cocotb/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.240233 piel-0.0.32/docs/autoapi/piel/components/
--rw-r--r--   0 runner    (1001) docker     (123)       84 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/components/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.240233 piel-0.0.32/docs/autoapi/piel/config/
--rw-r--r--   0 runner    (1001) docker     (123)      277 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/config/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.240233 piel-0.0.32/docs/autoapi/piel/defaults/
--rw-r--r--   0 runner    (1001) docker     (123)      216 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/defaults/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.240233 piel-0.0.32/docs/autoapi/piel/file_system/
--rw-r--r--   0 runner    (1001) docker     (123)     5117 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/file_system/index.rst
--rw-r--r--   0 runner    (1001) docker     (123)    29073 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.240233 piel-0.0.32/docs/autoapi/piel/integration/
--rw-r--r--   0 runner    (1001) docker     (123)     1447 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/integration/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.240233 piel-0.0.32/docs/autoapi/piel/integration/openlane_gdsfactory_core/
--rw-r--r--   0 runner    (1001) docker     (123)     1694 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/integration/openlane_gdsfactory_core/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.240233 piel-0.0.32/docs/autoapi/piel/integration/sax_cocotb/
--rw-r--r--   0 runner    (1001) docker     (123)      120 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/integration/sax_cocotb/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.240233 piel-0.0.32/docs/autoapi/piel/models/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.240233 piel-0.0.32/docs/autoapi/piel/models/frequency/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.240233 piel-0.0.32/docs/autoapi/piel/models/frequency/electrical/
--rw-r--r--   0 runner    (1001) docker     (123)      135 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/frequency/electrical/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.240233 piel-0.0.32/docs/autoapi/piel/models/frequency/electro_optic/
--rw-r--r--   0 runner    (1001) docker     (123)      144 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/frequency/electro_optic/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/frequency/electronic/
--rw-r--r--   0 runner    (1001) docker     (123)      135 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/frequency/electronic/index.rst
--rw-r--r--   0 runner    (1001) docker     (123)      300 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/frequency/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/frequency/opto_electronic/
--rw-r--r--   0 runner    (1001) docker     (123)      150 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/frequency/opto_electronic/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/frequency/photonic/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/frequency/photonic/coupler_simple/
--rw-r--r--   0 runner    (1001) docker     (123)      351 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/frequency/photonic/coupler_simple/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/frequency/photonic/directional_coupler_length/
--rw-r--r--   0 runner    (1001) docker     (123)      511 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/frequency/photonic/directional_coupler_length/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/frequency/photonic/directional_coupler_real/
--rw-r--r--   0 runner    (1001) docker     (123)      204 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/frequency/photonic/directional_coupler_real/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/frequency/photonic/directional_coupler_simple/
--rw-r--r--   0 runner    (1001) docker     (123)      423 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/frequency/photonic/directional_coupler_simple/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/frequency/photonic/grating_coupler/
--rw-r--r--   0 runner    (1001) docker     (123)      415 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/frequency/photonic/grating_coupler/index.rst
--rw-r--r--   0 runner    (1001) docker     (123)      446 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/frequency/photonic/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/frequency/photonic/mmi1x2/
--rw-r--r--   0 runner    (1001) docker     (123)      317 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/frequency/photonic/mmi1x2/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/frequency/photonic/mmi2x2/
--rw-r--r--   0 runner    (1001) docker     (123)      317 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/frequency/photonic/mmi2x2/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/frequency/photonic/straight_waveguide/
--rw-r--r--   0 runner    (1001) docker     (123)      418 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/frequency/photonic/straight_waveguide/index.rst
--rw-r--r--   0 runner    (1001) docker     (123)      320 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/logic/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/logic/electrical/
--rw-r--r--   0 runner    (1001) docker     (123)      123 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/logic/electrical/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/logic/electro_optic/
--rw-r--r--   0 runner    (1001) docker     (123)      132 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/logic/electro_optic/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/logic/electronic/
--rw-r--r--   0 runner    (1001) docker     (123)      123 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/logic/electronic/index.rst
--rw-r--r--   0 runner    (1001) docker     (123)      288 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/logic/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/logic/opto_electronic/
--rw-r--r--   0 runner    (1001) docker     (123)      138 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/logic/opto_electronic/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/logic/photonic/
--rw-r--r--   0 runner    (1001) docker     (123)      117 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/logic/photonic/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/physical/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/physical/electrical/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/physical/electrical/cable/
--rw-r--r--   0 runner    (1001) docker     (123)      150 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/physical/electrical/cable/index.rst
--rw-r--r--   0 runner    (1001) docker     (123)      221 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/physical/electrical/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/physical/electro_optic/
--rw-r--r--   0 runner    (1001) docker     (123)      141 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/physical/electro_optic/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/physical/electronic/
--rw-r--r--   0 runner    (1001) docker     (123)      132 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/physical/electronic/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/physical/geometry/
--rw-r--r--   0 runner    (1001) docker     (123)      579 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/physical/geometry/index.rst
--rw-r--r--   0 runner    (1001) docker     (123)     1293 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/physical/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/physical/opto_electronic/
--rw-r--r--   0 runner    (1001) docker     (123)      147 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/physical/opto_electronic/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/physical/photonic/
--rw-r--r--   0 runner    (1001) docker     (123)      126 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/physical/photonic/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/physical/thermal/
--rw-r--r--   0 runner    (1001) docker     (123)      382 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/physical/thermal/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/physical/units/
--rw-r--r--   0 runner    (1001) docker     (123)      526 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/physical/units/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/transient/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/transient/electrical/
--rw-r--r--   0 runner    (1001) docker     (123)      135 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/transient/electrical/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/transient/electro_optic/
--rw-r--r--   0 runner    (1001) docker     (123)      144 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/transient/electro_optic/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/transient/electronic/
--rw-r--r--   0 runner    (1001) docker     (123)      135 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/transient/electronic/index.rst
--rw-r--r--   0 runner    (1001) docker     (123)      300 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/transient/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/transient/opto_electronic/
--rw-r--r--   0 runner    (1001) docker     (123)      150 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/transient/opto_electronic/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/transient/photonic/
--rw-r--r--   0 runner    (1001) docker     (123)      129 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/transient/photonic/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/models/utils/
--rw-r--r--   0 runner    (1001) docker     (123)       90 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/models/utils/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/openlane/
--rw-r--r--   0 runner    (1001) docker     (123)    18165 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/openlane/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/openlane/migrate/
--rw-r--r--   0 runner    (1001) docker     (123)     1701 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/openlane/migrate/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.244233 piel-0.0.32/docs/autoapi/piel/openlane/parse/
--rw-r--r--   0 runner    (1001) docker     (123)    12538 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/openlane/parse/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.248233 piel-0.0.32/docs/autoapi/piel/openlane/parse/run_output/
--rw-r--r--   0 runner    (1001) docker     (123)     1806 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/openlane/parse/run_output/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.248233 piel-0.0.32/docs/autoapi/piel/openlane/parse/sta_rpt/
--rw-r--r--   0 runner    (1001) docker     (123)     5374 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/openlane/parse/sta_rpt/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.248233 piel-0.0.32/docs/autoapi/piel/openlane/parse/utils/
--rw-r--r--   0 runner    (1001) docker     (123)     2114 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/openlane/parse/utils/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.248233 piel-0.0.32/docs/autoapi/piel/openlane/utils/
--rw-r--r--   0 runner    (1001) docker     (123)      492 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/openlane/utils/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.248233 piel-0.0.32/docs/autoapi/piel/openlane/v1/
--rw-r--r--   0 runner    (1001) docker     (123)     5629 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/openlane/v1/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.248233 piel-0.0.32/docs/autoapi/piel/openlane/v2/
--rw-r--r--   0 runner    (1001) docker     (123)      660 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/openlane/v2/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.248233 piel-0.0.32/docs/autoapi/piel/parametric/
--rw-r--r--   0 runner    (1001) docker     (123)     3026 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/parametric/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.248233 piel-0.0.32/docs/autoapi/piel/piel/
--rw-r--r--   0 runner    (1001) docker     (123)      113 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/piel/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.248233 piel-0.0.32/docs/autoapi/piel/project_structure/
--rw-r--r--   0 runner    (1001) docker     (123)     1037 2023-06-27 21:04:28.000000 piel-0.0.32/docs/autoapi/piel/project_structure/index.rst
--rw-r--r--   0 runner    (1001) docker     (123)     4063 2023-06-27 21:04:28.000000 piel-0.0.32/docs/conf.py
--rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-27 21:04:28.000000 piel-0.0.32/docs/contributing.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.236233 piel-0.0.32/docs/examples/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.236233 piel-0.0.32/docs/examples/designs/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.236233 piel-0.0.32/docs/examples/designs/simple_design/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.236233 piel-0.0.32/docs/examples/designs/simple_design/simple_design/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.248233 piel-0.0.32/docs/examples/designs/simple_design/simple_design/tb/
--rw-r--r--   0 runner    (1001) docker     (123)      368 2023-06-27 21:04:28.000000 piel-0.0.32/docs/examples/designs/simple_design/simple_design/tb/Makefile
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.248233 piel-0.0.32/docs/examples/designs/simple_design/simple_design/tb/default/
--rw-r--r--   0 runner    (1001) docker     (123)     2271 2023-06-27 21:04:28.000000 piel-0.0.32/docs/examples/designs/simple_design/simple_design/tb/default/Makefile
--rw-r--r--   0 runner    (1001) docker     (123)      360 2023-06-27 21:04:28.000000 piel-0.0.32/docs/examples.rst
--rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-27 21:04:28.000000 piel-0.0.32/docs/history.rst
--rw-r--r--   0 runner    (1001) docker     (123)      582 2023-06-27 21:04:28.000000 piel-0.0.32/docs/index.rst
--rw-r--r--   0 runner    (1001) docker     (123)      766 2023-06-27 21:04:28.000000 piel-0.0.32/docs/make.bat
--rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-27 21:04:28.000000 piel-0.0.32/docs/readme.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.236233 piel-0.0.32/docs/sections/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.248233 piel-0.0.32/docs/sections/about/
--rw-r--r--   0 runner    (1001) docker     (123)      164 2023-06-27 21:04:28.000000 piel-0.0.32/docs/sections/about/AUTHORS.rst
--rw-r--r--   0 runner    (1001) docker     (123)      117 2023-06-27 21:04:28.000000 piel-0.0.32/docs/sections/about/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.248233 piel-0.0.32/docs/sections/codesign/
--rw-r--r--   0 runner    (1001) docker     (123)      189 2023-06-27 21:04:28.000000 piel-0.0.32/docs/sections/codesign/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.248233 piel-0.0.32/docs/sections/components/
--rw-r--r--   0 runner    (1001) docker     (123)      107 2023-06-27 21:04:28.000000 piel-0.0.32/docs/sections/components/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.248233 piel-0.0.32/docs/sections/environment/
--rw-r--r--   0 runner    (1001) docker     (123)      239 2023-06-27 21:04:28.000000 piel-0.0.32/docs/sections/environment/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.248233 piel-0.0.32/docs/sections/integration/
--rw-r--r--   0 runner    (1001) docker     (123)      165 2023-06-27 21:04:28.000000 piel-0.0.32/docs/sections/integration/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.248233 piel-0.0.32/docs/sections/models/
--rw-r--r--   0 runner    (1001) docker     (123)       99 2023-06-27 21:04:28.000000 piel-0.0.32/docs/sections/models/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.248233 piel-0.0.32/piel/
--rw-r--r--   0 runner    (1001) docker     (123)      532 2023-06-27 21:04:28.000000 piel-0.0.32/piel/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      375 2023-06-27 21:04:28.000000 piel-0.0.32/piel/cli.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.248233 piel-0.0.32/piel/cocotb/
--rw-r--r--   0 runner    (1001) docker     (123)       20 2023-06-27 21:04:28.000000 piel-0.0.32/piel/cocotb/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6179 2023-06-27 21:04:28.000000 piel-0.0.32/piel/cocotb/core.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.248233 piel-0.0.32/piel/components/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:28.000000 piel-0.0.32/piel/components/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      805 2023-06-27 21:04:28.000000 piel-0.0.32/piel/config.py
--rw-r--r--   0 runner    (1001) docker     (123)     1383 2023-06-27 21:04:28.000000 piel-0.0.32/piel/defaults.py
--rw-r--r--   0 runner    (1001) docker     (123)    10793 2023-06-27 21:04:28.000000 piel-0.0.32/piel/file_system.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.252233 piel-0.0.32/piel/integration/
--rw-r--r--   0 runner    (1001) docker     (123)       40 2023-06-27 21:04:28.000000 piel-0.0.32/piel/integration/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2057 2023-06-27 21:04:28.000000 piel-0.0.32/piel/integration/openlane_gdsfactory_core.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:28.000000 piel-0.0.32/piel/integration/sax_cocotb.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.252233 piel-0.0.32/piel/models/
--rw-r--r--   0 runner    (1001) docker     (123)      209 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.252233 piel-0.0.32/piel/models/frequency/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/frequency/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.252233 piel-0.0.32/piel/models/frequency/electrical/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/frequency/electrical/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.252233 piel-0.0.32/piel/models/frequency/electro_optic/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/frequency/electro_optic/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.252233 piel-0.0.32/piel/models/frequency/electronic/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/frequency/electronic/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.252233 piel-0.0.32/piel/models/frequency/opto_electronic/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/frequency/opto_electronic/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.252233 piel-0.0.32/piel/models/frequency/photonic/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/frequency/photonic/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      319 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/frequency/photonic/coupler_simple.py
--rw-r--r--   0 runner    (1001) docker     (123)      665 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/frequency/photonic/directional_coupler_length.py
--rw-r--r--   0 runner    (1001) docker     (123)      672 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/frequency/photonic/directional_coupler_real.py
--rw-r--r--   0 runner    (1001) docker     (123)      343 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/frequency/photonic/directional_coupler_simple.py
--rw-r--r--   0 runner    (1001) docker     (123)      639 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/frequency/photonic/grating_coupler.py
--rw-r--r--   0 runner    (1001) docker     (123)      142 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/frequency/photonic/mmi1x2.py
--rw-r--r--   0 runner    (1001) docker     (123)      216 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/frequency/photonic/mmi2x2.py
--rw-r--r--   0 runner    (1001) docker     (123)      436 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/frequency/photonic/straight_waveguide.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.252233 piel-0.0.32/piel/models/logic/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/logic/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.252233 piel-0.0.32/piel/models/logic/electrical/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/logic/electrical/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.252233 piel-0.0.32/piel/models/logic/electro_optic/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/logic/electro_optic/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.252233 piel-0.0.32/piel/models/logic/electronic/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/logic/electronic/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.252233 piel-0.0.32/piel/models/logic/opto_electronic/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/logic/opto_electronic/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.252233 piel-0.0.32/piel/models/logic/photonic/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/logic/photonic/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.252233 piel-0.0.32/piel/models/physical/
--rw-r--r--   0 runner    (1001) docker     (123)       45 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/physical/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.252233 piel-0.0.32/piel/models/physical/electrical/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/physical/electrical/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/physical/electrical/cable.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.252233 piel-0.0.32/piel/models/physical/electro_optic/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/physical/electro_optic/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.252233 piel-0.0.32/piel/models/physical/electronic/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/physical/electronic/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      371 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/physical/geometry.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.252233 piel-0.0.32/piel/models/physical/opto_electronic/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/physical/opto_electronic/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.252233 piel-0.0.32/piel/models/physical/photonic/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/physical/photonic/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      344 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/physical/thermal.py
--rw-r--r--   0 runner    (1001) docker     (123)      335 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/physical/units.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.252233 piel-0.0.32/piel/models/transient/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/transient/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.256233 piel-0.0.32/piel/models/transient/electrical/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/transient/electrical/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.256233 piel-0.0.32/piel/models/transient/electro_optic/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/transient/electro_optic/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.256233 piel-0.0.32/piel/models/transient/electronic/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/transient/electronic/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.256233 piel-0.0.32/piel/models/transient/opto_electronic/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/transient/opto_electronic/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.256233 piel-0.0.32/piel/models/transient/photonic/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/transient/photonic/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:28.000000 piel-0.0.32/piel/models/utils.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.256233 piel-0.0.32/piel/openlane/
--rw-r--r--   0 runner    (1001) docker     (123)      101 2023-06-27 21:04:28.000000 piel-0.0.32/piel/openlane/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2048 2023-06-27 21:04:28.000000 piel-0.0.32/piel/openlane/migrate.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.256233 piel-0.0.32/piel/openlane/parse/
--rw-r--r--   0 runner    (1001) docker     (123)      237 2023-06-27 21:04:28.000000 piel-0.0.32/piel/openlane/parse/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2249 2023-06-27 21:04:28.000000 piel-0.0.32/piel/openlane/parse/run_output.py
--rw-r--r--   0 runner    (1001) docker     (123)    10314 2023-06-27 21:04:28.000000 piel-0.0.32/piel/openlane/parse/sta_rpt.py
--rw-r--r--   0 runner    (1001) docker     (123)     2177 2023-06-27 21:04:28.000000 piel-0.0.32/piel/openlane/parse/utils.py
--rw-r--r--   0 runner    (1001) docker     (123)     1395 2023-06-27 21:04:28.000000 piel-0.0.32/piel/openlane/utils.py
--rw-r--r--   0 runner    (1001) docker     (123)    10692 2023-06-27 21:04:28.000000 piel-0.0.32/piel/openlane/v1.py
--rw-r--r--   0 runner    (1001) docker     (123)      975 2023-06-27 21:04:28.000000 piel-0.0.32/piel/openlane/v2.py
--rw-r--r--   0 runner    (1001) docker     (123)     3929 2023-06-27 21:04:28.000000 piel-0.0.32/piel/parametric.py
--rw-r--r--   0 runner    (1001) docker     (123)     1854 2023-06-27 21:04:28.000000 piel-0.0.32/piel/project_structure.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.248233 piel-0.0.32/piel.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     3210 2023-06-27 21:04:44.000000 piel-0.0.32/piel.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     6125 2023-06-27 21:04:44.000000 piel-0.0.32/piel.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 21:04:44.000000 piel-0.0.32/piel.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       39 2023-06-27 21:04:44.000000 piel-0.0.32/piel.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 21:04:44.000000 piel-0.0.32/piel.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)      207 2023-06-27 21:04:44.000000 piel-0.0.32/piel.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)        5 2023-06-27 21:04:44.000000 piel-0.0.32/piel.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)      137 2023-06-27 21:04:44.256233 piel-0.0.32/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     1866 2023-06-27 21:04:28.000000 piel-0.0.32/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:04:44.256233 piel-0.0.32/tests/
--rw-r--r--   0 runner    (1001) docker     (123)       34 2023-06-27 21:04:28.000000 piel-0.0.32/tests/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      964 2023-06-27 21:04:28.000000 piel-0.0.32/tests/test_piel.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.707905 piel-0.0.33/
+-rw-r--r--   0 runner    (1001) docker     (123)     3478 2023-06-28 09:50:13.000000 piel-0.0.33/CONTRIBUTING.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1073 2023-06-28 09:50:13.000000 piel-0.0.33/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)      262 2023-06-28 09:50:13.000000 piel-0.0.33/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)     3210 2023-06-28 09:50:33.707905 piel-0.0.33/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2385 2023-06-28 09:50:13.000000 piel-0.0.33/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.691905 piel-0.0.33/docs/
+-rw-r--r--   0 runner    (1001) docker     (123)      605 2023-06-28 09:50:13.000000 piel-0.0.33/docs/Makefile
+-rw-r--r--   0 runner    (1001) docker     (123)     4082 2023-06-28 09:50:13.000000 piel-0.0.33/docs/conf.py
+-rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-28 09:50:13.000000 piel-0.0.33/docs/contributing.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.683905 piel-0.0.33/docs/examples/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.687905 piel-0.0.33/docs/examples/designs/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.687905 piel-0.0.33/docs/examples/designs/simple_design/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.687905 piel-0.0.33/docs/examples/designs/simple_design/simple_design/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.691905 piel-0.0.33/docs/examples/designs/simple_design/simple_design/tb/
+-rw-r--r--   0 runner    (1001) docker     (123)      368 2023-06-28 09:50:13.000000 piel-0.0.33/docs/examples/designs/simple_design/simple_design/tb/Makefile
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.691905 piel-0.0.33/docs/examples/designs/simple_design/simple_design/tb/default/
+-rw-r--r--   0 runner    (1001) docker     (123)     2271 2023-06-28 09:50:13.000000 piel-0.0.33/docs/examples/designs/simple_design/simple_design/tb/default/Makefile
+-rw-r--r--   0 runner    (1001) docker     (123)      360 2023-06-28 09:50:13.000000 piel-0.0.33/docs/examples.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      559 2023-06-28 09:50:13.000000 piel-0.0.33/docs/index.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      766 2023-06-28 09:50:13.000000 piel-0.0.33/docs/make.bat
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.687905 piel-0.0.33/docs/sections/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.691905 piel-0.0.33/docs/sections/about/
+-rw-r--r--   0 runner    (1001) docker     (123)      164 2023-06-28 09:50:13.000000 piel-0.0.33/docs/sections/about/AUTHORS.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      117 2023-06-28 09:50:13.000000 piel-0.0.33/docs/sections/about/index.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.691905 piel-0.0.33/docs/sections/codesign/
+-rw-r--r--   0 runner    (1001) docker     (123)      197 2023-06-28 09:50:13.000000 piel-0.0.33/docs/sections/codesign/index.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.695905 piel-0.0.33/docs/sections/components/
+-rw-r--r--   0 runner    (1001) docker     (123)      107 2023-06-28 09:50:13.000000 piel-0.0.33/docs/sections/components/index.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.695905 piel-0.0.33/docs/sections/environment/
+-rw-r--r--   0 runner    (1001) docker     (123)      239 2023-06-28 09:50:13.000000 piel-0.0.33/docs/sections/environment/index.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.695905 piel-0.0.33/docs/sections/integration/
+-rw-r--r--   0 runner    (1001) docker     (123)      165 2023-06-28 09:50:13.000000 piel-0.0.33/docs/sections/integration/index.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.695905 piel-0.0.33/docs/sections/models/
+-rw-r--r--   0 runner    (1001) docker     (123)       99 2023-06-28 09:50:13.000000 piel-0.0.33/docs/sections/models/index.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.695905 piel-0.0.33/piel/
+-rw-r--r--   0 runner    (1001) docker     (123)      532 2023-06-28 09:50:13.000000 piel-0.0.33/piel/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      375 2023-06-28 09:50:13.000000 piel-0.0.33/piel/cli.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.695905 piel-0.0.33/piel/cocotb/
+-rw-r--r--   0 runner    (1001) docker     (123)       20 2023-06-28 09:50:13.000000 piel-0.0.33/piel/cocotb/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6179 2023-06-28 09:50:13.000000 piel-0.0.33/piel/cocotb/core.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.695905 piel-0.0.33/piel/components/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:13.000000 piel-0.0.33/piel/components/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      805 2023-06-28 09:50:13.000000 piel-0.0.33/piel/config.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1383 2023-06-28 09:50:13.000000 piel-0.0.33/piel/defaults.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10793 2023-06-28 09:50:13.000000 piel-0.0.33/piel/file_system.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.699905 piel-0.0.33/piel/integration/
+-rw-r--r--   0 runner    (1001) docker     (123)       40 2023-06-28 09:50:13.000000 piel-0.0.33/piel/integration/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2057 2023-06-28 09:50:13.000000 piel-0.0.33/piel/integration/openlane_gdsfactory_core.py
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:13.000000 piel-0.0.33/piel/integration/sax_cocotb.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.699905 piel-0.0.33/piel/models/
+-rw-r--r--   0 runner    (1001) docker     (123)      209 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.699905 piel-0.0.33/piel/models/frequency/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/frequency/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.699905 piel-0.0.33/piel/models/frequency/electrical/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/frequency/electrical/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.699905 piel-0.0.33/piel/models/frequency/electro_optic/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/frequency/electro_optic/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.699905 piel-0.0.33/piel/models/frequency/electronic/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/frequency/electronic/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.699905 piel-0.0.33/piel/models/frequency/opto_electronic/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/frequency/opto_electronic/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.699905 piel-0.0.33/piel/models/frequency/photonic/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/frequency/photonic/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      319 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/frequency/photonic/coupler_simple.py
+-rw-r--r--   0 runner    (1001) docker     (123)      665 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/frequency/photonic/directional_coupler_length.py
+-rw-r--r--   0 runner    (1001) docker     (123)      672 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/frequency/photonic/directional_coupler_real.py
+-rw-r--r--   0 runner    (1001) docker     (123)      343 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/frequency/photonic/directional_coupler_simple.py
+-rw-r--r--   0 runner    (1001) docker     (123)      639 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/frequency/photonic/grating_coupler.py
+-rw-r--r--   0 runner    (1001) docker     (123)      142 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/frequency/photonic/mmi1x2.py
+-rw-r--r--   0 runner    (1001) docker     (123)      216 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/frequency/photonic/mmi2x2.py
+-rw-r--r--   0 runner    (1001) docker     (123)      436 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/frequency/photonic/straight_waveguide.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.699905 piel-0.0.33/piel/models/logic/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/logic/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.699905 piel-0.0.33/piel/models/logic/electrical/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/logic/electrical/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.699905 piel-0.0.33/piel/models/logic/electro_optic/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/logic/electro_optic/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.699905 piel-0.0.33/piel/models/logic/electronic/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/logic/electronic/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.703905 piel-0.0.33/piel/models/logic/opto_electronic/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/logic/opto_electronic/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.703905 piel-0.0.33/piel/models/logic/photonic/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/logic/photonic/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.703905 piel-0.0.33/piel/models/physical/
+-rw-r--r--   0 runner    (1001) docker     (123)       45 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/physical/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.703905 piel-0.0.33/piel/models/physical/electrical/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/physical/electrical/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/physical/electrical/cable.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.703905 piel-0.0.33/piel/models/physical/electro_optic/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/physical/electro_optic/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.703905 piel-0.0.33/piel/models/physical/electronic/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/physical/electronic/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      371 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/physical/geometry.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.703905 piel-0.0.33/piel/models/physical/opto_electronic/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/physical/opto_electronic/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.703905 piel-0.0.33/piel/models/physical/photonic/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/physical/photonic/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      344 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/physical/thermal.py
+-rw-r--r--   0 runner    (1001) docker     (123)      335 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/physical/units.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.703905 piel-0.0.33/piel/models/transient/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/transient/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.703905 piel-0.0.33/piel/models/transient/electrical/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/transient/electrical/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.703905 piel-0.0.33/piel/models/transient/electro_optic/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/transient/electro_optic/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.703905 piel-0.0.33/piel/models/transient/electronic/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/transient/electronic/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.703905 piel-0.0.33/piel/models/transient/opto_electronic/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/transient/opto_electronic/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.703905 piel-0.0.33/piel/models/transient/photonic/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/transient/photonic/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:13.000000 piel-0.0.33/piel/models/utils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.707905 piel-0.0.33/piel/openlane/
+-rw-r--r--   0 runner    (1001) docker     (123)      101 2023-06-28 09:50:13.000000 piel-0.0.33/piel/openlane/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2048 2023-06-28 09:50:13.000000 piel-0.0.33/piel/openlane/migrate.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.707905 piel-0.0.33/piel/openlane/parse/
+-rw-r--r--   0 runner    (1001) docker     (123)      237 2023-06-28 09:50:13.000000 piel-0.0.33/piel/openlane/parse/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2249 2023-06-28 09:50:13.000000 piel-0.0.33/piel/openlane/parse/run_output.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10314 2023-06-28 09:50:13.000000 piel-0.0.33/piel/openlane/parse/sta_rpt.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2177 2023-06-28 09:50:13.000000 piel-0.0.33/piel/openlane/parse/utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1395 2023-06-28 09:50:13.000000 piel-0.0.33/piel/openlane/utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10692 2023-06-28 09:50:13.000000 piel-0.0.33/piel/openlane/v1.py
+-rw-r--r--   0 runner    (1001) docker     (123)      975 2023-06-28 09:50:13.000000 piel-0.0.33/piel/openlane/v2.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3929 2023-06-28 09:50:13.000000 piel-0.0.33/piel/parametric.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1854 2023-06-28 09:50:13.000000 piel-0.0.33/piel/project_structure.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.695905 piel-0.0.33/piel.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     3210 2023-06-28 09:50:33.000000 piel-0.0.33/piel.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2929 2023-06-28 09:50:33.000000 piel-0.0.33/piel.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 09:50:33.000000 piel-0.0.33/piel.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       39 2023-06-28 09:50:33.000000 piel-0.0.33/piel.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 09:50:33.000000 piel-0.0.33/piel.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)      207 2023-06-28 09:50:33.000000 piel-0.0.33/piel.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        5 2023-06-28 09:50:33.000000 piel-0.0.33/piel.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      137 2023-06-28 09:50:33.707905 piel-0.0.33/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1866 2023-06-28 09:50:13.000000 piel-0.0.33/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:50:33.707905 piel-0.0.33/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)       34 2023-06-28 09:50:13.000000 piel-0.0.33/tests/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      964 2023-06-28 09:50:13.000000 piel-0.0.33/tests/test_piel.py
```

### Comparing `piel-0.0.32/CONTRIBUTING.rst` & `piel-0.0.33/CONTRIBUTING.rst`

 * *Files identical despite different names*

### Comparing `piel-0.0.32/LICENSE` & `piel-0.0.33/LICENSE`

 * *Files identical despite different names*

### Comparing `piel-0.0.32/PKG-INFO` & `piel-0.0.33/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: piel
-Version: 0.0.32
+Version: 0.0.33
 Summary: Photonic and electronic co-simulation system design tools interfaced with open-source design software like GDSFactory and OpenROAD.
 Home-page: https://github.com/daquintero/piel
 Author: Dario Quintero
 Author-email: darioaquintero@gmail.com
 License: MIT license
 Keywords: piel
 Classifier: Development Status :: 2 - Pre-Alpha
```

### Comparing `piel-0.0.32/README.md` & `piel-0.0.33/README.md`

 * *Files identical despite different names*

### Comparing `piel-0.0.32/docs/Makefile` & `piel-0.0.33/docs/Makefile`

 * *Files identical despite different names*

### Comparing `piel-0.0.32/docs/autoapi/piel/integration/index.rst` & `piel-0.0.33/piel/integration/openlane_gdsfactory_core.py`

 * *Files 25% similar despite different names*

```diff
@@ -1,46 +1,51 @@
-:py:mod:`piel.integration`
-==========================
+"""
+There are a number of ways to generate gdsfactory integration.
 
-.. py:module:: piel.integration
+It is worth noting that GDSFactory has already the following PDKs installed:
+* SKY130nm https://gdsfactory.github.io/skywater130/
+* GF180nm https://gdsfactory.github.io/gf180/
+"""
+import gdsfactory as gf
+import pathlib
+from ..file_system import check_path_exists
+from ..openlane.migrate import get_design_from_openlane_migration
+from ..openlane.utils import find_design_run
+
+
+def create_gdsfactory_component_from_openlane(
+    design_name_v1: str | None = None,
+    design_directory: str | pathlib.Path | None = None,
+    run_name: str | None = None,
+    v1: bool = True,
+) -> gf.Component:
+    """
+    This function cretes a gdsfactory layout component that can be included in the network codesign of the device, or that can be used for interconnection codesign.
+
+    It will look into the latest design run and extract the final OpenLane-generated GDS. You do not have to have run this with OpenLane2 as it just looks at the latest run.
+
+    Args:
+        design_name_v1(str): Design name of the v1 design that can be found within `$OPENLANE_ROOT/"<latest>"/designs`.
+        design_directory(str): Design directory PATH.
+        run_name(str): Name of the run to extract the GDS from. If None, it will look at the latest run.
+        v1(bool): If True, it will import the design from the OpenLane v1 configuration.
+
+    Returns:
+        component(gf.Component): GDSFactory component.
+    """
+    design_name, design_directory = get_design_from_openlane_migration(
+        v1=v1, design_name_v1=design_name_v1, design_directory=design_directory
+    )
+    latest_design_run_directory = find_design_run(design_directory, run_name=run_name)
+    final_gds_run = (
+        latest_design_run_directory
+        / "results"
+        / "final"
+        / "gds"
+        / (design_name + ".gds")
+    )
+    check_path_exists(final_gds_run, raise_errors=True)
+    component = gf.import_gds(final_gds_run, name=design_name)
+    return component
 
 
-Submodules
-----------
-.. toctree::
-   :titlesonly:
-   :maxdepth: 1
-
-   openlane_gdsfactory_core/index.rst
-   sax_cocotb/index.rst
-
-
-Package Contents
-----------------
-
-
-Functions
-~~~~~~~~~
-
-.. autoapisummary::
-
-   piel.integration.create_gdsfactory_component_from_openlane
-
-
-
-.. py:function:: create_gdsfactory_component_from_openlane(design_name_v1: str | None = None, design_directory: str | pathlib.Path | None = None, run_name: str | None = None, v1: bool = True) -> gdsfactory.Component
-
-   This function cretes a gdsfactory layout component that can be included in the network codesign of the device, or that can be used for interconnection codesign.
-
-   It will look into the latest design run and extract the final OpenLane-generated GDS. You do not have to have run this with OpenLane2 as it just looks at the latest run.
-
-   :param design_name_v1: Design name of the v1 design that can be found within `$OPENLANE_ROOT/"<latest>"/designs`.
-   :type design_name_v1: str
-   :param design_directory: Design directory PATH.
-   :type design_directory: str
-   :param run_name: Name of the run to extract the GDS from. If None, it will look at the latest run.
-   :type run_name: str
-   :param v1: If True, it will import the design from the OpenLane v1 configuration.
-   :type v1: bool
-
-   :returns: GDSFactory component.
-   :rtype: component(gf.Component)
+__all__ = ["create_gdsfactory_component_from_openlane"]
```

### Comparing `piel-0.0.32/docs/conf.py` & `piel-0.0.33/docs/conf.py`

 * *Files 2% similar despite different names*

```diff
@@ -40,15 +40,15 @@
 autoapi_keep_files = True
 autoapi_template_dir = "_autoapi_templates"
 autosummary_generate = True  # Turn on sphinx.ext.autosummary
 autoclass_content = "both"  # Add __init__ doc (ie. params) to class summaries
 autodoc_inherit_docstrings = True  # If no docstring, inherit from base class
 author = "Dario Quintero"
 copyright = "2023, Dario Quintero"
-exclude_patterns = ["_build", "Thumbs.db", ".DS_Store"]
+exclude_patterns = ["_build", "Thumbs.db", ".DS_Store", "examples/designs"]
 extensions = [
     "autoapi.extension",
     "IPython.sphinxext.ipython_console_highlighting",
     "nbsphinx",  # Integrate Jupyter Notebooks and Sphinx
     "myst_parser",
     "sphinx.ext.autodoc",  # Core Sphinx library for auto html doc generation from docstrings
     "sphinx.ext.autosummary",  # Create neat summary tables for modules/classes/methods etc
@@ -66,15 +66,15 @@
 # Grouping the document tree into LaTeX files. List of tuples
 # (source start file, target name, title, author, documentclass
 # [howto, manual, or own class]).
 latex_documents = [
     (master_doc, "piel.tex", "piel Documentation", "Dario Quintero", "manual"),
 ]
 html_show_sourcelink = (
-    False  # Remove 'view source code' from top of page (for html, not python)
+    True  # Remove 'view source code' from top of page (for html, not python)
 )
 html_static_path = ["_static"]
 html_theme = "alabaster"
 htmlhelp_basename = "pieldoc"
 man_pages = [(master_doc, "piel", "piel Documentation", [author], 1)]
 project = "piel"
 pygments_style = "sphinx"
```

### Comparing `piel-0.0.32/docs/examples/designs/simple_design/simple_design/tb/default/Makefile` & `piel-0.0.33/docs/examples/designs/simple_design/simple_design/tb/default/Makefile`

 * *Files identical despite different names*

### Comparing `piel-0.0.32/docs/index.rst` & `piel-0.0.33/docs/index.rst`

 * *Files 18% similar despite different names*

```diff
@@ -1,27 +1,24 @@
-**P**\hotonics & **I**\ntegrated **EL**\ectronic
+**P**\hotonic & **I**\ntegrated **EL**\ectronic
 ===============================================
 Co-simulation system design tools interfaced with open-source design software like GDSFactory and OpenROAD.
 
-
 .. toctree::
    :maxdepth: 2
    :caption: Contents:
 
-   readme
-   installation
    examples
+   installation
    sections/environment/index
    sections/integration/index
    sections/codesign/index
    sections/components/index
    sections/models/index
    contributing
    sections/about/index
-   authors
 
 
 Indices and tables
 ==================
 * :ref:`genindex`
 * :ref:`modindex`
 * :ref:`search`
```

### Comparing `piel-0.0.32/docs/make.bat` & `piel-0.0.33/docs/make.bat`

 * *Files identical despite different names*

### Comparing `piel-0.0.32/piel/__init__.py` & `piel-0.0.33/piel/__init__.py`

 * *Files 1% similar despite different names*

```diff
@@ -17,8 +17,8 @@
 
 os.environ["PIEL_PACKAGE_DIRECTORY"] = str(
     pathlib.Path(__file__).parent.parent.resolve()
 )
 
 __author__ = """Dario Quintero"""
 __email__ = "darioaquintero@gmail.com"
-__version__ = "0.0.32"
+__version__ = "0.0.33"
```

### Comparing `piel-0.0.32/piel/cocotb/core.py` & `piel-0.0.33/piel/cocotb/core.py`

 * *Files identical despite different names*

### Comparing `piel-0.0.32/piel/config.py` & `piel-0.0.33/piel/config.py`

 * *Files identical despite different names*

### Comparing `piel-0.0.32/piel/defaults.py` & `piel-0.0.33/piel/defaults.py`

 * *Files identical despite different names*

### Comparing `piel-0.0.32/piel/file_system.py` & `piel-0.0.33/piel/file_system.py`

 * *Files identical despite different names*

### Comparing `piel-0.0.32/piel/models/frequency/photonic/directional_coupler_length.py` & `piel-0.0.33/piel/models/frequency/photonic/directional_coupler_length.py`

 * *Files identical despite different names*

### Comparing `piel-0.0.32/piel/models/frequency/photonic/directional_coupler_real.py` & `piel-0.0.33/piel/models/frequency/photonic/directional_coupler_real.py`

 * *Files identical despite different names*

### Comparing `piel-0.0.32/piel/models/frequency/photonic/grating_coupler.py` & `piel-0.0.33/piel/models/frequency/photonic/grating_coupler.py`

 * *Files identical despite different names*

### Comparing `piel-0.0.32/piel/openlane/migrate.py` & `piel-0.0.33/piel/openlane/migrate.py`

 * *Files identical despite different names*

### Comparing `piel-0.0.32/piel/openlane/parse/run_output.py` & `piel-0.0.33/piel/openlane/parse/run_output.py`

 * *Files identical despite different names*

### Comparing `piel-0.0.32/piel/openlane/parse/sta_rpt.py` & `piel-0.0.33/piel/openlane/parse/sta_rpt.py`

 * *Files identical despite different names*

### Comparing `piel-0.0.32/piel/openlane/parse/utils.py` & `piel-0.0.33/piel/openlane/parse/utils.py`

 * *Files identical despite different names*

### Comparing `piel-0.0.32/piel/openlane/utils.py` & `piel-0.0.33/piel/openlane/utils.py`

 * *Files identical despite different names*

### Comparing `piel-0.0.32/piel/openlane/v1.py` & `piel-0.0.33/piel/openlane/v1.py`

 * *Files identical despite different names*

### Comparing `piel-0.0.32/piel/openlane/v2.py` & `piel-0.0.33/piel/openlane/v2.py`

 * *Files identical despite different names*

### Comparing `piel-0.0.32/piel/parametric.py` & `piel-0.0.33/piel/parametric.py`

 * *Files identical despite different names*

### Comparing `piel-0.0.32/piel/project_structure.py` & `piel-0.0.33/piel/project_structure.py`

 * *Files identical despite different names*

### Comparing `piel-0.0.32/piel.egg-info/PKG-INFO` & `piel-0.0.33/piel.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: piel
-Version: 0.0.32
+Version: 0.0.33
 Summary: Photonic and electronic co-simulation system design tools interfaced with open-source design software like GDSFactory and OpenROAD.
 Home-page: https://github.com/daquintero/piel
 Author: Dario Quintero
 Author-email: darioaquintero@gmail.com
 License: MIT license
 Keywords: piel
 Classifier: Development Status :: 2 - Pre-Alpha
```

### Comparing `piel-0.0.32/setup.py` & `piel-0.0.33/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -62,10 +62,10 @@
     include_package_data=True,
     keywords="piel",
     name="piel",
     packages=find_packages(include=["piel", "piel.*"]),
     test_suite="tests",
     tests_require=test_requirements,
     url="https://github.com/daquintero/piel",
-    version="0.0.32",
+    version="0.0.33",
     zip_safe=False,
 )
```

### Comparing `piel-0.0.32/tests/test_piel.py` & `piel-0.0.33/tests/test_piel.py`

 * *Files identical despite different names*


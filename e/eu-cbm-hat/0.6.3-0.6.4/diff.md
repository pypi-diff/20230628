# Comparing `tmp/eu_cbm_hat-0.6.3.tar.gz` & `tmp/eu_cbm_hat-0.6.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "eu_cbm_hat-0.6.3.tar", last modified: Tue Jun  6 14:52:38 2023, max compression
+gzip compressed data, was "eu_cbm_hat-0.6.4.tar", last modified: Wed Jun 28 10:15:34 2023, max compression
```

## Comparing `eu_cbm_hat-0.6.3.tar` & `eu_cbm_hat-0.6.4.tar`

### file list

```diff
@@ -1,147 +1,151 @@
-drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-06 14:52:38.123123 eu_cbm_hat-0.6.3/
--rw-r--r--   0 paul      (1000) paul      (1000)    13862 2022-12-07 14:55:14.000000 eu_cbm_hat-0.6.3/LICENCE.txt
--rw-r--r--   0 paul      (1000) paul      (1000)       92 2022-12-07 14:57:34.000000 eu_cbm_hat-0.6.3/MANIFEST.in
--rw-r--r--   0 paul      (1000) paul      (1000)    57674 2022-12-07 16:29:26.000000 eu_cbm_hat-0.6.3/NOTICE.txt
--rw-r--r--   0 paul      (1000) paul      (1000)     8078 2023-06-06 14:52:38.123123 eu_cbm_hat-0.6.3/PKG-INFO
--rw-r--r--   0 paul      (1000) paul      (1000)     7649 2023-05-16 17:40:14.000000 eu_cbm_hat-0.6.3/README.md
-drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-06 14:52:38.103122 eu_cbm_hat-0.6.3/eu_cbm_hat/
--rw-r--r--   0 paul      (1000) paul      (1000)     1618 2023-06-06 14:47:43.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/__init__.py
-drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-06 14:52:38.103122 eu_cbm_hat-0.6.3/eu_cbm_hat/cbm/
--rw-r--r--   0 paul      (1000) paul      (1000)       72 2022-12-09 09:42:16.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/cbm/__init__.py
--rw-r--r--   0 paul      (1000) paul      (1000)    30598 2023-06-05 14:51:46.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/cbm/dynamic.py
--rw-r--r--   0 paul      (1000) paul      (1000)     5853 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/cbm/simulation.py
-drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-06 14:52:38.107122 eu_cbm_hat-0.6.3/eu_cbm_hat/combos/
--rw-r--r--   0 paul      (1000) paul      (1000)     1359 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/combos/__init__.py
--rw-r--r--   0 paul      (1000) paul      (1000)     5182 2022-12-07 10:05:35.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/combos/base_combo.py
--rw-r--r--   0 paul      (1000) paul      (1000)      905 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/combos/harvest_test.py
--rw-r--r--   0 paul      (1000) paul      (1000)      825 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/combos/hat.py
--rw-r--r--   0 paul      (1000) paul      (1000)     2091 2022-12-07 10:05:35.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/combos/historical.py
--rw-r--r--   0 paul      (1000) paul      (1000)      791 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/combos/no_market_forcing.py
--rw-r--r--   0 paul      (1000) paul      (1000)      793 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/combos/potencia_baseline.py
--rw-r--r--   0 paul      (1000) paul      (1000)      805 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/combos/potencia_necp_bme_up100.py
--rw-r--r--   0 paul      (1000) paul      (1000)      805 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/combos/potencia_necp_bme_up200.py
--rw-r--r--   0 paul      (1000) paul      (1000)      807 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/combos/potencia_necp_bms_down50.py
--rw-r--r--   0 paul      (1000) paul      (1000)      807 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/combos/potencia_necp_bms_down90.py
--rw-r--r--   0 paul      (1000) paul      (1000)      777 2023-02-14 09:33:00.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/combos/reference.py
--rw-r--r--   0 paul      (1000) paul      (1000)      845 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/combos/reference_crf.py
--rw-r--r--   0 paul      (1000) paul      (1000)      835 2022-12-21 16:03:35.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/combos/skewfcth.py
--rw-r--r--   0 paul      (1000) paul      (1000)      818 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/combos/special.py
-drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-06 14:52:38.107122 eu_cbm_hat-0.6.3/eu_cbm_hat/core/
--rw-r--r--   0 paul      (1000) paul      (1000)      618 2022-12-09 09:35:23.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/core/__init__.py
--rw-r--r--   0 paul      (1000) paul      (1000)     2743 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/core/continent.py
--rw-r--r--   0 paul      (1000) paul      (1000)     5672 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/core/country.py
--rw-r--r--   0 paul      (1000) paul      (1000)     8949 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/core/runner.py
-drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-06 14:52:38.107122 eu_cbm_hat-0.6.3/eu_cbm_hat/info/
--rw-r--r--   0 paul      (1000) paul      (1000)        0 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/info/__init__.py
--rw-r--r--   0 paul      (1000) paul      (1000)     5226 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/info/aidb.py
--rw-r--r--   0 paul      (1000) paul      (1000)     5983 2022-12-15 15:55:50.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/info/fluxes.py
--rw-r--r--   0 paul      (1000) paul      (1000)     5456 2022-12-07 10:05:35.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/info/harvest.py
--rw-r--r--   0 paul      (1000) paul      (1000)     5224 2023-05-16 16:03:15.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/info/input_data.py
--rw-r--r--   0 paul      (1000) paul      (1000)     2573 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/info/internal_data.py
--rw-r--r--   0 paul      (1000) paul      (1000)     4019 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/info/orig_data.py
--rw-r--r--   0 paul      (1000) paul      (1000)     7534 2022-12-07 10:05:35.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/info/output_data.py
--rw-r--r--   0 paul      (1000) paul      (1000)    14668 2022-12-15 16:30:06.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/info/silviculture.py
-drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-06 14:52:38.107122 eu_cbm_hat-0.6.3/eu_cbm_hat/launch/
--rw-r--r--   0 paul      (1000) paul      (1000)      167 2022-12-09 09:56:16.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/launch/__init__.py
--rw-r--r--   0 paul      (1000) paul      (1000)     3287 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/launch/associations.py
--rw-r--r--   0 paul      (1000) paul      (1000)     3743 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/launch/create_json.py
-drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-06 14:52:38.107122 eu_cbm_hat-0.6.3/eu_cbm_hat/pump/
--rw-r--r--   0 paul      (1000) paul      (1000)       84 2022-12-09 10:01:44.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/pump/__init__.py
--rw-r--r--   0 paul      (1000) paul      (1000)     1059 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/pump/classifiers.py
--rw-r--r--   0 paul      (1000) paul      (1000)     1401 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/pump/column_order.py
--rw-r--r--   0 paul      (1000) paul      (1000)     3287 2023-05-16 16:06:20.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/pump/long_or_wide.py
--rw-r--r--   0 paul      (1000) paul      (1000)      801 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/pump/post_processor.py
--rw-r--r--   0 paul      (1000) paul      (1000)     3659 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/pump/pre_processor.py
-drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-06 14:52:38.111122 eu_cbm_hat-0.6.3/eu_cbm_hat/qaqc/
--rw-r--r--   0 paul      (1000) paul      (1000)     1150 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/qaqc/__init__.py
--rw-r--r--   0 paul      (1000) paul      (1000)     1694 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/qaqc/aidb.py
--rw-r--r--   0 paul      (1000) paul      (1000)     7382 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/qaqc/expected_provided.py
--rw-r--r--   0 paul      (1000) paul      (1000)     3226 2022-12-07 10:05:35.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/qaqc/input_years.py
--rw-r--r--   0 paul      (1000) paul      (1000)     5958 2022-12-15 15:59:43.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/qaqc/silviculture.py
-drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-06 14:52:38.111122 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/
--rw-r--r--   0 paul      (1000) paul      (1000)      895 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/copy_data.py
-drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-06 14:52:38.099122 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/
-drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-06 14:52:38.111122 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/combos/
--rw-r--r--   0 paul      (1000) paul      (1000)     3775 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/combos/reference.yaml
-drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-06 14:52:38.111122 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/common/
--rw-r--r--   0 paul      (1000) paul      (1000)      999 2023-04-26 17:02:44.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/common/country_codes.csv
--rw-r--r--   0 paul      (1000) paul      (1000)      267 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/common/reference_years.csv
-drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-06 14:52:38.095122 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/
-drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-06 14:52:38.099122 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/
-drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-06 14:52:38.099122 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/
-drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-06 14:52:38.111122 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/afforestation/
--rw-r--r--   0 paul      (1000) paul      (1000)        1 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/afforestation/events.csv
--rw-r--r--   0 paul      (1000) paul      (1000)        1 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/afforestation/growth_curves.csv
--rw-r--r--   0 paul      (1000) paul      (1000)        1 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/afforestation/inventory.csv
--rw-r--r--   0 paul      (1000) paul      (1000)        1 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/afforestation/transitions.csv
-drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-06 14:52:38.111122 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/deforestation/
--rw-r--r--   0 paul      (1000) paul      (1000)        1 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/deforestation/events.csv
--rw-r--r--   0 paul      (1000) paul      (1000)        0 2023-04-26 17:02:44.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/deforestation/growth_curves.csv
--rw-r--r--   0 paul      (1000) paul      (1000)        0 2023-04-26 17:02:44.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/deforestation/inventory.csv
--rw-r--r--   0 paul      (1000) paul      (1000)        1 2023-04-26 17:02:44.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/deforestation/transitions.csv
-drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-06 14:52:38.111122 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/mgmt/
--rw-r--r--   0 paul      (1000) paul      (1000)     3418 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/mgmt/events.csv
--rw-r--r--   0 paul      (1000) paul      (1000)    13415 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/mgmt/growth_curves.csv
--rw-r--r--   0 paul      (1000) paul      (1000)     6835 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/mgmt/inventory.csv
--rw-r--r--   0 paul      (1000) paul      (1000)      843 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/mgmt/transitions.csv
-drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-06 14:52:38.111122 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/nd_nsr/
--rw-r--r--   0 paul      (1000) paul      (1000)        1 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/nd_nsr/events.csv
--rw-r--r--   0 paul      (1000) paul      (1000)        1 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/nd_nsr/growth_curves.csv
--rw-r--r--   0 paul      (1000) paul      (1000)        0 2023-04-26 17:02:44.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/nd_nsr/inventory.csv
--rw-r--r--   0 paul      (1000) paul      (1000)        1 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/nd_nsr/transitions.csv
-drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-06 14:52:38.111122 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/nd_sr/
--rw-r--r--   0 paul      (1000) paul      (1000)     1649 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/nd_sr/events.csv
--rw-r--r--   0 paul      (1000) paul      (1000)        1 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/nd_sr/growth_curves.csv
--rw-r--r--   0 paul      (1000) paul      (1000)        0 2023-04-26 17:02:44.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/nd_sr/inventory.csv
--rw-r--r--   0 paul      (1000) paul      (1000)      631 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/nd_sr/transitions.csv
-drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-06 14:52:38.115122 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/common/
--rw-r--r--   0 paul      (1000) paul      (1000)      586 2023-04-26 17:02:44.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/common/age_classes.csv
--rw-r--r--   0 paul      (1000) paul      (1000)      833 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/common/classifiers.csv
--rw-r--r--   0 paul      (1000) paul      (1000)      585 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/common/disturbance_types.csv
-drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-06 14:52:38.115122 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/config/
--rw-r--r--   0 paul      (1000) paul      (1000)     2098 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/config/associations.csv
-drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-06 14:52:38.115122 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/silv/
--rw-r--r--   0 paul      (1000) paul      (1000)     6303 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/silv/events_templates.csv
--rw-r--r--   0 paul      (1000) paul      (1000)     2632 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/silv/harvest_factors.csv
--rw-r--r--   0 paul      (1000) paul      (1000)     4603 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/silv/irw_frac_by_dist.csv
--rw-r--r--   0 paul      (1000) paul      (1000)      104 2023-04-26 17:02:44.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/silv/vol_to_mass_coefs.csv
-drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-06 14:52:38.099122 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/domestic_harvest/
-drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-06 14:52:38.115122 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/domestic_harvest/reference/
--rw-r--r--   0 paul      (1000) paul      (1000)   145505 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/domestic_harvest/reference/fw_harvest.csv
--rw-r--r--   0 paul      (1000) paul      (1000)   134895 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/domestic_harvest/reference/irw_harvest.csv
--rw-r--r--   0 paul      (1000) paul      (1000)      299 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/test_qaqc.py
--rw-r--r--   0 paul      (1000) paul      (1000)     1489 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/test_salvage.py
--rw-r--r--   0 paul      (1000) paul      (1000)     2041 2023-02-14 09:33:00.000000 eu_cbm_hat-0.6.3/eu_cbm_hat/tests/test_silviculture.py
-drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-06 14:52:38.103122 eu_cbm_hat-0.6.3/eu_cbm_hat.egg-info/
--rw-r--r--   0 paul      (1000) paul      (1000)     8078 2023-06-06 14:52:38.000000 eu_cbm_hat-0.6.3/eu_cbm_hat.egg-info/PKG-INFO
--rw-r--r--   0 paul      (1000) paul      (1000)     4904 2023-06-06 14:52:38.000000 eu_cbm_hat-0.6.3/eu_cbm_hat.egg-info/SOURCES.txt
--rw-r--r--   0 paul      (1000) paul      (1000)        1 2023-06-06 14:52:38.000000 eu_cbm_hat-0.6.3/eu_cbm_hat.egg-info/dependency_links.txt
--rw-r--r--   0 paul      (1000) paul      (1000)      134 2023-06-06 14:52:38.000000 eu_cbm_hat-0.6.3/eu_cbm_hat.egg-info/requires.txt
--rw-r--r--   0 paul      (1000) paul      (1000)       46 2023-06-06 14:52:38.000000 eu_cbm_hat-0.6.3/eu_cbm_hat.egg-info/top_level.txt
-drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-06 14:52:38.099122 eu_cbm_hat-0.6.3/scripts/
-drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-06 14:52:38.115122 eu_cbm_hat-0.6.3/scripts/conversion/
--rw-r--r--   0 paul      (1000) paul      (1000)     5120 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/scripts/conversion/add_indicators_to_aidb.py
--rw-r--r--   0 paul      (1000) paul      (1000)     4140 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/scripts/conversion/convert_aidb.py
--rw-r--r--   0 paul      (1000) paul      (1000)     2355 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/scripts/conversion/merge_growth_curves.py
--rw-r--r--   0 paul      (1000) paul      (1000)     1765 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/scripts/conversion/rename_all_classifiers.py
--rw-r--r--   0 paul      (1000) paul      (1000)     1436 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/scripts/conversion/rename_associations.py
--rw-r--r--   0 paul      (1000) paul      (1000)     1954 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/scripts/conversion/update_input_classif.py
-drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-06 14:52:38.119122 eu_cbm_hat-0.6.3/scripts/running/
--rw-r--r--   0 paul      (1000) paul      (1000)      718 2023-05-31 09:20:18.000000 eu_cbm_hat-0.6.3/scripts/running/run_at.py
--rw-r--r--   0 paul      (1000) paul      (1000)      607 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/scripts/running/run_ee.py
--rw-r--r--   0 paul      (1000) paul      (1000)      454 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/scripts/running/run_fi.py
--rw-r--r--   0 paul      (1000) paul      (1000)      542 2023-06-05 13:51:32.000000 eu_cbm_hat-0.6.3/scripts/running/run_fr.py
--rw-r--r--   0 paul      (1000) paul      (1000)      607 2023-05-16 15:21:25.000000 eu_cbm_hat-0.6.3/scripts/running/run_hu.py
--rw-r--r--   0 paul      (1000) paul      (1000)     1059 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/scripts/running/run_lu.py
--rw-r--r--   0 paul      (1000) paul      (1000)      526 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/scripts/running/run_se.py
--rw-r--r--   0 paul      (1000) paul      (1000)      607 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/scripts/running/run_si.py
--rw-r--r--   0 paul      (1000) paul      (1000)     1353 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/scripts/running/run_zz.py
--rw-r--r--   0 paul      (1000) paul      (1000)     1542 2022-12-07 10:05:35.000000 eu_cbm_hat-0.6.3/scripts/running/run_zz_in_temp_dir_without_eu_cbm_data.py
-drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-06 14:52:38.123123 eu_cbm_hat-0.6.3/scripts/setup/
--rw-r--r--   0 paul      (1000) paul      (1000)    11109 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/scripts/setup/activities_creation.py
--rw-r--r--   0 paul      (1000) paul      (1000)      463 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/scripts/setup/aidb_symlink.py
--rw-r--r--   0 paul      (1000) paul      (1000)     2711 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.3/scripts/setup/copy_zz_from_libcbm_data.py
--rw-r--r--   0 paul      (1000) paul      (1000)      572 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/scripts/setup/make_interface.py
--rw-r--r--   0 paul      (1000) paul      (1000)      572 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.3/scripts/setup/save_interface.py
--rw-r--r--   0 paul      (1000) paul      (1000)       38 2023-06-06 14:52:38.123123 eu_cbm_hat-0.6.3/setup.cfg
--rw-r--r--   0 paul      (1000) paul      (1000)     1436 2023-06-06 14:47:43.000000 eu_cbm_hat-0.6.3/setup.py
+drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-28 10:15:34.336535 eu_cbm_hat-0.6.4/
+-rw-r--r--   0 paul      (1000) paul      (1000)    13862 2022-12-07 14:55:14.000000 eu_cbm_hat-0.6.4/LICENCE.txt
+-rw-r--r--   0 paul      (1000) paul      (1000)       92 2022-12-07 14:57:34.000000 eu_cbm_hat-0.6.4/MANIFEST.in
+-rw-r--r--   0 paul      (1000) paul      (1000)    57674 2022-12-07 16:29:26.000000 eu_cbm_hat-0.6.4/NOTICE.txt
+-rw-r--r--   0 paul      (1000) paul      (1000)     8078 2023-06-28 10:15:34.336535 eu_cbm_hat-0.6.4/PKG-INFO
+-rw-r--r--   0 paul      (1000) paul      (1000)     7649 2023-05-16 17:40:14.000000 eu_cbm_hat-0.6.4/README.md
+drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-28 10:15:34.300535 eu_cbm_hat-0.6.4/eu_cbm_hat/
+-rw-r--r--   0 paul      (1000) paul      (1000)     1618 2023-06-28 10:15:02.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/__init__.py
+drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-28 10:15:34.304535 eu_cbm_hat-0.6.4/eu_cbm_hat/cbm/
+-rw-r--r--   0 paul      (1000) paul      (1000)       72 2022-12-09 09:42:16.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/cbm/__init__.py
+-rw-r--r--   0 paul      (1000) paul      (1000)    31577 2023-06-27 16:23:38.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/cbm/dynamic.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     5853 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/cbm/simulation.py
+drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-28 10:15:34.308535 eu_cbm_hat-0.6.4/eu_cbm_hat/combos/
+-rw-r--r--   0 paul      (1000) paul      (1000)     3604 2023-06-20 08:59:59.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/combos/__init__.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     5199 2023-06-20 14:08:29.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/combos/base_combo.py
+-rw-r--r--   0 paul      (1000) paul      (1000)      905 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/combos/harvest_test.py
+-rw-r--r--   0 paul      (1000) paul      (1000)      825 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/combos/hat.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     2091 2022-12-07 10:05:35.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/combos/historical.py
+-rw-r--r--   0 paul      (1000) paul      (1000)      833 2023-06-20 07:57:49.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/combos/ia_2040.py
+-rw-r--r--   0 paul      (1000) paul      (1000)      791 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/combos/no_market_forcing.py
+-rw-r--r--   0 paul      (1000) paul      (1000)      719 2023-06-20 08:23:58.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/combos/pikbau.py
+-rw-r--r--   0 paul      (1000) paul      (1000)      721 2023-06-20 08:01:12.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/combos/pikfair.py
+-rw-r--r--   0 paul      (1000) paul      (1000)      793 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/combos/potencia_baseline.py
+-rw-r--r--   0 paul      (1000) paul      (1000)      805 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/combos/potencia_necp_bme_up100.py
+-rw-r--r--   0 paul      (1000) paul      (1000)      805 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/combos/potencia_necp_bme_up200.py
+-rw-r--r--   0 paul      (1000) paul      (1000)      807 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/combos/potencia_necp_bms_down50.py
+-rw-r--r--   0 paul      (1000) paul      (1000)      807 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/combos/potencia_necp_bms_down90.py
+-rw-r--r--   0 paul      (1000) paul      (1000)      777 2023-02-14 09:33:00.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/combos/reference.py
+-rw-r--r--   0 paul      (1000) paul      (1000)      845 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/combos/reference_crf.py
+-rw-r--r--   0 paul      (1000) paul      (1000)      835 2022-12-21 16:03:35.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/combos/skewfcth.py
+-rw-r--r--   0 paul      (1000) paul      (1000)      818 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/combos/special.py
+drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-28 10:15:34.312535 eu_cbm_hat-0.6.4/eu_cbm_hat/core/
+-rw-r--r--   0 paul      (1000) paul      (1000)      618 2022-12-09 09:35:23.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/core/__init__.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     2743 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/core/continent.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     5672 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/core/country.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     8949 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/core/runner.py
+drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-28 10:15:34.312535 eu_cbm_hat-0.6.4/eu_cbm_hat/info/
+-rw-r--r--   0 paul      (1000) paul      (1000)        0 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/info/__init__.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     5226 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/info/aidb.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     5983 2022-12-15 15:55:50.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/info/fluxes.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     5456 2022-12-07 10:05:35.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/info/harvest.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     5224 2023-05-16 16:03:15.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/info/input_data.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     2573 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/info/internal_data.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     4019 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/info/orig_data.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     7534 2023-06-26 11:09:26.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/info/output_data.py
+-rw-r--r--   0 paul      (1000) paul      (1000)    14668 2022-12-15 16:30:06.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/info/silviculture.py
+drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-28 10:15:34.312535 eu_cbm_hat-0.6.4/eu_cbm_hat/launch/
+-rw-r--r--   0 paul      (1000) paul      (1000)      167 2022-12-09 09:56:16.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/launch/__init__.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     3287 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/launch/associations.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     3743 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/launch/create_json.py
+drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-28 10:15:34.316535 eu_cbm_hat-0.6.4/eu_cbm_hat/pump/
+-rw-r--r--   0 paul      (1000) paul      (1000)       84 2022-12-09 10:01:44.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/pump/__init__.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     1059 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/pump/classifiers.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     1401 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/pump/column_order.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     3287 2023-05-16 16:06:20.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/pump/long_or_wide.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     1803 2023-06-26 16:35:35.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/pump/post_processor.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     3659 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/pump/pre_processor.py
+drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-28 10:15:34.316535 eu_cbm_hat-0.6.4/eu_cbm_hat/qaqc/
+-rw-r--r--   0 paul      (1000) paul      (1000)     1150 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/qaqc/__init__.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     1694 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/qaqc/aidb.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     7382 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/qaqc/expected_provided.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     3226 2022-12-07 10:05:35.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/qaqc/input_years.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     5958 2022-12-15 15:59:43.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/qaqc/silviculture.py
+drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-28 10:15:34.320535 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/
+-rw-r--r--   0 paul      (1000) paul      (1000)      895 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/copy_data.py
+drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-28 10:15:34.300535 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/
+drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-28 10:15:34.320535 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/combos/
+-rw-r--r--   0 paul      (1000) paul      (1000)     3775 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/combos/reference.yaml
+drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-28 10:15:34.320535 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/common/
+-rw-r--r--   0 paul      (1000) paul      (1000)      999 2023-04-26 17:02:44.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/common/country_codes.csv
+-rw-r--r--   0 paul      (1000) paul      (1000)      267 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/common/reference_years.csv
+drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-28 10:15:34.296535 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/
+drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-28 10:15:34.300535 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/
+drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-28 10:15:34.300535 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/
+drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-28 10:15:34.320535 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/afforestation/
+-rw-r--r--   0 paul      (1000) paul      (1000)        1 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/afforestation/events.csv
+-rw-r--r--   0 paul      (1000) paul      (1000)        1 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/afforestation/growth_curves.csv
+-rw-r--r--   0 paul      (1000) paul      (1000)        1 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/afforestation/inventory.csv
+-rw-r--r--   0 paul      (1000) paul      (1000)        1 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/afforestation/transitions.csv
+drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-28 10:15:34.324535 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/deforestation/
+-rw-r--r--   0 paul      (1000) paul      (1000)        1 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/deforestation/events.csv
+-rw-r--r--   0 paul      (1000) paul      (1000)        0 2023-04-26 17:02:44.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/deforestation/growth_curves.csv
+-rw-r--r--   0 paul      (1000) paul      (1000)        0 2023-04-26 17:02:44.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/deforestation/inventory.csv
+-rw-r--r--   0 paul      (1000) paul      (1000)        1 2023-04-26 17:02:44.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/deforestation/transitions.csv
+drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-28 10:15:34.324535 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/mgmt/
+-rw-r--r--   0 paul      (1000) paul      (1000)     3418 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/mgmt/events.csv
+-rw-r--r--   0 paul      (1000) paul      (1000)    13415 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/mgmt/growth_curves.csv
+-rw-r--r--   0 paul      (1000) paul      (1000)     6835 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/mgmt/inventory.csv
+-rw-r--r--   0 paul      (1000) paul      (1000)      843 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/mgmt/transitions.csv
+drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-28 10:15:34.324535 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/nd_nsr/
+-rw-r--r--   0 paul      (1000) paul      (1000)        1 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/nd_nsr/events.csv
+-rw-r--r--   0 paul      (1000) paul      (1000)        1 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/nd_nsr/growth_curves.csv
+-rw-r--r--   0 paul      (1000) paul      (1000)        0 2023-04-26 17:02:44.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/nd_nsr/inventory.csv
+-rw-r--r--   0 paul      (1000) paul      (1000)        1 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/nd_nsr/transitions.csv
+drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-28 10:15:34.324535 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/nd_sr/
+-rw-r--r--   0 paul      (1000) paul      (1000)     1649 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/nd_sr/events.csv
+-rw-r--r--   0 paul      (1000) paul      (1000)        1 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/nd_sr/growth_curves.csv
+-rw-r--r--   0 paul      (1000) paul      (1000)        0 2023-04-26 17:02:44.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/nd_sr/inventory.csv
+-rw-r--r--   0 paul      (1000) paul      (1000)      631 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/nd_sr/transitions.csv
+drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-28 10:15:34.328535 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/common/
+-rw-r--r--   0 paul      (1000) paul      (1000)      586 2023-04-26 17:02:44.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/common/age_classes.csv
+-rw-r--r--   0 paul      (1000) paul      (1000)      833 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/common/classifiers.csv
+-rw-r--r--   0 paul      (1000) paul      (1000)      585 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/common/disturbance_types.csv
+drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-28 10:15:34.328535 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/config/
+-rw-r--r--   0 paul      (1000) paul      (1000)     2098 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/config/associations.csv
+drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-28 10:15:34.328535 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/silv/
+-rw-r--r--   0 paul      (1000) paul      (1000)     6303 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/silv/events_templates.csv
+-rw-r--r--   0 paul      (1000) paul      (1000)     2632 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/silv/harvest_factors.csv
+-rw-r--r--   0 paul      (1000) paul      (1000)     4603 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/silv/irw_frac_by_dist.csv
+-rw-r--r--   0 paul      (1000) paul      (1000)      104 2023-04-26 17:02:44.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/silv/vol_to_mass_coefs.csv
+drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-28 10:15:34.300535 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/domestic_harvest/
+drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-28 10:15:34.328535 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/domestic_harvest/reference/
+-rw-r--r--   0 paul      (1000) paul      (1000)   145505 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/domestic_harvest/reference/fw_harvest.csv
+-rw-r--r--   0 paul      (1000) paul      (1000)   134895 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/domestic_harvest/reference/irw_harvest.csv
+-rw-r--r--   0 paul      (1000) paul      (1000)      299 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/test_qaqc.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     1489 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/test_salvage.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     2041 2023-02-14 09:33:00.000000 eu_cbm_hat-0.6.4/eu_cbm_hat/tests/test_silviculture.py
+drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-28 10:15:34.304535 eu_cbm_hat-0.6.4/eu_cbm_hat.egg-info/
+-rw-r--r--   0 paul      (1000) paul      (1000)     8078 2023-06-28 10:15:34.000000 eu_cbm_hat-0.6.4/eu_cbm_hat.egg-info/PKG-INFO
+-rw-r--r--   0 paul      (1000) paul      (1000)     5028 2023-06-28 10:15:34.000000 eu_cbm_hat-0.6.4/eu_cbm_hat.egg-info/SOURCES.txt
+-rw-r--r--   0 paul      (1000) paul      (1000)        1 2023-06-28 10:15:34.000000 eu_cbm_hat-0.6.4/eu_cbm_hat.egg-info/dependency_links.txt
+-rw-r--r--   0 paul      (1000) paul      (1000)      134 2023-06-28 10:15:34.000000 eu_cbm_hat-0.6.4/eu_cbm_hat.egg-info/requires.txt
+-rw-r--r--   0 paul      (1000) paul      (1000)       46 2023-06-28 10:15:34.000000 eu_cbm_hat-0.6.4/eu_cbm_hat.egg-info/top_level.txt
+drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-28 10:15:34.300535 eu_cbm_hat-0.6.4/scripts/
+drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-28 10:15:34.332535 eu_cbm_hat-0.6.4/scripts/conversion/
+-rw-r--r--   0 paul      (1000) paul      (1000)     5120 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/scripts/conversion/add_indicators_to_aidb.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     4140 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/scripts/conversion/convert_aidb.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     2355 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/scripts/conversion/merge_growth_curves.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     1765 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/scripts/conversion/rename_all_classifiers.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     1436 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/scripts/conversion/rename_associations.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     1954 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/scripts/conversion/update_input_classif.py
+drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-28 10:15:34.332535 eu_cbm_hat-0.6.4/scripts/running/
+-rw-r--r--   0 paul      (1000) paul      (1000)      718 2023-05-31 09:20:18.000000 eu_cbm_hat-0.6.4/scripts/running/run_at.py
+-rw-r--r--   0 paul      (1000) paul      (1000)      648 2023-06-20 09:22:23.000000 eu_cbm_hat-0.6.4/scripts/running/run_ee.py
+-rw-r--r--   0 paul      (1000) paul      (1000)      454 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/scripts/running/run_fi.py
+-rw-r--r--   0 paul      (1000) paul      (1000)      542 2023-06-05 13:51:32.000000 eu_cbm_hat-0.6.4/scripts/running/run_fr.py
+-rw-r--r--   0 paul      (1000) paul      (1000)      607 2023-05-16 15:21:25.000000 eu_cbm_hat-0.6.4/scripts/running/run_hu.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     1059 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/scripts/running/run_lu.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     2208 2023-06-21 16:44:21.000000 eu_cbm_hat-0.6.4/scripts/running/run_scenario_combo.py
+-rw-r--r--   0 paul      (1000) paul      (1000)      539 2023-06-27 15:03:33.000000 eu_cbm_hat-0.6.4/scripts/running/run_se.py
+-rw-r--r--   0 paul      (1000) paul      (1000)      607 2023-06-27 15:04:10.000000 eu_cbm_hat-0.6.4/scripts/running/run_si.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     1353 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/scripts/running/run_zz.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     1542 2022-12-07 10:05:35.000000 eu_cbm_hat-0.6.4/scripts/running/run_zz_in_temp_dir_without_eu_cbm_data.py
+drwxr-xr-x   0 paul      (1000) paul      (1000)        0 2023-06-28 10:15:34.336535 eu_cbm_hat-0.6.4/scripts/setup/
+-rw-r--r--   0 paul      (1000) paul      (1000)    11109 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/scripts/setup/activities_creation.py
+-rw-r--r--   0 paul      (1000) paul      (1000)      463 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/scripts/setup/aidb_symlink.py
+-rw-r--r--   0 paul      (1000) paul      (1000)     2711 2023-05-04 16:10:28.000000 eu_cbm_hat-0.6.4/scripts/setup/copy_zz_from_libcbm_data.py
+-rw-r--r--   0 paul      (1000) paul      (1000)      572 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/scripts/setup/make_interface.py
+-rw-r--r--   0 paul      (1000) paul      (1000)      572 2022-11-24 14:36:18.000000 eu_cbm_hat-0.6.4/scripts/setup/save_interface.py
+-rw-r--r--   0 paul      (1000) paul      (1000)       38 2023-06-28 10:15:34.336535 eu_cbm_hat-0.6.4/setup.cfg
+-rw-r--r--   0 paul      (1000) paul      (1000)     1436 2023-06-28 10:15:02.000000 eu_cbm_hat-0.6.4/setup.py
```

### Comparing `eu_cbm_hat-0.6.3/LICENCE.txt` & `eu_cbm_hat-0.6.4/LICENCE.txt`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/NOTICE.txt` & `eu_cbm_hat-0.6.4/NOTICE.txt`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/PKG-INFO` & `eu_cbm_hat-0.6.4/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: eu_cbm_hat
-Version: 0.6.3
+Version: 0.6.4
 Summary: eu_cbm_hat is a python package for running carbon budget simulations.
 Home-page: https://gitlab.com/bioeconomy/eu_cbm/eu_cbm_hat
 Author: Lucas Sinclair
 Author-email: lucas.sinclair@me.com
 Maintainer: Paul Rougieux
 License: EUPL
 Requires-Python: >=3.8
```

### Comparing `eu_cbm_hat-0.6.3/README.md` & `eu_cbm_hat-0.6.4/README.md`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/__init__.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/__init__.py`

 * *Files 1% similar despite different names*

```diff
@@ -13,15 +13,15 @@
 feedback under [issue
 50](https://gitlab.com/bioeconomy/eu_cbm/eu_cbm_hat/-/issues/50) ).
 - The Harvest Allocation Tool is implemented in `eu_cbm_hat.cbm.dynamic`.
 
 """
 
 # Special variables #
-__version__ = '0.6.3'
+__version__ = '0.6.4'
 
 # Built-in modules #
 import os, sys
 
 # First party modules #
 from autopaths import Path
 from autopaths.dir_path import DirectoryPath
```

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/cbm/dynamic.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/cbm/dynamic.py`

 * *Files 2% similar despite different names*

```diff
@@ -422,19 +422,36 @@
 
             # Only one of the columns matches the current year #
             harvest = harvest.rename(columns = {'value_%i' % self.year: 'skew'})
 
             # Keep only IRW coefficients
             harvest = harvest[harvest["product_created"] == "irw_and_fw"]
 
+
             # Keep only the columns that are not empty as join columns
             harvest_join_cols = []
             for col in self.runner.silv.harvest.cols:
                 if not any(harvest[col].isna()):
                     harvest_join_cols.append(col)
+            harvest = harvest[harvest_join_cols + ['skew']]
+
+            # Check if all rows for which a skew factor is defined are really
+            # present in df_irw_silv
+            df_irw_silv_check = df_irw_silv.value_counts(harvest_join_cols).reset_index()
+            if len(df_irw_silv_check) < len(harvest):
+                msg += "Some skew factors are present in harvest but not present in "
+                msg += "df_irw_silv. This might happen in rare cases where there is only "
+                msg += "coniferous forest available and no broadleaf forest available. "
+                msg += "For example because broadleaves are too young and the "
+                msg += "query('age >= sw_start') excluded those broadleaf rows. "
+                self.parent.log.info(msg)
+                # Recompute the skew
+                harvest2 = df_irw_silv_check.merge(harvest, on=harvest_join_cols)
+                harvest2["skew"] = harvest2["skew"] / harvest2["skew"].sum()
+                harvest = harvest2
 
             # If silv_practice is defined in harvest factors then use
             # self.runner.fluxes.df to add the silv_practice column to
             # df_irw_silv
             if "silv_practice" in harvest_join_cols:
                 df_silv_practice = self.runner.fluxes.df[["disturbance_type", "silv_practice"]]
                 df_irw_silv = df_irw_silv.merge(df_silv_practice, on="disturbance_type")
@@ -447,19 +464,18 @@
                     msg += f"{hfsp}"
                     msg +=  " do not match the ones in disturbance_types.csv: "
                     msg += f"{distsp}"
                     raise ValueError(msg)
 
             # Aggregate the normalized value by groups
             df_irw_silv["irw_norm_agg"] = df_irw_silv.groupby(harvest_join_cols)["irw_norm"].transform(sum)
-            
 
             # Merge disturbances and harvest factors
             df_irw_silv = pandas.merge(df_irw_silv,
-                                       harvest[harvest_join_cols + ['skew']],
+                                       harvest,
                                        how='inner',
                                        on=harvest_join_cols)
 
             # Modify the harvest distribution coefficient by the skew along each grouping variable
             df_irw_silv["irw_norm_skew"] = (df_irw_silv["irw_norm"]
                                             * df_irw_silv["skew"]
                                             / df_irw_silv["irw_norm_agg"])
```

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/cbm/simulation.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/cbm/simulation.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/combos/base_combo.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/combos/base_combo.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,15 +1,16 @@
 #!/usr/bin/env python3
 # -*- coding: utf-8 -*-
 
 """
-Written by Lucas Sinclair and Paul Rougieux.
+Written by Lucas Sinclair, Paul Rougieux and Viorel Blujdea.
 
 JRC Biomass Project.
 Unit D1 Bioeconomy.
+
 """
 
 # Built-in modules #
 import textwrap
 
 # Third party modules #
 import yaml, pandas
```

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/combos/harvest_test.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/combos/harvest_test.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/combos/hat.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/combos/hat.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/combos/historical.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/combos/historical.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/combos/no_market_forcing.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/combos/no_market_forcing.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/combos/potencia_baseline.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/combos/potencia_baseline.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/combos/potencia_necp_bme_up100.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/combos/potencia_necp_bme_up100.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/combos/potencia_necp_bme_up200.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/combos/potencia_necp_bme_up200.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/combos/potencia_necp_bms_down50.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/combos/potencia_necp_bms_down50.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/combos/potencia_necp_bms_down90.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/combos/potencia_necp_bms_down90.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/combos/reference.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/combos/reference.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/combos/reference_crf.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/combos/reference_crf.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/combos/skewfcth.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/combos/skewfcth.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/combos/special.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/combos/special.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/core/__init__.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/core/__init__.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/core/continent.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/core/continent.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/core/country.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/core/country.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/core/runner.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/core/runner.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/info/aidb.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/info/aidb.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/info/fluxes.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/info/fluxes.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/info/harvest.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/info/harvest.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/info/input_data.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/info/input_data.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/info/internal_data.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/info/internal_data.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/info/orig_data.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/info/orig_data.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/info/output_data.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/info/output_data.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/info/silviculture.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/info/silviculture.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/launch/associations.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/launch/associations.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/launch/create_json.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/launch/create_json.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/pump/classifiers.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/pump/classifiers.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/pump/column_order.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/pump/column_order.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/pump/long_or_wide.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/pump/long_or_wide.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/pump/pre_processor.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/pump/pre_processor.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/qaqc/__init__.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/qaqc/__init__.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/qaqc/aidb.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/qaqc/aidb.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/qaqc/expected_provided.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/qaqc/expected_provided.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/qaqc/input_years.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/qaqc/input_years.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/qaqc/silviculture.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/qaqc/silviculture.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/tests/copy_data.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/tests/copy_data.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/combos/reference.yaml` & `eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/combos/reference.yaml`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/common/country_codes.csv` & `eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/common/country_codes.csv`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/mgmt/events.csv` & `eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/mgmt/events.csv`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/mgmt/growth_curves.csv` & `eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/mgmt/growth_curves.csv`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/mgmt/inventory.csv` & `eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/mgmt/inventory.csv`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/mgmt/transitions.csv` & `eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/mgmt/transitions.csv`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/nd_sr/events.csv` & `eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/nd_sr/events.csv`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/nd_sr/transitions.csv` & `eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/activities/nd_sr/transitions.csv`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/common/age_classes.csv` & `eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/common/age_classes.csv`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/common/classifiers.csv` & `eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/common/classifiers.csv`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/common/disturbance_types.csv` & `eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/common/disturbance_types.csv`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/config/associations.csv` & `eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/config/associations.csv`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/silv/events_templates.csv` & `eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/silv/events_templates.csv`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/silv/harvest_factors.csv` & `eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/silv/harvest_factors.csv`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/silv/irw_frac_by_dist.csv` & `eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/countries/ZZ/silv/irw_frac_by_dist.csv`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/domestic_harvest/reference/fw_harvest.csv` & `eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/domestic_harvest/reference/fw_harvest.csv`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/tests/eu_cbm_data/domestic_harvest/reference/irw_harvest.csv` & `eu_cbm_hat-0.6.4/eu_cbm_hat/tests/eu_cbm_data/domestic_harvest/reference/irw_harvest.csv`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/tests/test_salvage.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/tests/test_salvage.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat/tests/test_silviculture.py` & `eu_cbm_hat-0.6.4/eu_cbm_hat/tests/test_silviculture.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat.egg-info/PKG-INFO` & `eu_cbm_hat-0.6.4/eu_cbm_hat.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: eu-cbm-hat
-Version: 0.6.3
+Version: 0.6.4
 Summary: eu_cbm_hat is a python package for running carbon budget simulations.
 Home-page: https://gitlab.com/bioeconomy/eu_cbm/eu_cbm_hat
 Author: Lucas Sinclair
 Author-email: lucas.sinclair@me.com
 Maintainer: Paul Rougieux
 License: EUPL
 Requires-Python: >=3.8
```

### Comparing `eu_cbm_hat-0.6.3/eu_cbm_hat.egg-info/SOURCES.txt` & `eu_cbm_hat-0.6.4/eu_cbm_hat.egg-info/SOURCES.txt`

 * *Files 2% similar despite different names*

```diff
@@ -13,15 +13,18 @@
 eu_cbm_hat/cbm/dynamic.py
 eu_cbm_hat/cbm/simulation.py
 eu_cbm_hat/combos/__init__.py
 eu_cbm_hat/combos/base_combo.py
 eu_cbm_hat/combos/harvest_test.py
 eu_cbm_hat/combos/hat.py
 eu_cbm_hat/combos/historical.py
+eu_cbm_hat/combos/ia_2040.py
 eu_cbm_hat/combos/no_market_forcing.py
+eu_cbm_hat/combos/pikbau.py
+eu_cbm_hat/combos/pikfair.py
 eu_cbm_hat/combos/potencia_baseline.py
 eu_cbm_hat/combos/potencia_necp_bme_up100.py
 eu_cbm_hat/combos/potencia_necp_bme_up200.py
 eu_cbm_hat/combos/potencia_necp_bms_down50.py
 eu_cbm_hat/combos/potencia_necp_bms_down90.py
 eu_cbm_hat/combos/reference.py
 eu_cbm_hat/combos/reference_crf.py
@@ -99,14 +102,15 @@
 scripts/conversion/update_input_classif.py
 scripts/running/run_at.py
 scripts/running/run_ee.py
 scripts/running/run_fi.py
 scripts/running/run_fr.py
 scripts/running/run_hu.py
 scripts/running/run_lu.py
+scripts/running/run_scenario_combo.py
 scripts/running/run_se.py
 scripts/running/run_si.py
 scripts/running/run_zz.py
 scripts/running/run_zz_in_temp_dir_without_eu_cbm_data.py
 scripts/setup/activities_creation.py
 scripts/setup/aidb_symlink.py
 scripts/setup/copy_zz_from_libcbm_data.py
```

### Comparing `eu_cbm_hat-0.6.3/scripts/conversion/add_indicators_to_aidb.py` & `eu_cbm_hat-0.6.4/scripts/conversion/add_indicators_to_aidb.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/scripts/conversion/convert_aidb.py` & `eu_cbm_hat-0.6.4/scripts/conversion/convert_aidb.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/scripts/conversion/merge_growth_curves.py` & `eu_cbm_hat-0.6.4/scripts/conversion/merge_growth_curves.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/scripts/conversion/rename_all_classifiers.py` & `eu_cbm_hat-0.6.4/scripts/conversion/rename_all_classifiers.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/scripts/conversion/rename_associations.py` & `eu_cbm_hat-0.6.4/scripts/conversion/rename_associations.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/scripts/conversion/update_input_classif.py` & `eu_cbm_hat-0.6.4/scripts/conversion/update_input_classif.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/scripts/running/run_at.py` & `eu_cbm_hat-0.6.4/scripts/running/run_at.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/scripts/running/run_ee.py` & `eu_cbm_hat-0.6.4/scripts/running/run_hu.py`

 * *Files 2% similar despite different names*

```diff
@@ -2,26 +2,26 @@
 # -*- coding: utf-8 -*-
 
 """
 A script to run Slovenia
 
 Typically you would run this file from a command line like this:
 
-     ipython3 -i -- ~/repos/eu_cbm/eu_cbm_hat/scripts/running/run_ee.py
+     ipython3 -i -- ~/repos/eu_cbm/eu_cbm_hat/scripts/running/run_hu.py
 
 """
 
 from eu_cbm_hat.core.continent import continent
 
 
 #############################################
 # Declare which scenario combination to run #
 #############################################
 combo   = continent.combos['reference']
-runner  = combo.runners['EE'][-1]
+runner  = combo.runners['HU'][-1]
 runner.num_timesteps = 25
 
 # Run the model
 output = runner.run(keep_in_ram=True, verbose=True, interrupt_on_error=True)
```

### Comparing `eu_cbm_hat-0.6.3/scripts/running/run_fr.py` & `eu_cbm_hat-0.6.4/scripts/running/run_fr.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/scripts/running/run_hu.py` & `eu_cbm_hat-0.6.4/scripts/running/run_si.py`

 * *Files 4% similar despite different names*

```diff
@@ -2,26 +2,26 @@
 # -*- coding: utf-8 -*-
 
 """
 A script to run Slovenia
 
 Typically you would run this file from a command line like this:
 
-     ipython3 -i -- ~/repos/eu_cbm/eu_cbm_hat/scripts/running/run_hu.py
+     ipython3 -i -- ~/repos/eu_cbm/eu_cbm_hat/scripts/running/run_si.py
 
 """
 
 from eu_cbm_hat.core.continent import continent
 
 
 #############################################
 # Declare which scenario combination to run #
 #############################################
 combo   = continent.combos['reference']
-runner  = combo.runners['HU'][-1]
-runner.num_timesteps = 25
+runner  = combo.runners['SI'][-1]
+runner.num_timesteps = 50
 
 # Run the model
 output = runner.run(keep_in_ram=True, verbose=True, interrupt_on_error=True)
```

### Comparing `eu_cbm_hat-0.6.3/scripts/running/run_lu.py` & `eu_cbm_hat-0.6.4/scripts/running/run_lu.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/scripts/running/run_se.py` & `eu_cbm_hat-0.6.4/scripts/running/run_se.py`

 * *Files 22% similar despite different names*

```diff
@@ -1,19 +1,19 @@
 #!/usr/bin/env python3
 # -*- coding: utf-8 -*-
 """
 A script to run Sweden.
 
 Typically you would run this file from a command line like this:
 
-     ipython3 -i -- ~/deploy/eu_cbm_hat/scripts/running/run_se.py
+     ipython3 -i -- ~/deploy/eu_cbm/eu_cbm_hat/scripts/running/run_se.py
 """
 
 from eu_cbm_hat.core.continent import continent
-runner = continent.combos['hat'].runners['SE'][-1]
-runner.num_timesteps = 40
+runner = continent.combos['reference'].runners['SE'][-1]
+runner.num_timesteps = 50
 
 # Run the model
 runner.run(keep_in_ram=True, verbose=True, interrupt_on_error=True)
 
 # Check expected provided
 runner.qaqc.expected_provided.by(index=["forest_type", "disturbance_type"])
```

### Comparing `eu_cbm_hat-0.6.3/scripts/running/run_si.py` & `eu_cbm_hat-0.6.4/scripts/running/run_ee.py`

 * *Files 10% similar despite different names*

```diff
@@ -2,26 +2,26 @@
 # -*- coding: utf-8 -*-
 
 """
 A script to run Slovenia
 
 Typically you would run this file from a command line like this:
 
-     ipython3 -i -- ~/repos/eu_cbm/eu_cbm_hat/scripts/running/run_si.py
+     ipython3 -i -- ~/repos/eu_cbm/eu_cbm_hat/scripts/running/run_ee.py
 
 """
 
 from eu_cbm_hat.core.continent import continent
 
 
 #############################################
 # Declare which scenario combination to run #
 #############################################
 combo   = continent.combos['reference']
-runner  = combo.runners['SI'][-1]
-runner.num_timesteps = 25
+runner  = combo.runners['EE'][-1]
+runner.num_timesteps = 2050 -  runner.country.inventory_start_year
 
 # Run the model
 output = runner.run(keep_in_ram=True, verbose=True, interrupt_on_error=True)
```

### Comparing `eu_cbm_hat-0.6.3/scripts/running/run_zz.py` & `eu_cbm_hat-0.6.4/scripts/running/run_zz.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/scripts/running/run_zz_in_temp_dir_without_eu_cbm_data.py` & `eu_cbm_hat-0.6.4/scripts/running/run_zz_in_temp_dir_without_eu_cbm_data.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/scripts/setup/activities_creation.py` & `eu_cbm_hat-0.6.4/scripts/setup/activities_creation.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/scripts/setup/copy_zz_from_libcbm_data.py` & `eu_cbm_hat-0.6.4/scripts/setup/copy_zz_from_libcbm_data.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/scripts/setup/make_interface.py` & `eu_cbm_hat-0.6.4/scripts/setup/make_interface.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/scripts/setup/save_interface.py` & `eu_cbm_hat-0.6.4/scripts/setup/save_interface.py`

 * *Files identical despite different names*

### Comparing `eu_cbm_hat-0.6.3/setup.py` & `eu_cbm_hat-0.6.4/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -16,15 +16,15 @@
 this_dir = path.abspath(path.dirname(__file__))
 readme_path = path.join(this_dir, 'README.md')
 with open(readme_path, encoding='utf-8') as handle: readme = handle.read()
 
 # Call setup #
 setup(
     name             = 'eu_cbm_hat',
-    version          = '0.6.3',
+    version          = '0.6.4',
     description      = 'eu_cbm_hat is a python package for running carbon'
                        ' budget simulations.',
     license          = 'EUPL',
     url              = 'https://gitlab.com/bioeconomy/eu_cbm/eu_cbm_hat',
     author           = 'Lucas Sinclair',
     author_email     = 'lucas.sinclair@me.com',
     maintainer       = 'Paul Rougieux',
```


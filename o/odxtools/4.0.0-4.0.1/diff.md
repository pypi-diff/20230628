# Comparing `tmp/odxtools-4.0.0.tar.gz` & `tmp/odxtools-4.0.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "odxtools-4.0.0.tar", last modified: Wed Jun 21 06:52:47 2023, max compression
+gzip compressed data, was "odxtools-4.0.1.tar", last modified: Wed Jun 28 12:36:24 2023, max compression
```

## Comparing `odxtools-4.0.0.tar` & `odxtools-4.0.1.tar`

### file list

```diff
@@ -1,127 +1,127 @@
-drwxr-xr-x   0 odxtools  (1002) odxtools  (1002)        0 2023-06-21 06:52:47.406999 odxtools-4.0.0/
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1069 2022-03-09 15:55:44.000000 odxtools-4.0.0/LICENSE
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)    23581 2023-06-21 06:52:47.406999 odxtools-4.0.0/PKG-INFO
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)    22767 2022-12-12 08:24:18.000000 odxtools-4.0.0/README.md
-drwxr-xr-x   0 odxtools  (1002) odxtools  (1002)        0 2023-06-21 06:52:47.386999 odxtools-4.0.0/examples/
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)       65 2023-01-27 13:39:15.000000 odxtools-4.0.0/examples/__init__.py
--rwxr-xr-x   0 odxtools  (1002) odxtools  (1002)     1686 2023-06-21 06:52:15.000000 odxtools-4.0.0/examples/isotp_send.py
--rwxr-xr-x   0 odxtools  (1002) odxtools  (1002)      811 2023-01-27 13:39:15.000000 odxtools-4.0.0/examples/mksomersaultpdx.py
--rwxr-xr-x   0 odxtools  (1002) odxtools  (1002)     1612 2023-01-27 13:39:15.000000 odxtools-4.0.0/examples/pdxcopy.py
--rwxr-xr-x   0 odxtools  (1002) odxtools  (1002)    77899 2023-06-21 06:52:15.000000 odxtools-4.0.0/examples/somersaultecu.py
--rwxr-xr-x   0 odxtools  (1002) odxtools  (1002)    19444 2023-01-27 13:39:15.000000 odxtools-4.0.0/examples/somersaultlazy.py
-drwxr-xr-x   0 odxtools  (1002) odxtools  (1002)        0 2023-06-21 06:52:47.394999 odxtools-4.0.0/odxtools/
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     2925 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/__init__.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)      153 2023-01-13 13:17:58.000000 odxtools-4.0.0/odxtools/__main__.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     7853 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/admindata.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     4267 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/audience.py
-drwxr-xr-x   0 odxtools  (1002) odxtools  (1002)        0 2023-06-21 06:52:47.398999 odxtools-4.0.0/odxtools/cli/
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)      140 2023-01-13 13:17:58.000000 odxtools-4.0.0/odxtools/cli/__init__.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)      549 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/cli/_parser_utils.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     3287 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/cli/_print_utils.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)    14094 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/cli/browse.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1171 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/cli/dummy_sub_parser.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     5974 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/cli/find.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     6728 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/cli/list.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1809 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/cli/main.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     7471 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/cli/snoop.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     5302 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/communicationparameter.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     8722 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/companydata.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)    11567 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/comparam_subset.py
-drwxr-xr-x   0 odxtools  (1002) odxtools  (1002)        0 2023-06-21 06:52:47.402999 odxtools-4.0.0/odxtools/compumethods/
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)      840 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/compumethods/__init__.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)      894 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/compumethods/compumethodbase.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)      210 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/compumethods/compurationalcoeffs.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1489 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/compumethods/compuscale.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     7485 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/compumethods/createanycompumethod.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)      843 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/compumethods/identicalcompumethod.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     2531 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/compumethods/limit.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     8228 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/compumethods/linearcompumethod.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1692 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/compumethods/scalelinearcompumethod.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     6252 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/compumethods/tabintpcompumethod.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     2502 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/compumethods/texttablecompumethod.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     5667 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/database.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)    15371 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/dataobjectproperty.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)      699 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/decodestate.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)    27425 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/diagcodedtypes.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     6643 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/diagdatadictionaryspec.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)    38635 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/diaglayer.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     5957 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/diaglayercontainer.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)    11411 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/diaglayerraw.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)      908 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/diaglayertype.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     6946 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/ecu_variant_matcher.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     3427 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/ecu_variant_patterns.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1190 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/encodestate.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     7285 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/endofpdufield.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     2429 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/envdata.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     5382 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/envdatadesc.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)      549 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/exceptions.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1249 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/functionalclass.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)      173 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/globals.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)    12104 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/isotp_state_machine.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)      452 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/load_file.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)      310 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/load_odx_d_file.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)      334 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/load_pdx_file.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)      963 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/message.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)    12896 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/multiplexer.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     4185 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/nameditemlist.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1209 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/obd.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     8438 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/odxlink.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     3469 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/odxtypes.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     3467 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/parameter_info.py
-drwxr-xr-x   0 odxtools  (1002) odxtools  (1002)        0 2023-06-21 06:52:47.406999 odxtools-4.0.0/odxtools/parameters/
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)      832 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/parameters/__init__.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     4330 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/parameters/codedconstparameter.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     9282 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/parameters/createanyparameter.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1566 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/parameters/dynamicparameter.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1387 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/parameters/lengthkeyparameter.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     2970 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/parameters/matchingrequestparameter.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     4851 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/parameters/nrcconstparameter.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     7208 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/parameters/parameterbase.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     4022 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/parameters/parameterwithdop.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     3263 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/parameters/physicalconstantparameter.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     2787 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/parameters/reservedparameter.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1805 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/parameters/systemparameter.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1090 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/parameters/tableentryparameter.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     2565 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/parameters/tablekeyparameter.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1230 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/parameters/tablestructparameter.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     3130 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/parameters/valueparameter.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     3304 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/parentref.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     2372 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/physicaltype.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)    13653 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/service.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)    16374 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/singleecujob.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     5290 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/specialdata.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1234 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/state.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     3495 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/statechart.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     2553 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/statetransition.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)    24316 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/structures.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     8058 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/table.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     4409 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/uds.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)    11672 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/units.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1885 2023-01-27 13:39:15.000000 odxtools-4.0.0/odxtools/utils.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)       87 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/version.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     5907 2023-06-21 06:52:15.000000 odxtools-4.0.0/odxtools/write_pdx_file.py
-drwxr-xr-x   0 odxtools  (1002) odxtools  (1002)        0 2023-06-21 06:52:47.398999 odxtools-4.0.0/odxtools.egg-info/
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)    23581 2023-06-21 06:52:47.000000 odxtools-4.0.0/odxtools.egg-info/PKG-INFO
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     3342 2023-06-21 06:52:47.000000 odxtools-4.0.0/odxtools.egg-info/SOURCES.txt
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)        1 2023-06-21 06:52:47.000000 odxtools-4.0.0/odxtools.egg-info/dependency_links.txt
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)       53 2023-06-21 06:52:47.000000 odxtools-4.0.0/odxtools.egg-info/entry_points.txt
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)      100 2023-06-21 06:52:47.000000 odxtools-4.0.0/odxtools.egg-info/requires.txt
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)       18 2023-06-21 06:52:47.000000 odxtools-4.0.0/odxtools.egg-info/top_level.txt
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)      382 2023-01-27 13:39:15.000000 odxtools-4.0.0/pyproject.toml
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)       38 2023-06-21 06:52:47.406999 odxtools-4.0.0/setup.cfg
--rwxr-xr-x   0 odxtools  (1002) odxtools  (1002)     2005 2023-01-27 13:39:15.000000 odxtools-4.0.0/setup.py
-drwxr-xr-x   0 odxtools  (1002) odxtools  (1002)        0 2023-06-21 06:52:47.406999 odxtools-4.0.0/tests/
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)    10427 2023-01-27 13:39:15.000000 odxtools-4.0.0/tests/test_compu_methods.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)    51723 2023-06-21 06:52:15.000000 odxtools-4.0.0/tests/test_decoding.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)    36363 2023-06-21 06:52:15.000000 odxtools-4.0.0/tests/test_diag_coded_types.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     9192 2023-06-21 06:52:15.000000 odxtools-4.0.0/tests/test_diag_data_dictionary_spec.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)    14065 2023-06-21 06:52:15.000000 odxtools-4.0.0/tests/test_ecu_variant_matching.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     2499 2023-01-13 13:17:58.000000 odxtools-4.0.0/tests/test_ecu_variant_patterns.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)    10314 2023-06-21 06:52:15.000000 odxtools-4.0.0/tests/test_encoding.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     3827 2023-01-27 13:39:15.000000 odxtools-4.0.0/tests/test_odxtools.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1962 2023-01-27 13:39:15.000000 odxtools-4.0.0/tests/test_odxtypes.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1639 2023-01-27 13:39:15.000000 odxtools-4.0.0/tests/test_readparameters.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)    17020 2023-06-21 06:52:15.000000 odxtools-4.0.0/tests/test_singleecujob.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)    10873 2023-06-21 06:52:15.000000 odxtools-4.0.0/tests/test_somersault.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)     8220 2023-06-21 06:52:15.000000 odxtools-4.0.0/tests/test_unit_spec.py
--rw-r--r--   0 odxtools  (1002) odxtools  (1002)      745 2023-01-13 13:17:58.000000 odxtools-4.0.0/tests/test_utils.py
+drwxr-xr-x   0 odxtools  (1002) odxtools  (1002)        0 2023-06-28 12:36:24.980317 odxtools-4.0.1/
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1069 2022-03-09 15:55:44.000000 odxtools-4.0.1/LICENSE
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)    23581 2023-06-28 12:36:24.976317 odxtools-4.0.1/PKG-INFO
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)    22767 2022-12-12 08:24:18.000000 odxtools-4.0.1/README.md
+drwxr-xr-x   0 odxtools  (1002) odxtools  (1002)        0 2023-06-28 12:36:24.956316 odxtools-4.0.1/examples/
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)       65 2023-01-27 13:39:15.000000 odxtools-4.0.1/examples/__init__.py
+-rwxr-xr-x   0 odxtools  (1002) odxtools  (1002)     1686 2023-06-21 06:52:15.000000 odxtools-4.0.1/examples/isotp_send.py
+-rwxr-xr-x   0 odxtools  (1002) odxtools  (1002)      811 2023-01-27 13:39:15.000000 odxtools-4.0.1/examples/mksomersaultpdx.py
+-rwxr-xr-x   0 odxtools  (1002) odxtools  (1002)     1612 2023-01-27 13:39:15.000000 odxtools-4.0.1/examples/pdxcopy.py
+-rwxr-xr-x   0 odxtools  (1002) odxtools  (1002)    81924 2023-06-28 12:35:57.000000 odxtools-4.0.1/examples/somersaultecu.py
+-rwxr-xr-x   0 odxtools  (1002) odxtools  (1002)    19444 2023-01-27 13:39:15.000000 odxtools-4.0.1/examples/somersaultlazy.py
+drwxr-xr-x   0 odxtools  (1002) odxtools  (1002)        0 2023-06-28 12:36:24.968317 odxtools-4.0.1/odxtools/
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     2925 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/__init__.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)      153 2023-01-13 13:17:58.000000 odxtools-4.0.1/odxtools/__main__.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     7853 2023-06-21 06:52:15.000000 odxtools-4.0.1/odxtools/admindata.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     4267 2023-06-21 06:52:15.000000 odxtools-4.0.1/odxtools/audience.py
+drwxr-xr-x   0 odxtools  (1002) odxtools  (1002)        0 2023-06-28 12:36:24.968317 odxtools-4.0.1/odxtools/cli/
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)      140 2023-01-13 13:17:58.000000 odxtools-4.0.1/odxtools/cli/__init__.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)      549 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/cli/_parser_utils.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     3287 2023-06-21 06:52:15.000000 odxtools-4.0.1/odxtools/cli/_print_utils.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)    14094 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/cli/browse.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1171 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/cli/dummy_sub_parser.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     5974 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/cli/find.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     7317 2023-06-28 12:35:57.000000 odxtools-4.0.1/odxtools/cli/list.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1809 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/cli/main.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     7471 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/cli/snoop.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     5302 2023-06-21 06:52:15.000000 odxtools-4.0.1/odxtools/communicationparameter.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     8581 2023-06-28 12:35:57.000000 odxtools-4.0.1/odxtools/companydata.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)    11567 2023-06-21 06:52:15.000000 odxtools-4.0.1/odxtools/comparam_subset.py
+drwxr-xr-x   0 odxtools  (1002) odxtools  (1002)        0 2023-06-28 12:36:24.972317 odxtools-4.0.1/odxtools/compumethods/
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)      840 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/compumethods/__init__.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)      894 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/compumethods/compumethodbase.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)      210 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/compumethods/compurationalcoeffs.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1489 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/compumethods/compuscale.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     7485 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/compumethods/createanycompumethod.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)      843 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/compumethods/identicalcompumethod.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     2531 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/compumethods/limit.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     8228 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/compumethods/linearcompumethod.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1692 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/compumethods/scalelinearcompumethod.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     6252 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/compumethods/tabintpcompumethod.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     2502 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/compumethods/texttablecompumethod.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     5667 2023-06-21 06:52:15.000000 odxtools-4.0.1/odxtools/database.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)    15371 2023-06-21 06:52:15.000000 odxtools-4.0.1/odxtools/dataobjectproperty.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)      699 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/decodestate.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)    27425 2023-06-21 06:52:15.000000 odxtools-4.0.1/odxtools/diagcodedtypes.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     6643 2023-06-21 06:52:15.000000 odxtools-4.0.1/odxtools/diagdatadictionaryspec.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)    39660 2023-06-28 12:35:57.000000 odxtools-4.0.1/odxtools/diaglayer.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     5957 2023-06-21 06:52:15.000000 odxtools-4.0.1/odxtools/diaglayercontainer.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)    11411 2023-06-21 06:52:15.000000 odxtools-4.0.1/odxtools/diaglayerraw.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)      908 2023-06-21 06:52:15.000000 odxtools-4.0.1/odxtools/diaglayertype.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     6969 2023-06-28 12:35:57.000000 odxtools-4.0.1/odxtools/ecu_variant_matcher.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     3427 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/ecu_variant_patterns.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1190 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/encodestate.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     7285 2023-06-21 06:52:15.000000 odxtools-4.0.1/odxtools/endofpdufield.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     2429 2023-06-21 06:52:15.000000 odxtools-4.0.1/odxtools/envdata.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     5382 2023-06-21 06:52:15.000000 odxtools-4.0.1/odxtools/envdatadesc.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)      549 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/exceptions.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1249 2023-06-21 06:52:15.000000 odxtools-4.0.1/odxtools/functionalclass.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)      173 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/globals.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)    12104 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/isotp_state_machine.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)      452 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/load_file.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)      310 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/load_odx_d_file.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)      334 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/load_pdx_file.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)      963 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/message.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)    12896 2023-06-21 06:52:15.000000 odxtools-4.0.1/odxtools/multiplexer.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     4185 2023-06-21 06:52:15.000000 odxtools-4.0.1/odxtools/nameditemlist.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1209 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/obd.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     8438 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/odxlink.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     3469 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/odxtypes.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     3467 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/parameter_info.py
+drwxr-xr-x   0 odxtools  (1002) odxtools  (1002)        0 2023-06-28 12:36:24.976317 odxtools-4.0.1/odxtools/parameters/
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)      832 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/parameters/__init__.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     4330 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/parameters/codedconstparameter.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     9282 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/parameters/createanyparameter.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1566 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/parameters/dynamicparameter.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1387 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/parameters/lengthkeyparameter.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     3011 2023-06-28 12:35:57.000000 odxtools-4.0.1/odxtools/parameters/matchingrequestparameter.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     4851 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/parameters/nrcconstparameter.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     7208 2023-06-21 06:52:15.000000 odxtools-4.0.1/odxtools/parameters/parameterbase.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     4108 2023-06-28 12:35:57.000000 odxtools-4.0.1/odxtools/parameters/parameterwithdop.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     3263 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/parameters/physicalconstantparameter.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     2787 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/parameters/reservedparameter.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1805 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/parameters/systemparameter.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1090 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/parameters/tableentryparameter.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     2565 2023-06-21 06:52:15.000000 odxtools-4.0.1/odxtools/parameters/tablekeyparameter.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1230 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/parameters/tablestructparameter.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     3130 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/parameters/valueparameter.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     3304 2023-06-21 06:52:15.000000 odxtools-4.0.1/odxtools/parentref.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     2372 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/physicaltype.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)    13655 2023-06-28 12:35:57.000000 odxtools-4.0.1/odxtools/service.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)    16374 2023-06-21 06:52:15.000000 odxtools-4.0.1/odxtools/singleecujob.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     5290 2023-06-21 06:52:15.000000 odxtools-4.0.1/odxtools/specialdata.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1234 2023-06-21 06:52:15.000000 odxtools-4.0.1/odxtools/state.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     3495 2023-06-21 06:52:15.000000 odxtools-4.0.1/odxtools/statechart.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     2553 2023-06-21 06:52:15.000000 odxtools-4.0.1/odxtools/statetransition.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)    24316 2023-06-21 06:52:15.000000 odxtools-4.0.1/odxtools/structures.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     8058 2023-06-21 06:52:15.000000 odxtools-4.0.1/odxtools/table.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     4409 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/uds.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)    11672 2023-06-21 06:52:15.000000 odxtools-4.0.1/odxtools/units.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1885 2023-01-27 13:39:15.000000 odxtools-4.0.1/odxtools/utils.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)       87 2023-06-28 12:35:57.000000 odxtools-4.0.1/odxtools/version.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     5907 2023-06-21 06:52:15.000000 odxtools-4.0.1/odxtools/write_pdx_file.py
+drwxr-xr-x   0 odxtools  (1002) odxtools  (1002)        0 2023-06-28 12:36:24.968317 odxtools-4.0.1/odxtools.egg-info/
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)    23581 2023-06-28 12:36:24.000000 odxtools-4.0.1/odxtools.egg-info/PKG-INFO
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     3342 2023-06-28 12:36:24.000000 odxtools-4.0.1/odxtools.egg-info/SOURCES.txt
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)        1 2023-06-28 12:36:24.000000 odxtools-4.0.1/odxtools.egg-info/dependency_links.txt
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)       53 2023-06-28 12:36:24.000000 odxtools-4.0.1/odxtools.egg-info/entry_points.txt
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)      100 2023-06-28 12:36:24.000000 odxtools-4.0.1/odxtools.egg-info/requires.txt
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)       18 2023-06-28 12:36:24.000000 odxtools-4.0.1/odxtools.egg-info/top_level.txt
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)      382 2023-01-27 13:39:15.000000 odxtools-4.0.1/pyproject.toml
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)       38 2023-06-28 12:36:24.980317 odxtools-4.0.1/setup.cfg
+-rwxr-xr-x   0 odxtools  (1002) odxtools  (1002)     2005 2023-01-27 13:39:15.000000 odxtools-4.0.1/setup.py
+drwxr-xr-x   0 odxtools  (1002) odxtools  (1002)        0 2023-06-28 12:36:24.976317 odxtools-4.0.1/tests/
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)    10427 2023-01-27 13:39:15.000000 odxtools-4.0.1/tests/test_compu_methods.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)    51695 2023-06-28 12:35:57.000000 odxtools-4.0.1/tests/test_decoding.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)    36363 2023-06-21 06:52:15.000000 odxtools-4.0.1/tests/test_diag_coded_types.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     9192 2023-06-21 06:52:15.000000 odxtools-4.0.1/tests/test_diag_data_dictionary_spec.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)    14065 2023-06-21 06:52:15.000000 odxtools-4.0.1/tests/test_ecu_variant_matching.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     2499 2023-01-13 13:17:58.000000 odxtools-4.0.1/tests/test_ecu_variant_patterns.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)    10314 2023-06-21 06:52:15.000000 odxtools-4.0.1/tests/test_encoding.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     3827 2023-01-27 13:39:15.000000 odxtools-4.0.1/tests/test_odxtools.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1962 2023-01-27 13:39:15.000000 odxtools-4.0.1/tests/test_odxtypes.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     1639 2023-01-27 13:39:15.000000 odxtools-4.0.1/tests/test_readparameters.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)    17020 2023-06-21 06:52:15.000000 odxtools-4.0.1/tests/test_singleecujob.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)    11866 2023-06-28 12:35:57.000000 odxtools-4.0.1/tests/test_somersault.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)     8220 2023-06-21 06:52:15.000000 odxtools-4.0.1/tests/test_unit_spec.py
+-rw-r--r--   0 odxtools  (1002) odxtools  (1002)      745 2023-01-13 13:17:58.000000 odxtools-4.0.1/tests/test_utils.py
```

### Comparing `odxtools-4.0.0/LICENSE` & `odxtools-4.0.1/LICENSE`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/PKG-INFO` & `odxtools-4.0.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: odxtools
-Version: 4.0.0
+Version: 4.0.1
 Summary: Utilities to work with the automotive diagnostics standard ODX.
 Home-page: https://github.com/Daimler/odxtools
 Author: Katrin Bauer, Andreas Lauser
 Author-email: katrin.b.bauer@mbition.io, andreas.lauser@mbition.io
 License: MIT
 Project-URL: Bug Tracker, https://github.com/Daimler/odxtools/issues
 Keywords: can,can bus,odx,pdx,obd,uds,automotive,diagnostics
```

### Comparing `odxtools-4.0.0/README.md` & `odxtools-4.0.1/README.md`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/examples/isotp_send.py` & `odxtools-4.0.1/examples/isotp_send.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/examples/mksomersaultpdx.py` & `odxtools-4.0.1/examples/mksomersaultpdx.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/examples/pdxcopy.py` & `odxtools-4.0.1/examples/pdxcopy.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/examples/somersaultecu.py` & `odxtools-4.0.1/examples/somersaultecu.py`

 * *Files 2% similar despite different names*

```diff
@@ -291,28 +291,43 @@
             base_type_encoding=None,
             is_condensed_raw=None,
             is_highlow_byte_order_raw=None,
         ),
 }
 
 somersault_physical_dimensions = {
-    "second":
+    "time":
         PhysicalDimension(
-            odx_id=OdxLinkId("somersault.PD.second", doc_frags),
-            short_name="second",
-            long_name="Second",
+            odx_id=OdxLinkId("somersault.PD.time", doc_frags),
+            short_name="time",
+            long_name="Time",
             time_exp=1,
             length_exp=0,
             mass_exp=0,
             current_exp=0,
             temperature_exp=0,
             molar_amount_exp=0,
             luminous_intensity_exp=0,
             oid=None,
             description=None,
+        ),
+    "temperature":
+        PhysicalDimension(
+            odx_id=OdxLinkId("somersault.PD.temperature", doc_frags),
+            short_name="temperature",
+            long_name="Temperature",
+            time_exp=0,
+            length_exp=0,
+            mass_exp=0,
+            current_exp=0,
+            temperature_exp=1,
+            molar_amount_exp=0,
+            luminous_intensity_exp=0,
+            oid=None,
+            description=None,
         )
 }
 
 somersault_units = {
     "second":
         Unit(
             odx_id=OdxLinkId("somersault.unit.second", doc_frags),
@@ -320,28 +335,41 @@
             short_name="second",
             display_name="s",
             long_name="Second",
             description="<p>SI unit for the time</p>",
             factor_si_to_unit=1,
             offset_si_to_unit=0,
             physical_dimension_ref=OdxLinkRef.from_id(
-                somersault_physical_dimensions["second"].odx_id),
+                somersault_physical_dimensions["time"].odx_id),
         ),
     "minute":
         Unit(
             odx_id=OdxLinkId("somersault.unit.minute", doc_frags),
             oid=None,
             short_name="minute",
             display_name="min",
             long_name="Minute",
             description=None,
             factor_si_to_unit=60,
             offset_si_to_unit=0,
             physical_dimension_ref=OdxLinkRef.from_id(
-                somersault_physical_dimensions["second"].odx_id),
+                somersault_physical_dimensions["time"].odx_id),
+        ),
+    "celsius":
+        Unit(
+            odx_id=OdxLinkId("somersault.unit.celsius", doc_frags),
+            oid=None,
+            short_name="celsius",
+            display_name="°C",
+            long_name="Degrees Celcius",
+            description=None,
+            factor_si_to_unit=1,
+            offset_si_to_unit=-273.15,
+            physical_dimension_ref=OdxLinkRef.from_id(
+                somersault_physical_dimensions["temperature"].odx_id),
         ),
 }
 
 somersault_unit_groups = {
     "european_duration":
         UnitGroup(
             oid=None,
@@ -433,14 +461,27 @@
             diag_coded_type=somersault_diagcodedtypes["uint8"],
             physical_type=PhysicalType(DataType.A_UINT32, display_radix=None, precision=None),
             compu_method=somersault_compumethods["uint_passthrough"],
             unit_ref=OdxLinkRef.from_id(somersault_units["second"].odx_id),
             is_visible_raw=None,
             sdgs=[],
         ),
+    "temperature":
+        DataObjectProperty(
+            odx_id=OdxLinkId("somersault.DOP.temperature", doc_frags),
+            short_name="temperature",
+            long_name=None,
+            description=None,
+            diag_coded_type=somersault_diagcodedtypes["uint8"],
+            physical_type=PhysicalType(DataType.A_UINT32, display_radix=None, precision=None),
+            compu_method=somersault_compumethods["uint_passthrough"],
+            unit_ref=OdxLinkRef.from_id(somersault_units["celsius"].odx_id),
+            is_visible_raw=None,
+            sdgs=[],
+        ),
     "error_code":
         DataObjectProperty(
             odx_id=OdxLinkId("somersault.DOP.error_code", doc_frags),
             short_name="error_code",
             long_name=None,
             description=None,
             diag_coded_type=somersault_diagcodedtypes["uint8"],
@@ -1336,14 +1377,78 @@
                     ),
                 ],
             ),
             byte_size=None,
         ),
 }
 
+somersault_global_negative_responses = {
+    "general":
+        Response(
+            odx_id=OdxLinkId("GNR.too_hot", doc_frags),
+            short_name="too_hot",
+            long_name=None,
+            description=None,
+            sdgs=[],
+            is_visible_raw=None,
+            response_type="GLOBAL-NEG-RESPONSE",
+            parameters=NamedItemList(
+                short_name_as_id,
+                [
+                    CodedConstParameter(
+                        short_name="sid",
+                        long_name=None,
+                        semantic=None,
+                        description=None,
+                        diag_coded_type=somersault_diagcodedtypes["uint8"],
+                        byte_position=0,
+                        coded_value=uds.NegativeResponseId,
+                        bit_position=None,
+                        sdgs=[],
+                    ),
+                    CodedConstParameter(
+                        short_name="too_hot_dummy",
+                        long_name=None,
+                        semantic=None,
+                        description=None,
+                        diag_coded_type=somersault_diagcodedtypes["uint8"],
+                        byte_position=1,
+                        coded_value=0xfe,
+                        bit_position=None,
+                        sdgs=[],
+                    ),
+                    CodedConstParameter(
+                        short_name="too_hot_id",
+                        long_name=None,
+                        semantic=None,
+                        description=None,
+                        diag_coded_type=somersault_diagcodedtypes["uint8"],
+                        byte_position=2,
+                        coded_value=0xa7,
+                        bit_position=None,
+                        sdgs=[],
+                    ),
+                    ValueParameter(
+                        short_name="temperature",
+                        long_name=None,
+                        semantic=None,
+                        description=None,
+                        physical_default_value_raw=None,
+                        byte_position=3,
+                        dop_ref=OdxLinkRef("somersault.DOP.temperature", doc_frags),
+                        dop_snref=None,
+                        bit_position=None,
+                        sdgs=[],
+                    ),
+                ],
+            ),
+            byte_size=None,
+        )
+}
+
 # services
 somersault_services = {
     "start_session":
         DiagService(
             odx_id=OdxLinkId("somersault.service.session_start", doc_frags),
             short_name="session_start",
             long_name=None,
@@ -1753,15 +1858,16 @@
     company_datas=NamedItemList(short_name_as_id),
     functional_classes=NamedItemList(short_name_as_id, somersault_functional_classes.values()),
     diag_data_dictionary_spec=somersault_diag_data_dictionary_spec,
     diag_comms=[*somersault_services.values(), *somersault_single_ecu_jobs.values()],
     requests=NamedItemList(short_name_as_id, somersault_requests.values()),
     positive_responses=NamedItemList(short_name_as_id, somersault_positive_responses.values()),
     negative_responses=NamedItemList(short_name_as_id, somersault_negative_responses.values()),
-    global_negative_responses=NamedItemList(short_name_as_id),
+    global_negative_responses=NamedItemList(short_name_as_id,
+                                            somersault_global_negative_responses.values()),
     import_refs=[],
     state_charts=NamedItemList(short_name_as_id),
     additional_audiences=NamedItemList(short_name_as_id, somersault_additional_audiences.values()),
     sdgs=[],
     parent_refs=[],
     communication_parameters=somersault_communication_parameters,
     ecu_variant_patterns=[],
```

#### encoding

```diff
@@ -1 +1 @@
-us-ascii
+utf-8
```

### Comparing `odxtools-4.0.0/examples/somersaultlazy.py` & `odxtools-4.0.1/examples/somersaultlazy.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/__init__.py` & `odxtools-4.0.1/odxtools/__init__.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/admindata.py` & `odxtools-4.0.1/odxtools/admindata.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/audience.py` & `odxtools-4.0.1/odxtools/audience.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/cli/_parser_utils.py` & `odxtools-4.0.1/odxtools/cli/_parser_utils.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/cli/_print_utils.py` & `odxtools-4.0.1/odxtools/cli/_print_utils.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/cli/browse.py` & `odxtools-4.0.1/odxtools/cli/browse.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/cli/dummy_sub_parser.py` & `odxtools-4.0.1/odxtools/cli/dummy_sub_parser.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/cli/find.py` & `odxtools-4.0.1/odxtools/cli/find.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/cli/list.py` & `odxtools-4.0.1/odxtools/cli/list.py`

 * *Files 9% similar despite different names*

```diff
@@ -13,14 +13,15 @@
 
 # name of the tool
 _odxtools_tool_name_ = "list"
 
 
 def print_summary(
     odxdb: Database,
+    print_global_neg_responses=False,
     print_services=False,
     print_dops=False,
     print_params=False,
     print_com_params=False,
     print_pre_condition_states=False,
     print_state_transitions=False,
     print_audiences=False,
@@ -56,18 +57,23 @@
             if (can_tx_id := dl.get_can_send_id(proto.short_name)) is not None:
                 print(f"  CAN send ID for protocol '{proto.short_name}': 0x{can_tx_id:x}")
 
         if dl.description:
             desc = format_desc(dl.description, ident=2)
             print(f" Description: " + desc)
 
+        if print_global_neg_responses and dl.global_negative_responses:
+            print(f"The global negative responses of '{dl.short_name}' are: ")
+            for gnr in dl.global_negative_responses:
+                print(f" {gnr}")
+
         if print_services and len(all_services) > 0:
             services = [s for s in all_services if service_filter(s)]
             if len(services) > 0:
-                print(f"The services of the {dl.variant_type.value} '{dl.short_name}' are: ")
+                print(f"The services of '{dl.short_name}' are: ")
                 for service in services:
                     if isinstance(service, DiagService):
                         print_diagnostic_service(
                             service,
                             print_params=print_params,
                             print_pre_condition_states=print_pre_condition_states,
                             print_state_transitions=print_state_transitions,
@@ -118,14 +124,24 @@
         nargs="+",
         metavar="VARIANT",
         required=False,
         help="Specifies which variants should be included.",
         default="all",
     )
 
+    parser.add_argument(
+        "-g",
+        "--global-negative-responses",
+        default=False,
+        action="store_const",
+        const=True,
+        required=False,
+        help="Print a list of the global negative responses for the selected ECUs.",
+    )
+
     # The service option is None if option is not passed at all (-> do not print services). It is an empty list if --services is passed
     parser.add_argument(
         "-s",
         "--services",
         nargs="*",
         default=None,
         metavar="SERVICE",
@@ -167,14 +183,15 @@
 
 def run(args):
     odxdb = _parser_utils.load_file(args)
 
     variants = args.variants if args.variants else None
     print_summary(
         odxdb,
+        print_global_neg_responses=args.all or args.global_neg_responses,
         print_services=args.all or args.params or args.services is not None,
         service_filter=(lambda s: s.short_name in args.services
                         if args.services and len(args.services) > 0 else lambda s: True),
         print_dops=args.all or args.dops,
         variants=None if variants == "all" else variants,
         print_params=args.all or args.params,
         print_com_params=args.all,
```

### Comparing `odxtools-4.0.0/odxtools/cli/main.py` & `odxtools-4.0.1/odxtools/cli/main.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/cli/snoop.py` & `odxtools-4.0.1/odxtools/cli/snoop.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/communicationparameter.py` & `odxtools-4.0.1/odxtools/communicationparameter.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/companydata.py` & `odxtools-4.0.1/odxtools/companydata.py`

 * *Files 5% similar despite different names*

```diff
@@ -96,21 +96,17 @@
 @dataclass
 class CompanySpecificInfo:
     related_docs: List[RelatedDoc]
     sdgs: List[SpecialDataGroup]
 
     @staticmethod
     def from_et(et_element, doc_frags: List[OdxDocFragment]) -> "CompanySpecificInfo":
-        related_docs = et_element.find("RELATED-DOCS")
-        if related_docs is not None:
-            rdlist = list()
-            for rd in related_docs.iterfind("RELATED-DOC"):
-                rdlist.append(RelatedDoc.from_et(rd))
-
-            related_docs = rdlist
+        related_docs = [
+            RelatedDoc.from_et(rd) for rd in et_element.iterfind("RELATED-DOCS/RELATED-DOC")
+        ]
 
         sdgs = create_sdgs_from_et(et_element.find("SDGS"), doc_frags)
 
         return CompanySpecificInfo(related_docs=related_docs, sdgs=sdgs)
 
     def _build_odxlinks(self) -> Dict[OdxLinkId, Any]:
         result = {}
```

### Comparing `odxtools-4.0.0/odxtools/comparam_subset.py` & `odxtools-4.0.1/odxtools/comparam_subset.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/compumethods/__init__.py` & `odxtools-4.0.1/odxtools/compumethods/__init__.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/compumethods/compumethodbase.py` & `odxtools-4.0.1/odxtools/compumethods/compumethodbase.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/compumethods/compuscale.py` & `odxtools-4.0.1/odxtools/compumethods/compuscale.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/compumethods/createanycompumethod.py` & `odxtools-4.0.1/odxtools/compumethods/createanycompumethod.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/compumethods/identicalcompumethod.py` & `odxtools-4.0.1/odxtools/compumethods/identicalcompumethod.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/compumethods/limit.py` & `odxtools-4.0.1/odxtools/compumethods/limit.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/compumethods/linearcompumethod.py` & `odxtools-4.0.1/odxtools/compumethods/linearcompumethod.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/compumethods/scalelinearcompumethod.py` & `odxtools-4.0.1/odxtools/compumethods/scalelinearcompumethod.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/compumethods/tabintpcompumethod.py` & `odxtools-4.0.1/odxtools/compumethods/tabintpcompumethod.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/compumethods/texttablecompumethod.py` & `odxtools-4.0.1/odxtools/compumethods/texttablecompumethod.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/database.py` & `odxtools-4.0.1/odxtools/database.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/dataobjectproperty.py` & `odxtools-4.0.1/odxtools/dataobjectproperty.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/decodestate.py` & `odxtools-4.0.1/odxtools/decodestate.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/diagcodedtypes.py` & `odxtools-4.0.1/odxtools/diagcodedtypes.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/diagdatadictionaryspec.py` & `odxtools-4.0.1/odxtools/diagdatadictionaryspec.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/diaglayer.py` & `odxtools-4.0.1/odxtools/diaglayer.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,13 +1,14 @@
 # SPDX-License-Identifier: MIT
 # Copyright (c) 2022 MBition GmbH
 import warnings
 from copy import copy
+from functools import cached_property
 from itertools import chain
-from typing import Any, Callable, Dict, Iterable, List, Optional, Tuple, TypeVar, Union
+from typing import Any, Callable, Dict, Iterable, List, Optional, Tuple, TypeVar, Union, cast
 from xml.etree import ElementTree
 
 from deprecation import deprecated
 
 from .admindata import AdminData
 from .audience import AdditionalAudience, Audience
 from .communicationparameter import CommunicationParameterRef
@@ -35,14 +36,16 @@
 from .structures import BasicStructure, Request, Response, create_any_structure_from_et
 from .table import Table
 from .units import UnitGroup, UnitSpec
 from .utils import create_description_from_et, short_name_as_id
 
 T = TypeVar("T")
 
+PrefixTree = Dict[int, Union[List[DiagService], "PrefixTree"]]
+
 
 class DiagLayer:
     """This class represents a "logical view" upon a diagnostic layer
     according to the ODX standard.
 
     i.e. it handles the value inheritance, communication parameters,
     encoding/decoding of data, etc.
@@ -814,18 +817,21 @@
     # </communication parameter handling>
     #####
 
     #####
     # <PDU decoding>
     #####
 
-    def _build_coded_prefix_tree(self):
+    @cached_property
+    def _prefix_tree(self) -> PrefixTree:
         """Constructs the coded prefix tree of the services.
-        Each leaf node is a list of `DiagService`s.
-        (This is because navigating from a service to the request/ responses is easier than finding the service for a given request/response object.)
+
+        Each leaf node is a list of `DiagService`s.  (This is because
+        navigating from a service to the request/ responses is easier
+        than finding the service for a given request/response object.)
 
         Example:
         Let there be four services with corresponding requests:
         * Request 1 has the coded constant prefix `12 34`.
         * Request 2 has the coded constant prefix `12 34`.
         * Request 3 has the coded constant prefix `12 56`.
         * Request 4 has the coded constant prefix `12 56 00`.
@@ -833,106 +839,124 @@
         Then, the constructed prefix tree is the dict
         ```
         {0x12: {0x34: {-1: [<Service 1>, <Service 2>]},
                 0x56: {-1: [<Service 3>],
                        0x0: {-1: [<Service 4>]}
                        }}}
         ```
-        Note, that the inner `-1` are constant to distinguish them from possible service IDs.
+        Note, that the inner `-1` are constant to distinguish them
+        from possible service IDs.
 
         Also note, that it is actually allowed that
         (a) SIDs for different services are the same like for service 1 and 2 (thus each leaf node is a list) and
         (b) one SID is the prefix of another SID like for service 3 and 4 (thus the constant `-1` key).
+
         """
-        services = [s for s in self._services if isinstance(s, DiagService)]
-        prefix_tree = {}
-        for s in services:
-            # Compute prefixes for the request and all responses
+        prefix_tree: PrefixTree = {}
+        for s in self.services:
+            # Compute prefixes for the service's request and all
+            # possible responses. We need to consider the global
+            # negative responses here, because they might contain
+            # MATCHING-REQUEST parameters. If these global responses
+            # do not contain such parameters, this will potentially
+            # result in an enormous amount of decoded messages for
+            # global negative responses. (I.e., one for each
+            # service. This can be avoided by specifying the
+            # corresponding request for `decode_response()`.)
             request_prefix = s.request.coded_const_prefix()
-            prefixes = [request_prefix] + [
-                message.coded_const_prefix(request_prefix=request_prefix)
-                for message in chain(s.positive_responses, s.negative_responses)
+            prefixes = [request_prefix]
+            prefixes += [
+                x.coded_const_prefix(request_prefix=request_prefix) for x in chain(
+                    s.positive_responses, s.negative_responses, self.global_negative_responses)
             ]
             for coded_prefix in prefixes:
-                # Traverse prefix tree
-                sub_tree = prefix_tree
-                for b in coded_prefix:
-                    if sub_tree.get(b) is None:
-                        sub_tree[b] = {}
-                    sub_tree = sub_tree.get(b)
-
-                    assert isinstance(
-                        sub_tree,
-                        dict), f"{sub_tree} has type {type(sub_tree)}. How did this happen?"
-                # Add service as leaf to prefix tree
-                if sub_tree.get(-1) is None:
-                    sub_tree[-1] = [s]
-                else:
-                    sub_tree[-1].append(s)
+                self._extend_prefix_tree(prefix_tree, coded_prefix, s)
+
         return prefix_tree
 
-    def _find_services_for_uds(self, message: Union[bytes, bytearray]):
-        if not hasattr(self, "_prefix_tree"):
-            # Compute the prefix tree the first time this decode function is called.
-            self._prefix_tree = self._build_coded_prefix_tree()
+    @staticmethod
+    def _extend_prefix_tree(prefix_tree: PrefixTree, coded_prefix: bytes,
+                            service: DiagService) -> None:
+
+        # make sure that tree has an entry for the given prefix
+        sub_tree = prefix_tree
+        for b in coded_prefix:
+            if b not in sub_tree:
+                sub_tree[b] = {}
+            sub_tree = cast(PrefixTree, sub_tree[b])
+
+        # Store the object as in the prefix tree. This is done by
+        # assigning the list of possible objects to the key -1 of the
+        # dictionary (this is quite hacky...)
+        if sub_tree.get(-1) is None:
+            sub_tree[-1] = [service]
+        else:
+            cast(List[DiagService], sub_tree[-1]).append(service)
+
+    def _find_services_for_uds(self, message: Union[bytes, bytearray]) -> List[DiagService]:
         prefix_tree = self._prefix_tree
 
         # Find matching service(s) in prefix tree
-        possible_services = []
+        possible_services: List[DiagService] = []
         for b in message:
-            if prefix_tree.get(b) is not None:
-                assert isinstance(prefix_tree.get(b), dict)
-                prefix_tree = prefix_tree.get(b)
+            if b in prefix_tree:
+                assert isinstance(prefix_tree[b], dict)
+                prefix_tree = cast(PrefixTree, prefix_tree[b])
             else:
                 break
             if -1 in prefix_tree:
-                possible_services += prefix_tree[-1]
+                possible_services += cast(List[DiagService], prefix_tree[-1])
         return possible_services
 
-    def decode(self, message: Union[bytes, bytearray]) -> Iterable[Message]:
-        possible_services = self._find_services_for_uds(message)
-
-        if possible_services is None:
-            raise DecodeError(f"Couldn't find corresponding service for message {message.hex()}.")
-
-        decoded_messages = []
+    def _decode(self, message: Union[bytes, bytearray],
+                candidate_services: Iterable[DiagService]) -> List[Message]:
+        decoded_messages: List[Message] = []
 
-        for service in possible_services:
+        for service in candidate_services:
             try:
                 decoded_messages.append(service.decode_message(message))
             except DecodeError as e:
-                pass
+                # check if the message can be decoded as a global
+                # negative response for the service
+                for gnr in self.global_negative_responses:
+                    try:
+                        decoded_gnr = gnr.decode(message)
+                        decoded_messages.append(
+                            Message(
+                                coded_message=message,
+                                service=service,
+                                structure=gnr,
+                                param_dict=decoded_gnr))
+                    except DecodeError:
+                        pass
+
         if len(decoded_messages) == 0:
             raise DecodeError(
-                f"None of the services {possible_services} could parse {message.hex()}.")
+                f"None of the services {candidate_services} could parse {message.hex()}.")
+
         return decoded_messages
 
+    def decode(self, message: Union[bytes, bytearray]) -> List[Message]:
+        candidate_services = self._find_services_for_uds(message)
+
+        return self._decode(message, candidate_services)
+
     def decode_response(self, response: Union[bytes, bytearray],
                         request: Union[bytes, bytearray, Message]) -> Iterable[Message]:
         if isinstance(request, Message):
-            possible_services = [request.service]
+            candidate_services = [request.service]
         else:
             if not isinstance(request, (bytes, bytearray)):
                 raise TypeError(f"Request parameter must have type "
                                 f"Message, bytes or bytearray but was {type(request)}")
-            possible_services = self._find_services_for_uds(request)
-        if possible_services is None:
+            candidate_services = self._find_services_for_uds(request)
+        if candidate_services is None:
             raise DecodeError(f"Couldn't find corresponding service for request {request.hex()}.")
 
-        decoded_messages = []
-
-        for service in possible_services:
-            try:
-                decoded_messages.append(service.decode_message(response))
-            except DecodeError as e:
-                pass
-        if len(decoded_messages) == 0:
-            raise DecodeError(
-                f"None of the services {possible_services} could parse {response.hex()}.")
-        return decoded_messages
+        return self._decode(response, candidate_services)
 
     #####
     # </PDU decoding>
     #####
 
     def __str__(self) -> str:
         return f"DiagLayer('{self.short_name}', type='{self.variant_type.value}')"
```

### Comparing `odxtools-4.0.0/odxtools/diaglayercontainer.py` & `odxtools-4.0.1/odxtools/diaglayercontainer.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/diaglayerraw.py` & `odxtools-4.0.1/odxtools/diaglayerraw.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/diaglayertype.py` & `odxtools-4.0.1/odxtools/diaglayertype.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/ecu_variant_matcher.py` & `odxtools-4.0.1/odxtools/ecu_variant_matcher.py`

 * *Files 1% similar despite different names*

```diff
@@ -165,9 +165,10 @@
 
     def _update_cache(self, req_bytes: bytes, resp_bytes: bytes) -> None:
         if self.use_cache:
             self.req_resp_cache[req_bytes] = resp_bytes
 
     def _get_ident_response(self) -> bytes:
         if not self._recent_ident_response:
-            raise RuntimeError("No response available. Mayby forgot to call 'evaluate' in loop?")
+            raise RuntimeError(
+                "No response available. Did you forget to call 'evaluate()' in a loop?")
         return self._recent_ident_response
```

### Comparing `odxtools-4.0.0/odxtools/ecu_variant_patterns.py` & `odxtools-4.0.1/odxtools/ecu_variant_patterns.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/encodestate.py` & `odxtools-4.0.1/odxtools/encodestate.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/endofpdufield.py` & `odxtools-4.0.1/odxtools/endofpdufield.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/envdata.py` & `odxtools-4.0.1/odxtools/envdata.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/envdatadesc.py` & `odxtools-4.0.1/odxtools/envdatadesc.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/exceptions.py` & `odxtools-4.0.1/odxtools/exceptions.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/functionalclass.py` & `odxtools-4.0.1/odxtools/functionalclass.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/isotp_state_machine.py` & `odxtools-4.0.1/odxtools/isotp_state_machine.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/message.py` & `odxtools-4.0.1/odxtools/message.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/multiplexer.py` & `odxtools-4.0.1/odxtools/multiplexer.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/nameditemlist.py` & `odxtools-4.0.1/odxtools/nameditemlist.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/obd.py` & `odxtools-4.0.1/odxtools/obd.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/odxlink.py` & `odxtools-4.0.1/odxtools/odxlink.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/odxtypes.py` & `odxtools-4.0.1/odxtools/odxtypes.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/parameter_info.py` & `odxtools-4.0.1/odxtools/parameter_info.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/parameters/__init__.py` & `odxtools-4.0.1/odxtools/parameters/__init__.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/parameters/codedconstparameter.py` & `odxtools-4.0.1/odxtools/parameters/codedconstparameter.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/parameters/createanyparameter.py` & `odxtools-4.0.1/odxtools/parameters/createanyparameter.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/parameters/dynamicparameter.py` & `odxtools-4.0.1/odxtools/parameters/dynamicparameter.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/parameters/lengthkeyparameter.py` & `odxtools-4.0.1/odxtools/parameters/lengthkeyparameter.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/parameters/matchingrequestparameter.py` & `odxtools-4.0.1/odxtools/parameters/matchingrequestparameter.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,11 +1,12 @@
 # SPDX-License-Identifier: MIT
 # Copyright (c) 2022 MBition GmbH
 from ..decodestate import DecodeState
 from ..encodestate import EncodeState
+from ..exceptions import EncodeError
 from .parameterbase import Parameter
 
 
 class MatchingRequestParameter(Parameter):
 
     def __init__(self, *, request_byte_position, byte_length, **kwargs):
         super().__init__(parameter_type="MATCHING-REQUEST-PARAM", **kwargs)
@@ -29,16 +30,16 @@
         return False
 
     def get_coded_value(self, request_value=None):
         return request_value
 
     def get_coded_value_as_bytes(self, encode_state: EncodeState):
         if not encode_state.triggering_request:
-            raise TypeError(f"Parameter '{self.short_name}' is of matching request type,"
-                            " but no original request has been specified.")
+            raise EncodeError(f"Parameter '{self.short_name}' is of matching request type,"
+                              " but no original request has been specified.")
         return encode_state.triggering_request[self
                                                .request_byte_position:self.request_byte_position +
                                                self.byte_length]
 
     def decode_from_pdu(self, decode_state: DecodeState):
         byte_position = (
             self.byte_position
```

### Comparing `odxtools-4.0.0/odxtools/parameters/nrcconstparameter.py` & `odxtools-4.0.1/odxtools/parameters/nrcconstparameter.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/parameters/parameterbase.py` & `odxtools-4.0.1/odxtools/parameters/parameterbase.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/parameters/parameterwithdop.py` & `odxtools-4.0.1/odxtools/parameters/parameterwithdop.py`

 * *Files 2% similar despite different names*

```diff
@@ -45,15 +45,17 @@
             # (e.g., static and dynamic fields)
             self._dop = odxlinks.resolve_lenient(self.dop_ref)
 
     def _resolve_snrefs(self, diag_layer: "DiagLayer") -> None:
         super()._resolve_snrefs(diag_layer)
 
         if self.dop_snref:
-            self._dop = diag_layer.diag_data_dictionary_spec.data_object_props[self.dop_snref]
+            spec = diag_layer.diag_data_dictionary_spec
+            self._dop = (
+                spec.data_object_props.get(self.dop_snref) or spec.structures.get(self.dop_snref))
 
     @property
     def dop(self) -> Optional[DopBase]:
         """may be a DataObjectProperty, a Structure or None"""
 
         return self._dop
```

### Comparing `odxtools-4.0.0/odxtools/parameters/physicalconstantparameter.py` & `odxtools-4.0.1/odxtools/parameters/physicalconstantparameter.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/parameters/reservedparameter.py` & `odxtools-4.0.1/odxtools/parameters/reservedparameter.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/parameters/systemparameter.py` & `odxtools-4.0.1/odxtools/parameters/systemparameter.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/parameters/tableentryparameter.py` & `odxtools-4.0.1/odxtools/parameters/tableentryparameter.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/parameters/tablekeyparameter.py` & `odxtools-4.0.1/odxtools/parameters/tablekeyparameter.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/parameters/tablestructparameter.py` & `odxtools-4.0.1/odxtools/parameters/tablestructparameter.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/parameters/valueparameter.py` & `odxtools-4.0.1/odxtools/parameters/valueparameter.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/parentref.py` & `odxtools-4.0.1/odxtools/parentref.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/physicaltype.py` & `odxtools-4.0.1/odxtools/physicaltype.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/service.py` & `odxtools-4.0.1/odxtools/service.py`

 * *Files 1% similar despite different names*

```diff
@@ -270,16 +270,16 @@
     def decode_message(self, message: Union[bytes, bytearray]) -> Message:
 
         # Check if message is a request or positive or negative response
         interpretable_message_types = []
 
         if (self.request is None or self.positive_responses is None or
                 self.negative_responses is None):
-            raise ValueError("References couldn't be resolved or have not been resolved yet."
-                             " Try calling `database.resolve_references()`.")
+            raise RuntimeError("References couldn't be resolved or have not been resolved yet."
+                               " Try calling `database.resolve_odxlinks()`.")
 
         for message_type in [self.request, *self.positive_responses, *self.negative_responses]:
             prefix = message_type.coded_const_prefix(
                 request_prefix=self.request.coded_const_prefix())
             if all(b == message[i] for (i, b) in enumerate(prefix)):
                 interpretable_message_types.append(message_type)
```

### Comparing `odxtools-4.0.0/odxtools/singleecujob.py` & `odxtools-4.0.1/odxtools/singleecujob.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/specialdata.py` & `odxtools-4.0.1/odxtools/specialdata.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/state.py` & `odxtools-4.0.1/odxtools/state.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/statechart.py` & `odxtools-4.0.1/odxtools/statechart.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/statetransition.py` & `odxtools-4.0.1/odxtools/statetransition.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/structures.py` & `odxtools-4.0.1/odxtools/structures.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/table.py` & `odxtools-4.0.1/odxtools/table.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/uds.py` & `odxtools-4.0.1/odxtools/uds.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/units.py` & `odxtools-4.0.1/odxtools/units.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/utils.py` & `odxtools-4.0.1/odxtools/utils.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools/write_pdx_file.py` & `odxtools-4.0.1/odxtools/write_pdx_file.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/odxtools.egg-info/PKG-INFO` & `odxtools-4.0.1/odxtools.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: odxtools
-Version: 4.0.0
+Version: 4.0.1
 Summary: Utilities to work with the automotive diagnostics standard ODX.
 Home-page: https://github.com/Daimler/odxtools
 Author: Katrin Bauer, Andreas Lauser
 Author-email: katrin.b.bauer@mbition.io, andreas.lauser@mbition.io
 License: MIT
 Project-URL: Bug Tracker, https://github.com/Daimler/odxtools/issues
 Keywords: can,can bus,odx,pdx,obd,uds,automotive,diagnostics
```

### Comparing `odxtools-4.0.0/odxtools.egg-info/SOURCES.txt` & `odxtools-4.0.1/odxtools.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/setup.py` & `odxtools-4.0.1/setup.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/tests/test_compu_methods.py` & `odxtools-4.0.1/tests/test_compu_methods.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/tests/test_decoding.py` & `odxtools-4.0.1/tests/test_decoding.py`

 * *Files 0% similar despite different names*

```diff
@@ -183,15 +183,15 @@
             ecu_variant_patterns=[],
         )
         diag_layer = DiagLayer(diag_layer_raw=diag_layer_raw)
         diag_layer._resolve_odxlinks(odxlinks)
         diag_layer._finalize_init(odxlinks)
 
         self.assertEqual(
-            diag_layer._build_coded_prefix_tree(),
+            diag_layer._prefix_tree,
             {0x7D: {
                 0xAB: {
                     -1: [service]
                 },
                 0xC: {
                     0xDE: {
                         -1: [service2]
@@ -417,15 +417,15 @@
             parent_refs=[],
             communication_parameters=[],
             ecu_variant_patterns=[],
         )
         diag_layer = DiagLayer(diag_layer_raw=diag_layer_raw)
         diag_layer._resolve_odxlinks(odxlinks)
         diag_layer._finalize_init(odxlinks)
-        self.assertDictEqual(diag_layer._build_coded_prefix_tree(),
+        self.assertDictEqual(diag_layer._prefix_tree,
                              {0x12: {
                                  0x34: {
                                      0x56: {
                                          0x78: {
                                              -1: [service]
                                          }
                                      }
```

### Comparing `odxtools-4.0.0/tests/test_diag_coded_types.py` & `odxtools-4.0.1/tests/test_diag_coded_types.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/tests/test_diag_data_dictionary_spec.py` & `odxtools-4.0.1/tests/test_diag_data_dictionary_spec.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/tests/test_ecu_variant_matching.py` & `odxtools-4.0.1/tests/test_ecu_variant_matching.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/tests/test_ecu_variant_patterns.py` & `odxtools-4.0.1/tests/test_ecu_variant_patterns.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/tests/test_encoding.py` & `odxtools-4.0.1/tests/test_encoding.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/tests/test_odxtools.py` & `odxtools-4.0.1/tests/test_odxtools.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/tests/test_odxtypes.py` & `odxtools-4.0.1/tests/test_odxtypes.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/tests/test_readparameters.py` & `odxtools-4.0.1/tests/test_readparameters.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/tests/test_singleecujob.py` & `odxtools-4.0.1/tests/test_singleecujob.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/tests/test_somersault.py` & `odxtools-4.0.1/tests/test_somersault.py`

 * *Files 9% similar despite different names*

```diff
@@ -168,14 +168,38 @@
         self.assertTrue(len(messages) == 1)
         m = messages[0]
         self.assertEqual(m.coded_message, bytes([0x03, 0x45]))
         self.assertEqual(m.service, odxdb.ecus.somersault_assiduous.services.headstand)
         self.assertEqual(m.structure, odxdb.ecus.somersault_assiduous.services.headstand.request)
         self.assertEqual(m.param_dict, {"sid": 0x03, "duration": 0x45})
 
+    def test_decode_global_negative_response(self):
+        ecu = odxdb.ecus.somersault_assiduous
+        coded_request = bytes([0x03, 0x45])
+
+        self.assertEqual(len(ecu.global_negative_responses), 1)
+
+        gnr = ecu.global_negative_responses.too_hot
+        coded_response = gnr.encode(coded_request=coded_request, temperature=35)
+
+        decoded = ecu.decode(coded_response)
+        # the global negative response for the somersault ECUs does
+        # not include any matching-request parameter, so decode()
+        # returns one possible instance per service
+        self.assertEqual(len(decoded), len(ecu.services))
+
+        # if we specify the request, the result should become unique
+        decoded = ecu.decode_response(coded_response, request=coded_request)
+        self.assertEqual(len(decoded), 1)
+
+        # make sure that the global negative response was decoded
+        # correctly
+        gnr = decoded[0]
+        self.assertEqual(gnr.param_dict['temperature'], 35)
+
     def test_decode_inherited_request(self):
         raw_message = odxdb.ecus.somersault_assiduous.services.do_backward_flips(
             backward_soberness_check=0x21, num_flips=2)
         messages = odxdb.ecus.somersault_assiduous.decode(raw_message)
         self.assertTrue(len(messages) == 1)
         m = messages[0]
         self.assertEqual(m.coded_message, bytes([0xBB, 0x21, 0x02]))
```

### Comparing `odxtools-4.0.0/tests/test_unit_spec.py` & `odxtools-4.0.1/tests/test_unit_spec.py`

 * *Files identical despite different names*

### Comparing `odxtools-4.0.0/tests/test_utils.py` & `odxtools-4.0.1/tests/test_utils.py`

 * *Files identical despite different names*


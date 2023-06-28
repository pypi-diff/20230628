# Comparing `tmp/excitingtools-1.2.0.tar.gz` & `tmp/excitingtools-1.3.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "excitingtools-1.2.0.tar", last modified: Wed Mar 22 15:09:22 2023, max compression
+gzip compressed data, was "/builds/sol/exciting/tools/exciting_tools/dist/.tmp-v4o47n79/excitingtools-1.3.0.tar", last modified: Wed Jun 28 14:25:21 2023, max compression
```

## Comparing `excitingtools-1.2.0.tar` & `excitingtools-1.3.0.tar`

### file list

```diff
@@ -1,150 +1,150 @@
-drwxr-xr-x   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:09:22.149668 excitingtools-1.2.0/
-drwxr-xr-x   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:09:22.118140 excitingtools-1.2.0/.github/
-drwxr-xr-x   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:09:22.125118 excitingtools-1.2.0/.github/workflows/
--rw-r--r--   0 fabianpeschel   (501) staff       (20)      602 2023-03-22 15:06:41.000000 excitingtools-1.2.0/.github/workflows/actions.yml
--rw-r--r--   0 fabianpeschel   (501) staff       (20)      647 2023-03-22 15:06:41.000000 excitingtools-1.2.0/.github/workflows/joss.yml
--rw-r--r--   0 fabianpeschel   (501) staff       (20)       39 2023-03-22 15:06:41.000000 excitingtools-1.2.0/.gitignore
--rw-r--r--   0 fabianpeschel   (501) staff       (20)    21948 2023-03-22 08:45:50.000000 excitingtools-1.2.0/.pylintrc
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     8901 2023-02-27 14:38:47.000000 excitingtools-1.2.0/.style.yapf
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     1916 2023-02-27 14:38:47.000000 excitingtools-1.2.0/CITATION.cff
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     5375 2023-02-27 14:38:47.000000 excitingtools-1.2.0/CONTRIBUTING.md
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     7650 2023-02-27 14:38:47.000000 excitingtools-1.2.0/COPYING.LESSER
--rw-r--r--   0 fabianpeschel   (501) staff       (20)    34915 2023-02-27 14:38:47.000000 excitingtools-1.2.0/COPYING.md
--rw-r--r--   0 fabianpeschel   (501) staff       (20)    53974 2023-03-22 15:09:22.149444 excitingtools-1.2.0/PKG-INFO
--rw-r--r--   0 fabianpeschel   (501) staff       (20)    13226 2023-03-22 15:06:41.000000 excitingtools-1.2.0/README.md
-drwxr-xr-x   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:09:22.125338 excitingtools-1.2.0/excitingtools/
--rw-r--r--   0 fabianpeschel   (501) staff       (20)      601 2023-02-27 14:38:47.000000 excitingtools-1.2.0/excitingtools/__init__.py
-drwxr-xr-x   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:09:22.126323 excitingtools-1.2.0/excitingtools/constants/
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     1349 2023-02-27 14:38:47.000000 excitingtools-1.2.0/excitingtools/constants/units.py
-drwxr-xr-x   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:09:22.127308 excitingtools-1.2.0/excitingtools/dataclasses/
--rw-r--r--   0 fabianpeschel   (501) staff       (20)      123 2023-02-27 14:38:47.000000 excitingtools-1.2.0/excitingtools/dataclasses/__init__.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     5365 2023-02-27 14:38:47.000000 excitingtools-1.2.0/excitingtools/dataclasses/band_structure.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)      807 2023-03-22 08:45:50.000000 excitingtools-1.2.0/excitingtools/dataclasses/data_structs.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)      145 2023-02-27 14:38:47.000000 excitingtools-1.2.0/excitingtools/dataclasses/density_of_states.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     5063 2023-03-22 08:45:50.000000 excitingtools-1.2.0/excitingtools/dataclasses/eigenvalues.py
-drwxr-xr-x   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:09:22.127510 excitingtools-1.2.0/excitingtools/eigenstates/
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     1111 2023-02-27 14:38:47.000000 excitingtools-1.2.0/excitingtools/eigenstates/eigenstates.py
-drwxr-xr-x   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:09:22.131095 excitingtools-1.2.0/excitingtools/exciting_dict_parsers/
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     4714 2023-02-27 14:38:47.000000 excitingtools-1.2.0/excitingtools/exciting_dict_parsers/RT_TDDFT_parser.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)        0 2023-02-27 14:38:47.000000 excitingtools-1.2.0/excitingtools/exciting_dict_parsers/__init__.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     4020 2023-03-22 08:45:50.000000 excitingtools-1.2.0/excitingtools/exciting_dict_parsers/bse_parser.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)    13617 2023-03-22 08:45:50.000000 excitingtools-1.2.0/excitingtools/exciting_dict_parsers/groundstate_parser.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     6829 2023-02-27 14:38:47.000000 excitingtools-1.2.0/excitingtools/exciting_dict_parsers/gw_eigenvalues_parser.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     3880 2023-02-27 14:38:47.000000 excitingtools-1.2.0/excitingtools/exciting_dict_parsers/gw_eps00_parser.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)    16723 2023-02-27 14:38:47.000000 excitingtools-1.2.0/excitingtools/exciting_dict_parsers/gw_info_parser.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     3292 2023-02-27 14:38:47.000000 excitingtools-1.2.0/excitingtools/exciting_dict_parsers/gw_vxc_parser.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     5590 2023-03-22 14:11:35.000000 excitingtools-1.2.0/excitingtools/exciting_dict_parsers/input_parser.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     9495 2023-03-22 08:45:50.000000 excitingtools-1.2.0/excitingtools/exciting_dict_parsers/parser_factory.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)    19455 2023-03-22 08:45:50.000000 excitingtools-1.2.0/excitingtools/exciting_dict_parsers/properties_parser.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     4160 2023-02-27 14:38:47.000000 excitingtools-1.2.0/excitingtools/exciting_dict_parsers/species_parser.py
-drwxr-xr-x   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:09:22.132074 excitingtools-1.2.0/excitingtools/exciting_obj_parsers/
--rw-r--r--   0 fabianpeschel   (501) staff       (20)      219 2023-02-27 14:38:47.000000 excitingtools-1.2.0/excitingtools/exciting_obj_parsers/__init__.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     1448 2023-03-22 08:45:50.000000 excitingtools-1.2.0/excitingtools/exciting_obj_parsers/eigenvalue_parser.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     4331 2023-02-27 14:38:47.000000 excitingtools-1.2.0/excitingtools/exciting_obj_parsers/gw_eigenvalues.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     2651 2023-03-22 14:11:35.000000 excitingtools-1.2.0/excitingtools/exciting_obj_parsers/input_xml.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     1230 2023-02-27 14:38:47.000000 excitingtools-1.2.0/excitingtools/exciting_obj_parsers/ks_band_structure.py
-drwxr-xr-x   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:09:22.134197 excitingtools-1.2.0/excitingtools/input/
--rw-r--r--   0 fabianpeschel   (501) staff       (20)        0 2023-02-27 14:38:47.000000 excitingtools-1.2.0/excitingtools/input/__init__.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     6280 2023-03-22 14:11:35.000000 excitingtools-1.2.0/excitingtools/input/base_class.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     2024 2023-03-22 14:11:35.000000 excitingtools-1.2.0/excitingtools/input/common.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     2926 2023-03-22 14:11:35.000000 excitingtools-1.2.0/excitingtools/input/ground_state.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     4834 2023-03-22 14:11:35.000000 excitingtools-1.2.0/excitingtools/input/input_xml.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     2388 2023-03-22 14:58:55.000000 excitingtools-1.2.0/excitingtools/input/properties.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)    11517 2023-03-22 14:11:35.000000 excitingtools-1.2.0/excitingtools/input/structure.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     5229 2023-02-27 14:38:47.000000 excitingtools-1.2.0/excitingtools/input/xml_utils.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     5676 2023-03-22 14:11:35.000000 excitingtools-1.2.0/excitingtools/input/xs.py
-drwxr-xr-x   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:09:22.134583 excitingtools-1.2.0/excitingtools/math/
--rw-r--r--   0 fabianpeschel   (501) staff       (20)        0 2023-02-27 14:38:47.000000 excitingtools-1.2.0/excitingtools/math/__init__.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)      576 2023-02-27 14:38:47.000000 excitingtools-1.2.0/excitingtools/math/math_utils.py
-drwxr-xr-x   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:09:22.136435 excitingtools-1.2.0/excitingtools/parser_utils/
--rw-r--r--   0 fabianpeschel   (501) staff       (20)       78 2023-02-27 14:38:47.000000 excitingtools-1.2.0/excitingtools/parser_utils/__init__.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)       46 2023-02-27 14:38:47.000000 excitingtools-1.2.0/excitingtools/parser_utils/erroneous_file_error.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)      960 2023-02-27 14:38:47.000000 excitingtools-1.2.0/excitingtools/parser_utils/grep_parser.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     2304 2023-02-27 14:38:47.000000 excitingtools-1.2.0/excitingtools/parser_utils/parser_decorators.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)      502 2023-03-22 08:45:50.000000 excitingtools-1.2.0/excitingtools/parser_utils/parser_utils.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     2227 2023-02-27 14:38:47.000000 excitingtools-1.2.0/excitingtools/parser_utils/regex_parser.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     1668 2023-02-27 14:38:47.000000 excitingtools-1.2.0/excitingtools/parser_utils/simple_parser.py
-drwxr-xr-x   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:09:22.136673 excitingtools-1.2.0/excitingtools/runner/
--rw-r--r--   0 fabianpeschel   (501) staff       (20)        0 2023-02-27 14:38:47.000000 excitingtools-1.2.0/excitingtools/runner/__init__.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     6165 2023-03-22 08:45:50.000000 excitingtools-1.2.0/excitingtools/runner/runner.py
-drwxr-xr-x   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:09:22.136951 excitingtools-1.2.0/excitingtools/structure/
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     4137 2023-02-27 14:38:47.000000 excitingtools-1.2.0/excitingtools/structure/lattice.py
-drwxr-xr-x   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:09:22.138507 excitingtools-1.2.0/excitingtools/utils/
--rw-r--r--   0 fabianpeschel   (501) staff       (20)        0 2023-02-27 14:38:47.000000 excitingtools-1.2.0/excitingtools/utils/__init__.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     5872 2023-02-27 14:38:47.000000 excitingtools-1.2.0/excitingtools/utils/dict_utils.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)      500 2023-03-22 08:45:50.000000 excitingtools-1.2.0/excitingtools/utils/jobflow_utils.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)      622 2023-02-27 14:38:47.000000 excitingtools-1.2.0/excitingtools/utils/test_utils.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     2136 2023-02-27 14:38:47.000000 excitingtools-1.2.0/excitingtools/utils/utils.py
-drwxr-xr-x   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:09:22.126170 excitingtools-1.2.0/excitingtools.egg-info/
--rw-r--r--   0 fabianpeschel   (501) staff       (20)    53974 2023-03-22 15:09:21.000000 excitingtools-1.2.0/excitingtools.egg-info/PKG-INFO
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     4228 2023-03-22 15:09:22.000000 excitingtools-1.2.0/excitingtools.egg-info/SOURCES.txt
--rw-r--r--   0 fabianpeschel   (501) staff       (20)        1 2023-03-22 15:09:21.000000 excitingtools-1.2.0/excitingtools.egg-info/dependency_links.txt
--rw-r--r--   0 fabianpeschel   (501) staff       (20)       72 2023-03-22 15:09:21.000000 excitingtools-1.2.0/excitingtools.egg-info/requires.txt
--rw-r--r--   0 fabianpeschel   (501) staff       (20)       14 2023-03-22 15:09:21.000000 excitingtools-1.2.0/excitingtools.egg-info/top_level.txt
--rw-r--r--   0 fabianpeschel   (501) staff       (20)      243 2023-02-27 14:38:47.000000 excitingtools-1.2.0/git-blame-ignore-revs
-drwxr-xr-x   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:09:22.139253 excitingtools-1.2.0/paper/
--rw-r--r--   0 fabianpeschel   (501) staff       (20)    10387 2023-03-22 08:45:50.000000 excitingtools-1.2.0/paper/joss_latex.template
--rw-r--r--   0 fabianpeschel   (501) staff       (20)    14039 2023-03-22 08:45:50.000000 excitingtools-1.2.0/paper/latex.template
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     5301 2023-03-22 15:06:41.000000 excitingtools-1.2.0/paper/paper.bib
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     8645 2023-03-22 15:06:41.000000 excitingtools-1.2.0/paper/paper.md
--rw-r--r--   0 fabianpeschel   (501) staff       (20)      830 2023-03-22 15:06:41.000000 excitingtools-1.2.0/pyproject.toml
--rw-r--r--   0 fabianpeschel   (501) staff       (20)       81 2023-02-27 14:38:47.000000 excitingtools-1.2.0/pytest.ini
--rw-r--r--   0 fabianpeschel   (501) staff       (20)       23 2023-03-22 15:06:41.000000 excitingtools-1.2.0/requirements.txt
--rw-r--r--   0 fabianpeschel   (501) staff       (20)       38 2023-03-22 15:09:22.149738 excitingtools-1.2.0/setup.cfg
-drwxr-xr-x   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:09:22.139552 excitingtools-1.2.0/tests/
--rw-r--r--   0 fabianpeschel   (501) staff       (20)        0 2023-02-27 14:38:47.000000 excitingtools-1.2.0/tests/__init__.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)      416 2023-03-22 08:45:50.000000 excitingtools-1.2.0/tests/conftest.py
-drwxr-xr-x   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:09:22.139972 excitingtools-1.2.0/tests/dataclasses/
--rw-r--r--   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:06:41.000000 excitingtools-1.2.0/tests/dataclasses/__init__.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     3774 2023-02-27 14:38:47.000000 excitingtools-1.2.0/tests/dataclasses/test_band_structure.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     4478 2023-02-27 14:38:47.000000 excitingtools-1.2.0/tests/dataclasses/test_eigenvalues.py
-drwxr-xr-x   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:09:22.142033 excitingtools-1.2.0/tests/dict_parsers/
--rw-r--r--   0 fabianpeschel   (501) staff       (20)        0 2023-02-27 14:38:47.000000 excitingtools-1.2.0/tests/dict_parsers/__init__.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)    13221 2023-02-27 14:38:47.000000 excitingtools-1.2.0/tests/dict_parsers/test_bse_parser.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)    42033 2023-02-27 14:38:47.000000 excitingtools-1.2.0/tests/dict_parsers/test_groundstate_parser.py
-drwxr-xr-x   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:09:22.143632 excitingtools-1.2.0/tests/dict_parsers/test_gw/
--rw-r--r--   0 fabianpeschel   (501) staff       (20)        0 2023-02-27 14:38:47.000000 excitingtools-1.2.0/tests/dict_parsers/test_gw/__init__.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)    17883 2023-02-27 14:38:47.000000 excitingtools-1.2.0/tests/dict_parsers/test_gw/mock_gw_info_out.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     1874 2023-02-27 14:38:47.000000 excitingtools-1.2.0/tests/dict_parsers/test_gw/test_gw_dos_parser.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)    16110 2023-02-27 14:38:47.000000 excitingtools-1.2.0/tests/dict_parsers/test_gw/test_gw_eignvalues_parser.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     4445 2023-02-27 14:38:47.000000 excitingtools-1.2.0/tests/dict_parsers/test_gw/test_gw_eps00_parser.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)    14356 2023-02-27 14:38:47.000000 excitingtools-1.2.0/tests/dict_parsers/test_gw/test_gw_info_parser.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     4471 2023-02-27 14:38:47.000000 excitingtools-1.2.0/tests/dict_parsers/test_gw/test_gw_vxc_parser.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     5060 2023-03-22 14:11:35.000000 excitingtools-1.2.0/tests/dict_parsers/test_input_parser.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     8348 2023-02-27 14:38:47.000000 excitingtools-1.2.0/tests/dict_parsers/test_ks_band_structure.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     1618 2023-02-27 14:38:47.000000 excitingtools-1.2.0/tests/dict_parsers/test_properties_parser.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)    11166 2023-02-27 14:38:47.000000 excitingtools-1.2.0/tests/dict_parsers/test_species_parser.py
-drwxr-xr-x   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:09:22.144097 excitingtools-1.2.0/tests/eigenstates/
--rw-r--r--   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:06:41.000000 excitingtools-1.2.0/tests/eigenstates/__init__.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)      954 2023-02-27 14:38:47.000000 excitingtools-1.2.0/tests/eigenstates/test_eigenstates.py
-drwxr-xr-x   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:09:22.146183 excitingtools-1.2.0/tests/input/
--rw-r--r--   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:06:41.000000 excitingtools-1.2.0/tests/input/__init__.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     1244 2023-03-22 14:11:35.000000 excitingtools-1.2.0/tests/input/test_base_class.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     7004 2023-03-22 14:11:35.000000 excitingtools-1.2.0/tests/input/test_ground_state.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     8138 2023-03-22 14:11:35.000000 excitingtools-1.2.0/tests/input/test_input_xml.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     1554 2023-03-22 15:01:56.000000 excitingtools-1.2.0/tests/input/test_properties.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)    14249 2023-03-22 14:11:35.000000 excitingtools-1.2.0/tests/input/test_structure.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     3216 2023-02-27 14:38:47.000000 excitingtools-1.2.0/tests/input/test_xml_utils.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     6896 2023-03-22 14:11:35.000000 excitingtools-1.2.0/tests/input/test_xs.py
-drwxr-xr-x   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:09:22.146534 excitingtools-1.2.0/tests/math/
--rw-r--r--   0 fabianpeschel   (501) staff       (20)        0 2023-02-27 14:38:47.000000 excitingtools-1.2.0/tests/math/__init__.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)      340 2023-02-27 14:38:47.000000 excitingtools-1.2.0/tests/math/test_math_utils.py
-drwxr-xr-x   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:09:22.147548 excitingtools-1.2.0/tests/obj_parsers/
--rw-r--r--   0 fabianpeschel   (501) staff       (20)        0 2023-02-27 14:38:47.000000 excitingtools-1.2.0/tests/obj_parsers/__init__.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     3508 2023-03-22 08:45:50.000000 excitingtools-1.2.0/tests/obj_parsers/test_eigenvalue_parser.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     1861 2023-02-27 14:38:47.000000 excitingtools-1.2.0/tests/obj_parsers/test_gw_dos.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     9190 2023-02-27 14:38:47.000000 excitingtools-1.2.0/tests/obj_parsers/test_gw_eigenvalues.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     3491 2023-03-22 14:11:35.000000 excitingtools-1.2.0/tests/obj_parsers/test_input_parser.py
-drwxr-xr-x   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:09:22.148073 excitingtools-1.2.0/tests/parser_utils/
--rw-r--r--   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:06:41.000000 excitingtools-1.2.0/tests/parser_utils/__init__.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     3176 2023-02-27 14:38:47.000000 excitingtools-1.2.0/tests/parser_utils/test_regex_parser.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     2122 2023-02-27 14:38:47.000000 excitingtools-1.2.0/tests/parser_utils/test_simple_parser.py
-drwxr-xr-x   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:09:22.148242 excitingtools-1.2.0/tests/runner/
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     4605 2023-03-22 08:45:50.000000 excitingtools-1.2.0/tests/runner/test_runner.py
-drwxr-xr-x   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:09:22.148530 excitingtools-1.2.0/tests/structure/
--rw-r--r--   0 fabianpeschel   (501) staff       (20)        0 2023-02-27 14:38:47.000000 excitingtools-1.2.0/tests/structure/__init__.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     2280 2023-02-27 14:38:47.000000 excitingtools-1.2.0/tests/structure/test_lattice.py
-drwxr-xr-x   0 fabianpeschel   (501) staff       (20)        0 2023-03-22 15:09:22.149015 excitingtools-1.2.0/tests/utils/
--rw-r--r--   0 fabianpeschel   (501) staff       (20)        0 2023-02-27 14:38:47.000000 excitingtools-1.2.0/tests/utils/__init__.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     6021 2023-02-27 14:38:47.000000 excitingtools-1.2.0/tests/utils/test_dict_utils.py
--rw-r--r--   0 fabianpeschel   (501) staff       (20)     1428 2023-02-27 14:38:47.000000 excitingtools-1.2.0/tests/utils/test_utils.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:25:21.000000 excitingtools-1.3.0/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:25:21.000000 excitingtools-1.3.0/.github/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:25:21.000000 excitingtools-1.3.0/.github/workflows/
+-rw-rw-rw-   0 root         (0) root         (0)      602 2023-06-28 14:24:48.000000 excitingtools-1.3.0/.github/workflows/actions.yml
+-rw-rw-rw-   0 root         (0) root         (0)      647 2023-06-28 14:24:48.000000 excitingtools-1.3.0/.github/workflows/joss.yml
+-rw-rw-rw-   0 root         (0) root         (0)    21948 2023-06-28 14:24:48.000000 excitingtools-1.3.0/.pylintrc
+-rw-rw-rw-   0 root         (0) root         (0)     8901 2023-06-28 14:24:48.000000 excitingtools-1.3.0/.style.yapf
+-rw-rw-rw-   0 root         (0) root         (0)     1916 2023-06-28 14:24:48.000000 excitingtools-1.3.0/CITATION.cff
+-rw-rw-rw-   0 root         (0) root         (0)     5375 2023-06-28 14:24:48.000000 excitingtools-1.3.0/CONTRIBUTING.md
+-rw-rw-rw-   0 root         (0) root         (0)     7650 2023-06-28 14:24:48.000000 excitingtools-1.3.0/COPYING.LESSER
+-rw-rw-rw-   0 root         (0) root         (0)    34915 2023-06-28 14:24:48.000000 excitingtools-1.3.0/COPYING.md
+-rw-r--r--   0 root         (0) root         (0)    54028 2023-06-28 14:25:21.000000 excitingtools-1.3.0/PKG-INFO
+-rw-rw-rw-   0 root         (0) root         (0)    13226 2023-06-28 14:24:48.000000 excitingtools-1.3.0/README.md
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:25:21.000000 excitingtools-1.3.0/excitingtools/
+-rw-rw-rw-   0 root         (0) root         (0)      651 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:25:21.000000 excitingtools-1.3.0/excitingtools/constants/
+-rw-rw-rw-   0 root         (0) root         (0)     1567 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/constants/units.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:25:21.000000 excitingtools-1.3.0/excitingtools/dataclasses/
+-rw-rw-rw-   0 root         (0) root         (0)      123 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/dataclasses/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)     5365 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/dataclasses/band_structure.py
+-rw-rw-rw-   0 root         (0) root         (0)      807 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/dataclasses/data_structs.py
+-rw-rw-rw-   0 root         (0) root         (0)      145 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/dataclasses/density_of_states.py
+-rw-rw-rw-   0 root         (0) root         (0)     6662 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/dataclasses/eigenvalues.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:25:21.000000 excitingtools-1.3.0/excitingtools/eigenstates/
+-rw-rw-rw-   0 root         (0) root         (0)     1111 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/eigenstates/eigenstates.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:25:21.000000 excitingtools-1.3.0/excitingtools/exciting_dict_parsers/
+-rw-rw-rw-   0 root         (0) root         (0)     4714 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/exciting_dict_parsers/RT_TDDFT_parser.py
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 14:24:49.000000 excitingtools-1.3.0/excitingtools/exciting_dict_parsers/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)     4020 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/exciting_dict_parsers/bse_parser.py
+-rw-rw-rw-   0 root         (0) root         (0)    13617 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/exciting_dict_parsers/groundstate_parser.py
+-rw-rw-rw-   0 root         (0) root         (0)     6829 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/exciting_dict_parsers/gw_eigenvalues_parser.py
+-rw-rw-rw-   0 root         (0) root         (0)     3880 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/exciting_dict_parsers/gw_eps00_parser.py
+-rw-rw-rw-   0 root         (0) root         (0)    16723 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/exciting_dict_parsers/gw_info_parser.py
+-rw-rw-rw-   0 root         (0) root         (0)     3292 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/exciting_dict_parsers/gw_vxc_parser.py
+-rw-rw-rw-   0 root         (0) root         (0)     5349 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/exciting_dict_parsers/input_parser.py
+-rw-rw-rw-   0 root         (0) root         (0)     9495 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/exciting_dict_parsers/parser_factory.py
+-rw-rw-rw-   0 root         (0) root         (0)    19455 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/exciting_dict_parsers/properties_parser.py
+-rw-rw-rw-   0 root         (0) root         (0)     4160 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/exciting_dict_parsers/species_parser.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:25:21.000000 excitingtools-1.3.0/excitingtools/exciting_obj_parsers/
+-rw-rw-rw-   0 root         (0) root         (0)      219 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/exciting_obj_parsers/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)     1448 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/exciting_obj_parsers/eigenvalue_parser.py
+-rw-rw-rw-   0 root         (0) root         (0)     4331 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/exciting_obj_parsers/gw_eigenvalues.py
+-rw-rw-rw-   0 root         (0) root         (0)      634 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/exciting_obj_parsers/input_xml.py
+-rw-rw-rw-   0 root         (0) root         (0)     1230 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/exciting_obj_parsers/ks_band_structure.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:25:21.000000 excitingtools-1.3.0/excitingtools/input/
+-rw-rw-rw-   0 root         (0) root         (0)      277 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/input/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)     7904 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/input/base_class.py
+-rw-rw-rw-   0 root         (0) root         (0)     1625 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/input/ground_state.py
+-rw-rw-rw-   0 root         (0) root         (0)     1825 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/input/input_xml.py
+-rw-rw-rw-   0 root         (0) root         (0)    10951 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/input/structure.py
+-rw-rw-rw-   0 root         (0) root         (0)     5229 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/input/xml_utils.py
+-rw-rw-rw-   0 root         (0) root         (0)     2629 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/input/xs.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:25:21.000000 excitingtools-1.3.0/excitingtools/math/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 14:24:49.000000 excitingtools-1.3.0/excitingtools/math/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)      576 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/math/math_utils.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:25:21.000000 excitingtools-1.3.0/excitingtools/parser_utils/
+-rw-rw-rw-   0 root         (0) root         (0)       78 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/parser_utils/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)       46 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/parser_utils/erroneous_file_error.py
+-rw-rw-rw-   0 root         (0) root         (0)      960 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/parser_utils/grep_parser.py
+-rw-rw-rw-   0 root         (0) root         (0)     2505 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/parser_utils/parser_decorators.py
+-rw-rw-rw-   0 root         (0) root         (0)     2666 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/parser_utils/parser_utils.py
+-rw-rw-rw-   0 root         (0) root         (0)     2227 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/parser_utils/regex_parser.py
+-rw-rw-rw-   0 root         (0) root         (0)     1668 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/parser_utils/simple_parser.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:25:21.000000 excitingtools-1.3.0/excitingtools/runner/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 14:24:49.000000 excitingtools-1.3.0/excitingtools/runner/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)     6165 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/runner/runner.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:25:21.000000 excitingtools-1.3.0/excitingtools/structure/
+-rw-rw-rw-   0 root         (0) root         (0)     4137 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/structure/lattice.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:25:21.000000 excitingtools-1.3.0/excitingtools/utils/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 14:24:49.000000 excitingtools-1.3.0/excitingtools/utils/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)     5853 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/utils/dict_utils.py
+-rw-rw-rw-   0 root         (0) root         (0)      500 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/utils/jobflow_utils.py
+-rw-rw-rw-   0 root         (0) root         (0)     9399 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/utils/schema_parsing.py
+-rw-rw-rw-   0 root         (0) root         (0)      622 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/utils/test_utils.py
+-rw-rw-rw-   0 root         (0) root         (0)     2298 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/utils/utils.py
+-rw-rw-rw-   0 root         (0) root         (0)    17015 2023-06-28 14:24:48.000000 excitingtools-1.3.0/excitingtools/utils/valid_attributes.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:25:21.000000 excitingtools-1.3.0/excitingtools.egg-info/
+-rw-r--r--   0 root         (0) root         (0)    54028 2023-06-28 14:25:20.000000 excitingtools-1.3.0/excitingtools.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     4275 2023-06-28 14:25:21.000000 excitingtools-1.3.0/excitingtools.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 14:25:20.000000 excitingtools-1.3.0/excitingtools.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)       58 2023-06-28 14:25:20.000000 excitingtools-1.3.0/excitingtools.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)       14 2023-06-28 14:25:20.000000 excitingtools-1.3.0/excitingtools.egg-info/top_level.txt
+-rw-rw-rw-   0 root         (0) root         (0)      243 2023-06-28 14:24:48.000000 excitingtools-1.3.0/git-blame-ignore-revs
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:25:21.000000 excitingtools-1.3.0/paper/
+-rw-rw-rw-   0 root         (0) root         (0)    10387 2023-06-28 14:24:48.000000 excitingtools-1.3.0/paper/joss_latex.template
+-rw-rw-rw-   0 root         (0) root         (0)    14039 2023-06-28 14:24:48.000000 excitingtools-1.3.0/paper/latex.template
+-rw-rw-rw-   0 root         (0) root         (0)     5301 2023-06-28 14:24:48.000000 excitingtools-1.3.0/paper/paper.bib
+-rw-rw-rw-   0 root         (0) root         (0)     8645 2023-06-28 14:24:48.000000 excitingtools-1.3.0/paper/paper.md
+-rw-rw-rw-   0 root         (0) root         (0)      808 2023-06-28 14:24:48.000000 excitingtools-1.3.0/pyproject.toml
+-rw-rw-rw-   0 root         (0) root         (0)       81 2023-06-28 14:24:48.000000 excitingtools-1.3.0/pytest.ini
+-rw-rw-rw-   0 root         (0) root         (0)       33 2023-06-28 14:24:48.000000 excitingtools-1.3.0/requirements.txt
+-rw-r--r--   0 root         (0) root         (0)       38 2023-06-28 14:25:21.000000 excitingtools-1.3.0/setup.cfg
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:25:21.000000 excitingtools-1.3.0/tests/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 14:24:49.000000 excitingtools-1.3.0/tests/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)      416 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/conftest.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:25:21.000000 excitingtools-1.3.0/tests/dataclasses/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 14:24:49.000000 excitingtools-1.3.0/tests/dataclasses/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)     3774 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/dataclasses/test_band_structure.py
+-rw-rw-rw-   0 root         (0) root         (0)     5438 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/dataclasses/test_eigenvalues.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:25:21.000000 excitingtools-1.3.0/tests/dict_parsers/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 14:24:49.000000 excitingtools-1.3.0/tests/dict_parsers/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)    13221 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/dict_parsers/test_bse_parser.py
+-rw-rw-rw-   0 root         (0) root         (0)    42033 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/dict_parsers/test_groundstate_parser.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:25:21.000000 excitingtools-1.3.0/tests/dict_parsers/test_gw/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 14:24:49.000000 excitingtools-1.3.0/tests/dict_parsers/test_gw/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)    17883 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/dict_parsers/test_gw/mock_gw_info_out.py
+-rw-rw-rw-   0 root         (0) root         (0)     1874 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/dict_parsers/test_gw/test_gw_dos_parser.py
+-rw-rw-rw-   0 root         (0) root         (0)    16110 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/dict_parsers/test_gw/test_gw_eignvalues_parser.py
+-rw-rw-rw-   0 root         (0) root         (0)     4445 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/dict_parsers/test_gw/test_gw_eps00_parser.py
+-rw-rw-rw-   0 root         (0) root         (0)    14356 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/dict_parsers/test_gw/test_gw_info_parser.py
+-rw-rw-rw-   0 root         (0) root         (0)     4471 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/dict_parsers/test_gw/test_gw_vxc_parser.py
+-rw-rw-rw-   0 root         (0) root         (0)     5182 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/dict_parsers/test_input_parser.py
+-rw-rw-rw-   0 root         (0) root         (0)     8348 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/dict_parsers/test_ks_band_structure.py
+-rw-rw-rw-   0 root         (0) root         (0)     1618 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/dict_parsers/test_properties_parser.py
+-rw-rw-rw-   0 root         (0) root         (0)    11166 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/dict_parsers/test_species_parser.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:25:21.000000 excitingtools-1.3.0/tests/eigenstates/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 14:24:49.000000 excitingtools-1.3.0/tests/eigenstates/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)      954 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/eigenstates/test_eigenstates.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:25:21.000000 excitingtools-1.3.0/tests/input/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 14:24:49.000000 excitingtools-1.3.0/tests/input/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)     1244 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/input/test_base_class.py
+-rw-rw-rw-   0 root         (0) root         (0)     8194 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/input/test_ground_state.py
+-rw-rw-rw-   0 root         (0) root         (0)     8785 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/input/test_input_xml.py
+-rw-rw-rw-   0 root         (0) root         (0)    16311 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/input/test_structure.py
+-rw-rw-rw-   0 root         (0) root         (0)     3216 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/input/test_xml_utils.py
+-rw-rw-rw-   0 root         (0) root         (0)     6894 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/input/test_xs.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:25:21.000000 excitingtools-1.3.0/tests/math/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 14:24:49.000000 excitingtools-1.3.0/tests/math/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)      340 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/math/test_math_utils.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:25:21.000000 excitingtools-1.3.0/tests/obj_parsers/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 14:24:49.000000 excitingtools-1.3.0/tests/obj_parsers/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)     3508 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/obj_parsers/test_eigenvalue_parser.py
+-rw-rw-rw-   0 root         (0) root         (0)     1861 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/obj_parsers/test_gw_dos.py
+-rw-rw-rw-   0 root         (0) root         (0)     9190 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/obj_parsers/test_gw_eigenvalues.py
+-rw-rw-rw-   0 root         (0) root         (0)     1611 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/obj_parsers/test_input_parser.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:25:21.000000 excitingtools-1.3.0/tests/parser_utils/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 14:24:49.000000 excitingtools-1.3.0/tests/parser_utils/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)     1529 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/parser_utils/test_parser_utils.py
+-rw-rw-rw-   0 root         (0) root         (0)     3176 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/parser_utils/test_regex_parser.py
+-rw-rw-rw-   0 root         (0) root         (0)     2122 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/parser_utils/test_simple_parser.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:25:21.000000 excitingtools-1.3.0/tests/runner/
+-rw-rw-rw-   0 root         (0) root         (0)     4605 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/runner/test_runner.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:25:21.000000 excitingtools-1.3.0/tests/structure/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 14:24:49.000000 excitingtools-1.3.0/tests/structure/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)     2280 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/structure/test_lattice.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:25:21.000000 excitingtools-1.3.0/tests/utils/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 14:24:49.000000 excitingtools-1.3.0/tests/utils/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)     6021 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/utils/test_dict_utils.py
+-rw-rw-rw-   0 root         (0) root         (0)     1255 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/utils/test_schema_parsing.py
+-rw-rw-rw-   0 root         (0) root         (0)     1428 2023-06-28 14:24:48.000000 excitingtools-1.3.0/tests/utils/test_utils.py
```

### filetype from file(1)

```diff
@@ -1 +1 @@
-POSIX tar archive
+POSIX tar archive (GNU)
```

### Comparing `excitingtools-1.2.0/.github/workflows/actions.yml` & `excitingtools-1.3.0/.github/workflows/actions.yml`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/.github/workflows/joss.yml` & `excitingtools-1.3.0/.github/workflows/joss.yml`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/.pylintrc` & `excitingtools-1.3.0/.pylintrc`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/.style.yapf` & `excitingtools-1.3.0/.style.yapf`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/CITATION.cff` & `excitingtools-1.3.0/CITATION.cff`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/CONTRIBUTING.md` & `excitingtools-1.3.0/CONTRIBUTING.md`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/COPYING.LESSER` & `excitingtools-1.3.0/COPYING.LESSER`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/COPYING.md` & `excitingtools-1.3.0/COPYING.md`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/PKG-INFO` & `excitingtools-1.3.0/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: excitingtools
-Version: 1.2.0
+Version: 1.3.0
 Summary: Utilities for aiding in the construction of exciting inputs and the postprocessing exciting outputs.
 Author-email: Alexander Buccheri <alexander.buccheri@mpsd.mpg.de>, Fabian Peschel <peschelf@physik.hu-berlin.de>
 License: ### GNU GENERAL PUBLIC LICENSE
         
         Version 3, 29 June 2007
         
         Copyright (C) 2007 Free Software Foundation, Inc.
@@ -678,14 +678,16 @@
         applications with the library. If this is what you want to do, use the
         GNU Lesser General Public License instead of this License. But first,
         please read <https://www.gnu.org/licenses/why-not-lgpl.html>.
 Project-URL: repository, https://github.com/exciting/excitingtools
 Requires-Python: >=3.6
 Description-Content-Type: text/markdown
 Provides-Extra: dev
+License-File: COPYING.LESSER
+License-File: COPYING.md
 
 # excitingtools
 <span style="font-family:american typewriter; font-size:1em;">**excitingtools**</span> is a collection of 
 modules to facilitate the generation of <span style="font-family:american typewriter; font-size:1em;">**exciting**</span>
 inputs and the post-processing of <span style="font-family:american typewriter; font-size:1em;">**exciting**</span> outputs. 
 
 <span style="font-family:american typewriter; font-size:1em;">**excitingtools**</span> currently provides functionality for:
```

### Comparing `excitingtools-1.2.0/README.md` & `excitingtools-1.3.0/README.md`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/excitingtools/__init__.py` & `excitingtools-1.3.0/excitingtools/__init__.py`

 * *Files 9% similar despite different names*

```diff
@@ -4,11 +4,13 @@
 # Questionable whether one should expose this - required for test framework recursive comparisons
 # Typically not the API one wants to expose to the user, as parsed dict keys are subject to change
 from excitingtools.exciting_dict_parsers.parser_factory import parser_chooser
 # Parsers returning to objects
 from excitingtools.exciting_obj_parsers import *
 # User-level objects
 from excitingtools.dataclasses import *
+# Input objects
+from excitingtools.input import *
 
 from pkg_resources import get_distribution
 
 __version__ = get_distribution('excitingtools').version
```

### Comparing `excitingtools-1.2.0/excitingtools/constants/units.py` & `excitingtools-1.3.0/excitingtools/constants/units.py`

 * *Files 20% similar despite different names*

```diff
@@ -1,11 +1,17 @@
 """ Units.
+
+Physical constants, defined according to [CODATA 2018])(http://physics.nist.gov/constants)
+One could also consider importing them from scipy
 """
 import enum
 
+bohr_to_angstrom = 0.529177210903
+angstrom_to_bohr = 1. / bohr_to_angstrom
+
 
 class Unit(enum.Enum):
     """
     Enum class for exciting units. All names are defined with
     as lowercase, for consistency.
 
     This could be replaced with [PINT](https://pint.readthedocs.io/en/stable/), as used by NOMAD, however it's
```

### Comparing `excitingtools-1.2.0/excitingtools/dataclasses/band_structure.py` & `excitingtools-1.3.0/excitingtools/dataclasses/band_structure.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/excitingtools/dataclasses/data_structs.py` & `excitingtools-1.3.0/excitingtools/dataclasses/data_structs.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/excitingtools/dataclasses/eigenvalues.py` & `excitingtools-1.3.0/excitingtools/dataclasses/eigenvalues.py`

 * *Files 16% similar despite different names*

```diff
@@ -1,13 +1,14 @@
 """ Eigenvalue class.
 """
 import warnings
+from itertools import permutations
 from typing import List, Union, Optional
-import numpy as np
 
+import numpy as np
 from excitingtools.dataclasses.data_structs import PointIndex, BandIndices, NumberOfStates
 
 
 class EigenValues:
     point_type = Union[np.ndarray, List[float]]
     index_type = Union[np.ndarray, List[int]]
     # If a k-index is not matched
@@ -128,7 +129,36 @@
         i_vbm = self.get_array_index(band_indices.VBM)
         i_cbm = self.get_array_index(band_indices.CBm)
 
         ik_vbm = k_indices[0] - 1
         ik_cbm = k_indices[1] - 1
 
         return self.all_eigenvalues[ik_cbm, i_cbm] - self.all_eigenvalues[ik_vbm, i_vbm]
+
+    def get_transition_energy(self, valence_k_point: point_type, conduction_k_point: point_type) -> float:
+        """Determine transition energy between two k-points in the valence band top and conduction band bottom,
+        respectively.
+
+        This function accounts for all different permutations in which the k-points can be found within the exciting
+        eigenvalue output files and determines band indices using occupation values.
+
+        :param valence_k_point: k-point for valence band in fractional coordinates.
+        :param conduction_k_point: k-point for conduction band in fractional coordinates.
+        :return: Transition energy in Hartree.
+        """
+        indices_valence = [self.get_index(k_point) for k_point in permutations(valence_k_point)]
+        try:
+            ik = next(i for i in indices_valence if i != self.NO_MATCH)
+        except StopIteration:
+            raise ValueError(f'Requested valence k-point {valence_k_point} not present.')
+
+        indices_conduction = [self.get_index(k_point) for k_point in permutations(conduction_k_point)]
+        try:
+            jk = next(i for i in indices_conduction if i != self.NO_MATCH)
+        except StopIteration:
+            raise ValueError(f'Requested conduction k-point {conduction_k_point} not present.')
+
+        iVBM = np.where(self.occupations[ik - 1] == 0)[0][0] + self.state_range.first_state - 1
+        jCBm = np.where(self.occupations[jk - 1] == 0)[0][0] + self.state_range.first_state
+
+        return self.band_gap(BandIndices(iVBM, jCBm), k_indices=[ik, jk])
+
```

### Comparing `excitingtools-1.2.0/excitingtools/eigenstates/eigenstates.py` & `excitingtools-1.3.0/excitingtools/eigenstates/eigenstates.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/excitingtools/exciting_dict_parsers/RT_TDDFT_parser.py` & `excitingtools-1.3.0/excitingtools/exciting_dict_parsers/RT_TDDFT_parser.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/excitingtools/exciting_dict_parsers/bse_parser.py` & `excitingtools-1.3.0/excitingtools/exciting_dict_parsers/bse_parser.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/excitingtools/exciting_dict_parsers/groundstate_parser.py` & `excitingtools-1.3.0/excitingtools/exciting_dict_parsers/groundstate_parser.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/excitingtools/exciting_dict_parsers/gw_eigenvalues_parser.py` & `excitingtools-1.3.0/excitingtools/exciting_dict_parsers/gw_eigenvalues_parser.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/excitingtools/exciting_dict_parsers/gw_eps00_parser.py` & `excitingtools-1.3.0/excitingtools/exciting_dict_parsers/gw_eps00_parser.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/excitingtools/exciting_dict_parsers/gw_info_parser.py` & `excitingtools-1.3.0/excitingtools/exciting_dict_parsers/gw_info_parser.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/excitingtools/exciting_dict_parsers/gw_vxc_parser.py` & `excitingtools-1.3.0/excitingtools/exciting_dict_parsers/gw_vxc_parser.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/excitingtools/exciting_dict_parsers/input_parser.py` & `excitingtools-1.3.0/excitingtools/exciting_dict_parsers/input_parser.py`

 * *Files 19% similar despite different names*

```diff
@@ -1,154 +1,137 @@
 """ Parsers for input.xml.
 
 TODO(Fabian): Issues 117 & 121:
 As more sub-elements are implemented in the input files, also add parsers here
 """
-import pathlib
-import warnings
-from typing import Dict, Union
+import copy
+from typing import Tuple
 from xml.etree import ElementTree
 
 from excitingtools.parser_utils.parser_decorators import xml_root
-from excitingtools.parser_utils.parser_utils import find_element
-
-# Valid input formats for all parsers
-root_type = Union[str, ElementTree.Element, pathlib.Path]
+from excitingtools.parser_utils.parser_utils import find_element, convert_string_dict
+from excitingtools.utils.valid_attributes import input_valid_attributes
 
 
 @xml_root
-def parse_title(root: root_type) -> str:
-    """
-    Parse exciting input.xml title element to find the title.
-    :param root: Input for the parser.
-    :returns: Title as string.
+def parse_input_xml(root):
+    """ Parse an input.xml file into dictionary. """
+    assert root.tag == "input"
+    return parse_element_xml(root)
+
+
+def get_root_from_tag(root: ElementTree.Element, tag: str = None) -> Tuple[ElementTree.Element, str]:
+    """ Get the root from a tag.
+
+    :param tag: tag of interest
+    :param root: xml root containing the tag (or having the specified tag as tag)
+    :returns: the tag and the found root, if tag was None returns the tag of the given root
     """
-    ground_state = find_element(root, 'title')
-    return ground_state.text
+    if tag is None:
+        return root, root.tag
+
+    root = find_element(root, tag)
+    if root is None:
+        raise ValueError(f"Your specified input has no tag {tag}.")
+
+    return root, root.tag
 
 
 @xml_root
-def parse_groundstate(root: root_type) -> dict:
-    """
-    Parse exciting input.xml groundstate element into python dictionary.
-    :param root: Input for the parser.
-    :returns: Dictionary containing the groundstate input element attributes.
+def parse_element_xml(root, tag: str = None) -> dict:
+    """ Parse a xml element into dictionary. Can be input.xml root or a subelement of it.
+    Put the attributes simply in dict and add recursively the subtrees and nested dicts.
+
+    :param tag: the tag to parse
+    :param root: the xml root containing the tag
+    :returns: the parsed dictionary, data converted to actual data types
     """
-    valid_xml_elements = {'spin', 'solver'}
+    root, tag = get_root_from_tag(root, tag)
 
-    ground_state = find_element(root, 'groundstate')
-    groundstate_dict: dict = ground_state.attrib
+    if tag in special_tags_to_parse_map.keys():
+        return special_tags_to_parse_map[tag](root)
 
-    subelements = {elem.tag: elem.attrib for elem in ground_state}
-    tags = set(subelements)
-    unsupported_tags = tags - valid_xml_elements
-    supported_tags = tags - unsupported_tags
+    element_dict = convert_string_dict(copy.deepcopy(root.attrib))
 
-    if unsupported_tags:
-        warnings.warn(f'Subelements {unsupported_tags} not yet supported. Groundstate will ignore it.')
+    subelements = list(root)
+    for subelement in subelements:
+        element_dict[subelement.tag] = parse_element_xml(subelement)
 
-    groundstate_dict.update({tag: subelements[tag] for tag in supported_tags})
-    return groundstate_dict
+    return element_dict
 
 
-@xml_root
-def parse_structure(root: root_type) -> dict:
+def _parse_input_tag(root) -> dict:
+    """ Parse special input tag. Necessary because exciting/xml allows arbitrary attributes at this level.
+    Only parses the explicitly named attributes in the schema.
+
+    :param root: the xml root containing the input tag
+    :returns: the parsed dictionary, data converted to actual data types
     """
-    Parse exciting input.xml structure element into python dictionary.
+    valid_attribs = {key: value for key, value in root.attrib.items() if key in input_valid_attributes}
+    element_dict = convert_string_dict(valid_attribs)
+
+    subelements = list(root)
+    for subelement in subelements:
+        element_dict[subelement.tag] = parse_element_xml(subelement)
+
+    return element_dict
+
+
+@xml_root
+def parse_structure(root) -> dict:
+    """ Parse exciting input.xml structure element into python dictionary.
+
     :param root: Input for the parser.
     :returns: Dictionary containing the structure input element attributes and subelements. Looks like:
         {'atoms': List of atoms with atom positions in fractional coordinates,
          'lattice': List of 3 lattice vectors, 'species_path': species_path as string,
          'crystal_properties': dictionary with the crystal_properties,
          'species_properties': dictionary with the species_properties,
          all additional keys are structure attributes}
     """
     structure = find_element(root, 'structure')
-    structure_properties = structure.attrib
+    structure_properties = convert_string_dict(copy.deepcopy(structure.attrib))
     species_path = structure_properties.pop('speciespath')
+
     crystal = structure.find('crystal')
-    crystal_properties = crystal.attrib
+    crystal_properties = convert_string_dict(copy.deepcopy(crystal.attrib))
     lattice = []
-    for base_vect in crystal.findall('basevect'):
+    for base_vect in crystal:
         lattice.append([float(x) for x in base_vect.text.split()])
 
     atoms = []
     species_properties = {}
     for species in structure.findall('species'):
-        species_attributes = species.attrib
+        species_attributes = convert_string_dict(copy.deepcopy(species.attrib))
         species_file = species_attributes.pop('speciesfile')
         species_symbol = species_file[:-4]
-        species_properties[species_symbol] = species_attributes
-        for atom in species:
-            atom_attributes = atom.attrib
-            coord = [float(x) for x in atom_attributes.pop('coord').split()]
-            atom_dict = {'species': species_symbol, 'position': coord}
+
+        species_subelements = list(species)
+        atom_xml_trees = [x for x in species_subelements if x.tag == "atom"]
+        for atom in atom_xml_trees:
+            atom_attributes = convert_string_dict(copy.deepcopy(atom.attrib))
+            atom_dict = {'species': species_symbol, 'position': atom_attributes.pop('coord')}
             atom_dict.update(atom_attributes)
             atoms.append(atom_dict)
 
+        other_xml_trees = set(species_subelements) - set(atom_xml_trees)
+        for tree in other_xml_trees:
+            species_attributes[tree.tag] = parse_element_xml(tree)
+        species_properties[species_symbol] = species_attributes
+
     return {
         'atoms': atoms,
         'lattice': lattice,
         'species_path': species_path,
         'crystal_properties': crystal_properties,
         'species_properties': species_properties,
         **structure_properties
     }
 
 
-@xml_root
-def parse_xs(root: root_type) -> dict:
-    """
-    Parse exciting input.xml xs element into python dictionary.
-    :param root: Input for the parser.
-    :returns: Dictionary containing the xs input element attributes and subelements. Could look like:
-        {all toplevel xs_properties as dict keys,
-         'energywindow': dictionary with the energywindow_properties,
-         'screening': dictionary with the screening_properties, 'BSE': dictionary with bse_properties,
-         'qpointset': List of qpoints, 'plan': List of tasks}
-    """
-    valid_xml_elements = {'BSE', 'energywindow', 'screening'}
-    special_elements = {'qpointset', 'plan'}
-    all_valid_elements = valid_xml_elements | special_elements
-
-    xs = find_element(root, 'xs')
-    if xs is None:
-        return {}
-    xs_dict: dict = xs.attrib
-
-    subelements = {elem.tag: elem.attrib for elem in xs}
-    tags = set(subelements)
-    unsupported_tags = tags - all_valid_elements
-    supported_xml_tags = tags - unsupported_tags - special_elements
-
-    if unsupported_tags:
-        warnings.warn(f'Subelements {unsupported_tags} not yet supported. XS will ignore it.')
-
-    xs_dict.update({tag: subelements[tag] for tag in supported_xml_tags})
-
-    qpointset_xml = xs.find('qpointset')
-    if qpointset_xml:
-        qpointset = []
-        for qpoint in qpointset_xml:
-            qpointset.append([float(x) for x in qpoint.text.split()])
-        xs_dict['qpointset'] = qpointset
-
-    plan_xml = xs.find('plan')
-    if plan_xml:
-        xs_dict['plan'] = [doonly.attrib['task'] for doonly in plan_xml]
-
-    return xs_dict
-
-
-@xml_root
-def parse_input_xml(root: root_type) -> Dict[str, dict]:
-    """
-    Parse exciting input.xml into python dictionaries.
-    :param root: Input for the parser.
-    :returns: Dictionary which looks like: {'structure': structure_dict,
-        'ground_state': groundstate_dict, 'xs': xs_dict}.
-    """
-    title = parse_title(root)
-    structure = parse_structure(root)
-    ground_state = parse_groundstate(root)
-    xs = parse_xs(root)
-    return {'title': title, 'structure': structure, 'groundstate': ground_state, 'xs': xs}
+# special tag to parse function map or lambda if one-liner
+# necessary for tags which doesn't contain simply xml attributes and subtrees
+special_tags_to_parse_map = {"input": _parse_input_tag,
+                             "title": lambda root: root.text,
+                             "structure": parse_structure,
+                             "qpointset": lambda root: [[float(x) for x in qpoint.text.split()] for qpoint in root],
+                             "plan": lambda root: [doonly.attrib['task'] for doonly in root]}
```

### Comparing `excitingtools-1.2.0/excitingtools/exciting_dict_parsers/parser_factory.py` & `excitingtools-1.3.0/excitingtools/exciting_dict_parsers/parser_factory.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/excitingtools/exciting_dict_parsers/properties_parser.py` & `excitingtools-1.3.0/excitingtools/exciting_dict_parsers/properties_parser.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/excitingtools/exciting_dict_parsers/species_parser.py` & `excitingtools-1.3.0/excitingtools/exciting_dict_parsers/species_parser.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/excitingtools/exciting_obj_parsers/eigenvalue_parser.py` & `excitingtools-1.3.0/excitingtools/exciting_obj_parsers/eigenvalue_parser.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/excitingtools/exciting_obj_parsers/gw_eigenvalues.py` & `excitingtools-1.3.0/excitingtools/exciting_obj_parsers/gw_eigenvalues.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/excitingtools/exciting_obj_parsers/ks_band_structure.py` & `excitingtools-1.3.0/excitingtools/exciting_obj_parsers/ks_band_structure.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/excitingtools/input/base_class.py` & `excitingtools-1.3.0/excitingtools/input/base_class.py`

 * *Files 18% similar despite different names*

```diff
@@ -1,98 +1,126 @@
 """Base class for exciting input classes.
 """
+import importlib
 from abc import ABC, abstractmethod
-from typing import Union, Set, Callable
-from xml.etree import ElementTree
 from pathlib import Path
+from typing import Union, List, Type
+from xml.etree import ElementTree
+
 import numpy as np
 
+from excitingtools.exciting_dict_parsers.input_parser import parse_element_xml
+from excitingtools.utils import valid_attributes as all_valid_attributes
 from excitingtools.utils.dict_utils import check_valid_keys
 from excitingtools.utils.jobflow_utils import special_serialization_attrs
 
+path_type = Union[str, Path]
 
-class ExcitingInput(ABC):
+
+class AbstractExcitingInput(ABC):
     """Base class for exciting inputs."""
-    name = "base"
+
+    @property
+    @abstractmethod
+    def name(self) -> str:
+        """ Tag of the xml subelement. """
+        ...
 
     @abstractmethod
     def to_xml(self) -> ElementTree:
         """ Convert class attributes to XML ElementTree."""
         ...
 
 
-class ExcitingXMLInput(ExcitingInput):
-    """Base class for exciting inputs that only consist of many attributes."""
+class ExcitingXMLInput(AbstractExcitingInput, ABC):
+    """Base class for exciting inputs, with exceptions being title, plan and qpointset,
+     because they are not passed as a dictionary. """
 
     # Convert python data to string, formatted specifically for
     _attributes_to_input_str = {int: lambda x: str(x),
                                 np.int64: lambda x: str(x),
                                 np.float64: lambda x: str(x),
                                 float: lambda x: str(x),
                                 bool: lambda x: str(x).lower(),
                                 str: lambda x: x,
                                 list: lambda mylist: " ".join(str(x).lower() for x in mylist).strip(),
                                 tuple: lambda mylist: " ".join(str(x).lower() for x in mylist).strip()
                                 }
-    _valid_attributes: Set[str] = None
-    parse_element: Callable = lambda x: x
-
-    @staticmethod
-    def _initialise_subelement_attribute(XMLClass, element, skip_none: bool = True):
-        """
-        Initialize given elements to the ExcitingXSInput constructor. If element is already ExcitingXMLInput class
-        object, nothing happens. For None elements None is returned. In any other case, the class constructor of the
-        given XSClass is called.
-        :param skip_none: if False, add empty subtree without attributes for given element
-        """
-        if isinstance(element, XMLClass):
-            return element
-        elif element is None and skip_none:
-            return None
-        elif element is None and not skip_none:
-            return XMLClass()
-        elif isinstance(element, dict):  # assume kwargs
-            return XMLClass(**element)
-        else:
-            # Assume the element type is valid for the class constructor
-            return XMLClass(element)
 
     def __init__(self, **kwargs):
         """Initialise class attributes with kwargs.
 
         Rather than define all options for a given method, pass as kwargs and directly
         insert as class attributes.
 
-        :param name: Method name.
+        Valid attributes, subtrees and mandatory attributes are taken automatically from
+        the parsed schema, see [valid_attributes.py](excitingtools/utils/valid_attributes.py).
         """
-        if self._valid_attributes:
-            check_valid_keys(kwargs.keys(), self._valid_attributes, self.name)
+        valid_attributes = set(all_valid_attributes.__dict__.get(self.name + "_valid_attributes", set()))
+        valid_subtrees = all_valid_attributes.__dict__.get(self.name + "_valid_subtrees", [])
+        mandatory_keys = set(all_valid_attributes.__dict__.get(self.name + "_mandatory_attributes", set()))
+
+        # check the keys
+        missing_mandatory_keys = mandatory_keys - set(kwargs.keys())
+        if missing_mandatory_keys:
+            raise ValueError(f"Missing mandatory arguments: {missing_mandatory_keys}")
+        check_valid_keys(kwargs.keys(), valid_attributes | set(valid_subtrees), self.name)
+
+        # initialise the subtrees
+        class_list = self._class_list_from_module()
+        subtree_class_map = {cls.name: cls for cls in class_list}
+        subtrees = set(kwargs.keys()) - valid_attributes
+        for subtree in subtrees:
+            kwargs[subtree] = self._initialise_subelement_attribute(subtree_class_map[subtree], kwargs[subtree])
+
+        # Set attributes from kwargs
         self.__dict__.update(kwargs)
 
-    def to_xml(self, **kwargs) -> ElementTree:
+    def _class_list_from_module(self) -> List[Type[AbstractExcitingInput]]:
+        """ Find all exciting input classes in own module and excitingtools.
+        """
+        excitingtools_contents = importlib.import_module("excitingtools").__dict__
+        module_contents = importlib.import_module(type(self).__module__).__dict__
+        all_contents = {**excitingtools_contents, **module_contents}.values()
+        return [cls for cls in all_contents if isinstance(cls, type) and issubclass(cls, AbstractExcitingInput)]
+
+    @staticmethod
+    def _initialise_subelement_attribute(XMLClass, element):
+        """ Initialize given elements to the ExcitingXSInput constructor. If element is already ExcitingXMLInput class
+        object, nothing happens. Else the class constructor of the given XMLClass is called. For a passed
+        dictionary the dictionary is passed as kwargs.
+        """
+        if isinstance(element, XMLClass):
+            return element
+        elif isinstance(element, dict):
+            # assume kwargs
+            return XMLClass(**element)
+        else:
+            # Assume the element type is valid for the class constructor
+            return XMLClass(element)
+
+    def to_xml(self) -> ElementTree:
         """Put class attributes into an XML tree, with the element given by self.name.
 
         Example ground state XML subtree:
            <groundstate vkloff="0.5  0.5  0.5" ngridk="2 2 2" mixer="msec" </groundstate>
 
         Note, kwargs preserve the order of the arguments, however the order does not appear to be
         preserved when passed to (or perhaps converted to string) with xml.etree.ElementTree.tostring.
 
-        kwargs argument allows to specify additional attributes.
-
         :return ElementTree.Element sub_tree: sub_tree element tree, with class attributes inserted.
         """
-        none_keys = set([key for key, value in vars(self).items() if value is None])
         attributes = {key: self._attributes_to_input_str[type(value)](value) for key, value
-                      in vars(self).items() if value is not None and not isinstance(value, ExcitingInput)}
-        subtrees = [self.__dict__[key] for key in set(vars(self).keys()) - set(attributes.keys()) - none_keys]
+                      in vars(self).items() if not isinstance(value, AbstractExcitingInput)}
+        xml_tree = ElementTree.Element(self.name, **attributes)
 
-        xml_tree = ElementTree.Element(self.name, **attributes, **kwargs)
-
-        for subtree in subtrees:
+        valid_subtrees = all_valid_attributes.__dict__.get(self.name + "_valid_subtrees", [])
+        subtrees = {key: self.__dict__[key] for key in set(vars(self).keys()) - set(attributes.keys())}
+        ordered_subtrees = [subtrees[x] for x in valid_subtrees if x in subtrees]
+        for subtree in ordered_subtrees:
             xml_tree.append(subtree.to_xml())
 
         # Seems to want this operation on a separate line
         xml_tree.text = ' '
 
         return xml_tree
 
@@ -102,30 +130,30 @@
 
     def as_dict(self) -> dict:
         """ Convert attributes to dictionary. """
         serialise_attrs = special_serialization_attrs(self)
         return {**serialise_attrs, "xml_string": self.to_xml_str()}
 
     @classmethod
-    def from_xml(cls, xml_string: str):
+    def from_xml(cls, xml_string: path_type):
         """ Initialise class instance from XML-formatted string.
 
         Example Usage
         --------------
         xs_input = ExcitingXSInput.from_xml(xml_string)
         """
-        return cls(**cls.parse_element(xml_string))
+        return cls(**parse_element_xml(xml_string, tag=cls.name))
 
     @classmethod
     def from_dict(cls, d):
         """ Recreates class instance from dictionary. """
         return cls.from_xml(d["xml_string"])
 
 
-def query_exciting_version(exciting_root: Union[Path, str]) -> dict:
+def query_exciting_version(exciting_root: path_type) -> dict:
     """Query the exciting version
     Inspect version.inc, which is constructed at compile-time.
 
     Assumes version.inc has this structure:
      #define GITHASH "1a2087b0775a87059d53"
      #define GITHASH2 "5d01a5475a10f00d0ad7"
      #define COMPILERVERSION "GNU Fortran (MacPorts gcc9 9.3.0_4) 9.3.0"
```

### Comparing `excitingtools-1.2.0/excitingtools/input/common.py` & `excitingtools-1.3.0/excitingtools/input/xs.py`

 * *Files 18% similar despite different names*

```diff
@@ -1,59 +1,88 @@
-""" Common input. """
-from typing import List, Union
+"""Module for class of exciting xs (excited states).
+https://exciting.wikidot.com/ref:xs
+"""
+from typing import Optional, List, Union
 from xml.etree import ElementTree
 
-from excitingtools.input.base_class import ExcitingXMLInput
+import numpy as np
 
+from excitingtools.input.base_class import AbstractExcitingInput, ExcitingXMLInput
+from excitingtools.utils.dict_utils import check_valid_keys
+from excitingtools.utils.utils import list_to_str
+from excitingtools.utils.valid_attributes import valid_plan_entries
 
-class ExcitingPointInput(ExcitingXMLInput):
+
+class ExcitingXSBSEInput(ExcitingXMLInput):
     """
-    Class for exciting point input.
+    Class for exciting BSE Input
     """
-    name = "point"
-    _valid_attributes = {"coord", "breakafter", "label"}
+    name = "BSE"
 
 
-class ExcitingPathInput(ExcitingXMLInput):
+class ExcitingXSScreeningInput(ExcitingXMLInput):
     """
-    Class for exciting path input.
+    Class for exciting Screening Input
     """
-    name = "path"
-    _valid_attributes = {"steps", "outfileprefix"}
+    name = "screening"
+
 
-    def __init__(self,
-                 points: List[Union[dict, ExcitingPointInput]],
-                 **kwargs):
-        """Generate an object of ExcitingXMLInput for the path attributes."""
-        super().__init__(**kwargs)
+class ExcitingXSEnergywindowInput(ExcitingXMLInput):
+    """
+    Class for exciting Energywindow Input
+    """
+    name = "energywindow"
 
-        # for i, point in enumerate(points):
-        #     setattr(self, f"point-{i}", self._initialise_subelement_attribute(ExcitingPointInput, point))
-        self.points = [self._initialise_subelement_attribute(ExcitingPointInput, point) for point in points]
-        # self.point = self._initialise_subelement_attribute(ExcitingPlot1dInput, points)
 
-    def to_xml(self) -> ElementTree:
-        """Put class attributes into an XML tree, with the element given by self.name.
-        :return ElementTree.Element sub_tree: sub_tree element tree, with class attributes inserted.
+class ExcitingXSQpointsetInput(AbstractExcitingInput):
+    """
+    Class for exciting Qpointset Input
+    """
+    name = "qpointset"
+
+    def __init__(self, qpointset: Optional[Union[np.ndarray, List[List[float]]]] = np.array([0.0, 0.0, 0.0])):
         """
-        attributes = {key: self._attributes_to_input_str[type(value)](value) for key, value
-                      in vars(self).items() if key != "points"}
-        xml_tree = ElementTree.Element(self.name, **attributes)
+        Qpointset should be passed either as numpy array or as a list of lists, so either
+        np.array([[0., 0., 0.], [0.0, 0.0, 0.01], ...])
+        or
+        [[0., 0., 0.], [0.0, 0.0, 0.01], ...]
+        """
+        self.qpointset = qpointset
 
-        for point in self.points:
-            xml_tree.append(point.to_xml())
+    def to_xml(self) -> ElementTree.Element:
+        """ Special implementation of to_xml for the qpointset element. """
+        qpointset = ElementTree.Element(self.name)
+        for qpoint in self.qpointset:
+            ElementTree.SubElement(qpointset, 'qpoint').text = list_to_str(qpoint)
 
-        return xml_tree
+        return qpointset
 
 
-class ExcitingPlot1dInput(ExcitingXMLInput):
+class ExcitingXSPlanInput(AbstractExcitingInput):
     """
-    Class for exciting plot 1d input.
+    Class for exciting Plan Input
     """
-    name = "plot1d"
+    name = "plan"
+
+    def __init__(self, plan: List[str]):
+        """
+        Plan doonly elements are passed as a List of strings in the order exciting shall execute them:
+            ['bse', 'xseigval', ...]
+        """
+        check_valid_keys(plan, valid_plan_entries, self.name)
+        self.plan = plan
+
+    def to_xml(self) -> ElementTree.Element:
+        """ Special implementation of to_xml for the plan element. """
+        plan = ElementTree.Element(self.name)
+        for task in self.plan:
+            ElementTree.SubElement(plan, 'doonly', task=task)
+
+        return plan
+
 
-    def __init__(self,
-                 path: Union[dict, ExcitingPathInput]):
-        """Generate an object of ExcitingXMLInput for the plot 1d attributes."""
-        super().__init__()
+class ExcitingXSInput(ExcitingXMLInput):
+    """ Class allowing to write attributes to XML."""
 
-        self.path = self._initialise_subelement_attribute(ExcitingPathInput, path)
+    # TODO(Fabian): Add all the other subelements, see http://exciting.wikidot.com/ref:xs
+    # Issue 121: https://git.physik.hu-berlin.de/sol/exciting/-/issues/121
+    name = "xs"
```

### Comparing `excitingtools-1.2.0/excitingtools/input/structure.py` & `excitingtools-1.3.0/excitingtools/input/structure.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,105 +1,105 @@
 """Structure class, mirroring that of exciting's structure XML sub-tree.
-http://exciting.wikidot.com/ref:structure
+https://exciting.wikidot.com/ref:structure
 """
-from typing import Optional, Union, List, Dict
 from pathlib import Path
+from typing import Optional, Union, List, Dict
 from xml.etree import ElementTree
 
-from excitingtools.exciting_dict_parsers.input_parser import parse_structure
-from excitingtools.utils.utils import list_to_str
-from excitingtools.utils.dict_utils import check_valid_keys
-from excitingtools.structure.lattice import check_lattice, check_lattice_vector_norms
 from excitingtools.input.base_class import ExcitingXMLInput
-
-
-# Set of all elements
-all_species = {'Ni', 'La', 'K', 'Xe', 'Ag', 'Bk', 'Co', 'Md', 'Lu', 'Ar',
-               'Bi', 'Cm', 'H', 'Yb', 'Zn', 'Te', 'I', 'Cl', 'As', 'Mg',
-               'No', 'Ta', 'N', 'Ac', 'Y', 'At', 'Tb', 'Tc', 'Au', 'O',
-               'Lr', 'In', 'Ge', 'Re', 'Pm', 'Gd', 'Kr', 'Po', 'Sc', 'Rf',
-               'Sb', 'Rb', 'Ru', 'Dy', 'Ho', 'Ra', 'Se', 'Sr', 'Fr', 'Ga',
-               'Fe', 'Es', 'Si', 'Pr', 'Pd', 'Er', 'Rn', 'Ir', 'He', 'Eu',
-               'Pt', 'Pu', 'Sn', 'Pb', 'Hf', 'Fm', 'Rh', 'Sm', 'Pa', 'Hg',
-               'Os', 'B', 'U', 'Zr', 'Cf', 'C', 'Na', 'Li', 'Mo', 'Cs',
-               'Al', 'V', 'Cd', 'Tm', 'Tl', 'Ba', 'Ce', 'W', 'Am', 'Cr',
-               'Nb', 'Mn', 'S', 'Ca', 'Be', 'Br', 'Th', 'Ti', 'Np', 'Ne',
-               'P', 'Cu', 'F', 'Nd'}
+from excitingtools.structure.lattice import check_lattice, check_lattice_vector_norms
+from excitingtools.utils import valid_attributes
+from excitingtools.utils.utils import list_to_str
+from excitingtools.constants.units import angstrom_to_bohr
 
 
 class ExcitingStructureCrystalInput(ExcitingXMLInput):
     """
     Class for exciting structure crystal input.
     """
     name = "crystal"
-    _valid_attributes = {'scale', 'stretch'}
 
 
 class ExcitingStructureSpeciesInput(ExcitingXMLInput):
     """
     Class for exciting structure species input.
     """
     name = "species"
-    _valid_attributes = {'rmt'}
+
+
+class ExcitingStructureLDAplusUInput(ExcitingXMLInput):
+    """
+    Class for exciting structure LDAplusU input.
+    """
+    name = "LDAplusU"
+
+
+class ExcitingStructureDfthalfparamInput(ExcitingXMLInput):
+    """
+    Class for exciting structure dfthalfparam input.
+    """
+    name = "dfthalfparam"
+
+
+class ExcitingStructureShellInput(ExcitingXMLInput):
+    """
+    Class for exciting structure shell input.
+    """
+    name = "shell"
 
 
 class ExcitingStructure(ExcitingXMLInput):
     """ Class allowing exciting XML structure to be written from python data.
-
-    TODO(Fabian/Alex) 117. Implement all remaining attributes:
-     All elements are species-specific. They should be passed like:
-     species_properties = {'S': {'LDAplusU':{'J': J, 'U': U, 'l': l}} }
-     Element: LDAplusU: J, U, l
-     Element: dfthalfparam: ampl, cut, exponent
-     Element: shell: ionization, number
     """
     name = "structure"
-    parse_element = parse_structure
     # Path type
     path_type = Union[str, Path]
 
-    # Mandatory attributes not specified
-    _valid_attributes = {'autormt', 'cartesian', 'epslat', 'primcell', 'tshift'}
-    _valid_atom_attributes = {'bfcmt', 'lockxyz', 'mommtfix'}
+    # Mandatory attribute "coord" taken out because it's specified inside the atoms
+    _valid_atom_attributes = set(valid_attributes.atom_valid_attributes) - {"coord"}
 
     def __init__(self,
                  atoms,
                  lattice: Optional[list] = None,
                  species_path: Optional[path_type] = './',
                  crystal_properties: Optional[Union[dict, ExcitingStructureCrystalInput]] = None,
                  species_properties: Optional[Dict[str, Union[dict, ExcitingStructureSpeciesInput]]] = None,
                  **kwargs):
         """ Initialise instance of ExcitingStructure.
 
         TODO(Alex) Issue 117. Create our own class with a subset of methods common to ASE' Atom()
           Then we can have a single API for this init. If ASE is used, xAtom() is just a wrapper of
           Atom(), else we have some light methods.
-        TODO(Alex/Fabian) Issue 117.
-          structure_attributes and crystal_attributes could equally be kwargs.
-          Consider changing or extending before the first major version.
+
+        All valid attributes can be found in the module valid_attributes.py
 
         :param atoms: Atoms object of type ase.atoms.Atoms or of the form List[dict], for example:
          atoms = [{'species': 'X', 'position': [x, y, z]}, ...].
          Each dict can also optionally contain the _valid_atom_attributes:
          {'species': 'X', 'position': [x, y, z],
            'bfcmt': [bx, by, bz], 'lockxyz': [lx, ly, lz], 'mommtfix': [mx, my, mz]}.
         If atoms are defined with ASE, optional atomic_properties cannot be specified.
         Eventually, the list of atoms will be replaced with our custom class, which will extend ase.Atoms()
         with the additional, optional attributes.
+        Species value can be a file_name without the suffix '.xml', which will be added automatically.
 
         :param lattice [a, b, c], where a, b and c are lattice vectors with 3 components.
          For example, a = [ax, ay, az]. Only required if one does not pass an ase Atoms object.
         :param species_path: Optional path to the location of species file/s.
-        :param crystal_properties: Optional crystal properties. See _valid_crystal_attributes
+        :param crystal_properties: Optional crystal properties.
         :param species_properties: Optional species properties, defined as:
         {'species1': {'rmt': rmt_value}, 'species2': {'rmt': rmt_value}}
-        :param kwargs: Optional structure properties. Passed as kwargs. See _valid_attributes
-        """
-        super().__init__(**kwargs)
-        self.structure_attributes = kwargs
+        and with subtrees as:
+        {'species1': {'rmt': rmt_value, 'LDAplusU': {'J': J, 'U': U, 'l': l}}, species2: ... }
+        :param kwargs: Optional structure properties. Passed as kwargs.
+        """
+        if isinstance(species_path, Path):
+            species_path = species_path.as_posix()
+        super().__init__(speciespath=species_path, **kwargs)
+        self.structure_attributes = {"speciespath": species_path, **kwargs}
 
         if isinstance(atoms, list) and lattice is None:
             raise ValueError("If atoms is a list, lattice must be passed as a separate argument.")
 
         # Simple container for atoms, as documented in __init__.
         if isinstance(atoms, list):
             check_lattice(lattice)
@@ -108,40 +108,39 @@
             self.species = [atom['species'].capitalize() for atom in atoms]
             self.positions = [atom['position'] for atom in atoms]
             self.atom_properties = self._init_atom_properties(atoms)
         else:
             self.lattice, self.species, self.positions = self._init_lattice_species_positions_from_ase_atoms(atoms)
             self.atom_properties = [{}] * len(self.species)
 
-        self.species_path = Path(species_path)
         self.unique_species = sorted(set(self.species))
 
-        # Catch symbols that are not valid elements
-        check_valid_keys(self.unique_species, all_species, name='Species input')
-
         # Optional properties
         self.crystal_properties = self._initialise_subelement_attribute(ExcitingStructureCrystalInput,
-                                                                        crystal_properties, skip_none=False)
-        self.species_properties = self._init_species_properties(species_properties)
+                                                                        crystal_properties or {})
+        self.species_properties = dict(self._init_species_properties(species_properties))
 
-    @staticmethod
-    def _init_lattice_species_positions_from_ase_atoms(atoms) -> tuple:
+    def _init_lattice_species_positions_from_ase_atoms(self, atoms) -> tuple:
         """ Initialise lattice, species and positions from an ASE Atoms Object.
 
         Duck typing for atoms, such that ASE is not a hard dependency.
 
         :param atoms: ASE Atoms object.
         :return  Lattice, species, positions: Lattice, species and positions
         """
         try:
             cell = atoms.get_cell()
             # Convert to consistent form, [a, b, c], where a = [ax, ay, az]
-            lattice = [list(cell[i, :]) for i in range(0, 3)]
+            # Additionally, ASE works in Angstrom, whereas exciting expects atomic units
+            lattice = [list(angstrom_to_bohr * cell[i, :]) for i in range(0, 3)]
             species = [x.capitalize() for x in atoms.get_chemical_symbols()]
-            positions = atoms.get_positions()
+            if self.structure_attributes.get("cartesian"):
+                positions = angstrom_to_bohr * atoms.get_positions()
+            else:
+                positions = atoms.get_scaled_positions()
             return lattice, species, positions
         except AttributeError:
             message = "atoms must either be an ase.atoms.Atoms object or List[dict], of the form" \
                       "[{'species': 'X', 'position': [x, y, z]}, ...]."
             raise AttributeError(message)
 
     def _init_atom_properties(self, atoms: List[dict]) -> List[dict]:
@@ -178,17 +177,18 @@
 
         :param species_properties: Species properties
         :return Dict of ExitingXMLInput-species_properties.
         """
         if species_properties is None:
             species_properties = {}
 
-        return {species: self._initialise_subelement_attribute(
-            ExcitingStructureSpeciesInput, species_properties.get(species), skip_none=False
-        ) for species in self.unique_species}
+        for species in self.unique_species:
+            props = species_properties.get(species) or {}
+            props["speciesfile"] = species + '.xml'
+            yield species, self._initialise_subelement_attribute(ExcitingStructureSpeciesInput, props)
 
     def _group_atoms_by_species(self) -> dict:
         """Get the atomic indices for atoms of each species.
 
         For example, for:
           species = ['Cd', 'S', 'Cd]
         return:
@@ -231,24 +231,24 @@
           </structure>
 
         :return ET structure: Element tree containing structure attributes.
         """
         structure_attributes = {
             key: self._attributes_to_input_str[type(value)](value) for key, value in self.structure_attributes.items()
         }
-        structure = ElementTree.Element(self.name, speciespath=self.species_path.as_posix(), **structure_attributes)
+        structure = ElementTree.Element(self.name, **structure_attributes)
         structure.text = ' '
 
         # Lattice vectors
         crystal = self.crystal_properties.to_xml()
         structure.append(crystal)
         for vector in self.lattice:
             ElementTree.SubElement(crystal, "basevect").text = list_to_str(vector)
 
         # Species tags
         atomic_indices = self._group_atoms_by_species()
         for x in self.unique_species:
-            species = self.species_properties[x].to_xml(speciesfile=x + '.xml')
+            species = self.species_properties[x].to_xml()
             structure.append(species)
             self._xml_atomic_subtree(x, species, atomic_indices)
 
         return structure
```

### Comparing `excitingtools-1.2.0/excitingtools/input/xml_utils.py` & `excitingtools-1.3.0/excitingtools/input/xml_utils.py`

 * *Ordering differences only*

 * *Files 2% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """Utilities to aid in writing and formatting XML
 """
+import re
 from typing import Union, List
 from xml.dom import minidom
 from xml.etree import ElementTree
-import re
 
 
 def xml_tree_to_pretty_str(elem: ElementTree.Element) -> str:
     """Convert an XML element to a pretty string.
 
     :param ElementTree.Element elem: Element/ element tree
     :return str : XML tree string, with pretty formatting.
```

### Comparing `excitingtools-1.2.0/excitingtools/math/math_utils.py` & `excitingtools-1.3.0/excitingtools/math/math_utils.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/excitingtools/parser_utils/grep_parser.py` & `excitingtools-1.3.0/excitingtools/parser_utils/grep_parser.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/excitingtools/parser_utils/parser_decorators.py` & `excitingtools-1.3.0/excitingtools/parser_utils/parser_decorators.py`

 * *Files 26% similar despite different names*

```diff
@@ -1,13 +1,12 @@
 """Decorators and wrappers for parser functions.
 """
-from typing import Callable, Union
-import os
-import xml.etree.ElementTree as ET
 import pathlib
+import xml.etree.ElementTree as ET
+from typing import Callable, Union
 
 
 def return_file_string(file_name: Union[str, pathlib.Path]) -> str:
     """ Given a file name, return the file contents as a string.
 
     :param file_name: File name.
     :return file_string: File contents string.
@@ -49,29 +48,31 @@
 
 
 def xml_root(func: Callable):
     """ Decorate XML parsers, enabling the developer to pass
     an XML file name, XML string or ElementTree.Element as input
     and return the XML root.
     """
-    def modified_func(input: str):
+    function_selection = {type(None): lambda x, y: func(x), str: lambda x, y: func(x, y)}
+
+    def modified_func(input: str, tag: str = None):
         # Element
         if isinstance(input, ET.Element):
-            return func(input)
+            return function_selection[type(tag)](input, tag)
 
         # File name
         try:
             tree = ET.parse(input)
             root = tree.getroot()
-            return func(root)
+            return function_selection[type(tag)](root, tag)
         except (FileNotFoundError, OSError):
             pass
 
         # XML string
         try:
             root = ET.fromstring(input)
-            return func(root)
-        except ET.ParseError:
+            return function_selection[type(tag)](root, tag)
+        except (ET.ParseError, TypeError):
             raise ValueError(f'Input string neither an XML file, '
                              f'nor valid XML: {input}')
 
     return modified_func
```

### Comparing `excitingtools-1.2.0/excitingtools/parser_utils/regex_parser.py` & `excitingtools-1.3.0/excitingtools/parser_utils/regex_parser.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/excitingtools/parser_utils/simple_parser.py` & `excitingtools-1.3.0/excitingtools/parser_utils/simple_parser.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/excitingtools/runner/runner.py` & `excitingtools-1.3.0/excitingtools/runner/runner.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/excitingtools/structure/lattice.py` & `excitingtools-1.3.0/excitingtools/structure/lattice.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/excitingtools/utils/dict_utils.py` & `excitingtools-1.3.0/excitingtools/utils/dict_utils.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,15 +1,16 @@
 """ Dictionary Utilities.
 """
-from typing import Optional, Iterator, Union
-import json
-import numpy as np
 import copy
-from collections.abc import Mapping, Hashable, KeysView
+import json
 import sys
+from collections.abc import Mapping, Hashable, KeysView
+from typing import Iterator, Union
+
+import numpy as np
 
 
 def common_iterable(obj: Union[dict, list]):
     """
     Create an iterable dict or tuple, such that one can iterate over a
     dictionary or list with the same syntax:
 
@@ -139,15 +140,15 @@
         return
     else:
         delete_nested_key(dictionary[key_chain[0]], key_chain[1:])
 
 
 def check_valid_keys(input_keys: Union[list, set, tuple, KeysView],
                      valid_keys: Union[list, set, tuple, KeysView],
-                     name: Optional[str] = ''):
+                     name: str = ''):
     """ Check that a given set of input keys are valid.
 
     :param input_keys: Input keys
     :param valid_keys: Valid keys
     :param name: Optional name for error message
     """
     erroneous_inputs = set(input_keys) - set(valid_keys)
```

### Comparing `excitingtools-1.2.0/excitingtools/utils/test_utils.py` & `excitingtools-1.3.0/excitingtools/utils/test_utils.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/excitingtools/utils/utils.py` & `excitingtools-1.3.0/excitingtools/utils/utils.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,11 +1,17 @@
-"""General utility functions. Typically conversion/type-checking.
+"""General utility functions. Typically, conversion/type-checking.
 """
-from typing import Union, List, Optional, Callable
+import pathlib
 import re
+from typing import Union, List, Optional, Callable
+
+
+def get_excitingtools_root() -> pathlib.Path:
+    """ Get the root directory of excitingtools. """
+    return pathlib.Path(__file__).parents[2]
 
 
 def can_be_float(value) -> bool:
     """
     Check if a value can be interpreted as a float
 
     :param value: Input
```

### Comparing `excitingtools-1.2.0/excitingtools.egg-info/PKG-INFO` & `excitingtools-1.3.0/excitingtools.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: excitingtools
-Version: 1.2.0
+Version: 1.3.0
 Summary: Utilities for aiding in the construction of exciting inputs and the postprocessing exciting outputs.
 Author-email: Alexander Buccheri <alexander.buccheri@mpsd.mpg.de>, Fabian Peschel <peschelf@physik.hu-berlin.de>
 License: ### GNU GENERAL PUBLIC LICENSE
         
         Version 3, 29 June 2007
         
         Copyright (C) 2007 Free Software Foundation, Inc.
@@ -678,14 +678,16 @@
         applications with the library. If this is what you want to do, use the
         GNU Lesser General Public License instead of this License. But first,
         please read <https://www.gnu.org/licenses/why-not-lgpl.html>.
 Project-URL: repository, https://github.com/exciting/excitingtools
 Requires-Python: >=3.6
 Description-Content-Type: text/markdown
 Provides-Extra: dev
+License-File: COPYING.LESSER
+License-File: COPYING.md
 
 # excitingtools
 <span style="font-family:american typewriter; font-size:1em;">**excitingtools**</span> is a collection of 
 modules to facilitate the generation of <span style="font-family:american typewriter; font-size:1em;">**exciting**</span>
 inputs and the post-processing of <span style="font-family:american typewriter; font-size:1em;">**exciting**</span> outputs. 
 
 <span style="font-family:american typewriter; font-size:1em;">**excitingtools**</span> currently provides functionality for:
```

### Comparing `excitingtools-1.2.0/excitingtools.egg-info/SOURCES.txt` & `excitingtools-1.3.0/excitingtools.egg-info/SOURCES.txt`

 * *Files 10% similar despite different names*

```diff
@@ -1,8 +1,7 @@
-.gitignore
 .pylintrc
 .style.yapf
 CITATION.cff
 CONTRIBUTING.md
 COPYING.LESSER
 COPYING.md
 README.md
@@ -40,18 +39,16 @@
 excitingtools/exciting_obj_parsers/__init__.py
 excitingtools/exciting_obj_parsers/eigenvalue_parser.py
 excitingtools/exciting_obj_parsers/gw_eigenvalues.py
 excitingtools/exciting_obj_parsers/input_xml.py
 excitingtools/exciting_obj_parsers/ks_band_structure.py
 excitingtools/input/__init__.py
 excitingtools/input/base_class.py
-excitingtools/input/common.py
 excitingtools/input/ground_state.py
 excitingtools/input/input_xml.py
-excitingtools/input/properties.py
 excitingtools/input/structure.py
 excitingtools/input/xml_utils.py
 excitingtools/input/xs.py
 excitingtools/math/__init__.py
 excitingtools/math/math_utils.py
 excitingtools/parser_utils/__init__.py
 excitingtools/parser_utils/erroneous_file_error.py
@@ -62,16 +59,18 @@
 excitingtools/parser_utils/simple_parser.py
 excitingtools/runner/__init__.py
 excitingtools/runner/runner.py
 excitingtools/structure/lattice.py
 excitingtools/utils/__init__.py
 excitingtools/utils/dict_utils.py
 excitingtools/utils/jobflow_utils.py
+excitingtools/utils/schema_parsing.py
 excitingtools/utils/test_utils.py
 excitingtools/utils/utils.py
+excitingtools/utils/valid_attributes.py
 paper/joss_latex.template
 paper/latex.template
 paper/paper.bib
 paper/paper.md
 tests/__init__.py
 tests/conftest.py
 tests/dataclasses/__init__.py
@@ -93,27 +92,28 @@
 tests/dict_parsers/test_gw/test_gw_vxc_parser.py
 tests/eigenstates/__init__.py
 tests/eigenstates/test_eigenstates.py
 tests/input/__init__.py
 tests/input/test_base_class.py
 tests/input/test_ground_state.py
 tests/input/test_input_xml.py
-tests/input/test_properties.py
 tests/input/test_structure.py
 tests/input/test_xml_utils.py
 tests/input/test_xs.py
 tests/math/__init__.py
 tests/math/test_math_utils.py
 tests/obj_parsers/__init__.py
 tests/obj_parsers/test_eigenvalue_parser.py
 tests/obj_parsers/test_gw_dos.py
 tests/obj_parsers/test_gw_eigenvalues.py
 tests/obj_parsers/test_input_parser.py
 tests/parser_utils/__init__.py
+tests/parser_utils/test_parser_utils.py
 tests/parser_utils/test_regex_parser.py
 tests/parser_utils/test_simple_parser.py
 tests/runner/test_runner.py
 tests/structure/__init__.py
 tests/structure/test_lattice.py
 tests/utils/__init__.py
 tests/utils/test_dict_utils.py
+tests/utils/test_schema_parsing.py
 tests/utils/test_utils.py
```

### Comparing `excitingtools-1.2.0/paper/joss_latex.template` & `excitingtools-1.3.0/paper/joss_latex.template`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/paper/latex.template` & `excitingtools-1.3.0/paper/latex.template`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/paper/paper.bib` & `excitingtools-1.3.0/paper/paper.bib`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/paper/paper.md` & `excitingtools-1.3.0/paper/paper.md`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/pyproject.toml` & `excitingtools-1.3.0/pyproject.toml`

 * *Files 12% similar despite different names*

```diff
@@ -1,23 +1,22 @@
 [project]
 name = "excitingtools"
 description = "Utilities for aiding in the construction of exciting inputs and the postprocessing exciting outputs."
-version = "1.2.0"
+version = "1.3.0"
 authors = [
     { name = "Alexander Buccheri", email = "alexander.buccheri@mpsd.mpg.de"},
     { name = "Fabian Peschel",     email = "peschelf@physik.hu-berlin.de"}
 ]
 license = {file = "COPYING.md"}
 readme = "README.md"
 requires-python = ">=3.6"
 
 dependencies = [
-    'wheel>=0.35.0',
     'numpy>=1.14.5',
-    'matplotlib>=2.2.0',
+    'matplotlib>=2.2.0'
 ]
 
 [project.optional-dependencies]
 dev = [
     "pytest",
     "ase>=3.20.0"
 ]
```

### Comparing `excitingtools-1.2.0/tests/dataclasses/test_band_structure.py` & `excitingtools-1.3.0/tests/dataclasses/test_band_structure.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/tests/dataclasses/test_eigenvalues.py` & `excitingtools-1.3.0/tests/dataclasses/test_eigenvalues.py`

 * *Files 20% similar despite different names*

```diff
@@ -28,23 +28,27 @@
 
     ref_k_points = np.array([[0.000000, 0.000000, 0.000000],
                              [0.000000, 0.000000, 0.500000],
                              [0.000000, 0.500000, 0.500000]])
 
     ref_weights = [0.125, 0.5, 0.375000]
 
-    eigen_values = EigenValues(NumberOfStates(19, 24), ref_k_points, [1, 2, 3], ref_gw_eigenvalues, ref_weights)
+    ref_occupations = np.array([[2, 2, 2, 0, 0, 0], [2, 2, 2, 0, 0, 0], [2, 2, 2, 0, 0, 0]])
+
+    eigen_values = EigenValues(NumberOfStates(19, 24), ref_k_points, [1, 2, 3], ref_gw_eigenvalues, ref_weights,
+                               ref_occupations)
 
     assert ref_gw_eigenvalues.shape == (len(eigen_values.k_points), eigen_values.state_range.n_states)
     assert eigen_values.state_range.first_state == 19
     assert eigen_values.state_range.last_state == 24
     assert np.allclose(eigen_values.k_points, ref_k_points)
     assert eigen_values.k_indices == [1, 2, 3]
     assert np.allclose(eigen_values.all_eigenvalues, ref_gw_eigenvalues), "GW column eigenvalues, for all k-points"
     assert eigen_values.weights == ref_weights
+    assert np.allclose(eigen_values.occupations, ref_occupations)
     return eigen_values
 
 
 def test_class_eigenvalues_get_array_index(eigenvalues_instance):
     assert eigenvalues_instance.get_array_index(19) == 0, "Index of first state in array"
     assert eigenvalues_instance.get_array_index(24) == 5, "Index of last state in array"
     assert eigenvalues_instance.state_range.n_states == 6, "Total number of states"
@@ -87,7 +91,22 @@
     k_conduction = [0.000, 0.000, 0.000]
 
     indirect_band_gap = eigenvalues_instance.band_gap(BandIndices(21, 22), k_points=[k_valence, k_conduction])
     direct_band_gap_at_Gamma = eigenvalues_instance.band_gap(BandIndices(21, 22), k_points=[k_conduction, k_conduction])
 
     assert np.isclose(indirect_band_gap, 0.19767), 'Indirect band gap in Ha'
     assert np.isclose(direct_band_gap_at_Gamma, 0.218540887), 'Direct band gap at Gamma, in Ha'
+
+
+def test_class_eigenvalues_get_transition_energy(eigenvalues_instance):
+    k_valence = [0.000, 0.500, 0.500]
+    k_conduction = [0.000, 0.000, 0.000]
+
+    indirect_gap = eigenvalues_instance.get_transition_energy(k_valence, k_conduction)
+    direct_gap_at_Gamma =eigenvalues_instance.get_transition_energy(k_conduction, k_conduction)
+
+    assert np.isclose(indirect_gap, 0.19767), 'Transition energy for X→Γ, in Ha'
+    assert np.isclose(direct_gap_at_Gamma, 0.21854), 'Transition energy for Γ→Γ, in Ha'
+
+    with pytest.raises(ValueError, match="Requested conduction k-point \\[1, 1, 1\\] not present."):
+        eigenvalues_instance.get_transition_energy(k_valence, [1, 1, 1]), \
+        "ValueError is returned if k-point is not matched."
```

#### encoding

```diff
@@ -1 +1 @@
-us-ascii
+utf-8
```

### Comparing `excitingtools-1.2.0/tests/dict_parsers/test_bse_parser.py` & `excitingtools-1.3.0/tests/dict_parsers/test_bse_parser.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/tests/dict_parsers/test_groundstate_parser.py` & `excitingtools-1.3.0/tests/dict_parsers/test_groundstate_parser.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/tests/dict_parsers/test_gw/mock_gw_info_out.py` & `excitingtools-1.3.0/tests/dict_parsers/test_gw/mock_gw_info_out.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/tests/dict_parsers/test_gw/test_gw_dos_parser.py` & `excitingtools-1.3.0/tests/dict_parsers/test_gw/test_gw_dos_parser.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/tests/dict_parsers/test_gw/test_gw_eignvalues_parser.py` & `excitingtools-1.3.0/tests/dict_parsers/test_gw/test_gw_eignvalues_parser.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/tests/dict_parsers/test_gw/test_gw_eps00_parser.py` & `excitingtools-1.3.0/tests/dict_parsers/test_gw/test_gw_eps00_parser.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/tests/dict_parsers/test_gw/test_gw_info_parser.py` & `excitingtools-1.3.0/tests/dict_parsers/test_gw/test_gw_info_parser.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/tests/dict_parsers/test_gw/test_gw_vxc_parser.py` & `excitingtools-1.3.0/tests/dict_parsers/test_gw/test_gw_vxc_parser.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/tests/dict_parsers/test_input_parser.py` & `excitingtools-1.3.0/tests/dict_parsers/test_input_parser.py`

 * *Files 18% similar despite different names*

```diff
@@ -1,37 +1,45 @@
 """
 Test for the input.xml file parser
 """
 import pytest
 
-from excitingtools.exciting_dict_parsers.input_parser import parse_groundstate, parse_structure, parse_xs, \
-    parse_input_xml, parse_title
-
+from excitingtools.exciting_dict_parsers.input_parser import parse_element_xml, parse_structure, parse_input_xml
 
 reference_input_str = """<?xml version="1.0" encoding="UTF-8"?>
-<input>
+<input sharedfs="true" 
+  xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
+  xsi:noNamespaceSchemaLocation="https://xml.exciting-code.org/excitinginput.xsd">
   
   <title>Lithium Fluoride BSE</title>
   
   <structure speciespath="." autormt="false" epslat="1.0d-6">
-    <crystal scale="1.0" stretch="1.0">
+    <crystal scale="1.0" stretch="1.0 1.0 1.0">
       <basevect>3.80402 3.80402 0.00000</basevect>
       <basevect>3.80402 0.00000 3.80402</basevect>
       <basevect>0.00000 3.80402 3.80402</basevect>
     </crystal>
     <species speciesfile="Li.xml" rmt="1.5">
       <atom coord="0.0000  0.0000  0.0000" bfcmt="0.0 0.0 0.0"/>
+      <dfthalfparam 
+        cut="3.90" 
+        ampl="1" 
+        exponent="8">
+        <shell number="0" ionization="0.25" />
+      </dfthalfparam>
     </species>
     <species speciesfile="F.xml">
       <atom coord="0.5000  0.5000  0.5000" lockxyz="false true false"/>
+      <LDAplusU J="2.3" U="0.5" l="3"/>
     </species>
   </structure>
   
   <groundstate xctype="GGA_PBE" ngridk="4 4 4" epsengy="1d-7" outputlevel="high">
    <spin bfieldc="0 0 0" fixspin="total FSM"/>
+   <OEP maxitoep="100"> </OEP>
   </groundstate>
 
   <xs xstype="BSE" 
    ngridq="3 3 3"
    vkloff="0.05 0.15 0.25" 
    nempty="1"
    broad="0.0073499"
@@ -58,120 +66,95 @@
   </xs>
   
 </input>
 """
 
 
 def test_parse_title():
-    assert parse_title(reference_input_str) == "Lithium Fluoride BSE"
+    assert parse_element_xml(reference_input_str, tag="title") == "Lithium Fluoride BSE"
 
 
 def test_parse_groundstate():
-    ground_state = parse_groundstate(reference_input_str)
+    ground_state = parse_element_xml(reference_input_str, tag="groundstate")
     assert ground_state == {
-        'xctype': 'GGA_PBE', 'ngridk': '4 4 4',
-        'epsengy': '1d-7', 'outputlevel': 'high',
-        'spin': {'bfieldc': '0 0 0', 'fixspin': 'total FSM'}
-        }
+        'xctype': 'GGA_PBE', 'ngridk': [4, 4, 4],
+        'epsengy': 1e-7, 'outputlevel': 'high',
+        'spin': {'bfieldc': [0, 0, 0], 'fixspin': 'total FSM'},
+        'OEP': {'maxitoep': 100}
+    }
 
 
 def test_parse_groundstate_from_gs_root():
-    ground_state = parse_groundstate('<groundstate xctype="GGA_PBE" ngridk="4 4 4" epsengy="1d-7" outputlevel="high"/>')
+    ground_state = parse_element_xml('<groundstate xctype="GGA_PBE" ngridk="4 4 4" epsengy="1d-7" outputlevel="high"/>',
+                                     tag="groundstate")
     assert ground_state == {
-        'xctype': 'GGA_PBE', 'ngridk': '4 4 4',
-        'epsengy': '1d-7', 'outputlevel': 'high'
-        }
+        'xctype': 'GGA_PBE', 'ngridk': [4, 4, 4],
+        'epsengy': 1e-7, 'outputlevel': 'high'
+    }
 
 
 def test_parse_structure():
     structure = parse_structure(reference_input_str)
     structure_ref = {
         'atoms': [{'species': 'Li', 'position': [0.0, 0.0, 0.0],
-                   'bfcmt': '0.0 0.0 0.0'},
+                   'bfcmt': [0.0, 0.0, 0.0]},
                   {'species': 'F', 'position': [0.5, 0.5, 0.5],
-                   'lockxyz': 'false true false'}],
+                   'lockxyz': [False, True, False]}],
         'lattice': [[3.80402, 3.80402, 0.0],
                     [3.80402, 0.0, 3.80402],
                     [0.0, 3.80402, 3.80402]],
         'species_path': '.',
-        'crystal_properties': {'scale': '1.0', 'stretch': '1.0'},
-        'species_properties': {'Li': {'rmt': '1.5'}, 'F': {}},
-        'autormt': 'false',
-        'epslat': '1.0d-6',
-        }
+        'crystal_properties': {'scale': 1.0, 'stretch': [1.0, 1.0, 1.0]},
+        'species_properties': {'F': {'LDAplusU': {'J': 2.3, 'U': 0.5, 'l': 3}},
+                               'Li': {'dfthalfparam': {'ampl': 1,
+                                                       'cut': 3.9,
+                                                       'exponent': 8,
+                                                       'shell': {'ionization': 0.25,
+                                                                 'number': 0}},
+                                      'rmt': 1.5}},
+        'autormt': False,
+        'epslat': 1.0e-6,
+    }
     assert structure_ref == structure
 
 
 def test_parse_xs():
-    xs = parse_xs(reference_input_str)
+    xs = parse_element_xml(reference_input_str, tag="xs")
     xs_ref = {
         'xstype': 'BSE',
-        'ngridq': '3 3 3',
-        'vkloff': '0.05 0.15 0.25',
-        'nempty': '1',
-        'broad': '0.0073499',
-        'nosym': 'true',
-        'energywindow': {'intv': '0.0 1.0', 'points': '50'},
-        'screening': {'screentype': 'full', 'nempty': '115'},
-        'BSE': {'bsetype': 'singlet', 'nstlbse': '1 5 1 2', 'aresbse': 'false'},
+        'ngridq': [3, 3, 3],
+        'vkloff': [0.05, 0.15, 0.25],
+        'nempty': 1,
+        'broad': 0.0073499,
+        'nosym': True,
+        'energywindow': {'intv': [0.0, 1.0], 'points': 50},
+        'screening': {'screentype': 'full', 'nempty': 115},
+        'BSE': {'bsetype': 'singlet', 'nstlbse': [1, 5, 1, 2], 'aresbse': False},
         'qpointset': [[0.0, 0.0, 0.0]],
         'plan': ['screen', 'bse']
-        }
+    }
     assert xs_ref == xs
+    assert isinstance(xs["ngridq"][0], int)
 
 
-def test_parse_input_xml():
-    parsed_data = parse_input_xml(reference_input_str)
-    assert set(parsed_data.keys()) == {'title', 'groundstate', 'structure', 'xs'}
+input_ref_parsed_keys = {'title', 'groundstate', 'structure', 'xs', 'sharedfs'}
 
 
-reference_input_str_without_xs = """<?xml version="1.0" encoding="UTF-8"?>
-<input>
-
-  <title>Lithium Fluoride BSE</title>
-
-  <structure speciespath="." autormt="false" epslat="1.0d-6">
-    <crystal scale="1.0" stretch="1.0">
-      <basevect>3.80402 3.80402 0.00000</basevect>
-      <basevect>3.80402 0.00000 3.80402</basevect>
-      <basevect>0.00000 3.80402 3.80402</basevect>
-    </crystal>
-    <species speciesfile="Li.xml" rmt="1.5">
-      <atom coord="0.0000  0.0000  0.0000" bfcmt="0.0 0.0 0.0"/>
-    </species>
-    <species speciesfile="F.xml">
-      <atom coord="0.5000  0.5000  0.5000" lockxyz="false true false"/>
-    </species>
-  </structure>
-
-  <groundstate xctype="GGA_PBE" ngridk="4 4 4" epsengy="1d-7" outputlevel="high"/>
-
-</input>
-"""
-
-
-def test_parse_xs_no_xs():
-    xs = parse_xs(reference_input_str_without_xs)
-    assert xs == {}
+def test_parse_input_xml():
+    parsed_data = parse_element_xml(reference_input_str)
+    assert set(parsed_data.keys()) == input_ref_parsed_keys
+    assert parsed_data['sharedfs']
 
 
-reference_input_str_warning = """<?xml version="1.0" encoding="UTF-8"?>
-<input>
-  <xs xstype="BSE" 
-   ngridq="3 3 3"
-   vkloff="0.05 0.15 0.25" 
-   nempty="1"
-   broad="0.0073499"
-   nosym="true">
+def test_parse_input_xml_directly():
+    parsed_data = parse_input_xml(reference_input_str)
+    assert set(parsed_data.keys()) == input_ref_parsed_keys
 
-   <transitions></transitions>
-  </xs>
 
-</input>
-"""
+def test_parse_missing_tag():
+    with pytest.raises(ValueError, match="Your specified input has no tag missing_tag"):
+        parse_element_xml(reference_input_str, "missing_tag")
 
 
-def test_parse_xs_warning():
-    with pytest.warns(UserWarning, match="Subelements {'transitions'} not yet supported. XS will ignore it."):
-        xs = parse_xs(reference_input_str_warning)
-    assert xs == {"xstype": "BSE", 'ngridq': '3 3 3', 'vkloff': '0.05 0.15 0.25', 'nempty': '1',
-                  'broad': '0.0073499', 'nosym': 'true'}
+def test_parse_input_xml_with_tag():
+    parsed_data = parse_element_xml(reference_input_str, tag="input")
+    assert set(parsed_data.keys()) == input_ref_parsed_keys
```

### Comparing `excitingtools-1.2.0/tests/dict_parsers/test_ks_band_structure.py` & `excitingtools-1.3.0/tests/dict_parsers/test_ks_band_structure.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/tests/dict_parsers/test_properties_parser.py` & `excitingtools-1.3.0/tests/dict_parsers/test_properties_parser.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/tests/dict_parsers/test_species_parser.py` & `excitingtools-1.3.0/tests/dict_parsers/test_species_parser.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/tests/eigenstates/test_eigenstates.py` & `excitingtools-1.3.0/tests/eigenstates/test_eigenstates.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/tests/input/test_base_class.py` & `excitingtools-1.3.0/tests/input/test_base_class.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/tests/input/test_ground_state.py` & `excitingtools-1.3.0/tests/input/test_ground_state.py`

 * *Files 7% similar despite different names*

```diff
@@ -102,15 +102,15 @@
 def test_from_dict():
     ref_rgkmax = 8.5
     ref_dict = {'xml_string': f'<groundstate rgkmax="{ref_rgkmax}"> </groundstate>'}
     gs_input = ExcitingGroundStateInput.from_dict(ref_dict)
 
     assert gs_input.name == 'groundstate'
     # added comment for pylint to disable warning, because of dynamic attributes
-    assert gs_input.rgkmax == str(ref_rgkmax), f'Expect rgkmax to be equal {ref_rgkmax}'  # pylint: disable=no-member
+    assert gs_input.rgkmax == ref_rgkmax, f'Expect rgkmax to be equal {ref_rgkmax}'  # pylint: disable=no-member
 
 
 def test_spin_input():
     spin_attributes = {'bfieldc': [0, 0, 0], 'fixspin': 'total FSM'}
     spin_keys = list(spin_attributes)
     gs_input = ExcitingGroundStateInput(rgkmax=7.0, spin=spin_attributes)
 
@@ -125,23 +125,61 @@
     assert spin_xml.tag == "spin"
     assert spin_xml.keys() == spin_keys, 'Should contain all spin attributes'
     assert spin_xml.get('bfieldc') == '0 0 0'
     assert spin_xml.get('fixspin') == 'total FSM'
 
 
 def test_solver_input():
-    solver_attributes = {'ArpackImproveInverse': True, 'ArpackShift': 2.4}
+    solver_attributes = {'packedmatrixstorage': True, 'type': "Lapack"}
     solver_keys = list(solver_attributes)
     gs_input = ExcitingGroundStateInput(solver=solver_attributes)
 
     gs_xml = gs_input.to_xml()
     assert gs_xml.tag == 'groundstate'
     assert set(gs_xml.keys()) == set()
 
     elements = list(gs_xml)
     assert len(elements) == 1
 
     solver_xml = elements[0]
     assert solver_xml.tag == "solver"
     assert solver_xml.keys() == solver_keys, 'Should contain all spin attributes'
-    assert solver_xml.get('ArpackImproveInverse') == 'true'
-    assert solver_xml.get('ArpackShift') == '2.4'
+    assert solver_xml.get('packedmatrixstorage') == 'true'
+    assert solver_xml.get('type') == 'Lapack'
+
+
+def test_dfthalf_input():
+    dfthalf_attributes = {"printVSfile": True}
+    dfthalf_keys = list(dfthalf_attributes)
+    gs_input = ExcitingGroundStateInput(dfthalf=dfthalf_attributes)
+
+    gs_xml = gs_input.to_xml()
+    assert gs_xml.tag == 'groundstate'
+    assert set(gs_xml.keys()) == set()
+
+    elements = list(gs_xml)
+    assert len(elements) == 1
+
+    dfthalf_xml = elements[0]
+    assert dfthalf_xml.tag == "dfthalf"
+    assert dfthalf_xml.keys() == dfthalf_keys, 'Should contain all dfthalf attributes'
+    assert dfthalf_xml.get('printVSfile') == 'true'
+
+
+def test_OEP_input():
+    oep_attributes = {"convoep": 1e-5, "maxitoep": 200, "tauoep": [1, 2, 3]}
+    oep_keys = list(oep_attributes)
+    gs_input = ExcitingGroundStateInput(OEP=oep_attributes)
+
+    gs_xml = gs_input.to_xml()
+    assert gs_xml.tag == 'groundstate'
+    assert set(gs_xml.keys()) == set()
+
+    elements = list(gs_xml)
+    assert len(elements) == 1
+
+    oep_xml = elements[0]
+    assert oep_xml.tag == "OEP"
+    assert oep_xml.keys() == oep_keys, 'Should contain all dfthalf attributes'
+    assert oep_xml.get('convoep') == '1e-05'
+    assert oep_xml.get('maxitoep') == '200'
+    assert oep_xml.get('tauoep') == '1 2 3'
```

### Comparing `excitingtools-1.2.0/tests/input/test_input_xml.py` & `excitingtools-1.3.0/tests/input/test_input_xml.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,34 +1,36 @@
 """Test composition of an exciting input XML.
 
 TODO(Fab/Alex/Dan) Issue 117. Would be nice to assert that the output is valid
     XML * https://lxml.de/validation.html
 Also see: https://xmlschema.readthedocs.io/en/latest/usage.html#xsd-declarations
 """
-import re
 
 import pytest
 
+from excitingtools.input.ground_state import ExcitingGroundStateInput
 from excitingtools.input.input_xml import ExcitingInputXML
 from excitingtools.input.structure import ExcitingStructure
-from excitingtools.input.ground_state import ExcitingGroundStateInput
 from excitingtools.input.xs import ExcitingXSInput
 
 
 @pytest.fixture
-def exciting_input_xml() -> ExcitingInputXML:
-    """ Initialises a complete input file. """
-    # Structure
+def exciting_structure() -> ExcitingStructure:
+    """ Initialise an exciting structure. """
     cubic_lattice = [[1.0, 0.0, 0.0], [0.0, 1.0, 0.0], [0.0, 0.0, 1.0]]
     arbitrary_atoms = [{'species': 'Li', 'position': [0.0, 0.0, 0.0]},
                        {'species': 'Li', 'position': [1.0, 0.0, 0.0]},
                        {'species': 'F', 'position': [2.0, 0.0, 0.0]}]
 
-    structure = ExcitingStructure(arbitrary_atoms, cubic_lattice, '.')
+    return ExcitingStructure(arbitrary_atoms, cubic_lattice, '.')
 
+
+@pytest.fixture
+def exciting_input_xml(exciting_structure: ExcitingStructure) -> ExcitingInputXML:
+    """ Initialises a complete input file. """
     ground_state = ExcitingGroundStateInput(
         rgkmax=8.0,
         do="fromscratch",
         ngridk=[6, 6, 6],
         xctype="GGA_PBE_SOL",
         vkloff=[0, 0, 0],
         tforce=True,
@@ -43,25 +45,26 @@
     xs = ExcitingXSInput(xstype="BSE", broad=0.32, ngridk=[8, 8, 8],
                          BSE=bse_attributes,
                          energywindow=energywindow_attributes,
                          screening=screening_attributes,
                          qpointset=qpointset_input,
                          plan=plan_input)
 
-    return ExcitingInputXML(structure, title='Test Case', groundstate=ground_state, xs=xs)
+    return ExcitingInputXML(sharedfs=True, structure=exciting_structure, title='Test Case', groundstate=ground_state,
+                            xs=xs)
 
 
 def test_exciting_input_xml_structure_and_gs_and_xs(exciting_input_xml: ExcitingInputXML):
     """Test the XML created for a ground state input is valid.
     Test SubTree composition using only mandatory attributes for each XML subtree.
     """
     input_xml_tree = exciting_input_xml.to_xml()
 
     assert input_xml_tree.tag == 'input'
-    assert input_xml_tree.keys() == []
+    assert input_xml_tree.keys() == ['sharedfs']
 
     subelements = list(input_xml_tree)
     assert len(subelements) == 4
 
     title_xml = subelements[0]
     assert title_xml.tag == 'title'
     assert title_xml.keys() == []
@@ -138,18 +141,18 @@
     assert doonlys[1].items() == [('task', 'bse')]
 
 
 def test_attribute_modification(exciting_input_xml: ExcitingInputXML):
     """Test the XML created for a ground state input is valid.
     Test SubTree composition using only mandatory attributes for each XML subtree.
     """
-    exciting_input_xml.title = "New Test Case"
+    exciting_input_xml.set_title("New Test Case")
     exciting_input_xml.structure.crystal_properties.scale = 2.3
     exciting_input_xml.groundstate.rgkmax = 9.0
-    exciting_input_xml.__dict__['xs'].energywindow.points = 4000
+    exciting_input_xml.xs.energywindow.points = 4000
     input_xml_tree = exciting_input_xml.to_xml()
 
     subelements = list(input_xml_tree)
     assert len(subelements) == 4
 
     title_xml = subelements[0]
     assert title_xml.tag == 'title'
@@ -167,36 +170,45 @@
 
     energywindow_xml = xs_xml.find("energywindow")
     assert energywindow_xml.get('points') == '4000'
 
 
 def test_as_dict(exciting_input_xml: ExcitingInputXML, mock_env_jobflow_missing):
     dict_representation = exciting_input_xml.as_dict()
-    assert len(dict_representation) == 4, "expect 4 different keys"
-    assert dict_representation['title'] == "Test Case"
-    # check only that the xml string starts with the correct tag:
-    assert re.match(r'<structure', dict_representation['structure']['xml_string'], flags=re.MULTILINE)
-    assert re.match(r'<groundstate', dict_representation['groundstate']['xml_string'], flags=re.MULTILINE)
-    assert re.match(r'<xs', dict_representation['xs']['xml_string'], flags=re.MULTILINE)
+    assert set(dict_representation.keys()) == {"xml_string"}
+    # check only that the xml string starts with the correct first lines:
+    assert dict_representation["xml_string"].startswith('<?xml version="1.0" ?>\n<input sharedfs="true">\n\t \n\t'
+                                                        '<title>Test Case</title>\n\t<structure')
 
 
 def test_as_dict_jobflow(exciting_input_xml: ExcitingInputXML, mock_env_jobflow):
-    ref_dict = {'@class': 'ExcitingInputXML',
-                '@module': 'excitingtools.input.input_xml',
-                'title': "Test Case"}
     dict_representation = exciting_input_xml.as_dict()
-    # assert only the correct keys, rest is tested in corresponding test files
-    assert set(dict_representation.pop('structure').keys()) == {'@class', '@module', 'xml_string'}
-    assert set(dict_representation.pop('groundstate').keys()) == {'@class', '@module', 'xml_string'}
-    assert set(dict_representation.pop('xs').keys()) == {'@class', '@module', 'xml_string'}
-    assert dict_representation == ref_dict
+    xml_string = dict_representation.pop("xml_string")
+    assert dict_representation == {'@class': 'ExcitingInputXML',
+                                   '@module': 'excitingtools.input.input_xml'}
+    # check only that the xml string starts with the correct first lines:
+    assert xml_string.startswith('<?xml version="1.0" ?>\n<input sharedfs="true">\n\t \n\t'
+                                 '<title>Test Case</title>\n\t<structure')
 
 
 def test_from_dict(exciting_input_xml: ExcitingInputXML, mock_env_jobflow_missing):
     new_input_xml = ExcitingInputXML.from_dict(exciting_input_xml.as_dict())
-    assert new_input_xml.title == "Test Case"
-    assert new_input_xml.groundstate.ngridk == '6 6 6'
+    assert new_input_xml.title.title == "Test Case"  # pylint: disable=no-member
+    assert new_input_xml.groundstate.ngridk == [6, 6, 6]  # pylint: disable=no-member
 
 
 def test_from_dict_jobflow(exciting_input_xml: ExcitingInputXML, mock_env_jobflow):
     new_input_xml = ExcitingInputXML.from_dict(exciting_input_xml.as_dict())
-    assert new_input_xml.title == "Test Case"
+    assert new_input_xml.title.title == "Test Case"  # pylint: disable=no-member
+
+
+def test_missing_structure():
+    with pytest.raises(ValueError, match="Missing mandatory arguments: {'structure'}"):
+        ExcitingInputXML(title="Test Case", groundstate=ExcitingGroundStateInput())
+
+
+def test_from_gs_dict(exciting_structure):
+    input_xml = ExcitingInputXML(structure=exciting_structure, title="Test Case",
+                                 groundstate={"rgkmax": 7.0})
+    assert input_xml.title.title == "Test Case"  # pylint: disable=no-member
+    assert input_xml.groundstate.rgkmax == 7.0  # pylint: disable=no-member
+    assert input_xml.structure.speciespath == "."  # pylint: disable=no-member
```

### Comparing `excitingtools-1.2.0/tests/input/test_structure.py` & `excitingtools-1.3.0/tests/input/test_structure.py`

 * *Files 16% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 """Test ExcitingStructure, python API that generates exciting's structure XML.
 
 NOTE:
-All attribute tests should assert on the XML tree content,s as the attribute
+All attribute tests should assert on the XML tree content, as the attribute
 order is not preserved by the ElementTree.tostring method. Elements appear to
 be fine.
 
 For example:
 
  `gs_xml_string = xml.etree.ElementTree.tostring(
      gs_xml, encoding='unicode', method='xml')`
@@ -14,16 +14,17 @@
 
 '<groundstate ngridk="8 8 8" rgkmax="8.6"> </groundstate>'
 or
 '<groundstate rgkmax="8.6" ngridk="8 8 8"> </groundstate>'
 
 """
 import sys
-import pytest
+
 import numpy as np
+import pytest
 
 try:
     import ase
 except ImportError:
     pass
 
 from excitingtools.input.structure import ExcitingStructure
@@ -44,15 +45,15 @@
 
 def test_class_exciting_structure_xml(xml_structure_H2He):
     """
     Test input XML attributes from an instance of ExcitingStructure.
     """
     assert xml_structure_H2He.tag == 'structure', 'XML root should be structure'
     assert xml_structure_H2He.keys() == ['speciespath'], 'structure defined to have only speciespath '
-    assert xml_structure_H2He.get('speciespath') == '.', 'species path set to .'
+    assert xml_structure_H2He.get('speciespath') == './', 'species path set to ./'
 
 
 def test_class_exciting_structure_crystal_xml(xml_structure_H2He):
     """
     crystal subtree of structure.
     """
     elements = list(xml_structure_H2He)
@@ -116,15 +117,15 @@
 
 def test_optional_atom_attributes_xml(xml_structure_CdS):
     """
     Test optional atom attributes are correctly set in XML tree.
     """
     assert xml_structure_CdS.tag == 'structure'
     assert xml_structure_CdS.keys() == ['speciespath'], 'structure defined to have only speciespath '
-    assert xml_structure_CdS.get('speciespath') == '.', 'speciespath set to be .'
+    assert xml_structure_CdS.get('speciespath') == './', 'speciespath set to be ./'
 
     elements = list(xml_structure_CdS)
     assert len(elements) == 3, 'Expect structure tree to have 3 sub-elements'
 
     # Crystal
     crystal_xml = elements[0]
     assert crystal_xml.tag == "crystal", 'First subtree is crystal'
@@ -181,15 +182,15 @@
 
     mandatory = {'speciespath'}
     optional = set(structure_attributes)
 
     assert xml_structure.tag == 'structure'
     assert set(xml_structure.keys()) == mandatory | optional, \
         'Should contain mandatory speciespath plus all optional attributes'
-    assert xml_structure.get('speciespath') == '.', 'species path should be .'
+    assert xml_structure.get('speciespath') == './', 'species path should be ./'
     assert xml_structure.get('autormt') == 'true'
     assert xml_structure.get('cartesian') == 'false'
     assert xml_structure.get('epslat') == '1e-06'
     assert xml_structure.get('primcell') == 'false'
     assert xml_structure.get('tshift') == 'true'
 
 
@@ -199,34 +200,36 @@
     """
     cubic_lattice, arbitrary_atoms = lattice_and_atoms_CdS
 
     structure = ExcitingStructure(
         arbitrary_atoms,
         cubic_lattice,
         './',
-        crystal_properties={'scale': 1.00, 'stretch': 1.00}
+        crystal_properties={'scale': 1.00, 'stretch': [1.00, 1.00, 1.00]}
     )
     xml_structure = structure.to_xml()
 
     elements = list(xml_structure)
     assert len(elements) == 3, 'Number of sub-elements in structure tree'
 
     crystal_xml = elements[0]
     assert crystal_xml.tag == "crystal", 'First subtree is crystal'
     assert crystal_xml.keys() == ['scale', 'stretch'], 'Optional crystal properties'
     assert crystal_xml.get('scale') == '1.0', 'scale value inconsistent with input'
-    assert crystal_xml.get('stretch') == '1.0', 'stretch value inconsistent with input'
+    assert crystal_xml.get('stretch') == '1.0 1.0 1.0', 'stretch value inconsistent with input'
 
 
 def test_optional_species_attributes_xml(lattice_and_atoms_CdS):
     """
     Test optional species attributes.
     """
     cubic_lattice, arbitrary_atoms = lattice_and_atoms_CdS
-    species_attributes = {'Cd': {'rmt': 3.0}, 'S': {'rmt': 4.0}}
+    species_attributes = {'Cd': {'rmt': 3.0, "LDAplusU": {"J": 1.5, "U": 2.4, "l": 2}},
+                          'S': {'rmt': 4.0, "dfthalfparam": {"ampl": 1.2, "cut": 1.9, "exponent": 5,
+                                                             "shell": {"ionization": 0.8, "number": 1}}}}
 
     structure = ExcitingStructure(
         arbitrary_atoms, cubic_lattice, './', species_properties=species_attributes
     )
     xml_structure = structure.to_xml()
 
     elements = list(xml_structure)
@@ -238,20 +241,49 @@
     species_s_xml = elements[2]
     assert species_s_xml.tag == "species", 'Third subtree is species'
 
     assert set(species_cd_xml.keys()) == {'speciesfile', 'rmt'}, "species attributes differ from expected"
     assert species_cd_xml.get('speciesfile') == 'Cd.xml', 'speciesfile differs from expected'
     assert species_cd_xml.get('rmt') == '3.0', 'Cd muffin tin radius differs from input'
 
+    species_cd_elements = list(species_cd_xml)
+    assert len(species_cd_elements) == 2
+    ldaplusu_xml = species_cd_elements[0]
+    assert ldaplusu_xml.tag == "LDAplusU"
+
+    assert set(ldaplusu_xml.keys()) == {'J', 'U', 'l'}
+    assert ldaplusu_xml.get("J") == "1.5"
+    assert ldaplusu_xml.get("U") == "2.4"
+    assert ldaplusu_xml.get("l") == "2"
+
     assert set(species_s_xml.keys()) == {'speciesfile', 'rmt'}, "species attributes differ from expected"
     assert species_s_xml.get('speciesfile') == 'S.xml', 'speciesfile differs from expected'
     assert species_s_xml.get('rmt') == '4.0', 'S muffin tin radius differs from input'
 
+    species_s_elements = list(species_s_xml)
+    assert len(species_s_elements) == 2
+    dfthalfparam_xml = species_s_elements[0]
+    assert dfthalfparam_xml.tag == "dfthalfparam"
+
+    assert set(dfthalfparam_xml.keys()) == {'ampl', 'cut', 'exponent'}
+    assert dfthalfparam_xml.get("ampl") == "1.2"
+    assert dfthalfparam_xml.get("cut") == "1.9"
+    assert dfthalfparam_xml.get("exponent") == "5"
+
+    dfthalfparam_elements = list(dfthalfparam_xml)
+    assert len(dfthalfparam_elements) == 1
+    shell_xml = dfthalfparam_elements[0]
+    assert shell_xml.tag == "shell"
+
+    assert set(shell_xml.keys()) == {'ionization', 'number'}
+    assert shell_xml.get('ionization') == '0.8'
+    assert shell_xml.get('number') == '1'
+
 
-ref_dict = {'xml_string': '<structure speciespath="."> <crystal> <basevect>1.0 0.0 0.0</basevect>'
+ref_dict = {'xml_string': '<structure speciespath="./"> <crystal> <basevect>1.0 0.0 0.0</basevect>'
                           '<basevect>0.0 1.0 0.0</basevect><basevect>0.0 0.0 1.0</basevect></crystal>'
                           '<species speciesfile="Cd.xml"> <atom coord="0.0 0.0 0.0"> </atom></species>'
                           '<species speciesfile="S.xml"> <atom coord="1.0 0.0 0.0"> </atom></species></structure>'}
 
 
 def test_as_dict(lattice_and_atoms_CdS, mock_env_jobflow_missing):
     cubic_lattice, arbitrary_atoms = lattice_and_atoms_CdS
@@ -274,15 +306,15 @@
 def test_from_dict(lattice_and_atoms_CdS):
     cubic_lattice, arbitrary_atoms = lattice_and_atoms_CdS
     structure = ExcitingStructure.from_dict(ref_dict)
 
     assert structure.lattice == cubic_lattice
     assert structure.species == [d['species'] for d in arbitrary_atoms]
     assert structure.positions == [d['position'] for d in arbitrary_atoms]
-    assert structure.species_path.as_posix() == '.'
+    assert structure.speciespath == './'  # pylint: disable=no-member
 
 
 @pytest.fixture
 def lattice_and_atoms_H20():
     """
     H20 molecule in a big box (angstrom)
     """
@@ -297,15 +329,15 @@
     """
     Test group_atoms_by_species method.
     """
     cubic_lattice, atoms = lattice_and_atoms_H20
     structure = ExcitingStructure(atoms, cubic_lattice, './')
     assert structure.species == ['H', 'O', 'H'], 'Species list differs from lattice_and_atoms_H20'
 
-    indices = structure._group_atoms_by_species()
+    indices = dict(structure._group_atoms_by_species())
     assert set(indices.keys()) == {'H', 'O'}, 'List unique species in structure'
     assert indices['H'] == [0, 2], "Expect atoms 0 and 2 to be H"
     assert indices['O'] == [1], "Expect atom 1 to be O"
 
     hydrogen = [structure.species[i] for i in indices['H']]
     oxygen = [structure.species[i] for i in indices['O']]
     assert hydrogen == ["H", "H"], "Expect list to only contain H symbols"
@@ -340,20 +372,36 @@
     structure = ExcitingStructure(atoms, species_path='./')
 
     assert structure.species == ["H", "O", "H"]
     assert np.allclose(structure.lattice,
                        [[10.0, 0.0, 0.0], [0.0, 10.0, 0.0], [0.0, 0.0, 10.0]]), \
         'Expect lattice vectors to match input values'
 
-    assert np.allclose(structure.positions, atoms.positions), 'Expect positions to match input values.'
+    assert np.allclose(structure.positions, atoms.get_scaled_positions()), 'Expect positions to match input values.'
 
     # TODO(Alex) Issue 117. Compare xml_structure built with and without ASE - should be consistent
     # This just confirms the XML tree is built, not that it is correct.
     xml_structure = structure.to_xml()
     assert list(xml_structure.keys()) == ['speciespath'], 'Only expect speciespath in structure xml keys'
 
 
-def test_species_not_existing():
+def test_using_non_standard_species_symbol():
     cubic_lattice = [[10.0, 0.0, 0.0], [0.0, 10.0, 0.0], [0.0, 0.0, 10.0]]
-    atoms = [{'species': 'A', 'position': [0.00000, 0.75545, -0.47116]}]
-    with pytest.raises(ValueError, match="Species input keys are not valid: {'A'}"):
-        ExcitingStructure(atoms, cubic_lattice)
+    atoms = [{'species': 'C_molecule', 'position': [0.00000, 0.75545, -0.47116]}]
+    structure = ExcitingStructure(atoms, cubic_lattice)
+
+    structure_xml = structure.to_xml()
+    assert structure_xml.tag == 'structure', 'XML root should be structure'
+    assert structure_xml.keys() == ['speciespath'], 'structure defined to have only speciespath '
+    assert structure_xml.get('speciespath') == './', 'species path set to ./'
+
+    elements = list(structure_xml)
+    assert len(elements) == 2, 'Expect structure tree to have 2 sub-elements'
+
+    species_c_xml = elements[1]
+    assert species_c_xml.tag == "species", 'Second subtree is species'
+
+    assert species_c_xml.items() == [('speciesfile', 'C_molecule.xml')], 'species is inconsistent'
+
+    atoms_h = list(species_c_xml)
+    assert len(atoms_h) == 1
+    assert atoms_h[0].items() == [('coord', '0.0 0.75545 -0.47116')]
```

### Comparing `excitingtools-1.2.0/tests/input/test_xml_utils.py` & `excitingtools-1.3.0/tests/input/test_xml_utils.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/tests/input/test_xs.py` & `excitingtools-1.3.0/tests/input/test_xs.py`

 * *Files 5% similar despite different names*

```diff
@@ -11,15 +11,15 @@
 
     xs_xml = xs_input.to_xml()
     assert xs_xml.tag == 'xs'
     assert xs_xml.items() == [('xstype', 'BSE')]
 
 
 def test_class_ExcitingXSInput_xstype_missing():
-    with pytest.raises(AssertionError, match="It's necessary to specify the xstype."):
+    with pytest.raises(ValueError, match="Missing mandatory arguments: {'xstype'}"):
         ExcitingXSInput(ngridk=[4, 4, 4])
 
 
 def test_ExcitingXSInput_as_dict(mock_env_jobflow_missing):
     xs_input = ExcitingXSInput(xstype="BSE")
     ref_dict = {'xml_string': '<xs xstype="BSE"> </xs>'}
     assert xs_input.as_dict() == ref_dict, 'expected different dict representation'
```

### Comparing `excitingtools-1.2.0/tests/obj_parsers/test_eigenvalue_parser.py` & `excitingtools-1.3.0/tests/obj_parsers/test_eigenvalue_parser.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/tests/obj_parsers/test_gw_dos.py` & `excitingtools-1.3.0/tests/obj_parsers/test_gw_dos.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/tests/obj_parsers/test_gw_eigenvalues.py` & `excitingtools-1.3.0/tests/obj_parsers/test_gw_eigenvalues.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/tests/obj_parsers/test_input_parser.py` & `excitingtools-1.3.0/tests/obj_parsers/test_input_parser.py`

 * *Files 26% similar despite different names*

```diff
@@ -1,13 +1,12 @@
 """
 Test for the input.xml file parser
 """
-import pytest
 
-from excitingtools.exciting_obj_parsers.input_xml import parse_groundstate, parse_structure, parse_xs
+from excitingtools.exciting_obj_parsers.input_xml import parse_input_xml
 
 reference_input_str = """<?xml version="1.0" encoding="UTF-8"?>
 <input>
   
   <title>Lithium Fluoride BSE</title>
   
   <structure speciespath="." autormt="false" epslat="1.0d-6">
@@ -53,78 +52,11 @@
    </plan>
   </xs>
   
 </input>
 """
 
 
-def test_parse_groundstate_to_object():
-    # just calls the function to see whether the initialization of object returns without errors
-    ground_state = parse_groundstate(reference_input_str)
-    assert ground_state.to_xml().tag == 'groundstate'
-
-
-def test_parse_structure_to_object():
-    # just calls the function to see whether the initialization of object returns without errors
-    structure = parse_structure(reference_input_str)
-    structure_xml = structure.to_xml()
-    assert structure_xml.tag == 'structure'
-
-
-def test_parse_xs_to_object():
-    # just calls the function to see whether the initialization of object returns without errors
-    xs = parse_xs(reference_input_str)
-    xs_xml = xs.to_xml()
-    assert xs_xml.tag == 'xs'
-
-
-reference_input_str_without_xs = """<?xml version="1.0" encoding="UTF-8"?>
-<input>
-
-  <title>Lithium Fluoride BSE</title>
-
-  <structure speciespath="." autormt="false" epslat="1.0d-6">
-    <crystal scale="1.0" stretch="1.0">
-      <basevect>3.80402 3.80402 0.00000</basevect>
-      <basevect>3.80402 0.00000 3.80402</basevect>
-      <basevect>0.00000 3.80402 3.80402</basevect>
-    </crystal>
-    <species speciesfile="Li.xml" rmt="1.5">
-      <atom coord="0.0000  0.0000  0.0000" bfcmt="0.0 0.0 0.0"/>
-    </species>
-    <species speciesfile="F.xml">
-      <atom coord="0.5000  0.5000  0.5000" lockxyz="false true false"/>
-    </species>
-  </structure>
-
-  <groundstate xctype="GGA_PBE" ngridk="4 4 4" epsengy="1d-7" outputlevel="high"/>
-
-</input>
-"""
-
-
-def test_parse_xs_to_object_no_xs():
-    xs = parse_xs(reference_input_str_without_xs)
-    assert xs is None
-
-
-reference_input_str_warning = """<?xml version="1.0" encoding="UTF-8"?>
-<input>
-  <xs xstype="BSE" 
-   ngridq="3 3 3"
-   vkloff="0.05 0.15 0.25" 
-   nempty="1"
-   broad="0.0073499"
-   nosym="true">
-
-   <transitions></transitions>
-  </xs>
-
-</input>
-"""
-
-
-def test_parse_xs_to_object_warning():
-    with pytest.warns(UserWarning, match="Subelements {'transitions'} not yet supported. XS will ignore it."):
-        xs = parse_xs(reference_input_str_warning)
-    xs_xml = xs.to_xml()
-    assert xs_xml.tag == 'xs'
+def test_parse_input_xml_to_object():
+    input_xml = parse_input_xml(reference_input_str)
+    assert set(vars(input_xml)) == {'xs', 'groundstate', 'structure', 'title'}
+    assert input_xml.to_xml_str().startswith('<?xml version="1.0" ?>\n<input>\n\t \n\t<title>Lithium Fluoride BSE')
```

### Comparing `excitingtools-1.2.0/tests/parser_utils/test_regex_parser.py` & `excitingtools-1.3.0/tests/parser_utils/test_regex_parser.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/tests/parser_utils/test_simple_parser.py` & `excitingtools-1.3.0/tests/parser_utils/test_simple_parser.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/tests/runner/test_runner.py` & `excitingtools-1.3.0/tests/runner/test_runner.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/tests/structure/test_lattice.py` & `excitingtools-1.3.0/tests/structure/test_lattice.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/tests/utils/test_dict_utils.py` & `excitingtools-1.3.0/tests/utils/test_dict_utils.py`

 * *Files identical despite different names*

### Comparing `excitingtools-1.2.0/tests/utils/test_utils.py` & `excitingtools-1.3.0/tests/utils/test_utils.py`

 * *Files identical despite different names*


# Comparing `tmp/fmat-0.1.0.tar.gz` & `tmp/fmat-0.1.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "fmat-0.1.0.tar", last modified: Mon Jun 26 18:06:47 2023, max compression
+gzip compressed data, was "fmat-0.1.3.tar", last modified: Wed Jun 28 13:26:36 2023, max compression
```

## Comparing `fmat-0.1.0.tar` & `fmat-0.1.3.tar`

### file list

```diff
@@ -1,85 +1,66 @@
-drwxr-xr-x   0 sunhui     (501) staff       (20)        0 2023-06-26 18:06:47.100684 fmat-0.1.0/
--rw-r--r--   0 sunhui     (501) staff       (20)    35149 2023-06-23 02:15:48.000000 fmat-0.1.0/LICENSE
--rw-r--r--   0 sunhui     (501) staff       (20)       68 2023-06-26 14:59:56.000000 fmat-0.1.0/MANIFEST.in
--rw-r--r--   0 sunhui     (501) staff       (20)      774 2023-06-26 18:06:47.100317 fmat-0.1.0/PKG-INFO
--rw-r--r--   0 sunhui     (501) staff       (20)     4399 2023-06-26 18:02:52.000000 fmat-0.1.0/README.rst
-drwxr-xr-x   0 sunhui     (501) staff       (20)        0 2023-06-26 18:06:47.074236 fmat-0.1.0/fmat/
-drwxr-xr-x   0 sunhui     (501) staff       (20)        0 2023-06-26 18:06:47.078195 fmat-0.1.0/fmat/__pycache__/
--rw-r--r--   0 sunhui     (501) staff       (20)      156 2023-06-19 20:05:36.000000 fmat-0.1.0/fmat/__pycache__/__init__.cpython-39.pyc
--rw-r--r--   0 sunhui     (501) staff       (20)     3299 2023-06-20 20:41:42.000000 fmat-0.1.0/fmat/__pycache__/ref_data.cpython-39.pyc
-drwxr-xr-x   0 sunhui     (501) staff       (20)        0 2023-06-26 18:06:47.082378 fmat-0.1.0/fmat/core/
--rw-rw-r--   0 sunhui     (501) staff       (20)     9842 2023-06-26 13:02:55.000000 fmat-0.1.0/fmat/core/GenerateEqScript.py
--rw-r--r--   0 sunhui     (501) staff       (20)    11710 2023-06-26 14:59:29.000000 fmat-0.1.0/fmat/core/GenerateScheilScript.py
--rw-rw-r--   0 sunhui     (501) staff       (20)     5719 2023-06-26 14:59:24.000000 fmat-0.1.0/fmat/core/ReadEqResult.py
--rw-rw-r--   0 sunhui     (501) staff       (20)    12898 2023-06-26 14:59:20.000000 fmat-0.1.0/fmat/core/ReadScheilResult.py
--rw-r--r--   0 sunhui     (501) staff       (20)        0 2023-06-19 20:33:09.000000 fmat-0.1.0/fmat/core/__init__.py
--rw-r--r--   0 sunhui     (501) staff       (20)      157 2023-06-20 18:46:55.000000 fmat-0.1.0/fmat/core/__init__.pyc
-drwxr-xr-x   0 sunhui     (501) staff       (20)        0 2023-06-26 18:06:47.085181 fmat-0.1.0/fmat/core/__pycache__/
--rw-r--r--   0 sunhui     (501) staff       (20)     6589 2023-06-26 15:01:32.000000 fmat-0.1.0/fmat/core/__pycache__/GenerateEqScript.cpython-39.pyc
--rw-r--r--   0 sunhui     (501) staff       (20)     6531 2023-06-26 15:01:32.000000 fmat-0.1.0/fmat/core/__pycache__/GenerateScheilScript.cpython-39.pyc
--rw-r--r--   0 sunhui     (501) staff       (20)     4102 2023-06-26 15:01:32.000000 fmat-0.1.0/fmat/core/__pycache__/ReadEqResult.cpython-39.pyc
--rw-r--r--   0 sunhui     (501) staff       (20)     8595 2023-06-26 15:01:32.000000 fmat-0.1.0/fmat/core/__pycache__/ReadScheilResult.cpython-39.pyc
--rw-r--r--   0 sunhui     (501) staff       (20)      161 2023-06-20 12:57:47.000000 fmat-0.1.0/fmat/core/__pycache__/__init__.cpython-39.pyc
--rw-r--r--   0 sunhui     (501) staff       (20)     3865 2023-06-26 15:01:28.000000 fmat-0.1.0/fmat/core/__pycache__/compositions.cpython-39.pyc
--rw-r--r--   0 sunhui     (501) staff       (20)     6419 2023-06-26 15:01:29.000000 fmat-0.1.0/fmat/core/__pycache__/pycalphad_run.cpython-39.pyc
--rw-r--r--   0 sunhui     (501) staff       (20)     4439 2023-06-26 14:59:32.000000 fmat-0.1.0/fmat/core/compositions.py
--rw-r--r--   0 sunhui     (501) staff       (20)     8270 2023-06-26 14:59:27.000000 fmat-0.1.0/fmat/core/pycalphad_run.py
-drwxr-xr-x   0 sunhui     (501) staff       (20)        0 2023-06-26 18:06:47.086206 fmat-0.1.0/fmat/plot/
--rw-rw-r--   0 sunhui     (501) staff       (20)    34457 2023-06-26 14:59:18.000000 fmat-0.1.0/fmat/plot/FeasibilityMap.py
--rw-r--r--   0 sunhui     (501) staff       (20)        0 2023-06-19 20:33:17.000000 fmat-0.1.0/fmat/plot/__init__.py
-drwxr-xr-x   0 sunhui     (501) staff       (20)        0 2023-06-26 18:06:47.087212 fmat-0.1.0/fmat/plot/__pycache__/
--rw-r--r--   0 sunhui     (501) staff       (20)    23605 2023-06-26 15:01:32.000000 fmat-0.1.0/fmat/plot/__pycache__/FeasibilityMap.cpython-39.pyc
--rw-r--r--   0 sunhui     (501) staff       (20)      161 2023-06-20 12:57:49.000000 fmat-0.1.0/fmat/plot/__pycache__/__init__.cpython-39.pyc
--rw-r--r--   0 sunhui     (501) staff       (20)     3294 2023-06-19 20:05:50.000000 fmat-0.1.0/fmat/plot/__pycache__/feasibility_helpers.cpython-39.pyc
--rw-rw-r--   0 sunhui     (501) staff       (20)     4368 2023-06-14 20:17:00.000000 fmat-0.1.0/fmat/plot/feasibility_helpers.py
--rw-r--r--   0 sunhui     (501) staff       (20)     4750 2023-06-20 20:40:05.000000 fmat-0.1.0/fmat/ref_data.py
-drwxr-xr-x   0 sunhui     (501) staff       (20)        0 2023-06-26 18:06:47.088780 fmat-0.1.0/fmat/tests/
--rw-r--r--   0 sunhui     (501) staff       (20)        0 2023-06-21 20:12:11.000000 fmat-0.1.0/fmat/tests/__init__.py
-drwxr-xr-x   0 sunhui     (501) staff       (20)        0 2023-06-26 18:06:47.091116 fmat-0.1.0/fmat/tests/__pycache__/
--rw-r--r--   0 sunhui     (501) staff       (20)      162 2023-06-21 20:12:13.000000 fmat-0.1.0/fmat/tests/__pycache__/__init__.cpython-39.pyc
--rw-r--r--   0 sunhui     (501) staff       (20)     1799 2023-06-26 15:01:28.000000 fmat-0.1.0/fmat/tests/__pycache__/test_compositions.cpython-39-pytest-7.3.2.pyc
--rw-r--r--   0 sunhui     (501) staff       (20)     7409 2023-06-26 15:01:29.000000 fmat-0.1.0/fmat/tests/__pycache__/test_plotting.cpython-39-pytest-7.3.2.pyc
--rw-r--r--   0 sunhui     (501) staff       (20)     2706 2023-06-26 15:04:23.000000 fmat-0.1.0/fmat/tests/__pycache__/test_pycalphad_run.cpython-39-pytest-7.3.2.pyc
--rw-r--r--   0 sunhui     (501) staff       (20)     4170 2023-06-26 15:01:32.000000 fmat-0.1.0/fmat/tests/__pycache__/test_thermo_calc_script.cpython-39-pytest-7.3.2.pyc
--rw-r--r--   0 sunhui     (501) staff       (20)     1279 2023-06-26 14:59:16.000000 fmat-0.1.0/fmat/tests/test_compositions.py
--rw-r--r--   0 sunhui     (501) staff       (20)    13284 2023-06-26 14:59:12.000000 fmat-0.1.0/fmat/tests/test_plotting.py
--rw-r--r--   0 sunhui     (501) staff       (20)     1815 2023-06-26 15:04:06.000000 fmat-0.1.0/fmat/tests/test_pycalphad_run.py
--rw-r--r--   0 sunhui     (501) staff       (20)     3513 2023-06-26 14:59:00.000000 fmat-0.1.0/fmat/tests/test_thermo_calc_script.py
-drwxr-xr-x   0 sunhui     (501) staff       (20)        0 2023-06-26 18:06:47.092233 fmat-0.1.0/fmat/tests/testsCaseFiles/
--rw-r--r--   0 sunhui     (501) staff       (20)    16269 2023-03-30 16:57:48.000000 fmat-0.1.0/fmat/tests/testsCaseFiles/Ag-Al-Cu.TDB
-drwxr-xr-x   0 sunhui     (501) staff       (20)        0 2023-06-26 18:06:47.071311 fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/
-drwxr-xr-x   0 sunhui     (501) staff       (20)        0 2023-06-26 18:06:47.094422 fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Equilibrium Simulation/
--rw-r--r--   0 sunhui     (501) staff       (20)     6680 2023-06-19 20:21:14.000000 fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Equilibrium Simulation/0_mole.exp
--rw-r--r--   0 sunhui     (501) staff       (20)     6684 2023-06-19 20:21:14.000000 fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Equilibrium Simulation/0_wt.exp
--rw-r--r--   0 sunhui     (501) staff       (20)     6680 2023-06-19 20:20:55.000000 fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Equilibrium Simulation/1_mole.exp
--rw-r--r--   0 sunhui     (501) staff       (20)     6684 2023-06-19 20:20:56.000000 fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Equilibrium Simulation/1_wt.exp
--rw-r--r--   0 sunhui     (501) staff       (20)     6680 2023-06-19 20:21:05.000000 fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Equilibrium Simulation/2_mole.exp
--rw-r--r--   0 sunhui     (501) staff       (20)     6684 2023-06-19 20:21:05.000000 fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Equilibrium Simulation/2_wt.exp
-drwxr-xr-x   0 sunhui     (501) staff       (20)        0 2023-06-26 18:06:47.099328 fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/
--rw-r--r--   0 sunhui     (501) staff       (20)     1813 2023-06-19 20:23:19.000000 fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/0_composition_wt%.exp
--rw-r--r--   0 sunhui     (501) staff       (20)      966 2023-06-19 20:23:17.000000 fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/0_liquid_mol%.exp
--rw-r--r--   0 sunhui     (501) staff       (20)      966 2023-06-19 20:23:19.000000 fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/0_liquid_wt%.exp
--rw-r--r--   0 sunhui     (501) staff       (20)     1034 2023-06-19 20:23:18.000000 fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/0_solid_mol%.exp
--rw-r--r--   0 sunhui     (501) staff       (20)     1034 2023-06-19 20:23:18.000000 fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/0_solid_wt%.exp
--rw-r--r--   0 sunhui     (501) staff       (20)     1813 2023-06-19 20:23:31.000000 fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/1_composition_wt%.exp
--rw-r--r--   0 sunhui     (501) staff       (20)      966 2023-06-19 20:23:30.000000 fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/1_liquid_mol%.exp
--rw-r--r--   0 sunhui     (501) staff       (20)      966 2023-06-19 20:23:31.000000 fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/1_liquid_wt%.exp
--rw-r--r--   0 sunhui     (501) staff       (20)     1034 2023-06-19 20:23:30.000000 fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/1_solid_mol%.exp
--rw-r--r--   0 sunhui     (501) staff       (20)     1034 2023-06-19 20:23:30.000000 fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/1_solid_wt%.exp
--rw-r--r--   0 sunhui     (501) staff       (20)     1813 2023-06-19 20:23:12.000000 fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/2_composition_wt%.exp
--rw-r--r--   0 sunhui     (501) staff       (20)      966 2023-06-19 20:23:09.000000 fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/2_liquid_mol%.exp
--rw-r--r--   0 sunhui     (501) staff       (20)      966 2023-06-19 20:23:11.000000 fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/2_liquid_wt%.exp
--rw-r--r--   0 sunhui     (501) staff       (20)     1034 2023-06-19 20:23:10.000000 fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/2_solid_mol%.exp
--rw-r--r--   0 sunhui     (501) staff       (20)     1034 2023-06-19 20:23:11.000000 fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/2_solid_wt%.exp
-drwxr-xr-x   0 sunhui     (501) staff       (20)        0 2023-06-26 18:06:47.099773 fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/Result/
--rw-r--r--   0 sunhui     (501) staff       (20)        0 2023-06-22 15:06:21.000000 fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/Result/data.json
--rw-r--r--   0 sunhui     (501) staff       (20)     5055 2023-06-20 19:44:03.000000 fmat-0.1.0/fmat/tests/testsCaseFiles/composition_for_feasibilityMap.xlsx
--rw-r--r--   0 sunhui     (501) staff       (20)      488 2023-06-26 18:05:27.000000 fmat-0.1.0/fmat/tests/testsCaseFiles/setting.npy
-drwxr-xr-x   0 sunhui     (501) staff       (20)        0 2023-06-26 18:06:47.077054 fmat-0.1.0/fmat.egg-info/
--rw-r--r--   0 sunhui     (501) staff       (20)      774 2023-06-26 18:06:44.000000 fmat-0.1.0/fmat.egg-info/PKG-INFO
--rw-r--r--   0 sunhui     (501) staff       (20)     3330 2023-06-26 18:06:47.000000 fmat-0.1.0/fmat.egg-info/SOURCES.txt
--rw-r--r--   0 sunhui     (501) staff       (20)        1 2023-06-26 18:06:44.000000 fmat-0.1.0/fmat.egg-info/dependency_links.txt
--rw-r--r--   0 sunhui     (501) staff       (20)      127 2023-06-26 18:06:44.000000 fmat-0.1.0/fmat.egg-info/requires.txt
--rw-r--r--   0 sunhui     (501) staff       (20)        5 2023-06-26 18:06:44.000000 fmat-0.1.0/fmat.egg-info/top_level.txt
--rw-r--r--   0 sunhui     (501) staff       (20)     1048 2023-06-26 18:04:55.000000 fmat-0.1.0/pyproject.toml
--rw-r--r--   0 sunhui     (501) staff       (20)       38 2023-06-26 18:06:47.100836 fmat-0.1.0/setup.cfg
+drwxr-xr-x   0 sunhui     (501) staff       (20)        0 2023-06-28 13:26:36.737960 fmat-0.1.3/
+drwxr-xr-x   0 sunhui     (501) staff       (20)        0 2023-06-28 13:26:36.709489 fmat-0.1.3/.github/
+drwxr-xr-x   0 sunhui     (501) staff       (20)        0 2023-06-28 13:26:36.713312 fmat-0.1.3/.github/workflows/
+-rw-r--r--   0 sunhui     (501) staff       (20)      748 2023-06-28 13:20:38.000000 fmat-0.1.3/.github/workflows/lastCommit.yml
+-rw-r--r--   0 sunhui     (501) staff       (20)    35149 2023-06-23 02:15:48.000000 fmat-0.1.3/LICENSE
+-rw-r--r--   0 sunhui     (501) staff       (20)       68 2023-06-26 14:59:56.000000 fmat-0.1.3/MANIFEST.in
+-rw-r--r--   0 sunhui     (501) staff       (20)      729 2023-06-28 13:26:36.737426 fmat-0.1.3/PKG-INFO
+-rw-r--r--   0 sunhui     (501) staff       (20)     4399 2023-06-26 18:25:01.000000 fmat-0.1.3/README.rst
+drwxr-xr-x   0 sunhui     (501) staff       (20)        0 2023-06-28 13:26:36.713756 fmat-0.1.3/fmat/
+drwxr-xr-x   0 sunhui     (501) staff       (20)        0 2023-06-28 13:26:36.719701 fmat-0.1.3/fmat/core/
+-rw-rw-r--   0 sunhui     (501) staff       (20)     9842 2023-06-26 13:02:55.000000 fmat-0.1.3/fmat/core/GenerateEqScript.py
+-rw-r--r--   0 sunhui     (501) staff       (20)    11710 2023-06-26 14:59:29.000000 fmat-0.1.3/fmat/core/GenerateScheilScript.py
+-rw-rw-r--   0 sunhui     (501) staff       (20)     5719 2023-06-26 14:59:24.000000 fmat-0.1.3/fmat/core/ReadEqResult.py
+-rw-rw-r--   0 sunhui     (501) staff       (20)    12898 2023-06-26 14:59:20.000000 fmat-0.1.3/fmat/core/ReadScheilResult.py
+-rw-r--r--   0 sunhui     (501) staff       (20)        0 2023-06-19 20:33:09.000000 fmat-0.1.3/fmat/core/__init__.py
+-rw-r--r--   0 sunhui     (501) staff       (20)     4439 2023-06-26 14:59:32.000000 fmat-0.1.3/fmat/core/compositions.py
+-rw-r--r--   0 sunhui     (501) staff       (20)     8388 2023-06-28 13:15:59.000000 fmat-0.1.3/fmat/core/pycalphad_run.py
+drwxr-xr-x   0 sunhui     (501) staff       (20)        0 2023-06-28 13:26:36.720862 fmat-0.1.3/fmat/plot/
+-rw-rw-r--   0 sunhui     (501) staff       (20)    34457 2023-06-26 14:59:18.000000 fmat-0.1.3/fmat/plot/FeasibilityMap.py
+-rw-r--r--   0 sunhui     (501) staff       (20)        0 2023-06-19 20:33:17.000000 fmat-0.1.3/fmat/plot/__init__.py
+-rw-rw-r--   0 sunhui     (501) staff       (20)     4368 2023-06-14 20:17:00.000000 fmat-0.1.3/fmat/plot/feasibility_helpers.py
+-rw-r--r--   0 sunhui     (501) staff       (20)     4750 2023-06-20 20:40:05.000000 fmat-0.1.3/fmat/ref_data.py
+drwxr-xr-x   0 sunhui     (501) staff       (20)        0 2023-06-28 13:26:36.722473 fmat-0.1.3/fmat/tests/
+-rw-r--r--   0 sunhui     (501) staff       (20)        0 2023-06-21 20:12:11.000000 fmat-0.1.3/fmat/tests/__init__.py
+-rw-r--r--   0 sunhui     (501) staff       (20)     1279 2023-06-26 14:59:16.000000 fmat-0.1.3/fmat/tests/test_compositions.py
+-rw-r--r--   0 sunhui     (501) staff       (20)    13284 2023-06-26 14:59:12.000000 fmat-0.1.3/fmat/tests/test_plotting.py
+-rw-r--r--   0 sunhui     (501) staff       (20)     1815 2023-06-28 13:19:40.000000 fmat-0.1.3/fmat/tests/test_pycalphad_run.py
+-rw-r--r--   0 sunhui     (501) staff       (20)     3513 2023-06-26 14:59:00.000000 fmat-0.1.3/fmat/tests/test_thermo_calc_script.py
+drwxr-xr-x   0 sunhui     (501) staff       (20)        0 2023-06-28 13:26:36.723646 fmat-0.1.3/fmat/tests/testsCaseFiles/
+-rw-r--r--   0 sunhui     (501) staff       (20)    16269 2023-03-30 16:57:48.000000 fmat-0.1.3/fmat/tests/testsCaseFiles/Ag-Al-Cu.TDB
+drwxr-xr-x   0 sunhui     (501) staff       (20)        0 2023-06-28 13:26:36.711066 fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/
+drwxr-xr-x   0 sunhui     (501) staff       (20)        0 2023-06-28 13:26:36.727410 fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Equilibrium Simulation/
+-rw-r--r--   0 sunhui     (501) staff       (20)     6680 2023-06-19 20:21:14.000000 fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Equilibrium Simulation/0_mole.exp
+-rw-r--r--   0 sunhui     (501) staff       (20)     6684 2023-06-19 20:21:14.000000 fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Equilibrium Simulation/0_wt.exp
+-rw-r--r--   0 sunhui     (501) staff       (20)     6680 2023-06-19 20:20:55.000000 fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Equilibrium Simulation/1_mole.exp
+-rw-r--r--   0 sunhui     (501) staff       (20)     6684 2023-06-19 20:20:56.000000 fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Equilibrium Simulation/1_wt.exp
+-rw-r--r--   0 sunhui     (501) staff       (20)     6680 2023-06-19 20:21:05.000000 fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Equilibrium Simulation/2_mole.exp
+-rw-r--r--   0 sunhui     (501) staff       (20)     6684 2023-06-19 20:21:05.000000 fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Equilibrium Simulation/2_wt.exp
+drwxr-xr-x   0 sunhui     (501) staff       (20)        0 2023-06-28 13:26:36.736150 fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/
+-rw-r--r--   0 sunhui     (501) staff       (20)     1813 2023-06-19 20:23:19.000000 fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/0_composition_wt%.exp
+-rw-r--r--   0 sunhui     (501) staff       (20)      966 2023-06-19 20:23:17.000000 fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/0_liquid_mol%.exp
+-rw-r--r--   0 sunhui     (501) staff       (20)      966 2023-06-19 20:23:19.000000 fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/0_liquid_wt%.exp
+-rw-r--r--   0 sunhui     (501) staff       (20)     1034 2023-06-19 20:23:18.000000 fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/0_solid_mol%.exp
+-rw-r--r--   0 sunhui     (501) staff       (20)     1034 2023-06-19 20:23:18.000000 fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/0_solid_wt%.exp
+-rw-r--r--   0 sunhui     (501) staff       (20)     1813 2023-06-19 20:23:31.000000 fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/1_composition_wt%.exp
+-rw-r--r--   0 sunhui     (501) staff       (20)      966 2023-06-19 20:23:30.000000 fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/1_liquid_mol%.exp
+-rw-r--r--   0 sunhui     (501) staff       (20)      966 2023-06-19 20:23:31.000000 fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/1_liquid_wt%.exp
+-rw-r--r--   0 sunhui     (501) staff       (20)     1034 2023-06-19 20:23:30.000000 fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/1_solid_mol%.exp
+-rw-r--r--   0 sunhui     (501) staff       (20)     1034 2023-06-19 20:23:30.000000 fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/1_solid_wt%.exp
+-rw-r--r--   0 sunhui     (501) staff       (20)     1813 2023-06-19 20:23:12.000000 fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/2_composition_wt%.exp
+-rw-r--r--   0 sunhui     (501) staff       (20)      966 2023-06-19 20:23:09.000000 fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/2_liquid_mol%.exp
+-rw-r--r--   0 sunhui     (501) staff       (20)      966 2023-06-19 20:23:11.000000 fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/2_liquid_wt%.exp
+-rw-r--r--   0 sunhui     (501) staff       (20)     1034 2023-06-19 20:23:10.000000 fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/2_solid_mol%.exp
+-rw-r--r--   0 sunhui     (501) staff       (20)     1034 2023-06-19 20:23:11.000000 fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/2_solid_wt%.exp
+drwxr-xr-x   0 sunhui     (501) staff       (20)        0 2023-06-28 13:26:36.736750 fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/Result/
+-rw-r--r--   0 sunhui     (501) staff       (20)        0 2023-06-22 15:06:21.000000 fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/Result/data.json
+-rw-r--r--   0 sunhui     (501) staff       (20)     5055 2023-06-20 19:44:03.000000 fmat-0.1.3/fmat/tests/testsCaseFiles/composition_for_feasibilityMap.xlsx
+-rw-r--r--   0 sunhui     (501) staff       (20)      488 2023-06-28 13:17:23.000000 fmat-0.1.3/fmat/tests/testsCaseFiles/setting.npy
+drwxr-xr-x   0 sunhui     (501) staff       (20)        0 2023-06-28 13:26:36.716553 fmat-0.1.3/fmat.egg-info/
+-rw-r--r--   0 sunhui     (501) staff       (20)      729 2023-06-28 13:26:34.000000 fmat-0.1.3/fmat.egg-info/PKG-INFO
+-rw-r--r--   0 sunhui     (501) staff       (20)     2414 2023-06-28 13:26:36.000000 fmat-0.1.3/fmat.egg-info/SOURCES.txt
+-rw-r--r--   0 sunhui     (501) staff       (20)        1 2023-06-28 13:26:34.000000 fmat-0.1.3/fmat.egg-info/dependency_links.txt
+-rw-r--r--   0 sunhui     (501) staff       (20)      118 2023-06-28 13:26:34.000000 fmat-0.1.3/fmat.egg-info/requires.txt
+-rw-r--r--   0 sunhui     (501) staff       (20)        5 2023-06-28 13:26:34.000000 fmat-0.1.3/fmat.egg-info/top_level.txt
+-rw-r--r--   0 sunhui     (501) staff       (20)     1000 2023-06-28 13:26:19.000000 fmat-0.1.3/pyproject.toml
+-rw-r--r--   0 sunhui     (501) staff       (20)       38 2023-06-28 13:26:36.738164 fmat-0.1.3/setup.cfg
```

### Comparing `fmat-0.1.0/LICENSE` & `fmat-0.1.3/LICENSE`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/PKG-INFO` & `fmat-0.1.3/PKG-INFO`

 * *Files 7% similar despite different names*

```diff
@@ -1,18 +1,17 @@
 Metadata-Version: 2.1
 Name: fmat
-Version: 0.1.0
+Version: 0.1.3
 Summary: Feasibility MAP for materials design
 Author-email: Hui Sun <HuiSun@psu.edu>
 Project-URL: Bug Tracker, https://github.com/HUISUN24/feasibility_map/issues
 Classifier: Programming Language :: Python :: 3.9
-Classifier: Programming Language :: Python :: 3.10
 Classifier: Development Status :: 2 - Pre-Alpha
 Classifier: Intended Audience :: Science/Research
 Classifier: License :: OSI Approved :: GNU General Public License v3 (GPLv3)
 Classifier: Operating System :: OS Independent
 Classifier: Topic :: Scientific/Engineering
 Classifier: Topic :: Scientific/Engineering :: Chemistry
 Classifier: Topic :: Scientific/Engineering :: Physics
-Requires-Python: >=3.9
+Requires-Python: <3.10,>=3.8
 Description-Content-Type: text/markdown
 License-File: LICENSE
```

### Comparing `fmat-0.1.0/README.rst` & `fmat-0.1.3/README.rst`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/core/GenerateEqScript.py` & `fmat-0.1.3/fmat/core/GenerateEqScript.py`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/core/GenerateScheilScript.py` & `fmat-0.1.3/fmat/core/GenerateScheilScript.py`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/core/ReadEqResult.py` & `fmat-0.1.3/fmat/core/ReadEqResult.py`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/core/ReadScheilResult.py` & `fmat-0.1.3/fmat/core/ReadScheilResult.py`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/core/compositions.py` & `fmat-0.1.3/fmat/core/compositions.py`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/core/pycalphad_run.py` & `fmat-0.1.3/fmat/core/pycalphad_run.py`

 * *Files 4% similar despite different names*

```diff
@@ -53,15 +53,15 @@
         print(f"{composition} ({num+1}/{len(compositions_list)})")
         # Equilibrium calculation for feasibility
         
         for key,val in composition.items():
             composition[key] = float("{:.6f}".format(val))    
         conds = {**composition}
         conds.update(potentials)
-        
+        print('aa',comps, phases, conds)
         iter_args_equilibrium.append((dbf, comps, phases, conds))
     # Multiprocessing step:
     cores = os.cpu_count() - 1
     with Pool(cores) as p:
         eq_results = p.starmap(equilibrium, iter_args_equilibrium)
     # Chang eq result to dict
     equilibrium_result = defaultdict(dict)
@@ -128,22 +128,22 @@
     if isExist:
         f = open(path+'/Pycalphad/Equilibrium Simulation'+'/Result/data_mole.json')
         eq_results = json.load(f)
         for j in eq_results.values():
             if len(j.keys()) == 1:
                 j = None
                 LiquidusTemp.append(intial_temperature)
-                continue;
+                break;
             for n,a in enumerate(j['LIQUID']):
                 if n+1 == len(j['LIQUID']):
                     print('cannot find liquid phase in eq results, start with back up temperature')
                     LiquidusTemp.append(intial_temperature)
                 elif float(a) < 1 and float(j['LIQUID'][n+1]) == 1:
                     LiquidusTemp.append(j['TK'][n+1])
-                    continue;
+                    break;
     if len(LiquidusTemp) == 0:
         T_liquid = [intial_temperature]*len(compositions_list)
     else:
         T_liquid = LiquidusTemp
     # Generate points for adaptive Scheil starting points (performance)
     points_dict = {}
     for phase_name in phases:
@@ -160,14 +160,15 @@
     adaptive = True
     # Run simulations
     iter_args_scheil = []
     for num, composition in enumerate(compositions_list):
         print(f"{composition} ({num+1}/{len(compositions_list)})")
         for key,val in composition.items():
             composition[key] = float("{:.6f}".format(val))    
+        print('in',comps, phases, composition, T_liquid[num], step_temperature,liquid_name)
         iter_args_scheil.append((dbf, comps, phases, composition, T_liquid[num], step_temperature,liquid_name, eq_kwargs,
                                    stop, verbose, adaptive))
     # Multiprocessing step:
     cores = os.cpu_count() - 1
     
     with Pool(cores) as p:    
         scheil_results_ori = p.starmap(simulate_scheil_solidification, iter_args_scheil)
```

### Comparing `fmat-0.1.0/fmat/plot/FeasibilityMap.py` & `fmat-0.1.3/fmat/plot/FeasibilityMap.py`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/plot/feasibility_helpers.py` & `fmat-0.1.3/fmat/plot/feasibility_helpers.py`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/ref_data.py` & `fmat-0.1.3/fmat/ref_data.py`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/tests/test_compositions.py` & `fmat-0.1.3/fmat/tests/test_compositions.py`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/tests/test_plotting.py` & `fmat-0.1.3/fmat/tests/test_plotting.py`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/tests/test_pycalphad_run.py` & `fmat-0.1.3/fmat/tests/test_pycalphad_run.py`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/tests/test_thermo_calc_script.py` & `fmat-0.1.3/fmat/tests/test_thermo_calc_script.py`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/tests/testsCaseFiles/Ag-Al-Cu.TDB` & `fmat-0.1.3/fmat/tests/testsCaseFiles/Ag-Al-Cu.TDB`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Equilibrium Simulation/0_mole.exp` & `fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Equilibrium Simulation/0_mole.exp`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Equilibrium Simulation/0_wt.exp` & `fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Equilibrium Simulation/0_wt.exp`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Equilibrium Simulation/1_mole.exp` & `fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Equilibrium Simulation/1_mole.exp`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Equilibrium Simulation/1_wt.exp` & `fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Equilibrium Simulation/1_wt.exp`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Equilibrium Simulation/2_mole.exp` & `fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Equilibrium Simulation/2_mole.exp`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Equilibrium Simulation/2_wt.exp` & `fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Equilibrium Simulation/2_wt.exp`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/0_composition_wt%.exp` & `fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/0_composition_wt%.exp`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/0_liquid_mol%.exp` & `fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/0_liquid_mol%.exp`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/0_liquid_wt%.exp` & `fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/0_liquid_wt%.exp`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/0_solid_mol%.exp` & `fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/0_solid_mol%.exp`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/0_solid_wt%.exp` & `fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/0_solid_wt%.exp`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/1_composition_wt%.exp` & `fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/1_composition_wt%.exp`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/1_liquid_mol%.exp` & `fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/1_liquid_mol%.exp`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/1_liquid_wt%.exp` & `fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/1_liquid_wt%.exp`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/1_solid_mol%.exp` & `fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/1_solid_mol%.exp`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/1_solid_wt%.exp` & `fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/1_solid_wt%.exp`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/2_composition_wt%.exp` & `fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/2_composition_wt%.exp`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/2_liquid_mol%.exp` & `fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/2_liquid_mol%.exp`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/2_liquid_wt%.exp` & `fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/2_liquid_wt%.exp`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/2_solid_mol%.exp` & `fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/2_solid_mol%.exp`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/2_solid_wt%.exp` & `fmat-0.1.3/fmat/tests/testsCaseFiles/Thermo-calc/Scheil Simulation/2_solid_wt%.exp`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat/tests/testsCaseFiles/composition_for_feasibilityMap.xlsx` & `fmat-0.1.3/fmat/tests/testsCaseFiles/composition_for_feasibilityMap.xlsx`

 * *Files identical despite different names*

### Comparing `fmat-0.1.0/fmat.egg-info/PKG-INFO` & `fmat-0.1.3/fmat.egg-info/PKG-INFO`

 * *Files 7% similar despite different names*

```diff
@@ -1,18 +1,17 @@
 Metadata-Version: 2.1
 Name: fmat
-Version: 0.1.0
+Version: 0.1.3
 Summary: Feasibility MAP for materials design
 Author-email: Hui Sun <HuiSun@psu.edu>
 Project-URL: Bug Tracker, https://github.com/HUISUN24/feasibility_map/issues
 Classifier: Programming Language :: Python :: 3.9
-Classifier: Programming Language :: Python :: 3.10
 Classifier: Development Status :: 2 - Pre-Alpha
 Classifier: Intended Audience :: Science/Research
 Classifier: License :: OSI Approved :: GNU General Public License v3 (GPLv3)
 Classifier: Operating System :: OS Independent
 Classifier: Topic :: Scientific/Engineering
 Classifier: Topic :: Scientific/Engineering :: Chemistry
 Classifier: Topic :: Scientific/Engineering :: Physics
-Requires-Python: >=3.9
+Requires-Python: <3.10,>=3.8
 Description-Content-Type: text/markdown
 License-File: LICENSE
```

### Comparing `fmat-0.1.0/pyproject.toml` & `fmat-0.1.3/pyproject.toml`

 * *Files 8% similar despite different names*

```diff
@@ -1,35 +1,34 @@
 [build-system]
 requires = ["setuptools>=61.0", "setuptools-scm"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "fmat"
-version = "0.1.0"
+version = "0.1.3"
 authors = [
   { name="Hui Sun", email="HuiSun@psu.edu" },
 ]
 classifiers = [
     "Programming Language :: Python :: 3.9",
-    "Programming Language :: Python :: 3.10",
     "Development Status :: 2 - Pre-Alpha",
     "Intended Audience :: Science/Research",
     "License :: OSI Approved :: GNU General Public License v3 (GPLv3)",
     "Operating System :: OS Independent",
     "Topic :: Scientific/Engineering",
     "Topic :: Scientific/Engineering :: Chemistry",
     "Topic :: Scientific/Engineering :: Physics",
 ]
 description = "Feasibility MAP for materials design"
 readme = "README.md"
 
-requires-python = ">=3.9"
+requires-python = ">=3.8, <3.10"
 dependencies = [
-    "matplotlib>=3.6.2",
-    "numpy<=1.20.3",
+    "matplotlib",
+    "numpy<=1.22",
     "pycalphad<=0.9.2",
     "pandas>=2.0.2",
     "tqdm>=4.65.0",
     "scheil>=0.1.6",
     "scikit-learn>=0.24.1",
     "openpyxl>=3.1.2",
 ]
```


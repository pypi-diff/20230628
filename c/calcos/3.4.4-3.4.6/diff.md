# Comparing `tmp/calcos-3.4.4.tar.gz` & `tmp/calcos-3.4.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "calcos-3.4.4.tar", last modified: Thu Jan 12 18:28:52 2023, max compression
+gzip compressed data, was "calcos-3.4.6.tar", last modified: Wed Jun 28 13:55:19 2023, max compression
```

## Comparing `calcos-3.4.4.tar` & `calcos-3.4.6.tar`

### file list

```diff
@@ -1,82 +1,85 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-01-12 18:28:52.025339 calcos-3.4.4/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-01-12 18:28:52.017339 calcos-3.4.4/.github/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-01-12 18:28:52.017339 calcos-3.4.4/.github/workflows/
--rw-r--r--   0 runner    (1001) docker     (123)     1274 2023-01-12 18:28:28.000000 calcos-3.4.4/.github/workflows/publish-to-pypi.yml
--rw-r--r--   0 runner    (1001) docker     (123)     1733 2023-01-12 18:28:28.000000 calcos-3.4.4/.github/workflows/python_testing.yml
--rw-r--r--   0 runner    (1001) docker     (123)       98 2023-01-12 18:28:28.000000 calcos-3.4.4/.gitignore
--rw-r--r--   0 runner    (1001) docker     (123)      434 2023-01-12 18:28:28.000000 calcos-3.4.4/.readthedocs.yml
--rw-r--r--   0 runner    (1001) docker     (123)     3207 2023-01-12 18:28:28.000000 calcos-3.4.4/CODE_OF_CONDUCT.md
--rw-r--r--   0 runner    (1001) docker     (123)     1371 2023-01-12 18:28:28.000000 calcos-3.4.4/Jenkinsfile
--rw-r--r--   0 runner    (1001) docker     (123)     1667 2023-01-12 18:28:28.000000 calcos-3.4.4/JenkinsfileRT
--rw-r--r--   0 runner    (1001) docker     (123)      672 2023-01-12 18:28:52.025339 calcos-3.4.4/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      370 2023-01-12 18:28:28.000000 calcos-3.4.4/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-01-12 18:28:52.021339 calcos-3.4.4/calcos/
--rw-r--r--   0 runner    (1001) docker     (123)     5253 2023-01-12 18:28:28.000000 calcos-3.4.4/calcos/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    25421 2023-01-12 18:28:28.000000 calcos-3.4.4/calcos/accum.py
--rw-r--r--   0 runner    (1001) docker     (123)     3548 2023-01-12 18:28:28.000000 calcos-3.4.4/calcos/airglow.py
--rw-r--r--   0 runner    (1001) docker     (123)     5262 2023-01-12 18:28:28.000000 calcos-3.4.4/calcos/average.py
--rw-r--r--   0 runner    (1001) docker     (123)    13155 2023-01-12 18:28:28.000000 calcos-3.4.4/calcos/burst.py
--rw-r--r--   0 runner    (1001) docker     (123)     7611 2023-01-12 18:28:28.000000 calcos-3.4.4/calcos/calcos.help
--rwxr-xr-x   0 runner    (1001) docker     (123)   139904 2023-01-12 18:28:28.000000 calcos-3.4.4/calcos/calcos.py
--rw-r--r--   0 runner    (1001) docker     (123)     6652 2023-01-12 18:28:28.000000 calcos-3.4.4/calcos/calcosparam.py
--rw-r--r--   0 runner    (1001) docker     (123)    82085 2023-01-12 18:28:28.000000 calcos-3.4.4/calcos/concurrent.py
--rwxr-xr-x   0 runner    (1001) docker     (123)   128867 2023-01-12 18:28:28.000000 calcos-3.4.4/calcos/cosutil.py
--rw-r--r--   0 runner    (1001) docker     (123)     6713 2023-01-12 18:28:28.000000 calcos-3.4.4/calcos/dispersion.py
--rw-r--r--   0 runner    (1001) docker     (123)   115243 2023-01-12 18:28:28.000000 calcos-3.4.4/calcos/extract.py
--rw-r--r--   0 runner    (1001) docker     (123)    35355 2023-01-12 18:28:28.000000 calcos-3.4.4/calcos/findshift1.py
--rw-r--r--   0 runner    (1001) docker     (123)    49402 2023-01-12 18:28:28.000000 calcos-3.4.4/calcos/fpavg.py
--rw-r--r--   0 runner    (1001) docker     (123)    13126 2023-01-12 18:28:28.000000 calcos-3.4.4/calcos/getinfo.py
--rw-r--r--   0 runner    (1001) docker     (123)     6296 2023-01-12 18:28:28.000000 calcos-3.4.4/calcos/orbit.py
--rw-r--r--   0 runner    (1001) docker     (123)     6393 2023-01-12 18:28:28.000000 calcos-3.4.4/calcos/osmstep.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-01-12 18:28:52.025339 calcos-3.4.4/calcos/pars/
--rw-r--r--   0 runner    (1001) docker     (123)      313 2023-01-12 18:28:28.000000 calcos-3.4.4/calcos/pars/calcos.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     1472 2023-01-12 18:28:28.000000 calcos-3.4.4/calcos/pars/calcos.cfgspc
--rw-r--r--   0 runner    (1001) docker     (123)     5149 2023-01-12 18:28:28.000000 calcos-3.4.4/calcos/phot.py
--rw-r--r--   0 runner    (1001) docker     (123)     4765 2023-01-12 18:28:28.000000 calcos-3.4.4/calcos/shiftfile.py
--rw-r--r--   0 runner    (1001) docker     (123)    23257 2023-01-12 18:28:28.000000 calcos-3.4.4/calcos/splittag.py
--rw-r--r--   0 runner    (1001) docker     (123)    21291 2023-01-12 18:28:28.000000 calcos-3.4.4/calcos/spwcs.py
--rw-r--r--   0 runner    (1001) docker     (123)    25999 2023-01-12 18:28:28.000000 calcos-3.4.4/calcos/timeline.py
--rw-r--r--   0 runner    (1001) docker     (123)   185542 2023-01-12 18:28:28.000000 calcos-3.4.4/calcos/timetag.py
--rw-r--r--   0 runner    (1001) docker     (123)    27796 2023-01-12 18:28:28.000000 calcos-3.4.4/calcos/trace.py
--rw-r--r--   0 runner    (1001) docker     (123)      160 2023-01-12 18:28:51.000000 calcos-3.4.4/calcos/version.py
--rw-r--r--   0 runner    (1001) docker     (123)    37980 2023-01-12 18:28:28.000000 calcos-3.4.4/calcos/wavecal.py
--rwxr-xr-x   0 runner    (1001) docker     (123)    21305 2023-01-12 18:28:28.000000 calcos-3.4.4/calcos/x1d.py
--rw-r--r--   0 runner    (1001) docker     (123)    12077 2023-01-12 18:28:28.000000 calcos-3.4.4/calcos/xd_search.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-01-12 18:28:52.025339 calcos-3.4.4/calcos.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)      672 2023-01-12 18:28:51.000000 calcos-3.4.4/calcos.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1445 2023-01-12 18:28:52.000000 calcos-3.4.4/calcos.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-01-12 18:28:51.000000 calcos-3.4.4/calcos.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       39 2023-01-12 18:28:51.000000 calcos-3.4.4/calcos.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)      105 2023-01-12 18:28:51.000000 calcos-3.4.4/calcos.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)        7 2023-01-12 18:28:51.000000 calcos-3.4.4/calcos.egg-info/top_level.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-01-12 18:28:52.025339 calcos-3.4.4/docs/
--rw-r--r--   0 runner    (1001) docker     (123)     3130 2023-01-12 18:28:28.000000 calcos-3.4.4/docs/Makefile
--rw-r--r--   0 runner    (1001) docker     (123)     3075 2023-01-12 18:28:28.000000 calcos-3.4.4/docs/make.bat
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-01-12 18:28:52.025339 calcos-3.4.4/docs/source/
--rw-r--r--   0 runner    (1001) docker     (123)     6684 2023-01-12 18:28:28.000000 calcos-3.4.4/docs/source/conf.py
--rw-r--r--   0 runner    (1001) docker     (123)      361 2023-01-12 18:28:28.000000 calcos-3.4.4/docs/source/index.rst
--rw-r--r--   0 runner    (1001) docker     (123)      170 2023-01-12 18:28:28.000000 calcos-3.4.4/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)      228 2023-01-12 18:28:52.029338 calcos-3.4.4/setup.cfg
--rwxr-xr-x   0 runner    (1001) docker     (123)     2271 2023-01-12 18:28:28.000000 calcos-3.4.4/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-01-12 18:28:52.025339 calcos-3.4.4/src/
--rw-r--r--   0 runner    (1001) docker     (123)   129422 2023-01-12 18:28:28.000000 calcos-3.4.4/src/ccos.c
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-01-12 18:28:52.025339 calcos-3.4.4/tests/
--rw-r--r--   0 runner    (1001) docker     (123)     6605 2023-01-12 18:28:28.000000 calcos-3.4.4/tests/README.md
--rw-r--r--   0 runner    (1001) docker     (123)     1294 2023-01-12 18:28:28.000000 calcos-3.4.4/tests/conftest.py
--rw-r--r--   0 runner    (1001) docker     (123)    24325 2023-01-12 18:28:28.000000 calcos-3.4.4/tests/generate_tempfiles.py
--rw-r--r--   0 runner    (1001) docker     (123)     8199 2023-01-12 18:28:28.000000 calcos-3.4.4/tests/helpers.py
--rw-r--r--   0 runner    (1001) docker     (123)     1494 2023-01-12 18:28:28.000000 calcos-3.4.4/tests/test_airglow.py
--rw-r--r--   0 runner    (1001) docker     (123)     1144 2023-01-12 18:28:28.000000 calcos-3.4.4/tests/test_average.py
--rw-r--r--   0 runner    (1001) docker     (123)    35265 2023-01-12 18:28:28.000000 calcos-3.4.4/tests/test_cosutil.py
--rw-r--r--   0 runner    (1001) docker     (123)     1233 2023-01-12 18:28:28.000000 calcos-3.4.4/tests/test_dark_fuva.py
--rw-r--r--   0 runner    (1001) docker     (123)     1183 2023-01-12 18:28:28.000000 calcos-3.4.4/tests/test_dark_fuvb.py
--rw-r--r--   0 runner    (1001) docker     (123)     1108 2023-01-12 18:28:28.000000 calcos-3.4.4/tests/test_dark_nuv.py
--rw-r--r--   0 runner    (1001) docker     (123)     2156 2023-01-12 18:28:28.000000 calcos-3.4.4/tests/test_extract.py
--rw-r--r--   0 runner    (1001) docker     (123)     1116 2023-01-12 18:28:28.000000 calcos-3.4.4/tests/test_flat_fuva.py
--rw-r--r--   0 runner    (1001) docker     (123)     1104 2023-01-12 18:28:28.000000 calcos-3.4.4/tests/test_flat_nuv.py
--rw-r--r--   0 runner    (1001) docker     (123)     1196 2023-01-12 18:28:28.000000 calcos-3.4.4/tests/test_flat_relmvreq.py
--rw-r--r--   0 runner    (1001) docker     (123)     1627 2023-01-12 18:28:28.000000 calcos-3.4.4/tests/test_fuv_timetag.py
--rw-r--r--   0 runner    (1001) docker     (123)     2111 2023-01-12 18:28:28.000000 calcos-3.4.4/tests/test_shiftfile.py
--rw-r--r--   0 runner    (1001) docker     (123)     1268 2023-01-12 18:28:28.000000 calcos-3.4.4/tests/test_wavecal_fuva_f140l.py
--rw-r--r--   0 runner    (1001) docker     (123)     1155 2023-01-12 18:28:28.000000 calcos-3.4.4/tests/test_wavecal_fuva_g130m.py
--rw-r--r--   0 runner    (1001) docker     (123)     1773 2023-01-12 18:28:28.000000 calcos-3.4.4/tox.ini
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:55:19.637626 calcos-3.4.6/
+-rw-r--r--   0 runner    (1001) docker     (123)      230 2023-06-28 13:55:07.000000 calcos-3.4.6/.flake8
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:55:19.629626 calcos-3.4.6/.github/
+-rw-r--r--   0 runner    (1001) docker     (123)      161 2023-06-28 13:55:07.000000 calcos-3.4.6/.github/CODEOWNERS
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:55:19.629626 calcos-3.4.6/.github/workflows/
+-rw-r--r--   0 runner    (1001) docker     (123)     1276 2023-06-28 13:55:07.000000 calcos-3.4.6/.github/workflows/publish-to-pypi.yml
+-rw-r--r--   0 runner    (1001) docker     (123)     1733 2023-06-28 13:55:07.000000 calcos-3.4.6/.github/workflows/python_testing.yml
+-rw-r--r--   0 runner    (1001) docker     (123)       98 2023-06-28 13:55:07.000000 calcos-3.4.6/.gitignore
+-rw-r--r--   0 runner    (1001) docker     (123)      544 2023-06-28 13:55:07.000000 calcos-3.4.6/.readthedocs.yml
+-rw-r--r--   0 runner    (1001) docker     (123)     3207 2023-06-28 13:55:07.000000 calcos-3.4.6/CODE_OF_CONDUCT.md
+-rw-r--r--   0 runner    (1001) docker     (123)     1334 2023-06-28 13:55:07.000000 calcos-3.4.6/Jenkinsfile
+-rw-r--r--   0 runner    (1001) docker     (123)     1630 2023-06-28 13:55:07.000000 calcos-3.4.6/JenkinsfileRT
+-rw-r--r--   0 runner    (1001) docker     (123)      941 2023-06-28 13:55:19.637626 calcos-3.4.6/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      370 2023-06-28 13:55:07.000000 calcos-3.4.6/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:55:19.633626 calcos-3.4.6/calcos/
+-rw-r--r--   0 runner    (1001) docker     (123)     5253 2023-06-28 13:55:07.000000 calcos-3.4.6/calcos/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25421 2023-06-28 13:55:07.000000 calcos-3.4.6/calcos/accum.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3548 2023-06-28 13:55:07.000000 calcos-3.4.6/calcos/airglow.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5262 2023-06-28 13:55:07.000000 calcos-3.4.6/calcos/average.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13155 2023-06-28 13:55:07.000000 calcos-3.4.6/calcos/burst.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7611 2023-06-28 13:55:07.000000 calcos-3.4.6/calcos/calcos.help
+-rwxr-xr-x   0 runner    (1001) docker     (123)   139904 2023-06-28 13:55:07.000000 calcos-3.4.6/calcos/calcos.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6652 2023-06-28 13:55:07.000000 calcos-3.4.6/calcos/calcosparam.py
+-rw-r--r--   0 runner    (1001) docker     (123)    82085 2023-06-28 13:55:07.000000 calcos-3.4.6/calcos/concurrent.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)   128867 2023-06-28 13:55:07.000000 calcos-3.4.6/calcos/cosutil.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6713 2023-06-28 13:55:07.000000 calcos-3.4.6/calcos/dispersion.py
+-rw-r--r--   0 runner    (1001) docker     (123)   115243 2023-06-28 13:55:07.000000 calcos-3.4.6/calcos/extract.py
+-rw-r--r--   0 runner    (1001) docker     (123)    35355 2023-06-28 13:55:07.000000 calcos-3.4.6/calcos/findshift1.py
+-rw-r--r--   0 runner    (1001) docker     (123)    49417 2023-06-28 13:55:07.000000 calcos-3.4.6/calcos/fpavg.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13126 2023-06-28 13:55:07.000000 calcos-3.4.6/calcos/getinfo.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6296 2023-06-28 13:55:07.000000 calcos-3.4.6/calcos/orbit.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6393 2023-06-28 13:55:07.000000 calcos-3.4.6/calcos/osmstep.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:55:19.633626 calcos-3.4.6/calcos/pars/
+-rw-r--r--   0 runner    (1001) docker     (123)      313 2023-06-28 13:55:07.000000 calcos-3.4.6/calcos/pars/calcos.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1472 2023-06-28 13:55:07.000000 calcos-3.4.6/calcos/pars/calcos.cfgspc
+-rw-r--r--   0 runner    (1001) docker     (123)     5149 2023-06-28 13:55:07.000000 calcos-3.4.6/calcos/phot.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4765 2023-06-28 13:55:07.000000 calcos-3.4.6/calcos/shiftfile.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23257 2023-06-28 13:55:07.000000 calcos-3.4.6/calcos/splittag.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21291 2023-06-28 13:55:07.000000 calcos-3.4.6/calcos/spwcs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25999 2023-06-28 13:55:07.000000 calcos-3.4.6/calcos/timeline.py
+-rw-r--r--   0 runner    (1001) docker     (123)   187336 2023-06-28 13:55:07.000000 calcos-3.4.6/calcos/timetag.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27796 2023-06-28 13:55:07.000000 calcos-3.4.6/calcos/trace.py
+-rw-r--r--   0 runner    (1001) docker     (123)      160 2023-06-28 13:55:19.000000 calcos-3.4.6/calcos/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)    37980 2023-06-28 13:55:07.000000 calcos-3.4.6/calcos/wavecal.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)    21305 2023-06-28 13:55:07.000000 calcos-3.4.6/calcos/x1d.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12077 2023-06-28 13:55:07.000000 calcos-3.4.6/calcos/xd_search.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:55:19.633626 calcos-3.4.6/calcos.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)      941 2023-06-28 13:55:19.000000 calcos-3.4.6/calcos.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1488 2023-06-28 13:55:19.000000 calcos-3.4.6/calcos.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 13:55:19.000000 calcos-3.4.6/calcos.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       39 2023-06-28 13:55:19.000000 calcos-3.4.6/calcos.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      113 2023-06-28 13:55:19.000000 calcos-3.4.6/calcos.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        7 2023-06-28 13:55:19.000000 calcos-3.4.6/calcos.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:55:19.633626 calcos-3.4.6/docs/
+-rw-r--r--   0 runner    (1001) docker     (123)     3130 2023-06-28 13:55:07.000000 calcos-3.4.6/docs/Makefile
+-rw-r--r--   0 runner    (1001) docker     (123)     3075 2023-06-28 13:55:07.000000 calcos-3.4.6/docs/make.bat
+-rw-r--r--   0 runner    (1001) docker     (123)      128 2023-06-28 13:55:07.000000 calcos-3.4.6/docs/rtd_environment.yaml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:55:19.633626 calcos-3.4.6/docs/source/
+-rw-r--r--   0 runner    (1001) docker     (123)     7098 2023-06-28 13:55:07.000000 calcos-3.4.6/docs/source/conf.py
+-rw-r--r--   0 runner    (1001) docker     (123)      361 2023-06-28 13:55:07.000000 calcos-3.4.6/docs/source/index.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1406 2023-06-28 13:55:07.000000 calcos-3.4.6/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 13:55:19.637626 calcos-3.4.6/setup.cfg
+-rwxr-xr-x   0 runner    (1001) docker     (123)      943 2023-06-28 13:55:07.000000 calcos-3.4.6/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:55:19.633626 calcos-3.4.6/src/
+-rw-r--r--   0 runner    (1001) docker     (123)   129422 2023-06-28 13:55:07.000000 calcos-3.4.6/src/ccos.c
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:55:19.637626 calcos-3.4.6/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)     6605 2023-06-28 13:55:07.000000 calcos-3.4.6/tests/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)     1294 2023-06-28 13:55:07.000000 calcos-3.4.6/tests/conftest.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24325 2023-06-28 13:55:07.000000 calcos-3.4.6/tests/generate_tempfiles.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8199 2023-06-28 13:55:07.000000 calcos-3.4.6/tests/helpers.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1542 2023-06-28 13:55:07.000000 calcos-3.4.6/tests/test_airglow.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1238 2023-06-28 13:55:07.000000 calcos-3.4.6/tests/test_average.py
+-rw-r--r--   0 runner    (1001) docker     (123)    36822 2023-06-28 13:55:07.000000 calcos-3.4.6/tests/test_cosutil.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1233 2023-06-28 13:55:07.000000 calcos-3.4.6/tests/test_dark_fuva.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1183 2023-06-28 13:55:07.000000 calcos-3.4.6/tests/test_dark_fuvb.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1108 2023-06-28 13:55:07.000000 calcos-3.4.6/tests/test_dark_nuv.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2327 2023-06-28 13:55:07.000000 calcos-3.4.6/tests/test_extract.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1116 2023-06-28 13:55:07.000000 calcos-3.4.6/tests/test_flat_fuva.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1104 2023-06-28 13:55:07.000000 calcos-3.4.6/tests/test_flat_nuv.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1196 2023-06-28 13:55:07.000000 calcos-3.4.6/tests/test_flat_relmvreq.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1627 2023-06-28 13:55:07.000000 calcos-3.4.6/tests/test_fuv_timetag.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2347 2023-06-28 13:55:07.000000 calcos-3.4.6/tests/test_shiftfile.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1268 2023-06-28 13:55:07.000000 calcos-3.4.6/tests/test_wavecal_fuva_f140l.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1155 2023-06-28 13:55:07.000000 calcos-3.4.6/tests/test_wavecal_fuva_g130m.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1773 2023-06-28 13:55:07.000000 calcos-3.4.6/tox.ini
```

### Comparing `calcos-3.4.4/.github/workflows/publish-to-pypi.yml` & `calcos-3.4.6/.github/workflows/publish-to-pypi.yml`

 * *Files 4% similar despite different names*

```diff
@@ -13,15 +13,15 @@
 
   build_wheels:
     name: Build wheels on ${{ matrix.os }}
     needs: [validate]
     runs-on: ${{ matrix.os }}
     strategy:
       matrix:
-        os: [ubuntu-20.04, macos-10.15]
+        os: [ubuntu-latest, macos-latest]
 
     steps:
       - uses: spacetelescope/action-publish_to_pypi/build-wheel@master
 
   build_sdist:
     name: Build source distribution
     needs: [validate]
```

### Comparing `calcos-3.4.4/.github/workflows/python_testing.yml` & `calcos-3.4.6/.github/workflows/python_testing.yml`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/CODE_OF_CONDUCT.md` & `calcos-3.4.6/CODE_OF_CONDUCT.md`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/Jenkinsfile` & `calcos-3.4.6/Jenkinsfile`

 * *Files 4% similar despite different names*

```diff
@@ -23,13 +23,13 @@
 bc1.failedFailureThresh = 6
 
 // Run with astropy dev and Python 3.8
 bc2 = utils.copy(bc1)
 bc2.name = "dev"
 bc2.conda_packages[0] = "python=3.8"
 bc2.build_cmds = ["pip install -e .[test]",
-                  "pip install git+https://github.com/astropy/astropy.git#egg=astropy --upgrade --no-deps",
+                  "pip install astropy>=0.0.dev0 --upgrade --no-deps",
                   "pip install pyyaml"]
 
 // Iterate over configurations that define the (distibuted) build matrix.
 // Spawn a host of the given nodetype for each combination and run in parallel.
 utils.run([bc0, bc1, bc2])
```

### Comparing `calcos-3.4.4/JenkinsfileRT` & `calcos-3.4.6/JenkinsfileRT`

 * *Files 4% similar despite different names*

```diff
@@ -25,14 +25,14 @@
 bc.failedFailureThresh = 6
 
 // Astropy dev and Python 3.8 (astropy dev requires python >= 3.8)
 bc1 = utils.copy(bc)
 bc1.name = "dev"
 bc1.conda_packages[0] = "python=3.8"
 bc1.build_cmds = ["pip install -e .[test]",
-                  "pip install git+https://github.com/astropy/astropy.git#egg=astropy --upgrade --no-deps",
+                  "pip install astropy>=0.0.dev0 --upgrade --no-deps",
                   "pip install pyyaml"]
 
 // Iterate over configurations that define the (distributed) build matrix.
 // Spawn a host of the given nodetype for each combination and run in parallel.
 // Also apply the job configuration defined in `jobconfig` above.
 utils.run([bc, bc1, jobconfig])
```

### Comparing `calcos-3.4.4/PKG-INFO` & `calcos-3.4.6/PKG-INFO`

 * *Files 27% similar despite different names*

```diff
@@ -1,20 +1,25 @@
 Metadata-Version: 2.1
 Name: calcos
-Version: 3.4.4
+Version: 3.4.6
 Summary: Calibration software for COS (Cosmic Origins Spectrograph)
-Home-page: https://github.com/spacetelescope/calcos
 Author: Phil Hodge, Robert Jedrzejewski
-Author-email: help@stsci.edu
-License: BSD
 Classifier: Intended Audience :: Science/Research
 Classifier: License :: OSI Approved :: BSD License
 Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: C
 Classifier: Topic :: Software Development :: Libraries :: Python Modules
 Requires-Python: >=3.8
-Description-Content-Type: text/x-rst
+Description-Content-Type: text/markdown
 Provides-Extra: docs
 Provides-Extra: test
 
-README.md
+# CALCOS
+
+[![Jenkins CI](https://ssbjenkins.stsci.edu/job/STScI/job/calcos/job/master/badge/icon)](https://ssbjenkins.stsci.edu/job/STScI/job/calcos/job/master/)
+
+Calibration software for HST/COS.
+
+Nightly regression test results are available only from within the STScI
+network at this time.
+https://plwishmaster.stsci.edu:8081/job/RT/job/calcos/test_results_analyzer/
```

### Comparing `calcos-3.4.4/calcos/__init__.py` & `calcos-3.4.6/calcos/__init__.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/calcos/accum.py` & `calcos-3.4.6/calcos/accum.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/calcos/airglow.py` & `calcos-3.4.6/calcos/airglow.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/calcos/average.py` & `calcos-3.4.6/calcos/average.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/calcos/burst.py` & `calcos-3.4.6/calcos/burst.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/calcos/calcos.help` & `calcos-3.4.6/calcos/calcos.help`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/calcos/calcos.py` & `calcos-3.4.6/calcos/calcos.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/calcos/calcosparam.py` & `calcos-3.4.6/calcos/calcosparam.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/calcos/concurrent.py` & `calcos-3.4.6/calcos/concurrent.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/calcos/cosutil.py` & `calcos-3.4.6/calcos/cosutil.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/calcos/dispersion.py` & `calcos-3.4.6/calcos/dispersion.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/calcos/extract.py` & `calcos-3.4.6/calcos/extract.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/calcos/findshift1.py` & `calcos-3.4.6/calcos/findshift1.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/calcos/fpavg.py` & `calcos-3.4.6/calcos/fpavg.py`

 * *Files 0% similar despite different names*

```diff
@@ -592,15 +592,15 @@
         col.append(fits.Column(name="WAVELENGTH", format=rpt+"D",
                    unit="angstrom"))
         col.append(fits.Column(name="FLUX", format=rpt+"E",
                    unit="erg /s /cm**2 /angstrom"))
         col.append(fits.Column(name="ERROR", format=rpt+"E",
                    unit="erg /s /cm**2 /angstrom"))
         col.append(fits.Column(name="ERROR_LOWER", format=rpt+"E",
-                   unit="count /s"))
+                   unit="erg /s /cm**2 /angstrom"))
         col.append(fits.Column(name="GROSS", format=rpt+"E",
                    unit="count /s"))
         col.append(fits.Column(name="GCOUNTS", format=rpt+"E",
                    unit="count"))
         col.append(fits.Column(name="VARIANCE_FLAT", format=rpt+"E",
                    unit="count"))
         col.append(fits.Column(name="VARIANCE_COUNTS", format=rpt+"E",
```

### Comparing `calcos-3.4.4/calcos/getinfo.py` & `calcos-3.4.6/calcos/getinfo.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/calcos/orbit.py` & `calcos-3.4.6/calcos/orbit.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/calcos/osmstep.py` & `calcos-3.4.6/calcos/osmstep.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/calcos/pars/calcos.cfgspc` & `calcos-3.4.6/calcos/pars/calcos.cfgspc`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/calcos/phot.py` & `calcos-3.4.6/calcos/phot.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/calcos/shiftfile.py` & `calcos-3.4.6/calcos/shiftfile.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/calcos/splittag.py` & `calcos-3.4.6/calcos/splittag.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/calcos/spwcs.py` & `calcos-3.4.6/calcos/spwcs.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/calcos/timeline.py` & `calcos-3.4.6/calcos/timeline.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/calcos/timetag.py` & `calcos-3.4.6/calcos/timetag.py`

 * *Files 1% similar despite different names*

```diff
@@ -4637,21 +4637,22 @@
     full_wavecal_path = os.path.join(input_path, preceding_wavecal)
     fw = fits.open(full_wavecal_path)
     start = fw[1].header['expstart']
     fw.close()
     # Simulated wavecal is to go 600s after the start of the preceding wavecal
     tsimulated = start + 600.0 / SEC_PER_DAY
     seconds_since_exposure_start = (tsimulated - info['expstart']) * SEC_PER_DAY
-    matching_wavecals = wavecal.selectWavecalInfo(wavecal_info,
-                                                  info['cenwave'],
-                                                  info['fpoffset'])
+    matching_wavecals = getBracketingWavecals(wavecal_info,
+                                              info['cenwave'],
+                                              info['fpoffset'],
+                                              tmid)
     nwavecals = len(matching_wavecals)
     if nwavecals != 2:
-        cosutil.printMsg('Expected exactly 2 matching wavecals, got {}'.format(nwavecals))
-        return None
+        cosutil.printError('Expected exactly 2 matching wavecals, got {}'.format(nwavecals))
+        raise RuntimeError("Unable to find 2 bracketing wavecals in association")
     shift1_before = matching_wavecals[0]['shift_dict'][key]
     tbefore = matching_wavecals[0]['time']
     seconds_before = (tbefore - info['expstart']) * SEC_PER_DAY
     shift1_after = matching_wavecals[1]['shift_dict'][key]
     tafter = matching_wavecals[1]['time']
     seconds_after = (tafter - info['expstart']) * SEC_PER_DAY
     cosutil.printMsg("Wavecal before exposure has {}={:.4f} at t={:.4f} ({:.4f}s)".format(key, shift1_before, tbefore, seconds_before))
@@ -4663,14 +4664,64 @@
     early_slope = early_slope / SEC_PER_DAY
     early_intercept = simulated_shift + (info['expstart'] - tsimulated) * early_slope * SEC_PER_DAY
     late_slope = (shift1_after - simulated_shift) / (tafter - tsimulated)
     late_slope = late_slope / SEC_PER_DAY
     late_intercept = simulated_shift + (info['expstart'] - tsimulated) * late_slope * SEC_PER_DAY
     return (seconds_since_exposure_start, early_slope, early_intercept, late_slope, late_intercept)
 
+def getBracketingWavecals(wavecal_info, cenwave, fpoffset, tmid):
+    """For simulated wavecals, return the two wavecals that bracket the
+    exposure in time.
+
+    Parameters
+    ----------
+
+    wavecal_info: List of dictionaries
+        The list of wavecal information dictionaries
+
+    cenwave: int
+        Central wavelength, used to select entries from wavecal_info
+
+    fpoffset: int
+        Used to find one or more elements of wavecal_info
+
+    tmid: float
+        Midpoint in time of the exposure
+
+    Returns
+    -------
+    list
+        List of dictionaries in wavecal_info that match cenwave and
+        fpoffset and bracket the exposure in time
+    """
+
+    subset_wavecal_info = []
+
+    for wc_dict in wavecal_info:
+        if wc_dict["cenwave"] == cenwave and wc_dict["fpoffset"] == fpoffset:
+            subset_wavecal_info.append(wc_dict)
+
+    if len(subset_wavecal_info) == 2:
+        # Only 2 wavecal records match
+        return subset_wavecal_info
+    else:
+        index_of_wavecal_before = 0
+        index_of_wavecal_after = 0
+        smallest_interval_before = -100.0
+        smallest_interval_after = 100.0
+        for index, wc_dict in enumerate(subset_wavecal_info):
+            daysafter = wc_dict["time"] - tmid
+            if daysafter > 0 and daysafter < smallest_interval_after:
+                index_of_wavecal_after = index
+                smallest_interval_after = daysafter
+            if daysafter < 0 and daysafter > smallest_interval_before:
+                index_of_wavecal_before = index
+                smallest_interval_before = daysafter
+        return [subset_wavecal_info[index_of_wavecal_before], subset_wavecal_info[index_of_wavecal_after]]
+
 def computeWavelengths(events, info, reffiles, helcorr="OMIT", hdr=None):
     """Compute wavelengths for a corrtag table.
 
     Parameters
     ----------
     events: astropy.io.fits record array, or None
         The data unit containing the events table.
```

### Comparing `calcos-3.4.4/calcos/trace.py` & `calcos-3.4.6/calcos/trace.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/calcos/wavecal.py` & `calcos-3.4.6/calcos/wavecal.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/calcos/x1d.py` & `calcos-3.4.6/calcos/x1d.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/calcos/xd_search.py` & `calcos-3.4.6/calcos/xd_search.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/calcos.egg-info/PKG-INFO` & `calcos-3.4.6/calcos.egg-info/PKG-INFO`

 * *Files 27% similar despite different names*

```diff
@@ -1,20 +1,25 @@
 Metadata-Version: 2.1
 Name: calcos
-Version: 3.4.4
+Version: 3.4.6
 Summary: Calibration software for COS (Cosmic Origins Spectrograph)
-Home-page: https://github.com/spacetelescope/calcos
 Author: Phil Hodge, Robert Jedrzejewski
-Author-email: help@stsci.edu
-License: BSD
 Classifier: Intended Audience :: Science/Research
 Classifier: License :: OSI Approved :: BSD License
 Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: C
 Classifier: Topic :: Software Development :: Libraries :: Python Modules
 Requires-Python: >=3.8
-Description-Content-Type: text/x-rst
+Description-Content-Type: text/markdown
 Provides-Extra: docs
 Provides-Extra: test
 
-README.md
+# CALCOS
+
+[![Jenkins CI](https://ssbjenkins.stsci.edu/job/STScI/job/calcos/job/master/badge/icon)](https://ssbjenkins.stsci.edu/job/STScI/job/calcos/job/master/)
+
+Calibration software for HST/COS.
+
+Nightly regression test results are available only from within the STScI
+network at this time.
+https://plwishmaster.stsci.edu:8081/job/RT/job/calcos/test_results_analyzer/
```

### Comparing `calcos-3.4.4/calcos.egg-info/SOURCES.txt` & `calcos-3.4.6/calcos.egg-info/SOURCES.txt`

 * *Files 4% similar despite different names*

```diff
@@ -1,17 +1,18 @@
+.flake8
 .gitignore
 .readthedocs.yml
 CODE_OF_CONDUCT.md
 Jenkinsfile
 JenkinsfileRT
 README.md
 pyproject.toml
-setup.cfg
 setup.py
 tox.ini
+.github/CODEOWNERS
 .github/workflows/publish-to-pypi.yml
 .github/workflows/python_testing.yml
 calcos/__init__.py
 calcos/accum.py
 calcos/airglow.py
 calcos/average.py
 calcos/burst.py
@@ -44,14 +45,15 @@
 calcos.egg-info/entry_points.txt
 calcos.egg-info/requires.txt
 calcos.egg-info/top_level.txt
 calcos/pars/calcos.cfg
 calcos/pars/calcos.cfgspc
 docs/Makefile
 docs/make.bat
+docs/rtd_environment.yaml
 docs/source/conf.py
 docs/source/index.rst
 src/ccos.c
 tests/README.md
 tests/conftest.py
 tests/generate_tempfiles.py
 tests/helpers.py
```

### Comparing `calcos-3.4.4/docs/Makefile` & `calcos-3.4.6/docs/Makefile`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/docs/make.bat` & `calcos-3.4.6/docs/make.bat`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/docs/source/conf.py` & `calcos-3.4.6/docs/source/conf.py`

 * *Files 6% similar despite different names*

```diff
@@ -10,14 +10,22 @@
 #
 # All configuration values have a default; values that are commented out
 # serve to show the default.
 
 import os
 import sys
 
+import stsci_rtd_theme
+
+def setup(app):
+    try:
+        app.add_css_file("stsci.css")
+    except AttributeError:
+        app.add_stylesheet("stsci.css")
+
 # If extensions (or modules to document with autodoc) are in another directory,
 # add these directories to sys.path here. If the directory is relative to the
 # documentation root, use os.path.abspath to make it absolute, like shown here.
 sys.path.insert(1, os.path.abspath('.'))
 sys.path.insert(1, os.path.abspath(os.path.join('..')))
 sys.path.insert(1, os.path.abspath(os.path.join('..', '..')))
 
@@ -96,23 +104,30 @@
 #modindex_common_prefix = []
 
 
 # -- Options for HTML output ---------------------------------------------------
 
 # The theme to use for HTML and HTML Help pages.  Major themes that come with
 # Sphinx are currently 'default' and 'sphinxdoc'.
-# html_theme = 'default'
+html_theme = 'stsci_rtd_theme'
 
 # Theme options are theme-specific and customize the look and feel of a theme
 # further.  For a list of options available for each theme, see the
 # documentation.
-#html_theme_options = {}
+html_theme_options = {
+    "collapse_navigation": True
+    # "nosidebar": "false",
+    # "sidebarbgcolor": "#4db8ff",
+    # "sidebartextcolor": "black",
+    # "sidebarlinkcolor": "black",
+    # "headbgcolor": "white",
+}
 
 # Add any paths that contain custom themes here, relative to this directory.
-#html_theme_path = []
+html_theme_path = [stsci_rtd_theme.get_html_theme_path()]
 
 # The name for this set of Sphinx documents.  If None, it defaults to
 # "<project> v<release> documentation".
 #html_title = None
 
 # A shorter title for the navigation bar.  Default is the same as html_title.
 #html_short_title = None
@@ -200,8 +215,10 @@
 #latex_appendices = []
 
 # If false, no module index is generated.
 #latex_use_modindex = True
 
 
 # Example configuration for intersphinx: refer to the Python standard library.
-intersphinx_mapping = {'http://docs.python.org/': None}
+intersphinx_mapping = {
+    'python': ('https://docs.python.org/3/', None),
+}
```

### Comparing `calcos-3.4.4/src/ccos.c` & `calcos-3.4.6/src/ccos.c`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/tests/README.md` & `calcos-3.4.6/tests/README.md`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/tests/conftest.py` & `calcos-3.4.6/tests/conftest.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/tests/generate_tempfiles.py` & `calcos-3.4.6/tests/generate_tempfiles.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/tests/helpers.py` & `calcos-3.4.6/tests/helpers.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/tests/test_airglow.py` & `calcos-3.4.6/tests/test_airglow.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,9 +1,10 @@
 from calcos import airglow
 from generate_tempfiles import create_disptab_file
+import os
 
 
 def test_find_airglow_limits():
     """
     unit test for find_airglow_limits()
     test ran
     - By providing certain values as dict to be used as filter for finding the dispersion
@@ -34,7 +35,10 @@
             limits = airglow.findAirglowLimits(inf, segment, disptab, line)
             if limits is not None:
                 x, y = limits
                 test_pxl.append((x, y))
     # Verify
     for i in range(len(actual_pxl)):
         assert actual_pxl[i] == test_pxl[i]
+
+    # Cleanup
+    os.remove(disptab)
```

### Comparing `calcos-3.4.4/tests/test_average.py` & `calcos-3.4.6/tests/test_average.py`

 * *Files 5% similar despite different names*

```diff
@@ -31,7 +31,12 @@
     out_hdr = fits.open(outfile)
 
     # Verify
     assert os.path.exists(outfile)
     for (i, j, k) in zip(inhdr1[1].header, inhdr2[1].header, out_hdr[1].header):
         assert i == j == k
     np.testing.assert_array_equal((inhdr1[1].data + inhdr1[1].data) / 2, out_hdr[1].data)
+
+    # Cleanup
+    for tempfile in infile:
+        os.remove(tempfile)
+    os.remove(outfile)
```

### Comparing `calcos-3.4.4/tests/test_cosutil.py` & `calcos-3.4.6/tests/test_cosutil.py`

 * *Files 5% similar despite different names*

```diff
@@ -18,37 +18,43 @@
     ofd = generate_fits_file(name)
 
     target_col = 'TIME'
     # Test
     col_exists = True
     # Verify
     assert col_exists == cosutil.findColumn(name, target_col)
+    # Cleanup
+    os.remove(name)
 
 
 def test_get_table():
     # Setup
     # create a test fits file
     name = "getTable.fits"
     ofd = generate_fits_file(name)
     truth = [tuple(ofd[1].data[3])]
     time = ofd[1].data[3][0]
     # Test
     dt = list(cosutil.getTable(name, {'TIME': time}, exactly_one=True))
     # Verify
     np.testing.assert_array_equal(truth, dt)
+    # Cleanup
+    os.remove(name)
 
 
 def test_get_table_exceptions():
     # Raise MissingRowError
     name = "getTable.fits"
     generate_fits_file(name)
     # truth = [tuple(ofd[1].data[3])]
-    t = np.ones(5)  # non-existent values
+    t = 1.0  # non-existent value
     with pytest.raises(MissingRowError):
         cosutil.getTable(name, {'Time': t}, exactly_one=True)
+    # Cleanup
+    os.remove(name)
 
 
 def test_get_col_copy():
     # Setup
     # create a test fits file
     name = "getTable.fits"
     ofd = generate_fits_file(name)
@@ -58,49 +64,58 @@
     # Test (using filename or portion of data)
     test1 = cosutil.getColCopy(name, column=col_name)
     test2 = cosutil.getColCopy(column=col_name, data=portion_of_array)
 
     # Verify
     np.testing.assert_array_equal(truth_values, test1)
     np.testing.assert_array_equal(truth_values, test2)
+    # Cleanup
+    os.remove(name)
 
 
 def test_get_col_copy_exception():
     # raise RuntimeError error
     with pytest.raises(RuntimeError):
         name = "getTable.fits"
         ofd = generate_fits_file(name)
         col_name = 'XCORR'
         portion_of_array = ofd[1].data[:]
         cosutil.getColCopy(filename="Output/getTable.fits", column=col_name, data=portion_of_array)
         cosutil.getColCopy(filename=None, column=col_name, data=None)
+    # Cleanup
+    os.remove(name)
 
 
 def test_get_headers():
     # Setup
     # create a test fits file
     name = "getHeaders.fits"
     ofd = generate_fits_file(name)
     true_hdr = ofd[0].header
 
     # Test
     test_hdr = cosutil.getHeaders(name)
 
     # Verify
     np.testing.assert_array_equal(true_hdr, test_hdr[0])
+    # Cleanup
+    os.remove(name)
 
 
 def test_write_output_events():
     # Setup
     in_file = "outputEvents.fits"
     out_file = "outputEvents_cpy.fits"
     generate_fits_file(in_file)
     actual_lines = 10
     lines = cosutil.writeOutputEvents(in_file, out_file)
     assert actual_lines == lines
+    # Cleanup
+    os.remove(in_file)
+    os.remove(out_file)
 
 
 def test_concat_arrays():
     # setup
     arr1 = np.ones(10, dtype=float)
     arr2 = np.zeros(10, dtype=float)
     actual = np.concatenate((arr1, arr2), axis=0)
@@ -118,14 +133,16 @@
     # Test
     cosutil.updateFilename(before_update_hdr[0].header, filename)
     before_update_hdr.close()
     after_update_hdr = fits.open("update_filename.fits")
     # Verity
     assert filename == after_update_hdr[0].header["filename"]
     after_update_hdr.close()
+    # Cleanup
+    os.remove("update_filename.fits")
 
 
 def test_copy_file():
     # Setup
     infile = "input.fits"
     generate_fits_file(infile)
     outfile = "output.fits"
@@ -133,14 +150,17 @@
     cosutil.copyFile(infile, outfile)
     # Verify
     inf = fits.open(infile)
     out = fits.open(outfile)
     np.testing.assert_array_equal(inf[1].data, out[1].data)
     np.testing.assert_array_equal(inf[2].data, out[2].data)
     np.testing.assert_array_equal(inf[3].data, out[3].data)
+    # Cleanup
+    os.remove("input.fits")
+    os.remove("output.fits")
 
 
 def test_is_product():
     # Setup
     product_file = "my0_product_a.fits"
     raw_file = "my_raw.fits"
     generate_fits_file(product_file)
@@ -150,14 +170,17 @@
     # NOTE:
     # no test to be done here since we're checking the file if its a product or not
     # the return of the function isProduct() is a boolean hence, assert it directly.
 
     # Verify
     assert cosutil.isProduct(product_file)
     assert not cosutil.isProduct(raw_file)
+    # Cleanup
+    os.remove(product_file)
+    os.remove(raw_file)
 
 
 def test_gehrels_lower():
     # Setup
     counts = 4.0
     actual = 1.9090363511659807
     # Test
@@ -238,34 +261,39 @@
     hdu = generate_fits_file("corrtag.fits")
     num_of_rows = 10
     # Test
     # detector parameter is not needed consider removing it
     out_bin_table = cosutil.createCorrtagHDU(num_of_rows, detector="FUV", hdu=hdu[0])
     assert len(out_bin_table.data) == num_of_rows
     assert all(out_bin_table.header) == all(hdu[0].header)
+    # Cleanup
+    os.remove("corrtag.fits")
 
 
 def test_remove_wcs_keywords():
     # Setup
     hdu = generate_fits_file("removeWCS.fits")
-    inhdr = fits.getheader("corrtag.fits", 1)
+    hdu2 = generate_fits_file("corrtag.fits")
+    inhdr = hdu2[1].header
     cd = hdu[1].data.columns
     WCS_keywords = ['TCTYP*',
                     'TCUNI*',
                     'TCRPX*',
                     'TCRVL*',
                     'TCDLT*',
                     ]
     # Test
     newheader = cosutil.remove_WCS_keywords(inhdr, cd)
     # Verify
     for keys in WCS_keywords:
         assert keys not in newheader
         assert len(inhdr[keys]) > 0
-
+    # Cleanup
+    os.remove("removeWCS.fits")
+    os.remove("corrtag.fits")
 
 def test_dummy_gti():
     # Setup
     test_exptime_value = 1.423
     # Test
     dummy_hdu = cosutil.dummyGTI(test_exptime_value)
     # Verify
@@ -276,14 +304,16 @@
 def test_return_gti():
     # Setup
     hdu = generate_fits_file("gti_file.fits")
     # Test
     gti = cosutil.returnGTI("gti_file.fits")
     # Verify
     np.testing.assert_array_equal(list(hdu[2].data), gti)
+    # Cleanup
+    os.remove("gti_file.fits")
 
 
 def test_err_frequentist():
     """
     unit test for err_frequentist(counts)
     - create 3 arrays similar to the test in err_gehrels().
     - find the poisson confidence interval for each array.
@@ -440,15 +470,17 @@
     inhdr = fits.getheader("original.fits", 1)
     outhdr = fits.getheader("copy.fits", 1)
     # Test
     cosutil.copyExptimeKeywords(inhdr, outhdr)
     # Verify
     for header in headers:
         assert inhdr[header] == outhdr[header]
-
+    # Cleanup
+    for tempfile in files:
+        os.remove(tempfile)
 
 def test_copy_voltage_keywords():
     # Setup
     # create two files each for FUV and NUV
     generate_fits_file("originalFUV.fits")
     generate_fits_file("originalNUV.fits")
     generate_fits_file("copyFUV.fits")
@@ -491,15 +523,19 @@
     for header in fuv_headers:
         assert in_FUV_hdr[header] == out_FUV_hdr[header]
     # Test 2
     cosutil.copyVoltageKeywords(in_NUV_hdr, out_NUV_hdr, detectors[1])
     # Verify 2
     for header in nuv_headers:
         assert in_NUV_hdr[header] == out_NUV_hdr[header]
-
+    # Cleanup
+    for tempfile in original:
+        os.remove(tempfile)
+    for tempfile in copy:
+        os.remove(tempfile)
 
 def test_copy_sub_keywords():
     # Setup
     generate_fits_file("subKeywords.fits")
     generate_fits_file("copySubKeywords.fits")
     files = ["subKeywords.fits", "copySubKeywords.fits"]
     headers = ["corner%1dx", "corner%1dy", "size%1dx", "size%1dy"]
@@ -523,14 +559,17 @@
     # Verify
     for header in headers:
         for i in range(8):
             assert inhdr[header % i] == outhdr[header % i]
     cosutil.copySubKeywords(inhdr, outhdr, True)
     # check if nsubarry has been set to 0
     assert inhdr["nsubarry"] == outhdr["nsubarry"]
+    # Cleanup
+    for tempfile in files:
+        os.remove(tempfile)
 
 
 def test_modify_asn_mtyp():
     # Setup
     str1 = "EXP-TESTVALUE"
     str2 = "EXP_SECONDVALUE"
     str3 = "VALUE_WITHOUT_PREFIX"
@@ -560,27 +599,32 @@
     generate_fits_file(original_filename2)
     # Test
     cosutil.renameFile(original_filename1, new_filename1)
     cosutil.renameFile(original_filename2, new_filename2)
     # Verify
     assert os.path.exists(new_filename1)
     assert os.path.exists(new_filename2)
+    # Cleanup
+    os.remove(new_filename1)
+    os.remove(new_filename2)
 
 
 def test_del_corrtag_wcs():
     # Setup
     generate_fits_file("del_corrtagWCS.fits")
     thdr = fits.getheader("del_corrtagWCS.fits", 3)
     tkey = ["TCTYP2", "TCRVL2", "TCRPX2", "TCDLT2", "TCUNI2", "TC2_2", "TC2_3",
             "TCTYP3", "TCRVL3", "TCRPX3", "TCDLT3", "TCUNI3", "TC3_2", "TC3_3"]
     # Test
     thdr = cosutil.delCorrtagWCS(thdr)
     # Verify
     for key in tkey:
         assert key not in thdr
+    # Cleanup
+    os.remove("del_corrtagWCS.fits")
 
 
 def test_set_verbosity():
     # Setup
     verbosity = 5
     # Test
     cosutil.setVerbosity(verbosity)
@@ -850,14 +894,17 @@
     cosutil.findRefFile(ref1, missing1, wrong_f1, bad_ver1)
     cosutil.findRefFile(ref2, missing2, wrong_f2, bad_ver2)
     cosutil.findRefFile(ref3, missing3, wrong_f3, bad_ver3)
     # Verify
     assert actual_missing == missing1
     assert actual_bad_ver == bad_ver2
     assert actual_wrong_ver == wrong_f3
+    # Cleanup
+    os.remove("wrong_file.fits")
+    os.remove("test.fits")
 
 
 def test_cmp_version():
     # Setup
     min_ver = ["1", "1", "1.1", "1.1", "1.1", "1.2", "1.0", "2.7", "2.0", "2.9", "2.12d", "2.13d", "2.13"]
     vcalcos = ["1", "1.1", "1", "1.1", "1.2", "1.1", "1.7", "2.8", "2.13.1", "2.9", "2.13b", "2.13b", "2.13b"]
     calcos_ver = ["1.1", "1", "1", "1.2", "1.1", "1.1", "2.3", "2.8a", "2.13", "2.13.1", "2.12a", "2.13a", "2.13c"]
@@ -887,14 +934,16 @@
     sys.stdout = sys.__stdout__
     print(capture_msg.getvalue())
 
     # Verify
     assert pedgr1 == "OK"
     assert pedgr2 == "DUMMY"
     assert err_msg == capture_msg.getvalue()
+    # Cleanup
+    os.remove(filename)
 
 
 def test_get_aperture_keyword():
     # Setup
     generate_fits_file("aperture_test.fits")
     # condition 1
     fits.setval("aperture_test.fits", "aperture", value="PSA-FUV", ext=0)
@@ -938,28 +987,32 @@
     # Verify
     assert rtn1 == rtn_value1
     assert rtn2 == rtn_value2
     assert rtn3 == rtn_value3
     assert rtn4 == rtn_value4
     assert rtn5 == rtn_value5
     assert rtn6 == rtn_value6
+    # Cleanup
+    os.remove("aperture_test.fits")
 
 
 def test_write_version_to_trailer():
     capture_msg = io.StringIO()
     sys.stdout = capture_msg
     generate_fits_file("dummy_file.fits")
     ascii_file = open("ascii.txt", mode="w")
     cosutil.fd_trl = ascii_file
     cosutil.CALCOS_VERSION = '3.1.0'
     cosutil.writeVersionToTrailer()
     sys.stdout = sys.__stdout__
     assert ascii_file == cosutil.fd_trl
     assert capture_msg.getvalue() == ''
-
+    # Cleanup
+    os.remove("ascii.txt")
+    os.remove("dummy_file.fits")
 
 def test_get_switch():
     # Setup
     generate_fits_file("switch.fits")
     phdr = fits.getheader("switch.fits", ext=0)
     keyword = "statflag"
     # Test
@@ -967,46 +1020,55 @@
     phdr.set('STATFLAG', False, 'Calculate statistics')
     switch2 = cosutil.getSwitch(phdr, keyword)
     switch3 = cosutil.getSwitch(phdr, "none")
     # Verify
     assert switch == 'PERFORM'
     assert switch2 == 'OMIT'
     assert switch3 == 'N/A'
+    # Cleanup
+    os.remove("switch.fits")
 
 
 def test_temp_pulse_height_range():
     generate_fits_file("pulseHeightRef.fits")
     true_pha_value = 4
     fits.setval("pulseHeightRef.fits", "pharange", value=true_pha_value, ext=0)
     fits.getheader("pulseHeightRef.fits", ext=0)
     pha_value = cosutil.tempPulseHeightRange('pulseHeightRef.fits')
     assert true_pha_value == pha_value
+    # Cleanup
+    os.remove("pulseHeightRef.fits")
 
 
 def test_get_pulse_height_range():
+    generate_fits_file("pulseHeightRef.fits")
     fits.setval("pulseHeightRef.fits", "phalowrA", value=7, ext=0)
     fits.setval("pulseHeightRef.fits", "phaupprA", value=10, ext=0)
     hdu = fits.getheader("pulseHeightRef.fits", ext=0)
     seg = ['FUVA', 'FUVB']
     actual = [' 7_10', None]
     for s, a in zip(seg, actual):
         test_str = cosutil.getPulseHeightRange(hdu, s)
         assert a == test_str
+    # Cleanup
+    os.remove("pulseHeightRef.fits")
 
 
 def test_time_at_midpoint():
     # Setup
     generate_fits_file("test_timeAtMidpoint.fits")
     hdr = fits.getheader("test_timeAtMidpoint.fits", ext=1)
     info = {'expstart': hdr['TCRPX7'], 'expend': hdr['TCRVL7']}
     average = 4776.314586556611
     # Test
     test_average = cosutil.timeAtMidpoint(info)
     # Verify
     assert average == test_average
+    # Cleanup
+    os.remove("test_timeAtMidpoint.fits")
 
 
 def test_timeline_times():
     # Setup
     first_time = np.array([2.5], dtype=np.float32)
     last_time = np.array([3.8], dtype=np.float32)
     actual_values = [2.5, 3.5, 4.5, 5.5, 6.5, 7.5, 8.5, 9.5, 10.5]
@@ -1049,7 +1111,9 @@
     val3 = phdr.values()
     val4 = reffiles["flt_hdr"]
     # Test
     cosutil.overrideKeywords(phdr, hdr, info, switches, reffiles)
     phdr = fits.getheader("overridekeywords.fits", ext=0)
     # Verify
     assert val1 == phdr["statflag"]
+    # Cleanup
+    os.remove("overridekeywords.fits")
```

### Comparing `calcos-3.4.4/tests/test_dark_fuva.py` & `calcos-3.4.6/tests/test_dark_fuva.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/tests/test_dark_fuvb.py` & `calcos-3.4.6/tests/test_dark_fuvb.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/tests/test_dark_nuv.py` & `calcos-3.4.6/tests/test_dark_nuv.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/tests/test_extract.py` & `calcos-3.4.6/tests/test_extract.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,7 +1,9 @@
+import os
+
 from calcos.x1d import *
 import numpy as np
 from generate_tempfiles import generate_fits_file
 
 def test_get_columns():
     """
     Test if the function is returning the right column fields
@@ -25,14 +27,16 @@
     (xf, yf, dq2, epsilon2) = extract.getColumns(test_data, detector)
 
     # Verify
     np.testing.assert_array_equal(xfull, xf)
     np.testing.assert_array_equal(yfull, yf)
     np.testing.assert_array_equal(dq, dq2)
     np.testing.assert_array_equal(epsilon, epsilon2)
+    # Cleanup
+    os.remove("lbgu17qnq_corrtag_a.fits")
 
 
 def test_remove_unwanted_column():
     """
     Old column length should be equal to new column length + amount of the removed columns
     """
     # Setup
@@ -48,14 +52,16 @@
     # Verify
     deleted_cols = set(cols) - set(new_cols)
     deleted_cols = np.array(list(deleted_cols))
     temp_cols = [d.name for d in deleted_cols]
     deleted_cols = deleted_cols[np.argsort(temp_cols)]
     # assert target_cols[0] == deleted_cols[0].name
     # assert target_cols[1] == deleted_cols[1].name
+    # Cleanup
+    os.remove('lbgu17qnq_lampflash.fits')
 
 
 def test_next_power_of_two():
     """
     Test the next_power_of_two
     @return: none
     """
@@ -73,7 +79,10 @@
     comment = "This comment is generated by a unit-test."
 
     # Exercise
     test_table = extract.add_column_comment(ofd, 'TIME', comment)
 
     # Verify
     assert comment == test_table[1].header.comments['TTYPE1']
+    # Cleanup
+    os.remove('myFitsFile.fits')
+
```

### Comparing `calcos-3.4.4/tests/test_flat_fuva.py` & `calcos-3.4.6/tests/test_flat_fuva.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/tests/test_flat_nuv.py` & `calcos-3.4.6/tests/test_flat_nuv.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/tests/test_flat_relmvreq.py` & `calcos-3.4.6/tests/test_flat_relmvreq.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/tests/test_fuv_timetag.py` & `calcos-3.4.6/tests/test_fuv_timetag.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/tests/test_shiftfile.py` & `calcos-3.4.6/tests/test_shiftfile.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,12 +1,13 @@
-from calcos import shiftfile
+import os
 
+from calcos import shiftfile
 
-def test_shift_file():  # Tests the initialized variables
-    # Setup
+def create_shift_file(filename):
+    # Create the shift file for use in tests
     shift_file = "shift_file.txt"
     with open(shift_file, "w") as file:
         file.write("#dataset\tfpoffset\tflash #\tstripe\tshift1\tshift2\n")
         for i in range(10):
             if i % 3 == 0:
                 file.write("{}\t{}\t{}\t{}\t{}\t{}\n".format("abc123def", "any", "1", "NUVA", "45.234435", "7"))
             elif i % 5 == 0:
@@ -14,23 +15,31 @@
             elif i % 6 == 0 or i % 8 == 0:
                 file.write("{}\t{}\t{}\t{}\t{}\t{}\n".format("ghi456jkl", "any", "2", "FUVA", "19.543453", "5"))
             elif i == 9:
                 file.write("{}\t{}\t{}\t{}\t{}\t{}\n".format("mno789pqr", "any", "2", "FUVB", "52.723453", "6"))
             else:
                 file.write("{}\t{}\t{}\t{}\t{}\t{}\n".format("mno789pqr", "any", "1", "NUVC", "-34.543453", "7"))
 
+    return
+
+def test_shift_file():
+    shift_file = "shift_file.txt"
+    create_shift_file(shift_file)
     # Test
     ob = shiftfile.ShiftFile(shift_file, 'abc123def', 'any')
     # Verify
     assert len(ob.user_shift_dict) > 0
+    # Cleanup
+    os.remove(shift_file)
 
 
 def test_get_shifts():
     # Setup
     shift_file = "shift_file.txt"
+    create_shift_file(shift_file)
     ob1 = shiftfile.ShiftFile(shift_file, 'ghi456jkl', 'any')
     ob2 = shiftfile.ShiftFile(shift_file, 'abc123def', 'any')
     keys = [('any', 'nuva'), ('any', 'nuvb'), (2, 'nuvc'), ('any', 'any'), ('any', 'fuva'), ('any', 'fuvb')]
     expected_values1 = [((None, None), 0), ((34.543453, 7.0), 1), ((None, None), 0), ((19.543453, 5.0), 2), ((19.543453, 5.0), 1), ((None, None), 0)]
     expected_values2 = [((45.234435, 7.0), 1), ((None, None), 0), ((None, None), 0), ((45.234435, 7.0), 1), ((None, None), 0), ((None, None), 0)]
     # Test
     test_values1 = []
@@ -39,7 +48,10 @@
         test_values1.append(shiftfile.ShiftFile.getShifts(ob1, key))
     for key in keys:
         test_values2.append(shiftfile.ShiftFile.getShifts(ob2, key))
     # Verify
     for i in range(len(expected_values1)):
         assert expected_values1[i] == test_values1[i]
         assert expected_values2[i] == test_values2[i]
+    # Cleanup
+    os.remove(shift_file)
+
```

### Comparing `calcos-3.4.4/tests/test_wavecal_fuva_f140l.py` & `calcos-3.4.6/tests/test_wavecal_fuva_f140l.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/tests/test_wavecal_fuva_g130m.py` & `calcos-3.4.6/tests/test_wavecal_fuva_g130m.py`

 * *Files identical despite different names*

### Comparing `calcos-3.4.4/tox.ini` & `calcos-3.4.6/tox.ini`

 * *Files identical despite different names*


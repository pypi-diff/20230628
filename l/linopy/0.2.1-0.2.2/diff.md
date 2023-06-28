# Comparing `tmp/linopy-0.2.1.tar.gz` & `tmp/linopy-0.2.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "linopy-0.2.1.tar", last modified: Mon Jun 26 14:27:42 2023, max compression
+gzip compressed data, was "linopy-0.2.2.tar", last modified: Wed Jun 28 14:01:38 2023, max compression
```

## Comparing `linopy-0.2.1.tar` & `linopy-0.2.2.tar`

### file list

```diff
@@ -1,148 +1,157 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:27:42.676888 linopy-0.2.1/
--rw-r--r--   0 runner    (1001) docker     (123)   180224 2023-06-26 14:27:32.000000 linopy-0.2.1/.coverage
--rw-r--r--   0 runner    (1001) docker     (123)       67 2023-06-26 14:27:32.000000 linopy-0.2.1/.coveragerc
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:27:42.652886 linopy-0.2.1/.github/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:27:42.656886 linopy-0.2.1/.github/workflows/
--rw-r--r--   0 runner    (1001) docker     (123)     2230 2023-06-26 14:27:32.000000 linopy-0.2.1/.github/workflows/CI.yaml
--rw-r--r--   0 runner    (1001) docker     (123)      837 2023-06-26 14:27:32.000000 linopy-0.2.1/.github/workflows/deploy.yml
--rw-r--r--   0 runner    (1001) docker     (123)      399 2023-06-26 14:27:32.000000 linopy-0.2.1/.gitignore
--rw-r--r--   0 runner    (1001) docker     (123)     1228 2023-06-26 14:27:32.000000 linopy-0.2.1/.pre-commit-config.yaml
--rw-r--r--   0 runner    (1001) docker     (123)      119 2023-06-26 14:27:32.000000 linopy-0.2.1/.readthedocs.yaml
--rw-r--r--   0 runner    (1001) docker     (123)      137 2023-06-26 14:27:32.000000 linopy-0.2.1/CONTRIBUTING.md
--rw-r--r--   0 runner    (1001) docker     (123)     1075 2023-06-26 14:27:32.000000 linopy-0.2.1/LICENSE.txt
--rw-r--r--   0 runner    (1001) docker     (123)     3480 2023-06-26 14:27:42.676888 linopy-0.2.1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2786 2023-06-26 14:27:32.000000 linopy-0.2.1/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:27:42.660887 linopy-0.2.1/benchmark/
--rw-r--r--   0 runner    (1001) docker     (123)     2857 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/README.md
--rw-r--r--   0 runner    (1001) docker     (123)     7509 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/Snakefile
--rw-r--r--   0 runner    (1001) docker     (123)    21144 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/benchmark-absolute.pdf
--rw-r--r--   0 runner    (1001) docker     (123)   188981 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/benchmark-absolute.png
--rw-r--r--   0 runner    (1001) docker     (123)    20512 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/benchmark-overhead.pdf
--rw-r--r--   0 runner    (1001) docker     (123)   179946 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/benchmark-overhead.png
--rw-r--r--   0 runner    (1001) docker     (123)    18784 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/benchmark_resource-absolute.pdf
--rw-r--r--   0 runner    (1001) docker     (123)   149975 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/benchmark_resource-absolute.png
--rw-r--r--   0 runner    (1001) docker     (123)    18038 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/benchmark_resource-overhead.pdf
--rw-r--r--   0 runner    (1001) docker     (123)   132957 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/benchmark_resource-overhead.png
--rw-r--r--   0 runner    (1001) docker     (123)      339 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/config.yaml
--rw-r--r--   0 runner    (1001) docker     (123)     7011 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/environment.fixed.yaml
--rw-r--r--   0 runner    (1001) docker     (123)      249 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/environment.yaml
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:27:42.660887 linopy-0.2.1/benchmark/notebooks/
--rw-r--r--   0 runner    (1001) docker     (123)     3362 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/notebooks/plot-benchmarks.py.ipynb
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:27:42.660887 linopy-0.2.1/benchmark/scripts/
--rwxr-xr-x   0 runner    (1001) docker     (123)     1450 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/benchmark_cvxpy.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     1537 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/benchmark_gurobipy.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     1541 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/benchmark_jump.jl
--rwxr-xr-x   0 runner    (1001) docker     (123)     1458 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/benchmark_linopy.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     2007 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/benchmark_ortools.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     1796 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/benchmark_pulp.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     2043 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/benchmark_pyomo.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:27:42.660887 linopy-0.2.1/benchmark/scripts/benchmarks-pypsa-eur/
--rw-r--r--   0 runner    (1001) docker     (123)      451 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/benchmarks-pypsa-eur/benchmark-linopy.py
--rw-r--r--   0 runner    (1001) docker     (123)      503 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/benchmarks-pypsa-eur/benchmark-pyomo.py
--rw-r--r--   0 runner    (1001) docker     (123)      477 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/benchmarks-pypsa-eur/benchmark-pypsa-linopf.py
--rw-r--r--   0 runner    (1001) docker     (123)      247 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/benchmarks-pypsa-eur/common.py
--rw-r--r--   0 runner    (1001) docker     (123)      708 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/benchmarks-pypsa-eur/plot-benchmarks.py
--rwxr-xr-x   0 runner    (1001) docker     (123)      469 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/common.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     1050 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/concat-benchmarks.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:27:42.660887 linopy-0.2.1/benchmark/scripts/leftovers/
--rw-r--r--   0 runner    (1001) docker     (123)      698 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/leftovers/benchmark-linopy.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:27:42.664887 linopy-0.2.1/benchmark/scripts/leftovers/benchmarks-pypsa-eur/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:27:42.664887 linopy-0.2.1/benchmark/scripts/leftovers/benchmarks-pypsa-eur/__pycache__/
--rw-r--r--   0 runner    (1001) docker     (123)      742 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/leftovers/benchmarks-pypsa-eur/__pycache__/benchmark-linopy.cpython-310.pyc
--rw-r--r--   0 runner    (1001) docker     (123)      777 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/leftovers/benchmarks-pypsa-eur/__pycache__/benchmark-pyomo.cpython-310.pyc
--rw-r--r--   0 runner    (1001) docker     (123)      764 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/leftovers/benchmarks-pypsa-eur/__pycache__/benchmark-pypsa-linopf.cpython-310.pyc
--rw-r--r--   0 runner    (1001) docker     (123)      380 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/leftovers/benchmarks-pypsa-eur/__pycache__/common.cpython-39.pyc
--rw-r--r--   0 runner    (1001) docker     (123)      909 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/leftovers/benchmarks-pypsa-eur/__pycache__/plot-benchmarks.cpython-310.pyc
--rw-r--r--   0 runner    (1001) docker     (123)    18477 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/leftovers/benchmarks-pypsa-eur/benchmark-linopy-pypsa-eur.dat
--rw-r--r--   0 runner    (1001) docker     (123)      451 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/leftovers/benchmarks-pypsa-eur/benchmark-linopy.py
--rw-r--r--   0 runner    (1001) docker     (123)   103087 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/leftovers/benchmarks-pypsa-eur/benchmark-pyomo-pypsa-eur.dat
--rw-r--r--   0 runner    (1001) docker     (123)      503 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/leftovers/benchmarks-pypsa-eur/benchmark-pyomo.py
--rw-r--r--   0 runner    (1001) docker     (123)    26681 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/leftovers/benchmarks-pypsa-eur/benchmark-pypsa-eur-with-pypsa.pdf
--rw-r--r--   0 runner    (1001) docker     (123)    18332 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/leftovers/benchmarks-pypsa-eur/benchmark-pypsa-eur.pdf
--rw-r--r--   0 runner    (1001) docker     (123)      477 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/leftovers/benchmarks-pypsa-eur/benchmark-pypsa-linopf.py
--rw-r--r--   0 runner    (1001) docker     (123)   381819 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/leftovers/benchmarks-pypsa-eur/benchmark-pypsa_linopf-pypsa-eur.dat
--rw-r--r--   0 runner    (1001) docker     (123)      247 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/leftovers/benchmarks-pypsa-eur/common.py
--rw-r--r--   0 runner    (1001) docker     (123)      708 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/leftovers/benchmarks-pypsa-eur/plot-benchmarks.py
--rw-r--r--   0 runner    (1001) docker     (123)     1471 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/leftovers/common.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     1392 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/merge-benchmarks.py
--rw-r--r--   0 runner    (1001) docker     (123)      613 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/plot-benchmarks.py
--rwxr-xr-x   0 runner    (1001) docker     (123)      291 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/run-cvxpy.py
--rwxr-xr-x   0 runner    (1001) docker     (123)      291 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/run-gurobipy.py
--rwxr-xr-x   0 runner    (1001) docker     (123)      399 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/run-linopy.py
--rwxr-xr-x   0 runner    (1001) docker     (123)      290 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/run-ortools.py
--rwxr-xr-x   0 runner    (1001) docker     (123)      287 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/run-pulp.py
--rwxr-xr-x   0 runner    (1001) docker     (123)      399 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/run-pyomo.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     1023 2023-06-26 14:27:32.000000 linopy-0.2.1/benchmark/scripts/write-lp-file.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:27:42.668887 linopy-0.2.1/doc/
--rw-r--r--   0 runner    (1001) docker     (123)      634 2023-06-26 14:27:32.000000 linopy-0.2.1/doc/Makefile
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:27:42.668887 linopy-0.2.1/doc/_static/
--rw-r--r--   0 runner    (1001) docker     (123)     1393 2023-06-26 14:27:32.000000 linopy-0.2.1/doc/_static/theme_overrides.css
--rw-r--r--   0 runner    (1001) docker     (123)     3647 2023-06-26 14:27:32.000000 linopy-0.2.1/doc/api.rst
--rw-r--r--   0 runner    (1001) docker     (123)    57997 2023-06-26 14:27:32.000000 linopy-0.2.1/doc/benchmark.png
--rw-r--r--   0 runner    (1001) docker     (123)     1087 2023-06-26 14:27:32.000000 linopy-0.2.1/doc/benchmark.rst
--rw-r--r--   0 runner    (1001) docker     (123)     4054 2023-06-26 14:27:32.000000 linopy-0.2.1/doc/conf.py
--rw-r--r--   0 runner    (1001) docker     (123)     2964 2023-06-26 14:27:32.000000 linopy-0.2.1/doc/contributing.rst
--rw-r--r--   0 runner    (1001) docker     (123)       51 2023-06-26 14:27:32.000000 linopy-0.2.1/doc/create-a-model.nblink
--rw-r--r--   0 runner    (1001) docker     (123)       57 2023-06-26 14:27:32.000000 linopy-0.2.1/doc/creating-constraints.nblink
--rw-r--r--   0 runner    (1001) docker     (123)       55 2023-06-26 14:27:32.000000 linopy-0.2.1/doc/creating-variables.nblink
--rw-r--r--   0 runner    (1001) docker     (123)     3334 2023-06-26 14:27:32.000000 linopy-0.2.1/doc/index.rst
--rw-r--r--   0 runner    (1001) docker     (123)    80342 2023-06-26 14:27:32.000000 linopy-0.2.1/doc/logo.pdf
--rw-r--r--   0 runner    (1001) docker     (123)   132092 2023-06-26 14:27:32.000000 linopy-0.2.1/doc/logo.png
--rw-r--r--   0 runner    (1001) docker     (123)     1135 2023-06-26 14:27:32.000000 linopy-0.2.1/doc/logo.py
--rw-r--r--   0 runner    (1001) docker     (123)      795 2023-06-26 14:27:32.000000 linopy-0.2.1/doc/make.bat
--rw-r--r--   0 runner    (1001) docker     (123)       56 2023-06-26 14:27:32.000000 linopy-0.2.1/doc/manipulating-models.nblink
--rw-r--r--   0 runner    (1001) docker     (123)       57 2023-06-26 14:27:32.000000 linopy-0.2.1/doc/migrating-from-pyomo.nblink
--rw-r--r--   0 runner    (1001) docker     (123)    19816 2023-06-26 14:27:32.000000 linopy-0.2.1/doc/release_notes.rst
--rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-26 14:27:32.000000 linopy-0.2.1/doc/solve-on-remote.nblink
--rw-r--r--   0 runner    (1001) docker     (123)     1579 2023-06-26 14:27:32.000000 linopy-0.2.1/doc/solvers.rst
--rw-r--r--   0 runner    (1001) docker     (123)     2415 2023-06-26 14:27:32.000000 linopy-0.2.1/doc/syntax.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:27:42.668887 linopy-0.2.1/examples/
--rw-r--r--   0 runner    (1001) docker     (123)    10175 2023-06-26 14:27:32.000000 linopy-0.2.1/examples/create-a-model.ipynb
--rw-r--r--   0 runner    (1001) docker     (123)     8419 2023-06-26 14:27:32.000000 linopy-0.2.1/examples/creating-constraints.ipynb
--rw-r--r--   0 runner    (1001) docker     (123)    10367 2023-06-26 14:27:32.000000 linopy-0.2.1/examples/creating-variables.ipynb
--rw-r--r--   0 runner    (1001) docker     (123)     7586 2023-06-26 14:27:32.000000 linopy-0.2.1/examples/manipulating-models.ipynb
--rw-r--r--   0 runner    (1001) docker     (123)      705 2023-06-26 14:27:32.000000 linopy-0.2.1/examples/migrating-from-pyomo.ipynb
--rw-r--r--   0 runner    (1001) docker     (123)    27151 2023-06-26 14:27:32.000000 linopy-0.2.1/examples/solve-on-remote.ipynb
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:27:42.672888 linopy-0.2.1/linopy/
--rw-r--r--   0 runner    (1001) docker     (123)      741 2023-06-26 14:27:32.000000 linopy-0.2.1/linopy/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    11018 2023-06-26 14:27:32.000000 linopy-0.2.1/linopy/common.py
--rw-r--r--   0 runner    (1001) docker     (123)     1324 2023-06-26 14:27:32.000000 linopy-0.2.1/linopy/config.py
--rw-r--r--   0 runner    (1001) docker     (123)     6148 2023-06-26 14:27:32.000000 linopy-0.2.1/linopy/constants.py
--rw-r--r--   0 runner    (1001) docker     (123)    29733 2023-06-26 14:27:32.000000 linopy-0.2.1/linopy/constraints.py
--rw-r--r--   0 runner    (1001) docker     (123)    47153 2023-06-26 14:27:32.000000 linopy-0.2.1/linopy/expressions.py
--rw-r--r--   0 runner    (1001) docker     (123)    18671 2023-06-26 14:27:32.000000 linopy-0.2.1/linopy/io.py
--rw-r--r--   0 runner    (1001) docker     (123)     3693 2023-06-26 14:27:32.000000 linopy-0.2.1/linopy/matrices.py
--rw-r--r--   0 runner    (1001) docker     (123)    37414 2023-06-26 14:27:32.000000 linopy-0.2.1/linopy/model.py
--rw-r--r--   0 runner    (1001) docker     (123)      731 2023-06-26 14:27:32.000000 linopy-0.2.1/linopy/monkey_patch_xarray.py
--rw-r--r--   0 runner    (1001) docker     (123)     8138 2023-06-26 14:27:32.000000 linopy-0.2.1/linopy/remote.py
--rw-r--r--   0 runner    (1001) docker     (123)    20119 2023-06-26 14:27:32.000000 linopy-0.2.1/linopy/solvers.py
--rw-r--r--   0 runner    (1001) docker     (123)      578 2023-06-26 14:27:32.000000 linopy-0.2.1/linopy/testing.py
--rw-r--r--   0 runner    (1001) docker     (123)    36288 2023-06-26 14:27:32.000000 linopy-0.2.1/linopy/variables.py
--rw-r--r--   0 runner    (1001) docker     (123)      160 2023-06-26 14:27:42.000000 linopy-0.2.1/linopy/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:27:42.672888 linopy-0.2.1/linopy.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     3480 2023-06-26 14:27:42.000000 linopy-0.2.1/linopy.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     4364 2023-06-26 14:27:42.000000 linopy-0.2.1/linopy.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-26 14:27:42.000000 linopy-0.2.1/linopy.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)      273 2023-06-26 14:27:42.000000 linopy-0.2.1/linopy.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)        7 2023-06-26 14:27:42.000000 linopy-0.2.1/linopy.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)      131 2023-06-26 14:27:32.000000 linopy-0.2.1/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-26 14:27:42.676888 linopy-0.2.1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     1849 2023-06-26 14:27:32.000000 linopy-0.2.1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:27:42.676888 linopy-0.2.1/test/
--rw-r--r--   0 runner    (1001) docker     (123)     5066 2023-06-26 14:27:32.000000 linopy-0.2.1/test/test_common.py
--rw-r--r--   0 runner    (1001) docker     (123)    12044 2023-06-26 14:27:32.000000 linopy-0.2.1/test/test_constraint.py
--rw-r--r--   0 runner    (1001) docker     (123)     4721 2023-06-26 14:27:32.000000 linopy-0.2.1/test/test_constraints.py
--rw-r--r--   0 runner    (1001) docker     (123)     1709 2023-06-26 14:27:32.000000 linopy-0.2.1/test/test_inconsistency_checks.py
--rw-r--r--   0 runner    (1001) docker     (123)     2644 2023-06-26 14:27:32.000000 linopy-0.2.1/test/test_io.py
--rw-r--r--   0 runner    (1001) docker     (123)    17139 2023-06-26 14:27:32.000000 linopy-0.2.1/test/test_linear_expression.py
--rw-r--r--   0 runner    (1001) docker     (123)     1919 2023-06-26 14:27:32.000000 linopy-0.2.1/test/test_matrices.py
--rw-r--r--   0 runner    (1001) docker     (123)     2698 2023-06-26 14:27:32.000000 linopy-0.2.1/test/test_model.py
--rw-r--r--   0 runner    (1001) docker     (123)    15044 2023-06-26 14:27:32.000000 linopy-0.2.1/test/test_optimization.py
--rw-r--r--   0 runner    (1001) docker     (123)     1466 2023-06-26 14:27:32.000000 linopy-0.2.1/test/test_options.py
--rw-r--r--   0 runner    (1001) docker     (123)     4348 2023-06-26 14:27:32.000000 linopy-0.2.1/test/test_quadratic_expression.py
--rw-r--r--   0 runner    (1001) docker     (123)     4054 2023-06-26 14:27:32.000000 linopy-0.2.1/test/test_repr.py
--rw-r--r--   0 runner    (1001) docker     (123)      951 2023-06-26 14:27:32.000000 linopy-0.2.1/test/test_scalar_constraint.py
--rw-r--r--   0 runner    (1001) docker     (123)     2086 2023-06-26 14:27:32.000000 linopy-0.2.1/test/test_scalar_linear_expression.py
--rw-r--r--   0 runner    (1001) docker     (123)     4529 2023-06-26 14:27:32.000000 linopy-0.2.1/test/test_variable.py
--rw-r--r--   0 runner    (1001) docker     (123)     7468 2023-06-26 14:27:32.000000 linopy-0.2.1/test/test_variable_assignment.py
--rw-r--r--   0 runner    (1001) docker     (123)     2313 2023-06-26 14:27:32.000000 linopy-0.2.1/test/test_variables.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:01:38.903917 linopy-0.2.2/
+-rw-r--r--   0 runner    (1001) docker     (123)   180224 2023-06-28 14:01:29.000000 linopy-0.2.2/.coverage
+-rw-r--r--   0 runner    (1001) docker     (123)       67 2023-06-28 14:01:29.000000 linopy-0.2.2/.coveragerc
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:01:38.883917 linopy-0.2.2/.github/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:01:38.887917 linopy-0.2.2/.github/workflows/
+-rw-r--r--   0 runner    (1001) docker     (123)     2230 2023-06-28 14:01:29.000000 linopy-0.2.2/.github/workflows/CI.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)      837 2023-06-28 14:01:29.000000 linopy-0.2.2/.github/workflows/deploy.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      399 2023-06-28 14:01:29.000000 linopy-0.2.2/.gitignore
+-rw-r--r--   0 runner    (1001) docker     (123)     1228 2023-06-28 14:01:29.000000 linopy-0.2.2/.pre-commit-config.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)      159 2023-06-28 14:01:29.000000 linopy-0.2.2/.readthedocs.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)      137 2023-06-28 14:01:29.000000 linopy-0.2.2/CONTRIBUTING.md
+-rw-r--r--   0 runner    (1001) docker     (123)     1075 2023-06-28 14:01:29.000000 linopy-0.2.2/LICENSE.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     3480 2023-06-28 14:01:38.903917 linopy-0.2.2/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2786 2023-06-28 14:01:29.000000 linopy-0.2.2/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:01:38.887917 linopy-0.2.2/benchmark/
+-rw-r--r--   0 runner    (1001) docker     (123)     2857 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)     7509 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/Snakefile
+-rw-r--r--   0 runner    (1001) docker     (123)    21144 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/benchmark-absolute.pdf
+-rw-r--r--   0 runner    (1001) docker     (123)   188981 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/benchmark-absolute.png
+-rw-r--r--   0 runner    (1001) docker     (123)    20512 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/benchmark-overhead.pdf
+-rw-r--r--   0 runner    (1001) docker     (123)   179946 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/benchmark-overhead.png
+-rw-r--r--   0 runner    (1001) docker     (123)    18784 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/benchmark_resource-absolute.pdf
+-rw-r--r--   0 runner    (1001) docker     (123)   149975 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/benchmark_resource-absolute.png
+-rw-r--r--   0 runner    (1001) docker     (123)    18038 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/benchmark_resource-overhead.pdf
+-rw-r--r--   0 runner    (1001) docker     (123)   132957 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/benchmark_resource-overhead.png
+-rw-r--r--   0 runner    (1001) docker     (123)      339 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/config.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)     7011 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/environment.fixed.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)      249 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/environment.yaml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:01:38.887917 linopy-0.2.2/benchmark/notebooks/
+-rw-r--r--   0 runner    (1001) docker     (123)     3362 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/notebooks/plot-benchmarks.py.ipynb
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:01:38.891918 linopy-0.2.2/benchmark/scripts/
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1450 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/benchmark_cvxpy.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1537 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/benchmark_gurobipy.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1541 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/benchmark_jump.jl
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1458 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/benchmark_linopy.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     2007 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/benchmark_ortools.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1796 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/benchmark_pulp.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     2043 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/benchmark_pyomo.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:01:38.891918 linopy-0.2.2/benchmark/scripts/benchmarks-pypsa-eur/
+-rw-r--r--   0 runner    (1001) docker     (123)      451 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/benchmarks-pypsa-eur/benchmark-linopy.py
+-rw-r--r--   0 runner    (1001) docker     (123)      503 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/benchmarks-pypsa-eur/benchmark-pyomo.py
+-rw-r--r--   0 runner    (1001) docker     (123)      477 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/benchmarks-pypsa-eur/benchmark-pypsa-linopf.py
+-rw-r--r--   0 runner    (1001) docker     (123)      247 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/benchmarks-pypsa-eur/common.py
+-rw-r--r--   0 runner    (1001) docker     (123)      708 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/benchmarks-pypsa-eur/plot-benchmarks.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)      469 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/common.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1050 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/concat-benchmarks.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:01:38.891918 linopy-0.2.2/benchmark/scripts/leftovers/
+-rw-r--r--   0 runner    (1001) docker     (123)      698 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/leftovers/benchmark-linopy.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:01:38.895918 linopy-0.2.2/benchmark/scripts/leftovers/benchmarks-pypsa-eur/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:01:38.895918 linopy-0.2.2/benchmark/scripts/leftovers/benchmarks-pypsa-eur/__pycache__/
+-rw-r--r--   0 runner    (1001) docker     (123)      742 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/leftovers/benchmarks-pypsa-eur/__pycache__/benchmark-linopy.cpython-310.pyc
+-rw-r--r--   0 runner    (1001) docker     (123)      777 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/leftovers/benchmarks-pypsa-eur/__pycache__/benchmark-pyomo.cpython-310.pyc
+-rw-r--r--   0 runner    (1001) docker     (123)      764 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/leftovers/benchmarks-pypsa-eur/__pycache__/benchmark-pypsa-linopf.cpython-310.pyc
+-rw-r--r--   0 runner    (1001) docker     (123)      380 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/leftovers/benchmarks-pypsa-eur/__pycache__/common.cpython-39.pyc
+-rw-r--r--   0 runner    (1001) docker     (123)      909 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/leftovers/benchmarks-pypsa-eur/__pycache__/plot-benchmarks.cpython-310.pyc
+-rw-r--r--   0 runner    (1001) docker     (123)    18477 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/leftovers/benchmarks-pypsa-eur/benchmark-linopy-pypsa-eur.dat
+-rw-r--r--   0 runner    (1001) docker     (123)      451 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/leftovers/benchmarks-pypsa-eur/benchmark-linopy.py
+-rw-r--r--   0 runner    (1001) docker     (123)   103087 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/leftovers/benchmarks-pypsa-eur/benchmark-pyomo-pypsa-eur.dat
+-rw-r--r--   0 runner    (1001) docker     (123)      503 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/leftovers/benchmarks-pypsa-eur/benchmark-pyomo.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26681 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/leftovers/benchmarks-pypsa-eur/benchmark-pypsa-eur-with-pypsa.pdf
+-rw-r--r--   0 runner    (1001) docker     (123)    18332 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/leftovers/benchmarks-pypsa-eur/benchmark-pypsa-eur.pdf
+-rw-r--r--   0 runner    (1001) docker     (123)      477 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/leftovers/benchmarks-pypsa-eur/benchmark-pypsa-linopf.py
+-rw-r--r--   0 runner    (1001) docker     (123)   381819 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/leftovers/benchmarks-pypsa-eur/benchmark-pypsa_linopf-pypsa-eur.dat
+-rw-r--r--   0 runner    (1001) docker     (123)      247 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/leftovers/benchmarks-pypsa-eur/common.py
+-rw-r--r--   0 runner    (1001) docker     (123)      708 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/leftovers/benchmarks-pypsa-eur/plot-benchmarks.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1471 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/leftovers/common.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1392 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/merge-benchmarks.py
+-rw-r--r--   0 runner    (1001) docker     (123)      613 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/plot-benchmarks.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)      291 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/run-cvxpy.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)      291 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/run-gurobipy.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)      399 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/run-linopy.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)      290 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/run-ortools.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)      287 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/run-pulp.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)      399 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/run-pyomo.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1023 2023-06-28 14:01:29.000000 linopy-0.2.2/benchmark/scripts/write-lp-file.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:01:38.899917 linopy-0.2.2/doc/
+-rw-r--r--   0 runner    (1001) docker     (123)      634 2023-06-28 14:01:29.000000 linopy-0.2.2/doc/Makefile
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:01:38.899917 linopy-0.2.2/doc/_static/
+-rw-r--r--   0 runner    (1001) docker     (123)     1393 2023-06-28 14:01:29.000000 linopy-0.2.2/doc/_static/theme_overrides.css
+-rw-r--r--   0 runner    (1001) docker     (123)     3082 2023-06-28 14:01:29.000000 linopy-0.2.2/doc/api.rst
+-rw-r--r--   0 runner    (1001) docker     (123)    57997 2023-06-28 14:01:29.000000 linopy-0.2.2/doc/benchmark.png
+-rw-r--r--   0 runner    (1001) docker     (123)     1087 2023-06-28 14:01:29.000000 linopy-0.2.2/doc/benchmark.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     4037 2023-06-28 14:01:29.000000 linopy-0.2.2/doc/conf.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2964 2023-06-28 14:01:29.000000 linopy-0.2.2/doc/contributing.rst
+-rw-r--r--   0 runner    (1001) docker     (123)       68 2023-06-28 14:01:29.000000 linopy-0.2.2/doc/create-a-model-with-coordinates.nblink
+-rw-r--r--   0 runner    (1001) docker     (123)       51 2023-06-28 14:01:29.000000 linopy-0.2.2/doc/create-a-model.nblink
+-rw-r--r--   0 runner    (1001) docker     (123)       57 2023-06-28 14:01:29.000000 linopy-0.2.2/doc/creating-constraints.nblink
+-rw-r--r--   0 runner    (1001) docker     (123)       57 2023-06-28 14:01:29.000000 linopy-0.2.2/doc/creating-expressions.nblink
+-rw-r--r--   0 runner    (1001) docker     (123)       55 2023-06-28 14:01:29.000000 linopy-0.2.2/doc/creating-variables.nblink
+-rw-r--r--   0 runner    (1001) docker     (123)     3195 2023-06-28 14:01:29.000000 linopy-0.2.2/doc/index.rst
+-rw-r--r--   0 runner    (1001) docker     (123)       53 2023-06-28 14:01:29.000000 linopy-0.2.2/doc/infeasible-model.nblink
+-rw-r--r--   0 runner    (1001) docker     (123)     5889 2023-06-28 14:01:29.000000 linopy-0.2.2/doc/logo.pdf
+-rw-r--r--   0 runner    (1001) docker     (123)    49959 2023-06-28 14:01:29.000000 linopy-0.2.2/doc/logo.png
+-rw-r--r--   0 runner    (1001) docker     (123)     1973 2023-06-28 14:01:29.000000 linopy-0.2.2/doc/logo.py
+-rw-r--r--   0 runner    (1001) docker     (123)      795 2023-06-28 14:01:29.000000 linopy-0.2.2/doc/make.bat
+-rw-r--r--   0 runner    (1001) docker     (123)       56 2023-06-28 14:01:29.000000 linopy-0.2.2/doc/manipulating-models.nblink
+-rw-r--r--   0 runner    (1001) docker     (123)       57 2023-06-28 14:01:29.000000 linopy-0.2.2/doc/migrating-from-pyomo.nblink
+-rw-r--r--   0 runner    (1001) docker     (123)     1612 2023-06-28 14:01:29.000000 linopy-0.2.2/doc/prerequisites.rst
+-rw-r--r--   0 runner    (1001) docker     (123)    20317 2023-06-28 14:01:29.000000 linopy-0.2.2/doc/release_notes.rst
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 14:01:29.000000 linopy-0.2.2/doc/solve-on-remote.nblink
+-rw-r--r--   0 runner    (1001) docker     (123)     2415 2023-06-28 14:01:29.000000 linopy-0.2.2/doc/syntax.rst
+-rw-r--r--   0 runner    (1001) docker     (123)       54 2023-06-28 14:01:29.000000 linopy-0.2.2/doc/testing-framework.nblink
+-rw-r--r--   0 runner    (1001) docker     (123)      679 2023-06-28 14:01:29.000000 linopy-0.2.2/doc/user-guide.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:01:38.899917 linopy-0.2.2/examples/
+-rw-r--r--   0 runner    (1001) docker     (123)     5492 2023-06-28 14:01:29.000000 linopy-0.2.2/examples/create-a-model-with-coordinates.ipynb
+-rw-r--r--   0 runner    (1001) docker     (123)     6822 2023-06-28 14:01:29.000000 linopy-0.2.2/examples/create-a-model.ipynb
+-rw-r--r--   0 runner    (1001) docker     (123)     5585 2023-06-28 14:01:29.000000 linopy-0.2.2/examples/creating-constraints.ipynb
+-rw-r--r--   0 runner    (1001) docker     (123)    10887 2023-06-28 14:01:29.000000 linopy-0.2.2/examples/creating-expressions.ipynb
+-rw-r--r--   0 runner    (1001) docker     (123)    16957 2023-06-28 14:01:29.000000 linopy-0.2.2/examples/creating-variables.ipynb
+-rw-r--r--   0 runner    (1001) docker     (123)     3214 2023-06-28 14:01:29.000000 linopy-0.2.2/examples/infeasible-model.ipynb
+-rw-r--r--   0 runner    (1001) docker     (123)     7504 2023-06-28 14:01:29.000000 linopy-0.2.2/examples/manipulating-models.ipynb
+-rw-r--r--   0 runner    (1001) docker     (123)     3230 2023-06-28 14:01:29.000000 linopy-0.2.2/examples/migrating-from-pyomo.ipynb
+-rw-r--r--   0 runner    (1001) docker     (123)    26407 2023-06-28 14:01:29.000000 linopy-0.2.2/examples/solve-on-remote.ipynb
+-rw-r--r--   0 runner    (1001) docker     (123)     3573 2023-06-28 14:01:29.000000 linopy-0.2.2/examples/testing-framework.ipynb
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:01:38.899917 linopy-0.2.2/linopy/
+-rw-r--r--   0 runner    (1001) docker     (123)      741 2023-06-28 14:01:29.000000 linopy-0.2.2/linopy/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12779 2023-06-28 14:01:29.000000 linopy-0.2.2/linopy/common.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1324 2023-06-28 14:01:29.000000 linopy-0.2.2/linopy/config.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6148 2023-06-28 14:01:29.000000 linopy-0.2.2/linopy/constants.py
+-rw-r--r--   0 runner    (1001) docker     (123)    30484 2023-06-28 14:01:29.000000 linopy-0.2.2/linopy/constraints.py
+-rw-r--r--   0 runner    (1001) docker     (123)    47260 2023-06-28 14:01:29.000000 linopy-0.2.2/linopy/expressions.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18671 2023-06-28 14:01:29.000000 linopy-0.2.2/linopy/io.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3693 2023-06-28 14:01:29.000000 linopy-0.2.2/linopy/matrices.py
+-rw-r--r--   0 runner    (1001) docker     (123)    38430 2023-06-28 14:01:29.000000 linopy-0.2.2/linopy/model.py
+-rw-r--r--   0 runner    (1001) docker     (123)      731 2023-06-28 14:01:29.000000 linopy-0.2.2/linopy/monkey_patch_xarray.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8138 2023-06-28 14:01:29.000000 linopy-0.2.2/linopy/remote.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20119 2023-06-28 14:01:29.000000 linopy-0.2.2/linopy/solvers.py
+-rw-r--r--   0 runner    (1001) docker     (123)      578 2023-06-28 14:01:29.000000 linopy-0.2.2/linopy/testing.py
+-rw-r--r--   0 runner    (1001) docker     (123)    35634 2023-06-28 14:01:29.000000 linopy-0.2.2/linopy/variables.py
+-rw-r--r--   0 runner    (1001) docker     (123)      160 2023-06-28 14:01:38.000000 linopy-0.2.2/linopy/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:01:38.903917 linopy-0.2.2/linopy.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     3480 2023-06-28 14:01:38.000000 linopy-0.2.2/linopy.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     4669 2023-06-28 14:01:38.000000 linopy-0.2.2/linopy.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 14:01:38.000000 linopy-0.2.2/linopy.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      291 2023-06-28 14:01:38.000000 linopy-0.2.2/linopy.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        7 2023-06-28 14:01:38.000000 linopy-0.2.2/linopy.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      131 2023-06-28 14:01:29.000000 linopy-0.2.2/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 14:01:38.903917 linopy-0.2.2/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1882 2023-06-28 14:01:29.000000 linopy-0.2.2/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:01:38.903917 linopy-0.2.2/test/
+-rw-r--r--   0 runner    (1001) docker     (123)     5066 2023-06-28 14:01:29.000000 linopy-0.2.2/test/test_common.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12044 2023-06-28 14:01:29.000000 linopy-0.2.2/test/test_constraint.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4721 2023-06-28 14:01:29.000000 linopy-0.2.2/test/test_constraints.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1709 2023-06-28 14:01:29.000000 linopy-0.2.2/test/test_inconsistency_checks.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2644 2023-06-28 14:01:29.000000 linopy-0.2.2/test/test_io.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17392 2023-06-28 14:01:29.000000 linopy-0.2.2/test/test_linear_expression.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1919 2023-06-28 14:01:29.000000 linopy-0.2.2/test/test_matrices.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2698 2023-06-28 14:01:29.000000 linopy-0.2.2/test/test_model.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15195 2023-06-28 14:01:29.000000 linopy-0.2.2/test/test_optimization.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1466 2023-06-28 14:01:29.000000 linopy-0.2.2/test/test_options.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4348 2023-06-28 14:01:29.000000 linopy-0.2.2/test/test_quadratic_expression.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4227 2023-06-28 14:01:29.000000 linopy-0.2.2/test/test_repr.py
+-rw-r--r--   0 runner    (1001) docker     (123)      951 2023-06-28 14:01:29.000000 linopy-0.2.2/test/test_scalar_constraint.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2086 2023-06-28 14:01:29.000000 linopy-0.2.2/test/test_scalar_linear_expression.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4529 2023-06-28 14:01:29.000000 linopy-0.2.2/test/test_variable.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7468 2023-06-28 14:01:29.000000 linopy-0.2.2/test/test_variable_assignment.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2313 2023-06-28 14:01:29.000000 linopy-0.2.2/test/test_variables.py
```

### Comparing `linopy-0.2.1/.coverage` & `linopy-0.2.2/.coverage`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/.github/workflows/CI.yaml` & `linopy-0.2.2/.github/workflows/CI.yaml`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/.github/workflows/deploy.yml` & `linopy-0.2.2/.github/workflows/deploy.yml`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/.pre-commit-config.yaml` & `linopy-0.2.2/.pre-commit-config.yaml`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/LICENSE.txt` & `linopy-0.2.2/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/PKG-INFO` & `linopy-0.2.2/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: linopy
-Version: 0.2.1
+Version: 0.2.2
 Summary: Linear optimization with N-D labeled arrays in Python
 Home-page: https://github.com/PyPSA/linopy
 Author: Fabian Hofmann
 Author-email: hofmann@fias.uni-frankfurt.de
 License: MIT
 Classifier: Development Status :: 3 - Alpha
 Classifier: Environment :: Console
```

### Comparing `linopy-0.2.1/README.md` & `linopy-0.2.2/README.md`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/README.md` & `linopy-0.2.2/benchmark/README.md`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/Snakefile` & `linopy-0.2.2/benchmark/Snakefile`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/benchmark-absolute.pdf` & `linopy-0.2.2/benchmark/benchmark-absolute.pdf`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/benchmark-absolute.png` & `linopy-0.2.2/benchmark/benchmark-absolute.png`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/benchmark-overhead.pdf` & `linopy-0.2.2/benchmark/benchmark-overhead.pdf`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/benchmark-overhead.png` & `linopy-0.2.2/benchmark/benchmark-overhead.png`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/benchmark_resource-absolute.pdf` & `linopy-0.2.2/benchmark/benchmark_resource-absolute.pdf`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/benchmark_resource-absolute.png` & `linopy-0.2.2/benchmark/benchmark_resource-absolute.png`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/benchmark_resource-overhead.pdf` & `linopy-0.2.2/benchmark/benchmark_resource-overhead.pdf`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/benchmark_resource-overhead.png` & `linopy-0.2.2/benchmark/benchmark_resource-overhead.png`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/environment.fixed.yaml` & `linopy-0.2.2/benchmark/environment.fixed.yaml`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/notebooks/plot-benchmarks.py.ipynb` & `linopy-0.2.2/benchmark/notebooks/plot-benchmarks.py.ipynb`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/scripts/benchmark_cvxpy.py` & `linopy-0.2.2/benchmark/scripts/benchmark_cvxpy.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/scripts/benchmark_gurobipy.py` & `linopy-0.2.2/benchmark/scripts/benchmark_gurobipy.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/scripts/benchmark_jump.jl` & `linopy-0.2.2/benchmark/scripts/benchmark_jump.jl`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/scripts/benchmark_linopy.py` & `linopy-0.2.2/benchmark/scripts/benchmark_linopy.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/scripts/benchmark_ortools.py` & `linopy-0.2.2/benchmark/scripts/benchmark_ortools.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/scripts/benchmark_pulp.py` & `linopy-0.2.2/benchmark/scripts/benchmark_pulp.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/scripts/benchmark_pyomo.py` & `linopy-0.2.2/benchmark/scripts/benchmark_pyomo.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/scripts/benchmarks-pypsa-eur/plot-benchmarks.py` & `linopy-0.2.2/benchmark/scripts/benchmarks-pypsa-eur/plot-benchmarks.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/scripts/concat-benchmarks.py` & `linopy-0.2.2/benchmark/scripts/concat-benchmarks.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/scripts/leftovers/benchmark-linopy.py` & `linopy-0.2.2/benchmark/scripts/leftovers/benchmark-linopy.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/scripts/leftovers/benchmarks-pypsa-eur/__pycache__/benchmark-linopy.cpython-310.pyc` & `linopy-0.2.2/benchmark/scripts/leftovers/benchmarks-pypsa-eur/__pycache__/benchmark-linopy.cpython-310.pyc`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/scripts/leftovers/benchmarks-pypsa-eur/__pycache__/benchmark-pyomo.cpython-310.pyc` & `linopy-0.2.2/benchmark/scripts/leftovers/benchmarks-pypsa-eur/__pycache__/benchmark-pyomo.cpython-310.pyc`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/scripts/leftovers/benchmarks-pypsa-eur/__pycache__/benchmark-pypsa-linopf.cpython-310.pyc` & `linopy-0.2.2/benchmark/scripts/leftovers/benchmarks-pypsa-eur/__pycache__/benchmark-pypsa-linopf.cpython-310.pyc`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/scripts/leftovers/benchmarks-pypsa-eur/__pycache__/plot-benchmarks.cpython-310.pyc` & `linopy-0.2.2/benchmark/scripts/leftovers/benchmarks-pypsa-eur/__pycache__/plot-benchmarks.cpython-310.pyc`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/scripts/leftovers/benchmarks-pypsa-eur/benchmark-linopy-pypsa-eur.dat` & `linopy-0.2.2/benchmark/scripts/leftovers/benchmarks-pypsa-eur/benchmark-linopy-pypsa-eur.dat`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/scripts/leftovers/benchmarks-pypsa-eur/benchmark-pyomo-pypsa-eur.dat` & `linopy-0.2.2/benchmark/scripts/leftovers/benchmarks-pypsa-eur/benchmark-pyomo-pypsa-eur.dat`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/scripts/leftovers/benchmarks-pypsa-eur/benchmark-pypsa-eur-with-pypsa.pdf` & `linopy-0.2.2/benchmark/scripts/leftovers/benchmarks-pypsa-eur/benchmark-pypsa-eur-with-pypsa.pdf`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/scripts/leftovers/benchmarks-pypsa-eur/benchmark-pypsa-eur.pdf` & `linopy-0.2.2/benchmark/scripts/leftovers/benchmarks-pypsa-eur/benchmark-pypsa-eur.pdf`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/scripts/leftovers/benchmarks-pypsa-eur/benchmark-pypsa_linopf-pypsa-eur.dat` & `linopy-0.2.2/benchmark/scripts/leftovers/benchmarks-pypsa-eur/benchmark-pypsa_linopf-pypsa-eur.dat`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/scripts/leftovers/benchmarks-pypsa-eur/plot-benchmarks.py` & `linopy-0.2.2/benchmark/scripts/leftovers/benchmarks-pypsa-eur/plot-benchmarks.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/scripts/leftovers/common.py` & `linopy-0.2.2/benchmark/scripts/leftovers/common.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/scripts/merge-benchmarks.py` & `linopy-0.2.2/benchmark/scripts/merge-benchmarks.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/scripts/plot-benchmarks.py` & `linopy-0.2.2/benchmark/scripts/plot-benchmarks.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/benchmark/scripts/write-lp-file.py` & `linopy-0.2.2/benchmark/scripts/write-lp-file.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/doc/Makefile` & `linopy-0.2.2/doc/Makefile`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/doc/_static/theme_overrides.css` & `linopy-0.2.2/doc/_static/theme_overrides.css`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/doc/api.rst` & `linopy-0.2.2/doc/api.rst`

 * *Files 14% similar despite different names*

```diff
@@ -17,23 +17,14 @@
     model.Model
     model.Model.add_variables
     model.Model.add_constraints
     model.Model.add_objective
     model.Model.linexpr
     model.Model.remove_constraints
 
-Creating a model with ``eval`` strings (experimental)
-=====================================================
-
-.. autosummary::
-    :toctree: generated/
-
-    model.Model.vareval
-    model.Model.lineval
-    model.Model.coneval
 
 Classes under the hook
 ======================
 
 Variable
 --------
 
@@ -58,61 +49,51 @@
 
 .. autosummary::
     :toctree: generated/
 
     variables.Variables
     variables.Variables.add
     variables.Variables.remove
+    variables.Variables.continuous
+    variables.Variables.integers
     variables.Variables.binaries
-    variables.Variables.non_binaries
     variables.Variables.integers
-    variables.Variables.iter_ravel
-    variables.Variables.ravel
-    variables.Variables.get_blocks
+    variables.Variables.flat
 
 
 LinearExpressions
 -----------------
 
 .. autosummary::
     :toctree: generated/
 
     expressions.LinearExpression
     expressions.LinearExpression.sum
-    expressions.LinearExpression.groupby_sum
+    expressions.LinearExpression.where
+    expressions.LinearExpression.groupby
+    expressions.LinearExpression.rolling
     expressions.LinearExpression.from_tuples
     expressions.merge
     expressions.ScalarLinearExpression
 
 Constraint
 ----------
 
 ``Constraint`` is a subclass of ``xarray.DataArray`` and contains all labels referring to a multi-dimensional constraint.
 
 .. autosummary::
     :toctree: generated/
 
     constraints.Constraint
-    constraints.Constraint.to_array
     constraints.Constraint.coeffs
     constraints.Constraint.vars
     constraints.Constraint.lhs
     constraints.Constraint.sign
     constraints.Constraint.rhs
-
-
-AnonymousConstraint
--------------------
-
-``AnonynousConstraint`` contains all information about lower bounds, upper bounds, sign and right-hand-side of a constraint that is not yet added to a ``Model`` instance.
-
-.. autosummary::
-    :toctree: generated/
-
-    constraints.AnonymousConstraint
+    constraints.Constraint.flat
 
 
 Constraints
 -----------
 
 .. autosummary::
     :toctree: generated/
@@ -120,17 +101,15 @@
     constraints.Constraints
     constraints.Constraints.add
     constraints.Constraints.remove
     constraints.Constraints.coefficientrange
     constraints.Constraints.inequalities
     constraints.Constraints.equalities
     constraints.Constraints.sanitize_missings
-    constraints.Constraints.get_blocks
-    constraints.Constraints.iter_ravel
-    constraints.Constraints.ravel
+    constraints.Constraints.flat
     constraints.Constraints.to_matrix
 
 
 IO functions
 ============
 
 .. autosummary::
```

### Comparing `linopy-0.2.1/doc/benchmark.png` & `linopy-0.2.2/doc/benchmark.png`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/doc/benchmark.rst` & `linopy-0.2.2/doc/benchmark.rst`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/doc/conf.py` & `linopy-0.2.2/doc/conf.py`

 * *Files 3% similar despite different names*

```diff
@@ -88,37 +88,35 @@
 .. note::
 
     You can `download <https://github.com/pypsa/linopy/tree/v{{ env.config.release|e }}/examples/{{ docname }}>`_ this example as a Jupyter notebook
     or start it `in interactive mode <https://mybinder.org/v2/gh/PyPSA/linopy/v{{ env.config.release|e }}?filepath=examples/{{ docname|e }}>`_.
 
 """
 
-nbsphinx_allow_errors = True
+nbsphinx_allow_errors = False
 
 # -- Options for HTML output -------------------------------------------------
 
 # The theme to use for HTML and HTML Help pages.  See the documentation for
 # a list of builtin themes.
-html_theme = "sphinx_rtd_theme"
+html_theme = "sphinx_book_theme"
+
+html_title = "Linopy: Optimization with n-dimensional labeled variables"
+
 
 # Theme options are theme-specific and customize the look and feel of a theme
 # further.  For a list of options available for each theme, see the
 # documentation.
 html_theme_options = {
-    "display_version": True,
-    "sticky_navigation": True,
-    # 'style_nav_header_background': '#009682',
+    "repository_url": "https://github.com/pypsa/linopy",
+    "use_repository_button": True,
 }
 
 
 # These folders are copied to the documentation's HTML output
 html_static_path = ["_static"]
 html_logo = "logo.png"
-html_theme_options = {
-    "logo_only": True,
-    "display_version": False,
-}
 
 
 # These paths are either relative to html_static_path
 # or fully qualified paths (eg. https://...)
 html_css_files = ["theme_overrides.css"]
```

### Comparing `linopy-0.2.1/doc/contributing.rst` & `linopy-0.2.2/doc/contributing.rst`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/doc/index.rst` & `linopy-0.2.2/doc/index.rst`

 * *Files 10% similar despite different names*

```diff
@@ -4,25 +4,21 @@
    contain the root `toctree` directive.
 
 .. module:: linopy
 
 linopy: Linear optimization with N-D labeled variables
 ======================================================
 
-|PyPI| |CI| |License: GPL v3|
+|PyPI| |CI| |License|
 
-**linopy** is an open-source python package that facilitates **linear or
-mixed-integer optimisation** with **real world data**. It builds a
-bridge between data analysis packages like
+
+Welcome to Linopy! This Python library is designed to make linear programming easy, flexible, and performant. Whether you're dealing with Linear, Integer, Mixed-Integer, or Quadratic Programming, Linopy is as a user-friendly interface to define variables and constraints. It serves as a bridge, connecting data analysis packages such like
 `xarray <https://github.com/pydata/xarray>`__ &
-`pandas <https://pandas.pydata.org/>`__ and linear problem solvers like
-`cbc <https://projects.coin-or.org/Cbc>`__,
-`gurobi <https://www.gurobi.com/>`__ (see the full list below). The
-project aims to make linear programming in python easy, highly-flexible
-and performant.
+`pandas <https://pandas.pydata.org/>`__ with problem solvers.
+
 
 Main features
 -------------
 
 **linopy** is heavily based on
 `xarray <https://github.com/pydata/xarray>`__ which allows for many
 flexible data-handling features:
@@ -38,37 +34,23 @@
 -  Get insight into the **clear and transparent data model**
 -  **Modify** and **delete** assigned variables and constraints on the
    fly
 -  Use **lazy operations** for large linear programs with
    `dask <https://dask.org/>`__
 -  Choose from **different commercial and non-commercial solvers**
 -  Fast **import and export** a linear model using xarray’s netcdf IO
+-  Support of various solvers
+   - `Cbc <https://projects.coin-or.org/Cbc>`__
+   - `GLPK <https://www.gnu.org/software/glpk/>`__
+   - `HiGHS <https://www.maths.ed.ac.uk/hall/HiGHS/>`__
+   - `Gurobi <https://www.gurobi.com/>`__
+   - `Xpress <https://www.fico.com/en/products/fico-xpress-solver>`__
+   - `Cplex <https://www.ibm.com/de-de/analytics/cplex-optimizer>`__
 
-Installation
-------------
-
-So far **linopy** is available on the PyPI repository
-
-.. code:: bash
-
-   pip install linopy
-
-Supported solvers
------------------
-
-**linopy** supports the following solvers
-
--  `Cbc <https://projects.coin-or.org/Cbc>`__
--  `GLPK <https://www.gnu.org/software/glpk/>`__
--  `HiGHS <https://www.maths.ed.ac.uk/hall/HiGHS/>`__
--  `Gurobi <https://www.gurobi.com/>`__
--  `Xpress <https://www.fico.com/en/products/fico-xpress-solver>`__
--  `Cplex <https://www.ibm.com/de-de/analytics/cplex-optimizer>`__
 
-Note that these do have to be installed by the user separately.
 
 License
 =======
 
 Copyright 2021-2023 Fabian Hofmann
 
 This package is published under MIT license.
@@ -80,28 +62,34 @@
 .. |License| image:: https://img.shields.io/pypi/l/linopy.svg
    :target: https://mit-license.org/
 
 
 .. toctree::
    :hidden:
    :maxdepth: 2
-   :caption: Getting started
+   :caption: Getting Started
 
+   prerequisites
    create-a-model
-   solvers
+   create-a-model-with-coordinates
 
 .. toctree::
    :hidden:
    :maxdepth: 2
    :caption: User Guide
 
+   user-guide
    creating-variables
+   creating-expressions
    creating-constraints
    manipulating-models
+   testing-framework
+   infeasible-model
    solve-on-remote
+   migrating-from-pyomo
 
 
 .. toctree::
    :hidden:
    :maxdepth: 2
    :caption: Benchmarking
```

### Comparing `linopy-0.2.1/doc/make.bat` & `linopy-0.2.2/doc/make.bat`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/doc/release_notes.rst` & `linopy-0.2.2/doc/release_notes.rst`

 * *Files 3% similar despite different names*

```diff
@@ -4,14 +4,24 @@
 .. Upcoming Release
 .. ----------------
 
 Version 0.2.1
 -------------
 
 
+* The documentation was revised and extended.
+* A new function `print_labels` was added to the `Variables` and `Constraints` class. This function allows to print the variables/constraints from a list of labels.
+* A new function `compute_infeasibilities` and `print_infeasibilities` was added to the `Model` class. This function allows to compute the infeasibilities of an infeasible model and print them out. The function only supports the `gurobi` solver so far.
+
+
+
+Version 0.2.1
+-------------
+
+
 * Backwards compatibility for python 3.8.
 * `Variable`, `LinearExpression` and `Constraint` now have a print function to easily print the objects with larger layouts, i.e. showing more terms and lines.
 
 
 Version 0.2.0
 -------------
 
@@ -22,15 +32,15 @@
 * `LinearExpression`'s now support constant values. This allows defining linear expressions with numeric constant values, like `x + 5`.
 * When defining constraints, it is not needed to separate variables from constants anymore. Thus, expressions  like `x <= y` or `5 * x + 10 >= y` are supported.
 * The new default solver will now be the first element in `available_solvers`.
 * The classes `Variable`, `LinearExpression` and `Constraint` now have a `loc` method.
 * The classes `Variable`, `LinearExpression`, `Constraint`, `Variables` and `Constraints` now have a `flat` method, which returns a flattened `pandas.DataFrame` of the object in long-table format.
 * It is now possible to access variables and constraints by a dot notation. For example, `model.variables.x` returns the variable `x` of the model.
 * Variable assignment without explicit coordinates is now supported. In an internal step, integer coordinates are assigned to the dimensions without explicit coordinates.
-* The `groupby` function now supports passing `pandas.Dataframe`s as groupby keys. These allows to group by multiple variables at once.
+* The `groupby` function now supports passing a `pandas.Dataframe` as `groupby` keys. These allows to group by multiple variables at once.
 * The performance of the `groupby` function was strongly increased. In large operations a speedup of 10x was observed.
 * New test functions `assert_varequal`, `assert_conequal` were added to the `testing` module.
 
 
 **Deprecations**
 
 * The class `AnonymousConstraint` is now deprecated in the favor of `Constraint`. The latter can now be assigned to a model or not.
@@ -119,15 +129,15 @@
 * The `eval` module was removed in favor of arithmetic operations on the classes `Variable`, `LinearExpression` and `Constraint`.
 * Solver options are now printed out in the console when solving a model.
 * If a variable with indexes differing from the model internal indexes are assigned, linopy will raise a warning and align the variable to the model indexes.
 
 Version 0.0.15
 --------------
 
-* Using the python `sum()` function over `ScalarVariable`s and `ScalarLinearExpression`s is now supported.
+* Using the python `sum()` function over a `ScalarVariable` or a `ScalarLinearExpression` is now supported.
 * Returning None type in `from_rule` assignment is now supported.
 * Python 3.11 is now supported
 * Xarray versions higher and lower `v2022.06.` are now supported.
 
 Version 0.0.14
 --------------
```

### Comparing `linopy-0.2.1/doc/syntax.rst` & `linopy-0.2.2/doc/syntax.rst`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/examples/create-a-model.ipynb` & `linopy-0.2.2/examples/manipulating-models.ipynb`

 * *Files 21% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.9458591683201059%*

 * *Differences: {"'cells'": "{0: {'id': '37a85c22', 'source': {insert: [(0, '# Modifying Models\\n'), (2, 'Given a "*

 * *            'model that is already built and possibly optimized, the user might want to modify '*

 * *            'single constraint or variable bounds by means of correction or exploration of the '*

 * *            'feasible space. \\n\'), (3, \'\\n\'), (4, "In the following we show how single '*

 * *            "elements can be tweaked or rewritten. Let's start with the simple model of the "*

 * *            '`Getting Started […]*

```diff
@@ -1,386 +1,301 @@
 {
     "cells": [
         {
             "cell_type": "markdown",
-            "id": "4db583af",
+            "id": "37a85c22",
             "metadata": {},
             "source": [
-                "# Solve a basic optimization model\n",
+                "# Modifying Models\n",
                 "\n",
-                "In this example, we explain the basic functions of the linopy Model class. First, we are setting up a very simple linear optimization model, given by "
-            ]
-        },
-        {
-            "cell_type": "markdown",
-            "id": "together-ocean",
-            "metadata": {},
-            "source": [
-                "Minimize:\n",
-                "$$ x + 2y $$\n",
-                "      \n",
-                "subject to:\n",
+                "Given a model that is already built and possibly optimized, the user might want to modify single constraint or variable bounds by means of correction or exploration of the feasible space. \n",
                 "\n",
-                "$$ x \\ge 0 $$\n",
-                "$$y \\ge 0 $$\n",
-                "$$3x + 7y \\ge 10 $$\n",
-                "$$5x + 2y \\ge 3 $$"
+                "In the following we show how single elements can be tweaked or rewritten. Let's start with the simple model of the `Getting Started` section. "
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "dramatic-cannon",
+            "id": "16a41836",
             "metadata": {},
             "outputs": [],
             "source": [
-                "from linopy import Model"
+                "import linopy \n",
+                "import pandas as pd\n",
+                "import xarray as xr"
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "technical-conducting",
+            "id": "8f4d182f",
             "metadata": {},
             "outputs": [],
             "source": [
-                "m = Model()"
-            ]
-        },
-        {
-            "cell_type": "markdown",
-            "id": "rolled-delicious",
-            "metadata": {},
-            "source": [
-                "The Model class serves at a container for all the relevant data. \n",
+                "m = linopy.Model()\n",
+                "time = pd.Index(range(10), name='time')\n",
                 "\n",
-                "### Adding variables\n",
+                "x = m.add_variables(lower=0, coords=[time], name='x', )\n",
+                "y = m.add_variables(lower=0, coords=[time], name='y')\n",
                 "\n",
-                "Let's add the two variables. Note that a variable can always be assigned with a lower and an upper bound. In this case, both `x` and `y` have a lower bound of zero (coming from the first two constraints). Note, the default for lower and upper bounds are minus and plus infinity."
-            ]
-        },
-        {
-            "cell_type": "code",
-            "execution_count": null,
-            "id": "protecting-power",
-            "metadata": {},
-            "outputs": [],
-            "source": [
-                "x = m.add_variables(lower=0, name='x')\n",
-                "y = m.add_variables(lower=0, name='y');"
-            ]
-        },
-        {
-            "cell_type": "markdown",
-            "id": "featured-maria",
-            "metadata": {},
-            "source": [
-                "`x` and `y` are linopy variables. Each of them consist of an array with the variable references in the model, that is the names of variables that will finally be used when solving the model. "
-            ]
-        },
-        {
-            "cell_type": "code",
-            "execution_count": null,
-            "id": "virtual-anxiety",
-            "metadata": {},
-            "outputs": [],
-            "source": [
-                "x"
+                "factor = pd.Series(time, index=time)\n",
+                "\n",
+                "con1 = m.add_constraints(3*x + 7*y >= 10*factor, name='con1')\n",
+                "con2 = m.add_constraints(5*x + 2*y >= 3*factor, name='con2')\n",
+                "\n",
+                "m.add_objective(x + 2*y) \n",
+                "m.solve()\n",
+                "\n",
+                "m.solve();\n",
+                "sol = m.solution.to_dataframe()\n",
+                "sol.plot(grid=True, ylabel='Optimal Value')"
             ]
         },
         {
             "cell_type": "markdown",
-            "id": "sonic-rebate",
+            "id": "d3f4b966",
             "metadata": {},
             "source": [
-                "Since both `x` and `y` are scalar variables, so their arrays also contain just one variable reference. The variable `x` points to the optimisation variable 1 and the variable `y` points to the optimisation variable 2. Later we will see the benefit of this behaviour.  \n",
+                "The figure above shows the optimal values of `x(t)` and `y(t)`. \n",
                 "\n",
-                "### Adding Constraints\n",
+                "## Varying lower and upper bounds\n",
                 "\n",
-                "Constraints consist of the left hand side (lhs) and the righ hand side (rhs). The first constraint that we want to write down is \n",
-                "$3x + 7y >= 10$, which we can write just exactly in this way"
+                "Now, let's say we want to set the lower bound of `y(t)` to 1. This would translate to:"
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "fbb46cad",
+            "id": "f7db57f8",
             "metadata": {},
             "outputs": [],
             "source": [
-                "3*x + 7*y >= 10"
+                "x.lower = 1 "
             ]
         },
         {
             "cell_type": "markdown",
-            "id": "f4666bee",
+            "id": "66b8be86",
             "metadata": {},
             "source": [
-                "Note, we can also mix the constant and the variable expression, like this"
+                ".. note::\n",
+                "   The same could have been achieved by calling `m.variables.x.lower = 1`\n",
+                "\n",
+                "Let's solve it again!"
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "60f41b76",
+            "id": "c37add87",
             "metadata": {},
             "outputs": [],
             "source": [
-                "3*x + 7*y - 10 >= 0"
-            ]
-        },
-        {
-            "cell_type": "markdown",
-            "id": "02abd938",
-            "metadata": {},
-            "source": [
-                "... and linopy will automatically take over the separation of variables expression on the lhs, and constant values on the rhs.\n",
-                "\n",
-                "The constraint is currently not assigned to the model. We assign it by calling the function `m.add_constraints`."
+                "m.solve();\n",
+                "sol = m.solution.to_dataframe()\n",
+                "sol.plot(grid=True, ylabel='Optimal Value')"
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "hollywood-production",
+            "id": "b5be8d00",
             "metadata": {},
             "outputs": [],
             "source": [
-                "m.add_constraints(3*x + 7*y >= 10)\n",
-                "m.add_constraints(5*x + 2*y >= 3);"
+                "sol"
             ]
         },
         {
             "cell_type": "markdown",
-            "id": "global-maple",
+            "id": "d35e3309",
             "metadata": {},
             "source": [
-                "## Adding the Objective \n",
+                "We see that the new lower bound of x is binding across all time steps.\n",
                 "\n",
-                "We do the same for defining the objective while the objective function only consists of a linear expression."
+                "Of course the implementation is flexible over the dimensions, so we can pass non-scalar values:"
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "overall-exhibition",
+            "id": "451aba93",
             "metadata": {},
             "outputs": [],
             "source": [
-                "m.add_objective(x + 2*y)"
+                "x.lower = xr.DataArray(range(10, 0, -1), coords=(time,))"
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "pressing-copying",
+            "id": "e25f26a1",
             "metadata": {},
             "outputs": [],
             "source": [
-                "m.solve()"
+                "m.solve();\n",
+                "sol = m.solution.to_dataframe()\n",
+                "sol.plot(grid=True, ylabel='Optimal Value')"
             ]
         },
         {
             "cell_type": "markdown",
-            "id": "preceding-limit",
+            "id": "4d991939",
             "metadata": {},
             "source": [
-                "The solution of the linear problem assinged to the variables under `solution` in fom of a `xarray.Dataset`. "
+                "You can manipulate the upper bound of a variable in the same way."
             ]
         },
         {
-            "cell_type": "code",
-            "execution_count": null,
-            "id": "electric-duration",
+            "cell_type": "markdown",
+            "id": "de29c28e",
             "metadata": {},
-            "outputs": [],
             "source": [
-                "x.solution"
+                "## Varying Constraints\n",
+                "\n",
+                "A similar functionality is implemented for constraints. Here we can modify the left-hand-side, the sign and the right-hand-side.\n",
+                "\n",
+                "Assume we want to relax the right-hand-side of the first constraint `con1` to `8 * factor`. This would translate to:"
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "e6d31751",
+            "id": "18d1bf4b",
             "metadata": {},
             "outputs": [],
             "source": [
-                "y.solution"
+                "con1.rhs = 8 * factor"
             ]
         },
         {
             "cell_type": "markdown",
-            "id": "f2c1a9d5",
+            "id": "5499b3b4",
             "metadata": {},
             "source": [
-                "## Expanding the dimensionality\n",
+                ".. note::\n",
+                "   The same could have been achieved by calling `m.variables.con1.rhs = 8 * factor`\n",
                 "\n",
-                "Now comes the interesting part. Suppose the two variables `x` and `y` are a function of time `t` and a modified problem setup like "
+                "Let's solve it again!"
             ]
         },
         {
-            "cell_type": "markdown",
-            "id": "comparable-talent",
+            "cell_type": "code",
+            "execution_count": null,
+            "id": "e4d34142",
             "metadata": {},
+            "outputs": [],
             "source": [
-                "Minimize:\n",
-                "$$\\sum_t x_t + 2 y_t$$\n",
-                "\n",
-                "subject to:\n",
-                "\n",
-                "$$\n",
-                "x_t \\ge 0 \\qquad \\forall t \\\\\n",
-                "y_t \\ge 0 \\qquad \\forall t \\\\\n",
-                "3x_t + 7y_t \\ge 10 t \\qquad \\forall t\\\\\n",
-                "5x_t + 2y_t \\ge 3 t \\qquad \\forall t\n",
-                "$$\n",
-                "\n",
-                "whereas `t` spans all the range from 0 to 10."
+                "m.solve();\n",
+                "sol = m.solution.to_dataframe()\n",
+                "sol.plot(grid=True, ylabel='Optimal Value')"
             ]
         },
         {
             "cell_type": "markdown",
-            "id": "proprietary-receipt",
+            "id": "bc683e13",
             "metadata": {},
             "source": [
-                "First, we define a new model (we just overwrite the old `m`)."
+                "In contrast to previous figure, we now see that the optimal value of `y` does not reach values above 10 in the end. \n",
+                "\n",
+                "In the same way, we can modify the left-hand-side. Assume we want to weight `y` with a coefficient of 8 in the constraints, this gives"
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "close-maximum",
+            "id": "f8e81d20",
             "metadata": {},
             "outputs": [],
             "source": [
-                "m = Model()"
+                "con1.lhs = 3 * x + 8 * y"
             ]
         },
         {
             "cell_type": "markdown",
-            "id": "positive-appearance",
-            "metadata": {},
-            "source": [
-                "Again, we define `x` and `y` using the `add_variables` function, but now we are adding a `coords` argument. This automatically creates optimization variables for all coordinates, in this case time-steps."
-            ]
-        },
-        {
-            "cell_type": "code",
-            "execution_count": null,
-            "id": "included-religious",
+            "id": "cc377d95",
             "metadata": {},
-            "outputs": [],
             "source": [
-                "import pandas as pd\n",
-                "time = pd.Index(range(10), name='time')\n",
-                "\n",
-                "x = m.add_variables(lower=0, coords=[time], name='x', )\n",
-                "y = m.add_variables(lower=0, coords=[time], name='y')"
+                "**Note:**\n",
+                "The same could have been achieved by calling \n",
+                "```python \n",
+                "m.constraints['con1'].lhs = 3 * x + 8 * y\n",
+                "```"
             ]
         },
         {
             "cell_type": "markdown",
-            "id": "terminal-ethernet",
+            "id": "633d463b",
             "metadata": {},
             "source": [
-                "We again write the constraints out using the syntax from above, while multiplying the rhs with `t`. Note that the coordinates from the lhs and the rhs have to match. \n",
-                "\n",
-                "*Note: In case lhs and rhs have different sets of coordinates, the constraint creation is broadcasted over all combinations of coordinates.*"
+                "which leads to"
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "comprehensive-blend",
+            "id": "9b73250d",
             "metadata": {},
             "outputs": [],
             "source": [
-                "factor = pd.Series(time, index=time)\n",
-                "\n",
-                "m.add_constraints(3*x + 7*y >= 10*factor, name='Constraint1')\n",
-                "m.add_constraints(5*x + 2*y >= 3*factor, name='Constraint2')\n",
-                "m"
+                "m.solve();\n",
+                "sol = m.solution.to_dataframe()\n",
+                "sol.plot(grid=True, ylabel='Optimal Value')"
             ]
         },
         {
             "cell_type": "markdown",
-            "id": "induced-professor",
+            "id": "e509d5d7",
             "metadata": {},
             "source": [
-                "When we add the objective, we use the `sum` function of `linopy.LinearExpression`. This stacks the `term_` dimension, such that all terms of the `time` dimension are rewritten into one big expression. "
-            ]
-        },
-        {
-            "cell_type": "code",
-            "execution_count": null,
-            "id": "alternate-story",
-            "metadata": {},
-            "outputs": [],
-            "source": [
-                "obj = (x + 2*y).sum()\n",
-                "m.add_objective(obj)"
+                "## Varying the objective \n",
+                "\n",
+                "Varying the objective happens in the same way as for the left-hand-side of the constraint as it is a linear expression too. Note, when passing an unstacked linear expression, i.e. an expression with more than the `_term` dimension, `linopy` will automatically stack it. \n",
+                "\n",
+                "So assume, we would like to modify the weight of `y` in the objective function, this translates to:"
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "outer-presence",
+            "id": "44689b5b",
             "metadata": {},
             "outputs": [],
             "source": [
-                "m.solve()"
+                "m.objective = x + 3*y"
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "monthly-census",
+            "id": "2144af8e",
             "metadata": {},
             "outputs": [],
             "source": [
-                "m.solution.to_dataframe().plot(grid=True, ylabel='Optimal Value')"
-            ]
-        },
-        {
-            "cell_type": "markdown",
-            "id": "owned-europe",
-            "metadata": {},
-            "source": [
-                "You can easily add dimensions in this way. Since the underlying code is highly relying on `xarray` broadcasting on new dimensions is automatically supported, so even the `rhs` can introduce new dimensions. Just be careful that all variable dimensions have the correct dimension name. "
+                "m.solve();\n",
+                "sol = m.solution.to_dataframe()\n",
+                "sol.plot(grid=True, ylabel='Optimal Value')"
             ]
         },
         {
             "cell_type": "markdown",
-            "id": "classified-colonial",
+            "id": "f1faa095",
             "metadata": {},
             "source": [
-                "We limit the slope of the `y` variable by adding a constraint in the form of \n",
-                "$$ y_{t} - y_{t-1} \\le 0.5 \\qquad \\forall t \\ge 1$$"
+                "As a consequence, `y` stays at zero for all time steps."
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "organized-hampshire",
+            "id": "85cbd60b",
             "metadata": {},
             "outputs": [],
             "source": [
-                "lhs = (y - y.shift(time=1)).sel(time=time[1:])\n",
-                "m.add_constraints(lhs <= 0.5, name='Limited growth y')"
-            ]
-        },
-        {
-            "cell_type": "code",
-            "execution_count": null,
-            "id": "sustained-portrait",
-            "metadata": {},
-            "outputs": [],
-            "source": [
-                "m.solve()\n",
-                "m.solution.to_dataframe().plot(grid=True, ylabel='Optimal Value');"
+                "m.objective"
             ]
         }
     ],
     "metadata": {
         "@webio": {
             "lastCommId": null,
             "lastKernelId": null
```

### Comparing `linopy-0.2.1/examples/creating-constraints.ipynb` & `linopy-0.2.2/examples/create-a-model.ipynb`

 * *Files 20% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.9428454184704185%*

 * *Differences: {"'cells'": "{0: {'id': '4db583af', 'source': {insert: [(0, '# Solve a Basic Model\\n'), (2, 'In "*

 * *            'this example, we explain the basic functions of the linopy `Model` class. First, we '*

 * *            "are setting up a very simple linear optimization model, given by ')], delete: [7, 6, "*

 * *            "5, 4, 2, 1, 0]}, 'attachments': OrderedDict()}, 1: {'id': 'together-ocean', 'source': "*

 * *            "{insert: [(0, 'Minimize:\\n'), (1, '$$ x + 2y $$\\n'), (2, '      \\n'), (3, 'subject "*

 * *             […]*

```diff
@@ -1,330 +1,262 @@
 {
     "cells": [
         {
+            "attachments": {},
             "cell_type": "markdown",
-            "id": "e8249281",
+            "id": "4db583af",
             "metadata": {},
             "source": [
-                "# Creating constraints\n",
+                "# Solve a Basic Model\n",
                 "\n",
-                "Constraints are created and at the same time assigned to the model using the function \n",
-                "\n",
-                "```\n",
-                "model.add_constraints\n",
-                "```\n",
-                "where `model` is a `linopy.Model` instance. Again, we want to understand this function and its argument. So, let's create a model first."
-            ]
-        },
-        {
-            "cell_type": "code",
-            "execution_count": null,
-            "id": "e0c196e4",
-            "metadata": {},
-            "outputs": [],
-            "source": [
-                "from linopy import Model\n",
-                "import numpy as np\n",
-                "import pandas as pd\n",
-                "import xarray as xr\n",
-                "m = Model()"
+                "In this example, we explain the basic functions of the linopy `Model` class. First, we are setting up a very simple linear optimization model, given by "
             ]
         },
         {
+            "attachments": {},
             "cell_type": "markdown",
-            "id": "043c0b06",
+            "id": "together-ocean",
             "metadata": {},
             "source": [
-                "`linopy` follows the convention that all variables stand on the left-hand-side (lhs) of a constraint. In contrast, constant values are on the right-hand-side (rhs). Given a variable `x` which has to by lower than 10/3, the constraint would be formulated as \n",
-                "\n",
-                "$$ x \\le \\frac{10}{3} $$\n",
-                "\n",
-                "or\n",
+                "Minimize:\n",
+                "$$ x + 2y $$\n",
+                "      \n",
+                "subject to:\n",
                 "\n",
-                "$$ 3 x \\le 10 $$\n",
-                " \n",
-                "and **not** as \n",
-                "\n",
-                "$$ x - \\frac{3}{10} \\le 0 $$"
-            ]
-        },
-        {
-            "cell_type": "markdown",
-            "id": "6c6420a7",
-            "metadata": {},
-            "source": [
-                "## Using arithmetic operations\n",
-                "\n",
-                "Typically the lhs is given as a linear expression built by an arithmetic linear combination of variables, e.g.  "
-            ]
-        },
-        {
-            "cell_type": "code",
-            "execution_count": null,
-            "id": "6b496b92",
-            "metadata": {},
-            "outputs": [],
-            "source": [
-                "x = m.add_variables()"
+                "$$ x \\ge 0 $$\n",
+                "$$y \\ge 0 $$\n",
+                "$$3x + 7y \\ge 10 $$\n",
+                "$$5x + 2y \\ge 3 $$"
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "4c8aba7e",
+            "id": "dramatic-cannon",
             "metadata": {},
             "outputs": [],
-            "source": [
-                "lhs = 3 * x\n",
-                "lhs"
-            ]
+            "source": []
         },
         {
+            "attachments": {},
             "cell_type": "markdown",
-            "id": "ffe7dc45",
+            "id": "43949d36",
             "metadata": {},
             "source": [
-                "When applying one of the operators `<=`, `>=`, `==` to the expression, an unassigned constraint is built:"
+                "### Initializing a `Model`\n",
+                "\n",
+                "The Model class in Linopy is a fundamental part of the library. It serves as a container for all the relevant data associated with a linear optimization problem. This includes variables, constraints, and the objective function."
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "0301876e",
+            "id": "technical-conducting",
             "metadata": {},
             "outputs": [],
             "source": [
-                "con = lhs <= 10\n",
-                "con"
+                "from linopy import Model\n",
+                "m = Model()"
             ]
         },
         {
+            "attachments": {},
             "cell_type": "markdown",
-            "id": "0d75781d",
+            "id": "e5b16d53",
             "metadata": {},
             "source": [
-                "Why is it anonymous? Because it is not yet added to the model. We can inspect the elements of the anonymous constraint: "
+                "This creates a new Model object, which you can then use to define your optimization problem."
             ]
         },
         {
-            "cell_type": "code",
-            "execution_count": null,
-            "id": "01f182b5",
+            "attachments": {},
+            "cell_type": "markdown",
+            "id": "rolled-delicious",
             "metadata": {},
-            "outputs": [],
             "source": [
-                "con.lhs"
+                "\n",
+                "\n",
+                "### Adding variables\n",
+                "\n",
+                "Variables in a linear optimization problem represent the decision variables. A variable can always be assigned with a lower and an upper bound. In our case, both `x` and `y` have a lower bound of zero (default is unbouded). In Linopy, you can add variables to a Model using the `add_variables` method:"
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "783287b3",
+            "id": "protecting-power",
             "metadata": {},
             "outputs": [],
             "source": [
-                "con.rhs"
+                "x = m.add_variables(lower=0, name='x')\n",
+                "y = m.add_variables(lower=0, name='y');"
             ]
         },
         {
+            "attachments": {},
             "cell_type": "markdown",
-            "id": "aac468c3",
+            "id": "featured-maria",
             "metadata": {},
             "source": [
-                "We can now add the constraint to the model by passing the unassigned `Constraint` to the `.add_constraint` function. "
+                "`x` and `y` are linopy variables of the class `linopy.Variable`. Each of them contain all relevant information that define it. The `name` parameter is optional but can be useful for referencing the variables later."
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "0adf929b",
+            "id": "virtual-anxiety",
             "metadata": {},
             "outputs": [],
             "source": [
-                "c = m.add_constraints(con, name='my-constraint')\n",
-                "c"
+                "x"
             ]
         },
         {
+            "attachments": {},
             "cell_type": "markdown",
-            "id": "e78c2635",
+            "id": "sonic-rebate",
             "metadata": {},
             "source": [
-                "The same output would be generated if passing lhs, sign and rhs as separate arguments to the function:"
+                "Since both `x` and `y` are scalar variables (meaning they don't have any dimensions), their underlying data contain only one optimization variable each.  \n",
+                "\n",
+                "### Adding Constraints\n",
+                "\n",
+                "Constraints define the feasible region of the optimization problem. They consist of the left hand side (lhs) and the right hand side (rhs). The first constraint that we want to write down is \n",
+                "$3x + 7y >= 10$, which we write out exactly in the mathematical way"
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "c084adec",
+            "id": "fbb46cad",
             "metadata": {},
             "outputs": [],
             "source": [
-                "m.add_constraints(lhs, \"<=\", 10, name='the-same-constraint')"
+                "3*x + 7*y >= 10"
             ]
         },
         {
+            "attachments": {},
             "cell_type": "markdown",
-            "id": "2b4db4d5",
+            "id": "f4666bee",
             "metadata": {},
             "source": [
-                "Note that the return value of the operation is a `Constraint` which contains the reference labels to the constraints in the optimization model. Also is redirects to its lhs, sign and rhs, for example we can call"
+                "Note, we can also mix the constant and the variable expression, like this"
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "ea6e990c",
+            "id": "60f41b76",
             "metadata": {},
             "outputs": [],
             "source": [
-                "c.lhs"
+                "3*x + 7*y - 10 >= 0"
             ]
         },
         {
+            "attachments": {},
             "cell_type": "markdown",
-            "id": "e6ae2a19",
+            "id": "02abd938",
             "metadata": {},
             "source": [
-                "to inspect the lhs of a defined constraint."
-            ]
-        },
-        {
-            "cell_type": "markdown",
-            "id": "ab947d1a",
-            "metadata": {},
-            "source": [
-                "### Multiplication with arrays\n",
+                "... and linopy will automatically take over the separation of variables expression on the lhs, and constant values on the rhs.\n",
                 "\n",
-                "When multiplying variables with coefficients, the dimension handling follows the convention of `xarray`. That is, non-overlapping dimensions are spanned and broadcasted. For example, let's multiply `x` with an array going from 0 to 5: "
+                "The constraint is currently not assigned to the model. We assign it by calling the function `m.add_constraints`."
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "c73df0dd",
-            "metadata": {
-                "scrolled": true
-            },
+            "id": "hollywood-production",
+            "metadata": {},
             "outputs": [],
             "source": [
-                "coeff = xr.DataArray(np.arange(5), coords={'my-dim': pd.RangeIndex(5)})\n",
-                "coeff * x"
+                "m.add_constraints(3*x + 7*y >= 10)\n",
+                "m.add_constraints(5*x + 2*y >= 3);"
             ]
         },
         {
+            "attachments": {},
             "cell_type": "markdown",
-            "id": "f3437499",
+            "id": "global-maple",
             "metadata": {},
             "source": [
-                "Now, an expression of shape 5 with one term is created. \n",
+                "## Adding the Objective \n",
                 "\n",
-                "**Note:** It is strongly recommended to use `xarray.DataArray`'s for multiplying coefficients with `Variable`'s. It is also possible to use numpy arrays, however these are less secure considering the dimension handling. It is not recommended to use `pandas` objects, as these do not preserve the `linopy` types.  "
-            ]
-        },
-        {
-            "cell_type": "markdown",
-            "id": "9898f0c1",
-            "metadata": {},
-            "source": [
-                "## Using rules \n",
-                "\n",
-                "Similar to the implementation in Pyomo, expressions and constraints can be created using a combination of a function and a set of coordinates to iterate over. For creating expressions, the function itself has to return a `ScalarLinearExpression` which can be obtained by selecting single values of the variables are combining them: "
+                "The objective function defines what you want to optimize. You can set the objective function of a Model in Linopy using the add_objective method. For our example that would be"
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "a6125df8",
+            "id": "overall-exhibition",
             "metadata": {},
             "outputs": [],
             "source": [
-                "x[0]"
+                "m.add_objective(x + 2*y)"
             ]
         },
         {
+            "attachments": {},
             "cell_type": "markdown",
-            "id": "4f8bfddf",
+            "id": "6f9692aa",
             "metadata": {},
             "source": [
-                "For example"
+                "## Solving the Model\n",
+                "\n",
+                "Once you've defined your Model with variables, constraints, and an objective function, you can solve it using the `solve` method:"
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "ff76bbab",
+            "id": "pressing-copying",
             "metadata": {},
             "outputs": [],
             "source": [
-                "coords = pd.RangeIndex(10), [\"a\", \"b\"]\n",
-                "b = m.add_variables(0, 100, coords)\n",
-                "\n",
-                "def bound(m, i, j):\n",
-                "     if i % 2:\n",
-                "         return (i / 2) * b[i, j]\n",
-                "     else:\n",
-                "         return i * b[i, j]\n",
-                "\n",
-                "expr = m.linexpr(bound, coords)\n",
-                "expr"
+                "m.solve()"
             ]
         },
         {
+            "attachments": {},
             "cell_type": "markdown",
-            "id": "e6d3b069",
+            "id": "preceding-limit",
             "metadata": {},
             "source": [
-                "Note that the function's first argument has to be the model itself, even though it might not be used in the function."
+                "The solution of the linear problem assigned to the variables under `solution` in form of a `xarray.Dataset`. "
             ]
         },
         {
-            "cell_type": "markdown",
-            "id": "cf42a9e3",
+            "cell_type": "code",
+            "execution_count": null,
+            "id": "electric-duration",
             "metadata": {},
+            "outputs": [],
             "source": [
-                "This functionality is also supported by the `.add_constraints` function. When passing a function as a first argument, `.add_constraints` expects `coords` to by non-empty. The function itself has to return a `AnonymousScalarConstraint`, as done by "
+                "x.solution"
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "c993ba4b",
+            "id": "e6d31751",
             "metadata": {},
             "outputs": [],
             "source": [
-                "x[0] <= 3"
+                "y.solution"
             ]
         },
         {
+            "attachments": {},
             "cell_type": "markdown",
-            "id": "e9b76d72",
-            "metadata": {},
-            "source": [
-                "For example"
-            ]
-        },
-        {
-            "cell_type": "code",
-            "execution_count": null,
-            "id": "9f572cfc",
+            "id": "e296f641",
             "metadata": {},
-            "outputs": [],
             "source": [
-                "coords = pd.RangeIndex(10), [\"a\", \"b\"]\n",
-                "b = m.add_variables(0, 100, coords)\n",
-                "\n",
-                "def bound(m, i, j):\n",
-                "     if i % 2:\n",
-                "         return (i / 2) * b[i, j] >= i\n",
-                "     else:\n",
-                "         return i * b[i, j]  == 0.\n",
-                "\n",
-                "con = m.add_constraints(bound, coords=coords)\n",
-                "con"
+                "Well done! You solved your first linopy model!"
             ]
         }
     ],
     "metadata": {
         "@webio": {
             "lastCommId": null,
             "lastKernelId": null
```

### Comparing `linopy-0.2.1/examples/creating-variables.ipynb` & `linopy-0.2.2/examples/creating-expressions.ipynb`

 * *Files 16% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.9465178571428572%*

 * *Differences: {"'cells'": "{0: {'id': '4db583af', 'source': {insert: [(0, '# Creating Expressions\\n'), (2, 'In "*

 * *            'this notebook, we look at different options to create expressions. A strong focus '*

 * *            'will be set on the array-like operations: Since variables are represented in '*

 * *            'array-like structure, we benefit from a lot of well-knwon functionalities which we '*

 * *            "know from `numpy`, `pandas` or `xarray`.\\n'), (4, '\\n'), (5, 'These are for "*

 * *            "example\\n'), (6, ' […]*

```diff
@@ -1,339 +1,387 @@
 {
     "cells": [
         {
+            "attachments": {},
             "cell_type": "markdown",
-            "id": "e8249281",
+            "id": "4db583af",
             "metadata": {},
             "source": [
-                "# Creating variables\n",
+                "# Creating Expressions\n",
                 "\n",
-                "Variables are created and at the same time assigned to the model using the function \n",
+                "In this notebook, we look at different options to create expressions. A strong focus will be set on the array-like operations: Since variables are represented in array-like structure, we benefit from a lot of well-knwon functionalities which we know from `numpy`, `pandas` or `xarray`.\n",
                 "\n",
-                "```\n",
-                "model.add_variables\n",
-                "```\n",
-                "where `model` is a `linopy.Model` instance. In the following we show how this function works and what the resulting variables look like. So, let's create a model and go through it!"
+                "\n",
+                "These are for example\n",
+                "\n",
+                "- `arithmetic` operations to create expressions\n",
+                "- `broadcasting` to combine smaller and larger arrays\n",
+                "- `.loc` to select a subset of the original array using indexes\n",
+                "- `.where` to select where the variable or expression should be active or not\n",
+                "- `.shift` to shift the whole array along one dimension\n",
+                "- `.groupby` to group by a key and apply operations on the groups \n",
+                "- `.rolling` to perform a rolling operation and perform operations\n"
             ]
         },
         {
-            "cell_type": "code",
-            "execution_count": null,
-            "id": "e0c196e4",
+            "attachments": {},
+            "cell_type": "markdown",
+            "id": "f3712718",
             "metadata": {},
-            "outputs": [],
             "source": [
-                "from linopy import Model\n",
-                "import numpy as np\n",
-                "import pandas as pd\n",
-                "import xarray as xr\n",
-                "m = Model()"
+                ".. hint::\n",
+                "   Nearly all of the functions and properties, that can be accessed from a `Variable`, can be accesses from a `LinearExpression` and `QuadraticExpression`."
             ]
         },
         {
+            "attachments": {},
             "cell_type": "markdown",
-            "id": "6c6420a7",
+            "id": "95b25d13",
             "metadata": {},
             "source": [
-                "First of all it is crucial to know, that the return value of the `.add_variables` function is a `linopy.Variable` which is essentially like an `xarray.DataArray`, but it some additional features. That means it can have an arbitrary number of labeled dimensions. For each coordinate, exactly one representative scalar variable is defined. \n",
-                "\n",
-                "The first three arguments of the `.add_variables` function are \n",
-                "1. `lower` denoting the lower bound of the variables (default `-inf`) \n",
-                "2. `upper` denoting the upper bound (default `+inf`)\n",
-                "3. `coords` (default None). \n",
-                "These argument determine the shape of the added variable array. \n",
-                "\n",
-                "Generally, the function is strongly aligned to the initialization of an `xarray.DataArray`, meaning `lower` and `upper` can be \n",
-                "\n",
-                "* scalar values (int/float)\n",
-                "* numpy ndarray's\n",
-                "* pandas Series\n",
-                "* pandas DataFrame's\n",
-                "* xarray DataArray's\n",
+                "Let's start by creating a model."
+            ]
+        },
+        {
+            "cell_type": "code",
+            "execution_count": null,
+            "id": "close-maximum",
+            "metadata": {},
+            "outputs": [],
+            "source": [
+                "import linopy\n",
+                "import pandas as pd\n",
+                "import xarray as xr\n",
                 "\n",
+                "time = pd.Index(range(10), name='time')\n",
+                "port = pd.Index(list('abcd'), name='port')\n",
                 "\n",
-                "Note that scalars, numpy objects and pandas objects do not have or do not require dimension names. Thus, the naming of the dimensions are done by `xarray` if not explicitly passing `coords`. As we show later, it is very important to take care of the dimension names.    "
+                "m = linopy.Model()\n",
+                "x = m.add_variables(lower=0, coords=[time], name='x')\n",
+                "y = m.add_variables(lower=0, coords=[time, port], name='y')\n",
+                "m"
             ]
         },
         {
+            "attachments": {},
             "cell_type": "markdown",
-            "id": "a2283b9a",
+            "id": "582a0cad",
             "metadata": {},
             "source": [
-                "## Using scalar values\n",
+                "## Arithmetic Operations\n",
+                "\n",
+                "Arithmetic operations such as addition (`+`), subtraction (`-`), multiplication (`*`) can be used directly on the variables and expressions in Linopy. These operations are applied element-wise on the variables.\n",
                 "\n",
-                "If we just keep the default, which is `-inf` and `+inf` for `lower` and `upper`, the code returns"
+                "For example, if you want to create a new combined expr `z` that is the sum of `x` and `y`, you can do so as follows:"
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "ee589323",
+            "id": "0aec195a",
             "metadata": {},
             "outputs": [],
             "source": [
-                "m.add_variables()"
+                "z = x + y\n",
+                "z"
             ]
         },
         {
+            "attachments": {},
             "cell_type": "markdown",
-            "id": "de3f227e",
+            "id": "8c4b9ea6",
             "metadata": {},
             "source": [
-                "which is a variable without any coordinates and with just one scalar variable with label `0`. \n",
-                "You can pass any scalar to the lower and upper bounds, e.g."
+                ".. note::\n",
+                "   In the addition, the variable `x` is broadcasted and the return value has the same set of dimensions as `y`.  "
+            ]
+        },
+        {
+            "attachments": {},
+            "cell_type": "markdown",
+            "id": "a1de2b9a",
+            "metadata": {},
+            "source": [
+                "Similarly, you can subtract `y` from `x` or multiply `x` and `y` as follows:"
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "1b0ea3d6",
+            "id": "c56761cd",
             "metadata": {},
             "outputs": [],
             "source": [
-                "m.add_variables(lower=9, upper=15)"
+                "z = x - y\n",
+                "z"
             ]
         },
         {
+            "cell_type": "code",
+            "execution_count": null,
+            "id": "b59fa397",
+            "metadata": {},
+            "outputs": [],
+            "source": [
+                "z = x * y\n",
+                "z"
+            ]
+        },
+        {
+            "attachments": {},
             "cell_type": "markdown",
-            "id": "e7b0c023",
+            "id": "0ca00a73",
             "metadata": {},
             "source": [
-                "If `coords` is given, these will be ignored. "
+                "In all cases, the returned shape is the same. Note that, the output type of the multiplication is a `QuadraticExpression` and not a `LinearExpression`.\n"
             ]
         },
         {
+            "attachments": {},
             "cell_type": "markdown",
-            "id": "437cc7a1",
+            "id": "3ff0d1cd",
             "metadata": {},
             "source": [
-                "## Using numpy arrays\n",
-                "\n",
-                "If `lower` and `upper` are numpy arrays, `linopy` requires the `coords` argument not to be `None`, otherwise an error is raised. Thus, it is helpful to define the coordinates in advance and pass it to the function."
+                "The `z` expression, which carries along `x` and `y`, has different attributes such as `coord_dims`, `dims`, `size`."
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "0fe33c34",
-            "metadata": {
-                "scrolled": true
-            },
+            "id": "35c7331f",
+            "metadata": {},
             "outputs": [],
             "source": [
-                "coords = pd.RangeIndex(2, name='a'),\n",
-                "lower=np.array([1,2])\n",
-                "m.add_variables(lower=lower, coords=coords)"
+                "z.coord_dims"
             ]
         },
         {
+            "attachments": {},
             "cell_type": "markdown",
-            "id": "5052b9b5",
+            "id": "f7578221",
             "metadata": {},
             "source": [
-                "**Note three things:** \n",
-                "\n",
-                "1. `coords` is an tuple of indexes as expected by `xarray.DataArray`. \n",
-                "2. The shape of `lower` is aligned with `coords`.\n",
-                "3. A name was set in the index creation. This is helpful as we can ensure which dimension the variable is defined on. Otherwise `xarray` would just insert the dimension names which can lead to unexpected broadcasting later\n",
-                "\n",
-                "Let's make the same example without adding the dimension name to the index:"
+                ".. important::\n",
+                "   When combining variables or expression with dimensions of the same name and size, the first object will determine the coordinates of the resulting expression. For example: "
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "5f0994da",
+            "id": "8c511f35",
             "metadata": {},
             "outputs": [],
             "source": [
-                "coords = pd.RangeIndex(2),\n",
-                "m.add_variables(lower=lower, coords=coords)"
+                "other_time = pd.Index(range(10, 20), name='time')\n",
+                "b = m.add_variables(coords=[other_time], name='b')\n",
+                "b"
             ]
         },
         {
+            "attachments": {},
             "cell_type": "markdown",
-            "id": "dff8126d",
+            "id": "59f43468",
             "metadata": {},
             "source": [
-                "The dimension is now called `dim_0`, any new assignment of variable without dimension names, will also try to use that dimension name. This is not recommended as it possibly bloats the data structure of the model. \n",
-                "\n",
-                "**Hint:**\n",
-                "If you want to make sure, you are not messing up with dimensions, create the model with the flag `force_dim_names = True`, i.e."
+                "`b` has the same shape as `x`, but they have different coordinates. When we combine `x` and `b` the coordinates on dimension `time` will be taken from the first object and the coordinates of the subsequent object will be ignored:"
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "d133a7a4",
+            "id": "26edd6ab",
             "metadata": {},
             "outputs": [],
             "source": [
-                "other = Model(force_dim_names=True)\n",
-                "try: \n",
-                "    other.add_variables(lower=lower, coords=coords)\n",
-                "except ValueError as e:\n",
-                "    print(\"This raised an error:\", e)"
+                "x + b"
             ]
         },
         {
+            "attachments": {},
             "cell_type": "markdown",
-            "id": "9203ff16",
+            "id": "de6d3073",
             "metadata": {},
             "source": [
-                "## Using pandas objects\n",
+                "## Using `.loc` to select a subset\n",
+                "\n",
+                "The `.loc` function allows you to select a subset of the array using indexes. This is useful when you want to apply operations to a specific subset of your variables.\n",
                 "\n",
-                "Pandas objects always have indexes but do not require dimension names. It is again helpful to ensure that the variable have explicit dimension names, when passing `lower` and `upper` without `coords`. This can be done by either passing the `dims` argument to the `.add_variables` function, i.e."
+                "For example, if you want to apply a summation to the variables `x` and `y` only for the first 5 time steps, you can do so as follows:"
+            ]
+        },
+        {
+            "cell_type": "code",
+            "execution_count": null,
+            "id": "93119cfc",
+            "metadata": {},
+            "outputs": [],
+            "source": [
+                "x.loc[:5]"
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "2cf719be",
+            "id": "ae6a1b29",
             "metadata": {},
             "outputs": [],
             "source": [
-                "lower = pd.Series([1,1])\n",
-                "upper = pd.Series([10, 12])\n",
-                "m.add_variables(lower, upper, dims='my-dim')"
+                "x.loc[:5] + y.loc[:5] "
             ]
         },
         {
+            "attachments": {},
             "cell_type": "markdown",
-            "id": "3a4cf2d4",
+            "id": "14b02f7d",
             "metadata": {},
             "source": [
-                "or naming the indexes and columns of the pandas objects directly, e.g."
+                "which is the same as"
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "61896a6f",
+            "id": "7281f08c",
             "metadata": {},
             "outputs": [],
             "source": [
-                "lower = pd.Series([1,1]).rename_axis('my-dim')\n",
-                "upper = pd.Series([10, 12]).rename_axis('my-dim')\n",
-                "m.add_variables(lower, upper)"
+                "expr = x + y\n",
+                "expr.loc[:5]"
             ]
         },
         {
+            "attachments": {},
             "cell_type": "markdown",
-            "id": "2b462ff9",
+            "id": "c3c97abf",
             "metadata": {},
             "source": [
-                "**Note:** If `lower` and `upper` do not have the same dimension names, the arrays are broadcasted, meaning the dimensions are spanned: "
+                "In combination with the overwrite of the coordinates, this is useful when you need to combine different selections, like"
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "6ffd5a4e",
-            "metadata": {
-                "scrolled": true
-            },
+            "id": "27063ea9",
+            "metadata": {},
             "outputs": [],
             "source": [
-                "lower = pd.Series([1,1]).rename_axis('my-dim')\n",
-                "upper = pd.Series([10, 12]).rename_axis('my-other-dim')\n",
-                "m.add_variables(lower, upper)"
+                "x.loc[:4] + y.loc[5:]"
             ]
         },
         {
+            "attachments": {},
             "cell_type": "markdown",
-            "id": "31bbdbab",
+            "id": "cdb53f49",
             "metadata": {},
             "source": [
-                "Now instead of 2 variables, 4 variables were defined.  \n",
+                "## Using `.where` to select active variables or expressions\n",
                 "\n",
-                "The similar bahvior accounts for the case when passing a DataFrame and a Series without dimension names. The index axis is the first axis of both object, thus these are expected to be the same (Note that pandas convention, is that Series are aligned and broadcasted along the column dimension of DataFrames):  "
+                "The `.where` function allows you to select where the variable or expression should be active or not. This is useful when you want to apply constraints or operations only to a specific subset of your variables based on a condition. It is quite similar to the functionality of masking, that we showed earlier.\n",
+                "\n",
+                "For example, if you want to create an sum of the variables `x` and `y` where `time` is greater than 2, you can do so as follows:"
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "fa2adc81",
+            "id": "ab8f59fd",
             "metadata": {},
             "outputs": [],
             "source": [
-                "lower = pd.DataFrame([[1,1, 2], [1,2,2]])\n",
-                "upper = pd.Series([10, 12])\n",
-                "m.add_variables(lower, upper)"
+                "mask = xr.DataArray(time > 2, coords=[time])\n",
+                "(x + y).where(mask)"
             ]
         },
         {
+            "attachments": {},
             "cell_type": "markdown",
-            "id": "8b1734df",
+            "id": "3ee10a58",
             "metadata": {},
             "source": [
-                "Again, one is always safer when explicitly naming the dimensions:"
+                "We can use this to make a conditional summation:"
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "21f7db15",
+            "id": "21fa9664",
             "metadata": {},
             "outputs": [],
             "source": [
-                "lower = lower.rename_axis(index='my-dim', columns='my-other-dim')\n",
-                "upper = upper.rename_axis('my-dim')\n",
-                "m.add_variables(lower, upper)"
+                "(x + y).where(mask) + xr.DataArray(5, coords=[time]).where(~mask, 0)"
             ]
         },
         {
+            "attachments": {},
             "cell_type": "markdown",
-            "id": "77e264e2",
+            "id": "652973ea",
             "metadata": {},
             "source": [
-                "The `coords` and `dims` argument is applied to `lower` and `upper` individually. Hence, when mixing array's of different shapes, setting `coords` or `dims` will raised an error:"
+                "## Using `.shift` to shift the Variable along one dimension\n",
+                "\n",
+                "The `.shift` function allows you to shift the whole array along one dimension. This is useful when you want to apply constraints or operations that involve a time delay or a shift in the time steps.\n",
+                "\n",
+                "For example, if you want to apply a constraint that involves a one time step delay in the variables `x` and `y`, you can do so as follows:"
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "d0fc67cf",
+            "id": "organized-hampshire",
             "metadata": {},
             "outputs": [],
             "source": [
-                "coords = pd.Index([1,2]), pd.Index([3,4,5])\n",
-                "try:\n",
-                "    m.add_variables(lower, upper, coords=coords)\n",
-                "except ValueError as e:\n",
-                "    print(\"This raises an error:\", e)"
+                "y - y.shift(time=1)"
             ]
         },
         {
+            "attachments": {},
             "cell_type": "markdown",
-            "id": "f8bd2484",
+            "id": "eaf3f38c",
             "metadata": {},
             "source": [
-                "## Using xarray DataArray's\n",
+                "## Using `.groupby` to group by a key and apply operations on the groups\n",
+                "\n",
+                "The `.groupby` function allows you to group by a key and apply operations on the groups. This is useful when you want to apply constraints or operations that involve a grouping of the time steps or any other dimension.\n",
                 "\n",
-                "This is the most straight-forward and recommended method to create variables, as DataArray's have a well defined set of dimension names. "
+                "For example, if you want to apply a constraint that involves the sum of `x` and `y` over every two time steps, you can do so as follows:"
             ]
         },
         {
             "cell_type": "code",
             "execution_count": null,
-            "id": "e7a08f1e",
+            "id": "5170d187",
             "metadata": {},
             "outputs": [],
             "source": [
-                "lower = xr.DataArray([1,2,3], coords=(pd.RangeIndex(3),), dims='my-dim')\n",
-                "m.add_variables(lower)"
+                "group_key = pd.Series(time.values // 2, index=time)\n",
+                "(x + y).groupby(group_key).sum() "
             ]
         },
         {
+            "attachments": {},
             "cell_type": "markdown",
-            "id": "3f7bbbcb",
+            "id": "7ded9a54",
+            "metadata": {},
+            "source": [
+                "## Using `.rolling` to perform a rolling operation\n",
+                "\n",
+                "The `.rolling` function allows you to perform a rolling operation and apply operations. This is useful when you want to apply constraints or operations that involve a rolling window of the time steps or any other dimension.\n",
+                "\n",
+                "For example, if you want to apply a constraint that involves the sum of `x` over a rolling window of 3 time steps, you can do so as follows:"
+            ]
+        },
+        {
+            "cell_type": "code",
+            "execution_count": null,
+            "id": "d703fb70",
             "metadata": {},
+            "outputs": [],
             "source": [
-                "Again, you can arbitrarily broadcast dimensions when passing DataArray's with different set of dimensions. Note however, linopy expects non empty coordinates, it order to keep the model structure clean. "
+                "x.rolling(time=3).sum()"
             ]
         }
     ],
     "metadata": {
         "@webio": {
             "lastCommId": null,
             "lastKernelId": null
@@ -349,13 +397,13 @@
                 "version": 3
             },
             "file_extension": ".py",
             "mimetype": "text/x-python",
             "name": "python",
             "nbconvert_exporter": "python",
             "pygments_lexer": "ipython3",
-            "version": "3.10.5"
+            "version": "3.11.3"
         }
     },
     "nbformat": 4,
     "nbformat_minor": 5
 }
```

### Comparing `linopy-0.2.1/examples/solve-on-remote.ipynb` & `linopy-0.2.2/examples/solve-on-remote.ipynb`

 * *Files 2% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.9856897937759883%*

 * *Differences: {"'cells'": "{0: {'source': {insert: [(0, '# Solve on a Server\\n')], delete: [0]}}, 2: "*

 * *            "{'execution_count': 6, 'outputs': {0: {'data': {'text/plain': {insert: [(0, 'Linopy "*

 * *            "LP model\\n'), (1, '===============\\n'), (5, ' * x (dim_0, dim_1)\\n'), (6, ' * y "*

 * *            "(dim_0, dim_1)\\n'), (10, ' * con0 (dim_0, dim_1)\\n'), (11, ' * con1 (dim_0, "*

 * *            "dim_1)\\n')], delete: [21, 20, 19, 18, 17, 16, 15, 11, 10, 9, 8, 7, 6, 5, 1, 0]}}, "*

 * *            "'execution_count': 6} […]*

```diff
@@ -1,15 +1,15 @@
 {
     "cells": [
         {
             "cell_type": "markdown",
             "id": "4db583af",
             "metadata": {},
             "source": [
-                "# Solve a model on a remote machine\n",
+                "# Solve on a Server\n",
                 "\n",
                 "In this example, we explain how linopy can handle model optimization on remote machines. \n",
                 "What you need in order to run the example:\n",
                 "* a running installation of paramiko on your local machine (use `pip install paramiko` for example)\n",
                 "* a remote server with an working installation of linopy, e.g. in a `conda` environment.\n",
                 "* a working ssh access to that machine \n",
                 "\n",
@@ -33,64 +33,55 @@
                 "## Create a model\n",
                 "\n",
                 "First we are going to build the optimization model we want to solve in our local process."
             ]
         },
         {
             "cell_type": "code",
-            "execution_count": 1,
+            "execution_count": 6,
             "id": "dramatic-cannon",
             "metadata": {},
             "outputs": [
                 {
                     "data": {
                         "text/plain": [
-                            "Linopy model\n",
-                            "============\n",
+                            "Linopy LP model\n",
+                            "===============\n",
                             "\n",
                             "Variables:\n",
                             "----------\n",
-                            "Dimensions:  (dim_0: 10, dim_1: 10)\n",
-                            "Coordinates:\n",
-                            "  * dim_0    (dim_0) int64 0 1 2 3 4 5 6 7 8 9\n",
-                            "  * dim_1    (dim_1) int64 0 1 2 3 4 5 6 7 8 9\n",
-                            "Data:\n",
-                            "    x        (dim_0, dim_1) int64 0 1 2 3 4 5 6 7 8 ... 92 93 94 95 96 97 98 99\n",
-                            "    y        (dim_0, dim_1) int64 100 101 102 103 104 ... 195 196 197 198 199\n",
+                            " * x (dim_0, dim_1)\n",
+                            " * y (dim_0, dim_1)\n",
                             "\n",
                             "Constraints:\n",
                             "------------\n",
-                            "Dimensions:  (dim_0: 10, dim_1: 10)\n",
-                            "Coordinates:\n",
-                            "  * dim_0    (dim_0) int64 0 1 2 3 4 5 6 7 8 9\n",
-                            "  * dim_1    (dim_1) int64 0 1 2 3 4 5 6 7 8 9\n",
-                            "Data:\n",
-                            "    con0     (dim_0, dim_1) int64 0 1 2 3 4 5 6 7 8 ... 92 93 94 95 96 97 98 99\n",
-                            "    con1     (dim_0, dim_1) int64 100 101 102 103 104 ... 195 196 197 198 199\n",
+                            " * con0 (dim_0, dim_1)\n",
+                            " * con1 (dim_0, dim_1)\n",
                             "\n",
                             "Status:\n",
                             "-------\n",
                             "initialized"
                         ]
                     },
-                    "execution_count": 1,
+                    "execution_count": 6,
                     "metadata": {},
                     "output_type": "execute_result"
                 }
             ],
             "source": [
                 "from linopy import Model\n",
                 "from numpy import arange\n",
+                "from xarray import DataArray\n",
                 "\n",
                 "N = 10\n",
                 "m = Model()\n",
                 "coords = [arange(N), arange(N)]\n",
                 "x = m.add_variables(coords=coords, name='x')\n",
                 "y = m.add_variables(coords=coords, name='y')\n",
-                "m.add_constraints(x - y >= arange(N))\n",
+                "m.add_constraints(x - y >= DataArray(arange(N)))\n",
                 "m.add_constraints(x + y >= 0)\n",
                 "m.add_objective((2 * x + y).sum())\n",
                 "m"
             ]
         },
         {
             "cell_type": "markdown",
@@ -605,22 +596,14 @@
                     "metadata": {},
                     "output_type": "execute_result"
                 }
             ],
             "source": [
                 "m.solution"
             ]
-        },
-        {
-            "cell_type": "code",
-            "execution_count": null,
-            "id": "b1ab3037",
-            "metadata": {},
-            "outputs": [],
-            "source": []
         }
     ],
     "metadata": {
         "@webio": {
             "lastCommId": null,
             "lastKernelId": null
         },
@@ -635,13 +618,13 @@
                 "version": 3
             },
             "file_extension": ".py",
             "mimetype": "text/x-python",
             "name": "python",
             "nbconvert_exporter": "python",
             "pygments_lexer": "ipython3",
-            "version": "3.10.5"
+            "version": "3.11.3"
         }
     },
     "nbformat": 4,
     "nbformat_minor": 5
 }
```

### Comparing `linopy-0.2.1/linopy/__init__.py` & `linopy-0.2.2/linopy/__init__.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/linopy/common.py` & `linopy-0.2.2/linopy/common.py`

 * *Files 7% similar despite different names*

```diff
@@ -19,14 +19,15 @@
 
 from linopy.config import options
 from linopy.constants import (
     HELPER_DIMS,
     SIGNS,
     TERM_DIM,
     SIGNS_alternative,
+    SIGNS_pretty,
     sign_replace_dict,
 )
 
 
 def maybe_replace_sign(sign):
     if sign in SIGNS_alternative:
         return sign_replace_dict[sign]
@@ -51,21 +52,24 @@
         if dims is not None:
             dims = [axis.name or list(dims)[i] for i, axis in enumerate(arr.axes)]
         if coords is not None and not isinstance(coords, list):
             coords = {dim: coords[dim] for dim in dims}
         arr = DataArray(arr, coords=coords, dims=dims, **kwargs)
 
     elif isinstance(arr, np.ndarray):
-        dims = list(dims)[: arr.ndim] if dims else []
+        ndim = max(arr.ndim, 0 if coords is None else len(coords))
 
-        if isinstance(coords, list):
+        if dims is not None and len(dims):
+            # ensure dims is defined for ndim
+            dims = list(dims)[:ndim] if dims else []
+            dims = dims + [f"dim_{i}" for i in range(len(dims), ndim)]
+
+        if isinstance(coords, list) and dims is not None and len(dims):
             coords = dict(zip(dims, coords))
 
-        if len(dims) < arr.ndim:
-            dims = list(dims) + [f"dim_{i}" for i in range(len(dims), arr.ndim)]
         arr = DataArray(arr, coords=coords, dims=dims, **kwargs)
 
     elif isinstance(arr, (np.number, int, float, str, bool, list)):
         arr = DataArray(arr, coords=coords, dims=dims, **kwargs)
 
     elif not isinstance(arr, DataArray):
         supported_types = [
@@ -196,14 +200,48 @@
             if d in line:
                 parts = line.split(d)
                 formatted_line = f"{parts[0]:<{max_pos}}{d} {parts[1].strip()}"
         formatted_lines.append(formatted_line)
     return formatted_lines
 
 
+def get_label_position(obj, values):
+    """
+    Get tuple of name and coordinate for variable labels.
+    """
+
+    def find_single(value):
+        if value == -1:
+            return None, None
+        for name, val in obj.items():
+            labels = val.labels
+            start, stop = val.range
+
+            if value >= start and value < stop:
+                index = np.unravel_index(value - start, labels.shape)
+
+                # Extract the coordinates from the indices
+                coord = {
+                    dim: labels.indexes[dim][i] for dim, i in zip(labels.dims, index)
+                }
+
+                # Add the name of the DataArray and the coordinates to the result list
+                return name, coord
+
+    ndim = np.array(values).ndim
+    if ndim == 0:
+        return find_single(values)
+    elif ndim == 1:
+        return [find_single(v) for v in values]
+    elif ndim == 2:
+        return [[find_single(v) for v in _] for _ in values.T]
+    else:
+        raise ValueError("Array's with more than two dimensions is not supported")
+
+
 def print_coord(coord):
     if isinstance(coord, dict):
         coord = coord.values()
     return "[" + ", ".join([str(c) for c in coord]) + "]" if len(coord) else ""
 
 
 def print_single_variable(model, label):
@@ -285,14 +323,29 @@
         if residual != " None":
             res += residual
         return res
     expr = list(zip(c, model.variables.get_label_position(v)))
     return print_line(expr, const)
 
 
+def print_single_constraint(model, label):
+    constraints = model.constraints
+    name, coord = constraints.get_label_position(label)
+
+    coeffs = model.constraints[name].coeffs.sel(coord).values
+    vars = model.constraints[name].vars.sel(coord).values
+    sign = model.constraints[name].sign.sel(coord).item()
+    rhs = model.constraints[name].rhs.sel(coord).item()
+
+    expr = print_single_expression(coeffs, vars, 0, model)
+    sign = SIGNS_pretty[sign]
+
+    return f"{name}{print_coord(coord)}: {expr} {sign} {rhs:.12g}"
+
+
 def has_optimized_model(func):
     """
     Check if a reference model is set.
     """
 
     @wraps(func)
     def wrapper(self, *args, **kwargs):
```

### Comparing `linopy-0.2.1/linopy/config.py` & `linopy-0.2.2/linopy/config.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/linopy/constants.py` & `linopy-0.2.2/linopy/constants.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/linopy/constraints.py` & `linopy-0.2.2/linopy/constraints.py`

 * *Files 2% similar despite different names*

```diff
@@ -23,18 +23,20 @@
 
 from linopy import expressions, variables
 from linopy.common import (
     LocIndexer,
     align_lines_by_delimiter,
     forward_as_properties,
     generate_indices_for_printout,
+    get_label_position,
     has_optimized_model,
     is_constant,
     maybe_replace_signs,
     print_coord,
+    print_single_constraint,
     print_single_expression,
     replace_by_map,
     save_join,
 )
 from linopy.config import options
 from linopy.constants import (
     EQUAL,
@@ -697,14 +699,35 @@
         if not isinstance(label, (float, int)) or label < 0:
             raise ValueError("Label must be a positive number.")
         for name, ds in self.items():
             if label in ds.labels:
                 return name
         raise ValueError(f"No constraint found containing the label {label}.")
 
+    def get_label_position(self, values):
+        """
+        Get tuple of name and coordinate for constraint labels.
+        """
+        return get_label_position(self, values)
+
+    def print_labels(self, values, display_max_terms=None):
+        """
+        Print a selection of labels of the constraints.
+
+        Parameters
+        ----------
+        values : list, array-like
+            One dimensional array of constraint labels.
+        """
+        with options as opts:
+            if display_max_terms is not None:
+                opts.set_value(display_max_terms=display_max_terms)
+            res = [print_single_constraint(self.model, v) for v in values]
+        print("\n".join(res))
+
     def set_blocks(self, block_map):
         """
         Get a dataset of same shape as constraints.labels with block values.
 
         Let N be the number of blocks.
         The following cases are considered:
```

### Comparing `linopy-0.2.1/linopy/expressions.py` & `linopy-0.2.2/linopy/expressions.py`

 * *Files 1% similar despite different names*

```diff
@@ -4,14 +4,15 @@
 Linopy expressions module.
 
 This module contains definition related to affine expressions.
 """
 
 import functools
 import logging
+import warnings
 from dataclasses import dataclass, field
 from itertools import product, zip_longest
 from typing import Any, Mapping, Union
 
 import numpy as np
 import pandas as pd
 import xarray as xr
@@ -159,14 +160,17 @@
             int_map = None
             if isinstance(group, pd.DataFrame):
                 int_map = get_index_map(*group.values.T)
                 orig_group = group
                 group = group.apply(tuple, axis=1).map(int_map)
 
             group_dim = group.index.name
+            if group_name == group_dim:
+                raise ValueError("Group name cannot be the same as group dimension")
+
             arrays = [group, group.groupby(group).cumcount()]
             idx = pd.MultiIndex.from_arrays(
                 arrays, names=[group_name, GROUPED_TERM_DIM]
             )
             ds = self.data.assign_coords({group_dim: idx})
             ds = ds.unstack(group_dim, fill_value=LinearExpression._fill_value)
             ds = LinearExpression._sum(ds, dims=GROUPED_TERM_DIM)
@@ -175,22 +179,20 @@
                 index = ds.indexes["group"].map({v: k for k, v in int_map.items()})
                 index.names = orig_group.columns
                 index.name = group_name
                 ds = xr.Dataset(ds.assign_coords({group_name: index}))
 
             return LinearExpression(ds, self.model)
 
-        else:
-
-            def func(ds):
-                ds = LinearExpression._sum(ds, self.groupby._group_dim)
-                ds = ds.assign_coords({TERM_DIM: np.arange(len(ds._term))})
-                return ds
+        def func(ds):
+            ds = LinearExpression._sum(ds, self.groupby._group_dim)
+            ds = ds.assign_coords({TERM_DIM: np.arange(len(ds._term))})
+            return ds
 
-            return self.map(func, **kwargs)
+        return self.map(func, **kwargs)
 
     def roll(self, **kwargs):
         """
         Roll the groupby object.
 
         **kwargs
             Arbitrary keyword arguments.
```

### Comparing `linopy-0.2.1/linopy/io.py` & `linopy-0.2.2/linopy/io.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/linopy/matrices.py` & `linopy-0.2.2/linopy/matrices.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/linopy/model.py` & `linopy-0.2.2/linopy/model.py`

 * *Files 1% similar despite different names*

```diff
@@ -11,14 +11,15 @@
 import warnings
 from pathlib import Path
 from tempfile import NamedTemporaryFile, gettempdir
 
 import numpy as np
 import pandas as pd
 import xarray as xr
+from deprecation import deprecated
 from numpy import inf, nan
 from xarray import DataArray, Dataset
 
 from linopy import solvers
 from linopy.common import (
     as_dataarray,
     best_int,
@@ -1086,24 +1087,25 @@
                     vals = dual[idx].values.reshape(con.labels.shape)
                 except KeyError:
                     vals = dual.reindex(idx).values.reshape(con.labels.shape)
                 con.dual = xr.DataArray(vals, con.labels.coords)
 
         return result.status.status.value, result.status.termination_condition.value
 
-    def compute_set_of_infeasible_constraints(self):
+    def compute_infeasibilities(self):
         """
         Compute a set of infeasible constraints.
 
-        This method requires gurobipy to be running.
+        This function requires that the model was solved with `gurobi` and the
+        termination condition was infeasible.
 
         Returns
         -------
-        labels : xr.DataArray
-            Labels of the infeasible constraints. Labels with value -1 are not in the set.
+        labels : list
+            Labels of the infeasible constraints.
         """
         if "gurobi" not in available_solvers:
             raise ImportError("Gurobi is required for this method.")
 
         import gurobipy
 
         solver_model = getattr(self, "solver_model")
@@ -1115,14 +1117,42 @@
         f = NamedTemporaryFile(suffix=".ilp", prefix="linopy-iis-", delete=False)
         solver_model.write(f.name)
         labels = []
         for line in f.readlines():
             line = line.decode()
             if line.startswith(" c"):
                 labels.append(int(line.split(":")[0][2:]))
+        return labels
+
+    def print_infeasibilities(self, display_max_terms=None):
+        """
+        Print a list of infeasible constraints.
+
+        This function requires that the model was solved with `gurobi` and the
+        termination condition was infeasible.
+        """
+        labels = self.compute_infeasibilities()
+        self.constraints.print_labels(labels, display_max_terms=display_max_terms)
+
+    @deprecated(
+        details="Use `compute_infeasibilities`/`print_infeasibilities` instead."
+    )
+    def compute_set_of_infeasible_constraints(self):
+        """
+        Compute a set of infeasible constraints.
+
+        This function requires that the model was solved with `gurobi` and the
+        termination condition was infeasible.
+
+        Returns
+        -------
+        labels : xr.DataArray
+            Labels of the infeasible constraints. Labels with value -1 are not in the set.
+        """
+        labels = self.compute_infeasibilities()
         cons = self.constraints.labels.isin(np.array(labels))
         subset = self.constraints.labels.where(cons, -1)
         subset = subset.drop_vars(
             [k for (k, v) in (subset == -1).all().items() if v.item()]
         )
         return subset
```

### Comparing `linopy-0.2.1/linopy/monkey_patch_xarray.py` & `linopy-0.2.2/linopy/monkey_patch_xarray.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/linopy/remote.py` & `linopy-0.2.2/linopy/remote.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/linopy/solvers.py` & `linopy-0.2.2/linopy/solvers.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/linopy/testing.py` & `linopy-0.2.2/linopy/testing.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/linopy/variables.py` & `linopy-0.2.2/linopy/variables.py`

 * *Files 0% similar despite different names*

```diff
@@ -22,14 +22,15 @@
 import linopy.expressions as expressions
 from linopy.common import (
     LocIndexer,
     as_dataarray,
     fill_missing_coords,
     forward_as_properties,
     generate_indices_for_printout,
+    get_label_position,
     has_optimized_model,
     is_constant,
     print_coord,
     print_single_variable,
     save_join,
 )
 from linopy.config import options
@@ -948,43 +949,27 @@
         """
         return self[name].range
 
     def get_label_position(self, values):
         """
         Get tuple of name and coordinate for variable labels.
         """
+        return get_label_position(self, values)
 
-        def find_single(value):
-            if value == -1:
-                return None, None
-            for name, var in self.items():
-                labels = var.labels
-                start, stop = var.range
-
-                if value >= start and value < stop:
-                    index = np.unravel_index(value - start, labels.shape)
-
-                    # Extract the coordinates from the indices
-                    coord = {
-                        dim: labels.indexes[dim][i]
-                        for dim, i in zip(labels.dims, index)
-                    }
-
-                    # Add the name of the DataArray and the coordinates to the result list
-                    return name, coord
-
-        ndim = np.array(values).ndim
-        if ndim == 0:
-            return find_single(values)
-        elif ndim == 1:
-            return [find_single(v) for v in values]
-        elif ndim == 2:
-            return [[find_single(v) for v in _] for _ in values.T]
-        else:
-            raise ValueError("Array's with more than two dimensions is not supported")
+    def print_labels(self, values):
+        """
+        Print a selection of labels of the variables.
+
+        Parameters
+        ----------
+        values : list, array-like
+            One dimensional array of constraint labels.
+        """
+        res = [print_single_variable(self.model, v) for v in values]
+        print("\n".join(res))
 
     @deprecated("0.2", details="Use `to_dataframe` or `flat` instead.")
     def iter_ravel(self, key, filter_missings=False):
         """
         Create an generator which iterates over all arrays in `key` and
         flattens them.
```

### Comparing `linopy-0.2.1/linopy.egg-info/PKG-INFO` & `linopy-0.2.2/linopy.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: linopy
-Version: 0.2.1
+Version: 0.2.2
 Summary: Linear optimization with N-D labeled arrays in Python
 Home-page: https://github.com/PyPSA/linopy
 Author: Fabian Hofmann
 Author-email: hofmann@fias.uni-frankfurt.de
 License: MIT
 Classifier: Development Status :: 3 - Alpha
 Classifier: Environment :: Console
```

### Comparing `linopy-0.2.1/linopy.egg-info/SOURCES.txt` & `linopy-0.2.2/linopy.egg-info/SOURCES.txt`

 * *Files 3% similar despite different names*

```diff
@@ -66,35 +66,44 @@
 benchmark/scripts/leftovers/benchmarks-pypsa-eur/__pycache__/plot-benchmarks.cpython-310.pyc
 doc/Makefile
 doc/api.rst
 doc/benchmark.png
 doc/benchmark.rst
 doc/conf.py
 doc/contributing.rst
+doc/create-a-model-with-coordinates.nblink
 doc/create-a-model.nblink
 doc/creating-constraints.nblink
+doc/creating-expressions.nblink
 doc/creating-variables.nblink
 doc/index.rst
+doc/infeasible-model.nblink
 doc/logo.pdf
 doc/logo.png
 doc/logo.py
 doc/make.bat
 doc/manipulating-models.nblink
 doc/migrating-from-pyomo.nblink
+doc/prerequisites.rst
 doc/release_notes.rst
 doc/solve-on-remote.nblink
-doc/solvers.rst
 doc/syntax.rst
+doc/testing-framework.nblink
+doc/user-guide.rst
 doc/_static/theme_overrides.css
+examples/create-a-model-with-coordinates.ipynb
 examples/create-a-model.ipynb
 examples/creating-constraints.ipynb
+examples/creating-expressions.ipynb
 examples/creating-variables.ipynb
+examples/infeasible-model.ipynb
 examples/manipulating-models.ipynb
 examples/migrating-from-pyomo.ipynb
 examples/solve-on-remote.ipynb
+examples/testing-framework.ipynb
 linopy/__init__.py
 linopy/common.py
 linopy/config.py
 linopy/constants.py
 linopy/constraints.py
 linopy/expressions.py
 linopy/io.py
```

### Comparing `linopy-0.2.1/setup.py` & `linopy-0.2.2/setup.py`

 * *Files 5% similar despite different names*

```diff
@@ -39,14 +39,15 @@
     ],
     extras_require={
         "docs": [
             "ipython",
             "numpydoc",
             "sphinx",
             "sphinx_rtd_theme",
+            "sphinx_book_theme",
             "nbsphinx",
             "nbsphinx-link",
             "gurobipy",
             "ipykernel",
             "matplotlib",
         ],
         "dev": [
```

### Comparing `linopy-0.2.1/test/test_common.py` & `linopy-0.2.2/test/test_common.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/test/test_constraint.py` & `linopy-0.2.2/test/test_constraint.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/test/test_constraints.py` & `linopy-0.2.2/test/test_constraints.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/test/test_inconsistency_checks.py` & `linopy-0.2.2/test/test_inconsistency_checks.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/test/test_io.py` & `linopy-0.2.2/test/test_io.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/test/test_linear_expression.py` & `linopy-0.2.2/test/test_linear_expression.py`

 * *Files 2% similar despite different names*

```diff
@@ -434,14 +434,22 @@
     groups = pd.Series([1] * 10 + [2] * 10, index=v.indexes["dim_2"])
     grouped = expr.groupby(groups).sum()
     assert "group" in grouped.dims
     assert (grouped.data.group == [1, 2]).all()
     assert grouped.nterm == 10
 
 
+def test_linear_expression_groupby_with_series_false(v):
+    expr = 1 * v
+    groups = pd.Series([1] * 10 + [2] * 10, index=v.indexes["dim_2"])
+    groups.name = "dim_2"
+    with pytest.raises(ValueError):
+        grouped = expr.groupby(groups).sum()
+
+
 def test_linear_expression_groupby_with_dataframe(v):
     expr = 1 * v
     groups = pd.DataFrame(
         {"a": [1] * 10 + [2] * 10, "b": list(range(4)) * 5}, index=v.indexes["dim_2"]
     )
     grouped = expr.groupby(xr.DataArray(groups)).sum()
     index = pd.MultiIndex.from_frame(groups)
```

### Comparing `linopy-0.2.1/test/test_matrices.py` & `linopy-0.2.2/test/test_matrices.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/test/test_model.py` & `linopy-0.2.2/test/test_model.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/test/test_optimization.py` & `linopy-0.2.2/test/test_optimization.py`

 * *Files 2% similar despite different names*

```diff
@@ -345,18 +345,22 @@
     model.add_constraints([(1, "y")], "<=", 0)
 
     status, condition = model.solve(solver, io_api=io_api)
     assert status == "warning"
     assert "infeasible" in condition
 
     if solver == "gurobi":
-        model.compute_set_of_infeasible_constraints()
+        # ignore deprecated warning
+        with pytest.warns(DeprecationWarning):
+            model.compute_set_of_infeasible_constraints()
+        model.compute_infeasibilities()
+        model.print_infeasibilities()
     else:
         with pytest.raises((NotImplementedError, ImportError)):
-            model.compute_set_of_infeasible_constraints()
+            model.compute_infeasibilities()
 
 
 @pytest.mark.parametrize(
     "solver,io_api", [p for p in params if p[0] not in ["glpk", "cplex"]]
 )
 def test_model_with_inf(model_with_inf, solver, io_api):
     status, condition = model_with_inf.solve(solver, io_api=io_api)
```

### Comparing `linopy-0.2.1/test/test_options.py` & `linopy-0.2.2/test/test_options.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/test/test_quadratic_expression.py` & `linopy-0.2.2/test/test_quadratic_expression.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/test/test_repr.py` & `linopy-0.2.2/test/test_repr.py`

 * *Files 4% similar despite different names*

```diff
@@ -146,7 +146,13 @@
         default_repr = repr(o)
         with options as opts:
             opts.set_value(display_max_rows=20)
             longer_repr = repr(o)
         assert len(default_repr) < len(longer_repr)
 
         longer_repr = o.print(display_max_rows=20)
+
+
+def test_print_labels():
+    m.variables.print_labels([1, 2, 3])
+    m.constraints.print_labels([1, 2, 3])
+    m.constraints.print_labels([1, 2, 3], display_max_terms=10)
```

### Comparing `linopy-0.2.1/test/test_scalar_constraint.py` & `linopy-0.2.2/test/test_scalar_constraint.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/test/test_scalar_linear_expression.py` & `linopy-0.2.2/test/test_scalar_linear_expression.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/test/test_variable.py` & `linopy-0.2.2/test/test_variable.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/test/test_variable_assignment.py` & `linopy-0.2.2/test/test_variable_assignment.py`

 * *Files identical despite different names*

### Comparing `linopy-0.2.1/test/test_variables.py` & `linopy-0.2.2/test/test_variables.py`

 * *Files identical despite different names*


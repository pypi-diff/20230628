# Comparing `tmp/pharmpy-core-0.96.0.tar.gz` & `tmp/pharmpy-core-0.97.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pharmpy-core-0.96.0.tar", last modified: Fri May 26 09:46:09 2023, max compression
+gzip compressed data, was "pharmpy-core-0.97.0.tar", last modified: Wed Jun 28 07:02:54 2023, max compression
```

## Comparing `pharmpy-core-0.96.0.tar` & `pharmpy-core-0.97.0.tar`

### file list

```diff
@@ -1,1195 +1,1197 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.042861 pharmpy-core-0.96.0/
--rw-r--r--   0 runner    (1001) docker     (123)      419 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/.bumpversion.cfg
--rw-r--r--   0 runner    (1001) docker     (123)      227 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/.coveragerc
--rw-r--r--   0 runner    (1001) docker     (123)      891 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/AUTHORS.rst
--rw-r--r--   0 runner    (1001) docker     (123)    45995 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/CHANGELOG.rst
--rw-r--r--   0 runner    (1001) docker     (123)     2852 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/CODE_OF_CONDUCT.rst
--rw-r--r--   0 runner    (1001) docker     (123)    35196 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     7652 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/LICENSE.LESSER
--rw-r--r--   0 runner    (1001) docker     (123)      524 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)    47910 2023-05-26 09:46:09.042861 pharmpy-core-0.96.0/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2933 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/README.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.942861 pharmpy-core-0.96.0/docs/
--rw-r--r--   0 runner    (1001) docker     (123)    10512 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/NONMEM.rst
--rw-r--r--   0 runner    (1001) docker     (123)    14367 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/Pharmpy_logo.svg
--rw-r--r--   0 runner    (1001) docker     (123)    14872 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/Pharmpy_logo_dark.svg
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.942861 pharmpy-core-0.96.0/docs/_ext/
--rw-r--r--   0 runner    (1001) docker     (123)     7108 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/_ext/conversion.py
--rw-r--r--   0 runner    (1001) docker     (123)     4723 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/_ext/pharmpy_snippet.py
--rw-r--r--   0 runner    (1001) docker     (123)     5230 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/allometry.rst
--rw-r--r--   0 runner    (1001) docker     (123)    24284 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/amd.rst
--rw-r--r--   0 runner    (1001) docker     (123)      591 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/api.rst
--rw-r--r--   0 runner    (1001) docker     (123)       30 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/api_model.rst
--rw-r--r--   0 runner    (1001) docker     (123)       33 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/api_modeling.rst
--rw-r--r--   0 runner    (1001) docker     (123)       30 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/api_tools.rst
--rw-r--r--   0 runner    (1001) docker     (123)       34 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/api_workflows.rst
--rw-r--r--   0 runner    (1001) docker     (123)     4317 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/bootstrap.rst
--rw-r--r--   0 runner    (1001) docker     (123)     2807 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/cdd.rst
--rw-r--r--   0 runner    (1001) docker     (123)       76 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/changelog.rst
--rw-r--r--   0 runner    (1001) docker     (123)      413 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/citation.rst
--rw-r--r--   0 runner    (1001) docker     (123)      802 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/cli.rst
--rw-r--r--   0 runner    (1001) docker     (123)       58 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/code_of_conduct.rst
--rw-r--r--   0 runner    (1001) docker     (123)     2155 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/conf.py
--rw-r--r--   0 runner    (1001) docker     (123)     1742 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/configuration.rst
--rw-r--r--   0 runner    (1001) docker     (123)     6059 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/contribute.rst
--rw-r--r--   0 runner    (1001) docker     (123)       47 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/contributors.rst
--rw-r--r--   0 runner    (1001) docker     (123)    10790 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/covsearch.rst
--rw-r--r--   0 runner    (1001) docker     (123)      644 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/crossval.rst
--rw-r--r--   0 runner    (1001) docker     (123)     1290 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/custom.css
--rw-r--r--   0 runner    (1001) docker     (123)     7038 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/data.rst
--rw-r--r--   0 runner    (1001) docker     (123)     2793 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/design.rst
--rw-r--r--   0 runner    (1001) docker     (123)      177 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/developers.rst
--rw-r--r--   0 runner    (1001) docker     (123)    10499 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/estmethod.rst
--rw-r--r--   0 runner    (1001) docker     (123)     8137 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/frem.rst
--rw-r--r--   0 runner    (1001) docker     (123)     1470 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/getting_started.rst
--rw-r--r--   0 runner    (1001) docker     (123)      854 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/help_functions.py
--rw-r--r--   0 runner    (1001) docker     (123)    12790 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/iivsearch.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.942861 pharmpy-core-0.96.0/docs/images/
--rw-r--r--   0 runner    (1001) docker     (123)     5937 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/images/Pharmpy_symbol.svg
--rw-r--r--   0 runner    (1001) docker     (123)   179150 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/images/tools.png
--rw-r--r--   0 runner    (1001) docker     (123)     1457 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/index.rst
--rw-r--r--   0 runner    (1001) docker     (123)    11603 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/iovsearch.rst
--rw-r--r--   0 runner    (1001) docker     (123)     2827 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/license.rst
--rw-r--r--   0 runner    (1001) docker     (123)      967 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/linearize.rst
--rw-r--r--   0 runner    (1001) docker     (123)     6577 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/model.rst
--rw-r--r--   0 runner    (1001) docker     (123)     2769 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/modelfit.rst
--rw-r--r--   0 runner    (1001) docker     (123)    28238 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/modeling.rst
--rw-r--r--   0 runner    (1001) docker     (123)    16031 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/modelsearch.rst
--rw-r--r--   0 runner    (1001) docker     (123)     4434 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/nonmem_plugin.rst
--rw-r--r--   0 runner    (1001) docker     (123)    12416 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/pharmr_logo.svg
--rw-r--r--   0 runner    (1001) docker     (123)     1072 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/plots.rst
--rw-r--r--   0 runner    (1001) docker     (123)     1248 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/plugins.rst
--rw-r--r--   0 runner    (1001) docker     (123)     5585 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/projects.rst
--rw-r--r--   0 runner    (1001) docker     (123)      452 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/psn_resmod.rst
--rw-r--r--   0 runner    (1001) docker     (123)      336 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/psn_tools.rst
--rw-r--r--   0 runner    (1001) docker     (123)     2758 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/qa.rst
--rw-r--r--   0 runner    (1001) docker     (123)      157 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/requirements.txt
--rw-r--r--   0 runner    (1001) docker     (123)     7786 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/ruvsearch.rst
--rw-r--r--   0 runner    (1001) docker     (123)     2697 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/scm.rst
--rw-r--r--   0 runner    (1001) docker     (123)     1416 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/simeval.rst
--rw-r--r--   0 runner    (1001) docker     (123)      109 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/spelling_wordlist.txt
--rw-r--r--   0 runner    (1001) docker     (123)    15103 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/tools.rst
--rw-r--r--   0 runner    (1001) docker     (123)      389 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/user_guide.rst
--rw-r--r--   0 runner    (1001) docker     (123)     4159 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/docs/using_r.rst
--rw-r--r--   0 runner    (1001) docker     (123)      358 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)     2406 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/requirements.txt
--rw-r--r--   0 runner    (1001) docker     (123)      813 2023-05-26 09:46:09.046861 pharmpy-core-0.96.0/setup.cfg
--rwxr-xr-x   0 runner    (1001) docker     (123)     3180 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.942861 pharmpy-core-0.96.0/src/
--rw-r--r--   0 runner    (1001) docker     (123)      257 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/conftest.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.946861 pharmpy-core-0.96.0/src/pharmpy/
--rw-r--r--   0 runner    (1001) docker     (123)      219 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      125 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    80648 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/cli.py
--rw-r--r--   0 runner    (1001) docker     (123)     3593 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/config.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.946861 pharmpy-core-0.96.0/src/pharmpy/deps/
--rw-r--r--   0 runner    (1001) docker     (123)      579 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/deps/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      518 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/deps/altair.py
--rw-r--r--   0 runner    (1001) docker     (123)      213 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/deps/rich.py
--rw-r--r--   0 runner    (1001) docker     (123)      165 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/deps/scipy.py
--rw-r--r--   0 runner    (1001) docker     (123)      261 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/deps/sympy_printing.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.946861 pharmpy-core-0.96.0/src/pharmpy/internals/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      413 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/code_generator.py
--rw-r--r--   0 runner    (1001) docker     (123)      909 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/df.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.946861 pharmpy-core-0.96.0/src/pharmpy/internals/ds/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/ds/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1922 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/ds/ordered_set.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.946861 pharmpy-core-0.96.0/src/pharmpy/internals/expr/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/expr/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      352 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/expr/assumptions.py
--rw-r--r--   0 runner    (1001) docker     (123)     1397 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/expr/eval.py
--rw-r--r--   0 runner    (1001) docker     (123)      955 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/expr/funcs.py
--rw-r--r--   0 runner    (1001) docker     (123)      632 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/expr/leaves.py
--rw-r--r--   0 runner    (1001) docker     (123)      697 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/expr/ode.py
--rw-r--r--   0 runner    (1001) docker     (123)      264 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/expr/parse.py
--rw-r--r--   0 runner    (1001) docker     (123)     2959 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/expr/subs.py
--rw-r--r--   0 runner    (1001) docker     (123)     2273 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/expr/tree.py
--rw-r--r--   0 runner    (1001) docker     (123)      585 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/expr/units.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.946861 pharmpy-core-0.96.0/src/pharmpy/internals/fn/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/fn/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2335 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/fn/signature.py
--rw-r--r--   0 runner    (1001) docker     (123)     5576 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/fn/type.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.946861 pharmpy-core-0.96.0/src/pharmpy/internals/fs/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/fs/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      496 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/fs/cwd.py
--rw-r--r--   0 runner    (1001) docker     (123)    19768 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/fs/lock.py
--rw-r--r--   0 runner    (1001) docker     (123)      770 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/fs/path.py
--rw-r--r--   0 runner    (1001) docker     (123)     3611 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/fs/tmp.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.930861 pharmpy-core-0.96.0/src/pharmpy/internals/graph/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.946861 pharmpy-core-0.96.0/src/pharmpy/internals/graph/directed/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/graph/directed/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      758 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/graph/directed/connected_components.py
--rw-r--r--   0 runner    (1001) docker     (123)      327 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/graph/directed/inverse.py
--rw-r--r--   0 runner    (1001) docker     (123)      425 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/graph/directed/reachability.py
--rw-r--r--   0 runner    (1001) docker     (123)      923 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/immutable.py
--rw-r--r--   0 runner    (1001) docker     (123)     6508 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/math.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.946861 pharmpy-core-0.96.0/src/pharmpy/internals/module/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/module/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1380 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/module/lazy.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.950861 pharmpy-core-0.96.0/src/pharmpy/internals/parse/
--rw-r--r--   0 runner    (1001) docker     (123)      297 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/parse/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    15783 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/parse/generic.py
--rw-r--r--   0 runner    (1001) docker     (123)     3050 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/parse/ignored.py
--rw-r--r--   0 runner    (1001) docker     (123)      964 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/parse/missing.py
--rw-r--r--   0 runner    (1001) docker     (123)     2519 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/parse/prettyprint.py
--rw-r--r--   0 runner    (1001) docker     (123)     1044 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/parse/tree.py
--rw-r--r--   0 runner    (1001) docker     (123)     4340 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/parse/treeprint.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.950861 pharmpy-core-0.96.0/src/pharmpy/internals/sequence/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/sequence/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2114 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/sequence/lcs.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.950861 pharmpy-core-0.96.0/src/pharmpy/internals/set/
--rw-r--r--   0 runner    (1001) docker     (123)     1498 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/set/partitions.py
--rw-r--r--   0 runner    (1001) docker     (123)     1413 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/set/subsets.py
--rw-r--r--   0 runner    (1001) docker     (123)     6365 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/internals/unicode.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.950861 pharmpy-core-0.96.0/src/pharmpy/model/
--rw-r--r--   0 runner    (1001) docker     (123)     1353 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      922 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/data.py
--rw-r--r--   0 runner    (1001) docker     (123)    30729 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/datainfo.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.950861 pharmpy-core-0.96.0/src/pharmpy/model/distributions/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/distributions/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1053 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/distributions/numeric.py
--rw-r--r--   0 runner    (1001) docker     (123)    19145 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/distributions/symbolic.py
--rw-r--r--   0 runner    (1001) docker     (123)    14790 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/estimation.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.950861 pharmpy-core-0.96.0/src/pharmpy/model/external/
--rw-r--r--   0 runner    (1001) docker     (123)       60 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.950861 pharmpy-core-0.96.0/src/pharmpy/model/external/fcon/
--rw-r--r--   0 runner    (1001) docker     (123)      104 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/fcon/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2117 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/fcon/model.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.950861 pharmpy-core-0.96.0/src/pharmpy/model/external/nlmixr/
--rw-r--r--   0 runner    (1001) docker     (123)       78 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nlmixr/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    10036 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nlmixr/error_model.py
--rw-r--r--   0 runner    (1001) docker     (123)     5571 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nlmixr/ini.py
--rw-r--r--   0 runner    (1001) docker     (123)     9061 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nlmixr/model.py
--rw-r--r--   0 runner    (1001) docker     (123)    15427 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nlmixr/model_block.py
--rw-r--r--   0 runner    (1001) docker     (123)      408 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nlmixr/name_mangle.py
--rw-r--r--   0 runner    (1001) docker     (123)    10780 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nlmixr/sanity_checks.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.950861 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/
--rw-r--r--   0 runner    (1001) docker     (123)      155 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    22581 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/advan.py
--rw-r--r--   0 runner    (1001) docker     (123)    11551 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/dataset.py
--rw-r--r--   0 runner    (1001) docker     (123)      297 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/detect.py
--rw-r--r--   0 runner    (1001) docker     (123)    14131 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/model.py
--rw-r--r--   0 runner    (1001) docker     (123)     6712 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/nmtran_parser.py
--rw-r--r--   0 runner    (1001) docker     (123)    28896 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/parsing.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.954861 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/
--rw-r--r--   0 runner    (1001) docker     (123)       45 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      866 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/abbreviated_record.py
--rw-r--r--   0 runner    (1001) docker     (123)    25158 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/code_record.py
--rw-r--r--   0 runner    (1001) docker     (123)     5455 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/data_record.py
--rw-r--r--   0 runner    (1001) docker     (123)      423 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/estimation_record.py
--rw-r--r--   0 runner    (1001) docker     (123)      361 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/etas_record.py
--rw-r--r--   0 runner    (1001) docker     (123)     3476 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/factory.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.954861 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/grammars/
--rw-r--r--   0 runner    (1001) docker     (123)     2904 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/grammars/abbreviated_record.lark
--rw-r--r--   0 runner    (1001) docker     (123)     6372 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/grammars/code_record.lark
--rw-r--r--   0 runner    (1001) docker     (123)     2232 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/grammars/data_record.lark
--rw-r--r--   0 runner    (1001) docker     (123)      360 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/grammars/definitions.lark
--rw-r--r--   0 runner    (1001) docker     (123)     3216 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/grammars/omega_record.lark
--rw-r--r--   0 runner    (1001) docker     (123)      318 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/grammars/option_record.lark
--rw-r--r--   0 runner    (1001) docker     (123)      146 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/grammars/problem_record.lark
--rw-r--r--   0 runner    (1001) docker     (123)     1397 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/grammars/simulation_record.lark
--rw-r--r--   0 runner    (1001) docker     (123)     1921 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/grammars/theta_record.lark
--rw-r--r--   0 runner    (1001) docker     (123)     1692 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/model_record.py
--rw-r--r--   0 runner    (1001) docker     (123)    17000 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/omega_record.py
--rw-r--r--   0 runner    (1001) docker     (123)    20087 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/option_record.py
--rw-r--r--   0 runner    (1001) docker     (123)     2841 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/parsers.py
--rw-r--r--   0 runner    (1001) docker     (123)      840 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/problem_record.py
--rw-r--r--   0 runner    (1001) docker     (123)      366 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/raw_record.py
--rw-r--r--   0 runner    (1001) docker     (123)      565 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/record.py
--rw-r--r--   0 runner    (1001) docker     (123)      426 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/simulation_record.py
--rw-r--r--   0 runner    (1001) docker     (123)      952 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/sizes_record.py
--rw-r--r--   0 runner    (1001) docker     (123)     1002 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/subroutine_record.py
--rw-r--r--   0 runner    (1001) docker     (123)     2803 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/table_record.py
--rw-r--r--   0 runner    (1001) docker     (123)     5335 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/theta_record.py
--rw-r--r--   0 runner    (1001) docker     (123)    11765 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/table.py
--rw-r--r--   0 runner    (1001) docker     (123)    64737 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/update.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.954861 pharmpy-core-0.96.0/src/pharmpy/model/external/rxode/
--rw-r--r--   0 runner    (1001) docker     (123)       78 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/rxode/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     7199 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/rxode/model.py
--rw-r--r--   0 runner    (1001) docker     (123)     1186 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/external/utils.py
--rw-r--r--   0 runner    (1001) docker     (123)    21361 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/model.py
--rw-r--r--   0 runner    (1001) docker     (123)    13285 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/parameters.py
--rw-r--r--   0 runner    (1001) docker     (123)    34378 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/random_variables.py
--rw-r--r--   0 runner    (1001) docker     (123)     8281 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/results.py
--rw-r--r--   0 runner    (1001) docker     (123)    72906 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/model/statements.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.958861 pharmpy-core-0.96.0/src/pharmpy/modeling/
--rw-r--r--   0 runner    (1001) docker     (123)    10619 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4589 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/allometry.py
--rw-r--r--   0 runner    (1001) docker     (123)     6418 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/basic_models.py
--rw-r--r--   0 runner    (1001) docker     (123)     6536 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/block_rvs.py
--rw-r--r--   0 runner    (1001) docker     (123)     6721 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/blq.py
--rw-r--r--   0 runner    (1001) docker     (123)    18481 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/common.py
--rw-r--r--   0 runner    (1001) docker     (123)     1127 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/compartments.py
--rw-r--r--   0 runner    (1001) docker     (123)    21363 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/covariate_effect.py
--rw-r--r--   0 runner    (1001) docker     (123)    49871 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/data.py
--rw-r--r--   0 runner    (1001) docker     (123)    36044 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/error.py
--rw-r--r--   0 runner    (1001) docker     (123)     5087 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/estimation.py
--rw-r--r--   0 runner    (1001) docker     (123)     9043 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/estimation_steps.py
--rw-r--r--   0 runner    (1001) docker     (123)    16283 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/eta_additions.py
--rw-r--r--   0 runner    (1001) docker     (123)     7964 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/eta_transformations.py
--rw-r--r--   0 runner    (1001) docker     (123)    15348 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/evaluation.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.958861 pharmpy-core-0.96.0/src/pharmpy/modeling/example_models/
--rw-r--r--   0 runner    (1001) docker     (123)    50310 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/example_models/moxo.csv
--rw-r--r--   0 runner    (1001) docker     (123)     1392 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/example_models/moxo.mod
--rw-r--r--   0 runner    (1001) docker     (123)      989 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/example_models/pheno.cov
--rw-r--r--   0 runner    (1001) docker     (123)      680 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/example_models/pheno.datainfo
--rw-r--r--   0 runner    (1001) docker     (123)    38720 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/example_models/pheno.dta
--rw-r--r--   0 runner    (1001) docker     (123)     2851 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/example_models/pheno.ext
--rw-r--r--   0 runner    (1001) docker     (123)    21259 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/example_models/pheno.lst
--rw-r--r--   0 runner    (1001) docker     (123)      662 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/example_models/pheno.mod
--rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/example_models/pheno.phi
--rw-r--r--   0 runner    (1001) docker     (123)    90151 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/example_models/pheno.tab
--rw-r--r--   0 runner    (1001) docker     (123)   298562 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/example_models/pheno_linear.dta
--rw-r--r--   0 runner    (1001) docker     (123)     2384 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/example_models/pheno_linear.ext
--rw-r--r--   0 runner    (1001) docker     (123)    14564 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/example_models/pheno_linear.lst
--rw-r--r--   0 runner    (1001) docker     (123)      605 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/example_models/pheno_linear.mod
--rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/example_models/pheno_linear.phi
--rw-r--r--   0 runner    (1001) docker     (123)    45278 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/expressions.py
--rw-r--r--   0 runner    (1001) docker     (123)     2746 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/help_functions.py
--rw-r--r--   0 runner    (1001) docker     (123)    11217 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/iterators.py
--rw-r--r--   0 runner    (1001) docker     (123)     1572 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/lrt.py
--rw-r--r--   0 runner    (1001) docker     (123)    19639 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/math.py
--rw-r--r--   0 runner    (1001) docker     (123)     2671 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/metabolite.py
--rw-r--r--   0 runner    (1001) docker     (123)    70916 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/odes.py
--rw-r--r--   0 runner    (1001) docker     (123)    12116 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/parameter_sampling.py
--rw-r--r--   0 runner    (1001) docker     (123)    15780 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/parameters.py
--rw-r--r--   0 runner    (1001) docker     (123)     4939 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/plots.py
--rw-r--r--   0 runner    (1001) docker     (123)     1700 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/remove_iiv.py
--rw-r--r--   0 runner    (1001) docker     (123)     2292 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/remove_iov.py
--rw-r--r--   0 runner    (1001) docker     (123)    25760 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/results.py
--rw-r--r--   0 runner    (1001) docker     (123)     6314 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/tmdd.py
--rw-r--r--   0 runner    (1001) docker     (123)     4920 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/units.py
--rw-r--r--   0 runner    (1001) docker     (123)     4242 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/update_inits.py
--rw-r--r--   0 runner    (1001) docker     (123)     1628 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/modeling/write_csv.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.962861 pharmpy-core-0.96.0/src/pharmpy/reporting/
--rw-r--r--   0 runner    (1001) docker     (123)    11165 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/reporting/altairplot.py
--rw-r--r--   0 runner    (1001) docker     (123)      361 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/reporting/conf.py
--rw-r--r--   0 runner    (1001) docker     (123)      643 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/reporting/custom.css
--rwxr-xr-x   0 runner    (1001) docker     (123)     5634 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/reporting/reporting.py
--rw-r--r--   0 runner    (1001) docker     (123)     8772 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/results.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.962861 pharmpy-core-0.96.0/src/pharmpy/tools/
--rw-r--r--   0 runner    (1001) docker     (123)     3744 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.962861 pharmpy-core-0.96.0/src/pharmpy/tools/allometry/
--rw-r--r--   0 runner    (1001) docker     (123)       99 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/allometry/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6487 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/allometry/tool.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.962861 pharmpy-core-0.96.0/src/pharmpy/tools/amd/
--rw-r--r--   0 runner    (1001) docker     (123)       69 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/amd/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4902 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/amd/funcs.py
--rw-r--r--   0 runner    (1001) docker     (123)      458 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/amd/results.py
--rw-r--r--   0 runner    (1001) docker     (123)    16119 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/amd/run.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.962861 pharmpy-core-0.96.0/src/pharmpy/tools/bootstrap/
--rw-r--r--   0 runner    (1001) docker     (123)      157 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/bootstrap/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      540 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/bootstrap/report.rst
--rw-r--r--   0 runner    (1001) docker     (123)     8800 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/bootstrap/results.py
--rw-r--r--   0 runner    (1001) docker     (123)     1818 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/bootstrap/tool.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.962861 pharmpy-core-0.96.0/src/pharmpy/tools/cdd/
--rw-r--r--   0 runner    (1001) docker     (123)       98 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/cdd/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     8393 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/cdd/results.py
--rw-r--r--   0 runner    (1001) docker     (123)     4863 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/common.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.962861 pharmpy-core-0.96.0/src/pharmpy/tools/covsearch/
--rw-r--r--   0 runner    (1001) docker     (123)      192 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/covsearch/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      386 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/covsearch/results.py
--rw-r--r--   0 runner    (1001) docker     (123)    19965 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/covsearch/tool.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.962861 pharmpy-core-0.96.0/src/pharmpy/tools/crossval/
--rw-r--r--   0 runner    (1001) docker     (123)      147 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/crossval/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1449 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/crossval/results.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.962861 pharmpy-core-0.96.0/src/pharmpy/tools/estmethod/
--rw-r--r--   0 runner    (1001) docker     (123)      171 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/estmethod/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5527 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/estmethod/algorithms.py
--rw-r--r--   0 runner    (1001) docker     (123)      583 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/estmethod/report.rst
--rw-r--r--   0 runner    (1001) docker     (123)     6974 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/estmethod/tool.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.962861 pharmpy-core-0.96.0/src/pharmpy/tools/evaldesign/
--rw-r--r--   0 runner    (1001) docker     (123)      140 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/evaldesign/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      722 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/evaldesign/tool.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.962861 pharmpy-core-0.96.0/src/pharmpy/tools/external/
--rw-r--r--   0 runner    (1001) docker     (123)       82 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/external/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.962861 pharmpy-core-0.96.0/src/pharmpy/tools/external/nlmixr/
--rw-r--r--   0 runner    (1001) docker     (123)      783 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/external/nlmixr/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    19032 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/external/nlmixr/run.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.962861 pharmpy-core-0.96.0/src/pharmpy/tools/external/nonmem/
--rw-r--r--   0 runner    (1001) docker     (123)      782 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/external/nonmem/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      635 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/external/nonmem/config.py
--rw-r--r--   0 runner    (1001) docker     (123)    21360 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/external/nonmem/results.py
--rw-r--r--   0 runner    (1001) docker     (123)    18254 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/external/nonmem/results_file.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     7225 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/external/nonmem/run.py
--rw-r--r--   0 runner    (1001) docker     (123)      332 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/external/results.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.962861 pharmpy-core-0.96.0/src/pharmpy/tools/external/rxode/
--rw-r--r--   0 runner    (1001) docker     (123)      779 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/external/rxode/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6598 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/external/rxode/run.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.966861 pharmpy-core-0.96.0/src/pharmpy/tools/frem/
--rw-r--r--   0 runner    (1001) docker     (123)      102 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/frem/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1897 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/frem/models.py
--rw-r--r--   0 runner    (1001) docker     (123)      505 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/frem/report.rst
--rw-r--r--   0 runner    (1001) docker     (123)    39039 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/frem/results.py
--rw-r--r--   0 runner    (1001) docker     (123)     2914 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/frem/tool.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.966861 pharmpy-core-0.96.0/src/pharmpy/tools/funcs/
--rw-r--r--   0 runner    (1001) docker     (123)      372 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/funcs/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     9605 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/funcs/ml.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.966861 pharmpy-core-0.96.0/src/pharmpy/tools/funcs/ml_models/
--rw-r--r--   0 runner    (1001) docker     (123)    91484 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/funcs/ml_models/infinds.tflite
--rw-r--r--   0 runner    (1001) docker     (123)    93596 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/funcs/ml_models/outliers.tflite
--rw-r--r--   0 runner    (1001) docker     (123)     9949 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/funcs/summarize_individuals.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.966861 pharmpy-core-0.96.0/src/pharmpy/tools/iivsearch/
--rw-r--r--   0 runner    (1001) docker     (123)      172 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/iivsearch/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5147 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/iivsearch/algorithms.py
--rw-r--r--   0 runner    (1001) docker     (123)     9843 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/iivsearch/tool.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.966861 pharmpy-core-0.96.0/src/pharmpy/tools/iovsearch/
--rw-r--r--   0 runner    (1001) docker     (123)      171 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/iovsearch/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    12441 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/iovsearch/tool.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.966861 pharmpy-core-0.96.0/src/pharmpy/tools/linearize/
--rw-r--r--   0 runner    (1001) docker     (123)      104 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/linearize/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2012 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/linearize/results.py
--rw-r--r--   0 runner    (1001) docker     (123)     2357 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/linearize/tool.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.966861 pharmpy-core-0.96.0/src/pharmpy/tools/mfl/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/mfl/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.966861 pharmpy-core-0.96.0/src/pharmpy/tools/mfl/feature/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/mfl/feature/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1211 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/mfl/feature/absorption.py
--rw-r--r--   0 runner    (1001) docker     (123)     5067 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/mfl/feature/covariate.py
--rw-r--r--   0 runner    (1001) docker     (123)     1405 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/mfl/feature/elimination.py
--rw-r--r--   0 runner    (1001) docker     (123)      209 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/mfl/feature/feature.py
--rw-r--r--   0 runner    (1001) docker     (123)      430 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/mfl/feature/lagtime.py
--rw-r--r--   0 runner    (1001) docker     (123)      577 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/mfl/feature/peripherals.py
--rw-r--r--   0 runner    (1001) docker     (123)     1269 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/mfl/feature/transits.py
--rw-r--r--   0 runner    (1001) docker     (123)      636 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/mfl/filter.py
--rw-r--r--   0 runner    (1001) docker     (123)     2619 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/mfl/grammar.py
--rw-r--r--   0 runner    (1001) docker     (123)     2166 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/mfl/helpers.py
--rw-r--r--   0 runner    (1001) docker     (123)     1275 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/mfl/interpreter.py
--rw-r--r--   0 runner    (1001) docker     (123)      603 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/mfl/parse.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.966861 pharmpy-core-0.96.0/src/pharmpy/tools/mfl/statement/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/mfl/statement/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      596 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/mfl/statement/definition.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.970861 pharmpy-core-0.96.0/src/pharmpy/tools/mfl/statement/feature/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/mfl/statement/feature/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      751 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/mfl/statement/feature/absorption.py
--rw-r--r--   0 runner    (1001) docker     (123)      780 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/mfl/statement/feature/count_interpreter.py
--rw-r--r--   0 runner    (1001) docker     (123)     2010 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/mfl/statement/feature/covariate.py
--rw-r--r--   0 runner    (1001) docker     (123)      762 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/mfl/statement/feature/elimination.py
--rw-r--r--   0 runner    (1001) docker     (123)      253 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/mfl/statement/feature/feature.py
--rw-r--r--   0 runner    (1001) docker     (123)      342 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/mfl/statement/feature/lagtime.py
--rw-r--r--   0 runner    (1001) docker     (123)      444 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/mfl/statement/feature/peripherals.py
--rw-r--r--   0 runner    (1001) docker     (123)      269 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/mfl/statement/feature/symbols.py
--rw-r--r--   0 runner    (1001) docker     (123)      850 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/mfl/statement/feature/transits.py
--rw-r--r--   0 runner    (1001) docker     (123)      134 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/mfl/statement/statement.py
--rw-r--r--   0 runner    (1001) docker     (123)     2105 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/mfl/stringify.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.970861 pharmpy-core-0.96.0/src/pharmpy/tools/modelfit/
--rw-r--r--   0 runner    (1001) docker     (123)      671 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/modelfit/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4086 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/modelfit/tool.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.970861 pharmpy-core-0.96.0/src/pharmpy/tools/modelsearch/
--rw-r--r--   0 runner    (1001) docker     (123)      177 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/modelsearch/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    11394 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/modelsearch/algorithms.py
--rw-r--r--   0 runner    (1001) docker     (123)     5407 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/modelsearch/tool.py
--rw-r--r--   0 runner    (1001) docker     (123)     6174 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/psn_helpers.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.970861 pharmpy-core-0.96.0/src/pharmpy/tools/qa/
--rw-r--r--   0 runner    (1001) docker     (123)       83 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/qa/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    19639 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/qa/results.py
--rw-r--r--   0 runner    (1001) docker     (123)     2372 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/rankfuncs.py
--rw-r--r--   0 runner    (1001) docker     (123)      848 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/reporting.py
--rw-r--r--   0 runner    (1001) docker     (123)    33617 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/run.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.970861 pharmpy-core-0.96.0/src/pharmpy/tools/ruvsearch/
--rw-r--r--   0 runner    (1001) docker     (123)      191 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/ruvsearch/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4507 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/ruvsearch/results.py
--rw-r--r--   0 runner    (1001) docker     (123)    16708 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/ruvsearch/tool.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.970861 pharmpy-core-0.96.0/src/pharmpy/tools/scm/
--rw-r--r--   0 runner    (1001) docker     (123)      164 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/scm/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2422 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/scm/psn_wrapper.py
--rw-r--r--   0 runner    (1001) docker     (123)    27585 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/scm/results.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.970861 pharmpy-core-0.96.0/src/pharmpy/tools/simeval/
--rw-r--r--   0 runner    (1001) docker     (123)       98 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/simeval/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2870 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/simeval/results.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.970861 pharmpy-core-0.96.0/src/pharmpy/tools/simfit/
--rw-r--r--   0 runner    (1001) docker     (123)      110 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/simfit/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      687 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/simfit/results.py
--rw-r--r--   0 runner    (1001) docker     (123)     2152 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/tools/wrap.py
--rw-r--r--   0 runner    (1001) docker     (123)     5676 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/visualization.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.970861 pharmpy-core-0.96.0/src/pharmpy/workflows/
--rw-r--r--   0 runner    (1001) docker     (123)     2459 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/workflows/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      830 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/workflows/args.py
--rw-r--r--   0 runner    (1001) docker     (123)     1141 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/workflows/call.py
--rw-r--r--   0 runner    (1001) docker     (123)      449 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/workflows/context.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.970861 pharmpy-core-0.96.0/src/pharmpy/workflows/dispatchers/
--rw-r--r--   0 runner    (1001) docker     (123)      325 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/workflows/dispatchers/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4460 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/workflows/dispatchers/local_dask.py
--rw-r--r--   0 runner    (1001) docker     (123)     2711 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/workflows/execute.py
--rw-r--r--   0 runner    (1001) docker     (123)     2805 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/workflows/log.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.970861 pharmpy-core-0.96.0/src/pharmpy/workflows/model_database/
--rw-r--r--   0 runner    (1001) docker     (123)      289 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/workflows/model_database/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     9287 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/workflows/model_database/baseclass.py
--rw-r--r--   0 runner    (1001) docker     (123)    12311 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/workflows/model_database/local_directory.py
--rw-r--r--   0 runner    (1001) docker     (123)      807 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/workflows/model_database/null_database.py
--rw-r--r--   0 runner    (1001) docker     (123)     1390 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/workflows/optimize.py
--rw-r--r--   0 runner    (1001) docker     (123)      505 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/workflows/task.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.970861 pharmpy-core-0.96.0/src/pharmpy/workflows/tool_database/
--rw-r--r--   0 runner    (1001) docker     (123)      229 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/workflows/tool_database/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1540 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/workflows/tool_database/baseclass.py
--rw-r--r--   0 runner    (1001) docker     (123)     2922 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/workflows/tool_database/local_directory.py
--rw-r--r--   0 runner    (1001) docker     (123)      593 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/workflows/tool_database/null_database.py
--rw-r--r--   0 runner    (1001) docker     (123)     5880 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/src/pharmpy/workflows/workflow.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.974861 pharmpy-core-0.96.0/src/pharmpy_core.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    47910 2023-05-26 09:46:08.000000 pharmpy-core-0.96.0/src/pharmpy_core.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    47414 2023-05-26 09:46:08.000000 pharmpy-core-0.96.0/src/pharmpy_core.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-05-26 09:46:08.000000 pharmpy-core-0.96.0/src/pharmpy_core.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)      114 2023-05-26 09:46:08.000000 pharmpy-core-0.96.0/src/pharmpy_core.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-05-26 09:40:32.000000 pharmpy-core-0.96.0/src/pharmpy_core.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)      238 2023-05-26 09:46:08.000000 pharmpy-core-0.96.0/src/pharmpy_core.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       17 2023-05-26 09:46:08.000000 pharmpy-core-0.96.0/src/pharmpy_core.egg-info/top_level.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.974861 pharmpy-core-0.96.0/tests/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.974861 pharmpy-core-0.96.0/tests/cli/
--rw-r--r--   0 runner    (1001) docker     (123)     8805 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/cli/test_cli.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.974861 pharmpy-core-0.96.0/tests/config/
--rw-r--r--   0 runner    (1001) docker     (123)      403 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/config/test_config.py
--rw-r--r--   0 runner    (1001) docker     (123)     2970 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/conftest.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.974861 pharmpy-core-0.96.0/tests/deps/
--rw-r--r--   0 runner    (1001) docker     (123)      257 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/deps/test_deps.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.974861 pharmpy-core-0.96.0/tests/external/
--rw-r--r--   0 runner    (1001) docker     (123)      463 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/external/test_external.py
--rw-r--r--   0 runner    (1001) docker     (123)     2320 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/external/test_nlmixr.py
--rw-r--r--   0 runner    (1001) docker     (123)     1721 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/external/test_rxode.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.974861 pharmpy-core-0.96.0/tests/integration/
--rw-r--r--   0 runner    (1001) docker     (123)     1152 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/integration/conftest.py
--rw-r--r--   0 runner    (1001) docker     (123)     1522 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/integration/test_allometry.py
--rw-r--r--   0 runner    (1001) docker     (123)     1557 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/integration/test_amd.py
--rw-r--r--   0 runner    (1001) docker     (123)      800 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/integration/test_bootstrap.py
--rw-r--r--   0 runner    (1001) docker     (123)     1096 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/integration/test_common.py
--rw-r--r--   0 runner    (1001) docker     (123)      640 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/integration/test_covsearch.py
--rw-r--r--   0 runner    (1001) docker     (123)     1059 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/integration/test_estmethod.py
--rw-r--r--   0 runner    (1001) docker     (123)      662 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/integration/test_evaldesign.py
--rw-r--r--   0 runner    (1001) docker     (123)     4025 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/integration/test_fit.py
--rw-r--r--   0 runner    (1001) docker     (123)     7463 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/integration/test_iivsearch.py
--rw-r--r--   0 runner    (1001) docker     (123)     1440 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/integration/test_iovsearch.py
--rw-r--r--   0 runner    (1001) docker     (123)     7834 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/integration/test_modelsearch.py
--rw-r--r--   0 runner    (1001) docker     (123)     8845 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/integration/test_resume.py
--rw-r--r--   0 runner    (1001) docker     (123)     1678 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/integration/test_ruvsearch.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.974861 pharmpy-core-0.96.0/tests/internals/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.974861 pharmpy-core-0.96.0/tests/internals/fs/
--rw-r--r--   0 runner    (1001) docker     (123)    15348 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/internals/fs/test_lock.py
--rw-r--r--   0 runner    (1001) docker     (123)      223 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/internals/fs/test_tmp.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.974861 pharmpy-core-0.96.0/tests/internals/module/
--rw-r--r--   0 runner    (1001) docker     (123)      513 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/internals/module/test_lazy.py
--rw-r--r--   0 runner    (1001) docker     (123)     5505 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/internals/test_math.py
--rw-r--r--   0 runner    (1001) docker     (123)     3863 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/internals/test_parse.py
--rw-r--r--   0 runner    (1001) docker     (123)      485 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/lib.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.974861 pharmpy-core-0.96.0/tests/model/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/model/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    10091 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/model/test_datainfo.py
--rw-r--r--   0 runner    (1001) docker     (123)     5537 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/model/test_estimation.py
--rw-r--r--   0 runner    (1001) docker     (123)     2829 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/model/test_model.py
--rw-r--r--   0 runner    (1001) docker     (123)     8855 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/model/test_parameter.py
--rw-r--r--   0 runner    (1001) docker     (123)    29709 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/model/test_random_variables.py
--rw-r--r--   0 runner    (1001) docker     (123)    15860 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/model/test_statements.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.978861 pharmpy-core-0.96.0/tests/modeling/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/modeling/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    14199 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/modeling/test_add_covariate_effect.py
--rw-r--r--   0 runner    (1001) docker     (123)     4437 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/modeling/test_allometry.py
--rw-r--r--   0 runner    (1001) docker     (123)      274 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/modeling/test_basic_models.py
--rw-r--r--   0 runner    (1001) docker     (123)     3861 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/modeling/test_block_rvs.py
--rw-r--r--   0 runner    (1001) docker     (123)     6067 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/modeling/test_blq.py
--rw-r--r--   0 runner    (1001) docker     (123)     4448 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/modeling/test_common.py
--rw-r--r--   0 runner    (1001) docker     (123)      246 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/modeling/test_compartments.py
--rw-r--r--   0 runner    (1001) docker     (123)     1329 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/modeling/test_covariate_effect.py
--rw-r--r--   0 runner    (1001) docker     (123)    10292 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/modeling/test_data_funcs.py
--rw-r--r--   0 runner    (1001) docker     (123)    17022 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/modeling/test_distribution.py
--rw-r--r--   0 runner    (1001) docker     (123)    27570 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/modeling/test_error.py
--rw-r--r--   0 runner    (1001) docker     (123)     4447 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/modeling/test_estimation_steps.py
--rw-r--r--   0 runner    (1001) docker     (123)     1887 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/modeling/test_eta_additions.py
--rw-r--r--   0 runner    (1001) docker     (123)      751 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/modeling/test_eta_transformations.py
--rw-r--r--   0 runner    (1001) docker     (123)     4191 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/modeling/test_evaluate.py
--rw-r--r--   0 runner    (1001) docker     (123)    20673 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/modeling/test_expressions.py
--rw-r--r--   0 runner    (1001) docker     (123)     2591 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/modeling/test_has_covariate_effect.py
--rw-r--r--   0 runner    (1001) docker     (123)     1301 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/modeling/test_help_functions.py
--rw-r--r--   0 runner    (1001) docker     (123)     3651 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/modeling/test_iterators.py
--rw-r--r--   0 runner    (1001) docker     (123)     4607 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/modeling/test_lrt.py
--rw-r--r--   0 runner    (1001) docker     (123)      522 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/modeling/test_metabolite.py
--rw-r--r--   0 runner    (1001) docker     (123)   100513 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/modeling/test_modeling.py
--rw-r--r--   0 runner    (1001) docker     (123)     3142 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/modeling/test_parameter_sampling.py
--rw-r--r--   0 runner    (1001) docker     (123)     4968 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/modeling/test_parameters.py
--rw-r--r--   0 runner    (1001) docker     (123)     1154 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/modeling/test_plots.py
--rw-r--r--   0 runner    (1001) docker     (123)    16483 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/modeling/test_remove_covariate_effect.py
--rw-r--r--   0 runner    (1001) docker     (123)     7765 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/modeling/test_results.py
--rw-r--r--   0 runner    (1001) docker     (123)      334 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/modeling/test_tmdd.py
--rw-r--r--   0 runner    (1001) docker     (123)      366 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/modeling/test_units.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.978861 pharmpy-core-0.96.0/tests/nonmem/
--rw-r--r--   0 runner    (1001) docker     (123)      495 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/nonmem/conftest.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.978861 pharmpy-core-0.96.0/tests/nonmem/output/
--rw-r--r--   0 runner    (1001) docker     (123)    13614 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/nonmem/output/test_nonmem_results_file.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.982861 pharmpy-core-0.96.0/tests/nonmem/records/
--rw-r--r--   0 runner    (1001) docker     (123)      295 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/nonmem/records/conftest.py
--rw-r--r--   0 runner    (1001) docker     (123)      834 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/nonmem/records/test_abbreviated.py
--rw-r--r--   0 runner    (1001) docker     (123)    28308 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/nonmem/records/test_code.py
--rw-r--r--   0 runner    (1001) docker     (123)     6044 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/nonmem/records/test_data.py
--rw-r--r--   0 runner    (1001) docker     (123)      587 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/nonmem/records/test_estimation_record.py
--rw-r--r--   0 runner    (1001) docker     (123)      155 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/nonmem/records/test_etas.py
--rw-r--r--   0 runner    (1001) docker     (123)     1525 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/nonmem/records/test_factory.py
--rw-r--r--   0 runner    (1001) docker     (123)     2372 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/nonmem/records/test_model_record.py
--rw-r--r--   0 runner    (1001) docker     (123)    10795 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/nonmem/records/test_omega.py
--rw-r--r--   0 runner    (1001) docker     (123)     7717 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/nonmem/records/test_option_record.py
--rw-r--r--   0 runner    (1001) docker     (123)      974 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/nonmem/records/test_problem.py
--rw-r--r--   0 runner    (1001) docker     (123)      339 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/nonmem/records/test_simulation.py
--rw-r--r--   0 runner    (1001) docker     (123)     1080 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/nonmem/records/test_sizes.py
--rw-r--r--   0 runner    (1001) docker     (123)      490 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/nonmem/records/test_subroutines.py
--rw-r--r--   0 runner    (1001) docker     (123)     4609 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/nonmem/records/test_theta.py
--rw-r--r--   0 runner    (1001) docker     (123)     8486 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/nonmem/test_advan.py
--rw-r--r--   0 runner    (1001) docker     (123)     2673 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/nonmem/test_des.py
--rw-r--r--   0 runner    (1001) docker     (123)      361 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/nonmem/test_fcon.py
--rw-r--r--   0 runner    (1001) docker     (123)     2045 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/nonmem/test_input.py
--rw-r--r--   0 runner    (1001) docker     (123)     8868 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/nonmem/test_modelfit_results.py
--rw-r--r--   0 runner    (1001) docker     (123)    35139 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/nonmem/test_nonmem_model.py
--rw-r--r--   0 runner    (1001) docker     (123)     3822 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/nonmem/test_nonmem_table.py
--rw-r--r--   0 runner    (1001) docker     (123)     1734 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/nonmem/test_parser.py
--rw-r--r--   0 runner    (1001) docker     (123)     5595 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/nonmem/test_read.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.982861 pharmpy-core-0.96.0/tests/testdata/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.982861 pharmpy-core-0.96.0/tests/testdata/frem/
--rw-r--r--   0 runner    (1001) docker     (123)    52275 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/frem/results.json
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.986861 pharmpy-core-0.96.0/tests/testdata/nonmem/
--rw-r--r--   0 runner    (1001) docker     (123)     4053 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/DDMODEL00000130
--rw-r--r--   0 runner    (1001) docker     (123)    59142 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/Simulated_CMS_colistin_PK_data.csv
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.986861 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/
--rw-r--r--   0 runner    (1001) docker     (123)      989 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real.cov
--rw-r--r--   0 runner    (1001) docker     (123)     2851 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real.ext
--rw-r--r--   0 runner    (1001) docker     (123)    21259 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real.lst
--rw-r--r--   0 runner    (1001) docker     (123)      668 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real.mod
--rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real.phi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.986861 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.990861 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/
--rw-r--r--   0 runner    (1001) docker     (123)      989 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_1.cov
--rw-r--r--   0 runner    (1001) docker     (123)     2851 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_1.ext
--rw-r--r--   0 runner    (1001) docker     (123)    22061 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_1.lst
--rw-r--r--   0 runner    (1001) docker     (123)     1009 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_1.mod
--rw-r--r--   0 runner    (1001) docker     (123)      989 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_10.cov
--rw-r--r--   0 runner    (1001) docker     (123)     2724 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_10.ext
--rw-r--r--   0 runner    (1001) docker     (123)    21670 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_10.lst
--rw-r--r--   0 runner    (1001) docker     (123)     1005 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_10.mod
--rw-r--r--   0 runner    (1001) docker     (123)      989 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_2.cov
--rw-r--r--   0 runner    (1001) docker     (123)     2724 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_2.ext
--rw-r--r--   0 runner    (1001) docker     (123)    21677 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_2.lst
--rw-r--r--   0 runner    (1001) docker     (123)     1012 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_2.mod
--rw-r--r--   0 runner    (1001) docker     (123)      989 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_3.cov
--rw-r--r--   0 runner    (1001) docker     (123)     2851 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_3.ext
--rw-r--r--   0 runner    (1001) docker     (123)    22067 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_3.lst
--rw-r--r--   0 runner    (1001) docker     (123)     1015 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_3.mod
--rw-r--r--   0 runner    (1001) docker     (123)      989 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_4.cov
--rw-r--r--   0 runner    (1001) docker     (123)     2724 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_4.ext
--rw-r--r--   0 runner    (1001) docker     (123)    21680 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_4.lst
--rw-r--r--   0 runner    (1001) docker     (123)     1015 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_4.mod
--rw-r--r--   0 runner    (1001) docker     (123)      989 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_5.cov
--rw-r--r--   0 runner    (1001) docker     (123)     2724 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_5.ext
--rw-r--r--   0 runner    (1001) docker     (123)    21680 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_5.lst
--rw-r--r--   0 runner    (1001) docker     (123)     1015 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_5.mod
--rw-r--r--   0 runner    (1001) docker     (123)      989 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_6.cov
--rw-r--r--   0 runner    (1001) docker     (123)     2724 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_6.ext
--rw-r--r--   0 runner    (1001) docker     (123)    21680 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_6.lst
--rw-r--r--   0 runner    (1001) docker     (123)     1015 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_6.mod
--rw-r--r--   0 runner    (1001) docker     (123)      989 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_7.cov
--rw-r--r--   0 runner    (1001) docker     (123)     2724 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_7.ext
--rw-r--r--   0 runner    (1001) docker     (123)    21680 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_7.lst
--rw-r--r--   0 runner    (1001) docker     (123)     1015 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_7.mod
--rw-r--r--   0 runner    (1001) docker     (123)      989 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_8.cov
--rw-r--r--   0 runner    (1001) docker     (123)     2978 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_8.ext
--rw-r--r--   0 runner    (1001) docker     (123)    22454 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_8.lst
--rw-r--r--   0 runner    (1001) docker     (123)     1015 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_8.mod
--rw-r--r--   0 runner    (1001) docker     (123)      989 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_9.cov
--rw-r--r--   0 runner    (1001) docker     (123)     2851 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_9.ext
--rw-r--r--   0 runner    (1001) docker     (123)    22067 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_9.lst
--rw-r--r--   0 runner    (1001) docker     (123)     1015 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_9.mod
--rw-r--r--   0 runner    (1001) docker     (123)     1020 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_1.mod
--rw-r--r--   0 runner    (1001) docker     (123)     1016 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_10.mod
--rw-r--r--   0 runner    (1001) docker     (123)     1023 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_2.mod
--rw-r--r--   0 runner    (1001) docker     (123)     1026 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_3.mod
--rw-r--r--   0 runner    (1001) docker     (123)     1026 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_4.mod
--rw-r--r--   0 runner    (1001) docker     (123)     1026 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_5.mod
--rw-r--r--   0 runner    (1001) docker     (123)     1026 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_6.mod
--rw-r--r--   0 runner    (1001) docker     (123)     1026 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_7.mod
--rw-r--r--   0 runner    (1001) docker     (123)     1026 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_8.mod
--rw-r--r--   0 runner    (1001) docker     (123)     1026 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_9.mod
--rw-r--r--   0 runner    (1001) docker     (123)     1730 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/meta.yaml
--rw-r--r--   0 runner    (1001) docker     (123)      168 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/skipped_individuals1.csv
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.990861 pharmpy-core-0.96.0/tests/testdata/nonmem/errors/
--rw-r--r--   0 runner    (1001) docker     (123)     1210 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/errors/control_stream_error.lst
--rw-r--r--   0 runner    (1001) docker     (123)    10369 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/errors/est_step_warning.lst
--rw-r--r--   0 runner    (1001) docker     (123)     9105 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/errors/estimate_near_boundary_warning.lst
--rw-r--r--   0 runner    (1001) docker     (123)     1014 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/errors/failed_run.ext
--rw-r--r--   0 runner    (1001) docker     (123)      422 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/errors/failed_run.mod
--rw-r--r--   0 runner    (1001) docker     (123)    23702 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/errors/no_header_error.ext
--rw-r--r--   0 runner    (1001) docker     (123)    19648 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/errors/no_header_error.lst
--rw-r--r--   0 runner    (1001) docker     (123)    13342 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/errors/rounding_error.lst
--rw-r--r--   0 runner    (1001) docker     (123)      819 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/errors/run_interrupted.ext
--rw-r--r--   0 runner    (1001) docker     (123)      345 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/errors/run_interrupted.mod
--rw-r--r--   0 runner    (1001) docker     (123)    10316 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/errors/zero_gradient_error.lst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.990861 pharmpy-core-0.96.0/tests/testdata/nonmem/fcon/
--rw-r--r--   0 runner    (1001) docker     (123)     6241 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/fcon/FCON
--rw-r--r--   0 runner    (1001) docker     (123)    39432 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/fcon/FDATA
--rw-r--r--   0 runner    (1001) docker     (123)       43 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/file.csv
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.934861 pharmpy-core-0.96.0/tests/testdata/nonmem/frem/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.994861 pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno/
--rw-r--r--   0 runner    (1001) docker     (123)    22896 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno/frem_dataset.dta
--rw-r--r--   0 runner    (1001) docker     (123)     1277 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno/model_3.ext
--rw-r--r--   0 runner    (1001) docker     (123)    11250 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno/model_3.lst
--rw-r--r--   0 runner    (1001) docker     (123)     1623 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno/model_3.mod
--rw-r--r--   0 runner    (1001) docker     (123)    14006 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno/model_3.phi
--rw-r--r--   0 runner    (1001) docker     (123)    14006 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno/model_3_input.phi
--rw-r--r--   0 runner    (1001) docker     (123)     4861 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno/model_4.cov
--rw-r--r--   0 runner    (1001) docker     (123)     2884 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno/model_4.ext
--rw-r--r--   0 runner    (1001) docker     (123)    26246 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno/model_4.lst
--rw-r--r--   0 runner    (1001) docker     (123)     1553 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno/model_4.mod
--rw-r--r--   0 runner    (1001) docker     (123)    13993 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno/model_4.phi
--rw-r--r--   0 runner    (1001) docker     (123)    14006 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno/model_4_input.phi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.994861 pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno_cat/
--rw-r--r--   0 runner    (1001) docker     (123)    24625 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno_cat/frem_dataset.dta
--rw-r--r--   0 runner    (1001) docker     (123)     4861 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno_cat/model_4.cor
--rw-r--r--   0 runner    (1001) docker     (123)     4861 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno_cat/model_4.cov
--rw-r--r--   0 runner    (1001) docker     (123)     2884 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno_cat/model_4.ext
--rw-r--r--   0 runner    (1001) docker     (123)    26183 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno_cat/model_4.lst
--rw-r--r--   0 runner    (1001) docker     (123)     1599 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno_cat/model_4.mod
--rw-r--r--   0 runner    (1001) docker     (123)    13993 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno_cat/model_4.phi
--rw-r--r--   0 runner    (1001) docker     (123)    14006 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno_cat/model_4_input.phi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.934861 pharmpy-core-0.96.0/tests/testdata/nonmem/linearize/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.994861 pharmpy-core-0.96.0/tests/testdata/nonmem/linearize/linearize_dir1/
--rw-r--r--   0 runner    (1001) docker     (123)       44 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/linearize/linearize_dir1/command.txt
--rw-r--r--   0 runner    (1001) docker     (123)     2472 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/linearize/linearize_dir1/pheno_linbase.ext
--rw-r--r--   0 runner    (1001) docker     (123)    14234 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/linearize/linearize_dir1/pheno_linbase.lst
--rw-r--r--   0 runner    (1001) docker     (123)      618 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/linearize/linearize_dir1/pheno_linbase.mod
--rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/linearize/linearize_dir1/pheno_linbase.phi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.994861 pharmpy-core-0.96.0/tests/testdata/nonmem/linearize/linearize_dir1/scm_dir1/
--rw-r--r--   0 runner    (1001) docker     (123)      653 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/linearize/linearize_dir1/scm_dir1/derivatives.ext
--rw-r--r--   0 runner    (1001) docker     (123)     9547 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/linearize/linearize_dir1/scm_dir1/derivatives.lst
--rw-r--r--   0 runner    (1001) docker     (123)      733 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/linearize/linearize_dir1/scm_dir1/derivatives.mod
--rw-r--r--   0 runner    (1001) docker     (123)     6986 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/linearize/linearize_dir1/scm_dir1/derivatives.phi
--rw-r--r--   0 runner    (1001) docker     (123)      190 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/minimal.mod
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.934861 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.994861 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/covariance/
--rw-r--r--   0 runner    (1001) docker     (123)     2032 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/covariance/pheno_nocovariance.coi
--rw-r--r--   0 runner    (1001) docker     (123)     1615 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/covariance/pheno_nocovariance.ext
--rw-r--r--   0 runner    (1001) docker     (123)    17620 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/covariance/pheno_nocovariance.lst
--rw-r--r--   0 runner    (1001) docker     (123)      815 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/covariance/pheno_nocovariance.mod
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.934861 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/multPROB/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.934861 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/multPROB/multEST/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.994861 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/multPROB/multEST/withSIM/
--rw-r--r--   0 runner    (1001) docker     (123)    14783 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/multPROB/multEST/withSIM/multprobmix_nm730.ext
--rw-r--r--   0 runner    (1001) docker     (123)    91887 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/multPROB/multEST/withSIM/multprobmix_nm730.lst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.934861 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.934861 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.994861 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/
--rw-r--r--   0 runner    (1001) docker     (123)    36515 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/anneal2_V7_30_beta.lst
--rw-r--r--   0 runner    (1001) docker     (123)    38720 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/pheno_multEST.dta
--rw-r--r--   0 runner    (1001) docker     (123)     1963 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/pheno_multEST.ext
--rw-r--r--   0 runner    (1001) docker     (123)    16505 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/pheno_multEST.lst
--rw-r--r--   0 runner    (1001) docker     (123)      384 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/pheno_multEST.mod
--rw-r--r--   0 runner    (1001) docker     (123)    13947 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/pheno_multEST.phi
--rw-r--r--   0 runner    (1001) docker     (123)    59168 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/superid2_6_V7_30_beta.lst
--rw-r--r--   0 runner    (1001) docker     (123)    37889 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/withBayes.cov
--rw-r--r--   0 runner    (1001) docker     (123)   115118 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/withBayes.ext
--rw-r--r--   0 runner    (1001) docker     (123)    82511 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/withBayes.lst
--rw-r--r--   0 runner    (1001) docker     (123)     2273 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/withBayes.mod
--rw-r--r--   0 runner    (1001) docker     (123)    75841 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/withBayes.phi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.998861 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/noESTwithSIM/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/noESTwithSIM/onlysim.ext
--rw-r--r--   0 runner    (1001) docker     (123)     5179 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/noESTwithSIM/onlysim.lst
--rw-r--r--   0 runner    (1001) docker     (123)      648 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/noESTwithSIM/onlysim.mod
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.934861 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.998861 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/
--rw-r--r--   0 runner    (1001) docker     (123)    15883 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/UseCase7.lst
--rw-r--r--   0 runner    (1001) docker     (123)    18122 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/example6b_V7_30_beta.lst
--rw-r--r--   0 runner    (1001) docker     (123)    15469 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/hessian_error.lst
--rw-r--r--   0 runner    (1001) docker     (123)    26695 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/large_s_matrix_cov_fail.lst
--rw-r--r--   0 runner    (1001) docker     (123)      688 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/maxeval0.ext
--rw-r--r--   0 runner    (1001) docker     (123)     8760 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/maxeval0.lst
--rw-r--r--   0 runner    (1001) docker     (123)      661 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/maxeval0.mod
--rw-r--r--   0 runner    (1001) docker     (123)      972 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/maxeval3.cov
--rw-r--r--   0 runner    (1001) docker     (123)     1564 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/maxeval3.ext
--rw-r--r--   0 runner    (1001) docker     (123)    17548 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/maxeval3.lst
--rw-r--r--   0 runner    (1001) docker     (123)      691 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/maxeval3.mod
--rw-r--r--   0 runner    (1001) docker     (123)     6956 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/maxeval3.phi
--rw-r--r--   0 runner    (1001) docker     (123)    13203 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/mox_fail_nonp.lst
--rw-r--r--   0 runner    (1001) docker     (123)    14451 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/mox_nocov_nonp.lst
--rw-r--r--   0 runner    (1001) docker     (123)     2492 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/near_bounds.ext
--rw-r--r--   0 runner    (1001) docker     (123)    11801 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/near_bounds.lst
--rw-r--r--   0 runner    (1001) docker     (123)     1393 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/near_bounds.mod
--rw-r--r--   0 runner    (1001) docker     (123)     5460 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/nm710_fail_negV.lst
--rw-r--r--   0 runner    (1001) docker     (123)    38720 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/pheno.dta
--rw-r--r--   0 runner    (1001) docker     (123)     1170 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/pheno.ext
--rw-r--r--   0 runner    (1001) docker     (123)    17299 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/pheno.lst
--rw-r--r--   0 runner    (1001) docker     (123)      735 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/pheno.mod
--rw-r--r--   0 runner    (1001) docker     (123)     6933 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/pheno.phi
--rw-r--r--   0 runner    (1001) docker     (123)    16143 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/pheno_nonp.lst
--rw-r--r--   0 runner    (1001) docker     (123)    14090 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/phenocorr.lst
--rw-r--r--   0 runner    (1001) docker     (123)    54699 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/sparse_matrix_with_msfi.lst
--rw-r--r--   0 runner    (1001) docker     (123)    31702 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/theo.lst
--rw-r--r--   0 runner    (1001) docker     (123)    19741 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/theo_nonp.lst
--rw-r--r--   0 runner    (1001) docker     (123)    31702 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/theo_withcov.lst
--rw-r--r--   0 runner    (1001) docker     (123)    13140 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/warfarin_ddmore.lst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.998861 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/withSIM/
--rw-r--r--   0 runner    (1001) docker     (123)   178666 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/withSIM/control3boot.ext
--rw-r--r--   0 runner    (1001) docker     (123)  1091059 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/withSIM/control3boot.res
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.002861 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/simfit/
--rw-r--r--   0 runner    (1001) docker     (123)     4152 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/simfit/sim-1.ext
--rw-r--r--   0 runner    (1001) docker     (123)    38485 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/simfit/sim-1.lst
--rw-r--r--   0 runner    (1001) docker     (123)      841 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/simfit/sim-1.mod
--rw-r--r--   0 runner    (1001) docker     (123)    41718 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/simfit/sim-1.phi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.002861 pharmpy-core-0.96.0/tests/testdata/nonmem/modeling/
--rw-r--r--   0 runner    (1001) docker     (123)      857 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modeling/pheno_1transit.mod
--rw-r--r--   0 runner    (1001) docker     (123)      884 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modeling/pheno_2transits.mod
--rw-r--r--   0 runner    (1001) docker     (123)      665 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modeling/pheno_advan1.mod
--rw-r--r--   0 runner    (1001) docker     (123)      819 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modeling/pheno_advan11.mod
--rw-r--r--   0 runner    (1001) docker     (123)      846 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modeling/pheno_advan12.mod
--rw-r--r--   0 runner    (1001) docker     (123)      707 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modeling/pheno_advan1_zero_order.mod
--rw-r--r--   0 runner    (1001) docker     (123)      701 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modeling/pheno_advan2.mod
--rw-r--r--   0 runner    (1001) docker     (123)      719 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modeling/pheno_advan2_seq.mod
--rw-r--r--   0 runner    (1001) docker     (123)      735 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modeling/pheno_advan3.mod
--rw-r--r--   0 runner    (1001) docker     (123)      769 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modeling/pheno_advan4.mod
--rw-r--r--   0 runner    (1001) docker     (123)      826 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modeling/pheno_advan5_depot.mod
--rw-r--r--   0 runner    (1001) docker     (123)      784 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modeling/pheno_advan5_nodepot.mod
--rw-r--r--   0 runner    (1001) docker     (123)    18812 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modeling/pheno_zero_order.csv
--rw-r--r--   0 runner    (1001) docker     (123)      937 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/modeling/transit_indirect_reabsorption.mod
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.006861 pharmpy-core-0.96.0/tests/testdata/nonmem/models/
--rw-r--r--   0 runner    (1001) docker     (123)     1546 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/fviii6.datainfo
--rw-r--r--   0 runner    (1001) docker     (123)     3072 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/fviii6.mod
--rw-r--r--   0 runner    (1001) docker     (123)      336 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/fviii6.prn
--rw-r--r--   0 runner    (1001) docker     (123)     1716 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox1.cov
--rw-r--r--   0 runner    (1001) docker     (123)     1827 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox1.ext
--rw-r--r--   0 runner    (1001) docker     (123)    19098 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox1.lst
--rw-r--r--   0 runner    (1001) docker     (123)      762 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox1.mod
--rw-r--r--   0 runner    (1001) docker     (123)    12566 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox1.phi
--rw-r--r--   0 runner    (1001) docker     (123)     1306 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox2.ext
--rw-r--r--   0 runner    (1001) docker     (123)    90456 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox2.lst
--rw-r--r--   0 runner    (1001) docker     (123)      703 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox2.mod
--rw-r--r--   0 runner    (1001) docker     (123)    12377 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox2.phi
--rw-r--r--   0 runner    (1001) docker     (123)     1716 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox_2comp.cov
--rw-r--r--   0 runner    (1001) docker     (123)     1827 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox_2comp.ext
--rw-r--r--   0 runner    (1001) docker     (123)    21336 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox_2comp.lst
--rw-r--r--   0 runner    (1001) docker     (123)      704 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox_2comp.mod
--rw-r--r--   0 runner    (1001) docker     (123)    12566 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox_2comp.phi
--rw-r--r--   0 runner    (1001) docker     (123)   175384 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox_simulated_log.csv
--rw-r--r--   0 runner    (1001) docker     (123)   185992 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox_simulated_normal.csv
--rw-r--r--   0 runner    (1001) docker     (123)     4764 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox_simulated_normal.datainfo
--rw-r--r--   0 runner    (1001) docker     (123)   105888 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/moxo_simulated_amd.csv
--rw-r--r--   0 runner    (1001) docker     (123)     2816 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/moxo_simulated_amd.datainfo
--rw-r--r--   0 runner    (1001) docker     (123)    70155 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/mytab_mox2
--rw-r--r--   0 runner    (1001) docker     (123)    11500 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/pef.csv
--rwxr-xr-x   0 runner    (1001) docker     (123)      189 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/pef.mod
--rw-r--r--   0 runner    (1001) docker     (123)     1346 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/pheno_advan3_trans1.ext
--rw-r--r--   0 runner    (1001) docker     (123)    12218 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/pheno_advan3_trans1.lst
--rw-r--r--   0 runner    (1001) docker     (123)      452 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/pheno_advan3_trans1.mod
--rw-r--r--   0 runner    (1001) docker     (123)    10093 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/pheno_advan3_trans1.phi
--rw-r--r--   0 runner    (1001) docker     (123)      367 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/pheno_conc.mod
--rw-r--r--   0 runner    (1001) docker     (123)     6107 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/pheno_dvid.csv
--rw-r--r--   0 runner    (1001) docker     (123)      533 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/pheno_dvid.mod
--rw-r--r--   0 runner    (1001) docker     (123)      989 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/pheno_noifs.coi
--rw-r--r--   0 runner    (1001) docker     (123)      793 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/pheno_noifs.cor
--rw-r--r--   0 runner    (1001) docker     (123)      793 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/pheno_noifs.cov
--rw-r--r--   0 runner    (1001) docker     (123)      982 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/pheno_noifs.ext
--rw-r--r--   0 runner    (1001) docker     (123)    10527 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/pheno_noifs.lst
--rw-r--r--   0 runner    (1001) docker     (123)      428 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/pheno_noifs.mod
--rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/pheno_noifs.phi
--rw-r--r--   0 runner    (1001) docker     (123)      709 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/pheno_trans1.ext
--rw-r--r--   0 runner    (1001) docker     (123)    10693 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/pheno_trans1.lst
--rw-r--r--   0 runner    (1001) docker     (123)      273 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/pheno_trans1.mod
--rw-r--r--   0 runner    (1001) docker     (123)     4633 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/models/pheno_trans1.phi
--rw-r--r--   0 runner    (1001) docker     (123)      763 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/pheno.datainfo
--rw-r--r--   0 runner    (1001) docker     (123)    38720 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/pheno.dta
--rw-r--r--   0 runner    (1001) docker     (123)      982 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/pheno.ext
--rw-r--r--   0 runner    (1001) docker     (123)    10540 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/pheno.lst
--rw-r--r--   0 runner    (1001) docker     (123)      345 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/pheno.mod
--rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/pheno.phi
--rw-r--r--   0 runner    (1001) docker     (123)      470 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_abbr.mod
--rw-r--r--   0 runner    (1001) docker     (123)      354 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_abbr_comments.mod
--rw-r--r--   0 runner    (1001) docker     (123)      629 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_block.mod
--rw-r--r--   0 runner    (1001) docker     (123)      341 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_clashing_symbols.mod
--rw-r--r--   0 runner    (1001) docker     (123)      947 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_etas.mod
--rw-r--r--   0 runner    (1001) docker     (123)      736 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_multivariate_piecewise.mod
--rw-r--r--   0 runner    (1001) docker     (123)      357 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_nm750.mod
--rw-r--r--   0 runner    (1001) docker     (123)    38720 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_no_obs_1stID.dta
--rw-r--r--   0 runner    (1001) docker     (123)    36053 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_rate.dta
--rw-r--r--   0 runner    (1001) docker     (123)      989 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_real.coi
--rw-r--r--   0 runner    (1001) docker     (123)      989 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_real.cor
--rw-r--r--   0 runner    (1001) docker     (123)      989 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_real.cov
--rw-r--r--   0 runner    (1001) docker     (123)     2851 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_real.ext
--rw-r--r--   0 runner    (1001) docker     (123)    21259 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_real.lst
--rw-r--r--   0 runner    (1001) docker     (123)      666 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_real.mod
--rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_real.phi
--rw-r--r--   0 runner    (1001) docker     (123)    90151 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_real.tab
--rw-r--r--   0 runner    (1001) docker     (123)    22114 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_real.xml
--rw-r--r--   0 runner    (1001) docker     (123)   298562 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_real_linbase.dta
--rw-r--r--   0 runner    (1001) docker     (123)     1288 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_real_linbase.ext
--rw-r--r--   0 runner    (1001) docker     (123)    28308 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_real_linbase.lst
--rw-r--r--   0 runner    (1001) docker     (123)      712 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_real_linbase.mod
--rw-r--r--   0 runner    (1001) docker     (123)     6933 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_real_linbase.phi
--rw-r--r--   0 runner    (1001) docker     (123)    17010 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_real_linbase.tab
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.010861 pharmpy-core-0.96.0/tests/testdata/nonmem/qa/
--rw-r--r--   0 runner    (1001) docker     (123)   370034 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/qa/add_etas_linbase.dta
--rw-r--r--   0 runner    (1001) docker     (123)     4838 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/qa/add_etas_linbase.ext
--rw-r--r--   0 runner    (1001) docker     (123)    16579 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/qa/add_etas_linbase.lst
--rw-r--r--   0 runner    (1001) docker     (123)      873 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/qa/add_etas_linbase.mod
--rw-r--r--   0 runner    (1001) docker     (123)     2350 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/qa/boxcox.ext
--rw-r--r--   0 runner    (1001) docker     (123)    14595 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/qa/boxcox.lst
--rw-r--r--   0 runner    (1001) docker     (123)      803 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/qa/boxcox.mod
--rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/qa/boxcox.phi
--rw-r--r--   0 runner    (1001) docker     (123)    11716 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/qa/cdd_results.json
--rw-r--r--   0 runner    (1001) docker     (123)     2824 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/qa/fullblock.ext
--rw-r--r--   0 runner    (1001) docker     (123)    17210 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/qa/fullblock.lst
--rw-r--r--   0 runner    (1001) docker     (123)      653 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/qa/fullblock.mod
--rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/qa/fullblock.phi
--rw-r--r--   0 runner    (1001) docker     (123)     2620 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/qa/iov.ext
--rw-r--r--   0 runner    (1001) docker     (123)    12617 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/qa/iov.lst
--rw-r--r--   0 runner    (1001) docker     (123)      662 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/qa/iov.mod
--rw-r--r--   0 runner    (1001) docker     (123)    24133 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/qa/iov.phi
--rw-r--r--   0 runner    (1001) docker     (123)   262826 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/qa/pheno_linbase.dta
--rw-r--r--   0 runner    (1001) docker     (123)     2472 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/qa/pheno_linbase.ext
--rw-r--r--   0 runner    (1001) docker     (123)    15014 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/qa/pheno_linbase.lst
--rw-r--r--   0 runner    (1001) docker     (123)      638 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/qa/pheno_linbase.mod
--rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/qa/pheno_linbase.phi
--rw-r--r--   0 runner    (1001) docker     (123)     3943 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/qa/resmod_results.json
--rw-r--r--   0 runner    (1001) docker     (123)     2198 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/qa/scm_results.json
--rw-r--r--   0 runner    (1001) docker     (123)   392990 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/qa/simeval_results.json
--rw-r--r--   0 runner    (1001) docker     (123)     3262 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/qa/tdist.ext
--rw-r--r--   0 runner    (1001) docker     (123)    17544 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/qa/tdist.lst
--rw-r--r--   0 runner    (1001) docker     (123)     1045 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/qa/tdist.mod
--rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/qa/tdist.phi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.010861 pharmpy-core-0.96.0/tests/testdata/nonmem/ruvsearch/
--rw-r--r--   0 runner    (1001) docker     (123)     1512 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/ruvsearch/mox3.ext
--rw-r--r--   0 runner    (1001) docker     (123)    13182 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/ruvsearch/mox3.lst
--rw-r--r--   0 runner    (1001) docker     (123)      672 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/ruvsearch/mox3.mod
--rw-r--r--   0 runner    (1001) docker     (123)    12417 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/ruvsearch/mox3.phi
--rw-r--r--   0 runner    (1001) docker     (123)   276902 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/ruvsearch/moxo_simulated_resmod.csv
--rw-r--r--   0 runner    (1001) docker     (123)   180553 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/ruvsearch/mytab
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.014861 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.014861 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/backward_dir1/
--rw-r--r--   0 runner    (1001) docker     (123)      337 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/backward_dir1/config_fake.scm
--rw-r--r--   0 runner    (1001) docker     (123)     1812 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/backward_dir1/meta.yaml
--rw-r--r--   0 runner    (1001) docker     (123)     3068 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/backward_dir1/scmlog.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.014861 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/gofofv_dir1/
--rw-r--r--   0 runner    (1001) docker     (123)    10037 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/gofofv_dir1/scmlog.txt
--rw-r--r--   0 runner    (1001) docker     (123)     5383 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/localmin.logf
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.014861 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/log_steps/
--rw-r--r--   0 runner    (1001) docker     (123)      565 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/log_steps/backward_ofv_1.txt
--rw-r--r--   0 runner    (1001) docker     (123)      434 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/log_steps/backward_pval_1.txt
--rw-r--r--   0 runner    (1001) docker     (123)      215 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/log_steps/backward_pval_2.txt
--rw-r--r--   0 runner    (1001) docker     (123)      809 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/log_steps/forward_ofv_1.txt
--rw-r--r--   0 runner    (1001) docker     (123)      761 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/log_steps/forward_pval_1.txt
--rw-r--r--   0 runner    (1001) docker     (123)     3813 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/log_steps/forward_pval_2.txt
--rw-r--r--   0 runner    (1001) docker     (123)     2723 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/log_steps/forward_pval_3.txt
--rw-r--r--   0 runner    (1001) docker     (123)      325 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/log_steps/forward_pval_4.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.014861 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/mergeofv_dir1/
--rw-r--r--   0 runner    (1001) docker     (123)      260 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/mergeofv_dir1/config_havebaserun.scm
--rw-r--r--   0 runner    (1001) docker     (123)     1896 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/mergeofv_dir1/meta.yaml
--rw-r--r--   0 runner    (1001) docker     (123)    38957 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/mergeofv_dir1/scmlog.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.014861 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/mergeofv_dir2/
--rw-r--r--   0 runner    (1001) docker     (123)      187 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/mergeofv_dir2/config_havebaserun.scm
--rw-r--r--   0 runner    (1001) docker     (123)     1882 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/mergeofv_dir2/meta.yaml
--rw-r--r--   0 runner    (1001) docker     (123)    20500 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/mergeofv_dir2/scmlog.txt
--rw-r--r--   0 runner    (1001) docker     (123)     2115 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/meta.yaml
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.014861 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/onlyforward_dir1/
--rw-r--r--   0 runner    (1001) docker     (123)      318 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/onlyforward_dir1/config_normal.scm
--rw-r--r--   0 runner    (1001) docker     (123)     1819 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/onlyforward_dir1/meta.yaml
--rw-r--r--   0 runner    (1001) docker     (123)     1762 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/onlyforward_dir1/scmlog.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.014861 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/scm_dir1/
--rw-r--r--   0 runner    (1001) docker     (123)     8045 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/scm_dir1/scmlog.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.014861 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/scmplus_dir1/
--rw-r--r--   0 runner    (1001) docker     (123)     6870 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/scm/scmplus_dir1/scmlog.txt
--rw-r--r--   0 runner    (1001) docker     (123)   108031 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/sdtab1
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.014861 pharmpy-core-0.96.0/tests/testdata/nonmem/secondary_parameters/
--rw-r--r--   0 runner    (1001) docker     (123)      793 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/secondary_parameters/pheno.cov
--rw-r--r--   0 runner    (1001) docker     (123)    38720 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/secondary_parameters/pheno.dta
--rw-r--r--   0 runner    (1001) docker     (123)     1324 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/secondary_parameters/pheno.ext
--rw-r--r--   0 runner    (1001) docker     (123)    16221 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/secondary_parameters/pheno.lst
--rw-r--r--   0 runner    (1001) docker     (123)      357 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/secondary_parameters/pheno.mod
--rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/secondary_parameters/pheno.phi
--rw-r--r--   0 runner    (1001) docker     (123)      793 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/secondary_parameters/run1.cov
--rw-r--r--   0 runner    (1001) docker     (123)     1324 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/secondary_parameters/run1.ext
--rw-r--r--   0 runner    (1001) docker     (123)    16509 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/secondary_parameters/run1.lst
--rw-r--r--   0 runner    (1001) docker     (123)      365 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/secondary_parameters/run1.mod
--rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/secondary_parameters/run1.phi
--rw-r--r--   0 runner    (1001) docker     (123)      989 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/secondary_parameters/run2.cov
--rw-r--r--   0 runner    (1001) docker     (123)     1454 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/secondary_parameters/run2.ext
--rw-r--r--   0 runner    (1001) docker     (123)    17071 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/secondary_parameters/run2.lst
--rw-r--r--   0 runner    (1001) docker     (123)      484 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/secondary_parameters/run2.mod
--rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/nonmem/secondary_parameters/run2.phi
--rw-r--r--   0 runner    (1001) docker     (123)    16730 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/pheno_data.csv
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.938861 pharmpy-core-0.96.0/tests/testdata/psn/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.018861 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/
--rw-r--r--   0 runner    (1001) docker     (123)       50 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/command.txt
--rw-r--r--   0 runner    (1001) docker     (123)    13424 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/est_data0.dta
--rw-r--r--   0 runner    (1001) docker     (123)    13450 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/est_data1.dta
--rw-r--r--   0 runner    (1001) docker     (123)    13336 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/est_data2.dta
--rw-r--r--   0 runner    (1001) docker     (123)    13843 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/est_data3.dta
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.022861 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/
--rw-r--r--   0 runner    (1001) docker     (123)      793 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model0.cor
--rw-r--r--   0 runner    (1001) docker     (123)      793 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model0.cov
--rw-r--r--   0 runner    (1001) docker     (123)     1324 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model0.ext
--rw-r--r--   0 runner    (1001) docker     (123)    17040 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model0.lst
--rw-r--r--   0 runner    (1001) docker     (123)      394 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model0.mod
--rw-r--r--   0 runner    (1001) docker     (123)     5263 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model0.phi
--rw-r--r--   0 runner    (1001) docker     (123)      793 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model1.cor
--rw-r--r--   0 runner    (1001) docker     (123)      793 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model1.cov
--rw-r--r--   0 runner    (1001) docker     (123)     1324 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model1.ext
--rw-r--r--   0 runner    (1001) docker     (123)    17040 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model1.lst
--rw-r--r--   0 runner    (1001) docker     (123)      394 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model1.mod
--rw-r--r--   0 runner    (1001) docker     (123)     5263 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model1.phi
--rw-r--r--   0 runner    (1001) docker     (123)      793 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model2.cor
--rw-r--r--   0 runner    (1001) docker     (123)      793 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model2.cov
--rw-r--r--   0 runner    (1001) docker     (123)     1324 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model2.ext
--rw-r--r--   0 runner    (1001) docker     (123)    17040 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model2.lst
--rw-r--r--   0 runner    (1001) docker     (123)      394 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model2.mod
--rw-r--r--   0 runner    (1001) docker     (123)     5263 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model2.phi
--rw-r--r--   0 runner    (1001) docker     (123)      793 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model3.cor
--rw-r--r--   0 runner    (1001) docker     (123)      793 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model3.cov
--rw-r--r--   0 runner    (1001) docker     (123)     1324 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model3.ext
--rw-r--r--   0 runner    (1001) docker     (123)    17040 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model3.lst
--rw-r--r--   0 runner    (1001) docker     (123)      394 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model3.mod
--rw-r--r--   0 runner    (1001) docker     (123)     5377 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model3.phi
--rw-r--r--   0 runner    (1001) docker     (123)      767 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/pred_model0.ext
--rw-r--r--   0 runner    (1001) docker     (123)    11625 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/pred_model0.lst
--rw-r--r--   0 runner    (1001) docker     (123)      407 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/pred_model0.mod
--rw-r--r--   0 runner    (1001) docker     (123)     1970 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/pred_model0.phi
--rw-r--r--   0 runner    (1001) docker     (123)      767 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/pred_model1.ext
--rw-r--r--   0 runner    (1001) docker     (123)    11637 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/pred_model1.lst
--rw-r--r--   0 runner    (1001) docker     (123)      406 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/pred_model1.mod
--rw-r--r--   0 runner    (1001) docker     (123)     1970 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/pred_model1.phi
--rw-r--r--   0 runner    (1001) docker     (123)      767 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/pred_model2.ext
--rw-r--r--   0 runner    (1001) docker     (123)    11623 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/pred_model2.lst
--rw-r--r--   0 runner    (1001) docker     (123)      405 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/pred_model2.mod
--rw-r--r--   0 runner    (1001) docker     (123)     1970 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/pred_model2.phi
--rw-r--r--   0 runner    (1001) docker     (123)      806 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/pred_model3.cor
--rw-r--r--   0 runner    (1001) docker     (123)      806 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/pred_model3.cov
--rw-r--r--   0 runner    (1001) docker     (123)      995 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/pred_model3.ext
--rw-r--r--   0 runner    (1001) docker     (123)    15116 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/pred_model3.lst
--rw-r--r--   0 runner    (1001) docker     (123)      405 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/pred_model3.mod
--rw-r--r--   0 runner    (1001) docker     (123)     1856 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/pred_model3.phi
--rw-r--r--   0 runner    (1001) docker     (123)     1509 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/meta.yaml
--rw-r--r--   0 runner    (1001) docker     (123)     4615 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/pred_data0.dta
--rw-r--r--   0 runner    (1001) docker     (123)     4589 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/pred_data1.dta
--rw-r--r--   0 runner    (1001) docker     (123)     4703 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/pred_data2.dta
--rw-r--r--   0 runner    (1001) docker     (123)     4196 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/pred_data3.dta
--rw-r--r--   0 runner    (1001) docker     (123)     1579 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/version_and_option_info.txt
--rw-r--r--   0 runner    (1001) docker     (123)      265 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/xv_result.csv
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.022861 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/
--rw-r--r--   0 runner    (1001) docker     (123)       50 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/command.txt
--rw-r--r--   0 runner    (1001) docker     (123)      353 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/covariates_summary.csv
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.022861 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/final_models/
--rw-r--r--   0 runner    (1001) docker     (123)     1983 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/final_models/model_4.ext
--rw-r--r--   0 runner    (1001) docker     (123)    14761 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/final_models/model_4.lst
--rw-r--r--   0 runner    (1001) docker     (123)     1110 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/final_models/model_4.mod
--rw-r--r--   0 runner    (1001) docker     (123)    13993 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/final_models/model_4.phi
--rw-r--r--   0 runner    (1001) docker     (123)    14006 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/final_models/model_4_input.phi
--rw-r--r--   0 runner    (1001) docker     (123)    19440 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/frem_dataset.dta
--rw-r--r--   0 runner    (1001) docker     (123)     3246 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/frem_results.csv
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.026861 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/
--rw-r--r--   0 runner    (1001) docker     (123)      613 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/filter_data_model.ext
--rw-r--r--   0 runner    (1001) docker     (123)     9040 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/filter_data_model.lst
--rw-r--r--   0 runner    (1001) docker     (123)      525 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/filter_data_model.mod
--rw-r--r--   0 runner    (1001) docker     (123)     6946 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/filter_data_model.phi
--rw-r--r--   0 runner    (1001) docker     (123)    93135 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/filtered_plus_type0.dta
--rw-r--r--   0 runner    (1001) docker     (123)      793 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_1.cov
--rw-r--r--   0 runner    (1001) docker     (123)     1324 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_1.ext
--rw-r--r--   0 runner    (1001) docker     (123)    16221 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_1.lst
--rw-r--r--   0 runner    (1001) docker     (123)      393 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_1.mod
--rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_1.phi
--rw-r--r--   0 runner    (1001) docker     (123)      393 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_1b.mod
--rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_1b.phi
--rw-r--r--   0 runner    (1001) docker     (123)     4392 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_2.cor
--rw-r--r--   0 runner    (1001) docker     (123)     4392 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_2.cov
--rw-r--r--   0 runner    (1001) docker     (123)     1996 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_2.ext
--rw-r--r--   0 runner    (1001) docker     (123)    21654 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_2.lst
--rw-r--r--   0 runner    (1001) docker     (123)     1083 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_2.mod
--rw-r--r--   0 runner    (1001) docker     (123)    14006 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_2.phi
--rw-r--r--   0 runner    (1001) docker     (123)    13826 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_2_input.phi
--rw-r--r--   0 runner    (1001) docker     (123)     1225 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_3.ext
--rw-r--r--   0 runner    (1001) docker     (123)    10472 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_3.lst
--rw-r--r--   0 runner    (1001) docker     (123)     1162 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_3.mod
--rw-r--r--   0 runner    (1001) docker     (123)    14006 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_3.phi
--rw-r--r--   0 runner    (1001) docker     (123)    14006 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_3_input.phi
--rw-r--r--   0 runner    (1001) docker     (123)     1225 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_3b.ext
--rw-r--r--   0 runner    (1001) docker     (123)    10750 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_3b.lst
--rw-r--r--   0 runner    (1001) docker     (123)     1188 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_3b.mod
--rw-r--r--   0 runner    (1001) docker     (123)    14006 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_3b.phi
--rw-r--r--   0 runner    (1001) docker     (123)    14006 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_3b_input.phi
--rw-r--r--   0 runner    (1001) docker     (123)     1816 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/meta.yaml
--rw-r--r--   0 runner    (1001) docker     (123)     2970 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/proposal_density.cov
--rw-r--r--   0 runner    (1001) docker     (123)     1852 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/version_and_option_info.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.026861 pharmpy-core-0.96.0/tests/testdata/psn/qa_dir1/
--rw-r--r--   0 runner    (1001) docker     (123)       39 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/qa_dir1/command.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.026861 pharmpy-core-0.96.0/tests/testdata/psn/qa_dir1/linearize_run/
--rw-r--r--   0 runner    (1001) docker     (123)     5485 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/qa_dir1/linearize_run/results.json
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.026861 pharmpy-core-0.96.0/tests/testdata/psn/qa_dir1/linearize_run/scm_dir1/
--rw-r--r--   0 runner    (1001) docker     (123)      705 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/qa_dir1/linearize_run/scm_dir1/derivatives.ext
--rw-r--r--   0 runner    (1001) docker     (123)    12131 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/qa_dir1/linearize_run/scm_dir1/derivatives.lst
--rw-r--r--   0 runner    (1001) docker     (123)     1280 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/qa_dir1/linearize_run/scm_dir1/derivatives.mod
--rw-r--r--   0 runner    (1001) docker     (123)     6986 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/qa_dir1/linearize_run/scm_dir1/derivatives.phi
--rw-r--r--   0 runner    (1001) docker     (123)   137744 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/qa_dir1/linearize_run/scm_dir1/extra_table
--rw-r--r--   0 runner    (1001) docker     (123)   316422 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/qa_dir1/pheno_real_linbase.dta
--rw-r--r--   0 runner    (1001) docker     (123)     1856 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/qa_dir1/pheno_real_linbase.ext
--rw-r--r--   0 runner    (1001) docker     (123)    13850 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/qa_dir1/pheno_real_linbase.lst
--rw-r--r--   0 runner    (1001) docker     (123)      700 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/qa_dir1/pheno_real_linbase.mod
--rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/qa_dir1/pheno_real_linbase.phi
--rw-r--r--   0 runner    (1001) docker     (123)    11536 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/qa_dir1/results_summary.yaml
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.026861 pharmpy-core-0.96.0/tests/testdata/psn/resmod_dir1/
--rw-r--r--   0 runner    (1001) docker     (123)     1985 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/resmod_dir1/resmod_results.csv
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.026861 pharmpy-core-0.96.0/tests/testdata/psn/resmod_dir2/
--rw-r--r--   0 runner    (1001) docker     (123)    11647 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/resmod_dir2/resmod_results.csv
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.026861 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.030861 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/
--rw-r--r--   0 runner    (1001) docker     (123)    63331 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/orig_pred.dta
--rw-r--r--   0 runner    (1001) docker     (123)      793 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/original.cor
--rw-r--r--   0 runner    (1001) docker     (123)      793 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/original.cov
--rw-r--r--   0 runner    (1001) docker     (123)     1324 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/original.ext
--rw-r--r--   0 runner    (1001) docker     (123)      591 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/original.mod
--rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/original.phi
--rw-r--r--   0 runner    (1001) docker     (123)    54391 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/original_res_table.dta
--rw-r--r--   0 runner    (1001) docker     (123)    38720 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/pheno.dta
--rw-r--r--   0 runner    (1001) docker     (123)     1306 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-1.ext
--rw-r--r--   0 runner    (1001) docker     (123)    14039 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-1.lst
--rw-r--r--   0 runner    (1001) docker     (123)      509 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-1.mod
--rw-r--r--   0 runner    (1001) docker     (123)    13972 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-1.phi
--rw-r--r--   0 runner    (1001) docker     (123)     1306 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-2.ext
--rw-r--r--   0 runner    (1001) docker     (123)    14039 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-2.lst
--rw-r--r--   0 runner    (1001) docker     (123)      509 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-2.mod
--rw-r--r--   0 runner    (1001) docker     (123)    13972 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-2.phi
--rw-r--r--   0 runner    (1001) docker     (123)      653 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-3.ext
--rw-r--r--   0 runner    (1001) docker     (123)     9500 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-3.lst
--rw-r--r--   0 runner    (1001) docker     (123)      509 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-3.mod
--rw-r--r--   0 runner    (1001) docker     (123)     6986 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-3.phi
--rw-r--r--   0 runner    (1001) docker     (123)      653 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-4.ext
--rw-r--r--   0 runner    (1001) docker     (123)     9500 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-4.lst
--rw-r--r--   0 runner    (1001) docker     (123)      509 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-4.mod
--rw-r--r--   0 runner    (1001) docker     (123)     6986 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-4.phi
--rw-r--r--   0 runner    (1001) docker     (123)      653 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-5.ext
--rw-r--r--   0 runner    (1001) docker     (123)     9500 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-5.lst
--rw-r--r--   0 runner    (1001) docker     (123)      509 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-5.mod
--rw-r--r--   0 runner    (1001) docker     (123)     6986 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-5.phi
--rw-r--r--   0 runner    (1001) docker     (123)      653 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-6.ext
--rw-r--r--   0 runner    (1001) docker     (123)     9500 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-6.lst
--rw-r--r--   0 runner    (1001) docker     (123)      509 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-6.mod
--rw-r--r--   0 runner    (1001) docker     (123)     6986 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-6.phi
--rw-r--r--   0 runner    (1001) docker     (123)      653 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-7.ext
--rw-r--r--   0 runner    (1001) docker     (123)     9500 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-7.lst
--rw-r--r--   0 runner    (1001) docker     (123)      509 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-7.mod
--rw-r--r--   0 runner    (1001) docker     (123)     6986 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-7.phi
--rw-r--r--   0 runner    (1001) docker     (123)      653 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-8.ext
--rw-r--r--   0 runner    (1001) docker     (123)     9500 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-8.lst
--rw-r--r--   0 runner    (1001) docker     (123)      509 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-8.mod
--rw-r--r--   0 runner    (1001) docker     (123)     6986 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-8.phi
--rw-r--r--   0 runner    (1001) docker     (123)    73024 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim_res_table-1.dta
--rw-r--r--   0 runner    (1001) docker     (123)    73024 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim_res_table-2.dta
--rw-r--r--   0 runner    (1001) docker     (123)    36512 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim_res_table-3.dta
--rw-r--r--   0 runner    (1001) docker     (123)    36512 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim_res_table-4.dta
--rw-r--r--   0 runner    (1001) docker     (123)    36512 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim_res_table-5.dta
--rw-r--r--   0 runner    (1001) docker     (123)    36512 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim_res_table-6.dta
--rw-r--r--   0 runner    (1001) docker     (123)    36512 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim_res_table-7.dta
--rw-r--r--   0 runner    (1001) docker     (123)    36512 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim_res_table-8.dta
--rw-r--r--   0 runner    (1001) docker     (123)    21489 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/summary_cwres.csv
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.034861 pharmpy-core-0.96.0/tests/testdata/results/
--rw-r--r--   0 runner    (1001) docker     (123)    24788 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/allometry_results.json
--rw-r--r--   0 runner    (1001) docker     (123)    50648 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/amd_results.json
--rw-r--r--   0 runner    (1001) docker     (123)   130598 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/bootstrap_results.json
--rw-r--r--   0 runner    (1001) docker     (123)    12291 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/cdd_results.json
--rw-r--r--   0 runner    (1001) docker     (123)  1360720 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/covsearch_results.json
--rw-r--r--   0 runner    (1001) docker     (123)     6524 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/estmethod_results.json
--rw-r--r--   0 runner    (1001) docker     (123)   205797 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/iivsearch_results.json
--rw-r--r--   0 runner    (1001) docker     (123)   197228 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/iovsearch_results.json
--rw-r--r--   0 runner    (1001) docker     (123)    12639 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/linearize_results.json
--rw-r--r--   0 runner    (1001) docker     (123)      787 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/metadata.json
--rw-r--r--   0 runner    (1001) docker     (123)   105603 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/modelsearch_results.json
--rw-r--r--   0 runner    (1001) docker     (123)     7841 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/qa_results.json
--rw-r--r--   0 runner    (1001) docker     (123)    57352 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/ruvsearch_results.json
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.938861 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.034861 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/
--rw-r--r--   0 runner    (1001) docker     (123)      787 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/metadata.json
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.034861 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.034861 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/.datasets/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:08.938861 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/.datasets/.hash/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.038861 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/.datasets/.hash/-7907770233072098756/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/.datasets/.hash/-7907770233072098756/input_model.csv
--rw-r--r--   0 runner    (1001) docker     (123)   183701 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/.datasets/input_model.csv
--rw-r--r--   0 runner    (1001) docker     (123)     4639 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/.datasets/input_model.datainfo
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-26 09:41:55.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/.lock
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.038861 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/input_model/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.038861 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/input_model/.pharmpy/
--rw-r--r--   0 runner    (1001) docker     (123)     7143 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/input_model/.pharmpy/results.json
--rw-r--r--   0 runner    (1001) docker     (123)      707 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/input_model/input_model.mod
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.038861 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.038861 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/.pharmpy/
--rw-r--r--   0 runner    (1001) docker     (123)      119 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/.pharmpy/metadata.json
--rw-r--r--   0 runner    (1001) docker     (123)     7120 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/.pharmpy/results.json
--rw-r--r--   0 runner    (1001) docker     (123)     1488 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/modelsearch_run1.ext
--rw-r--r--   0 runner    (1001) docker     (123)    91188 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/modelsearch_run1.lst
--rw-r--r--   0 runner    (1001) docker     (123)      881 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/modelsearch_run1.mod
--rw-r--r--   0 runner    (1001) docker     (123)    12377 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/modelsearch_run1.phi
--rw-r--r--   0 runner    (1001) docker     (123)    70155 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/mytab_mox1
--rw-r--r--   0 runner    (1001) docker     (123)      169 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/nonmem.json
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/stderr
--rw-r--r--   0 runner    (1001) docker     (123)     1796 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/stdout
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.038861 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.038861 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/.pharmpy/
--rw-r--r--   0 runner    (1001) docker     (123)      119 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/.pharmpy/metadata.json
--rw-r--r--   0 runner    (1001) docker     (123)     7112 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/.pharmpy/results.json
--rw-r--r--   0 runner    (1001) docker     (123)     1761 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/modelsearch_run2.ext
--rw-r--r--   0 runner    (1001) docker     (123)    91119 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/modelsearch_run2.lst
--rw-r--r--   0 runner    (1001) docker     (123)      834 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/modelsearch_run2.mod
--rw-r--r--   0 runner    (1001) docker     (123)    17187 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/modelsearch_run2.phi
--rw-r--r--   0 runner    (1001) docker     (123)    70155 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/mytab_mox2
--rw-r--r--   0 runner    (1001) docker     (123)      169 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/nonmem.json
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/stderr
--rw-r--r--   0 runner    (1001) docker     (123)     1796 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/stdout
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.038861 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.038861 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/.pharmpy/
--rw-r--r--   0 runner    (1001) docker     (123)      119 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/.pharmpy/metadata.json
--rw-r--r--   0 runner    (1001) docker     (123)    53630 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/.pharmpy/results.json
--rw-r--r--   0 runner    (1001) docker     (123)     1943 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/modelsearch_run3.ext
--rw-r--r--   0 runner    (1001) docker     (123)    91754 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/modelsearch_run3.lst
--rw-r--r--   0 runner    (1001) docker     (123)      975 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/modelsearch_run3.mod
--rw-r--r--   0 runner    (1001) docker     (123)    17187 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/modelsearch_run3.phi
--rw-r--r--   0 runner    (1001) docker     (123)    70155 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/mytab_mox3
--rw-r--r--   0 runner    (1001) docker     (123)      169 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/nonmem.json
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/stderr
--rw-r--r--   0 runner    (1001) docker     (123)     2012 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/stdout
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.042861 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.042861 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/.pharmpy/
--rw-r--r--   0 runner    (1001) docker     (123)      119 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/.pharmpy/metadata.json
--rw-r--r--   0 runner    (1001) docker     (123)    54979 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/.pharmpy/results.json
--rw-r--r--   0 runner    (1001) docker     (123)     1943 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/modelsearch_run4.ext
--rw-r--r--   0 runner    (1001) docker     (123)    91879 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/modelsearch_run4.lst
--rw-r--r--   0 runner    (1001) docker     (123)      989 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/modelsearch_run4.mod
--rw-r--r--   0 runner    (1001) docker     (123)    17187 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/modelsearch_run4.phi
--rw-r--r--   0 runner    (1001) docker     (123)    70155 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/mytab_mox4
--rw-r--r--   0 runner    (1001) docker     (123)      169 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/nonmem.json
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/stderr
--rw-r--r--   0 runner    (1001) docker     (123)     2012 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/stdout
--rw-r--r--   0 runner    (1001) docker     (123)    47403 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/results.csv
--rw-r--r--   0 runner    (1001) docker     (123)   105597 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/results.json
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.042861 pharmpy-core-0.96.0/tests/tools/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/tools/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2400 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/tools/test_allometry.py
--rw-r--r--   0 runner    (1001) docker     (123)     7559 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/tools/test_amd.py
--rw-r--r--   0 runner    (1001) docker     (123)     1369 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/tools/test_bootstrap.py
--rw-r--r--   0 runner    (1001) docker     (123)     8607 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/tools/test_cdd.py
--rw-r--r--   0 runner    (1001) docker     (123)     3914 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/tools/test_covsearch.py
--rw-r--r--   0 runner    (1001) docker     (123)      500 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/tools/test_crossval.py
--rw-r--r--   0 runner    (1001) docker     (123)     2802 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/tools/test_estmethod.py
--rw-r--r--   0 runner    (1001) docker     (123)      956 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/tools/test_exports.py
--rw-r--r--   0 runner    (1001) docker     (123)    28369 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/tools/test_frem.py
--rw-r--r--   0 runner    (1001) docker     (123)     8107 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/tools/test_iivsearch.py
--rw-r--r--   0 runner    (1001) docker     (123)     3186 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/tools/test_iovsearch.py
--rw-r--r--   0 runner    (1001) docker     (123)     4328 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/tools/test_linearize.py
--rw-r--r--   0 runner    (1001) docker     (123)    11786 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/tools/test_mfl.py
--rw-r--r--   0 runner    (1001) docker     (123)     1096 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/tools/test_ml.py
--rw-r--r--   0 runner    (1001) docker     (123)    10258 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/tools/test_modelsearch.py
--rw-r--r--   0 runner    (1001) docker     (123)    10900 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/tools/test_qa.py
--rw-r--r--   0 runner    (1001) docker     (123)     1799 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/tools/test_rankfuncs.py
--rw-r--r--   0 runner    (1001) docker     (123)    15964 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/tools/test_run.py
--rw-r--r--   0 runner    (1001) docker     (123)     2546 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/tools/test_runtool.py
--rw-r--r--   0 runner    (1001) docker     (123)     5139 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/tools/test_ruvsearch.py
--rw-r--r--   0 runner    (1001) docker     (123)    19845 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/tools/test_scm.py
--rw-r--r--   0 runner    (1001) docker     (123)      247 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/tools/test_simeval.py
--rw-r--r--   0 runner    (1001) docker     (123)      979 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/tools/test_start_model.py
--rw-r--r--   0 runner    (1001) docker     (123)     2962 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/tools/test_summarize_individuals.py
--rw-r--r--   0 runner    (1001) docker     (123)     1535 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/tools/test_wrap.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-26 09:46:09.042861 pharmpy-core-0.96.0/tests/workflows/
--rw-r--r--   0 runner    (1001) docker     (123)     1988 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/workflows/test_call.py
--rw-r--r--   0 runner    (1001) docker     (123)     6586 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/workflows/test_execute.py
--rw-r--r--   0 runner    (1001) docker     (123)      318 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/workflows/test_log.py
--rw-r--r--   0 runner    (1001) docker     (123)     3173 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/workflows/test_model_database.py
--rw-r--r--   0 runner    (1001) docker     (123)      416 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/workflows/test_task.py
--rw-r--r--   0 runner    (1001) docker     (123)      198 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/workflows/test_tool_database.py
--rw-r--r--   0 runner    (1001) docker     (123)     4125 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tests/workflows/test_workflow.py
--rw-r--r--   0 runner    (1001) docker     (123)     3971 2023-05-26 09:39:32.000000 pharmpy-core-0.96.0/tox.ini
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.551107 pharmpy-core-0.97.0/
+-rw-r--r--   0 runner    (1001) docker     (123)      419 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/.bumpversion.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)      227 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/.coveragerc
+-rw-r--r--   0 runner    (1001) docker     (123)      973 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/AUTHORS.rst
+-rw-r--r--   0 runner    (1001) docker     (123)    46403 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/CHANGELOG.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     2852 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/CODE_OF_CONDUCT.rst
+-rw-r--r--   0 runner    (1001) docker     (123)    35196 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     7652 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/LICENSE.LESSER
+-rw-r--r--   0 runner    (1001) docker     (123)      524 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)    48318 2023-06-28 07:02:54.551107 pharmpy-core-0.97.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2933 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/README.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.403094 pharmpy-core-0.97.0/docs/
+-rw-r--r--   0 runner    (1001) docker     (123)    10512 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/NONMEM.rst
+-rw-r--r--   0 runner    (1001) docker     (123)    14367 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/Pharmpy_logo.svg
+-rw-r--r--   0 runner    (1001) docker     (123)    14872 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/Pharmpy_logo_dark.svg
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.403094 pharmpy-core-0.97.0/docs/_ext/
+-rw-r--r--   0 runner    (1001) docker     (123)     7108 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/_ext/conversion.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4723 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/_ext/pharmpy_snippet.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5230 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/allometry.rst
+-rw-r--r--   0 runner    (1001) docker     (123)    24284 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/amd.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      741 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/api.rst
+-rw-r--r--   0 runner    (1001) docker     (123)       30 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/api_model.rst
+-rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/api_modeling.rst
+-rw-r--r--   0 runner    (1001) docker     (123)       30 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/api_tools.rst
+-rw-r--r--   0 runner    (1001) docker     (123)       34 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/api_workflows.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     4317 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/bootstrap.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     2807 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/cdd.rst
+-rw-r--r--   0 runner    (1001) docker     (123)       76 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/changelog.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      413 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/citation.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      802 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/cli.rst
+-rw-r--r--   0 runner    (1001) docker     (123)       58 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/code_of_conduct.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     2155 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/conf.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3921 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/configuration.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     6059 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/contribute.rst
+-rw-r--r--   0 runner    (1001) docker     (123)       47 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/contributors.rst
+-rw-r--r--   0 runner    (1001) docker     (123)    10790 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/covsearch.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      644 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/crossval.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1290 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/custom.css
+-rw-r--r--   0 runner    (1001) docker     (123)     5302 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/data.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     2793 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/design.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      177 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/developers.rst
+-rw-r--r--   0 runner    (1001) docker     (123)    10499 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/estmethod.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     8137 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/frem.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1624 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/getting_started.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      854 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/help_functions.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12790 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/iivsearch.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.403094 pharmpy-core-0.97.0/docs/images/
+-rw-r--r--   0 runner    (1001) docker     (123)     5937 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/images/Pharmpy_symbol.svg
+-rw-r--r--   0 runner    (1001) docker     (123)   179150 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/images/tools.png
+-rw-r--r--   0 runner    (1001) docker     (123)     1509 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/index.rst
+-rw-r--r--   0 runner    (1001) docker     (123)    11603 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/iovsearch.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     2827 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/license.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      967 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/linearize.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     8102 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/model.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     3653 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/modelfit.rst
+-rw-r--r--   0 runner    (1001) docker     (123)    16627 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/modeling.rst
+-rw-r--r--   0 runner    (1001) docker     (123)    16031 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/modelsearch.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     4434 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/nonmem_plugin.rst
+-rw-r--r--   0 runner    (1001) docker     (123)    12416 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/pharmr_logo.svg
+-rw-r--r--   0 runner    (1001) docker     (123)     1072 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/plots.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1248 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/plugins.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     5585 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/projects.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      452 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/psn_resmod.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      336 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/psn_tools.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     2758 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/qa.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      157 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/requirements.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     7786 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/ruvsearch.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     2697 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/scm.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1416 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/simeval.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      109 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/spelling_wordlist.txt
+-rw-r--r--   0 runner    (1001) docker     (123)    15280 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/tools.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      388 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/user_guide.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     4212 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/docs/using_r.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      358 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)     2406 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/requirements.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      813 2023-06-28 07:02:54.551107 pharmpy-core-0.97.0/setup.cfg
+-rwxr-xr-x   0 runner    (1001) docker     (123)     3180 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.403094 pharmpy-core-0.97.0/src/
+-rw-r--r--   0 runner    (1001) docker     (123)      257 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/conftest.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.403094 pharmpy-core-0.97.0/src/pharmpy/
+-rw-r--r--   0 runner    (1001) docker     (123)      219 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      125 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    80641 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/cli.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3593 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/config.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.403094 pharmpy-core-0.97.0/src/pharmpy/deps/
+-rw-r--r--   0 runner    (1001) docker     (123)      579 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/deps/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      518 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/deps/altair.py
+-rw-r--r--   0 runner    (1001) docker     (123)      213 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/deps/rich.py
+-rw-r--r--   0 runner    (1001) docker     (123)      165 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/deps/scipy.py
+-rw-r--r--   0 runner    (1001) docker     (123)      261 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/deps/sympy_printing.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.403094 pharmpy-core-0.97.0/src/pharmpy/internals/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      413 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/code_generator.py
+-rw-r--r--   0 runner    (1001) docker     (123)      909 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/df.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.403094 pharmpy-core-0.97.0/src/pharmpy/internals/ds/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/ds/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1922 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/ds/ordered_set.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.407094 pharmpy-core-0.97.0/src/pharmpy/internals/expr/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/expr/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      352 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/expr/assumptions.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1397 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/expr/eval.py
+-rw-r--r--   0 runner    (1001) docker     (123)      955 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/expr/funcs.py
+-rw-r--r--   0 runner    (1001) docker     (123)      632 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/expr/leaves.py
+-rw-r--r--   0 runner    (1001) docker     (123)      697 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/expr/ode.py
+-rw-r--r--   0 runner    (1001) docker     (123)      264 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/expr/parse.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2959 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/expr/subs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2273 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/expr/tree.py
+-rw-r--r--   0 runner    (1001) docker     (123)      585 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/expr/units.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.407094 pharmpy-core-0.97.0/src/pharmpy/internals/fn/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/fn/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2335 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/fn/signature.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5576 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/fn/type.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.407094 pharmpy-core-0.97.0/src/pharmpy/internals/fs/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/fs/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      496 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/fs/cwd.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19768 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/fs/lock.py
+-rw-r--r--   0 runner    (1001) docker     (123)      770 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/fs/path.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3611 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/fs/tmp.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.371091 pharmpy-core-0.97.0/src/pharmpy/internals/graph/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.407094 pharmpy-core-0.97.0/src/pharmpy/internals/graph/directed/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/graph/directed/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      758 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/graph/directed/connected_components.py
+-rw-r--r--   0 runner    (1001) docker     (123)      327 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/graph/directed/inverse.py
+-rw-r--r--   0 runner    (1001) docker     (123)      425 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/graph/directed/reachability.py
+-rw-r--r--   0 runner    (1001) docker     (123)      923 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/immutable.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6508 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/math.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.407094 pharmpy-core-0.97.0/src/pharmpy/internals/module/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/module/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1380 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/module/lazy.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.407094 pharmpy-core-0.97.0/src/pharmpy/internals/parse/
+-rw-r--r--   0 runner    (1001) docker     (123)      297 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/parse/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15783 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/parse/generic.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3050 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/parse/ignored.py
+-rw-r--r--   0 runner    (1001) docker     (123)      964 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/parse/missing.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2519 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/parse/prettyprint.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1044 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/parse/tree.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4340 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/parse/treeprint.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.407094 pharmpy-core-0.97.0/src/pharmpy/internals/sequence/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/sequence/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2114 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/sequence/lcs.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.407094 pharmpy-core-0.97.0/src/pharmpy/internals/set/
+-rw-r--r--   0 runner    (1001) docker     (123)     1498 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/set/partitions.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1413 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/set/subsets.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6365 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/internals/unicode.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.411095 pharmpy-core-0.97.0/src/pharmpy/model/
+-rw-r--r--   0 runner    (1001) docker     (123)     1353 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      922 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/data.py
+-rw-r--r--   0 runner    (1001) docker     (123)    30935 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/datainfo.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.411095 pharmpy-core-0.97.0/src/pharmpy/model/distributions/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/distributions/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1053 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/distributions/numeric.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19145 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/distributions/symbolic.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14857 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/estimation.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.411095 pharmpy-core-0.97.0/src/pharmpy/model/external/
+-rw-r--r--   0 runner    (1001) docker     (123)       60 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.411095 pharmpy-core-0.97.0/src/pharmpy/model/external/fcon/
+-rw-r--r--   0 runner    (1001) docker     (123)      104 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/fcon/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2117 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/fcon/model.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.411095 pharmpy-core-0.97.0/src/pharmpy/model/external/generic/
+-rw-r--r--   0 runner    (1001) docker     (123)      164 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/generic/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      944 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/generic/generic.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.411095 pharmpy-core-0.97.0/src/pharmpy/model/external/nlmixr/
+-rw-r--r--   0 runner    (1001) docker     (123)       78 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nlmixr/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10767 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nlmixr/error_model.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5571 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nlmixr/ini.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8908 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nlmixr/model.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16669 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nlmixr/model_block.py
+-rw-r--r--   0 runner    (1001) docker     (123)      408 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nlmixr/name_mangle.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11271 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nlmixr/sanity_checks.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.411095 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/
+-rw-r--r--   0 runner    (1001) docker     (123)      155 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22606 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/advan.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11551 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/dataset.py
+-rw-r--r--   0 runner    (1001) docker     (123)      297 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/detect.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14131 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/model.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6712 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/nmtran_parser.py
+-rw-r--r--   0 runner    (1001) docker     (123)    29064 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/parsing.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.415095 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/
+-rw-r--r--   0 runner    (1001) docker     (123)       45 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      866 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/abbreviated_record.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25255 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/code_record.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5455 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/data_record.py
+-rw-r--r--   0 runner    (1001) docker     (123)      423 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/estimation_record.py
+-rw-r--r--   0 runner    (1001) docker     (123)      361 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/etas_record.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3476 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/factory.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.415095 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/grammars/
+-rw-r--r--   0 runner    (1001) docker     (123)     2904 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/grammars/abbreviated_record.lark
+-rw-r--r--   0 runner    (1001) docker     (123)     6372 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/grammars/code_record.lark
+-rw-r--r--   0 runner    (1001) docker     (123)     2232 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/grammars/data_record.lark
+-rw-r--r--   0 runner    (1001) docker     (123)      360 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/grammars/definitions.lark
+-rw-r--r--   0 runner    (1001) docker     (123)     3216 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/grammars/omega_record.lark
+-rw-r--r--   0 runner    (1001) docker     (123)      318 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/grammars/option_record.lark
+-rw-r--r--   0 runner    (1001) docker     (123)      146 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/grammars/problem_record.lark
+-rw-r--r--   0 runner    (1001) docker     (123)     1397 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/grammars/simulation_record.lark
+-rw-r--r--   0 runner    (1001) docker     (123)     1921 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/grammars/theta_record.lark
+-rw-r--r--   0 runner    (1001) docker     (123)     1692 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/model_record.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17000 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/omega_record.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20087 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/option_record.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2841 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/parsers.py
+-rw-r--r--   0 runner    (1001) docker     (123)      840 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/problem_record.py
+-rw-r--r--   0 runner    (1001) docker     (123)      366 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/raw_record.py
+-rw-r--r--   0 runner    (1001) docker     (123)      565 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/record.py
+-rw-r--r--   0 runner    (1001) docker     (123)      426 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/simulation_record.py
+-rw-r--r--   0 runner    (1001) docker     (123)      952 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/sizes_record.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1002 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/subroutine_record.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2803 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/table_record.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5335 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/theta_record.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11765 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/table.py
+-rw-r--r--   0 runner    (1001) docker     (123)    65273 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/update.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.415095 pharmpy-core-0.97.0/src/pharmpy/model/external/rxode/
+-rw-r--r--   0 runner    (1001) docker     (123)       78 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/rxode/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7165 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/rxode/model.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1186 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/external/utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23605 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/model.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13285 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/parameters.py
+-rw-r--r--   0 runner    (1001) docker     (123)    34378 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/random_variables.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8281 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/results.py
+-rw-r--r--   0 runner    (1001) docker     (123)    73469 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/model/statements.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.419095 pharmpy-core-0.97.0/src/pharmpy/modeling/
+-rw-r--r--   0 runner    (1001) docker     (123)    10651 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4589 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/allometry.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6404 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/basic_models.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6796 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/blq.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17482 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/common.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1127 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/compartments.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21363 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/covariate_effect.py
+-rw-r--r--   0 runner    (1001) docker     (123)    49871 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/data.py
+-rw-r--r--   0 runner    (1001) docker     (123)    37095 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/error.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5087 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/estimation.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9043 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/estimation_steps.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15348 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/evaluation.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.423096 pharmpy-core-0.97.0/src/pharmpy/modeling/example_models/
+-rw-r--r--   0 runner    (1001) docker     (123)    50310 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/example_models/moxo.csv
+-rw-r--r--   0 runner    (1001) docker     (123)     1392 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/example_models/moxo.mod
+-rw-r--r--   0 runner    (1001) docker     (123)      989 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/example_models/pheno.cov
+-rw-r--r--   0 runner    (1001) docker     (123)      680 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/example_models/pheno.datainfo
+-rw-r--r--   0 runner    (1001) docker     (123)    38720 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/example_models/pheno.dta
+-rw-r--r--   0 runner    (1001) docker     (123)     2851 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/example_models/pheno.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    21259 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/example_models/pheno.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      662 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/example_models/pheno.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/example_models/pheno.phi
+-rw-r--r--   0 runner    (1001) docker     (123)    90151 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/example_models/pheno.tab
+-rw-r--r--   0 runner    (1001) docker     (123)   298562 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/example_models/pheno_linear.dta
+-rw-r--r--   0 runner    (1001) docker     (123)     2384 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/example_models/pheno_linear.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    14564 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/example_models/pheno_linear.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      605 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/example_models/pheno_linear.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/example_models/pheno_linear.phi
+-rw-r--r--   0 runner    (1001) docker     (123)    45809 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/expressions.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2746 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/help_functions.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11217 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/iterators.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1572 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/lrt.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19639 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/math.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2671 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/metabolite.py
+-rw-r--r--   0 runner    (1001) docker     (123)    70962 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/odes.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12116 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/parameter_sampling.py
+-rw-r--r--   0 runner    (1001) docker     (123)    34944 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/parameter_variability.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18858 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/parameters.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5110 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/pd.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4939 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/plots.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25760 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/results.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8253 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/tmdd.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4920 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/units.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1628 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/modeling/write_csv.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.423096 pharmpy-core-0.97.0/src/pharmpy/reporting/
+-rw-r--r--   0 runner    (1001) docker     (123)    11165 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/reporting/altairplot.py
+-rw-r--r--   0 runner    (1001) docker     (123)      361 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/reporting/conf.py
+-rw-r--r--   0 runner    (1001) docker     (123)      643 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/reporting/custom.css
+-rwxr-xr-x   0 runner    (1001) docker     (123)     5634 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/reporting/reporting.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8772 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/results.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.423096 pharmpy-core-0.97.0/src/pharmpy/tools/
+-rw-r--r--   0 runner    (1001) docker     (123)     3816 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.423096 pharmpy-core-0.97.0/src/pharmpy/tools/allometry/
+-rw-r--r--   0 runner    (1001) docker     (123)       99 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/allometry/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6487 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/allometry/tool.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.423096 pharmpy-core-0.97.0/src/pharmpy/tools/amd/
+-rw-r--r--   0 runner    (1001) docker     (123)       69 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/amd/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4902 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/amd/funcs.py
+-rw-r--r--   0 runner    (1001) docker     (123)      458 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/amd/results.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16449 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/amd/run.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.427096 pharmpy-core-0.97.0/src/pharmpy/tools/bootstrap/
+-rw-r--r--   0 runner    (1001) docker     (123)      157 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/bootstrap/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      540 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/bootstrap/report.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     8798 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/bootstrap/results.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1818 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/bootstrap/tool.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.427096 pharmpy-core-0.97.0/src/pharmpy/tools/cdd/
+-rw-r--r--   0 runner    (1001) docker     (123)       98 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/cdd/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8392 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/cdd/results.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4863 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/common.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.427096 pharmpy-core-0.97.0/src/pharmpy/tools/covsearch/
+-rw-r--r--   0 runner    (1001) docker     (123)      192 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/covsearch/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      386 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/covsearch/results.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19965 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/covsearch/tool.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.427096 pharmpy-core-0.97.0/src/pharmpy/tools/crossval/
+-rw-r--r--   0 runner    (1001) docker     (123)      147 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/crossval/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1449 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/crossval/results.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.427096 pharmpy-core-0.97.0/src/pharmpy/tools/estmethod/
+-rw-r--r--   0 runner    (1001) docker     (123)      171 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/estmethod/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5527 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/estmethod/algorithms.py
+-rw-r--r--   0 runner    (1001) docker     (123)      583 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/estmethod/report.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     7029 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/estmethod/tool.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.427096 pharmpy-core-0.97.0/src/pharmpy/tools/evaldesign/
+-rw-r--r--   0 runner    (1001) docker     (123)      140 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/evaldesign/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      722 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/evaldesign/tool.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.427096 pharmpy-core-0.97.0/src/pharmpy/tools/external/
+-rw-r--r--   0 runner    (1001) docker     (123)       82 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/external/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.427096 pharmpy-core-0.97.0/src/pharmpy/tools/external/nlmixr/
+-rw-r--r--   0 runner    (1001) docker     (123)      783 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/external/nlmixr/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20571 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/external/nlmixr/run.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.427096 pharmpy-core-0.97.0/src/pharmpy/tools/external/nonmem/
+-rw-r--r--   0 runner    (1001) docker     (123)      782 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/external/nonmem/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      635 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/external/nonmem/config.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21360 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/external/nonmem/results.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18254 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/external/nonmem/results_file.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     7225 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/external/nonmem/run.py
+-rw-r--r--   0 runner    (1001) docker     (123)      332 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/external/results.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.427096 pharmpy-core-0.97.0/src/pharmpy/tools/external/rxode/
+-rw-r--r--   0 runner    (1001) docker     (123)      779 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/external/rxode/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6598 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/external/rxode/run.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.427096 pharmpy-core-0.97.0/src/pharmpy/tools/frem/
+-rw-r--r--   0 runner    (1001) docker     (123)      102 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/frem/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1897 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/frem/models.py
+-rw-r--r--   0 runner    (1001) docker     (123)      505 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/frem/report.rst
+-rw-r--r--   0 runner    (1001) docker     (123)    39054 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/frem/results.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2913 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/frem/tool.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.431097 pharmpy-core-0.97.0/src/pharmpy/tools/funcs/
+-rw-r--r--   0 runner    (1001) docker     (123)      372 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/funcs/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9605 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/funcs/ml.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.431097 pharmpy-core-0.97.0/src/pharmpy/tools/funcs/ml_models/
+-rw-r--r--   0 runner    (1001) docker     (123)    91484 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/funcs/ml_models/infinds.tflite
+-rw-r--r--   0 runner    (1001) docker     (123)    93596 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/funcs/ml_models/outliers.tflite
+-rw-r--r--   0 runner    (1001) docker     (123)     9949 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/funcs/summarize_individuals.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.431097 pharmpy-core-0.97.0/src/pharmpy/tools/iivsearch/
+-rw-r--r--   0 runner    (1001) docker     (123)      172 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/iivsearch/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5109 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/iivsearch/algorithms.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9843 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/iivsearch/tool.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.431097 pharmpy-core-0.97.0/src/pharmpy/tools/iovsearch/
+-rw-r--r--   0 runner    (1001) docker     (123)      171 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/iovsearch/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12449 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/iovsearch/tool.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.431097 pharmpy-core-0.97.0/src/pharmpy/tools/linearize/
+-rw-r--r--   0 runner    (1001) docker     (123)      104 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/linearize/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2012 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/linearize/results.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2357 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/linearize/tool.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.431097 pharmpy-core-0.97.0/src/pharmpy/tools/mfl/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/mfl/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.431097 pharmpy-core-0.97.0/src/pharmpy/tools/mfl/feature/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/mfl/feature/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1211 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/mfl/feature/absorption.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5067 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/mfl/feature/covariate.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1405 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/mfl/feature/elimination.py
+-rw-r--r--   0 runner    (1001) docker     (123)      209 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/mfl/feature/feature.py
+-rw-r--r--   0 runner    (1001) docker     (123)      430 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/mfl/feature/lagtime.py
+-rw-r--r--   0 runner    (1001) docker     (123)      577 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/mfl/feature/peripherals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1269 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/mfl/feature/transits.py
+-rw-r--r--   0 runner    (1001) docker     (123)      636 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/mfl/filter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2619 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/mfl/grammar.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2166 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/mfl/helpers.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1275 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/mfl/interpreter.py
+-rw-r--r--   0 runner    (1001) docker     (123)      603 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/mfl/parse.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.431097 pharmpy-core-0.97.0/src/pharmpy/tools/mfl/statement/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/mfl/statement/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      596 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/mfl/statement/definition.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.435097 pharmpy-core-0.97.0/src/pharmpy/tools/mfl/statement/feature/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/mfl/statement/feature/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      751 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/mfl/statement/feature/absorption.py
+-rw-r--r--   0 runner    (1001) docker     (123)      780 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/mfl/statement/feature/count_interpreter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2010 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/mfl/statement/feature/covariate.py
+-rw-r--r--   0 runner    (1001) docker     (123)      762 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/mfl/statement/feature/elimination.py
+-rw-r--r--   0 runner    (1001) docker     (123)      253 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/mfl/statement/feature/feature.py
+-rw-r--r--   0 runner    (1001) docker     (123)      342 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/mfl/statement/feature/lagtime.py
+-rw-r--r--   0 runner    (1001) docker     (123)      444 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/mfl/statement/feature/peripherals.py
+-rw-r--r--   0 runner    (1001) docker     (123)      269 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/mfl/statement/feature/symbols.py
+-rw-r--r--   0 runner    (1001) docker     (123)      850 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/mfl/statement/feature/transits.py
+-rw-r--r--   0 runner    (1001) docker     (123)      134 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/mfl/statement/statement.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2105 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/mfl/stringify.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.435097 pharmpy-core-0.97.0/src/pharmpy/tools/modelfit/
+-rw-r--r--   0 runner    (1001) docker     (123)      671 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/modelfit/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4086 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/modelfit/tool.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.435097 pharmpy-core-0.97.0/src/pharmpy/tools/modelsearch/
+-rw-r--r--   0 runner    (1001) docker     (123)      177 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/modelsearch/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11394 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/modelsearch/algorithms.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5407 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/modelsearch/tool.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6174 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/psn_helpers.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.435097 pharmpy-core-0.97.0/src/pharmpy/tools/qa/
+-rw-r--r--   0 runner    (1001) docker     (123)       83 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/qa/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19639 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/qa/results.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2372 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/rankfuncs.py
+-rw-r--r--   0 runner    (1001) docker     (123)      848 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/reporting.py
+-rw-r--r--   0 runner    (1001) docker     (123)    33617 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/run.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.435097 pharmpy-core-0.97.0/src/pharmpy/tools/ruvsearch/
+-rw-r--r--   0 runner    (1001) docker     (123)      191 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/ruvsearch/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4507 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/ruvsearch/results.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17509 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/ruvsearch/tool.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.435097 pharmpy-core-0.97.0/src/pharmpy/tools/scm/
+-rw-r--r--   0 runner    (1001) docker     (123)      164 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/scm/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2422 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/scm/psn_wrapper.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27707 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/scm/results.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.435097 pharmpy-core-0.97.0/src/pharmpy/tools/simeval/
+-rw-r--r--   0 runner    (1001) docker     (123)       98 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/simeval/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2870 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/simeval/results.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.435097 pharmpy-core-0.97.0/src/pharmpy/tools/simfit/
+-rw-r--r--   0 runner    (1001) docker     (123)      110 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/simfit/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      687 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/simfit/results.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.435097 pharmpy-core-0.97.0/src/pharmpy/tools/structsearch/
+-rw-r--r--   0 runner    (1001) docker     (123)      181 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/structsearch/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4746 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/structsearch/tmdd.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3389 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/structsearch/tool.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2152 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/tools/wrap.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5676 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/visualization.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.439097 pharmpy-core-0.97.0/src/pharmpy/workflows/
+-rw-r--r--   0 runner    (1001) docker     (123)     2459 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/workflows/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      830 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/workflows/args.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1141 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/workflows/call.py
+-rw-r--r--   0 runner    (1001) docker     (123)      449 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/workflows/context.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.439097 pharmpy-core-0.97.0/src/pharmpy/workflows/dispatchers/
+-rw-r--r--   0 runner    (1001) docker     (123)      325 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/workflows/dispatchers/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4460 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/workflows/dispatchers/local_dask.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2711 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/workflows/execute.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2805 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/workflows/log.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.439097 pharmpy-core-0.97.0/src/pharmpy/workflows/model_database/
+-rw-r--r--   0 runner    (1001) docker     (123)      289 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/workflows/model_database/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9287 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/workflows/model_database/baseclass.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12310 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/workflows/model_database/local_directory.py
+-rw-r--r--   0 runner    (1001) docker     (123)      807 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/workflows/model_database/null_database.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1390 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/workflows/optimize.py
+-rw-r--r--   0 runner    (1001) docker     (123)      505 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/workflows/task.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.439097 pharmpy-core-0.97.0/src/pharmpy/workflows/tool_database/
+-rw-r--r--   0 runner    (1001) docker     (123)      229 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/workflows/tool_database/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1540 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/workflows/tool_database/baseclass.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2922 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/workflows/tool_database/local_directory.py
+-rw-r--r--   0 runner    (1001) docker     (123)      593 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/workflows/tool_database/null_database.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5880 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/src/pharmpy/workflows/workflow.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.439097 pharmpy-core-0.97.0/src/pharmpy_core.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    48318 2023-06-28 07:02:54.000000 pharmpy-core-0.97.0/src/pharmpy_core.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    47419 2023-06-28 07:02:54.000000 pharmpy-core-0.97.0/src/pharmpy_core.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 07:02:54.000000 pharmpy-core-0.97.0/src/pharmpy_core.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      114 2023-06-28 07:02:54.000000 pharmpy-core-0.97.0/src/pharmpy_core.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 06:56:11.000000 pharmpy-core-0.97.0/src/pharmpy_core.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)      238 2023-06-28 07:02:54.000000 pharmpy-core-0.97.0/src/pharmpy_core.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       17 2023-06-28 07:02:54.000000 pharmpy-core-0.97.0/src/pharmpy_core.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.439097 pharmpy-core-0.97.0/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.439097 pharmpy-core-0.97.0/tests/cli/
+-rw-r--r--   0 runner    (1001) docker     (123)     8805 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/cli/test_cli.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.439097 pharmpy-core-0.97.0/tests/config/
+-rw-r--r--   0 runner    (1001) docker     (123)      403 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/config/test_config.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2970 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/conftest.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.439097 pharmpy-core-0.97.0/tests/deps/
+-rw-r--r--   0 runner    (1001) docker     (123)      257 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/deps/test_deps.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.439097 pharmpy-core-0.97.0/tests/external/
+-rw-r--r--   0 runner    (1001) docker     (123)      505 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/external/test_external.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2338 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/external/test_nlmixr.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1721 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/external/test_rxode.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.451098 pharmpy-core-0.97.0/tests/integration/
+-rw-r--r--   0 runner    (1001) docker     (123)     1152 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/integration/conftest.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1522 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/integration/test_allometry.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1557 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/integration/test_amd.py
+-rw-r--r--   0 runner    (1001) docker     (123)      800 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/integration/test_bootstrap.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1096 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/integration/test_common.py
+-rw-r--r--   0 runner    (1001) docker     (123)      640 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/integration/test_covsearch.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1059 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/integration/test_estmethod.py
+-rw-r--r--   0 runner    (1001) docker     (123)      662 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/integration/test_evaldesign.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4025 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/integration/test_fit.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7463 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/integration/test_iivsearch.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1440 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/integration/test_iovsearch.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7834 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/integration/test_modelsearch.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8845 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/integration/test_resume.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2743 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/integration/test_ruvsearch.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.451098 pharmpy-core-0.97.0/tests/internals/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.451098 pharmpy-core-0.97.0/tests/internals/fs/
+-rw-r--r--   0 runner    (1001) docker     (123)    15348 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/internals/fs/test_lock.py
+-rw-r--r--   0 runner    (1001) docker     (123)      223 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/internals/fs/test_tmp.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.451098 pharmpy-core-0.97.0/tests/internals/module/
+-rw-r--r--   0 runner    (1001) docker     (123)      513 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/internals/module/test_lazy.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5505 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/internals/test_math.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3863 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/internals/test_parse.py
+-rw-r--r--   0 runner    (1001) docker     (123)      485 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/lib.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.451098 pharmpy-core-0.97.0/tests/model/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/model/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10111 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/model/test_datainfo.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5537 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/model/test_estimation.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3043 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/model/test_model.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8855 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/model/test_parameter.py
+-rw-r--r--   0 runner    (1001) docker     (123)    29709 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/model/test_random_variables.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15860 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/model/test_statements.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.459099 pharmpy-core-0.97.0/tests/modeling/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/modeling/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4437 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/modeling/test_allometry.py
+-rw-r--r--   0 runner    (1001) docker     (123)      274 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/modeling/test_basic_models.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6655 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/modeling/test_blq.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4448 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/modeling/test_common.py
+-rw-r--r--   0 runner    (1001) docker     (123)      246 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/modeling/test_compartments.py
+-rw-r--r--   0 runner    (1001) docker     (123)    34423 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/modeling/test_covariate_effect.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10292 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/modeling/test_data_funcs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27901 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/modeling/test_error.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4447 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/modeling/test_estimation_steps.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4191 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/modeling/test_evaluate.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20673 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/modeling/test_expressions.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1301 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/modeling/test_help_functions.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3651 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/modeling/test_iterators.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4607 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/modeling/test_lrt.py
+-rw-r--r--   0 runner    (1001) docker     (123)      522 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/modeling/test_metabolite.py
+-rw-r--r--   0 runner    (1001) docker     (123)    66667 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/modeling/test_odes.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3142 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/modeling/test_parameter_sampling.py
+-rw-r--r--   0 runner    (1001) docker     (123)    54748 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/modeling/test_parameter_variability.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7614 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/modeling/test_parameters.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4824 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/modeling/test_pd.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1154 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/modeling/test_plots.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7765 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/modeling/test_results.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1587 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/modeling/test_tmdd.py
+-rw-r--r--   0 runner    (1001) docker     (123)      366 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/modeling/test_units.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.463099 pharmpy-core-0.97.0/tests/nonmem/
+-rw-r--r--   0 runner    (1001) docker     (123)      495 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/nonmem/conftest.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.467100 pharmpy-core-0.97.0/tests/nonmem/output/
+-rw-r--r--   0 runner    (1001) docker     (123)    13614 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/nonmem/output/test_nonmem_results_file.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.471100 pharmpy-core-0.97.0/tests/nonmem/records/
+-rw-r--r--   0 runner    (1001) docker     (123)      295 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/nonmem/records/conftest.py
+-rw-r--r--   0 runner    (1001) docker     (123)      834 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/nonmem/records/test_abbreviated.py
+-rw-r--r--   0 runner    (1001) docker     (123)    28308 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/nonmem/records/test_code.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6044 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/nonmem/records/test_data.py
+-rw-r--r--   0 runner    (1001) docker     (123)      587 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/nonmem/records/test_estimation_record.py
+-rw-r--r--   0 runner    (1001) docker     (123)      155 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/nonmem/records/test_etas.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1525 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/nonmem/records/test_factory.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2372 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/nonmem/records/test_model_record.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10795 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/nonmem/records/test_omega.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7717 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/nonmem/records/test_option_record.py
+-rw-r--r--   0 runner    (1001) docker     (123)      974 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/nonmem/records/test_problem.py
+-rw-r--r--   0 runner    (1001) docker     (123)      339 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/nonmem/records/test_simulation.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1080 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/nonmem/records/test_sizes.py
+-rw-r--r--   0 runner    (1001) docker     (123)      490 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/nonmem/records/test_subroutines.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4609 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/nonmem/records/test_theta.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8486 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/nonmem/test_advan.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2673 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/nonmem/test_des.py
+-rw-r--r--   0 runner    (1001) docker     (123)      361 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/nonmem/test_fcon.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2045 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/nonmem/test_input.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8868 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/nonmem/test_modelfit_results.py
+-rw-r--r--   0 runner    (1001) docker     (123)    35449 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/nonmem/test_nonmem_model.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3822 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/nonmem/test_nonmem_table.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1734 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/nonmem/test_parser.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5595 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/nonmem/test_read.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.471100 pharmpy-core-0.97.0/tests/testdata/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.471100 pharmpy-core-0.97.0/tests/testdata/frem/
+-rw-r--r--   0 runner    (1001) docker     (123)    52275 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/frem/results.json
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.475100 pharmpy-core-0.97.0/tests/testdata/nonmem/
+-rw-r--r--   0 runner    (1001) docker     (123)     4053 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/DDMODEL00000130
+-rw-r--r--   0 runner    (1001) docker     (123)    59142 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/Simulated_CMS_colistin_PK_data.csv
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.475100 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/
+-rw-r--r--   0 runner    (1001) docker     (123)      989 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real.cov
+-rw-r--r--   0 runner    (1001) docker     (123)     2851 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    21259 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      668 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real.phi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.475100 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.479101 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/
+-rw-r--r--   0 runner    (1001) docker     (123)      989 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_1.cov
+-rw-r--r--   0 runner    (1001) docker     (123)     2851 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_1.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    22061 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_1.lst
+-rw-r--r--   0 runner    (1001) docker     (123)     1009 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_1.mod
+-rw-r--r--   0 runner    (1001) docker     (123)      989 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_10.cov
+-rw-r--r--   0 runner    (1001) docker     (123)     2724 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_10.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    21670 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_10.lst
+-rw-r--r--   0 runner    (1001) docker     (123)     1005 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_10.mod
+-rw-r--r--   0 runner    (1001) docker     (123)      989 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_2.cov
+-rw-r--r--   0 runner    (1001) docker     (123)     2724 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_2.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    21677 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_2.lst
+-rw-r--r--   0 runner    (1001) docker     (123)     1012 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_2.mod
+-rw-r--r--   0 runner    (1001) docker     (123)      989 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_3.cov
+-rw-r--r--   0 runner    (1001) docker     (123)     2851 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_3.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    22067 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_3.lst
+-rw-r--r--   0 runner    (1001) docker     (123)     1015 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_3.mod
+-rw-r--r--   0 runner    (1001) docker     (123)      989 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_4.cov
+-rw-r--r--   0 runner    (1001) docker     (123)     2724 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_4.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    21680 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_4.lst
+-rw-r--r--   0 runner    (1001) docker     (123)     1015 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_4.mod
+-rw-r--r--   0 runner    (1001) docker     (123)      989 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_5.cov
+-rw-r--r--   0 runner    (1001) docker     (123)     2724 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_5.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    21680 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_5.lst
+-rw-r--r--   0 runner    (1001) docker     (123)     1015 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_5.mod
+-rw-r--r--   0 runner    (1001) docker     (123)      989 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_6.cov
+-rw-r--r--   0 runner    (1001) docker     (123)     2724 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_6.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    21680 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_6.lst
+-rw-r--r--   0 runner    (1001) docker     (123)     1015 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_6.mod
+-rw-r--r--   0 runner    (1001) docker     (123)      989 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_7.cov
+-rw-r--r--   0 runner    (1001) docker     (123)     2724 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_7.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    21680 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_7.lst
+-rw-r--r--   0 runner    (1001) docker     (123)     1015 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_7.mod
+-rw-r--r--   0 runner    (1001) docker     (123)      989 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_8.cov
+-rw-r--r--   0 runner    (1001) docker     (123)     2978 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_8.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    22454 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_8.lst
+-rw-r--r--   0 runner    (1001) docker     (123)     1015 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_8.mod
+-rw-r--r--   0 runner    (1001) docker     (123)      989 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_9.cov
+-rw-r--r--   0 runner    (1001) docker     (123)     2851 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_9.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    22067 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_9.lst
+-rw-r--r--   0 runner    (1001) docker     (123)     1015 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_9.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     1020 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_1.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     1016 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_10.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     1023 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_2.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     1026 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_3.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     1026 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_4.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     1026 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_5.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     1026 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_6.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     1026 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_7.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     1026 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_8.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     1026 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_9.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     1730 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/meta.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)      168 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/skipped_individuals1.csv
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.483101 pharmpy-core-0.97.0/tests/testdata/nonmem/errors/
+-rw-r--r--   0 runner    (1001) docker     (123)     1210 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/errors/control_stream_error.lst
+-rw-r--r--   0 runner    (1001) docker     (123)    10369 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/errors/est_step_warning.lst
+-rw-r--r--   0 runner    (1001) docker     (123)     9105 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/errors/estimate_near_boundary_warning.lst
+-rw-r--r--   0 runner    (1001) docker     (123)     1014 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/errors/failed_run.ext
+-rw-r--r--   0 runner    (1001) docker     (123)      422 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/errors/failed_run.mod
+-rw-r--r--   0 runner    (1001) docker     (123)    23702 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/errors/no_header_error.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    19648 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/errors/no_header_error.lst
+-rw-r--r--   0 runner    (1001) docker     (123)    13342 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/errors/rounding_error.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      819 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/errors/run_interrupted.ext
+-rw-r--r--   0 runner    (1001) docker     (123)      345 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/errors/run_interrupted.mod
+-rw-r--r--   0 runner    (1001) docker     (123)    10316 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/errors/zero_gradient_error.lst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.483101 pharmpy-core-0.97.0/tests/testdata/nonmem/fcon/
+-rw-r--r--   0 runner    (1001) docker     (123)     6241 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/fcon/FCON
+-rw-r--r--   0 runner    (1001) docker     (123)    39432 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/fcon/FDATA
+-rw-r--r--   0 runner    (1001) docker     (123)       43 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/file.csv
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.387093 pharmpy-core-0.97.0/tests/testdata/nonmem/frem/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.483101 pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno/
+-rw-r--r--   0 runner    (1001) docker     (123)    22896 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno/frem_dataset.dta
+-rw-r--r--   0 runner    (1001) docker     (123)     1277 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno/model_3.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    11250 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno/model_3.lst
+-rw-r--r--   0 runner    (1001) docker     (123)     1623 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno/model_3.mod
+-rw-r--r--   0 runner    (1001) docker     (123)    14006 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno/model_3.phi
+-rw-r--r--   0 runner    (1001) docker     (123)    14006 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno/model_3_input.phi
+-rw-r--r--   0 runner    (1001) docker     (123)     4861 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno/model_4.cov
+-rw-r--r--   0 runner    (1001) docker     (123)     2884 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno/model_4.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    26246 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno/model_4.lst
+-rw-r--r--   0 runner    (1001) docker     (123)     1553 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno/model_4.mod
+-rw-r--r--   0 runner    (1001) docker     (123)    13993 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno/model_4.phi
+-rw-r--r--   0 runner    (1001) docker     (123)    14006 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno/model_4_input.phi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.483101 pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno_cat/
+-rw-r--r--   0 runner    (1001) docker     (123)    24625 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno_cat/frem_dataset.dta
+-rw-r--r--   0 runner    (1001) docker     (123)     4861 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno_cat/model_4.cor
+-rw-r--r--   0 runner    (1001) docker     (123)     4861 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno_cat/model_4.cov
+-rw-r--r--   0 runner    (1001) docker     (123)     2884 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno_cat/model_4.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    26183 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno_cat/model_4.lst
+-rw-r--r--   0 runner    (1001) docker     (123)     1599 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno_cat/model_4.mod
+-rw-r--r--   0 runner    (1001) docker     (123)    13993 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno_cat/model_4.phi
+-rw-r--r--   0 runner    (1001) docker     (123)    14006 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno_cat/model_4_input.phi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.387093 pharmpy-core-0.97.0/tests/testdata/nonmem/linearize/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.483101 pharmpy-core-0.97.0/tests/testdata/nonmem/linearize/linearize_dir1/
+-rw-r--r--   0 runner    (1001) docker     (123)       44 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/linearize/linearize_dir1/command.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     2472 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/linearize/linearize_dir1/pheno_linbase.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    14234 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/linearize/linearize_dir1/pheno_linbase.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      618 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/linearize/linearize_dir1/pheno_linbase.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/linearize/linearize_dir1/pheno_linbase.phi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.487101 pharmpy-core-0.97.0/tests/testdata/nonmem/linearize/linearize_dir1/scm_dir1/
+-rw-r--r--   0 runner    (1001) docker     (123)      653 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/linearize/linearize_dir1/scm_dir1/derivatives.ext
+-rw-r--r--   0 runner    (1001) docker     (123)     9547 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/linearize/linearize_dir1/scm_dir1/derivatives.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      733 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/linearize/linearize_dir1/scm_dir1/derivatives.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     6986 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/linearize/linearize_dir1/scm_dir1/derivatives.phi
+-rw-r--r--   0 runner    (1001) docker     (123)      190 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/minimal.mod
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.387093 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.487101 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/covariance/
+-rw-r--r--   0 runner    (1001) docker     (123)     2032 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/covariance/pheno_nocovariance.coi
+-rw-r--r--   0 runner    (1001) docker     (123)     1615 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/covariance/pheno_nocovariance.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    17620 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/covariance/pheno_nocovariance.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      815 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/covariance/pheno_nocovariance.mod
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.387093 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/multPROB/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.387093 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/multPROB/multEST/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.487101 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/multPROB/multEST/withSIM/
+-rw-r--r--   0 runner    (1001) docker     (123)    14783 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/multPROB/multEST/withSIM/multprobmix_nm730.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    91887 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/multPROB/multEST/withSIM/multprobmix_nm730.lst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.387093 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.387093 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.487101 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/
+-rw-r--r--   0 runner    (1001) docker     (123)    36515 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/anneal2_V7_30_beta.lst
+-rw-r--r--   0 runner    (1001) docker     (123)    38720 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/pheno_multEST.dta
+-rw-r--r--   0 runner    (1001) docker     (123)     1963 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/pheno_multEST.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    16505 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/pheno_multEST.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      384 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/pheno_multEST.mod
+-rw-r--r--   0 runner    (1001) docker     (123)    13947 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/pheno_multEST.phi
+-rw-r--r--   0 runner    (1001) docker     (123)    59168 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/superid2_6_V7_30_beta.lst
+-rw-r--r--   0 runner    (1001) docker     (123)    37889 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/withBayes.cov
+-rw-r--r--   0 runner    (1001) docker     (123)   115118 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/withBayes.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    82511 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/withBayes.lst
+-rw-r--r--   0 runner    (1001) docker     (123)     2273 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/withBayes.mod
+-rw-r--r--   0 runner    (1001) docker     (123)    75841 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/withBayes.phi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.487101 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/noESTwithSIM/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/noESTwithSIM/onlysim.ext
+-rw-r--r--   0 runner    (1001) docker     (123)     5179 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/noESTwithSIM/onlysim.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      648 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/noESTwithSIM/onlysim.mod
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.387093 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.491102 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/
+-rw-r--r--   0 runner    (1001) docker     (123)    15883 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/UseCase7.lst
+-rw-r--r--   0 runner    (1001) docker     (123)    18122 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/example6b_V7_30_beta.lst
+-rw-r--r--   0 runner    (1001) docker     (123)    15469 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/hessian_error.lst
+-rw-r--r--   0 runner    (1001) docker     (123)    26695 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/large_s_matrix_cov_fail.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      688 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/maxeval0.ext
+-rw-r--r--   0 runner    (1001) docker     (123)     8760 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/maxeval0.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      661 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/maxeval0.mod
+-rw-r--r--   0 runner    (1001) docker     (123)      972 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/maxeval3.cov
+-rw-r--r--   0 runner    (1001) docker     (123)     1564 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/maxeval3.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    17548 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/maxeval3.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      691 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/maxeval3.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     6956 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/maxeval3.phi
+-rw-r--r--   0 runner    (1001) docker     (123)    13203 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/mox_fail_nonp.lst
+-rw-r--r--   0 runner    (1001) docker     (123)    14451 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/mox_nocov_nonp.lst
+-rw-r--r--   0 runner    (1001) docker     (123)     2492 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/near_bounds.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    11801 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/near_bounds.lst
+-rw-r--r--   0 runner    (1001) docker     (123)     1393 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/near_bounds.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     5460 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/nm710_fail_negV.lst
+-rw-r--r--   0 runner    (1001) docker     (123)    38720 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/pheno.dta
+-rw-r--r--   0 runner    (1001) docker     (123)     1170 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/pheno.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    17299 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/pheno.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      735 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/pheno.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     6933 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/pheno.phi
+-rw-r--r--   0 runner    (1001) docker     (123)    16143 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/pheno_nonp.lst
+-rw-r--r--   0 runner    (1001) docker     (123)    14090 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/phenocorr.lst
+-rw-r--r--   0 runner    (1001) docker     (123)    54699 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/sparse_matrix_with_msfi.lst
+-rw-r--r--   0 runner    (1001) docker     (123)    31702 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/theo.lst
+-rw-r--r--   0 runner    (1001) docker     (123)    19741 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/theo_nonp.lst
+-rw-r--r--   0 runner    (1001) docker     (123)    31702 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/theo_withcov.lst
+-rw-r--r--   0 runner    (1001) docker     (123)    13140 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/warfarin_ddmore.lst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.491102 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/withSIM/
+-rw-r--r--   0 runner    (1001) docker     (123)   178666 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/withSIM/control3boot.ext
+-rw-r--r--   0 runner    (1001) docker     (123)  1091059 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/withSIM/control3boot.res
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.495102 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/simfit/
+-rw-r--r--   0 runner    (1001) docker     (123)     4152 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/simfit/sim-1.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    38485 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/simfit/sim-1.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      841 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/simfit/sim-1.mod
+-rw-r--r--   0 runner    (1001) docker     (123)    41718 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/simfit/sim-1.phi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.495102 pharmpy-core-0.97.0/tests/testdata/nonmem/modeling/
+-rw-r--r--   0 runner    (1001) docker     (123)      857 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modeling/pheno_1transit.mod
+-rw-r--r--   0 runner    (1001) docker     (123)      884 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modeling/pheno_2transits.mod
+-rw-r--r--   0 runner    (1001) docker     (123)      665 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modeling/pheno_advan1.mod
+-rw-r--r--   0 runner    (1001) docker     (123)      819 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modeling/pheno_advan11.mod
+-rw-r--r--   0 runner    (1001) docker     (123)      846 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modeling/pheno_advan12.mod
+-rw-r--r--   0 runner    (1001) docker     (123)      707 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modeling/pheno_advan1_zero_order.mod
+-rw-r--r--   0 runner    (1001) docker     (123)      701 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modeling/pheno_advan2.mod
+-rw-r--r--   0 runner    (1001) docker     (123)      719 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modeling/pheno_advan2_seq.mod
+-rw-r--r--   0 runner    (1001) docker     (123)      735 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modeling/pheno_advan3.mod
+-rw-r--r--   0 runner    (1001) docker     (123)      769 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modeling/pheno_advan4.mod
+-rw-r--r--   0 runner    (1001) docker     (123)      826 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modeling/pheno_advan5_depot.mod
+-rw-r--r--   0 runner    (1001) docker     (123)      784 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modeling/pheno_advan5_nodepot.mod
+-rw-r--r--   0 runner    (1001) docker     (123)    18812 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modeling/pheno_zero_order.csv
+-rw-r--r--   0 runner    (1001) docker     (123)      937 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/modeling/transit_indirect_reabsorption.mod
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.503103 pharmpy-core-0.97.0/tests/testdata/nonmem/models/
+-rw-r--r--   0 runner    (1001) docker     (123)     1546 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/fviii6.datainfo
+-rw-r--r--   0 runner    (1001) docker     (123)     3072 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/fviii6.mod
+-rw-r--r--   0 runner    (1001) docker     (123)      336 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/fviii6.prn
+-rw-r--r--   0 runner    (1001) docker     (123)     1716 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox1.cov
+-rw-r--r--   0 runner    (1001) docker     (123)     1827 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox1.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    19098 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox1.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      762 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox1.mod
+-rw-r--r--   0 runner    (1001) docker     (123)    12566 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox1.phi
+-rw-r--r--   0 runner    (1001) docker     (123)     1306 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox2.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    90456 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox2.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      703 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox2.mod
+-rw-r--r--   0 runner    (1001) docker     (123)    12377 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox2.phi
+-rw-r--r--   0 runner    (1001) docker     (123)     1716 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox_2comp.cov
+-rw-r--r--   0 runner    (1001) docker     (123)     1827 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox_2comp.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    21336 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox_2comp.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      704 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox_2comp.mod
+-rw-r--r--   0 runner    (1001) docker     (123)    12566 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox_2comp.phi
+-rw-r--r--   0 runner    (1001) docker     (123)   175384 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox_simulated_log.csv
+-rw-r--r--   0 runner    (1001) docker     (123)   185992 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox_simulated_normal.csv
+-rw-r--r--   0 runner    (1001) docker     (123)     4764 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox_simulated_normal.datainfo
+-rw-r--r--   0 runner    (1001) docker     (123)   105888 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/moxo_simulated_amd.csv
+-rw-r--r--   0 runner    (1001) docker     (123)     2816 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/moxo_simulated_amd.datainfo
+-rw-r--r--   0 runner    (1001) docker     (123)    70155 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/mytab_mox2
+-rw-r--r--   0 runner    (1001) docker     (123)    11500 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/pef.csv
+-rwxr-xr-x   0 runner    (1001) docker     (123)      189 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/pef.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     1346 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_advan3_trans1.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    12218 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_advan3_trans1.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      452 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_advan3_trans1.mod
+-rw-r--r--   0 runner    (1001) docker     (123)    10093 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_advan3_trans1.phi
+-rw-r--r--   0 runner    (1001) docker     (123)      367 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_conc.mod
+-rw-r--r--   0 runner    (1001) docker     (123)      557 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_des_assignments.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     6107 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_dvid.csv
+-rw-r--r--   0 runner    (1001) docker     (123)      533 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_dvid.mod
+-rw-r--r--   0 runner    (1001) docker     (123)      989 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_noifs.coi
+-rw-r--r--   0 runner    (1001) docker     (123)      793 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_noifs.cor
+-rw-r--r--   0 runner    (1001) docker     (123)      793 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_noifs.cov
+-rw-r--r--   0 runner    (1001) docker     (123)      982 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_noifs.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    10527 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_noifs.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      428 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_noifs.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_noifs.phi
+-rw-r--r--   0 runner    (1001) docker     (123)      709 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_trans1.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    10693 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_trans1.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      273 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_trans1.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     4633 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_trans1.phi
+-rw-r--r--   0 runner    (1001) docker     (123)      763 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/pheno.datainfo
+-rw-r--r--   0 runner    (1001) docker     (123)    38720 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/pheno.dta
+-rw-r--r--   0 runner    (1001) docker     (123)      982 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/pheno.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    10540 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/pheno.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      345 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/pheno.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/pheno.phi
+-rw-r--r--   0 runner    (1001) docker     (123)      470 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_abbr.mod
+-rw-r--r--   0 runner    (1001) docker     (123)      354 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_abbr_comments.mod
+-rw-r--r--   0 runner    (1001) docker     (123)      629 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_block.mod
+-rw-r--r--   0 runner    (1001) docker     (123)      341 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_clashing_symbols.mod
+-rw-r--r--   0 runner    (1001) docker     (123)      947 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_etas.mod
+-rw-r--r--   0 runner    (1001) docker     (123)      736 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_multivariate_piecewise.mod
+-rw-r--r--   0 runner    (1001) docker     (123)      357 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_nm750.mod
+-rw-r--r--   0 runner    (1001) docker     (123)    38720 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_no_obs_1stID.dta
+-rw-r--r--   0 runner    (1001) docker     (123)      633 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_pd.csv
+-rw-r--r--   0 runner    (1001) docker     (123)      383 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_pd.mod
+-rw-r--r--   0 runner    (1001) docker     (123)    36053 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_rate.dta
+-rw-r--r--   0 runner    (1001) docker     (123)      989 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_real.coi
+-rw-r--r--   0 runner    (1001) docker     (123)      989 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_real.cor
+-rw-r--r--   0 runner    (1001) docker     (123)      989 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_real.cov
+-rw-r--r--   0 runner    (1001) docker     (123)     2851 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_real.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    21259 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_real.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      666 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_real.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_real.phi
+-rw-r--r--   0 runner    (1001) docker     (123)    90151 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_real.tab
+-rw-r--r--   0 runner    (1001) docker     (123)    22114 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_real.xml
+-rw-r--r--   0 runner    (1001) docker     (123)   298562 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_real_linbase.dta
+-rw-r--r--   0 runner    (1001) docker     (123)     1288 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_real_linbase.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    28308 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_real_linbase.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      712 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_real_linbase.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     6933 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_real_linbase.phi
+-rw-r--r--   0 runner    (1001) docker     (123)    17010 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_real_linbase.tab
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.507103 pharmpy-core-0.97.0/tests/testdata/nonmem/qa/
+-rw-r--r--   0 runner    (1001) docker     (123)   370034 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/qa/add_etas_linbase.dta
+-rw-r--r--   0 runner    (1001) docker     (123)     4838 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/qa/add_etas_linbase.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    16579 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/qa/add_etas_linbase.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      873 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/qa/add_etas_linbase.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     2350 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/qa/boxcox.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    14595 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/qa/boxcox.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      803 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/qa/boxcox.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/qa/boxcox.phi
+-rw-r--r--   0 runner    (1001) docker     (123)    11716 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/qa/cdd_results.json
+-rw-r--r--   0 runner    (1001) docker     (123)     2824 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/qa/fullblock.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    17210 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/qa/fullblock.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      653 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/qa/fullblock.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/qa/fullblock.phi
+-rw-r--r--   0 runner    (1001) docker     (123)     2620 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/qa/iov.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    12617 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/qa/iov.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      662 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/qa/iov.mod
+-rw-r--r--   0 runner    (1001) docker     (123)    24133 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/qa/iov.phi
+-rw-r--r--   0 runner    (1001) docker     (123)   262826 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/qa/pheno_linbase.dta
+-rw-r--r--   0 runner    (1001) docker     (123)     2472 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/qa/pheno_linbase.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    15014 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/qa/pheno_linbase.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      638 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/qa/pheno_linbase.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/qa/pheno_linbase.phi
+-rw-r--r--   0 runner    (1001) docker     (123)     3943 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/qa/resmod_results.json
+-rw-r--r--   0 runner    (1001) docker     (123)     2198 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/qa/scm_results.json
+-rw-r--r--   0 runner    (1001) docker     (123)   392990 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/qa/simeval_results.json
+-rw-r--r--   0 runner    (1001) docker     (123)     3262 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/qa/tdist.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    17544 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/qa/tdist.lst
+-rw-r--r--   0 runner    (1001) docker     (123)     1045 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/qa/tdist.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/qa/tdist.phi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.507103 pharmpy-core-0.97.0/tests/testdata/nonmem/ruvsearch/
+-rw-r--r--   0 runner    (1001) docker     (123)     1512 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/ruvsearch/mox3.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    13182 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/ruvsearch/mox3.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      672 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/ruvsearch/mox3.mod
+-rw-r--r--   0 runner    (1001) docker     (123)    12417 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/ruvsearch/mox3.phi
+-rw-r--r--   0 runner    (1001) docker     (123)   276902 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/ruvsearch/moxo_simulated_resmod.csv
+-rw-r--r--   0 runner    (1001) docker     (123)   180553 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/ruvsearch/mytab
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.507103 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.507103 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/backward_dir1/
+-rw-r--r--   0 runner    (1001) docker     (123)      337 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/backward_dir1/config_fake.scm
+-rw-r--r--   0 runner    (1001) docker     (123)     1812 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/backward_dir1/meta.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)     3068 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/backward_dir1/scmlog.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.511103 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/gofofv_dir1/
+-rw-r--r--   0 runner    (1001) docker     (123)    10037 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/gofofv_dir1/scmlog.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     5383 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/localmin.logf
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.511103 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/log_steps/
+-rw-r--r--   0 runner    (1001) docker     (123)      565 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/log_steps/backward_ofv_1.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      434 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/log_steps/backward_pval_1.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      215 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/log_steps/backward_pval_2.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      809 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/log_steps/forward_ofv_1.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      761 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/log_steps/forward_pval_1.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     3813 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/log_steps/forward_pval_2.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     2723 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/log_steps/forward_pval_3.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      325 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/log_steps/forward_pval_4.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.511103 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/mergeofv_dir1/
+-rw-r--r--   0 runner    (1001) docker     (123)      260 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/mergeofv_dir1/config_havebaserun.scm
+-rw-r--r--   0 runner    (1001) docker     (123)     1896 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/mergeofv_dir1/meta.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)    38957 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/mergeofv_dir1/scmlog.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.511103 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/mergeofv_dir2/
+-rw-r--r--   0 runner    (1001) docker     (123)      187 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/mergeofv_dir2/config_havebaserun.scm
+-rw-r--r--   0 runner    (1001) docker     (123)     1882 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/mergeofv_dir2/meta.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)    20500 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/mergeofv_dir2/scmlog.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     2115 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/meta.yaml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.511103 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/onlyforward_dir1/
+-rw-r--r--   0 runner    (1001) docker     (123)      318 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/onlyforward_dir1/config_normal.scm
+-rw-r--r--   0 runner    (1001) docker     (123)     1819 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/onlyforward_dir1/meta.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)     1762 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/onlyforward_dir1/scmlog.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.511103 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/scm_dir1/
+-rw-r--r--   0 runner    (1001) docker     (123)     8045 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/scm_dir1/scmlog.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.511103 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/scmplus_dir1/
+-rw-r--r--   0 runner    (1001) docker     (123)     6870 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/scm/scmplus_dir1/scmlog.txt
+-rw-r--r--   0 runner    (1001) docker     (123)   108031 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/sdtab1
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.515104 pharmpy-core-0.97.0/tests/testdata/nonmem/secondary_parameters/
+-rw-r--r--   0 runner    (1001) docker     (123)      793 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/secondary_parameters/pheno.cov
+-rw-r--r--   0 runner    (1001) docker     (123)    38720 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/secondary_parameters/pheno.dta
+-rw-r--r--   0 runner    (1001) docker     (123)     1324 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/secondary_parameters/pheno.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    16221 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/secondary_parameters/pheno.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      357 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/secondary_parameters/pheno.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/secondary_parameters/pheno.phi
+-rw-r--r--   0 runner    (1001) docker     (123)      793 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/secondary_parameters/run1.cov
+-rw-r--r--   0 runner    (1001) docker     (123)     1324 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/secondary_parameters/run1.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    16509 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/secondary_parameters/run1.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      365 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/secondary_parameters/run1.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/secondary_parameters/run1.phi
+-rw-r--r--   0 runner    (1001) docker     (123)      989 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/secondary_parameters/run2.cov
+-rw-r--r--   0 runner    (1001) docker     (123)     1454 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/secondary_parameters/run2.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    17071 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/secondary_parameters/run2.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      484 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/secondary_parameters/run2.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/nonmem/secondary_parameters/run2.phi
+-rw-r--r--   0 runner    (1001) docker     (123)    16730 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/pheno_data.csv
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.391093 pharmpy-core-0.97.0/tests/testdata/psn/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.515104 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/
+-rw-r--r--   0 runner    (1001) docker     (123)       50 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/command.txt
+-rw-r--r--   0 runner    (1001) docker     (123)    13424 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/est_data0.dta
+-rw-r--r--   0 runner    (1001) docker     (123)    13450 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/est_data1.dta
+-rw-r--r--   0 runner    (1001) docker     (123)    13336 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/est_data2.dta
+-rw-r--r--   0 runner    (1001) docker     (123)    13843 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/est_data3.dta
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.523105 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/
+-rw-r--r--   0 runner    (1001) docker     (123)      793 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model0.cor
+-rw-r--r--   0 runner    (1001) docker     (123)      793 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model0.cov
+-rw-r--r--   0 runner    (1001) docker     (123)     1324 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model0.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    17040 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model0.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      394 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model0.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     5263 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model0.phi
+-rw-r--r--   0 runner    (1001) docker     (123)      793 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model1.cor
+-rw-r--r--   0 runner    (1001) docker     (123)      793 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model1.cov
+-rw-r--r--   0 runner    (1001) docker     (123)     1324 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model1.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    17040 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model1.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      394 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model1.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     5263 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model1.phi
+-rw-r--r--   0 runner    (1001) docker     (123)      793 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model2.cor
+-rw-r--r--   0 runner    (1001) docker     (123)      793 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model2.cov
+-rw-r--r--   0 runner    (1001) docker     (123)     1324 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model2.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    17040 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model2.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      394 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model2.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     5263 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model2.phi
+-rw-r--r--   0 runner    (1001) docker     (123)      793 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model3.cor
+-rw-r--r--   0 runner    (1001) docker     (123)      793 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model3.cov
+-rw-r--r--   0 runner    (1001) docker     (123)     1324 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model3.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    17040 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model3.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      394 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model3.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     5377 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model3.phi
+-rw-r--r--   0 runner    (1001) docker     (123)      767 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/pred_model0.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    11625 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/pred_model0.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      407 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/pred_model0.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     1970 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/pred_model0.phi
+-rw-r--r--   0 runner    (1001) docker     (123)      767 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/pred_model1.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    11637 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/pred_model1.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      406 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/pred_model1.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     1970 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/pred_model1.phi
+-rw-r--r--   0 runner    (1001) docker     (123)      767 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/pred_model2.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    11623 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/pred_model2.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      405 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/pred_model2.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     1970 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/pred_model2.phi
+-rw-r--r--   0 runner    (1001) docker     (123)      806 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/pred_model3.cor
+-rw-r--r--   0 runner    (1001) docker     (123)      806 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/pred_model3.cov
+-rw-r--r--   0 runner    (1001) docker     (123)      995 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/pred_model3.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    15116 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/pred_model3.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      405 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/pred_model3.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     1856 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/pred_model3.phi
+-rw-r--r--   0 runner    (1001) docker     (123)     1509 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/meta.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)     4615 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/pred_data0.dta
+-rw-r--r--   0 runner    (1001) docker     (123)     4589 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/pred_data1.dta
+-rw-r--r--   0 runner    (1001) docker     (123)     4703 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/pred_data2.dta
+-rw-r--r--   0 runner    (1001) docker     (123)     4196 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/pred_data3.dta
+-rw-r--r--   0 runner    (1001) docker     (123)     1579 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/version_and_option_info.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      265 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/xv_result.csv
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.523105 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/
+-rw-r--r--   0 runner    (1001) docker     (123)       50 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/command.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      353 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/covariates_summary.csv
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.523105 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/final_models/
+-rw-r--r--   0 runner    (1001) docker     (123)     1983 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/final_models/model_4.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    14761 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/final_models/model_4.lst
+-rw-r--r--   0 runner    (1001) docker     (123)     1110 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/final_models/model_4.mod
+-rw-r--r--   0 runner    (1001) docker     (123)    13993 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/final_models/model_4.phi
+-rw-r--r--   0 runner    (1001) docker     (123)    14006 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/final_models/model_4_input.phi
+-rw-r--r--   0 runner    (1001) docker     (123)    19440 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/frem_dataset.dta
+-rw-r--r--   0 runner    (1001) docker     (123)     3246 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/frem_results.csv
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.527105 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/
+-rw-r--r--   0 runner    (1001) docker     (123)      613 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/filter_data_model.ext
+-rw-r--r--   0 runner    (1001) docker     (123)     9040 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/filter_data_model.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      525 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/filter_data_model.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     6946 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/filter_data_model.phi
+-rw-r--r--   0 runner    (1001) docker     (123)    93135 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/filtered_plus_type0.dta
+-rw-r--r--   0 runner    (1001) docker     (123)      793 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_1.cov
+-rw-r--r--   0 runner    (1001) docker     (123)     1324 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_1.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    16221 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_1.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      393 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_1.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_1.phi
+-rw-r--r--   0 runner    (1001) docker     (123)      393 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_1b.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_1b.phi
+-rw-r--r--   0 runner    (1001) docker     (123)     4392 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_2.cor
+-rw-r--r--   0 runner    (1001) docker     (123)     4392 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_2.cov
+-rw-r--r--   0 runner    (1001) docker     (123)     1996 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_2.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    21654 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_2.lst
+-rw-r--r--   0 runner    (1001) docker     (123)     1083 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_2.mod
+-rw-r--r--   0 runner    (1001) docker     (123)    14006 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_2.phi
+-rw-r--r--   0 runner    (1001) docker     (123)    13826 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_2_input.phi
+-rw-r--r--   0 runner    (1001) docker     (123)     1225 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_3.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    10472 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_3.lst
+-rw-r--r--   0 runner    (1001) docker     (123)     1162 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_3.mod
+-rw-r--r--   0 runner    (1001) docker     (123)    14006 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_3.phi
+-rw-r--r--   0 runner    (1001) docker     (123)    14006 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_3_input.phi
+-rw-r--r--   0 runner    (1001) docker     (123)     1225 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_3b.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    10750 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_3b.lst
+-rw-r--r--   0 runner    (1001) docker     (123)     1188 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_3b.mod
+-rw-r--r--   0 runner    (1001) docker     (123)    14006 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_3b.phi
+-rw-r--r--   0 runner    (1001) docker     (123)    14006 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_3b_input.phi
+-rw-r--r--   0 runner    (1001) docker     (123)     1816 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/meta.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)     2970 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/proposal_density.cov
+-rw-r--r--   0 runner    (1001) docker     (123)     1852 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/version_and_option_info.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.531105 pharmpy-core-0.97.0/tests/testdata/psn/qa_dir1/
+-rw-r--r--   0 runner    (1001) docker     (123)       39 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/qa_dir1/command.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.531105 pharmpy-core-0.97.0/tests/testdata/psn/qa_dir1/linearize_run/
+-rw-r--r--   0 runner    (1001) docker     (123)     5485 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/qa_dir1/linearize_run/results.json
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.531105 pharmpy-core-0.97.0/tests/testdata/psn/qa_dir1/linearize_run/scm_dir1/
+-rw-r--r--   0 runner    (1001) docker     (123)      705 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/qa_dir1/linearize_run/scm_dir1/derivatives.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    12131 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/qa_dir1/linearize_run/scm_dir1/derivatives.lst
+-rw-r--r--   0 runner    (1001) docker     (123)     1280 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/qa_dir1/linearize_run/scm_dir1/derivatives.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     6986 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/qa_dir1/linearize_run/scm_dir1/derivatives.phi
+-rw-r--r--   0 runner    (1001) docker     (123)   137744 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/qa_dir1/linearize_run/scm_dir1/extra_table
+-rw-r--r--   0 runner    (1001) docker     (123)   316422 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/qa_dir1/pheno_real_linbase.dta
+-rw-r--r--   0 runner    (1001) docker     (123)     1856 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/qa_dir1/pheno_real_linbase.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    13850 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/qa_dir1/pheno_real_linbase.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      700 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/qa_dir1/pheno_real_linbase.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/qa_dir1/pheno_real_linbase.phi
+-rw-r--r--   0 runner    (1001) docker     (123)    11536 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/qa_dir1/results_summary.yaml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.531105 pharmpy-core-0.97.0/tests/testdata/psn/resmod_dir1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1985 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/resmod_dir1/resmod_results.csv
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.531105 pharmpy-core-0.97.0/tests/testdata/psn/resmod_dir2/
+-rw-r--r--   0 runner    (1001) docker     (123)    11647 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/resmod_dir2/resmod_results.csv
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.531105 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.535106 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/
+-rw-r--r--   0 runner    (1001) docker     (123)    63331 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/orig_pred.dta
+-rw-r--r--   0 runner    (1001) docker     (123)      793 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/original.cor
+-rw-r--r--   0 runner    (1001) docker     (123)      793 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/original.cov
+-rw-r--r--   0 runner    (1001) docker     (123)     1324 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/original.ext
+-rw-r--r--   0 runner    (1001) docker     (123)      591 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/original.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     6973 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/original.phi
+-rw-r--r--   0 runner    (1001) docker     (123)    54391 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/original_res_table.dta
+-rw-r--r--   0 runner    (1001) docker     (123)    38720 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/pheno.dta
+-rw-r--r--   0 runner    (1001) docker     (123)     1306 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-1.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    14039 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-1.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      509 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-1.mod
+-rw-r--r--   0 runner    (1001) docker     (123)    13972 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-1.phi
+-rw-r--r--   0 runner    (1001) docker     (123)     1306 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-2.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    14039 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-2.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      509 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-2.mod
+-rw-r--r--   0 runner    (1001) docker     (123)    13972 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-2.phi
+-rw-r--r--   0 runner    (1001) docker     (123)      653 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-3.ext
+-rw-r--r--   0 runner    (1001) docker     (123)     9500 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-3.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      509 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-3.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     6986 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-3.phi
+-rw-r--r--   0 runner    (1001) docker     (123)      653 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-4.ext
+-rw-r--r--   0 runner    (1001) docker     (123)     9500 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-4.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      509 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-4.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     6986 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-4.phi
+-rw-r--r--   0 runner    (1001) docker     (123)      653 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-5.ext
+-rw-r--r--   0 runner    (1001) docker     (123)     9500 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-5.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      509 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-5.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     6986 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-5.phi
+-rw-r--r--   0 runner    (1001) docker     (123)      653 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-6.ext
+-rw-r--r--   0 runner    (1001) docker     (123)     9500 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-6.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      509 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-6.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     6986 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-6.phi
+-rw-r--r--   0 runner    (1001) docker     (123)      653 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-7.ext
+-rw-r--r--   0 runner    (1001) docker     (123)     9500 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-7.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      509 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-7.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     6986 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-7.phi
+-rw-r--r--   0 runner    (1001) docker     (123)      653 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-8.ext
+-rw-r--r--   0 runner    (1001) docker     (123)     9500 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-8.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      509 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-8.mod
+-rw-r--r--   0 runner    (1001) docker     (123)     6986 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-8.phi
+-rw-r--r--   0 runner    (1001) docker     (123)    73024 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim_res_table-1.dta
+-rw-r--r--   0 runner    (1001) docker     (123)    73024 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim_res_table-2.dta
+-rw-r--r--   0 runner    (1001) docker     (123)    36512 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim_res_table-3.dta
+-rw-r--r--   0 runner    (1001) docker     (123)    36512 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim_res_table-4.dta
+-rw-r--r--   0 runner    (1001) docker     (123)    36512 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim_res_table-5.dta
+-rw-r--r--   0 runner    (1001) docker     (123)    36512 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim_res_table-6.dta
+-rw-r--r--   0 runner    (1001) docker     (123)    36512 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim_res_table-7.dta
+-rw-r--r--   0 runner    (1001) docker     (123)    36512 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim_res_table-8.dta
+-rw-r--r--   0 runner    (1001) docker     (123)    21489 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/summary_cwres.csv
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.539106 pharmpy-core-0.97.0/tests/testdata/results/
+-rw-r--r--   0 runner    (1001) docker     (123)    24788 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/allometry_results.json
+-rw-r--r--   0 runner    (1001) docker     (123)    50648 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/amd_results.json
+-rw-r--r--   0 runner    (1001) docker     (123)   130598 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/bootstrap_results.json
+-rw-r--r--   0 runner    (1001) docker     (123)    12291 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/cdd_results.json
+-rw-r--r--   0 runner    (1001) docker     (123)  1360720 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/covsearch_results.json
+-rw-r--r--   0 runner    (1001) docker     (123)     6524 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/estmethod_results.json
+-rw-r--r--   0 runner    (1001) docker     (123)   205797 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/iivsearch_results.json
+-rw-r--r--   0 runner    (1001) docker     (123)   197228 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/iovsearch_results.json
+-rw-r--r--   0 runner    (1001) docker     (123)    12639 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/linearize_results.json
+-rw-r--r--   0 runner    (1001) docker     (123)      787 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/metadata.json
+-rw-r--r--   0 runner    (1001) docker     (123)   105603 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/modelsearch_results.json
+-rw-r--r--   0 runner    (1001) docker     (123)     7841 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/qa_results.json
+-rw-r--r--   0 runner    (1001) docker     (123)    57352 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/ruvsearch_results.json
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.391093 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.543106 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/
+-rw-r--r--   0 runner    (1001) docker     (123)      787 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/metadata.json
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.543106 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.543106 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/.datasets/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.391093 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/.datasets/.hash/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.543106 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/.datasets/.hash/-7907770233072098756/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/.datasets/.hash/-7907770233072098756/input_model.csv
+-rw-r--r--   0 runner    (1001) docker     (123)   183701 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/.datasets/input_model.csv
+-rw-r--r--   0 runner    (1001) docker     (123)     4639 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/.datasets/input_model.datainfo
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:58:19.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/.lock
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.543106 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/input_model/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.543106 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/input_model/.pharmpy/
+-rw-r--r--   0 runner    (1001) docker     (123)     7143 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/input_model/.pharmpy/results.json
+-rw-r--r--   0 runner    (1001) docker     (123)      707 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/input_model/input_model.mod
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.543106 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.543106 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/.pharmpy/
+-rw-r--r--   0 runner    (1001) docker     (123)      119 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/.pharmpy/metadata.json
+-rw-r--r--   0 runner    (1001) docker     (123)     7120 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/.pharmpy/results.json
+-rw-r--r--   0 runner    (1001) docker     (123)     1488 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/modelsearch_run1.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    91188 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/modelsearch_run1.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      881 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/modelsearch_run1.mod
+-rw-r--r--   0 runner    (1001) docker     (123)    12377 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/modelsearch_run1.phi
+-rw-r--r--   0 runner    (1001) docker     (123)    70155 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/mytab_mox1
+-rw-r--r--   0 runner    (1001) docker     (123)      169 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/nonmem.json
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/stderr
+-rw-r--r--   0 runner    (1001) docker     (123)     1796 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/stdout
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.543106 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.543106 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/.pharmpy/
+-rw-r--r--   0 runner    (1001) docker     (123)      119 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/.pharmpy/metadata.json
+-rw-r--r--   0 runner    (1001) docker     (123)     7112 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/.pharmpy/results.json
+-rw-r--r--   0 runner    (1001) docker     (123)     1761 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/modelsearch_run2.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    91119 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/modelsearch_run2.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      834 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/modelsearch_run2.mod
+-rw-r--r--   0 runner    (1001) docker     (123)    17187 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/modelsearch_run2.phi
+-rw-r--r--   0 runner    (1001) docker     (123)    70155 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/mytab_mox2
+-rw-r--r--   0 runner    (1001) docker     (123)      169 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/nonmem.json
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/stderr
+-rw-r--r--   0 runner    (1001) docker     (123)     1796 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/stdout
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.547107 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.547107 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/.pharmpy/
+-rw-r--r--   0 runner    (1001) docker     (123)      119 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/.pharmpy/metadata.json
+-rw-r--r--   0 runner    (1001) docker     (123)    53630 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/.pharmpy/results.json
+-rw-r--r--   0 runner    (1001) docker     (123)     1943 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/modelsearch_run3.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    91754 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/modelsearch_run3.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      975 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/modelsearch_run3.mod
+-rw-r--r--   0 runner    (1001) docker     (123)    17187 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/modelsearch_run3.phi
+-rw-r--r--   0 runner    (1001) docker     (123)    70155 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/mytab_mox3
+-rw-r--r--   0 runner    (1001) docker     (123)      169 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/nonmem.json
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/stderr
+-rw-r--r--   0 runner    (1001) docker     (123)     2012 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/stdout
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.547107 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.547107 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/.pharmpy/
+-rw-r--r--   0 runner    (1001) docker     (123)      119 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/.pharmpy/metadata.json
+-rw-r--r--   0 runner    (1001) docker     (123)    54979 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/.pharmpy/results.json
+-rw-r--r--   0 runner    (1001) docker     (123)     1943 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/modelsearch_run4.ext
+-rw-r--r--   0 runner    (1001) docker     (123)    91879 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/modelsearch_run4.lst
+-rw-r--r--   0 runner    (1001) docker     (123)      989 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/modelsearch_run4.mod
+-rw-r--r--   0 runner    (1001) docker     (123)    17187 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/modelsearch_run4.phi
+-rw-r--r--   0 runner    (1001) docker     (123)    70155 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/mytab_mox4
+-rw-r--r--   0 runner    (1001) docker     (123)      169 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/nonmem.json
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/stderr
+-rw-r--r--   0 runner    (1001) docker     (123)     2012 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/stdout
+-rw-r--r--   0 runner    (1001) docker     (123)    47403 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/results.csv
+-rw-r--r--   0 runner    (1001) docker     (123)   105597 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/results.json
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.551107 pharmpy-core-0.97.0/tests/tools/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/tools/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2400 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/tools/test_allometry.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7559 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/tools/test_amd.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1369 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/tools/test_bootstrap.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8607 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/tools/test_cdd.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3914 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/tools/test_covsearch.py
+-rw-r--r--   0 runner    (1001) docker     (123)      500 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/tools/test_crossval.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2802 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/tools/test_estmethod.py
+-rw-r--r--   0 runner    (1001) docker     (123)      956 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/tools/test_exports.py
+-rw-r--r--   0 runner    (1001) docker     (123)    28369 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/tools/test_frem.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8107 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/tools/test_iivsearch.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3186 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/tools/test_iovsearch.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4328 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/tools/test_linearize.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11786 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/tools/test_mfl.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1096 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/tools/test_ml.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10258 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/tools/test_modelsearch.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10900 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/tools/test_qa.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1799 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/tools/test_rankfuncs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15964 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/tools/test_run.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2546 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/tools/test_runtool.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6451 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/tools/test_ruvsearch.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19845 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/tools/test_scm.py
+-rw-r--r--   0 runner    (1001) docker     (123)      247 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/tools/test_simeval.py
+-rw-r--r--   0 runner    (1001) docker     (123)      979 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/tools/test_start_model.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1836 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/tools/test_structsearch.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2962 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/tools/test_summarize_individuals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1535 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/tools/test_wrap.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:02:54.551107 pharmpy-core-0.97.0/tests/workflows/
+-rw-r--r--   0 runner    (1001) docker     (123)     1988 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/workflows/test_call.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6586 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/workflows/test_execute.py
+-rw-r--r--   0 runner    (1001) docker     (123)      318 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/workflows/test_log.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3173 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/workflows/test_model_database.py
+-rw-r--r--   0 runner    (1001) docker     (123)      416 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/workflows/test_task.py
+-rw-r--r--   0 runner    (1001) docker     (123)      198 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/workflows/test_tool_database.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4125 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tests/workflows/test_workflow.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3971 2023-06-28 06:54:49.000000 pharmpy-core-0.97.0/tox.ini
```

### Comparing `pharmpy-core-0.96.0/AUTHORS.rst` & `pharmpy-core-0.97.0/AUTHORS.rst`

 * *Files 25% similar despite different names*

```diff
@@ -9,14 +9,15 @@
 * Rikard Nordgren, rikard.nordgren@farmaci.uu.se (maintainer)
 * Stella Belin, stella.belin@farmaci.uu.se (maintainer)
 * Kajsa Harling
 * Zhe Huang, zhe.huang@farmaci.uu.se
 * Aurelien Ooms
 * Gunnar Yngman, gunnar.yngman@farmaci.uu.se
 * Johan Borg
+* Antonia Hufnagl
 
 Scientific input
 ~~~~~~~~~~~~~~~~
 
 * Mats O. Karlsson
 * Andrew C. Hooker
 * João A. Abrantes
@@ -25,14 +26,18 @@
 * Simon Carter
 * Xiaomei Chen
 * Alzahra Hamdan
 * Osama Qutishat
 * Sebastian Ueckert
 * Shijun Wang
 * Tianwu Yang
+* Keqi Shi
+* Xuanlin Liu
+* Samia Mohamed
+* Yersultan Mirasbekov
 
 Funding
 ~~~~~~~
 
 A warm thanks to all our sponsors!
 
 *  F\. Hoffman-La Roche Ltd.
```

### Comparing `pharmpy-core-0.96.0/CHANGELOG.rst` & `pharmpy-core-0.97.0/CHANGELOG.rst`

 * *Files 1% similar despite different names*

```diff
@@ -1,7 +1,25 @@
+0.97.0 (2023-06-28)
+-------------------
+
+New features
+============
+
+* Support BLQ transformations in RUVSearch
+* New tool structsearch and support for TMDD models
+* Add function ``modeling.set_direct_effect``
+* Add function ``modeling.add_effect_compartment``
+
+Changes
+=======
+
+* Reorganizing of modeling module
+* Support changing error model with BLQ transformation
+* Add ``max_iter`` option for RUVSearch
+
 0.96.0 (2023-05-26)
 -------------------
 
 Changes
 =======
 
 * Rename functions handling the precision matrix (was previously referring to information matrix which was an error)
```

### Comparing `pharmpy-core-0.96.0/CODE_OF_CONDUCT.rst` & `pharmpy-core-0.97.0/CODE_OF_CONDUCT.rst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/LICENSE` & `pharmpy-core-0.97.0/LICENSE`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/LICENSE.LESSER` & `pharmpy-core-0.97.0/LICENSE.LESSER`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/MANIFEST.in` & `pharmpy-core-0.97.0/MANIFEST.in`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/PKG-INFO` & `pharmpy-core-0.97.0/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pharmpy-core
-Version: 0.96.0
+Version: 0.97.0
 Summary: Pharmacometric modeling
 Home-page: https://pharmpy.github.io
 Author: Rikard Nordgren
 Author-email: rikard.nordgren@farmaci.uu.se
 License: GNU Lesser General Public License v3 (LGPLv3)
 Project-URL: Bug Tracker, https://github.com/pharmpy/pharmpy/issues
 Project-URL: Source Code, https://github.com/pharmpy/pharmpy
@@ -40,14 +40,32 @@
 * A model abstraction as a foundation for higher level operations on models
 * Functions for manipulation of models, e.g. changing model components like elimination or absorption
 * Reading NONMEM models and results
 * Running models and complex workflows (with NONMEM or to some extent nlmixr)
 
 This is the `team behind Pharmpy <https://pharmpy.github.io/latest/contributors.html>`_
 
+0.97.0 (2023-06-28)
+-------------------
+
+New features
+============
+
+* Support BLQ transformations in RUVSearch
+* New tool structsearch and support for TMDD models
+* Add function ``modeling.set_direct_effect``
+* Add function ``modeling.add_effect_compartment``
+
+Changes
+=======
+
+* Reorganizing of modeling module
+* Support changing error model with BLQ transformation
+* Add ``max_iter`` option for RUVSearch
+
 0.96.0 (2023-05-26)
 -------------------
 
 Changes
 =======
 
 * Rename functions handling the precision matrix (was previously referring to information matrix which was an error)
```

### Comparing `pharmpy-core-0.96.0/README.rst` & `pharmpy-core-0.97.0/README.rst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/docs/NONMEM.rst` & `pharmpy-core-0.97.0/docs/NONMEM.rst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/docs/Pharmpy_logo.svg` & `pharmpy-core-0.97.0/docs/Pharmpy_logo.svg`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/docs/Pharmpy_logo_dark.svg` & `pharmpy-core-0.97.0/docs/Pharmpy_logo_dark.svg`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/docs/_ext/conversion.py` & `pharmpy-core-0.97.0/docs/_ext/conversion.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/docs/_ext/pharmpy_snippet.py` & `pharmpy-core-0.97.0/docs/_ext/pharmpy_snippet.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/docs/allometry.rst` & `pharmpy-core-0.97.0/docs/allometry.rst`

 * *Files 1% similar despite different names*

```diff
@@ -12,16 +12,16 @@
 
 The allometry tool is available both in Pharmpy/pharmr and from the command line.
 
 To initiate allometry in Python/R:
 
 .. pharmpy-code::
 
-    from pharmpy.modeling import read_model, read_modelfit_results
-    from pharmpy.tools import run_allometry
+    from pharmpy.modeling import read_model
+    from pharmpy.tools import read_modelfit_results, run_allometry
 
     start_model = read_model('path/to/model')
     start_model_results = read_modelfit_results('path/to/model')
     res = run_allometry(model=start_model, results=start_model_results)
 
 To run allometry from the command line, the example code is redefined accordingly:
```

### Comparing `pharmpy-core-0.96.0/docs/amd.rst` & `pharmpy-core-0.97.0/docs/amd.rst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/docs/bootstrap.rst` & `pharmpy-core-0.97.0/docs/bootstrap.rst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/docs/cdd.rst` & `pharmpy-core-0.97.0/docs/cdd.rst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/docs/cli.rst` & `pharmpy-core-0.97.0/docs/cli.rst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/docs/conf.py` & `pharmpy-core-0.97.0/docs/conf.py`

 * *Files 2% similar despite different names*

```diff
@@ -29,15 +29,15 @@
 
 source_suffix = '.rst'
 master_doc = 'index'
 project = 'Pharmpy'
 year = '2018-2023'
 authors = ['the Pharmpy development team']
 copyright = '{0}; {1}'.format(year, ', '.join(authors))
-version = release = '0.96.0'
+version = release = '0.97.0'
 html_show_sourcelink = False
 
 pygments_style = 'trac'
 templates_path = ['.']
 
 html_static_path = ['.']
 html_theme = "pydata_sphinx_theme"
```

### Comparing `pharmpy-core-0.96.0/docs/contribute.rst` & `pharmpy-core-0.97.0/docs/contribute.rst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/docs/covsearch.rst` & `pharmpy-core-0.97.0/docs/covsearch.rst`

 * *Files 1% similar despite different names*

```diff
@@ -13,16 +13,16 @@
 
 The COVsearch tool is available both in Pharmpy/pharmr and from the command line.
 
 To initiate COVsearch in Python/R:
 
 .. pharmpy-code::
 
-    from pharmpy.modeling import read_model, read_modelfit_results
-    from pharmpy.tools import run_covsearch
+    from pharmpy.modeling import read_model
+    from pharmpy.tools import run_covsearch, read_modelfit_results
 
     start_model = read_model('path/to/model')
     start_model_results = read_modelfit_results('path/to/model')
     res = run_covsearch(algorithm='scm-forward-then-backward',
                         model=start_model,
                         results=start_model_results,
                         effects='COVARIATE(@IIV, @CONTINUOUS, *); COVARIATE(@IIV, @CATEGORICAL, CAT)',
```

### Comparing `pharmpy-core-0.96.0/docs/crossval.rst` & `pharmpy-core-0.97.0/docs/crossval.rst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/docs/custom.css` & `pharmpy-core-0.97.0/docs/custom.css`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/docs/data.rst` & `pharmpy-core-0.97.0/docs/data.rst`

 * *Files 18% similar despite different names*

```diff
@@ -1,15 +1,16 @@
+.. _dataset:
+
 ===================
 Datasets in Pharmpy
 ===================
 
-Datasets in Pharmpy are represented using the :py:class:`pd.DataFrame` class and a separate :py:class:`DataInfo` class that provides additional information about the dataset.
-This could contain for example a description of how the columns are used in the model or the units used for the data.
-
-.. math::
+Datasets in Pharmpy are represented using the :py:class:`pd.DataFrame` class and a separate
+:py:class:`pharmpy.model.DataInfo` class that provides additional information about the dataset. This could contain
+for example a description of how the columns are used in the model or the units used for the data.
 
 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 Retrieving the dataset from a model
 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 
 The dataset connected to a model can be retrieved from the `dataset` attribute.
 
@@ -43,125 +44,27 @@
 
    raw.dtypes
 
 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 Update the dataset of a model
 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 
-A new or updated dataset can be set to a model
+Since the Pharmpy dataset is a pandas dataframe, it can be manipulated as such. A new or updated dataset can be set to
+a model like this:
 
 .. pharmpy-execute::
    :hide-output:
 
    import numpy as np
 
    df['DV'] = np.log(df['DV'], where=(df['DV'] != 0))
    model = model.replace(dataset=df)
 
-~~~~~~~~
-Subjects
-~~~~~~~~
-
-An array of all subject IDs can be retrieved.
-
-.. pharmpy-execute::
-
-    from pharmpy.modeling import get_ids
-    model = read_model(path / "pheno_real.mod")
-    get_ids(model)
-
-The number of subjects in the dataset could optionally be retrieved directly.
-
-.. pharmpy-execute::
-
-    from pharmpy.modeling import get_number_of_individuals
-    get_number_of_individuals(model)
-
-
-~~~~~~~~~~~~
-Observations
-~~~~~~~~~~~~
-
-The observations of the dataset indexed on subject ID and the independent variable can be extracted.
-
-.. pharmpy-execute::
-
-    from pharmpy.modeling import get_observations
-    get_observations(model)
-
-The total number of observations can optionally be retrieved directly.
-
-.. pharmpy-execute::
-
-    from pharmpy.modeling import get_number_of_observations
-    get_number_of_observations(model)
-
-~~~~~~
-Dosing
-~~~~~~
-
-Extract dosing information
-==========================
-
-The doses of the dataset indexed on subject ID and the independent variable can be extracted.
-
-.. pharmpy-execute::
-
-    from pharmpy.modeling import get_doses
-    doses = get_doses(model)
-    doses
-
-All unique doses can be listed
-
-.. pharmpy-execute::
-
-    doses.unique()
-
-as well as the largest and the smallest dose
-
-.. pharmpy-execute::
-
-    doses.min()
-
-.. pharmpy-execute::
-
-    doses.max()
-
-Dose grouping
-=============
-
-It is possible to create a DOSEID that groups each dose period starting from 1.
-
-.. pharmpy-execute::
-
-    from pharmpy.modeling import get_doseid
-    ser = get_doseid(model)
-    ser
-
-Time after dose
-===============
-
-Add a column for time after dose (TAD)
-
-.. pharmpy-execute::
-
-    from pharmpy.modeling import add_time_after_dose
-    model = add_time_after_dose(model)
-    model.dataset['TAD']
-
-Concentration parameters
-========================
-
-Extract pharmacokinetic concentration parameters from the dataset
-
-.. pharmpy-execute::
-
-    from pharmpy.modeling import get_concentration_parameters_from_data
-    get_concentration_parameters_from_data(model)
-
+The :py:mod:`pharmpy.modeling` module has several functions to examine and modify the dataset, see the user guide for
+:ref:`dataset modeling<modeling_dataset>`.
 
 .. _datainfo:
 
 ~~~~~~~~
 DataInfo
 ~~~~~~~~
```

### Comparing `pharmpy-core-0.96.0/docs/design.rst` & `pharmpy-core-0.97.0/docs/design.rst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/docs/estmethod.rst` & `pharmpy-core-0.97.0/docs/estmethod.rst`

 * *Files 0% similar despite different names*

```diff
@@ -12,16 +12,16 @@
 
 The Estmethod tool is available both in Pharmpy/pharmr and from the command line.
 
 To initiate Estmethod in Python/R:
 
 .. pharmpy-code::
 
-    from pharmpy.modeling import read_model, read_modelfit_results
-    from pharmpy.tools import run_estmethod
+    from pharmpy.modeling import read_model
+    from pharmpy.tools import read_modelfit_results, run_estmethod
 
     start_model = read_model('path/to/model')
     start_model_results = read_modelfit_results('path/to/model')
     res = run_estmethod(algorithm='exhaustive',
                         model=start_model,
                         results=start_model_results,
                         methods='all',
```

### Comparing `pharmpy-core-0.96.0/docs/frem.rst` & `pharmpy-core-0.97.0/docs/frem.rst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/docs/getting_started.rst` & `pharmpy-core-0.97.0/docs/getting_started.rst`

 * *Files 15% similar despite different names*

```diff
@@ -24,16 +24,16 @@
 
     pip install --index-url https://google-coral.github.io/py-repo/ tflite_runtime
 
 ---------------
 A first example
 ---------------
 
-The :class:`pharmpy.Model` class is representation of a nonlinear mixed effects model. For example, to
-read an example NONMEM model (in this case ``pheno``):
+The :class:`pharmpy.model.Model` class is representation of a nonlinear mixed effects model. For example, to
+load an example NONMEM model:
 
 .. pharmpy-execute::
    :hide-output:
 
     from pharmpy.modeling import load_example_model, print_model_code
 
     model = load_example_model('pheno')
@@ -41,11 +41,14 @@
 
 The model file format is automatically detected:
 
 .. pharmpy-execute::
 
     type(model)
 
-You can read more about how to read in an examine your model in :ref:`model`, and how to transform your model via
+You can read more about how to read in and examine your model in :ref:`model`, and how to transform your model via
 :ref:`modeling`. We also have several :ref:`pharmpy_tools` to run more complex workflows.
 
+.. note::
 
+    In order to run any of the tools you need to have a configuration file set up with a path to NONMEM, instructions
+    can be found :ref:`here <config_page>`.
```

### Comparing `pharmpy-core-0.96.0/docs/help_functions.py` & `pharmpy-core-0.97.0/docs/help_functions.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/docs/iivsearch.rst` & `pharmpy-core-0.97.0/docs/iivsearch.rst`

 * *Files 0% similar despite different names*

```diff
@@ -13,16 +13,16 @@
 
 The IIVsearch tool is available both in Pharmpy/pharmr and from the command line.
 
 To initiate IIVsearch in Python/R:
 
 .. pharmpy-code::
 
-    from pharmpy.modeling import read_model, read_modelfit_results
-    from pharmpy.tools import run_iivsearch
+    from pharmpy.modeling import read_model
+    from pharmpy.tools import read_modelfit_results, run_iivsearch
 
     start_model = read_model('path/to/model')
     start_model_results = read_model_results('path/to/model')
     res = run_iivsearch(algorithm='brute_force',
                         model=start_model,
                         results=start_model_results,
                         iiv_strategy='no_add',
```

### Comparing `pharmpy-core-0.96.0/docs/images/Pharmpy_symbol.svg` & `pharmpy-core-0.97.0/docs/images/Pharmpy_symbol.svg`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/docs/images/tools.png` & `pharmpy-core-0.97.0/docs/images/tools.png`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/docs/index.rst` & `pharmpy-core-0.97.0/docs/index.rst`

 * *Files 19% similar despite different names*

```diff
@@ -17,19 +17,19 @@
 pharmr package or via its built-in command line interface. Current features include:
 
 * General model abstraction for pharmacometric models
 * Manipulation of models
 * Extraction of model estimation results
 * Manipulation of datasets
 * Various calculations and evaluations
-* Running models
-* Running higher level workflows or tools
-* Plugin system to support different model formats
+* Plugin system to support different model formats (NONMEM, nlmixr2, rxODE2)
+* Running models (NONMEM, nlmixr2, rxODE2)
+* Running higher level workflows or tools (NONMEM)
 * Parsing and updating NONMEM models
-* Partial support for model conversion to nlmixr and rxode
+* Model conversion to NONMEM, nlmixr2, and rxODE2
 
 We encourage your contribution to the Pharmpy project! You can report issues and post suggestions of features via
 GitHub issues (to `Pharmpy <https://github.com/pharmpy/pharmpy/issues>`_ or to
 `pharmr <https://github.com/pharmpy/pharmr/issues>`_). If you want to contribute with code you can find more information
 under :ref:`contribute`.
 
 Pharmpy is maintained by the Uppsala University Pharmacometrics group and is an open-source project.
```

### Comparing `pharmpy-core-0.96.0/docs/iovsearch.rst` & `pharmpy-core-0.97.0/docs/iovsearch.rst`

 * *Files 1% similar despite different names*

```diff
@@ -13,16 +13,16 @@
 
 The IOVsearch tool is available both in Pharmpy/pharmr and from the command line.
 
 To initiate IOVsearch in Python/R:
 
 .. pharmpy-code::
 
-    from pharmpy.modeling import read_model, read_modelfit_results
-    from pharmpy.tools import run_iovsearch
+    from pharmpy.modeling import read_model
+    from pharmpy.tools import read_modelfit_results, run_iovsearch
 
     start_model = read_model('path/to/model')
     start_model_results = read_modelfit_results('path/to/model')
     res = run_iovsearch(model=start_model,
                         results=start_model_results,
                         column='OCC',
                         list_of_parameters=None,
```

### Comparing `pharmpy-core-0.96.0/docs/license.rst` & `pharmpy-core-0.97.0/docs/license.rst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/docs/linearize.rst` & `pharmpy-core-0.97.0/docs/linearize.rst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/docs/model.rst` & `pharmpy-core-0.97.0/docs/model.rst`

 * *Files 16% similar despite different names*

```diff
@@ -1,20 +1,34 @@
 .. _model:
 
 =================
 The Pharmpy model
 =================
 
-At the heart of Pharmpy lies its non-linear mixed effects model abstraction. A model needs to follow the interface of the base model class :py:class:`pharmpy.model.Model`. This means that any model format can in theory be supported by Pharmpy via subclasses that implement the same base interface. This makes any operation performed on a model be the same regardless of the underlying implementation of the model and it is one of the core design principles of Pharmpy.
+At the heart of Pharmpy lies its non-linear mixed effects model abstraction. A model needs to follow the interface of
+the base model class :py:class:`pharmpy.model.Model`. This means that any model format can in theory be supported by
+Pharmpy via subclasses that implement the same base interface. This makes any operation performed on a model be the
+same regardless of the underlying implementation of the model and it is one of the core design principles of Pharmpy.
+This allows the functions in :py:mod:`pharmpy.modeling` and tools in :py:mod:`pharmpy.tools` to be independent
+on the estimation software: it is only when writing and fitting a model that the implementation is estimation software
+specific.
+
+.. warning::
+
+    This section is intended to give an overview of the Pharmpy model and its different components. For higher level
+    manipulations, please check out the functions in :py:mod:`pharmpy.modeling`, which are described in further detail
+    in :ref:`the modeling user guide<modeling>`
+
 
 ~~~~~~~~~~~~~~~~~~
 Reading in a model
 ~~~~~~~~~~~~~~~~~~
 
-Reading a model from a model specification file into a Pharmy model object can be done by using the :py:func:`read_model<pharmpy.modeling.read_model>` function.
+Reading a model from a model specification file into a Pharmpy model object can be done by using the
+:py:func:`pharmpy.modeling.read_model` function.
 
 .. pharmpy-execute::
    :hide-output:
    :hide-code:
 
    from pathlib import Path
    path = Path('tests/testdata/nonmem/')
@@ -23,133 +37,218 @@
    :hide-output:
 
    from pharmpy.modeling import read_model
 
    model = read_model(path / "pheno_real.mod")
 
 
-Internally this will trigger a model type detection to select which model implementation to use, i.e. if it is an NM-TRAN control stream the Pharmpy NONMEM model class will be selected transparent to the user.
-
-~~~~~~~~~~
-Model name
-~~~~~~~~~~
-
-A model has a name property that can be read or changed. After reading a model from a file the name is set to the filename without extension.
-
-.. pharmpy-execute::
-
-   model.name
+Internally this will trigger a model type detection to select which model implementation to use, i.e. if it is an
+NM-TRAN control stream the Pharmpy NONMEM model subclass will be selected.
 
 .. _model_write:
 
 ~~~~~~~~~~~~~~~
 Writing a model
 ~~~~~~~~~~~~~~~
 
-A model object can be written to a file using its source format. By default the model file will be created in the current working directory using the name of the model.
+A model object can be written to a file using its source format. By default the model file will be created in the
+current working directory using the name of the model.
 
 .. pharmpy-code::
 
     from pharmpy.modeling import write_model
     write_model(model)
 
 Optionally a path can be specified:
 
 .. pharmpy-code::
 
    write_model(model, path='/home/user/mymodel.mod')
 
 
-~~~~~~~~~~~~~~~~~~~~~~
-Getting the model code
-~~~~~~~~~~~~~~~~~~~~~~
+~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
+Inspecting the model attributes
+~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
+
+Name and description
+~~~~~~~~~~~~~~~~~~~~
 
-The model code can be inspected using :py:func:`print_model_code<pharmpy.modeling.print_model_code>` or retrieved using :py:func:`generate_model_code<pharmpy.modeling.generate_model_code>`.
+A model has a name property that can be read or changed. After reading a model from a file the name is set to the
+filename without extension.
 
 .. pharmpy-execute::
 
-    from pharmpy.modeling import print_model_code
+   model.name
 
-    print_model_code(model)
 
-~~~~~~~~~~~~~~~~
-Model parameters
-~~~~~~~~~~~~~~~~
 
-Model parameters are scalar values that are used in the mathematical definition of the model and are estimated when a model is fit from data. The parameters of a model are thus optimization parameters and can in turn be used as parameters in statistical distributions or as structural parameters. A parameter is represented by using the :py:class:`pharmpy.Parameter` class.
+Parameters
+~~~~~~~~~~
+
+Model parameters are scalar values that are used in the mathematical definition of the model and are estimated when a
+model is fit from data. The parameters of a model are thus optimization parameters and can in turn be used as
+parameters in statistical distributions or as structural parameters. A parameter is represented by using the
+:py:class:`pharmpy.model.Parameter` class.
+
+It is often convenient to work with a set of parameters at the same time, for example all parameters of a model.
+In Pharmpy multiple parameters are organized using the :py:class:`pharmpy.model.Parameters` class as an ordered set of
+:py:class:`pharmpy.model.Parameter`. All parameters of a model can be accessed by using the parameters attribute:
 
 .. pharmpy-execute::
 
-   from pharmpy.model import Parameter
+   parset = model.parameters
+   parset
 
-   par = Parameter('THETA_1', 0.1, upper=2, fix=False)
-   par
+Operations on multiple parameters are made easier using methods or properties on parameter sets. For example, to get
+all initial estimates as a dictionary:
+
+.. pharmpy-execute::
 
-A model parameter must have a name and an inital value and can optionally be constrained to a lower and or upper bound. A parameter can also be fixed meaning that it will be set to its initial value. The parameter attributes can be read out via properties.
+   parset.inits
+
+Each parameter can be retrieved using indexing:
+
+.. pharmpy-execute::
+
+   par = parset['PTVCL']
+
+A model parameter must have a name and an initial value and can optionally be constrained to a lower and or upper bound.
+A parameter can also be fixed meaning that it will be set to its initial value. The parameter attributes can be read
+out via properties.
 
 .. pharmpy-execute::
 
    par.lower
 
+Random variables
+~~~~~~~~~~~~~~~~
+
+The random variables of a model are available through the ``random_variables`` property and are organized using the
+:py:class:`pharmpy.model.RandomVariables` which is an ordered set of distributions of either
+:py:class:`pharmpy.model.NormalDistribution` or :py:class:`pharmpy.model.JointNormalDistribution` class. All random
+variables of a model can be accessed by using the random variables attribute:
+
+.. pharmpy-execute::
 
-~~~~~~~~~~~~~~
-Parameter sets
-~~~~~~~~~~~~~~
+   rvs = model.random_variables
+   rvs
 
-It is often convenient to work with a set of parameters at the same time, for example all parameters of a model. In Pharmpy multiple parameters are organized using the :py:class:`pharmpy.Parameters` class as an ordered set of :py:class:`pharmpy.Parameter`. All parameters of a model can be accessed by using the parameters attribute:
+The set of random variables can be split into subsets of random variables, for example IIVs:
 
 .. pharmpy-execute::
 
-   parset = model.parameters
-   parset
+   rvs.iiv
 
-Each parameter can be retrieved using indexing
+A distribution can be extracted using the name of one of the etas:
 
 .. pharmpy-execute::
 
-   parset['PTVCL']
+   dist = rvs['ETA_1']
+   dist
 
-Operations on multiple parameters are made easier using methods or properties on parameter sets. For example:
+Similarly to parameters, we can extract different attributes from the distribution:
 
-Get all initial estimates as a dictionary:
+.. pharmpy-execute::
+
+   dist.names
+
+Statements
+~~~~~~~~~~
+
+The model statements represent the mathematical description of the model. All statements can be retrieved via the
+statements property as a :py:class:`pharmpy.model.Statements` object, which is a list of model statements of either the
+class :py:class:`pharmpy.model.Assignment` or :py:class:`pharmpy.model.ODESystem`.
 
 .. pharmpy-execute::
 
-   parset.inits
+   statements = model.statements
+   statements
 
+Changing the statements of a model can be done by setting the statements property. This way of manipulating a model is
+quite low level and flexible but cumbersome. For higher level model manipulation use the :py:mod:`pharmpy.modeling`
+module.
 
-~~~~~~~~~~~~~~~~
-Random variables
+If the model has a system of ordinary differential equations this will be part of the statements. It can easily be
+retrieved from the statement object
+
+.. pharmpy-execute::
+
+   statements.ode_system
+
+Get the amounts vector:
+
+.. pharmpy-execute::
+
+   statements.ode_system.amounts
+
+Get the compartmental matrix:
+
+.. pharmpy-execute::
+
+   statements.ode_system.compartmental_matrix
+
+Dataset and datainfo
+~~~~~~~~~~~~~~~~~~~~
+
+See :ref:`dataset`.
+
+Estimation steps
 ~~~~~~~~~~~~~~~~
 
-The random variables of a model are available through the ``random_variables`` property:
+The :py:class:`pharmpy.model.EstimationSteps` object contains information on how to estimate the model.
 
 .. pharmpy-execute::
 
-   rvs = model.random_variables
-   rvs
+   ests = model.estimation_steps
+   ests
+
+Dependent variables
+~~~~~~~~~~~~~~~~~~~
+
+A model can describe one or more dependent variables (output variables). Each dependent variable is defined in the
+``dependent_variables`` attribute. This is a dictionary of each dependent variable symbol to the corresponding ``DVID``.
+If there is only one dependent variable the ``DVID`` column in the dataset is not needed and its value in this
+definition is unimportant. The expressions of the dependent variables are all found in the statements.
 
 .. pharmpy-execute::
-   :hide-output:
 
-   eta1 = rvs['ETA_1']
+    model.dependent_variables
+
+~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
+Low level manipulations of the model object
+~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 
-Joint distributions are also supported
+Creating and adding parameters
+~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
+
+It is possible to create a parameter of the :py:class:`pharmpy.model.Parameter` class.
+
+.. pharmpy-execute::
+
+   from pharmpy.model import Parameter
+
+   par = Parameter('THETA_1', 0.1, upper=2, fix=False)
+   par
+
+Substituting symbolic random variable distribution with numeric
+~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 
 .. pharmpy-execute::
 
    from pharmpy.tools import read_modelfit_results
 
    frem_path = path / "frem" / "pheno" / "model_4.mod"
    frem_model = read_model(frem_path)
    frem_model_results = read_modelfit_results(frem_path)
 
    rvs = frem_model.random_variables
    rvs
 
+Starting by extracting the variance:
+
 .. pharmpy-execute::
 
    omega = rvs['ETA_1'].variance
    omega
 
 Substitution of numerical values can be done directly from initial values
 
@@ -178,49 +277,7 @@
 
    a = np.array(omega_est).astype(np.float64)
    a
 
 .. pharmpy-execute::
 
    np.linalg.cholesky(a)
-
-~~~~~~~~~~~~~~~~~
-Model statements
-~~~~~~~~~~~~~~~~~
-
-The model statements represent the mathematical description of the model. All statements can be retrieved via the statements property as a :py:class:`pharmpy.Statements` object, which is a list of model statements.
-
-.. pharmpy-execute::
-
-   statements = model.statements
-   print(statements)
-
-Changing the statements of a model can be done by setting the statements property. This way of manipulating a model is quite low level and flexible but cumbersome. For higher level model manipulation use the :py:mod:`pharmpy.modeling` module.
-
-If the model has a system of ordinary differential equations this will be part of the statements. It can easily be retrieved from the statement object
-
-.. pharmpy-execute::
-
-   print(statements.ode_system)
-
-Get the amounts vector:
-
-.. pharmpy-execute::
-
-   statements.ode_system.amounts
-
-Get the compartmental matrix:
-
-.. pharmpy-execute::
-
-   statements.ode_system.compartmental_matrix
-
-
-~~~~~~~~~~~~~~~~~~~
-Dependent variables
-~~~~~~~~~~~~~~~~~~~
-
-A model can describe one or more dependent variables (output variables). Each dependent variable is defined in the ``dependent_variables`` attribute. This is a dictionary of each dependent variable symbol to the corresponding ``DVID``. If there is only one dependent variable the ``DVID`` column in the dataset is not needed and its value in this definition is unimportant. The expressions of the dependent variables are all found in the statements.
-
-.. pharmpy-execute::
-
-    model.dependent_variables
```

### Comparing `pharmpy-core-0.96.0/docs/modelsearch.rst` & `pharmpy-core-0.97.0/docs/modelsearch.rst`

 * *Files 0% similar despite different names*

```diff
@@ -13,16 +13,16 @@
 
 The modelsearch tool is available both in Pharmpy/pharmr and from the command line.
 
 To initiate modelsearch in Python/R:
 
 .. pharmpy-code::
 
-    from pharmpy.modeling import read_model, read_modelfit_results
-    from pharmpy.tools import run_modelsearch
+    from pharmpy.modeling import read_model
+    from pharmpy.tools import read_modelfit_results, run_modelsearch
 
     start_model = read_model('path/to/model')
     start_model_results = read_modelfit_results('path/to/model')
     res = run_modelsearch(search_space='PERIPHERALS(1);LAGTIME()',
                           algorithm='reduced_stepwise',
                           model=start_model,
                           results=start_model_results,
```

### Comparing `pharmpy-core-0.96.0/docs/nonmem_plugin.rst` & `pharmpy-core-0.97.0/docs/nonmem_plugin.rst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/docs/pharmr_logo.svg` & `pharmpy-core-0.97.0/docs/pharmr_logo.svg`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/docs/plots.rst` & `pharmpy-core-0.97.0/docs/plots.rst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/docs/plugins.rst` & `pharmpy-core-0.97.0/docs/plugins.rst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/docs/projects.rst` & `pharmpy-core-0.97.0/docs/projects.rst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/docs/qa.rst` & `pharmpy-core-0.97.0/docs/qa.rst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/docs/ruvsearch.rst` & `pharmpy-core-0.97.0/docs/ruvsearch.rst`

 * *Files 1% similar despite different names*

```diff
@@ -12,16 +12,16 @@
 
 The RUVsearch tool is available both in Pharmpy/pharmr and from the command line.
 
 To initiate RUVsearch in Python/R:
 
 .. pharmpy-code::
 
-    from pharmpy.modeling import read_model, read_modelfit_results
-    from pharmpy.tools import run_ruvsearch
+    from pharmpy.modeling import read_model
+    from pharmpy.tools import read_modelfit_results, run_ruvsearch
 
     start_model = read_model('path/to/model')
     start_model_results = read_modelfit_results('path/to/model')
     res = run_ruvsearch(model=start_model, results=start_model_results)
 
 To run RUVsearch from the command line, the example code is redefined accordingly:
```

### Comparing `pharmpy-core-0.96.0/docs/scm.rst` & `pharmpy-core-0.97.0/docs/scm.rst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/docs/simeval.rst` & `pharmpy-core-0.97.0/docs/simeval.rst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/docs/tools.rst` & `pharmpy-core-0.97.0/docs/tools.rst`

 * *Files 1% similar despite different names*

```diff
@@ -15,14 +15,19 @@
 are implemented in Pharmpy, while the tools connected to PsN allows for parsing and presenting
 results from PsN tools. Documentation of PsN tools can be found :ref:`here <psn_with_pharmpy>`.
 
 ~~~~~~~~~~~~~~~~
 Tools in Pharmpy
 ~~~~~~~~~~~~~~~~
 
+.. note::
+
+    In order to run any of the tools you need to have a configuration file set up with a path to NONMEM, instructions
+    can be found :ref:`here <config_page>`.
+
 .. toctree::
    :maxdepth: 1
 
    AMD - automatic model development <amd>
    Modelsearch - search for best structural model for a PK model <modelsearch>
    IIVsearch - search for best IIV structure (both variance and covariance) <iivsearch>
    IOVsearch - search for best IOV structure and trim IIV <iovsearch>
@@ -47,16 +52,17 @@
 +------------+---------------------------------------------+
 
 ~~~~~~~~~~~~~~~
 Common features
 ~~~~~~~~~~~~~~~
 
 .. note::
-    The AMD tool is a collection of tools, meaning that some aspects of this section may not be applicable. For example
-    datasets will be in the database for each subtool
+
+    The AMD tool is a collection of tools, meaning that some aspects of this section may not be applicable. For
+    example, datasets will be in the database for each subtool.
 
 .. _tool_database:
 
 Tool database
 ~~~~~~~~~~~~~
 
 When running a tool, all candidate models and their corresponding files are stored in a tool database. As an example,
```

### Comparing `pharmpy-core-0.96.0/docs/using_r.rst` & `pharmpy-core-0.97.0/docs/using_r.rst`

 * *Files 2% similar despite different names*

```diff
@@ -43,16 +43,16 @@
 If you get any error during the installation or when running the code above, please check :ref:`trouble_shoot_pharmr`.
 
 .. _trouble_shoot_pharmr:
 
 Trouble shooting
 ================
 
-Wrong Python version
---------------------
+Wrong Python version when using conda
+-------------------------------------
 
 pharmr uses the package `reticulate <https://rstudio.github.io/reticulate>`_ for calling Python from R. When reticulate
 sets up Miniconda it can default to use Python 3.8. If you have any trouble installing Pharmpy or any of its
 dependencies, you can do the following to check the Python version in your reticulate environment:
 
 .. code-block:: r
 
@@ -85,15 +85,15 @@
 
 .. code-block::
 
     python:         .../r-reticulate/bin/python
     libpython:      .../r-reticulate/lib/libpython3.11.so
     ...
 
-If you are using Rstudio you can change this in either project or global options, under Python.
+If you are using Rstudio you can change this in either project or global options, under Python/Python interpreter.
 
 Mismatch of versions between Pharmpy and pharmr
 -----------------------------------------------
 
 The version number of pharmr mirrors Pharmpy, so it is important to make sure they have the same version number
 (a warning will appear if they are different). To avoid this happening, use ``install_pharmpy()`` which detects which
 version of pharmr you have installed and installs the correct version.
```

### Comparing `pharmpy-core-0.96.0/requirements.txt` & `pharmpy-core-0.97.0/requirements.txt`

 * *Files 4% similar despite different names*

```diff
@@ -10,97 +10,97 @@
 certifi==2023.5.7
 charset-normalizer==3.1.0
 click==8.1.3
 cloudpickle==2.2.1
 comm==0.1.3
 commonmark==0.9.1
 csscompressor==0.9.5
-dask==2023.5.0
+dask==2023.6.1
 debugpy==1.6.7
 decorator==5.1.1
 defusedxml==0.7.1
-distributed==2023.5.0
+distributed==2023.6.1
 docutils==0.20.1
 entrypoints==0.4
 executing==1.2.0
 fastjsonschema==2.17.1
-fsspec==2023.5.0
+fsspec==2023.6.0
 HeapDict==1.0.1
 idna==3.4
 imagesize==1.4.1
-importlib_metadata==6.6.0
-ipykernel==6.23.1
-ipython==8.13.2
+importlib_metadata==6.7.0
+ipykernel==6.23.3
+ipython==8.14.0
 ipywidgets==8.0.6
 jedi==0.18.2
 Jinja2==3.1.2
 jsonschema==4.17.3
-jupyter-client==8.2.0
-jupyter-core==5.3.0
+jupyter-client==8.3.0
+jupyter-core==5.3.1
 jupyter-sphinx==0.4.0
 jupyterlab-pygments==0.2.2
 jupyterlab-widgets==3.0.7
 lark==1.1.5
 locket==1.0.0
 lxml==4.9.2
-MarkupSafe==2.1.2
+MarkupSafe==2.1.3
 matplotlib-inline==0.1.6
 mistune==2.0.5
 mpmath==1.3.0
 msgpack==1.0.5
 nbclient==0.8.0
-nbconvert==7.4.0
-nbformat==5.8.0
+nbconvert==7.6.0
+nbformat==5.9.0
 nest-asyncio==1.5.6
 networkx==3.1
 numexpr==2.8.4
 numpy==1.24.3
 packaging==23.1
 pandas==1.5.3
 pandocfilters==1.5.0
 parso==0.8.3
 partd==1.4.0
 pexpect==4.8.0
 pickleshare==0.7.5
-platformdirs==3.5.1
+platformdirs==3.8.0
 prompt-toolkit==3.0.38
 psutil==5.9.5
 ptyprocess==0.7.0
 pure-eval==0.2.2
 Pygments==2.15.1
 pyreadr==0.4.7
 pyrsistent==0.19.3
 python-dateutil==2.8.2
 pytz==2023.3
 pywin32>=302,!=304; sys_platform == 'win32' and platform_python_implementation != 'PyPy'
 PyYAML==6.0
 requests==2.31.0
-pyzmq==25.0.2
-rich==13.3.5
-scipy==1.10.1
+pyzmq==25.1.0
+rich==13.4.2
+scipy==1.11.0
 six==1.16.0
 snowballstemmer==2.2.0
 sortedcontainers==2.4.0
 soupsieve==2.4.1
 Sphinx==7.0.1
 sphinxcontrib-devhelp==1.0.2
 sphinxcontrib-htmlhelp==2.0.1
 sphinxcontrib-jsmath==1.0.1
 sphinxcontrib-qthelp==1.0.3
 sphinxcontrib-serializinghtml==1.1.5
 sphinxcontrib.applehelp==1.0.4
 stack-data==0.6.2
 symengine==0.10.0
 sympy==1.12
-tblib==1.7.0
+tblib==2.0.0
 tinycss2==1.2.1
 toolz==0.12.0
 tornado==6.3.2
 traitlets==5.9.0
-urllib3==2.0.2
+urllib3==2.0.3
 wcwidth==0.2.6
 webencodings==0.5.1
 widgetsnbextension==4.0.7
 zict==3.0.0
 zipp==3.15.0
 tflite-runtime==2.12.0; sys_platform == 'linux' and python_version == '3.9'
 tflite_runtime @ https://github.com/hjonnala/snippets/raw/main/wheels/python3.10/tflite_runtime-2.5.0.post1-cp310-cp310-linux_x86_64.whl ; sys_platform == 'linux' and python_version == '3.10'
```

### Comparing `pharmpy-core-0.96.0/setup.cfg` & `pharmpy-core-0.97.0/setup.cfg`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/setup.py` & `pharmpy-core-0.97.0/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -25,15 +25,15 @@
     txt = re.compile(pat, re.MULTILINE | re.DOTALL).findall(text_str)
     txt = [dedent(block).strip() for block in txt]
     return '\n\n'.join(txt)
 
 
 setup(
     name='pharmpy-core',
-    version='0.96.0',
+    version='0.97.0',
     license='GNU Lesser General Public License v3 (LGPLv3)',
     description='Pharmacometric modeling',
     long_description='%s\n\n%s'
     % (strip_refs(longdesc(read('README.rst'))), strip_refs(read('CHANGELOG.rst'))),
     author='Rikard Nordgren',
     author_email='rikard.nordgren@farmaci.uu.se',
     url='https://pharmpy.github.io',
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/cli.py` & `pharmpy-core-0.97.0/src/pharmpy/cli.py`

 * *Files 0% similar despite different names*

```diff
@@ -755,15 +755,15 @@
         method=args.method,
         force_posdef_covmatrix=args.force_posdef_covmatrix,
         force_posdef_samples=args.force_posdef_samples,
     )
     res.to_json(path=args.psn_dir / 'results.json')
     res.to_csv(path=args.psn_dir / 'results.csv')
 
-    from pharmpy.modeling.reporting import create_report
+    from pharmpy.tools.reporting import create_report
 
     create_report(res, args.psn_dir)
 
 
 def results_linearize(args):
     from pharmpy.tools.linearize.results import psn_linearize_results
 
@@ -844,15 +844,15 @@
     """Subcommand to generate reports"""
     results_path = args.psn_dir / 'results.json'
     if not results_path.is_file():
         error(FileNotFoundError(results_path))
     from pharmpy.results import read_results
 
     res = read_results(results_path)
-    from pharmpy.modeling.reporting import create_report
+    from pharmpy.tools.reporting import create_report
 
     create_report(res, args.psn_dir)
 
 
 def results_summary(args):
     """Subcommand to output summary of modelfit"""
     for model in args.models:
@@ -905,15 +905,15 @@
     """Returns :class:`~pharmpy.model.Model` or pd.DataFrame from *path*"""
     path = check_input_path(path)
     from pharmpy.plugins.utils import PluginError
 
     try:
         from pharmpy.model import Model
 
-        obj = Model.create_model(path)
+        obj = Model.parse_model(path)
     except PluginError:
         obj = pd.read_csv(path)
     return obj
 
 
 def comma_list(s):
     if s == '':
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/config.py` & `pharmpy-core-0.97.0/src/pharmpy/config.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/deps/__init__.py` & `pharmpy-core-0.97.0/src/pharmpy/deps/__init__.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/deps/altair.py` & `pharmpy-core-0.97.0/src/pharmpy/deps/altair.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/internals/df.py` & `pharmpy-core-0.97.0/src/pharmpy/internals/df.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/internals/ds/ordered_set.py` & `pharmpy-core-0.97.0/src/pharmpy/internals/ds/ordered_set.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/internals/expr/eval.py` & `pharmpy-core-0.97.0/src/pharmpy/internals/expr/eval.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/internals/expr/funcs.py` & `pharmpy-core-0.97.0/src/pharmpy/internals/expr/funcs.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/internals/expr/leaves.py` & `pharmpy-core-0.97.0/src/pharmpy/internals/expr/leaves.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/internals/expr/ode.py` & `pharmpy-core-0.97.0/src/pharmpy/internals/expr/ode.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/internals/expr/subs.py` & `pharmpy-core-0.97.0/src/pharmpy/internals/expr/subs.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/internals/expr/tree.py` & `pharmpy-core-0.97.0/src/pharmpy/internals/expr/tree.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/internals/expr/units.py` & `pharmpy-core-0.97.0/src/pharmpy/internals/expr/units.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/internals/fn/signature.py` & `pharmpy-core-0.97.0/src/pharmpy/internals/fn/signature.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/internals/fn/type.py` & `pharmpy-core-0.97.0/src/pharmpy/internals/fn/type.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/internals/fs/lock.py` & `pharmpy-core-0.97.0/src/pharmpy/internals/fs/lock.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/internals/fs/path.py` & `pharmpy-core-0.97.0/src/pharmpy/internals/fs/path.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/internals/fs/tmp.py` & `pharmpy-core-0.97.0/src/pharmpy/internals/fs/tmp.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/internals/graph/directed/connected_components.py` & `pharmpy-core-0.97.0/src/pharmpy/internals/graph/directed/connected_components.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/internals/immutable.py` & `pharmpy-core-0.97.0/src/pharmpy/internals/immutable.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/internals/math.py` & `pharmpy-core-0.97.0/src/pharmpy/internals/math.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/internals/module/lazy.py` & `pharmpy-core-0.97.0/src/pharmpy/internals/module/lazy.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/internals/parse/generic.py` & `pharmpy-core-0.97.0/src/pharmpy/internals/parse/generic.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/internals/parse/ignored.py` & `pharmpy-core-0.97.0/src/pharmpy/internals/parse/ignored.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/internals/parse/missing.py` & `pharmpy-core-0.97.0/src/pharmpy/internals/parse/missing.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/internals/parse/prettyprint.py` & `pharmpy-core-0.97.0/src/pharmpy/internals/parse/prettyprint.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/internals/parse/tree.py` & `pharmpy-core-0.97.0/src/pharmpy/internals/parse/tree.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/internals/parse/treeprint.py` & `pharmpy-core-0.97.0/src/pharmpy/internals/parse/treeprint.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/internals/sequence/lcs.py` & `pharmpy-core-0.97.0/src/pharmpy/internals/sequence/lcs.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/internals/set/partitions.py` & `pharmpy-core-0.97.0/src/pharmpy/internals/set/partitions.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/internals/set/subsets.py` & `pharmpy-core-0.97.0/src/pharmpy/internals/set/subsets.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/internals/unicode.py` & `pharmpy-core-0.97.0/src/pharmpy/internals/unicode.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/__init__.py` & `pharmpy-core-0.97.0/src/pharmpy/model/__init__.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/data.py` & `pharmpy-core-0.97.0/src/pharmpy/model/data.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/datainfo.py` & `pharmpy-core-0.97.0/src/pharmpy/model/datainfo.py`

 * *Files 1% similar despite different names*

```diff
@@ -275,15 +275,15 @@
         }
 
     @classmethod
     def from_dict(cls, d):
         return cls(
             name=d['name'],
             type=d['type'],
-            unit=sympy.parse_expr(d['unit']),
+            unit=parse_units(d['unit']),
             scale=d['scale'],
             continuous=d['continuous'],
             categories=d['categories'],
             drop=d['drop'],
             datatype=d['datatype'],
             descriptor=d['descriptor'],
         )
@@ -865,29 +865,36 @@
         return {
             col.name: col.datatype
             if not col.drop and not col.datatype.startswith('nmtran')
             else 'str'
             for col in self
         }
 
+    def to_dict(self):
+        return self._to_dict(path=None)
+
+    @classmethod
+    def from_dict(cls, d):
+        columns = [ColumnInfo.from_dict(col) for col in d['columns']]
+        return cls(columns=columns, path=d['path'], separator=d['separator'])
+
     def _to_dict(self, path: Optional[str]):
         a = []
         for col in self._columns:
             d = {
                 "name": col.name,
                 "type": col.type,
                 "scale": col.scale,
                 "continuous": col.continuous,
                 "categories": col.categories,
                 "unit": str(col.unit),
                 "datatype": col.datatype,
                 "drop": col.drop,
+                "descriptor": col.descriptor,
             }
-            if col.descriptor is not None:
-                d["descriptor"] = col.descriptor
             a.append(d)
 
         return {
             "columns": a,
             "path": path,
             "separator": self._separator,
         }
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/distributions/numeric.py` & `pharmpy-core-0.97.0/src/pharmpy/model/distributions/numeric.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/distributions/symbolic.py` & `pharmpy-core-0.97.0/src/pharmpy/model/distributions/symbolic.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/estimation.py` & `pharmpy-core-0.97.0/src/pharmpy/model/estimation.py`

 * *Files 4% similar despite different names*

```diff
@@ -305,19 +305,20 @@
             'isample': self._isample,
             'niter': self._niter,
             'auto': self._auto,
             'keep_every_nth_iter': self._keep_every_nth_iter,
             'solver': self._solver,
             'solver_rtol': self._solver_rtol,
             'solver_atol': self._solver_atol,
-            'tool_options': self._tool_options,
+            'tool_options': dict(self._tool_options),
         }
 
     @classmethod
     def from_dict(cls, d):
+        d['tool_options'] = frozenmapping(d['tool_options'])
         return cls(**d)
 
     def __repr__(self):
         return (
             f'EstimationStep("{self.method}", interaction={self.interaction}, '
             f'cov={self.cov}, evaluation={self.evaluation}, '
             f'maximum_evaluations={self.maximum_evaluations}, laplace={self.laplace}, '
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/fcon/model.py` & `pharmpy-core-0.97.0/src/pharmpy/model/external/fcon/model.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/nlmixr/error_model.py` & `pharmpy-core-0.97.0/src/pharmpy/model/external/nlmixr/error_model.py`

 * *Files 11% similar despite different names*

```diff
@@ -40,15 +40,15 @@
 
     def find_term(self):
         # NEED TO BE
         # VAR 1 : y = F + F*eps + eps
         # VAR 2 : y = F + F*theta*eps + theta*eps (EPS FIX 1)
         # VAR 3 : y = F + W*eps (W = sqrt(theta....)) (EPS FIX 1)
         # VAR 4 : y = F + W*eps (W = F*theta + theta) (EPS FIX 1)
-        # ELSE raise error
+        # ELSE conversion might be incorrect.
         terms = sympy.Add.make_args(self.expr)
         # Assert that it follows the above set of format rules
         assert len(terms) <= 3
 
         errors = []
         for term in terms:
             error_term = False
@@ -86,37 +86,51 @@
                     self.res += term
                     self.create_res_alias()
 
         if self.res is None:
             print("No resulting term found")
             exit
         elif len(errors) > 2:
-            print("Too many error terms found")
-            exit
+            print("Too many error terms found. Will try to translate either way.")
 
         for t in errors:
             prop = False
+            ali_removed = False
             term = t["term"]
             full_term = t["full_term"]
             for symbol in full_term.free_symbols.union(term.free_symbols):
                 for ali in find_aliases(symbol, self.model):
                     if ali in self.res_alias:
                         prop = True
                         # Remove the resulting symbol from the error term
                         term = convert_eps_to_sigma(term, self.model)
-                        term = term.subs(ali, 1)
-                        self.prop = error(
-                            self.model, term, t["sigma"], sigma_alias=t["sigma_alias"], prop=True
-                        )
-
-            if prop is False:
+                        if ali in term.free_symbols:
+                            term = term.subs(ali, 1)
+                            ali_removed = True
+            if prop is True:
+                if not ali_removed:
+                    term = term / self.res
+                if self.prop.expr == 0:
+                    self.prop = error(
+                        self.model,
+                        term,
+                        t["sigma"],
+                        sigma_alias=t["sigma_alias"],
+                        prop=True,
+                    )
+                else:
+                    self.prop.expr = self.prop.expr + term
+            else:
                 term = convert_eps_to_sigma(term, self.model)
-                self.add = error(
-                    self.model, term, t["sigma"], sigma_alias=t["sigma_alias"], add=True
-                )
+                if self.add.expr == 0:
+                    self.add = error(
+                        self.model, term, t["sigma"], sigma_alias=t["sigma_alias"], add=True
+                    )
+                else:
+                    self.add.expr = self.add.expr + term
 
     def is_only_piecewise(self):
         dv = list(self.model.dependent_variables.keys())[0]
         for s in reversed(self.model.statements.after_odes):
             if s.symbol == dv:
                 if not s.expression.is_Piecewise:
                     self.only_piecewise = False
@@ -152,15 +166,20 @@
             if self.model.parameters[str(self.sigma)].init == 1.0:
                 if self.model.parameters[str(self.sigma)].fix:
                     return True
         else:
             return False
 
     def check_dependecies(self):
-        if self.model is not None and self.expr is not None:
+        if (
+            self.model is not None
+            and self.expr is not None
+            and self.model.parameters[self.sigma].init == 1
+            and self.sigma_fix
+        ):
             accepted_symbols = set([self.sigma, self.sigma_alias])
             thetas = get_thetas(self.model).symbols
             accepted_symbols.update(thetas)
             etas = [sympy.Symbol(i) for i in self.model.random_variables.etas.names]
             accepted_symbols.update(etas)
             for symbol in self.expr.free_symbols:
                 if not any([i in accepted_symbols for i in find_aliases(symbol, self.model)]):
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/nlmixr/ini.py` & `pharmpy-core-0.97.0/src/pharmpy/model/external/nlmixr/ini.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/nlmixr/model.py` & `pharmpy-core-0.97.0/src/pharmpy/model/external/nlmixr/model.py`

 * *Files 2% similar despite different names*

```diff
@@ -4,33 +4,30 @@
 
 import pharmpy.model
 from pharmpy.internals.code_generator import CodeGenerator
 from pharmpy.modeling import drop_columns, get_evid, translate_nmtran_time, update_inits
 
 from .error_model import res_error_term
 from .ini import add_eta, add_sigma, add_theta
-from .model_block import add_bioavailability, add_lag_times, add_ode, add_statements
+from .model_block import add_bio_lag, add_ode, add_statements
 from .sanity_checks import check_model
 
 
 def convert_model(
     model: pharmpy.model.Model,
-    keep_etas: bool = False,
     skip_check: bool = False,
     updated_estimates: bool = False,
 ) -> pharmpy.model.Model:
     """
     Convert a NONMEM model into an nlmixr model
 
     Parameters
     ----------
     model : pharmpy.model.Model
         A NONMEM pharmpy model object
-    keep_etas : bool, optional
-        Decide if NONMEM estimated thetas are to be used. The default is False.
     skip_check : bool, optional
         Skip determination of error model type. Could speed up conversion. The default is False.
 
     Returns
     -------
     pharmpy.model.Model
         A model converted to nlmixr format.
@@ -182,16 +179,16 @@
         dv_term = res_error_term(model, dv_statement.expression)
         dependencies = dv_term.dependencies()
         dv_term.create_res_alias()
         res_alias = dv_term.res_alias
 
     # Add bioavailability statements
     if model.statements.ode_system is not None:
-        add_bioavailability(model, cg)
-        add_lag_times(model, cg)
+        add_bio_lag(model, cg, bio=True)
+        add_bio_lag(model, cg, lag=True)
 
     # Add statements after ODEs
     if len(model.statements.after_odes) == 0:
         statements = model.statements
     else:
         statements = model.statements.after_odes
     add_statements(
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/nlmixr/model_block.py` & `pharmpy-core-0.97.0/src/pharmpy/model/external/nlmixr/model_block.py`

 * *Files 5% similar despite different names*

```diff
@@ -138,23 +138,25 @@
 
                             if s.symbol in dependencies:
                                 if not value.is_constant() and not isinstance(value, sympy.Symbol):
                                     add, prop = extract_add_prop(value, res_alias, model)
                                     cg.add(f'add_error <- {add}')
                                     cg.add(f'prop_error <- {prop}')
                         elif s.symbol == dv:
-                            if not value.is_constant() and not isinstance(value, sympy.Symbol):
+                            if value != dv:
                                 t = res_error_term(model, value)
                                 # FIXME : Remove sigma here instead of in ini
                                 # also remove aliases for sigma
                                 cg.add(f"res <- {t.res}")
                                 cg.add(f'add_error <- {t.add.expr}')
                                 cg.add(f'prop_error <- {t.prop.expr}')
                             else:
-                                cg.add(f'{s.symbol.name} <- {value}')
+                                cg.add("res <- res")
+                                cg.add('add_error <- add_error')
+                                cg.add('prop_error <- prop_error')
                         else:
                             cg.add(f'{s.symbol.name} <- {value}')
 
                         cg.dedent()
                     cg.add('}')
                 elif s.symbol in dependencies:
                     add, prop = extract_add_prop(s.expression, res_alias, model)
@@ -202,53 +204,88 @@
         terms = [s]
     elif isinstance(s, sympy.Float):
         terms = [s]
     else:
         terms = sympy.Add.make_args(s.expression)
     assert len(terms) <= 2
 
-    r = r"sqrt\([a-zA-Z0-9_.-]*\*\*2\*[a-zA-Z0-9_.-]*\*\*2 \+ [a-zA-Z0-9_.-]*\*\*2\)"
-    if re.match(r, str(s)):
-        w = True
-    else:
-        w = False
+    w = False
+
+    if isinstance(s, sympy.Pow):
+        s_arg = sympy.Add.make_args(s.args[0])
+        if len(s_arg) <= 2:
+            all_pow = True
+            for t in s_arg:
+                for f in sympy.Mul.make_args(t):
+                    if (
+                        isinstance(f, sympy.Pow)
+                        or isinstance(f, sympy.Integer)
+                        or isinstance(f, sympy.Float)
+                    ):
+                        pass
+                    else:
+                        all_pow = False
+        if all_pow:
+            w = True
 
     prop = 0
     add = 0
     prop_found = False
     for term in terms:
         for symbol in term.free_symbols:
             if symbol in res_alias:
                 if prop_found is False:
                     term = term.subs(symbol, 1)
                     if w:
-                        prop = list(term.free_symbols)[0]
+                        prop = sympy.sqrt(term)
                     else:
-                        add = term
+                        prop += term
                     prop_found = True
         if prop_found is False:
             if w:
-                add = list(term.free_symbols)[0]
+                add = sympy.sqrt(term)
             else:
-                add = term
+                add += term
     return add, prop
 
 
-def add_bioavailability(model: pharmpy.model.Model, cg: CodeGenerator):
-    bio = get_bioavailability(model)
-    for comp, symbol in bio.items():
-        symbol_value = model.statements.find_assignment(symbol).expression
-        cg.add(f'f(A_{comp}) <- {symbol_value}')
+def add_bio_lag(model: pharmpy.model.Model, cg: CodeGenerator, bio=False, lag=False):
+    if bio:
+        bio_lag = get_bioavailability(model)
+    elif lag:
+        bio_lag = get_lag_times(model)
+    else:
+        return
 
+    for s in model.statements.before_odes:
+        if s.symbol in bio_lag.values():
+            comp = list(bio_lag.keys())[list(bio_lag.values()).index(s.symbol)]
+
+            if s.expression.is_Piecewise:
+                first = True
+                for value, cond in s.expression.args:
+                    if cond is not sympy.S.true:
+                        cond = convert_eq(cond)
+                        if first:
+                            cg.add(f'if ({cond}) {{')
+                            first = False
+                        else:
+                            cg.add(f'}} else if ({cond}) {{')
+                    else:
+                        cg.add('} else {')
 
-def add_lag_times(model: pharmpy.model.Model, cg: CodeGenerator):
-    lag = get_lag_times(model)
-    for comp, symbol in lag.items():
-        symbol_value = model.statements.find_assignment(symbol).expression
-        cg.add(f'alag(A_{comp}) <- {symbol_value}')
+                    if bio:
+                        cg.add(f'f(A_{comp}) <- {value}')
+                    elif lag:
+                        cg.add(f'alag(A_{comp}) <- {value}')
+            else:
+                if bio:
+                    cg.add(f'f(A_{comp}) <- {s.expression}')
+                elif lag:
+                    cg.add(f'alag(A_{comp}) <- {s.expression}')
 
 
 def add_piecewise(model: pharmpy.model.Model, cg: CodeGenerator, s):
     expr = s.expression
     first = True
     for value, cond in expr.args:
         if cond is not sympy.S.true:
@@ -427,22 +464,23 @@
     -------
     str
         A string with R format for the same statement
 
     """
     cond = sympy.pretty(cond)
     cond = cond.replace("=", "==")
+    cond = cond.replace("≠", "!=")
     cond = cond.replace("≤", "<=")
     cond = cond.replace("≥", "<=")
     cond = cond.replace("∧", "&")
     cond = cond.replace("∨", "|")
 
     cond = re.sub(r'(ID\s*==\s*)(\d+)', r"\1'\2'", cond)
 
     if (
         re.search(r'(ID\s*<=\s*)(\d+)', cond)
         or re.search(r'(ID\s*>=\s*)(\d+)', cond)
         or re.search(r'(ID\s*<\s*)(\d+)', cond)
         or re.search(r'(ID\s*>\s*)(\d+)', cond)
     ):
-        raise ValueError(f"Condition '{cond}' not supported by nlmixr")
+        print(f"Condition '{cond}' not supported by nlmixr. Model will not run.")
     return cond
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/nlmixr/sanity_checks.py` & `pharmpy-core-0.97.0/src/pharmpy/model/external/nlmixr/sanity_checks.py`

 * *Files 6% similar despite different names*

```diff
@@ -38,43 +38,58 @@
         Issues will be printed to the terminal and model is returned.
 
     """
 
     # Checks for the dataset
     if model.dataset is not None:
         if "TIME" in model.dataset.columns:
+            # Forcefully change so that doses and observation dont happen
+            # at the same time
             if same_time(model):
                 print_warning(
                     "Observation and bolus dose at the same time in the data. Modified for nlmixr model"
                 )
                 model = change_same_time(model)
+        else:
+            # Add placeholder time to be able to run model
+            print_warning(
+                "TIME column required to run model. Added time with zero value for all events"
+            )
+            model = add_time(model)
 
     # Checks regarding error model
     if not skip_error_model_check:
         if not known_error_model(model):
             print_warning("Format of error model cannot be determined.")
 
     # Checks regarding random variables
     if rvs_same(model, sigma=True):
-        print_warning("Sigma with value same not supported. Updated as follows.")
+        print_warning("Sigma with value same not supported. Parameters are updated")
         model = change_rvs_same(model, sigma=True)
     if rvs_same(model, omega=True):
-        print_warning("Omega with value same not supported. Updated as follows.")
+        print_warning("Omega with value same not supported. Parameters are updated")
         model = change_rvs_same(model, omega=True)
 
     # Checks regarding esimation method
     method = model.estimation_steps[0].method
     if not known_estimation_method(method):
         print_warning(
             f"Estimation method {method} unknown to nlmixr2. Using 'FOCEI' as placeholder"
         )
 
     return model
 
 
+def add_time(model):
+    dataset = model.dataset
+    dataset["TIME"] = 0
+    model = model.replace(dataset=dataset)
+    return model
+
+
 def known_estimation_method(method):
     nonmem_method_to_nlmixr = {"FOCE": "foce", "FO": "fo", "SAEM": "saem"}
     if method in nonmem_method_to_nlmixr.keys():
         return True
     else:
         return False
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/advan.py` & `pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/advan.py`

 * *Files 1% similar despite different names*

```diff
@@ -279,14 +279,15 @@
         rec_model = control_stream.get_records('MODEL')[0]
 
         subs_dict, comp_names = {}, {}
         comps = [c for c, _ in rec_model.compartments()]
         func_to_name = {}
 
         t = sympy.Symbol('t')
+        subs_dict['T'] = t
         for i, c in enumerate(comps, 1):
             a = sympy.Function(f'A_{c}')
             subs_dict[f'DADT({i})'] = sympy.Derivative(a(t))
             subs_dict[f'DADT ({i})'] = sympy.Derivative(a(t))
             subs_dict[f'A({i})'] = a(t)
             comp_names[f'A({i})'] = a
             func_to_name[a] = c
@@ -337,15 +338,15 @@
         comps = [c for c, _ in rec_model.compartments()]
         func_to_name = {}
         t = sympy.Symbol('t')
         for i, c in enumerate(comps, 1):
             a = sympy.Function(f'A_{c}')
             subs_dict[f'DADT({i})'] = sympy.Derivative(a(t))
             subs_dict[f'DADT ({i})'] = sympy.Derivative(a(t))
-            subs_dict[f'A({i})'] = str(a)
+            subs_dict[f'A({i})'] = a(t)
             comp_names[f'A({i})'] = a
             func_to_name[a] = c
 
         sset = des.statements.subs(subs_dict)
 
         statements = [sympy.Eq(s.symbol, s.expression) for s in sset if s.symbol.is_Symbol]
         if len(statements) == 0:
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/dataset.py` & `pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/dataset.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/model.py` & `pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/model.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/nmtran_parser.py` & `pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/nmtran_parser.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/parsing.py` & `pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/parsing.py`

 * *Files 1% similar despite different names*

```diff
@@ -247,20 +247,25 @@
         else:
             cm, link, comp_map = comp
             statements += [cm, link]
             if des:
                 rec_model = control_stream.get_records('MODEL')[0]
                 comps = [c for c, _ in rec_model.compartments()]
                 for i, c in enumerate(comps, 1):
-                    trans_amounts[sympy.Symbol(f"A({i})")] = f'A_{c}'
+                    trans_amounts[sympy.Symbol(f"A({i})")] = sympy.Function(f'A_{c}')(
+                        sympy.Symbol('t')
+                    )
                     trans_amounts[sympy.Symbol(f"A_0({i})")] = sympy.Function(f'A_{c}')(0)
             else:
                 for i, amount in enumerate(cm.amounts, start=1):
-                    trans_amounts[sympy.Symbol(f"A({i})")] = amount
+                    trans_amounts[sympy.Symbol(f"A({i})")] = sympy.Function(amount.name)(
+                        sympy.Symbol('t')
+                    )
                     trans_amounts[sympy.Symbol(f"A_0({i})")] = sympy.Function(amount.name)(0)
+
         statements += error.statements
         if trans_amounts:
             statements = statements.subs(trans_amounts)
 
     return statements, comp_map
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/abbreviated_record.py` & `pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/abbreviated_record.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/code_record.py` & `pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/code_record.py`

 * *Files 1% similar despite different names*

```diff
@@ -574,20 +574,22 @@
     def _statement_to_nodes(self, defined_symbols: Set[sympy.Symbol], s: Assignment, rvs, trans):
         statement_str = nmtran_assignment_string(s, defined_symbols, rvs, trans) + '\n'
         node_tree = CodeRecordParser(statement_str).root
         assert node_tree is not None
         statement_nodes = list(node_tree.subtrees('statement'))
         return statement_nodes
 
-    def from_odes(self, ode_system):
-        """Set statements of record given an explicit ode system"""
+    def from_odes(self, ode_system, extra):
+        """Set statements of record given an explicit ode system
+        extra statements are added to the top
+        """
         odes = ode_system.eqs
         functions = [ode.lhs.args[0] for ode in odes]
         function_map = {f: sympy.Symbol(f'A({i + 1})') for i, f in enumerate(functions)}
-        statements = []
+        statements = [s.subs(function_map) for s in extra]
         for i, ode in enumerate(odes):
             # For now Piecewise signals zero-order infusions, which are handled with parameters
             ode = ode.replace(sympy.Piecewise, lambda a1, a2: 0)
             symbol = sympy.Symbol(f'DADT({i + 1})')
             expression = subs(ode.rhs, function_map, simultaneous=True)
             statements.append(Assignment(symbol, expression))
         return self.update_statements(statements)
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/data_record.py` & `pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/data_record.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/factory.py` & `pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/factory.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/grammars/abbreviated_record.lark` & `pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/grammars/abbreviated_record.lark`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/grammars/code_record.lark` & `pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/grammars/code_record.lark`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/grammars/data_record.lark` & `pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/grammars/data_record.lark`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/grammars/omega_record.lark` & `pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/grammars/omega_record.lark`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/grammars/simulation_record.lark` & `pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/grammars/simulation_record.lark`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/grammars/theta_record.lark` & `pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/grammars/theta_record.lark`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/model_record.py` & `pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/model_record.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/omega_record.py` & `pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/omega_record.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/option_record.py` & `pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/option_record.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/parsers.py` & `pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/parsers.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/problem_record.py` & `pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/problem_record.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/record.py` & `pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/record.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/sizes_record.py` & `pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/sizes_record.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/subroutine_record.py` & `pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/subroutine_record.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/table_record.py` & `pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/table_record.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/records/theta_record.py` & `pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/records/theta_record.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/table.py` & `pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/table.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/nonmem/update.py` & `pharmpy-core-0.97.0/src/pharmpy/model/external/nonmem/update.py`

 * *Files 1% similar despite different names*

```diff
@@ -509,15 +509,21 @@
         newrec = subs.append_option('ADVAN13')
     if not subs.has_option('TOL'):
         newrec = newrec.append_option('TOL', '9')
     cs = cs.replace_records([subs], [newrec])
     des = create_record('$DES\nDUMMY=0\n')
     cs = cs.insert_record(des)
     assert isinstance(des, CodeRecord)
-    newdes = des.from_odes(new)
+
+    to_odes = []
+    for s in model.statements.before_odes:
+        if model.statements.ode_system.t in s.free_symbols:
+            to_odes.append(s)
+
+    newdes = des.from_odes(new, to_odes)
     cs = cs.replace_records([des], [newdes])
     cs = cs.remove_records(model.internals.control_stream.get_records('MODEL'))
     mod = create_record('$MODEL\n')
     cs = cs.insert_record(mod)
     old_mod = mod
     assert isinstance(mod, ModelRecord)
     dosecmt_name = new.dosing_compartment.name
@@ -588,14 +594,21 @@
                     newsubs = subs.set_advan(advan)
                     newcs = model.internals.control_stream.replace_records([subs], [newsubs])
                     model = model.replace(internals=model.internals.replace(control_stream=newcs))
                     model = update_model_record(model, advan)
 
     main_statements = model.statements.before_odes
     main_statements = update_ics(main_statements, new_odes)
+    if model.statements.ode_system is not None:
+        keep = []
+        for s in main_statements:
+            if model.statements.ode_system.t not in s.free_symbols:
+                keep.append(s)
+        main_statements = Statements(tuple(keep))
+
     error_statements = model.statements.after_odes
 
     rec = model.internals.control_stream.get_pred_pk_record()
     newrec = rec.update_statements(main_statements.subs(trans), model.random_variables, trans)
     newcs = model.internals.control_stream.replace_records([rec], [newrec])
     model = model.replace(internals=model.internals.replace(control_stream=newcs))
 
@@ -610,14 +623,15 @@
                 error_statements = error_statements[0:i] + error_statements[i + 1 :]
                 break
         new_ode_system = new.ode_system
         if new_ode_system is not None:
             amounts = list(new_ode_system.amounts)
             for i, amount in enumerate(amounts, start=1):
                 trans[amount] = sympy.Symbol(f"A({i})")
+                trans[sympy.Function(amount.name)(new_ode_system.t)] = sympy.Symbol(f"A({i})")
         new_error = error.update_statements(
             error_statements.subs(trans), model.random_variables, trans
         )
         new_error = new_error.update_extra_nodes(model.dependent_variables)
         newcs = model.internals.control_stream.replace_records([error], [new_error])
         model = model.replace(internals=model.internals.replace(control_stream=newcs))
     return model, updated_dataset
@@ -888,19 +902,20 @@
                         sympy.Symbol('K23'): sympy.Symbol('K12'),
                         sympy.Symbol('K32'): sympy.Symbol('K21'),
                         sympy.Symbol('K24'): sympy.Symbol('K13'),
                         sympy.Symbol('K42'): sympy.Symbol('K31'),
                     }
                 )
     if advan == 'ADVAN5' or advan == 'ADVAN7':
+        n = newmap['CENTRAL']
         if from_advan not in ('ADVAN5', 'ADVAN7'):
-            n = len(newmap)
-            d[sympy.Symbol('K')] = sympy.Symbol(f'K{n-1}0')
+            d[sympy.Symbol('K')] = sympy.Symbol(f'K{n}0')
         else:
-            d[sympy.Symbol(f'K{len(oldmap)-1}0')] = sympy.Symbol(f'K{len(newmap)-1}0')
+            n_old = oldmap['CENTRAL']
+            d[sympy.Symbol(f'K{n_old}0')] = sympy.Symbol(f'K{n}0')
     model = model.replace(statements=statements.subs(d))
     return model
 
 
 def match_advan1(odes):
     return len(odes) == 1
 
@@ -1098,19 +1113,19 @@
     return model
 
 
 def update_model_record(model: Model, advan):
     """Update $MODEL"""
     odes = model.statements.ode_system
     if not isinstance(odes, CompartmentalSystem):
-        return
+        return model
 
     oldmap = model.internals.compartment_map
     if oldmap is None:
-        return
+        return model
     newmap = new_compartmental_map(odes)
 
     replace_dict = {'compartment_map': newmap}
 
     if advan in ['ADVAN1', 'ADVAN2', 'ADVAN3', 'ADVAN4', 'ADVAN10', 'ADVAN11', 'ADVAN12']:
         newcs = model.internals.control_stream.remove_records(
             model.internals.control_stream.get_records('MODEL')
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/rxode/model.py` & `pharmpy-core-0.97.0/src/pharmpy/model/external/rxode/model.py`

 * *Files 3% similar despite different names*

```diff
@@ -3,20 +3,15 @@
 from typing import Optional
 
 import pharmpy.model
 from pharmpy.deps import sympy
 from pharmpy.internals.code_generator import CodeGenerator
 from pharmpy.model.external.nlmixr.error_model import convert_eps_to_sigma
 from pharmpy.model.external.nlmixr.model import add_evid
-from pharmpy.model.external.nlmixr.model_block import (
-    add_bioavailability,
-    add_lag_times,
-    add_ode,
-    convert_eq,
-)
+from pharmpy.model.external.nlmixr.model_block import add_bio_lag, add_ode, convert_eq
 from pharmpy.modeling import (
     drop_columns,
     get_bioavailability,
     get_lag_times,
     get_thetas,
     translate_nmtran_time,
 )
@@ -110,16 +105,16 @@
     add_true_statements(model, cg, model.statements.before_odes)
 
     if model.statements.ode_system:
         add_ode(model, cg)
 
     # Add bioavailability statements
     if model.statements.ode_system is not None:
-        add_bioavailability(model, cg)
-        add_lag_times(model, cg)
+        add_bio_lag(model, cg, bio=True)
+        add_bio_lag(model, cg, lag=True)
 
     # Add statements after ODE
     add_true_statements(model, cg, model.statements.after_odes)
 
 
 def add_true_statements(model, cg, statements):
     for s in statements:
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/external/utils.py` & `pharmpy-core-0.97.0/src/pharmpy/model/external/utils.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/model.py` & `pharmpy-core-0.97.0/src/pharmpy/model/model.py`

 * *Files 15% similar despite different names*

```diff
@@ -8,17 +8,19 @@
 Inherit to *implement*, i.e. to define support for a specific model type.
 
 Definitions
 -----------
 """
 from __future__ import annotations
 
+import json
 import warnings
 from pathlib import Path
 
+import pharmpy
 from pharmpy.deps import pandas as pd
 from pharmpy.deps import sympy
 from pharmpy.internals.immutable import Immutable, frozenmapping
 from pharmpy.model.external import detect_model
 
 from .datainfo import ColumnInfo, DataInfo
 from .estimation import EstimationSteps
@@ -184,14 +186,16 @@
     def _canonicalize_statements(statements, params, rvs, datainfo):
         if statements is None:
             return Statements()
         if not isinstance(statements, Statements):
             raise TypeError("model.statements must be of Statements type")
         colnames = {sympy.Symbol(colname) for colname in datainfo.names}
         symbs_all = rvs.free_symbols.union(params.symbols).union(colnames)
+        if statements.ode_system is not None:
+            symbs_all = symbs_all.union({statements.ode_system.t})
         sset_prev = []
         for i, statement in enumerate(statements):
             if isinstance(statement, ODESystem):
                 continue
 
             symbs = statement.expression.free_symbols
             if not symbs.issubset(symbs_all):
@@ -391,16 +395,22 @@
             return False
         if self.dependent_variables != other.dependent_variables:
             return False
         if self.observation_transformation != other.observation_transformation:
             return False
         if self.estimation_steps != other.estimation_steps:
             return False
-        if self.initial_individual_estimates != other.initial_individual_estimates:
-            return False
+        if self.initial_individual_estimates is None:
+            if other.initial_individual_estimates is not None:
+                return False
+        else:
+            if other.initial_individual_estimates is None:
+                return False
+            elif not self.initial_individual_estimates.equals(other.initial_individual_estimates):
+                return False
         if self.datainfo != other.datainfo:
             return False
         if self.value_type != other.value_type:
             return False
 
         return True
 
@@ -415,14 +425,60 @@
                 self._estimation_steps,
                 self._initial_individual_estimates,
                 self._datainfo,
                 self._value_type,
             )
         )
 
+    def to_dict(self):
+        if self._initial_individual_estimates is not None:
+            ie = self._initial_individual_estimates.to_dict()
+        else:
+            ie = None
+        depvars = {str(key): val for key, val in self._dependent_variables.items()}
+        obstrans = {
+            sympy.srepr(key): sympy.srepr(val)
+            for key, val in self._observation_transformation.items()
+        }
+        return {
+            'parameters': self._parameters.to_dict(),
+            'random_variables': self._random_variables.to_dict(),
+            'statements': self._statements.to_dict(),
+            'estimation_steps': self._estimation_steps.to_dict(),
+            'datainfo': self._datainfo.to_dict(),
+            'value_type': self._value_type,
+            'dependent_variables': depvars,
+            'observation_transformation': obstrans,
+            'initial_individual_estimates': ie,
+        }
+
+    @classmethod
+    def from_dict(cls, d):
+        ie_dict = d['initial_individual_estimates']
+        if ie_dict is None:
+            ie = None
+        else:
+            ie = pd.DataFrame.from_dict(ie_dict)
+        depvars = {sympy.Symbol(key): value for key, value in d['dependent_variables'].items()}
+        obstrans = {
+            sympy.parse_expr(key): sympy.parse_expr(val)
+            for key, val in d['observation_transformation'].items()
+        }
+        return cls(
+            parameters=Parameters.from_dict(d['parameters']),
+            random_variables=RandomVariables.from_dict(d['random_variables']),
+            statements=Statements.from_dict(d['statements']),
+            estimation_steps=EstimationSteps.from_dict(d['estimation_steps']),
+            datainfo=DataInfo.from_dict(d['datainfo']),
+            value_type=d['value_type'],
+            dependent_variables=frozenmapping(depvars),
+            observation_transformation=frozenmapping(obstrans),
+            initial_individual_estimates=ie,
+        )
+
     def __repr__(self):
         return f'<Pharmpy model object {self.name}>'
 
     def _repr_html_(self):
         stat = self.statements._repr_html_()
         rvs = self.random_variables._repr_latex_()
         return f'<hr>{stat}<hr>${rvs}$<hr>{self.parameters._repr_html_()}<hr>'
@@ -518,15 +574,18 @@
     def modelfit_results(self):
         """Modelfit results for this model"""
         return self._modelfit_results
 
     @property
     def model_code(self):
         """Model type specific code"""
-        raise NotImplementedError("Generic model does not implement the model_code property")
+        d = self.to_dict()
+        d['__magic__'] = "Pharmpy Model"
+        d['__version__'] = pharmpy.__version__
+        return json.dumps(d)
 
     @property
     def parent_model(self):
         """Name of parent model"""
         return self._parent_model
 
     def has_same_dataset_as(self, other):
@@ -601,17 +660,15 @@
 
     def update_source(self):
         """Update source code of the model. If any paths need to be changed or added (e.g. for a
         NONMEM model with an updated dataset) they will be replaced with DUMMYPATH"""
         return self
 
     def write_files(self, path=None, force=False):
-        """Write necessary files of the model. If any paths need to be changed or added (e.g. for a
-        NONMEM model with an updated dataset) they will be replaced with the correct path. update_source()
-        will be called first."""
+        """Write all extra files needed for a specific external format."""
         return self
 
 
 def compare_before_after_params(old, new):
     # FIXME Move this to the right module
     before = {}
     after = {}
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/parameters.py` & `pharmpy-core-0.97.0/src/pharmpy/model/parameters.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/random_variables.py` & `pharmpy-core-0.97.0/src/pharmpy/model/random_variables.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/results.py` & `pharmpy-core-0.97.0/src/pharmpy/model/results.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/model/statements.py` & `pharmpy-core-0.97.0/src/pharmpy/model/statements.py`

 * *Files 1% similar despite different names*

```diff
@@ -11,14 +11,21 @@
 from pharmpy.internals.expr.leaves import free_images, free_images_and_symbols
 from pharmpy.internals.expr.ode import canonical_ode_rhs
 from pharmpy.internals.expr.parse import parse as parse_expr
 from pharmpy.internals.expr.subs import subs
 from pharmpy.internals.immutable import Immutable
 
 
+def is_zero_matrix(A):
+    for e in A:
+        if not e.is_zero:
+            return False
+    return True
+
+
 class Statement(Immutable):
     """Abstract base class for all types of statements"""
 
     def __add__(self, other):
         if isinstance(other, Statements):
             return Statements((self,) + other._statements)
         elif isinstance(other, Statement):
@@ -427,15 +434,15 @@
 
 
 def _comps(graph):
     return {comp for comp in graph.nodes if not isinstance(comp, Output)}
 
 
 def to_compartmental_system(names, eqs):
-    """Convert an list of odes to a compartmenal system
+    """Convert an list of odes to a compartmental system
 
     names : func to compartment name map
     """
 
     cb = CompartmentalSystemBuilder()
     compartments = {}
     concentrations = set()
@@ -492,26 +499,27 @@
                         for i, neweq in enumerate(neweqs):
                             if neweq.lhs.args[0].name == eq.lhs.args[0].name:
                                 neweqs[i] = sympy.Eq(neweq.lhs, sympy.expand(neweq.rhs - term))
                             elif neweq.lhs.args[0].name == comp_func.name:
                                 neweqs[i] = sympy.Eq(neweq.lhs, sympy.expand(neweq.rhs + term))
     for eq in neweqs:
         if eq.rhs != 0:
-            i = sympy.Add(0)
-            o = sympy.Add(0)
+            i = sympy.Integer(0)
+            o = sympy.Integer(0)
             for term in sympy.Add.make_args(eq.rhs):
                 if _is_positive(term):
                     i = i + term
                 else:
                     o = o + term
-
             comp_func = eq.lhs.args[0]
             from_comp = compartments[names[comp_func.func]]
-            cb.add_flow(from_comp, output, -o / comp_func)
-            cb.set_input(from_comp, i)
+            if o != 0:
+                cb.add_flow(from_comp, output, -o / comp_func)
+            if i != 0:
+                cb.set_input(from_comp, i)
     cs = CompartmentalSystem(cb)
     return cs
 
 
 class CompartmentalSystem(ODESystem):
     """System of ODEs descibed as a compartmental system
 
@@ -1202,24 +1210,32 @@
                 if comp not in bidirects and comp != output:
                     current = comp
                     break
             else:
                 break
 
         noutput = len(self.get_compartment_inflows(output))
-        nrows = comp_height * 2 - 1 + (1 if noutput > 1 else 0)
+        have_zo_input = int(not is_zero_matrix(self.zero_order_inputs))
+        comp_nrows = comp_height * 2 - 1 + (1 if noutput > 1 else 0)
+        nrows = comp_nrows + have_zo_input
         ncols = comp_width * 2
         grid = unicode.Grid(nrows, ncols)
 
         current = self.dosing_compartment
         col = 0
-        if nrows == 1 or nrows == 2:
-            main_row = 0
+        if comp_nrows == 1 or comp_nrows == 2:
+            main_row = 0 + have_zo_input
         else:
-            main_row = 2
+            main_row = 2 + have_zo_input
+
+        if have_zo_input:
+            # Assuming a fully linear layout
+            for i, zo in enumerate(self.zero_order_inputs):
+                if zo != 0:
+                    grid.set(0, i * 2, unicode.VerticalArrow(str(zo)))
 
         while True:
             bidirects = self.get_bidirectionals(current)
             outflows = self.get_compartment_outflows(current)
             comp_box = unicode.Box(comp_string(current))
             grid.set(main_row, col, comp_box)
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/__init__.py` & `pharmpy-core-0.97.0/src/pharmpy/modeling/__init__.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,10 +1,9 @@
 from .allometry import add_allometry
 from .basic_models import create_basic_pk_model
-from .block_rvs import create_joint_distribution, split_joint_distribution
 from .blq import transform_blq
 from .common import (
     bump_model_number,
     convert_model,
     create_config_template,
     get_config_path,
     get_model_code,
@@ -71,20 +70,14 @@
     add_estimation_step,
     append_estimation_step_options,
     remove_covariance_step,
     remove_estimation_step,
     set_estimation_step,
     set_evaluation_step,
 )
-from .eta_additions import add_iiv, add_iov, add_pk_iiv
-from .eta_transformations import (
-    transform_etas_boxcox,
-    transform_etas_john_draper,
-    transform_etas_tdist,
-)
 from .evaluation import (
     evaluate_epsilon_gradient,
     evaluate_eta_gradient,
     evaluate_expression,
     evaluate_individual_prediction,
     evaluate_population_prediction,
     evaluate_weighted_residuals,
@@ -157,57 +150,71 @@
 )
 from .parameter_sampling import (
     create_rng,
     sample_individual_estimates,
     sample_parameters_from_covariance_matrix,
     sample_parameters_uniformly,
 )
+from .parameter_variability import (
+    add_iiv,
+    add_iov,
+    add_pk_iiv,
+    create_joint_distribution,
+    remove_iiv,
+    remove_iov,
+    split_joint_distribution,
+    transform_etas_boxcox,
+    transform_etas_john_draper,
+    transform_etas_tdist,
+    update_initial_individual_estimates,
+)
 from .parameters import (
     add_population_parameter,
     fix_or_unfix_parameters,
     fix_parameters,
     fix_parameters_to,
     get_omegas,
     get_sigmas,
     get_thetas,
     set_initial_estimates,
     set_lower_bounds,
     set_upper_bounds,
     unconstrain_parameters,
     unfix_parameters,
     unfix_parameters_to,
+    update_inits,
 )
+from .pd import add_effect_compartment, set_direct_effect
 from .plots import (
     plot_individual_predictions,
     plot_iofv_vs_iofv,
     plot_transformed_eta_distributions,
 )
-from .remove_iiv import remove_iiv
-from .remove_iov import remove_iov
 from .results import (
     calculate_aic,
     calculate_bic,
     calculate_eta_shrinkage,
     calculate_individual_parameter_statistics,
     calculate_individual_shrinkage,
     calculate_pk_parameters_statistics,
     check_high_correlations,
     check_parameters_near_bounds,
 )
 from .tmdd import set_tmdd
 from .units import get_unit_of
-from .update_inits import update_initial_individual_estimates, update_inits
 from .write_csv import write_csv
 
 # Must be set directly, otherwise errors about unused imports
 __all__ = [
+    'set_direct_effect',
     'add_allometry',
     'add_covariance_step',
     'add_covariate_effect',
     'add_estimation_step',
+    'add_effect_compartment',
     'add_iiv',
     'add_individual_parameter',
     'add_iov',
     'add_lag_time',
     'add_metabolite',
     'add_peripheral_compartment',
     'add_pk_iiv',
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/allometry.py` & `pharmpy-core-0.97.0/src/pharmpy/modeling/allometry.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/basic_models.py` & `pharmpy-core-0.97.0/src/pharmpy/modeling/basic_models.py`

 * *Files 6% similar despite different names*

```diff
@@ -23,19 +23,18 @@
     Parameter,
     Parameters,
     RandomVariables,
     Statements,
     output,
 )
 
-from .block_rvs import create_joint_distribution
 from .data import read_dataset_from_datainfo
 from .error import set_proportional_error_model
-from .eta_additions import add_iiv
 from .odes import set_first_order_absorption
+from .parameter_variability import add_iiv, create_joint_distribution
 from .parameters import set_initial_estimates
 
 
 def create_basic_pk_model(
     modeltype: str,
     dataset_path: Optional[str] = None,
     cl_init: float = 0.01,
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/blq.py` & `pharmpy-core-0.97.0/src/pharmpy/modeling/blq.py`

 * *Files 3% similar despite different names*

```diff
@@ -4,15 +4,15 @@
 from typing import Optional
 
 from pharmpy.deps import sympy
 from pharmpy.internals.expr.funcs import PHI
 from pharmpy.model import Assignment, EstimationSteps, JointNormalDistribution, Model
 
 from .data import remove_loq_data
-from .expressions import create_symbol, simplify_expression
+from .expressions import _simplify_expression_from_parameters, create_symbol
 
 SUPPORTED_METHODS = frozenset(['m1', 'm3', 'm4'])
 
 
 def transform_blq(model: Model, method: str = 'm4', lloq: Optional[float] = None):
     """Transform for BLQ data
 
@@ -178,26 +178,28 @@
         raise ValueError(
             f'Invalid input model: covariance between epsilons not supported in `method` {method}'
         )
 
 
 def _get_sd(model, y):
     y_expr = model.statements.find_assignment(y.symbol).expression
-    sd_expr = get_sd_expr(y_expr, model.random_variables)
+    sd_expr = get_sd_expr(y_expr, model.random_variables, model.parameters)
     symb_sd = create_symbol(model, 'SD')
-    return Assignment(symb_sd, simplify_expression(model, sd_expr))
+    return Assignment(symb_sd, sd_expr)
 
 
-def get_sd_expr(y_expr, rvs):
+def get_sd_expr(y_expr, rvs, params):
     rv_terms = [arg for arg in y_expr.args if arg.free_symbols.intersection(rvs.free_symbols)]
     sd_expr = []
     for i, term in enumerate(rv_terms, 1):
         rvs_in_term = rvs.free_symbols.intersection(term.free_symbols)
         if len(rvs_in_term) > 1:
             raise ValueError(
                 'Invalid input model: error model not supported, terms in error model cannot contain '
                 'more than one random variable'
             )
         expr = rvs.replace_with_sympy_rvs(term)
         sd_expr.append(sympy.stats.std(expr))
 
-    return sympy.sqrt(sympy.Add(*[expr**2 for expr in sd_expr]))
+    return _simplify_expression_from_parameters(
+        sympy.sqrt(sympy.Add(*[expr**2 for expr in sd_expr])), params
+    )
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/common.py` & `pharmpy-core-0.97.0/src/pharmpy/modeling/common.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,12 @@
 """Common modeling pipeline elements
 :meta private:
 """
 
+import importlib
 import re
 import warnings
 from pathlib import Path
 from typing import Dict, Union
 
 import pharmpy.config as config
 from pharmpy.deps import sympy
@@ -162,45 +163,17 @@
     >>> model = load_example_model("pheno")
     >>> converted_model = convert_model(model, "nlmixr")    # doctest: +SKIP
 
     """
     supported = ['generic', 'nlmixr', 'nonmem', 'rxode']
     if to_format not in supported:
         raise ValueError(f"Unknown format {to_format}: supported formats are f{supported}")
-    # FIXME: Use code that can discover plugins below
-    if to_format == 'generic':
-        new = Model()
-        new = new.replace(
-            dataset=model.dataset,
-            datainfo=model.datainfo,
-            name=model.name,
-            parameters=model.parameters,
-            statements=model.statements,
-            random_variables=model.random_variables,
-            estimation_steps=model.estimation_steps,
-            dependent_variables=model.dependent_variables,
-            observation_transformation=model.observation_transformation,
-            description=model.description,
-            parent_model=model.name,
-            filename_extension=model.filename_extension,
-            initial_individual_estimates=model.initial_individual_estimates,
-        )
-        return new
-    elif to_format == 'nlmixr':
-        import pharmpy.model.external.nlmixr.model as nlmixr
-
-        new = nlmixr.convert_model(model)
-    elif to_format == 'rxode':
-        import pharmpy.model.external.rxode.model as rxode
-
-        new = rxode.convert_model(model)
-    else:
-        import pharmpy.model.external.nonmem.model as nonmem
-
-        new = nonmem.convert_model(model)
+    module_name = 'pharmpy.model.external.' + to_format
+    module = importlib.import_module(module_name)
+    new = module.convert_model(model)
     return new
 
 
 def get_model_code(model: Model):
     """Get the model code of the underlying model language
 
     Parameters
@@ -531,19 +504,19 @@
     -------
     >>> from pharmpy.modeling import get_config_path
     >>> get_config_path()  # doctest: +SKIP
     """
     if config.user_config_file_enabled():
         env_path = config.env_config_path()
         if env_path is not None:
-            return str(env_path)
+            return str(env_path.resolve())
         else:
             config_path = config.user_config_path()
             if config_path.exists():
-                return str(config_path)
+                return str(config_path.resolve())
             else:
                 warnings.warn(f'Cannot find config path {config_path}')
                 return None
     else:
         warnings.warn('User config file is disabled')
         return None
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/compartments.py` & `pharmpy-core-0.97.0/src/pharmpy/modeling/compartments.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/covariate_effect.py` & `pharmpy-core-0.97.0/src/pharmpy/modeling/covariate_effect.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/data.py` & `pharmpy-core-0.97.0/src/pharmpy/modeling/data.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/error.py` & `pharmpy-core-0.97.0/src/pharmpy/modeling/error.py`

 * *Files 1% similar despite different names*

```diff
@@ -9,15 +9,15 @@
 from pharmpy.internals.expr.parse import parse as parse_expr
 from pharmpy.internals.expr.subs import subs
 from pharmpy.model import Assignment, Model, NormalDistribution, Parameter, Parameters, Statements
 
 from .blq import get_blq_symb_and_type, get_sd_expr, has_blq_transformation
 from .common import _get_unused_parameters_and_rvs, remove_unused_parameters_and_rvs
 from .data import get_observations
-from .expressions import _create_symbol, create_symbol, get_dv_symbol, simplify_expression
+from .expressions import _create_symbol, create_symbol, get_dv_symbol
 from .help_functions import _format_input_list, _get_epsilons
 from .parameters import add_population_parameter, fix_parameters, set_initial_estimates
 
 
 def _preparations(model, y=None):
     stats = model.statements
     # FIXME: handle other DVs?
@@ -278,15 +278,15 @@
         error_expr = sympy.log(ipred) + ruv if zero_protection else sympy.log(f_dummy) + ruv
     elif data_trans == dv:
         error_expr = f_dummy + ipred * ruv if zero_protection else f_dummy + f_dummy * ruv
     else:
         raise ValueError(f"Not supported data transformation {data_trans}")
 
     if has_blq_transformation(model):
-        f, stats_new = _get_updated_blq_statements(model, error_expr, y, f, f_dummy, eps)
+        f, stats_new = _get_updated_blq_statements(model, error_expr, f, f_dummy, eps)
     else:
         expr = error_expr.subs({f_dummy: f})
         stats_new = stats.reassign(y, expr)
 
     if zero_protection:
         guard_expr = sympy.Piecewise((2.225e-16, sympy.Eq(f, 0)), (f, True))
         guard_assignment = Assignment(ipred, guard_expr)
@@ -303,32 +303,36 @@
     )
 
     model = model.replace(statements=stats_new, random_variables=rvs_new, parameters=params_new)
 
     return model.update_source()
 
 
-def _get_updated_blq_statements(model, expr_dummy, y, f, f_dummy, eps_new):
-    blq_symb, _ = get_blq_symb_and_type(model)
-    for expr, cond in f.args:
-        if blq_symb in cond.free_symbols:
-            f_above_lloq = expr
-            break
-    else:
-        raise AssertionError('BLQ symbol not found')
+def _get_updated_blq_statements(model, expr_dummy, f, f_dummy, eps_new):
+    y = list(model.dependent_variables.keys())[0]
+    f_above_lloq = _get_f_above_lloq(model, f)
     expr_above_lloq = expr_dummy.subs({f_dummy: f_above_lloq})
     expr = f.subs({f_above_lloq: expr_above_lloq})
     # FIXME: make more general
     sd = model.statements.find_assignment('SD')
-    sd_new = get_sd_expr(expr_above_lloq, model.random_variables + eps_new)
-    stats_new = model.statements.reassign(sd.symbol, simplify_expression(model, sd_new))
+    sd_new = get_sd_expr(expr_above_lloq, model.random_variables + eps_new, model.parameters)
+    stats_new = model.statements.reassign(sd.symbol, sd_new)
     stats_new = stats_new.reassign(y, expr)
     return f_above_lloq, stats_new
 
 
+def _get_f_above_lloq(model, f):
+    blq_symb, _ = get_blq_symb_and_type(model)
+    for expr, cond in f.args:
+        if blq_symb in cond.free_symbols:
+            return expr
+    else:
+        raise AssertionError('BLQ symbol not found')
+
+
 def set_combined_error_model(
     model: Model,
     dv: Union[sympy.Symbol, str, int, None] = None,
     data_trans: Optional[Union[str, sympy.Expr]] = None,
 ):
     r"""Set a combined error model. Initial estimates for new sigmas are :math:`(min(DV)/2)²` for
     proportional and 0.09 for additive.
@@ -446,15 +450,15 @@
         else:
             error_expr = f_dummy + f_dummy * ruv_prop + ruv_add
     else:
         raise ValueError(f"Not supported data transformation {data_trans}")
 
     if has_blq_transformation(model):
         _, stats_new = _get_updated_blq_statements(
-            model, error_expr, y, f, f_dummy, [eps_prop, eps_add]
+            model, error_expr, f, f_dummy, [eps_prop, eps_add]
         )
     else:
         expr = error_expr.subs({f_dummy: f})
         stats_new = stats.reassign(y, expr)
 
     rvs_new, params_new = _get_unused_parameters_and_rvs(
         stats_new, model.parameters, model.random_variables + [eps_prop, eps_add]
@@ -941,27 +945,38 @@
 
     if has_proportional_error_model(model):
         theta_init = 1
     else:
         theta_init = 0.1
 
     # Find for example W = IPRED
+    ipredadj = None
+    alternative = None
     for s in sset:
-        if isinstance(s, Assignment) and s.expression == ipred:
-            alternative = s.symbol
-            if zero_protection:
-                guard_expr = sympy.Piecewise(
-                    (2.225e-307, sympy.Eq(s.expression, 0)), (s.expression, True)
-                )
-                guard_assignment = Assignment(ipred, guard_expr)
-                ind = sset.find_assignment_index('Y')
-                sset = sset[0:ind] + guard_assignment + sset[ind:]
-            break
-    else:
-        alternative = None
+        if isinstance(s, Assignment):
+            if s.expression == ipred:
+                alternative = s.symbol
+                if zero_protection:
+                    guard_expr = sympy.Piecewise(
+                        (2.225e-307, sympy.Eq(s.expression, 0)), (s.expression, True)
+                    )
+                    guard_assignment = Assignment(ipred, guard_expr)
+                    ind = sset.find_assignment_index('Y')
+                    sset = sset[0:ind] + guard_assignment + sset[ind:]
+                break
+            if isinstance(s.expression, sympy.Piecewise):
+                args = s.expression.args
+                for expr, cond in args:
+                    if expr == ipred:
+                        ipredadj = s.symbol
+                        break
+
+        if has_blq_transformation(model):
+            _, _, f = _preparations(model)
+            ipred = _get_f_above_lloq(model, f)
 
     for e in eps.names:
         theta_name = str(
             _create_symbol(
                 sset, pset, model.random_variables, model.datainfo, 'power', force_numbering=True
             )
         )
@@ -971,15 +986,28 @@
             theta = Parameter(theta_name, theta_init, lower=lower_limit)
         pset.append(theta)
         sset = sset.subs(
             {sympy.Symbol(e) * ipred: sympy.Symbol(e)}
         )  # To avoid getting F*EPS*F**THETA
         if alternative:  # To avoid getting W*EPS*F**THETA
             sset = sset.subs({sympy.Symbol(e) * alternative: sympy.Symbol(e)})
-        sset = sset.subs({sympy.Symbol(e): ipred ** sympy.Symbol(theta.name) * sympy.Symbol(e)})
+
+        if ipredadj:
+            sset = sset.subs(
+                {sympy.Symbol(e) * ipredadj: ipredadj ** sympy.Symbol(theta.name) * sympy.Symbol(e)}
+            )
+        else:
+            sset = sset.subs({sympy.Symbol(e): ipred ** sympy.Symbol(theta.name) * sympy.Symbol(e)})
+
+        if has_blq_transformation(model):
+            # FIXME: make more general
+            y_above_lloq, _ = sset.find_assignment('Y').expression.args[0]
+            sd = model.statements.find_assignment('SD')
+            sd_new = get_sd_expr(y_above_lloq, model.random_variables, Parameters.create(pset))
+            sset = sset.reassign(sd.symbol, sd_new)
 
     model = model.replace(parameters=Parameters.create(pset), statements=sset)
 
     return model.update_source()
 
 
 def get_ipred(model):
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/estimation.py` & `pharmpy-core-0.97.0/src/pharmpy/modeling/estimation.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/estimation_steps.py` & `pharmpy-core-0.97.0/src/pharmpy/modeling/estimation_steps.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/evaluation.py` & `pharmpy-core-0.97.0/src/pharmpy/modeling/evaluation.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/example_models/moxo.csv` & `pharmpy-core-0.97.0/src/pharmpy/modeling/example_models/moxo.csv`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/example_models/moxo.mod` & `pharmpy-core-0.97.0/src/pharmpy/modeling/example_models/moxo.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/example_models/pheno.cov` & `pharmpy-core-0.97.0/src/pharmpy/modeling/example_models/pheno.cov`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/example_models/pheno.datainfo` & `pharmpy-core-0.97.0/src/pharmpy/modeling/example_models/pheno.datainfo`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/example_models/pheno.dta` & `pharmpy-core-0.97.0/src/pharmpy/modeling/example_models/pheno.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/example_models/pheno.ext` & `pharmpy-core-0.97.0/src/pharmpy/modeling/example_models/pheno.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/example_models/pheno.lst` & `pharmpy-core-0.97.0/src/pharmpy/modeling/example_models/pheno.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/example_models/pheno.mod` & `pharmpy-core-0.97.0/src/pharmpy/modeling/example_models/pheno.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/example_models/pheno.phi` & `pharmpy-core-0.97.0/src/pharmpy/modeling/example_models/pheno.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/example_models/pheno.tab` & `pharmpy-core-0.97.0/src/pharmpy/modeling/example_models/pheno.tab`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/example_models/pheno_linear.dta` & `pharmpy-core-0.97.0/src/pharmpy/modeling/example_models/pheno_linear.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/example_models/pheno_linear.ext` & `pharmpy-core-0.97.0/src/pharmpy/modeling/example_models/pheno_linear.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/example_models/pheno_linear.lst` & `pharmpy-core-0.97.0/src/pharmpy/modeling/example_models/pheno_linear.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/example_models/pheno_linear.mod` & `pharmpy-core-0.97.0/src/pharmpy/modeling/example_models/pheno_linear.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/example_models/pheno_linear.phi` & `pharmpy-core-0.97.0/src/pharmpy/modeling/example_models/pheno_linear.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/expressions.py` & `pharmpy-core-0.97.0/src/pharmpy/modeling/expressions.py`

 * *Files 1% similar despite different names*

```diff
@@ -364,17 +364,21 @@
     Example
     -------
     >>> from pharmpy.modeling import load_example_model, simplify_expression
     >>> model = load_example_model("pheno")
     >>> simplify_expression(model, "Abs(PTVCL)")
     PTVCL
     """
+    return _simplify_expression_from_parameters(expr, model.parameters)
+
+
+def _simplify_expression_from_parameters(expr, parameters):
     expr = parse_expr(expr)
     d = {}
-    for p in model.parameters:
+    for p in parameters:
         if p.fix:
             s = sympy.Float(p.init)
         elif p.upper < 0:
             s = sympy.Symbol(p.name, real=True, negative=True)
             d[s] = p.symbol
         elif p.upper <= 0:
             s = sympy.Symbol(p.name, real=True, nonpositive=True)
@@ -1322,24 +1326,36 @@
 
     for assignment in assignments:
         symbol = assignment.symbol
         expression = assignment.expression
         fs = expression.free_symbols
 
         if symbol not in fs:  # NOTE We skip redefinitions (e.g. CL=CL+1)
-            if len(fs) == 1:
+            if sympy.Symbol('t') in fs:  # FIXME: Should use ode.t here at some point
+                yield 'synthetic', assignment
+                continue
+            elif len(fs) == 1:
                 a = next(iter(fs))
                 if a in symbols:
                     yield 'synthetic', assignment  # E.g. S1=V
                     continue
             elif len(fs) == 2:
                 it = iter(fs)
                 a = next(it)
                 b = next(it)
-                if a in symbols and b in symbols and (expression == a / b or expression == b / a):
+                if (
+                    a in symbols
+                    and b in symbols
+                    and (
+                        expression == a / b
+                        or expression == b / a
+                        or expression == a * b
+                        or expression == b * a
+                    )
+                ):
                     yield 'synthetic', assignment  # E.g. K=CL/V
                     continue
 
         yield 'natural', assignment
 
 
 def _remove_synthetic_assignments(classified_assignments: List[Tuple[str, Assignment]]):
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/help_functions.py` & `pharmpy-core-0.97.0/src/pharmpy/modeling/help_functions.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/iterators.py` & `pharmpy-core-0.97.0/src/pharmpy/modeling/iterators.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/lrt.py` & `pharmpy-core-0.97.0/src/pharmpy/modeling/lrt.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/math.py` & `pharmpy-core-0.97.0/src/pharmpy/modeling/math.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/metabolite.py` & `pharmpy-core-0.97.0/src/pharmpy/modeling/metabolite.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/odes.py` & `pharmpy-core-0.97.0/src/pharmpy/modeling/odes.py`

 * *Files 0% similar despite different names*

```diff
@@ -1893,16 +1893,16 @@
     True
     """
 
     if not has_odes(model):
         return False
 
     odes = model.statements.ode_system
-    M = odes.compartmental_matrix
-    return odes.t not in M.free_symbols
+    symbs = odes.compartmental_matrix.free_symbols | odes.zero_order_inputs.free_symbols
+    return odes.t not in symbs
 
 
 def has_linear_odes_with_real_eigenvalues(model: Model):
     """Check if model has a linear ode system with real eigenvalues
 
     Parameters
     ----------
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/parameter_sampling.py` & `pharmpy-core-0.97.0/src/pharmpy/modeling/parameter_sampling.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/parameters.py` & `pharmpy-core-0.97.0/src/pharmpy/modeling/parameters.py`

 * *Files 15% similar despite different names*

```diff
@@ -1,9 +1,10 @@
 from typing import Dict, List, Optional, Union
 
+from pharmpy.deps import pandas as pd
 from pharmpy.model import Model, Parameter, Parameters
 
 
 def get_thetas(model: Model):
     """Get all thetas (structural parameters) of a model
 
     Parameters
@@ -128,14 +129,92 @@
     unfix_paramaters_to : Unfixing parameters and setting a new initial estimate in the same
     """
     new = model.parameters.set_initial_estimates(inits)
     model = model.replace(parameters=new)
     return model.update_source()
 
 
+def update_inits(
+    model: Model, parameter_estimates: pd.Series, move_est_close_to_bounds: bool = False
+):
+    """Update initial parameter estimate for a model
+
+    Updates initial estimates of population parameters for a model.
+    If the new initial estimates are out of bounds or NaN this function will raise.
+
+    Parameters
+    ----------
+    model : Model
+        Pharmpy model to update initial estimates
+    parameter_estimates : pd.Series
+        Parameter estimates to update
+    move_est_close_to_bounds : bool
+        Move estimates that are close to bounds. If correlation >0.99 the correlation will
+        be set to 0.9, if variance is <0.001 the variance will be set to 0.01.
+
+    Returns
+    -------
+    Model
+        Pharmpy model object
+
+    Example
+    -------
+    >>> from pharmpy.modeling import load_example_model, update_inits
+    >>> from pharmpy.tools import load_example_modelfit_results
+    >>> model = load_example_model("pheno")
+    >>> results = load_example_modelfit_results("pheno")
+    >>> model.parameters.inits  # doctest:+ELLIPSIS
+    {'PTVCL': 0.00469307, 'PTVV': 1.00916, 'THETA_3': 0.1, 'IVCL': 0.0309626, 'IVV': 0.031128, 'SIGMA_1_1': 0.013241}
+    >>> model = update_inits(model, results.parameter_estimates)
+    >>> model.parameters.inits  # doctest:+ELLIPSIS
+    {'PTVCL': 0.00469555, 'PTVV': 0.984258, 'THETA_3': 0.15892, 'IVCL': 0.0293508, 'IVV': 0.027906, ...}
+
+    """
+    # FIXME: can be combined with set_initial_estimates
+    if move_est_close_to_bounds:
+        parameter_estimates = _move_est_close_to_bounds(model, parameter_estimates)
+
+    model = model.replace(parameters=model.parameters.set_initial_estimates(parameter_estimates))
+
+    return model.update_source()
+
+
+def _move_est_close_to_bounds(model: Model, pe):
+    rvs, pset = model.random_variables, model.parameters
+    est = pe.to_dict()
+    sdcorr = rvs.parameters_sdcorr(est)
+    newdict = est.copy()
+    for dist in rvs:
+        rvs = dist.names
+        if len(rvs) > 1:
+            sigma_sym = dist.variance
+            for i in range(sigma_sym.rows):
+                for j in range(sigma_sym.cols):
+                    param_name = sigma_sym[i, j].name
+                    if i != j:
+                        if sdcorr[param_name] > 0.99:
+                            name_i, name_j = sigma_sym[i, i].name, sigma_sym[j, j].name
+                            # From correlation to covariance
+                            corr_new = 0.9
+                            sd_i, sd_j = sdcorr[name_i], sdcorr[name_j]
+                            newdict[param_name] = corr_new * sd_i * sd_j
+                    else:
+                        if not _is_zero_fix(pset[param_name]) and est[param_name] < 0.001:
+                            newdict[param_name] = 0.01
+        else:
+            param_name = dist.variance.name
+            if not _is_zero_fix(pset[param_name]) and est[param_name] < 0.001:
+                newdict[param_name] = 0.01
+    return newdict
+
+
+def _is_zero_fix(param):
+    return param.init == 0 and param.fix
+
+
 def set_upper_bounds(model: Model, bounds: Dict[str, float]):
     """Set parameter upper bounds
 
     Parameters
     ----------
     model : Model
         Pharmpy model
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/plots.py` & `pharmpy-core-0.97.0/src/pharmpy/modeling/plots.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/results.py` & `pharmpy-core-0.97.0/src/pharmpy/modeling/results.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/units.py` & `pharmpy-core-0.97.0/src/pharmpy/modeling/units.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/modeling/write_csv.py` & `pharmpy-core-0.97.0/src/pharmpy/modeling/write_csv.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/reporting/altairplot.py` & `pharmpy-core-0.97.0/src/pharmpy/reporting/altairplot.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/reporting/custom.css` & `pharmpy-core-0.97.0/src/pharmpy/reporting/custom.css`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/reporting/reporting.py` & `pharmpy-core-0.97.0/src/pharmpy/reporting/reporting.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/results.py` & `pharmpy-core-0.97.0/src/pharmpy/results.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/__init__.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/__init__.py`

 * *Files 1% similar despite different names*

```diff
@@ -21,14 +21,15 @@
     'run_covsearch',  # pyright: ignore [reportUnsupportedDunderAll]
     'run_estmethod',  # pyright: ignore [reportUnsupportedDunderAll]
     'run_iivsearch',  # pyright: ignore [reportUnsupportedDunderAll]
     'run_iovsearch',  # pyright: ignore [reportUnsupportedDunderAll]
     'run_modelfit',  # pyright: ignore [reportUnsupportedDunderAll]
     'run_modelsearch',  # pyright: ignore [reportUnsupportedDunderAll]
     'run_ruvsearch',  # pyright: ignore [reportUnsupportedDunderAll]
+    'run_structsearch',  # pyright: ignore [reportUnsupportedDunderAll]
     'run_tool',  # pyright: ignore [reportUnsupportedDunderAll]
     'summarize_errors',  # pyright: ignore [reportUnsupportedDunderAll]
     'summarize_individuals',  # pyright: ignore [reportUnsupportedDunderAll]
     'summarize_individuals_count_table',  # pyright: ignore [reportUnsupportedDunderAll]
     'summarize_modelfit_results',  # pyright: ignore [reportUnsupportedDunderAll]
     'write_results',  # pyright: ignore [reportUnsupportedDunderAll]
 )
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/allometry/tool.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/allometry/tool.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/amd/funcs.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/amd/funcs.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/amd/run.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/amd/run.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,18 +1,18 @@
 import warnings
 from pathlib import Path
 from typing import Callable, List, Optional, Tuple, Union
 
 from pharmpy.deps import pandas as pd
 from pharmpy.deps import sympy
 from pharmpy.model import Model, Results
-from pharmpy.modeling.blq import transform_blq
+from pharmpy.modeling.blq import has_blq_transformation, transform_blq
 from pharmpy.modeling.common import convert_model
 from pharmpy.modeling.covariate_effect import get_covariates_allowed_in_covariate_effect
-from pharmpy.modeling.eta_additions import get_occasion_levels
+from pharmpy.modeling.parameter_variability import get_occasion_levels
 from pharmpy.results import ModelfitResults
 from pharmpy.tools import retrieve_final_model, summarize_errors, write_results
 from pharmpy.tools.allometry.tool import validate_allometric_variable
 from pharmpy.tools.mfl.feature.covariate import covariates as extract_covariates
 from pharmpy.tools.mfl.feature.covariate import spec as covariate_spec
 from pharmpy.tools.mfl.filter import covsearch_statement_types, modelsearch_statement_types
 from pharmpy.tools.mfl.parse import parse as mfl_parse
@@ -30,15 +30,16 @@
 from ..run import run_tool
 from .results import AMDResults
 
 
 def run_amd(
     input: Union[Model, Path, str],
     results: Optional[ModelfitResults] = None,
-    modeltype: str = 'pk_oral',
+    modeltype: str = 'basic_pk',
+    administraton: str = 'oral',
     cl_init: float = 0.01,
     vc_init: float = 1.0,
     mat_init: float = 0.1,
     search_space: Optional[str] = None,
     lloq_method: Optional[str] = None,
     lloq_limit: Optional[str] = None,
     order: Optional[List[str]] = None,
@@ -54,15 +55,17 @@
     Parameters
     ----------
     input : Model or Path
         Read model object/Path to a dataset
     results : ModelfitResults
         Reults of input if input is a model
     modeltype : str
-        Type of model to build. Either 'pk_oral' or 'pk_iv'
+        Type of model to build. Either 'basic_pl' or 'tmdd'
+    administration : str
+        Route of administration. Either 'iv' or 'oral'
     cl_init : float
         Initial estimate for the population clearance
     vc_init : float
         Initial estimate for the central compartment population volume
     mat_init : float
         Initial estimate for the mean absorption time (not for iv models)
     search_space : str
@@ -326,15 +329,19 @@
         return res
 
     return _run_iiv
 
 
 def _subfunc_ruvsearch(path) -> SubFunc:
     def _run_ruvsearch(model):
-        res = run_tool('ruvsearch', model, path=path / 'ruvsearch')
+        if has_blq_transformation(model):
+            skip, max_iter = ['IIV_on_RUV', 'time_varying'], 1
+        else:
+            skip, max_iter = [], 3
+        res = run_tool('ruvsearch', model, skip=skip, max_iter=max_iter, path=path / 'ruvsearch')
         assert isinstance(res, Results)
         return res
 
     return _run_ruvsearch
 
 
 def _subfunc_covariates(
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/bootstrap/report.rst` & `pharmpy-core-0.97.0/src/pharmpy/tools/bootstrap/report.rst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/bootstrap/results.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/bootstrap/results.py`

 * *Files 1% similar despite different names*

```diff
@@ -208,21 +208,21 @@
     """Create bootstrapresults from a PsN bootstrap run
 
     :param path: Path to PsN boostrap run directory
     :return: A :class:`BootstrapResults` object
     """
     path = Path(path)
 
-    models = [Model.create_model(p) for p in model_paths(path, 'bs_pr1_*.mod')]
+    models = [Model.parse_model(p) for p in model_paths(path, 'bs_pr1_*.mod')]
     # Read the results already now to give an appropriate error if no results exists
     results = [m.modelfit_results for m in models if m.modelfit_results is not None]
     if not results:
         raise FileNotFoundError("No model results available in m1")
     try:
-        base_model = Model.create_model(cmd_line_model_path(path))
+        base_model = Model.parse_model(cmd_line_model_path(path))
     except FileNotFoundError:
         base_model = None
 
     # Read dOFV results in NONMEM specific way. Models have multiple $PROBLEM
     # Create proper result objects to pass to calculate_results
     dofv_results = None
     if (path / 'm1' / 'dofv_1.mod').is_file():
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/bootstrap/tool.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/bootstrap/tool.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/cdd/results.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/cdd/results.py`

 * *Files 0% similar despite different names*

```diff
@@ -229,15 +229,15 @@
     if not path.is_dir():
         raise IOError(f'Could not find cdd folder: {str(path)}')
 
     options = psn_cdd_options(path)
 
     if base_model_path is None:
         base_model_path = Path(options['model_path'])
-    base_model = Model.create_model(base_model_path)
+    base_model = Model.parse_model(base_model_path)
     base_model_results = read_modelfit_results(base_model_path)
 
     paths = model_paths(path, 'cdd_*.mod')
     cdd_models = list(map(Model.parse_model, paths))
     cdd_results = list(map(read_modelfit_results, paths))
     skipped_individuals = psn_cdd_skipped_individuals(path)
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/common.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/common.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/covsearch/tool.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/covsearch/tool.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/crossval/results.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/crossval/results.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/estmethod/algorithms.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/estmethod/algorithms.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/estmethod/report.rst` & `pharmpy-core-0.97.0/src/pharmpy/tools/estmethod/report.rst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/estmethod/tool.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/estmethod/tool.py`

 * *Files 2% similar despite different names*

```diff
@@ -4,15 +4,15 @@
 
 import pharmpy.tools.estmethod.algorithms as algorithms
 from pharmpy.deps import numpy as np
 from pharmpy.deps import pandas as pd
 from pharmpy.internals.fn.signature import with_same_arguments_as
 from pharmpy.internals.fn.type import with_runtime_arguments_type_check
 from pharmpy.model import Model
-from pharmpy.modeling import has_first_order_elimination
+from pharmpy.modeling import has_linear_odes
 from pharmpy.results import ModelfitResults
 from pharmpy.tools import summarize_errors, summarize_modelfit_results
 from pharmpy.tools.common import ToolResults
 from pharmpy.tools.modelfit import create_fit_workflow
 from pharmpy.workflows import Task, Workflow
 
 EST_METHODS = ('FOCE', 'FO', 'IMP', 'IMPMAP', 'ITS', 'SAEM', 'LAPLACE', 'BAYES')
@@ -68,14 +68,17 @@
     if model is not None:
         start_task = Task('start_estmethod', start, model)
     else:
         start_task = Task('start_estmethod', start)
 
     wf.add_task(start_task)
 
+    if methods is None:
+        methods = [model.estimation_steps[-1].method]
+
     wf_algorithm, task_base_model_fit = algorithm_func(
         _format_input(methods, EST_METHODS), _format_input(solvers, SOLVERS)
     )
     wf.insert_workflow(wf_algorithm, predecessors=start_task)
 
     wf_fit = create_fit_workflow(n=len(wf.output_tasks))
     wf.insert_workflow(wf_fit, predecessors=wf.output_tasks)
@@ -171,15 +174,15 @@
 
     return pd.concat(dfs.values(), keys=dfs.keys())
 
 
 @with_runtime_arguments_type_check
 @with_same_arguments_as(create_workflow)
 def validate_input(algorithm, methods, solvers, model):
-    if solvers is not None and has_first_order_elimination(model):
+    if solvers is not None and has_linear_odes(model):
         raise ValueError(
             'Invalid input `model`: testing non-linear solvers on linear system is not supported'
         )
 
     if algorithm not in ALGORITHMS:
         raise ValueError(
             f'Invalid `algorithm`: got `{algorithm}`, must be one of {sorted(ALGORITHMS)}.'
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/evaldesign/tool.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/evaldesign/tool.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/external/nlmixr/__init__.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/external/nlmixr/__init__.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/external/nlmixr/run.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/external/nlmixr/run.py`

 * *Files 4% similar despite different names*

```diff
@@ -20,15 +20,17 @@
     write_csv,
 )
 from pharmpy.results import ModelfitResults
 from pharmpy.tools import fit
 from pharmpy.workflows.log import Log
 
 
-def execute_model(model: pharmpy.model.Model, db: str, evaluate=False) -> pharmpy.model.Model:
+def execute_model(
+    model: pharmpy.model.Model, db: str, evaluate=False, path=None
+) -> pharmpy.model.Model:
     """
     Executes a model using nlmixr2 estimation.
 
     Parameters
     ----------
     model : pharmpy.model.Model
         An pharmpy model object.
@@ -44,28 +46,28 @@
     if evaluate:
         if [s.evaluation for s in model.estimation_steps._steps][0] is False:
             model = set_evaluation_step(model)
 
     db = pharmpy.workflows.LocalDirectoryToolDatabase(db)
     database = db.model_database
     model = convert_model(model)
-    path = Path.cwd() / f'nlmixr_run_{model.name}-{uuid.uuid1()}'
+    if path is None:
+        path = Path.cwd() / f'nlmixr_run_{model.name}-{uuid.uuid1()}'
     model.internals.path = path
     meta = path / '.pharmpy'
     meta.mkdir(parents=True, exist_ok=True)
     if model.datainfo.path is not None:
         model = model.replace(datainfo=model.datainfo.replace(path=None))
     write_csv(model, path=path)
     model = model.replace(datainfo=model.datainfo.replace(path=path))
 
     dataname = f'{model.name}.csv'
     pre = f'library(nlmixr2)\n\ndataset <- read.csv("{path / dataname}")\n'
 
     if "fix_eta" in model.estimation_steps[0].tool_options:
-        write_fix_eta(model, path=path)
         pre += f'etas <- as.matrix(read.csv("{path}/fix_eta.csv"))'
     pre += "\n"
 
     code = pre + model.model_code
     cg = CodeGenerator()
     cg.add('ofv <- fit$objDf$OBJF')
     cg.add('thetas <- as.data.frame(fit$theta)')
@@ -143,14 +145,15 @@
 
 
 def verification(
     model: pharmpy.model.Model,
     db_name: str,
     error: float = 10**-3,
     return_comp: bool = False,
+    return_stat: bool = False,
     fix_eta: bool = True,
     force_ipred: bool = False,
     force_pred: bool = False,
     ignore_print=False,
 ) -> Union[bool, pd.DataFrame]:
     """
     Verify that a model inputet in NONMEM format can be correctly translated to
@@ -184,162 +187,203 @@
         If return_comp = True, return a table of comparisons and differences in
         predictions instead of a boolean indicating if they are the same or not
 
     """
 
     nonmem_model = model
 
-    # Save results from the nonmem model
-    if nonmem_model.modelfit_results is None:
-        if not ignore_print:
-            print_step("Calculating NONMEM predictions... (this might take a while)")
-        nonmem_model = nonmem_model.replace(modelfit_results=fit(nonmem_model))
-    else:
-        if nonmem_model.modelfit_results.predictions is None:
+    try:
+        # Save results from the nonmem model
+        if nonmem_model.modelfit_results is None:
             if not ignore_print:
                 print_step("Calculating NONMEM predictions... (this might take a while)")
             nonmem_model = nonmem_model.replace(modelfit_results=fit(nonmem_model))
+        else:
+            if nonmem_model.modelfit_results.predictions is None:
+                if not ignore_print:
+                    print_step("Calculating NONMEM predictions... (this might take a while)")
+                nonmem_model = nonmem_model.replace(modelfit_results=fit(nonmem_model))
+    except Exception:
+        raise Exception("Nonmem model could not be fitted")
 
     # Set a tool option to fix theta values when running nlmixr
     if fix_eta:
         nonmem_model = fixate_eta(nonmem_model)
 
     # Check that evaluation step is set to True
     if [s.evaluation for s in nonmem_model.estimation_steps._steps][0] is False:
         nonmem_model = set_evaluation_step(nonmem_model)
 
     # Update the nonmem model with new estimates
     # and convert to nlmixr
     if not ignore_print:
         print_step("Converting NONMEM model to nlmixr2...")
-    if fix_eta is True:
-        nlmixr_model = convert_model(
-            update_inits(nonmem_model, nonmem_model.modelfit_results.parameter_estimates),
-            keep_etas=True,
-        )
-    else:
+    try:
         nlmixr_model = convert_model(
             update_inits(nonmem_model, nonmem_model.modelfit_results.parameter_estimates)
         )
+    except Exception:
+        raise Exception("Could not convert model to nlmixr2")
 
     # Execute the nlmixr model
     if not ignore_print:
         print_step("Executing nlmixr2 model... (this might take a while)")
-
-    nlmixr_model = execute_model(nlmixr_model, db_name)
+    path = Path.cwd() / f'nlmixr_run_{model.name}-{uuid.uuid1()}'
+    meta = path / '.pharmpy'
+    meta.mkdir(parents=True, exist_ok=True)
+    write_fix_eta(nonmem_model, path=path)
+    try:
+        nlmixr_model = execute_model(nlmixr_model, db_name, path=path)
+    except Exception:
+        raise Exception("nlmixr2 model could not be fitted")
 
     # Combine the two based on ID and time
     if not ignore_print:
         print_step("Creating result comparison table...")
     combined_result = compare_models(
         nonmem_model,
         nlmixr_model,
         error=error,
         force_ipred=force_ipred,
         force_pred=force_pred,
+        return_stat=return_stat,
         ignore_print=ignore_print,
     )
 
     if not ignore_print:
         print_step("DONE")
-    if return_comp is True:
+    if return_comp is True or return_stat is True:
         return combined_result
     else:
         if all(combined_result["PASS/FAIL"] == "PASS"):
             return True
         else:
             return False
 
 
 def compare_models(
-    model_1, model_2, error=10**-3, force_ipred=False, force_pred=False, ignore_print=False
+    model_1,
+    model_2,
+    error=10**-3,
+    force_ipred=False,
+    force_pred=False,
+    ignore_print=False,
+    return_stat=False,
 ):
     assert model_1.modelfit_results.predictions is not None
     assert model_2.modelfit_results.predictions is not None
 
     mod1 = model_1
-    mod1_type = str(type(mod1)).split(".")[2]
+    mod1_type = str(type(mod1)).split(".")[3]
     mod2 = model_2
-    mod2_type = str(type(mod2)).split(".")[2]
+    mod2_type = str(type(mod2)).split(".")[3]
 
     nm_to_r = False
-    if (
-        mod1_type == "nonmem"
-        and mod2_type != "nonmem"
-        or mod2_type == "nonmem"
-        and mod1_type != "nonmem"
+    if (mod1_type == "nonmem" and mod2_type != "nonmem") or (
+        mod2_type == "nonmem" and mod1_type != "nonmem"
     ):
         nm_to_r = True
 
     mod1 = mod1.replace(dataset=mod1.dataset.reset_index())
     mod2 = mod2.replace(dataset=mod2.dataset.reset_index())
 
-    for mod in [mod1, mod2]:
-        if "EVID" not in mod.dataset.columns:
-            mod = add_evid(mod)
+    if "EVID" not in mod1.dataset.columns:
+        mod1 = add_evid(mod1)
+
+    if "EVID" not in mod2.dataset.columns:
+        mod2 = add_evid(mod2)
 
     if nm_to_r:
         if mod1_type == "nonmem":
             predictions = mod1.modelfit_results.predictions.reset_index()
             predictions = predictions.drop(
                 mod1.dataset[~mod1.dataset["EVID"].isin([0, 2])].index.to_list()
             )
             predictions = predictions.set_index(["ID", "TIME"])
             mod1 = mod1.replace(modelfit_results=ModelfitResults(predictions=predictions))
+
+            dataset = mod1.dataset
+            dv_var = "DV"
+            dv = dataset.drop(mod1.dataset[~mod1.dataset["EVID"].isin([0, 2])].index.to_list())[
+                dv_var
+            ]
         if mod2_type == "nonmem":
             predictions = mod2.modelfit_results.predictions.reset_index()
             predictions = predictions.drop(
                 mod2.dataset[~mod2.dataset["EVID"].isin([0, 2])].index.to_list()
             )
             predictions = predictions.set_index(["ID", "TIME"])
             mod2 = mod2.replace(modelfit_results=ModelfitResults(predictions=predictions))
 
+            dataset = mod2.dataset
+            dv_var = "DV"
+            dv = dataset.drop(mod2.dataset[~mod2.dataset["EVID"].isin([0, 2])].index.to_list())[
+                dv_var
+            ]
+    else:
+        dataset = mod1.dataset
+        dv_var = "DV"
+        dv = dataset.drop(mod1.dataset[~mod1.dataset["EVID"].isin([0, 2])].index.to_list())[dv_var]
+
+    dv = dv.reset_index(drop=True)
+
     mod1_results = mod1.modelfit_results.predictions.copy()
 
     mod2_results = mod2.modelfit_results.predictions.copy()
 
     pred = False
     ipred = False
     # ---
     if force_pred:
         if "PRED" in mod1_results.columns:
             pred = True
             p = "PRED"
             assert p in mod2_results.columns
             mod1_results.rename(columns={p: f'PRED_{mod1_type}'}, inplace=True)
             mod2_results.rename(columns={p: f'PRED_{mod2_type}'}, inplace=True)
+        else:
+            print("No PRED column found")
+            return None
     elif force_ipred:
         if "IPRED" in mod1_results.columns:
             p = "IPRED"
             ipred = True
             assert p in mod2_results.columns
             mod1_results.rename(columns={p: f'{p}_{mod1_type}'}, inplace=True)
             mod2_results.rename(columns={p: f'IPRED_{mod2_type}'}, inplace=True)
         elif "CIPREDI" in mod1_results.columns:
             p = "CIPREDI"
             ipred = True
             assert p in mod2_results.columns
             mod1_results.rename(columns={p: f'{p}_{mod1_type}'}, inplace=True)
             mod2_results.rename(columns={p: f'IPRED_{mod2_type}'}, inplace=True)
+        else:
+            print("No IPRED (or CIPRED) column found")
+            return None
     else:
-        for p in mod1_results.columns:
-            if p == "PRED":
-                pred = True
-                assert p in mod2_results.columns
-                mod1_results.rename(columns={p: f'PRED_{mod1_type}'}, inplace=True)
-                mod2_results.rename(columns={p: f'PRED_{mod2_type}'}, inplace=True)
-            elif (p == "IPRED" or p == "CIPREDI") and "PRED" not in mod1_results.columns:
-                ipred = True
-                assert "IPRED" in mod2_results.columns or "CIPREDI" in mod2_results.columns
-                mod1_results.rename(columns={p: f'{p}_{mod1_type}'}, inplace=True)
-                if "IPRED" in mod2_results.columns:
-                    mod2_results.rename(columns={p: f'IPRED_{mod2_type}'}, inplace=True)
-                else:
-                    mod2_results.rename(columns={p: f'CIPREDI_{mod2_type}'}, inplace=True)
-    # ---
+        if "PRED" in mod1_results.columns:
+            p = "PRED"
+            pred = True
+            assert p in mod2_results.columns
+            mod1_results.rename(columns={p: f'PRED_{mod1_type}'}, inplace=True)
+            mod2_results.rename(columns={p: f'PRED_{mod2_type}'}, inplace=True)
+        elif "IPRED" in mod1_results.columns:
+            p = "IPRED"
+            ipred = True
+            mod1_results.rename(columns={p: f'{p}_{mod1_type}'}, inplace=True)
+            assert p in mod2_results.columns
+            mod2_results.rename(columns={p: f'{p}_{mod2_type}'}, inplace=True)
+        elif "CIPREDI" in mod1_results.columns:
+            p = "CIPREDI"
+            ipred = True
+            mod1_results.rename(columns={p: f'IPRED_{mod1_type}'}, inplace=True)
+            if p not in mod2_results.columns:
+                mod2_results.rename(columns={"IPRED": f'IPRED_{mod2_type}'}, inplace=True)
+            else:
+                mod2_results.rename(columns={p: f'IPRED_{mod2_type}'}, inplace=True)
 
     if not (pred or ipred):
         print("No comparable prediction value was found. Please use 'PRED' or 'IPRED")
         return False
 
     combined_result = mod1_results
     if pred:
@@ -350,14 +394,16 @@
         )
     if ipred:
         combined_result[f'IPRED_{mod2_type}'] = mod2_results[f'IPRED_{mod2_type}'].to_list()
         combined_result['IPRED_DIFF'] = abs(
             combined_result[f'IPRED_{mod1_type}'] - combined_result[f'IPRED_{mod2_type}']
         )
 
+    combined_result["DV"] = dv.values
+
     combined_result["PASS/FAIL"] = "PASS"
     if not ignore_print:
         print("Differences in population predicted values")
     if (pred and ipred) or (pred and not ipred):
         if force_ipred:
             if not ignore_print:
                 print("Using IPRED values for final comparison")
@@ -374,19 +420,22 @@
             if not ignore_print:
                 print("Using IPRED values instead")
         final = "IPRED"
 
     combined_result.loc[combined_result[f'{final}_DIFF'] > error, "PASS/FAIL"] = "FAIL"
     if not ignore_print:
         print(
-            combined_result[f'{final}_DIFF'].describe()[["mean", "75%", "max"]].to_string(),
+            combined_result[f'{final}_DIFF'].describe()[["min", "mean", "75%", "max"]].to_string(),
             end="\n\n",
         )
 
-    return combined_result
+    if return_stat:
+        return combined_result[f'{final}_DIFF'].describe()[["min", "mean", "75%", "max"]]
+    else:
+        return combined_result
 
 
 def print_step(s: str) -> None:
     """
     Print step currently being performed. Used during verification
 
     Parameters
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/external/nonmem/__init__.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/external/nonmem/__init__.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/external/nonmem/config.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/external/nonmem/config.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/external/nonmem/results.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/external/nonmem/results.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/external/nonmem/results_file.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/external/nonmem/results_file.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/external/nonmem/run.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/external/nonmem/run.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/external/rxode/__init__.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/external/rxode/__init__.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/external/rxode/run.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/external/rxode/run.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/frem/models.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/frem/models.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/frem/results.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/frem/results.py`

 * *Files 0% similar despite different names*

```diff
@@ -1048,15 +1048,16 @@
             elif row.startswith('log: '):
                 logtransformed_covariates = row[5:].split(',')
 
     # add log transformed columns for the -log option. Should be done when creating dataset
     df = model_4.dataset
     if logtransformed_covariates:
         for lncov in logtransformed_covariates:
-            df = df.copy()[f'LN{lncov}'] = np.log(df[lncov])
+            df = df.copy()
+            df[f'LN{lncov}'] = np.log(df[lncov])
         model_4 = model_4.replace(dataset=df)
 
     nunique = get_baselines(model_4)[all_covariates].nunique()
     continuous = list(nunique.index[nunique != 2])
     categorical = list(nunique.index[nunique == 2])
 
     intmod_names = ['model_1.mod', 'model_2.mod', 'model_3.mod', 'model_3b.mod']
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/frem/tool.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/frem/tool.py`

 * *Files 1% similar despite different names*

```diff
@@ -12,15 +12,15 @@
 )
 from pharmpy.tools import read_modelfit_results
 
 from .models import create_model3b
 
 
 def setup(model_path, covariates):
-    input_model = Model.create_model(model_path)
+    input_model = Model.parse_model(model_path)
     covariates = check_covariates(input_model, covariates)
     return covariates
 
 
 def check_covariates(input_model, covariates):
     """Perform checks of covariates and filter out inappropriate ones
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/funcs/ml.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/funcs/ml.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/funcs/ml_models/infinds.tflite` & `pharmpy-core-0.97.0/src/pharmpy/tools/funcs/ml_models/infinds.tflite`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/funcs/ml_models/outliers.tflite` & `pharmpy-core-0.97.0/src/pharmpy/tools/funcs/ml_models/outliers.tflite`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/funcs/summarize_individuals.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/funcs/summarize_individuals.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/iivsearch/algorithms.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/iivsearch/algorithms.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,16 +1,15 @@
 from typing import Dict, Tuple
 
 import pharmpy.tools.modelfit as modelfit
 from pharmpy.internals.expr.subs import subs
 from pharmpy.internals.set.partitions import partitions
 from pharmpy.internals.set.subsets import non_empty_subsets
 from pharmpy.model import Model, RandomVariables
-from pharmpy.modeling import remove_iiv
-from pharmpy.modeling.block_rvs import create_joint_distribution, split_joint_distribution
+from pharmpy.modeling import create_joint_distribution, remove_iiv, split_joint_distribution
 from pharmpy.modeling.expressions import get_rv_parameters
 from pharmpy.results import mfr
 from pharmpy.tools.common import update_initial_estimates
 from pharmpy.workflows import Task, Workflow
 
 
 def brute_force_no_of_etas(base_model, index_offset=0):
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/iivsearch/tool.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/iivsearch/tool.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/iovsearch/tool.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/iovsearch/tool.py`

 * *Files 1% similar despite different names*

```diff
@@ -7,15 +7,15 @@
 from pharmpy.deps import pandas as pd
 from pharmpy.deps import sympy
 from pharmpy.internals.fn.signature import with_same_arguments_as
 from pharmpy.internals.fn.type import with_runtime_arguments_type_check
 from pharmpy.internals.set.subsets import non_empty_proper_subsets, non_empty_subsets
 from pharmpy.model import Assignment, Model
 from pharmpy.modeling import add_iov, get_pk_parameters, remove_iiv, remove_iov
-from pharmpy.modeling.eta_additions import ADD_IOV_DISTRIBUTION
+from pharmpy.modeling.parameter_variability import ADD_IOV_DISTRIBUTION
 from pharmpy.modeling.results import RANK_TYPES
 from pharmpy.results import ModelfitResults
 from pharmpy.tools import rank_models, summarize_modelfit_results
 from pharmpy.tools.common import (
     ToolResults,
     create_results,
     summarize_tool,
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/linearize/results.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/linearize/results.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/linearize/tool.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/linearize/tool.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/mfl/feature/absorption.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/mfl/feature/absorption.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/mfl/feature/covariate.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/mfl/feature/covariate.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/mfl/feature/elimination.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/mfl/feature/elimination.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/mfl/feature/peripherals.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/mfl/feature/peripherals.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/mfl/feature/transits.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/mfl/feature/transits.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/mfl/filter.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/mfl/filter.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/mfl/grammar.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/mfl/grammar.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/mfl/helpers.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/mfl/helpers.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/mfl/interpreter.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/mfl/interpreter.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/mfl/parse.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/mfl/parse.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/mfl/statement/definition.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/mfl/statement/definition.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/mfl/statement/feature/absorption.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/mfl/statement/feature/absorption.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/mfl/statement/feature/count_interpreter.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/mfl/statement/feature/count_interpreter.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/mfl/statement/feature/covariate.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/mfl/statement/feature/covariate.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/mfl/statement/feature/elimination.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/mfl/statement/feature/elimination.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/mfl/statement/feature/transits.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/mfl/statement/feature/transits.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/mfl/stringify.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/mfl/stringify.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/modelfit/__init__.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/modelfit/__init__.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/modelfit/tool.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/modelfit/tool.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/modelsearch/algorithms.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/modelsearch/algorithms.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/modelsearch/tool.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/modelsearch/tool.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/psn_helpers.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/psn_helpers.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/qa/results.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/qa/results.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/rankfuncs.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/rankfuncs.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/reporting.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/reporting.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/run.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/run.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/ruvsearch/results.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/ruvsearch/results.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/ruvsearch/tool.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/ruvsearch/tool.py`

 * *Files 2% similar despite different names*

```diff
@@ -23,14 +23,15 @@
     create_symbol,
     get_mdv,
     set_combined_error_model,
     set_iiv_on_ruv,
     set_initial_estimates,
     set_power_on_ruv,
 )
+from pharmpy.modeling.blq import has_blq_transformation
 from pharmpy.modeling.error import remove_error_model, set_time_varying_error_model
 from pharmpy.results import ModelfitResults
 from pharmpy.tools import (
     summarize_errors,
     summarize_individuals,
     summarize_individuals_count_table,
     summarize_modelfit_results,
@@ -46,14 +47,15 @@
 
 def create_workflow(
     model: Optional[Model] = None,
     results: Optional[ModelfitResults] = None,
     groups: int = 4,
     p_value: float = 0.05,
     skip: Optional[List[str]] = None,
+    max_iter: Optional[int] = 3,
 ):
     """Run the ruvsearch tool. For more details, see :ref:`ruvsearch`.
 
     Parameters
     ----------
     model : Model
         Pharmpy model
@@ -61,14 +63,16 @@
         Results of model
     groups : int
         The number of bins to use for the time varying models
     p_value : float
         The p-value to use for the likelihood ratio test
     skip : list
         A list of models to not attempt.
+    max_iter :  int
+        Number of iterations to run (1, 2, or 3). For models with BLQ only one iteration is supported.
 
     Returns
     -------
     RUVSearchResults
         Ruvsearch tool result object
 
     Examples
@@ -79,15 +83,15 @@
     >>> results = load_example_modelfit_results("pheno")
     >>> run_ruvsearch(model=model, results=results)      # doctest: +SKIP
 
     """
 
     wf = Workflow()
     wf.name = "ruvsearch"
-    start_task = Task('start_ruvsearch', start, model, groups, p_value, skip)
+    start_task = Task('start_ruvsearch', start, model, groups, p_value, skip, max_iter)
     wf.add_task(start_task)
     task_results = Task('results', _results)
     wf.add_task(task_results, predecessors=[start_task])
     return wf
 
 
 def create_iteration_workflow(model, groups, cutoff, skip, current_iteration):
@@ -137,25 +141,25 @@
     post_pro = partial(post_process, cutoff=cutoff, current_iteration=current_iteration)
     task_post_process = Task('post_process', post_pro)
     wf.add_task(task_post_process, predecessors=[start_task] + fit_wf.output_tasks)
 
     return wf
 
 
-def start(context, model, groups, p_value, skip):
+def start(context, model, groups, p_value, skip, max_iter):
     cutoff = float(stats.chi2.isf(q=p_value, df=1))
     if skip is None:
         skip = []
 
     sum_models = []
     selected_models = [model]
     cwres_models = []
     tool_database = None
     last_iteration = 0
-    for current_iteration in (1, 2, 3):
+    for current_iteration in range(1, max_iter + 1):
         last_iteration = current_iteration
         wf = create_iteration_workflow(model, groups, cutoff, skip, current_iteration)
         res, best_model, selected_model_name = call_workflow(
             wf, f'results{current_iteration}', context
         )
         if current_iteration == 1:
             sum_models.append(summarize_modelfit_results(model.modelfit_results))
@@ -328,16 +332,19 @@
         name=name,
         description=name,
     )
     return model
 
 
 def _create_dataset(input_model):
+    # Non-observations have already been filtered
     residuals = input_model.modelfit_results.residuals
     cwres = residuals['CWRES'].reset_index(drop=True)
+    if has_blq_transformation(input_model):
+        cwres = cwres.loc[cwres != 0]
     predictions = input_model.modelfit_results.predictions
     if 'CIPREDI' in predictions:
         ipredcol = 'CIPREDI'
     elif 'IPRED' in predictions:
         ipredcol = 'IPRED'
     else:
         raise ValueError("Need CIPREDI or IPRED")
@@ -348,14 +355,15 @@
     input_id = input_model.dataset[label_id].astype('int64').squeeze().reset_index(drop=True)
     input_model = add_time_after_dose(input_model)
     tad_label = input_model.datainfo.descriptorix['time after dose'][0].name
     tad = input_model.dataset[tad_label].squeeze().reset_index(drop=True)
     df = pd.concat([mdv, input_id, tad, ipred], axis=1)
     df = df[df['MDV'] == 0].reset_index(drop=True)
     df = pd.concat([df, cwres], axis=1).rename(columns={'CWRES': 'DV', ipredcol: 'IPRED'})
+    df = df.loc[df['DV'].notna()]
     return df
 
 
 def _time_after_dose(model):
     if 'TAD' in model.dataset:
         pass
     else:
@@ -434,24 +442,27 @@
         model = None
         selected_model_name = None
     return model, selected_model_name
 
 
 @with_runtime_arguments_type_check
 @with_same_arguments_as(create_workflow)
-def validate_input(model, groups, p_value, skip):
+def validate_input(model, groups, p_value, skip, max_iter):
     if groups <= 0:
         raise ValueError(f'Invalid `groups`: got `{groups}`, must be >= 1.')
 
     if not 0 < p_value <= 1:
         raise ValueError(f'Invalid `p_value`: got `{p_value}`, must be a float in range (0, 1].')
 
     if skip is not None and not set(skip).issubset(SKIP):
         raise ValueError(f'Invalid `skip`: got `{skip}`, must be None/NULL or a subset of {SKIP}.')
 
+    if max_iter < 1 or max_iter > 3:
+        raise ValueError(f'Invalid `max_iter`: got `{max_iter}`, must be int in range [1, 3].')
+
     if model is not None:
         if model.modelfit_results is None:
             raise ValueError(f'Invalid `model`: {model} is missing modelfit results.')
 
         residuals = model.modelfit_results.residuals
         if residuals is None or 'CWRES' not in residuals:
             raise ValueError(
@@ -461,7 +472,13 @@
 
         predictions = model.modelfit_results.predictions
         if predictions is None or ('CIPREDI' not in predictions and 'IPRED' not in predictions):
             raise ValueError(
                 f'Invalid `model`: please check {model.name}.mod file to'
                 f' make sure ID, TIME, CIPREDI (or IPRED) are in $TABLE.'
             )
+
+        if has_blq_transformation(model) and max_iter > 1:
+            raise ValueError(
+                f'Invalid `max_iter`: got `{max_iter}`,only 1 iteration is supported '
+                f'for models with BLQ transformation.'
+            )
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/scm/psn_wrapper.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/scm/psn_wrapper.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/scm/results.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/scm/results.py`

 * *Files 2% similar despite different names*

```diff
@@ -5,15 +5,16 @@
 from io import StringIO
 from pathlib import Path
 from typing import Any, Optional
 
 from pharmpy.deps import numpy as np
 from pharmpy.deps import pandas as pd
 from pharmpy.model import Model, Results
-from pharmpy.results import mfr
+from pharmpy.results import ModelfitResults
+from pharmpy.tools import read_modelfit_results
 from pharmpy.tools.psn_helpers import (
     arguments_from_command,
     options_from_command,
     tool_from_command,
 )
 
 
@@ -668,28 +669,29 @@
         degrees = row.delta_df
         model_name = row.model.replace(
             '-', ''
         )  # FIXME: The dash should not have been in the table!
         model_path = path / row.directory / f'{model_name}.mod'
         if not model_path.is_file():
             return np.nan
-        model = Model.create_model(model_path)
+        model = Model.parse_model(model_path)
+        results = read_modelfit_results(model_path)
         varpars = model.random_variables.free_symbols
         all_thetas = [param for param in model.parameters if param.symbol not in varpars]
         new_thetas = all_thetas[-degrees:]
         covariate_effects = {
-            param.name: _parameter_estimates(model, param.name) for param in new_thetas
+            param.name: _parameter_estimates(results, param.name) for param in new_thetas
         }
         return covariate_effects
 
     steps['covariate_effects'] = steps.apply(fn, axis=1)
 
 
-def _parameter_estimates(model: Model, parameter: str):
-    pe = mfr(model).parameter_estimates
+def _parameter_estimates(results: ModelfitResults, parameter: str):
+    pe = results.parameter_estimates
     assert pe is not None
     return pe[parameter]
 
 
 def psn_scm_results(path):
     """Create scm results from a PsN SCM run
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/simeval/results.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/simeval/results.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/simfit/results.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/simfit/results.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/tools/wrap.py` & `pharmpy-core-0.97.0/src/pharmpy/tools/wrap.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/visualization.py` & `pharmpy-core-0.97.0/src/pharmpy/visualization.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/workflows/__init__.py` & `pharmpy-core-0.97.0/src/pharmpy/workflows/__init__.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/workflows/args.py` & `pharmpy-core-0.97.0/src/pharmpy/workflows/args.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/workflows/call.py` & `pharmpy-core-0.97.0/src/pharmpy/workflows/call.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/workflows/dispatchers/local_dask.py` & `pharmpy-core-0.97.0/src/pharmpy/workflows/dispatchers/local_dask.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/workflows/execute.py` & `pharmpy-core-0.97.0/src/pharmpy/workflows/execute.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/workflows/log.py` & `pharmpy-core-0.97.0/src/pharmpy/workflows/log.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/workflows/model_database/baseclass.py` & `pharmpy-core-0.97.0/src/pharmpy/workflows/model_database/baseclass.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/workflows/model_database/local_directory.py` & `pharmpy-core-0.97.0/src/pharmpy/workflows/model_database/local_directory.py`

 * *Files 0% similar despite different names*

```diff
@@ -100,15 +100,15 @@
 
     def retrieve_model(self, name):
         filename = name + self.file_extension
         path = self.path / filename
         from pharmpy.model import Model
 
         try:
-            model = Model.create_model(path)
+            model = Model.parse_model(path)
         except FileNotFoundError:
             raise KeyError('Model cannot be found in database')
         model = get_modelfit_results(model, self.path)
         return model
 
     def retrieve_modelfit_results(self, name):
         return self.retrieve_model(name).modelfit_results
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy/workflows/model_database/null_database.py` & `pharmpy-core-0.97.0/src/pharmpy/workflows/model_database/null_database.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/workflows/optimize.py` & `pharmpy-core-0.97.0/src/pharmpy/workflows/optimize.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/workflows/tool_database/baseclass.py` & `pharmpy-core-0.97.0/src/pharmpy/workflows/tool_database/baseclass.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/workflows/tool_database/local_directory.py` & `pharmpy-core-0.97.0/src/pharmpy/workflows/tool_database/local_directory.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/workflows/tool_database/null_database.py` & `pharmpy-core-0.97.0/src/pharmpy/workflows/tool_database/null_database.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy/workflows/workflow.py` & `pharmpy-core-0.97.0/src/pharmpy/workflows/workflow.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/src/pharmpy_core.egg-info/PKG-INFO` & `pharmpy-core-0.97.0/src/pharmpy_core.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pharmpy-core
-Version: 0.96.0
+Version: 0.97.0
 Summary: Pharmacometric modeling
 Home-page: https://pharmpy.github.io
 Author: Rikard Nordgren
 Author-email: rikard.nordgren@farmaci.uu.se
 License: GNU Lesser General Public License v3 (LGPLv3)
 Project-URL: Bug Tracker, https://github.com/pharmpy/pharmpy/issues
 Project-URL: Source Code, https://github.com/pharmpy/pharmpy
@@ -40,14 +40,32 @@
 * A model abstraction as a foundation for higher level operations on models
 * Functions for manipulation of models, e.g. changing model components like elimination or absorption
 * Reading NONMEM models and results
 * Running models and complex workflows (with NONMEM or to some extent nlmixr)
 
 This is the `team behind Pharmpy <https://pharmpy.github.io/latest/contributors.html>`_
 
+0.97.0 (2023-06-28)
+-------------------
+
+New features
+============
+
+* Support BLQ transformations in RUVSearch
+* New tool structsearch and support for TMDD models
+* Add function ``modeling.set_direct_effect``
+* Add function ``modeling.add_effect_compartment``
+
+Changes
+=======
+
+* Reorganizing of modeling module
+* Support changing error model with BLQ transformation
+* Add ``max_iter`` option for RUVSearch
+
 0.96.0 (2023-05-26)
 -------------------
 
 Changes
 =======
 
 * Rename functions handling the precision matrix (was previously referring to information matrix which was an error)
```

### Comparing `pharmpy-core-0.96.0/src/pharmpy_core.egg-info/SOURCES.txt` & `pharmpy-core-0.97.0/src/pharmpy_core.egg-info/SOURCES.txt`

 * *Files 1% similar despite different names*

```diff
@@ -138,14 +138,16 @@
 src/pharmpy/model/distributions/__init__.py
 src/pharmpy/model/distributions/numeric.py
 src/pharmpy/model/distributions/symbolic.py
 src/pharmpy/model/external/__init__.py
 src/pharmpy/model/external/utils.py
 src/pharmpy/model/external/fcon/__init__.py
 src/pharmpy/model/external/fcon/model.py
+src/pharmpy/model/external/generic/__init__.py
+src/pharmpy/model/external/generic/generic.py
 src/pharmpy/model/external/nlmixr/__init__.py
 src/pharmpy/model/external/nlmixr/error_model.py
 src/pharmpy/model/external/nlmixr/ini.py
 src/pharmpy/model/external/nlmixr/model.py
 src/pharmpy/model/external/nlmixr/model_block.py
 src/pharmpy/model/external/nlmixr/name_mangle.py
 src/pharmpy/model/external/nlmixr/sanity_checks.py
@@ -187,42 +189,38 @@
 src/pharmpy/model/external/nonmem/records/grammars/simulation_record.lark
 src/pharmpy/model/external/nonmem/records/grammars/theta_record.lark
 src/pharmpy/model/external/rxode/__init__.py
 src/pharmpy/model/external/rxode/model.py
 src/pharmpy/modeling/__init__.py
 src/pharmpy/modeling/allometry.py
 src/pharmpy/modeling/basic_models.py
-src/pharmpy/modeling/block_rvs.py
 src/pharmpy/modeling/blq.py
 src/pharmpy/modeling/common.py
 src/pharmpy/modeling/compartments.py
 src/pharmpy/modeling/covariate_effect.py
 src/pharmpy/modeling/data.py
 src/pharmpy/modeling/error.py
 src/pharmpy/modeling/estimation.py
 src/pharmpy/modeling/estimation_steps.py
-src/pharmpy/modeling/eta_additions.py
-src/pharmpy/modeling/eta_transformations.py
 src/pharmpy/modeling/evaluation.py
 src/pharmpy/modeling/expressions.py
 src/pharmpy/modeling/help_functions.py
 src/pharmpy/modeling/iterators.py
 src/pharmpy/modeling/lrt.py
 src/pharmpy/modeling/math.py
 src/pharmpy/modeling/metabolite.py
 src/pharmpy/modeling/odes.py
 src/pharmpy/modeling/parameter_sampling.py
+src/pharmpy/modeling/parameter_variability.py
 src/pharmpy/modeling/parameters.py
+src/pharmpy/modeling/pd.py
 src/pharmpy/modeling/plots.py
-src/pharmpy/modeling/remove_iiv.py
-src/pharmpy/modeling/remove_iov.py
 src/pharmpy/modeling/results.py
 src/pharmpy/modeling/tmdd.py
 src/pharmpy/modeling/units.py
-src/pharmpy/modeling/update_inits.py
 src/pharmpy/modeling/write_csv.py
 src/pharmpy/modeling/example_models/moxo.csv
 src/pharmpy/modeling/example_models/moxo.mod
 src/pharmpy/modeling/example_models/pheno.cov
 src/pharmpy/modeling/example_models/pheno.datainfo
 src/pharmpy/modeling/example_models/pheno.dta
 src/pharmpy/modeling/example_models/pheno.ext
@@ -339,14 +337,17 @@
 src/pharmpy/tools/scm/__init__.py
 src/pharmpy/tools/scm/psn_wrapper.py
 src/pharmpy/tools/scm/results.py
 src/pharmpy/tools/simeval/__init__.py
 src/pharmpy/tools/simeval/results.py
 src/pharmpy/tools/simfit/__init__.py
 src/pharmpy/tools/simfit/results.py
+src/pharmpy/tools/structsearch/__init__.py
+src/pharmpy/tools/structsearch/tmdd.py
+src/pharmpy/tools/structsearch/tool.py
 src/pharmpy/workflows/__init__.py
 src/pharmpy/workflows/args.py
 src/pharmpy/workflows/call.py
 src/pharmpy/workflows/context.py
 src/pharmpy/workflows/execute.py
 src/pharmpy/workflows/log.py
 src/pharmpy/workflows/optimize.py
@@ -401,40 +402,35 @@
 tests/model/test_datainfo.py
 tests/model/test_estimation.py
 tests/model/test_model.py
 tests/model/test_parameter.py
 tests/model/test_random_variables.py
 tests/model/test_statements.py
 tests/modeling/__init__.py
-tests/modeling/test_add_covariate_effect.py
 tests/modeling/test_allometry.py
 tests/modeling/test_basic_models.py
-tests/modeling/test_block_rvs.py
 tests/modeling/test_blq.py
 tests/modeling/test_common.py
 tests/modeling/test_compartments.py
 tests/modeling/test_covariate_effect.py
 tests/modeling/test_data_funcs.py
-tests/modeling/test_distribution.py
 tests/modeling/test_error.py
 tests/modeling/test_estimation_steps.py
-tests/modeling/test_eta_additions.py
-tests/modeling/test_eta_transformations.py
 tests/modeling/test_evaluate.py
 tests/modeling/test_expressions.py
-tests/modeling/test_has_covariate_effect.py
 tests/modeling/test_help_functions.py
 tests/modeling/test_iterators.py
 tests/modeling/test_lrt.py
 tests/modeling/test_metabolite.py
-tests/modeling/test_modeling.py
+tests/modeling/test_odes.py
 tests/modeling/test_parameter_sampling.py
+tests/modeling/test_parameter_variability.py
 tests/modeling/test_parameters.py
+tests/modeling/test_pd.py
 tests/modeling/test_plots.py
-tests/modeling/test_remove_covariate_effect.py
 tests/modeling/test_results.py
 tests/modeling/test_tmdd.py
 tests/modeling/test_units.py
 tests/nonmem/conftest.py
 tests/nonmem/test_advan.py
 tests/nonmem/test_des.py
 tests/nonmem/test_fcon.py
@@ -476,14 +472,16 @@
 tests/testdata/nonmem/pheno_abbr_comments.mod
 tests/testdata/nonmem/pheno_block.mod
 tests/testdata/nonmem/pheno_clashing_symbols.mod
 tests/testdata/nonmem/pheno_etas.mod
 tests/testdata/nonmem/pheno_multivariate_piecewise.mod
 tests/testdata/nonmem/pheno_nm750.mod
 tests/testdata/nonmem/pheno_no_obs_1stID.dta
+tests/testdata/nonmem/pheno_pd.csv
+tests/testdata/nonmem/pheno_pd.mod
 tests/testdata/nonmem/pheno_rate.dta
 tests/testdata/nonmem/pheno_real.coi
 tests/testdata/nonmem/pheno_real.cor
 tests/testdata/nonmem/pheno_real.cov
 tests/testdata/nonmem/pheno_real.ext
 tests/testdata/nonmem/pheno_real.lst
 tests/testdata/nonmem/pheno_real.mod
@@ -693,14 +691,15 @@
 tests/testdata/nonmem/models/pef.csv
 tests/testdata/nonmem/models/pef.mod
 tests/testdata/nonmem/models/pheno_advan3_trans1.ext
 tests/testdata/nonmem/models/pheno_advan3_trans1.lst
 tests/testdata/nonmem/models/pheno_advan3_trans1.mod
 tests/testdata/nonmem/models/pheno_advan3_trans1.phi
 tests/testdata/nonmem/models/pheno_conc.mod
+tests/testdata/nonmem/models/pheno_des_assignments.mod
 tests/testdata/nonmem/models/pheno_dvid.csv
 tests/testdata/nonmem/models/pheno_dvid.mod
 tests/testdata/nonmem/models/pheno_noifs.coi
 tests/testdata/nonmem/models/pheno_noifs.cor
 tests/testdata/nonmem/models/pheno_noifs.cov
 tests/testdata/nonmem/models/pheno_noifs.ext
 tests/testdata/nonmem/models/pheno_noifs.lst
@@ -1027,14 +1026,15 @@
 tests/tools/test_rankfuncs.py
 tests/tools/test_run.py
 tests/tools/test_runtool.py
 tests/tools/test_ruvsearch.py
 tests/tools/test_scm.py
 tests/tools/test_simeval.py
 tests/tools/test_start_model.py
+tests/tools/test_structsearch.py
 tests/tools/test_summarize_individuals.py
 tests/tools/test_wrap.py
 tests/workflows/test_call.py
 tests/workflows/test_execute.py
 tests/workflows/test_log.py
 tests/workflows/test_model_database.py
 tests/workflows/test_task.py
```

### Comparing `pharmpy-core-0.96.0/tests/cli/test_cli.py` & `pharmpy-core-0.97.0/tests/cli/test_cli.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/conftest.py` & `pharmpy-core-0.97.0/tests/conftest.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/external/test_nlmixr.py` & `pharmpy-core-0.97.0/tests/external/test_nlmixr.py`

 * *Files 2% similar despite different names*

```diff
@@ -45,16 +45,16 @@
     model = convert_model(nmmodel)
     assert "EVID" in model.dataset.columns
 
 
 def test_w_error_model(testdata, load_model_for_test):
     nmmodel = load_model_for_test(testdata / 'nonmem' / 'models' / 'fviii6.mod')
     model = convert_model(nmmodel)
-    assert 'add_error <- THETA_3' in model.model_code
-    assert 'prop_error <- THETA_4' in model.model_code
+    assert 'add_error <- sqrt(THETA_3**2)' in model.model_code
+    assert 'prop_error <- sqrt(THETA_4**2)' in model.model_code
     assert "Y ~ add(add_error) + prop(prop_error)" in model.model_code
 
 
 def test_omega_same(testdata, load_model_for_test):
     nmmodel = load_model_for_test(testdata / 'nonmem' / 'models' / 'fviii6.mod')
     model = convert_model(nmmodel)
     assert "IOV_CL_7" in model.parameters
```

### Comparing `pharmpy-core-0.96.0/tests/external/test_rxode.py` & `pharmpy-core-0.97.0/tests/external/test_rxode.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/integration/conftest.py` & `pharmpy-core-0.97.0/tests/integration/conftest.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/integration/test_allometry.py` & `pharmpy-core-0.97.0/tests/integration/test_allometry.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/integration/test_amd.py` & `pharmpy-core-0.97.0/tests/integration/test_amd.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/integration/test_bootstrap.py` & `pharmpy-core-0.97.0/tests/integration/test_bootstrap.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/integration/test_common.py` & `pharmpy-core-0.97.0/tests/integration/test_common.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/integration/test_covsearch.py` & `pharmpy-core-0.97.0/tests/integration/test_covsearch.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/integration/test_estmethod.py` & `pharmpy-core-0.97.0/tests/integration/test_estmethod.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/integration/test_evaldesign.py` & `pharmpy-core-0.97.0/tests/integration/test_evaldesign.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/integration/test_fit.py` & `pharmpy-core-0.97.0/tests/integration/test_fit.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/integration/test_iivsearch.py` & `pharmpy-core-0.97.0/tests/integration/test_iivsearch.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/integration/test_iovsearch.py` & `pharmpy-core-0.97.0/tests/integration/test_iovsearch.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/integration/test_modelsearch.py` & `pharmpy-core-0.97.0/tests/integration/test_modelsearch.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/integration/test_resume.py` & `pharmpy-core-0.97.0/tests/integration/test_resume.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/internals/fs/test_lock.py` & `pharmpy-core-0.97.0/tests/internals/fs/test_lock.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/internals/module/test_lazy.py` & `pharmpy-core-0.97.0/tests/internals/module/test_lazy.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/internals/test_math.py` & `pharmpy-core-0.97.0/tests/internals/test_math.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/internals/test_parse.py` & `pharmpy-core-0.97.0/tests/internals/test_parse.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/model/test_datainfo.py` & `pharmpy-core-0.97.0/tests/model/test_datainfo.py`

 * *Files 0% similar despite different names*

```diff
@@ -168,15 +168,15 @@
 
 def test_json(tmp_path):
     col1 = ColumnInfo.create("ID", type='id', scale='nominal')
     col2 = ColumnInfo.create(
         "TIME", type='idv', scale='ratio', unit="h", descriptor='time after dose'
     )
     di = DataInfo.create([col1, col2])
-    correct = '{"columns": [{"name": "ID", "type": "id", "scale": "nominal", "continuous": false, "categories": null, "unit": "1", "datatype": "float64", "drop": false}, {"name": "TIME", "type": "idv", "scale": "ratio", "continuous": true, "categories": null, "unit": "hour", "datatype": "float64", "drop": false, "descriptor": "time after dose"}], "path": null, "separator": ","}'  # noqa: E501
+    correct = '{"columns": [{"name": "ID", "type": "id", "scale": "nominal", "continuous": false, "categories": null, "unit": "1", "datatype": "float64", "drop": false, "descriptor": null}, {"name": "TIME", "type": "idv", "scale": "ratio", "continuous": true, "categories": null, "unit": "hour", "datatype": "float64", "drop": false, "descriptor": "time after dose"}], "path": null, "separator": ","}'  # noqa: E501
     assert di.to_json() == correct
 
     newdi = DataInfo.from_json(correct)
     assert newdi == di
 
     di.to_json(tmp_path / 'my.datainfo')
     assert (tmp_path / 'my.datainfo').is_file()
```

### Comparing `pharmpy-core-0.96.0/tests/model/test_estimation.py` & `pharmpy-core-0.97.0/tests/model/test_estimation.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/model/test_model.py` & `pharmpy-core-0.97.0/tests/model/test_model.py`

 * *Files 3% similar despite different names*

```diff
@@ -76,7 +76,15 @@
 
     sset_new = sset_new.before_odes + x_assignment + sset_new.ode_system + sset_new.after_odes
     with pytest.raises(ValueError, match='Symbol x defined after being used'):
         model.replace(statements=sset_new)
 
     sset_new = sset.reassign(cl.symbol, cl.expression + sympy.Symbol('TIME'))
     model.replace(statements=sset_new)
+
+
+def test_dict(load_model_for_test, testdata):
+    path = testdata / 'nonmem' / 'pheno.mod'
+    model = load_model_for_test(path)
+    d = model.to_dict()
+    model2 = Model.from_dict(d)
+    assert model == model2
```

### Comparing `pharmpy-core-0.96.0/tests/model/test_parameter.py` & `pharmpy-core-0.97.0/tests/model/test_parameter.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/model/test_random_variables.py` & `pharmpy-core-0.97.0/tests/model/test_random_variables.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/model/test_statements.py` & `pharmpy-core-0.97.0/tests/model/test_statements.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/modeling/test_allometry.py` & `pharmpy-core-0.97.0/tests/modeling/test_allometry.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/modeling/test_blq.py` & `pharmpy-core-0.97.0/tests/modeling/test_blq.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,13 +1,14 @@
 import pytest
 
 from pharmpy.deps import numpy as np
 from pharmpy.model.model import update_datainfo
 from pharmpy.modeling import (
     create_joint_distribution,
+    remove_error_model,
     set_additive_error_model,
     set_combined_error_model,
     set_iiv_on_ruv,
     set_power_on_ruv,
     set_proportional_error_model,
     transform_blq,
 )
@@ -92,20 +93,37 @@
             'm4',
             set_proportional_error_model,
             set_combined_error_model,
             {},
             'SD = SQRT(F**2*SIGMA(1,1) + SIGMA(2,2))',
             ('Y = F + EPS(1)*F + EPS(2)', 'Y = (CUMD - CUMDZ)/(1 - CUMDZ)'),
         ),
+        (
+            'm4',
+            set_additive_error_model,
+            set_power_on_ruv,
+            {},
+            'SD = SQRT(F**(2*THETA(3))*SIGMA(1,1))',
+            ('Y = F + EPS(1)*F**THETA(3)', 'Y = (CUMD - CUMDZ)/(1 - CUMDZ)'),
+        ),
+        (
+            'm4',
+            set_proportional_error_model,
+            set_power_on_ruv,
+            {},
+            'SD = SQRT(IPREDADJ**(2*THETA(3))*SIGMA(1,1))',
+            ('Y = F + EPS(1)*IPREDADJ**THETA(3)', 'Y = (CUMD - CUMDZ)/(1 - CUMDZ)'),
+        ),
     ],
 )
 def test_update_blq_transformation(
     load_model_for_test, testdata, method, error_func_before, error_func_after, args, sd_ref, y_ref
 ):
     model = load_model_for_test(testdata / 'nonmem' / 'pheno.mod')
+    model = remove_error_model(model)
     model = error_func_before(model)
 
     model = transform_blq(model, method=method, lloq=0.1)
 
     model = error_func_after(model, **args)
 
     assert sd_ref in model.model_code
```

### Comparing `pharmpy-core-0.96.0/tests/modeling/test_common.py` & `pharmpy-core-0.97.0/tests/modeling/test_common.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/modeling/test_data_funcs.py` & `pharmpy-core-0.97.0/tests/modeling/test_data_funcs.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/modeling/test_error.py` & `pharmpy-core-0.97.0/tests/modeling/test_error.py`

 * *Files 1% similar despite different names*

```diff
@@ -1022,7 +1022,16 @@
 
         assert (
             rec_theta == f'$THETA (0,0.00469307) ; PTVCL\n'
             f'$THETA (0,1.00916) ; PTVV\n'
             f'$THETA (-.99,.1)\n'
             f'{theta_ref}\n'
         )
+
+
+def test_set_power_on_ruv_with_zero_protect(load_model_for_test, testdata):
+    model = load_model_for_test(testdata / 'nonmem' / 'pheno.mod')
+    model = remove_error_model(model)
+    model = set_proportional_error_model(model)
+    model = set_power_on_ruv(model)
+
+    assert 'F + EPS(1)*IPREDADJ**THETA(3)' in model.model_code
```

### Comparing `pharmpy-core-0.96.0/tests/modeling/test_estimation_steps.py` & `pharmpy-core-0.97.0/tests/modeling/test_estimation_steps.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/modeling/test_evaluate.py` & `pharmpy-core-0.97.0/tests/modeling/test_evaluate.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/modeling/test_expressions.py` & `pharmpy-core-0.97.0/tests/modeling/test_expressions.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/modeling/test_help_functions.py` & `pharmpy-core-0.97.0/tests/modeling/test_help_functions.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/modeling/test_iterators.py` & `pharmpy-core-0.97.0/tests/modeling/test_iterators.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/modeling/test_lrt.py` & `pharmpy-core-0.97.0/tests/modeling/test_lrt.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/modeling/test_metabolite.py` & `pharmpy-core-0.97.0/tests/modeling/test_metabolite.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/modeling/test_parameter_sampling.py` & `pharmpy-core-0.97.0/tests/modeling/test_parameter_sampling.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/modeling/test_plots.py` & `pharmpy-core-0.97.0/tests/modeling/test_plots.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/modeling/test_results.py` & `pharmpy-core-0.97.0/tests/modeling/test_results.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/nonmem/output/test_nonmem_results_file.py` & `pharmpy-core-0.97.0/tests/nonmem/output/test_nonmem_results_file.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/nonmem/records/test_abbreviated.py` & `pharmpy-core-0.97.0/tests/nonmem/records/test_abbreviated.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/nonmem/records/test_code.py` & `pharmpy-core-0.97.0/tests/nonmem/records/test_code.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/nonmem/records/test_data.py` & `pharmpy-core-0.97.0/tests/nonmem/records/test_data.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/nonmem/records/test_estimation_record.py` & `pharmpy-core-0.97.0/tests/nonmem/records/test_estimation_record.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/nonmem/records/test_factory.py` & `pharmpy-core-0.97.0/tests/nonmem/records/test_factory.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/nonmem/records/test_model_record.py` & `pharmpy-core-0.97.0/tests/nonmem/records/test_model_record.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/nonmem/records/test_omega.py` & `pharmpy-core-0.97.0/tests/nonmem/records/test_omega.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/nonmem/records/test_option_record.py` & `pharmpy-core-0.97.0/tests/nonmem/records/test_option_record.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/nonmem/records/test_problem.py` & `pharmpy-core-0.97.0/tests/nonmem/records/test_problem.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/nonmem/records/test_sizes.py` & `pharmpy-core-0.97.0/tests/nonmem/records/test_sizes.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/nonmem/records/test_theta.py` & `pharmpy-core-0.97.0/tests/nonmem/records/test_theta.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/nonmem/test_advan.py` & `pharmpy-core-0.97.0/tests/nonmem/test_advan.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/nonmem/test_des.py` & `pharmpy-core-0.97.0/tests/nonmem/test_des.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/nonmem/test_input.py` & `pharmpy-core-0.97.0/tests/nonmem/test_input.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/nonmem/test_modelfit_results.py` & `pharmpy-core-0.97.0/tests/nonmem/test_modelfit_results.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/nonmem/test_nonmem_model.py` & `pharmpy-core-0.97.0/tests/nonmem/test_nonmem_model.py`

 * *Files 0% similar despite different names*

```diff
@@ -1164,7 +1164,16 @@
 
 def test_zo(load_model_for_test, pheno_path):
     model = load_model_for_test(pheno_path)
     model = set_zero_order_input(model, "CENTRAL", 10)
     des = model.internals.control_stream.get_records("DES")[0]
     print(des)
     assert str(des) == "$DES\nDADT(1) = -A(1)*CL/V + 10\n"
+
+
+def test_des_assignments(load_model_for_test, testdata):
+    model = load_model_for_test(testdata / "nonmem" / "models" / "pheno_des_assignments.mod")
+
+    stats = model.statements
+
+    assert stats[3] == Assignment.create("KE", "CL/VC")
+    assert stats[4] == Assignment.create("EXTRA", "2 * A_CENTRAL(t)")
```

### Comparing `pharmpy-core-0.96.0/tests/nonmem/test_nonmem_table.py` & `pharmpy-core-0.97.0/tests/nonmem/test_nonmem_table.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/nonmem/test_parser.py` & `pharmpy-core-0.97.0/tests/nonmem/test_parser.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/nonmem/test_read.py` & `pharmpy-core-0.97.0/tests/nonmem/test_read.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/frem/results.json` & `pharmpy-core-0.97.0/tests/testdata/frem/results.json`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/DDMODEL00000130` & `pharmpy-core-0.97.0/tests/testdata/nonmem/DDMODEL00000130`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/Simulated_CMS_colistin_PK_data.csv` & `pharmpy-core-0.97.0/tests/testdata/nonmem/Simulated_CMS_colistin_PK_data.csv`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real.cov` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real.cov`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real.phi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_1.cov` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_1.cov`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_1.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_1.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_1.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_1.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_1.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_1.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_10.cov` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_10.cov`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_10.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_10.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_10.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_10.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_10.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_10.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_2.cov` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_2.cov`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_2.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_2.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_2.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_2.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_2.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_2.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_3.cov` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_3.cov`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_3.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_3.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_3.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_3.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_3.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_3.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_4.cov` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_4.cov`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_4.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_4.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_4.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_4.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_4.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_4.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_5.cov` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_5.cov`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_5.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_5.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_5.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_5.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_5.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_5.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_6.cov` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_6.cov`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_6.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_6.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_6.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_6.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_6.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_6.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_7.cov` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_7.cov`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_7.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_7.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_7.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_7.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_7.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_7.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_8.cov` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_8.cov`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_8.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_8.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_8.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_8.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_8.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_8.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_9.cov` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_9.cov`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_9.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_9.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_9.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_9.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_9.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/cdd_9.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_1.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_1.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_10.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_10.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_2.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_2.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_3.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_3.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_4.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_4.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_5.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_5.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_6.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_6.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_7.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_7.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_8.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_8.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_9.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/m1/rem_9.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/cdd/pheno_real_bin10/meta.yaml` & `pharmpy-core-0.97.0/tests/testdata/nonmem/cdd/pheno_real_bin10/meta.yaml`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/errors/control_stream_error.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/errors/control_stream_error.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/errors/est_step_warning.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/errors/est_step_warning.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/errors/estimate_near_boundary_warning.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/errors/estimate_near_boundary_warning.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/errors/failed_run.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/errors/failed_run.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/errors/no_header_error.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/errors/no_header_error.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/errors/no_header_error.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/errors/no_header_error.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/errors/rounding_error.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/errors/rounding_error.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/errors/run_interrupted.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/errors/run_interrupted.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/errors/zero_gradient_error.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/errors/zero_gradient_error.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/fcon/FCON` & `pharmpy-core-0.97.0/tests/testdata/nonmem/fcon/FCON`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/fcon/FDATA` & `pharmpy-core-0.97.0/tests/testdata/nonmem/fcon/FDATA`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno/frem_dataset.dta` & `pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno/frem_dataset.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno/model_3.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno/model_3.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno/model_3.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno/model_3.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno/model_3.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno/model_3.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno/model_3.phi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno/model_3.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno/model_3_input.phi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno/model_3_input.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno/model_4.cov` & `pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno/model_4.cov`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno/model_4.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno/model_4.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno/model_4.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno/model_4.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno/model_4.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno/model_4.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno/model_4.phi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno/model_4.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno/model_4_input.phi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno/model_4_input.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno_cat/frem_dataset.dta` & `pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno_cat/frem_dataset.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno_cat/model_4.cor` & `pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno_cat/model_4.cor`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno_cat/model_4.cov` & `pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno_cat/model_4.cov`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno_cat/model_4.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno_cat/model_4.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno_cat/model_4.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno_cat/model_4.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno_cat/model_4.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno_cat/model_4.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno_cat/model_4.phi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno_cat/model_4.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/frem/pheno_cat/model_4_input.phi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/frem/pheno_cat/model_4_input.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/linearize/linearize_dir1/pheno_linbase.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/linearize/linearize_dir1/pheno_linbase.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/linearize/linearize_dir1/pheno_linbase.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/linearize/linearize_dir1/pheno_linbase.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/linearize/linearize_dir1/pheno_linbase.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/linearize/linearize_dir1/pheno_linbase.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/linearize/linearize_dir1/pheno_linbase.phi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/linearize/linearize_dir1/pheno_linbase.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/linearize/linearize_dir1/scm_dir1/derivatives.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/linearize/linearize_dir1/scm_dir1/derivatives.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/linearize/linearize_dir1/scm_dir1/derivatives.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/linearize/linearize_dir1/scm_dir1/derivatives.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/linearize/linearize_dir1/scm_dir1/derivatives.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/linearize/linearize_dir1/scm_dir1/derivatives.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/linearize/linearize_dir1/scm_dir1/derivatives.phi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/linearize/linearize_dir1/scm_dir1/derivatives.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/covariance/pheno_nocovariance.coi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/covariance/pheno_nocovariance.coi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/covariance/pheno_nocovariance.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/covariance/pheno_nocovariance.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/covariance/pheno_nocovariance.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/covariance/pheno_nocovariance.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/covariance/pheno_nocovariance.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/covariance/pheno_nocovariance.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/multPROB/multEST/withSIM/multprobmix_nm730.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/multPROB/multEST/withSIM/multprobmix_nm730.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/multPROB/multEST/withSIM/multprobmix_nm730.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/multPROB/multEST/withSIM/multprobmix_nm730.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/anneal2_V7_30_beta.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/anneal2_V7_30_beta.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/pheno_multEST.dta` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/pheno_multEST.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/pheno_multEST.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/pheno_multEST.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/pheno_multEST.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/pheno_multEST.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/pheno_multEST.phi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/pheno_multEST.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/superid2_6_V7_30_beta.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/superid2_6_V7_30_beta.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/withBayes.cov` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/withBayes.cov`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/withBayes.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/withBayes.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/withBayes.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/withBayes.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/withBayes.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/withBayes.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/withBayes.phi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/multEST/noSIM/withBayes.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/noESTwithSIM/onlysim.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/noESTwithSIM/onlysim.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/noESTwithSIM/onlysim.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/noESTwithSIM/onlysim.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/UseCase7.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/UseCase7.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/example6b_V7_30_beta.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/example6b_V7_30_beta.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/hessian_error.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/hessian_error.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/large_s_matrix_cov_fail.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/large_s_matrix_cov_fail.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/maxeval0.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/maxeval0.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/maxeval0.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/maxeval0.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/maxeval0.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/maxeval0.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/maxeval3.cov` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/maxeval3.cov`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/maxeval3.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/maxeval3.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/maxeval3.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/maxeval3.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/maxeval3.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/maxeval3.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/maxeval3.phi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/maxeval3.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/mox_fail_nonp.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/mox_fail_nonp.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/mox_nocov_nonp.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/mox_nocov_nonp.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/near_bounds.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/near_bounds.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/near_bounds.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/near_bounds.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/near_bounds.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/near_bounds.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/nm710_fail_negV.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/nm710_fail_negV.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/pheno.dta` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/pheno.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/pheno.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/pheno.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/pheno.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/pheno.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/pheno.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/pheno.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/pheno.phi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/pheno.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/pheno_nonp.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/pheno_nonp.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/phenocorr.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/phenocorr.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/sparse_matrix_with_msfi.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/sparse_matrix_with_msfi.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/theo.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/theo.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/theo_nonp.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/theo_nonp.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/theo_withcov.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/theo_withcov.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/warfarin_ddmore.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/noSIM/warfarin_ddmore.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/withSIM/control3boot.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/withSIM/control3boot.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/withSIM/control3boot.res` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/onePROB/oneEST/withSIM/control3boot.res`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/simfit/sim-1.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/simfit/sim-1.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/simfit/sim-1.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/simfit/sim-1.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/simfit/sim-1.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/simfit/sim-1.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modelfit_results/simfit/sim-1.phi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modelfit_results/simfit/sim-1.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modeling/pheno_1transit.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modeling/pheno_1transit.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modeling/pheno_2transits.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modeling/pheno_2transits.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modeling/pheno_advan1.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modeling/pheno_advan1.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modeling/pheno_advan11.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modeling/pheno_advan11.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modeling/pheno_advan12.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modeling/pheno_advan12.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modeling/pheno_advan1_zero_order.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modeling/pheno_advan1_zero_order.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modeling/pheno_advan2.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modeling/pheno_advan2.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modeling/pheno_advan2_seq.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modeling/pheno_advan2_seq.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modeling/pheno_advan3.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modeling/pheno_advan3.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modeling/pheno_advan4.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modeling/pheno_advan4.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modeling/pheno_advan5_depot.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modeling/pheno_advan5_depot.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modeling/pheno_advan5_nodepot.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modeling/pheno_advan5_nodepot.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modeling/pheno_zero_order.csv` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modeling/pheno_zero_order.csv`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/modeling/transit_indirect_reabsorption.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/modeling/transit_indirect_reabsorption.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/fviii6.datainfo` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/fviii6.datainfo`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/fviii6.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/fviii6.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox1.cov` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox1.cov`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox1.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox1.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox1.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox1.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox1.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox1.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox1.phi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox1.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox2.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox2.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox2.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox2.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox2.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox2.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox2.phi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox2.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox_2comp.cov` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox_2comp.cov`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox_2comp.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox_2comp.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox_2comp.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox_2comp.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox_2comp.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox_2comp.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox_2comp.phi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox_2comp.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox_simulated_log.csv` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox_simulated_log.csv`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox_simulated_normal.csv` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox_simulated_normal.csv`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/mox_simulated_normal.datainfo` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/mox_simulated_normal.datainfo`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/moxo_simulated_amd.csv` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/moxo_simulated_amd.csv`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/moxo_simulated_amd.datainfo` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/moxo_simulated_amd.datainfo`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/mytab_mox2` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/mytab_mox2`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/pef.csv` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/pef.csv`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/pheno_advan3_trans1.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_advan3_trans1.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/pheno_advan3_trans1.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_advan3_trans1.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/pheno_advan3_trans1.phi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_advan3_trans1.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/pheno_dvid.csv` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_dvid.csv`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/pheno_dvid.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_dvid.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/pheno_noifs.coi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_noifs.coi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/pheno_noifs.cor` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_noifs.cor`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/pheno_noifs.cov` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_noifs.cov`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/pheno_noifs.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_noifs.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/pheno_noifs.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_noifs.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/pheno_noifs.phi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_noifs.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/pheno_trans1.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_trans1.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/pheno_trans1.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_trans1.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/models/pheno_trans1.phi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/models/pheno_trans1.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/pheno.datainfo` & `pharmpy-core-0.97.0/tests/testdata/nonmem/pheno.datainfo`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/pheno.dta` & `pharmpy-core-0.97.0/tests/testdata/nonmem/pheno.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/pheno.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/pheno.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/pheno.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/pheno.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/pheno.phi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/pheno.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_block.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_block.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_etas.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_etas.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_multivariate_piecewise.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_multivariate_piecewise.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_no_obs_1stID.dta` & `pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_no_obs_1stID.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_rate.dta` & `pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_rate.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_real.coi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_real.coi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_real.cor` & `pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_real.cor`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_real.cov` & `pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_real.cov`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_real.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_real.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_real.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_real.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_real.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_real.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_real.phi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_real.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_real.tab` & `pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_real.tab`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_real.xml` & `pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_real.xml`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_real_linbase.dta` & `pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_real_linbase.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_real_linbase.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_real_linbase.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_real_linbase.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_real_linbase.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_real_linbase.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_real_linbase.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_real_linbase.phi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_real_linbase.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/pheno_real_linbase.tab` & `pharmpy-core-0.97.0/tests/testdata/nonmem/pheno_real_linbase.tab`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/qa/add_etas_linbase.dta` & `pharmpy-core-0.97.0/tests/testdata/nonmem/qa/add_etas_linbase.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/qa/add_etas_linbase.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/qa/add_etas_linbase.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/qa/add_etas_linbase.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/qa/add_etas_linbase.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/qa/add_etas_linbase.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/qa/add_etas_linbase.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/qa/boxcox.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/qa/boxcox.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/qa/boxcox.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/qa/boxcox.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/qa/boxcox.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/qa/boxcox.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/qa/boxcox.phi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/qa/boxcox.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/qa/cdd_results.json` & `pharmpy-core-0.97.0/tests/testdata/nonmem/qa/cdd_results.json`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/qa/fullblock.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/qa/fullblock.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/qa/fullblock.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/qa/fullblock.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/qa/fullblock.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/qa/fullblock.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/qa/fullblock.phi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/qa/fullblock.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/qa/iov.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/qa/iov.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/qa/iov.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/qa/iov.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/qa/iov.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/qa/iov.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/qa/iov.phi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/qa/iov.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/qa/pheno_linbase.dta` & `pharmpy-core-0.97.0/tests/testdata/nonmem/qa/pheno_linbase.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/qa/pheno_linbase.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/qa/pheno_linbase.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/qa/pheno_linbase.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/qa/pheno_linbase.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/qa/pheno_linbase.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/qa/pheno_linbase.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/qa/pheno_linbase.phi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/qa/pheno_linbase.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/qa/resmod_results.json` & `pharmpy-core-0.97.0/tests/testdata/nonmem/qa/resmod_results.json`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/qa/scm_results.json` & `pharmpy-core-0.97.0/tests/testdata/nonmem/qa/scm_results.json`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/qa/simeval_results.json` & `pharmpy-core-0.97.0/tests/testdata/nonmem/qa/simeval_results.json`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/qa/tdist.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/qa/tdist.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/qa/tdist.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/qa/tdist.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/qa/tdist.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/qa/tdist.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/qa/tdist.phi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/qa/tdist.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/ruvsearch/mox3.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/ruvsearch/mox3.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/ruvsearch/mox3.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/ruvsearch/mox3.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/ruvsearch/mox3.mod` & `pharmpy-core-0.97.0/tests/testdata/nonmem/ruvsearch/mox3.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/ruvsearch/mox3.phi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/ruvsearch/mox3.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/ruvsearch/moxo_simulated_resmod.csv` & `pharmpy-core-0.97.0/tests/testdata/nonmem/ruvsearch/moxo_simulated_resmod.csv`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/ruvsearch/mytab` & `pharmpy-core-0.97.0/tests/testdata/nonmem/ruvsearch/mytab`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/scm/backward_dir1/meta.yaml` & `pharmpy-core-0.97.0/tests/testdata/nonmem/scm/backward_dir1/meta.yaml`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/scm/backward_dir1/scmlog.txt` & `pharmpy-core-0.97.0/tests/testdata/nonmem/scm/backward_dir1/scmlog.txt`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/scm/gofofv_dir1/scmlog.txt` & `pharmpy-core-0.97.0/tests/testdata/nonmem/scm/gofofv_dir1/scmlog.txt`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/scm/localmin.logf` & `pharmpy-core-0.97.0/tests/testdata/nonmem/scm/localmin.logf`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/scm/log_steps/backward_ofv_1.txt` & `pharmpy-core-0.97.0/tests/testdata/nonmem/scm/log_steps/backward_ofv_1.txt`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/scm/log_steps/forward_ofv_1.txt` & `pharmpy-core-0.97.0/tests/testdata/nonmem/scm/log_steps/forward_ofv_1.txt`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/scm/log_steps/forward_pval_1.txt` & `pharmpy-core-0.97.0/tests/testdata/nonmem/scm/log_steps/forward_pval_1.txt`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/scm/log_steps/forward_pval_2.txt` & `pharmpy-core-0.97.0/tests/testdata/nonmem/scm/log_steps/forward_pval_2.txt`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/scm/log_steps/forward_pval_3.txt` & `pharmpy-core-0.97.0/tests/testdata/nonmem/scm/log_steps/forward_pval_3.txt`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/scm/mergeofv_dir1/meta.yaml` & `pharmpy-core-0.97.0/tests/testdata/nonmem/scm/mergeofv_dir1/meta.yaml`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/scm/mergeofv_dir1/scmlog.txt` & `pharmpy-core-0.97.0/tests/testdata/nonmem/scm/mergeofv_dir1/scmlog.txt`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/scm/mergeofv_dir2/meta.yaml` & `pharmpy-core-0.97.0/tests/testdata/nonmem/scm/mergeofv_dir2/meta.yaml`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/scm/mergeofv_dir2/scmlog.txt` & `pharmpy-core-0.97.0/tests/testdata/nonmem/scm/mergeofv_dir2/scmlog.txt`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/scm/meta.yaml` & `pharmpy-core-0.97.0/tests/testdata/nonmem/scm/meta.yaml`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/scm/onlyforward_dir1/meta.yaml` & `pharmpy-core-0.97.0/tests/testdata/nonmem/scm/onlyforward_dir1/meta.yaml`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/scm/onlyforward_dir1/scmlog.txt` & `pharmpy-core-0.97.0/tests/testdata/nonmem/scm/onlyforward_dir1/scmlog.txt`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/scm/scm_dir1/scmlog.txt` & `pharmpy-core-0.97.0/tests/testdata/nonmem/scm/scm_dir1/scmlog.txt`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/scm/scmplus_dir1/scmlog.txt` & `pharmpy-core-0.97.0/tests/testdata/nonmem/scm/scmplus_dir1/scmlog.txt`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/sdtab1` & `pharmpy-core-0.97.0/tests/testdata/nonmem/sdtab1`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/secondary_parameters/pheno.cov` & `pharmpy-core-0.97.0/tests/testdata/nonmem/secondary_parameters/pheno.cov`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/secondary_parameters/pheno.dta` & `pharmpy-core-0.97.0/tests/testdata/nonmem/secondary_parameters/pheno.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/secondary_parameters/pheno.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/secondary_parameters/pheno.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/secondary_parameters/pheno.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/secondary_parameters/pheno.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/secondary_parameters/pheno.phi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/secondary_parameters/pheno.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/secondary_parameters/run1.cov` & `pharmpy-core-0.97.0/tests/testdata/nonmem/secondary_parameters/run1.cov`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/secondary_parameters/run1.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/secondary_parameters/run1.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/secondary_parameters/run1.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/secondary_parameters/run1.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/secondary_parameters/run1.phi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/secondary_parameters/run1.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/secondary_parameters/run2.cov` & `pharmpy-core-0.97.0/tests/testdata/nonmem/secondary_parameters/run2.cov`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/secondary_parameters/run2.ext` & `pharmpy-core-0.97.0/tests/testdata/nonmem/secondary_parameters/run2.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/secondary_parameters/run2.lst` & `pharmpy-core-0.97.0/tests/testdata/nonmem/secondary_parameters/run2.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/nonmem/secondary_parameters/run2.phi` & `pharmpy-core-0.97.0/tests/testdata/nonmem/secondary_parameters/run2.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/pheno_data.csv` & `pharmpy-core-0.97.0/tests/testdata/pheno_data.csv`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/est_data0.dta` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/est_data0.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/est_data1.dta` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/est_data1.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/est_data2.dta` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/est_data2.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/est_data3.dta` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/est_data3.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model0.cor` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model0.cor`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model0.cov` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model0.cov`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model0.ext` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model0.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model0.lst` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model0.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model0.phi` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model0.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model1.cor` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model1.cor`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model1.cov` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model1.cov`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model1.ext` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model1.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model1.lst` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model1.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model1.phi` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model1.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model2.cor` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model2.cor`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model2.cov` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model2.cov`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model2.ext` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model2.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model2.lst` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model2.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model2.phi` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model2.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model3.cor` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model3.cor`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model3.cov` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model3.cov`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model3.ext` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model3.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model3.lst` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model3.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/est_model3.phi` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/est_model3.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/pred_model0.ext` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/pred_model0.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/pred_model0.lst` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/pred_model0.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/pred_model0.phi` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/pred_model0.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/pred_model1.ext` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/pred_model1.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/pred_model1.lst` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/pred_model1.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/pred_model1.phi` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/pred_model1.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/pred_model2.ext` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/pred_model2.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/pred_model2.lst` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/pred_model2.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/pred_model2.phi` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/pred_model2.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/pred_model3.cor` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/pred_model3.cor`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/pred_model3.cov` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/pred_model3.cov`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/pred_model3.ext` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/pred_model3.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/pred_model3.lst` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/pred_model3.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/m1/pred_model3.phi` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/m1/pred_model3.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/meta.yaml` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/meta.yaml`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/pred_data0.dta` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/pred_data0.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/pred_data1.dta` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/pred_data1.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/pred_data2.dta` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/pred_data2.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/pred_data3.dta` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/pred_data3.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/crossval_dir1/version_and_option_info.txt` & `pharmpy-core-0.97.0/tests/testdata/psn/crossval_dir1/version_and_option_info.txt`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/final_models/model_4.ext` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/final_models/model_4.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/final_models/model_4.lst` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/final_models/model_4.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/final_models/model_4.mod` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/final_models/model_4.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/final_models/model_4.phi` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/final_models/model_4.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/final_models/model_4_input.phi` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/final_models/model_4_input.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/frem_dataset.dta` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/frem_dataset.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/frem_results.csv` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/frem_results.csv`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/filter_data_model.ext` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/filter_data_model.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/filter_data_model.lst` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/filter_data_model.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/filter_data_model.mod` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/filter_data_model.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/filter_data_model.phi` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/filter_data_model.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/filtered_plus_type0.dta` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/filtered_plus_type0.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_1.cov` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_1.cov`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_1.ext` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_1.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_1.lst` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_1.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_1.phi` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_1.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_1b.phi` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_1b.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_2.cor` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_2.cor`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_2.cov` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_2.cov`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_2.ext` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_2.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_2.lst` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_2.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_2.mod` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_2.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_2.phi` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_2.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_2_input.phi` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_2_input.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_3.ext` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_3.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_3.lst` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_3.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_3.mod` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_3.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_3.phi` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_3.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_3_input.phi` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_3_input.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_3b.ext` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_3b.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_3b.lst` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_3b.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_3b.mod` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_3b.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_3b.phi` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_3b.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/m1/model_3b_input.phi` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/m1/model_3b_input.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/meta.yaml` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/meta.yaml`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/proposal_density.cov` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/proposal_density.cov`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/frem_dir1/version_and_option_info.txt` & `pharmpy-core-0.97.0/tests/testdata/psn/frem_dir1/version_and_option_info.txt`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/qa_dir1/linearize_run/results.json` & `pharmpy-core-0.97.0/tests/testdata/psn/qa_dir1/linearize_run/results.json`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/qa_dir1/linearize_run/scm_dir1/derivatives.ext` & `pharmpy-core-0.97.0/tests/testdata/psn/qa_dir1/linearize_run/scm_dir1/derivatives.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/qa_dir1/linearize_run/scm_dir1/derivatives.lst` & `pharmpy-core-0.97.0/tests/testdata/psn/qa_dir1/linearize_run/scm_dir1/derivatives.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/qa_dir1/linearize_run/scm_dir1/derivatives.mod` & `pharmpy-core-0.97.0/tests/testdata/psn/qa_dir1/linearize_run/scm_dir1/derivatives.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/qa_dir1/linearize_run/scm_dir1/derivatives.phi` & `pharmpy-core-0.97.0/tests/testdata/psn/qa_dir1/linearize_run/scm_dir1/derivatives.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/qa_dir1/linearize_run/scm_dir1/extra_table` & `pharmpy-core-0.97.0/tests/testdata/psn/qa_dir1/linearize_run/scm_dir1/extra_table`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/qa_dir1/pheno_real_linbase.dta` & `pharmpy-core-0.97.0/tests/testdata/psn/qa_dir1/pheno_real_linbase.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/qa_dir1/pheno_real_linbase.ext` & `pharmpy-core-0.97.0/tests/testdata/psn/qa_dir1/pheno_real_linbase.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/qa_dir1/pheno_real_linbase.lst` & `pharmpy-core-0.97.0/tests/testdata/psn/qa_dir1/pheno_real_linbase.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/qa_dir1/pheno_real_linbase.mod` & `pharmpy-core-0.97.0/tests/testdata/psn/qa_dir1/pheno_real_linbase.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/qa_dir1/pheno_real_linbase.phi` & `pharmpy-core-0.97.0/tests/testdata/psn/qa_dir1/pheno_real_linbase.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/qa_dir1/results_summary.yaml` & `pharmpy-core-0.97.0/tests/testdata/psn/qa_dir1/results_summary.yaml`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/resmod_dir1/resmod_results.csv` & `pharmpy-core-0.97.0/tests/testdata/psn/resmod_dir1/resmod_results.csv`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/resmod_dir2/resmod_results.csv` & `pharmpy-core-0.97.0/tests/testdata/psn/resmod_dir2/resmod_results.csv`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/orig_pred.dta` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/orig_pred.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/original.cor` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/original.cor`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/original.cov` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/original.cov`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/original.ext` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/original.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/original.mod` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/original.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/original.phi` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/original.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/original_res_table.dta` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/original_res_table.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/pheno.dta` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/pheno.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-1.ext` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-1.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-1.lst` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-1.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-1.phi` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-1.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-2.ext` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-2.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-2.lst` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-2.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-2.phi` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-2.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-3.ext` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-3.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-3.lst` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-3.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-3.phi` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-3.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-4.ext` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-4.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-4.lst` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-4.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-4.phi` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-4.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-5.ext` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-5.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-5.lst` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-5.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-5.phi` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-5.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-6.ext` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-6.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-6.lst` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-6.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-6.phi` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-6.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-7.ext` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-7.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-7.lst` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-7.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-7.phi` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-7.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-8.ext` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-8.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-8.lst` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-8.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim-8.phi` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim-8.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim_res_table-1.dta` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim_res_table-1.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim_res_table-2.dta` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim_res_table-2.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim_res_table-3.dta` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim_res_table-3.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim_res_table-4.dta` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim_res_table-4.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim_res_table-5.dta` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim_res_table-5.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim_res_table-6.dta` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim_res_table-6.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim_res_table-7.dta` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim_res_table-7.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/m1/sim_res_table-8.dta` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/m1/sim_res_table-8.dta`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/psn/simeval_dir1/summary_cwres.csv` & `pharmpy-core-0.97.0/tests/testdata/psn/simeval_dir1/summary_cwres.csv`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/allometry_results.json` & `pharmpy-core-0.97.0/tests/testdata/results/allometry_results.json`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/amd_results.json` & `pharmpy-core-0.97.0/tests/testdata/results/amd_results.json`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/bootstrap_results.json` & `pharmpy-core-0.97.0/tests/testdata/results/bootstrap_results.json`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/cdd_results.json` & `pharmpy-core-0.97.0/tests/testdata/results/cdd_results.json`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/covsearch_results.json` & `pharmpy-core-0.97.0/tests/testdata/results/covsearch_results.json`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/estmethod_results.json` & `pharmpy-core-0.97.0/tests/testdata/results/estmethod_results.json`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/iivsearch_results.json` & `pharmpy-core-0.97.0/tests/testdata/results/iivsearch_results.json`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/iovsearch_results.json` & `pharmpy-core-0.97.0/tests/testdata/results/iovsearch_results.json`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/linearize_results.json` & `pharmpy-core-0.97.0/tests/testdata/results/linearize_results.json`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/metadata.json` & `pharmpy-core-0.97.0/tests/testdata/results/metadata.json`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/modelsearch_results.json` & `pharmpy-core-0.97.0/tests/testdata/results/modelsearch_results.json`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/qa_results.json` & `pharmpy-core-0.97.0/tests/testdata/results/qa_results.json`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/ruvsearch_results.json` & `pharmpy-core-0.97.0/tests/testdata/results/ruvsearch_results.json`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/metadata.json` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/metadata.json`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/.datasets/input_model.csv` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/.datasets/input_model.csv`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/.datasets/input_model.datainfo` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/.datasets/input_model.datainfo`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/input_model/.pharmpy/results.json` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/input_model/.pharmpy/results.json`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/input_model/input_model.mod` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/input_model/input_model.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/.pharmpy/results.json` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/.pharmpy/results.json`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/modelsearch_run1.ext` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/modelsearch_run1.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/modelsearch_run1.lst` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/modelsearch_run1.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/modelsearch_run1.mod` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/modelsearch_run1.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/modelsearch_run1.phi` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/modelsearch_run1.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/mytab_mox1` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/mytab_mox1`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/stdout` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run1/stdout`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/.pharmpy/results.json` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/.pharmpy/results.json`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/modelsearch_run2.ext` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/modelsearch_run2.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/modelsearch_run2.lst` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/modelsearch_run2.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/modelsearch_run2.mod` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/modelsearch_run2.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/modelsearch_run2.phi` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/modelsearch_run2.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/mytab_mox2` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/mytab_mox2`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/stdout` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run2/stdout`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/.pharmpy/results.json` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/.pharmpy/results.json`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/modelsearch_run3.ext` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/modelsearch_run3.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/modelsearch_run3.lst` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/modelsearch_run3.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/modelsearch_run3.mod` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/modelsearch_run3.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/modelsearch_run3.phi` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/modelsearch_run3.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/mytab_mox3` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/mytab_mox3`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/stdout` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run3/stdout`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/.pharmpy/results.json` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/.pharmpy/results.json`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/modelsearch_run4.ext` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/modelsearch_run4.ext`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/modelsearch_run4.lst` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/modelsearch_run4.lst`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/modelsearch_run4.mod` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/modelsearch_run4.mod`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/modelsearch_run4.phi` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/modelsearch_run4.phi`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/mytab_mox4` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/mytab_mox4`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/stdout` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/models/modelsearch_run4/stdout`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/results.csv` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/results.csv`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/testdata/results/tool_databases/modelsearch/results.json` & `pharmpy-core-0.97.0/tests/testdata/results/tool_databases/modelsearch/results.json`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/tools/test_allometry.py` & `pharmpy-core-0.97.0/tests/tools/test_allometry.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/tools/test_amd.py` & `pharmpy-core-0.97.0/tests/tools/test_amd.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/tools/test_bootstrap.py` & `pharmpy-core-0.97.0/tests/tools/test_bootstrap.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/tools/test_cdd.py` & `pharmpy-core-0.97.0/tests/tools/test_cdd.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/tools/test_covsearch.py` & `pharmpy-core-0.97.0/tests/tools/test_covsearch.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/tools/test_estmethod.py` & `pharmpy-core-0.97.0/tests/tools/test_estmethod.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/tools/test_exports.py` & `pharmpy-core-0.97.0/tests/tools/test_exports.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/tools/test_frem.py` & `pharmpy-core-0.97.0/tests/tools/test_frem.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/tools/test_iivsearch.py` & `pharmpy-core-0.97.0/tests/tools/test_iivsearch.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/tools/test_iovsearch.py` & `pharmpy-core-0.97.0/tests/tools/test_iovsearch.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/tools/test_linearize.py` & `pharmpy-core-0.97.0/tests/tools/test_linearize.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/tools/test_mfl.py` & `pharmpy-core-0.97.0/tests/tools/test_mfl.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/tools/test_ml.py` & `pharmpy-core-0.97.0/tests/tools/test_ml.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/tools/test_modelsearch.py` & `pharmpy-core-0.97.0/tests/tools/test_modelsearch.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/tools/test_qa.py` & `pharmpy-core-0.97.0/tests/tools/test_qa.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/tools/test_rankfuncs.py` & `pharmpy-core-0.97.0/tests/tools/test_rankfuncs.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/tools/test_run.py` & `pharmpy-core-0.97.0/tests/tools/test_run.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/tools/test_runtool.py` & `pharmpy-core-0.97.0/tests/tools/test_runtool.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/tools/test_ruvsearch.py` & `pharmpy-core-0.97.0/tests/tools/test_ruvsearch.py`

 * *Files 11% similar despite different names*

```diff
@@ -1,15 +1,17 @@
+import shutil
 from dataclasses import replace
 
 import pytest
 
-from pharmpy.modeling import remove_covariance_step
+from pharmpy.internals.fs.cwd import chdir
+from pharmpy.modeling import remove_covariance_step, transform_blq
 from pharmpy.tools import read_modelfit_results
 from pharmpy.tools.ruvsearch.results import psn_resmod_results
-from pharmpy.tools.ruvsearch.tool import create_workflow, validate_input
+from pharmpy.tools.ruvsearch.tool import _create_dataset, create_workflow, validate_input
 from pharmpy.workflows import Workflow
 
 
 def test_resmod_results(testdata):
     res = psn_resmod_results(testdata / 'psn' / 'resmod_dir1')
     assert list(res.cwres_models['dOFV']) == [
         -1.31,
@@ -57,14 +59,50 @@
     model = load_model_for_test(testdata / 'nonmem' / 'ruvsearch' / 'mox3.mod')
     res = read_modelfit_results(testdata / 'nonmem' / 'ruvsearch' / 'mox3.mod')
     model = model.replace(modelfit_results=res)
     model = remove_covariance_step(model)
     validate_input(model=model)
 
 
+def test_create_dataset(load_model_for_test, testdata, tmp_path):
+    model = load_model_for_test(testdata / 'nonmem' / 'ruvsearch' / 'mox3.mod')
+    res = read_modelfit_results(testdata / 'nonmem' / 'ruvsearch' / 'mox3.mod')
+    model = model.replace(modelfit_results=res)
+
+    df = _create_dataset(model)
+
+    assert len(df) == 1006
+    assert (df['DV'] != 0).all()
+
+    with chdir(tmp_path):
+        for path in (testdata / 'nonmem' / 'ruvsearch').glob('mox3.*'):
+            shutil.copy2(path, tmp_path)
+        shutil.copy2(testdata / 'nonmem' / 'ruvsearch' / 'moxo_simulated_resmod.csv', tmp_path)
+        shutil.copy2(testdata / 'nonmem' / 'ruvsearch' / 'mytab', tmp_path)
+
+        # Introduce 0 in CWRES to mimic rows BLQ
+        with open('mytab') as f:
+            mytab_new = f.read().replace('-2.4366E+00', '0.0000E+00')
+
+        with open('mytab', 'w') as f:
+            f.write(mytab_new)
+
+        model = load_model_for_test('mox3.mod')
+        res = read_modelfit_results('mox3.mod')
+
+        model = model.replace(modelfit_results=res)
+
+        model = transform_blq(model, method='m3', lloq=0.05)
+
+        df = _create_dataset(model)
+
+        assert len(df) == 1005
+        assert (df['DV'] != 0).all()
+
+
 @pytest.mark.parametrize(
     ('model_path', 'arguments', 'exception', 'match'),
     [
         (
             None,
             dict(groups=3.1415),
             TypeError,
```

### Comparing `pharmpy-core-0.96.0/tests/tools/test_scm.py` & `pharmpy-core-0.97.0/tests/tools/test_scm.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/tools/test_start_model.py` & `pharmpy-core-0.97.0/tests/tools/test_start_model.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/tools/test_summarize_individuals.py` & `pharmpy-core-0.97.0/tests/tools/test_summarize_individuals.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/tools/test_wrap.py` & `pharmpy-core-0.97.0/tests/tools/test_wrap.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/workflows/test_call.py` & `pharmpy-core-0.97.0/tests/workflows/test_call.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/workflows/test_execute.py` & `pharmpy-core-0.97.0/tests/workflows/test_execute.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/workflows/test_model_database.py` & `pharmpy-core-0.97.0/tests/workflows/test_model_database.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tests/workflows/test_workflow.py` & `pharmpy-core-0.97.0/tests/workflows/test_workflow.py`

 * *Files identical despite different names*

### Comparing `pharmpy-core-0.96.0/tox.ini` & `pharmpy-core-0.97.0/tox.ini`

 * *Files identical despite different names*


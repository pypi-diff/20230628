# Comparing `tmp/openmim-0.3.7.tar.gz` & `tmp/openmim-0.3.8.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/openmim-0.3.7.tar", last modified: Tue Mar 21 11:09:40 2023, max compression
+gzip compressed data, was "openmim-0.3.8.tar", last modified: Wed Jun 28 07:41:28 2023, max compression
```

## Comparing `openmim-0.3.7.tar` & `openmim-0.3.8.tar`

### file list

```diff
@@ -1,45 +1,58 @@
-drwxr-xr-x   0 runner    (1001) docker     (116)        0 2023-03-21 11:09:40.000000 openmim-0.3.7/
--rw-r--r--   0 runner    (1001) docker     (116)       27 2023-03-21 11:09:37.000000 openmim-0.3.7/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (116)    18679 2023-03-21 11:09:40.000000 openmim-0.3.7/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (116)    14950 2023-03-21 11:09:37.000000 openmim-0.3.7/README.md
-drwxr-xr-x   0 runner    (1001) docker     (116)        0 2023-03-21 11:09:40.000000 openmim-0.3.7/mim/
--rw-r--r--   0 runner    (1001) docker     (116)      844 2023-03-21 11:09:37.000000 openmim-0.3.7/mim/__init__.py
--rw-r--r--   0 runner    (1001) docker     (116)      159 2023-03-21 11:09:37.000000 openmim-0.3.7/mim/__main__.py
--rw-r--r--   0 runner    (1001) docker     (116)     2968 2023-03-21 11:09:37.000000 openmim-0.3.7/mim/cli.py
-drwxr-xr-x   0 runner    (1001) docker     (116)        0 2023-03-21 11:09:40.000000 openmim-0.3.7/mim/click/
--rw-r--r--   0 runner    (1001) docker     (116)      460 2023-03-21 11:09:37.000000 openmim-0.3.7/mim/click/__init__.py
--rw-r--r--   0 runner    (1001) docker     (116)      790 2023-03-21 11:09:37.000000 openmim-0.3.7/mim/click/autocompletion.py
--rw-r--r--   0 runner    (1001) docker     (116)     1637 2023-03-21 11:09:37.000000 openmim-0.3.7/mim/click/compat.py
--rw-r--r--   0 runner    (1001) docker     (116)     4868 2023-03-21 11:09:37.000000 openmim-0.3.7/mim/click/customcommand.py
--rw-r--r--   0 runner    (1001) docker     (116)     2249 2023-03-21 11:09:37.000000 openmim-0.3.7/mim/click/option.py
--rw-r--r--   0 runner    (1001) docker     (116)      190 2023-03-21 11:09:37.000000 openmim-0.3.7/mim/click/utils.py
-drwxr-xr-x   0 runner    (1001) docker     (116)        0 2023-03-21 11:09:40.000000 openmim-0.3.7/mim/commands/
--rw-r--r--   0 runner    (1001) docker     (116)      453 2023-03-21 11:09:37.000000 openmim-0.3.7/mim/commands/__init__.py
--rw-r--r--   0 runner    (1001) docker     (116)     5118 2023-03-21 11:09:37.000000 openmim-0.3.7/mim/commands/download.py
--rw-r--r--   0 runner    (1001) docker     (116)    16187 2023-03-21 11:09:37.000000 openmim-0.3.7/mim/commands/gridsearch.py
--rw-r--r--   0 runner    (1001) docker     (116)    14725 2023-03-21 11:09:37.000000 openmim-0.3.7/mim/commands/install.py
--rw-r--r--   0 runner    (1001) docker     (116)     2855 2023-03-21 11:09:37.000000 openmim-0.3.7/mim/commands/list.py
--rw-r--r--   0 runner    (1001) docker     (116)     5711 2023-03-21 11:09:37.000000 openmim-0.3.7/mim/commands/run.py
--rw-r--r--   0 runner    (1001) docker     (116)    27632 2023-03-21 11:09:37.000000 openmim-0.3.7/mim/commands/search.py
--rw-r--r--   0 runner    (1001) docker     (116)    10686 2023-03-21 11:09:37.000000 openmim-0.3.7/mim/commands/test.py
--rw-r--r--   0 runner    (1001) docker     (116)     9928 2023-03-21 11:09:37.000000 openmim-0.3.7/mim/commands/train.py
--rw-r--r--   0 runner    (1001) docker     (116)     2404 2023-03-21 11:09:37.000000 openmim-0.3.7/mim/commands/uninstall.py
-drwxr-xr-x   0 runner    (1001) docker     (116)        0 2023-03-21 11:09:40.000000 openmim-0.3.7/mim/utils/
--rw-r--r--   0 runner    (1001) docker     (116)     1967 2023-03-21 11:09:37.000000 openmim-0.3.7/mim/utils/__init__.py
--rw-r--r--   0 runner    (1001) docker     (116)     1273 2023-03-21 11:09:37.000000 openmim-0.3.7/mim/utils/default.py
--rw-r--r--   0 runner    (1001) docker     (116)     1071 2023-03-21 11:09:37.000000 openmim-0.3.7/mim/utils/progress_bars.py
--rw-r--r--   0 runner    (1001) docker     (116)    16351 2023-03-21 11:09:37.000000 openmim-0.3.7/mim/utils/utils.py
--rw-r--r--   0 runner    (1001) docker     (116)      500 2023-03-21 11:09:37.000000 openmim-0.3.7/mim/version.py
-drwxr-xr-x   0 runner    (1001) docker     (116)        0 2023-03-21 11:09:40.000000 openmim-0.3.7/openmim.egg-info/
--rw-r--r--   0 runner    (1001) docker     (116)    18679 2023-03-21 11:09:40.000000 openmim-0.3.7/openmim.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (116)      815 2023-03-21 11:09:40.000000 openmim-0.3.7/openmim.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (116)        1 2023-03-21 11:09:40.000000 openmim-0.3.7/openmim.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (116)       55 2023-03-21 11:09:40.000000 openmim-0.3.7/openmim.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (116)      325 2023-03-21 11:09:40.000000 openmim-0.3.7/openmim.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (116)        4 2023-03-21 11:09:40.000000 openmim-0.3.7/openmim.egg-info/top_level.txt
-drwxr-xr-x   0 runner    (1001) docker     (116)        0 2023-03-21 11:09:40.000000 openmim-0.3.7/requirements/
--rw-r--r--   0 runner    (1001) docker     (116)      171 2023-03-21 11:09:37.000000 openmim-0.3.7/requirements/docs.txt
--rw-r--r--   0 runner    (1001) docker     (116)       67 2023-03-21 11:09:37.000000 openmim-0.3.7/requirements/install.txt
--rw-r--r--   0 runner    (1001) docker     (116)       35 2023-03-21 11:09:37.000000 openmim-0.3.7/requirements/tests.txt
--rw-r--r--   0 runner    (1001) docker     (116)      590 2023-03-21 11:09:40.000000 openmim-0.3.7/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (116)     3921 2023-03-21 11:09:37.000000 openmim-0.3.7/setup.py
+drwxrwxr-x   0 zhouzaida (900020515) zhouzaida (900020515)        0 2023-06-28 07:41:28.343375 openmim-0.3.8/
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)    11408 2023-06-28 07:39:52.000000 openmim-0.3.8/LICENSE
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)       27 2023-06-28 07:39:52.000000 openmim-0.3.8/MANIFEST.in
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)    15568 2023-06-28 07:41:28.343375 openmim-0.3.8/PKG-INFO
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)    15249 2023-06-28 07:39:52.000000 openmim-0.3.8/README.md
+drwxrwxr-x   0 zhouzaida (900020515) zhouzaida (900020515)        0 2023-06-28 07:41:28.338375 openmim-0.3.8/mim/
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      844 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/__init__.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      159 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/__main__.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     2968 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/cli.py
+drwxrwxr-x   0 zhouzaida (900020515) zhouzaida (900020515)        0 2023-06-28 07:41:28.339375 openmim-0.3.8/mim/click/
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      460 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/click/__init__.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      790 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/click/autocompletion.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     1637 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/click/compat.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     4868 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/click/customcommand.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     2249 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/click/option.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      190 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/click/utils.py
+drwxrwxr-x   0 zhouzaida (900020515) zhouzaida (900020515)        0 2023-06-28 07:41:28.340375 openmim-0.3.8/mim/commands/
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      453 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/commands/__init__.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     5118 2023-06-28 07:40:52.000000 openmim-0.3.8/mim/commands/download.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)    16187 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/commands/gridsearch.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)    14727 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/commands/install.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     2855 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/commands/list.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     5711 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/commands/run.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)    27632 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/commands/search.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)    10686 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/commands/test.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     9928 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/commands/train.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     2404 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/commands/uninstall.py
+drwxrwxr-x   0 zhouzaida (900020515) zhouzaida (900020515)        0 2023-06-28 07:41:28.340375 openmim-0.3.8/mim/utils/
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     1967 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/utils/__init__.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     1297 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/utils/default.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     1071 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/utils/progress_bars.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)    16351 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/utils/utils.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      500 2023-06-28 07:40:52.000000 openmim-0.3.8/mim/version.py
+drwxrwxr-x   0 zhouzaida (900020515) zhouzaida (900020515)        0 2023-06-28 07:41:28.341375 openmim-0.3.8/openmim.egg-info/
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)    15568 2023-06-28 07:41:28.000000 openmim-0.3.8/openmim.egg-info/PKG-INFO
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     1056 2023-06-28 07:41:28.000000 openmim-0.3.8/openmim.egg-info/SOURCES.txt
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)        1 2023-06-28 07:41:28.000000 openmim-0.3.8/openmim.egg-info/dependency_links.txt
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)       36 2023-06-28 07:41:28.000000 openmim-0.3.8/openmim.egg-info/entry_points.txt
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      325 2023-06-28 07:41:28.000000 openmim-0.3.8/openmim.egg-info/requires.txt
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)        4 2023-06-28 07:41:28.000000 openmim-0.3.8/openmim.egg-info/top_level.txt
+drwxrwxr-x   0 zhouzaida (900020515) zhouzaida (900020515)        0 2023-06-28 07:41:28.341375 openmim-0.3.8/requirements/
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      171 2023-06-28 07:39:52.000000 openmim-0.3.8/requirements/docs.txt
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)       67 2023-06-28 07:40:52.000000 openmim-0.3.8/requirements/install.txt
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)       35 2023-06-28 07:39:52.000000 openmim-0.3.8/requirements/tests.txt
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      590 2023-06-28 07:41:28.344375 openmim-0.3.8/setup.cfg
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     3921 2023-06-28 07:39:52.000000 openmim-0.3.8/setup.py
+drwxrwxr-x   0 zhouzaida (900020515) zhouzaida (900020515)        0 2023-06-28 07:41:28.343375 openmim-0.3.8/tests/
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     2232 2023-06-28 07:39:52.000000 openmim-0.3.8/tests/test_download.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     2952 2023-06-28 07:39:52.000000 openmim-0.3.8/tests/test_gridsearch.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     2750 2023-06-28 07:39:52.000000 openmim-0.3.8/tests/test_install.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     1224 2023-06-28 07:39:52.000000 openmim-0.3.8/tests/test_list.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     2111 2023-06-28 07:39:52.000000 openmim-0.3.8/tests/test_run.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     4352 2023-06-28 07:39:52.000000 openmim-0.3.8/tests/test_search.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     1939 2023-06-28 07:39:52.000000 openmim-0.3.8/tests/test_test.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     1783 2023-06-28 07:39:52.000000 openmim-0.3.8/tests/test_train.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     2614 2023-06-28 07:39:52.000000 openmim-0.3.8/tests/test_uninstall.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     1655 2023-06-28 07:39:52.000000 openmim-0.3.8/tests/test_utils.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      286 2023-06-28 07:39:52.000000 openmim-0.3.8/tests/test_version.py
```

### filetype from file(1)

```diff
@@ -1 +1 @@
-POSIX tar archive (GNU)
+POSIX tar archive
```

### Comparing `openmim-0.3.7/PKG-INFO` & `openmim-0.3.8/README.md`

 * *Files 17% similar despite different names*

```diff
@@ -1,437 +1,425 @@
-Metadata-Version: 2.1
-Name: openmim
-Version: 0.3.7
-Summary: MIM Installs OpenMMLab packages
-Home-page: https://github.com/open-mmlab/mim
-Author: MIM Authors
-Author-email: openmmlab@gmail.com
-License: UNKNOWN
-Description: # MIM: MIM Installs OpenMMLab Packages
-        
-        MIM provides a unified interface for launching and installing OpenMMLab projects and their extensions, and managing the OpenMMLab model zoo.
-        
-        ## Major Features
-        
-        - **Package Management**
-        
-          You can use MIM to manage OpenMMLab codebases, install or uninstall them conveniently.
-        
-        - **Model Management**
-        
-          You can use MIM to manage OpenMMLab model zoo, e.g., download checkpoints by name, search checkpoints that meet specific criteria.
-        
-        - **Unified Entrypoint for Scripts**
-        
-          You can execute any script provided by all OpenMMLab codebases with unified commands. Train, test and inference become easier than ever. Besides, you can use `gridsearch` command for vanilla hyper-parameter search.
-        
-        ## License
-        
-        This project is released under the [Apache 2.0 license](LICENSE).
-        
-        ## Changelog
-        
-        v0.1.1 was released in 13/6/2021.
-        
-        ## Customization
-        
-        You can use `.mimrc` for customization. Now we support customize default values of each sub-command. Please refer to [customization.md](docs/en/customization.md) for details.
-        
-        ## Build custom projects with MIM
-        
-        We provide some examples of how to build custom projects based on OpenMMLAB codebases and MIM in [MIM-Example](https://github.com/open-mmlab/mim-example).
-        Without worrying about copying codes and scripts from existing codebases, users can focus on developing new components and MIM helps integrate and run the new project.
-        
-        ## Installation
-        
-        Please refer to [installation.md](docs/en/installation.md) for installation.
-        
-        ## Command
-        
-        <details>
-        <summary>1. install</summary>
-        
-        - command
-        
-          ```bash
-          # install latest version of mmcv-full
-          > mim install mmcv-full  # wheel
-          # install 1.5.0
-          > mim install mmcv-full==1.5.0
-        
-          # install latest version of mmcls
-          > mim install mmcls
-          # install master branch
-          > mim install git+https://github.com/open-mmlab/mmclassification.git
-          # install local repo
-          > git clone https://github.com/open-mmlab/mmclassification.git
-          > cd mmclassification
-          > mim install .
-        
-          # install extension based on OpenMMLab
-          mim install git+https://github.com/xxx/mmcls-project.git
-          ```
-        
-        - api
-        
-          ```python
-          from mim import install
-        
-          # install mmcv
-          install('mmcv-full')
-        
-          # install mmcls will automatically install mmcv if it is not installed
-          install('mmcls')
-        
-          # install extension based on OpenMMLab
-          install('git+https://github.com/xxx/mmcls-project.git')
-          ```
-        
-        </details>
-        
-        <details>
-        <summary>2. uninstall</summary>
-        
-        - command
-        
-          ```bash
-          # uninstall mmcv
-          > mim uninstall mmcv-full
-        
-          # uninstall mmcls
-          > mim uninstall mmcls
-          ```
-        
-        - api
-        
-          ```python
-          from mim import uninstall
-        
-          # uninstall mmcv
-          uninstall('mmcv-full')
-        
-          # uninstall mmcls
-          uninstall('mmcls')
-          ```
-        
-        </details>
-        
-        <details>
-        <summary>3. list</summary>
-        
-        - command
-        
-          ```bash
-          > mim list
-          > mim list --all
-          ```
-        
-        - api
-        
-          ```python
-          from mim import list_package
-        
-          list_package()
-          list_package(True)
-          ```
-        
-        </details>
-        
-        <details>
-        <summary>4. search</summary>
-        
-        - command
-        
-          ```bash
-          > mim search mmcls
-          > mim search mmcls==0.23.0 --remote
-          > mim search mmcls --config resnet18_8xb16_cifar10
-          > mim search mmcls --model resnet
-          > mim search mmcls --dataset cifar-10
-          > mim search mmcls --valid-field
-          > mim search mmcls --condition 'batch_size>45,epochs>100'
-          > mim search mmcls --condition 'batch_size>45 epochs>100'
-          > mim search mmcls --condition '128<batch_size<=256'
-          > mim search mmcls --sort batch_size epochs
-          > mim search mmcls --field epochs batch_size weight
-          > mim search mmcls --exclude-field weight paper
-          ```
-        
-        - api
-        
-          ```python
-          from mim import get_model_info
-        
-          get_model_info('mmcls')
-          get_model_info('mmcls==0.23.0', local=False)
-          get_model_info('mmcls', models=['resnet'])
-          get_model_info('mmcls', training_datasets=['cifar-10'])
-          get_model_info('mmcls', filter_conditions='batch_size>45,epochs>100')
-          get_model_info('mmcls', filter_conditions='batch_size>45 epochs>100')
-          get_model_info('mmcls', filter_conditions='128<batch_size<=256')
-          get_model_info('mmcls', sorted_fields=['batch_size', 'epochs'])
-          get_model_info('mmcls', shown_fields=['epochs', 'batch_size', 'weight'])
-          ```
-        
-        </details>
-        
-        <details>
-        <summary>5. download</summary>
-        
-        - command
-        
-          ```bash
-          > mim download mmcls --config resnet18_8xb16_cifar10
-          > mim download mmcls --config resnet18_8xb16_cifar10 --dest .
-          ```
-        
-        - api
-        
-          ```python
-          from mim import download
-        
-          download('mmcls', ['resnet18_8xb16_cifar10'])
-          download('mmcls', ['resnet18_8xb16_cifar10'], dest_root='.')
-          ```
-        
-        </details>
-        
-        <details>
-        <summary>6. train</summary>
-        
-        - command
-        
-          ```bash
-          # Train models on a single server with CPU by setting `gpus` to 0 and
-          # 'launcher' to 'none' (if applicable). The training script of the
-          # corresponding codebase will fail if it doesn't support CPU training.
-          > mim train mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 0
-          # Train models on a single server with one GPU
-          > mim train mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 1
-          # Train models on a single server with 4 GPUs and pytorch distributed
-          > mim train mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 4 \
-              --launcher pytorch
-          # Train models on a slurm HPC with one 8-GPU node
-          > mim train mmcls resnet101_b16x8_cifar10.py --launcher slurm --gpus 8 \
-              --gpus-per-node 8 --partition partition_name --work-dir tmp
-          # Print help messages of sub-command train
-          > mim train -h
-          # Print help messages of sub-command train and the training script of mmcls
-          > mim train mmcls -h
-          ```
-        
-        - api
-        
-          ```python
-          from mim import train
-        
-          train(repo='mmcls', config='resnet18_8xb16_cifar10.py', gpus=0,
-                other_args='--work-dir tmp')
-          train(repo='mmcls', config='resnet18_8xb16_cifar10.py', gpus=1,
-                other_args='--work-dir tmp')
-          train(repo='mmcls', config='resnet18_8xb16_cifar10.py', gpus=4,
-                launcher='pytorch', other_args='--work-dir tmp')
-          train(repo='mmcls', config='resnet18_8xb16_cifar10.py', gpus=8,
-                launcher='slurm', gpus_per_node=8, partition='partition_name',
-                other_args='--work-dir tmp')
-          ```
-        
-        </details>
-        
-        <details>
-        <summary>7. test</summary>
-        
-        - command
-        
-          ```bash
-          # Test models on a single server with 1 GPU, report accuracy
-          > mim test mmcls resnet101_b16x8_cifar10.py --checkpoint \
-              tmp/epoch_3.pth --gpus 1 --metrics accuracy
-          # Test models on a single server with 1 GPU, save predictions
-          > mim test mmcls resnet101_b16x8_cifar10.py --checkpoint \
-              tmp/epoch_3.pth --gpus 1 --out tmp.pkl
-          # Test models on a single server with 4 GPUs, pytorch distributed,
-          # report accuracy
-          > mim test mmcls resnet101_b16x8_cifar10.py --checkpoint \
-              tmp/epoch_3.pth --gpus 4 --launcher pytorch --metrics accuracy
-          # Test models on a slurm HPC with one 8-GPU node, report accuracy
-          > mim test mmcls resnet101_b16x8_cifar10.py --checkpoint \
-              tmp/epoch_3.pth --gpus 8 --metrics accuracy --partition \
-              partition_name --gpus-per-node 8 --launcher slurm
-          # Print help messages of sub-command test
-          > mim test -h
-          # Print help messages of sub-command test and the testing script of mmcls
-          > mim test mmcls -h
-          ```
-        
-        - api
-        
-          ```python
-          from mim import test
-          test(repo='mmcls', config='resnet101_b16x8_cifar10.py',
-               checkpoint='tmp/epoch_3.pth', gpus=1, other_args='--metrics accuracy')
-          test(repo='mmcls', config='resnet101_b16x8_cifar10.py',
-               checkpoint='tmp/epoch_3.pth', gpus=1, other_args='--out tmp.pkl')
-          test(repo='mmcls', config='resnet101_b16x8_cifar10.py',
-               checkpoint='tmp/epoch_3.pth', gpus=4, launcher='pytorch',
-               other_args='--metrics accuracy')
-          test(repo='mmcls', config='resnet101_b16x8_cifar10.py',
-               checkpoint='tmp/epoch_3.pth', gpus=8, partition='partition_name',
-               launcher='slurm', gpus_per_node=8, other_args='--metrics accuracy')
-          ```
-        
-        </details>
-        
-        <details>
-        <summary>8. run</summary>
-        
-        - command
-        
-          ```bash
-          # Get the Flops of a model
-          > mim run mmcls get_flops resnet101_b16x8_cifar10.py
-          # Publish a model
-          > mim run mmcls publish_model input.pth output.pth
-          # Train models on a slurm HPC with one GPU
-          > srun -p partition --gres=gpu:1 mim run mmcls train \
-              resnet101_b16x8_cifar10.py --work-dir tmp
-          # Test models on a slurm HPC with one GPU, report accuracy
-          > srun -p partition --gres=gpu:1 mim run mmcls test \
-              resnet101_b16x8_cifar10.py tmp/epoch_3.pth --metrics accuracy
-          # Print help messages of sub-command run
-          > mim run -h
-          # Print help messages of sub-command run, list all available scripts in
-          # codebase mmcls
-          > mim run mmcls -h
-          # Print help messages of sub-command run, print the help message of
-          # training script in mmcls
-          > mim run mmcls train -h
-          ```
-        
-        - api
-        
-          ```python
-          from mim import run
-        
-          run(repo='mmcls', command='get_flops',
-              other_args='resnet101_b16x8_cifar10.py')
-          run(repo='mmcls', command='publish_model',
-              other_args='input.pth output.pth')
-          run(repo='mmcls', command='train',
-              other_args='resnet101_b16x8_cifar10.py --work-dir tmp')
-          run(repo='mmcls', command='test',
-              other_args='resnet101_b16x8_cifar10.py tmp/epoch_3.pth --metrics accuracy')
-          ```
-        
-        </details>
-        
-        <details>
-        <summary>9. gridsearch</summary>
-        
-        - command
-        
-          ```bash
-          # Parameter search on a single server with CPU by setting `gpus` to 0 and
-          # 'launcher' to 'none' (if applicable). The training script of the
-          # corresponding codebase will fail if it doesn't support CPU training.
-          > mim gridsearch mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 0 \
-              --search-args '--optimizer.lr 1e-2 1e-3'
-          # Parameter search with on a single server with one GPU, search learning
-          # rate
-          > mim gridsearch mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 1 \
-              --search-args '--optimizer.lr 1e-2 1e-3'
-          # Parameter search with on a single server with one GPU, search
-          # weight_decay
-          > mim gridsearch mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 1 \
-              --search-args '--optimizer.weight_decay 1e-3 1e-4'
-          # Parameter search with on a single server with one GPU, search learning
-          # rate and weight_decay
-          > mim gridsearch mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 1 \
-              --search-args '--optimizer.lr 1e-2 1e-3 --optimizer.weight_decay 1e-3 \
-              1e-4'
-          # Parameter search on a slurm HPC with one 8-GPU node, search learning
-          # rate and weight_decay
-          > mim gridsearch mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 8 \
-              --partition partition_name --gpus-per-node 8 --launcher slurm \
-              --search-args '--optimizer.lr 1e-2 1e-3 --optimizer.weight_decay 1e-3 \
-              1e-4'
-          # Parameter search on a slurm HPC with one 8-GPU node, search learning
-          # rate and weight_decay, max parallel jobs is 2
-          > mim gridsearch mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 8 \
-              --partition partition_name --gpus-per-node 8 --launcher slurm \
-              --max-jobs 2 --search-args '--optimizer.lr 1e-2 1e-3 \
-              --optimizer.weight_decay 1e-3 1e-4'
-          # Print the help message of sub-command search
-          > mim gridsearch -h
-          # Print the help message of sub-command search and the help message of the
-          # training script of codebase mmcls
-          > mim gridsearch mmcls -h
-          ```
-        
-        - api
-        
-          ```python
-          from mim import gridsearch
-        
-          gridsearch(repo='mmcls', config='resnet101_b16x8_cifar10.py', gpus=0,
-                     search_args='--optimizer.lr 1e-2 1e-3',
-                     other_args='--work-dir tmp')
-          gridsearch(repo='mmcls', config='resnet101_b16x8_cifar10.py', gpus=1,
-                     search_args='--optimizer.lr 1e-2 1e-3',
-                     other_args='--work-dir tmp')
-          gridsearch(repo='mmcls', config='resnet101_b16x8_cifar10.py', gpus=1,
-                     search_args='--optimizer.weight_decay 1e-3 1e-4',
-                     other_args='--work-dir tmp')
-          gridsearch(repo='mmcls', config='resnet101_b16x8_cifar10.py', gpus=1,
-                     search_args='--optimizer.lr 1e-2 1e-3 --optimizer.weight_decay'
-                                 '1e-3 1e-4',
-                     other_args='--work-dir tmp')
-          gridsearch(repo='mmcls', config='resnet101_b16x8_cifar10.py', gpus=8,
-                     partition='partition_name', gpus_per_node=8, launcher='slurm',
-                     search_args='--optimizer.lr 1e-2 1e-3 --optimizer.weight_decay'
-                                 ' 1e-3 1e-4',
-                     other_args='--work-dir tmp')
-          gridsearch(repo='mmcls', config='resnet101_b16x8_cifar10.py', gpus=8,
-                     partition='partition_name', gpus_per_node=8, launcher='slurm',
-                     max_workers=2,
-                     search_args='--optimizer.lr 1e-2 1e-3 --optimizer.weight_decay'
-                                 ' 1e-3 1e-4',
-                     other_args='--work-dir tmp')
-          ```
-        
-        </details>
-        
-        ## Contributing
-        
-        We appreciate all contributions to improve mim. Please refer to [CONTRIBUTING.md](https://github.com/open-mmlab/mmcv/blob/master/CONTRIBUTING.md) for the contributing guideline.
-        
-        ## License
-        
-        This project is released under the [Apache 2.0 license](LICENSE).
-        
-        ## Projects in OpenMMLab
-        
-        - [MMCV](https://github.com/open-mmlab/mmcv): OpenMMLab foundational library for computer vision.
-        - [MIM](https://github.com/open-mmlab/mim): MIM installs OpenMMLab packages.
-        - [MMClassification](https://github.com/open-mmlab/mmclassification): OpenMMLab image classification toolbox and benchmark.
-        - [MMDetection](https://github.com/open-mmlab/mmdetection): OpenMMLab detection toolbox and benchmark.
-        - [MMDetection3D](https://github.com/open-mmlab/mmdetection3d): OpenMMLab's next-generation platform for general 3D object detection.
-        - [MMRotate](https://github.com/open-mmlab/mmrotate): OpenMMLab rotated object detection toolbox and benchmark.
-        - [MMSegmentation](https://github.com/open-mmlab/mmsegmentation): OpenMMLab semantic segmentation toolbox and benchmark.
-        - [MMOCR](https://github.com/open-mmlab/mmocr): OpenMMLab text detection, recognition, and understanding toolbox.
-        - [MMPose](https://github.com/open-mmlab/mmpose): OpenMMLab pose estimation toolbox and benchmark.
-        - [MMHuman3D](https://github.com/open-mmlab/mmhuman3d): OpenMMLab 3D human parametric model toolbox and benchmark.
-        - [MMSelfSup](https://github.com/open-mmlab/mmselfsup): OpenMMLab self-supervised learning toolbox and benchmark.
-        - [MMRazor](https://github.com/open-mmlab/mmrazor): OpenMMLab model compression toolbox and benchmark.
-        - [MMFewShot](https://github.com/open-mmlab/mmfewshot): OpenMMLab fewshot learning toolbox and benchmark.
-        - [MMAction2](https://github.com/open-mmlab/mmaction2): OpenMMLab's next-generation action understanding toolbox and benchmark.
-        - [MMTracking](https://github.com/open-mmlab/mmtracking): OpenMMLab video perception toolbox and benchmark.
-        - [MMFlow](https://github.com/open-mmlab/mmflow): OpenMMLab optical flow toolbox and benchmark.
-        - [MMEditing](https://github.com/open-mmlab/mmediting): OpenMMLab image and video editing toolbox.
-        - [MMGeneration](https://github.com/open-mmlab/mmgeneration): OpenMMLab image and video generative models toolbox.
-        - [MMDeploy](https://github.com/open-mmlab/mmdeploy): OpenMMLab model deployment framework.
-        
-Platform: UNKNOWN
-Requires-Python: >=3.6
-Description-Content-Type: text/markdown
-Provides-Extra: all
-Provides-Extra: tests
+# MIM: MIM Installs OpenMMLab Packages
+
+MIM provides a unified interface for launching and installing OpenMMLab projects and their extensions, and managing the OpenMMLab model zoo.
+
+## Major Features
+
+- **Package Management**
+
+  You can use MIM to manage OpenMMLab codebases, install or uninstall them conveniently.
+
+- **Model Management**
+
+  You can use MIM to manage OpenMMLab model zoo, e.g., download checkpoints by name, search checkpoints that meet specific criteria.
+
+- **Unified Entrypoint for Scripts**
+
+  You can execute any script provided by all OpenMMLab codebases with unified commands. Train, test and inference become easier than ever. Besides, you can use `gridsearch` command for vanilla hyper-parameter search.
+
+## License
+
+This project is released under the [Apache 2.0 license](LICENSE).
+
+## Changelog
+
+v0.1.1 was released in 13/6/2021.
+
+## Customization
+
+You can use `.mimrc` for customization. Now we support customize default values of each sub-command. Please refer to [customization.md](docs/en/customization.md) for details.
+
+## Build custom projects with MIM
+
+We provide some examples of how to build custom projects based on OpenMMLAB codebases and MIM in [MIM-Example](https://github.com/open-mmlab/mim-example).
+Without worrying about copying codes and scripts from existing codebases, users can focus on developing new components and MIM helps integrate and run the new project.
+
+## Installation
+
+Please refer to [installation.md](docs/en/installation.md) for installation.
+
+## Command
+
+<details>
+<summary>1. install</summary>
+
+- command
+
+  ```bash
+  # install latest version of mmcv-full
+  > mim install mmcv-full  # wheel
+  # install 1.5.0
+  > mim install mmcv-full==1.5.0
+
+  # install latest version of mmcls
+  > mim install mmcls
+  # install master branch
+  > mim install git+https://github.com/open-mmlab/mmclassification.git
+  # install local repo
+  > git clone https://github.com/open-mmlab/mmclassification.git
+  > cd mmclassification
+  > mim install .
+
+  # install extension based on OpenMMLab
+  mim install git+https://github.com/xxx/mmcls-project.git
+  ```
+
+- api
+
+  ```python
+  from mim import install
+
+  # install mmcv
+  install('mmcv-full')
+
+  # install mmcls will automatically install mmcv if it is not installed
+  install('mmcls')
+
+  # install extension based on OpenMMLab
+  install('git+https://github.com/xxx/mmcls-project.git')
+  ```
+
+</details>
+
+<details>
+<summary>2. uninstall</summary>
+
+- command
+
+  ```bash
+  # uninstall mmcv
+  > mim uninstall mmcv-full
+
+  # uninstall mmcls
+  > mim uninstall mmcls
+  ```
+
+- api
+
+  ```python
+  from mim import uninstall
+
+  # uninstall mmcv
+  uninstall('mmcv-full')
+
+  # uninstall mmcls
+  uninstall('mmcls')
+  ```
+
+</details>
+
+<details>
+<summary>3. list</summary>
+
+- command
+
+  ```bash
+  > mim list
+  > mim list --all
+  ```
+
+- api
+
+  ```python
+  from mim import list_package
+
+  list_package()
+  list_package(True)
+  ```
+
+</details>
+
+<details>
+<summary>4. search</summary>
+
+- command
+
+  ```bash
+  > mim search mmcls
+  > mim search mmcls==0.23.0 --remote
+  > mim search mmcls --config resnet18_8xb16_cifar10
+  > mim search mmcls --model resnet
+  > mim search mmcls --dataset cifar-10
+  > mim search mmcls --valid-field
+  > mim search mmcls --condition 'batch_size>45,epochs>100'
+  > mim search mmcls --condition 'batch_size>45 epochs>100'
+  > mim search mmcls --condition '128<batch_size<=256'
+  > mim search mmcls --sort batch_size epochs
+  > mim search mmcls --field epochs batch_size weight
+  > mim search mmcls --exclude-field weight paper
+  ```
+
+- api
+
+  ```python
+  from mim import get_model_info
+
+  get_model_info('mmcls')
+  get_model_info('mmcls==0.23.0', local=False)
+  get_model_info('mmcls', models=['resnet'])
+  get_model_info('mmcls', training_datasets=['cifar-10'])
+  get_model_info('mmcls', filter_conditions='batch_size>45,epochs>100')
+  get_model_info('mmcls', filter_conditions='batch_size>45 epochs>100')
+  get_model_info('mmcls', filter_conditions='128<batch_size<=256')
+  get_model_info('mmcls', sorted_fields=['batch_size', 'epochs'])
+  get_model_info('mmcls', shown_fields=['epochs', 'batch_size', 'weight'])
+  ```
+
+</details>
+
+<details>
+<summary>5. download</summary>
+
+- command
+
+  ```bash
+  > mim download mmcls --config resnet18_8xb16_cifar10
+  > mim download mmcls --config resnet18_8xb16_cifar10 --dest .
+  ```
+
+- api
+
+  ```python
+  from mim import download
+
+  download('mmcls', ['resnet18_8xb16_cifar10'])
+  download('mmcls', ['resnet18_8xb16_cifar10'], dest_root='.')
+  ```
+
+</details>
+
+<details>
+<summary>6. train</summary>
+
+- command
+
+  ```bash
+  # Train models on a single server with CPU by setting `gpus` to 0 and
+  # 'launcher' to 'none' (if applicable). The training script of the
+  # corresponding codebase will fail if it doesn't support CPU training.
+  > mim train mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 0
+  # Train models on a single server with one GPU
+  > mim train mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 1
+  # Train models on a single server with 4 GPUs and pytorch distributed
+  > mim train mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 4 \
+      --launcher pytorch
+  # Train models on a slurm HPC with one 8-GPU node
+  > mim train mmcls resnet101_b16x8_cifar10.py --launcher slurm --gpus 8 \
+      --gpus-per-node 8 --partition partition_name --work-dir tmp
+  # Print help messages of sub-command train
+  > mim train -h
+  # Print help messages of sub-command train and the training script of mmcls
+  > mim train mmcls -h
+  ```
+
+- api
+
+  ```python
+  from mim import train
+
+  train(repo='mmcls', config='resnet18_8xb16_cifar10.py', gpus=0,
+        other_args='--work-dir tmp')
+  train(repo='mmcls', config='resnet18_8xb16_cifar10.py', gpus=1,
+        other_args='--work-dir tmp')
+  train(repo='mmcls', config='resnet18_8xb16_cifar10.py', gpus=4,
+        launcher='pytorch', other_args='--work-dir tmp')
+  train(repo='mmcls', config='resnet18_8xb16_cifar10.py', gpus=8,
+        launcher='slurm', gpus_per_node=8, partition='partition_name',
+        other_args='--work-dir tmp')
+  ```
+
+</details>
+
+<details>
+<summary>7. test</summary>
+
+- command
+
+  ```bash
+  # Test models on a single server with 1 GPU, report accuracy
+  > mim test mmcls resnet101_b16x8_cifar10.py --checkpoint \
+      tmp/epoch_3.pth --gpus 1 --metrics accuracy
+  # Test models on a single server with 1 GPU, save predictions
+  > mim test mmcls resnet101_b16x8_cifar10.py --checkpoint \
+      tmp/epoch_3.pth --gpus 1 --out tmp.pkl
+  # Test models on a single server with 4 GPUs, pytorch distributed,
+  # report accuracy
+  > mim test mmcls resnet101_b16x8_cifar10.py --checkpoint \
+      tmp/epoch_3.pth --gpus 4 --launcher pytorch --metrics accuracy
+  # Test models on a slurm HPC with one 8-GPU node, report accuracy
+  > mim test mmcls resnet101_b16x8_cifar10.py --checkpoint \
+      tmp/epoch_3.pth --gpus 8 --metrics accuracy --partition \
+      partition_name --gpus-per-node 8 --launcher slurm
+  # Print help messages of sub-command test
+  > mim test -h
+  # Print help messages of sub-command test and the testing script of mmcls
+  > mim test mmcls -h
+  ```
+
+- api
+
+  ```python
+  from mim import test
+  test(repo='mmcls', config='resnet101_b16x8_cifar10.py',
+       checkpoint='tmp/epoch_3.pth', gpus=1, other_args='--metrics accuracy')
+  test(repo='mmcls', config='resnet101_b16x8_cifar10.py',
+       checkpoint='tmp/epoch_3.pth', gpus=1, other_args='--out tmp.pkl')
+  test(repo='mmcls', config='resnet101_b16x8_cifar10.py',
+       checkpoint='tmp/epoch_3.pth', gpus=4, launcher='pytorch',
+       other_args='--metrics accuracy')
+  test(repo='mmcls', config='resnet101_b16x8_cifar10.py',
+       checkpoint='tmp/epoch_3.pth', gpus=8, partition='partition_name',
+       launcher='slurm', gpus_per_node=8, other_args='--metrics accuracy')
+  ```
+
+</details>
+
+<details>
+<summary>8. run</summary>
+
+- command
+
+  ```bash
+  # Get the Flops of a model
+  > mim run mmcls get_flops resnet101_b16x8_cifar10.py
+  # Publish a model
+  > mim run mmcls publish_model input.pth output.pth
+  # Train models on a slurm HPC with one GPU
+  > srun -p partition --gres=gpu:1 mim run mmcls train \
+      resnet101_b16x8_cifar10.py --work-dir tmp
+  # Test models on a slurm HPC with one GPU, report accuracy
+  > srun -p partition --gres=gpu:1 mim run mmcls test \
+      resnet101_b16x8_cifar10.py tmp/epoch_3.pth --metrics accuracy
+  # Print help messages of sub-command run
+  > mim run -h
+  # Print help messages of sub-command run, list all available scripts in
+  # codebase mmcls
+  > mim run mmcls -h
+  # Print help messages of sub-command run, print the help message of
+  # training script in mmcls
+  > mim run mmcls train -h
+  ```
+
+- api
+
+  ```python
+  from mim import run
+
+  run(repo='mmcls', command='get_flops',
+      other_args='resnet101_b16x8_cifar10.py')
+  run(repo='mmcls', command='publish_model',
+      other_args='input.pth output.pth')
+  run(repo='mmcls', command='train',
+      other_args='resnet101_b16x8_cifar10.py --work-dir tmp')
+  run(repo='mmcls', command='test',
+      other_args='resnet101_b16x8_cifar10.py tmp/epoch_3.pth --metrics accuracy')
+  ```
+
+</details>
+
+<details>
+<summary>9. gridsearch</summary>
+
+- command
+
+  ```bash
+  # Parameter search on a single server with CPU by setting `gpus` to 0 and
+  # 'launcher' to 'none' (if applicable). The training script of the
+  # corresponding codebase will fail if it doesn't support CPU training.
+  > mim gridsearch mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 0 \
+      --search-args '--optimizer.lr 1e-2 1e-3'
+  # Parameter search with on a single server with one GPU, search learning
+  # rate
+  > mim gridsearch mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 1 \
+      --search-args '--optimizer.lr 1e-2 1e-3'
+  # Parameter search with on a single server with one GPU, search
+  # weight_decay
+  > mim gridsearch mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 1 \
+      --search-args '--optimizer.weight_decay 1e-3 1e-4'
+  # Parameter search with on a single server with one GPU, search learning
+  # rate and weight_decay
+  > mim gridsearch mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 1 \
+      --search-args '--optimizer.lr 1e-2 1e-3 --optimizer.weight_decay 1e-3 \
+      1e-4'
+  # Parameter search on a slurm HPC with one 8-GPU node, search learning
+  # rate and weight_decay
+  > mim gridsearch mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 8 \
+      --partition partition_name --gpus-per-node 8 --launcher slurm \
+      --search-args '--optimizer.lr 1e-2 1e-3 --optimizer.weight_decay 1e-3 \
+      1e-4'
+  # Parameter search on a slurm HPC with one 8-GPU node, search learning
+  # rate and weight_decay, max parallel jobs is 2
+  > mim gridsearch mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 8 \
+      --partition partition_name --gpus-per-node 8 --launcher slurm \
+      --max-jobs 2 --search-args '--optimizer.lr 1e-2 1e-3 \
+      --optimizer.weight_decay 1e-3 1e-4'
+  # Print the help message of sub-command search
+  > mim gridsearch -h
+  # Print the help message of sub-command search and the help message of the
+  # training script of codebase mmcls
+  > mim gridsearch mmcls -h
+  ```
+
+- api
+
+  ```python
+  from mim import gridsearch
+
+  gridsearch(repo='mmcls', config='resnet101_b16x8_cifar10.py', gpus=0,
+             search_args='--optimizer.lr 1e-2 1e-3',
+             other_args='--work-dir tmp')
+  gridsearch(repo='mmcls', config='resnet101_b16x8_cifar10.py', gpus=1,
+             search_args='--optimizer.lr 1e-2 1e-3',
+             other_args='--work-dir tmp')
+  gridsearch(repo='mmcls', config='resnet101_b16x8_cifar10.py', gpus=1,
+             search_args='--optimizer.weight_decay 1e-3 1e-4',
+             other_args='--work-dir tmp')
+  gridsearch(repo='mmcls', config='resnet101_b16x8_cifar10.py', gpus=1,
+             search_args='--optimizer.lr 1e-2 1e-3 --optimizer.weight_decay'
+                         '1e-3 1e-4',
+             other_args='--work-dir tmp')
+  gridsearch(repo='mmcls', config='resnet101_b16x8_cifar10.py', gpus=8,
+             partition='partition_name', gpus_per_node=8, launcher='slurm',
+             search_args='--optimizer.lr 1e-2 1e-3 --optimizer.weight_decay'
+                         ' 1e-3 1e-4',
+             other_args='--work-dir tmp')
+  gridsearch(repo='mmcls', config='resnet101_b16x8_cifar10.py', gpus=8,
+             partition='partition_name', gpus_per_node=8, launcher='slurm',
+             max_workers=2,
+             search_args='--optimizer.lr 1e-2 1e-3 --optimizer.weight_decay'
+                         ' 1e-3 1e-4',
+             other_args='--work-dir tmp')
+  ```
+
+</details>
+
+## Contributing
+
+We appreciate all contributions to improve mim. Please refer to [CONTRIBUTING.md](https://github.com/open-mmlab/mmcv/blob/master/CONTRIBUTING.md) for the contributing guideline.
+
+## License
+
+This project is released under the [Apache 2.0 license](LICENSE).
+
+## Projects in OpenMMLab
+
+- [MMEngine](https://github.com/open-mmlab/mmengine): OpenMMLab foundational library for training deep learning models.
+- [MMCV](https://github.com/open-mmlab/mmcv): OpenMMLab foundational library for computer vision.
+- [MMEval](https://github.com/open-mmlab/mmeval): A unified evaluation library for multiple machine learning libraries.
+- [MMPreTrain](https://github.com/open-mmlab/mmpretrain): OpenMMLab pre-training toolbox and benchmark.
+- [MMagic](https://github.com/open-mmlab/mmagic): Open**MM**Lab **A**dvanced, **G**enerative and **I**ntelligent **C**reation toolbox.
+- [MMDetection](https://github.com/open-mmlab/mmdetection): OpenMMLab detection toolbox and benchmark.
+- [MMYOLO](https://github.com/open-mmlab/mmyolo): OpenMMLab YOLO series toolbox and benchmark.
+- [MMDetection3D](https://github.com/open-mmlab/mmdetection3d): OpenMMLab's next-generation platform for general 3D object detection.
+- [MMRotate](https://github.com/open-mmlab/mmrotate): OpenMMLab rotated object detection toolbox and benchmark.
+- [MMTracking](https://github.com/open-mmlab/mmtracking): OpenMMLab video perception toolbox and benchmark.
+- [MMPose](https://github.com/open-mmlab/mmpose): OpenMMLab pose estimation toolbox and benchmark.
+- [MMSegmentation](https://github.com/open-mmlab/mmsegmentation): OpenMMLab semantic segmentation toolbox and benchmark.
+- [MMOCR](https://github.com/open-mmlab/mmocr): OpenMMLab text detection, recognition, and understanding toolbox.
+- [MMHuman3D](https://github.com/open-mmlab/mmhuman3d): OpenMMLab 3D human parametric model toolbox and benchmark.
+- [MMSelfSup](https://github.com/open-mmlab/mmselfsup): OpenMMLab self-supervised learning toolbox and benchmark.
+- [MMFewShot](https://github.com/open-mmlab/mmfewshot): OpenMMLab fewshot learning toolbox and benchmark.
+- [MMAction2](https://github.com/open-mmlab/mmaction2): OpenMMLab's next-generation action understanding toolbox and benchmark.
+- [MMFlow](https://github.com/open-mmlab/mmflow): OpenMMLab optical flow toolbox and benchmark.
+- [MMDeploy](https://github.com/open-mmlab/mmdeploy): OpenMMLab model deployment framework.
+- [MMRazor](https://github.com/open-mmlab/mmrazor): OpenMMLab model compression toolbox and benchmark.
+- [Playground](https://github.com/open-mmlab/playground): A central hub for gathering and showcasing amazing projects built upon OpenMMLab.
```

### Comparing `openmim-0.3.7/README.md` & `openmim-0.3.8/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,7 +1,20 @@
+Metadata-Version: 2.1
+Name: openmim
+Version: 0.3.8
+Summary: MIM Installs OpenMMLab packages
+Home-page: https://github.com/open-mmlab/mim
+Author: MIM Authors
+Author-email: openmmlab@gmail.com
+Requires-Python: >=3.6
+Description-Content-Type: text/markdown
+Provides-Extra: all
+Provides-Extra: tests
+License-File: LICENSE
+
 # MIM: MIM Installs OpenMMLab Packages
 
 MIM provides a unified interface for launching and installing OpenMMLab projects and their extensions, and managing the OpenMMLab model zoo.
 
 ## Major Features
 
 - **Package Management**
@@ -398,26 +411,28 @@
 
 ## License
 
 This project is released under the [Apache 2.0 license](LICENSE).
 
 ## Projects in OpenMMLab
 
+- [MMEngine](https://github.com/open-mmlab/mmengine): OpenMMLab foundational library for training deep learning models.
 - [MMCV](https://github.com/open-mmlab/mmcv): OpenMMLab foundational library for computer vision.
-- [MIM](https://github.com/open-mmlab/mim): MIM installs OpenMMLab packages.
-- [MMClassification](https://github.com/open-mmlab/mmclassification): OpenMMLab image classification toolbox and benchmark.
+- [MMEval](https://github.com/open-mmlab/mmeval): A unified evaluation library for multiple machine learning libraries.
+- [MMPreTrain](https://github.com/open-mmlab/mmpretrain): OpenMMLab pre-training toolbox and benchmark.
+- [MMagic](https://github.com/open-mmlab/mmagic): Open**MM**Lab **A**dvanced, **G**enerative and **I**ntelligent **C**reation toolbox.
 - [MMDetection](https://github.com/open-mmlab/mmdetection): OpenMMLab detection toolbox and benchmark.
+- [MMYOLO](https://github.com/open-mmlab/mmyolo): OpenMMLab YOLO series toolbox and benchmark.
 - [MMDetection3D](https://github.com/open-mmlab/mmdetection3d): OpenMMLab's next-generation platform for general 3D object detection.
 - [MMRotate](https://github.com/open-mmlab/mmrotate): OpenMMLab rotated object detection toolbox and benchmark.
+- [MMTracking](https://github.com/open-mmlab/mmtracking): OpenMMLab video perception toolbox and benchmark.
+- [MMPose](https://github.com/open-mmlab/mmpose): OpenMMLab pose estimation toolbox and benchmark.
 - [MMSegmentation](https://github.com/open-mmlab/mmsegmentation): OpenMMLab semantic segmentation toolbox and benchmark.
 - [MMOCR](https://github.com/open-mmlab/mmocr): OpenMMLab text detection, recognition, and understanding toolbox.
-- [MMPose](https://github.com/open-mmlab/mmpose): OpenMMLab pose estimation toolbox and benchmark.
 - [MMHuman3D](https://github.com/open-mmlab/mmhuman3d): OpenMMLab 3D human parametric model toolbox and benchmark.
 - [MMSelfSup](https://github.com/open-mmlab/mmselfsup): OpenMMLab self-supervised learning toolbox and benchmark.
-- [MMRazor](https://github.com/open-mmlab/mmrazor): OpenMMLab model compression toolbox and benchmark.
 - [MMFewShot](https://github.com/open-mmlab/mmfewshot): OpenMMLab fewshot learning toolbox and benchmark.
 - [MMAction2](https://github.com/open-mmlab/mmaction2): OpenMMLab's next-generation action understanding toolbox and benchmark.
-- [MMTracking](https://github.com/open-mmlab/mmtracking): OpenMMLab video perception toolbox and benchmark.
 - [MMFlow](https://github.com/open-mmlab/mmflow): OpenMMLab optical flow toolbox and benchmark.
-- [MMEditing](https://github.com/open-mmlab/mmediting): OpenMMLab image and video editing toolbox.
-- [MMGeneration](https://github.com/open-mmlab/mmgeneration): OpenMMLab image and video generative models toolbox.
 - [MMDeploy](https://github.com/open-mmlab/mmdeploy): OpenMMLab model deployment framework.
+- [MMRazor](https://github.com/open-mmlab/mmrazor): OpenMMLab model compression toolbox and benchmark.
+- [Playground](https://github.com/open-mmlab/playground): A central hub for gathering and showcasing amazing projects built upon OpenMMLab.
```

### Comparing `openmim-0.3.7/mim/__init__.py` & `openmim-0.3.8/mim/__init__.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.7/mim/cli.py` & `openmim-0.3.8/mim/cli.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.7/mim/click/autocompletion.py` & `openmim-0.3.8/mim/click/autocompletion.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.7/mim/click/compat.py` & `openmim-0.3.8/mim/click/compat.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.7/mim/click/customcommand.py` & `openmim-0.3.8/mim/click/customcommand.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.7/mim/click/option.py` & `openmim-0.3.8/mim/click/option.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.7/mim/commands/download.py` & `openmim-0.3.8/mim/commands/download.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.7/mim/commands/gridsearch.py` & `openmim-0.3.8/mim/commands/gridsearch.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.7/mim/commands/install.py` & `openmim-0.3.8/mim/commands/install.py`

 * *Files 1% similar despite different names*

```diff
@@ -240,15 +240,15 @@
     origin_iter_dependencies = Distribution.iter_dependencies
 
     def patched_iter_dependencies(self, extras=()):
         deps = list(origin_iter_dependencies(self, extras))
         if self.canonical_name not in PKG2PROJECT or self.canonical_name == 'mmcv-full':  # noqa: E501
             return deps
 
-        if 'mim' in self.iter_provided_extras:
+        if 'mim' in self.iter_provided_extras():
             mim_extra_requires = list(
                 origin_iter_dependencies(self, ('mim', )))
             filter_invalid_marker(mim_extra_requires)
             deps += mim_extra_requires
         else:
             if not hasattr(self, '_mm_deps'):
                 assert self.version is not None
```

### Comparing `openmim-0.3.7/mim/commands/list.py` & `openmim-0.3.8/mim/commands/list.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.7/mim/commands/run.py` & `openmim-0.3.8/mim/commands/run.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.7/mim/commands/search.py` & `openmim-0.3.8/mim/commands/search.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.7/mim/commands/test.py` & `openmim-0.3.8/mim/commands/test.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.7/mim/commands/train.py` & `openmim-0.3.8/mim/commands/train.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.7/mim/commands/uninstall.py` & `openmim-0.3.8/mim/commands/uninstall.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.7/mim/utils/__init__.py` & `openmim-0.3.8/mim/utils/__init__.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.7/mim/utils/default.py` & `openmim-0.3.8/mim/utils/default.py`

 * *Files 4% similar despite different names*

```diff
@@ -26,14 +26,15 @@
     'mmedit': 'mmediting',
     'mmocr': 'mmocr',
     'mmgen': 'mmgeneration',
     'mmselfsup': 'mmselfsup',
     'mmrotate': 'mmrotate',
     'mmflow': 'mmflow',
     'mmyolo': 'mmyolo',
+    'mmagic': 'mmagic',
 }
 # TODO: Should directly infer MODULE name from PKG info
 PKG2MODULE = {
     'mmcv-full': 'mmcv',
     'mmaction2': 'mmaction',
     'mmsegmentation': 'mmseg',
 }
```

### Comparing `openmim-0.3.7/mim/utils/progress_bars.py` & `openmim-0.3.8/mim/utils/progress_bars.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.7/mim/utils/utils.py` & `openmim-0.3.8/mim/utils/utils.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.7/openmim.egg-info/PKG-INFO` & `openmim-0.3.8/openmim.egg-info/PKG-INFO`

 * *Files 21% similar despite different names*

```diff
@@ -1,437 +1,438 @@
 Metadata-Version: 2.1
 Name: openmim
-Version: 0.3.7
+Version: 0.3.8
 Summary: MIM Installs OpenMMLab packages
 Home-page: https://github.com/open-mmlab/mim
 Author: MIM Authors
 Author-email: openmmlab@gmail.com
-License: UNKNOWN
-Description: # MIM: MIM Installs OpenMMLab Packages
-        
-        MIM provides a unified interface for launching and installing OpenMMLab projects and their extensions, and managing the OpenMMLab model zoo.
-        
-        ## Major Features
-        
-        - **Package Management**
-        
-          You can use MIM to manage OpenMMLab codebases, install or uninstall them conveniently.
-        
-        - **Model Management**
-        
-          You can use MIM to manage OpenMMLab model zoo, e.g., download checkpoints by name, search checkpoints that meet specific criteria.
-        
-        - **Unified Entrypoint for Scripts**
-        
-          You can execute any script provided by all OpenMMLab codebases with unified commands. Train, test and inference become easier than ever. Besides, you can use `gridsearch` command for vanilla hyper-parameter search.
-        
-        ## License
-        
-        This project is released under the [Apache 2.0 license](LICENSE).
-        
-        ## Changelog
-        
-        v0.1.1 was released in 13/6/2021.
-        
-        ## Customization
-        
-        You can use `.mimrc` for customization. Now we support customize default values of each sub-command. Please refer to [customization.md](docs/en/customization.md) for details.
-        
-        ## Build custom projects with MIM
-        
-        We provide some examples of how to build custom projects based on OpenMMLAB codebases and MIM in [MIM-Example](https://github.com/open-mmlab/mim-example).
-        Without worrying about copying codes and scripts from existing codebases, users can focus on developing new components and MIM helps integrate and run the new project.
-        
-        ## Installation
-        
-        Please refer to [installation.md](docs/en/installation.md) for installation.
-        
-        ## Command
-        
-        <details>
-        <summary>1. install</summary>
-        
-        - command
-        
-          ```bash
-          # install latest version of mmcv-full
-          > mim install mmcv-full  # wheel
-          # install 1.5.0
-          > mim install mmcv-full==1.5.0
-        
-          # install latest version of mmcls
-          > mim install mmcls
-          # install master branch
-          > mim install git+https://github.com/open-mmlab/mmclassification.git
-          # install local repo
-          > git clone https://github.com/open-mmlab/mmclassification.git
-          > cd mmclassification
-          > mim install .
-        
-          # install extension based on OpenMMLab
-          mim install git+https://github.com/xxx/mmcls-project.git
-          ```
-        
-        - api
-        
-          ```python
-          from mim import install
-        
-          # install mmcv
-          install('mmcv-full')
-        
-          # install mmcls will automatically install mmcv if it is not installed
-          install('mmcls')
-        
-          # install extension based on OpenMMLab
-          install('git+https://github.com/xxx/mmcls-project.git')
-          ```
-        
-        </details>
-        
-        <details>
-        <summary>2. uninstall</summary>
-        
-        - command
-        
-          ```bash
-          # uninstall mmcv
-          > mim uninstall mmcv-full
-        
-          # uninstall mmcls
-          > mim uninstall mmcls
-          ```
-        
-        - api
-        
-          ```python
-          from mim import uninstall
-        
-          # uninstall mmcv
-          uninstall('mmcv-full')
-        
-          # uninstall mmcls
-          uninstall('mmcls')
-          ```
-        
-        </details>
-        
-        <details>
-        <summary>3. list</summary>
-        
-        - command
-        
-          ```bash
-          > mim list
-          > mim list --all
-          ```
-        
-        - api
-        
-          ```python
-          from mim import list_package
-        
-          list_package()
-          list_package(True)
-          ```
-        
-        </details>
-        
-        <details>
-        <summary>4. search</summary>
-        
-        - command
-        
-          ```bash
-          > mim search mmcls
-          > mim search mmcls==0.23.0 --remote
-          > mim search mmcls --config resnet18_8xb16_cifar10
-          > mim search mmcls --model resnet
-          > mim search mmcls --dataset cifar-10
-          > mim search mmcls --valid-field
-          > mim search mmcls --condition 'batch_size>45,epochs>100'
-          > mim search mmcls --condition 'batch_size>45 epochs>100'
-          > mim search mmcls --condition '128<batch_size<=256'
-          > mim search mmcls --sort batch_size epochs
-          > mim search mmcls --field epochs batch_size weight
-          > mim search mmcls --exclude-field weight paper
-          ```
-        
-        - api
-        
-          ```python
-          from mim import get_model_info
-        
-          get_model_info('mmcls')
-          get_model_info('mmcls==0.23.0', local=False)
-          get_model_info('mmcls', models=['resnet'])
-          get_model_info('mmcls', training_datasets=['cifar-10'])
-          get_model_info('mmcls', filter_conditions='batch_size>45,epochs>100')
-          get_model_info('mmcls', filter_conditions='batch_size>45 epochs>100')
-          get_model_info('mmcls', filter_conditions='128<batch_size<=256')
-          get_model_info('mmcls', sorted_fields=['batch_size', 'epochs'])
-          get_model_info('mmcls', shown_fields=['epochs', 'batch_size', 'weight'])
-          ```
-        
-        </details>
-        
-        <details>
-        <summary>5. download</summary>
-        
-        - command
-        
-          ```bash
-          > mim download mmcls --config resnet18_8xb16_cifar10
-          > mim download mmcls --config resnet18_8xb16_cifar10 --dest .
-          ```
-        
-        - api
-        
-          ```python
-          from mim import download
-        
-          download('mmcls', ['resnet18_8xb16_cifar10'])
-          download('mmcls', ['resnet18_8xb16_cifar10'], dest_root='.')
-          ```
-        
-        </details>
-        
-        <details>
-        <summary>6. train</summary>
-        
-        - command
-        
-          ```bash
-          # Train models on a single server with CPU by setting `gpus` to 0 and
-          # 'launcher' to 'none' (if applicable). The training script of the
-          # corresponding codebase will fail if it doesn't support CPU training.
-          > mim train mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 0
-          # Train models on a single server with one GPU
-          > mim train mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 1
-          # Train models on a single server with 4 GPUs and pytorch distributed
-          > mim train mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 4 \
-              --launcher pytorch
-          # Train models on a slurm HPC with one 8-GPU node
-          > mim train mmcls resnet101_b16x8_cifar10.py --launcher slurm --gpus 8 \
-              --gpus-per-node 8 --partition partition_name --work-dir tmp
-          # Print help messages of sub-command train
-          > mim train -h
-          # Print help messages of sub-command train and the training script of mmcls
-          > mim train mmcls -h
-          ```
-        
-        - api
-        
-          ```python
-          from mim import train
-        
-          train(repo='mmcls', config='resnet18_8xb16_cifar10.py', gpus=0,
-                other_args='--work-dir tmp')
-          train(repo='mmcls', config='resnet18_8xb16_cifar10.py', gpus=1,
-                other_args='--work-dir tmp')
-          train(repo='mmcls', config='resnet18_8xb16_cifar10.py', gpus=4,
-                launcher='pytorch', other_args='--work-dir tmp')
-          train(repo='mmcls', config='resnet18_8xb16_cifar10.py', gpus=8,
-                launcher='slurm', gpus_per_node=8, partition='partition_name',
-                other_args='--work-dir tmp')
-          ```
-        
-        </details>
-        
-        <details>
-        <summary>7. test</summary>
-        
-        - command
-        
-          ```bash
-          # Test models on a single server with 1 GPU, report accuracy
-          > mim test mmcls resnet101_b16x8_cifar10.py --checkpoint \
-              tmp/epoch_3.pth --gpus 1 --metrics accuracy
-          # Test models on a single server with 1 GPU, save predictions
-          > mim test mmcls resnet101_b16x8_cifar10.py --checkpoint \
-              tmp/epoch_3.pth --gpus 1 --out tmp.pkl
-          # Test models on a single server with 4 GPUs, pytorch distributed,
-          # report accuracy
-          > mim test mmcls resnet101_b16x8_cifar10.py --checkpoint \
-              tmp/epoch_3.pth --gpus 4 --launcher pytorch --metrics accuracy
-          # Test models on a slurm HPC with one 8-GPU node, report accuracy
-          > mim test mmcls resnet101_b16x8_cifar10.py --checkpoint \
-              tmp/epoch_3.pth --gpus 8 --metrics accuracy --partition \
-              partition_name --gpus-per-node 8 --launcher slurm
-          # Print help messages of sub-command test
-          > mim test -h
-          # Print help messages of sub-command test and the testing script of mmcls
-          > mim test mmcls -h
-          ```
-        
-        - api
-        
-          ```python
-          from mim import test
-          test(repo='mmcls', config='resnet101_b16x8_cifar10.py',
-               checkpoint='tmp/epoch_3.pth', gpus=1, other_args='--metrics accuracy')
-          test(repo='mmcls', config='resnet101_b16x8_cifar10.py',
-               checkpoint='tmp/epoch_3.pth', gpus=1, other_args='--out tmp.pkl')
-          test(repo='mmcls', config='resnet101_b16x8_cifar10.py',
-               checkpoint='tmp/epoch_3.pth', gpus=4, launcher='pytorch',
-               other_args='--metrics accuracy')
-          test(repo='mmcls', config='resnet101_b16x8_cifar10.py',
-               checkpoint='tmp/epoch_3.pth', gpus=8, partition='partition_name',
-               launcher='slurm', gpus_per_node=8, other_args='--metrics accuracy')
-          ```
-        
-        </details>
-        
-        <details>
-        <summary>8. run</summary>
-        
-        - command
-        
-          ```bash
-          # Get the Flops of a model
-          > mim run mmcls get_flops resnet101_b16x8_cifar10.py
-          # Publish a model
-          > mim run mmcls publish_model input.pth output.pth
-          # Train models on a slurm HPC with one GPU
-          > srun -p partition --gres=gpu:1 mim run mmcls train \
-              resnet101_b16x8_cifar10.py --work-dir tmp
-          # Test models on a slurm HPC with one GPU, report accuracy
-          > srun -p partition --gres=gpu:1 mim run mmcls test \
-              resnet101_b16x8_cifar10.py tmp/epoch_3.pth --metrics accuracy
-          # Print help messages of sub-command run
-          > mim run -h
-          # Print help messages of sub-command run, list all available scripts in
-          # codebase mmcls
-          > mim run mmcls -h
-          # Print help messages of sub-command run, print the help message of
-          # training script in mmcls
-          > mim run mmcls train -h
-          ```
-        
-        - api
-        
-          ```python
-          from mim import run
-        
-          run(repo='mmcls', command='get_flops',
-              other_args='resnet101_b16x8_cifar10.py')
-          run(repo='mmcls', command='publish_model',
-              other_args='input.pth output.pth')
-          run(repo='mmcls', command='train',
-              other_args='resnet101_b16x8_cifar10.py --work-dir tmp')
-          run(repo='mmcls', command='test',
-              other_args='resnet101_b16x8_cifar10.py tmp/epoch_3.pth --metrics accuracy')
-          ```
-        
-        </details>
-        
-        <details>
-        <summary>9. gridsearch</summary>
-        
-        - command
-        
-          ```bash
-          # Parameter search on a single server with CPU by setting `gpus` to 0 and
-          # 'launcher' to 'none' (if applicable). The training script of the
-          # corresponding codebase will fail if it doesn't support CPU training.
-          > mim gridsearch mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 0 \
-              --search-args '--optimizer.lr 1e-2 1e-3'
-          # Parameter search with on a single server with one GPU, search learning
-          # rate
-          > mim gridsearch mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 1 \
-              --search-args '--optimizer.lr 1e-2 1e-3'
-          # Parameter search with on a single server with one GPU, search
-          # weight_decay
-          > mim gridsearch mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 1 \
-              --search-args '--optimizer.weight_decay 1e-3 1e-4'
-          # Parameter search with on a single server with one GPU, search learning
-          # rate and weight_decay
-          > mim gridsearch mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 1 \
-              --search-args '--optimizer.lr 1e-2 1e-3 --optimizer.weight_decay 1e-3 \
-              1e-4'
-          # Parameter search on a slurm HPC with one 8-GPU node, search learning
-          # rate and weight_decay
-          > mim gridsearch mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 8 \
-              --partition partition_name --gpus-per-node 8 --launcher slurm \
-              --search-args '--optimizer.lr 1e-2 1e-3 --optimizer.weight_decay 1e-3 \
-              1e-4'
-          # Parameter search on a slurm HPC with one 8-GPU node, search learning
-          # rate and weight_decay, max parallel jobs is 2
-          > mim gridsearch mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 8 \
-              --partition partition_name --gpus-per-node 8 --launcher slurm \
-              --max-jobs 2 --search-args '--optimizer.lr 1e-2 1e-3 \
-              --optimizer.weight_decay 1e-3 1e-4'
-          # Print the help message of sub-command search
-          > mim gridsearch -h
-          # Print the help message of sub-command search and the help message of the
-          # training script of codebase mmcls
-          > mim gridsearch mmcls -h
-          ```
-        
-        - api
-        
-          ```python
-          from mim import gridsearch
-        
-          gridsearch(repo='mmcls', config='resnet101_b16x8_cifar10.py', gpus=0,
-                     search_args='--optimizer.lr 1e-2 1e-3',
-                     other_args='--work-dir tmp')
-          gridsearch(repo='mmcls', config='resnet101_b16x8_cifar10.py', gpus=1,
-                     search_args='--optimizer.lr 1e-2 1e-3',
-                     other_args='--work-dir tmp')
-          gridsearch(repo='mmcls', config='resnet101_b16x8_cifar10.py', gpus=1,
-                     search_args='--optimizer.weight_decay 1e-3 1e-4',
-                     other_args='--work-dir tmp')
-          gridsearch(repo='mmcls', config='resnet101_b16x8_cifar10.py', gpus=1,
-                     search_args='--optimizer.lr 1e-2 1e-3 --optimizer.weight_decay'
-                                 '1e-3 1e-4',
-                     other_args='--work-dir tmp')
-          gridsearch(repo='mmcls', config='resnet101_b16x8_cifar10.py', gpus=8,
-                     partition='partition_name', gpus_per_node=8, launcher='slurm',
-                     search_args='--optimizer.lr 1e-2 1e-3 --optimizer.weight_decay'
-                                 ' 1e-3 1e-4',
-                     other_args='--work-dir tmp')
-          gridsearch(repo='mmcls', config='resnet101_b16x8_cifar10.py', gpus=8,
-                     partition='partition_name', gpus_per_node=8, launcher='slurm',
-                     max_workers=2,
-                     search_args='--optimizer.lr 1e-2 1e-3 --optimizer.weight_decay'
-                                 ' 1e-3 1e-4',
-                     other_args='--work-dir tmp')
-          ```
-        
-        </details>
-        
-        ## Contributing
-        
-        We appreciate all contributions to improve mim. Please refer to [CONTRIBUTING.md](https://github.com/open-mmlab/mmcv/blob/master/CONTRIBUTING.md) for the contributing guideline.
-        
-        ## License
-        
-        This project is released under the [Apache 2.0 license](LICENSE).
-        
-        ## Projects in OpenMMLab
-        
-        - [MMCV](https://github.com/open-mmlab/mmcv): OpenMMLab foundational library for computer vision.
-        - [MIM](https://github.com/open-mmlab/mim): MIM installs OpenMMLab packages.
-        - [MMClassification](https://github.com/open-mmlab/mmclassification): OpenMMLab image classification toolbox and benchmark.
-        - [MMDetection](https://github.com/open-mmlab/mmdetection): OpenMMLab detection toolbox and benchmark.
-        - [MMDetection3D](https://github.com/open-mmlab/mmdetection3d): OpenMMLab's next-generation platform for general 3D object detection.
-        - [MMRotate](https://github.com/open-mmlab/mmrotate): OpenMMLab rotated object detection toolbox and benchmark.
-        - [MMSegmentation](https://github.com/open-mmlab/mmsegmentation): OpenMMLab semantic segmentation toolbox and benchmark.
-        - [MMOCR](https://github.com/open-mmlab/mmocr): OpenMMLab text detection, recognition, and understanding toolbox.
-        - [MMPose](https://github.com/open-mmlab/mmpose): OpenMMLab pose estimation toolbox and benchmark.
-        - [MMHuman3D](https://github.com/open-mmlab/mmhuman3d): OpenMMLab 3D human parametric model toolbox and benchmark.
-        - [MMSelfSup](https://github.com/open-mmlab/mmselfsup): OpenMMLab self-supervised learning toolbox and benchmark.
-        - [MMRazor](https://github.com/open-mmlab/mmrazor): OpenMMLab model compression toolbox and benchmark.
-        - [MMFewShot](https://github.com/open-mmlab/mmfewshot): OpenMMLab fewshot learning toolbox and benchmark.
-        - [MMAction2](https://github.com/open-mmlab/mmaction2): OpenMMLab's next-generation action understanding toolbox and benchmark.
-        - [MMTracking](https://github.com/open-mmlab/mmtracking): OpenMMLab video perception toolbox and benchmark.
-        - [MMFlow](https://github.com/open-mmlab/mmflow): OpenMMLab optical flow toolbox and benchmark.
-        - [MMEditing](https://github.com/open-mmlab/mmediting): OpenMMLab image and video editing toolbox.
-        - [MMGeneration](https://github.com/open-mmlab/mmgeneration): OpenMMLab image and video generative models toolbox.
-        - [MMDeploy](https://github.com/open-mmlab/mmdeploy): OpenMMLab model deployment framework.
-        
-Platform: UNKNOWN
 Requires-Python: >=3.6
 Description-Content-Type: text/markdown
 Provides-Extra: all
 Provides-Extra: tests
+License-File: LICENSE
+
+# MIM: MIM Installs OpenMMLab Packages
+
+MIM provides a unified interface for launching and installing OpenMMLab projects and their extensions, and managing the OpenMMLab model zoo.
+
+## Major Features
+
+- **Package Management**
+
+  You can use MIM to manage OpenMMLab codebases, install or uninstall them conveniently.
+
+- **Model Management**
+
+  You can use MIM to manage OpenMMLab model zoo, e.g., download checkpoints by name, search checkpoints that meet specific criteria.
+
+- **Unified Entrypoint for Scripts**
+
+  You can execute any script provided by all OpenMMLab codebases with unified commands. Train, test and inference become easier than ever. Besides, you can use `gridsearch` command for vanilla hyper-parameter search.
+
+## License
+
+This project is released under the [Apache 2.0 license](LICENSE).
+
+## Changelog
+
+v0.1.1 was released in 13/6/2021.
+
+## Customization
+
+You can use `.mimrc` for customization. Now we support customize default values of each sub-command. Please refer to [customization.md](docs/en/customization.md) for details.
+
+## Build custom projects with MIM
+
+We provide some examples of how to build custom projects based on OpenMMLAB codebases and MIM in [MIM-Example](https://github.com/open-mmlab/mim-example).
+Without worrying about copying codes and scripts from existing codebases, users can focus on developing new components and MIM helps integrate and run the new project.
+
+## Installation
+
+Please refer to [installation.md](docs/en/installation.md) for installation.
+
+## Command
+
+<details>
+<summary>1. install</summary>
+
+- command
+
+  ```bash
+  # install latest version of mmcv-full
+  > mim install mmcv-full  # wheel
+  # install 1.5.0
+  > mim install mmcv-full==1.5.0
+
+  # install latest version of mmcls
+  > mim install mmcls
+  # install master branch
+  > mim install git+https://github.com/open-mmlab/mmclassification.git
+  # install local repo
+  > git clone https://github.com/open-mmlab/mmclassification.git
+  > cd mmclassification
+  > mim install .
+
+  # install extension based on OpenMMLab
+  mim install git+https://github.com/xxx/mmcls-project.git
+  ```
+
+- api
+
+  ```python
+  from mim import install
+
+  # install mmcv
+  install('mmcv-full')
+
+  # install mmcls will automatically install mmcv if it is not installed
+  install('mmcls')
+
+  # install extension based on OpenMMLab
+  install('git+https://github.com/xxx/mmcls-project.git')
+  ```
+
+</details>
+
+<details>
+<summary>2. uninstall</summary>
+
+- command
+
+  ```bash
+  # uninstall mmcv
+  > mim uninstall mmcv-full
+
+  # uninstall mmcls
+  > mim uninstall mmcls
+  ```
+
+- api
+
+  ```python
+  from mim import uninstall
+
+  # uninstall mmcv
+  uninstall('mmcv-full')
+
+  # uninstall mmcls
+  uninstall('mmcls')
+  ```
+
+</details>
+
+<details>
+<summary>3. list</summary>
+
+- command
+
+  ```bash
+  > mim list
+  > mim list --all
+  ```
+
+- api
+
+  ```python
+  from mim import list_package
+
+  list_package()
+  list_package(True)
+  ```
+
+</details>
+
+<details>
+<summary>4. search</summary>
+
+- command
+
+  ```bash
+  > mim search mmcls
+  > mim search mmcls==0.23.0 --remote
+  > mim search mmcls --config resnet18_8xb16_cifar10
+  > mim search mmcls --model resnet
+  > mim search mmcls --dataset cifar-10
+  > mim search mmcls --valid-field
+  > mim search mmcls --condition 'batch_size>45,epochs>100'
+  > mim search mmcls --condition 'batch_size>45 epochs>100'
+  > mim search mmcls --condition '128<batch_size<=256'
+  > mim search mmcls --sort batch_size epochs
+  > mim search mmcls --field epochs batch_size weight
+  > mim search mmcls --exclude-field weight paper
+  ```
+
+- api
+
+  ```python
+  from mim import get_model_info
+
+  get_model_info('mmcls')
+  get_model_info('mmcls==0.23.0', local=False)
+  get_model_info('mmcls', models=['resnet'])
+  get_model_info('mmcls', training_datasets=['cifar-10'])
+  get_model_info('mmcls', filter_conditions='batch_size>45,epochs>100')
+  get_model_info('mmcls', filter_conditions='batch_size>45 epochs>100')
+  get_model_info('mmcls', filter_conditions='128<batch_size<=256')
+  get_model_info('mmcls', sorted_fields=['batch_size', 'epochs'])
+  get_model_info('mmcls', shown_fields=['epochs', 'batch_size', 'weight'])
+  ```
+
+</details>
+
+<details>
+<summary>5. download</summary>
+
+- command
+
+  ```bash
+  > mim download mmcls --config resnet18_8xb16_cifar10
+  > mim download mmcls --config resnet18_8xb16_cifar10 --dest .
+  ```
+
+- api
+
+  ```python
+  from mim import download
+
+  download('mmcls', ['resnet18_8xb16_cifar10'])
+  download('mmcls', ['resnet18_8xb16_cifar10'], dest_root='.')
+  ```
+
+</details>
+
+<details>
+<summary>6. train</summary>
+
+- command
+
+  ```bash
+  # Train models on a single server with CPU by setting `gpus` to 0 and
+  # 'launcher' to 'none' (if applicable). The training script of the
+  # corresponding codebase will fail if it doesn't support CPU training.
+  > mim train mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 0
+  # Train models on a single server with one GPU
+  > mim train mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 1
+  # Train models on a single server with 4 GPUs and pytorch distributed
+  > mim train mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 4 \
+      --launcher pytorch
+  # Train models on a slurm HPC with one 8-GPU node
+  > mim train mmcls resnet101_b16x8_cifar10.py --launcher slurm --gpus 8 \
+      --gpus-per-node 8 --partition partition_name --work-dir tmp
+  # Print help messages of sub-command train
+  > mim train -h
+  # Print help messages of sub-command train and the training script of mmcls
+  > mim train mmcls -h
+  ```
+
+- api
+
+  ```python
+  from mim import train
+
+  train(repo='mmcls', config='resnet18_8xb16_cifar10.py', gpus=0,
+        other_args='--work-dir tmp')
+  train(repo='mmcls', config='resnet18_8xb16_cifar10.py', gpus=1,
+        other_args='--work-dir tmp')
+  train(repo='mmcls', config='resnet18_8xb16_cifar10.py', gpus=4,
+        launcher='pytorch', other_args='--work-dir tmp')
+  train(repo='mmcls', config='resnet18_8xb16_cifar10.py', gpus=8,
+        launcher='slurm', gpus_per_node=8, partition='partition_name',
+        other_args='--work-dir tmp')
+  ```
+
+</details>
+
+<details>
+<summary>7. test</summary>
+
+- command
+
+  ```bash
+  # Test models on a single server with 1 GPU, report accuracy
+  > mim test mmcls resnet101_b16x8_cifar10.py --checkpoint \
+      tmp/epoch_3.pth --gpus 1 --metrics accuracy
+  # Test models on a single server with 1 GPU, save predictions
+  > mim test mmcls resnet101_b16x8_cifar10.py --checkpoint \
+      tmp/epoch_3.pth --gpus 1 --out tmp.pkl
+  # Test models on a single server with 4 GPUs, pytorch distributed,
+  # report accuracy
+  > mim test mmcls resnet101_b16x8_cifar10.py --checkpoint \
+      tmp/epoch_3.pth --gpus 4 --launcher pytorch --metrics accuracy
+  # Test models on a slurm HPC with one 8-GPU node, report accuracy
+  > mim test mmcls resnet101_b16x8_cifar10.py --checkpoint \
+      tmp/epoch_3.pth --gpus 8 --metrics accuracy --partition \
+      partition_name --gpus-per-node 8 --launcher slurm
+  # Print help messages of sub-command test
+  > mim test -h
+  # Print help messages of sub-command test and the testing script of mmcls
+  > mim test mmcls -h
+  ```
+
+- api
+
+  ```python
+  from mim import test
+  test(repo='mmcls', config='resnet101_b16x8_cifar10.py',
+       checkpoint='tmp/epoch_3.pth', gpus=1, other_args='--metrics accuracy')
+  test(repo='mmcls', config='resnet101_b16x8_cifar10.py',
+       checkpoint='tmp/epoch_3.pth', gpus=1, other_args='--out tmp.pkl')
+  test(repo='mmcls', config='resnet101_b16x8_cifar10.py',
+       checkpoint='tmp/epoch_3.pth', gpus=4, launcher='pytorch',
+       other_args='--metrics accuracy')
+  test(repo='mmcls', config='resnet101_b16x8_cifar10.py',
+       checkpoint='tmp/epoch_3.pth', gpus=8, partition='partition_name',
+       launcher='slurm', gpus_per_node=8, other_args='--metrics accuracy')
+  ```
+
+</details>
+
+<details>
+<summary>8. run</summary>
+
+- command
+
+  ```bash
+  # Get the Flops of a model
+  > mim run mmcls get_flops resnet101_b16x8_cifar10.py
+  # Publish a model
+  > mim run mmcls publish_model input.pth output.pth
+  # Train models on a slurm HPC with one GPU
+  > srun -p partition --gres=gpu:1 mim run mmcls train \
+      resnet101_b16x8_cifar10.py --work-dir tmp
+  # Test models on a slurm HPC with one GPU, report accuracy
+  > srun -p partition --gres=gpu:1 mim run mmcls test \
+      resnet101_b16x8_cifar10.py tmp/epoch_3.pth --metrics accuracy
+  # Print help messages of sub-command run
+  > mim run -h
+  # Print help messages of sub-command run, list all available scripts in
+  # codebase mmcls
+  > mim run mmcls -h
+  # Print help messages of sub-command run, print the help message of
+  # training script in mmcls
+  > mim run mmcls train -h
+  ```
+
+- api
+
+  ```python
+  from mim import run
+
+  run(repo='mmcls', command='get_flops',
+      other_args='resnet101_b16x8_cifar10.py')
+  run(repo='mmcls', command='publish_model',
+      other_args='input.pth output.pth')
+  run(repo='mmcls', command='train',
+      other_args='resnet101_b16x8_cifar10.py --work-dir tmp')
+  run(repo='mmcls', command='test',
+      other_args='resnet101_b16x8_cifar10.py tmp/epoch_3.pth --metrics accuracy')
+  ```
+
+</details>
+
+<details>
+<summary>9. gridsearch</summary>
+
+- command
+
+  ```bash
+  # Parameter search on a single server with CPU by setting `gpus` to 0 and
+  # 'launcher' to 'none' (if applicable). The training script of the
+  # corresponding codebase will fail if it doesn't support CPU training.
+  > mim gridsearch mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 0 \
+      --search-args '--optimizer.lr 1e-2 1e-3'
+  # Parameter search with on a single server with one GPU, search learning
+  # rate
+  > mim gridsearch mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 1 \
+      --search-args '--optimizer.lr 1e-2 1e-3'
+  # Parameter search with on a single server with one GPU, search
+  # weight_decay
+  > mim gridsearch mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 1 \
+      --search-args '--optimizer.weight_decay 1e-3 1e-4'
+  # Parameter search with on a single server with one GPU, search learning
+  # rate and weight_decay
+  > mim gridsearch mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 1 \
+      --search-args '--optimizer.lr 1e-2 1e-3 --optimizer.weight_decay 1e-3 \
+      1e-4'
+  # Parameter search on a slurm HPC with one 8-GPU node, search learning
+  # rate and weight_decay
+  > mim gridsearch mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 8 \
+      --partition partition_name --gpus-per-node 8 --launcher slurm \
+      --search-args '--optimizer.lr 1e-2 1e-3 --optimizer.weight_decay 1e-3 \
+      1e-4'
+  # Parameter search on a slurm HPC with one 8-GPU node, search learning
+  # rate and weight_decay, max parallel jobs is 2
+  > mim gridsearch mmcls resnet101_b16x8_cifar10.py --work-dir tmp --gpus 8 \
+      --partition partition_name --gpus-per-node 8 --launcher slurm \
+      --max-jobs 2 --search-args '--optimizer.lr 1e-2 1e-3 \
+      --optimizer.weight_decay 1e-3 1e-4'
+  # Print the help message of sub-command search
+  > mim gridsearch -h
+  # Print the help message of sub-command search and the help message of the
+  # training script of codebase mmcls
+  > mim gridsearch mmcls -h
+  ```
+
+- api
+
+  ```python
+  from mim import gridsearch
+
+  gridsearch(repo='mmcls', config='resnet101_b16x8_cifar10.py', gpus=0,
+             search_args='--optimizer.lr 1e-2 1e-3',
+             other_args='--work-dir tmp')
+  gridsearch(repo='mmcls', config='resnet101_b16x8_cifar10.py', gpus=1,
+             search_args='--optimizer.lr 1e-2 1e-3',
+             other_args='--work-dir tmp')
+  gridsearch(repo='mmcls', config='resnet101_b16x8_cifar10.py', gpus=1,
+             search_args='--optimizer.weight_decay 1e-3 1e-4',
+             other_args='--work-dir tmp')
+  gridsearch(repo='mmcls', config='resnet101_b16x8_cifar10.py', gpus=1,
+             search_args='--optimizer.lr 1e-2 1e-3 --optimizer.weight_decay'
+                         '1e-3 1e-4',
+             other_args='--work-dir tmp')
+  gridsearch(repo='mmcls', config='resnet101_b16x8_cifar10.py', gpus=8,
+             partition='partition_name', gpus_per_node=8, launcher='slurm',
+             search_args='--optimizer.lr 1e-2 1e-3 --optimizer.weight_decay'
+                         ' 1e-3 1e-4',
+             other_args='--work-dir tmp')
+  gridsearch(repo='mmcls', config='resnet101_b16x8_cifar10.py', gpus=8,
+             partition='partition_name', gpus_per_node=8, launcher='slurm',
+             max_workers=2,
+             search_args='--optimizer.lr 1e-2 1e-3 --optimizer.weight_decay'
+                         ' 1e-3 1e-4',
+             other_args='--work-dir tmp')
+  ```
+
+</details>
+
+## Contributing
+
+We appreciate all contributions to improve mim. Please refer to [CONTRIBUTING.md](https://github.com/open-mmlab/mmcv/blob/master/CONTRIBUTING.md) for the contributing guideline.
+
+## License
+
+This project is released under the [Apache 2.0 license](LICENSE).
+
+## Projects in OpenMMLab
+
+- [MMEngine](https://github.com/open-mmlab/mmengine): OpenMMLab foundational library for training deep learning models.
+- [MMCV](https://github.com/open-mmlab/mmcv): OpenMMLab foundational library for computer vision.
+- [MMEval](https://github.com/open-mmlab/mmeval): A unified evaluation library for multiple machine learning libraries.
+- [MMPreTrain](https://github.com/open-mmlab/mmpretrain): OpenMMLab pre-training toolbox and benchmark.
+- [MMagic](https://github.com/open-mmlab/mmagic): Open**MM**Lab **A**dvanced, **G**enerative and **I**ntelligent **C**reation toolbox.
+- [MMDetection](https://github.com/open-mmlab/mmdetection): OpenMMLab detection toolbox and benchmark.
+- [MMYOLO](https://github.com/open-mmlab/mmyolo): OpenMMLab YOLO series toolbox and benchmark.
+- [MMDetection3D](https://github.com/open-mmlab/mmdetection3d): OpenMMLab's next-generation platform for general 3D object detection.
+- [MMRotate](https://github.com/open-mmlab/mmrotate): OpenMMLab rotated object detection toolbox and benchmark.
+- [MMTracking](https://github.com/open-mmlab/mmtracking): OpenMMLab video perception toolbox and benchmark.
+- [MMPose](https://github.com/open-mmlab/mmpose): OpenMMLab pose estimation toolbox and benchmark.
+- [MMSegmentation](https://github.com/open-mmlab/mmsegmentation): OpenMMLab semantic segmentation toolbox and benchmark.
+- [MMOCR](https://github.com/open-mmlab/mmocr): OpenMMLab text detection, recognition, and understanding toolbox.
+- [MMHuman3D](https://github.com/open-mmlab/mmhuman3d): OpenMMLab 3D human parametric model toolbox and benchmark.
+- [MMSelfSup](https://github.com/open-mmlab/mmselfsup): OpenMMLab self-supervised learning toolbox and benchmark.
+- [MMFewShot](https://github.com/open-mmlab/mmfewshot): OpenMMLab fewshot learning toolbox and benchmark.
+- [MMAction2](https://github.com/open-mmlab/mmaction2): OpenMMLab's next-generation action understanding toolbox and benchmark.
+- [MMFlow](https://github.com/open-mmlab/mmflow): OpenMMLab optical flow toolbox and benchmark.
+- [MMDeploy](https://github.com/open-mmlab/mmdeploy): OpenMMLab model deployment framework.
+- [MMRazor](https://github.com/open-mmlab/mmrazor): OpenMMLab model compression toolbox and benchmark.
+- [Playground](https://github.com/open-mmlab/playground): A central hub for gathering and showcasing amazing projects built upon OpenMMLab.
```

### Comparing `openmim-0.3.7/openmim.egg-info/SOURCES.txt` & `openmim-0.3.8/openmim.egg-info/SOURCES.txt`

 * *Files 24% similar despite different names*

```diff
@@ -1,7 +1,8 @@
+LICENSE
 MANIFEST.in
 README.md
 setup.cfg
 setup.py
 mim/__init__.py
 mim/__main__.py
 mim/cli.py
@@ -30,8 +31,19 @@
 openmim.egg-info/SOURCES.txt
 openmim.egg-info/dependency_links.txt
 openmim.egg-info/entry_points.txt
 openmim.egg-info/requires.txt
 openmim.egg-info/top_level.txt
 requirements/docs.txt
 requirements/install.txt
-requirements/tests.txt
+requirements/tests.txt
+tests/test_download.py
+tests/test_gridsearch.py
+tests/test_install.py
+tests/test_list.py
+tests/test_run.py
+tests/test_search.py
+tests/test_test.py
+tests/test_train.py
+tests/test_uninstall.py
+tests/test_utils.py
+tests/test_version.py
```

### Comparing `openmim-0.3.7/setup.cfg` & `openmim-0.3.8/setup.cfg`

 * *Files identical despite different names*

### Comparing `openmim-0.3.7/setup.py` & `openmim-0.3.8/setup.py`

 * *Files identical despite different names*


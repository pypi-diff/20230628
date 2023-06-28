# Comparing `tmp/fastcs-0.1a2.tar.gz` & `tmp/fastcs-0.1a3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "fastcs-0.1a2.tar", last modified: Wed Jun 28 08:57:04 2023, max compression
+gzip compressed data, was "fastcs-0.1a3.tar", last modified: Wed Jun 28 12:15:18 2023, max compression
```

## Comparing `fastcs-0.1a2.tar` & `fastcs-0.1a3.tar`

### file list

```diff
@@ -1,82 +1,82 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.753186 fastcs-0.1a2/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.749186 fastcs-0.1a2/.devcontainer/
--rw-r--r--   0 runner    (1001) docker     (123)     2143 2023-06-28 08:56:52.000000 fastcs-0.1a2/.devcontainer/devcontainer.json
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.749186 fastcs-0.1a2/.github/
--rw-r--r--   0 runner    (1001) docker     (123)     1344 2023-06-28 08:56:52.000000 fastcs-0.1a2/.github/CONTRIBUTING.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.745186 fastcs-0.1a2/.github/actions/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.749186 fastcs-0.1a2/.github/actions/install_requirements/
--rw-r--r--   0 runner    (1001) docker     (123)     2065 2023-06-28 08:56:52.000000 fastcs-0.1a2/.github/actions/install_requirements/action.yml
--rw-r--r--   0 runner    (1001) docker     (123)      529 2023-06-28 08:56:52.000000 fastcs-0.1a2/.github/dependabot.yml
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.749186 fastcs-0.1a2/.github/pages/
--rw-r--r--   0 runner    (1001) docker     (123)      237 2023-06-28 08:56:52.000000 fastcs-0.1a2/.github/pages/index.html
--rwxr-xr-x   0 runner    (1001) docker     (123)     3041 2023-06-28 08:56:52.000000 fastcs-0.1a2/.github/pages/make_switcher.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.749186 fastcs-0.1a2/.github/workflows/
--rw-r--r--   0 runner    (1001) docker     (123)     7631 2023-06-28 08:56:52.000000 fastcs-0.1a2/.github/workflows/code.yml
--rw-r--r--   0 runner    (1001) docker     (123)     1830 2023-06-28 08:56:52.000000 fastcs-0.1a2/.github/workflows/docs.yml
--rw-r--r--   0 runner    (1001) docker     (123)     1524 2023-06-28 08:56:52.000000 fastcs-0.1a2/.github/workflows/docs_clean.yml
--rw-r--r--   0 runner    (1001) docker     (123)      597 2023-06-28 08:56:52.000000 fastcs-0.1a2/.github/workflows/linkcheck.yml
--rw-r--r--   0 runner    (1001) docker     (123)      824 2023-06-28 08:56:52.000000 fastcs-0.1a2/.gitignore
--rw-r--r--   0 runner    (1001) docker     (123)      504 2023-06-28 08:56:52.000000 fastcs-0.1a2/.pre-commit-config.yaml
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.749186 fastcs-0.1a2/.vscode/
--rw-r--r--   0 runner    (1001) docker     (123)      218 2023-06-28 08:56:52.000000 fastcs-0.1a2/.vscode/extensions.json
--rw-r--r--   0 runner    (1001) docker     (123)      888 2023-06-28 08:56:52.000000 fastcs-0.1a2/.vscode/launch.json
--rw-r--r--   0 runner    (1001) docker     (123)      543 2023-06-28 08:56:52.000000 fastcs-0.1a2/.vscode/settings.json
--rw-r--r--   0 runner    (1001) docker     (123)      398 2023-06-28 08:56:52.000000 fastcs-0.1a2/.vscode/tasks.json
--rw-r--r--   0 runner    (1001) docker     (123)     1041 2023-06-28 08:56:52.000000 fastcs-0.1a2/Dockerfile
--rw-r--r--   0 runner    (1001) docker     (123)    11357 2023-06-28 08:56:52.000000 fastcs-0.1a2/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15833 2023-06-28 08:57:04.753186 fastcs-0.1a2/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2097 2023-06-28 08:56:52.000000 fastcs-0.1a2/README.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.749186 fastcs-0.1a2/docs/
--rw-r--r--   0 runner    (1001) docker     (123)     6485 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/conf.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.749186 fastcs-0.1a2/docs/developer/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.749186 fastcs-0.1a2/docs/developer/explanations/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.749186 fastcs-0.1a2/docs/developer/explanations/decisions/
--rw-r--r--   0 runner    (1001) docker     (123)      506 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/developer/explanations/decisions/0001-record-architecture-decisions.rst
--rw-r--r--   0 runner    (1001) docker     (123)      702 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/developer/explanations/decisions/0002-switched-to-pip-skeleton.rst
--rw-r--r--   0 runner    (1001) docker     (123)      558 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/developer/explanations/decisions.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.753186 fastcs-0.1a2/docs/developer/how-to/
--rw-r--r--   0 runner    (1001) docker     (123)      955 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/developer/how-to/build-docs.rst
--rw-r--r--   0 runner    (1001) docker     (123)       47 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/developer/how-to/contribute.rst
--rw-r--r--   0 runner    (1001) docker     (123)     1085 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/developer/how-to/lint.rst
--rw-r--r--   0 runner    (1001) docker     (123)      630 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/developer/how-to/make-release.rst
--rw-r--r--   0 runner    (1001) docker     (123)     2880 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/developer/how-to/pin-requirements.rst
--rw-r--r--   0 runner    (1001) docker     (123)      418 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/developer/how-to/run-tests.rst
--rw-r--r--   0 runner    (1001) docker     (123)      267 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/developer/how-to/static-analysis.rst
--rw-r--r--   0 runner    (1001) docker     (123)      820 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/developer/how-to/test-container.rst
--rw-r--r--   0 runner    (1001) docker     (123)      744 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/developer/how-to/update-tools.rst
--rw-r--r--   0 runner    (1001) docker     (123)     1404 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/developer/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.753186 fastcs-0.1a2/docs/developer/reference/
--rw-r--r--   0 runner    (1001) docker     (123)     1425 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/developer/reference/standards.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.753186 fastcs-0.1a2/docs/developer/tutorials/
--rw-r--r--   0 runner    (1001) docker     (123)     1632 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/developer/tutorials/dev-install.rst
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/genindex.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.753186 fastcs-0.1a2/docs/images/
--rw-r--r--   0 runner    (1001) docker     (123)     2294 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/images/fastcs.svg
--rw-r--r--   0 runner    (1001) docker     (123)      876 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.753186 fastcs-0.1a2/docs/user/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.753186 fastcs-0.1a2/docs/user/explanations/
--rw-r--r--   0 runner    (1001) docker     (123)      664 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/user/explanations/docs-structure.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.753186 fastcs-0.1a2/docs/user/how-to/
--rw-r--r--   0 runner    (1001) docker     (123)      452 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/user/how-to/run-container.rst
--rw-r--r--   0 runner    (1001) docker     (123)     1208 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/user/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.753186 fastcs-0.1a2/docs/user/reference/
--rw-r--r--   0 runner    (1001) docker     (123)      256 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/user/reference/api.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.753186 fastcs-0.1a2/docs/user/tutorials/
--rw-r--r--   0 runner    (1001) docker     (123)      991 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/user/tutorials/installation.rst
--rw-r--r--   0 runner    (1001) docker     (123)     3189 2023-06-28 08:56:52.000000 fastcs-0.1a2/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 08:57:04.753186 fastcs-0.1a2/setup.cfg
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.749186 fastcs-0.1a2/src/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.753186 fastcs-0.1a2/src/fastcs/
--rw-r--r--   0 runner    (1001) docker     (123)      222 2023-06-28 08:56:52.000000 fastcs-0.1a2/src/fastcs/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      323 2023-06-28 08:56:52.000000 fastcs-0.1a2/src/fastcs/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)      157 2023-06-28 08:57:04.000000 fastcs-0.1a2/src/fastcs/_version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.753186 fastcs-0.1a2/src/fastcs.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15833 2023-06-28 08:57:04.000000 fastcs-0.1a2/src/fastcs.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1666 2023-06-28 08:57:04.000000 fastcs-0.1a2/src/fastcs.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 08:57:04.000000 fastcs-0.1a2/src/fastcs.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       48 2023-06-28 08:57:04.000000 fastcs-0.1a2/src/fastcs.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)      230 2023-06-28 08:57:04.000000 fastcs-0.1a2/src/fastcs.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)        7 2023-06-28 08:57:04.000000 fastcs-0.1a2/src/fastcs.egg-info/top_level.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.753186 fastcs-0.1a2/tests/
--rw-r--r--   0 runner    (1001) docker     (123)     1622 2023-06-28 08:56:52.000000 fastcs-0.1a2/tests/test_boilerplate_removed.py
--rw-r--r--   0 runner    (1001) docker     (123)      215 2023-06-28 08:56:52.000000 fastcs-0.1a2/tests/test_cli.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:15:18.210192 fastcs-0.1a3/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:15:18.194191 fastcs-0.1a3/.devcontainer/
+-rw-r--r--   0 runner    (1001) docker     (123)     2143 2023-06-28 12:15:06.000000 fastcs-0.1a3/.devcontainer/devcontainer.json
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:15:18.194191 fastcs-0.1a3/.github/
+-rw-r--r--   0 runner    (1001) docker     (123)     1344 2023-06-28 12:15:06.000000 fastcs-0.1a3/.github/CONTRIBUTING.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:15:18.186191 fastcs-0.1a3/.github/actions/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:15:18.194191 fastcs-0.1a3/.github/actions/install_requirements/
+-rw-r--r--   0 runner    (1001) docker     (123)     2065 2023-06-28 12:15:06.000000 fastcs-0.1a3/.github/actions/install_requirements/action.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      529 2023-06-28 12:15:06.000000 fastcs-0.1a3/.github/dependabot.yml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:15:18.198191 fastcs-0.1a3/.github/pages/
+-rw-r--r--   0 runner    (1001) docker     (123)      237 2023-06-28 12:15:06.000000 fastcs-0.1a3/.github/pages/index.html
+-rwxr-xr-x   0 runner    (1001) docker     (123)     3041 2023-06-28 12:15:06.000000 fastcs-0.1a3/.github/pages/make_switcher.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:15:18.198191 fastcs-0.1a3/.github/workflows/
+-rw-r--r--   0 runner    (1001) docker     (123)     7631 2023-06-28 12:15:06.000000 fastcs-0.1a3/.github/workflows/code.yml
+-rw-r--r--   0 runner    (1001) docker     (123)     1830 2023-06-28 12:15:06.000000 fastcs-0.1a3/.github/workflows/docs.yml
+-rw-r--r--   0 runner    (1001) docker     (123)     1524 2023-06-28 12:15:06.000000 fastcs-0.1a3/.github/workflows/docs_clean.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      597 2023-06-28 12:15:06.000000 fastcs-0.1a3/.github/workflows/linkcheck.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      824 2023-06-28 12:15:06.000000 fastcs-0.1a3/.gitignore
+-rw-r--r--   0 runner    (1001) docker     (123)      504 2023-06-28 12:15:06.000000 fastcs-0.1a3/.pre-commit-config.yaml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:15:18.198191 fastcs-0.1a3/.vscode/
+-rw-r--r--   0 runner    (1001) docker     (123)      218 2023-06-28 12:15:06.000000 fastcs-0.1a3/.vscode/extensions.json
+-rw-r--r--   0 runner    (1001) docker     (123)      888 2023-06-28 12:15:06.000000 fastcs-0.1a3/.vscode/launch.json
+-rw-r--r--   0 runner    (1001) docker     (123)      543 2023-06-28 12:15:06.000000 fastcs-0.1a3/.vscode/settings.json
+-rw-r--r--   0 runner    (1001) docker     (123)      398 2023-06-28 12:15:06.000000 fastcs-0.1a3/.vscode/tasks.json
+-rw-r--r--   0 runner    (1001) docker     (123)     1041 2023-06-28 12:15:06.000000 fastcs-0.1a3/Dockerfile
+-rw-r--r--   0 runner    (1001) docker     (123)    11357 2023-06-28 12:15:06.000000 fastcs-0.1a3/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15659 2023-06-28 12:15:18.210192 fastcs-0.1a3/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1923 2023-06-28 12:15:06.000000 fastcs-0.1a3/README.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:15:18.202191 fastcs-0.1a3/docs/
+-rw-r--r--   0 runner    (1001) docker     (123)     6485 2023-06-28 12:15:06.000000 fastcs-0.1a3/docs/conf.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:15:18.202191 fastcs-0.1a3/docs/developer/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:15:18.202191 fastcs-0.1a3/docs/developer/explanations/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:15:18.202191 fastcs-0.1a3/docs/developer/explanations/decisions/
+-rw-r--r--   0 runner    (1001) docker     (123)      506 2023-06-28 12:15:06.000000 fastcs-0.1a3/docs/developer/explanations/decisions/0001-record-architecture-decisions.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      702 2023-06-28 12:15:06.000000 fastcs-0.1a3/docs/developer/explanations/decisions/0002-switched-to-pip-skeleton.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      558 2023-06-28 12:15:06.000000 fastcs-0.1a3/docs/developer/explanations/decisions.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:15:18.206191 fastcs-0.1a3/docs/developer/how-to/
+-rw-r--r--   0 runner    (1001) docker     (123)      955 2023-06-28 12:15:06.000000 fastcs-0.1a3/docs/developer/how-to/build-docs.rst
+-rw-r--r--   0 runner    (1001) docker     (123)       47 2023-06-28 12:15:06.000000 fastcs-0.1a3/docs/developer/how-to/contribute.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1085 2023-06-28 12:15:06.000000 fastcs-0.1a3/docs/developer/how-to/lint.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      630 2023-06-28 12:15:06.000000 fastcs-0.1a3/docs/developer/how-to/make-release.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     2880 2023-06-28 12:15:06.000000 fastcs-0.1a3/docs/developer/how-to/pin-requirements.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      418 2023-06-28 12:15:06.000000 fastcs-0.1a3/docs/developer/how-to/run-tests.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      267 2023-06-28 12:15:06.000000 fastcs-0.1a3/docs/developer/how-to/static-analysis.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      820 2023-06-28 12:15:06.000000 fastcs-0.1a3/docs/developer/how-to/test-container.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      744 2023-06-28 12:15:06.000000 fastcs-0.1a3/docs/developer/how-to/update-tools.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1404 2023-06-28 12:15:06.000000 fastcs-0.1a3/docs/developer/index.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:15:18.206191 fastcs-0.1a3/docs/developer/reference/
+-rw-r--r--   0 runner    (1001) docker     (123)     1425 2023-06-28 12:15:06.000000 fastcs-0.1a3/docs/developer/reference/standards.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:15:18.206191 fastcs-0.1a3/docs/developer/tutorials/
+-rw-r--r--   0 runner    (1001) docker     (123)     1632 2023-06-28 12:15:06.000000 fastcs-0.1a3/docs/developer/tutorials/dev-install.rst
+-rw-r--r--   0 runner    (1001) docker     (123)       65 2023-06-28 12:15:06.000000 fastcs-0.1a3/docs/genindex.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:15:18.206191 fastcs-0.1a3/docs/images/
+-rw-r--r--   0 runner    (1001) docker     (123)     2294 2023-06-28 12:15:06.000000 fastcs-0.1a3/docs/images/fastcs.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      709 2023-06-28 12:15:06.000000 fastcs-0.1a3/docs/index.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:15:18.206191 fastcs-0.1a3/docs/user/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:15:18.206191 fastcs-0.1a3/docs/user/explanations/
+-rw-r--r--   0 runner    (1001) docker     (123)      664 2023-06-28 12:15:06.000000 fastcs-0.1a3/docs/user/explanations/docs-structure.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:15:18.206191 fastcs-0.1a3/docs/user/how-to/
+-rw-r--r--   0 runner    (1001) docker     (123)      452 2023-06-28 12:15:06.000000 fastcs-0.1a3/docs/user/how-to/run-container.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1208 2023-06-28 12:15:06.000000 fastcs-0.1a3/docs/user/index.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:15:18.206191 fastcs-0.1a3/docs/user/reference/
+-rw-r--r--   0 runner    (1001) docker     (123)      256 2023-06-28 12:15:06.000000 fastcs-0.1a3/docs/user/reference/api.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:15:18.206191 fastcs-0.1a3/docs/user/tutorials/
+-rw-r--r--   0 runner    (1001) docker     (123)      991 2023-06-28 12:15:06.000000 fastcs-0.1a3/docs/user/tutorials/installation.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     3189 2023-06-28 12:15:06.000000 fastcs-0.1a3/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 12:15:18.210192 fastcs-0.1a3/setup.cfg
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:15:18.194191 fastcs-0.1a3/src/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:15:18.210192 fastcs-0.1a3/src/fastcs/
+-rw-r--r--   0 runner    (1001) docker     (123)      222 2023-06-28 12:15:06.000000 fastcs-0.1a3/src/fastcs/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      323 2023-06-28 12:15:06.000000 fastcs-0.1a3/src/fastcs/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      157 2023-06-28 12:15:18.000000 fastcs-0.1a3/src/fastcs/_version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:15:18.210192 fastcs-0.1a3/src/fastcs.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15659 2023-06-28 12:15:18.000000 fastcs-0.1a3/src/fastcs.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1666 2023-06-28 12:15:18.000000 fastcs-0.1a3/src/fastcs.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 12:15:18.000000 fastcs-0.1a3/src/fastcs.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       48 2023-06-28 12:15:18.000000 fastcs-0.1a3/src/fastcs.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      230 2023-06-28 12:15:18.000000 fastcs-0.1a3/src/fastcs.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        7 2023-06-28 12:15:18.000000 fastcs-0.1a3/src/fastcs.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:15:18.210192 fastcs-0.1a3/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)     1622 2023-06-28 12:15:06.000000 fastcs-0.1a3/tests/test_boilerplate_removed.py
+-rw-r--r--   0 runner    (1001) docker     (123)      215 2023-06-28 12:15:06.000000 fastcs-0.1a3/tests/test_cli.py
```

### Comparing `fastcs-0.1a2/.devcontainer/devcontainer.json` & `fastcs-0.1a3/.devcontainer/devcontainer.json`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a2/.github/CONTRIBUTING.rst` & `fastcs-0.1a3/.github/CONTRIBUTING.rst`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a2/.github/actions/install_requirements/action.yml` & `fastcs-0.1a3/.github/actions/install_requirements/action.yml`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a2/.github/dependabot.yml` & `fastcs-0.1a3/.github/dependabot.yml`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a2/.github/pages/make_switcher.py` & `fastcs-0.1a3/.github/pages/make_switcher.py`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a2/.github/workflows/code.yml` & `fastcs-0.1a3/.github/workflows/code.yml`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a2/.github/workflows/docs.yml` & `fastcs-0.1a3/.github/workflows/docs.yml`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a2/.github/workflows/docs_clean.yml` & `fastcs-0.1a3/.github/workflows/docs_clean.yml`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a2/.github/workflows/linkcheck.yml` & `fastcs-0.1a3/.github/workflows/linkcheck.yml`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a2/.gitignore` & `fastcs-0.1a3/.gitignore`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a2/.vscode/launch.json` & `fastcs-0.1a3/.vscode/launch.json`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a2/.vscode/settings.json` & `fastcs-0.1a3/.vscode/settings.json`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a2/Dockerfile` & `fastcs-0.1a3/Dockerfile`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a2/LICENSE` & `fastcs-0.1a3/LICENSE`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a2/PKG-INFO` & `fastcs-0.1a3/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: fastcs
-Version: 0.1a2
+Version: 0.1a3
 Summary: Control system agnostic framework for building Device support in Python that will work for both EPICS and Tango
 Author-email: Martin Gaughran <martin.gaughran@diamond.ac.uk>
 License:                                  Apache License
                                    Version 2.0, January 2004
                                 http://www.apache.org/licenses/
         
            TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION
@@ -220,26 +220,23 @@
 
 FastCS
 ===========================
 
 |code_ci| |docs_ci| |coverage| |pypi_version| |license|
 
 .. image:: https://raw.githubusercontent.com/DiamondLightSource/FastCS/main/docs/images/fastcs.svg
-    :width: 150px
-    :height: 150px
+    :width: 105px
+    :height: 105px
     :align: left
-    :class: not-in-sphinx
     :target: https://DiamondLightSource.github.io/FastCS
 
-============== ==============================================================
-PyPI           ``pip install FastCS``
-Source code    https://github.com/DiamondLightSource/FastCS
-Documentation  https://DiamondLightSource.github.io/FastCS
-Releases       https://github.com/DiamondLightSource/FastCS/releases
-============== ==============================================================
+:PyPI:           ``pip install FastCS``
+:Source code:    https://github.com/DiamondLightSource/FastCS
+:Documentation:  https://DiamondLightSource.github.io/FastCS
+:Releases:       https://github.com/DiamondLightSource/FastCS/releases
 
 FastCS is a control system agnostic framework for building Device support in
 Python that will work for both EPICS and Tango without depending on either.
 
 .. note::
 
     This repository is in an early stage of development, and doesn't currently do the above!
```

### Comparing `fastcs-0.1a2/README.rst` & `fastcs-0.1a3/README.rst`

 * *Files 4% similar despite different names*

```diff
@@ -1,25 +1,22 @@
 FastCS
 ===========================
 
 |code_ci| |docs_ci| |coverage| |pypi_version| |license|
 
 .. image:: https://raw.githubusercontent.com/DiamondLightSource/FastCS/main/docs/images/fastcs.svg
-    :width: 150px
-    :height: 150px
+    :width: 105px
+    :height: 105px
     :align: left
-    :class: not-in-sphinx
     :target: https://DiamondLightSource.github.io/FastCS
 
-============== ==============================================================
-PyPI           ``pip install FastCS``
-Source code    https://github.com/DiamondLightSource/FastCS
-Documentation  https://DiamondLightSource.github.io/FastCS
-Releases       https://github.com/DiamondLightSource/FastCS/releases
-============== ==============================================================
+:PyPI:           ``pip install FastCS``
+:Source code:    https://github.com/DiamondLightSource/FastCS
+:Documentation:  https://DiamondLightSource.github.io/FastCS
+:Releases:       https://github.com/DiamondLightSource/FastCS/releases
 
 FastCS is a control system agnostic framework for building Device support in
 Python that will work for both EPICS and Tango without depending on either.
 
 .. note::
 
     This repository is in an early stage of development, and doesn't currently do the above!
```

### Comparing `fastcs-0.1a2/docs/conf.py` & `fastcs-0.1a3/docs/conf.py`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a2/docs/developer/explanations/decisions/0002-switched-to-pip-skeleton.rst` & `fastcs-0.1a3/docs/developer/explanations/decisions/0002-switched-to-pip-skeleton.rst`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a2/docs/developer/explanations/decisions.rst` & `fastcs-0.1a3/docs/developer/explanations/decisions.rst`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a2/docs/developer/how-to/build-docs.rst` & `fastcs-0.1a3/docs/developer/how-to/build-docs.rst`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a2/docs/developer/how-to/lint.rst` & `fastcs-0.1a3/docs/developer/how-to/lint.rst`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a2/docs/developer/how-to/make-release.rst` & `fastcs-0.1a3/docs/developer/how-to/make-release.rst`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a2/docs/developer/how-to/pin-requirements.rst` & `fastcs-0.1a3/docs/developer/how-to/pin-requirements.rst`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a2/docs/developer/how-to/test-container.rst` & `fastcs-0.1a3/docs/developer/how-to/test-container.rst`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a2/docs/developer/how-to/update-tools.rst` & `fastcs-0.1a3/docs/developer/how-to/update-tools.rst`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a2/docs/developer/index.rst` & `fastcs-0.1a3/docs/developer/index.rst`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a2/docs/developer/reference/standards.rst` & `fastcs-0.1a3/docs/developer/reference/standards.rst`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a2/docs/developer/tutorials/dev-install.rst` & `fastcs-0.1a3/docs/developer/tutorials/dev-install.rst`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a2/docs/images/fastcs.svg` & `fastcs-0.1a3/docs/images/fastcs.svg`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a2/docs/user/explanations/docs-structure.rst` & `fastcs-0.1a3/docs/user/explanations/docs-structure.rst`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a2/docs/user/index.rst` & `fastcs-0.1a3/docs/user/index.rst`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a2/docs/user/tutorials/installation.rst` & `fastcs-0.1a3/docs/user/tutorials/installation.rst`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a2/pyproject.toml` & `fastcs-0.1a3/pyproject.toml`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a2/src/fastcs.egg-info/PKG-INFO` & `fastcs-0.1a3/src/fastcs.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: fastcs
-Version: 0.1a2
+Version: 0.1a3
 Summary: Control system agnostic framework for building Device support in Python that will work for both EPICS and Tango
 Author-email: Martin Gaughran <martin.gaughran@diamond.ac.uk>
 License:                                  Apache License
                                    Version 2.0, January 2004
                                 http://www.apache.org/licenses/
         
            TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION
@@ -220,26 +220,23 @@
 
 FastCS
 ===========================
 
 |code_ci| |docs_ci| |coverage| |pypi_version| |license|
 
 .. image:: https://raw.githubusercontent.com/DiamondLightSource/FastCS/main/docs/images/fastcs.svg
-    :width: 150px
-    :height: 150px
+    :width: 105px
+    :height: 105px
     :align: left
-    :class: not-in-sphinx
     :target: https://DiamondLightSource.github.io/FastCS
 
-============== ==============================================================
-PyPI           ``pip install FastCS``
-Source code    https://github.com/DiamondLightSource/FastCS
-Documentation  https://DiamondLightSource.github.io/FastCS
-Releases       https://github.com/DiamondLightSource/FastCS/releases
-============== ==============================================================
+:PyPI:           ``pip install FastCS``
+:Source code:    https://github.com/DiamondLightSource/FastCS
+:Documentation:  https://DiamondLightSource.github.io/FastCS
+:Releases:       https://github.com/DiamondLightSource/FastCS/releases
 
 FastCS is a control system agnostic framework for building Device support in
 Python that will work for both EPICS and Tango without depending on either.
 
 .. note::
 
     This repository is in an early stage of development, and doesn't currently do the above!
```

### Comparing `fastcs-0.1a2/src/fastcs.egg-info/SOURCES.txt` & `fastcs-0.1a3/src/fastcs.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a2/tests/test_boilerplate_removed.py` & `fastcs-0.1a3/tests/test_boilerplate_removed.py`

 * *Files identical despite different names*


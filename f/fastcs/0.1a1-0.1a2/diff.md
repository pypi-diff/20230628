# Comparing `tmp/fastcs-0.1a1.tar.gz` & `tmp/fastcs-0.1a2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "fastcs-0.1a1.tar", last modified: Tue Jun 27 10:59:51 2023, max compression
+gzip compressed data, was "fastcs-0.1a2.tar", last modified: Wed Jun 28 08:57:04 2023, max compression
```

## Comparing `fastcs-0.1a1.tar` & `fastcs-0.1a2.tar`

### file list

```diff
@@ -1,82 +1,82 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 10:59:51.831767 fastcs-0.1a1/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 10:59:51.823767 fastcs-0.1a1/.devcontainer/
--rw-r--r--   0 runner    (1001) docker     (123)     2143 2023-06-27 10:59:41.000000 fastcs-0.1a1/.devcontainer/devcontainer.json
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 10:59:51.823767 fastcs-0.1a1/.github/
--rw-r--r--   0 runner    (1001) docker     (123)     1344 2023-06-27 10:59:41.000000 fastcs-0.1a1/.github/CONTRIBUTING.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 10:59:51.819766 fastcs-0.1a1/.github/actions/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 10:59:51.823767 fastcs-0.1a1/.github/actions/install_requirements/
--rw-r--r--   0 runner    (1001) docker     (123)     2065 2023-06-27 10:59:41.000000 fastcs-0.1a1/.github/actions/install_requirements/action.yml
--rw-r--r--   0 runner    (1001) docker     (123)      529 2023-06-27 10:59:41.000000 fastcs-0.1a1/.github/dependabot.yml
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 10:59:51.823767 fastcs-0.1a1/.github/pages/
--rw-r--r--   0 runner    (1001) docker     (123)      237 2023-06-27 10:59:41.000000 fastcs-0.1a1/.github/pages/index.html
--rwxr-xr-x   0 runner    (1001) docker     (123)     3041 2023-06-27 10:59:41.000000 fastcs-0.1a1/.github/pages/make_switcher.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 10:59:51.823767 fastcs-0.1a1/.github/workflows/
--rw-r--r--   0 runner    (1001) docker     (123)     7631 2023-06-27 10:59:41.000000 fastcs-0.1a1/.github/workflows/code.yml
--rw-r--r--   0 runner    (1001) docker     (123)     1830 2023-06-27 10:59:41.000000 fastcs-0.1a1/.github/workflows/docs.yml
--rw-r--r--   0 runner    (1001) docker     (123)     1524 2023-06-27 10:59:41.000000 fastcs-0.1a1/.github/workflows/docs_clean.yml
--rw-r--r--   0 runner    (1001) docker     (123)      597 2023-06-27 10:59:41.000000 fastcs-0.1a1/.github/workflows/linkcheck.yml
--rw-r--r--   0 runner    (1001) docker     (123)      824 2023-06-27 10:59:41.000000 fastcs-0.1a1/.gitignore
--rw-r--r--   0 runner    (1001) docker     (123)      504 2023-06-27 10:59:41.000000 fastcs-0.1a1/.pre-commit-config.yaml
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 10:59:51.823767 fastcs-0.1a1/.vscode/
--rw-r--r--   0 runner    (1001) docker     (123)      218 2023-06-27 10:59:41.000000 fastcs-0.1a1/.vscode/extensions.json
--rw-r--r--   0 runner    (1001) docker     (123)      888 2023-06-27 10:59:41.000000 fastcs-0.1a1/.vscode/launch.json
--rw-r--r--   0 runner    (1001) docker     (123)      543 2023-06-27 10:59:41.000000 fastcs-0.1a1/.vscode/settings.json
--rw-r--r--   0 runner    (1001) docker     (123)      398 2023-06-27 10:59:41.000000 fastcs-0.1a1/.vscode/tasks.json
--rw-r--r--   0 runner    (1001) docker     (123)     1041 2023-06-27 10:59:41.000000 fastcs-0.1a1/Dockerfile
--rw-r--r--   0 runner    (1001) docker     (123)    11357 2023-06-27 10:59:41.000000 fastcs-0.1a1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15710 2023-06-27 10:59:51.831767 fastcs-0.1a1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1973 2023-06-27 10:59:41.000000 fastcs-0.1a1/README.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 10:59:51.827767 fastcs-0.1a1/docs/
--rw-r--r--   0 runner    (1001) docker     (123)     6485 2023-06-27 10:59:41.000000 fastcs-0.1a1/docs/conf.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 10:59:51.827767 fastcs-0.1a1/docs/developer/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 10:59:51.827767 fastcs-0.1a1/docs/developer/explanations/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 10:59:51.827767 fastcs-0.1a1/docs/developer/explanations/decisions/
--rw-r--r--   0 runner    (1001) docker     (123)      506 2023-06-27 10:59:41.000000 fastcs-0.1a1/docs/developer/explanations/decisions/0001-record-architecture-decisions.rst
--rw-r--r--   0 runner    (1001) docker     (123)      702 2023-06-27 10:59:41.000000 fastcs-0.1a1/docs/developer/explanations/decisions/0002-switched-to-pip-skeleton.rst
--rw-r--r--   0 runner    (1001) docker     (123)      558 2023-06-27 10:59:41.000000 fastcs-0.1a1/docs/developer/explanations/decisions.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 10:59:51.827767 fastcs-0.1a1/docs/developer/how-to/
--rw-r--r--   0 runner    (1001) docker     (123)      955 2023-06-27 10:59:41.000000 fastcs-0.1a1/docs/developer/how-to/build-docs.rst
--rw-r--r--   0 runner    (1001) docker     (123)       47 2023-06-27 10:59:41.000000 fastcs-0.1a1/docs/developer/how-to/contribute.rst
--rw-r--r--   0 runner    (1001) docker     (123)     1085 2023-06-27 10:59:41.000000 fastcs-0.1a1/docs/developer/how-to/lint.rst
--rw-r--r--   0 runner    (1001) docker     (123)      630 2023-06-27 10:59:41.000000 fastcs-0.1a1/docs/developer/how-to/make-release.rst
--rw-r--r--   0 runner    (1001) docker     (123)     2880 2023-06-27 10:59:41.000000 fastcs-0.1a1/docs/developer/how-to/pin-requirements.rst
--rw-r--r--   0 runner    (1001) docker     (123)      418 2023-06-27 10:59:41.000000 fastcs-0.1a1/docs/developer/how-to/run-tests.rst
--rw-r--r--   0 runner    (1001) docker     (123)      267 2023-06-27 10:59:41.000000 fastcs-0.1a1/docs/developer/how-to/static-analysis.rst
--rw-r--r--   0 runner    (1001) docker     (123)      820 2023-06-27 10:59:41.000000 fastcs-0.1a1/docs/developer/how-to/test-container.rst
--rw-r--r--   0 runner    (1001) docker     (123)      744 2023-06-27 10:59:41.000000 fastcs-0.1a1/docs/developer/how-to/update-tools.rst
--rw-r--r--   0 runner    (1001) docker     (123)     1404 2023-06-27 10:59:41.000000 fastcs-0.1a1/docs/developer/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 10:59:51.827767 fastcs-0.1a1/docs/developer/reference/
--rw-r--r--   0 runner    (1001) docker     (123)     1425 2023-06-27 10:59:41.000000 fastcs-0.1a1/docs/developer/reference/standards.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 10:59:51.827767 fastcs-0.1a1/docs/developer/tutorials/
--rw-r--r--   0 runner    (1001) docker     (123)     1632 2023-06-27 10:59:41.000000 fastcs-0.1a1/docs/developer/tutorials/dev-install.rst
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-06-27 10:59:41.000000 fastcs-0.1a1/docs/genindex.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 10:59:51.827767 fastcs-0.1a1/docs/images/
--rw-r--r--   0 runner    (1001) docker     (123)     2294 2023-06-27 10:59:41.000000 fastcs-0.1a1/docs/images/fastcs.svg
--rw-r--r--   0 runner    (1001) docker     (123)      732 2023-06-27 10:59:41.000000 fastcs-0.1a1/docs/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 10:59:51.827767 fastcs-0.1a1/docs/user/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 10:59:51.827767 fastcs-0.1a1/docs/user/explanations/
--rw-r--r--   0 runner    (1001) docker     (123)      664 2023-06-27 10:59:41.000000 fastcs-0.1a1/docs/user/explanations/docs-structure.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 10:59:51.827767 fastcs-0.1a1/docs/user/how-to/
--rw-r--r--   0 runner    (1001) docker     (123)      452 2023-06-27 10:59:41.000000 fastcs-0.1a1/docs/user/how-to/run-container.rst
--rw-r--r--   0 runner    (1001) docker     (123)     1208 2023-06-27 10:59:41.000000 fastcs-0.1a1/docs/user/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 10:59:51.827767 fastcs-0.1a1/docs/user/reference/
--rw-r--r--   0 runner    (1001) docker     (123)      256 2023-06-27 10:59:41.000000 fastcs-0.1a1/docs/user/reference/api.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 10:59:51.827767 fastcs-0.1a1/docs/user/tutorials/
--rw-r--r--   0 runner    (1001) docker     (123)      991 2023-06-27 10:59:41.000000 fastcs-0.1a1/docs/user/tutorials/installation.rst
--rw-r--r--   0 runner    (1001) docker     (123)     3189 2023-06-27 10:59:41.000000 fastcs-0.1a1/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-27 10:59:51.831767 fastcs-0.1a1/setup.cfg
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 10:59:51.823767 fastcs-0.1a1/src/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 10:59:51.827767 fastcs-0.1a1/src/fastcs/
--rw-r--r--   0 runner    (1001) docker     (123)      222 2023-06-27 10:59:41.000000 fastcs-0.1a1/src/fastcs/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      323 2023-06-27 10:59:41.000000 fastcs-0.1a1/src/fastcs/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)      157 2023-06-27 10:59:51.000000 fastcs-0.1a1/src/fastcs/_version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 10:59:51.831767 fastcs-0.1a1/src/fastcs.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15710 2023-06-27 10:59:51.000000 fastcs-0.1a1/src/fastcs.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1666 2023-06-27 10:59:51.000000 fastcs-0.1a1/src/fastcs.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 10:59:51.000000 fastcs-0.1a1/src/fastcs.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       48 2023-06-27 10:59:51.000000 fastcs-0.1a1/src/fastcs.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)      230 2023-06-27 10:59:51.000000 fastcs-0.1a1/src/fastcs.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)        7 2023-06-27 10:59:51.000000 fastcs-0.1a1/src/fastcs.egg-info/top_level.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 10:59:51.831767 fastcs-0.1a1/tests/
--rw-r--r--   0 runner    (1001) docker     (123)     1622 2023-06-27 10:59:41.000000 fastcs-0.1a1/tests/test_boilerplate_removed.py
--rw-r--r--   0 runner    (1001) docker     (123)      215 2023-06-27 10:59:41.000000 fastcs-0.1a1/tests/test_cli.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.753186 fastcs-0.1a2/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.749186 fastcs-0.1a2/.devcontainer/
+-rw-r--r--   0 runner    (1001) docker     (123)     2143 2023-06-28 08:56:52.000000 fastcs-0.1a2/.devcontainer/devcontainer.json
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.749186 fastcs-0.1a2/.github/
+-rw-r--r--   0 runner    (1001) docker     (123)     1344 2023-06-28 08:56:52.000000 fastcs-0.1a2/.github/CONTRIBUTING.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.745186 fastcs-0.1a2/.github/actions/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.749186 fastcs-0.1a2/.github/actions/install_requirements/
+-rw-r--r--   0 runner    (1001) docker     (123)     2065 2023-06-28 08:56:52.000000 fastcs-0.1a2/.github/actions/install_requirements/action.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      529 2023-06-28 08:56:52.000000 fastcs-0.1a2/.github/dependabot.yml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.749186 fastcs-0.1a2/.github/pages/
+-rw-r--r--   0 runner    (1001) docker     (123)      237 2023-06-28 08:56:52.000000 fastcs-0.1a2/.github/pages/index.html
+-rwxr-xr-x   0 runner    (1001) docker     (123)     3041 2023-06-28 08:56:52.000000 fastcs-0.1a2/.github/pages/make_switcher.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.749186 fastcs-0.1a2/.github/workflows/
+-rw-r--r--   0 runner    (1001) docker     (123)     7631 2023-06-28 08:56:52.000000 fastcs-0.1a2/.github/workflows/code.yml
+-rw-r--r--   0 runner    (1001) docker     (123)     1830 2023-06-28 08:56:52.000000 fastcs-0.1a2/.github/workflows/docs.yml
+-rw-r--r--   0 runner    (1001) docker     (123)     1524 2023-06-28 08:56:52.000000 fastcs-0.1a2/.github/workflows/docs_clean.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      597 2023-06-28 08:56:52.000000 fastcs-0.1a2/.github/workflows/linkcheck.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      824 2023-06-28 08:56:52.000000 fastcs-0.1a2/.gitignore
+-rw-r--r--   0 runner    (1001) docker     (123)      504 2023-06-28 08:56:52.000000 fastcs-0.1a2/.pre-commit-config.yaml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.749186 fastcs-0.1a2/.vscode/
+-rw-r--r--   0 runner    (1001) docker     (123)      218 2023-06-28 08:56:52.000000 fastcs-0.1a2/.vscode/extensions.json
+-rw-r--r--   0 runner    (1001) docker     (123)      888 2023-06-28 08:56:52.000000 fastcs-0.1a2/.vscode/launch.json
+-rw-r--r--   0 runner    (1001) docker     (123)      543 2023-06-28 08:56:52.000000 fastcs-0.1a2/.vscode/settings.json
+-rw-r--r--   0 runner    (1001) docker     (123)      398 2023-06-28 08:56:52.000000 fastcs-0.1a2/.vscode/tasks.json
+-rw-r--r--   0 runner    (1001) docker     (123)     1041 2023-06-28 08:56:52.000000 fastcs-0.1a2/Dockerfile
+-rw-r--r--   0 runner    (1001) docker     (123)    11357 2023-06-28 08:56:52.000000 fastcs-0.1a2/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15833 2023-06-28 08:57:04.753186 fastcs-0.1a2/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2097 2023-06-28 08:56:52.000000 fastcs-0.1a2/README.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.749186 fastcs-0.1a2/docs/
+-rw-r--r--   0 runner    (1001) docker     (123)     6485 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/conf.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.749186 fastcs-0.1a2/docs/developer/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.749186 fastcs-0.1a2/docs/developer/explanations/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.749186 fastcs-0.1a2/docs/developer/explanations/decisions/
+-rw-r--r--   0 runner    (1001) docker     (123)      506 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/developer/explanations/decisions/0001-record-architecture-decisions.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      702 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/developer/explanations/decisions/0002-switched-to-pip-skeleton.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      558 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/developer/explanations/decisions.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.753186 fastcs-0.1a2/docs/developer/how-to/
+-rw-r--r--   0 runner    (1001) docker     (123)      955 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/developer/how-to/build-docs.rst
+-rw-r--r--   0 runner    (1001) docker     (123)       47 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/developer/how-to/contribute.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1085 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/developer/how-to/lint.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      630 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/developer/how-to/make-release.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     2880 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/developer/how-to/pin-requirements.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      418 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/developer/how-to/run-tests.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      267 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/developer/how-to/static-analysis.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      820 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/developer/how-to/test-container.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      744 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/developer/how-to/update-tools.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1404 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/developer/index.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.753186 fastcs-0.1a2/docs/developer/reference/
+-rw-r--r--   0 runner    (1001) docker     (123)     1425 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/developer/reference/standards.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.753186 fastcs-0.1a2/docs/developer/tutorials/
+-rw-r--r--   0 runner    (1001) docker     (123)     1632 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/developer/tutorials/dev-install.rst
+-rw-r--r--   0 runner    (1001) docker     (123)       65 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/genindex.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.753186 fastcs-0.1a2/docs/images/
+-rw-r--r--   0 runner    (1001) docker     (123)     2294 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/images/fastcs.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      876 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/index.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.753186 fastcs-0.1a2/docs/user/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.753186 fastcs-0.1a2/docs/user/explanations/
+-rw-r--r--   0 runner    (1001) docker     (123)      664 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/user/explanations/docs-structure.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.753186 fastcs-0.1a2/docs/user/how-to/
+-rw-r--r--   0 runner    (1001) docker     (123)      452 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/user/how-to/run-container.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1208 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/user/index.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.753186 fastcs-0.1a2/docs/user/reference/
+-rw-r--r--   0 runner    (1001) docker     (123)      256 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/user/reference/api.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.753186 fastcs-0.1a2/docs/user/tutorials/
+-rw-r--r--   0 runner    (1001) docker     (123)      991 2023-06-28 08:56:52.000000 fastcs-0.1a2/docs/user/tutorials/installation.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     3189 2023-06-28 08:56:52.000000 fastcs-0.1a2/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 08:57:04.753186 fastcs-0.1a2/setup.cfg
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.749186 fastcs-0.1a2/src/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.753186 fastcs-0.1a2/src/fastcs/
+-rw-r--r--   0 runner    (1001) docker     (123)      222 2023-06-28 08:56:52.000000 fastcs-0.1a2/src/fastcs/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      323 2023-06-28 08:56:52.000000 fastcs-0.1a2/src/fastcs/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      157 2023-06-28 08:57:04.000000 fastcs-0.1a2/src/fastcs/_version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.753186 fastcs-0.1a2/src/fastcs.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15833 2023-06-28 08:57:04.000000 fastcs-0.1a2/src/fastcs.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1666 2023-06-28 08:57:04.000000 fastcs-0.1a2/src/fastcs.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 08:57:04.000000 fastcs-0.1a2/src/fastcs.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       48 2023-06-28 08:57:04.000000 fastcs-0.1a2/src/fastcs.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      230 2023-06-28 08:57:04.000000 fastcs-0.1a2/src/fastcs.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        7 2023-06-28 08:57:04.000000 fastcs-0.1a2/src/fastcs.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:57:04.753186 fastcs-0.1a2/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)     1622 2023-06-28 08:56:52.000000 fastcs-0.1a2/tests/test_boilerplate_removed.py
+-rw-r--r--   0 runner    (1001) docker     (123)      215 2023-06-28 08:56:52.000000 fastcs-0.1a2/tests/test_cli.py
```

### Comparing `fastcs-0.1a1/.devcontainer/devcontainer.json` & `fastcs-0.1a2/.devcontainer/devcontainer.json`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a1/.github/CONTRIBUTING.rst` & `fastcs-0.1a2/.github/CONTRIBUTING.rst`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a1/.github/actions/install_requirements/action.yml` & `fastcs-0.1a2/.github/actions/install_requirements/action.yml`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a1/.github/dependabot.yml` & `fastcs-0.1a2/.github/dependabot.yml`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a1/.github/pages/make_switcher.py` & `fastcs-0.1a2/.github/pages/make_switcher.py`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a1/.github/workflows/code.yml` & `fastcs-0.1a2/.github/workflows/code.yml`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a1/.github/workflows/docs.yml` & `fastcs-0.1a2/.github/workflows/docs.yml`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a1/.github/workflows/docs_clean.yml` & `fastcs-0.1a2/.github/workflows/docs_clean.yml`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a1/.github/workflows/linkcheck.yml` & `fastcs-0.1a2/.github/workflows/linkcheck.yml`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a1/.gitignore` & `fastcs-0.1a2/.gitignore`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a1/.vscode/launch.json` & `fastcs-0.1a2/.vscode/launch.json`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a1/.vscode/settings.json` & `fastcs-0.1a2/.vscode/settings.json`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a1/Dockerfile` & `fastcs-0.1a2/Dockerfile`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a1/LICENSE` & `fastcs-0.1a2/LICENSE`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a1/PKG-INFO` & `fastcs-0.1a2/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: fastcs
-Version: 0.1a1
+Version: 0.1a2
 Summary: Control system agnostic framework for building Device support in Python that will work for both EPICS and Tango
 Author-email: Martin Gaughran <martin.gaughran@diamond.ac.uk>
 License:                                  Apache License
                                    Version 2.0, January 2004
                                 http://www.apache.org/licenses/
         
            TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION
@@ -214,33 +214,40 @@
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Requires-Python: >=3.7
 Description-Content-Type: text/x-rst
 Provides-Extra: dev
 License-File: LICENSE
 
-|logo| FastCS
+FastCS
 ===========================
 
 |code_ci| |docs_ci| |coverage| |pypi_version| |license|
 
-FastCS is a control system agnostic framework for building Device support in
-Python that will work for both EPICS and Tango without depending on either.
-
-.. note::
-
-    This repository is in an early stage of development, and doesn't currently do the above!
+.. image:: https://raw.githubusercontent.com/DiamondLightSource/FastCS/main/docs/images/fastcs.svg
+    :width: 150px
+    :height: 150px
+    :align: left
+    :class: not-in-sphinx
+    :target: https://DiamondLightSource.github.io/FastCS
 
 ============== ==============================================================
 PyPI           ``pip install FastCS``
 Source code    https://github.com/DiamondLightSource/FastCS
 Documentation  https://DiamondLightSource.github.io/FastCS
 Releases       https://github.com/DiamondLightSource/FastCS/releases
 ============== ==============================================================
 
+FastCS is a control system agnostic framework for building Device support in
+Python that will work for both EPICS and Tango without depending on either.
+
+.. note::
+
+    This repository is in an early stage of development, and doesn't currently do the above!
+
 .. |code_ci| image:: https://github.com/DiamondLightSource/FastCS/actions/workflows/code.yml/badge.svg?branch=main
     :target: https://github.com/DiamondLightSource/FastCS/actions/workflows/code.yml
     :alt: Code CI
 
 .. |docs_ci| image:: https://github.com/DiamondLightSource/FastCS/actions/workflows/docs.yml/badge.svg?branch=main
     :target: https://github.com/DiamondLightSource/FastCS/actions/workflows/docs.yml
     :alt: Docs CI
@@ -258,9 +265,7 @@
     :alt: Apache License
 
 ..
     Anything below this line is used when viewing README.rst and will be replaced
     when included in index.rst
 
 See https://DiamondLightSource.github.io/FastCS for more detailed documentation.
-
-.. |logo| image:: https://raw.githubusercontent.com/DiamondLightSource/FastCS/main/docs/images/fastcs.svg
```

### Comparing `fastcs-0.1a1/README.rst` & `fastcs-0.1a2/README.rst`

 * *Files 5% similar despite different names*

```diff
@@ -1,26 +1,33 @@
-|logo| FastCS
+FastCS
 ===========================
 
 |code_ci| |docs_ci| |coverage| |pypi_version| |license|
 
-FastCS is a control system agnostic framework for building Device support in
-Python that will work for both EPICS and Tango without depending on either.
-
-.. note::
-
-    This repository is in an early stage of development, and doesn't currently do the above!
+.. image:: https://raw.githubusercontent.com/DiamondLightSource/FastCS/main/docs/images/fastcs.svg
+    :width: 150px
+    :height: 150px
+    :align: left
+    :class: not-in-sphinx
+    :target: https://DiamondLightSource.github.io/FastCS
 
 ============== ==============================================================
 PyPI           ``pip install FastCS``
 Source code    https://github.com/DiamondLightSource/FastCS
 Documentation  https://DiamondLightSource.github.io/FastCS
 Releases       https://github.com/DiamondLightSource/FastCS/releases
 ============== ==============================================================
 
+FastCS is a control system agnostic framework for building Device support in
+Python that will work for both EPICS and Tango without depending on either.
+
+.. note::
+
+    This repository is in an early stage of development, and doesn't currently do the above!
+
 .. |code_ci| image:: https://github.com/DiamondLightSource/FastCS/actions/workflows/code.yml/badge.svg?branch=main
     :target: https://github.com/DiamondLightSource/FastCS/actions/workflows/code.yml
     :alt: Code CI
 
 .. |docs_ci| image:: https://github.com/DiamondLightSource/FastCS/actions/workflows/docs.yml/badge.svg?branch=main
     :target: https://github.com/DiamondLightSource/FastCS/actions/workflows/docs.yml
     :alt: Docs CI
@@ -38,9 +45,7 @@
     :alt: Apache License
 
 ..
     Anything below this line is used when viewing README.rst and will be replaced
     when included in index.rst
 
 See https://DiamondLightSource.github.io/FastCS for more detailed documentation.
-
-.. |logo| image:: https://raw.githubusercontent.com/DiamondLightSource/FastCS/main/docs/images/fastcs.svg
```

### Comparing `fastcs-0.1a1/docs/conf.py` & `fastcs-0.1a2/docs/conf.py`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a1/docs/developer/explanations/decisions/0002-switched-to-pip-skeleton.rst` & `fastcs-0.1a2/docs/developer/explanations/decisions/0002-switched-to-pip-skeleton.rst`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a1/docs/developer/explanations/decisions.rst` & `fastcs-0.1a2/docs/developer/explanations/decisions.rst`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a1/docs/developer/how-to/build-docs.rst` & `fastcs-0.1a2/docs/developer/how-to/build-docs.rst`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a1/docs/developer/how-to/lint.rst` & `fastcs-0.1a2/docs/developer/how-to/lint.rst`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a1/docs/developer/how-to/make-release.rst` & `fastcs-0.1a2/docs/developer/how-to/make-release.rst`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a1/docs/developer/how-to/pin-requirements.rst` & `fastcs-0.1a2/docs/developer/how-to/pin-requirements.rst`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a1/docs/developer/how-to/test-container.rst` & `fastcs-0.1a2/docs/developer/how-to/test-container.rst`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a1/docs/developer/how-to/update-tools.rst` & `fastcs-0.1a2/docs/developer/how-to/update-tools.rst`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a1/docs/developer/index.rst` & `fastcs-0.1a2/docs/developer/index.rst`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a1/docs/developer/reference/standards.rst` & `fastcs-0.1a2/docs/developer/reference/standards.rst`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a1/docs/developer/tutorials/dev-install.rst` & `fastcs-0.1a2/docs/developer/tutorials/dev-install.rst`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a1/docs/images/fastcs.svg` & `fastcs-0.1a2/docs/images/fastcs.svg`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a1/docs/index.rst` & `fastcs-0.1a2/docs/index.rst`

 * *Files 14% similar despite different names*

```diff
@@ -1,46 +1,55 @@
 00000000: 3a68 746d 6c5f 7468 656d 652e 7369 6465  :html_theme.side
 00000010: 6261 725f 7365 636f 6e64 6172 792e 7265  bar_secondary.re
 00000020: 6d6f 7665 3a0a 0a2e 2e20 696e 636c 7564  move:.... includ
 00000030: 653a 3a20 2e2e 2f52 4541 444d 452e 7273  e:: ../README.rs
 00000040: 740a 2020 2020 3a65 6e64 2d62 6566 6f72  t.    :end-befor
 00000050: 653a 2077 6865 6e20 696e 636c 7564 6564  e: when included
 00000060: 2069 6e20 696e 6465 782e 7273 740a 0a2e   in index.rst...
-00000070: 2e20 7c6c 6f67 6f7c 2072 6570 6c61 6365  . |logo| replace
-00000080: 3a3a 205c 0a0a 486f 7720 7468 6520 646f  :: \..How the do
-00000090: 6375 6d65 6e74 6174 696f 6e20 6973 2073  cumentation is s
-000000a0: 7472 7563 7475 7265 640a 2d2d 2d2d 2d2d  tructured.------
-000000b0: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
-000000c0: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d0a 0a54  -------------..T
-000000d0: 6865 2064 6f63 756d 656e 7461 7469 6f6e  he documentation
-000000e0: 2069 7320 7370 6c69 7420 696e 746f 2032   is split into 2
-000000f0: 2073 6563 7469 6f6e 733a 0a0a 2e2e 2067   sections:.... g
-00000100: 7269 643a 3a20 320a 0a20 2020 202e 2e20  rid:: 2..    .. 
-00000110: 6772 6964 2d69 7465 6d2d 6361 7264 3a3a  grid-item-card::
-00000120: 203a 6d61 7465 7269 616c 2d72 6567 756c   :material-regul
-00000130: 6172 3a60 7065 7273 6f6e 3b34 656d 600a  ar:`person;4em`.
-00000140: 2020 2020 2020 2020 3a6c 696e 6b3a 2075          :link: u
-00000150: 7365 722f 696e 6465 780a 2020 2020 2020  ser/index.      
-00000160: 2020 3a6c 696e 6b2d 7479 7065 3a20 646f    :link-type: do
-00000170: 630a 0a20 2020 2020 2020 2054 6865 2055  c..        The U
-00000180: 7365 7220 4775 6964 6520 636f 6e74 6169  ser Guide contai
-00000190: 6e73 2064 6f63 756d 656e 7461 7469 6f6e  ns documentation
-000001a0: 206f 6e20 686f 7720 746f 2069 6e73 7461   on how to insta
-000001b0: 6c6c 2061 6e64 2075 7365 2046 6173 7443  ll and use FastC
-000001c0: 532e 0a0a 2020 2020 2e2e 2067 7269 642d  S...    .. grid-
-000001d0: 6974 656d 2d63 6172 643a 3a20 3a6d 6174  item-card:: :mat
-000001e0: 6572 6961 6c2d 7265 6775 6c61 723a 6063  erial-regular:`c
-000001f0: 6f64 653b 3465 6d60 0a20 2020 2020 2020  ode;4em`.       
-00000200: 203a 6c69 6e6b 3a20 6465 7665 6c6f 7065   :link: develope
-00000210: 722f 696e 6465 780a 2020 2020 2020 2020  r/index.        
-00000220: 3a6c 696e 6b2d 7479 7065 3a20 646f 630a  :link-type: doc.
-00000230: 0a20 2020 2020 2020 2054 6865 2044 6576  .        The Dev
-00000240: 656c 6f70 6572 2047 7569 6465 2063 6f6e  eloper Guide con
-00000250: 7461 696e 7320 646f 6375 6d65 6e74 6174  tains documentat
-00000260: 696f 6e20 6f6e 2068 6f77 2074 6f20 6465  ion on how to de
-00000270: 7665 6c6f 7020 616e 6420 636f 6e74 7269  velop and contri
-00000280: 6275 7465 2063 6861 6e67 6573 2062 6163  bute changes bac
-00000290: 6b20 746f 2046 6173 7443 532e 0a0a 2e2e  k to FastCS.....
-000002a0: 2074 6f63 7472 6565 3a3a 0a20 2020 203a   toctree::.    :
-000002b0: 6869 6464 656e 3a0a 0a20 2020 2075 7365  hidden:..    use
-000002c0: 722f 696e 6465 780a 2020 2020 6465 7665  r/index.    deve
-000002d0: 6c6f 7065 722f 696e 6465 780a            loper/index.
+00000070: 2e20 7261 773a 3a20 6874 6d6c 0a0a 2020  . raw:: html..  
+00000080: 2020 3c73 7479 6c65 3e0a 2020 2020 2f2a    <style>.    /*
+00000090: 2044 6f6e 2774 2064 6973 706c 6179 206c   Don't display l
+000000a0: 6f67 6f20 7768 656e 2072 656e 6465 7264  ogo when renderd
+000000b0: 2069 6e20 7370 6869 6e78 2072 6174 6865   in sphinx rathe
+000000c0: 7220 7468 616e 2047 6974 4875 622f 5079  r than GitHub/Py
+000000d0: 5049 202a 2f0a 2020 2020 2e6e 6f74 2d69  PI */.    .not-i
+000000e0: 6e2d 7370 6869 6e78 207b 0a20 2020 2020  n-sphinx {.     
+000000f0: 2020 2064 6973 706c 6179 3a20 6e6f 6e65     display: none
+00000100: 3b0a 2020 2020 7d0a 2020 2020 3c2f 7374  ;.    }.    </st
+00000110: 796c 653e 0a0a 486f 7720 7468 6520 646f  yle>..How the do
+00000120: 6375 6d65 6e74 6174 696f 6e20 6973 2073  cumentation is s
+00000130: 7472 7563 7475 7265 640a 2d2d 2d2d 2d2d  tructured.------
+00000140: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
+00000150: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d0a 0a54  -------------..T
+00000160: 6865 2064 6f63 756d 656e 7461 7469 6f6e  he documentation
+00000170: 2069 7320 7370 6c69 7420 696e 746f 2032   is split into 2
+00000180: 2073 6563 7469 6f6e 733a 0a0a 2e2e 2067   sections:.... g
+00000190: 7269 643a 3a20 320a 0a20 2020 202e 2e20  rid:: 2..    .. 
+000001a0: 6772 6964 2d69 7465 6d2d 6361 7264 3a3a  grid-item-card::
+000001b0: 203a 6d61 7465 7269 616c 2d72 6567 756c   :material-regul
+000001c0: 6172 3a60 7065 7273 6f6e 3b34 656d 600a  ar:`person;4em`.
+000001d0: 2020 2020 2020 2020 3a6c 696e 6b3a 2075          :link: u
+000001e0: 7365 722f 696e 6465 780a 2020 2020 2020  ser/index.      
+000001f0: 2020 3a6c 696e 6b2d 7479 7065 3a20 646f    :link-type: do
+00000200: 630a 0a20 2020 2020 2020 2054 6865 2055  c..        The U
+00000210: 7365 7220 4775 6964 6520 636f 6e74 6169  ser Guide contai
+00000220: 6e73 2064 6f63 756d 656e 7461 7469 6f6e  ns documentation
+00000230: 206f 6e20 686f 7720 746f 2069 6e73 7461   on how to insta
+00000240: 6c6c 2061 6e64 2075 7365 2046 6173 7443  ll and use FastC
+00000250: 532e 0a0a 2020 2020 2e2e 2067 7269 642d  S...    .. grid-
+00000260: 6974 656d 2d63 6172 643a 3a20 3a6d 6174  item-card:: :mat
+00000270: 6572 6961 6c2d 7265 6775 6c61 723a 6063  erial-regular:`c
+00000280: 6f64 653b 3465 6d60 0a20 2020 2020 2020  ode;4em`.       
+00000290: 203a 6c69 6e6b 3a20 6465 7665 6c6f 7065   :link: develope
+000002a0: 722f 696e 6465 780a 2020 2020 2020 2020  r/index.        
+000002b0: 3a6c 696e 6b2d 7479 7065 3a20 646f 630a  :link-type: doc.
+000002c0: 0a20 2020 2020 2020 2054 6865 2044 6576  .        The Dev
+000002d0: 656c 6f70 6572 2047 7569 6465 2063 6f6e  eloper Guide con
+000002e0: 7461 696e 7320 646f 6375 6d65 6e74 6174  tains documentat
+000002f0: 696f 6e20 6f6e 2068 6f77 2074 6f20 6465  ion on how to de
+00000300: 7665 6c6f 7020 616e 6420 636f 6e74 7269  velop and contri
+00000310: 6275 7465 2063 6861 6e67 6573 2062 6163  bute changes bac
+00000320: 6b20 746f 2046 6173 7443 532e 0a0a 2e2e  k to FastCS.....
+00000330: 2074 6f63 7472 6565 3a3a 0a20 2020 203a   toctree::.    :
+00000340: 6869 6464 656e 3a0a 0a20 2020 2075 7365  hidden:..    use
+00000350: 722f 696e 6465 780a 2020 2020 6465 7665  r/index.    deve
+00000360: 6c6f 7065 722f 696e 6465 780a            loper/index.
```

### Comparing `fastcs-0.1a1/docs/user/explanations/docs-structure.rst` & `fastcs-0.1a2/docs/user/explanations/docs-structure.rst`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a1/docs/user/index.rst` & `fastcs-0.1a2/docs/user/index.rst`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a1/docs/user/tutorials/installation.rst` & `fastcs-0.1a2/docs/user/tutorials/installation.rst`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a1/pyproject.toml` & `fastcs-0.1a2/pyproject.toml`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a1/src/fastcs.egg-info/PKG-INFO` & `fastcs-0.1a2/src/fastcs.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: fastcs
-Version: 0.1a1
+Version: 0.1a2
 Summary: Control system agnostic framework for building Device support in Python that will work for both EPICS and Tango
 Author-email: Martin Gaughran <martin.gaughran@diamond.ac.uk>
 License:                                  Apache License
                                    Version 2.0, January 2004
                                 http://www.apache.org/licenses/
         
            TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION
@@ -214,33 +214,40 @@
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Requires-Python: >=3.7
 Description-Content-Type: text/x-rst
 Provides-Extra: dev
 License-File: LICENSE
 
-|logo| FastCS
+FastCS
 ===========================
 
 |code_ci| |docs_ci| |coverage| |pypi_version| |license|
 
-FastCS is a control system agnostic framework for building Device support in
-Python that will work for both EPICS and Tango without depending on either.
-
-.. note::
-
-    This repository is in an early stage of development, and doesn't currently do the above!
+.. image:: https://raw.githubusercontent.com/DiamondLightSource/FastCS/main/docs/images/fastcs.svg
+    :width: 150px
+    :height: 150px
+    :align: left
+    :class: not-in-sphinx
+    :target: https://DiamondLightSource.github.io/FastCS
 
 ============== ==============================================================
 PyPI           ``pip install FastCS``
 Source code    https://github.com/DiamondLightSource/FastCS
 Documentation  https://DiamondLightSource.github.io/FastCS
 Releases       https://github.com/DiamondLightSource/FastCS/releases
 ============== ==============================================================
 
+FastCS is a control system agnostic framework for building Device support in
+Python that will work for both EPICS and Tango without depending on either.
+
+.. note::
+
+    This repository is in an early stage of development, and doesn't currently do the above!
+
 .. |code_ci| image:: https://github.com/DiamondLightSource/FastCS/actions/workflows/code.yml/badge.svg?branch=main
     :target: https://github.com/DiamondLightSource/FastCS/actions/workflows/code.yml
     :alt: Code CI
 
 .. |docs_ci| image:: https://github.com/DiamondLightSource/FastCS/actions/workflows/docs.yml/badge.svg?branch=main
     :target: https://github.com/DiamondLightSource/FastCS/actions/workflows/docs.yml
     :alt: Docs CI
@@ -258,9 +265,7 @@
     :alt: Apache License
 
 ..
     Anything below this line is used when viewing README.rst and will be replaced
     when included in index.rst
 
 See https://DiamondLightSource.github.io/FastCS for more detailed documentation.
-
-.. |logo| image:: https://raw.githubusercontent.com/DiamondLightSource/FastCS/main/docs/images/fastcs.svg
```

### Comparing `fastcs-0.1a1/src/fastcs.egg-info/SOURCES.txt` & `fastcs-0.1a2/src/fastcs.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `fastcs-0.1a1/tests/test_boilerplate_removed.py` & `fastcs-0.1a2/tests/test_boilerplate_removed.py`

 * *Files identical despite different names*


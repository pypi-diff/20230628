# Comparing `tmp/gto-0.3.3.tar.gz` & `tmp/gto-0.3.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "gto-0.3.3.tar", last modified: Thu Jun  8 15:55:25 2023, max compression
+gzip compressed data, was "gto-0.3.4.tar", last modified: Wed Jun 28 11:32:12 2023, max compression
```

## Comparing `gto-0.3.3.tar` & `gto-0.3.4.tar`

### file list

```diff
@@ -1,64 +1,64 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-08 15:55:25.642439 gto-0.3.3/
--rw-r--r--   0 runner    (1001) docker     (123)      164 2023-06-08 15:55:09.000000 gto-0.3.3/.coveragerc
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-08 15:55:25.626438 gto-0.3.3/.github/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-08 15:55:25.630438 gto-0.3.3/.github/ISSUE_TEMPLATE/
--rw-r--r--   0 runner    (1001) docker     (123)     1358 2023-06-08 15:55:09.000000 gto-0.3.3/.github/ISSUE_TEMPLATE/epic-or-story.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-08 15:55:25.630438 gto-0.3.3/.github/workflows/
--rw-r--r--   0 runner    (1001) docker     (123)     3442 2023-06-08 15:55:09.000000 gto-0.3.3/.github/workflows/check-test-release.yml
--rw-r--r--   0 runner    (1001) docker     (123)     2071 2023-06-08 15:55:09.000000 gto-0.3.3/.gitignore
--rw-r--r--   0 runner    (1001) docker     (123)     1457 2023-06-08 15:55:09.000000 gto-0.3.3/.pre-commit-config.yaml
--rw-r--r--   0 runner    (1001) docker     (123)    20057 2023-06-08 15:55:09.000000 gto-0.3.3/.pylintrc
--rw-r--r--   0 runner    (1001) docker     (123)    11345 2023-06-08 15:55:09.000000 gto-0.3.3/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     3499 2023-06-08 15:55:25.642439 gto-0.3.3/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2765 2023-06-08 15:55:09.000000 gto-0.3.3/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-08 15:55:25.634439 gto-0.3.3/gto/
--rw-r--r--   0 runner    (1001) docker     (123)      265 2023-06-08 15:55:09.000000 gto-0.3.3/gto/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      160 2023-06-08 15:55:25.000000 gto-0.3.3/gto/_gto_version.py
--rw-r--r--   0 runner    (1001) docker     (123)      404 2023-06-08 15:55:09.000000 gto-0.3.3/gto/_version.py
--rw-r--r--   0 runner    (1001) docker     (123)    16090 2023-06-08 15:55:09.000000 gto-0.3.3/gto/api.py
--rw-r--r--   0 runner    (1001) docker     (123)    19695 2023-06-08 15:55:09.000000 gto-0.3.3/gto/base.py
--rw-r--r--   0 runner    (1001) docker     (123)    25318 2023-06-08 15:55:09.000000 gto-0.3.3/gto/cli.py
--rw-r--r--   0 runner    (1001) docker     (123)      501 2023-06-08 15:55:09.000000 gto-0.3.3/gto/commit_message_generator.py
--rw-r--r--   0 runner    (1001) docker     (123)     4102 2023-06-08 15:55:09.000000 gto-0.3.3/gto/config.py
--rw-r--r--   0 runner    (1001) docker     (123)     3713 2023-06-08 15:55:09.000000 gto-0.3.3/gto/constants.py
--rw-r--r--   0 runner    (1001) docker     (123)     5762 2023-06-08 15:55:09.000000 gto-0.3.3/gto/exceptions.py
--rw-r--r--   0 runner    (1001) docker     (123)     1931 2023-06-08 15:55:09.000000 gto-0.3.3/gto/ext.py
--rw-r--r--   0 runner    (1001) docker     (123)     7367 2023-06-08 15:55:09.000000 gto-0.3.3/gto/git_utils.py
--rw-r--r--   0 runner    (1001) docker     (123)    18038 2023-06-08 15:55:09.000000 gto-0.3.3/gto/index.py
--rw-r--r--   0 runner    (1001) docker     (123)      763 2023-06-08 15:55:09.000000 gto-0.3.3/gto/log.py
--rw-r--r--   0 runner    (1001) docker     (123)    20901 2023-06-08 15:55:09.000000 gto-0.3.3/gto/registry.py
--rw-r--r--   0 runner    (1001) docker     (123)    11221 2023-06-08 15:55:09.000000 gto-0.3.3/gto/tag.py
--rw-r--r--   0 runner    (1001) docker     (123)     1720 2023-06-08 15:55:09.000000 gto-0.3.3/gto/ui.py
--rw-r--r--   0 runner    (1001) docker     (123)     2990 2023-06-08 15:55:09.000000 gto-0.3.3/gto/utils.py
--rw-r--r--   0 runner    (1001) docker     (123)     3123 2023-06-08 15:55:09.000000 gto-0.3.3/gto/versions.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-08 15:55:25.638439 gto-0.3.3/gto.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     3499 2023-06-08 15:55:25.000000 gto-0.3.3/gto.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1112 2023-06-08 15:55:25.000000 gto-0.3.3/gto.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-08 15:55:25.000000 gto-0.3.3/gto.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       84 2023-06-08 15:55:25.000000 gto-0.3.3/gto.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-08 15:55:25.000000 gto-0.3.3/gto.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)      236 2023-06-08 15:55:25.000000 gto-0.3.3/gto.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       10 2023-06-08 15:55:25.000000 gto-0.3.3/gto.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)      207 2023-06-08 15:55:09.000000 gto-0.3.3/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)       41 2023-06-08 15:55:09.000000 gto-0.3.3/renovate.json
--rw-r--r--   0 runner    (1001) docker     (123)     1152 2023-06-08 15:55:25.646439 gto-0.3.3/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2137 2023-06-08 15:55:09.000000 gto-0.3.3/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-08 15:55:25.642439 gto-0.3.3/tests/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-08 15:55:09.000000 gto-0.3.3/tests/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3250 2023-06-08 15:55:09.000000 gto-0.3.3/tests/conftest.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-08 15:55:25.642439 gto-0.3.3/tests/resources/
--rw-r--r--   0 runner    (1001) docker     (123)      759 2023-06-08 15:55:09.000000 gto-0.3.3/tests/resources/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1568 2023-06-08 15:55:09.000000 gto-0.3.3/tests/resources/sample_remote_repo_expected_history_churn.json
--rw-r--r--   0 runner    (1001) docker     (123)      703 2023-06-08 15:55:09.000000 gto-0.3.3/tests/resources/sample_remote_repo_expected_registry.json
--rw-r--r--   0 runner    (1001) docker     (123)      563 2023-06-08 15:55:09.000000 gto-0.3.3/tests/skip_presets.py
--rw-r--r--   0 runner    (1001) docker     (123)    22113 2023-06-08 15:55:09.000000 gto-0.3.3/tests/test_api.py
--rw-r--r--   0 runner    (1001) docker     (123)    10301 2023-06-08 15:55:09.000000 gto-0.3.3/tests/test_cli.py
--rw-r--r--   0 runner    (1001) docker     (123)     2772 2023-06-08 15:55:09.000000 gto-0.3.3/tests/test_config.py
--rw-r--r--   0 runner    (1001) docker     (123)     1202 2023-06-08 15:55:09.000000 gto-0.3.3/tests/test_constants.py
--rw-r--r--   0 runner    (1001) docker     (123)    13338 2023-06-08 15:55:09.000000 gto-0.3.3/tests/test_git_utils.py
--rw-r--r--   0 runner    (1001) docker     (123)     3241 2023-06-08 15:55:09.000000 gto-0.3.3/tests/test_index.py
--rw-r--r--   0 runner    (1001) docker     (123)    19732 2023-06-08 15:55:09.000000 gto-0.3.3/tests/test_registry.py
--rw-r--r--   0 runner    (1001) docker     (123)     5427 2023-06-08 15:55:09.000000 gto-0.3.3/tests/test_showcase.py
--rw-r--r--   0 runner    (1001) docker     (123)     3965 2023-06-08 15:55:09.000000 gto-0.3.3/tests/test_tag.py
--rw-r--r--   0 runner    (1001) docker     (123)      816 2023-06-08 15:55:09.000000 gto-0.3.3/tests/test_versions.py
--rw-r--r--   0 runner    (1001) docker     (123)     1605 2023-06-08 15:55:09.000000 gto-0.3.3/tests/utils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:32:12.307748 gto-0.3.4/
+-rw-r--r--   0 runner    (1001) docker     (123)      164 2023-06-28 11:31:48.000000 gto-0.3.4/.coveragerc
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:32:12.295747 gto-0.3.4/.github/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:32:12.295747 gto-0.3.4/.github/ISSUE_TEMPLATE/
+-rw-r--r--   0 runner    (1001) docker     (123)     1358 2023-06-28 11:31:48.000000 gto-0.3.4/.github/ISSUE_TEMPLATE/epic-or-story.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:32:12.299747 gto-0.3.4/.github/workflows/
+-rw-r--r--   0 runner    (1001) docker     (123)     3074 2023-06-28 11:31:48.000000 gto-0.3.4/.github/workflows/check-test-release.yml
+-rw-r--r--   0 runner    (1001) docker     (123)     2071 2023-06-28 11:31:48.000000 gto-0.3.4/.gitignore
+-rw-r--r--   0 runner    (1001) docker     (123)     1457 2023-06-28 11:31:48.000000 gto-0.3.4/.pre-commit-config.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)    20057 2023-06-28 11:31:48.000000 gto-0.3.4/.pylintrc
+-rw-r--r--   0 runner    (1001) docker     (123)    11345 2023-06-28 11:31:48.000000 gto-0.3.4/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     3717 2023-06-28 11:32:12.307748 gto-0.3.4/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2881 2023-06-28 11:31:48.000000 gto-0.3.4/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:32:12.303747 gto-0.3.4/gto/
+-rw-r--r--   0 runner    (1001) docker     (123)      265 2023-06-28 11:31:48.000000 gto-0.3.4/gto/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      160 2023-06-28 11:32:12.000000 gto-0.3.4/gto/_gto_version.py
+-rw-r--r--   0 runner    (1001) docker     (123)      404 2023-06-28 11:31:48.000000 gto-0.3.4/gto/_version.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16090 2023-06-28 11:31:48.000000 gto-0.3.4/gto/api.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19695 2023-06-28 11:31:48.000000 gto-0.3.4/gto/base.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25318 2023-06-28 11:31:48.000000 gto-0.3.4/gto/cli.py
+-rw-r--r--   0 runner    (1001) docker     (123)      501 2023-06-28 11:31:48.000000 gto-0.3.4/gto/commit_message_generator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4102 2023-06-28 11:31:48.000000 gto-0.3.4/gto/config.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3713 2023-06-28 11:31:48.000000 gto-0.3.4/gto/constants.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5762 2023-06-28 11:31:48.000000 gto-0.3.4/gto/exceptions.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1931 2023-06-28 11:31:48.000000 gto-0.3.4/gto/ext.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7367 2023-06-28 11:31:48.000000 gto-0.3.4/gto/git_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18038 2023-06-28 11:31:48.000000 gto-0.3.4/gto/index.py
+-rw-r--r--   0 runner    (1001) docker     (123)      763 2023-06-28 11:31:48.000000 gto-0.3.4/gto/log.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20901 2023-06-28 11:31:48.000000 gto-0.3.4/gto/registry.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11210 2023-06-28 11:31:48.000000 gto-0.3.4/gto/tag.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1720 2023-06-28 11:31:48.000000 gto-0.3.4/gto/ui.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2990 2023-06-28 11:31:48.000000 gto-0.3.4/gto/utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3123 2023-06-28 11:31:48.000000 gto-0.3.4/gto/versions.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:32:12.303747 gto-0.3.4/gto.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     3717 2023-06-28 11:32:12.000000 gto-0.3.4/gto.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1112 2023-06-28 11:32:12.000000 gto-0.3.4/gto.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 11:32:12.000000 gto-0.3.4/gto.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       84 2023-06-28 11:32:12.000000 gto-0.3.4/gto.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 11:32:12.000000 gto-0.3.4/gto.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)      236 2023-06-28 11:32:12.000000 gto-0.3.4/gto.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       10 2023-06-28 11:32:12.000000 gto-0.3.4/gto.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      207 2023-06-28 11:31:48.000000 gto-0.3.4/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       41 2023-06-28 11:31:48.000000 gto-0.3.4/renovate.json
+-rw-r--r--   0 runner    (1001) docker     (123)     1152 2023-06-28 11:32:12.311748 gto-0.3.4/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2237 2023-06-28 11:31:48.000000 gto-0.3.4/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:32:12.307748 gto-0.3.4/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 11:31:48.000000 gto-0.3.4/tests/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3250 2023-06-28 11:31:48.000000 gto-0.3.4/tests/conftest.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:32:12.307748 gto-0.3.4/tests/resources/
+-rw-r--r--   0 runner    (1001) docker     (123)      759 2023-06-28 11:31:48.000000 gto-0.3.4/tests/resources/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1568 2023-06-28 11:31:48.000000 gto-0.3.4/tests/resources/sample_remote_repo_expected_history_churn.json
+-rw-r--r--   0 runner    (1001) docker     (123)      703 2023-06-28 11:31:48.000000 gto-0.3.4/tests/resources/sample_remote_repo_expected_registry.json
+-rw-r--r--   0 runner    (1001) docker     (123)      563 2023-06-28 11:31:48.000000 gto-0.3.4/tests/skip_presets.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22732 2023-06-28 11:31:48.000000 gto-0.3.4/tests/test_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10301 2023-06-28 11:31:48.000000 gto-0.3.4/tests/test_cli.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2772 2023-06-28 11:31:48.000000 gto-0.3.4/tests/test_config.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1202 2023-06-28 11:31:48.000000 gto-0.3.4/tests/test_constants.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13338 2023-06-28 11:31:48.000000 gto-0.3.4/tests/test_git_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3241 2023-06-28 11:31:48.000000 gto-0.3.4/tests/test_index.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19732 2023-06-28 11:31:48.000000 gto-0.3.4/tests/test_registry.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5427 2023-06-28 11:31:48.000000 gto-0.3.4/tests/test_showcase.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3965 2023-06-28 11:31:48.000000 gto-0.3.4/tests/test_tag.py
+-rw-r--r--   0 runner    (1001) docker     (123)      816 2023-06-28 11:31:48.000000 gto-0.3.4/tests/test_versions.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1605 2023-06-28 11:31:48.000000 gto-0.3.4/tests/utils.py
```

### Comparing `gto-0.3.3/.github/ISSUE_TEMPLATE/epic-or-story.md` & `gto-0.3.4/.github/ISSUE_TEMPLATE/epic-or-story.md`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/.github/workflows/check-test-release.yml` & `gto-0.3.4/.github/workflows/check-test-release.yml`

 * *Files 11% similar despite different names*

```diff
@@ -33,15 +33,15 @@
   test:
     if: startsWith(github.ref, 'refs/tags') || github.event_name == 'pull_request' || github.event_name == 'schedule' || github.repository_owner != 'iterative'
     name: Test ${{ matrix.os }} with py${{ matrix.python }}
     runs-on: ${{ matrix.os }}
     strategy:
       matrix:
         os: [ubuntu-latest, macos-latest, windows-latest]
-        python: ["3.7", "3.8", "3.9"]
+        python: ["3.7", "3.8", "3.9", "3.10"]
       fail-fast: false
     timeout-minutes: 10
     steps:
     - uses: actions/checkout@v3
       with:
         fetch-depth: 0
     - uses: actions/setup-python@v4
@@ -88,17 +88,7 @@
         password: ${{ secrets.PYPI_TOKEN }}
         upload: ${{ github.event_name == 'push' && startsWith(github.ref, 'refs/tags') }}
     - id: meta
       name: Changelog
       run: |
         echo ::set-output name=tag::${GITHUB_REF#refs/tags/}
         git log --pretty='format:%d%n- %s%n%b---' $(git tag --sort=v:refname | tail -n2 | head -n1)..HEAD > _CHANGES.md
-    # - if: github.event_name == 'push' && startsWith(github.ref, 'refs/tags')
-    #   uses: softprops/action-gh-release@v1
-    #   env:
-    #     GITHUB_TOKEN: ${{ secrets.GH_TOKEN }}
-    #   with:
-    #     name: gto ${{ steps.meta.outputs.tag }} alpha
-    #     body_path: _CHANGES.md
-    #     draft: true
-    #     files: |
-    #       dist/${{ steps.dist.outputs.whl }}
```

### Comparing `gto-0.3.3/.gitignore` & `gto-0.3.4/.gitignore`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/.pre-commit-config.yaml` & `gto-0.3.4/.pre-commit-config.yaml`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/.pylintrc` & `gto-0.3.4/.pylintrc`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/LICENSE` & `gto-0.3.4/LICENSE`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/PKG-INFO` & `gto-0.3.4/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,22 +1,24 @@
 Metadata-Version: 2.1
 Name: gto
-Version: 0.3.3
+Version: 0.3.4
 Summary: Version and deploy your models following GitOps principles
 Download-URL: https://github.com/iterative/gto
 Author: Alexander Guschin
 Author-email: aguschin@iterative.ai
 License: Apache License 2.0
 Keywords: git repo repository artifact registry developer-tools collaboration
 Classifier: Development Status :: 2 - Pre-Alpha
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
+Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
 Requires-Python: >=3.6
 Description-Content-Type: text/markdown
 Provides-Extra: tests
 License-File: LICENSE
 
 # GTO
 
@@ -28,18 +30,20 @@
 
 - Registry: Track new artifacts and their versions for releases and significant
   changes.
 - Lifecycle Management: Create actionable stages for versions marking status of
   artifact or it's readiness to be consumed by a specific environment.
 - GitOps: Signal CI/CD automation or other downstream systems to act upon these
   new versions and lifecycle updates.
-- Enrichments: Annotate and query artifact metadata with additional information.
 
 GTO works by creating annotated Git tags in a standard format.
 
+💡 Together with [DVC](https://dvc.org), GTO serves as a backbone for Git-based
+[Iterative Studio Model Registry](https://dvc.org/doc/studio/user-guide/model-registry/what-is-a-model-registry).
+
 ## Installation
 
 GTO requires Python 3. It works on any OS.
 
 ```console
 $ pip install gto
 ```
```

#### encoding

```diff
@@ -1 +1 @@
-us-ascii
+utf-8
```

### Comparing `gto-0.3.3/README.md` & `gto-0.3.4/README.md`

 * *Files 12% similar despite different names*

```diff
@@ -8,18 +8,20 @@
 
 - Registry: Track new artifacts and their versions for releases and significant
   changes.
 - Lifecycle Management: Create actionable stages for versions marking status of
   artifact or it's readiness to be consumed by a specific environment.
 - GitOps: Signal CI/CD automation or other downstream systems to act upon these
   new versions and lifecycle updates.
-- Enrichments: Annotate and query artifact metadata with additional information.
 
 GTO works by creating annotated Git tags in a standard format.
 
+💡 Together with [DVC](https://dvc.org), GTO serves as a backbone for Git-based
+[Iterative Studio Model Registry](https://dvc.org/doc/studio/user-guide/model-registry/what-is-a-model-registry).
+
 ## Installation
 
 GTO requires Python 3. It works on any OS.
 
 ```console
 $ pip install gto
 ```
```

#### encoding

```diff
@@ -1 +1 @@
-us-ascii
+utf-8
```

### Comparing `gto-0.3.3/gto/api.py` & `gto-0.3.4/gto/api.py`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/gto/base.py` & `gto-0.3.4/gto/base.py`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/gto/cli.py` & `gto-0.3.4/gto/cli.py`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/gto/config.py` & `gto-0.3.4/gto/config.py`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/gto/constants.py` & `gto-0.3.4/gto/constants.py`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/gto/exceptions.py` & `gto-0.3.4/gto/exceptions.py`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/gto/ext.py` & `gto-0.3.4/gto/ext.py`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/gto/git_utils.py` & `gto-0.3.4/gto/git_utils.py`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/gto/index.py` & `gto-0.3.4/gto/index.py`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/gto/log.py` & `gto-0.3.4/gto/log.py`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/gto/registry.py` & `gto-0.3.4/gto/registry.py`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/gto/tag.py` & `gto-0.3.4/gto/tag.py`

 * *Files 0% similar despite different names*

```diff
@@ -57,17 +57,17 @@
     stage: Optional[str] = None,
     repo: Optional[git.Repo] = None,
     simple: bool = False,
 ):
     if action not in TagTemplates:
         raise UnknownAction(action=action)
 
-    artifact = name_to_tag(artifact)
-
-    tag = TagTemplates[action].format(artifact=artifact, version=version, stage=stage)
+    tag = TagTemplates[action].format(
+        artifact=name_to_tag(artifact), version=version, stage=stage
+    )
     if simple:
         return tag
     if repo is None:
         raise MissingArg(arg="repo")
     counter = 0
     for t in repo.tags:
         parsed = parse_name(t.name, raise_on_fail=False)  # type: ignore
```

### Comparing `gto-0.3.3/gto/ui.py` & `gto-0.3.4/gto/ui.py`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/gto/utils.py` & `gto-0.3.4/gto/utils.py`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/gto/versions.py` & `gto-0.3.4/gto/versions.py`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/gto.egg-info/PKG-INFO` & `gto-0.3.4/gto.egg-info/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,22 +1,24 @@
 Metadata-Version: 2.1
 Name: gto
-Version: 0.3.3
+Version: 0.3.4
 Summary: Version and deploy your models following GitOps principles
 Download-URL: https://github.com/iterative/gto
 Author: Alexander Guschin
 Author-email: aguschin@iterative.ai
 License: Apache License 2.0
 Keywords: git repo repository artifact registry developer-tools collaboration
 Classifier: Development Status :: 2 - Pre-Alpha
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
+Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
 Requires-Python: >=3.6
 Description-Content-Type: text/markdown
 Provides-Extra: tests
 License-File: LICENSE
 
 # GTO
 
@@ -28,18 +30,20 @@
 
 - Registry: Track new artifacts and their versions for releases and significant
   changes.
 - Lifecycle Management: Create actionable stages for versions marking status of
   artifact or it's readiness to be consumed by a specific environment.
 - GitOps: Signal CI/CD automation or other downstream systems to act upon these
   new versions and lifecycle updates.
-- Enrichments: Annotate and query artifact metadata with additional information.
 
 GTO works by creating annotated Git tags in a standard format.
 
+💡 Together with [DVC](https://dvc.org), GTO serves as a backbone for Git-based
+[Iterative Studio Model Registry](https://dvc.org/doc/studio/user-guide/model-registry/what-is-a-model-registry).
+
 ## Installation
 
 GTO requires Python 3. It works on any OS.
 
 ```console
 $ pip install gto
 ```
```

#### encoding

```diff
@@ -1 +1 @@
-us-ascii
+utf-8
```

### Comparing `gto-0.3.3/gto.egg-info/SOURCES.txt` & `gto-0.3.4/gto.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/setup.cfg` & `gto-0.3.4/setup.cfg`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/setup.py` & `gto-0.3.4/setup.py`

 * *Files 3% similar despite different names*

```diff
@@ -49,14 +49,16 @@
     classifiers=[
         "Development Status :: 2 - Pre-Alpha",
         "Programming Language :: Python :: 3",
         "Programming Language :: Python :: 3.6",
         "Programming Language :: Python :: 3.7",
         "Programming Language :: Python :: 3.8",
         "Programming Language :: Python :: 3.9",
+        "Programming Language :: Python :: 3.10",
+        "Programming Language :: Python :: 3.11",
     ],
     packages=find_packages(exclude=["tests"]),
     include_package_data=True,
     entry_points={
         "console_scripts": ["gto = gto.cli:app"],
         "gto.enrichment": [
             # "mlem = gto.ext_mlem:MlemEnrichment",
```

### Comparing `gto-0.3.3/tests/conftest.py` & `gto-0.3.4/tests/conftest.py`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/tests/resources/__init__.py` & `gto-0.3.4/tests/resources/__init__.py`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/tests/resources/sample_remote_repo_expected_history_churn.json` & `gto-0.3.4/tests/resources/sample_remote_repo_expected_history_churn.json`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/tests/resources/sample_remote_repo_expected_registry.json` & `gto-0.3.4/tests/resources/sample_remote_repo_expected_registry.json`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/tests/skip_presets.py` & `gto-0.3.4/tests/skip_presets.py`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/tests/test_api.py` & `gto-0.3.4/tests/test_api.py`

 * *Files 2% similar despite different names*

```diff
@@ -50,21 +50,21 @@
     repo: git.Repo
     repo, write_file = init_showcase_semver
     with open(
         os.path.join(repo.working_dir, "artifacts.yaml"), "w", encoding="utf8"
     ) as f:
         f.write("rf: \n  type: model\n  path: models/random-forest.pkl\n")
     repo.index.add(["artifacts.yaml"])
-    repo.index.commit("Added index")
+    repo.index.commit("Commit 1")
     with open(
         os.path.join(repo.working_dir, "artifacts.yaml"), "w", encoding="utf8"
     ) as f:
         f.write("rf: \n  type: model\n  path: models/random-forest.pklx\n")
     repo.index.add(["artifacts.yaml"])
-    repo.index.commit("Added index")
+    repo.index.commit("Commit 2")
     return repo, "new-artifact"
 
 
 # def test_api_info_commands_repo_with_artifact(
 #     repo_with_artifact: Tuple[git.Repo, Callable]
 # ):
 #     repo, write_file = repo_with_artifact
@@ -145,16 +145,24 @@
     assert latest.version == vname1
 
     assert len(gto.api.show(repo.working_dir, name, deprecated=False)) == 1
     assert len(gto.api.show(repo.working_dir, name, deprecated=True)) == 2
     assert len(gto.api._show_versions(repo.working_dir, name, ref="HEAD")) == 0
 
 
-def test_assign(repo_with_artifact: Tuple[git.Repo, str]):
-    repo, name = repo_with_artifact
+@pytest.mark.parametrize(
+    "name",
+    (
+        "model",
+        "folder:artifact",
+        "some/folder:some/artifact",
+    ),
+)
+def test_assign(repo_with_artifact: Tuple[git.Repo, str], name):
+    repo, _ = repo_with_artifact
     stage = "staging"
     repo.create_tag("v1.0.0")
     repo.create_tag("wrong-tag-unrelated")
     message = "some msg"
     author = "GTO"
     author_email = "gto@iterative.ai"
     event = gto.api.assign(
@@ -180,14 +188,30 @@
             message=message,
             commit_hexsha=repo.commit().hexsha,
             is_active=True,
             ref=event.ref,
         ),
         {"created_at", "assignments", "unassignments", "tag", "activated_at"},
     )
+    event = gto.api.assign(
+        repo.working_dir,
+        name,
+        stage,
+        ref="HEAD^1",
+        name_version="v0.0.2",
+        message=message,
+        author=author,
+        author_email=author_email,
+    )
+    assignments = gto.api.find_versions_in_stage(repo.working_dir, name, stage)
+    assert len(assignments) == 1
+    assignments = gto.api.find_versions_in_stage(
+        repo.working_dir, name, stage, versions_per_stage=-1
+    )
+    assert len(assignments) == 2
 
 
 def test_assign_skip_registration(repo_with_artifact: Tuple[git.Repo, str]):
     repo, name = repo_with_artifact
     stage = "staging"
     with pytest.raises(WrongArgs):
         gto.api.assign(
```

### Comparing `gto-0.3.3/tests/test_cli.py` & `gto-0.3.4/tests/test_cli.py`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/tests/test_config.py` & `gto-0.3.4/tests/test_config.py`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/tests/test_constants.py` & `gto-0.3.4/tests/test_constants.py`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/tests/test_git_utils.py` & `gto-0.3.4/tests/test_git_utils.py`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/tests/test_index.py` & `gto-0.3.4/tests/test_index.py`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/tests/test_registry.py` & `gto-0.3.4/tests/test_registry.py`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/tests/test_showcase.py` & `gto-0.3.4/tests/test_showcase.py`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/tests/test_tag.py` & `gto-0.3.4/tests/test_tag.py`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/tests/test_versions.py` & `gto-0.3.4/tests/test_versions.py`

 * *Files identical despite different names*

### Comparing `gto-0.3.3/tests/utils.py` & `gto-0.3.4/tests/utils.py`

 * *Files identical despite different names*


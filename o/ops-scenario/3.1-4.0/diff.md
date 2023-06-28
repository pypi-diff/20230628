# Comparing `tmp/ops-scenario-3.1.tar.gz` & `tmp/ops-scenario-4.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ops-scenario-3.1.tar", last modified: Thu Jun  1 08:48:06 2023, max compression
+gzip compressed data, was "ops-scenario-4.0.tar", last modified: Wed Jun 28 13:21:30 2023, max compression
```

## Comparing `ops-scenario-3.1.tar` & `ops-scenario-4.0.tar`

### file list

```diff
@@ -1,69 +1,70 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-01 08:48:06.212750 ops-scenario-3.1/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-01 08:48:06.204750 ops-scenario-3.1/.github/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-01 08:48:06.204750 ops-scenario-3.1/.github/workflows/
--rw-r--r--   0 runner    (1001) docker     (123)     1630 2023-06-01 08:47:52.000000 ops-scenario-3.1/.github/workflows/build_wheels.yaml
--rw-r--r--   0 runner    (1001) docker     (123)      869 2023-06-01 08:47:52.000000 ops-scenario-3.1/.github/workflows/quality_checks.yaml
--rw-r--r--   0 runner    (1001) docker     (123)       98 2023-06-01 08:47:52.000000 ops-scenario-3.1/.gitignore
--rw-r--r--   0 runner    (1001) docker     (123)     2557 2023-06-01 08:47:52.000000 ops-scenario-3.1/.pre-commit-config.yaml
--rw-r--r--   0 runner    (1001) docker     (123)       23 2023-06-01 08:47:52.000000 ops-scenario-3.1/CODEOWNERS
--rw-r--r--   0 runner    (1001) docker     (123)     3364 2023-06-01 08:47:52.000000 ops-scenario-3.1/CONTRIBUTING.md
--rw-r--r--   0 runner    (1001) docker     (123)    11358 2023-06-01 08:47:52.000000 ops-scenario-3.1/LICENSE.txt
--rw-r--r--   0 runner    (1001) docker     (123)    33446 2023-06-01 08:48:06.212750 ops-scenario-3.1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    32637 2023-06-01 08:47:52.000000 ops-scenario-3.1/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-01 08:48:06.208750 ops-scenario-3.1/ops_scenario.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    33446 2023-06-01 08:48:06.000000 ops-scenario-3.1/ops_scenario.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1587 2023-06-01 08:48:06.000000 ops-scenario-3.1/ops_scenario.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-01 08:48:06.000000 ops-scenario-3.1/ops_scenario.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)      108 2023-06-01 08:48:06.000000 ops-scenario-3.1/ops_scenario.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)       34 2023-06-01 08:48:06.000000 ops-scenario-3.1/ops_scenario.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-01 08:48:06.000000 ops-scenario-3.1/ops_scenario.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)     1414 2023-06-01 08:47:52.000000 ops-scenario-3.1/pyproject.toml
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-01 08:48:06.208750 ops-scenario-3.1/resources/
--rw-r--r--   0 runner    (1001) docker     (123)    50386 2023-06-01 08:47:52.000000 ops-scenario-3.1/resources/state-transition-model.png
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-01 08:48:06.208750 ops-scenario-3.1/scenario/
--rw-r--r--   0 runner    (1001) docker     (123)     1023 2023-06-01 08:47:52.000000 ops-scenario-3.1/scenario/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2800 2023-06-01 08:47:52.000000 ops-scenario-3.1/scenario/capture_events.py
--rw-r--r--   0 runner    (1001) docker     (123)    10784 2023-06-01 08:47:52.000000 ops-scenario-3.1/scenario/consistency_checker.py
--rw-r--r--   0 runner    (1001) docker     (123)     4198 2023-06-01 08:47:52.000000 ops-scenario-3.1/scenario/context.py
--rw-r--r--   0 runner    (1001) docker     (123)     1326 2023-06-01 08:47:52.000000 ops-scenario-3.1/scenario/fs_mocks.py
--rw-r--r--   0 runner    (1001) docker     (123)      228 2023-06-01 08:47:52.000000 ops-scenario-3.1/scenario/logger.py
--rw-r--r--   0 runner    (1001) docker     (123)    12662 2023-06-01 08:47:52.000000 ops-scenario-3.1/scenario/mocking.py
--rw-r--r--   0 runner    (1001) docker     (123)     3111 2023-06-01 08:47:52.000000 ops-scenario-3.1/scenario/ops_main_mock.py
--rw-r--r--   0 runner    (1001) docker     (123)      253 2023-06-01 08:47:52.000000 ops-scenario-3.1/scenario/pytest_plugin.py
--rw-r--r--   0 runner    (1001) docker     (123)    17887 2023-06-01 08:47:52.000000 ops-scenario-3.1/scenario/runtime.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-01 08:48:06.208750 ops-scenario-3.1/scenario/scripts/
--rw-r--r--   0 runner    (1001) docker     (123)      506 2023-06-01 08:47:52.000000 ops-scenario-3.1/scenario/scripts/errors.py
--rw-r--r--   0 runner    (1001) docker     (123)      457 2023-06-01 08:47:52.000000 ops-scenario-3.1/scenario/scripts/logger.py
--rw-r--r--   0 runner    (1001) docker     (123)      868 2023-06-01 08:47:52.000000 ops-scenario-3.1/scenario/scripts/main.py
--rw-r--r--   0 runner    (1001) docker     (123)    29890 2023-06-01 08:47:52.000000 ops-scenario-3.1/scenario/scripts/snapshot.py
--rw-r--r--   0 runner    (1001) docker     (123)     7403 2023-06-01 08:47:52.000000 ops-scenario-3.1/scenario/scripts/state_apply.py
--rw-r--r--   0 runner    (1001) docker     (123)      800 2023-06-01 08:47:52.000000 ops-scenario-3.1/scenario/scripts/utils.py
--rw-r--r--   0 runner    (1001) docker     (123)     4252 2023-06-01 08:47:52.000000 ops-scenario-3.1/scenario/sequences.py
--rw-r--r--   0 runner    (1001) docker     (123)    39857 2023-06-01 08:47:52.000000 ops-scenario-3.1/scenario/state.py
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-01 08:48:06.212750 ops-scenario-3.1/setup.cfg
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-01 08:48:06.208750 ops-scenario-3.1/tests/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-01 08:48:06.208750 ops-scenario-3.1/tests/resources/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-01 08:47:52.000000 ops-scenario-3.1/tests/resources/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      326 2023-06-01 08:47:52.000000 ops-scenario-3.1/tests/resources/demo_decorate_class.py
--rw-r--r--   0 runner    (1001) docker     (123)     6141 2023-06-01 08:47:52.000000 ops-scenario-3.1/tests/test_consistency_checker.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-01 08:48:06.212750 ops-scenario-3.1/tests/test_e2e/
--rw-r--r--   0 runner    (1001) docker     (123)     1331 2023-06-01 08:47:52.000000 ops-scenario-3.1/tests/test_e2e/test_builtin_scenes.py
--rw-r--r--   0 runner    (1001) docker     (123)     1492 2023-06-01 08:47:52.000000 ops-scenario-3.1/tests/test_e2e/test_config.py
--rw-r--r--   0 runner    (1001) docker     (123)     2035 2023-06-01 08:47:52.000000 ops-scenario-3.1/tests/test_e2e/test_custom_event_triggers.py
--rw-r--r--   0 runner    (1001) docker     (123)     5081 2023-06-01 08:47:52.000000 ops-scenario-3.1/tests/test_e2e/test_deferred.py
--rw-r--r--   0 runner    (1001) docker     (123)      845 2023-06-01 08:47:52.000000 ops-scenario-3.1/tests/test_e2e/test_juju_log.py
--rw-r--r--   0 runner    (1001) docker     (123)     1490 2023-06-01 08:47:52.000000 ops-scenario-3.1/tests/test_e2e/test_network.py
--rw-r--r--   0 runner    (1001) docker     (123)      943 2023-06-01 08:47:52.000000 ops-scenario-3.1/tests/test_e2e/test_observers.py
--rw-r--r--   0 runner    (1001) docker     (123)     8608 2023-06-01 08:47:52.000000 ops-scenario-3.1/tests/test_e2e/test_pebble.py
--rw-r--r--   0 runner    (1001) docker     (123)     3522 2023-06-01 08:47:52.000000 ops-scenario-3.1/tests/test_e2e/test_play_assertions.py
--rw-r--r--   0 runner    (1001) docker     (123)     7992 2023-06-01 08:47:52.000000 ops-scenario-3.1/tests/test_e2e/test_relations.py
--rw-r--r--   0 runner    (1001) docker     (123)     2629 2023-06-01 08:47:52.000000 ops-scenario-3.1/tests/test_e2e/test_rubbish_events.py
--rw-r--r--   0 runner    (1001) docker     (123)     6706 2023-06-01 08:47:52.000000 ops-scenario-3.1/tests/test_e2e/test_secrets.py
--rw-r--r--   0 runner    (1001) docker     (123)     7230 2023-06-01 08:47:52.000000 ops-scenario-3.1/tests/test_e2e/test_state.py
--rw-r--r--   0 runner    (1001) docker     (123)     2331 2023-06-01 08:47:52.000000 ops-scenario-3.1/tests/test_e2e/test_status.py
--rw-r--r--   0 runner    (1001) docker     (123)     1550 2023-06-01 08:47:52.000000 ops-scenario-3.1/tests/test_e2e/test_stored_state.py
--rw-r--r--   0 runner    (1001) docker     (123)     1690 2023-06-01 08:47:52.000000 ops-scenario-3.1/tests/test_e2e/test_vroot.py
--rw-r--r--   0 runner    (1001) docker     (123)     2623 2023-06-01 08:47:52.000000 ops-scenario-3.1/tests/test_emitted_events_util.py
--rw-r--r--   0 runner    (1001) docker     (123)     1567 2023-06-01 08:47:52.000000 ops-scenario-3.1/tests/test_plugin.py
--rw-r--r--   0 runner    (1001) docker     (123)     2706 2023-06-01 08:47:52.000000 ops-scenario-3.1/tests/test_runtime.py
--rw-r--r--   0 runner    (1001) docker     (123)     1233 2023-06-01 08:47:52.000000 ops-scenario-3.1/tox.ini
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:21:30.004937 ops-scenario-4.0/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:21:29.980936 ops-scenario-4.0/.github/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:21:29.992936 ops-scenario-4.0/.github/workflows/
+-rw-r--r--   0 runner    (1001) docker     (123)     1630 2023-06-28 13:21:17.000000 ops-scenario-4.0/.github/workflows/build_wheels.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)      885 2023-06-28 13:21:17.000000 ops-scenario-4.0/.github/workflows/quality_checks.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)       98 2023-06-28 13:21:17.000000 ops-scenario-4.0/.gitignore
+-rw-r--r--   0 runner    (1001) docker     (123)     2557 2023-06-28 13:21:17.000000 ops-scenario-4.0/.pre-commit-config.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)       23 2023-06-28 13:21:17.000000 ops-scenario-4.0/CODEOWNERS
+-rw-r--r--   0 runner    (1001) docker     (123)     3364 2023-06-28 13:21:17.000000 ops-scenario-4.0/CONTRIBUTING.md
+-rw-r--r--   0 runner    (1001) docker     (123)    11358 2023-06-28 13:21:17.000000 ops-scenario-4.0/LICENSE.txt
+-rw-r--r--   0 runner    (1001) docker     (123)    38100 2023-06-28 13:21:30.004937 ops-scenario-4.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    37291 2023-06-28 13:21:17.000000 ops-scenario-4.0/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:21:29.992936 ops-scenario-4.0/ops_scenario.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    38100 2023-06-28 13:21:29.000000 ops-scenario-4.0/ops_scenario.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1609 2023-06-28 13:21:29.000000 ops-scenario-4.0/ops_scenario.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 13:21:29.000000 ops-scenario-4.0/ops_scenario.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       56 2023-06-28 13:21:29.000000 ops-scenario-4.0/ops_scenario.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       34 2023-06-28 13:21:29.000000 ops-scenario-4.0/ops_scenario.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-28 13:21:29.000000 ops-scenario-4.0/ops_scenario.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     1339 2023-06-28 13:21:17.000000 ops-scenario-4.0/pyproject.toml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:21:29.992936 ops-scenario-4.0/resources/
+-rw-r--r--   0 runner    (1001) docker     (123)    50386 2023-06-28 13:21:17.000000 ops-scenario-4.0/resources/state-transition-model.png
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:21:29.996936 ops-scenario-4.0/scenario/
+-rw-r--r--   0 runner    (1001) docker     (123)      943 2023-06-28 13:21:17.000000 ops-scenario-4.0/scenario/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2933 2023-06-28 13:21:17.000000 ops-scenario-4.0/scenario/capture_events.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13853 2023-06-28 13:21:17.000000 ops-scenario-4.0/scenario/consistency_checker.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8354 2023-06-28 13:21:17.000000 ops-scenario-4.0/scenario/context.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1423 2023-06-28 13:21:17.000000 ops-scenario-4.0/scenario/fs_mocks.py
+-rw-r--r--   0 runner    (1001) docker     (123)      228 2023-06-28 13:21:17.000000 ops-scenario-4.0/scenario/logger.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13868 2023-06-28 13:21:17.000000 ops-scenario-4.0/scenario/mocking.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4624 2023-06-28 13:21:17.000000 ops-scenario-4.0/scenario/ops_main_mock.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18285 2023-06-28 13:21:17.000000 ops-scenario-4.0/scenario/runtime.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:21:30.000937 ops-scenario-4.0/scenario/scripts/
+-rw-r--r--   0 runner    (1001) docker     (123)      506 2023-06-28 13:21:17.000000 ops-scenario-4.0/scenario/scripts/errors.py
+-rw-r--r--   0 runner    (1001) docker     (123)      457 2023-06-28 13:21:17.000000 ops-scenario-4.0/scenario/scripts/logger.py
+-rw-r--r--   0 runner    (1001) docker     (123)      868 2023-06-28 13:21:17.000000 ops-scenario-4.0/scenario/scripts/main.py
+-rw-r--r--   0 runner    (1001) docker     (123)    30113 2023-06-28 13:21:17.000000 ops-scenario-4.0/scenario/scripts/snapshot.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7403 2023-06-28 13:21:17.000000 ops-scenario-4.0/scenario/scripts/state_apply.py
+-rw-r--r--   0 runner    (1001) docker     (123)      800 2023-06-28 13:21:17.000000 ops-scenario-4.0/scenario/scripts/utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4309 2023-06-28 13:21:17.000000 ops-scenario-4.0/scenario/sequences.py
+-rw-r--r--   0 runner    (1001) docker     (123)    39630 2023-06-28 13:21:17.000000 ops-scenario-4.0/scenario/state.py
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 13:21:30.004937 ops-scenario-4.0/setup.cfg
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:21:30.000937 ops-scenario-4.0/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)     1211 2023-06-28 13:21:17.000000 ops-scenario-4.0/tests/helpers.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:21:30.000937 ops-scenario-4.0/tests/resources/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 13:21:17.000000 ops-scenario-4.0/tests/resources/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      326 2023-06-28 13:21:17.000000 ops-scenario-4.0/tests/resources/demo_decorate_class.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7025 2023-06-28 13:21:17.000000 ops-scenario-4.0/tests/test_consistency_checker.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:21:30.004937 ops-scenario-4.0/tests/test_e2e/
+-rw-r--r--   0 runner    (1001) docker     (123)     3401 2023-06-28 13:21:17.000000 ops-scenario-4.0/tests/test_e2e/test_actions.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1331 2023-06-28 13:21:17.000000 ops-scenario-4.0/tests/test_e2e/test_builtin_scenes.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1497 2023-06-28 13:21:17.000000 ops-scenario-4.0/tests/test_e2e/test_config.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4418 2023-06-28 13:21:17.000000 ops-scenario-4.0/tests/test_e2e/test_custom_event_triggers.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5090 2023-06-28 13:21:17.000000 ops-scenario-4.0/tests/test_e2e/test_deferred.py
+-rw-r--r--   0 runner    (1001) docker     (123)      968 2023-06-28 13:21:17.000000 ops-scenario-4.0/tests/test_e2e/test_juju_log.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1495 2023-06-28 13:21:17.000000 ops-scenario-4.0/tests/test_e2e/test_network.py
+-rw-r--r--   0 runner    (1001) docker     (123)      948 2023-06-28 13:21:17.000000 ops-scenario-4.0/tests/test_e2e/test_observers.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8588 2023-06-28 13:21:17.000000 ops-scenario-4.0/tests/test_e2e/test_pebble.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3327 2023-06-28 13:21:17.000000 ops-scenario-4.0/tests/test_e2e/test_play_assertions.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7997 2023-06-28 13:21:17.000000 ops-scenario-4.0/tests/test_e2e/test_relations.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2634 2023-06-28 13:21:17.000000 ops-scenario-4.0/tests/test_e2e/test_rubbish_events.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6711 2023-06-28 13:21:17.000000 ops-scenario-4.0/tests/test_e2e/test_secrets.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6846 2023-06-28 13:21:17.000000 ops-scenario-4.0/tests/test_e2e/test_state.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2941 2023-06-28 13:21:17.000000 ops-scenario-4.0/tests/test_e2e/test_status.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1555 2023-06-28 13:21:17.000000 ops-scenario-4.0/tests/test_e2e/test_stored_state.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1715 2023-06-28 13:21:17.000000 ops-scenario-4.0/tests/test_e2e/test_vroot.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2683 2023-06-28 13:21:17.000000 ops-scenario-4.0/tests/test_emitted_events_util.py
+-rw-r--r--   0 runner    (1001) docker     (123)      888 2023-06-28 13:21:17.000000 ops-scenario-4.0/tests/test_plugin.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2961 2023-06-28 13:21:17.000000 ops-scenario-4.0/tests/test_runtime.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1358 2023-06-28 13:21:17.000000 ops-scenario-4.0/tox.ini
```

### Comparing `ops-scenario-3.1/.github/workflows/build_wheels.yaml` & `ops-scenario-4.0/.github/workflows/build_wheels.yaml`

 * *Files identical despite different names*

### Comparing `ops-scenario-3.1/.github/workflows/quality_checks.yaml` & `ops-scenario-4.0/.github/workflows/quality_checks.yaml`

 * *Files 11% similar despite different names*

```diff
@@ -13,29 +13,29 @@
       - name: Checkout
         uses: actions/checkout@v3
         with:
           fetch-depth: 1
       - name: Set up python
         uses: actions/setup-python@v4
         with:
-          python-version: 3.8
+          python-version: "3.10"
       - name: Install dependencies
         run: python -m pip install tox
-      - name: Run tests
+      - name: Run lint tests
         run: tox -vve lint
 
   unit-test:
     name: Unit Tests
     runs-on: ubuntu-latest
     steps:
       - name: Checkout
         uses: actions/checkout@v3
         with:
           fetch-depth: 1
       - name: Set up python
         uses: actions/setup-python@v4
         with:
-          python-version: 3.8
+          python-version: "3.10"
       - name: Install dependencies
         run: python -m pip install tox
-      - name: Run tests
+      - name: Run unit tests
         run: tox -vve unit
```

### Comparing `ops-scenario-3.1/.pre-commit-config.yaml` & `ops-scenario-4.0/.pre-commit-config.yaml`

 * *Files identical despite different names*

### Comparing `ops-scenario-3.1/CONTRIBUTING.md` & `ops-scenario-4.0/CONTRIBUTING.md`

 * *Files identical despite different names*

### Comparing `ops-scenario-3.1/LICENSE.txt` & `ops-scenario-4.0/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `ops-scenario-3.1/PKG-INFO` & `ops-scenario-4.0/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -1,34 +1,15 @@
-Metadata-Version: 2.1
-Name: ops-scenario
-Version: 3.1
-Summary: Python library providing a Scenario-based testing API for Operator Framework charms.
-Author-email: Pietro Pasotti <pietro.pasotti@canonical.com>
-License: Apache-2.0
-Project-URL: Homepage, https://github.com/canonical/ops-scenario
-Project-URL: Bug Tracker, https://github.com/canonical/ops-scenario/issues
-Keywords: juju,test
-Classifier: Development Status :: 3 - Alpha
-Classifier: License :: OSI Approved :: Apache Software License
-Classifier: Framework :: Pytest
-Classifier: Intended Audience :: Developers
-Classifier: Topic :: Software Development :: Quality Assurance
-Classifier: Topic :: Software Development :: Testing
-Classifier: Topic :: Utilities
-Requires-Python: >=3.8
-Description-Content-Type: text/markdown
-License-File: LICENSE.txt
-
 # Scenario
 
 [![Build](https://github.com/canonical/ops-scenario/actions/workflows/build_wheels.yaml/badge.svg)](https://github.com/canonical/ops-scenario/actions/workflows/build_wheels.yaml)
 [![QC](https://github.com/canonical/ops-scenario/actions/workflows/quality_checks.yaml/badge.svg?event=pull_request)](https://github.com/canonical/ops-scenario/actions/workflows/quality_checks.yaml?event=pull_request)
 [![Discourse Status](https://img.shields.io/discourse/status?server=https%3A%2F%2Fdiscourse.charmhub.io&style=flat&label=CharmHub%20Discourse)](https://discourse.charmhub.io)
 [![foo](https://img.shields.io/badge/everything-charming-blueviolet)](https://github.com/PietroPasotti/jhack)
 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://discourse.charmhub.io/t/rethinking-charm-testing-with-ops-scenario/8649)
+[![Python >= 3.8](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/)
 
 Scenario is a state-transition, functional testing framework for Operator Framework charms.
 
 Where the Harness enables you to procedurally mock pieces of the state the charm needs to function, Scenario tests allow
 you to declaratively define the state all at once, and use it as a sort of context against which you can fire a single
 event on the charm and execute its logic.
 
@@ -88,16 +69,16 @@
     - declare the input state
     - select an event to fire
 - **Act**:
     - run the state (i.e. obtain the output state)
     - optionally, use pre-event and post-event hooks to get a hold of the charm instance and run assertions on internal
       APIs
 - **Assert**:
-    - verify that the output state is how you expect it to be
-    - optionally, verify that the delta with the input state is what you expect it to be
+    - verify that the output state (or the delta with the input state) is how you expect it to be
+    - verify that the charm has seen a certain sequence of statuses, events, and `juju-log` calls
 
 The most basic scenario is the so-called `null scenario`: one in which all is defaulted and barely any data is
 available. The charm has no config, no relations, no networks, and no leadership.
 
 With that, we can write the simplest possible scenario test:
 
 ```python
@@ -110,15 +91,15 @@
     pass
 
 
 def test_scenario_base():
     ctx = Context(MyCharm,
                   meta={"name": "foo"})
     out = ctx.run('start', State())
-    assert out.status.unit == UnknownStatus()
+    assert out.unit_status == UnknownStatus()
 ```
 
 Now let's start making it more complicated. Our charm sets a special state if it has leadership on 'start':
 
 ```python
 import pytest
 from scenario import State, Context
@@ -137,17 +118,16 @@
             self.unit.status = ActiveStatus('I am ruled')
 
 
 @pytest.mark.parametrize('leader', (True, False))
 def test_status_leader(leader):
     ctx = Context(MyCharm,
                   meta={"name": "foo"})
-    out = ctx.run('start',
-                  State(leader=leader)
-    assert out.status.unit == ActiveStatus('I rule' if leader else 'I am ruled')
+    out = ctx.run('start', State(leader=leader))
+    assert out.unit_status == ActiveStatus('I rule' if leader else 'I am ruled')
 ```
 
 By defining the right state we can programmatically define what answers will the charm get to all the questions it can
 ask the juju model: am I leader? What are my relations? What is the remote unit I'm talking to? etc...
 
 ## Statuses
 
@@ -169,33 +149,56 @@
             self.unit.status = WaitingStatus('checking this is right...')
             self._check_that_takes_some_more_time()
             self.unit.status = ActiveStatus('I am ruled')
     except:
         self.unit.status = BlockedStatus('something went wrong')
 ```
 
-You can verify that the charm has followed the expected path by checking the **unit status history** like so:
+More broadly, often we want to test 'side effects' of executing a charm, such as what events have been emitted, what statuses it went through, etc... Before we get there, we have to explain what the `Context` represents, and its relationship with the `State`.
+
+# Context and State
+
+Consider the following tests. Suppose we want to verify that while handling a given toplevel juju event:
+
+- a specific chain of (custom) events was emitted on the charm
+- the charm `juju-log`ged these specific strings
+- the charm went through this sequence of app/unit statuses (e.g. `maintenance`, then `waiting`, then `active`)
+
+These types of test have a place in Scenario, but that is not State: the contents of the juju log or the status history
+are side effects of executing a charm, but are not persisted in a charm-accessible "state" in any meaningful way.
+In other words: those data streams are, from the charm's perspective, write-only.
+
+As such, they do not belong in `scenario.State` but in `scenario.Context`: the object representing the charm's execution
+context.
+
+## Status history
+
+You can verify that the charm has followed the expected path by checking the unit/app status history like so:
 
 ```python
 from charm import MyCharm
 from ops.model import MaintenanceStatus, ActiveStatus, WaitingStatus, UnknownStatus
 from scenario import State, Context
 
 
 def test_statuses():
     ctx = Context(MyCharm,
                   meta={"name": "foo"})
-    out = ctx.run('start',
-                  State(leader=False))
-    assert out.status.unit_history == [
+    ctx.run('start', State(leader=False))
+    assert ctx.unit_status_history == [
         UnknownStatus(),
         MaintenanceStatus('determining who the ruler is...'),
         WaitingStatus('checking this is right...'),
         ActiveStatus("I am ruled"),
     ]
+
+    assert ctx.app_status_history == [
+        UnknownStatus(),
+        ActiveStatus(""),
+    ]
 ```
 
 Note that the current status is not in the **unit status history**.
 
 Also note that, unless you initialize the State with a preexisting status, the first status in the history will always
 be `unknown`. That is because, so far as scenario is concerned, each event is "the first event this charm has ever
 seen".
@@ -203,17 +206,104 @@
 If you want to simulate a situation in which the charm already has seen some event, and is in a status other than
 Unknown (the default status every charm is born with), you will have to pass the 'initial status' to State.
 
 ```python
 from ops.model import ActiveStatus
 from scenario import State, Status
 
-State(leader=False, status=Status(unit=ActiveStatus('foo')))
+# ...
+ctx.run('start', State(unit_status=ActiveStatus('foo')))
+assert ctx.unit_status_history == [
+    ActiveStatus('foo'),  # now the first status is active: 'foo'!
+    # ...
+]
+
 ```
 
+## Workload version history
+
+Using a similar api to `*_status_history`, you can assert that the charm has set one or more workload versions during a
+hook execution:
+
+```python
+from scenario import Context
+
+# ...
+ctx: Context
+assert ctx.workload_version_history == ['1', '1.2', '1.5']
+# ...
+```
+
+## Emitted events
+
+If your charm deals with deferred events, custom events, and charm libs that in turn emit their own custom events, it
+can be hard to examine the resulting control flow. In these situations it can be useful to verify that, as a result of a
+given juju event triggering (say, 'start'), a specific chain of deferred and custom events is emitted on the charm. The
+resulting state, black-box as it is, gives little insight into how exactly it was obtained.
+
+```python
+from scenario import Context
+from ops.charm import StartEvent
+
+
+def test_foo():
+    ctx = Context(...)
+    ctx.run('start', ...)
+
+    assert len(ctx.emitted_events) == 1
+    assert isinstance(ctx.emitted_events[0], StartEvent)
+```
+
+### Low-level access: using directly `capture_events`
+
+If you need more control over what events are captured (or you're not into pytest), you can use directly the context
+manager that powers the `emitted_events` fixture: `scenario.capture_events`.
+This context manager allows you to intercept any events emitted by the framework.
+
+Usage:
+
+```python
+from ops.charm import StartEvent, UpdateStatusEvent
+from scenario import State, Context, DeferredEvent, capture_events
+
+with capture_events() as emitted:
+    ctx = Context(...)
+    state_out = ctx.run(
+        "update-status",
+        State(deferred=[DeferredEvent("start", ...)])
+    )
+
+# deferred events get reemitted first
+assert isinstance(emitted[0], StartEvent)
+# the main juju event gets emitted next
+assert isinstance(emitted[1], UpdateStatusEvent)
+# possibly followed by a tail of all custom events that the main juju event triggered in turn
+# assert isinstance(emitted[2], MyFooEvent)
+# ...
+```
+
+You can filter events by type like so:
+
+```python
+from ops.charm import StartEvent, RelationEvent
+from scenario import capture_events
+
+with capture_events(StartEvent, RelationEvent) as emitted:
+    # capture all `start` and `*-relation-*` events.
+    pass
+```
+
+Configuration:
+
+- Passing no event types, like: `capture_events()`, is equivalent to `capture_events(EventBase)`.
+- By default, **framework events** (`PreCommit`, `Commit`) are not considered for inclusion in the output list even if
+  they match the instance check. You can toggle that by passing: `capture_events(include_framework=True)`.
+- By default, **deferred events** are included in the listing if they match the instance check. You can toggle that by
+  passing: `capture_events(include_deferred=True)`.
+
 ## Relations
 
 You can write scenario tests to verify the shape of relation data:
 
 ```python
 from ops.charm import CharmBase
 
@@ -322,18 +412,18 @@
   from unit IDs to databags)
 - `Relation.remote_app_name` maps to `SubordinateRelation.primary_app_name`
 
 ```python
 from scenario.state import SubordinateRelation
 
 relation = SubordinateRelation(
-  endpoint="peers",
-  remote_unit_data={"foo": "bar"},
-  remote_app_name="zookeeper",
-  remote_unit_id=42
+    endpoint="peers",
+    remote_unit_data={"foo": "bar"},
+    remote_app_name="zookeeper",
+    remote_unit_id=42
 )
 relation.remote_unit_name  # "zookeeper/42"
 ```
 
 ## Triggering Relation Events
 
 If you want to trigger relation events, the easiest way to do so is get a hold of the Relation instance and grab the
@@ -532,36 +622,41 @@
             id='foo',
             contents={0: {'key': 'public'}}
         )
     ]
 )
 ```
 
-The only mandatory arguments to Secret are its secret ID (which should be unique) and its 'contents': that is, a mapping from revision numbers (integers) to a str:str dict representing the payload of the revision. 
+The only mandatory arguments to Secret are its secret ID (which should be unique) and its 'contents': that is, a mapping
+from revision numbers (integers) to a str:str dict representing the payload of the revision.
 
-By default, the secret is not owned by **this charm** nor is it granted to it. 
-Therefore, if charm code attempted to get that secret revision, it would get a permission error: we didn't grant it to this charm, nor we specified that the secret is owned by it.
+By default, the secret is not owned by **this charm** nor is it granted to it.
+Therefore, if charm code attempted to get that secret revision, it would get a permission error: we didn't grant it to
+this charm, nor we specified that the secret is owned by it.
 
 To specify a secret owned by this unit (or app):
+
 ```python
 from scenario import State, Secret
 
 state = State(
     secrets=[
         Secret(
             id='foo',
             contents={0: {'key': 'public'}},
             owner='unit',  # or 'app'
-            remote_grants = {0: {"remote"}}  # the secret owner has granted access to the "remote" app over some relation with ID 0
+            remote_grants={0: {"remote"}}
+            # the secret owner has granted access to the "remote" app over some relation with ID 0
         )
     ]
 )
 ```
 
 To specify a secret owned by some other application and give this unit (or app) access to it:
+
 ```python
 from scenario import State, Secret
 
 state = State(
     secrets=[
         Secret(
             id='foo',
@@ -570,14 +665,64 @@
             granted="unit",  # or "app",
             revision=0,  # the revision that this unit (or app) is currently tracking
         )
     ]
 )
 ```
 
+# Actions
+
+An action is a special sort of event, even though `ops` handles them almost identically.
+In most cases, you'll want to inspect the 'results' of an action, or whether it has failed or
+logged something while executing. Many actions don't have a direct effect on the output state.
+For this reason, the output state is less prominent in the return type of `Context.run_action`.
+
+How to test actions with scenario:
+
+## Actions without parameters
+
+```python
+from scenario import Context, State, ActionOutput
+from charm import MyCharm
+
+
+def test_backup_action():
+    ctx = Context(MyCharm)
+
+    # If you didn't declare do_backup in the charm's `actions.yaml`, 
+    # the `ConsistencyChecker` will slap you on the wrist and refuse to proceed.
+    out: ActionOutput = ctx.run_action("do_backup_action", State())
+
+    # you can assert action results, logs, failure using the ActionOutput interface
+    assert out.results == {'foo': 'bar'}
+    assert out.logs == ['baz', 'qux']
+    assert out.failure == 'boo-hoo'
+```
+
+## Parametrized Actions
+
+If the action takes parameters, you'll need to instantiate an `Action`.
+
+```python
+from scenario import Action, Context, State, ActionOutput
+from charm import MyCharm
+
+
+def test_backup_action():
+    # define an action
+    action = Action('do_backup', params={'a': 'b'})
+    ctx = Context(MyCharm)
+
+    # if the parameters (or their type) don't match what declared in actions.yaml, 
+    # the `ConsistencyChecker` will slap you on the other wrist. 
+    out: ActionOutput = ctx.run_action(action, State())
+
+    # ...
+```
+
 # Deferred events
 
 Scenario allows you to accurately simulate the Operator Framework's event queue. The event queue is responsible for
 keeping track of the deferred events. On the input side, you can verify that if the charm triggers with this and that
 event in its queue (they would be there because they had been deferred in the previous run), then the output state is
 valid.
 
@@ -739,82 +884,40 @@
         })
 ])
 ```
 
 And the charm's runtime will see `self.stored_State.foo` and `.baz` as expected. Also, you can run assertions on it on
 the output side the same as any other bit of state.
 
-# Emitted events
-
-If your charm deals with deferred events, custom events, and charm libs that in turn emit their own custom events, it
-can be hard to examine the resulting control flow. In these situations it can be useful to verify that, as a result of a
-given juju event triggering (say, 'start'), a specific chain of deferred and custom events is emitted on the charm. The
-resulting state, black-box as it is, gives little insight into how exactly it was obtained.
-
-`scenario`, among many other great things, is also a pytest plugin. It exposes a fixture called `emitted_events` that
-you can use like so:
-
-```python
-from scenario import Context
-from ops.charm import StartEvent
+# Emitting custom events
 
+While the main use case of Scenario is to emit juju events, i.e. the built-in `start`, `install`, `*-relation-changed`, etc..., it can be sometimes handy to directly trigger custom events defined on arbitrary Objects in your hierarchy.
 
-def test_foo(emitted_events):
-    Context(...).run('start', ...)
-
-    assert len(emitted_events) == 1
-    assert isinstance(emitted_events[0], StartEvent)
-```
-
-## Customizing: capture_events
-
-If you need more control over what events are captured (or you're not into pytest), you can use directly the context
-manager that powers the `emitted_events` fixture: `scenario.capture_events`.
-This context manager allows you to intercept any events emitted by the framework.
+Suppose your charm uses a charm library providing an `ingress_provided` event.
+The 'proper' way to emit it is to run the event that causes that custom event to be emitted by the library, whatever that may be, for example a `foo-relation-changed`.
 
-Usage:
+However, that may mean that you have to set up all sorts of State and mocks so that the right preconditions are met and the event is emitted at all.
 
+However if you attempt to run that event directly you will get an error:
 ```python
-from ops.charm import StartEvent, UpdateStatusEvent
-from scenario import State, Context, DeferredEvent, capture_events
-
-with capture_events() as emitted:
-    ctx = Context(...)
-    state_out = ctx.run(
-        "update-status",
-        State(deferred=[DeferredEvent("start", ...)])
-    )
-
-# deferred events get reemitted first
-assert isinstance(emitted[0], StartEvent)
-# the main juju event gets emitted next
-assert isinstance(emitted[1], UpdateStatusEvent)
-# possibly followed by a tail of all custom events that the main juju event triggered in turn
-# assert isinstance(emitted[2], MyFooEvent)
-# ...
+from scenario import Context, State
+Context(...).run("ingress_provided", State())  # raises scenario.ops_main_mock.NoObserverError
 ```
+This happens because the framework, by default, searches for an event source named `ingress_provided` in `charm.on`, but since the event is defined on another Object, it will fail to find it.
 
-You can filter events by type like so:
+You can prefix the event name with the path leading to its owner to tell Scenario where to find the event source:
 
 ```python
-from ops.charm import StartEvent, RelationEvent
-from scenario import capture_events
-
-with capture_events(StartEvent, RelationEvent) as emitted:
-    # capture all `start` and `*-relation-*` events.
-    pass
+from scenario import Context, State
+Context(...).run("my_charm_lib.on.ingress_provided", State())
 ```
 
-Passing no event types, like: `capture_events()`, is equivalent to `capture_events(EventBase)`.
-
-By default, **framework events** (`PreCommit`, `Commit`) are not considered for inclusion in the output list even if
-they match the instance check. You can toggle that by passing: `capture_events(include_framework=True)`.
+This will instruct Scenario to emit `my_charm.my_charm_lib.on.foo`.
 
-By default, **deferred events** are included in the listing if they match the instance check. You can toggle that by
-passing: `capture_events(include_deferred=True)`.
+(always omit the 'root', i.e. the charm framework key, from the path)
 
 # The virtual charm root
 
 Before executing the charm, Scenario writes the metadata, config, and actions `yaml`s to a temporary directory. The
 charm will see that tempdir as its 'root'. This allows us to keep things simple when dealing with metadata that can be
 either inferred from the charm type being passed to `Context` or be passed to it as an argument, thereby overriding
 the inferred one. This also allows you to test with charms defined on the fly, as in:
@@ -902,8 +1005,8 @@
 `scenario snapshot prometheus-k8s/0`, you will get a printout of the State object. Pipe that out into some file, import
 all you need from `scenario`, and you have a working `State` that you can `Context.run` events with.
 
 You can also pass a `--format` flag to obtain instead:
 
 - a jsonified `State` data structure, for portability
 - a full-fledged pytest test case (with imports and all), where you only have to fill in the charm type and the event
-  that you wish to trigger.
+  that you wish to trigger.
```

### Comparing `ops-scenario-3.1/README.md` & `ops-scenario-4.0/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,14 +1,35 @@
+Metadata-Version: 2.1
+Name: ops-scenario
+Version: 4.0
+Summary: Python library providing a Scenario-based testing API for Operator Framework charms.
+Author-email: Pietro Pasotti <pietro.pasotti@canonical.com>
+License: Apache-2.0
+Project-URL: Homepage, https://github.com/canonical/ops-scenario
+Project-URL: Bug Tracker, https://github.com/canonical/ops-scenario/issues
+Keywords: juju,test
+Classifier: Development Status :: 3 - Alpha
+Classifier: License :: OSI Approved :: Apache Software License
+Classifier: Framework :: Pytest
+Classifier: Intended Audience :: Developers
+Classifier: Topic :: Software Development :: Quality Assurance
+Classifier: Topic :: Software Development :: Testing
+Classifier: Topic :: Utilities
+Requires-Python: >=3.8
+Description-Content-Type: text/markdown
+License-File: LICENSE.txt
+
 # Scenario
 
 [![Build](https://github.com/canonical/ops-scenario/actions/workflows/build_wheels.yaml/badge.svg)](https://github.com/canonical/ops-scenario/actions/workflows/build_wheels.yaml)
 [![QC](https://github.com/canonical/ops-scenario/actions/workflows/quality_checks.yaml/badge.svg?event=pull_request)](https://github.com/canonical/ops-scenario/actions/workflows/quality_checks.yaml?event=pull_request)
 [![Discourse Status](https://img.shields.io/discourse/status?server=https%3A%2F%2Fdiscourse.charmhub.io&style=flat&label=CharmHub%20Discourse)](https://discourse.charmhub.io)
 [![foo](https://img.shields.io/badge/everything-charming-blueviolet)](https://github.com/PietroPasotti/jhack)
 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://discourse.charmhub.io/t/rethinking-charm-testing-with-ops-scenario/8649)
+[![Python >= 3.8](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/)
 
 Scenario is a state-transition, functional testing framework for Operator Framework charms.
 
 Where the Harness enables you to procedurally mock pieces of the state the charm needs to function, Scenario tests allow
 you to declaratively define the state all at once, and use it as a sort of context against which you can fire a single
 event on the charm and execute its logic.
 
@@ -68,16 +89,16 @@
     - declare the input state
     - select an event to fire
 - **Act**:
     - run the state (i.e. obtain the output state)
     - optionally, use pre-event and post-event hooks to get a hold of the charm instance and run assertions on internal
       APIs
 - **Assert**:
-    - verify that the output state is how you expect it to be
-    - optionally, verify that the delta with the input state is what you expect it to be
+    - verify that the output state (or the delta with the input state) is how you expect it to be
+    - verify that the charm has seen a certain sequence of statuses, events, and `juju-log` calls
 
 The most basic scenario is the so-called `null scenario`: one in which all is defaulted and barely any data is
 available. The charm has no config, no relations, no networks, and no leadership.
 
 With that, we can write the simplest possible scenario test:
 
 ```python
@@ -90,15 +111,15 @@
     pass
 
 
 def test_scenario_base():
     ctx = Context(MyCharm,
                   meta={"name": "foo"})
     out = ctx.run('start', State())
-    assert out.status.unit == UnknownStatus()
+    assert out.unit_status == UnknownStatus()
 ```
 
 Now let's start making it more complicated. Our charm sets a special state if it has leadership on 'start':
 
 ```python
 import pytest
 from scenario import State, Context
@@ -117,17 +138,16 @@
             self.unit.status = ActiveStatus('I am ruled')
 
 
 @pytest.mark.parametrize('leader', (True, False))
 def test_status_leader(leader):
     ctx = Context(MyCharm,
                   meta={"name": "foo"})
-    out = ctx.run('start',
-                  State(leader=leader)
-    assert out.status.unit == ActiveStatus('I rule' if leader else 'I am ruled')
+    out = ctx.run('start', State(leader=leader))
+    assert out.unit_status == ActiveStatus('I rule' if leader else 'I am ruled')
 ```
 
 By defining the right state we can programmatically define what answers will the charm get to all the questions it can
 ask the juju model: am I leader? What are my relations? What is the remote unit I'm talking to? etc...
 
 ## Statuses
 
@@ -149,33 +169,56 @@
             self.unit.status = WaitingStatus('checking this is right...')
             self._check_that_takes_some_more_time()
             self.unit.status = ActiveStatus('I am ruled')
     except:
         self.unit.status = BlockedStatus('something went wrong')
 ```
 
-You can verify that the charm has followed the expected path by checking the **unit status history** like so:
+More broadly, often we want to test 'side effects' of executing a charm, such as what events have been emitted, what statuses it went through, etc... Before we get there, we have to explain what the `Context` represents, and its relationship with the `State`.
+
+# Context and State
+
+Consider the following tests. Suppose we want to verify that while handling a given toplevel juju event:
+
+- a specific chain of (custom) events was emitted on the charm
+- the charm `juju-log`ged these specific strings
+- the charm went through this sequence of app/unit statuses (e.g. `maintenance`, then `waiting`, then `active`)
+
+These types of test have a place in Scenario, but that is not State: the contents of the juju log or the status history
+are side effects of executing a charm, but are not persisted in a charm-accessible "state" in any meaningful way.
+In other words: those data streams are, from the charm's perspective, write-only.
+
+As such, they do not belong in `scenario.State` but in `scenario.Context`: the object representing the charm's execution
+context.
+
+## Status history
+
+You can verify that the charm has followed the expected path by checking the unit/app status history like so:
 
 ```python
 from charm import MyCharm
 from ops.model import MaintenanceStatus, ActiveStatus, WaitingStatus, UnknownStatus
 from scenario import State, Context
 
 
 def test_statuses():
     ctx = Context(MyCharm,
                   meta={"name": "foo"})
-    out = ctx.run('start',
-                  State(leader=False))
-    assert out.status.unit_history == [
+    ctx.run('start', State(leader=False))
+    assert ctx.unit_status_history == [
         UnknownStatus(),
         MaintenanceStatus('determining who the ruler is...'),
         WaitingStatus('checking this is right...'),
         ActiveStatus("I am ruled"),
     ]
+
+    assert ctx.app_status_history == [
+        UnknownStatus(),
+        ActiveStatus(""),
+    ]
 ```
 
 Note that the current status is not in the **unit status history**.
 
 Also note that, unless you initialize the State with a preexisting status, the first status in the history will always
 be `unknown`. That is because, so far as scenario is concerned, each event is "the first event this charm has ever
 seen".
@@ -183,17 +226,104 @@
 If you want to simulate a situation in which the charm already has seen some event, and is in a status other than
 Unknown (the default status every charm is born with), you will have to pass the 'initial status' to State.
 
 ```python
 from ops.model import ActiveStatus
 from scenario import State, Status
 
-State(leader=False, status=Status(unit=ActiveStatus('foo')))
+# ...
+ctx.run('start', State(unit_status=ActiveStatus('foo')))
+assert ctx.unit_status_history == [
+    ActiveStatus('foo'),  # now the first status is active: 'foo'!
+    # ...
+]
+
 ```
 
+## Workload version history
+
+Using a similar api to `*_status_history`, you can assert that the charm has set one or more workload versions during a
+hook execution:
+
+```python
+from scenario import Context
+
+# ...
+ctx: Context
+assert ctx.workload_version_history == ['1', '1.2', '1.5']
+# ...
+```
+
+## Emitted events
+
+If your charm deals with deferred events, custom events, and charm libs that in turn emit their own custom events, it
+can be hard to examine the resulting control flow. In these situations it can be useful to verify that, as a result of a
+given juju event triggering (say, 'start'), a specific chain of deferred and custom events is emitted on the charm. The
+resulting state, black-box as it is, gives little insight into how exactly it was obtained.
+
+```python
+from scenario import Context
+from ops.charm import StartEvent
+
+
+def test_foo():
+    ctx = Context(...)
+    ctx.run('start', ...)
+
+    assert len(ctx.emitted_events) == 1
+    assert isinstance(ctx.emitted_events[0], StartEvent)
+```
+
+### Low-level access: using directly `capture_events`
+
+If you need more control over what events are captured (or you're not into pytest), you can use directly the context
+manager that powers the `emitted_events` fixture: `scenario.capture_events`.
+This context manager allows you to intercept any events emitted by the framework.
+
+Usage:
+
+```python
+from ops.charm import StartEvent, UpdateStatusEvent
+from scenario import State, Context, DeferredEvent, capture_events
+
+with capture_events() as emitted:
+    ctx = Context(...)
+    state_out = ctx.run(
+        "update-status",
+        State(deferred=[DeferredEvent("start", ...)])
+    )
+
+# deferred events get reemitted first
+assert isinstance(emitted[0], StartEvent)
+# the main juju event gets emitted next
+assert isinstance(emitted[1], UpdateStatusEvent)
+# possibly followed by a tail of all custom events that the main juju event triggered in turn
+# assert isinstance(emitted[2], MyFooEvent)
+# ...
+```
+
+You can filter events by type like so:
+
+```python
+from ops.charm import StartEvent, RelationEvent
+from scenario import capture_events
+
+with capture_events(StartEvent, RelationEvent) as emitted:
+    # capture all `start` and `*-relation-*` events.
+    pass
+```
+
+Configuration:
+
+- Passing no event types, like: `capture_events()`, is equivalent to `capture_events(EventBase)`.
+- By default, **framework events** (`PreCommit`, `Commit`) are not considered for inclusion in the output list even if
+  they match the instance check. You can toggle that by passing: `capture_events(include_framework=True)`.
+- By default, **deferred events** are included in the listing if they match the instance check. You can toggle that by
+  passing: `capture_events(include_deferred=True)`.
+
 ## Relations
 
 You can write scenario tests to verify the shape of relation data:
 
 ```python
 from ops.charm import CharmBase
 
@@ -302,18 +432,18 @@
   from unit IDs to databags)
 - `Relation.remote_app_name` maps to `SubordinateRelation.primary_app_name`
 
 ```python
 from scenario.state import SubordinateRelation
 
 relation = SubordinateRelation(
-  endpoint="peers",
-  remote_unit_data={"foo": "bar"},
-  remote_app_name="zookeeper",
-  remote_unit_id=42
+    endpoint="peers",
+    remote_unit_data={"foo": "bar"},
+    remote_app_name="zookeeper",
+    remote_unit_id=42
 )
 relation.remote_unit_name  # "zookeeper/42"
 ```
 
 ## Triggering Relation Events
 
 If you want to trigger relation events, the easiest way to do so is get a hold of the Relation instance and grab the
@@ -512,36 +642,41 @@
             id='foo',
             contents={0: {'key': 'public'}}
         )
     ]
 )
 ```
 
-The only mandatory arguments to Secret are its secret ID (which should be unique) and its 'contents': that is, a mapping from revision numbers (integers) to a str:str dict representing the payload of the revision. 
+The only mandatory arguments to Secret are its secret ID (which should be unique) and its 'contents': that is, a mapping
+from revision numbers (integers) to a str:str dict representing the payload of the revision.
 
-By default, the secret is not owned by **this charm** nor is it granted to it. 
-Therefore, if charm code attempted to get that secret revision, it would get a permission error: we didn't grant it to this charm, nor we specified that the secret is owned by it.
+By default, the secret is not owned by **this charm** nor is it granted to it.
+Therefore, if charm code attempted to get that secret revision, it would get a permission error: we didn't grant it to
+this charm, nor we specified that the secret is owned by it.
 
 To specify a secret owned by this unit (or app):
+
 ```python
 from scenario import State, Secret
 
 state = State(
     secrets=[
         Secret(
             id='foo',
             contents={0: {'key': 'public'}},
             owner='unit',  # or 'app'
-            remote_grants = {0: {"remote"}}  # the secret owner has granted access to the "remote" app over some relation with ID 0
+            remote_grants={0: {"remote"}}
+            # the secret owner has granted access to the "remote" app over some relation with ID 0
         )
     ]
 )
 ```
 
 To specify a secret owned by some other application and give this unit (or app) access to it:
+
 ```python
 from scenario import State, Secret
 
 state = State(
     secrets=[
         Secret(
             id='foo',
@@ -550,14 +685,64 @@
             granted="unit",  # or "app",
             revision=0,  # the revision that this unit (or app) is currently tracking
         )
     ]
 )
 ```
 
+# Actions
+
+An action is a special sort of event, even though `ops` handles them almost identically.
+In most cases, you'll want to inspect the 'results' of an action, or whether it has failed or
+logged something while executing. Many actions don't have a direct effect on the output state.
+For this reason, the output state is less prominent in the return type of `Context.run_action`.
+
+How to test actions with scenario:
+
+## Actions without parameters
+
+```python
+from scenario import Context, State, ActionOutput
+from charm import MyCharm
+
+
+def test_backup_action():
+    ctx = Context(MyCharm)
+
+    # If you didn't declare do_backup in the charm's `actions.yaml`, 
+    # the `ConsistencyChecker` will slap you on the wrist and refuse to proceed.
+    out: ActionOutput = ctx.run_action("do_backup_action", State())
+
+    # you can assert action results, logs, failure using the ActionOutput interface
+    assert out.results == {'foo': 'bar'}
+    assert out.logs == ['baz', 'qux']
+    assert out.failure == 'boo-hoo'
+```
+
+## Parametrized Actions
+
+If the action takes parameters, you'll need to instantiate an `Action`.
+
+```python
+from scenario import Action, Context, State, ActionOutput
+from charm import MyCharm
+
+
+def test_backup_action():
+    # define an action
+    action = Action('do_backup', params={'a': 'b'})
+    ctx = Context(MyCharm)
+
+    # if the parameters (or their type) don't match what declared in actions.yaml, 
+    # the `ConsistencyChecker` will slap you on the other wrist. 
+    out: ActionOutput = ctx.run_action(action, State())
+
+    # ...
+```
+
 # Deferred events
 
 Scenario allows you to accurately simulate the Operator Framework's event queue. The event queue is responsible for
 keeping track of the deferred events. On the input side, you can verify that if the charm triggers with this and that
 event in its queue (they would be there because they had been deferred in the previous run), then the output state is
 valid.
 
@@ -719,82 +904,40 @@
         })
 ])
 ```
 
 And the charm's runtime will see `self.stored_State.foo` and `.baz` as expected. Also, you can run assertions on it on
 the output side the same as any other bit of state.
 
-# Emitted events
-
-If your charm deals with deferred events, custom events, and charm libs that in turn emit their own custom events, it
-can be hard to examine the resulting control flow. In these situations it can be useful to verify that, as a result of a
-given juju event triggering (say, 'start'), a specific chain of deferred and custom events is emitted on the charm. The
-resulting state, black-box as it is, gives little insight into how exactly it was obtained.
-
-`scenario`, among many other great things, is also a pytest plugin. It exposes a fixture called `emitted_events` that
-you can use like so:
-
-```python
-from scenario import Context
-from ops.charm import StartEvent
+# Emitting custom events
 
+While the main use case of Scenario is to emit juju events, i.e. the built-in `start`, `install`, `*-relation-changed`, etc..., it can be sometimes handy to directly trigger custom events defined on arbitrary Objects in your hierarchy.
 
-def test_foo(emitted_events):
-    Context(...).run('start', ...)
-
-    assert len(emitted_events) == 1
-    assert isinstance(emitted_events[0], StartEvent)
-```
-
-## Customizing: capture_events
-
-If you need more control over what events are captured (or you're not into pytest), you can use directly the context
-manager that powers the `emitted_events` fixture: `scenario.capture_events`.
-This context manager allows you to intercept any events emitted by the framework.
+Suppose your charm uses a charm library providing an `ingress_provided` event.
+The 'proper' way to emit it is to run the event that causes that custom event to be emitted by the library, whatever that may be, for example a `foo-relation-changed`.
 
-Usage:
+However, that may mean that you have to set up all sorts of State and mocks so that the right preconditions are met and the event is emitted at all.
 
+However if you attempt to run that event directly you will get an error:
 ```python
-from ops.charm import StartEvent, UpdateStatusEvent
-from scenario import State, Context, DeferredEvent, capture_events
-
-with capture_events() as emitted:
-    ctx = Context(...)
-    state_out = ctx.run(
-        "update-status",
-        State(deferred=[DeferredEvent("start", ...)])
-    )
-
-# deferred events get reemitted first
-assert isinstance(emitted[0], StartEvent)
-# the main juju event gets emitted next
-assert isinstance(emitted[1], UpdateStatusEvent)
-# possibly followed by a tail of all custom events that the main juju event triggered in turn
-# assert isinstance(emitted[2], MyFooEvent)
-# ...
+from scenario import Context, State
+Context(...).run("ingress_provided", State())  # raises scenario.ops_main_mock.NoObserverError
 ```
+This happens because the framework, by default, searches for an event source named `ingress_provided` in `charm.on`, but since the event is defined on another Object, it will fail to find it.
 
-You can filter events by type like so:
+You can prefix the event name with the path leading to its owner to tell Scenario where to find the event source:
 
 ```python
-from ops.charm import StartEvent, RelationEvent
-from scenario import capture_events
-
-with capture_events(StartEvent, RelationEvent) as emitted:
-    # capture all `start` and `*-relation-*` events.
-    pass
+from scenario import Context, State
+Context(...).run("my_charm_lib.on.ingress_provided", State())
 ```
 
-Passing no event types, like: `capture_events()`, is equivalent to `capture_events(EventBase)`.
-
-By default, **framework events** (`PreCommit`, `Commit`) are not considered for inclusion in the output list even if
-they match the instance check. You can toggle that by passing: `capture_events(include_framework=True)`.
+This will instruct Scenario to emit `my_charm.my_charm_lib.on.foo`.
 
-By default, **deferred events** are included in the listing if they match the instance check. You can toggle that by
-passing: `capture_events(include_deferred=True)`.
+(always omit the 'root', i.e. the charm framework key, from the path)
 
 # The virtual charm root
 
 Before executing the charm, Scenario writes the metadata, config, and actions `yaml`s to a temporary directory. The
 charm will see that tempdir as its 'root'. This allows us to keep things simple when dealing with metadata that can be
 either inferred from the charm type being passed to `Context` or be passed to it as an argument, thereby overriding
 the inferred one. This also allows you to test with charms defined on the fly, as in:
@@ -882,8 +1025,8 @@
 `scenario snapshot prometheus-k8s/0`, you will get a printout of the State object. Pipe that out into some file, import
 all you need from `scenario`, and you have a working `State` that you can `Context.run` events with.
 
 You can also pass a `--format` flag to obtain instead:
 
 - a jsonified `State` data structure, for portability
 - a full-fledged pytest test case (with imports and all), where you only have to fill in the charm type and the event
-  that you wish to trigger.
+  that you wish to trigger.
```

### Comparing `ops-scenario-3.1/ops_scenario.egg-info/PKG-INFO` & `ops-scenario-4.0/ops_scenario.egg-info/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ops-scenario
-Version: 3.1
+Version: 4.0
 Summary: Python library providing a Scenario-based testing API for Operator Framework charms.
 Author-email: Pietro Pasotti <pietro.pasotti@canonical.com>
 License: Apache-2.0
 Project-URL: Homepage, https://github.com/canonical/ops-scenario
 Project-URL: Bug Tracker, https://github.com/canonical/ops-scenario/issues
 Keywords: juju,test
 Classifier: Development Status :: 3 - Alpha
@@ -21,14 +21,15 @@
 # Scenario
 
 [![Build](https://github.com/canonical/ops-scenario/actions/workflows/build_wheels.yaml/badge.svg)](https://github.com/canonical/ops-scenario/actions/workflows/build_wheels.yaml)
 [![QC](https://github.com/canonical/ops-scenario/actions/workflows/quality_checks.yaml/badge.svg?event=pull_request)](https://github.com/canonical/ops-scenario/actions/workflows/quality_checks.yaml?event=pull_request)
 [![Discourse Status](https://img.shields.io/discourse/status?server=https%3A%2F%2Fdiscourse.charmhub.io&style=flat&label=CharmHub%20Discourse)](https://discourse.charmhub.io)
 [![foo](https://img.shields.io/badge/everything-charming-blueviolet)](https://github.com/PietroPasotti/jhack)
 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://discourse.charmhub.io/t/rethinking-charm-testing-with-ops-scenario/8649)
+[![Python >= 3.8](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/)
 
 Scenario is a state-transition, functional testing framework for Operator Framework charms.
 
 Where the Harness enables you to procedurally mock pieces of the state the charm needs to function, Scenario tests allow
 you to declaratively define the state all at once, and use it as a sort of context against which you can fire a single
 event on the charm and execute its logic.
 
@@ -88,16 +89,16 @@
     - declare the input state
     - select an event to fire
 - **Act**:
     - run the state (i.e. obtain the output state)
     - optionally, use pre-event and post-event hooks to get a hold of the charm instance and run assertions on internal
       APIs
 - **Assert**:
-    - verify that the output state is how you expect it to be
-    - optionally, verify that the delta with the input state is what you expect it to be
+    - verify that the output state (or the delta with the input state) is how you expect it to be
+    - verify that the charm has seen a certain sequence of statuses, events, and `juju-log` calls
 
 The most basic scenario is the so-called `null scenario`: one in which all is defaulted and barely any data is
 available. The charm has no config, no relations, no networks, and no leadership.
 
 With that, we can write the simplest possible scenario test:
 
 ```python
@@ -110,15 +111,15 @@
     pass
 
 
 def test_scenario_base():
     ctx = Context(MyCharm,
                   meta={"name": "foo"})
     out = ctx.run('start', State())
-    assert out.status.unit == UnknownStatus()
+    assert out.unit_status == UnknownStatus()
 ```
 
 Now let's start making it more complicated. Our charm sets a special state if it has leadership on 'start':
 
 ```python
 import pytest
 from scenario import State, Context
@@ -137,17 +138,16 @@
             self.unit.status = ActiveStatus('I am ruled')
 
 
 @pytest.mark.parametrize('leader', (True, False))
 def test_status_leader(leader):
     ctx = Context(MyCharm,
                   meta={"name": "foo"})
-    out = ctx.run('start',
-                  State(leader=leader)
-    assert out.status.unit == ActiveStatus('I rule' if leader else 'I am ruled')
+    out = ctx.run('start', State(leader=leader))
+    assert out.unit_status == ActiveStatus('I rule' if leader else 'I am ruled')
 ```
 
 By defining the right state we can programmatically define what answers will the charm get to all the questions it can
 ask the juju model: am I leader? What are my relations? What is the remote unit I'm talking to? etc...
 
 ## Statuses
 
@@ -169,33 +169,56 @@
             self.unit.status = WaitingStatus('checking this is right...')
             self._check_that_takes_some_more_time()
             self.unit.status = ActiveStatus('I am ruled')
     except:
         self.unit.status = BlockedStatus('something went wrong')
 ```
 
-You can verify that the charm has followed the expected path by checking the **unit status history** like so:
+More broadly, often we want to test 'side effects' of executing a charm, such as what events have been emitted, what statuses it went through, etc... Before we get there, we have to explain what the `Context` represents, and its relationship with the `State`.
+
+# Context and State
+
+Consider the following tests. Suppose we want to verify that while handling a given toplevel juju event:
+
+- a specific chain of (custom) events was emitted on the charm
+- the charm `juju-log`ged these specific strings
+- the charm went through this sequence of app/unit statuses (e.g. `maintenance`, then `waiting`, then `active`)
+
+These types of test have a place in Scenario, but that is not State: the contents of the juju log or the status history
+are side effects of executing a charm, but are not persisted in a charm-accessible "state" in any meaningful way.
+In other words: those data streams are, from the charm's perspective, write-only.
+
+As such, they do not belong in `scenario.State` but in `scenario.Context`: the object representing the charm's execution
+context.
+
+## Status history
+
+You can verify that the charm has followed the expected path by checking the unit/app status history like so:
 
 ```python
 from charm import MyCharm
 from ops.model import MaintenanceStatus, ActiveStatus, WaitingStatus, UnknownStatus
 from scenario import State, Context
 
 
 def test_statuses():
     ctx = Context(MyCharm,
                   meta={"name": "foo"})
-    out = ctx.run('start',
-                  State(leader=False))
-    assert out.status.unit_history == [
+    ctx.run('start', State(leader=False))
+    assert ctx.unit_status_history == [
         UnknownStatus(),
         MaintenanceStatus('determining who the ruler is...'),
         WaitingStatus('checking this is right...'),
         ActiveStatus("I am ruled"),
     ]
+
+    assert ctx.app_status_history == [
+        UnknownStatus(),
+        ActiveStatus(""),
+    ]
 ```
 
 Note that the current status is not in the **unit status history**.
 
 Also note that, unless you initialize the State with a preexisting status, the first status in the history will always
 be `unknown`. That is because, so far as scenario is concerned, each event is "the first event this charm has ever
 seen".
@@ -203,17 +226,104 @@
 If you want to simulate a situation in which the charm already has seen some event, and is in a status other than
 Unknown (the default status every charm is born with), you will have to pass the 'initial status' to State.
 
 ```python
 from ops.model import ActiveStatus
 from scenario import State, Status
 
-State(leader=False, status=Status(unit=ActiveStatus('foo')))
+# ...
+ctx.run('start', State(unit_status=ActiveStatus('foo')))
+assert ctx.unit_status_history == [
+    ActiveStatus('foo'),  # now the first status is active: 'foo'!
+    # ...
+]
+
+```
+
+## Workload version history
+
+Using a similar api to `*_status_history`, you can assert that the charm has set one or more workload versions during a
+hook execution:
+
+```python
+from scenario import Context
+
+# ...
+ctx: Context
+assert ctx.workload_version_history == ['1', '1.2', '1.5']
+# ...
+```
+
+## Emitted events
+
+If your charm deals with deferred events, custom events, and charm libs that in turn emit their own custom events, it
+can be hard to examine the resulting control flow. In these situations it can be useful to verify that, as a result of a
+given juju event triggering (say, 'start'), a specific chain of deferred and custom events is emitted on the charm. The
+resulting state, black-box as it is, gives little insight into how exactly it was obtained.
+
+```python
+from scenario import Context
+from ops.charm import StartEvent
+
+
+def test_foo():
+    ctx = Context(...)
+    ctx.run('start', ...)
+
+    assert len(ctx.emitted_events) == 1
+    assert isinstance(ctx.emitted_events[0], StartEvent)
+```
+
+### Low-level access: using directly `capture_events`
+
+If you need more control over what events are captured (or you're not into pytest), you can use directly the context
+manager that powers the `emitted_events` fixture: `scenario.capture_events`.
+This context manager allows you to intercept any events emitted by the framework.
+
+Usage:
+
+```python
+from ops.charm import StartEvent, UpdateStatusEvent
+from scenario import State, Context, DeferredEvent, capture_events
+
+with capture_events() as emitted:
+    ctx = Context(...)
+    state_out = ctx.run(
+        "update-status",
+        State(deferred=[DeferredEvent("start", ...)])
+    )
+
+# deferred events get reemitted first
+assert isinstance(emitted[0], StartEvent)
+# the main juju event gets emitted next
+assert isinstance(emitted[1], UpdateStatusEvent)
+# possibly followed by a tail of all custom events that the main juju event triggered in turn
+# assert isinstance(emitted[2], MyFooEvent)
+# ...
+```
+
+You can filter events by type like so:
+
+```python
+from ops.charm import StartEvent, RelationEvent
+from scenario import capture_events
+
+with capture_events(StartEvent, RelationEvent) as emitted:
+    # capture all `start` and `*-relation-*` events.
+    pass
 ```
 
+Configuration:
+
+- Passing no event types, like: `capture_events()`, is equivalent to `capture_events(EventBase)`.
+- By default, **framework events** (`PreCommit`, `Commit`) are not considered for inclusion in the output list even if
+  they match the instance check. You can toggle that by passing: `capture_events(include_framework=True)`.
+- By default, **deferred events** are included in the listing if they match the instance check. You can toggle that by
+  passing: `capture_events(include_deferred=True)`.
+
 ## Relations
 
 You can write scenario tests to verify the shape of relation data:
 
 ```python
 from ops.charm import CharmBase
 
@@ -322,18 +432,18 @@
   from unit IDs to databags)
 - `Relation.remote_app_name` maps to `SubordinateRelation.primary_app_name`
 
 ```python
 from scenario.state import SubordinateRelation
 
 relation = SubordinateRelation(
-  endpoint="peers",
-  remote_unit_data={"foo": "bar"},
-  remote_app_name="zookeeper",
-  remote_unit_id=42
+    endpoint="peers",
+    remote_unit_data={"foo": "bar"},
+    remote_app_name="zookeeper",
+    remote_unit_id=42
 )
 relation.remote_unit_name  # "zookeeper/42"
 ```
 
 ## Triggering Relation Events
 
 If you want to trigger relation events, the easiest way to do so is get a hold of the Relation instance and grab the
@@ -532,36 +642,41 @@
             id='foo',
             contents={0: {'key': 'public'}}
         )
     ]
 )
 ```
 
-The only mandatory arguments to Secret are its secret ID (which should be unique) and its 'contents': that is, a mapping from revision numbers (integers) to a str:str dict representing the payload of the revision. 
+The only mandatory arguments to Secret are its secret ID (which should be unique) and its 'contents': that is, a mapping
+from revision numbers (integers) to a str:str dict representing the payload of the revision.
 
-By default, the secret is not owned by **this charm** nor is it granted to it. 
-Therefore, if charm code attempted to get that secret revision, it would get a permission error: we didn't grant it to this charm, nor we specified that the secret is owned by it.
+By default, the secret is not owned by **this charm** nor is it granted to it.
+Therefore, if charm code attempted to get that secret revision, it would get a permission error: we didn't grant it to
+this charm, nor we specified that the secret is owned by it.
 
 To specify a secret owned by this unit (or app):
+
 ```python
 from scenario import State, Secret
 
 state = State(
     secrets=[
         Secret(
             id='foo',
             contents={0: {'key': 'public'}},
             owner='unit',  # or 'app'
-            remote_grants = {0: {"remote"}}  # the secret owner has granted access to the "remote" app over some relation with ID 0
+            remote_grants={0: {"remote"}}
+            # the secret owner has granted access to the "remote" app over some relation with ID 0
         )
     ]
 )
 ```
 
 To specify a secret owned by some other application and give this unit (or app) access to it:
+
 ```python
 from scenario import State, Secret
 
 state = State(
     secrets=[
         Secret(
             id='foo',
@@ -570,14 +685,64 @@
             granted="unit",  # or "app",
             revision=0,  # the revision that this unit (or app) is currently tracking
         )
     ]
 )
 ```
 
+# Actions
+
+An action is a special sort of event, even though `ops` handles them almost identically.
+In most cases, you'll want to inspect the 'results' of an action, or whether it has failed or
+logged something while executing. Many actions don't have a direct effect on the output state.
+For this reason, the output state is less prominent in the return type of `Context.run_action`.
+
+How to test actions with scenario:
+
+## Actions without parameters
+
+```python
+from scenario import Context, State, ActionOutput
+from charm import MyCharm
+
+
+def test_backup_action():
+    ctx = Context(MyCharm)
+
+    # If you didn't declare do_backup in the charm's `actions.yaml`, 
+    # the `ConsistencyChecker` will slap you on the wrist and refuse to proceed.
+    out: ActionOutput = ctx.run_action("do_backup_action", State())
+
+    # you can assert action results, logs, failure using the ActionOutput interface
+    assert out.results == {'foo': 'bar'}
+    assert out.logs == ['baz', 'qux']
+    assert out.failure == 'boo-hoo'
+```
+
+## Parametrized Actions
+
+If the action takes parameters, you'll need to instantiate an `Action`.
+
+```python
+from scenario import Action, Context, State, ActionOutput
+from charm import MyCharm
+
+
+def test_backup_action():
+    # define an action
+    action = Action('do_backup', params={'a': 'b'})
+    ctx = Context(MyCharm)
+
+    # if the parameters (or their type) don't match what declared in actions.yaml, 
+    # the `ConsistencyChecker` will slap you on the other wrist. 
+    out: ActionOutput = ctx.run_action(action, State())
+
+    # ...
+```
+
 # Deferred events
 
 Scenario allows you to accurately simulate the Operator Framework's event queue. The event queue is responsible for
 keeping track of the deferred events. On the input side, you can verify that if the charm triggers with this and that
 event in its queue (they would be there because they had been deferred in the previous run), then the output state is
 valid.
 
@@ -739,82 +904,40 @@
         })
 ])
 ```
 
 And the charm's runtime will see `self.stored_State.foo` and `.baz` as expected. Also, you can run assertions on it on
 the output side the same as any other bit of state.
 
-# Emitted events
-
-If your charm deals with deferred events, custom events, and charm libs that in turn emit their own custom events, it
-can be hard to examine the resulting control flow. In these situations it can be useful to verify that, as a result of a
-given juju event triggering (say, 'start'), a specific chain of deferred and custom events is emitted on the charm. The
-resulting state, black-box as it is, gives little insight into how exactly it was obtained.
-
-`scenario`, among many other great things, is also a pytest plugin. It exposes a fixture called `emitted_events` that
-you can use like so:
-
-```python
-from scenario import Context
-from ops.charm import StartEvent
+# Emitting custom events
 
+While the main use case of Scenario is to emit juju events, i.e. the built-in `start`, `install`, `*-relation-changed`, etc..., it can be sometimes handy to directly trigger custom events defined on arbitrary Objects in your hierarchy.
 
-def test_foo(emitted_events):
-    Context(...).run('start', ...)
-
-    assert len(emitted_events) == 1
-    assert isinstance(emitted_events[0], StartEvent)
-```
-
-## Customizing: capture_events
-
-If you need more control over what events are captured (or you're not into pytest), you can use directly the context
-manager that powers the `emitted_events` fixture: `scenario.capture_events`.
-This context manager allows you to intercept any events emitted by the framework.
+Suppose your charm uses a charm library providing an `ingress_provided` event.
+The 'proper' way to emit it is to run the event that causes that custom event to be emitted by the library, whatever that may be, for example a `foo-relation-changed`.
 
-Usage:
+However, that may mean that you have to set up all sorts of State and mocks so that the right preconditions are met and the event is emitted at all.
 
+However if you attempt to run that event directly you will get an error:
 ```python
-from ops.charm import StartEvent, UpdateStatusEvent
-from scenario import State, Context, DeferredEvent, capture_events
-
-with capture_events() as emitted:
-    ctx = Context(...)
-    state_out = ctx.run(
-        "update-status",
-        State(deferred=[DeferredEvent("start", ...)])
-    )
-
-# deferred events get reemitted first
-assert isinstance(emitted[0], StartEvent)
-# the main juju event gets emitted next
-assert isinstance(emitted[1], UpdateStatusEvent)
-# possibly followed by a tail of all custom events that the main juju event triggered in turn
-# assert isinstance(emitted[2], MyFooEvent)
-# ...
+from scenario import Context, State
+Context(...).run("ingress_provided", State())  # raises scenario.ops_main_mock.NoObserverError
 ```
+This happens because the framework, by default, searches for an event source named `ingress_provided` in `charm.on`, but since the event is defined on another Object, it will fail to find it.
 
-You can filter events by type like so:
+You can prefix the event name with the path leading to its owner to tell Scenario where to find the event source:
 
 ```python
-from ops.charm import StartEvent, RelationEvent
-from scenario import capture_events
-
-with capture_events(StartEvent, RelationEvent) as emitted:
-    # capture all `start` and `*-relation-*` events.
-    pass
+from scenario import Context, State
+Context(...).run("my_charm_lib.on.ingress_provided", State())
 ```
 
-Passing no event types, like: `capture_events()`, is equivalent to `capture_events(EventBase)`.
-
-By default, **framework events** (`PreCommit`, `Commit`) are not considered for inclusion in the output list even if
-they match the instance check. You can toggle that by passing: `capture_events(include_framework=True)`.
+This will instruct Scenario to emit `my_charm.my_charm_lib.on.foo`.
 
-By default, **deferred events** are included in the listing if they match the instance check. You can toggle that by
-passing: `capture_events(include_deferred=True)`.
+(always omit the 'root', i.e. the charm framework key, from the path)
 
 # The virtual charm root
 
 Before executing the charm, Scenario writes the metadata, config, and actions `yaml`s to a temporary directory. The
 charm will see that tempdir as its 'root'. This allows us to keep things simple when dealing with metadata that can be
 either inferred from the charm type being passed to `Context` or be passed to it as an argument, thereby overriding
 the inferred one. This also allows you to test with charms defined on the fly, as in:
```

### Comparing `ops-scenario-3.1/ops_scenario.egg-info/SOURCES.txt` & `ops-scenario-4.0/ops_scenario.egg-info/SOURCES.txt`

 * *Files 5% similar despite different names*

```diff
@@ -19,30 +19,31 @@
 scenario/capture_events.py
 scenario/consistency_checker.py
 scenario/context.py
 scenario/fs_mocks.py
 scenario/logger.py
 scenario/mocking.py
 scenario/ops_main_mock.py
-scenario/pytest_plugin.py
 scenario/runtime.py
 scenario/sequences.py
 scenario/state.py
 scenario/scripts/errors.py
 scenario/scripts/logger.py
 scenario/scripts/main.py
 scenario/scripts/snapshot.py
 scenario/scripts/state_apply.py
 scenario/scripts/utils.py
+tests/helpers.py
 tests/test_consistency_checker.py
 tests/test_emitted_events_util.py
 tests/test_plugin.py
 tests/test_runtime.py
 tests/resources/__init__.py
 tests/resources/demo_decorate_class.py
+tests/test_e2e/test_actions.py
 tests/test_e2e/test_builtin_scenes.py
 tests/test_e2e/test_config.py
 tests/test_e2e/test_custom_event_triggers.py
 tests/test_e2e/test_deferred.py
 tests/test_e2e/test_juju_log.py
 tests/test_e2e/test_network.py
 tests/test_e2e/test_observers.py
```

### Comparing `ops-scenario-3.1/pyproject.toml` & `ops-scenario-4.0/pyproject.toml`

 * *Files 6% similar despite different names*

```diff
@@ -4,15 +4,15 @@
     "setuptools_scm >= 2.0.0, <3"
 ]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "ops-scenario"
 
-version = "3.1"
+version = "4.0"
 
 authors = [
     { name = "Pietro Pasotti", email = "pietro.pasotti@canonical.com" }
 ]
 description = "Python library providing a Scenario-based testing API for Operator Framework charms."
 license.text = "Apache-2.0"
 keywords = ["juju", "test"]
@@ -31,17 +31,14 @@
     'Framework :: Pytest',
     'Intended Audience :: Developers',
     'Topic :: Software Development :: Quality Assurance',
     'Topic :: Software Development :: Testing',
     'Topic :: Utilities',
 ]
 
-[project.entry-points.pytest11]
-emitted_events = "scenario.pytest_plugin"
-
 [project.urls]
 "Homepage" = "https://github.com/canonical/ops-scenario"
 "Bug Tracker" = "https://github.com/canonical/ops-scenario/issues"
 
 [project.scripts]
 scenario = "scenario.scripts.main:main"
```

### Comparing `ops-scenario-3.1/resources/state-transition-model.png` & `ops-scenario-4.0/resources/state-transition-model.png`

 * *Files identical despite different names*

### Comparing `ops-scenario-3.1/scenario/capture_events.py` & `ops-scenario-4.0/scenario/capture_events.py`

 * *Files 12% similar despite different names*

```diff
@@ -49,14 +49,16 @@
     _real_reemit = Framework.reemit
 
     def _wrapped_emit(self, evt):
         if not include_framework and isinstance(evt, (PreCommitEvent, CommitEvent)):
             return _real_emit(self, evt)
 
         if isinstance(evt, allowed_types):
+            # dump/undump the event to ensure any custom attributes are (re)set by restore()
+            evt.restore(evt.snapshot())
             captured.append(evt)
 
         return _real_emit(self, evt)
 
     def _wrapped_reemit(self):
         # Framework calls reemit() before emitting the main juju event. We intercept that call
         # and capture all events in storage.
```

### Comparing `ops-scenario-3.1/scenario/consistency_checker.py` & `ops-scenario-4.0/scenario/consistency_checker.py`

 * *Files 15% similar despite different names*

```diff
@@ -1,15 +1,26 @@
+#!/usr/bin/env python3
+# Copyright 2023 Canonical Ltd.
+# See LICENSE file for licensing details.
 import os
 from collections import Counter
+from collections.abc import Sequence
 from itertools import chain
-from typing import TYPE_CHECKING, Iterable, NamedTuple, Tuple
+from numbers import Number
+from typing import TYPE_CHECKING, Iterable, List, NamedTuple, Tuple
 
 from scenario.runtime import InconsistentScenarioError
 from scenario.runtime import logger as scenario_logger
-from scenario.state import PeerRelation, SubordinateRelation, _CharmSpec, normalize_name
+from scenario.state import (
+    Action,
+    PeerRelation,
+    SubordinateRelation,
+    _CharmSpec,
+    normalize_name,
+)
 
 if TYPE_CHECKING:
     from scenario.state import Event, State
 
 logger = scenario_logger.getChild("consistency_checker")
 
 
@@ -91,47 +102,141 @@
     For example, it checks that a relation event has a relation instance, and that
     the relation endpoint name matches the event prefix.
     """
     errors = []
     warnings = []
 
     # custom event: can't make assumptions about its name and its semantics
+    # todo: should we then just skip the other checks?
     if not event._is_builtin_event(charm_spec):
         warnings.append(
             "this is a custom event; if its name makes it look like a builtin one "
             "(e.g. a relation event, or a workload event), you might get some false-negative "
             "consistency checks.",
         )
 
     if event._is_relation_event:
-        if not event.relation:
+        _check_relation_event(charm_spec, event, errors, warnings)
+
+    if event._is_workload_event:
+        _check_workload_event(charm_spec, event, errors, warnings)
+
+    if event._is_action_event:
+        _check_action_event(charm_spec, event, errors, warnings)
+
+    return Results(errors, warnings)
+
+
+def _check_relation_event(
+    charm_spec: _CharmSpec,  # noqa: U100
+    event: "Event",
+    errors: List[str],
+    warnings: List[str],  # noqa: U100
+):
+    if not event.relation:
+        errors.append(
+            "cannot construct a relation event without the relation instance. "
+            "Please pass one.",
+        )
+    else:
+        if not event.name.startswith(normalize_name(event.relation.endpoint)):
             errors.append(
-                "cannot construct a relation event without the relation instance. "
-                "Please pass one.",
+                f"relation event should start with relation endpoint name. {event.name} does "
+                f"not start with {event.relation.endpoint}.",
             )
-        else:
-            if not event.name.startswith(normalize_name(event.relation.endpoint)):
-                errors.append(
-                    f"relation event should start with relation endpoint name. {event.name} does "
-                    f"not start with {event.relation.endpoint}.",
-                )
 
-    if event._is_workload_event:
-        if not event.container:
+
+def _check_workload_event(
+    charm_spec: _CharmSpec,  # noqa: U100
+    event: "Event",
+    errors: List[str],
+    warnings: List[str],  # noqa: U100
+):
+    if not event.container:
+        errors.append(
+            "cannot construct a workload event without the container instance. "
+            "Please pass one.",
+        )
+    elif not event.name.startswith(normalize_name(event.container.name)):
+        errors.append(
+            f"workload event should start with container name. {event.name} does "
+            f"not start with {event.container.name}.",
+        )
+
+
+def _check_action_event(
+    charm_spec: _CharmSpec,
+    event: "Event",
+    errors: List[str],
+    warnings: List[str],
+):
+    action = event.action
+    if not action:
+        errors.append(
+            "cannot construct a workload event without the container instance. "
+            "Please pass one.",
+        )
+    elif not event.name.startswith(normalize_name(action.name)):
+        errors.append(
+            f"action event should start with action name. {event.name} does "
+            f"not start with {action.name}.",
+        )
+    if action.name not in charm_spec.actions:
+        errors.append(
+            f"action event {event.name} refers to action {action.name} "
+            f"which is not declared in the charm metadata (actions.yaml).",
+        )
+
+    _check_action_param_types(charm_spec, action, errors, warnings)
+
+
+def _check_action_param_types(
+    charm_spec: _CharmSpec,
+    action: Action,
+    errors: List[str],
+    warnings: List[str],
+):
+    to_python_type = {
+        "string": str,
+        "boolean": bool,
+        "number": Number,
+        "array": Sequence,
+        "object": dict,
+    }
+    expected_param_type = {}
+    for par_name, par_spec in charm_spec.actions[action.name].get("params", {}).items():
+        value = par_spec.get("type")
+        if not value:
             errors.append(
-                "cannot construct a workload event without the container instance. "
-                "Please pass one.",
+                f"action parameter {par_name} has no type. "
+                f"Charmcraft will be unhappy about this. ",
+            )
+            continue
+
+        try:
+            expected_param_type[par_name] = to_python_type[value]
+        except KeyError:
+            warnings.append(
+                f"unknown data type declared for parameter {par_name}: type={value}. "
+                f"Cannot consistency-check.",
+            )
+
+    for provided_param_name, provided_param_value in action.params.items():
+        expected_type = expected_param_type.get(provided_param_name)
+        if not expected_type:
+            errors.append(
+                f"param {provided_param_name} is not a valid parameter for {action.name}: "
+                "missing from action specification",
+            )
+            continue
+        if not isinstance(provided_param_value, expected_type):
+            errors.append(
+                f"param {provided_param_name} is of type {type(provided_param_value)}: "
+                f"expecting {expected_type}",
             )
-        else:
-            if not event.name.startswith(normalize_name(event.container.name)):
-                errors.append(
-                    f"workload event should start with container name. {event.name} does "
-                    f"not start with {event.container.name}.",
-                )
-    return Results(errors, warnings)
 
 
 def check_config_consistency(
     *,
     state: "State",
     charm_spec: "_CharmSpec",
     **_kwargs,  # noqa: U101
```

### Comparing `ops-scenario-3.1/scenario/context.py` & `ops-scenario-4.0/scenario/ops_main_mock.py`

 * *Files 22% similar despite different names*

```diff
@@ -1,110 +1,150 @@
 #!/usr/bin/env python3
 # Copyright 2023 Canonical Ltd.
 # See LICENSE file for licensing details.
-from typing import TYPE_CHECKING, Any, Callable, Dict, Optional, Type, Union
-
-from scenario.logger import logger as scenario_logger
-from scenario.runtime import Runtime
-from scenario.state import Event, _CharmSpec
+import inspect
+import os
+from typing import TYPE_CHECKING, Any, Callable, Optional, Sequence
+
+import ops.charm
+import ops.framework
+import ops.model
+import ops.storage
+from ops import CharmBase
+from ops.charm import CharmMeta
+from ops.log import setup_root_logging
+
+# use logger from ops.main so that juju_log will be triggered
+from ops.main import CHARM_STATE_FILE, _Dispatcher, _get_charm_dir, _get_event_args
+from ops.main import logger as ops_logger
 
 if TYPE_CHECKING:
-    from pathlib import Path
-
     from ops.testing import CharmType
 
-    from scenario.state import State
+    from scenario.context import Context
+    from scenario.state import Event, State, _CharmSpec
 
-    PathLike = Union[str, Path]
 
-logger = scenario_logger.getChild("runtime")
+class NoObserverError(RuntimeError):
+    """Error raised when the event being dispatched has no registered observers."""
 
 
-class Context:
-    """Scenario test execution context."""
-
-    def __init__(
-        self,
-        charm_type: Type["CharmType"],
-        meta: Optional[Dict[str, Any]] = None,
-        actions: Optional[Dict[str, Any]] = None,
-        config: Optional[Dict[str, Any]] = None,
-        charm_root: "PathLike" = None,
-        juju_version: str = "3.0",
-    ):
-        """Initializer.
-
-        :arg charm_type: the CharmBase subclass to call ``ops.main()`` on.
-        :arg meta: charm metadata to use. Needs to be a valid metadata.yaml format (as a dict).
-            If none is provided, we will search for a ``metadata.yaml`` file in the charm root.
-        :arg actions: charm actions to use. Needs to be a valid actions.yaml format (as a dict).
-            If none is provided, we will search for a ``actions.yaml`` file in the charm root.
-        :arg config: charm config to use. Needs to be a valid config.yaml format (as a dict).
-            If none is provided, we will search for a ``config.yaml`` file in the charm root.
-        :arg juju_version: Juju agent version to simulate.
-        :arg charm_root: virtual charm root the charm will be executed with.
-            If the charm, say, expects a `./src/foo/bar.yaml` file present relative to the
-            execution cwd, you need to use this. E.g.:
-
-            >>> import scenario
-            >>> import tempfile
-            >>> virtual_root = tempfile.TemporaryDirectory()
-            >>> local_path = Path(local_path.name)
-            >>> (local_path / 'foo').mkdir()
-            >>> (local_path / 'foo' / 'bar.yaml').write_text('foo: bar')
-            >>> scenario.Context(... charm_root=virtual_root).run(...)
-
-        """
-
-        if not any((meta, actions, config)):
-            logger.debug("Autoloading charmspec...")
-            spec = _CharmSpec.autoload(charm_type)
-        else:
-            if not meta:
-                meta = {"name": str(charm_type.__name__)}
-            spec = _CharmSpec(
-                charm_type=charm_type,
-                meta=meta,
-                actions=actions,
-                config=config,
-            )
+class BadOwnerPath(RuntimeError):
+    """Error raised when the owner path does not lead to a valid ObjectEvents instance."""
 
-        self.charm_spec = spec
-        self.charm_root = charm_root
-        self.juju_version = juju_version
-
-    def run(
-        self,
-        event: Union["Event", str],
-        state: "State",
-        pre_event: Optional[Callable[["CharmType"], None]] = None,
-        post_event: Optional[Callable[["CharmType"], None]] = None,
-    ) -> "State":
-        """Trigger a charm execution with an Event and a State.
-
-        Calling this function will call ops' main() and set up the context according to the
-        specified State, then emit the event on the charm.
-
-        :arg event: the Event that the charm will respond to. Can be a string or an Event instance.
-        :arg state: the State instance to use as data source for the hook tool calls that the
-            charm will invoke when handling the Event.
-        :arg pre_event: callback to be invoked right before emitting the event on the newly
-            instantiated charm. Will receive the charm instance as only positional argument.
-        :arg post_event: callback to be invoked right after emitting the event on the charm.
-            Will receive the charm instance as only positional argument.
-        """
-
-        runtime = Runtime(
-            charm_spec=self.charm_spec,
-            juju_version=self.juju_version,
-            charm_root=self.charm_root,
+
+def _get_owner(root: Any, path: Sequence[str]) -> ops.ObjectEvents:
+    """Walk path on root to an ObjectEvents instance."""
+    obj = root
+    for step in path:
+        try:
+            obj = getattr(obj, step)
+        except AttributeError:
+            raise BadOwnerPath(
+                f"event_owner_path {path!r} invalid: {step!r} leads to nowhere.",
+            )
+    if not isinstance(obj, ops.ObjectEvents):
+        raise BadOwnerPath(
+            f"event_owner_path {path!r} invalid: does not lead to "
+            f"an ObjectEvents instance.",
         )
+    return obj
 
-        if isinstance(event, str):
-            event = Event(event)
 
-        return runtime.exec(
-            state=state,
-            event=event,
-            pre_event=pre_event,
-            post_event=post_event,
+def _emit_charm_event(
+    charm: "CharmBase",
+    event_name: str,
+    event: "Event" = None,
+):
+    """Emits a charm event based on a Juju event name.
+
+    Args:
+        charm: A charm instance to emit an event from.
+        event_name: A Juju event name to emit on a charm.
+        event_owner_path: Event source lookup path.
+    """
+    owner = _get_owner(charm, event.owner_path) if event else charm.on
+
+    try:
+        event_to_emit = getattr(owner, event_name)
+    except AttributeError:
+        ops_logger.debug("Event %s not defined for %s.", event_name, charm)
+        raise NoObserverError(
+            f"Cannot fire {event_name!r} on {owner}: "
+            f"invalid event (not on charm.on). "
+            f"Use Context.run_custom instead.",
         )
+
+    args, kwargs = _get_event_args(charm, event_to_emit)
+    ops_logger.debug("Emitting Juju event %s.", event_name)
+    event_to_emit.emit(*args, **kwargs)
+
+
+def main(
+    pre_event: Optional[Callable[["CharmType"], None]] = None,
+    post_event: Optional[Callable[["CharmType"], None]] = None,
+    state: "State" = None,
+    event: "Event" = None,
+    context: "Context" = None,
+    charm_spec: "_CharmSpec" = None,
+):
+    """Set up the charm and dispatch the observed event."""
+    charm_class = charm_spec.charm_type
+    charm_dir = _get_charm_dir()
+
+    from scenario.mocking import _MockModelBackend
+
+    model_backend = _MockModelBackend(  # pyright: reportPrivateUsage=false
+        state=state,
+        event=event,
+        context=context,
+        charm_spec=charm_spec,
+    )
+    debug = "JUJU_DEBUG" in os.environ
+    setup_root_logging(model_backend, debug=debug)
+    ops_logger.debug(
+        "Operator Framework %s up and running.",
+        ops.__version__,
+    )  # type:ignore
+
+    dispatcher = _Dispatcher(charm_dir)
+    dispatcher.run_any_legacy_hook()
+
+    metadata = (charm_dir / "metadata.yaml").read_text()
+    actions_meta = charm_dir / "actions.yaml"
+    if actions_meta.exists():
+        actions_metadata = actions_meta.read_text()
+    else:
+        actions_metadata = None
+
+    meta = CharmMeta.from_yaml(metadata, actions_metadata)
+    model = ops.model.Model(meta, model_backend)
+
+    charm_state_path = charm_dir / CHARM_STATE_FILE
+
+    # TODO: add use_juju_for_storage support
+    store = ops.storage.SQLiteStorage(charm_state_path)
+    framework = ops.framework.Framework(store, charm_dir, meta, model)
+    framework.set_breakpointhook()
+    try:
+        sig = inspect.signature(charm_class)
+        sig.bind(framework)  # signature check
+
+        charm = charm_class(framework)
+        dispatcher.ensure_event_links(charm)
+
+        # Skip reemission of deferred events for collect-metrics events because
+        # they do not have the full access to all hook tools.
+        if not dispatcher.is_restricted_context():
+            framework.reemit()
+
+        if pre_event:
+            pre_event(charm)
+
+        _emit_charm_event(charm, dispatcher.event_name, event)
+
+        if post_event:
+            post_event(charm)
+
+        framework.commit()
+    finally:
+        framework.close()
```

### Comparing `ops-scenario-3.1/scenario/fs_mocks.py` & `ops-scenario-4.0/scenario/fs_mocks.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,7 +1,10 @@
+#!/usr/bin/env python3
+# Copyright 2023 Canonical Ltd.
+# See LICENSE file for licensing details.
 import pathlib
 from typing import Dict
 
 from ops.testing import _TestingFilesystem, _TestingStorageMount  # noqa
 
 
 # todo consider duplicating the filesystem on State.copy() to be able to diff
```

### Comparing `ops-scenario-3.1/scenario/mocking.py` & `ops-scenario-4.0/scenario/mocking.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,24 +1,30 @@
 #!/usr/bin/env python3
 # Copyright 2023 Canonical Ltd.
 # See LICENSE file for licensing details.
 import datetime
 import random
 from io import StringIO
-from typing import TYPE_CHECKING, Dict, Optional, Tuple, Union
+from typing import TYPE_CHECKING, Any, Dict, Optional, Tuple, Union
 
 from ops import pebble
-from ops.model import SecretInfo, SecretRotate, _ModelBackend
+from ops.model import (
+    SecretInfo,
+    SecretRotate,
+    _format_action_result_dict,
+    _ModelBackend,
+)
 from ops.pebble import Client, ExecError
 from ops.testing import _TestingPebbleClient
 
 from scenario.logger import logger as scenario_logger
-from scenario.state import PeerRelation
+from scenario.state import JujuLogLine, PeerRelation
 
 if TYPE_CHECKING:
+    from scenario.context import Context
     from scenario.state import Container as ContainerSpec
     from scenario.state import (
         Event,
         ExecOutput,
         Relation,
         State,
         SubordinateRelation,
@@ -51,18 +57,25 @@
         return out.stdout, out.stderr
 
     def send_signal(self, sig: Union[int, str]):  # noqa: U100
         raise NotImplementedError()
 
 
 class _MockModelBackend(_ModelBackend):
-    def __init__(self, state: "State", event: "Event", charm_spec: "_CharmSpec"):
+    def __init__(
+        self,
+        state: "State",
+        event: "Event",
+        charm_spec: "_CharmSpec",
+        context: "Context",
+    ):
         super().__init__()
         self._state = state
         self._event = event
+        self._context = context
         self._charm_spec = charm_spec
 
     def get_pebble(self, socket_path: str) -> "Client":
         return _MockPebbleClient(
             socket_path=socket_path,
             state=self._state,
             event=self._event,
@@ -115,15 +128,15 @@
         unit_id = int(obj_name.split("/")[-1])
         return relation._get_databag_for_remote(unit_id)  # noqa
 
     def is_leader(self):
         return self._state.leader
 
     def status_get(self, *, is_app: bool = False):
-        status, message = self._state.status.app if is_app else self._state.status.unit
+        status, message = self._state.app_status if is_app else self._state.unit_status
         return {"status": status, "message": message}
 
     def relation_ids(self, relation_name):
         return [
             rel.relation_id
             for rel in self._state.relations
             if rel.endpoint == relation_name
@@ -159,21 +172,26 @@
             logger.warning("network-get -r not implemented")
 
         network = next(filter(lambda r: r.name == binding_name, self._state.networks))
         return network.hook_tool_output_fmt()
 
     # setter methods: these can mutate the state.
     def application_version_set(self, version: str):
-        self._state.status._update_workload_version(version)
+        if workload_version := self._state.workload_version:
+            # do not record if empty = unset
+            self._context.workload_version_history.append(workload_version)
+
+        self._state._update_workload_version(version)
 
     def status_set(self, status: str, message: str = "", *, is_app: bool = False):
-        self._state.status._update_status(status, message, is_app)
+        self._context._record_status(self._state, is_app)
+        self._state._update_status(status, message, is_app)
 
     def juju_log(self, level: str, message: str):
-        self._state.juju_log.append((level, message))
+        self._context.juju_log.append(JujuLogLine(level, message))
 
     def relation_set(self, relation_id: int, key: str, value: str, is_app: bool):
         relation = self._get_relation_by_id(relation_id)
         if is_app:
             if not self._state.leader:
                 raise RuntimeError("needs leadership to set app data")
             tgt = relation.local_app_data
@@ -295,30 +313,50 @@
         else:
             secret.contents.clear()
 
     def relation_remote_app_name(self, relation_id: int):
         relation = self._get_relation_by_id(relation_id)
         return relation.remote_app_name
 
-    # TODO:
-    def action_set(self, *args, **kwargs):  # noqa: U100
-        raise NotImplementedError("action_set")
+    def action_set(self, results: Dict[str, Any]):
+        if not self._event.action:
+            raise RuntimeError(
+                "not in the context of an action event: cannot action-set",
+            )
+        # let ops validate the results dict
+        _format_action_result_dict(results)
+        # but then we will store it in its unformatted, original form
+        self._context._action_results = results
+
+    def action_fail(self, message: str = ""):
+        if not self._event.action:
+            raise RuntimeError(
+                "not in the context of an action event: cannot action-fail",
+            )
+        self._context._action_failure = message
 
-    def action_fail(self, *args, **kwargs):  # noqa: U100
-        raise NotImplementedError("action_fail")
+    def action_log(self, message: str):
+        if not self._event.action:
+            raise RuntimeError(
+                "not in the context of an action event: cannot action-log",
+            )
+        self._context._action_logs.append(message)
 
-    def action_log(self, *args, **kwargs):  # noqa: U100
-        raise NotImplementedError("action_log")
+    def action_get(self):
+        action = self._event.action
+        if not action:
+            raise RuntimeError(
+                "not in the context of an action event: cannot action-get",
+            )
+        return action.params
 
+    # TODO:
     def storage_add(self, *args, **kwargs):  # noqa: U100
         raise NotImplementedError("storage_add")
 
-    def action_get(self):
-        raise NotImplementedError("action_get")
-
     def resource_get(self, *args, **kwargs):  # noqa: U100
         raise NotImplementedError("resource_get")
 
     def storage_list(self, *args, **kwargs):  # noqa: U100
         raise NotImplementedError("storage_list")
 
     def storage_get(self, *args, **kwargs):  # noqa: U100
```

### Comparing `ops-scenario-3.1/scenario/runtime.py` & `ops-scenario-4.0/scenario/runtime.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,39 +1,44 @@
 #!/usr/bin/env python3
 # Copyright 2023 Canonical Ltd.
 # See LICENSE file for licensing details.
 import marshal
 import os
 import re
 import tempfile
+import typing
 from contextlib import contextmanager
 from pathlib import Path
 from typing import (
     TYPE_CHECKING,
     Any,
     Callable,
+    ContextManager,
     Dict,
     List,
     Optional,
+    Tuple,
     Type,
     TypeVar,
     Union,
 )
 
 import yaml
-from ops.framework import _event_regex
+from ops.framework import EventBase, _event_regex
 from ops.storage import SQLiteStorage
 
+from scenario.capture_events import capture_events
 from scenario.logger import logger as scenario_logger
 from scenario.ops_main_mock import NoObserverError
 from scenario.state import DeferredEvent, PeerRelation, StoredState
 
 if TYPE_CHECKING:
     from ops.testing import CharmType
 
+    from scenario.context import Context
     from scenario.state import AnyRelation, Event, State, _CharmSpec
 
     _CT = TypeVar("_CT", bound=Type[CharmType])
 
     PathLike = Union[str, Path]
 
 logger = scenario_logger.getChild("runtime")
@@ -248,15 +253,15 @@
         class WrappedCharm(charm_type):  # type: ignore
             on = WrappedEvents()
 
         WrappedCharm.__name__ = charm_type.__name__
         return WrappedCharm
 
     @contextmanager
-    def virtual_charm_root(self):
+    def _virtual_charm_root(self) -> typing.ContextManager[Path]:
         # If we are using runtime on a real charm, we can make some assumptions about the
         # directory structure we are going to find.
         # If we're, say, dynamically defining charm types and doing tests on them, we'll have to
         # generate the metadata files ourselves. To be sure, we ALWAYS use a tempdir. Ground truth
         # is what the user passed via the CharmSpec
         spec = self._charm_spec
 
@@ -319,44 +324,53 @@
     def _close_storage(self, state: "State", temporary_charm_root: Path):
         """Now that we're done processing this event, read the charm state and expose it."""
         store = self._get_state_db(temporary_charm_root)
         deferred = store.get_deferred_events()
         stored_state = store.get_stored_state()
         return state.replace(deferred=deferred, stored_state=stored_state)
 
+    @contextmanager
+    def _exec_ctx(self) -> ContextManager[Tuple[Path, List[EventBase]]]:
+        """python 3.8 compatibility shim"""
+        with self._virtual_charm_root() as temporary_charm_root:
+            # todo allow customizing capture_events
+            with capture_events() as captured:
+                yield (temporary_charm_root, captured)
+
     def exec(
         self,
         state: "State",
         event: "Event",
+        context: "Context",
         pre_event: Optional[Callable[["CharmType"], None]] = None,
         post_event: Optional[Callable[["CharmType"], None]] = None,
     ) -> "State":
         """Runs an event with this state as initial state on a charm.
 
         Returns the 'output state', that is, the state as mutated by the charm during the
         event handling.
 
         This will set the environment up and call ops.main.main().
         After that it's up to ops.
         """
+        # todo consider forking out a real subprocess and do the mocking by
+        #  mocking hook tool executables
+
         from scenario.consistency_checker import check_consistency  # avoid cycles
 
         check_consistency(state, event, self._charm_spec, self._juju_version)
 
         charm_type = self._charm_spec.charm_type
         logger.info(f"Preparing to fire {event.name} on {charm_type.__name__}")
 
         # we make a copy to avoid mutating the input state
         output_state = state.copy()
 
         logger.info(" - generating virtual charm root")
-        with self.virtual_charm_root() as temporary_charm_root:
-            # todo consider forking out a real subprocess and do the mocking by
-            #  generating hook tool executables
-
+        with self._exec_ctx() as (temporary_charm_root, captured):
             logger.info(" - initializing storage")
             self._initialize_storage(state, temporary_charm_root)
 
             logger.info(" - preparing env")
             env = self._get_event_env(
                 state=state,
                 event=event,
@@ -371,14 +385,15 @@
 
             try:
                 mocked_main(
                     pre_event=pre_event,
                     post_event=post_event,
                     state=output_state,
                     event=event,
+                    context=context,
                     charm_spec=self._charm_spec.replace(
                         charm_type=self._wrap(charm_type),
                     ),
                 )
             except NoObserverError:
                 raise  # propagate along
             except Exception as e:
@@ -390,14 +405,16 @@
 
             logger.info(" - Clearing env")
             self._cleanup_env(env)
 
             logger.info(" - closing storage")
             output_state = self._close_storage(output_state, temporary_charm_root)
 
+        context.emitted_events.extend(captured)
+
         logger.info("event dispatched. done.")
         return output_state
 
 
 def trigger(
     state: "State",
     event: Union["Event", str],
@@ -438,37 +455,22 @@
         >>> virtual_root = tempfile.TemporaryDirectory()
         >>> local_path = Path(local_path.name)
         >>> (local_path / 'foo').mkdir()
         >>> (local_path / 'foo' / 'bar.yaml').write_text('foo: bar')
         >>> scenario, State(), (... charm_root=virtual_root)
 
     """
-    from scenario.state import Event, _CharmSpec
-
-    if isinstance(event, str):
-        event = Event(event)
-
-    if not any((meta, actions, config)):
-        logger.debug("Autoloading charmspec...")
-        spec = _CharmSpec.autoload(charm_type)
-    else:
-        if not meta:
-            meta = {"name": str(charm_type.__name__)}
-        spec = _CharmSpec(
-            charm_type=charm_type,
-            meta=meta,
-            actions=actions,
-            config=config,
-        )
-
-    runtime = Runtime(
-        charm_spec=spec,
-        juju_version=juju_version,
-        charm_root=charm_root,
+    logger.warning(
+        "DEPRECATION NOTICE: scenario.runtime.trigger() is deprecated and "
+        "will be removed soon; please use the scenario.context.Context api.",
     )
+    from scenario.context import Context
 
-    return runtime.exec(
-        state=state,
-        event=event,
-        pre_event=pre_event,
-        post_event=post_event,
+    ctx = Context(
+        charm_type=charm_type,
+        meta=meta,
+        actions=actions,
+        config=config,
+        charm_root=charm_root,
+        juju_version=juju_version,
     )
+    return ctx.run(event, state=state, pre_event=pre_event, post_event=post_event)
```

### Comparing `ops-scenario-3.1/scenario/scripts/main.py` & `ops-scenario-4.0/scenario/scripts/main.py`

 * *Files identical despite different names*

### Comparing `ops-scenario-3.1/scenario/scripts/snapshot.py` & `ops-scenario-4.0/scenario/scripts/snapshot.py`

 * *Files 1% similar despite different names*

```diff
@@ -5,15 +5,15 @@
 import datetime
 import json
 import os
 import re
 import shlex
 import sys
 import tempfile
-from dataclasses import asdict
+from dataclasses import asdict, dataclass
 from enum import Enum
 from itertools import chain
 from pathlib import Path
 from subprocess import run
 from typing import Any, BinaryIO, Dict, Iterable, List, Optional, TextIO, Tuple, Union
 
 import ops.pebble
@@ -31,15 +31,14 @@
     Container,
     Model,
     Mount,
     Network,
     Relation,
     Secret,
     State,
-    Status,
     _EntityStatus,
 )
 
 logger = root_scripts_logger.getChild(__file__)
 
 JUJU_RELATION_KEYS = frozenset({"egress-subnets", "ingress-address", "private-address"})
 JUJU_CONFIG_KEYS = frozenset({})
@@ -438,14 +437,21 @@
 
 def get_juju_status(model: Optional[str]) -> Dict:
     """Return juju status as json."""
     logger.info("getting status...")
     return _juju_run("status --relations", model=model)
 
 
+@dataclass
+class Status:
+    app: _EntityStatus
+    unit: _EntityStatus
+    workload_version: str
+
+
 def get_status(juju_status: Dict, target: JujuUnitName) -> Status:
     """Parse `juju status` to get the Status data structure and some relation information."""
     app = juju_status["applications"][target.app_name]
 
     app_status_raw = app["application-status"]
     app_status = app_status_raw["current"], app_status_raw.get("message", "")
 
@@ -734,18 +740,22 @@
         logger.critical(f"could not fetch metadata from {target}.")
         sys.exit(1)
 
     try:
         unit_state_db = RemoteUnitStateDB(model, target)
         juju_status = get_juju_status(model)
         endpoints = get_endpoints(juju_status, target)
+        status = get_status(juju_status, target=target)
+
         state = State(
             leader=get_leader(target, model),
+            unit_status=status.unit,
+            app_status=status.app,
+            workload_version=status.workload_version,
             model=state_model,
-            status=get_status(juju_status, target=target),
             config=if_include("c", lambda: get_config(target, model), {}),
             relations=if_include(
                 "r",
                 lambda: get_relations(
                     target,
                     model,
                     metadata=metadata,
```

### Comparing `ops-scenario-3.1/scenario/scripts/state_apply.py` & `ops-scenario-4.0/scenario/scripts/state_apply.py`

 * *Files identical despite different names*

### Comparing `ops-scenario-3.1/scenario/scripts/utils.py` & `ops-scenario-4.0/scenario/scripts/utils.py`

 * *Files identical despite different names*

### Comparing `ops-scenario-3.1/scenario/sequences.py` & `ops-scenario-4.0/scenario/sequences.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 #!/usr/bin/env python3
 # Copyright 2023 Canonical Ltd.
 # See LICENSE file for licensing details.
 import typing
 from itertools import chain
 from typing import Any, Callable, Dict, Iterable, Optional, TextIO, Type, Union
 
-from scenario import trigger
+from scenario import Context
 from scenario.logger import logger as scenario_logger
 from scenario.state import (
     ATTACH_ALL_STORAGES,
     BREAK_ALL_RELATIONS,
     CREATE_ALL_RELATIONS,
     DETACH_ALL_STORAGES,
     META_EVENTS,
@@ -107,24 +107,25 @@
     should pass out of the box.
 
     If you want to, you can inject more stringent state checks using the
     pre_event and post_event hooks.
     """
 
     template = template_state if template_state else State()
+    out = []
 
     for event, state in generate_builtin_sequences(
         (
             template.replace(leader=True),
             template.replace(leader=False),
         ),
     ):
-        trigger(
-            state,
-            event=event,
-            charm_type=charm_type,
-            meta=meta,
-            actions=actions,
-            config=config,
-            pre_event=pre_event,
-            post_event=post_event,
+        ctx = Context(charm_type=charm_type, meta=meta, actions=actions, config=config)
+        out.append(
+            ctx.run(
+                event,
+                state=state,
+                pre_event=pre_event,
+                post_event=post_event,
+            ),
         )
+    return out
```

### Comparing `ops-scenario-3.1/scenario/state.py` & `ops-scenario-4.0/scenario/state.py`

 * *Files 4% similar despite different names*

```diff
@@ -3,60 +3,67 @@
 # See LICENSE file for licensing details.
 import copy
 import dataclasses
 import datetime
 import inspect
 import re
 import typing
+from collections import namedtuple
 from itertools import chain
 from pathlib import Path, PurePosixPath
 from typing import Any, Callable, Dict, List, Literal, Optional, Set, Tuple, Type, Union
 from uuid import uuid4
 
 import yaml
 from ops import pebble
 from ops.charm import CharmEvents
 from ops.model import SecretRotate, StatusBase
 
 from scenario.fs_mocks import _MockFileSystem, _MockStorageMount
 from scenario.logger import logger as scenario_logger
 
+JujuLogLine = namedtuple("JujuLogLine", ("level", "message"))
+
 if typing.TYPE_CHECKING:
     try:
         from typing import Self
     except ImportError:
         from typing_extensions import Self
     from ops.testing import CharmType
 
     PathLike = Union[str, Path]
     AnyRelation = Union["Relation", "PeerRelation", "SubordinateRelation"]
+    AnyJson = Union[str, bool, dict, int, float, list]
 
 logger = scenario_logger.getChild("state")
 
 ATTACH_ALL_STORAGES = "ATTACH_ALL_STORAGES"
 CREATE_ALL_RELATIONS = "CREATE_ALL_RELATIONS"
 BREAK_ALL_RELATIONS = "BREAK_ALL_RELATIONS"
 DETACH_ALL_STORAGES = "DETACH_ALL_STORAGES"
+
+ACTION_EVENT_SUFFIX = "_action"
+PEBBLE_READY_EVENT_SUFFIX = "_pebble_ready"
 RELATION_EVENTS_SUFFIX = {
     "_relation_changed",
     "_relation_broken",
     "_relation_joined",
     "_relation_departed",
     "_relation_created",
 }
 STORAGE_EVENTS_SUFFIX = {
     "_storage_detaching",
     "_storage_attached",
 }
 
-SECRET_EVENTS_SUFFIX = {
-    "_secret_changed",
-    "_secret_removed",
-    "_secret_rotate",
-    "_secret_expired",
+SECRET_EVENTS = {
+    "secret_changed",
+    "secret_removed",
+    "secret_rotate",
+    "secret_expired",
 }
 
 META_EVENTS = {
     "CREATE_ALL_RELATIONS": "_relation_created",
     "BREAK_ALL_RELATIONS": "_relation_broken",
     "DETACH_ALL_STORAGES": "_storage_detaching",
     "ATTACH_ALL_STORAGES": "_storage_attached",
@@ -260,47 +267,47 @@
                     f"found a value of type {type(v)}",
                 )
 
     @property
     def changed_event(self) -> "Event":
         """Sugar to generate a <this relation>-relation-changed event."""
         return Event(
-            name=normalize_name(self.endpoint + "-relation-changed"),
+            path=normalize_name(self.endpoint + "-relation-changed"),
             relation=self,
         )
 
     @property
     def joined_event(self) -> "Event":
         """Sugar to generate a <this relation>-relation-joined event."""
         return Event(
-            name=normalize_name(self.endpoint + "-relation-joined"),
+            path=normalize_name(self.endpoint + "-relation-joined"),
             relation=self,
         )
 
     @property
     def created_event(self) -> "Event":
         """Sugar to generate a <this relation>-relation-created event."""
         return Event(
-            name=normalize_name(self.endpoint + "-relation-created"),
+            path=normalize_name(self.endpoint + "-relation-created"),
             relation=self,
         )
 
     @property
     def departed_event(self) -> "Event":
         """Sugar to generate a <this relation>-relation-departed event."""
         return Event(
-            name=normalize_name(self.endpoint + "-relation-departed"),
+            path=normalize_name(self.endpoint + "-relation-departed"),
             relation=self,
         )
 
     @property
     def broken_event(self) -> "Event":
         """Sugar to generate a <this relation>-relation-broken event."""
         return Event(
-            name=normalize_name(self.endpoint + "-relation-broken"),
+            path=normalize_name(self.endpoint + "-relation-broken"),
             relation=self,
         )
 
 
 def unify_ids_and_remote_units_data(ids: List[int], data: Dict[int, Any]):
     """Unify and validate a list of unit IDs and a mapping from said ids to databag contents.
 
@@ -624,15 +631,15 @@
     def pebble_ready_event(self):
         """Sugar to generate a <this container's name>-pebble-ready event."""
         if not self.can_connect:
             logger.warning(
                 "you **can** fire pebble-ready while the container cannot connect, "
                 "but that's most likely not what you want.",
             )
-        return Event(name=normalize_name(self.name + "-pebble-ready"), container=self)
+        return Event(path=normalize_name(self.name + "-pebble-ready"), container=self)
 
 
 @dataclasses.dataclass(frozen=True)
 class Address(_DCBase):
     hostname: str
     value: str
     cidr: str
@@ -735,71 +742,14 @@
 
 def _status_to_entitystatus(obj: StatusBase) -> _EntityStatus:
     """Convert StatusBase to _EntityStatus."""
     return _EntityStatus(obj.name, obj.message)
 
 
 @dataclasses.dataclass(frozen=True)
-class Status(_DCBase):
-    """Represents the 'juju statuses' of the application/unit being tested."""
-
-    # the current statuses. Will be cast to _EntitiyStatus in __post_init__
-    app: Union[StatusBase, _EntityStatus] = _EntityStatus("unknown")
-    unit: Union[StatusBase, _EntityStatus] = _EntityStatus("unknown")
-    workload_version: str = ""
-
-    # most to least recent statuses; do NOT include the current one.
-    app_history: List[_EntityStatus] = dataclasses.field(default_factory=list)
-    unit_history: List[_EntityStatus] = dataclasses.field(default_factory=list)
-    previous_workload_version: Optional[str] = None
-
-    def __post_init__(self):
-        for name in ["app", "unit"]:
-            val = getattr(self, name)
-            if isinstance(val, _EntityStatus):
-                pass
-            elif isinstance(val, StatusBase):
-                object.__setattr__(self, name, _status_to_entitystatus(val))
-            elif isinstance(val, tuple):
-                logger.warning(
-                    "Initializing Status.[app/unit] with Tuple[str, str] is deprecated "
-                    "and will be removed soon. \n"
-                    f"Please pass a StatusBase instance: `StatusBase(*{val})`",
-                )
-                object.__setattr__(self, name, _EntityStatus(*val))
-            else:
-                raise TypeError(f"Invalid status.{name}: {val!r}")
-
-    def _update_workload_version(self, new_workload_version: str):
-        """Update the current app version and record the previous one."""
-        # We don't keep a full history because we don't expect the app version to change more
-        # than once per hook.
-
-        # bypass frozen dataclass
-        object.__setattr__(self, "previous_workload_version", self.workload_version)
-        object.__setattr__(self, "workload_version", new_workload_version)
-
-    def _update_status(
-        self,
-        new_status: str,
-        new_message: str = "",
-        is_app: bool = False,
-    ):
-        """Update the current app/unit status and add the previous one to the history."""
-        if is_app:
-            self.app_history.append(self.app)
-            # bypass frozen dataclass
-            object.__setattr__(self, "app", _EntityStatus(new_status, new_message))
-        else:
-            self.unit_history.append(self.unit)
-            # bypass frozen dataclass
-            object.__setattr__(self, "unit", _EntityStatus(new_status, new_message))
-
-
-@dataclasses.dataclass(frozen=True)
 class StoredState(_DCBase):
     # /-separated Object names. E.g. MyCharm/MyCharmLib.
     # if None, this StoredState instance is owned by the Framework.
     owner_path: Optional[str]
 
     name: str = "_stored"
     content: Dict[str, Any] = dataclasses.field(default_factory=dict)
@@ -822,30 +772,61 @@
 
     config: Dict[str, Union[str, int, float, bool]] = dataclasses.field(
         default_factory=dict,
     )
     relations: List["AnyRelation"] = dataclasses.field(default_factory=list)
     networks: List[Network] = dataclasses.field(default_factory=list)
     containers: List[Container] = dataclasses.field(default_factory=list)
-    status: Status = dataclasses.field(default_factory=Status)
     leader: bool = False
     model: Model = Model()
-    juju_log: List[Tuple[str, str]] = dataclasses.field(default_factory=list)
     secrets: List[Secret] = dataclasses.field(default_factory=list)
 
     unit_id: int = 0
     # represents the OF's event queue. These events will be emitted before the event being
     # dispatched, and represent the events that had been deferred during the previous run.
     # If the charm defers any events during "this execution", they will be appended
     # to this list.
     deferred: List["DeferredEvent"] = dataclasses.field(default_factory=list)
-    stored_state: List["StoredState"] = dataclasses.field(default_factory=dict)
+    stored_state: List["StoredState"] = dataclasses.field(default_factory=list)
+
+    """Represents the 'juju statuses' of the application/unit being tested."""
+
+    # the current statuses. Will be cast to _EntitiyStatus in __post_init__
+    app_status: Union[StatusBase, _EntityStatus] = _EntityStatus("unknown")
+    unit_status: Union[StatusBase, _EntityStatus] = _EntityStatus("unknown")
+    workload_version: str = ""
+
+    def __post_init__(self):
+        for name in ["app_status", "unit_status"]:
+            val = getattr(self, name)
+            if isinstance(val, _EntityStatus):
+                pass
+            elif isinstance(val, StatusBase):
+                object.__setattr__(self, name, _status_to_entitystatus(val))
+            else:
+                raise TypeError(f"Invalid status.{name}: {val!r}")
+
+    def _update_workload_version(self, new_workload_version: str):
+        """Update the current app version and record the previous one."""
+        # We don't keep a full history because we don't expect the app version to change more
+        # than once per hook.
 
-    # todo:
-    #  actions?
+        # bypass frozen dataclass
+        object.__setattr__(self, "workload_version", new_workload_version)
+
+    def _update_status(
+        self,
+        new_status: str,
+        new_message: str = "",
+        is_app: bool = False,
+    ):
+        """Update the current app/unit status and add the previous one to the history."""
+        name = "app_status" if is_app else "unit_status"
+        # bypass frozen dataclass
+        object.__setattr__(self, name, _EntityStatus(new_status, new_message))
 
     def with_can_connect(self, container_name: str, can_connect: bool) -> "State":
         def replacer(container: Container):
             if container.name == container_name:
                 return container.replace(can_connect=can_connect)
             return container
 
@@ -854,15 +835,15 @@
 
     def with_leadership(self, leader: bool) -> "State":
         return self.replace(leader=leader)
 
     def with_unit_status(self, status: StatusBase) -> "State":
         return self.replace(
             status=dataclasses.replace(
-                self.status,
+                self.unit_status,
                 unit=_status_to_entitystatus(status),
             ),
         )
 
     def get_container(self, container: Union[str, Container]) -> Container:
         """Get container from this State, based on an input container or its name."""
         name = container.name if isinstance(container, Container) else container
@@ -952,58 +933,82 @@
     @property
     def name(self):
         return self.handle_path.split("/")[-1].split("[")[0]
 
 
 @dataclasses.dataclass(frozen=True)
 class Event(_DCBase):
-    name: str
+    path: str
     args: Tuple[Any] = ()
     kwargs: Dict[str, Any] = dataclasses.field(default_factory=dict)
 
     # if this is a relation event, the relation it refers to
     relation: Optional["AnyRelation"] = None
     # and the name of the remote unit this relation event is about
     relation_remote_unit_id: Optional[int] = None
 
     # if this is a secret event, the secret it refers to
     secret: Optional[Secret] = None
 
     # if this is a workload (container) event, the container it refers to
     container: Optional[Container] = None
 
+    # if this is an action event, the Action instance
+    action: Optional["Action"] = None
+
     # todo add other meta for
     #  - secret events
     #  - pebble?
     #  - action?
 
+    _owner_path: List[str] = dataclasses.field(default_factory=list)
+
     def __call__(self, remote_unit_id: Optional[int] = None) -> "Event":
         if remote_unit_id and not self._is_relation_event:
             raise ValueError(
                 "cannot pass param `remote_unit_id` to a "
                 "non-relation event constructor.",
             )
         return self.replace(relation_remote_unit_id=remote_unit_id)
 
     def __post_init__(self):
-        if "-" in self.name:
-            logger.warning(f"Only use underscores in event names. {self.name!r}")
+        if "-" in self.path:
+            logger.warning(f"Only use underscores in event paths. {self.path!r}")
 
+        path = normalize_name(self.path)
         # bypass frozen dataclass
-        object.__setattr__(self, "name", normalize_name(self.name))
+        object.__setattr__(self, "path", path)
+
+    @property
+    def name(self) -> str:
+        """Event name."""
+        return self.path.split(".")[-1]
+
+    @property
+    def owner_path(self) -> List[str]:
+        """Path to the ObjectEvents instance owning this event.
+
+        If this event is defined on the toplevel charm class, it should be ['on'].
+        """
+        return self.path.split(".")[:-1] or ["on"]
 
     @property
     def _is_relation_event(self) -> bool:
         """Whether the event name indicates that this is a relation event."""
         return any(self.name.endswith(suffix) for suffix in RELATION_EVENTS_SUFFIX)
 
     @property
+    def _is_action_event(self) -> bool:
+        """Whether the event name indicates that this is a relation event."""
+        return self.name.endswith(ACTION_EVENT_SUFFIX)
+
+    @property
     def _is_secret_event(self) -> bool:
         """Whether the event name indicates that this is a secret event."""
-        return any(self.name.endswith(suffix) for suffix in SECRET_EVENTS_SUFFIX)
+        return self.name in SECRET_EVENTS
 
     @property
     def _is_storage_event(self) -> bool:
         """Whether the event name indicates that this is a storage event."""
         return any(self.name.endswith(suffix) for suffix in STORAGE_EVENTS_SUFFIX)
 
     @property
@@ -1033,32 +1038,29 @@
         builtins = []
         for relation_name in chain(
             charm_spec.meta.get("requires", ()),
             charm_spec.meta.get("provides", ()),
             charm_spec.meta.get("peers", ()),
         ):
             relation_name = relation_name.replace("-", "_")
-            builtins.append(relation_name + "_relation_created")
-            builtins.append(relation_name + "_relation_joined")
-            builtins.append(relation_name + "_relation_changed")
-            builtins.append(relation_name + "_relation_departed")
-            builtins.append(relation_name + "_relation_broken")
+            for relation_evt_suffix in RELATION_EVENTS_SUFFIX:
+                builtins.append(relation_name + relation_evt_suffix)
 
         for storage_name in charm_spec.meta.get("storages", ()):
             storage_name = storage_name.replace("-", "_")
-            builtins.append(storage_name + "_storage_attached")
-            builtins.append(storage_name + "_storage_detaching")
+            for storage_evt_suffix in STORAGE_EVENTS_SUFFIX:
+                builtins.append(storage_name + storage_evt_suffix)
 
         for action_name in charm_spec.actions or ():
             action_name = action_name.replace("-", "_")
-            builtins.append(action_name + "_action")
+            builtins.append(action_name + ACTION_EVENT_SUFFIX)
 
         for container_name in charm_spec.meta.get("containers", ()):
             container_name = container_name.replace("-", "_")
-            builtins.append(container_name + "_pebble_ready")
+            builtins.append(container_name + PEBBLE_READY_EVENT_SUFFIX)
 
         return event_name in builtins
 
     def deferred(self, handler: Callable, event_id: int = 1) -> DeferredEvent:
         """Construct a DeferredEvent from this Event."""
         handler_repr = repr(handler)
         handler_re = re.compile(r"<function (.*) at .*>")
@@ -1078,18 +1080,14 @@
         if self._is_workload_event:
             # this is a WorkloadEvent. The snapshot:
             snapshot_data = {
                 "container_name": self.container.name,
             }
 
         elif self._is_relation_event:
-            if not self.relation:
-                raise ValueError(
-                    "this is a relation event; expected relation attribute",
-                )
             # this is a RelationEvent. The snapshot:
             snapshot_data = {
                 "relation_name": self.relation.endpoint,
                 "relation_id": self.relation.relation_id,
                 "app_name": self.relation.remote_app_name,
                 "unit_name": f"{self.relation.remote_app_name}/{self.relation_remote_unit_id}",
             }
@@ -1098,14 +1096,26 @@
             handle_path,
             owner_name,
             handler_name,
             snapshot_data=snapshot_data,
         )
 
 
+@dataclasses.dataclass(frozen=True)
+class Action(_DCBase):
+    name: str
+
+    params: Dict[str, "AnyJson"] = dataclasses.field(default_factory=dict)
+
+    @property
+    def event(self) -> Event:
+        """Helper to generate an action event from this action."""
+        return Event(self.name + ACTION_EVENT_SUFFIX, action=self)
+
+
 def deferred(
     event: Union[str, Event],
     handler: Callable,
     event_id: int = 1,
     relation: "Relation" = None,
     container: "Container" = None,
 ):
```

### Comparing `ops-scenario-3.1/tests/test_consistency_checker.py` & `ops-scenario-4.0/tests/test_consistency_checker.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,14 +1,15 @@
 import pytest
 from ops.charm import CharmBase
 
 from scenario.consistency_checker import check_consistency
 from scenario.runtime import InconsistentScenarioError
 from scenario.state import (
     RELATION_EVENTS_SUFFIX,
+    Action,
     Container,
     Event,
     PeerRelation,
     Relation,
     Secret,
     State,
     SubordinateRelation,
@@ -219,7 +220,42 @@
 def test_container_pebble_evt_consistent():
     container = Container("foo-bar-baz")
     assert_consistent(
         State(containers=[container]),
         container.pebble_ready_event,
         _CharmSpec(MyCharm, {"containers": {"foo-bar-baz": {}}}),
     )
+
+
+def test_action_name():
+    action = Action("foo", params={"bar": "baz"})
+
+    assert_consistent(
+        State(),
+        action.event,
+        _CharmSpec(
+            MyCharm, meta={}, actions={"foo": {"params": {"bar": {"type": "string"}}}}
+        ),
+    )
+    assert_inconsistent(
+        State(),
+        Event("box_action", action=action),
+        _CharmSpec(MyCharm, meta={}, actions={"foo": {}}),
+    )
+
+
+def test_action_params_type():
+    action = Action("foo", params={"bar": "baz"})
+    assert_consistent(
+        State(),
+        action.event,
+        _CharmSpec(
+            MyCharm, meta={}, actions={"foo": {"params": {"bar": {"type": "string"}}}}
+        ),
+    )
+    assert_inconsistent(
+        State(),
+        action.event,
+        _CharmSpec(
+            MyCharm, meta={}, actions={"foo": {"params": {"bar": {"type": "boolean"}}}}
+        ),
+    )
```

### Comparing `ops-scenario-3.1/tests/test_e2e/test_builtin_scenes.py` & `ops-scenario-4.0/tests/test_e2e/test_builtin_scenes.py`

 * *Files identical despite different names*

### Comparing `ops-scenario-3.1/tests/test_e2e/test_config.py` & `ops-scenario-4.0/tests/test_e2e/test_config.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 import pytest
 from ops.charm import CharmBase
 from ops.framework import Framework
 
-from scenario import trigger
 from scenario.state import Event, Network, Relation, State, _CharmSpec
+from tests.helpers import trigger
 
 
 @pytest.fixture(scope="function")
 def mycharm():
     class MyCharm(CharmBase):
         def __init__(self, framework: Framework):
             super().__init__(framework)
```

### Comparing `ops-scenario-3.1/tests/test_e2e/test_deferred.py` & `ops-scenario-4.0/tests/test_e2e/test_deferred.py`

 * *Files 2% similar despite different names*

```diff
@@ -6,16 +6,16 @@
     RelationChangedEvent,
     StartEvent,
     UpdateStatusEvent,
     WorkloadEvent,
 )
 from ops.framework import Framework
 
-from scenario import trigger
 from scenario.state import Container, DeferredEvent, Relation, State, deferred
+from tests.helpers import trigger
 
 CHARM_CALLED = 0
 
 
 @pytest.fixture(scope="function")
 def mycharm():
     class MyCharm(CharmBase):
@@ -67,15 +67,15 @@
     assert len(mycharm.captured) == 2
     upstat, start = mycharm.captured
     assert isinstance(upstat, UpdateStatusEvent)
     assert isinstance(start, StartEvent)
 
 
 def test_deferred_relation_event_without_relation_raises(mycharm):
-    with pytest.raises(ValueError):
+    with pytest.raises(AttributeError):
         deferred(event="foo_relation_changed", handler=mycharm._on_event)
 
 
 def test_deferred_relation_evt(mycharm):
     rel = Relation(endpoint="foo", remote_app_name="remote")
     evt1 = rel.changed_event.deferred(handler=mycharm._on_event)
     evt2 = deferred(
```

### Comparing `ops-scenario-3.1/tests/test_e2e/test_juju_log.py` & `ops-scenario-4.0/tests/test_e2e/test_juju_log.py`

 * *Files 21% similar despite different names*

```diff
@@ -1,14 +1,15 @@
 import logging
 
 import pytest
 from ops.charm import CharmBase
 
-from scenario import trigger
-from scenario.state import State
+from scenario import Context
+from scenario.state import JujuLogLine, State
+from tests.helpers import trigger
 
 logger = logging.getLogger("testing logger")
 
 
 @pytest.fixture(scope="function")
 def mycharm():
     class MyCharm(CharmBase):
@@ -23,11 +24,14 @@
             print("foo!")
             logger.warning("bar!")
 
     return MyCharm
 
 
 def test_juju_log(mycharm):
-    out = trigger(State(), "start", mycharm, meta=mycharm.META)
-    assert out.juju_log[16] == ("DEBUG", "Emitting Juju event start.")
+    ctx = Context(mycharm, meta=mycharm.META)
+    ctx.run("start", State())
+    assert ctx.juju_log[-2] == JujuLogLine(
+        level="DEBUG", message="Emitting Juju event start."
+    )
+    assert ctx.juju_log[-1] == JujuLogLine(level="WARNING", message="bar!")
     # prints are not juju-logged.
-    assert out.juju_log[17] == ("WARNING", "bar!")
```

### Comparing `ops-scenario-3.1/tests/test_e2e/test_network.py` & `ops-scenario-4.0/tests/test_e2e/test_network.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 import pytest
 from ops.charm import CharmBase
 from ops.framework import Framework
 
-from scenario import trigger
 from scenario.state import Event, Network, Relation, State, _CharmSpec
+from tests.helpers import trigger
 
 
 @pytest.fixture(scope="function")
 def mycharm():
     class MyCharm(CharmBase):
         _call = None
         called = False
```

### Comparing `ops-scenario-3.1/tests/test_e2e/test_observers.py` & `ops-scenario-4.0/tests/test_e2e/test_observers.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 import pytest
 from ops.charm import ActionEvent, CharmBase, StartEvent
 from ops.framework import Framework
 
-from scenario import trigger
 from scenario.state import Event, State, _CharmSpec
+from tests.helpers import trigger
 
 
 @pytest.fixture(scope="function")
 def charm_evts():
     events = []
 
     class MyCharm(CharmBase):
```

### Comparing `ops-scenario-3.1/tests/test_e2e/test_pebble.py` & `ops-scenario-4.0/tests/test_e2e/test_pebble.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,19 +1,18 @@
 import tempfile
 from pathlib import Path
 
 import pytest
-import yaml
 from ops import pebble
 from ops.charm import CharmBase
 from ops.framework import Framework
 from ops.pebble import ServiceStartup, ServiceStatus
 
-from scenario import trigger
 from scenario.state import Container, ExecOutput, Mount, State
+from tests.helpers import trigger
 
 
 @pytest.fixture(scope="function")
 def charm_cls():
     class MyCharm(CharmBase):
         def __init__(self, framework: Framework):
             super().__init__(framework)
@@ -132,15 +131,15 @@
     )
 
     if make_dirs:
         file = out.get_container("foo").filesystem.open("/foo/bar/baz.txt")
         assert file.read() == text
     else:
         # nothing has changed
-        out_purged = out.replace(juju_log=[], stored_state=state.stored_state)
+        out_purged = out.replace(stored_state=state.stored_state)
         assert not out_purged.jsonpatch_delta(state)
 
 
 LS = """
 .rw-rw-r--  228 ubuntu ubuntu 18 jan 12:05 -- charmcraft.yaml    
 .rw-rw-r--  497 ubuntu ubuntu 18 jan 12:05 -- config.yaml        
 .rw-rw-r--  900 ubuntu ubuntu 18 jan 12:05 -- CONTRIBUTING.md
```

### Comparing `ops-scenario-3.1/tests/test_e2e/test_play_assertions.py` & `ops-scenario-4.0/tests/test_e2e/test_play_assertions.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 import pytest
 from ops.charm import CharmBase
 from ops.framework import Framework
 from ops.model import ActiveStatus, BlockedStatus
 
-from scenario import trigger
-from scenario.state import Event, Relation, State, Status, _CharmSpec
+from scenario.state import Relation, State
+from tests.helpers import trigger
 
 
 @pytest.fixture(scope="function")
 def mycharm():
     class MyCharm(CharmBase):
         _call = None
         called = False
@@ -41,46 +41,41 @@
         post_event._called = True
         assert charm.unit.status == ActiveStatus("yabadoodle")
         assert charm.called
 
     mycharm._call = call
 
     initial_state = State(
-        config={"foo": "bar"}, leader=True, status=Status(unit=BlockedStatus("foo"))
+        config={"foo": "bar"}, leader=True, unit_status=BlockedStatus("foo")
     )
 
     out = trigger(
         initial_state,
         charm_type=mycharm,
         meta={"name": "foo"},
         config={"options": {"foo": {"type": "string"}}},
         event="start",
         post_event=post_event,
         pre_event=pre_event,
     )
 
-    assert out.status.unit == ActiveStatus("yabadoodle")
+    assert out.unit_status == ActiveStatus("yabadoodle")
 
-    out_purged = out.replace(juju_log=[], stored_state=initial_state.stored_state)
+    out_purged = out.replace(stored_state=initial_state.stored_state)
     assert out_purged.jsonpatch_delta(initial_state) == [
         {
             "op": "replace",
-            "path": "/status/unit/message",
+            "path": "/unit_status/message",
             "value": "yabadoodle",
         },
         {
             "op": "replace",
-            "path": "/status/unit/name",
+            "path": "/unit_status/name",
             "value": "active",
         },
-        {
-            "op": "add",
-            "path": "/status/unit_history/0",
-            "value": {"message": "foo", "name": "blocked"},
-        },
     ]
 
 
 def test_relation_data_access(mycharm):
     mycharm._call = lambda *_: True
 
     def check_relation_data(charm):
```

### Comparing `ops-scenario-3.1/tests/test_e2e/test_relations.py` & `ops-scenario-4.0/tests/test_e2e/test_relations.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,22 +1,22 @@
 from typing import Type
 
 import pytest
 from ops.charm import CharmBase, CharmEvents, RelationDepartedEvent
 from ops.framework import EventBase, Framework
 
-from scenario import trigger
 from scenario.state import (
     PeerRelation,
     Relation,
     RelationBase,
     State,
     StateValidationError,
     SubordinateRelation,
 )
+from tests.helpers import trigger
 
 
 @pytest.fixture(scope="function")
 def mycharm():
     class MyCharmEvents(CharmEvents):
         @classmethod
         def define_event(cls, event_kind: str, event_type: "Type[EventBase]"):
```

### Comparing `ops-scenario-3.1/tests/test_e2e/test_rubbish_events.py` & `ops-scenario-4.0/tests/test_e2e/test_rubbish_events.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,16 +1,16 @@
 import os
 
 import pytest
 from ops.charm import CharmBase, CharmEvents
 from ops.framework import EventBase, EventSource, Framework, Object
 
-from scenario import trigger
 from scenario.ops_main_mock import NoObserverError
 from scenario.state import Container, Event, State, _CharmSpec
+from tests.helpers import trigger
 
 
 class QuxEvent(EventBase):
     pass
 
 
 class SubEvent(EventBase):
```

### Comparing `ops-scenario-3.1/tests/test_e2e/test_secrets.py` & `ops-scenario-4.0/tests/test_e2e/test_secrets.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 import pytest
 from ops.charm import CharmBase
 from ops.framework import Framework
 from ops.model import SecretRotate
 
-from scenario import trigger
 from scenario.state import Relation, Secret, State
+from tests.helpers import trigger
 
 
 @pytest.fixture(scope="function")
 def mycharm():
     class MyCharm(CharmBase):
         def __init__(self, framework: Framework):
             super().__init__(framework)
```

### Comparing `ops-scenario-3.1/tests/test_e2e/test_state.py` & `ops-scenario-4.0/tests/test_e2e/test_state.py`

 * *Files 4% similar despite different names*

```diff
@@ -2,16 +2,16 @@
 from typing import Type
 
 import pytest
 from ops.charm import CharmBase, CharmEvents
 from ops.framework import EventBase, Framework
 from ops.model import ActiveStatus, UnknownStatus, WaitingStatus
 
-from scenario import trigger
 from scenario.state import Container, Relation, State, sort_patch
+from tests.helpers import trigger
 
 CUSTOM_EVT_SUFFIXES = {
     "relation_created",
     "relation_joined",
     "relation_changed",
     "relation_departed",
     "relation_broken",
@@ -52,15 +52,15 @@
 @pytest.fixture
 def state():
     return State(config={"foo": "bar"}, leader=True)
 
 
 def test_bare_event(state, mycharm):
     out = trigger(state, "start", mycharm, meta={"name": "foo"})
-    out_purged = out.replace(juju_log=[], stored_state=state.stored_state)
+    out_purged = out.replace(stored_state=state.stored_state)
     assert state.jsonpatch_delta(out_purged) == []
 
 
 def test_leader_get(state, mycharm):
     def pre_event(charm):
         assert charm.unit.is_leader()
 
@@ -83,36 +83,26 @@
     out = trigger(
         state,
         "start",
         mycharm,
         meta={"name": "foo"},
         config={"options": {"foo": {"type": "string"}}},
     )
-    assert out.status.unit == ActiveStatus("foo test")
-    assert out.status.app == WaitingStatus("foo barz")
-    assert out.status.workload_version == ""
+    assert out.unit_status == ActiveStatus("foo test")
+    assert out.app_status == WaitingStatus("foo barz")
+    assert out.workload_version == ""
 
-    # ignore logging output and stored state in the delta
-    out_purged = out.replace(juju_log=[], stored_state=state.stored_state)
+    # ignore stored state in the delta
+    out_purged = out.replace(stored_state=state.stored_state)
     assert out_purged.jsonpatch_delta(state) == sort_patch(
         [
-            {"op": "replace", "path": "/status/app/message", "value": "foo barz"},
-            {"op": "replace", "path": "/status/app/name", "value": "waiting"},
-            {
-                "op": "add",
-                "path": "/status/app_history/0",
-                "value": {"message": "", "name": "unknown"},
-            },
-            {"op": "replace", "path": "/status/unit/message", "value": "foo test"},
-            {"op": "replace", "path": "/status/unit/name", "value": "active"},
-            {
-                "op": "add",
-                "path": "/status/unit_history/0",
-                "value": {"message": "", "name": "unknown"},
-            },
+            {"op": "replace", "path": "/app_status/message", "value": "foo barz"},
+            {"op": "replace", "path": "/app_status/name", "value": "waiting"},
+            {"op": "replace", "path": "/unit_status/message", "value": "foo test"},
+            {"op": "replace", "path": "/unit_status/name", "value": "active"},
         ]
     )
 
 
 @pytest.mark.parametrize("connect", (True, False))
 def test_container(connect, mycharm):
     def pre_event(charm: CharmBase):
```

### Comparing `ops-scenario-3.1/tests/test_e2e/test_status.py` & `ops-scenario-4.0/tests/test_e2e/test_status.py`

 * *Files 11% similar despite different names*

```diff
@@ -1,14 +1,15 @@
 import pytest
 from ops.charm import CharmBase
 from ops.framework import Framework
 from ops.model import ActiveStatus, BlockedStatus, UnknownStatus, WaitingStatus
 
-from scenario import trigger
-from scenario.state import State, Status
+from scenario import Context
+from scenario.state import State
+from tests.helpers import trigger
 
 
 @pytest.fixture(scope="function")
 def mycharm():
     class MyCharm(CharmBase):
         def __init__(self, framework: Framework):
             super().__init__(framework)
@@ -29,61 +30,91 @@
         State(leader=True),
         "update_status",
         mycharm,
         meta={"name": "local"},
         post_event=post_event,
     )
 
-    assert out.status.unit == UnknownStatus()
+    assert out.unit_status == UnknownStatus()
 
 
 def test_status_history(mycharm):
     def post_event(charm: CharmBase):
         for obj in [charm.unit, charm.app]:
             obj.status = ActiveStatus("1")
             obj.status = BlockedStatus("2")
             obj.status = WaitingStatus("3")
 
-    out = trigger(
-        State(leader=True),
-        "update_status",
+    ctx = Context(
         mycharm,
         meta={"name": "local"},
+    )
+
+    out = ctx.run(
+        "update_status",
+        State(leader=True),
         post_event=post_event,
     )
 
-    assert out.status.unit == WaitingStatus("3")
-    assert out.status.unit_history == [
+    assert out.unit_status == WaitingStatus("3")
+    assert ctx.unit_status_history == [
         UnknownStatus(),
         ActiveStatus("1"),
         BlockedStatus("2"),
     ]
 
-    assert out.status.app == WaitingStatus("3")
-    assert out.status.app_history == [
+    assert out.app_status == WaitingStatus("3")
+    assert ctx.app_status_history == [
         UnknownStatus(),
         ActiveStatus("1"),
         BlockedStatus("2"),
     ]
 
 
 def test_status_history_preservation(mycharm):
     def post_event(charm: CharmBase):
         for obj in [charm.unit, charm.app]:
             obj.status = WaitingStatus("3")
 
-    out = trigger(
+    ctx = Context(
+        mycharm,
+        meta={"name": "local"},
+    )
+
+    out = ctx.run(
+        "update_status",
         State(
             leader=True,
-            status=Status(unit=ActiveStatus("foo"), app=ActiveStatus("bar")),
+            unit_status=ActiveStatus("foo"),
+            app_status=ActiveStatus("bar"),
         ),
-        "update_status",
+        post_event=post_event,
+    )
+
+    assert out.unit_status == WaitingStatus("3")
+    assert ctx.unit_status_history == [ActiveStatus("foo")]
+
+    assert out.app_status == WaitingStatus("3")
+    assert ctx.app_status_history == [ActiveStatus("bar")]
+
+
+def test_workload_history(mycharm):
+    def post_event(charm: CharmBase):
+        charm.unit.set_workload_version("1")
+        charm.unit.set_workload_version("1.1")
+        charm.unit.set_workload_version("1.2")
+
+    ctx = Context(
         mycharm,
         meta={"name": "local"},
-        post_event=post_event,
     )
 
-    assert out.status.unit == WaitingStatus("3")
-    assert out.status.unit_history == [ActiveStatus("foo")]
+    out = ctx.run(
+        "update_status",
+        State(
+            leader=True,
+        ),
+        post_event=post_event,
+    )
 
-    assert out.status.app == WaitingStatus("3")
-    assert out.status.app_history == [ActiveStatus("bar")]
+    assert ctx.workload_version_history == ["1", "1.1"]
+    assert out.workload_version == "1.2"
```

### Comparing `ops-scenario-3.1/tests/test_e2e/test_stored_state.py` & `ops-scenario-4.0/tests/test_e2e/test_stored_state.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 import pytest
 from ops.charm import CharmBase
 from ops.framework import Framework
 from ops.framework import StoredState as ops_storedstate
 
-from scenario import trigger
 from scenario.state import State, StoredState
+from tests.helpers import trigger
 
 
 @pytest.fixture(scope="function")
 def mycharm():
     class MyCharm(CharmBase):
         META = {"name": "mycharm"}
```

### Comparing `ops-scenario-3.1/tests/test_e2e/test_vroot.py` & `ops-scenario-4.0/tests/test_e2e/test_vroot.py`

 * *Files 10% similar despite different names*

```diff
@@ -3,15 +3,16 @@
 
 import pytest
 from ops.charm import CharmBase
 from ops.framework import Framework
 from ops.model import ActiveStatus
 
 from scenario import State
-from scenario.runtime import DirtyVirtualCharmRootError, trigger
+from scenario.runtime import DirtyVirtualCharmRootError
+from tests.helpers import trigger
 
 
 class MyCharm(CharmBase):
     META = {"name": "my-charm"}
 
     def __init__(self, framework: Framework):
         super().__init__(framework)
@@ -38,15 +39,15 @@
             State(),
             "start",
             charm_type=MyCharm,
             meta=MyCharm.META,
             charm_root=t,
         )
 
-    assert out.status.unit == ("active", "hello world")
+    assert out.unit_status == ("active", "hello world")
 
 
 @pytest.mark.parametrize("meta_overwrite", ["metadata", "actions", "config"])
 def test_dirty_vroot_raises(meta_overwrite):
     with tempfile.TemporaryDirectory() as myvroot:
         t = Path(myvroot)
         meta_file = t / f"{meta_overwrite}.yaml"
```

### Comparing `ops-scenario-3.1/tests/test_emitted_events_util.py` & `ops-scenario-4.0/tests/test_emitted_events_util.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,12 +1,14 @@
 import pytest
 from ops.charm import CharmBase, CharmEvents, StartEvent
 from ops.framework import CommitEvent, EventBase, EventSource, PreCommitEvent
 
-from scenario import Event, State, capture_events, trigger
+from scenario import Event, State
+from scenario.capture_events import capture_events
+from tests.helpers import trigger
 
 
 class Foo(EventBase):
     pass
 
 
 class MyCharmEvents(CharmEvents):
```

### Comparing `ops-scenario-3.1/tests/test_plugin.py` & `ops-scenario-4.0/tests/test_plugin.py`

 * *Files 25% similar despite different names*

```diff
@@ -1,42 +1,14 @@
 import sys
 
 pytest_plugins = "pytester"
 sys.path.append(".")
 
 
-def test_emitted_events_fixture(pytester):
-    """Make sure that pytest accepts our fixture."""
-
-    # create a temporary pytest test module
-    pytester.makepyfile(
-        """
-        from scenario import State
-        def test_sth(emitted_events):
-            assert emitted_events == []
-    """
-    )
-
-    # run pytest with the following cmd args
-    result = pytester.runpytest("-v")
-
-    # fnmatch_lines does an assertion internally
-    result.stdout.fnmatch_lines(
-        [
-            "*::test_sth PASSED*",
-        ]
-    )
-
-    # make sure that we get a '0' exit code for the testsuite
-    assert result.ret == 0
-
-
 def test_context(pytester):
-    """Make sure that pytest accepts our fixture."""
-
     # create a temporary pytest test module
     pytester.makepyfile(
         """
         import pytest
         from scenario import State
         from scenario import Context
         import ops
```

### Comparing `ops-scenario-3.1/tests/test_runtime.py` & `ops-scenario-4.0/tests/test_runtime.py`

 * *Files 9% similar despite different names*

```diff
@@ -3,14 +3,15 @@
 from unittest.mock import MagicMock
 
 import pytest
 import yaml
 from ops.charm import CharmBase, CharmEvents
 from ops.framework import EventBase
 
+from scenario import Context
 from scenario.runtime import Runtime
 from scenario.state import Event, State, _CharmSpec
 
 
 def charm_type():
     class _CharmEvents(CharmEvents):
         pass
@@ -36,28 +37,30 @@
             "name": "foo",
             "requires": {"ingress-per-unit": {"interface": "ingress_per_unit"}},
         }
         temppath = Path(tempdir)
         meta_file = temppath / "metadata.yaml"
         meta_file.write_text(yaml.safe_dump(meta))
 
+        my_charm_type = charm_type()
         runtime = Runtime(
             _CharmSpec(
-                charm_type(),
+                my_charm_type,
                 meta=meta,
             ),
         )
 
         pre_event = MagicMock(return_value=None)
         post_event = MagicMock(return_value=None)
         runtime.exec(
             state=State(),
             event=Event("update_status"),
             pre_event=pre_event,
             post_event=post_event,
+            context=Context(my_charm_type, meta=meta),
         )
 
         assert pre_event.called
         assert post_event.called
 
 
 def test_event_emission():
@@ -77,15 +80,17 @@
         runtime = Runtime(
             _CharmSpec(
                 my_charm_type,
                 meta=meta,
             ),
         )
 
-        runtime.exec(state=State(), event=Event("bar"))
+        runtime.exec(
+            state=State(), event=Event("bar"), context=Context(my_charm_type, meta=meta)
+        )
 
         assert my_charm_type._event
         assert isinstance(my_charm_type._event, MyEvt)
 
 
 @pytest.mark.parametrize("app_name", ("foo", "bar-baz", "QuX2"))
 @pytest.mark.parametrize("unit_id", (1, 2, 42))
@@ -103,9 +108,12 @@
         ),
     )
 
     def post_event(charm: CharmBase):
         assert charm.unit.name == f"{app_name}/{unit_id}"
 
     runtime.exec(
-        state=State(unit_id=unit_id), event=Event("start"), post_event=post_event
+        state=State(unit_id=unit_id),
+        event=Event("start"),
+        post_event=post_event,
+        context=Context(my_charm_type, meta=meta),
     )
```

### Comparing `ops-scenario-3.1/tox.ini` & `ops-scenario-4.0/tox.ini`

 * *Files 24% similar despite different names*

```diff
@@ -2,45 +2,47 @@
 requires =
     tox>=4.2
 env_list =
     py311
     py38
     py37
     py36
-    unit
     lint
     lint-tests
 skip_missing_interpreters = true
 
 [vars]
 src_path = {toxinidir}/scenario
 tst_path = {toxinidir}/tests
 all_path = {[vars]src_path}, {[vars]tst_path}
 
-[testenv:lint]
-description = Format the code base to adhere to our styles, and complain about what we cannot do automatically.
-skip_install = true
-deps =
-    pre-commit>=3.2.2
-commands =
-    pre-commit run --all-files {posargs}
-    python -c 'print(r"hint: run {envbindir}{/}pre-commit install to add checks as pre-commit hook")'
-
-[testenv:unit]
+[testenv]
+# don't install as a sdist, instead, install as wheel (create wheel once), then install in all envs
+package = wheel
+wheel_build_env = .pkg
 description = unit tests
 deps =
     coverage[toml]
     jsonpatch
     pytest
 commands =
     coverage run \
       --source={[vars]src_path} \
       -m pytest -v --tb native --log-cli-level=INFO -s {posargs} {[vars]tst_path}
     coverage report
 
+[testenv:lint]
+description = Format the code base to adhere to our styles, and complain about what we cannot do automatically.
+skip_install = true
+deps =
+    pre-commit>=3.2.2
+commands =
+    pre-commit run --all-files {posargs}
+    python -c 'print(r"hint: run {envbindir}{/}pre-commit install to add checks as pre-commit hook")'
+
 [testenv:lint-tests]
 description = Lint test files.
 skip_install = true
 deps =
     black
     coverage[toml]
     isort
```


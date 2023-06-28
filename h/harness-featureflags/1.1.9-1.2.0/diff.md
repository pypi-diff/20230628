# Comparing `tmp/harness-featureflags-1.1.9.tar.gz` & `tmp/harness-featureflags-1.2.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "harness-featureflags-1.1.9.tar", last modified: Tue Feb 21 15:02:49 2023, max compression
+gzip compressed data, was "harness-featureflags-1.2.0.tar", last modified: Wed Jun 28 14:43:04 2023, max compression
```

## Comparing `harness-featureflags-1.1.9.tar` & `harness-featureflags-1.2.0.tar`

### file list

```diff
@@ -1,237 +1,239 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-02-21 15:02:49.622905 harness-featureflags-1.1.9/
--rw-r--r--   0 root         (0) root         (0)      163 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/AUTHORS.rst
--rw-r--r--   0 root         (0) root         (0)     3655 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/CONTRIBUTING.rst
--rw-r--r--   0 root         (0) root         (0)       89 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/HISTORY.rst
--rw-r--r--   0 root         (0) root         (0)      585 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/LICENSE
--rw-r--r--   0 root         (0) root         (0)      262 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/MANIFEST.in
--rw-r--r--   0 root         (0) root         (0)     6285 2023-02-21 15:02:49.622905 harness-featureflags-1.1.9/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)     4384 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/README.md
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-02-21 15:02:49.604904 harness-featureflags-1.1.9/docs/
--rw-r--r--   0 root         (0) root         (0)      621 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/docs/Makefile
--rw-r--r--   0 root         (0) root         (0)       28 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/docs/authors.rst
--rwxr-xr-x   0 root         (0) root         (0)     4958 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/docs/conf.py
--rw-r--r--   0 root         (0) root         (0)       33 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/docs/contributing.rst
--rw-r--r--   0 root         (0) root         (0)     1753 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/docs/featureflags.api.default.rst
--rw-r--r--   0 root         (0) root         (0)      591 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/docs/featureflags.api.rst
--rw-r--r--   0 root         (0) root         (0)      183 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/docs/featureflags.client.rst
--rw-r--r--   0 root         (0) root         (0)      195 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/docs/featureflags.evaluation.rst
--rw-r--r--   0 root         (0) root         (0)     3689 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/docs/featureflags.evaluations.rst
--rw-r--r--   0 root         (0) root         (0)     1378 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/docs/featureflags.ftypes.rst
--rw-r--r--   0 root         (0) root         (0)     2781 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/docs/featureflags.models.rst
--rw-r--r--   0 root         (0) root         (0)     1916 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/docs/featureflags.rest.api.default.rst
--rw-r--r--   0 root         (0) root         (0)      263 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/docs/featureflags.rest.api.rst
--rw-r--r--   0 root         (0) root         (0)     4302 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/docs/featureflags.rest.models.rst
--rw-r--r--   0 root         (0) root         (0)      621 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/docs/featureflags.rest.rst
--rw-r--r--   0 root         (0) root         (0)     1853 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/docs/featureflags.rst
--rw-r--r--   0 root         (0) root         (0)       28 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/docs/history.rst
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-02-21 15:02:49.604904 harness-featureflags-1.1.9/docs/images/
--rw-r--r--   0 root         (0) root         (0)   100515 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/docs/images/ff-gui.png
--rw-r--r--   0 root         (0) root         (0)      333 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/docs/index.rst
--rw-r--r--   0 root         (0) root         (0)     1215 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/docs/installation.rst
--rw-r--r--   0 root         (0) root         (0)      782 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/docs/make.bat
--rw-r--r--   0 root         (0) root         (0)       73 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/docs/modules.rst
--rw-r--r--   0 root         (0) root         (0)       27 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/docs/readme.rst
--rw-r--r--   0 root         (0) root         (0)       98 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/docs/usage.rst
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-02-21 15:02:49.605904 harness-featureflags-1.1.9/featureflags/
--rw-r--r--   0 root         (0) root         (0)      148 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/__init__.py
--rw-r--r--   0 root         (0) root         (0)     7444 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/analytics.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-02-21 15:02:49.605904 harness-featureflags-1.1.9/featureflags/api/
--rw-r--r--   0 root         (0) root         (0)      173 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/api/__init__.py
--rw-r--r--   0 root         (0) root         (0)     1742 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/api/client.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-02-21 15:02:49.606904 harness-featureflags-1.1.9/featureflags/api/default/
--rw-r--r--   0 root         (0) root         (0)        0 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/api/default/__init__.py
--rw-r--r--   0 root         (0) root         (0)     3027 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/api/default/authenticate.py
--rw-r--r--   0 root         (0) root         (0)     2872 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/api/default/get_all_segments.py
--rw-r--r--   0 root         (0) root         (0)     2995 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/api/default/get_feature_config.py
--rw-r--r--   0 root         (0) root         (0)     2943 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/api/default/get_feature_config_by_identifier.py
--rw-r--r--   0 root         (0) root         (0)     2538 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/api/default/get_segment_by_identifier.py
--rw-r--r--   0 root         (0) root         (0)     1907 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/api/default/post_metrics.py
--rw-r--r--   0 root         (0) root         (0)     1595 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/api/default/stream.py
--rw-r--r--   0 root         (0) root         (0)      923 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/api/types.py
--rw-r--r--   0 root         (0) root         (0)     7546 2023-02-21 15:01:39.000000 harness-featureflags-1.1.9/featureflags/client.py
--rw-r--r--   0 root         (0) root         (0)     2057 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/config.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-02-21 15:02:49.608904 harness-featureflags-1.1.9/featureflags/evaluations/
--rw-r--r--   0 root         (0) root         (0)        0 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/evaluations/__init__.py
--rw-r--r--   0 root         (0) root         (0)     2878 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/evaluations/auth_target.py
--rw-r--r--   0 root         (0) root         (0)     3892 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/evaluations/clause.py
--rw-r--r--   0 root         (0) root         (0)      273 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/evaluations/constants.py
--rw-r--r--   0 root         (0) root         (0)     2799 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/evaluations/distribution.py
--rw-r--r--   0 root         (0) root         (0)      124 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/evaluations/enum.py
--rw-r--r--   0 root         (0) root         (0)    13883 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/evaluations/evaluator.py
--rw-r--r--   0 root         (0) root         (0)     9128 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/evaluations/feature.py
--rw-r--r--   0 root         (0) root         (0)     1548 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/evaluations/prerequisite.py
--rw-r--r--   0 root         (0) root         (0)     5429 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/evaluations/segment.py
--rw-r--r--   0 root         (0) root         (0)     2063 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/evaluations/serve.py
--rw-r--r--   0 root         (0) root         (0)     3165 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/evaluations/serving_rule.py
--rw-r--r--   0 root         (0) root         (0)      473 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/evaluations/strategy.py
--rw-r--r--   0 root         (0) root         (0)     1544 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/evaluations/tag.py
--rw-r--r--   0 root         (0) root         (0)     4378 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/evaluations/target.py
--rw-r--r--   0 root         (0) root         (0)     1339 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/evaluations/target_attributes.py
--rw-r--r--   0 root         (0) root         (0)     1606 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/evaluations/target_map.py
--rw-r--r--   0 root         (0) root         (0)     2656 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/evaluations/variation.py
--rw-r--r--   0 root         (0) root         (0)     2564 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/evaluations/variation_map.py
--rw-r--r--   0 root         (0) root         (0)     1525 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/evaluations/weighted_variation.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-02-21 15:02:49.608904 harness-featureflags-1.1.9/featureflags/ftypes/
--rw-r--r--   0 root         (0) root         (0)      242 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/ftypes/__init__.py
--rw-r--r--   0 root         (0) root         (0)     1053 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/ftypes/boolean.py
--rw-r--r--   0 root         (0) root         (0)     1304 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/ftypes/integer.py
--rw-r--r--   0 root         (0) root         (0)     2469 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/ftypes/interface.py
--rw-r--r--   0 root         (0) root         (0)     1009 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/ftypes/json.py
--rw-r--r--   0 root         (0) root         (0)     1317 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/ftypes/number.py
--rw-r--r--   0 root         (0) root         (0)     1694 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/ftypes/string.py
--rw-r--r--   0 root         (0) root         (0)      497 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/ftypes/utils.py
--rw-r--r--   0 root         (0) root         (0)     1041 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/interface.py
--rw-r--r--   0 root         (0) root         (0)     1218 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/lru_cache.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-02-21 15:02:49.610904 harness-featureflags-1.1.9/featureflags/models/
--rw-r--r--   0 root         (0) root         (0)      809 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/models/__init__.py
--rw-r--r--   0 root         (0) root         (0)     2054 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/models/authentication_request.py
--rw-r--r--   0 root         (0) root         (0)     2708 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/models/authentication_request_target.py
--rw-r--r--   0 root         (0) root         (0)     1284 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/models/authentication_request_target_attributes.py
--rw-r--r--   0 root         (0) root         (0)     1421 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/models/authentication_response.py
--rw-r--r--   0 root         (0) root         (0)     1430 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/models/error.py
--rw-r--r--   0 root         (0) root         (0)     1421 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/models/key_value.py
--rw-r--r--   0 root         (0) root         (0)     1313 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/models/message.py
--rw-r--r--   0 root         (0) root         (0)     2827 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/models/metrics.py
--rw-r--r--   0 root         (0) root         (0)     2372 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/models/metrics_data.py
--rw-r--r--   0 root         (0) root         (0)      155 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/models/metrics_data_metrics_type.py
--rw-r--r--   0 root         (0) root         (0)     2131 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/models/pagination.py
--rw-r--r--   0 root         (0) root         (0)     2055 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/models/target_data.py
--rw-r--r--   0 root         (0) root         (0)       92 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/models/unset.py
--rw-r--r--   0 root         (0) root         (0)     1466 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/persisting.py
--rw-r--r--   0 root         (0) root         (0)     4917 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/polling.py
--rw-r--r--   0 root         (0) root         (0)     8198 2023-02-21 15:01:38.000000 harness-featureflags-1.1.9/featureflags/repository.py
--rw-r--r--   0 root         (0) root         (0)     6887 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/sse_client.py
--rw-r--r--   0 root         (0) root         (0)     6358 2023-02-21 15:01:38.000000 harness-featureflags-1.1.9/featureflags/streaming.py
--rw-r--r--   0 root         (0) root         (0)      151 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/featureflags/util.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-02-21 15:02:49.610904 harness-featureflags-1.1.9/harness_featureflags.egg-info/
--rw-r--r--   0 root         (0) root         (0)     6285 2023-02-21 15:02:49.000000 harness-featureflags-1.1.9/harness_featureflags.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)    14969 2023-02-21 15:02:49.000000 harness-featureflags-1.1.9/harness_featureflags.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-02-21 15:02:49.000000 harness-featureflags-1.1.9/harness_featureflags.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-02-21 15:02:49.000000 harness-featureflags-1.1.9/harness_featureflags.egg-info/not-zip-safe
--rw-r--r--   0 root         (0) root         (0)       70 2023-02-21 15:02:49.000000 harness-featureflags-1.1.9/harness_featureflags.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)       13 2023-02-21 15:02:49.000000 harness-featureflags-1.1.9/harness_featureflags.egg-info/top_level.txt
--rw-r--r--   0 root         (0) root         (0)      454 2023-02-21 15:02:49.623905 harness-featureflags-1.1.9/setup.cfg
--rw-r--r--   0 root         (0) root         (0)     1646 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/setup.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-02-21 15:02:49.610904 harness-featureflags-1.1.9/tests/
--rw-r--r--   0 root         (0) root         (0)       42 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/tests/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-02-21 15:02:49.611904 harness-featureflags-1.1.9/tests/integration/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-02-21 15:02:49.612904 harness-featureflags-1.1.9/tests/integration/ff-test-cases/
--rw-r--r--   0 root         (0) root         (0)       62 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/.git
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-02-21 15:02:49.601904 harness-featureflags-1.1.9/tests/integration/ff-test-cases/.github/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-02-21 15:02:49.612904 harness-featureflags-1.1.9/tests/integration/ff-test-cases/.github/workflows/
--rw-r--r--   0 root         (0) root         (0)      333 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/.github/workflows/ci.yml
--rw-r--r--   0 root         (0) root         (0)       39 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/.gitignore
--rw-r--r--   0 root         (0) root         (0)     2746 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/Makefile
--rw-r--r--   0 root         (0) root         (0)     3334 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/README.md
--rw-r--r--   0 root         (0) root         (0)    15527 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/client-v1.yaml
--rw-r--r--   0 root         (0) root         (0)       59 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/go.mod
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-02-21 15:02:49.612904 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-02-21 15:02:49.613905 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOffRules/
--rw-r--r--   0 root         (0) root         (0)    16904 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_Bool_State_Disabled_On_False_Off_False_Should_Return_False.json
--rw-r--r--   0 root         (0) root         (0)    16898 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_Bool_State_Disabled_On_False_Off_True_Should_Return_True.json
--rw-r--r--   0 root         (0) root         (0)    16901 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_Bool_State_Disabled_On_True_Off_False_Should_Return_False.json
--rw-r--r--   0 root         (0) root         (0)    16895 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_Bool_State_Disabled_On_True_Off_True_Should_Return_True.json
--rw-r--r--   0 root         (0) root         (0)    17222 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_JSON_State_Disabled_On_complexJSON_Off_emptyJSON_Should_Return_validJSON.json
--rw-r--r--   0 root         (0) root         (0)    17197 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_JSON_State_Disabled_On_validJSON_Off_emptyJSON_Should_Return_emptyJSON.json
--rw-r--r--   0 root         (0) root         (0)    17019 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_Number_State_Disabled_On_011_Off_2_Should_Return_2.json
--rw-r--r--   0 root         (0) root         (0)    17041 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_Number_State_Disabled_On_324523_Off_011_Should_Return_011.json
--rw-r--r--   0 root         (0) root         (0)    20249 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_String_State_Disabled_On_sonnet19_Off_sonnet53_Should_Return_sonnet53.json
--rw-r--r--   0 root         (0) root         (0)    20313 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_String_State_Disabled_On_sonnet53_Off_sonnet19_Should_Return_sonnet19.json
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-02-21 15:02:49.615905 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOnRules/
--rw-r--r--   0 root         (0) root         (0)    16899 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_Bool_State_Enabled_On_False_Off_False_Should_Return_False.json
--rw-r--r--   0 root         (0) root         (0)    16894 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_Bool_State_Enabled_On_False_Off_True_Should_Return_True.json
--rw-r--r--   0 root         (0) root         (0)    16895 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_Bool_State_Enabled_On_True_Off_False_Should_Return_False.json
--rw-r--r--   0 root         (0) root         (0)    16890 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_Bool_State_Enabled_On_True_Off_True_Should_Return_True.json
--rw-r--r--   0 root         (0) root         (0)    17241 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_JSON_State_Enabled_On_complexJSON_Off_emptyJSON_Should_Return_complexJSON.json
--rw-r--r--   0 root         (0) root         (0)    17211 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_JSON_State_Enabled_On_validJSON_Off_emptyJSON_Should_Return_validJSON.json
--rw-r--r--   0 root         (0) root         (0)    17021 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_Number_State_Enabled_On_011_Off_2_Should_Return_011.json
--rw-r--r--   0 root         (0) root         (0)    17041 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_Number_State_Enabled_On_324523_Off_011_Should_Return_324523.json
--rw-r--r--   0 root         (0) root         (0)    20308 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_String_State_Enabled_On_sonnet19_Off_sonnet53_Should_Return_sonnet19.json
--rw-r--r--   0 root         (0) root         (0)    20244 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_String_State_Enabled_On_sonnet53_Off_sonnet19_Should_Return_sonnet53.json
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-02-21 15:02:49.616905 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/GroupRules/
--rw-r--r--   0 root         (0) root         (0)    17239 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_EqualsThree_Should_Return_false_for_Target_three.json
--rw-r--r--   0 root         (0) root         (0)    17230 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_EqualsThree_Should_Return_true_for_Target_one.json
--rw-r--r--   0 root         (0) root         (0)    17276 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_GroupWithMultipleOrRules_Should_Return_true_for_Target_three.json
--rw-r--r--   0 root         (0) root         (0)    17243 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_InOneTwoThree_Should_Return_true_for_Target_three.json
--rw-r--r--   0 root         (0) root         (0)    17270 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_IncludeAndExcludeGroup_Should_Return_true_for_Target_three.json
--rw-r--r--   0 root         (0) root         (0)    17240 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_IncludedOnly_Should_Return_true_for_Target_three.json
--rw-r--r--   0 root         (0) root         (0)    17275 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_StartsWithTExcludesThree_Should_Return_true_for_Target_three.json
--rw-r--r--   0 root         (0) root         (0)    17232 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_StartsWithT_Should_Return_false_for_Target_one.json
--rw-r--r--   0 root         (0) root         (0)    17237 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_StartsWithT_Should_Return_true_for_Target_three.json
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-02-21 15:02:49.619905 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/
--rw-r--r--   0 root         (0) root         (0)    17050 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_BoolBool_State_Enabled_On_True_Off_False_Prerequisites_AlwaysOff_Should_Return_False.json
--rw-r--r--   0 root         (0) root         (0)    17048 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_BoolBool_State_Enabled_On_True_Off_False_Prerequisites_AlwaysOff_Should_Return_True.json
--rw-r--r--   0 root         (0) root         (0)    17045 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_BoolBool_State_Enabled_On_True_Off_True_Prerequisites_AlwaysOn_Should_Return_False.json
--rw-r--r--   0 root         (0) root         (0)    17041 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_BoolBool_State_Enabled_On_True_Off_True_Prerequisites_AlwaysOn_Should_Return_True.json
--rw-r--r--   0 root         (0) root         (0)    17039 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_BoolInt_State_Enabled_On_True_Off_False_Prerequisites_AlwaysOff_Should_Return_False.json
--rw-r--r--   0 root         (0) root         (0)    17039 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_BoolInt_State_Enabled_On_True_Off_False_Prerequisites_AlwaysOff_Should_Return_True.json
--rw-r--r--   0 root         (0) root         (0)    17036 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_BoolInt_State_Enabled_On_True_Off_True_Prerequisites_AlwaysOn_Should_Return_False.json
--rw-r--r--   0 root         (0) root         (0)    17030 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_BoolInt_State_Enabled_On_True_Off_True_Prerequisites_AlwaysOn_Should_Return_True.json
--rw-r--r--   0 root         (0) root         (0)    17169 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntBool_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOff_Should_Return_011.json
--rw-r--r--   0 root         (0) root         (0)    17163 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntBool_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOff_Should_Return_2.json
--rw-r--r--   0 root         (0) root         (0)    17166 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntBool_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOn_Should_Return_011.json
--rw-r--r--   0 root         (0) root         (0)    17158 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntBool_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOn_Should_Return_2.json
--rw-r--r--   0 root         (0) root         (0)    17158 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntInt_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOff_Should_Return_011.json
--rw-r--r--   0 root         (0) root         (0)    17154 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntInt_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOff_Should_Return_2.json
--rw-r--r--   0 root         (0) root         (0)    17157 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntInt_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOn_Should_Return_011.json
--rw-r--r--   0 root         (0) root         (0)    17147 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntInt_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOn_Should_Return_2.json
--rw-r--r--   0 root         (0) root         (0)    17173 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntJson_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOff_Should_Return_011.json
--rw-r--r--   0 root         (0) root         (0)    17164 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntJson_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOff_Should_Return_2.json
--rw-r--r--   0 root         (0) root         (0)    17167 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntJson_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOn_Should_Return_011.json
--rw-r--r--   0 root         (0) root         (0)    17162 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntJson_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOn_Should_Return_2.json
--rw-r--r--   0 root         (0) root         (0)    17183 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntString_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOff_Should_Return_011.json
--rw-r--r--   0 root         (0) root         (0)    17176 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntString_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOff_Should_Return_2.json
--rw-r--r--   0 root         (0) root         (0)    17179 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntString_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOn_Should_Return_011.json
--rw-r--r--   0 root         (0) root         (0)    17172 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntString_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOn_Should_Return_2.json
--rw-r--r--   0 root         (0) root         (0)    17353 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_JsonJson_State_Enabled_On_com_Off_val_Prerequisites_AlwaysOff_Should_Return_Com.json
--rw-r--r--   0 root         (0) root         (0)    17335 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_JsonJson_State_Enabled_On_com_Off_val_Prerequisites_AlwaysOff_Should_Return_Val.json
--rw-r--r--   0 root         (0) root         (0)    17351 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_JsonJson_State_Enabled_On_com_Off_val_Prerequisites_AlwaysOn_Should_Return_Com.json
--rw-r--r--   0 root         (0) root         (0)    17329 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_JsonJson_State_Enabled_On_com_Off_val_Prerequisites_AlwaysOn_Should_Return_Val.json
--rw-r--r--   0 root         (0) root         (0)    20370 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_StrStr_State_Enabled_On_s19_Off_s53_Prerequisites_AlwaysOff_Should_Return_off.json
--rw-r--r--   0 root         (0) root         (0)    20432 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_StrStr_State_Enabled_On_s19_Off_s53_Prerequisites_AlwaysOff_Should_Return_on.json
--rw-r--r--   0 root         (0) root         (0)    20366 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_StrStr_State_Enabled_On_s19_Off_s53_Prerequisites_AlwaysOn_Should_Return_Off.json
--rw-r--r--   0 root         (0) root         (0)    20428 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_StrStr_State_Enabled_On_s19_Off_s53_Prerequisites_AlwaysOn_Should_Return_On.json
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-02-21 15:02:49.621905 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/TargetRules/
--rw-r--r--   0 root         (0) root         (0)    17225 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_Bool_State_Disabled_Should_Return_Default_Off_Value.json
--rw-r--r--   0 root         (0) root         (0)    17229 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_Bool_State_Enabled_Should_Return_false_for_Target_four.json
--rw-r--r--   0 root         (0) root         (0)    17545 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_Bool_State_Enabled_Should_Return_false_for_Target_six.json
--rw-r--r--   0 root         (0) root         (0)    17229 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_Bool_State_Enabled_Should_Return_true_for_Target_three.json
--rw-r--r--   0 root         (0) root         (0)    17879 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_JSON_State_Enabled_Should_Return_complexJSON_for_Target_five.json
--rw-r--r--   0 root         (0) root         (0)    17836 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_JSON_State_Enabled_Should_Return_emptyJSON_for_Target_four.json
--rw-r--r--   0 root         (0) root         (0)    17870 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_JSON_State_Enabled_Should_Return_validJSON_for_Target_anonymous.json
--rw-r--r--   0 root         (0) root         (0)    17673 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_Number_State_Enabled_Should_Return_2_for_Target_four.json
--rw-r--r--   0 root         (0) root         (0)    17688 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_Number_State_Enabled_Should_Return_324523_for_Target_five.json
--rw-r--r--   0 root         (0) root         (0)    17705 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_Number_State_Enabled_Should_Return_sonnet53_for_Target_anonymous.json
--rw-r--r--   0 root         (0) root         (0)    20968 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_String_State_Enabled_Should_Return_sonnet53_for_Target_anonymous.json
--rw-r--r--   0 root         (0) root         (0)    20889 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_String_State_Enabled_Should_Return_sonnet53_for_Target_four.json
--rw-r--r--   0 root         (0) root         (0)    21601 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_String_State_Enabled_Should_Return_thehobbit_for_Target_five.json
--rw-r--r--   0 root         (0) root         (0)     1475 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/bool_on_simple_rule.json
--rw-r--r--   0 root         (0) root         (0)     1038 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/off_flag.json
--rw-r--r--   0 root         (0) root         (0)     1084 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/off_off_no_rules.json
--rw-r--r--   0 root         (0) root         (0)     1065 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/on_off_no_rules.json
--rw-r--r--   0 root         (0) root         (0)     2430 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/prereq.json
--rw-r--r--   0 root         (0) root         (0)     1762 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/rules_priority.json
--rw-r--r--   0 root         (0) root         (0)     1574 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/segment_includes_target.json
--rw-r--r--   0 root         (0) root         (0)     1279 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/test_empty_or_missing_target_attributes.json
--rw-r--r--   0 root         (0) root         (0)     6749 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/types.gen.go
--rw-r--r--   0 root         (0) root         (0)      384 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/types.go
--rw-r--r--   0 root         (0) root         (0)     2697 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/validator.go
--rw-r--r--   0 root         (0) root         (0)      128 2023-02-21 15:00:31.000000 harness-featureflags-1.1.9/tests/integration/ff-test-cases/validator_test.go
--rw-r--r--   0 root         (0) root         (0)      734 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/tests/integration/test_clause.py
--rw-r--r--   0 root         (0) root         (0)     4150 2023-02-21 15:01:38.000000 harness-featureflags-1.1.9/tests/integration/test_evaluator.py
--rw-r--r--   0 root         (0) root         (0)     3885 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/tests/integration/test_feature.py
--rw-r--r--   0 root         (0) root         (0)      698 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/tests/test_client.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-02-21 15:02:49.622905 harness-featureflags-1.1.9/tests/unit/
--rw-r--r--   0 root         (0) root         (0)        0 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/tests/unit/__init__.py
--rw-r--r--   0 root         (0) root         (0)      349 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/tests/unit/test_boolean.py
--rw-r--r--   0 root         (0) root         (0)     1608 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/tests/unit/test_clause.py
--rw-r--r--   0 root         (0) root         (0)     7062 2023-02-21 15:01:38.000000 harness-featureflags-1.1.9/tests/unit/test_evaluator.py
--rw-r--r--   0 root         (0) root         (0)        0 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/tests/unit/test_feature.py
--rw-r--r--   0 root         (0) root         (0)     1073 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/tests/unit/test_integer.py
--rw-r--r--   0 root         (0) root         (0)     2701 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/tests/unit/test_lru.py
--rw-r--r--   0 root         (0) root         (0)     1092 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/tests/unit/test_number.py
--rw-r--r--   0 root         (0) root         (0)     7669 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/tests/unit/test_sse_client.py
--rw-r--r--   0 root         (0) root         (0)     1589 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/tests/unit/test_string.py
--rw-r--r--   0 root         (0) root         (0)     1684 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/tests/unit/test_target.py
--rw-r--r--   0 root         (0) root         (0)     1137 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/tests/unit/test_utils.py
--rw-r--r--   0 root         (0) root         (0)     1500 2023-02-21 15:00:23.000000 harness-featureflags-1.1.9/tests/unit/test_variation.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:43:04.789575 harness-featureflags-1.2.0/
+-rw-r--r--   0 root         (0) root         (0)      163 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/AUTHORS.rst
+-rw-r--r--   0 root         (0) root         (0)     3655 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/CONTRIBUTING.rst
+-rw-r--r--   0 root         (0) root         (0)       89 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/HISTORY.rst
+-rw-r--r--   0 root         (0) root         (0)      585 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/LICENSE
+-rw-r--r--   0 root         (0) root         (0)      262 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/MANIFEST.in
+-rw-r--r--   0 root         (0) root         (0)     5307 2023-06-28 14:43:04.789575 harness-featureflags-1.2.0/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     4373 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/README.md
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:43:04.702568 harness-featureflags-1.2.0/docs/
+-rw-r--r--   0 root         (0) root         (0)      621 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/docs/Makefile
+-rw-r--r--   0 root         (0) root         (0)       28 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/docs/authors.rst
+-rwxr-xr-x   0 root         (0) root         (0)     4958 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/docs/conf.py
+-rw-r--r--   0 root         (0) root         (0)       33 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/docs/contributing.rst
+-rw-r--r--   0 root         (0) root         (0)     1753 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/docs/featureflags.api.default.rst
+-rw-r--r--   0 root         (0) root         (0)      591 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/docs/featureflags.api.rst
+-rw-r--r--   0 root         (0) root         (0)      183 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/docs/featureflags.client.rst
+-rw-r--r--   0 root         (0) root         (0)      195 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/docs/featureflags.evaluation.rst
+-rw-r--r--   0 root         (0) root         (0)     3689 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/docs/featureflags.evaluations.rst
+-rw-r--r--   0 root         (0) root         (0)     1378 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/docs/featureflags.ftypes.rst
+-rw-r--r--   0 root         (0) root         (0)     2781 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/docs/featureflags.models.rst
+-rw-r--r--   0 root         (0) root         (0)     1916 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/docs/featureflags.rest.api.default.rst
+-rw-r--r--   0 root         (0) root         (0)      263 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/docs/featureflags.rest.api.rst
+-rw-r--r--   0 root         (0) root         (0)     4302 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/docs/featureflags.rest.models.rst
+-rw-r--r--   0 root         (0) root         (0)      621 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/docs/featureflags.rest.rst
+-rw-r--r--   0 root         (0) root         (0)     1853 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/docs/featureflags.rst
+-rw-r--r--   0 root         (0) root         (0)       28 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/docs/history.rst
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:43:04.702568 harness-featureflags-1.2.0/docs/images/
+-rw-r--r--   0 root         (0) root         (0)   100515 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/docs/images/ff-gui.png
+-rw-r--r--   0 root         (0) root         (0)      333 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/docs/index.rst
+-rw-r--r--   0 root         (0) root         (0)     1215 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/docs/installation.rst
+-rw-r--r--   0 root         (0) root         (0)      782 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/docs/make.bat
+-rw-r--r--   0 root         (0) root         (0)       73 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/docs/modules.rst
+-rw-r--r--   0 root         (0) root         (0)       27 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/docs/readme.rst
+-rw-r--r--   0 root         (0) root         (0)       98 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/docs/usage.rst
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:43:04.704568 harness-featureflags-1.2.0/featureflags/
+-rw-r--r--   0 root         (0) root         (0)      148 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    12093 2023-06-28 14:41:39.000000 harness-featureflags-1.2.0/featureflags/analytics.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:43:04.705568 harness-featureflags-1.2.0/featureflags/api/
+-rw-r--r--   0 root         (0) root         (0)      173 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/api/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     1850 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/api/client.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:43:04.706568 harness-featureflags-1.2.0/featureflags/api/default/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/api/default/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     3972 2023-06-28 14:41:38.000000 harness-featureflags-1.2.0/featureflags/api/default/authenticate.py
+-rw-r--r--   0 root         (0) root         (0)     2872 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/api/default/get_all_segments.py
+-rw-r--r--   0 root         (0) root         (0)     2995 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/api/default/get_feature_config.py
+-rw-r--r--   0 root         (0) root         (0)     2943 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/api/default/get_feature_config_by_identifier.py
+-rw-r--r--   0 root         (0) root         (0)     2538 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/api/default/get_segment_by_identifier.py
+-rw-r--r--   0 root         (0) root         (0)     1907 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/api/default/post_metrics.py
+-rw-r--r--   0 root         (0) root         (0)     1595 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/api/default/stream.py
+-rw-r--r--   0 root         (0) root         (0)      923 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/api/types.py
+-rw-r--r--   0 root         (0) root         (0)     9676 2023-06-28 14:41:38.000000 harness-featureflags-1.2.0/featureflags/client.py
+-rw-r--r--   0 root         (0) root         (0)     2603 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/config.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:43:04.708569 harness-featureflags-1.2.0/featureflags/evaluations/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/evaluations/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     2878 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/evaluations/auth_target.py
+-rw-r--r--   0 root         (0) root         (0)     3892 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/evaluations/clause.py
+-rw-r--r--   0 root         (0) root         (0)      273 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/evaluations/constants.py
+-rw-r--r--   0 root         (0) root         (0)     2799 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/evaluations/distribution.py
+-rw-r--r--   0 root         (0) root         (0)      124 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/evaluations/enum.py
+-rw-r--r--   0 root         (0) root         (0)    13944 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/evaluations/evaluator.py
+-rw-r--r--   0 root         (0) root         (0)     9128 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/evaluations/feature.py
+-rw-r--r--   0 root         (0) root         (0)     1548 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/evaluations/prerequisite.py
+-rw-r--r--   0 root         (0) root         (0)     5429 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/evaluations/segment.py
+-rw-r--r--   0 root         (0) root         (0)     2063 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/evaluations/serve.py
+-rw-r--r--   0 root         (0) root         (0)     3165 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/evaluations/serving_rule.py
+-rw-r--r--   0 root         (0) root         (0)      473 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/evaluations/strategy.py
+-rw-r--r--   0 root         (0) root         (0)     1544 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/evaluations/tag.py
+-rw-r--r--   0 root         (0) root         (0)     4378 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/evaluations/target.py
+-rw-r--r--   0 root         (0) root         (0)     1339 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/evaluations/target_attributes.py
+-rw-r--r--   0 root         (0) root         (0)     1606 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/evaluations/target_map.py
+-rw-r--r--   0 root         (0) root         (0)     5352 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/evaluations/variation.py
+-rw-r--r--   0 root         (0) root         (0)     2564 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/evaluations/variation_map.py
+-rw-r--r--   0 root         (0) root         (0)     1525 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/evaluations/weighted_variation.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:43:04.709569 harness-featureflags-1.2.0/featureflags/ftypes/
+-rw-r--r--   0 root         (0) root         (0)      242 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/ftypes/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     1053 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/ftypes/boolean.py
+-rw-r--r--   0 root         (0) root         (0)     1304 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/ftypes/integer.py
+-rw-r--r--   0 root         (0) root         (0)     2469 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/ftypes/interface.py
+-rw-r--r--   0 root         (0) root         (0)     1009 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/ftypes/json.py
+-rw-r--r--   0 root         (0) root         (0)     1317 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/ftypes/number.py
+-rw-r--r--   0 root         (0) root         (0)     1694 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/ftypes/string.py
+-rw-r--r--   0 root         (0) root         (0)      497 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/ftypes/utils.py
+-rw-r--r--   0 root         (0) root         (0)     1041 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/interface.py
+-rw-r--r--   0 root         (0) root         (0)     1218 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/lru_cache.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:43:04.710569 harness-featureflags-1.2.0/featureflags/models/
+-rw-r--r--   0 root         (0) root         (0)      809 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/models/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     2054 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/models/authentication_request.py
+-rw-r--r--   0 root         (0) root         (0)     2708 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/models/authentication_request_target.py
+-rw-r--r--   0 root         (0) root         (0)     1284 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/models/authentication_request_target_attributes.py
+-rw-r--r--   0 root         (0) root         (0)     1421 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/models/authentication_response.py
+-rw-r--r--   0 root         (0) root         (0)     1430 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/models/error.py
+-rw-r--r--   0 root         (0) root         (0)     1421 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/models/key_value.py
+-rw-r--r--   0 root         (0) root         (0)     1313 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/models/message.py
+-rw-r--r--   0 root         (0) root         (0)     2827 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/models/metrics.py
+-rw-r--r--   0 root         (0) root         (0)     2372 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/models/metrics_data.py
+-rw-r--r--   0 root         (0) root         (0)      155 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/models/metrics_data_metrics_type.py
+-rw-r--r--   0 root         (0) root         (0)     2131 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/models/pagination.py
+-rw-r--r--   0 root         (0) root         (0)     2055 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/models/target_data.py
+-rw-r--r--   0 root         (0) root         (0)       92 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/models/unset.py
+-rw-r--r--   0 root         (0) root         (0)     1466 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/persisting.py
+-rw-r--r--   0 root         (0) root         (0)     4963 2023-06-28 14:41:39.000000 harness-featureflags-1.2.0/featureflags/polling.py
+-rw-r--r--   0 root         (0) root         (0)     8198 2023-06-28 14:41:38.000000 harness-featureflags-1.2.0/featureflags/repository.py
+-rw-r--r--   0 root         (0) root         (0)     4161 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/sdk_logging_codes.py
+-rw-r--r--   0 root         (0) root         (0)     7401 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/sse_client.py
+-rw-r--r--   0 root         (0) root         (0)     6298 2023-06-28 14:41:38.000000 harness-featureflags-1.2.0/featureflags/streaming.py
+-rw-r--r--   0 root         (0) root         (0)      151 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/featureflags/util.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:43:04.711569 harness-featureflags-1.2.0/harness_featureflags.egg-info/
+-rw-r--r--   0 root         (0) root         (0)     5307 2023-06-28 14:43:04.000000 harness-featureflags-1.2.0/harness_featureflags.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)    15040 2023-06-28 14:43:04.000000 harness-featureflags-1.2.0/harness_featureflags.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 14:43:04.000000 harness-featureflags-1.2.0/harness_featureflags.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 14:43:04.000000 harness-featureflags-1.2.0/harness_featureflags.egg-info/not-zip-safe
+-rw-r--r--   0 root         (0) root         (0)       86 2023-06-28 14:43:04.000000 harness-featureflags-1.2.0/harness_featureflags.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)       13 2023-06-28 14:43:04.000000 harness-featureflags-1.2.0/harness_featureflags.egg-info/top_level.txt
+-rw-r--r--   0 root         (0) root         (0)      454 2023-06-28 14:43:04.790575 harness-featureflags-1.2.0/setup.cfg
+-rw-r--r--   0 root         (0) root         (0)     1669 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:43:04.711569 harness-featureflags-1.2.0/tests/
+-rw-r--r--   0 root         (0) root         (0)       42 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/tests/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:43:04.711569 harness-featureflags-1.2.0/tests/integration/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:43:04.769573 harness-featureflags-1.2.0/tests/integration/ff-test-cases/
+-rw-r--r--   0 root         (0) root         (0)       62 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/.git
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:43:04.696568 harness-featureflags-1.2.0/tests/integration/ff-test-cases/.github/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:43:04.769573 harness-featureflags-1.2.0/tests/integration/ff-test-cases/.github/workflows/
+-rw-r--r--   0 root         (0) root         (0)      333 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/.github/workflows/ci.yml
+-rw-r--r--   0 root         (0) root         (0)       39 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/.gitignore
+-rw-r--r--   0 root         (0) root         (0)     2746 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/Makefile
+-rw-r--r--   0 root         (0) root         (0)     3334 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/README.md
+-rw-r--r--   0 root         (0) root         (0)    15527 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/client-v1.yaml
+-rw-r--r--   0 root         (0) root         (0)       59 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/go.mod
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:43:04.770573 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:43:04.772574 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOffRules/
+-rw-r--r--   0 root         (0) root         (0)    16904 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_Bool_State_Disabled_On_False_Off_False_Should_Return_False.json
+-rw-r--r--   0 root         (0) root         (0)    16898 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_Bool_State_Disabled_On_False_Off_True_Should_Return_True.json
+-rw-r--r--   0 root         (0) root         (0)    16901 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_Bool_State_Disabled_On_True_Off_False_Should_Return_False.json
+-rw-r--r--   0 root         (0) root         (0)    16895 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_Bool_State_Disabled_On_True_Off_True_Should_Return_True.json
+-rw-r--r--   0 root         (0) root         (0)    17222 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_JSON_State_Disabled_On_complexJSON_Off_emptyJSON_Should_Return_validJSON.json
+-rw-r--r--   0 root         (0) root         (0)    17197 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_JSON_State_Disabled_On_validJSON_Off_emptyJSON_Should_Return_emptyJSON.json
+-rw-r--r--   0 root         (0) root         (0)    17019 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_Number_State_Disabled_On_011_Off_2_Should_Return_2.json
+-rw-r--r--   0 root         (0) root         (0)    17041 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_Number_State_Disabled_On_324523_Off_011_Should_Return_011.json
+-rw-r--r--   0 root         (0) root         (0)    20249 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_String_State_Disabled_On_sonnet19_Off_sonnet53_Should_Return_sonnet53.json
+-rw-r--r--   0 root         (0) root         (0)    20313 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_String_State_Disabled_On_sonnet53_Off_sonnet19_Should_Return_sonnet19.json
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:43:04.774574 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOnRules/
+-rw-r--r--   0 root         (0) root         (0)    16899 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_Bool_State_Enabled_On_False_Off_False_Should_Return_False.json
+-rw-r--r--   0 root         (0) root         (0)    16894 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_Bool_State_Enabled_On_False_Off_True_Should_Return_True.json
+-rw-r--r--   0 root         (0) root         (0)    16895 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_Bool_State_Enabled_On_True_Off_False_Should_Return_False.json
+-rw-r--r--   0 root         (0) root         (0)    16890 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_Bool_State_Enabled_On_True_Off_True_Should_Return_True.json
+-rw-r--r--   0 root         (0) root         (0)    17241 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_JSON_State_Enabled_On_complexJSON_Off_emptyJSON_Should_Return_complexJSON.json
+-rw-r--r--   0 root         (0) root         (0)    17211 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_JSON_State_Enabled_On_validJSON_Off_emptyJSON_Should_Return_validJSON.json
+-rw-r--r--   0 root         (0) root         (0)    17021 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_Number_State_Enabled_On_011_Off_2_Should_Return_011.json
+-rw-r--r--   0 root         (0) root         (0)    17041 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_Number_State_Enabled_On_324523_Off_011_Should_Return_324523.json
+-rw-r--r--   0 root         (0) root         (0)    20308 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_String_State_Enabled_On_sonnet19_Off_sonnet53_Should_Return_sonnet19.json
+-rw-r--r--   0 root         (0) root         (0)    20244 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_String_State_Enabled_On_sonnet53_Off_sonnet19_Should_Return_sonnet53.json
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:43:04.777574 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/GroupRules/
+-rw-r--r--   0 root         (0) root         (0)    17239 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_EqualsThree_Should_Return_false_for_Target_three.json
+-rw-r--r--   0 root         (0) root         (0)    17230 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_EqualsThree_Should_Return_true_for_Target_one.json
+-rw-r--r--   0 root         (0) root         (0)    17276 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_GroupWithMultipleOrRules_Should_Return_true_for_Target_three.json
+-rw-r--r--   0 root         (0) root         (0)    17243 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_InOneTwoThree_Should_Return_true_for_Target_three.json
+-rw-r--r--   0 root         (0) root         (0)    17270 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_IncludeAndExcludeGroup_Should_Return_true_for_Target_three.json
+-rw-r--r--   0 root         (0) root         (0)    17240 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_IncludedOnly_Should_Return_true_for_Target_three.json
+-rw-r--r--   0 root         (0) root         (0)    17275 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_StartsWithTExcludesThree_Should_Return_true_for_Target_three.json
+-rw-r--r--   0 root         (0) root         (0)    17232 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_StartsWithT_Should_Return_false_for_Target_one.json
+-rw-r--r--   0 root         (0) root         (0)    17237 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_StartsWithT_Should_Return_true_for_Target_three.json
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:43:04.784575 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/
+-rw-r--r--   0 root         (0) root         (0)    17050 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_BoolBool_State_Enabled_On_True_Off_False_Prerequisites_AlwaysOff_Should_Return_False.json
+-rw-r--r--   0 root         (0) root         (0)    17048 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_BoolBool_State_Enabled_On_True_Off_False_Prerequisites_AlwaysOff_Should_Return_True.json
+-rw-r--r--   0 root         (0) root         (0)    17045 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_BoolBool_State_Enabled_On_True_Off_True_Prerequisites_AlwaysOn_Should_Return_False.json
+-rw-r--r--   0 root         (0) root         (0)    17041 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_BoolBool_State_Enabled_On_True_Off_True_Prerequisites_AlwaysOn_Should_Return_True.json
+-rw-r--r--   0 root         (0) root         (0)    17039 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_BoolInt_State_Enabled_On_True_Off_False_Prerequisites_AlwaysOff_Should_Return_False.json
+-rw-r--r--   0 root         (0) root         (0)    17039 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_BoolInt_State_Enabled_On_True_Off_False_Prerequisites_AlwaysOff_Should_Return_True.json
+-rw-r--r--   0 root         (0) root         (0)    17036 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_BoolInt_State_Enabled_On_True_Off_True_Prerequisites_AlwaysOn_Should_Return_False.json
+-rw-r--r--   0 root         (0) root         (0)    17030 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_BoolInt_State_Enabled_On_True_Off_True_Prerequisites_AlwaysOn_Should_Return_True.json
+-rw-r--r--   0 root         (0) root         (0)    17169 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntBool_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOff_Should_Return_011.json
+-rw-r--r--   0 root         (0) root         (0)    17163 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntBool_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOff_Should_Return_2.json
+-rw-r--r--   0 root         (0) root         (0)    17166 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntBool_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOn_Should_Return_011.json
+-rw-r--r--   0 root         (0) root         (0)    17158 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntBool_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOn_Should_Return_2.json
+-rw-r--r--   0 root         (0) root         (0)    17158 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntInt_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOff_Should_Return_011.json
+-rw-r--r--   0 root         (0) root         (0)    17154 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntInt_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOff_Should_Return_2.json
+-rw-r--r--   0 root         (0) root         (0)    17157 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntInt_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOn_Should_Return_011.json
+-rw-r--r--   0 root         (0) root         (0)    17147 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntInt_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOn_Should_Return_2.json
+-rw-r--r--   0 root         (0) root         (0)    17173 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntJson_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOff_Should_Return_011.json
+-rw-r--r--   0 root         (0) root         (0)    17164 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntJson_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOff_Should_Return_2.json
+-rw-r--r--   0 root         (0) root         (0)    17167 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntJson_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOn_Should_Return_011.json
+-rw-r--r--   0 root         (0) root         (0)    17162 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntJson_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOn_Should_Return_2.json
+-rw-r--r--   0 root         (0) root         (0)    17183 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntString_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOff_Should_Return_011.json
+-rw-r--r--   0 root         (0) root         (0)    17176 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntString_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOff_Should_Return_2.json
+-rw-r--r--   0 root         (0) root         (0)    17179 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntString_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOn_Should_Return_011.json
+-rw-r--r--   0 root         (0) root         (0)    17172 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntString_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOn_Should_Return_2.json
+-rw-r--r--   0 root         (0) root         (0)    17353 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_JsonJson_State_Enabled_On_com_Off_val_Prerequisites_AlwaysOff_Should_Return_Com.json
+-rw-r--r--   0 root         (0) root         (0)    17335 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_JsonJson_State_Enabled_On_com_Off_val_Prerequisites_AlwaysOff_Should_Return_Val.json
+-rw-r--r--   0 root         (0) root         (0)    17351 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_JsonJson_State_Enabled_On_com_Off_val_Prerequisites_AlwaysOn_Should_Return_Com.json
+-rw-r--r--   0 root         (0) root         (0)    17329 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_JsonJson_State_Enabled_On_com_Off_val_Prerequisites_AlwaysOn_Should_Return_Val.json
+-rw-r--r--   0 root         (0) root         (0)    20370 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_StrStr_State_Enabled_On_s19_Off_s53_Prerequisites_AlwaysOff_Should_Return_off.json
+-rw-r--r--   0 root         (0) root         (0)    20432 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_StrStr_State_Enabled_On_s19_Off_s53_Prerequisites_AlwaysOff_Should_Return_on.json
+-rw-r--r--   0 root         (0) root         (0)    20366 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_StrStr_State_Enabled_On_s19_Off_s53_Prerequisites_AlwaysOn_Should_Return_Off.json
+-rw-r--r--   0 root         (0) root         (0)    20428 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_StrStr_State_Enabled_On_s19_Off_s53_Prerequisites_AlwaysOn_Should_Return_On.json
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:43:04.786575 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/TargetRules/
+-rw-r--r--   0 root         (0) root         (0)    17225 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_Bool_State_Disabled_Should_Return_Default_Off_Value.json
+-rw-r--r--   0 root         (0) root         (0)    17229 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_Bool_State_Enabled_Should_Return_false_for_Target_four.json
+-rw-r--r--   0 root         (0) root         (0)    17545 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_Bool_State_Enabled_Should_Return_false_for_Target_six.json
+-rw-r--r--   0 root         (0) root         (0)    17229 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_Bool_State_Enabled_Should_Return_true_for_Target_three.json
+-rw-r--r--   0 root         (0) root         (0)    17879 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_JSON_State_Enabled_Should_Return_complexJSON_for_Target_five.json
+-rw-r--r--   0 root         (0) root         (0)    17836 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_JSON_State_Enabled_Should_Return_emptyJSON_for_Target_four.json
+-rw-r--r--   0 root         (0) root         (0)    17870 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_JSON_State_Enabled_Should_Return_validJSON_for_Target_anonymous.json
+-rw-r--r--   0 root         (0) root         (0)    17673 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_Number_State_Enabled_Should_Return_2_for_Target_four.json
+-rw-r--r--   0 root         (0) root         (0)    17688 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_Number_State_Enabled_Should_Return_324523_for_Target_five.json
+-rw-r--r--   0 root         (0) root         (0)    17705 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_Number_State_Enabled_Should_Return_sonnet53_for_Target_anonymous.json
+-rw-r--r--   0 root         (0) root         (0)    20968 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_String_State_Enabled_Should_Return_sonnet53_for_Target_anonymous.json
+-rw-r--r--   0 root         (0) root         (0)    20889 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_String_State_Enabled_Should_Return_sonnet53_for_Target_four.json
+-rw-r--r--   0 root         (0) root         (0)    21601 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_String_State_Enabled_Should_Return_thehobbit_for_Target_five.json
+-rw-r--r--   0 root         (0) root         (0)     1475 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/bool_on_simple_rule.json
+-rw-r--r--   0 root         (0) root         (0)     1038 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/off_flag.json
+-rw-r--r--   0 root         (0) root         (0)     1084 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/off_off_no_rules.json
+-rw-r--r--   0 root         (0) root         (0)     1065 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/on_off_no_rules.json
+-rw-r--r--   0 root         (0) root         (0)     2430 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/prereq.json
+-rw-r--r--   0 root         (0) root         (0)     1762 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/rules_priority.json
+-rw-r--r--   0 root         (0) root         (0)     1574 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/segment_includes_target.json
+-rw-r--r--   0 root         (0) root         (0)     1279 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/test_empty_or_missing_target_attributes.json
+-rw-r--r--   0 root         (0) root         (0)     6749 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/types.gen.go
+-rw-r--r--   0 root         (0) root         (0)      384 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/types.go
+-rw-r--r--   0 root         (0) root         (0)     2697 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/validator.go
+-rw-r--r--   0 root         (0) root         (0)      128 2023-06-28 14:41:00.000000 harness-featureflags-1.2.0/tests/integration/ff-test-cases/validator_test.go
+-rw-r--r--   0 root         (0) root         (0)      734 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/tests/integration/test_clause.py
+-rw-r--r--   0 root         (0) root         (0)     4273 2023-06-28 14:41:38.000000 harness-featureflags-1.2.0/tests/integration/test_evaluator.py
+-rw-r--r--   0 root         (0) root         (0)     3885 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/tests/integration/test_feature.py
+-rw-r--r--   0 root         (0) root         (0)      698 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/tests/test_client.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:43:04.789575 harness-featureflags-1.2.0/tests/unit/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/tests/unit/__init__.py
+-rw-r--r--   0 root         (0) root         (0)      349 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/tests/unit/test_boolean.py
+-rw-r--r--   0 root         (0) root         (0)     1608 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/tests/unit/test_clause.py
+-rw-r--r--   0 root         (0) root         (0)     7062 2023-06-28 14:41:38.000000 harness-featureflags-1.2.0/tests/unit/test_evaluator.py
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/tests/unit/test_feature.py
+-rw-r--r--   0 root         (0) root         (0)     1073 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/tests/unit/test_integer.py
+-rw-r--r--   0 root         (0) root         (0)     2701 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/tests/unit/test_lru.py
+-rw-r--r--   0 root         (0) root         (0)     1092 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/tests/unit/test_number.py
+-rw-r--r--   0 root         (0) root         (0)     1285 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/tests/unit/test_sdk_logging_codes.py
+-rw-r--r--   0 root         (0) root         (0)     7669 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/tests/unit/test_sse_client.py
+-rw-r--r--   0 root         (0) root         (0)     1589 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/tests/unit/test_string.py
+-rw-r--r--   0 root         (0) root         (0)     1684 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/tests/unit/test_target.py
+-rw-r--r--   0 root         (0) root         (0)     1137 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/tests/unit/test_utils.py
+-rw-r--r--   0 root         (0) root         (0)     2363 2023-06-28 14:40:54.000000 harness-featureflags-1.2.0/tests/unit/test_variation.py
```

### Comparing `harness-featureflags-1.1.9/CONTRIBUTING.rst` & `harness-featureflags-1.2.0/CONTRIBUTING.rst`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/LICENSE` & `harness-featureflags-1.2.0/LICENSE`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/PKG-INFO` & `harness-featureflags-1.2.0/PKG-INFO`

 * *Files 16% similar despite different names*

```diff
@@ -1,145 +1,144 @@
 Metadata-Version: 2.1
 Name: harness-featureflags
-Version: 1.1.9
+Version: 1.2.0
 Summary: Feature flag server SDK for python
 Home-page: https://github.com/harness/ff-python-server-sdk
 Author: Enver Bisevac
 Author-email: enver.bisevac@harness.io
 License: Apache Software License 2.0
-Description: Python SDK For Harness Feature Flags
-        ========================
-        
-        [![pypi](https://img.shields.io/pypi/v/harness-featureflags.svg)](https://pypi.python.org/pypi/harness-featureflags)
-        
-        ## Table of Contents
-        **[Intro](#Intro)**<br>
-        **[Requirements](#Requirements)**<br>
-        **[Quickstart](#Quickstart)**<br>
-        **[Further Reading](docs/further_reading.md)**<br>
-        **[Build Instructions](docs/build.md)**<br>
-        
-        
-        ## Intro
-        
-        Use this README to get started with our Feature Flags (FF) SDK for Python. This guide outlines the basics of getting started with the SDK and provides a full code sample for you to try out. 
-        This sample doesn’t include configuration options, for in depth steps and configuring the SDK, for example, disabling streaming or using our Relay Proxy, see the  [Python SDK Reference](https://ngdocs.harness.io/article/hwoxb6x2oe-python-sdk-reference).
-        
-        For a sample FF Python SDK project, see our test [test python project](examples/getting_started/getting_started.py).
-        
-        ![FeatureFlags](https://github.com/harness/ff-python-server-sdk/raw/main/docs/images/ff-gui.png)
-        
-        ## Requirements
-        
-        [Python 3.7](https://www.python.org/downloads/) or newer (python --version)<br>
-        [pip](https://packaging.python.org/en/latest/tutorials/installing-packages/#id12)<br>
-        <br>
-        [For Mac users](https://opensource.com/article/19/5/python-3-default-mac) if you don't already have pyenv or something similar installed for managing python version<br>
-        
-        
-        ## Quickstart
-        To follow along with our test code sample, make sure you’ve:
-        
-        - [Created a Feature Flag on the Harness Platform](https://ngdocs.harness.io/article/1j7pdkqh7j-create-a-feature-flag) called harnessappdemodarkmode
-        - [Created a server SDK key and made a copy of it](https://ngdocs.harness.io/article/1j7pdkqh7j-create-a-feature-flag#step_3_create_an_sdk_key)
-        - 
-        ### Install the SDK
-        Install the python SDK using pip
-        ```python
-        python -m pip install harness-featureflags
-        ```
-        
-        ### Code Sample
-        The following is a complete code example that you can use to test the `harnessappdemodarkmode` Flag you created on the Harness Platform. When you run the code it will:
-        - Connect to the FF service.
-        - Report the value of the Flag every 10 seconds until the connection is closed. Every time the harnessappdemodarkmode Flag is toggled on or off on the Harness Platform, the updated value is reported. 
-        - Close the SDK.
-        
-        ```python
-        from featureflags.client import CfClient
-        from featureflags.config import *
-        from featureflags.evaluations.auth_target import Target
-        from featureflags.util import log
-        import os
-        import time
-        
-        # API Key
-        apiKey = os.getenv('FF_API_KEY', "changeme")
-        
-        # Flag Name
-        flagName = os.getenv('FF_FLAG_NAME', "harnessappdemodarkmode")
-        
-        def main():    
-            # Create a Feature Flag Client
-            client = CfClient(apiKey)
-        
-            # Create a target (different targets can get different results based on rules.  This include a custom attribute 'location')
-            target = Target(identifier='pythonSDK', name="PythonSDK", attributes={"location": "emea"})
-        
-            # Loop forever reporting the state of the flag
-            while True:
-                result = client.bool_variation(flagName, target, False)
-                log.info("Flag variation %s", result)
-                time.sleep(10)
-        
-            close()
-        
-        
-        if __name__ == "__main__":
-            main()
-        ```
-        
-        ### Running the example
-        
-        ```bash
-        $ export FF_API_KEY=<your key here>
-        $ python3 examples/getting_started/getting_started.py
-        ```
-        
-        ### Running the example with Docker
-        If you dont have the right version of python installed locally, or dont want to install the dependancies you can
-        use docker to quickly get started
-        
-        ```bash
-        # Install the package
-        docker run -v $(pwd):/app -w /app python:3.7-slim python -m pip install -t ./local  harness-featureflags
-        
-        # Run the script
-        docker run  -e PYTHONPATH=/app/local -e FF_API_KEY=$FF_API_KEY -v $(pwd):/app -w /app python:3.7-slim python examples/getting_started/getting_started.py
-        ```
-        
-        ### Additional Reading
-        
-        For further examples and config options, see the [Python SDK Reference](https://ngdocs.harness.io/article/hwoxb6x2oe-python-sdk-reference).
-        
-        For more information about Feature Flags, see our [Feature Flags documentation](https://ngdocs.harness.io/article/0a2u2ppp8s-getting-started-with-feature-flags).
-        
-        -------------------------
-        [Harness](https://www.harness.io/) is a feature management platform that helps teams to build better software and to
-        test features quicker.
-        
-        -------------------------
-        
-        
-        
-        =======
-        History
-        =======
-        
-        1.0.1 (2021-07-07)
-        ------------------
-        
-        * First release on PyPI.
-        
 Keywords: featureflags
-Platform: UNKNOWN
 Classifier: Development Status :: 2 - Pre-Alpha
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: Apache Software License
 Classifier: Natural Language :: English
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.5
 Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Requires-Python: >=3.5
 Description-Content-Type: text/markdown
+License-File: LICENSE
+License-File: AUTHORS.rst
+
+Python SDK For Harness Feature Flags
+========================
+
+[![pypi](https://img.shields.io/pypi/v/harness-featureflags.svg)](https://pypi.python.org/pypi/harness-featureflags)
+
+## Table of Contents
+**[Intro](#Intro)**<br>
+**[Requirements](#Requirements)**<br>
+**[Quickstart](#Quickstart)**<br>
+**[Further Reading](docs/further_reading.md)**<br>
+**[Build Instructions](docs/build.md)**<br>
+
+
+## Intro
+
+Use this README to get started with our Feature Flags (FF) SDK for Python. This guide outlines the basics of getting started with the SDK and provides a full code sample for you to try out. 
+This sample doesn’t include configuration options, for in depth steps and configuring the SDK, for example, disabling streaming or using our Relay Proxy, see the  [Python SDK Reference](https://ngdocs.harness.io/article/hwoxb6x2oe-python-sdk-reference).
+
+For a sample FF Python SDK project, see our test [test python project](examples/getting_started/getting_started.py).
+
+![FeatureFlags](https://github.com/harness/ff-python-server-sdk/raw/main/docs/images/ff-gui.png)
+
+## Requirements
+
+[Python 3.7](https://www.python.org/downloads/) or newer (python --version)<br>
+[pip](https://packaging.python.org/en/latest/tutorials/installing-packages/#id12)<br>
+<br>
+[For Mac users](https://opensource.com/article/19/5/python-3-default-mac) if you don't already have pyenv or something similar installed for managing python version<br>
+
+
+## Quickstart
+To follow along with our test code sample, make sure you’ve:
+
+- [Created a Feature Flag on the Harness Platform](https://ngdocs.harness.io/article/1j7pdkqh7j-create-a-feature-flag) called harnessappdemodarkmode
+- [Created a server SDK key and made a copy of it](https://ngdocs.harness.io/article/1j7pdkqh7j-create-a-feature-flag#step_3_create_an_sdk_key)
+- 
+### Install the SDK
+Install the python SDK using pip
+```python
+python -m pip install harness-featureflags
+```
+
+### Code Sample
+The following is a complete code example that you can use to test the `harnessappdemodarkmode` Flag you created on the Harness Platform. When you run the code it will:
+- Connect to the FF service.
+- Report the value of the Flag every 10 seconds until the connection is closed. Every time the harnessappdemodarkmode Flag is toggled on or off on the Harness Platform, the updated value is reported. 
+- Close the SDK.
+
+```python
+from featureflags.client import CfClient
+from featureflags.config import *
+from featureflags.evaluations.auth_target import Target
+from featureflags.util import log
+import os
+import time
+
+# API Key
+apiKey = os.getenv('FF_API_KEY', "changeme")
+
+# Flag Name
+flagName = os.getenv('FF_FLAG_NAME', "harnessappdemodarkmode")
+
+def main():    
+    # Create a Feature Flag Client
+    client = CfClient(apiKey)
+
+    # Create a target (different targets can get different results based on rules.  This include a custom attribute 'location')
+    target = Target(identifier='HT_1', name="Harness_Target_1", attributes={"location": "emea"})
+
+    # Loop forever reporting the state of the flag
+    while True:
+        result = client.bool_variation(flagName, target, False)
+        log.info("Flag variation %s", result)
+        time.sleep(10)
+
+
+if __name__ == "__main__":
+    main()
+```
+
+### Running the example
+
+```bash
+$ export FF_API_KEY=<your key here>
+$ python3 examples/getting_started/getting_started.py
+```
+
+### Running the example with Docker
+If you dont have the right version of python installed locally, or dont want to install the dependancies you can
+use docker to quickly get started
+
+```bash
+# Install the package
+docker run -v $(pwd):/app -w /app python:3.7-slim python -m pip install -t ./local  harness-featureflags
+
+# Run the script
+docker run  -e PYTHONPATH=/app/local -e FF_API_KEY=$FF_API_KEY -v $(pwd):/app -w /app python:3.7-slim python examples/getting_started/getting_started.py
+```
+
+### Additional Reading
+
+For further examples and config options, see the [Python SDK Reference](https://ngdocs.harness.io/article/hwoxb6x2oe-python-sdk-reference).
+
+For more information about Feature Flags, see our [Feature Flags documentation](https://ngdocs.harness.io/article/0a2u2ppp8s-getting-started-with-feature-flags).
+
+-------------------------
+[Harness](https://www.harness.io/) is a feature management platform that helps teams to build better software and to
+test features quicker.
+
+-------------------------
+
+
+
+=======
+History
+=======
+
+1.0.1 (2021-07-07)
+------------------
+
+* First release on PyPI.
```

### Comparing `harness-featureflags-1.1.9/README.md` & `harness-featureflags-1.2.0/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -61,24 +61,22 @@
 flagName = os.getenv('FF_FLAG_NAME', "harnessappdemodarkmode")
 
 def main():    
     # Create a Feature Flag Client
     client = CfClient(apiKey)
 
     # Create a target (different targets can get different results based on rules.  This include a custom attribute 'location')
-    target = Target(identifier='pythonSDK', name="PythonSDK", attributes={"location": "emea"})
+    target = Target(identifier='HT_1', name="Harness_Target_1", attributes={"location": "emea"})
 
     # Loop forever reporting the state of the flag
     while True:
         result = client.bool_variation(flagName, target, False)
         log.info("Flag variation %s", result)
         time.sleep(10)
 
-    close()
-
 
 if __name__ == "__main__":
     main()
 ```
 
 ### Running the example
```

### Comparing `harness-featureflags-1.1.9/docs/Makefile` & `harness-featureflags-1.2.0/docs/Makefile`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/docs/conf.py` & `harness-featureflags-1.2.0/docs/conf.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/docs/featureflags.api.default.rst` & `harness-featureflags-1.2.0/docs/featureflags.api.default.rst`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/docs/featureflags.api.rst` & `harness-featureflags-1.2.0/docs/featureflags.api.rst`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/docs/featureflags.evaluations.rst` & `harness-featureflags-1.2.0/docs/featureflags.evaluations.rst`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/docs/featureflags.ftypes.rst` & `harness-featureflags-1.2.0/docs/featureflags.ftypes.rst`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/docs/featureflags.models.rst` & `harness-featureflags-1.2.0/docs/featureflags.models.rst`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/docs/featureflags.rest.api.default.rst` & `harness-featureflags-1.2.0/docs/featureflags.rest.api.default.rst`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/docs/featureflags.rest.models.rst` & `harness-featureflags-1.2.0/docs/featureflags.rest.models.rst`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/docs/featureflags.rest.rst` & `harness-featureflags-1.2.0/docs/featureflags.rest.rst`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/docs/featureflags.rst` & `harness-featureflags-1.2.0/docs/featureflags.rst`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/docs/images/ff-gui.png` & `harness-featureflags-1.2.0/docs/images/ff-gui.png`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/docs/installation.rst` & `harness-featureflags-1.2.0/docs/installation.rst`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/docs/make.bat` & `harness-featureflags-1.2.0/docs/make.bat`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/api/client.py` & `harness-featureflags-1.2.0/featureflags/api/client.py`

 * *Files 6% similar despite different names*

```diff
@@ -8,15 +8,16 @@
     """A class for keeping track of data related to the API"""
 
     base_url: str
     events_url: str
     params: Dict[str, str] = attr.ib(factory=dict, kw_only=True)
     cookies: Dict[str, str] = attr.ib(factory=dict, kw_only=True)
     headers: Dict[str, str] = attr.ib(factory=dict, kw_only=True)
-    timeout: float = attr.ib(5.0, kw_only=True)
+    timeout: float = attr.ib(30.0, kw_only=True)
+    max_auth_retries: int
 
     def get_headers(self) -> Dict[str, str]:
         """Get headers to be used in all endpoints"""
         return {**self.headers}
 
     def with_headers(self, headers: Dict[str, str]) -> "Client":
         """Get a new client matching this one with additional headers"""
@@ -31,14 +32,17 @@
     def with_cookies(self, cookies: Dict[str, str]) -> "Client":
         """Get a new client matching this one with additional cookies"""
         return attr.evolve(self, cookies={**self.cookies, **cookies})
 
     def get_timeout(self) -> float:
         return self.timeout
 
+    def get_max_auth_retries(self) -> int:
+        return self.max_auth_retries
+
     def with_timeout(self, timeout: float) -> "Client":
         """
         Get a new client matching this one with a new timeout (in seconds)
         """
         return attr.evolve(self, timeout=timeout)
```

### Comparing `harness-featureflags-1.1.9/featureflags/api/default/authenticate.py` & `harness-featureflags-1.2.0/featureflags/api/default/authenticate.py`

 * *Files 22% similar despite different names*

```diff
@@ -1,21 +1,29 @@
 from typing import Any, Dict, Optional, Union
 
 import httpx
+from tenacity import (Retrying, retry_all, retry_if_result, stop_after_attempt,
+                      wait_exponential)
 
 from featureflags.api.client import Client
 from featureflags.api.types import Response
 from featureflags.models.authentication_request import AuthenticationRequest
 from featureflags.models.authentication_response import AuthenticationResponse
+from featureflags.sdk_logging_codes import warn_auth_retying
+from featureflags.util import log
+
+
+class UnrecoverableAuthenticationException(Exception):
+    pass
 
 
 def _get_kwargs(
-    *,
-    client: Client,
-    json_body: AuthenticationRequest,
+        *,
+        client: Client,
+        json_body: AuthenticationRequest,
 ) -> Dict[str, Any]:
     url = "{}/client/auth".format(client.base_url)
 
     headers: Dict[str, Any] = client.get_headers()
     cookies: Dict[str, Any] = client.get_cookies()
 
     json_json_body = json_body.to_dict()
@@ -26,100 +34,107 @@
         "cookies": cookies,
         "timeout": client.get_timeout(),
         "json": json_json_body,
     }
 
 
 def _parse_response(
-    *, response: httpx.Response
+        *, response: httpx.Response
 ) -> Optional[Union[AuthenticationResponse, None]]:
     if response.status_code == 200:
-        response_200 = AuthenticationResponse.from_dict(response.json())
-
-        return response_200
-    if response.status_code == 401:
-        response_401 = None
-
-        return response_401
-    if response.status_code == 403:
-        response_403 = None
-
-        return response_403
-    if response.status_code == 404:
-        response_404 = None
-
-        return response_404
-    if response.status_code == 500:
-        response_500 = None
-
-        return response_500
-    return None
+        return AuthenticationResponse.from_dict(response.json())
+    else:
+        raise UnrecoverableAuthenticationException(
+            f'Authentication failed on an unrecoverable error: {response}')
 
 
 def _build_response(
-    *, response: httpx.Response
+        *, response: httpx.Response
 ) -> Response[Union[AuthenticationResponse, None]]:
     return Response(
         status_code=response.status_code,
         content=response.content,
         headers=response.headers,
         parsed=_parse_response(response=response),
     )
 
 
 def sync_detailed(
-    *,
-    client: Client,
-    json_body: AuthenticationRequest,
+        *,
+        client: Client,
+        json_body: AuthenticationRequest,
 ) -> Response[Union[AuthenticationResponse, None]]:
     kwargs = _get_kwargs(
         client=client,
         json_body=json_body,
     )
+    max_auth_retries = client.get_max_auth_retries()
+    response = _post_request(kwargs, max_auth_retries)
+    return _build_response(response=response)
 
-    response = httpx.post(
-        **kwargs,
-    )
 
-    return _build_response(response=response)
+def handle_http_result(response):
+    code = response.status_code
+    if code in {408, 425, 429, 500, 502, 503, 504}:
+        return True
+    else:
+        log.error(
+            f'Authentication received HTTP code #{code} and '
+            'will not attempt to reconnect')
+        return False
+
+
+def _post_request(kwargs, max_auth_retries):
+    retryer = Retrying(
+        wait=wait_exponential(multiplier=1, min=4, max=10),
+        retry=retry_all(
+            retry_if_result(lambda response: response.status_code != 200),
+            retry_if_result(handle_http_result)
+        ),
+        before_sleep=lambda retry_state: warn_auth_retying(
+            retry_state.attempt_number,
+            retry_state.outcome.result()),
+        stop=stop_after_attempt(max_auth_retries),
+    )
+    return retryer(httpx.post, **kwargs)
 
 
 def sync(
-    *,
-    client: Client,
-    json_body: AuthenticationRequest,
+        *,
+        client: Client,
+        json_body: AuthenticationRequest,
 ) -> Optional[Union[AuthenticationResponse, None]]:
     """Used to retrieve all target segments for certain account id."""
 
     return sync_detailed(
         client=client,
         json_body=json_body,
     ).parsed
 
 
 async def asyncio_detailed(
-    *,
-    client: Client,
-    json_body: AuthenticationRequest,
+        *,
+        client: Client,
+        json_body: AuthenticationRequest,
 ) -> Response[Union[AuthenticationResponse, None]]:
     kwargs = _get_kwargs(
         client=client,
         json_body=json_body,
     )
 
     async with httpx.AsyncClient() as _client:
         response = await _client.post(**kwargs)
 
     return _build_response(response=response)
 
 
 async def asyncio(
-    *,
-    client: Client,
-    json_body: AuthenticationRequest,
+        *,
+        client: Client,
+        json_body: AuthenticationRequest,
 ) -> Optional[Union[AuthenticationResponse, None]]:
     """Used to retrieve all target segments for certain account id."""
 
     return (
         await asyncio_detailed(
             client=client,
             json_body=json_body,
```

### Comparing `harness-featureflags-1.1.9/featureflags/api/default/get_all_segments.py` & `harness-featureflags-1.2.0/featureflags/api/default/get_all_segments.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/api/default/get_feature_config.py` & `harness-featureflags-1.2.0/featureflags/api/default/get_feature_config.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/api/default/get_feature_config_by_identifier.py` & `harness-featureflags-1.2.0/featureflags/api/default/get_feature_config_by_identifier.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/api/default/get_segment_by_identifier.py` & `harness-featureflags-1.2.0/featureflags/api/default/get_segment_by_identifier.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/api/default/post_metrics.py` & `harness-featureflags-1.2.0/featureflags/api/default/post_metrics.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/api/default/stream.py` & `harness-featureflags-1.2.0/featureflags/api/default/stream.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/api/types.py` & `harness-featureflags-1.2.0/featureflags/api/types.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/client.py` & `harness-featureflags-1.2.0/featureflags/client.py`

 * *Files 16% similar despite different names*

```diff
@@ -1,40 +1,49 @@
 """Client for interacting with Harness FF server"""
 
 import threading
 from typing import Any, Callable, Dict, Optional
 
 from jwt import decode
+from tenacity import RetryError
 
+import featureflags.sdk_logging_codes as sdk_codes
 from featureflags.analytics import AnalyticsService
 from featureflags.evaluations.evaluator import Evaluator
 from featureflags.repository import Repository
 
 from .api.client import AuthenticatedClient, Client
-from .api.default.authenticate import AuthenticationRequest
+from .api.default.authenticate import (AuthenticationRequest,
+                                       UnrecoverableAuthenticationException)
 from .api.default.authenticate import sync as authenticate
 from .config import Config, default_config
 from .evaluations.auth_target import Target
 from .polling import PollingProcessor
 from .streaming import StreamProcessor
-from .util import log
 
 VERSION: str = "1.0"
 
 
+class MissingOrEmptyAPIKeyException(Exception):
+    pass
+
+
 class CfClient(object):
     def __init__(
             self, sdk_key: str,
             *options: Callable,
             config: Optional[Config] = None
     ):
         self._client: Optional[Client] = None
         #  The Client is considered initialized when flags and groups
         #  are loaded into cache.
         self._initialized = threading.Event()
+        # Keep track if initialization has failed due to authentication
+        # or a missing/empty API key.
+        self._initialized_failed = False
         self._auth_token: Optional[str] = None
         self._environment_id: Optional[str] = None
         self._sdk_key: Optional[str] = sdk_key
         self._config: Config = default_config
         self._cluster: str = '1'
 
         if config:
@@ -49,68 +58,94 @@
 
         self._repository = Repository(self._config.cache)
         self._evaluator = Evaluator(self._repository)
 
         self.run()
 
     def run(self):
-        self.authenticate()
+        try:
+            if self._sdk_key is None or self._sdk_key == "":
+                raise MissingOrEmptyAPIKeyException()
+            self.authenticate()
+            sdk_codes.info_sdk_auth_ok()
+            streaming_event = threading.Event()
+            polling_event = threading.Event()
 
-        streaming_event = threading.Event()
-        polling_event = threading.Event()
-
-        self._polling_processor = PollingProcessor(
-            client=self._client,
-            config=self._config,
-            environment_id=self._environment_id,
-            #  PollingProcessor is responsible for doing the initial
-            #  flag/group fetch and cache. So we allocate it the responsibility
-            #  for setting the Client is_initialized variable.
-            wait_for_initialization=self._initialized,
-            ready=polling_event,
-            stream_ready=streaming_event,
-            repository=self._repository
-        )
-        self._polling_processor.start()
-
-        if self._config.enable_stream:
-            self._stream = StreamProcessor(
-                repository=self._repository,
+            self._polling_processor = PollingProcessor(
                 client=self._client,
-                environment_id=self._environment_id,
-                api_key=self._sdk_key,
-                token=self._auth_token,
                 config=self._config,
-                ready=streaming_event,
-                poller=polling_event,
-                cluster=self._cluster,
+                environment_id=self._environment_id,
+                #  PollingProcessor is responsible for doing the initial
+                #  flag/group fetch and cache. So we allocate it the
+                #  responsibility
+                #  for setting the Client is_initialized variable.
+                wait_for_initialization=self._initialized,
+                ready=polling_event,
+                stream_ready=streaming_event,
+                repository=self._repository
             )
-            self._stream.start()
+            self._polling_processor.start()
 
-        if self._config.enable_analytics:
-            self._analytics = AnalyticsService(
-                config=self._config,
-                client=self._client,
-                environment=self._environment_id
-            )
+            if self._config.enable_stream:
+                self._stream = StreamProcessor(
+                    repository=self._repository,
+                    client=self._client,
+                    environment_id=self._environment_id,
+                    api_key=self._sdk_key,
+                    token=self._auth_token,
+                    config=self._config,
+                    ready=streaming_event,
+                    poller=polling_event,
+                    cluster=self._cluster,
+                )
+                self._stream.start()
+
+            if self._config.enable_analytics:
+                self._analytics = AnalyticsService(
+                    config=self._config,
+                    client=self._client,
+                    environment=self._environment_id
+                )
+
+        except RetryError:
+            sdk_codes.warn_auth_failed_exceed_retries()
+            sdk_codes.warn_failed_init_auth_error()
+            self._initialized_failed = True
+            # We just need to unblock the thread here
+            # in case wait_for_intialization was called. The SDK has already
+            # logged that authentication failed and defaults will be returned.
+            self._initialized.set()
+        except UnrecoverableAuthenticationException:
+            self._initialized_failed = True
+            sdk_codes.warn_auth_failed_srv_defaults()
+            sdk_codes.warn_failed_init_auth_error()
+            # Same again, unblock the thread.
+            self._initialized.set()
+        except MissingOrEmptyAPIKeyException:
+            self._initialized_failed = True
+            sdk_codes.wan_missing_sdk_key()
+            # And again, unblock the thread.
+            self._initialized.set()
 
     def wait_for_initialization(self):
-        log.debug("Waiting for initialization to finish")
         self._initialized.wait()
 
     def is_initialized(self):
+        if self._initialized_failed:
+            return False
         return self._initialized.is_set()
 
     def get_environment_id(self):
         return self._environment_id
 
     def authenticate(self):
         client = Client(
             base_url=self._config.base_url,
-            events_url=self._config.events_url
+            events_url=self._config.events_url,
+            max_auth_retries=self._config.max_auth_retries
         )
         body = AuthenticationRequest(api_key=self._sdk_key)
         response = authenticate(client=client, json_body=body)
         self._auth_token = response.auth_token
 
         decoded = decode(self._auth_token, options={
             "verify_signature": False})
@@ -120,83 +155,90 @@
             self._cluster = '1'
         self._client = AuthenticatedClient(
             base_url=self._config.base_url,
             events_url=self._config.events_url,
             token=self._auth_token,
             params={
                 'cluster': self._cluster
-            }
+            },
+            max_auth_retries=self._config.max_auth_retries
         )
-        self._client.with_headers({"User-Agent": "PythonSDK/" + VERSION})
+        # Additional headers used to track usage
+        additional_headers = {
+            "User-Agent": "PythonSDK/" + VERSION,
+            "Harness-SDK-Info": f'Python {VERSION} Server',
+            "Harness-EnvironmentID": self._environment_id,
+            "Harness-AccountID": decoded["accountID"]}
+        self._client = self._client.with_headers(additional_headers)
 
     def bool_variation(self, identifier: str, target: Target,
                        default: bool) -> bool:
         variation = self._evaluator.evaluate(identifier, target)
         # Only register metrics if analytics is enabled,
         # and sometimes when the SDK starts up we can
         # evaluate before the flag is cached which results in
         # an empty identifier.
         if self._config.enable_analytics and variation.identifier != "":
             self._analytics.enqueue(target, identifier, variation)
-        return variation.bool(default)
+        return variation.bool(target, identifier, default)
 
     def int_variation(self, identifier: str, target: Target,
                       default: int) -> int:
         variation = self._evaluator.evaluate(identifier, target)
         # Only register metrics if analytics is enabled,
         # and sometimes when the SDK starts up we can
         # evaluate before the flag is cached which results in
         # an empty identifier.
         if self._config.enable_analytics and variation.identifier != "":
             self._analytics.enqueue(target, identifier, variation)
-        return variation.int(default)
+        return variation.int(target, identifier, default)
 
     def number_variation(self, identifier: str, target: Target,
                          default: float) -> float:
         variation = self._evaluator.evaluate(
             identifier, target)
         # Only register metrics if analytics is enabled,
         # and sometimes when the SDK starts up we can
         # evaluate before the flag is cached which results in
         # an empty identifier.
         if self._config.enable_analytics and variation.identifier != "":
             self._analytics.enqueue(target, identifier, variation)
-        return variation.number(default)
+        return variation.number(target, identifier, default)
 
     def string_variation(self, identifier: str, target: Target,
                          default: str) -> str:
         variation = self._evaluator.evaluate(
             identifier, target)
         # Only register metrics if analytics is enabled,
         # and sometimes when the SDK starts up we can
         # evaluate before the flag is cached which results in
         # an empty identifier.
         if self._config.enable_analytics and variation.identifier != "":
             self._analytics.enqueue(target, identifier, variation)
-        return variation.string(default)
+        return variation.string(target, identifier, default)
 
     def json_variation(self, identifier: str, target: Target,
                        default: Dict[str, Any]) -> Dict[str, Any]:
         variation = self._evaluator.evaluate(identifier, target)
         # Only register metrics if analytics is enabled,
         # and sometimes when the SDK starts up we can
         # evaluate before the flag is cached which results in
         # an empty identifier.
         if self._config.enable_analytics and variation.identifier != "":
             self._analytics.enqueue(target, identifier, variation)
-        return variation.json(default)
+        return variation.json(target, identifier, default)
 
     def close(self):
-        log.info('closing sdk client')
+        sdk_codes.info_sdk_start_close()
         self._polling_processor.stop()
         if self._config.enable_stream:
             self._stream.stop()
 
         if self._config.enable_analytics:
             self._analytics.close()
-        log.info('All threads finished')
+        sdk_codes.info_sdk_close_success()
 
     def __enter__(self):
         return self
 
     def __exit__(self, type, value, traceback):
         self.close()
```

### Comparing `harness-featureflags-1.1.9/featureflags/config.py` & `harness-featureflags-1.2.0/featureflags/config.py`

 * *Files 24% similar despite different names*

```diff
@@ -1,14 +1,15 @@
 """Configuration is a base class that has default values that you can change
 during the instance of the client class"""
 
 from typing import Callable
 
 from .interface import Cache
 from .lru_cache import LRUCache
+from .util import log
 
 BASE_URL = "https://config.ff.harness.io/api/1.0"
 EVENTS_URL = "https://events.ff.harness.io/api/1.0"
 MINUTE = 60
 PULL_INTERVAL = 1 * MINUTE
 PERSIST_INTERVAL = 1 * MINUTE
 EVENTS_SYNC_INTERVAL = 1 * MINUTE
@@ -21,27 +22,35 @@
             events_url: str = EVENTS_URL,
             pull_interval: int = PULL_INTERVAL,
             persist_interval: int = PERSIST_INTERVAL,
             events_sync_interval: int = EVENTS_SYNC_INTERVAL,
             cache: Cache = None,
             store: object = None,
             enable_stream: bool = True,
-            enable_analytics: bool = True
+            enable_analytics: bool = True,
+            max_auth_retries: int = 10
     ):
         self.base_url = base_url
         self.events_url = events_url
         self.pull_interval = pull_interval
         self.persist_interval = persist_interval
-        self.events_sync_interval = events_sync_interval
+        if events_sync_interval < EVENTS_SYNC_INTERVAL:
+            log.warning("Metrics events sync interval cannot be lower than "
+                        "60 seconds. Default of 60 seconds will be used")
+            self.events_sync_interval = EVENTS_SYNC_INTERVAL
+        else:
+            self.events_sync_interval = events_sync_interval
+
         self.cache = cache
         if self.cache is None:
             self.cache = LRUCache()
         self.store = store
         self.enable_stream = enable_stream
         self.enable_analytics = enable_analytics
+        self.max_auth_retries = max_auth_retries
 
 
 default_config = Config()
 
 
 def with_base_url(base_url: str) -> Callable:
     def func(config: Config) -> None:
@@ -72,7 +81,14 @@
 
 
 def with_pull_interval(value: int) -> Callable:
     def func(config: Config) -> None:
         config.pull_interval = value
 
     return func
+
+
+def with_max_auth_retries(value: int) -> Callable:
+    def func(config: Config) -> None:
+        config.max_auth_retries = value
+
+    return func
```

### Comparing `harness-featureflags-1.1.9/featureflags/evaluations/auth_target.py` & `harness-featureflags-1.2.0/featureflags/evaluations/auth_target.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/evaluations/clause.py` & `harness-featureflags-1.2.0/featureflags/evaluations/clause.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/evaluations/distribution.py` & `harness-featureflags-1.2.0/featureflags/evaluations/distribution.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/evaluations/evaluator.py` & `harness-featureflags-1.2.0/featureflags/evaluations/evaluator.py`

 * *Files 2% similar despite different names*

```diff
@@ -291,16 +291,17 @@
                 # valid value of the pre requisite FF
                 log.info('Pre requisite flag %s should have the variations %s',
                          config.feature, pqs.variations)
 
                 if isinstance(variation, Unset) or variation.identifier \
                         not in pqs.variations:
                     return False
-                else:
-                    return self._check_prerequisite(config, target)
+                # Check for any nested prerequisites
+                if not self._check_prerequisite(config, target):
+                    return False
         return True
 
     def evaluate(self, identifier: str, target: Target) -> Variation:
         fc = self.provider.get_flag(identifier)
         if not fc:
             return Variation(identifier="", value=None)
```

### Comparing `harness-featureflags-1.1.9/featureflags/evaluations/feature.py` & `harness-featureflags-1.2.0/featureflags/evaluations/feature.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/evaluations/prerequisite.py` & `harness-featureflags-1.2.0/featureflags/evaluations/prerequisite.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/evaluations/segment.py` & `harness-featureflags-1.2.0/featureflags/evaluations/segment.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/evaluations/serve.py` & `harness-featureflags-1.2.0/featureflags/evaluations/serve.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/evaluations/serving_rule.py` & `harness-featureflags-1.2.0/featureflags/evaluations/serving_rule.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/evaluations/tag.py` & `harness-featureflags-1.2.0/featureflags/evaluations/tag.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/evaluations/target.py` & `harness-featureflags-1.2.0/featureflags/evaluations/target.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/evaluations/target_attributes.py` & `harness-featureflags-1.2.0/featureflags/evaluations/target_attributes.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/evaluations/target_map.py` & `harness-featureflags-1.2.0/featureflags/evaluations/target_map.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/evaluations/variation.py` & `harness-featureflags-1.2.0/featureflags/models/authentication_request.py`

 * *Files 26% similar despite different names*

```diff
@@ -1,99 +1,71 @@
-import json
 from typing import Any, Dict, List, Type, TypeVar, Union
-from xmlrpc.client import boolean
 
 import attr
 
-from featureflags.models import UNSET, Unset
+from .authentication_request_target import AuthenticationRequestTarget
+from .unset import UNSET, Unset
 
-T = TypeVar("T", bound="Variation")
+T = TypeVar("T", bound="AuthenticationRequest")
 
 
 @attr.s(auto_attribs=True)
-class Variation(object):
-    identifier: str
-    value: Union[str, None]
-    name: Union[Unset, str] = UNSET
-    description: Union[Unset, str] = UNSET
-    additional_properties: Dict[str, Any] = attr.ib(init=False, factory=dict)
+class AuthenticationRequest:
+    """ """
 
-    def bool(self, default: bool = False) -> bool:
-        if self.value:
-            return self.value.lower() == "true"
-        return default
-
-    def string(self, default: str) -> str:
-        return self.value or default
-
-    def number(self, default: float) -> float:
-        if self.value:
-            return float(self.value)
-        return default
-
-    def int(self, default: int) -> int:
-        if self.value:
-            return int(self.value)
-        return default
-
-    def json(self, default: dict) -> dict:
-        if self.value:
-            return json.loads(self.value)
-        return default
+    api_key: str
+    target: Union[Unset, AuthenticationRequestTarget] = UNSET
+    additional_properties: Dict[str, Any] = attr.ib(init=False, factory=dict)
 
     def to_dict(self) -> Dict[str, Any]:
-        identifier = self.identifier
-        value = self.value
-        name = self.name
-        description = self.description
+        api_key = self.api_key
+        target: Union[Unset, Dict[str, Any]] = UNSET
+        if not isinstance(self.target, Unset):
+            target = self.target.to_dict()
 
         field_dict: Dict[str, Any] = {}
         field_dict.update(self.additional_properties)
         field_dict.update(
             {
-                "identifier": identifier,
-                "value": value,
+                "apiKey": api_key,
             }
         )
-        if name is not UNSET:
-            field_dict["name"] = name
-        if description is not UNSET:
-            field_dict["description"] = description
+        if target is not UNSET:
+            field_dict["target"] = target
 
         return field_dict
 
     @classmethod
     def from_dict(cls: Type[T], src_dict: Dict[str, Any]) -> T:
         d = src_dict.copy()
-        identifier = d.pop("identifier")
-
-        value = d.pop("value")
-
-        name = d.pop("name", UNSET)
-
-        description = d.pop("description", UNSET)
+        api_key = d.pop("apiKey")
 
-        variation = cls(
-            identifier=identifier,
-            value=value,
-            name=name,
-            description=description,
+        _target = d.pop("target", UNSET)
+        target: Union[Unset, AuthenticationRequestTarget]
+        if isinstance(_target, Unset):
+            target = UNSET
+        else:
+            target = AuthenticationRequestTarget.from_dict(_target)
+
+        authentication_request = cls(
+            api_key=api_key,
+            target=target,
         )
 
-        variation.additional_properties = d
-        return variation
+        authentication_request.additional_properties = d
+        return authentication_request
 
     @property
     def additional_keys(self) -> List[str]:
         return list(self.additional_properties.keys())
 
     def __getitem__(self, key: str) -> Any:
         return self.additional_properties[key]
 
     def __setitem__(self, key: str, value: Any) -> None:
         self.additional_properties[key] = value
 
     def __delitem__(self, key: str) -> None:
         del self.additional_properties[key]
 
-    def __contains__(self, key: str) -> boolean:
+    def __contains__(self, key: str) -> bool:
         return key in self.additional_properties
```

### Comparing `harness-featureflags-1.1.9/featureflags/evaluations/variation_map.py` & `harness-featureflags-1.2.0/featureflags/evaluations/variation_map.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/evaluations/weighted_variation.py` & `harness-featureflags-1.2.0/featureflags/evaluations/weighted_variation.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/ftypes/boolean.py` & `harness-featureflags-1.2.0/featureflags/ftypes/boolean.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/ftypes/integer.py` & `harness-featureflags-1.2.0/featureflags/ftypes/integer.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/ftypes/interface.py` & `harness-featureflags-1.2.0/featureflags/ftypes/interface.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/ftypes/json.py` & `harness-featureflags-1.2.0/featureflags/ftypes/json.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/ftypes/number.py` & `harness-featureflags-1.2.0/featureflags/ftypes/number.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/ftypes/string.py` & `harness-featureflags-1.2.0/featureflags/ftypes/string.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/interface.py` & `harness-featureflags-1.2.0/featureflags/interface.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/lru_cache.py` & `harness-featureflags-1.2.0/featureflags/lru_cache.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/models/__init__.py` & `harness-featureflags-1.2.0/featureflags/models/__init__.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/models/authentication_request_target.py` & `harness-featureflags-1.2.0/featureflags/models/authentication_request_target.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/models/authentication_request_target_attributes.py` & `harness-featureflags-1.2.0/featureflags/models/authentication_request_target_attributes.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/models/authentication_response.py` & `harness-featureflags-1.2.0/featureflags/models/authentication_response.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/models/error.py` & `harness-featureflags-1.2.0/featureflags/models/error.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/models/key_value.py` & `harness-featureflags-1.2.0/featureflags/models/key_value.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/models/message.py` & `harness-featureflags-1.2.0/featureflags/models/message.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/models/metrics.py` & `harness-featureflags-1.2.0/featureflags/models/metrics.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/models/metrics_data.py` & `harness-featureflags-1.2.0/featureflags/models/metrics_data.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/models/pagination.py` & `harness-featureflags-1.2.0/featureflags/models/pagination.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/models/target_data.py` & `harness-featureflags-1.2.0/featureflags/models/target_data.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/persisting.py` & `harness-featureflags-1.2.0/featureflags/persisting.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/polling.py` & `harness-featureflags-1.2.0/featureflags/polling.py`

 * *Files 11% similar despite different names*

```diff
@@ -3,14 +3,16 @@
 
 from featureflags.api.client import AuthenticatedClient
 from featureflags.repository import DataProviderInterface
 
 from .api.default.get_all_segments import sync as retrieve_segments
 from .api.default.get_feature_config import sync as retrieve_flags
 from .config import Config
+from .sdk_logging_codes import (info_poll_started, info_polling_stopped,
+                                info_sdk_init_ok, info_sdk_init_waiting)
 from .util import log
 
 
 class PollingProcessor(Thread):
 
     def __init__(self, client: AuthenticatedClient, config: Config,
                  environment_id: str, wait_for_initialization: Event,
@@ -35,40 +37,39 @@
                             str(self.__config.pull_interval) +
                             " setting to 60")
                 self.__config.pull_interval = 60
 
             self.__running = True
             #  Get initial flags and groups
             try:
+                info_sdk_init_waiting()
                 log.info("Fetching initial target segments and flags")
                 self.retrieve_flags_and_segments()
                 log.info("Initial target segments and flags fetched. "
                          "PollingProcessor will start in: " +
                          str(self.__config.pull_interval) + " seconds")
                 #  Segments and flags have been cached so
                 #  mark the Client as initialised.
                 self.__wait_for_initialization.set()
-                log.debug("CfClient initialized")
+                info_sdk_init_ok()
             except Exception as ex:
                 log.exception(
                     'Error: Exception encountered when '
                     'getting initial flags and segments. %s',
                     ex
                 )
             #  Sleep for an interval before going into the polling loop.
             time.sleep(self.__config.pull_interval)
-            log.info("Starting PollingProcessor with request interval: " +
-                     str(self.__config.pull_interval))
+            info_poll_started(self.__config.pull_interval)
             while self.__running:
                 start_time = time.time()
                 try:
                     if self.__config.enable_stream and \
                             self.__stream_ready.is_set():
-                        log.debug('Poller will be paused because' +
-                                  ' streaming mode is active')
+                        info_polling_stopped('streaming mode is active')
                         # on stream disconnect, make sure flags are in sync
                         self.retrieve_flags_and_segments()
                         #  Block until ready.set() is called
                         self.__ready.wait()
                         log.debug('Poller resuming ')
                     else:
                         self.retrieve_flags_and_segments()
@@ -83,16 +84,16 @@
                 if elapsed < self.__config.pull_interval:
                     log.info("Poller sleeping for " +
                              (self.__config.pull_interval - elapsed).__str__())
                     " seconds"
                     time.sleep(self.__config.pull_interval - elapsed)
 
     def stop(self):
-        log.info("Stopping PollingProcessor")
         self.__running = False
+        info_polling_stopped("Client was closed")
 
     def retrieve_flags_and_segments(self):
         t1 = Thread(target=self.__retrieve_segments)
         t2 = Thread(target=self.__retrieve_flags)
         t1.start()
         t2.start()
         t1.join()
```

### Comparing `harness-featureflags-1.1.9/featureflags/repository.py` & `harness-featureflags-1.2.0/featureflags/repository.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/featureflags/sse_client.py` & `harness-featureflags-1.2.0/featureflags/sse_client.py`

 * *Files 7% similar despite different names*

```diff
@@ -105,15 +105,26 @@
             try:
                 next_chunk = next(self.resp_iterator)
                 if not next_chunk:
                     raise EOFError()
                 self.buf += self.decoder.decode(next_chunk)
 
             except (StopIteration, requests.RequestException, EOFError) as e:
-                log.error(e)
+                if isinstance(e, StopIteration):
+                    log.error("Error when iterating through stream messages, "
+                              "attempting to resume")
+
+                if isinstance(e, EOFError):
+                    log.error("Received unexpected EOF from stream, "
+                              "attempting to reconnect")
+
+                if isinstance(e, requests.RequestException):
+                    log.error("Error encountered in stream, "
+                              "attempting to reconnect: %s", e)
+
                 time.sleep(self.retry / 1000.0)
                 self._connect()
 
                 # The SSE spec only supports resuming from a whole message, so
                 # if we have half a message we should throw it out.
                 head, sep, _ = self.buf.rpartition("\n")
                 self.buf = head + sep
```

### Comparing `harness-featureflags-1.1.9/featureflags/streaming.py` & `harness-featureflags-1.2.0/featureflags/streaming.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,21 +1,25 @@
 import random
 import threading
 import time
 from threading import Thread
-from typing import List, Union
+from typing import Union
 
 from featureflags.repository import DataProviderInterface
 
 from .api.client import AuthenticatedClient
 from .api.default.get_feature_config_by_identifier import \
     sync as get_feature_config
 from .api.default.get_segment_by_identifier import sync as get_target_segment
 from .config import Config
 from .models.message import Message
+from .sdk_logging_codes import (info_stream_connected,
+                                info_stream_event_received,
+                                info_stream_stopped, warn_stream_disconnected,
+                                warn_stream_retrying)
 from .sse_client import SSEClient
 from .util import log
 
 BACK_OFF_IN_SECONDS = 5
 
 
 class StreamProcessor(Thread):
@@ -33,49 +37,48 @@
         self._ready = ready
         self.poller = poller
         self._client = client
         self._environment_id = environment_id
         self._api_key = api_key
         self._token = token
         self._stream_url = f'{config.base_url}/stream?cluster={cluster}'
-        self._msg_processors: List[Union[FlagMsgProcessor,
-                                         SegmentMsgProcessor]] = []
         self._repository = repository
 
     def run(self):
         log.info("Starting StreamingProcessor connecting to uri: " +
                  self._stream_url)
         self._running = True
         retries = 0
         while self._running:
             try:
                 messages = self._connect()
+                info_stream_connected()
                 self.poller.clear()  # were streaming now, so tell any poller
                 # threads calling wait to wait...
                 self._ready.set()
                 retries = 0  # reset the retry counter
                 for msg in messages:
                     if not self._running:
                         break
                     if msg.data:
-                        log.info("message received %s", msg.data)
+                        info_stream_event_received(msg.data)
                         message = Message.from_str(msg.data)
                         self.process_message(message)
                     if self._ready.is_set() is False:
                         self._ready.set()
             except Exception as e:
-                log.error("Unexpected error on stream connection: %s", e)
+                warn_stream_disconnected(e)
                 # Signal the poller than it should start due to stream error.
                 if self.poller.is_set() is False:
                     self.poller.set()
 
                 # Calculate back of sleep
                 sleep = (BACK_OFF_IN_SECONDS * 2 ** retries +
                          random.uniform(0, 1))
-                log.info(f"retrying stream connection in {sleep.__str__()}s")
+                warn_stream_retrying(f'{sleep.__str__()}s')
                 time.sleep(sleep)
                 retries += 1
 
     def _connect(self) -> SSEClient:
         return SSEClient(self._stream_url, headers={
             'Authorization': f'Bearer {self._token}',
             'API-Key': self._api_key
@@ -95,21 +98,18 @@
                 repository=self._repository,
                 client=self._client,
                 environment_id=self._environment_id,
                 msg=msg
             )
         if processor:
             processor.start()
-            self._msg_processors.append(processor)
 
     def stop(self):
-        log.info("Stopping stream processor and msg processors")
-        for processor in self._msg_processors:
-            processor.stop()
         self._running = False
+        info_stream_stopped()
 
 
 class FlagMsgProcessor(Thread):
 
     def __init__(self, repository: DataProviderInterface,
                  client: AuthenticatedClient,
                  environment_id: str, msg: Message):
```

### Comparing `harness-featureflags-1.1.9/harness_featureflags.egg-info/PKG-INFO` & `harness-featureflags-1.2.0/harness_featureflags.egg-info/PKG-INFO`

 * *Files 16% similar despite different names*

```diff
@@ -1,145 +1,144 @@
 Metadata-Version: 2.1
 Name: harness-featureflags
-Version: 1.1.9
+Version: 1.2.0
 Summary: Feature flag server SDK for python
 Home-page: https://github.com/harness/ff-python-server-sdk
 Author: Enver Bisevac
 Author-email: enver.bisevac@harness.io
 License: Apache Software License 2.0
-Description: Python SDK For Harness Feature Flags
-        ========================
-        
-        [![pypi](https://img.shields.io/pypi/v/harness-featureflags.svg)](https://pypi.python.org/pypi/harness-featureflags)
-        
-        ## Table of Contents
-        **[Intro](#Intro)**<br>
-        **[Requirements](#Requirements)**<br>
-        **[Quickstart](#Quickstart)**<br>
-        **[Further Reading](docs/further_reading.md)**<br>
-        **[Build Instructions](docs/build.md)**<br>
-        
-        
-        ## Intro
-        
-        Use this README to get started with our Feature Flags (FF) SDK for Python. This guide outlines the basics of getting started with the SDK and provides a full code sample for you to try out. 
-        This sample doesn’t include configuration options, for in depth steps and configuring the SDK, for example, disabling streaming or using our Relay Proxy, see the  [Python SDK Reference](https://ngdocs.harness.io/article/hwoxb6x2oe-python-sdk-reference).
-        
-        For a sample FF Python SDK project, see our test [test python project](examples/getting_started/getting_started.py).
-        
-        ![FeatureFlags](https://github.com/harness/ff-python-server-sdk/raw/main/docs/images/ff-gui.png)
-        
-        ## Requirements
-        
-        [Python 3.7](https://www.python.org/downloads/) or newer (python --version)<br>
-        [pip](https://packaging.python.org/en/latest/tutorials/installing-packages/#id12)<br>
-        <br>
-        [For Mac users](https://opensource.com/article/19/5/python-3-default-mac) if you don't already have pyenv or something similar installed for managing python version<br>
-        
-        
-        ## Quickstart
-        To follow along with our test code sample, make sure you’ve:
-        
-        - [Created a Feature Flag on the Harness Platform](https://ngdocs.harness.io/article/1j7pdkqh7j-create-a-feature-flag) called harnessappdemodarkmode
-        - [Created a server SDK key and made a copy of it](https://ngdocs.harness.io/article/1j7pdkqh7j-create-a-feature-flag#step_3_create_an_sdk_key)
-        - 
-        ### Install the SDK
-        Install the python SDK using pip
-        ```python
-        python -m pip install harness-featureflags
-        ```
-        
-        ### Code Sample
-        The following is a complete code example that you can use to test the `harnessappdemodarkmode` Flag you created on the Harness Platform. When you run the code it will:
-        - Connect to the FF service.
-        - Report the value of the Flag every 10 seconds until the connection is closed. Every time the harnessappdemodarkmode Flag is toggled on or off on the Harness Platform, the updated value is reported. 
-        - Close the SDK.
-        
-        ```python
-        from featureflags.client import CfClient
-        from featureflags.config import *
-        from featureflags.evaluations.auth_target import Target
-        from featureflags.util import log
-        import os
-        import time
-        
-        # API Key
-        apiKey = os.getenv('FF_API_KEY', "changeme")
-        
-        # Flag Name
-        flagName = os.getenv('FF_FLAG_NAME', "harnessappdemodarkmode")
-        
-        def main():    
-            # Create a Feature Flag Client
-            client = CfClient(apiKey)
-        
-            # Create a target (different targets can get different results based on rules.  This include a custom attribute 'location')
-            target = Target(identifier='pythonSDK', name="PythonSDK", attributes={"location": "emea"})
-        
-            # Loop forever reporting the state of the flag
-            while True:
-                result = client.bool_variation(flagName, target, False)
-                log.info("Flag variation %s", result)
-                time.sleep(10)
-        
-            close()
-        
-        
-        if __name__ == "__main__":
-            main()
-        ```
-        
-        ### Running the example
-        
-        ```bash
-        $ export FF_API_KEY=<your key here>
-        $ python3 examples/getting_started/getting_started.py
-        ```
-        
-        ### Running the example with Docker
-        If you dont have the right version of python installed locally, or dont want to install the dependancies you can
-        use docker to quickly get started
-        
-        ```bash
-        # Install the package
-        docker run -v $(pwd):/app -w /app python:3.7-slim python -m pip install -t ./local  harness-featureflags
-        
-        # Run the script
-        docker run  -e PYTHONPATH=/app/local -e FF_API_KEY=$FF_API_KEY -v $(pwd):/app -w /app python:3.7-slim python examples/getting_started/getting_started.py
-        ```
-        
-        ### Additional Reading
-        
-        For further examples and config options, see the [Python SDK Reference](https://ngdocs.harness.io/article/hwoxb6x2oe-python-sdk-reference).
-        
-        For more information about Feature Flags, see our [Feature Flags documentation](https://ngdocs.harness.io/article/0a2u2ppp8s-getting-started-with-feature-flags).
-        
-        -------------------------
-        [Harness](https://www.harness.io/) is a feature management platform that helps teams to build better software and to
-        test features quicker.
-        
-        -------------------------
-        
-        
-        
-        =======
-        History
-        =======
-        
-        1.0.1 (2021-07-07)
-        ------------------
-        
-        * First release on PyPI.
-        
 Keywords: featureflags
-Platform: UNKNOWN
 Classifier: Development Status :: 2 - Pre-Alpha
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: Apache Software License
 Classifier: Natural Language :: English
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.5
 Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Requires-Python: >=3.5
 Description-Content-Type: text/markdown
+License-File: LICENSE
+License-File: AUTHORS.rst
+
+Python SDK For Harness Feature Flags
+========================
+
+[![pypi](https://img.shields.io/pypi/v/harness-featureflags.svg)](https://pypi.python.org/pypi/harness-featureflags)
+
+## Table of Contents
+**[Intro](#Intro)**<br>
+**[Requirements](#Requirements)**<br>
+**[Quickstart](#Quickstart)**<br>
+**[Further Reading](docs/further_reading.md)**<br>
+**[Build Instructions](docs/build.md)**<br>
+
+
+## Intro
+
+Use this README to get started with our Feature Flags (FF) SDK for Python. This guide outlines the basics of getting started with the SDK and provides a full code sample for you to try out. 
+This sample doesn’t include configuration options, for in depth steps and configuring the SDK, for example, disabling streaming or using our Relay Proxy, see the  [Python SDK Reference](https://ngdocs.harness.io/article/hwoxb6x2oe-python-sdk-reference).
+
+For a sample FF Python SDK project, see our test [test python project](examples/getting_started/getting_started.py).
+
+![FeatureFlags](https://github.com/harness/ff-python-server-sdk/raw/main/docs/images/ff-gui.png)
+
+## Requirements
+
+[Python 3.7](https://www.python.org/downloads/) or newer (python --version)<br>
+[pip](https://packaging.python.org/en/latest/tutorials/installing-packages/#id12)<br>
+<br>
+[For Mac users](https://opensource.com/article/19/5/python-3-default-mac) if you don't already have pyenv or something similar installed for managing python version<br>
+
+
+## Quickstart
+To follow along with our test code sample, make sure you’ve:
+
+- [Created a Feature Flag on the Harness Platform](https://ngdocs.harness.io/article/1j7pdkqh7j-create-a-feature-flag) called harnessappdemodarkmode
+- [Created a server SDK key and made a copy of it](https://ngdocs.harness.io/article/1j7pdkqh7j-create-a-feature-flag#step_3_create_an_sdk_key)
+- 
+### Install the SDK
+Install the python SDK using pip
+```python
+python -m pip install harness-featureflags
+```
+
+### Code Sample
+The following is a complete code example that you can use to test the `harnessappdemodarkmode` Flag you created on the Harness Platform. When you run the code it will:
+- Connect to the FF service.
+- Report the value of the Flag every 10 seconds until the connection is closed. Every time the harnessappdemodarkmode Flag is toggled on or off on the Harness Platform, the updated value is reported. 
+- Close the SDK.
+
+```python
+from featureflags.client import CfClient
+from featureflags.config import *
+from featureflags.evaluations.auth_target import Target
+from featureflags.util import log
+import os
+import time
+
+# API Key
+apiKey = os.getenv('FF_API_KEY', "changeme")
+
+# Flag Name
+flagName = os.getenv('FF_FLAG_NAME', "harnessappdemodarkmode")
+
+def main():    
+    # Create a Feature Flag Client
+    client = CfClient(apiKey)
+
+    # Create a target (different targets can get different results based on rules.  This include a custom attribute 'location')
+    target = Target(identifier='HT_1', name="Harness_Target_1", attributes={"location": "emea"})
+
+    # Loop forever reporting the state of the flag
+    while True:
+        result = client.bool_variation(flagName, target, False)
+        log.info("Flag variation %s", result)
+        time.sleep(10)
+
+
+if __name__ == "__main__":
+    main()
+```
+
+### Running the example
+
+```bash
+$ export FF_API_KEY=<your key here>
+$ python3 examples/getting_started/getting_started.py
+```
+
+### Running the example with Docker
+If you dont have the right version of python installed locally, or dont want to install the dependancies you can
+use docker to quickly get started
+
+```bash
+# Install the package
+docker run -v $(pwd):/app -w /app python:3.7-slim python -m pip install -t ./local  harness-featureflags
+
+# Run the script
+docker run  -e PYTHONPATH=/app/local -e FF_API_KEY=$FF_API_KEY -v $(pwd):/app -w /app python:3.7-slim python examples/getting_started/getting_started.py
+```
+
+### Additional Reading
+
+For further examples and config options, see the [Python SDK Reference](https://ngdocs.harness.io/article/hwoxb6x2oe-python-sdk-reference).
+
+For more information about Feature Flags, see our [Feature Flags documentation](https://ngdocs.harness.io/article/0a2u2ppp8s-getting-started-with-feature-flags).
+
+-------------------------
+[Harness](https://www.harness.io/) is a feature management platform that helps teams to build better software and to
+test features quicker.
+
+-------------------------
+
+
+
+=======
+History
+=======
+
+1.0.1 (2021-07-07)
+------------------
+
+* First release on PyPI.
```

### Comparing `harness-featureflags-1.1.9/harness_featureflags.egg-info/SOURCES.txt` & `harness-featureflags-1.2.0/harness_featureflags.egg-info/SOURCES.txt`

 * *Files 0% similar despite different names*

```diff
@@ -35,14 +35,15 @@
 featureflags/client.py
 featureflags/config.py
 featureflags/interface.py
 featureflags/lru_cache.py
 featureflags/persisting.py
 featureflags/polling.py
 featureflags/repository.py
+featureflags/sdk_logging_codes.py
 featureflags/sse_client.py
 featureflags/streaming.py
 featureflags/util.py
 featureflags/api/__init__.py
 featureflags/api/client.py
 featureflags/api/types.py
 featureflags/api/default/__init__.py
@@ -203,12 +204,13 @@
 tests/unit/test_boolean.py
 tests/unit/test_clause.py
 tests/unit/test_evaluator.py
 tests/unit/test_feature.py
 tests/unit/test_integer.py
 tests/unit/test_lru.py
 tests/unit/test_number.py
+tests/unit/test_sdk_logging_codes.py
 tests/unit/test_sse_client.py
 tests/unit/test_string.py
 tests/unit/test_target.py
 tests/unit/test_utils.py
 tests/unit/test_variation.py
```

### Comparing `harness-featureflags-1.1.9/setup.py` & `harness-featureflags-1.2.0/setup.py`

 * *Files 5% similar despite different names*

```diff
@@ -9,19 +9,20 @@
 with open("README.md") as readme_file:
     readme = readme_file.read()
 
 with open("HISTORY.rst") as history_file:
     history = history_file.read()
 
 requirements = [
-    "httpx>=0.23.0",
+    "httpx>=0.24.1",
     "pyjwt>=2.4.0",
     "attrs>=21.2.0",
     "mmh3>=3.0.0",
-    "requests>=2.25.1"
+    "requests>=2.25.1",
+    "tenacity==8.2.2"
 ]
 
 setup_requirements = [
     "pytest-runner",
 ]
 
 test_requirements = [
@@ -52,10 +53,10 @@
     keywords="featureflags",
     name="harness-featureflags",
     packages=find_packages(include=["featureflags", "featureflags.*"]),
     setup_requires=setup_requirements,
     test_suite="tests",
     tests_require=test_requirements,
     url="https://github.com/harness/ff-python-server-sdk",
-    version='1.1.9',
+    version='1.2.0',
     zip_safe=False,
 )
```

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/Makefile` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/Makefile`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/README.md` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/README.md`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/client-v1.yaml` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/client-v1.yaml`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_Bool_State_Disabled_On_False_Off_False_Should_Return_False.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_Bool_State_Disabled_On_False_Off_False_Should_Return_False.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_Bool_State_Disabled_On_False_Off_True_Should_Return_True.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_Bool_State_Disabled_On_False_Off_True_Should_Return_True.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_Bool_State_Disabled_On_True_Off_False_Should_Return_False.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_Bool_State_Disabled_On_True_Off_False_Should_Return_False.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_Bool_State_Disabled_On_True_Off_True_Should_Return_True.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_Bool_State_Disabled_On_True_Off_True_Should_Return_True.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_JSON_State_Disabled_On_complexJSON_Off_emptyJSON_Should_Return_validJSON.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_JSON_State_Disabled_On_complexJSON_Off_emptyJSON_Should_Return_validJSON.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_JSON_State_Disabled_On_validJSON_Off_emptyJSON_Should_Return_emptyJSON.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_JSON_State_Disabled_On_validJSON_Off_emptyJSON_Should_Return_emptyJSON.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_Number_State_Disabled_On_011_Off_2_Should_Return_2.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_Number_State_Disabled_On_011_Off_2_Should_Return_2.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_Number_State_Disabled_On_324523_Off_011_Should_Return_011.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_Number_State_Disabled_On_324523_Off_011_Should_Return_011.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_String_State_Disabled_On_sonnet19_Off_sonnet53_Should_Return_sonnet53.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_String_State_Disabled_On_sonnet19_Off_sonnet53_Should_Return_sonnet53.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_String_State_Disabled_On_sonnet53_Off_sonnet19_Should_Return_sonnet19.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOffRules/DefaultOffRules_Type_String_State_Disabled_On_sonnet53_Off_sonnet19_Should_Return_sonnet19.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_Bool_State_Enabled_On_False_Off_False_Should_Return_False.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_Bool_State_Enabled_On_False_Off_False_Should_Return_False.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_Bool_State_Enabled_On_False_Off_True_Should_Return_True.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_Bool_State_Enabled_On_False_Off_True_Should_Return_True.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_Bool_State_Enabled_On_True_Off_False_Should_Return_False.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_Bool_State_Enabled_On_True_Off_False_Should_Return_False.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_Bool_State_Enabled_On_True_Off_True_Should_Return_True.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_Bool_State_Enabled_On_True_Off_True_Should_Return_True.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_JSON_State_Enabled_On_complexJSON_Off_emptyJSON_Should_Return_complexJSON.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_JSON_State_Enabled_On_complexJSON_Off_emptyJSON_Should_Return_complexJSON.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_JSON_State_Enabled_On_validJSON_Off_emptyJSON_Should_Return_validJSON.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_JSON_State_Enabled_On_validJSON_Off_emptyJSON_Should_Return_validJSON.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_Number_State_Enabled_On_011_Off_2_Should_Return_011.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_Number_State_Enabled_On_011_Off_2_Should_Return_011.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_Number_State_Enabled_On_324523_Off_011_Should_Return_324523.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_Number_State_Enabled_On_324523_Off_011_Should_Return_324523.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_String_State_Enabled_On_sonnet19_Off_sonnet53_Should_Return_sonnet19.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_String_State_Enabled_On_sonnet19_Off_sonnet53_Should_Return_sonnet19.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_String_State_Enabled_On_sonnet53_Off_sonnet19_Should_Return_sonnet53.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/DefaultOnRules/DefaultOnRules_Type_String_State_Enabled_On_sonnet53_Off_sonnet19_Should_Return_sonnet53.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_EqualsThree_Should_Return_false_for_Target_three.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_EqualsThree_Should_Return_false_for_Target_three.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_EqualsThree_Should_Return_true_for_Target_one.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_EqualsThree_Should_Return_true_for_Target_one.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_GroupWithMultipleOrRules_Should_Return_true_for_Target_three.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_GroupWithMultipleOrRules_Should_Return_true_for_Target_three.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_InOneTwoThree_Should_Return_true_for_Target_three.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_InOneTwoThree_Should_Return_true_for_Target_three.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_IncludeAndExcludeGroup_Should_Return_true_for_Target_three.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_IncludeAndExcludeGroup_Should_Return_true_for_Target_three.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_IncludedOnly_Should_Return_true_for_Target_three.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_IncludedOnly_Should_Return_true_for_Target_three.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_StartsWithTExcludesThree_Should_Return_true_for_Target_three.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_StartsWithTExcludesThree_Should_Return_true_for_Target_three.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_StartsWithT_Should_Return_false_for_Target_one.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_StartsWithT_Should_Return_false_for_Target_one.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_StartsWithT_Should_Return_true_for_Target_three.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/GroupRules/GroupRules_Type_Bool_State_Enabled_StartsWithT_Should_Return_true_for_Target_three.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_BoolBool_State_Enabled_On_True_Off_False_Prerequisites_AlwaysOff_Should_Return_False.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_BoolBool_State_Enabled_On_True_Off_False_Prerequisites_AlwaysOff_Should_Return_False.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_BoolBool_State_Enabled_On_True_Off_False_Prerequisites_AlwaysOff_Should_Return_True.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_BoolBool_State_Enabled_On_True_Off_False_Prerequisites_AlwaysOff_Should_Return_True.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_BoolBool_State_Enabled_On_True_Off_True_Prerequisites_AlwaysOn_Should_Return_False.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_BoolBool_State_Enabled_On_True_Off_True_Prerequisites_AlwaysOn_Should_Return_False.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_BoolBool_State_Enabled_On_True_Off_True_Prerequisites_AlwaysOn_Should_Return_True.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_BoolBool_State_Enabled_On_True_Off_True_Prerequisites_AlwaysOn_Should_Return_True.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_BoolInt_State_Enabled_On_True_Off_False_Prerequisites_AlwaysOff_Should_Return_False.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_BoolInt_State_Enabled_On_True_Off_False_Prerequisites_AlwaysOff_Should_Return_False.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_BoolInt_State_Enabled_On_True_Off_False_Prerequisites_AlwaysOff_Should_Return_True.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_BoolInt_State_Enabled_On_True_Off_False_Prerequisites_AlwaysOff_Should_Return_True.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_BoolInt_State_Enabled_On_True_Off_True_Prerequisites_AlwaysOn_Should_Return_False.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_BoolInt_State_Enabled_On_True_Off_True_Prerequisites_AlwaysOn_Should_Return_False.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_BoolInt_State_Enabled_On_True_Off_True_Prerequisites_AlwaysOn_Should_Return_True.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_BoolInt_State_Enabled_On_True_Off_True_Prerequisites_AlwaysOn_Should_Return_True.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntBool_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOff_Should_Return_011.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntBool_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOff_Should_Return_011.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntBool_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOff_Should_Return_2.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntBool_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOff_Should_Return_2.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntBool_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOn_Should_Return_011.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntBool_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOn_Should_Return_011.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntBool_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOn_Should_Return_2.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntBool_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOn_Should_Return_2.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntInt_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOff_Should_Return_011.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntInt_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOff_Should_Return_011.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntInt_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOff_Should_Return_2.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntInt_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOff_Should_Return_2.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntInt_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOn_Should_Return_011.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntInt_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOn_Should_Return_011.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntInt_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOn_Should_Return_2.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntInt_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOn_Should_Return_2.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntJson_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOff_Should_Return_011.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntJson_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOff_Should_Return_011.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntJson_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOff_Should_Return_2.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntJson_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOff_Should_Return_2.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntJson_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOn_Should_Return_011.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntJson_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOn_Should_Return_011.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntJson_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOn_Should_Return_2.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntJson_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOn_Should_Return_2.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntString_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOff_Should_Return_011.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntString_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOff_Should_Return_011.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntString_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOff_Should_Return_2.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntString_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOff_Should_Return_2.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntString_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOn_Should_Return_011.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntString_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOn_Should_Return_011.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntString_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOn_Should_Return_2.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_IntString_State_Enabled_On_2_Off_011_Prerequisites_AlwaysOn_Should_Return_2.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_JsonJson_State_Enabled_On_com_Off_val_Prerequisites_AlwaysOff_Should_Return_Com.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_JsonJson_State_Enabled_On_com_Off_val_Prerequisites_AlwaysOff_Should_Return_Com.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_JsonJson_State_Enabled_On_com_Off_val_Prerequisites_AlwaysOff_Should_Return_Val.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_JsonJson_State_Enabled_On_com_Off_val_Prerequisites_AlwaysOff_Should_Return_Val.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_JsonJson_State_Enabled_On_com_Off_val_Prerequisites_AlwaysOn_Should_Return_Com.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_JsonJson_State_Enabled_On_com_Off_val_Prerequisites_AlwaysOn_Should_Return_Com.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_JsonJson_State_Enabled_On_com_Off_val_Prerequisites_AlwaysOn_Should_Return_Val.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_JsonJson_State_Enabled_On_com_Off_val_Prerequisites_AlwaysOn_Should_Return_Val.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_StrStr_State_Enabled_On_s19_Off_s53_Prerequisites_AlwaysOff_Should_Return_off.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_StrStr_State_Enabled_On_s19_Off_s53_Prerequisites_AlwaysOff_Should_Return_off.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_StrStr_State_Enabled_On_s19_Off_s53_Prerequisites_AlwaysOff_Should_Return_on.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_StrStr_State_Enabled_On_s19_Off_s53_Prerequisites_AlwaysOff_Should_Return_on.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_StrStr_State_Enabled_On_s19_Off_s53_Prerequisites_AlwaysOn_Should_Return_Off.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_StrStr_State_Enabled_On_s19_Off_s53_Prerequisites_AlwaysOn_Should_Return_Off.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/Prerequisites/Type_StrStr_State_Enabled_On_s19_Off_s53_Prerequisites_AlwaysOn_Should_Return_On.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/Prerequisites/Type_StrStr_State_Enabled_On_s19_Off_s53_Prerequisites_AlwaysOn_Should_Return_On.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_Bool_State_Disabled_Should_Return_Default_Off_Value.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_Bool_State_Disabled_Should_Return_Default_Off_Value.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_Bool_State_Enabled_Should_Return_false_for_Target_four.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_Bool_State_Enabled_Should_Return_false_for_Target_four.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_Bool_State_Enabled_Should_Return_false_for_Target_six.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_Bool_State_Enabled_Should_Return_false_for_Target_six.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_Bool_State_Enabled_Should_Return_true_for_Target_three.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_Bool_State_Enabled_Should_Return_true_for_Target_three.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_JSON_State_Enabled_Should_Return_complexJSON_for_Target_five.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_JSON_State_Enabled_Should_Return_complexJSON_for_Target_five.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_JSON_State_Enabled_Should_Return_emptyJSON_for_Target_four.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_JSON_State_Enabled_Should_Return_emptyJSON_for_Target_four.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_JSON_State_Enabled_Should_Return_validJSON_for_Target_anonymous.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_JSON_State_Enabled_Should_Return_validJSON_for_Target_anonymous.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_Number_State_Enabled_Should_Return_2_for_Target_four.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_Number_State_Enabled_Should_Return_2_for_Target_four.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_Number_State_Enabled_Should_Return_324523_for_Target_five.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_Number_State_Enabled_Should_Return_324523_for_Target_five.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_Number_State_Enabled_Should_Return_sonnet53_for_Target_anonymous.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_Number_State_Enabled_Should_Return_sonnet53_for_Target_anonymous.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_String_State_Enabled_Should_Return_sonnet53_for_Target_anonymous.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_String_State_Enabled_Should_Return_sonnet53_for_Target_anonymous.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_String_State_Enabled_Should_Return_sonnet53_for_Target_four.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_String_State_Enabled_Should_Return_sonnet53_for_Target_four.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_String_State_Enabled_Should_Return_thehobbit_for_Target_five.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/TargetRules/TargetRules_Type_String_State_Enabled_Should_Return_thehobbit_for_Target_five.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/bool_on_simple_rule.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/bool_on_simple_rule.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/off_flag.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/off_flag.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/off_off_no_rules.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/off_off_no_rules.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/on_off_no_rules.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/on_off_no_rules.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/prereq.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/prereq.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/rules_priority.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/rules_priority.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/segment_includes_target.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/segment_includes_target.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/tests/test_empty_or_missing_target_attributes.json` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/tests/test_empty_or_missing_target_attributes.json`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/types.gen.go` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/types.gen.go`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/ff-test-cases/validator.go` & `harness-featureflags-1.2.0/tests/integration/ff-test-cases/validator.go`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/test_clause.py` & `harness-featureflags-1.2.0/tests/integration/test_clause.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/integration/test_evaluator.py` & `harness-featureflags-1.2.0/tests/integration/test_evaluator.py`

 * *Files 4% similar despite different names*

```diff
@@ -125,22 +125,26 @@
             None
         )
 
     got = None
 
     switch_kind = {
         FeatureConfigKind.BOOLEAN:
-            lambda: evaluator.evaluate(tc.flag, target).bool(default=False),
+            lambda: evaluator.evaluate(tc.flag, target)
+            .bool(target, tc.flag, default=False),
         FeatureConfigKind.STRING:
             lambda: evaluator.evaluate(tc.flag, target).string(
+                target, tc.flag,
                 default="failed"),
         FeatureConfigKind.INT:
-            lambda: evaluator.evaluate(tc.flag, target).number(default=0.100),
+            lambda: evaluator.evaluate(tc.flag, target)
+            .number(target, tc.flag, default=0.100),
         FeatureConfigKind.JSON:
-            lambda: evaluator.evaluate(tc.flag, target).json(default={}),
+            lambda: evaluator.evaluate(tc.flag, target)
+            .json(target, tc.flag, default={}),
     }
 
     kind = repository.get_flag(tc.flag).kind
     got = switch_kind[kind]()
 
     if kind == FeatureConfigKind.JSON:
         tc.expected = json.loads(tc.expected)
```

### Comparing `harness-featureflags-1.1.9/tests/integration/test_feature.py` & `harness-featureflags-1.2.0/tests/integration/test_feature.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/test_client.py` & `harness-featureflags-1.2.0/tests/test_client.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/unit/test_clause.py` & `harness-featureflags-1.2.0/tests/unit/test_clause.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/unit/test_evaluator.py` & `harness-featureflags-1.2.0/tests/unit/test_evaluator.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/unit/test_integer.py` & `harness-featureflags-1.2.0/tests/unit/test_integer.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/unit/test_lru.py` & `harness-featureflags-1.2.0/tests/unit/test_lru.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/unit/test_number.py` & `harness-featureflags-1.2.0/tests/unit/test_number.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/unit/test_sse_client.py` & `harness-featureflags-1.2.0/tests/unit/test_sse_client.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/unit/test_string.py` & `harness-featureflags-1.2.0/tests/unit/test_string.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/unit/test_target.py` & `harness-featureflags-1.2.0/tests/unit/test_target.py`

 * *Files identical despite different names*

### Comparing `harness-featureflags-1.1.9/tests/unit/test_utils.py` & `harness-featureflags-1.2.0/tests/unit/test_utils.py`

 * *Files identical despite different names*


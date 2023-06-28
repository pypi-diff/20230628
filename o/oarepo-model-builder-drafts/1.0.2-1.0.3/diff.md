# Comparing `tmp/oarepo-model-builder-drafts-1.0.2.tar.gz` & `tmp/oarepo-model-builder-drafts-1.0.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "oarepo-model-builder-drafts-1.0.2.tar", last modified: Wed Apr 19 13:16:16 2023, max compression
+gzip compressed data, was "oarepo-model-builder-drafts-1.0.3.tar", last modified: Wed Jun 28 14:06:11 2023, max compression
```

## Comparing `oarepo-model-builder-drafts-1.0.2.tar` & `oarepo-model-builder-drafts-1.0.3.tar`

### file list

```diff
@@ -1,51 +1,62 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 13:16:16.970021 oarepo-model-builder-drafts-1.0.2/
--rw-r--r--   0 runner    (1001) docker     (123)      412 2023-04-19 13:16:16.970021 oarepo-model-builder-drafts-1.0.2/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      299 2023-04-19 13:14:10.000000 oarepo-model-builder-drafts-1.0.2/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 13:16:16.966021 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-04-19 13:14:10.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 13:16:16.966021 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/builders/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-04-19 13:14:10.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/builders/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      946 2023-04-19 13:14:10.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/builders/parent_jsonschema_builder.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 13:16:16.966021 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/invenio/
--rw-r--r--   0 runner    (1001) docker     (123)      772 2023-04-19 13:14:10.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/invenio/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      300 2023-04-19 13:14:10.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/invenio/invenio_drafts_parent_metadata.py
--rw-r--r--   0 runner    (1001) docker     (123)      284 2023-04-19 13:14:10.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/invenio/invenio_drafts_parent_record.py
--rw-r--r--   0 runner    (1001) docker     (123)      963 2023-04-19 13:14:10.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/invenio/invenio_drafts_parent_state.py
--rw-r--r--   0 runner    (1001) docker     (123)      287 2023-04-19 13:14:10.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/invenio/invenio_drafts_record_extra_fields.py
--rw-r--r--   0 runner    (1001) docker     (123)      323 2023-04-19 13:14:10.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/invenio/invenio_drafts_record_metadata_extra_fields.py
--rw-r--r--   0 runner    (1001) docker     (123)      310 2023-04-19 13:14:10.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/invenio/invenio_drafts_record_service_config.py
--rw-r--r--   0 runner    (1001) docker     (123)      418 2023-04-19 13:14:10.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/invenio/invenio_drafts_setup_cfg.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 13:16:16.970021 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/invenio/templates/
--rw-r--r--   0 runner    (1001) docker     (123)      382 2023-04-19 13:14:10.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/invenio/templates/invenio_drafts_parent_metadata.py.jinja2
--rw-r--r--   0 runner    (1001) docker     (123)      810 2023-04-19 13:14:10.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/invenio/templates/invenio_drafts_parent_record.py.jinja2
--rw-r--r--   0 runner    (1001) docker     (123)      404 2023-04-19 13:14:10.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/invenio/templates/invenio_drafts_parent_state.py.jinja2
--rw-r--r--   0 runner    (1001) docker     (123)      339 2023-04-19 13:14:10.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/invenio/templates/invenio_drafts_record_extra_fields.py.jinja2
--rw-r--r--   0 runner    (1001) docker     (123)      155 2023-04-19 13:14:10.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/invenio/templates/invenio_drafts_record_metadata_extra_fields.py.jinja2
--rw-r--r--   0 runner    (1001) docker     (123)     1378 2023-04-19 13:14:10.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/invenio/templates/invenio_drafts_record_service_config.py.jinja2
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 13:16:16.970021 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/model_preprocessors/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-04-19 13:14:10.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/model_preprocessors/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      440 2023-04-19 13:14:10.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/model_preprocessors/invenio_drafts_base_classes.py
--rw-r--r--   0 runner    (1001) docker     (123)     1735 2023-04-19 13:14:10.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/model_preprocessors/invenio_drafts_common.py
--rw-r--r--   0 runner    (1001) docker     (123)     1443 2023-04-19 13:14:10.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/model_preprocessors/invenio_drafts_draft.py
--rw-r--r--   0 runner    (1001) docker     (123)     1163 2023-04-19 13:14:10.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/model_preprocessors/invenio_drafts_record.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 13:16:16.970021 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/profiles/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-04-19 13:14:10.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/profiles/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      441 2023-04-19 13:14:10.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/profiles/drafts.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 13:16:16.970021 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/tests/
--rw-r--r--   0 runner    (1001) docker     (123)       90 2023-04-19 13:14:10.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/tests/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1228 2023-04-19 13:14:10.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/tests/invenio_drafts_test_resources.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 13:16:16.970021 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/tests/templates/
--rw-r--r--   0 runner    (1001) docker     (123)      290 2023-04-19 13:14:10.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/tests/templates/invenio_conftest.py.jinja2
--rw-r--r--   0 runner    (1001) docker     (123)     7525 2023-04-19 13:14:10.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/tests/templates/invenio_test_resources.py.jinja2
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 13:16:16.970021 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/validation/
--rw-r--r--   0 runner    (1001) docker     (123)      997 2023-04-19 13:14:10.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/validation/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 13:16:16.966021 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)      412 2023-04-19 13:16:16.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2361 2023-04-19 13:16:16.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-04-19 13:16:16.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)     3717 2023-04-19 13:16:16.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)       62 2023-04-19 13:16:16.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       28 2023-04-19 13:16:16.000000 oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)      102 2023-04-19 13:14:10.000000 oarepo-model-builder-drafts-1.0.2/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)     4219 2023-04-19 13:16:16.970021 oarepo-model-builder-drafts-1.0.2/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-04-19 13:14:10.000000 oarepo-model-builder-drafts-1.0.2/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:06:11.606684 oarepo-model-builder-drafts-1.0.3/
+-rw-r--r--   0 runner    (1001) docker     (123)      412 2023-06-28 14:06:11.606684 oarepo-model-builder-drafts-1.0.3/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      299 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:06:11.586683 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:06:11.586683 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/builders/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/builders/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1300 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/builders/parent_jsonschema_builder.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:06:11.586683 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/
+-rw-r--r--   0 runner    (1001) docker     (123)       68 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:06:11.590684 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/
+-rw-r--r--   0 runner    (1001) docker     (123)      763 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4953 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:06:11.594684 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_model/
+-rw-r--r--   0 runner    (1001) docker     (123)      768 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_model/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      811 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_model/defaults.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7067 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_model/draft_parent.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1142 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_model/jsonschema.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1592 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_model/mapping.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1516 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_model/pid.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1610 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_model/record.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1913 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_model/record_metadata.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1515 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_model/resource.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1929 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_model/service.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1065 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_tests.py
+-rw-r--r--   0 runner    (1001) docker     (123)      488 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/draft.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:06:11.598683 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/
+-rw-r--r--   0 runner    (1001) docker     (123)      727 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      288 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/invenio_drafts_parent_metadata.py
+-rw-r--r--   0 runner    (1001) docker     (123)      837 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/invenio_drafts_parent_record.py
+-rw-r--r--   0 runner    (1001) docker     (123)      402 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/invenio_drafts_parent_state.py
+-rw-r--r--   0 runner    (1001) docker     (123)      492 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/invenio_drafts_record_extra_fields.py
+-rw-r--r--   0 runner    (1001) docker     (123)      593 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/invenio_drafts_record_metadata_extra_fields.py
+-rw-r--r--   0 runner    (1001) docker     (123)      417 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/invenio_drafts_record_service_config.py
+-rw-r--r--   0 runner    (1001) docker     (123)      393 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/invenio_drafts_setup_cfg.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:06:11.602684 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/templates/
+-rw-r--r--   0 runner    (1001) docker     (123)      259 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/templates/invenio_drafts_parent_metadata.py.jinja2
+-rw-r--r--   0 runner    (1001) docker     (123)      528 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/templates/invenio_drafts_parent_record.py.jinja2
+-rw-r--r--   0 runner    (1001) docker     (123)      518 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/templates/invenio_drafts_parent_state.py.jinja2
+-rw-r--r--   0 runner    (1001) docker     (123)      422 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/templates/invenio_drafts_record_extra_fields.py.jinja2
+-rw-r--r--   0 runner    (1001) docker     (123)      254 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/templates/invenio_drafts_record_metadata_extra_fields.py.jinja2
+-rw-r--r--   0 runner    (1001) docker     (123)      145 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/templates/invenio_drafts_record_service_config.py.jinja2
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:06:11.602684 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/profiles/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/profiles/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1339 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/profiles/draft.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:06:11.602684 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)      154 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/tests/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      584 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/tests/invenio_drafts_conftest.py
+-rw-r--r--   0 runner    (1001) docker     (123)      612 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/tests/invenio_drafts_test_resources.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:06:11.606684 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/tests/templates/
+-rw-r--r--   0 runner    (1001) docker     (123)      431 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/tests/templates/invenio_conftest.py.jinja2
+-rw-r--r--   0 runner    (1001) docker     (123)     6475 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/tests/templates/invenio_test_resources.py.jinja2
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:06:11.586683 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)      412 2023-06-28 14:06:11.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     3027 2023-06-28 14:06:11.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 14:06:11.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     2646 2023-06-28 14:06:11.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       62 2023-06-28 14:06:11.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 14:06:11.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      102 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)     3132 2023-06-28 14:06:11.606684 oarepo-model-builder-drafts-1.0.3/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/setup.py
```

### Comparing `oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/invenio/__init__.py` & `oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/__init__.py`

 * *Files 18% similar despite different names*

```diff
@@ -1,10 +1,8 @@
 TEMPLATES = {
-    "drafts-record-extra-fields": "templates/invenio_drafts_record_extra_fields.py.jinja2",                            #adds drafts extension fields to record
+    "drafts-record-extra-fields": "templates/invenio_drafts_record_extra_fields.py.jinja2",  # adds drafts extension fields to record
     "drafts-record-metadata-extra-fields": "templates/invenio_drafts_record_metadata_extra_fields.py.jinja2",  # adds parent specific fields to model metadata classes
-
-    "drafts-parent-record": "templates/invenio_drafts_parent_record.py.jinja2",              #adds draft parent record class
-    "drafts-parent-metadata": "templates/invenio_drafts_parent_metadata.py.jinja2",            #adds draft parent metadata classes
-
+    "drafts-parent-record": "templates/invenio_drafts_parent_record.py.jinja2",  # adds draft parent record class
+    "drafts-parent-metadata": "templates/invenio_drafts_parent_metadata.py.jinja2",  # adds draft parent metadata classes
     "drafts-record-service-config": "templates/invenio_drafts_record_service_config.py.jinja2",
-    "drafts-parent-state": "templates/invenio_drafts_parent_state.py.jinja2"
-}
+    "drafts-parent-state": "templates/invenio_drafts_parent_state.py.jinja2",
+}
```

### Comparing `oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts/invenio/invenio_drafts_parent_state.py` & `oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/invenio_drafts_parent_record.py`

 * *Files 22% similar despite different names*

```diff
@@ -1,21 +1,22 @@
+from pathlib import Path
+
 from oarepo_model_builder.invenio.invenio_base import InvenioBaseClassPythonBuilder
 from oarepo_model_builder.outputs.python import PythonOutput
-from oarepo_model_builder.utils.hyphen_munch import HyphenMunch
 
 
-class InvenioDraftsParentStateBuilder(InvenioBaseClassPythonBuilder):
-    TYPE = "invenio_drafts_parent_state"
-    class_config = "drafts-parent-record-metadata-class"
-    template = "drafts-parent-state"
+class InvenioDraftsParentRecordBuilder(InvenioBaseClassPythonBuilder):
+    TYPE = "invenio_drafts_parent_record"
+    section = "draft-parent-record"
+    template = "drafts-parent-record"
 
-    def process_template(self, python_path, template, **extra_kwargs):
+    def process_template(self, python_path: Path, template, **extra_kwargs):
         if self.parent_modules:
             self.create_parent_modules(python_path)
         output: PythonOutput = self.builder.get_output("python", python_path)
-        context = HyphenMunch(
-            settings=self.settings, current_model=self.current_model, model=self.schema.model, **extra_kwargs
-        )
-        template = self.call_components(
-            "invenio_before_python_template", template, context=context
+        context = dict(
+            settings=self.settings,
+            current_model=self.current_model,
+            schema=self.current_model.schema.schema,
+            **extra_kwargs,
         )
-        output.merge(template, context)
+        output.merge(template, context)
```

### Comparing `oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts.egg-info/SOURCES.txt` & `oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts.egg-info/SOURCES.txt`

 * *Files 16% similar despite different names*

```diff
@@ -7,33 +7,43 @@
 oarepo_model_builder_drafts.egg-info/SOURCES.txt
 oarepo_model_builder_drafts.egg-info/dependency_links.txt
 oarepo_model_builder_drafts.egg-info/entry_points.txt
 oarepo_model_builder_drafts.egg-info/requires.txt
 oarepo_model_builder_drafts.egg-info/top_level.txt
 oarepo_model_builder_drafts/builders/__init__.py
 oarepo_model_builder_drafts/builders/parent_jsonschema_builder.py
+oarepo_model_builder_drafts/datatypes/__init__.py
+oarepo_model_builder_drafts/datatypes/draft.py
+oarepo_model_builder_drafts/datatypes/components/__init__.py
+oarepo_model_builder_drafts/datatypes/components/draft.py
+oarepo_model_builder_drafts/datatypes/components/draft_tests.py
+oarepo_model_builder_drafts/datatypes/components/draft_model/__init__.py
+oarepo_model_builder_drafts/datatypes/components/draft_model/defaults.py
+oarepo_model_builder_drafts/datatypes/components/draft_model/draft_parent.py
+oarepo_model_builder_drafts/datatypes/components/draft_model/jsonschema.py
+oarepo_model_builder_drafts/datatypes/components/draft_model/mapping.py
+oarepo_model_builder_drafts/datatypes/components/draft_model/pid.py
+oarepo_model_builder_drafts/datatypes/components/draft_model/record.py
+oarepo_model_builder_drafts/datatypes/components/draft_model/record_metadata.py
+oarepo_model_builder_drafts/datatypes/components/draft_model/resource.py
+oarepo_model_builder_drafts/datatypes/components/draft_model/service.py
 oarepo_model_builder_drafts/invenio/__init__.py
 oarepo_model_builder_drafts/invenio/invenio_drafts_parent_metadata.py
 oarepo_model_builder_drafts/invenio/invenio_drafts_parent_record.py
 oarepo_model_builder_drafts/invenio/invenio_drafts_parent_state.py
 oarepo_model_builder_drafts/invenio/invenio_drafts_record_extra_fields.py
 oarepo_model_builder_drafts/invenio/invenio_drafts_record_metadata_extra_fields.py
 oarepo_model_builder_drafts/invenio/invenio_drafts_record_service_config.py
 oarepo_model_builder_drafts/invenio/invenio_drafts_setup_cfg.py
 oarepo_model_builder_drafts/invenio/templates/invenio_drafts_parent_metadata.py.jinja2
 oarepo_model_builder_drafts/invenio/templates/invenio_drafts_parent_record.py.jinja2
 oarepo_model_builder_drafts/invenio/templates/invenio_drafts_parent_state.py.jinja2
 oarepo_model_builder_drafts/invenio/templates/invenio_drafts_record_extra_fields.py.jinja2
 oarepo_model_builder_drafts/invenio/templates/invenio_drafts_record_metadata_extra_fields.py.jinja2
 oarepo_model_builder_drafts/invenio/templates/invenio_drafts_record_service_config.py.jinja2
-oarepo_model_builder_drafts/model_preprocessors/__init__.py
-oarepo_model_builder_drafts/model_preprocessors/invenio_drafts_base_classes.py
-oarepo_model_builder_drafts/model_preprocessors/invenio_drafts_common.py
-oarepo_model_builder_drafts/model_preprocessors/invenio_drafts_draft.py
-oarepo_model_builder_drafts/model_preprocessors/invenio_drafts_record.py
 oarepo_model_builder_drafts/profiles/__init__.py
-oarepo_model_builder_drafts/profiles/drafts.py
+oarepo_model_builder_drafts/profiles/draft.py
 oarepo_model_builder_drafts/tests/__init__.py
+oarepo_model_builder_drafts/tests/invenio_drafts_conftest.py
 oarepo_model_builder_drafts/tests/invenio_drafts_test_resources.py
 oarepo_model_builder_drafts/tests/templates/invenio_conftest.py.jinja2
-oarepo_model_builder_drafts/tests/templates/invenio_test_resources.py.jinja2
-oarepo_model_builder_drafts/validation/__init__.py
+oarepo_model_builder_drafts/tests/templates/invenio_test_resources.py.jinja2
```

### Comparing `oarepo-model-builder-drafts-1.0.2/oarepo_model_builder_drafts.egg-info/entry_points.txt` & `oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts.egg-info/entry_points.txt`

 * *Files 20% similar despite different names*

```diff
@@ -1,43 +1,32 @@
-[oarepo_model_builder.builders.drafts]
+[oarepo_model_builder.builders.draft]
 0020-jsonschema_drafts_parent = oarepo_model_builder_drafts.builders.parent_jsonschema_builder:JSONSchemaDraftsParentBuilder
+0030-mapping = oarepo_model_builder.builders.mapping:MappingBuilder
 0110-invenio_record = oarepo_model_builder.invenio.invenio_record:InvenioRecordBuilder
 0120-invenio_record_metadata = oarepo_model_builder.invenio.invenio_record_metadata:InvenioRecordMetadataBuilder
+0340-invenio_record_dumper = oarepo_model_builder.invenio.invenio_record_dumper:InvenioRecordDumperBuilder
 2800-invenio_drafts_record_metadata_extra_fields = oarepo_model_builder_drafts.invenio.invenio_drafts_record_metadata_extra_fields:InvenioDraftsRecordMetadataExtraFieldsBuilder
-2800-invenio_drafts_record_service_config = oarepo_model_builder_drafts.invenio.invenio_drafts_record_service_config:InvenioDraftsRecordServiceConfigBuilder
 2900-invenio_drafts_record_extra_fields = oarepo_model_builder_drafts.invenio.invenio_drafts_record_extra_fields:InvenioDraftsRecordExtraFieldsBuilder
-3100-invenio_drafts_parent_state = oarepo_model_builder_drafts.invenio.invenio_drafts_parent_state:InvenioDraftsParentStateBuilder
-3200-invenio_drafts_test_resource = oarepo_model_builder_drafts.tests.invenio_drafts_test_resources:InvenioDraftsTestResourcesBuilder
+3500-invenio_drafts_setup_cfg = oarepo_model_builder_drafts.invenio.invenio_drafts_setup_cfg:InvenioDraftsSetupCfgBuilder
+5150-invenio_drafts_parent_state = oarepo_model_builder_drafts.invenio.invenio_drafts_parent_state:InvenioDraftsParentStateBuilder
+5200-invenio_drafts_record_service_config = oarepo_model_builder_drafts.invenio.invenio_drafts_record_service_config:InvenioDraftsRecordServiceConfigBuilder
+6000-invenio_conftest = oarepo_model_builder_drafts.tests.invenio_drafts_conftest:InvenioDraftsConftestBuilder
+6100-invenio_drafts_test_resource = oarepo_model_builder_drafts.tests.invenio_drafts_test_resources:InvenioDraftsTestResourcesBuilder
 
-[oarepo_model_builder.builders.model]
+[oarepo_model_builder.builders.record]
 0100-invenio_drafts_parent_metadata = oarepo_model_builder_drafts.invenio.invenio_drafts_parent_metadata:InvenioDraftsParentMetadataBuilder
 0105-invenio_drafts_parent_record = oarepo_model_builder_drafts.invenio.invenio_drafts_parent_record:InvenioDraftsParentRecordBuilder
 2800-invenio_drafts_record_metadata_extra_fields = oarepo_model_builder_drafts.invenio.invenio_drafts_record_metadata_extra_fields:InvenioDraftsRecordMetadataExtraFieldsBuilder
 2900-invenio_drafts_record_extra_fields = oarepo_model_builder_drafts.invenio.invenio_drafts_record_extra_fields:InvenioDraftsRecordExtraFieldsBuilder
-3500-invenio_drafts_setup_cfg = oarepo_model_builder_drafts.invenio.invenio_drafts_setup_cfg:InvenioDraftsSetupCfgBuilder
 
-[oarepo_model_builder.model_preprocessors.drafts]
-05-invenio_drafts_common = oarepo_model_builder_drafts.model_preprocessors.invenio_drafts_common:InvenioDraftsCommonModelPreprocessor
-05-invenio_drafts_draft = oarepo_model_builder_drafts.model_preprocessors.invenio_drafts_draft:InvenioDraftsDraftModelPreprocessor
-10-default = oarepo_model_builder.model_preprocessors.default_values:DefaultValuesModelPreprocessor
-12-invenio = oarepo_model_builder.model_preprocessors.invenio:InvenioModelPreprocessor
-15-invenio_base_classes = oarepo_model_builder.model_preprocessors.invenio_base_classes:InvenioBaseClassesModelPreprocessor
-15-invenio_drafts_base_classes = oarepo_model_builder_drafts.model_preprocessors.invenio_drafts_base_classes:InvenioDraftsBaseClassesModelPreprocessor
+[oarepo_model_builder.datatypes]
+invenio_drafts = oarepo_model_builder_drafts.datatypes:DRAFT_DATATYPES
 
-[oarepo_model_builder.model_preprocessors.model]
-05-invenio_drafts_common = oarepo_model_builder_drafts.model_preprocessors.invenio_drafts_common:InvenioDraftsCommonModelPreprocessor
-05-invenio_drafts_record = oarepo_model_builder_drafts.model_preprocessors.invenio_drafts_record:InvenioDraftsRecordModelPreprocessor
-15-invenio_drafts_base_classes = oarepo_model_builder_drafts.model_preprocessors.invenio_drafts_base_classes:InvenioDraftsBaseClassesModelPreprocessor
+[oarepo_model_builder.datatypes.components]
+invenio_drafts = oarepo_model_builder_drafts.datatypes.components:DRAFT_COMPONENTS
 
 [oarepo_model_builder.profiles]
-drafts = oarepo_model_builder_drafts.profiles.drafts:DraftsProfile
-
-[oarepo_model_builder.property_preprocessors.drafts]
-200-datatypes = oarepo_model_builder.property_preprocessors.datatype_preprocessor:DataTypePreprocessor
-300-enums = oarepo_model_builder.property_preprocessors.enum:EnumPreprocessor
+draft = oarepo_model_builder_drafts.profiles.draft:DraftProfile
 
 [oarepo_model_builder.templates]
 99-drafts_templates = oarepo_model_builder_drafts.invenio
 99-drafts_test_templates = oarepo_model_builder_drafts.tests
-
-[oarepo_model_builder.validation]
-drafts-validation = oarepo_model_builder_drafts.validation:validators
```

### Comparing `oarepo-model-builder-drafts-1.0.2/setup.cfg` & `oarepo-model-builder-drafts-1.0.3/setup.cfg`

 * *Files 21% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [metadata]
 name = oarepo-model-builder-drafts
-version = 1.0.2
+version = 1.0.3
 description = 
 authors = Ronald Krist <krist@cesnet.cz>
 readme = README.md
 long_description = file:README.md
 long_description_content_type = text/markdown
 
 [options]
@@ -13,51 +13,39 @@
 	oarepo-model-builder-tests>=3.1.0
 	oarepo-model-builder>=3.1.2
 
 [options.package_data]
 * = *.json, *.rst, *.md, *.json5, *.jinja2
 
 [options.entry_points]
-oarepo_model_builder.builders.drafts = 
+oarepo_model_builder.datatypes = 
+	invenio_drafts = oarepo_model_builder_drafts.datatypes:DRAFT_DATATYPES
+oarepo_model_builder.datatypes.components = 
+	invenio_drafts = oarepo_model_builder_drafts.datatypes.components:DRAFT_COMPONENTS
+oarepo_model_builder.profiles = 
+	draft = oarepo_model_builder_drafts.profiles.draft:DraftProfile
+oarepo_model_builder.builders.draft = 
 	0020-jsonschema_drafts_parent  = oarepo_model_builder_drafts.builders.parent_jsonschema_builder:JSONSchemaDraftsParentBuilder
+	0030-mapping  = oarepo_model_builder.builders.mapping:MappingBuilder
+	
 	0110-invenio_record  = oarepo_model_builder.invenio.invenio_record:InvenioRecordBuilder
 	0120-invenio_record_metadata  = oarepo_model_builder.invenio.invenio_record_metadata:InvenioRecordMetadataBuilder
-	
-	2800-invenio_drafts_record_service_config = oarepo_model_builder_drafts.invenio.invenio_drafts_record_service_config:InvenioDraftsRecordServiceConfigBuilder
+	0340-invenio_record_dumper  = oarepo_model_builder.invenio.invenio_record_dumper:InvenioRecordDumperBuilder
 	2800-invenio_drafts_record_metadata_extra_fields = oarepo_model_builder_drafts.invenio.invenio_drafts_record_metadata_extra_fields:InvenioDraftsRecordMetadataExtraFieldsBuilder
 	2900-invenio_drafts_record_extra_fields = oarepo_model_builder_drafts.invenio.invenio_drafts_record_extra_fields:InvenioDraftsRecordExtraFieldsBuilder
-	3100-invenio_drafts_parent_state = oarepo_model_builder_drafts.invenio.invenio_drafts_parent_state:InvenioDraftsParentStateBuilder
-	
-	3200-invenio_drafts_test_resource = oarepo_model_builder_drafts.tests.invenio_drafts_test_resources:InvenioDraftsTestResourcesBuilder
-oarepo_model_builder.builders.model = 
-	
-	0105-invenio_drafts_parent_record = oarepo_model_builder_drafts.invenio.invenio_drafts_parent_record:InvenioDraftsParentRecordBuilder
+	5150-invenio_drafts_parent_state = oarepo_model_builder_drafts.invenio.invenio_drafts_parent_state:InvenioDraftsParentStateBuilder
+	5200-invenio_drafts_record_service_config = oarepo_model_builder_drafts.invenio.invenio_drafts_record_service_config:InvenioDraftsRecordServiceConfigBuilder
+	3500-invenio_drafts_setup_cfg = oarepo_model_builder_drafts.invenio.invenio_drafts_setup_cfg:InvenioDraftsSetupCfgBuilder
+	6000-invenio_conftest = oarepo_model_builder_drafts.tests.invenio_drafts_conftest:InvenioDraftsConftestBuilder
+	6100-invenio_drafts_test_resource = oarepo_model_builder_drafts.tests.invenio_drafts_test_resources:InvenioDraftsTestResourcesBuilder
+oarepo_model_builder.builders.record = 
 	0100-invenio_drafts_parent_metadata = oarepo_model_builder_drafts.invenio.invenio_drafts_parent_metadata:InvenioDraftsParentMetadataBuilder
+	0105-invenio_drafts_parent_record = oarepo_model_builder_drafts.invenio.invenio_drafts_parent_record:InvenioDraftsParentRecordBuilder
 	2800-invenio_drafts_record_metadata_extra_fields = oarepo_model_builder_drafts.invenio.invenio_drafts_record_metadata_extra_fields:InvenioDraftsRecordMetadataExtraFieldsBuilder
-	
 	2900-invenio_drafts_record_extra_fields = oarepo_model_builder_drafts.invenio.invenio_drafts_record_extra_fields:InvenioDraftsRecordExtraFieldsBuilder
-	3500-invenio_drafts_setup_cfg = oarepo_model_builder_drafts.invenio.invenio_drafts_setup_cfg:InvenioDraftsSetupCfgBuilder
-oarepo_model_builder.profiles = 
-	drafts = oarepo_model_builder_drafts.profiles.drafts:DraftsProfile
-oarepo_model_builder.validation = 
-	drafts-validation = oarepo_model_builder_drafts.validation:validators
-oarepo_model_builder.property_preprocessors.drafts = 
-	200-datatypes  = oarepo_model_builder.property_preprocessors.datatype_preprocessor:DataTypePreprocessor
-	300-enums  = oarepo_model_builder.property_preprocessors.enum:EnumPreprocessor
-oarepo_model_builder.model_preprocessors.model = 
-	05-invenio_drafts_record = oarepo_model_builder_drafts.model_preprocessors.invenio_drafts_record:InvenioDraftsRecordModelPreprocessor
-	05-invenio_drafts_common = oarepo_model_builder_drafts.model_preprocessors.invenio_drafts_common:InvenioDraftsCommonModelPreprocessor
-	15-invenio_drafts_base_classes = oarepo_model_builder_drafts.model_preprocessors.invenio_drafts_base_classes:InvenioDraftsBaseClassesModelPreprocessor
-oarepo_model_builder.model_preprocessors.drafts = 
-	05-invenio_drafts_draft = oarepo_model_builder_drafts.model_preprocessors.invenio_drafts_draft:InvenioDraftsDraftModelPreprocessor
-	05-invenio_drafts_common = oarepo_model_builder_drafts.model_preprocessors.invenio_drafts_common:InvenioDraftsCommonModelPreprocessor
-	10-default  = oarepo_model_builder.model_preprocessors.default_values:DefaultValuesModelPreprocessor
-	12-invenio  = oarepo_model_builder.model_preprocessors.invenio:InvenioModelPreprocessor
-	15-invenio_drafts_base_classes = oarepo_model_builder_drafts.model_preprocessors.invenio_drafts_base_classes:InvenioDraftsBaseClassesModelPreprocessor
-	15-invenio_base_classes  = oarepo_model_builder.model_preprocessors.invenio_base_classes:InvenioBaseClassesModelPreprocessor
 oarepo_model_builder.templates = 
 	99-drafts_templates = oarepo_model_builder_drafts.invenio
 	99-drafts_test_templates = oarepo_model_builder_drafts.tests
 
 [egg_info]
 tag_build = 
 tag_date = 0
```


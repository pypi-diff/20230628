# Comparing `tmp/oarepo-model-builder-drafts-1.0.3.tar.gz` & `tmp/oarepo-model-builder-drafts-1.0.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "oarepo-model-builder-drafts-1.0.3.tar", last modified: Wed Jun 28 14:06:11 2023, max compression
+gzip compressed data, was "oarepo-model-builder-drafts-1.0.4.tar", last modified: Wed Jun 28 15:13:47 2023, max compression
```

## Comparing `oarepo-model-builder-drafts-1.0.3.tar` & `oarepo-model-builder-drafts-1.0.4.tar`

### file list

```diff
@@ -1,62 +1,62 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:06:11.606684 oarepo-model-builder-drafts-1.0.3/
--rw-r--r--   0 runner    (1001) docker     (123)      412 2023-06-28 14:06:11.606684 oarepo-model-builder-drafts-1.0.3/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      299 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:06:11.586683 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:06:11.586683 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/builders/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/builders/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1300 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/builders/parent_jsonschema_builder.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:06:11.586683 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/
--rw-r--r--   0 runner    (1001) docker     (123)       68 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:06:11.590684 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/
--rw-r--r--   0 runner    (1001) docker     (123)      763 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4953 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:06:11.594684 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_model/
--rw-r--r--   0 runner    (1001) docker     (123)      768 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_model/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      811 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_model/defaults.py
--rw-r--r--   0 runner    (1001) docker     (123)     7067 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_model/draft_parent.py
--rw-r--r--   0 runner    (1001) docker     (123)     1142 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_model/jsonschema.py
--rw-r--r--   0 runner    (1001) docker     (123)     1592 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_model/mapping.py
--rw-r--r--   0 runner    (1001) docker     (123)     1516 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_model/pid.py
--rw-r--r--   0 runner    (1001) docker     (123)     1610 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_model/record.py
--rw-r--r--   0 runner    (1001) docker     (123)     1913 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_model/record_metadata.py
--rw-r--r--   0 runner    (1001) docker     (123)     1515 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_model/resource.py
--rw-r--r--   0 runner    (1001) docker     (123)     1929 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_model/service.py
--rw-r--r--   0 runner    (1001) docker     (123)     1065 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_tests.py
--rw-r--r--   0 runner    (1001) docker     (123)      488 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/draft.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:06:11.598683 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/
--rw-r--r--   0 runner    (1001) docker     (123)      727 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      288 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/invenio_drafts_parent_metadata.py
--rw-r--r--   0 runner    (1001) docker     (123)      837 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/invenio_drafts_parent_record.py
--rw-r--r--   0 runner    (1001) docker     (123)      402 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/invenio_drafts_parent_state.py
--rw-r--r--   0 runner    (1001) docker     (123)      492 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/invenio_drafts_record_extra_fields.py
--rw-r--r--   0 runner    (1001) docker     (123)      593 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/invenio_drafts_record_metadata_extra_fields.py
--rw-r--r--   0 runner    (1001) docker     (123)      417 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/invenio_drafts_record_service_config.py
--rw-r--r--   0 runner    (1001) docker     (123)      393 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/invenio_drafts_setup_cfg.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:06:11.602684 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/templates/
--rw-r--r--   0 runner    (1001) docker     (123)      259 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/templates/invenio_drafts_parent_metadata.py.jinja2
--rw-r--r--   0 runner    (1001) docker     (123)      528 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/templates/invenio_drafts_parent_record.py.jinja2
--rw-r--r--   0 runner    (1001) docker     (123)      518 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/templates/invenio_drafts_parent_state.py.jinja2
--rw-r--r--   0 runner    (1001) docker     (123)      422 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/templates/invenio_drafts_record_extra_fields.py.jinja2
--rw-r--r--   0 runner    (1001) docker     (123)      254 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/templates/invenio_drafts_record_metadata_extra_fields.py.jinja2
--rw-r--r--   0 runner    (1001) docker     (123)      145 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/templates/invenio_drafts_record_service_config.py.jinja2
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:06:11.602684 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/profiles/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/profiles/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1339 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/profiles/draft.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:06:11.602684 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/tests/
--rw-r--r--   0 runner    (1001) docker     (123)      154 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/tests/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      584 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/tests/invenio_drafts_conftest.py
--rw-r--r--   0 runner    (1001) docker     (123)      612 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/tests/invenio_drafts_test_resources.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:06:11.606684 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/tests/templates/
--rw-r--r--   0 runner    (1001) docker     (123)      431 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/tests/templates/invenio_conftest.py.jinja2
--rw-r--r--   0 runner    (1001) docker     (123)     6475 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/tests/templates/invenio_test_resources.py.jinja2
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:06:11.586683 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)      412 2023-06-28 14:06:11.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     3027 2023-06-28 14:06:11.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 14:06:11.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)     2646 2023-06-28 14:06:11.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)       62 2023-06-28 14:06:11.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 14:06:11.000000 oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)      102 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)     3132 2023-06-28 14:06:11.606684 oarepo-model-builder-drafts-1.0.3/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 14:02:21.000000 oarepo-model-builder-drafts-1.0.3/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:13:47.094029 oarepo-model-builder-drafts-1.0.4/
+-rw-r--r--   0 runner    (1001) docker     (123)      412 2023-06-28 15:13:47.094029 oarepo-model-builder-drafts-1.0.4/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      299 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:13:47.086028 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:13:47.090029 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/builders/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/builders/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1300 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/builders/parent_jsonschema_builder.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:13:47.090029 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/datatypes/
+-rw-r--r--   0 runner    (1001) docker     (123)       68 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/datatypes/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:13:47.090029 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/datatypes/components/
+-rw-r--r--   0 runner    (1001) docker     (123)      763 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/datatypes/components/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5084 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/datatypes/components/draft.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:13:47.090029 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/datatypes/components/draft_model/
+-rw-r--r--   0 runner    (1001) docker     (123)      768 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/datatypes/components/draft_model/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      811 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/datatypes/components/draft_model/defaults.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7067 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/datatypes/components/draft_model/draft_parent.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1142 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/datatypes/components/draft_model/jsonschema.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1592 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/datatypes/components/draft_model/mapping.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1516 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/datatypes/components/draft_model/pid.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1610 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/datatypes/components/draft_model/record.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1913 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/datatypes/components/draft_model/record_metadata.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1515 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/datatypes/components/draft_model/resource.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1929 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/datatypes/components/draft_model/service.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1065 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/datatypes/components/draft_tests.py
+-rw-r--r--   0 runner    (1001) docker     (123)      488 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/datatypes/draft.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:13:47.094029 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/invenio/
+-rw-r--r--   0 runner    (1001) docker     (123)      727 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/invenio/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      288 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/invenio/invenio_drafts_parent_metadata.py
+-rw-r--r--   0 runner    (1001) docker     (123)      837 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/invenio/invenio_drafts_parent_record.py
+-rw-r--r--   0 runner    (1001) docker     (123)      402 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/invenio/invenio_drafts_parent_state.py
+-rw-r--r--   0 runner    (1001) docker     (123)      492 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/invenio/invenio_drafts_record_extra_fields.py
+-rw-r--r--   0 runner    (1001) docker     (123)      593 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/invenio/invenio_drafts_record_metadata_extra_fields.py
+-rw-r--r--   0 runner    (1001) docker     (123)      417 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/invenio/invenio_drafts_record_service_config.py
+-rw-r--r--   0 runner    (1001) docker     (123)      393 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/invenio/invenio_drafts_setup_cfg.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:13:47.094029 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/invenio/templates/
+-rw-r--r--   0 runner    (1001) docker     (123)      259 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/invenio/templates/invenio_drafts_parent_metadata.py.jinja2
+-rw-r--r--   0 runner    (1001) docker     (123)      528 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/invenio/templates/invenio_drafts_parent_record.py.jinja2
+-rw-r--r--   0 runner    (1001) docker     (123)      518 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/invenio/templates/invenio_drafts_parent_state.py.jinja2
+-rw-r--r--   0 runner    (1001) docker     (123)      422 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/invenio/templates/invenio_drafts_record_extra_fields.py.jinja2
+-rw-r--r--   0 runner    (1001) docker     (123)      254 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/invenio/templates/invenio_drafts_record_metadata_extra_fields.py.jinja2
+-rw-r--r--   0 runner    (1001) docker     (123)      145 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/invenio/templates/invenio_drafts_record_service_config.py.jinja2
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:13:47.094029 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/profiles/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/profiles/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1501 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/profiles/draft.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:13:47.094029 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)      154 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/tests/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      584 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/tests/invenio_drafts_conftest.py
+-rw-r--r--   0 runner    (1001) docker     (123)      612 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/tests/invenio_drafts_test_resources.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:13:47.094029 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/tests/templates/
+-rw-r--r--   0 runner    (1001) docker     (123)      431 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/tests/templates/invenio_conftest.py.jinja2
+-rw-r--r--   0 runner    (1001) docker     (123)     6475 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/tests/templates/invenio_test_resources.py.jinja2
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:13:47.090029 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)      412 2023-06-28 15:13:47.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     3027 2023-06-28 15:13:47.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 15:13:47.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     2646 2023-06-28 15:13:47.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       62 2023-06-28 15:13:47.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 15:13:47.000000 oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      102 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)     3132 2023-06-28 15:13:47.094029 oarepo-model-builder-drafts-1.0.4/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 15:09:40.000000 oarepo-model-builder-drafts-1.0.4/setup.py
```

### Comparing `oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/builders/parent_jsonschema_builder.py` & `oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/builders/parent_jsonschema_builder.py`

 * *Files identical despite different names*

### Comparing `oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/__init__.py` & `oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/datatypes/components/__init__.py`

 * *Files identical despite different names*

### Comparing `oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft.py` & `oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/datatypes/components/draft.py`

 * *Files 6% similar despite different names*

```diff
@@ -5,28 +5,30 @@
     ModelDataType,
     Section,
 )
 from oarepo_model_builder.datatypes.components import (
     PIDModelComponent,
     RecordModelComponent,
     ResourceModelComponent,
-    ServiceModelComponent,
+    ServiceModelComponent, DefaultsModelComponent,
 )
 from oarepo_model_builder.datatypes.components.model.utils import set_default
 from oarepo_model_builder.datatypes.model import Link
+import marshmallow as ma
+def get_draft_schema():
+    from ..draft import DraftDataType
 
+    return DraftDataType.validator()
 
 class DraftComponent(DataTypeComponent):
     eligible_datatypes = [ModelDataType]
-    affects = [
-        RecordModelComponent,
-        ServiceModelComponent,
-        ResourceModelComponent,
-        PIDModelComponent,
-    ]
+    affects = [DefaultsModelComponent]
+    class ModelSchema(ma.Schema):
+        draft = ma.fields.Nested(get_draft_schema)
+
 
     def process_links(self, datatype, section: Section, **kwargs):
         # add files link item
         if self.is_record_profile:
             if "links_search" in section.config:
                 section.config.pop("links_search")
             for link in section.config["links_item"]:
```

### Comparing `oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_model/__init__.py` & `oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/datatypes/components/draft_model/__init__.py`

 * *Files identical despite different names*

### Comparing `oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_model/defaults.py` & `oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/datatypes/components/draft_model/defaults.py`

 * *Files identical despite different names*

### Comparing `oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_model/draft_parent.py` & `oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/datatypes/components/draft_model/draft_parent.py`

 * *Files identical despite different names*

### Comparing `oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_model/jsonschema.py` & `oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/datatypes/components/draft_model/jsonschema.py`

 * *Files identical despite different names*

### Comparing `oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_model/mapping.py` & `oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/datatypes/components/draft_model/mapping.py`

 * *Files identical despite different names*

### Comparing `oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_model/pid.py` & `oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/datatypes/components/draft_model/pid.py`

 * *Files identical despite different names*

### Comparing `oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_model/record.py` & `oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/datatypes/components/draft_model/record.py`

 * *Files identical despite different names*

### Comparing `oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_model/record_metadata.py` & `oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/datatypes/components/draft_model/record_metadata.py`

 * *Files identical despite different names*

### Comparing `oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_model/resource.py` & `oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/datatypes/components/draft_model/resource.py`

 * *Files identical despite different names*

### Comparing `oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_model/service.py` & `oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/datatypes/components/draft_model/service.py`

 * *Files identical despite different names*

### Comparing `oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/datatypes/components/draft_tests.py` & `oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/datatypes/components/draft_tests.py`

 * *Files identical despite different names*

### Comparing `oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/__init__.py` & `oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/invenio/__init__.py`

 * *Files identical despite different names*

### Comparing `oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/invenio_drafts_parent_record.py` & `oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/invenio/invenio_drafts_parent_record.py`

 * *Files identical despite different names*

### Comparing `oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/invenio_drafts_record_metadata_extra_fields.py` & `oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/invenio/invenio_drafts_record_metadata_extra_fields.py`

 * *Files identical despite different names*

### Comparing `oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/templates/invenio_drafts_parent_record.py.jinja2` & `oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/invenio/templates/invenio_drafts_parent_record.py.jinja2`

 * *Files identical despite different names*

### Comparing `oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/invenio/templates/invenio_drafts_parent_state.py.jinja2` & `oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/invenio/templates/invenio_drafts_parent_state.py.jinja2`

 * *Files identical despite different names*

### Comparing `oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/profiles/draft.py` & `oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/profiles/draft.py`

 * *Files 8% similar despite different names*

```diff
@@ -16,15 +16,16 @@
         profile: str,
         model_path: List[str],
         output_directory: Union[str, Path],
         builder: ModelBuilder,
         **kwargs,
     ):
         parent_record = model.get_schema_section("record", model_path[:-1])
-        dict_setdefault(model.schema, model_path, default={})
+        if not dict_get(model.schema, model_path): #todo the record profile builders could present a problem if this situation means nothing related to drafts will be generated but the plugin is installed
+            return
         draft_profile = dict_get(model.schema, model_path)
         draft_profile["type"] = "draft_record"
 
         # pass the parent record as an extra context item. This will be handled by file-aware
         # components in their "prepare" method
         super().build(
             model=model,
```

### Comparing `oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/tests/invenio_drafts_conftest.py` & `oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/tests/invenio_drafts_conftest.py`

 * *Files identical despite different names*

### Comparing `oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/tests/invenio_drafts_test_resources.py` & `oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/tests/invenio_drafts_test_resources.py`

 * *Files identical despite different names*

### Comparing `oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts/tests/templates/invenio_test_resources.py.jinja2` & `oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts/tests/templates/invenio_test_resources.py.jinja2`

 * *Files identical despite different names*

### Comparing `oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts.egg-info/SOURCES.txt` & `oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `oarepo-model-builder-drafts-1.0.3/oarepo_model_builder_drafts.egg-info/entry_points.txt` & `oarepo-model-builder-drafts-1.0.4/oarepo_model_builder_drafts.egg-info/entry_points.txt`

 * *Files identical despite different names*

### Comparing `oarepo-model-builder-drafts-1.0.3/setup.cfg` & `oarepo-model-builder-drafts-1.0.4/setup.cfg`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [metadata]
 name = oarepo-model-builder-drafts
-version = 1.0.3
+version = 1.0.4
 description = 
 authors = Ronald Krist <krist@cesnet.cz>
 readme = README.md
 long_description = file:README.md
 long_description_content_type = text/markdown
 
 [options]
```


# Comparing `tmp/akerbp.mlops-3.2.1a0.tar.gz` & `tmp/akerbp.mlops-3.2.1a1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "/opt/atlassian/pipelines/agent/build/dist/.tmp-zgruussn/akerbp.mlops-3.2.1a0.tar", last modified: Wed Jun 28 08:55:00 2023, max compression
+gzip compressed data, was "/opt/atlassian/pipelines/agent/build/dist/.tmp-eafljzo3/akerbp.mlops-3.2.1a1.tar", last modified: Wed Jun 28 10:48:36 2023, max compression
```

## Comparing `akerbp.mlops-3.2.1a0.tar` & `akerbp.mlops-3.2.1a1.tar`

### file list

```diff
@@ -1,86 +1,86 @@
-drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 08:55:00.185714 akerbp.mlops-3.2.1a0/
--rw-rw-rw-   0 root         (0) root         (0)      637 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/.flake8
--rw-rw-rw-   0 root         (0) root         (0)      225 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/.gitattributes
--rw-rw-rw-   0 root         (0) root         (0)      324 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/.gitignore
--rw-rw-rw-   0 root         (0) root         (0)      663 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/.pre-commit-config.yaml
--rw-rw-rw-   0 root         (0) root         (0)    11320 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/LICENSE
--rw-rw-rw-   0 root         (0) root         (0)    48989 2023-06-28 08:55:00.185714 akerbp.mlops-3.2.1a0/PKG-INFO
--rw-rw-rw-   0 root         (0) root         (0)    35467 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/README.md
--rw-rw-rw-   0 root         (0) root         (0)     4229 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/bitbucket-pipelines.yml
-drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 08:55:00.177713 akerbp.mlops-3.2.1a0/bitbucket_pipeline_helpers/
--rw-rw-rw-   0 root         (0) root         (0)      373 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/bitbucket_pipeline_helpers/promote_dummy_artifacts.py
--rw-rw-rw-   0 root         (0) root         (0)      286 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/bitbucket_pipeline_helpers/remove_dummy_artifacts.py
--rw-rw-rw-   0 root         (0) root         (0)      355 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/bitbucket_pipeline_helpers/upload_dummy_artifacts.py
--rw-rw-rw-   0 root         (0) root         (0)     1183 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/build.sh
--rw-rw-rw-   0 root         (0) root         (0)     3740 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/increment_package_version.py
--rw-rw-rw-   0 root         (0) root         (0)      207 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/install.sh
--rw-rw-rw-   0 root         (0) root         (0)     1023 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/mlops_settings.yaml
-drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 08:55:00.177713 akerbp.mlops-3.2.1a0/model_artifact/
--rw-rw-rw-   0 root         (0) root         (0)      187 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/model_artifact/README.md
--rw-rw-rw-   0 root         (0) root         (0)      255 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/model_artifact/mlpet_settings.yaml
-drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 08:55:00.177713 akerbp.mlops-3.2.1a0/model_code/
--rw-rw-rw-   0 root         (0) root         (0)     9932 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/model_code/model.py
--rw-rw-rw-   0 root         (0) root         (0)      127 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/model_code/requirements.model
--rw-rw-rw-   0 root         (0) root         (0)     5427 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/model_code/test_model.py
--rw-rw-rw-   0 root         (0) root         (0)      338 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/mypy.ini
--rw-rw-rw-   0 root         (0) root         (0)     1639 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/pyproject.toml
--rw-rw-rw-   0 root         (0) root         (0)       38 2023-06-28 08:55:00.185714 akerbp.mlops-3.2.1a0/setup.cfg
--rw-rw-rw-   0 root         (0) root         (0)       69 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/setup.py
-drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 08:55:00.173714 akerbp.mlops-3.2.1a0/src/
-drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 08:55:00.173714 akerbp.mlops-3.2.1a0/src/akerbp/
-drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 08:55:00.177713 akerbp.mlops-3.2.1a0/src/akerbp/mlops/
--rw-rw-rw-   0 root         (0) root         (0)       57 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/src/akerbp/mlops/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)       19 2023-06-28 08:55:00.000000 akerbp.mlops-3.2.1a0/src/akerbp/mlops/_version.py
-drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 08:55:00.181714 akerbp.mlops-3.2.1a0/src/akerbp/mlops/cdf/
--rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/src/akerbp/mlops/cdf/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)      314 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/src/akerbp/mlops/cdf/download_function_file.py
--rw-rw-rw-   0 root         (0) root         (0)     3115 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/src/akerbp/mlops/cdf/handler.py
--rw-rw-rw-   0 root         (0) root         (0)    38950 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/src/akerbp/mlops/cdf/helpers.py
-drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 08:55:00.181714 akerbp.mlops-3.2.1a0/src/akerbp/mlops/core/
--rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/src/akerbp/mlops/core/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)    16504 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/src/akerbp/mlops/core/config.py
--rw-rw-rw-   0 root         (0) root         (0)     1211 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/src/akerbp/mlops/core/exceptions.py
--rw-rw-rw-   0 root         (0) root         (0)     6474 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/src/akerbp/mlops/core/helpers.py
--rw-rw-rw-   0 root         (0) root         (0)     2162 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/src/akerbp/mlops/core/logger.py
--rw-rw-rw-   0 root         (0) root         (0)      551 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/src/akerbp/mlops/core/logger_config.py
--rw-rw-rw-   0 root         (0) root         (0)     2771 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/src/akerbp/mlops/core/mappings.py
-drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 08:55:00.181714 akerbp.mlops-3.2.1a0/src/akerbp/mlops/deployment/
--rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/src/akerbp/mlops/deployment/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)     1321 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/src/akerbp/mlops/deployment/bitbucket-pipelines.yml
--rw-rw-rw-   0 root         (0) root         (0)     5828 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/src/akerbp/mlops/deployment/deploy.py
--rw-rw-rw-   0 root         (0) root         (0)      195 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/src/akerbp/mlops/deployment/deploy_prediction_service.py
--rw-rw-rw-   0 root         (0) root         (0)      241 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/src/akerbp/mlops/deployment/deploy_training_service.py
--rw-rw-rw-   0 root         (0) root         (0)    21208 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/src/akerbp/mlops/deployment/helpers.py
--rw-rw-rw-   0 root         (0) root         (0)      835 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/src/akerbp/mlops/deployment/platforms.py
--rw-rw-rw-   0 root         (0) root         (0)     5062 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/src/akerbp/mlops/deployment/setup.py
-drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 08:55:00.181714 akerbp.mlops-3.2.1a0/src/akerbp/mlops/model_manager/
--rw-rw-rw-   0 root         (0) root         (0)       55 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/src/akerbp/mlops/model_manager/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)    22658 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/src/akerbp/mlops/model_manager/model_manager.py
-drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 08:55:00.181714 akerbp.mlops-3.2.1a0/src/akerbp/mlops/services/
--rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/src/akerbp/mlops/services/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)     8607 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/src/akerbp/mlops/services/prediction.py
--rw-rw-rw-   0 root         (0) root         (0)     3925 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/src/akerbp/mlops/services/test_service.py
--rw-rw-rw-   0 root         (0) root         (0)     1833 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/src/akerbp/mlops/services/training.py
-drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 08:55:00.177713 akerbp.mlops-3.2.1a0/src/akerbp.mlops.egg-info/
--rw-rw-rw-   0 root         (0) root         (0)    48989 2023-06-28 08:55:00.000000 akerbp.mlops-3.2.1a0/src/akerbp.mlops.egg-info/PKG-INFO
--rw-rw-rw-   0 root         (0) root         (0)     2394 2023-06-28 08:55:00.000000 akerbp.mlops-3.2.1a0/src/akerbp.mlops.egg-info/SOURCES.txt
--rw-rw-rw-   0 root         (0) root         (0)        1 2023-06-28 08:55:00.000000 akerbp.mlops-3.2.1a0/src/akerbp.mlops.egg-info/dependency_links.txt
--rw-rw-rw-   0 root         (0) root         (0)      180 2023-06-28 08:55:00.000000 akerbp.mlops-3.2.1a0/src/akerbp.mlops.egg-info/entry_points.txt
--rw-rw-rw-   0 root         (0) root         (0)      191 2023-06-28 08:55:00.000000 akerbp.mlops-3.2.1a0/src/akerbp.mlops.egg-info/requires.txt
--rw-rw-rw-   0 root         (0) root         (0)        7 2023-06-28 08:55:00.000000 akerbp.mlops-3.2.1a0/src/akerbp.mlops.egg-info/top_level.txt
-drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 08:55:00.185714 akerbp.mlops-3.2.1a0/test/
--rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/test/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)    11480 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/test/test_data_validation.py
--rw-rw-rw-   0 root         (0) root         (0)     2697 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/test/test_install_requirements.py
--rw-rw-rw-   0 root         (0) root         (0)     1547 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/test/test_metadata_validation.py
--rw-rw-rw-   0 root         (0) root         (0)       15 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/test/test_requirements.txt
-drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 08:55:00.185714 akerbp.mlops-3.2.1a0/test/test_settings/
--rw-rw-rw-   0 root         (0) root         (0)      721 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/test/test_settings/installing_reqs_in_venv.yaml
--rw-rw-rw-   0 root         (0) root         (0)     1341 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/test/test_settings/multiple_models_all_required_fields.yaml
--rw-rw-rw-   0 root         (0) root         (0)     1267 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/test/test_settings/multiple_models_missing_field.yaml
--rw-rw-rw-   0 root         (0) root         (0)      674 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/test/test_settings/single_model_all_required_fields.yaml
--rw-rw-rw-   0 root         (0) root         (0)      713 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/test/test_settings/single_model_missing_field.yaml
--rw-rw-rw-   0 root         (0) root         (0)      675 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/test/test_settings/single_model_missing_petrel_field.yaml
--rw-rw-rw-   0 root         (0) root         (0)      636 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/test/test_settings/single_model_no_required_input.yaml
--rw-rw-rw-   0 root         (0) root         (0)      677 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/test/test_settings/single_model_required_input.yaml
--rw-rw-rw-   0 root         (0) root         (0)     3562 2023-06-28 08:54:36.000000 akerbp.mlops-3.2.1a0/test/test_version_increment.py
+drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 10:48:36.481123 akerbp.mlops-3.2.1a1/
+-rw-rw-rw-   0 root         (0) root         (0)      637 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/.flake8
+-rw-rw-rw-   0 root         (0) root         (0)      225 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/.gitattributes
+-rw-rw-rw-   0 root         (0) root         (0)      324 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/.gitignore
+-rw-rw-rw-   0 root         (0) root         (0)      663 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/.pre-commit-config.yaml
+-rw-rw-rw-   0 root         (0) root         (0)    11320 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/LICENSE
+-rw-rw-rw-   0 root         (0) root         (0)    48989 2023-06-28 10:48:36.481123 akerbp.mlops-3.2.1a1/PKG-INFO
+-rw-rw-rw-   0 root         (0) root         (0)    35467 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/README.md
+-rw-rw-rw-   0 root         (0) root         (0)     4229 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/bitbucket-pipelines.yml
+drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 10:48:36.473123 akerbp.mlops-3.2.1a1/bitbucket_pipeline_helpers/
+-rw-rw-rw-   0 root         (0) root         (0)      373 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/bitbucket_pipeline_helpers/promote_dummy_artifacts.py
+-rw-rw-rw-   0 root         (0) root         (0)      286 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/bitbucket_pipeline_helpers/remove_dummy_artifacts.py
+-rw-rw-rw-   0 root         (0) root         (0)      355 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/bitbucket_pipeline_helpers/upload_dummy_artifacts.py
+-rw-rw-rw-   0 root         (0) root         (0)     1183 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/build.sh
+-rw-rw-rw-   0 root         (0) root         (0)     3740 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/increment_package_version.py
+-rw-rw-rw-   0 root         (0) root         (0)      207 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/install.sh
+-rw-rw-rw-   0 root         (0) root         (0)     1023 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/mlops_settings.yaml
+drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 10:48:36.473123 akerbp.mlops-3.2.1a1/model_artifact/
+-rw-rw-rw-   0 root         (0) root         (0)      187 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/model_artifact/README.md
+-rw-rw-rw-   0 root         (0) root         (0)      255 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/model_artifact/mlpet_settings.yaml
+drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 10:48:36.473123 akerbp.mlops-3.2.1a1/model_code/
+-rw-rw-rw-   0 root         (0) root         (0)     9932 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/model_code/model.py
+-rw-rw-rw-   0 root         (0) root         (0)      127 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/model_code/requirements.model
+-rw-rw-rw-   0 root         (0) root         (0)     5427 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/model_code/test_model.py
+-rw-rw-rw-   0 root         (0) root         (0)      338 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/mypy.ini
+-rw-rw-rw-   0 root         (0) root         (0)     1639 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/pyproject.toml
+-rw-rw-rw-   0 root         (0) root         (0)       38 2023-06-28 10:48:36.481123 akerbp.mlops-3.2.1a1/setup.cfg
+-rw-rw-rw-   0 root         (0) root         (0)       69 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/setup.py
+drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 10:48:36.469123 akerbp.mlops-3.2.1a1/src/
+drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 10:48:36.469123 akerbp.mlops-3.2.1a1/src/akerbp/
+drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 10:48:36.477123 akerbp.mlops-3.2.1a1/src/akerbp/mlops/
+-rw-rw-rw-   0 root         (0) root         (0)       57 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/src/akerbp/mlops/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)       19 2023-06-28 10:48:36.000000 akerbp.mlops-3.2.1a1/src/akerbp/mlops/_version.py
+drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 10:48:36.477123 akerbp.mlops-3.2.1a1/src/akerbp/mlops/cdf/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/src/akerbp/mlops/cdf/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)      314 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/src/akerbp/mlops/cdf/download_function_file.py
+-rw-rw-rw-   0 root         (0) root         (0)     3115 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/src/akerbp/mlops/cdf/handler.py
+-rw-rw-rw-   0 root         (0) root         (0)    38715 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/src/akerbp/mlops/cdf/helpers.py
+drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 10:48:36.477123 akerbp.mlops-3.2.1a1/src/akerbp/mlops/core/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/src/akerbp/mlops/core/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)    16504 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/src/akerbp/mlops/core/config.py
+-rw-rw-rw-   0 root         (0) root         (0)     1211 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/src/akerbp/mlops/core/exceptions.py
+-rw-rw-rw-   0 root         (0) root         (0)     6474 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/src/akerbp/mlops/core/helpers.py
+-rw-rw-rw-   0 root         (0) root         (0)     2162 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/src/akerbp/mlops/core/logger.py
+-rw-rw-rw-   0 root         (0) root         (0)      551 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/src/akerbp/mlops/core/logger_config.py
+-rw-rw-rw-   0 root         (0) root         (0)     2771 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/src/akerbp/mlops/core/mappings.py
+drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 10:48:36.477123 akerbp.mlops-3.2.1a1/src/akerbp/mlops/deployment/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/src/akerbp/mlops/deployment/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)     1321 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/src/akerbp/mlops/deployment/bitbucket-pipelines.yml
+-rw-rw-rw-   0 root         (0) root         (0)     5828 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/src/akerbp/mlops/deployment/deploy.py
+-rw-rw-rw-   0 root         (0) root         (0)      195 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/src/akerbp/mlops/deployment/deploy_prediction_service.py
+-rw-rw-rw-   0 root         (0) root         (0)      241 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/src/akerbp/mlops/deployment/deploy_training_service.py
+-rw-rw-rw-   0 root         (0) root         (0)    21249 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/src/akerbp/mlops/deployment/helpers.py
+-rw-rw-rw-   0 root         (0) root         (0)      835 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/src/akerbp/mlops/deployment/platforms.py
+-rw-rw-rw-   0 root         (0) root         (0)     5062 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/src/akerbp/mlops/deployment/setup.py
+drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 10:48:36.481123 akerbp.mlops-3.2.1a1/src/akerbp/mlops/model_manager/
+-rw-rw-rw-   0 root         (0) root         (0)       55 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/src/akerbp/mlops/model_manager/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)    22835 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/src/akerbp/mlops/model_manager/model_manager.py
+drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 10:48:36.481123 akerbp.mlops-3.2.1a1/src/akerbp/mlops/services/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/src/akerbp/mlops/services/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)     8607 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/src/akerbp/mlops/services/prediction.py
+-rw-rw-rw-   0 root         (0) root         (0)     3925 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/src/akerbp/mlops/services/test_service.py
+-rw-rw-rw-   0 root         (0) root         (0)     1833 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/src/akerbp/mlops/services/training.py
+drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 10:48:36.477123 akerbp.mlops-3.2.1a1/src/akerbp.mlops.egg-info/
+-rw-rw-rw-   0 root         (0) root         (0)    48989 2023-06-28 10:48:36.000000 akerbp.mlops-3.2.1a1/src/akerbp.mlops.egg-info/PKG-INFO
+-rw-rw-rw-   0 root         (0) root         (0)     2394 2023-06-28 10:48:36.000000 akerbp.mlops-3.2.1a1/src/akerbp.mlops.egg-info/SOURCES.txt
+-rw-rw-rw-   0 root         (0) root         (0)        1 2023-06-28 10:48:36.000000 akerbp.mlops-3.2.1a1/src/akerbp.mlops.egg-info/dependency_links.txt
+-rw-rw-rw-   0 root         (0) root         (0)      180 2023-06-28 10:48:36.000000 akerbp.mlops-3.2.1a1/src/akerbp.mlops.egg-info/entry_points.txt
+-rw-rw-rw-   0 root         (0) root         (0)      191 2023-06-28 10:48:36.000000 akerbp.mlops-3.2.1a1/src/akerbp.mlops.egg-info/requires.txt
+-rw-rw-rw-   0 root         (0) root         (0)        7 2023-06-28 10:48:36.000000 akerbp.mlops-3.2.1a1/src/akerbp.mlops.egg-info/top_level.txt
+drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 10:48:36.481123 akerbp.mlops-3.2.1a1/test/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/test/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)    11480 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/test/test_data_validation.py
+-rw-rw-rw-   0 root         (0) root         (0)     2697 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/test/test_install_requirements.py
+-rw-rw-rw-   0 root         (0) root         (0)     1547 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/test/test_metadata_validation.py
+-rw-rw-rw-   0 root         (0) root         (0)       15 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/test/test_requirements.txt
+drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 10:48:36.481123 akerbp.mlops-3.2.1a1/test/test_settings/
+-rw-rw-rw-   0 root         (0) root         (0)      721 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/test/test_settings/installing_reqs_in_venv.yaml
+-rw-rw-rw-   0 root         (0) root         (0)     1341 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/test/test_settings/multiple_models_all_required_fields.yaml
+-rw-rw-rw-   0 root         (0) root         (0)     1267 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/test/test_settings/multiple_models_missing_field.yaml
+-rw-rw-rw-   0 root         (0) root         (0)      674 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/test/test_settings/single_model_all_required_fields.yaml
+-rw-rw-rw-   0 root         (0) root         (0)      713 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/test/test_settings/single_model_missing_field.yaml
+-rw-rw-rw-   0 root         (0) root         (0)      675 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/test/test_settings/single_model_missing_petrel_field.yaml
+-rw-rw-rw-   0 root         (0) root         (0)      636 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/test/test_settings/single_model_no_required_input.yaml
+-rw-rw-rw-   0 root         (0) root         (0)      677 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/test/test_settings/single_model_required_input.yaml
+-rw-rw-rw-   0 root         (0) root         (0)     3562 2023-06-28 10:48:08.000000 akerbp.mlops-3.2.1a1/test/test_version_increment.py
```

### Comparing `akerbp.mlops-3.2.1a0/.flake8` & `akerbp.mlops-3.2.1a1/.flake8`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/.pre-commit-config.yaml` & `akerbp.mlops-3.2.1a1/.pre-commit-config.yaml`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/LICENSE` & `akerbp.mlops-3.2.1a1/LICENSE`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/PKG-INFO` & `akerbp.mlops-3.2.1a1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: akerbp.mlops
-Version: 3.2.1a0
+Version: 3.2.1a1
 Summary: MLOps framework
 Author-email: "Alfonso M. Canterla" <alfonso.canterla@soprasteria.com>
 Maintainer-email: "Christian N. Lehre" <christian.lehre@soprasteria.com>
 License:             Apache License
                                    Version 2.0, January 2004
                                 http://www.apache.org/licenses/
```

### Comparing `akerbp.mlops-3.2.1a0/README.md` & `akerbp.mlops-3.2.1a1/README.md`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/bitbucket-pipelines.yml` & `akerbp.mlops-3.2.1a1/bitbucket-pipelines.yml`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/build.sh` & `akerbp.mlops-3.2.1a1/build.sh`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/increment_package_version.py` & `akerbp.mlops-3.2.1a1/increment_package_version.py`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/mlops_settings.yaml` & `akerbp.mlops-3.2.1a1/mlops_settings.yaml`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/model_code/model.py` & `akerbp.mlops-3.2.1a1/model_code/model.py`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/model_code/test_model.py` & `akerbp.mlops-3.2.1a1/model_code/test_model.py`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/pyproject.toml` & `akerbp.mlops-3.2.1a1/pyproject.toml`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/src/akerbp/mlops/cdf/handler.py` & `akerbp.mlops-3.2.1a1/src/akerbp/mlops/cdf/handler.py`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/src/akerbp/mlops/cdf/helpers.py` & `akerbp.mlops-3.2.1a1/src/akerbp/mlops/cdf/helpers.py`

 * *Files 2% similar despite different names*

```diff
@@ -413,19 +413,14 @@
             mlpet_version = "not found"
         metadata["akerbp.mlpet_version"] = mlpet_version  # type: ignore
     except KeyError:
         raise Exception(
             "Metadata field is missing, please update mlops_settings.yaml"
         ) from None
 
-    # Tag with version number in case of numbered artifact version
-    if len(function_name.split("_")) == 4:
-        artifact_version = function_name.split("-")[-1]
-        metadata["version"] = str(artifact_version)  # type: ignore
-
     f = functools.partial(
         create_function_from_folder,
         human_readable_name,
         function_name,
         folder,
         handler_path,
         description,
```

### Comparing `akerbp.mlops-3.2.1a0/src/akerbp/mlops/core/config.py` & `akerbp.mlops-3.2.1a1/src/akerbp/mlops/core/config.py`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/src/akerbp/mlops/core/exceptions.py` & `akerbp.mlops-3.2.1a1/src/akerbp/mlops/core/exceptions.py`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/src/akerbp/mlops/core/helpers.py` & `akerbp.mlops-3.2.1a1/src/akerbp/mlops/core/helpers.py`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/src/akerbp/mlops/core/logger.py` & `akerbp.mlops-3.2.1a1/src/akerbp/mlops/core/logger.py`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/src/akerbp/mlops/core/logger_config.py` & `akerbp.mlops-3.2.1a1/src/akerbp/mlops/core/logger_config.py`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/src/akerbp/mlops/core/mappings.py` & `akerbp.mlops-3.2.1a1/src/akerbp/mlops/core/mappings.py`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/src/akerbp/mlops/deployment/bitbucket-pipelines.yml` & `akerbp.mlops-3.2.1a1/src/akerbp/mlops/deployment/bitbucket-pipelines.yml`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/src/akerbp/mlops/deployment/deploy.py` & `akerbp.mlops-3.2.1a1/src/akerbp/mlops/deployment/deploy.py`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/src/akerbp/mlops/deployment/helpers.py` & `akerbp.mlops-3.2.1a1/src/akerbp/mlops/deployment/helpers.py`

 * *Files 1% similar despite different names*

```diff
@@ -5,15 +5,15 @@
 import shutil
 import subprocess
 import sys
 import tempfile
 import venv
 from importlib import resources as importlib_resources
 from pathlib import Path
-from typing import Any, Dict, Optional
+from typing import Any, Dict, Optional, Union
 
 import akerbp.mlops as akerbp_mlops
 from akerbp.mlops.cdf import helpers as cdf
 from akerbp.mlops.core.config import ENV_VARS, ServiceSettings
 from akerbp.mlops.core.exceptions import (
     DeploymentError,
     TestError,
@@ -581,14 +581,15 @@
         logger.info(
             f"Redeploying numbered model {c.human_friendly_model_name} with external id {external_id} to {platform} in {env}"
         )
         redeploy_model_with_numbered_external_id(
             c,
             numbered_external_id=numbered_external_id,
             test_payload=test_payload,
+            info=model_info,
         )
 
     if platform == "cdf":
         logger.info("Initiating garbage collection of old, numbered model versions")
         cdf.garbage_collection(
             c,
             function_name,
@@ -597,24 +598,24 @@
         )
 
 
 def redeploy_model_with_numbered_external_id(
     c: ServiceSettings,
     numbered_external_id: str,
     test_payload: Any,
+    info: Dict[str, Union[str, Dict[str, str]]],
     platform_methods: Dict = platform_methods,
 ) -> None:
     deploy_function, _, test_function = platform_methods[c.platform]
 
-    model_info = c.info[service_name]
     try:
         deploy_function(
             c.human_friendly_model_name,
             numbered_external_id,
-            info=model_info,
+            info=info,
         )
     except Exception as e:
         raise DeploymentError(
             f"Redeployment of numbered model failed with message:  \n{str(e)}"
         ) from e
 
     if c.test_file:
```

### Comparing `akerbp.mlops-3.2.1a0/src/akerbp/mlops/deployment/platforms.py` & `akerbp.mlops-3.2.1a1/src/akerbp/mlops/deployment/platforms.py`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/src/akerbp/mlops/deployment/setup.py` & `akerbp.mlops-3.2.1a1/src/akerbp/mlops/deployment/setup.py`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/src/akerbp/mlops/model_manager/model_manager.py` & `akerbp.mlops-3.2.1a1/src/akerbp/mlops/model_manager/model_manager.py`

 * *Files 1% similar despite different names*

```diff
@@ -511,14 +511,19 @@
         functions_client = cdf.get_client(
             client_id=client_secrets["id-write"],
             client_secret=client_secrets["secret-write"],
         )
         latest_deployed_model = functions_client.functions.retrieve(
             external_id=external_id_function
         )
+
+        if latest_deployed_model is None:
+            raise ValueError(
+                f"Function with external id {external_id_function} does not exist in CDF"
+            )
         try:
             version = latest_deployed_model.metadata["version"]
 
         except KeyError:
             logger.warn(
                 f"Deployed function with external id {external_id_function} does not have a version attribute in the metadata"
             )
```

### Comparing `akerbp.mlops-3.2.1a0/src/akerbp/mlops/services/prediction.py` & `akerbp.mlops-3.2.1a1/src/akerbp/mlops/services/prediction.py`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/src/akerbp/mlops/services/test_service.py` & `akerbp.mlops-3.2.1a1/src/akerbp/mlops/services/test_service.py`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/src/akerbp/mlops/services/training.py` & `akerbp.mlops-3.2.1a1/src/akerbp/mlops/services/training.py`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/src/akerbp.mlops.egg-info/PKG-INFO` & `akerbp.mlops-3.2.1a1/src/akerbp.mlops.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: akerbp.mlops
-Version: 3.2.1a0
+Version: 3.2.1a1
 Summary: MLOps framework
 Author-email: "Alfonso M. Canterla" <alfonso.canterla@soprasteria.com>
 Maintainer-email: "Christian N. Lehre" <christian.lehre@soprasteria.com>
 License:             Apache License
                                    Version 2.0, January 2004
                                 http://www.apache.org/licenses/
```

### Comparing `akerbp.mlops-3.2.1a0/src/akerbp.mlops.egg-info/SOURCES.txt` & `akerbp.mlops-3.2.1a1/src/akerbp.mlops.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/test/test_data_validation.py` & `akerbp.mlops-3.2.1a1/test/test_data_validation.py`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/test/test_install_requirements.py` & `akerbp.mlops-3.2.1a1/test/test_install_requirements.py`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/test/test_metadata_validation.py` & `akerbp.mlops-3.2.1a1/test/test_metadata_validation.py`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/test/test_settings/installing_reqs_in_venv.yaml` & `akerbp.mlops-3.2.1a1/test/test_settings/installing_reqs_in_venv.yaml`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/test/test_settings/multiple_models_all_required_fields.yaml` & `akerbp.mlops-3.2.1a1/test/test_settings/multiple_models_all_required_fields.yaml`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/test/test_settings/multiple_models_missing_field.yaml` & `akerbp.mlops-3.2.1a1/test/test_settings/multiple_models_missing_field.yaml`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/test/test_settings/single_model_all_required_fields.yaml` & `akerbp.mlops-3.2.1a1/test/test_settings/single_model_all_required_fields.yaml`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/test/test_settings/single_model_missing_field.yaml` & `akerbp.mlops-3.2.1a1/test/test_settings/single_model_missing_field.yaml`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/test/test_settings/single_model_missing_petrel_field.yaml` & `akerbp.mlops-3.2.1a1/test/test_settings/single_model_missing_petrel_field.yaml`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/test/test_settings/single_model_no_required_input.yaml` & `akerbp.mlops-3.2.1a1/test/test_settings/single_model_no_required_input.yaml`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/test/test_settings/single_model_required_input.yaml` & `akerbp.mlops-3.2.1a1/test/test_settings/single_model_required_input.yaml`

 * *Files identical despite different names*

### Comparing `akerbp.mlops-3.2.1a0/test/test_version_increment.py` & `akerbp.mlops-3.2.1a1/test/test_version_increment.py`

 * *Files identical despite different names*


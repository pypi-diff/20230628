# Comparing `tmp/fractal_server-1.3.1.tar.gz` & `tmp/fractal_server-1.3.2a0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "fractal_server-1.3.1.tar", max compression
+gzip compressed data, was "fractal_server-1.3.2a0.tar", max compression
```

## Comparing `fractal_server-1.3.1.tar` & `fractal_server-1.3.2a0.tar`

### file list

```diff
@@ -1,99 +1,99 @@
--rw-r--r--   0        0        0     1576 2023-06-23 06:18:06.498772 fractal_server-1.3.1/LICENSE
--rw-r--r--   0        0        0     2100 2023-06-23 06:18:06.498772 fractal_server-1.3.1/README.md
--rw-r--r--   0        0        0       69 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/.gitignore
--rw-r--r--   0        0        0       22 2023-06-27 14:52:47.431576 fractal_server-1.3.1/fractal_server/__init__.py
--rw-r--r--   0        0        0     2202 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/__main__.py
--rw-r--r--   0        0        0     3153 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/alembic.ini
--rw-r--r--   0        0        0        0 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/app/__init__.py
--rw-r--r--   0        0        0     1242 2023-06-27 14:23:44.473555 fractal_server-1.3.1/fractal_server/app/api/__init__.py
--rw-r--r--   0        0        0       24 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/app/api/v1/__init__.py
--rw-r--r--   0        0        0     7622 2023-06-27 14:28:32.735643 fractal_server-1.3.1/fractal_server/app/api/v1/_aux_functions.py
--rw-r--r--   0        0        0     7624 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/app/api/v1/dataset.py
--rw-r--r--   0        0        0     4990 2023-06-27 14:51:02.824508 fractal_server-1.3.1/fractal_server/app/api/v1/job.py
--rw-r--r--   0        0        0     8880 2023-06-27 14:30:25.873556 fractal_server-1.3.1/fractal_server/app/api/v1/project.py
--rw-r--r--   0        0        0     5516 2023-06-27 14:23:44.473555 fractal_server-1.3.1/fractal_server/app/api/v1/task.py
--rw-r--r--   0        0        0    10831 2023-06-27 14:23:44.473555 fractal_server-1.3.1/fractal_server/app/api/v1/task_collection.py
--rw-r--r--   0        0        0     9246 2023-06-27 14:23:44.473555 fractal_server-1.3.1/fractal_server/app/api/v1/workflow.py
--rw-r--r--   0        0        0     5165 2023-06-27 14:23:44.473555 fractal_server-1.3.1/fractal_server/app/api/v1/workflowtask.py
--rw-r--r--   0        0        0     3081 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/app/db/__init__.py
--rw-r--r--   0        0        0      372 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/app/models/__init__.py
--rw-r--r--   0        0        0     3412 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/app/models/job.py
--rw-r--r--   0        0        0      309 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/app/models/linkuserproject.py
--rw-r--r--   0        0        0     2355 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/app/models/project.py
--rw-r--r--   0        0        0     2563 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/app/models/security.py
--rw-r--r--   0        0        0     1119 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/app/models/state.py
--rw-r--r--   0        0        0     2535 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/app/models/task.py
--rw-r--r--   0        0        0     5205 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/app/models/workflow.py
--rw-r--r--   0        0        0       16 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/app/runner/.gitignore
--rw-r--r--   0        0        0    10102 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/app/runner/__init__.py
--rw-r--r--   0        0        0    19523 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/app/runner/_common.py
--rw-r--r--   0        0        0     5464 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/app/runner/_local/__init__.py
--rw-r--r--   0        0        0     3245 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/app/runner/_local/_local_config.py
--rw-r--r--   0        0        0     1631 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/app/runner/_local/_submit_setup.py
--rw-r--r--   0        0        0     3620 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/app/runner/_local/executor.py
--rw-r--r--   0        0        0       16 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/app/runner/_slurm/.gitignore
--rw-r--r--   0        0        0     3839 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/app/runner/_slurm/__init__.py
--rw-r--r--   0        0        0     8840 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/app/runner/_slurm/_batching.py
--rw-r--r--   0        0        0     4331 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/app/runner/_slurm/_executor_wait_thread.py
--rw-r--r--   0        0        0    19766 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/app/runner/_slurm/_slurm_config.py
--rw-r--r--   0        0        0     2942 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/app/runner/_slurm/_submit_setup.py
--rw-r--r--   0        0        0     4534 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/app/runner/_slurm/_subprocess_run_as_user.py
--rw-r--r--   0        0        0    42200 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/app/runner/_slurm/executor.py
--rw-r--r--   0        0        0     5852 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/app/runner/_slurm/remote.py
--rw-r--r--   0        0        0     7900 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/app/runner/common.py
--rw-r--r--   0        0        0    11324 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/app/security/__init__.py
--rw-r--r--   0        0        0       49 2023-06-26 06:59:30.472776 fractal_server-1.3.1/fractal_server/common/.git
--rw-r--r--   0        0        0      717 2023-06-26 06:59:30.480776 fractal_server-1.3.1/fractal_server/common/.github/workflows/ci.yml
--rw-r--r--   0        0        0      364 2023-06-26 06:59:30.480776 fractal_server-1.3.1/fractal_server/common/.github/workflows/project-management.yml
--rw-r--r--   0        0        0       34 2023-06-26 06:59:30.480776 fractal_server-1.3.1/fractal_server/common/.gitignore
--rw-r--r--   0        0        0      620 2023-06-26 06:59:30.480776 fractal_server-1.3.1/fractal_server/common/.pre-commit-config.yaml
--rw-r--r--   0        0        0     1964 2023-06-26 06:59:30.480776 fractal_server-1.3.1/fractal_server/common/README.md
--rw-r--r--   0        0        0        0 2023-06-26 06:59:30.480776 fractal_server-1.3.1/fractal_server/common/__init__.py
--rw-r--r--   0        0        0      163 2023-06-26 06:59:32.128764 fractal_server-1.3.1/fractal_server/common/__pycache__/__init__.cpython-310.pyc
--rw-r--r--   0        0        0       57 2023-06-26 06:59:30.480776 fractal_server-1.3.1/fractal_server/common/requirements.txt
--rw-r--r--   0        0        0      614 2023-06-26 06:59:30.480776 fractal_server-1.3.1/fractal_server/common/schemas/__init__.py
--rw-r--r--   0        0        0      425 2023-06-26 06:59:32.128764 fractal_server-1.3.1/fractal_server/common/schemas/__pycache__/__init__.cpython-310.pyc
--rw-r--r--   0        0        0     1767 2023-06-26 06:59:32.128764 fractal_server-1.3.1/fractal_server/common/schemas/__pycache__/_validators.cpython-310.pyc
--rw-r--r--   0        0        0     1624 2023-06-26 06:59:32.128764 fractal_server-1.3.1/fractal_server/common/schemas/__pycache__/applyworkflow.cpython-310.pyc
--rw-r--r--   0        0        0     4082 2023-06-26 06:59:32.132763 fractal_server-1.3.1/fractal_server/common/schemas/__pycache__/manifest.cpython-310.pyc
--rw-r--r--   0        0        0     3551 2023-06-26 06:59:32.132763 fractal_server-1.3.1/fractal_server/common/schemas/__pycache__/project.cpython-310.pyc
--rw-r--r--   0        0        0     1179 2023-06-26 06:59:32.140764 fractal_server-1.3.1/fractal_server/common/schemas/__pycache__/state.cpython-310.pyc
--rw-r--r--   0        0        0     2719 2023-06-26 06:59:32.140764 fractal_server-1.3.1/fractal_server/common/schemas/__pycache__/task.cpython-310.pyc
--rw-r--r--   0        0        0     3306 2023-06-26 06:59:32.144764 fractal_server-1.3.1/fractal_server/common/schemas/__pycache__/task_collection.cpython-310.pyc
--rw-r--r--   0        0        0     1216 2023-06-26 06:59:32.148764 fractal_server-1.3.1/fractal_server/common/schemas/__pycache__/user.cpython-310.pyc
--rw-r--r--   0        0        0     3896 2023-06-26 06:59:32.152763 fractal_server-1.3.1/fractal_server/common/schemas/__pycache__/workflow.cpython-310.pyc
--rw-r--r--   0        0        0     1616 2023-06-26 06:59:30.480776 fractal_server-1.3.1/fractal_server/common/schemas/_validators.py
--rw-r--r--   0        0        0     1117 2023-06-26 06:59:30.480776 fractal_server-1.3.1/fractal_server/common/schemas/applyworkflow.py
--rw-r--r--   0        0        0     3479 2023-06-26 06:59:30.480776 fractal_server-1.3.1/fractal_server/common/schemas/manifest.py
--rw-r--r--   0        0        0     2483 2023-06-26 06:59:30.480776 fractal_server-1.3.1/fractal_server/common/schemas/project.py
--rw-r--r--   0        0        0      673 2023-06-26 06:59:30.480776 fractal_server-1.3.1/fractal_server/common/schemas/state.py
--rw-r--r--   0        0        0     2578 2023-06-26 06:59:30.480776 fractal_server-1.3.1/fractal_server/common/schemas/task.py
--rw-r--r--   0        0        0     2935 2023-06-26 06:59:30.480776 fractal_server-1.3.1/fractal_server/common/schemas/task_collection.py
--rw-r--r--   0        0        0     1216 2023-06-26 06:59:30.480776 fractal_server-1.3.1/fractal_server/common/schemas/user.py
--rw-r--r--   0        0        0     2457 2023-06-26 06:59:30.480776 fractal_server-1.3.1/fractal_server/common/schemas/workflow.py
--rw-r--r--   0        0        0      139 2023-06-26 06:59:30.480776 fractal_server-1.3.1/fractal_server/common/tests/conftest.py
--rw-r--r--   0        0        0      298 2023-06-26 06:59:30.480776 fractal_server-1.3.1/fractal_server/common/tests/test_applyworkflow.py
--rw-r--r--   0        0        0     2144 2023-06-26 06:59:30.480776 fractal_server-1.3.1/fractal_server/common/tests/test_dataset.py
--rw-r--r--   0        0        0     1420 2023-06-26 06:59:30.480776 fractal_server-1.3.1/fractal_server/common/tests/test_manifest.py
--rw-r--r--   0        0        0      525 2023-06-26 06:59:30.480776 fractal_server-1.3.1/fractal_server/common/tests/test_project.py
--rw-r--r--   0        0        0      551 2023-06-26 06:59:30.480776 fractal_server-1.3.1/fractal_server/common/tests/test_state.py
--rw-r--r--   0        0        0     1190 2023-06-26 06:59:30.480776 fractal_server-1.3.1/fractal_server/common/tests/test_task.py
--rw-r--r--   0        0        0      968 2023-06-26 06:59:30.480776 fractal_server-1.3.1/fractal_server/common/tests/test_task_collection.py
--rw-r--r--   0        0        0     1499 2023-06-26 06:59:30.480776 fractal_server-1.3.1/fractal_server/common/tests/test_user.py
--rw-r--r--   0        0        0     2596 2023-06-26 06:59:30.480776 fractal_server-1.3.1/fractal_server/common/tests/test_workflow.py
--rw-r--r--   0        0        0    12432 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/config.py
--rw-r--r--   0        0        0     4562 2023-06-27 14:30:25.873556 fractal_server-1.3.1/fractal_server/logger.py
--rw-r--r--   0        0        0     5935 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/main.py
--rw-r--r--   0        0        0       59 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/migrations/README
--rw-r--r--   0        0        0     2330 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/migrations/env.py
--rw-r--r--   0        0        0      550 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/migrations/script.py.mako
--rw-r--r--   0        0        0      954 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/migrations/versions/4c308bcaea2b_add_task_args_schema_and_task_args_.py
--rw-r--r--   0        0        0     8770 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/migrations/versions/50a13d6138fd_initial_schema.py
--rw-r--r--   0        0        0      746 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/migrations/versions/f384e1c0cf5d_drop_task_default_args_columns.py
--rw-r--r--   0        0        0        0 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/py.typed
--rw-r--r--   0        0        0     2786 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/syringe.py
--rw-r--r--   0        0        0       72 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/tasks/__init__.py
--rw-r--r--   0        0        0    17581 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/tasks/collection.py
--rw-r--r--   0        0        0     2115 2023-06-23 06:18:06.502771 fractal_server-1.3.1/fractal_server/utils.py
--rw-r--r--   0        0        0     2700 2023-06-27 14:52:47.431576 fractal_server-1.3.1/pyproject.toml
--rw-r--r--   0        0        0     3544 1970-01-01 00:00:00.000000 fractal_server-1.3.1/PKG-INFO
+-rw-r--r--   0        0        0     1576 2023-06-23 06:18:06.498772 fractal_server-1.3.2a0/LICENSE
+-rw-r--r--   0        0        0     2100 2023-06-23 06:18:06.498772 fractal_server-1.3.2a0/README.md
+-rw-r--r--   0        0        0       69 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/.gitignore
+-rw-r--r--   0        0        0       24 2023-06-28 13:06:20.475252 fractal_server-1.3.2a0/fractal_server/__init__.py
+-rw-r--r--   0        0        0     2202 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/__main__.py
+-rw-r--r--   0        0        0     3153 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/alembic.ini
+-rw-r--r--   0        0        0        0 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/app/__init__.py
+-rw-r--r--   0        0        0     1242 2023-06-27 14:23:44.473555 fractal_server-1.3.2a0/fractal_server/app/api/__init__.py
+-rw-r--r--   0        0        0       24 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/app/api/v1/__init__.py
+-rw-r--r--   0        0        0     7622 2023-06-27 14:28:32.735643 fractal_server-1.3.2a0/fractal_server/app/api/v1/_aux_functions.py
+-rw-r--r--   0        0        0     7624 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/app/api/v1/dataset.py
+-rw-r--r--   0        0        0     4990 2023-06-27 14:51:02.824508 fractal_server-1.3.2a0/fractal_server/app/api/v1/job.py
+-rw-r--r--   0        0        0     8880 2023-06-27 14:30:25.873556 fractal_server-1.3.2a0/fractal_server/app/api/v1/project.py
+-rw-r--r--   0        0        0     5516 2023-06-27 14:23:44.473555 fractal_server-1.3.2a0/fractal_server/app/api/v1/task.py
+-rw-r--r--   0        0        0    10831 2023-06-27 14:23:44.473555 fractal_server-1.3.2a0/fractal_server/app/api/v1/task_collection.py
+-rw-r--r--   0        0        0     9246 2023-06-27 14:23:44.473555 fractal_server-1.3.2a0/fractal_server/app/api/v1/workflow.py
+-rw-r--r--   0        0        0     5165 2023-06-27 14:23:44.473555 fractal_server-1.3.2a0/fractal_server/app/api/v1/workflowtask.py
+-rw-r--r--   0        0        0     3081 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/app/db/__init__.py
+-rw-r--r--   0        0        0      372 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/app/models/__init__.py
+-rw-r--r--   0        0        0     3412 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/app/models/job.py
+-rw-r--r--   0        0        0      309 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/app/models/linkuserproject.py
+-rw-r--r--   0        0        0     2355 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/app/models/project.py
+-rw-r--r--   0        0        0     2563 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/app/models/security.py
+-rw-r--r--   0        0        0     1119 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/app/models/state.py
+-rw-r--r--   0        0        0     2535 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/app/models/task.py
+-rw-r--r--   0        0        0     5205 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/app/models/workflow.py
+-rw-r--r--   0        0        0       16 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/app/runner/.gitignore
+-rw-r--r--   0        0        0    10102 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/app/runner/__init__.py
+-rw-r--r--   0        0        0    19523 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/app/runner/_common.py
+-rw-r--r--   0        0        0     5464 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/app/runner/_local/__init__.py
+-rw-r--r--   0        0        0     3245 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/app/runner/_local/_local_config.py
+-rw-r--r--   0        0        0     1631 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/app/runner/_local/_submit_setup.py
+-rw-r--r--   0        0        0     3620 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/app/runner/_local/executor.py
+-rw-r--r--   0        0        0       16 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/app/runner/_slurm/.gitignore
+-rw-r--r--   0        0        0     3839 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/app/runner/_slurm/__init__.py
+-rw-r--r--   0        0        0     8840 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/app/runner/_slurm/_batching.py
+-rw-r--r--   0        0        0     4331 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/app/runner/_slurm/_executor_wait_thread.py
+-rw-r--r--   0        0        0    19766 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/app/runner/_slurm/_slurm_config.py
+-rw-r--r--   0        0        0     2942 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/app/runner/_slurm/_submit_setup.py
+-rw-r--r--   0        0        0     4534 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/app/runner/_slurm/_subprocess_run_as_user.py
+-rw-r--r--   0        0        0    42304 2023-06-28 13:05:15.436431 fractal_server-1.3.2a0/fractal_server/app/runner/_slurm/executor.py
+-rw-r--r--   0        0        0     5852 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/app/runner/_slurm/remote.py
+-rw-r--r--   0        0        0     7900 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/app/runner/common.py
+-rw-r--r--   0        0        0    11324 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/app/security/__init__.py
+-rw-r--r--   0        0        0       49 2023-06-26 06:59:30.472776 fractal_server-1.3.2a0/fractal_server/common/.git
+-rw-r--r--   0        0        0      717 2023-06-26 06:59:30.480776 fractal_server-1.3.2a0/fractal_server/common/.github/workflows/ci.yml
+-rw-r--r--   0        0        0      364 2023-06-26 06:59:30.480776 fractal_server-1.3.2a0/fractal_server/common/.github/workflows/project-management.yml
+-rw-r--r--   0        0        0       34 2023-06-26 06:59:30.480776 fractal_server-1.3.2a0/fractal_server/common/.gitignore
+-rw-r--r--   0        0        0      620 2023-06-26 06:59:30.480776 fractal_server-1.3.2a0/fractal_server/common/.pre-commit-config.yaml
+-rw-r--r--   0        0        0     1964 2023-06-26 06:59:30.480776 fractal_server-1.3.2a0/fractal_server/common/README.md
+-rw-r--r--   0        0        0        0 2023-06-26 06:59:30.480776 fractal_server-1.3.2a0/fractal_server/common/__init__.py
+-rw-r--r--   0        0        0      163 2023-06-26 06:59:32.128764 fractal_server-1.3.2a0/fractal_server/common/__pycache__/__init__.cpython-310.pyc
+-rw-r--r--   0        0        0       57 2023-06-26 06:59:30.480776 fractal_server-1.3.2a0/fractal_server/common/requirements.txt
+-rw-r--r--   0        0        0      614 2023-06-26 06:59:30.480776 fractal_server-1.3.2a0/fractal_server/common/schemas/__init__.py
+-rw-r--r--   0        0        0      425 2023-06-26 06:59:32.128764 fractal_server-1.3.2a0/fractal_server/common/schemas/__pycache__/__init__.cpython-310.pyc
+-rw-r--r--   0        0        0     1767 2023-06-26 06:59:32.128764 fractal_server-1.3.2a0/fractal_server/common/schemas/__pycache__/_validators.cpython-310.pyc
+-rw-r--r--   0        0        0     1624 2023-06-26 06:59:32.128764 fractal_server-1.3.2a0/fractal_server/common/schemas/__pycache__/applyworkflow.cpython-310.pyc
+-rw-r--r--   0        0        0     4082 2023-06-26 06:59:32.132763 fractal_server-1.3.2a0/fractal_server/common/schemas/__pycache__/manifest.cpython-310.pyc
+-rw-r--r--   0        0        0     3551 2023-06-26 06:59:32.132763 fractal_server-1.3.2a0/fractal_server/common/schemas/__pycache__/project.cpython-310.pyc
+-rw-r--r--   0        0        0     1179 2023-06-26 06:59:32.140764 fractal_server-1.3.2a0/fractal_server/common/schemas/__pycache__/state.cpython-310.pyc
+-rw-r--r--   0        0        0     2719 2023-06-26 06:59:32.140764 fractal_server-1.3.2a0/fractal_server/common/schemas/__pycache__/task.cpython-310.pyc
+-rw-r--r--   0        0        0     3306 2023-06-26 06:59:32.144764 fractal_server-1.3.2a0/fractal_server/common/schemas/__pycache__/task_collection.cpython-310.pyc
+-rw-r--r--   0        0        0     1216 2023-06-26 06:59:32.148764 fractal_server-1.3.2a0/fractal_server/common/schemas/__pycache__/user.cpython-310.pyc
+-rw-r--r--   0        0        0     3896 2023-06-26 06:59:32.152763 fractal_server-1.3.2a0/fractal_server/common/schemas/__pycache__/workflow.cpython-310.pyc
+-rw-r--r--   0        0        0     1616 2023-06-26 06:59:30.480776 fractal_server-1.3.2a0/fractal_server/common/schemas/_validators.py
+-rw-r--r--   0        0        0     1117 2023-06-26 06:59:30.480776 fractal_server-1.3.2a0/fractal_server/common/schemas/applyworkflow.py
+-rw-r--r--   0        0        0     3479 2023-06-26 06:59:30.480776 fractal_server-1.3.2a0/fractal_server/common/schemas/manifest.py
+-rw-r--r--   0        0        0     2483 2023-06-26 06:59:30.480776 fractal_server-1.3.2a0/fractal_server/common/schemas/project.py
+-rw-r--r--   0        0        0      673 2023-06-26 06:59:30.480776 fractal_server-1.3.2a0/fractal_server/common/schemas/state.py
+-rw-r--r--   0        0        0     2578 2023-06-26 06:59:30.480776 fractal_server-1.3.2a0/fractal_server/common/schemas/task.py
+-rw-r--r--   0        0        0     2935 2023-06-26 06:59:30.480776 fractal_server-1.3.2a0/fractal_server/common/schemas/task_collection.py
+-rw-r--r--   0        0        0     1216 2023-06-26 06:59:30.480776 fractal_server-1.3.2a0/fractal_server/common/schemas/user.py
+-rw-r--r--   0        0        0     2457 2023-06-26 06:59:30.480776 fractal_server-1.3.2a0/fractal_server/common/schemas/workflow.py
+-rw-r--r--   0        0        0      139 2023-06-26 06:59:30.480776 fractal_server-1.3.2a0/fractal_server/common/tests/conftest.py
+-rw-r--r--   0        0        0      298 2023-06-26 06:59:30.480776 fractal_server-1.3.2a0/fractal_server/common/tests/test_applyworkflow.py
+-rw-r--r--   0        0        0     2144 2023-06-26 06:59:30.480776 fractal_server-1.3.2a0/fractal_server/common/tests/test_dataset.py
+-rw-r--r--   0        0        0     1420 2023-06-26 06:59:30.480776 fractal_server-1.3.2a0/fractal_server/common/tests/test_manifest.py
+-rw-r--r--   0        0        0      525 2023-06-26 06:59:30.480776 fractal_server-1.3.2a0/fractal_server/common/tests/test_project.py
+-rw-r--r--   0        0        0      551 2023-06-26 06:59:30.480776 fractal_server-1.3.2a0/fractal_server/common/tests/test_state.py
+-rw-r--r--   0        0        0     1190 2023-06-26 06:59:30.480776 fractal_server-1.3.2a0/fractal_server/common/tests/test_task.py
+-rw-r--r--   0        0        0      968 2023-06-26 06:59:30.480776 fractal_server-1.3.2a0/fractal_server/common/tests/test_task_collection.py
+-rw-r--r--   0        0        0     1499 2023-06-26 06:59:30.480776 fractal_server-1.3.2a0/fractal_server/common/tests/test_user.py
+-rw-r--r--   0        0        0     2596 2023-06-26 06:59:30.480776 fractal_server-1.3.2a0/fractal_server/common/tests/test_workflow.py
+-rw-r--r--   0        0        0    12432 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/config.py
+-rw-r--r--   0        0        0     4562 2023-06-27 14:30:25.873556 fractal_server-1.3.2a0/fractal_server/logger.py
+-rw-r--r--   0        0        0     5935 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/main.py
+-rw-r--r--   0        0        0       59 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/migrations/README
+-rw-r--r--   0        0        0     2330 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/migrations/env.py
+-rw-r--r--   0        0        0      550 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/migrations/script.py.mako
+-rw-r--r--   0        0        0      954 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/migrations/versions/4c308bcaea2b_add_task_args_schema_and_task_args_.py
+-rw-r--r--   0        0        0     8770 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/migrations/versions/50a13d6138fd_initial_schema.py
+-rw-r--r--   0        0        0      746 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/migrations/versions/f384e1c0cf5d_drop_task_default_args_columns.py
+-rw-r--r--   0        0        0        0 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/py.typed
+-rw-r--r--   0        0        0     2786 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/syringe.py
+-rw-r--r--   0        0        0       72 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/tasks/__init__.py
+-rw-r--r--   0        0        0    17583 2023-06-28 12:43:53.050307 fractal_server-1.3.2a0/fractal_server/tasks/collection.py
+-rw-r--r--   0        0        0     2115 2023-06-23 06:18:06.502771 fractal_server-1.3.2a0/fractal_server/utils.py
+-rw-r--r--   0        0        0     2704 2023-06-28 13:06:20.475252 fractal_server-1.3.2a0/pyproject.toml
+-rw-r--r--   0        0        0     3546 1970-01-01 00:00:00.000000 fractal_server-1.3.2a0/PKG-INFO
```

### Comparing `fractal_server-1.3.1/LICENSE` & `fractal_server-1.3.2a0/LICENSE`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/README.md` & `fractal_server-1.3.2a0/README.md`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/__main__.py` & `fractal_server-1.3.2a0/fractal_server/__main__.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/alembic.ini` & `fractal_server-1.3.2a0/fractal_server/alembic.ini`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/app/api/__init__.py` & `fractal_server-1.3.2a0/fractal_server/app/api/__init__.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/app/api/v1/_aux_functions.py` & `fractal_server-1.3.2a0/fractal_server/app/api/v1/_aux_functions.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/app/api/v1/dataset.py` & `fractal_server-1.3.2a0/fractal_server/app/api/v1/dataset.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/app/api/v1/job.py` & `fractal_server-1.3.2a0/fractal_server/app/api/v1/job.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/app/api/v1/project.py` & `fractal_server-1.3.2a0/fractal_server/app/api/v1/project.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/app/api/v1/task.py` & `fractal_server-1.3.2a0/fractal_server/app/api/v1/task.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/app/api/v1/task_collection.py` & `fractal_server-1.3.2a0/fractal_server/app/api/v1/task_collection.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/app/api/v1/workflow.py` & `fractal_server-1.3.2a0/fractal_server/app/api/v1/workflow.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/app/api/v1/workflowtask.py` & `fractal_server-1.3.2a0/fractal_server/app/api/v1/workflowtask.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/app/db/__init__.py` & `fractal_server-1.3.2a0/fractal_server/app/db/__init__.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/app/models/job.py` & `fractal_server-1.3.2a0/fractal_server/app/models/job.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/app/models/project.py` & `fractal_server-1.3.2a0/fractal_server/app/models/project.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/app/models/security.py` & `fractal_server-1.3.2a0/fractal_server/app/models/security.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/app/models/state.py` & `fractal_server-1.3.2a0/fractal_server/app/models/state.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/app/models/task.py` & `fractal_server-1.3.2a0/fractal_server/app/models/task.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/app/models/workflow.py` & `fractal_server-1.3.2a0/fractal_server/app/models/workflow.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/app/runner/__init__.py` & `fractal_server-1.3.2a0/fractal_server/app/runner/__init__.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/app/runner/_common.py` & `fractal_server-1.3.2a0/fractal_server/app/runner/_common.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/app/runner/_local/__init__.py` & `fractal_server-1.3.2a0/fractal_server/app/runner/_local/__init__.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/app/runner/_local/_local_config.py` & `fractal_server-1.3.2a0/fractal_server/app/runner/_local/_local_config.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/app/runner/_local/_submit_setup.py` & `fractal_server-1.3.2a0/fractal_server/app/runner/_local/_submit_setup.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/app/runner/_local/executor.py` & `fractal_server-1.3.2a0/fractal_server/app/runner/_local/executor.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/app/runner/_slurm/__init__.py` & `fractal_server-1.3.2a0/fractal_server/app/runner/_slurm/__init__.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/app/runner/_slurm/_batching.py` & `fractal_server-1.3.2a0/fractal_server/app/runner/_slurm/_batching.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/app/runner/_slurm/_executor_wait_thread.py` & `fractal_server-1.3.2a0/fractal_server/app/runner/_slurm/_executor_wait_thread.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/app/runner/_slurm/_slurm_config.py` & `fractal_server-1.3.2a0/fractal_server/app/runner/_slurm/_slurm_config.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/app/runner/_slurm/_submit_setup.py` & `fractal_server-1.3.2a0/fractal_server/app/runner/_slurm/_submit_setup.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/app/runner/_slurm/_subprocess_run_as_user.py` & `fractal_server-1.3.2a0/fractal_server/app/runner/_slurm/_subprocess_run_as_user.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/app/runner/_slurm/executor.py` & `fractal_server-1.3.2a0/fractal_server/app/runner/_slurm/executor.py`

 * *Files 0% similar despite different names*

```diff
@@ -28,14 +28,15 @@
 from cfut import SlurmExecutor
 from cfut.util import random_string
 
 from ....config import get_settings
 from ....logger import set_logger
 from ....syringe import Inject
 from .._common import get_task_file_paths
+from .._common import SHUTDOWN_FILENAME
 from .._common import TaskFiles
 from ..common import JobExecutionError
 from ..common import TaskExecutionError
 from ._batching import heuristics
 from ._executor_wait_thread import FractalSlurmWaitThread
 from ._slurm_config import get_default_slurm_config
 from ._slurm_config import SlurmConfig
@@ -220,15 +221,17 @@
         # cfut.SlurmWaitThread)
         if not slurm_poll_interval:
             settings = Inject(get_settings)
             slurm_poll_interval = settings.FRACTAL_SLURM_POLL_INTERVAL
         self.wait_thread.slurm_poll_interval = slurm_poll_interval
         self.wait_thread.slurm_user = self.slurm_user
 
-        self.wait_thread.shutdown_file = shutdown_file
+        self.wait_thread.shutdown_file = shutdown_file or (
+            self.working_dir / SHUTDOWN_FILENAME
+        )
         self.wait_thread.shutdown_callback = self.shutdown
 
     def _cleanup(self, jobid: str) -> None:
         """
         Given a job ID as returned by _start, perform any necessary
         cleanup after the job has finished.
         """
```

### Comparing `fractal_server-1.3.1/fractal_server/app/runner/_slurm/remote.py` & `fractal_server-1.3.2a0/fractal_server/app/runner/_slurm/remote.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/app/runner/common.py` & `fractal_server-1.3.2a0/fractal_server/app/runner/common.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/app/security/__init__.py` & `fractal_server-1.3.2a0/fractal_server/app/security/__init__.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/common/.github/workflows/ci.yml` & `fractal_server-1.3.2a0/fractal_server/common/.github/workflows/ci.yml`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/common/.pre-commit-config.yaml` & `fractal_server-1.3.2a0/fractal_server/common/.pre-commit-config.yaml`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/common/README.md` & `fractal_server-1.3.2a0/fractal_server/common/README.md`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/common/schemas/__init__.py` & `fractal_server-1.3.2a0/fractal_server/common/schemas/__init__.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/common/schemas/__pycache__/_validators.cpython-310.pyc` & `fractal_server-1.3.2a0/fractal_server/common/schemas/__pycache__/_validators.cpython-310.pyc`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/common/schemas/__pycache__/applyworkflow.cpython-310.pyc` & `fractal_server-1.3.2a0/fractal_server/common/schemas/__pycache__/applyworkflow.cpython-310.pyc`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/common/schemas/__pycache__/manifest.cpython-310.pyc` & `fractal_server-1.3.2a0/fractal_server/common/schemas/__pycache__/manifest.cpython-310.pyc`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/common/schemas/__pycache__/project.cpython-310.pyc` & `fractal_server-1.3.2a0/fractal_server/common/schemas/__pycache__/project.cpython-310.pyc`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/common/schemas/__pycache__/state.cpython-310.pyc` & `fractal_server-1.3.2a0/fractal_server/common/schemas/__pycache__/state.cpython-310.pyc`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/common/schemas/__pycache__/task.cpython-310.pyc` & `fractal_server-1.3.2a0/fractal_server/common/schemas/__pycache__/task.cpython-310.pyc`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/common/schemas/__pycache__/task_collection.cpython-310.pyc` & `fractal_server-1.3.2a0/fractal_server/common/schemas/__pycache__/task_collection.cpython-310.pyc`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/common/schemas/__pycache__/user.cpython-310.pyc` & `fractal_server-1.3.2a0/fractal_server/common/schemas/__pycache__/user.cpython-310.pyc`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/common/schemas/__pycache__/workflow.cpython-310.pyc` & `fractal_server-1.3.2a0/fractal_server/common/schemas/__pycache__/workflow.cpython-310.pyc`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/common/schemas/_validators.py` & `fractal_server-1.3.2a0/fractal_server/common/schemas/_validators.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/common/schemas/applyworkflow.py` & `fractal_server-1.3.2a0/fractal_server/common/schemas/applyworkflow.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/common/schemas/manifest.py` & `fractal_server-1.3.2a0/fractal_server/common/schemas/manifest.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/common/schemas/project.py` & `fractal_server-1.3.2a0/fractal_server/common/schemas/project.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/common/schemas/state.py` & `fractal_server-1.3.2a0/fractal_server/common/schemas/state.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/common/schemas/task.py` & `fractal_server-1.3.2a0/fractal_server/common/schemas/task.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/common/schemas/task_collection.py` & `fractal_server-1.3.2a0/fractal_server/common/schemas/task_collection.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/common/schemas/user.py` & `fractal_server-1.3.2a0/fractal_server/common/schemas/user.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/common/schemas/workflow.py` & `fractal_server-1.3.2a0/fractal_server/common/schemas/workflow.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/common/tests/test_dataset.py` & `fractal_server-1.3.2a0/fractal_server/common/tests/test_dataset.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/common/tests/test_manifest.py` & `fractal_server-1.3.2a0/fractal_server/common/tests/test_manifest.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/common/tests/test_project.py` & `fractal_server-1.3.2a0/fractal_server/common/tests/test_project.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/common/tests/test_state.py` & `fractal_server-1.3.2a0/fractal_server/common/tests/test_state.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/common/tests/test_task.py` & `fractal_server-1.3.2a0/fractal_server/common/tests/test_task.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/common/tests/test_task_collection.py` & `fractal_server-1.3.2a0/fractal_server/common/tests/test_task_collection.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/common/tests/test_user.py` & `fractal_server-1.3.2a0/fractal_server/common/tests/test_user.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/common/tests/test_workflow.py` & `fractal_server-1.3.2a0/fractal_server/common/tests/test_workflow.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/config.py` & `fractal_server-1.3.2a0/fractal_server/config.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/logger.py` & `fractal_server-1.3.2a0/fractal_server/logger.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/main.py` & `fractal_server-1.3.2a0/fractal_server/main.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/migrations/env.py` & `fractal_server-1.3.2a0/fractal_server/migrations/env.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/migrations/script.py.mako` & `fractal_server-1.3.2a0/fractal_server/migrations/script.py.mako`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/migrations/versions/4c308bcaea2b_add_task_args_schema_and_task_args_.py` & `fractal_server-1.3.2a0/fractal_server/migrations/versions/4c308bcaea2b_add_task_args_schema_and_task_args_.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/migrations/versions/50a13d6138fd_initial_schema.py` & `fractal_server-1.3.2a0/fractal_server/migrations/versions/50a13d6138fd_initial_schema.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/migrations/versions/f384e1c0cf5d_drop_task_default_args_columns.py` & `fractal_server-1.3.2a0/fractal_server/migrations/versions/f384e1c0cf5d_drop_task_default_args_columns.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/syringe.py` & `fractal_server-1.3.2a0/fractal_server/syringe.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/fractal_server/tasks/collection.py` & `fractal_server-1.3.2a0/fractal_server/tasks/collection.py`

 * *Files 1% similar despite different names*

```diff
@@ -509,30 +509,30 @@
             current_version = next(
                 line.split()[-1]
                 for line in stdout_inspect.split("\n")
                 if line.startswith("Version:")
             )
             if current_version != pinned_pkg_version:
                 logger.debug(
-                    f"Currently installed version of {pinned_pkg_name}"
+                    f"Currently installed version of {pinned_pkg_name} "
                     f"({current_version}) differs from pinned version "
                     f"({pinned_pkg_version}); "
                     f"install version {pinned_pkg_version}."
                 )
                 await execute_command(
                     cwd=venv_path,
                     command=(
                         f"{pip} install "
                         f"{pinned_pkg_name}=={pinned_pkg_version}"
                     ),
                     logger_name=logger_name,
                 )
             else:
                 logger.debug(
-                    f"Currently installed version of {pinned_pkg_name}"
+                    f"Currently installed version of {pinned_pkg_name} "
                     f"({current_version}) already matches the pinned version."
                 )
 
     # Extract package installation path from `pip show`
     stdout_inspect = await execute_command(
         cwd=venv_path, command=cmd_inspect, logger_name=logger_name
     )
```

### Comparing `fractal_server-1.3.1/fractal_server/utils.py` & `fractal_server-1.3.2a0/fractal_server/utils.py`

 * *Files identical despite different names*

### Comparing `fractal_server-1.3.1/pyproject.toml` & `fractal_server-1.3.2a0/pyproject.toml`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "fractal-server"
-version = "1.3.1"
+version = "1.3.2a0"
 description = "Server component of the Fractal analytics platform"
 authors = [
     "Jacopo Nespolo <jacopo.nespolo@exact-lab.it>",
     "Marco Franzon <marco.franzon@exact-lab.it>",
     "Tommaso Comparin <tommaso.comparin@exact-lab.it>",
 ]
 readme = "README.md"
@@ -73,15 +73,15 @@
 asyncio_mode = "auto"
 filterwarnings = [
     "error::RuntimeWarning",
     "error::pytest.PytestUnraisableExceptionWarning",
 ]
 
 [tool.bumpver]
-current_version = "1.3.1"
+current_version = "1.3.2a0"
 version_pattern = "MAJOR.MINOR.PATCH[PYTAGNUM]"
 commit_message = "bump version {old_version} -> {new_version}"
 commit = true
 tag = true
 push = true
 
 [tool.bumpver.file_patterns]
```

### Comparing `fractal_server-1.3.1/PKG-INFO` & `fractal_server-1.3.2a0/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: fractal-server
-Version: 1.3.1
+Version: 1.3.2a0
 Summary: Server component of the Fractal analytics platform
 Home-page: https://github.com/fractal-analytics-platform/fractal-server
 License: BSD-3-Clause
 Author: Jacopo Nespolo
 Author-email: jacopo.nespolo@exact-lab.it
 Requires-Python: >=3.9,<4.0
 Classifier: License :: OSI Approved :: BSD License
```


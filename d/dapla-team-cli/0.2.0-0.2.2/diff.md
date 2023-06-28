# Comparing `tmp/dapla_team_cli-0.2.0.tar.gz` & `tmp/dapla_team_cli-0.2.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dapla_team_cli-0.2.0.tar", max compression
+gzip compressed data, was "dapla_team_cli-0.2.2.tar", max compression
```

## Comparing `dapla_team_cli-0.2.0.tar` & `dapla_team_cli-0.2.2.tar`

### file list

```diff
@@ -1,89 +1,97 @@
--rw-r--r--   0        0        0     1099 2023-05-22 12:39:51.129940 dapla_team_cli-0.2.0/LICENSE
--rw-r--r--   0        0        0     2915 2023-05-22 12:39:51.129940 dapla_team_cli-0.2.0/README.md
--rw-r--r--   0        0        0     3015 2023-05-22 12:40:08.098262 dapla_team_cli-0.2.0/pyproject.toml
--rw-r--r--   0        0        0      433 2023-05-22 12:39:51.141940 dapla_team_cli-0.2.0/src/dapla_team_cli/__init__.py
--rw-r--r--   0        0        0     2629 2023-05-22 12:39:51.141940 dapla_team_cli-0.2.0/src/dapla_team_cli/__main__.py
--rw-r--r--   0        0        0       50 2023-05-22 12:39:51.141940 dapla_team_cli-0.2.0/src/dapla_team_cli/api/__init__.py
--rw-r--r--   0        0        0       43 2023-05-22 12:39:51.141940 dapla_team_cli-0.2.0/src/dapla_team_cli/api/models/__init__.py
--rw-r--r--   0        0        0     1111 2023-05-22 12:39:51.141940 dapla_team_cli-0.2.0/src/dapla_team_cli/api/models/group.py
--rw-r--r--   0        0        0      157 2023-05-22 12:39:51.141940 dapla_team_cli-0.2.0/src/dapla_team_cli/api/models/link.py
--rw-r--r--   0        0        0     1417 2023-05-22 12:39:51.141940 dapla_team_cli-0.2.0/src/dapla_team_cli/api/models/team.py
--rw-r--r--   0        0        0      873 2023-05-22 12:39:51.141940 dapla_team_cli-0.2.0/src/dapla_team_cli/api/models/user.py
--rw-r--r--   0        0        0     1351 2023-05-22 12:39:51.141940 dapla_team_cli-0.2.0/src/dapla_team_cli/api/utils.py
--rw-r--r--   0        0        0       27 2023-05-22 12:39:51.141940 dapla_team_cli-0.2.0/src/dapla_team_cli/auth/__init__.py
--rw-r--r--   0        0        0     2263 2023-05-22 12:39:51.141940 dapla_team_cli-0.2.0/src/dapla_team_cli/auth/cmd.py
--rw-r--r--   0        0        0       47 2023-05-22 12:39:51.141940 dapla_team_cli-0.2.0/src/dapla_team_cli/auth/services/__init__.py
--rw-r--r--   0        0        0      407 2023-05-22 12:39:51.141940 dapla_team_cli-0.2.0/src/dapla_team_cli/auth/services/expiry.py
--rw-r--r--   0        0        0     2284 2023-05-22 12:39:51.141940 dapla_team_cli-0.2.0/src/dapla_team_cli/auth/services/get_token.py
--rw-r--r--   0        0        0     1299 2023-05-22 12:39:51.141940 dapla_team_cli-0.2.0/src/dapla_team_cli/auth/services/set_token.py
--rw-r--r--   0        0        0     1496 2023-05-22 12:39:51.141940 dapla_team_cli-0.2.0/src/dapla_team_cli/config.py
--rw-r--r--   0        0        0       44 2023-05-22 12:39:51.141940 dapla_team_cli-0.2.0/src/dapla_team_cli/doctor/__init__.py
--rw-r--r--   0        0        0      708 2023-05-22 12:39:51.141940 dapla_team_cli-0.2.0/src/dapla_team_cli/doctor/check.py
--rw-r--r--   0        0        0     1398 2023-05-22 12:39:51.141940 dapla_team_cli-0.2.0/src/dapla_team_cli/doctor/cmd.py
--rw-r--r--   0        0        0     3483 2023-05-22 12:39:51.141940 dapla_team_cli-0.2.0/src/dapla_team_cli/doctor/gcloud.py
--rw-r--r--   0        0        0     1296 2023-05-22 12:39:51.141940 dapla_team_cli-0.2.0/src/dapla_team_cli/doctor/keycloak.py
--rw-r--r--   0        0        0     2060 2023-05-22 12:39:51.141940 dapla_team_cli-0.2.0/src/dapla_team_cli/gcp/__init__.py
--rw-r--r--   0        0        0   230022 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/gcp/project_roles.json
--rw-r--r--   0        0        0     4296 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/github.py
--rw-r--r--   0        0        0       35 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/groups/__init__.py
--rw-r--r--   0        0        0      357 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/groups/cmd.py
--rw-r--r--   0        0        0       35 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/groups/list_members/__init__.py
--rw-r--r--   0        0        0     2891 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/groups/list_members/cmd.py
--rw-r--r--   0        0        0       49 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/groups/services/__init__.py
--rw-r--r--   0        0        0       37 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/__init__.py
--rw-r--r--   0        0        0       33 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/approve/__init__.py
--rw-r--r--   0        0        0     1657 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/approve/approve.py
--rw-r--r--   0        0        0      359 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/approve/cmd.py
--rw-r--r--   0        0        0       36 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/atlantis_apply/__init__.py
--rw-r--r--   0        0        0     2795 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/atlantis_apply/atlantis_apply_all.py
--rw-r--r--   0        0        0      833 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/atlantis_apply/cmd.py
--rw-r--r--   0        0        0       35 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/atlantis_plan/__init__.py
--rw-r--r--   0        0        0     1431 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/atlantis_plan/atlantis_plan_all.py
--rw-r--r--   0        0        0      490 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/atlantis_plan/cmd.py
--rw-r--r--   0        0        0      675 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/batch_handler.py
--rw-r--r--   0        0        0     1191 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/cmd.py
--rw-r--r--   0        0        0     1809 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/const.py
--rw-r--r--   0        0        0       29 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/janitor/__init__.py
--rw-r--r--   0        0        0     2030 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/janitor/close_all.py
--rw-r--r--   0        0        0      694 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/janitor/cmd.py
--rw-r--r--   0        0        0       31 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/merge/__init__.py
--rw-r--r--   0        0        0      673 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/merge/cmd.py
--rw-r--r--   0        0        0     2592 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/merge/merge_all.py
--rw-r--r--   0        0        0       34 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/open/__init__.py
--rw-r--r--   0        0        0     2591 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/open/cmd.py
--rw-r--r--   0        0        0     3917 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/open/open_prs.py
--rw-r--r--   0        0        0       37 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/probe/__init__.py
--rw-r--r--   0        0        0      880 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/probe/cmd.py
--rw-r--r--   0        0        0     1851 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/probe/probe_atlantis_apply.py
--rw-r--r--   0        0        0     3659 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/probe/probe_workflows.py
--rw-r--r--   0        0        0      434 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/prompt_utils.py
--rw-r--r--   0        0        0       82 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/ready/__init__.py
--rw-r--r--   0        0        0      775 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/ready/cmd.py
--rw-r--r--   0        0        0     2332 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/ready/generate_state.py
--rw-r--r--   0        0        0     1225 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/rich_check.py
--rw-r--r--   0        0        0       54 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/state/__init__.py
--rw-r--r--   0        0        0      967 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/state/cmd.py
--rw-r--r--   0        0        0     3639 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/state/state_commands.py
--rw-r--r--   0        0        0     4426 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/state/state_utils.py
--rw-r--r--   0        0        0       35 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/validate/__init__.py
--rw-r--r--   0        0        0      135 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/pr/validate/cmd.py
--rw-r--r--   0        0        0       22 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/secrets/__init__.py
--rw-r--r--   0        0        0     2851 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/secrets/cmd.py
--rw-r--r--   0        0        0     2405 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/secrets/services.py
--rw-r--r--   0        0        0     3353 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/team.py
--rw-r--r--   0        0        0       37 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/tf/__init__.py
--rw-r--r--   0        0        0      345 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/tf/cmd.py
--rw-r--r--   0        0        0      414 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/tf/iam_bindings/__init__.py
--rw-r--r--   0        0        0     2962 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/tf/iam_bindings/auth_groups.py
--rw-r--r--   0        0        0     3727 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/tf/iam_bindings/buckets.py
--rw-r--r--   0        0        0    13631 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/tf/iam_bindings/cmd.py
--rw-r--r--   0        0        0     3174 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/tf/iam_bindings/configs.py
--rw-r--r--   0        0        0      434 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/tf/iam_bindings/environments.py
--rw-r--r--   0        0        0     3339 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/tf/iam_bindings/expiry.py
--rw-r--r--   0        0        0     1631 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/tf/iam_bindings/project_roles.py
--rw-r--r--   0        0        0     1021 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/tf/iam_bindings/templates/buckets-iam.jinja
--rw-r--r--   0        0        0      112 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/tf/iam_bindings/templates/iam-bindings-git-commit-msg.jinja
--rw-r--r--   0        0        0      977 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/tf/iam_bindings/templates/projects-iam.jinja
--rw-r--r--   0        0        0     6232 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/tf/iam_bindings/terraform.py
--rw-r--r--   0        0        0     1994 2023-05-22 12:39:51.145940 dapla_team_cli-0.2.0/src/dapla_team_cli/tf/iam_bindings/utilities.py
--rw-r--r--   0        0        0     4796 1970-01-01 00:00:00.000000 dapla_team_cli-0.2.0/PKG-INFO
+-rw-r--r--   0        0        0     1099 2023-06-28 12:14:50.822428 dapla_team_cli-0.2.2/LICENSE
+-rw-r--r--   0        0        0     2913 2023-06-28 12:14:50.822428 dapla_team_cli-0.2.2/README.md
+-rw-r--r--   0        0        0     3015 2023-06-28 12:15:05.402525 dapla_team_cli-0.2.2/pyproject.toml
+-rw-r--r--   0        0        0      433 2023-06-28 12:14:50.834428 dapla_team_cli-0.2.2/src/dapla_team_cli/__init__.py
+-rw-r--r--   0        0        0     2736 2023-06-28 12:15:05.402525 dapla_team_cli-0.2.2/src/dapla_team_cli/__main__.py
+-rw-r--r--   0        0        0       50 2023-06-28 12:14:50.834428 dapla_team_cli-0.2.2/src/dapla_team_cli/api/__init__.py
+-rw-r--r--   0        0        0      548 2023-06-28 12:14:50.834428 dapla_team_cli-0.2.2/src/dapla_team_cli/api/api_request.py
+-rw-r--r--   0        0        0       43 2023-06-28 12:14:50.834428 dapla_team_cli-0.2.2/src/dapla_team_cli/api/models/__init__.py
+-rw-r--r--   0        0        0     1215 2023-06-28 12:14:50.834428 dapla_team_cli-0.2.2/src/dapla_team_cli/api/models/group.py
+-rw-r--r--   0        0        0      157 2023-06-28 12:14:50.834428 dapla_team_cli-0.2.2/src/dapla_team_cli/api/models/link.py
+-rw-r--r--   0        0        0     1562 2023-06-28 12:14:50.834428 dapla_team_cli-0.2.2/src/dapla_team_cli/api/models/team.py
+-rw-r--r--   0        0        0      873 2023-06-28 12:14:50.834428 dapla_team_cli-0.2.2/src/dapla_team_cli/api/models/user.py
+-rw-r--r--   0        0        0     4361 2023-06-28 12:14:50.834428 dapla_team_cli-0.2.2/src/dapla_team_cli/api/utils.py
+-rw-r--r--   0        0        0       27 2023-06-28 12:14:50.834428 dapla_team_cli-0.2.2/src/dapla_team_cli/auth/__init__.py
+-rw-r--r--   0        0        0     2263 2023-06-28 12:14:50.834428 dapla_team_cli-0.2.2/src/dapla_team_cli/auth/cmd.py
+-rw-r--r--   0        0        0       47 2023-06-28 12:14:50.834428 dapla_team_cli-0.2.2/src/dapla_team_cli/auth/services/__init__.py
+-rw-r--r--   0        0        0      407 2023-06-28 12:14:50.834428 dapla_team_cli-0.2.2/src/dapla_team_cli/auth/services/expiry.py
+-rw-r--r--   0        0        0     2284 2023-06-28 12:14:50.834428 dapla_team_cli-0.2.2/src/dapla_team_cli/auth/services/get_token.py
+-rw-r--r--   0        0        0     1299 2023-06-28 12:14:50.834428 dapla_team_cli-0.2.2/src/dapla_team_cli/auth/services/set_token.py
+-rw-r--r--   0        0        0     1628 2023-06-28 12:15:05.402525 dapla_team_cli-0.2.2/src/dapla_team_cli/config.py
+-rw-r--r--   0        0        0       44 2023-06-28 12:14:50.834428 dapla_team_cli-0.2.2/src/dapla_team_cli/doctor/__init__.py
+-rw-r--r--   0        0        0      708 2023-06-28 12:14:50.834428 dapla_team_cli-0.2.2/src/dapla_team_cli/doctor/check.py
+-rw-r--r--   0        0        0     1398 2023-06-28 12:14:50.834428 dapla_team_cli-0.2.2/src/dapla_team_cli/doctor/cmd.py
+-rw-r--r--   0        0        0     3483 2023-06-28 12:14:50.834428 dapla_team_cli-0.2.2/src/dapla_team_cli/doctor/gcloud.py
+-rw-r--r--   0        0        0     1296 2023-06-28 12:14:50.834428 dapla_team_cli-0.2.2/src/dapla_team_cli/doctor/keycloak.py
+-rw-r--r--   0        0        0     2060 2023-06-28 12:14:50.834428 dapla_team_cli-0.2.2/src/dapla_team_cli/gcp/__init__.py
+-rw-r--r--   0        0        0   230022 2023-06-28 12:14:50.834428 dapla_team_cli-0.2.2/src/dapla_team_cli/gcp/project_roles.json
+-rw-r--r--   0        0        0     4296 2023-06-28 12:14:50.834428 dapla_team_cli-0.2.2/src/dapla_team_cli/github.py
+-rw-r--r--   0        0        0       35 2023-06-28 12:14:50.834428 dapla_team_cli-0.2.2/src/dapla_team_cli/groups/__init__.py
+-rw-r--r--   0        0        0     1653 2023-06-28 12:15:05.402525 dapla_team_cli-0.2.2/src/dapla_team_cli/groups/cmd.py
+-rw-r--r--   0        0        0     1222 2023-06-28 12:14:50.834428 dapla_team_cli-0.2.2/src/dapla_team_cli/groups/groups.py
+-rw-r--r--   0        0        0       50 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/groups/members/__init__.py
+-rw-r--r--   0        0        0     2409 2023-06-28 12:15:05.402525 dapla_team_cli-0.2.2/src/dapla_team_cli/groups/members/cmd.py
+-rw-r--r--   0        0        0     3244 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/groups/members/members.py
+-rw-r--r--   0        0        0       49 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/groups/services/__init__.py
+-rw-r--r--   0        0        0       37 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/__init__.py
+-rw-r--r--   0        0        0       33 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/approve/__init__.py
+-rw-r--r--   0        0        0     1657 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/approve/approve.py
+-rw-r--r--   0        0        0      359 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/approve/cmd.py
+-rw-r--r--   0        0        0       36 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/atlantis_apply/__init__.py
+-rw-r--r--   0        0        0     2795 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/atlantis_apply/atlantis_apply_all.py
+-rw-r--r--   0        0        0      833 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/atlantis_apply/cmd.py
+-rw-r--r--   0        0        0       35 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/atlantis_plan/__init__.py
+-rw-r--r--   0        0        0     1431 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/atlantis_plan/atlantis_plan_all.py
+-rw-r--r--   0        0        0      490 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/atlantis_plan/cmd.py
+-rw-r--r--   0        0        0      675 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/batch_handler.py
+-rw-r--r--   0        0        0     1191 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/cmd.py
+-rw-r--r--   0        0        0     1809 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/const.py
+-rw-r--r--   0        0        0       29 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/janitor/__init__.py
+-rw-r--r--   0        0        0     2030 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/janitor/close_all.py
+-rw-r--r--   0        0        0      694 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/janitor/cmd.py
+-rw-r--r--   0        0        0       31 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/merge/__init__.py
+-rw-r--r--   0        0        0      673 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/merge/cmd.py
+-rw-r--r--   0        0        0     2592 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/merge/merge_all.py
+-rw-r--r--   0        0        0       34 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/open/__init__.py
+-rw-r--r--   0        0        0     2591 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/open/cmd.py
+-rw-r--r--   0        0        0     3917 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/open/open_prs.py
+-rw-r--r--   0        0        0       37 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/probe/__init__.py
+-rw-r--r--   0        0        0      880 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/probe/cmd.py
+-rw-r--r--   0        0        0     1851 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/probe/probe_atlantis_apply.py
+-rw-r--r--   0        0        0     3659 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/probe/probe_workflows.py
+-rw-r--r--   0        0        0      434 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/prompt_utils.py
+-rw-r--r--   0        0        0       82 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/ready/__init__.py
+-rw-r--r--   0        0        0      775 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/ready/cmd.py
+-rw-r--r--   0        0        0     2332 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/ready/generate_state.py
+-rw-r--r--   0        0        0     1225 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/rich_check.py
+-rw-r--r--   0        0        0       54 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/state/__init__.py
+-rw-r--r--   0        0        0      967 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/state/cmd.py
+-rw-r--r--   0        0        0     3639 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/state/state_commands.py
+-rw-r--r--   0        0        0     4426 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/state/state_utils.py
+-rw-r--r--   0        0        0       35 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/validate/__init__.py
+-rw-r--r--   0        0        0      135 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/pr/validate/cmd.py
+-rw-r--r--   0        0        0      448 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/result_utils.py
+-rw-r--r--   0        0        0       22 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/secrets/__init__.py
+-rw-r--r--   0        0        0     2851 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/secrets/cmd.py
+-rw-r--r--   0        0        0     2405 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/secrets/services.py
+-rw-r--r--   0        0        0     3458 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/team.py
+-rw-r--r--   0        0        0       37 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/tf/__init__.py
+-rw-r--r--   0        0        0      345 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/tf/cmd.py
+-rw-r--r--   0        0        0      414 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/tf/iam_bindings/__init__.py
+-rw-r--r--   0        0        0     3004 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/tf/iam_bindings/auth_groups.py
+-rw-r--r--   0        0        0     3727 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/tf/iam_bindings/buckets.py
+-rw-r--r--   0        0        0    13631 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/tf/iam_bindings/cmd.py
+-rw-r--r--   0        0        0     3174 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/tf/iam_bindings/configs.py
+-rw-r--r--   0        0        0      434 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/tf/iam_bindings/environments.py
+-rw-r--r--   0        0        0     3339 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/tf/iam_bindings/expiry.py
+-rw-r--r--   0        0        0     1631 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/tf/iam_bindings/project_roles.py
+-rw-r--r--   0        0        0     1021 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/tf/iam_bindings/templates/buckets-iam.jinja
+-rw-r--r--   0        0        0      112 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/tf/iam_bindings/templates/iam-bindings-git-commit-msg.jinja
+-rw-r--r--   0        0        0      977 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/tf/iam_bindings/templates/projects-iam.jinja
+-rw-r--r--   0        0        0     6232 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/tf/iam_bindings/terraform.py
+-rw-r--r--   0        0        0     1994 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/tf/iam_bindings/utilities.py
+-rw-r--r--   0        0        0       35 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/transfer_service/__init__.py
+-rw-r--r--   0        0        0      991 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/transfer_service/cmd.py
+-rw-r--r--   0        0        0      917 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/transfer_service/transfer_service.py
+-rw-r--r--   0        0        0     1968 2023-06-28 12:14:50.838428 dapla_team_cli-0.2.2/src/dapla_team_cli/user.py
+-rw-r--r--   0        0        0     4794 1970-01-01 00:00:00.000000 dapla_team_cli-0.2.2/PKG-INFO
```

### Comparing `dapla_team_cli-0.2.0/LICENSE` & `dapla_team_cli-0.2.2/LICENSE`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/README.md` & `dapla_team_cli-0.2.2/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -73,8 +73,8 @@
 [file an issue]: https://github.com/statisticsnorway/dapla-team-cli/issues
 [pipx]: https://pypa.github.io/pipx
 
 <!-- github-only -->
 
 [license]: https://github.com/statisticsnorway/dapla-team-cli/blob/main/LICENSE
 [contributor guide]: https://github.com/statisticsnorway/dapla-team-cli/blob/main/CONTRIBUTING.md
-[command-line reference]: https://statisticsnorway.github.io/dapla-team-cli/command_reference.md
+[command-line reference]: https://statisticsnorway.github.io/dapla-team-cli/command_reference/
```

### Comparing `dapla_team_cli-0.2.0/pyproject.toml` & `dapla_team_cli-0.2.2/pyproject.toml`

 * *Files 5% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "dapla-team-cli"
-version = "0.2.0"
+version = "0.2.2"
 description = "CLI for working with Dapla Teams"
 authors = ["Kenneth Leine Schulstad <kls@rdck.no>"]
 license = "MIT"
 readme = "README.md"
 homepage = "https://github.com/statisticsnorway/dapla-team-cli"
 repository = "https://github.com/statisticsnorway/dapla-team-cli"
 documentation = "https://statisticsnorway.github.io/dapla-team-cli"
```

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/__main__.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -10,27 +10,28 @@
     ´iam-bindings´ is the actual command
 
 Command groups must be mounted here to become available.
 
 Each sub-command's modules should be grouped into a separate python package.
 """
 import logging
-import os
 from enum import Enum
 from importlib.metadata import version
 from typing import Optional
 
 import typer
 
 import dapla_team_cli.auth.cmd as auth
 import dapla_team_cli.doctor.cmd as doctor
 import dapla_team_cli.groups.cmd as groups
 import dapla_team_cli.pr.cmd as pr
 import dapla_team_cli.secrets.cmd as secrets
 import dapla_team_cli.tf.cmd as tf
+import dapla_team_cli.transfer_service.cmd as ts
+from dapla_team_cli.config import in_ipython_session
 
 
 app = typer.Typer(no_args_is_help=True, pretty_exceptions_show_locals=False)
 logging.basicConfig()
 
 __version__ = version("dapla_team_cli")
 
@@ -81,19 +82,19 @@
 
 def main() -> None:
     """Main function of dpteam."""
     app()
 
 
 app.add_typer(tf.app)
-app.add_typer(groups.app)
 app.add_typer(secrets.app)
 app.add_typer(auth.app)
+app.add_typer(groups.app)
 
-if os.getenv("NB_USER") != "jovyan":  # Batch update should only be used outside of Jupyter
+if not in_ipython_session:  # Batch update should only be used outside of Jupyter
     app.add_typer(pr.app)
-
+    app.add_typer(ts.app)
 
 app.command()(doctor.doctor)
 
 if __name__ == "__main__":
     main()
```

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/api/models/group.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/api/models/team.py`

 * *Files 13% similar despite different names*

```diff
@@ -1,34 +1,41 @@
-"""dapla-team-api Group model."""
+"""dapla-team-api Team model."""
 from typing import Any
 from typing import Dict
 from typing import List
 
 from pydantic import BaseModel
 from pydantic import Field
 from pydantic import parse_obj_as
 from returns.result import Result
 
+from dapla_team_cli.api.api_request import DaplaTeamApiRequest
+from dapla_team_cli.api.models.group import Group
+from dapla_team_cli.api.models.group import parse_groups
 from dapla_team_cli.api.models.link import Link
 from dapla_team_cli.api.models.user import User
 from dapla_team_cli.api.models.user import parse_users
 from dapla_team_cli.api.utils import get_resource
 
 
-class Group(BaseModel):
-    """Information about a Dapla team auth group."""
+class Team(BaseModel):
+    """Information about a Dapla team."""
 
-    ID: str = Field(alias="id")
-    azure_id: str = Field(alias="azureId")
-    name: str
+    uniform_team_name: str = Field(alias="uniformTeamName")
+    display_team_name: str = Field(alias="displayTeamName")
+    repo: str
     links: Dict[str, Link] = Field(alias="_links")
 
     def users(self) -> Result[List[User], str]:
-        """Get a list of Users in this group."""
-        return get_resource(self.links["users"].href).map(parse_users)
+        """Get a list of users in this team."""
+        return get_resource(DaplaTeamApiRequest(endpoint=self.links["users"].href, body=None)).map(parse_users)
 
+    def groups(self) -> Result[List[Group], str]:
+        """Get a list of auth groups in this team."""
+        return get_resource(DaplaTeamApiRequest(endpoint=self.links["groups"].href, body=None)).map(parse_groups)
 
-def parse_groups(groups_json: Dict[str, Any]) -> List[Group]:
-    """Parse JSON into a list of Groups."""
-    if "_embedded" not in groups_json or "groupList" not in groups_json["_embedded"]:
+
+def parse_teams(teams_json: Dict[str, Any]) -> List[Team]:
+    """Parse JSON into a list of Teams."""
+    if "_embedded" not in teams_json or "teamList" not in teams_json["_embedded"]:
         return []
-    return parse_obj_as(List[Group], groups_json["_embedded"]["groupList"])
+    return parse_obj_as(List[Team], teams_json["_embedded"]["teamList"])
```

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/api/models/user.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/api/models/user.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/auth/cmd.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/auth/cmd.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/auth/services/get_token.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/auth/services/get_token.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/auth/services/set_token.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/auth/services/set_token.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/config.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/config.py`

 * *Files 16% similar despite different names*

```diff
@@ -42,8 +42,14 @@
 
     if tmp:
         return str(config_folder_path / "tmp/")
 
     return str(config_folder_path)
 
 
+try:
+    __IPYTHON__  # type: ignore [name-defined]
+    in_ipython_session = True
+except NameError:
+    in_ipython_session = False
+
 DAPLA_TEAM_API_BASE = os.getenv("DAPLA_TEAM_API_BASE_URL", "https://team-api.dapla-staging.ssb.no")
```

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/doctor/check.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/doctor/check.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/doctor/cmd.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/doctor/cmd.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/doctor/gcloud.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/doctor/gcloud.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/doctor/keycloak.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/doctor/keycloak.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/gcp/__init__.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/gcp/__init__.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/gcp/project_roles.json` & `dapla_team_cli-0.2.2/src/dapla_team_cli/gcp/project_roles.json`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/github.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/github.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/groups/list_members/cmd.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/groups/members/members.py`

 * *Files 24% similar despite different names*

```diff
@@ -1,54 +1,61 @@
-"""List-members CLI command definition."""
-import sys
+"""Add or remove members from groups."""
+
 from typing import List
-from typing import Optional
 
-import typer
 from returns.pipeline import flow
 from returns.pointfree import alt
 from returns.pointfree import bind
 from returns.pointfree import map_
 from rich.console import Console
 from rich.style import Style
 from rich.table import Table
 
+from dapla_team_cli.api.api_request import DaplaTeamApiRequest
+from dapla_team_cli.api.api_request import UserBody
 from dapla_team_cli.api.models.group import Group
 from dapla_team_cli.api.models.team import Team
 from dapla_team_cli.api.models.user import User
+from dapla_team_cli.api.utils import delete_resource
 from dapla_team_cli.api.utils import get_resource
+from dapla_team_cli.api.utils import post_resource
 from dapla_team_cli.config import DAPLA_TEAM_API_BASE
-from dapla_team_cli.team import get_remote_from_name
-from dapla_team_cli.team import get_team_name
+from dapla_team_cli.result_utils import fail
 
 
 console = Console()
 
 styles = {
     "normal": Style(blink=True, bold=True),
     "warning": Style(color="dark_orange3", blink=True, bold=True),
 }
 
 
-def fail(message: str) -> None:
-    """Exit with a message if a Failure occurs."""
-    print(message)
-    sys.exit(1)
+def add_members(group_name: str, members: List[str]) -> None:
+    """Adds a member to a group."""
+    flow(
+        DaplaTeamApiRequest(endpoint=f"{DAPLA_TEAM_API_BASE}/groups/{group_name}", body=UserBody(users=members)),
+        post_resource,
+        alt(fail),
+    )
+
 
+def remove_members(group_name: str, members: List[str]) -> None:
+    """Removes a member from a group."""
+    flow(
+        DaplaTeamApiRequest(endpoint=f"{DAPLA_TEAM_API_BASE}/groups/{group_name}", body=UserBody(users=members)),
+        delete_resource,
+        alt(fail),
+    )
 
-def list_members(
-    team_name: Optional[str] = typer.Option(None, "--team-name", "-tn", help="Team name (e.g. demo-enhjoern-a)")  # noqa: B008
-) -> None:
-    """List groups (and members) for a team."""
-    if team_name is None:
-        team_name = get_team_name()
-    team = get_remote_from_name(team_name)
 
+def list_members(team_name: str) -> None:
+    """List members in groups."""
     flow(
-        f"{DAPLA_TEAM_API_BASE}/teams/{team.name}",
+        DaplaTeamApiRequest(endpoint=f"{DAPLA_TEAM_API_BASE}/teams/{team_name}", body=None),
         get_resource,
         map_(Team.parse_obj),
         bind(Team.groups),
         map_(_print_groups),
         alt(fail),
     )
```

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/pr/approve/approve.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/pr/approve/approve.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/pr/atlantis_apply/atlantis_apply_all.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/pr/atlantis_apply/atlantis_apply_all.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/pr/atlantis_apply/cmd.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/pr/atlantis_apply/cmd.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/pr/atlantis_plan/atlantis_plan_all.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/pr/atlantis_plan/atlantis_plan_all.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/pr/batch_handler.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/pr/batch_handler.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/pr/cmd.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/pr/cmd.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/pr/const.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/pr/const.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/pr/janitor/close_all.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/pr/janitor/close_all.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/pr/janitor/cmd.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/pr/janitor/cmd.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/pr/merge/cmd.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/pr/merge/cmd.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/pr/merge/merge_all.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/pr/merge/merge_all.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/pr/open/cmd.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/pr/open/cmd.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/pr/open/open_prs.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/pr/open/open_prs.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/pr/probe/cmd.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/pr/probe/cmd.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/pr/probe/probe_atlantis_apply.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/pr/probe/probe_atlantis_apply.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/pr/probe/probe_workflows.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/pr/probe/probe_workflows.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/pr/ready/cmd.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/pr/ready/cmd.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/pr/ready/generate_state.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/pr/ready/generate_state.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/pr/rich_check.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/pr/rich_check.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/pr/state/cmd.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/pr/state/cmd.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/pr/state/state_commands.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/pr/state/state_commands.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/pr/state/state_utils.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/pr/state/state_utils.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/secrets/cmd.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/secrets/cmd.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/secrets/services.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/secrets/services.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/team.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/team.py`

 * *Files 16% similar despite different names*

```diff
@@ -11,14 +11,15 @@
 from pydantic import BaseModel
 from returns.pipeline import flow
 from returns.pipeline import is_successful
 from returns.pointfree import map_
 from returns.result import Result
 
 from dapla_team_cli import prompt_custom_style
+from dapla_team_cli.api.api_request import DaplaTeamApiRequest
 from dapla_team_cli.api.models.team import Team
 from dapla_team_cli.api.models.team import parse_teams
 from dapla_team_cli.api.utils import get_resource
 from dapla_team_cli.config import DAPLA_TEAM_API_BASE
 from dapla_team_cli.config import get_config_folder_path
 
 
@@ -69,17 +70,19 @@
             sys.exit(1)
 
     return TeamRepoInfo(name=team_name, remote_url=iac_repo_remote_url, clone_folder=iac_repo_clone_folder)
 
 
 def ask_for_team_name() -> str:
     """Ask for team name."""
-    teams: Result[List[Team], str] = flow(f"{DAPLA_TEAM_API_BASE}/teams", get_resource, map_(parse_teams))
+    teams: Result[List[Team], str] = flow(
+        DaplaTeamApiRequest(endpoint=f"{DAPLA_TEAM_API_BASE}/teams", body=None), get_resource, map_(parse_teams)
+    )
     if not is_successful(teams):
-        if "401 Unauthorized" in teams.failure():
+        if "401" in teams.failure():
             print("Autocomplete unavailable due to authentication failure.")
             if os.getenv("NB_USER") != "jovyan":
                 print("You may need to run `dpteam auth login` to fix it.")
         logger.debug("failure getting list of teams: %s", teams.failure())
         team_choices = [f"Autocomplete unavailable due to: {teams.failure()}"]
     else:
         team_choices = [team.uniform_team_name for team in teams.unwrap()]
```

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/tf/iam_bindings/auth_groups.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/tf/iam_bindings/auth_groups.py`

 * *Files 2% similar despite different names*

```diff
@@ -79,14 +79,15 @@
         choices=[
             q.Choice(auth_group, value=auth_group)
             for auth_group in [
                 f"{team_name}-support",
                 f"{team_name}-developers",
                 f"{team_name}-data-admins",
                 f"{team_name}-managers",
+                f"{team_name}-consumers",
                 "other...",
             ]
         ],
     ).ask()
 
     if auth_group == "other...":
         auth_group = q.text(
```

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/tf/iam_bindings/buckets.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/tf/iam_bindings/buckets.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/tf/iam_bindings/cmd.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/tf/iam_bindings/cmd.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/tf/iam_bindings/configs.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/tf/iam_bindings/configs.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/tf/iam_bindings/expiry.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/tf/iam_bindings/expiry.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/tf/iam_bindings/project_roles.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/tf/iam_bindings/project_roles.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/tf/iam_bindings/templates/buckets-iam.jinja` & `dapla_team_cli-0.2.2/src/dapla_team_cli/tf/iam_bindings/templates/buckets-iam.jinja`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/tf/iam_bindings/templates/projects-iam.jinja` & `dapla_team_cli-0.2.2/src/dapla_team_cli/tf/iam_bindings/templates/projects-iam.jinja`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/tf/iam_bindings/terraform.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/tf/iam_bindings/terraform.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/src/dapla_team_cli/tf/iam_bindings/utilities.py` & `dapla_team_cli-0.2.2/src/dapla_team_cli/tf/iam_bindings/utilities.py`

 * *Files identical despite different names*

### Comparing `dapla_team_cli-0.2.0/PKG-INFO` & `dapla_team_cli-0.2.2/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: dapla-team-cli
-Version: 0.2.0
+Version: 0.2.2
 Summary: CLI for working with Dapla Teams
 Home-page: https://github.com/statisticsnorway/dapla-team-cli
 License: MIT
 Author: Kenneth Leine Schulstad
 Author-email: kls@rdck.no
 Requires-Python: >=3.10.0,<4.0
 Classifier: Development Status :: 2 - Pre-Alpha
@@ -117,9 +117,9 @@
 [file an issue]: https://github.com/statisticsnorway/dapla-team-cli/issues
 [pipx]: https://pypa.github.io/pipx
 
 <!-- github-only -->
 
 [license]: https://github.com/statisticsnorway/dapla-team-cli/blob/main/LICENSE
 [contributor guide]: https://github.com/statisticsnorway/dapla-team-cli/blob/main/CONTRIBUTING.md
-[command-line reference]: https://statisticsnorway.github.io/dapla-team-cli/command_reference.md
+[command-line reference]: https://statisticsnorway.github.io/dapla-team-cli/command_reference/
```


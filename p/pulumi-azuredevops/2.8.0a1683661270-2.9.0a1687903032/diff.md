# Comparing `tmp/pulumi_azuredevops-2.8.0a1683661270.tar.gz` & `tmp/pulumi_azuredevops-2.9.0a1687903032.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pulumi_azuredevops-2.8.0a1683661270.tar", last modified: Tue May  9 19:47:38 2023, max compression
+gzip compressed data, was "pulumi_azuredevops-2.9.0a1687903032.tar", last modified: Tue Jun 27 22:02:01 2023, max compression
```

## Comparing `pulumi_azuredevops-2.8.0a1683661270.tar` & `pulumi_azuredevops-2.9.0a1687903032.tar`

### file list

```diff
@@ -1,173 +1,178 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-09 19:47:38.406342 pulumi_azuredevops-2.8.0a1683661270/
--rw-r--r--   0 runner    (1001) docker     (123)     2779 2023-05-09 19:47:38.402342 pulumi_azuredevops-2.8.0a1683661270/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2408 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-09 19:47:38.398342 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/
--rw-r--r--   0 runner    (1001) docker     (123)    24455 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)   147060 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/_inputs.py
--rw-r--r--   0 runner    (1001) docker     (123)     8081 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/_utilities.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-09 19:47:38.398342 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/agent/
--rw-r--r--   0 runner    (1001) docker     (123)      381 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/agent/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5243 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/agent/get_pool.py
--rw-r--r--   0 runner    (1001) docker     (123)     3194 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/agent/get_pools.py
--rw-r--r--   0 runner    (1001) docker     (123)     2325 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/agent/outputs.py
--rw-r--r--   0 runner    (1001) docker     (123)    13934 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/agent/pool.py
--rw-r--r--   0 runner    (1001) docker     (123)    10876 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/agent/queue.py
--rw-r--r--   0 runner    (1001) docker     (123)    17119 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/area_permissions.py
--rw-r--r--   0 runner    (1001) docker     (123)    16909 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/branch_policy_auto_reviewers.py
--rw-r--r--   0 runner    (1001) docker     (123)    18285 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/branch_policy_build_validation.py
--rw-r--r--   0 runner    (1001) docker     (123)    16901 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/branch_policy_comment_resolution.py
--rw-r--r--   0 runner    (1001) docker     (123)    16839 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/branch_policy_merge_types.py
--rw-r--r--   0 runner    (1001) docker     (123)    17465 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/branch_policy_min_reviewers.py
--rw-r--r--   0 runner    (1001) docker     (123)    17269 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/branch_policy_status_check.py
--rw-r--r--   0 runner    (1001) docker     (123)    16783 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/branch_policy_work_item_linking.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-09 19:47:38.398342 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/build/
--rw-r--r--   0 runner    (1001) docker     (123)      346 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/build/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    48005 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/build/_inputs.py
--rw-r--r--   0 runner    (1001) docker     (123)    38702 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/build/build_definition.py
--rw-r--r--   0 runner    (1001) docker     (123)    44955 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/build/outputs.py
--rw-r--r--   0 runner    (1001) docker     (123)    38457 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/build_definition.py
--rw-r--r--   0 runner    (1001) docker     (123)    19191 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/build_definition_permissions.py
--rw-r--r--   0 runner    (1001) docker     (123)    10897 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/build_folder.py
--rw-r--r--   0 runner    (1001) docker     (123)    18236 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/build_folder_permissions.py
--rw-r--r--   0 runner    (1001) docker     (123)    32736 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/check_branch_control.py
--rw-r--r--   0 runner    (1001) docker     (123)    52960 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/check_business_hours.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-09 19:47:38.398342 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/config/
--rw-r--r--   0 runner    (1001) docker     (123)      285 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/config/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      895 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/config/vars.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-09 19:47:38.398342 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/core/
--rw-r--r--   0 runner    (1001) docker     (123)      434 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/core/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2715 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/core/get_client_config.py
--rw-r--r--   0 runner    (1001) docker     (123)     7091 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/core/get_project.py
--rw-r--r--   0 runner    (1001) docker     (123)     5973 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/core/get_projects.py
--rw-r--r--   0 runner    (1001) docker     (123)     2140 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/core/outputs.py
--rw-r--r--   0 runner    (1001) docker     (123)    21750 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/core/project.py
--rw-r--r--   0 runner    (1001) docker     (123)    10599 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/core/project_features.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-09 19:47:38.398342 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/entitlement/
--rw-r--r--   0 runner    (1001) docker     (123)      289 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/entitlement/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    21027 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/entitlement/user.py
--rw-r--r--   0 runner    (1001) docker     (123)    11285 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/environment.py
--rw-r--r--   0 runner    (1001) docker     (123)     5414 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_agent_queue.py
--rw-r--r--   0 runner    (1001) docker     (123)     7809 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_area.py
--rw-r--r--   0 runner    (1001) docker     (123)     9131 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_build_definition.py
--rw-r--r--   0 runner    (1001) docker     (123)     2427 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_client_config.py
--rw-r--r--   0 runner    (1001) docker     (123)     7712 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_git_repository.py
--rw-r--r--   0 runner    (1001) docker     (123)     6593 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_group.py
--rw-r--r--   0 runner    (1001) docker     (123)     4258 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_groups.py
--rw-r--r--   0 runner    (1001) docker     (123)     8222 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_iteration.py
--rw-r--r--   0 runner    (1001) docker     (123)     4864 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_pool.py
--rw-r--r--   0 runner    (1001) docker     (123)     2939 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_pools.py
--rw-r--r--   0 runner    (1001) docker     (123)     6692 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_project.py
--rw-r--r--   0 runner    (1001) docker     (123)     5566 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_projects.py
--rw-r--r--   0 runner    (1001) docker     (123)     6231 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_repositories.py
--rw-r--r--   0 runner    (1001) docker     (123)    11555 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_service_endpoint_azure_rm.py
--rw-r--r--   0 runner    (1001) docker     (123)     7381 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_service_endpoint_github.py
--rw-r--r--   0 runner    (1001) docker     (123)     6433 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_team.py
--rw-r--r--   0 runner    (1001) docker     (123)     4897 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_teams.py
--rw-r--r--   0 runner    (1001) docker     (123)     8027 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_users.py
--rw-r--r--   0 runner    (1001) docker     (123)     7158 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_variable_group.py
--rw-r--r--   0 runner    (1001) docker     (123)    22657 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/git.py
--rw-r--r--   0 runner    (1001) docker     (123)    29029 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/git_permissions.py
--rw-r--r--   0 runner    (1001) docker     (123)    18373 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/git_repository_branch.py
--rw-r--r--   0 runner    (1001) docker     (123)    19180 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/git_repository_file.py
--rw-r--r--   0 runner    (1001) docker     (123)    29921 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/group.py
--rw-r--r--   0 runner    (1001) docker     (123)    16344 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/group_membership.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-09 19:47:38.402342 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/identities/
--rw-r--r--   0 runner    (1001) docker     (123)      394 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/identities/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     7000 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/identities/get_group.py
--rw-r--r--   0 runner    (1001) docker     (123)     8434 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/identities/get_users.py
--rw-r--r--   0 runner    (1001) docker     (123)    30141 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/identities/group.py
--rw-r--r--   0 runner    (1001) docker     (123)    16604 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/identities/group_membership.py
--rw-r--r--   0 runner    (1001) docker     (123)     3792 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/identities/outputs.py
--rw-r--r--   0 runner    (1001) docker     (123)    17830 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/iterative_permissions.py
--rw-r--r--   0 runner    (1001) docker     (123)   189015 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/outputs.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-09 19:47:38.402342 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/pipeline/
--rw-r--r--   0 runner    (1001) docker     (123)      344 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/pipeline/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6356 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/pipeline/_inputs.py
--rw-r--r--   0 runner    (1001) docker     (123)     6104 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/pipeline/outputs.py
--rw-r--r--   0 runner    (1001) docker     (123)    24694 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/pipeline/variable_group.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-09 19:47:38.402342 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/policy/
--rw-r--r--   0 runner    (1001) docker     (123)      403 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/policy/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    19196 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/policy/_inputs.py
--rw-r--r--   0 runner    (1001) docker     (123)    18595 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/policy/branch_policy_build_validation.py
--rw-r--r--   0 runner    (1001) docker     (123)    17760 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/policy/branch_policy_min_reviewers.py
--rw-r--r--   0 runner    (1001) docker     (123)    18687 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/policy/outputs.py
--rw-r--r--   0 runner    (1001) docker     (123)    13744 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/pool.py
--rw-r--r--   0 runner    (1001) docker     (123)    21552 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/project.py
--rw-r--r--   0 runner    (1001) docker     (123)    10359 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/project_features.py
--rw-r--r--   0 runner    (1001) docker     (123)    14893 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/project_permissions.py
--rw-r--r--   0 runner    (1001) docker     (123)    20739 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/project_pipeline_settings.py
--rw-r--r--   0 runner    (1001) docker     (123)     6491 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/provider.py
--rw-r--r--   0 runner    (1001) docker     (123)       48 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/pulumi-plugin.json
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    10681 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/queue.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-09 19:47:38.402342 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/repository/
--rw-r--r--   0 runner    (1001) docker     (123)      365 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/repository/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3325 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/repository/_inputs.py
--rw-r--r--   0 runner    (1001) docker     (123)     6694 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/repository/get_repositories.py
--rw-r--r--   0 runner    (1001) docker     (123)    22877 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/repository/git.py
--rw-r--r--   0 runner    (1001) docker     (123)     6629 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/repository/outputs.py
--rw-r--r--   0 runner    (1001) docker     (123)    21646 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/repository_policy_author_email_pattern.py
--rw-r--r--   0 runner    (1001) docker     (123)    20590 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/repository_policy_case_enforcement.py
--rw-r--r--   0 runner    (1001) docker     (123)    17771 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/repository_policy_check_credentials.py
--rw-r--r--   0 runner    (1001) docker     (123)    21645 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/repository_policy_file_path_pattern.py
--rw-r--r--   0 runner    (1001) docker     (123)    20081 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/repository_policy_max_file_size.py
--rw-r--r--   0 runner    (1001) docker     (123)    19867 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/repository_policy_max_path_length.py
--rw-r--r--   0 runner    (1001) docker     (123)    17657 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/repository_policy_reserved_names.py
--rw-r--r--   0 runner    (1001) docker     (123)    17259 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/resource_authorization.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-09 19:47:38.402342 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/security/
--rw-r--r--   0 runner    (1001) docker     (123)      307 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/security/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    17543 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/security/resource_authorization.py
--rw-r--r--   0 runner    (1001) docker     (123)    22800 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_artifactory.py
--rw-r--r--   0 runner    (1001) docker     (123)    30438 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_aws.py
--rw-r--r--   0 runner    (1001) docker     (123)    22356 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_azure_dev_ops.py
--rw-r--r--   0 runner    (1001) docker     (123)    30733 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_azure_ecr.py
--rw-r--r--   0 runner    (1001) docker     (123)    39015 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_azure_rm.py
--rw-r--r--   0 runner    (1001) docker     (123)    18522 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_bit_bucket.py
--rw-r--r--   0 runner    (1001) docker     (123)    27775 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_docker_registry.py
--rw-r--r--   0 runner    (1001) docker     (123)    21448 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_generic.py
--rw-r--r--   0 runner    (1001) docker     (123)    24317 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_generic_git.py
--rw-r--r--   0 runner    (1001) docker     (123)    22104 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_git_hub.py
--rw-r--r--   0 runner    (1001) docker     (123)    18919 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_git_hub_enterprise.py
--rw-r--r--   0 runner    (1001) docker     (123)    25990 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_kubernetes.py
--rw-r--r--   0 runner    (1001) docker     (123)    18135 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_npm.py
--rw-r--r--   0 runner    (1001) docker     (123)    19896 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_pipeline.py
--rw-r--r--   0 runner    (1001) docker     (123)    26154 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_service_fabric.py
--rw-r--r--   0 runner    (1001) docker     (123)    16823 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_sonar_cloud.py
--rw-r--r--   0 runner    (1001) docker     (123)    19644 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_sonar_qube.py
--rw-r--r--   0 runner    (1001) docker     (123)    25220 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_ssh.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-09 19:47:38.402342 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint/
--rw-r--r--   0 runner    (1001) docker     (123)      444 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    14031 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint/_inputs.py
--rw-r--r--   0 runner    (1001) docker     (123)    38745 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint/azure_rm.py
--rw-r--r--   0 runner    (1001) docker     (123)    18472 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint/bit_bucket.py
--rw-r--r--   0 runner    (1001) docker     (123)    27750 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint/docker_registry.py
--rw-r--r--   0 runner    (1001) docker     (123)    21619 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint/git_hub.py
--rw-r--r--   0 runner    (1001) docker     (123)    25315 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint/kubernetes.py
--rw-r--r--   0 runner    (1001) docker     (123)    14643 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint/outputs.py
--rw-r--r--   0 runner    (1001) docker     (123)    24537 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint_argocd.py
--rw-r--r--   0 runner    (1001) docker     (123)    17775 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint_externaltfs.py
--rw-r--r--   0 runner    (1001) docker     (123)    20949 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint_incomingwebhook.py
--rw-r--r--   0 runner    (1001) docker     (123)    25176 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint_jfrog_artifactory_v2.py
--rw-r--r--   0 runner    (1001) docker     (123)    25252 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint_jfrog_distribution_v2.py
--rw-r--r--   0 runner    (1001) docker     (123)    24924 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint_jfrog_platform_v2.py
--rw-r--r--   0 runner    (1001) docker     (123)    24638 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint_jfrog_xray_v2.py
--rw-r--r--   0 runner    (1001) docker     (123)    19961 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint_octopusdeploy.py
--rw-r--r--   0 runner    (1001) docker     (123)    19604 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint_permissions.py
--rw-r--r--   0 runner    (1001) docker     (123)    15186 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/servicehook_permissions.py
--rw-r--r--   0 runner    (1001) docker     (123)    15665 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/tagging_permissions.py
--rw-r--r--   0 runner    (1001) docker     (123)    17288 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/team.py
--rw-r--r--   0 runner    (1001) docker     (123)    16132 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/team_administrators.py
--rw-r--r--   0 runner    (1001) docker     (123)    15381 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/team_members.py
--rw-r--r--   0 runner    (1001) docker     (123)    20819 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/user.py
--rw-r--r--   0 runner    (1001) docker     (123)    24438 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/variable_group.py
--rw-r--r--   0 runner    (1001) docker     (123)    22220 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/work_item_query_permissions.py
--rw-r--r--   0 runner    (1001) docker     (123)    21319 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/workitem.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-09 19:47:38.398342 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     2779 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     6645 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       49 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       19 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-05-09 19:47:38.406342 pulumi_azuredevops-2.8.0a1683661270/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2185 2023-05-09 19:47:38.000000 pulumi_azuredevops-2.8.0a1683661270/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 22:02:01.439819 pulumi_azuredevops-2.9.0a1687903032/
+-rw-r--r--   0 runner    (1001) docker     (123)     2779 2023-06-27 22:02:01.439819 pulumi_azuredevops-2.9.0a1687903032/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2408 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 22:02:01.435819 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/
+-rw-r--r--   0 runner    (1001) docker     (123)    25284 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)   148052 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/_inputs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8081 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/_utilities.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 22:02:01.435819 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/agent/
+-rw-r--r--   0 runner    (1001) docker     (123)      381 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/agent/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5243 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/agent/get_pool.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3194 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/agent/get_pools.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2325 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/agent/outputs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13934 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/agent/pool.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10876 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/agent/queue.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21946 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/area_permissions.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16909 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/branch_policy_auto_reviewers.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18285 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/branch_policy_build_validation.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16901 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/branch_policy_comment_resolution.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16839 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/branch_policy_merge_types.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17521 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/branch_policy_min_reviewers.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17269 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/branch_policy_status_check.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16783 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/branch_policy_work_item_linking.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 22:02:01.435819 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/build/
+-rw-r--r--   0 runner    (1001) docker     (123)      346 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/build/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    48005 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/build/_inputs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    38702 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/build/build_definition.py
+-rw-r--r--   0 runner    (1001) docker     (123)    44955 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/build/outputs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    38457 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/build_definition.py
+-rw-r--r--   0 runner    (1001) docker     (123)    29611 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/build_definition_permissions.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10897 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/build_folder.py
+-rw-r--r--   0 runner    (1001) docker     (123)    28656 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/build_folder_permissions.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24797 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/check_approval.py
+-rw-r--r--   0 runner    (1001) docker     (123)    32736 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/check_branch_control.py
+-rw-r--r--   0 runner    (1001) docker     (123)    52960 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/check_business_hours.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 22:02:01.435819 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/config/
+-rw-r--r--   0 runner    (1001) docker     (123)      285 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/config/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      895 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/config/vars.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 22:02:01.435819 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/core/
+-rw-r--r--   0 runner    (1001) docker     (123)      434 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/core/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2715 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/core/get_client_config.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7091 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/core/get_project.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6159 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/core/get_projects.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2320 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/core/outputs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23966 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/core/project.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12815 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/core/project_features.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 22:02:01.435819 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/entitlement/
+-rw-r--r--   0 runner    (1001) docker     (123)      289 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/entitlement/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22004 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/entitlement/user.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11285 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/environment.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5414 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_agent_queue.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7809 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_area.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9131 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_build_definition.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2427 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_client_config.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7712 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_git_repository.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6593 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_group.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4258 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_groups.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8222 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_iteration.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4864 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_pool.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2939 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_pools.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6692 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_project.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5752 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_projects.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6489 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_repositories.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12011 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_service_endpoint_azure_rm.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7837 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_service_endpoint_github.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6908 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_serviceendpoint_npm.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6722 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_serviceendpoint_sonarcloud.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6433 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_team.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4897 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_teams.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8749 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_users.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7158 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_variable_group.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22657 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/git.py
+-rw-r--r--   0 runner    (1001) docker     (123)    42152 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/git_permissions.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18373 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/git_repository_branch.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19180 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/git_repository_file.py
+-rw-r--r--   0 runner    (1001) docker     (123)    29921 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/group.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16344 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/group_membership.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 22:02:01.435819 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/identities/
+-rw-r--r--   0 runner    (1001) docker     (123)      394 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/identities/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7000 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/identities/get_group.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9156 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/identities/get_users.py
+-rw-r--r--   0 runner    (1001) docker     (123)    30141 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/identities/group.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16604 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/identities/group_membership.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4488 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/identities/outputs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20627 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/iterative_permissions.py
+-rw-r--r--   0 runner    (1001) docker     (123)   190883 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/outputs.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 22:02:01.435819 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/pipeline/
+-rw-r--r--   0 runner    (1001) docker     (123)      344 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/pipeline/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6356 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/pipeline/_inputs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6104 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/pipeline/outputs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24694 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/pipeline/variable_group.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18446 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/pipeline_authorization.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 22:02:01.439819 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/policy/
+-rw-r--r--   0 runner    (1001) docker     (123)      403 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/policy/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19760 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/policy/_inputs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18595 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/policy/branch_policy_build_validation.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17816 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/policy/branch_policy_min_reviewers.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19251 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/policy/outputs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13744 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/pool.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23768 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/project.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12575 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/project_features.py
+-rw-r--r--   0 runner    (1001) docker     (123)    32348 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/project_permissions.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26391 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/project_pipeline_settings.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6491 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/provider.py
+-rw-r--r--   0 runner    (1001) docker     (123)       48 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/pulumi-plugin.json
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    10681 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/queue.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 22:02:01.439819 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/repository/
+-rw-r--r--   0 runner    (1001) docker     (123)      365 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/repository/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3325 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/repository/_inputs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6952 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/repository/get_repositories.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22877 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/repository/git.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6629 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/repository/outputs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21646 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/repository_policy_author_email_pattern.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20590 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/repository_policy_case_enforcement.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17771 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/repository_policy_check_credentials.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21645 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/repository_policy_file_path_pattern.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20081 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/repository_policy_max_file_size.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19867 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/repository_policy_max_path_length.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17657 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/repository_policy_reserved_names.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17259 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/resource_authorization.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 22:02:01.439819 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/security/
+-rw-r--r--   0 runner    (1001) docker     (123)      307 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/security/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17543 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/security/resource_authorization.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23910 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_artifactory.py
+-rw-r--r--   0 runner    (1001) docker     (123)    30438 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_aws.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22356 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_azure_dev_ops.py
+-rw-r--r--   0 runner    (1001) docker     (123)    30733 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_azure_ecr.py
+-rw-r--r--   0 runner    (1001) docker     (123)    40776 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_azure_rm.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18522 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_bit_bucket.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27775 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_docker_registry.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21448 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_generic.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24944 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_generic_git.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21079 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_git_hub.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17746 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_git_hub_enterprise.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25990 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_kubernetes.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18135 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_npm.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19896 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_pipeline.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26154 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_service_fabric.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16823 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_sonar_cloud.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19644 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_sonar_qube.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25220 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_ssh.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 22:02:01.439819 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint/
+-rw-r--r--   0 runner    (1001) docker     (123)      444 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14031 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint/_inputs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    40506 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint/azure_rm.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18472 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint/bit_bucket.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27750 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint/docker_registry.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20654 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint/git_hub.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25315 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint/kubernetes.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14643 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint/outputs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25458 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint_argocd.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17775 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint_externaltfs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24481 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint_gcp_terraform.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20949 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint_incomingwebhook.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25698 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint_jfrog_artifactory_v2.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25774 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint_jfrog_distribution_v2.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25446 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint_jfrog_platform_v2.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25160 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint_jfrog_xray_v2.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19961 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint_octopusdeploy.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23199 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint_permissions.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17857 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/servicehook_permissions.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18420 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/tagging_permissions.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21748 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/team.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18460 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/team_administrators.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17513 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/team_members.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21796 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/user.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24438 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/variable_group.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25563 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/work_item_query_permissions.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25381 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/workitem.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 22:02:01.435819 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     2779 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     6878 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       49 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       19 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-27 22:02:01.439819 pulumi_azuredevops-2.9.0a1687903032/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2185 2023-06-27 22:02:01.000000 pulumi_azuredevops-2.9.0a1687903032/setup.py
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/PKG-INFO` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
-Name: pulumi_azuredevops
-Version: 2.8.0a1683661270
+Name: pulumi-azuredevops
+Version: 2.9.0a1687903032
 Summary: A Pulumi package for creating and managing Azure DevOps.
 Home-page: https://pulumi.io
 License: Apache-2.0
 Project-URL: Repository, https://github.com/pulumi/pulumi-azuredevops
 Keywords: pulumi azuredevops
 Platform: UNKNOWN
 Requires-Python: >=3.7
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/README.md` & `pulumi_azuredevops-2.9.0a1687903032/README.md`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/__init__.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/__init__.py`

 * *Files 1% similar despite different names*

```diff
@@ -13,14 +13,15 @@
 from .branch_policy_min_reviewers import *
 from .branch_policy_status_check import *
 from .branch_policy_work_item_linking import *
 from .build_definition import *
 from .build_definition_permissions import *
 from .build_folder import *
 from .build_folder_permissions import *
+from .check_approval import *
 from .check_branch_control import *
 from .check_business_hours import *
 from .environment import *
 from .get_agent_queue import *
 from .get_area import *
 from .get_build_definition import *
 from .get_client_config import *
@@ -31,25 +32,28 @@
 from .get_pool import *
 from .get_pools import *
 from .get_project import *
 from .get_projects import *
 from .get_repositories import *
 from .get_service_endpoint_azure_rm import *
 from .get_service_endpoint_github import *
+from .get_serviceendpoint_npm import *
+from .get_serviceendpoint_sonarcloud import *
 from .get_team import *
 from .get_teams import *
 from .get_users import *
 from .get_variable_group import *
 from .git import *
 from .git_permissions import *
 from .git_repository_branch import *
 from .git_repository_file import *
 from .group import *
 from .group_membership import *
 from .iterative_permissions import *
+from .pipeline_authorization import *
 from .pool import *
 from .project import *
 from .project_features import *
 from .project_permissions import *
 from .project_pipeline_settings import *
 from .provider import *
 from .queue import *
@@ -77,14 +81,15 @@
 from .service_endpoint_pipeline import *
 from .service_endpoint_service_fabric import *
 from .service_endpoint_sonar_cloud import *
 from .service_endpoint_sonar_qube import *
 from .service_endpoint_ssh import *
 from .serviceendpoint_argocd import *
 from .serviceendpoint_externaltfs import *
+from .serviceendpoint_gcp_terraform import *
 from .serviceendpoint_incomingwebhook import *
 from .serviceendpoint_jfrog_artifactory_v2 import *
 from .serviceendpoint_jfrog_distribution_v2 import *
 from .serviceendpoint_jfrog_platform_v2 import *
 from .serviceendpoint_jfrog_xray_v2 import *
 from .serviceendpoint_octopusdeploy import *
 from .serviceendpoint_permissions import *
@@ -378,14 +383,22 @@
   "fqn": "pulumi_azuredevops",
   "classes": {
    "azuredevops:index/buildFolderPermissions:BuildFolderPermissions": "BuildFolderPermissions"
   }
  },
  {
   "pkg": "azuredevops",
+  "mod": "index/checkApproval",
+  "fqn": "pulumi_azuredevops",
+  "classes": {
+   "azuredevops:index/checkApproval:CheckApproval": "CheckApproval"
+  }
+ },
+ {
+  "pkg": "azuredevops",
   "mod": "index/checkBranchControl",
   "fqn": "pulumi_azuredevops",
   "classes": {
    "azuredevops:index/checkBranchControl:CheckBranchControl": "CheckBranchControl"
   }
  },
  {
@@ -458,14 +471,22 @@
   "fqn": "pulumi_azuredevops",
   "classes": {
    "azuredevops:index/iterativePermissions:IterativePermissions": "IterativePermissions"
   }
  },
  {
   "pkg": "azuredevops",
+  "mod": "index/pipelineAuthorization",
+  "fqn": "pulumi_azuredevops",
+  "classes": {
+   "azuredevops:index/pipelineAuthorization:PipelineAuthorization": "PipelineAuthorization"
+  }
+ },
+ {
+  "pkg": "azuredevops",
   "mod": "index/pool",
   "fqn": "pulumi_azuredevops",
   "classes": {
    "azuredevops:index/pool:Pool": "Pool"
   }
  },
  {
@@ -730,14 +751,22 @@
   "fqn": "pulumi_azuredevops",
   "classes": {
    "azuredevops:index/serviceendpointExternaltfs:ServiceendpointExternaltfs": "ServiceendpointExternaltfs"
   }
  },
  {
   "pkg": "azuredevops",
+  "mod": "index/serviceendpointGcpTerraform",
+  "fqn": "pulumi_azuredevops",
+  "classes": {
+   "azuredevops:index/serviceendpointGcpTerraform:ServiceendpointGcpTerraform": "ServiceendpointGcpTerraform"
+  }
+ },
+ {
+  "pkg": "azuredevops",
   "mod": "index/serviceendpointIncomingwebhook",
   "fqn": "pulumi_azuredevops",
   "classes": {
    "azuredevops:index/serviceendpointIncomingwebhook:ServiceendpointIncomingwebhook": "ServiceendpointIncomingwebhook"
   }
  },
  {
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/_inputs.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/_inputs.py`

 * *Files 0% similar despite different names*

```diff
@@ -76,14 +76,16 @@
                  path_filters: Optional[pulumi.Input[Sequence[pulumi.Input[str]]]] = None,
                  submitter_can_vote: Optional[pulumi.Input[bool]] = None):
         """
         :param pulumi.Input[Sequence[pulumi.Input[str]]] auto_reviewer_ids: Required reviewers ids. Supports multiples user Ids.
         :param pulumi.Input[Sequence[pulumi.Input['BranchPolicyAutoReviewersSettingsScopeArgs']]] scopes: Controls which repositories and branches the policy will be enabled for. This block must be defined at least once.
         :param pulumi.Input[str] message: Activity feed message, Message will appear in the activity feed of pull requests with automatically added reviewers.
         :param pulumi.Input[int] minimum_number_of_reviewers: Minimum number of required reviewers. Defaults to `1`.
+               
+               > **Note** Has to be greater than `0`. Can only be greater than `1` when attribute `auto_reviewer_ids` contains exactly one group! Only has an effect when attribute `blocking` is set to `true`.
         :param pulumi.Input[Sequence[pulumi.Input[str]]] path_filters: Filter path(s) on which the policy is applied. Supports absolute paths, wildcards and multiple paths. Example: /WebApp/Models/Data.cs, /WebApp/* or *.cs,/WebApp/Models/Data.cs;ClientApp/Models/Data.cs.
         :param pulumi.Input[bool] submitter_can_vote: Controls whether or not the submitter's vote counts. Defaults to `false`.
         """
         pulumi.set(__self__, "auto_reviewer_ids", auto_reviewer_ids)
         pulumi.set(__self__, "scopes", scopes)
         if message is not None:
             pulumi.set(__self__, "message", message)
@@ -131,14 +133,16 @@
         pulumi.set(self, "message", value)
 
     @property
     @pulumi.getter(name="minimumNumberOfReviewers")
     def minimum_number_of_reviewers(self) -> Optional[pulumi.Input[int]]:
         """
         Minimum number of required reviewers. Defaults to `1`.
+
+        > **Note** Has to be greater than `0`. Can only be greater than `1` when attribute `auto_reviewer_ids` contains exactly one group! Only has an effect when attribute `blocking` is set to `true`.
         """
         return pulumi.get(self, "minimum_number_of_reviewers")
 
     @minimum_number_of_reviewers.setter
     def minimum_number_of_reviewers(self, value: Optional[pulumi.Input[int]]):
         pulumi.set(self, "minimum_number_of_reviewers", value)
 
@@ -619,19 +623,21 @@
                  last_pusher_cannot_approve: Optional[pulumi.Input[bool]] = None,
                  on_last_iteration_require_vote: Optional[pulumi.Input[bool]] = None,
                  on_push_reset_all_votes: Optional[pulumi.Input[bool]] = None,
                  on_push_reset_approved_votes: Optional[pulumi.Input[bool]] = None,
                  reviewer_count: Optional[pulumi.Input[int]] = None,
                  submitter_can_vote: Optional[pulumi.Input[bool]] = None):
         """
-        :param pulumi.Input[Sequence[pulumi.Input['BranchPolicyMinReviewersSettingsScopeArgs']]] scopes: Controls which repositories and branches the policy will be enabled for. This block must be defined at least once.
+        :param pulumi.Input[Sequence[pulumi.Input['BranchPolicyMinReviewersSettingsScopeArgs']]] scopes: A `scope` block as defined below. Controls which repositories and branches the policy will be enabled for. This block must be defined at least once.
         :param pulumi.Input[bool] allow_completion_with_rejects_or_waits: Allow completion even if some reviewers vote to wait or reject. Defaults to `false`.
         :param pulumi.Input[bool] last_pusher_cannot_approve: Prohibit the most recent pusher from approving their own changes. Defaults to `false`.
         :param pulumi.Input[bool] on_last_iteration_require_vote: On last iteration require vote. Defaults to `false`.
         :param pulumi.Input[bool] on_push_reset_all_votes: When new changes are pushed reset all code reviewer votes. Defaults to `false`.
+               
+               > **Note:** If `on_push_reset_all_votes` is `true` then `on_push_reset_approved_votes` will be set to `true`. To enable `on_push_reset_approved_votes`, you need explicitly set `on_push_reset_all_votes` `false` or not configure.
         :param pulumi.Input[bool] on_push_reset_approved_votes: When new changes are pushed reset all approval votes (does not reset votes to reject or wait). Defaults to `false`.
         :param pulumi.Input[int] reviewer_count: The number of reviewers needed to approve.
         :param pulumi.Input[bool] submitter_can_vote: Allow requesters to approve their own changes. Defaults to `false`.
         """
         pulumi.set(__self__, "scopes", scopes)
         if allow_completion_with_rejects_or_waits is not None:
             pulumi.set(__self__, "allow_completion_with_rejects_or_waits", allow_completion_with_rejects_or_waits)
@@ -648,15 +654,15 @@
         if submitter_can_vote is not None:
             pulumi.set(__self__, "submitter_can_vote", submitter_can_vote)
 
     @property
     @pulumi.getter
     def scopes(self) -> pulumi.Input[Sequence[pulumi.Input['BranchPolicyMinReviewersSettingsScopeArgs']]]:
         """
-        Controls which repositories and branches the policy will be enabled for. This block must be defined at least once.
+        A `scope` block as defined below. Controls which repositories and branches the policy will be enabled for. This block must be defined at least once.
         """
         return pulumi.get(self, "scopes")
 
     @scopes.setter
     def scopes(self, value: pulumi.Input[Sequence[pulumi.Input['BranchPolicyMinReviewersSettingsScopeArgs']]]):
         pulumi.set(self, "scopes", value)
 
@@ -697,14 +703,16 @@
         pulumi.set(self, "on_last_iteration_require_vote", value)
 
     @property
     @pulumi.getter(name="onPushResetAllVotes")
     def on_push_reset_all_votes(self) -> Optional[pulumi.Input[bool]]:
         """
         When new changes are pushed reset all code reviewer votes. Defaults to `false`.
+
+        > **Note:** If `on_push_reset_all_votes` is `true` then `on_push_reset_approved_votes` will be set to `true`. To enable `on_push_reset_approved_votes`, you need explicitly set `on_push_reset_all_votes` `false` or not configure.
         """
         return pulumi.get(self, "on_push_reset_all_votes")
 
     @on_push_reset_all_votes.setter
     def on_push_reset_all_votes(self, value: Optional[pulumi.Input[bool]]):
         pulumi.set(self, "on_push_reset_all_votes", value)
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/_utilities.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/_utilities.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/agent/get_pool.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/agent/get_pool.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/agent/get_pools.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/agent/get_pools.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/agent/outputs.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/agent/outputs.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/agent/pool.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/agent/pool.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/agent/queue.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/agent/queue.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/area_permissions.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/tagging_permissions.py`

 * *Files 11% similar despite different names*

```diff
@@ -5,37 +5,41 @@
 import copy
 import warnings
 import pulumi
 import pulumi.runtime
 from typing import Any, Mapping, Optional, Sequence, Union, overload
 from . import _utilities
 
-__all__ = ['AreaPermissionsArgs', 'AreaPermissions']
+__all__ = ['TaggingPermissionsArgs', 'TaggingPermissions']
 
 @pulumi.input_type
-class AreaPermissionsArgs:
+class TaggingPermissionsArgs:
     def __init__(__self__, *,
                  permissions: pulumi.Input[Mapping[str, pulumi.Input[str]]],
                  principal: pulumi.Input[str],
-                 project_id: pulumi.Input[str],
-                 path: Optional[pulumi.Input[str]] = None,
+                 project_id: Optional[pulumi.Input[str]] = None,
                  replace: Optional[pulumi.Input[bool]] = None):
         """
-        The set of arguments for constructing a AreaPermissions resource.
+        The set of arguments for constructing a TaggingPermissions resource.
         :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available.
-        :param pulumi.Input[str] principal: The **group** principal to assign the permissions.
-        :param pulumi.Input[str] project_id: The ID of the project to assign the permissions.
-        :param pulumi.Input[str] path: The name of the branch to assign the permissions.
-        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`.
+        :param pulumi.Input[str] principal: The **group or user** principal to assign the permissions.
+        :param pulumi.Input[str] project_id: The ID of the project to assign the permissions. If omitted, organization wide permissions for tagging are managed.
+        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
+               
+               | Name               | Permission Description     |
+               | ------------------ | -------------------------- |
+               | Enumerate          | Enumerate tag definitions  |
+               | Create             | Create tag definition      |
+               | Update             | Update tag definition      |
+               | Delete             | Delete tag definition      |
         """
         pulumi.set(__self__, "permissions", permissions)
         pulumi.set(__self__, "principal", principal)
-        pulumi.set(__self__, "project_id", project_id)
-        if path is not None:
-            pulumi.set(__self__, "path", path)
+        if project_id is not None:
+            pulumi.set(__self__, "project_id", project_id)
         if replace is not None:
             pulumi.set(__self__, "replace", replace)
 
     @property
     @pulumi.getter
     def permissions(self) -> pulumi.Input[Mapping[str, pulumi.Input[str]]]:
         """
@@ -47,190 +51,179 @@
     def permissions(self, value: pulumi.Input[Mapping[str, pulumi.Input[str]]]):
         pulumi.set(self, "permissions", value)
 
     @property
     @pulumi.getter
     def principal(self) -> pulumi.Input[str]:
         """
-        The **group** principal to assign the permissions.
+        The **group or user** principal to assign the permissions.
         """
         return pulumi.get(self, "principal")
 
     @principal.setter
     def principal(self, value: pulumi.Input[str]):
         pulumi.set(self, "principal", value)
 
     @property
     @pulumi.getter(name="projectId")
-    def project_id(self) -> pulumi.Input[str]:
+    def project_id(self) -> Optional[pulumi.Input[str]]:
         """
-        The ID of the project to assign the permissions.
+        The ID of the project to assign the permissions. If omitted, organization wide permissions for tagging are managed.
         """
         return pulumi.get(self, "project_id")
 
     @project_id.setter
-    def project_id(self, value: pulumi.Input[str]):
+    def project_id(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "project_id", value)
 
     @property
     @pulumi.getter
-    def path(self) -> Optional[pulumi.Input[str]]:
-        """
-        The name of the branch to assign the permissions.
-        """
-        return pulumi.get(self, "path")
-
-    @path.setter
-    def path(self, value: Optional[pulumi.Input[str]]):
-        pulumi.set(self, "path", value)
-
-    @property
-    @pulumi.getter
     def replace(self) -> Optional[pulumi.Input[bool]]:
         """
-        Replace (`true`) or merge (`false`) the permissions. Default: `true`.
+        Replace (`true`) or merge (`false`) the permissions. Default: `true`
+
+        | Name               | Permission Description     |
+        | ------------------ | -------------------------- |
+        | Enumerate          | Enumerate tag definitions  |
+        | Create             | Create tag definition      |
+        | Update             | Update tag definition      |
+        | Delete             | Delete tag definition      |
         """
         return pulumi.get(self, "replace")
 
     @replace.setter
     def replace(self, value: Optional[pulumi.Input[bool]]):
         pulumi.set(self, "replace", value)
 
 
 @pulumi.input_type
-class _AreaPermissionsState:
+class _TaggingPermissionsState:
     def __init__(__self__, *,
-                 path: Optional[pulumi.Input[str]] = None,
                  permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
                  principal: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  replace: Optional[pulumi.Input[bool]] = None):
         """
-        Input properties used for looking up and filtering AreaPermissions resources.
-        :param pulumi.Input[str] path: The name of the branch to assign the permissions.
+        Input properties used for looking up and filtering TaggingPermissions resources.
         :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available.
-        :param pulumi.Input[str] principal: The **group** principal to assign the permissions.
-        :param pulumi.Input[str] project_id: The ID of the project to assign the permissions.
-        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`.
+        :param pulumi.Input[str] principal: The **group or user** principal to assign the permissions.
+        :param pulumi.Input[str] project_id: The ID of the project to assign the permissions. If omitted, organization wide permissions for tagging are managed.
+        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
+               
+               | Name               | Permission Description     |
+               | ------------------ | -------------------------- |
+               | Enumerate          | Enumerate tag definitions  |
+               | Create             | Create tag definition      |
+               | Update             | Update tag definition      |
+               | Delete             | Delete tag definition      |
         """
-        if path is not None:
-            pulumi.set(__self__, "path", path)
         if permissions is not None:
             pulumi.set(__self__, "permissions", permissions)
         if principal is not None:
             pulumi.set(__self__, "principal", principal)
         if project_id is not None:
             pulumi.set(__self__, "project_id", project_id)
         if replace is not None:
             pulumi.set(__self__, "replace", replace)
 
     @property
     @pulumi.getter
-    def path(self) -> Optional[pulumi.Input[str]]:
-        """
-        The name of the branch to assign the permissions.
-        """
-        return pulumi.get(self, "path")
-
-    @path.setter
-    def path(self, value: Optional[pulumi.Input[str]]):
-        pulumi.set(self, "path", value)
-
-    @property
-    @pulumi.getter
     def permissions(self) -> Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]:
         """
         the permissions to assign. The following permissions are available.
         """
         return pulumi.get(self, "permissions")
 
     @permissions.setter
     def permissions(self, value: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]):
         pulumi.set(self, "permissions", value)
 
     @property
     @pulumi.getter
     def principal(self) -> Optional[pulumi.Input[str]]:
         """
-        The **group** principal to assign the permissions.
+        The **group or user** principal to assign the permissions.
         """
         return pulumi.get(self, "principal")
 
     @principal.setter
     def principal(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "principal", value)
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> Optional[pulumi.Input[str]]:
         """
-        The ID of the project to assign the permissions.
+        The ID of the project to assign the permissions. If omitted, organization wide permissions for tagging are managed.
         """
         return pulumi.get(self, "project_id")
 
     @project_id.setter
     def project_id(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "project_id", value)
 
     @property
     @pulumi.getter
     def replace(self) -> Optional[pulumi.Input[bool]]:
         """
-        Replace (`true`) or merge (`false`) the permissions. Default: `true`.
+        Replace (`true`) or merge (`false`) the permissions. Default: `true`
+
+        | Name               | Permission Description     |
+        | ------------------ | -------------------------- |
+        | Enumerate          | Enumerate tag definitions  |
+        | Create             | Create tag definition      |
+        | Update             | Update tag definition      |
+        | Delete             | Delete tag definition      |
         """
         return pulumi.get(self, "replace")
 
     @replace.setter
     def replace(self, value: Optional[pulumi.Input[bool]]):
         pulumi.set(self, "replace", value)
 
 
-class AreaPermissions(pulumi.CustomResource):
+class TaggingPermissions(pulumi.CustomResource):
     @overload
     def __init__(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
-                 path: Optional[pulumi.Input[str]] = None,
                  permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
                  principal: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  replace: Optional[pulumi.Input[bool]] = None,
                  __props__=None):
         """
-        Manages permissions for an Area (Component)
-
-        > **Note** Permissions can be assigned to group principals and not to single user principals.
+        Manages permissions for tagging
 
         ## Permission levels
 
-        Permission for Areas within Azure DevOps can be applied on two different levels.
-        Those levels are reflected by specifying (or omitting) values for the arguments `project_id` and `path`.
+        Permissions for tagging within Azure DevOps can be applied only on Organizational and Project level.
+        The project level is reflected by specifying the argument `project_id`, otherwise the permissions are set on the organizational level.
 
         ## Example Usage
 
         ```python
         import pulumi
         import pulumi_azuredevops as azuredevops
 
         example = azuredevops.Project("example",
             work_item_template="Agile",
             version_control="Git",
             visibility="private",
             description="Managed by Terraform")
-        example_project_readers = azuredevops.get_group_output(project_id=example.id,
+        example_readers = azuredevops.get_group_output(project_id=example.id,
             name="Readers")
-        example_root_permissions = azuredevops.AreaPermissions("example-root-permissions",
+        example_permissions = azuredevops.TaggingPermissions("example-permissions",
             project_id=example.id,
-            principal=example_project_readers.id,
-            path="/",
+            principal=example_readers.id,
             permissions={
-                "CREATE_CHILDREN": "Deny",
-                "GENERIC_READ": "Allow",
-                "DELETE": "Deny",
-                "WORK_ITEM_READ": "Allow",
+                "Enumerate": "allow",
+                "Create": "allow",
+                "Update": "allow",
+                "Delete": "allow",
             })
         ```
         ## Relevant Links
 
         * [Azure DevOps Service REST API 6.0 - Security](https://docs.microsoft.com/en-us/rest/api/azure/devops/security/?view=azure-devops-rest-6.0)
 
         ## PAT Permissions Required
@@ -239,58 +232,61 @@
 
         ## Import
 
         The resource does not support import.
 
         :param str resource_name: The name of the resource.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[str] path: The name of the branch to assign the permissions.
         :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available.
-        :param pulumi.Input[str] principal: The **group** principal to assign the permissions.
-        :param pulumi.Input[str] project_id: The ID of the project to assign the permissions.
-        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`.
+        :param pulumi.Input[str] principal: The **group or user** principal to assign the permissions.
+        :param pulumi.Input[str] project_id: The ID of the project to assign the permissions. If omitted, organization wide permissions for tagging are managed.
+        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
+               
+               | Name               | Permission Description     |
+               | ------------------ | -------------------------- |
+               | Enumerate          | Enumerate tag definitions  |
+               | Create             | Create tag definition      |
+               | Update             | Update tag definition      |
+               | Delete             | Delete tag definition      |
         """
         ...
     @overload
     def __init__(__self__,
                  resource_name: str,
-                 args: AreaPermissionsArgs,
+                 args: TaggingPermissionsArgs,
                  opts: Optional[pulumi.ResourceOptions] = None):
         """
-        Manages permissions for an Area (Component)
-
-        > **Note** Permissions can be assigned to group principals and not to single user principals.
+        Manages permissions for tagging
 
         ## Permission levels
 
-        Permission for Areas within Azure DevOps can be applied on two different levels.
-        Those levels are reflected by specifying (or omitting) values for the arguments `project_id` and `path`.
+        Permissions for tagging within Azure DevOps can be applied only on Organizational and Project level.
+        The project level is reflected by specifying the argument `project_id`, otherwise the permissions are set on the organizational level.
 
         ## Example Usage
 
         ```python
         import pulumi
         import pulumi_azuredevops as azuredevops
 
         example = azuredevops.Project("example",
             work_item_template="Agile",
             version_control="Git",
             visibility="private",
             description="Managed by Terraform")
-        example_project_readers = azuredevops.get_group_output(project_id=example.id,
+        example_readers = azuredevops.get_group_output(project_id=example.id,
             name="Readers")
-        example_root_permissions = azuredevops.AreaPermissions("example-root-permissions",
+        example_permissions = azuredevops.TaggingPermissions("example-permissions",
             project_id=example.id,
-            principal=example_project_readers.id,
-            path="/",
+            principal=example_readers.id,
             permissions={
-                "CREATE_CHILDREN": "Deny",
-                "GENERIC_READ": "Allow",
-                "DELETE": "Deny",
-                "WORK_ITEM_READ": "Allow",
+                "Enumerate": "allow",
+                "Create": "allow",
+                "Update": "allow",
+                "Delete": "allow",
             })
         ```
         ## Relevant Links
 
         * [Azure DevOps Service REST API 6.0 - Security](https://docs.microsoft.com/en-us/rest/api/azure/devops/security/?view=azure-devops-rest-6.0)
 
         ## PAT Permissions Required
@@ -298,125 +294,124 @@
         - **Project & Team**: vso.security_manage - Grants the ability to read, write, and manage security permissions.
 
         ## Import
 
         The resource does not support import.
 
         :param str resource_name: The name of the resource.
-        :param AreaPermissionsArgs args: The arguments to use to populate this resource's properties.
+        :param TaggingPermissionsArgs args: The arguments to use to populate this resource's properties.
         :param pulumi.ResourceOptions opts: Options for the resource.
         """
         ...
     def __init__(__self__, resource_name: str, *args, **kwargs):
-        resource_args, opts = _utilities.get_resource_args_opts(AreaPermissionsArgs, pulumi.ResourceOptions, *args, **kwargs)
+        resource_args, opts = _utilities.get_resource_args_opts(TaggingPermissionsArgs, pulumi.ResourceOptions, *args, **kwargs)
         if resource_args is not None:
             __self__._internal_init(resource_name, opts, **resource_args.__dict__)
         else:
             __self__._internal_init(resource_name, *args, **kwargs)
 
     def _internal_init(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
-                 path: Optional[pulumi.Input[str]] = None,
                  permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
                  principal: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  replace: Optional[pulumi.Input[bool]] = None,
                  __props__=None):
         opts = pulumi.ResourceOptions.merge(_utilities.get_resource_opts_defaults(), opts)
         if not isinstance(opts, pulumi.ResourceOptions):
             raise TypeError('Expected resource options to be a ResourceOptions instance')
         if opts.id is None:
             if __props__ is not None:
                 raise TypeError('__props__ is only valid when passed in combination with a valid opts.id to get an existing resource')
-            __props__ = AreaPermissionsArgs.__new__(AreaPermissionsArgs)
+            __props__ = TaggingPermissionsArgs.__new__(TaggingPermissionsArgs)
 
-            __props__.__dict__["path"] = path
             if permissions is None and not opts.urn:
                 raise TypeError("Missing required property 'permissions'")
             __props__.__dict__["permissions"] = permissions
             if principal is None and not opts.urn:
                 raise TypeError("Missing required property 'principal'")
             __props__.__dict__["principal"] = principal
-            if project_id is None and not opts.urn:
-                raise TypeError("Missing required property 'project_id'")
             __props__.__dict__["project_id"] = project_id
             __props__.__dict__["replace"] = replace
-        super(AreaPermissions, __self__).__init__(
-            'azuredevops:index/areaPermissions:AreaPermissions',
+        super(TaggingPermissions, __self__).__init__(
+            'azuredevops:index/taggingPermissions:TaggingPermissions',
             resource_name,
             __props__,
             opts)
 
     @staticmethod
     def get(resource_name: str,
             id: pulumi.Input[str],
             opts: Optional[pulumi.ResourceOptions] = None,
-            path: Optional[pulumi.Input[str]] = None,
             permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
             principal: Optional[pulumi.Input[str]] = None,
             project_id: Optional[pulumi.Input[str]] = None,
-            replace: Optional[pulumi.Input[bool]] = None) -> 'AreaPermissions':
+            replace: Optional[pulumi.Input[bool]] = None) -> 'TaggingPermissions':
         """
-        Get an existing AreaPermissions resource's state with the given name, id, and optional extra
+        Get an existing TaggingPermissions resource's state with the given name, id, and optional extra
         properties used to qualify the lookup.
 
         :param str resource_name: The unique name of the resulting resource.
         :param pulumi.Input[str] id: The unique provider ID of the resource to lookup.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[str] path: The name of the branch to assign the permissions.
         :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available.
-        :param pulumi.Input[str] principal: The **group** principal to assign the permissions.
-        :param pulumi.Input[str] project_id: The ID of the project to assign the permissions.
-        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`.
+        :param pulumi.Input[str] principal: The **group or user** principal to assign the permissions.
+        :param pulumi.Input[str] project_id: The ID of the project to assign the permissions. If omitted, organization wide permissions for tagging are managed.
+        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
+               
+               | Name               | Permission Description     |
+               | ------------------ | -------------------------- |
+               | Enumerate          | Enumerate tag definitions  |
+               | Create             | Create tag definition      |
+               | Update             | Update tag definition      |
+               | Delete             | Delete tag definition      |
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
 
-        __props__ = _AreaPermissionsState.__new__(_AreaPermissionsState)
+        __props__ = _TaggingPermissionsState.__new__(_TaggingPermissionsState)
 
-        __props__.__dict__["path"] = path
         __props__.__dict__["permissions"] = permissions
         __props__.__dict__["principal"] = principal
         __props__.__dict__["project_id"] = project_id
         __props__.__dict__["replace"] = replace
-        return AreaPermissions(resource_name, opts=opts, __props__=__props__)
-
-    @property
-    @pulumi.getter
-    def path(self) -> pulumi.Output[Optional[str]]:
-        """
-        The name of the branch to assign the permissions.
-        """
-        return pulumi.get(self, "path")
+        return TaggingPermissions(resource_name, opts=opts, __props__=__props__)
 
     @property
     @pulumi.getter
     def permissions(self) -> pulumi.Output[Mapping[str, str]]:
         """
         the permissions to assign. The following permissions are available.
         """
         return pulumi.get(self, "permissions")
 
     @property
     @pulumi.getter
     def principal(self) -> pulumi.Output[str]:
         """
-        The **group** principal to assign the permissions.
+        The **group or user** principal to assign the permissions.
         """
         return pulumi.get(self, "principal")
 
     @property
     @pulumi.getter(name="projectId")
-    def project_id(self) -> pulumi.Output[str]:
+    def project_id(self) -> pulumi.Output[Optional[str]]:
         """
-        The ID of the project to assign the permissions.
+        The ID of the project to assign the permissions. If omitted, organization wide permissions for tagging are managed.
         """
         return pulumi.get(self, "project_id")
 
     @property
     @pulumi.getter
     def replace(self) -> pulumi.Output[Optional[bool]]:
         """
-        Replace (`true`) or merge (`false`) the permissions. Default: `true`.
+        Replace (`true`) or merge (`false`) the permissions. Default: `true`
+
+        | Name               | Permission Description     |
+        | ------------------ | -------------------------- |
+        | Enumerate          | Enumerate tag definitions  |
+        | Create             | Create tag definition      |
+        | Update             | Update tag definition      |
+        | Delete             | Delete tag definition      |
         """
         return pulumi.get(self, "replace")
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/branch_policy_auto_reviewers.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/branch_policy_auto_reviewers.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/branch_policy_build_validation.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/branch_policy_build_validation.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/branch_policy_comment_resolution.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/branch_policy_comment_resolution.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/branch_policy_merge_types.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/branch_policy_merge_types.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/branch_policy_min_reviewers.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/policy/branch_policy_min_reviewers.py`

 * *Files 4% similar despite different names*

```diff
@@ -3,15 +3,15 @@
 # *** Do not edit by hand unless you're certain you know what you are doing! ***
 
 import copy
 import warnings
 import pulumi
 import pulumi.runtime
 from typing import Any, Mapping, Optional, Sequence, Union, overload
-from . import _utilities
+from .. import _utilities
 from . import outputs
 from ._inputs import *
 
 __all__ = ['BranchPolicyMinReviewersArgs', 'BranchPolicyMinReviewers']
 
 @pulumi.input_type
 class BranchPolicyMinReviewersArgs:
@@ -19,15 +19,15 @@
                  project_id: pulumi.Input[str],
                  settings: pulumi.Input['BranchPolicyMinReviewersSettingsArgs'],
                  blocking: Optional[pulumi.Input[bool]] = None,
                  enabled: Optional[pulumi.Input[bool]] = None):
         """
         The set of arguments for constructing a BranchPolicyMinReviewers resource.
         :param pulumi.Input[str] project_id: The ID of the project in which the policy will be created.
-        :param pulumi.Input['BranchPolicyMinReviewersSettingsArgs'] settings: Configuration for the policy. This block must be defined exactly once.
+        :param pulumi.Input['BranchPolicyMinReviewersSettingsArgs'] settings: A `settings` block as defined below.. This block must be defined exactly once.
         :param pulumi.Input[bool] blocking: A flag indicating if the policy should be blocking. Defaults to `true`.
         :param pulumi.Input[bool] enabled: A flag indicating if the policy should be enabled. Defaults to `true`.
         """
         pulumi.set(__self__, "project_id", project_id)
         pulumi.set(__self__, "settings", settings)
         if blocking is not None:
             pulumi.set(__self__, "blocking", blocking)
@@ -46,15 +46,15 @@
     def project_id(self, value: pulumi.Input[str]):
         pulumi.set(self, "project_id", value)
 
     @property
     @pulumi.getter
     def settings(self) -> pulumi.Input['BranchPolicyMinReviewersSettingsArgs']:
         """
-        Configuration for the policy. This block must be defined exactly once.
+        A `settings` block as defined below.. This block must be defined exactly once.
         """
         return pulumi.get(self, "settings")
 
     @settings.setter
     def settings(self, value: pulumi.Input['BranchPolicyMinReviewersSettingsArgs']):
         pulumi.set(self, "settings", value)
 
@@ -91,15 +91,15 @@
                  project_id: Optional[pulumi.Input[str]] = None,
                  settings: Optional[pulumi.Input['BranchPolicyMinReviewersSettingsArgs']] = None):
         """
         Input properties used for looking up and filtering BranchPolicyMinReviewers resources.
         :param pulumi.Input[bool] blocking: A flag indicating if the policy should be blocking. Defaults to `true`.
         :param pulumi.Input[bool] enabled: A flag indicating if the policy should be enabled. Defaults to `true`.
         :param pulumi.Input[str] project_id: The ID of the project in which the policy will be created.
-        :param pulumi.Input['BranchPolicyMinReviewersSettingsArgs'] settings: Configuration for the policy. This block must be defined exactly once.
+        :param pulumi.Input['BranchPolicyMinReviewersSettingsArgs'] settings: A `settings` block as defined below.. This block must be defined exactly once.
         """
         if blocking is not None:
             pulumi.set(__self__, "blocking", blocking)
         if enabled is not None:
             pulumi.set(__self__, "enabled", enabled)
         if project_id is not None:
             pulumi.set(__self__, "project_id", project_id)
@@ -142,24 +142,29 @@
     def project_id(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "project_id", value)
 
     @property
     @pulumi.getter
     def settings(self) -> Optional[pulumi.Input['BranchPolicyMinReviewersSettingsArgs']]:
         """
-        Configuration for the policy. This block must be defined exactly once.
+        A `settings` block as defined below.. This block must be defined exactly once.
         """
         return pulumi.get(self, "settings")
 
     @settings.setter
     def settings(self, value: Optional[pulumi.Input['BranchPolicyMinReviewersSettingsArgs']]):
         pulumi.set(self, "settings", value)
 
 
+warnings.warn("""azuredevops.policy.BranchPolicyMinReviewers has been deprecated in favor of azuredevops.BranchPolicyMinReviewers""", DeprecationWarning)
+
+
 class BranchPolicyMinReviewers(pulumi.CustomResource):
+    warnings.warn("""azuredevops.policy.BranchPolicyMinReviewers has been deprecated in favor of azuredevops.BranchPolicyMinReviewers""", DeprecationWarning)
+
     @overload
     def __init__(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
                  blocking: Optional[pulumi.Input[bool]] = None,
                  enabled: Optional[pulumi.Input[bool]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
@@ -213,23 +218,23 @@
         - [Azure DevOps Service REST API 6.0 - Policy Configurations](https://docs.microsoft.com/en-us/rest/api/azure/devops/policy/configurations/create?view=azure-devops-rest-6.0)
 
         ## Import
 
         Azure DevOps Branch Policies can be imported using the project ID and policy configuration ID
 
         ```sh
-         $ pulumi import azuredevops:index/branchPolicyMinReviewers:BranchPolicyMinReviewers example 00000000-0000-0000-0000-000000000000/0
+         $ pulumi import azuredevops:Policy/branchPolicyMinReviewers:BranchPolicyMinReviewers example 00000000-0000-0000-0000-000000000000/0
         ```
 
         :param str resource_name: The name of the resource.
         :param pulumi.ResourceOptions opts: Options for the resource.
         :param pulumi.Input[bool] blocking: A flag indicating if the policy should be blocking. Defaults to `true`.
         :param pulumi.Input[bool] enabled: A flag indicating if the policy should be enabled. Defaults to `true`.
         :param pulumi.Input[str] project_id: The ID of the project in which the policy will be created.
-        :param pulumi.Input[pulumi.InputType['BranchPolicyMinReviewersSettingsArgs']] settings: Configuration for the policy. This block must be defined exactly once.
+        :param pulumi.Input[pulumi.InputType['BranchPolicyMinReviewersSettingsArgs']] settings: A `settings` block as defined below.. This block must be defined exactly once.
         """
         ...
     @overload
     def __init__(__self__,
                  resource_name: str,
                  args: BranchPolicyMinReviewersArgs,
                  opts: Optional[pulumi.ResourceOptions] = None):
@@ -281,15 +286,15 @@
         - [Azure DevOps Service REST API 6.0 - Policy Configurations](https://docs.microsoft.com/en-us/rest/api/azure/devops/policy/configurations/create?view=azure-devops-rest-6.0)
 
         ## Import
 
         Azure DevOps Branch Policies can be imported using the project ID and policy configuration ID
 
         ```sh
-         $ pulumi import azuredevops:index/branchPolicyMinReviewers:BranchPolicyMinReviewers example 00000000-0000-0000-0000-000000000000/0
+         $ pulumi import azuredevops:Policy/branchPolicyMinReviewers:BranchPolicyMinReviewers example 00000000-0000-0000-0000-000000000000/0
         ```
 
         :param str resource_name: The name of the resource.
         :param BranchPolicyMinReviewersArgs args: The arguments to use to populate this resource's properties.
         :param pulumi.ResourceOptions opts: Options for the resource.
         """
         ...
@@ -304,14 +309,15 @@
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
                  blocking: Optional[pulumi.Input[bool]] = None,
                  enabled: Optional[pulumi.Input[bool]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  settings: Optional[pulumi.Input[pulumi.InputType['BranchPolicyMinReviewersSettingsArgs']]] = None,
                  __props__=None):
+        pulumi.log.warn("""BranchPolicyMinReviewers is deprecated: azuredevops.policy.BranchPolicyMinReviewers has been deprecated in favor of azuredevops.BranchPolicyMinReviewers""")
         opts = pulumi.ResourceOptions.merge(_utilities.get_resource_opts_defaults(), opts)
         if not isinstance(opts, pulumi.ResourceOptions):
             raise TypeError('Expected resource options to be a ResourceOptions instance')
         if opts.id is None:
             if __props__ is not None:
                 raise TypeError('__props__ is only valid when passed in combination with a valid opts.id to get an existing resource')
             __props__ = BranchPolicyMinReviewersArgs.__new__(BranchPolicyMinReviewersArgs)
@@ -320,18 +326,16 @@
             __props__.__dict__["enabled"] = enabled
             if project_id is None and not opts.urn:
                 raise TypeError("Missing required property 'project_id'")
             __props__.__dict__["project_id"] = project_id
             if settings is None and not opts.urn:
                 raise TypeError("Missing required property 'settings'")
             __props__.__dict__["settings"] = settings
-        alias_opts = pulumi.ResourceOptions(aliases=[pulumi.Alias(type_="azuredevops:Policy/branchPolicyMinReviewers:BranchPolicyMinReviewers")])
-        opts = pulumi.ResourceOptions.merge(opts, alias_opts)
         super(BranchPolicyMinReviewers, __self__).__init__(
-            'azuredevops:index/branchPolicyMinReviewers:BranchPolicyMinReviewers',
+            'azuredevops:Policy/branchPolicyMinReviewers:BranchPolicyMinReviewers',
             resource_name,
             __props__,
             opts)
 
     @staticmethod
     def get(resource_name: str,
             id: pulumi.Input[str],
@@ -346,15 +350,15 @@
 
         :param str resource_name: The unique name of the resulting resource.
         :param pulumi.Input[str] id: The unique provider ID of the resource to lookup.
         :param pulumi.ResourceOptions opts: Options for the resource.
         :param pulumi.Input[bool] blocking: A flag indicating if the policy should be blocking. Defaults to `true`.
         :param pulumi.Input[bool] enabled: A flag indicating if the policy should be enabled. Defaults to `true`.
         :param pulumi.Input[str] project_id: The ID of the project in which the policy will be created.
-        :param pulumi.Input[pulumi.InputType['BranchPolicyMinReviewersSettingsArgs']] settings: Configuration for the policy. This block must be defined exactly once.
+        :param pulumi.Input[pulumi.InputType['BranchPolicyMinReviewersSettingsArgs']] settings: A `settings` block as defined below.. This block must be defined exactly once.
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
 
         __props__ = _BranchPolicyMinReviewersState.__new__(_BranchPolicyMinReviewersState)
 
         __props__.__dict__["blocking"] = blocking
         __props__.__dict__["enabled"] = enabled
@@ -386,11 +390,11 @@
         """
         return pulumi.get(self, "project_id")
 
     @property
     @pulumi.getter
     def settings(self) -> pulumi.Output['outputs.BranchPolicyMinReviewersSettings']:
         """
-        Configuration for the policy. This block must be defined exactly once.
+        A `settings` block as defined below.. This block must be defined exactly once.
         """
         return pulumi.get(self, "settings")
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/branch_policy_status_check.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/branch_policy_status_check.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/branch_policy_work_item_linking.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/branch_policy_work_item_linking.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/build/_inputs.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/build/_inputs.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/build/build_definition.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/build/build_definition.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/build/outputs.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/build/outputs.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/build_definition.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/build_definition.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/build_definition_permissions.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/servicehook_permissions.py`

 * *Files 18% similar despite different names*

```diff
@@ -5,52 +5,45 @@
 import copy
 import warnings
 import pulumi
 import pulumi.runtime
 from typing import Any, Mapping, Optional, Sequence, Union, overload
 from . import _utilities
 
-__all__ = ['BuildDefinitionPermissionsArgs', 'BuildDefinitionPermissions']
+__all__ = ['ServicehookPermissionsArgs', 'ServicehookPermissions']
 
 @pulumi.input_type
-class BuildDefinitionPermissionsArgs:
+class ServicehookPermissionsArgs:
     def __init__(__self__, *,
-                 build_definition_id: pulumi.Input[str],
                  permissions: pulumi.Input[Mapping[str, pulumi.Input[str]]],
                  principal: pulumi.Input[str],
-                 project_id: pulumi.Input[str],
+                 project_id: Optional[pulumi.Input[str]] = None,
                  replace: Optional[pulumi.Input[bool]] = None):
         """
-        The set of arguments for constructing a BuildDefinitionPermissions resource.
-        :param pulumi.Input[str] build_definition_id: The id of the build definition to assign the permissions.
+        The set of arguments for constructing a ServicehookPermissions resource.
         :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available.
         :param pulumi.Input[str] principal: The **group** principal to assign the permissions.
-        :param pulumi.Input[str] project_id: The ID of the project to assign the permissions.
-        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`.
+        :param pulumi.Input[str] project_id: The ID of the project.
+        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
+               
+               | Name               | Permission Description   |
+               | ------------------ | ------------------------ |
+               | ViewSubscriptions  | View Subscriptions       |
+               | EditSubscriptions  | Edit Subscription        |
+               | DeleteSubscriptions| Delete Subscriptions     |
+               | PublishEvents      | Publish Events           |
         """
-        pulumi.set(__self__, "build_definition_id", build_definition_id)
         pulumi.set(__self__, "permissions", permissions)
         pulumi.set(__self__, "principal", principal)
-        pulumi.set(__self__, "project_id", project_id)
+        if project_id is not None:
+            pulumi.set(__self__, "project_id", project_id)
         if replace is not None:
             pulumi.set(__self__, "replace", replace)
 
     @property
-    @pulumi.getter(name="buildDefinitionId")
-    def build_definition_id(self) -> pulumi.Input[str]:
-        """
-        The id of the build definition to assign the permissions.
-        """
-        return pulumi.get(self, "build_definition_id")
-
-    @build_definition_id.setter
-    def build_definition_id(self, value: pulumi.Input[str]):
-        pulumi.set(self, "build_definition_id", value)
-
-    @property
     @pulumi.getter
     def permissions(self) -> pulumi.Input[Mapping[str, pulumi.Input[str]]]:
         """
         the permissions to assign. The following permissions are available.
         """
         return pulumi.get(self, "permissions")
 
@@ -68,77 +61,75 @@
 
     @principal.setter
     def principal(self, value: pulumi.Input[str]):
         pulumi.set(self, "principal", value)
 
     @property
     @pulumi.getter(name="projectId")
-    def project_id(self) -> pulumi.Input[str]:
+    def project_id(self) -> Optional[pulumi.Input[str]]:
         """
-        The ID of the project to assign the permissions.
+        The ID of the project.
         """
         return pulumi.get(self, "project_id")
 
     @project_id.setter
-    def project_id(self, value: pulumi.Input[str]):
+    def project_id(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "project_id", value)
 
     @property
     @pulumi.getter
     def replace(self) -> Optional[pulumi.Input[bool]]:
         """
-        Replace (`true`) or merge (`false`) the permissions. Default: `true`.
+        Replace (`true`) or merge (`false`) the permissions. Default: `true`
+
+        | Name               | Permission Description   |
+        | ------------------ | ------------------------ |
+        | ViewSubscriptions  | View Subscriptions       |
+        | EditSubscriptions  | Edit Subscription        |
+        | DeleteSubscriptions| Delete Subscriptions     |
+        | PublishEvents      | Publish Events           |
         """
         return pulumi.get(self, "replace")
 
     @replace.setter
     def replace(self, value: Optional[pulumi.Input[bool]]):
         pulumi.set(self, "replace", value)
 
 
 @pulumi.input_type
-class _BuildDefinitionPermissionsState:
+class _ServicehookPermissionsState:
     def __init__(__self__, *,
-                 build_definition_id: Optional[pulumi.Input[str]] = None,
                  permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
                  principal: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  replace: Optional[pulumi.Input[bool]] = None):
         """
-        Input properties used for looking up and filtering BuildDefinitionPermissions resources.
-        :param pulumi.Input[str] build_definition_id: The id of the build definition to assign the permissions.
+        Input properties used for looking up and filtering ServicehookPermissions resources.
         :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available.
         :param pulumi.Input[str] principal: The **group** principal to assign the permissions.
-        :param pulumi.Input[str] project_id: The ID of the project to assign the permissions.
-        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`.
+        :param pulumi.Input[str] project_id: The ID of the project.
+        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
+               
+               | Name               | Permission Description   |
+               | ------------------ | ------------------------ |
+               | ViewSubscriptions  | View Subscriptions       |
+               | EditSubscriptions  | Edit Subscription        |
+               | DeleteSubscriptions| Delete Subscriptions     |
+               | PublishEvents      | Publish Events           |
         """
-        if build_definition_id is not None:
-            pulumi.set(__self__, "build_definition_id", build_definition_id)
         if permissions is not None:
             pulumi.set(__self__, "permissions", permissions)
         if principal is not None:
             pulumi.set(__self__, "principal", principal)
         if project_id is not None:
             pulumi.set(__self__, "project_id", project_id)
         if replace is not None:
             pulumi.set(__self__, "replace", replace)
 
     @property
-    @pulumi.getter(name="buildDefinitionId")
-    def build_definition_id(self) -> Optional[pulumi.Input[str]]:
-        """
-        The id of the build definition to assign the permissions.
-        """
-        return pulumi.get(self, "build_definition_id")
-
-    @build_definition_id.setter
-    def build_definition_id(self, value: Optional[pulumi.Input[str]]):
-        pulumi.set(self, "build_definition_id", value)
-
-    @property
     @pulumi.getter
     def permissions(self) -> Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]:
         """
         the permissions to assign. The following permissions are available.
         """
         return pulumi.get(self, "permissions")
 
@@ -158,90 +149,81 @@
     def principal(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "principal", value)
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> Optional[pulumi.Input[str]]:
         """
-        The ID of the project to assign the permissions.
+        The ID of the project.
         """
         return pulumi.get(self, "project_id")
 
     @project_id.setter
     def project_id(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "project_id", value)
 
     @property
     @pulumi.getter
     def replace(self) -> Optional[pulumi.Input[bool]]:
         """
-        Replace (`true`) or merge (`false`) the permissions. Default: `true`.
+        Replace (`true`) or merge (`false`) the permissions. Default: `true`
+
+        | Name               | Permission Description   |
+        | ------------------ | ------------------------ |
+        | ViewSubscriptions  | View Subscriptions       |
+        | EditSubscriptions  | Edit Subscription        |
+        | DeleteSubscriptions| Delete Subscriptions     |
+        | PublishEvents      | Publish Events           |
         """
         return pulumi.get(self, "replace")
 
     @replace.setter
     def replace(self, value: Optional[pulumi.Input[bool]]):
         pulumi.set(self, "replace", value)
 
 
-class BuildDefinitionPermissions(pulumi.CustomResource):
+class ServicehookPermissions(pulumi.CustomResource):
     @overload
     def __init__(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
-                 build_definition_id: Optional[pulumi.Input[str]] = None,
                  permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
                  principal: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  replace: Optional[pulumi.Input[bool]] = None,
                  __props__=None):
         """
-        Manages permissions for a Build Definition
+        Manages permissions for service hooks
+
+        ## Permission levels
 
-        > **Note** Permissions can be assigned to group principals and not to single user principals.
+        Permissions for service hooks within Azure DevOps can be applied on the Organizational level or, if the optional attribute `project_id` is specified, on Project level.
+        Those levels are reflected by specifying (or omitting) values for the argument `project_id`.
 
         ## Example Usage
 
         ```python
         import pulumi
         import pulumi_azuredevops as azuredevops
 
-        example_project = azuredevops.Project("exampleProject",
+        example = azuredevops.Project("example",
             work_item_template="Agile",
             version_control="Git",
             visibility="private",
             description="Managed by Terraform")
-        example_readers = azuredevops.get_group_output(project_id=example_project.id,
+        example_readers = azuredevops.get_group_output(project_id=example.id,
             name="Readers")
-        example_git = azuredevops.Git("exampleGit",
-            project_id=example_project.id,
-            initialization=azuredevops.GitInitializationArgs(
-                init_type="Clean",
-            ))
-        example_build_definition = azuredevops.BuildDefinition("exampleBuildDefinition",
-            project_id=example_project.id,
-            path="\\\\ExampleFolder",
-            ci_trigger=azuredevops.BuildDefinitionCiTriggerArgs(
-                use_yaml=True,
-            ),
-            repository=azuredevops.BuildDefinitionRepositoryArgs(
-                repo_type="TfsGit",
-                repo_id=example_git.id,
-                branch_name=example_git.default_branch,
-                yml_path="azure-pipelines.yml",
-            ))
-        example_build_definition_permissions = azuredevops.BuildDefinitionPermissions("exampleBuildDefinitionPermissions",
-            project_id=example_project.id,
+        example_permissions = azuredevops.ServicehookPermissions("example-permissions",
+            project_id=example.id,
             principal=example_readers.id,
-            build_definition_id=example_build_definition.id,
             permissions={
-                "ViewBuilds": "Allow",
-                "EditBuildQuality": "Deny",
-                "DeleteBuilds": "Deny",
-                "StopBuilds": "Allow",
+                "ViewSubscriptions": "allow",
+                "EditSubscriptions": "allow",
+                "DeleteSubscriptions": "allow",
+                "PublishEvents": "allow",
             })
         ```
         ## Relevant Links
 
         * [Azure DevOps Service REST API 6.0 - Security](https://docs.microsoft.com/en-us/rest/api/azure/devops/security/?view=azure-devops-rest-6.0)
 
         ## PAT Permissions Required
@@ -250,70 +232,61 @@
 
         ## Import
 
         The resource does not support import.
 
         :param str resource_name: The name of the resource.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[str] build_definition_id: The id of the build definition to assign the permissions.
         :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available.
         :param pulumi.Input[str] principal: The **group** principal to assign the permissions.
-        :param pulumi.Input[str] project_id: The ID of the project to assign the permissions.
-        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`.
+        :param pulumi.Input[str] project_id: The ID of the project.
+        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
+               
+               | Name               | Permission Description   |
+               | ------------------ | ------------------------ |
+               | ViewSubscriptions  | View Subscriptions       |
+               | EditSubscriptions  | Edit Subscription        |
+               | DeleteSubscriptions| Delete Subscriptions     |
+               | PublishEvents      | Publish Events           |
         """
         ...
     @overload
     def __init__(__self__,
                  resource_name: str,
-                 args: BuildDefinitionPermissionsArgs,
+                 args: ServicehookPermissionsArgs,
                  opts: Optional[pulumi.ResourceOptions] = None):
         """
-        Manages permissions for a Build Definition
+        Manages permissions for service hooks
 
-        > **Note** Permissions can be assigned to group principals and not to single user principals.
+        ## Permission levels
+
+        Permissions for service hooks within Azure DevOps can be applied on the Organizational level or, if the optional attribute `project_id` is specified, on Project level.
+        Those levels are reflected by specifying (or omitting) values for the argument `project_id`.
 
         ## Example Usage
 
         ```python
         import pulumi
         import pulumi_azuredevops as azuredevops
 
-        example_project = azuredevops.Project("exampleProject",
+        example = azuredevops.Project("example",
             work_item_template="Agile",
             version_control="Git",
             visibility="private",
             description="Managed by Terraform")
-        example_readers = azuredevops.get_group_output(project_id=example_project.id,
+        example_readers = azuredevops.get_group_output(project_id=example.id,
             name="Readers")
-        example_git = azuredevops.Git("exampleGit",
-            project_id=example_project.id,
-            initialization=azuredevops.GitInitializationArgs(
-                init_type="Clean",
-            ))
-        example_build_definition = azuredevops.BuildDefinition("exampleBuildDefinition",
-            project_id=example_project.id,
-            path="\\\\ExampleFolder",
-            ci_trigger=azuredevops.BuildDefinitionCiTriggerArgs(
-                use_yaml=True,
-            ),
-            repository=azuredevops.BuildDefinitionRepositoryArgs(
-                repo_type="TfsGit",
-                repo_id=example_git.id,
-                branch_name=example_git.default_branch,
-                yml_path="azure-pipelines.yml",
-            ))
-        example_build_definition_permissions = azuredevops.BuildDefinitionPermissions("exampleBuildDefinitionPermissions",
-            project_id=example_project.id,
+        example_permissions = azuredevops.ServicehookPermissions("example-permissions",
+            project_id=example.id,
             principal=example_readers.id,
-            build_definition_id=example_build_definition.id,
             permissions={
-                "ViewBuilds": "Allow",
-                "EditBuildQuality": "Deny",
-                "DeleteBuilds": "Deny",
-                "StopBuilds": "Allow",
+                "ViewSubscriptions": "allow",
+                "EditSubscriptions": "allow",
+                "DeleteSubscriptions": "allow",
+                "PublishEvents": "allow",
             })
         ```
         ## Relevant Links
 
         * [Azure DevOps Service REST API 6.0 - Security](https://docs.microsoft.com/en-us/rest/api/azure/devops/security/?view=azure-devops-rest-6.0)
 
         ## PAT Permissions Required
@@ -321,101 +294,91 @@
         - **Project & Team**: vso.security_manage - Grants the ability to read, write, and manage security permissions.
 
         ## Import
 
         The resource does not support import.
 
         :param str resource_name: The name of the resource.
-        :param BuildDefinitionPermissionsArgs args: The arguments to use to populate this resource's properties.
+        :param ServicehookPermissionsArgs args: The arguments to use to populate this resource's properties.
         :param pulumi.ResourceOptions opts: Options for the resource.
         """
         ...
     def __init__(__self__, resource_name: str, *args, **kwargs):
-        resource_args, opts = _utilities.get_resource_args_opts(BuildDefinitionPermissionsArgs, pulumi.ResourceOptions, *args, **kwargs)
+        resource_args, opts = _utilities.get_resource_args_opts(ServicehookPermissionsArgs, pulumi.ResourceOptions, *args, **kwargs)
         if resource_args is not None:
             __self__._internal_init(resource_name, opts, **resource_args.__dict__)
         else:
             __self__._internal_init(resource_name, *args, **kwargs)
 
     def _internal_init(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
-                 build_definition_id: Optional[pulumi.Input[str]] = None,
                  permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
                  principal: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  replace: Optional[pulumi.Input[bool]] = None,
                  __props__=None):
         opts = pulumi.ResourceOptions.merge(_utilities.get_resource_opts_defaults(), opts)
         if not isinstance(opts, pulumi.ResourceOptions):
             raise TypeError('Expected resource options to be a ResourceOptions instance')
         if opts.id is None:
             if __props__ is not None:
                 raise TypeError('__props__ is only valid when passed in combination with a valid opts.id to get an existing resource')
-            __props__ = BuildDefinitionPermissionsArgs.__new__(BuildDefinitionPermissionsArgs)
+            __props__ = ServicehookPermissionsArgs.__new__(ServicehookPermissionsArgs)
 
-            if build_definition_id is None and not opts.urn:
-                raise TypeError("Missing required property 'build_definition_id'")
-            __props__.__dict__["build_definition_id"] = build_definition_id
             if permissions is None and not opts.urn:
                 raise TypeError("Missing required property 'permissions'")
             __props__.__dict__["permissions"] = permissions
             if principal is None and not opts.urn:
                 raise TypeError("Missing required property 'principal'")
             __props__.__dict__["principal"] = principal
-            if project_id is None and not opts.urn:
-                raise TypeError("Missing required property 'project_id'")
             __props__.__dict__["project_id"] = project_id
             __props__.__dict__["replace"] = replace
-        super(BuildDefinitionPermissions, __self__).__init__(
-            'azuredevops:index/buildDefinitionPermissions:BuildDefinitionPermissions',
+        super(ServicehookPermissions, __self__).__init__(
+            'azuredevops:index/servicehookPermissions:ServicehookPermissions',
             resource_name,
             __props__,
             opts)
 
     @staticmethod
     def get(resource_name: str,
             id: pulumi.Input[str],
             opts: Optional[pulumi.ResourceOptions] = None,
-            build_definition_id: Optional[pulumi.Input[str]] = None,
             permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
             principal: Optional[pulumi.Input[str]] = None,
             project_id: Optional[pulumi.Input[str]] = None,
-            replace: Optional[pulumi.Input[bool]] = None) -> 'BuildDefinitionPermissions':
+            replace: Optional[pulumi.Input[bool]] = None) -> 'ServicehookPermissions':
         """
-        Get an existing BuildDefinitionPermissions resource's state with the given name, id, and optional extra
+        Get an existing ServicehookPermissions resource's state with the given name, id, and optional extra
         properties used to qualify the lookup.
 
         :param str resource_name: The unique name of the resulting resource.
         :param pulumi.Input[str] id: The unique provider ID of the resource to lookup.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[str] build_definition_id: The id of the build definition to assign the permissions.
         :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available.
         :param pulumi.Input[str] principal: The **group** principal to assign the permissions.
-        :param pulumi.Input[str] project_id: The ID of the project to assign the permissions.
-        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`.
+        :param pulumi.Input[str] project_id: The ID of the project.
+        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
+               
+               | Name               | Permission Description   |
+               | ------------------ | ------------------------ |
+               | ViewSubscriptions  | View Subscriptions       |
+               | EditSubscriptions  | Edit Subscription        |
+               | DeleteSubscriptions| Delete Subscriptions     |
+               | PublishEvents      | Publish Events           |
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
 
-        __props__ = _BuildDefinitionPermissionsState.__new__(_BuildDefinitionPermissionsState)
+        __props__ = _ServicehookPermissionsState.__new__(_ServicehookPermissionsState)
 
-        __props__.__dict__["build_definition_id"] = build_definition_id
         __props__.__dict__["permissions"] = permissions
         __props__.__dict__["principal"] = principal
         __props__.__dict__["project_id"] = project_id
         __props__.__dict__["replace"] = replace
-        return BuildDefinitionPermissions(resource_name, opts=opts, __props__=__props__)
-
-    @property
-    @pulumi.getter(name="buildDefinitionId")
-    def build_definition_id(self) -> pulumi.Output[str]:
-        """
-        The id of the build definition to assign the permissions.
-        """
-        return pulumi.get(self, "build_definition_id")
+        return ServicehookPermissions(resource_name, opts=opts, __props__=__props__)
 
     @property
     @pulumi.getter
     def permissions(self) -> pulumi.Output[Mapping[str, str]]:
         """
         the permissions to assign. The following permissions are available.
         """
@@ -427,21 +390,28 @@
         """
         The **group** principal to assign the permissions.
         """
         return pulumi.get(self, "principal")
 
     @property
     @pulumi.getter(name="projectId")
-    def project_id(self) -> pulumi.Output[str]:
+    def project_id(self) -> pulumi.Output[Optional[str]]:
         """
-        The ID of the project to assign the permissions.
+        The ID of the project.
         """
         return pulumi.get(self, "project_id")
 
     @property
     @pulumi.getter
     def replace(self) -> pulumi.Output[Optional[bool]]:
         """
-        Replace (`true`) or merge (`false`) the permissions. Default: `true`.
+        Replace (`true`) or merge (`false`) the permissions. Default: `true`
+
+        | Name               | Permission Description   |
+        | ------------------ | ------------------------ |
+        | ViewSubscriptions  | View Subscriptions       |
+        | EditSubscriptions  | Edit Subscription        |
+        | DeleteSubscriptions| Delete Subscriptions     |
+        | PublishEvents      | Publish Events           |
         """
         return pulumi.get(self, "replace")
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/build_folder.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/build_folder.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/build_folder_permissions.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/iterative_permissions.py`

 * *Files 20% similar despite different names*

```diff
@@ -5,53 +5,49 @@
 import copy
 import warnings
 import pulumi
 import pulumi.runtime
 from typing import Any, Mapping, Optional, Sequence, Union, overload
 from . import _utilities
 
-__all__ = ['BuildFolderPermissionsArgs', 'BuildFolderPermissions']
+__all__ = ['IterativePermissionsArgs', 'IterativePermissions']
 
 @pulumi.input_type
-class BuildFolderPermissionsArgs:
+class IterativePermissionsArgs:
     def __init__(__self__, *,
-                 path: pulumi.Input[str],
                  permissions: pulumi.Input[Mapping[str, pulumi.Input[str]]],
                  principal: pulumi.Input[str],
                  project_id: pulumi.Input[str],
+                 path: Optional[pulumi.Input[str]] = None,
                  replace: Optional[pulumi.Input[bool]] = None):
         """
-        The set of arguments for constructing a BuildFolderPermissions resource.
-        :param pulumi.Input[str] path: The folder path to assign the permissions.
+        The set of arguments for constructing a IterativePermissions resource.
         :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available.
         :param pulumi.Input[str] principal: The **group** principal to assign the permissions.
         :param pulumi.Input[str] project_id: The ID of the project to assign the permissions.
-        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`.
+        :param pulumi.Input[str] path: The name of the branch to assign the permissions.
+        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
+               
+               | Permission      | Description                    |
+               |-----------------|--------------------------------|
+               | GENERIC_READ    | View permissions for this node |
+               | GENERIC_WRITE   | Edit this node                 |
+               | CREATE_CHILDREN | Create child nodes             |
+               | DELETE          | Delete this node               |
         """
-        pulumi.set(__self__, "path", path)
         pulumi.set(__self__, "permissions", permissions)
         pulumi.set(__self__, "principal", principal)
         pulumi.set(__self__, "project_id", project_id)
+        if path is not None:
+            pulumi.set(__self__, "path", path)
         if replace is not None:
             pulumi.set(__self__, "replace", replace)
 
     @property
     @pulumi.getter
-    def path(self) -> pulumi.Input[str]:
-        """
-        The folder path to assign the permissions.
-        """
-        return pulumi.get(self, "path")
-
-    @path.setter
-    def path(self, value: pulumi.Input[str]):
-        pulumi.set(self, "path", value)
-
-    @property
-    @pulumi.getter
     def permissions(self) -> pulumi.Input[Mapping[str, pulumi.Input[str]]]:
         """
         the permissions to assign. The following permissions are available.
         """
         return pulumi.get(self, "permissions")
 
     @permissions.setter
@@ -80,40 +76,66 @@
 
     @project_id.setter
     def project_id(self, value: pulumi.Input[str]):
         pulumi.set(self, "project_id", value)
 
     @property
     @pulumi.getter
+    def path(self) -> Optional[pulumi.Input[str]]:
+        """
+        The name of the branch to assign the permissions.
+        """
+        return pulumi.get(self, "path")
+
+    @path.setter
+    def path(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "path", value)
+
+    @property
+    @pulumi.getter
     def replace(self) -> Optional[pulumi.Input[bool]]:
         """
-        Replace (`true`) or merge (`false`) the permissions. Default: `true`.
+        Replace (`true`) or merge (`false`) the permissions. Default: `true`
+
+        | Permission      | Description                    |
+        |-----------------|--------------------------------|
+        | GENERIC_READ    | View permissions for this node |
+        | GENERIC_WRITE   | Edit this node                 |
+        | CREATE_CHILDREN | Create child nodes             |
+        | DELETE          | Delete this node               |
         """
         return pulumi.get(self, "replace")
 
     @replace.setter
     def replace(self, value: Optional[pulumi.Input[bool]]):
         pulumi.set(self, "replace", value)
 
 
 @pulumi.input_type
-class _BuildFolderPermissionsState:
+class _IterativePermissionsState:
     def __init__(__self__, *,
                  path: Optional[pulumi.Input[str]] = None,
                  permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
                  principal: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  replace: Optional[pulumi.Input[bool]] = None):
         """
-        Input properties used for looking up and filtering BuildFolderPermissions resources.
-        :param pulumi.Input[str] path: The folder path to assign the permissions.
+        Input properties used for looking up and filtering IterativePermissions resources.
+        :param pulumi.Input[str] path: The name of the branch to assign the permissions.
         :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available.
         :param pulumi.Input[str] principal: The **group** principal to assign the permissions.
         :param pulumi.Input[str] project_id: The ID of the project to assign the permissions.
-        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`.
+        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
+               
+               | Permission      | Description                    |
+               |-----------------|--------------------------------|
+               | GENERIC_READ    | View permissions for this node |
+               | GENERIC_WRITE   | Edit this node                 |
+               | CREATE_CHILDREN | Create child nodes             |
+               | DELETE          | Delete this node               |
         """
         if path is not None:
             pulumi.set(__self__, "path", path)
         if permissions is not None:
             pulumi.set(__self__, "permissions", permissions)
         if principal is not None:
             pulumi.set(__self__, "principal", principal)
@@ -122,15 +144,15 @@
         if replace is not None:
             pulumi.set(__self__, "replace", replace)
 
     @property
     @pulumi.getter
     def path(self) -> Optional[pulumi.Input[str]]:
         """
-        The folder path to assign the permissions.
+        The name of the branch to assign the permissions.
         """
         return pulumi.get(self, "path")
 
     @path.setter
     def path(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "path", value)
 
@@ -170,75 +192,80 @@
     def project_id(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "project_id", value)
 
     @property
     @pulumi.getter
     def replace(self) -> Optional[pulumi.Input[bool]]:
         """
-        Replace (`true`) or merge (`false`) the permissions. Default: `true`.
+        Replace (`true`) or merge (`false`) the permissions. Default: `true`
+
+        | Permission      | Description                    |
+        |-----------------|--------------------------------|
+        | GENERIC_READ    | View permissions for this node |
+        | GENERIC_WRITE   | Edit this node                 |
+        | CREATE_CHILDREN | Create child nodes             |
+        | DELETE          | Delete this node               |
         """
         return pulumi.get(self, "replace")
 
     @replace.setter
     def replace(self, value: Optional[pulumi.Input[bool]]):
         pulumi.set(self, "replace", value)
 
 
-class BuildFolderPermissions(pulumi.CustomResource):
+class IterativePermissions(pulumi.CustomResource):
     @overload
     def __init__(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
                  path: Optional[pulumi.Input[str]] = None,
                  permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
                  principal: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  replace: Optional[pulumi.Input[bool]] = None,
                  __props__=None):
         """
-        Manages permissions for a Build Folder
+        Manages permissions for an Iteration (Sprint)
 
         > **Note** Permissions can be assigned to group principals and not to single user principals.
 
+        ## Permission levels
+
+        Permission for Iterations within Azure DevOps can be applied on two different levels.
+        Those levels are reflected by specifying (or omitting) values for the arguments `project_id` and `path`.
+
         ## Example Usage
 
         ```python
         import pulumi
         import pulumi_azuredevops as azuredevops
 
-        example_project = azuredevops.Project("exampleProject",
+        example = azuredevops.Project("example",
             work_item_template="Agile",
             version_control="Git",
             visibility="private",
             description="Managed by Terraform")
-        example_readers = azuredevops.get_group_output(project_id=example_project.id,
+        example_readers = azuredevops.get_group_output(project_id=example.id,
             name="Readers")
-        example_build_folder = azuredevops.BuildFolder("exampleBuildFolder",
-            project_id=example_project.id,
-            path="\\\\ExampleFolder",
-            description="ExampleFolder description")
-        example_build_folder_permissions = azuredevops.BuildFolderPermissions("exampleBuildFolderPermissions",
-            project_id=example_project.id,
-            path="\\\\ExampleFolder",
+        example_root_permissions = azuredevops.IterativePermissions("example-root-permissions",
+            project_id=example.id,
             principal=example_readers.id,
             permissions={
-                "ViewBuilds": "Allow",
-                "EditBuildQuality": "Allow",
-                "RetainIndefinitely": "Allow",
-                "DeleteBuilds": "Deny",
-                "ManageBuildQualities": "Deny",
-                "DestroyBuilds": "Deny",
-                "UpdateBuildInformation": "Deny",
-                "QueueBuilds": "Allow",
-                "ManageBuildQueue": "Deny",
-                "StopBuilds": "Allow",
-                "ViewBuildDefinition": "Allow",
-                "EditBuildDefinition": "Deny",
-                "DeleteBuildDefinition": "Deny",
-                "AdministerBuildPermissions": "NotSet",
+                "CREATE_CHILDREN": "Deny",
+                "GENERIC_READ": "NotSet",
+                "DELETE": "Deny",
+            })
+        example_iteration_permissions = azuredevops.IterativePermissions("example-iteration-permissions",
+            project_id=example.id,
+            principal=example_readers.id,
+            path="Iteration 1",
+            permissions={
+                "CREATE_CHILDREN": "Allow",
+                "GENERIC_READ": "NotSet",
+                "DELETE": "Allow",
             })
         ```
         ## Relevant Links
 
         * [Azure DevOps Service REST API 6.0 - Security](https://docs.microsoft.com/en-us/rest/api/azure/devops/security/?view=azure-devops-rest-6.0)
 
         ## PAT Permissions Required
@@ -247,67 +274,72 @@
 
         ## Import
 
         The resource does not support import.
 
         :param str resource_name: The name of the resource.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[str] path: The folder path to assign the permissions.
+        :param pulumi.Input[str] path: The name of the branch to assign the permissions.
         :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available.
         :param pulumi.Input[str] principal: The **group** principal to assign the permissions.
         :param pulumi.Input[str] project_id: The ID of the project to assign the permissions.
-        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`.
+        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
+               
+               | Permission      | Description                    |
+               |-----------------|--------------------------------|
+               | GENERIC_READ    | View permissions for this node |
+               | GENERIC_WRITE   | Edit this node                 |
+               | CREATE_CHILDREN | Create child nodes             |
+               | DELETE          | Delete this node               |
         """
         ...
     @overload
     def __init__(__self__,
                  resource_name: str,
-                 args: BuildFolderPermissionsArgs,
+                 args: IterativePermissionsArgs,
                  opts: Optional[pulumi.ResourceOptions] = None):
         """
-        Manages permissions for a Build Folder
+        Manages permissions for an Iteration (Sprint)
 
         > **Note** Permissions can be assigned to group principals and not to single user principals.
 
+        ## Permission levels
+
+        Permission for Iterations within Azure DevOps can be applied on two different levels.
+        Those levels are reflected by specifying (or omitting) values for the arguments `project_id` and `path`.
+
         ## Example Usage
 
         ```python
         import pulumi
         import pulumi_azuredevops as azuredevops
 
-        example_project = azuredevops.Project("exampleProject",
+        example = azuredevops.Project("example",
             work_item_template="Agile",
             version_control="Git",
             visibility="private",
             description="Managed by Terraform")
-        example_readers = azuredevops.get_group_output(project_id=example_project.id,
+        example_readers = azuredevops.get_group_output(project_id=example.id,
             name="Readers")
-        example_build_folder = azuredevops.BuildFolder("exampleBuildFolder",
-            project_id=example_project.id,
-            path="\\\\ExampleFolder",
-            description="ExampleFolder description")
-        example_build_folder_permissions = azuredevops.BuildFolderPermissions("exampleBuildFolderPermissions",
-            project_id=example_project.id,
-            path="\\\\ExampleFolder",
+        example_root_permissions = azuredevops.IterativePermissions("example-root-permissions",
+            project_id=example.id,
             principal=example_readers.id,
             permissions={
-                "ViewBuilds": "Allow",
-                "EditBuildQuality": "Allow",
-                "RetainIndefinitely": "Allow",
-                "DeleteBuilds": "Deny",
-                "ManageBuildQualities": "Deny",
-                "DestroyBuilds": "Deny",
-                "UpdateBuildInformation": "Deny",
-                "QueueBuilds": "Allow",
-                "ManageBuildQueue": "Deny",
-                "StopBuilds": "Allow",
-                "ViewBuildDefinition": "Allow",
-                "EditBuildDefinition": "Deny",
-                "DeleteBuildDefinition": "Deny",
-                "AdministerBuildPermissions": "NotSet",
+                "CREATE_CHILDREN": "Deny",
+                "GENERIC_READ": "NotSet",
+                "DELETE": "Deny",
+            })
+        example_iteration_permissions = azuredevops.IterativePermissions("example-iteration-permissions",
+            project_id=example.id,
+            principal=example_readers.id,
+            path="Iteration 1",
+            permissions={
+                "CREATE_CHILDREN": "Allow",
+                "GENERIC_READ": "NotSet",
+                "DELETE": "Allow",
             })
         ```
         ## Relevant Links
 
         * [Azure DevOps Service REST API 6.0 - Security](https://docs.microsoft.com/en-us/rest/api/azure/devops/security/?view=azure-devops-rest-6.0)
 
         ## PAT Permissions Required
@@ -315,20 +347,20 @@
         - **Project & Team**: vso.security_manage - Grants the ability to read, write, and manage security permissions.
 
         ## Import
 
         The resource does not support import.
 
         :param str resource_name: The name of the resource.
-        :param BuildFolderPermissionsArgs args: The arguments to use to populate this resource's properties.
+        :param IterativePermissionsArgs args: The arguments to use to populate this resource's properties.
         :param pulumi.ResourceOptions opts: Options for the resource.
         """
         ...
     def __init__(__self__, resource_name: str, *args, **kwargs):
-        resource_args, opts = _utilities.get_resource_args_opts(BuildFolderPermissionsArgs, pulumi.ResourceOptions, *args, **kwargs)
+        resource_args, opts = _utilities.get_resource_args_opts(IterativePermissionsArgs, pulumi.ResourceOptions, *args, **kwargs)
         if resource_args is not None:
             __self__._internal_init(resource_name, opts, **resource_args.__dict__)
         else:
             __self__._internal_init(resource_name, *args, **kwargs)
 
     def _internal_init(__self__,
                  resource_name: str,
@@ -341,73 +373,78 @@
                  __props__=None):
         opts = pulumi.ResourceOptions.merge(_utilities.get_resource_opts_defaults(), opts)
         if not isinstance(opts, pulumi.ResourceOptions):
             raise TypeError('Expected resource options to be a ResourceOptions instance')
         if opts.id is None:
             if __props__ is not None:
                 raise TypeError('__props__ is only valid when passed in combination with a valid opts.id to get an existing resource')
-            __props__ = BuildFolderPermissionsArgs.__new__(BuildFolderPermissionsArgs)
+            __props__ = IterativePermissionsArgs.__new__(IterativePermissionsArgs)
 
-            if path is None and not opts.urn:
-                raise TypeError("Missing required property 'path'")
             __props__.__dict__["path"] = path
             if permissions is None and not opts.urn:
                 raise TypeError("Missing required property 'permissions'")
             __props__.__dict__["permissions"] = permissions
             if principal is None and not opts.urn:
                 raise TypeError("Missing required property 'principal'")
             __props__.__dict__["principal"] = principal
             if project_id is None and not opts.urn:
                 raise TypeError("Missing required property 'project_id'")
             __props__.__dict__["project_id"] = project_id
             __props__.__dict__["replace"] = replace
-        super(BuildFolderPermissions, __self__).__init__(
-            'azuredevops:index/buildFolderPermissions:BuildFolderPermissions',
+        super(IterativePermissions, __self__).__init__(
+            'azuredevops:index/iterativePermissions:IterativePermissions',
             resource_name,
             __props__,
             opts)
 
     @staticmethod
     def get(resource_name: str,
             id: pulumi.Input[str],
             opts: Optional[pulumi.ResourceOptions] = None,
             path: Optional[pulumi.Input[str]] = None,
             permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
             principal: Optional[pulumi.Input[str]] = None,
             project_id: Optional[pulumi.Input[str]] = None,
-            replace: Optional[pulumi.Input[bool]] = None) -> 'BuildFolderPermissions':
+            replace: Optional[pulumi.Input[bool]] = None) -> 'IterativePermissions':
         """
-        Get an existing BuildFolderPermissions resource's state with the given name, id, and optional extra
+        Get an existing IterativePermissions resource's state with the given name, id, and optional extra
         properties used to qualify the lookup.
 
         :param str resource_name: The unique name of the resulting resource.
         :param pulumi.Input[str] id: The unique provider ID of the resource to lookup.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[str] path: The folder path to assign the permissions.
+        :param pulumi.Input[str] path: The name of the branch to assign the permissions.
         :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available.
         :param pulumi.Input[str] principal: The **group** principal to assign the permissions.
         :param pulumi.Input[str] project_id: The ID of the project to assign the permissions.
-        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`.
+        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
+               
+               | Permission      | Description                    |
+               |-----------------|--------------------------------|
+               | GENERIC_READ    | View permissions for this node |
+               | GENERIC_WRITE   | Edit this node                 |
+               | CREATE_CHILDREN | Create child nodes             |
+               | DELETE          | Delete this node               |
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
 
-        __props__ = _BuildFolderPermissionsState.__new__(_BuildFolderPermissionsState)
+        __props__ = _IterativePermissionsState.__new__(_IterativePermissionsState)
 
         __props__.__dict__["path"] = path
         __props__.__dict__["permissions"] = permissions
         __props__.__dict__["principal"] = principal
         __props__.__dict__["project_id"] = project_id
         __props__.__dict__["replace"] = replace
-        return BuildFolderPermissions(resource_name, opts=opts, __props__=__props__)
+        return IterativePermissions(resource_name, opts=opts, __props__=__props__)
 
     @property
     @pulumi.getter
-    def path(self) -> pulumi.Output[str]:
+    def path(self) -> pulumi.Output[Optional[str]]:
         """
-        The folder path to assign the permissions.
+        The name of the branch to assign the permissions.
         """
         return pulumi.get(self, "path")
 
     @property
     @pulumi.getter
     def permissions(self) -> pulumi.Output[Mapping[str, str]]:
         """
@@ -431,11 +468,18 @@
         """
         return pulumi.get(self, "project_id")
 
     @property
     @pulumi.getter
     def replace(self) -> pulumi.Output[Optional[bool]]:
         """
-        Replace (`true`) or merge (`false`) the permissions. Default: `true`.
+        Replace (`true`) or merge (`false`) the permissions. Default: `true`
+
+        | Permission      | Description                    |
+        |-----------------|--------------------------------|
+        | GENERIC_READ    | View permissions for this node |
+        | GENERIC_WRITE   | Edit this node                 |
+        | CREATE_CHILDREN | Create child nodes             |
+        | DELETE          | Delete this node               |
         """
         return pulumi.get(self, "replace")
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/check_branch_control.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/check_branch_control.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/check_business_hours.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/check_business_hours.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/config/vars.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/config/vars.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/core/get_client_config.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/core/get_client_config.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/core/get_project.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/core/get_project.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/core/get_projects.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/core/get_projects.py`

 * *Files 2% similar despite different names*

```diff
@@ -105,14 +105,16 @@
     ## Relevant Links
 
     - [Azure DevOps Service REST API 6.0 - Projects - Get](https://docs.microsoft.com/en-us/rest/api/azure/devops/core/projects/get?view=azure-devops-rest-6.0)
 
 
     :param str name: Name of the Project, if not specified all projects will be returned.
     :param str state: State of the Project, if not specified all projects will be returned. Valid values are `all`, `deleting`, `new`, `wellFormed`, `createPending`, `unchanged`,`deleted`.
+           
+           DataSource without specifying any arguments will return all projects.
     """
     pulumi.log.warn("""get_projects is deprecated: azuredevops.core.getProjects has been deprecated in favor of azuredevops.getProjects""")
     __args__ = dict()
     __args__['name'] = name
     __args__['state'] = state
     opts = pulumi.InvokeOptions.merge(_utilities.get_invoke_opts_defaults(), opts)
     __ret__ = pulumi.runtime.invoke('azuredevops:Core/getProjects:getProjects', __args__, opts=opts, typ=GetProjectsResult).value
@@ -147,10 +149,12 @@
     ## Relevant Links
 
     - [Azure DevOps Service REST API 6.0 - Projects - Get](https://docs.microsoft.com/en-us/rest/api/azure/devops/core/projects/get?view=azure-devops-rest-6.0)
 
 
     :param str name: Name of the Project, if not specified all projects will be returned.
     :param str state: State of the Project, if not specified all projects will be returned. Valid values are `all`, `deleting`, `new`, `wellFormed`, `createPending`, `unchanged`,`deleted`.
+           
+           DataSource without specifying any arguments will return all projects.
     """
     pulumi.log.warn("""get_projects is deprecated: azuredevops.core.getProjects has been deprecated in favor of azuredevops.getProjects""")
     ...
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/core/outputs.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/core/outputs.py`

 * *Files 6% similar despite different names*

```diff
@@ -21,14 +21,16 @@
                  project_url: str,
                  state: str):
         """
         :param str name: Name of the Project, if not specified all projects will be returned.
         :param str project_id: The ID of the Project.
         :param str project_url: Url to the full version of the object.
         :param str state: State of the Project, if not specified all projects will be returned. Valid values are `all`, `deleting`, `new`, `wellFormed`, `createPending`, `unchanged`,`deleted`.
+               
+               DataSource without specifying any arguments will return all projects.
         """
         pulumi.set(__self__, "name", name)
         pulumi.set(__self__, "project_id", project_id)
         pulumi.set(__self__, "project_url", project_url)
         pulumi.set(__self__, "state", state)
 
     @property
@@ -56,11 +58,13 @@
         return pulumi.get(self, "project_url")
 
     @property
     @pulumi.getter
     def state(self) -> str:
         """
         State of the Project, if not specified all projects will be returned. Valid values are `all`, `deleting`, `new`, `wellFormed`, `createPending`, `unchanged`,`deleted`.
+
+        DataSource without specifying any arguments will return all projects.
         """
         return pulumi.get(self, "state")
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/core/project.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/project.py`

 * *Files 6% similar despite different names*

```diff
@@ -3,15 +3,15 @@
 # *** Do not edit by hand unless you're certain you know what you are doing! ***
 
 import copy
 import warnings
 import pulumi
 import pulumi.runtime
 from typing import Any, Mapping, Optional, Sequence, Union, overload
-from .. import _utilities
+from . import _utilities
 
 __all__ = ['ProjectArgs', 'Project']
 
 @pulumi.input_type
 class ProjectArgs:
     def __init__(__self__, *,
                  description: Optional[pulumi.Input[str]] = None,
@@ -21,14 +21,19 @@
                  visibility: Optional[pulumi.Input[str]] = None,
                  work_item_template: Optional[pulumi.Input[str]] = None):
         """
         The set of arguments for constructing a Project resource.
         :param pulumi.Input[str] description: The Description of the Project.
         :param pulumi.Input[Mapping[str, pulumi.Input[str]]] features: Defines the status (`enabled`, `disabled`) of the project features.
                Valid features are `boards`, `repositories`, `pipelines`, `testplans`, `artifacts`
+               
+               > **NOTE:**
+               > It's possible to define project features both within the `ProjectFeatures` resource and
+               > via the `features` block by using the `Project` resource.
+               > However it's not possible to use both methods to manage features, since there'll be conflicts.
         :param pulumi.Input[str] name: The Project Name.
         :param pulumi.Input[str] version_control: Specifies the version control system. Valid values: `Git` or `Tfvc`. Defaults to `Git`.
         :param pulumi.Input[str] visibility: Specifies the visibility of the Project. Valid values: `private` or `public`. Defaults to `private`.
         :param pulumi.Input[str] work_item_template: Specifies the work item template. Valid values: `Agile`, `Basic`, `CMMI`, `Scrum` or a custom, pre-existing one. Defaults to `Agile`. An empty string will use the parent organization default.
         """
         if description is not None:
             pulumi.set(__self__, "description", description)
@@ -57,14 +62,19 @@
 
     @property
     @pulumi.getter
     def features(self) -> Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]:
         """
         Defines the status (`enabled`, `disabled`) of the project features.
         Valid features are `boards`, `repositories`, `pipelines`, `testplans`, `artifacts`
+
+        > **NOTE:**
+        > It's possible to define project features both within the `ProjectFeatures` resource and
+        > via the `features` block by using the `Project` resource.
+        > However it's not possible to use both methods to manage features, since there'll be conflicts.
         """
         return pulumi.get(self, "features")
 
     @features.setter
     def features(self, value: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]):
         pulumi.set(self, "features", value)
 
@@ -128,14 +138,19 @@
                  visibility: Optional[pulumi.Input[str]] = None,
                  work_item_template: Optional[pulumi.Input[str]] = None):
         """
         Input properties used for looking up and filtering Project resources.
         :param pulumi.Input[str] description: The Description of the Project.
         :param pulumi.Input[Mapping[str, pulumi.Input[str]]] features: Defines the status (`enabled`, `disabled`) of the project features.
                Valid features are `boards`, `repositories`, `pipelines`, `testplans`, `artifacts`
+               
+               > **NOTE:**
+               > It's possible to define project features both within the `ProjectFeatures` resource and
+               > via the `features` block by using the `Project` resource.
+               > However it's not possible to use both methods to manage features, since there'll be conflicts.
         :param pulumi.Input[str] name: The Project Name.
         :param pulumi.Input[str] process_template_id: The Process Template ID used by the Project.
         :param pulumi.Input[str] version_control: Specifies the version control system. Valid values: `Git` or `Tfvc`. Defaults to `Git`.
         :param pulumi.Input[str] visibility: Specifies the visibility of the Project. Valid values: `private` or `public`. Defaults to `private`.
         :param pulumi.Input[str] work_item_template: Specifies the work item template. Valid values: `Agile`, `Basic`, `CMMI`, `Scrum` or a custom, pre-existing one. Defaults to `Agile`. An empty string will use the parent organization default.
         """
         if description is not None:
@@ -167,14 +182,19 @@
 
     @property
     @pulumi.getter
     def features(self) -> Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]:
         """
         Defines the status (`enabled`, `disabled`) of the project features.
         Valid features are `boards`, `repositories`, `pipelines`, `testplans`, `artifacts`
+
+        > **NOTE:**
+        > It's possible to define project features both within the `ProjectFeatures` resource and
+        > via the `features` block by using the `Project` resource.
+        > However it's not possible to use both methods to manage features, since there'll be conflicts.
         """
         return pulumi.get(self, "features")
 
     @features.setter
     def features(self, value: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]):
         pulumi.set(self, "features", value)
 
@@ -235,20 +255,15 @@
         return pulumi.get(self, "work_item_template")
 
     @work_item_template.setter
     def work_item_template(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "work_item_template", value)
 
 
-warnings.warn("""azuredevops.core.Project has been deprecated in favor of azuredevops.Project""", DeprecationWarning)
-
-
 class Project(pulumi.CustomResource):
-    warnings.warn("""azuredevops.core.Project has been deprecated in favor of azuredevops.Project""", DeprecationWarning)
-
     @overload
     def __init__(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
                  description: Optional[pulumi.Input[str]] = None,
                  features: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
                  name: Optional[pulumi.Input[str]] = None,
@@ -284,28 +299,33 @@
         - **Project & Team**: Read, Write, & Manage
 
         ## Import
 
         Azure DevOps Projects can be imported using the project name or by the project Guid, e.g.
 
         ```sh
-         $ pulumi import azuredevops:Core/project:Project example "Example Project"
+         $ pulumi import azuredevops:index/project:Project example "Example Project"
         ```
 
          or
 
         ```sh
-         $ pulumi import azuredevops:Core/project:Project example 00000000-0000-0000-0000-000000000000
+         $ pulumi import azuredevops:index/project:Project example 00000000-0000-0000-0000-000000000000
         ```
 
         :param str resource_name: The name of the resource.
         :param pulumi.ResourceOptions opts: Options for the resource.
         :param pulumi.Input[str] description: The Description of the Project.
         :param pulumi.Input[Mapping[str, pulumi.Input[str]]] features: Defines the status (`enabled`, `disabled`) of the project features.
                Valid features are `boards`, `repositories`, `pipelines`, `testplans`, `artifacts`
+               
+               > **NOTE:**
+               > It's possible to define project features both within the `ProjectFeatures` resource and
+               > via the `features` block by using the `Project` resource.
+               > However it's not possible to use both methods to manage features, since there'll be conflicts.
         :param pulumi.Input[str] name: The Project Name.
         :param pulumi.Input[str] version_control: Specifies the version control system. Valid values: `Git` or `Tfvc`. Defaults to `Git`.
         :param pulumi.Input[str] visibility: Specifies the visibility of the Project. Valid values: `private` or `public`. Defaults to `private`.
         :param pulumi.Input[str] work_item_template: Specifies the work item template. Valid values: `Agile`, `Basic`, `CMMI`, `Scrum` or a custom, pre-existing one. Defaults to `Agile`. An empty string will use the parent organization default.
         """
         ...
     @overload
@@ -341,21 +361,21 @@
         - **Project & Team**: Read, Write, & Manage
 
         ## Import
 
         Azure DevOps Projects can be imported using the project name or by the project Guid, e.g.
 
         ```sh
-         $ pulumi import azuredevops:Core/project:Project example "Example Project"
+         $ pulumi import azuredevops:index/project:Project example "Example Project"
         ```
 
          or
 
         ```sh
-         $ pulumi import azuredevops:Core/project:Project example 00000000-0000-0000-0000-000000000000
+         $ pulumi import azuredevops:index/project:Project example 00000000-0000-0000-0000-000000000000
         ```
 
         :param str resource_name: The name of the resource.
         :param ProjectArgs args: The arguments to use to populate this resource's properties.
         :param pulumi.ResourceOptions opts: Options for the resource.
         """
         ...
@@ -372,15 +392,14 @@
                  description: Optional[pulumi.Input[str]] = None,
                  features: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
                  name: Optional[pulumi.Input[str]] = None,
                  version_control: Optional[pulumi.Input[str]] = None,
                  visibility: Optional[pulumi.Input[str]] = None,
                  work_item_template: Optional[pulumi.Input[str]] = None,
                  __props__=None):
-        pulumi.log.warn("""Project is deprecated: azuredevops.core.Project has been deprecated in favor of azuredevops.Project""")
         opts = pulumi.ResourceOptions.merge(_utilities.get_resource_opts_defaults(), opts)
         if not isinstance(opts, pulumi.ResourceOptions):
             raise TypeError('Expected resource options to be a ResourceOptions instance')
         if opts.id is None:
             if __props__ is not None:
                 raise TypeError('__props__ is only valid when passed in combination with a valid opts.id to get an existing resource')
             __props__ = ProjectArgs.__new__(ProjectArgs)
@@ -388,16 +407,18 @@
             __props__.__dict__["description"] = description
             __props__.__dict__["features"] = features
             __props__.__dict__["name"] = name
             __props__.__dict__["version_control"] = version_control
             __props__.__dict__["visibility"] = visibility
             __props__.__dict__["work_item_template"] = work_item_template
             __props__.__dict__["process_template_id"] = None
+        alias_opts = pulumi.ResourceOptions(aliases=[pulumi.Alias(type_="azuredevops:Core/project:Project")])
+        opts = pulumi.ResourceOptions.merge(opts, alias_opts)
         super(Project, __self__).__init__(
-            'azuredevops:Core/project:Project',
+            'azuredevops:index/project:Project',
             resource_name,
             __props__,
             opts)
 
     @staticmethod
     def get(resource_name: str,
             id: pulumi.Input[str],
@@ -415,14 +436,19 @@
 
         :param str resource_name: The unique name of the resulting resource.
         :param pulumi.Input[str] id: The unique provider ID of the resource to lookup.
         :param pulumi.ResourceOptions opts: Options for the resource.
         :param pulumi.Input[str] description: The Description of the Project.
         :param pulumi.Input[Mapping[str, pulumi.Input[str]]] features: Defines the status (`enabled`, `disabled`) of the project features.
                Valid features are `boards`, `repositories`, `pipelines`, `testplans`, `artifacts`
+               
+               > **NOTE:**
+               > It's possible to define project features both within the `ProjectFeatures` resource and
+               > via the `features` block by using the `Project` resource.
+               > However it's not possible to use both methods to manage features, since there'll be conflicts.
         :param pulumi.Input[str] name: The Project Name.
         :param pulumi.Input[str] process_template_id: The Process Template ID used by the Project.
         :param pulumi.Input[str] version_control: Specifies the version control system. Valid values: `Git` or `Tfvc`. Defaults to `Git`.
         :param pulumi.Input[str] visibility: Specifies the visibility of the Project. Valid values: `private` or `public`. Defaults to `private`.
         :param pulumi.Input[str] work_item_template: Specifies the work item template. Valid values: `Agile`, `Basic`, `CMMI`, `Scrum` or a custom, pre-existing one. Defaults to `Agile`. An empty string will use the parent organization default.
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
@@ -448,14 +474,19 @@
 
     @property
     @pulumi.getter
     def features(self) -> pulumi.Output[Optional[Mapping[str, str]]]:
         """
         Defines the status (`enabled`, `disabled`) of the project features.
         Valid features are `boards`, `repositories`, `pipelines`, `testplans`, `artifacts`
+
+        > **NOTE:**
+        > It's possible to define project features both within the `ProjectFeatures` resource and
+        > via the `features` block by using the `Project` resource.
+        > However it's not possible to use both methods to manage features, since there'll be conflicts.
         """
         return pulumi.get(self, "features")
 
     @property
     @pulumi.getter
     def name(self) -> pulumi.Output[str]:
         """
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/core/project_features.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/environment.py`

 * *Files 26% similar despite different names*

```diff
@@ -3,260 +3,288 @@
 # *** Do not edit by hand unless you're certain you know what you are doing! ***
 
 import copy
 import warnings
 import pulumi
 import pulumi.runtime
 from typing import Any, Mapping, Optional, Sequence, Union, overload
-from .. import _utilities
+from . import _utilities
 
-__all__ = ['ProjectFeaturesArgs', 'ProjectFeatures']
+__all__ = ['EnvironmentArgs', 'Environment']
 
 @pulumi.input_type
-class ProjectFeaturesArgs:
+class EnvironmentArgs:
     def __init__(__self__, *,
-                 features: pulumi.Input[Mapping[str, pulumi.Input[str]]],
-                 project_id: pulumi.Input[str]):
+                 project_id: pulumi.Input[str],
+                 description: Optional[pulumi.Input[str]] = None,
+                 name: Optional[pulumi.Input[str]] = None):
+        """
+        The set of arguments for constructing a Environment resource.
+        :param pulumi.Input[str] project_id: The ID of the project. Changing this forces a new Environment to be created.
+        :param pulumi.Input[str] description: A description for the Environment.
+        :param pulumi.Input[str] name: The name which should be used for this Environment.
         """
-        The set of arguments for constructing a ProjectFeatures resource.
-        :param pulumi.Input[Mapping[str, pulumi.Input[str]]] features: Defines the status (`enabled`, `disabled`) of the project features.  
-               Valid features `boards`, `repositories`, `pipelines`, `testplans`, `artifacts`
-        """
-        pulumi.set(__self__, "features", features)
         pulumi.set(__self__, "project_id", project_id)
-
-    @property
-    @pulumi.getter
-    def features(self) -> pulumi.Input[Mapping[str, pulumi.Input[str]]]:
-        """
-        Defines the status (`enabled`, `disabled`) of the project features.  
-        Valid features `boards`, `repositories`, `pipelines`, `testplans`, `artifacts`
-        """
-        return pulumi.get(self, "features")
-
-    @features.setter
-    def features(self, value: pulumi.Input[Mapping[str, pulumi.Input[str]]]):
-        pulumi.set(self, "features", value)
+        if description is not None:
+            pulumi.set(__self__, "description", description)
+        if name is not None:
+            pulumi.set(__self__, "name", name)
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> pulumi.Input[str]:
+        """
+        The ID of the project. Changing this forces a new Environment to be created.
+        """
         return pulumi.get(self, "project_id")
 
     @project_id.setter
     def project_id(self, value: pulumi.Input[str]):
         pulumi.set(self, "project_id", value)
 
+    @property
+    @pulumi.getter
+    def description(self) -> Optional[pulumi.Input[str]]:
+        """
+        A description for the Environment.
+        """
+        return pulumi.get(self, "description")
+
+    @description.setter
+    def description(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "description", value)
+
+    @property
+    @pulumi.getter
+    def name(self) -> Optional[pulumi.Input[str]]:
+        """
+        The name which should be used for this Environment.
+        """
+        return pulumi.get(self, "name")
+
+    @name.setter
+    def name(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "name", value)
+
 
 @pulumi.input_type
-class _ProjectFeaturesState:
+class _EnvironmentState:
     def __init__(__self__, *,
-                 features: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
+                 description: Optional[pulumi.Input[str]] = None,
+                 name: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None):
         """
-        Input properties used for looking up and filtering ProjectFeatures resources.
-        :param pulumi.Input[Mapping[str, pulumi.Input[str]]] features: Defines the status (`enabled`, `disabled`) of the project features.  
-               Valid features `boards`, `repositories`, `pipelines`, `testplans`, `artifacts`
-        """
-        if features is not None:
-            pulumi.set(__self__, "features", features)
+        Input properties used for looking up and filtering Environment resources.
+        :param pulumi.Input[str] description: A description for the Environment.
+        :param pulumi.Input[str] name: The name which should be used for this Environment.
+        :param pulumi.Input[str] project_id: The ID of the project. Changing this forces a new Environment to be created.
+        """
+        if description is not None:
+            pulumi.set(__self__, "description", description)
+        if name is not None:
+            pulumi.set(__self__, "name", name)
         if project_id is not None:
             pulumi.set(__self__, "project_id", project_id)
 
     @property
     @pulumi.getter
-    def features(self) -> Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]:
+    def description(self) -> Optional[pulumi.Input[str]]:
+        """
+        A description for the Environment.
+        """
+        return pulumi.get(self, "description")
+
+    @description.setter
+    def description(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "description", value)
+
+    @property
+    @pulumi.getter
+    def name(self) -> Optional[pulumi.Input[str]]:
         """
-        Defines the status (`enabled`, `disabled`) of the project features.  
-        Valid features `boards`, `repositories`, `pipelines`, `testplans`, `artifacts`
+        The name which should be used for this Environment.
         """
-        return pulumi.get(self, "features")
+        return pulumi.get(self, "name")
 
-    @features.setter
-    def features(self, value: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]):
-        pulumi.set(self, "features", value)
+    @name.setter
+    def name(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "name", value)
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> Optional[pulumi.Input[str]]:
+        """
+        The ID of the project. Changing this forces a new Environment to be created.
+        """
         return pulumi.get(self, "project_id")
 
     @project_id.setter
     def project_id(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "project_id", value)
 
 
-warnings.warn("""azuredevops.core.ProjectFeatures has been deprecated in favor of azuredevops.ProjectFeatures""", DeprecationWarning)
-
-
-class ProjectFeatures(pulumi.CustomResource):
-    warnings.warn("""azuredevops.core.ProjectFeatures has been deprecated in favor of azuredevops.ProjectFeatures""", DeprecationWarning)
-
+class Environment(pulumi.CustomResource):
     @overload
     def __init__(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
-                 features: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
+                 description: Optional[pulumi.Input[str]] = None,
+                 name: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  __props__=None):
         """
-        Manages features for Azure DevOps projects
+        Manages an Environment.
 
         ## Example Usage
 
         ```python
         import pulumi
         import pulumi_azuredevops as azuredevops
 
-        example = azuredevops.Project("example",
-            visibility="private",
-            version_control="Git",
+        example_project = azuredevops.Project("exampleProject",
             work_item_template="Agile",
+            version_control="Git",
+            visibility="private",
             description="Managed by Terraform")
-        example_features = azuredevops.ProjectFeatures("example-features",
-            project_id=example.id,
-            features={
-                "testplans": "disabled",
-                "artifacts": "enabled",
-            })
+        example_environment = azuredevops.Environment("exampleEnvironment", project_id=example_project.id)
         ```
         ## Relevant Links
 
-        No official documentation available
-
-        ## PAT Permissions Required
-
-        - **Project & Team**: Read, Write, & Manage
+        * [Azure DevOps Service REST API 6.0 - Environments](https://docs.microsoft.com/en-us/rest/api/azure/devops/distributedtask/environments?view=azure-devops-rest-6.0)
 
         ## Import
 
-        Azure DevOps feature settings can be imported using the project id, e.g.
+        Azure DevOps Environments can be imported using the project ID and environment ID, e.g.
 
         ```sh
-         $ pulumi import azuredevops:Core/projectFeatures:ProjectFeatures example 00000000-0000-0000-0000-000000000000
+         $ pulumi import azuredevops:index/environment:Environment example 00000000-0000-0000-0000-000000000000/0
         ```
 
         :param str resource_name: The name of the resource.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[Mapping[str, pulumi.Input[str]]] features: Defines the status (`enabled`, `disabled`) of the project features.  
-               Valid features `boards`, `repositories`, `pipelines`, `testplans`, `artifacts`
+        :param pulumi.Input[str] description: A description for the Environment.
+        :param pulumi.Input[str] name: The name which should be used for this Environment.
+        :param pulumi.Input[str] project_id: The ID of the project. Changing this forces a new Environment to be created.
         """
         ...
     @overload
     def __init__(__self__,
                  resource_name: str,
-                 args: ProjectFeaturesArgs,
+                 args: EnvironmentArgs,
                  opts: Optional[pulumi.ResourceOptions] = None):
         """
-        Manages features for Azure DevOps projects
+        Manages an Environment.
 
         ## Example Usage
 
         ```python
         import pulumi
         import pulumi_azuredevops as azuredevops
 
-        example = azuredevops.Project("example",
-            visibility="private",
-            version_control="Git",
+        example_project = azuredevops.Project("exampleProject",
             work_item_template="Agile",
+            version_control="Git",
+            visibility="private",
             description="Managed by Terraform")
-        example_features = azuredevops.ProjectFeatures("example-features",
-            project_id=example.id,
-            features={
-                "testplans": "disabled",
-                "artifacts": "enabled",
-            })
+        example_environment = azuredevops.Environment("exampleEnvironment", project_id=example_project.id)
         ```
         ## Relevant Links
 
-        No official documentation available
-
-        ## PAT Permissions Required
-
-        - **Project & Team**: Read, Write, & Manage
+        * [Azure DevOps Service REST API 6.0 - Environments](https://docs.microsoft.com/en-us/rest/api/azure/devops/distributedtask/environments?view=azure-devops-rest-6.0)
 
         ## Import
 
-        Azure DevOps feature settings can be imported using the project id, e.g.
+        Azure DevOps Environments can be imported using the project ID and environment ID, e.g.
 
         ```sh
-         $ pulumi import azuredevops:Core/projectFeatures:ProjectFeatures example 00000000-0000-0000-0000-000000000000
+         $ pulumi import azuredevops:index/environment:Environment example 00000000-0000-0000-0000-000000000000/0
         ```
 
         :param str resource_name: The name of the resource.
-        :param ProjectFeaturesArgs args: The arguments to use to populate this resource's properties.
+        :param EnvironmentArgs args: The arguments to use to populate this resource's properties.
         :param pulumi.ResourceOptions opts: Options for the resource.
         """
         ...
     def __init__(__self__, resource_name: str, *args, **kwargs):
-        resource_args, opts = _utilities.get_resource_args_opts(ProjectFeaturesArgs, pulumi.ResourceOptions, *args, **kwargs)
+        resource_args, opts = _utilities.get_resource_args_opts(EnvironmentArgs, pulumi.ResourceOptions, *args, **kwargs)
         if resource_args is not None:
             __self__._internal_init(resource_name, opts, **resource_args.__dict__)
         else:
             __self__._internal_init(resource_name, *args, **kwargs)
 
     def _internal_init(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
-                 features: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
+                 description: Optional[pulumi.Input[str]] = None,
+                 name: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  __props__=None):
-        pulumi.log.warn("""ProjectFeatures is deprecated: azuredevops.core.ProjectFeatures has been deprecated in favor of azuredevops.ProjectFeatures""")
         opts = pulumi.ResourceOptions.merge(_utilities.get_resource_opts_defaults(), opts)
         if not isinstance(opts, pulumi.ResourceOptions):
             raise TypeError('Expected resource options to be a ResourceOptions instance')
         if opts.id is None:
             if __props__ is not None:
                 raise TypeError('__props__ is only valid when passed in combination with a valid opts.id to get an existing resource')
-            __props__ = ProjectFeaturesArgs.__new__(ProjectFeaturesArgs)
+            __props__ = EnvironmentArgs.__new__(EnvironmentArgs)
 
-            if features is None and not opts.urn:
-                raise TypeError("Missing required property 'features'")
-            __props__.__dict__["features"] = features
+            __props__.__dict__["description"] = description
+            __props__.__dict__["name"] = name
             if project_id is None and not opts.urn:
                 raise TypeError("Missing required property 'project_id'")
             __props__.__dict__["project_id"] = project_id
-        super(ProjectFeatures, __self__).__init__(
-            'azuredevops:Core/projectFeatures:ProjectFeatures',
+        super(Environment, __self__).__init__(
+            'azuredevops:index/environment:Environment',
             resource_name,
             __props__,
             opts)
 
     @staticmethod
     def get(resource_name: str,
             id: pulumi.Input[str],
             opts: Optional[pulumi.ResourceOptions] = None,
-            features: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
-            project_id: Optional[pulumi.Input[str]] = None) -> 'ProjectFeatures':
+            description: Optional[pulumi.Input[str]] = None,
+            name: Optional[pulumi.Input[str]] = None,
+            project_id: Optional[pulumi.Input[str]] = None) -> 'Environment':
         """
-        Get an existing ProjectFeatures resource's state with the given name, id, and optional extra
+        Get an existing Environment resource's state with the given name, id, and optional extra
         properties used to qualify the lookup.
 
         :param str resource_name: The unique name of the resulting resource.
         :param pulumi.Input[str] id: The unique provider ID of the resource to lookup.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[Mapping[str, pulumi.Input[str]]] features: Defines the status (`enabled`, `disabled`) of the project features.  
-               Valid features `boards`, `repositories`, `pipelines`, `testplans`, `artifacts`
+        :param pulumi.Input[str] description: A description for the Environment.
+        :param pulumi.Input[str] name: The name which should be used for this Environment.
+        :param pulumi.Input[str] project_id: The ID of the project. Changing this forces a new Environment to be created.
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
 
-        __props__ = _ProjectFeaturesState.__new__(_ProjectFeaturesState)
+        __props__ = _EnvironmentState.__new__(_EnvironmentState)
 
-        __props__.__dict__["features"] = features
+        __props__.__dict__["description"] = description
+        __props__.__dict__["name"] = name
         __props__.__dict__["project_id"] = project_id
-        return ProjectFeatures(resource_name, opts=opts, __props__=__props__)
+        return Environment(resource_name, opts=opts, __props__=__props__)
 
     @property
     @pulumi.getter
-    def features(self) -> pulumi.Output[Mapping[str, str]]:
+    def description(self) -> pulumi.Output[Optional[str]]:
         """
-        Defines the status (`enabled`, `disabled`) of the project features.  
-        Valid features `boards`, `repositories`, `pipelines`, `testplans`, `artifacts`
+        A description for the Environment.
         """
-        return pulumi.get(self, "features")
+        return pulumi.get(self, "description")
+
+    @property
+    @pulumi.getter
+    def name(self) -> pulumi.Output[str]:
+        """
+        The name which should be used for this Environment.
+        """
+        return pulumi.get(self, "name")
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> pulumi.Output[str]:
+        """
+        The ID of the project. Changing this forces a new Environment to be created.
+        """
         return pulumi.get(self, "project_id")
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/entitlement/user.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/entitlement/user.py`

 * *Files 8% similar despite different names*

```diff
@@ -19,14 +19,16 @@
                  origin: Optional[pulumi.Input[str]] = None,
                  origin_id: Optional[pulumi.Input[str]] = None,
                  principal_name: Optional[pulumi.Input[str]] = None):
         """
         The set of arguments for constructing a User resource.
         :param pulumi.Input[str] account_license_type: Type of Account License. Valid values: `advanced`, `earlyAdopter`, `express`, `none`, `professional`, or `stakeholder`. Defaults to `express`. In addition the value `basic` is allowed which is an alias for `express` and reflects the name of the `express` license used in the Azure DevOps web interface.
         :param pulumi.Input[str] licensing_source: The source of the licensing (e.g. Account. MSDN etc.) Valid values: `account` (Default), `auto`, `msdn`, `none`, `profile`, `trial`
+               
+               > **NOTE:** A user can only be referenced by it's `principal_name` or by the combination of `origin_id` and `origin`.
         :param pulumi.Input[str] origin: The type of source provider for the origin identifier.
         :param pulumi.Input[str] origin_id: The unique identifier from the system of origin. Typically a sid, object id or Guid. e.g. Used for member of other tenant on Azure Active Directory.
         :param pulumi.Input[str] principal_name: The principal name is the PrincipalName of a graph member from the source provider. Usually, e-mail address.
         """
         if account_license_type is not None:
             pulumi.set(__self__, "account_license_type", account_license_type)
         if licensing_source is not None:
@@ -51,14 +53,16 @@
         pulumi.set(self, "account_license_type", value)
 
     @property
     @pulumi.getter(name="licensingSource")
     def licensing_source(self) -> Optional[pulumi.Input[str]]:
         """
         The source of the licensing (e.g. Account. MSDN etc.) Valid values: `account` (Default), `auto`, `msdn`, `none`, `profile`, `trial`
+
+        > **NOTE:** A user can only be referenced by it's `principal_name` or by the combination of `origin_id` and `origin`.
         """
         return pulumi.get(self, "licensing_source")
 
     @licensing_source.setter
     def licensing_source(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "licensing_source", value)
 
@@ -109,14 +113,16 @@
                  origin_id: Optional[pulumi.Input[str]] = None,
                  principal_name: Optional[pulumi.Input[str]] = None):
         """
         Input properties used for looking up and filtering User resources.
         :param pulumi.Input[str] account_license_type: Type of Account License. Valid values: `advanced`, `earlyAdopter`, `express`, `none`, `professional`, or `stakeholder`. Defaults to `express`. In addition the value `basic` is allowed which is an alias for `express` and reflects the name of the `express` license used in the Azure DevOps web interface.
         :param pulumi.Input[str] descriptor: The descriptor is the primary way to reference the graph subject while the system is running. This field will uniquely identify the user graph subject.
         :param pulumi.Input[str] licensing_source: The source of the licensing (e.g. Account. MSDN etc.) Valid values: `account` (Default), `auto`, `msdn`, `none`, `profile`, `trial`
+               
+               > **NOTE:** A user can only be referenced by it's `principal_name` or by the combination of `origin_id` and `origin`.
         :param pulumi.Input[str] origin: The type of source provider for the origin identifier.
         :param pulumi.Input[str] origin_id: The unique identifier from the system of origin. Typically a sid, object id or Guid. e.g. Used for member of other tenant on Azure Active Directory.
         :param pulumi.Input[str] principal_name: The principal name is the PrincipalName of a graph member from the source provider. Usually, e-mail address.
         """
         if account_license_type is not None:
             pulumi.set(__self__, "account_license_type", account_license_type)
         if descriptor is not None:
@@ -155,14 +161,16 @@
         pulumi.set(self, "descriptor", value)
 
     @property
     @pulumi.getter(name="licensingSource")
     def licensing_source(self) -> Optional[pulumi.Input[str]]:
         """
         The source of the licensing (e.g. Account. MSDN etc.) Valid values: `account` (Default), `auto`, `msdn`, `none`, `profile`, `trial`
+
+        > **NOTE:** A user can only be referenced by it's `principal_name` or by the combination of `origin_id` and `origin`.
         """
         return pulumi.get(self, "licensing_source")
 
     @licensing_source.setter
     def licensing_source(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "licensing_source", value)
 
@@ -243,14 +251,16 @@
 
         The resources allows the import via the UUID of a user entitlement or by using the principal name of a user owning an entitlement.
 
         :param str resource_name: The name of the resource.
         :param pulumi.ResourceOptions opts: Options for the resource.
         :param pulumi.Input[str] account_license_type: Type of Account License. Valid values: `advanced`, `earlyAdopter`, `express`, `none`, `professional`, or `stakeholder`. Defaults to `express`. In addition the value `basic` is allowed which is an alias for `express` and reflects the name of the `express` license used in the Azure DevOps web interface.
         :param pulumi.Input[str] licensing_source: The source of the licensing (e.g. Account. MSDN etc.) Valid values: `account` (Default), `auto`, `msdn`, `none`, `profile`, `trial`
+               
+               > **NOTE:** A user can only be referenced by it's `principal_name` or by the combination of `origin_id` and `origin`.
         :param pulumi.Input[str] origin: The type of source provider for the origin identifier.
         :param pulumi.Input[str] origin_id: The unique identifier from the system of origin. Typically a sid, object id or Guid. e.g. Used for member of other tenant on Azure Active Directory.
         :param pulumi.Input[str] principal_name: The principal name is the PrincipalName of a graph member from the source provider. Usually, e-mail address.
         """
         ...
     @overload
     def __init__(__self__,
@@ -339,14 +349,16 @@
 
         :param str resource_name: The unique name of the resulting resource.
         :param pulumi.Input[str] id: The unique provider ID of the resource to lookup.
         :param pulumi.ResourceOptions opts: Options for the resource.
         :param pulumi.Input[str] account_license_type: Type of Account License. Valid values: `advanced`, `earlyAdopter`, `express`, `none`, `professional`, or `stakeholder`. Defaults to `express`. In addition the value `basic` is allowed which is an alias for `express` and reflects the name of the `express` license used in the Azure DevOps web interface.
         :param pulumi.Input[str] descriptor: The descriptor is the primary way to reference the graph subject while the system is running. This field will uniquely identify the user graph subject.
         :param pulumi.Input[str] licensing_source: The source of the licensing (e.g. Account. MSDN etc.) Valid values: `account` (Default), `auto`, `msdn`, `none`, `profile`, `trial`
+               
+               > **NOTE:** A user can only be referenced by it's `principal_name` or by the combination of `origin_id` and `origin`.
         :param pulumi.Input[str] origin: The type of source provider for the origin identifier.
         :param pulumi.Input[str] origin_id: The unique identifier from the system of origin. Typically a sid, object id or Guid. e.g. Used for member of other tenant on Azure Active Directory.
         :param pulumi.Input[str] principal_name: The principal name is the PrincipalName of a graph member from the source provider. Usually, e-mail address.
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
 
         __props__ = _UserState.__new__(_UserState)
@@ -376,14 +388,16 @@
         return pulumi.get(self, "descriptor")
 
     @property
     @pulumi.getter(name="licensingSource")
     def licensing_source(self) -> pulumi.Output[Optional[str]]:
         """
         The source of the licensing (e.g. Account. MSDN etc.) Valid values: `account` (Default), `auto`, `msdn`, `none`, `profile`, `trial`
+
+        > **NOTE:** A user can only be referenced by it's `principal_name` or by the combination of `origin_id` and `origin`.
         """
         return pulumi.get(self, "licensing_source")
 
     @property
     @pulumi.getter
     def origin(self) -> pulumi.Output[str]:
         """
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/environment.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/queue.py`

 * *Files 18% similar despite different names*

```diff
@@ -5,286 +5,260 @@
 import copy
 import warnings
 import pulumi
 import pulumi.runtime
 from typing import Any, Mapping, Optional, Sequence, Union, overload
 from . import _utilities
 
-__all__ = ['EnvironmentArgs', 'Environment']
+__all__ = ['QueueArgs', 'Queue']
 
 @pulumi.input_type
-class EnvironmentArgs:
+class QueueArgs:
     def __init__(__self__, *,
-                 project_id: pulumi.Input[str],
-                 description: Optional[pulumi.Input[str]] = None,
-                 name: Optional[pulumi.Input[str]] = None):
-        """
-        The set of arguments for constructing a Environment resource.
-        :param pulumi.Input[str] project_id: The ID of the project. Changing this forces a new Environment to be created.
-        :param pulumi.Input[str] description: A description for the Environment.
-        :param pulumi.Input[str] name: The name which should be used for this Environment.
+                 agent_pool_id: pulumi.Input[int],
+                 project_id: pulumi.Input[str]):
         """
+        The set of arguments for constructing a Queue resource.
+        :param pulumi.Input[int] agent_pool_id: The ID of the organization agent pool.
+        :param pulumi.Input[str] project_id: The ID of the project in which to create the resource.
+        """
+        pulumi.set(__self__, "agent_pool_id", agent_pool_id)
         pulumi.set(__self__, "project_id", project_id)
-        if description is not None:
-            pulumi.set(__self__, "description", description)
-        if name is not None:
-            pulumi.set(__self__, "name", name)
+
+    @property
+    @pulumi.getter(name="agentPoolId")
+    def agent_pool_id(self) -> pulumi.Input[int]:
+        """
+        The ID of the organization agent pool.
+        """
+        return pulumi.get(self, "agent_pool_id")
+
+    @agent_pool_id.setter
+    def agent_pool_id(self, value: pulumi.Input[int]):
+        pulumi.set(self, "agent_pool_id", value)
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> pulumi.Input[str]:
         """
-        The ID of the project. Changing this forces a new Environment to be created.
+        The ID of the project in which to create the resource.
         """
         return pulumi.get(self, "project_id")
 
     @project_id.setter
     def project_id(self, value: pulumi.Input[str]):
         pulumi.set(self, "project_id", value)
 
-    @property
-    @pulumi.getter
-    def description(self) -> Optional[pulumi.Input[str]]:
-        """
-        A description for the Environment.
-        """
-        return pulumi.get(self, "description")
-
-    @description.setter
-    def description(self, value: Optional[pulumi.Input[str]]):
-        pulumi.set(self, "description", value)
-
-    @property
-    @pulumi.getter
-    def name(self) -> Optional[pulumi.Input[str]]:
-        """
-        The name which should be used for this Environment.
-        """
-        return pulumi.get(self, "name")
-
-    @name.setter
-    def name(self, value: Optional[pulumi.Input[str]]):
-        pulumi.set(self, "name", value)
-
 
 @pulumi.input_type
-class _EnvironmentState:
+class _QueueState:
     def __init__(__self__, *,
-                 description: Optional[pulumi.Input[str]] = None,
-                 name: Optional[pulumi.Input[str]] = None,
+                 agent_pool_id: Optional[pulumi.Input[int]] = None,
                  project_id: Optional[pulumi.Input[str]] = None):
         """
-        Input properties used for looking up and filtering Environment resources.
-        :param pulumi.Input[str] description: A description for the Environment.
-        :param pulumi.Input[str] name: The name which should be used for this Environment.
-        :param pulumi.Input[str] project_id: The ID of the project. Changing this forces a new Environment to be created.
-        """
-        if description is not None:
-            pulumi.set(__self__, "description", description)
-        if name is not None:
-            pulumi.set(__self__, "name", name)
+        Input properties used for looking up and filtering Queue resources.
+        :param pulumi.Input[int] agent_pool_id: The ID of the organization agent pool.
+        :param pulumi.Input[str] project_id: The ID of the project in which to create the resource.
+        """
+        if agent_pool_id is not None:
+            pulumi.set(__self__, "agent_pool_id", agent_pool_id)
         if project_id is not None:
             pulumi.set(__self__, "project_id", project_id)
 
     @property
-    @pulumi.getter
-    def description(self) -> Optional[pulumi.Input[str]]:
-        """
-        A description for the Environment.
-        """
-        return pulumi.get(self, "description")
-
-    @description.setter
-    def description(self, value: Optional[pulumi.Input[str]]):
-        pulumi.set(self, "description", value)
-
-    @property
-    @pulumi.getter
-    def name(self) -> Optional[pulumi.Input[str]]:
+    @pulumi.getter(name="agentPoolId")
+    def agent_pool_id(self) -> Optional[pulumi.Input[int]]:
         """
-        The name which should be used for this Environment.
+        The ID of the organization agent pool.
         """
-        return pulumi.get(self, "name")
+        return pulumi.get(self, "agent_pool_id")
 
-    @name.setter
-    def name(self, value: Optional[pulumi.Input[str]]):
-        pulumi.set(self, "name", value)
+    @agent_pool_id.setter
+    def agent_pool_id(self, value: Optional[pulumi.Input[int]]):
+        pulumi.set(self, "agent_pool_id", value)
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> Optional[pulumi.Input[str]]:
         """
-        The ID of the project. Changing this forces a new Environment to be created.
+        The ID of the project in which to create the resource.
         """
         return pulumi.get(self, "project_id")
 
     @project_id.setter
     def project_id(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "project_id", value)
 
 
-class Environment(pulumi.CustomResource):
+class Queue(pulumi.CustomResource):
     @overload
     def __init__(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
-                 description: Optional[pulumi.Input[str]] = None,
-                 name: Optional[pulumi.Input[str]] = None,
+                 agent_pool_id: Optional[pulumi.Input[int]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  __props__=None):
         """
-        Manages an Environment.
+        Manages an agent queue within Azure DevOps. In the UI, this is equivalent to adding an
+        Organization defined pool to a project.
+
+        The created queue is not authorized for use by all pipelines in the project. However,
+        the `ResourceAuthorization` resource can be used to grant authorization.
 
         ## Example Usage
 
         ```python
         import pulumi
         import pulumi_azuredevops as azuredevops
 
-        example_project = azuredevops.Project("exampleProject",
-            work_item_template="Agile",
-            version_control="Git",
-            visibility="private",
-            description="Managed by Terraform")
-        example_environment = azuredevops.Environment("exampleEnvironment", project_id=example_project.id)
+        example_project = azuredevops.Project("exampleProject")
+        example_pool = azuredevops.get_pool(name="example-pool")
+        example_queue = azuredevops.Queue("exampleQueue",
+            project_id=example_project.id,
+            agent_pool_id=example_pool.id)
+        # Grant access to queue to all pipelines in the project
+        example_resource_authorization = azuredevops.ResourceAuthorization("exampleResourceAuthorization",
+            project_id=example_project.id,
+            resource_id=example_queue.id,
+            type="queue",
+            authorized=True)
         ```
         ## Relevant Links
 
-        * [Azure DevOps Service REST API 6.0 - Environments](https://docs.microsoft.com/en-us/rest/api/azure/devops/distributedtask/environments?view=azure-devops-rest-6.0)
+        - [Azure DevOps Service REST API 6.0 - Agent Queues](https://docs.microsoft.com/en-us/rest/api/azure/devops/distributedtask/queues?view=azure-devops-rest-6.0)
 
         ## Import
 
-        Azure DevOps Environments can be imported using the project ID and environment ID, e.g.
+        Azure DevOps Agent Pools can be imported using the project ID and agent queue ID, e.g.
 
         ```sh
-         $ pulumi import azuredevops:index/environment:Environment example 00000000-0000-0000-0000-000000000000/0
+         $ pulumi import azuredevops:index/queue:Queue example 00000000-0000-0000-0000-000000000000/0
         ```
 
         :param str resource_name: The name of the resource.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[str] description: A description for the Environment.
-        :param pulumi.Input[str] name: The name which should be used for this Environment.
-        :param pulumi.Input[str] project_id: The ID of the project. Changing this forces a new Environment to be created.
+        :param pulumi.Input[int] agent_pool_id: The ID of the organization agent pool.
+        :param pulumi.Input[str] project_id: The ID of the project in which to create the resource.
         """
         ...
     @overload
     def __init__(__self__,
                  resource_name: str,
-                 args: EnvironmentArgs,
+                 args: QueueArgs,
                  opts: Optional[pulumi.ResourceOptions] = None):
         """
-        Manages an Environment.
+        Manages an agent queue within Azure DevOps. In the UI, this is equivalent to adding an
+        Organization defined pool to a project.
+
+        The created queue is not authorized for use by all pipelines in the project. However,
+        the `ResourceAuthorization` resource can be used to grant authorization.
 
         ## Example Usage
 
         ```python
         import pulumi
         import pulumi_azuredevops as azuredevops
 
-        example_project = azuredevops.Project("exampleProject",
-            work_item_template="Agile",
-            version_control="Git",
-            visibility="private",
-            description="Managed by Terraform")
-        example_environment = azuredevops.Environment("exampleEnvironment", project_id=example_project.id)
+        example_project = azuredevops.Project("exampleProject")
+        example_pool = azuredevops.get_pool(name="example-pool")
+        example_queue = azuredevops.Queue("exampleQueue",
+            project_id=example_project.id,
+            agent_pool_id=example_pool.id)
+        # Grant access to queue to all pipelines in the project
+        example_resource_authorization = azuredevops.ResourceAuthorization("exampleResourceAuthorization",
+            project_id=example_project.id,
+            resource_id=example_queue.id,
+            type="queue",
+            authorized=True)
         ```
         ## Relevant Links
 
-        * [Azure DevOps Service REST API 6.0 - Environments](https://docs.microsoft.com/en-us/rest/api/azure/devops/distributedtask/environments?view=azure-devops-rest-6.0)
+        - [Azure DevOps Service REST API 6.0 - Agent Queues](https://docs.microsoft.com/en-us/rest/api/azure/devops/distributedtask/queues?view=azure-devops-rest-6.0)
 
         ## Import
 
-        Azure DevOps Environments can be imported using the project ID and environment ID, e.g.
+        Azure DevOps Agent Pools can be imported using the project ID and agent queue ID, e.g.
 
         ```sh
-         $ pulumi import azuredevops:index/environment:Environment example 00000000-0000-0000-0000-000000000000/0
+         $ pulumi import azuredevops:index/queue:Queue example 00000000-0000-0000-0000-000000000000/0
         ```
 
         :param str resource_name: The name of the resource.
-        :param EnvironmentArgs args: The arguments to use to populate this resource's properties.
+        :param QueueArgs args: The arguments to use to populate this resource's properties.
         :param pulumi.ResourceOptions opts: Options for the resource.
         """
         ...
     def __init__(__self__, resource_name: str, *args, **kwargs):
-        resource_args, opts = _utilities.get_resource_args_opts(EnvironmentArgs, pulumi.ResourceOptions, *args, **kwargs)
+        resource_args, opts = _utilities.get_resource_args_opts(QueueArgs, pulumi.ResourceOptions, *args, **kwargs)
         if resource_args is not None:
             __self__._internal_init(resource_name, opts, **resource_args.__dict__)
         else:
             __self__._internal_init(resource_name, *args, **kwargs)
 
     def _internal_init(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
-                 description: Optional[pulumi.Input[str]] = None,
-                 name: Optional[pulumi.Input[str]] = None,
+                 agent_pool_id: Optional[pulumi.Input[int]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  __props__=None):
         opts = pulumi.ResourceOptions.merge(_utilities.get_resource_opts_defaults(), opts)
         if not isinstance(opts, pulumi.ResourceOptions):
             raise TypeError('Expected resource options to be a ResourceOptions instance')
         if opts.id is None:
             if __props__ is not None:
                 raise TypeError('__props__ is only valid when passed in combination with a valid opts.id to get an existing resource')
-            __props__ = EnvironmentArgs.__new__(EnvironmentArgs)
+            __props__ = QueueArgs.__new__(QueueArgs)
 
-            __props__.__dict__["description"] = description
-            __props__.__dict__["name"] = name
+            if agent_pool_id is None and not opts.urn:
+                raise TypeError("Missing required property 'agent_pool_id'")
+            __props__.__dict__["agent_pool_id"] = agent_pool_id
             if project_id is None and not opts.urn:
                 raise TypeError("Missing required property 'project_id'")
             __props__.__dict__["project_id"] = project_id
-        super(Environment, __self__).__init__(
-            'azuredevops:index/environment:Environment',
+        alias_opts = pulumi.ResourceOptions(aliases=[pulumi.Alias(type_="azuredevops:Agent/queue:Queue")])
+        opts = pulumi.ResourceOptions.merge(opts, alias_opts)
+        super(Queue, __self__).__init__(
+            'azuredevops:index/queue:Queue',
             resource_name,
             __props__,
             opts)
 
     @staticmethod
     def get(resource_name: str,
             id: pulumi.Input[str],
             opts: Optional[pulumi.ResourceOptions] = None,
-            description: Optional[pulumi.Input[str]] = None,
-            name: Optional[pulumi.Input[str]] = None,
-            project_id: Optional[pulumi.Input[str]] = None) -> 'Environment':
+            agent_pool_id: Optional[pulumi.Input[int]] = None,
+            project_id: Optional[pulumi.Input[str]] = None) -> 'Queue':
         """
-        Get an existing Environment resource's state with the given name, id, and optional extra
+        Get an existing Queue resource's state with the given name, id, and optional extra
         properties used to qualify the lookup.
 
         :param str resource_name: The unique name of the resulting resource.
         :param pulumi.Input[str] id: The unique provider ID of the resource to lookup.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[str] description: A description for the Environment.
-        :param pulumi.Input[str] name: The name which should be used for this Environment.
-        :param pulumi.Input[str] project_id: The ID of the project. Changing this forces a new Environment to be created.
+        :param pulumi.Input[int] agent_pool_id: The ID of the organization agent pool.
+        :param pulumi.Input[str] project_id: The ID of the project in which to create the resource.
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
 
-        __props__ = _EnvironmentState.__new__(_EnvironmentState)
+        __props__ = _QueueState.__new__(_QueueState)
 
-        __props__.__dict__["description"] = description
-        __props__.__dict__["name"] = name
+        __props__.__dict__["agent_pool_id"] = agent_pool_id
         __props__.__dict__["project_id"] = project_id
-        return Environment(resource_name, opts=opts, __props__=__props__)
-
-    @property
-    @pulumi.getter
-    def description(self) -> pulumi.Output[Optional[str]]:
-        """
-        A description for the Environment.
-        """
-        return pulumi.get(self, "description")
+        return Queue(resource_name, opts=opts, __props__=__props__)
 
     @property
-    @pulumi.getter
-    def name(self) -> pulumi.Output[str]:
+    @pulumi.getter(name="agentPoolId")
+    def agent_pool_id(self) -> pulumi.Output[int]:
         """
-        The name which should be used for this Environment.
+        The ID of the organization agent pool.
         """
-        return pulumi.get(self, "name")
+        return pulumi.get(self, "agent_pool_id")
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> pulumi.Output[str]:
         """
-        The ID of the project. Changing this forces a new Environment to be created.
+        The ID of the project in which to create the resource.
         """
         return pulumi.get(self, "project_id")
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_agent_queue.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_agent_queue.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_area.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_area.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_build_definition.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_build_definition.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_client_config.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_client_config.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_git_repository.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_git_repository.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_group.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_group.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_groups.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_groups.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_iteration.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_iteration.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_pool.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_pool.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_pools.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_pools.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_project.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_project.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_projects.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_projects.py`

 * *Files 4% similar despite different names*

```diff
@@ -103,14 +103,16 @@
     ## Relevant Links
 
     - [Azure DevOps Service REST API 6.0 - Projects - Get](https://docs.microsoft.com/en-us/rest/api/azure/devops/core/projects/get?view=azure-devops-rest-6.0)
 
 
     :param str name: Name of the Project, if not specified all projects will be returned.
     :param str state: State of the Project, if not specified all projects will be returned. Valid values are `all`, `deleting`, `new`, `wellFormed`, `createPending`, `unchanged`,`deleted`.
+           
+           DataSource without specifying any arguments will return all projects.
     """
     __args__ = dict()
     __args__['name'] = name
     __args__['state'] = state
     opts = pulumi.InvokeOptions.merge(_utilities.get_invoke_opts_defaults(), opts)
     __ret__ = pulumi.runtime.invoke('azuredevops:index/getProjects:getProjects', __args__, opts=opts, typ=GetProjectsResult).value
 
@@ -144,9 +146,11 @@
     ## Relevant Links
 
     - [Azure DevOps Service REST API 6.0 - Projects - Get](https://docs.microsoft.com/en-us/rest/api/azure/devops/core/projects/get?view=azure-devops-rest-6.0)
 
 
     :param str name: Name of the Project, if not specified all projects will be returned.
     :param str state: State of the Project, if not specified all projects will be returned. Valid values are `all`, `deleting`, `new`, `wellFormed`, `createPending`, `unchanged`,`deleted`.
+           
+           DataSource without specifying any arguments will return all projects.
     """
     ...
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_repositories.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_repositories.py`

 * *Files 4% similar despite different names*

```diff
@@ -111,14 +111,15 @@
         name="Example Repository")
     ```
     ## Relevant Links
 
     - [Azure DevOps Service REST API 6.0 - Git API](https://docs.microsoft.com/en-us/rest/api/azure/devops/git/?view=azure-devops-rest-6.0)
 
 
+    :param bool include_hidden: DataSource without specifying any arguments will return all Git repositories of an organization.
     :param str name: Name of the Git repository to retrieve; requires `project_id` to be specified as well
     :param str project_id: ID of project to list Git repositories
     """
     __args__ = dict()
     __args__['includeHidden'] = include_hidden
     __args__['name'] = name
     __args__['projectId'] = project_id
@@ -155,11 +156,12 @@
         name="Example Repository")
     ```
     ## Relevant Links
 
     - [Azure DevOps Service REST API 6.0 - Git API](https://docs.microsoft.com/en-us/rest/api/azure/devops/git/?view=azure-devops-rest-6.0)
 
 
+    :param bool include_hidden: DataSource without specifying any arguments will return all Git repositories of an organization.
     :param str name: Name of the Git repository to retrieve; requires `project_id` to be specified as well
     :param str project_id: ID of project to list Git repositories
     """
     ...
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_service_endpoint_azure_rm.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_service_endpoint_azure_rm.py`

 * *Files 2% similar despite different names*

```diff
@@ -198,14 +198,17 @@
     pulumi.export("serviceEndpointId", serviceendpoint.id)
     ```
 
 
     :param str project_id: The ID of the project.
     :param str service_endpoint_id: the ID of the Service Endpoint.
     :param str service_endpoint_name: the Name of the Service Endpoint.
+           
+           > **NOTE:** One of either `service_endpoint_id` or `service_endpoint_name` must be specified.
+           > **NOTE:** When supplying `service_endpoint_name`, take care to ensure that this is a unique name.
     """
     __args__ = dict()
     __args__['projectId'] = project_id
     __args__['serviceEndpointId'] = service_endpoint_id
     __args__['serviceEndpointName'] = service_endpoint_name
     opts = pulumi.InvokeOptions.merge(_utilities.get_invoke_opts_defaults(), opts)
     __ret__ = pulumi.runtime.invoke('azuredevops:index/getServiceEndpointAzureRM:getServiceEndpointAzureRM', __args__, opts=opts, typ=GetServiceEndpointAzureRMResult).value
@@ -257,9 +260,12 @@
     pulumi.export("serviceEndpointId", serviceendpoint.id)
     ```
 
 
     :param str project_id: The ID of the project.
     :param str service_endpoint_id: the ID of the Service Endpoint.
     :param str service_endpoint_name: the Name of the Service Endpoint.
+           
+           > **NOTE:** One of either `service_endpoint_id` or `service_endpoint_name` must be specified.
+           > **NOTE:** When supplying `service_endpoint_name`, take care to ensure that this is a unique name.
     """
     ...
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_service_endpoint_github.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_service_endpoint_github.py`

 * *Files 3% similar despite different names*

```diff
@@ -126,14 +126,17 @@
     pulumi.export("serviceEndpointId", serviceendpoint.id)
     ```
 
 
     :param str project_id: The ID of the project.
     :param str service_endpoint_id: the ID of the Service Endpoint.
     :param str service_endpoint_name: the Name of the Service Endpoint.
+           
+           > **NOTE:** One of either `service_endpoint_id` or `service_endpoint_name` must be specified.
+           > **NOTE:** When supplying `service_endpoint_name`, take care to ensure that this is a unique name.
     """
     __args__ = dict()
     __args__['projectId'] = project_id
     __args__['serviceEndpointId'] = service_endpoint_id
     __args__['serviceEndpointName'] = service_endpoint_name
     opts = pulumi.InvokeOptions.merge(_utilities.get_invoke_opts_defaults(), opts)
     __ret__ = pulumi.runtime.invoke('azuredevops:index/getServiceEndpointGithub:getServiceEndpointGithub', __args__, opts=opts, typ=GetServiceEndpointGithubResult).value
@@ -179,9 +182,12 @@
     pulumi.export("serviceEndpointId", serviceendpoint.id)
     ```
 
 
     :param str project_id: The ID of the project.
     :param str service_endpoint_id: the ID of the Service Endpoint.
     :param str service_endpoint_name: the Name of the Service Endpoint.
+           
+           > **NOTE:** One of either `service_endpoint_id` or `service_endpoint_name` must be specified.
+           > **NOTE:** When supplying `service_endpoint_name`, take care to ensure that this is a unique name.
     """
     ...
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_team.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_team.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_teams.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_teams.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_users.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_users.py`

 * *Files 6% similar despite different names*

```diff
@@ -129,14 +129,28 @@
     ## Relevant Links
 
     - [Azure DevOps Service REST API 6.0 - Graph Users API](https://docs.microsoft.com/en-us/rest/api/azure/devops/graph/users?view=azure-devops-rest-6.0)
 
 
     :param str origin: The type of source provider for the `origin_id` parameter (ex:AD, AAD, MSA) The supported origins are listed below.
     :param str origin_id: The unique identifier from the system of origin.
+           
+           DataSource without specifying any arguments will return all users inside an organization.
+           
+           List of possible subject types
+           
+           ```python
+           import pulumi
+           ```
+           
+           List of possible origins
+           
+           ```python
+           import pulumi
+           ```
     :param str principal_name: The PrincipalName of this graph member from the source provider.
     :param Sequence[str] subject_types: A list of user subject subtypes to reduce the retrieved results, e.g. `msa`, `aad`, `svc` (service identity), `imp` (imported identity), etc. The supported subject types are listed below.
     """
     __args__ = dict()
     __args__['origin'] = origin
     __args__['originId'] = origin_id
     __args__['principalName'] = principal_name
@@ -181,11 +195,25 @@
     ## Relevant Links
 
     - [Azure DevOps Service REST API 6.0 - Graph Users API](https://docs.microsoft.com/en-us/rest/api/azure/devops/graph/users?view=azure-devops-rest-6.0)
 
 
     :param str origin: The type of source provider for the `origin_id` parameter (ex:AD, AAD, MSA) The supported origins are listed below.
     :param str origin_id: The unique identifier from the system of origin.
+           
+           DataSource without specifying any arguments will return all users inside an organization.
+           
+           List of possible subject types
+           
+           ```python
+           import pulumi
+           ```
+           
+           List of possible origins
+           
+           ```python
+           import pulumi
+           ```
     :param str principal_name: The PrincipalName of this graph member from the source provider.
     :param Sequence[str] subject_types: A list of user subject subtypes to reduce the retrieved results, e.g. `msa`, `aad`, `svc` (service identity), `imp` (imported identity), etc. The supported subject types are listed below.
     """
     ...
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/get_variable_group.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/get_variable_group.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/git.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/git.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/git_permissions.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/work_item_query_permissions.py`

 * *Files 15% similar despite different names*

```diff
@@ -5,49 +5,59 @@
 import copy
 import warnings
 import pulumi
 import pulumi.runtime
 from typing import Any, Mapping, Optional, Sequence, Union, overload
 from . import _utilities
 
-__all__ = ['GitPermissionsArgs', 'GitPermissions']
+__all__ = ['WorkItemQueryPermissionsArgs', 'WorkItemQueryPermissions']
 
 @pulumi.input_type
-class GitPermissionsArgs:
+class WorkItemQueryPermissionsArgs:
     def __init__(__self__, *,
                  permissions: pulumi.Input[Mapping[str, pulumi.Input[str]]],
                  principal: pulumi.Input[str],
                  project_id: pulumi.Input[str],
-                 branch_name: Optional[pulumi.Input[str]] = None,
-                 replace: Optional[pulumi.Input[bool]] = None,
-                 repository_id: Optional[pulumi.Input[str]] = None):
+                 path: Optional[pulumi.Input[str]] = None,
+                 replace: Optional[pulumi.Input[bool]] = None):
         """
-        The set of arguments for constructing a GitPermissions resource.
-        :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The follwing permissions are available
+        The set of arguments for constructing a WorkItemQueryPermissions resource.
+        :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available
+               
+               | Permissions              | Description                        |
+               |--------------------------|------------------------------------|
+               | Read                     | Read                               |
+               | Contribute               | Contribute                         |
+               | Delete                   | Delete                             |
+               | ManagePermissions        | Manage Permissions                 |
         :param pulumi.Input[str] principal: The **group** principal to assign the permissions.
         :param pulumi.Input[str] project_id: The ID of the project to assign the permissions.
-        :param pulumi.Input[str] branch_name: The name of the branch to assign the permissions.
+        :param pulumi.Input[str] path: Path to a query or folder beneath `Shared Queries`
         :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
-        :param pulumi.Input[str] repository_id: The ID of the GIT repository to assign the permissions
         """
         pulumi.set(__self__, "permissions", permissions)
         pulumi.set(__self__, "principal", principal)
         pulumi.set(__self__, "project_id", project_id)
-        if branch_name is not None:
-            pulumi.set(__self__, "branch_name", branch_name)
+        if path is not None:
+            pulumi.set(__self__, "path", path)
         if replace is not None:
             pulumi.set(__self__, "replace", replace)
-        if repository_id is not None:
-            pulumi.set(__self__, "repository_id", repository_id)
 
     @property
     @pulumi.getter
     def permissions(self) -> pulumi.Input[Mapping[str, pulumi.Input[str]]]:
         """
-        the permissions to assign. The follwing permissions are available
+        the permissions to assign. The following permissions are available
+
+        | Permissions              | Description                        |
+        |--------------------------|------------------------------------|
+        | Read                     | Read                               |
+        | Contribute               | Contribute                         |
+        | Delete                   | Delete                             |
+        | ManagePermissions        | Manage Permissions                 |
         """
         return pulumi.get(self, "permissions")
 
     @permissions.setter
     def permissions(self, value: pulumi.Input[Mapping[str, pulumi.Input[str]]]):
         pulumi.set(self, "permissions", value)
 
@@ -72,98 +82,96 @@
         return pulumi.get(self, "project_id")
 
     @project_id.setter
     def project_id(self, value: pulumi.Input[str]):
         pulumi.set(self, "project_id", value)
 
     @property
-    @pulumi.getter(name="branchName")
-    def branch_name(self) -> Optional[pulumi.Input[str]]:
+    @pulumi.getter
+    def path(self) -> Optional[pulumi.Input[str]]:
         """
-        The name of the branch to assign the permissions.
+        Path to a query or folder beneath `Shared Queries`
         """
-        return pulumi.get(self, "branch_name")
+        return pulumi.get(self, "path")
 
-    @branch_name.setter
-    def branch_name(self, value: Optional[pulumi.Input[str]]):
-        pulumi.set(self, "branch_name", value)
+    @path.setter
+    def path(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "path", value)
 
     @property
     @pulumi.getter
     def replace(self) -> Optional[pulumi.Input[bool]]:
         """
         Replace (`true`) or merge (`false`) the permissions. Default: `true`
         """
         return pulumi.get(self, "replace")
 
     @replace.setter
     def replace(self, value: Optional[pulumi.Input[bool]]):
         pulumi.set(self, "replace", value)
 
-    @property
-    @pulumi.getter(name="repositoryId")
-    def repository_id(self) -> Optional[pulumi.Input[str]]:
-        """
-        The ID of the GIT repository to assign the permissions
-        """
-        return pulumi.get(self, "repository_id")
-
-    @repository_id.setter
-    def repository_id(self, value: Optional[pulumi.Input[str]]):
-        pulumi.set(self, "repository_id", value)
-
 
 @pulumi.input_type
-class _GitPermissionsState:
+class _WorkItemQueryPermissionsState:
     def __init__(__self__, *,
-                 branch_name: Optional[pulumi.Input[str]] = None,
+                 path: Optional[pulumi.Input[str]] = None,
                  permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
                  principal: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
-                 replace: Optional[pulumi.Input[bool]] = None,
-                 repository_id: Optional[pulumi.Input[str]] = None):
+                 replace: Optional[pulumi.Input[bool]] = None):
         """
-        Input properties used for looking up and filtering GitPermissions resources.
-        :param pulumi.Input[str] branch_name: The name of the branch to assign the permissions.
-        :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The follwing permissions are available
+        Input properties used for looking up and filtering WorkItemQueryPermissions resources.
+        :param pulumi.Input[str] path: Path to a query or folder beneath `Shared Queries`
+        :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available
+               
+               | Permissions              | Description                        |
+               |--------------------------|------------------------------------|
+               | Read                     | Read                               |
+               | Contribute               | Contribute                         |
+               | Delete                   | Delete                             |
+               | ManagePermissions        | Manage Permissions                 |
         :param pulumi.Input[str] principal: The **group** principal to assign the permissions.
         :param pulumi.Input[str] project_id: The ID of the project to assign the permissions.
         :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
-        :param pulumi.Input[str] repository_id: The ID of the GIT repository to assign the permissions
         """
-        if branch_name is not None:
-            pulumi.set(__self__, "branch_name", branch_name)
+        if path is not None:
+            pulumi.set(__self__, "path", path)
         if permissions is not None:
             pulumi.set(__self__, "permissions", permissions)
         if principal is not None:
             pulumi.set(__self__, "principal", principal)
         if project_id is not None:
             pulumi.set(__self__, "project_id", project_id)
         if replace is not None:
             pulumi.set(__self__, "replace", replace)
-        if repository_id is not None:
-            pulumi.set(__self__, "repository_id", repository_id)
 
     @property
-    @pulumi.getter(name="branchName")
-    def branch_name(self) -> Optional[pulumi.Input[str]]:
+    @pulumi.getter
+    def path(self) -> Optional[pulumi.Input[str]]:
         """
-        The name of the branch to assign the permissions.
+        Path to a query or folder beneath `Shared Queries`
         """
-        return pulumi.get(self, "branch_name")
+        return pulumi.get(self, "path")
 
-    @branch_name.setter
-    def branch_name(self, value: Optional[pulumi.Input[str]]):
-        pulumi.set(self, "branch_name", value)
+    @path.setter
+    def path(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "path", value)
 
     @property
     @pulumi.getter
     def permissions(self) -> Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]:
         """
-        the permissions to assign. The follwing permissions are available
+        the permissions to assign. The following permissions are available
+
+        | Permissions              | Description                        |
+        |--------------------------|------------------------------------|
+        | Read                     | Read                               |
+        | Contribute               | Contribute                         |
+        | Delete                   | Delete                             |
+        | ManagePermissions        | Manage Permissions                 |
         """
         return pulumi.get(self, "permissions")
 
     @permissions.setter
     def permissions(self, value: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]):
         pulumi.set(self, "permissions", value)
 
@@ -199,190 +207,124 @@
         """
         return pulumi.get(self, "replace")
 
     @replace.setter
     def replace(self, value: Optional[pulumi.Input[bool]]):
         pulumi.set(self, "replace", value)
 
-    @property
-    @pulumi.getter(name="repositoryId")
-    def repository_id(self) -> Optional[pulumi.Input[str]]:
-        """
-        The ID of the GIT repository to assign the permissions
-        """
-        return pulumi.get(self, "repository_id")
-
-    @repository_id.setter
-    def repository_id(self, value: Optional[pulumi.Input[str]]):
-        pulumi.set(self, "repository_id", value)
 
-
-class GitPermissions(pulumi.CustomResource):
+class WorkItemQueryPermissions(pulumi.CustomResource):
     @overload
     def __init__(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
-                 branch_name: Optional[pulumi.Input[str]] = None,
+                 path: Optional[pulumi.Input[str]] = None,
                  permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
                  principal: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  replace: Optional[pulumi.Input[bool]] = None,
-                 repository_id: Optional[pulumi.Input[str]] = None,
                  __props__=None):
         """
-        Manages permissions for Git repositories.
+        Manages permissions for Work Item Queries.
 
         > **Note** Permissions can be assigned to group principals and not to single user principals.
 
         ## Permission levels
 
-        Permission for Git Repositories within Azure DevOps can be applied on three different levels.
-        Those levels are reflected by specifying (or omitting) values for the arguments `project_id`, `repository_id` and `branch_name`.
+        Permission for Work Item Queries within Azure DevOps can be applied on two different levels.
+        Those levels are reflected by specifying (or omitting) values for the arguments `project_id` and `path`.
 
         ### Project level
 
-        Permissions for all Git Repositories inside a project (existing or newly created ones) are specified, if only the argument `project_id` has a value.
+        Permissions for all Work Item Queries inside a project (existing or newly created ones) are specified, if only the argument `project_id` has a value.
 
         #### Example usage
 
         ```python
         import pulumi
         import pulumi_azuredevops as azuredevops
 
         example = azuredevops.Project("example",
             work_item_template="Agile",
             version_control="Git",
             visibility="private",
             description="Managed by Terraform")
         example_readers = azuredevops.get_group_output(project_id=example.id,
             name="Readers")
-        example_permissions = azuredevops.GitPermissions("example-permissions",
+        project_wiq_root_permissions = azuredevops.WorkItemQueryPermissions("project-wiq-root-permissions",
             project_id=example.id,
             principal=example_readers.id,
             permissions={
                 "CreateRepository": "Deny",
                 "DeleteRepository": "Deny",
                 "RenameRepository": "NotSet",
             })
         ```
 
-        ### Repository level
-
-        Permissions for a specific Git Repository and all existing or newly created branches are specified if the arguments `project_id` and `repository_id` are set.
-
-        #### Example usage
-
-        ```python
-        import pulumi
-        import pulumi_azuredevops as azuredevops
-
-        example_project = azuredevops.Project("exampleProject",
-            work_item_template="Agile",
-            version_control="Git",
-            visibility="private",
-            description="Managed by Terraform")
-        example_group = azuredevops.get_group(name="Project Collection Administrators")
-        example_git = azuredevops.Git("exampleGit",
-            project_id=example_project.id,
-            initialization=azuredevops.GitInitializationArgs(
-                init_type="Clean",
-            ))
-        example_permissions = azuredevops.GitPermissions("example-permissions",
-            project_id=example_git.project_id,
-            repository_id=example_git.id,
-            principal=example_group.id,
-            permissions={
-                "RemoveOthersLocks": "Allow",
-                "ManagePermissions": "Deny",
-                "CreateTag": "Deny",
-                "CreateBranch": "NotSet",
-            })
-        ```
+        ### Shared Queries folder level
 
-        ### Branch level
+        Permissions for a specific folder inside Shared Queries are specified if the arguments `project_id` and `path` are set.
 
-        Permissions for a specific branch inside a Git Repository are specified if all above mentioned the arguments are set.
+        > **Note** To set permissions for the Shared Queries folder itself use `/` as path value
 
         #### Example usage
 
         ```python
         import pulumi
         import pulumi_azuredevops as azuredevops
 
-        example_project = azuredevops.Project("exampleProject",
+        example = azuredevops.Project("example",
             work_item_template="Agile",
             version_control="Git",
             visibility="private",
             description="Managed by Terraform")
-        example_git = azuredevops.Git("exampleGit",
-            project_id=example_project.id,
-            initialization=azuredevops.GitInitializationArgs(
-                init_type="Clean",
-            ))
-        example_group = azuredevops.get_group(name="Project Collection Administrators")
-        example_permissions = azuredevops.GitPermissions("example-permissions",
-            project_id=example_git.project_id,
-            repository_id=example_git.id,
-            branch_name="refs/heads/master",
-            principal=example_group.id,
+        example_readers = azuredevops.get_group_output(project_id=example.id,
+            name="Readers")
+        example_permissions = azuredevops.WorkItemQueryPermissions("example-permissions",
+            project_id=example.id,
+            path="/Team",
+            principal=example_readers.id,
             permissions={
-                "RemoveOthersLocks": "Allow",
-                "ForcePush": "Deny",
+                "Contribute": "Allow",
+                "Delete": "Deny",
+                "Read": "NotSet",
             })
         ```
 
         ## Example Usage
 
         ```python
         import pulumi
         import pulumi_azuredevops as azuredevops
 
-        example_project = azuredevops.Project("exampleProject",
-            visibility="private",
-            version_control="Git",
+        example = azuredevops.Project("example",
             work_item_template="Agile",
+            version_control="Git",
+            visibility="private",
             description="Managed by Terraform")
-        example_project_readers = azuredevops.get_group_output(project_id=example_project.id,
+        example_readers = azuredevops.get_group_output(project_id=example.id,
             name="Readers")
-        example_project_contributors = azuredevops.get_group_output(project_id=example_project.id,
+        example_contributors = azuredevops.get_group_output(project_id=example.id,
             name="Contributors")
-        example_project_administrators = azuredevops.get_group_output(project_id=example_project.id,
-            name="Project administrators")
-        example_permissions = azuredevops.GitPermissions("example-permissions",
-            project_id=example_project.id,
-            principal=example_project_readers.id,
-            permissions={
-                "CreateRepository": "Deny",
-                "DeleteRepository": "Deny",
-                "RenameRepository": "NotSet",
-            })
-        example_git = azuredevops.Git("exampleGit",
-            project_id=example_project.id,
-            default_branch="refs/heads/master",
-            initialization=azuredevops.GitInitializationArgs(
-                init_type="Clean",
-            ))
-        example_repo_permissions = azuredevops.GitPermissions("example-repo-permissions",
-            project_id=example_git.project_id,
-            repository_id=example_git.id,
-            principal=example_project_administrators.id,
+        example_project_permissions = azuredevops.WorkItemQueryPermissions("example-project-permissions",
+            project_id=example.id,
+            principal=example_readers.id,
             permissions={
-                "RemoveOthersLocks": "Allow",
+                "Read": "Allow",
+                "Delete": "Deny",
+                "Contribute": "Deny",
                 "ManagePermissions": "Deny",
-                "CreateTag": "Deny",
-                "CreateBranch": "NotSet",
             })
-        example_branch_permissions = azuredevops.GitPermissions("example-branch-permissions",
-            project_id=example_git.project_id,
-            repository_id=example_git.id,
-            branch_name="master",
-            principal=example_project_contributors.id,
+        example_sharedqueries_permissions = azuredevops.WorkItemQueryPermissions("example-sharedqueries-permissions",
+            project_id=example.id,
+            path="/",
+            principal=example_contributors.id,
             permissions={
-                "RemoveOthersLocks": "Allow",
-                "ForcePush": "Deny",
+                "Read": "Allow",
+                "Delete": "Deny",
             })
         ```
         ## Relevant Links
 
         * [Azure DevOps Service REST API 6.0 - Security](https://docs.microsoft.com/en-us/rest/api/azure/devops/security/?view=azure-devops-rest-6.0)
 
         ## PAT Permissions Required
@@ -391,178 +333,131 @@
 
         ## Import
 
         The resource does not support import.
 
         :param str resource_name: The name of the resource.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[str] branch_name: The name of the branch to assign the permissions.
-        :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The follwing permissions are available
+        :param pulumi.Input[str] path: Path to a query or folder beneath `Shared Queries`
+        :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available
+               
+               | Permissions              | Description                        |
+               |--------------------------|------------------------------------|
+               | Read                     | Read                               |
+               | Contribute               | Contribute                         |
+               | Delete                   | Delete                             |
+               | ManagePermissions        | Manage Permissions                 |
         :param pulumi.Input[str] principal: The **group** principal to assign the permissions.
         :param pulumi.Input[str] project_id: The ID of the project to assign the permissions.
         :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
-        :param pulumi.Input[str] repository_id: The ID of the GIT repository to assign the permissions
         """
         ...
     @overload
     def __init__(__self__,
                  resource_name: str,
-                 args: GitPermissionsArgs,
+                 args: WorkItemQueryPermissionsArgs,
                  opts: Optional[pulumi.ResourceOptions] = None):
         """
-        Manages permissions for Git repositories.
+        Manages permissions for Work Item Queries.
 
         > **Note** Permissions can be assigned to group principals and not to single user principals.
 
         ## Permission levels
 
-        Permission for Git Repositories within Azure DevOps can be applied on three different levels.
-        Those levels are reflected by specifying (or omitting) values for the arguments `project_id`, `repository_id` and `branch_name`.
+        Permission for Work Item Queries within Azure DevOps can be applied on two different levels.
+        Those levels are reflected by specifying (or omitting) values for the arguments `project_id` and `path`.
 
         ### Project level
 
-        Permissions for all Git Repositories inside a project (existing or newly created ones) are specified, if only the argument `project_id` has a value.
+        Permissions for all Work Item Queries inside a project (existing or newly created ones) are specified, if only the argument `project_id` has a value.
 
         #### Example usage
 
         ```python
         import pulumi
         import pulumi_azuredevops as azuredevops
 
         example = azuredevops.Project("example",
             work_item_template="Agile",
             version_control="Git",
             visibility="private",
             description="Managed by Terraform")
         example_readers = azuredevops.get_group_output(project_id=example.id,
             name="Readers")
-        example_permissions = azuredevops.GitPermissions("example-permissions",
+        project_wiq_root_permissions = azuredevops.WorkItemQueryPermissions("project-wiq-root-permissions",
             project_id=example.id,
             principal=example_readers.id,
             permissions={
                 "CreateRepository": "Deny",
                 "DeleteRepository": "Deny",
                 "RenameRepository": "NotSet",
             })
         ```
 
-        ### Repository level
-
-        Permissions for a specific Git Repository and all existing or newly created branches are specified if the arguments `project_id` and `repository_id` are set.
+        ### Shared Queries folder level
 
-        #### Example usage
+        Permissions for a specific folder inside Shared Queries are specified if the arguments `project_id` and `path` are set.
 
-        ```python
-        import pulumi
-        import pulumi_azuredevops as azuredevops
-
-        example_project = azuredevops.Project("exampleProject",
-            work_item_template="Agile",
-            version_control="Git",
-            visibility="private",
-            description="Managed by Terraform")
-        example_group = azuredevops.get_group(name="Project Collection Administrators")
-        example_git = azuredevops.Git("exampleGit",
-            project_id=example_project.id,
-            initialization=azuredevops.GitInitializationArgs(
-                init_type="Clean",
-            ))
-        example_permissions = azuredevops.GitPermissions("example-permissions",
-            project_id=example_git.project_id,
-            repository_id=example_git.id,
-            principal=example_group.id,
-            permissions={
-                "RemoveOthersLocks": "Allow",
-                "ManagePermissions": "Deny",
-                "CreateTag": "Deny",
-                "CreateBranch": "NotSet",
-            })
-        ```
-
-        ### Branch level
-
-        Permissions for a specific branch inside a Git Repository are specified if all above mentioned the arguments are set.
+        > **Note** To set permissions for the Shared Queries folder itself use `/` as path value
 
         #### Example usage
 
         ```python
         import pulumi
         import pulumi_azuredevops as azuredevops
 
-        example_project = azuredevops.Project("exampleProject",
+        example = azuredevops.Project("example",
             work_item_template="Agile",
             version_control="Git",
             visibility="private",
             description="Managed by Terraform")
-        example_git = azuredevops.Git("exampleGit",
-            project_id=example_project.id,
-            initialization=azuredevops.GitInitializationArgs(
-                init_type="Clean",
-            ))
-        example_group = azuredevops.get_group(name="Project Collection Administrators")
-        example_permissions = azuredevops.GitPermissions("example-permissions",
-            project_id=example_git.project_id,
-            repository_id=example_git.id,
-            branch_name="refs/heads/master",
-            principal=example_group.id,
+        example_readers = azuredevops.get_group_output(project_id=example.id,
+            name="Readers")
+        example_permissions = azuredevops.WorkItemQueryPermissions("example-permissions",
+            project_id=example.id,
+            path="/Team",
+            principal=example_readers.id,
             permissions={
-                "RemoveOthersLocks": "Allow",
-                "ForcePush": "Deny",
+                "Contribute": "Allow",
+                "Delete": "Deny",
+                "Read": "NotSet",
             })
         ```
 
         ## Example Usage
 
         ```python
         import pulumi
         import pulumi_azuredevops as azuredevops
 
-        example_project = azuredevops.Project("exampleProject",
-            visibility="private",
-            version_control="Git",
+        example = azuredevops.Project("example",
             work_item_template="Agile",
+            version_control="Git",
+            visibility="private",
             description="Managed by Terraform")
-        example_project_readers = azuredevops.get_group_output(project_id=example_project.id,
+        example_readers = azuredevops.get_group_output(project_id=example.id,
             name="Readers")
-        example_project_contributors = azuredevops.get_group_output(project_id=example_project.id,
+        example_contributors = azuredevops.get_group_output(project_id=example.id,
             name="Contributors")
-        example_project_administrators = azuredevops.get_group_output(project_id=example_project.id,
-            name="Project administrators")
-        example_permissions = azuredevops.GitPermissions("example-permissions",
-            project_id=example_project.id,
-            principal=example_project_readers.id,
-            permissions={
-                "CreateRepository": "Deny",
-                "DeleteRepository": "Deny",
-                "RenameRepository": "NotSet",
-            })
-        example_git = azuredevops.Git("exampleGit",
-            project_id=example_project.id,
-            default_branch="refs/heads/master",
-            initialization=azuredevops.GitInitializationArgs(
-                init_type="Clean",
-            ))
-        example_repo_permissions = azuredevops.GitPermissions("example-repo-permissions",
-            project_id=example_git.project_id,
-            repository_id=example_git.id,
-            principal=example_project_administrators.id,
+        example_project_permissions = azuredevops.WorkItemQueryPermissions("example-project-permissions",
+            project_id=example.id,
+            principal=example_readers.id,
             permissions={
-                "RemoveOthersLocks": "Allow",
+                "Read": "Allow",
+                "Delete": "Deny",
+                "Contribute": "Deny",
                 "ManagePermissions": "Deny",
-                "CreateTag": "Deny",
-                "CreateBranch": "NotSet",
             })
-        example_branch_permissions = azuredevops.GitPermissions("example-branch-permissions",
-            project_id=example_git.project_id,
-            repository_id=example_git.id,
-            branch_name="master",
-            principal=example_project_contributors.id,
+        example_sharedqueries_permissions = azuredevops.WorkItemQueryPermissions("example-sharedqueries-permissions",
+            project_id=example.id,
+            path="/",
+            principal=example_contributors.id,
             permissions={
-                "RemoveOthersLocks": "Allow",
-                "ForcePush": "Deny",
+                "Read": "Allow",
+                "Delete": "Deny",
             })
         ```
         ## Relevant Links
 
         * [Azure DevOps Service REST API 6.0 - Security](https://docs.microsoft.com/en-us/rest/api/azure/devops/security/?view=azure-devops-rest-6.0)
 
         ## PAT Permissions Required
@@ -570,110 +465,119 @@
         - **Project & Team**: vso.security_manage - Grants the ability to read, write, and manage security permissions.
 
         ## Import
 
         The resource does not support import.
 
         :param str resource_name: The name of the resource.
-        :param GitPermissionsArgs args: The arguments to use to populate this resource's properties.
+        :param WorkItemQueryPermissionsArgs args: The arguments to use to populate this resource's properties.
         :param pulumi.ResourceOptions opts: Options for the resource.
         """
         ...
     def __init__(__self__, resource_name: str, *args, **kwargs):
-        resource_args, opts = _utilities.get_resource_args_opts(GitPermissionsArgs, pulumi.ResourceOptions, *args, **kwargs)
+        resource_args, opts = _utilities.get_resource_args_opts(WorkItemQueryPermissionsArgs, pulumi.ResourceOptions, *args, **kwargs)
         if resource_args is not None:
             __self__._internal_init(resource_name, opts, **resource_args.__dict__)
         else:
             __self__._internal_init(resource_name, *args, **kwargs)
 
     def _internal_init(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
-                 branch_name: Optional[pulumi.Input[str]] = None,
+                 path: Optional[pulumi.Input[str]] = None,
                  permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
                  principal: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  replace: Optional[pulumi.Input[bool]] = None,
-                 repository_id: Optional[pulumi.Input[str]] = None,
                  __props__=None):
         opts = pulumi.ResourceOptions.merge(_utilities.get_resource_opts_defaults(), opts)
         if not isinstance(opts, pulumi.ResourceOptions):
             raise TypeError('Expected resource options to be a ResourceOptions instance')
         if opts.id is None:
             if __props__ is not None:
                 raise TypeError('__props__ is only valid when passed in combination with a valid opts.id to get an existing resource')
-            __props__ = GitPermissionsArgs.__new__(GitPermissionsArgs)
+            __props__ = WorkItemQueryPermissionsArgs.__new__(WorkItemQueryPermissionsArgs)
 
-            __props__.__dict__["branch_name"] = branch_name
+            __props__.__dict__["path"] = path
             if permissions is None and not opts.urn:
                 raise TypeError("Missing required property 'permissions'")
             __props__.__dict__["permissions"] = permissions
             if principal is None and not opts.urn:
                 raise TypeError("Missing required property 'principal'")
             __props__.__dict__["principal"] = principal
             if project_id is None and not opts.urn:
                 raise TypeError("Missing required property 'project_id'")
             __props__.__dict__["project_id"] = project_id
             __props__.__dict__["replace"] = replace
-            __props__.__dict__["repository_id"] = repository_id
-        super(GitPermissions, __self__).__init__(
-            'azuredevops:index/gitPermissions:GitPermissions',
+        super(WorkItemQueryPermissions, __self__).__init__(
+            'azuredevops:index/workItemQueryPermissions:WorkItemQueryPermissions',
             resource_name,
             __props__,
             opts)
 
     @staticmethod
     def get(resource_name: str,
             id: pulumi.Input[str],
             opts: Optional[pulumi.ResourceOptions] = None,
-            branch_name: Optional[pulumi.Input[str]] = None,
+            path: Optional[pulumi.Input[str]] = None,
             permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
             principal: Optional[pulumi.Input[str]] = None,
             project_id: Optional[pulumi.Input[str]] = None,
-            replace: Optional[pulumi.Input[bool]] = None,
-            repository_id: Optional[pulumi.Input[str]] = None) -> 'GitPermissions':
+            replace: Optional[pulumi.Input[bool]] = None) -> 'WorkItemQueryPermissions':
         """
-        Get an existing GitPermissions resource's state with the given name, id, and optional extra
+        Get an existing WorkItemQueryPermissions resource's state with the given name, id, and optional extra
         properties used to qualify the lookup.
 
         :param str resource_name: The unique name of the resulting resource.
         :param pulumi.Input[str] id: The unique provider ID of the resource to lookup.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[str] branch_name: The name of the branch to assign the permissions.
-        :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The follwing permissions are available
+        :param pulumi.Input[str] path: Path to a query or folder beneath `Shared Queries`
+        :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available
+               
+               | Permissions              | Description                        |
+               |--------------------------|------------------------------------|
+               | Read                     | Read                               |
+               | Contribute               | Contribute                         |
+               | Delete                   | Delete                             |
+               | ManagePermissions        | Manage Permissions                 |
         :param pulumi.Input[str] principal: The **group** principal to assign the permissions.
         :param pulumi.Input[str] project_id: The ID of the project to assign the permissions.
         :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
-        :param pulumi.Input[str] repository_id: The ID of the GIT repository to assign the permissions
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
 
-        __props__ = _GitPermissionsState.__new__(_GitPermissionsState)
+        __props__ = _WorkItemQueryPermissionsState.__new__(_WorkItemQueryPermissionsState)
 
-        __props__.__dict__["branch_name"] = branch_name
+        __props__.__dict__["path"] = path
         __props__.__dict__["permissions"] = permissions
         __props__.__dict__["principal"] = principal
         __props__.__dict__["project_id"] = project_id
         __props__.__dict__["replace"] = replace
-        __props__.__dict__["repository_id"] = repository_id
-        return GitPermissions(resource_name, opts=opts, __props__=__props__)
+        return WorkItemQueryPermissions(resource_name, opts=opts, __props__=__props__)
 
     @property
-    @pulumi.getter(name="branchName")
-    def branch_name(self) -> pulumi.Output[Optional[str]]:
+    @pulumi.getter
+    def path(self) -> pulumi.Output[Optional[str]]:
         """
-        The name of the branch to assign the permissions.
+        Path to a query or folder beneath `Shared Queries`
         """
-        return pulumi.get(self, "branch_name")
+        return pulumi.get(self, "path")
 
     @property
     @pulumi.getter
     def permissions(self) -> pulumi.Output[Mapping[str, str]]:
         """
-        the permissions to assign. The follwing permissions are available
+        the permissions to assign. The following permissions are available
+
+        | Permissions              | Description                        |
+        |--------------------------|------------------------------------|
+        | Read                     | Read                               |
+        | Contribute               | Contribute                         |
+        | Delete                   | Delete                             |
+        | ManagePermissions        | Manage Permissions                 |
         """
         return pulumi.get(self, "permissions")
 
     @property
     @pulumi.getter
     def principal(self) -> pulumi.Output[str]:
         """
@@ -693,15 +597,7 @@
     @pulumi.getter
     def replace(self) -> pulumi.Output[Optional[bool]]:
         """
         Replace (`true`) or merge (`false`) the permissions. Default: `true`
         """
         return pulumi.get(self, "replace")
 
-    @property
-    @pulumi.getter(name="repositoryId")
-    def repository_id(self) -> pulumi.Output[Optional[str]]:
-        """
-        The ID of the GIT repository to assign the permissions
-        """
-        return pulumi.get(self, "repository_id")
-
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/git_repository_branch.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/git_repository_branch.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/git_repository_file.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/git_repository_file.py`

 * *Files 2% similar despite different names*

```diff
@@ -260,15 +260,15 @@
         ```
         ## Relevant Links
 
         - [Azure DevOps Service REST API 6.0 - Git API](https://docs.microsoft.com/en-us/rest/api/azure/devops/git/?view=azure-devops-rest-6.0)
 
         ## Import
 
-        Repository files can be imported using a combination of the `repositroy ID` and `file`, e.g.
+        Repository files can be imported using a combination of the `repository ID` and `file`, e.g.
 
         ```sh
          $ pulumi import azuredevops:index/gitRepositoryFile:GitRepositoryFile example 00000000-0000-0000-0000-000000000000/.gitignore
         ```
 
          To import a file from a branch other than `master`, append `:` and the branch name, e.g.
 
@@ -320,15 +320,15 @@
         ```
         ## Relevant Links
 
         - [Azure DevOps Service REST API 6.0 - Git API](https://docs.microsoft.com/en-us/rest/api/azure/devops/git/?view=azure-devops-rest-6.0)
 
         ## Import
 
-        Repository files can be imported using a combination of the `repositroy ID` and `file`, e.g.
+        Repository files can be imported using a combination of the `repository ID` and `file`, e.g.
 
         ```sh
          $ pulumi import azuredevops:index/gitRepositoryFile:GitRepositoryFile example 00000000-0000-0000-0000-000000000000/.gitignore
         ```
 
          To import a file from a branch other than `master`, append `:` and the branch name, e.g.
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/group.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/group.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/group_membership.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/group_membership.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/identities/get_group.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/identities/get_group.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/identities/get_users.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/identities/get_users.py`

 * *Files 7% similar despite different names*

```diff
@@ -131,14 +131,28 @@
     ## Relevant Links
 
     - [Azure DevOps Service REST API 6.0 - Graph Users API](https://docs.microsoft.com/en-us/rest/api/azure/devops/graph/users?view=azure-devops-rest-6.0)
 
 
     :param str origin: The type of source provider for the `origin_id` parameter (ex:AD, AAD, MSA) The supported origins are listed below.
     :param str origin_id: The unique identifier from the system of origin.
+           
+           DataSource without specifying any arguments will return all users inside an organization.
+           
+           List of possible subject types
+           
+           ```python
+           import pulumi
+           ```
+           
+           List of possible origins
+           
+           ```python
+           import pulumi
+           ```
     :param str principal_name: The PrincipalName of this graph member from the source provider.
     :param Sequence[str] subject_types: A list of user subject subtypes to reduce the retrieved results, e.g. `msa`, `aad`, `svc` (service identity), `imp` (imported identity), etc. The supported subject types are listed below.
     """
     pulumi.log.warn("""get_users is deprecated: azuredevops.identities.getUsers has been deprecated in favor of azuredevops.getUsers""")
     __args__ = dict()
     __args__['origin'] = origin
     __args__['originId'] = origin_id
@@ -184,12 +198,26 @@
     ## Relevant Links
 
     - [Azure DevOps Service REST API 6.0 - Graph Users API](https://docs.microsoft.com/en-us/rest/api/azure/devops/graph/users?view=azure-devops-rest-6.0)
 
 
     :param str origin: The type of source provider for the `origin_id` parameter (ex:AD, AAD, MSA) The supported origins are listed below.
     :param str origin_id: The unique identifier from the system of origin.
+           
+           DataSource without specifying any arguments will return all users inside an organization.
+           
+           List of possible subject types
+           
+           ```python
+           import pulumi
+           ```
+           
+           List of possible origins
+           
+           ```python
+           import pulumi
+           ```
     :param str principal_name: The PrincipalName of this graph member from the source provider.
     :param Sequence[str] subject_types: A list of user subject subtypes to reduce the retrieved results, e.g. `msa`, `aad`, `svc` (service identity), `imp` (imported identity), etc. The supported subject types are listed below.
     """
     pulumi.log.warn("""get_users is deprecated: azuredevops.identities.getUsers has been deprecated in favor of azuredevops.getUsers""")
     ...
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/identities/group.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/identities/group.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/identities/group_membership.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/identities/group_membership.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/identities/outputs.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/identities/outputs.py`

 * *Files 12% similar despite different names*

```diff
@@ -27,14 +27,28 @@
         :param str descriptor: The descriptor is the primary way to reference the graph subject while the system is running. This field will uniquely identify the same graph subject across both Accounts and Organizations.
         :param str display_name: This is the non-unique display name of the graph subject. To change this field, you must alter its value in the source provider.
         :param str id: The user ID.
         :param str mail_address: The email address of record for a given graph member. This may be different than the principal name.
         :param str origin: The type of source provider for the `origin_id` parameter (ex:AD, AAD, MSA) The supported origins are listed below.
         :param str principal_name: The PrincipalName of this graph member from the source provider.
         :param str origin_id: The unique identifier from the system of origin.
+               
+               DataSource without specifying any arguments will return all users inside an organization.
+               
+               List of possible subject types
+               
+               ```python
+               import pulumi
+               ```
+               
+               List of possible origins
+               
+               ```python
+               import pulumi
+               ```
         """
         pulumi.set(__self__, "descriptor", descriptor)
         pulumi.set(__self__, "display_name", display_name)
         pulumi.set(__self__, "id", id)
         pulumi.set(__self__, "mail_address", mail_address)
         pulumi.set(__self__, "origin", origin)
         pulumi.set(__self__, "principal_name", principal_name)
@@ -90,11 +104,25 @@
         return pulumi.get(self, "principal_name")
 
     @property
     @pulumi.getter(name="originId")
     def origin_id(self) -> Optional[str]:
         """
         The unique identifier from the system of origin.
+
+        DataSource without specifying any arguments will return all users inside an organization.
+
+        List of possible subject types
+
+        ```python
+        import pulumi
+        ```
+
+        List of possible origins
+
+        ```python
+        import pulumi
+        ```
         """
         return pulumi.get(self, "origin_id")
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/iterative_permissions.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/resource_authorization.py`

 * *Files 24% similar despite different names*

```diff
@@ -5,432 +5,390 @@
 import copy
 import warnings
 import pulumi
 import pulumi.runtime
 from typing import Any, Mapping, Optional, Sequence, Union, overload
 from . import _utilities
 
-__all__ = ['IterativePermissionsArgs', 'IterativePermissions']
+__all__ = ['ResourceAuthorizationArgs', 'ResourceAuthorization']
 
 @pulumi.input_type
-class IterativePermissionsArgs:
+class ResourceAuthorizationArgs:
     def __init__(__self__, *,
-                 permissions: pulumi.Input[Mapping[str, pulumi.Input[str]]],
-                 principal: pulumi.Input[str],
+                 authorized: pulumi.Input[bool],
                  project_id: pulumi.Input[str],
-                 path: Optional[pulumi.Input[str]] = None,
-                 replace: Optional[pulumi.Input[bool]] = None):
+                 resource_id: pulumi.Input[str],
+                 definition_id: Optional[pulumi.Input[int]] = None,
+                 type: Optional[pulumi.Input[str]] = None):
+        """
+        The set of arguments for constructing a ResourceAuthorization resource.
+        :param pulumi.Input[bool] authorized: Set to true to allow public access in the project. Type: boolean.
+        :param pulumi.Input[str] project_id: The project ID or project name. Type: string.
+        :param pulumi.Input[str] resource_id: The ID of the resource to authorize. Type: string.
+        :param pulumi.Input[int] definition_id: The ID of the build definition to authorize. Type: string.
+        :param pulumi.Input[str] type: The type of the resource to authorize. Type: string. Valid values: `endpoint`, `queue`, `variablegroup`. Default value: `endpoint`.
         """
-        The set of arguments for constructing a IterativePermissions resource.
-        :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available.
-        :param pulumi.Input[str] principal: The **group** principal to assign the permissions.
-        :param pulumi.Input[str] project_id: The ID of the project to assign the permissions.
-        :param pulumi.Input[str] path: The name of the branch to assign the permissions.
-        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
-        """
-        pulumi.set(__self__, "permissions", permissions)
-        pulumi.set(__self__, "principal", principal)
+        pulumi.set(__self__, "authorized", authorized)
         pulumi.set(__self__, "project_id", project_id)
-        if path is not None:
-            pulumi.set(__self__, "path", path)
-        if replace is not None:
-            pulumi.set(__self__, "replace", replace)
-
-    @property
-    @pulumi.getter
-    def permissions(self) -> pulumi.Input[Mapping[str, pulumi.Input[str]]]:
-        """
-        the permissions to assign. The following permissions are available.
-        """
-        return pulumi.get(self, "permissions")
-
-    @permissions.setter
-    def permissions(self, value: pulumi.Input[Mapping[str, pulumi.Input[str]]]):
-        pulumi.set(self, "permissions", value)
+        pulumi.set(__self__, "resource_id", resource_id)
+        if definition_id is not None:
+            pulumi.set(__self__, "definition_id", definition_id)
+        if type is not None:
+            pulumi.set(__self__, "type", type)
 
     @property
     @pulumi.getter
-    def principal(self) -> pulumi.Input[str]:
+    def authorized(self) -> pulumi.Input[bool]:
         """
-        The **group** principal to assign the permissions.
+        Set to true to allow public access in the project. Type: boolean.
         """
-        return pulumi.get(self, "principal")
+        return pulumi.get(self, "authorized")
 
-    @principal.setter
-    def principal(self, value: pulumi.Input[str]):
-        pulumi.set(self, "principal", value)
+    @authorized.setter
+    def authorized(self, value: pulumi.Input[bool]):
+        pulumi.set(self, "authorized", value)
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> pulumi.Input[str]:
         """
-        The ID of the project to assign the permissions.
+        The project ID or project name. Type: string.
         """
         return pulumi.get(self, "project_id")
 
     @project_id.setter
     def project_id(self, value: pulumi.Input[str]):
         pulumi.set(self, "project_id", value)
 
     @property
-    @pulumi.getter
-    def path(self) -> Optional[pulumi.Input[str]]:
+    @pulumi.getter(name="resourceId")
+    def resource_id(self) -> pulumi.Input[str]:
         """
-        The name of the branch to assign the permissions.
+        The ID of the resource to authorize. Type: string.
         """
-        return pulumi.get(self, "path")
+        return pulumi.get(self, "resource_id")
 
-    @path.setter
-    def path(self, value: Optional[pulumi.Input[str]]):
-        pulumi.set(self, "path", value)
+    @resource_id.setter
+    def resource_id(self, value: pulumi.Input[str]):
+        pulumi.set(self, "resource_id", value)
+
+    @property
+    @pulumi.getter(name="definitionId")
+    def definition_id(self) -> Optional[pulumi.Input[int]]:
+        """
+        The ID of the build definition to authorize. Type: string.
+        """
+        return pulumi.get(self, "definition_id")
+
+    @definition_id.setter
+    def definition_id(self, value: Optional[pulumi.Input[int]]):
+        pulumi.set(self, "definition_id", value)
 
     @property
     @pulumi.getter
-    def replace(self) -> Optional[pulumi.Input[bool]]:
+    def type(self) -> Optional[pulumi.Input[str]]:
         """
-        Replace (`true`) or merge (`false`) the permissions. Default: `true`
+        The type of the resource to authorize. Type: string. Valid values: `endpoint`, `queue`, `variablegroup`. Default value: `endpoint`.
         """
-        return pulumi.get(self, "replace")
+        return pulumi.get(self, "type")
 
-    @replace.setter
-    def replace(self, value: Optional[pulumi.Input[bool]]):
-        pulumi.set(self, "replace", value)
+    @type.setter
+    def type(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "type", value)
 
 
 @pulumi.input_type
-class _IterativePermissionsState:
+class _ResourceAuthorizationState:
     def __init__(__self__, *,
-                 path: Optional[pulumi.Input[str]] = None,
-                 permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
-                 principal: Optional[pulumi.Input[str]] = None,
+                 authorized: Optional[pulumi.Input[bool]] = None,
+                 definition_id: Optional[pulumi.Input[int]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
-                 replace: Optional[pulumi.Input[bool]] = None):
+                 resource_id: Optional[pulumi.Input[str]] = None,
+                 type: Optional[pulumi.Input[str]] = None):
         """
-        Input properties used for looking up and filtering IterativePermissions resources.
-        :param pulumi.Input[str] path: The name of the branch to assign the permissions.
-        :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available.
-        :param pulumi.Input[str] principal: The **group** principal to assign the permissions.
-        :param pulumi.Input[str] project_id: The ID of the project to assign the permissions.
-        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
-        """
-        if path is not None:
-            pulumi.set(__self__, "path", path)
-        if permissions is not None:
-            pulumi.set(__self__, "permissions", permissions)
-        if principal is not None:
-            pulumi.set(__self__, "principal", principal)
+        Input properties used for looking up and filtering ResourceAuthorization resources.
+        :param pulumi.Input[bool] authorized: Set to true to allow public access in the project. Type: boolean.
+        :param pulumi.Input[int] definition_id: The ID of the build definition to authorize. Type: string.
+        :param pulumi.Input[str] project_id: The project ID or project name. Type: string.
+        :param pulumi.Input[str] resource_id: The ID of the resource to authorize. Type: string.
+        :param pulumi.Input[str] type: The type of the resource to authorize. Type: string. Valid values: `endpoint`, `queue`, `variablegroup`. Default value: `endpoint`.
+        """
+        if authorized is not None:
+            pulumi.set(__self__, "authorized", authorized)
+        if definition_id is not None:
+            pulumi.set(__self__, "definition_id", definition_id)
         if project_id is not None:
             pulumi.set(__self__, "project_id", project_id)
-        if replace is not None:
-            pulumi.set(__self__, "replace", replace)
-
-    @property
-    @pulumi.getter
-    def path(self) -> Optional[pulumi.Input[str]]:
-        """
-        The name of the branch to assign the permissions.
-        """
-        return pulumi.get(self, "path")
-
-    @path.setter
-    def path(self, value: Optional[pulumi.Input[str]]):
-        pulumi.set(self, "path", value)
+        if resource_id is not None:
+            pulumi.set(__self__, "resource_id", resource_id)
+        if type is not None:
+            pulumi.set(__self__, "type", type)
 
     @property
     @pulumi.getter
-    def permissions(self) -> Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]:
+    def authorized(self) -> Optional[pulumi.Input[bool]]:
         """
-        the permissions to assign. The following permissions are available.
+        Set to true to allow public access in the project. Type: boolean.
         """
-        return pulumi.get(self, "permissions")
+        return pulumi.get(self, "authorized")
 
-    @permissions.setter
-    def permissions(self, value: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]):
-        pulumi.set(self, "permissions", value)
+    @authorized.setter
+    def authorized(self, value: Optional[pulumi.Input[bool]]):
+        pulumi.set(self, "authorized", value)
 
     @property
-    @pulumi.getter
-    def principal(self) -> Optional[pulumi.Input[str]]:
+    @pulumi.getter(name="definitionId")
+    def definition_id(self) -> Optional[pulumi.Input[int]]:
         """
-        The **group** principal to assign the permissions.
+        The ID of the build definition to authorize. Type: string.
         """
-        return pulumi.get(self, "principal")
+        return pulumi.get(self, "definition_id")
 
-    @principal.setter
-    def principal(self, value: Optional[pulumi.Input[str]]):
-        pulumi.set(self, "principal", value)
+    @definition_id.setter
+    def definition_id(self, value: Optional[pulumi.Input[int]]):
+        pulumi.set(self, "definition_id", value)
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> Optional[pulumi.Input[str]]:
         """
-        The ID of the project to assign the permissions.
+        The project ID or project name. Type: string.
         """
         return pulumi.get(self, "project_id")
 
     @project_id.setter
     def project_id(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "project_id", value)
 
     @property
+    @pulumi.getter(name="resourceId")
+    def resource_id(self) -> Optional[pulumi.Input[str]]:
+        """
+        The ID of the resource to authorize. Type: string.
+        """
+        return pulumi.get(self, "resource_id")
+
+    @resource_id.setter
+    def resource_id(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "resource_id", value)
+
+    @property
     @pulumi.getter
-    def replace(self) -> Optional[pulumi.Input[bool]]:
+    def type(self) -> Optional[pulumi.Input[str]]:
         """
-        Replace (`true`) or merge (`false`) the permissions. Default: `true`
+        The type of the resource to authorize. Type: string. Valid values: `endpoint`, `queue`, `variablegroup`. Default value: `endpoint`.
         """
-        return pulumi.get(self, "replace")
+        return pulumi.get(self, "type")
 
-    @replace.setter
-    def replace(self, value: Optional[pulumi.Input[bool]]):
-        pulumi.set(self, "replace", value)
+    @type.setter
+    def type(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "type", value)
 
 
-class IterativePermissions(pulumi.CustomResource):
+class ResourceAuthorization(pulumi.CustomResource):
     @overload
     def __init__(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
-                 path: Optional[pulumi.Input[str]] = None,
-                 permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
-                 principal: Optional[pulumi.Input[str]] = None,
+                 authorized: Optional[pulumi.Input[bool]] = None,
+                 definition_id: Optional[pulumi.Input[int]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
-                 replace: Optional[pulumi.Input[bool]] = None,
+                 resource_id: Optional[pulumi.Input[str]] = None,
+                 type: Optional[pulumi.Input[str]] = None,
                  __props__=None):
         """
-        Manages permissions for an Iteration (Sprint)
+        Manages authorization of resources, e.g. for access in build pipelines.
 
-        > **Note** Permissions can be assigned to group principals and not to single user principals.
-
-        ## Permission levels
-
-        Permission for Iterations within Azure DevOps can be applied on two different levels.
-        Those levels are reflected by specifying (or omitting) values for the arguments `project_id` and `path`.
+        Currently supported resources: service endpoint (aka service connection, endpoint).
 
         ## Example Usage
 
         ```python
         import pulumi
         import pulumi_azuredevops as azuredevops
 
-        example = azuredevops.Project("example",
-            work_item_template="Agile",
-            version_control="Git",
+        example_project = azuredevops.Project("exampleProject",
             visibility="private",
+            version_control="Git",
+            work_item_template="Agile",
+            description="Managed by Terraform")
+        example_service_endpoint_bit_bucket = azuredevops.ServiceEndpointBitBucket("exampleServiceEndpointBitBucket",
+            project_id=example_project.id,
+            username="username",
+            password="password",
+            service_endpoint_name="example-bitbucket",
             description="Managed by Terraform")
-        example_readers = azuredevops.get_group_output(project_id=example.id,
-            name="Readers")
-        example_root_permissions = azuredevops.IterativePermissions("example-root-permissions",
-            project_id=example.id,
-            principal=example_readers.id,
-            permissions={
-                "CREATE_CHILDREN": "Deny",
-                "GENERIC_READ": "NotSet",
-                "DELETE": "Deny",
-            })
-        example_iteration_permissions = azuredevops.IterativePermissions("example-iteration-permissions",
-            project_id=example.id,
-            principal=example_readers.id,
-            path="Iteration 1",
-            permissions={
-                "CREATE_CHILDREN": "Allow",
-                "GENERIC_READ": "NotSet",
-                "DELETE": "Allow",
-            })
+        example_resource_authorization = azuredevops.ResourceAuthorization("exampleResourceAuthorization",
+            project_id=example_project.id,
+            resource_id=example_service_endpoint_bit_bucket.id,
+            authorized=True)
         ```
         ## Relevant Links
 
-        * [Azure DevOps Service REST API 6.0 - Security](https://docs.microsoft.com/en-us/rest/api/azure/devops/security/?view=azure-devops-rest-6.0)
-
-        ## PAT Permissions Required
-
-        - **Project & Team**: vso.security_manage - Grants the ability to read, write, and manage security permissions.
-
-        ## Import
-
-        The resource does not support import.
+        - [Azure DevOps Service REST API 6.0 - Authorize Definition Resource](https://docs.microsoft.com/en-us/rest/api/azure/devops/build/resources/authorize%20definition%20resources?view=azure-devops-rest-6.0)
 
         :param str resource_name: The name of the resource.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[str] path: The name of the branch to assign the permissions.
-        :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available.
-        :param pulumi.Input[str] principal: The **group** principal to assign the permissions.
-        :param pulumi.Input[str] project_id: The ID of the project to assign the permissions.
-        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
+        :param pulumi.Input[bool] authorized: Set to true to allow public access in the project. Type: boolean.
+        :param pulumi.Input[int] definition_id: The ID of the build definition to authorize. Type: string.
+        :param pulumi.Input[str] project_id: The project ID or project name. Type: string.
+        :param pulumi.Input[str] resource_id: The ID of the resource to authorize. Type: string.
+        :param pulumi.Input[str] type: The type of the resource to authorize. Type: string. Valid values: `endpoint`, `queue`, `variablegroup`. Default value: `endpoint`.
         """
         ...
     @overload
     def __init__(__self__,
                  resource_name: str,
-                 args: IterativePermissionsArgs,
+                 args: ResourceAuthorizationArgs,
                  opts: Optional[pulumi.ResourceOptions] = None):
         """
-        Manages permissions for an Iteration (Sprint)
-
-        > **Note** Permissions can be assigned to group principals and not to single user principals.
+        Manages authorization of resources, e.g. for access in build pipelines.
 
-        ## Permission levels
-
-        Permission for Iterations within Azure DevOps can be applied on two different levels.
-        Those levels are reflected by specifying (or omitting) values for the arguments `project_id` and `path`.
+        Currently supported resources: service endpoint (aka service connection, endpoint).
 
         ## Example Usage
 
         ```python
         import pulumi
         import pulumi_azuredevops as azuredevops
 
-        example = azuredevops.Project("example",
-            work_item_template="Agile",
-            version_control="Git",
+        example_project = azuredevops.Project("exampleProject",
             visibility="private",
+            version_control="Git",
+            work_item_template="Agile",
             description="Managed by Terraform")
-        example_readers = azuredevops.get_group_output(project_id=example.id,
-            name="Readers")
-        example_root_permissions = azuredevops.IterativePermissions("example-root-permissions",
-            project_id=example.id,
-            principal=example_readers.id,
-            permissions={
-                "CREATE_CHILDREN": "Deny",
-                "GENERIC_READ": "NotSet",
-                "DELETE": "Deny",
-            })
-        example_iteration_permissions = azuredevops.IterativePermissions("example-iteration-permissions",
-            project_id=example.id,
-            principal=example_readers.id,
-            path="Iteration 1",
-            permissions={
-                "CREATE_CHILDREN": "Allow",
-                "GENERIC_READ": "NotSet",
-                "DELETE": "Allow",
-            })
+        example_service_endpoint_bit_bucket = azuredevops.ServiceEndpointBitBucket("exampleServiceEndpointBitBucket",
+            project_id=example_project.id,
+            username="username",
+            password="password",
+            service_endpoint_name="example-bitbucket",
+            description="Managed by Terraform")
+        example_resource_authorization = azuredevops.ResourceAuthorization("exampleResourceAuthorization",
+            project_id=example_project.id,
+            resource_id=example_service_endpoint_bit_bucket.id,
+            authorized=True)
         ```
         ## Relevant Links
 
-        * [Azure DevOps Service REST API 6.0 - Security](https://docs.microsoft.com/en-us/rest/api/azure/devops/security/?view=azure-devops-rest-6.0)
-
-        ## PAT Permissions Required
-
-        - **Project & Team**: vso.security_manage - Grants the ability to read, write, and manage security permissions.
-
-        ## Import
-
-        The resource does not support import.
+        - [Azure DevOps Service REST API 6.0 - Authorize Definition Resource](https://docs.microsoft.com/en-us/rest/api/azure/devops/build/resources/authorize%20definition%20resources?view=azure-devops-rest-6.0)
 
         :param str resource_name: The name of the resource.
-        :param IterativePermissionsArgs args: The arguments to use to populate this resource's properties.
+        :param ResourceAuthorizationArgs args: The arguments to use to populate this resource's properties.
         :param pulumi.ResourceOptions opts: Options for the resource.
         """
         ...
     def __init__(__self__, resource_name: str, *args, **kwargs):
-        resource_args, opts = _utilities.get_resource_args_opts(IterativePermissionsArgs, pulumi.ResourceOptions, *args, **kwargs)
+        resource_args, opts = _utilities.get_resource_args_opts(ResourceAuthorizationArgs, pulumi.ResourceOptions, *args, **kwargs)
         if resource_args is not None:
             __self__._internal_init(resource_name, opts, **resource_args.__dict__)
         else:
             __self__._internal_init(resource_name, *args, **kwargs)
 
     def _internal_init(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
-                 path: Optional[pulumi.Input[str]] = None,
-                 permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
-                 principal: Optional[pulumi.Input[str]] = None,
+                 authorized: Optional[pulumi.Input[bool]] = None,
+                 definition_id: Optional[pulumi.Input[int]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
-                 replace: Optional[pulumi.Input[bool]] = None,
+                 resource_id: Optional[pulumi.Input[str]] = None,
+                 type: Optional[pulumi.Input[str]] = None,
                  __props__=None):
         opts = pulumi.ResourceOptions.merge(_utilities.get_resource_opts_defaults(), opts)
         if not isinstance(opts, pulumi.ResourceOptions):
             raise TypeError('Expected resource options to be a ResourceOptions instance')
         if opts.id is None:
             if __props__ is not None:
                 raise TypeError('__props__ is only valid when passed in combination with a valid opts.id to get an existing resource')
-            __props__ = IterativePermissionsArgs.__new__(IterativePermissionsArgs)
+            __props__ = ResourceAuthorizationArgs.__new__(ResourceAuthorizationArgs)
 
-            __props__.__dict__["path"] = path
-            if permissions is None and not opts.urn:
-                raise TypeError("Missing required property 'permissions'")
-            __props__.__dict__["permissions"] = permissions
-            if principal is None and not opts.urn:
-                raise TypeError("Missing required property 'principal'")
-            __props__.__dict__["principal"] = principal
+            if authorized is None and not opts.urn:
+                raise TypeError("Missing required property 'authorized'")
+            __props__.__dict__["authorized"] = authorized
+            __props__.__dict__["definition_id"] = definition_id
             if project_id is None and not opts.urn:
                 raise TypeError("Missing required property 'project_id'")
             __props__.__dict__["project_id"] = project_id
-            __props__.__dict__["replace"] = replace
-        super(IterativePermissions, __self__).__init__(
-            'azuredevops:index/iterativePermissions:IterativePermissions',
+            if resource_id is None and not opts.urn:
+                raise TypeError("Missing required property 'resource_id'")
+            __props__.__dict__["resource_id"] = resource_id
+            __props__.__dict__["type"] = type
+        alias_opts = pulumi.ResourceOptions(aliases=[pulumi.Alias(type_="azuredevops:Security/resourceAuthorization:ResourceAuthorization")])
+        opts = pulumi.ResourceOptions.merge(opts, alias_opts)
+        super(ResourceAuthorization, __self__).__init__(
+            'azuredevops:index/resourceAuthorization:ResourceAuthorization',
             resource_name,
             __props__,
             opts)
 
     @staticmethod
     def get(resource_name: str,
             id: pulumi.Input[str],
             opts: Optional[pulumi.ResourceOptions] = None,
-            path: Optional[pulumi.Input[str]] = None,
-            permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
-            principal: Optional[pulumi.Input[str]] = None,
+            authorized: Optional[pulumi.Input[bool]] = None,
+            definition_id: Optional[pulumi.Input[int]] = None,
             project_id: Optional[pulumi.Input[str]] = None,
-            replace: Optional[pulumi.Input[bool]] = None) -> 'IterativePermissions':
+            resource_id: Optional[pulumi.Input[str]] = None,
+            type: Optional[pulumi.Input[str]] = None) -> 'ResourceAuthorization':
         """
-        Get an existing IterativePermissions resource's state with the given name, id, and optional extra
+        Get an existing ResourceAuthorization resource's state with the given name, id, and optional extra
         properties used to qualify the lookup.
 
         :param str resource_name: The unique name of the resulting resource.
         :param pulumi.Input[str] id: The unique provider ID of the resource to lookup.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[str] path: The name of the branch to assign the permissions.
-        :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available.
-        :param pulumi.Input[str] principal: The **group** principal to assign the permissions.
-        :param pulumi.Input[str] project_id: The ID of the project to assign the permissions.
-        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
+        :param pulumi.Input[bool] authorized: Set to true to allow public access in the project. Type: boolean.
+        :param pulumi.Input[int] definition_id: The ID of the build definition to authorize. Type: string.
+        :param pulumi.Input[str] project_id: The project ID or project name. Type: string.
+        :param pulumi.Input[str] resource_id: The ID of the resource to authorize. Type: string.
+        :param pulumi.Input[str] type: The type of the resource to authorize. Type: string. Valid values: `endpoint`, `queue`, `variablegroup`. Default value: `endpoint`.
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
 
-        __props__ = _IterativePermissionsState.__new__(_IterativePermissionsState)
+        __props__ = _ResourceAuthorizationState.__new__(_ResourceAuthorizationState)
 
-        __props__.__dict__["path"] = path
-        __props__.__dict__["permissions"] = permissions
-        __props__.__dict__["principal"] = principal
+        __props__.__dict__["authorized"] = authorized
+        __props__.__dict__["definition_id"] = definition_id
         __props__.__dict__["project_id"] = project_id
-        __props__.__dict__["replace"] = replace
-        return IterativePermissions(resource_name, opts=opts, __props__=__props__)
+        __props__.__dict__["resource_id"] = resource_id
+        __props__.__dict__["type"] = type
+        return ResourceAuthorization(resource_name, opts=opts, __props__=__props__)
 
     @property
     @pulumi.getter
-    def path(self) -> pulumi.Output[Optional[str]]:
+    def authorized(self) -> pulumi.Output[bool]:
         """
-        The name of the branch to assign the permissions.
+        Set to true to allow public access in the project. Type: boolean.
         """
-        return pulumi.get(self, "path")
+        return pulumi.get(self, "authorized")
 
     @property
-    @pulumi.getter
-    def permissions(self) -> pulumi.Output[Mapping[str, str]]:
+    @pulumi.getter(name="definitionId")
+    def definition_id(self) -> pulumi.Output[Optional[int]]:
         """
-        the permissions to assign. The following permissions are available.
+        The ID of the build definition to authorize. Type: string.
         """
-        return pulumi.get(self, "permissions")
+        return pulumi.get(self, "definition_id")
 
     @property
-    @pulumi.getter
-    def principal(self) -> pulumi.Output[str]:
+    @pulumi.getter(name="projectId")
+    def project_id(self) -> pulumi.Output[str]:
         """
-        The **group** principal to assign the permissions.
+        The project ID or project name. Type: string.
         """
-        return pulumi.get(self, "principal")
+        return pulumi.get(self, "project_id")
 
     @property
-    @pulumi.getter(name="projectId")
-    def project_id(self) -> pulumi.Output[str]:
+    @pulumi.getter(name="resourceId")
+    def resource_id(self) -> pulumi.Output[str]:
         """
-        The ID of the project to assign the permissions.
+        The ID of the resource to authorize. Type: string.
         """
-        return pulumi.get(self, "project_id")
+        return pulumi.get(self, "resource_id")
 
     @property
     @pulumi.getter
-    def replace(self) -> pulumi.Output[Optional[bool]]:
+    def type(self) -> pulumi.Output[Optional[str]]:
         """
-        Replace (`true`) or merge (`false`) the permissions. Default: `true`
+        The type of the resource to authorize. Type: string. Valid values: `endpoint`, `queue`, `variablegroup`. Default value: `endpoint`.
         """
-        return pulumi.get(self, "replace")
+        return pulumi.get(self, "type")
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/outputs.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/outputs.py`

 * *Files 2% similar despite different names*

```diff
@@ -123,14 +123,16 @@
                  path_filters: Optional[Sequence[str]] = None,
                  submitter_can_vote: Optional[bool] = None):
         """
         :param Sequence[str] auto_reviewer_ids: Required reviewers ids. Supports multiples user Ids.
         :param Sequence['BranchPolicyAutoReviewersSettingsScopeArgs'] scopes: Controls which repositories and branches the policy will be enabled for. This block must be defined at least once.
         :param str message: Activity feed message, Message will appear in the activity feed of pull requests with automatically added reviewers.
         :param int minimum_number_of_reviewers: Minimum number of required reviewers. Defaults to `1`.
+               
+               > **Note** Has to be greater than `0`. Can only be greater than `1` when attribute `auto_reviewer_ids` contains exactly one group! Only has an effect when attribute `blocking` is set to `true`.
         :param Sequence[str] path_filters: Filter path(s) on which the policy is applied. Supports absolute paths, wildcards and multiple paths. Example: /WebApp/Models/Data.cs, /WebApp/* or *.cs,/WebApp/Models/Data.cs;ClientApp/Models/Data.cs.
         :param bool submitter_can_vote: Controls whether or not the submitter's vote counts. Defaults to `false`.
         """
         pulumi.set(__self__, "auto_reviewer_ids", auto_reviewer_ids)
         pulumi.set(__self__, "scopes", scopes)
         if message is not None:
             pulumi.set(__self__, "message", message)
@@ -166,14 +168,16 @@
         return pulumi.get(self, "message")
 
     @property
     @pulumi.getter(name="minimumNumberOfReviewers")
     def minimum_number_of_reviewers(self) -> Optional[int]:
         """
         Minimum number of required reviewers. Defaults to `1`.
+
+        > **Note** Has to be greater than `0`. Can only be greater than `1` when attribute `auto_reviewer_ids` contains exactly one group! Only has an effect when attribute `blocking` is set to `true`.
         """
         return pulumi.get(self, "minimum_number_of_reviewers")
 
     @property
     @pulumi.getter(name="pathFilters")
     def path_filters(self) -> Optional[Sequence[str]]:
         """
@@ -705,19 +709,21 @@
                  last_pusher_cannot_approve: Optional[bool] = None,
                  on_last_iteration_require_vote: Optional[bool] = None,
                  on_push_reset_all_votes: Optional[bool] = None,
                  on_push_reset_approved_votes: Optional[bool] = None,
                  reviewer_count: Optional[int] = None,
                  submitter_can_vote: Optional[bool] = None):
         """
-        :param Sequence['BranchPolicyMinReviewersSettingsScopeArgs'] scopes: Controls which repositories and branches the policy will be enabled for. This block must be defined at least once.
+        :param Sequence['BranchPolicyMinReviewersSettingsScopeArgs'] scopes: A `scope` block as defined below. Controls which repositories and branches the policy will be enabled for. This block must be defined at least once.
         :param bool allow_completion_with_rejects_or_waits: Allow completion even if some reviewers vote to wait or reject. Defaults to `false`.
         :param bool last_pusher_cannot_approve: Prohibit the most recent pusher from approving their own changes. Defaults to `false`.
         :param bool on_last_iteration_require_vote: On last iteration require vote. Defaults to `false`.
         :param bool on_push_reset_all_votes: When new changes are pushed reset all code reviewer votes. Defaults to `false`.
+               
+               > **Note:** If `on_push_reset_all_votes` is `true` then `on_push_reset_approved_votes` will be set to `true`. To enable `on_push_reset_approved_votes`, you need explicitly set `on_push_reset_all_votes` `false` or not configure.
         :param bool on_push_reset_approved_votes: When new changes are pushed reset all approval votes (does not reset votes to reject or wait). Defaults to `false`.
         :param int reviewer_count: The number of reviewers needed to approve.
         :param bool submitter_can_vote: Allow requesters to approve their own changes. Defaults to `false`.
         """
         pulumi.set(__self__, "scopes", scopes)
         if allow_completion_with_rejects_or_waits is not None:
             pulumi.set(__self__, "allow_completion_with_rejects_or_waits", allow_completion_with_rejects_or_waits)
@@ -734,15 +740,15 @@
         if submitter_can_vote is not None:
             pulumi.set(__self__, "submitter_can_vote", submitter_can_vote)
 
     @property
     @pulumi.getter
     def scopes(self) -> Sequence['outputs.BranchPolicyMinReviewersSettingsScope']:
         """
-        Controls which repositories and branches the policy will be enabled for. This block must be defined at least once.
+        A `scope` block as defined below. Controls which repositories and branches the policy will be enabled for. This block must be defined at least once.
         """
         return pulumi.get(self, "scopes")
 
     @property
     @pulumi.getter(name="allowCompletionWithRejectsOrWaits")
     def allow_completion_with_rejects_or_waits(self) -> Optional[bool]:
         """
@@ -767,14 +773,16 @@
         return pulumi.get(self, "on_last_iteration_require_vote")
 
     @property
     @pulumi.getter(name="onPushResetAllVotes")
     def on_push_reset_all_votes(self) -> Optional[bool]:
         """
         When new changes are pushed reset all code reviewer votes. Defaults to `false`.
+
+        > **Note:** If `on_push_reset_all_votes` is `true` then `on_push_reset_approved_votes` will be set to `true`. To enable `on_push_reset_approved_votes`, you need explicitly set `on_push_reset_all_votes` `false` or not configure.
         """
         return pulumi.get(self, "on_push_reset_all_votes")
 
     @property
     @pulumi.getter(name="onPushResetApprovedVotes")
     def on_push_reset_approved_votes(self) -> Optional[bool]:
         """
@@ -4398,14 +4406,16 @@
                  project_url: str,
                  state: str):
         """
         :param str name: Name of the Project, if not specified all projects will be returned.
         :param str project_id: The ID of the Project.
         :param str project_url: Url to the full version of the object.
         :param str state: State of the Project, if not specified all projects will be returned. Valid values are `all`, `deleting`, `new`, `wellFormed`, `createPending`, `unchanged`,`deleted`.
+               
+               DataSource without specifying any arguments will return all projects.
         """
         pulumi.set(__self__, "name", name)
         pulumi.set(__self__, "project_id", project_id)
         pulumi.set(__self__, "project_url", project_url)
         pulumi.set(__self__, "state", state)
 
     @property
@@ -4433,14 +4443,16 @@
         return pulumi.get(self, "project_url")
 
     @property
     @pulumi.getter
     def state(self) -> str:
         """
         State of the Project, if not specified all projects will be returned. Valid values are `all`, `deleting`, `new`, `wellFormed`, `createPending`, `unchanged`,`deleted`.
+
+        DataSource without specifying any arguments will return all projects.
         """
         return pulumi.get(self, "state")
 
 
 @pulumi.output_type
 class GetRepositoriesRepositoryResult(dict):
     def __init__(__self__, *,
@@ -4630,14 +4642,28 @@
         :param str descriptor: The descriptor is the primary way to reference the graph subject while the system is running. This field will uniquely identify the same graph subject across both Accounts and Organizations.
         :param str display_name: This is the non-unique display name of the graph subject. To change this field, you must alter its value in the source provider.
         :param str id: The user ID.
         :param str mail_address: The email address of record for a given graph member. This may be different than the principal name.
         :param str origin: The type of source provider for the `origin_id` parameter (ex:AD, AAD, MSA) The supported origins are listed below.
         :param str principal_name: The PrincipalName of this graph member from the source provider.
         :param str origin_id: The unique identifier from the system of origin.
+               
+               DataSource without specifying any arguments will return all users inside an organization.
+               
+               List of possible subject types
+               
+               ```python
+               import pulumi
+               ```
+               
+               List of possible origins
+               
+               ```python
+               import pulumi
+               ```
         """
         pulumi.set(__self__, "descriptor", descriptor)
         pulumi.set(__self__, "display_name", display_name)
         pulumi.set(__self__, "id", id)
         pulumi.set(__self__, "mail_address", mail_address)
         pulumi.set(__self__, "origin", origin)
         pulumi.set(__self__, "principal_name", principal_name)
@@ -4693,14 +4719,28 @@
         return pulumi.get(self, "principal_name")
 
     @property
     @pulumi.getter(name="originId")
     def origin_id(self) -> Optional[str]:
         """
         The unique identifier from the system of origin.
+
+        DataSource without specifying any arguments will return all users inside an organization.
+
+        List of possible subject types
+
+        ```python
+        import pulumi
+        ```
+
+        List of possible origins
+
+        ```python
+        import pulumi
+        ```
         """
         return pulumi.get(self, "origin_id")
 
 
 @pulumi.output_type
 class GetVariableGroupKeyVaultResult(dict):
     def __init__(__self__, *,
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/pipeline/_inputs.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/pipeline/_inputs.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/pipeline/outputs.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/pipeline/outputs.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/pipeline/variable_group.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/pipeline/variable_group.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/policy/_inputs.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/policy/_inputs.py`

 * *Files 12% similar despite different names*

```diff
@@ -195,19 +195,21 @@
                  last_pusher_cannot_approve: Optional[pulumi.Input[bool]] = None,
                  on_last_iteration_require_vote: Optional[pulumi.Input[bool]] = None,
                  on_push_reset_all_votes: Optional[pulumi.Input[bool]] = None,
                  on_push_reset_approved_votes: Optional[pulumi.Input[bool]] = None,
                  reviewer_count: Optional[pulumi.Input[int]] = None,
                  submitter_can_vote: Optional[pulumi.Input[bool]] = None):
         """
-        :param pulumi.Input[Sequence[pulumi.Input['BranchPolicyMinReviewersSettingsScopeArgs']]] scopes: Controls which repositories and branches the policy will be enabled for. This block must be defined at least once.
+        :param pulumi.Input[Sequence[pulumi.Input['BranchPolicyMinReviewersSettingsScopeArgs']]] scopes: A `scope` block as defined below. Controls which repositories and branches the policy will be enabled for. This block must be defined at least once.
         :param pulumi.Input[bool] allow_completion_with_rejects_or_waits: Allow completion even if some reviewers vote to wait or reject. Defaults to `false`.
         :param pulumi.Input[bool] last_pusher_cannot_approve: Prohibit the most recent pusher from approving their own changes. Defaults to `false`.
         :param pulumi.Input[bool] on_last_iteration_require_vote: On last iteration require vote. Defaults to `false`.
         :param pulumi.Input[bool] on_push_reset_all_votes: When new changes are pushed reset all code reviewer votes. Defaults to `false`.
+               
+               > **Note:** If `on_push_reset_all_votes` is `true` then `on_push_reset_approved_votes` will be set to `true`. To enable `on_push_reset_approved_votes`, you need explicitly set `on_push_reset_all_votes` `false` or not configure.
         :param pulumi.Input[bool] on_push_reset_approved_votes: When new changes are pushed reset all approval votes (does not reset votes to reject or wait). Defaults to `false`.
         :param pulumi.Input[int] reviewer_count: The number of reviewers needed to approve.
         :param pulumi.Input[bool] submitter_can_vote: Allow requesters to approve their own changes. Defaults to `false`.
         """
         pulumi.set(__self__, "scopes", scopes)
         if allow_completion_with_rejects_or_waits is not None:
             pulumi.set(__self__, "allow_completion_with_rejects_or_waits", allow_completion_with_rejects_or_waits)
@@ -224,15 +226,15 @@
         if submitter_can_vote is not None:
             pulumi.set(__self__, "submitter_can_vote", submitter_can_vote)
 
     @property
     @pulumi.getter
     def scopes(self) -> pulumi.Input[Sequence[pulumi.Input['BranchPolicyMinReviewersSettingsScopeArgs']]]:
         """
-        Controls which repositories and branches the policy will be enabled for. This block must be defined at least once.
+        A `scope` block as defined below. Controls which repositories and branches the policy will be enabled for. This block must be defined at least once.
         """
         return pulumi.get(self, "scopes")
 
     @scopes.setter
     def scopes(self, value: pulumi.Input[Sequence[pulumi.Input['BranchPolicyMinReviewersSettingsScopeArgs']]]):
         pulumi.set(self, "scopes", value)
 
@@ -273,14 +275,16 @@
         pulumi.set(self, "on_last_iteration_require_vote", value)
 
     @property
     @pulumi.getter(name="onPushResetAllVotes")
     def on_push_reset_all_votes(self) -> Optional[pulumi.Input[bool]]:
         """
         When new changes are pushed reset all code reviewer votes. Defaults to `false`.
+
+        > **Note:** If `on_push_reset_all_votes` is `true` then `on_push_reset_approved_votes` will be set to `true`. To enable `on_push_reset_approved_votes`, you need explicitly set `on_push_reset_all_votes` `false` or not configure.
         """
         return pulumi.get(self, "on_push_reset_all_votes")
 
     @on_push_reset_all_votes.setter
     def on_push_reset_all_votes(self, value: Optional[pulumi.Input[bool]]):
         pulumi.set(self, "on_push_reset_all_votes", value)
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/policy/branch_policy_build_validation.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/policy/branch_policy_build_validation.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/policy/branch_policy_min_reviewers.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/branch_policy_min_reviewers.py`

 * *Files 3% similar despite different names*

```diff
@@ -3,15 +3,15 @@
 # *** Do not edit by hand unless you're certain you know what you are doing! ***
 
 import copy
 import warnings
 import pulumi
 import pulumi.runtime
 from typing import Any, Mapping, Optional, Sequence, Union, overload
-from .. import _utilities
+from . import _utilities
 from . import outputs
 from ._inputs import *
 
 __all__ = ['BranchPolicyMinReviewersArgs', 'BranchPolicyMinReviewers']
 
 @pulumi.input_type
 class BranchPolicyMinReviewersArgs:
@@ -19,15 +19,15 @@
                  project_id: pulumi.Input[str],
                  settings: pulumi.Input['BranchPolicyMinReviewersSettingsArgs'],
                  blocking: Optional[pulumi.Input[bool]] = None,
                  enabled: Optional[pulumi.Input[bool]] = None):
         """
         The set of arguments for constructing a BranchPolicyMinReviewers resource.
         :param pulumi.Input[str] project_id: The ID of the project in which the policy will be created.
-        :param pulumi.Input['BranchPolicyMinReviewersSettingsArgs'] settings: Configuration for the policy. This block must be defined exactly once.
+        :param pulumi.Input['BranchPolicyMinReviewersSettingsArgs'] settings: A `settings` block as defined below.. This block must be defined exactly once.
         :param pulumi.Input[bool] blocking: A flag indicating if the policy should be blocking. Defaults to `true`.
         :param pulumi.Input[bool] enabled: A flag indicating if the policy should be enabled. Defaults to `true`.
         """
         pulumi.set(__self__, "project_id", project_id)
         pulumi.set(__self__, "settings", settings)
         if blocking is not None:
             pulumi.set(__self__, "blocking", blocking)
@@ -46,15 +46,15 @@
     def project_id(self, value: pulumi.Input[str]):
         pulumi.set(self, "project_id", value)
 
     @property
     @pulumi.getter
     def settings(self) -> pulumi.Input['BranchPolicyMinReviewersSettingsArgs']:
         """
-        Configuration for the policy. This block must be defined exactly once.
+        A `settings` block as defined below.. This block must be defined exactly once.
         """
         return pulumi.get(self, "settings")
 
     @settings.setter
     def settings(self, value: pulumi.Input['BranchPolicyMinReviewersSettingsArgs']):
         pulumi.set(self, "settings", value)
 
@@ -91,15 +91,15 @@
                  project_id: Optional[pulumi.Input[str]] = None,
                  settings: Optional[pulumi.Input['BranchPolicyMinReviewersSettingsArgs']] = None):
         """
         Input properties used for looking up and filtering BranchPolicyMinReviewers resources.
         :param pulumi.Input[bool] blocking: A flag indicating if the policy should be blocking. Defaults to `true`.
         :param pulumi.Input[bool] enabled: A flag indicating if the policy should be enabled. Defaults to `true`.
         :param pulumi.Input[str] project_id: The ID of the project in which the policy will be created.
-        :param pulumi.Input['BranchPolicyMinReviewersSettingsArgs'] settings: Configuration for the policy. This block must be defined exactly once.
+        :param pulumi.Input['BranchPolicyMinReviewersSettingsArgs'] settings: A `settings` block as defined below.. This block must be defined exactly once.
         """
         if blocking is not None:
             pulumi.set(__self__, "blocking", blocking)
         if enabled is not None:
             pulumi.set(__self__, "enabled", enabled)
         if project_id is not None:
             pulumi.set(__self__, "project_id", project_id)
@@ -142,29 +142,24 @@
     def project_id(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "project_id", value)
 
     @property
     @pulumi.getter
     def settings(self) -> Optional[pulumi.Input['BranchPolicyMinReviewersSettingsArgs']]:
         """
-        Configuration for the policy. This block must be defined exactly once.
+        A `settings` block as defined below.. This block must be defined exactly once.
         """
         return pulumi.get(self, "settings")
 
     @settings.setter
     def settings(self, value: Optional[pulumi.Input['BranchPolicyMinReviewersSettingsArgs']]):
         pulumi.set(self, "settings", value)
 
 
-warnings.warn("""azuredevops.policy.BranchPolicyMinReviewers has been deprecated in favor of azuredevops.BranchPolicyMinReviewers""", DeprecationWarning)
-
-
 class BranchPolicyMinReviewers(pulumi.CustomResource):
-    warnings.warn("""azuredevops.policy.BranchPolicyMinReviewers has been deprecated in favor of azuredevops.BranchPolicyMinReviewers""", DeprecationWarning)
-
     @overload
     def __init__(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
                  blocking: Optional[pulumi.Input[bool]] = None,
                  enabled: Optional[pulumi.Input[bool]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
@@ -218,23 +213,23 @@
         - [Azure DevOps Service REST API 6.0 - Policy Configurations](https://docs.microsoft.com/en-us/rest/api/azure/devops/policy/configurations/create?view=azure-devops-rest-6.0)
 
         ## Import
 
         Azure DevOps Branch Policies can be imported using the project ID and policy configuration ID
 
         ```sh
-         $ pulumi import azuredevops:Policy/branchPolicyMinReviewers:BranchPolicyMinReviewers example 00000000-0000-0000-0000-000000000000/0
+         $ pulumi import azuredevops:index/branchPolicyMinReviewers:BranchPolicyMinReviewers example 00000000-0000-0000-0000-000000000000/0
         ```
 
         :param str resource_name: The name of the resource.
         :param pulumi.ResourceOptions opts: Options for the resource.
         :param pulumi.Input[bool] blocking: A flag indicating if the policy should be blocking. Defaults to `true`.
         :param pulumi.Input[bool] enabled: A flag indicating if the policy should be enabled. Defaults to `true`.
         :param pulumi.Input[str] project_id: The ID of the project in which the policy will be created.
-        :param pulumi.Input[pulumi.InputType['BranchPolicyMinReviewersSettingsArgs']] settings: Configuration for the policy. This block must be defined exactly once.
+        :param pulumi.Input[pulumi.InputType['BranchPolicyMinReviewersSettingsArgs']] settings: A `settings` block as defined below.. This block must be defined exactly once.
         """
         ...
     @overload
     def __init__(__self__,
                  resource_name: str,
                  args: BranchPolicyMinReviewersArgs,
                  opts: Optional[pulumi.ResourceOptions] = None):
@@ -286,15 +281,15 @@
         - [Azure DevOps Service REST API 6.0 - Policy Configurations](https://docs.microsoft.com/en-us/rest/api/azure/devops/policy/configurations/create?view=azure-devops-rest-6.0)
 
         ## Import
 
         Azure DevOps Branch Policies can be imported using the project ID and policy configuration ID
 
         ```sh
-         $ pulumi import azuredevops:Policy/branchPolicyMinReviewers:BranchPolicyMinReviewers example 00000000-0000-0000-0000-000000000000/0
+         $ pulumi import azuredevops:index/branchPolicyMinReviewers:BranchPolicyMinReviewers example 00000000-0000-0000-0000-000000000000/0
         ```
 
         :param str resource_name: The name of the resource.
         :param BranchPolicyMinReviewersArgs args: The arguments to use to populate this resource's properties.
         :param pulumi.ResourceOptions opts: Options for the resource.
         """
         ...
@@ -309,15 +304,14 @@
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
                  blocking: Optional[pulumi.Input[bool]] = None,
                  enabled: Optional[pulumi.Input[bool]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  settings: Optional[pulumi.Input[pulumi.InputType['BranchPolicyMinReviewersSettingsArgs']]] = None,
                  __props__=None):
-        pulumi.log.warn("""BranchPolicyMinReviewers is deprecated: azuredevops.policy.BranchPolicyMinReviewers has been deprecated in favor of azuredevops.BranchPolicyMinReviewers""")
         opts = pulumi.ResourceOptions.merge(_utilities.get_resource_opts_defaults(), opts)
         if not isinstance(opts, pulumi.ResourceOptions):
             raise TypeError('Expected resource options to be a ResourceOptions instance')
         if opts.id is None:
             if __props__ is not None:
                 raise TypeError('__props__ is only valid when passed in combination with a valid opts.id to get an existing resource')
             __props__ = BranchPolicyMinReviewersArgs.__new__(BranchPolicyMinReviewersArgs)
@@ -326,16 +320,18 @@
             __props__.__dict__["enabled"] = enabled
             if project_id is None and not opts.urn:
                 raise TypeError("Missing required property 'project_id'")
             __props__.__dict__["project_id"] = project_id
             if settings is None and not opts.urn:
                 raise TypeError("Missing required property 'settings'")
             __props__.__dict__["settings"] = settings
+        alias_opts = pulumi.ResourceOptions(aliases=[pulumi.Alias(type_="azuredevops:Policy/branchPolicyMinReviewers:BranchPolicyMinReviewers")])
+        opts = pulumi.ResourceOptions.merge(opts, alias_opts)
         super(BranchPolicyMinReviewers, __self__).__init__(
-            'azuredevops:Policy/branchPolicyMinReviewers:BranchPolicyMinReviewers',
+            'azuredevops:index/branchPolicyMinReviewers:BranchPolicyMinReviewers',
             resource_name,
             __props__,
             opts)
 
     @staticmethod
     def get(resource_name: str,
             id: pulumi.Input[str],
@@ -350,15 +346,15 @@
 
         :param str resource_name: The unique name of the resulting resource.
         :param pulumi.Input[str] id: The unique provider ID of the resource to lookup.
         :param pulumi.ResourceOptions opts: Options for the resource.
         :param pulumi.Input[bool] blocking: A flag indicating if the policy should be blocking. Defaults to `true`.
         :param pulumi.Input[bool] enabled: A flag indicating if the policy should be enabled. Defaults to `true`.
         :param pulumi.Input[str] project_id: The ID of the project in which the policy will be created.
-        :param pulumi.Input[pulumi.InputType['BranchPolicyMinReviewersSettingsArgs']] settings: Configuration for the policy. This block must be defined exactly once.
+        :param pulumi.Input[pulumi.InputType['BranchPolicyMinReviewersSettingsArgs']] settings: A `settings` block as defined below.. This block must be defined exactly once.
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
 
         __props__ = _BranchPolicyMinReviewersState.__new__(_BranchPolicyMinReviewersState)
 
         __props__.__dict__["blocking"] = blocking
         __props__.__dict__["enabled"] = enabled
@@ -390,11 +386,11 @@
         """
         return pulumi.get(self, "project_id")
 
     @property
     @pulumi.getter
     def settings(self) -> pulumi.Output['outputs.BranchPolicyMinReviewersSettings']:
         """
-        Configuration for the policy. This block must be defined exactly once.
+        A `settings` block as defined below.. This block must be defined exactly once.
         """
         return pulumi.get(self, "settings")
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/policy/outputs.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/policy/outputs.py`

 * *Files 2% similar despite different names*

```diff
@@ -233,19 +233,21 @@
                  last_pusher_cannot_approve: Optional[bool] = None,
                  on_last_iteration_require_vote: Optional[bool] = None,
                  on_push_reset_all_votes: Optional[bool] = None,
                  on_push_reset_approved_votes: Optional[bool] = None,
                  reviewer_count: Optional[int] = None,
                  submitter_can_vote: Optional[bool] = None):
         """
-        :param Sequence['BranchPolicyMinReviewersSettingsScopeArgs'] scopes: Controls which repositories and branches the policy will be enabled for. This block must be defined at least once.
+        :param Sequence['BranchPolicyMinReviewersSettingsScopeArgs'] scopes: A `scope` block as defined below. Controls which repositories and branches the policy will be enabled for. This block must be defined at least once.
         :param bool allow_completion_with_rejects_or_waits: Allow completion even if some reviewers vote to wait or reject. Defaults to `false`.
         :param bool last_pusher_cannot_approve: Prohibit the most recent pusher from approving their own changes. Defaults to `false`.
         :param bool on_last_iteration_require_vote: On last iteration require vote. Defaults to `false`.
         :param bool on_push_reset_all_votes: When new changes are pushed reset all code reviewer votes. Defaults to `false`.
+               
+               > **Note:** If `on_push_reset_all_votes` is `true` then `on_push_reset_approved_votes` will be set to `true`. To enable `on_push_reset_approved_votes`, you need explicitly set `on_push_reset_all_votes` `false` or not configure.
         :param bool on_push_reset_approved_votes: When new changes are pushed reset all approval votes (does not reset votes to reject or wait). Defaults to `false`.
         :param int reviewer_count: The number of reviewers needed to approve.
         :param bool submitter_can_vote: Allow requesters to approve their own changes. Defaults to `false`.
         """
         pulumi.set(__self__, "scopes", scopes)
         if allow_completion_with_rejects_or_waits is not None:
             pulumi.set(__self__, "allow_completion_with_rejects_or_waits", allow_completion_with_rejects_or_waits)
@@ -262,15 +264,15 @@
         if submitter_can_vote is not None:
             pulumi.set(__self__, "submitter_can_vote", submitter_can_vote)
 
     @property
     @pulumi.getter
     def scopes(self) -> Sequence['outputs.BranchPolicyMinReviewersSettingsScope']:
         """
-        Controls which repositories and branches the policy will be enabled for. This block must be defined at least once.
+        A `scope` block as defined below. Controls which repositories and branches the policy will be enabled for. This block must be defined at least once.
         """
         return pulumi.get(self, "scopes")
 
     @property
     @pulumi.getter(name="allowCompletionWithRejectsOrWaits")
     def allow_completion_with_rejects_or_waits(self) -> Optional[bool]:
         """
@@ -295,14 +297,16 @@
         return pulumi.get(self, "on_last_iteration_require_vote")
 
     @property
     @pulumi.getter(name="onPushResetAllVotes")
     def on_push_reset_all_votes(self) -> Optional[bool]:
         """
         When new changes are pushed reset all code reviewer votes. Defaults to `false`.
+
+        > **Note:** If `on_push_reset_all_votes` is `true` then `on_push_reset_approved_votes` will be set to `true`. To enable `on_push_reset_approved_votes`, you need explicitly set `on_push_reset_all_votes` `false` or not configure.
         """
         return pulumi.get(self, "on_push_reset_all_votes")
 
     @property
     @pulumi.getter(name="onPushResetApprovedVotes")
     def on_push_reset_approved_votes(self) -> Optional[bool]:
         """
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/pool.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/pool.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/project.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/core/project.py`

 * *Files 14% similar despite different names*

```diff
@@ -3,15 +3,15 @@
 # *** Do not edit by hand unless you're certain you know what you are doing! ***
 
 import copy
 import warnings
 import pulumi
 import pulumi.runtime
 from typing import Any, Mapping, Optional, Sequence, Union, overload
-from . import _utilities
+from .. import _utilities
 
 __all__ = ['ProjectArgs', 'Project']
 
 @pulumi.input_type
 class ProjectArgs:
     def __init__(__self__, *,
                  description: Optional[pulumi.Input[str]] = None,
@@ -21,14 +21,19 @@
                  visibility: Optional[pulumi.Input[str]] = None,
                  work_item_template: Optional[pulumi.Input[str]] = None):
         """
         The set of arguments for constructing a Project resource.
         :param pulumi.Input[str] description: The Description of the Project.
         :param pulumi.Input[Mapping[str, pulumi.Input[str]]] features: Defines the status (`enabled`, `disabled`) of the project features.
                Valid features are `boards`, `repositories`, `pipelines`, `testplans`, `artifacts`
+               
+               > **NOTE:**
+               > It's possible to define project features both within the `ProjectFeatures` resource and
+               > via the `features` block by using the `Project` resource.
+               > However it's not possible to use both methods to manage features, since there'll be conflicts.
         :param pulumi.Input[str] name: The Project Name.
         :param pulumi.Input[str] version_control: Specifies the version control system. Valid values: `Git` or `Tfvc`. Defaults to `Git`.
         :param pulumi.Input[str] visibility: Specifies the visibility of the Project. Valid values: `private` or `public`. Defaults to `private`.
         :param pulumi.Input[str] work_item_template: Specifies the work item template. Valid values: `Agile`, `Basic`, `CMMI`, `Scrum` or a custom, pre-existing one. Defaults to `Agile`. An empty string will use the parent organization default.
         """
         if description is not None:
             pulumi.set(__self__, "description", description)
@@ -57,14 +62,19 @@
 
     @property
     @pulumi.getter
     def features(self) -> Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]:
         """
         Defines the status (`enabled`, `disabled`) of the project features.
         Valid features are `boards`, `repositories`, `pipelines`, `testplans`, `artifacts`
+
+        > **NOTE:**
+        > It's possible to define project features both within the `ProjectFeatures` resource and
+        > via the `features` block by using the `Project` resource.
+        > However it's not possible to use both methods to manage features, since there'll be conflicts.
         """
         return pulumi.get(self, "features")
 
     @features.setter
     def features(self, value: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]):
         pulumi.set(self, "features", value)
 
@@ -128,14 +138,19 @@
                  visibility: Optional[pulumi.Input[str]] = None,
                  work_item_template: Optional[pulumi.Input[str]] = None):
         """
         Input properties used for looking up and filtering Project resources.
         :param pulumi.Input[str] description: The Description of the Project.
         :param pulumi.Input[Mapping[str, pulumi.Input[str]]] features: Defines the status (`enabled`, `disabled`) of the project features.
                Valid features are `boards`, `repositories`, `pipelines`, `testplans`, `artifacts`
+               
+               > **NOTE:**
+               > It's possible to define project features both within the `ProjectFeatures` resource and
+               > via the `features` block by using the `Project` resource.
+               > However it's not possible to use both methods to manage features, since there'll be conflicts.
         :param pulumi.Input[str] name: The Project Name.
         :param pulumi.Input[str] process_template_id: The Process Template ID used by the Project.
         :param pulumi.Input[str] version_control: Specifies the version control system. Valid values: `Git` or `Tfvc`. Defaults to `Git`.
         :param pulumi.Input[str] visibility: Specifies the visibility of the Project. Valid values: `private` or `public`. Defaults to `private`.
         :param pulumi.Input[str] work_item_template: Specifies the work item template. Valid values: `Agile`, `Basic`, `CMMI`, `Scrum` or a custom, pre-existing one. Defaults to `Agile`. An empty string will use the parent organization default.
         """
         if description is not None:
@@ -167,14 +182,19 @@
 
     @property
     @pulumi.getter
     def features(self) -> Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]:
         """
         Defines the status (`enabled`, `disabled`) of the project features.
         Valid features are `boards`, `repositories`, `pipelines`, `testplans`, `artifacts`
+
+        > **NOTE:**
+        > It's possible to define project features both within the `ProjectFeatures` resource and
+        > via the `features` block by using the `Project` resource.
+        > However it's not possible to use both methods to manage features, since there'll be conflicts.
         """
         return pulumi.get(self, "features")
 
     @features.setter
     def features(self, value: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]):
         pulumi.set(self, "features", value)
 
@@ -235,15 +255,20 @@
         return pulumi.get(self, "work_item_template")
 
     @work_item_template.setter
     def work_item_template(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "work_item_template", value)
 
 
+warnings.warn("""azuredevops.core.Project has been deprecated in favor of azuredevops.Project""", DeprecationWarning)
+
+
 class Project(pulumi.CustomResource):
+    warnings.warn("""azuredevops.core.Project has been deprecated in favor of azuredevops.Project""", DeprecationWarning)
+
     @overload
     def __init__(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
                  description: Optional[pulumi.Input[str]] = None,
                  features: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
                  name: Optional[pulumi.Input[str]] = None,
@@ -279,28 +304,33 @@
         - **Project & Team**: Read, Write, & Manage
 
         ## Import
 
         Azure DevOps Projects can be imported using the project name or by the project Guid, e.g.
 
         ```sh
-         $ pulumi import azuredevops:index/project:Project example "Example Project"
+         $ pulumi import azuredevops:Core/project:Project example "Example Project"
         ```
 
          or
 
         ```sh
-         $ pulumi import azuredevops:index/project:Project example 00000000-0000-0000-0000-000000000000
+         $ pulumi import azuredevops:Core/project:Project example 00000000-0000-0000-0000-000000000000
         ```
 
         :param str resource_name: The name of the resource.
         :param pulumi.ResourceOptions opts: Options for the resource.
         :param pulumi.Input[str] description: The Description of the Project.
         :param pulumi.Input[Mapping[str, pulumi.Input[str]]] features: Defines the status (`enabled`, `disabled`) of the project features.
                Valid features are `boards`, `repositories`, `pipelines`, `testplans`, `artifacts`
+               
+               > **NOTE:**
+               > It's possible to define project features both within the `ProjectFeatures` resource and
+               > via the `features` block by using the `Project` resource.
+               > However it's not possible to use both methods to manage features, since there'll be conflicts.
         :param pulumi.Input[str] name: The Project Name.
         :param pulumi.Input[str] version_control: Specifies the version control system. Valid values: `Git` or `Tfvc`. Defaults to `Git`.
         :param pulumi.Input[str] visibility: Specifies the visibility of the Project. Valid values: `private` or `public`. Defaults to `private`.
         :param pulumi.Input[str] work_item_template: Specifies the work item template. Valid values: `Agile`, `Basic`, `CMMI`, `Scrum` or a custom, pre-existing one. Defaults to `Agile`. An empty string will use the parent organization default.
         """
         ...
     @overload
@@ -336,21 +366,21 @@
         - **Project & Team**: Read, Write, & Manage
 
         ## Import
 
         Azure DevOps Projects can be imported using the project name or by the project Guid, e.g.
 
         ```sh
-         $ pulumi import azuredevops:index/project:Project example "Example Project"
+         $ pulumi import azuredevops:Core/project:Project example "Example Project"
         ```
 
          or
 
         ```sh
-         $ pulumi import azuredevops:index/project:Project example 00000000-0000-0000-0000-000000000000
+         $ pulumi import azuredevops:Core/project:Project example 00000000-0000-0000-0000-000000000000
         ```
 
         :param str resource_name: The name of the resource.
         :param ProjectArgs args: The arguments to use to populate this resource's properties.
         :param pulumi.ResourceOptions opts: Options for the resource.
         """
         ...
@@ -367,14 +397,15 @@
                  description: Optional[pulumi.Input[str]] = None,
                  features: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
                  name: Optional[pulumi.Input[str]] = None,
                  version_control: Optional[pulumi.Input[str]] = None,
                  visibility: Optional[pulumi.Input[str]] = None,
                  work_item_template: Optional[pulumi.Input[str]] = None,
                  __props__=None):
+        pulumi.log.warn("""Project is deprecated: azuredevops.core.Project has been deprecated in favor of azuredevops.Project""")
         opts = pulumi.ResourceOptions.merge(_utilities.get_resource_opts_defaults(), opts)
         if not isinstance(opts, pulumi.ResourceOptions):
             raise TypeError('Expected resource options to be a ResourceOptions instance')
         if opts.id is None:
             if __props__ is not None:
                 raise TypeError('__props__ is only valid when passed in combination with a valid opts.id to get an existing resource')
             __props__ = ProjectArgs.__new__(ProjectArgs)
@@ -382,18 +413,16 @@
             __props__.__dict__["description"] = description
             __props__.__dict__["features"] = features
             __props__.__dict__["name"] = name
             __props__.__dict__["version_control"] = version_control
             __props__.__dict__["visibility"] = visibility
             __props__.__dict__["work_item_template"] = work_item_template
             __props__.__dict__["process_template_id"] = None
-        alias_opts = pulumi.ResourceOptions(aliases=[pulumi.Alias(type_="azuredevops:Core/project:Project")])
-        opts = pulumi.ResourceOptions.merge(opts, alias_opts)
         super(Project, __self__).__init__(
-            'azuredevops:index/project:Project',
+            'azuredevops:Core/project:Project',
             resource_name,
             __props__,
             opts)
 
     @staticmethod
     def get(resource_name: str,
             id: pulumi.Input[str],
@@ -411,14 +440,19 @@
 
         :param str resource_name: The unique name of the resulting resource.
         :param pulumi.Input[str] id: The unique provider ID of the resource to lookup.
         :param pulumi.ResourceOptions opts: Options for the resource.
         :param pulumi.Input[str] description: The Description of the Project.
         :param pulumi.Input[Mapping[str, pulumi.Input[str]]] features: Defines the status (`enabled`, `disabled`) of the project features.
                Valid features are `boards`, `repositories`, `pipelines`, `testplans`, `artifacts`
+               
+               > **NOTE:**
+               > It's possible to define project features both within the `ProjectFeatures` resource and
+               > via the `features` block by using the `Project` resource.
+               > However it's not possible to use both methods to manage features, since there'll be conflicts.
         :param pulumi.Input[str] name: The Project Name.
         :param pulumi.Input[str] process_template_id: The Process Template ID used by the Project.
         :param pulumi.Input[str] version_control: Specifies the version control system. Valid values: `Git` or `Tfvc`. Defaults to `Git`.
         :param pulumi.Input[str] visibility: Specifies the visibility of the Project. Valid values: `private` or `public`. Defaults to `private`.
         :param pulumi.Input[str] work_item_template: Specifies the work item template. Valid values: `Agile`, `Basic`, `CMMI`, `Scrum` or a custom, pre-existing one. Defaults to `Agile`. An empty string will use the parent organization default.
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
@@ -444,14 +478,19 @@
 
     @property
     @pulumi.getter
     def features(self) -> pulumi.Output[Optional[Mapping[str, str]]]:
         """
         Defines the status (`enabled`, `disabled`) of the project features.
         Valid features are `boards`, `repositories`, `pipelines`, `testplans`, `artifacts`
+
+        > **NOTE:**
+        > It's possible to define project features both within the `ProjectFeatures` resource and
+        > via the `features` block by using the `Project` resource.
+        > However it's not possible to use both methods to manage features, since there'll be conflicts.
         """
         return pulumi.get(self, "features")
 
     @property
     @pulumi.getter
     def name(self) -> pulumi.Output[str]:
         """
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/project_permissions.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/security/resource_authorization.py`

 * *Files 22% similar despite different names*

```diff
@@ -3,361 +3,396 @@
 # *** Do not edit by hand unless you're certain you know what you are doing! ***
 
 import copy
 import warnings
 import pulumi
 import pulumi.runtime
 from typing import Any, Mapping, Optional, Sequence, Union, overload
-from . import _utilities
+from .. import _utilities
 
-__all__ = ['ProjectPermissionsArgs', 'ProjectPermissions']
+__all__ = ['ResourceAuthorizationArgs', 'ResourceAuthorization']
 
 @pulumi.input_type
-class ProjectPermissionsArgs:
+class ResourceAuthorizationArgs:
     def __init__(__self__, *,
-                 permissions: pulumi.Input[Mapping[str, pulumi.Input[str]]],
-                 principal: pulumi.Input[str],
+                 authorized: pulumi.Input[bool],
                  project_id: pulumi.Input[str],
-                 replace: Optional[pulumi.Input[bool]] = None):
+                 resource_id: pulumi.Input[str],
+                 definition_id: Optional[pulumi.Input[int]] = None,
+                 type: Optional[pulumi.Input[str]] = None):
+        """
+        The set of arguments for constructing a ResourceAuthorization resource.
+        :param pulumi.Input[bool] authorized: Set to true to allow public access in the project. Type: boolean.
+        :param pulumi.Input[str] project_id: The project ID or project name. Type: string.
+        :param pulumi.Input[str] resource_id: The ID of the resource to authorize. Type: string.
+        :param pulumi.Input[int] definition_id: The ID of the build definition to authorize. Type: string.
+        :param pulumi.Input[str] type: The type of the resource to authorize. Type: string. Valid values: `endpoint`, `queue`, `variablegroup`. Default value: `endpoint`.
         """
-        The set of arguments for constructing a ProjectPermissions resource.
-        :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available
-        :param pulumi.Input[str] principal: The **group** principal to assign the permissions.
-        :param pulumi.Input[str] project_id: The ID of the project to assign the permissions.
-        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
-        """
-        pulumi.set(__self__, "permissions", permissions)
-        pulumi.set(__self__, "principal", principal)
+        pulumi.set(__self__, "authorized", authorized)
         pulumi.set(__self__, "project_id", project_id)
-        if replace is not None:
-            pulumi.set(__self__, "replace", replace)
+        pulumi.set(__self__, "resource_id", resource_id)
+        if definition_id is not None:
+            pulumi.set(__self__, "definition_id", definition_id)
+        if type is not None:
+            pulumi.set(__self__, "type", type)
 
     @property
     @pulumi.getter
-    def permissions(self) -> pulumi.Input[Mapping[str, pulumi.Input[str]]]:
+    def authorized(self) -> pulumi.Input[bool]:
         """
-        the permissions to assign. The following permissions are available
+        Set to true to allow public access in the project. Type: boolean.
         """
-        return pulumi.get(self, "permissions")
+        return pulumi.get(self, "authorized")
 
-    @permissions.setter
-    def permissions(self, value: pulumi.Input[Mapping[str, pulumi.Input[str]]]):
-        pulumi.set(self, "permissions", value)
-
-    @property
-    @pulumi.getter
-    def principal(self) -> pulumi.Input[str]:
-        """
-        The **group** principal to assign the permissions.
-        """
-        return pulumi.get(self, "principal")
-
-    @principal.setter
-    def principal(self, value: pulumi.Input[str]):
-        pulumi.set(self, "principal", value)
+    @authorized.setter
+    def authorized(self, value: pulumi.Input[bool]):
+        pulumi.set(self, "authorized", value)
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> pulumi.Input[str]:
         """
-        The ID of the project to assign the permissions.
+        The project ID or project name. Type: string.
         """
         return pulumi.get(self, "project_id")
 
     @project_id.setter
     def project_id(self, value: pulumi.Input[str]):
         pulumi.set(self, "project_id", value)
 
     @property
+    @pulumi.getter(name="resourceId")
+    def resource_id(self) -> pulumi.Input[str]:
+        """
+        The ID of the resource to authorize. Type: string.
+        """
+        return pulumi.get(self, "resource_id")
+
+    @resource_id.setter
+    def resource_id(self, value: pulumi.Input[str]):
+        pulumi.set(self, "resource_id", value)
+
+    @property
+    @pulumi.getter(name="definitionId")
+    def definition_id(self) -> Optional[pulumi.Input[int]]:
+        """
+        The ID of the build definition to authorize. Type: string.
+        """
+        return pulumi.get(self, "definition_id")
+
+    @definition_id.setter
+    def definition_id(self, value: Optional[pulumi.Input[int]]):
+        pulumi.set(self, "definition_id", value)
+
+    @property
     @pulumi.getter
-    def replace(self) -> Optional[pulumi.Input[bool]]:
+    def type(self) -> Optional[pulumi.Input[str]]:
         """
-        Replace (`true`) or merge (`false`) the permissions. Default: `true`
+        The type of the resource to authorize. Type: string. Valid values: `endpoint`, `queue`, `variablegroup`. Default value: `endpoint`.
         """
-        return pulumi.get(self, "replace")
+        return pulumi.get(self, "type")
 
-    @replace.setter
-    def replace(self, value: Optional[pulumi.Input[bool]]):
-        pulumi.set(self, "replace", value)
+    @type.setter
+    def type(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "type", value)
 
 
 @pulumi.input_type
-class _ProjectPermissionsState:
+class _ResourceAuthorizationState:
     def __init__(__self__, *,
-                 permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
-                 principal: Optional[pulumi.Input[str]] = None,
+                 authorized: Optional[pulumi.Input[bool]] = None,
+                 definition_id: Optional[pulumi.Input[int]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
-                 replace: Optional[pulumi.Input[bool]] = None):
+                 resource_id: Optional[pulumi.Input[str]] = None,
+                 type: Optional[pulumi.Input[str]] = None):
         """
-        Input properties used for looking up and filtering ProjectPermissions resources.
-        :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available
-        :param pulumi.Input[str] principal: The **group** principal to assign the permissions.
-        :param pulumi.Input[str] project_id: The ID of the project to assign the permissions.
-        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
-        """
-        if permissions is not None:
-            pulumi.set(__self__, "permissions", permissions)
-        if principal is not None:
-            pulumi.set(__self__, "principal", principal)
+        Input properties used for looking up and filtering ResourceAuthorization resources.
+        :param pulumi.Input[bool] authorized: Set to true to allow public access in the project. Type: boolean.
+        :param pulumi.Input[int] definition_id: The ID of the build definition to authorize. Type: string.
+        :param pulumi.Input[str] project_id: The project ID or project name. Type: string.
+        :param pulumi.Input[str] resource_id: The ID of the resource to authorize. Type: string.
+        :param pulumi.Input[str] type: The type of the resource to authorize. Type: string. Valid values: `endpoint`, `queue`, `variablegroup`. Default value: `endpoint`.
+        """
+        if authorized is not None:
+            pulumi.set(__self__, "authorized", authorized)
+        if definition_id is not None:
+            pulumi.set(__self__, "definition_id", definition_id)
         if project_id is not None:
             pulumi.set(__self__, "project_id", project_id)
-        if replace is not None:
-            pulumi.set(__self__, "replace", replace)
+        if resource_id is not None:
+            pulumi.set(__self__, "resource_id", resource_id)
+        if type is not None:
+            pulumi.set(__self__, "type", type)
 
     @property
     @pulumi.getter
-    def permissions(self) -> Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]:
+    def authorized(self) -> Optional[pulumi.Input[bool]]:
         """
-        the permissions to assign. The following permissions are available
+        Set to true to allow public access in the project. Type: boolean.
         """
-        return pulumi.get(self, "permissions")
+        return pulumi.get(self, "authorized")
 
-    @permissions.setter
-    def permissions(self, value: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]):
-        pulumi.set(self, "permissions", value)
+    @authorized.setter
+    def authorized(self, value: Optional[pulumi.Input[bool]]):
+        pulumi.set(self, "authorized", value)
 
     @property
-    @pulumi.getter
-    def principal(self) -> Optional[pulumi.Input[str]]:
+    @pulumi.getter(name="definitionId")
+    def definition_id(self) -> Optional[pulumi.Input[int]]:
         """
-        The **group** principal to assign the permissions.
+        The ID of the build definition to authorize. Type: string.
         """
-        return pulumi.get(self, "principal")
+        return pulumi.get(self, "definition_id")
 
-    @principal.setter
-    def principal(self, value: Optional[pulumi.Input[str]]):
-        pulumi.set(self, "principal", value)
+    @definition_id.setter
+    def definition_id(self, value: Optional[pulumi.Input[int]]):
+        pulumi.set(self, "definition_id", value)
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> Optional[pulumi.Input[str]]:
         """
-        The ID of the project to assign the permissions.
+        The project ID or project name. Type: string.
         """
         return pulumi.get(self, "project_id")
 
     @project_id.setter
     def project_id(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "project_id", value)
 
     @property
+    @pulumi.getter(name="resourceId")
+    def resource_id(self) -> Optional[pulumi.Input[str]]:
+        """
+        The ID of the resource to authorize. Type: string.
+        """
+        return pulumi.get(self, "resource_id")
+
+    @resource_id.setter
+    def resource_id(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "resource_id", value)
+
+    @property
     @pulumi.getter
-    def replace(self) -> Optional[pulumi.Input[bool]]:
+    def type(self) -> Optional[pulumi.Input[str]]:
         """
-        Replace (`true`) or merge (`false`) the permissions. Default: `true`
+        The type of the resource to authorize. Type: string. Valid values: `endpoint`, `queue`, `variablegroup`. Default value: `endpoint`.
         """
-        return pulumi.get(self, "replace")
+        return pulumi.get(self, "type")
+
+    @type.setter
+    def type(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "type", value)
+
+
+warnings.warn("""azuredevops.security.ResourceAuthorization has been deprecated in favor of azuredevops.ResourceAuthorization""", DeprecationWarning)
 
-    @replace.setter
-    def replace(self, value: Optional[pulumi.Input[bool]]):
-        pulumi.set(self, "replace", value)
 
+class ResourceAuthorization(pulumi.CustomResource):
+    warnings.warn("""azuredevops.security.ResourceAuthorization has been deprecated in favor of azuredevops.ResourceAuthorization""", DeprecationWarning)
 
-class ProjectPermissions(pulumi.CustomResource):
     @overload
     def __init__(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
-                 permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
-                 principal: Optional[pulumi.Input[str]] = None,
+                 authorized: Optional[pulumi.Input[bool]] = None,
+                 definition_id: Optional[pulumi.Input[int]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
-                 replace: Optional[pulumi.Input[bool]] = None,
+                 resource_id: Optional[pulumi.Input[str]] = None,
+                 type: Optional[pulumi.Input[str]] = None,
                  __props__=None):
         """
-        Manages permissions for a AzureDevOps project
+        Manages authorization of resources, e.g. for access in build pipelines.
 
-        > **Note** Permissions can be assigned to group principals and not to single user principals.
+        Currently supported resources: service endpoint (aka service connection, endpoint).
 
         ## Example Usage
 
         ```python
         import pulumi
         import pulumi_azuredevops as azuredevops
 
-        example = azuredevops.Project("example",
+        example_project = azuredevops.Project("exampleProject",
             visibility="private",
             version_control="Git",
             work_item_template="Agile",
             description="Managed by Terraform")
-        example_readers = azuredevops.get_group_output(project_id=example.id,
-            name="Readers")
-        example_permission = azuredevops.ProjectPermissions("example-permission",
-            project_id=example.id,
-            principal=example_readers.id,
-            permissions={
-                "DELETE": "Deny",
-                "EDIT_BUILD_STATUS": "NotSet",
-                "WORK_ITEM_MOVE": "Allow",
-                "DELETE_TEST_RESULTS": "Deny",
-            })
+        example_service_endpoint_bit_bucket = azuredevops.ServiceEndpointBitBucket("exampleServiceEndpointBitBucket",
+            project_id=example_project.id,
+            username="username",
+            password="password",
+            service_endpoint_name="example-bitbucket",
+            description="Managed by Terraform")
+        example_resource_authorization = azuredevops.ResourceAuthorization("exampleResourceAuthorization",
+            project_id=example_project.id,
+            resource_id=example_service_endpoint_bit_bucket.id,
+            authorized=True)
         ```
         ## Relevant Links
 
-        * [Azure DevOps Service REST API 6.0 - Security](https://docs.microsoft.com/en-us/rest/api/azure/devops/security/?view=azure-devops-rest-6.0)
-
-        ## PAT Permissions Required
-
-        - **Project & Team**: vso.security_manage - Grants the ability to read, write, and manage security permissions.
-
-        ## Import
-
-        The resource does not support import.
+        - [Azure DevOps Service REST API 6.0 - Authorize Definition Resource](https://docs.microsoft.com/en-us/rest/api/azure/devops/build/resources/authorize%20definition%20resources?view=azure-devops-rest-6.0)
 
         :param str resource_name: The name of the resource.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available
-        :param pulumi.Input[str] principal: The **group** principal to assign the permissions.
-        :param pulumi.Input[str] project_id: The ID of the project to assign the permissions.
-        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
+        :param pulumi.Input[bool] authorized: Set to true to allow public access in the project. Type: boolean.
+        :param pulumi.Input[int] definition_id: The ID of the build definition to authorize. Type: string.
+        :param pulumi.Input[str] project_id: The project ID or project name. Type: string.
+        :param pulumi.Input[str] resource_id: The ID of the resource to authorize. Type: string.
+        :param pulumi.Input[str] type: The type of the resource to authorize. Type: string. Valid values: `endpoint`, `queue`, `variablegroup`. Default value: `endpoint`.
         """
         ...
     @overload
     def __init__(__self__,
                  resource_name: str,
-                 args: ProjectPermissionsArgs,
+                 args: ResourceAuthorizationArgs,
                  opts: Optional[pulumi.ResourceOptions] = None):
         """
-        Manages permissions for a AzureDevOps project
+        Manages authorization of resources, e.g. for access in build pipelines.
 
-        > **Note** Permissions can be assigned to group principals and not to single user principals.
+        Currently supported resources: service endpoint (aka service connection, endpoint).
 
         ## Example Usage
 
         ```python
         import pulumi
         import pulumi_azuredevops as azuredevops
 
-        example = azuredevops.Project("example",
+        example_project = azuredevops.Project("exampleProject",
             visibility="private",
             version_control="Git",
             work_item_template="Agile",
             description="Managed by Terraform")
-        example_readers = azuredevops.get_group_output(project_id=example.id,
-            name="Readers")
-        example_permission = azuredevops.ProjectPermissions("example-permission",
-            project_id=example.id,
-            principal=example_readers.id,
-            permissions={
-                "DELETE": "Deny",
-                "EDIT_BUILD_STATUS": "NotSet",
-                "WORK_ITEM_MOVE": "Allow",
-                "DELETE_TEST_RESULTS": "Deny",
-            })
+        example_service_endpoint_bit_bucket = azuredevops.ServiceEndpointBitBucket("exampleServiceEndpointBitBucket",
+            project_id=example_project.id,
+            username="username",
+            password="password",
+            service_endpoint_name="example-bitbucket",
+            description="Managed by Terraform")
+        example_resource_authorization = azuredevops.ResourceAuthorization("exampleResourceAuthorization",
+            project_id=example_project.id,
+            resource_id=example_service_endpoint_bit_bucket.id,
+            authorized=True)
         ```
         ## Relevant Links
 
-        * [Azure DevOps Service REST API 6.0 - Security](https://docs.microsoft.com/en-us/rest/api/azure/devops/security/?view=azure-devops-rest-6.0)
-
-        ## PAT Permissions Required
-
-        - **Project & Team**: vso.security_manage - Grants the ability to read, write, and manage security permissions.
-
-        ## Import
-
-        The resource does not support import.
+        - [Azure DevOps Service REST API 6.0 - Authorize Definition Resource](https://docs.microsoft.com/en-us/rest/api/azure/devops/build/resources/authorize%20definition%20resources?view=azure-devops-rest-6.0)
 
         :param str resource_name: The name of the resource.
-        :param ProjectPermissionsArgs args: The arguments to use to populate this resource's properties.
+        :param ResourceAuthorizationArgs args: The arguments to use to populate this resource's properties.
         :param pulumi.ResourceOptions opts: Options for the resource.
         """
         ...
     def __init__(__self__, resource_name: str, *args, **kwargs):
-        resource_args, opts = _utilities.get_resource_args_opts(ProjectPermissionsArgs, pulumi.ResourceOptions, *args, **kwargs)
+        resource_args, opts = _utilities.get_resource_args_opts(ResourceAuthorizationArgs, pulumi.ResourceOptions, *args, **kwargs)
         if resource_args is not None:
             __self__._internal_init(resource_name, opts, **resource_args.__dict__)
         else:
             __self__._internal_init(resource_name, *args, **kwargs)
 
     def _internal_init(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
-                 permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
-                 principal: Optional[pulumi.Input[str]] = None,
+                 authorized: Optional[pulumi.Input[bool]] = None,
+                 definition_id: Optional[pulumi.Input[int]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
-                 replace: Optional[pulumi.Input[bool]] = None,
+                 resource_id: Optional[pulumi.Input[str]] = None,
+                 type: Optional[pulumi.Input[str]] = None,
                  __props__=None):
+        pulumi.log.warn("""ResourceAuthorization is deprecated: azuredevops.security.ResourceAuthorization has been deprecated in favor of azuredevops.ResourceAuthorization""")
         opts = pulumi.ResourceOptions.merge(_utilities.get_resource_opts_defaults(), opts)
         if not isinstance(opts, pulumi.ResourceOptions):
             raise TypeError('Expected resource options to be a ResourceOptions instance')
         if opts.id is None:
             if __props__ is not None:
                 raise TypeError('__props__ is only valid when passed in combination with a valid opts.id to get an existing resource')
-            __props__ = ProjectPermissionsArgs.__new__(ProjectPermissionsArgs)
+            __props__ = ResourceAuthorizationArgs.__new__(ResourceAuthorizationArgs)
 
-            if permissions is None and not opts.urn:
-                raise TypeError("Missing required property 'permissions'")
-            __props__.__dict__["permissions"] = permissions
-            if principal is None and not opts.urn:
-                raise TypeError("Missing required property 'principal'")
-            __props__.__dict__["principal"] = principal
+            if authorized is None and not opts.urn:
+                raise TypeError("Missing required property 'authorized'")
+            __props__.__dict__["authorized"] = authorized
+            __props__.__dict__["definition_id"] = definition_id
             if project_id is None and not opts.urn:
                 raise TypeError("Missing required property 'project_id'")
             __props__.__dict__["project_id"] = project_id
-            __props__.__dict__["replace"] = replace
-        super(ProjectPermissions, __self__).__init__(
-            'azuredevops:index/projectPermissions:ProjectPermissions',
+            if resource_id is None and not opts.urn:
+                raise TypeError("Missing required property 'resource_id'")
+            __props__.__dict__["resource_id"] = resource_id
+            __props__.__dict__["type"] = type
+        super(ResourceAuthorization, __self__).__init__(
+            'azuredevops:Security/resourceAuthorization:ResourceAuthorization',
             resource_name,
             __props__,
             opts)
 
     @staticmethod
     def get(resource_name: str,
             id: pulumi.Input[str],
             opts: Optional[pulumi.ResourceOptions] = None,
-            permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
-            principal: Optional[pulumi.Input[str]] = None,
+            authorized: Optional[pulumi.Input[bool]] = None,
+            definition_id: Optional[pulumi.Input[int]] = None,
             project_id: Optional[pulumi.Input[str]] = None,
-            replace: Optional[pulumi.Input[bool]] = None) -> 'ProjectPermissions':
+            resource_id: Optional[pulumi.Input[str]] = None,
+            type: Optional[pulumi.Input[str]] = None) -> 'ResourceAuthorization':
         """
-        Get an existing ProjectPermissions resource's state with the given name, id, and optional extra
+        Get an existing ResourceAuthorization resource's state with the given name, id, and optional extra
         properties used to qualify the lookup.
 
         :param str resource_name: The unique name of the resulting resource.
         :param pulumi.Input[str] id: The unique provider ID of the resource to lookup.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available
-        :param pulumi.Input[str] principal: The **group** principal to assign the permissions.
-        :param pulumi.Input[str] project_id: The ID of the project to assign the permissions.
-        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
+        :param pulumi.Input[bool] authorized: Set to true to allow public access in the project. Type: boolean.
+        :param pulumi.Input[int] definition_id: The ID of the build definition to authorize. Type: string.
+        :param pulumi.Input[str] project_id: The project ID or project name. Type: string.
+        :param pulumi.Input[str] resource_id: The ID of the resource to authorize. Type: string.
+        :param pulumi.Input[str] type: The type of the resource to authorize. Type: string. Valid values: `endpoint`, `queue`, `variablegroup`. Default value: `endpoint`.
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
 
-        __props__ = _ProjectPermissionsState.__new__(_ProjectPermissionsState)
+        __props__ = _ResourceAuthorizationState.__new__(_ResourceAuthorizationState)
 
-        __props__.__dict__["permissions"] = permissions
-        __props__.__dict__["principal"] = principal
+        __props__.__dict__["authorized"] = authorized
+        __props__.__dict__["definition_id"] = definition_id
         __props__.__dict__["project_id"] = project_id
-        __props__.__dict__["replace"] = replace
-        return ProjectPermissions(resource_name, opts=opts, __props__=__props__)
+        __props__.__dict__["resource_id"] = resource_id
+        __props__.__dict__["type"] = type
+        return ResourceAuthorization(resource_name, opts=opts, __props__=__props__)
 
     @property
     @pulumi.getter
-    def permissions(self) -> pulumi.Output[Mapping[str, str]]:
+    def authorized(self) -> pulumi.Output[bool]:
         """
-        the permissions to assign. The following permissions are available
+        Set to true to allow public access in the project. Type: boolean.
         """
-        return pulumi.get(self, "permissions")
+        return pulumi.get(self, "authorized")
 
     @property
-    @pulumi.getter
-    def principal(self) -> pulumi.Output[str]:
+    @pulumi.getter(name="definitionId")
+    def definition_id(self) -> pulumi.Output[Optional[int]]:
         """
-        The **group** principal to assign the permissions.
+        The ID of the build definition to authorize. Type: string.
         """
-        return pulumi.get(self, "principal")
+        return pulumi.get(self, "definition_id")
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> pulumi.Output[str]:
         """
-        The ID of the project to assign the permissions.
+        The project ID or project name. Type: string.
         """
         return pulumi.get(self, "project_id")
 
     @property
+    @pulumi.getter(name="resourceId")
+    def resource_id(self) -> pulumi.Output[str]:
+        """
+        The ID of the resource to authorize. Type: string.
+        """
+        return pulumi.get(self, "resource_id")
+
+    @property
     @pulumi.getter
-    def replace(self) -> pulumi.Output[Optional[bool]]:
+    def type(self) -> pulumi.Output[Optional[str]]:
         """
-        Replace (`true`) or merge (`false`) the permissions. Default: `true`
+        The type of the resource to authorize. Type: string. Valid values: `endpoint`, `queue`, `variablegroup`. Default value: `endpoint`.
         """
-        return pulumi.get(self, "replace")
+        return pulumi.get(self, "type")
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/project_pipeline_settings.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/project_pipeline_settings.py`

 * *Files 22% similar despite different names*

```diff
@@ -12,30 +12,39 @@
 __all__ = ['ProjectPipelineSettingsArgs', 'ProjectPipelineSettings']
 
 @pulumi.input_type
 class ProjectPipelineSettingsArgs:
     def __init__(__self__, *,
                  project_id: pulumi.Input[str],
                  enforce_job_scope: Optional[pulumi.Input[bool]] = None,
+                 enforce_job_scope_for_release: Optional[pulumi.Input[bool]] = None,
                  enforce_referenced_repo_scoped_token: Optional[pulumi.Input[bool]] = None,
                  enforce_settable_var: Optional[pulumi.Input[bool]] = None,
                  publish_pipeline_metadata: Optional[pulumi.Input[bool]] = None,
                  status_badges_are_private: Optional[pulumi.Input[bool]] = None):
         """
         The set of arguments for constructing a ProjectPipelineSettings resource.
         :param pulumi.Input[str] project_id: The `id` of the project for which the project pipeline settings will be managed.
         :param pulumi.Input[bool] enforce_job_scope: Limit job authorization scope to current project for non-release pipelines.
+        :param pulumi.Input[bool] enforce_job_scope_for_release: Limit job authorization scope to current project for release pipelines.
+               
+               > **NOTE:**
+               > The settings at the organization will override settings specified on the project.
+               > For example, if `enforce_job_scope` is true at the organization, the `ProjectPipelineSettings` resource cannot set it to false.
+               > In this scenario, the plan will always show that the resource is trying to change `enforce_job_scope` from `true` to `false`.
         :param pulumi.Input[bool] enforce_referenced_repo_scoped_token: Protect access to repositories in YAML pipelines.
         :param pulumi.Input[bool] enforce_settable_var: Limit variables that can be set at queue time.
         :param pulumi.Input[bool] publish_pipeline_metadata: Publish metadata from pipelines.
         :param pulumi.Input[bool] status_badges_are_private: Disable anonymous access to badges.
         """
         pulumi.set(__self__, "project_id", project_id)
         if enforce_job_scope is not None:
             pulumi.set(__self__, "enforce_job_scope", enforce_job_scope)
+        if enforce_job_scope_for_release is not None:
+            pulumi.set(__self__, "enforce_job_scope_for_release", enforce_job_scope_for_release)
         if enforce_referenced_repo_scoped_token is not None:
             pulumi.set(__self__, "enforce_referenced_repo_scoped_token", enforce_referenced_repo_scoped_token)
         if enforce_settable_var is not None:
             pulumi.set(__self__, "enforce_settable_var", enforce_settable_var)
         if publish_pipeline_metadata is not None:
             pulumi.set(__self__, "publish_pipeline_metadata", publish_pipeline_metadata)
         if status_badges_are_private is not None:
@@ -62,14 +71,31 @@
         return pulumi.get(self, "enforce_job_scope")
 
     @enforce_job_scope.setter
     def enforce_job_scope(self, value: Optional[pulumi.Input[bool]]):
         pulumi.set(self, "enforce_job_scope", value)
 
     @property
+    @pulumi.getter(name="enforceJobScopeForRelease")
+    def enforce_job_scope_for_release(self) -> Optional[pulumi.Input[bool]]:
+        """
+        Limit job authorization scope to current project for release pipelines.
+
+        > **NOTE:**
+        > The settings at the organization will override settings specified on the project.
+        > For example, if `enforce_job_scope` is true at the organization, the `ProjectPipelineSettings` resource cannot set it to false.
+        > In this scenario, the plan will always show that the resource is trying to change `enforce_job_scope` from `true` to `false`.
+        """
+        return pulumi.get(self, "enforce_job_scope_for_release")
+
+    @enforce_job_scope_for_release.setter
+    def enforce_job_scope_for_release(self, value: Optional[pulumi.Input[bool]]):
+        pulumi.set(self, "enforce_job_scope_for_release", value)
+
+    @property
     @pulumi.getter(name="enforceReferencedRepoScopedToken")
     def enforce_referenced_repo_scoped_token(self) -> Optional[pulumi.Input[bool]]:
         """
         Protect access to repositories in YAML pipelines.
         """
         return pulumi.get(self, "enforce_referenced_repo_scoped_token")
 
@@ -114,30 +140,39 @@
         pulumi.set(self, "status_badges_are_private", value)
 
 
 @pulumi.input_type
 class _ProjectPipelineSettingsState:
     def __init__(__self__, *,
                  enforce_job_scope: Optional[pulumi.Input[bool]] = None,
+                 enforce_job_scope_for_release: Optional[pulumi.Input[bool]] = None,
                  enforce_referenced_repo_scoped_token: Optional[pulumi.Input[bool]] = None,
                  enforce_settable_var: Optional[pulumi.Input[bool]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  publish_pipeline_metadata: Optional[pulumi.Input[bool]] = None,
                  status_badges_are_private: Optional[pulumi.Input[bool]] = None):
         """
         Input properties used for looking up and filtering ProjectPipelineSettings resources.
         :param pulumi.Input[bool] enforce_job_scope: Limit job authorization scope to current project for non-release pipelines.
+        :param pulumi.Input[bool] enforce_job_scope_for_release: Limit job authorization scope to current project for release pipelines.
+               
+               > **NOTE:**
+               > The settings at the organization will override settings specified on the project.
+               > For example, if `enforce_job_scope` is true at the organization, the `ProjectPipelineSettings` resource cannot set it to false.
+               > In this scenario, the plan will always show that the resource is trying to change `enforce_job_scope` from `true` to `false`.
         :param pulumi.Input[bool] enforce_referenced_repo_scoped_token: Protect access to repositories in YAML pipelines.
         :param pulumi.Input[bool] enforce_settable_var: Limit variables that can be set at queue time.
         :param pulumi.Input[str] project_id: The `id` of the project for which the project pipeline settings will be managed.
         :param pulumi.Input[bool] publish_pipeline_metadata: Publish metadata from pipelines.
         :param pulumi.Input[bool] status_badges_are_private: Disable anonymous access to badges.
         """
         if enforce_job_scope is not None:
             pulumi.set(__self__, "enforce_job_scope", enforce_job_scope)
+        if enforce_job_scope_for_release is not None:
+            pulumi.set(__self__, "enforce_job_scope_for_release", enforce_job_scope_for_release)
         if enforce_referenced_repo_scoped_token is not None:
             pulumi.set(__self__, "enforce_referenced_repo_scoped_token", enforce_referenced_repo_scoped_token)
         if enforce_settable_var is not None:
             pulumi.set(__self__, "enforce_settable_var", enforce_settable_var)
         if project_id is not None:
             pulumi.set(__self__, "project_id", project_id)
         if publish_pipeline_metadata is not None:
@@ -154,14 +189,31 @@
         return pulumi.get(self, "enforce_job_scope")
 
     @enforce_job_scope.setter
     def enforce_job_scope(self, value: Optional[pulumi.Input[bool]]):
         pulumi.set(self, "enforce_job_scope", value)
 
     @property
+    @pulumi.getter(name="enforceJobScopeForRelease")
+    def enforce_job_scope_for_release(self) -> Optional[pulumi.Input[bool]]:
+        """
+        Limit job authorization scope to current project for release pipelines.
+
+        > **NOTE:**
+        > The settings at the organization will override settings specified on the project.
+        > For example, if `enforce_job_scope` is true at the organization, the `ProjectPipelineSettings` resource cannot set it to false.
+        > In this scenario, the plan will always show that the resource is trying to change `enforce_job_scope` from `true` to `false`.
+        """
+        return pulumi.get(self, "enforce_job_scope_for_release")
+
+    @enforce_job_scope_for_release.setter
+    def enforce_job_scope_for_release(self, value: Optional[pulumi.Input[bool]]):
+        pulumi.set(self, "enforce_job_scope_for_release", value)
+
+    @property
     @pulumi.getter(name="enforceReferencedRepoScopedToken")
     def enforce_referenced_repo_scoped_token(self) -> Optional[pulumi.Input[bool]]:
         """
         Protect access to repositories in YAML pipelines.
         """
         return pulumi.get(self, "enforce_referenced_repo_scoped_token")
 
@@ -220,14 +272,15 @@
 
 class ProjectPipelineSettings(pulumi.CustomResource):
     @overload
     def __init__(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
                  enforce_job_scope: Optional[pulumi.Input[bool]] = None,
+                 enforce_job_scope_for_release: Optional[pulumi.Input[bool]] = None,
                  enforce_referenced_repo_scoped_token: Optional[pulumi.Input[bool]] = None,
                  enforce_settable_var: Optional[pulumi.Input[bool]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  publish_pipeline_metadata: Optional[pulumi.Input[bool]] = None,
                  status_badges_are_private: Optional[pulumi.Input[bool]] = None,
                  __props__=None):
         """
@@ -267,14 +320,20 @@
         ```sh
          $ pulumi import azuredevops:index/projectPipelineSettings:ProjectPipelineSettings example 00000000-0000-0000-0000-000000000000
         ```
 
         :param str resource_name: The name of the resource.
         :param pulumi.ResourceOptions opts: Options for the resource.
         :param pulumi.Input[bool] enforce_job_scope: Limit job authorization scope to current project for non-release pipelines.
+        :param pulumi.Input[bool] enforce_job_scope_for_release: Limit job authorization scope to current project for release pipelines.
+               
+               > **NOTE:**
+               > The settings at the organization will override settings specified on the project.
+               > For example, if `enforce_job_scope` is true at the organization, the `ProjectPipelineSettings` resource cannot set it to false.
+               > In this scenario, the plan will always show that the resource is trying to change `enforce_job_scope` from `true` to `false`.
         :param pulumi.Input[bool] enforce_referenced_repo_scoped_token: Protect access to repositories in YAML pipelines.
         :param pulumi.Input[bool] enforce_settable_var: Limit variables that can be set at queue time.
         :param pulumi.Input[str] project_id: The `id` of the project for which the project pipeline settings will be managed.
         :param pulumi.Input[bool] publish_pipeline_metadata: Publish metadata from pipelines.
         :param pulumi.Input[bool] status_badges_are_private: Disable anonymous access to badges.
         """
         ...
@@ -333,14 +392,15 @@
         else:
             __self__._internal_init(resource_name, *args, **kwargs)
 
     def _internal_init(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
                  enforce_job_scope: Optional[pulumi.Input[bool]] = None,
+                 enforce_job_scope_for_release: Optional[pulumi.Input[bool]] = None,
                  enforce_referenced_repo_scoped_token: Optional[pulumi.Input[bool]] = None,
                  enforce_settable_var: Optional[pulumi.Input[bool]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  publish_pipeline_metadata: Optional[pulumi.Input[bool]] = None,
                  status_badges_are_private: Optional[pulumi.Input[bool]] = None,
                  __props__=None):
         opts = pulumi.ResourceOptions.merge(_utilities.get_resource_opts_defaults(), opts)
@@ -348,14 +408,15 @@
             raise TypeError('Expected resource options to be a ResourceOptions instance')
         if opts.id is None:
             if __props__ is not None:
                 raise TypeError('__props__ is only valid when passed in combination with a valid opts.id to get an existing resource')
             __props__ = ProjectPipelineSettingsArgs.__new__(ProjectPipelineSettingsArgs)
 
             __props__.__dict__["enforce_job_scope"] = enforce_job_scope
+            __props__.__dict__["enforce_job_scope_for_release"] = enforce_job_scope_for_release
             __props__.__dict__["enforce_referenced_repo_scoped_token"] = enforce_referenced_repo_scoped_token
             __props__.__dict__["enforce_settable_var"] = enforce_settable_var
             if project_id is None and not opts.urn:
                 raise TypeError("Missing required property 'project_id'")
             __props__.__dict__["project_id"] = project_id
             __props__.__dict__["publish_pipeline_metadata"] = publish_pipeline_metadata
             __props__.__dict__["status_badges_are_private"] = status_badges_are_private
@@ -366,38 +427,46 @@
             opts)
 
     @staticmethod
     def get(resource_name: str,
             id: pulumi.Input[str],
             opts: Optional[pulumi.ResourceOptions] = None,
             enforce_job_scope: Optional[pulumi.Input[bool]] = None,
+            enforce_job_scope_for_release: Optional[pulumi.Input[bool]] = None,
             enforce_referenced_repo_scoped_token: Optional[pulumi.Input[bool]] = None,
             enforce_settable_var: Optional[pulumi.Input[bool]] = None,
             project_id: Optional[pulumi.Input[str]] = None,
             publish_pipeline_metadata: Optional[pulumi.Input[bool]] = None,
             status_badges_are_private: Optional[pulumi.Input[bool]] = None) -> 'ProjectPipelineSettings':
         """
         Get an existing ProjectPipelineSettings resource's state with the given name, id, and optional extra
         properties used to qualify the lookup.
 
         :param str resource_name: The unique name of the resulting resource.
         :param pulumi.Input[str] id: The unique provider ID of the resource to lookup.
         :param pulumi.ResourceOptions opts: Options for the resource.
         :param pulumi.Input[bool] enforce_job_scope: Limit job authorization scope to current project for non-release pipelines.
+        :param pulumi.Input[bool] enforce_job_scope_for_release: Limit job authorization scope to current project for release pipelines.
+               
+               > **NOTE:**
+               > The settings at the organization will override settings specified on the project.
+               > For example, if `enforce_job_scope` is true at the organization, the `ProjectPipelineSettings` resource cannot set it to false.
+               > In this scenario, the plan will always show that the resource is trying to change `enforce_job_scope` from `true` to `false`.
         :param pulumi.Input[bool] enforce_referenced_repo_scoped_token: Protect access to repositories in YAML pipelines.
         :param pulumi.Input[bool] enforce_settable_var: Limit variables that can be set at queue time.
         :param pulumi.Input[str] project_id: The `id` of the project for which the project pipeline settings will be managed.
         :param pulumi.Input[bool] publish_pipeline_metadata: Publish metadata from pipelines.
         :param pulumi.Input[bool] status_badges_are_private: Disable anonymous access to badges.
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
 
         __props__ = _ProjectPipelineSettingsState.__new__(_ProjectPipelineSettingsState)
 
         __props__.__dict__["enforce_job_scope"] = enforce_job_scope
+        __props__.__dict__["enforce_job_scope_for_release"] = enforce_job_scope_for_release
         __props__.__dict__["enforce_referenced_repo_scoped_token"] = enforce_referenced_repo_scoped_token
         __props__.__dict__["enforce_settable_var"] = enforce_settable_var
         __props__.__dict__["project_id"] = project_id
         __props__.__dict__["publish_pipeline_metadata"] = publish_pipeline_metadata
         __props__.__dict__["status_badges_are_private"] = status_badges_are_private
         return ProjectPipelineSettings(resource_name, opts=opts, __props__=__props__)
 
@@ -406,14 +475,27 @@
     def enforce_job_scope(self) -> pulumi.Output[bool]:
         """
         Limit job authorization scope to current project for non-release pipelines.
         """
         return pulumi.get(self, "enforce_job_scope")
 
     @property
+    @pulumi.getter(name="enforceJobScopeForRelease")
+    def enforce_job_scope_for_release(self) -> pulumi.Output[bool]:
+        """
+        Limit job authorization scope to current project for release pipelines.
+
+        > **NOTE:**
+        > The settings at the organization will override settings specified on the project.
+        > For example, if `enforce_job_scope` is true at the organization, the `ProjectPipelineSettings` resource cannot set it to false.
+        > In this scenario, the plan will always show that the resource is trying to change `enforce_job_scope` from `true` to `false`.
+        """
+        return pulumi.get(self, "enforce_job_scope_for_release")
+
+    @property
     @pulumi.getter(name="enforceReferencedRepoScopedToken")
     def enforce_referenced_repo_scoped_token(self) -> pulumi.Output[bool]:
         """
         Protect access to repositories in YAML pipelines.
         """
         return pulumi.get(self, "enforce_referenced_repo_scoped_token")
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/provider.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/provider.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/repository/_inputs.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/repository/_inputs.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/repository/get_repositories.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/repository/get_repositories.py`

 * *Files 6% similar despite different names*

```diff
@@ -113,14 +113,15 @@
         name="Example Repository")
     ```
     ## Relevant Links
 
     - [Azure DevOps Service REST API 6.0 - Git API](https://docs.microsoft.com/en-us/rest/api/azure/devops/git/?view=azure-devops-rest-6.0)
 
 
+    :param bool include_hidden: DataSource without specifying any arguments will return all Git repositories of an organization.
     :param str name: Name of the Git repository to retrieve; requires `project_id` to be specified as well
     :param str project_id: ID of project to list Git repositories
     """
     pulumi.log.warn("""get_repositories is deprecated: azuredevops.repository.getRepositories has been deprecated in favor of azuredevops.getRepositories""")
     __args__ = dict()
     __args__['includeHidden'] = include_hidden
     __args__['name'] = name
@@ -158,12 +159,13 @@
         name="Example Repository")
     ```
     ## Relevant Links
 
     - [Azure DevOps Service REST API 6.0 - Git API](https://docs.microsoft.com/en-us/rest/api/azure/devops/git/?view=azure-devops-rest-6.0)
 
 
+    :param bool include_hidden: DataSource without specifying any arguments will return all Git repositories of an organization.
     :param str name: Name of the Git repository to retrieve; requires `project_id` to be specified as well
     :param str project_id: ID of project to list Git repositories
     """
     pulumi.log.warn("""get_repositories is deprecated: azuredevops.repository.getRepositories has been deprecated in favor of azuredevops.getRepositories""")
     ...
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/repository/git.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/repository/git.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/repository/outputs.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/repository/outputs.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/repository_policy_author_email_pattern.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/repository_policy_author_email_pattern.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/repository_policy_case_enforcement.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/repository_policy_case_enforcement.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/repository_policy_check_credentials.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/repository_policy_check_credentials.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/repository_policy_file_path_pattern.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/repository_policy_file_path_pattern.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/repository_policy_max_file_size.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/repository_policy_max_file_size.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/repository_policy_max_path_length.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/repository_policy_max_path_length.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/repository_policy_reserved_names.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/repository_policy_reserved_names.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/resource_authorization.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/pipeline_authorization.py`

 * *Files 22% similar despite different names*

```diff
@@ -5,390 +5,409 @@
 import copy
 import warnings
 import pulumi
 import pulumi.runtime
 from typing import Any, Mapping, Optional, Sequence, Union, overload
 from . import _utilities
 
-__all__ = ['ResourceAuthorizationArgs', 'ResourceAuthorization']
+__all__ = ['PipelineAuthorizationArgs', 'PipelineAuthorization']
 
 @pulumi.input_type
-class ResourceAuthorizationArgs:
+class PipelineAuthorizationArgs:
     def __init__(__self__, *,
-                 authorized: pulumi.Input[bool],
                  project_id: pulumi.Input[str],
                  resource_id: pulumi.Input[str],
-                 definition_id: Optional[pulumi.Input[int]] = None,
-                 type: Optional[pulumi.Input[str]] = None):
+                 type: pulumi.Input[str],
+                 pipeline_id: Optional[pulumi.Input[int]] = None):
         """
-        The set of arguments for constructing a ResourceAuthorization resource.
-        :param pulumi.Input[bool] authorized: Set to true to allow public access in the project. Type: boolean.
-        :param pulumi.Input[str] project_id: The project ID or project name. Type: string.
-        :param pulumi.Input[str] resource_id: The ID of the resource to authorize. Type: string.
-        :param pulumi.Input[int] definition_id: The ID of the build definition to authorize. Type: string.
-        :param pulumi.Input[str] type: The type of the resource to authorize. Type: string. Valid values: `endpoint`, `queue`, `variablegroup`. Default value: `endpoint`.
+        The set of arguments for constructing a PipelineAuthorization resource.
+        :param pulumi.Input[str] project_id: The  ID of the project. Changing this forces a new resource to be created
+        :param pulumi.Input[str] resource_id: The ID of the resource to authorize. Changing this forces a new resource to be created
+        :param pulumi.Input[str] type: The type of the resource to authorize. Valid values: `endpoint`, `queue`, `variablegroup`, `environment`. Changing this forces a new resource to be created
+        :param pulumi.Input[int] pipeline_id: The ID of the pipeline. Changing this forces a new resource to be created
         """
-        pulumi.set(__self__, "authorized", authorized)
         pulumi.set(__self__, "project_id", project_id)
         pulumi.set(__self__, "resource_id", resource_id)
-        if definition_id is not None:
-            pulumi.set(__self__, "definition_id", definition_id)
-        if type is not None:
-            pulumi.set(__self__, "type", type)
-
-    @property
-    @pulumi.getter
-    def authorized(self) -> pulumi.Input[bool]:
-        """
-        Set to true to allow public access in the project. Type: boolean.
-        """
-        return pulumi.get(self, "authorized")
-
-    @authorized.setter
-    def authorized(self, value: pulumi.Input[bool]):
-        pulumi.set(self, "authorized", value)
+        pulumi.set(__self__, "type", type)
+        if pipeline_id is not None:
+            pulumi.set(__self__, "pipeline_id", pipeline_id)
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> pulumi.Input[str]:
         """
-        The project ID or project name. Type: string.
+        The  ID of the project. Changing this forces a new resource to be created
         """
         return pulumi.get(self, "project_id")
 
     @project_id.setter
     def project_id(self, value: pulumi.Input[str]):
         pulumi.set(self, "project_id", value)
 
     @property
     @pulumi.getter(name="resourceId")
     def resource_id(self) -> pulumi.Input[str]:
         """
-        The ID of the resource to authorize. Type: string.
+        The ID of the resource to authorize. Changing this forces a new resource to be created
         """
         return pulumi.get(self, "resource_id")
 
     @resource_id.setter
     def resource_id(self, value: pulumi.Input[str]):
         pulumi.set(self, "resource_id", value)
 
     @property
-    @pulumi.getter(name="definitionId")
-    def definition_id(self) -> Optional[pulumi.Input[int]]:
+    @pulumi.getter
+    def type(self) -> pulumi.Input[str]:
         """
-        The ID of the build definition to authorize. Type: string.
+        The type of the resource to authorize. Valid values: `endpoint`, `queue`, `variablegroup`, `environment`. Changing this forces a new resource to be created
         """
-        return pulumi.get(self, "definition_id")
+        return pulumi.get(self, "type")
 
-    @definition_id.setter
-    def definition_id(self, value: Optional[pulumi.Input[int]]):
-        pulumi.set(self, "definition_id", value)
+    @type.setter
+    def type(self, value: pulumi.Input[str]):
+        pulumi.set(self, "type", value)
 
     @property
-    @pulumi.getter
-    def type(self) -> Optional[pulumi.Input[str]]:
+    @pulumi.getter(name="pipelineId")
+    def pipeline_id(self) -> Optional[pulumi.Input[int]]:
         """
-        The type of the resource to authorize. Type: string. Valid values: `endpoint`, `queue`, `variablegroup`. Default value: `endpoint`.
+        The ID of the pipeline. Changing this forces a new resource to be created
         """
-        return pulumi.get(self, "type")
+        return pulumi.get(self, "pipeline_id")
 
-    @type.setter
-    def type(self, value: Optional[pulumi.Input[str]]):
-        pulumi.set(self, "type", value)
+    @pipeline_id.setter
+    def pipeline_id(self, value: Optional[pulumi.Input[int]]):
+        pulumi.set(self, "pipeline_id", value)
 
 
 @pulumi.input_type
-class _ResourceAuthorizationState:
+class _PipelineAuthorizationState:
     def __init__(__self__, *,
-                 authorized: Optional[pulumi.Input[bool]] = None,
-                 definition_id: Optional[pulumi.Input[int]] = None,
+                 pipeline_id: Optional[pulumi.Input[int]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  resource_id: Optional[pulumi.Input[str]] = None,
                  type: Optional[pulumi.Input[str]] = None):
         """
-        Input properties used for looking up and filtering ResourceAuthorization resources.
-        :param pulumi.Input[bool] authorized: Set to true to allow public access in the project. Type: boolean.
-        :param pulumi.Input[int] definition_id: The ID of the build definition to authorize. Type: string.
-        :param pulumi.Input[str] project_id: The project ID or project name. Type: string.
-        :param pulumi.Input[str] resource_id: The ID of the resource to authorize. Type: string.
-        :param pulumi.Input[str] type: The type of the resource to authorize. Type: string. Valid values: `endpoint`, `queue`, `variablegroup`. Default value: `endpoint`.
-        """
-        if authorized is not None:
-            pulumi.set(__self__, "authorized", authorized)
-        if definition_id is not None:
-            pulumi.set(__self__, "definition_id", definition_id)
+        Input properties used for looking up and filtering PipelineAuthorization resources.
+        :param pulumi.Input[int] pipeline_id: The ID of the pipeline. Changing this forces a new resource to be created
+        :param pulumi.Input[str] project_id: The  ID of the project. Changing this forces a new resource to be created
+        :param pulumi.Input[str] resource_id: The ID of the resource to authorize. Changing this forces a new resource to be created
+        :param pulumi.Input[str] type: The type of the resource to authorize. Valid values: `endpoint`, `queue`, `variablegroup`, `environment`. Changing this forces a new resource to be created
+        """
+        if pipeline_id is not None:
+            pulumi.set(__self__, "pipeline_id", pipeline_id)
         if project_id is not None:
             pulumi.set(__self__, "project_id", project_id)
         if resource_id is not None:
             pulumi.set(__self__, "resource_id", resource_id)
         if type is not None:
             pulumi.set(__self__, "type", type)
 
     @property
-    @pulumi.getter
-    def authorized(self) -> Optional[pulumi.Input[bool]]:
-        """
-        Set to true to allow public access in the project. Type: boolean.
-        """
-        return pulumi.get(self, "authorized")
-
-    @authorized.setter
-    def authorized(self, value: Optional[pulumi.Input[bool]]):
-        pulumi.set(self, "authorized", value)
-
-    @property
-    @pulumi.getter(name="definitionId")
-    def definition_id(self) -> Optional[pulumi.Input[int]]:
+    @pulumi.getter(name="pipelineId")
+    def pipeline_id(self) -> Optional[pulumi.Input[int]]:
         """
-        The ID of the build definition to authorize. Type: string.
+        The ID of the pipeline. Changing this forces a new resource to be created
         """
-        return pulumi.get(self, "definition_id")
+        return pulumi.get(self, "pipeline_id")
 
-    @definition_id.setter
-    def definition_id(self, value: Optional[pulumi.Input[int]]):
-        pulumi.set(self, "definition_id", value)
+    @pipeline_id.setter
+    def pipeline_id(self, value: Optional[pulumi.Input[int]]):
+        pulumi.set(self, "pipeline_id", value)
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> Optional[pulumi.Input[str]]:
         """
-        The project ID or project name. Type: string.
+        The  ID of the project. Changing this forces a new resource to be created
         """
         return pulumi.get(self, "project_id")
 
     @project_id.setter
     def project_id(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "project_id", value)
 
     @property
     @pulumi.getter(name="resourceId")
     def resource_id(self) -> Optional[pulumi.Input[str]]:
         """
-        The ID of the resource to authorize. Type: string.
+        The ID of the resource to authorize. Changing this forces a new resource to be created
         """
         return pulumi.get(self, "resource_id")
 
     @resource_id.setter
     def resource_id(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "resource_id", value)
 
     @property
     @pulumi.getter
     def type(self) -> Optional[pulumi.Input[str]]:
         """
-        The type of the resource to authorize. Type: string. Valid values: `endpoint`, `queue`, `variablegroup`. Default value: `endpoint`.
+        The type of the resource to authorize. Valid values: `endpoint`, `queue`, `variablegroup`, `environment`. Changing this forces a new resource to be created
         """
         return pulumi.get(self, "type")
 
     @type.setter
     def type(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "type", value)
 
 
-class ResourceAuthorization(pulumi.CustomResource):
+class PipelineAuthorization(pulumi.CustomResource):
     @overload
     def __init__(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
-                 authorized: Optional[pulumi.Input[bool]] = None,
-                 definition_id: Optional[pulumi.Input[int]] = None,
+                 pipeline_id: Optional[pulumi.Input[int]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  resource_id: Optional[pulumi.Input[str]] = None,
                  type: Optional[pulumi.Input[str]] = None,
                  __props__=None):
         """
-        Manages authorization of resources, e.g. for access in build pipelines.
+        Manage pipeline access permissions to resources.
 
-        Currently supported resources: service endpoint (aka service connection, endpoint).
+        > **Note** This resource is a replacement for `ResourceAuthorization`.  Pipeline authorizations managed by `ResourceAuthorization` can also
+        be managed by this resource
 
         ## Example Usage
+        ### Authorization for all pipelines
 
         ```python
         import pulumi
         import pulumi_azuredevops as azuredevops
 
         example_project = azuredevops.Project("exampleProject",
             visibility="private",
             version_control="Git",
             work_item_template="Agile",
             description="Managed by Terraform")
-        example_service_endpoint_bit_bucket = azuredevops.ServiceEndpointBitBucket("exampleServiceEndpointBitBucket",
+        example_pool = azuredevops.Pool("examplePool",
+            auto_provision=False,
+            auto_update=False)
+        example_queue = azuredevops.Queue("exampleQueue",
             project_id=example_project.id,
-            username="username",
-            password="password",
-            service_endpoint_name="example-bitbucket",
+            agent_pool_id=example_pool.id)
+        example_pipeline_authorization = azuredevops.PipelineAuthorization("examplePipelineAuthorization",
+            project_id=example_project.id,
+            resource_id=example_queue.id,
+            type="queue")
+        ```
+        ### Authorization for specific pipeline
+
+        ```python
+        import pulumi
+        import pulumi_azuredevops as azuredevops
+
+        example_project = azuredevops.Project("exampleProject",
+            visibility="private",
+            version_control="Git",
+            work_item_template="Agile",
             description="Managed by Terraform")
-        example_resource_authorization = azuredevops.ResourceAuthorization("exampleResourceAuthorization",
+        example_pool = azuredevops.Pool("examplePool",
+            auto_provision=False,
+            auto_update=False)
+        example_queue = azuredevops.Queue("exampleQueue",
+            project_id=example_project.id,
+            agent_pool_id=example_pool.id)
+        example_git_repository = azuredevops.get_git_repository_output(project_id=example_project.id,
+            name="Example Project")
+        example_build_definition = azuredevops.BuildDefinition("exampleBuildDefinition",
             project_id=example_project.id,
-            resource_id=example_service_endpoint_bit_bucket.id,
-            authorized=True)
+            repository=azuredevops.BuildDefinitionRepositoryArgs(
+                repo_type="TfsGit",
+                repo_id=example_git_repository.id,
+                yml_path="azure-pipelines.yml",
+            ))
+        example_pipeline_authorization = azuredevops.PipelineAuthorization("examplePipelineAuthorization",
+            project_id=example_project.id,
+            resource_id=example_queue.id,
+            type="queue",
+            pipeline_id=example_build_definition.id)
         ```
         ## Relevant Links
 
-        - [Azure DevOps Service REST API 6.0 - Authorize Definition Resource](https://docs.microsoft.com/en-us/rest/api/azure/devops/build/resources/authorize%20definition%20resources?view=azure-devops-rest-6.0)
+        - [Azure DevOps Service REST API 7.1 - Pipeline Permissions](https://learn.microsoft.com/en-us/rest/api/azure/devops/approvalsandchecks/pipeline-permissions?view=azure-devops-rest-7.1)
 
         :param str resource_name: The name of the resource.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[bool] authorized: Set to true to allow public access in the project. Type: boolean.
-        :param pulumi.Input[int] definition_id: The ID of the build definition to authorize. Type: string.
-        :param pulumi.Input[str] project_id: The project ID or project name. Type: string.
-        :param pulumi.Input[str] resource_id: The ID of the resource to authorize. Type: string.
-        :param pulumi.Input[str] type: The type of the resource to authorize. Type: string. Valid values: `endpoint`, `queue`, `variablegroup`. Default value: `endpoint`.
+        :param pulumi.Input[int] pipeline_id: The ID of the pipeline. Changing this forces a new resource to be created
+        :param pulumi.Input[str] project_id: The  ID of the project. Changing this forces a new resource to be created
+        :param pulumi.Input[str] resource_id: The ID of the resource to authorize. Changing this forces a new resource to be created
+        :param pulumi.Input[str] type: The type of the resource to authorize. Valid values: `endpoint`, `queue`, `variablegroup`, `environment`. Changing this forces a new resource to be created
         """
         ...
     @overload
     def __init__(__self__,
                  resource_name: str,
-                 args: ResourceAuthorizationArgs,
+                 args: PipelineAuthorizationArgs,
                  opts: Optional[pulumi.ResourceOptions] = None):
         """
-        Manages authorization of resources, e.g. for access in build pipelines.
+        Manage pipeline access permissions to resources.
 
-        Currently supported resources: service endpoint (aka service connection, endpoint).
+        > **Note** This resource is a replacement for `ResourceAuthorization`.  Pipeline authorizations managed by `ResourceAuthorization` can also
+        be managed by this resource
 
         ## Example Usage
+        ### Authorization for all pipelines
 
         ```python
         import pulumi
         import pulumi_azuredevops as azuredevops
 
         example_project = azuredevops.Project("exampleProject",
             visibility="private",
             version_control="Git",
             work_item_template="Agile",
             description="Managed by Terraform")
-        example_service_endpoint_bit_bucket = azuredevops.ServiceEndpointBitBucket("exampleServiceEndpointBitBucket",
+        example_pool = azuredevops.Pool("examplePool",
+            auto_provision=False,
+            auto_update=False)
+        example_queue = azuredevops.Queue("exampleQueue",
+            project_id=example_project.id,
+            agent_pool_id=example_pool.id)
+        example_pipeline_authorization = azuredevops.PipelineAuthorization("examplePipelineAuthorization",
             project_id=example_project.id,
-            username="username",
-            password="password",
-            service_endpoint_name="example-bitbucket",
+            resource_id=example_queue.id,
+            type="queue")
+        ```
+        ### Authorization for specific pipeline
+
+        ```python
+        import pulumi
+        import pulumi_azuredevops as azuredevops
+
+        example_project = azuredevops.Project("exampleProject",
+            visibility="private",
+            version_control="Git",
+            work_item_template="Agile",
             description="Managed by Terraform")
-        example_resource_authorization = azuredevops.ResourceAuthorization("exampleResourceAuthorization",
+        example_pool = azuredevops.Pool("examplePool",
+            auto_provision=False,
+            auto_update=False)
+        example_queue = azuredevops.Queue("exampleQueue",
             project_id=example_project.id,
-            resource_id=example_service_endpoint_bit_bucket.id,
-            authorized=True)
+            agent_pool_id=example_pool.id)
+        example_git_repository = azuredevops.get_git_repository_output(project_id=example_project.id,
+            name="Example Project")
+        example_build_definition = azuredevops.BuildDefinition("exampleBuildDefinition",
+            project_id=example_project.id,
+            repository=azuredevops.BuildDefinitionRepositoryArgs(
+                repo_type="TfsGit",
+                repo_id=example_git_repository.id,
+                yml_path="azure-pipelines.yml",
+            ))
+        example_pipeline_authorization = azuredevops.PipelineAuthorization("examplePipelineAuthorization",
+            project_id=example_project.id,
+            resource_id=example_queue.id,
+            type="queue",
+            pipeline_id=example_build_definition.id)
         ```
         ## Relevant Links
 
-        - [Azure DevOps Service REST API 6.0 - Authorize Definition Resource](https://docs.microsoft.com/en-us/rest/api/azure/devops/build/resources/authorize%20definition%20resources?view=azure-devops-rest-6.0)
+        - [Azure DevOps Service REST API 7.1 - Pipeline Permissions](https://learn.microsoft.com/en-us/rest/api/azure/devops/approvalsandchecks/pipeline-permissions?view=azure-devops-rest-7.1)
 
         :param str resource_name: The name of the resource.
-        :param ResourceAuthorizationArgs args: The arguments to use to populate this resource's properties.
+        :param PipelineAuthorizationArgs args: The arguments to use to populate this resource's properties.
         :param pulumi.ResourceOptions opts: Options for the resource.
         """
         ...
     def __init__(__self__, resource_name: str, *args, **kwargs):
-        resource_args, opts = _utilities.get_resource_args_opts(ResourceAuthorizationArgs, pulumi.ResourceOptions, *args, **kwargs)
+        resource_args, opts = _utilities.get_resource_args_opts(PipelineAuthorizationArgs, pulumi.ResourceOptions, *args, **kwargs)
         if resource_args is not None:
             __self__._internal_init(resource_name, opts, **resource_args.__dict__)
         else:
             __self__._internal_init(resource_name, *args, **kwargs)
 
     def _internal_init(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
-                 authorized: Optional[pulumi.Input[bool]] = None,
-                 definition_id: Optional[pulumi.Input[int]] = None,
+                 pipeline_id: Optional[pulumi.Input[int]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  resource_id: Optional[pulumi.Input[str]] = None,
                  type: Optional[pulumi.Input[str]] = None,
                  __props__=None):
         opts = pulumi.ResourceOptions.merge(_utilities.get_resource_opts_defaults(), opts)
         if not isinstance(opts, pulumi.ResourceOptions):
             raise TypeError('Expected resource options to be a ResourceOptions instance')
         if opts.id is None:
             if __props__ is not None:
                 raise TypeError('__props__ is only valid when passed in combination with a valid opts.id to get an existing resource')
-            __props__ = ResourceAuthorizationArgs.__new__(ResourceAuthorizationArgs)
+            __props__ = PipelineAuthorizationArgs.__new__(PipelineAuthorizationArgs)
 
-            if authorized is None and not opts.urn:
-                raise TypeError("Missing required property 'authorized'")
-            __props__.__dict__["authorized"] = authorized
-            __props__.__dict__["definition_id"] = definition_id
+            __props__.__dict__["pipeline_id"] = pipeline_id
             if project_id is None and not opts.urn:
                 raise TypeError("Missing required property 'project_id'")
             __props__.__dict__["project_id"] = project_id
             if resource_id is None and not opts.urn:
                 raise TypeError("Missing required property 'resource_id'")
             __props__.__dict__["resource_id"] = resource_id
+            if type is None and not opts.urn:
+                raise TypeError("Missing required property 'type'")
             __props__.__dict__["type"] = type
-        alias_opts = pulumi.ResourceOptions(aliases=[pulumi.Alias(type_="azuredevops:Security/resourceAuthorization:ResourceAuthorization")])
-        opts = pulumi.ResourceOptions.merge(opts, alias_opts)
-        super(ResourceAuthorization, __self__).__init__(
-            'azuredevops:index/resourceAuthorization:ResourceAuthorization',
+        super(PipelineAuthorization, __self__).__init__(
+            'azuredevops:index/pipelineAuthorization:PipelineAuthorization',
             resource_name,
             __props__,
             opts)
 
     @staticmethod
     def get(resource_name: str,
             id: pulumi.Input[str],
             opts: Optional[pulumi.ResourceOptions] = None,
-            authorized: Optional[pulumi.Input[bool]] = None,
-            definition_id: Optional[pulumi.Input[int]] = None,
+            pipeline_id: Optional[pulumi.Input[int]] = None,
             project_id: Optional[pulumi.Input[str]] = None,
             resource_id: Optional[pulumi.Input[str]] = None,
-            type: Optional[pulumi.Input[str]] = None) -> 'ResourceAuthorization':
+            type: Optional[pulumi.Input[str]] = None) -> 'PipelineAuthorization':
         """
-        Get an existing ResourceAuthorization resource's state with the given name, id, and optional extra
+        Get an existing PipelineAuthorization resource's state with the given name, id, and optional extra
         properties used to qualify the lookup.
 
         :param str resource_name: The unique name of the resulting resource.
         :param pulumi.Input[str] id: The unique provider ID of the resource to lookup.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[bool] authorized: Set to true to allow public access in the project. Type: boolean.
-        :param pulumi.Input[int] definition_id: The ID of the build definition to authorize. Type: string.
-        :param pulumi.Input[str] project_id: The project ID or project name. Type: string.
-        :param pulumi.Input[str] resource_id: The ID of the resource to authorize. Type: string.
-        :param pulumi.Input[str] type: The type of the resource to authorize. Type: string. Valid values: `endpoint`, `queue`, `variablegroup`. Default value: `endpoint`.
+        :param pulumi.Input[int] pipeline_id: The ID of the pipeline. Changing this forces a new resource to be created
+        :param pulumi.Input[str] project_id: The  ID of the project. Changing this forces a new resource to be created
+        :param pulumi.Input[str] resource_id: The ID of the resource to authorize. Changing this forces a new resource to be created
+        :param pulumi.Input[str] type: The type of the resource to authorize. Valid values: `endpoint`, `queue`, `variablegroup`, `environment`. Changing this forces a new resource to be created
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
 
-        __props__ = _ResourceAuthorizationState.__new__(_ResourceAuthorizationState)
+        __props__ = _PipelineAuthorizationState.__new__(_PipelineAuthorizationState)
 
-        __props__.__dict__["authorized"] = authorized
-        __props__.__dict__["definition_id"] = definition_id
+        __props__.__dict__["pipeline_id"] = pipeline_id
         __props__.__dict__["project_id"] = project_id
         __props__.__dict__["resource_id"] = resource_id
         __props__.__dict__["type"] = type
-        return ResourceAuthorization(resource_name, opts=opts, __props__=__props__)
-
-    @property
-    @pulumi.getter
-    def authorized(self) -> pulumi.Output[bool]:
-        """
-        Set to true to allow public access in the project. Type: boolean.
-        """
-        return pulumi.get(self, "authorized")
+        return PipelineAuthorization(resource_name, opts=opts, __props__=__props__)
 
     @property
-    @pulumi.getter(name="definitionId")
-    def definition_id(self) -> pulumi.Output[Optional[int]]:
+    @pulumi.getter(name="pipelineId")
+    def pipeline_id(self) -> pulumi.Output[Optional[int]]:
         """
-        The ID of the build definition to authorize. Type: string.
+        The ID of the pipeline. Changing this forces a new resource to be created
         """
-        return pulumi.get(self, "definition_id")
+        return pulumi.get(self, "pipeline_id")
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> pulumi.Output[str]:
         """
-        The project ID or project name. Type: string.
+        The  ID of the project. Changing this forces a new resource to be created
         """
         return pulumi.get(self, "project_id")
 
     @property
     @pulumi.getter(name="resourceId")
     def resource_id(self) -> pulumi.Output[str]:
         """
-        The ID of the resource to authorize. Type: string.
+        The ID of the resource to authorize. Changing this forces a new resource to be created
         """
         return pulumi.get(self, "resource_id")
 
     @property
     @pulumi.getter
-    def type(self) -> pulumi.Output[Optional[str]]:
+    def type(self) -> pulumi.Output[str]:
         """
-        The type of the resource to authorize. Type: string. Valid values: `endpoint`, `queue`, `variablegroup`. Default value: `endpoint`.
+        The type of the resource to authorize. Valid values: `endpoint`, `queue`, `variablegroup`, `environment`. Changing this forces a new resource to be created
         """
         return pulumi.get(self, "type")
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/security/resource_authorization.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint_externaltfs.py`

 * *Files 24% similar despite different names*

```diff
@@ -3,396 +3,382 @@
 # *** Do not edit by hand unless you're certain you know what you are doing! ***
 
 import copy
 import warnings
 import pulumi
 import pulumi.runtime
 from typing import Any, Mapping, Optional, Sequence, Union, overload
-from .. import _utilities
+from . import _utilities
+from . import outputs
+from ._inputs import *
 
-__all__ = ['ResourceAuthorizationArgs', 'ResourceAuthorization']
+__all__ = ['ServiceendpointExternaltfsArgs', 'ServiceendpointExternaltfs']
 
 @pulumi.input_type
-class ResourceAuthorizationArgs:
+class ServiceendpointExternaltfsArgs:
     def __init__(__self__, *,
-                 authorized: pulumi.Input[bool],
+                 auth_personal: pulumi.Input['ServiceendpointExternaltfsAuthPersonalArgs'],
+                 connection_url: pulumi.Input[str],
                  project_id: pulumi.Input[str],
-                 resource_id: pulumi.Input[str],
-                 definition_id: Optional[pulumi.Input[int]] = None,
-                 type: Optional[pulumi.Input[str]] = None):
-        """
-        The set of arguments for constructing a ResourceAuthorization resource.
-        :param pulumi.Input[bool] authorized: Set to true to allow public access in the project. Type: boolean.
-        :param pulumi.Input[str] project_id: The project ID or project name. Type: string.
-        :param pulumi.Input[str] resource_id: The ID of the resource to authorize. Type: string.
-        :param pulumi.Input[int] definition_id: The ID of the build definition to authorize. Type: string.
-        :param pulumi.Input[str] type: The type of the resource to authorize. Type: string. Valid values: `endpoint`, `queue`, `variablegroup`. Default value: `endpoint`.
+                 service_endpoint_name: pulumi.Input[str],
+                 authorization: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
+                 description: Optional[pulumi.Input[str]] = None):
+        """
+        The set of arguments for constructing a ServiceendpointExternaltfs resource.
+        :param pulumi.Input['ServiceendpointExternaltfsAuthPersonalArgs'] auth_personal: An `auth_personal` block as documented below. Allows connecting using a personal access token.
+        :param pulumi.Input[str] connection_url: URL of the Azure DevOps organization or the TFS Project Collection to connect to.
+        :param pulumi.Input[str] project_id: The ID of the project.
+        :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         """
-        pulumi.set(__self__, "authorized", authorized)
+        pulumi.set(__self__, "auth_personal", auth_personal)
+        pulumi.set(__self__, "connection_url", connection_url)
         pulumi.set(__self__, "project_id", project_id)
-        pulumi.set(__self__, "resource_id", resource_id)
-        if definition_id is not None:
-            pulumi.set(__self__, "definition_id", definition_id)
-        if type is not None:
-            pulumi.set(__self__, "type", type)
+        pulumi.set(__self__, "service_endpoint_name", service_endpoint_name)
+        if authorization is not None:
+            pulumi.set(__self__, "authorization", authorization)
+        if description is not None:
+            pulumi.set(__self__, "description", description)
 
     @property
-    @pulumi.getter
-    def authorized(self) -> pulumi.Input[bool]:
+    @pulumi.getter(name="authPersonal")
+    def auth_personal(self) -> pulumi.Input['ServiceendpointExternaltfsAuthPersonalArgs']:
         """
-        Set to true to allow public access in the project. Type: boolean.
+        An `auth_personal` block as documented below. Allows connecting using a personal access token.
         """
-        return pulumi.get(self, "authorized")
+        return pulumi.get(self, "auth_personal")
 
-    @authorized.setter
-    def authorized(self, value: pulumi.Input[bool]):
-        pulumi.set(self, "authorized", value)
+    @auth_personal.setter
+    def auth_personal(self, value: pulumi.Input['ServiceendpointExternaltfsAuthPersonalArgs']):
+        pulumi.set(self, "auth_personal", value)
+
+    @property
+    @pulumi.getter(name="connectionUrl")
+    def connection_url(self) -> pulumi.Input[str]:
+        """
+        URL of the Azure DevOps organization or the TFS Project Collection to connect to.
+        """
+        return pulumi.get(self, "connection_url")
+
+    @connection_url.setter
+    def connection_url(self, value: pulumi.Input[str]):
+        pulumi.set(self, "connection_url", value)
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> pulumi.Input[str]:
         """
-        The project ID or project name. Type: string.
+        The ID of the project.
         """
         return pulumi.get(self, "project_id")
 
     @project_id.setter
     def project_id(self, value: pulumi.Input[str]):
         pulumi.set(self, "project_id", value)
 
     @property
-    @pulumi.getter(name="resourceId")
-    def resource_id(self) -> pulumi.Input[str]:
+    @pulumi.getter(name="serviceEndpointName")
+    def service_endpoint_name(self) -> pulumi.Input[str]:
         """
-        The ID of the resource to authorize. Type: string.
+        The Service Endpoint name.
         """
-        return pulumi.get(self, "resource_id")
+        return pulumi.get(self, "service_endpoint_name")
 
-    @resource_id.setter
-    def resource_id(self, value: pulumi.Input[str]):
-        pulumi.set(self, "resource_id", value)
+    @service_endpoint_name.setter
+    def service_endpoint_name(self, value: pulumi.Input[str]):
+        pulumi.set(self, "service_endpoint_name", value)
 
     @property
-    @pulumi.getter(name="definitionId")
-    def definition_id(self) -> Optional[pulumi.Input[int]]:
-        """
-        The ID of the build definition to authorize. Type: string.
-        """
-        return pulumi.get(self, "definition_id")
+    @pulumi.getter
+    def authorization(self) -> Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]:
+        return pulumi.get(self, "authorization")
 
-    @definition_id.setter
-    def definition_id(self, value: Optional[pulumi.Input[int]]):
-        pulumi.set(self, "definition_id", value)
+    @authorization.setter
+    def authorization(self, value: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]):
+        pulumi.set(self, "authorization", value)
 
     @property
     @pulumi.getter
-    def type(self) -> Optional[pulumi.Input[str]]:
-        """
-        The type of the resource to authorize. Type: string. Valid values: `endpoint`, `queue`, `variablegroup`. Default value: `endpoint`.
-        """
-        return pulumi.get(self, "type")
+    def description(self) -> Optional[pulumi.Input[str]]:
+        return pulumi.get(self, "description")
 
-    @type.setter
-    def type(self, value: Optional[pulumi.Input[str]]):
-        pulumi.set(self, "type", value)
+    @description.setter
+    def description(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "description", value)
 
 
 @pulumi.input_type
-class _ResourceAuthorizationState:
+class _ServiceendpointExternaltfsState:
     def __init__(__self__, *,
-                 authorized: Optional[pulumi.Input[bool]] = None,
-                 definition_id: Optional[pulumi.Input[int]] = None,
+                 auth_personal: Optional[pulumi.Input['ServiceendpointExternaltfsAuthPersonalArgs']] = None,
+                 authorization: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
+                 connection_url: Optional[pulumi.Input[str]] = None,
+                 description: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
-                 resource_id: Optional[pulumi.Input[str]] = None,
-                 type: Optional[pulumi.Input[str]] = None):
+                 service_endpoint_name: Optional[pulumi.Input[str]] = None):
         """
-        Input properties used for looking up and filtering ResourceAuthorization resources.
-        :param pulumi.Input[bool] authorized: Set to true to allow public access in the project. Type: boolean.
-        :param pulumi.Input[int] definition_id: The ID of the build definition to authorize. Type: string.
-        :param pulumi.Input[str] project_id: The project ID or project name. Type: string.
-        :param pulumi.Input[str] resource_id: The ID of the resource to authorize. Type: string.
-        :param pulumi.Input[str] type: The type of the resource to authorize. Type: string. Valid values: `endpoint`, `queue`, `variablegroup`. Default value: `endpoint`.
-        """
-        if authorized is not None:
-            pulumi.set(__self__, "authorized", authorized)
-        if definition_id is not None:
-            pulumi.set(__self__, "definition_id", definition_id)
+        Input properties used for looking up and filtering ServiceendpointExternaltfs resources.
+        :param pulumi.Input['ServiceendpointExternaltfsAuthPersonalArgs'] auth_personal: An `auth_personal` block as documented below. Allows connecting using a personal access token.
+        :param pulumi.Input[str] connection_url: URL of the Azure DevOps organization or the TFS Project Collection to connect to.
+        :param pulumi.Input[str] project_id: The ID of the project.
+        :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
+        """
+        if auth_personal is not None:
+            pulumi.set(__self__, "auth_personal", auth_personal)
+        if authorization is not None:
+            pulumi.set(__self__, "authorization", authorization)
+        if connection_url is not None:
+            pulumi.set(__self__, "connection_url", connection_url)
+        if description is not None:
+            pulumi.set(__self__, "description", description)
         if project_id is not None:
             pulumi.set(__self__, "project_id", project_id)
-        if resource_id is not None:
-            pulumi.set(__self__, "resource_id", resource_id)
-        if type is not None:
-            pulumi.set(__self__, "type", type)
+        if service_endpoint_name is not None:
+            pulumi.set(__self__, "service_endpoint_name", service_endpoint_name)
 
     @property
-    @pulumi.getter
-    def authorized(self) -> Optional[pulumi.Input[bool]]:
+    @pulumi.getter(name="authPersonal")
+    def auth_personal(self) -> Optional[pulumi.Input['ServiceendpointExternaltfsAuthPersonalArgs']]:
         """
-        Set to true to allow public access in the project. Type: boolean.
+        An `auth_personal` block as documented below. Allows connecting using a personal access token.
         """
-        return pulumi.get(self, "authorized")
+        return pulumi.get(self, "auth_personal")
+
+    @auth_personal.setter
+    def auth_personal(self, value: Optional[pulumi.Input['ServiceendpointExternaltfsAuthPersonalArgs']]):
+        pulumi.set(self, "auth_personal", value)
 
-    @authorized.setter
-    def authorized(self, value: Optional[pulumi.Input[bool]]):
-        pulumi.set(self, "authorized", value)
+    @property
+    @pulumi.getter
+    def authorization(self) -> Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]:
+        return pulumi.get(self, "authorization")
+
+    @authorization.setter
+    def authorization(self, value: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]):
+        pulumi.set(self, "authorization", value)
 
     @property
-    @pulumi.getter(name="definitionId")
-    def definition_id(self) -> Optional[pulumi.Input[int]]:
+    @pulumi.getter(name="connectionUrl")
+    def connection_url(self) -> Optional[pulumi.Input[str]]:
         """
-        The ID of the build definition to authorize. Type: string.
+        URL of the Azure DevOps organization or the TFS Project Collection to connect to.
         """
-        return pulumi.get(self, "definition_id")
+        return pulumi.get(self, "connection_url")
+
+    @connection_url.setter
+    def connection_url(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "connection_url", value)
+
+    @property
+    @pulumi.getter
+    def description(self) -> Optional[pulumi.Input[str]]:
+        return pulumi.get(self, "description")
 
-    @definition_id.setter
-    def definition_id(self, value: Optional[pulumi.Input[int]]):
-        pulumi.set(self, "definition_id", value)
+    @description.setter
+    def description(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "description", value)
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> Optional[pulumi.Input[str]]:
         """
-        The project ID or project name. Type: string.
+        The ID of the project.
         """
         return pulumi.get(self, "project_id")
 
     @project_id.setter
     def project_id(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "project_id", value)
 
     @property
-    @pulumi.getter(name="resourceId")
-    def resource_id(self) -> Optional[pulumi.Input[str]]:
-        """
-        The ID of the resource to authorize. Type: string.
-        """
-        return pulumi.get(self, "resource_id")
-
-    @resource_id.setter
-    def resource_id(self, value: Optional[pulumi.Input[str]]):
-        pulumi.set(self, "resource_id", value)
-
-    @property
-    @pulumi.getter
-    def type(self) -> Optional[pulumi.Input[str]]:
+    @pulumi.getter(name="serviceEndpointName")
+    def service_endpoint_name(self) -> Optional[pulumi.Input[str]]:
         """
-        The type of the resource to authorize. Type: string. Valid values: `endpoint`, `queue`, `variablegroup`. Default value: `endpoint`.
+        The Service Endpoint name.
         """
-        return pulumi.get(self, "type")
+        return pulumi.get(self, "service_endpoint_name")
 
-    @type.setter
-    def type(self, value: Optional[pulumi.Input[str]]):
-        pulumi.set(self, "type", value)
+    @service_endpoint_name.setter
+    def service_endpoint_name(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "service_endpoint_name", value)
 
 
-warnings.warn("""azuredevops.security.ResourceAuthorization has been deprecated in favor of azuredevops.ResourceAuthorization""", DeprecationWarning)
-
-
-class ResourceAuthorization(pulumi.CustomResource):
-    warnings.warn("""azuredevops.security.ResourceAuthorization has been deprecated in favor of azuredevops.ResourceAuthorization""", DeprecationWarning)
-
+class ServiceendpointExternaltfs(pulumi.CustomResource):
     @overload
     def __init__(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
-                 authorized: Optional[pulumi.Input[bool]] = None,
-                 definition_id: Optional[pulumi.Input[int]] = None,
+                 auth_personal: Optional[pulumi.Input[pulumi.InputType['ServiceendpointExternaltfsAuthPersonalArgs']]] = None,
+                 authorization: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
+                 connection_url: Optional[pulumi.Input[str]] = None,
+                 description: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
-                 resource_id: Optional[pulumi.Input[str]] = None,
-                 type: Optional[pulumi.Input[str]] = None,
+                 service_endpoint_name: Optional[pulumi.Input[str]] = None,
                  __props__=None):
         """
-        Manages authorization of resources, e.g. for access in build pipelines.
+        Manages an Azure Repos/Team Foundation Server service endpoint within Azure DevOps.
 
-        Currently supported resources: service endpoint (aka service connection, endpoint).
+        ## Relevant Links
 
-        ## Example Usage
+        - [Azure DevOps Service REST API 6.0 - Service Endpoints](https://docs.microsoft.com/en-us/rest/api/azure/devops/serviceendpoint/endpoints?view=azure-devops-rest-6.0)
 
-        ```python
-        import pulumi
-        import pulumi_azuredevops as azuredevops
-
-        example_project = azuredevops.Project("exampleProject",
-            visibility="private",
-            version_control="Git",
-            work_item_template="Agile",
-            description="Managed by Terraform")
-        example_service_endpoint_bit_bucket = azuredevops.ServiceEndpointBitBucket("exampleServiceEndpointBitBucket",
-            project_id=example_project.id,
-            username="username",
-            password="password",
-            service_endpoint_name="example-bitbucket",
-            description="Managed by Terraform")
-        example_resource_authorization = azuredevops.ResourceAuthorization("exampleResourceAuthorization",
-            project_id=example_project.id,
-            resource_id=example_service_endpoint_bit_bucket.id,
-            authorized=True)
-        ```
-        ## Relevant Links
+        ## Import
 
-        - [Azure DevOps Service REST API 6.0 - Authorize Definition Resource](https://docs.microsoft.com/en-us/rest/api/azure/devops/build/resources/authorize%20definition%20resources?view=azure-devops-rest-6.0)
+        Azure DevOps Service Endpoint External TFS can be imported using **projectID/serviceEndpointID** or **projectName/serviceEndpointID**
+
+        ```sh
+         $ pulumi import azuredevops:index/serviceendpointExternaltfs:ServiceendpointExternaltfs example 00000000-0000-0000-0000-000000000000/00000000-0000-0000-0000-000000000000
+        ```
 
         :param str resource_name: The name of the resource.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[bool] authorized: Set to true to allow public access in the project. Type: boolean.
-        :param pulumi.Input[int] definition_id: The ID of the build definition to authorize. Type: string.
-        :param pulumi.Input[str] project_id: The project ID or project name. Type: string.
-        :param pulumi.Input[str] resource_id: The ID of the resource to authorize. Type: string.
-        :param pulumi.Input[str] type: The type of the resource to authorize. Type: string. Valid values: `endpoint`, `queue`, `variablegroup`. Default value: `endpoint`.
+        :param pulumi.Input[pulumi.InputType['ServiceendpointExternaltfsAuthPersonalArgs']] auth_personal: An `auth_personal` block as documented below. Allows connecting using a personal access token.
+        :param pulumi.Input[str] connection_url: URL of the Azure DevOps organization or the TFS Project Collection to connect to.
+        :param pulumi.Input[str] project_id: The ID of the project.
+        :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         """
         ...
     @overload
     def __init__(__self__,
                  resource_name: str,
-                 args: ResourceAuthorizationArgs,
+                 args: ServiceendpointExternaltfsArgs,
                  opts: Optional[pulumi.ResourceOptions] = None):
         """
-        Manages authorization of resources, e.g. for access in build pipelines.
+        Manages an Azure Repos/Team Foundation Server service endpoint within Azure DevOps.
 
-        Currently supported resources: service endpoint (aka service connection, endpoint).
+        ## Relevant Links
 
-        ## Example Usage
+        - [Azure DevOps Service REST API 6.0 - Service Endpoints](https://docs.microsoft.com/en-us/rest/api/azure/devops/serviceendpoint/endpoints?view=azure-devops-rest-6.0)
 
-        ```python
-        import pulumi
-        import pulumi_azuredevops as azuredevops
-
-        example_project = azuredevops.Project("exampleProject",
-            visibility="private",
-            version_control="Git",
-            work_item_template="Agile",
-            description="Managed by Terraform")
-        example_service_endpoint_bit_bucket = azuredevops.ServiceEndpointBitBucket("exampleServiceEndpointBitBucket",
-            project_id=example_project.id,
-            username="username",
-            password="password",
-            service_endpoint_name="example-bitbucket",
-            description="Managed by Terraform")
-        example_resource_authorization = azuredevops.ResourceAuthorization("exampleResourceAuthorization",
-            project_id=example_project.id,
-            resource_id=example_service_endpoint_bit_bucket.id,
-            authorized=True)
-        ```
-        ## Relevant Links
+        ## Import
+
+        Azure DevOps Service Endpoint External TFS can be imported using **projectID/serviceEndpointID** or **projectName/serviceEndpointID**
 
-        - [Azure DevOps Service REST API 6.0 - Authorize Definition Resource](https://docs.microsoft.com/en-us/rest/api/azure/devops/build/resources/authorize%20definition%20resources?view=azure-devops-rest-6.0)
+        ```sh
+         $ pulumi import azuredevops:index/serviceendpointExternaltfs:ServiceendpointExternaltfs example 00000000-0000-0000-0000-000000000000/00000000-0000-0000-0000-000000000000
+        ```
 
         :param str resource_name: The name of the resource.
-        :param ResourceAuthorizationArgs args: The arguments to use to populate this resource's properties.
+        :param ServiceendpointExternaltfsArgs args: The arguments to use to populate this resource's properties.
         :param pulumi.ResourceOptions opts: Options for the resource.
         """
         ...
     def __init__(__self__, resource_name: str, *args, **kwargs):
-        resource_args, opts = _utilities.get_resource_args_opts(ResourceAuthorizationArgs, pulumi.ResourceOptions, *args, **kwargs)
+        resource_args, opts = _utilities.get_resource_args_opts(ServiceendpointExternaltfsArgs, pulumi.ResourceOptions, *args, **kwargs)
         if resource_args is not None:
             __self__._internal_init(resource_name, opts, **resource_args.__dict__)
         else:
             __self__._internal_init(resource_name, *args, **kwargs)
 
     def _internal_init(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
-                 authorized: Optional[pulumi.Input[bool]] = None,
-                 definition_id: Optional[pulumi.Input[int]] = None,
+                 auth_personal: Optional[pulumi.Input[pulumi.InputType['ServiceendpointExternaltfsAuthPersonalArgs']]] = None,
+                 authorization: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
+                 connection_url: Optional[pulumi.Input[str]] = None,
+                 description: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
-                 resource_id: Optional[pulumi.Input[str]] = None,
-                 type: Optional[pulumi.Input[str]] = None,
+                 service_endpoint_name: Optional[pulumi.Input[str]] = None,
                  __props__=None):
-        pulumi.log.warn("""ResourceAuthorization is deprecated: azuredevops.security.ResourceAuthorization has been deprecated in favor of azuredevops.ResourceAuthorization""")
         opts = pulumi.ResourceOptions.merge(_utilities.get_resource_opts_defaults(), opts)
         if not isinstance(opts, pulumi.ResourceOptions):
             raise TypeError('Expected resource options to be a ResourceOptions instance')
         if opts.id is None:
             if __props__ is not None:
                 raise TypeError('__props__ is only valid when passed in combination with a valid opts.id to get an existing resource')
-            __props__ = ResourceAuthorizationArgs.__new__(ResourceAuthorizationArgs)
+            __props__ = ServiceendpointExternaltfsArgs.__new__(ServiceendpointExternaltfsArgs)
 
-            if authorized is None and not opts.urn:
-                raise TypeError("Missing required property 'authorized'")
-            __props__.__dict__["authorized"] = authorized
-            __props__.__dict__["definition_id"] = definition_id
+            if auth_personal is None and not opts.urn:
+                raise TypeError("Missing required property 'auth_personal'")
+            __props__.__dict__["auth_personal"] = auth_personal
+            __props__.__dict__["authorization"] = authorization
+            if connection_url is None and not opts.urn:
+                raise TypeError("Missing required property 'connection_url'")
+            __props__.__dict__["connection_url"] = connection_url
+            __props__.__dict__["description"] = description
             if project_id is None and not opts.urn:
                 raise TypeError("Missing required property 'project_id'")
             __props__.__dict__["project_id"] = project_id
-            if resource_id is None and not opts.urn:
-                raise TypeError("Missing required property 'resource_id'")
-            __props__.__dict__["resource_id"] = resource_id
-            __props__.__dict__["type"] = type
-        super(ResourceAuthorization, __self__).__init__(
-            'azuredevops:Security/resourceAuthorization:ResourceAuthorization',
+            if service_endpoint_name is None and not opts.urn:
+                raise TypeError("Missing required property 'service_endpoint_name'")
+            __props__.__dict__["service_endpoint_name"] = service_endpoint_name
+        super(ServiceendpointExternaltfs, __self__).__init__(
+            'azuredevops:index/serviceendpointExternaltfs:ServiceendpointExternaltfs',
             resource_name,
             __props__,
             opts)
 
     @staticmethod
     def get(resource_name: str,
             id: pulumi.Input[str],
             opts: Optional[pulumi.ResourceOptions] = None,
-            authorized: Optional[pulumi.Input[bool]] = None,
-            definition_id: Optional[pulumi.Input[int]] = None,
+            auth_personal: Optional[pulumi.Input[pulumi.InputType['ServiceendpointExternaltfsAuthPersonalArgs']]] = None,
+            authorization: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
+            connection_url: Optional[pulumi.Input[str]] = None,
+            description: Optional[pulumi.Input[str]] = None,
             project_id: Optional[pulumi.Input[str]] = None,
-            resource_id: Optional[pulumi.Input[str]] = None,
-            type: Optional[pulumi.Input[str]] = None) -> 'ResourceAuthorization':
+            service_endpoint_name: Optional[pulumi.Input[str]] = None) -> 'ServiceendpointExternaltfs':
         """
-        Get an existing ResourceAuthorization resource's state with the given name, id, and optional extra
+        Get an existing ServiceendpointExternaltfs resource's state with the given name, id, and optional extra
         properties used to qualify the lookup.
 
         :param str resource_name: The unique name of the resulting resource.
         :param pulumi.Input[str] id: The unique provider ID of the resource to lookup.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[bool] authorized: Set to true to allow public access in the project. Type: boolean.
-        :param pulumi.Input[int] definition_id: The ID of the build definition to authorize. Type: string.
-        :param pulumi.Input[str] project_id: The project ID or project name. Type: string.
-        :param pulumi.Input[str] resource_id: The ID of the resource to authorize. Type: string.
-        :param pulumi.Input[str] type: The type of the resource to authorize. Type: string. Valid values: `endpoint`, `queue`, `variablegroup`. Default value: `endpoint`.
+        :param pulumi.Input[pulumi.InputType['ServiceendpointExternaltfsAuthPersonalArgs']] auth_personal: An `auth_personal` block as documented below. Allows connecting using a personal access token.
+        :param pulumi.Input[str] connection_url: URL of the Azure DevOps organization or the TFS Project Collection to connect to.
+        :param pulumi.Input[str] project_id: The ID of the project.
+        :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
 
-        __props__ = _ResourceAuthorizationState.__new__(_ResourceAuthorizationState)
+        __props__ = _ServiceendpointExternaltfsState.__new__(_ServiceendpointExternaltfsState)
 
-        __props__.__dict__["authorized"] = authorized
-        __props__.__dict__["definition_id"] = definition_id
+        __props__.__dict__["auth_personal"] = auth_personal
+        __props__.__dict__["authorization"] = authorization
+        __props__.__dict__["connection_url"] = connection_url
+        __props__.__dict__["description"] = description
         __props__.__dict__["project_id"] = project_id
-        __props__.__dict__["resource_id"] = resource_id
-        __props__.__dict__["type"] = type
-        return ResourceAuthorization(resource_name, opts=opts, __props__=__props__)
+        __props__.__dict__["service_endpoint_name"] = service_endpoint_name
+        return ServiceendpointExternaltfs(resource_name, opts=opts, __props__=__props__)
 
     @property
-    @pulumi.getter
-    def authorized(self) -> pulumi.Output[bool]:
+    @pulumi.getter(name="authPersonal")
+    def auth_personal(self) -> pulumi.Output['outputs.ServiceendpointExternaltfsAuthPersonal']:
         """
-        Set to true to allow public access in the project. Type: boolean.
+        An `auth_personal` block as documented below. Allows connecting using a personal access token.
         """
-        return pulumi.get(self, "authorized")
+        return pulumi.get(self, "auth_personal")
+
+    @property
+    @pulumi.getter
+    def authorization(self) -> pulumi.Output[Mapping[str, str]]:
+        return pulumi.get(self, "authorization")
 
     @property
-    @pulumi.getter(name="definitionId")
-    def definition_id(self) -> pulumi.Output[Optional[int]]:
+    @pulumi.getter(name="connectionUrl")
+    def connection_url(self) -> pulumi.Output[str]:
         """
-        The ID of the build definition to authorize. Type: string.
+        URL of the Azure DevOps organization or the TFS Project Collection to connect to.
         """
-        return pulumi.get(self, "definition_id")
+        return pulumi.get(self, "connection_url")
+
+    @property
+    @pulumi.getter
+    def description(self) -> pulumi.Output[Optional[str]]:
+        return pulumi.get(self, "description")
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> pulumi.Output[str]:
         """
-        The project ID or project name. Type: string.
+        The ID of the project.
         """
         return pulumi.get(self, "project_id")
 
     @property
-    @pulumi.getter(name="resourceId")
-    def resource_id(self) -> pulumi.Output[str]:
-        """
-        The ID of the resource to authorize. Type: string.
-        """
-        return pulumi.get(self, "resource_id")
-
-    @property
-    @pulumi.getter
-    def type(self) -> pulumi.Output[Optional[str]]:
+    @pulumi.getter(name="serviceEndpointName")
+    def service_endpoint_name(self) -> pulumi.Output[str]:
         """
-        The type of the resource to authorize. Type: string. Valid values: `endpoint`, `queue`, `variablegroup`. Default value: `endpoint`.
+        The Service Endpoint name.
         """
-        return pulumi.get(self, "type")
+        return pulumi.get(self, "service_endpoint_name")
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_artifactory.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_artifactory.py`

 * *Files 3% similar despite different names*

```diff
@@ -24,14 +24,17 @@
                  authorization: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
                  description: Optional[pulumi.Input[str]] = None):
         """
         The set of arguments for constructing a ServiceEndpointArtifactory resource.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         :param pulumi.Input[str] url: URL of the Artifactory server to connect with.
+               
+               _Note: URL should not end in a slash character._
+               * either `authentication_token` or `authentication_basic` (one is required)
         :param pulumi.Input[str] description: The Service Endpoint description.
         """
         pulumi.set(__self__, "project_id", project_id)
         pulumi.set(__self__, "service_endpoint_name", service_endpoint_name)
         pulumi.set(__self__, "url", url)
         if authentication_basic is not None:
             pulumi.set(__self__, "authentication_basic", authentication_basic)
@@ -67,14 +70,17 @@
         pulumi.set(self, "service_endpoint_name", value)
 
     @property
     @pulumi.getter
     def url(self) -> pulumi.Input[str]:
         """
         URL of the Artifactory server to connect with.
+
+        _Note: URL should not end in a slash character._
+        * either `authentication_token` or `authentication_basic` (one is required)
         """
         return pulumi.get(self, "url")
 
     @url.setter
     def url(self, value: pulumi.Input[str]):
         pulumi.set(self, "url", value)
 
@@ -130,14 +136,17 @@
                  url: Optional[pulumi.Input[str]] = None):
         """
         Input properties used for looking up and filtering ServiceEndpointArtifactory resources.
         :param pulumi.Input[str] description: The Service Endpoint description.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         :param pulumi.Input[str] url: URL of the Artifactory server to connect with.
+               
+               _Note: URL should not end in a slash character._
+               * either `authentication_token` or `authentication_basic` (one is required)
         """
         if authentication_basic is not None:
             pulumi.set(__self__, "authentication_basic", authentication_basic)
         if authentication_token is not None:
             pulumi.set(__self__, "authentication_token", authentication_token)
         if authorization is not None:
             pulumi.set(__self__, "authorization", authorization)
@@ -214,14 +223,17 @@
         pulumi.set(self, "service_endpoint_name", value)
 
     @property
     @pulumi.getter
     def url(self) -> Optional[pulumi.Input[str]]:
         """
         URL of the Artifactory server to connect with.
+
+        _Note: URL should not end in a slash character._
+        * either `authentication_token` or `authentication_basic` (one is required)
         """
         return pulumi.get(self, "url")
 
     @url.setter
     def url(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "url", value)
 
@@ -298,14 +310,17 @@
 
         :param str resource_name: The name of the resource.
         :param pulumi.ResourceOptions opts: Options for the resource.
         :param pulumi.Input[str] description: The Service Endpoint description.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         :param pulumi.Input[str] url: URL of the Artifactory server to connect with.
+               
+               _Note: URL should not end in a slash character._
+               * either `authentication_token` or `authentication_basic` (one is required)
         """
         ...
     @overload
     def __init__(__self__,
                  resource_name: str,
                  args: ServiceEndpointArtifactoryArgs,
                  opts: Optional[pulumi.ResourceOptions] = None):
@@ -434,14 +449,17 @@
         :param str resource_name: The unique name of the resulting resource.
         :param pulumi.Input[str] id: The unique provider ID of the resource to lookup.
         :param pulumi.ResourceOptions opts: Options for the resource.
         :param pulumi.Input[str] description: The Service Endpoint description.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         :param pulumi.Input[str] url: URL of the Artifactory server to connect with.
+               
+               _Note: URL should not end in a slash character._
+               * either `authentication_token` or `authentication_basic` (one is required)
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
 
         __props__ = _ServiceEndpointArtifactoryState.__new__(_ServiceEndpointArtifactoryState)
 
         __props__.__dict__["authentication_basic"] = authentication_basic
         __props__.__dict__["authentication_token"] = authentication_token
@@ -492,10 +510,13 @@
         return pulumi.get(self, "service_endpoint_name")
 
     @property
     @pulumi.getter
     def url(self) -> pulumi.Output[str]:
         """
         URL of the Artifactory server to connect with.
+
+        _Note: URL should not end in a slash character._
+        * either `authentication_token` or `authentication_basic` (one is required)
         """
         return pulumi.get(self, "url")
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_aws.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_aws.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_azure_dev_ops.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_azure_dev_ops.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_azure_ecr.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_azure_ecr.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_azure_rm.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_azure_rm.py`

 * *Files 5% similar despite different names*

```diff
@@ -36,14 +36,16 @@
         :param pulumi.Input[str] azurerm_management_group_id: The Management group ID of the Azure targets.
         :param pulumi.Input[str] azurerm_management_group_name: The Management group Name of the targets.
         :param pulumi.Input[str] azurerm_subscription_id: The Subscription ID of the Azure targets.
         :param pulumi.Input[str] azurerm_subscription_name: The Subscription Name of the targets.
         :param pulumi.Input['ServiceEndpointAzureRMCredentialsArgs'] credentials: A `credentials` block.
         :param pulumi.Input[str] description: Service connection description.
         :param pulumi.Input[str] environment: The Cloud Environment to use. Defaults to `AzureCloud`. Possible values are `AzureCloud`, `AzureChinaCloud`. Changing this forces a new resource to be created.
+               
+               > **NOTE:** One of either `Subscription` scoped i.e. `azurerm_subscription_id`, `azurerm_subscription_name` or `ManagementGroup` scoped i.e. `azurerm_management_group_id`, `azurerm_management_group_name` values must be specified.
         :param pulumi.Input[str] resource_group: The resource group used for scope of automatic service endpoint.
         """
         pulumi.set(__self__, "azurerm_spn_tenantid", azurerm_spn_tenantid)
         pulumi.set(__self__, "project_id", project_id)
         pulumi.set(__self__, "service_endpoint_name", service_endpoint_name)
         if authorization is not None:
             pulumi.set(__self__, "authorization", authorization)
@@ -182,14 +184,16 @@
         pulumi.set(self, "description", value)
 
     @property
     @pulumi.getter
     def environment(self) -> Optional[pulumi.Input[str]]:
         """
         The Cloud Environment to use. Defaults to `AzureCloud`. Possible values are `AzureCloud`, `AzureChinaCloud`. Changing this forces a new resource to be created.
+
+        > **NOTE:** One of either `Subscription` scoped i.e. `azurerm_subscription_id`, `azurerm_subscription_name` or `ManagementGroup` scoped i.e. `azurerm_management_group_id`, `azurerm_management_group_name` values must be specified.
         """
         return pulumi.get(self, "environment")
 
     @environment.setter
     def environment(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "environment", value)
 
@@ -227,14 +231,16 @@
         :param pulumi.Input[str] azurerm_management_group_name: The Management group Name of the targets.
         :param pulumi.Input[str] azurerm_spn_tenantid: The Tenant ID if the service principal.
         :param pulumi.Input[str] azurerm_subscription_id: The Subscription ID of the Azure targets.
         :param pulumi.Input[str] azurerm_subscription_name: The Subscription Name of the targets.
         :param pulumi.Input['ServiceEndpointAzureRMCredentialsArgs'] credentials: A `credentials` block.
         :param pulumi.Input[str] description: Service connection description.
         :param pulumi.Input[str] environment: The Cloud Environment to use. Defaults to `AzureCloud`. Possible values are `AzureCloud`, `AzureChinaCloud`. Changing this forces a new resource to be created.
+               
+               > **NOTE:** One of either `Subscription` scoped i.e. `azurerm_subscription_id`, `azurerm_subscription_name` or `ManagementGroup` scoped i.e. `azurerm_management_group_id`, `azurerm_management_group_name` values must be specified.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] resource_group: The resource group used for scope of automatic service endpoint.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint Name.
         """
         if authorization is not None:
             pulumi.set(__self__, "authorization", authorization)
         if azurerm_management_group_id is not None:
@@ -354,14 +360,16 @@
         pulumi.set(self, "description", value)
 
     @property
     @pulumi.getter
     def environment(self) -> Optional[pulumi.Input[str]]:
         """
         The Cloud Environment to use. Defaults to `AzureCloud`. Possible values are `AzureCloud`, `AzureChinaCloud`. Changing this forces a new resource to be created.
+
+        > **NOTE:** One of either `Subscription` scoped i.e. `azurerm_subscription_id`, `azurerm_subscription_name` or `ManagementGroup` scoped i.e. `azurerm_management_group_id`, `azurerm_management_group_name` values must be specified.
         """
         return pulumi.get(self, "environment")
 
     @environment.setter
     def environment(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "environment", value)
 
@@ -511,14 +519,16 @@
         :param pulumi.Input[str] azurerm_management_group_name: The Management group Name of the targets.
         :param pulumi.Input[str] azurerm_spn_tenantid: The Tenant ID if the service principal.
         :param pulumi.Input[str] azurerm_subscription_id: The Subscription ID of the Azure targets.
         :param pulumi.Input[str] azurerm_subscription_name: The Subscription Name of the targets.
         :param pulumi.Input[pulumi.InputType['ServiceEndpointAzureRMCredentialsArgs']] credentials: A `credentials` block.
         :param pulumi.Input[str] description: Service connection description.
         :param pulumi.Input[str] environment: The Cloud Environment to use. Defaults to `AzureCloud`. Possible values are `AzureCloud`, `AzureChinaCloud`. Changing this forces a new resource to be created.
+               
+               > **NOTE:** One of either `Subscription` scoped i.e. `azurerm_subscription_id`, `azurerm_subscription_name` or `ManagementGroup` scoped i.e. `azurerm_management_group_id`, `azurerm_management_group_name` values must be specified.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] resource_group: The resource group used for scope of automatic service endpoint.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint Name.
         """
         ...
     @overload
     def __init__(__self__,
@@ -699,14 +709,16 @@
         :param pulumi.Input[str] azurerm_management_group_name: The Management group Name of the targets.
         :param pulumi.Input[str] azurerm_spn_tenantid: The Tenant ID if the service principal.
         :param pulumi.Input[str] azurerm_subscription_id: The Subscription ID of the Azure targets.
         :param pulumi.Input[str] azurerm_subscription_name: The Subscription Name of the targets.
         :param pulumi.Input[pulumi.InputType['ServiceEndpointAzureRMCredentialsArgs']] credentials: A `credentials` block.
         :param pulumi.Input[str] description: Service connection description.
         :param pulumi.Input[str] environment: The Cloud Environment to use. Defaults to `AzureCloud`. Possible values are `AzureCloud`, `AzureChinaCloud`. Changing this forces a new resource to be created.
+               
+               > **NOTE:** One of either `Subscription` scoped i.e. `azurerm_subscription_id`, `azurerm_subscription_name` or `ManagementGroup` scoped i.e. `azurerm_management_group_id`, `azurerm_management_group_name` values must be specified.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] resource_group: The resource group used for scope of automatic service endpoint.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint Name.
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
 
         __props__ = _ServiceEndpointAzureRMState.__new__(_ServiceEndpointAzureRMState)
@@ -787,14 +799,16 @@
         return pulumi.get(self, "description")
 
     @property
     @pulumi.getter
     def environment(self) -> pulumi.Output[Optional[str]]:
         """
         The Cloud Environment to use. Defaults to `AzureCloud`. Possible values are `AzureCloud`, `AzureChinaCloud`. Changing this forces a new resource to be created.
+
+        > **NOTE:** One of either `Subscription` scoped i.e. `azurerm_subscription_id`, `azurerm_subscription_name` or `ManagementGroup` scoped i.e. `azurerm_management_group_id`, `azurerm_management_group_name` values must be specified.
         """
         return pulumi.get(self, "environment")
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> pulumi.Output[str]:
         """
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_bit_bucket.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_bit_bucket.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_docker_registry.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_docker_registry.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_generic.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_generic.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_generic_git.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_generic_git.py`

 * *Files 2% similar despite different names*

```diff
@@ -25,14 +25,16 @@
         """
         The set of arguments for constructing a ServiceEndpointGenericGit resource.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] repository_url: The URL of the repository associated with the service endpoint.
         :param pulumi.Input[str] service_endpoint_name: The name of the service endpoint.
         :param pulumi.Input[bool] enable_pipelines_access: A value indicating whether or not to attempt accessing this git server from Azure Pipelines.
         :param pulumi.Input[str] password: The PAT or password used to authenticate to the git repository.
+               
+               > **Note** For AzureDevOps Git, PAT should be used as the password.
         :param pulumi.Input[str] username: The username used to authenticate to the git repository.
         """
         pulumi.set(__self__, "project_id", project_id)
         pulumi.set(__self__, "repository_url", repository_url)
         pulumi.set(__self__, "service_endpoint_name", service_endpoint_name)
         if authorization is not None:
             pulumi.set(__self__, "authorization", authorization)
@@ -112,14 +114,16 @@
         pulumi.set(self, "enable_pipelines_access", value)
 
     @property
     @pulumi.getter
     def password(self) -> Optional[pulumi.Input[str]]:
         """
         The PAT or password used to authenticate to the git repository.
+
+        > **Note** For AzureDevOps Git, PAT should be used as the password.
         """
         return pulumi.get(self, "password")
 
     @password.setter
     def password(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "password", value)
 
@@ -148,14 +152,16 @@
                  repository_url: Optional[pulumi.Input[str]] = None,
                  service_endpoint_name: Optional[pulumi.Input[str]] = None,
                  username: Optional[pulumi.Input[str]] = None):
         """
         Input properties used for looking up and filtering ServiceEndpointGenericGit resources.
         :param pulumi.Input[bool] enable_pipelines_access: A value indicating whether or not to attempt accessing this git server from Azure Pipelines.
         :param pulumi.Input[str] password: The PAT or password used to authenticate to the git repository.
+               
+               > **Note** For AzureDevOps Git, PAT should be used as the password.
         :param pulumi.Input[str] password_hash: A bcrypted hash of the attribute 'password'
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] repository_url: The URL of the repository associated with the service endpoint.
         :param pulumi.Input[str] service_endpoint_name: The name of the service endpoint.
         :param pulumi.Input[str] username: The username used to authenticate to the git repository.
         """
         if authorization is not None:
@@ -208,14 +214,16 @@
         pulumi.set(self, "enable_pipelines_access", value)
 
     @property
     @pulumi.getter
     def password(self) -> Optional[pulumi.Input[str]]:
         """
         The PAT or password used to authenticate to the git repository.
+
+        > **Note** For AzureDevOps Git, PAT should be used as the password.
         """
         return pulumi.get(self, "password")
 
     @password.setter
     def password(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "password", value)
 
@@ -329,14 +337,16 @@
          $ pulumi import azuredevops:index/serviceEndpointGenericGit:ServiceEndpointGenericGit example 00000000-0000-0000-0000-000000000000/00000000-0000-0000-0000-000000000000
         ```
 
         :param str resource_name: The name of the resource.
         :param pulumi.ResourceOptions opts: Options for the resource.
         :param pulumi.Input[bool] enable_pipelines_access: A value indicating whether or not to attempt accessing this git server from Azure Pipelines.
         :param pulumi.Input[str] password: The PAT or password used to authenticate to the git repository.
+               
+               > **Note** For AzureDevOps Git, PAT should be used as the password.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] repository_url: The URL of the repository associated with the service endpoint.
         :param pulumi.Input[str] service_endpoint_name: The name of the service endpoint.
         :param pulumi.Input[str] username: The username used to authenticate to the git repository.
         """
         ...
     @overload
@@ -452,14 +462,16 @@
         properties used to qualify the lookup.
 
         :param str resource_name: The unique name of the resulting resource.
         :param pulumi.Input[str] id: The unique provider ID of the resource to lookup.
         :param pulumi.ResourceOptions opts: Options for the resource.
         :param pulumi.Input[bool] enable_pipelines_access: A value indicating whether or not to attempt accessing this git server from Azure Pipelines.
         :param pulumi.Input[str] password: The PAT or password used to authenticate to the git repository.
+               
+               > **Note** For AzureDevOps Git, PAT should be used as the password.
         :param pulumi.Input[str] password_hash: A bcrypted hash of the attribute 'password'
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] repository_url: The URL of the repository associated with the service endpoint.
         :param pulumi.Input[str] service_endpoint_name: The name of the service endpoint.
         :param pulumi.Input[str] username: The username used to authenticate to the git repository.
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
@@ -496,14 +508,16 @@
         return pulumi.get(self, "enable_pipelines_access")
 
     @property
     @pulumi.getter
     def password(self) -> pulumi.Output[Optional[str]]:
         """
         The PAT or password used to authenticate to the git repository.
+
+        > **Note** For AzureDevOps Git, PAT should be used as the password.
         """
         return pulumi.get(self, "password")
 
     @property
     @pulumi.getter(name="passwordHash")
     def password_hash(self) -> pulumi.Output[str]:
         """
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_git_hub.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_git_hub.py`

 * *Files 6% similar despite different names*

```diff
@@ -22,15 +22,14 @@
                  auth_personal: Optional[pulumi.Input['ServiceEndpointGitHubAuthPersonalArgs']] = None,
                  authorization: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
                  description: Optional[pulumi.Input[str]] = None):
         """
         The set of arguments for constructing a ServiceEndpointGitHub resource.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
-        :param pulumi.Input['ServiceEndpointGitHubAuthOauthArgs'] auth_oauth: An `auth_oauth` block as documented below. Allows connecting using an Oauth token.
         :param pulumi.Input['ServiceEndpointGitHubAuthPersonalArgs'] auth_personal: An `auth_personal` block as documented below. Allows connecting using a personal access token.
         """
         pulumi.set(__self__, "project_id", project_id)
         pulumi.set(__self__, "service_endpoint_name", service_endpoint_name)
         if auth_oauth is not None:
             pulumi.set(__self__, "auth_oauth", auth_oauth)
         if auth_personal is not None:
@@ -63,17 +62,14 @@
     @service_endpoint_name.setter
     def service_endpoint_name(self, value: pulumi.Input[str]):
         pulumi.set(self, "service_endpoint_name", value)
 
     @property
     @pulumi.getter(name="authOauth")
     def auth_oauth(self) -> Optional[pulumi.Input['ServiceEndpointGitHubAuthOauthArgs']]:
-        """
-        An `auth_oauth` block as documented below. Allows connecting using an Oauth token.
-        """
         return pulumi.get(self, "auth_oauth")
 
     @auth_oauth.setter
     def auth_oauth(self, value: Optional[pulumi.Input['ServiceEndpointGitHubAuthOauthArgs']]):
         pulumi.set(self, "auth_oauth", value)
 
     @property
@@ -114,15 +110,14 @@
                  auth_personal: Optional[pulumi.Input['ServiceEndpointGitHubAuthPersonalArgs']] = None,
                  authorization: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
                  description: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  service_endpoint_name: Optional[pulumi.Input[str]] = None):
         """
         Input properties used for looking up and filtering ServiceEndpointGitHub resources.
-        :param pulumi.Input['ServiceEndpointGitHubAuthOauthArgs'] auth_oauth: An `auth_oauth` block as documented below. Allows connecting using an Oauth token.
         :param pulumi.Input['ServiceEndpointGitHubAuthPersonalArgs'] auth_personal: An `auth_personal` block as documented below. Allows connecting using a personal access token.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         """
         if auth_oauth is not None:
             pulumi.set(__self__, "auth_oauth", auth_oauth)
         if auth_personal is not None:
@@ -135,17 +130,14 @@
             pulumi.set(__self__, "project_id", project_id)
         if service_endpoint_name is not None:
             pulumi.set(__self__, "service_endpoint_name", service_endpoint_name)
 
     @property
     @pulumi.getter(name="authOauth")
     def auth_oauth(self) -> Optional[pulumi.Input['ServiceEndpointGitHubAuthOauthArgs']]:
-        """
-        An `auth_oauth` block as documented below. Allows connecting using an Oauth token.
-        """
         return pulumi.get(self, "auth_oauth")
 
     @auth_oauth.setter
     def auth_oauth(self, value: Optional[pulumi.Input['ServiceEndpointGitHubAuthOauthArgs']]):
         pulumi.set(self, "auth_oauth", value)
 
     @property
@@ -278,15 +270,14 @@
 
         ```sh
          $ pulumi import azuredevops:index/serviceEndpointGitHub:ServiceEndpointGitHub example 00000000-0000-0000-0000-000000000000/00000000-0000-0000-0000-000000000000
         ```
 
         :param str resource_name: The name of the resource.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[pulumi.InputType['ServiceEndpointGitHubAuthOauthArgs']] auth_oauth: An `auth_oauth` block as documented below. Allows connecting using an Oauth token.
         :param pulumi.Input[pulumi.InputType['ServiceEndpointGitHubAuthPersonalArgs']] auth_personal: An `auth_personal` block as documented below. Allows connecting using a personal access token.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         """
         ...
     @overload
     def __init__(__self__,
@@ -419,15 +410,14 @@
         """
         Get an existing ServiceEndpointGitHub resource's state with the given name, id, and optional extra
         properties used to qualify the lookup.
 
         :param str resource_name: The unique name of the resulting resource.
         :param pulumi.Input[str] id: The unique provider ID of the resource to lookup.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[pulumi.InputType['ServiceEndpointGitHubAuthOauthArgs']] auth_oauth: An `auth_oauth` block as documented below. Allows connecting using an Oauth token.
         :param pulumi.Input[pulumi.InputType['ServiceEndpointGitHubAuthPersonalArgs']] auth_personal: An `auth_personal` block as documented below. Allows connecting using a personal access token.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
 
         __props__ = _ServiceEndpointGitHubState.__new__(_ServiceEndpointGitHubState)
@@ -439,17 +429,14 @@
         __props__.__dict__["project_id"] = project_id
         __props__.__dict__["service_endpoint_name"] = service_endpoint_name
         return ServiceEndpointGitHub(resource_name, opts=opts, __props__=__props__)
 
     @property
     @pulumi.getter(name="authOauth")
     def auth_oauth(self) -> pulumi.Output[Optional['outputs.ServiceEndpointGitHubAuthOauth']]:
-        """
-        An `auth_oauth` block as documented below. Allows connecting using an Oauth token.
-        """
         return pulumi.get(self, "auth_oauth")
 
     @property
     @pulumi.getter(name="authPersonal")
     def auth_personal(self) -> pulumi.Output[Optional['outputs.ServiceEndpointGitHubAuthPersonal']]:
         """
         An `auth_personal` block as documented below. Allows connecting using a personal access token.
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_git_hub_enterprise.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_git_hub_enterprise.py`

 * *Files 7% similar despite different names*

```diff
@@ -20,15 +20,14 @@
                  project_id: pulumi.Input[str],
                  service_endpoint_name: pulumi.Input[str],
                  url: pulumi.Input[str],
                  authorization: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
                  description: Optional[pulumi.Input[str]] = None):
         """
         The set of arguments for constructing a ServiceEndpointGitHubEnterprise resource.
-        :param pulumi.Input['ServiceEndpointGitHubEnterpriseAuthPersonalArgs'] auth_personal: An `auth_personal` block as documented below. Allows connecting using a personal access token.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         :param pulumi.Input[str] url: GitHub Enterprise Server Url.
         """
         pulumi.set(__self__, "auth_personal", auth_personal)
         pulumi.set(__self__, "project_id", project_id)
         pulumi.set(__self__, "service_endpoint_name", service_endpoint_name)
@@ -37,17 +36,14 @@
             pulumi.set(__self__, "authorization", authorization)
         if description is not None:
             pulumi.set(__self__, "description", description)
 
     @property
     @pulumi.getter(name="authPersonal")
     def auth_personal(self) -> pulumi.Input['ServiceEndpointGitHubEnterpriseAuthPersonalArgs']:
-        """
-        An `auth_personal` block as documented below. Allows connecting using a personal access token.
-        """
         return pulumi.get(self, "auth_personal")
 
     @auth_personal.setter
     def auth_personal(self, value: pulumi.Input['ServiceEndpointGitHubEnterpriseAuthPersonalArgs']):
         pulumi.set(self, "auth_personal", value)
 
     @property
@@ -112,15 +108,14 @@
                  authorization: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
                  description: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  service_endpoint_name: Optional[pulumi.Input[str]] = None,
                  url: Optional[pulumi.Input[str]] = None):
         """
         Input properties used for looking up and filtering ServiceEndpointGitHubEnterprise resources.
-        :param pulumi.Input['ServiceEndpointGitHubEnterpriseAuthPersonalArgs'] auth_personal: An `auth_personal` block as documented below. Allows connecting using a personal access token.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         :param pulumi.Input[str] url: GitHub Enterprise Server Url.
         """
         if auth_personal is not None:
             pulumi.set(__self__, "auth_personal", auth_personal)
         if authorization is not None:
@@ -133,17 +128,14 @@
             pulumi.set(__self__, "service_endpoint_name", service_endpoint_name)
         if url is not None:
             pulumi.set(__self__, "url", url)
 
     @property
     @pulumi.getter(name="authPersonal")
     def auth_personal(self) -> Optional[pulumi.Input['ServiceEndpointGitHubEnterpriseAuthPersonalArgs']]:
-        """
-        An `auth_personal` block as documented below. Allows connecting using a personal access token.
-        """
         return pulumi.get(self, "auth_personal")
 
     @auth_personal.setter
     def auth_personal(self, value: Optional[pulumi.Input['ServiceEndpointGitHubEnterpriseAuthPersonalArgs']]):
         pulumi.set(self, "auth_personal", value)
 
     @property
@@ -246,15 +238,14 @@
 
         ```sh
          $ pulumi import azuredevops:index/serviceEndpointGitHubEnterprise:ServiceEndpointGitHubEnterprise example 00000000-0000-0000-0000-000000000000/00000000-0000-0000-0000-000000000000
         ```
 
         :param str resource_name: The name of the resource.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[pulumi.InputType['ServiceEndpointGitHubEnterpriseAuthPersonalArgs']] auth_personal: An `auth_personal` block as documented below. Allows connecting using a personal access token.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         :param pulumi.Input[str] url: GitHub Enterprise Server Url.
         """
         ...
     @overload
     def __init__(__self__,
@@ -359,15 +350,14 @@
         """
         Get an existing ServiceEndpointGitHubEnterprise resource's state with the given name, id, and optional extra
         properties used to qualify the lookup.
 
         :param str resource_name: The unique name of the resulting resource.
         :param pulumi.Input[str] id: The unique provider ID of the resource to lookup.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[pulumi.InputType['ServiceEndpointGitHubEnterpriseAuthPersonalArgs']] auth_personal: An `auth_personal` block as documented below. Allows connecting using a personal access token.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         :param pulumi.Input[str] url: GitHub Enterprise Server Url.
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
 
         __props__ = _ServiceEndpointGitHubEnterpriseState.__new__(_ServiceEndpointGitHubEnterpriseState)
@@ -379,17 +369,14 @@
         __props__.__dict__["service_endpoint_name"] = service_endpoint_name
         __props__.__dict__["url"] = url
         return ServiceEndpointGitHubEnterprise(resource_name, opts=opts, __props__=__props__)
 
     @property
     @pulumi.getter(name="authPersonal")
     def auth_personal(self) -> pulumi.Output['outputs.ServiceEndpointGitHubEnterpriseAuthPersonal']:
-        """
-        An `auth_personal` block as documented below. Allows connecting using a personal access token.
-        """
         return pulumi.get(self, "auth_personal")
 
     @property
     @pulumi.getter
     def authorization(self) -> pulumi.Output[Mapping[str, str]]:
         return pulumi.get(self, "authorization")
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_kubernetes.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_kubernetes.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_npm.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_npm.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_pipeline.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_pipeline.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_service_fabric.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_service_fabric.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_sonar_cloud.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_sonar_cloud.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_sonar_qube.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_sonar_qube.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/service_endpoint_ssh.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/service_endpoint_ssh.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint/_inputs.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint/_inputs.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint/azure_rm.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint/azure_rm.py`

 * *Files 14% similar despite different names*

```diff
@@ -36,14 +36,16 @@
         :param pulumi.Input[str] azurerm_management_group_id: The Management group ID of the Azure targets.
         :param pulumi.Input[str] azurerm_management_group_name: The Management group Name of the targets.
         :param pulumi.Input[str] azurerm_subscription_id: The Subscription ID of the Azure targets.
         :param pulumi.Input[str] azurerm_subscription_name: The Subscription Name of the targets.
         :param pulumi.Input['AzureRMCredentialsArgs'] credentials: A `credentials` block.
         :param pulumi.Input[str] description: Service connection description.
         :param pulumi.Input[str] environment: The Cloud Environment to use. Defaults to `AzureCloud`. Possible values are `AzureCloud`, `AzureChinaCloud`. Changing this forces a new resource to be created.
+               
+               > **NOTE:** One of either `Subscription` scoped i.e. `azurerm_subscription_id`, `azurerm_subscription_name` or `ManagementGroup` scoped i.e. `azurerm_management_group_id`, `azurerm_management_group_name` values must be specified.
         :param pulumi.Input[str] resource_group: The resource group used for scope of automatic service endpoint.
         """
         pulumi.set(__self__, "azurerm_spn_tenantid", azurerm_spn_tenantid)
         pulumi.set(__self__, "project_id", project_id)
         pulumi.set(__self__, "service_endpoint_name", service_endpoint_name)
         if authorization is not None:
             pulumi.set(__self__, "authorization", authorization)
@@ -182,14 +184,16 @@
         pulumi.set(self, "description", value)
 
     @property
     @pulumi.getter
     def environment(self) -> Optional[pulumi.Input[str]]:
         """
         The Cloud Environment to use. Defaults to `AzureCloud`. Possible values are `AzureCloud`, `AzureChinaCloud`. Changing this forces a new resource to be created.
+
+        > **NOTE:** One of either `Subscription` scoped i.e. `azurerm_subscription_id`, `azurerm_subscription_name` or `ManagementGroup` scoped i.e. `azurerm_management_group_id`, `azurerm_management_group_name` values must be specified.
         """
         return pulumi.get(self, "environment")
 
     @environment.setter
     def environment(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "environment", value)
 
@@ -227,14 +231,16 @@
         :param pulumi.Input[str] azurerm_management_group_name: The Management group Name of the targets.
         :param pulumi.Input[str] azurerm_spn_tenantid: The Tenant ID if the service principal.
         :param pulumi.Input[str] azurerm_subscription_id: The Subscription ID of the Azure targets.
         :param pulumi.Input[str] azurerm_subscription_name: The Subscription Name of the targets.
         :param pulumi.Input['AzureRMCredentialsArgs'] credentials: A `credentials` block.
         :param pulumi.Input[str] description: Service connection description.
         :param pulumi.Input[str] environment: The Cloud Environment to use. Defaults to `AzureCloud`. Possible values are `AzureCloud`, `AzureChinaCloud`. Changing this forces a new resource to be created.
+               
+               > **NOTE:** One of either `Subscription` scoped i.e. `azurerm_subscription_id`, `azurerm_subscription_name` or `ManagementGroup` scoped i.e. `azurerm_management_group_id`, `azurerm_management_group_name` values must be specified.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] resource_group: The resource group used for scope of automatic service endpoint.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint Name.
         """
         if authorization is not None:
             pulumi.set(__self__, "authorization", authorization)
         if azurerm_management_group_id is not None:
@@ -354,14 +360,16 @@
         pulumi.set(self, "description", value)
 
     @property
     @pulumi.getter
     def environment(self) -> Optional[pulumi.Input[str]]:
         """
         The Cloud Environment to use. Defaults to `AzureCloud`. Possible values are `AzureCloud`, `AzureChinaCloud`. Changing this forces a new resource to be created.
+
+        > **NOTE:** One of either `Subscription` scoped i.e. `azurerm_subscription_id`, `azurerm_subscription_name` or `ManagementGroup` scoped i.e. `azurerm_management_group_id`, `azurerm_management_group_name` values must be specified.
         """
         return pulumi.get(self, "environment")
 
     @environment.setter
     def environment(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "environment", value)
 
@@ -516,14 +524,16 @@
         :param pulumi.Input[str] azurerm_management_group_name: The Management group Name of the targets.
         :param pulumi.Input[str] azurerm_spn_tenantid: The Tenant ID if the service principal.
         :param pulumi.Input[str] azurerm_subscription_id: The Subscription ID of the Azure targets.
         :param pulumi.Input[str] azurerm_subscription_name: The Subscription Name of the targets.
         :param pulumi.Input[pulumi.InputType['AzureRMCredentialsArgs']] credentials: A `credentials` block.
         :param pulumi.Input[str] description: Service connection description.
         :param pulumi.Input[str] environment: The Cloud Environment to use. Defaults to `AzureCloud`. Possible values are `AzureCloud`, `AzureChinaCloud`. Changing this forces a new resource to be created.
+               
+               > **NOTE:** One of either `Subscription` scoped i.e. `azurerm_subscription_id`, `azurerm_subscription_name` or `ManagementGroup` scoped i.e. `azurerm_management_group_id`, `azurerm_management_group_name` values must be specified.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] resource_group: The resource group used for scope of automatic service endpoint.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint Name.
         """
         ...
     @overload
     def __init__(__self__,
@@ -703,14 +713,16 @@
         :param pulumi.Input[str] azurerm_management_group_name: The Management group Name of the targets.
         :param pulumi.Input[str] azurerm_spn_tenantid: The Tenant ID if the service principal.
         :param pulumi.Input[str] azurerm_subscription_id: The Subscription ID of the Azure targets.
         :param pulumi.Input[str] azurerm_subscription_name: The Subscription Name of the targets.
         :param pulumi.Input[pulumi.InputType['AzureRMCredentialsArgs']] credentials: A `credentials` block.
         :param pulumi.Input[str] description: Service connection description.
         :param pulumi.Input[str] environment: The Cloud Environment to use. Defaults to `AzureCloud`. Possible values are `AzureCloud`, `AzureChinaCloud`. Changing this forces a new resource to be created.
+               
+               > **NOTE:** One of either `Subscription` scoped i.e. `azurerm_subscription_id`, `azurerm_subscription_name` or `ManagementGroup` scoped i.e. `azurerm_management_group_id`, `azurerm_management_group_name` values must be specified.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] resource_group: The resource group used for scope of automatic service endpoint.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint Name.
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
 
         __props__ = _AzureRMState.__new__(_AzureRMState)
@@ -791,14 +803,16 @@
         return pulumi.get(self, "description")
 
     @property
     @pulumi.getter
     def environment(self) -> pulumi.Output[Optional[str]]:
         """
         The Cloud Environment to use. Defaults to `AzureCloud`. Possible values are `AzureCloud`, `AzureChinaCloud`. Changing this forces a new resource to be created.
+
+        > **NOTE:** One of either `Subscription` scoped i.e. `azurerm_subscription_id`, `azurerm_subscription_name` or `ManagementGroup` scoped i.e. `azurerm_management_group_id`, `azurerm_management_group_name` values must be specified.
         """
         return pulumi.get(self, "environment")
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> pulumi.Output[str]:
         """
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint/bit_bucket.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint/bit_bucket.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint/docker_registry.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint/docker_registry.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint/git_hub.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint/git_hub.py`

 * *Files 6% similar despite different names*

```diff
@@ -22,15 +22,14 @@
                  auth_personal: Optional[pulumi.Input['GitHubAuthPersonalArgs']] = None,
                  authorization: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
                  description: Optional[pulumi.Input[str]] = None):
         """
         The set of arguments for constructing a GitHub resource.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
-        :param pulumi.Input['GitHubAuthOauthArgs'] auth_oauth: An `auth_oauth` block as documented below. Allows connecting using an Oauth token.
         :param pulumi.Input['GitHubAuthPersonalArgs'] auth_personal: An `auth_personal` block as documented below. Allows connecting using a personal access token.
         """
         pulumi.set(__self__, "project_id", project_id)
         pulumi.set(__self__, "service_endpoint_name", service_endpoint_name)
         if auth_oauth is not None:
             pulumi.set(__self__, "auth_oauth", auth_oauth)
         if auth_personal is not None:
@@ -63,17 +62,14 @@
     @service_endpoint_name.setter
     def service_endpoint_name(self, value: pulumi.Input[str]):
         pulumi.set(self, "service_endpoint_name", value)
 
     @property
     @pulumi.getter(name="authOauth")
     def auth_oauth(self) -> Optional[pulumi.Input['GitHubAuthOauthArgs']]:
-        """
-        An `auth_oauth` block as documented below. Allows connecting using an Oauth token.
-        """
         return pulumi.get(self, "auth_oauth")
 
     @auth_oauth.setter
     def auth_oauth(self, value: Optional[pulumi.Input['GitHubAuthOauthArgs']]):
         pulumi.set(self, "auth_oauth", value)
 
     @property
@@ -114,15 +110,14 @@
                  auth_personal: Optional[pulumi.Input['GitHubAuthPersonalArgs']] = None,
                  authorization: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
                  description: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  service_endpoint_name: Optional[pulumi.Input[str]] = None):
         """
         Input properties used for looking up and filtering GitHub resources.
-        :param pulumi.Input['GitHubAuthOauthArgs'] auth_oauth: An `auth_oauth` block as documented below. Allows connecting using an Oauth token.
         :param pulumi.Input['GitHubAuthPersonalArgs'] auth_personal: An `auth_personal` block as documented below. Allows connecting using a personal access token.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         """
         if auth_oauth is not None:
             pulumi.set(__self__, "auth_oauth", auth_oauth)
         if auth_personal is not None:
@@ -135,17 +130,14 @@
             pulumi.set(__self__, "project_id", project_id)
         if service_endpoint_name is not None:
             pulumi.set(__self__, "service_endpoint_name", service_endpoint_name)
 
     @property
     @pulumi.getter(name="authOauth")
     def auth_oauth(self) -> Optional[pulumi.Input['GitHubAuthOauthArgs']]:
-        """
-        An `auth_oauth` block as documented below. Allows connecting using an Oauth token.
-        """
         return pulumi.get(self, "auth_oauth")
 
     @auth_oauth.setter
     def auth_oauth(self, value: Optional[pulumi.Input['GitHubAuthOauthArgs']]):
         pulumi.set(self, "auth_oauth", value)
 
     @property
@@ -283,15 +275,14 @@
 
         ```sh
          $ pulumi import azuredevops:ServiceEndpoint/gitHub:GitHub example 00000000-0000-0000-0000-000000000000/00000000-0000-0000-0000-000000000000
         ```
 
         :param str resource_name: The name of the resource.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[pulumi.InputType['GitHubAuthOauthArgs']] auth_oauth: An `auth_oauth` block as documented below. Allows connecting using an Oauth token.
         :param pulumi.Input[pulumi.InputType['GitHubAuthPersonalArgs']] auth_personal: An `auth_personal` block as documented below. Allows connecting using a personal access token.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         """
         ...
     @overload
     def __init__(__self__,
@@ -423,15 +414,14 @@
         """
         Get an existing GitHub resource's state with the given name, id, and optional extra
         properties used to qualify the lookup.
 
         :param str resource_name: The unique name of the resulting resource.
         :param pulumi.Input[str] id: The unique provider ID of the resource to lookup.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[pulumi.InputType['GitHubAuthOauthArgs']] auth_oauth: An `auth_oauth` block as documented below. Allows connecting using an Oauth token.
         :param pulumi.Input[pulumi.InputType['GitHubAuthPersonalArgs']] auth_personal: An `auth_personal` block as documented below. Allows connecting using a personal access token.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
 
         __props__ = _GitHubState.__new__(_GitHubState)
@@ -443,17 +433,14 @@
         __props__.__dict__["project_id"] = project_id
         __props__.__dict__["service_endpoint_name"] = service_endpoint_name
         return GitHub(resource_name, opts=opts, __props__=__props__)
 
     @property
     @pulumi.getter(name="authOauth")
     def auth_oauth(self) -> pulumi.Output[Optional['outputs.GitHubAuthOauth']]:
-        """
-        An `auth_oauth` block as documented below. Allows connecting using an Oauth token.
-        """
         return pulumi.get(self, "auth_oauth")
 
     @property
     @pulumi.getter(name="authPersonal")
     def auth_personal(self) -> pulumi.Output[Optional['outputs.GitHubAuthPersonal']]:
         """
         An `auth_personal` block as documented below. Allows connecting using a personal access token.
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint/kubernetes.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint/kubernetes.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint/outputs.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint/outputs.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint_argocd.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint_argocd.py`

 * *Files 2% similar despite different names*

```diff
@@ -25,14 +25,16 @@
                  description: Optional[pulumi.Input[str]] = None):
         """
         The set of arguments for constructing a ServiceendpointArgocd resource.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         :param pulumi.Input[str] url: URL of the ArgoCD server to connect with.
         :param pulumi.Input['ServiceendpointArgocdAuthenticationBasicArgs'] authentication_basic: An `authentication_basic` block for the ArgoCD as documented below.
+               
+               > **NOTE:** `authentication_basic` and `authentication_token` conflict with each other, only one is required.
         :param pulumi.Input['ServiceendpointArgocdAuthenticationTokenArgs'] authentication_token: An `authentication_token` block for the ArgoCD as documented below.
         :param pulumi.Input[str] description: The Service Endpoint description.
         """
         pulumi.set(__self__, "project_id", project_id)
         pulumi.set(__self__, "service_endpoint_name", service_endpoint_name)
         pulumi.set(__self__, "url", url)
         if authentication_basic is not None:
@@ -81,14 +83,16 @@
         pulumi.set(self, "url", value)
 
     @property
     @pulumi.getter(name="authenticationBasic")
     def authentication_basic(self) -> Optional[pulumi.Input['ServiceendpointArgocdAuthenticationBasicArgs']]:
         """
         An `authentication_basic` block for the ArgoCD as documented below.
+
+        > **NOTE:** `authentication_basic` and `authentication_token` conflict with each other, only one is required.
         """
         return pulumi.get(self, "authentication_basic")
 
     @authentication_basic.setter
     def authentication_basic(self, value: Optional[pulumi.Input['ServiceendpointArgocdAuthenticationBasicArgs']]):
         pulumi.set(self, "authentication_basic", value)
 
@@ -135,14 +139,16 @@
                  description: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  service_endpoint_name: Optional[pulumi.Input[str]] = None,
                  url: Optional[pulumi.Input[str]] = None):
         """
         Input properties used for looking up and filtering ServiceendpointArgocd resources.
         :param pulumi.Input['ServiceendpointArgocdAuthenticationBasicArgs'] authentication_basic: An `authentication_basic` block for the ArgoCD as documented below.
+               
+               > **NOTE:** `authentication_basic` and `authentication_token` conflict with each other, only one is required.
         :param pulumi.Input['ServiceendpointArgocdAuthenticationTokenArgs'] authentication_token: An `authentication_token` block for the ArgoCD as documented below.
         :param pulumi.Input[str] description: The Service Endpoint description.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         :param pulumi.Input[str] url: URL of the ArgoCD server to connect with.
         """
         if authentication_basic is not None:
@@ -161,14 +167,16 @@
             pulumi.set(__self__, "url", url)
 
     @property
     @pulumi.getter(name="authenticationBasic")
     def authentication_basic(self) -> Optional[pulumi.Input['ServiceendpointArgocdAuthenticationBasicArgs']]:
         """
         An `authentication_basic` block for the ArgoCD as documented below.
+
+        > **NOTE:** `authentication_basic` and `authentication_token` conflict with each other, only one is required.
         """
         return pulumi.get(self, "authentication_basic")
 
     @authentication_basic.setter
     def authentication_basic(self, value: Optional[pulumi.Input['ServiceendpointArgocdAuthenticationBasicArgs']]):
         pulumi.set(self, "authentication_basic", value)
 
@@ -311,14 +319,16 @@
         ```sh
          $ pulumi import azuredevops:index/serviceendpointArgocd:ServiceendpointArgocd example 00000000-0000-0000-0000-000000000000/00000000-0000-0000-0000-000000000000
         ```
 
         :param str resource_name: The name of the resource.
         :param pulumi.ResourceOptions opts: Options for the resource.
         :param pulumi.Input[pulumi.InputType['ServiceendpointArgocdAuthenticationBasicArgs']] authentication_basic: An `authentication_basic` block for the ArgoCD as documented below.
+               
+               > **NOTE:** `authentication_basic` and `authentication_token` conflict with each other, only one is required.
         :param pulumi.Input[pulumi.InputType['ServiceendpointArgocdAuthenticationTokenArgs']] authentication_token: An `authentication_token` block for the ArgoCD as documented below.
         :param pulumi.Input[str] description: The Service Endpoint description.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         :param pulumi.Input[str] url: URL of the ArgoCD server to connect with.
         """
         ...
@@ -449,14 +459,16 @@
         Get an existing ServiceendpointArgocd resource's state with the given name, id, and optional extra
         properties used to qualify the lookup.
 
         :param str resource_name: The unique name of the resulting resource.
         :param pulumi.Input[str] id: The unique provider ID of the resource to lookup.
         :param pulumi.ResourceOptions opts: Options for the resource.
         :param pulumi.Input[pulumi.InputType['ServiceendpointArgocdAuthenticationBasicArgs']] authentication_basic: An `authentication_basic` block for the ArgoCD as documented below.
+               
+               > **NOTE:** `authentication_basic` and `authentication_token` conflict with each other, only one is required.
         :param pulumi.Input[pulumi.InputType['ServiceendpointArgocdAuthenticationTokenArgs']] authentication_token: An `authentication_token` block for the ArgoCD as documented below.
         :param pulumi.Input[str] description: The Service Endpoint description.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         :param pulumi.Input[str] url: URL of the ArgoCD server to connect with.
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
@@ -473,14 +485,16 @@
         return ServiceendpointArgocd(resource_name, opts=opts, __props__=__props__)
 
     @property
     @pulumi.getter(name="authenticationBasic")
     def authentication_basic(self) -> pulumi.Output[Optional['outputs.ServiceendpointArgocdAuthenticationBasic']]:
         """
         An `authentication_basic` block for the ArgoCD as documented below.
+
+        > **NOTE:** `authentication_basic` and `authentication_token` conflict with each other, only one is required.
         """
         return pulumi.get(self, "authentication_basic")
 
     @property
     @pulumi.getter(name="authenticationToken")
     def authentication_token(self) -> pulumi.Output[Optional['outputs.ServiceendpointArgocdAuthenticationToken']]:
         """
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint_externaltfs.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint_octopusdeploy.py`

 * *Files 16% similar despite different names*

```diff
@@ -4,67 +4,57 @@
 
 import copy
 import warnings
 import pulumi
 import pulumi.runtime
 from typing import Any, Mapping, Optional, Sequence, Union, overload
 from . import _utilities
-from . import outputs
-from ._inputs import *
 
-__all__ = ['ServiceendpointExternaltfsArgs', 'ServiceendpointExternaltfs']
+__all__ = ['ServiceendpointOctopusdeployArgs', 'ServiceendpointOctopusdeploy']
 
 @pulumi.input_type
-class ServiceendpointExternaltfsArgs:
+class ServiceendpointOctopusdeployArgs:
     def __init__(__self__, *,
-                 auth_personal: pulumi.Input['ServiceendpointExternaltfsAuthPersonalArgs'],
-                 connection_url: pulumi.Input[str],
+                 api_key: pulumi.Input[str],
                  project_id: pulumi.Input[str],
                  service_endpoint_name: pulumi.Input[str],
+                 url: pulumi.Input[str],
                  authorization: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
-                 description: Optional[pulumi.Input[str]] = None):
+                 description: Optional[pulumi.Input[str]] = None,
+                 ignore_ssl_error: Optional[pulumi.Input[bool]] = None):
         """
-        The set of arguments for constructing a ServiceendpointExternaltfs resource.
-        :param pulumi.Input['ServiceendpointExternaltfsAuthPersonalArgs'] auth_personal: An `auth_personal` block as documented below. Allows connecting using a personal access token.
-        :param pulumi.Input[str] connection_url: URL of the Azure DevOps organization or the TFS Project Collection to connect to.
+        The set of arguments for constructing a ServiceendpointOctopusdeploy resource.
+        :param pulumi.Input[str] api_key: API key to connect to Octopus Deploy.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
+        :param pulumi.Input[str] url: Octopus Server url.
+        :param pulumi.Input[bool] ignore_ssl_error: Whether to ignore SSL errors when connecting to the Octopus server from the agent. Default to `false`.
         """
-        pulumi.set(__self__, "auth_personal", auth_personal)
-        pulumi.set(__self__, "connection_url", connection_url)
+        pulumi.set(__self__, "api_key", api_key)
         pulumi.set(__self__, "project_id", project_id)
         pulumi.set(__self__, "service_endpoint_name", service_endpoint_name)
+        pulumi.set(__self__, "url", url)
         if authorization is not None:
             pulumi.set(__self__, "authorization", authorization)
         if description is not None:
             pulumi.set(__self__, "description", description)
+        if ignore_ssl_error is not None:
+            pulumi.set(__self__, "ignore_ssl_error", ignore_ssl_error)
 
     @property
-    @pulumi.getter(name="authPersonal")
-    def auth_personal(self) -> pulumi.Input['ServiceendpointExternaltfsAuthPersonalArgs']:
+    @pulumi.getter(name="apiKey")
+    def api_key(self) -> pulumi.Input[str]:
         """
-        An `auth_personal` block as documented below. Allows connecting using a personal access token.
+        API key to connect to Octopus Deploy.
         """
-        return pulumi.get(self, "auth_personal")
+        return pulumi.get(self, "api_key")
 
-    @auth_personal.setter
-    def auth_personal(self, value: pulumi.Input['ServiceendpointExternaltfsAuthPersonalArgs']):
-        pulumi.set(self, "auth_personal", value)
-
-    @property
-    @pulumi.getter(name="connectionUrl")
-    def connection_url(self) -> pulumi.Input[str]:
-        """
-        URL of the Azure DevOps organization or the TFS Project Collection to connect to.
-        """
-        return pulumi.get(self, "connection_url")
-
-    @connection_url.setter
-    def connection_url(self, value: pulumi.Input[str]):
-        pulumi.set(self, "connection_url", value)
+    @api_key.setter
+    def api_key(self, value: pulumi.Input[str]):
+        pulumi.set(self, "api_key", value)
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> pulumi.Input[str]:
         """
         The ID of the project.
         """
@@ -84,14 +74,26 @@
 
     @service_endpoint_name.setter
     def service_endpoint_name(self, value: pulumi.Input[str]):
         pulumi.set(self, "service_endpoint_name", value)
 
     @property
     @pulumi.getter
+    def url(self) -> pulumi.Input[str]:
+        """
+        Octopus Server url.
+        """
+        return pulumi.get(self, "url")
+
+    @url.setter
+    def url(self, value: pulumi.Input[str]):
+        pulumi.set(self, "url", value)
+
+    @property
+    @pulumi.getter
     def authorization(self) -> Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]:
         return pulumi.get(self, "authorization")
 
     @authorization.setter
     def authorization(self, value: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]):
         pulumi.set(self, "authorization", value)
 
@@ -100,87 +102,103 @@
     def description(self) -> Optional[pulumi.Input[str]]:
         return pulumi.get(self, "description")
 
     @description.setter
     def description(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "description", value)
 
+    @property
+    @pulumi.getter(name="ignoreSslError")
+    def ignore_ssl_error(self) -> Optional[pulumi.Input[bool]]:
+        """
+        Whether to ignore SSL errors when connecting to the Octopus server from the agent. Default to `false`.
+        """
+        return pulumi.get(self, "ignore_ssl_error")
+
+    @ignore_ssl_error.setter
+    def ignore_ssl_error(self, value: Optional[pulumi.Input[bool]]):
+        pulumi.set(self, "ignore_ssl_error", value)
+
 
 @pulumi.input_type
-class _ServiceendpointExternaltfsState:
+class _ServiceendpointOctopusdeployState:
     def __init__(__self__, *,
-                 auth_personal: Optional[pulumi.Input['ServiceendpointExternaltfsAuthPersonalArgs']] = None,
+                 api_key: Optional[pulumi.Input[str]] = None,
                  authorization: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
-                 connection_url: Optional[pulumi.Input[str]] = None,
                  description: Optional[pulumi.Input[str]] = None,
+                 ignore_ssl_error: Optional[pulumi.Input[bool]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
-                 service_endpoint_name: Optional[pulumi.Input[str]] = None):
+                 service_endpoint_name: Optional[pulumi.Input[str]] = None,
+                 url: Optional[pulumi.Input[str]] = None):
         """
-        Input properties used for looking up and filtering ServiceendpointExternaltfs resources.
-        :param pulumi.Input['ServiceendpointExternaltfsAuthPersonalArgs'] auth_personal: An `auth_personal` block as documented below. Allows connecting using a personal access token.
-        :param pulumi.Input[str] connection_url: URL of the Azure DevOps organization or the TFS Project Collection to connect to.
+        Input properties used for looking up and filtering ServiceendpointOctopusdeploy resources.
+        :param pulumi.Input[str] api_key: API key to connect to Octopus Deploy.
+        :param pulumi.Input[bool] ignore_ssl_error: Whether to ignore SSL errors when connecting to the Octopus server from the agent. Default to `false`.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
+        :param pulumi.Input[str] url: Octopus Server url.
         """
-        if auth_personal is not None:
-            pulumi.set(__self__, "auth_personal", auth_personal)
+        if api_key is not None:
+            pulumi.set(__self__, "api_key", api_key)
         if authorization is not None:
             pulumi.set(__self__, "authorization", authorization)
-        if connection_url is not None:
-            pulumi.set(__self__, "connection_url", connection_url)
         if description is not None:
             pulumi.set(__self__, "description", description)
+        if ignore_ssl_error is not None:
+            pulumi.set(__self__, "ignore_ssl_error", ignore_ssl_error)
         if project_id is not None:
             pulumi.set(__self__, "project_id", project_id)
         if service_endpoint_name is not None:
             pulumi.set(__self__, "service_endpoint_name", service_endpoint_name)
+        if url is not None:
+            pulumi.set(__self__, "url", url)
 
     @property
-    @pulumi.getter(name="authPersonal")
-    def auth_personal(self) -> Optional[pulumi.Input['ServiceendpointExternaltfsAuthPersonalArgs']]:
+    @pulumi.getter(name="apiKey")
+    def api_key(self) -> Optional[pulumi.Input[str]]:
         """
-        An `auth_personal` block as documented below. Allows connecting using a personal access token.
+        API key to connect to Octopus Deploy.
         """
-        return pulumi.get(self, "auth_personal")
+        return pulumi.get(self, "api_key")
 
-    @auth_personal.setter
-    def auth_personal(self, value: Optional[pulumi.Input['ServiceendpointExternaltfsAuthPersonalArgs']]):
-        pulumi.set(self, "auth_personal", value)
+    @api_key.setter
+    def api_key(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "api_key", value)
 
     @property
     @pulumi.getter
     def authorization(self) -> Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]:
         return pulumi.get(self, "authorization")
 
     @authorization.setter
     def authorization(self, value: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]):
         pulumi.set(self, "authorization", value)
 
     @property
-    @pulumi.getter(name="connectionUrl")
-    def connection_url(self) -> Optional[pulumi.Input[str]]:
-        """
-        URL of the Azure DevOps organization or the TFS Project Collection to connect to.
-        """
-        return pulumi.get(self, "connection_url")
-
-    @connection_url.setter
-    def connection_url(self, value: Optional[pulumi.Input[str]]):
-        pulumi.set(self, "connection_url", value)
-
-    @property
     @pulumi.getter
     def description(self) -> Optional[pulumi.Input[str]]:
         return pulumi.get(self, "description")
 
     @description.setter
     def description(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "description", value)
 
     @property
+    @pulumi.getter(name="ignoreSslError")
+    def ignore_ssl_error(self) -> Optional[pulumi.Input[bool]]:
+        """
+        Whether to ignore SSL errors when connecting to the Octopus server from the agent. Default to `false`.
+        """
+        return pulumi.get(self, "ignore_ssl_error")
+
+    @ignore_ssl_error.setter
+    def ignore_ssl_error(self, value: Optional[pulumi.Input[bool]]):
+        pulumi.set(self, "ignore_ssl_error", value)
+
+    @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> Optional[pulumi.Input[str]]:
         """
         The ID of the project.
         """
         return pulumi.get(self, "project_id")
 
@@ -196,181 +214,236 @@
         """
         return pulumi.get(self, "service_endpoint_name")
 
     @service_endpoint_name.setter
     def service_endpoint_name(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "service_endpoint_name", value)
 
+    @property
+    @pulumi.getter
+    def url(self) -> Optional[pulumi.Input[str]]:
+        """
+        Octopus Server url.
+        """
+        return pulumi.get(self, "url")
+
+    @url.setter
+    def url(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "url", value)
 
-class ServiceendpointExternaltfs(pulumi.CustomResource):
+
+class ServiceendpointOctopusdeploy(pulumi.CustomResource):
     @overload
     def __init__(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
-                 auth_personal: Optional[pulumi.Input[pulumi.InputType['ServiceendpointExternaltfsAuthPersonalArgs']]] = None,
+                 api_key: Optional[pulumi.Input[str]] = None,
                  authorization: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
-                 connection_url: Optional[pulumi.Input[str]] = None,
                  description: Optional[pulumi.Input[str]] = None,
+                 ignore_ssl_error: Optional[pulumi.Input[bool]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  service_endpoint_name: Optional[pulumi.Input[str]] = None,
+                 url: Optional[pulumi.Input[str]] = None,
                  __props__=None):
         """
-        Manages an Azure Repos/Team Foundation Server service endpoint within Azure DevOps.
+        Manages an Octopus Deploy service endpoint within Azure DevOps. Using this service endpoint requires you to install [Octopus Deploy](https://marketplace.visualstudio.com/items?itemName=octopusdeploy.octopus-deploy-build-release-tasks).
+
+        ## Example Usage
 
+        ```python
+        import pulumi
+        import pulumi_azuredevops as azuredevops
+
+        example_project = azuredevops.Project("exampleProject",
+            visibility="private",
+            version_control="Git",
+            work_item_template="Agile",
+            description="Managed by Terraform")
+        example_serviceendpoint_octopusdeploy = azuredevops.ServiceendpointOctopusdeploy("exampleServiceendpointOctopusdeploy",
+            project_id=example_project.id,
+            url="https://octopus.com",
+            api_key="000000000000000000000000000000000000",
+            service_endpoint_name="Example Octopus Deploy",
+            description="Managed by Terraform")
+        ```
         ## Relevant Links
 
-        - [Azure DevOps Service REST API 6.0 - Service Endpoints](https://docs.microsoft.com/en-us/rest/api/azure/devops/serviceendpoint/endpoints?view=azure-devops-rest-6.0)
+        - [Azure DevOps Service REST API 6.0 - Agent Pools](https://docs.microsoft.com/en-us/rest/api/azure/devops/serviceendpoint/endpoints?view=azure-devops-rest-6.0)
 
         ## Import
 
-        Azure DevOps Service Endpoint External TFS can be imported using **projectID/serviceEndpointID** or **projectName/serviceEndpointID**
+        Azure DevOps Service Endpoint Octopus Deploy can be imported using **projectID/serviceEndpointID** or **projectName/serviceEndpointID**
 
         ```sh
-         $ pulumi import azuredevops:index/serviceendpointExternaltfs:ServiceendpointExternaltfs example 00000000-0000-0000-0000-000000000000/00000000-0000-0000-0000-000000000000
+         $ pulumi import azuredevops:index/serviceendpointOctopusdeploy:ServiceendpointOctopusdeploy example 00000000-0000-0000-0000-000000000000/00000000-0000-0000-0000-000000000000
         ```
 
         :param str resource_name: The name of the resource.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[pulumi.InputType['ServiceendpointExternaltfsAuthPersonalArgs']] auth_personal: An `auth_personal` block as documented below. Allows connecting using a personal access token.
-        :param pulumi.Input[str] connection_url: URL of the Azure DevOps organization or the TFS Project Collection to connect to.
+        :param pulumi.Input[str] api_key: API key to connect to Octopus Deploy.
+        :param pulumi.Input[bool] ignore_ssl_error: Whether to ignore SSL errors when connecting to the Octopus server from the agent. Default to `false`.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
+        :param pulumi.Input[str] url: Octopus Server url.
         """
         ...
     @overload
     def __init__(__self__,
                  resource_name: str,
-                 args: ServiceendpointExternaltfsArgs,
+                 args: ServiceendpointOctopusdeployArgs,
                  opts: Optional[pulumi.ResourceOptions] = None):
         """
-        Manages an Azure Repos/Team Foundation Server service endpoint within Azure DevOps.
+        Manages an Octopus Deploy service endpoint within Azure DevOps. Using this service endpoint requires you to install [Octopus Deploy](https://marketplace.visualstudio.com/items?itemName=octopusdeploy.octopus-deploy-build-release-tasks).
 
+        ## Example Usage
+
+        ```python
+        import pulumi
+        import pulumi_azuredevops as azuredevops
+
+        example_project = azuredevops.Project("exampleProject",
+            visibility="private",
+            version_control="Git",
+            work_item_template="Agile",
+            description="Managed by Terraform")
+        example_serviceendpoint_octopusdeploy = azuredevops.ServiceendpointOctopusdeploy("exampleServiceendpointOctopusdeploy",
+            project_id=example_project.id,
+            url="https://octopus.com",
+            api_key="000000000000000000000000000000000000",
+            service_endpoint_name="Example Octopus Deploy",
+            description="Managed by Terraform")
+        ```
         ## Relevant Links
 
-        - [Azure DevOps Service REST API 6.0 - Service Endpoints](https://docs.microsoft.com/en-us/rest/api/azure/devops/serviceendpoint/endpoints?view=azure-devops-rest-6.0)
+        - [Azure DevOps Service REST API 6.0 - Agent Pools](https://docs.microsoft.com/en-us/rest/api/azure/devops/serviceendpoint/endpoints?view=azure-devops-rest-6.0)
 
         ## Import
 
-        Azure DevOps Service Endpoint External TFS can be imported using **projectID/serviceEndpointID** or **projectName/serviceEndpointID**
+        Azure DevOps Service Endpoint Octopus Deploy can be imported using **projectID/serviceEndpointID** or **projectName/serviceEndpointID**
 
         ```sh
-         $ pulumi import azuredevops:index/serviceendpointExternaltfs:ServiceendpointExternaltfs example 00000000-0000-0000-0000-000000000000/00000000-0000-0000-0000-000000000000
+         $ pulumi import azuredevops:index/serviceendpointOctopusdeploy:ServiceendpointOctopusdeploy example 00000000-0000-0000-0000-000000000000/00000000-0000-0000-0000-000000000000
         ```
 
         :param str resource_name: The name of the resource.
-        :param ServiceendpointExternaltfsArgs args: The arguments to use to populate this resource's properties.
+        :param ServiceendpointOctopusdeployArgs args: The arguments to use to populate this resource's properties.
         :param pulumi.ResourceOptions opts: Options for the resource.
         """
         ...
     def __init__(__self__, resource_name: str, *args, **kwargs):
-        resource_args, opts = _utilities.get_resource_args_opts(ServiceendpointExternaltfsArgs, pulumi.ResourceOptions, *args, **kwargs)
+        resource_args, opts = _utilities.get_resource_args_opts(ServiceendpointOctopusdeployArgs, pulumi.ResourceOptions, *args, **kwargs)
         if resource_args is not None:
             __self__._internal_init(resource_name, opts, **resource_args.__dict__)
         else:
             __self__._internal_init(resource_name, *args, **kwargs)
 
     def _internal_init(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
-                 auth_personal: Optional[pulumi.Input[pulumi.InputType['ServiceendpointExternaltfsAuthPersonalArgs']]] = None,
+                 api_key: Optional[pulumi.Input[str]] = None,
                  authorization: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
-                 connection_url: Optional[pulumi.Input[str]] = None,
                  description: Optional[pulumi.Input[str]] = None,
+                 ignore_ssl_error: Optional[pulumi.Input[bool]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  service_endpoint_name: Optional[pulumi.Input[str]] = None,
+                 url: Optional[pulumi.Input[str]] = None,
                  __props__=None):
         opts = pulumi.ResourceOptions.merge(_utilities.get_resource_opts_defaults(), opts)
         if not isinstance(opts, pulumi.ResourceOptions):
             raise TypeError('Expected resource options to be a ResourceOptions instance')
         if opts.id is None:
             if __props__ is not None:
                 raise TypeError('__props__ is only valid when passed in combination with a valid opts.id to get an existing resource')
-            __props__ = ServiceendpointExternaltfsArgs.__new__(ServiceendpointExternaltfsArgs)
+            __props__ = ServiceendpointOctopusdeployArgs.__new__(ServiceendpointOctopusdeployArgs)
 
-            if auth_personal is None and not opts.urn:
-                raise TypeError("Missing required property 'auth_personal'")
-            __props__.__dict__["auth_personal"] = auth_personal
+            if api_key is None and not opts.urn:
+                raise TypeError("Missing required property 'api_key'")
+            __props__.__dict__["api_key"] = api_key
             __props__.__dict__["authorization"] = authorization
-            if connection_url is None and not opts.urn:
-                raise TypeError("Missing required property 'connection_url'")
-            __props__.__dict__["connection_url"] = connection_url
             __props__.__dict__["description"] = description
+            __props__.__dict__["ignore_ssl_error"] = ignore_ssl_error
             if project_id is None and not opts.urn:
                 raise TypeError("Missing required property 'project_id'")
             __props__.__dict__["project_id"] = project_id
             if service_endpoint_name is None and not opts.urn:
                 raise TypeError("Missing required property 'service_endpoint_name'")
             __props__.__dict__["service_endpoint_name"] = service_endpoint_name
-        super(ServiceendpointExternaltfs, __self__).__init__(
-            'azuredevops:index/serviceendpointExternaltfs:ServiceendpointExternaltfs',
+            if url is None and not opts.urn:
+                raise TypeError("Missing required property 'url'")
+            __props__.__dict__["url"] = url
+        super(ServiceendpointOctopusdeploy, __self__).__init__(
+            'azuredevops:index/serviceendpointOctopusdeploy:ServiceendpointOctopusdeploy',
             resource_name,
             __props__,
             opts)
 
     @staticmethod
     def get(resource_name: str,
             id: pulumi.Input[str],
             opts: Optional[pulumi.ResourceOptions] = None,
-            auth_personal: Optional[pulumi.Input[pulumi.InputType['ServiceendpointExternaltfsAuthPersonalArgs']]] = None,
+            api_key: Optional[pulumi.Input[str]] = None,
             authorization: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
-            connection_url: Optional[pulumi.Input[str]] = None,
             description: Optional[pulumi.Input[str]] = None,
+            ignore_ssl_error: Optional[pulumi.Input[bool]] = None,
             project_id: Optional[pulumi.Input[str]] = None,
-            service_endpoint_name: Optional[pulumi.Input[str]] = None) -> 'ServiceendpointExternaltfs':
+            service_endpoint_name: Optional[pulumi.Input[str]] = None,
+            url: Optional[pulumi.Input[str]] = None) -> 'ServiceendpointOctopusdeploy':
         """
-        Get an existing ServiceendpointExternaltfs resource's state with the given name, id, and optional extra
+        Get an existing ServiceendpointOctopusdeploy resource's state with the given name, id, and optional extra
         properties used to qualify the lookup.
 
         :param str resource_name: The unique name of the resulting resource.
         :param pulumi.Input[str] id: The unique provider ID of the resource to lookup.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[pulumi.InputType['ServiceendpointExternaltfsAuthPersonalArgs']] auth_personal: An `auth_personal` block as documented below. Allows connecting using a personal access token.
-        :param pulumi.Input[str] connection_url: URL of the Azure DevOps organization or the TFS Project Collection to connect to.
+        :param pulumi.Input[str] api_key: API key to connect to Octopus Deploy.
+        :param pulumi.Input[bool] ignore_ssl_error: Whether to ignore SSL errors when connecting to the Octopus server from the agent. Default to `false`.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
+        :param pulumi.Input[str] url: Octopus Server url.
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
 
-        __props__ = _ServiceendpointExternaltfsState.__new__(_ServiceendpointExternaltfsState)
+        __props__ = _ServiceendpointOctopusdeployState.__new__(_ServiceendpointOctopusdeployState)
 
-        __props__.__dict__["auth_personal"] = auth_personal
+        __props__.__dict__["api_key"] = api_key
         __props__.__dict__["authorization"] = authorization
-        __props__.__dict__["connection_url"] = connection_url
         __props__.__dict__["description"] = description
+        __props__.__dict__["ignore_ssl_error"] = ignore_ssl_error
         __props__.__dict__["project_id"] = project_id
         __props__.__dict__["service_endpoint_name"] = service_endpoint_name
-        return ServiceendpointExternaltfs(resource_name, opts=opts, __props__=__props__)
+        __props__.__dict__["url"] = url
+        return ServiceendpointOctopusdeploy(resource_name, opts=opts, __props__=__props__)
 
     @property
-    @pulumi.getter(name="authPersonal")
-    def auth_personal(self) -> pulumi.Output['outputs.ServiceendpointExternaltfsAuthPersonal']:
+    @pulumi.getter(name="apiKey")
+    def api_key(self) -> pulumi.Output[str]:
         """
-        An `auth_personal` block as documented below. Allows connecting using a personal access token.
+        API key to connect to Octopus Deploy.
         """
-        return pulumi.get(self, "auth_personal")
+        return pulumi.get(self, "api_key")
 
     @property
     @pulumi.getter
     def authorization(self) -> pulumi.Output[Mapping[str, str]]:
         return pulumi.get(self, "authorization")
 
     @property
-    @pulumi.getter(name="connectionUrl")
-    def connection_url(self) -> pulumi.Output[str]:
-        """
-        URL of the Azure DevOps organization or the TFS Project Collection to connect to.
-        """
-        return pulumi.get(self, "connection_url")
-
-    @property
     @pulumi.getter
     def description(self) -> pulumi.Output[Optional[str]]:
         return pulumi.get(self, "description")
 
     @property
+    @pulumi.getter(name="ignoreSslError")
+    def ignore_ssl_error(self) -> pulumi.Output[Optional[bool]]:
+        """
+        Whether to ignore SSL errors when connecting to the Octopus server from the agent. Default to `false`.
+        """
+        return pulumi.get(self, "ignore_ssl_error")
+
+    @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> pulumi.Output[str]:
         """
         The ID of the project.
         """
         return pulumi.get(self, "project_id")
 
@@ -378,7 +451,15 @@
     @pulumi.getter(name="serviceEndpointName")
     def service_endpoint_name(self) -> pulumi.Output[str]:
         """
         The Service Endpoint name.
         """
         return pulumi.get(self, "service_endpoint_name")
 
+    @property
+    @pulumi.getter
+    def url(self) -> pulumi.Output[str]:
+        """
+        Octopus Server url.
+        """
+        return pulumi.get(self, "url")
+
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint_incomingwebhook.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint_incomingwebhook.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint_jfrog_artifactory_v2.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint_jfrog_artifactory_v2.py`

 * *Files 2% similar despite different names*

```diff
@@ -24,14 +24,16 @@
                  authorization: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
                  description: Optional[pulumi.Input[str]] = None):
         """
         The set of arguments for constructing a ServiceendpointJfrogArtifactoryV2 resource.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         :param pulumi.Input[str] url: URL of the Artifactory server to connect with.
+               
+               > **NOTE:** URL should not end in a slash character.
         :param pulumi.Input['ServiceendpointJfrogArtifactoryV2AuthenticationBasicArgs'] authentication_basic: A `authentication_basic` block as documented below.
         :param pulumi.Input['ServiceendpointJfrogArtifactoryV2AuthenticationTokenArgs'] authentication_token: A `authentication_token` block as documented below.
         :param pulumi.Input[str] description: The Service Endpoint description.
         """
         pulumi.set(__self__, "project_id", project_id)
         pulumi.set(__self__, "service_endpoint_name", service_endpoint_name)
         pulumi.set(__self__, "url", url)
@@ -69,14 +71,16 @@
         pulumi.set(self, "service_endpoint_name", value)
 
     @property
     @pulumi.getter
     def url(self) -> pulumi.Input[str]:
         """
         URL of the Artifactory server to connect with.
+
+        > **NOTE:** URL should not end in a slash character.
         """
         return pulumi.get(self, "url")
 
     @url.setter
     def url(self, value: pulumi.Input[str]):
         pulumi.set(self, "url", value)
 
@@ -140,14 +144,16 @@
         Input properties used for looking up and filtering ServiceendpointJfrogArtifactoryV2 resources.
         :param pulumi.Input['ServiceendpointJfrogArtifactoryV2AuthenticationBasicArgs'] authentication_basic: A `authentication_basic` block as documented below.
         :param pulumi.Input['ServiceendpointJfrogArtifactoryV2AuthenticationTokenArgs'] authentication_token: A `authentication_token` block as documented below.
         :param pulumi.Input[str] description: The Service Endpoint description.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         :param pulumi.Input[str] url: URL of the Artifactory server to connect with.
+               
+               > **NOTE:** URL should not end in a slash character.
         """
         if authentication_basic is not None:
             pulumi.set(__self__, "authentication_basic", authentication_basic)
         if authentication_token is not None:
             pulumi.set(__self__, "authentication_token", authentication_token)
         if authorization is not None:
             pulumi.set(__self__, "authorization", authorization)
@@ -230,14 +236,16 @@
         pulumi.set(self, "service_endpoint_name", value)
 
     @property
     @pulumi.getter
     def url(self) -> Optional[pulumi.Input[str]]:
         """
         URL of the Artifactory server to connect with.
+
+        > **NOTE:** URL should not end in a slash character.
         """
         return pulumi.get(self, "url")
 
     @url.setter
     def url(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "url", value)
 
@@ -318,14 +326,16 @@
         :param pulumi.ResourceOptions opts: Options for the resource.
         :param pulumi.Input[pulumi.InputType['ServiceendpointJfrogArtifactoryV2AuthenticationBasicArgs']] authentication_basic: A `authentication_basic` block as documented below.
         :param pulumi.Input[pulumi.InputType['ServiceendpointJfrogArtifactoryV2AuthenticationTokenArgs']] authentication_token: A `authentication_token` block as documented below.
         :param pulumi.Input[str] description: The Service Endpoint description.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         :param pulumi.Input[str] url: URL of the Artifactory server to connect with.
+               
+               > **NOTE:** URL should not end in a slash character.
         """
         ...
     @overload
     def __init__(__self__,
                  resource_name: str,
                  args: ServiceendpointJfrogArtifactoryV2Args,
                  opts: Optional[pulumi.ResourceOptions] = None):
@@ -458,14 +468,16 @@
         :param pulumi.ResourceOptions opts: Options for the resource.
         :param pulumi.Input[pulumi.InputType['ServiceendpointJfrogArtifactoryV2AuthenticationBasicArgs']] authentication_basic: A `authentication_basic` block as documented below.
         :param pulumi.Input[pulumi.InputType['ServiceendpointJfrogArtifactoryV2AuthenticationTokenArgs']] authentication_token: A `authentication_token` block as documented below.
         :param pulumi.Input[str] description: The Service Endpoint description.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         :param pulumi.Input[str] url: URL of the Artifactory server to connect with.
+               
+               > **NOTE:** URL should not end in a slash character.
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
 
         __props__ = _ServiceendpointJfrogArtifactoryV2State.__new__(_ServiceendpointJfrogArtifactoryV2State)
 
         __props__.__dict__["authentication_basic"] = authentication_basic
         __props__.__dict__["authentication_token"] = authentication_token
@@ -522,10 +534,12 @@
         return pulumi.get(self, "service_endpoint_name")
 
     @property
     @pulumi.getter
     def url(self) -> pulumi.Output[str]:
         """
         URL of the Artifactory server to connect with.
+
+        > **NOTE:** URL should not end in a slash character.
         """
         return pulumi.get(self, "url")
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint_jfrog_distribution_v2.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint_jfrog_distribution_v2.py`

 * *Files 2% similar despite different names*

```diff
@@ -24,14 +24,16 @@
                  authorization: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
                  description: Optional[pulumi.Input[str]] = None):
         """
         The set of arguments for constructing a ServiceendpointJfrogDistributionV2 resource.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         :param pulumi.Input[str] url: URL of the Artifactory server to connect with.
+               
+               > **NOTE:** URL should not end in a slash character.
         :param pulumi.Input['ServiceendpointJfrogDistributionV2AuthenticationBasicArgs'] authentication_basic: A `authentication_basic` block as documented below.
         :param pulumi.Input['ServiceendpointJfrogDistributionV2AuthenticationTokenArgs'] authentication_token: A `authentication_token` block as documented below.
         :param pulumi.Input[str] description: The Service Endpoint description.
         """
         pulumi.set(__self__, "project_id", project_id)
         pulumi.set(__self__, "service_endpoint_name", service_endpoint_name)
         pulumi.set(__self__, "url", url)
@@ -69,14 +71,16 @@
         pulumi.set(self, "service_endpoint_name", value)
 
     @property
     @pulumi.getter
     def url(self) -> pulumi.Input[str]:
         """
         URL of the Artifactory server to connect with.
+
+        > **NOTE:** URL should not end in a slash character.
         """
         return pulumi.get(self, "url")
 
     @url.setter
     def url(self, value: pulumi.Input[str]):
         pulumi.set(self, "url", value)
 
@@ -140,14 +144,16 @@
         Input properties used for looking up and filtering ServiceendpointJfrogDistributionV2 resources.
         :param pulumi.Input['ServiceendpointJfrogDistributionV2AuthenticationBasicArgs'] authentication_basic: A `authentication_basic` block as documented below.
         :param pulumi.Input['ServiceendpointJfrogDistributionV2AuthenticationTokenArgs'] authentication_token: A `authentication_token` block as documented below.
         :param pulumi.Input[str] description: The Service Endpoint description.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         :param pulumi.Input[str] url: URL of the Artifactory server to connect with.
+               
+               > **NOTE:** URL should not end in a slash character.
         """
         if authentication_basic is not None:
             pulumi.set(__self__, "authentication_basic", authentication_basic)
         if authentication_token is not None:
             pulumi.set(__self__, "authentication_token", authentication_token)
         if authorization is not None:
             pulumi.set(__self__, "authorization", authorization)
@@ -230,14 +236,16 @@
         pulumi.set(self, "service_endpoint_name", value)
 
     @property
     @pulumi.getter
     def url(self) -> Optional[pulumi.Input[str]]:
         """
         URL of the Artifactory server to connect with.
+
+        > **NOTE:** URL should not end in a slash character.
         """
         return pulumi.get(self, "url")
 
     @url.setter
     def url(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "url", value)
 
@@ -318,14 +326,16 @@
         :param pulumi.ResourceOptions opts: Options for the resource.
         :param pulumi.Input[pulumi.InputType['ServiceendpointJfrogDistributionV2AuthenticationBasicArgs']] authentication_basic: A `authentication_basic` block as documented below.
         :param pulumi.Input[pulumi.InputType['ServiceendpointJfrogDistributionV2AuthenticationTokenArgs']] authentication_token: A `authentication_token` block as documented below.
         :param pulumi.Input[str] description: The Service Endpoint description.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         :param pulumi.Input[str] url: URL of the Artifactory server to connect with.
+               
+               > **NOTE:** URL should not end in a slash character.
         """
         ...
     @overload
     def __init__(__self__,
                  resource_name: str,
                  args: ServiceendpointJfrogDistributionV2Args,
                  opts: Optional[pulumi.ResourceOptions] = None):
@@ -458,14 +468,16 @@
         :param pulumi.ResourceOptions opts: Options for the resource.
         :param pulumi.Input[pulumi.InputType['ServiceendpointJfrogDistributionV2AuthenticationBasicArgs']] authentication_basic: A `authentication_basic` block as documented below.
         :param pulumi.Input[pulumi.InputType['ServiceendpointJfrogDistributionV2AuthenticationTokenArgs']] authentication_token: A `authentication_token` block as documented below.
         :param pulumi.Input[str] description: The Service Endpoint description.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         :param pulumi.Input[str] url: URL of the Artifactory server to connect with.
+               
+               > **NOTE:** URL should not end in a slash character.
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
 
         __props__ = _ServiceendpointJfrogDistributionV2State.__new__(_ServiceendpointJfrogDistributionV2State)
 
         __props__.__dict__["authentication_basic"] = authentication_basic
         __props__.__dict__["authentication_token"] = authentication_token
@@ -522,10 +534,12 @@
         return pulumi.get(self, "service_endpoint_name")
 
     @property
     @pulumi.getter
     def url(self) -> pulumi.Output[str]:
         """
         URL of the Artifactory server to connect with.
+
+        > **NOTE:** URL should not end in a slash character.
         """
         return pulumi.get(self, "url")
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint_jfrog_platform_v2.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint_jfrog_platform_v2.py`

 * *Files 4% similar despite different names*

```diff
@@ -24,14 +24,16 @@
                  authorization: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
                  description: Optional[pulumi.Input[str]] = None):
         """
         The set of arguments for constructing a ServiceendpointJfrogPlatformV2 resource.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         :param pulumi.Input[str] url: URL of the Artifactory server to connect with.
+               
+               > **NOTE:** URL should not end in a slash character.
         :param pulumi.Input['ServiceendpointJfrogPlatformV2AuthenticationBasicArgs'] authentication_basic: A `authentication_basic` block as documented below.
         :param pulumi.Input['ServiceendpointJfrogPlatformV2AuthenticationTokenArgs'] authentication_token: A `authentication_token` block as documented below.
         :param pulumi.Input[str] description: The Service Endpoint description.
         """
         pulumi.set(__self__, "project_id", project_id)
         pulumi.set(__self__, "service_endpoint_name", service_endpoint_name)
         pulumi.set(__self__, "url", url)
@@ -69,14 +71,16 @@
         pulumi.set(self, "service_endpoint_name", value)
 
     @property
     @pulumi.getter
     def url(self) -> pulumi.Input[str]:
         """
         URL of the Artifactory server to connect with.
+
+        > **NOTE:** URL should not end in a slash character.
         """
         return pulumi.get(self, "url")
 
     @url.setter
     def url(self, value: pulumi.Input[str]):
         pulumi.set(self, "url", value)
 
@@ -140,14 +144,16 @@
         Input properties used for looking up and filtering ServiceendpointJfrogPlatformV2 resources.
         :param pulumi.Input['ServiceendpointJfrogPlatformV2AuthenticationBasicArgs'] authentication_basic: A `authentication_basic` block as documented below.
         :param pulumi.Input['ServiceendpointJfrogPlatformV2AuthenticationTokenArgs'] authentication_token: A `authentication_token` block as documented below.
         :param pulumi.Input[str] description: The Service Endpoint description.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         :param pulumi.Input[str] url: URL of the Artifactory server to connect with.
+               
+               > **NOTE:** URL should not end in a slash character.
         """
         if authentication_basic is not None:
             pulumi.set(__self__, "authentication_basic", authentication_basic)
         if authentication_token is not None:
             pulumi.set(__self__, "authentication_token", authentication_token)
         if authorization is not None:
             pulumi.set(__self__, "authorization", authorization)
@@ -230,14 +236,16 @@
         pulumi.set(self, "service_endpoint_name", value)
 
     @property
     @pulumi.getter
     def url(self) -> Optional[pulumi.Input[str]]:
         """
         URL of the Artifactory server to connect with.
+
+        > **NOTE:** URL should not end in a slash character.
         """
         return pulumi.get(self, "url")
 
     @url.setter
     def url(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "url", value)
 
@@ -318,14 +326,16 @@
         :param pulumi.ResourceOptions opts: Options for the resource.
         :param pulumi.Input[pulumi.InputType['ServiceendpointJfrogPlatformV2AuthenticationBasicArgs']] authentication_basic: A `authentication_basic` block as documented below.
         :param pulumi.Input[pulumi.InputType['ServiceendpointJfrogPlatformV2AuthenticationTokenArgs']] authentication_token: A `authentication_token` block as documented below.
         :param pulumi.Input[str] description: The Service Endpoint description.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         :param pulumi.Input[str] url: URL of the Artifactory server to connect with.
+               
+               > **NOTE:** URL should not end in a slash character.
         """
         ...
     @overload
     def __init__(__self__,
                  resource_name: str,
                  args: ServiceendpointJfrogPlatformV2Args,
                  opts: Optional[pulumi.ResourceOptions] = None):
@@ -458,14 +468,16 @@
         :param pulumi.ResourceOptions opts: Options for the resource.
         :param pulumi.Input[pulumi.InputType['ServiceendpointJfrogPlatformV2AuthenticationBasicArgs']] authentication_basic: A `authentication_basic` block as documented below.
         :param pulumi.Input[pulumi.InputType['ServiceendpointJfrogPlatformV2AuthenticationTokenArgs']] authentication_token: A `authentication_token` block as documented below.
         :param pulumi.Input[str] description: The Service Endpoint description.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         :param pulumi.Input[str] url: URL of the Artifactory server to connect with.
+               
+               > **NOTE:** URL should not end in a slash character.
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
 
         __props__ = _ServiceendpointJfrogPlatformV2State.__new__(_ServiceendpointJfrogPlatformV2State)
 
         __props__.__dict__["authentication_basic"] = authentication_basic
         __props__.__dict__["authentication_token"] = authentication_token
@@ -522,10 +534,12 @@
         return pulumi.get(self, "service_endpoint_name")
 
     @property
     @pulumi.getter
     def url(self) -> pulumi.Output[str]:
         """
         URL of the Artifactory server to connect with.
+
+        > **NOTE:** URL should not end in a slash character.
         """
         return pulumi.get(self, "url")
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint_jfrog_xray_v2.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint_jfrog_xray_v2.py`

 * *Files 2% similar despite different names*

```diff
@@ -24,14 +24,16 @@
                  authorization: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
                  description: Optional[pulumi.Input[str]] = None):
         """
         The set of arguments for constructing a ServiceendpointJfrogXrayV2 resource.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         :param pulumi.Input[str] url: URL of the Artifactory server to connect with.
+               
+               > **NOTE:** URL should not end in a slash character.
         :param pulumi.Input['ServiceendpointJfrogXrayV2AuthenticationBasicArgs'] authentication_basic: A `authentication_basic` block as documented below.
         :param pulumi.Input['ServiceendpointJfrogXrayV2AuthenticationTokenArgs'] authentication_token: A `authentication_token` block as documented below.
         :param pulumi.Input[str] description: The Service Endpoint description.
         """
         pulumi.set(__self__, "project_id", project_id)
         pulumi.set(__self__, "service_endpoint_name", service_endpoint_name)
         pulumi.set(__self__, "url", url)
@@ -69,14 +71,16 @@
         pulumi.set(self, "service_endpoint_name", value)
 
     @property
     @pulumi.getter
     def url(self) -> pulumi.Input[str]:
         """
         URL of the Artifactory server to connect with.
+
+        > **NOTE:** URL should not end in a slash character.
         """
         return pulumi.get(self, "url")
 
     @url.setter
     def url(self, value: pulumi.Input[str]):
         pulumi.set(self, "url", value)
 
@@ -140,14 +144,16 @@
         Input properties used for looking up and filtering ServiceendpointJfrogXrayV2 resources.
         :param pulumi.Input['ServiceendpointJfrogXrayV2AuthenticationBasicArgs'] authentication_basic: A `authentication_basic` block as documented below.
         :param pulumi.Input['ServiceendpointJfrogXrayV2AuthenticationTokenArgs'] authentication_token: A `authentication_token` block as documented below.
         :param pulumi.Input[str] description: The Service Endpoint description.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         :param pulumi.Input[str] url: URL of the Artifactory server to connect with.
+               
+               > **NOTE:** URL should not end in a slash character.
         """
         if authentication_basic is not None:
             pulumi.set(__self__, "authentication_basic", authentication_basic)
         if authentication_token is not None:
             pulumi.set(__self__, "authentication_token", authentication_token)
         if authorization is not None:
             pulumi.set(__self__, "authorization", authorization)
@@ -230,14 +236,16 @@
         pulumi.set(self, "service_endpoint_name", value)
 
     @property
     @pulumi.getter
     def url(self) -> Optional[pulumi.Input[str]]:
         """
         URL of the Artifactory server to connect with.
+
+        > **NOTE:** URL should not end in a slash character.
         """
         return pulumi.get(self, "url")
 
     @url.setter
     def url(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "url", value)
 
@@ -318,14 +326,16 @@
         :param pulumi.ResourceOptions opts: Options for the resource.
         :param pulumi.Input[pulumi.InputType['ServiceendpointJfrogXrayV2AuthenticationBasicArgs']] authentication_basic: A `authentication_basic` block as documented below.
         :param pulumi.Input[pulumi.InputType['ServiceendpointJfrogXrayV2AuthenticationTokenArgs']] authentication_token: A `authentication_token` block as documented below.
         :param pulumi.Input[str] description: The Service Endpoint description.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         :param pulumi.Input[str] url: URL of the Artifactory server to connect with.
+               
+               > **NOTE:** URL should not end in a slash character.
         """
         ...
     @overload
     def __init__(__self__,
                  resource_name: str,
                  args: ServiceendpointJfrogXrayV2Args,
                  opts: Optional[pulumi.ResourceOptions] = None):
@@ -458,14 +468,16 @@
         :param pulumi.ResourceOptions opts: Options for the resource.
         :param pulumi.Input[pulumi.InputType['ServiceendpointJfrogXrayV2AuthenticationBasicArgs']] authentication_basic: A `authentication_basic` block as documented below.
         :param pulumi.Input[pulumi.InputType['ServiceendpointJfrogXrayV2AuthenticationTokenArgs']] authentication_token: A `authentication_token` block as documented below.
         :param pulumi.Input[str] description: The Service Endpoint description.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
         :param pulumi.Input[str] url: URL of the Artifactory server to connect with.
+               
+               > **NOTE:** URL should not end in a slash character.
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
 
         __props__ = _ServiceendpointJfrogXrayV2State.__new__(_ServiceendpointJfrogXrayV2State)
 
         __props__.__dict__["authentication_basic"] = authentication_basic
         __props__.__dict__["authentication_token"] = authentication_token
@@ -522,10 +534,12 @@
         return pulumi.get(self, "service_endpoint_name")
 
     @property
     @pulumi.getter
     def url(self) -> pulumi.Output[str]:
         """
         URL of the Artifactory server to connect with.
+
+        > **NOTE:** URL should not end in a slash character.
         """
         return pulumi.get(self, "url")
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint_octopusdeploy.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint_gcp_terraform.py`

 * *Files 18% similar despite different names*

```diff
@@ -5,56 +5,75 @@
 import copy
 import warnings
 import pulumi
 import pulumi.runtime
 from typing import Any, Mapping, Optional, Sequence, Union, overload
 from . import _utilities
 
-__all__ = ['ServiceendpointOctopusdeployArgs', 'ServiceendpointOctopusdeploy']
+__all__ = ['ServiceendpointGcpTerraformArgs', 'ServiceendpointGcpTerraform']
 
 @pulumi.input_type
-class ServiceendpointOctopusdeployArgs:
+class ServiceendpointGcpTerraformArgs:
     def __init__(__self__, *,
-                 api_key: pulumi.Input[str],
+                 gcp_project_id: pulumi.Input[str],
+                 private_key: pulumi.Input[str],
                  project_id: pulumi.Input[str],
                  service_endpoint_name: pulumi.Input[str],
-                 url: pulumi.Input[str],
+                 token_uri: pulumi.Input[str],
                  authorization: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
+                 client_email: Optional[pulumi.Input[str]] = None,
                  description: Optional[pulumi.Input[str]] = None,
-                 ignore_ssl_error: Optional[pulumi.Input[bool]] = None):
+                 scope: Optional[pulumi.Input[str]] = None):
         """
-        The set of arguments for constructing a ServiceendpointOctopusdeploy resource.
-        :param pulumi.Input[str] api_key: API key to connect to Octopus Deploy.
+        The set of arguments for constructing a ServiceendpointGcpTerraform resource.
+        :param pulumi.Input[str] gcp_project_id: GCP project associated with the Service Connection.
+        :param pulumi.Input[str] private_key: The client email field in the JSON key file for creating the JSON Web Token.
         :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
-        :param pulumi.Input[str] url: Octopus Server url.
-        :param pulumi.Input[bool] ignore_ssl_error: Whether to ignore SSL errors when connecting to the Octopus server from the agent. Default to `false`.
+        :param pulumi.Input[str] token_uri: The token uri field in the JSON key file for creating the JSON Web Token.
+        :param pulumi.Input[str] client_email: The client email field in the JSON key file for creating the JSON Web Token.
+        :param pulumi.Input[str] scope: Scope to be provided.
         """
-        pulumi.set(__self__, "api_key", api_key)
+        pulumi.set(__self__, "gcp_project_id", gcp_project_id)
+        pulumi.set(__self__, "private_key", private_key)
         pulumi.set(__self__, "project_id", project_id)
         pulumi.set(__self__, "service_endpoint_name", service_endpoint_name)
-        pulumi.set(__self__, "url", url)
+        pulumi.set(__self__, "token_uri", token_uri)
         if authorization is not None:
             pulumi.set(__self__, "authorization", authorization)
+        if client_email is not None:
+            pulumi.set(__self__, "client_email", client_email)
         if description is not None:
             pulumi.set(__self__, "description", description)
-        if ignore_ssl_error is not None:
-            pulumi.set(__self__, "ignore_ssl_error", ignore_ssl_error)
+        if scope is not None:
+            pulumi.set(__self__, "scope", scope)
 
     @property
-    @pulumi.getter(name="apiKey")
-    def api_key(self) -> pulumi.Input[str]:
+    @pulumi.getter(name="gcpProjectId")
+    def gcp_project_id(self) -> pulumi.Input[str]:
         """
-        API key to connect to Octopus Deploy.
+        GCP project associated with the Service Connection.
         """
-        return pulumi.get(self, "api_key")
+        return pulumi.get(self, "gcp_project_id")
 
-    @api_key.setter
-    def api_key(self, value: pulumi.Input[str]):
-        pulumi.set(self, "api_key", value)
+    @gcp_project_id.setter
+    def gcp_project_id(self, value: pulumi.Input[str]):
+        pulumi.set(self, "gcp_project_id", value)
+
+    @property
+    @pulumi.getter(name="privateKey")
+    def private_key(self) -> pulumi.Input[str]:
+        """
+        The client email field in the JSON key file for creating the JSON Web Token.
+        """
+        return pulumi.get(self, "private_key")
+
+    @private_key.setter
+    def private_key(self, value: pulumi.Input[str]):
+        pulumi.set(self, "private_key", value)
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> pulumi.Input[str]:
         """
         The ID of the project.
         """
@@ -73,393 +92,471 @@
         return pulumi.get(self, "service_endpoint_name")
 
     @service_endpoint_name.setter
     def service_endpoint_name(self, value: pulumi.Input[str]):
         pulumi.set(self, "service_endpoint_name", value)
 
     @property
-    @pulumi.getter
-    def url(self) -> pulumi.Input[str]:
+    @pulumi.getter(name="tokenUri")
+    def token_uri(self) -> pulumi.Input[str]:
         """
-        Octopus Server url.
+        The token uri field in the JSON key file for creating the JSON Web Token.
         """
-        return pulumi.get(self, "url")
+        return pulumi.get(self, "token_uri")
 
-    @url.setter
-    def url(self, value: pulumi.Input[str]):
-        pulumi.set(self, "url", value)
+    @token_uri.setter
+    def token_uri(self, value: pulumi.Input[str]):
+        pulumi.set(self, "token_uri", value)
 
     @property
     @pulumi.getter
     def authorization(self) -> Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]:
         return pulumi.get(self, "authorization")
 
     @authorization.setter
     def authorization(self, value: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]):
         pulumi.set(self, "authorization", value)
 
     @property
+    @pulumi.getter(name="clientEmail")
+    def client_email(self) -> Optional[pulumi.Input[str]]:
+        """
+        The client email field in the JSON key file for creating the JSON Web Token.
+        """
+        return pulumi.get(self, "client_email")
+
+    @client_email.setter
+    def client_email(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "client_email", value)
+
+    @property
     @pulumi.getter
     def description(self) -> Optional[pulumi.Input[str]]:
         return pulumi.get(self, "description")
 
     @description.setter
     def description(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "description", value)
 
     @property
-    @pulumi.getter(name="ignoreSslError")
-    def ignore_ssl_error(self) -> Optional[pulumi.Input[bool]]:
+    @pulumi.getter
+    def scope(self) -> Optional[pulumi.Input[str]]:
         """
-        Whether to ignore SSL errors when connecting to the Octopus server from the agent. Default to `false`.
+        Scope to be provided.
         """
-        return pulumi.get(self, "ignore_ssl_error")
+        return pulumi.get(self, "scope")
 
-    @ignore_ssl_error.setter
-    def ignore_ssl_error(self, value: Optional[pulumi.Input[bool]]):
-        pulumi.set(self, "ignore_ssl_error", value)
+    @scope.setter
+    def scope(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "scope", value)
 
 
 @pulumi.input_type
-class _ServiceendpointOctopusdeployState:
+class _ServiceendpointGcpTerraformState:
     def __init__(__self__, *,
-                 api_key: Optional[pulumi.Input[str]] = None,
                  authorization: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
+                 client_email: Optional[pulumi.Input[str]] = None,
                  description: Optional[pulumi.Input[str]] = None,
-                 ignore_ssl_error: Optional[pulumi.Input[bool]] = None,
+                 gcp_project_id: Optional[pulumi.Input[str]] = None,
+                 private_key: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
+                 scope: Optional[pulumi.Input[str]] = None,
                  service_endpoint_name: Optional[pulumi.Input[str]] = None,
-                 url: Optional[pulumi.Input[str]] = None):
+                 token_uri: Optional[pulumi.Input[str]] = None):
         """
-        Input properties used for looking up and filtering ServiceendpointOctopusdeploy resources.
-        :param pulumi.Input[str] api_key: API key to connect to Octopus Deploy.
-        :param pulumi.Input[bool] ignore_ssl_error: Whether to ignore SSL errors when connecting to the Octopus server from the agent. Default to `false`.
+        Input properties used for looking up and filtering ServiceendpointGcpTerraform resources.
+        :param pulumi.Input[str] client_email: The client email field in the JSON key file for creating the JSON Web Token.
+        :param pulumi.Input[str] gcp_project_id: GCP project associated with the Service Connection.
+        :param pulumi.Input[str] private_key: The client email field in the JSON key file for creating the JSON Web Token.
         :param pulumi.Input[str] project_id: The ID of the project.
+        :param pulumi.Input[str] scope: Scope to be provided.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
-        :param pulumi.Input[str] url: Octopus Server url.
+        :param pulumi.Input[str] token_uri: The token uri field in the JSON key file for creating the JSON Web Token.
         """
-        if api_key is not None:
-            pulumi.set(__self__, "api_key", api_key)
         if authorization is not None:
             pulumi.set(__self__, "authorization", authorization)
+        if client_email is not None:
+            pulumi.set(__self__, "client_email", client_email)
         if description is not None:
             pulumi.set(__self__, "description", description)
-        if ignore_ssl_error is not None:
-            pulumi.set(__self__, "ignore_ssl_error", ignore_ssl_error)
+        if gcp_project_id is not None:
+            pulumi.set(__self__, "gcp_project_id", gcp_project_id)
+        if private_key is not None:
+            pulumi.set(__self__, "private_key", private_key)
         if project_id is not None:
             pulumi.set(__self__, "project_id", project_id)
+        if scope is not None:
+            pulumi.set(__self__, "scope", scope)
         if service_endpoint_name is not None:
             pulumi.set(__self__, "service_endpoint_name", service_endpoint_name)
-        if url is not None:
-            pulumi.set(__self__, "url", url)
-
-    @property
-    @pulumi.getter(name="apiKey")
-    def api_key(self) -> Optional[pulumi.Input[str]]:
-        """
-        API key to connect to Octopus Deploy.
-        """
-        return pulumi.get(self, "api_key")
-
-    @api_key.setter
-    def api_key(self, value: Optional[pulumi.Input[str]]):
-        pulumi.set(self, "api_key", value)
+        if token_uri is not None:
+            pulumi.set(__self__, "token_uri", token_uri)
 
     @property
     @pulumi.getter
     def authorization(self) -> Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]:
         return pulumi.get(self, "authorization")
 
     @authorization.setter
     def authorization(self, value: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]):
         pulumi.set(self, "authorization", value)
 
     @property
+    @pulumi.getter(name="clientEmail")
+    def client_email(self) -> Optional[pulumi.Input[str]]:
+        """
+        The client email field in the JSON key file for creating the JSON Web Token.
+        """
+        return pulumi.get(self, "client_email")
+
+    @client_email.setter
+    def client_email(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "client_email", value)
+
+    @property
     @pulumi.getter
     def description(self) -> Optional[pulumi.Input[str]]:
         return pulumi.get(self, "description")
 
     @description.setter
     def description(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "description", value)
 
     @property
-    @pulumi.getter(name="ignoreSslError")
-    def ignore_ssl_error(self) -> Optional[pulumi.Input[bool]]:
+    @pulumi.getter(name="gcpProjectId")
+    def gcp_project_id(self) -> Optional[pulumi.Input[str]]:
+        """
+        GCP project associated with the Service Connection.
+        """
+        return pulumi.get(self, "gcp_project_id")
+
+    @gcp_project_id.setter
+    def gcp_project_id(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "gcp_project_id", value)
+
+    @property
+    @pulumi.getter(name="privateKey")
+    def private_key(self) -> Optional[pulumi.Input[str]]:
         """
-        Whether to ignore SSL errors when connecting to the Octopus server from the agent. Default to `false`.
+        The client email field in the JSON key file for creating the JSON Web Token.
         """
-        return pulumi.get(self, "ignore_ssl_error")
+        return pulumi.get(self, "private_key")
 
-    @ignore_ssl_error.setter
-    def ignore_ssl_error(self, value: Optional[pulumi.Input[bool]]):
-        pulumi.set(self, "ignore_ssl_error", value)
+    @private_key.setter
+    def private_key(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "private_key", value)
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> Optional[pulumi.Input[str]]:
         """
         The ID of the project.
         """
         return pulumi.get(self, "project_id")
 
     @project_id.setter
     def project_id(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "project_id", value)
 
     @property
+    @pulumi.getter
+    def scope(self) -> Optional[pulumi.Input[str]]:
+        """
+        Scope to be provided.
+        """
+        return pulumi.get(self, "scope")
+
+    @scope.setter
+    def scope(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "scope", value)
+
+    @property
     @pulumi.getter(name="serviceEndpointName")
     def service_endpoint_name(self) -> Optional[pulumi.Input[str]]:
         """
         The Service Endpoint name.
         """
         return pulumi.get(self, "service_endpoint_name")
 
     @service_endpoint_name.setter
     def service_endpoint_name(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "service_endpoint_name", value)
 
     @property
-    @pulumi.getter
-    def url(self) -> Optional[pulumi.Input[str]]:
+    @pulumi.getter(name="tokenUri")
+    def token_uri(self) -> Optional[pulumi.Input[str]]:
         """
-        Octopus Server url.
+        The token uri field in the JSON key file for creating the JSON Web Token.
         """
-        return pulumi.get(self, "url")
+        return pulumi.get(self, "token_uri")
 
-    @url.setter
-    def url(self, value: Optional[pulumi.Input[str]]):
-        pulumi.set(self, "url", value)
+    @token_uri.setter
+    def token_uri(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "token_uri", value)
 
 
-class ServiceendpointOctopusdeploy(pulumi.CustomResource):
+class ServiceendpointGcpTerraform(pulumi.CustomResource):
     @overload
     def __init__(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
-                 api_key: Optional[pulumi.Input[str]] = None,
                  authorization: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
+                 client_email: Optional[pulumi.Input[str]] = None,
                  description: Optional[pulumi.Input[str]] = None,
-                 ignore_ssl_error: Optional[pulumi.Input[bool]] = None,
+                 gcp_project_id: Optional[pulumi.Input[str]] = None,
+                 private_key: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
+                 scope: Optional[pulumi.Input[str]] = None,
                  service_endpoint_name: Optional[pulumi.Input[str]] = None,
-                 url: Optional[pulumi.Input[str]] = None,
+                 token_uri: Optional[pulumi.Input[str]] = None,
                  __props__=None):
         """
-        Manages an Octopus Deploy service endpoint within Azure DevOps. Using this service endpoint requires you to install [Octopus Deploy](https://marketplace.visualstudio.com/items?itemName=octopusdeploy.octopus-deploy-build-release-tasks).
-
         ## Example Usage
 
         ```python
         import pulumi
         import pulumi_azuredevops as azuredevops
 
         example_project = azuredevops.Project("exampleProject",
             visibility="private",
             version_control="Git",
             work_item_template="Agile",
             description="Managed by Terraform")
-        example_serviceendpoint_octopusdeploy = azuredevops.ServiceendpointOctopusdeploy("exampleServiceendpointOctopusdeploy",
+        example_serviceendpoint_gcp_terraform = azuredevops.ServiceendpointGcpTerraform("exampleServiceendpointGcpTerraform",
             project_id=example_project.id,
-            url="https://octopus.com",
-            api_key="000000000000000000000000000000000000",
-            service_endpoint_name="Example Octopus Deploy",
+            token_uri="https://oauth2.example.com/token",
+            client_email="gcp-sa-example@example.iam.gserviceaccount.com",
+            private_key="0000000000000000000000000000000000000",
+            service_endpoint_name="Example GCP Terraform extension",
+            gcp_project_id="Example GCP Project",
             description="Managed by Terraform")
         ```
         ## Relevant Links
 
-        - [Azure DevOps Service REST API 6.0 - Agent Pools](https://docs.microsoft.com/en-us/rest/api/azure/devops/serviceendpoint/endpoints?view=azure-devops-rest-6.0)
+        - [Azure DevOps Service REST API 7.1 - Service Endpoints](https://docs.microsoft.com/en-us/rest/api/azure/devops/serviceendpoint/endpoints?view=azure-devops-rest-7.1)
 
         ## Import
 
-        Azure DevOps Service Endpoint Octopus Deploy can be imported using **projectID/serviceEndpointID** or **projectName/serviceEndpointID**
+        Azure DevOps Service Endpoint GCP can be imported using **projectID/serviceEndpointID** or **projectName/serviceEndpointID**
 
         ```sh
-         $ pulumi import azuredevops:index/serviceendpointOctopusdeploy:ServiceendpointOctopusdeploy example 00000000-0000-0000-0000-000000000000/00000000-0000-0000-0000-000000000000
+         $ pulumi import azuredevops:index/serviceendpointGcpTerraform:ServiceendpointGcpTerraform azuredevops_serviceendpoint_gcp_terraform.example 00000000-0000-0000-0000-000000000000/00000000-0000-0000-0000-000000000000
         ```
 
         :param str resource_name: The name of the resource.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[str] api_key: API key to connect to Octopus Deploy.
-        :param pulumi.Input[bool] ignore_ssl_error: Whether to ignore SSL errors when connecting to the Octopus server from the agent. Default to `false`.
+        :param pulumi.Input[str] client_email: The client email field in the JSON key file for creating the JSON Web Token.
+        :param pulumi.Input[str] gcp_project_id: GCP project associated with the Service Connection.
+        :param pulumi.Input[str] private_key: The client email field in the JSON key file for creating the JSON Web Token.
         :param pulumi.Input[str] project_id: The ID of the project.
+        :param pulumi.Input[str] scope: Scope to be provided.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
-        :param pulumi.Input[str] url: Octopus Server url.
+        :param pulumi.Input[str] token_uri: The token uri field in the JSON key file for creating the JSON Web Token.
         """
         ...
     @overload
     def __init__(__self__,
                  resource_name: str,
-                 args: ServiceendpointOctopusdeployArgs,
+                 args: ServiceendpointGcpTerraformArgs,
                  opts: Optional[pulumi.ResourceOptions] = None):
         """
-        Manages an Octopus Deploy service endpoint within Azure DevOps. Using this service endpoint requires you to install [Octopus Deploy](https://marketplace.visualstudio.com/items?itemName=octopusdeploy.octopus-deploy-build-release-tasks).
-
         ## Example Usage
 
         ```python
         import pulumi
         import pulumi_azuredevops as azuredevops
 
         example_project = azuredevops.Project("exampleProject",
             visibility="private",
             version_control="Git",
             work_item_template="Agile",
             description="Managed by Terraform")
-        example_serviceendpoint_octopusdeploy = azuredevops.ServiceendpointOctopusdeploy("exampleServiceendpointOctopusdeploy",
+        example_serviceendpoint_gcp_terraform = azuredevops.ServiceendpointGcpTerraform("exampleServiceendpointGcpTerraform",
             project_id=example_project.id,
-            url="https://octopus.com",
-            api_key="000000000000000000000000000000000000",
-            service_endpoint_name="Example Octopus Deploy",
+            token_uri="https://oauth2.example.com/token",
+            client_email="gcp-sa-example@example.iam.gserviceaccount.com",
+            private_key="0000000000000000000000000000000000000",
+            service_endpoint_name="Example GCP Terraform extension",
+            gcp_project_id="Example GCP Project",
             description="Managed by Terraform")
         ```
         ## Relevant Links
 
-        - [Azure DevOps Service REST API 6.0 - Agent Pools](https://docs.microsoft.com/en-us/rest/api/azure/devops/serviceendpoint/endpoints?view=azure-devops-rest-6.0)
+        - [Azure DevOps Service REST API 7.1 - Service Endpoints](https://docs.microsoft.com/en-us/rest/api/azure/devops/serviceendpoint/endpoints?view=azure-devops-rest-7.1)
 
         ## Import
 
-        Azure DevOps Service Endpoint Octopus Deploy can be imported using **projectID/serviceEndpointID** or **projectName/serviceEndpointID**
+        Azure DevOps Service Endpoint GCP can be imported using **projectID/serviceEndpointID** or **projectName/serviceEndpointID**
 
         ```sh
-         $ pulumi import azuredevops:index/serviceendpointOctopusdeploy:ServiceendpointOctopusdeploy example 00000000-0000-0000-0000-000000000000/00000000-0000-0000-0000-000000000000
+         $ pulumi import azuredevops:index/serviceendpointGcpTerraform:ServiceendpointGcpTerraform azuredevops_serviceendpoint_gcp_terraform.example 00000000-0000-0000-0000-000000000000/00000000-0000-0000-0000-000000000000
         ```
 
         :param str resource_name: The name of the resource.
-        :param ServiceendpointOctopusdeployArgs args: The arguments to use to populate this resource's properties.
+        :param ServiceendpointGcpTerraformArgs args: The arguments to use to populate this resource's properties.
         :param pulumi.ResourceOptions opts: Options for the resource.
         """
         ...
     def __init__(__self__, resource_name: str, *args, **kwargs):
-        resource_args, opts = _utilities.get_resource_args_opts(ServiceendpointOctopusdeployArgs, pulumi.ResourceOptions, *args, **kwargs)
+        resource_args, opts = _utilities.get_resource_args_opts(ServiceendpointGcpTerraformArgs, pulumi.ResourceOptions, *args, **kwargs)
         if resource_args is not None:
             __self__._internal_init(resource_name, opts, **resource_args.__dict__)
         else:
             __self__._internal_init(resource_name, *args, **kwargs)
 
     def _internal_init(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
-                 api_key: Optional[pulumi.Input[str]] = None,
                  authorization: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
+                 client_email: Optional[pulumi.Input[str]] = None,
                  description: Optional[pulumi.Input[str]] = None,
-                 ignore_ssl_error: Optional[pulumi.Input[bool]] = None,
+                 gcp_project_id: Optional[pulumi.Input[str]] = None,
+                 private_key: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
+                 scope: Optional[pulumi.Input[str]] = None,
                  service_endpoint_name: Optional[pulumi.Input[str]] = None,
-                 url: Optional[pulumi.Input[str]] = None,
+                 token_uri: Optional[pulumi.Input[str]] = None,
                  __props__=None):
         opts = pulumi.ResourceOptions.merge(_utilities.get_resource_opts_defaults(), opts)
         if not isinstance(opts, pulumi.ResourceOptions):
             raise TypeError('Expected resource options to be a ResourceOptions instance')
         if opts.id is None:
             if __props__ is not None:
                 raise TypeError('__props__ is only valid when passed in combination with a valid opts.id to get an existing resource')
-            __props__ = ServiceendpointOctopusdeployArgs.__new__(ServiceendpointOctopusdeployArgs)
+            __props__ = ServiceendpointGcpTerraformArgs.__new__(ServiceendpointGcpTerraformArgs)
 
-            if api_key is None and not opts.urn:
-                raise TypeError("Missing required property 'api_key'")
-            __props__.__dict__["api_key"] = api_key
             __props__.__dict__["authorization"] = authorization
+            __props__.__dict__["client_email"] = client_email
             __props__.__dict__["description"] = description
-            __props__.__dict__["ignore_ssl_error"] = ignore_ssl_error
+            if gcp_project_id is None and not opts.urn:
+                raise TypeError("Missing required property 'gcp_project_id'")
+            __props__.__dict__["gcp_project_id"] = gcp_project_id
+            if private_key is None and not opts.urn:
+                raise TypeError("Missing required property 'private_key'")
+            __props__.__dict__["private_key"] = None if private_key is None else pulumi.Output.secret(private_key)
             if project_id is None and not opts.urn:
                 raise TypeError("Missing required property 'project_id'")
             __props__.__dict__["project_id"] = project_id
+            __props__.__dict__["scope"] = scope
             if service_endpoint_name is None and not opts.urn:
                 raise TypeError("Missing required property 'service_endpoint_name'")
             __props__.__dict__["service_endpoint_name"] = service_endpoint_name
-            if url is None and not opts.urn:
-                raise TypeError("Missing required property 'url'")
-            __props__.__dict__["url"] = url
-        super(ServiceendpointOctopusdeploy, __self__).__init__(
-            'azuredevops:index/serviceendpointOctopusdeploy:ServiceendpointOctopusdeploy',
+            if token_uri is None and not opts.urn:
+                raise TypeError("Missing required property 'token_uri'")
+            __props__.__dict__["token_uri"] = token_uri
+        secret_opts = pulumi.ResourceOptions(additional_secret_outputs=["privateKey"])
+        opts = pulumi.ResourceOptions.merge(opts, secret_opts)
+        super(ServiceendpointGcpTerraform, __self__).__init__(
+            'azuredevops:index/serviceendpointGcpTerraform:ServiceendpointGcpTerraform',
             resource_name,
             __props__,
             opts)
 
     @staticmethod
     def get(resource_name: str,
             id: pulumi.Input[str],
             opts: Optional[pulumi.ResourceOptions] = None,
-            api_key: Optional[pulumi.Input[str]] = None,
             authorization: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
+            client_email: Optional[pulumi.Input[str]] = None,
             description: Optional[pulumi.Input[str]] = None,
-            ignore_ssl_error: Optional[pulumi.Input[bool]] = None,
+            gcp_project_id: Optional[pulumi.Input[str]] = None,
+            private_key: Optional[pulumi.Input[str]] = None,
             project_id: Optional[pulumi.Input[str]] = None,
+            scope: Optional[pulumi.Input[str]] = None,
             service_endpoint_name: Optional[pulumi.Input[str]] = None,
-            url: Optional[pulumi.Input[str]] = None) -> 'ServiceendpointOctopusdeploy':
+            token_uri: Optional[pulumi.Input[str]] = None) -> 'ServiceendpointGcpTerraform':
         """
-        Get an existing ServiceendpointOctopusdeploy resource's state with the given name, id, and optional extra
+        Get an existing ServiceendpointGcpTerraform resource's state with the given name, id, and optional extra
         properties used to qualify the lookup.
 
         :param str resource_name: The unique name of the resulting resource.
         :param pulumi.Input[str] id: The unique provider ID of the resource to lookup.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[str] api_key: API key to connect to Octopus Deploy.
-        :param pulumi.Input[bool] ignore_ssl_error: Whether to ignore SSL errors when connecting to the Octopus server from the agent. Default to `false`.
+        :param pulumi.Input[str] client_email: The client email field in the JSON key file for creating the JSON Web Token.
+        :param pulumi.Input[str] gcp_project_id: GCP project associated with the Service Connection.
+        :param pulumi.Input[str] private_key: The client email field in the JSON key file for creating the JSON Web Token.
         :param pulumi.Input[str] project_id: The ID of the project.
+        :param pulumi.Input[str] scope: Scope to be provided.
         :param pulumi.Input[str] service_endpoint_name: The Service Endpoint name.
-        :param pulumi.Input[str] url: Octopus Server url.
+        :param pulumi.Input[str] token_uri: The token uri field in the JSON key file for creating the JSON Web Token.
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
 
-        __props__ = _ServiceendpointOctopusdeployState.__new__(_ServiceendpointOctopusdeployState)
+        __props__ = _ServiceendpointGcpTerraformState.__new__(_ServiceendpointGcpTerraformState)
 
-        __props__.__dict__["api_key"] = api_key
         __props__.__dict__["authorization"] = authorization
+        __props__.__dict__["client_email"] = client_email
         __props__.__dict__["description"] = description
-        __props__.__dict__["ignore_ssl_error"] = ignore_ssl_error
+        __props__.__dict__["gcp_project_id"] = gcp_project_id
+        __props__.__dict__["private_key"] = private_key
         __props__.__dict__["project_id"] = project_id
+        __props__.__dict__["scope"] = scope
         __props__.__dict__["service_endpoint_name"] = service_endpoint_name
-        __props__.__dict__["url"] = url
-        return ServiceendpointOctopusdeploy(resource_name, opts=opts, __props__=__props__)
-
-    @property
-    @pulumi.getter(name="apiKey")
-    def api_key(self) -> pulumi.Output[str]:
-        """
-        API key to connect to Octopus Deploy.
-        """
-        return pulumi.get(self, "api_key")
+        __props__.__dict__["token_uri"] = token_uri
+        return ServiceendpointGcpTerraform(resource_name, opts=opts, __props__=__props__)
 
     @property
     @pulumi.getter
     def authorization(self) -> pulumi.Output[Mapping[str, str]]:
         return pulumi.get(self, "authorization")
 
     @property
+    @pulumi.getter(name="clientEmail")
+    def client_email(self) -> pulumi.Output[Optional[str]]:
+        """
+        The client email field in the JSON key file for creating the JSON Web Token.
+        """
+        return pulumi.get(self, "client_email")
+
+    @property
     @pulumi.getter
     def description(self) -> pulumi.Output[Optional[str]]:
         return pulumi.get(self, "description")
 
     @property
-    @pulumi.getter(name="ignoreSslError")
-    def ignore_ssl_error(self) -> pulumi.Output[Optional[bool]]:
+    @pulumi.getter(name="gcpProjectId")
+    def gcp_project_id(self) -> pulumi.Output[str]:
+        """
+        GCP project associated with the Service Connection.
+        """
+        return pulumi.get(self, "gcp_project_id")
+
+    @property
+    @pulumi.getter(name="privateKey")
+    def private_key(self) -> pulumi.Output[str]:
         """
-        Whether to ignore SSL errors when connecting to the Octopus server from the agent. Default to `false`.
+        The client email field in the JSON key file for creating the JSON Web Token.
         """
-        return pulumi.get(self, "ignore_ssl_error")
+        return pulumi.get(self, "private_key")
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> pulumi.Output[str]:
         """
         The ID of the project.
         """
         return pulumi.get(self, "project_id")
 
     @property
+    @pulumi.getter
+    def scope(self) -> pulumi.Output[Optional[str]]:
+        """
+        Scope to be provided.
+        """
+        return pulumi.get(self, "scope")
+
+    @property
     @pulumi.getter(name="serviceEndpointName")
     def service_endpoint_name(self) -> pulumi.Output[str]:
         """
         The Service Endpoint name.
         """
         return pulumi.get(self, "service_endpoint_name")
 
     @property
-    @pulumi.getter
-    def url(self) -> pulumi.Output[str]:
+    @pulumi.getter(name="tokenUri")
+    def token_uri(self) -> pulumi.Output[str]:
         """
-        Octopus Server url.
+        The token uri field in the JSON key file for creating the JSON Web Token.
         """
-        return pulumi.get(self, "url")
+        return pulumi.get(self, "token_uri")
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/serviceendpoint_permissions.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/area_permissions.py`

 * *Files 23% similar despite different names*

```diff
@@ -5,39 +5,50 @@
 import copy
 import warnings
 import pulumi
 import pulumi.runtime
 from typing import Any, Mapping, Optional, Sequence, Union, overload
 from . import _utilities
 
-__all__ = ['ServiceendpointPermissionsArgs', 'ServiceendpointPermissions']
+__all__ = ['AreaPermissionsArgs', 'AreaPermissions']
 
 @pulumi.input_type
-class ServiceendpointPermissionsArgs:
+class AreaPermissionsArgs:
     def __init__(__self__, *,
                  permissions: pulumi.Input[Mapping[str, pulumi.Input[str]]],
                  principal: pulumi.Input[str],
                  project_id: pulumi.Input[str],
-                 replace: Optional[pulumi.Input[bool]] = None,
-                 serviceendpoint_id: Optional[pulumi.Input[str]] = None):
+                 path: Optional[pulumi.Input[str]] = None,
+                 replace: Optional[pulumi.Input[bool]] = None):
         """
-        The set of arguments for constructing a ServiceendpointPermissions resource.
+        The set of arguments for constructing a AreaPermissions resource.
         :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available.
         :param pulumi.Input[str] principal: The **group** principal to assign the permissions.
-        :param pulumi.Input[str] project_id: The ID of the project.
-        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
-        :param pulumi.Input[str] serviceendpoint_id: The id of the service endpoint to assign the permissions.
+        :param pulumi.Input[str] project_id: The ID of the project to assign the permissions.
+        :param pulumi.Input[str] path: The name of the branch to assign the permissions.
+        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`.
+               
+               | Permission         | Description                    |
+               |--------------------|--------------------------------|
+               | GENERIC_READ       | View permissions for this node |
+               | GENERIC_WRITE      | Edit this node                 |
+               | CREATE_CHILDREN    | Create child nodes             |
+               | DELETE             | Delete this node               |
+               | WORK_ITEM_READ     | View work items in this node   |
+               | WORK_ITEM_WRITE    | Edit work items in this node   |
+               | MANAGE_TEST_PLANS  | Manage test plans              |
+               | MANAGE_TEST_SUITES | Manage test suites             |
         """
         pulumi.set(__self__, "permissions", permissions)
         pulumi.set(__self__, "principal", principal)
         pulumi.set(__self__, "project_id", project_id)
+        if path is not None:
+            pulumi.set(__self__, "path", path)
         if replace is not None:
             pulumi.set(__self__, "replace", replace)
-        if serviceendpoint_id is not None:
-            pulumi.set(__self__, "serviceendpoint_id", serviceendpoint_id)
 
     @property
     @pulumi.getter
     def permissions(self) -> pulumi.Input[Mapping[str, pulumi.Input[str]]]:
         """
         the permissions to assign. The following permissions are available.
         """
@@ -59,73 +70,107 @@
     def principal(self, value: pulumi.Input[str]):
         pulumi.set(self, "principal", value)
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> pulumi.Input[str]:
         """
-        The ID of the project.
+        The ID of the project to assign the permissions.
         """
         return pulumi.get(self, "project_id")
 
     @project_id.setter
     def project_id(self, value: pulumi.Input[str]):
         pulumi.set(self, "project_id", value)
 
     @property
     @pulumi.getter
-    def replace(self) -> Optional[pulumi.Input[bool]]:
+    def path(self) -> Optional[pulumi.Input[str]]:
         """
-        Replace (`true`) or merge (`false`) the permissions. Default: `true`
+        The name of the branch to assign the permissions.
         """
-        return pulumi.get(self, "replace")
+        return pulumi.get(self, "path")
 
-    @replace.setter
-    def replace(self, value: Optional[pulumi.Input[bool]]):
-        pulumi.set(self, "replace", value)
+    @path.setter
+    def path(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "path", value)
 
     @property
-    @pulumi.getter(name="serviceendpointId")
-    def serviceendpoint_id(self) -> Optional[pulumi.Input[str]]:
+    @pulumi.getter
+    def replace(self) -> Optional[pulumi.Input[bool]]:
         """
-        The id of the service endpoint to assign the permissions.
+        Replace (`true`) or merge (`false`) the permissions. Default: `true`.
+
+        | Permission         | Description                    |
+        |--------------------|--------------------------------|
+        | GENERIC_READ       | View permissions for this node |
+        | GENERIC_WRITE      | Edit this node                 |
+        | CREATE_CHILDREN    | Create child nodes             |
+        | DELETE             | Delete this node               |
+        | WORK_ITEM_READ     | View work items in this node   |
+        | WORK_ITEM_WRITE    | Edit work items in this node   |
+        | MANAGE_TEST_PLANS  | Manage test plans              |
+        | MANAGE_TEST_SUITES | Manage test suites             |
         """
-        return pulumi.get(self, "serviceendpoint_id")
+        return pulumi.get(self, "replace")
 
-    @serviceendpoint_id.setter
-    def serviceendpoint_id(self, value: Optional[pulumi.Input[str]]):
-        pulumi.set(self, "serviceendpoint_id", value)
+    @replace.setter
+    def replace(self, value: Optional[pulumi.Input[bool]]):
+        pulumi.set(self, "replace", value)
 
 
 @pulumi.input_type
-class _ServiceendpointPermissionsState:
+class _AreaPermissionsState:
     def __init__(__self__, *,
+                 path: Optional[pulumi.Input[str]] = None,
                  permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
                  principal: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
-                 replace: Optional[pulumi.Input[bool]] = None,
-                 serviceendpoint_id: Optional[pulumi.Input[str]] = None):
+                 replace: Optional[pulumi.Input[bool]] = None):
         """
-        Input properties used for looking up and filtering ServiceendpointPermissions resources.
+        Input properties used for looking up and filtering AreaPermissions resources.
+        :param pulumi.Input[str] path: The name of the branch to assign the permissions.
         :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available.
         :param pulumi.Input[str] principal: The **group** principal to assign the permissions.
-        :param pulumi.Input[str] project_id: The ID of the project.
-        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
-        :param pulumi.Input[str] serviceendpoint_id: The id of the service endpoint to assign the permissions.
+        :param pulumi.Input[str] project_id: The ID of the project to assign the permissions.
+        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`.
+               
+               | Permission         | Description                    |
+               |--------------------|--------------------------------|
+               | GENERIC_READ       | View permissions for this node |
+               | GENERIC_WRITE      | Edit this node                 |
+               | CREATE_CHILDREN    | Create child nodes             |
+               | DELETE             | Delete this node               |
+               | WORK_ITEM_READ     | View work items in this node   |
+               | WORK_ITEM_WRITE    | Edit work items in this node   |
+               | MANAGE_TEST_PLANS  | Manage test plans              |
+               | MANAGE_TEST_SUITES | Manage test suites             |
         """
+        if path is not None:
+            pulumi.set(__self__, "path", path)
         if permissions is not None:
             pulumi.set(__self__, "permissions", permissions)
         if principal is not None:
             pulumi.set(__self__, "principal", principal)
         if project_id is not None:
             pulumi.set(__self__, "project_id", project_id)
         if replace is not None:
             pulumi.set(__self__, "replace", replace)
-        if serviceendpoint_id is not None:
-            pulumi.set(__self__, "serviceendpoint_id", serviceendpoint_id)
+
+    @property
+    @pulumi.getter
+    def path(self) -> Optional[pulumi.Input[str]]:
+        """
+        The name of the branch to assign the permissions.
+        """
+        return pulumi.get(self, "path")
+
+    @path.setter
+    def path(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "path", value)
 
     @property
     @pulumi.getter
     def permissions(self) -> Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]:
         """
         the permissions to assign. The following permissions are available.
         """
@@ -147,108 +192,89 @@
     def principal(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "principal", value)
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> Optional[pulumi.Input[str]]:
         """
-        The ID of the project.
+        The ID of the project to assign the permissions.
         """
         return pulumi.get(self, "project_id")
 
     @project_id.setter
     def project_id(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "project_id", value)
 
     @property
     @pulumi.getter
     def replace(self) -> Optional[pulumi.Input[bool]]:
         """
-        Replace (`true`) or merge (`false`) the permissions. Default: `true`
+        Replace (`true`) or merge (`false`) the permissions. Default: `true`.
+
+        | Permission         | Description                    |
+        |--------------------|--------------------------------|
+        | GENERIC_READ       | View permissions for this node |
+        | GENERIC_WRITE      | Edit this node                 |
+        | CREATE_CHILDREN    | Create child nodes             |
+        | DELETE             | Delete this node               |
+        | WORK_ITEM_READ     | View work items in this node   |
+        | WORK_ITEM_WRITE    | Edit work items in this node   |
+        | MANAGE_TEST_PLANS  | Manage test plans              |
+        | MANAGE_TEST_SUITES | Manage test suites             |
         """
         return pulumi.get(self, "replace")
 
     @replace.setter
     def replace(self, value: Optional[pulumi.Input[bool]]):
         pulumi.set(self, "replace", value)
 
-    @property
-    @pulumi.getter(name="serviceendpointId")
-    def serviceendpoint_id(self) -> Optional[pulumi.Input[str]]:
-        """
-        The id of the service endpoint to assign the permissions.
-        """
-        return pulumi.get(self, "serviceendpoint_id")
-
-    @serviceendpoint_id.setter
-    def serviceendpoint_id(self, value: Optional[pulumi.Input[str]]):
-        pulumi.set(self, "serviceendpoint_id", value)
 
-
-class ServiceendpointPermissions(pulumi.CustomResource):
+class AreaPermissions(pulumi.CustomResource):
     @overload
     def __init__(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
+                 path: Optional[pulumi.Input[str]] = None,
                  permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
                  principal: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  replace: Optional[pulumi.Input[bool]] = None,
-                 serviceendpoint_id: Optional[pulumi.Input[str]] = None,
                  __props__=None):
         """
-        Manages permissions for a Service Endpoint
+        Manages permissions for an Area (Component)
 
         > **Note** Permissions can be assigned to group principals and not to single user principals.
 
         ## Permission levels
 
-        Permission for Service Endpoints within Azure DevOps can be applied on two different levels.
-        Those levels are reflected by specifying (or omitting) values for the arguments `project_id` and `serviceendpoint_id`.
+        Permission for Areas within Azure DevOps can be applied on two different levels.
+        Those levels are reflected by specifying (or omitting) values for the arguments `project_id` and `path`.
 
         ## Example Usage
 
         ```python
         import pulumi
         import pulumi_azuredevops as azuredevops
 
-        example_project = azuredevops.Project("exampleProject",
+        example = azuredevops.Project("example",
             work_item_template="Agile",
             version_control="Git",
             visibility="private",
             description="Managed by Terraform")
-        example_readers = azuredevops.get_group_output(project_id=example_project.id,
+        example_project_readers = azuredevops.get_group_output(project_id=example.id,
             name="Readers")
-        example_root_permissions = azuredevops.ServiceendpointPermissions("example-root-permissions",
-            project_id=example_project.id,
-            principal=example_readers.id,
-            permissions={
-                "Use": "allow",
-                "Administer": "allow",
-                "Create": "allow",
-                "ViewAuthorization": "allow",
-                "ViewEndpoint": "allow",
-            })
-        example_service_endpoint_docker_registry = azuredevops.ServiceEndpointDockerRegistry("exampleServiceEndpointDockerRegistry",
-            project_id=example_project.id,
-            service_endpoint_name="Example Docker Hub",
-            docker_username="username",
-            docker_email="email@example.com",
-            docker_password="password",
-            registry_type="DockerHub")
-        example_permissions = azuredevops.ServiceendpointPermissions("example-permissions",
-            project_id=example_project.id,
-            principal=example_readers.id,
-            serviceendpoint_id=example_service_endpoint_docker_registry.id,
+        example_root_permissions = azuredevops.AreaPermissions("example-root-permissions",
+            project_id=example.id,
+            principal=example_project_readers.id,
+            path="/",
             permissions={
-                "Use": "allow",
-                "Administer": "deny",
-                "Create": "deny",
-                "ViewAuthorization": "allow",
-                "ViewEndpoint": "allow",
+                "CREATE_CHILDREN": "Deny",
+                "GENERIC_READ": "Allow",
+                "DELETE": "Deny",
+                "WORK_ITEM_READ": "Allow",
             })
         ```
         ## Relevant Links
 
         * [Azure DevOps Service REST API 6.0 - Security](https://docs.microsoft.com/en-us/rest/api/azure/devops/security/?view=azure-devops-rest-6.0)
 
         ## PAT Permissions Required
@@ -257,76 +283,69 @@
 
         ## Import
 
         The resource does not support import.
 
         :param str resource_name: The name of the resource.
         :param pulumi.ResourceOptions opts: Options for the resource.
+        :param pulumi.Input[str] path: The name of the branch to assign the permissions.
         :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available.
         :param pulumi.Input[str] principal: The **group** principal to assign the permissions.
-        :param pulumi.Input[str] project_id: The ID of the project.
-        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
-        :param pulumi.Input[str] serviceendpoint_id: The id of the service endpoint to assign the permissions.
+        :param pulumi.Input[str] project_id: The ID of the project to assign the permissions.
+        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`.
+               
+               | Permission         | Description                    |
+               |--------------------|--------------------------------|
+               | GENERIC_READ       | View permissions for this node |
+               | GENERIC_WRITE      | Edit this node                 |
+               | CREATE_CHILDREN    | Create child nodes             |
+               | DELETE             | Delete this node               |
+               | WORK_ITEM_READ     | View work items in this node   |
+               | WORK_ITEM_WRITE    | Edit work items in this node   |
+               | MANAGE_TEST_PLANS  | Manage test plans              |
+               | MANAGE_TEST_SUITES | Manage test suites             |
         """
         ...
     @overload
     def __init__(__self__,
                  resource_name: str,
-                 args: ServiceendpointPermissionsArgs,
+                 args: AreaPermissionsArgs,
                  opts: Optional[pulumi.ResourceOptions] = None):
         """
-        Manages permissions for a Service Endpoint
+        Manages permissions for an Area (Component)
 
         > **Note** Permissions can be assigned to group principals and not to single user principals.
 
         ## Permission levels
 
-        Permission for Service Endpoints within Azure DevOps can be applied on two different levels.
-        Those levels are reflected by specifying (or omitting) values for the arguments `project_id` and `serviceendpoint_id`.
+        Permission for Areas within Azure DevOps can be applied on two different levels.
+        Those levels are reflected by specifying (or omitting) values for the arguments `project_id` and `path`.
 
         ## Example Usage
 
         ```python
         import pulumi
         import pulumi_azuredevops as azuredevops
 
-        example_project = azuredevops.Project("exampleProject",
+        example = azuredevops.Project("example",
             work_item_template="Agile",
             version_control="Git",
             visibility="private",
             description="Managed by Terraform")
-        example_readers = azuredevops.get_group_output(project_id=example_project.id,
+        example_project_readers = azuredevops.get_group_output(project_id=example.id,
             name="Readers")
-        example_root_permissions = azuredevops.ServiceendpointPermissions("example-root-permissions",
-            project_id=example_project.id,
-            principal=example_readers.id,
-            permissions={
-                "Use": "allow",
-                "Administer": "allow",
-                "Create": "allow",
-                "ViewAuthorization": "allow",
-                "ViewEndpoint": "allow",
-            })
-        example_service_endpoint_docker_registry = azuredevops.ServiceEndpointDockerRegistry("exampleServiceEndpointDockerRegistry",
-            project_id=example_project.id,
-            service_endpoint_name="Example Docker Hub",
-            docker_username="username",
-            docker_email="email@example.com",
-            docker_password="password",
-            registry_type="DockerHub")
-        example_permissions = azuredevops.ServiceendpointPermissions("example-permissions",
-            project_id=example_project.id,
-            principal=example_readers.id,
-            serviceendpoint_id=example_service_endpoint_docker_registry.id,
+        example_root_permissions = azuredevops.AreaPermissions("example-root-permissions",
+            project_id=example.id,
+            principal=example_project_readers.id,
+            path="/",
             permissions={
-                "Use": "allow",
-                "Administer": "deny",
-                "Create": "deny",
-                "ViewAuthorization": "allow",
-                "ViewEndpoint": "allow",
+                "CREATE_CHILDREN": "Deny",
+                "GENERIC_READ": "Allow",
+                "DELETE": "Deny",
+                "WORK_ITEM_READ": "Allow",
             })
         ```
         ## Relevant Links
 
         * [Azure DevOps Service REST API 6.0 - Security](https://docs.microsoft.com/en-us/rest/api/azure/devops/security/?view=azure-devops-rest-6.0)
 
         ## PAT Permissions Required
@@ -334,91 +353,110 @@
         - **Project & Team**: vso.security_manage - Grants the ability to read, write, and manage security permissions.
 
         ## Import
 
         The resource does not support import.
 
         :param str resource_name: The name of the resource.
-        :param ServiceendpointPermissionsArgs args: The arguments to use to populate this resource's properties.
+        :param AreaPermissionsArgs args: The arguments to use to populate this resource's properties.
         :param pulumi.ResourceOptions opts: Options for the resource.
         """
         ...
     def __init__(__self__, resource_name: str, *args, **kwargs):
-        resource_args, opts = _utilities.get_resource_args_opts(ServiceendpointPermissionsArgs, pulumi.ResourceOptions, *args, **kwargs)
+        resource_args, opts = _utilities.get_resource_args_opts(AreaPermissionsArgs, pulumi.ResourceOptions, *args, **kwargs)
         if resource_args is not None:
             __self__._internal_init(resource_name, opts, **resource_args.__dict__)
         else:
             __self__._internal_init(resource_name, *args, **kwargs)
 
     def _internal_init(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
+                 path: Optional[pulumi.Input[str]] = None,
                  permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
                  principal: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  replace: Optional[pulumi.Input[bool]] = None,
-                 serviceendpoint_id: Optional[pulumi.Input[str]] = None,
                  __props__=None):
         opts = pulumi.ResourceOptions.merge(_utilities.get_resource_opts_defaults(), opts)
         if not isinstance(opts, pulumi.ResourceOptions):
             raise TypeError('Expected resource options to be a ResourceOptions instance')
         if opts.id is None:
             if __props__ is not None:
                 raise TypeError('__props__ is only valid when passed in combination with a valid opts.id to get an existing resource')
-            __props__ = ServiceendpointPermissionsArgs.__new__(ServiceendpointPermissionsArgs)
+            __props__ = AreaPermissionsArgs.__new__(AreaPermissionsArgs)
 
+            __props__.__dict__["path"] = path
             if permissions is None and not opts.urn:
                 raise TypeError("Missing required property 'permissions'")
             __props__.__dict__["permissions"] = permissions
             if principal is None and not opts.urn:
                 raise TypeError("Missing required property 'principal'")
             __props__.__dict__["principal"] = principal
             if project_id is None and not opts.urn:
                 raise TypeError("Missing required property 'project_id'")
             __props__.__dict__["project_id"] = project_id
             __props__.__dict__["replace"] = replace
-            __props__.__dict__["serviceendpoint_id"] = serviceendpoint_id
-        super(ServiceendpointPermissions, __self__).__init__(
-            'azuredevops:index/serviceendpointPermissions:ServiceendpointPermissions',
+        super(AreaPermissions, __self__).__init__(
+            'azuredevops:index/areaPermissions:AreaPermissions',
             resource_name,
             __props__,
             opts)
 
     @staticmethod
     def get(resource_name: str,
             id: pulumi.Input[str],
             opts: Optional[pulumi.ResourceOptions] = None,
+            path: Optional[pulumi.Input[str]] = None,
             permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
             principal: Optional[pulumi.Input[str]] = None,
             project_id: Optional[pulumi.Input[str]] = None,
-            replace: Optional[pulumi.Input[bool]] = None,
-            serviceendpoint_id: Optional[pulumi.Input[str]] = None) -> 'ServiceendpointPermissions':
+            replace: Optional[pulumi.Input[bool]] = None) -> 'AreaPermissions':
         """
-        Get an existing ServiceendpointPermissions resource's state with the given name, id, and optional extra
+        Get an existing AreaPermissions resource's state with the given name, id, and optional extra
         properties used to qualify the lookup.
 
         :param str resource_name: The unique name of the resulting resource.
         :param pulumi.Input[str] id: The unique provider ID of the resource to lookup.
         :param pulumi.ResourceOptions opts: Options for the resource.
+        :param pulumi.Input[str] path: The name of the branch to assign the permissions.
         :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available.
         :param pulumi.Input[str] principal: The **group** principal to assign the permissions.
-        :param pulumi.Input[str] project_id: The ID of the project.
-        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
-        :param pulumi.Input[str] serviceendpoint_id: The id of the service endpoint to assign the permissions.
+        :param pulumi.Input[str] project_id: The ID of the project to assign the permissions.
+        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`.
+               
+               | Permission         | Description                    |
+               |--------------------|--------------------------------|
+               | GENERIC_READ       | View permissions for this node |
+               | GENERIC_WRITE      | Edit this node                 |
+               | CREATE_CHILDREN    | Create child nodes             |
+               | DELETE             | Delete this node               |
+               | WORK_ITEM_READ     | View work items in this node   |
+               | WORK_ITEM_WRITE    | Edit work items in this node   |
+               | MANAGE_TEST_PLANS  | Manage test plans              |
+               | MANAGE_TEST_SUITES | Manage test suites             |
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
 
-        __props__ = _ServiceendpointPermissionsState.__new__(_ServiceendpointPermissionsState)
+        __props__ = _AreaPermissionsState.__new__(_AreaPermissionsState)
 
+        __props__.__dict__["path"] = path
         __props__.__dict__["permissions"] = permissions
         __props__.__dict__["principal"] = principal
         __props__.__dict__["project_id"] = project_id
         __props__.__dict__["replace"] = replace
-        __props__.__dict__["serviceendpoint_id"] = serviceendpoint_id
-        return ServiceendpointPermissions(resource_name, opts=opts, __props__=__props__)
+        return AreaPermissions(resource_name, opts=opts, __props__=__props__)
+
+    @property
+    @pulumi.getter
+    def path(self) -> pulumi.Output[Optional[str]]:
+        """
+        The name of the branch to assign the permissions.
+        """
+        return pulumi.get(self, "path")
 
     @property
     @pulumi.getter
     def permissions(self) -> pulumi.Output[Mapping[str, str]]:
         """
         the permissions to assign. The following permissions are available.
         """
@@ -432,27 +470,30 @@
         """
         return pulumi.get(self, "principal")
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> pulumi.Output[str]:
         """
-        The ID of the project.
+        The ID of the project to assign the permissions.
         """
         return pulumi.get(self, "project_id")
 
     @property
     @pulumi.getter
     def replace(self) -> pulumi.Output[Optional[bool]]:
         """
-        Replace (`true`) or merge (`false`) the permissions. Default: `true`
-        """
-        return pulumi.get(self, "replace")
+        Replace (`true`) or merge (`false`) the permissions. Default: `true`.
 
-    @property
-    @pulumi.getter(name="serviceendpointId")
-    def serviceendpoint_id(self) -> pulumi.Output[Optional[str]]:
+        | Permission         | Description                    |
+        |--------------------|--------------------------------|
+        | GENERIC_READ       | View permissions for this node |
+        | GENERIC_WRITE      | Edit this node                 |
+        | CREATE_CHILDREN    | Create child nodes             |
+        | DELETE             | Delete this node               |
+        | WORK_ITEM_READ     | View work items in this node   |
+        | WORK_ITEM_WRITE    | Edit work items in this node   |
+        | MANAGE_TEST_PLANS  | Manage test plans              |
+        | MANAGE_TEST_SUITES | Manage test suites             |
         """
-        The id of the service endpoint to assign the permissions.
-        """
-        return pulumi.get(self, "serviceendpoint_id")
+        return pulumi.get(self, "replace")
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/tagging_permissions.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/team_members.py`

 * *Files 25% similar despite different names*

```diff
@@ -5,364 +5,398 @@
 import copy
 import warnings
 import pulumi
 import pulumi.runtime
 from typing import Any, Mapping, Optional, Sequence, Union, overload
 from . import _utilities
 
-__all__ = ['TaggingPermissionsArgs', 'TaggingPermissions']
+__all__ = ['TeamMembersArgs', 'TeamMembers']
 
 @pulumi.input_type
-class TaggingPermissionsArgs:
+class TeamMembersArgs:
     def __init__(__self__, *,
-                 permissions: pulumi.Input[Mapping[str, pulumi.Input[str]]],
-                 principal: pulumi.Input[str],
-                 project_id: Optional[pulumi.Input[str]] = None,
-                 replace: Optional[pulumi.Input[bool]] = None):
-        """
-        The set of arguments for constructing a TaggingPermissions resource.
-        :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available.
-        :param pulumi.Input[str] principal: The **group or user** principal to assign the permissions.
-        :param pulumi.Input[str] project_id: The ID of the project to assign the permissions. If omitted, organization wide permissions for tagging are managed.
-        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
-        """
-        pulumi.set(__self__, "permissions", permissions)
-        pulumi.set(__self__, "principal", principal)
-        if project_id is not None:
-            pulumi.set(__self__, "project_id", project_id)
-        if replace is not None:
-            pulumi.set(__self__, "replace", replace)
+                 members: pulumi.Input[Sequence[pulumi.Input[str]]],
+                 project_id: pulumi.Input[str],
+                 team_id: pulumi.Input[str],
+                 mode: Optional[pulumi.Input[str]] = None):
+        """
+        The set of arguments for constructing a TeamMembers resource.
+        :param pulumi.Input[Sequence[pulumi.Input[str]]] members: List of subject descriptors to define members of the team.
+               
+               > NOTE: It's possible to define team members both within the
+               > `Team` resource via the `members` block and by using the
+               > `TeamMembers` resource. However it's not possible to use
+               > both methods to manage team members, since there'll be conflicts.
+        :param pulumi.Input[str] project_id: The Project ID.
+        :param pulumi.Input[str] team_id: The ID of the Team.
+        :param pulumi.Input[str] mode: The mode how the resource manages team members.
+               - `mode == add`: the resource will ensure that all specified members will be part of the referenced team
+               - `mode == overwrite`: the resource will replace all existing members with the members specified within the `members` block
+        """
+        pulumi.set(__self__, "members", members)
+        pulumi.set(__self__, "project_id", project_id)
+        pulumi.set(__self__, "team_id", team_id)
+        if mode is not None:
+            pulumi.set(__self__, "mode", mode)
 
     @property
     @pulumi.getter
-    def permissions(self) -> pulumi.Input[Mapping[str, pulumi.Input[str]]]:
-        """
-        the permissions to assign. The following permissions are available.
+    def members(self) -> pulumi.Input[Sequence[pulumi.Input[str]]]:
         """
-        return pulumi.get(self, "permissions")
-
-    @permissions.setter
-    def permissions(self, value: pulumi.Input[Mapping[str, pulumi.Input[str]]]):
-        pulumi.set(self, "permissions", value)
+        List of subject descriptors to define members of the team.
 
-    @property
-    @pulumi.getter
-    def principal(self) -> pulumi.Input[str]:
-        """
-        The **group or user** principal to assign the permissions.
+        > NOTE: It's possible to define team members both within the
+        > `Team` resource via the `members` block and by using the
+        > `TeamMembers` resource. However it's not possible to use
+        > both methods to manage team members, since there'll be conflicts.
         """
-        return pulumi.get(self, "principal")
+        return pulumi.get(self, "members")
 
-    @principal.setter
-    def principal(self, value: pulumi.Input[str]):
-        pulumi.set(self, "principal", value)
+    @members.setter
+    def members(self, value: pulumi.Input[Sequence[pulumi.Input[str]]]):
+        pulumi.set(self, "members", value)
 
     @property
     @pulumi.getter(name="projectId")
-    def project_id(self) -> Optional[pulumi.Input[str]]:
+    def project_id(self) -> pulumi.Input[str]:
         """
-        The ID of the project to assign the permissions. If omitted, organization wide permissions for tagging are managed.
+        The Project ID.
         """
         return pulumi.get(self, "project_id")
 
     @project_id.setter
-    def project_id(self, value: Optional[pulumi.Input[str]]):
+    def project_id(self, value: pulumi.Input[str]):
         pulumi.set(self, "project_id", value)
 
     @property
+    @pulumi.getter(name="teamId")
+    def team_id(self) -> pulumi.Input[str]:
+        """
+        The ID of the Team.
+        """
+        return pulumi.get(self, "team_id")
+
+    @team_id.setter
+    def team_id(self, value: pulumi.Input[str]):
+        pulumi.set(self, "team_id", value)
+
+    @property
     @pulumi.getter
-    def replace(self) -> Optional[pulumi.Input[bool]]:
+    def mode(self) -> Optional[pulumi.Input[str]]:
         """
-        Replace (`true`) or merge (`false`) the permissions. Default: `true`
+        The mode how the resource manages team members.
+        - `mode == add`: the resource will ensure that all specified members will be part of the referenced team
+        - `mode == overwrite`: the resource will replace all existing members with the members specified within the `members` block
         """
-        return pulumi.get(self, "replace")
+        return pulumi.get(self, "mode")
 
-    @replace.setter
-    def replace(self, value: Optional[pulumi.Input[bool]]):
-        pulumi.set(self, "replace", value)
+    @mode.setter
+    def mode(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "mode", value)
 
 
 @pulumi.input_type
-class _TaggingPermissionsState:
+class _TeamMembersState:
     def __init__(__self__, *,
-                 permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
-                 principal: Optional[pulumi.Input[str]] = None,
+                 members: Optional[pulumi.Input[Sequence[pulumi.Input[str]]]] = None,
+                 mode: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
-                 replace: Optional[pulumi.Input[bool]] = None):
+                 team_id: Optional[pulumi.Input[str]] = None):
         """
-        Input properties used for looking up and filtering TaggingPermissions resources.
-        :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available.
-        :param pulumi.Input[str] principal: The **group or user** principal to assign the permissions.
-        :param pulumi.Input[str] project_id: The ID of the project to assign the permissions. If omitted, organization wide permissions for tagging are managed.
-        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
-        """
-        if permissions is not None:
-            pulumi.set(__self__, "permissions", permissions)
-        if principal is not None:
-            pulumi.set(__self__, "principal", principal)
+        Input properties used for looking up and filtering TeamMembers resources.
+        :param pulumi.Input[Sequence[pulumi.Input[str]]] members: List of subject descriptors to define members of the team.
+               
+               > NOTE: It's possible to define team members both within the
+               > `Team` resource via the `members` block and by using the
+               > `TeamMembers` resource. However it's not possible to use
+               > both methods to manage team members, since there'll be conflicts.
+        :param pulumi.Input[str] mode: The mode how the resource manages team members.
+               - `mode == add`: the resource will ensure that all specified members will be part of the referenced team
+               - `mode == overwrite`: the resource will replace all existing members with the members specified within the `members` block
+        :param pulumi.Input[str] project_id: The Project ID.
+        :param pulumi.Input[str] team_id: The ID of the Team.
+        """
+        if members is not None:
+            pulumi.set(__self__, "members", members)
+        if mode is not None:
+            pulumi.set(__self__, "mode", mode)
         if project_id is not None:
             pulumi.set(__self__, "project_id", project_id)
-        if replace is not None:
-            pulumi.set(__self__, "replace", replace)
+        if team_id is not None:
+            pulumi.set(__self__, "team_id", team_id)
 
     @property
     @pulumi.getter
-    def permissions(self) -> Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]:
+    def members(self) -> Optional[pulumi.Input[Sequence[pulumi.Input[str]]]]:
         """
-        the permissions to assign. The following permissions are available.
+        List of subject descriptors to define members of the team.
+
+        > NOTE: It's possible to define team members both within the
+        > `Team` resource via the `members` block and by using the
+        > `TeamMembers` resource. However it's not possible to use
+        > both methods to manage team members, since there'll be conflicts.
         """
-        return pulumi.get(self, "permissions")
+        return pulumi.get(self, "members")
 
-    @permissions.setter
-    def permissions(self, value: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]):
-        pulumi.set(self, "permissions", value)
+    @members.setter
+    def members(self, value: Optional[pulumi.Input[Sequence[pulumi.Input[str]]]]):
+        pulumi.set(self, "members", value)
 
     @property
     @pulumi.getter
-    def principal(self) -> Optional[pulumi.Input[str]]:
+    def mode(self) -> Optional[pulumi.Input[str]]:
         """
-        The **group or user** principal to assign the permissions.
+        The mode how the resource manages team members.
+        - `mode == add`: the resource will ensure that all specified members will be part of the referenced team
+        - `mode == overwrite`: the resource will replace all existing members with the members specified within the `members` block
         """
-        return pulumi.get(self, "principal")
+        return pulumi.get(self, "mode")
 
-    @principal.setter
-    def principal(self, value: Optional[pulumi.Input[str]]):
-        pulumi.set(self, "principal", value)
+    @mode.setter
+    def mode(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "mode", value)
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> Optional[pulumi.Input[str]]:
         """
-        The ID of the project to assign the permissions. If omitted, organization wide permissions for tagging are managed.
+        The Project ID.
         """
         return pulumi.get(self, "project_id")
 
     @project_id.setter
     def project_id(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "project_id", value)
 
     @property
-    @pulumi.getter
-    def replace(self) -> Optional[pulumi.Input[bool]]:
+    @pulumi.getter(name="teamId")
+    def team_id(self) -> Optional[pulumi.Input[str]]:
         """
-        Replace (`true`) or merge (`false`) the permissions. Default: `true`
+        The ID of the Team.
         """
-        return pulumi.get(self, "replace")
+        return pulumi.get(self, "team_id")
 
-    @replace.setter
-    def replace(self, value: Optional[pulumi.Input[bool]]):
-        pulumi.set(self, "replace", value)
+    @team_id.setter
+    def team_id(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "team_id", value)
 
 
-class TaggingPermissions(pulumi.CustomResource):
+class TeamMembers(pulumi.CustomResource):
     @overload
     def __init__(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
-                 permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
-                 principal: Optional[pulumi.Input[str]] = None,
+                 members: Optional[pulumi.Input[Sequence[pulumi.Input[str]]]] = None,
+                 mode: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
-                 replace: Optional[pulumi.Input[bool]] = None,
+                 team_id: Optional[pulumi.Input[str]] = None,
                  __props__=None):
         """
-        Manages permissions for tagging
-
-        ## Permission levels
-
-        Permissions for tagging within Azure DevOps can be applied only on Organizational and Project level.
-        The project level is reflected by specifying the argument `project_id`, otherwise the permissions are set on the organizational level.
+        Manages members of a team within a project in a Azure DevOps organization.
 
         ## Example Usage
 
         ```python
         import pulumi
         import pulumi_azuredevops as azuredevops
 
-        example = azuredevops.Project("example",
+        example_project = azuredevops.Project("exampleProject",
             work_item_template="Agile",
             version_control="Git",
             visibility="private",
             description="Managed by Terraform")
-        example_readers = azuredevops.get_group_output(project_id=example.id,
+        example_project_readers = azuredevops.get_group_output(project_id=example_project.id,
             name="Readers")
-        example_permissions = azuredevops.TaggingPermissions("example-permissions",
-            project_id=example.id,
-            principal=example_readers.id,
-            permissions={
-                "Enumerate": "allow",
-                "Create": "allow",
-                "Update": "allow",
-                "Delete": "allow",
-            })
+        example_team = azuredevops.Team("exampleTeam", project_id=example_project.id)
+        example_team_members = azuredevops.TeamMembers("example-team-members",
+            project_id=example_team.project_id,
+            team_id=example_team.id,
+            mode="overwrite",
+            members=[example_project_readers.descriptor])
         ```
         ## Relevant Links
 
-        * [Azure DevOps Service REST API 6.0 - Security](https://docs.microsoft.com/en-us/rest/api/azure/devops/security/?view=azure-devops-rest-6.0)
+        - [Azure DevOps Service REST API 6.0 - Teams - Update](https://docs.microsoft.com/en-us/rest/api/azure/devops/core/teams/update?view=azure-devops-rest-6.0)
 
         ## PAT Permissions Required
 
-        - **Project & Team**: vso.security_manage - Grants the ability to read, write, and manage security permissions.
+        - **vso.project_write**:	Grants the ability to read and update projects and teams.
 
         ## Import
 
         The resource does not support import.
 
         :param str resource_name: The name of the resource.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available.
-        :param pulumi.Input[str] principal: The **group or user** principal to assign the permissions.
-        :param pulumi.Input[str] project_id: The ID of the project to assign the permissions. If omitted, organization wide permissions for tagging are managed.
-        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
+        :param pulumi.Input[Sequence[pulumi.Input[str]]] members: List of subject descriptors to define members of the team.
+               
+               > NOTE: It's possible to define team members both within the
+               > `Team` resource via the `members` block and by using the
+               > `TeamMembers` resource. However it's not possible to use
+               > both methods to manage team members, since there'll be conflicts.
+        :param pulumi.Input[str] mode: The mode how the resource manages team members.
+               - `mode == add`: the resource will ensure that all specified members will be part of the referenced team
+               - `mode == overwrite`: the resource will replace all existing members with the members specified within the `members` block
+        :param pulumi.Input[str] project_id: The Project ID.
+        :param pulumi.Input[str] team_id: The ID of the Team.
         """
         ...
     @overload
     def __init__(__self__,
                  resource_name: str,
-                 args: TaggingPermissionsArgs,
+                 args: TeamMembersArgs,
                  opts: Optional[pulumi.ResourceOptions] = None):
         """
-        Manages permissions for tagging
-
-        ## Permission levels
-
-        Permissions for tagging within Azure DevOps can be applied only on Organizational and Project level.
-        The project level is reflected by specifying the argument `project_id`, otherwise the permissions are set on the organizational level.
+        Manages members of a team within a project in a Azure DevOps organization.
 
         ## Example Usage
 
         ```python
         import pulumi
         import pulumi_azuredevops as azuredevops
 
-        example = azuredevops.Project("example",
+        example_project = azuredevops.Project("exampleProject",
             work_item_template="Agile",
             version_control="Git",
             visibility="private",
             description="Managed by Terraform")
-        example_readers = azuredevops.get_group_output(project_id=example.id,
+        example_project_readers = azuredevops.get_group_output(project_id=example_project.id,
             name="Readers")
-        example_permissions = azuredevops.TaggingPermissions("example-permissions",
-            project_id=example.id,
-            principal=example_readers.id,
-            permissions={
-                "Enumerate": "allow",
-                "Create": "allow",
-                "Update": "allow",
-                "Delete": "allow",
-            })
+        example_team = azuredevops.Team("exampleTeam", project_id=example_project.id)
+        example_team_members = azuredevops.TeamMembers("example-team-members",
+            project_id=example_team.project_id,
+            team_id=example_team.id,
+            mode="overwrite",
+            members=[example_project_readers.descriptor])
         ```
         ## Relevant Links
 
-        * [Azure DevOps Service REST API 6.0 - Security](https://docs.microsoft.com/en-us/rest/api/azure/devops/security/?view=azure-devops-rest-6.0)
+        - [Azure DevOps Service REST API 6.0 - Teams - Update](https://docs.microsoft.com/en-us/rest/api/azure/devops/core/teams/update?view=azure-devops-rest-6.0)
 
         ## PAT Permissions Required
 
-        - **Project & Team**: vso.security_manage - Grants the ability to read, write, and manage security permissions.
+        - **vso.project_write**:	Grants the ability to read and update projects and teams.
 
         ## Import
 
         The resource does not support import.
 
         :param str resource_name: The name of the resource.
-        :param TaggingPermissionsArgs args: The arguments to use to populate this resource's properties.
+        :param TeamMembersArgs args: The arguments to use to populate this resource's properties.
         :param pulumi.ResourceOptions opts: Options for the resource.
         """
         ...
     def __init__(__self__, resource_name: str, *args, **kwargs):
-        resource_args, opts = _utilities.get_resource_args_opts(TaggingPermissionsArgs, pulumi.ResourceOptions, *args, **kwargs)
+        resource_args, opts = _utilities.get_resource_args_opts(TeamMembersArgs, pulumi.ResourceOptions, *args, **kwargs)
         if resource_args is not None:
             __self__._internal_init(resource_name, opts, **resource_args.__dict__)
         else:
             __self__._internal_init(resource_name, *args, **kwargs)
 
     def _internal_init(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
-                 permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
-                 principal: Optional[pulumi.Input[str]] = None,
+                 members: Optional[pulumi.Input[Sequence[pulumi.Input[str]]]] = None,
+                 mode: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
-                 replace: Optional[pulumi.Input[bool]] = None,
+                 team_id: Optional[pulumi.Input[str]] = None,
                  __props__=None):
         opts = pulumi.ResourceOptions.merge(_utilities.get_resource_opts_defaults(), opts)
         if not isinstance(opts, pulumi.ResourceOptions):
             raise TypeError('Expected resource options to be a ResourceOptions instance')
         if opts.id is None:
             if __props__ is not None:
                 raise TypeError('__props__ is only valid when passed in combination with a valid opts.id to get an existing resource')
-            __props__ = TaggingPermissionsArgs.__new__(TaggingPermissionsArgs)
+            __props__ = TeamMembersArgs.__new__(TeamMembersArgs)
 
-            if permissions is None and not opts.urn:
-                raise TypeError("Missing required property 'permissions'")
-            __props__.__dict__["permissions"] = permissions
-            if principal is None and not opts.urn:
-                raise TypeError("Missing required property 'principal'")
-            __props__.__dict__["principal"] = principal
+            if members is None and not opts.urn:
+                raise TypeError("Missing required property 'members'")
+            __props__.__dict__["members"] = members
+            __props__.__dict__["mode"] = mode
+            if project_id is None and not opts.urn:
+                raise TypeError("Missing required property 'project_id'")
             __props__.__dict__["project_id"] = project_id
-            __props__.__dict__["replace"] = replace
-        super(TaggingPermissions, __self__).__init__(
-            'azuredevops:index/taggingPermissions:TaggingPermissions',
+            if team_id is None and not opts.urn:
+                raise TypeError("Missing required property 'team_id'")
+            __props__.__dict__["team_id"] = team_id
+        super(TeamMembers, __self__).__init__(
+            'azuredevops:index/teamMembers:TeamMembers',
             resource_name,
             __props__,
             opts)
 
     @staticmethod
     def get(resource_name: str,
             id: pulumi.Input[str],
             opts: Optional[pulumi.ResourceOptions] = None,
-            permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
-            principal: Optional[pulumi.Input[str]] = None,
+            members: Optional[pulumi.Input[Sequence[pulumi.Input[str]]]] = None,
+            mode: Optional[pulumi.Input[str]] = None,
             project_id: Optional[pulumi.Input[str]] = None,
-            replace: Optional[pulumi.Input[bool]] = None) -> 'TaggingPermissions':
+            team_id: Optional[pulumi.Input[str]] = None) -> 'TeamMembers':
         """
-        Get an existing TaggingPermissions resource's state with the given name, id, and optional extra
+        Get an existing TeamMembers resource's state with the given name, id, and optional extra
         properties used to qualify the lookup.
 
         :param str resource_name: The unique name of the resulting resource.
         :param pulumi.Input[str] id: The unique provider ID of the resource to lookup.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available.
-        :param pulumi.Input[str] principal: The **group or user** principal to assign the permissions.
-        :param pulumi.Input[str] project_id: The ID of the project to assign the permissions. If omitted, organization wide permissions for tagging are managed.
-        :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
+        :param pulumi.Input[Sequence[pulumi.Input[str]]] members: List of subject descriptors to define members of the team.
+               
+               > NOTE: It's possible to define team members both within the
+               > `Team` resource via the `members` block and by using the
+               > `TeamMembers` resource. However it's not possible to use
+               > both methods to manage team members, since there'll be conflicts.
+        :param pulumi.Input[str] mode: The mode how the resource manages team members.
+               - `mode == add`: the resource will ensure that all specified members will be part of the referenced team
+               - `mode == overwrite`: the resource will replace all existing members with the members specified within the `members` block
+        :param pulumi.Input[str] project_id: The Project ID.
+        :param pulumi.Input[str] team_id: The ID of the Team.
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
 
-        __props__ = _TaggingPermissionsState.__new__(_TaggingPermissionsState)
+        __props__ = _TeamMembersState.__new__(_TeamMembersState)
 
-        __props__.__dict__["permissions"] = permissions
-        __props__.__dict__["principal"] = principal
+        __props__.__dict__["members"] = members
+        __props__.__dict__["mode"] = mode
         __props__.__dict__["project_id"] = project_id
-        __props__.__dict__["replace"] = replace
-        return TaggingPermissions(resource_name, opts=opts, __props__=__props__)
+        __props__.__dict__["team_id"] = team_id
+        return TeamMembers(resource_name, opts=opts, __props__=__props__)
 
     @property
     @pulumi.getter
-    def permissions(self) -> pulumi.Output[Mapping[str, str]]:
+    def members(self) -> pulumi.Output[Sequence[str]]:
         """
-        the permissions to assign. The following permissions are available.
+        List of subject descriptors to define members of the team.
+
+        > NOTE: It's possible to define team members both within the
+        > `Team` resource via the `members` block and by using the
+        > `TeamMembers` resource. However it's not possible to use
+        > both methods to manage team members, since there'll be conflicts.
         """
-        return pulumi.get(self, "permissions")
+        return pulumi.get(self, "members")
 
     @property
     @pulumi.getter
-    def principal(self) -> pulumi.Output[str]:
+    def mode(self) -> pulumi.Output[Optional[str]]:
         """
-        The **group or user** principal to assign the permissions.
+        The mode how the resource manages team members.
+        - `mode == add`: the resource will ensure that all specified members will be part of the referenced team
+        - `mode == overwrite`: the resource will replace all existing members with the members specified within the `members` block
         """
-        return pulumi.get(self, "principal")
+        return pulumi.get(self, "mode")
 
     @property
     @pulumi.getter(name="projectId")
-    def project_id(self) -> pulumi.Output[Optional[str]]:
+    def project_id(self) -> pulumi.Output[str]:
         """
-        The ID of the project to assign the permissions. If omitted, organization wide permissions for tagging are managed.
+        The Project ID.
         """
         return pulumi.get(self, "project_id")
 
     @property
-    @pulumi.getter
-    def replace(self) -> pulumi.Output[Optional[bool]]:
+    @pulumi.getter(name="teamId")
+    def team_id(self) -> pulumi.Output[str]:
         """
-        Replace (`true`) or merge (`false`) the permissions. Default: `true`
+        The ID of the Team.
         """
-        return pulumi.get(self, "replace")
+        return pulumi.get(self, "team_id")
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/team.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/team_administrators.py`

 * *Files 20% similar despite different names*

```diff
@@ -5,430 +5,398 @@
 import copy
 import warnings
 import pulumi
 import pulumi.runtime
 from typing import Any, Mapping, Optional, Sequence, Union, overload
 from . import _utilities
 
-__all__ = ['TeamArgs', 'Team']
+__all__ = ['TeamAdministratorsArgs', 'TeamAdministrators']
 
 @pulumi.input_type
-class TeamArgs:
+class TeamAdministratorsArgs:
     def __init__(__self__, *,
+                 administrators: pulumi.Input[Sequence[pulumi.Input[str]]],
                  project_id: pulumi.Input[str],
-                 administrators: Optional[pulumi.Input[Sequence[pulumi.Input[str]]]] = None,
-                 description: Optional[pulumi.Input[str]] = None,
-                 members: Optional[pulumi.Input[Sequence[pulumi.Input[str]]]] = None,
-                 name: Optional[pulumi.Input[str]] = None):
+                 team_id: pulumi.Input[str],
+                 mode: Optional[pulumi.Input[str]] = None):
         """
-        The set of arguments for constructing a Team resource.
+        The set of arguments for constructing a TeamAdministrators resource.
+        :param pulumi.Input[Sequence[pulumi.Input[str]]] administrators: List of subject descriptors to define adminitrators of the team.
+               
+               > NOTE: It's possible to define team administrators both within the
+               > `Team` resource via the `administrators` block and by using the
+               > `TeamAdministrators` resource. However it's not possible to use
+               > both methods to manage team administrators, since there'll be conflicts.
         :param pulumi.Input[str] project_id: The Project ID.
-        :param pulumi.Input[Sequence[pulumi.Input[str]]] administrators: List of subject descriptors to define administrators of the team.
-        :param pulumi.Input[str] description: The description of the Team.
-        :param pulumi.Input[Sequence[pulumi.Input[str]]] members: List of subject descriptors to define members of the team.
-        :param pulumi.Input[str] name: The name of the Team.
+        :param pulumi.Input[str] team_id: The ID of the Team.
+        :param pulumi.Input[str] mode: The mode how the resource manages team administrators.
+               - `mode == add`: the resource will ensure that all specified administrators will be part of the referenced team
+               - `mode == overwrite`: the resource will replace all existing administrators with the administrators specified within the `administrators` block
         """
+        pulumi.set(__self__, "administrators", administrators)
         pulumi.set(__self__, "project_id", project_id)
-        if administrators is not None:
-            pulumi.set(__self__, "administrators", administrators)
-        if description is not None:
-            pulumi.set(__self__, "description", description)
-        if members is not None:
-            pulumi.set(__self__, "members", members)
-        if name is not None:
-            pulumi.set(__self__, "name", name)
-
-    @property
-    @pulumi.getter(name="projectId")
-    def project_id(self) -> pulumi.Input[str]:
-        """
-        The Project ID.
-        """
-        return pulumi.get(self, "project_id")
-
-    @project_id.setter
-    def project_id(self, value: pulumi.Input[str]):
-        pulumi.set(self, "project_id", value)
+        pulumi.set(__self__, "team_id", team_id)
+        if mode is not None:
+            pulumi.set(__self__, "mode", mode)
 
     @property
     @pulumi.getter
-    def administrators(self) -> Optional[pulumi.Input[Sequence[pulumi.Input[str]]]]:
+    def administrators(self) -> pulumi.Input[Sequence[pulumi.Input[str]]]:
         """
-        List of subject descriptors to define administrators of the team.
+        List of subject descriptors to define adminitrators of the team.
+
+        > NOTE: It's possible to define team administrators both within the
+        > `Team` resource via the `administrators` block and by using the
+        > `TeamAdministrators` resource. However it's not possible to use
+        > both methods to manage team administrators, since there'll be conflicts.
         """
         return pulumi.get(self, "administrators")
 
     @administrators.setter
-    def administrators(self, value: Optional[pulumi.Input[Sequence[pulumi.Input[str]]]]):
+    def administrators(self, value: pulumi.Input[Sequence[pulumi.Input[str]]]):
         pulumi.set(self, "administrators", value)
 
     @property
-    @pulumi.getter
-    def description(self) -> Optional[pulumi.Input[str]]:
+    @pulumi.getter(name="projectId")
+    def project_id(self) -> pulumi.Input[str]:
         """
-        The description of the Team.
+        The Project ID.
         """
-        return pulumi.get(self, "description")
+        return pulumi.get(self, "project_id")
 
-    @description.setter
-    def description(self, value: Optional[pulumi.Input[str]]):
-        pulumi.set(self, "description", value)
+    @project_id.setter
+    def project_id(self, value: pulumi.Input[str]):
+        pulumi.set(self, "project_id", value)
 
     @property
-    @pulumi.getter
-    def members(self) -> Optional[pulumi.Input[Sequence[pulumi.Input[str]]]]:
+    @pulumi.getter(name="teamId")
+    def team_id(self) -> pulumi.Input[str]:
         """
-        List of subject descriptors to define members of the team.
+        The ID of the Team.
         """
-        return pulumi.get(self, "members")
+        return pulumi.get(self, "team_id")
 
-    @members.setter
-    def members(self, value: Optional[pulumi.Input[Sequence[pulumi.Input[str]]]]):
-        pulumi.set(self, "members", value)
+    @team_id.setter
+    def team_id(self, value: pulumi.Input[str]):
+        pulumi.set(self, "team_id", value)
 
     @property
     @pulumi.getter
-    def name(self) -> Optional[pulumi.Input[str]]:
+    def mode(self) -> Optional[pulumi.Input[str]]:
         """
-        The name of the Team.
+        The mode how the resource manages team administrators.
+        - `mode == add`: the resource will ensure that all specified administrators will be part of the referenced team
+        - `mode == overwrite`: the resource will replace all existing administrators with the administrators specified within the `administrators` block
         """
-        return pulumi.get(self, "name")
+        return pulumi.get(self, "mode")
 
-    @name.setter
-    def name(self, value: Optional[pulumi.Input[str]]):
-        pulumi.set(self, "name", value)
+    @mode.setter
+    def mode(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "mode", value)
 
 
 @pulumi.input_type
-class _TeamState:
+class _TeamAdministratorsState:
     def __init__(__self__, *,
                  administrators: Optional[pulumi.Input[Sequence[pulumi.Input[str]]]] = None,
-                 description: Optional[pulumi.Input[str]] = None,
-                 descriptor: Optional[pulumi.Input[str]] = None,
-                 members: Optional[pulumi.Input[Sequence[pulumi.Input[str]]]] = None,
-                 name: Optional[pulumi.Input[str]] = None,
-                 project_id: Optional[pulumi.Input[str]] = None):
-        """
-        Input properties used for looking up and filtering Team resources.
-        :param pulumi.Input[Sequence[pulumi.Input[str]]] administrators: List of subject descriptors to define administrators of the team.
-        :param pulumi.Input[str] description: The description of the Team.
-        :param pulumi.Input[str] descriptor: The descriptor of the Team.
-        :param pulumi.Input[Sequence[pulumi.Input[str]]] members: List of subject descriptors to define members of the team.
-        :param pulumi.Input[str] name: The name of the Team.
+                 mode: Optional[pulumi.Input[str]] = None,
+                 project_id: Optional[pulumi.Input[str]] = None,
+                 team_id: Optional[pulumi.Input[str]] = None):
+        """
+        Input properties used for looking up and filtering TeamAdministrators resources.
+        :param pulumi.Input[Sequence[pulumi.Input[str]]] administrators: List of subject descriptors to define adminitrators of the team.
+               
+               > NOTE: It's possible to define team administrators both within the
+               > `Team` resource via the `administrators` block and by using the
+               > `TeamAdministrators` resource. However it's not possible to use
+               > both methods to manage team administrators, since there'll be conflicts.
+        :param pulumi.Input[str] mode: The mode how the resource manages team administrators.
+               - `mode == add`: the resource will ensure that all specified administrators will be part of the referenced team
+               - `mode == overwrite`: the resource will replace all existing administrators with the administrators specified within the `administrators` block
         :param pulumi.Input[str] project_id: The Project ID.
+        :param pulumi.Input[str] team_id: The ID of the Team.
         """
         if administrators is not None:
             pulumi.set(__self__, "administrators", administrators)
-        if description is not None:
-            pulumi.set(__self__, "description", description)
-        if descriptor is not None:
-            pulumi.set(__self__, "descriptor", descriptor)
-        if members is not None:
-            pulumi.set(__self__, "members", members)
-        if name is not None:
-            pulumi.set(__self__, "name", name)
+        if mode is not None:
+            pulumi.set(__self__, "mode", mode)
         if project_id is not None:
             pulumi.set(__self__, "project_id", project_id)
+        if team_id is not None:
+            pulumi.set(__self__, "team_id", team_id)
 
     @property
     @pulumi.getter
     def administrators(self) -> Optional[pulumi.Input[Sequence[pulumi.Input[str]]]]:
         """
-        List of subject descriptors to define administrators of the team.
+        List of subject descriptors to define adminitrators of the team.
+
+        > NOTE: It's possible to define team administrators both within the
+        > `Team` resource via the `administrators` block and by using the
+        > `TeamAdministrators` resource. However it's not possible to use
+        > both methods to manage team administrators, since there'll be conflicts.
         """
         return pulumi.get(self, "administrators")
 
     @administrators.setter
     def administrators(self, value: Optional[pulumi.Input[Sequence[pulumi.Input[str]]]]):
         pulumi.set(self, "administrators", value)
 
     @property
     @pulumi.getter
-    def description(self) -> Optional[pulumi.Input[str]]:
+    def mode(self) -> Optional[pulumi.Input[str]]:
         """
-        The description of the Team.
+        The mode how the resource manages team administrators.
+        - `mode == add`: the resource will ensure that all specified administrators will be part of the referenced team
+        - `mode == overwrite`: the resource will replace all existing administrators with the administrators specified within the `administrators` block
         """
-        return pulumi.get(self, "description")
+        return pulumi.get(self, "mode")
 
-    @description.setter
-    def description(self, value: Optional[pulumi.Input[str]]):
-        pulumi.set(self, "description", value)
-
-    @property
-    @pulumi.getter
-    def descriptor(self) -> Optional[pulumi.Input[str]]:
-        """
-        The descriptor of the Team.
-        """
-        return pulumi.get(self, "descriptor")
-
-    @descriptor.setter
-    def descriptor(self, value: Optional[pulumi.Input[str]]):
-        pulumi.set(self, "descriptor", value)
-
-    @property
-    @pulumi.getter
-    def members(self) -> Optional[pulumi.Input[Sequence[pulumi.Input[str]]]]:
-        """
-        List of subject descriptors to define members of the team.
-        """
-        return pulumi.get(self, "members")
-
-    @members.setter
-    def members(self, value: Optional[pulumi.Input[Sequence[pulumi.Input[str]]]]):
-        pulumi.set(self, "members", value)
-
-    @property
-    @pulumi.getter
-    def name(self) -> Optional[pulumi.Input[str]]:
-        """
-        The name of the Team.
-        """
-        return pulumi.get(self, "name")
-
-    @name.setter
-    def name(self, value: Optional[pulumi.Input[str]]):
-        pulumi.set(self, "name", value)
+    @mode.setter
+    def mode(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "mode", value)
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> Optional[pulumi.Input[str]]:
         """
         The Project ID.
         """
         return pulumi.get(self, "project_id")
 
     @project_id.setter
     def project_id(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "project_id", value)
 
+    @property
+    @pulumi.getter(name="teamId")
+    def team_id(self) -> Optional[pulumi.Input[str]]:
+        """
+        The ID of the Team.
+        """
+        return pulumi.get(self, "team_id")
+
+    @team_id.setter
+    def team_id(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "team_id", value)
 
-class Team(pulumi.CustomResource):
+
+class TeamAdministrators(pulumi.CustomResource):
     @overload
     def __init__(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
                  administrators: Optional[pulumi.Input[Sequence[pulumi.Input[str]]]] = None,
-                 description: Optional[pulumi.Input[str]] = None,
-                 members: Optional[pulumi.Input[Sequence[pulumi.Input[str]]]] = None,
-                 name: Optional[pulumi.Input[str]] = None,
+                 mode: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
+                 team_id: Optional[pulumi.Input[str]] = None,
                  __props__=None):
         """
-        Manages a team within a project in a Azure DevOps organization.
+        Manages administrators of a team within a project in a Azure DevOps organization.
 
         ## Example Usage
 
         ```python
         import pulumi
         import pulumi_azuredevops as azuredevops
 
         example_project = azuredevops.Project("exampleProject",
             work_item_template="Agile",
             version_control="Git",
             visibility="private",
             description="Managed by Terraform")
         example_project_contributors = azuredevops.get_group_output(project_id=example_project.id,
             name="Contributors")
-        example_project_readers = azuredevops.get_group_output(project_id=example_project.id,
-            name="Readers")
-        example_team = azuredevops.Team("exampleTeam",
-            project_id=example_project.id,
-            administrators=[example_project_contributors.descriptor],
-            members=[example_project_readers.descriptor])
+        example_team = azuredevops.Team("exampleTeam", project_id=example_project.id)
+        example_team_administrators = azuredevops.TeamAdministrators("example-team-administrators",
+            project_id=example_team.project_id,
+            team_id=example_team.id,
+            mode="overwrite",
+            administrators=[example_project_contributors.descriptor])
         ```
         ## Relevant Links
 
-        - [Azure DevOps Service REST API 6.0 - Teams - Create](https://docs.microsoft.com/en-us/rest/api/azure/devops/core/teams/create?view=azure-devops-rest-6.0)
+        - [Azure DevOps Service REST API 6.0 - Teams - Update](https://docs.microsoft.com/en-us/rest/api/azure/devops/core/teams/update?view=azure-devops-rest-6.0)
 
         ## PAT Permissions Required
 
-        - **vso.project_manage**:	Grants the ability to create, read, update, and delete projects and teams.
+        - **vso.project_write**:	Grants the ability to read and update projects and teams.
 
         ## Import
 
-        Azure DevOps teams can be imported using the complete resource id `<project_id>/<team_id>` e.g.
-
-        ```sh
-         $ pulumi import azuredevops:index/team:Team example 00000000-0000-0000-0000-000000000000/00000000-0000-0000-0000-000000000000
-        ```
+        The resource does not support import.
 
         :param str resource_name: The name of the resource.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[Sequence[pulumi.Input[str]]] administrators: List of subject descriptors to define administrators of the team.
-        :param pulumi.Input[str] description: The description of the Team.
-        :param pulumi.Input[Sequence[pulumi.Input[str]]] members: List of subject descriptors to define members of the team.
-        :param pulumi.Input[str] name: The name of the Team.
+        :param pulumi.Input[Sequence[pulumi.Input[str]]] administrators: List of subject descriptors to define adminitrators of the team.
+               
+               > NOTE: It's possible to define team administrators both within the
+               > `Team` resource via the `administrators` block and by using the
+               > `TeamAdministrators` resource. However it's not possible to use
+               > both methods to manage team administrators, since there'll be conflicts.
+        :param pulumi.Input[str] mode: The mode how the resource manages team administrators.
+               - `mode == add`: the resource will ensure that all specified administrators will be part of the referenced team
+               - `mode == overwrite`: the resource will replace all existing administrators with the administrators specified within the `administrators` block
         :param pulumi.Input[str] project_id: The Project ID.
+        :param pulumi.Input[str] team_id: The ID of the Team.
         """
         ...
     @overload
     def __init__(__self__,
                  resource_name: str,
-                 args: TeamArgs,
+                 args: TeamAdministratorsArgs,
                  opts: Optional[pulumi.ResourceOptions] = None):
         """
-        Manages a team within a project in a Azure DevOps organization.
+        Manages administrators of a team within a project in a Azure DevOps organization.
 
         ## Example Usage
 
         ```python
         import pulumi
         import pulumi_azuredevops as azuredevops
 
         example_project = azuredevops.Project("exampleProject",
             work_item_template="Agile",
             version_control="Git",
             visibility="private",
             description="Managed by Terraform")
         example_project_contributors = azuredevops.get_group_output(project_id=example_project.id,
             name="Contributors")
-        example_project_readers = azuredevops.get_group_output(project_id=example_project.id,
-            name="Readers")
-        example_team = azuredevops.Team("exampleTeam",
-            project_id=example_project.id,
-            administrators=[example_project_contributors.descriptor],
-            members=[example_project_readers.descriptor])
+        example_team = azuredevops.Team("exampleTeam", project_id=example_project.id)
+        example_team_administrators = azuredevops.TeamAdministrators("example-team-administrators",
+            project_id=example_team.project_id,
+            team_id=example_team.id,
+            mode="overwrite",
+            administrators=[example_project_contributors.descriptor])
         ```
         ## Relevant Links
 
-        - [Azure DevOps Service REST API 6.0 - Teams - Create](https://docs.microsoft.com/en-us/rest/api/azure/devops/core/teams/create?view=azure-devops-rest-6.0)
+        - [Azure DevOps Service REST API 6.0 - Teams - Update](https://docs.microsoft.com/en-us/rest/api/azure/devops/core/teams/update?view=azure-devops-rest-6.0)
 
         ## PAT Permissions Required
 
-        - **vso.project_manage**:	Grants the ability to create, read, update, and delete projects and teams.
+        - **vso.project_write**:	Grants the ability to read and update projects and teams.
 
         ## Import
 
-        Azure DevOps teams can be imported using the complete resource id `<project_id>/<team_id>` e.g.
-
-        ```sh
-         $ pulumi import azuredevops:index/team:Team example 00000000-0000-0000-0000-000000000000/00000000-0000-0000-0000-000000000000
-        ```
+        The resource does not support import.
 
         :param str resource_name: The name of the resource.
-        :param TeamArgs args: The arguments to use to populate this resource's properties.
+        :param TeamAdministratorsArgs args: The arguments to use to populate this resource's properties.
         :param pulumi.ResourceOptions opts: Options for the resource.
         """
         ...
     def __init__(__self__, resource_name: str, *args, **kwargs):
-        resource_args, opts = _utilities.get_resource_args_opts(TeamArgs, pulumi.ResourceOptions, *args, **kwargs)
+        resource_args, opts = _utilities.get_resource_args_opts(TeamAdministratorsArgs, pulumi.ResourceOptions, *args, **kwargs)
         if resource_args is not None:
             __self__._internal_init(resource_name, opts, **resource_args.__dict__)
         else:
             __self__._internal_init(resource_name, *args, **kwargs)
 
     def _internal_init(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
                  administrators: Optional[pulumi.Input[Sequence[pulumi.Input[str]]]] = None,
-                 description: Optional[pulumi.Input[str]] = None,
-                 members: Optional[pulumi.Input[Sequence[pulumi.Input[str]]]] = None,
-                 name: Optional[pulumi.Input[str]] = None,
+                 mode: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
+                 team_id: Optional[pulumi.Input[str]] = None,
                  __props__=None):
         opts = pulumi.ResourceOptions.merge(_utilities.get_resource_opts_defaults(), opts)
         if not isinstance(opts, pulumi.ResourceOptions):
             raise TypeError('Expected resource options to be a ResourceOptions instance')
         if opts.id is None:
             if __props__ is not None:
                 raise TypeError('__props__ is only valid when passed in combination with a valid opts.id to get an existing resource')
-            __props__ = TeamArgs.__new__(TeamArgs)
+            __props__ = TeamAdministratorsArgs.__new__(TeamAdministratorsArgs)
 
+            if administrators is None and not opts.urn:
+                raise TypeError("Missing required property 'administrators'")
             __props__.__dict__["administrators"] = administrators
-            __props__.__dict__["description"] = description
-            __props__.__dict__["members"] = members
-            __props__.__dict__["name"] = name
+            __props__.__dict__["mode"] = mode
             if project_id is None and not opts.urn:
                 raise TypeError("Missing required property 'project_id'")
             __props__.__dict__["project_id"] = project_id
-            __props__.__dict__["descriptor"] = None
-        super(Team, __self__).__init__(
-            'azuredevops:index/team:Team',
+            if team_id is None and not opts.urn:
+                raise TypeError("Missing required property 'team_id'")
+            __props__.__dict__["team_id"] = team_id
+        super(TeamAdministrators, __self__).__init__(
+            'azuredevops:index/teamAdministrators:TeamAdministrators',
             resource_name,
             __props__,
             opts)
 
     @staticmethod
     def get(resource_name: str,
             id: pulumi.Input[str],
             opts: Optional[pulumi.ResourceOptions] = None,
             administrators: Optional[pulumi.Input[Sequence[pulumi.Input[str]]]] = None,
-            description: Optional[pulumi.Input[str]] = None,
-            descriptor: Optional[pulumi.Input[str]] = None,
-            members: Optional[pulumi.Input[Sequence[pulumi.Input[str]]]] = None,
-            name: Optional[pulumi.Input[str]] = None,
-            project_id: Optional[pulumi.Input[str]] = None) -> 'Team':
+            mode: Optional[pulumi.Input[str]] = None,
+            project_id: Optional[pulumi.Input[str]] = None,
+            team_id: Optional[pulumi.Input[str]] = None) -> 'TeamAdministrators':
         """
-        Get an existing Team resource's state with the given name, id, and optional extra
+        Get an existing TeamAdministrators resource's state with the given name, id, and optional extra
         properties used to qualify the lookup.
 
         :param str resource_name: The unique name of the resulting resource.
         :param pulumi.Input[str] id: The unique provider ID of the resource to lookup.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[Sequence[pulumi.Input[str]]] administrators: List of subject descriptors to define administrators of the team.
-        :param pulumi.Input[str] description: The description of the Team.
-        :param pulumi.Input[str] descriptor: The descriptor of the Team.
-        :param pulumi.Input[Sequence[pulumi.Input[str]]] members: List of subject descriptors to define members of the team.
-        :param pulumi.Input[str] name: The name of the Team.
+        :param pulumi.Input[Sequence[pulumi.Input[str]]] administrators: List of subject descriptors to define adminitrators of the team.
+               
+               > NOTE: It's possible to define team administrators both within the
+               > `Team` resource via the `administrators` block and by using the
+               > `TeamAdministrators` resource. However it's not possible to use
+               > both methods to manage team administrators, since there'll be conflicts.
+        :param pulumi.Input[str] mode: The mode how the resource manages team administrators.
+               - `mode == add`: the resource will ensure that all specified administrators will be part of the referenced team
+               - `mode == overwrite`: the resource will replace all existing administrators with the administrators specified within the `administrators` block
         :param pulumi.Input[str] project_id: The Project ID.
+        :param pulumi.Input[str] team_id: The ID of the Team.
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
 
-        __props__ = _TeamState.__new__(_TeamState)
+        __props__ = _TeamAdministratorsState.__new__(_TeamAdministratorsState)
 
         __props__.__dict__["administrators"] = administrators
-        __props__.__dict__["description"] = description
-        __props__.__dict__["descriptor"] = descriptor
-        __props__.__dict__["members"] = members
-        __props__.__dict__["name"] = name
+        __props__.__dict__["mode"] = mode
         __props__.__dict__["project_id"] = project_id
-        return Team(resource_name, opts=opts, __props__=__props__)
+        __props__.__dict__["team_id"] = team_id
+        return TeamAdministrators(resource_name, opts=opts, __props__=__props__)
 
     @property
     @pulumi.getter
     def administrators(self) -> pulumi.Output[Sequence[str]]:
         """
-        List of subject descriptors to define administrators of the team.
-        """
-        return pulumi.get(self, "administrators")
-
-    @property
-    @pulumi.getter
-    def description(self) -> pulumi.Output[Optional[str]]:
-        """
-        The description of the Team.
-        """
-        return pulumi.get(self, "description")
+        List of subject descriptors to define adminitrators of the team.
 
-    @property
-    @pulumi.getter
-    def descriptor(self) -> pulumi.Output[str]:
+        > NOTE: It's possible to define team administrators both within the
+        > `Team` resource via the `administrators` block and by using the
+        > `TeamAdministrators` resource. However it's not possible to use
+        > both methods to manage team administrators, since there'll be conflicts.
         """
-        The descriptor of the Team.
-        """
-        return pulumi.get(self, "descriptor")
-
-    @property
-    @pulumi.getter
-    def members(self) -> pulumi.Output[Sequence[str]]:
-        """
-        List of subject descriptors to define members of the team.
-        """
-        return pulumi.get(self, "members")
+        return pulumi.get(self, "administrators")
 
     @property
     @pulumi.getter
-    def name(self) -> pulumi.Output[str]:
+    def mode(self) -> pulumi.Output[Optional[str]]:
         """
-        The name of the Team.
+        The mode how the resource manages team administrators.
+        - `mode == add`: the resource will ensure that all specified administrators will be part of the referenced team
+        - `mode == overwrite`: the resource will replace all existing administrators with the administrators specified within the `administrators` block
         """
-        return pulumi.get(self, "name")
+        return pulumi.get(self, "mode")
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> pulumi.Output[str]:
         """
         The Project ID.
         """
         return pulumi.get(self, "project_id")
 
+    @property
+    @pulumi.getter(name="teamId")
+    def team_id(self) -> pulumi.Output[str]:
+        """
+        The ID of the Team.
+        """
+        return pulumi.get(self, "team_id")
+
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/user.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/user.py`

 * *Files 4% similar despite different names*

```diff
@@ -19,14 +19,16 @@
                  origin: Optional[pulumi.Input[str]] = None,
                  origin_id: Optional[pulumi.Input[str]] = None,
                  principal_name: Optional[pulumi.Input[str]] = None):
         """
         The set of arguments for constructing a User resource.
         :param pulumi.Input[str] account_license_type: Type of Account License. Valid values: `advanced`, `earlyAdopter`, `express`, `none`, `professional`, or `stakeholder`. Defaults to `express`. In addition the value `basic` is allowed which is an alias for `express` and reflects the name of the `express` license used in the Azure DevOps web interface.
         :param pulumi.Input[str] licensing_source: The source of the licensing (e.g. Account. MSDN etc.) Valid values: `account` (Default), `auto`, `msdn`, `none`, `profile`, `trial`
+               
+               > **NOTE:** A user can only be referenced by it's `principal_name` or by the combination of `origin_id` and `origin`.
         :param pulumi.Input[str] origin: The type of source provider for the origin identifier.
         :param pulumi.Input[str] origin_id: The unique identifier from the system of origin. Typically a sid, object id or Guid. e.g. Used for member of other tenant on Azure Active Directory.
         :param pulumi.Input[str] principal_name: The principal name is the PrincipalName of a graph member from the source provider. Usually, e-mail address.
         """
         if account_license_type is not None:
             pulumi.set(__self__, "account_license_type", account_license_type)
         if licensing_source is not None:
@@ -51,14 +53,16 @@
         pulumi.set(self, "account_license_type", value)
 
     @property
     @pulumi.getter(name="licensingSource")
     def licensing_source(self) -> Optional[pulumi.Input[str]]:
         """
         The source of the licensing (e.g. Account. MSDN etc.) Valid values: `account` (Default), `auto`, `msdn`, `none`, `profile`, `trial`
+
+        > **NOTE:** A user can only be referenced by it's `principal_name` or by the combination of `origin_id` and `origin`.
         """
         return pulumi.get(self, "licensing_source")
 
     @licensing_source.setter
     def licensing_source(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "licensing_source", value)
 
@@ -109,14 +113,16 @@
                  origin_id: Optional[pulumi.Input[str]] = None,
                  principal_name: Optional[pulumi.Input[str]] = None):
         """
         Input properties used for looking up and filtering User resources.
         :param pulumi.Input[str] account_license_type: Type of Account License. Valid values: `advanced`, `earlyAdopter`, `express`, `none`, `professional`, or `stakeholder`. Defaults to `express`. In addition the value `basic` is allowed which is an alias for `express` and reflects the name of the `express` license used in the Azure DevOps web interface.
         :param pulumi.Input[str] descriptor: The descriptor is the primary way to reference the graph subject while the system is running. This field will uniquely identify the user graph subject.
         :param pulumi.Input[str] licensing_source: The source of the licensing (e.g. Account. MSDN etc.) Valid values: `account` (Default), `auto`, `msdn`, `none`, `profile`, `trial`
+               
+               > **NOTE:** A user can only be referenced by it's `principal_name` or by the combination of `origin_id` and `origin`.
         :param pulumi.Input[str] origin: The type of source provider for the origin identifier.
         :param pulumi.Input[str] origin_id: The unique identifier from the system of origin. Typically a sid, object id or Guid. e.g. Used for member of other tenant on Azure Active Directory.
         :param pulumi.Input[str] principal_name: The principal name is the PrincipalName of a graph member from the source provider. Usually, e-mail address.
         """
         if account_license_type is not None:
             pulumi.set(__self__, "account_license_type", account_license_type)
         if descriptor is not None:
@@ -155,14 +161,16 @@
         pulumi.set(self, "descriptor", value)
 
     @property
     @pulumi.getter(name="licensingSource")
     def licensing_source(self) -> Optional[pulumi.Input[str]]:
         """
         The source of the licensing (e.g. Account. MSDN etc.) Valid values: `account` (Default), `auto`, `msdn`, `none`, `profile`, `trial`
+
+        > **NOTE:** A user can only be referenced by it's `principal_name` or by the combination of `origin_id` and `origin`.
         """
         return pulumi.get(self, "licensing_source")
 
     @licensing_source.setter
     def licensing_source(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "licensing_source", value)
 
@@ -238,14 +246,16 @@
 
         The resources allows the import via the UUID of a user entitlement or by using the principal name of a user owning an entitlement.
 
         :param str resource_name: The name of the resource.
         :param pulumi.ResourceOptions opts: Options for the resource.
         :param pulumi.Input[str] account_license_type: Type of Account License. Valid values: `advanced`, `earlyAdopter`, `express`, `none`, `professional`, or `stakeholder`. Defaults to `express`. In addition the value `basic` is allowed which is an alias for `express` and reflects the name of the `express` license used in the Azure DevOps web interface.
         :param pulumi.Input[str] licensing_source: The source of the licensing (e.g. Account. MSDN etc.) Valid values: `account` (Default), `auto`, `msdn`, `none`, `profile`, `trial`
+               
+               > **NOTE:** A user can only be referenced by it's `principal_name` or by the combination of `origin_id` and `origin`.
         :param pulumi.Input[str] origin: The type of source provider for the origin identifier.
         :param pulumi.Input[str] origin_id: The unique identifier from the system of origin. Typically a sid, object id or Guid. e.g. Used for member of other tenant on Azure Active Directory.
         :param pulumi.Input[str] principal_name: The principal name is the PrincipalName of a graph member from the source provider. Usually, e-mail address.
         """
         ...
     @overload
     def __init__(__self__,
@@ -335,14 +345,16 @@
 
         :param str resource_name: The unique name of the resulting resource.
         :param pulumi.Input[str] id: The unique provider ID of the resource to lookup.
         :param pulumi.ResourceOptions opts: Options for the resource.
         :param pulumi.Input[str] account_license_type: Type of Account License. Valid values: `advanced`, `earlyAdopter`, `express`, `none`, `professional`, or `stakeholder`. Defaults to `express`. In addition the value `basic` is allowed which is an alias for `express` and reflects the name of the `express` license used in the Azure DevOps web interface.
         :param pulumi.Input[str] descriptor: The descriptor is the primary way to reference the graph subject while the system is running. This field will uniquely identify the user graph subject.
         :param pulumi.Input[str] licensing_source: The source of the licensing (e.g. Account. MSDN etc.) Valid values: `account` (Default), `auto`, `msdn`, `none`, `profile`, `trial`
+               
+               > **NOTE:** A user can only be referenced by it's `principal_name` or by the combination of `origin_id` and `origin`.
         :param pulumi.Input[str] origin: The type of source provider for the origin identifier.
         :param pulumi.Input[str] origin_id: The unique identifier from the system of origin. Typically a sid, object id or Guid. e.g. Used for member of other tenant on Azure Active Directory.
         :param pulumi.Input[str] principal_name: The principal name is the PrincipalName of a graph member from the source provider. Usually, e-mail address.
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
 
         __props__ = _UserState.__new__(_UserState)
@@ -372,14 +384,16 @@
         return pulumi.get(self, "descriptor")
 
     @property
     @pulumi.getter(name="licensingSource")
     def licensing_source(self) -> pulumi.Output[Optional[str]]:
         """
         The source of the licensing (e.g. Account. MSDN etc.) Valid values: `account` (Default), `auto`, `msdn`, `none`, `profile`, `trial`
+
+        > **NOTE:** A user can only be referenced by it's `principal_name` or by the combination of `origin_id` and `origin`.
         """
         return pulumi.get(self, "licensing_source")
 
     @property
     @pulumi.getter
     def origin(self) -> pulumi.Output[str]:
         """
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/variable_group.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/variable_group.py`

 * *Files identical despite different names*

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/work_item_query_permissions.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/serviceendpoint_permissions.py`

 * *Files 23% similar despite different names*

```diff
@@ -5,45 +5,53 @@
 import copy
 import warnings
 import pulumi
 import pulumi.runtime
 from typing import Any, Mapping, Optional, Sequence, Union, overload
 from . import _utilities
 
-__all__ = ['WorkItemQueryPermissionsArgs', 'WorkItemQueryPermissions']
+__all__ = ['ServiceendpointPermissionsArgs', 'ServiceendpointPermissions']
 
 @pulumi.input_type
-class WorkItemQueryPermissionsArgs:
+class ServiceendpointPermissionsArgs:
     def __init__(__self__, *,
                  permissions: pulumi.Input[Mapping[str, pulumi.Input[str]]],
                  principal: pulumi.Input[str],
                  project_id: pulumi.Input[str],
-                 path: Optional[pulumi.Input[str]] = None,
-                 replace: Optional[pulumi.Input[bool]] = None):
+                 replace: Optional[pulumi.Input[bool]] = None,
+                 serviceendpoint_id: Optional[pulumi.Input[str]] = None):
         """
-        The set of arguments for constructing a WorkItemQueryPermissions resource.
-        :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available
+        The set of arguments for constructing a ServiceendpointPermissions resource.
+        :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available.
         :param pulumi.Input[str] principal: The **group** principal to assign the permissions.
-        :param pulumi.Input[str] project_id: The ID of the project to assign the permissions.
-        :param pulumi.Input[str] path: Path to a query or folder beneath `Shared Queries`
+        :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
+               
+               | Permission        | Description                         |
+               | ----------------- | ----------------------------------- |
+               | Use               | Use service endpoint                |
+               | Administer        | Full control over service endpoints |
+               | Create            | Create service endpoints            |
+               | ViewAuthorization | View authorizations                 |
+               | ViewEndpoint      | View service endpoint properties    |
+        :param pulumi.Input[str] serviceendpoint_id: The id of the service endpoint to assign the permissions.
         """
         pulumi.set(__self__, "permissions", permissions)
         pulumi.set(__self__, "principal", principal)
         pulumi.set(__self__, "project_id", project_id)
-        if path is not None:
-            pulumi.set(__self__, "path", path)
         if replace is not None:
             pulumi.set(__self__, "replace", replace)
+        if serviceendpoint_id is not None:
+            pulumi.set(__self__, "serviceendpoint_id", serviceendpoint_id)
 
     @property
     @pulumi.getter
     def permissions(self) -> pulumi.Input[Mapping[str, pulumi.Input[str]]]:
         """
-        the permissions to assign. The following permissions are available
+        the permissions to assign. The following permissions are available.
         """
         return pulumi.get(self, "permissions")
 
     @permissions.setter
     def permissions(self, value: pulumi.Input[Mapping[str, pulumi.Input[str]]]):
         pulumi.set(self, "permissions", value)
 
@@ -59,91 +67,95 @@
     def principal(self, value: pulumi.Input[str]):
         pulumi.set(self, "principal", value)
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> pulumi.Input[str]:
         """
-        The ID of the project to assign the permissions.
+        The ID of the project.
         """
         return pulumi.get(self, "project_id")
 
     @project_id.setter
     def project_id(self, value: pulumi.Input[str]):
         pulumi.set(self, "project_id", value)
 
     @property
     @pulumi.getter
-    def path(self) -> Optional[pulumi.Input[str]]:
-        """
-        Path to a query or folder beneath `Shared Queries`
-        """
-        return pulumi.get(self, "path")
-
-    @path.setter
-    def path(self, value: Optional[pulumi.Input[str]]):
-        pulumi.set(self, "path", value)
-
-    @property
-    @pulumi.getter
     def replace(self) -> Optional[pulumi.Input[bool]]:
         """
         Replace (`true`) or merge (`false`) the permissions. Default: `true`
+
+        | Permission        | Description                         |
+        | ----------------- | ----------------------------------- |
+        | Use               | Use service endpoint                |
+        | Administer        | Full control over service endpoints |
+        | Create            | Create service endpoints            |
+        | ViewAuthorization | View authorizations                 |
+        | ViewEndpoint      | View service endpoint properties    |
         """
         return pulumi.get(self, "replace")
 
     @replace.setter
     def replace(self, value: Optional[pulumi.Input[bool]]):
         pulumi.set(self, "replace", value)
 
+    @property
+    @pulumi.getter(name="serviceendpointId")
+    def serviceendpoint_id(self) -> Optional[pulumi.Input[str]]:
+        """
+        The id of the service endpoint to assign the permissions.
+        """
+        return pulumi.get(self, "serviceendpoint_id")
+
+    @serviceendpoint_id.setter
+    def serviceendpoint_id(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "serviceendpoint_id", value)
+
 
 @pulumi.input_type
-class _WorkItemQueryPermissionsState:
+class _ServiceendpointPermissionsState:
     def __init__(__self__, *,
-                 path: Optional[pulumi.Input[str]] = None,
                  permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
                  principal: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
-                 replace: Optional[pulumi.Input[bool]] = None):
+                 replace: Optional[pulumi.Input[bool]] = None,
+                 serviceendpoint_id: Optional[pulumi.Input[str]] = None):
         """
-        Input properties used for looking up and filtering WorkItemQueryPermissions resources.
-        :param pulumi.Input[str] path: Path to a query or folder beneath `Shared Queries`
-        :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available
+        Input properties used for looking up and filtering ServiceendpointPermissions resources.
+        :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available.
         :param pulumi.Input[str] principal: The **group** principal to assign the permissions.
-        :param pulumi.Input[str] project_id: The ID of the project to assign the permissions.
+        :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
+               
+               | Permission        | Description                         |
+               | ----------------- | ----------------------------------- |
+               | Use               | Use service endpoint                |
+               | Administer        | Full control over service endpoints |
+               | Create            | Create service endpoints            |
+               | ViewAuthorization | View authorizations                 |
+               | ViewEndpoint      | View service endpoint properties    |
+        :param pulumi.Input[str] serviceendpoint_id: The id of the service endpoint to assign the permissions.
         """
-        if path is not None:
-            pulumi.set(__self__, "path", path)
         if permissions is not None:
             pulumi.set(__self__, "permissions", permissions)
         if principal is not None:
             pulumi.set(__self__, "principal", principal)
         if project_id is not None:
             pulumi.set(__self__, "project_id", project_id)
         if replace is not None:
             pulumi.set(__self__, "replace", replace)
-
-    @property
-    @pulumi.getter
-    def path(self) -> Optional[pulumi.Input[str]]:
-        """
-        Path to a query or folder beneath `Shared Queries`
-        """
-        return pulumi.get(self, "path")
-
-    @path.setter
-    def path(self, value: Optional[pulumi.Input[str]]):
-        pulumi.set(self, "path", value)
+        if serviceendpoint_id is not None:
+            pulumi.set(__self__, "serviceendpoint_id", serviceendpoint_id)
 
     @property
     @pulumi.getter
     def permissions(self) -> Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]:
         """
-        the permissions to assign. The following permissions are available
+        the permissions to assign. The following permissions are available.
         """
         return pulumi.get(self, "permissions")
 
     @permissions.setter
     def permissions(self, value: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]):
         pulumi.set(self, "permissions", value)
 
@@ -159,144 +171,116 @@
     def principal(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "principal", value)
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> Optional[pulumi.Input[str]]:
         """
-        The ID of the project to assign the permissions.
+        The ID of the project.
         """
         return pulumi.get(self, "project_id")
 
     @project_id.setter
     def project_id(self, value: Optional[pulumi.Input[str]]):
         pulumi.set(self, "project_id", value)
 
     @property
     @pulumi.getter
     def replace(self) -> Optional[pulumi.Input[bool]]:
         """
         Replace (`true`) or merge (`false`) the permissions. Default: `true`
+
+        | Permission        | Description                         |
+        | ----------------- | ----------------------------------- |
+        | Use               | Use service endpoint                |
+        | Administer        | Full control over service endpoints |
+        | Create            | Create service endpoints            |
+        | ViewAuthorization | View authorizations                 |
+        | ViewEndpoint      | View service endpoint properties    |
         """
         return pulumi.get(self, "replace")
 
     @replace.setter
     def replace(self, value: Optional[pulumi.Input[bool]]):
         pulumi.set(self, "replace", value)
 
+    @property
+    @pulumi.getter(name="serviceendpointId")
+    def serviceendpoint_id(self) -> Optional[pulumi.Input[str]]:
+        """
+        The id of the service endpoint to assign the permissions.
+        """
+        return pulumi.get(self, "serviceendpoint_id")
 
-class WorkItemQueryPermissions(pulumi.CustomResource):
+    @serviceendpoint_id.setter
+    def serviceendpoint_id(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "serviceendpoint_id", value)
+
+
+class ServiceendpointPermissions(pulumi.CustomResource):
     @overload
     def __init__(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
-                 path: Optional[pulumi.Input[str]] = None,
                  permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
                  principal: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  replace: Optional[pulumi.Input[bool]] = None,
+                 serviceendpoint_id: Optional[pulumi.Input[str]] = None,
                  __props__=None):
         """
-        Manages permissions for Work Item Queries.
+        Manages permissions for a Service Endpoint
 
         > **Note** Permissions can be assigned to group principals and not to single user principals.
 
         ## Permission levels
 
-        Permission for Work Item Queries within Azure DevOps can be applied on two different levels.
-        Those levels are reflected by specifying (or omitting) values for the arguments `project_id` and `path`.
-
-        ### Project level
-
-        Permissions for all Work Item Queries inside a project (existing or newly created ones) are specified, if only the argument `project_id` has a value.
-
-        #### Example usage
-
-        ```python
-        import pulumi
-        import pulumi_azuredevops as azuredevops
-
-        example = azuredevops.Project("example",
-            work_item_template="Agile",
-            version_control="Git",
-            visibility="private",
-            description="Managed by Terraform")
-        example_readers = azuredevops.get_group_output(project_id=example.id,
-            name="Readers")
-        project_wiq_root_permissions = azuredevops.WorkItemQueryPermissions("project-wiq-root-permissions",
-            project_id=example.id,
-            principal=example_readers.id,
-            permissions={
-                "CreateRepository": "Deny",
-                "DeleteRepository": "Deny",
-                "RenameRepository": "NotSet",
-            })
-        ```
-
-        ### Shared Queries folder level
-
-        Permissions for a specific folder inside Shared Queries are specified if the arguments `project_id` and `path` are set.
-
-        > **Note** To set permissions for the Shared Queries folder itself use `/` as path value
-
-        #### Example usage
-
-        ```python
-        import pulumi
-        import pulumi_azuredevops as azuredevops
-
-        example = azuredevops.Project("example",
-            work_item_template="Agile",
-            version_control="Git",
-            visibility="private",
-            description="Managed by Terraform")
-        example_readers = azuredevops.get_group_output(project_id=example.id,
-            name="Readers")
-        example_permissions = azuredevops.WorkItemQueryPermissions("example-permissions",
-            project_id=example.id,
-            path="/Team",
-            principal=example_readers.id,
-            permissions={
-                "Contribute": "Allow",
-                "Delete": "Deny",
-                "Read": "NotSet",
-            })
-        ```
+        Permission for Service Endpoints within Azure DevOps can be applied on two different levels.
+        Those levels are reflected by specifying (or omitting) values for the arguments `project_id` and `serviceendpoint_id`.
 
         ## Example Usage
 
         ```python
         import pulumi
         import pulumi_azuredevops as azuredevops
 
-        example = azuredevops.Project("example",
+        example_project = azuredevops.Project("exampleProject",
             work_item_template="Agile",
             version_control="Git",
             visibility="private",
             description="Managed by Terraform")
-        example_readers = azuredevops.get_group_output(project_id=example.id,
+        example_readers = azuredevops.get_group_output(project_id=example_project.id,
             name="Readers")
-        example_contributors = azuredevops.get_group_output(project_id=example.id,
-            name="Contributors")
-        example_project_permissions = azuredevops.WorkItemQueryPermissions("example-project-permissions",
-            project_id=example.id,
+        example_root_permissions = azuredevops.ServiceendpointPermissions("example-root-permissions",
+            project_id=example_project.id,
             principal=example_readers.id,
             permissions={
-                "Read": "Allow",
-                "Delete": "Deny",
-                "Contribute": "Deny",
-                "ManagePermissions": "Deny",
+                "Use": "allow",
+                "Administer": "allow",
+                "Create": "allow",
+                "ViewAuthorization": "allow",
+                "ViewEndpoint": "allow",
             })
-        example_sharedqueries_permissions = azuredevops.WorkItemQueryPermissions("example-sharedqueries-permissions",
-            project_id=example.id,
-            path="/",
-            principal=example_contributors.id,
+        example_service_endpoint_docker_registry = azuredevops.ServiceEndpointDockerRegistry("exampleServiceEndpointDockerRegistry",
+            project_id=example_project.id,
+            service_endpoint_name="Example Docker Hub",
+            docker_username="username",
+            docker_email="email@example.com",
+            docker_password="password",
+            registry_type="DockerHub")
+        example_permissions = azuredevops.ServiceendpointPermissions("example-permissions",
+            project_id=example_project.id,
+            principal=example_readers.id,
+            serviceendpoint_id=example_service_endpoint_docker_registry.id,
             permissions={
-                "Read": "Allow",
-                "Delete": "Deny",
+                "Use": "allow",
+                "Administer": "deny",
+                "Create": "deny",
+                "ViewAuthorization": "allow",
+                "ViewEndpoint": "allow",
             })
         ```
         ## Relevant Links
 
         * [Azure DevOps Service REST API 6.0 - Security](https://docs.microsoft.com/en-us/rest/api/azure/devops/security/?view=azure-devops-rest-6.0)
 
         ## PAT Permissions Required
@@ -305,124 +289,84 @@
 
         ## Import
 
         The resource does not support import.
 
         :param str resource_name: The name of the resource.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[str] path: Path to a query or folder beneath `Shared Queries`
-        :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available
+        :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available.
         :param pulumi.Input[str] principal: The **group** principal to assign the permissions.
-        :param pulumi.Input[str] project_id: The ID of the project to assign the permissions.
+        :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
+               
+               | Permission        | Description                         |
+               | ----------------- | ----------------------------------- |
+               | Use               | Use service endpoint                |
+               | Administer        | Full control over service endpoints |
+               | Create            | Create service endpoints            |
+               | ViewAuthorization | View authorizations                 |
+               | ViewEndpoint      | View service endpoint properties    |
+        :param pulumi.Input[str] serviceendpoint_id: The id of the service endpoint to assign the permissions.
         """
         ...
     @overload
     def __init__(__self__,
                  resource_name: str,
-                 args: WorkItemQueryPermissionsArgs,
+                 args: ServiceendpointPermissionsArgs,
                  opts: Optional[pulumi.ResourceOptions] = None):
         """
-        Manages permissions for Work Item Queries.
+        Manages permissions for a Service Endpoint
 
         > **Note** Permissions can be assigned to group principals and not to single user principals.
 
         ## Permission levels
 
-        Permission for Work Item Queries within Azure DevOps can be applied on two different levels.
-        Those levels are reflected by specifying (or omitting) values for the arguments `project_id` and `path`.
-
-        ### Project level
-
-        Permissions for all Work Item Queries inside a project (existing or newly created ones) are specified, if only the argument `project_id` has a value.
-
-        #### Example usage
-
-        ```python
-        import pulumi
-        import pulumi_azuredevops as azuredevops
-
-        example = azuredevops.Project("example",
-            work_item_template="Agile",
-            version_control="Git",
-            visibility="private",
-            description="Managed by Terraform")
-        example_readers = azuredevops.get_group_output(project_id=example.id,
-            name="Readers")
-        project_wiq_root_permissions = azuredevops.WorkItemQueryPermissions("project-wiq-root-permissions",
-            project_id=example.id,
-            principal=example_readers.id,
-            permissions={
-                "CreateRepository": "Deny",
-                "DeleteRepository": "Deny",
-                "RenameRepository": "NotSet",
-            })
-        ```
-
-        ### Shared Queries folder level
-
-        Permissions for a specific folder inside Shared Queries are specified if the arguments `project_id` and `path` are set.
-
-        > **Note** To set permissions for the Shared Queries folder itself use `/` as path value
-
-        #### Example usage
-
-        ```python
-        import pulumi
-        import pulumi_azuredevops as azuredevops
-
-        example = azuredevops.Project("example",
-            work_item_template="Agile",
-            version_control="Git",
-            visibility="private",
-            description="Managed by Terraform")
-        example_readers = azuredevops.get_group_output(project_id=example.id,
-            name="Readers")
-        example_permissions = azuredevops.WorkItemQueryPermissions("example-permissions",
-            project_id=example.id,
-            path="/Team",
-            principal=example_readers.id,
-            permissions={
-                "Contribute": "Allow",
-                "Delete": "Deny",
-                "Read": "NotSet",
-            })
-        ```
+        Permission for Service Endpoints within Azure DevOps can be applied on two different levels.
+        Those levels are reflected by specifying (or omitting) values for the arguments `project_id` and `serviceendpoint_id`.
 
         ## Example Usage
 
         ```python
         import pulumi
         import pulumi_azuredevops as azuredevops
 
-        example = azuredevops.Project("example",
+        example_project = azuredevops.Project("exampleProject",
             work_item_template="Agile",
             version_control="Git",
             visibility="private",
             description="Managed by Terraform")
-        example_readers = azuredevops.get_group_output(project_id=example.id,
+        example_readers = azuredevops.get_group_output(project_id=example_project.id,
             name="Readers")
-        example_contributors = azuredevops.get_group_output(project_id=example.id,
-            name="Contributors")
-        example_project_permissions = azuredevops.WorkItemQueryPermissions("example-project-permissions",
-            project_id=example.id,
+        example_root_permissions = azuredevops.ServiceendpointPermissions("example-root-permissions",
+            project_id=example_project.id,
             principal=example_readers.id,
             permissions={
-                "Read": "Allow",
-                "Delete": "Deny",
-                "Contribute": "Deny",
-                "ManagePermissions": "Deny",
+                "Use": "allow",
+                "Administer": "allow",
+                "Create": "allow",
+                "ViewAuthorization": "allow",
+                "ViewEndpoint": "allow",
             })
-        example_sharedqueries_permissions = azuredevops.WorkItemQueryPermissions("example-sharedqueries-permissions",
-            project_id=example.id,
-            path="/",
-            principal=example_contributors.id,
+        example_service_endpoint_docker_registry = azuredevops.ServiceEndpointDockerRegistry("exampleServiceEndpointDockerRegistry",
+            project_id=example_project.id,
+            service_endpoint_name="Example Docker Hub",
+            docker_username="username",
+            docker_email="email@example.com",
+            docker_password="password",
+            registry_type="DockerHub")
+        example_permissions = azuredevops.ServiceendpointPermissions("example-permissions",
+            project_id=example_project.id,
+            principal=example_readers.id,
+            serviceendpoint_id=example_service_endpoint_docker_registry.id,
             permissions={
-                "Read": "Allow",
-                "Delete": "Deny",
+                "Use": "allow",
+                "Administer": "deny",
+                "Create": "deny",
+                "ViewAuthorization": "allow",
+                "ViewEndpoint": "allow",
             })
         ```
         ## Relevant Links
 
         * [Azure DevOps Service REST API 6.0 - Security](https://docs.microsoft.com/en-us/rest/api/azure/devops/security/?view=azure-devops-rest-6.0)
 
         ## PAT Permissions Required
@@ -430,105 +374,105 @@
         - **Project & Team**: vso.security_manage - Grants the ability to read, write, and manage security permissions.
 
         ## Import
 
         The resource does not support import.
 
         :param str resource_name: The name of the resource.
-        :param WorkItemQueryPermissionsArgs args: The arguments to use to populate this resource's properties.
+        :param ServiceendpointPermissionsArgs args: The arguments to use to populate this resource's properties.
         :param pulumi.ResourceOptions opts: Options for the resource.
         """
         ...
     def __init__(__self__, resource_name: str, *args, **kwargs):
-        resource_args, opts = _utilities.get_resource_args_opts(WorkItemQueryPermissionsArgs, pulumi.ResourceOptions, *args, **kwargs)
+        resource_args, opts = _utilities.get_resource_args_opts(ServiceendpointPermissionsArgs, pulumi.ResourceOptions, *args, **kwargs)
         if resource_args is not None:
             __self__._internal_init(resource_name, opts, **resource_args.__dict__)
         else:
             __self__._internal_init(resource_name, *args, **kwargs)
 
     def _internal_init(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
-                 path: Optional[pulumi.Input[str]] = None,
                  permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
                  principal: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  replace: Optional[pulumi.Input[bool]] = None,
+                 serviceendpoint_id: Optional[pulumi.Input[str]] = None,
                  __props__=None):
         opts = pulumi.ResourceOptions.merge(_utilities.get_resource_opts_defaults(), opts)
         if not isinstance(opts, pulumi.ResourceOptions):
             raise TypeError('Expected resource options to be a ResourceOptions instance')
         if opts.id is None:
             if __props__ is not None:
                 raise TypeError('__props__ is only valid when passed in combination with a valid opts.id to get an existing resource')
-            __props__ = WorkItemQueryPermissionsArgs.__new__(WorkItemQueryPermissionsArgs)
+            __props__ = ServiceendpointPermissionsArgs.__new__(ServiceendpointPermissionsArgs)
 
-            __props__.__dict__["path"] = path
             if permissions is None and not opts.urn:
                 raise TypeError("Missing required property 'permissions'")
             __props__.__dict__["permissions"] = permissions
             if principal is None and not opts.urn:
                 raise TypeError("Missing required property 'principal'")
             __props__.__dict__["principal"] = principal
             if project_id is None and not opts.urn:
                 raise TypeError("Missing required property 'project_id'")
             __props__.__dict__["project_id"] = project_id
             __props__.__dict__["replace"] = replace
-        super(WorkItemQueryPermissions, __self__).__init__(
-            'azuredevops:index/workItemQueryPermissions:WorkItemQueryPermissions',
+            __props__.__dict__["serviceendpoint_id"] = serviceendpoint_id
+        super(ServiceendpointPermissions, __self__).__init__(
+            'azuredevops:index/serviceendpointPermissions:ServiceendpointPermissions',
             resource_name,
             __props__,
             opts)
 
     @staticmethod
     def get(resource_name: str,
             id: pulumi.Input[str],
             opts: Optional[pulumi.ResourceOptions] = None,
-            path: Optional[pulumi.Input[str]] = None,
             permissions: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
             principal: Optional[pulumi.Input[str]] = None,
             project_id: Optional[pulumi.Input[str]] = None,
-            replace: Optional[pulumi.Input[bool]] = None) -> 'WorkItemQueryPermissions':
+            replace: Optional[pulumi.Input[bool]] = None,
+            serviceendpoint_id: Optional[pulumi.Input[str]] = None) -> 'ServiceendpointPermissions':
         """
-        Get an existing WorkItemQueryPermissions resource's state with the given name, id, and optional extra
+        Get an existing ServiceendpointPermissions resource's state with the given name, id, and optional extra
         properties used to qualify the lookup.
 
         :param str resource_name: The unique name of the resulting resource.
         :param pulumi.Input[str] id: The unique provider ID of the resource to lookup.
         :param pulumi.ResourceOptions opts: Options for the resource.
-        :param pulumi.Input[str] path: Path to a query or folder beneath `Shared Queries`
-        :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available
+        :param pulumi.Input[Mapping[str, pulumi.Input[str]]] permissions: the permissions to assign. The following permissions are available.
         :param pulumi.Input[str] principal: The **group** principal to assign the permissions.
-        :param pulumi.Input[str] project_id: The ID of the project to assign the permissions.
+        :param pulumi.Input[str] project_id: The ID of the project.
         :param pulumi.Input[bool] replace: Replace (`true`) or merge (`false`) the permissions. Default: `true`
+               
+               | Permission        | Description                         |
+               | ----------------- | ----------------------------------- |
+               | Use               | Use service endpoint                |
+               | Administer        | Full control over service endpoints |
+               | Create            | Create service endpoints            |
+               | ViewAuthorization | View authorizations                 |
+               | ViewEndpoint      | View service endpoint properties    |
+        :param pulumi.Input[str] serviceendpoint_id: The id of the service endpoint to assign the permissions.
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
 
-        __props__ = _WorkItemQueryPermissionsState.__new__(_WorkItemQueryPermissionsState)
+        __props__ = _ServiceendpointPermissionsState.__new__(_ServiceendpointPermissionsState)
 
-        __props__.__dict__["path"] = path
         __props__.__dict__["permissions"] = permissions
         __props__.__dict__["principal"] = principal
         __props__.__dict__["project_id"] = project_id
         __props__.__dict__["replace"] = replace
-        return WorkItemQueryPermissions(resource_name, opts=opts, __props__=__props__)
-
-    @property
-    @pulumi.getter
-    def path(self) -> pulumi.Output[Optional[str]]:
-        """
-        Path to a query or folder beneath `Shared Queries`
-        """
-        return pulumi.get(self, "path")
+        __props__.__dict__["serviceendpoint_id"] = serviceendpoint_id
+        return ServiceendpointPermissions(resource_name, opts=opts, __props__=__props__)
 
     @property
     @pulumi.getter
     def permissions(self) -> pulumi.Output[Mapping[str, str]]:
         """
-        the permissions to assign. The following permissions are available
+        the permissions to assign. The following permissions are available.
         """
         return pulumi.get(self, "permissions")
 
     @property
     @pulumi.getter
     def principal(self) -> pulumi.Output[str]:
         """
@@ -536,19 +480,35 @@
         """
         return pulumi.get(self, "principal")
 
     @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> pulumi.Output[str]:
         """
-        The ID of the project to assign the permissions.
+        The ID of the project.
         """
         return pulumi.get(self, "project_id")
 
     @property
     @pulumi.getter
     def replace(self) -> pulumi.Output[Optional[bool]]:
         """
         Replace (`true`) or merge (`false`) the permissions. Default: `true`
+
+        | Permission        | Description                         |
+        | ----------------- | ----------------------------------- |
+        | Use               | Use service endpoint                |
+        | Administer        | Full control over service endpoints |
+        | Create            | Create service endpoints            |
+        | ViewAuthorization | View authorizations                 |
+        | ViewEndpoint      | View service endpoint properties    |
         """
         return pulumi.get(self, "replace")
 
+    @property
+    @pulumi.getter(name="serviceendpointId")
+    def serviceendpoint_id(self) -> pulumi.Output[Optional[str]]:
+        """
+        The id of the service endpoint to assign the permissions.
+        """
+        return pulumi.get(self, "serviceendpoint_id")
+
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops/workitem.py` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops/workitem.py`

 * *Files 9% similar despite different names*

```diff
@@ -13,31 +13,39 @@
 
 @pulumi.input_type
 class WorkitemArgs:
     def __init__(__self__, *,
                  project_id: pulumi.Input[str],
                  title: pulumi.Input[str],
                  type: pulumi.Input[str],
+                 area_path: Optional[pulumi.Input[str]] = None,
                  custom_fields: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
+                 iteration_path: Optional[pulumi.Input[str]] = None,
                  state: Optional[pulumi.Input[str]] = None,
                  tags: Optional[pulumi.Input[Sequence[pulumi.Input[str]]]] = None):
         """
         The set of arguments for constructing a Workitem resource.
         :param pulumi.Input[str] project_id: The ID of the Project.
         :param pulumi.Input[str] title: The Title of the Work Item.
         :param pulumi.Input[str] type: The Type of the Work Item. The work item type varies depending on the process used when creating the project(`Agile`, `Basic`, `Scrum`, `Scrum`). See [Work Item Types](https://learn.microsoft.com/en-us/azure/devops/boards/work-items/about-work-items?view=azure-devops) for more details.
+        :param pulumi.Input[str] area_path: Specifies the area where the Work Item is used.
         :param pulumi.Input[Mapping[str, pulumi.Input[str]]] custom_fields: Specifies a list with Custom Fields for the Work Item.
+        :param pulumi.Input[str] iteration_path: Specifies the iteration in which the Work Item is used.
         :param pulumi.Input[str] state: The state of the Work Item. The four main states that are defined for the User Story (`Agile`) are `New`, `Active`, `Resolved`, and `Closed`. See [Workflow states](https://learn.microsoft.com/en-us/azure/devops/boards/work-items/workflow-and-state-categories?view=azure-devops&tabs=agile-process#workflow-states) for more details.
         :param pulumi.Input[Sequence[pulumi.Input[str]]] tags: Specifies a list of Tags.
         """
         pulumi.set(__self__, "project_id", project_id)
         pulumi.set(__self__, "title", title)
         pulumi.set(__self__, "type", type)
+        if area_path is not None:
+            pulumi.set(__self__, "area_path", area_path)
         if custom_fields is not None:
             pulumi.set(__self__, "custom_fields", custom_fields)
+        if iteration_path is not None:
+            pulumi.set(__self__, "iteration_path", iteration_path)
         if state is not None:
             pulumi.set(__self__, "state", state)
         if tags is not None:
             pulumi.set(__self__, "tags", tags)
 
     @property
     @pulumi.getter(name="projectId")
@@ -72,26 +80,50 @@
         return pulumi.get(self, "type")
 
     @type.setter
     def type(self, value: pulumi.Input[str]):
         pulumi.set(self, "type", value)
 
     @property
+    @pulumi.getter(name="areaPath")
+    def area_path(self) -> Optional[pulumi.Input[str]]:
+        """
+        Specifies the area where the Work Item is used.
+        """
+        return pulumi.get(self, "area_path")
+
+    @area_path.setter
+    def area_path(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "area_path", value)
+
+    @property
     @pulumi.getter(name="customFields")
     def custom_fields(self) -> Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]:
         """
         Specifies a list with Custom Fields for the Work Item.
         """
         return pulumi.get(self, "custom_fields")
 
     @custom_fields.setter
     def custom_fields(self, value: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]):
         pulumi.set(self, "custom_fields", value)
 
     @property
+    @pulumi.getter(name="iterationPath")
+    def iteration_path(self) -> Optional[pulumi.Input[str]]:
+        """
+        Specifies the iteration in which the Work Item is used.
+        """
+        return pulumi.get(self, "iteration_path")
+
+    @iteration_path.setter
+    def iteration_path(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "iteration_path", value)
+
+    @property
     @pulumi.getter
     def state(self) -> Optional[pulumi.Input[str]]:
         """
         The state of the Work Item. The four main states that are defined for the User Story (`Agile`) are `New`, `Active`, `Resolved`, and `Closed`. See [Workflow states](https://learn.microsoft.com/en-us/azure/devops/boards/work-items/workflow-and-state-categories?view=azure-devops&tabs=agile-process#workflow-states) for more details.
         """
         return pulumi.get(self, "state")
 
@@ -111,55 +143,87 @@
     def tags(self, value: Optional[pulumi.Input[Sequence[pulumi.Input[str]]]]):
         pulumi.set(self, "tags", value)
 
 
 @pulumi.input_type
 class _WorkitemState:
     def __init__(__self__, *,
+                 area_path: Optional[pulumi.Input[str]] = None,
                  custom_fields: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
+                 iteration_path: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  state: Optional[pulumi.Input[str]] = None,
                  tags: Optional[pulumi.Input[Sequence[pulumi.Input[str]]]] = None,
                  title: Optional[pulumi.Input[str]] = None,
                  type: Optional[pulumi.Input[str]] = None):
         """
         Input properties used for looking up and filtering Workitem resources.
+        :param pulumi.Input[str] area_path: Specifies the area where the Work Item is used.
         :param pulumi.Input[Mapping[str, pulumi.Input[str]]] custom_fields: Specifies a list with Custom Fields for the Work Item.
+        :param pulumi.Input[str] iteration_path: Specifies the iteration in which the Work Item is used.
         :param pulumi.Input[str] project_id: The ID of the Project.
         :param pulumi.Input[str] state: The state of the Work Item. The four main states that are defined for the User Story (`Agile`) are `New`, `Active`, `Resolved`, and `Closed`. See [Workflow states](https://learn.microsoft.com/en-us/azure/devops/boards/work-items/workflow-and-state-categories?view=azure-devops&tabs=agile-process#workflow-states) for more details.
         :param pulumi.Input[Sequence[pulumi.Input[str]]] tags: Specifies a list of Tags.
         :param pulumi.Input[str] title: The Title of the Work Item.
         :param pulumi.Input[str] type: The Type of the Work Item. The work item type varies depending on the process used when creating the project(`Agile`, `Basic`, `Scrum`, `Scrum`). See [Work Item Types](https://learn.microsoft.com/en-us/azure/devops/boards/work-items/about-work-items?view=azure-devops) for more details.
         """
+        if area_path is not None:
+            pulumi.set(__self__, "area_path", area_path)
         if custom_fields is not None:
             pulumi.set(__self__, "custom_fields", custom_fields)
+        if iteration_path is not None:
+            pulumi.set(__self__, "iteration_path", iteration_path)
         if project_id is not None:
             pulumi.set(__self__, "project_id", project_id)
         if state is not None:
             pulumi.set(__self__, "state", state)
         if tags is not None:
             pulumi.set(__self__, "tags", tags)
         if title is not None:
             pulumi.set(__self__, "title", title)
         if type is not None:
             pulumi.set(__self__, "type", type)
 
     @property
+    @pulumi.getter(name="areaPath")
+    def area_path(self) -> Optional[pulumi.Input[str]]:
+        """
+        Specifies the area where the Work Item is used.
+        """
+        return pulumi.get(self, "area_path")
+
+    @area_path.setter
+    def area_path(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "area_path", value)
+
+    @property
     @pulumi.getter(name="customFields")
     def custom_fields(self) -> Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]:
         """
         Specifies a list with Custom Fields for the Work Item.
         """
         return pulumi.get(self, "custom_fields")
 
     @custom_fields.setter
     def custom_fields(self, value: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]):
         pulumi.set(self, "custom_fields", value)
 
     @property
+    @pulumi.getter(name="iterationPath")
+    def iteration_path(self) -> Optional[pulumi.Input[str]]:
+        """
+        Specifies the iteration in which the Work Item is used.
+        """
+        return pulumi.get(self, "iteration_path")
+
+    @iteration_path.setter
+    def iteration_path(self, value: Optional[pulumi.Input[str]]):
+        pulumi.set(self, "iteration_path", value)
+
+    @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> Optional[pulumi.Input[str]]:
         """
         The ID of the Project.
         """
         return pulumi.get(self, "project_id")
 
@@ -217,15 +281,17 @@
 
 
 class Workitem(pulumi.CustomResource):
     @overload
     def __init__(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
+                 area_path: Optional[pulumi.Input[str]] = None,
                  custom_fields: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
+                 iteration_path: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  state: Optional[pulumi.Input[str]] = None,
                  tags: Optional[pulumi.Input[Sequence[pulumi.Input[str]]]] = None,
                  title: Optional[pulumi.Input[str]] = None,
                  type: Optional[pulumi.Input[str]] = None,
                  __props__=None):
         """
@@ -274,15 +340,17 @@
 
         ## Import
 
         Work Item resource does not support import.
 
         :param str resource_name: The name of the resource.
         :param pulumi.ResourceOptions opts: Options for the resource.
+        :param pulumi.Input[str] area_path: Specifies the area where the Work Item is used.
         :param pulumi.Input[Mapping[str, pulumi.Input[str]]] custom_fields: Specifies a list with Custom Fields for the Work Item.
+        :param pulumi.Input[str] iteration_path: Specifies the iteration in which the Work Item is used.
         :param pulumi.Input[str] project_id: The ID of the Project.
         :param pulumi.Input[str] state: The state of the Work Item. The four main states that are defined for the User Story (`Agile`) are `New`, `Active`, `Resolved`, and `Closed`. See [Workflow states](https://learn.microsoft.com/en-us/azure/devops/boards/work-items/workflow-and-state-categories?view=azure-devops&tabs=agile-process#workflow-states) for more details.
         :param pulumi.Input[Sequence[pulumi.Input[str]]] tags: Specifies a list of Tags.
         :param pulumi.Input[str] title: The Title of the Work Item.
         :param pulumi.Input[str] type: The Type of the Work Item. The work item type varies depending on the process used when creating the project(`Agile`, `Basic`, `Scrum`, `Scrum`). See [Work Item Types](https://learn.microsoft.com/en-us/azure/devops/boards/work-items/about-work-items?view=azure-devops) for more details.
         """
         ...
@@ -350,30 +418,34 @@
             __self__._internal_init(resource_name, opts, **resource_args.__dict__)
         else:
             __self__._internal_init(resource_name, *args, **kwargs)
 
     def _internal_init(__self__,
                  resource_name: str,
                  opts: Optional[pulumi.ResourceOptions] = None,
+                 area_path: Optional[pulumi.Input[str]] = None,
                  custom_fields: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
+                 iteration_path: Optional[pulumi.Input[str]] = None,
                  project_id: Optional[pulumi.Input[str]] = None,
                  state: Optional[pulumi.Input[str]] = None,
                  tags: Optional[pulumi.Input[Sequence[pulumi.Input[str]]]] = None,
                  title: Optional[pulumi.Input[str]] = None,
                  type: Optional[pulumi.Input[str]] = None,
                  __props__=None):
         opts = pulumi.ResourceOptions.merge(_utilities.get_resource_opts_defaults(), opts)
         if not isinstance(opts, pulumi.ResourceOptions):
             raise TypeError('Expected resource options to be a ResourceOptions instance')
         if opts.id is None:
             if __props__ is not None:
                 raise TypeError('__props__ is only valid when passed in combination with a valid opts.id to get an existing resource')
             __props__ = WorkitemArgs.__new__(WorkitemArgs)
 
+            __props__.__dict__["area_path"] = area_path
             __props__.__dict__["custom_fields"] = custom_fields
+            __props__.__dict__["iteration_path"] = iteration_path
             if project_id is None and not opts.urn:
                 raise TypeError("Missing required property 'project_id'")
             __props__.__dict__["project_id"] = project_id
             __props__.__dict__["state"] = state
             __props__.__dict__["tags"] = tags
             if title is None and not opts.urn:
                 raise TypeError("Missing required property 'title'")
@@ -387,55 +459,77 @@
             __props__,
             opts)
 
     @staticmethod
     def get(resource_name: str,
             id: pulumi.Input[str],
             opts: Optional[pulumi.ResourceOptions] = None,
+            area_path: Optional[pulumi.Input[str]] = None,
             custom_fields: Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]] = None,
+            iteration_path: Optional[pulumi.Input[str]] = None,
             project_id: Optional[pulumi.Input[str]] = None,
             state: Optional[pulumi.Input[str]] = None,
             tags: Optional[pulumi.Input[Sequence[pulumi.Input[str]]]] = None,
             title: Optional[pulumi.Input[str]] = None,
             type: Optional[pulumi.Input[str]] = None) -> 'Workitem':
         """
         Get an existing Workitem resource's state with the given name, id, and optional extra
         properties used to qualify the lookup.
 
         :param str resource_name: The unique name of the resulting resource.
         :param pulumi.Input[str] id: The unique provider ID of the resource to lookup.
         :param pulumi.ResourceOptions opts: Options for the resource.
+        :param pulumi.Input[str] area_path: Specifies the area where the Work Item is used.
         :param pulumi.Input[Mapping[str, pulumi.Input[str]]] custom_fields: Specifies a list with Custom Fields for the Work Item.
+        :param pulumi.Input[str] iteration_path: Specifies the iteration in which the Work Item is used.
         :param pulumi.Input[str] project_id: The ID of the Project.
         :param pulumi.Input[str] state: The state of the Work Item. The four main states that are defined for the User Story (`Agile`) are `New`, `Active`, `Resolved`, and `Closed`. See [Workflow states](https://learn.microsoft.com/en-us/azure/devops/boards/work-items/workflow-and-state-categories?view=azure-devops&tabs=agile-process#workflow-states) for more details.
         :param pulumi.Input[Sequence[pulumi.Input[str]]] tags: Specifies a list of Tags.
         :param pulumi.Input[str] title: The Title of the Work Item.
         :param pulumi.Input[str] type: The Type of the Work Item. The work item type varies depending on the process used when creating the project(`Agile`, `Basic`, `Scrum`, `Scrum`). See [Work Item Types](https://learn.microsoft.com/en-us/azure/devops/boards/work-items/about-work-items?view=azure-devops) for more details.
         """
         opts = pulumi.ResourceOptions.merge(opts, pulumi.ResourceOptions(id=id))
 
         __props__ = _WorkitemState.__new__(_WorkitemState)
 
+        __props__.__dict__["area_path"] = area_path
         __props__.__dict__["custom_fields"] = custom_fields
+        __props__.__dict__["iteration_path"] = iteration_path
         __props__.__dict__["project_id"] = project_id
         __props__.__dict__["state"] = state
         __props__.__dict__["tags"] = tags
         __props__.__dict__["title"] = title
         __props__.__dict__["type"] = type
         return Workitem(resource_name, opts=opts, __props__=__props__)
 
     @property
+    @pulumi.getter(name="areaPath")
+    def area_path(self) -> pulumi.Output[str]:
+        """
+        Specifies the area where the Work Item is used.
+        """
+        return pulumi.get(self, "area_path")
+
+    @property
     @pulumi.getter(name="customFields")
     def custom_fields(self) -> pulumi.Output[Optional[Mapping[str, str]]]:
         """
         Specifies a list with Custom Fields for the Work Item.
         """
         return pulumi.get(self, "custom_fields")
 
     @property
+    @pulumi.getter(name="iterationPath")
+    def iteration_path(self) -> pulumi.Output[str]:
+        """
+        Specifies the iteration in which the Work Item is used.
+        """
+        return pulumi.get(self, "iteration_path")
+
+    @property
     @pulumi.getter(name="projectId")
     def project_id(self) -> pulumi.Output[str]:
         """
         The ID of the Project.
         """
         return pulumi.get(self, "project_id")
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops.egg-info/PKG-INFO` & `pulumi_azuredevops-2.9.0a1687903032/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
-Name: pulumi-azuredevops
-Version: 2.8.0a1683661270
+Name: pulumi_azuredevops
+Version: 2.9.0a1687903032
 Summary: A Pulumi package for creating and managing Azure DevOps.
 Home-page: https://pulumi.io
 License: Apache-2.0
 Project-URL: Repository, https://github.com/pulumi/pulumi-azuredevops
 Keywords: pulumi azuredevops
 Platform: UNKNOWN
 Requires-Python: >=3.7
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/pulumi_azuredevops.egg-info/SOURCES.txt` & `pulumi_azuredevops-2.9.0a1687903032/pulumi_azuredevops.egg-info/SOURCES.txt`

 * *Files 2% similar despite different names*

```diff
@@ -11,14 +11,15 @@
 pulumi_azuredevops/branch_policy_min_reviewers.py
 pulumi_azuredevops/branch_policy_status_check.py
 pulumi_azuredevops/branch_policy_work_item_linking.py
 pulumi_azuredevops/build_definition.py
 pulumi_azuredevops/build_definition_permissions.py
 pulumi_azuredevops/build_folder.py
 pulumi_azuredevops/build_folder_permissions.py
+pulumi_azuredevops/check_approval.py
 pulumi_azuredevops/check_branch_control.py
 pulumi_azuredevops/check_business_hours.py
 pulumi_azuredevops/environment.py
 pulumi_azuredevops/get_agent_queue.py
 pulumi_azuredevops/get_area.py
 pulumi_azuredevops/get_build_definition.py
 pulumi_azuredevops/get_client_config.py
@@ -29,26 +30,29 @@
 pulumi_azuredevops/get_pool.py
 pulumi_azuredevops/get_pools.py
 pulumi_azuredevops/get_project.py
 pulumi_azuredevops/get_projects.py
 pulumi_azuredevops/get_repositories.py
 pulumi_azuredevops/get_service_endpoint_azure_rm.py
 pulumi_azuredevops/get_service_endpoint_github.py
+pulumi_azuredevops/get_serviceendpoint_npm.py
+pulumi_azuredevops/get_serviceendpoint_sonarcloud.py
 pulumi_azuredevops/get_team.py
 pulumi_azuredevops/get_teams.py
 pulumi_azuredevops/get_users.py
 pulumi_azuredevops/get_variable_group.py
 pulumi_azuredevops/git.py
 pulumi_azuredevops/git_permissions.py
 pulumi_azuredevops/git_repository_branch.py
 pulumi_azuredevops/git_repository_file.py
 pulumi_azuredevops/group.py
 pulumi_azuredevops/group_membership.py
 pulumi_azuredevops/iterative_permissions.py
 pulumi_azuredevops/outputs.py
+pulumi_azuredevops/pipeline_authorization.py
 pulumi_azuredevops/pool.py
 pulumi_azuredevops/project.py
 pulumi_azuredevops/project_features.py
 pulumi_azuredevops/project_permissions.py
 pulumi_azuredevops/project_pipeline_settings.py
 pulumi_azuredevops/provider.py
 pulumi_azuredevops/pulumi-plugin.json
@@ -78,14 +82,15 @@
 pulumi_azuredevops/service_endpoint_pipeline.py
 pulumi_azuredevops/service_endpoint_service_fabric.py
 pulumi_azuredevops/service_endpoint_sonar_cloud.py
 pulumi_azuredevops/service_endpoint_sonar_qube.py
 pulumi_azuredevops/service_endpoint_ssh.py
 pulumi_azuredevops/serviceendpoint_argocd.py
 pulumi_azuredevops/serviceendpoint_externaltfs.py
+pulumi_azuredevops/serviceendpoint_gcp_terraform.py
 pulumi_azuredevops/serviceendpoint_incomingwebhook.py
 pulumi_azuredevops/serviceendpoint_jfrog_artifactory_v2.py
 pulumi_azuredevops/serviceendpoint_jfrog_distribution_v2.py
 pulumi_azuredevops/serviceendpoint_jfrog_platform_v2.py
 pulumi_azuredevops/serviceendpoint_jfrog_xray_v2.py
 pulumi_azuredevops/serviceendpoint_octopusdeploy.py
 pulumi_azuredevops/serviceendpoint_permissions.py
```

### Comparing `pulumi_azuredevops-2.8.0a1683661270/setup.py` & `pulumi_azuredevops-2.9.0a1687903032/setup.py`

 * *Files 3% similar despite different names*

```diff
@@ -4,16 +4,16 @@
 
 import errno
 from setuptools import setup, find_packages
 from setuptools.command.install import install
 from subprocess import check_call
 
 
-VERSION = "2.8.0a1683661270"
-PLUGIN_VERSION = "2.8.0-alpha.1683661270+aa6c7d3b"
+VERSION = "2.9.0a1687903032"
+PLUGIN_VERSION = "2.9.0-alpha.1687903032+7d8e5cbf"
 
 class InstallPluginCommand(install):
     def run(self):
         install.run(self)
         try:
             check_call(['pulumi', 'plugin', 'install', 'resource', 'azuredevops', PLUGIN_VERSION])
         except OSError as error:
```


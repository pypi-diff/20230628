# Comparing `tmp/python-semantic-release-8.0.0rc1.tar.gz` & `tmp/python-semantic-release-8.0.0rc2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "python-semantic-release-8.0.0rc1.tar", last modified: Sat Jun 17 14:18:59 2023, max compression
+gzip compressed data, was "python-semantic-release-8.0.0rc2.tar", last modified: Wed Jun 28 08:39:57 2023, max compression
```

## Comparing `python-semantic-release-8.0.0rc1.tar` & `python-semantic-release-8.0.0rc2.tar`

### file list

```diff
@@ -1,130 +1,130 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-17 14:18:59.933924 python-semantic-release-8.0.0rc1/
--rw-r--r--   0 root         (0) root         (0)      230 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/AUTHORS.rst
--rw-r--r--   0 root         (0) root         (0)     1084 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/LICENSE
--rw-r--r--   0 root         (0) root         (0)      153 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/MANIFEST.in
--rw-r--r--   0 root         (0) root         (0)     3111 2023-06-17 14:18:59.933924 python-semantic-release-8.0.0rc1/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)     2272 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/README.rst
--rw-r--r--   0 root         (0) root         (0)     4681 2023-06-17 14:18:52.000000 python-semantic-release-8.0.0rc1/pyproject.toml
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-17 14:18:59.917924 python-semantic-release-8.0.0rc1/python_semantic_release.egg-info/
--rw-r--r--   0 root         (0) root         (0)     3111 2023-06-17 14:18:59.000000 python-semantic-release-8.0.0rc1/python_semantic_release.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)     4221 2023-06-17 14:18:59.000000 python-semantic-release-8.0.0rc1/python_semantic_release.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-17 14:18:59.000000 python-semantic-release-8.0.0rc1/python_semantic_release.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)       95 2023-06-17 14:18:59.000000 python-semantic-release-8.0.0rc1/python_semantic_release.egg-info/entry_points.txt
--rw-r--r--   0 root         (0) root         (0)      598 2023-06-17 14:18:59.000000 python-semantic-release-8.0.0rc1/python_semantic_release.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)       23 2023-06-17 14:18:59.000000 python-semantic-release-8.0.0rc1/python_semantic_release.egg-info/top_level.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-17 14:18:59.917924 python-semantic-release-8.0.0rc1/semantic_release/
--rw-r--r--   0 root         (0) root         (0)     1090 2023-06-17 14:18:52.000000 python-semantic-release-8.0.0rc1/semantic_release/__init__.py
--rw-r--r--   0 root         (0) root         (0)      106 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/__main__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-17 14:18:59.917924 python-semantic-release-8.0.0rc1/semantic_release/changelog/
--rw-r--r--   0 root         (0) root         (0)      361 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/changelog/__init__.py
--rw-r--r--   0 root         (0) root         (0)      941 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/changelog/context.py
--rw-r--r--   0 root         (0) root         (0)     6470 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/changelog/release_history.py
--rw-r--r--   0 root         (0) root         (0)     4328 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/changelog/template.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-17 14:18:59.917924 python-semantic-release-8.0.0rc1/semantic_release/cli/
--rw-r--r--   0 root         (0) root         (0)      451 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/cli/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-17 14:18:59.921924 python-semantic-release-8.0.0rc1/semantic_release/cli/commands/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/cli/commands/__init__.py
--rw-r--r--   0 root         (0) root         (0)     3246 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/cli/commands/changelog.py
--rw-r--r--   0 root         (0) root         (0)     1448 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/cli/commands/generate_config.py
--rw-r--r--   0 root         (0) root         (0)     4978 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/cli/commands/main.py
--rw-r--r--   0 root         (0) root         (0)     1298 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/cli/commands/publish.py
--rw-r--r--   0 root         (0) root         (0)    18650 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/cli/commands/version.py
--rw-r--r--   0 root         (0) root         (0)      929 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/cli/common.py
--rw-r--r--   0 root         (0) root         (0)    13706 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/cli/config.py
--rw-r--r--   0 root         (0) root         (0)       39 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/cli/const.py
--rw-r--r--   0 root         (0) root         (0)     2105 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/cli/github_actions_output.py
--rw-r--r--   0 root         (0) root         (0)     2875 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/cli/masking_filter.py
--rw-r--r--   0 root         (0) root         (0)      935 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/cli/util.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-17 14:18:59.921924 python-semantic-release-8.0.0rc1/semantic_release/commit_parser/
--rw-r--r--   0 root         (0) root         (0)      884 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/commit_parser/__init__.py
--rw-r--r--   0 root         (0) root         (0)     2569 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/commit_parser/_base.py
--rw-r--r--   0 root         (0) root         (0)     4364 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/commit_parser/angular.py
--rw-r--r--   0 root         (0) root         (0)     3288 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/commit_parser/emoji.py
--rw-r--r--   0 root         (0) root         (0)     5713 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/commit_parser/scipy.py
--rw-r--r--   0 root         (0) root         (0)     3193 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/commit_parser/tag.py
--rw-r--r--   0 root         (0) root         (0)     1456 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/commit_parser/token.py
--rw-r--r--   0 root         (0) root         (0)      529 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/commit_parser/util.py
--rw-r--r--   0 root         (0) root         (0)      831 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/const.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-17 14:18:59.913924 python-semantic-release-8.0.0rc1/semantic_release/data/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-17 14:18:59.921924 python-semantic-release-8.0.0rc1/semantic_release/data/templates/
--rw-r--r--   0 root         (0) root         (0)     1059 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/data/templates/CHANGELOG.md.j2
--rw-r--r--   0 root         (0) root         (0)      465 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/data/templates/release_notes.md.j2
--rw-r--r--   0 root         (0) root         (0)     1020 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/enums.py
--rw-r--r--   0 root         (0) root         (0)      674 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/errors.py
--rw-r--r--   0 root         (0) root         (0)     4088 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/helpers.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-17 14:18:59.921924 python-semantic-release-8.0.0rc1/semantic_release/hvcs/
--rw-r--r--   0 root         (0) root         (0)      300 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/hvcs/__init__.py
--rw-r--r--   0 root         (0) root         (0)     5579 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/hvcs/_base.py
--rw-r--r--   0 root         (0) root         (0)     8285 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/hvcs/gitea.py
--rw-r--r--   0 root         (0) root         (0)    10154 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/hvcs/github.py
--rw-r--r--   0 root         (0) root         (0)     5029 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/hvcs/gitlab.py
--rw-r--r--   0 root         (0) root         (0)      681 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/hvcs/token_auth.py
--rw-r--r--   0 root         (0) root         (0)     2774 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/hvcs/util.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-17 14:18:59.925924 python-semantic-release-8.0.0rc1/semantic_release/version/
--rw-r--r--   0 root         (0) root         (0)      339 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/version/__init__.py
--rw-r--r--   0 root         (0) root         (0)    14177 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/version/algorithm.py
--rw-r--r--   0 root         (0) root         (0)     7267 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/version/declaration.py
--rw-r--r--   0 root         (0) root         (0)     3103 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/version/translator.py
--rw-r--r--   0 root         (0) root         (0)    14060 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/semantic_release/version/version.py
--rw-r--r--   0 root         (0) root         (0)       38 2023-06-17 14:18:59.933924 python-semantic-release-8.0.0rc1/setup.cfg
--rw-r--r--   0 root         (0) root         (0)      466 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/setup.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-17 14:18:59.913924 python-semantic-release-8.0.0rc1/tests/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-17 14:18:59.925924 python-semantic-release-8.0.0rc1/tests/command_line/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/command_line/__init__.py
--rw-r--r--   0 root         (0) root         (0)      190 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/command_line/conftest.py
--rw-r--r--   0 root         (0) root         (0)     5707 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/command_line/test_changelog.py
--rw-r--r--   0 root         (0) root         (0)     1320 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/command_line/test_generate_config.py
--rw-r--r--   0 root         (0) root         (0)      641 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/command_line/test_help.py
--rw-r--r--   0 root         (0) root         (0)     1167 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/command_line/test_main.py
--rw-r--r--   0 root         (0) root         (0)     1430 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/command_line/test_publish.py
--rw-r--r--   0 root         (0) root         (0)    20288 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/command_line/test_version.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-17 14:18:59.925924 python-semantic-release-8.0.0rc1/tests/fixtures/
--rw-r--r--   0 root         (0) root         (0)      106 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/fixtures/__init__.py
--rw-r--r--   0 root         (0) root         (0)      906 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/fixtures/commit_parsers.py
--rw-r--r--   0 root         (0) root         (0)     2235 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/fixtures/example_project.py
--rw-r--r--   0 root         (0) root         (0)    45283 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/fixtures/git_repo.py
--rw-r--r--   0 root         (0) root         (0)     4424 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/fixtures/scipy.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-17 14:18:59.925924 python-semantic-release-8.0.0rc1/tests/scenario/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/scenario/__init__.py
--rw-r--r--   0 root         (0) root         (0)    46838 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/scenario/test_next_version.py
--rw-r--r--   0 root         (0) root         (0)    12186 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/scenario/test_release_history.py
--rw-r--r--   0 root         (0) root         (0)     3513 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/scenario/test_template_render.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-17 14:18:59.925924 python-semantic-release-8.0.0rc1/tests/unit/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/unit/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-17 14:18:59.925924 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-17 14:18:59.929924 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/changelog/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/changelog/__init__.py
--rw-r--r--   0 root         (0) root         (0)     5005 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/changelog/test_changelog_context.py
--rw-r--r--   0 root         (0) root         (0)     2540 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/changelog/test_default_changelog.py
--rw-r--r--   0 root         (0) root         (0)     1747 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/changelog/test_release_notes.py
--rw-r--r--   0 root         (0) root         (0)     2102 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/changelog/test_template.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-17 14:18:59.929924 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/cli/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/cli/__init__.py
--rw-r--r--   0 root         (0) root         (0)     1709 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/cli/test_config.py
--rw-r--r--   0 root         (0) root         (0)     1784 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/cli/test_github_actions_output.py
--rw-r--r--   0 root         (0) root         (0)     5768 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/cli/test_masking_filter.py
--rw-r--r--   0 root         (0) root         (0)      799 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/cli/test_version.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-17 14:18:59.929924 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/commit_parser/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/commit_parser/__init__.py
--rw-r--r--   0 root         (0) root         (0)      140 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/commit_parser/helper.py
--rw-r--r--   0 root         (0) root         (0)     5969 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/commit_parser/test_angular.py
--rw-r--r--   0 root         (0) root         (0)     2487 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/commit_parser/test_emoji.py
--rw-r--r--   0 root         (0) root         (0)      500 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/commit_parser/test_scipy.py
--rw-r--r--   0 root         (0) root         (0)     2173 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/commit_parser/test_tag.py
--rw-r--r--   0 root         (0) root         (0)      648 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/commit_parser/test_token.py
--rw-r--r--   0 root         (0) root         (0)      442 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/commit_parser/test_util.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-17 14:18:59.933924 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/hvcs/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/hvcs/__init__.py
--rw-r--r--   0 root         (0) root         (0)     1349 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/hvcs/test__base.py
--rw-r--r--   0 root         (0) root         (0)    22874 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/hvcs/test_gitea.py
--rw-r--r--   0 root         (0) root         (0)    24334 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/hvcs/test_github.py
--rw-r--r--   0 root         (0) root         (0)    10021 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/hvcs/test_gitlab.py
--rw-r--r--   0 root         (0) root         (0)      965 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/hvcs/test_token_auth.py
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/hvcs/test_util.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-17 14:18:59.933924 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/version/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/version/__init__.py
--rw-r--r--   0 root         (0) root         (0)     7319 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/version/test_algorithm.py
--rw-r--r--   0 root         (0) root         (0)     3715 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/version/test_declaration.py
--rw-r--r--   0 root         (0) root         (0)     2996 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/version/test_translator.py
--rw-r--r--   0 root         (0) root         (0)     9640 2023-06-17 14:18:03.000000 python-semantic-release-8.0.0rc1/tests/unit/semantic_release/version/test_version.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 08:39:57.636877 python-semantic-release-8.0.0rc2/
+-rw-r--r--   0 root         (0) root         (0)      230 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/AUTHORS.rst
+-rw-r--r--   0 root         (0) root         (0)     1084 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/LICENSE
+-rw-r--r--   0 root         (0) root         (0)      153 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/MANIFEST.in
+-rw-r--r--   0 root         (0) root         (0)     3111 2023-06-28 08:39:57.636877 python-semantic-release-8.0.0rc2/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     2272 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/README.rst
+-rw-r--r--   0 root         (0) root         (0)     4681 2023-06-28 08:39:49.000000 python-semantic-release-8.0.0rc2/pyproject.toml
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 08:39:57.624876 python-semantic-release-8.0.0rc2/python_semantic_release.egg-info/
+-rw-r--r--   0 root         (0) root         (0)     3111 2023-06-28 08:39:57.000000 python-semantic-release-8.0.0rc2/python_semantic_release.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     4221 2023-06-28 08:39:57.000000 python-semantic-release-8.0.0rc2/python_semantic_release.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 08:39:57.000000 python-semantic-release-8.0.0rc2/python_semantic_release.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)       95 2023-06-28 08:39:57.000000 python-semantic-release-8.0.0rc2/python_semantic_release.egg-info/entry_points.txt
+-rw-r--r--   0 root         (0) root         (0)      598 2023-06-28 08:39:57.000000 python-semantic-release-8.0.0rc2/python_semantic_release.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)       23 2023-06-28 08:39:57.000000 python-semantic-release-8.0.0rc2/python_semantic_release.egg-info/top_level.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 08:39:57.624876 python-semantic-release-8.0.0rc2/semantic_release/
+-rw-r--r--   0 root         (0) root         (0)     1090 2023-06-28 08:39:49.000000 python-semantic-release-8.0.0rc2/semantic_release/__init__.py
+-rw-r--r--   0 root         (0) root         (0)      106 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/__main__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 08:39:57.624876 python-semantic-release-8.0.0rc2/semantic_release/changelog/
+-rw-r--r--   0 root         (0) root         (0)      361 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/changelog/__init__.py
+-rw-r--r--   0 root         (0) root         (0)      941 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/changelog/context.py
+-rw-r--r--   0 root         (0) root         (0)     6470 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/changelog/release_history.py
+-rw-r--r--   0 root         (0) root         (0)     4328 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/changelog/template.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 08:39:57.624876 python-semantic-release-8.0.0rc2/semantic_release/cli/
+-rw-r--r--   0 root         (0) root         (0)      451 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/cli/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 08:39:57.628877 python-semantic-release-8.0.0rc2/semantic_release/cli/commands/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/cli/commands/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     3246 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/cli/commands/changelog.py
+-rw-r--r--   0 root         (0) root         (0)     1448 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/cli/commands/generate_config.py
+-rw-r--r--   0 root         (0) root         (0)     4978 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/cli/commands/main.py
+-rw-r--r--   0 root         (0) root         (0)     1298 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/cli/commands/publish.py
+-rw-r--r--   0 root         (0) root         (0)    18649 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/cli/commands/version.py
+-rw-r--r--   0 root         (0) root         (0)      929 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/cli/common.py
+-rw-r--r--   0 root         (0) root         (0)    13706 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/cli/config.py
+-rw-r--r--   0 root         (0) root         (0)       39 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/cli/const.py
+-rw-r--r--   0 root         (0) root         (0)     2105 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/cli/github_actions_output.py
+-rw-r--r--   0 root         (0) root         (0)     2875 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/cli/masking_filter.py
+-rw-r--r--   0 root         (0) root         (0)      935 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/cli/util.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 08:39:57.628877 python-semantic-release-8.0.0rc2/semantic_release/commit_parser/
+-rw-r--r--   0 root         (0) root         (0)      884 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/commit_parser/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     2569 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/commit_parser/_base.py
+-rw-r--r--   0 root         (0) root         (0)     4364 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/commit_parser/angular.py
+-rw-r--r--   0 root         (0) root         (0)     3288 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/commit_parser/emoji.py
+-rw-r--r--   0 root         (0) root         (0)     5713 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/commit_parser/scipy.py
+-rw-r--r--   0 root         (0) root         (0)     3193 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/commit_parser/tag.py
+-rw-r--r--   0 root         (0) root         (0)     1456 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/commit_parser/token.py
+-rw-r--r--   0 root         (0) root         (0)      529 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/commit_parser/util.py
+-rw-r--r--   0 root         (0) root         (0)      831 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/const.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 08:39:57.620876 python-semantic-release-8.0.0rc2/semantic_release/data/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 08:39:57.628877 python-semantic-release-8.0.0rc2/semantic_release/data/templates/
+-rw-r--r--   0 root         (0) root         (0)     1059 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/data/templates/CHANGELOG.md.j2
+-rw-r--r--   0 root         (0) root         (0)      465 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/data/templates/release_notes.md.j2
+-rw-r--r--   0 root         (0) root         (0)     1020 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/enums.py
+-rw-r--r--   0 root         (0) root         (0)      674 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/errors.py
+-rw-r--r--   0 root         (0) root         (0)     4088 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/helpers.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 08:39:57.628877 python-semantic-release-8.0.0rc2/semantic_release/hvcs/
+-rw-r--r--   0 root         (0) root         (0)      300 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/hvcs/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     5579 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/hvcs/_base.py
+-rw-r--r--   0 root         (0) root         (0)     8285 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/hvcs/gitea.py
+-rw-r--r--   0 root         (0) root         (0)    10154 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/hvcs/github.py
+-rw-r--r--   0 root         (0) root         (0)     5029 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/hvcs/gitlab.py
+-rw-r--r--   0 root         (0) root         (0)      681 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/hvcs/token_auth.py
+-rw-r--r--   0 root         (0) root         (0)     2774 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/hvcs/util.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 08:39:57.628877 python-semantic-release-8.0.0rc2/semantic_release/version/
+-rw-r--r--   0 root         (0) root         (0)      339 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/version/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    14177 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/version/algorithm.py
+-rw-r--r--   0 root         (0) root         (0)     7267 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/version/declaration.py
+-rw-r--r--   0 root         (0) root         (0)     3103 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/version/translator.py
+-rw-r--r--   0 root         (0) root         (0)    14060 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/semantic_release/version/version.py
+-rw-r--r--   0 root         (0) root         (0)       38 2023-06-28 08:39:57.636877 python-semantic-release-8.0.0rc2/setup.cfg
+-rw-r--r--   0 root         (0) root         (0)      466 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 08:39:57.620876 python-semantic-release-8.0.0rc2/tests/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 08:39:57.632877 python-semantic-release-8.0.0rc2/tests/command_line/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/command_line/__init__.py
+-rw-r--r--   0 root         (0) root         (0)      190 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/command_line/conftest.py
+-rw-r--r--   0 root         (0) root         (0)     5707 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/command_line/test_changelog.py
+-rw-r--r--   0 root         (0) root         (0)     1320 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/command_line/test_generate_config.py
+-rw-r--r--   0 root         (0) root         (0)      641 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/command_line/test_help.py
+-rw-r--r--   0 root         (0) root         (0)     1167 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/command_line/test_main.py
+-rw-r--r--   0 root         (0) root         (0)     1430 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/command_line/test_publish.py
+-rw-r--r--   0 root         (0) root         (0)    20288 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/command_line/test_version.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 08:39:57.632877 python-semantic-release-8.0.0rc2/tests/fixtures/
+-rw-r--r--   0 root         (0) root         (0)      106 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/fixtures/__init__.py
+-rw-r--r--   0 root         (0) root         (0)      906 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/fixtures/commit_parsers.py
+-rw-r--r--   0 root         (0) root         (0)     2235 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/fixtures/example_project.py
+-rw-r--r--   0 root         (0) root         (0)    45283 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/fixtures/git_repo.py
+-rw-r--r--   0 root         (0) root         (0)     4424 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/fixtures/scipy.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 08:39:57.632877 python-semantic-release-8.0.0rc2/tests/scenario/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/scenario/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    46838 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/scenario/test_next_version.py
+-rw-r--r--   0 root         (0) root         (0)    12186 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/scenario/test_release_history.py
+-rw-r--r--   0 root         (0) root         (0)     3513 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/scenario/test_template_render.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 08:39:57.632877 python-semantic-release-8.0.0rc2/tests/unit/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/unit/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 08:39:57.632877 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 08:39:57.632877 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/changelog/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/changelog/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     5005 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/changelog/test_changelog_context.py
+-rw-r--r--   0 root         (0) root         (0)     2540 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/changelog/test_default_changelog.py
+-rw-r--r--   0 root         (0) root         (0)     1747 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/changelog/test_release_notes.py
+-rw-r--r--   0 root         (0) root         (0)     2102 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/changelog/test_template.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 08:39:57.632877 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/cli/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/cli/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     1709 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/cli/test_config.py
+-rw-r--r--   0 root         (0) root         (0)     1784 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/cli/test_github_actions_output.py
+-rw-r--r--   0 root         (0) root         (0)     5768 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/cli/test_masking_filter.py
+-rw-r--r--   0 root         (0) root         (0)      799 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/cli/test_version.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 08:39:57.636877 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/commit_parser/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/commit_parser/__init__.py
+-rw-r--r--   0 root         (0) root         (0)      140 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/commit_parser/helper.py
+-rw-r--r--   0 root         (0) root         (0)     5969 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/commit_parser/test_angular.py
+-rw-r--r--   0 root         (0) root         (0)     2487 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/commit_parser/test_emoji.py
+-rw-r--r--   0 root         (0) root         (0)      500 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/commit_parser/test_scipy.py
+-rw-r--r--   0 root         (0) root         (0)     2173 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/commit_parser/test_tag.py
+-rw-r--r--   0 root         (0) root         (0)      648 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/commit_parser/test_token.py
+-rw-r--r--   0 root         (0) root         (0)      442 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/commit_parser/test_util.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 08:39:57.636877 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/hvcs/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/hvcs/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     1349 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/hvcs/test__base.py
+-rw-r--r--   0 root         (0) root         (0)    22874 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/hvcs/test_gitea.py
+-rw-r--r--   0 root         (0) root         (0)    24334 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/hvcs/test_github.py
+-rw-r--r--   0 root         (0) root         (0)    10021 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/hvcs/test_gitlab.py
+-rw-r--r--   0 root         (0) root         (0)      965 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/hvcs/test_token_auth.py
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/hvcs/test_util.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 08:39:57.636877 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/version/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/version/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     7319 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/version/test_algorithm.py
+-rw-r--r--   0 root         (0) root         (0)     3715 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/version/test_declaration.py
+-rw-r--r--   0 root         (0) root         (0)     2996 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/version/test_translator.py
+-rw-r--r--   0 root         (0) root         (0)     9640 2023-06-28 08:38:57.000000 python-semantic-release-8.0.0rc2/tests/unit/semantic_release/version/test_version.py
```

### Comparing `python-semantic-release-8.0.0rc1/LICENSE` & `python-semantic-release-8.0.0rc2/LICENSE`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/PKG-INFO` & `python-semantic-release-8.0.0rc2/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: python-semantic-release
-Version: 8.0.0rc1
+Version: 8.0.0rc2
 Summary: Automatic Semantic Versioning for Python projects
 Author-email: Rolf Erik Lekang <me@rolflekang.com>
 License: MIT
 Project-URL: Project Url, http://github.com/python-semantic-release/python-semantic-release
 Project-URL: Homepage, https://python-semantic-release.readthedocs.io
 Classifier: Programming Language :: Python
 Classifier: Programming Language :: Python :: 3
```

### Comparing `python-semantic-release-8.0.0rc1/README.rst` & `python-semantic-release-8.0.0rc2/README.rst`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/pyproject.toml` & `python-semantic-release-8.0.0rc2/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -2,15 +2,15 @@
 # and https://setuptools.pypa.io/en/latest/userguide/pyproject_config.html
 [build-system]
 requires = ["setuptools>=61.0.0", "wheel"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "python-semantic-release"
-version = "8.0.0-rc.1"
+version = "8.0.0-rc.2"
 description = "Automatic Semantic Versioning for Python projects"
 requires-python = ">=3.7"
 license = { text = "MIT" }
 classifiers = [
   "Programming Language :: Python",
   "Programming Language :: Python :: 3",
   "Programming Language :: Python :: 3.7",
```

### Comparing `python-semantic-release-8.0.0rc1/python_semantic_release.egg-info/PKG-INFO` & `python-semantic-release-8.0.0rc2/python_semantic_release.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: python-semantic-release
-Version: 8.0.0rc1
+Version: 8.0.0rc2
 Summary: Automatic Semantic Versioning for Python projects
 Author-email: Rolf Erik Lekang <me@rolflekang.com>
 License: MIT
 Project-URL: Project Url, http://github.com/python-semantic-release/python-semantic-release
 Project-URL: Homepage, https://python-semantic-release.readthedocs.io
 Classifier: Programming Language :: Python
 Classifier: Programming Language :: Python :: 3
```

### Comparing `python-semantic-release-8.0.0rc1/python_semantic_release.egg-info/SOURCES.txt` & `python-semantic-release-8.0.0rc2/python_semantic_release.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/python_semantic_release.egg-info/requires.txt` & `python-semantic-release-8.0.0rc2/python_semantic_release.egg-info/requires.txt`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/__init__.py` & `python-semantic-release-8.0.0rc2/semantic_release/__init__.py`

 * *Files 0% similar despite different names*

```diff
@@ -19,15 +19,15 @@
 from semantic_release.version import (
     Version as Version,
     VersionTranslator as VersionTranslator,
     next_version as next_version,
     tags_and_versions as tags_and_versions,
 )
 
-__version__ = "8.0.0-rc.1"
+__version__ = "8.0.0-rc.2"
 
 
 def setup_hook(argv: list[str]) -> None:
     """
     A hook to be used in setup.py to enable `python setup.py publish`.
 
     :param argv: sys.argv
```

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/changelog/context.py` & `python-semantic-release-8.0.0rc2/semantic_release/changelog/context.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/changelog/release_history.py` & `python-semantic-release-8.0.0rc2/semantic_release/changelog/release_history.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/changelog/template.py` & `python-semantic-release-8.0.0rc2/semantic_release/changelog/template.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/cli/commands/changelog.py` & `python-semantic-release-8.0.0rc2/semantic_release/cli/commands/changelog.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/cli/commands/generate_config.py` & `python-semantic-release-8.0.0rc2/semantic_release/cli/commands/generate_config.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/cli/commands/main.py` & `python-semantic-release-8.0.0rc2/semantic_release/cli/commands/main.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/cli/commands/publish.py` & `python-semantic-release-8.0.0rc2/semantic_release/cli/commands/publish.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/cli/commands/version.py` & `python-semantic-release-8.0.0rc2/semantic_release/cli/commands/version.py`

 * *Files 0% similar despite different names*

```diff
@@ -226,16 +226,14 @@
     commit_author = runtime.commit_author
     commit_message = runtime.commit_message
     major_on_zero = runtime.major_on_zero
     build_command = runtime.build_command
     opts = runtime.global_cli_options
     gha_output = VersionGitHubActionsOutput()
 
-    ctx.call_on_close(gha_output.write_if_possible)
-
     if prerelease_token:
         log.info("Forcing use of %s as the prerelease token", prerelease_token)
         translator.prerelease_token = prerelease_token
 
     # Only push if we're committing changes
     if push_changes and not commit_changes:
         log.info("changes will not be pushed because --no-commit disables pushing")
@@ -282,14 +280,15 @@
         )
 
     if build_metadata:
         new_version.build_metadata = build_metadata
 
     gha_output.released = False
     gha_output.version = new_version
+    ctx.call_on_close(gha_output.write_if_possible)
 
     # Print the new version so that command-line output capture will work
     click.echo(str(new_version))
 
     # If the new version has already been released, we fail and abort if strict;
     # otherwise we exit with 0.
     if new_version in {v for _, v in tags_and_versions(repo.tags, translator)}:
```

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/cli/common.py` & `python-semantic-release-8.0.0rc2/semantic_release/cli/common.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/cli/config.py` & `python-semantic-release-8.0.0rc2/semantic_release/cli/config.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/cli/github_actions_output.py` & `python-semantic-release-8.0.0rc2/semantic_release/cli/github_actions_output.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/cli/masking_filter.py` & `python-semantic-release-8.0.0rc2/semantic_release/cli/masking_filter.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/cli/util.py` & `python-semantic-release-8.0.0rc2/semantic_release/cli/util.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/commit_parser/__init__.py` & `python-semantic-release-8.0.0rc2/semantic_release/commit_parser/__init__.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/commit_parser/_base.py` & `python-semantic-release-8.0.0rc2/semantic_release/commit_parser/_base.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/commit_parser/angular.py` & `python-semantic-release-8.0.0rc2/semantic_release/commit_parser/angular.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/commit_parser/emoji.py` & `python-semantic-release-8.0.0rc2/semantic_release/commit_parser/emoji.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/commit_parser/scipy.py` & `python-semantic-release-8.0.0rc2/semantic_release/commit_parser/scipy.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/commit_parser/tag.py` & `python-semantic-release-8.0.0rc2/semantic_release/commit_parser/tag.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/commit_parser/token.py` & `python-semantic-release-8.0.0rc2/semantic_release/commit_parser/token.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/commit_parser/util.py` & `python-semantic-release-8.0.0rc2/semantic_release/commit_parser/util.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/const.py` & `python-semantic-release-8.0.0rc2/semantic_release/const.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/data/templates/CHANGELOG.md.j2` & `python-semantic-release-8.0.0rc2/semantic_release/data/templates/CHANGELOG.md.j2`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/enums.py` & `python-semantic-release-8.0.0rc2/semantic_release/enums.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/errors.py` & `python-semantic-release-8.0.0rc2/semantic_release/errors.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/helpers.py` & `python-semantic-release-8.0.0rc2/semantic_release/helpers.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/hvcs/_base.py` & `python-semantic-release-8.0.0rc2/semantic_release/hvcs/_base.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/hvcs/gitea.py` & `python-semantic-release-8.0.0rc2/semantic_release/hvcs/gitea.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/hvcs/github.py` & `python-semantic-release-8.0.0rc2/semantic_release/hvcs/github.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/hvcs/gitlab.py` & `python-semantic-release-8.0.0rc2/semantic_release/hvcs/gitlab.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/hvcs/token_auth.py` & `python-semantic-release-8.0.0rc2/semantic_release/hvcs/token_auth.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/hvcs/util.py` & `python-semantic-release-8.0.0rc2/semantic_release/hvcs/util.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/version/algorithm.py` & `python-semantic-release-8.0.0rc2/semantic_release/version/algorithm.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/version/declaration.py` & `python-semantic-release-8.0.0rc2/semantic_release/version/declaration.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/version/translator.py` & `python-semantic-release-8.0.0rc2/semantic_release/version/translator.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/semantic_release/version/version.py` & `python-semantic-release-8.0.0rc2/semantic_release/version/version.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/command_line/test_changelog.py` & `python-semantic-release-8.0.0rc2/tests/command_line/test_changelog.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/command_line/test_generate_config.py` & `python-semantic-release-8.0.0rc2/tests/command_line/test_generate_config.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/command_line/test_help.py` & `python-semantic-release-8.0.0rc2/tests/command_line/test_help.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/command_line/test_main.py` & `python-semantic-release-8.0.0rc2/tests/command_line/test_main.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/command_line/test_publish.py` & `python-semantic-release-8.0.0rc2/tests/command_line/test_publish.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/command_line/test_version.py` & `python-semantic-release-8.0.0rc2/tests/command_line/test_version.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/fixtures/commit_parsers.py` & `python-semantic-release-8.0.0rc2/tests/fixtures/commit_parsers.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/fixtures/example_project.py` & `python-semantic-release-8.0.0rc2/tests/fixtures/example_project.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/fixtures/git_repo.py` & `python-semantic-release-8.0.0rc2/tests/fixtures/git_repo.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/fixtures/scipy.py` & `python-semantic-release-8.0.0rc2/tests/fixtures/scipy.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/scenario/test_next_version.py` & `python-semantic-release-8.0.0rc2/tests/scenario/test_next_version.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/scenario/test_release_history.py` & `python-semantic-release-8.0.0rc2/tests/scenario/test_release_history.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/scenario/test_template_render.py` & `python-semantic-release-8.0.0rc2/tests/scenario/test_template_render.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/unit/semantic_release/changelog/test_changelog_context.py` & `python-semantic-release-8.0.0rc2/tests/unit/semantic_release/changelog/test_changelog_context.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/unit/semantic_release/changelog/test_default_changelog.py` & `python-semantic-release-8.0.0rc2/tests/unit/semantic_release/changelog/test_default_changelog.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/unit/semantic_release/changelog/test_release_notes.py` & `python-semantic-release-8.0.0rc2/tests/unit/semantic_release/changelog/test_release_notes.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/unit/semantic_release/changelog/test_template.py` & `python-semantic-release-8.0.0rc2/tests/unit/semantic_release/changelog/test_template.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/unit/semantic_release/cli/test_config.py` & `python-semantic-release-8.0.0rc2/tests/unit/semantic_release/cli/test_config.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/unit/semantic_release/cli/test_github_actions_output.py` & `python-semantic-release-8.0.0rc2/tests/unit/semantic_release/cli/test_github_actions_output.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/unit/semantic_release/cli/test_masking_filter.py` & `python-semantic-release-8.0.0rc2/tests/unit/semantic_release/cli/test_masking_filter.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/unit/semantic_release/cli/test_version.py` & `python-semantic-release-8.0.0rc2/tests/unit/semantic_release/cli/test_version.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/unit/semantic_release/commit_parser/test_angular.py` & `python-semantic-release-8.0.0rc2/tests/unit/semantic_release/commit_parser/test_angular.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/unit/semantic_release/commit_parser/test_emoji.py` & `python-semantic-release-8.0.0rc2/tests/unit/semantic_release/commit_parser/test_emoji.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/unit/semantic_release/commit_parser/test_tag.py` & `python-semantic-release-8.0.0rc2/tests/unit/semantic_release/commit_parser/test_tag.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/unit/semantic_release/commit_parser/test_token.py` & `python-semantic-release-8.0.0rc2/tests/unit/semantic_release/commit_parser/test_token.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/unit/semantic_release/hvcs/test__base.py` & `python-semantic-release-8.0.0rc2/tests/unit/semantic_release/hvcs/test__base.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/unit/semantic_release/hvcs/test_gitea.py` & `python-semantic-release-8.0.0rc2/tests/unit/semantic_release/hvcs/test_gitea.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/unit/semantic_release/hvcs/test_github.py` & `python-semantic-release-8.0.0rc2/tests/unit/semantic_release/hvcs/test_github.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/unit/semantic_release/hvcs/test_gitlab.py` & `python-semantic-release-8.0.0rc2/tests/unit/semantic_release/hvcs/test_gitlab.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/unit/semantic_release/hvcs/test_token_auth.py` & `python-semantic-release-8.0.0rc2/tests/unit/semantic_release/hvcs/test_token_auth.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/unit/semantic_release/version/test_algorithm.py` & `python-semantic-release-8.0.0rc2/tests/unit/semantic_release/version/test_algorithm.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/unit/semantic_release/version/test_declaration.py` & `python-semantic-release-8.0.0rc2/tests/unit/semantic_release/version/test_declaration.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/unit/semantic_release/version/test_translator.py` & `python-semantic-release-8.0.0rc2/tests/unit/semantic_release/version/test_translator.py`

 * *Files identical despite different names*

### Comparing `python-semantic-release-8.0.0rc1/tests/unit/semantic_release/version/test_version.py` & `python-semantic-release-8.0.0rc2/tests/unit/semantic_release/version/test_version.py`

 * *Files identical despite different names*


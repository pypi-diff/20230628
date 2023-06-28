# Comparing `tmp/robotframework-tidy-4.3.0.tar.gz` & `tmp/robotframework-tidy-4.4.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "robotframework-tidy-4.3.0.tar", last modified: Tue May 30 10:41:57 2023, max compression
+gzip compressed data, was "robotframework-tidy-4.4.0.tar", last modified: Wed Jun 28 10:07:28 2023, max compression
```

## Comparing `robotframework-tidy-4.3.0.tar` & `robotframework-tidy-4.4.0.tar`

### file list

```diff
@@ -1,69 +1,69 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-30 10:41:57.145647 robotframework-tidy-4.3.0/
--rw-r--r--   0 runner    (1001) docker     (123)    11357 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)       28 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)     4190 2023-05-30 10:41:57.145647 robotframework-tidy-4.3.0/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2995 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       79 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/pyproject.toml
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-30 10:41:57.133647 robotframework-tidy-4.3.0/robotframework_tidy.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     4190 2023-05-30 10:41:57.000000 robotframework-tidy-4.3.0/robotframework_tidy.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2180 2023-05-30 10:41:57.000000 robotframework-tidy-4.3.0/robotframework_tidy.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-05-30 10:41:57.000000 robotframework-tidy-4.3.0/robotframework_tidy.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       46 2023-05-30 10:41:57.000000 robotframework-tidy-4.3.0/robotframework_tidy.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)      281 2023-05-30 10:41:57.000000 robotframework-tidy-4.3.0/robotframework_tidy.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)        9 2023-05-30 10:41:57.000000 robotframework-tidy-4.3.0/robotframework_tidy.egg-info/top_level.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-30 10:41:57.137647 robotframework-tidy-4.3.0/robotidy/
--rw-r--r--   0 runner    (1001) docker     (123)       68 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)       67 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/__main__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-30 10:41:57.137647 robotframework-tidy-4.3.0/robotidy/__pycache__/
--rw-r--r--   0 runner    (1001) docker     (123)      278 2023-05-30 10:41:56.000000 robotframework-tidy-4.3.0/robotidy/__pycache__/__init__.cpython-311.pyc
--rw-r--r--   0 runner    (1001) docker     (123)      206 2023-05-30 10:41:56.000000 robotframework-tidy-4.3.0/robotidy/__pycache__/version.cpython-311.pyc
--rw-r--r--   0 runner    (1001) docker     (123)     1959 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/api.py
--rw-r--r--   0 runner    (1001) docker     (123)     4839 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/app.py
--rw-r--r--   0 runner    (1001) docker     (123)    14328 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/cli.py
--rw-r--r--   0 runner    (1001) docker     (123)    15395 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/config.py
--rw-r--r--   0 runner    (1001) docker     (123)     1122 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/decorators.py
--rw-r--r--   0 runner    (1001) docker     (123)     6706 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/disablers.py
--rw-r--r--   0 runner    (1001) docker     (123)     1529 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/exceptions.py
--rw-r--r--   0 runner    (1001) docker     (123)     5490 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/files.py
--rw-r--r--   0 runner    (1001) docker     (123)      398 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/rich_console.py
--rw-r--r--   0 runner    (1001) docker     (123)     7280 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/skip.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-30 10:41:57.145647 robotframework-tidy-4.3.0/robotidy/transformers/
--rw-r--r--   0 runner    (1001) docker     (123)     5064 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/AddMissingEnd.py
--rw-r--r--   0 runner    (1001) docker     (123)     2345 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/AlignKeywordsSection.py
--rw-r--r--   0 runner    (1001) docker     (123)     6320 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/AlignSettingsSection.py
--rw-r--r--   0 runner    (1001) docker     (123)     7483 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/AlignTemplatedTestCases.py
--rw-r--r--   0 runner    (1001) docker     (123)     2537 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/AlignTestCasesSection.py
--rw-r--r--   0 runner    (1001) docker     (123)     5143 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/AlignVariablesSection.py
--rw-r--r--   0 runner    (1001) docker     (123)     1227 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/DiscardEmptySections.py
--rw-r--r--   0 runner    (1001) docker     (123)     6881 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/GenerateDocumentation.py
--rw-r--r--   0 runner    (1001) docker     (123)     9853 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/IndentNestedKeywords.py
--rw-r--r--   0 runner    (1001) docker     (123)    12649 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/InlineIf.py
--rw-r--r--   0 runner    (1001) docker     (123)     7673 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/MergeAndOrderSections.py
--rw-r--r--   0 runner    (1001) docker     (123)     6212 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/NormalizeAssignments.py
--rw-r--r--   0 runner    (1001) docker     (123)     1710 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/NormalizeComments.py
--rw-r--r--   0 runner    (1001) docker     (123)     5755 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/NormalizeNewLines.py
--rw-r--r--   0 runner    (1001) docker     (123)     2003 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/NormalizeSectionHeaderName.py
--rw-r--r--   0 runner    (1001) docker     (123)     8181 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/NormalizeSeparators.py
--rw-r--r--   0 runner    (1001) docker     (123)     1499 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/NormalizeSettingName.py
--rw-r--r--   0 runner    (1001) docker     (123)     4037 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/NormalizeTags.py
--rw-r--r--   0 runner    (1001) docker     (123)     8471 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/OrderSettings.py
--rw-r--r--   0 runner    (1001) docker     (123)     8834 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/OrderSettingsSection.py
--rw-r--r--   0 runner    (1001) docker     (123)     2951 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/OrderTags.py
--rw-r--r--   0 runner    (1001) docker     (123)     4175 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/RemoveEmptySettings.py
--rw-r--r--   0 runner    (1001) docker     (123)     8421 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/RenameKeywords.py
--rw-r--r--   0 runner    (1001) docker     (123)     3737 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/RenameTestCases.py
--rw-r--r--   0 runner    (1001) docker     (123)    17838 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/RenameVariables.py
--rw-r--r--   0 runner    (1001) docker     (123)     2773 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/ReplaceBreakContinue.py
--rw-r--r--   0 runner    (1001) docker     (123)     2219 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/ReplaceEmptyValues.py
--rw-r--r--   0 runner    (1001) docker     (123)     2856 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/ReplaceReturns.py
--rw-r--r--   0 runner    (1001) docker     (123)     6192 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/ReplaceRunKeywordIf.py
--rw-r--r--   0 runner    (1001) docker     (123)     2925 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/SmartSortKeywords.py
--rw-r--r--   0 runner    (1001) docker     (123)    12317 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/SplitTooLongLine.py
--rw-r--r--   0 runner    (1001) docker     (123)    10020 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/Translate.py
--rw-r--r--   0 runner    (1001) docker     (123)    19687 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    23065 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/aligners_core.py
--rw-r--r--   0 runner    (1001) docker     (123)     1812 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/transformers/run_keywords.py
--rw-r--r--   0 runner    (1001) docker     (123)    13951 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/utils.py
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/robotidy/version.py
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-05-30 10:41:57.145647 robotframework-tidy-4.3.0/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2099 2023-05-30 10:41:41.000000 robotframework-tidy-4.3.0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:07:28.299725 robotframework-tidy-4.4.0/
+-rw-r--r--   0 runner    (1001) docker     (123)    11357 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)     4190 2023-06-28 10:07:28.299725 robotframework-tidy-4.4.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2995 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       79 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/pyproject.toml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:07:28.291725 robotframework-tidy-4.4.0/robotframework_tidy.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     4190 2023-06-28 10:07:28.000000 robotframework-tidy-4.4.0/robotframework_tidy.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2180 2023-06-28 10:07:28.000000 robotframework-tidy-4.4.0/robotframework_tidy.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 10:07:28.000000 robotframework-tidy-4.4.0/robotframework_tidy.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       46 2023-06-28 10:07:28.000000 robotframework-tidy-4.4.0/robotframework_tidy.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      281 2023-06-28 10:07:28.000000 robotframework-tidy-4.4.0/robotframework_tidy.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-28 10:07:28.000000 robotframework-tidy-4.4.0/robotframework_tidy.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:07:28.295725 robotframework-tidy-4.4.0/robotidy/
+-rw-r--r--   0 runner    (1001) docker     (123)       68 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)       67 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/__main__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:07:28.295725 robotframework-tidy-4.4.0/robotidy/__pycache__/
+-rw-r--r--   0 runner    (1001) docker     (123)      278 2023-06-28 10:07:27.000000 robotframework-tidy-4.4.0/robotidy/__pycache__/__init__.cpython-311.pyc
+-rw-r--r--   0 runner    (1001) docker     (123)      206 2023-06-28 10:07:27.000000 robotframework-tidy-4.4.0/robotidy/__pycache__/version.cpython-311.pyc
+-rw-r--r--   0 runner    (1001) docker     (123)     1959 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4839 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/app.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14328 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/cli.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15395 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/config.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1122 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/decorators.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6706 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/disablers.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1529 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/exceptions.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5490 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/files.py
+-rw-r--r--   0 runner    (1001) docker     (123)      398 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/rich_console.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7280 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/skip.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:07:28.295725 robotframework-tidy-4.4.0/robotidy/transformers/
+-rw-r--r--   0 runner    (1001) docker     (123)     5064 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/AddMissingEnd.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2345 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/AlignKeywordsSection.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6320 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/AlignSettingsSection.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7483 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/AlignTemplatedTestCases.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2537 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/AlignTestCasesSection.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5143 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/AlignVariablesSection.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1227 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/DiscardEmptySections.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6881 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/GenerateDocumentation.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9853 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/IndentNestedKeywords.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12649 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/InlineIf.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7673 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/MergeAndOrderSections.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6212 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/NormalizeAssignments.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1710 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/NormalizeComments.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5755 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/NormalizeNewLines.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2003 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/NormalizeSectionHeaderName.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8181 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/NormalizeSeparators.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1499 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/NormalizeSettingName.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4037 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/NormalizeTags.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8471 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/OrderSettings.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8834 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/OrderSettingsSection.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2951 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/OrderTags.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4175 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/RemoveEmptySettings.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8474 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/RenameKeywords.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3998 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/RenameTestCases.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18367 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/RenameVariables.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2773 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/ReplaceBreakContinue.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2219 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/ReplaceEmptyValues.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2856 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/ReplaceReturns.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6192 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/ReplaceRunKeywordIf.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2925 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/SmartSortKeywords.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12317 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/SplitTooLongLine.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10020 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/Translate.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19687 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23065 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/aligners_core.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1812 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/transformers/run_keywords.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13951 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/robotidy/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 10:07:28.299725 robotframework-tidy-4.4.0/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2099 2023-06-28 10:07:15.000000 robotframework-tidy-4.4.0/setup.py
```

### Comparing `robotframework-tidy-4.3.0/LICENSE` & `robotframework-tidy-4.4.0/LICENSE`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/PKG-INFO` & `robotframework-tidy-4.4.0/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: robotframework-tidy
-Version: 4.3.0
+Version: 4.4.0
 Summary: Code autoformatter for Robot Framework
 Home-page: https://github.com/MarketSquare/robotframework-tidy
 Author: MarketSquare - Robot Framework community
 Author-email: bartek.hirsz@gmail.com
 License: Apache License 2.0
 Keywords: robotframework
 Platform: any
```

### Comparing `robotframework-tidy-4.3.0/README.md` & `robotframework-tidy-4.4.0/README.md`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotframework_tidy.egg-info/PKG-INFO` & `robotframework-tidy-4.4.0/robotframework_tidy.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: robotframework-tidy
-Version: 4.3.0
+Version: 4.4.0
 Summary: Code autoformatter for Robot Framework
 Home-page: https://github.com/MarketSquare/robotframework-tidy
 Author: MarketSquare - Robot Framework community
 Author-email: bartek.hirsz@gmail.com
 License: Apache License 2.0
 Keywords: robotframework
 Platform: any
```

### Comparing `robotframework-tidy-4.3.0/robotframework_tidy.egg-info/SOURCES.txt` & `robotframework-tidy-4.4.0/robotframework_tidy.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/api.py` & `robotframework-tidy-4.4.0/robotidy/api.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/app.py` & `robotframework-tidy-4.4.0/robotidy/app.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/cli.py` & `robotframework-tidy-4.4.0/robotidy/cli.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/config.py` & `robotframework-tidy-4.4.0/robotidy/config.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/decorators.py` & `robotframework-tidy-4.4.0/robotidy/decorators.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/disablers.py` & `robotframework-tidy-4.4.0/robotidy/disablers.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/exceptions.py` & `robotframework-tidy-4.4.0/robotidy/exceptions.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/files.py` & `robotframework-tidy-4.4.0/robotidy/files.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/skip.py` & `robotframework-tidy-4.4.0/robotidy/skip.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/AddMissingEnd.py` & `robotframework-tidy-4.4.0/robotidy/transformers/AddMissingEnd.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/AlignKeywordsSection.py` & `robotframework-tidy-4.4.0/robotidy/transformers/AlignKeywordsSection.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/AlignSettingsSection.py` & `robotframework-tidy-4.4.0/robotidy/transformers/AlignSettingsSection.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/AlignTemplatedTestCases.py` & `robotframework-tidy-4.4.0/robotidy/transformers/AlignTemplatedTestCases.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/AlignTestCasesSection.py` & `robotframework-tidy-4.4.0/robotidy/transformers/AlignTestCasesSection.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/AlignVariablesSection.py` & `robotframework-tidy-4.4.0/robotidy/transformers/AlignVariablesSection.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/DiscardEmptySections.py` & `robotframework-tidy-4.4.0/robotidy/transformers/DiscardEmptySections.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/GenerateDocumentation.py` & `robotframework-tidy-4.4.0/robotidy/transformers/GenerateDocumentation.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/IndentNestedKeywords.py` & `robotframework-tidy-4.4.0/robotidy/transformers/IndentNestedKeywords.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/InlineIf.py` & `robotframework-tidy-4.4.0/robotidy/transformers/InlineIf.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/MergeAndOrderSections.py` & `robotframework-tidy-4.4.0/robotidy/transformers/MergeAndOrderSections.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/NormalizeAssignments.py` & `robotframework-tidy-4.4.0/robotidy/transformers/NormalizeAssignments.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/NormalizeComments.py` & `robotframework-tidy-4.4.0/robotidy/transformers/NormalizeComments.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/NormalizeNewLines.py` & `robotframework-tidy-4.4.0/robotidy/transformers/NormalizeNewLines.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/NormalizeSectionHeaderName.py` & `robotframework-tidy-4.4.0/robotidy/transformers/NormalizeSectionHeaderName.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/NormalizeSeparators.py` & `robotframework-tidy-4.4.0/robotidy/transformers/NormalizeSeparators.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/NormalizeSettingName.py` & `robotframework-tidy-4.4.0/robotidy/transformers/NormalizeSettingName.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/NormalizeTags.py` & `robotframework-tidy-4.4.0/robotidy/transformers/NormalizeTags.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/OrderSettings.py` & `robotframework-tidy-4.4.0/robotidy/transformers/OrderSettings.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/OrderSettingsSection.py` & `robotframework-tidy-4.4.0/robotidy/transformers/OrderSettingsSection.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/OrderTags.py` & `robotframework-tidy-4.4.0/robotidy/transformers/OrderTags.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/RemoveEmptySettings.py` & `robotframework-tidy-4.4.0/robotidy/transformers/RemoveEmptySettings.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/RenameKeywords.py` & `robotframework-tidy-4.4.0/robotidy/transformers/RenameKeywords.py`

 * *Files 4% similar despite different names*

```diff
@@ -89,52 +89,57 @@
         return self.generic_visit(node)
 
     def rename_node(self, token, is_keyword_call):
         if self.replace_pattern is not None:
             new_value = self.rename_with_pattern(token.value, is_keyword_call=is_keyword_call)
         else:
             new_value = self.normalize_name(token.value, is_keyword_call=is_keyword_call)
-        if not new_value.strip():  # do not allow renames that removes keywords altogether
+        new_value = new_value.strip()
+        if not new_value:  # do not allow renaming that removes keywords altogether
             return
         token.value = new_value
 
     def normalize_name(self, value, is_keyword_call):
         var_found = False
         parts = []
-        new_name, remaining = "", ""
+        remaining = ""
         for prefix, match, remaining in VariableIterator(value, ignore_errors=True):
             var_found = True
             # rename strips whitespace, so we need to preserve it if needed
             if not prefix.strip() and parts:
                 parts.extend([" ", match])
             else:
-                leading_space = " " if prefix.startswith(" ") else ""
-                trailing_space = " " if prefix.endswith(" ") else ""
-                parts.extend([leading_space, self.rename_part(prefix, is_keyword_call), trailing_space, match])
+                parts.extend([self.rename_part(prefix, is_keyword_call), match])
         if var_found:
-            if remaining.startswith(" "):
-                parts.append(" ")
             parts.append(self.rename_part(remaining, is_keyword_call))
             return "".join(parts).strip()
         return self.rename_part(value, is_keyword_call)
 
     def rename_part(self, part: str, is_keyword_call: bool):
         if is_keyword_call and self.ignore_library:
             lib_name, *kw_name = part.rsplit(".", maxsplit=1)
             if not kw_name:
                 return self.remove_underscores_and_capitalize(part)
             return f"{lib_name}.{self.remove_underscores_and_capitalize(kw_name[0])}"
         return ".".join([self.remove_underscores_and_capitalize(name_part) for name_part in part.split(".")])
 
     def remove_underscores_and_capitalize(self, value: str):
         if self.remove_underscores:
-            value = re.sub("_+", " ", value)  # replace one or more _ with one space
-        value = value.strip()
+            value = value.replace("_", " ")
+            value = re.sub(r" +", " ", value)  # replace one or more spaces by one
+        words = []
+        split_words = value.split(" ")
         # capitalize first letter of every word, leave rest untouched
-        return "".join([a if a.isupper() else b for a, b in zip(value, string.capwords(value))])
+        for index, word in enumerate(split_words):
+            if not word:
+                if index in (0, len(split_words) - 1):  # leading and trailing whitespace
+                    words.append("")
+            else:
+                words.append(word[0].upper() + word[1:])
+        return " ".join(words)
 
     def rename_with_pattern(self, value: str, is_keyword_call: bool):
         lib_name = ""
         if is_keyword_call and "." in value:
             # rename only non lib part
             found_lib = -1
             for prefix, _, _ in VariableIterator(value):
```

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/RenameTestCases.py` & `robotframework-tidy-4.4.0/robotidy/transformers/RenameTestCases.py`

 * *Files 6% similar despite different names*

```diff
@@ -4,25 +4,30 @@
 
 from robot.api.parsing import Token
 
 from robotidy.disablers import skip_if_disabled, skip_section_if_disabled
 from robotidy.exceptions import InvalidParameterValueError
 from robotidy.transformers import Transformer
 
+IGNORE_CHARS = {"(", "[", "{", "!", "?"}
+
 
 def cap_string_until_succeed(word: str):
     """
     Yield characters from the word and capitalize character until we are able to make char uppercase.
     """
     capitalize = True
     for char in word:
         if capitalize:
-            char = char.upper()
-            if char.isupper():
+            # chars like numbers, -, dots, commas etc. will not change case, and we should not capitalize further
+            if char == char.upper() and char not in IGNORE_CHARS:
                 capitalize = False
+            else:
+                char = char.upper()
+                capitalize = not char.isupper()
         yield char
 
 
 def cap_word(word: str):
     """
     Capitalize the word. The word can start with ( or contain ':
```

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/RenameVariables.py` & `robotframework-tidy-4.4.0/robotidy/transformers/RenameVariables.py`

 * *Files 2% similar despite different names*

```diff
@@ -158,35 +158,38 @@
     ```
     """
 
     ENABLED = False
     HANDLES_SKIP = frozenset({"skip_sections"})
     MORE_THAN_2_SPACES: Pattern = re.compile(r"\s{2,}")
     CAMEL_CASE: Pattern = re.compile(r"((?<=[a-z0-9])[A-Z]|(?!^)[A-Z](?=[a-z]))")
+    DEFAULT_IGNORE_CASE = {"\\n"}
 
     def __init__(
         self,
         settings_section_case: str = "upper",
         variables_section_case: str = "upper",
         unknown_variables_case: str = "upper",
         variable_separator: str = "underscore",
         convert_camel_case: bool = True,
+        ignore_case: str = None,
         skip: Skip = None,
     ):
         super().__init__(skip)
         self.validate_case("settings_section_case", settings_section_case, ["upper", "lower", "ignore"])
         self.validate_case("variables_section_case", variables_section_case, ["upper", "lower", "ignore"])
         self.validate_case("unknown_variables_case", unknown_variables_case, ["upper", "lower", "ignore"])
         self.validate_variable_separator(variable_separator)
         self.settings_section_case = settings_section_case
         self.variables_section_case = variables_section_case
         self.unknown_variables_case = unknown_variables_case
         # we always convert to space, so we only need to check if we need to convert back to _
         self.replace_variable_separator = variable_separator == "underscore"
         self.convert_camel_case = convert_camel_case
+        self.ignore_case = self.get_ignored_variables_case(ignore_case)
         self.variables_scope = VariablesScope()
 
     def validate_case(self, param_name: str, case: str, allowed_case: List):
         if case not in allowed_case:
             case_types = ", ".join(allowed_case)
             raise InvalidParameterValueError(
                 self.__class__.__name__,
@@ -200,14 +203,20 @@
             raise InvalidParameterValueError(
                 self.__class__.__name__,
                 "variable_separator",
                 variable_separator,
                 "Allowed values are: underscore, space",
             )
 
+    def get_ignored_variables_case(self, ignore_vars):
+        if ignore_vars is None:
+            return self.DEFAULT_IGNORE_CASE
+        ignored_vars = set(ignore_vars.split(","))
+        return ignored_vars.union(self.DEFAULT_IGNORE_CASE)
+
     @skip_section_if_disabled
     def visit_Section(self, node):  # noqa
         return self.generic_visit(node)
 
     @skip_if_disabled
     def visit_LibraryImport(self, node):  # noqa
         for data_token in node.data_tokens[1:]:
@@ -404,14 +413,16 @@
             if is_var:
                 name += self.rename(remaining, case=variable_case, strip_fn="rstrip")
             else:
                 name += remaining
         return name
 
     def set_name_case(self, name: str, case: str):
+        if name in self.ignore_case:
+            return name
         if case == "upper":
             return name.upper()
         if case == "lower":
             return name.lower()
         if case == "auto":
             if self.variables_scope.is_local(name):
                 return name.lower()
@@ -423,26 +434,28 @@
     def rename(self, variable_value: str, case: str, strip_fn: str = "strip"):
         if not variable_value:
             return variable_value
         # split on variable attribute access like ${var['item']}, ${var.item}, ${var(method)}..
         variable_name, item_access = split_string_on_delimiter(variable_value)
         if self.convert_camel_case:
             variable_name = self.CAMEL_CASE.sub(r" \1", variable_name)
-        variable_name = self.set_name_case(variable_name, case)
         variable_name = variable_name.replace("_", " ")
         variable_name = self.MORE_THAN_2_SPACES.sub(" ", variable_name)
+        if variable_name == " ":  # ${ } or ${_}
+            return "_" + item_access
         # to handle cases like ${var_${variable}_} we need to only strip whitespace at start/end depending on the type
         if strip_fn == "strip":
             variable_name = variable_name.strip()
         elif strip_fn == "lstrip":
             variable_name = variable_name.lstrip()
         elif strip_fn == "rstrip":
             variable_name = variable_name.rstrip()
         if self.replace_variable_separator:
             variable_name = variable_name.replace(" ", "_")
+        variable_name = self.set_name_case(variable_name, case)
         return variable_name + item_access
 
 
 def split_string_on_delimiter(string: str) -> Tuple[str, str]:
     """
     Split string on first occurrence of the delimiters.
```

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/ReplaceBreakContinue.py` & `robotframework-tidy-4.4.0/robotidy/transformers/ReplaceBreakContinue.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/ReplaceEmptyValues.py` & `robotframework-tidy-4.4.0/robotidy/transformers/ReplaceEmptyValues.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/ReplaceReturns.py` & `robotframework-tidy-4.4.0/robotidy/transformers/ReplaceReturns.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/ReplaceRunKeywordIf.py` & `robotframework-tidy-4.4.0/robotidy/transformers/ReplaceRunKeywordIf.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/SmartSortKeywords.py` & `robotframework-tidy-4.4.0/robotidy/transformers/SmartSortKeywords.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/SplitTooLongLine.py` & `robotframework-tidy-4.4.0/robotidy/transformers/SplitTooLongLine.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/Translate.py` & `robotframework-tidy-4.4.0/robotidy/transformers/Translate.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/__init__.py` & `robotframework-tidy-4.4.0/robotidy/transformers/__init__.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/aligners_core.py` & `robotframework-tidy-4.4.0/robotidy/transformers/aligners_core.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/transformers/run_keywords.py` & `robotframework-tidy-4.4.0/robotidy/transformers/run_keywords.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/robotidy/utils.py` & `robotframework-tidy-4.4.0/robotidy/utils.py`

 * *Files identical despite different names*

### Comparing `robotframework-tidy-4.3.0/setup.py` & `robotframework-tidy-4.4.0/setup.py`

 * *Files identical despite different names*


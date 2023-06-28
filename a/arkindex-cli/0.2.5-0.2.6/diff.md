# Comparing `tmp/arkindex-cli-0.2.5.tar.gz` & `tmp/arkindex-cli-0.2.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "arkindex-cli-0.2.5.tar", last modified: Thu Apr 13 08:33:32 2023, max compression
+gzip compressed data, was "arkindex-cli-0.2.6.tar", last modified: Wed Jun 28 15:37:32 2023, max compression
```

## Comparing `arkindex-cli-0.2.5.tar` & `arkindex-cli-0.2.6.tar`

### file list

```diff
@@ -1,63 +1,67 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-04-13 08:33:32.660972 arkindex-cli-0.2.5/
--rw-rw-rw-   0 root         (0) root         (0)      104 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/MANIFEST.in
--rw-r--r--   0 root         (0) root         (0)     1343 2023-04-13 08:33:32.660972 arkindex-cli-0.2.5/PKG-INFO
--rw-rw-rw-   0 root         (0) root         (0)     1062 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/README.md
--rw-rw-rw-   0 root         (0) root         (0)        6 2023-04-13 08:30:48.000000 arkindex-cli-0.2.5/VERSION
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-04-13 08:33:32.656972 arkindex-cli-0.2.5/arkindex_cli/
--rw-rw-rw-   0 root         (0) root         (0)      501 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)     1792 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/argtypes.py
--rw-rw-rw-   0 root         (0) root         (0)     4208 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/auth.py
--rw-rw-rw-   0 root         (0) root         (0)     2369 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/cli.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-04-13 08:33:32.656972 arkindex-cli-0.2.5/arkindex_cli/commands/
--rw-rw-rw-   0 root         (0) root         (0)        0 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)     2325 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/benchmark.py
--rw-rw-rw-   0 root         (0) root         (0)     1836 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/classes.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-04-13 08:33:32.656972 arkindex-cli-0.2.5/arkindex_cli/commands/elements/
--rw-rw-rw-   0 root         (0) root         (0)     1101 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/elements/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)     2765 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/elements/link.py
--rw-rw-rw-   0 root         (0) root         (0)     8629 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/elements/list.py
--rw-rw-rw-   0 root         (0) root         (0)    13082 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/elements/ml_splits.py
--rw-rw-rw-   0 root         (0) root         (0)     4654 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/elements/page_copy.py
--rw-rw-rw-   0 root         (0) root         (0)     4555 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/elements/reject_classifications.py
--rw-rw-rw-   0 root         (0) root         (0)     2576 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/elements/unlink.py
--rw-rw-rw-   0 root         (0) root         (0)     7173 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/elements/utils.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-04-13 08:33:32.660972 arkindex-cli-0.2.5/arkindex_cli/commands/export/
--rw-rw-rw-   0 root         (0) root         (0)     1092 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/export/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)    18108 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/export/alto.py
--rw-rw-rw-   0 root         (0) root         (0)     9285 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/export/csv.py
--rw-rw-rw-   0 root         (0) root         (0)    30744 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/export/db.py
--rw-rw-rw-   0 root         (0) root         (0)     2592 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/export/entities.py
--rw-rw-rw-   0 root         (0) root         (0)    11662 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/export/pdf.py
--rw-rw-rw-   0 root         (0) root         (0)     2170 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/export/utils.py
--rw-rw-rw-   0 root         (0) root         (0)     2222 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/login.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-04-13 08:33:32.660972 arkindex-cli-0.2.5/arkindex_cli/commands/models/
--rw-rw-rw-   0 root         (0) root         (0)      531 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/models/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)     4060 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/models/publish.py
--rw-rw-rw-   0 root         (0) root         (0)     8877 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/models/utils.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-04-13 08:33:32.660972 arkindex-cli-0.2.5/arkindex_cli/commands/process/
--rw-rw-rw-   0 root         (0) root         (0)      684 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/process/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)     6684 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/process/base.py
--rw-rw-rw-   0 root         (0) root         (0)     3077 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/process/recover.py
--rw-rw-rw-   0 root         (0) root         (0)     3049 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/process/report.py
--rw-rw-rw-   0 root         (0) root         (0)     2505 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/secrets.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-04-13 08:33:32.660972 arkindex-cli-0.2.5/arkindex_cli/commands/upload/
--rw-rw-rw-   0 root         (0) root         (0)      866 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/upload/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-04-13 08:33:32.660972 arkindex-cli-0.2.5/arkindex_cli/commands/upload/alto/
--rw-rw-rw-   0 root         (0) root         (0)    24164 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/upload/alto/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)    16784 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/upload/alto/parser.py
--rw-rw-rw-   0 root         (0) root         (0)     9303 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/upload/iiif.py
--rw-rw-rw-   0 root         (0) root         (0)     4308 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/upload/minio_client.py
--rw-rw-rw-   0 root         (0) root         (0)     8060 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/commands/upload/page_xml_import.py
--rw-rw-rw-   0 root         (0) root         (0)      966 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/arkindex_cli/utils.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-04-13 08:33:32.656972 arkindex-cli-0.2.5/arkindex_cli.egg-info/
--rw-r--r--   0 root         (0) root         (0)     1343 2023-04-13 08:33:32.000000 arkindex-cli-0.2.5/arkindex_cli.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)     1751 2023-04-13 08:33:32.000000 arkindex-cli-0.2.5/arkindex_cli.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-04-13 08:33:32.000000 arkindex-cli-0.2.5/arkindex_cli.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)       51 2023-04-13 08:33:32.000000 arkindex-cli-0.2.5/arkindex_cli.egg-info/entry_points.txt
--rw-r--r--   0 root         (0) root         (0)      154 2023-04-13 08:33:32.000000 arkindex-cli-0.2.5/arkindex_cli.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)       13 2023-04-13 08:33:32.000000 arkindex-cli-0.2.5/arkindex_cli.egg-info/top_level.txt
--rw-rw-rw-   0 root         (0) root         (0)       17 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/requirements-export.txt
--rw-rw-rw-   0 root         (0) root         (0)       58 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/requirements-tests.txt
--rw-rw-rw-   0 root         (0) root         (0)      127 2023-04-13 08:26:58.000000 arkindex-cli-0.2.5/requirements.txt
--rw-r--r--   0 root         (0) root         (0)       38 2023-04-13 08:33:32.660972 arkindex-cli-0.2.5/setup.cfg
--rw-rw-rw-   0 root         (0) root         (0)     1010 2023-04-13 08:01:03.000000 arkindex-cli-0.2.5/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:37:32.663961 arkindex-cli-0.2.6/
+-rw-rw-rw-   0 root         (0) root         (0)      104 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/MANIFEST.in
+-rw-r--r--   0 root         (0) root         (0)     1342 2023-06-28 15:37:32.663961 arkindex-cli-0.2.6/PKG-INFO
+-rw-rw-rw-   0 root         (0) root         (0)     1062 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/README.md
+-rw-rw-rw-   0 root         (0) root         (0)        6 2023-06-28 15:36:31.000000 arkindex-cli-0.2.6/VERSION
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:37:32.659961 arkindex-cli-0.2.6/arkindex_cli/
+-rw-rw-rw-   0 root         (0) root         (0)      501 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)     1792 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/argtypes.py
+-rw-rw-rw-   0 root         (0) root         (0)     4208 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/auth.py
+-rw-rw-rw-   0 root         (0) root         (0)     2621 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/cli.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:37:32.659961 arkindex-cli-0.2.6/arkindex_cli/commands/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 15:37:29.000000 arkindex-cli-0.2.6/arkindex_cli/commands/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)     2325 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/commands/benchmark.py
+-rw-rw-rw-   0 root         (0) root         (0)     1836 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/commands/classes.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:37:32.663961 arkindex-cli-0.2.6/arkindex_cli/commands/elements/
+-rw-rw-rw-   0 root         (0) root         (0)     1101 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/commands/elements/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)     2765 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/commands/elements/link.py
+-rw-rw-rw-   0 root         (0) root         (0)     8629 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/commands/elements/list.py
+-rw-rw-rw-   0 root         (0) root         (0)    13082 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/commands/elements/ml_splits.py
+-rw-rw-rw-   0 root         (0) root         (0)     4654 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/commands/elements/page_copy.py
+-rw-rw-rw-   0 root         (0) root         (0)     4555 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/commands/elements/reject_classifications.py
+-rw-rw-rw-   0 root         (0) root         (0)     2576 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/commands/elements/unlink.py
+-rw-rw-rw-   0 root         (0) root         (0)     7173 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/commands/elements/utils.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:37:32.663961 arkindex-cli-0.2.6/arkindex_cli/commands/export/
+-rw-rw-rw-   0 root         (0) root         (0)     1092 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/commands/export/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)    18108 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/commands/export/alto.py
+-rw-rw-rw-   0 root         (0) root         (0)     9577 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/commands/export/csv.py
+-rw-rw-rw-   0 root         (0) root         (0)    31338 2023-06-28 15:36:31.000000 arkindex-cli-0.2.6/arkindex_cli/commands/export/db.py
+-rw-rw-rw-   0 root         (0) root         (0)     3175 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/commands/export/entities.py
+-rw-rw-rw-   0 root         (0) root         (0)    12609 2023-06-28 15:36:31.000000 arkindex-cli-0.2.6/arkindex_cli/commands/export/pdf.py
+-rw-rw-rw-   0 root         (0) root         (0)     2702 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/commands/export/utils.py
+-rw-rw-rw-   0 root         (0) root         (0)     2222 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/commands/login.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:37:32.663961 arkindex-cli-0.2.6/arkindex_cli/commands/models/
+-rw-rw-rw-   0 root         (0) root         (0)      531 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/commands/models/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)     4060 2023-06-28 15:36:31.000000 arkindex-cli-0.2.6/arkindex_cli/commands/models/publish.py
+-rw-rw-rw-   0 root         (0) root         (0)     8877 2023-06-28 15:36:31.000000 arkindex-cli-0.2.6/arkindex_cli/commands/models/utils.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:37:32.663961 arkindex-cli-0.2.6/arkindex_cli/commands/process/
+-rw-rw-rw-   0 root         (0) root         (0)      684 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/commands/process/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)     6684 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/commands/process/base.py
+-rw-rw-rw-   0 root         (0) root         (0)     3077 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/commands/process/recover.py
+-rw-rw-rw-   0 root         (0) root         (0)     3049 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/commands/process/report.py
+-rw-rw-rw-   0 root         (0) root         (0)     2505 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/commands/secrets.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:37:32.663961 arkindex-cli-0.2.6/arkindex_cli/commands/upload/
+-rw-rw-rw-   0 root         (0) root         (0)      960 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/commands/upload/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:37:32.663961 arkindex-cli-0.2.6/arkindex_cli/commands/upload/alto/
+-rw-rw-rw-   0 root         (0) root         (0)    24937 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/commands/upload/alto/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)     8850 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/commands/upload/alto/parser.py
+-rw-rw-rw-   0 root         (0) root         (0)     9303 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/commands/upload/iiif.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:37:32.663961 arkindex-cli-0.2.6/arkindex_cli/commands/upload/mets/
+-rw-rw-rw-   0 root         (0) root         (0)     5111 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/commands/upload/mets/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)      872 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/commands/upload/mets/cache.py
+-rw-rw-rw-   0 root         (0) root         (0)    13456 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/commands/upload/mets/parser.py
+-rw-rw-rw-   0 root         (0) root         (0)     4308 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/commands/upload/minio_client.py
+-rw-rw-rw-   0 root         (0) root         (0)     8060 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/commands/upload/page_xml_import.py
+-rw-rw-rw-   0 root         (0) root         (0)      966 2023-06-23 08:28:16.000000 arkindex-cli-0.2.6/arkindex_cli/utils.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:37:32.659961 arkindex-cli-0.2.6/arkindex_cli.egg-info/
+-rw-r--r--   0 root         (0) root         (0)     1342 2023-06-28 15:37:32.000000 arkindex-cli-0.2.6/arkindex_cli.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     1884 2023-06-28 15:37:32.000000 arkindex-cli-0.2.6/arkindex_cli.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 15:37:32.000000 arkindex-cli-0.2.6/arkindex_cli.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)       51 2023-06-28 15:37:32.000000 arkindex-cli-0.2.6/arkindex_cli.egg-info/entry_points.txt
+-rw-r--r--   0 root         (0) root         (0)      177 2023-06-28 15:37:32.000000 arkindex-cli-0.2.6/arkindex_cli.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)       13 2023-06-28 15:37:32.000000 arkindex-cli-0.2.6/arkindex_cli.egg-info/top_level.txt
+-rw-rw-rw-   0 root         (0) root         (0)       17 2023-06-23 08:28:17.000000 arkindex-cli-0.2.6/requirements-export.txt
+-rw-rw-rw-   0 root         (0) root         (0)       58 2023-06-23 08:28:17.000000 arkindex-cli-0.2.6/requirements-tests.txt
+-rw-rw-rw-   0 root         (0) root         (0)      150 2023-06-23 08:28:17.000000 arkindex-cli-0.2.6/requirements.txt
+-rw-r--r--   0 root         (0) root         (0)       38 2023-06-28 15:37:32.663961 arkindex-cli-0.2.6/setup.cfg
+-rw-rw-rw-   0 root         (0) root         (0)     1009 2023-06-23 08:28:17.000000 arkindex-cli-0.2.6/setup.py
```

### Comparing `arkindex-cli-0.2.5/PKG-INFO` & `arkindex-cli-0.2.6/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 Metadata-Version: 2.1
 Name: arkindex-cli
-Version: 0.2.5
+Version: 0.2.6
 Summary: Arkindex CLI client easy and sexy to use
 Home-page: https://arkindex.teklia.com
 Author: Teklia
 Author-email: contact@teklia.com
-Requires-Python: >=3.10
+Requires-Python: >=3.8
 Description-Content-Type: text/markdown
 Provides-Extra: export
 
 # Arkindex CLI
 
 Documentation for users is available in the [docs](./docs) folder, and online as [cli.arkindex.org](https://cli.arkindex.org).
```

### Comparing `arkindex-cli-0.2.5/README.md` & `arkindex-cli-0.2.6/README.md`

 * *Files identical despite different names*

### Comparing `arkindex-cli-0.2.5/arkindex_cli/argtypes.py` & `arkindex-cli-0.2.6/arkindex_cli/argtypes.py`

 * *Files identical despite different names*

### Comparing `arkindex-cli-0.2.5/arkindex_cli/auth.py` & `arkindex-cli-0.2.6/arkindex_cli/auth.py`

 * *Files identical despite different names*

### Comparing `arkindex-cli-0.2.5/arkindex_cli/cli.py` & `arkindex-cli-0.2.6/arkindex_cli/cli.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,10 +1,11 @@
 # -*- coding: utf-8 -*-
 import argparse
 import errno
+import warnings
 from pathlib import Path
 
 from arkindex_cli.commands.benchmark import add_benchmark_parser
 from arkindex_cli.commands.classes import add_classes_parser
 from arkindex_cli.commands.elements import add_elements_parser
 from arkindex_cli.commands.export import add_export_parser
 from arkindex_cli.commands.login import add_login_parser
@@ -59,14 +60,19 @@
     add_upload_parser(subcommands)
     add_models_parser(subcommands)
 
     return parser
 
 
 def main():
+    # Ignore the deprecation warnings of the SQLite export functions, which are only intended for other scripts.
+    warnings.filterwarnings(
+        action="ignore", category=FutureWarning, module="arkindex_cli.commands.export"
+    )
+
     parser = get_parser()
     args = vars(parser.parse_args())
     if "func" in args:
         # Run the subcommand's function
         try:
             status = args.pop("func")(**args)
             parser.exit(status=status)
```

### Comparing `arkindex-cli-0.2.5/arkindex_cli/commands/benchmark.py` & `arkindex-cli-0.2.6/arkindex_cli/commands/benchmark.py`

 * *Files identical despite different names*

### Comparing `arkindex-cli-0.2.5/arkindex_cli/commands/classes.py` & `arkindex-cli-0.2.6/arkindex_cli/commands/classes.py`

 * *Files identical despite different names*

### Comparing `arkindex-cli-0.2.5/arkindex_cli/commands/elements/__init__.py` & `arkindex-cli-0.2.6/arkindex_cli/commands/elements/__init__.py`

 * *Files identical despite different names*

### Comparing `arkindex-cli-0.2.5/arkindex_cli/commands/elements/link.py` & `arkindex-cli-0.2.6/arkindex_cli/commands/elements/link.py`

 * *Files identical despite different names*

### Comparing `arkindex-cli-0.2.5/arkindex_cli/commands/elements/list.py` & `arkindex-cli-0.2.6/arkindex_cli/commands/elements/list.py`

 * *Files identical despite different names*

### Comparing `arkindex-cli-0.2.5/arkindex_cli/commands/elements/ml_splits.py` & `arkindex-cli-0.2.6/arkindex_cli/commands/elements/ml_splits.py`

 * *Files identical despite different names*

### Comparing `arkindex-cli-0.2.5/arkindex_cli/commands/elements/page_copy.py` & `arkindex-cli-0.2.6/arkindex_cli/commands/elements/page_copy.py`

 * *Files identical despite different names*

### Comparing `arkindex-cli-0.2.5/arkindex_cli/commands/elements/reject_classifications.py` & `arkindex-cli-0.2.6/arkindex_cli/commands/elements/reject_classifications.py`

 * *Files identical despite different names*

### Comparing `arkindex-cli-0.2.5/arkindex_cli/commands/elements/unlink.py` & `arkindex-cli-0.2.6/arkindex_cli/commands/elements/unlink.py`

 * *Files identical despite different names*

### Comparing `arkindex-cli-0.2.5/arkindex_cli/commands/elements/utils.py` & `arkindex-cli-0.2.6/arkindex_cli/commands/elements/utils.py`

 * *Files identical despite different names*

### Comparing `arkindex-cli-0.2.5/arkindex_cli/commands/export/__init__.py` & `arkindex-cli-0.2.6/arkindex_cli/commands/export/__init__.py`

 * *Files identical despite different names*

### Comparing `arkindex-cli-0.2.5/arkindex_cli/commands/export/alto.py` & `arkindex-cli-0.2.6/arkindex_cli/commands/export/alto.py`

 * *Files identical despite different names*

### Comparing `arkindex-cli-0.2.5/arkindex_cli/commands/export/csv.py` & `arkindex-cli-0.2.6/arkindex_cli/commands/export/csv.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,14 +1,16 @@
 # -*- coding: utf-8 -*-
 
 import csv
+import fnmatch
 import logging
 from datetime import datetime, timezone
+from itertools import chain
 from pathlib import Path
-from typing import Optional
+from typing import List, Optional
 from uuid import UUID
 
 from arkindex_cli.commands.export.db import (
     classes_columns,
     element_classes,
     element_entities,
     element_image,
@@ -30,15 +32,14 @@
     with_parent_metadata=False,
     with_entities=False,
     classes_columns=None,
     metadata_columns=None,
     entity_type_columns=None,
     classification_worker_version=None,
     entities_worker_version=None,
-    entities_recursive=False,
 ):
     assert (
         not with_metadata or metadata_columns is not None
     ), "Metadata columns are required to output element metadata"
     assert (
         not with_classes or classes_columns is not None
     ), "Classes columns are required to output element classifications"
@@ -91,17 +92,15 @@
                     None,
                 )
     if with_entities:
         serialized_element = {
             **serialized_element,
             **{key: None for key in entity_type_columns},
         }
-        entities = element_entities(
-            database_path, item.id, entities_worker_version, entities_recursive
-        )
+        entities = element_entities(database_path, item.id, entities_worker_version)
         for entity in entities:
             if f"entity_{entity.entity_type}" in serialized_element:
                 serialized_element[f"entity_{entity.entity_type}"] = entity.name
             # If entity.entity_type is not in serialized_element, iterate through
             # the list of entity.name and assign them to entity_{entity.entity_type}_1,
             # entity_{entity.entity_type}_2 etc.
             else:
@@ -121,30 +120,26 @@
     recursive: Optional[bool] = False,
     with_classes: Optional[bool] = False,
     with_metadata: Optional[bool] = False,
     with_parent_metadata: Optional[bool] = False,
     with_entities: Optional[bool] = False,
     classification_worker_version: Optional[str] = None,
     entities_worker_version: Optional[str] = None,
-    entities_recursive: Optional[bool] = False,
+    output_header: Optional[List[str]] = [],
 ):
     database_path = database_path.absolute()
     assert database_path.is_file(), f"Database at {database_path} not found"
     if with_parent_metadata:
         assert (
             with_metadata
         ), "The --with-parent-metadata option can only be used if --with-metadata is set."
     if entities_worker_version:
         assert (
             with_entities
         ), "The --entities-worker-version option can only be used if --with-entities is set."
-    if entities_recursive:
-        assert (
-            with_entities
-        ), "The --entities-recursive option can only be used if --with-entities is set."
 
     output_path = output_path.absolute()
 
     if recursive:
         assert (
             parent
         ), "The recursive option can only be used if a parent_element is given. If no parent_element is specified, element listing is recursive by default."
@@ -171,36 +166,50 @@
         md_columns = metadata_columns(
             database_path, parent, type, recursive, load_parents=with_parent_metadata
         )
         csv_header = csv_header + md_columns
     et_columns = None
     if with_entities:
         et_columns = entity_type_columns(
-            database_path, parent, type, entities_worker_version, entities_recursive
+            database_path,
+            parent,
+            type,
+            entities_worker_version,
+            recursive=recursive,
         )
         csv_header = csv_header + et_columns
 
+    if output_header:
+        filtered_header = list(
+            chain(*[fnmatch.filter(csv_header, header) for header in output_header])
+        )
+        # Keep the initial order of the CSV columns
+        csv_header = [header for header in csv_header if header in filtered_header]
+
     with open(output_path, "w", encoding="UTF8", newline="") as output:
         writer = csv.DictWriter(output, fieldnames=csv_header)
         writer.writeheader()
         for element in elements:
-            serialized_element = element_dict(
-                database_path,
-                element,
-                with_classes,
-                with_metadata,
-                with_parent_metadata,
-                with_entities,
-                classes_columns=cl_columns,
-                metadata_columns=md_columns,
-                entity_type_columns=et_columns,
-                classification_worker_version=classification_worker_version,
-                entities_worker_version=entities_worker_version,
-                entities_recursive=entities_recursive,
-            )
+            serialized_element = {
+                key: value
+                for key, value in element_dict(
+                    database_path,
+                    element,
+                    with_classes,
+                    with_metadata,
+                    with_parent_metadata,
+                    with_entities,
+                    classes_columns=cl_columns,
+                    metadata_columns=md_columns,
+                    entity_type_columns=et_columns,
+                    classification_worker_version=classification_worker_version,
+                    entities_worker_version=entities_worker_version,
+                ).items()
+                if key in csv_header
+            }
             writer.writerow(serialized_element)
     logger.info(f"Exported elements successfully written to {output_path}.")
 
 
 def add_csv_parser(subcommands):
     csv_parser = subcommands.add_parser(
         "csv",
@@ -239,20 +248,23 @@
     )
     csv_parser.add_argument(
         "--entities-worker-version",
         type=uuid_or_manual,
         help="Only retrieve the entities created by a specific worker version.",
     )
     csv_parser.add_argument(
-        "--entities-recursive",
-        action="store_true",
-        help="Recursively list entities attached to elements' children.",
-    )
-    csv_parser.add_argument(
         "-o",
         "--output",
         default=Path.cwd() / "elements.csv",
         type=Path,
         help="Path to a CSV file where results will be outputted. Defaults to '<current_directory>/elements.csv'.",
         dest="output_path",
     )
+    csv_parser.add_argument(
+        "-f",
+        "--field",
+        nargs="+",
+        type=str,
+        help="Limit the CSV columns to the selected fields",
+        dest="output_header",
+    )
     csv_parser.set_defaults(func=run)
```

### Comparing `arkindex-cli-0.2.5/arkindex_cli/commands/export/db.py` & `arkindex-cli-0.2.6/arkindex_cli/commands/export/db.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,15 +1,18 @@
 # -*- coding: utf-8 -*-
-
 import sqlite3
 import uuid
+import warnings
 from collections import namedtuple
+from functools import wraps
 from itertools import starmap
 from typing import List, Optional
 
+from arkindex_cli.commands.export.utils import Ordering
+
 # creating named tuple for easier handling of list_elements returned values
 
 Image = namedtuple("Image", ["id", "url"])
 Element = namedtuple("Element", ["id", "name", "polygon", "worker_version_id"])
 TypedElement = namedtuple(
     "Element", ["id", "name", "type", "polygon", "worker_version_id", "created"]
 )
@@ -41,14 +44,28 @@
         "class_id",
         "classification_confidence",
         "classification_worker_version",
     ],
 )
 
 
+def deprecated(func):
+    @wraps(func)
+    def wrapper(*args, **kwargs):
+        warnings.warn(
+            "This method is deprecated. Please use the arkindex-export library instead: https://pypi.org/project/arkindex-export/",
+            FutureWarning,
+            stacklevel=2,
+        )
+        return func(*args, **kwargs)
+
+    return wrapper
+
+
+@deprecated
 def list_elements(database_path: str, type: str) -> List[Element]:
     """
     Gets a database path, and the specified page type
     """
 
     # connection to the database
     connection = sqlite3.Connection(database_path)
@@ -62,91 +79,103 @@
 
     cursor.close()
     connection.close()
 
     return result
 
 
+@deprecated
 def list_pages(database_path: str, page_type: str) -> list:
     """
     Gets a database path, and the specified page type
     """
 
     return list_elements(database_path, page_type)
 
 
+@deprecated
 def list_folders(database_path: str, folder_type: str) -> list:
     """
     Gets a database path, the optional folder_type as strings
     """
 
     return list_elements(database_path, folder_type)
 
 
+@deprecated
 def list_lines(database_path: str, line_type: str) -> list:
     """
     Gets a database path, and the specified line_type
     """
 
     return list_elements(database_path, line_type)
 
 
+@deprecated
 def filter_folder_id(query_result: list, element_ids: list) -> list:
     """
     Gets the optional element_id arg and filter by respective value
     """
 
     filtered_list = []
     for elt in query_result:
         # must convert values from query result
         # (returned as strings by cursor.fetchall) in uuid type
         if uuid.UUID(elt[0]) in element_ids:
             filtered_list.append(elt)
     return filtered_list
 
 
-def list_children(database_path: str, parent_id: str, child_type: str) -> List[Element]:
+@deprecated
+def list_children(
+    database_path: str,
+    parent_id: str,
+    child_type: str,
+    ordering: Ordering = Ordering.Position,
+) -> List[Element]:
     """
     Gets the absolute path to the database and the optional element_id arg (parent_id),
     the type of child element and returns the list of child elements
     """
 
     # connection to the database
     connection = sqlite3.Connection(database_path)
     cursor = connection.cursor()
 
-    # query execution
-    cursor.execute(
-        """
+    order_statement = "ord" if ordering == Ordering.Position else "name"
+    query = f"""
         WITH RECURSIVE page_ids (id,ord) AS (
                 SELECT child_id, ordering
                 FROM element_path
                 WHERE parent_id = ?
             UNION
                 SELECT child_id, ordering
                 FROM element_path
                 JOIN page_ids ON (element_path.parent_id = page_ids.id)
         )
         SELECT element.id, name, polygon, worker_version_id
         FROM element
         JOIN page_ids USING (id)
         WHERE type = ?
-        ORDER BY page_ids.ord;
-        """,
-        (parent_id, child_type),
-    )
+        ORDER BY {order_statement};
+        """
+
+    params = list(map(str, [parent_id, child_type]))
 
+    # query execution
+    cursor.execute(query, params)
     result = list(starmap(Element, cursor.fetchall()))
 
     cursor.close()
     connection.close()
 
     return result
 
 
+@deprecated
 def get_elements(
     database_path: str,
     parent_id: Optional[str],
     element_type: Optional[str],
     recursive: bool,
 ) -> List[TypedElement]:
     """
@@ -249,14 +278,15 @@
 
     cursor.close()
     connection.close()
 
     return result
 
 
+@deprecated
 def element_metadata(
     database_path: str, element_id: str, load_parents: bool = False
 ) -> Optional[List[Metadata]]:
     """
     Retrieve an element's metadata.
     If load_parents is set to True, also lists metadata of all its ascending elements.
     """
@@ -291,14 +321,15 @@
     cursor.close()
     connection.close()
     if result is None:
         return
     return list(starmap(Metadata, result))
 
 
+@deprecated
 def classes_columns(
     database_path: str,
     parent_id: Optional[uuid.UUID],
     element_type: Optional[str],
     recursive: False,
 ) -> List[str]:
     connection = sqlite3.Connection(database_path)
@@ -392,14 +423,15 @@
         return []
     columns = [item[0] for item in result]
     cursor.close()
     connection.close()
     return columns
 
 
+@deprecated
 def metadata_columns(
     database_path: str,
     parent_id: Optional[uuid.UUID],
     element_type: Optional[str],
     recursive: False,
     load_parents: False,
 ) -> List[str]:
@@ -553,14 +585,15 @@
                 i += 1
         else:
             if name not in columns:
                 columns.append(name)
     return columns
 
 
+@deprecated
 def element_classes(
     database_path: str,
     element_id: str,
     classification_worker_version: Optional[uuid.UUID],
 ) -> Optional[List[Classification]]:
     """
     Retrieve an element's classes.
@@ -598,14 +631,15 @@
     cursor.close()
     connection.close()
     if result is None:
         return
     return list(starmap(Classification, result))
 
 
+@deprecated
 def transcription_entities(database_path: str) -> Optional[List[TranscriptionEntity]]:
     """
     Retrieve all transcription entities in the corpus
     """
 
     connection = sqlite3.Connection(database_path)
     cursor = connection.cursor()
@@ -625,14 +659,15 @@
     cursor.close()
     connection.close()
     if result is None:
         return
     return list(starmap(TranscriptionEntity, result))
 
 
+@deprecated
 def element_image(database_path: str, element_id: str) -> Optional[Image]:
     """
     Gets the absolute path to the database and the element_id, and
     returns the url of the element as a string
     """
     # connection to the database
     connection = sqlite3.Connection(database_path)
@@ -654,134 +689,128 @@
     cursor.close()
     connection.close()
     if result is None:
         return
     return Image(*result)
 
 
+@deprecated
 def recursive_element_transcriptions(
-    database_path: str, element_id: str
+    database_path: str,
+    element_id: str,
+    transcription_worker_version: Optional[str] = None,
 ) -> Optional[Transcription]:
 
     # connection to the database
     connection = sqlite3.Connection(database_path)
     cursor = connection.cursor()
 
-    # query execution
-    cursor.execute(
-        """
+    params: list[str] = [
+        element_id,
+    ]
+    extra_where = ""
+    if transcription_worker_version is not None:
+        extra_where = "AND transcription.worker_version_id = ?"
+        params.append(transcription_worker_version)
+
+    query = f"""
         WITH RECURSIVE child_ids (element_id) AS (
                 SELECT child_id
                 FROM element_path
                 WHERE parent_id = ?
             UNION
                 SELECT child_id
                 FROM element_path
                 JOIN child_ids ON (element_path.parent_id = child_ids.element_id)
         )
         SELECT
-        transcription.id, transcription.element_id, text, confidence, worker_version_id
+        transcription.id, transcription.element_id, text, transcription.confidence, transcription.worker_version_id
         FROM child_ids INNER JOIN transcription
-        ON child_ids.element_id = transcription.element_id;
-        """,
-        (element_id,),
-    )
+        ON child_ids.element_id = transcription.element_id
+        {extra_where};
+        """
+
+    params = list(map(str, params))
+
+    cursor.execute(query, params)
 
     result = cursor.fetchall()
     cursor.close()
     connection.close()
     if result is None:
         return
     return list(starmap(Transcription, result))
 
 
+@deprecated
 def element_transcription(
-    database_path: str, element_id: str
+    database_path: str,
+    element_id: str,
+    transcription_worker_version: Optional[str] = None,
 ) -> Optional[Transcription]:
 
     # connection to the database
     connection = sqlite3.Connection(database_path)
     cursor = connection.cursor()
 
-    # query execution
-    cursor.execute(
-        """
+    params: list[str] = [
+        element_id,
+    ]
+    extra_where = ""
+    if transcription_worker_version is not None:
+        extra_where = "AND transcription.worker_version_id = ?"
+        params.append(transcription_worker_version)
+
+    query = f"""
         SELECT id, element_id, text, confidence, worker_version_id FROM transcription
         WHERE element_id = ?
-        """,
-        (element_id,),
-    )
+        {extra_where};
+        """
+
+    params = list(map(str, params))
+
+    cursor.execute(query, params)
 
     result = cursor.fetchall()
     cursor.close()
     connection.close()
     if result is None:
         return
     return list(starmap(Transcription, result))
 
 
+@deprecated
 def element_entities(
     database_path: str,
     element_id: str,
     worker_version_id: str = None,
-    entities_recursive: bool = False,
 ) -> Optional[List[ElementEntity]]:
 
     connection = sqlite3.Connection(database_path)
     cursor = connection.cursor()
 
     params = [
         element_id,
     ]
-    where = ""
-
-    if entities_recursive:
-        base_query = """
-        WITH RECURSIVE child_ids (element_id) AS (
-            SELECT ?
-                UNION
-                    SELECT child_id
-                    FROM element_path
-                    WHERE parent_id = ?
-                UNION
-                    SELECT child_id
-                    FROM element_path
-                    JOIN child_ids ON (element_path.parent_id = child_ids.element_id)
-        )
-        SELECT entity_type.name, entity.name, ROW_NUMBER() OVER (PARTITION BY entity_type.name) AS number
-        FROM child_ids INNER JOIN transcription ON child_ids.element_id = transcription.element_id
-        """
-        params.append(element_id)
-    else:
-        base_query = """
-        SELECT entity_type.name, entity.name, ROW_NUMBER() OVER (PARTITION BY entity_type.name) AS number
-        FROM transcription
-        """
-        where = "WHERE transcription.element_id = ?"
-
-    kw = "WHERE"
-    if where:
-        kw = "AND"
+    extra_where = ""
     if worker_version_id == "manual":
-        where = " ".join(
-            [where, f"{kw} transcription_entity.worker_version_id IS NULL"]
-        ).strip()
+        extra_where = "AND transcription_entity.worker_version_id IS NULL"
     elif worker_version_id is not None:
-        where = " ".join(
-            [where, f"{kw} transcription_entity.worker_version_id = ?"]
-        ).strip()
+        extra_where = "AND transcription_entity.worker_version_id = ?"
         params.append(worker_version_id)
 
     query = f"""
-        {base_query}
+        SELECT entity_type.name, entity.name, ROW_NUMBER() OVER (PARTITION BY entity_type.name) AS number
+        FROM transcription
         INNER JOIN transcription_entity ON transcription_entity.transcription_id = transcription.id
         INNER JOIN entity ON entity.id = transcription_entity.entity_id
         INNER JOIN entity_type ON entity_type.id = entity.type_id
-        {where}
-        GROUP BY entity.name
+        WHERE transcription.element_id = ?
+        {extra_where}
+        GROUP BY entity.id
         ORDER BY entity_type.name, entity.name;
         """
 
     params = list(map(str, params))
 
     cursor.execute(query, params)
 
@@ -789,14 +818,15 @@
     cursor.close()
     connection.close()
     if result is None:
         return []
     return list(starmap(ElementEntity, result))
 
 
+@deprecated
 def entity_type_columns(
     database_path: str,
     parent_id: Optional[uuid.UUID],
     element_type: Optional[str],
     entities_worker_version: Optional[str],
     recursive: False,
 ) -> List[str]:
@@ -893,15 +923,15 @@
         {base_query}
         SELECT subquery.name, MAX(count)
         {join}
         INNER JOIN transcription_entity ON transcription_entity.transcription_id = transcription.id
         INNER JOIN entity ON entity.id = transcription_entity.entity_id
         INNER JOIN entity_type ON entity_type.id = entity.type_id
         {where}
-        GROUP BY entity_type.name
+        GROUP BY transcription.element_id, entity_type.name
         ) subquery GROUP BY name;
     """
 
     params = list(map(str, params))
 
     cursor.execute(query, params)
     result = cursor.fetchall()
@@ -922,14 +952,15 @@
             if name not in columns:
                 columns.append(f"entity_{name}")
     cursor.close()
     connection.close()
     return columns
 
 
+@deprecated
 def get_worker_version(database_path: str, worker_version_id: str) -> Optional[Worker]:
     """
     Returns the worker namedtuple from the given element id
     """
 
     # connection to the database
     connection = sqlite3.Connection(database_path)
```

### Comparing `arkindex-cli-0.2.5/arkindex_cli/commands/export/entities.py` & `arkindex-cli-0.2.6/arkindex_cli/commands/export/entities.py`

 * *Files 22% similar despite different names*

```diff
@@ -6,32 +6,50 @@
 from pathlib import Path
 from typing import Optional
 from urllib.parse import urlparse
 
 from rich.console import Console
 from rich.progress import track
 
-from arkindex_cli.commands.export.db import transcription_entities
+from arkindex_export import (
+    Entity,
+    EntityType,
+    Transcription,
+    TranscriptionEntity,
+    open_database,
+)
+from peewee import Value
 
 logger = logging.getLogger(__name__)
 
 
-def tr_ent_dict(item, instance_url):
-    element_url = f"{instance_url.rstrip('/')}/element/{item.element_id}"
-    return {
-        "transcription_id": item.transcription_id,
-        "element_id": item.element_id,
-        "element_url": element_url,
-        "entity_id": item.entity_id,
-        "entity_value": item.entity_value,
-        "entity_type": item.entity_type,
-        "entity_metas": item.entity_metas,
-        "offset": item.offset,
-        "length": item.length,
-    }
+def retrieve_transcription_entities(instance_url):
+    return (
+        TranscriptionEntity.select(
+            TranscriptionEntity.transcription_id.alias("transcription_id"),
+            Transcription.element_id.alias("element_id"),
+            (
+                Value(f"{instance_url.rstrip('/')}/element/").concat(
+                    Transcription.element_id
+                )
+            ).alias("element_url"),
+            TranscriptionEntity.entity_id.alias("entity_id"),
+            EntityType.name.alias("entity_type"),
+            Entity.name.alias("entity_value"),
+            Entity.metas.alias("entity_metas"),
+            TranscriptionEntity.length,
+            TranscriptionEntity.offset,
+        )
+        .join(Entity)
+        .join(EntityType)
+        .switch(TranscriptionEntity)
+        .join(Transcription)
+        .order_by(TranscriptionEntity.transcription_id, TranscriptionEntity.entity_id)
+        .dicts()
+    )
 
 
 def run(
     database_path: Path,
     output_path: Path,
     instance_url: str,
     profile_slug: Optional[str] = None,
@@ -49,25 +67,27 @@
         "entity_id",
         "entity_value",
         "entity_type",
         "entity_metas",
         "offset",
         "length",
     ]
-    tr_entities = transcription_entities(database_path)
+
+    open_database(database_path)
+    tr_entities = retrieve_transcription_entities(instance_url)
 
     writer = csv.DictWriter(output_path, fieldnames=csv_header)
     writer.writeheader()
-    for trent in track(
-        tr_entities,
+    for tr_entity in track(
+        tr_entities.iterator(),
         description="Exporting transcription entities",
+        total=TranscriptionEntity.select().count(),
         console=Console(file=sys.stderr),
     ):
-        serialized_ent = tr_ent_dict(trent, instance_url)
-        writer.writerow(serialized_ent)
+        writer.writerow(tr_entity)
 
     logger.info(
         f"Exported transcription entities successfully written to {output_path.name}."
     )
 
 
 def add_entities_parser(subcommands) -> None:
```

### Comparing `arkindex-cli-0.2.5/arkindex_cli/commands/export/pdf.py` & `arkindex-cli-0.2.6/arkindex_cli/commands/export/pdf.py`

 * *Files 3% similar despite different names*

```diff
@@ -12,15 +12,20 @@
     element_image,
     element_transcription,
     filter_folder_id,
     list_children,
     list_folders,
     recursive_element_transcriptions,
 )
-from arkindex_cli.commands.export.utils import bounding_box, image_download
+from arkindex_cli.commands.export.utils import (
+    Ordering,
+    bounding_box,
+    bounding_box_arkindex,
+    image_download,
+)
 
 try:
     from reportlab.lib import colors
     from reportlab.pdfbase.pdfmetrics import stringWidth
     from reportlab.pdfgen import canvas
 
     from PIL import Image
@@ -82,14 +87,24 @@
         "-o",
         "--output",
         default=Path.cwd(),
         type=Path,
         help="Path to a directory where files will be exported to. Defaults to the current directory.",
         dest="output_path",
     )
+    pdf_parser.add_argument(
+        "--order-by-name",
+        action="store_true",
+        help="Order exported elements by name instead of the internal position on Arkindex.",
+    )
+    pdf_parser.add_argument(
+        "--transcription-worker-version",
+        type=UUID,
+        help="Filter transcriptions by worker version.",
+    )
     pdf_parser.set_defaults(func=run)
 
 
 def image_draw(page: Element, image_path: str, c: "canvas", temp_dir: str) -> tuple:
     """
     Draw suitable image depending on crop if it is necessary
     """
@@ -146,14 +161,16 @@
     folder: Element,
     database_path,
     output_path,
     page_type,
     use_page_transcriptions,
     line_type,
     debug,
+    order_by_name,
+    transcription_worker_version,
     **kwargs,
 ) -> None:
     """
     Gets the database path, argument from cli, path to the generated pdf and the
     temporary directory where to find downloaded images
     """
 
@@ -167,51 +184,59 @@
 
     # chooses color depending on debug option
     selected_color = colors.transparent
 
     if debug:
         selected_color = colors.fuchsia
 
+    # Trigger name ordering if required
+    ordering = Ordering.Name if order_by_name else Ordering.Position
+
     try:
         # canvas requires the input path as string
         c = canvas.Canvas(str(Path(output_path) / f"{folder.name}.pdf"))
-
-        for page in list_children(database_path, folder.id, page_type):
+        for page in list_children(
+            database_path, folder.id, page_type, ordering=ordering
+        ):
+            logger.info(f"Processing page {page}")
             # handling case where no url is returned
             page_image = element_image(database_path, page.id)
 
+            page_bbox = bounding_box_arkindex(page.polygon)
             if page_image is None:
                 logger.warning(f"no image for page {page.name} ({page.id})")
                 continue
 
             # downloading existing image
             existing_image = image_download(page_image.url, page_image.id, temp_dir)
 
             # running reportlab drawing actions through image_draw and
             # returning updated image dimensions for the next steps
             image_width, image_height = image_draw(page, existing_image, c, temp_dir)
 
             if use_page_transcriptions:
                 # Only export page-level transcriptions
-                page_transcriptions = element_transcription(database_path, page.id)
+                page_transcriptions = element_transcription(
+                    database_path, page.id, str(transcription_worker_version)
+                )
                 if not len(page_transcriptions):
                     logger.warning(
                         f"No page-level transcription for {page_type} {page.id}."
                     )
                 for transcription in page_transcriptions:
                     c.setFillColor(selected_color)
                     textobject = c.beginText(0, image_height)
                     for line in transcription.text.splitlines(False):
                         textobject.textLine(line.rstrip())
                     c.drawText(textobject)
 
             else:
                 # getting the list of Transcriptions namedtuples for each page
                 page_transcriptions = recursive_element_transcriptions(
-                    database_path, page.id
+                    database_path, page.id, str(transcription_worker_version)
                 )
 
                 # creating a dictionary where keys are lines ids and values are
                 # relative line transcriptions
                 transcriptions_dict = {
                     transcription.element_id: transcription
                     for transcription in page_transcriptions
@@ -222,23 +247,25 @@
                     logger.warning(f"no {line_type!r} in page {page.name} ({page.id})")
 
                 for line in lines:
 
                     # handling case where no polygon is returned
                     if line.polygon is None:
                         logger.warning(f"no polygon for line {line.name} ({line.id})")
-
                     # getting bounding box dimensions
-                    line_box_dim = bounding_box(line.polygon)
+                    line_box_dim = bounding_box(
+                        line.polygon, offset_x=page_bbox.x, offset_y=page_bbox.y
+                    )
 
                     # drawing line polygon bounding box
                     # as the y axis is inverted, y origin point is "height - max_y"
 
                     # drawing line polygon bounding box
                     c.rect(
+                        # Remove page offset
                         line_box_dim.x,
                         image_height - line_box_dim.y,
                         line_box_dim.width,
                         line_box_dim.height,
                         # linebox visible according to debug value
                         stroke=debug,
                     )
@@ -278,15 +305,14 @@
                         # character width so the fontsize match with the line_box_width
                         # corresponds to line box width divided by total number
                         # of characters in the string
                         font_width = line_box_dim.width / len(text_to_draw)
 
                         # adjusts the font size to match line box width
                         c.setFont("Courier", font_width * char_ratio)
-
                         # as the y axis is inverted, y origin point is "height - max_y"
                         c.drawString(
                             line_box_dim.x, image_height - line_box_dim.y, text_to_draw
                         )
 
             # save state and prepared new possible insertion within a page
             # (force PageBreak)
```

### Comparing `arkindex-cli-0.2.5/arkindex_cli/commands/export/utils.py` & `arkindex-cli-0.2.6/arkindex_cli/commands/export/utils.py`

 * *Files 22% similar despite different names*

```diff
@@ -1,65 +1,82 @@
 # -*- coding: utf-8 -*-
 
 import json
 import logging
 from collections import namedtuple
+from enum import Enum
 from typing import Optional
 from uuid import UUID
 
 import requests
 
 logging.basicConfig(level=logging.INFO, format="[%(levelname)s] %(message)s")
 logger = logging.getLogger(__name__)
 
 BoundingBox = namedtuple("BoundingBox", ["x", "y", "width", "height"])
 
 
+class Ordering(Enum):
+    Position = "position"
+    Name = "name"
+
+
 def uuid_or_manual(value: Optional[str]) -> Optional[str]:
     if not value:
         return None
     try:
         return UUID(value)
     except (TypeError, ValueError):
         if value != "manual":
             raise ValueError(
                 "You must provide either a valid UUID or the string 'manual'."
             )
         return value
 
 
-def bounding_box(polygon) -> Optional[BoundingBox]:
+def parse_polygon(polygon):
+    # getting polygon coordinates
+    x_coords, y_coords = zip(*json.loads(polygon))
+
+    # determining line box dimensions
+    min_x, min_y = min(x_coords), min(y_coords)
+    max_x, max_y = max(x_coords), max(y_coords)
+    width, height = max_x - min_x, max_y - min_y
+    return min_x, max_x, min_y, max_y, width, height
+
+
+def bounding_box(polygon, offset_x=0, offset_y=0) -> Optional[BoundingBox]:
     """
     Gets the coordinates of the a polygon and sets the coordinates of the lower
     left point at which box starts, third value is the width of the box, the last
     one is the height,
     the y axis is switched in arkindex coordinates, starting from top left corner
     to the bottom whereas for reportlab the y axis starts from bottom left corner
     to the top,
     implies reportlab first point corresponds to arkindex (min_x,max_y)
     """
 
-    # getting polygon coordinates
-    x_coords, y_coords = zip(*json.loads(polygon))
+    min_x, _, _, max_y, width, height = parse_polygon(polygon)
+    return BoundingBox(min_x - offset_x, max_y - offset_y, width, height)
 
-    # determining line box dimensions
-    min_x, min_y = min(x_coords), min(y_coords)
-    max_x, max_y = max(x_coords), max(y_coords)
-    width, height = max_x - min_x, max_y - min_y
 
-    return BoundingBox(min_x, max_y, width, height)
+def bounding_box_arkindex(polygon) -> Optional[BoundingBox]:
+    """
+    Get a bounding box with (min_x, min_y, width, height)
+    """
+    min_x, _, min_y, _, width, height = parse_polygon(polygon)
+    return BoundingBox(min_x, min_y, width, height)
 
 
 def image_download(image_url: str, image_name: str, temp_dir: str) -> str:
     """
     Gets an url and download the requested image on a temporary directory
     """
 
     image_path = temp_dir / f"{image_name}.jpg"
-
     # case where image_path already exists
     if image_path.is_file():
         return image_path
 
     flavoured_url = image_url + "/full/full/0/default.jpg"
     logger.info(f"downloading {flavoured_url}")
     r = requests.get(flavoured_url, stream=True)
```

### Comparing `arkindex-cli-0.2.5/arkindex_cli/commands/login.py` & `arkindex-cli-0.2.6/arkindex_cli/commands/login.py`

 * *Files identical despite different names*

### Comparing `arkindex-cli-0.2.5/arkindex_cli/commands/models/__init__.py` & `arkindex-cli-0.2.6/arkindex_cli/commands/models/__init__.py`

 * *Files identical despite different names*

### Comparing `arkindex-cli-0.2.5/arkindex_cli/commands/models/publish.py` & `arkindex-cli-0.2.6/arkindex_cli/commands/models/publish.py`

 * *Files identical despite different names*

### Comparing `arkindex-cli-0.2.5/arkindex_cli/commands/models/utils.py` & `arkindex-cli-0.2.6/arkindex_cli/commands/models/utils.py`

 * *Files identical despite different names*

### Comparing `arkindex-cli-0.2.5/arkindex_cli/commands/process/__init__.py` & `arkindex-cli-0.2.6/arkindex_cli/commands/process/__init__.py`

 * *Files identical despite different names*

### Comparing `arkindex-cli-0.2.5/arkindex_cli/commands/process/base.py` & `arkindex-cli-0.2.6/arkindex_cli/commands/process/base.py`

 * *Files identical despite different names*

### Comparing `arkindex-cli-0.2.5/arkindex_cli/commands/process/recover.py` & `arkindex-cli-0.2.6/arkindex_cli/commands/process/recover.py`

 * *Files identical despite different names*

### Comparing `arkindex-cli-0.2.5/arkindex_cli/commands/process/report.py` & `arkindex-cli-0.2.6/arkindex_cli/commands/process/report.py`

 * *Files identical despite different names*

### Comparing `arkindex-cli-0.2.5/arkindex_cli/commands/secrets.py` & `arkindex-cli-0.2.6/arkindex_cli/commands/secrets.py`

 * *Files identical despite different names*

### Comparing `arkindex-cli-0.2.5/arkindex_cli/commands/upload/__init__.py` & `arkindex-cli-0.2.6/arkindex_cli/commands/upload/__init__.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,10 +1,11 @@
 # -*- coding: utf-8 -*-
 from arkindex_cli.commands.upload.alto import add_alto_parser
 from arkindex_cli.commands.upload.iiif import add_iiif_parser
+from arkindex_cli.commands.upload.mets import add_mets_parser
 from arkindex_cli.commands.upload.minio_client import add_minio_client_parser
 from arkindex_cli.commands.upload.page_xml_import import add_pagexml_import_parser
 
 
 def add_upload_parser(subcommands) -> None:
     upload_parser = subcommands.add_parser(
         "upload",
@@ -12,12 +13,13 @@
         help="Upload data to Arkindex",
     )
     subparsers = upload_parser.add_subparsers()
     add_iiif_parser(subparsers)
     add_minio_client_parser(subparsers)
     add_pagexml_import_parser(subparsers)
     add_alto_parser(subparsers)
+    add_mets_parser(subparsers)
 
     def subcommand_required(*args, **kwargs):
         upload_parser.error("A subcommand is required.")
 
     upload_parser.set_defaults(func=subcommand_required)
```

### Comparing `arkindex-cli-0.2.5/arkindex_cli/commands/upload/alto/__init__.py` & `arkindex-cli-0.2.6/arkindex_cli/commands/upload/alto/__init__.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,31 +1,27 @@
 # -*- coding: utf-8 -*-
 import csv
 import errno
+import itertools
 import json
 import logging
 import re
 from pathlib import Path
-from typing import Optional, Union
+from typing import List, Optional, Union
 from uuid import UUID
 
 from apistar.exceptions import ErrorResponse
 from arkindex import ArkindexClient
 from lxml import etree as ET
 from lxml import objectify
 from rich.progress import Progress, track
 
 from arkindex_cli.argtypes import URLArgument
 from arkindex_cli.auth import Profiles
-from arkindex_cli.commands.upload.alto.parser import (
-    AltoElement,
-    MetsProcessingError,
-    RootAltoElement,
-    RootMetsElement,
-)
+from arkindex_cli.commands.upload.alto.parser import AltoElement, RootAltoElement
 
 REGEX_IMAGE_ID = re.compile(r"0+(\d+)")
 
 logger = logging.getLogger(__name__)
 
 
 def add_alto_parser(subcommands):
@@ -64,14 +60,24 @@
         required=True,
     )
     gallica.add_argument(
         "--json-summary",
         help="Build a JSON file creation report for each parsed ALTO file.",
         action="store_true",
     )
+    gallica.add_argument(
+        "--skip-metadatas",
+        help="Skipping Alto ID metadata publication speeds up a lot the execution time",
+        action="store_true",
+    )
+    gallica.add_argument(
+        "--worker-run-id",
+        help="Worker Run used to publish elements and transcriptions in bulk. This is required to use bulk endpoints and speed up publication.",
+        type=UUID,
+    ),
     types = gallica.add_mutually_exclusive_group(required=True)
     types.add_argument(
         "--create-types",
         help="Create an element type in the Arkindex corpus for each element type in the ALTO files.",
         action="store_true",
     )
     types.add_argument(
@@ -107,14 +113,24 @@
     alto.add_argument(
         "--parent-id",
         help="UUID of a parent folder under which page elements will be created.",
         type=UUID,
         required=True,
     )
     alto.add_argument(
+        "--skip-metadatas",
+        help="Skipping Alto ID metadata publication speeds up a lot the execution time",
+        action="store_true",
+    )
+    alto.add_argument(
+        "--worker-run-id",
+        help="Worker Run used to publish elements and transcriptions in bulk. This is required to use bulk endpoints and speed up publication.",
+        type=UUID,
+    )
+    alto.add_argument(
         "--dpi-x",
         help="Horizontal resolution of the image, in dots per inch, to be used for ALTO files using coordinates in tenths of millimeters.\n"
         "Strictly positive integer. Ignored for files using coordinates in pixels.",
         type=int,
     )
     alto.add_argument(
         "--dpi-y",
@@ -136,37 +152,14 @@
     types.add_argument(
         "--existing-types",
         help='Specify correspondences between element types in the Arkindex corpus and in the ALTO files. Format: --existing-types="alto_type:arkindex_type alto_type_2:arkindex_type_2"',
         type=str,
     )
     alto.set_defaults(func=run)
 
-    mets = subcommands.add_parser(
-        "mets",
-        description="Upload METS XML documents to Arkindex.",
-        help="Upload METS XML documents to Arkindex.",
-    )
-    mets.add_argument(
-        "path",
-        help="Path to a METS file.",
-        type=Path,
-    )
-    mets.add_argument(
-        "corpus_id",
-        help="ID of the Arkindex corpus.",
-        type=UUID,
-    )
-    mets.add_argument(
-        "--element-id",
-        help="ID of the Arkindex element.",
-        type=UUID,
-        required=True,
-    )
-    mets.set_defaults(func=run_mets)
-
 
 def check_element_type(corpus: dict, type_slug: str) -> None:
     types = {type["slug"] for type in corpus["types"]}
     if type_slug not in types:
         raise ValueError(f"Type {type_slug} not found.")
     return True
 
@@ -178,32 +171,42 @@
     except ErrorResponse as e:
         # When the image already exists, its ID is returned in a HTTP 400
         if e.status_code == 400 and "id" in e.content:
             return e.content["id"]
         raise
 
 
+_TYPES = {}
+
+
 def get_element_type(
     client: ArkindexClient,
     corpus_id: UUID,
     node_name: str,
     types_dict: Optional[dict],
     create_types: bool = False,
 ):
     """
     Retrieve or create an alto node's corresponding Arkindex element type.
+    Always fetch types from Arkindex if not cached yet.
+    If types_dict is set, directly look for a matching type from that dictionary.
+    Otherwise, look for a matching Arkindex type, creating it if required.
     """
-    arkindex_corpus_types = [
-        item["slug"] for item in client.request("RetrieveCorpus", id=corpus_id)["types"]
-    ]
+    corpus_id = str(corpus_id)
+    if corpus_id not in _TYPES:
+        _TYPES[corpus_id] = arkindex_corpus_types = [
+            item["slug"]
+            for item in client.request("RetrieveCorpus", id=corpus_id)["types"]
+        ]
+    else:
+        arkindex_corpus_types = _TYPES[corpus_id]
+
     if types_dict is not None:
         if node_name not in types_dict:
-            logger.info(
-                f"Skipping alto element {node_name}: not in given types dictionary."
-            )
+            raise Exception(f"Alto element {node_name} not in given types dictionary.")
         else:
             return types_dict[node_name]
     elif create_types:
         if node_name not in arkindex_corpus_types:
             logger.info(
                 f"Creating element type {node_name} in target corpus {corpus_id}…"
             )
@@ -212,166 +215,223 @@
                     "CreateElementType",
                     body={
                         "slug": node_name,
                         "display_name": node_name,
                         "corpus": corpus_id,
                     },
                 )
+                _TYPES[corpus_id].append(node_name)
             except ErrorResponse as e:
                 logger.error(
                     f"Failed to create element type {node_name} in target corpus {corpus_id}."
                 )
                 raise Exception(e.content)
         else:
-            logger.info(
+            logger.debug(
                 f"Element type {node_name} exists in target corpus {corpus_id}."
             )
         return node_name
+    raise ValueError(
+        f"No type can be found matching node {node_name} in corpus {corpus_id}. "
+        "Hint: either define types_dict or allow type creation."
+    )
 
 
 def create_elements(
     client: ArkindexClient,
-    item: Union[AltoElement, dict],
+    nodes: List[AltoElement],
     image_id: str,
-    element_name: str,
-    corpus: dict,
     parent_id: UUID,
-    types_dict: Optional[dict],
-    create_types: bool,
+    corpus_id: UUID,
+    worker_run_id: UUID,
+    parent_node: Union[AltoElement, None] = None,
+    publish_metadatas: bool = True,
+    create_types: bool = True,
+    types_dict: Optional[dict] = None,
 ):
-    # Specific handling of the Page node, which is the "base" element created from the
-    # image on Arkindex, and which is parent to all other elements.
-    if type(item) == AltoElement and item.node_name == "page":
-        page_node = item
-        # For page nodes, a polygon can be defined by WIDTH, HEIGHT, V_POS and H_POS
-        # like other nodes, or from WIDTH and HEIGHT only.
-        if page_node.polygon:
-            page_polygon = page_node.polygon
-        else:
-            page_polygon = page_node.ark_polygon(
-                {"x": 0, "y": 0, "width": page_node.width, "height": page_node.height}
-            )
-        logger.info(f"Creating page {element_name}…")
-        page = client.request(
+    # Mapping of Alto ID => Arkindex ID
+    out = {}
+
+    # Cleanup nodes:
+    # - no nodes without ID
+    # - no nodes without polygon when parent has a polygon
+    nodes = [
+        node for node in nodes if node.id and (parent_node is None or node.polygon)
+    ]
+    if not nodes:
+        return out
+
+    # Create elements slowly one-by-one when
+    # - parent is unknown, so probably without any polygon nor image
+    # - parent is known but has not polygon
+    # - all nodes without any zones
+    # - no worker run ID is set
+    distinctive_elts = [node for node in nodes if not node.polygon]
+    if parent_node is None or not parent_node.polygon or not worker_run_id:
+        distinctive_elts += nodes
+
+    for node in distinctive_elts:
+        body = {
+            "corpus": str(corpus_id),
+            "parent": str(parent_id),
+            "type": get_element_type(
+                client,
+                corpus_id,
+                node.node_name,
+                types_dict=types_dict,
+                create_types=create_types,
+            ),
+            "name": node.name,
+        }
+
+        if image_id and node.polygon:
+            body["polygon"] = node.polygon
+            body["image"] = image_id
+
+        element = client.request(
             "CreateElement",
-            body={
-                "corpus": corpus["id"],
-                "parent": str(parent_id),
-                "type": get_element_type(
-                    client,
-                    corpus["id"],
-                    page_node.node_name,
-                    types_dict,
-                    create_types,
-                ),
-                "name": element_name,
-                "image": image_id,
-                "polygon": page_polygon,
-            },
-            slim_output=True,
+            body=body,
         )
-        # Publish ALTO ID as metadata
-        client.request(
-            "CreateMetaData",
-            id=page["id"],
-            body={"name": "Alto ID", "value": page_node.name, "type": "reference"},
+
+        # Store the arkindex ID of the newly created element
+        out[node.id] = element["id"]
+
+        # Build transcription when available
+        if node.text:
+            client.request(
+                "CreateTranscription",
+                id=element["id"],
+                body={"text": node.text},
+            )
+
+    if distinctive_elts:
+        logger.info(f"Published {len(distinctive_elts)} elements distinctly")
+
+    # Split remaining nodes with/without transcriptions
+    # to take advantage of CreateElements & CreateElementTranscriptions
+    with_transcriptions = [node for node in nodes if node.text and node.id not in out]
+    without_transcriptions = [
+        node for node in nodes if not node.text and node.id not in out
+    ]
+
+    if without_transcriptions:
+        try:
+            elements = client.request(
+                "CreateElements",
+                id=parent_id,
+                body={
+                    "worker_run_id": str(worker_run_id),
+                    "elements": [
+                        {
+                            "name": node.name,
+                            "type": get_element_type(
+                                client,
+                                corpus_id,
+                                node.node_name,
+                                types_dict=types_dict,
+                                create_types=create_types,
+                            ),
+                            "polygon": node.polygon,
+                        }
+                        for node in without_transcriptions
+                    ],
+                },
+            )
+        except ErrorResponse as e:
+            logger.error(f"Failed to create elements: {e.content}")
+            raise
+
+        # Store the arkindex ID of the newly created element
+        node_ids = (node.id for node in without_transcriptions)
+        arkindex_ids = (elt["id"] for elt in elements)
+        out.update(dict(zip(node_ids, arkindex_ids)))
+
+        logger.info(f"Published {len(without_transcriptions)} elements")
+
+    if with_transcriptions:
+
+        # To create elements and transcriptions, we first
+        # need to group nodes by their types
+        groups = itertools.groupby(
+            sorted(with_transcriptions, key=lambda n: n.node_name),
+            lambda n: n.node_name,
         )
-        page_subelements = page_node.serialized_children
-        elements = {page_node.name: page["id"]}
-        for subelement in page_subelements:
-            elements.update(
-                create_elements(
-                    client=client,
-                    item=subelement,
-                    image_id=image_id,
-                    element_name=None,
-                    corpus=corpus,
-                    parent_id=page["id"],
-                    types_dict=types_dict,
-                    create_types=create_types,
+
+        for node_name, node_group in groups:
+            node_group = list(node_group)  # needed because we access it several times
+            try:
+                elements = client.request(
+                    "CreateElementTranscriptions",
+                    id=parent_id,
+                    body={
+                        "element_type": get_element_type(
+                            client,
+                            corpus_id,
+                            node_name,
+                            types_dict=types_dict,
+                            create_types=create_types,
+                        ),
+                        "worker_run_id": str(worker_run_id),
+                        "return_elements": True,
+                        "transcriptions": [
+                            {
+                                "polygon": node.polygon,
+                                "text": node.text,
+                                "confidence": 1.0,
+                            }
+                            for node in node_group
+                        ],
+                    },
                 )
+            except ErrorResponse as e:
+                logger.error(f"Failed to create elements: {e.content}")
+                raise
+
+            # Store the arkindex ID of the newly created element
+            node_ids = (node.id for node in node_group)
+            arkindex_ids = (elt["element_id"] for elt in elements)
+            out.update(dict(zip(node_ids, arkindex_ids)))
+
+        logger.info(
+            f"Published {len(with_transcriptions)} elements with transcriptions"
+        )
+
+    # Publish metadatas slowly, there is no alternative here
+    if publish_metadatas:
+        for node in nodes:
+            client.request(
+                "CreateMetaData",
+                id=out[node.id],
+                body={"name": "Alto ID", "value": node.id, "type": "reference"},
+            )
+
+        logger.info(f"Published {len(nodes)} metadatas")
+
+    # All nodes are created at this point
+    # we can directly iterate on their children
+    for node in nodes:
+        if not node.children:
+            continue
+
+        out.update(
+            create_elements(
+                client,
+                nodes=node.children,
+                image_id=image_id,
+                parent_id=out[node.id],
+                corpus_id=corpus_id,
+                worker_run_id=worker_run_id,
+                parent_node=node,
+                publish_metadatas=publish_metadatas,
+                types_dict=types_dict,
+                create_types=create_types,
             )
-    elif type(item) == dict:
-        elements = {}
-        if "polygon" in item:
-            base_dict = item.copy()
-            base_dict.pop("children")
-            base_dict.pop("text", None)
-            element_name = "0"
-            if "name" in base_dict:
-                element_name = base_dict["name"]
-            element_type = get_element_type(
-                client, corpus["id"], base_dict["type"], types_dict, create_types
-            )
-            if element_type:
-                element_body = {
-                    "type": element_type,
-                    "name": element_name,
-                    "parent": parent_id,
-                    "corpus": corpus["id"],
-                    "image": image_id,
-                    "polygon": base_dict["polygon"],
-                }
-                logger.info(f"Creating {element_type} {element_name}…")
-                try:
-                    created_element = client.request(
-                        "CreateElement", body=element_body, slim_output=True
-                    )
-                    # Publish ALTO ID as metadata
-                    client.request(
-                        "CreateMetaData",
-                        id=created_element["id"],
-                        body={
-                            "name": "Alto ID",
-                            "value": element_name,
-                            "type": "reference",
-                        },
-                    )
-
-                    parent_id = created_element["id"]
-                    elements[element_name] = parent_id
-
-                except ErrorResponse as e:
-                    raise Exception(
-                        f"Could not create the element {element_name} with type {element_type}: HTTP {e.status_code} - {e.content}"
-                    )
-
-                # Create transcription if there is one
-                if "text" in item:
-                    transcription_body = {"text": item["text"]}
-                    logger.info(
-                        f"Creating transcription {item['text']} for {element_type} {element_name}…"
-                    )
-                    try:
-                        client.request(
-                            "CreateTranscription",
-                            id=created_element["id"],
-                            body=transcription_body,
-                        )
-                    except ErrorResponse as e:
-                        logger.error(
-                            f"Could not create the transcription for element {created_element['id']}: HTTP {e.status_code} - {e.content}"
-                        )
-            else:
-                parent_id = parent_id
-        if len(item["children"]) > 0:
-            for child in item["children"]:
-                elements.update(
-                    create_elements(
-                        client,
-                        child,
-                        image_id,
-                        None,
-                        corpus,
-                        parent_id,
-                        types_dict,
-                        create_types,
-                    )
-                )
-    return elements
+        )
+
+    return out
 
 
 def format_url(path: Path, iiif_base_url: str, folders_ark_id_dict: dict = None):
     """
     This function is used to create the url to get the image from the Gallica IIIF server
     """
     # The path.name looks like 18840615_1-0003.xml with the folder id being the 18840615 which we use to
@@ -408,14 +468,16 @@
     create_types: bool,
     dpi_x: Optional[int] = None,
     dpi_y: Optional[int] = None,
     gallica: bool = False,
     folders_ark_id_dict: dict = None,
     alto_namespace: str = None,
     json_summary: bool = False,
+    worker_run_id: Optional[UUID] = None,
+    skip_metadatas: bool = False,
 ) -> None:
     with open(path) as file:
         # This ensures that comments in the XML files do not cause the
         # "no Alto namespace found" exception.
         parser = ET.XMLParser(remove_comments=True)
         tree = objectify.parse(file, parser=parser)
         root = RootAltoElement(
@@ -434,32 +496,32 @@
         # 'http://server/iiif/root%2Fdirectory'
         # urljoin or path.join would erase that identifier prefix.
         if gallica:
             url = format_url(path, iiif_base_url, folders_ark_id_dict)
             image_id = create_iiif_image(client, url)
         else:
             image_id = create_iiif_image(client, iiif_base_url + root.filename)
-        page_name = root.filename
         page_node = AltoElement(
             page_nodes[0],
             alto_namespace=alto_namespace,
             unit=root.unit,
             dpi_x=dpi_x,
             dpi_y=dpi_y,
         )
         page_node.parse_children()
         elements = create_elements(
-            client,
-            page_node,
-            image_id,
-            page_name,
-            corpus,
-            parent_id,
-            types_dict,
-            create_types,
+            client=client,
+            nodes=[page_node],
+            image_id=image_id,
+            parent_id=parent_id,
+            corpus_id=corpus["id"],
+            worker_run_id=worker_run_id,
+            publish_metadatas=not skip_metadatas,
+            create_types=create_types,
+            types_dict=types_dict,
         )
     elif len(page_nodes) > 1:
         elements = {}
         for page_node in page_nodes:
             page_node = AltoElement(
                 page_node,
                 alto_namespace=alto_namespace,
@@ -471,25 +533,25 @@
                 logger.warning(
                     "Attribute PHYSICAL_IMG_NR was not set for this Page node. Skipping…"
                 )
                 return
             image_id = create_iiif_image(
                 client, iiif_base_url + page_node.page_image_id
             )
-            page_name = page_node.name
             elements.update(
                 create_elements(
-                    client,
-                    page_node,
-                    image_id,
-                    page_name,
-                    corpus,
-                    parent_id,
-                    types_dict,
-                    create_types,
+                    client=client,
+                    nodes=[page_node],
+                    image_id=image_id,
+                    parent_id=parent_id,
+                    corpus_id=corpus,
+                    worker_run_id=worker_run_id,
+                    publish_metadatas=not skip_metadatas,
+                    create_types=create_types,
+                    types_dict=types_dict,
                 )
             )
     else:
         logger.warning(f"No Page node found in file {root.filename}. Skipping…")
         return
 
     if json_summary:
@@ -512,14 +574,16 @@
     parent_id: UUID,
     create_types: bool = False,
     existing_types: Optional[str] = None,
     metadata_file: Path = None,
     json_summary: bool = False,
     profile_slug: Optional[str] = None,
     alto_namespace: str = None,
+    worker_run_id: Optional[UUID] = None,
+    skip_metadatas: bool = False,
 ):
     # If this is a Gallica import, load the metadata CSV file
     folders_ark_id_dict = dict()
     with open(metadata_file, "r") as file:
         reader = csv.reader(file)
         # Create a dictionary with the folder name as the id and the Gallica Ark ID as the value
         folders_ark_id_dict = {row[0]: row[1] for row in reader}
@@ -530,14 +594,16 @@
         create_types=create_types,
         existing_types=existing_types,
         folders_ark_id_dict=folders_ark_id_dict,
         gallica=True,
         profile_slug=profile_slug,
         alto_namespace=alto_namespace,
         json_summary=json_summary,
+        worker_run_id=worker_run_id,
+        skip_metadatas=skip_metadatas,
     )
 
 
 def run(
     path: Path,
     iiif_base_url: str,
     parent_id: UUID,
@@ -546,14 +612,16 @@
     create_types: bool = False,
     existing_types: Optional[str] = None,
     folders_ark_id_dict: dict = None,
     profile_slug: Optional[str] = None,
     gallica: bool = False,
     alto_namespace: str = None,
     json_summary: bool = False,
+    worker_run_id: Optional[UUID] = None,
+    skip_metadatas: bool = False,
 ) -> int:
     if (dpi_x is None) ^ (dpi_y is None):
         logger.error("--dpi-x and --dpi-y must be either both set or both unset.")
         return errno.EINVAL
 
     if dpi_x is not None and dpi_x <= 0:
         logger.error("--dpi-x must be a strictly positive integer.")
@@ -593,14 +661,19 @@
             corpus = client.request("RetrieveCorpus", id=corpus_id)
         except ErrorResponse as e:
             logger.error(
                 f"Could not retrieve corpus {corpus_id}: HTTP {e.status_code} - {e.content}"
             )
             return errno.EREMOTEIO
 
+    if not worker_run_id:
+        logger.info(
+            "Upload METS in slow mode (Set --worker-run-id to use bulk endpoints)"
+        )
+
     types_dict = None
     if existing_types:
         split_str = existing_types.split(" ")
         types_dict = {}
         for item in split_str:
             split_item = item.split(":")
             types_dict[str(split_item[0]).lower()] = str(split_item[1]).lower()
@@ -625,71 +698,20 @@
                 parent_id=parent_id,
                 types_dict=types_dict,
                 create_types=create_types,
                 dpi_x=dpi_x,
                 dpi_y=dpi_y,
                 alto_namespace=alto_namespace,
                 json_summary=json_summary,
+                worker_run_id=worker_run_id,
+                skip_metadatas=skip_metadatas,
             )
         except ErrorResponse as e:
             logger.error(
                 f"Upload failed for file {file_path}: HTTP {e.status_code} - {e.content}"
             )
             failed += 1
         except Exception as e:
             logger.error(f"Upload failed for file {file_path}: {e}")
             failed += 1
     # Return a non-zero error code when all files have failed
     return failed >= len(file_paths)
-
-
-def run_mets(
-    path: Path,
-    corpus_id: UUID,
-    element_id: UUID,
-    profile_slug: Optional[str] = None,
-):
-    with Progress(transient=True) as progress:
-        progress.add_task(start=False, description="Loading API client")
-        client = Profiles().get_api_client_or_exit(profile_slug)
-
-    # Parse TOC
-    assert path.exists(), f"Cannot find METS at {path}"
-
-    with path.open() as file:
-        # This ensures that comments in the XML files do not cause the
-        # "no Alto namespace found" exception.
-        parser = ET.XMLParser(remove_comments=True)
-        tree = objectify.parse(file, parser=parser)
-
-        root = RootMetsElement(path, tree.getroot())
-
-    with Progress(transient=True) as progress:
-        progress.add_task(start=False, description="Fetching corpus")
-        try:
-            corpus = client.request("RetrieveCorpus", id=corpus_id)
-        except ErrorResponse as e:
-            logger.error(
-                f"Could not retrieve corpus {corpus_id}: HTTP {e.status_code} - {e.content}"
-            )
-            return errno.EREMOTEIO
-
-    # Check that every type used by the tree is available on the corpus
-    for type_slug in root.parse_object_types():
-        check_element_type(corpus, type_slug=type_slug)
-
-    # Check the existence of the top element
-    with Progress(transient=True) as progress:
-        progress.add_task(start=False, description="Fetching parent element")
-        try:
-            client.request("RetrieveElement", id=element_id)
-        except ErrorResponse as e:
-            logger.error(
-                f"Could not retrieve parent element {element_id}: HTTP {e.status_code} - {e.content}"
-            )
-            return errno.EREMOTEIO
-
-    try:
-        root.publish(arkindex_client=client, parent_id=element_id, corpus_id=corpus_id)
-    except MetsProcessingError:
-        logger.error(f"Failed to publish METS file @ {path}")
-        return errno.EREMOTEIO
```

### Comparing `arkindex-cli-0.2.5/arkindex_cli/commands/upload/iiif.py` & `arkindex-cli-0.2.6/arkindex_cli/commands/upload/iiif.py`

 * *Files identical despite different names*

### Comparing `arkindex-cli-0.2.5/arkindex_cli/commands/upload/minio_client.py` & `arkindex-cli-0.2.6/arkindex_cli/commands/upload/minio_client.py`

 * *Files identical despite different names*

### Comparing `arkindex-cli-0.2.5/arkindex_cli/commands/upload/page_xml_import.py` & `arkindex-cli-0.2.6/arkindex_cli/commands/upload/page_xml_import.py`

 * *Files identical despite different names*

### Comparing `arkindex-cli-0.2.5/arkindex_cli/utils.py` & `arkindex-cli-0.2.6/arkindex_cli/utils.py`

 * *Files identical despite different names*

### Comparing `arkindex-cli-0.2.5/arkindex_cli.egg-info/PKG-INFO` & `arkindex-cli-0.2.6/arkindex_cli.egg-info/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 Metadata-Version: 2.1
 Name: arkindex-cli
-Version: 0.2.5
+Version: 0.2.6
 Summary: Arkindex CLI client easy and sexy to use
 Home-page: https://arkindex.teklia.com
 Author: Teklia
 Author-email: contact@teklia.com
-Requires-Python: >=3.10
+Requires-Python: >=3.8
 Description-Content-Type: text/markdown
 Provides-Extra: export
 
 # Arkindex CLI
 
 Documentation for users is available in the [docs](./docs) folder, and online as [cli.arkindex.org](https://cli.arkindex.org).
```

### Comparing `arkindex-cli-0.2.5/arkindex_cli.egg-info/SOURCES.txt` & `arkindex-cli-0.2.6/arkindex_cli.egg-info/SOURCES.txt`

 * *Files 6% similar despite different names*

```diff
@@ -44,8 +44,11 @@
 arkindex_cli/commands/process/recover.py
 arkindex_cli/commands/process/report.py
 arkindex_cli/commands/upload/__init__.py
 arkindex_cli/commands/upload/iiif.py
 arkindex_cli/commands/upload/minio_client.py
 arkindex_cli/commands/upload/page_xml_import.py
 arkindex_cli/commands/upload/alto/__init__.py
-arkindex_cli/commands/upload/alto/parser.py
+arkindex_cli/commands/upload/alto/parser.py
+arkindex_cli/commands/upload/mets/__init__.py
+arkindex_cli/commands/upload/mets/cache.py
+arkindex_cli/commands/upload/mets/parser.py
```

### Comparing `arkindex-cli-0.2.5/setup.py` & `arkindex-cli-0.2.6/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -24,14 +24,14 @@
     version=VERSION,
     description="Arkindex CLI client easy and sexy to use",
     author="Teklia",
     author_email="contact@teklia.com",
     url="https://arkindex.teklia.com",
     long_description=README,
     long_description_content_type="text/markdown",
-    python_requires=">=3.10",
+    python_requires=">=3.8",
     install_requires=install_requires,
     tests_require=[],
     extras_require={"export": requirements("requirements-export.txt")},
     packages=find_packages(),
     entry_points={"console_scripts": ["arkindex = arkindex_cli.cli:main"]},
 )
```


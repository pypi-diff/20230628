# Comparing `tmp/swh.fuse-1.0.5.tar.gz` & `tmp/swh.fuse-1.0.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/swh.fuse-1.0.5.tar", last modified: Fri Apr  1 10:20:42 2022, max compression
+gzip compressed data, was "swh.fuse-1.0.6.tar", last modified: Wed Jun 28 14:21:20 2023, max compression
```

## Comparing `swh.fuse-1.0.5.tar` & `swh.fuse-1.0.6.tar`

### file list

```diff
@@ -1,98 +1,99 @@
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2022-04-01 10:20:42.000000 swh.fuse-1.0.5/
--rw-r--r--   0 jenkins    (115) docker     (999)      111 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/.gitignore
--rw-r--r--   0 jenkins    (115) docker     (999)      993 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/.pre-commit-config.yaml
--rw-r--r--   0 jenkins    (115) docker     (999)      112 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/AUTHORS
--rw-r--r--   0 jenkins    (115) docker     (999)     3397 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/CODE_OF_CONDUCT.md
--rw-r--r--   0 jenkins    (115) docker     (999)       19 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/CONTRIBUTORS
--rw-r--r--   0 jenkins    (115) docker     (999)    35147 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/LICENSE
--rw-r--r--   0 jenkins    (115) docker     (999)      112 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/MANIFEST.in
--rw-r--r--   0 jenkins    (115) docker     (999)      163 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/Makefile
--rw-r--r--   0 jenkins    (115) docker     (999)     2169 2022-04-01 10:20:42.000000 swh.fuse-1.0.5/PKG-INFO
--rw-r--r--   0 jenkins    (115) docker     (999)     1229 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/README.rst
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2022-04-01 10:20:42.000000 swh.fuse-1.0.5/debian/
--rw-r--r--   0 jenkins    (115) docker     (999)       95 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/debian/changelog
--rw-r--r--   0 jenkins    (115) docker     (999)        2 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/debian/compat
--rw-r--r--   0 jenkins    (115) docker     (999)      728 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/debian/control
--rw-r--r--   0 jenkins    (115) docker     (999)      931 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/debian/copyright
--rwxr-xr-x   0 jenkins    (115) docker     (999)      309 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/debian/rules
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2022-04-01 10:20:42.000000 swh.fuse-1.0.5/debian/source/
--rw-r--r--   0 jenkins    (115) docker     (999)       12 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/debian/source/format
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2022-04-01 10:20:42.000000 swh.fuse-1.0.5/docs/
--rw-r--r--   0 jenkins    (115) docker     (999)       24 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/docs/.gitignore
--rw-r--r--   0 jenkins    (115) docker     (999)       63 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/docs/Makefile
--rw-r--r--   0 jenkins    (115) docker     (999)      200 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/docs/Makefile.local
--rw-r--r--   0 jenkins    (115) docker     (999)     1229 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/docs/README.rst
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2022-04-01 10:20:42.000000 swh.fuse-1.0.5/docs/_static/
--rw-r--r--   0 jenkins    (115) docker     (999)        0 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/docs/_static/.placeholder
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2022-04-01 10:20:42.000000 swh.fuse-1.0.5/docs/_templates/
--rw-r--r--   0 jenkins    (115) docker     (999)        0 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/docs/_templates/.placeholder
--rw-r--r--   0 jenkins    (115) docker     (999)      127 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/docs/cli.rst
--rw-r--r--   0 jenkins    (115) docker     (999)       43 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/docs/conf.py
--rw-r--r--   0 jenkins    (115) docker     (999)     2584 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/docs/configuration.rst
--rw-r--r--   0 jenkins    (115) docker     (999)     9666 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/docs/design.md
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2022-04-01 10:20:42.000000 swh.fuse-1.0.5/docs/images/
--rw-r--r--   0 jenkins    (115) docker     (999)      328 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/docs/images/Makefile
--rw-r--r--   0 jenkins    (115) docker     (999)     9188 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/docs/images/arch-container.pdf
--rw-r--r--   0 jenkins    (115) docker     (999)    51941 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/docs/images/arch-container.png
--rw-r--r--   0 jenkins    (115) docker     (999)     1090 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/docs/images/arch-container.puml
--rw-r--r--   0 jenkins    (115) docker     (999)    15223 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/docs/images/arch-container.svg
--rw-r--r--   0 jenkins    (115) docker     (999)     3729 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/docs/images/arch-context.pdf
--rw-r--r--   0 jenkins    (115) docker     (999)    14499 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/docs/images/arch-context.png
--rw-r--r--   0 jenkins    (115) docker     (999)      508 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/docs/images/arch-context.puml
--rw-r--r--   0 jenkins    (115) docker     (999)     6056 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/docs/images/arch-context.svg
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2022-04-01 10:20:42.000000 swh.fuse-1.0.5/docs/images/c4-plantuml/
--rw-r--r--   0 jenkins    (115) docker     (999)     3872 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/docs/images/c4-plantuml/C4.puml
--rw-r--r--   0 jenkins    (115) docker     (999)     1995 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/docs/images/c4-plantuml/C4_Component.puml
--rw-r--r--   0 jenkins    (115) docker     (999)     2176 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/docs/images/c4-plantuml/C4_Container.puml
--rw-r--r--   0 jenkins    (115) docker     (999)     3546 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/docs/images/c4-plantuml/C4_Context.puml
--rw-r--r--   0 jenkins    (115) docker     (999)     1071 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/docs/images/c4-plantuml/LICENSE
--rw-r--r--   0 jenkins    (115) docker     (999)      201 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/docs/index.rst
--rw-r--r--   0 jenkins    (115) docker     (999)    10085 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/docs/tutorial.rst
--rw-r--r--   0 jenkins    (115) docker     (999)      453 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/mypy.ini
--rw-r--r--   0 jenkins    (115) docker     (999)      237 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/pyproject.toml
--rw-r--r--   0 jenkins    (115) docker     (999)       39 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/pytest.ini
--rw-r--r--   0 jenkins    (115) docker     (999)       62 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/requirements-swh.txt
--rw-r--r--   0 jenkins    (115) docker     (999)      140 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/requirements-test.txt
--rw-r--r--   0 jenkins    (115) docker     (999)       55 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/requirements.txt
--rw-r--r--   0 jenkins    (115) docker     (999)       93 2022-04-01 10:20:42.000000 swh.fuse-1.0.5/setup.cfg
--rwxr-xr-x   0 jenkins    (115) docker     (999)     2344 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/setup.py
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2022-04-01 10:20:42.000000 swh.fuse-1.0.5/swh/
--rw-r--r--   0 jenkins    (115) docker     (999)       76 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/swh/__init__.py
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2022-04-01 10:20:42.000000 swh.fuse-1.0.5/swh/fuse/
--rw-r--r--   0 jenkins    (115) docker     (999)       23 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/swh/fuse/__init__.py
--rw-r--r--   0 jenkins    (115) docker     (999)    14691 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/swh/fuse/cache.py
--rw-r--r--   0 jenkins    (115) docker     (999)     6439 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/swh/fuse/cli.py
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2022-04-01 10:20:42.000000 swh.fuse-1.0.5/swh/fuse/fs/
--rw-r--r--   0 jenkins    (115) docker     (999)    22615 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/swh/fuse/fs/artifact.py
--rw-r--r--   0 jenkins    (115) docker     (999)     4418 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/swh/fuse/fs/entry.py
--rw-r--r--   0 jenkins    (115) docker     (999)     8998 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/swh/fuse/fs/mountpoint.py
--rw-r--r--   0 jenkins    (115) docker     (999)    13100 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/swh/fuse/fuse.py
--rw-r--r--   0 jenkins    (115) docker     (999)       27 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/swh/fuse/py.typed
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2022-04-01 10:20:42.000000 swh.fuse-1.0.5/swh/fuse/tests/
--rw-r--r--   0 jenkins    (115) docker     (999)        0 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/swh/fuse/tests/__init__.py
--rw-r--r--   0 jenkins    (115) docker     (999)     1266 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/swh/fuse/tests/api_url.py
--rw-r--r--   0 jenkins    (115) docker     (999)     1393 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/swh/fuse/tests/common.py
--rw-r--r--   0 jenkins    (115) docker     (999)     2540 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/swh/fuse/tests/conftest.py
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2022-04-01 10:20:42.000000 swh.fuse-1.0.5/swh/fuse/tests/data/
--rw-r--r--   0 jenkins    (115) docker     (999)        0 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/swh/fuse/tests/data/__init__.py
--rw-r--r--   0 jenkins    (115) docker     (999)   185334 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/swh/fuse/tests/data/api_data.py
--rw-r--r--   0 jenkins    (115) docker     (999)     4064 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/swh/fuse/tests/data/config.py
--rwxr-xr-x   0 jenkins    (115) docker     (999)     8356 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/swh/fuse/tests/data/gen-api-data.py
--rw-r--r--   0 jenkins    (115) docker     (999)     1261 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/swh/fuse/tests/test_cache.py
--rw-r--r--   0 jenkins    (115) docker     (999)     1089 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/swh/fuse/tests/test_cli.py
--rw-r--r--   0 jenkins    (115) docker     (999)      434 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/swh/fuse/tests/test_content.py
--rw-r--r--   0 jenkins    (115) docker     (999)     1683 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/swh/fuse/tests/test_directory.py
--rw-r--r--   0 jenkins    (115) docker     (999)      423 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/swh/fuse/tests/test_meta.py
--rw-r--r--   0 jenkins    (115) docker     (999)     1188 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/swh/fuse/tests/test_mountpoint.py
--rw-r--r--   0 jenkins    (115) docker     (999)      807 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/swh/fuse/tests/test_origin.py
--rw-r--r--   0 jenkins    (115) docker     (999)     1420 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/swh/fuse/tests/test_release.py
--rw-r--r--   0 jenkins    (115) docker     (999)     3339 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/swh/fuse/tests/test_revision.py
--rw-r--r--   0 jenkins    (115) docker     (999)     1103 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/swh/fuse/tests/test_snapshot.py
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2022-04-01 10:20:42.000000 swh.fuse-1.0.5/swh.fuse.egg-info/
--rw-r--r--   0 jenkins    (115) docker     (999)     2169 2022-04-01 10:20:41.000000 swh.fuse-1.0.5/swh.fuse.egg-info/PKG-INFO
--rw-r--r--   0 jenkins    (115) docker     (999)     1915 2022-04-01 10:20:41.000000 swh.fuse-1.0.5/swh.fuse.egg-info/SOURCES.txt
--rw-r--r--   0 jenkins    (115) docker     (999)        1 2022-04-01 10:20:41.000000 swh.fuse-1.0.5/swh.fuse.egg-info/dependency_links.txt
--rw-r--r--   0 jenkins    (115) docker     (999)       42 2022-04-01 10:20:41.000000 swh.fuse-1.0.5/swh.fuse.egg-info/entry_points.txt
--rw-r--r--   0 jenkins    (115) docker     (999)      202 2022-04-01 10:20:41.000000 swh.fuse-1.0.5/swh.fuse.egg-info/requires.txt
--rw-r--r--   0 jenkins    (115) docker     (999)        4 2022-04-01 10:20:41.000000 swh.fuse-1.0.5/swh.fuse.egg-info/top_level.txt
--rw-r--r--   0 jenkins    (115) docker     (999)     1398 2022-04-01 10:20:38.000000 swh.fuse-1.0.5/tox.ini
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 14:21:20.543575 swh.fuse-1.0.6/
+-rw-r--r--   0 jenkins    (115) docker     (999)       83 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/.git-blame-ignore-revs
+-rw-r--r--   0 jenkins    (115) docker     (999)      111 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/.gitignore
+-rw-r--r--   0 jenkins    (115) docker     (999)      957 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/.pre-commit-config.yaml
+-rw-r--r--   0 jenkins    (115) docker     (999)      112 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/AUTHORS
+-rw-r--r--   0 jenkins    (115) docker     (999)     3397 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/CODE_OF_CONDUCT.md
+-rw-r--r--   0 jenkins    (115) docker     (999)       19 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/CONTRIBUTORS
+-rw-r--r--   0 jenkins    (115) docker     (999)    35147 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/LICENSE
+-rw-r--r--   0 jenkins    (115) docker     (999)      112 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/MANIFEST.in
+-rw-r--r--   0 jenkins    (115) docker     (999)      163 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/Makefile
+-rw-r--r--   0 jenkins    (115) docker     (999)     2132 2023-06-28 14:21:20.567575 swh.fuse-1.0.6/PKG-INFO
+-rw-r--r--   0 jenkins    (115) docker     (999)     1229 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/README.rst
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 14:21:20.475575 swh.fuse-1.0.6/debian/
+-rw-r--r--   0 jenkins    (115) docker     (999)       95 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/debian/changelog
+-rw-r--r--   0 jenkins    (115) docker     (999)        2 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/debian/compat
+-rw-r--r--   0 jenkins    (115) docker     (999)      728 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/debian/control
+-rw-r--r--   0 jenkins    (115) docker     (999)      931 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/debian/copyright
+-rwxr-xr-x   0 jenkins    (115) docker     (999)      309 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/debian/rules
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 14:21:20.475575 swh.fuse-1.0.6/debian/source/
+-rw-r--r--   0 jenkins    (115) docker     (999)       12 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/debian/source/format
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 14:21:20.535575 swh.fuse-1.0.6/docs/
+-rw-r--r--   0 jenkins    (115) docker     (999)       24 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/docs/.gitignore
+-rw-r--r--   0 jenkins    (115) docker     (999)       63 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/docs/Makefile
+-rw-r--r--   0 jenkins    (115) docker     (999)      200 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/docs/Makefile.local
+-rw-r--r--   0 jenkins    (115) docker     (999)     1229 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/docs/README.rst
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 14:21:20.535575 swh.fuse-1.0.6/docs/_static/
+-rw-r--r--   0 jenkins    (115) docker     (999)        0 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/docs/_static/.placeholder
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 14:21:20.535575 swh.fuse-1.0.6/docs/_templates/
+-rw-r--r--   0 jenkins    (115) docker     (999)        0 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/docs/_templates/.placeholder
+-rw-r--r--   0 jenkins    (115) docker     (999)      127 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/docs/cli.rst
+-rw-r--r--   0 jenkins    (115) docker     (999)       43 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/docs/conf.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     2584 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/docs/configuration.rst
+-rw-r--r--   0 jenkins    (115) docker     (999)     9666 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/docs/design.md
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 14:21:20.535575 swh.fuse-1.0.6/docs/images/
+-rw-r--r--   0 jenkins    (115) docker     (999)      328 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/docs/images/Makefile
+-rw-r--r--   0 jenkins    (115) docker     (999)     9188 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/docs/images/arch-container.pdf
+-rw-r--r--   0 jenkins    (115) docker     (999)    51941 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/docs/images/arch-container.png
+-rw-r--r--   0 jenkins    (115) docker     (999)     1090 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/docs/images/arch-container.puml
+-rw-r--r--   0 jenkins    (115) docker     (999)    15223 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/docs/images/arch-container.svg
+-rw-r--r--   0 jenkins    (115) docker     (999)     3729 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/docs/images/arch-context.pdf
+-rw-r--r--   0 jenkins    (115) docker     (999)    14499 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/docs/images/arch-context.png
+-rw-r--r--   0 jenkins    (115) docker     (999)      508 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/docs/images/arch-context.puml
+-rw-r--r--   0 jenkins    (115) docker     (999)     6056 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/docs/images/arch-context.svg
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 14:21:20.535575 swh.fuse-1.0.6/docs/images/c4-plantuml/
+-rw-r--r--   0 jenkins    (115) docker     (999)     3872 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/docs/images/c4-plantuml/C4.puml
+-rw-r--r--   0 jenkins    (115) docker     (999)     1995 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/docs/images/c4-plantuml/C4_Component.puml
+-rw-r--r--   0 jenkins    (115) docker     (999)     2176 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/docs/images/c4-plantuml/C4_Container.puml
+-rw-r--r--   0 jenkins    (115) docker     (999)     3546 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/docs/images/c4-plantuml/C4_Context.puml
+-rw-r--r--   0 jenkins    (115) docker     (999)     1071 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/docs/images/c4-plantuml/LICENSE
+-rw-r--r--   0 jenkins    (115) docker     (999)      306 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/docs/index.rst
+-rw-r--r--   0 jenkins    (115) docker     (999)    10085 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/docs/tutorial.rst
+-rw-r--r--   0 jenkins    (115) docker     (999)      453 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/mypy.ini
+-rw-r--r--   0 jenkins    (115) docker     (999)      237 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/pyproject.toml
+-rw-r--r--   0 jenkins    (115) docker     (999)       62 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/pytest.ini
+-rw-r--r--   0 jenkins    (115) docker     (999)       62 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/requirements-swh.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)      140 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/requirements-test.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)       55 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/requirements.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)      120 2023-06-28 14:21:20.567575 swh.fuse-1.0.6/setup.cfg
+-rwxr-xr-x   0 jenkins    (115) docker     (999)     2344 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/setup.py
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 14:21:20.535575 swh.fuse-1.0.6/swh/
+-rw-r--r--   0 jenkins    (115) docker     (999)       76 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/swh/__init__.py
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 14:21:20.539575 swh.fuse-1.0.6/swh/fuse/
+-rw-r--r--   0 jenkins    (115) docker     (999)       23 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/swh/fuse/__init__.py
+-rw-r--r--   0 jenkins    (115) docker     (999)    14741 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/swh/fuse/cache.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     6491 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/swh/fuse/cli.py
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 14:21:20.539575 swh.fuse-1.0.6/swh/fuse/fs/
+-rw-r--r--   0 jenkins    (115) docker     (999)    22819 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/swh/fuse/fs/artifact.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     4387 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/swh/fuse/fs/entry.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     9011 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/swh/fuse/fs/mountpoint.py
+-rw-r--r--   0 jenkins    (115) docker     (999)    12929 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/swh/fuse/fuse.py
+-rw-r--r--   0 jenkins    (115) docker     (999)       27 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/swh/fuse/py.typed
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 14:21:20.539575 swh.fuse-1.0.6/swh/fuse/tests/
+-rw-r--r--   0 jenkins    (115) docker     (999)        0 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/swh/fuse/tests/__init__.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     1266 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/swh/fuse/tests/api_url.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     1393 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/swh/fuse/tests/common.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     2574 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/swh/fuse/tests/conftest.py
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 14:21:20.543575 swh.fuse-1.0.6/swh/fuse/tests/data/
+-rw-r--r--   0 jenkins    (115) docker     (999)        0 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/swh/fuse/tests/data/__init__.py
+-rw-r--r--   0 jenkins    (115) docker     (999)   185334 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/swh/fuse/tests/data/api_data.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     4152 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/swh/fuse/tests/data/config.py
+-rwxr-xr-x   0 jenkins    (115) docker     (999)     8356 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/swh/fuse/tests/data/gen-api-data.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     1261 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/swh/fuse/tests/test_cache.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     1143 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/swh/fuse/tests/test_cli.py
+-rw-r--r--   0 jenkins    (115) docker     (999)      434 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/swh/fuse/tests/test_content.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     1683 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/swh/fuse/tests/test_directory.py
+-rw-r--r--   0 jenkins    (115) docker     (999)      423 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/swh/fuse/tests/test_meta.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     1188 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/swh/fuse/tests/test_mountpoint.py
+-rw-r--r--   0 jenkins    (115) docker     (999)      807 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/swh/fuse/tests/test_origin.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     1420 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/swh/fuse/tests/test_release.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     3339 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/swh/fuse/tests/test_revision.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     1103 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/swh/fuse/tests/test_snapshot.py
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 14:21:20.539575 swh.fuse-1.0.6/swh.fuse.egg-info/
+-rw-r--r--   0 jenkins    (115) docker     (999)     2132 2023-06-28 14:21:20.000000 swh.fuse-1.0.6/swh.fuse.egg-info/PKG-INFO
+-rw-r--r--   0 jenkins    (115) docker     (999)     1938 2023-06-28 14:21:20.000000 swh.fuse-1.0.6/swh.fuse.egg-info/SOURCES.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)        1 2023-06-28 14:21:20.000000 swh.fuse-1.0.6/swh.fuse.egg-info/dependency_links.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)       42 2023-06-28 14:21:20.000000 swh.fuse-1.0.6/swh.fuse.egg-info/entry_points.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)      202 2023-06-28 14:21:20.000000 swh.fuse-1.0.6/swh.fuse.egg-info/requires.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)        4 2023-06-28 14:21:20.000000 swh.fuse-1.0.6/swh.fuse.egg-info/top_level.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)     1477 2023-06-28 14:21:13.000000 swh.fuse-1.0.6/tox.ini
```

### filetype from file(1)

```diff
@@ -1 +1 @@
-POSIX tar archive (GNU)
+POSIX tar archive
```

### Comparing `swh.fuse-1.0.5/.pre-commit-config.yaml` & `swh.fuse-1.0.6/.pre-commit-config.yaml`

 * *Files 9% similar despite different names*

```diff
@@ -1,43 +1,41 @@
 repos:
   - repo: https://github.com/pre-commit/pre-commit-hooks
-    rev: v4.1.0
+    rev: v4.3.0
     hooks:
       - id: trailing-whitespace
       - id: check-json
       - id: check-yaml
 
-  - repo: https://gitlab.com/pycqa/flake8
-    rev: 4.0.1
+  - repo: https://github.com/pycqa/flake8
+    rev: 5.0.4
     hooks:
       - id: flake8
+        additional_dependencies: [flake8-bugbear==22.9.23]
 
   - repo: https://github.com/codespell-project/codespell
-    rev: v2.1.0
+    rev: v2.2.2
     hooks:
       - id: codespell
         name: Check source code spelling
         args: [-L nin, -L nIn, -L crate, -L grammer]
         stages: [commit]
-      - id: codespell
-        name: Check commit message spelling
-        stages: [commit-msg]
 
   - repo: local
     hooks:
       - id: mypy
         name: mypy
         entry: env DJANGO_SETTINGS_MODULE=swh.deposit.settings.testing mypy
         args: [swh]
         pass_filenames: false
         language: system
         types: [python]
 
   - repo: https://github.com/PyCQA/isort
-    rev: 5.10.1
+    rev: 5.11.5
     hooks:
       - id: isort
 
   - repo: https://github.com/python/black
-    rev: 19.10b0
+    rev: 22.10.0
     hooks:
       - id: black
```

### Comparing `swh.fuse-1.0.5/CODE_OF_CONDUCT.md` & `swh.fuse-1.0.6/CODE_OF_CONDUCT.md`

 * *Files identical despite different names*

### Comparing `swh.fuse-1.0.5/LICENSE` & `swh.fuse-1.0.6/LICENSE`

 * *Files identical despite different names*

### Comparing `swh.fuse-1.0.5/PKG-INFO` & `swh.fuse-1.0.6/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,20 +1,18 @@
 Metadata-Version: 2.1
 Name: swh.fuse
-Version: 1.0.5
+Version: 1.0.6
 Summary: Software Heritage virtual file system
 Home-page: https://forge.softwareheritage.org/source/swh-fuse
 Author: Software Heritage developers
 Author-email: swh-devel@inria.fr
-License: UNKNOWN
 Project-URL: Bug Reports, https://forge.softwareheritage.org/maniphest
 Project-URL: Funding, https://www.softwareheritage.org/donate
 Project-URL: Source, https://forge.softwareheritage.org/source/swh-fuse
 Project-URL: Documentation, https://docs.softwareheritage.org/devel/swh-fuse/
-Platform: UNKNOWN
 Classifier: Programming Language :: Python :: 3
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: GNU General Public License v3 (GPLv3)
 Classifier: Operating System :: OS Independent
 Classifier: Development Status :: 3 - Alpha
 Requires-Python: >=3.7
 Description-Content-Type: text/x-rst
@@ -52,9 +50,7 @@
   Filesystem (SwhFS): Integrating Source Code Archival with Development
   <https://arxiv.org/pdf/2102.06390.pdf>`_. In proceedings of `ICSE 2021
   <https://conf.researchr.org/home/icse-2021>`_: The 43rd International
   Conference on Software Engineering, May 2021, Madrid, Spain. IEEE 2021.
 
   Links: `preprint <https://arxiv.org/pdf/2102.06390.pdf>`_, `bibtex
   <https://upsilon.cc/~zack/research/publications/saner-2020-swh-graph.bib>`_.
-
-
```

### Comparing `swh.fuse-1.0.5/README.rst` & `swh.fuse-1.0.6/README.rst`

 * *Files identical despite different names*

### Comparing `swh.fuse-1.0.5/debian/control` & `swh.fuse-1.0.6/debian/control`

 * *Files identical despite different names*

### Comparing `swh.fuse-1.0.5/debian/copyright` & `swh.fuse-1.0.6/debian/copyright`

 * *Files identical despite different names*

### Comparing `swh.fuse-1.0.5/docs/README.rst` & `swh.fuse-1.0.6/docs/README.rst`

 * *Files identical despite different names*

### Comparing `swh.fuse-1.0.5/docs/configuration.rst` & `swh.fuse-1.0.6/docs/configuration.rst`

 * *Files identical despite different names*

### Comparing `swh.fuse-1.0.5/docs/design.md` & `swh.fuse-1.0.6/docs/design.md`

 * *Files identical despite different names*

### Comparing `swh.fuse-1.0.5/docs/images/arch-container.pdf` & `swh.fuse-1.0.6/docs/images/arch-container.pdf`

 * *Files identical despite different names*

### Comparing `swh.fuse-1.0.5/docs/images/arch-container.png` & `swh.fuse-1.0.6/docs/images/arch-container.png`

 * *Files identical despite different names*

### Comparing `swh.fuse-1.0.5/docs/images/arch-container.puml` & `swh.fuse-1.0.6/docs/images/arch-container.puml`

 * *Files identical despite different names*

### Comparing `swh.fuse-1.0.5/docs/images/arch-container.svg` & `swh.fuse-1.0.6/docs/images/arch-container.svg`

 * *Files identical despite different names*

### Comparing `swh.fuse-1.0.5/docs/images/arch-context.pdf` & `swh.fuse-1.0.6/docs/images/arch-context.pdf`

 * *Files identical despite different names*

### Comparing `swh.fuse-1.0.5/docs/images/arch-context.png` & `swh.fuse-1.0.6/docs/images/arch-context.png`

 * *Files identical despite different names*

### Comparing `swh.fuse-1.0.5/docs/images/arch-context.svg` & `swh.fuse-1.0.6/docs/images/arch-context.svg`

 * *Files identical despite different names*

### Comparing `swh.fuse-1.0.5/docs/images/c4-plantuml/C4.puml` & `swh.fuse-1.0.6/docs/images/c4-plantuml/C4.puml`

 * *Files identical despite different names*

### Comparing `swh.fuse-1.0.5/docs/images/c4-plantuml/C4_Component.puml` & `swh.fuse-1.0.6/docs/images/c4-plantuml/C4_Component.puml`

 * *Files identical despite different names*

### Comparing `swh.fuse-1.0.5/docs/images/c4-plantuml/C4_Container.puml` & `swh.fuse-1.0.6/docs/images/c4-plantuml/C4_Container.puml`

 * *Files identical despite different names*

### Comparing `swh.fuse-1.0.5/docs/images/c4-plantuml/C4_Context.puml` & `swh.fuse-1.0.6/docs/images/c4-plantuml/C4_Context.puml`

 * *Files identical despite different names*

### Comparing `swh.fuse-1.0.5/docs/images/c4-plantuml/LICENSE` & `swh.fuse-1.0.6/docs/images/c4-plantuml/LICENSE`

 * *Files identical despite different names*

### Comparing `swh.fuse-1.0.5/docs/tutorial.rst` & `swh.fuse-1.0.6/docs/tutorial.rst`

 * *Files identical despite different names*

### Comparing `swh.fuse-1.0.5/setup.py` & `swh.fuse-1.0.6/setup.py`

 * *Files identical despite different names*

### Comparing `swh.fuse-1.0.5/swh/fuse/cache.py` & `swh.fuse-1.0.6/swh/fuse/cache.py`

 * *Files 2% similar despite different names*

```diff
@@ -76,35 +76,35 @@
 
     async def __aexit__(self, type=None, val=None, tb=None) -> None:
         await self.metadata.__aexit__()
         await self.blob.__aexit__()
         await self.history.__aexit__()
 
     async def get_cached_swhids(self) -> AsyncGenerator[CoreSWHID, None]:
-        """ Return a list of all previously cached SWHID """
+        """Return a list of all previously cached SWHID"""
 
         # Use the metadata db since it should always contain all accessed SWHIDs
         metadata_cursor = await self.metadata.conn.execute(
             "select swhid from metadata_cache"
         )
         swhids = await metadata_cursor.fetchall()
         for raw_swhid in swhids:
             yield CoreSWHID.from_string(raw_swhid[0])
 
     async def get_cached_visits(self) -> AsyncGenerator[str, None]:
-        """ Return a list of all previously cached visit URL """
+        """Return a list of all previously cached visit URL"""
 
         cursor = await self.metadata.conn.execute("select url from visits_cache")
         urls = await cursor.fetchall()
         for raw_url in urls:
             yield raw_url[0]
 
 
 class AbstractCache(ABC):
-    """ Abstract cache implementation to share common behavior between cache types """
+    """Abstract cache implementation to share common behavior between cache types"""
 
     DB_SCHEMA: str = ""
     conf: Dict[str, Any]
     conn: aiosqlite.Connection
 
     def __init__(
         self, conf: Dict[str, Any], conn: Optional[aiosqlite.Connection] = None
@@ -125,19 +125,19 @@
     async def __aexit__(self, type=None, val=None, tb=None) -> None:
         # In case we were given an existing connection, do not close it here
         if self.init_conn is None:
             await self.conn.close()
 
 
 class MetadataCache(AbstractCache):
-    """ The metadata cache map each artifact to the complete metadata of the
+    """The metadata cache map each artifact to the complete metadata of the
     referenced object. This is analogous to what is available in
     `archive/<SWHID>.json` file (and generally used as data source for returning
     the content of those files). Artifacts are identified using their SWHIDs, or
-    in the case of origin visits, using their URLs. """
+    in the case of origin visits, using their URLs."""
 
     DB_SCHEMA = """
         create table if not exists metadata_cache (
             swhid text not null primary key,
             metadata blob,
             date text
         );
@@ -162,15 +162,16 @@
                 else metadata
             )
         else:
             return None
 
     async def get_visits(self, url_encoded: str) -> Optional[List[Dict[str, Any]]]:
         cursor = await self.conn.execute(
-            "select metadata, itime from visits_cache where url=?", (url_encoded,),
+            "select metadata, itime from visits_cache where url=?",
+            (url_encoded,),
         )
         cache = await cursor.fetchone()
         if cache:
             metadata, itime = cache[0], cache[1]
             # Force-update cache with (potentially) new origin visits
             diff = datetime.now() - itime
             if diff.days >= 1:
@@ -202,27 +203,28 @@
             "insert or replace into visits_cache values (?, ?, ?)",
             (url_encoded, json.dumps(visits), datetime.now()),
         )
         await self.conn.commit()
 
     async def remove(self, swhid: CoreSWHID) -> None:
         await self.conn.execute(
-            "delete from metadata_cache where swhid=?", (str(swhid),),
+            "delete from metadata_cache where swhid=?",
+            (str(swhid),),
         )
         await self.conn.commit()
 
 
 class BlobCache(AbstractCache):
-    """ The blob cache map SWHIDs of type `cnt` to the bytes of their archived
+    """The blob cache map SWHIDs of type `cnt` to the bytes of their archived
     content.
 
     The blob cache entry for a given content object is populated, at the latest,
     the first time the object is `read()`-d. It might be populated earlier on
     due to prefetching, e.g., when a directory pointing to the given content is
-    listed for the first time. """
+    listed for the first time."""
 
     DB_SCHEMA = """
         create table if not exists blob_cache (
             swhid text not null primary key,
             blob blob
         );
     """
@@ -242,26 +244,27 @@
         await self.conn.execute(
             "insert into blob_cache values (?, ?)", (str(swhid), blob)
         )
         await self.conn.commit()
 
     async def remove(self, swhid: CoreSWHID) -> None:
         await self.conn.execute(
-            "delete from blob_cache where swhid=?", (str(swhid),),
+            "delete from blob_cache where swhid=?",
+            (str(swhid),),
         )
         await self.conn.commit()
 
 
 class HistoryCache(AbstractCache):
-    """ The history cache map SWHIDs of type `rev` to a list of `rev` SWHIDs
+    """The history cache map SWHIDs of type `rev` to a list of `rev` SWHIDs
     corresponding to all its revision ancestors, sorted in reverse topological
     order. As the parents cache, the history cache is lazily populated and can
     be prefetched. To efficiently store the ancestor lists, the history cache
     represents ancestors as graph edges (a pair of two SWHID nodes), meaning the
-    history cache is shared amongst all revisions parents. """
+    history cache is shared amongst all revisions parents."""
 
     DB_SCHEMA = """
         create table if not exists history_graph (
             src text not null,
             dst text not null,
             unique(src, dst)
         );
@@ -278,15 +281,18 @@
             join dfs on history_graph.src = dfs.node
         )
         -- Do not keep the root node since it is not an ancestor
         select * from dfs limit -1 offset 1
     """
 
     async def get(self, swhid: CoreSWHID) -> Optional[List[CoreSWHID]]:
-        cursor = await self.conn.execute(self.HISTORY_REC_QUERY, (str(swhid),),)
+        cursor = await self.conn.execute(
+            self.HISTORY_REC_QUERY,
+            (str(swhid),),
+        )
         cache = await cursor.fetchall()
         if not cache:
             return None
         history = []
         for row in cache:
             parent = row[0]
             try:
@@ -326,26 +332,26 @@
             await self.conn.executemany(
                 "insert or ignore into history_graph values (?, ?)", edges
             )
             await self.conn.commit()
 
 
 class DirEntryCache:
-    """ The direntry cache map inode representing directories to the entries
+    """The direntry cache map inode representing directories to the entries
     they contain. Each entry comes with its name as well as file attributes
     (i.e., all its needed to perform a detailed directory listing).
 
     Additional attributes of each directory entry should be looked up on a entry
     by entry basis, possibly hitting other caches.
 
     The direntry cache for a given dir is populated, at the latest, when the
     content of the directory is listed. More aggressive prefetching might
     happen. For instance, when first opening a dir a recursive listing of it can
     be retrieved from the remote backend and used to recursively populate the
-    direntry cache for all (transitive) sub-directories. """
+    direntry cache for all (transitive) sub-directories."""
 
     @dataclass
     class LRU(OrderedDict):
         max_ram: int
         used_ram: int = field(init=False, default=0)
 
         def sizeof(self, value: Any) -> int:
@@ -381,15 +387,15 @@
 
         num = float(m.group(1))
         unit = m.group(2).upper()
 
         if unit == "%":
             max_ram = int(num * virtual_memory().available / 100)
         else:
-            units = {"B": 1, "KB": 10 ** 3, "MB": 10 ** 6, "GB": 10 ** 9}
+            units = {"B": 1, "KB": 10**3, "MB": 10**6, "GB": 10**9}
             max_ram = int(float(num) * units[unit])
 
         self.lru_cache = self.LRU(max_ram)
 
     def get(self, direntry: FuseDirEntry) -> Optional[List[FuseEntry]]:
         return self.lru_cache.get(direntry.inode, None)
```

### Comparing `swh.fuse-1.0.5/swh/fuse/cli.py` & `swh.fuse-1.0.6/swh/fuse/cli.py`

 * *Files 2% similar despite different names*

```diff
@@ -64,15 +64,15 @@
         ctx.exit(1)
 
     if not config_file:
         config_file = DEFAULT_CONFIG_PATH
 
     if os.path.isfile(config_file):
         try:
-            conf = config.read_raw_config(config.config_basepath(config_file))
+            conf = config.read_raw_config(config_file)
             if not conf:
                 raise ValueError(f"Cannot parse configuration file: {config_file}")
 
             if config_file == DEFAULT_CONFIG_PATH:
                 try:
                     conf = conf["swh"]["fuse"]
                 except KeyError:
@@ -157,15 +157,18 @@
                     "handlers": {
                         "syslog": {
                             "class": "logging.handlers.SysLogHandler",
                             "address": "/dev/log",
                         },
                     },
                     "loggers": {
-                        LOGGER_NAME: {"level": log_level, "handlers": ["syslog"],},
+                        LOGGER_NAME: {
+                            "level": log_level,
+                            "handlers": ["syslog"],
+                        },
                     },
                 }
             )
 
         conf = ctx.obj["config"]
         asyncio.run(fuse.main(swhids, path, conf))
 
@@ -198,17 +201,15 @@
         )
         ctx.exit(1)
 
 
 @fuse.command()
 @click.pass_context
 def clean(ctx):
-    """Clean on-disk cache(s).
-
-    """
+    """Clean on-disk cache(s)."""
 
     def rm_cache(conf, cache_name):
         try:
             Path(conf["cache"][cache_name]["path"]).unlink()
         except (FileNotFoundError, KeyError):
             pass
```

### Comparing `swh.fuse-1.0.5/swh/fuse/fs/artifact.py` & `swh.fuse-1.0.6/swh/fuse/fs/artifact.py`

 * *Files 3% similar despite different names*

```diff
@@ -24,23 +24,23 @@
 from swh.model.swhids import CoreSWHID, ObjectType
 
 SWHID_REGEXP = r"swh:1:(cnt|dir|rel|rev|snp):[0-9a-f]{40}"
 
 
 @dataclass
 class Content(FuseFileEntry):
-    """ Software Heritage content artifact.
+    """Software Heritage content artifact.
 
     Content leaves (AKA blobs) are represented on disks as regular files,
     containing the corresponding bytes, as archived.
 
     Note that permissions are associated to blobs only in the context of
     directories. Hence, when accessing blobs from the top-level `archive/`
     directory, the permissions of the `archive/SWHID` file will be arbitrary and
-    not meaningful (e.g., `0x644`). """
+    not meaningful (e.g., `0x644`)."""
 
     swhid: CoreSWHID
     prefetch: Any = None
     """optional prefetched metadata used to set entry attributes"""
 
     async def get_content(self) -> bytes:
         data = await self.fuse.get_blob(self.swhid)
@@ -53,24 +53,24 @@
             return self.prefetch["length"]
         else:
             return await super().size()
 
 
 @dataclass
 class Directory(FuseDirEntry):
-    """ Software Heritage directory artifact.
+    """Software Heritage directory artifact.
 
     Directory nodes are represented as directories on the file-system,
     containing one entry for each entry of the archived directory. Entry names
     and other metadata, including permissions, will correspond to the archived
     entry metadata.
 
     Note that the FUSE mount is read-only, no matter what the permissions say.
     So it is possible that, in the context of a directory, a file is presented
-    as writable, whereas actually writing to it will fail with `EPERM`. """
+    as writable, whereas actually writing to it will fail with `EPERM`."""
 
     swhid: CoreSWHID
 
     async def compute_entries(self) -> AsyncIterator[FuseEntry]:
         metadata = await self.fuse.get_metadata(self.swhid)
         for entry in metadata:
             name = entry["name"]
@@ -89,15 +89,17 @@
                 try:
                     # Symlink target is stored in the blob content
                     target = await self.fuse.get_blob(swhid)
                 except Exception:
                     pass  # Ignore error and create a (broken) symlink anyway
 
                 yield self.create_child(
-                    FuseSymlinkEntry, name=name, target=target,
+                    FuseSymlinkEntry,
+                    name=name,
+                    target=target,
                 )
             # 2. Regular file
             elif swhid.object_type == ObjectType.CONTENT:
                 yield self.create_child(
                     Content,
                     name=name,
                     mode=mode,
@@ -105,15 +107,18 @@
                     # The directory API has extra info we can use to set
                     # attributes without additional Software Heritage API call
                     prefetch=entry,
                 )
             # 3. Regular directory
             elif swhid.object_type == ObjectType.DIRECTORY:
                 yield self.create_child(
-                    Directory, name=name, mode=mode, swhid=swhid,
+                    Directory,
+                    name=name,
+                    mode=mode,
+                    swhid=swhid,
                 )
             # 4. Submodule
             elif swhid.object_type == ObjectType.REVISION:
                 try:
                     # Make sure the revision metadata is fetched and create a
                     # symlink to distinguish it with regular directories
                     await self.fuse.get_metadata(swhid)
@@ -127,15 +132,15 @@
                 )
             else:
                 raise ValueError("Unknown directory entry type: {swhid.object_type}")
 
 
 @dataclass
 class Revision(FuseDirEntry):
-    """ Software Heritage revision artifact.
+    """Software Heritage revision artifact.
 
     Revision (AKA commit) nodes are represented on the file-system as
     directories with the following entries:
 
     - `root`: source tree at the time of the commit, as a symlink pointing into
       `archive/`, to a SWHID of type `dir`
     - `parents/` (note the plural): a virtual directory containing entries named
@@ -145,15 +150,15 @@
     - `parent` (note the singular): present if and only if the current commit
       has at least one parent commit (which is the most common case). When
       present it is a symlink pointing into `parents/1/`
     - `history`: a virtual directory listing all its revision ancestors, sorted
       in reverse topological order. The history can be listed through
       `by-date/`, `by-hash/` or `by-page/` with each its own sharding policy.
     - `meta.json`: metadata for the current node, as a symlink pointing to the
-      relevant `archive/<SWHID>.json` file """
+      relevant `archive/<SWHID>.json` file"""
 
     swhid: CoreSWHID
 
     async def compute_entries(self) -> AsyncIterator[FuseEntry]:
         metadata = await self.fuse.get_metadata(self.swhid)
         directory = metadata["directory"]
         parents = metadata["parents"]
@@ -175,28 +180,30 @@
             name="parents",
             mode=int(EntryMode.RDONLY_DIR),
             parents=[x["id"] for x in parents],
         )
 
         if len(parents) >= 1:
             yield self.create_child(
-                FuseSymlinkEntry, name="parent", target="parents/1/",
+                FuseSymlinkEntry,
+                name="parent",
+                target="parents/1/",
             )
 
         yield self.create_child(
             RevisionHistory,
             name="history",
             mode=int(EntryMode.RDONLY_DIR),
             swhid=self.swhid,
         )
 
 
 @dataclass
 class RevisionParents(FuseDirEntry):
-    """ Revision virtual `parents/` directory """
+    """Revision virtual `parents/` directory"""
 
     parents: List[CoreSWHID]
 
     async def compute_entries(self) -> AsyncIterator[FuseEntry]:
         root_path = self.get_relative_root_path()
         for i, parent in enumerate(self.parents):
             yield self.create_child(
@@ -204,15 +211,15 @@
                 name=str(i + 1),
                 target=Path(root_path, f"archive/{parent}"),
             )
 
 
 @dataclass
 class RevisionHistory(FuseDirEntry):
-    """ Revision virtual `history/` directory """
+    """Revision virtual `history/` directory"""
 
     swhid: CoreSWHID
 
     async def prefill_by_date_cache(self, by_date_dir: FuseDirEntry) -> None:
         history = await self.fuse.get_history(self.swhid)
         nb_api_calls = 0
         for swhid in history:
@@ -258,26 +265,26 @@
             mode=int(EntryMode.RDONLY_DIR),
             history_swhid=self.swhid,
         )
 
 
 @dataclass
 class RevisionHistoryShardByDate(FuseDirEntry):
-    """ Revision virtual `history/by-date` sharded directory """
+    """Revision virtual `history/by-date` sharded directory"""
 
     history_swhid: CoreSWHID
     prefix: str = field(default="")
     is_status_done: bool = field(default=False)
 
     DATE_FMT = "{year:04d}/{month:02d}/{day:02d}/"
     ENTRIES_REGEXP = re.compile(r"^([0-9]{2,4})|(" + SWHID_REGEXP + ")$")
 
     @dataclass
     class StatusFile(FuseFileEntry):
-        """ Temporary file used to indicate loading progress in by-date/ """
+        """Temporary file used to indicate loading progress in by-date/"""
 
         name: str = field(init=False, default=".status")
         mode: int = field(init=False, default=int(EntryMode.RDONLY_FILE))
         history_swhid: CoreSWHID
 
         def __post_init__(self):
             super().__post_init__()
@@ -341,15 +348,15 @@
             self.fuse._remove_inode(self.status_file.inode)
         elif not self.is_status_done and depth == 0:
             yield self.status_file
 
 
 @dataclass
 class RevisionHistoryShardByHash(FuseDirEntry):
-    """ Revision virtual `history/by-hash` sharded directory """
+    """Revision virtual `history/by-hash` sharded directory"""
 
     history_swhid: CoreSWHID
     prefix: str = field(default="")
 
     SHARDING_LENGTH = 2
     ENTRIES_REGEXP = re.compile(r"^([a-f0-9]+)|(" + SWHID_REGEXP + ")$")
 
@@ -379,15 +386,15 @@
                         prefix=next_prefix,
                         history_swhid=self.history_swhid,
                     )
 
 
 @dataclass
 class RevisionHistoryShardByPage(FuseDirEntry):
-    """ Revision virtual `history/by-page` sharded directory """
+    """Revision virtual `history/by-page` sharded directory"""
 
     history_swhid: CoreSWHID
     prefix: Optional[int] = field(default=None)
 
     PAGE_SIZE = 10_000
     PAGE_FMT = "{page_number:03d}"
     ENTRIES_REGEXP = re.compile(r"^([0-9]+)|(" + SWHID_REGEXP + ")$")
@@ -417,26 +424,26 @@
                     history_swhid=self.history_swhid,
                     prefix=page_number,
                 )
 
 
 @dataclass
 class Release(FuseDirEntry):
-    """ Software Heritage release artifact.
+    """Software Heritage release artifact.
 
     Release nodes are represented on the file-system as directories with the
     following entries:
 
     - `target`: target node, as a symlink to `archive/<SWHID>`
     - `target_type`: regular file containing the type of the target SWHID
     - `root`: present if and only if the release points to something that
       (transitively) resolves to a directory. When present it is a symlink
       pointing into `archive/` to the SWHID of the given directory
     - `meta.json`: metadata for the current node, as a symlink pointing to the
-      relevant `archive/<SWHID>.json` file """
+      relevant `archive/<SWHID>.json` file"""
 
     swhid: CoreSWHID
 
     async def find_root_directory(self, swhid: CoreSWHID) -> Optional[CoreSWHID]:
         if swhid.object_type == ObjectType.RELEASE:
             metadata = await self.fuse.get_metadata(swhid)
             return await self.find_root_directory(metadata["target"])
@@ -476,31 +483,31 @@
                 name="root",
                 target=Path(root_path, f"archive/{target_dir}"),
             )
 
 
 @dataclass
 class ReleaseType(FuseFileEntry):
-    """ Release type virtual file """
+    """Release type virtual file"""
 
     target_type: ObjectType
 
     async def get_content(self) -> bytes:
         return str.encode(self.target_type.name.lower() + "\n")
 
 
 @dataclass
 class Snapshot(FuseDirEntry):
-    """ Software Heritage snapshot artifact.
+    """Software Heritage snapshot artifact.
 
     Snapshot nodes are represented on the file-system as recursive directories
     following the branch names structure. For example, a branch named
     ``refs/tags/v1.0`` will be represented as a ``refs`` directory containing a
     ``tags`` directory containing a ``v1.0`` symlink pointing to the branch
-    target SWHID. """
+    target SWHID."""
 
     swhid: CoreSWHID
     prefix: str = field(default="")
 
     async def compute_entries(self) -> AsyncIterator[FuseEntry]:
         metadata = await self.fuse.get_metadata(self.swhid)
         root_path = self.get_relative_root_path()
@@ -522,15 +529,17 @@
                 if target_type == "alias":
                     prefix = Path(branch_name).parent
                     target = os.path.relpath(target_raw, prefix)
                 else:
                     target = f"{root_path}/archive/{target_raw}"
 
                 yield self.create_child(
-                    FuseSymlinkEntry, name=next_prefix, target=Path(target),
+                    FuseSymlinkEntry,
+                    name=next_prefix,
+                    target=Path(target),
                 )
             else:
                 subdirs.add(next_prefix)
 
         for subdir in subdirs:
             yield self.create_child(
                 Snapshot,
@@ -539,24 +548,24 @@
                 swhid=self.swhid,
                 prefix=f"{self.prefix}{subdir}/",
             )
 
 
 @dataclass
 class Origin(FuseDirEntry):
-    """ Software Heritage origin artifact.
+    """Software Heritage origin artifact.
 
     Origin nodes are represented on the file-system as directories with one
     entry for each origin visit.
 
     The visits directories are named after the visit date (`YYYY-MM-DD`, if
     multiple visits occur the same day only the first one is kept). Each visit
     directory contains a `meta.json` with associated metadata for the origin
     node, and potentially a `snapshot` symlink pointing to the visit's snapshot
-    node. """
+    node."""
 
     DATE_FMT = "{year:04d}-{month:02d}-{day:02d}"
     ENTRIES_REGEXP = re.compile(r"^[0-9]{4}-[0-9]{2}-[0-9]{2}$")
 
     async def compute_entries(self) -> AsyncIterator[FuseEntry]:
         # The origin's name is always its URL (encoded to create a valid UNIX filename)
         visits = await self.fuse.get_visits(self.name)
@@ -569,21 +578,24 @@
             if name in seen_date:
                 logging.debug(
                     "Conflict date on origin: %s, %s", visit["origin"], str(name)
                 )
             else:
                 seen_date.add(name)
                 yield self.create_child(
-                    OriginVisit, name=name, mode=int(EntryMode.RDONLY_DIR), meta=visit,
+                    OriginVisit,
+                    name=name,
+                    mode=int(EntryMode.RDONLY_DIR),
+                    meta=visit,
                 )
 
 
 @dataclass
 class OriginVisit(FuseDirEntry):
-    """ Origin visit virtual directory """
+    """Origin visit virtual directory"""
 
     meta: Dict[str, Any]
 
     @dataclass
     class MetaFile(FuseFileEntry):
         content: str
```

### Comparing `swh.fuse-1.0.5/swh/fuse/fs/entry.py` & `swh.fuse-1.0.6/swh/fuse/fs/entry.py`

 * *Files 4% similar despite different names*

```diff
@@ -13,15 +13,15 @@
 from typing import TYPE_CHECKING, Any, AsyncIterator, Dict, Optional, Pattern, Union
 
 if TYPE_CHECKING:  # avoid cyclic import
     from swh.fuse.fuse import Fuse
 
 
 class EntryMode(IntEnum):
-    """ Default entry mode and permissions for the FUSE.
+    """Default entry mode and permissions for the FUSE.
 
     The FUSE mount is always read-only, even if permissions contradict this
     statement (in a context of a directory, entries are listed with permissions
     taken from the archive).
     """
 
     RDONLY_FILE = S_IFREG | 0o444
@@ -31,16 +31,15 @@
     # `cache/` sub-directories need the write permission in order to invalidate
     # cached artifacts using `rm {SWHID}`
     RDWR_DIR = S_IFDIR | 0o755
 
 
 @dataclass
 class FuseEntry:
-    """ Main wrapper class to manipulate virtual FUSE entries
-    """
+    """Main wrapper class to manipulate virtual FUSE entries"""
 
     name: str
     """entry filename"""
     mode: int
     """entry permission mode"""
     depth: int
     fuse: Fuse
@@ -51,15 +50,15 @@
 
     def __post_init__(self):
         self.inode = self.fuse._alloc_inode(self)
         # By default, let the kernel cache previously accessed data
         self.file_info_attrs["keep_cache"] = True
 
     async def size(self) -> int:
-        """ Return the size (in bytes) of an entry """
+        """Return the size (in bytes) of an entry"""
 
         raise NotImplementedError
 
     async def unlink(self, name: str) -> None:
         raise NotImplementedError
 
     def get_relative_root_path(self) -> str:
@@ -67,81 +66,80 @@
 
     def create_child(self, constructor: Any, **kwargs) -> FuseEntry:
         return constructor(depth=self.depth + 1, fuse=self.fuse, **kwargs)
 
 
 @dataclass
 class FuseFileEntry(FuseEntry):
-    """ FUSE virtual file entry """
+    """FUSE virtual file entry"""
 
     async def get_content(self) -> bytes:
-        """ Return the content of a file entry """
+        """Return the content of a file entry"""
 
         raise NotImplementedError
 
     async def size(self) -> int:
         return len(await self.get_content())
 
 
 @dataclass
 class FuseDirEntry(FuseEntry):
-    """ FUSE virtual directory entry """
+    """FUSE virtual directory entry"""
 
     ENTRIES_REGEXP: Optional[Pattern] = field(init=False, default=None)
 
     async def size(self) -> int:
         return 0
 
     def validate_entry(self, name: str) -> bool:
-        """ Return true if the name matches the directory entries regular
-        expression, and false otherwise """
+        """Return true if the name matches the directory entries regular
+        expression, and false otherwise"""
 
         if self.ENTRIES_REGEXP:
             return bool(re.match(self.ENTRIES_REGEXP, name))
         else:
             return True
 
     async def compute_entries(self):
-        """ Return the child entries of a directory entry """
+        """Return the child entries of a directory entry"""
 
         raise NotImplementedError
 
     async def get_entries(self, offset: int = 0) -> AsyncIterator[FuseEntry]:
-        """ Return the child entries of a directory entry using direntry cache """
+        """Return the child entries of a directory entry using direntry cache"""
 
         cache = self.fuse.cache.direntry.get(self)
         if cache:
             entries = cache
         else:
             entries = [x async for x in self.compute_entries()]
             self.fuse.cache.direntry.set(self, entries)
 
         # Avoid copy by manual iteration (instead of slicing) and use of a
         # generator (instead of returning the full list every time)
         for i in range(offset, len(entries)):
             yield entries[i]
 
     async def lookup(self, name: str) -> Optional[FuseEntry]:
-        """ Look up a FUSE entry by name """
+        """Look up a FUSE entry by name"""
 
         async for entry in self.get_entries():
             if entry.name == name:
                 return entry
         return None
 
 
 @dataclass
 class FuseSymlinkEntry(FuseEntry):
-    """ FUSE virtual symlink entry
-    """
+    """FUSE virtual symlink entry"""
 
     mode: int = field(init=False, default=int(EntryMode.RDONLY_LNK))
     target: Union[str, bytes, Path]
     """path to symlink target"""
 
     async def size(self) -> int:
         return len(str(self.target))
 
     def get_target(self) -> Union[str, bytes, Path]:
-        """ Return the path target of a symlink entry """
+        """Return the path target of a symlink entry"""
 
         return self.target
```

### Comparing `swh.fuse-1.0.5/swh/fuse/fs/mountpoint.py` & `swh.fuse-1.0.6/swh/fuse/fs/mountpoint.py`

 * *Files 3% similar despite different names*

```diff
@@ -22,35 +22,35 @@
 from swh.model.swhids import CoreSWHID, ObjectType
 
 JSON_SUFFIX = ".json"
 
 
 @dataclass
 class Root(FuseDirEntry):
-    """ The FUSE mountpoint, consisting of the archive/ and origin/ directories """
+    """The FUSE mountpoint, consisting of the archive/ and origin/ directories"""
 
     name: str = field(init=False, default="")
     mode: int = field(init=False, default=int(EntryMode.RDONLY_DIR))
     depth: int = field(init=False, default=1)
 
     async def compute_entries(self) -> AsyncIterator[FuseEntry]:
         yield self.create_child(ArchiveDir)
         yield self.create_child(OriginDir)
         yield self.create_child(CacheDir)
         yield self.create_child(Readme)
 
 
 @dataclass
 class ArchiveDir(FuseDirEntry):
-    """ The `archive/` virtual directory allows to mount any artifact on the fly
+    """The `archive/` virtual directory allows to mount any artifact on the fly
     using its SWHID as name. The associated metadata of the artifact from the
     Software Heritage Web API can also be accessed through the `SWHID.json` file
     (in case of pagination, the JSON file will contain a complete version with
     all pages merged together). Note: the archive directory cannot be listed
-    with ls, but entries in it can be accessed (e.g., using cat or cd). """
+    with ls, but entries in it can be accessed (e.g., using cat or cd)."""
 
     name: str = field(init=False, default="archive")
     mode: int = field(init=False, default=int(EntryMode.RDONLY_DIR))
 
     ENTRIES_REGEXP = re.compile(r"^(" + SWHID_REGEXP + ")(.json)?$")
 
     async def compute_entries(self) -> AsyncIterator[FuseEntry]:
@@ -83,16 +83,16 @@
                 )
         except ValidationError:
             return None
 
 
 @dataclass
 class MetaEntry(FuseFileEntry):
-    """ An entry for a `archive/<SWHID>.json` file, containing all the SWHID's
-    metadata from the Software Heritage archive. """
+    """An entry for a `archive/<SWHID>.json` file, containing all the SWHID's
+    metadata from the Software Heritage archive."""
 
     swhid: CoreSWHID
 
     async def get_content(self) -> bytes:
         # Make sure the metadata is in cache
         await self.fuse.get_metadata(self.swhid)
         # Retrieve raw JSON metadata from cache (un-typified)
@@ -102,26 +102,28 @@
 
     async def size(self) -> int:
         return len(await self.get_content())
 
 
 @dataclass
 class OriginDir(FuseDirEntry):
-    """ The origin/ directory is lazily populated with one entry per accessed
+    """The origin/ directory is lazily populated with one entry per accessed
     origin URL (mangled to create a valid UNIX filename). The URL encoding is
-    done using the percent-encoding mechanism described in RFC 3986. """
+    done using the percent-encoding mechanism described in RFC 3986."""
 
     name: str = field(init=False, default="origin")
     mode: int = field(init=False, default=int(EntryMode.RDONLY_DIR))
 
     ENTRIES_REGEXP = re.compile(r"^.*%3A.*$")  # %3A is the encoded version of ':'
 
     def create_origin_child(self, url_encoded: str) -> FuseEntry:
         return super().create_child(
-            Origin, name=url_encoded, mode=int(EntryMode.RDONLY_DIR),
+            Origin,
+            name=url_encoded,
+            mode=int(EntryMode.RDONLY_DIR),
         )
 
     async def compute_entries(self) -> AsyncIterator[FuseEntry]:
         async for url in self.fuse.cache.get_cached_visits():
             yield self.create_origin_child(url)
 
     async def lookup(self, name: str) -> Optional[FuseEntry]:
@@ -136,15 +138,15 @@
             return self.create_origin_child(url_encoded)
         except ValueError:
             return None
 
 
 @dataclass
 class CacheDir(FuseDirEntry):
-    """ The cache/ directory is an on-disk representation of locally cached
+    """The cache/ directory is an on-disk representation of locally cached
     objects and metadata. Via this directory you can browse cached data and
     selectively remove them from the cache, freeing disk space. (See `swh fs
     clean` in the {ref}`CLI <swh-fuse-cli>` to completely empty the cache). The
     directory is populated with symlinks to: all artifacts, identified by their
     SWHIDs and sharded by the first two character of their object id, the
     metadata identified by a `SWHID.json` entry, and the `origin/` directory.
     """
@@ -205,15 +207,15 @@
             name=OriginDir.name,
             target=Path(self.get_relative_root_path(), OriginDir.name),
         )
 
 
 @dataclass
 class Readme(FuseFileEntry):
-    """ Top-level README to explain briefly what is SwhFS. """
+    """Top-level README to explain briefly what is SwhFS."""
 
     name: str = field(init=False, default="README")
     mode: int = field(init=False, default=int(EntryMode.RDONLY_FILE))
 
     CONTENT = """Welcome to the Software Heritage Filesystem (SwhFS)!
 
 This is a user-space POSIX filesystem to browse the Software Heritage archive,
```

### Comparing `swh.fuse-1.0.5/swh/fuse/fuse.py` & `swh.fuse-1.0.6/swh/fuse/fuse.py`

 * *Files 12% similar despite different names*

```diff
@@ -22,26 +22,24 @@
 from swh.fuse.fs.entry import FuseDirEntry, FuseEntry, FuseFileEntry, FuseSymlinkEntry
 from swh.fuse.fs.mountpoint import Root
 from swh.model.swhids import CoreSWHID, ObjectType
 from swh.web.client.client import WebAPIClient
 
 
 class Fuse(pyfuse3.Operations):
-    """ Software Heritage Filesystem in Userspace (FUSE). Locally mount parts of
-    the archive and navigate it as a virtual file system. """
+    """Software Heritage Filesystem in Userspace (FUSE). Locally mount parts of
+    the archive and navigate it as a virtual file system."""
 
     def __init__(self, root_path: Path, cache: FuseCache, conf: Dict[str, Any]):
         super(Fuse, self).__init__()
 
         self._next_inode: int = pyfuse3.ROOT_INODE
         self._inode2entry: Dict[int, FuseEntry] = {}
 
-        # The fuse constructor keyword is propagated up to FuseEntry dataclass, but mypy
-        # 0.812 considers it an unexpected kwarg. Skip typing it.
-        self.root = Root(fuse=self)  # type: ignore
+        self.root = Root(fuse=self)
         self.conf = conf
         self.logger = logging.getLogger(LOGGER_NAME)
 
         self.time_ns: int = time.time_ns()  # start time, used as timestamp
         self.gid = os.getgid()
         self.uid = os.getuid()
 
@@ -50,15 +48,15 @@
         )
         self.cache = cache
 
     def shutdown(self) -> None:
         pass
 
     def _alloc_inode(self, entry: FuseEntry) -> int:
-        """ Return a unique inode integer for a given entry """
+        """Return a unique inode integer for a given entry"""
 
         inode = self._next_inode
         self._next_inode += 1
         self._inode2entry[inode] = entry
 
         return inode
 
@@ -70,23 +68,23 @@
 
         try:
             pyfuse3.invalidate_inode(inode)
         except FileNotFoundError:
             pass
 
     def inode2entry(self, inode: int) -> FuseEntry:
-        """ Return the entry matching a given inode """
+        """Return the entry matching a given inode"""
 
         try:
             return self._inode2entry[inode]
         except KeyError:
             raise pyfuse3.FUSEError(errno.ENOENT)
 
     async def get_metadata(self, swhid: CoreSWHID) -> Any:
-        """ Retrieve metadata for a given SWHID using Software Heritage API """
+        """Retrieve metadata for a given SWHID using Software Heritage API"""
 
         cache = await self.cache.metadata.get(swhid)
         if cache:
             return cache
 
         try:
             typify = False  # Get the raw JSON from the API
@@ -97,16 +95,16 @@
             # Retrieve it from cache so it is correctly typed
             return await self.cache.metadata.get(swhid)
         except requests.HTTPError as err:
             self.logger.error("Cannot fetch metadata for object %s: %s", swhid, err)
             raise
 
     async def get_blob(self, swhid: CoreSWHID) -> bytes:
-        """ Retrieve the blob bytes for a given content SWHID using Software
-        Heritage API """
+        """Retrieve the blob bytes for a given content SWHID using Software
+        Heritage API"""
 
         if swhid.object_type != ObjectType.CONTENT:
             raise pyfuse3.FUSEError(errno.EINVAL)
 
         # Make sure the metadata cache is also populated with the given SWHID
         await self.get_metadata(swhid)
 
@@ -123,15 +121,15 @@
             await self.cache.blob.set(swhid, blob)
             return blob
         except requests.HTTPError as err:
             self.logger.error("Cannot fetch blob for object %s: %s", swhid, err)
             raise
 
     async def get_history(self, swhid: CoreSWHID) -> List[CoreSWHID]:
-        """ Retrieve a revision's history using Software Heritage Graph API """
+        """Retrieve a revision's history using Software Heritage Graph API"""
 
         if swhid.object_type != ObjectType.REVISION:
             raise pyfuse3.FUSEError(errno.EINVAL)
 
         cache = await self.cache.history.get(swhid)
         if cache:
             self.logger.debug(
@@ -154,20 +152,22 @@
             # Ignore exception since swh-graph does not necessarily contain the
             # most recent artifacts from the archive. Computing the full history
             # from the Web API is too computationally intensive so simply return
             # an empty list.
             return []
 
     async def get_visits(self, url_encoded: str) -> List[Dict[str, Any]]:
-        """ Retrieve origin visits given an encoded-URL using Software Heritage API """
+        """Retrieve origin visits given an encoded-URL using Software Heritage API"""
 
         cache = await self.cache.metadata.get_visits(url_encoded)
         if cache:
             self.logger.debug(
-                "Found %d visits for origin '%s' in cache", len(cache), url_encoded,
+                "Found %d visits for origin '%s' in cache",
+                len(cache),
+                url_encoded,
             )
             return cache
 
         try:
             self.logger.debug(
                 "Retrieving visits for origin '%s' via web API...", url_encoded
             )
@@ -193,15 +193,15 @@
         except (ValueError, requests.HTTPError) as err:
             self.logger.error(
                 "Cannot fetch visits for origin '%s': %s", url_encoded, err
             )
             raise
 
     async def get_attrs(self, entry: FuseEntry) -> pyfuse3.EntryAttributes:
-        """ Return entry attributes """
+        """Return entry attributes"""
 
         attrs = pyfuse3.EntryAttributes()
         attrs.st_size = 0
         attrs.st_atime_ns = self.time_ns
         attrs.st_ctime_ns = self.time_ns
         attrs.st_mtime_ns = self.time_ns
         attrs.st_gid = self.gid
@@ -210,28 +210,28 @@
         attrs.st_mode = entry.mode
         attrs.st_size = await entry.size()
         return attrs
 
     async def getattr(
         self, inode: int, _ctx: pyfuse3.RequestContext
     ) -> pyfuse3.EntryAttributes:
-        """ Get attributes for a given inode """
+        """Get attributes for a given inode"""
 
         entry = self.inode2entry(inode)
         return await self.get_attrs(entry)
 
     async def opendir(self, inode: int, _ctx: pyfuse3.RequestContext) -> int:
-        """ Open a directory referred by a given inode """
+        """Open a directory referred by a given inode"""
 
         # Re-use inode as directory handle
         self.logger.debug("opendir(inode=%d)", inode)
         return inode
 
     async def readdir(self, fh: int, offset: int, token: pyfuse3.ReaddirToken) -> None:
-        """ Read entries in an open directory """
+        """Read entries in an open directory"""
 
         # opendir() uses inode as directory handle
         inode = fh
         direntry = self.inode2entry(inode)
         self.logger.debug(
             "readdir(dirname=%s, fh=%d, offset=%d)", direntry.name, fh, offset
         )
@@ -250,23 +250,23 @@
         except Exception as err:
             self.logger.exception("Cannot readdir: %s", err)
             raise pyfuse3.FUSEError(errno.ENOENT)
 
     async def open(
         self, inode: int, _flags: int, _ctx: pyfuse3.RequestContext
     ) -> pyfuse3.FileInfo:
-        """ Open an inode and return a unique file handle """
+        """Open an inode and return a unique file handle"""
 
         # Re-use inode as file handle
         self.logger.debug("open(inode=%d)", inode)
         entry = self.inode2entry(inode)
         return pyfuse3.FileInfo(fh=inode, **entry.file_info_attrs)
 
     async def read(self, fh: int, offset: int, length: int) -> bytes:
-        """ Read `length` bytes from file handle `fh` at position `offset` """
+        """Read `length` bytes from file handle `fh` at position `offset`"""
 
         # open() uses inode as file handle
         inode = fh
 
         entry = self.inode2entry(inode)
         self.logger.debug(
             "read(name=%s, fh=%d, offset=%d, length=%d)", entry.name, fh, offset, length
@@ -279,15 +279,15 @@
         except Exception as err:
             self.logger.exception("Cannot read: %s", err)
             raise pyfuse3.FUSEError(errno.ENOENT)
 
     async def lookup(
         self, parent_inode: int, name: str, _ctx: pyfuse3.RequestContext
     ) -> pyfuse3.EntryAttributes:
-        """ Look up a directory entry by name and get its attributes """
+        """Look up a directory entry by name and get its attributes"""
 
         name = os.fsdecode(name)
         parent_entry = self.inode2entry(parent_inode)
         self.logger.debug(
             "lookup(parent_name=%s, parent_inode=%d, name=%s)",
             parent_entry.name,
             parent_inode,
@@ -310,15 +310,15 @@
         self.logger.debug("readlink(name=%s, inode=%d)", entry.name, inode)
         assert isinstance(entry, FuseSymlinkEntry)
         return os.fsencode(entry.get_target())
 
     async def unlink(
         self, parent_inode: int, name: str, _ctx: pyfuse3.RequestContext
     ) -> None:
-        """ Remove a file """
+        """Remove a file"""
 
         name = os.fsdecode(name)
         parent_entry = self.inode2entry(parent_inode)
         self.logger.debug(
             "unlink(parent_name=%s, parent_inode=%d, name=%s)",
             parent_entry.name,
             parent_inode,
@@ -329,15 +329,15 @@
             await parent_entry.unlink(name)
         except Exception as err:
             self.logger.exception("Cannot unlink: %s", err)
             raise pyfuse3.FUSEError(errno.ENOENT)
 
 
 async def main(swhids: List[CoreSWHID], root_path: Path, conf: Dict[str, Any]) -> None:
-    """ swh-fuse CLI entry-point """
+    """swh-fuse CLI entry-point"""
 
     # Use pyfuse3 asyncio layer to match the rest of Software Heritage codebase
     pyfuse3_asyncio.enable()
 
     async with FuseCache(conf["cache"]) as cache:
         fs = Fuse(root_path, cache, conf)
```

### Comparing `swh.fuse-1.0.5/swh/fuse/tests/api_url.py` & `swh.fuse-1.0.6/swh/fuse/tests/api_url.py`

 * *Files identical despite different names*

### Comparing `swh.fuse-1.0.5/swh/fuse/tests/common.py` & `swh.fuse-1.0.6/swh/fuse/tests/common.py`

 * *Files identical despite different names*

### Comparing `swh.fuse-1.0.5/swh/fuse/tests/conftest.py` & `swh.fuse-1.0.6/swh/fuse/tests/conftest.py`

 * *Files 6% similar despite different names*

```diff
@@ -35,15 +35,18 @@
 
 
 @pytest.fixture
 def fuse_mntdir(web_api_mock):
     tmpdir = TemporaryDirectory(suffix=".swh-fuse-test")
 
     config = {
-        "cache": {"metadata": {"in-memory": True}, "blob": {"in-memory": True},},
+        "cache": {
+            "metadata": {"in-memory": True},
+            "blob": {"in-memory": True},
+        },
         "web-api": {"url": API_URL, "auth-token": None},
         "json-indent": None,
     }
 
     # Run FUSE in foreground mode but in a separate process, so it does not
     # block execution and remains easy to kill during teardown
     def fuse_process(mntdir: Path):
```

### Comparing `swh.fuse-1.0.5/swh/fuse/tests/data/api_data.py` & `swh.fuse-1.0.6/swh/fuse/tests/data/api_data.py`

 * *Files identical despite different names*

### Comparing `swh.fuse-1.0.5/swh/fuse/tests/data/config.py` & `swh.fuse-1.0.6/swh/fuse/tests/data/config.py`

 * *Files 4% similar despite different names*

```diff
@@ -42,18 +42,30 @@
 # responsible for merging everything together so the real API will have no
 # problem, only the mock offline one.
 ROOT_SNP = "swh:1:snp:02db117fef22434f1658b833a756775ca6effed0"
 ROOT_SNP_MASTER_BRANCH = "swh:1:rev:430a9fd4c797c50cea26157141b2408073b2ed91"
 FAKE_SNP_SPECIAL_CASES_SWHID = "swh:1:snp:0000000000000000000000000000000000000000"
 FAKE_SNP_SPECIAL_CASES = {
     # All possible target types
-    "mycnt": {"target_type": "content", "target": remove_swhid_prefix(REGULAR_FILE),},
-    "mydir": {"target_type": "directory", "target": remove_swhid_prefix(ROOT_DIR),},
-    "myrev": {"target_type": "revision", "target": remove_swhid_prefix(ROOT_REV),},
-    "myrel": {"target_type": "release", "target": remove_swhid_prefix(ROOT_REL),},
+    "mycnt": {
+        "target_type": "content",
+        "target": remove_swhid_prefix(REGULAR_FILE),
+    },
+    "mydir": {
+        "target_type": "directory",
+        "target": remove_swhid_prefix(ROOT_DIR),
+    },
+    "myrev": {
+        "target_type": "revision",
+        "target": remove_swhid_prefix(ROOT_REV),
+    },
+    "myrel": {
+        "target_type": "release",
+        "target": remove_swhid_prefix(ROOT_REL),
+    },
     "refs/heads/master": {
         "target_type": "revision",
         "target": remove_swhid_prefix(ROOT_SNP_MASTER_BRANCH),
     },
     # Alias with different target paths
     "alias-rootdir": {
         "target_type": "alias",
```

### Comparing `swh.fuse-1.0.5/swh/fuse/tests/data/gen-api-data.py` & `swh.fuse-1.0.6/swh/fuse/tests/data/gen-api-data.py`

 * *Files 1% similar despite different names*

```diff
@@ -120,15 +120,15 @@
 swh:1:rev:4a1f86ccd7e823f63d12208baef79b1e74479203 swh:1:rev:0016473117e4bc3c8959bf2fd49368844847d74c
 swh:1:rev:0016473117e4bc3c8959bf2fd49368844847d74c swh:1:rev:935442babcf4f8ae52c1a13bb9ce07270a302886
 swh:1:rev:935442babcf4f8ae52c1a13bb9ce07270a302886 swh:1:rev:1f3cff91f6762b0f47f41025b5e2c5ac942479ba
 swh:1:rev:1f3cff91f6762b0f47f41025b5e2c5ac942479ba swh:1:rev:bc286c7f2ceb5c3d2e06ec72f78d28842f94ef65
 swh:1:rev:bc286c7f2ceb5c3d2e06ec72f78d28842f94ef65 swh:1:rev:f038f4d533f897a29f9422510d1b3f0caac97388
 swh:1:rev:f038f4d533f897a29f9422510d1b3f0caac97388 swh:1:rev:d6b7c96c3eb29b9244ece0c046d3f372ff432d04
 swh:1:rev:d6b7c96c3eb29b9244ece0c046d3f372ff432d04 swh:1:rev:c01efc669f09508b55eced32d3c88702578a7c3e
-"""  # NoQA: E501
+"""  # NoQA: B950
             MOCK_ARCHIVE[url] = history
 
             hist_nodes = set(
                 map(
                     CoreSWHID.from_string,
                     [edge.split(" ")[1] for edge in history.strip().split("\n")],
                 )
```

### Comparing `swh.fuse-1.0.5/swh/fuse/tests/test_cache.py` & `swh.fuse-1.0.6/swh/fuse/tests/test_cache.py`

 * *Files identical despite different names*

### Comparing `swh.fuse-1.0.5/swh/fuse/tests/test_cli.py` & `swh.fuse-1.0.6/swh/fuse/tests/test_cli.py`

 * *Files 22% similar despite different names*

```diff
@@ -26,12 +26,17 @@
     fake_blob_db.touch()
     config_path.write_text(yaml.dump(config))
 
     assert fake_metadata_db.exists()
     assert fake_blob_db.exists()
 
     CliRunner().invoke(
-        cli.fuse, args=["--config-file", str(config_path), "clean",],
+        cli.fuse,
+        args=[
+            "--config-file",
+            str(config_path),
+            "clean",
+        ],
     )
 
     assert not fake_metadata_db.exists()
     assert not fake_blob_db.exists()
```

### Comparing `swh.fuse-1.0.5/swh/fuse/tests/test_directory.py` & `swh.fuse-1.0.6/swh/fuse/tests/test_directory.py`

 * *Files identical despite different names*

### Comparing `swh.fuse-1.0.5/swh/fuse/tests/test_mountpoint.py` & `swh.fuse-1.0.6/swh/fuse/tests/test_mountpoint.py`

 * *Files identical despite different names*

### Comparing `swh.fuse-1.0.5/swh/fuse/tests/test_origin.py` & `swh.fuse-1.0.6/swh/fuse/tests/test_origin.py`

 * *Files identical despite different names*

### Comparing `swh.fuse-1.0.5/swh/fuse/tests/test_release.py` & `swh.fuse-1.0.6/swh/fuse/tests/test_release.py`

 * *Files identical despite different names*

### Comparing `swh.fuse-1.0.5/swh/fuse/tests/test_revision.py` & `swh.fuse-1.0.6/swh/fuse/tests/test_revision.py`

 * *Files identical despite different names*

### Comparing `swh.fuse-1.0.5/swh/fuse/tests/test_snapshot.py` & `swh.fuse-1.0.6/swh/fuse/tests/test_snapshot.py`

 * *Files identical despite different names*

### Comparing `swh.fuse-1.0.5/swh.fuse.egg-info/PKG-INFO` & `swh.fuse-1.0.6/swh.fuse.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,20 +1,18 @@
 Metadata-Version: 2.1
 Name: swh.fuse
-Version: 1.0.5
+Version: 1.0.6
 Summary: Software Heritage virtual file system
 Home-page: https://forge.softwareheritage.org/source/swh-fuse
 Author: Software Heritage developers
 Author-email: swh-devel@inria.fr
-License: UNKNOWN
 Project-URL: Bug Reports, https://forge.softwareheritage.org/maniphest
 Project-URL: Funding, https://www.softwareheritage.org/donate
 Project-URL: Source, https://forge.softwareheritage.org/source/swh-fuse
 Project-URL: Documentation, https://docs.softwareheritage.org/devel/swh-fuse/
-Platform: UNKNOWN
 Classifier: Programming Language :: Python :: 3
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: GNU General Public License v3 (GPLv3)
 Classifier: Operating System :: OS Independent
 Classifier: Development Status :: 3 - Alpha
 Requires-Python: >=3.7
 Description-Content-Type: text/x-rst
@@ -52,9 +50,7 @@
   Filesystem (SwhFS): Integrating Source Code Archival with Development
   <https://arxiv.org/pdf/2102.06390.pdf>`_. In proceedings of `ICSE 2021
   <https://conf.researchr.org/home/icse-2021>`_: The 43rd International
   Conference on Software Engineering, May 2021, Madrid, Spain. IEEE 2021.
 
   Links: `preprint <https://arxiv.org/pdf/2102.06390.pdf>`_, `bibtex
   <https://upsilon.cc/~zack/research/publications/saner-2020-swh-graph.bib>`_.
-
-
```

### Comparing `swh.fuse-1.0.5/swh.fuse.egg-info/SOURCES.txt` & `swh.fuse-1.0.6/swh.fuse.egg-info/SOURCES.txt`

 * *Files 4% similar despite different names*

```diff
@@ -1,7 +1,8 @@
+.git-blame-ignore-revs
 .gitignore
 .pre-commit-config.yaml
 AUTHORS
 CODE_OF_CONDUCT.md
 CONTRIBUTORS
 LICENSE
 MANIFEST.in
```

### Comparing `swh.fuse-1.0.5/tox.ini` & `swh.fuse-1.0.6/tox.ini`

 * *Files 15% similar despite different names*

```diff
@@ -1,8 +1,10 @@
 [tox]
+requires =
+  tox>4
 envlist=black,flake8,mypy,py3
 
 [testenv]
 extras =
   testing
 deps =
   pytest-cov
@@ -10,63 +12,62 @@
   pytest {envsitepackagesdir}/swh/fuse \
          --cov={envsitepackagesdir}/swh/fuse \
          --cov-branch {posargs}
 
 [testenv:black]
 skip_install = true
 deps =
-  black==19.10b0
+  black==22.10.0
 commands =
   {envpython} -m black --check swh
 
 [testenv:flake8]
 skip_install = true
 deps =
-  flake8
+  flake8==5.0.4
+  flake8-bugbear==22.9.23
+  pycodestyle==2.9.1
 commands =
   {envpython} -m flake8
 
 [testenv:mypy]
 extras =
   testing
 deps =
-  mypy==0.920
+  mypy==1.0.1
 commands =
   mypy swh
 
 # build documentation outside swh-environment using the current
 # git HEAD of swh-docs, is executed on CI for each diff to prevent
 # breaking doc build
 [testenv:sphinx]
-whitelist_externals = make
+allowlist_externals = make
 usedevelop = true
 extras =
   testing
 deps =
   # fetch and install swh-docs in develop mode
-  -e git+https://forge.softwareheritage.org/source/swh-docs#egg=swh.docs
-
+  -e git+https://gitlab.softwareheritage.org/swh/devel/swh-docs.git\#egg=swh.docs
 setenv =
   SWH_PACKAGE_DOC_TOX_BUILD = 1
   # turn warnings into errors
   SPHINXOPTS = -W
 commands =
   make -I ../.tox/sphinx/src/swh-docs/swh/ -C docs
 
-
 # build documentation only inside swh-environment using local state
 # of swh-docs package
 [testenv:sphinx-dev]
-whitelist_externals = make
+allowlist_externals = make
 usedevelop = true
 extras =
   testing
 deps =
   # install swh-docs in develop mode
   -e ../swh-docs
-
 setenv =
   SWH_PACKAGE_DOC_TOX_BUILD = 1
   # turn warnings into errors
   SPHINXOPTS = -W
 commands =
   make -I ../.tox/sphinx-dev/src/swh-docs/swh/ -C docs
```


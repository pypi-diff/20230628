# Comparing `tmp/types-flake8-plugin-utils-1.3.7.3.tar.gz` & `tmp/types-flake8-plugin-utils-1.3.7.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-flake8-plugin-utils-1.3.7.3.tar", last modified: Wed May 10 15:20:05 2023, max compression
+gzip compressed data, was "types-flake8-plugin-utils-1.3.7.4.tar", last modified: Wed Jun 28 09:16:40 2023, max compression
```

## Comparing `types-flake8-plugin-utils-1.3.7.3.tar` & `types-flake8-plugin-utils-1.3.7.4.tar`

### file list

```diff
@@ -1,20 +1,20 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-10 15:20:05.357573 types-flake8-plugin-utils-1.3.7.3/
--rw-r--r--   0 runner    (1001) docker     (123)     1016 2023-05-10 15:20:02.000000 types-flake8-plugin-utils-1.3.7.3/CHANGELOG.md
--rw-r--r--   0 runner    (1001) docker     (123)       21 2023-05-10 15:20:02.000000 types-flake8-plugin-utils-1.3.7.3/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)     1378 2023-05-10 15:20:05.357573 types-flake8-plugin-utils-1.3.7.3/PKG-INFO
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-10 15:20:05.353573 types-flake8-plugin-utils-1.3.7.3/flake8_plugin_utils-stubs/
--rw-r--r--   0 runner    (1001) docker     (123)       82 2023-05-10 15:20:02.000000 types-flake8-plugin-utils-1.3.7.3/flake8_plugin_utils-stubs/METADATA.toml
--rw-r--r--   0 runner    (1001) docker     (123)      300 2023-05-10 15:19:44.000000 types-flake8-plugin-utils-1.3.7.3/flake8_plugin_utils-stubs/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     1489 2023-05-10 15:19:44.000000 types-flake8-plugin-utils-1.3.7.3/flake8_plugin_utils-stubs/plugin.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-10 15:20:05.357573 types-flake8-plugin-utils-1.3.7.3/flake8_plugin_utils-stubs/utils/
--rw-r--r--   0 runner    (1001) docker     (123)      249 2023-05-10 15:19:44.000000 types-flake8-plugin-utils-1.3.7.3/flake8_plugin_utils-stubs/utils/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      365 2023-05-10 15:19:44.000000 types-flake8-plugin-utils-1.3.7.3/flake8_plugin_utils-stubs/utils/assertions.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      133 2023-05-10 15:19:44.000000 types-flake8-plugin-utils-1.3.7.3/flake8_plugin_utils-stubs/utils/constants.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       84 2023-05-10 15:19:44.000000 types-flake8-plugin-utils-1.3.7.3/flake8_plugin_utils-stubs/utils/equiv_nodes.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-05-10 15:20:05.357573 types-flake8-plugin-utils-1.3.7.3/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     1889 2023-05-10 15:20:02.000000 types-flake8-plugin-utils-1.3.7.3/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-10 15:20:05.357573 types-flake8-plugin-utils-1.3.7.3/types_flake8_plugin_utils.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     1378 2023-05-10 15:20:05.000000 types-flake8-plugin-utils-1.3.7.3/types_flake8_plugin_utils.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      531 2023-05-10 15:20:05.000000 types-flake8-plugin-utils-1.3.7.3/types_flake8_plugin_utils.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-05-10 15:20:05.000000 types-flake8-plugin-utils-1.3.7.3/types_flake8_plugin_utils.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       26 2023-05-10 15:20:05.000000 types-flake8-plugin-utils-1.3.7.3/types_flake8_plugin_utils.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:16:40.038333 types-flake8-plugin-utils-1.3.7.4/
+-rw-r--r--   0 runner    (1001) docker     (123)     1255 2023-06-28 09:16:36.000000 types-flake8-plugin-utils-1.3.7.4/CHANGELOG.md
+-rw-r--r--   0 runner    (1001) docker     (123)       21 2023-06-28 09:16:36.000000 types-flake8-plugin-utils-1.3.7.4/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)     1836 2023-06-28 09:16:40.038333 types-flake8-plugin-utils-1.3.7.4/PKG-INFO
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:16:40.038333 types-flake8-plugin-utils-1.3.7.4/flake8_plugin_utils-stubs/
+-rw-r--r--   0 runner    (1001) docker     (123)      132 2023-06-28 09:16:36.000000 types-flake8-plugin-utils-1.3.7.4/flake8_plugin_utils-stubs/METADATA.toml
+-rw-r--r--   0 runner    (1001) docker     (123)      300 2023-06-28 09:16:15.000000 types-flake8-plugin-utils-1.3.7.4/flake8_plugin_utils-stubs/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     1489 2023-06-28 09:16:15.000000 types-flake8-plugin-utils-1.3.7.4/flake8_plugin_utils-stubs/plugin.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:16:40.038333 types-flake8-plugin-utils-1.3.7.4/flake8_plugin_utils-stubs/utils/
+-rw-r--r--   0 runner    (1001) docker     (123)      249 2023-06-28 09:16:15.000000 types-flake8-plugin-utils-1.3.7.4/flake8_plugin_utils-stubs/utils/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      365 2023-06-28 09:16:15.000000 types-flake8-plugin-utils-1.3.7.4/flake8_plugin_utils-stubs/utils/assertions.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      133 2023-06-28 09:16:15.000000 types-flake8-plugin-utils-1.3.7.4/flake8_plugin_utils-stubs/utils/constants.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       84 2023-06-28 09:16:15.000000 types-flake8-plugin-utils-1.3.7.4/flake8_plugin_utils-stubs/utils/equiv_nodes.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 09:16:40.042333 types-flake8-plugin-utils-1.3.7.4/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2359 2023-06-28 09:16:36.000000 types-flake8-plugin-utils-1.3.7.4/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:16:40.038333 types-flake8-plugin-utils-1.3.7.4/types_flake8_plugin_utils.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     1836 2023-06-28 09:16:39.000000 types-flake8-plugin-utils-1.3.7.4/types_flake8_plugin_utils.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      531 2023-06-28 09:16:39.000000 types-flake8-plugin-utils-1.3.7.4/types_flake8_plugin_utils.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 09:16:39.000000 types-flake8-plugin-utils-1.3.7.4/types_flake8_plugin_utils.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       26 2023-06-28 09:16:39.000000 types-flake8-plugin-utils-1.3.7.4/types_flake8_plugin_utils.egg-info/top_level.txt
```

### Comparing `types-flake8-plugin-utils-1.3.7.3/CHANGELOG.md` & `types-flake8-plugin-utils-1.3.7.4/CHANGELOG.md`

 * *Files 24% similar despite different names*

```diff
@@ -1,7 +1,16 @@
+## 1.3.7.4 (2023-06-28)
+
+[stubsabot] Mark flake8-plugin-utils as obsolete since 1.3.3 (#10373)
+
+Release: https://pypi.org/pypi/flake8-plugin-utils/1.3.3
+Homepage: https://pypi.org/project/flake8-plugin-utils
+
+Co-authored-by: stubsabot <>
+
 ## 1.3.7.3 (2023-05-10)
 
 Add `partial_stub` metadata field (#10157)
 
 ## 1.3.7.2 (2023-03-27)
 
 Add defaults for third-party stubs E-H (#9954)
```

### Comparing `types-flake8-plugin-utils-1.3.7.3/PKG-INFO` & `types-flake8-plugin-utils-1.3.7.4/PKG-INFO`

 * *Files 15% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: types-flake8-plugin-utils
-Version: 1.3.7.3
+Version: 1.3.7.4
 Summary: Typing stubs for flake8-plugin-utils
 Home-page: https://github.com/python/typeshed
 License: Apache-2.0 license
 Project-URL: GitHub, https://github.com/python/typeshed
 Project-URL: Changes, https://github.com/typeshed-internal/stub_uploader/blob/main/data/changelogs/flake8-plugin-utils.md
 Project-URL: Issue tracker, https://github.com/python/typeshed/issues
 Project-URL: Chat, https://gitter.im/python/typing
@@ -21,9 +21,20 @@
 [pyright](https://github.com/microsoft/pyright),
 [pytype](https://github.com/google/pytype/),
 PyCharm, etc. to check code that uses
 `flake8-plugin-utils`. The source for this package can be found at
 https://github.com/python/typeshed/tree/main/stubs/flake8-plugin-utils. All fixes for
 types and metadata should be contributed there.
 
+*Note:* The `flake8-plugin-utils` package includes type annotations or type stubs
+since version 1.3.3. Please uninstall the `types-flake8-plugin-utils`
+package if you use this or a newer version.
+
+
+This stub package is marked as [partial](https://peps.python.org/pep-0561/#partial-stub-packages).
+If you find that annotations are missing, feel free to contribute and help complete them.
+
+
 See https://github.com/python/typeshed/blob/main/README.md for more details.
-This package was generated from typeshed commit `d1bfd08b4bc843227d097decfd99d70272a1f804`.
+This package was generated from typeshed commit `d5f0d155d1d847d2aab3566ba196ff031d94a1bf` and was tested
+with mypy 1.4.1, pyright 1.1.315, and
+pytype 2023.6.2.
```

### Comparing `types-flake8-plugin-utils-1.3.7.3/flake8_plugin_utils-stubs/plugin.pyi` & `types-flake8-plugin-utils-1.3.7.4/flake8_plugin_utils-stubs/plugin.pyi`

 * *Files identical despite different names*

### Comparing `types-flake8-plugin-utils-1.3.7.3/setup.py` & `types-flake8-plugin-utils-1.3.7.4/setup.py`

 * *Files 9% similar despite different names*

```diff
@@ -11,33 +11,44 @@
 [pyright](https://github.com/microsoft/pyright),
 [pytype](https://github.com/google/pytype/),
 PyCharm, etc. to check code that uses
 `flake8-plugin-utils`. The source for this package can be found at
 https://github.com/python/typeshed/tree/main/stubs/flake8-plugin-utils. All fixes for
 types and metadata should be contributed there.
 
+*Note:* The `flake8-plugin-utils` package includes type annotations or type stubs
+since version 1.3.3. Please uninstall the `types-flake8-plugin-utils`
+package if you use this or a newer version.
+
+
+This stub package is marked as [partial](https://peps.python.org/pep-0561/#partial-stub-packages).
+If you find that annotations are missing, feel free to contribute and help complete them.
+
+
 See https://github.com/python/typeshed/blob/main/README.md for more details.
-This package was generated from typeshed commit `d1bfd08b4bc843227d097decfd99d70272a1f804`.
+This package was generated from typeshed commit `d5f0d155d1d847d2aab3566ba196ff031d94a1bf` and was tested
+with mypy 1.4.1, pyright 1.1.315, and
+pytype 2023.6.2.
 '''.lstrip()
 
 setup(name=name,
-      version="1.3.7.3",
+      version="1.3.7.4",
       description=description,
       long_description=long_description,
       long_description_content_type="text/markdown",
       url="https://github.com/python/typeshed",
       project_urls={
           "GitHub": "https://github.com/python/typeshed",
           "Changes": "https://github.com/typeshed-internal/stub_uploader/blob/main/data/changelogs/flake8-plugin-utils.md",
           "Issue tracker": "https://github.com/python/typeshed/issues",
           "Chat": "https://gitter.im/python/typing",
       },
       install_requires=[],
       packages=['flake8_plugin_utils-stubs'],
-      package_data={'flake8_plugin_utils-stubs': ['__init__.pyi', 'plugin.pyi', 'utils/__init__.pyi', 'utils/assertions.pyi', 'utils/constants.pyi', 'utils/equiv_nodes.pyi', 'METADATA.toml']},
+      package_data={'flake8_plugin_utils-stubs': ['__init__.pyi', 'plugin.pyi', 'utils/__init__.pyi', 'utils/assertions.pyi', 'utils/constants.pyi', 'utils/equiv_nodes.pyi', 'METADATA.toml', 'py.typed']},
       license="Apache-2.0 license",
       classifiers=[
           "License :: OSI Approved :: Apache Software License",
           "Programming Language :: Python :: 3",
           "Typing :: Stubs Only",
       ]
 )
```

### Comparing `types-flake8-plugin-utils-1.3.7.3/types_flake8_plugin_utils.egg-info/PKG-INFO` & `types-flake8-plugin-utils-1.3.7.4/types_flake8_plugin_utils.egg-info/PKG-INFO`

 * *Files 15% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: types-flake8-plugin-utils
-Version: 1.3.7.3
+Version: 1.3.7.4
 Summary: Typing stubs for flake8-plugin-utils
 Home-page: https://github.com/python/typeshed
 License: Apache-2.0 license
 Project-URL: GitHub, https://github.com/python/typeshed
 Project-URL: Changes, https://github.com/typeshed-internal/stub_uploader/blob/main/data/changelogs/flake8-plugin-utils.md
 Project-URL: Issue tracker, https://github.com/python/typeshed/issues
 Project-URL: Chat, https://gitter.im/python/typing
@@ -21,9 +21,20 @@
 [pyright](https://github.com/microsoft/pyright),
 [pytype](https://github.com/google/pytype/),
 PyCharm, etc. to check code that uses
 `flake8-plugin-utils`. The source for this package can be found at
 https://github.com/python/typeshed/tree/main/stubs/flake8-plugin-utils. All fixes for
 types and metadata should be contributed there.
 
+*Note:* The `flake8-plugin-utils` package includes type annotations or type stubs
+since version 1.3.3. Please uninstall the `types-flake8-plugin-utils`
+package if you use this or a newer version.
+
+
+This stub package is marked as [partial](https://peps.python.org/pep-0561/#partial-stub-packages).
+If you find that annotations are missing, feel free to contribute and help complete them.
+
+
 See https://github.com/python/typeshed/blob/main/README.md for more details.
-This package was generated from typeshed commit `d1bfd08b4bc843227d097decfd99d70272a1f804`.
+This package was generated from typeshed commit `d5f0d155d1d847d2aab3566ba196ff031d94a1bf` and was tested
+with mypy 1.4.1, pyright 1.1.315, and
+pytype 2023.6.2.
```

### Comparing `types-flake8-plugin-utils-1.3.7.3/types_flake8_plugin_utils.egg-info/SOURCES.txt` & `types-flake8-plugin-utils-1.3.7.4/types_flake8_plugin_utils.egg-info/SOURCES.txt`

 * *Files identical despite different names*


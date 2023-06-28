# Comparing `tmp/oceanumlab-0.4.1.tar.gz` & `tmp/oceanumlab-0.4.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "oceanumlab-0.4.1.tar", last modified: Wed Jun 14 02:06:28 2023, max compression
+gzip compressed data, last modified: Sun Feb  2 00:00:00 2020, max compression
```

## Comparing `oceanumlab-0.4.1.tar` & `oceanumlab-0.4.2.tar`

### file list

```diff
@@ -1,71 +1,103 @@
-drwxrwxr-x   0 dave      (1000) dave      (1000)        0 2023-06-14 02:06:28.176727 oceanumlab-0.4.1/
--rw-rw-r--   0 dave      (1000) dave      (1000)       86 2022-06-20 01:46:54.000000 oceanumlab-0.4.1/CHANGELOG.md
--rw-rw-r--   0 dave      (1000) dave      (1000)     1515 2022-06-20 01:46:54.000000 oceanumlab-0.4.1/LICENSE
--rw-rw-r--   0 dave      (1000) dave      (1000)      512 2022-06-20 01:46:54.000000 oceanumlab-0.4.1/MANIFEST.in
--rw-rw-r--   0 dave      (1000) dave      (1000)     4980 2023-06-14 02:06:28.176727 oceanumlab-0.4.1/PKG-INFO
--rw-rw-r--   0 dave      (1000) dave      (1000)     3912 2022-06-27 22:21:02.000000 oceanumlab-0.4.1/README.md
--rw-rw-r--   0 dave      (1000) dave      (1000)     1892 2022-06-20 01:46:54.000000 oceanumlab-0.4.1/RELEASE.md
--rw-rw-r--   0 dave      (1000) dave      (1000)       68 2022-06-20 01:46:54.000000 oceanumlab-0.4.1/babel.config.js
--rw-rw-r--   0 dave      (1000) dave      (1000)      197 2022-06-20 01:46:54.000000 oceanumlab-0.4.1/conftest.py
--rw-rw-r--   0 dave      (1000) dave      (1000)      181 2022-06-20 01:46:54.000000 oceanumlab-0.4.1/install.json
--rw-rw-r--   0 dave      (1000) dave      (1000)      864 2023-03-01 01:19:27.000000 oceanumlab-0.4.1/jest.config.js
-drwxrwxr-x   0 dave      (1000) dave      (1000)        0 2023-06-14 02:06:28.156727 oceanumlab-0.4.1/jupyter-config/
-drwxrwxr-x   0 dave      (1000) dave      (1000)        0 2023-06-14 02:06:28.160727 oceanumlab-0.4.1/jupyter-config/nb-config/
--rw-rw-r--   0 dave      (1000) dave      (1000)       87 2022-06-20 01:46:54.000000 oceanumlab-0.4.1/jupyter-config/nb-config/oceanumlab.json
-drwxrwxr-x   0 dave      (1000) dave      (1000)        0 2023-06-14 02:06:28.160727 oceanumlab-0.4.1/jupyter-config/server-config/
--rw-rw-r--   0 dave      (1000) dave      (1000)       85 2022-06-20 01:46:54.000000 oceanumlab-0.4.1/jupyter-config/server-config/oceanumlab.json
-drwxrwxr-x   0 dave      (1000) dave      (1000)        0 2023-06-14 02:06:28.160727 oceanumlab-0.4.1/oceanumlab/
--rw-rw-r--   0 dave      (1000) dave      (1000)      926 2022-10-19 02:54:28.000000 oceanumlab-0.4.1/oceanumlab/__init__.py
--rw-rw-r--   0 dave      (1000) dave      (1000)     1044 2023-02-27 02:23:39.000000 oceanumlab-0.4.1/oceanumlab/handlers.py
-drwxrwxr-x   0 dave      (1000) dave      (1000)        0 2023-06-14 02:06:28.164727 oceanumlab-0.4.1/oceanumlab/labextension/
--rw-rw-r--   0 dave      (1000) dave      (1000)      181 2023-06-14 02:06:14.000000 oceanumlab-0.4.1/oceanumlab/labextension/install.json
--rw-rw-r--   0 dave      (1000) dave      (1000)     4024 2023-06-14 02:06:14.000000 oceanumlab-0.4.1/oceanumlab/labextension/package.json
-drwxrwxr-x   0 dave      (1000) dave      (1000)        0 2023-06-14 02:06:28.156727 oceanumlab-0.4.1/oceanumlab/labextension/schemas/
-drwxrwxr-x   0 dave      (1000) dave      (1000)        0 2023-06-14 02:06:28.156727 oceanumlab-0.4.1/oceanumlab/labextension/schemas/@oceanum/
-drwxrwxr-x   0 dave      (1000) dave      (1000)        0 2023-06-14 02:06:28.164727 oceanumlab-0.4.1/oceanumlab/labextension/schemas/@oceanum/oceanumlab/
--rw-rw-r--   0 dave      (1000) dave      (1000)     3882 2023-06-14 02:06:14.000000 oceanumlab-0.4.1/oceanumlab/labextension/schemas/@oceanum/oceanumlab/package.json.orig
--rw-rw-r--   0 dave      (1000) dave      (1000)      736 2023-06-14 02:06:14.000000 oceanumlab-0.4.1/oceanumlab/labextension/schemas/@oceanum/oceanumlab/plugin.json
-drwxrwxr-x   0 dave      (1000) dave      (1000)        0 2023-06-14 02:06:28.172727 oceanumlab-0.4.1/oceanumlab/labextension/static/
--rw-rw-r--   0 dave      (1000) dave      (1000)  4131662 2023-06-14 02:06:14.000000 oceanumlab-0.4.1/oceanumlab/labextension/static/490.7bd4977c6b29fa73fa5d.js
--rw-rw-r--   0 dave      (1000) dave      (1000)     6199 2023-06-14 02:06:14.000000 oceanumlab-0.4.1/oceanumlab/labextension/static/549.98d9219eb389c3f2404c.js
--rw-rw-r--   0 dave      (1000) dave      (1000)    21379 2023-06-14 02:06:14.000000 oceanumlab-0.4.1/oceanumlab/labextension/static/746.d3b024e6eae9ee883ccc.js
--rw-rw-r--   0 dave      (1000) dave      (1000)     8116 2023-06-14 02:06:14.000000 oceanumlab-0.4.1/oceanumlab/labextension/static/remoteEntry.8438a14f26699b797d74.js
--rw-rw-r--   0 dave      (1000) dave      (1000)      163 2023-06-14 02:06:14.000000 oceanumlab-0.4.1/oceanumlab/labextension/static/style.js
--rw-rw-r--   0 dave      (1000) dave      (1000)     3675 2023-06-14 02:06:14.000000 oceanumlab-0.4.1/oceanumlab/labextension/static/third-party-licenses.json
-drwxrwxr-x   0 dave      (1000) dave      (1000)        0 2023-06-14 02:06:28.172727 oceanumlab-0.4.1/oceanumlab/tests/
--rw-rw-r--   0 dave      (1000) dave      (1000)       40 2022-06-20 01:46:54.000000 oceanumlab-0.4.1/oceanumlab/tests/__init__.py
--rw-rw-r--   0 dave      (1000) dave      (1000)      284 2023-03-01 04:13:25.000000 oceanumlab-0.4.1/oceanumlab/tests/test_handlers.py
-drwxrwxr-x   0 dave      (1000) dave      (1000)        0 2023-06-14 02:06:28.164727 oceanumlab-0.4.1/oceanumlab.egg-info/
--rw-rw-r--   0 dave      (1000) dave      (1000)     4980 2023-06-14 02:06:28.000000 oceanumlab-0.4.1/oceanumlab.egg-info/PKG-INFO
--rw-rw-r--   0 dave      (1000) dave      (1000)     1457 2023-06-14 02:06:28.000000 oceanumlab-0.4.1/oceanumlab.egg-info/SOURCES.txt
--rw-rw-r--   0 dave      (1000) dave      (1000)        1 2023-06-14 02:06:28.000000 oceanumlab-0.4.1/oceanumlab.egg-info/dependency_links.txt
--rw-rw-r--   0 dave      (1000) dave      (1000)        1 2023-06-14 02:06:08.000000 oceanumlab-0.4.1/oceanumlab.egg-info/not-zip-safe
--rw-rw-r--   0 dave      (1000) dave      (1000)       98 2023-06-14 02:06:28.000000 oceanumlab-0.4.1/oceanumlab.egg-info/requires.txt
--rw-rw-r--   0 dave      (1000) dave      (1000)       11 2023-06-14 02:06:28.000000 oceanumlab-0.4.1/oceanumlab.egg-info/top_level.txt
--rw-rw-r--   0 dave      (1000) dave      (1000)     3882 2023-06-14 02:05:23.000000 oceanumlab-0.4.1/package.json
--rw-rw-r--   0 dave      (1000) dave      (1000)      575 2023-03-01 04:06:02.000000 oceanumlab-0.4.1/pyproject.toml
-drwxrwxr-x   0 dave      (1000) dave      (1000)        0 2023-06-14 02:06:28.172727 oceanumlab-0.4.1/schema/
--rw-rw-r--   0 dave      (1000) dave      (1000)      736 2023-02-27 02:48:20.000000 oceanumlab-0.4.1/schema/plugin.json
--rw-rw-r--   0 dave      (1000) dave      (1000)       38 2023-06-14 02:06:28.176727 oceanumlab-0.4.1/setup.cfg
--rw-rw-r--   0 dave      (1000) dave      (1000)     3424 2022-06-20 05:36:28.000000 oceanumlab-0.4.1/setup.py
-drwxrwxr-x   0 dave      (1000) dave      (1000)        0 2023-06-14 02:06:28.172727 oceanumlab-0.4.1/src/
--rw-rw-r--   0 dave      (1000) dave      (1000)      335 2022-06-20 20:32:03.000000 oceanumlab-0.4.1/src/DatameshUI.tsx
--rw-rw-r--   0 dave      (1000) dave      (1000)    14244 2023-02-27 05:27:57.000000 oceanumlab-0.4.1/src/DatameshWidget.tsx
--rw-rw-r--   0 dave      (1000) dave      (1000)     3434 2022-06-20 22:56:03.000000 oceanumlab-0.4.1/src/DatasourceItem.tsx
--rw-rw-r--   0 dave      (1000) dave      (1000)     1110 2022-06-20 04:51:20.000000 oceanumlab-0.4.1/src/handler.ts
--rw-rw-r--   0 dave      (1000) dave      (1000)     3990 2023-03-01 00:04:26.000000 oceanumlab-0.4.1/src/index.ts
--rw-rw-r--   0 dave      (1000) dave      (1000)       74 2022-06-20 01:53:54.000000 oceanumlab-0.4.1/src/svg.d.ts
-drwxrwxr-x   0 dave      (1000) dave      (1000)        0 2023-06-14 02:06:28.172727 oceanumlab-0.4.1/style/
-drwxrwxr-x   0 dave      (1000) dave      (1000)        0 2023-06-14 02:06:28.176727 oceanumlab-0.4.1/style/icons/
--rw-rw-r--   0 dave      (1000) dave      (1000)     6719 2022-06-20 01:57:06.000000 oceanumlab-0.4.1/style/icons/oceanum.png
--rw-rw-r--   0 dave      (1000) dave      (1000)     5926 2022-06-20 01:57:06.000000 oceanumlab-0.4.1/style/icons/oceanum.svg
--rw-rw-r--   0 dave      (1000) dave      (1000)     2651 2023-02-28 23:48:07.000000 oceanumlab-0.4.1/style/index.css
--rw-rw-r--   0 dave      (1000) dave      (1000)      874 2023-03-01 00:23:30.000000 oceanumlab-0.4.1/tsconfig.json
-drwxrwxr-x   0 dave      (1000) dave      (1000)        0 2023-06-14 02:06:28.176727 oceanumlab-0.4.1/ui-tests/
--rw-rw-r--   0 dave      (1000) dave      (1000)     3390 2022-06-20 01:46:54.000000 oceanumlab-0.4.1/ui-tests/README.md
--rw-rw-r--   0 dave      (1000) dave      (1000)      609 2022-06-20 01:46:54.000000 oceanumlab-0.4.1/ui-tests/jupyter_server_test_config.py
--rw-rw-r--   0 dave      (1000) dave      (1000)      322 2022-06-20 01:46:54.000000 oceanumlab-0.4.1/ui-tests/package.json
--rw-rw-r--   0 dave      (1000) dave      (1000)      340 2022-06-20 01:46:54.000000 oceanumlab-0.4.1/ui-tests/playwright.config.js
-drwxrwxr-x   0 dave      (1000) dave      (1000)        0 2023-06-14 02:06:28.176727 oceanumlab-0.4.1/ui-tests/tests/
--rw-rw-r--   0 dave      (1000) dave      (1000)      516 2022-06-21 01:27:55.000000 oceanumlab-0.4.1/ui-tests/tests/oceanumlab.spec.ts
--rw-rw-r--   0 dave      (1000) dave      (1000)      190 2023-02-28 22:52:39.000000 oceanumlab-0.4.1/webpack.config.js
+-rw-r--r--   0        0        0      483 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/.copier-answers.yml
+-rw-r--r--   0        0        0       66 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/.eslintignore
+-rw-r--r--   0        0        0     1025 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/.eslintrc.js
+-rw-r--r--   0        0        0       78 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/.prettierignore
+-rw-r--r--   0        0        0      102 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/.prettierrc
+-rw-r--r--   0        0        0      297 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/.stylelintrc
+-rw-r--r--   0        0        0       57 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/.yarnrc.yml
+-rw-r--r--   0        0        0       86 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/CHANGELOG.md
+-rw-r--r--   0        0        0     2210 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/Makefile
+-rw-r--r--   0        0        0     3919 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/RELEASE.md
+-rw-r--r--   0        0        0       68 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/babel.config.js
+-rw-r--r--   0        0        0      198 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/conftest.py
+-rw-r--r--   0        0        0      181 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/install.json
+-rw-r--r--   0        0        0      608 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/jest.config.js
+-rw-r--r--   0        0        0     3932 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/package.json
+-rw-r--r--   0        0        0     3424 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/setup.py
+-rw-r--r--   0        0        0      581 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/tsconfig.json
+-rw-r--r--   0        0        0       30 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/tsconfig.test.json
+-rw-r--r--   0        0        0      190 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/webpack.config.js
+-rw-r--r--   0        0        0   384785 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/yarn.lock
+-rw-r--r--   0        0        0     2267 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/.vscode/launch.json
+-rw-r--r--   0        0        0      483 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/.copier-answers.yml
+-rw-r--r--   0        0        0     1637 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/.gitignore
+-rw-r--r--   0        0        0       78 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/.prettierignore
+-rw-r--r--   0        0        0       57 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/.yarnrc.yml
+-rw-r--r--   0        0        0       86 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/CHANGELOG.md
+-rw-r--r--   0        0        0     1515 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/LICENSE
+-rw-r--r--   0        0        0     4084 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/README.md
+-rw-r--r--   0        0        0     3919 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/RELEASE.md
+-rw-r--r--   0        0        0       68 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/babel.config.js
+-rw-r--r--   0        0        0      198 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/conftest.py
+-rw-r--r--   0        0        0      181 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/install.json
+-rw-r--r--   0        0        0      608 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/jest.config.js
+-rw-r--r--   0        0        0     6696 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/package.json
+-rw-r--r--   0        0        0     2579 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/pyproject.toml
+-rw-r--r--   0        0        0       33 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/setup.py
+-rw-r--r--   0        0        0      560 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/tsconfig.json
+-rw-r--r--   0        0        0       30 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/tsconfig.test.json
+-rw-r--r--   0        0        0       87 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/jupyter-config/nb-config/oceanumlab.json
+-rw-r--r--   0        0        0       85 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/jupyter-config/server-config/oceanumlab.json
+-rw-r--r--   0        0        0     1247 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/oceanumlab/__init__.py
+-rw-r--r--   0        0        0      778 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/oceanumlab/handlers.py
+-rw-r--r--   0        0        0       40 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/oceanumlab/tests/__init__.py
+-rw-r--r--   0        0        0      295 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/oceanumlab/tests/test_handlers.py
+-rw-r--r--   0        0        0      191 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/schema/plugin.json
+-rw-r--r--   0        0        0     1104 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/src/handler.ts
+-rw-r--r--   0        0        0     1234 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/src/index.ts
+-rw-r--r--   0        0        0      194 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/src/__tests__/oceanumlab.spec.ts
+-rw-r--r--   0        0        0      138 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/style/base.css
+-rw-r--r--   0        0        0       20 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/style/index.css
+-rw-r--r--   0        0        0       21 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/style/index.js
+-rw-r--r--   0        0        0     3758 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/ui-tests/README.md
+-rw-r--r--   0        0        0      397 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/ui-tests/jupyter_server_test_config.py
+-rw-r--r--   0        0        0      437 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/ui-tests/package.json
+-rw-r--r--   0        0        0      340 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/ui-tests/playwright.config.js
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/ui-tests/yarn.lock
+-rw-r--r--   0        0        0      526 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/_temp_extension/ui-tests/tests/oceanumlab.spec.ts
+-rw-r--r--   0        0        0       87 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/jupyter-config/nb-config/oceanumlab.json
+-rw-r--r--   0        0        0       85 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/jupyter-config/server-config/oceanumlab.json
+-rw-r--r--   0        0        0      926 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/oceanumlab/__init__.py
+-rw-r--r--   0        0        0      171 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/oceanumlab/_version.py
+-rw-r--r--   0        0        0     1044 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/oceanumlab/handlers.py
+-rw-r--r--   0        0        0    21384 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/oceanumlab/labextension/build_log.json
+-rw-r--r--   0        0        0     4074 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/oceanumlab/labextension/package.json
+-rw-r--r--   0        0        0     3932 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/oceanumlab/labextension/schemas/@oceanum/oceanumlab/package.json.orig
+-rw-r--r--   0        0        0      736 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/oceanumlab/labextension/schemas/@oceanum/oceanumlab/plugin.json
+-rw-r--r--   0        0        0    49512 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/oceanumlab/labextension/static/lib_index_js.fe271c5a1524b3150109.js
+-rw-r--r--   0        0        0    42504 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/oceanumlab/labextension/static/lib_index_js.fe271c5a1524b3150109.js.map
+-rw-r--r--   0        0        0    32179 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/oceanumlab/labextension/static/remoteEntry.d6c53f9a8466e60ef1b1.js
+-rw-r--r--   0        0        0    31008 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/oceanumlab/labextension/static/remoteEntry.d6c53f9a8466e60ef1b1.js.map
+-rw-r--r--   0        0        0      163 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/oceanumlab/labextension/static/style.js
+-rw-r--r--   0        0        0    10662 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/oceanumlab/labextension/static/style_index_css.35da1c86a5689163d63d.js
+-rw-r--r--   0        0        0    10523 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/oceanumlab/labextension/static/style_index_css.35da1c86a5689163d63d.js.map
+-rw-r--r--   0        0        0    12068 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/oceanumlab/labextension/static/vendors-node_modules_css-loader_dist_runtime_api_js-node_modules_css-loader_dist_runtime_cssW-72eba1.cdb07a33d62465011526.js
+-rw-r--r--   0        0        0    13805 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/oceanumlab/labextension/static/vendors-node_modules_css-loader_dist_runtime_api_js-node_modules_css-loader_dist_runtime_cssW-72eba1.cdb07a33d62465011526.js.map
+-rw-r--r--   0        0        0  8818198 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/oceanumlab/labextension/static/vendors-node_modules_phosphor-react_dist_index_esm_js.a2d73cddf27390da0fec.js
+-rw-r--r--   0        0        0 10430236 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/oceanumlab/labextension/static/vendors-node_modules_phosphor-react_dist_index_esm_js.a2d73cddf27390da0fec.js.map
+-rw-r--r--   0        0        0       40 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/oceanumlab/tests/__init__.py
+-rw-r--r--   0        0        0      284 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/oceanumlab/tests/test_handlers.py
+-rw-r--r--   0        0        0      736 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/schema/plugin.json
+-rw-r--r--   0        0        0      335 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/src/DatameshUI.tsx
+-rw-r--r--   0        0        0    14368 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/src/DatameshWidget.tsx
+-rw-r--r--   0        0        0     3434 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/src/DatasourceItem.tsx
+-rw-r--r--   0        0        0     1110 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/src/handler.ts
+-rw-r--r--   0        0        0     3990 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/src/index.ts
+-rw-r--r--   0        0        0       74 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/src/svg.d.ts
+-rw-r--r--   0        0        0      194 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/src/__tests__/oceanumlab.spec.ts
+-rw-r--r--   0        0        0      138 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/style/base.css
+-rw-r--r--   0        0        0     2651 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/style/index.css
+-rw-r--r--   0        0        0       21 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/style/index.js
+-rw-r--r--   0        0        0     6719 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/style/icons/oceanum.png
+-rw-r--r--   0        0        0     5926 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/style/icons/oceanum.svg
+-rw-r--r--   0        0        0     3758 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/ui-tests/README.md
+-rw-r--r--   0        0        0      397 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/ui-tests/jupyter_server_test_config.py
+-rw-r--r--   0        0        0      322 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/ui-tests/package.json
+-rw-r--r--   0        0        0      340 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/ui-tests/playwright.config.js
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/ui-tests/yarn.lock
+-rw-r--r--   0        0        0      516 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/ui-tests/tests/oceanumlab.spec.ts
+-rw-r--r--   0        0        0     1637 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/.gitignore
+-rw-r--r--   0        0        0     1515 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/LICENSE
+-rw-r--r--   0        0        0     3912 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/README.md
+-rw-r--r--   0        0        0     2578 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/pyproject.toml
+-rw-r--r--   0        0        0     7035 2020-02-02 00:00:00.000000 oceanumlab-0.4.2/PKG-INFO
```

### Comparing `oceanumlab-0.4.1/LICENSE` & `oceanumlab-0.4.2/LICENSE`

 * *Files identical despite different names*

### Comparing `oceanumlab-0.4.1/PKG-INFO` & `oceanumlab-0.4.2/README.md`

 * *Files 20% similar despite different names*

```diff
@@ -1,36 +1,7 @@
-Metadata-Version: 2.1
-Name: oceanumlab
-Version: 0.4.1
-Summary: A Jupyterlab extension to interact with the Oceanum.io platform
-Home-page: https://github.com/oceanum-io/oceanumlab
-Author: Oceanum
-Author-email: developers@oceanum.science
-License: BSD-3-Clause
-Keywords: Jupyter,JupyterLab,JupyterLab3
-Platform: Linux
-Platform: Mac OS X
-Platform: Windows
-Classifier: License :: OSI Approved :: BSD License
-Classifier: Programming Language :: Python
-Classifier: Programming Language :: Python :: 3
-Classifier: Programming Language :: Python :: 3.7
-Classifier: Programming Language :: Python :: 3.8
-Classifier: Programming Language :: Python :: 3.9
-Classifier: Programming Language :: Python :: 3.10
-Classifier: Framework :: Jupyter
-Classifier: Framework :: Jupyter :: JupyterLab
-Classifier: Framework :: Jupyter :: JupyterLab :: 3
-Classifier: Framework :: Jupyter :: JupyterLab :: Extensions
-Classifier: Framework :: Jupyter :: JupyterLab :: Extensions :: Prebuilt
-Requires-Python: >=3.7
-Description-Content-Type: text/markdown
-Provides-Extra: test
-License-File: LICENSE
-
 # oceanumlab
 
 [![Github Actions Status](https://github.com/oceanum-io/oceanumlab/workflows/Build/badge.svg)](https://github.com/oceanum-io/oceanumlab/actions/workflows/build.yml)
 A Jupyterlab extension to interact with the Oceanum.io platform
 
 This extension is composed of a Python package named `oceanumlab`
 for the server extension and a NPM package named `oceanumlab`
```

### Comparing `oceanumlab-0.4.1/README.md` & `oceanumlab-0.4.2/_temp_extension/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -1,19 +1,19 @@
 # oceanumlab
 
-[![Github Actions Status](https://github.com/oceanum-io/oceanumlab/workflows/Build/badge.svg)](https://github.com/oceanum-io/oceanumlab/actions/workflows/build.yml)
+[![Github Actions Status](https://github.com/oceanum-io/oceanumlab.git/workflows/Build/badge.svg)](https://github.com/oceanum-io/oceanumlab.git/actions/workflows/build.yml)
 A Jupyterlab extension to interact with the Oceanum.io platform
 
 This extension is composed of a Python package named `oceanumlab`
-for the server extension and a NPM package named `oceanumlab`
+for the server extension and a NPM package named `@oceanum/oceanumlab`
 for the frontend extension.
 
 ## Requirements
 
-- JupyterLab >= 3.0
+- JupyterLab >= 4.0.0
 
 ## Install
 
 To install the extension, execute:
 
 ```bash
 pip install oceanumlab
@@ -53,15 +53,15 @@
 [yarn](https://yarnpkg.com/) that is installed with JupyterLab. You may use
 `yarn` or `npm` in lieu of `jlpm` below.
 
 ```bash
 # Clone the repo to your local environment
 # Change directory to the oceanumlab directory
 # Install package in development mode
-pip install -e .
+pip install -e ".[test]"
 # Link your development version of the extension with JupyterLab
 jupyter labextension develop . --overwrite
 # Server extension must be manually installed in develop mode
 jupyter server extension enable oceanumlab
 # Rebuild extension Typescript source after making changes
 jlpm build
 ```
@@ -89,26 +89,28 @@
 # Server extension must be manually disabled in develop mode
 jupyter server extension disable oceanumlab
 pip uninstall oceanumlab
 ```
 
 In development mode, you will also need to remove the symlink created by `jupyter labextension develop`
 command. To find its location, you can run `jupyter labextension list` to figure out where the `labextensions`
-folder is located. Then you can remove the symlink named `oceanumlab` within that folder.
+folder is located. Then you can remove the symlink named `@oceanum/oceanumlab` within that folder.
 
 ### Testing the extension
 
 #### Server tests
 
 This extension is using [Pytest](https://docs.pytest.org/) for Python code testing.
 
 Install test dependencies (needed only once):
 
 ```sh
 pip install -e ".[test]"
+# Each time you install the Python package, you need to restore the front-end extension link
+jupyter labextension develop . --overwrite
 ```
 
 To execute them, run:
 
 ```sh
 pytest -vv -r ap --cov oceanumlab
 ```
```

### Comparing `oceanumlab-0.4.1/jest.config.js` & `oceanumlab-0.4.2/jest.config.js`

 * *Files 25% similar despite different names*

#### js-beautify {}

```diff
@@ -1,42 +1,28 @@
 const jestJupyterLab = require('@jupyterlab/testutils/lib/jest-config');
 
 const esModules = [
+    '@codemirror',
+    '@jupyter/ydoc',
     '@jupyterlab/',
     'lib0',
-    'y\\-protocols',
-    'y\\-websocket',
+    'nanoid',
+    'vscode-ws-jsonrpc',
+    'y-protocols',
+    'y-websocket',
     'yjs'
 ].join('|');
 
-const jlabConfig = jestJupyterLab(__dirname);
-
-const {
-    moduleFileExtensions,
-    moduleNameMapper,
-    preset,
-    setupFilesAfterEnv,
-    setupFiles,
-    testPathIgnorePatterns,
-    transform
-} = jlabConfig;
+const baseConfig = jestJupyterLab(__dirname);
 
 module.exports = {
-    moduleFileExtensions,
-    moduleNameMapper,
-    preset,
-    setupFilesAfterEnv,
-    setupFiles,
-    testPathIgnorePatterns,
-    transform,
+    ...baseConfig,
     automock: false,
-    collectCoverageFrom: ['src/**/*.{ts,tsx}', '!src/**/*.d.ts'],
-    coverageDirectory: 'coverage',
+    collectCoverageFrom: [
+        'src/**/*.{ts,tsx}',
+        '!src/**/*.d.ts',
+        '!src/**/.ipynb_checkpoints/*'
+    ],
     coverageReporters: ['lcov', 'text'],
-    globals: {
-        'ts-jest': {
-            tsconfig: 'tsconfig.json'
-        }
-    },
     testRegex: 'src/.*/.*.spec.ts[x]?$',
     transformIgnorePatterns: [`/node_modules/(?!${esModules}).+`]
 };
```

### Comparing `oceanumlab-0.4.1/oceanumlab/__init__.py` & `oceanumlab-0.4.2/oceanumlab/__init__.py`

 * *Files identical despite different names*

### Comparing `oceanumlab-0.4.1/oceanumlab/handlers.py` & `oceanumlab-0.4.2/oceanumlab/handlers.py`

 * *Files identical despite different names*

### Comparing `oceanumlab-0.4.1/oceanumlab/labextension/package.json` & `oceanumlab-0.4.2/package.json`

 * *Files 2% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.9672619047619049%*

 * *Differences: {"'dependencies'": "{'@jupyterlab/rendermime-interfaces': '3.6.1'}",*

 * * "'jupyterlab'": "{delete: ['_build']}",*

 * * "'version'": "'0.4.2'"}*

```diff
@@ -6,14 +6,15 @@
     "bugs": {
         "url": "https://github.com/oceanum-io/oceanumlab/issues"
     },
     "dependencies": {
         "@jupyterlab/application": "^3.6.1",
         "@jupyterlab/apputils": "3.6.1",
         "@jupyterlab/coreutils": "^5.6.1",
+        "@jupyterlab/rendermime-interfaces": "3.6.1",
         "@jupyterlab/services": "^6.6.1",
         "@jupyterlab/settingregistry": "^3.6.1",
         "phosphor-react": "^1.4.1"
     },
     "description": "A Jupyterlab extension to interact with the Oceanum.io platform",
     "devDependencies": {
         "@babel/core": "^7.21.0",
@@ -53,19 +54,14 @@
             ],
             "before-build-python": [
                 "jlpm clean:all"
             ]
         }
     },
     "jupyterlab": {
-        "_build": {
-            "extension": "./extension",
-            "load": "static/remoteEntry.8438a14f26699b797d74.js",
-            "style": "./style"
-        },
         "discovery": {
             "server": {
                 "base": {
                     "name": "oceanumlab"
                 },
                 "managers": [
                     "pip"
@@ -119,9 +115,9 @@
         "watch:src": "npx tsc -w"
     },
     "sideEffects": [
         "style/*.css"
     ],
     "style": "style/index.css",
     "types": "lib/index.d.ts",
-    "version": "0.4.0"
+    "version": "0.4.2"
 }
```

### Comparing `oceanumlab-0.4.1/oceanumlab/labextension/schemas/@oceanum/oceanumlab/package.json.orig` & `oceanumlab-0.4.2/oceanumlab/labextension/schemas/@oceanum/oceanumlab/package.json.orig`

 * *Files 2% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.9714285714285715%*

 * *Differences: {"'dependencies'": "{'@jupyterlab/rendermime-interfaces': '3.6.1'}", "'version'": "'0.4.2'"}*

```diff
@@ -6,14 +6,15 @@
     "bugs": {
         "url": "https://github.com/oceanum-io/oceanumlab/issues"
     },
     "dependencies": {
         "@jupyterlab/application": "^3.6.1",
         "@jupyterlab/apputils": "3.6.1",
         "@jupyterlab/coreutils": "^5.6.1",
+        "@jupyterlab/rendermime-interfaces": "3.6.1",
         "@jupyterlab/services": "^6.6.1",
         "@jupyterlab/settingregistry": "^3.6.1",
         "phosphor-react": "^1.4.1"
     },
     "description": "A Jupyterlab extension to interact with the Oceanum.io platform",
     "devDependencies": {
         "@babel/core": "^7.21.0",
@@ -114,9 +115,9 @@
         "watch:src": "npx tsc -w"
     },
     "sideEffects": [
         "style/*.css"
     ],
     "style": "style/index.css",
     "types": "lib/index.d.ts",
-    "version": "0.4.0"
+    "version": "0.4.2"
 }
```

### Comparing `oceanumlab-0.4.1/oceanumlab/labextension/schemas/@oceanum/oceanumlab/plugin.json` & `oceanumlab-0.4.2/oceanumlab/labextension/schemas/@oceanum/oceanumlab/plugin.json`

 * *Files identical despite different names*

### Comparing `oceanumlab-0.4.1/package.json` & `oceanumlab-0.4.2/oceanumlab/labextension/package.json`

 * *Files 2% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.9672619047619049%*

 * *Differences: {"'dependencies'": "{'@jupyterlab/rendermime-interfaces': '3.6.1'}",*

 * * "'jupyterlab'": "{'_build': OrderedDict([('load', 'static/remoteEntry.d6c53f9a8466e60ef1b1.js'), "*

 * *                 "('extension', './extension'), ('style', './style')])}",*

 * * "'version'": "'0.4.2'"}*

```diff
@@ -6,14 +6,15 @@
     "bugs": {
         "url": "https://github.com/oceanum-io/oceanumlab/issues"
     },
     "dependencies": {
         "@jupyterlab/application": "^3.6.1",
         "@jupyterlab/apputils": "3.6.1",
         "@jupyterlab/coreutils": "^5.6.1",
+        "@jupyterlab/rendermime-interfaces": "3.6.1",
         "@jupyterlab/services": "^6.6.1",
         "@jupyterlab/settingregistry": "^3.6.1",
         "phosphor-react": "^1.4.1"
     },
     "description": "A Jupyterlab extension to interact with the Oceanum.io platform",
     "devDependencies": {
         "@babel/core": "^7.21.0",
@@ -53,14 +54,19 @@
             ],
             "before-build-python": [
                 "jlpm clean:all"
             ]
         }
     },
     "jupyterlab": {
+        "_build": {
+            "extension": "./extension",
+            "load": "static/remoteEntry.d6c53f9a8466e60ef1b1.js",
+            "style": "./style"
+        },
         "discovery": {
             "server": {
                 "base": {
                     "name": "oceanumlab"
                 },
                 "managers": [
                     "pip"
@@ -114,9 +120,9 @@
         "watch:src": "npx tsc -w"
     },
     "sideEffects": [
         "style/*.css"
     ],
     "style": "style/index.css",
     "types": "lib/index.d.ts",
-    "version": "0.4.1"
+    "version": "0.4.2"
 }
```

### Comparing `oceanumlab-0.4.1/schema/plugin.json` & `oceanumlab-0.4.2/schema/plugin.json`

 * *Files identical despite different names*

### Comparing `oceanumlab-0.4.1/setup.py` & `oceanumlab-0.4.2/setup.py`

 * *Files identical despite different names*

### Comparing `oceanumlab-0.4.1/src/DatameshWidget.tsx` & `oceanumlab-0.4.2/src/DatameshWidget.tsx`

 * *Files 2% similar despite different names*

```diff
@@ -1,64 +1,70 @@
 import { JupyterFrontEnd } from '@jupyterlab/application';
 import {
   Dialog,
-  showDialog,
   ReactWidget,
-  UseSignal
+  UseSignal,
+  showDialog
 } from '@jupyterlab/apputils';
 import { CodeCell } from '@jupyterlab/cells';
 import { CodeEditor } from '@jupyterlab/codeeditor';
 import * as nbformat from '@jupyterlab/nbformat';
 import { Notebook, NotebookModel, NotebookPanel } from '@jupyterlab/notebook';
-import { addIcon, LabIcon } from '@jupyterlab/ui-components';
+import { LabIcon, addIcon } from '@jupyterlab/ui-components';
 import { MimeData } from '@lumino/coreutils';
 import { Drag } from '@lumino/dragdrop';
-import { Widget } from '@lumino/widgets';
 import { Signal } from '@lumino/signaling';
+import { Widget } from '@lumino/widgets';
 
 import React from 'react';
 
 import { DatasourceItem } from './DatasourceItem';
 
 const JUPYTER_CELL_MIME = 'application/vnd.jupyter.cells';
 
 const datameshToken = (notebook: Notebook): string => {
   const datameshTokenInjected =
     notebook &&
     notebook.widgets.find(cell => {
-      const line = cell.editor.getLine(0);
-      if (line && line.indexOf('DATAMESH_TOKEN=') >= 0) {
-        return true;
+      if (cell.editor) {
+        const line = cell.editor.getLine(0);
+        if (line && line.indexOf('DATAMESH_TOKEN=') >= 0) {
+          return true;
+        }
       }
     });
   if (!datameshTokenInjected) {
     return `DATAMESH_TOKEN='${window.datameshToken}';`;
+  } else {
+    return '';
   }
 };
 
 const datasourceCode = (
   datasource: IDatasource,
   notebook: Notebook,
   icell: number
 ): string => {
   const datameshImport =
     notebook &&
     notebook.widgets.find(cell => {
-      let found = false;
-      for (let i = 0; i < icell; i++) {
-        const line = cell.editor.getLine(i);
-        if (
-          line &&
-          line.indexOf('from oceanum.datamesh import Connector') >= 0
-        ) {
-          found = true;
-          break;
+      if (cell.editor) {
+        let found = false;
+        for (let i = 0; i < icell; i++) {
+          const line = cell.editor.getLine(i);
+          if (
+            line &&
+            line.indexOf('from oceanum.datamesh import Connector') >= 0
+          ) {
+            found = true;
+            break;
+          }
         }
+        return found;
       }
-      return found;
     });
   let datasourceStr = datasource.datasource.replace(/[\s-.]/g, '_');
   const tokenString = window.injectToken ? 'token=DATAMESH_TOKEN' : '';
   if (
     datasource.variables ||
     datasource.geofilter ||
     datasource.timefilter ||
```

### Comparing `oceanumlab-0.4.1/src/DatasourceItem.tsx` & `oceanumlab-0.4.2/src/DatasourceItem.tsx`

 * *Files identical despite different names*

### Comparing `oceanumlab-0.4.1/src/handler.ts` & `oceanumlab-0.4.2/src/handler.ts`

 * *Files identical despite different names*

### Comparing `oceanumlab-0.4.1/src/index.ts` & `oceanumlab-0.4.2/src/index.ts`

 * *Files identical despite different names*

### Comparing `oceanumlab-0.4.1/style/icons/oceanum.png` & `oceanumlab-0.4.2/style/icons/oceanum.png`

 * *Files identical despite different names*

### Comparing `oceanumlab-0.4.1/style/icons/oceanum.svg` & `oceanumlab-0.4.2/style/icons/oceanum.svg`

 * *Files identical despite different names*

### Comparing `oceanumlab-0.4.1/style/index.css` & `oceanumlab-0.4.2/style/index.css`

 * *Files identical despite different names*

### Comparing `oceanumlab-0.4.1/ui-tests/README.md` & `oceanumlab-0.4.2/_temp_extension/ui-tests/README.md`

 * *Files 5% similar despite different names*

```diff
@@ -1,22 +1,23 @@
 # Integration Testing
 
 This folder contains the integration tests of the extension.
 
-They are defined using [Playwright](https://playwright.dev/docs/intro/) test runner
+They are defined using [Playwright](https://playwright.dev/docs/intro) test runner
 and [Galata](https://github.com/jupyterlab/jupyterlab/tree/master/galata) helper.
 
-The Playwright configuration is defined in [playwright.config.js](../playwright.config.js)
-in the root directory.
+The Playwright configuration is defined in [playwright.config.js](./playwright.config.js).
 
 The JupyterLab server configuration to use for the integration test is defined
-in [jupyter_server_test_config.py](../jupyter_server_test_config.py) in the root directory.
+in [jupyter_server_test_config.py](./jupyter_server_test_config.py).
 
 The default configuration will produce video for failing tests and an HTML report.
 
+> There is a new experimental UI mode that you may fall in love with; see [that video](https://www.youtube.com/watch?v=jF0yA-JLQW0).
+
 ## Run the tests
 
 > All commands are assumed to be executed from the root directory
 
 To run the tests, you need to:
 
 1. Compile the extension:
@@ -106,15 +107,22 @@
 ```sh
 cd ./ui-tests
 jlpm install
 jlpm playwright install
 cd ..
 ```
 
-3. Execute the [Playwright code generator](https://playwright.dev/docs/codegen):
+3. Start the server:
+
+```sh
+cd ./ui-tests
+jlpm start
+```
+
+4. Execute the [Playwright code generator](https://playwright.dev/docs/codegen) in **another terminal**:
 
 ```sh
 cd ./ui-tests
 jlpm playwright codegen localhost:8888
 ```
 
 ## Debug tests
@@ -141,9 +149,19 @@
 cd ..
 ```
 
 3. Execute the Playwright tests in [debug mode](https://playwright.dev/docs/debug):
 
 ```sh
 cd ./ui-tests
-PWDEBUG=1 jlpm playwright test
+jlpm playwright test --debug
+```
+
+## Upgrade Playwright and the browsers
+
+To update the web browser versions, you must update the package `@playwright/test`:
+
+```sh
+cd ./ui-tests
+jlpm up "@playwright/test"
+jlpm playwright install
 ```
```

### Comparing `oceanumlab-0.4.1/ui-tests/tests/oceanumlab.spec.ts` & `oceanumlab-0.4.2/ui-tests/tests/oceanumlab.spec.ts`

 * *Files identical despite different names*


# Comparing `tmp/flask-rest-jsonapi-next-0.34.6.tar.gz` & `tmp/flask-rest-jsonapi-next-0.34.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "flask-rest-jsonapi-next-0.34.6.tar", last modified: Tue Jun 27 11:33:02 2023, max compression
+gzip compressed data, was "flask-rest-jsonapi-next-0.34.7.tar", last modified: Wed Jun 28 13:56:10 2023, max compression
```

## Comparing `flask-rest-jsonapi-next-0.34.6.tar` & `flask-rest-jsonapi-next-0.34.7.tar`

### file list

```diff
@@ -1,81 +1,81 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 11:33:02.482515 flask-rest-jsonapi-next-0.34.6/
--rw-r--r--   0 runner    (1001) docker     (123)      314 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/.bumpversion.cfg
--rw-r--r--   0 runner    (1001) docker     (123)      427 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/.readthedocs.yaml
--rw-r--r--   0 runner    (1001) docker     (123)     4460 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/CHANGELOG.md
--rw-r--r--   0 runner    (1001) docker     (123)     1071 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)      254 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)     4860 2023-06-27 11:33:02.482515 flask-rest-jsonapi-next-0.34.6/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     3719 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 11:33:02.478515 flask-rest-jsonapi-next-0.34.6/docs/
--rw-r--r--   0 runner    (1001) docker     (123)     7634 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/docs/Makefile
--rw-r--r--   0 runner    (1001) docker     (123)      295 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/docs/api.rst
--rw-r--r--   0 runner    (1001) docker     (123)     1298 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/docs/conf.py
--rw-r--r--   0 runner    (1001) docker     (123)      485 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/docs/configuration.rst
--rw-r--r--   0 runner    (1001) docker     (123)     5591 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/docs/data_layer.rst
--rw-r--r--   0 runner    (1001) docker     (123)     2854 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/docs/errors.rst
--rw-r--r--   0 runner    (1001) docker     (123)     5512 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/docs/features.rst
--rw-r--r--   0 runner    (1001) docker     (123)     5160 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/docs/filtering.rst
--rw-r--r--   0 runner    (1001) docker     (123)     2265 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/docs/flask-rest-jsonapi-next.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 11:33:02.478515 flask-rest-jsonapi-next-0.34.6/docs/img/
--rw-r--r--   0 runner    (1001) docker     (123)    60801 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/docs/img/schema.png
--rw-r--r--   0 runner    (1001) docker     (123)     4119 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/docs/include_related_objects.rst
--rw-r--r--   0 runner    (1001) docker     (123)     2841 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/docs/index.rst
--rw-r--r--   0 runner    (1001) docker     (123)      609 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/docs/installation.rst
--rw-r--r--   0 runner    (1001) docker     (123)     4453 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/docs/logical_data_abstraction.rst
--rw-r--r--   0 runner    (1001) docker     (123)      800 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/docs/make.bat
--rw-r--r--   0 runner    (1001) docker     (123)      106 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/docs/modules.rst
--rw-r--r--   0 runner    (1001) docker     (123)     2362 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/docs/oauth.rst
--rw-r--r--   0 runner    (1001) docker     (123)     1034 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/docs/pagination.rst
--rw-r--r--   0 runner    (1001) docker     (123)     2783 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/docs/permission.rst
--rw-r--r--   0 runner    (1001) docker     (123)    25491 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/docs/quickstart.rst
--rw-r--r--   0 runner    (1001) docker     (123)     6990 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/docs/resource_manager.rst
--rw-r--r--   0 runner    (1001) docker     (123)      882 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/docs/routing.rst
--rw-r--r--   0 runner    (1001) docker     (123)      896 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/docs/sorting.rst
--rw-r--r--   0 runner    (1001) docker     (123)     1686 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/docs/sparse_fieldsets.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 11:33:02.478515 flask-rest-jsonapi-next-0.34.6/examples/
--rw-r--r--   0 runner    (1001) docker     (123)     5717 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/examples/api.py
--rw-r--r--   0 runner    (1001) docker     (123)     7316 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/examples/api_nested.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 11:33:02.478515 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/
--rw-r--r--   0 runner    (1001) docker     (123)      376 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     7840 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/api.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 11:33:02.478515 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/data_layers/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/data_layers/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    32059 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/data_layers/alchemy.py
--rw-r--r--   0 runner    (1001) docker     (123)    14136 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/data_layers/base.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 11:33:02.478515 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/data_layers/filtering/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/data_layers/filtering/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6158 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/data_layers/filtering/alchemy.py
--rw-r--r--   0 runner    (1001) docker     (123)     2654 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/decorators.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 11:33:02.478515 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/error_responses/
--rw-r--r--   0 runner    (1001) docker     (123)      209 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/error_responses/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2331 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/error_responses/error_formatters.py
--rw-r--r--   0 runner    (1001) docker     (123)     2504 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/error_responses/errors_as_json_api.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 11:33:02.482515 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/error_responses/exception_converters/
--rw-r--r--   0 runner    (1001) docker     (123)      294 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/error_responses/exception_converters/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2152 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/error_responses/exception_converters/base.py
--rw-r--r--   0 runner    (1001) docker     (123)      493 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/error_responses/exception_converters/flask_rest_jsonapi.py
--rw-r--r--   0 runner    (1001) docker     (123)     1342 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/error_responses/exception_converters/marshamallow.py
--rw-r--r--   0 runner    (1001) docker     (123)     2024 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/error_responses/exception_converters/registry.py
--rw-r--r--   0 runner    (1001) docker     (123)     8494 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/error_responses/exception_converters/sqlalchemy.py
--rw-r--r--   0 runner    (1001) docker     (123)      335 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/error_responses/exception_converters/werkzeug.py
--rw-r--r--   0 runner    (1001) docker     (123)      617 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/error_responses/exceptions.py
--rw-r--r--   0 runner    (1001) docker     (123)      478 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/errors.py
--rw-r--r--   0 runner    (1001) docker     (123)     3072 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/exceptions.py
--rw-r--r--   0 runner    (1001) docker     (123)     1994 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/pagination.py
--rw-r--r--   0 runner    (1001) docker     (123)     7678 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/querystring.py
--rw-r--r--   0 runner    (1001) docker     (123)    21925 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/resource.py
--rw-r--r--   0 runner    (1001) docker     (123)     7386 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/schema.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 11:33:02.478515 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     4860 2023-06-27 11:33:02.000000 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2306 2023-06-27 11:33:02.000000 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 11:33:02.000000 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 11:33:02.000000 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)      288 2023-06-27 11:33:02.000000 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       43 2023-06-27 11:33:02.000000 flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)     2140 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-27 11:33:02.482515 flask-rest-jsonapi-next-0.34.6/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)       69 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 11:33:02.482515 flask-rest-jsonapi-next-0.34.6/tests/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/tests/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      171 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/tests/conftest.py
--rw-r--r--   0 runner    (1001) docker     (123)    69985 2023-06-27 11:32:52.000000 flask-rest-jsonapi-next-0.34.6/tests/test_sqlalchemy_data_layer.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:56:10.527414 flask-rest-jsonapi-next-0.34.7/
+-rw-r--r--   0 runner    (1001) docker     (123)      314 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/.bumpversion.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)      427 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/.readthedocs.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)     4521 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/CHANGELOG.md
+-rw-r--r--   0 runner    (1001) docker     (123)     1071 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)      254 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)     4860 2023-06-28 13:56:10.527414 flask-rest-jsonapi-next-0.34.7/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     3719 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:56:10.519414 flask-rest-jsonapi-next-0.34.7/docs/
+-rw-r--r--   0 runner    (1001) docker     (123)     7634 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/docs/Makefile
+-rw-r--r--   0 runner    (1001) docker     (123)      295 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/docs/api.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1298 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/docs/conf.py
+-rw-r--r--   0 runner    (1001) docker     (123)      485 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/docs/configuration.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     5591 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/docs/data_layer.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     2854 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/docs/errors.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     5512 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/docs/features.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     5160 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/docs/filtering.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     2265 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/docs/flask-rest-jsonapi-next.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:56:10.519414 flask-rest-jsonapi-next-0.34.7/docs/img/
+-rw-r--r--   0 runner    (1001) docker     (123)    60801 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/docs/img/schema.png
+-rw-r--r--   0 runner    (1001) docker     (123)     4119 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/docs/include_related_objects.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     2841 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/docs/index.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      609 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/docs/installation.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     4453 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/docs/logical_data_abstraction.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      800 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/docs/make.bat
+-rw-r--r--   0 runner    (1001) docker     (123)      106 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/docs/modules.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     2362 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/docs/oauth.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1034 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/docs/pagination.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     2783 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/docs/permission.rst
+-rw-r--r--   0 runner    (1001) docker     (123)    25491 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/docs/quickstart.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     6990 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/docs/resource_manager.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      882 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/docs/routing.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      896 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/docs/sorting.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1686 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/docs/sparse_fieldsets.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:56:10.519414 flask-rest-jsonapi-next-0.34.7/examples/
+-rw-r--r--   0 runner    (1001) docker     (123)     5717 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/examples/api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7316 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/examples/api_nested.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:56:10.523414 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/
+-rw-r--r--   0 runner    (1001) docker     (123)      376 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7840 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/api.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:56:10.523414 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/data_layers/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/data_layers/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    32059 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/data_layers/alchemy.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14136 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/data_layers/base.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:56:10.523414 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/data_layers/filtering/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/data_layers/filtering/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6158 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/data_layers/filtering/alchemy.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2654 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/decorators.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:56:10.523414 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/error_responses/
+-rw-r--r--   0 runner    (1001) docker     (123)      209 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/error_responses/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2331 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/error_responses/error_formatters.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2504 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/error_responses/errors_as_json_api.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:56:10.523414 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/error_responses/exception_converters/
+-rw-r--r--   0 runner    (1001) docker     (123)      294 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/error_responses/exception_converters/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2152 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/error_responses/exception_converters/base.py
+-rw-r--r--   0 runner    (1001) docker     (123)      493 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/error_responses/exception_converters/flask_rest_jsonapi.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1342 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/error_responses/exception_converters/marshamallow.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2072 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/error_responses/exception_converters/registry.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8494 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/error_responses/exception_converters/sqlalchemy.py
+-rw-r--r--   0 runner    (1001) docker     (123)      335 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/error_responses/exception_converters/werkzeug.py
+-rw-r--r--   0 runner    (1001) docker     (123)      617 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/error_responses/exceptions.py
+-rw-r--r--   0 runner    (1001) docker     (123)      478 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/errors.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3072 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/exceptions.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1994 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/pagination.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7678 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/querystring.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21925 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/resource.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7386 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/schema.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:56:10.523414 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     4860 2023-06-28 13:56:10.000000 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2306 2023-06-28 13:56:10.000000 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 13:56:10.000000 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 13:56:10.000000 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)      288 2023-06-28 13:56:10.000000 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       43 2023-06-28 13:56:10.000000 flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     2140 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 13:56:10.527414 flask-rest-jsonapi-next-0.34.7/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)       69 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:56:10.527414 flask-rest-jsonapi-next-0.34.7/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/tests/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      171 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/tests/conftest.py
+-rw-r--r--   0 runner    (1001) docker     (123)    69985 2023-06-28 13:56:00.000000 flask-rest-jsonapi-next-0.34.7/tests/test_sqlalchemy_data_layer.py
```

### Comparing `flask-rest-jsonapi-next-0.34.6/CHANGELOG.md` & `flask-rest-jsonapi-next-0.34.7/CHANGELOG.md`

 * *Files 4% similar despite different names*

```diff
@@ -1,9 +1,13 @@
 # CHANGELOG
 
+## 0.34.7 (fork-0.34.7) (2023-06-28)
+
+- fix: missing import
+
 ## 0.34.6 (fork-0.34.6) (2023-06-27)
 
 - fix: filtering operator `between` was not correctly implemented for SQLAlchemy
   data layer
 
 ## 0.34.5 (fork-0.34.5) (2023-02-13)
```

### Comparing `flask-rest-jsonapi-next-0.34.6/LICENSE` & `flask-rest-jsonapi-next-0.34.7/LICENSE`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/PKG-INFO` & `flask-rest-jsonapi-next-0.34.7/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: flask-rest-jsonapi-next
-Version: 0.34.6
+Version: 0.34.7
 Summary: Flask extension to create REST web api according to JSONAPI 1.0 specification with Flask, Marshmallow and data provider of your choice (SQLAlchemy, MongoDB, ...)
 Author: original miLibris/flask-rest-jsonapi contributors
 Maintainer-email: Tomislav Adamic <tomislav.adamic@gmail.com>
 License: MIT
 Project-URL: Source, https://github.com/tadams42/flask-rest-jsonapi-next
 Project-URL: Documentation, https://flask-rest-jsonapi-next.readthedocs.io/en/latest/
 Keywords: web,api,rest,jsonapi,flask,sqlalchemy,marshmallow
```

### Comparing `flask-rest-jsonapi-next-0.34.6/README.md` & `flask-rest-jsonapi-next-0.34.7/README.md`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/docs/Makefile` & `flask-rest-jsonapi-next-0.34.7/docs/Makefile`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/docs/conf.py` & `flask-rest-jsonapi-next-0.34.7/docs/conf.py`

 * *Files 1% similar despite different names*

```diff
@@ -5,15 +5,15 @@
 
 # -- Project information -----------------------------------------------------
 # https://www.sphinx-doc.org/en/master/usage/configuration.html#project-information
 
 project = "flask-rest-jsonapi-next"
 copyright = "2016-2021 miLibris; 2021-... miLibris, tadams42"
 author = "tadams42"
-release = "0.34.6"
+release = "0.34.7"
 
 # -- General configuration ---------------------------------------------------
 # https://www.sphinx-doc.org/en/master/usage/configuration.html#general-configuration
 
 extensions = [
     "sphinx.ext.autodoc",
     "sphinx.ext.intersphinx",
```

### Comparing `flask-rest-jsonapi-next-0.34.6/docs/data_layer.rst` & `flask-rest-jsonapi-next-0.34.7/docs/data_layer.rst`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/docs/errors.rst` & `flask-rest-jsonapi-next-0.34.7/docs/errors.rst`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/docs/features.rst` & `flask-rest-jsonapi-next-0.34.7/docs/features.rst`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/docs/filtering.rst` & `flask-rest-jsonapi-next-0.34.7/docs/filtering.rst`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/docs/flask-rest-jsonapi-next.rst` & `flask-rest-jsonapi-next-0.34.7/docs/flask-rest-jsonapi-next.rst`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/docs/img/schema.png` & `flask-rest-jsonapi-next-0.34.7/docs/img/schema.png`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/docs/include_related_objects.rst` & `flask-rest-jsonapi-next-0.34.7/docs/include_related_objects.rst`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/docs/index.rst` & `flask-rest-jsonapi-next-0.34.7/docs/index.rst`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/docs/installation.rst` & `flask-rest-jsonapi-next-0.34.7/docs/installation.rst`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/docs/logical_data_abstraction.rst` & `flask-rest-jsonapi-next-0.34.7/docs/logical_data_abstraction.rst`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/docs/make.bat` & `flask-rest-jsonapi-next-0.34.7/docs/make.bat`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/docs/oauth.rst` & `flask-rest-jsonapi-next-0.34.7/docs/oauth.rst`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/docs/pagination.rst` & `flask-rest-jsonapi-next-0.34.7/docs/pagination.rst`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/docs/permission.rst` & `flask-rest-jsonapi-next-0.34.7/docs/permission.rst`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/docs/quickstart.rst` & `flask-rest-jsonapi-next-0.34.7/docs/quickstart.rst`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/docs/resource_manager.rst` & `flask-rest-jsonapi-next-0.34.7/docs/resource_manager.rst`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/docs/routing.rst` & `flask-rest-jsonapi-next-0.34.7/docs/routing.rst`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/docs/sorting.rst` & `flask-rest-jsonapi-next-0.34.7/docs/sorting.rst`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/docs/sparse_fieldsets.rst` & `flask-rest-jsonapi-next-0.34.7/docs/sparse_fieldsets.rst`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/examples/api.py` & `flask-rest-jsonapi-next-0.34.7/examples/api.py`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/examples/api_nested.py` & `flask-rest-jsonapi-next-0.34.7/examples/api_nested.py`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/api.py` & `flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/api.py`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/data_layers/alchemy.py` & `flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/data_layers/alchemy.py`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/data_layers/base.py` & `flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/data_layers/base.py`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/data_layers/filtering/alchemy.py` & `flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/data_layers/filtering/alchemy.py`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/decorators.py` & `flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/decorators.py`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/error_responses/error_formatters.py` & `flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/error_responses/error_formatters.py`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/error_responses/errors_as_json_api.py` & `flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/error_responses/errors_as_json_api.py`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/error_responses/exception_converters/base.py` & `flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/error_responses/exception_converters/base.py`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/error_responses/exception_converters/marshamallow.py` & `flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/error_responses/exception_converters/marshamallow.py`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/error_responses/exception_converters/registry.py` & `flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/error_responses/exception_converters/registry.py`

 * *Files 3% similar despite different names*

```diff
@@ -42,14 +42,15 @@
 
         if klass and klass not in CONVERTERS_REGISTRY:
             CONVERTERS_REGISTRY.append(klass)
 
     @classmethod
     def get_converted_data(cls, err):
         from .sqlalchemy import GenericSQLAlchemyErrorConverter
+        from .base import GenericErrorConverter
 
         data = None
 
         for klass in CONVERTERS_REGISTRY:
             try:
                 data = klass.convert(err)
             except ValueError:
```

### Comparing `flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/error_responses/exception_converters/sqlalchemy.py` & `flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/error_responses/exception_converters/sqlalchemy.py`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/error_responses/exceptions.py` & `flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/error_responses/exceptions.py`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/exceptions.py` & `flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/exceptions.py`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/pagination.py` & `flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/pagination.py`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/querystring.py` & `flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/querystring.py`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/resource.py` & `flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/resource.py`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next/schema.py` & `flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next/schema.py`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next.egg-info/PKG-INFO` & `flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: flask-rest-jsonapi-next
-Version: 0.34.6
+Version: 0.34.7
 Summary: Flask extension to create REST web api according to JSONAPI 1.0 specification with Flask, Marshmallow and data provider of your choice (SQLAlchemy, MongoDB, ...)
 Author: original miLibris/flask-rest-jsonapi contributors
 Maintainer-email: Tomislav Adamic <tomislav.adamic@gmail.com>
 License: MIT
 Project-URL: Source, https://github.com/tadams42/flask-rest-jsonapi-next
 Project-URL: Documentation, https://flask-rest-jsonapi-next.readthedocs.io/en/latest/
 Keywords: web,api,rest,jsonapi,flask,sqlalchemy,marshmallow
```

### Comparing `flask-rest-jsonapi-next-0.34.6/flask_rest_jsonapi_next.egg-info/SOURCES.txt` & `flask-rest-jsonapi-next-0.34.7/flask_rest_jsonapi_next.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `flask-rest-jsonapi-next-0.34.6/pyproject.toml` & `flask-rest-jsonapi-next-0.34.7/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -2,15 +2,15 @@
 # setuptools v64 was first to support `pip install -e` for packages defined using
 # pyproject.toml (older versions support this, but only for setup.py projects)
 requires = ["setuptools>=64", "wheel"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "flask-rest-jsonapi-next"
-version = "0.34.6"
+version = "0.34.7"
 description = "Flask extension to create REST web api according to JSONAPI 1.0 specification with Flask, Marshmallow and data provider of your choice (SQLAlchemy, MongoDB, ...)"
 readme = "README.md"
 classifiers = [
 	"Framework :: Flask",
 	"Programming Language :: Python :: 3",
 	"Programming Language :: Python :: 3.7",
 	"Programming Language :: Python :: 3.8",
```

### Comparing `flask-rest-jsonapi-next-0.34.6/tests/test_sqlalchemy_data_layer.py` & `flask-rest-jsonapi-next-0.34.7/tests/test_sqlalchemy_data_layer.py`

 * *Files identical despite different names*


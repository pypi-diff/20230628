# Comparing `tmp/thipster-0.20.0.tar.gz` & `tmp/thipster-0.20.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "thipster-0.20.0.tar", last modified: Tue Jun 27 07:58:24 2023, max compression
+gzip compressed data, was "thipster-0.20.1.tar", last modified: Wed Jun 28 07:44:44 2023, max compression
```

## Comparing `thipster-0.20.0.tar` & `thipster-0.20.1.tar`

### file list

```diff
@@ -1,81 +1,81 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 07:58:24.620068 thipster-0.20.0/
--rw-r--r--   0 root         (0) root         (0)     1052 2023-06-27 07:58:20.000000 thipster-0.20.0/LICENSE
--rw-r--r--   0 root         (0) root         (0)       81 2023-06-27 07:58:20.000000 thipster-0.20.0/MANIFEST.in
--rw-r--r--   0 root         (0) root         (0)     5376 2023-06-27 07:58:24.620068 thipster-0.20.0/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)     4544 2023-06-27 07:58:20.000000 thipster-0.20.0/README.md
--rw-r--r--   0 root         (0) root         (0)     1358 2023-06-27 07:58:20.000000 thipster-0.20.0/pyproject.toml
--rw-r--r--   0 root         (0) root         (0)       82 2023-06-27 07:58:20.000000 thipster-0.20.0/requirements.txt
--rw-r--r--   0 root         (0) root         (0)       38 2023-06-27 07:58:24.620068 thipster-0.20.0/setup.cfg
--rw-r--r--   0 root         (0) root         (0)     1848 2023-06-27 07:58:21.000000 thipster-0.20.0/setup.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 07:58:24.608067 thipster-0.20.0/tests/
--rw-r--r--   0 root         (0) root         (0)       38 2023-06-27 07:58:20.000000 thipster-0.20.0/tests/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 07:58:24.608067 thipster-0.20.0/tests/engine/
--rw-r--r--   0 root         (0) root         (0)       29 2023-06-27 07:58:20.000000 thipster-0.20.0/tests/engine/__init__.py
--rw-r--r--   0 root         (0) root         (0)     3478 2023-06-27 07:58:20.000000 thipster-0.20.0/tests/engine/test_engine.py
--rw-r--r--   0 root         (0) root         (0)     6190 2023-06-27 07:58:20.000000 thipster-0.20.0/tests/engine/test_generation.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 07:58:24.608067 thipster-0.20.0/tests/parser/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 07:58:20.000000 thipster-0.20.0/tests/parser/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 07:58:24.612067 thipster-0.20.0/tests/parser/dsl_parser/
--rw-r--r--   0 root         (0) root         (0)       33 2023-06-27 07:58:20.000000 thipster-0.20.0/tests/parser/dsl_parser/__init__.py
--rw-r--r--   0 root         (0) root         (0)     1436 2023-06-27 07:58:20.000000 thipster-0.20.0/tests/parser/dsl_parser/test_ast.py
--rw-r--r--   0 root         (0) root         (0)    17236 2023-06-27 07:58:20.000000 thipster-0.20.0/tests/parser/dsl_parser/test_dslparser.py
--rw-r--r--   0 root         (0) root         (0)    15129 2023-06-27 07:58:20.000000 thipster-0.20.0/tests/parser/dsl_parser/test_lexer.py
--rw-r--r--   0 root         (0) root         (0)     1028 2023-06-27 07:58:20.000000 thipster-0.20.0/tests/parser/dsl_parser/test_token.py
--rw-r--r--   0 root         (0) root         (0)     3748 2023-06-27 07:58:20.000000 thipster-0.20.0/tests/parser/dsl_parser/test_tokenparser.py
--rw-r--r--   0 root         (0) root         (0)     5314 2023-06-27 07:58:20.000000 thipster-0.20.0/tests/parser/test_parsedfile.py
--rw-r--r--   0 root         (0) root         (0)     3558 2023-06-27 07:58:20.000000 thipster-0.20.0/tests/parser/test_parserfactory.py
--rw-r--r--   0 root         (0) root         (0)     4822 2023-06-27 07:58:20.000000 thipster-0.20.0/tests/parser/test_yamlparser.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 07:58:24.612067 thipster-0.20.0/tests/repository/
--rw-r--r--   0 root         (0) root         (0)       50 2023-06-27 07:58:20.000000 thipster-0.20.0/tests/repository/__init__.py
--rw-r--r--   0 root         (0) root         (0)     1745 2023-06-27 07:58:20.000000 thipster-0.20.0/tests/repository/test_github_repository.py
--rw-r--r--   0 root         (0) root         (0)     6375 2023-06-27 07:58:20.000000 thipster-0.20.0/tests/repository/test_local_repository.py
--rw-r--r--   0 root         (0) root         (0)     6201 2023-06-27 07:58:20.000000 thipster-0.20.0/tests/repository/test_resourcemodel.py
--rw-r--r--   0 root         (0) root         (0)     3577 2023-06-27 07:58:20.000000 thipster-0.20.0/tests/test_e2e.py
--rw-r--r--   0 root         (0) root         (0)     6483 2023-06-27 07:58:20.000000 thipster-0.20.0/tests/test_tools.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 07:58:24.612067 thipster-0.20.0/thipster/
--rw-r--r--   0 root         (0) root         (0)      171 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 07:58:24.612067 thipster-0.20.0/thipster/auth/
--rw-r--r--   0 root         (0) root         (0)      215 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/auth/__init__.py
--rw-r--r--   0 root         (0) root         (0)      964 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/auth/google.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 07:58:24.616068 thipster-0.20.0/thipster/engine/
--rw-r--r--   0 root         (0) root         (0)      415 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/engine/__init__.py
--rw-r--r--   0 root         (0) root         (0)     5610 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/engine/engine.py
--rw-r--r--   0 root         (0) root         (0)      434 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/engine/exceptions.py
--rw-r--r--   0 root         (0) root         (0)      456 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/engine/i_auth.py
--rw-r--r--   0 root         (0) root         (0)      828 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/engine/i_parser.py
--rw-r--r--   0 root         (0) root         (0)      621 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/engine/i_repository.py
--rw-r--r--   0 root         (0) root         (0)     2166 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/engine/i_terraform.py
--rw-r--r--   0 root         (0) root         (0)     5757 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/engine/parsed_file.py
--rw-r--r--   0 root         (0) root         (0)     4646 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/engine/resource_model.py
--rw-r--r--   0 root         (0) root         (0)      719 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/helpers.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 07:58:24.616068 thipster-0.20.0/thipster/parser/
--rw-r--r--   0 root         (0) root         (0)      364 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/parser/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 07:58:24.616068 thipster-0.20.0/thipster/parser/dsl_parser/
--rw-r--r--   0 root         (0) root         (0)       30 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/parser/dsl_parser/__init__.py
--rw-r--r--   0 root         (0) root         (0)    12599 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/parser/dsl_parser/ast.py
--rw-r--r--   0 root         (0) root         (0)     5311 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/parser/dsl_parser/exceptions.py
--rw-r--r--   0 root         (0) root         (0)    14004 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/parser/dsl_parser/interpreter.py
--rw-r--r--   0 root         (0) root         (0)    14943 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/parser/dsl_parser/lexer.py
--rw-r--r--   0 root         (0) root         (0)     3283 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/parser/dsl_parser/lexer_position.py
--rw-r--r--   0 root         (0) root         (0)     2127 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/parser/dsl_parser/parser.py
--rw-r--r--   0 root         (0) root         (0)     2472 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/parser/dsl_parser/token.py
--rw-r--r--   0 root         (0) root         (0)    21940 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/parser/dsl_parser/token_parser.py
--rw-r--r--   0 root         (0) root         (0)     1209 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/parser/exceptions.py
--rw-r--r--   0 root         (0) root         (0)     2631 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/parser/parser_factory.py
--rw-r--r--   0 root         (0) root         (0)     6866 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/parser/yaml_parser.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 07:58:24.620068 thipster-0.20.0/thipster/repository/
--rw-r--r--   0 root         (0) root         (0)      332 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/repository/__init__.py
--rw-r--r--   0 root         (0) root         (0)      640 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/repository/exceptions.py
--rw-r--r--   0 root         (0) root         (0)     2015 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/repository/github.py
--rw-r--r--   0 root         (0) root         (0)     4821 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/repository/json.py
--rw-r--r--   0 root         (0) root         (0)     1086 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/repository/local.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 07:58:24.620068 thipster-0.20.0/thipster/terraform/
--rw-r--r--   0 root         (0) root         (0)      327 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/terraform/__init__.py
--rw-r--r--   0 root         (0) root         (0)    24467 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/terraform/cdk.py
--rw-r--r--   0 root         (0) root         (0)     3350 2023-06-27 07:58:20.000000 thipster-0.20.0/thipster/terraform/exceptions.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 07:58:24.612067 thipster-0.20.0/thipster.egg-info/
--rw-r--r--   0 root         (0) root         (0)     5376 2023-06-27 07:58:24.000000 thipster-0.20.0/thipster.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)     1957 2023-06-27 07:58:24.000000 thipster-0.20.0/thipster.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-27 07:58:24.000000 thipster-0.20.0/thipster.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)      388 2023-06-27 07:58:24.000000 thipster-0.20.0/thipster.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)       15 2023-06-27 07:58:24.000000 thipster-0.20.0/thipster.egg-info/top_level.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:44:44.053661 thipster-0.20.1/
+-rw-r--r--   0 root         (0) root         (0)     1052 2023-06-28 07:44:40.000000 thipster-0.20.1/LICENSE
+-rw-r--r--   0 root         (0) root         (0)       81 2023-06-28 07:44:40.000000 thipster-0.20.1/MANIFEST.in
+-rw-r--r--   0 root         (0) root         (0)     5376 2023-06-28 07:44:44.053661 thipster-0.20.1/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     4544 2023-06-28 07:44:40.000000 thipster-0.20.1/README.md
+-rw-r--r--   0 root         (0) root         (0)     1358 2023-06-28 07:44:40.000000 thipster-0.20.1/pyproject.toml
+-rw-r--r--   0 root         (0) root         (0)       82 2023-06-28 07:44:40.000000 thipster-0.20.1/requirements.txt
+-rw-r--r--   0 root         (0) root         (0)       38 2023-06-28 07:44:44.053661 thipster-0.20.1/setup.cfg
+-rw-r--r--   0 root         (0) root         (0)     1848 2023-06-28 07:44:41.000000 thipster-0.20.1/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:44:44.045661 thipster-0.20.1/tests/
+-rw-r--r--   0 root         (0) root         (0)       38 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:44:44.045661 thipster-0.20.1/tests/engine/
+-rw-r--r--   0 root         (0) root         (0)       29 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/engine/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     3478 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/engine/test_engine.py
+-rw-r--r--   0 root         (0) root         (0)     6190 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/engine/test_generation.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:44:44.045661 thipster-0.20.1/tests/parser/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/parser/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:44:44.049661 thipster-0.20.1/tests/parser/dsl_parser/
+-rw-r--r--   0 root         (0) root         (0)       33 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/parser/dsl_parser/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     1436 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/parser/dsl_parser/test_ast.py
+-rw-r--r--   0 root         (0) root         (0)    17236 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/parser/dsl_parser/test_dslparser.py
+-rw-r--r--   0 root         (0) root         (0)    15129 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/parser/dsl_parser/test_lexer.py
+-rw-r--r--   0 root         (0) root         (0)     1028 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/parser/dsl_parser/test_token.py
+-rw-r--r--   0 root         (0) root         (0)     3748 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/parser/dsl_parser/test_tokenparser.py
+-rw-r--r--   0 root         (0) root         (0)     5314 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/parser/test_parsedfile.py
+-rw-r--r--   0 root         (0) root         (0)     3558 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/parser/test_parserfactory.py
+-rw-r--r--   0 root         (0) root         (0)     4822 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/parser/test_yamlparser.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:44:44.049661 thipster-0.20.1/tests/repository/
+-rw-r--r--   0 root         (0) root         (0)       50 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/repository/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     1745 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/repository/test_github_repository.py
+-rw-r--r--   0 root         (0) root         (0)     6375 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/repository/test_local_repository.py
+-rw-r--r--   0 root         (0) root         (0)     6201 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/repository/test_resourcemodel.py
+-rw-r--r--   0 root         (0) root         (0)     3577 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/test_e2e.py
+-rw-r--r--   0 root         (0) root         (0)     6483 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/test_tools.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:44:44.049661 thipster-0.20.1/thipster/
+-rw-r--r--   0 root         (0) root         (0)      171 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:44:44.049661 thipster-0.20.1/thipster/auth/
+-rw-r--r--   0 root         (0) root         (0)      215 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/auth/__init__.py
+-rw-r--r--   0 root         (0) root         (0)      964 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/auth/google.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:44:44.049661 thipster-0.20.1/thipster/engine/
+-rw-r--r--   0 root         (0) root         (0)      415 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/engine/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     5610 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/engine/engine.py
+-rw-r--r--   0 root         (0) root         (0)      434 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/engine/exceptions.py
+-rw-r--r--   0 root         (0) root         (0)      456 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/engine/i_auth.py
+-rw-r--r--   0 root         (0) root         (0)      828 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/engine/i_parser.py
+-rw-r--r--   0 root         (0) root         (0)      621 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/engine/i_repository.py
+-rw-r--r--   0 root         (0) root         (0)     2166 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/engine/i_terraform.py
+-rw-r--r--   0 root         (0) root         (0)     5757 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/engine/parsed_file.py
+-rw-r--r--   0 root         (0) root         (0)     4646 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/engine/resource_model.py
+-rw-r--r--   0 root         (0) root         (0)      719 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/helpers.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:44:44.049661 thipster-0.20.1/thipster/parser/
+-rw-r--r--   0 root         (0) root         (0)      364 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/parser/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:44:44.053661 thipster-0.20.1/thipster/parser/dsl_parser/
+-rw-r--r--   0 root         (0) root         (0)       30 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/parser/dsl_parser/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    12599 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/parser/dsl_parser/ast.py
+-rw-r--r--   0 root         (0) root         (0)     5311 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/parser/dsl_parser/exceptions.py
+-rw-r--r--   0 root         (0) root         (0)    14004 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/parser/dsl_parser/interpreter.py
+-rw-r--r--   0 root         (0) root         (0)    14943 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/parser/dsl_parser/lexer.py
+-rw-r--r--   0 root         (0) root         (0)     3283 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/parser/dsl_parser/lexer_position.py
+-rw-r--r--   0 root         (0) root         (0)     2127 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/parser/dsl_parser/parser.py
+-rw-r--r--   0 root         (0) root         (0)     2472 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/parser/dsl_parser/token.py
+-rw-r--r--   0 root         (0) root         (0)    22021 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/parser/dsl_parser/token_parser.py
+-rw-r--r--   0 root         (0) root         (0)     1209 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/parser/exceptions.py
+-rw-r--r--   0 root         (0) root         (0)     2631 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/parser/parser_factory.py
+-rw-r--r--   0 root         (0) root         (0)     6866 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/parser/yaml_parser.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:44:44.053661 thipster-0.20.1/thipster/repository/
+-rw-r--r--   0 root         (0) root         (0)      332 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/repository/__init__.py
+-rw-r--r--   0 root         (0) root         (0)      640 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/repository/exceptions.py
+-rw-r--r--   0 root         (0) root         (0)     2015 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/repository/github.py
+-rw-r--r--   0 root         (0) root         (0)     4821 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/repository/json.py
+-rw-r--r--   0 root         (0) root         (0)     1086 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/repository/local.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:44:44.053661 thipster-0.20.1/thipster/terraform/
+-rw-r--r--   0 root         (0) root         (0)      327 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/terraform/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    24467 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/terraform/cdk.py
+-rw-r--r--   0 root         (0) root         (0)     3350 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/terraform/exceptions.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:44:44.049661 thipster-0.20.1/thipster.egg-info/
+-rw-r--r--   0 root         (0) root         (0)     5376 2023-06-28 07:44:44.000000 thipster-0.20.1/thipster.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     1957 2023-06-28 07:44:44.000000 thipster-0.20.1/thipster.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 07:44:44.000000 thipster-0.20.1/thipster.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)      388 2023-06-28 07:44:44.000000 thipster-0.20.1/thipster.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)       15 2023-06-28 07:44:44.000000 thipster-0.20.1/thipster.egg-info/top_level.txt
```

### Comparing `thipster-0.20.0/LICENSE` & `thipster-0.20.1/LICENSE`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/PKG-INFO` & `thipster-0.20.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: thipster
-Version: 0.20.0
+Version: 0.20.1
 Summary: THipster is a tool dedicated to simplifying the difficulty associated with writing Terraform files. It allows users to write infrastructure as code in a simplified format, using either YAML (with JINJA) or the dedicated Thipster DSL.
 Home-page: https://github.com/THipster/THipster
 Download-URL: https://github.com/THipster/THipster.git
 Keywords: thipster,terraform,infrastructure,infrastructure-as-code,iac,generator,dsl,yaml
 Classifier: Development Status :: 1 - Planning
 Classifier: Programming Language :: Python :: 3.11
 Classifier: License :: OSI Approved :: MIT License
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: thipster Version: 0.20.0 Summary: THipster is a
+Metadata-Version: 2.1 Name: thipster Version: 0.20.1 Summary: THipster is a
 tool dedicated to simplifying the difficulty associated with writing Terraform
 files. It allows users to write infrastructure as code in a simplified format,
 using either YAML (with JINJA) or the dedicated Thipster DSL. Home-page: https:
 //github.com/THipster/THipster Download-URL: https://github.com/THipster/
 THipster.git Keywords: thipster,terraform,infrastructure,infrastructure-as-
 code,iac,generator,dsl,yaml Classifier: Development Status :: 1 - Planning
 Classifier: Programming Language :: Python :: 3.11 Classifier: License :: OSI
```

### Comparing `thipster-0.20.0/README.md` & `thipster-0.20.1/README.md`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/pyproject.toml` & `thipster-0.20.1/pyproject.toml`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/setup.py` & `thipster-0.20.1/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -10,15 +10,15 @@
     for req_file in Path('requirements').glob('requirements-*.txt'):
         extras_require[
             req_file.stem.removeprefix('requirements-')
         ] = req_file.read_text().splitlines()
     return extras_require
 
 
-__version__ = '0.20.0'
+__version__ = '0.20.1'
 
 with Path('requirements.txt').open() as f:
     required = f.read().splitlines()
 
 with Path('README.md').open() as rm:
     readme = rm.read()
```

### Comparing `thipster-0.20.0/tests/engine/test_engine.py` & `thipster-0.20.1/tests/engine/test_engine.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/tests/engine/test_generation.py` & `thipster-0.20.1/tests/engine/test_generation.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/tests/parser/dsl_parser/test_ast.py` & `thipster-0.20.1/tests/parser/dsl_parser/test_ast.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/tests/parser/dsl_parser/test_dslparser.py` & `thipster-0.20.1/tests/parser/dsl_parser/test_dslparser.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/tests/parser/dsl_parser/test_lexer.py` & `thipster-0.20.1/tests/parser/dsl_parser/test_lexer.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/tests/parser/dsl_parser/test_token.py` & `thipster-0.20.1/tests/parser/dsl_parser/test_token.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/tests/parser/dsl_parser/test_tokenparser.py` & `thipster-0.20.1/tests/parser/dsl_parser/test_tokenparser.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/tests/parser/test_parsedfile.py` & `thipster-0.20.1/tests/parser/test_parsedfile.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/tests/parser/test_parserfactory.py` & `thipster-0.20.1/tests/parser/test_parserfactory.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/tests/parser/test_yamlparser.py` & `thipster-0.20.1/tests/parser/test_yamlparser.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/tests/repository/test_github_repository.py` & `thipster-0.20.1/tests/repository/test_github_repository.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/tests/repository/test_local_repository.py` & `thipster-0.20.1/tests/repository/test_local_repository.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/tests/repository/test_resourcemodel.py` & `thipster-0.20.1/tests/repository/test_resourcemodel.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/tests/test_e2e.py` & `thipster-0.20.1/tests/test_e2e.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/tests/test_tools.py` & `thipster-0.20.1/tests/test_tools.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/thipster/auth/google.py` & `thipster-0.20.1/thipster/auth/google.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/thipster/engine/engine.py` & `thipster-0.20.1/thipster/engine/engine.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/thipster/engine/i_parser.py` & `thipster-0.20.1/thipster/engine/i_parser.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/thipster/engine/i_repository.py` & `thipster-0.20.1/thipster/engine/i_repository.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/thipster/engine/i_terraform.py` & `thipster-0.20.1/thipster/engine/i_terraform.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/thipster/engine/parsed_file.py` & `thipster-0.20.1/thipster/engine/parsed_file.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/thipster/engine/resource_model.py` & `thipster-0.20.1/thipster/engine/resource_model.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/thipster/helpers.py` & `thipster-0.20.1/thipster/helpers.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/thipster/parser/dsl_parser/ast.py` & `thipster-0.20.1/thipster/parser/dsl_parser/ast.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/thipster/parser/dsl_parser/exceptions.py` & `thipster-0.20.1/thipster/parser/dsl_parser/exceptions.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/thipster/parser/dsl_parser/interpreter.py` & `thipster-0.20.1/thipster/parser/dsl_parser/interpreter.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/thipster/parser/dsl_parser/lexer.py` & `thipster-0.20.1/thipster/parser/dsl_parser/lexer.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/thipster/parser/dsl_parser/lexer_position.py` & `thipster-0.20.1/thipster/parser/dsl_parser/lexer_position.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/thipster/parser/dsl_parser/parser.py` & `thipster-0.20.1/thipster/parser/dsl_parser/parser.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/thipster/parser/dsl_parser/token.py` & `thipster-0.20.1/thipster/parser/dsl_parser/token.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/thipster/parser/dsl_parser/token_parser.py` & `thipster-0.20.1/thipster/parser/dsl_parser/token_parser.py`

 * *Files 2% similar despite different names*

```diff
@@ -626,14 +626,17 @@
 
     def __get_atom(self):
         next_token_type = self.__get_next_type()
         match next_token_type:
             case TT.INT:
                 return ast.IntNode(self.__next())
 
+            case TT.VAR:
+                return ast.VariableNode(self.__next())
+
             case TT.FLOAT:
                 return ast.FloatNode(self.__next())
 
             case TT.PARENTHESES_START:
                 self.__next(TT.PARENTHESES_START)
                 self.__get_whitespaces()
                 expression = self.__get_arith_expr()
```

### Comparing `thipster-0.20.0/thipster/parser/exceptions.py` & `thipster-0.20.1/thipster/parser/exceptions.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/thipster/parser/parser_factory.py` & `thipster-0.20.1/thipster/parser/parser_factory.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/thipster/parser/yaml_parser.py` & `thipster-0.20.1/thipster/parser/yaml_parser.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/thipster/repository/exceptions.py` & `thipster-0.20.1/thipster/repository/exceptions.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/thipster/repository/github.py` & `thipster-0.20.1/thipster/repository/github.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/thipster/repository/json.py` & `thipster-0.20.1/thipster/repository/json.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/thipster/repository/local.py` & `thipster-0.20.1/thipster/repository/local.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/thipster/terraform/cdk.py` & `thipster-0.20.1/thipster/terraform/cdk.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/thipster/terraform/exceptions.py` & `thipster-0.20.1/thipster/terraform/exceptions.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.0/thipster.egg-info/PKG-INFO` & `thipster-0.20.1/thipster.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: thipster
-Version: 0.20.0
+Version: 0.20.1
 Summary: THipster is a tool dedicated to simplifying the difficulty associated with writing Terraform files. It allows users to write infrastructure as code in a simplified format, using either YAML (with JINJA) or the dedicated Thipster DSL.
 Home-page: https://github.com/THipster/THipster
 Download-URL: https://github.com/THipster/THipster.git
 Keywords: thipster,terraform,infrastructure,infrastructure-as-code,iac,generator,dsl,yaml
 Classifier: Development Status :: 1 - Planning
 Classifier: Programming Language :: Python :: 3.11
 Classifier: License :: OSI Approved :: MIT License
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: thipster Version: 0.20.0 Summary: THipster is a
+Metadata-Version: 2.1 Name: thipster Version: 0.20.1 Summary: THipster is a
 tool dedicated to simplifying the difficulty associated with writing Terraform
 files. It allows users to write infrastructure as code in a simplified format,
 using either YAML (with JINJA) or the dedicated Thipster DSL. Home-page: https:
 //github.com/THipster/THipster Download-URL: https://github.com/THipster/
 THipster.git Keywords: thipster,terraform,infrastructure,infrastructure-as-
 code,iac,generator,dsl,yaml Classifier: Development Status :: 1 - Planning
 Classifier: Programming Language :: Python :: 3.11 Classifier: License :: OSI
```

### Comparing `thipster-0.20.0/thipster.egg-info/SOURCES.txt` & `thipster-0.20.1/thipster.egg-info/SOURCES.txt`

 * *Files identical despite different names*


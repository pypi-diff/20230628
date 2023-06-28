# Comparing `tmp/thipster-0.20.1.tar.gz` & `tmp/thipster-0.21.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "thipster-0.20.1.tar", last modified: Wed Jun 28 07:44:44 2023, max compression
+gzip compressed data, was "thipster-0.21.0.tar", last modified: Wed Jun 28 14:27:12 2023, max compression
```

## Comparing `thipster-0.20.1.tar` & `thipster-0.21.0.tar`

### file list

```diff
@@ -1,81 +1,81 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:44:44.053661 thipster-0.20.1/
--rw-r--r--   0 root         (0) root         (0)     1052 2023-06-28 07:44:40.000000 thipster-0.20.1/LICENSE
--rw-r--r--   0 root         (0) root         (0)       81 2023-06-28 07:44:40.000000 thipster-0.20.1/MANIFEST.in
--rw-r--r--   0 root         (0) root         (0)     5376 2023-06-28 07:44:44.053661 thipster-0.20.1/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)     4544 2023-06-28 07:44:40.000000 thipster-0.20.1/README.md
--rw-r--r--   0 root         (0) root         (0)     1358 2023-06-28 07:44:40.000000 thipster-0.20.1/pyproject.toml
--rw-r--r--   0 root         (0) root         (0)       82 2023-06-28 07:44:40.000000 thipster-0.20.1/requirements.txt
--rw-r--r--   0 root         (0) root         (0)       38 2023-06-28 07:44:44.053661 thipster-0.20.1/setup.cfg
--rw-r--r--   0 root         (0) root         (0)     1848 2023-06-28 07:44:41.000000 thipster-0.20.1/setup.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:44:44.045661 thipster-0.20.1/tests/
--rw-r--r--   0 root         (0) root         (0)       38 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:44:44.045661 thipster-0.20.1/tests/engine/
--rw-r--r--   0 root         (0) root         (0)       29 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/engine/__init__.py
--rw-r--r--   0 root         (0) root         (0)     3478 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/engine/test_engine.py
--rw-r--r--   0 root         (0) root         (0)     6190 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/engine/test_generation.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:44:44.045661 thipster-0.20.1/tests/parser/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/parser/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:44:44.049661 thipster-0.20.1/tests/parser/dsl_parser/
--rw-r--r--   0 root         (0) root         (0)       33 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/parser/dsl_parser/__init__.py
--rw-r--r--   0 root         (0) root         (0)     1436 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/parser/dsl_parser/test_ast.py
--rw-r--r--   0 root         (0) root         (0)    17236 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/parser/dsl_parser/test_dslparser.py
--rw-r--r--   0 root         (0) root         (0)    15129 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/parser/dsl_parser/test_lexer.py
--rw-r--r--   0 root         (0) root         (0)     1028 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/parser/dsl_parser/test_token.py
--rw-r--r--   0 root         (0) root         (0)     3748 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/parser/dsl_parser/test_tokenparser.py
--rw-r--r--   0 root         (0) root         (0)     5314 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/parser/test_parsedfile.py
--rw-r--r--   0 root         (0) root         (0)     3558 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/parser/test_parserfactory.py
--rw-r--r--   0 root         (0) root         (0)     4822 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/parser/test_yamlparser.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:44:44.049661 thipster-0.20.1/tests/repository/
--rw-r--r--   0 root         (0) root         (0)       50 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/repository/__init__.py
--rw-r--r--   0 root         (0) root         (0)     1745 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/repository/test_github_repository.py
--rw-r--r--   0 root         (0) root         (0)     6375 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/repository/test_local_repository.py
--rw-r--r--   0 root         (0) root         (0)     6201 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/repository/test_resourcemodel.py
--rw-r--r--   0 root         (0) root         (0)     3577 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/test_e2e.py
--rw-r--r--   0 root         (0) root         (0)     6483 2023-06-28 07:44:40.000000 thipster-0.20.1/tests/test_tools.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:44:44.049661 thipster-0.20.1/thipster/
--rw-r--r--   0 root         (0) root         (0)      171 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:44:44.049661 thipster-0.20.1/thipster/auth/
--rw-r--r--   0 root         (0) root         (0)      215 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/auth/__init__.py
--rw-r--r--   0 root         (0) root         (0)      964 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/auth/google.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:44:44.049661 thipster-0.20.1/thipster/engine/
--rw-r--r--   0 root         (0) root         (0)      415 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/engine/__init__.py
--rw-r--r--   0 root         (0) root         (0)     5610 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/engine/engine.py
--rw-r--r--   0 root         (0) root         (0)      434 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/engine/exceptions.py
--rw-r--r--   0 root         (0) root         (0)      456 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/engine/i_auth.py
--rw-r--r--   0 root         (0) root         (0)      828 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/engine/i_parser.py
--rw-r--r--   0 root         (0) root         (0)      621 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/engine/i_repository.py
--rw-r--r--   0 root         (0) root         (0)     2166 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/engine/i_terraform.py
--rw-r--r--   0 root         (0) root         (0)     5757 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/engine/parsed_file.py
--rw-r--r--   0 root         (0) root         (0)     4646 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/engine/resource_model.py
--rw-r--r--   0 root         (0) root         (0)      719 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/helpers.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:44:44.049661 thipster-0.20.1/thipster/parser/
--rw-r--r--   0 root         (0) root         (0)      364 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/parser/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:44:44.053661 thipster-0.20.1/thipster/parser/dsl_parser/
--rw-r--r--   0 root         (0) root         (0)       30 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/parser/dsl_parser/__init__.py
--rw-r--r--   0 root         (0) root         (0)    12599 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/parser/dsl_parser/ast.py
--rw-r--r--   0 root         (0) root         (0)     5311 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/parser/dsl_parser/exceptions.py
--rw-r--r--   0 root         (0) root         (0)    14004 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/parser/dsl_parser/interpreter.py
--rw-r--r--   0 root         (0) root         (0)    14943 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/parser/dsl_parser/lexer.py
--rw-r--r--   0 root         (0) root         (0)     3283 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/parser/dsl_parser/lexer_position.py
--rw-r--r--   0 root         (0) root         (0)     2127 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/parser/dsl_parser/parser.py
--rw-r--r--   0 root         (0) root         (0)     2472 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/parser/dsl_parser/token.py
--rw-r--r--   0 root         (0) root         (0)    22021 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/parser/dsl_parser/token_parser.py
--rw-r--r--   0 root         (0) root         (0)     1209 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/parser/exceptions.py
--rw-r--r--   0 root         (0) root         (0)     2631 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/parser/parser_factory.py
--rw-r--r--   0 root         (0) root         (0)     6866 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/parser/yaml_parser.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:44:44.053661 thipster-0.20.1/thipster/repository/
--rw-r--r--   0 root         (0) root         (0)      332 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/repository/__init__.py
--rw-r--r--   0 root         (0) root         (0)      640 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/repository/exceptions.py
--rw-r--r--   0 root         (0) root         (0)     2015 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/repository/github.py
--rw-r--r--   0 root         (0) root         (0)     4821 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/repository/json.py
--rw-r--r--   0 root         (0) root         (0)     1086 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/repository/local.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:44:44.053661 thipster-0.20.1/thipster/terraform/
--rw-r--r--   0 root         (0) root         (0)      327 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/terraform/__init__.py
--rw-r--r--   0 root         (0) root         (0)    24467 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/terraform/cdk.py
--rw-r--r--   0 root         (0) root         (0)     3350 2023-06-28 07:44:40.000000 thipster-0.20.1/thipster/terraform/exceptions.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:44:44.049661 thipster-0.20.1/thipster.egg-info/
--rw-r--r--   0 root         (0) root         (0)     5376 2023-06-28 07:44:44.000000 thipster-0.20.1/thipster.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)     1957 2023-06-28 07:44:44.000000 thipster-0.20.1/thipster.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 07:44:44.000000 thipster-0.20.1/thipster.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)      388 2023-06-28 07:44:44.000000 thipster-0.20.1/thipster.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)       15 2023-06-28 07:44:44.000000 thipster-0.20.1/thipster.egg-info/top_level.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:27:12.686181 thipster-0.21.0/
+-rw-r--r--   0 root         (0) root         (0)     1052 2023-06-28 14:27:08.000000 thipster-0.21.0/LICENSE
+-rw-r--r--   0 root         (0) root         (0)       81 2023-06-28 14:27:08.000000 thipster-0.21.0/MANIFEST.in
+-rw-r--r--   0 root         (0) root         (0)     5376 2023-06-28 14:27:12.682181 thipster-0.21.0/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     4544 2023-06-28 14:27:08.000000 thipster-0.21.0/README.md
+-rw-r--r--   0 root         (0) root         (0)     1358 2023-06-28 14:27:08.000000 thipster-0.21.0/pyproject.toml
+-rw-r--r--   0 root         (0) root         (0)       82 2023-06-28 14:27:08.000000 thipster-0.21.0/requirements.txt
+-rw-r--r--   0 root         (0) root         (0)       38 2023-06-28 14:27:12.686181 thipster-0.21.0/setup.cfg
+-rw-r--r--   0 root         (0) root         (0)     1848 2023-06-28 14:27:09.000000 thipster-0.21.0/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:27:12.678181 thipster-0.21.0/tests/
+-rw-r--r--   0 root         (0) root         (0)       38 2023-06-28 14:27:08.000000 thipster-0.21.0/tests/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:27:12.678181 thipster-0.21.0/tests/engine/
+-rw-r--r--   0 root         (0) root         (0)       29 2023-06-28 14:27:08.000000 thipster-0.21.0/tests/engine/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     3478 2023-06-28 14:27:08.000000 thipster-0.21.0/tests/engine/test_engine.py
+-rw-r--r--   0 root         (0) root         (0)     6152 2023-06-28 14:27:08.000000 thipster-0.21.0/tests/engine/test_generation.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:27:12.678181 thipster-0.21.0/tests/parser/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 14:27:08.000000 thipster-0.21.0/tests/parser/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:27:12.678181 thipster-0.21.0/tests/parser/dsl_parser/
+-rw-r--r--   0 root         (0) root         (0)       33 2023-06-28 14:27:08.000000 thipster-0.21.0/tests/parser/dsl_parser/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     1436 2023-06-28 14:27:08.000000 thipster-0.21.0/tests/parser/dsl_parser/test_ast.py
+-rw-r--r--   0 root         (0) root         (0)    18012 2023-06-28 14:27:08.000000 thipster-0.21.0/tests/parser/dsl_parser/test_dslparser.py
+-rw-r--r--   0 root         (0) root         (0)    15123 2023-06-28 14:27:08.000000 thipster-0.21.0/tests/parser/dsl_parser/test_lexer.py
+-rw-r--r--   0 root         (0) root         (0)     1028 2023-06-28 14:27:08.000000 thipster-0.21.0/tests/parser/dsl_parser/test_token.py
+-rw-r--r--   0 root         (0) root         (0)     3748 2023-06-28 14:27:08.000000 thipster-0.21.0/tests/parser/dsl_parser/test_tokenparser.py
+-rw-r--r--   0 root         (0) root         (0)     5314 2023-06-28 14:27:08.000000 thipster-0.21.0/tests/parser/test_parsedfile.py
+-rw-r--r--   0 root         (0) root         (0)     3558 2023-06-28 14:27:08.000000 thipster-0.21.0/tests/parser/test_parserfactory.py
+-rw-r--r--   0 root         (0) root         (0)     4822 2023-06-28 14:27:08.000000 thipster-0.21.0/tests/parser/test_yamlparser.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:27:12.678181 thipster-0.21.0/tests/repository/
+-rw-r--r--   0 root         (0) root         (0)       50 2023-06-28 14:27:08.000000 thipster-0.21.0/tests/repository/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     1745 2023-06-28 14:27:08.000000 thipster-0.21.0/tests/repository/test_github_repository.py
+-rw-r--r--   0 root         (0) root         (0)     6375 2023-06-28 14:27:08.000000 thipster-0.21.0/tests/repository/test_local_repository.py
+-rw-r--r--   0 root         (0) root         (0)     6201 2023-06-28 14:27:08.000000 thipster-0.21.0/tests/repository/test_resourcemodel.py
+-rw-r--r--   0 root         (0) root         (0)     3577 2023-06-28 14:27:08.000000 thipster-0.21.0/tests/test_e2e.py
+-rw-r--r--   0 root         (0) root         (0)     6483 2023-06-28 14:27:08.000000 thipster-0.21.0/tests/test_tools.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:27:12.678181 thipster-0.21.0/thipster/
+-rw-r--r--   0 root         (0) root         (0)      171 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:27:12.678181 thipster-0.21.0/thipster/auth/
+-rw-r--r--   0 root         (0) root         (0)      215 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/auth/__init__.py
+-rw-r--r--   0 root         (0) root         (0)      964 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/auth/google.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:27:12.682181 thipster-0.21.0/thipster/engine/
+-rw-r--r--   0 root         (0) root         (0)      415 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/engine/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     5610 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/engine/engine.py
+-rw-r--r--   0 root         (0) root         (0)      434 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/engine/exceptions.py
+-rw-r--r--   0 root         (0) root         (0)      456 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/engine/i_auth.py
+-rw-r--r--   0 root         (0) root         (0)      828 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/engine/i_parser.py
+-rw-r--r--   0 root         (0) root         (0)      621 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/engine/i_repository.py
+-rw-r--r--   0 root         (0) root         (0)     2166 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/engine/i_terraform.py
+-rw-r--r--   0 root         (0) root         (0)     5757 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/engine/parsed_file.py
+-rw-r--r--   0 root         (0) root         (0)     4646 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/engine/resource_model.py
+-rw-r--r--   0 root         (0) root         (0)      719 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/helpers.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:27:12.682181 thipster-0.21.0/thipster/parser/
+-rw-r--r--   0 root         (0) root         (0)      364 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/parser/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:27:12.682181 thipster-0.21.0/thipster/parser/dsl_parser/
+-rw-r--r--   0 root         (0) root         (0)       30 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/parser/dsl_parser/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    12599 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/parser/dsl_parser/ast.py
+-rw-r--r--   0 root         (0) root         (0)     5311 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/parser/dsl_parser/exceptions.py
+-rw-r--r--   0 root         (0) root         (0)    14004 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/parser/dsl_parser/interpreter.py
+-rw-r--r--   0 root         (0) root         (0)    14943 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/parser/dsl_parser/lexer.py
+-rw-r--r--   0 root         (0) root         (0)     3283 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/parser/dsl_parser/lexer_position.py
+-rw-r--r--   0 root         (0) root         (0)     2127 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/parser/dsl_parser/parser.py
+-rw-r--r--   0 root         (0) root         (0)     2472 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/parser/dsl_parser/token.py
+-rw-r--r--   0 root         (0) root         (0)    23237 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/parser/dsl_parser/token_parser.py
+-rw-r--r--   0 root         (0) root         (0)     1209 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/parser/exceptions.py
+-rw-r--r--   0 root         (0) root         (0)     2631 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/parser/parser_factory.py
+-rw-r--r--   0 root         (0) root         (0)     6866 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/parser/yaml_parser.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:27:12.682181 thipster-0.21.0/thipster/repository/
+-rw-r--r--   0 root         (0) root         (0)      332 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/repository/__init__.py
+-rw-r--r--   0 root         (0) root         (0)      640 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/repository/exceptions.py
+-rw-r--r--   0 root         (0) root         (0)     2015 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/repository/github.py
+-rw-r--r--   0 root         (0) root         (0)     4821 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/repository/json.py
+-rw-r--r--   0 root         (0) root         (0)     1086 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/repository/local.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:27:12.682181 thipster-0.21.0/thipster/terraform/
+-rw-r--r--   0 root         (0) root         (0)      327 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/terraform/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    24467 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/terraform/cdk.py
+-rw-r--r--   0 root         (0) root         (0)     3350 2023-06-28 14:27:08.000000 thipster-0.21.0/thipster/terraform/exceptions.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:27:12.678181 thipster-0.21.0/thipster.egg-info/
+-rw-r--r--   0 root         (0) root         (0)     5376 2023-06-28 14:27:12.000000 thipster-0.21.0/thipster.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     1957 2023-06-28 14:27:12.000000 thipster-0.21.0/thipster.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 14:27:12.000000 thipster-0.21.0/thipster.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)      388 2023-06-28 14:27:12.000000 thipster-0.21.0/thipster.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)       15 2023-06-28 14:27:12.000000 thipster-0.21.0/thipster.egg-info/top_level.txt
```

### Comparing `thipster-0.20.1/LICENSE` & `thipster-0.21.0/LICENSE`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/PKG-INFO` & `thipster-0.21.0/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: thipster
-Version: 0.20.1
+Version: 0.21.0
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
-Metadata-Version: 2.1 Name: thipster Version: 0.20.1 Summary: THipster is a
+Metadata-Version: 2.1 Name: thipster Version: 0.21.0 Summary: THipster is a
 tool dedicated to simplifying the difficulty associated with writing Terraform
 files. It allows users to write infrastructure as code in a simplified format,
 using either YAML (with JINJA) or the dedicated Thipster DSL. Home-page: https:
 //github.com/THipster/THipster Download-URL: https://github.com/THipster/
 THipster.git Keywords: thipster,terraform,infrastructure,infrastructure-as-
 code,iac,generator,dsl,yaml Classifier: Development Status :: 1 - Planning
 Classifier: Programming Language :: Python :: 3.11 Classifier: License :: OSI
```

### Comparing `thipster-0.20.1/README.md` & `thipster-0.21.0/README.md`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/pyproject.toml` & `thipster-0.21.0/pyproject.toml`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/setup.py` & `thipster-0.21.0/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -10,15 +10,15 @@
     for req_file in Path('requirements').glob('requirements-*.txt'):
         extras_require[
             req_file.stem.removeprefix('requirements-')
         ] = req_file.read_text().splitlines()
     return extras_require
 
 
-__version__ = '0.20.1'
+__version__ = '0.21.0'
 
 with Path('requirements.txt').open() as f:
     required = f.read().splitlines()
 
 with Path('README.md').open() as rm:
     readme = rm.read()
```

### Comparing `thipster-0.20.1/tests/engine/test_engine.py` & `thipster-0.21.0/tests/engine/test_engine.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/tests/engine/test_generation.py` & `thipster-0.21.0/tests/engine/test_generation.py`

 * *Files 1% similar despite different names*

```diff
@@ -46,15 +46,15 @@
     bucket_name = f'empty-bucket-{uuid.uuid4().int}'
     clean_up = process_file(
         directory=function_name,
         file=f"""
 bucket {empty_bucket_name}:
 
 bucket {bucket_name}:
-    region: europe-west2
+  region: europe-west2
 """,
         mock_auth=True,
     )
 
     # Assertions on plan
     assert_number_of_resource_type_is('google_storage_bucket', 2)
     assert_resource_created('google_storage_bucket', empty_bucket_name)
@@ -175,22 +175,22 @@
     function_name = get_function_name()
 
     bucket_name = f'cors-bucket-{uuid.uuid4().int}'
     clean_up = process_file(
         directory=function_name,
         file=f"""
 bucket {bucket_name}:
-    cors:
-        origin:
-            - "http://example.com"
-        method:
-            - "*"
-        responseHeader:
-            - "*"
-        maxAge: 400
+  cors:
+    origin:
+      - "http://example.com"
+    method:
+      - "*"
+    responseHeader:
+      - "*"
+    maxAge: 400
 """,
         mock_auth=True,
     )
 
     # Assertions on plan
     assert_number_of_resource_type_is('google_storage_bucket', 1)
     assert_resource_created('google_storage_bucket', bucket_name)
```

### Comparing `thipster-0.20.1/tests/parser/dsl_parser/test_ast.py` & `thipster-0.21.0/tests/parser/dsl_parser/test_ast.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/tests/parser/dsl_parser/test_dslparser.py` & `thipster-0.21.0/tests/parser/dsl_parser/test_dslparser.py`

 * *Files 3% similar despite different names*

```diff
@@ -211,16 +211,16 @@
 
 
 def test_parse_dict_list_in_dict():
     """Test the parsing of a list and dict in a dict."""
     out = __test_file(
         file="""bucket my-bucket:
 \ttoto:
-\t\t aaa: val1
-\t\t bbb: val2
+\t\taaa: val1
+\t\tbbb: val2
 \ttata:
 \t\t- ccc
 \t\t- ddd
 """,
     )
 
     assert len(out.resources) == 1
@@ -234,14 +234,46 @@
     assert toto.name == 'toto'
     assert isinstance(toto._ParsedAttribute__value, pf.ParsedDict)
     tata = bucket.attributes[1]
     assert tata.name == 'tata'
     assert isinstance(tata._ParsedAttribute__value, pf.ParsedList)
 
 
+def test_parse_dict_list_in_list():
+    """Test the parsing of a list and dict in a dict."""
+    out = __test_file(
+        file="""
+bucket my-bucket:
+  toto:
+  - aaa: val1
+    bbb: val2
+  - tata:
+    - ccc
+    - ddd
+  - foo
+""",
+    )
+
+    assert len(out.resources) == 1
+
+    bucket = out.resources[0]
+    assert bucket.resource_type == 'bucket'
+    assert bucket.name == 'my-bucket'
+    assert len(bucket.attributes) == 1
+
+    toto = bucket.attributes[0]
+    assert toto.name == 'toto'
+    assert isinstance(toto._ParsedAttribute__value, pf.ParsedList)
+    tested_list = toto.value
+    assert len(tested_list) == 3
+    assert isinstance(tested_list[0], pf.ParsedDict)
+    assert isinstance(tested_list[1], pf.ParsedDict)
+    assert isinstance(tested_list[2], pf.ParsedValue)
+
+
 def test_parse_if_else():
     """Test the parsing of if else statements."""
     # IN DICT
     out = __test_file(
         file="""bucket my-bucket:
 \tregion: euw if 1 == 1 else us
 """,
@@ -447,15 +479,15 @@
 
     assert len(out.resources) == 2
 
 
 def test_parse_if_and_amount_resource():
     """Test the parsing of an amount."""
     out = __test_file(
-        file="""bucket my-bucket:  if 1==1 amount: 3
+        file="""bucket my-bucket: if 1==1 amount: 3
 \tregion: euw
 """,
     )
 
     assert len(out.resources) == 3
 
     out = __test_file(
```

### Comparing `thipster-0.20.1/tests/parser/dsl_parser/test_lexer.py` & `thipster-0.21.0/tests/parser/dsl_parser/test_lexer.py`

 * *Files 0% similar despite different names*

```diff
@@ -215,43 +215,43 @@
 
 
 def test_lex_tab():
     """Test the lexing of a tab."""
     __single_token_test('\t', TT.TAB)
 
 
-def test_lex_4_whitespaces_as_tab():
-    """Test if 4 whitespaces are considered as a tab."""
+def test_lex_2_whitespaces_as_tab():
+    """Test if 2 whitespaces are considered as a tab."""
     input_file = {
-        'file': '    \n\t',
+        'file': '  \n\t',
     }
     expected_output = [
         __get_token_string('file', 1, 1, TT.TAB),
-        __get_token_string('file', 1, 5, TT.NEWLINE),
+        __get_token_string('file', 1, 3, TT.NEWLINE),
         __get_token_string('file', 2, 1, TT.TAB),
         __get_token_string('file', 2, 2, TT.NEWLINE),
         __get_token_string('file', 3, 1, TT.EOF),
     ]
     lexer = Lexer(input_file)
     output = lexer.run()
 
     assert len(output) == len(expected_output)
     for i in range(len(expected_output)):
         assert repr(output[i]) == expected_output[i]
 
 
-def test_lex_2_4_whitespaces_as_tabs():
-    """Test if 2*4 whitespaces are considered as 2 tabs."""
+def test_lex_2_2_whitespaces_as_tabs():
+    """Test if 2*2 whitespaces are considered as 2 tabs."""
     input_file = {
-        'file': '        \n\t',
+        'file': '    \n\t',
     }
     expected_output = [
         __get_token_string('file', 1, 1, TT.TAB),
-        __get_token_string('file', 1, 5, TT.TAB),
-        __get_token_string('file', 1, 9, TT.NEWLINE),
+        __get_token_string('file', 1, 3, TT.TAB),
+        __get_token_string('file', 1, 5, TT.NEWLINE),
         __get_token_string('file', 2, 1, TT.TAB),
         __get_token_string('file', 2, 2, TT.NEWLINE),
         __get_token_string('file', 3, 1, TT.EOF),
     ]
     lexer = Lexer(input_file)
     output = lexer.run()
```

### Comparing `thipster-0.20.1/tests/parser/dsl_parser/test_token.py` & `thipster-0.21.0/tests/parser/dsl_parser/test_token.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/tests/parser/dsl_parser/test_tokenparser.py` & `thipster-0.21.0/tests/parser/dsl_parser/test_tokenparser.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/tests/parser/test_parsedfile.py` & `thipster-0.21.0/tests/parser/test_parsedfile.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/tests/parser/test_parserfactory.py` & `thipster-0.21.0/tests/parser/test_parserfactory.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/tests/parser/test_yamlparser.py` & `thipster-0.21.0/tests/parser/test_yamlparser.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/tests/repository/test_github_repository.py` & `thipster-0.21.0/tests/repository/test_github_repository.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/tests/repository/test_local_repository.py` & `thipster-0.21.0/tests/repository/test_local_repository.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/tests/repository/test_resourcemodel.py` & `thipster-0.21.0/tests/repository/test_resourcemodel.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/tests/test_e2e.py` & `thipster-0.21.0/tests/test_e2e.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/tests/test_tools.py` & `thipster-0.21.0/tests/test_tools.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/thipster/auth/google.py` & `thipster-0.21.0/thipster/auth/google.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/thipster/engine/engine.py` & `thipster-0.21.0/thipster/engine/engine.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/thipster/engine/i_parser.py` & `thipster-0.21.0/thipster/engine/i_parser.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/thipster/engine/i_repository.py` & `thipster-0.21.0/thipster/engine/i_repository.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/thipster/engine/i_terraform.py` & `thipster-0.21.0/thipster/engine/i_terraform.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/thipster/engine/parsed_file.py` & `thipster-0.21.0/thipster/engine/parsed_file.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/thipster/engine/resource_model.py` & `thipster-0.21.0/thipster/engine/resource_model.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/thipster/helpers.py` & `thipster-0.21.0/thipster/helpers.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/thipster/parser/dsl_parser/ast.py` & `thipster-0.21.0/thipster/parser/dsl_parser/ast.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/thipster/parser/dsl_parser/exceptions.py` & `thipster-0.21.0/thipster/parser/dsl_parser/exceptions.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/thipster/parser/dsl_parser/interpreter.py` & `thipster-0.21.0/thipster/parser/dsl_parser/interpreter.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/thipster/parser/dsl_parser/lexer.py` & `thipster-0.21.0/thipster/parser/dsl_parser/lexer.py`

 * *Files 1% similar despite different names*

```diff
@@ -336,19 +336,19 @@
         """
         self.__handle_current_token()
         self.__add_base_token(TT.WHITESPACE)
         self.__lexerPosition.next_column()
         self.__lexerPosition.reset_current_token()
         self.__lexerPosition.isVariable = False
         self.__lexerPosition.increment_consecutive_whitespaces()
-        if self.__lexerPosition.consecutiveWhitespaces == 4:
-            self.__lexerPosition.next_column(-4)
-            self.__rm_last_tokens(4)
+        if self.__lexerPosition.consecutiveWhitespaces == 2:
+            self.__lexerPosition.next_column(-2)
+            self.__rm_last_tokens(2)
             self.__add_base_token(TT.TAB)
-            self.__lexerPosition.next_column(4)
+            self.__lexerPosition.next_column(2)
             self.__lexerPosition.reset_consecutive_whitespaces()
             self.__lexerPosition.set_current_token_index()
 
     def __handle_newline_token(self) -> None:
         r"""Handle a NEWLINE token '\\n'."""
         if not self.__lexerPosition.isMultiLine:
             self.__handle_base_token(TT.NEWLINE)
```

### Comparing `thipster-0.20.1/thipster/parser/dsl_parser/lexer_position.py` & `thipster-0.21.0/thipster/parser/dsl_parser/lexer_position.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/thipster/parser/dsl_parser/parser.py` & `thipster-0.21.0/thipster/parser/dsl_parser/parser.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/thipster/parser/dsl_parser/token.py` & `thipster-0.21.0/thipster/parser/dsl_parser/token.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/thipster/parser/dsl_parser/token_parser.py` & `thipster-0.21.0/thipster/parser/dsl_parser/token_parser.py`

 * *Files 2% similar despite different names*

```diff
@@ -263,47 +263,56 @@
         i = indent
         try:
             next_token_type = self.__get_next_type(indent)
             while next_token_type == TT.WHITESPACE:
                 i += 1
                 next_token_type = self.__get_next_type(i)
 
-            if next_token_type == TT.STRING:
-                props = self.__get_dict(indent)
-
-            elif next_token_type == TT.MINUS:
+            if next_token_type == TT.MINUS:
                 props = self.__get_list(indent)
-
+            elif self.__get_next_type(indent - 1) == TT.MINUS:
+                props = self.__get_list(indent - 1, check_small_indent=False)
+            elif next_token_type == TT.STRING:
+                props = self.__get_dict(indent)
             else:
                 raise DSLSyntaxError(self.__next(), TT.TAB)
 
         except DSLUnexpectedEOFError as eof:
             if indent > 1:
                 raise DSLUnexpectedEOFError from eof
 
             if eof.__cause__:
                 raise DSLUnexpectedEOFError from eof.__cause__
 
             props = ast.DictNode([])
 
         return props
 
-    def __get_list(self, indent: int) -> ast.ListNode:
-        r"""Create an AST List node.
+    def __get_list(self, indent: int, check_small_indent=True) -> ast.ListNode:
+        """Create an AST List node.
 
-        Format: { "-", value, [amt_ctrl], [if_else_ctrl], "\\n"}.
+        Format: { "-", (value, [if_else_ctrl], [amt_ctrl], NEWLINE | dict) }.
         """
         list_items = []
 
         try:
-            while self.__get_tabs(indent):
-                self.__check(TT.MINUS)
+            small_indent = indent-1 if check_small_indent else indent
+            while self.__get_tabs(small_indent):
+                if not self.__check(TT.MINUS):
+                    if not check_small_indent:
+                        raise DSLSyntaxError(self.__next(), TT.TAB)
+                    small_indent = indent
+                    self.__next(TT.TAB)
+                    self.__next(TT.MINUS)
+                check_small_indent = False
+                self.__next(TT.WHITESPACE)
                 self.__get_whitespaces()
 
-                value = self.__get_value()
+                value = self.__get_dict(indent+1, no_indent_first=True)\
+                    if self.__check_dict() else self.__get_value()
                 self.__get_whitespaces()
 
                 if_else_ctrl = self.__get_if_else_ctrl()
                 self.__get_whitespaces()
                 amount_ctrl = self.__get_nb_ctrl()
                 self.__get_whitespaces()
 
@@ -326,14 +335,28 @@
                 position=self.__tokens[0].position,
                 token_type=TT.NEWLINE,
             ),
         )
 
         return ast.ListNode(list_items)
 
+    def __check_dict(self):
+        i = 0
+        next_type = self.__get_next_type(i)
+        has_amount = False
+        has_colon = False
+        while self.__get_next_type(i) is not TT.NEWLINE:
+            if next_type is TT.AMOUNT:
+                has_amount = True
+            if next_type is TT.COLON:
+                has_colon = True
+            i += 1
+            next_type = self.__get_next_type(i)
+        return has_colon and not has_amount
+
     def __get_inline_list(self) -> ast.ListNode:
         list_items = []
 
         self.__next(TT.BRACKETS_START)
         self.__get_whitespaces()
         next_token_type = self.__get_next_type()
 
@@ -355,27 +378,28 @@
                 list_items.append(self.__get_value())
                 self.__get_whitespaces()
         else:
             self.__next(TT.BRACKETS_END)
 
         return ast.ListNode(list_items)
 
-    def __get_dict(self, indent: int) -> ast.DictNode:
-        r"""Create an AST Dict node.
+    def __get_dict(self, indent: int, no_indent_first=False) -> ast.DictNode:
+        """Create an AST Dict node.
 
-        Format: { parameter, "\\n" }.
+        Format: { parameter, NEWLINE }.
         """
         parameters = []
 
         try:
-            while self.__get_tabs(indent):
+            while self.__get_tabs(indent) or no_indent_first:
                 self.__get_whitespaces()
                 parameters.append(self.__get_parameter(indent))
                 self.__get_whitespaces()
                 self.__get_newline()
+                no_indent_first = False
         except Exception as e:
             raise e
 
         self.__tokens.insert(
             0, Token(
                 position=self.__tokens[0].position,
                 token_type=TT.NEWLINE,
```

### Comparing `thipster-0.20.1/thipster/parser/exceptions.py` & `thipster-0.21.0/thipster/parser/exceptions.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/thipster/parser/parser_factory.py` & `thipster-0.21.0/thipster/parser/parser_factory.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/thipster/parser/yaml_parser.py` & `thipster-0.21.0/thipster/parser/yaml_parser.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/thipster/repository/exceptions.py` & `thipster-0.21.0/thipster/repository/exceptions.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/thipster/repository/github.py` & `thipster-0.21.0/thipster/repository/github.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/thipster/repository/json.py` & `thipster-0.21.0/thipster/repository/json.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/thipster/repository/local.py` & `thipster-0.21.0/thipster/repository/local.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/thipster/terraform/cdk.py` & `thipster-0.21.0/thipster/terraform/cdk.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/thipster/terraform/exceptions.py` & `thipster-0.21.0/thipster/terraform/exceptions.py`

 * *Files identical despite different names*

### Comparing `thipster-0.20.1/thipster.egg-info/PKG-INFO` & `thipster-0.21.0/thipster.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: thipster
-Version: 0.20.1
+Version: 0.21.0
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
-Metadata-Version: 2.1 Name: thipster Version: 0.20.1 Summary: THipster is a
+Metadata-Version: 2.1 Name: thipster Version: 0.21.0 Summary: THipster is a
 tool dedicated to simplifying the difficulty associated with writing Terraform
 files. It allows users to write infrastructure as code in a simplified format,
 using either YAML (with JINJA) or the dedicated Thipster DSL. Home-page: https:
 //github.com/THipster/THipster Download-URL: https://github.com/THipster/
 THipster.git Keywords: thipster,terraform,infrastructure,infrastructure-as-
 code,iac,generator,dsl,yaml Classifier: Development Status :: 1 - Planning
 Classifier: Programming Language :: Python :: 3.11 Classifier: License :: OSI
```

### Comparing `thipster-0.20.1/thipster.egg-info/SOURCES.txt` & `thipster-0.21.0/thipster.egg-info/SOURCES.txt`

 * *Files identical despite different names*


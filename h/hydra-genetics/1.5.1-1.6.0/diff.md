# Comparing `tmp/hydra-genetics-1.5.1.tar.gz` & `tmp/hydra-genetics-1.6.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "hydra-genetics-1.5.1.tar", last modified: Fri Jun  2 13:01:10 2023, max compression
+gzip compressed data, was "hydra-genetics-1.6.0.tar", last modified: Wed Jun 28 14:20:23 2023, max compression
```

## Comparing `hydra-genetics-1.5.1.tar` & `hydra-genetics-1.6.0.tar`

### file list

```diff
@@ -1,131 +1,131 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:10.645204 hydra-genetics-1.5.1/
--rw-r--r--   0 runner    (1001) docker     (123)    34961 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/LICENSE.md
--rw-r--r--   0 runner    (1001) docker     (123)      129 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)     2378 2023-06-02 13:01:10.645204 hydra-genetics-1.5.1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1935 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:10.645204 hydra-genetics-1.5.1/hydra_genetics/
--rw-r--r--   0 runner    (1001) docker     (123)      624 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    10139 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)      497 2023-06-02 13:01:10.645204 hydra-genetics-1.5.1/hydra_genetics/_version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:10.637204 hydra-genetics-1.5.1/hydra_genetics/commands/
--rw-r--r--   0 runner    (1001) docker     (123)       70 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/commands/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    33247 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/commands/create.py
--rw-r--r--   0 runner    (1001) docker     (123)     4801 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/commands/prep_pipeline_env.py
--rw-r--r--   0 runner    (1001) docker     (123)     7983 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/commands/references.py
--rw-r--r--   0 runner    (1001) docker     (123)       53 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/exceptions.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:10.637204 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:10.637204 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.github/
--rw-r--r--   0 runner    (1001) docker     (123)      231 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.github/CODEOWNERS
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:10.637204 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.github/ISSUE_TEMPLATE/
--rw-r--r--   0 runner    (1001) docker     (123)     1369 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.github/ISSUE_TEMPLATE/bug_report.md
--rw-r--r--   0 runner    (1001) docker     (123)      808 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.github/ISSUE_TEMPLATE/feature_request.md
--rw-r--r--   0 runner    (1001) docker     (123)      698 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.github/PULL_REQUEST_TEMPLATE.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:10.637204 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.github/linters/
--rw-r--r--   0 runner    (1001) docker     (123)       64 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.github/linters/.snakefmt.toml
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:10.637204 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.github/linters/report/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.github/linters/report/.gitkeep
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:10.641203 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.github/workflows/
--rw-r--r--   0 runner    (1001) docker     (123)      364 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.github/workflows/conventional-prs.yml
--rw-r--r--   0 runner    (1001) docker     (123)     1657 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.github/workflows/integration.yaml
--rw-r--r--   0 runner    (1001) docker     (123)      869 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.github/workflows/lint.yaml
--rw-r--r--   0 runner    (1001) docker     (123)      902 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.github/workflows/pycodestyle.yaml
--rw-r--r--   0 runner    (1001) docker     (123)      830 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.github/workflows/pytest.yaml
--rw-r--r--   0 runner    (1001) docker     (123)      317 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.github/workflows/release-please.yaml
--rw-r--r--   0 runner    (1001) docker     (123)      845 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.github/workflows/snakefmt.yaml
--rw-r--r--   0 runner    (1001) docker     (123)     1011 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.github/workflows/snakemake-dry-run.yaml
--rw-r--r--   0 runner    (1001) docker     (123)       98 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.gitignore
--rw-r--r--   0 runner    (1001) docker     (123)      441 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.readthedocs.yaml
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:10.633203 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.tests/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:10.641203 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.tests/integration/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:10.641203 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.tests/integration/config/
--rw-r--r--   0 runner    (1001) docker     (123)       46 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.tests/integration/config/config.yaml
--rw-r--r--   0 runner    (1001) docker     (123)       51 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.tests/integration/config/resources.yaml
--rw-r--r--   0 runner    (1001) docker     (123)       15 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.tests/integration/samples.tsv
--rw-r--r--   0 runner    (1001) docker     (123)      155 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.tests/integration/units.tsv
--rw-r--r--   0 runner    (1001) docker     (123)    34961 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/LICENSE.md
--rw-r--r--   0 runner    (1001) docker     (123)     3920 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:10.641203 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/config/
--rw-r--r--   0 runner    (1001) docker     (123)      174 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/config/config.yaml
--rw-r--r--   0 runner    (1001) docker     (123)      104 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/config/output_files.yaml
--rw-r--r--   0 runner    (1001) docker     (123)      109 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/config/resources.yaml
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/config/samples.tsv
--rw-r--r--   0 runner    (1001) docker     (123)      149 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/config/units.tsv
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:10.641203 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/docs/
--rw-r--r--   0 runner    (1001) docker     (123)      673 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/docs/extra.css
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:10.641203 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/docs/includes/
--rw-r--r--   0 runner    (1001) docker     (123)       29 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/docs/includes/abbreviations.md
--rw-r--r--   0 runner    (1001) docker     (123)      733 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/docs/index.md
--rw-r--r--   0 runner    (1001) docker     (123)       51 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/docs/intro.md
--rw-r--r--   0 runner    (1001) docker     (123)      218 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/docs/requirements.txt
--rw-r--r--   0 runner    (1001) docker     (123)       42 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/docs/softwares.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:10.641203 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/images/
--rw-r--r--   0 runner    (1001) docker     (123)    61275 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/images/hydragenetics.png
--rw-r--r--   0 runner    (1001) docker     (123)      862 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/mkdocs.yaml
--rw-r--r--   0 runner    (1001) docker     (123)       63 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/requirements.test.txt
--rw-r--r--   0 runner    (1001) docker     (123)      103 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/requirements.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:10.641203 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/workflow/
--rw-r--r--   0 runner    (1001) docker     (123)      378 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/workflow/Snakefile
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:10.641203 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/workflow/notebooks/
--rw-r--r--   0 runner    (1001) docker     (123)       47 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/workflow/notebooks/describe_jupyter_notebook.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:10.641203 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/workflow/rules/
--rw-r--r--   0 runner    (1001) docker     (123)     5604 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/workflow/rules/common.smk
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:10.641203 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/workflow/schemas/
--rw-r--r--   0 runner    (1001) docker     (123)      543 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/workflow/schemas/config.schema.yaml
--rw-r--r--   0 runner    (1001) docker     (123)     1352 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/workflow/schemas/output_files.schema.yaml
--rw-r--r--   0 runner    (1001) docker     (123)      706 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/workflow/schemas/resources.schema.yaml
--rw-r--r--   0 runner    (1001) docker     (123)      144 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/workflow/schemas/rules.schema.yaml
--rw-r--r--   0 runner    (1001) docker     (123)      243 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/workflow/schemas/samples.schema.yaml
--rw-r--r--   0 runner    (1001) docker     (123)      972 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/workflow/schemas/units.schema.yaml
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:10.641203 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/workflow/scripts/
--rw-r--r--   0 runner    (1001) docker     (123)      215 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/workflow/scripts/dummy.py
--rw-r--r--   0 runner    (1001) docker     (123)      259 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/pipeline-template/workflow/scripts/test_dummy.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:10.641203 hydra-genetics-1.5.1/hydra_genetics/rule-template/
--rw-r--r--   0 runner    (1001) docker     (123)     1028 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/rule-template/config.schema.yaml
--rw-r--r--   0 runner    (1001) docker     (123)     1568 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/rule-template/resources.schema.yaml
--rw-r--r--   0 runner    (1001) docker     (123)      886 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/rule-template/rules.schema.yaml
--rw-r--r--   0 runner    (1001) docker     (123)     1466 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/rule-template/skeleton_rule.smk
--rw-r--r--   0 runner    (1001) docker     (123)      384 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/rule-template/softwares.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:10.641203 hydra-genetics-1.5.1/hydra_genetics/utils/
--rw-r--r--   0 runner    (1001) docker     (123)       57 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/utils/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:10.645204 hydra-genetics-1.5.1/hydra_genetics/utils/io/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/utils/io/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1125 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/utils/io/chr.py
--rw-r--r--   0 runner    (1001) docker     (123)     2516 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/utils/io/hotspot.py
--rw-r--r--   0 runner    (1001) docker     (123)    18291 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/utils/io/hotspot_report.py
--rw-r--r--   0 runner    (1001) docker     (123)     1447 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/utils/io/multibp.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/utils/io/readers.py
--rw-r--r--   0 runner    (1001) docker     (123)     7975 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/utils/io/reference.py
--rw-r--r--   0 runner    (1001) docker     (123)     4022 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/utils/io/utils.py
--rw-r--r--   0 runner    (1001) docker     (123)     1682 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/utils/misc.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:10.645204 hydra-genetics-1.5.1/hydra_genetics/utils/models/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/utils/models/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6541 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/utils/models/hotspot.py
--rw-r--r--   0 runner    (1001) docker     (123)      403 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/utils/resources.py
--rw-r--r--   0 runner    (1001) docker     (123)     1146 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/utils/samples.py
--rw-r--r--   0 runner    (1001) docker     (123)     9346 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/hydra_genetics/utils/units.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:10.637204 hydra-genetics-1.5.1/hydra_genetics.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     2378 2023-06-02 13:01:10.000000 hydra-genetics-1.5.1/hydra_genetics.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     4578 2023-06-02 13:01:10.000000 hydra-genetics-1.5.1/hydra_genetics.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-02 13:01:10.000000 hydra-genetics-1.5.1/hydra_genetics.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       63 2023-06-02 13:01:10.000000 hydra-genetics-1.5.1/hydra_genetics.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-02 13:01:10.000000 hydra-genetics-1.5.1/hydra_genetics.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       85 2023-06-02 13:01:10.000000 hydra-genetics-1.5.1/hydra_genetics.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       21 2023-06-02 13:01:10.000000 hydra-genetics-1.5.1/hydra_genetics.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)      228 2023-06-02 13:01:10.645204 hydra-genetics-1.5.1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     1725 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:10.645204 hydra-genetics-1.5.1/tests/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/tests/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:10.645204 hydra-genetics-1.5.1/tests/utils/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/tests/utils/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:10.645204 hydra-genetics-1.5.1/tests/utils/io/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/tests/utils/io/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6042 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/tests/utils/io/test_hotspot.py
--rw-r--r--   0 runner    (1001) docker     (123)    67196 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/tests/utils/io/test_mutations_report.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:10.645204 hydra-genetics-1.5.1/tests/utils/models/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/tests/utils/models/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4678 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/tests/utils/models/test_hotspot.py
--rw-r--r--   0 runner    (1001) docker     (123)     1590 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/tests/utils/test_misc.py
--rw-r--r--   0 runner    (1001) docker     (123)      641 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/tests/utils/test_resources.py
--rw-r--r--   0 runner    (1001) docker     (123)     1489 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/tests/utils/test_samples.py
--rw-r--r--   0 runner    (1001) docker     (123)    28006 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/tests/utils/test_units.py
--rw-r--r--   0 runner    (1001) docker     (123)    80044 2023-06-02 13:01:05.000000 hydra-genetics-1.5.1/versioneer.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:23.965019 hydra-genetics-1.6.0/
+-rw-r--r--   0 runner    (1001) docker     (123)    34961 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/LICENSE.md
+-rw-r--r--   0 runner    (1001) docker     (123)      129 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)     2378 2023-06-28 14:20:23.965019 hydra-genetics-1.6.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1935 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:23.965019 hydra-genetics-1.6.0/hydra_genetics/
+-rw-r--r--   0 runner    (1001) docker     (123)      624 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10139 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      497 2023-06-28 14:20:23.965019 hydra-genetics-1.6.0/hydra_genetics/_version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:23.953019 hydra-genetics-1.6.0/hydra_genetics/commands/
+-rw-r--r--   0 runner    (1001) docker     (123)       70 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/commands/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    33247 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/commands/create.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4801 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/commands/prep_pipeline_env.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7983 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/commands/references.py
+-rw-r--r--   0 runner    (1001) docker     (123)       53 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/exceptions.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:23.953019 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:23.953019 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.github/
+-rw-r--r--   0 runner    (1001) docker     (123)      231 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.github/CODEOWNERS
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:23.953019 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.github/ISSUE_TEMPLATE/
+-rw-r--r--   0 runner    (1001) docker     (123)     1369 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.github/ISSUE_TEMPLATE/bug_report.md
+-rw-r--r--   0 runner    (1001) docker     (123)      808 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.github/ISSUE_TEMPLATE/feature_request.md
+-rw-r--r--   0 runner    (1001) docker     (123)      698 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.github/PULL_REQUEST_TEMPLATE.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:23.953019 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.github/linters/
+-rw-r--r--   0 runner    (1001) docker     (123)       64 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.github/linters/.snakefmt.toml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:23.953019 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.github/linters/report/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.github/linters/report/.gitkeep
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:23.953019 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.github/workflows/
+-rw-r--r--   0 runner    (1001) docker     (123)      364 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.github/workflows/conventional-prs.yml
+-rw-r--r--   0 runner    (1001) docker     (123)     1657 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.github/workflows/integration.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)      869 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.github/workflows/lint.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)      902 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.github/workflows/pycodestyle.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)      830 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.github/workflows/pytest.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)      317 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.github/workflows/release-please.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)      845 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.github/workflows/snakefmt.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)     1011 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.github/workflows/snakemake-dry-run.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)       98 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.gitignore
+-rw-r--r--   0 runner    (1001) docker     (123)      441 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.readthedocs.yaml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:23.941019 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.tests/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:23.953019 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.tests/integration/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:23.957019 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.tests/integration/config/
+-rw-r--r--   0 runner    (1001) docker     (123)       46 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.tests/integration/config/config.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)       51 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.tests/integration/config/resources.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)       15 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.tests/integration/samples.tsv
+-rw-r--r--   0 runner    (1001) docker     (123)      155 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.tests/integration/units.tsv
+-rw-r--r--   0 runner    (1001) docker     (123)    34961 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/LICENSE.md
+-rw-r--r--   0 runner    (1001) docker     (123)     3920 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:23.957019 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/config/
+-rw-r--r--   0 runner    (1001) docker     (123)      174 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/config/config.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)      104 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/config/output_files.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)      109 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/config/resources.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/config/samples.tsv
+-rw-r--r--   0 runner    (1001) docker     (123)      149 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/config/units.tsv
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:23.957019 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/docs/
+-rw-r--r--   0 runner    (1001) docker     (123)      673 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/docs/extra.css
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:23.957019 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/docs/includes/
+-rw-r--r--   0 runner    (1001) docker     (123)       29 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/docs/includes/abbreviations.md
+-rw-r--r--   0 runner    (1001) docker     (123)      733 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/docs/index.md
+-rw-r--r--   0 runner    (1001) docker     (123)       51 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/docs/intro.md
+-rw-r--r--   0 runner    (1001) docker     (123)      218 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/docs/requirements.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       42 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/docs/softwares.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:23.957019 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/images/
+-rw-r--r--   0 runner    (1001) docker     (123)    61275 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/images/hydragenetics.png
+-rw-r--r--   0 runner    (1001) docker     (123)      862 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/mkdocs.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)       63 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/requirements.test.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      103 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/requirements.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:23.957019 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/workflow/
+-rw-r--r--   0 runner    (1001) docker     (123)      378 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/workflow/Snakefile
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:23.957019 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/workflow/notebooks/
+-rw-r--r--   0 runner    (1001) docker     (123)       47 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/workflow/notebooks/describe_jupyter_notebook.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:23.957019 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/workflow/rules/
+-rw-r--r--   0 runner    (1001) docker     (123)     5534 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/workflow/rules/common.smk
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:23.957019 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/workflow/schemas/
+-rw-r--r--   0 runner    (1001) docker     (123)      543 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/workflow/schemas/config.schema.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)     1352 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/workflow/schemas/output_files.schema.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)      706 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/workflow/schemas/resources.schema.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)      144 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/workflow/schemas/rules.schema.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)      243 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/workflow/schemas/samples.schema.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)      972 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/workflow/schemas/units.schema.yaml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:23.961019 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/workflow/scripts/
+-rw-r--r--   0 runner    (1001) docker     (123)      215 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/workflow/scripts/dummy.py
+-rw-r--r--   0 runner    (1001) docker     (123)      259 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/pipeline-template/workflow/scripts/test_dummy.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:23.961019 hydra-genetics-1.6.0/hydra_genetics/rule-template/
+-rw-r--r--   0 runner    (1001) docker     (123)     1028 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/rule-template/config.schema.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)     1568 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/rule-template/resources.schema.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)      886 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/rule-template/rules.schema.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)     1466 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/rule-template/skeleton_rule.smk
+-rw-r--r--   0 runner    (1001) docker     (123)      384 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/rule-template/softwares.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:23.961019 hydra-genetics-1.6.0/hydra_genetics/utils/
+-rw-r--r--   0 runner    (1001) docker     (123)       57 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/utils/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:23.961019 hydra-genetics-1.6.0/hydra_genetics/utils/io/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/utils/io/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1125 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/utils/io/chr.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2516 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/utils/io/hotspot.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18291 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/utils/io/hotspot_report.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1447 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/utils/io/multibp.py
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/utils/io/readers.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8149 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/utils/io/reference.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4022 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/utils/io/utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1645 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/utils/misc.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:23.961019 hydra-genetics-1.6.0/hydra_genetics/utils/models/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/utils/models/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6541 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/utils/models/hotspot.py
+-rw-r--r--   0 runner    (1001) docker     (123)      403 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/utils/resources.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1146 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/utils/samples.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9346 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/hydra_genetics/utils/units.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:23.949019 hydra-genetics-1.6.0/hydra_genetics.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     2378 2023-06-28 14:20:23.000000 hydra-genetics-1.6.0/hydra_genetics.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     4578 2023-06-28 14:20:23.000000 hydra-genetics-1.6.0/hydra_genetics.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 14:20:23.000000 hydra-genetics-1.6.0/hydra_genetics.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       63 2023-06-28 14:20:23.000000 hydra-genetics-1.6.0/hydra_genetics.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 14:20:23.000000 hydra-genetics-1.6.0/hydra_genetics.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       85 2023-06-28 14:20:23.000000 hydra-genetics-1.6.0/hydra_genetics.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       21 2023-06-28 14:20:23.000000 hydra-genetics-1.6.0/hydra_genetics.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      228 2023-06-28 14:20:23.965019 hydra-genetics-1.6.0/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1725 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:23.961019 hydra-genetics-1.6.0/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/tests/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:23.961019 hydra-genetics-1.6.0/tests/utils/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/tests/utils/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:23.961019 hydra-genetics-1.6.0/tests/utils/io/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/tests/utils/io/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6042 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/tests/utils/io/test_hotspot.py
+-rw-r--r--   0 runner    (1001) docker     (123)    67196 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/tests/utils/io/test_mutations_report.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:23.961019 hydra-genetics-1.6.0/tests/utils/models/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/tests/utils/models/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4678 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/tests/utils/models/test_hotspot.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1590 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/tests/utils/test_misc.py
+-rw-r--r--   0 runner    (1001) docker     (123)      641 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/tests/utils/test_resources.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1489 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/tests/utils/test_samples.py
+-rw-r--r--   0 runner    (1001) docker     (123)    28006 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/tests/utils/test_units.py
+-rw-r--r--   0 runner    (1001) docker     (123)    80044 2023-06-28 14:20:18.000000 hydra-genetics-1.6.0/versioneer.py
```

### Comparing `hydra-genetics-1.5.1/LICENSE.md` & `hydra-genetics-1.6.0/LICENSE.md`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/PKG-INFO` & `hydra-genetics-1.6.0/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: hydra-genetics
-Version: 1.5.1
+Version: 1.6.0
 Summary: Helper tools for use with hydra-genetics pipelines.
 Home-page: https://github.com/hydra-genetics/tools
 Author: Patrik Smeds
 Author-email: patrik.smeds@scilifelab.uu.se
 License: GPL-3
 Keywords: hydra-genetics,snakemake,bioinformatics,workflow,pipeline,clinical,biology,sequencing,NGS,next generation sequencing
 Description-Content-Type: text/markdown
```

### Comparing `hydra-genetics-1.5.1/README.md` & `hydra-genetics-1.6.0/README.md`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/__init__.py` & `hydra-genetics-1.6.0/hydra_genetics/__init__.py`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/__main__.py` & `hydra-genetics-1.6.0/hydra_genetics/__main__.py`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/commands/create.py` & `hydra-genetics-1.6.0/hydra_genetics/commands/create.py`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/commands/prep_pipeline_env.py` & `hydra-genetics-1.6.0/hydra_genetics/commands/prep_pipeline_env.py`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/commands/references.py` & `hydra-genetics-1.6.0/hydra_genetics/commands/references.py`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.github/ISSUE_TEMPLATE/bug_report.md` & `hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.github/ISSUE_TEMPLATE/bug_report.md`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.github/ISSUE_TEMPLATE/feature_request.md` & `hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.github/ISSUE_TEMPLATE/feature_request.md`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.github/PULL_REQUEST_TEMPLATE.md` & `hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.github/PULL_REQUEST_TEMPLATE.md`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.github/workflows/integration.yaml` & `hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.github/workflows/integration.yaml`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.github/workflows/lint.yaml` & `hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.github/workflows/lint.yaml`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.github/workflows/pycodestyle.yaml` & `hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.github/workflows/pycodestyle.yaml`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.github/workflows/pytest.yaml` & `hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.github/workflows/pytest.yaml`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.github/workflows/snakefmt.yaml` & `hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.github/workflows/snakefmt.yaml`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/pipeline-template/.github/workflows/snakemake-dry-run.yaml` & `hydra-genetics-1.6.0/hydra_genetics/pipeline-template/.github/workflows/snakemake-dry-run.yaml`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/pipeline-template/LICENSE.md` & `hydra-genetics-1.6.0/hydra_genetics/pipeline-template/LICENSE.md`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/pipeline-template/README.md` & `hydra-genetics-1.6.0/hydra_genetics/pipeline-template/README.md`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/pipeline-template/docs/extra.css` & `hydra-genetics-1.6.0/hydra_genetics/pipeline-template/docs/extra.css`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/pipeline-template/docs/index.md` & `hydra-genetics-1.6.0/hydra_genetics/pipeline-template/docs/index.md`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/pipeline-template/images/hydragenetics.png` & `hydra-genetics-1.6.0/hydra_genetics/pipeline-template/images/hydragenetics.png`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/pipeline-template/mkdocs.yaml` & `hydra-genetics-1.6.0/hydra_genetics/pipeline-template/mkdocs.yaml`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/pipeline-template/workflow/rules/common.smk` & `hydra-genetics-1.6.0/hydra_genetics/pipeline-template/workflow/rules/common.smk`

 * *Files 2% similar despite different names*

```diff
@@ -120,15 +120,14 @@
         rule_code = "\n".join(
             [
                 f'@workflow.rule(name="{rule_name}")',
                 f'@workflow.input("{input_file}")',
                 f'@workflow.output("{output_file}")',
                 f'@workflow.log("logs/{rule_name}_{output_file.name}.log")',
                 f'@workflow.container("{copy_container}")',
-                '@workflow.conda("../envs/copy_results_files.yaml")',
                 f'@workflow.resources(time="{time}", threads={threads}, mem_mb="{mem_mb}", '
                 f'mem_per_cpu={mem_per_cpu}, partition="{partition}")',
                 f'@workflow.shellcmd("{copy_container}")',
                 "@workflow.run\n",
                 f"def __rule_{rule_name}(input, output, params, wildcards, threads, resources, "
                 "log, version, rule, conda_env, container_img, singularity_args, use_singularity, "
                 "env_modules, bench_record, jobid, is_shell, bench_iteration, cleanup_scripts, "
```

### Comparing `hydra-genetics-1.5.1/hydra_genetics/pipeline-template/workflow/schemas/config.schema.yaml` & `hydra-genetics-1.6.0/hydra_genetics/pipeline-template/workflow/schemas/config.schema.yaml`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/pipeline-template/workflow/schemas/output_files.schema.yaml` & `hydra-genetics-1.6.0/hydra_genetics/pipeline-template/workflow/schemas/output_files.schema.yaml`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/pipeline-template/workflow/schemas/resources.schema.yaml` & `hydra-genetics-1.6.0/hydra_genetics/pipeline-template/workflow/schemas/resources.schema.yaml`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/pipeline-template/workflow/schemas/units.schema.yaml` & `hydra-genetics-1.6.0/hydra_genetics/pipeline-template/workflow/schemas/units.schema.yaml`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/rule-template/config.schema.yaml` & `hydra-genetics-1.6.0/hydra_genetics/rule-template/config.schema.yaml`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/rule-template/resources.schema.yaml` & `hydra-genetics-1.6.0/hydra_genetics/rule-template/resources.schema.yaml`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/rule-template/rules.schema.yaml` & `hydra-genetics-1.6.0/hydra_genetics/rule-template/rules.schema.yaml`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/rule-template/skeleton_rule.smk` & `hydra-genetics-1.6.0/hydra_genetics/rule-template/skeleton_rule.smk`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/utils/io/chr.py` & `hydra-genetics-1.6.0/hydra_genetics/utils/io/chr.py`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/utils/io/hotspot.py` & `hydra-genetics-1.6.0/hydra_genetics/utils/io/hotspot.py`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/utils/io/hotspot_report.py` & `hydra-genetics-1.6.0/hydra_genetics/utils/io/hotspot_report.py`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/utils/io/multibp.py` & `hydra-genetics-1.6.0/hydra_genetics/utils/io/multibp.py`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/utils/io/reference.py` & `hydra-genetics-1.6.0/hydra_genetics/utils/io/reference.py`

 * *Files 5% similar despite different names*

```diff
@@ -26,14 +26,17 @@
             (list, list, list, int, int, int): (fetched files, failed files, skipped files,
                                                 counter fetched files, counter failed files , counter skipped files)
     '''
     for k in validation_data:
         # If validation entry
         if "path" in validation_data[k]:
             file_path = os.path.join(output_dir, validation_data[k]['path'])
+            if 'url' not in validation_data[k]:
+                logging.debug(f"File {file_path} contains no url entry, i.e will not be retrieved!")
+                continue
             url = validation_data[k]['url']
             fetch_file = False
             if force and os.path.isfile(file_path):
                 logging.debug(f"Overwriting {file_path}")
                 fetch_file = True
             elif not os.path.isfile(file_path):
                 fetch_file = True
```

### Comparing `hydra-genetics-1.5.1/hydra_genetics/utils/io/utils.py` & `hydra-genetics-1.6.0/hydra_genetics/utils/io/utils.py`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/utils/misc.py` & `hydra-genetics-1.6.0/hydra_genetics/utils/misc.py`

 * *Files 4% similar despite different names*

```diff
@@ -15,15 +15,15 @@
             repo_path_v2 = os.path.join(config['hydra_local_path'], os.sep.join(repo.split(os.sep)[1:]))
             if not os.path.exists(repo_path_v2):
                 raise FileNotFoundError(f"Repo folder {repo_path} or {repo_path_v2} doesn't exist!")
             else:
                 repo_path = repo_path_v2
         if not os.path.isdir(repo_path):
             raise FileNotFoundError(f"{repo_path} isn't a folder!")
-        return LocalGitFile(os.path.join(config['hydra_local_path'], repo), path=path, tag=tag)
+        return LocalGitFile(repo_path, path=path, tag=tag)
     else:
         return GithubFile(repo, path=path, tag=tag)
 
 
 def merge(dict1, dict2):
     ''' Return a new dictionary by merging two dictionaries recursively. '''
```

### Comparing `hydra-genetics-1.5.1/hydra_genetics/utils/models/hotspot.py` & `hydra-genetics-1.6.0/hydra_genetics/utils/models/hotspot.py`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/utils/samples.py` & `hydra-genetics-1.6.0/hydra_genetics/utils/samples.py`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics/utils/units.py` & `hydra-genetics-1.6.0/hydra_genetics/utils/units.py`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/hydra_genetics.egg-info/PKG-INFO` & `hydra-genetics-1.6.0/hydra_genetics.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: hydra-genetics
-Version: 1.5.1
+Version: 1.6.0
 Summary: Helper tools for use with hydra-genetics pipelines.
 Home-page: https://github.com/hydra-genetics/tools
 Author: Patrik Smeds
 Author-email: patrik.smeds@scilifelab.uu.se
 License: GPL-3
 Keywords: hydra-genetics,snakemake,bioinformatics,workflow,pipeline,clinical,biology,sequencing,NGS,next generation sequencing
 Description-Content-Type: text/markdown
```

### Comparing `hydra-genetics-1.5.1/hydra_genetics.egg-info/SOURCES.txt` & `hydra-genetics-1.6.0/hydra_genetics.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/setup.py` & `hydra-genetics-1.6.0/setup.py`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/tests/utils/io/test_hotspot.py` & `hydra-genetics-1.6.0/tests/utils/io/test_hotspot.py`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/tests/utils/io/test_mutations_report.py` & `hydra-genetics-1.6.0/tests/utils/io/test_mutations_report.py`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/tests/utils/models/test_hotspot.py` & `hydra-genetics-1.6.0/tests/utils/models/test_hotspot.py`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/tests/utils/test_misc.py` & `hydra-genetics-1.6.0/tests/utils/test_misc.py`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/tests/utils/test_resources.py` & `hydra-genetics-1.6.0/tests/utils/test_resources.py`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/tests/utils/test_samples.py` & `hydra-genetics-1.6.0/tests/utils/test_samples.py`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/tests/utils/test_units.py` & `hydra-genetics-1.6.0/tests/utils/test_units.py`

 * *Files identical despite different names*

### Comparing `hydra-genetics-1.5.1/versioneer.py` & `hydra-genetics-1.6.0/versioneer.py`

 * *Files identical despite different names*


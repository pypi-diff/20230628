# Comparing `tmp/dpdispatcher-0.5.6.tar.gz` & `tmp/dpdispatcher-0.5.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dpdispatcher-0.5.6.tar", last modified: Thu Apr 13 04:21:20 2023, max compression
+gzip compressed data, was "dpdispatcher-0.5.7.tar", last modified: Tue Jun 27 23:33:24 2023, max compression
```

## Comparing `dpdispatcher-0.5.6.tar` & `dpdispatcher-0.5.7.tar`

### file list

```diff
@@ -1,297 +1,298 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.703903 dpdispatcher-0.5.6/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.671903 dpdispatcher-0.5.6/.github/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.679903 dpdispatcher-0.5.6/.github/workflows/
--rw-r--r--   0 runner    (1001) docker     (123)      847 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/.github/workflows/ci-docker.yml
--rw-r--r--   0 runner    (1001) docker     (123)      308 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/.github/workflows/machines.yml
--rw-r--r--   0 runner    (1001) docker     (123)      322 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/.github/workflows/mirror_gitee.yml
--rw-r--r--   0 runner    (1001) docker     (123)      338 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/.github/workflows/publish_conda.yml
--rw-r--r--   0 runner    (1001) docker     (123)      310 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/.github/workflows/pyright.yml
--rw-r--r--   0 runner    (1001) docker     (123)      211 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/.github/workflows/release.yml
--rw-r--r--   0 runner    (1001) docker     (123)      948 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/.github/workflows/test.yml
--rw-r--r--   0 runner    (1001) docker     (123)      403 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/.gitignore
--rw-r--r--   0 runner    (1001) docker     (123)      995 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/.pre-commit-config.yaml
--rw-r--r--   0 runner    (1001) docker     (123)      542 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/CONTRIBUTING.md
--rw-r--r--   0 runner    (1001) docker     (123)       87 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/Dockerfile
--rw-r--r--   0 runner    (1001) docker     (123)     7652 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    10941 2023-04-13 04:21:20.703903 dpdispatcher-0.5.6/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      855 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.679903 dpdispatcher-0.5.6/ci/
--rw-r--r--   0 runner    (1001) docker     (123)     1573 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/ci/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)      342 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/ci/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.679903 dpdispatcher-0.5.6/ci/pbs/
--rw-r--r--   0 runner    (1001) docker     (123)     1192 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/ci/pbs/docker-compose.yml
--rwxr-xr-x   0 runner    (1001) docker     (123)      253 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/ci/pbs/start-pbs.sh
--rwxr-xr-x   0 runner    (1001) docker     (123)      665 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/ci/pbs.sh
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.679903 dpdispatcher-0.5.6/ci/slurm/
--rw-r--r--   0 runner    (1001) docker     (123)     2282 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/ci/slurm/docker-compose.yml
--rw-r--r--   0 runner    (1001) docker     (123)      152 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/ci/slurm/register_cluster.sh
--rwxr-xr-x   0 runner    (1001) docker     (123)      662 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/ci/slurm/start-slurm.sh
--rwxr-xr-x   0 runner    (1001) docker     (123)      423 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/ci/slurm.sh
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.679903 dpdispatcher-0.5.6/ci/ssh/
--rw-r--r--   0 runner    (1001) docker     (123)      537 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/ci/ssh/docker-compose.yml
--rwxr-xr-x   0 runner    (1001) docker     (123)      302 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/ci/ssh/start-ssh.sh
--rwxr-xr-x   0 runner    (1001) docker     (123)      411 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/ci/ssh.sh
--rwxr-xr-x   0 runner    (1001) docker     (123)      586 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/ci/ssh_rsync.sh
--rw-r--r--   0 runner    (1001) docker     (123)      142 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/codecov.yml
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.679903 dpdispatcher-0.5.6/conda/
--rw-r--r--   0 runner    (1001) docker     (123)       80 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/conda/conda_build_config.yaml
--rw-r--r--   0 runner    (1001) docker     (123)      906 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/conda/meta.yaml
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.683903 dpdispatcher-0.5.6/doc/
--rw-r--r--   0 runner    (1001) docker     (123)      524 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/doc/.gitignore
--rw-r--r--   0 runner    (1001) docker     (123)      634 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/doc/Makefile
--rw-r--r--   0 runner    (1001) docker     (123)     3142 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/doc/batch.md
--rw-r--r--   0 runner    (1001) docker     (123)     2931 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/doc/conf.py
--rw-r--r--   0 runner    (1001) docker     (123)     2024 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/doc/context.md
--rw-r--r--   0 runner    (1001) docker     (123)       43 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/doc/credits.rst
--rw-r--r--   0 runner    (1001) docker     (123)     5037 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/doc/dpdispatcher_on_yarn.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.683903 dpdispatcher-0.5.6/doc/examples/
--rw-r--r--   0 runner    (1001) docker     (123)     1531 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/doc/examples/expanse.md
--rw-r--r--   0 runner    (1001) docker     (123)      500 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/doc/examples/g16.md
--rw-r--r--   0 runner    (1001) docker     (123)      947 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/doc/examples/shell.md
--rw-r--r--   0 runner    (1001) docker     (123)     4300 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/doc/getting-started.md
--rw-r--r--   0 runner    (1001) docker     (123)     1026 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/doc/index.rst
--rw-r--r--   0 runner    (1001) docker     (123)      118 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/doc/install.md
--rw-r--r--   0 runner    (1001) docker     (123)      398 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/doc/machine.rst
--rw-r--r--   0 runner    (1001) docker     (123)      795 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/doc/make.bat
--rw-r--r--   0 runner    (1001) docker     (123)        8 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/doc/requirements.txt
--rw-r--r--   0 runner    (1001) docker     (123)      408 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/doc/resources.rst
--rw-r--r--   0 runner    (1001) docker     (123)      389 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/doc/task.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.683903 dpdispatcher-0.5.6/dpdispatcher/
--rw-r--r--   0 runner    (1001) docker     (123)      233 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/dpdispatcher/JobStatus.py
--rw-r--r--   0 runner    (1001) docker     (123)     2866 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/dpdispatcher/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      160 2023-04-13 04:21:20.000000 dpdispatcher-0.5.6/dpdispatcher/_version.py
--rw-r--r--   0 runner    (1001) docker     (123)      188 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/dpdispatcher/arginfo.py
--rw-r--r--   0 runner    (1001) docker     (123)     3690 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/dpdispatcher/base_context.py
--rw-r--r--   0 runner    (1001) docker     (123)     6941 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/dpdispatcher/distributed_shell.py
--rw-r--r--   0 runner    (1001) docker     (123)     9758 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/dpdispatcher/dp_cloud_server.py
--rw-r--r--   0 runner    (1001) docker     (123)    11300 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/dpdispatcher/dp_cloud_server_context.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.687903 dpdispatcher-0.5.6/dpdispatcher/dpcloudserver/
--rw-r--r--   0 runner    (1001) docker     (123)       49 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/dpdispatcher/dpcloudserver/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    11154 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/dpdispatcher/dpcloudserver/client.py
--rw-r--r--   0 runner    (1001) docker     (123)      635 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/dpdispatcher/dpcloudserver/config.py
--rw-r--r--   0 runner    (1001) docker     (123)      721 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/dpdispatcher/dpcloudserver/retcode.py
--rw-r--r--   0 runner    (1001) docker     (123)     2932 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/dpdispatcher/dpcloudserver/temp_test.py
--rw-r--r--   0 runner    (1001) docker     (123)     2611 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/dpdispatcher/dpcloudserver/zip_file.py
--rw-r--r--   0 runner    (1001) docker     (123)       94 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/dpdispatcher/dpdisp.py
--rw-r--r--   0 runner    (1001) docker     (123)     6047 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/dpdispatcher/hdfs_cli.py
--rw-r--r--   0 runner    (1001) docker     (123)     8980 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/dpdispatcher/hdfs_context.py
--rw-r--r--   0 runner    (1001) docker     (123)     5775 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/dpdispatcher/lazy_local_context.py
--rw-r--r--   0 runner    (1001) docker     (123)    11855 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/dpdispatcher/local_context.py
--rw-r--r--   0 runner    (1001) docker     (123)     7553 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/dpdispatcher/lsf.py
--rw-r--r--   0 runner    (1001) docker     (123)    14949 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/dpdispatcher/machine.py
--rw-r--r--   0 runner    (1001) docker     (123)     6057 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/dpdispatcher/pbs.py
--rw-r--r--   0 runner    (1001) docker     (123)     3843 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/dpdispatcher/shell.py
--rw-r--r--   0 runner    (1001) docker     (123)    12886 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/dpdispatcher/slurm.py
--rw-r--r--   0 runner    (1001) docker     (123)    34670 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/dpdispatcher/ssh_context.py
--rw-r--r--   0 runner    (1001) docker     (123)    41960 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/dpdispatcher/submission.py
--rw-r--r--   0 runner    (1001) docker     (123)     5035 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/dpdispatcher/utils.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.687903 dpdispatcher-0.5.6/dpdispatcher.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    10941 2023-04-13 04:21:20.000000 dpdispatcher-0.5.6/dpdispatcher.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     7121 2023-04-13 04:21:20.000000 dpdispatcher-0.5.6/dpdispatcher.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-04-13 04:21:20.000000 dpdispatcher-0.5.6/dpdispatcher.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       52 2023-04-13 04:21:20.000000 dpdispatcher-0.5.6/dpdispatcher.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)      224 2023-04-13 04:21:20.000000 dpdispatcher-0.5.6/dpdispatcher.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       13 2023-04-13 04:21:20.000000 dpdispatcher-0.5.6/dpdispatcher.egg-info/top_level.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.671903 dpdispatcher-0.5.6/examples/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.687903 dpdispatcher-0.5.6/examples/machine/
--rw-r--r--   0 runner    (1001) docker     (123)      311 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/examples/machine/expanse.json
--rw-r--r--   0 runner    (1001) docker     (123)       92 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/examples/machine/lazy_local.json
--rw-r--r--   0 runner    (1001) docker     (123)      270 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/examples/machine/mandu.json
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.687903 dpdispatcher-0.5.6/examples/resources/
--rw-r--r--   0 runner    (1001) docker     (123)      602 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/examples/resources/expanse_cpu.json
--rw-r--r--   0 runner    (1001) docker     (123)      370 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/examples/resources/mandu.json
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.687903 dpdispatcher-0.5.6/examples/task/
--rw-r--r--   0 runner    (1001) docker     (123)      284 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/examples/task/deepmd-kit.json
--rw-r--r--   0 runner    (1001) docker     (123)      165 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/examples/task/g16.json
--rw-r--r--   0 runner    (1001) docker     (123)     3023 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/pyproject.toml
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.687903 dpdispatcher-0.5.6/scripts/
--rw-r--r--   0 runner    (1001) docker     (123)      648 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/scripts/script_gen_dargs_docs.py
--rw-r--r--   0 runner    (1001) docker     (123)      508 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/scripts/script_gen_dargs_json.py
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-04-13 04:21:20.703903 dpdispatcher-0.5.6/setup.cfg
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.691903 dpdispatcher-0.5.6/tests/
--rw-r--r--   0 runner    (1001) docker     (123)        7 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/.gitignore
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      133 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/batch.json
--rw-r--r--   0 runner    (1001) docker     (123)     1838 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/context.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     1843 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/debug_test_class_submission_init.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     3228 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/devel_test_ali_ehpc.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     2669 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/devel_test_dp_cloud_server.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     1752 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/devel_test_lazy_ali_ehpc.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     1398 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/devel_test_lsf.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     2357 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/devel_test_shell.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     2673 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/devel_test_slurm.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     2629 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/devel_test_ssh_ali_ehpc.py
--rw-r--r--   0 runner    (1001) docker     (123)      299 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/graph.pb
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.695903 dpdispatcher-0.5.6/tests/jsons/
--rw-r--r--   0 runner    (1001) docker     (123)     1451 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/jsons/job.json
--rw-r--r--   0 runner    (1001) docker     (123)      345 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/jsons/machine.json
--rw-r--r--   0 runner    (1001) docker     (123)      489 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/jsons/machine_ali_ehpc.json
--rw-r--r--   0 runner    (1001) docker     (123)      845 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/jsons/machine_center.json
--rw-r--r--   0 runner    (1001) docker     (123)      695 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/jsons/machine_diffenert.json
--rw-r--r--   0 runner    (1001) docker     (123)     1202 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/jsons/machine_dp_cloud_server.json
--rw-r--r--   0 runner    (1001) docker     (123)      497 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/jsons/machine_if_cuda_multi_devices.json
--rw-r--r--   0 runner    (1001) docker     (123)     1173 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/jsons/machine_lazy_local_lsf.json
--rw-r--r--   0 runner    (1001) docker     (123)      745 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/jsons/machine_lazy_local_slurm.json
--rw-r--r--   0 runner    (1001) docker     (123)      307 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/jsons/machine_lazylocal_shell.json
--rw-r--r--   0 runner    (1001) docker     (123)      352 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/jsons/machine_local_shell.json
--rw-r--r--   0 runner    (1001) docker     (123)     1108 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/jsons/machine_lsf.json
--rw-r--r--   0 runner    (1001) docker     (123)      879 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/jsons/machine_slurm.json
--rw-r--r--   0 runner    (1001) docker     (123)     1071 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/jsons/machine_yarn.json
--rw-r--r--   0 runner    (1001) docker     (123)      357 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/jsons/resources.json
--rw-r--r--   0 runner    (1001) docker     (123)     4505 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/jsons/submission.json
--rw-r--r--   0 runner    (1001) docker     (123)      239 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/jsons/task.json
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.695903 dpdispatcher-0.5.6/tests/lsf/
--rw-r--r--   0 runner    (1001) docker     (123)      684 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/lsf/context.py
--rw-r--r--   0 runner    (1001) docker     (123)     1581 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/lsf/test_dispatcher.py
--rw-r--r--   0 runner    (1001) docker     (123)     7600 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/lsf/test_lsf_local.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.695903 dpdispatcher-0.5.6/tests/old/
--rw-r--r--   0 runner    (1001) docker     (123)     1286 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/old/test_dispatcher_utils.py
--rw-r--r--   0 runner    (1001) docker     (123)     7968 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/old/test_lazy_local_context.py
--rw-r--r--   0 runner    (1001) docker     (123)    15772 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/old/test_local_context.py
--rw-r--r--   0 runner    (1001) docker     (123)      390 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/old/test_local_session.py
--rw-r--r--   0 runner    (1001) docker     (123)    10956 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/old/test_ssh_context.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.695903 dpdispatcher-0.5.6/tests/pbs/
--rw-r--r--   0 runner    (1001) docker     (123)      684 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/pbs/context.py
--rw-r--r--   0 runner    (1001) docker     (123)     1577 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/pbs/test_dispatcher.py
--rw-r--r--   0 runner    (1001) docker     (123)     5652 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/pbs/test_pbs_local.py
--rw-r--r--   0 runner    (1001) docker     (123)     5188 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/sample_class.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     1074 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/script_gen_json.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.695903 dpdispatcher-0.5.6/tests/shell/
--rw-r--r--   0 runner    (1001) docker     (123)      684 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/shell/context.py
--rw-r--r--   0 runner    (1001) docker     (123)     1532 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/shell/test_dispatcher.py
--rw-r--r--   0 runner    (1001) docker     (123)     8869 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/shell/test_shell_local.py
--rw-r--r--   0 runner    (1001) docker     (123)     7147 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/shell/test_shell_ssh.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.695903 dpdispatcher-0.5.6/tests/slurm/
--rw-r--r--   0 runner    (1001) docker     (123)      684 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/slurm/context.py
--rw-r--r--   0 runner    (1001) docker     (123)     1743 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/slurm/test_dispatcher.py
--rw-r--r--   0 runner    (1001) docker     (123)     1730 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/slurm/test_dispatcher_lazy_local.py
--rw-r--r--   0 runner    (1001) docker     (123)     8182 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/slurm/test_slurm_lazy_local.py
--rw-r--r--   0 runner    (1001) docker     (123)     7811 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/slurm/test_slurm_local.py
--rw-r--r--   0 runner    (1001) docker     (123)     8114 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/slurm/test_slurm_ssh.py
--rw-r--r--   0 runner    (1001) docker     (123)       55 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/slurm_test.env
--rw-r--r--   0 runner    (1001) docker     (123)     2629 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_argcheck.py
--rw-r--r--   0 runner    (1001) docker     (123)     1677 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_class_job.py
--rw-r--r--   0 runner    (1001) docker     (123)      697 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_class_machine.py
--rw-r--r--   0 runner    (1001) docker     (123)     6837 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_class_machine_dispatch.py
--rw-r--r--   0 runner    (1001) docker     (123)     1537 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_class_resources.py
--rw-r--r--   0 runner    (1001) docker     (123)     3790 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_class_submission.py
--rw-r--r--   0 runner    (1001) docker     (123)     2306 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_class_submission_init.py
--rw-r--r--   0 runner    (1001) docker     (123)     1260 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_class_task.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.671903 dpdispatcher-0.5.6/tests/test_context_dir/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.695903 dpdispatcher-0.5.6/tests/test_context_dir/0_md/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.695903 dpdispatcher-0.5.6/tests/test_context_dir/0_md/bct-1/
--rw-r--r--   0 runner    (1001) docker     (123)      340 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_context_dir/0_md/bct-1/conf.lmp
--rw-r--r--   0 runner    (1001) docker     (123)      842 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_context_dir/0_md/bct-1/input.lammps
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.695903 dpdispatcher-0.5.6/tests/test_context_dir/0_md/bct-1/some_dir/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_context_dir/0_md/bct-1/some_dir/some_file
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.695903 dpdispatcher-0.5.6/tests/test_context_dir/0_md/bct-2/
--rw-r--r--   0 runner    (1001) docker     (123)      340 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_context_dir/0_md/bct-2/conf.lmp
--rw-r--r--   0 runner    (1001) docker     (123)      842 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_context_dir/0_md/bct-2/input.lammps
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.695903 dpdispatcher-0.5.6/tests/test_context_dir/0_md/bct-3/
--rw-r--r--   0 runner    (1001) docker     (123)      340 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_context_dir/0_md/bct-3/conf.lmp
--rw-r--r--   0 runner    (1001) docker     (123)      842 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_context_dir/0_md/bct-3/input.lammps
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.699903 dpdispatcher-0.5.6/tests/test_context_dir/0_md/bct-4/
--rw-r--r--   0 runner    (1001) docker     (123)      340 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_context_dir/0_md/bct-4/conf.lmp
--rw-r--r--   0 runner    (1001) docker     (123)      842 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_context_dir/0_md/bct-4/input.lammps
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.699903 dpdispatcher-0.5.6/tests/test_context_dir/0_md/dir with space/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_context_dir/0_md/dir with space/file with space
--rw-r--r--   0 runner    (1001) docker     (123)      299 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_context_dir/0_md/graph.pb
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.699903 dpdispatcher-0.5.6/tests/test_context_dir/0_md/some_dir/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_context_dir/0_md/some_dir/some_file
--rw-r--r--   0 runner    (1001) docker     (123)     1402 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_group_size.py
--rw-r--r--   0 runner    (1001) docker     (123)     2859 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_hdfs_context.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.675903 dpdispatcher-0.5.6/tests/test_hdfs_dir/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.699903 dpdispatcher-0.5.6/tests/test_hdfs_dir/0_md/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.699903 dpdispatcher-0.5.6/tests/test_hdfs_dir/0_md/bct-1/
--rw-r--r--   0 runner    (1001) docker     (123)      340 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_hdfs_dir/0_md/bct-1/conf.lmp
--rw-r--r--   0 runner    (1001) docker     (123)      842 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_hdfs_dir/0_md/bct-1/input.lammps
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.699903 dpdispatcher-0.5.6/tests/test_hdfs_dir/0_md/bct-2/
--rw-r--r--   0 runner    (1001) docker     (123)      340 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_hdfs_dir/0_md/bct-2/conf.lmp
--rw-r--r--   0 runner    (1001) docker     (123)      842 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_hdfs_dir/0_md/bct-2/input.lammps
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.699903 dpdispatcher-0.5.6/tests/test_hdfs_dir/0_md/bct-3/
--rw-r--r--   0 runner    (1001) docker     (123)      340 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_hdfs_dir/0_md/bct-3/conf.lmp
--rw-r--r--   0 runner    (1001) docker     (123)      842 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_hdfs_dir/0_md/bct-3/input.lammps
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.699903 dpdispatcher-0.5.6/tests/test_hdfs_dir/0_md/bct-4/
--rw-r--r--   0 runner    (1001) docker     (123)      340 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_hdfs_dir/0_md/bct-4/conf.lmp
--rw-r--r--   0 runner    (1001) docker     (123)      842 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_hdfs_dir/0_md/bct-4/input.lammps
--rw-r--r--   0 runner    (1001) docker     (123)      299 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_hdfs_dir/0_md/graph.pb
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.675903 dpdispatcher-0.5.6/tests/test_if_cuda_multi_devices/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.699903 dpdispatcher-0.5.6/tests/test_if_cuda_multi_devices/test_dir/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_if_cuda_multi_devices/test_dir/test.txt
--rw-r--r--   0 runner    (1001) docker     (123)      921 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_import_classes.py
--rw-r--r--   0 runner    (1001) docker     (123)     3458 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_lazy_local_context.py
--rw-r--r--   0 runner    (1001) docker     (123)    11015 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_local_context.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.675903 dpdispatcher-0.5.6/tests/test_lsf_dir/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.699903 dpdispatcher-0.5.6/tests/test_lsf_dir/0_md/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.699903 dpdispatcher-0.5.6/tests/test_lsf_dir/0_md/bct-1/
--rw-r--r--   0 runner    (1001) docker     (123)      340 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_lsf_dir/0_md/bct-1/conf.lmp
--rw-r--r--   0 runner    (1001) docker     (123)      842 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_lsf_dir/0_md/bct-1/input.lammps
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.699903 dpdispatcher-0.5.6/tests/test_lsf_dir/0_md/bct-2/
--rw-r--r--   0 runner    (1001) docker     (123)      340 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_lsf_dir/0_md/bct-2/conf.lmp
--rw-r--r--   0 runner    (1001) docker     (123)      842 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_lsf_dir/0_md/bct-2/input.lammps
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.699903 dpdispatcher-0.5.6/tests/test_lsf_dir/0_md/bct-3/
--rw-r--r--   0 runner    (1001) docker     (123)      340 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_lsf_dir/0_md/bct-3/conf.lmp
--rw-r--r--   0 runner    (1001) docker     (123)      842 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_lsf_dir/0_md/bct-3/input.lammps
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.699903 dpdispatcher-0.5.6/tests/test_lsf_dir/0_md/bct-4/
--rw-r--r--   0 runner    (1001) docker     (123)      340 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_lsf_dir/0_md/bct-4/conf.lmp
--rw-r--r--   0 runner    (1001) docker     (123)      842 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_lsf_dir/0_md/bct-4/input.lammps
--rw-r--r--   0 runner    (1001) docker     (123)      299 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_lsf_dir/0_md/graph.pb
--rw-r--r--   0 runner    (1001) docker     (123)     2306 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_lsf_dir/0_md/submission.json
--rwxr-xr-x   0 runner    (1001) docker     (123)     4068 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_lsf_script_generation.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.675903 dpdispatcher-0.5.6/tests/test_pbs_dir/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.699903 dpdispatcher-0.5.6/tests/test_pbs_dir/0_md/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.699903 dpdispatcher-0.5.6/tests/test_pbs_dir/0_md/bct-1/
--rw-r--r--   0 runner    (1001) docker     (123)      340 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_pbs_dir/0_md/bct-1/conf.lmp
--rw-r--r--   0 runner    (1001) docker     (123)      842 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_pbs_dir/0_md/bct-1/input.lammps
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.699903 dpdispatcher-0.5.6/tests/test_pbs_dir/0_md/bct-2/
--rw-r--r--   0 runner    (1001) docker     (123)      340 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_pbs_dir/0_md/bct-2/conf.lmp
--rw-r--r--   0 runner    (1001) docker     (123)      842 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_pbs_dir/0_md/bct-2/input.lammps
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.699903 dpdispatcher-0.5.6/tests/test_pbs_dir/0_md/bct-3/
--rw-r--r--   0 runner    (1001) docker     (123)      340 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_pbs_dir/0_md/bct-3/conf.lmp
--rw-r--r--   0 runner    (1001) docker     (123)      842 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_pbs_dir/0_md/bct-3/input.lammps
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.699903 dpdispatcher-0.5.6/tests/test_pbs_dir/0_md/bct-4/
--rw-r--r--   0 runner    (1001) docker     (123)      340 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_pbs_dir/0_md/bct-4/conf.lmp
--rw-r--r--   0 runner    (1001) docker     (123)      842 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_pbs_dir/0_md/bct-4/input.lammps
--rw-r--r--   0 runner    (1001) docker     (123)      299 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_pbs_dir/0_md/graph.pb
--rw-r--r--   0 runner    (1001) docker     (123)      923 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_retry.py
--rw-r--r--   0 runner    (1001) docker     (123)     4134 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_run_submission.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     1913 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_shell_cuda_multi_devices.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     4895 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_shell_trival.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.675903 dpdispatcher-0.5.6/tests/test_shell_trival_dir/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.703903 dpdispatcher-0.5.6/tests/test_shell_trival_dir/fail_dir/
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_shell_trival_dir/fail_dir/mock_fail_task.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.703903 dpdispatcher-0.5.6/tests/test_shell_trival_dir/parent_dir/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.703903 dpdispatcher-0.5.6/tests/test_shell_trival_dir/parent_dir/dir with space/
--rw-r--r--   0 runner    (1001) docker     (123)       15 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_shell_trival_dir/parent_dir/dir with space/example.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.703903 dpdispatcher-0.5.6/tests/test_shell_trival_dir/parent_dir/dir1/
--rw-r--r--   0 runner    (1001) docker     (123)       15 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_shell_trival_dir/parent_dir/dir1/example.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.703903 dpdispatcher-0.5.6/tests/test_shell_trival_dir/parent_dir/dir2/
--rw-r--r--   0 runner    (1001) docker     (123)       15 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_shell_trival_dir/parent_dir/dir2/example.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.703903 dpdispatcher-0.5.6/tests/test_shell_trival_dir/parent_dir/dir3/
--rw-r--r--   0 runner    (1001) docker     (123)       15 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_shell_trival_dir/parent_dir/dir3/example.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.703903 dpdispatcher-0.5.6/tests/test_shell_trival_dir/parent_dir/dir4/
--rw-r--r--   0 runner    (1001) docker     (123)       15 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_shell_trival_dir/parent_dir/dir4/example.txt
--rw-r--r--   0 runner    (1001) docker     (123)      299 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_shell_trival_dir/parent_dir/graph.pb
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.703903 dpdispatcher-0.5.6/tests/test_shell_trival_dir/recover_dir/
--rw-r--r--   0 runner    (1001) docker     (123)       68 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_shell_trival_dir/recover_dir/mock_recover_task.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.675903 dpdispatcher-0.5.6/tests/test_slurm_dir/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.703903 dpdispatcher-0.5.6/tests/test_slurm_dir/0_md/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.703903 dpdispatcher-0.5.6/tests/test_slurm_dir/0_md/bct-1/
--rw-r--r--   0 runner    (1001) docker     (123)      340 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_slurm_dir/0_md/bct-1/conf.lmp
--rw-r--r--   0 runner    (1001) docker     (123)      842 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_slurm_dir/0_md/bct-1/input.lammps
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.703903 dpdispatcher-0.5.6/tests/test_slurm_dir/0_md/bct-2/
--rw-r--r--   0 runner    (1001) docker     (123)      340 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_slurm_dir/0_md/bct-2/conf.lmp
--rw-r--r--   0 runner    (1001) docker     (123)      842 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_slurm_dir/0_md/bct-2/input.lammps
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.703903 dpdispatcher-0.5.6/tests/test_slurm_dir/0_md/bct-3/
--rw-r--r--   0 runner    (1001) docker     (123)      340 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_slurm_dir/0_md/bct-3/conf.lmp
--rw-r--r--   0 runner    (1001) docker     (123)      842 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_slurm_dir/0_md/bct-3/input.lammps
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.703903 dpdispatcher-0.5.6/tests/test_slurm_dir/0_md/bct-4/
--rw-r--r--   0 runner    (1001) docker     (123)      340 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_slurm_dir/0_md/bct-4/conf.lmp
--rw-r--r--   0 runner    (1001) docker     (123)      842 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_slurm_dir/0_md/bct-4/input.lammps
--rw-r--r--   0 runner    (1001) docker     (123)     2670 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_slurm_dir/0_md/d3c842c5b9476e48f7145b370cd330372b9293e1.json
--rw-r--r--   0 runner    (1001) docker     (123)      299 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_slurm_dir/0_md/graph.pb
--rw-r--r--   0 runner    (1001) docker     (123)     2306 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_slurm_dir/0_md/submission.json
--rwxr-xr-x   0 runner    (1001) docker     (123)     2349 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_slurm_script_generation.py
--rw-r--r--   0 runner    (1001) docker     (123)     5851 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_ssh_context.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:20.703903 dpdispatcher-0.5.6/tests/test_work_path/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-04-13 04:21:11.000000 dpdispatcher-0.5.6/tests/test_work_path/.gitkeep
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.191884 dpdispatcher-0.5.7/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.163883 dpdispatcher-0.5.7/.github/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.167883 dpdispatcher-0.5.7/.github/workflows/
+-rw-r--r--   0 runner    (1001) docker     (123)      847 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/.github/workflows/ci-docker.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      308 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/.github/workflows/machines.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      322 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/.github/workflows/mirror_gitee.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      338 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/.github/workflows/publish_conda.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      347 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/.github/workflows/pyright.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      211 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/.github/workflows/release.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      948 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/.github/workflows/test.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      403 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/.gitignore
+-rw-r--r--   0 runner    (1001) docker     (123)      995 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/.pre-commit-config.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)      542 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/CONTRIBUTING.md
+-rw-r--r--   0 runner    (1001) docker     (123)       87 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/Dockerfile
+-rw-r--r--   0 runner    (1001) docker     (123)     7652 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    11740 2023-06-27 23:33:24.191884 dpdispatcher-0.5.7/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1654 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.171883 dpdispatcher-0.5.7/ci/
+-rw-r--r--   0 runner    (1001) docker     (123)     1573 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/ci/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)      342 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/ci/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.171883 dpdispatcher-0.5.7/ci/pbs/
+-rw-r--r--   0 runner    (1001) docker     (123)     1192 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/ci/pbs/docker-compose.yml
+-rwxr-xr-x   0 runner    (1001) docker     (123)      253 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/ci/pbs/start-pbs.sh
+-rwxr-xr-x   0 runner    (1001) docker     (123)      665 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/ci/pbs.sh
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.171883 dpdispatcher-0.5.7/ci/slurm/
+-rw-r--r--   0 runner    (1001) docker     (123)     2282 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/ci/slurm/docker-compose.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      152 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/ci/slurm/register_cluster.sh
+-rwxr-xr-x   0 runner    (1001) docker     (123)      662 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/ci/slurm/start-slurm.sh
+-rwxr-xr-x   0 runner    (1001) docker     (123)      423 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/ci/slurm.sh
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.171883 dpdispatcher-0.5.7/ci/ssh/
+-rw-r--r--   0 runner    (1001) docker     (123)      537 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/ci/ssh/docker-compose.yml
+-rwxr-xr-x   0 runner    (1001) docker     (123)      302 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/ci/ssh/start-ssh.sh
+-rwxr-xr-x   0 runner    (1001) docker     (123)      411 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/ci/ssh.sh
+-rwxr-xr-x   0 runner    (1001) docker     (123)      586 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/ci/ssh_rsync.sh
+-rw-r--r--   0 runner    (1001) docker     (123)      142 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/codecov.yml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.171883 dpdispatcher-0.5.7/conda/
+-rw-r--r--   0 runner    (1001) docker     (123)       80 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/conda/conda_build_config.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)      906 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/conda/meta.yaml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.171883 dpdispatcher-0.5.7/doc/
+-rw-r--r--   0 runner    (1001) docker     (123)      524 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/doc/.gitignore
+-rw-r--r--   0 runner    (1001) docker     (123)      634 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/doc/Makefile
+-rw-r--r--   0 runner    (1001) docker     (123)     3234 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/doc/batch.md
+-rw-r--r--   0 runner    (1001) docker     (123)     2931 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/doc/conf.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2024 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/doc/context.md
+-rw-r--r--   0 runner    (1001) docker     (123)       43 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/doc/credits.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     5037 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/doc/dpdispatcher_on_yarn.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.171883 dpdispatcher-0.5.7/doc/examples/
+-rw-r--r--   0 runner    (1001) docker     (123)     1531 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/doc/examples/expanse.md
+-rw-r--r--   0 runner    (1001) docker     (123)      500 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/doc/examples/g16.md
+-rw-r--r--   0 runner    (1001) docker     (123)      947 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/doc/examples/shell.md
+-rw-r--r--   0 runner    (1001) docker     (123)     4300 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/doc/getting-started.md
+-rw-r--r--   0 runner    (1001) docker     (123)     1026 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/doc/index.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      118 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/doc/install.md
+-rw-r--r--   0 runner    (1001) docker     (123)      398 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/doc/machine.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      795 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/doc/make.bat
+-rw-r--r--   0 runner    (1001) docker     (123)        8 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/doc/requirements.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      408 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/doc/resources.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      389 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/doc/task.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.175883 dpdispatcher-0.5.7/dpdispatcher/
+-rw-r--r--   0 runner    (1001) docker     (123)      233 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/dpdispatcher/JobStatus.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2866 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/dpdispatcher/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      160 2023-06-27 23:33:24.000000 dpdispatcher-0.5.7/dpdispatcher/_version.py
+-rw-r--r--   0 runner    (1001) docker     (123)      188 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/dpdispatcher/arginfo.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3610 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/dpdispatcher/base_context.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6933 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/dpdispatcher/distributed_shell.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9857 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/dpdispatcher/dp_cloud_server.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11255 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/dpdispatcher/dp_cloud_server_context.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.175883 dpdispatcher-0.5.7/dpdispatcher/dpcloudserver/
+-rw-r--r--   0 runner    (1001) docker     (123)       49 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/dpdispatcher/dpcloudserver/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11152 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/dpdispatcher/dpcloudserver/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)      635 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/dpdispatcher/dpcloudserver/config.py
+-rw-r--r--   0 runner    (1001) docker     (123)      721 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/dpdispatcher/dpcloudserver/retcode.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2932 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/dpdispatcher/dpcloudserver/temp_test.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2611 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/dpdispatcher/dpcloudserver/zip_file.py
+-rw-r--r--   0 runner    (1001) docker     (123)       94 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/dpdispatcher/dpdisp.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6047 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/dpdispatcher/hdfs_cli.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8938 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/dpdispatcher/hdfs_context.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5692 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/dpdispatcher/lazy_local_context.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11772 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/dpdispatcher/local_context.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7790 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/dpdispatcher/lsf.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15296 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/dpdispatcher/machine.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6327 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/dpdispatcher/pbs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4141 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/dpdispatcher/shell.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14648 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/dpdispatcher/slurm.py
+-rw-r--r--   0 runner    (1001) docker     (123)    35032 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/dpdispatcher/ssh_context.py
+-rw-r--r--   0 runner    (1001) docker     (123)    44077 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/dpdispatcher/submission.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5035 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/dpdispatcher/utils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.175883 dpdispatcher-0.5.7/dpdispatcher.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    11740 2023-06-27 23:33:24.000000 dpdispatcher-0.5.7/dpdispatcher.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     7167 2023-06-27 23:33:24.000000 dpdispatcher-0.5.7/dpdispatcher.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 23:33:24.000000 dpdispatcher-0.5.7/dpdispatcher.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-27 23:33:24.000000 dpdispatcher-0.5.7/dpdispatcher.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      224 2023-06-27 23:33:24.000000 dpdispatcher-0.5.7/dpdispatcher.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       13 2023-06-27 23:33:24.000000 dpdispatcher-0.5.7/dpdispatcher.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.163883 dpdispatcher-0.5.7/examples/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.175883 dpdispatcher-0.5.7/examples/machine/
+-rw-r--r--   0 runner    (1001) docker     (123)      311 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/examples/machine/expanse.json
+-rw-r--r--   0 runner    (1001) docker     (123)       92 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/examples/machine/lazy_local.json
+-rw-r--r--   0 runner    (1001) docker     (123)      270 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/examples/machine/mandu.json
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.175883 dpdispatcher-0.5.7/examples/resources/
+-rw-r--r--   0 runner    (1001) docker     (123)      602 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/examples/resources/expanse_cpu.json
+-rw-r--r--   0 runner    (1001) docker     (123)      370 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/examples/resources/mandu.json
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.179884 dpdispatcher-0.5.7/examples/task/
+-rw-r--r--   0 runner    (1001) docker     (123)      284 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/examples/task/deepmd-kit.json
+-rw-r--r--   0 runner    (1001) docker     (123)      165 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/examples/task/g16.json
+-rw-r--r--   0 runner    (1001) docker     (123)     3023 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/pyproject.toml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.179884 dpdispatcher-0.5.7/scripts/
+-rw-r--r--   0 runner    (1001) docker     (123)      648 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/scripts/script_gen_dargs_docs.py
+-rw-r--r--   0 runner    (1001) docker     (123)      508 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/scripts/script_gen_dargs_json.py
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-27 23:33:24.191884 dpdispatcher-0.5.7/setup.cfg
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.183884 dpdispatcher-0.5.7/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)        7 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/.gitignore
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      133 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/batch.json
+-rw-r--r--   0 runner    (1001) docker     (123)     1838 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/context.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1843 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/debug_test_class_submission_init.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     3228 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/devel_test_ali_ehpc.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     2669 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/devel_test_dp_cloud_server.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1752 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/devel_test_lazy_ali_ehpc.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1398 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/devel_test_lsf.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     2357 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/devel_test_shell.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     2673 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/devel_test_slurm.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     2629 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/devel_test_ssh_ali_ehpc.py
+-rw-r--r--   0 runner    (1001) docker     (123)      299 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/graph.pb
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.183884 dpdispatcher-0.5.7/tests/jsons/
+-rw-r--r--   0 runner    (1001) docker     (123)     1451 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/jsons/job.json
+-rw-r--r--   0 runner    (1001) docker     (123)      345 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/jsons/machine.json
+-rw-r--r--   0 runner    (1001) docker     (123)      489 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/jsons/machine_ali_ehpc.json
+-rw-r--r--   0 runner    (1001) docker     (123)      845 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/jsons/machine_center.json
+-rw-r--r--   0 runner    (1001) docker     (123)      695 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/jsons/machine_diffenert.json
+-rw-r--r--   0 runner    (1001) docker     (123)     1202 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/jsons/machine_dp_cloud_server.json
+-rw-r--r--   0 runner    (1001) docker     (123)      497 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/jsons/machine_if_cuda_multi_devices.json
+-rw-r--r--   0 runner    (1001) docker     (123)     1173 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/jsons/machine_lazy_local_lsf.json
+-rw-r--r--   0 runner    (1001) docker     (123)      745 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/jsons/machine_lazy_local_slurm.json
+-rw-r--r--   0 runner    (1001) docker     (123)      307 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/jsons/machine_lazylocal_shell.json
+-rw-r--r--   0 runner    (1001) docker     (123)      352 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/jsons/machine_local_shell.json
+-rw-r--r--   0 runner    (1001) docker     (123)     1108 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/jsons/machine_lsf.json
+-rw-r--r--   0 runner    (1001) docker     (123)      879 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/jsons/machine_slurm.json
+-rw-r--r--   0 runner    (1001) docker     (123)     1071 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/jsons/machine_yarn.json
+-rw-r--r--   0 runner    (1001) docker     (123)      357 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/jsons/resources.json
+-rw-r--r--   0 runner    (1001) docker     (123)     4505 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/jsons/submission.json
+-rw-r--r--   0 runner    (1001) docker     (123)      239 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/jsons/task.json
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.183884 dpdispatcher-0.5.7/tests/lsf/
+-rw-r--r--   0 runner    (1001) docker     (123)      684 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/lsf/context.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1581 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/lsf/test_dispatcher.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7600 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/lsf/test_lsf_local.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.183884 dpdispatcher-0.5.7/tests/old/
+-rw-r--r--   0 runner    (1001) docker     (123)     1286 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/old/test_dispatcher_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7968 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/old/test_lazy_local_context.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15772 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/old/test_local_context.py
+-rw-r--r--   0 runner    (1001) docker     (123)      390 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/old/test_local_session.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10956 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/old/test_ssh_context.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.183884 dpdispatcher-0.5.7/tests/pbs/
+-rw-r--r--   0 runner    (1001) docker     (123)      684 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/pbs/context.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1577 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/pbs/test_dispatcher.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5652 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/pbs/test_pbs_local.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5188 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/sample_class.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1074 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/script_gen_json.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.183884 dpdispatcher-0.5.7/tests/shell/
+-rw-r--r--   0 runner    (1001) docker     (123)      684 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/shell/context.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1532 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/shell/test_dispatcher.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8869 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/shell/test_shell_local.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7147 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/shell/test_shell_ssh.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.187884 dpdispatcher-0.5.7/tests/slurm/
+-rw-r--r--   0 runner    (1001) docker     (123)      684 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/slurm/context.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1743 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/slurm/test_dispatcher.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1730 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/slurm/test_dispatcher_lazy_local.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8182 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/slurm/test_slurm_lazy_local.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7811 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/slurm/test_slurm_local.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8114 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/slurm/test_slurm_ssh.py
+-rw-r--r--   0 runner    (1001) docker     (123)       55 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/slurm_test.env
+-rw-r--r--   0 runner    (1001) docker     (123)     2629 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_argcheck.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1677 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_class_job.py
+-rw-r--r--   0 runner    (1001) docker     (123)      697 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_class_machine.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6837 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_class_machine_dispatch.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1599 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_class_resources.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3790 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_class_submission.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2306 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_class_submission_init.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1260 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_class_task.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.163883 dpdispatcher-0.5.7/tests/test_context_dir/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.187884 dpdispatcher-0.5.7/tests/test_context_dir/0_md/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.187884 dpdispatcher-0.5.7/tests/test_context_dir/0_md/bct-1/
+-rw-r--r--   0 runner    (1001) docker     (123)      340 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_context_dir/0_md/bct-1/conf.lmp
+-rw-r--r--   0 runner    (1001) docker     (123)      842 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_context_dir/0_md/bct-1/input.lammps
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.187884 dpdispatcher-0.5.7/tests/test_context_dir/0_md/bct-1/some_dir/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_context_dir/0_md/bct-1/some_dir/some_file
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.187884 dpdispatcher-0.5.7/tests/test_context_dir/0_md/bct-2/
+-rw-r--r--   0 runner    (1001) docker     (123)      340 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_context_dir/0_md/bct-2/conf.lmp
+-rw-r--r--   0 runner    (1001) docker     (123)      842 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_context_dir/0_md/bct-2/input.lammps
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.187884 dpdispatcher-0.5.7/tests/test_context_dir/0_md/bct-3/
+-rw-r--r--   0 runner    (1001) docker     (123)      340 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_context_dir/0_md/bct-3/conf.lmp
+-rw-r--r--   0 runner    (1001) docker     (123)      842 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_context_dir/0_md/bct-3/input.lammps
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.187884 dpdispatcher-0.5.7/tests/test_context_dir/0_md/bct-4/
+-rw-r--r--   0 runner    (1001) docker     (123)      340 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_context_dir/0_md/bct-4/conf.lmp
+-rw-r--r--   0 runner    (1001) docker     (123)      842 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_context_dir/0_md/bct-4/input.lammps
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.187884 dpdispatcher-0.5.7/tests/test_context_dir/0_md/dir with space/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_context_dir/0_md/dir with space/file with space
+-rw-r--r--   0 runner    (1001) docker     (123)      299 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_context_dir/0_md/graph.pb
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.187884 dpdispatcher-0.5.7/tests/test_context_dir/0_md/some_dir/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_context_dir/0_md/some_dir/some_file
+-rw-r--r--   0 runner    (1001) docker     (123)     1402 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_group_size.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2859 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_hdfs_context.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.163883 dpdispatcher-0.5.7/tests/test_hdfs_dir/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.187884 dpdispatcher-0.5.7/tests/test_hdfs_dir/0_md/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.187884 dpdispatcher-0.5.7/tests/test_hdfs_dir/0_md/bct-1/
+-rw-r--r--   0 runner    (1001) docker     (123)      340 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_hdfs_dir/0_md/bct-1/conf.lmp
+-rw-r--r--   0 runner    (1001) docker     (123)      842 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_hdfs_dir/0_md/bct-1/input.lammps
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.187884 dpdispatcher-0.5.7/tests/test_hdfs_dir/0_md/bct-2/
+-rw-r--r--   0 runner    (1001) docker     (123)      340 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_hdfs_dir/0_md/bct-2/conf.lmp
+-rw-r--r--   0 runner    (1001) docker     (123)      842 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_hdfs_dir/0_md/bct-2/input.lammps
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.187884 dpdispatcher-0.5.7/tests/test_hdfs_dir/0_md/bct-3/
+-rw-r--r--   0 runner    (1001) docker     (123)      340 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_hdfs_dir/0_md/bct-3/conf.lmp
+-rw-r--r--   0 runner    (1001) docker     (123)      842 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_hdfs_dir/0_md/bct-3/input.lammps
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.187884 dpdispatcher-0.5.7/tests/test_hdfs_dir/0_md/bct-4/
+-rw-r--r--   0 runner    (1001) docker     (123)      340 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_hdfs_dir/0_md/bct-4/conf.lmp
+-rw-r--r--   0 runner    (1001) docker     (123)      842 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_hdfs_dir/0_md/bct-4/input.lammps
+-rw-r--r--   0 runner    (1001) docker     (123)      299 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_hdfs_dir/0_md/graph.pb
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.167883 dpdispatcher-0.5.7/tests/test_if_cuda_multi_devices/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.187884 dpdispatcher-0.5.7/tests/test_if_cuda_multi_devices/test_dir/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_if_cuda_multi_devices/test_dir/test.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      921 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_import_classes.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3458 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_lazy_local_context.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11015 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_local_context.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.167883 dpdispatcher-0.5.7/tests/test_lsf_dir/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.187884 dpdispatcher-0.5.7/tests/test_lsf_dir/0_md/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.187884 dpdispatcher-0.5.7/tests/test_lsf_dir/0_md/bct-1/
+-rw-r--r--   0 runner    (1001) docker     (123)      340 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_lsf_dir/0_md/bct-1/conf.lmp
+-rw-r--r--   0 runner    (1001) docker     (123)      842 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_lsf_dir/0_md/bct-1/input.lammps
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.187884 dpdispatcher-0.5.7/tests/test_lsf_dir/0_md/bct-2/
+-rw-r--r--   0 runner    (1001) docker     (123)      340 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_lsf_dir/0_md/bct-2/conf.lmp
+-rw-r--r--   0 runner    (1001) docker     (123)      842 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_lsf_dir/0_md/bct-2/input.lammps
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.187884 dpdispatcher-0.5.7/tests/test_lsf_dir/0_md/bct-3/
+-rw-r--r--   0 runner    (1001) docker     (123)      340 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_lsf_dir/0_md/bct-3/conf.lmp
+-rw-r--r--   0 runner    (1001) docker     (123)      842 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_lsf_dir/0_md/bct-3/input.lammps
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.191884 dpdispatcher-0.5.7/tests/test_lsf_dir/0_md/bct-4/
+-rw-r--r--   0 runner    (1001) docker     (123)      340 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_lsf_dir/0_md/bct-4/conf.lmp
+-rw-r--r--   0 runner    (1001) docker     (123)      842 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_lsf_dir/0_md/bct-4/input.lammps
+-rw-r--r--   0 runner    (1001) docker     (123)      299 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_lsf_dir/0_md/graph.pb
+-rw-r--r--   0 runner    (1001) docker     (123)     2306 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_lsf_dir/0_md/submission.json
+-rwxr-xr-x   0 runner    (1001) docker     (123)     4068 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_lsf_script_generation.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.167883 dpdispatcher-0.5.7/tests/test_pbs_dir/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.191884 dpdispatcher-0.5.7/tests/test_pbs_dir/0_md/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.191884 dpdispatcher-0.5.7/tests/test_pbs_dir/0_md/bct-1/
+-rw-r--r--   0 runner    (1001) docker     (123)      340 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_pbs_dir/0_md/bct-1/conf.lmp
+-rw-r--r--   0 runner    (1001) docker     (123)      842 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_pbs_dir/0_md/bct-1/input.lammps
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.191884 dpdispatcher-0.5.7/tests/test_pbs_dir/0_md/bct-2/
+-rw-r--r--   0 runner    (1001) docker     (123)      340 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_pbs_dir/0_md/bct-2/conf.lmp
+-rw-r--r--   0 runner    (1001) docker     (123)      842 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_pbs_dir/0_md/bct-2/input.lammps
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.191884 dpdispatcher-0.5.7/tests/test_pbs_dir/0_md/bct-3/
+-rw-r--r--   0 runner    (1001) docker     (123)      340 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_pbs_dir/0_md/bct-3/conf.lmp
+-rw-r--r--   0 runner    (1001) docker     (123)      842 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_pbs_dir/0_md/bct-3/input.lammps
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.191884 dpdispatcher-0.5.7/tests/test_pbs_dir/0_md/bct-4/
+-rw-r--r--   0 runner    (1001) docker     (123)      340 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_pbs_dir/0_md/bct-4/conf.lmp
+-rw-r--r--   0 runner    (1001) docker     (123)      842 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_pbs_dir/0_md/bct-4/input.lammps
+-rw-r--r--   0 runner    (1001) docker     (123)      299 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_pbs_dir/0_md/graph.pb
+-rw-r--r--   0 runner    (1001) docker     (123)      923 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_retry.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4534 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_run_submission.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4401 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_run_submission_ratio_unfinished.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1913 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_shell_cuda_multi_devices.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     4895 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_shell_trival.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.167883 dpdispatcher-0.5.7/tests/test_shell_trival_dir/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.191884 dpdispatcher-0.5.7/tests/test_shell_trival_dir/fail_dir/
+-rw-r--r--   0 runner    (1001) docker     (123)       65 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_shell_trival_dir/fail_dir/mock_fail_task.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.191884 dpdispatcher-0.5.7/tests/test_shell_trival_dir/parent_dir/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.191884 dpdispatcher-0.5.7/tests/test_shell_trival_dir/parent_dir/dir with space/
+-rw-r--r--   0 runner    (1001) docker     (123)       15 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_shell_trival_dir/parent_dir/dir with space/example.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.191884 dpdispatcher-0.5.7/tests/test_shell_trival_dir/parent_dir/dir1/
+-rw-r--r--   0 runner    (1001) docker     (123)       15 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_shell_trival_dir/parent_dir/dir1/example.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.191884 dpdispatcher-0.5.7/tests/test_shell_trival_dir/parent_dir/dir2/
+-rw-r--r--   0 runner    (1001) docker     (123)       15 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_shell_trival_dir/parent_dir/dir2/example.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.191884 dpdispatcher-0.5.7/tests/test_shell_trival_dir/parent_dir/dir3/
+-rw-r--r--   0 runner    (1001) docker     (123)       15 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_shell_trival_dir/parent_dir/dir3/example.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.191884 dpdispatcher-0.5.7/tests/test_shell_trival_dir/parent_dir/dir4/
+-rw-r--r--   0 runner    (1001) docker     (123)       15 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_shell_trival_dir/parent_dir/dir4/example.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      299 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_shell_trival_dir/parent_dir/graph.pb
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.191884 dpdispatcher-0.5.7/tests/test_shell_trival_dir/recover_dir/
+-rw-r--r--   0 runner    (1001) docker     (123)       68 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_shell_trival_dir/recover_dir/mock_recover_task.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.167883 dpdispatcher-0.5.7/tests/test_slurm_dir/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.191884 dpdispatcher-0.5.7/tests/test_slurm_dir/0_md/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.191884 dpdispatcher-0.5.7/tests/test_slurm_dir/0_md/bct-1/
+-rw-r--r--   0 runner    (1001) docker     (123)      340 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_slurm_dir/0_md/bct-1/conf.lmp
+-rw-r--r--   0 runner    (1001) docker     (123)      842 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_slurm_dir/0_md/bct-1/input.lammps
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.191884 dpdispatcher-0.5.7/tests/test_slurm_dir/0_md/bct-2/
+-rw-r--r--   0 runner    (1001) docker     (123)      340 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_slurm_dir/0_md/bct-2/conf.lmp
+-rw-r--r--   0 runner    (1001) docker     (123)      842 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_slurm_dir/0_md/bct-2/input.lammps
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.191884 dpdispatcher-0.5.7/tests/test_slurm_dir/0_md/bct-3/
+-rw-r--r--   0 runner    (1001) docker     (123)      340 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_slurm_dir/0_md/bct-3/conf.lmp
+-rw-r--r--   0 runner    (1001) docker     (123)      842 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_slurm_dir/0_md/bct-3/input.lammps
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.191884 dpdispatcher-0.5.7/tests/test_slurm_dir/0_md/bct-4/
+-rw-r--r--   0 runner    (1001) docker     (123)      340 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_slurm_dir/0_md/bct-4/conf.lmp
+-rw-r--r--   0 runner    (1001) docker     (123)      842 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_slurm_dir/0_md/bct-4/input.lammps
+-rw-r--r--   0 runner    (1001) docker     (123)     2670 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_slurm_dir/0_md/d3c842c5b9476e48f7145b370cd330372b9293e1.json
+-rw-r--r--   0 runner    (1001) docker     (123)      299 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_slurm_dir/0_md/graph.pb
+-rw-r--r--   0 runner    (1001) docker     (123)     2306 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_slurm_dir/0_md/submission.json
+-rwxr-xr-x   0 runner    (1001) docker     (123)     2349 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_slurm_script_generation.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7447 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_ssh_context.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:24.191884 dpdispatcher-0.5.7/tests/test_work_path/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 23:33:14.000000 dpdispatcher-0.5.7/tests/test_work_path/.gitkeep
```

### Comparing `dpdispatcher-0.5.6/.github/workflows/ci-docker.yml` & `dpdispatcher-0.5.7/.github/workflows/ci-docker.yml`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/.github/workflows/test.yml` & `dpdispatcher-0.5.7/.github/workflows/test.yml`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/.pre-commit-config.yaml` & `dpdispatcher-0.5.7/.pre-commit-config.yaml`

 * *Files 2% similar despite different names*

```diff
@@ -18,22 +18,22 @@
 # Python
 -   repo: https://github.com/psf/black
     rev: 23.3.0
     hooks:
     -   id: black-jupyter
 -   repo: https://github.com/charliermarsh/ruff-pre-commit
     # Ruff version.
-    rev: v0.0.260
+    rev: v0.0.275
     hooks:
     - id: ruff
       args: ["--fix"]
 # numpydoc
 -   repo: https://github.com/Carreau/velin
     rev: 0.0.12
     hooks:
     - id: velin
       args: ["--write"]
 # Python inside docs
 -   repo: https://github.com/asottile/blacken-docs
-    rev: 1.13.0
+    rev: 1.14.0
     hooks:
     -   id: blacken-docs
```

### Comparing `dpdispatcher-0.5.6/CONTRIBUTING.md` & `dpdispatcher-0.5.7/CONTRIBUTING.md`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/LICENSE` & `dpdispatcher-0.5.7/LICENSE`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/PKG-INFO` & `dpdispatcher-0.5.7/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: dpdispatcher
-Version: 0.5.6
+Version: 0.5.7
 Summary: Generate HPC scheduler systems jobs input scripts, submit these scripts to HPC systems, and poke until they finish
 Author: DeepModeling
 License:                    GNU LESSER GENERAL PUBLIC LICENSE
                                Version 3, 29 June 2007
         
          Copyright (C) 2007 Free Software Foundation, Inc. <https://fsf.org/>
          Everyone is permitted to copy and distribute verbatim copies
@@ -187,29 +187,38 @@
 Provides-Extra: docs
 Provides-Extra: cloudserver
 Provides-Extra: test
 License-File: LICENSE
 
 # DPDispatcher
 
-DPDispatcher is a python package used to generate HPC(High Performance Computing) scheduler systems (Slurm/PBS/LSF/dpcloudserver) jobs input scripts and submit these  scripts to HPC systems and poke until they finish.
+[![conda-forge](https://img.shields.io/conda/dn/conda-forge/dpdispatcher?color=red&label=conda-forge&logo=conda-forge)](https://anaconda.org/conda-forge/dpdispatcher)
+[![pip install](https://img.shields.io/pypi/dm/dpdispatcher?label=pip%20install&logo=pypi)](https://pypi.org/project/dpdispatcher)
+[![docker pull](https://img.shields.io/docker/pulls/dptechnology/dpdispatcher?logo=docker)](https://hub.docker.com/r/dptechnology/dpdispatcher)
+[![Documentation Status](https://readthedocs.org/projects/dpdispatcher/badge/)](https://dpdispatcher.readthedocs.io/)
+
+DPDispatcher is a Python package used to generate HPC (High-Performance Computing) scheduler systems (Slurm/PBS/LSF/Bohrium) jobs input scripts, submit them to HPC systems, and poke until they finish.
 ​
-DPDispatcher will monitor (poke) until these jobs finish and download the results files (if these jobs is running on remote systems connected by SSH).
+DPDispatcher will monitor (poke) until these jobs finish and download the results files (if these jobs are running on remote systems connected by SSH).
 
 For more information, check the [documentation](https://dpdispatcher.readthedocs.io/).
 
 ## Installation
 
-DPDispatcher can installed by `pip`:
+DPDispatcher can be installed by `pip`:
 
 ```bash
 pip install dpdispatcher
 ```
 
 ## Usage
 
 See [Getting Started](https://dpdispatcher.readthedocs.io/en/latest/getting-started.html) for usage.
 
 ## Contributing
 
-DPDispatcher is maintained by Deep Modeling's developers and welcome other people.
+DPDispatcher is maintained by Deep Modeling's developers and welcomes other people.
 See [Contributing Guide](CONTRIBUTING.md) to become a contributor! 🤓
+
+## References
+
+DPDispatcher is derivated from the [DP-GEN](https://github.com/deepmodeling/dpgen) package. To mention DPDispatcher in a scholarly publication, please read Section 3.3 in the [DP-GEN paper](https://doi.org/10.1016/j.cpc.2020.107206).
```

### Comparing `dpdispatcher-0.5.6/ci/LICENSE` & `dpdispatcher-0.5.7/ci/LICENSE`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/ci/pbs/docker-compose.yml` & `dpdispatcher-0.5.7/ci/pbs/docker-compose.yml`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/ci/pbs.sh` & `dpdispatcher-0.5.7/ci/pbs.sh`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/ci/slurm/docker-compose.yml` & `dpdispatcher-0.5.7/ci/slurm/docker-compose.yml`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/ci/slurm/start-slurm.sh` & `dpdispatcher-0.5.7/ci/slurm/start-slurm.sh`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/ci/ssh/docker-compose.yml` & `dpdispatcher-0.5.7/ci/ssh/docker-compose.yml`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/ci/ssh_rsync.sh` & `dpdispatcher-0.5.7/ci/ssh_rsync.sh`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/conda/meta.yaml` & `dpdispatcher-0.5.7/conda/meta.yaml`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/doc/.gitignore` & `dpdispatcher-0.5.7/doc/.gitignore`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/doc/Makefile` & `dpdispatcher-0.5.7/doc/Makefile`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/doc/batch.md` & `dpdispatcher-0.5.7/doc/batch.md`

 * *Files 5% similar despite different names*

```diff
@@ -17,17 +17,17 @@
 
 {dargs:argument}`batch_type <resources/batch_type>`: `Slurm`, `SlurmJobArray`
 
 [Slurm](https://slurm.schedmd.com/) is a job scheduling system used by lots of HPCs.
 One needs to make sure slurm has been setup in the remote server and the related environment is activated.
 
 When `SlurmJobArray` is used, dpdispatcher submits Slurm jobs with [job arrays](https://slurm.schedmd.com/job_array.html).
-In this way, a dpdispatcher {class}`task <dpdispatcher.submission.Task>` maps to a Slurm job and a dpdispatcher {class}`job <dpdispatcher.submission.Job>` maps to a Slurm job array.
+In this way, several dpdispatcher {class}`task <dpdispatcher.submission.Task>`s map to a Slurm job and a dpdispatcher {class}`job <dpdispatcher.submission.Job>` maps to a Slurm job array.
 Millions of Slurm jobs can be submitted quickly and Slurm can execute all Slurm jobs at the same time.
-One can use {dargs:argument}`group_size <resources/group_size>` to control how many Slurm jobs are contained in a Slurm job array.
+One can use {dargs:argument}`group_size <resources/group_size>` and {dargs:argument}`slurm_job_size <resources[SlurmJobArray]/kwargs/slurm_job_size>` to control how many Slurm jobs are contained in a Slurm job array.
 
 ## OpenPBS or PBSPro
 
 {dargs:argument}`batch_type <resources/batch_type>`: `PBS`
 
 [OpenPBS](https://www.openpbs.org/) is an open-source job scheduling of the Linux Foundation and [PBS Profession](https://www.altair.com/pbs-professional/) is its commercial solution.
 One needs to make sure OpenPBS has been setup in the remote server and the related environment is activated.
```

### Comparing `dpdispatcher-0.5.6/doc/conf.py` & `dpdispatcher-0.5.7/doc/conf.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/doc/context.md` & `dpdispatcher-0.5.7/doc/context.md`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/doc/dpdispatcher_on_yarn.md` & `dpdispatcher-0.5.7/doc/dpdispatcher_on_yarn.md`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/doc/examples/expanse.md` & `dpdispatcher-0.5.7/doc/examples/expanse.md`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/doc/examples/shell.md` & `dpdispatcher-0.5.7/doc/examples/shell.md`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/doc/getting-started.md` & `dpdispatcher-0.5.7/doc/getting-started.md`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/doc/index.rst` & `dpdispatcher-0.5.7/doc/index.rst`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/doc/make.bat` & `dpdispatcher-0.5.7/doc/make.bat`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/dpdispatcher/__init__.py` & `dpdispatcher-0.5.7/dpdispatcher/__init__.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/dpdispatcher/base_context.py` & `dpdispatcher-0.5.7/dpdispatcher/base_context.py`

 * *Files 6% similar despite different names*

```diff
@@ -66,17 +66,14 @@
     def write_file(self, fname, write_str):
         raise NotImplementedError("abstract method")
 
     @abstractmethod
     def read_file(self, fname):
         raise NotImplementedError("abstract method")
 
-    def kill(self, proc):
-        raise NotImplementedError("abstract method")
-
     def check_finish(self, proc):
         raise NotImplementedError("abstract method")
 
     @classmethod
     def machine_arginfo(cls) -> Argument:
         """Generate the machine arginfo.
```

### Comparing `dpdispatcher-0.5.6/dpdispatcher/distributed_shell.py` & `dpdispatcher-0.5.7/dpdispatcher/distributed_shell.py`

 * *Files 1% similar despite different names*

```diff
@@ -132,25 +132,24 @@
         script_file_name = job.script_file_name
         job_id_name = job.job_hash + "_job_id"
         output_name = job.job_hash + ".out"
         self.context.write_file(fname=script_file_name, write_str=script_str)
 
         resources = job.resources
         submit_command = (
-            "hadoop jar %s/hadoop-yarn-applications-distributedshell-*.jar "
+            "hadoop jar {}/hadoop-yarn-applications-distributedshell-*.jar "
             "org.apache.hadoop.yarn.applications.distributedshell.Client "
-            "-jar %s/hadoop-yarn-applications-distributedshell-*.jar "
-            '-queue %s -appname "distributedshell_dpgen_%s" '
+            "-jar {}/hadoop-yarn-applications-distributedshell-*.jar "
+            '-queue {} -appname "distributedshell_dpgen_{}" '
             "-shell_env YARN_CONTAINER_RUNTIME_TYPE=docker "
-            "-shell_env YARN_CONTAINER_RUNTIME_DOCKER_IMAGE=%s "
+            "-shell_env YARN_CONTAINER_RUNTIME_DOCKER_IMAGE={} "
             "-shell_env ENV_DOCKER_CONTAINER_SHM_SIZE='600m' "
             "-master_memory 1024 -master_vcores 2 -num_containers 1 "
-            "-container_resources memory-mb=%s,vcores=%s "
-            "-shell_script /tmp/%s"
-            % (
+            "-container_resources memory-mb={},vcores={} "
+            "-shell_script /tmp/{}".format(
                 resources.kwargs.get("yarn_path", ""),
                 resources.kwargs.get("yarn_path", ""),
                 resources.queue_name,
                 job.job_hash,
                 resources.kwargs.get("img_name", ""),
                 resources.kwargs.get("mem_limit", 1) * 1024,
                 resources.cpu_per_node,
```

### Comparing `dpdispatcher-0.5.6/dpdispatcher/dp_cloud_server.py` & `dpdispatcher-0.5.7/dpdispatcher/dp_cloud_server.py`

 * *Files 2% similar despite different names*

```diff
@@ -102,15 +102,17 @@
         zip_filename = job.job_hash + ".zip"
         # oss_task_zip = 'indicate/' + job.job_hash + '/' + zip_filename
         oss_task_zip = self._gen_oss_path(job, zip_filename)
         job_resources = ALI_OSS_BUCKET_URL + oss_task_zip
 
         input_data = self.input_data.copy()
 
-        input_data["job_resources"] = job_resources
+        if not input_data.get("job_resources"):
+            input_data["job_resources"] = []
+        input_data["job_resources"].append(job_resources)
         input_data["command"] = f"bash {job.script_file_name}"
         if not input_data.get("backward_files"):
             input_data["backward_files"] = self._gen_backward_files_list(job)
         input_data["logFiles"] = os.path.join(
             job.job_task_list[0].task_work_path, job.job_task_list[0].outlog
         )
         program_id = self.context.remote_profile.get("program_id")
```

### Comparing `dpdispatcher-0.5.6/dpdispatcher/dp_cloud_server_context.py` & `dpdispatcher-0.5.7/dpdispatcher/dp_cloud_server_context.py`

 * *Files 1% similar despite different names*

```diff
@@ -266,17 +266,14 @@
     # def get_return(self, cmd_pipes):
     #     if not self.check_finish(cmd_pipes):
     #         return None, None, None
     #     else :
     #         retcode = cmd_pipes['stdout'].channel.recv_exit_status()
     #         return retcode, cmd_pipes['stdout'], cmd_pipes['stderr']
 
-    def kill(self, cmd_pipes):
-        pass
-
     @classmethod
     def machine_subfields(cls) -> List[Argument]:
         """Generate the machine subfields.
 
         Returns
         -------
         list[Argument]
```

### Comparing `dpdispatcher-0.5.6/dpdispatcher/dpcloudserver/client.py` & `dpdispatcher-0.5.7/dpdispatcher/dpcloudserver/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -194,15 +194,15 @@
         return result
 
     def job_create(
         self, job_type, oss_path, input_data, program_id=None, group_id=None
     ):
         post_data = {
             "job_type": job_type,
-            "oss_path": [oss_path],
+            "oss_path": oss_path,
         }
         if program_id is not None:
             post_data["project_id"] = program_id
         if group_id is not None:
             post_data["job_group_id"] = group_id
         for k, v in input_data.items():
             post_data[k] = v
```

### Comparing `dpdispatcher-0.5.6/dpdispatcher/dpcloudserver/config.py` & `dpdispatcher-0.5.7/dpdispatcher/dpcloudserver/config.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/dpdispatcher/dpcloudserver/retcode.py` & `dpdispatcher-0.5.7/dpdispatcher/dpcloudserver/retcode.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/dpdispatcher/dpcloudserver/temp_test.py` & `dpdispatcher-0.5.7/dpdispatcher/dpcloudserver/temp_test.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/dpdispatcher/dpcloudserver/zip_file.py` & `dpdispatcher-0.5.7/dpdispatcher/dpcloudserver/zip_file.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/dpdispatcher/hdfs_cli.py` & `dpdispatcher-0.5.7/dpdispatcher/hdfs_cli.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/dpdispatcher/hdfs_context.py` & `dpdispatcher-0.5.7/dpdispatcher/hdfs_context.py`

 * *Files 2% similar despite different names*

```diff
@@ -243,10 +243,7 @@
         with open(local_file, "w") as fp:
             fp.write(write_str)
         HDFS.copy_from_local(local_file, os.path.join(self.remote_root, fname))
         return local_file
 
     def read_file(self, fname):
         return HDFS.read_hdfs_file(os.path.join(self.remote_root, fname))
-
-    def kill(self, job_id):
-        pass
```

### Comparing `dpdispatcher-0.5.6/dpdispatcher/lazy_local_context.py` & `dpdispatcher-0.5.7/dpdispatcher/lazy_local_context.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,9 +1,8 @@
 import os
-import signal
 import subprocess as sp
 
 from dpdispatcher.base_context import BaseContext
 
 
 class SPRetObj:
     def __init__(self, ret):
@@ -163,17 +162,14 @@
     def call(self, cmd):
         cwd = os.getcwd()
         proc = sp.Popen(
             cmd, cwd=self.local_root, shell=True, stdout=sp.PIPE, stderr=sp.PIPE
         )
         return proc
 
-    def kill(self, job_id):
-        os.kill(job_id, signal.SIGTERM)
-
     def check_finish(self, proc):
         return proc.poll() is not None
 
     def get_return(self, proc):
         ret = proc.poll()
         if ret is None:
             return None, None, None
```

### Comparing `dpdispatcher-0.5.6/dpdispatcher/local_context.py` & `dpdispatcher-0.5.7/dpdispatcher/local_context.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,10 @@
 import hashlib
 import os
 import shutil
-import signal
 import subprocess as sp
 from glob import glob
 from subprocess import TimeoutExpired
 
 from dpdispatcher import dlog
 from dpdispatcher.base_context import BaseContext
 
@@ -287,17 +286,14 @@
 
     def call(self, cmd):
         proc = sp.Popen(
             cmd, cwd=self.remote_root, shell=True, stdout=sp.PIPE, stderr=sp.PIPE
         )
         return proc
 
-    def kill(self, job_id):
-        os.kill(job_id, signal.SIGTERM)
-
     def check_finish(self, proc):
         return proc.poll() is not None
 
     def get_return(self, proc):
         ret = proc.poll()
         if ret is None:
             return None, None, None
```

### Comparing `dpdispatcher-0.5.6/dpdispatcher/lsf.py` & `dpdispatcher-0.5.7/dpdispatcher/lsf.py`

 * *Files 3% similar despite different names*

```diff
@@ -79,16 +79,15 @@
         script_file_name = job.script_file_name
         script_str = self.gen_script(job)
         job_id_name = job.job_hash + "_job_id"
         self.context.write_file(fname=script_file_name, write_str=script_str)
 
         try:
             stdin, stdout, stderr = self.context.block_checkcall(
-                "cd %s && %s %s"
-                % (
+                "cd {} && {} {}".format(
                     shlex.quote(self.context.remote_root),
                     "bsub < ",
                     shlex.quote(script_file_name),
                 )
             )
         except RuntimeError as err:
             raise RetrySignal(err) from err
@@ -207,7 +206,18 @@
                         doc=doc_custom_gpu_line,
                     ),
                 ],
                 optional=False,
                 doc="Extra arguments.",
             )
         ]
+
+    def kill(self, job):
+        """Kill the job.
+
+        Parameters
+        ----------
+        job : Job
+            job
+        """
+        job_id = job.job_id
+        ret, stdin, stdout, stderr = self.context.block_call("bkill " + str(job_id))
```

### Comparing `dpdispatcher-0.5.6/dpdispatcher/machine.py` & `dpdispatcher-0.5.7/dpdispatcher/machine.py`

 * *Files 1% similar despite different names*

```diff
@@ -373,16 +373,20 @@
         doc_clean_asynchronously = (
             "Clean the remote directory asynchronously after the job finishes."
         )
 
         machine_args = [
             Argument("batch_type", str, optional=False, doc=doc_batch_type),
             # TODO: add default to local_root and remote_root after refactor the code
-            Argument("local_root", [str, None], optional=False, doc=doc_local_root),
-            Argument("remote_root", [str, None], optional=True, doc=doc_remote_root),
+            Argument(
+                "local_root", [str, type(None)], optional=False, doc=doc_local_root
+            ),
+            Argument(
+                "remote_root", [str, type(None)], optional=True, doc=doc_remote_root
+            ),
             Argument(
                 "clean_asynchronously",
                 bool,
                 optional=True,
                 default=False,
                 doc=doc_clean_asynchronously,
             ),
@@ -435,7 +439,19 @@
             resources subfields
         """
         return [
             Argument(
                 "kwargs", dict, optional=True, doc="This field is empty for this batch."
             )
         ]
+
+    def kill(self, job):
+        """Kill the job.
+
+        If not implemented, pass and let the user manually kill it.
+
+        Parameters
+        ----------
+        job : Job
+            job
+        """
+        dlog.warning("Job %s should be manually killed" % job.job_id)
```

### Comparing `dpdispatcher-0.5.6/dpdispatcher/pbs.py` & `dpdispatcher-0.5.7/dpdispatcher/pbs.py`

 * *Files 2% similar despite different names*

```diff
@@ -42,16 +42,17 @@
         # script_str = self.sub_script(job_dirs, cmd, args=args, resources=resources, outlog=outlog, errlog=errlog)
         self.context.write_file(fname=script_file_name, write_str=script_str)
         # self.context.write_file(fname=os.path.join(self.context.submission.work_base, script_file_name), write_str=script_str)
         # script_file_dir = os.path.join(self.context.submission.work_base)
         script_file_dir = self.context.remote_root
         # stdin, stdout, stderr = self.context.block_checkcall('cd %s && %s %s' % (self.context.remote_root, 'qsub', script_file_name))
         stdin, stdout, stderr = self.context.block_checkcall(
-            "cd %s && %s %s"
-            % (shlex.quote(script_file_dir), "qsub", shlex.quote(script_file_name))
+            "cd {} && {} {}".format(
+                shlex.quote(script_file_dir), "qsub", shlex.quote(script_file_name)
+            )
         )
         subret = stdout.readlines()
         job_id = subret[0].split()[0]
         self.context.write_file(job_id_name, job_id)
         return job_id
 
     def default_resources(self, resources):
@@ -90,14 +91,25 @@
         else:
             return JobStatus.unknown
 
     def check_finish_tag(self, job):
         job_tag_finished = job.job_hash + "_job_tag_finished"
         return self.context.check_file_exists(job_tag_finished)
 
+    def kill(self, job):
+        """Kill the job.
+
+        Parameters
+        ----------
+        job : Job
+            job
+        """
+        job_id = job.job_id
+        ret, stdin, stdout, stderr = self.context.block_call("qdel " + str(job_id))
+
 
 class Torque(PBS):
     def check_status(self, job):
         job_id = job.job_id
         if job_id == "":
             return JobStatus.unsubmitted
         ret, stdin, stdout, stderr = self.context.block_call("qstat -l " + job_id)
```

### Comparing `dpdispatcher-0.5.6/dpdispatcher/shell.py` & `dpdispatcher-0.5.7/dpdispatcher/shell.py`

 * *Files 10% similar despite different names*

```diff
@@ -21,16 +21,15 @@
     def do_submit(self, job):
         script_str = self.gen_script(job)
         script_file_name = job.script_file_name
         job_id_name = job.job_hash + "_job_id"
         output_name = job.job_hash + ".out"
         self.context.write_file(fname=script_file_name, write_str=script_str)
         ret, stdin, stdout, stderr = self.context.block_call(
-            "cd %s && { nohup bash %s 1>>%s 2>>%s & } && echo $!"
-            % (
+            "cd {} && {{ nohup bash {} 1>>{} 2>>{} & }} && echo $!".format(
                 shlex.quote(self.context.remote_root),
                 script_file_name,
                 output_name,
                 output_name,
             )
         )
         if ret != 0:
@@ -62,15 +61,15 @@
         # print('shell.check_status.job_id', job_id)
         # job_state = JobStatus.unknown
         if job_id == "":
             return JobStatus.unsubmitted
 
         # mark defunct process as terminated
         ret, stdin, stdout, stderr = self.context.block_call(
-            f"if ps -p {job_id} > /dev/null && ! (ps -p {job_id} | grep defunct >/dev/null) ; then echo 1; fi"
+            f"if ps -p {job_id} > /dev/null && ! (ps -o command -p {job_id} | grep defunct >/dev/null) ; then echo 1; fi"
         )
         if ret != 0:
             err_str = stderr.read().decode("utf-8")
             raise RuntimeError(
                 "status command squeue fails to execute\nerror message:%s\nreturn code %d\n"
                 % (err_str, ret)
             )
@@ -97,7 +96,19 @@
     #             return True
     #     return False
 
     def check_finish_tag(self, job):
         job_tag_finished = job.job_hash + "_job_tag_finished"
         # print('job finished: ',job.job_id, job_tag_finished)
         return self.context.check_file_exists(job_tag_finished)
+
+    def kill(self, job):
+        """Kill the job.
+
+        Parameters
+        ----------
+        job : Job
+            job
+        """
+        job_id = job.job_id
+        # 9 means exit, cannot be blocked
+        ret, stdin, stdout, stderr = self.context.block_call("kill -9 " + str(job_id))
```

### Comparing `dpdispatcher-0.5.6/dpdispatcher/slurm.py` & `dpdispatcher-0.5.7/dpdispatcher/slurm.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,7 +1,8 @@
+import math
 import pathlib
 import shlex
 from typing import List
 
 from dargs import Argument
 
 from dpdispatcher import dlog
@@ -41,31 +42,33 @@
             script_header_dict[
                 "slurm_number_gpu_line"
             ] = "#SBATCH --gres=gpu:{gpu_per_node}".format(
                 gpu_per_node=resources.gpu_per_node
             )
         else:
             script_header_dict["slurm_number_gpu_line"] = custom_gpu_line
-        script_header_dict[
-            "slurm_partition_line"
-        ] = f"#SBATCH --partition {resources.queue_name}"
+        if resources.queue_name != "":
+            script_header_dict[
+                "slurm_partition_line"
+            ] = f"#SBATCH --partition {resources.queue_name}"
+        else:
+            script_header_dict["slurm_partition_line"] = ""
         slurm_script_header = slurm_script_header_template.format(**script_header_dict)
         return slurm_script_header
 
     @retry()
     def do_submit(self, job):
         script_file_name = job.script_file_name
         script_str = self.gen_script(job)
         job_id_name = job.job_hash + "_job_id"
         # script_str = self.sub_script(job_dirs, cmd, args=args, resources=resources, outlog=outlog, errlog=errlog)
         self.context.write_file(fname=script_file_name, write_str=script_str)
         # self.context.write_file(fname=os.path.join(self.context.submission.work_base, script_file_name), write_str=script_str)
         ret, stdin, stdout, stderr = self.context.block_call(
-            "cd %s && %s %s"
-            % (
+            "cd {} && {} {}".format(
                 shlex.quote(self.context.remote_root),
                 "sbatch",
                 shlex.quote(script_file_name),
             )
         )
         if ret != 0:
             err_str = stderr.read().decode("utf-8")
@@ -74,15 +77,20 @@
                 or "Unable to contact slurm controller" in err_str
             ):
                 # server network error, retry 3 times
                 raise RetrySignal(
                     "Get error code %d in submitting through ssh with job: %s . message: %s"
                     % (ret, job.job_hash, err_str)
                 )
-            elif "Job violates accounting/QOS policy" in err_str:
+            elif (
+                "Job violates accounting/QOS policy" in err_str
+                # the number of jobs exceeds DEFAULT_MAX_JOB_COUNT (by default 10000)
+                or "Slurm temporarily unable to accept job, sleeping and retrying"
+                in err_str
+            ):
                 # job number exceeds, skip the submitting
                 return ""
             raise RuntimeError(
                 "status command squeue fails to execute\nerror message:%s\nreturn code %d\n"
                 % (err_str, ret)
             )
         subret = stdout.readlines()
@@ -111,14 +119,15 @@
                     dlog.info(f"job: {job.job_hash} {job.job_id} finished")
                     return JobStatus.finished
                 else:
                     return JobStatus.terminated
             elif (
                 "Socket timed out on send/recv operation" in err_str
                 or "Unable to contact slurm controller" in err_str
+                or "Invalid user for SlurmUser" in err_str
             ):
                 # retry 3 times
                 raise RetrySignal(
                     "Get error code %d in checking status through ssh with job: %s . message: %s"
                     % (ret, job.job_hash, err_str)
                 )
             raise RuntimeError(
@@ -190,38 +199,55 @@
                     )
                 ],
                 optional=True,
                 doc="Extra arguments.",
             )
         ]
 
+    def kill(self, job):
+        """Kill the job.
+
+        Parameters
+        ----------
+        job : Job
+            job
+        """
+        job_id = job.job_id
+        # -Q Do not report an error if the specified job is already completed.
+        ret, stdin, stdout, stderr = self.context.block_call(
+            "scancel -Q " + str(job_id)
+        )
+        # we do not need to stop here if scancel failed; just continue
+
 
 class SlurmJobArray(Slurm):
     """Slurm with job array enabled for multiple tasks in a job."""
 
     def gen_script_header(self, job):
+        slurm_job_size = job.resources.kwargs.get("slurm_job_size", 1)
         if job.fail_count > 0:
             # resubmit jobs, check if some of tasks have been finished
-            job_array = []
+            job_array = set()
             for ii, task in enumerate(job.job_task_list):
                 task_tag_finished = (
                     pathlib.PurePath(task.task_work_path)
                     / (task.task_hash + "_task_tag_finished")
                 ).as_posix()
                 if not self.context.check_file_exists(task_tag_finished):
-                    job_array.append(ii)
+                    job_array.add(ii // slurm_job_size)
             return super().gen_script_header(job) + "\n#SBATCH --array=%s" % (
                 ",".join(map(str, job_array))
             )
         return super().gen_script_header(job) + "\n#SBATCH --array=0-%d" % (
-            len(job.job_task_list) - 1
+            math.ceil(len(job.job_task_list) / slurm_job_size) - 1
         )
 
     def gen_script_command(self, job):
         resources = job.resources
+        slurm_job_size = resources.kwargs.get("slurm_job_size", 1)
         # SLURM_ARRAY_TASK_ID: 0 ~ n_jobs-1
         script_command = "case $SLURM_ARRAY_TASK_ID in\n"
         for ii, task in enumerate(job.job_task_list):
             command_env = ""
             command_env += self.gen_command_env_cuda_devices(resources=resources)
 
             task_tag_finished = task.task_hash + "_task_tag_finished"
@@ -239,18 +265,24 @@
                 task_work_path=shlex.quote(
                     pathlib.PurePath(task.task_work_path).as_posix()
                 ),
                 command=task.command,
                 task_tag_finished=task_tag_finished,
                 log_err_part=log_err_part,
             )
-            script_command += f"{ii})\n"
+            if ii % slurm_job_size == 0:
+                script_command += f"{ii // slurm_job_size})\n"
             script_command += single_script_command
             script_command += self.gen_script_wait(resources=resources)
-            script_command += "\n;;\n"
+            script_command += "\n"
+            if (
+                ii % slurm_job_size == slurm_job_size - 1
+                or ii == len(job.job_task_list) - 1
+            ):
+                script_command += ";;\n"
         script_command += "*)\nexit 1\n;;\nesac\n"
         return script_command
 
     def gen_script_end(self, job):
         # We cannot have a end script for job array
         # we may check task tag instead
         return ""
@@ -333,13 +365,34 @@
                 return JobStatus.finished
             else:
                 return JobStatus.terminated
 
     def check_finish_tag(self, job):
         results = []
         for task in job.job_task_list:
-            task_tag_finished = (
-                pathlib.PurePath(task.task_work_path)
-                / (task.task_hash + "_task_tag_finished")
-            ).as_posix()
-            results.append(self.context.check_file_exists(task_tag_finished))
+            task.get_task_state(self.context)
+            results.append(task.task_state == JobStatus.finished)
         return all(results)
+
+    @classmethod
+    def resources_subfields(cls) -> List[Argument]:
+        """Generate the resources subfields.
+
+        Returns
+        -------
+        list[Argument]
+            resources subfields
+        """
+        doc_slurm_job_size = "Number of tasks in a Slurm job"
+        arg = super().resources_subfields()[0]
+        arg.extend_subfields(
+            [
+                Argument(
+                    "slurm_job_size",
+                    int,
+                    optional=True,
+                    default=1,
+                    doc=doc_slurm_job_size,
+                ),
+            ]
+        )
+        return [arg]
```

### Comparing `dpdispatcher-0.5.6/dpdispatcher/ssh_context.py` & `dpdispatcher-0.5.7/dpdispatcher/ssh_context.py`

 * *Files 2% similar despite different names*

```diff
@@ -112,15 +112,15 @@
     #     self.ssh.connect(hostname=hostname, port=port,
     #                      username=username, password=password,
     #                      key_filename=key_filename, timeout=timeout, passphrase=passphrase)
     #     assert(self.ssh.get_transport().is_active())
     #     transport = self.ssh.get_transport()
     #     transport.set_keepalive(60)
 
-    @retry(max_retry=3, sleep=1)
+    @retry(max_retry=6, sleep=1)
     def _setup_ssh(self):
         # machine = self.machine
         self.ssh = paramiko.SSHClient()
         self.ssh.set_missing_host_key_policy(paramiko.AutoAddPolicy)
         # if self.totp_secret and self.password is None:
         #     self.password = generate_totp(self.totp_secret)
         # self.ssh.connect(hostname=self.hostname, port=self.port,
@@ -195,29 +195,34 @@
             else:
                 key_ok = True
         if self.totp_secret is not None:
             try:
                 ts.auth_interactive(self.username, self.inter_handler)
             except paramiko.ssh_exception.AuthenticationException:
                 # since the asynchrony of interactive authentication, one addtional try is added
-                # retry for up to 3 times
+                # retry for up to 6 times
                 raise RetrySignal("Authentication failed")
         elif key_ok:
             pass
         elif self.password is not None:
             ts.auth_password(self.username, self.password)
         elif key_error is not None:
             raise RuntimeError(
                 "Authentication failed, try to provide password"
             ) from key_error
         else:
             raise RuntimeError("Please provide at least one form of authentication")
         assert ts.is_active()
         # Opening a session creates a channel along the socket to the server
-        ts.open_session(timeout=self.timeout)
+        try:
+            ts.open_session(timeout=self.timeout)
+        except paramiko.ssh_exception.SSHException:
+            # retry for up to 6 times
+            # ref: https://github.com/paramiko/paramiko/issues/1508
+            raise RetrySignal("Opening session failed")
         ts.set_keepalive(60)
         self.ssh._transport = ts  # type: ignore
         # reset sftp
         self._sftp = None
 
     def inter_handler(self, title, instructions, prompt_list):
         """inter_handler: the callback for paramiko.transport.auth_interactive.
@@ -319,22 +324,22 @@
         ssh_remote_profile_args = [
             Argument("hostname", str, optional=False, doc=doc_hostname),
             Argument("username", str, optional=False, doc=doc_username),
             Argument("password", str, optional=True, doc=doc_password),
             Argument("port", int, optional=True, default=22, doc=doc_port),
             Argument(
                 "key_filename",
-                [str, None],
+                [str, type(None)],
                 optional=True,
                 default=None,
                 doc=doc_key_filename,
             ),
             Argument(
                 "passphrase",
-                [str, None],
+                [str, type(None)],
                 optional=True,
                 default=None,
                 doc=doc_passphrase,
             ),
             Argument("timeout", int, optional=True, default=10, doc=doc_timeout),
             Argument(
                 "totp_secret", str, optional=True, default=None, doc=doc_totp_secret
@@ -493,14 +498,22 @@
             and old_remote_root != self.remote_root
             and self.check_file_exists(old_remote_root)
             and not self.check_file_exists(self.remote_root)
         ):
             self.block_checkcall(
                 f"mv {shlex.quote(old_remote_root)} {shlex.quote(self.remote_root)}"
             )
+        elif (
+            old_remote_root is not None
+            and old_remote_root != self.remote_root
+            and self.check_file_exists(old_remote_root)
+            and not len(self.ssh_session.sftp.listdir(old_remote_root))
+        ):
+            # if the new directory exists and the old directory does not contain files, then move the old directory
+            self._rmtree(old_remote_root)
 
         sftp = self.ssh_session.ssh.open_sftp()
         try:
             sftp.mkdir(self.remote_root)
         except OSError:
             pass
 
@@ -758,20 +771,14 @@
     def get_return(self, cmd_pipes):
         if not self.check_finish(cmd_pipes):
             return None, None, None
         else:
             retcode = cmd_pipes["stdout"].channel.recv_exit_status()
             return retcode, cmd_pipes["stdout"], cmd_pipes["stderr"]
 
-    def kill(self, cmd_pipes):
-        raise RuntimeError(
-            "dose not work! we do not know how to kill proc through paramiko.SSHClient"
-        )
-        # self.block_checkcall('kill -15 %s' % cmd_pipes['pid'])
-
     def _rmtree(self, remotepath, verbose=False):
         """Remove the remote path."""
         # The original implementation method removes files one by one using sftp.
         # If the latency of the remote server is high, it is very slow.
         # Thus, it's better to use system's `rm` to remove a directory, which may
         # save a lot of time.
         if verbose:
@@ -843,16 +850,15 @@
         # trans
         from_f = pathlib.PurePath(os.path.join(self.local_root, of)).as_posix()
         to_f = pathlib.PurePath(os.path.join(self.remote_root, of)).as_posix()
         try:
             self.ssh_session.put(from_f, to_f)
         except FileNotFoundError:
             raise FileNotFoundError(
-                "from %s to %s @ %s : %s Error!"
-                % (from_f, self.ssh_session.username, self.ssh_session.hostname, to_f)
+                f"from {from_f} to {self.ssh_session.username} @ {self.ssh_session.hostname} : {to_f} Error!"
             )
         # remote extract
         self.block_checkcall("tar xf %s" % of)
         # clean up
         os.remove(from_f)
         self.sftp.remove(to_f)
 
@@ -873,29 +879,27 @@
         # remote tar
         # If the number of files are large, we may get "Argument list too long" error.
         # Thus, "-T" accepts a file containing the list of files
         per_nfile = 100
         ntar = len(files) // per_nfile + 1
         if ntar <= 1:
             self.block_checkcall(
-                "tar %s %s %s"
-                % (
+                "tar {} {} {}".format(
                     tar_command,
                     shlex.quote(of),
                     " ".join([shlex.quote(file) for file in files]),
                 )
             )
         else:
             file_list_file = os.path.join(
                 self.remote_root, ".tmp.tar." + str(uuid.uuid4())
             )
             self.write_file(file_list_file, "\n".join(files))
             self.block_checkcall(
-                "tar %s %s -T %s"
-                % (tar_command, shlex.quote(of), shlex.quote(file_list_file))
+                f"tar {tar_command} {shlex.quote(of)} -T {shlex.quote(file_list_file)}"
             )
         # trans
         from_f = pathlib.PurePath(os.path.join(self.remote_root, of)).as_posix()
         to_f = pathlib.PurePath(os.path.join(self.local_root, of)).as_posix()
         if os.path.isfile(to_f):
             os.remove(to_f)
         self.ssh_session.get(from_f, to_f)
```

### Comparing `dpdispatcher-0.5.6/dpdispatcher/submission.py` & `dpdispatcher-0.5.7/dpdispatcher/submission.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,12 @@
 # %%
 import copy
 import json
 import os
+import pathlib
 import random
 import time
 import uuid
 from hashlib import sha1
 
 from dargs.dargs import Argument, Variant
 
@@ -231,15 +232,15 @@
         ratio_unfinished = self.resources.strategy["ratio_unfinished"]
         while not self.check_all_finished():
             if exit_on_submit is True:
                 dlog.info(f"submission succeeded: {self.submission_hash}")
                 dlog.info(f"at {self.machine.context.remote_root}")
                 return self.serialize()
             if ratio_unfinished > 0.0 and self.check_ratio_unfinished(ratio_unfinished):
-                self.remove_unfinished_jobs()
+                self.remove_unfinished_tasks()
                 break
 
             try:
                 time.sleep(30)
             except (Exception, KeyboardInterrupt, SystemExit) as e:
                 self.submission_to_json()
                 dlog.exception(e)
@@ -302,49 +303,61 @@
     #     """
     #     for job in self.belonging_jobs:
     #         job.submit_job()
     #     self.get_submission_state()
 
     # def update_submi
 
-    def check_ratio_unfinished(self, ratio_unfinished):
-        status_list = [job.job_state for job in self.belonging_jobs]
-        finished_num = status_list.count(JobStatus.finished)
-        if finished_num / len(self.belonging_jobs) < (1 - ratio_unfinished):
-            return False
+    def check_ratio_unfinished(self, ratio_unfinished: float) -> bool:
+        """Calculate the ratio of unfinished tasks in the submission.
+
+        Parameters
+        ----------
+        ratio_unfinished : float
+            the ratio of unfinished tasks in the submission
+
+        Returns
+        -------
+        bool
+            whether the ratio of unfinished tasks in the submission is larger than ratio_unfinished
+        """
+        assert self.resources is not None
+        if self.resources.group_size == 1:
+            # if group size is 1, calculate job state is enough and faster
+            status_list = [job.job_state for job in self.belonging_jobs]
         else:
-            return True
+            # get task state is more accurate
+            status_list = []
+            for task in self.belonging_tasks:
+                task.get_task_state(self.machine.context)
+                status_list.append(task.task_state)
+        finished_num = status_list.count(JobStatus.finished)
+        return finished_num / len(self.belonging_tasks) >= (1 - ratio_unfinished)
 
-    def remove_unfinished_jobs(self):
-        removed_jobs = [
-            job
-            for job in self.belonging_jobs
-            if job.job_state not in [JobStatus.finished]
-        ]
-        self.belonging_jobs = [
-            job for job in self.belonging_jobs if job.job_state in [JobStatus.finished]
-        ]
-        for job in removed_jobs:
-            # kill unfinished jobs
-            try:
-                self.machine.context.kill(job.job_id)
-            except Exception as e:
-                dlog.info("Can not kill job %s" % job.job_id)
-
-            # remove unfinished tasks
-            import os
-            import shutil
-
-            for task in job.job_task_list:
-                shutil.rmtree(
-                    os.path.join(self.machine.context.local_root, task.task_work_path),
-                    ignore_errors=True,
-                )
-            self.belonging_tasks = [
-                task for task in self.belonging_tasks if task not in job.job_task_list
+    def remove_unfinished_tasks(self):
+        dlog.info("Remove unfinished tasks")
+        # kill all jobs and mark them as finished
+        for job in self.belonging_jobs:
+            if job.job_state != JobStatus.finished:
+                self.machine.kill(job)
+                job.job_state = JobStatus.finished
+        # remove all unfinished tasks
+        finished_tasks = []
+        for task in self.belonging_tasks:
+            if task.task_state == JobStatus.finished:
+                finished_tasks.append(task)
+            # there is no need to remove actual remote directory
+            # as it should be cleaned anyway
+        self.belonging_tasks = finished_tasks
+        # clean removed tasks in jobs - although this should not be necessary
+        for job in self.belonging_jobs:
+            job.job_task_list = [
+                task
+                for task in job.job_task_list
+                if task.task_state == JobStatus.finished
             ]
 
     def check_all_finished(self):
         """Check whether all the jobs in the submission.
 
         Notes
         -----
@@ -459,14 +472,17 @@
                 fname=submission_file_name
             )
             submission_dict = json.loads(submission_dict_str)
             submission = Submission.deserialize(submission_dict=submission_dict)
             submission.bind_machine(machine=self.machine)
             if self == submission:
                 self.belonging_jobs = submission.belonging_jobs
+                self.belonging_tasks = [
+                    task for job in self.belonging_jobs for task in job.job_task_list
+                ]
                 self.bind_machine(machine=self.machine)
                 dlog.info(
                     f"Find old submission; recover submission from json file;"
                     f"submission.submission_hash:{submission.submission_hash}; "
                     f"machine.context.remote_root:{self.machine.context.remote_root}; "
                     f"submission.work_base:{submission.work_base};"
                 )
@@ -514,14 +530,15 @@
         self.errlog = errlog
 
         # self.task_need_resources = task_need_resources
 
         self.task_hash = self.get_hash()
         # self.task_need_resources="<to be completed in the future>"
         # self.uuid =
+        self.task_state = JobStatus.unsubmitted
 
     def __repr__(self):
         return str(self.serialize())
 
     def __eq__(self, other):
         return json.dumps(self.serialize()) == json.dumps(other.serialize())
 
@@ -598,23 +615,52 @@
                 "backward_files",
                 list,
                 optional=False,
                 doc=doc_backward_files,
                 default=[],
             ),
             Argument(
-                "outlog", [None, str], optional=False, doc=doc_outlog, default="log"
+                "outlog",
+                [type(None), str],
+                optional=False,
+                doc=doc_outlog,
+                default="log",
             ),
             Argument(
-                "errlog", [None, str], optional=False, doc=doc_errlog, default="err"
+                "errlog",
+                [type(None), str],
+                optional=False,
+                doc=doc_errlog,
+                default="err",
             ),
         ]
         task_format = Argument("task", dict, task_args)
         return task_format
 
+    def get_task_state(self, context):
+        """Get the task state by checking the tag file.
+
+        Parameters
+        ----------
+        context : Context
+            the context of the task
+        """
+        if self.task_state in (JobStatus.finished, JobStatus.unsubmitted):
+            # finished task should always be finished
+            # unsubmitted task do not need to check tag
+            return
+        # check tag
+        task_tag_finished = (
+            pathlib.PurePath(self.task_work_path)
+            / (self.task_hash + "_task_tag_finished")
+        ).as_posix()
+        result = context.check_file_exists(task_tag_finished)
+        if result:
+            self.task_state = JobStatus.finished
+
 
 class Job:
     """Job is generated by Submission automatically.
     A job ususally has many tasks and it may request computing resources from job scheduler systems.
     Each Job can generate a script file to be submitted to the job scheduler system or executed locally.
 
     Parameters
@@ -696,14 +742,16 @@
         )
 
         # job.job_runtime_info=job_dict[job_hash]['job_runtime_info']
         job.job_state = job_dict[job_hash]["job_state"]
         job.job_id = job_dict[job_hash]["job_id"]
         job.fail_count = job_dict[job_hash]["fail_count"]
         # job.job_uuid = job_dict[job_hash]['job_uuid']
+        for task in job.job_task_list:
+            task.task_state = job.job_state
         return job
 
     def get_job_state(self):
         """Get the jobs. Usually, this method will query the database of slurm or pbs job scheduler system and get the results.
 
         Notes
         -----
@@ -711,14 +759,19 @@
         """
         dlog.debug(
             f"debug:query database; self.job_hash:{self.job_hash}; self.job_id:{self.job_id}"
         )
         assert self.machine is not None
         job_state = self.machine.check_status(self)
         self.job_state = job_state
+        # update general task_state, which should be faster than checking tags
+        for task in self.job_task_list:
+            # only update if the task is not finished
+            if task.task_state != JobStatus.finished:
+                task.task_state = job_state
 
     def handle_unexpected_job_state(self):
         job_state = self.job_state
 
         if job_state == JobStatus.unknown:
             raise RuntimeError(f"job_state for job {self} is unknown")
 
@@ -834,15 +887,15 @@
     strategy : dict
         strategies we use to generation job submitting scripts.
         if_cuda_multi_devices : bool
             If there are multiple nvidia GPUS on the node, and we want to assign the tasks to different GPUS.
             If true, dpdispatcher will manually export environment variable CUDA_VISIBLE_DEVICES to different task.
             Usually, this option will be used with Task.task_need_resources variable simultaneously.
         ratio_unfinished : float
-            The ratio of `jobs` that can be unfinished.
+            The ratio of `task` that can be unfinished.
     para_deg : int
         Decide how many tasks will be run in parallel.
         Usually run with `strategy['if_cuda_multi_devices']`
     source_list : list of Path
         The env file to be sourced before the command execution.
     wait_time : int
         The waitting time in second after a single task submitted. Default: 0.
@@ -1006,15 +1059,15 @@
         doc_append_script = "Optional script run after jobs submitted."
         doc_wait_time = "The waitting time in second after a single `task` submitted"
         doc_if_cuda_multi_devices = (
             "If there are multiple nvidia GPUS on the node, and we want to assign the tasks to different GPUS."
             "If true, dpdispatcher will manually export environment variable CUDA_VISIBLE_DEVICES to different task."
             "Usually, this option will be used with Task.task_need_resources variable simultaneously."
         )
-        doc_ratio_unfinished = "The ratio of `jobs` that can be unfinished."
+        doc_ratio_unfinished = "The ratio of `tasks` that can be unfinished."
 
         strategy_args = [
             Argument(
                 "if_cuda_multi_devices",
                 bool,
                 optional=True,
                 default=False,
```

### Comparing `dpdispatcher-0.5.6/dpdispatcher/utils.py` & `dpdispatcher-0.5.7/dpdispatcher/utils.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/dpdispatcher.egg-info/PKG-INFO` & `dpdispatcher-0.5.7/dpdispatcher.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: dpdispatcher
-Version: 0.5.6
+Version: 0.5.7
 Summary: Generate HPC scheduler systems jobs input scripts, submit these scripts to HPC systems, and poke until they finish
 Author: DeepModeling
 License:                    GNU LESSER GENERAL PUBLIC LICENSE
                                Version 3, 29 June 2007
         
          Copyright (C) 2007 Free Software Foundation, Inc. <https://fsf.org/>
          Everyone is permitted to copy and distribute verbatim copies
@@ -187,29 +187,38 @@
 Provides-Extra: docs
 Provides-Extra: cloudserver
 Provides-Extra: test
 License-File: LICENSE
 
 # DPDispatcher
 
-DPDispatcher is a python package used to generate HPC(High Performance Computing) scheduler systems (Slurm/PBS/LSF/dpcloudserver) jobs input scripts and submit these  scripts to HPC systems and poke until they finish.
+[![conda-forge](https://img.shields.io/conda/dn/conda-forge/dpdispatcher?color=red&label=conda-forge&logo=conda-forge)](https://anaconda.org/conda-forge/dpdispatcher)
+[![pip install](https://img.shields.io/pypi/dm/dpdispatcher?label=pip%20install&logo=pypi)](https://pypi.org/project/dpdispatcher)
+[![docker pull](https://img.shields.io/docker/pulls/dptechnology/dpdispatcher?logo=docker)](https://hub.docker.com/r/dptechnology/dpdispatcher)
+[![Documentation Status](https://readthedocs.org/projects/dpdispatcher/badge/)](https://dpdispatcher.readthedocs.io/)
+
+DPDispatcher is a Python package used to generate HPC (High-Performance Computing) scheduler systems (Slurm/PBS/LSF/Bohrium) jobs input scripts, submit them to HPC systems, and poke until they finish.
 ​
-DPDispatcher will monitor (poke) until these jobs finish and download the results files (if these jobs is running on remote systems connected by SSH).
+DPDispatcher will monitor (poke) until these jobs finish and download the results files (if these jobs are running on remote systems connected by SSH).
 
 For more information, check the [documentation](https://dpdispatcher.readthedocs.io/).
 
 ## Installation
 
-DPDispatcher can installed by `pip`:
+DPDispatcher can be installed by `pip`:
 
 ```bash
 pip install dpdispatcher
 ```
 
 ## Usage
 
 See [Getting Started](https://dpdispatcher.readthedocs.io/en/latest/getting-started.html) for usage.
 
 ## Contributing
 
-DPDispatcher is maintained by Deep Modeling's developers and welcome other people.
+DPDispatcher is maintained by Deep Modeling's developers and welcomes other people.
 See [Contributing Guide](CONTRIBUTING.md) to become a contributor! 🤓
+
+## References
+
+DPDispatcher is derivated from the [DP-GEN](https://github.com/deepmodeling/dpgen) package. To mention DPDispatcher in a scholarly publication, please read Section 3.3 in the [DP-GEN paper](https://doi.org/10.1016/j.cpc.2020.107206).
```

### Comparing `dpdispatcher-0.5.6/dpdispatcher.egg-info/SOURCES.txt` & `dpdispatcher-0.5.7/dpdispatcher.egg-info/SOURCES.txt`

 * *Files 1% similar despite different names*

```diff
@@ -116,14 +116,15 @@
 tests/test_hdfs_context.py
 tests/test_import_classes.py
 tests/test_lazy_local_context.py
 tests/test_local_context.py
 tests/test_lsf_script_generation.py
 tests/test_retry.py
 tests/test_run_submission.py
+tests/test_run_submission_ratio_unfinished.py
 tests/test_shell_cuda_multi_devices.py
 tests/test_shell_trival.py
 tests/test_slurm_script_generation.py
 tests/test_ssh_context.py
 tests/jsons/job.json
 tests/jsons/machine.json
 tests/jsons/machine_ali_ehpc.json
```

### Comparing `dpdispatcher-0.5.6/examples/resources/expanse_cpu.json` & `dpdispatcher-0.5.7/examples/resources/expanse_cpu.json`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/pyproject.toml` & `dpdispatcher-0.5.7/pyproject.toml`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/scripts/script_gen_dargs_docs.py` & `dpdispatcher-0.5.7/scripts/script_gen_dargs_docs.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/context.py` & `dpdispatcher-0.5.7/tests/context.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/debug_test_class_submission_init.py` & `dpdispatcher-0.5.7/tests/debug_test_class_submission_init.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/devel_test_ali_ehpc.py` & `dpdispatcher-0.5.7/tests/devel_test_ali_ehpc.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/devel_test_dp_cloud_server.py` & `dpdispatcher-0.5.7/tests/devel_test_dp_cloud_server.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/devel_test_lazy_ali_ehpc.py` & `dpdispatcher-0.5.7/tests/devel_test_lazy_ali_ehpc.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/devel_test_lsf.py` & `dpdispatcher-0.5.7/tests/devel_test_lsf.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/devel_test_shell.py` & `dpdispatcher-0.5.7/tests/devel_test_shell.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/devel_test_slurm.py` & `dpdispatcher-0.5.7/tests/devel_test_slurm.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/devel_test_ssh_ali_ehpc.py` & `dpdispatcher-0.5.7/tests/devel_test_ssh_ali_ehpc.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/jsons/job.json` & `dpdispatcher-0.5.7/tests/jsons/job.json`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/jsons/machine_center.json` & `dpdispatcher-0.5.7/tests/jsons/machine_center.json`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/jsons/machine_diffenert.json` & `dpdispatcher-0.5.7/tests/jsons/machine_diffenert.json`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/jsons/machine_dp_cloud_server.json` & `dpdispatcher-0.5.7/tests/jsons/machine_dp_cloud_server.json`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/jsons/machine_lazy_local_lsf.json` & `dpdispatcher-0.5.7/tests/jsons/machine_lazy_local_lsf.json`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/jsons/machine_lazy_local_slurm.json` & `dpdispatcher-0.5.7/tests/jsons/machine_lazy_local_slurm.json`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/jsons/machine_lsf.json` & `dpdispatcher-0.5.7/tests/jsons/machine_lsf.json`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/jsons/machine_slurm.json` & `dpdispatcher-0.5.7/tests/jsons/machine_slurm.json`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/jsons/machine_yarn.json` & `dpdispatcher-0.5.7/tests/jsons/machine_yarn.json`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/jsons/submission.json` & `dpdispatcher-0.5.7/tests/jsons/submission.json`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/lsf/context.py` & `dpdispatcher-0.5.7/tests/lsf/context.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/lsf/test_dispatcher.py` & `dpdispatcher-0.5.7/tests/lsf/test_dispatcher.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/lsf/test_lsf_local.py` & `dpdispatcher-0.5.7/tests/lsf/test_lsf_local.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/old/test_dispatcher_utils.py` & `dpdispatcher-0.5.7/tests/old/test_dispatcher_utils.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/old/test_lazy_local_context.py` & `dpdispatcher-0.5.7/tests/old/test_lazy_local_context.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/old/test_local_context.py` & `dpdispatcher-0.5.7/tests/old/test_local_context.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/old/test_ssh_context.py` & `dpdispatcher-0.5.7/tests/old/test_ssh_context.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/pbs/context.py` & `dpdispatcher-0.5.7/tests/pbs/context.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/pbs/test_dispatcher.py` & `dpdispatcher-0.5.7/tests/pbs/test_dispatcher.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/pbs/test_pbs_local.py` & `dpdispatcher-0.5.7/tests/pbs/test_pbs_local.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/sample_class.py` & `dpdispatcher-0.5.7/tests/sample_class.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/script_gen_json.py` & `dpdispatcher-0.5.7/tests/script_gen_json.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/shell/context.py` & `dpdispatcher-0.5.7/tests/shell/context.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/shell/test_dispatcher.py` & `dpdispatcher-0.5.7/tests/shell/test_dispatcher.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/shell/test_shell_local.py` & `dpdispatcher-0.5.7/tests/shell/test_shell_local.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/shell/test_shell_ssh.py` & `dpdispatcher-0.5.7/tests/shell/test_shell_ssh.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/slurm/context.py` & `dpdispatcher-0.5.7/tests/slurm/context.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/slurm/test_dispatcher.py` & `dpdispatcher-0.5.7/tests/slurm/test_dispatcher.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/slurm/test_dispatcher_lazy_local.py` & `dpdispatcher-0.5.7/tests/slurm/test_dispatcher_lazy_local.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/slurm/test_slurm_lazy_local.py` & `dpdispatcher-0.5.7/tests/slurm/test_slurm_lazy_local.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/slurm/test_slurm_local.py` & `dpdispatcher-0.5.7/tests/slurm/test_slurm_local.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/slurm/test_slurm_ssh.py` & `dpdispatcher-0.5.7/tests/slurm/test_slurm_ssh.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_argcheck.py` & `dpdispatcher-0.5.7/tests/test_argcheck.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_class_job.py` & `dpdispatcher-0.5.7/tests/test_class_job.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_class_machine.py` & `dpdispatcher-0.5.7/tests/test_class_machine.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_class_machine_dispatch.py` & `dpdispatcher-0.5.7/tests/test_class_machine_dispatch.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_class_resources.py` & `dpdispatcher-0.5.7/tests/test_class_resources.py`

 * *Files 5% similar despite different names*

```diff
@@ -38,10 +38,13 @@
 
     def test_resources_json(self):
         with open("jsons/resources.json") as f:
             resources_json_dict = json.load(f)
         self.assertTrue(resources_json_dict, self.resources_dict)
         self.assertTrue(resources_json_dict, self.resources.serialize())
 
+    def test_arginfo(self):
+        self.resources.arginfo()
+
     def test_load_from_json(self):
         resources = Resources.load_from_json("jsons/resources.json")
         self.assertTrue(resources, self.resources)
```

### Comparing `dpdispatcher-0.5.6/tests/test_class_submission.py` & `dpdispatcher-0.5.7/tests/test_class_submission.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_class_submission_init.py` & `dpdispatcher-0.5.7/tests/test_class_submission_init.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_class_task.py` & `dpdispatcher-0.5.7/tests/test_class_task.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_context_dir/0_md/bct-1/input.lammps` & `dpdispatcher-0.5.7/tests/test_context_dir/0_md/bct-1/input.lammps`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_context_dir/0_md/bct-2/input.lammps` & `dpdispatcher-0.5.7/tests/test_context_dir/0_md/bct-2/input.lammps`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_context_dir/0_md/bct-3/input.lammps` & `dpdispatcher-0.5.7/tests/test_context_dir/0_md/bct-3/input.lammps`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_context_dir/0_md/bct-4/input.lammps` & `dpdispatcher-0.5.7/tests/test_context_dir/0_md/bct-4/input.lammps`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_group_size.py` & `dpdispatcher-0.5.7/tests/test_group_size.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_hdfs_context.py` & `dpdispatcher-0.5.7/tests/test_hdfs_context.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_hdfs_dir/0_md/bct-1/input.lammps` & `dpdispatcher-0.5.7/tests/test_hdfs_dir/0_md/bct-1/input.lammps`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_hdfs_dir/0_md/bct-2/input.lammps` & `dpdispatcher-0.5.7/tests/test_hdfs_dir/0_md/bct-2/input.lammps`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_hdfs_dir/0_md/bct-3/input.lammps` & `dpdispatcher-0.5.7/tests/test_hdfs_dir/0_md/bct-3/input.lammps`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_hdfs_dir/0_md/bct-4/input.lammps` & `dpdispatcher-0.5.7/tests/test_hdfs_dir/0_md/bct-4/input.lammps`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_import_classes.py` & `dpdispatcher-0.5.7/tests/test_import_classes.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_lazy_local_context.py` & `dpdispatcher-0.5.7/tests/test_lazy_local_context.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_local_context.py` & `dpdispatcher-0.5.7/tests/test_local_context.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_lsf_dir/0_md/bct-1/input.lammps` & `dpdispatcher-0.5.7/tests/test_lsf_dir/0_md/bct-1/input.lammps`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_lsf_dir/0_md/bct-2/input.lammps` & `dpdispatcher-0.5.7/tests/test_lsf_dir/0_md/bct-2/input.lammps`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_lsf_dir/0_md/bct-3/input.lammps` & `dpdispatcher-0.5.7/tests/test_lsf_dir/0_md/bct-3/input.lammps`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_lsf_dir/0_md/bct-4/input.lammps` & `dpdispatcher-0.5.7/tests/test_lsf_dir/0_md/bct-4/input.lammps`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_lsf_dir/0_md/submission.json` & `dpdispatcher-0.5.7/tests/test_lsf_dir/0_md/submission.json`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_lsf_script_generation.py` & `dpdispatcher-0.5.7/tests/test_lsf_script_generation.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_pbs_dir/0_md/bct-1/input.lammps` & `dpdispatcher-0.5.7/tests/test_pbs_dir/0_md/bct-1/input.lammps`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_pbs_dir/0_md/bct-2/input.lammps` & `dpdispatcher-0.5.7/tests/test_pbs_dir/0_md/bct-2/input.lammps`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_pbs_dir/0_md/bct-3/input.lammps` & `dpdispatcher-0.5.7/tests/test_pbs_dir/0_md/bct-3/input.lammps`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_pbs_dir/0_md/bct-4/input.lammps` & `dpdispatcher-0.5.7/tests/test_pbs_dir/0_md/bct-4/input.lammps`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_retry.py` & `dpdispatcher-0.5.7/tests/test_retry.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_run_submission.py` & `dpdispatcher-0.5.7/tests/test_run_submission.py`

 * *Files 8% similar despite different names*

```diff
@@ -119,14 +119,26 @@
     def setUp(self):
         super().setUp()
         self.machine_dict["batch_type"] = "SlurmJobArray"
         self.resources_dict["queue_name"] = "normal"
 
 
 @unittest.skipIf(
+    os.environ.get("DPDISPATCHER_TEST") != "slurm",
+    "outside the slurm testing environment",
+)
+class TestSlurmJobArrayRun2(RunSubmission, unittest.TestCase):
+    def setUp(self):
+        super().setUp()
+        self.machine_dict["batch_type"] = "SlurmJobArray"
+        self.resources_dict["queue_name"] = "normal"
+        self.resources_dict["kwargs"] = {"slurm_job_size": 2}
+
+
+@unittest.skipIf(
     os.environ.get("DPDISPATCHER_TEST") != "pbs", "outside the pbs testing environment"
 )
 class TestPBSRun(RunSubmission, unittest.TestCase):
     def setUp(self):
         super().setUp()
         self.machine_dict["batch_type"] = "PBS"
         self.resources_dict["queue_name"] = "workq"
```

### Comparing `dpdispatcher-0.5.6/tests/test_shell_cuda_multi_devices.py` & `dpdispatcher-0.5.7/tests/test_shell_cuda_multi_devices.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_shell_trival.py` & `dpdispatcher-0.5.7/tests/test_shell_trival.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_slurm_dir/0_md/bct-1/input.lammps` & `dpdispatcher-0.5.7/tests/test_slurm_dir/0_md/bct-1/input.lammps`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_slurm_dir/0_md/bct-2/input.lammps` & `dpdispatcher-0.5.7/tests/test_slurm_dir/0_md/bct-2/input.lammps`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_slurm_dir/0_md/bct-3/input.lammps` & `dpdispatcher-0.5.7/tests/test_slurm_dir/0_md/bct-3/input.lammps`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_slurm_dir/0_md/bct-4/input.lammps` & `dpdispatcher-0.5.7/tests/test_slurm_dir/0_md/bct-4/input.lammps`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_slurm_dir/0_md/d3c842c5b9476e48f7145b370cd330372b9293e1.json` & `dpdispatcher-0.5.7/tests/test_slurm_dir/0_md/d3c842c5b9476e48f7145b370cd330372b9293e1.json`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_slurm_dir/0_md/submission.json` & `dpdispatcher-0.5.7/tests/test_slurm_dir/0_md/submission.json`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_slurm_script_generation.py` & `dpdispatcher-0.5.7/tests/test_slurm_script_generation.py`

 * *Files identical despite different names*

### Comparing `dpdispatcher-0.5.6/tests/test_ssh_context.py` & `dpdispatcher-0.5.7/tests/test_ssh_context.py`

 * *Files 17% similar despite different names*

```diff
@@ -32,14 +32,15 @@
             "remote_profile": {
                 "hostname": "server",
                 "port": 22,
                 "username": "root",
                 "key_filename": "/root/.ssh/id_rsa",
             },
         }
+        cls.mdata = mdata
         try:
             cls.machine = Machine.load_from_dict(mdata)
         except (SSHException, socket.timeout):
             raise unittest.SkipTest("SSHException ssh cannot connect")
         cls.submission = SampleClass.get_sample_submission()
         cls.submission.bind_machine(cls.machine)
         cls.submission_hash = cls.submission.submission_hash
@@ -109,14 +110,61 @@
             resources=resources,
             forward_common_files=[],
             backward_common_files=[],
             task_list=[task],
         )
         submission.run_submission()
 
+    def test_recover(self):
+        """Test recover from a previous submission."""
+        machine = Machine.load_from_dict(self.machine.serialize())
+        resources = Resources.load_from_dict(
+            {
+                "number_node": 1,
+                "cpu_per_node": 1,
+                "gpu_per_node": 0,
+                "queue_name": "?",
+                "group_size": 1,
+            }
+        )
+        task = Task(
+            command="touch times && echo 1 >> times && test $(wc -l < times) -gt 3 && echo done",
+            task_work_path="./",
+            forward_files=[],
+            backward_files=[],
+            outlog="out.txt",
+        )
+
+        submission = Submission(
+            work_base="./",
+            machine=machine,
+            resources=resources,
+            forward_common_files=[],
+            backward_common_files=[],
+            task_list=[task],
+        )
+        try:
+            submission.run_submission()
+        except RuntimeError:
+            # expected to fail, try again
+            # reinit machine to test machine recover
+            machine = Machine.load_from_dict(self.mdata)
+            resources = Resources.load_from_dict(resources.serialize())
+            task = Task.deserialize(task.serialize())
+
+            submission = Submission(
+                work_base="./",
+                machine=machine,
+                resources=resources,
+                forward_common_files=[],
+                backward_common_files=[],
+                task_list=[task],
+            )
+            submission.run_submission()
+
     def test_download(self):
         self.context.download(self.__class__.submission)
 
 
 @unittest.skipIf(
     os.environ.get("DPDISPATCHER_TEST") != "ssh", "outside the ssh testing environment"
 )
```


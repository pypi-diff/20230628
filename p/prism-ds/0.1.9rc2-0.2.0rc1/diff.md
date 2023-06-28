# Comparing `tmp/prism-ds-0.1.9rc2.tar.gz` & `tmp/prism-ds-0.2.0rc1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "prism-ds-0.1.9rc2.tar", last modified: Tue May 30 02:24:22 2023, max compression
+gzip compressed data, was "prism-ds-0.2.0rc1.tar", last modified: Wed Jun 28 01:56:10 2023, max compression
```

## Comparing `prism-ds-0.1.9rc2.tar` & `prism-ds-0.2.0rc1.tar`

### file list

```diff
@@ -1,440 +1,450 @@
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.651464 prism-ds-0.1.9rc2/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)    11312 2022-08-08 04:50:27.000000 prism-ds-0.1.9rc2/LICENSE
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      219 2023-05-16 12:01:01.000000 prism-ds-0.1.9rc2/MANIFEST.in
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     5536 2023-05-30 02:24:22.651604 prism-ds-0.1.9rc2/PKG-INFO
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     4572 2023-05-16 12:50:41.000000 prism-ds-0.1.9rc2/README.md
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.544905 prism-ds-0.1.9rc2/prism/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2022-08-17 00:34:22.000000 prism-ds-0.1.9rc2/prism/__init__.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1070 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/admin.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.546830 prism-ds-0.1.9rc2/prism/agents/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/agents/__init__.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     7778 2023-05-15 03:40:20.000000 prism-ds-0.1.9rc2/prism/agents/base.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)    18475 2023-05-15 14:21:16.000000 prism-ds-0.1.9rc2/prism/agents/docker_agent.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)    37114 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/agents/ec2.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      533 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/agents/meta.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.547571 prism-ds-0.1.9rc2/prism/agents/scripts/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-05-16 12:00:13.000000 prism-ds-0.1.9rc2/prism/agents/scripts/__init__.py
--rwxr-xr-x   0 mihirtrivedi   (501) staff       (20)     3276 2023-05-15 03:40:20.000000 prism-ds-0.1.9rc2/prism/agents/scripts/apply.sh
--rwxr-xr-x   0 mihirtrivedi   (501) staff       (20)      680 2023-05-15 03:40:20.000000 prism-ds-0.1.9rc2/prism/agents/scripts/run.sh
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.550597 prism-ds-0.1.9rc2/prism/cli/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2022-08-08 04:50:27.000000 prism-ds-0.1.9rc2/prism/cli/__init__.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     9886 2023-05-15 03:40:20.000000 prism-ds-0.1.9rc2/prism/cli/agent.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     6974 2023-04-02 17:52:18.000000 prism-ds-0.1.9rc2/prism/cli/base.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     6235 2023-04-02 17:52:18.000000 prism-ds-0.1.9rc2/prism/cli/compile.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     4391 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/cli/connect.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     4186 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/cli/create_agent.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     4805 2023-05-27 16:07:03.000000 prism-ds-0.1.9rc2/prism/cli/create_task.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     4408 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/cli/create_trigger.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     5415 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/cli/graph.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     5452 2023-05-04 13:05:27.000000 prism-ds-0.1.9rc2/prism/cli/init.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     9372 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/cli/run.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      724 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/cli/spark_submit.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.550819 prism-ds-0.1.9rc2/prism/client/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)    12158 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/client/__init__.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     4973 2023-05-26 22:34:14.000000 prism-ds-0.1.9rc2/prism/constants.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.551502 prism-ds-0.1.9rc2/prism/decorators/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      116 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/decorators/__init__.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     7124 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/decorators/target.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     3116 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/decorators/task.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.551846 prism-ds-0.1.9rc2/prism/docs/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)       79 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/docs/__init__.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.555108 prism-ds-0.1.9rc2/prism/docs/build/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)    50665 2023-03-25 19:27:00.000000 prism-ds-0.1.9rc2/prism/docs/build/311ea03002abadcdcaba.png
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     6035 2023-03-25 19:27:00.000000 prism-ds-0.1.9rc2/prism/docs/build/54968a39190c43d592b9.svg
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)    15406 2023-03-25 19:27:00.000000 prism-ds-0.1.9rc2/prism/docs/build/737ad70b3f2d3a9b5f6e.ico
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)       86 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/docs/build/__init__.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     4653 2023-03-25 19:27:00.000000 prism-ds-0.1.9rc2/prism/docs/build/ce188596011a8fa32931.png
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)   560665 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/docs/build/index.html
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      961 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/docs/build/main.js.LICENSE.txt
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.555533 prism-ds-0.1.9rc2/prism/event_managers/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2022-08-08 04:50:27.000000 prism-ds-0.1.9rc2/prism/event_managers/__init__.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     5985 2023-05-04 14:38:23.000000 prism-ds-0.1.9rc2/prism/event_managers/base.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     7320 2023-05-27 16:07:03.000000 prism-ds-0.1.9rc2/prism/exceptions.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.557907 prism-ds-0.1.9rc2/prism/infra/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2022-08-08 04:50:27.000000 prism-ds-0.1.9rc2/prism/infra/__init__.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)    13452 2023-04-02 17:52:18.000000 prism-ds-0.1.9rc2/prism/infra/compiler.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)    13001 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/infra/executor.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     2395 2023-05-04 13:05:27.000000 prism-ds-0.1.9rc2/prism/infra/hooks.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     2811 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/infra/manifest.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     7801 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/infra/module.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     3629 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/infra/pipeline.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)    17123 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/infra/project.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1673 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/infra/sys_path.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      719 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/infra/task_manager.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)    21250 2023-05-15 14:21:16.000000 prism-ds-0.1.9rc2/prism/logging.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)    22347 2023-05-27 16:07:03.000000 prism-ds-0.1.9rc2/prism/main.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.560428 prism-ds-0.1.9rc2/prism/mixins/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2022-08-16 12:31:03.000000 prism-ds-0.1.9rc2/prism/mixins/__init__.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     2405 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/mixins/agent.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     2823 2023-05-15 03:40:20.000000 prism-ds-0.1.9rc2/prism/mixins/aws.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1124 2023-04-02 17:52:18.000000 prism-ds-0.1.9rc2/prism/mixins/base.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     8170 2023-04-02 17:52:18.000000 prism-ds-0.1.9rc2/prism/mixins/compile.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     7295 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/mixins/connect.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     2306 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/mixins/create_agent.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     5710 2023-05-27 16:07:03.000000 prism-ds-0.1.9rc2/prism/mixins/create_task.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     5422 2023-05-15 03:40:20.000000 prism-ds-0.1.9rc2/prism/mixins/create_trigger.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     2438 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/mixins/graph.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1107 2023-04-02 17:52:18.000000 prism-ds-0.1.9rc2/prism/mixins/run.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     4244 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/mixins/sys_handler.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.561086 prism-ds-0.1.9rc2/prism/parsers/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2022-08-08 04:50:27.000000 prism-ds-0.1.9rc2/prism/parsers/__init__.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)    23861 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/parsers/ast_parser.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     2206 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/parsers/base.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     3049 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/parsers/yml_parser.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.563958 prism-ds-0.1.9rc2/prism/profiles/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2022-08-08 04:50:27.000000 prism-ds-0.1.9rc2/prism/profiles/__init__.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     2745 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/profiles/adapter.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     3611 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/profiles/bigquery.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)    15601 2023-05-15 03:40:20.000000 prism-ds-0.1.9rc2/prism/profiles/dbt.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      539 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/profiles/meta.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     4501 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/profiles/postgres.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     9047 2023-05-04 13:05:27.000000 prism-ds-0.1.9rc2/prism/profiles/profile.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     4089 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/profiles/pyspark.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     4491 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/profiles/redshift.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     4077 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/profiles/snowflake.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     6292 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/profiles/trino.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.564528 prism-ds-0.1.9rc2/prism/spark/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2022-08-08 04:50:27.000000 prism-ds-0.1.9rc2/prism/spark/__init__.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      439 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/spark/script.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     2889 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/spark/wrapper.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1582 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/target.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     5145 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/task.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.564788 prism-ds-0.1.9rc2/prism/templates/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2022-08-17 00:55:51.000000 prism-ds-0.1.9rc2/prism/templates/__init__.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.565307 prism-ds-0.1.9rc2/prism/templates/agents/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)       59 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/templates/agents/__init__.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      233 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/templates/agents/docker.yml
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      191 2023-05-20 15:36:38.000000 prism-ds-0.1.9rc2/prism/templates/agents/ec2.yml
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.565946 prism-ds-0.1.9rc2/prism/templates/minimal_project/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)       19 2022-08-16 12:31:03.000000 prism-ds-0.1.9rc2/prism/templates/minimal_project/.gitignore
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)       68 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/templates/minimal_project/__init__.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.566676 prism-ds-0.1.9rc2/prism/templates/minimal_project/modules/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1011 2023-05-30 01:38:51.000000 prism-ds-0.1.9rc2/prism/templates/minimal_project/modules/class_task.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      938 2023-05-30 01:39:48.000000 prism-ds-0.1.9rc2/prism/templates/minimal_project/modules/decorated_task.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1328 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/templates/minimal_project/prism_project.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.567008 prism-ds-0.1.9rc2/prism/templates/profile/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)       61 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/templates/profile/__init__.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.567196 prism-ds-0.1.9rc2/prism/templates/profile/bigquery/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      148 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/templates/profile/bigquery/profile.yml
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.567368 prism-ds-0.1.9rc2/prism/templates/profile/dbt/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      141 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/templates/profile/dbt/profile.yml
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.567553 prism-ds-0.1.9rc2/prism/templates/profile/postgres/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      180 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/templates/profile/postgres/profile.yml
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.567717 prism-ds-0.1.9rc2/prism/templates/profile/pyspark/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      478 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/templates/profile/pyspark/profile.yml
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.567884 prism-ds-0.1.9rc2/prism/templates/profile/redshift/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      180 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/templates/profile/redshift/profile.yml
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.568059 prism-ds-0.1.9rc2/prism/templates/profile/snowflake/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      193 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/templates/profile/snowflake/profile.yml
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.568216 prism-ds-0.1.9rc2/prism/templates/profile/trino/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      189 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/templates/profile/trino/profile.yml
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.568927 prism-ds-0.1.9rc2/prism/templates/starter_project/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)       19 2022-08-08 04:50:27.000000 prism-ds-0.1.9rc2/prism/templates/starter_project/.gitignore
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)       68 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/templates/starter_project/__init__.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.569166 prism-ds-0.1.9rc2/prism/templates/starter_project/data/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2022-08-16 12:31:03.000000 prism-ds-0.1.9rc2/prism/templates/starter_project/data/.exists
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.569266 prism-ds-0.1.9rc2/prism/templates/starter_project/dev/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      788 2022-08-08 04:50:27.000000 prism-ds-0.1.9rc2/prism/templates/starter_project/dev/dev.ipynb
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.569717 prism-ds-0.1.9rc2/prism/templates/starter_project/modules/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1011 2023-05-30 01:39:55.000000 prism-ds-0.1.9rc2/prism/templates/starter_project/modules/class_task.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      938 2023-05-30 01:39:55.000000 prism-ds-0.1.9rc2/prism/templates/starter_project/modules/decorated_task.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.569943 prism-ds-0.1.9rc2/prism/templates/starter_project/output/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2022-08-16 12:31:03.000000 prism-ds-0.1.9rc2/prism/templates/starter_project/output/.exists
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1114 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/templates/starter_project/prism_project.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)       66 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/templates/starter_project/utils.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.570964 prism-ds-0.1.9rc2/prism/templates/tasks/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      426 2023-05-27 16:07:03.000000 prism-ds-0.1.9rc2/prism/templates/tasks/pyspark_cls.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      427 2023-05-27 16:07:03.000000 prism-ds-0.1.9rc2/prism/templates/tasks/pyspark_dec.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      426 2023-05-27 16:07:03.000000 prism-ds-0.1.9rc2/prism/templates/tasks/python_cls.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      427 2023-05-27 16:07:03.000000 prism-ds-0.1.9rc2/prism/templates/tasks/python_dec.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      155 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/templates/tasks/sql.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.571640 prism-ds-0.1.9rc2/prism/templates/triggers/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)       61 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/templates/triggers/__init__.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      267 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/templates/triggers/function.yml
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      208 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/templates/triggers/prism_project.yml
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.571825 prism-ds-0.1.9rc2/prism/tests/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2022-08-08 04:50:27.000000 prism-ds-0.1.9rc2/prism/tests/__init__.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.575003 prism-ds-0.1.9rc2/prism/tests/integration/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2022-08-08 04:50:27.000000 prism-ds-0.1.9rc2/prism/tests/integration/__init__.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     7910 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/integration_test_class.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)    14197 2023-05-15 03:40:20.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_client.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     7755 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_compile.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)    10260 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_connect.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     6520 2023-05-27 16:07:03.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_create.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     4010 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_dbt.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     5729 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_hooks.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     4539 2023-05-30 01:42:39.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_init.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.538878 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.575786 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/001_init/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)       68 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/001_init/__init__.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.576025 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/001_init/modules/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1008 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/001_init/modules/module01.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1122 2023-05-27 15:46:27.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/001_init/prism_project.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)       66 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/001_init/utils.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.576512 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/001a_init_minimal/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)       68 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/001a_init_minimal/__init__.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.576778 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/001a_init_minimal/modules/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1008 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/001a_init_minimal/modules/module01.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1345 2023-05-27 15:46:27.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/001a_init_minimal/prism_project.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.577277 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/002_no_project_py/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/002_no_project_py/__init__.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      772 2022-08-08 04:50:27.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/002_no_project_py/functions.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.578033 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/002_no_project_py/modules/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      835 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/002_no_project_py/modules/module01.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      867 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/002_no_project_py/modules/module02.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      867 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/002_no_project_py/modules/module03.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.578335 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/003_project_with_cycle/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/003_project_with_cycle/__init__.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.579103 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/003_project_with_cycle/modules/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      888 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/003_project_with_cycle/modules/module01.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      921 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/003_project_with_cycle/modules/module02.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      922 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/003_project_with_cycle/modules/module03.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1070 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/003_project_with_cycle/prism_project.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.579379 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/004_simple_project/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/004_simple_project/__init__.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.580050 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/004_simple_project/modules/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      983 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/004_simple_project/modules/module01.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1073 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/004_simple_project/modules/module02.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      917 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/004_simple_project/modules/module03.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1035 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/004_simple_project/prism_project.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.582247 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/005_simple_project_no_null/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/005_simple_project_no_null/__init__.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      772 2022-08-08 04:50:27.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/005_simple_project_no_null/functions.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.584684 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/005_simple_project_no_null/modules/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1031 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/005_simple_project_no_null/modules/module01.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1152 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/005_simple_project_no_null/modules/module02.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      986 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/005_simple_project_no_null/modules/module03.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      922 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/005_simple_project_no_null/modules/module04.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1070 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/005_simple_project_no_null/prism_project.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.585162 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/006_simple_project_with_profile/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/006_simple_project_with_profile/__init__.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.586991 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/006_simple_project_with_profile/modules/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      983 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/006_simple_project_with_profile/modules/module01.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1104 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/006_simple_project_with_profile/modules/module02.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      986 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/006_simple_project_with_profile/modules/module03.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      922 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/006_simple_project_with_profile/modules/module04.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1259 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/006_simple_project_with_profile/prism_project.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.589005 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/007_spark_project/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/007_spark_project/__init__.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.592342 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/007_spark_project/modules/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1790 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/007_spark_project/modules/module01.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1176 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/007_spark_project/modules/module02.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1051 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/007_spark_project/modules/module03.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      622 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/007_spark_project/modules/module04.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1075 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/007_spark_project/prism_project.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.593305 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/008_targets/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/008_targets/__init__.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.594963 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/008_targets/modules/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      973 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/008_targets/modules/csv.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1535 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/008_targets/modules/csv_iter.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1589 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/008_targets/modules/csv_mult.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1796 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/008_targets/modules/parquet.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      494 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/008_targets/modules/txt.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1075 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/008_targets/prism_project.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.595843 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/009_simple_dbt_project/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/009_simple_dbt_project/__init__.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.595960 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/009_simple_dbt_project/prism/
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.598080 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/009_simple_dbt_project/prism/modules/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      576 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/009_simple_dbt_project/prism/modules/bad_adapter.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      583 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/009_simple_dbt_project/prism/modules/filter_customers.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1075 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/009_simple_dbt_project/prism/prism_project.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.598377 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/010_project_nested_module_dirs/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/010_project_nested_module_dirs/__init__.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.600326 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/010_project_nested_module_dirs/modules/
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.600671 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/010_project_nested_module_dirs/modules/extract/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      983 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/010_project_nested_module_dirs/modules/extract/module01.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1112 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/010_project_nested_module_dirs/modules/extract/module02.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.602223 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/010_project_nested_module_dirs/modules/load/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      994 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/010_project_nested_module_dirs/modules/load/module03.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      931 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/010_project_nested_module_dirs/modules/module04.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1070 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/010_project_nested_module_dirs/prism_project.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.602523 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/011_bad_task_ref/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/011_bad_task_ref/__init__.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.602694 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/011_bad_task_ref/modules/
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.604926 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/011_bad_task_ref/modules/extract/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      983 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/011_bad_task_ref/modules/extract/module01.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1120 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/011_bad_task_ref/modules/extract/module02.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.605144 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/011_bad_task_ref/modules/load/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      994 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/011_bad_task_ref/modules/load/module03.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      931 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/011_bad_task_ref/modules/module04.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1070 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/011_bad_task_ref/prism_project.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.605393 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/012_concurrency/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/012_concurrency/__init__.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.606971 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/012_concurrency/modules/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1242 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/012_concurrency/modules/module01.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1245 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/012_concurrency/modules/module02.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1188 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/012_concurrency/modules/module03.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      922 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/012_concurrency/modules/module04.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1070 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/012_concurrency/prism_project.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.607319 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/013_hooks_sql_spark/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/013_hooks_sql_spark/__init__.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.609847 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/013_hooks_sql_spark/modules/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1359 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/013_hooks_sql_spark/modules/bad_adapter.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1090 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/013_hooks_sql_spark/modules/postgres.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1838 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/013_hooks_sql_spark/modules/snowflake.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     2154 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/013_hooks_sql_spark/modules/spark.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1075 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/013_hooks_sql_spark/prism_project.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.610262 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/014_test_triggers_normal/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/014_test_triggers_normal/__init__.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.610870 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/014_test_triggers_normal/modules/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      362 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/014_test_triggers_normal/modules/module01.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      347 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/014_test_triggers_normal/modules/module02.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1213 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/014_test_triggers_normal/prism_project.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.611283 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/015_test_triggers_no_dir/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/015_test_triggers_no_dir/__init__.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.611577 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/015_test_triggers_no_dir/modules/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      362 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/015_test_triggers_no_dir/modules/module01.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1153 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/015_test_triggers_no_dir/prism_project.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.612771 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/016_test_triggers_error/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/016_test_triggers_error/__init__.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.612983 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/016_test_triggers_error/modules/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      930 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/016_test_triggers_error/modules/module01.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1213 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/016_test_triggers_error/prism_project.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      129 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/016_test_triggers_error/utils.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.613476 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/017_test_triggers_extra_key/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/017_test_triggers_extra_key/__init__.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.613645 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/017_test_triggers_extra_key/modules/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      930 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/017_test_triggers_extra_key/modules/module01.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1213 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/017_test_triggers_extra_key/prism_project.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      129 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/017_test_triggers_extra_key/utils.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.614410 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/018_test_triggers_no_include/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/018_test_triggers_no_include/__init__.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.614771 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/018_test_triggers_no_include/modules/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      930 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/018_test_triggers_no_include/modules/module01.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1213 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/018_test_triggers_no_include/prism_project.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      129 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/018_test_triggers_no_include/utils.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.615067 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/019_dec_targets/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/019_dec_targets/__init__.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.615807 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/019_dec_targets/modules/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      578 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/019_dec_targets/modules/extract.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      620 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/019_dec_targets/modules/load.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1213 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/019_dec_targets/prism_project.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.616515 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/020_dec_retries/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/020_dec_retries/__init__.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.617807 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/020_dec_retries/modules/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      399 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/020_dec_retries/modules/extract.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      703 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/020_dec_retries/modules/load.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1213 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/020_dec_retries/prism_project.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      129 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/020_dec_retries/utils.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.618315 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/common/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/common/__init__.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      376 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_projects/common/functions.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)    36004 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_run.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)    11844 2023-03-26 19:43:45.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_spark_submit.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     5358 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/integration/test_targets.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.622689 prism-ds-0.1.9rc2/prism/tests/unit/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2022-08-08 04:50:27.000000 prism-ds-0.1.9rc2/prism/tests/unit/__init__.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.623224 prism-ds-0.1.9rc2/prism/tests/unit/dummy_modules/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/unit/dummy_modules/dummy_module1.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)    13709 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_adapter_profile.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.623341 prism-ds-0.1.9rc2/prism/tests/unit/test_agent/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1232 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_agent/prism_project.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)    10137 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_agents.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)    26210 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_dag_fns.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.623508 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)       77 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/__init__.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.625167 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/dag_cycle/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      173 2022-08-08 04:50:27.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/dag_cycle/__init__.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      171 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/dag_cycle/moduleA.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      224 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/dag_cycle/moduleB.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      198 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/dag_cycle/moduleC.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      250 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/dag_cycle/moduleD.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      250 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/dag_cycle/moduleE.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.630596 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_15nodes/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      436 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_15nodes/__init__.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      185 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_15nodes/module01.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      211 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_15nodes/module02.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      212 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_15nodes/module03.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      239 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_15nodes/module04.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      212 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_15nodes/module05.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      212 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_15nodes/module06.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      239 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_15nodes/module07.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      212 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_15nodes/module08.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      239 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_15nodes/module09.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      212 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_15nodes/module10.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      212 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_15nodes/module11.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      212 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_15nodes/module12.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      212 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_15nodes/module13.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      212 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_15nodes/module14.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      212 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_15nodes/module15.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.631648 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_3nodes/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      134 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_3nodes/__init__.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      183 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_3nodes/module01.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      211 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_3nodes/module02.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      210 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_3nodes/module03.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.633740 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_5nodes/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      179 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_5nodes/__init__.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      171 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_5nodes/moduleA.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      198 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_5nodes/moduleB.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      198 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_5nodes/moduleC.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      250 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_5nodes/moduleD.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      250 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_5nodes/moduleE.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.635072 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_norefs/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      179 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_norefs/__init__.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      171 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_norefs/moduleA.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      171 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_norefs/moduleB.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      171 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_norefs/moduleC.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      171 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_norefs/moduleD.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      171 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_norefs/moduleE.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.638595 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_selfref/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      180 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_selfref/__init__.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      171 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_selfref/moduleA.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      175 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_selfref/moduleB.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      171 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_selfref/moduleC.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      171 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_selfref/moduleD.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      171 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_all_things_dag/task_ref_selfref/moduleE.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      405 2022-08-08 04:50:27.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_import.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     4992 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_jinja.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)    10289 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_module_parser_cls.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     9472 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_module_parser_dec.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.646197 prism-ds-0.1.9rc2/prism/tests/unit/test_modules/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      143 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_modules/bad_run_extra_arg.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      127 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_modules/bad_run_missing_arg.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      135 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_modules/bad_run_no_tasks.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)       92 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_modules/dec_bad_dec_no_parentheses.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      105 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_modules/dec_bad_run_extra_arg.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)       87 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_modules/dec_bad_run_missing_arg.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      124 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_modules/dec_diff_decorator_structure.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      156 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_modules/dec_multiple_prism_tasks.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)       49 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_modules/dec_no_prism_task.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)       93 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_modules/dec_one_prism_task.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      126 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_modules/dec_other_functions.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      301 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_modules/dec_task_with_target.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      451 2023-05-26 22:30:47.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_modules/dec_tasks_refs.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      133 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_modules/diff_import_structure.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      173 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_modules/if_name_main.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      226 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_modules/multiple_prism_tasks.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      120 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_modules/no_prism_task.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      121 2022-08-08 04:50:27.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_modules/no_run_func.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      133 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_modules/one_prism_task.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      199 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_modules/other_classes.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      332 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_modules/task_with_target.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      345 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_modules/tasks_refs.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.648343 prism-ds-0.1.9rc2/prism/tests/unit/test_prism_project_py/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1070 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_prism_project_py/bad_trigger_key.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      915 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_prism_project_py/multiple_profiles.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      879 2022-08-08 04:50:27.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_prism_project_py/no_profile.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      909 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_prism_project_py/non_null_profile.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      894 2023-03-01 23:08:44.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_prism_project_py/null_profile.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1002 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_prism_project_py/on_failure_triggers_only.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1002 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_prism_project_py/on_success_triggers_only.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      998 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_prism_project_py/triggers_normal.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     7556 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_project.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     8920 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_trigger.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.648711 prism-ds-0.1.9rc2/prism/tests/unit/test_trigger_yml/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      931 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_trigger_yml/prism_project.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      111 2023-04-04 01:59:51.000000 prism-ds-0.1.9rc2/prism/tests/unit/test_trigger_yml/test_fn.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.649173 prism-ds-0.1.9rc2/prism/triggers/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)    19434 2023-05-04 14:37:27.000000 prism-ds-0.1.9rc2/prism/triggers/__init__.py
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      810 2023-05-04 14:39:42.000000 prism-ds-0.1.9rc2/prism/ui.py
-drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-05-30 02:24:22.650950 prism-ds-0.1.9rc2/prism_ds.egg-info/
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     5536 2023-05-30 02:24:22.000000 prism-ds-0.1.9rc2/prism_ds.egg-info/PKG-INFO
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)    17445 2023-05-30 02:24:22.000000 prism-ds-0.1.9rc2/prism_ds.egg-info/SOURCES.txt
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        1 2023-05-30 02:24:22.000000 prism-ds-0.1.9rc2/prism_ds.egg-info/dependency_links.txt
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)       42 2023-05-30 02:24:22.000000 prism-ds-0.1.9rc2/prism_ds.egg-info/entry_points.txt
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)        1 2022-10-22 21:37:16.000000 prism-ds-0.1.9rc2/prism_ds.egg-info/not-zip-safe
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      553 2023-05-30 02:24:22.000000 prism-ds-0.1.9rc2/prism_ds.egg-info/requires.txt
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)       15 2023-05-30 02:24:22.000000 prism-ds-0.1.9rc2/prism_ds.egg-info/top_level.txt
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)      743 2022-11-12 14:33:04.000000 prism-ds-0.1.9rc2/pyproject.toml
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1755 2023-05-30 02:24:22.652039 prism-ds-0.1.9rc2/setup.cfg
--rw-r--r--   0 mihirtrivedi   (501) staff       (20)       70 2023-05-04 13:05:27.000000 prism-ds-0.1.9rc2/setup.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.661272 prism-ds-0.2.0rc1/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)    11312 2022-08-08 04:50:27.000000 prism-ds-0.2.0rc1/LICENSE
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      219 2023-05-16 12:01:01.000000 prism-ds-0.2.0rc1/MANIFEST.in
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     5536 2023-06-28 01:56:10.661401 prism-ds-0.2.0rc1/PKG-INFO
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     4572 2023-05-16 12:50:41.000000 prism-ds-0.2.0rc1/README.md
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.560805 prism-ds-0.2.0rc1/prism/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2022-08-17 00:34:22.000000 prism-ds-0.2.0rc1/prism/__init__.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1070 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/admin.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.562640 prism-ds-0.2.0rc1/prism/agents/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/agents/__init__.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     7797 2023-06-28 00:35:11.000000 prism-ds-0.2.0rc1/prism/agents/base.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)    18553 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/agents/docker_agent.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)    37258 2023-06-28 00:56:35.000000 prism-ds-0.2.0rc1/prism/agents/ec2.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      533 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/agents/meta.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.563271 prism-ds-0.2.0rc1/prism/agents/scripts/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-05-16 12:00:13.000000 prism-ds-0.2.0rc1/prism/agents/scripts/__init__.py
+-rwxr-xr-x   0 mihirtrivedi   (501) staff       (20)     3307 2023-06-28 01:07:53.000000 prism-ds-0.2.0rc1/prism/agents/scripts/apply.sh
+-rwxr-xr-x   0 mihirtrivedi   (501) staff       (20)      710 2023-06-28 01:05:16.000000 prism-ds-0.2.0rc1/prism/agents/scripts/run.sh
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.565817 prism-ds-0.2.0rc1/prism/cli/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2022-08-08 04:50:27.000000 prism-ds-0.2.0rc1/prism/cli/__init__.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     9934 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/cli/agent.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     7058 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/cli/base.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     8047 2023-06-28 01:31:58.000000 prism-ds-0.2.0rc1/prism/cli/compile.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     4457 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/cli/connect.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     4222 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/cli/create_agent.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     4835 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/cli/create_task.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     4444 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/cli/create_trigger.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     5445 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/cli/graph.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     5506 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/cli/init.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     9408 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/cli/run.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      724 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/cli/spark_submit.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.566092 prism-ds-0.2.0rc1/prism/client/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)    12170 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/client/__init__.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     4973 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/constants.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.567065 prism-ds-0.2.0rc1/prism/decorators/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      116 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/decorators/__init__.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     7124 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/decorators/target.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     3116 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/decorators/task.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.567249 prism-ds-0.2.0rc1/prism/docs/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)       79 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/docs/__init__.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.570425 prism-ds-0.2.0rc1/prism/docs/build/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)    50665 2023-03-25 19:27:00.000000 prism-ds-0.2.0rc1/prism/docs/build/311ea03002abadcdcaba.png
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     6035 2023-03-25 19:27:00.000000 prism-ds-0.2.0rc1/prism/docs/build/54968a39190c43d592b9.svg
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)    15406 2023-03-25 19:27:00.000000 prism-ds-0.2.0rc1/prism/docs/build/737ad70b3f2d3a9b5f6e.ico
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)       86 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/docs/build/__init__.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     4653 2023-03-25 19:27:00.000000 prism-ds-0.2.0rc1/prism/docs/build/ce188596011a8fa32931.png
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)   560665 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/docs/build/index.html
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      961 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/docs/build/main.js.LICENSE.txt
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.570776 prism-ds-0.2.0rc1/prism/event_managers/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2022-08-08 04:50:27.000000 prism-ds-0.2.0rc1/prism/event_managers/__init__.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     6081 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/event_managers/base.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     7589 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/exceptions.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.572631 prism-ds-0.2.0rc1/prism/infra/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2022-08-08 04:50:27.000000 prism-ds-0.2.0rc1/prism/infra/__init__.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)    13457 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/infra/compiler.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)    13019 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/infra/executor.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     2401 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/infra/hooks.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     2811 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/infra/manifest.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     7801 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/infra/module.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     3635 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/infra/pipeline.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)    17171 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/infra/project.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1673 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/infra/sys_path.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      816 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/infra/task_manager.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)    25019 2023-06-28 01:11:01.000000 prism-ds-0.2.0rc1/prism/main.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.578188 prism-ds-0.2.0rc1/prism/mixins/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2022-08-16 12:31:03.000000 prism-ds-0.2.0rc1/prism/mixins/__init__.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     2405 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/mixins/agent.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     2823 2023-06-08 13:53:30.000000 prism-ds-0.2.0rc1/prism/mixins/aws.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1124 2023-04-02 17:52:18.000000 prism-ds-0.2.0rc1/prism/mixins/base.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     8194 2023-06-28 01:33:28.000000 prism-ds-0.2.0rc1/prism/mixins/compile.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     7301 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/mixins/connect.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     2312 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/mixins/create_agent.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     5716 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/mixins/create_task.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     5428 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/mixins/create_trigger.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     2438 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/mixins/graph.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1107 2023-04-02 17:52:18.000000 prism-ds-0.2.0rc1/prism/mixins/run.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     4244 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/mixins/sys_handler.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.578896 prism-ds-0.2.0rc1/prism/parsers/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2022-08-08 04:50:27.000000 prism-ds-0.2.0rc1/prism/parsers/__init__.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)    24860 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/parsers/ast_parser.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     2206 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/parsers/base.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     3049 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/parsers/yml_parser.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)    21581 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/prism_logging.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.581855 prism-ds-0.2.0rc1/prism/profiles/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2022-08-08 04:50:27.000000 prism-ds-0.2.0rc1/prism/profiles/__init__.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     2745 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/profiles/adapter.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     3611 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/profiles/bigquery.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)    15601 2023-05-15 03:40:20.000000 prism-ds-0.2.0rc1/prism/profiles/dbt.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      539 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/profiles/meta.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     4501 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/profiles/postgres.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     9117 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/profiles/profile.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     4089 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/profiles/pyspark.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     4491 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/profiles/redshift.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     4077 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/profiles/snowflake.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     6292 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/profiles/trino.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.582390 prism-ds-0.2.0rc1/prism/spark/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2022-08-08 04:50:27.000000 prism-ds-0.2.0rc1/prism/spark/__init__.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      439 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/spark/script.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     2889 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/spark/wrapper.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1582 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/target.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     5171 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/task.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.582559 prism-ds-0.2.0rc1/prism/templates/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2022-08-17 00:55:51.000000 prism-ds-0.2.0rc1/prism/templates/__init__.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.582987 prism-ds-0.2.0rc1/prism/templates/agents/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)       59 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/templates/agents/__init__.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      233 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/templates/agents/docker.yml
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      191 2023-05-20 15:36:38.000000 prism-ds-0.2.0rc1/prism/templates/agents/ec2.yml
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.583740 prism-ds-0.2.0rc1/prism/templates/minimal_project/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)       19 2022-08-16 12:31:03.000000 prism-ds-0.2.0rc1/prism/templates/minimal_project/.gitignore
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)       68 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/templates/minimal_project/__init__.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.584348 prism-ds-0.2.0rc1/prism/templates/minimal_project/modules/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1011 2023-05-30 01:38:51.000000 prism-ds-0.2.0rc1/prism/templates/minimal_project/modules/class_task.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      938 2023-05-30 01:39:48.000000 prism-ds-0.2.0rc1/prism/templates/minimal_project/modules/decorated_task.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1328 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/templates/minimal_project/prism_project.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.584681 prism-ds-0.2.0rc1/prism/templates/profile/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)       61 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/templates/profile/__init__.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.584863 prism-ds-0.2.0rc1/prism/templates/profile/bigquery/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      148 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/templates/profile/bigquery/profile.yml
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.585106 prism-ds-0.2.0rc1/prism/templates/profile/dbt/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      141 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/templates/profile/dbt/profile.yml
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.585368 prism-ds-0.2.0rc1/prism/templates/profile/postgres/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      180 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/templates/profile/postgres/profile.yml
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.585557 prism-ds-0.2.0rc1/prism/templates/profile/pyspark/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      478 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/templates/profile/pyspark/profile.yml
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.585707 prism-ds-0.2.0rc1/prism/templates/profile/redshift/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      180 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/templates/profile/redshift/profile.yml
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.585867 prism-ds-0.2.0rc1/prism/templates/profile/snowflake/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      193 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/templates/profile/snowflake/profile.yml
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.586027 prism-ds-0.2.0rc1/prism/templates/profile/trino/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      189 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/templates/profile/trino/profile.yml
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.586786 prism-ds-0.2.0rc1/prism/templates/starter_project/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)       19 2022-08-08 04:50:27.000000 prism-ds-0.2.0rc1/prism/templates/starter_project/.gitignore
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)       68 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/templates/starter_project/__init__.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.587056 prism-ds-0.2.0rc1/prism/templates/starter_project/data/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2022-08-16 12:31:03.000000 prism-ds-0.2.0rc1/prism/templates/starter_project/data/.exists
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.587149 prism-ds-0.2.0rc1/prism/templates/starter_project/dev/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      788 2022-08-08 04:50:27.000000 prism-ds-0.2.0rc1/prism/templates/starter_project/dev/dev.ipynb
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.587687 prism-ds-0.2.0rc1/prism/templates/starter_project/modules/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1011 2023-05-30 01:39:55.000000 prism-ds-0.2.0rc1/prism/templates/starter_project/modules/class_task.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      938 2023-05-30 01:39:55.000000 prism-ds-0.2.0rc1/prism/templates/starter_project/modules/decorated_task.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.587940 prism-ds-0.2.0rc1/prism/templates/starter_project/output/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2022-08-16 12:31:03.000000 prism-ds-0.2.0rc1/prism/templates/starter_project/output/.exists
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1114 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/templates/starter_project/prism_project.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)       66 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/templates/starter_project/utils.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.589246 prism-ds-0.2.0rc1/prism/templates/tasks/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      426 2023-05-27 16:07:03.000000 prism-ds-0.2.0rc1/prism/templates/tasks/pyspark_cls.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      427 2023-05-27 16:07:03.000000 prism-ds-0.2.0rc1/prism/templates/tasks/pyspark_dec.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      426 2023-05-27 16:07:03.000000 prism-ds-0.2.0rc1/prism/templates/tasks/python_cls.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      427 2023-05-27 16:07:03.000000 prism-ds-0.2.0rc1/prism/templates/tasks/python_dec.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      155 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/templates/tasks/sql.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.590032 prism-ds-0.2.0rc1/prism/templates/triggers/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)       61 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/templates/triggers/__init__.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      267 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/templates/triggers/function.yml
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      208 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/templates/triggers/prism_project.yml
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.590323 prism-ds-0.2.0rc1/prism/tests/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2022-08-08 04:50:27.000000 prism-ds-0.2.0rc1/prism/tests/__init__.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.592997 prism-ds-0.2.0rc1/prism/tests/integration/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2022-08-08 04:50:27.000000 prism-ds-0.2.0rc1/prism/tests/integration/__init__.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     7872 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/tests/integration/integration_test_class.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)    14197 2023-05-15 03:40:20.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_client.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     7755 2023-06-26 11:22:36.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_compile.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)    10444 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_connect.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     6520 2023-05-27 16:07:03.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_create.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     4020 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_dbt.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     5738 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_hooks.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     4539 2023-05-30 01:42:39.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_init.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.550429 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.593696 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/001_init/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)       68 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/001_init/__init__.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.594251 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/001_init/modules/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1011 2023-05-30 01:39:55.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/001_init/modules/class_task.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      938 2023-05-30 01:39:55.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/001_init/modules/decorated_task.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1122 2023-06-28 01:34:52.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/001_init/prism_project.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)       66 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/001_init/utils.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.594601 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/001a_init_minimal/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)       68 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/001a_init_minimal/__init__.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.595088 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/001a_init_minimal/modules/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1011 2023-05-30 01:38:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/001a_init_minimal/modules/class_task.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      938 2023-05-30 01:39:48.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/001a_init_minimal/modules/decorated_task.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1345 2023-06-28 01:34:52.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/001a_init_minimal/prism_project.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.595406 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/002_no_project_py/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/002_no_project_py/__init__.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      772 2022-08-08 04:50:27.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/002_no_project_py/functions.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.596267 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/002_no_project_py/modules/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      835 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/002_no_project_py/modules/module01.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      867 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/002_no_project_py/modules/module02.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      867 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/002_no_project_py/modules/module03.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.596604 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/003_project_with_cycle/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/003_project_with_cycle/__init__.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.597253 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/003_project_with_cycle/modules/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      888 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/003_project_with_cycle/modules/module01.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      921 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/003_project_with_cycle/modules/module02.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      922 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/003_project_with_cycle/modules/module03.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1070 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/003_project_with_cycle/prism_project.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.597647 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/004_simple_project/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/004_simple_project/__init__.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.598370 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/004_simple_project/modules/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      983 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/004_simple_project/modules/module01.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1073 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/004_simple_project/modules/module02.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      917 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/004_simple_project/modules/module03.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1035 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/004_simple_project/prism_project.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.599085 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/005_simple_project_no_null/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/005_simple_project_no_null/__init__.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      772 2022-08-08 04:50:27.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/005_simple_project_no_null/functions.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.599866 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/005_simple_project_no_null/modules/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1031 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/005_simple_project_no_null/modules/module01.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1152 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/005_simple_project_no_null/modules/module02.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      986 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/005_simple_project_no_null/modules/module03.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      922 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/005_simple_project_no_null/modules/module04.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1070 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/005_simple_project_no_null/prism_project.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.600212 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/006_simple_project_with_profile/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/006_simple_project_with_profile/__init__.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.601536 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/006_simple_project_with_profile/modules/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      983 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/006_simple_project_with_profile/modules/module01.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1104 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/006_simple_project_with_profile/modules/module02.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      986 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/006_simple_project_with_profile/modules/module03.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      922 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/006_simple_project_with_profile/modules/module04.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1259 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/006_simple_project_with_profile/prism_project.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.601932 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/007_spark_project/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/007_spark_project/__init__.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.602655 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/007_spark_project/modules/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1790 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/007_spark_project/modules/module01.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1176 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/007_spark_project/modules/module02.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1051 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/007_spark_project/modules/module03.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      622 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/007_spark_project/modules/module04.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1075 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/007_spark_project/prism_project.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.603004 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/008_targets/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/008_targets/__init__.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.605481 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/008_targets/modules/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      973 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/008_targets/modules/csv.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1535 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/008_targets/modules/csv_iter.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1589 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/008_targets/modules/csv_mult.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1796 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/008_targets/modules/parquet.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      494 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/008_targets/modules/txt.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1075 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/008_targets/prism_project.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.605642 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/009_simple_dbt_project/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/009_simple_dbt_project/__init__.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.605752 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/009_simple_dbt_project/prism/
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.606100 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/009_simple_dbt_project/prism/modules/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      576 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/009_simple_dbt_project/prism/modules/bad_adapter.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      583 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/009_simple_dbt_project/prism/modules/filter_customers.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1075 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/009_simple_dbt_project/prism/prism_project.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.606402 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/010_project_nested_module_dirs/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/010_project_nested_module_dirs/__init__.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.606672 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/010_project_nested_module_dirs/modules/
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.607028 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/010_project_nested_module_dirs/modules/extract/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      983 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/010_project_nested_module_dirs/modules/extract/module01.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1112 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/010_project_nested_module_dirs/modules/extract/module02.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.607210 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/010_project_nested_module_dirs/modules/load/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      994 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/010_project_nested_module_dirs/modules/load/module03.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      931 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/010_project_nested_module_dirs/modules/module04.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1070 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/010_project_nested_module_dirs/prism_project.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.607474 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/011_bad_task_ref/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/011_bad_task_ref/__init__.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.607630 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/011_bad_task_ref/modules/
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.607999 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/011_bad_task_ref/modules/extract/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      983 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/011_bad_task_ref/modules/extract/module01.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1120 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/011_bad_task_ref/modules/extract/module02.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.608160 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/011_bad_task_ref/modules/load/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      994 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/011_bad_task_ref/modules/load/module03.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      931 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/011_bad_task_ref/modules/module04.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1070 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/011_bad_task_ref/prism_project.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.608442 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/012_concurrency/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/012_concurrency/__init__.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.609127 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/012_concurrency/modules/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1242 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/012_concurrency/modules/module01.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1245 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/012_concurrency/modules/module02.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1188 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/012_concurrency/modules/module03.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      922 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/012_concurrency/modules/module04.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1070 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/012_concurrency/prism_project.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.609411 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/013_hooks_sql_spark/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/013_hooks_sql_spark/__init__.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.610125 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/013_hooks_sql_spark/modules/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1359 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/013_hooks_sql_spark/modules/bad_adapter.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1090 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/013_hooks_sql_spark/modules/postgres.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1838 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/013_hooks_sql_spark/modules/snowflake.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     2154 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/013_hooks_sql_spark/modules/spark.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1075 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/013_hooks_sql_spark/prism_project.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.610415 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/014_test_triggers_normal/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/014_test_triggers_normal/__init__.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.610924 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/014_test_triggers_normal/modules/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      362 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/014_test_triggers_normal/modules/module01.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      347 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/014_test_triggers_normal/modules/module02.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1213 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/014_test_triggers_normal/prism_project.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.611287 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/015_test_triggers_no_dir/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/015_test_triggers_no_dir/__init__.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.611562 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/015_test_triggers_no_dir/modules/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      362 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/015_test_triggers_no_dir/modules/module01.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1153 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/015_test_triggers_no_dir/prism_project.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.612141 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/016_test_triggers_error/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/016_test_triggers_error/__init__.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.612312 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/016_test_triggers_error/modules/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      930 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/016_test_triggers_error/modules/module01.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1213 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/016_test_triggers_error/prism_project.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      129 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/016_test_triggers_error/utils.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.613314 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/017_test_triggers_extra_key/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/017_test_triggers_extra_key/__init__.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.613531 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/017_test_triggers_extra_key/modules/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      930 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/017_test_triggers_extra_key/modules/module01.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1213 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/017_test_triggers_extra_key/prism_project.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      129 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/017_test_triggers_extra_key/utils.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.614278 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/018_test_triggers_no_include/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/018_test_triggers_no_include/__init__.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.614555 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/018_test_triggers_no_include/modules/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      930 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/018_test_triggers_no_include/modules/module01.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1213 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/018_test_triggers_no_include/prism_project.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      129 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/018_test_triggers_no_include/utils.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.614949 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/019_dec_targets/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/019_dec_targets/__init__.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.615499 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/019_dec_targets/modules/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      578 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/019_dec_targets/modules/extract.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      620 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/019_dec_targets/modules/load.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1213 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/019_dec_targets/prism_project.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.616204 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/020_dec_retries/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/020_dec_retries/__init__.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.616648 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/020_dec_retries/modules/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      399 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/020_dec_retries/modules/extract.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      703 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/020_dec_retries/modules/load.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1213 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/020_dec_retries/prism_project.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      129 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/020_dec_retries/utils.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.616962 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/021_no_py_in_ref/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/021_no_py_in_ref/__init__.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.617924 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/021_no_py_in_ref/modules/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1031 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/021_no_py_in_ref/modules/module01.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1149 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/021_no_py_in_ref/modules/module02.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      983 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/021_no_py_in_ref/modules/module03.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      919 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/021_no_py_in_ref/modules/module04.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1070 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/021_no_py_in_ref/prism_project.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.618224 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/common/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/common/__init__.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      376 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_projects/common/functions.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)    38789 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_run.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)    11839 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_spark_submit.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     5323 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/tests/integration/test_targets.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.620653 prism-ds-0.2.0rc1/prism/tests/unit/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2022-08-08 04:50:27.000000 prism-ds-0.2.0rc1/prism/tests/unit/__init__.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.620902 prism-ds-0.2.0rc1/prism/tests/unit/dummy_modules/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        0 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/unit/dummy_modules/dummy_module1.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)    13721 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_adapter_profile.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.621004 prism-ds-0.2.0rc1/prism/tests/unit/test_agent/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1232 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_agent/prism_project.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)    10137 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_agents.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)    26210 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_dag_fns.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.621162 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)       77 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/__init__.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.622470 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/dag_cycle/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      173 2022-08-08 04:50:27.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/dag_cycle/__init__.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      171 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/dag_cycle/moduleA.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      224 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/dag_cycle/moduleB.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      198 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/dag_cycle/moduleC.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      250 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/dag_cycle/moduleD.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      250 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/dag_cycle/moduleE.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.625531 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_15nodes/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      436 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_15nodes/__init__.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      185 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_15nodes/module01.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      211 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_15nodes/module02.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      212 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_15nodes/module03.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      239 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_15nodes/module04.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      212 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_15nodes/module05.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      212 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_15nodes/module06.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      239 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_15nodes/module07.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      212 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_15nodes/module08.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      239 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_15nodes/module09.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      212 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_15nodes/module10.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      212 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_15nodes/module11.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      212 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_15nodes/module12.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      212 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_15nodes/module13.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      212 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_15nodes/module14.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      212 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_15nodes/module15.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.626475 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_3nodes/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      134 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_3nodes/__init__.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      183 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_3nodes/module01.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      211 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_3nodes/module02.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      210 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_3nodes/module03.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.627738 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_5nodes/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      179 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_5nodes/__init__.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      171 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_5nodes/moduleA.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      198 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_5nodes/moduleB.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      198 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_5nodes/moduleC.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      250 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_5nodes/moduleD.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      250 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_5nodes/moduleE.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.630959 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_norefs/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      179 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_norefs/__init__.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      171 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_norefs/moduleA.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      171 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_norefs/moduleB.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      171 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_norefs/moduleC.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      171 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_norefs/moduleD.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      171 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_norefs/moduleE.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.634081 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_selfref/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      180 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_selfref/__init__.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      171 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_selfref/moduleA.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      175 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_selfref/moduleB.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      171 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_selfref/moduleC.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      171 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_selfref/moduleD.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      171 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_all_things_dag/task_ref_selfref/moduleE.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      405 2022-08-08 04:50:27.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_import.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     4992 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_jinja.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)    10289 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_module_parser_cls.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     9472 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_module_parser_dec.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.654382 prism-ds-0.2.0rc1/prism/tests/unit/test_modules/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      143 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_modules/bad_run_extra_arg.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      127 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_modules/bad_run_missing_arg.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      135 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_modules/bad_run_no_tasks.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)       92 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_modules/dec_bad_dec_no_parentheses.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      105 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_modules/dec_bad_run_extra_arg.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)       87 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_modules/dec_bad_run_missing_arg.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      124 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_modules/dec_diff_decorator_structure.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      156 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_modules/dec_multiple_prism_tasks.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)       49 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_modules/dec_no_prism_task.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)       93 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_modules/dec_one_prism_task.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      126 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_modules/dec_other_functions.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      301 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_modules/dec_task_with_target.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      451 2023-05-26 22:30:47.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_modules/dec_tasks_refs.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      133 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_modules/diff_import_structure.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      173 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_modules/if_name_main.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      226 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_modules/multiple_prism_tasks.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      120 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_modules/no_prism_task.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      121 2022-08-08 04:50:27.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_modules/no_run_func.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      133 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_modules/one_prism_task.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      199 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_modules/other_classes.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      332 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_modules/task_with_target.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      345 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_modules/tasks_refs.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.658006 prism-ds-0.2.0rc1/prism/tests/unit/test_prism_project_py/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1070 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_prism_project_py/bad_trigger_key.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      915 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_prism_project_py/multiple_profiles.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      879 2022-08-08 04:50:27.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_prism_project_py/no_profile.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      909 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_prism_project_py/non_null_profile.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      894 2023-03-01 23:08:44.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_prism_project_py/null_profile.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1002 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_prism_project_py/on_failure_triggers_only.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1002 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_prism_project_py/on_success_triggers_only.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      998 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_prism_project_py/triggers_normal.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     7556 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_project.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     8920 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_trigger.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.659062 prism-ds-0.2.0rc1/prism/tests/unit/test_trigger_yml/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      931 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_trigger_yml/prism_project.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      111 2023-04-04 01:59:51.000000 prism-ds-0.2.0rc1/prism/tests/unit/test_trigger_yml/test_fn.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.659333 prism-ds-0.2.0rc1/prism/triggers/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)    19500 2023-06-28 00:14:15.000000 prism-ds-0.2.0rc1/prism/triggers/__init__.py
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      810 2023-05-04 14:39:42.000000 prism-ds-0.2.0rc1/prism/ui.py
+drwxr-xr-x   0 mihirtrivedi   (501) staff       (20)        0 2023-06-28 01:56:10.661149 prism-ds-0.2.0rc1/prism_ds.egg-info/
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     5536 2023-06-28 01:56:10.000000 prism-ds-0.2.0rc1/prism_ds.egg-info/PKG-INFO
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)    18049 2023-06-28 01:56:10.000000 prism-ds-0.2.0rc1/prism_ds.egg-info/SOURCES.txt
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        1 2023-06-28 01:56:10.000000 prism-ds-0.2.0rc1/prism_ds.egg-info/dependency_links.txt
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)       44 2023-06-28 01:56:10.000000 prism-ds-0.2.0rc1/prism_ds.egg-info/entry_points.txt
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)        1 2023-06-26 13:49:56.000000 prism-ds-0.2.0rc1/prism_ds.egg-info/not-zip-safe
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      550 2023-06-28 01:56:10.000000 prism-ds-0.2.0rc1/prism_ds.egg-info/requires.txt
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)       11 2023-06-28 01:56:10.000000 prism-ds-0.2.0rc1/prism_ds.egg-info/top_level.txt
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)      743 2022-11-12 14:33:04.000000 prism-ds-0.2.0rc1/pyproject.toml
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)     1754 2023-06-28 01:56:10.661819 prism-ds-0.2.0rc1/setup.cfg
+-rw-r--r--   0 mihirtrivedi   (501) staff       (20)       70 2023-05-04 13:05:27.000000 prism-ds-0.2.0rc1/setup.py
```

### Comparing `prism-ds-0.1.9rc2/LICENSE` & `prism-ds-0.2.0rc1/LICENSE`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/PKG-INFO` & `prism-ds-0.2.0rc1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: prism-ds
-Version: 0.1.9rc2
+Version: 0.2.0rc1
 Summary: The easiest way to create data pipelines in Python.
 Author: prism founders
 Author-email: hello@runprism.com
 License: Apache-2.0
 Project-URL: homepage, https://www.runprism.com
 Project-URL: documentation, https://docs.runprism.com
 Project-URL: repository, https://github.com/runprism/prism
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: prism-ds Version: 0.1.9rc2 Summary: The easiest way
+Metadata-Version: 2.1 Name: prism-ds Version: 0.2.0rc1 Summary: The easiest way
 to create data pipelines in Python. Author: prism founders Author-email:
 hello@runprism.com License: Apache-2.0 Project-URL: homepage, https://
 www.runprism.com Project-URL: documentation, https://docs.runprism.com Project-
 URL: repository, https://github.com/runprism/prism Platform: unix Platform:
 linux Platform: osx Platform: win32 Classifier: Programming Language :: Python
 :: 3 Classifier: Programming Language :: Python :: 3.7 Classifier: Programming
 Language :: Python :: 3.8 Classifier: Programming Language :: Python :: 3.9
```

### Comparing `prism-ds-0.1.9rc2/README.md` & `prism-ds-0.2.0rc1/README.md`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/admin.py` & `prism-ds-0.2.0rc1/prism/admin.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/agents/base.py` & `prism-ds-0.2.0rc1/prism/agents/base.py`

 * *Files 2% similar despite different names*

```diff
@@ -181,16 +181,16 @@
         # Namespace to string conversion
         full_tb_cmd = "" if not full_tb else "--full-tb"
         log_level_cmd = "" if log_level == "info" else f"--log-level {log_level}"
         vars_cmd = "" if vars is None else " ".join([
             f"{k}={v}" for k, v in vars.items()
         ])
         context_cmd = "" if context == '{}' else f"--context '{context}'"
-        modules_cmd = "" if modules is None else "--modules " + " ".join([
-            m for m in modules
+        modules_cmd = "" if modules is None else " " .join([
+            f"--module {m.replace('.py', '')}" for m in modules
         ])
         all_upstream_cmd = "" if not all_upstream else "--all-upstream"
         all_downstream_cmd = "" if not all_downstream else "--all-downstream"
 
         # Full command
         full_cmd = f"prism run {full_tb_cmd} {log_level_cmd} {vars_cmd} {context_cmd} {modules_cmd} {all_upstream_cmd} {all_downstream_cmd}"  # noqa: E501
         return full_cmd
```

### Comparing `prism-ds-0.1.9rc2/prism/agents/docker_agent.py` & `prism-ds-0.2.0rc1/prism/agents/docker_agent.py`

 * *Files 4% similar despite different names*

```diff
@@ -9,15 +9,15 @@
 
 # Prism imports
 from prism.agents.base import Agent
 import prism.constants
 import prism.event_managers.base
 import prism.exceptions
 from prism.infra.project import PrismProject
-import prism.logging
+import prism.prism_logging
 from prism.triggers import TriggerManager
 import prism.ui
 
 # Standard library imports
 import argparse
 import docker
 import os
@@ -69,25 +69,25 @@
             if "server_url" in self.agent_conf.keys():
                 server_url = self.agent_conf["server_url"]
 
                 # If the specified server URL is blank, then default to
                 # "unix://var/run/docker.sock"
                 if server_url == "" or server_url is None:
                     if self.args.which in ["agent-apply", "agent-build"]:
-                        prism.logging.fire_console_event(
-                            prism.logging.DefaultServerURLEvent()
+                        prism.prism_logging.fire_console_event(
+                            prism.prism_logging.DefaultServerURLEvent()
                         )
-                        prism.logging.fire_empty_line_event()
+                        prism.prism_logging.fire_empty_line_event()
                     server_url = prism.constants.DEFAULT_SERVER_URL
             else:
                 if self.args.which in ["agent-apply", "agent-build"]:
-                    prism.logging.fire_console_event(
-                        prism.logging.DefaultServerURLEvent()
+                    prism.prism_logging.fire_console_event(
+                        prism.prism_logging.DefaultServerURLEvent()
                     )
-                    prism.logging.fire_empty_line_event()
+                    prism.prism_logging.fire_empty_line_event()
                 server_url = prism.constants.DEFAULT_SERVER_URL
 
             # In addition, create a low-level API client. We need this to capture the
             # logs when actually building the image.
             if SERVER_URL is not None:
                 self.build_client = docker.APIClient(base_url=SERVER_URL)
             else:
@@ -125,16 +125,16 @@
                 try:
                     _ = img_names[img_versions.index(latest_version_str)]
                 except KeyError:
                     raise prism.exceptions.RuntimeException(
                         message=f"could not find image associated with `{latest_version_str}`"  # noqa: E501
                     )
 
-                prism.logging.fire_console_event(
-                    prism.logging.MultipleAgentsFound(
+                prism.prism_logging.fire_console_event(
+                    prism.prism_logging.MultipleAgentsFound(
                         self.image_name, latest_version_str
                     ),
                     log_level='warn'
                 )
 
                 self.image_version = latest_version_str
 
@@ -458,15 +458,15 @@
                 for stm in streams:
                     if "stream" in stm:
                         log = json.loads(
                             stm.replace('\r', '').replace('\\n', '')
                         )["stream"]
                         if len(re.findall(r'^\s*$', log)) > 0:
                             continue
-                        prism.logging.DEFAULT_LOGGER.agent(  # type: ignore
+                        prism.prism_logging.DEFAULT_LOGGER.agent(  # type: ignore
                             f"{prism.ui.AGENT_EVENT}{self.image_name}:{new_img_version}{prism.ui.AGENT_WHICH_BUILD}[build]{prism.ui.RESET} | {log}"  # noqa: E501
                         )
 
         # Remove the old image
         if self.image_version is not None:
             client.images.remove(
                 image=f"{self.image_name}:{self.image_version}",
@@ -492,31 +492,31 @@
 
         # Get the container logs
         container = client.containers.get(container_id=container.id)
         for log in container.logs(stream=True, stdout=True, stderr=True):
             log_str = log.decode('utf-8')
             no_newline = log_str.replace("\n", "")
             if not re.findall(r"^[\-]+$", no_newline):
-                prism.logging.DEFAULT_LOGGER.agent(  # type: ignore
+                prism.prism_logging.DEFAULT_LOGGER.agent(  # type: ignore
                     f"{prism.ui.AGENT_EVENT}{self.image_name}:{self.image_version}{prism.ui.AGENT_WHICH_RUN}[run]{prism.ui.RESET} | {no_newline}"  # noqa: E501
                 )
         return
 
     def delete(self):
         """
         Delete the Docker agent
         """
         # Fire an empty line event... it just looks nicer
-        prism.logging.fire_empty_line_event()
+        prism.prism_logging.fire_empty_line_event()
         log_prefix = f"{prism.ui.AGENT_EVENT}{self.image_name}:{self.image_version}{prism.ui.RED}[delete]{prism.ui.RESET}"  # noqa: E501
 
         # Remove all images with the label "stage=intermediate"
         images = client.images.list(
             filters={"label": "stage=intermediate"}
         )
         for img in images:
-            prism.logging.DEFAULT_LOGGER.agent(  # type: ignore
+            prism.prism_logging.DEFAULT_LOGGER.agent(  # type: ignore
                 f"{log_prefix} | Deleting image {prism.ui.MAGENTA}{img.tags[0]}{prism.ui.RESET}"  # noqa: E501
             )
             client.images.remove(
                 image=img.tags[0]
             )
```

### Comparing `prism-ds-0.1.9rc2/prism/agents/ec2.py` & `prism-ds-0.2.0rc1/prism/agents/ec2.py`

 * *Files 6% similar despite different names*

```diff
@@ -9,15 +9,15 @@
 
 # Prism imports
 from prism.agents.base import Agent
 import prism.constants
 import prism.event_managers.base
 import prism.exceptions
 from prism.infra.project import PrismProject
-import prism.logging
+import prism.prism_logging
 from prism.triggers import TriggerManager
 import prism.ui
 from prism.mixins.aws import AwsMixin
 import urllib.request
 
 # Standard library imports
 import argparse
@@ -517,55 +517,55 @@
         # Create PEM key pair
         if resources["key_pair"] is None:
             pem_key_path = self.create_key_pair(
                 ec2_client,
                 key_name=instance_name,
             )
             log_instance_name = f"{prism.ui.MAGENTA}{instance_name}{prism.ui.RESET}"
-            prism.logging.DEFAULT_LOGGER.agent(  # type: ignore
+            prism.prism_logging.DEFAULT_LOGGER.agent(  # type: ignore
                 f"{log_prefix} | Created key pair {log_instance_name}"
             )
         else:
             # If the key-pair exists, then the location of the PEM key path should be
             # contained in ~/.prism/ec2.json. If it isn't, then either:
             #   1. The user manually created the key pair
             #   2. The user deleted ~/.prism/ec2.json
             if not Path(prism.constants.INTERNAL_FOLDER / 'ec2.json').is_file():
                 raise _create_exception("key-pair")
             pem_key_path = self.pem_key_path
 
             # Log
             log_instance_name = f"{prism.ui.MAGENTA}{instance_name}{prism.ui.RESET}"  # noqa: E501
             log_instance_path = f"{prism.ui.MAGENTA}{str(pem_key_path)}{prism.ui.RESET}"  # noqa: E501
-            prism.logging.DEFAULT_LOGGER.agent(  # type: ignore
+            prism.prism_logging.DEFAULT_LOGGER.agent(  # type: ignore
                 f"{log_prefix} | Using existing key-pair {log_instance_name} at {log_instance_path}"  # noqa: E501
             )
 
         # Security group
         if resources["security_group"] is None:
             security_group_id, vpc_id = self.create_new_security_group(
                 ec2_client,
                 instance_name
             )
 
             # Log
             log_security_group_id = f"{prism.ui.MAGENTA}{security_group_id}{prism.ui.RESET}"  # noqa: E501
             log_vpc_id = f"{prism.ui.MAGENTA}{vpc_id}{prism.ui.RESET}"  # noqa: E501
-            prism.logging.DEFAULT_LOGGER.agent(  # type: ignore
+            prism.prism_logging.DEFAULT_LOGGER.agent(  # type: ignore
                 f"{log_prefix} | Created security group with ID {log_security_group_id} in VPC {log_vpc_id}"  # noqa: E501
             )
         else:
             if not Path(prism.constants.INTERNAL_FOLDER / 'ec2.json').is_file():
                 raise _create_exception("security group")
 
             # Log
             security_group_id = self.security_group_id
             self.check_ingress_ip(ec2_client, security_group_id)
             log_security_group_id = f"{prism.ui.MAGENTA}{security_group_id}{prism.ui.RESET}"  # noqa: E501
-            prism.logging.DEFAULT_LOGGER.agent(  # type: ignore
+            prism.prism_logging.DEFAULT_LOGGER.agent(  # type: ignore
                 f"{log_prefix} | Using existing security group {log_security_group_id}"
             )
 
         # Log instance ID template
         log_instance_id_template = f"{prism.ui.MAGENTA}{{instance_id}}{prism.ui.RESET}"
 
         # Instance
@@ -590,25 +590,25 @@
                 SecurityGroupIds=[
                     security_group_id
                 ]
             )
             instance_id = instance[0].id
 
             # Log
-            prism.logging.DEFAULT_LOGGER.agent(  # type: ignore
+            prism.prism_logging.DEFAULT_LOGGER.agent(  # type: ignore
                 f"{log_prefix} | Created EC2 instance with ID {log_instance_id_template.format(instance_id=instance_id)}"  # noqa: E501
             )
             time.sleep(1)
         else:
             if not Path(prism.constants.INTERNAL_FOLDER / 'ec2.json').is_file():
                 raise _create_exception("instance")
             instance_id = self.instance_id
 
             # Log
-            prism.logging.DEFAULT_LOGGER.agent(  # type: ignore
+            prism.prism_logging.DEFAULT_LOGGER.agent(  # type: ignore
                 f"{log_prefix} | Using existing EC2 instance with ID {log_instance_id_template.format(instance_id=instance_id)}"  # noqa: E501
             )
 
         # Instance data
         resp = self.check_instance_data(ec2_client, instance_id)
 
         # If the instance exists but its key-name is not `instance_name` (this really
@@ -621,15 +621,15 @@
 
         # If the instance exists and is running, then just return
         elif len(resp.keys()) > 0 and resp["state"] in [State.PENDING, State.RUNNING]:
             while resp["state"] == State.PENDING:
 
                 # Log
                 log_pending_status = f"{prism.ui.YELLOW}pending{prism.ui.RESET}"
-                prism.logging.DEFAULT_LOGGER.agent(  # type: ignore
+                prism.prism_logging.DEFAULT_LOGGER.agent(  # type: ignore
                     f"{log_prefix} | Instance {log_instance_id_template.format(instance_id=instance_id)} is `{log_pending_status}`... checking again in 5 seconds"  # noqa: E501
                 )
                 resp = self.check_instance_data(
                     ec2_client,
                     instance_id
                 )
                 time.sleep(5)
@@ -816,20 +816,20 @@
         color: str,
         which: str,
         output: Any,
     ):
         if output:
             if isinstance(output, str):
                 if not re.findall(r"^[\-]+$", output.rstrip()):
-                    prism.logging.DEFAULT_LOGGER.agent(  # type: ignore
+                    prism.prism_logging.DEFAULT_LOGGER.agent(  # type: ignore
                         f"{prism.ui.AGENT_EVENT}{self.instance_name}{color}[{which}]{prism.ui.RESET} | {output.rstrip()}"  # noqa: E501
                     )
             else:
                 if not re.findall(r"^[\-]+$", output.decode().rstrip()):
-                    prism.logging.DEFAULT_LOGGER.agent(  # type: ignore
+                    prism.prism_logging.DEFAULT_LOGGER.agent(  # type: ignore
                         f"{prism.ui.AGENT_EVENT}{self.instance_name}{color}[{which}]{prism.ui.RESET} | {output.decode().rstrip()}"  # noqa: E501
                     )
 
     def stream_logs(self,
         cmd: List[str],
         color: str,
         which: str
@@ -869,15 +869,15 @@
         return process.stdout, process.stderr
 
     def apply(self):
         """
         Create the EC2 instance image
         """
         # Fire an empty line -- it just looks a little nicer
-        prism.logging.fire_console_event(prism.logging.EmptyLineEvent())
+        prism.prism_logging.fire_console_event(prism.prism_logging.EmptyLineEvent())
 
         # Instance type
         instance_type = self.parse_instance_type(self.agent_conf)
 
         # requirements.txt path
         requirements_txt_path = Path(self.parse_requirements(self.agent_conf))
 
@@ -925,15 +925,15 @@
         Run the project using the EC2 agent
         """
         # Full command
         full_cmd = self.construct_command()
 
         # Logging styling
         if self.instance_name is None or self.instance_id is None:
-            prism.logging.DEFAULT_LOGGER.agent(  # type: ignore
+            prism.prism_logging.DEFAULT_LOGGER.agent(  # type: ignore
                 "Agent data not found! Use `prism agent apply` to create your agent"
             )
             return
 
         # Check the ingress rules
         if self.security_group_id is not None:
             self.check_ingress_ip(self.ec2_client, self.security_group_id)
@@ -947,89 +947,89 @@
             '-d', str(self.project.project_dir),
             '-c', full_cmd,
         ]
         out, _ = self.stream_logs(cmd, prism.ui.AGENT_WHICH_RUN, "run")
 
         # Log anything from stdout that was printed in the project
         for line in out.readlines():
-            prism.logging.DEFAULT_LOGGER.agent(  # type: ignore
+            prism.prism_logging.DEFAULT_LOGGER.agent(  # type: ignore
                 f"{prism.ui.AGENT_EVENT}{self.instance_name}{prism.ui.AGENT_WHICH_RUN}[run]{prism.ui.RESET} | {line.rstrip()}"  # noqa: E501
             )
 
     def delete(self):
         """
         Delete all resources associated with agent. This includes:
             - Key pair
             - Security group
             - Instance
 
         In addition, remove the PEM key from our local files
         """
         # Fire an empty line -- it just looks a little nicer
-        prism.logging.fire_console_event(prism.logging.EmptyLineEvent())
+        prism.prism_logging.fire_console_event(prism.prism_logging.EmptyLineEvent())
 
         # Logging styling
         if self.instance_name is None:
-            prism.logging.DEFAULT_LOGGER.agent(  # type: ignore
+            prism.prism_logging.DEFAULT_LOGGER.agent(  # type: ignore
                 "Agent data not found! Did you manually delete the ~/.prism/ec2.json file?"  # noqa: E501
             )
             return
 
         # Logging styling
         log_prefix = f"{prism.ui.AGENT_EVENT}{self.instance_name}{prism.ui.RED}[delete]{prism.ui.RESET}"  # noqa: E501
 
         # Key pair
         if self.key_name is None:
-            prism.logging.DEFAULT_LOGGER.agent(  # type: ignore
+            prism.prism_logging.DEFAULT_LOGGER.agent(  # type: ignore
                 f"{log_prefix} | No agent data found!"
             )
         else:
             log_key_pair = f"{prism.ui.MAGENTA}{self.key_name}{prism.ui.RESET}"
             log_key_path = f"{prism.ui.MAGENTA}{str(self.pem_key_path)}{prism.ui.RESET}"
-            prism.logging.DEFAULT_LOGGER.agent(  # type: ignore
+            prism.prism_logging.DEFAULT_LOGGER.agent(  # type: ignore
                 f"{log_prefix} | Deleting key-pair {log_key_pair} at {log_key_path}"
             )
             self.ec2_client.delete_key_pair(
                 KeyName=self.key_name
             )
             os.unlink(str(self.pem_key_path))
 
         # Instance
         if self.instance_id is None:
-            prism.logging.DEFAULT_LOGGER.agent(  # type: ignore
+            prism.prism_logging.DEFAULT_LOGGER.agent(  # type: ignore
                 f"{log_prefix} | No instance found!"
             )
         else:
             log_instance_id = f"{prism.ui.MAGENTA}{self.instance_id}{prism.ui.RESET}"
-            prism.logging.DEFAULT_LOGGER.agent(  # type: ignore
+            prism.prism_logging.DEFAULT_LOGGER.agent(  # type: ignore
                 f"{log_prefix} | Deleting instance {log_instance_id}"
             )
             _ = self.ec2_client.terminate_instances(
                 InstanceIds=[self.instance_id]
             )
 
         # Security group
         if self.security_group_id is None:
-            prism.logging.DEFAULT_LOGGER.agent(  # type: ignore
+            prism.prism_logging.DEFAULT_LOGGER.agent(  # type: ignore
                 f"{log_prefix} | No security group found! If this is a mistake, then you may need to reset your resource data"  # noqa: E501
             )
         else:
             log_security_group_id = f"{prism.ui.MAGENTA}{self.security_group_id}{prism.ui.RESET}"  # noqa: E501
             while True:
                 try:
                     self.ec2_client.delete_security_group(
                         GroupId=self.security_group_id
                     )
-                    prism.logging.DEFAULT_LOGGER.agent(  # type: ignore
+                    prism.prism_logging.DEFAULT_LOGGER.agent(  # type: ignore
                         f"{log_prefix} | Deleting security group {log_security_group_id}"  # noqa: E501
                     )
                     break
                 except botocore.exceptions.ClientError as e:
                     if "DependencyViolation" in str(e):
-                        prism.logging.DEFAULT_LOGGER.agent(  # type: ignore
+                        prism.prism_logging.DEFAULT_LOGGER.agent(  # type: ignore
                             f"{log_prefix} | Encountered `DependencyViolation` when deleting security group {log_security_group_id}...waiting 5 seconds and trying again"  # noqa: E501
                         )
                         time.sleep(5)
                     else:
                         raise e
 
         # Remove the data
```

### Comparing `prism-ds-0.1.9rc2/prism/agents/meta.py` & `prism-ds-0.2.0rc1/prism/agents/meta.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/agents/scripts/apply.sh` & `prism-ds-0.2.0rc1/prism/agents/scripts/apply.sh`

 * *Files 3% similar despite different names*

```diff
@@ -12,15 +12,15 @@
 		e) env=${OPTARG};;
 	esac
 done
 
 # ssh into the project so that we can authenticate our key
 while true
 do
-  	ssh -i "${pem_path}" "${user}@${public_dns_name}" exit 2>/dev/null 2>&1
+  	ssh -o "StrictHostKeyChecking no" -i "${pem_path}" "${user}@${public_dns_name}" exit 2>/dev/null 2>&1
     if [ $? -eq 0 ]; then
         echo "SSH connection succeeded!"
         break
     else
         echo "SSH connection failed. Retrying in 5 seconds..."
         sleep 5
     fi
@@ -76,14 +76,15 @@
 SED_COMMAND=""
 for keyvalue in "${env_array[@]}"; do
 	IFS='=' read -r key value <<< "${keyvalue}"
 
 	# Update the key-value pair in .bashrc if it exists
     if ssh -i ${pem_path} ${user}@${public_dns_name} "grep -q '^export ${key}=' ~/.bashrc"; then
         ssh -i ${pem_path} ${user}@${public_dns_name} "sed -i 's/^export ${key}=.*$/export ${key}=${value}/' ~/.bashrc"
+
     # Add the new key-value pair to the end of .bashrc if it doesn't exist
     else
         ssh -i ${pem_path} ${user}@${public_dns_name} "echo 'export ${key}=${value}' >> ~/.bashrc"
     fi
 done
 
 # Reload .bashrc to update environment variables
```

### Comparing `prism-ds-0.1.9rc2/prism/agents/scripts/run.sh` & `prism-ds-0.2.0rc1/prism/agents/scripts/run.sh`

 * *Files 12% similar despite different names*

```diff
@@ -12,15 +12,15 @@
 done
 
 
 
 # Test the SSH connection
 while true
 do
-  	ssh -i "${pem_path}" "${user}@${public_dns_name}" exit 2>/dev/null 2>&1
+  	ssh -o "StrictHostKeyChecking no" -i "${pem_path}" "${user}@${public_dns_name}" exit 2>/dev/null 2>&1
     if [ $? -eq 0 ]; then
         break
     else
         echo "SSH connection failed. Retrying in 5 seconds..."
         sleep 5
     fi
 done
```

### Comparing `prism-ds-0.1.9rc2/prism/cli/agent.py` & `prism-ds-0.2.0rc1/prism/cli/agent.py`

 * *Files 2% similar despite different names*

```diff
@@ -17,16 +17,16 @@
 import prism.cli.run
 from prism.event_managers import base as base_event_manager
 import prism.mixins.agent
 import prism.mixins.run
 import prism.exceptions
 import prism.constants
 from prism.infra.project import PrismProject
-import prism.logging
-from prism.logging import fire_console_event, fire_empty_line_event, Event
+import prism.prism_logging
+from prism.prism_logging import fire_console_event, fire_empty_line_event, Event
 from prism.agents.meta import MetaAgent
 from prism.agents import meta  # noqa: F401
 
 # Ohter library imports
 import importlib
 import json
 from pathlib import Path
@@ -130,15 +130,15 @@
         Create and/or run the project on an agent.
         """
         # Event list
         event_list: List[Event] = []
 
         # Separator event
         event_list = fire_console_event(
-            prism.logging.SeparatorEvent(),
+            prism.prism_logging.SeparatorEvent(),
             event_list
         )
 
         # Get project directory
         self.project_dir = prism.cli.base.get_project_dir()
         os.chdir(str(self.project_dir))
 
@@ -189,26 +189,26 @@
         # ------------------------------------------------------------------------------
         # Delete the agent
 
         # If the user wants to delete the agent, then execute the delete function and
         # return
         if self.args.which == "agent-delete":
             event_list = fire_console_event(
-                prism.logging.DeletingAgentEvent(),
+                prism.prism_logging.DeletingAgentEvent(),
                 event_list
             )
 
         # ------------------------------------------------------------------------------
         # Create the agent
 
         # Fire a log event indicating that we're creating the agent (we only do this for
         # `agent-apply` and `agent-build`).
         elif self.args.which in ["agent-apply", "agent-build"]:
             event_list = fire_console_event(
-                prism.logging.CreatingAgentEvent(),
+                prism.prism_logging.CreatingAgentEvent(),
                 event_list
             )
 
         # The build_agent function will only actually *build* the agent if `agent-apply`
         # or `agent-build` is called. Otherwise, it will just instantiate the Agent
         # object and return it.
         build_manager = base_event_manager.BaseEventManager(
@@ -246,15 +246,15 @@
 
         if self.args.which in ["agent-apply", "agent-build"]:
             event_list = fire_empty_line_event(event_list)
 
         # Only execute the agent with `agent-run` or `agent-build`
         if self.args.which in ["agent-run", "agent-build"]:
             event_list = fire_console_event(
-                prism.logging.StreamingLogsStartEvent(),
+                prism.prism_logging.StreamingLogsStartEvent(),
                 event_list
             )
             event_list = fire_empty_line_event(event_list)
 
             agent_event_manager = base_event_manager.BaseEventManager(
                 idx=None,
                 total=None,
@@ -280,18 +280,18 @@
                 )
                 event_list = self.fire_tail_event(event_list)
                 return prism.cli.base.TaskRunReturnResult(event_list, True)
 
             # Now, we're done streaming logs
             event_list = fire_empty_line_event()
             event_list = fire_console_event(
-                prism.logging.StreamingLogsEndEvent(),
+                prism.prism_logging.StreamingLogsEndEvent(),
                 event_list
             )
 
         # Tail events
         event_list = fire_console_event(
-            prism.logging.SeparatorEvent(),
+            prism.prism_logging.SeparatorEvent(),
             event_list
         )
 
         return prism.cli.base.TaskRunReturnResult(event_list, False)
```

### Comparing `prism-ds-0.1.9rc2/prism/cli/base.py` & `prism-ds-0.2.0rc1/prism/cli/base.py`

 * *Files 4% similar despite different names*

```diff
@@ -17,16 +17,16 @@
 import os
 from pathlib import Path
 from typing import List, Tuple, Union
 
 # Prism-specific imports
 from prism.event_managers import base as base_event_manager
 import prism.exceptions
-import prism.logging
-from prism.logging import fire_console_event, fire_empty_line_event, Event
+import prism.prism_logging
+from prism.prism_logging import fire_console_event, fire_empty_line_event, Event
 from prism.mixins import base as base_mixins
 
 
 #####################
 # Functions / utils #
 #####################
 
@@ -91,15 +91,15 @@
 
 class TaskRunReturnResult:
     """
     Return result for tasks
     """
 
     def __init__(self,
-        event_list: List[prism.logging.Event],
+        event_list: List[prism.prism_logging.Event],
         has_error: bool = False
     ):
         self.event_list = event_list
         self.has_error = has_error
 
     def get_results(self):
         return ' | '.join([x.__str__() for x in self.event_list])
@@ -108,70 +108,70 @@
 class BaseTask(base_mixins.BaseMixin):
     """
     Interface for defining common behavior of tasks
     """
 
     def __init__(self, args):
         self.args = args
-        prism.logging.set_up_logger(self.args)
+        prism.prism_logging.set_up_logger(self.args)
 
     @classmethod
     def task_from_args(cls, args):
         return cls(args)
 
     def fire_header_events(self,
-        event_list: List[prism.logging.Event] = []
-    ) -> Tuple[List[prism.logging.Event], Union[Path, None]]:
+        event_list: List[prism.prism_logging.Event] = []
+    ) -> Tuple[List[prism.prism_logging.Event], Union[Path, None]]:
         """
         Fire header events that should be displayed at the beginning of all tasks
         (except the init task)
         """
         # Empty list for events
         base_event_list: List[Event] = []
 
         # Fire header events
         event_list = fire_console_event(
-            prism.logging.SeparatorEvent(), base_event_list, 1, 'info'
+            prism.prism_logging.SeparatorEvent(), base_event_list, 1, 'info'
         )
         event_list = fire_console_event(
-            prism.logging.TaskRunEvent(version=prism.constants.VERSION),
+            prism.prism_logging.TaskRunEvent(version=prism.constants.VERSION),
             event_list,
             0,
             'info'
         )
 
         # Get project directory
         try:
             project_dir = get_project_dir()
             event_list = fire_console_event(
-                prism.logging.CurrentProjectDirEvent(project_dir),
+                prism.prism_logging.CurrentProjectDirEvent(project_dir),
                 event_list,
                 0,
                 'info'
             )
             return event_list, project_dir
 
         # If project directory not found, fire an event
         except prism.exceptions.ProjectPyNotFoundException as err:
             event_list = fire_empty_line_event(event_list)
-            e = prism.logging.ProjectPyNotFoundEvent(err)
+            e = prism.prism_logging.ProjectPyNotFoundEvent(err)
             event_list = fire_console_event(e, event_list, log_level='error')
             event_list = self.fire_tail_event(event_list)
             return event_list, None
 
     def fire_tail_event(self,
-        event_list: List[prism.logging.Event] = []
-    ) -> List[prism.logging.Event]:
+        event_list: List[prism.prism_logging.Event] = []
+    ) -> List[prism.prism_logging.Event]:
         """
         Fire tail event
         """
         # Fire a separator event to indicate the end of a run. Note, this will
         # only fire if --quietly isn't invoked
-        event_list = prism.logging.fire_console_event(
-            prism.logging.SeparatorEvent(),
+        event_list = prism.prism_logging.fire_console_event(
+            prism.prism_logging.SeparatorEvent(),
             event_list,
             sleep=0,
             log_level='info'
         )
         return event_list
 
     def run(self):
```

### Comparing `prism-ds-0.1.9rc2/prism/cli/compile.py` & `prism-ds-0.2.0rc1/prism/cli/create_task.py`

 * *Files 26% similar despite different names*

```diff
@@ -1,183 +1,147 @@
 """
-Compile task class definition, called via `prism compile`
+Class associated with `prism create task` CLI command.
 
 Table of Contents
 - Imports
 - Class definition
 """
 
 
 ###########
 # Imports #
 ###########
 
-# Standard library imports
-import os
-import argparse
-from pathlib import Path
-from typing import List, Optional, Union
-
 # Prism-specific imports
+import importlib
 import prism.cli.base
+import prism.mixins.create_task
 import prism.mixins.compile
 import prism.exceptions
 import prism.constants
-import prism.logging
-from prism.logging import fire_console_event, fire_empty_line_event
+import prism.prism_logging
+from prism.prism_logging import fire_console_event, fire_empty_line_event
 from prism.event_managers.base import BaseEventManager, EventManagerOutput
-from prism.infra.project import PrismProject
+
+# Other imports
+from jinja2 import Environment, BaseLoader
 
 
 ####################
 # Class definition #
 ####################
 
-class CompileTask(prism.cli.base.BaseTask, prism.mixins.compile.CompileMixin):
+class CreateTaskTask(
+    prism.cli.base.BaseTask,
+    prism.mixins.compile.CompileMixin,
+    prism.mixins.create_task.CreateTaskMixins
+):
     """
-    Class for compiling a prism project and computing the DAG
+    Class for creating tasks. This is accessed via the `prism create task`.
     """
 
     def run(self) -> prism.cli.base.TaskRunReturnResult:
         """
-        Run the compile task. This task is executed when the user runs the compile task
-        from the CLI.
+        Create new task(s) according to the user's specifications
         """
 
         # ------------------------------------------------------------------------------
-        # Fire header events
+        # Fire header events, get prism project
 
-        event_list, project_dir = self.fire_header_events()
-        if project_dir is None:
-            return prism.cli.base.TaskRunReturnResult(event_list)
-        os.chdir(project_dir)
+        task_return_result: prism.cli.base.TaskRunReturnResult = super().run()
+        if task_return_result.has_error:
+            return task_return_result
+        event_list = task_return_result.event_list
+        event_list = fire_empty_line_event(event_list)
 
         # ------------------------------------------------------------------------------
-        # Define directories and get modules to compile
+        # Define task type, task number, and task name
 
-        compiled_dir = self.create_compiled_dir(project_dir)
+        task_type = self.args.type
+        decorated = self.args.decorated
 
-        # Modules directory
-        try:
-            modules_dir = self.get_modules_dir(project_dir)
-        except prism.exceptions.CompileException as err:
-            e = prism.logging.PrismExceptionErrorEvent(
-                err,
-                'accessing modules directory'
+        # If adapter type is None, throw an error
+        if task_type is None:
+            e = prism.prism_logging.InvalidType(
+                "task",
+                prism.constants.VALID_TASK_TYPES
             )
-            event_list = fire_console_event(e, event_list, 0, 'error')
+            event_list = fire_console_event(e, event_list, 0, log_level='error')
             event_list = self.fire_tail_event(event_list)
-            return prism.cli.base.TaskRunReturnResult(event_list, True)
+            return prism.cli.base.TaskRunReturnResult(event_list)
 
-        # Get modules to compile
-        user_arg_modules = self.user_arg_modules(self.args, modules_dir)
-        all_modules = self.get_modules(modules_dir)
-        event_list = fire_empty_line_event(event_list)
+        # Grab the template
+        if decorated:
+            template_module = importlib.import_module(
+                name=f"prism.templates.tasks.{task_type}_dec"
+            )
+        else:
+            template_module = importlib.import_module(
+                name=f"prism.templates.tasks.{task_type}_cls"
+            )
+        template = template_module.TEMPLATE
+        task_template = Environment(loader=BaseLoader).from_string(template)  # type: ignore # noqa: E501
+
+        # Get the number of tasks to create and the task name
+        task_number = self.args.number
+        user_task_name = self.args.name
+
+        # Get directory. If it's blank, then new tasks should be dumped into the
+        # `modules/` directory. Otherwise, add the inputted directory to the modules
+        # directory.
+        modules_dir = self.get_modules_dir(self.prism_project.project_dir)
+        if self.args.dir == "":
+            task_dir = modules_dir
+        else:
+            task_dir = modules_dir / self.args.dir
+
+        # Fire events
+        event_list = fire_console_event(
+            prism.prism_logging.CreatingTasksEvent(),
+            event_list,
+            log_level='info'
+        )
 
         # ------------------------------------------------------------------------------
-        # Parse module references
+        # Create tasks
 
-        compiler_manager = BaseEventManager(
+        task_manager = BaseEventManager(
             idx=None,
             total=None,
-            name='module DAG',
+            name='creating tasks',
             full_tb=self.args.full_tb,
-            func=self.compile_dag
+            func=self.create_tasks
         )
-        compiled_event_manager_output = compiler_manager.manage_events_during_run(
+        task_manager_output: EventManagerOutput = task_manager.manage_events_during_run(
             event_list=event_list,
-            project_dir=project_dir,
-            compiled_dir=compiled_dir,
-            all_modules=all_modules,
-            user_arg_modules=user_arg_modules
+            fire_exec_events=False,
+            task_number=task_number,
+            task_type=task_type,
+            user_task_name=user_task_name,
+            task_template=task_template,
+            task_dir=task_dir,
+            decorated=decorated,
         )
-        compiled_dag = compiled_event_manager_output.outputs
-        event_to_fire = compiled_event_manager_output.event_to_fire
-        event_list = compiled_event_manager_output.event_list
-        if compiled_dag == 0:
+        output = task_manager_output.outputs
+        event_to_fire = task_manager_output.event_to_fire
+        event_list = task_manager_output.event_list
+        if output == 0:
             event_list = fire_console_event(
                 event_to_fire,
                 event_list,
                 log_level='error'
             )
             event_list = self.fire_tail_event(event_list)
             return prism.cli.base.TaskRunReturnResult(event_list, True)
 
         # Print output message if successfully executed
         event_list = fire_empty_line_event(event_list)
         event_list = fire_console_event(
-            prism.logging.TaskSuccessfulEndEvent(),
+            prism.prism_logging.TaskSuccessfulEndEvent(),
             event_list,
             0,
             log_level='info'
         )
         event_list = self.fire_tail_event(event_list)
 
         # Return
         return prism.cli.base.TaskRunReturnResult(event_list)
-
-    def run_for_subclass(self,
-        args: argparse.Namespace,
-        project_dir: Path,
-        event_list: List[prism.logging.Event],
-        project: Optional[PrismProject] = None,
-        fire_exec_events: bool = True
-    ) -> Union[prism.cli.base.TaskRunReturnResult, EventManagerOutput]:
-        """
-        Run the compile task. This task is executed when the user runs a subclass of the
-        CompileTask (e.g., the RunTask)
-
-        args:
-            args: user arguments
-            project_dir: project directory
-            compiled_dir: directory to store manifest.json
-            event_list: list of events
-            fire_exec_events: bool controlling whether to fire logging events
-        returns:
-            dag: list of modules to run in sorted order
-        """
-
-        # Modules directory
-        try:
-            modules_dir = self.get_modules_dir(project_dir)
-        except prism.exceptions.CompileException as err:
-            e = prism.logging.PrismExceptionErrorEvent(
-                err,
-                'accessing modules directory'
-            )
-            event_list = fire_console_event(e, event_list, 0, log_level='error')
-            event_list = self.fire_tail_event(event_list)
-            return prism.cli.base.TaskRunReturnResult(event_list)
-
-        # Modules to compile
-        user_arg_modules = self.user_arg_modules(self.args, modules_dir)
-        all_modules = self.get_modules(modules_dir)
-
-        # All downstream
-        all_downstream = args.all_downstream
-
-        # Create compiled directory
-        compiled_dir = self.create_compiled_dir(project_dir)
-
-        # Parse module references
-        compiler_manager = BaseEventManager(
-            idx=None,
-            total=None,
-            name='module DAG',
-            full_tb=args.full_tb,
-            func=self.compile_dag
-        )
-        compiled_event_manager_output = compiler_manager.manage_events_during_run(
-            event_list=event_list,
-            fire_exec_events=fire_exec_events,
-            project_dir=project_dir,
-            compiled_dir=compiled_dir,
-            all_modules=all_modules,
-            user_arg_modules=user_arg_modules,
-            user_arg_all_downstream=all_downstream,
-            project=project
-        )
-        compiled_dag = compiled_event_manager_output.outputs
-        if compiled_dag == 0:
-            return compiled_event_manager_output
-
-        return compiled_event_manager_output
```

### Comparing `prism-ds-0.1.9rc2/prism/cli/connect.py` & `prism-ds-0.2.0rc1/prism/cli/connect.py`

 * *Files 3% similar despite different names*

```diff
@@ -12,17 +12,17 @@
 ###########
 
 # Prism-specific imports
 import prism.cli.base
 import prism.mixins.connect
 import prism.exceptions
 import prism.constants
-import prism.logging
+import prism.prism_logging
 from prism.event_managers.base import BaseEventManager
-from prism.logging import fire_console_event, fire_empty_line_event
+from prism.prism_logging import fire_console_event, fire_empty_line_event
 
 
 ####################
 # Class definition #
 ####################
 
 class ConnectTask(prism.cli.base.BaseTask, prism.mixins.connect.ConnectMixin):
@@ -49,34 +49,36 @@
         # Define profile type
 
         adapter_type = self.args.type
 
         # If adapter type is None, throw an error
         if adapter_type is None:
             self.prism_project.cleanup(self.prism_project.run_context)
-            e = prism.logging.InvalidType("adapter", prism.constants.VALID_ADAPTERS)
+            e = prism.prism_logging.InvalidType(
+                "adapter", prism.constants.VALID_ADAPTERS
+            )
             event_list = fire_console_event(e, event_list, 0, log_level='error')
             event_list = self.fire_tail_event(event_list)
             return prism.cli.base.TaskRunReturnResult(event_list)
 
         # If adapter type isn't valid, then throw an error
         elif adapter_type not in prism.constants.VALID_ADAPTERS:
             self.prism_project.cleanup(self.prism_project.run_context)
-            e = prism.logging.InvalidType(
+            e = prism.prism_logging.InvalidType(
                 "adapter",
                 prism.constants.VALID_ADAPTERS,
                 adapter_type
             )
             event_list = fire_console_event(e, event_list, 0, log_level='error')
             event_list = self.fire_tail_event(event_list)
             return prism.cli.base.TaskRunReturnResult(event_list)
 
         # Fire events
         event_list = fire_console_event(
-            prism.logging.SettingUpProfileEvent(),
+            prism.prism_logging.SettingUpProfileEvent(),
             event_list,
             log_level='info'
         )
 
         # ------------------------------------------------------------------------------
         # Get profile YML path
 
@@ -115,14 +117,14 @@
             )
             event_list = self.fire_tail_event(event_list)
             return prism.cli.base.TaskRunReturnResult(event_list)
 
         # Fire footer events
         event_list = fire_empty_line_event(event_list)
         event_list = fire_console_event(
-            prism.logging.TaskSuccessfulEndEvent(),
+            prism.prism_logging.TaskSuccessfulEndEvent(),
             event_list,
             0,
             log_level='info'
         )
         event_list = self.fire_tail_event(event_list)
         return prism.cli.base.TaskRunReturnResult(event_list)
```

### Comparing `prism-ds-0.1.9rc2/prism/cli/create_agent.py` & `prism-ds-0.2.0rc1/prism/cli/create_agent.py`

 * *Files 2% similar despite different names*

```diff
@@ -12,17 +12,17 @@
 ###########
 
 # Prism-specific imports
 import prism.cli.base
 import prism.mixins.create_agent
 import prism.exceptions
 import prism.constants
-import prism.logging
+import prism.prism_logging
 from prism.event_managers.base import BaseEventManager
-from prism.logging import fire_console_event, fire_empty_line_event
+from prism.prism_logging import fire_console_event, fire_empty_line_event
 
 
 ####################
 # Class definition #
 ####################
 
 class CreateAgentTask(
@@ -51,40 +51,40 @@
         # ------------------------------------------------------------------------------
         # Define agent type
 
         agent_type = self.args.type
 
         # If adapter type is None, throw an error
         if agent_type is None:
-            e = prism.logging.InvalidType(
+            e = prism.prism_logging.InvalidType(
                 "agent",
                 prism.constants.VALID_AGENTS
             )
             event_list = fire_console_event(e, event_list, 0, log_level='error')
             event_list = self.fire_tail_event(event_list)
             return prism.cli.base.TaskRunReturnResult(event_list)
 
         # If agent type isn't valid, then throw an error
         elif agent_type not in prism.constants.VALID_AGENTS:
-            e = prism.logging.InvalidType(
+            e = prism.prism_logging.InvalidType(
                 "agent",
                 prism.constants.VALID_AGENTS,
                 agent_type
             )
             event_list = fire_console_event(e, event_list, 0, log_level='error')
             event_list = self.fire_tail_event(event_list)
             return prism.cli.base.TaskRunReturnResult(event_list)
 
         # ------------------------------------------------------------------------------
         # Get agent filepath
 
         from pathlib import Path
         agent_filepath = Path(self.args.file)
         event_list = fire_console_event(
-            prism.logging.CreatingAgentYamlEvent(str(agent_filepath)),
+            prism.prism_logging.CreatingAgentYamlEvent(str(agent_filepath)),
             event_list,
             log_level='info'
         )
 
         # ------------------------------------------------------------------------------
         # Create agent
 
@@ -114,14 +114,14 @@
             )
             event_list = self.fire_tail_event(event_list)
             return prism.cli.base.TaskRunReturnResult(event_list)
 
         # Fire footer events
         event_list = fire_empty_line_event(event_list)
         event_list = fire_console_event(
-            prism.logging.TaskSuccessfulEndEvent(),
+            prism.prism_logging.TaskSuccessfulEndEvent(),
             event_list,
             0,
             log_level='info'
         )
         event_list = self.fire_tail_event(event_list)
         return prism.cli.base.TaskRunReturnResult(event_list)
```

### Comparing `prism-ds-0.1.9rc2/prism/cli/create_trigger.py` & `prism-ds-0.2.0rc1/prism/cli/create_trigger.py`

 * *Files 5% similar despite different names*

```diff
@@ -12,17 +12,17 @@
 ###########
 
 # Prism-specific imports
 import prism.cli.base
 import prism.mixins.create_trigger
 import prism.exceptions
 import prism.constants
-import prism.logging
+import prism.prism_logging
 from prism.event_managers.base import BaseEventManager
-from prism.logging import fire_console_event, fire_empty_line_event
+from prism.prism_logging import fire_console_event, fire_empty_line_event
 
 
 ####################
 # Class definition #
 ####################
 
 class CreateTriggerTask(
@@ -51,36 +51,36 @@
         # ------------------------------------------------------------------------------
         # Define trigger type
 
         trigger_type = self.args.type
 
         # If adapter type is None, throw an error
         if trigger_type is None:
-            e = prism.logging.InvalidType(
+            e = prism.prism_logging.InvalidType(
                 "trigger",
                 prism.constants.VALID_TRIGGER_TYPES
             )
             event_list = fire_console_event(e, event_list, 0, log_level='error')
             event_list = self.fire_tail_event(event_list)
             return prism.cli.base.TaskRunReturnResult(event_list)
 
         # If adapter type isn't valid, then throw an error
         elif trigger_type not in prism.constants.VALID_TRIGGER_TYPES:
-            e = prism.logging.InvalidType(
+            e = prism.prism_logging.InvalidType(
                 "trigger",
                 prism.constants.VALID_TRIGGER_TYPES,
                 trigger_type
             )
             event_list = fire_console_event(e, event_list, 0, log_level='error')
             event_list = self.fire_tail_event(event_list)
             return prism.cli.base.TaskRunReturnResult(event_list)
 
         # Fire events
         event_list = fire_console_event(
-            prism.logging.CreatingTriggersEvent(),
+            prism.prism_logging.CreatingTriggersEvent(),
             event_list,
             log_level='info'
         )
 
         # ------------------------------------------------------------------------------
         # Get triggers dir
 
@@ -118,14 +118,14 @@
             )
             event_list = self.fire_tail_event(event_list)
             return prism.cli.base.TaskRunReturnResult(event_list)
 
         # Fire footer events
         event_list = fire_empty_line_event(event_list)
         event_list = fire_console_event(
-            prism.logging.TaskSuccessfulEndEvent(),
+            prism.prism_logging.TaskSuccessfulEndEvent(),
             event_list,
             0,
             log_level='info'
         )
         event_list = self.fire_tail_event(event_list)
         return prism.cli.base.TaskRunReturnResult(event_list)
```

### Comparing `prism-ds-0.1.9rc2/prism/cli/graph.py` & `prism-ds-0.2.0rc1/prism/cli/graph.py`

 * *Files 5% similar despite different names*

```diff
@@ -19,16 +19,16 @@
 from http.server import SimpleHTTPRequestHandler
 from socketserver import TCPServer
 import sys
 
 # Prism-specific imports
 import prism.cli.base
 import prism.cli.compile
-import prism.logging
-from prism.logging import Event, fire_empty_line_event, fire_console_event
+import prism.prism_logging
+from prism.prism_logging import Event, fire_empty_line_event, fire_console_event
 import prism.mixins.graph
 import prism.event_managers.base as base_event_manager
 
 
 class GraphTask(prism.cli.compile.CompileTask, prism.mixins.graph.GraphMixin):
     """
     Class for generating Prism documentation
@@ -114,15 +114,15 @@
         def handler(signum, frame):
             nonlocal event_list
             event_list = fire_empty_line_event(event_list)
             res = input('Shutdown the Prism docs server (y/n)? ')
             if res == "y":
                 event_list = fire_empty_line_event(event_list)
                 event_list = fire_console_event(
-                    prism.logging.TaskSuccessfulEndEvent(),
+                    prism.prism_logging.TaskSuccessfulEndEvent(),
                     event_list,
                     0,
                     log_level='info'
                 )
                 event_list = self.fire_tail_event(event_list)
                 sys.exit(0)
             else:
@@ -134,19 +134,19 @@
         # Serve the docs
         os.chdir(build_path)
         port = self.args.port
         address = "0.0.0.0"
 
         event_list = fire_empty_line_event(event_list)
         event_list = fire_console_event(
-            prism.logging.ServingDocsEvent(address=address, port=port),
+            prism.prism_logging.ServingDocsEvent(address=address, port=port),
             log_level='info'
         )
         event_list = fire_console_event(
-            prism.logging.ServingDocsExitInfo(),
+            prism.prism_logging.ServingDocsExitInfo(),
             log_level='info'
         )
         event_list = fire_empty_line_event(event_list)
 
         # mypy doesn't think SimpleHTTPRequestHandler is ok here, but it is
         httpd = TCPServer(  # type: ignore
             (address, port), SimpleHTTPRequestHandler  # type: ignore
```

### Comparing `prism-ds-0.1.9rc2/prism/cli/init.py` & `prism-ds-0.2.0rc1/prism/cli/init.py`

 * *Files 6% similar despite different names*

```diff
@@ -19,16 +19,16 @@
 from pathlib import Path
 from typing import List
 
 # Prism-specific imports
 import prism.cli.base
 import prism.exceptions
 import prism.constants
-import prism.logging
-from prism.logging import Event, fire_console_event, fire_empty_line_event
+import prism.prism_logging
+from prism.prism_logging import Event, fire_console_event, fire_empty_line_event
 from prism.templates.starter_project import STARTER_PROJECT_TEMPLATE_DIR
 from prism.templates.minimal_project import MINIMAL_PROJECT_TEMPLATE_DIR
 
 
 #############
 # Constants #
 #############
@@ -110,21 +110,21 @@
         """
 
         # Keep track of events
         event_list: List[Event] = []
 
         # Header events
         event_list = fire_console_event(
-            prism.logging.SeparatorEvent(),
+            prism.prism_logging.SeparatorEvent(),
             event_list,
             0,
             log_level='info'
         )
         event_list = fire_console_event(
-            prism.logging.TaskRunEvent(prism.constants.VERSION),
+            prism.prism_logging.TaskRunEvent(prism.constants.VERSION),
             event_list,
             log_level='info'
         )
         event_list = fire_empty_line_event(event_list)
 
         # If the project name wasn't provided by the user, prompt them
         project_name = self.args.project_name
@@ -132,57 +132,57 @@
             project_name = click.prompt("What is the desired project name?")
             event_list = fire_empty_line_event(event_list)
 
         # If the project_name already exists witin the working directory, throw an error
         wkdir = Path.cwd()
         project_dir = wkdir / project_name
         if project_dir.is_dir():
-            e = prism.logging.ProjectAlreadyExistsEvent(str(project_dir))
+            e = prism.prism_logging.ProjectAlreadyExistsEvent(str(project_dir))
             event_list = fire_console_event(e, event_list, 0, log_level='error')
             event_list = fire_console_event(
-                prism.logging.SeparatorEvent(),
+                prism.prism_logging.SeparatorEvent(),
                 event_list,
                 0,
                 log_level='info'
             )
             return prism.cli.base.TaskRunReturnResult(event_list)
 
         # Define template to copy
         if self.args.minimal:
             template_dir = MINIMAL_PROJECT_TEMPLATE_DIR
         else:
             template_dir = STARTER_PROJECT_TEMPLATE_DIR
 
         # Copy starter project into project directory
         event_list = fire_console_event(
-            prism.logging.CreatingProjectDirEvent(),
+            prism.prism_logging.CreatingProjectDirEvent(),
             event_list,
             log_level='info'
         )
         self.create_starter_project_from_template(
             template_dir,
             project_dir,
             project_name
         )
 
         # Init task successful
         event_list = fire_empty_line_event(event_list)
         event_list = fire_console_event(
-            prism.logging.InitSuccessfulEvent(
+            prism.prism_logging.InitSuccessfulEvent(
                 msg=TASK_COMPLETE_MSG.format(
                     project_name=project_name,
                     docs_url='docs.runprism.com'
                 )
             ),
             event_list,
             0,
             log_level='agent'
         )
         event_list = fire_console_event(
-            prism.logging.SeparatorEvent(),
+            prism.prism_logging.SeparatorEvent(),
             event_list,
             0,
             log_level='info'
         )
 
         # Change working directory to the project directory
         os.chdir(project_dir)
```

### Comparing `prism-ds-0.1.9rc2/prism/cli/run.py` & `prism-ds-0.2.0rc1/prism/cli/run.py`

 * *Files 2% similar despite different names*

```diff
@@ -13,16 +13,16 @@
 
 # Prism-specific imports
 import prism.cli.base
 import prism.cli.compile
 import prism.mixins.run
 import prism.exceptions
 import prism.constants
-import prism.logging
-from prism.logging import fire_console_event, fire_empty_line_event
+import prism.prism_logging
+from prism.prism_logging import fire_console_event, fire_empty_line_event
 from prism.event_managers import base as base_event_manager
 from prism.infra import executor as prism_executor
 from prism.triggers import TriggerManager
 
 # Ohter library imports
 import json
 from typing import List, Optional
@@ -34,16 +34,16 @@
 
 class RunTask(prism.cli.compile.CompileTask, prism.mixins.run.RunMixin):
     """
     Class for defining the "run" task
     """
 
     def fire_error_events(self,
-        event_list: List[prism.logging.Event],
-        error_event: Optional[prism.logging.Event],
+        event_list: List[prism.prism_logging.Event],
+        error_event: Optional[prism.prism_logging.Event],
         trigger_manager: TriggerManager
     ):
         """
         Fire error events, including triggers
         """
         # Fire console event
         event_list = fire_console_event(
@@ -176,15 +176,15 @@
             return prism.cli.base.TaskRunReturnResult(event_list, True)
 
         # ------------------------------------------------------------------------------
         # Execute pipeline
 
         event_list = fire_empty_line_event(event_list)
         event_list = fire_console_event(
-            prism.logging.TasksHeaderEvent(msg=self.prism_project.slug),
+            prism.prism_logging.TasksHeaderEvent(msg=self.prism_project.slug),
             event_list
         )
 
         # Manager for executing pipeline.
         pipeline_exec_manager = base_event_manager.BaseEventManager(
             idx=None,
             total=None,
@@ -250,15 +250,15 @@
 
             # Only fire an empty line if we had triggers to execute
             if len(trigger_manager.on_success_triggers) > 0:
                 event_list = fire_empty_line_event(event_list)
 
             # Task is successful
             event_list = fire_console_event(
-                prism.logging.TaskSuccessfulEndEvent(),
+                prism.prism_logging.TaskSuccessfulEndEvent(),
                 event_list,
                 0,
                 log_level='info'
             )
             event_list = self.fire_tail_event(event_list)
 
         # Otherwise, just fire the tail event
```

### Comparing `prism-ds-0.1.9rc2/prism/cli/spark_submit.py` & `prism-ds-0.2.0rc1/prism/cli/spark_submit.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/client/__init__.py` & `prism-ds-0.2.0rc1/prism/client/__init__.py`

 * *Files 4% similar despite different names*

```diff
@@ -28,15 +28,15 @@
 from prism.infra import compiler as prism_compiler
 import prism.mixins.base
 import prism.mixins.compile
 import prism.mixins.connect
 import prism.mixins.run
 import prism.mixins.sys_handler
 from prism.parsers import ast_parser
-import prism.logging
+import prism.prism_logging
 
 
 ####################
 # Class definition #
 ####################
 
 class PrismDAG(
@@ -70,15 +70,15 @@
 
         # Define run context
         self.run_context = prism.constants.CONTEXT.copy()
 
         # Set up default logger
         args = argparse.Namespace()
         args.log_level = self.log_level
-        prism.logging.set_up_logger(args)
+        prism.prism_logging.set_up_logger(args)
 
     def _is_valid_project(self, user_project_dir: Path) -> bool:
         """
         Determine if `user_project_dir` is a valid project (i.e., that is has a
         `prism_project.py` file and a `modules` folder)
 
         args:
```

### Comparing `prism-ds-0.1.9rc2/prism/constants.py` & `prism-ds-0.2.0rc1/prism/constants.py`

 * *Files 0% similar despite different names*

```diff
@@ -13,15 +13,15 @@
 
 
 #############
 # Constants #
 #############
 
 # Version number
-VERSION = '0.1.9rc2'
+VERSION = '0.2.0rc1'
 
 # Root directory of project
 ROOT_DIR = str(Path(os.path.dirname(__file__)).parent)
 
 # Files to ignore when instantiating Prism project
 IGNORE_FILES = ["__pycache__", '*checkpoint.ipynb', '.ipynb_checkpoints']
```

### Comparing `prism-ds-0.1.9rc2/prism/decorators/target.py` & `prism-ds-0.2.0rc1/prism/decorators/target.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/decorators/task.py` & `prism-ds-0.2.0rc1/prism/decorators/task.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/docs/build/311ea03002abadcdcaba.png` & `prism-ds-0.2.0rc1/prism/docs/build/311ea03002abadcdcaba.png`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/docs/build/54968a39190c43d592b9.svg` & `prism-ds-0.2.0rc1/prism/docs/build/54968a39190c43d592b9.svg`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/docs/build/737ad70b3f2d3a9b5f6e.ico` & `prism-ds-0.2.0rc1/prism/docs/build/737ad70b3f2d3a9b5f6e.ico`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/docs/build/ce188596011a8fa32931.png` & `prism-ds-0.2.0rc1/prism/docs/build/ce188596011a8fa32931.png`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/docs/build/index.html` & `prism-ds-0.2.0rc1/prism/docs/build/index.html`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/docs/build/main.js.LICENSE.txt` & `prism-ds-0.2.0rc1/prism/docs/build/main.js.LICENSE.txt`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/event_managers/base.py` & `prism-ds-0.2.0rc1/prism/event_managers/base.py`

 * *Files 12% similar despite different names*

```diff
@@ -13,29 +13,29 @@
 # Standard library imports
 from dataclasses import dataclass
 import sys
 import time
 from typing import Any, Callable, List, Optional, Union
 
 # Prism-specific imports
-import prism.logging
+import prism.prism_logging
 import prism.exceptions
-from prism.logging import Event, fire_console_event, fire_empty_line_event
+from prism.prism_logging import Event, fire_console_event, fire_empty_line_event
 from prism.ui import RED, GREEN, EVENT_COLOR, RESET
 
 
 ####################
 # Class definition #
 ####################
 
 @dataclass
 class EventManagerOutput:
     outputs: Any
-    event_to_fire: Optional[prism.logging.Event]
-    event_list: List[prism.logging.Event]
+    event_to_fire: Optional[prism.prism_logging.Event]
+    event_list: List[prism.prism_logging.Event]
 
 
 class BaseEventManager:
     """
     Class for managing logging events fired by tasks and associated
     functions
     """
@@ -50,56 +50,56 @@
         self.idx = idx
         self.total = total
         self.name = name
         self.full_tb = full_tb
         self.func = func
 
     def fire_running_exec_event(self,
-        event_list: List[prism.logging.Event]
+        event_list: List[prism.prism_logging.Event]
     ):
         """
         Create ExecutionEvent informing user of task execution
         """
-        e = prism.logging.ExecutionEvent(
+        e = prism.prism_logging.ExecutionEvent(
             msg=f"RUNNING EVENT {EVENT_COLOR}'{self.name}'{RESET}",
             num=self.idx,
             total=self.total,
             status="RUN",
             execution_time=None
         )
         event_list = fire_console_event(e, event_list, log_level='info')
         return event_list
 
     def fire_success_exec_event(self,
         start_time: float,
-        event_list: List[prism.logging.Event]
+        event_list: List[prism.prism_logging.Event]
     ) -> List[Event]:
         """
         Create ExecutionEvent informing user of successful task execution
         """
         execution_time = time.time() - start_time
-        e = prism.logging.ExecutionEvent(
+        e = prism.prism_logging.ExecutionEvent(
             msg=f"{GREEN}FINISHED{RESET} EVENT {EVENT_COLOR}'{self.name}'{RESET}",
             num=self.idx,
             total=self.total,
             status="DONE",
             execution_time=execution_time
         )
         event_list = fire_console_event(e, event_list, log_level='info')
         return event_list
 
     def fire_error_exec_event(self,
         start_time: float,
-        event_list: List[prism.logging.Event]
+        event_list: List[prism.prism_logging.Event]
     ) -> List[Event]:
         """
         Create ExecutionEvent informing user of error in task execution
         """
         execution_time = time.time() - start_time
-        e = prism.logging.ExecutionEvent(
+        e = prism.prism_logging.ExecutionEvent(
             msg=f"{RED}ERROR{RESET} IN EVENT {EVENT_COLOR}'{self.name}'{RESET}",
             num=self.idx,
             total=self.total,
             status="ERROR",
             execution_time=execution_time
         )
 
@@ -111,15 +111,15 @@
     def run(self, **kwargs):
         """
         Execute task using inputted function inputted during initialization
         """
         return self.func(**kwargs)
 
     def manage_events_during_run(self,
-        event_list: List[prism.logging.Event],
+        event_list: List[prism.prism_logging.Event],
         fire_exec_events=True,
         fire_empty_line_events=True,
         **kwargs
     ) -> EventManagerOutput:
         """
         Fire relevant event managers
         """
@@ -139,45 +139,45 @@
 
         # If PrismException, then create PrismExceptionErrorEvent
         except prism.exceptions.PrismException as err:
             if fire_exec_events:
                 event_list = self.fire_error_exec_event(start_time, event_list)
             if fire_empty_line_events:
                 event_list = fire_empty_line_event(event_list)
-            prism_exception_event = prism.logging.PrismExceptionErrorEvent(
+            prism_exception_event = prism.prism_logging.PrismExceptionErrorEvent(
                 err, self.name
             )
             return EventManagerOutput(0, prism_exception_event, event_list)
 
         # If SyntaxError, then create ExecutionSyntaxErrorEvent
         except SyntaxError:
             if fire_exec_events:
                 event_list = self.fire_error_exec_event(start_time, event_list)
             if fire_empty_line_events:
                 event_list = fire_empty_line_event(event_list)
             exc_type, exc_value, exc_tb = sys.exc_info()
             if self.full_tb:
-                syntax_error_event = prism.logging.ExecutionSyntaxErrorEvent(
+                syntax_error_event = prism.prism_logging.ExecutionSyntaxErrorEvent(
                     self.name, exc_type, exc_value, exc_tb, True
                 )
             else:
-                syntax_error_event = prism.logging.ExecutionSyntaxErrorEvent(
+                syntax_error_event = prism.prism_logging.ExecutionSyntaxErrorEvent(
                     self.name, exc_type, exc_value, exc_tb, False
                 )
             return EventManagerOutput(0, syntax_error_event, event_list)
 
         # If any other Exception, then create ExecutionErrorEvent
         except Exception:
             if fire_exec_events:
                 event_list = self.fire_error_exec_event(start_time, event_list)
             if fire_empty_line_events:
                 event_list = fire_empty_line_event(event_list)
             exc_type, exc_value, exc_tb = sys.exc_info()
             if self.full_tb:
-                exception_event = prism.logging.ExecutionErrorEvent(
+                exception_event = prism.prism_logging.ExecutionErrorEvent(
                     self.name, exc_type, exc_value, exc_tb, True
                 )
             else:
-                exception_event = prism.logging.ExecutionErrorEvent(
+                exception_event = prism.prism_logging.ExecutionErrorEvent(
                     self.name, exc_type, exc_value, exc_tb, False
                 )
             return EventManagerOutput(0, exception_event, event_list)
```

### Comparing `prism-ds-0.1.9rc2/prism/exceptions.py` & `prism-ds-0.2.0rc1/prism/exceptions.py`

 * *Files 1% similar despite different names*

```diff
@@ -7,14 +7,26 @@
 class PrismException(Exception):
     """
     Parent class for all prismexceptions
     """
     pass
 
 
+class ArgumentException(PrismException):
+    """
+    Exception raised if the user passes a bad argument
+    """
+    def __init__(self, message):
+        self.message = message
+        super().__init__(self.message)
+
+    def __str__(self):
+        return self.message
+
+
 class InvalidProjectException(PrismException):
     """
     Exception raised if project is not valid
     """
 
     def __init__(self, message):
         self.message = message
```

### Comparing `prism-ds-0.1.9rc2/prism/infra/compiler.py` & `prism-ds-0.2.0rc1/prism/infra/compiler.py`

 * *Files 0% similar despite different names*

```diff
@@ -15,15 +15,15 @@
 import networkx as nx
 from pathlib import Path
 from typing import Any, Dict, List, Optional, Tuple
 
 # Prism-specific imports
 import prism.constants
 import prism.exceptions
-import prism.logging
+import prism.prism_logging
 import prism.parsers.ast_parser as ast_parser
 import prism.infra.module
 from prism.infra.manifest import Manifest, ModuleManifest
 from prism.infra.project import PrismProject
 
 
 ####################
@@ -80,15 +80,15 @@
         self.all_modules = all_modules
         self.user_arg_modules = user_arg_modules
         self.project = project
         os.chdir(project_dir)
 
         # Modules can only be executed if their predecessors are explicitly run or have
         # targets. For example, if our DAG is A --> B --> C and we call `prism run
-        # --modules C`, then Prism will parse the execution order, instantiate but NOT
+        # --module C`, then Prism will parse the execution order, instantiate but NOT
         # execute tasks A and B, and then run task C. In other words, A and B will
         # always be instantiated; the --all-upstream argument controls whether A and B
         # are executed.
 
         # This is why we don't need to keep track of the --all-upstream argument; it
         # doesn't affect what our topological sort looks like. However, the
         # --all-downstream argument does, since successors do not need to be
```

### Comparing `prism-ds-0.1.9rc2/prism/infra/executor.py` & `prism-ds-0.2.0rc1/prism/infra/executor.py`

 * *Files 1% similar despite different names*

```diff
@@ -19,16 +19,16 @@
 
 # Prism-specific imports
 import prism.exceptions
 from prism.infra import module as prism_module
 from prism.infra import compiler as prism_compiler
 from prism.infra.task_manager import PrismTaskManager
 from prism.infra.hooks import PrismHooks
-import prism.logging
-from prism.logging import Event, fire_console_event
+import prism.prism_logging
+from prism.prism_logging import Event, fire_console_event
 from prism.event_managers import base as base_event_manager
 from prism.constants import INTERNAL_TASK_MANAGER_VARNAME, INTERNAL_HOOKS_VARNAME
 
 
 ####################
 # Class definition #
 ####################
@@ -172,15 +172,15 @@
         # For testing, keep track of all events
         all_events = []
 
         while num_runs != num_expected_runs and outputs == 0:
             num_runs += 1
             if num_runs > 1:
                 event_list = fire_console_event(
-                    prism.logging.DelayEvent(name, retry_delay_seconds),
+                    prism.prism_logging.DelayEvent(name, retry_delay_seconds),
                     log_level='warn'
                 )
                 time.sleep(retry_delay_seconds)
                 name = module.name + f' (RETRY {num_runs - 1})'
 
             # Only fire empty line if last retry has been executed
             fire_empty_line_events = num_runs == num_expected_runs
```

### Comparing `prism-ds-0.1.9rc2/prism/infra/hooks.py` & `prism-ds-0.2.0rc1/prism/infra/hooks.py`

 * *Files 0% similar despite different names*

```diff
@@ -14,15 +14,15 @@
 import pandas as pd
 from typing import Any, Optional
 
 # Prism-specific imports
 from prism.infra import project as prism_project
 import prism.constants
 import prism.exceptions
-import prism.logging
+import prism.prism_logging
 
 
 ####################
 # Class definition #
 ####################
 
 class PrismHooks:
```

### Comparing `prism-ds-0.1.9rc2/prism/infra/manifest.py` & `prism-ds-0.2.0rc1/prism/infra/manifest.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/infra/module.py` & `prism-ds-0.2.0rc1/prism/infra/module.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/infra/pipeline.py` & `prism-ds-0.2.0rc1/prism/infra/pipeline.py`

 * *Files 2% similar despite different names*

```diff
@@ -15,15 +15,15 @@
 
 # Prism-specific imports
 from prism.infra import project as prism_project
 from prism.infra import executor as prism_executor
 from prism.infra import task_manager, hooks
 import prism.constants
 import prism.exceptions
-import prism.logging
+import prism.prism_logging
 from prism.constants import INTERNAL_TASK_MANAGER_VARNAME, INTERNAL_HOOKS_VARNAME
 
 
 ####################
 # Class definition #
 ####################
```

### Comparing `prism-ds-0.1.9rc2/prism/infra/project.py` & `prism-ds-0.2.0rc1/prism/infra/project.py`

 * *Files 2% similar despite different names*

```diff
@@ -17,16 +17,16 @@
 import jinja2
 import re
 from pathlib import Path
 from typing import Any, Dict, List, Optional
 
 # Prism-specific importss
 import prism.exceptions
-from prism.logging import fire_console_event
-import prism.logging
+from prism.prism_logging import fire_console_event
+import prism.prism_logging
 from prism.parsers import yml_parser
 from prism.profiles import profile
 from prism.infra.sys_path import SysPathEngine
 
 
 ####################
 # Class definition #
@@ -136,15 +136,15 @@
 
         # If we're creating the project as part of the `connect` task, we don't need to
         # generate the adapters; we only need to grab the profiles directory. If the
         # profile YML path isn't specified, default to the project dir.
         if self.which == "connect":
             if self.profile_yml_path is None:
                 fire_console_event(
-                    prism.logging.ProfileYmlWarningEvent(),
+                    prism.prism_logging.ProfileYmlWarningEvent(),
                     [],
                     0.01,
                     'warn'
                 )
                 self.profile_yml_path = self.project_dir / 'profile.yml'
 
         # If we're running the project using an agent, then we don't need to generate
@@ -159,15 +159,15 @@
         # Otherwise, the user wishes to run the project locally (either via the `run` or
         # `spark-submit` commands). For these, we do need to generate the adapters.
         else:
             # If the profile YML path isn't specified, only raise a warning if the
             # profile name is non-empty.
             if self.profile_name != "" and self.profile_yml_path is None:
                 fire_console_event(
-                    prism.logging.ProfileYmlWarningEvent(),
+                    prism.prism_logging.ProfileYmlWarningEvent(),
                     [],
                     0.01,
                     'warn'
                 )
                 self.profile_yml_path = self.project_dir / 'profile.yml'
 
             # Do all the other profile-related stuff
@@ -326,30 +326,30 @@
         """
         try:
             sys_path_config = run_context[self.filename.replace(".py", "")].SYS_PATH_CONF  # noqa: E501
         except AttributeError:
             sys_path_config = None
         if sys_path_config is None:
             fire_console_event(
-                prism.logging.SysPathConfigWarningEvent(),
+                prism.prism_logging.SysPathConfigWarningEvent(),
                 [],
                 0.01,
                 'warn'
             )
             return [self.project_dir]
         if not isinstance(sys_path_config, list):
             raise prism.exceptions.RuntimeException(
                 message='`SYS_PATH_CONF` must be a list'
             )
 
         # If the project directory is not in the sys.path config, throw a warning and
         # add it.
         if str(self.project_dir) not in [str(s) for s in sys_path_config]:
-            prism.logging.fire_console_event(
-                prism.logging.ProjectDirNotInSysPath(), [], log_level='warn'
+            prism.prism_logging.fire_console_event(
+                prism.prism_logging.ProjectDirNotInSysPath(), [], log_level='warn'
             )
             sys_path_config.insert(0, self.project_dir)
         return [Path(s) for s in sys_path_config]
 
     def get_thread_count(self,
         run_context: Dict[Any, Any]
     ) -> int:
@@ -364,15 +364,15 @@
         """
         try:
             thread_count = run_context[self.filename.replace(".py", "")].THREADS  # noqa: E501
         except AttributeError:
             thread_count = None
         if thread_count is None:
             fire_console_event(
-                prism.logging.ThreadsWarningEvent(),
+                prism.prism_logging.ThreadsWarningEvent(),
                 [],
                 0.01,
                 'warn'
             )
             return 1
         if not isinstance(thread_count, int):
             raise prism.exceptions.InvalidProjectPyException(
```

### Comparing `prism-ds-0.1.9rc2/prism/infra/sys_path.py` & `prism-ds-0.2.0rc1/prism/infra/sys_path.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/infra/task_manager.py` & `prism-ds-0.2.0rc1/prism/infra/task_manager.py`

 * *Files 10% similar despite different names*

```diff
@@ -7,14 +7,15 @@
 """
 
 ###########
 # Imports #
 ###########
 
 # Standard library imports
+import re
 from typing import Any, Dict
 
 
 ####################
 # Class definition #
 ####################
 
@@ -26,8 +27,10 @@
     via `tasks.ref('...')`.
     """
 
     def __init__(self, upstream: Dict[str, Any]):
         self.upstream = upstream
 
     def ref(self, module: str):
+        if len(re.findall(r'\.py$', module)) == 0:
+            module = f'{module}.py'
         return self.upstream[module].get_output()
```

### Comparing `prism-ds-0.1.9rc2/prism/logging.py` & `prism-ds-0.2.0rc1/prism/prism_logging.py`

 * *Files 4% similar despite different names*

```diff
@@ -574,14 +574,22 @@
 class ThreadsWarningEvent(Event):
 
     def message(self):
         return f'{YELLOW}`THREADS` not found in prism_project.py; defaulting to 1{RESET}'  # noqa: E501
 
 
 @dataclass
+class PyWarningEvent(Event):
+    module_name: str
+
+    def message(self):
+        return f'{YELLOW}Found `.py` in a tasks.ref(...) argument in `{self.module_name}`...This will be an error in a future version of Prism.{RESET}'  # noqa: E501
+
+
+@dataclass
 class DelayEvent(Event):
     name: str
     delay_seconds: int
 
     def message(self):
         if self.delay_seconds > 0:
             return f'{YELLOW}{self.name} failed...delaying {self.delay_seconds} before restarting{RESET}'  # noqa: E501
@@ -755,23 +763,23 @@
         sleep: number of seconds to pause after firing the event
         log_level: one of `info`, `warn`, `error`, or `debug`
     returns:
         event_list with `event` appended
     """
     if event is not None:
         if log_level == "info":
-            DEFAULT_LOGGER.info(event.message())  # type: ignore
+            DEFAULT_LOGGER.info(event.message())  # type: ignore # noqa: F821
         elif log_level == "warn":
-            DEFAULT_LOGGER.warning(event.message())  # type: ignore
+            DEFAULT_LOGGER.warning(event.message())  # type: ignore # noqa: F821
         elif log_level == "error":
-            DEFAULT_LOGGER.error(event.message())  # type: ignore
+            DEFAULT_LOGGER.error(event.message())  # type: ignore # noqa: F821
         elif log_level == "debug":
-            DEFAULT_LOGGER.debug(event.message())  # type: ignore
+            DEFAULT_LOGGER.debug(event.message())  # type: ignore # noqa: F821
         elif log_level == "agent":
-            DEFAULT_LOGGER.agent(event.message())  # type: ignore
+            DEFAULT_LOGGER.agent(event.message())  # type: ignore # noqa: F821
 
     # Sleep
     time.sleep(sleep)
 
     # Return event list
     if event is not None:
         event_list.append(event)
@@ -781,10 +789,10 @@
 def fire_empty_line_event(event_list: List[Event] = []):
     """
     Fire empty line event. These events are used to make the console logs look prettier,
     so they'll always be fired under the `info` level.
     """
     e = EmptyLineEvent()
     msg = e.message()
-    DEFAULT_LOGGER.info(msg)  # type: ignore
+    DEFAULT_LOGGER.info(msg)  # type: ignore # noqa: F821
     event_list.append(e)
     return event_list
```

### Comparing `prism-ds-0.1.9rc2/prism/mixins/agent.py` & `prism-ds-0.2.0rc1/prism/mixins/agent.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/mixins/aws.py` & `prism-ds-0.2.0rc1/prism/mixins/aws.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/mixins/base.py` & `prism-ds-0.2.0rc1/prism/mixins/base.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/mixins/compile.py` & `prism-ds-0.2.0rc1/prism/mixins/compile.py`

 * *Files 1% similar despite different names*

```diff
@@ -153,32 +153,32 @@
                         processed_modules.extend(
                             self.get_modules(Path(modules_dir / parent), Path(parent))
                         )
 
                     # Check if path is a directory
                     elif Path(modules_dir / m).is_dir():
                         raise prism.exceptions.CompileException(
-                            message=f'invalid --modules argument `{m}`'
+                            message=f'invalid --module argument `{m}`'
                         )
 
                     # Check if path is a file
                     elif Path(modules_dir / m).is_file():
                         if len(re.findall(r'\.py$', Path(modules_dir / m).name)) == 0:
                             raise prism.exceptions.CompileException(
-                                f'invalid --modules argument `{m}`'
+                                f'invalid --module argument `{m}`'
                             )
                         else:
                             processed_modules.extend([Path(m)])
 
                     else:
                         raise prism.exceptions.CompileException(
-                            f'invalid object `{str(m)}` in `{str(modules_dir)}`'
+                            f'could not find module `{str(m)}` in `{str(modules_dir.name)}/`'  # noqa: E501
                         )
 
-        # If --modules argument not specified, then get all modules
+        # If --module argument not specified, then get all modules
         except AttributeError:
             processed_modules = self.get_modules(modules_dir)
 
         return processed_modules
 
     def get_compiled_dir(self,
         project_dir: Path
```

### Comparing `prism-ds-0.1.9rc2/prism/mixins/connect.py` & `prism-ds-0.2.0rc1/prism/mixins/connect.py`

 * *Files 0% similar despite different names*

```diff
@@ -18,15 +18,15 @@
 from typing import Any, Dict
 
 # Prism-specific imports
 import prism.cli.base
 import prism.cli.compile
 import prism.exceptions
 import prism.constants
-import prism.logging
+import prism.prism_logging
 from prism.templates.profile import PROFILES_TEMPLATE_DIR as profiles_template_dir
 
 
 ####################
 # Class definition #
 ####################
```

### Comparing `prism-ds-0.1.9rc2/prism/mixins/create_agent.py` & `prism-ds-0.2.0rc1/prism/mixins/create_agent.py`

 * *Files 1% similar despite different names*

```diff
@@ -16,15 +16,15 @@
 from pathlib import Path
 
 # Prism-specific imports
 import prism.cli.base
 import prism.cli.compile
 import prism.exceptions
 import prism.constants
-import prism.logging
+import prism.prism_logging
 from prism.templates.agents import AGENTS_TEMPLATE_DIR as agents_template_dir
 
 
 ####################
 # Class definition #
 ####################
```

### Comparing `prism-ds-0.1.9rc2/prism/mixins/create_task.py` & `prism-ds-0.2.0rc1/prism/mixins/create_task.py`

 * *Files 0% similar despite different names*

```diff
@@ -16,15 +16,15 @@
 from typing import Dict
 
 # Prism-specific imports
 import prism.cli.base
 import prism.cli.compile
 import prism.exceptions
 import prism.constants
-import prism.logging
+import prism.prism_logging
 
 # Other imports
 from jinja2 import Template
 import re
 
 
 ####################
```

### Comparing `prism-ds-0.1.9rc2/prism/mixins/create_trigger.py` & `prism-ds-0.2.0rc1/prism/mixins/create_trigger.py`

 * *Files 0% similar despite different names*

```diff
@@ -18,15 +18,15 @@
 from typing import Any, Dict
 
 # Prism-specific imports
 import prism.cli.base
 import prism.cli.compile
 import prism.exceptions
 import prism.constants
-import prism.logging
+import prism.prism_logging
 from prism.templates.triggers import TRIGGERS_TEMPLATE_DIR as triggers_template_dir
 from prism.triggers import PrismTrigger
 
 
 ####################
 # Class definition #
 ####################
```

### Comparing `prism-ds-0.1.9rc2/prism/mixins/graph.py` & `prism-ds-0.2.0rc1/prism/mixins/graph.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/mixins/run.py` & `prism-ds-0.2.0rc1/prism/mixins/run.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/mixins/sys_handler.py` & `prism-ds-0.2.0rc1/prism/mixins/sys_handler.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/parsers/ast_parser.py` & `prism-ds-0.2.0rc1/prism/parsers/ast_parser.py`

 * *Files 2% similar despite different names*

```diff
@@ -17,14 +17,15 @@
 import astor
 from pathlib import Path
 from typing import List, Optional, Tuple, Union
 
 # Prism imports
 import prism.constants
 import prism.exceptions
+import prism.prism_logging
 from prism.infra.manifest import ModuleManifest
 
 
 ####################
 # Class definition #
 ####################
 
@@ -304,20 +305,36 @@
                 try:
                     if c.func.value.id == prism_task_manager_alias and c.func.attr == 'ref':  # type: ignore # noqa: E501
                         args = c.args
                         if len(args) > 1:
                             raise prism.exceptions.ParserException(
                                 'too many arguments in `tasks.ref()` call'
                             )
-                        if Path(args[0].s) not in mod_calls:                 # type: ignore # noqa: E501
-                            if args[0].s == str(self.module_relative_path):  # type: ignore # noqa: E501
+
+                        # Check the argument format. Convert it to a `.py` format.
+                        tmp_path = args[0].s  # type: ignore
+                        if len(re.findall(r'(?i)^[a-z0-9\_\-\/\*]+(?:\.py)?$', tmp_path)) == 0:  # noqa: E501
+                            raise prism.exceptions.ParserException(
+                                f'invalid module name `{tmp_path}`...can only contain letters, numbers, underscores or dashes'  # noqa: E501
+                            )
+                        if len(re.findall(r'\.py$', tmp_path)) > 0:
+                            prism.prism_logging.fire_console_event(
+                                prism.prism_logging.PyWarningEvent(str(self.module_relative_path)),  # noqa: E501
+                                event_list=[],
+                                log_level='warn'
+                            )
+                        if len(re.findall(r'\.py$', tmp_path)) == 0:
+                            tmp_path = f'{tmp_path}.py'
+
+                        if tmp_path not in mod_calls:  # type: ignore # noqa: E501
+                            if tmp_path == str(self.module_relative_path):  # type: ignore # noqa: E501
                                 raise prism.exceptions.ParserException(
                                     message=f'self-references found in `{str(self.module_relative_path)}`'  # noqa: E501
                                 )
-                            mod_calls.append(Path(args[0].s))  # type: ignore
+                            mod_calls.append(Path(tmp_path))  # type: ignore
 
                 # If we encounter an Attribute error, then the call object producing the
                 # error is not of interest to us. Skip.
                 except AttributeError:
                     pass
 
         return mod_calls
```

### Comparing `prism-ds-0.1.9rc2/prism/parsers/base.py` & `prism-ds-0.2.0rc1/prism/parsers/base.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/parsers/yml_parser.py` & `prism-ds-0.2.0rc1/prism/parsers/yml_parser.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/profiles/adapter.py` & `prism-ds-0.2.0rc1/prism/profiles/adapter.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/profiles/bigquery.py` & `prism-ds-0.2.0rc1/prism/profiles/bigquery.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/profiles/dbt.py` & `prism-ds-0.2.0rc1/prism/profiles/dbt.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/profiles/meta.py` & `prism-ds-0.2.0rc1/prism/profiles/meta.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/profiles/postgres.py` & `prism-ds-0.2.0rc1/prism/profiles/postgres.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/profiles/profile.py` & `prism-ds-0.2.0rc1/prism/profiles/profile.py`

 * *Files 2% similar despite different names*

```diff
@@ -15,15 +15,15 @@
 from typing import Any, Dict, Optional
 
 # Prism-specific imports
 from .meta import MetaAdapter
 from .adapter import Adapter
 import prism.exceptions
 import prism.constants
-import prism.logging
+import prism.prism_logging
 from prism.profiles import meta, adapter  # noqa: F401
 
 
 ####################
 # Class definition #
 ####################
 
@@ -154,36 +154,36 @@
         flag_missing_profile_yml = profile_yml == {}
         flag_missing_profile_name = profile_name == "" or profile_name is None
         flag_missing_named_profile = named_profile == {}
 
         if flag_missing_profile_yml:
             if not flag_missing_profile_name:
                 if fire_warnings:
-                    e2 = prism.logging.ProfileNameExistsYamlDoesNotExist()
-                    prism.logging.fire_console_event(e2, [], 0, log_level='warn')
+                    e2 = prism.prism_logging.ProfileNameExistsYamlDoesNotExist()
+                    prism.prism_logging.fire_console_event(e2, [], 0, log_level='warn')
             return False
 
         # Handle cases where the profile YML is non-empty
         else:
 
             # If missing profile name, then the named profile will, by definition, be
             # {}. Throw a warning and return False
             if flag_missing_profile_name:
                 if fire_warnings:
-                    e1 = prism.logging.ProfileNameDoesNotExistYamlExists()
-                    prism.logging.fire_console_event(e1, [], 0, log_level='warn')
+                    e1 = prism.prism_logging.ProfileNameDoesNotExistYamlExists()
+                    prism.prism_logging.fire_console_event(e1, [], 0, log_level='warn')
                 return False
 
             # If the profile name is not missing, check if the named profile is empty.
             # If it is, then raise a warning and return False.
             else:
                 if flag_missing_named_profile:
                     if fire_warnings:
-                        e3 = prism.logging.ProfileNameExistsNamedProfileDoesNotExist()
-                        prism.logging.fire_console_event(e3, [], 0, log_level='warn')
+                        e3 = prism.prism_logging.ProfileNameExistsNamedProfileDoesNotExist()  # noqa: E501
+                        prism.prism_logging.fire_console_event(e3, [], 0, log_level='warn')  # noqa: E501
                     return False
 
         # Nothing has been returned, return True
         return True
 
     def get_adapter_types(self):
         """
```

### Comparing `prism-ds-0.1.9rc2/prism/profiles/pyspark.py` & `prism-ds-0.2.0rc1/prism/profiles/pyspark.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/profiles/redshift.py` & `prism-ds-0.2.0rc1/prism/profiles/redshift.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/profiles/snowflake.py` & `prism-ds-0.2.0rc1/prism/profiles/snowflake.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/profiles/trino.py` & `prism-ds-0.2.0rc1/prism/profiles/trino.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/spark/wrapper.py` & `prism-ds-0.2.0rc1/prism/spark/wrapper.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/target.py` & `prism-ds-0.2.0rc1/prism/target.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/task.py` & `prism-ds-0.2.0rc1/prism/task.py`

 * *Files 2% similar despite different names*

```diff
@@ -12,15 +12,15 @@
 
 # Standard library imports
 from pathlib import Path
 from typing import Any, Callable, List, Optional, Union
 
 # Prism imports
 import prism.exceptions
-import prism.logging
+import prism.prism_logging
 import prism.infra.hooks
 import prism.infra.task_manager
 import prism.target
 
 
 ####################
 # Class definition #
@@ -92,15 +92,17 @@
         their own tasks.
         """
         if self.func is not None:
             return self.func(tasks, hooks)
         else:
             raise prism.exceptions.RuntimeException("`run` method not implemented")
 
-    @prism.logging.deprecated('prism.task.PrismTask.target', 'prism.decorators.target')
+    @prism.prism_logging.deprecated(
+        'prism.task.PrismTask.target', 'prism.decorators.target'
+    )
     def target(type, loc, **kwargs):
         """
         Decorator to use if task requires user to iterate through several different
         objects and save each object to an external location
         """
 
         def decorator_target(func):
```

### Comparing `prism-ds-0.1.9rc2/prism/templates/minimal_project/modules/class_task.py` & `prism-ds-0.2.0rc1/prism/templates/minimal_project/modules/class_task.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/templates/minimal_project/modules/decorated_task.py` & `prism-ds-0.2.0rc1/prism/templates/minimal_project/modules/decorated_task.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/templates/minimal_project/prism_project.py` & `prism-ds-0.2.0rc1/prism/templates/minimal_project/prism_project.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/templates/starter_project/dev/dev.ipynb` & `prism-ds-0.2.0rc1/prism/templates/starter_project/dev/dev.ipynb`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/templates/starter_project/modules/class_task.py` & `prism-ds-0.2.0rc1/prism/templates/starter_project/modules/class_task.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/templates/starter_project/modules/decorated_task.py` & `prism-ds-0.2.0rc1/prism/templates/starter_project/modules/decorated_task.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/templates/starter_project/prism_project.py` & `prism-ds-0.2.0rc1/prism/templates/starter_project/prism_project.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/integration_test_class.py` & `prism-ds-0.2.0rc1/prism/tests/integration/integration_test_class.py`

 * *Files 4% similar despite different names*

```diff
@@ -9,14 +9,15 @@
 """
 
 ###########
 # Imports #
 ###########
 
 # Standard library imports
+from prism.main import invoke
 import io
 import boto3
 import ast
 import astor
 import os
 from pathlib import Path
 import unittest
@@ -24,133 +25,128 @@
 import yaml
 import pandas as pd
 import json
 from typing import Any, Dict, List
 
 # Prism imports
 import prism.cli.base
-from prism.main import main
-import prism.logging
-from prism.constants import ROOT_DIR
+# from prism.main import main
+import prism.prism_logging
 
 # Ignore ResourceWarnings introduced by boto3
 import warnings
 
 #################################
 # Test case directory and paths #
 #################################
 
 # Directory containing all prism_project.py test cases
 TEST_CASE_WKDIR = os.path.dirname(__file__)
 TEST_PROJECTS = Path(TEST_CASE_WKDIR) / 'test_projects'
 
 
-################################
-## Test case class definition ##
-################################
+##############################
+# Test case class definition #
+##############################
 
 class IntegrationTestCase(unittest.TestCase):
 
-
     def _set_up_wkdir(self):
         # Remove logs.log from project
         if Path(Path.cwd() / 'logs.log').is_file():
             os.unlink(Path.cwd() / 'logs.log')
-        
+
         os.chdir(TEST_PROJECTS)
-        
 
     def _is_valid_project(self, path):
         """
-        Determine if `path` is a valid project (i.e., that is has a `prism_project.py` file and a `modules` folder)
+        Determine if `path` is a valid project (i.e., that is has a `prism_project.py`
+        file and a `modules` folder)
 
         args:
             path: project path
         returns:
             boolean indicating whether `path` is a valid project
         """
         os.chdir(path)
         project_dir = prism.cli.base.get_project_dir()
-        self.assertTrue(project_dir==path)
+        self.assertTrue(project_dir == path)
         self.assertTrue(Path(project_dir / 'modules').is_dir())
-    
 
     def _load_manifest(self, path: Path) -> dict:
         """
         Load manifest
         """
         with open(path, 'r') as f:
             manifest = json.load(f)
         f.close()
         return manifest
 
-    
-    def _load_module_refs(self, module_name: str, manifest: Dict[str, Any]) -> List[str]:
+    def _load_module_refs(
+        self,
+        module_name: str,
+        manifest: Dict[str, Any]
+    ) -> List[str]:
         """
         Load refs associated with module
         """
         module_refs = []
         all_refs = manifest["refs"]
         for ref_obj in all_refs:
-            if ref_obj["target"]==module_name:
+            if ref_obj["target"] == module_name:
                 module_refs.append(ref_obj["source"])
-        if len(module_refs)==1:
+        if len(module_refs) == 1:
             return module_refs[0]
         else:
             return module_refs
 
-
     def _run_prism(self, args: list):
         """
         Run prism using `args`
         """
-        return main(args, bool_return=True)
+        return invoke(args, bool_return=True)
 
-        
     def _ignore_warnings(test_func):
         """
-        Decorator to ignore ResourceWarnings during unittest functions. These arise due to some weird behavior by boto3.
+        Decorator to ignore ResourceWarnings during unittest functions. These arise due
+        to some weird behavior by boto3.
         """
         def do_test(self, *args, **kwargs):
             with warnings.catch_warnings():
                 warnings.simplefilter("ignore", ResourceWarning)
                 return test_func(self, *args, **kwargs)
         return do_test
 
-
     def _get_profile_name(self, wkdir):
         """
         Get the profile name from the profile YML file at `wkdir`
         """
         with open(Path(wkdir / 'profile.yml')) as f:
             yml_dict = yaml.safe_load(f)
         f.close()
         return list(yml_dict.keys())[0]
 
-    
     def _delete_obj_from_s3(self, profile, bucket, path):
         """
         Delete an object from S3
 
         args:
             profile: name of profile for boto3 client
             bucket: bucket containing parquet file
             path: path to parquet file
         returns:
             None
         """
         session = boto3.session.Session(profile_name=profile)
         client = session.client('s3')
-        s3 = session.resource('s3')
         objects_dict = client.list_objects_v2(Bucket=bucket, Prefix=path)
         s3_keys = [item['Key'] for item in objects_dict['Contents']]
         for key in s3_keys:
             client.delete_object(Bucket=bucket, Key=key)
 
-
     def _download_s3_file(self, s3, bucket, key):
         """
         Download parquet file from S3
 
         args:
             s3: boto3 S3 resource
             bucket: name of bucket containing parquet file
@@ -158,88 +154,83 @@
         returns:
             S3 object buffer for parquet file at `bucket` and `key`
         """
         buffer = io.BytesIO()
         s3.Object(bucket, key).download_fileobj(buffer)
         return buffer
 
-    
     def _get_csv_file_in_s3_as_pd(self, profile, bucket, path, **kwargs):
         """
         Get parquet file in an S3 bucket as a pandas DataFrame
 
         args:
             profile: name of profile for boto3 client
             bucket: bucket containing parquet file
             path: path to parquet file
         returns:
             parquet file at `bucket`/`path` as a Pandas DataFrame
         """
         session = boto3.session.Session(profile_name=profile)
         client = session.client('s3')
-        s3 = session.resource('s3')
         response = client.get_object(Bucket=bucket, Key=path)
         return pd.read_csv(response.get("Body"), **kwargs)
 
-
     def _remove_compiled_dir(self, wkdir):
         """
         Remove the .compiled directory, if it exists
         """
         if Path(wkdir / '.compiled').is_dir():
             shutil.rmtree(Path(wkdir / '.compiled'))
-    
 
     def _remove_files_in_output(self, wkdir):
         """
         Remove file outputs from `output` folder of project
         """
         for file in Path(wkdir / 'output').iterdir():
-            if Path(wkdir / 'output' / file).is_file() and file.name!=".exists":
+            if Path(wkdir / 'output' / file).is_file() and file.name != ".exists":
                 os.unlink(file)
-    
 
     def _remove_dirs_in_output(self, wkdir):
         """
         Remove directory outputs from `output` folder of project
         """
         for file in Path(wkdir / 'output').iterdir():
             if Path(wkdir / 'output' / file).is_dir():
                 shutil.rmtree(Path(wkdir / 'output' / file))
 
     def _remove_parquet_files_in_dir(self, dir):
         """
         Remove parquet files in directory
         """
         for filename in Path(dir).iterdir():
-            if str(filename).split('.')[-1]=="parquet":
+            if str(filename).split('.')[-1] == "parquet":
                 os.unlink(filename)
-            elif str(filename).split('.')[-1]=="crc" and str(filename).split('.')[-2]=="parquet":
+            elif (
+                str(filename).split('.')[-1] == "crc"
+                and str(filename).split('.')[-2] == "parquet"  # noqa: W503
+            ):
                 os.unlink(filename)
 
-
     def _file_as_str(self, path):
         """
         Open file as string
         """
         with open(path, 'r') as f:
             compiled_module_str = f.read()
         f.close()
         return compiled_module_str
 
-
     def _compiled_module_if_name_main(self, path):
         """
         Get `if __name__ == "__main__"` body from `path
         """
         compiled_module_str = self._file_as_str(path)
         if_name_main_body = self._get_if_name_main_body(compiled_module_str)
         return if_name_main_body
 
-    
     def _get_if_name_main_body(self, module_str: str) -> str:
         """
         Get the body of `if __name__ == "__main__"` and return it as a string
 
         args:
             module_str: module with `if __name__ == "__main__"` as a string
         returns:
@@ -247,27 +238,22 @@
         """
         module_ast_tree = ast.parse(module_str)
         self.assertTrue(isinstance(module_ast_tree, ast.Module))
         if_name_main_block = module_ast_tree.body[-1]
         self.assertTrue(isinstance(if_name_main_block, ast.If))
         return astor.to_source(if_name_main_block)
 
-    
     def _remove_profile_yml(self, wkdir):
         """
         Remove the profile YML file, if it exists
         """
         if Path(wkdir / 'profile.yml').is_file():
             os.unlink(Path(wkdir / 'profile.yml'))
-    
 
     def _profile_yml_as_dict(self, wkdir):
         """
         Open the profile YML file as a dict
         """
         with open(Path(wkdir / 'profile.yml'), 'r') as f:
             yml_dict = yaml.safe_load(f)
         f.close()
         return yml_dict
-
-
-# EOF
```

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_client.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_client.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_compile.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_compile.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_connect.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_connect.py`

 * *Files 6% similar despite different names*

```diff
@@ -11,16 +11,18 @@
 ###########
 # Imports #
 ###########
 
 # Standard library imports
 import os
 from pathlib import Path
+import click.exceptions
 
 # Prism imports
+import prism.constants
 import prism.tests.integration.integration_test_class as integration_test_class
 
 
 #################################
 # Test case directory and paths #
 #################################
 
@@ -282,29 +284,29 @@
         os.chdir(wkdir)
 
         # Remove the .compiled directory, if it exists
         self._remove_profile_yml(wkdir)
 
         # Execute command with a non-null, invalid type
         args = ['connect', '--type', 'dummy']
-        connect_run = self._run_prism(args)
-        connect_run_results = connect_run.get_results()
-        self.assertEqual(
-            ' | '.join(connect_task_invalid_expected_events),
-            connect_run_results
-        )
+        with self.assertRaises(click.exceptions.ClickException) as cm:
+            self._run_prism(args)
+        expected_msg = "'dummy' is not one of " + ", ".join([
+            "'" + t + "'" for t in prism.constants.VALID_ADAPTERS
+        ])
+        self.assertTrue(expected_msg, str(cm.exception))
 
         # Execute command with a Null
         args = ['connect', '--type', '']
-        connect_run = self._run_prism(args)
-        connect_run_results = connect_run.get_results()
-        self.assertEqual(
-            ' | '.join(connect_task_invalid_expected_events),
-            connect_run_results
-        )
+        with self.assertRaises(click.exceptions.ClickException) as cm:
+            self._run_prism(args)
+        expected_msg = "'' is not one of " + ", ".join([
+            "'" + t + "'" for t in prism.constants.VALID_ADAPTERS
+        ])
+        self.assertTrue(expected_msg, str(cm.exception))
 
         # Set up wkdir for next test case
         self._set_up_wkdir()
 
     def test_no_prism_project_py(self):
         """
         `prism connect` when there is no prism_project.py file
```

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_create.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_create.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_dbt.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_dbt.py`

 * *Files 4% similar despite different names*

```diff
@@ -18,15 +18,15 @@
 import os
 from pathlib import Path
 import pandas as pd
 import shutil
 
 # Prism imports
 import prism.cli.base
-import prism.logging
+import prism.prism_logging
 import prism.tests.integration.integration_test_class as integration_test_class
 
 
 #################################
 # Test case directory and paths #
 #################################
 
@@ -56,15 +56,15 @@
         self._remove_compiled_dir(wkdir)
 
         # Remove all folders / files in the output directory
         self._remove_dirs_in_output(wkdir)
         self._remove_files_in_output(wkdir)
 
         # Execute command.
-        args = ['run', '--modules', 'filter_customers.py']
+        args = ['run', '--module', 'filter_customers.py']
         run_results = self._run_prism(args)
         self.assertTrue(Path(wkdir / '.compiled').is_dir())
         self.assertTrue(Path(wkdir / '.compiled' / 'manifest.json').is_file())
         
         # Check contents of output
         df = pd.read_csv(wkdir / 'output' / 'jaffle_shop_customers.csv')
         expected_columns = [
@@ -106,23 +106,23 @@
 
         # Remove all folders / files in the output directory
         self._remove_dirs_in_output(wkdir)
         self._remove_files_in_output(wkdir)
         self.assertFalse(Path(wkdir / 'output' / 'bad_adapter.csv').is_file())
 
         # Execute command.
-        args = ['run', '--modules', 'bad_adapter.py']
+        args = ['run', '--module', 'bad_adapter.py']
         run_results = self._run_prism(args)
 
         # Nothing should be produced
         self.assertFalse(Path(wkdir / 'output' / 'bad_adapter.csv').is_file())
 
         # Last event in run_results (before separator event) should be an error event
         error_event = run_results.event_list[-2]
-        self.assertTrue(isinstance(error_event, prism.logging.PrismExceptionErrorEvent))
+        self.assertTrue(isinstance(error_event, prism.prism_logging.PrismExceptionErrorEvent))
         self.assertEqual('adapter `dbt_prsdfofile` not defined', error_event.err.message)
 
         # Remove the 'target' -- it contains dbt artifacts
         if Path(wkdir / 'target').is_dir():
             shutil.rmtree(Path(wkdir / 'target'))
 
         # Remove compiled folder
```

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_hooks.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_hooks.py`

 * *Files 1% similar despite different names*

```diff
@@ -49,15 +49,15 @@
         if Path(wkdir / '.compiled').is_dir():
             shutil.rmtree(Path(wkdir / '.compiled'))
         self.maxDiff = None
 
         # ------------------------------------------------------------------------------
         # Run snowflake.py and spark.py
 
-        args = ['spark-submit', '--modules', 'snowflake.py', 'spark.py']
+        args = ['spark-submit', '--module', 'snowflake.py', '--module', 'spark.py']
         self._run_prism(args)
 
         # Get module 1 and 2 outputs
         machinery_sample = pd.read_csv(wkdir / 'output' / 'machinery_sample.csv')
         household_sample = pd.read_csv(wkdir / 'output' / 'household_sample.csv')
         machinery_sample_filtered = pd.read_csv(
             wkdir / 'output' / 'machinery_sample_filtered.csv'
@@ -112,15 +112,15 @@
         if Path(wkdir / '.compiled').is_dir():
             shutil.rmtree(Path(wkdir / '.compiled'))
         self.maxDiff = None
 
         # ------------------------------------------------------------------------------
         # Run bad_adapter.py
 
-        args = ['spark-submit', '--modules', 'bad_adapter.py']
+        args = ['spark-submit', '--module', 'bad_adapter.py']
         _ = self._run_prism(args)
 
         # We can't check the error events directly; for now, let's just check that the
         # output wasn't created.
         self.assertFalse(Path(wkdir / 'output' / 'bad_adapter.csv').is_file())
 
         # Remove the .compiled directory, if it exists
@@ -147,15 +147,15 @@
         self.maxDiff = None
 
         # Check that expected output doesn't already exist
         expected_output = Path(wkdir) / 'output' / 'sample_postgres_data.csv'
         self.assertFalse(expected_output.is_file())
 
         # Run project
-        args = ['spark-submit', '--modules', 'postgres.py']
+        args = ['spark-submit', '--module', 'postgres.py']
         self._run_prism(args)
 
         # Check output
         self.assertTrue(expected_output.is_file())
         df = pd.read_csv(expected_output)
         self.assertEqual(df.shape[0], 1)
         self.assertEqual(df.test_col[0], 1)
```

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_init.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_init.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/001_init/modules/module01.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/001_init/modules/class_task.py`

 * *Files 12% similar despite different names*

```diff
@@ -15,15 +15,15 @@
 import prism_project
 
 
 ###################
 # Task definition #
 ###################
 
-class Module01(prism.task.PrismTask):
+class ExampleTask(prism.task.PrismTask):
 
     # Run
     @prism.decorators.target(type=prism.target.Txt, loc=prism_project.OUTPUT / 'hello_world.txt')
     def run(self, tasks, hooks):
         """
         Execute task.
```

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/001_init/prism_project.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/001_init/prism_project.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/001a_init_minimal/modules/module01.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/001a_init_minimal/modules/class_task.py`

 * *Files 12% similar despite different names*

```diff
@@ -15,15 +15,15 @@
 import prism_project
 
 
 ###################
 # Task definition #
 ###################
 
-class Module01(prism.task.PrismTask):
+class ExampleTask(prism.task.PrismTask):
 
     # Run
     @prism.decorators.target(type=prism.target.Txt, loc=prism_project.OUTPUT / 'hello_world.txt')
     def run(self, tasks, hooks):
         """
         Execute task.
```

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/001a_init_minimal/prism_project.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/001a_init_minimal/prism_project.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/002_no_project_py/functions.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/002_no_project_py/functions.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/002_no_project_py/modules/module01.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/002_no_project_py/modules/module01.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/002_no_project_py/modules/module02.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/002_no_project_py/modules/module02.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/002_no_project_py/modules/module03.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/002_no_project_py/modules/module03.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/003_project_with_cycle/modules/module01.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/003_project_with_cycle/modules/module01.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/003_project_with_cycle/modules/module02.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/003_project_with_cycle/modules/module02.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/003_project_with_cycle/modules/module03.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/003_project_with_cycle/modules/module03.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/003_project_with_cycle/prism_project.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/003_project_with_cycle/prism_project.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/004_simple_project/modules/module01.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/004_simple_project/modules/module01.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/004_simple_project/modules/module02.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/004_simple_project/modules/module02.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/004_simple_project/modules/module03.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/004_simple_project/modules/module03.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/004_simple_project/prism_project.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/004_simple_project/prism_project.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/005_simple_project_no_null/functions.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/005_simple_project_no_null/functions.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/005_simple_project_no_null/modules/module01.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/005_simple_project_no_null/modules/module01.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/005_simple_project_no_null/modules/module02.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/005_simple_project_no_null/modules/module02.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/005_simple_project_no_null/modules/module03.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/005_simple_project_no_null/modules/module03.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/005_simple_project_no_null/modules/module04.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/005_simple_project_no_null/modules/module04.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/005_simple_project_no_null/prism_project.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/005_simple_project_no_null/prism_project.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/006_simple_project_with_profile/modules/module01.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/006_simple_project_with_profile/modules/module01.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/006_simple_project_with_profile/modules/module02.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/006_simple_project_with_profile/modules/module02.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/006_simple_project_with_profile/modules/module03.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/006_simple_project_with_profile/modules/module03.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/006_simple_project_with_profile/modules/module04.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/006_simple_project_with_profile/modules/module04.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/006_simple_project_with_profile/prism_project.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/006_simple_project_with_profile/prism_project.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/007_spark_project/modules/module01.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/007_spark_project/modules/module01.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/007_spark_project/modules/module02.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/007_spark_project/modules/module02.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/007_spark_project/modules/module03.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/007_spark_project/modules/module03.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/007_spark_project/modules/module04.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/007_spark_project/modules/module04.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/007_spark_project/prism_project.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/007_spark_project/prism_project.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/008_targets/modules/csv.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/008_targets/modules/csv.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/008_targets/modules/csv_iter.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/008_targets/modules/csv_iter.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/008_targets/modules/csv_mult.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/008_targets/modules/csv_mult.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/008_targets/modules/parquet.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/008_targets/modules/parquet.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/008_targets/prism_project.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/008_targets/prism_project.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/009_simple_dbt_project/prism/modules/bad_adapter.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/009_simple_dbt_project/prism/modules/bad_adapter.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/009_simple_dbt_project/prism/modules/filter_customers.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/009_simple_dbt_project/prism/modules/filter_customers.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/009_simple_dbt_project/prism/prism_project.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/009_simple_dbt_project/prism/prism_project.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/010_project_nested_module_dirs/modules/extract/module01.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/010_project_nested_module_dirs/modules/extract/module01.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/010_project_nested_module_dirs/modules/extract/module02.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/010_project_nested_module_dirs/modules/extract/module02.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/010_project_nested_module_dirs/modules/load/module03.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/010_project_nested_module_dirs/modules/load/module03.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/010_project_nested_module_dirs/modules/module04.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/010_project_nested_module_dirs/modules/module04.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/010_project_nested_module_dirs/prism_project.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/010_project_nested_module_dirs/prism_project.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/011_bad_task_ref/modules/extract/module01.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/011_bad_task_ref/modules/extract/module01.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/011_bad_task_ref/modules/extract/module02.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/011_bad_task_ref/modules/extract/module02.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/011_bad_task_ref/modules/load/module03.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/011_bad_task_ref/modules/load/module03.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/011_bad_task_ref/modules/module04.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/011_bad_task_ref/modules/module04.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/011_bad_task_ref/prism_project.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/011_bad_task_ref/prism_project.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/012_concurrency/modules/module01.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/012_concurrency/modules/module01.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/012_concurrency/modules/module02.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/012_concurrency/modules/module02.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/012_concurrency/modules/module03.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/012_concurrency/modules/module03.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/012_concurrency/modules/module04.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/012_concurrency/modules/module04.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/012_concurrency/prism_project.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/012_concurrency/prism_project.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/013_hooks_sql_spark/modules/bad_adapter.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/013_hooks_sql_spark/modules/bad_adapter.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/013_hooks_sql_spark/modules/postgres.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/013_hooks_sql_spark/modules/postgres.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/013_hooks_sql_spark/modules/snowflake.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/013_hooks_sql_spark/modules/snowflake.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/013_hooks_sql_spark/modules/spark.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/013_hooks_sql_spark/modules/spark.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/013_hooks_sql_spark/prism_project.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/013_hooks_sql_spark/prism_project.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/014_test_triggers_normal/prism_project.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/014_test_triggers_normal/prism_project.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/015_test_triggers_no_dir/prism_project.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/015_test_triggers_no_dir/prism_project.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/016_test_triggers_error/modules/module01.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/016_test_triggers_error/modules/module01.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/016_test_triggers_error/prism_project.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/016_test_triggers_error/prism_project.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/017_test_triggers_extra_key/modules/module01.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/017_test_triggers_extra_key/modules/module01.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/017_test_triggers_extra_key/prism_project.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/017_test_triggers_extra_key/prism_project.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/018_test_triggers_no_include/modules/module01.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/018_test_triggers_no_include/modules/module01.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/018_test_triggers_no_include/prism_project.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/018_test_triggers_no_include/prism_project.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/019_dec_targets/modules/extract.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/019_dec_targets/modules/extract.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/019_dec_targets/modules/load.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/019_dec_targets/modules/load.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/019_dec_targets/prism_project.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/019_dec_targets/prism_project.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/020_dec_retries/modules/load.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/020_dec_retries/modules/load.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_projects/020_dec_retries/prism_project.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_projects/020_dec_retries/prism_project.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_run.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_run.py`

 * *Files 6% similar despite different names*

```diff
@@ -9,14 +9,15 @@
 """
 
 ###########
 # Imports #
 ###########
 
 # Standard library imports
+import pytest
 import json
 import pandas as pd
 import os
 from pathlib import Path
 import shutil
 from typing import Dict, List
 
@@ -209,15 +210,15 @@
 
         # ***************** #
         # Run only module 1 #
         # ***************** #
 
         # Expecatation: module 1 is the first module in the DAG. Therefore, we should
         # not encounter any errors with this command.
-        args = ['run', '--modules', 'module01.py']
+        args = ['run', '--module', 'module01.py']
         runtask_run = self._run_prism(args)
         runtask_run_results = runtask_run.get_results()
         expected_events = run_success_starting_events + \
             ['TasksHeaderEvent'] + \
             _execution_events_modules({'module01.py': 'DONE'}) + \
             _run_task_end_events('TaskSuccessfulEndEvent')
         self.assertEqual(' | '.join(expected_events), runtask_run_results)
@@ -247,15 +248,15 @@
 
         # Expecatation: module 2 depends on module 1. However, since we just ran module
         # 1, and the output of module 1 is stored in a target, we do not need to re-run
         # module 1 in order to run module 2. Therefore, we should not encounter any
         # errors with this command.
 
         # Execute command
-        args = ['run', '--modules', 'module02.py', '--full-tb']
+        args = ['run', '--module', 'module02.py', '--full-tb']
         runtask_run = self._run_prism(args)
         runtask_run_results = runtask_run.get_results()
         expected_events = run_success_starting_events + \
             ['TasksHeaderEvent'] + \
             _execution_events_modules({'module02.py': 'DONE'}) + \
             _run_task_end_events('TaskSuccessfulEndEvent')
         self.assertEqual(' | '.join(expected_events), runtask_run_results)
@@ -275,28 +276,28 @@
 
         # Expectation: module 4 depends on module 3. However, the output of module 3 is
         # not stored in a target. Therefore, running module 4 without including
         # 'all-upstream' should cause an error.
 
         # -------------------------------------
         # Execute command without `all-upstream`
-        args = ['run', '--modules', 'module04.py']
+        args = ['run', '--module', 'module04.py']
         runtask_run = self._run_prism(args)
         runtask_run_results = runtask_run.get_results()
         expected_events = run_success_starting_events + \
             ['TasksHeaderEvent'] + \
             _execution_events_modules({'module04.py': 'ERROR'}) + \
             _run_task_end_events('PrismExceptionErrorEvent')
         self.assertEqual(' | '.join(expected_events), runtask_run_results)
 
         # -----------------------------------
         # Execute command with `all-upstream`
         self._remove_compiled_dir(wkdir)
         self._remove_files_in_output(wkdir)
-        args = ['run', '--modules', 'module04.py', '--all-upstream']
+        args = ['run', '--module', 'module04.py', '--all-upstream']
         runtask_run = self._run_prism(args)
         runtask_run_results = runtask_run.get_results()
         self.assertEqual(
             ' | '.join(simple_project_no_null_all_modules_expected_events),
             runtask_run_results
         )
 
@@ -350,15 +351,15 @@
                 module02_txt
             )
 
         # ****************************************************** #
         # Execute all modules in extract folder using '*' syntax #
         # ****************************************************** #
 
-        args = ['run', '--modules', 'extract/*']
+        args = ['run', '--module', 'extract/*']
         run = self._run_prism(args)
         run_results = run.get_results()
         expected_events = run_success_starting_events + \
             ['TasksHeaderEvent'] + \
             _execution_events_modules(
                 {
                     'extract/module01.py': 'DONE',
@@ -387,17 +388,19 @@
 
         # ***************************************************************** #
         # Execute all modules in extract /load folder using explicit syntax #
         # ***************************************************************** #
 
         args = [
             'run',
-            '--modules',
+            '--module',
             'extract/module01.py',
+            '--module',
             'extract/module02.py',
+            '--module',
             'load/module03.py'
         ]
         run = self._run_prism(args)
         run_results = run.get_results()
         expected_events = run_success_starting_events + \
             ['TasksHeaderEvent'] + \
             _execution_events_modules(
@@ -540,15 +543,15 @@
 
         # Remove files in output folder
         self._remove_files_in_output(wkdir)
 
         # New output path
         output_path = str(wkdir.parent)
         self.assertFalse((Path(output_path) / 'module01.txt').is_file())
-        args = ['run', '--modules', 'module01.py', '--vars', f'OUTPUT={output_path}']
+        args = ['run', '--module', 'module01.py', '--vars', f'OUTPUT={output_path}']
         self._run_prism(args)
 
         # Get output
         self.assertTrue((Path(output_path) / 'module01.txt').is_file())
         module01_txt = self._file_as_str(Path(output_path) / 'module01.txt')
         self.assertEqual('Hello from module 1!', module01_txt)
         os.unlink(Path(output_path) / 'module01.txt')
@@ -575,15 +578,15 @@
         # Remove the .compiled directory, if it exists
         self._remove_compiled_dir(wkdir)
 
         # Remove all files in the output directory
         self._remove_files_in_output(wkdir)
 
         # Run all modules downstream of module01.py
-        args = ['run', '--modules', 'module01.py', '--all-downstream']
+        args = ['run', '--module', 'module01.py', '--all-downstream']
         run = self._run_prism(args)
         run_results = run.get_results()
         expected_events = run_success_starting_events + \
             ['TasksHeaderEvent'] + \
             _execution_events_modules(
                 {
                     'module01.py': 'DONE',
@@ -666,15 +669,15 @@
         # Remove the .compiled directory, if it exists
         self._remove_compiled_dir(wkdir)
 
         # Remove all files in the output directory
         self._remove_files_in_output(wkdir)
 
         # Run all modules downstream of module01.py
-        args = ['run', '--modules', 'module01.py']
+        args = ['run', '--module', 'module01.py']
         run = self._run_prism(args)
         run_results = run.get_results()
         expected_events = self._check_trigger_events(
             {'module01.py': 'DONE'}
         ) + _run_task_end_events('TaskSuccessfulEndEvent')
         self.assertEqual(' | '.join(expected_events), run_results)
 
@@ -699,15 +702,15 @@
         # Remove the .compiled directory, if it exists
         self._remove_compiled_dir(wkdir)
 
         # Remove all files in the output directory
         self._remove_files_in_output(wkdir)
 
         # Run all modules downstream of module01.py
-        args = ['run', '--modules', 'module02.py']
+        args = ['run', '--module', 'module02.py']
         run = self._run_prism(args)
         run_results = run.get_results()
         expected_events = self._check_trigger_events(
             {'module02.py': 'ERROR'},
             ["ExecutionErrorEvent", "TriggersHeaderEvent"]
         ) + ["SeparatorEvent"]
         self.assertEqual(' | '.join(expected_events), run_results)
@@ -733,15 +736,15 @@
         # Remove the .compiled directory, if it exists
         self._remove_compiled_dir(wkdir)
 
         # Remove all files in the output directory
         self._remove_files_in_output(wkdir)
 
         # Run all modules downstream of module01.py
-        args = ['run', '--modules', 'module01.py']
+        args = ['run', '--module', 'module01.py']
         run = self._run_prism(args)
         run_results = run.get_results()
         expected_events = self._check_trigger_events(
             {'module01.py': 'DONE'},
             ["TriggersHeaderEvent", "TriggersPathNotDefined"]
         ) + _run_task_end_events('TaskSuccessfulEndEvent')
         self.assertEqual(' | '.join(expected_events), run_results)
@@ -896,24 +899,24 @@
         # Dummy second target text file
         with open(Path(wkdir / 'output' / 'second_target.txt'), 'r') as f:
             second_target = f.read()
         self.assertEqual(second_target, "second target")
 
         # Check output of 'load' task
         names = [
-            "Andrey Fedyaev",
-            "Deng Qingming",
+            "Sergey Prokopyev",
             "Dmitry Petelin",
-            "Fei Junlong",
             "Frank Rubio",
-            "Sergey Prokopyev",
             "Stephen Bowen",
-            "Sultan Alneyadi",
             "Warren Hoburg",
-            "Zhang Lu",
+            "Sultan Alneyadi",
+            "Andrey Fedyaev",
+            "Jing Haiping",
+            "Gui Haichow",
+            "Zhu Yangzhu",
         ]
         for n in names:
             formatted_name = n.lower().replace(" ", "_")
             self.assertTrue(Path(wkdir / 'output' / f'{formatted_name}.txt').is_file())
             with open(Path(wkdir / 'output' / f'{formatted_name}.txt'), 'r') as f:
                 contents = f.read()
             self.assertEqual(contents, n)
@@ -992,7 +995,88 @@
             self.assertFalse(Path(wkdir / 'output' / f'{formatted_name}.txt').is_file())
 
         # Remove the .compiled directory, if it exists
         self._remove_compiled_dir(wkdir)
 
         # Set up the working directory
         self._set_up_wkdir()
+
+    def test_simple_project_no_py_in_ref(self):
+        """
+        `prism run` on simple project where `.py` is excluded from the task.ref(...)
+        calls
+        """
+        self.maxDiff = None
+
+        # Set working directory
+        wkdir = Path(TEST_PROJECTS) / '021_no_py_in_ref'
+        os.chdir(wkdir)
+
+        # Remove the .compiled directory, if it exists
+        self._remove_compiled_dir(wkdir)
+
+        # Remove all files in the output directory
+        self._remove_files_in_output(wkdir)
+
+        # Execute command. Remove the `.py` from the command as well.
+        args = [
+            'run',
+            '--module', 'module01',
+            '--module', 'module02',
+            '--module', 'module03',
+            '--module', 'module04',
+        ]
+        runtask_run = self._run_prism(args)
+        runtask_run_results = runtask_run.get_results()
+        self.assertEqual(
+            ' | '.join(simple_project_no_null_all_modules_expected_events),
+            runtask_run_results
+        )
+        self.assertTrue(Path(wkdir / 'output' / 'module01.txt').is_file())
+        self.assertTrue(Path(wkdir / 'output' / 'module02.txt').is_file())
+
+        # Check contents
+        module01_txt = self._file_as_str(Path(wkdir / 'output' / 'module01.txt'))
+        module02_txt = self._file_as_str(Path(wkdir / 'output' / 'module02.txt'))
+        self.assertEqual('Hello from module 1!', module01_txt)
+        self.assertEqual(
+            'Hello from module 1!' + '\n' + 'Hello from module 2!',
+            module02_txt
+        )
+
+        # Remove the .compiled directory, if it exists
+        self._remove_compiled_dir(wkdir)
+
+        # Set up wkdir for the next test case
+        self._set_up_wkdir()
+
+    def test_simple_project_modules_prefix_in_arg(self):
+        """
+        `prism run` on simple project where `modules/` is included in the `--module`
+        CLI argument
+        """
+        self.maxDiff = None
+
+        # Set working directory
+        wkdir = Path(TEST_PROJECTS) / '021_no_py_in_ref'
+        os.chdir(wkdir)
+
+        # Remove the .compiled directory, if it exists
+        self._remove_compiled_dir(wkdir)
+
+        # Remove all files in the output directory
+        self._remove_files_in_output(wkdir)
+
+        # Execute command. Remove the `.py` from the command as well.
+        args = [
+            'run',
+            '--module', 'modules/module01',
+            '--module', 'modules/module02',
+            '--module', 'modules/module03',
+            '--module', 'modules/module04',
+        ]
+        with pytest.raises(SystemExit) as cm:
+            self._run_prism(args)
+        self.assertEqual(cm.value.code, 1)
+
+        # Set up wkdir for the next test case
+        self._set_up_wkdir()
```

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_spark_submit.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_spark_submit.py`

 * *Files 1% similar despite different names*

```diff
@@ -127,15 +127,15 @@
 
         # ***************** #
         # Run only module 1 #
         # ***************** #
 
         # Expecatation: module 1 is the first module in the DAG. Therefore, we should
         # not encounter any errors with this command.
-        args = ['spark-submit', '--modules', 'module01.py']
+        args = ['spark-submit', '--module', 'module01.py']
         self._run_prism(args)
 
         # Check manifest
         self.assertTrue(Path(wkdir / '.compiled').is_dir())
         self.assertTrue(Path(wkdir / '.compiled' / 'manifest.json').is_file())
         manifest = self._load_manifest(Path(wkdir / '.compiled' / 'manifest.json'))
         module01_refs = self._load_module_refs("module01.py", manifest)
@@ -159,15 +159,15 @@
         # Execute module 2 #
         # **************** #
 
         # Expecatation: module 2 depends on module 1. However, since we just ran module
         # 1, and the output of module 1 is stored in a target, we do not need to re-run
         # module 1 in order to run module 2. Therefore, we should not encounter any
         # errors with this command.
-        args = ['spark-submit', '--modules', 'module02.py']
+        args = ['spark-submit', '--module', 'module02.py']
         self._run_prism(args)
 
         # Check the results of the output directory
         self.assertTrue(Path(wkdir / 'output' / 'module01').is_dir())
         self.assertTrue(Path(wkdir / 'output' / 'module02').is_dir())
         module02_df = pd.read_parquet(Path(wkdir / 'output' / 'module02'))
         self.assertEqual(['col1', 'col2', 'col3'], list(module02_df.columns))
@@ -183,21 +183,21 @@
 
         # Expectation: module 4 depends on module 3. However, the output of module 3 is
         # not stored in a target. Therefore, running module 4 without including
         # 'all-upstream' should cause an error.
 
         # -------------------------------------
         # Execute command without `all-upstream`
-        args = ['spark-submit', '--modules', 'module04.py']
+        args = ['spark-submit', '--module', 'module04.py']
         self._run_prism(args)
         self.assertFalse(Path(wkdir / 'output' / 'module04').is_dir())
 
         # -----------------------------------
         # Execute command with `all-upstream`
-        args = ['spark-submit', '--modules', 'module04.py', '--all-upstream']
+        args = ['spark-submit', '--module', 'module04.py', '--all-upstream']
         self._run_prism(args)
         self.assertTrue(Path(wkdir / 'output' / 'module04').is_dir())
         module04_df = pd.read_parquet(Path(wkdir / 'output' / 'module04'))
         self.assertEqual(['col1', 'col2', 'col3'], list(module04_df.columns))
         self.assertEqual(3, module04_df.shape[0])
         module04_df.sort_values(by='col1', inplace=True)
         module04_df.reset_index(inplace=True)
@@ -228,15 +228,15 @@
         # Remove the .compiled directory, if it exists
         self._remove_compiled_dir(wkdir)
 
         # Remove all files in the output directory
         self._remove_dirs_in_output(wkdir)
 
         # Run all modules downstream of module01.py
-        args = ['spark-submit', '--modules', 'module01.py', '--all-downstream']
+        args = ['spark-submit', '--module', 'module01.py', '--all-downstream']
         self._run_prism(args)
 
         # Check manifest
         self.assertTrue(Path(wkdir / '.compiled').is_dir())
         self.assertTrue(Path(wkdir / '.compiled' / 'manifest.json').is_file())
         manifest = self._load_manifest(Path(wkdir / '.compiled' / 'manifest.json'))
         module01_refs = self._load_module_refs("module01.py", manifest)
```

### Comparing `prism-ds-0.1.9rc2/prism/tests/integration/test_targets.py` & `prism-ds-0.2.0rc1/prism/tests/integration/test_targets.py`

 * *Files 10% similar despite different names*

```diff
@@ -8,48 +8,37 @@
 """
 
 ###########
 # Imports #
 ###########
 
 # Standard library imports
-import io
-import boto3
-import boto3.session
 import os
 from pathlib import Path
-import re
-import shutil
-import unittest
 import pandas as pd
-import yaml
 
 # Prism imports
-import prism.cli.base
-from prism.main import main
-import prism.logging
 import prism.tests.integration.integration_test_class as integration_test_class
 
 
 #################################
 # Test case directory and paths #
 #################################
 
 # Directory containing all prism_project.py test cases
 TEST_CASE_WKDIR = os.path.dirname(__file__)
 TEST_PROJECTS = Path(TEST_CASE_WKDIR) / 'test_projects'
 
 
-################################
-## Test case class definition ##
-################################
+##############################
+# Test case class definition #
+##############################
 
-class TestTargetIntegration(integration_test_class.IntegrationTestCase): 
+class TestTargetIntegration(integration_test_class.IntegrationTestCase):
 
-    
     def test_targets(self):
         """
         `prism spark-submit` on project `008_targets` produces the expected targets
         """
         self.maxDiff = None
 
         # Set working directory
@@ -61,52 +50,58 @@
 
         # Remove all folders / files in the output directory
         self._remove_dirs_in_output(wkdir)
         self._remove_files_in_output(wkdir)
 
         # Execute command.
         args = ['spark-submit']
-        spark_submit = self._run_prism(args)
+        _ = self._run_prism(args)
         self.assertTrue(Path(wkdir / '.compiled').is_dir())
         self.assertTrue(Path(wkdir / '.compiled' / 'manifest.json').is_file())
         manifest = self._load_manifest(Path(wkdir / '.compiled' / 'manifest.json'))
         for module in ['parquet.py', 'txt.py', 'csv.py', 'csv_mult.py']:
             refs = self._load_module_refs(module, manifest)
             self.assertEqual([], refs)
 
         # Check contents of output
 
         # Parquet target
         target_parquet_df = pd.read_parquet(Path(wkdir / 'output' / 'target_parquet'))
         expected_df = pd.DataFrame({
-            'col1': ['col1_value1', 'col1_value2', 'col1_value3', 'col1_value4', 'col1_value5', 'col1_value6'],
-            'col2': ['col2_value1', 'col2_value2', 'col2_value3', 'col2_value4', 'col2_value5', 'col2_value6'],
-            'col3': ['col3_value1', 'col3_value2', 'col3_value3', 'col3_value4', 'col3_value5', 'col3_value6'],
+            'col1': ['col1_value1', 'col1_value2', 'col1_value3', 'col1_value4', 'col1_value5', 'col1_value6'],  # noqa: E501
+            'col2': ['col2_value1', 'col2_value2', 'col2_value3', 'col2_value4', 'col2_value5', 'col2_value6'],  # noqa: E501
+            'col3': ['col3_value1', 'col3_value2', 'col3_value3', 'col3_value4', 'col3_value5', 'col3_value6'],  # noqa: E501
         })
         self.assertTrue(target_parquet_df.equals(expected_df))
 
         # Txt target
         target_txt_txt = self._file_as_str(Path(wkdir / 'output' / 'target_txt.txt'))
         self.assertEqual('Hello, world!', target_txt_txt)
 
         # CSV (single target)
-        target_csv_df = pd.read_csv(Path(wkdir / 'output' / 'target_csv.csv'), index_col=None)
+        target_csv_df = pd.read_csv(
+            Path(wkdir / 'output' / 'target_csv.csv'), index_col=None
+        )
         expected_df = pd.DataFrame({
             'col1': ['col1_value1', 'col1_value2', 'col1_value3'],
             'col2': ['col2_value1', 'col2_value2', 'col2_value3'],
             'col3': ['col3_value1', 'col3_value2', 'col3_value3'],
             'col4': ['col4_value1', 'col4_value2', 'col4_value3'],
             'col5': ['col5_value1', 'col5_value2', 'col5_value3'],
             'col6': ['col6_value1', 'col6_value2', 'col6_value3']
         })
         self.assertTrue(target_csv_df.equals(expected_df))
 
         # CSV (multiple targets)
-        target_csv_mult_df1 = pd.read_csv(Path(wkdir / 'output' / 'target_csv_mult_df1.csv'), index_col=None)
-        target_csv_mult_df2 = pd.read_csv(Path(wkdir / 'output' / 'target_csv_mult_df2.csv'), index_col=None)
+        target_csv_mult_df1 = pd.read_csv(
+            Path(wkdir / 'output' / 'target_csv_mult_df1.csv'), index_col=None
+        )
+        target_csv_mult_df2 = pd.read_csv(
+            Path(wkdir / 'output' / 'target_csv_mult_df2.csv'), index_col=None
+        )
         expected_df1 = pd.DataFrame({
             'col1': ['col1_value1', 'col1_value2', 'col1_value3'],
             'col2': ['col2_value1', 'col2_value2', 'col2_value3'],
             'col3': ['col3_value1', 'col3_value2', 'col3_value3'],
             'col4': ['col4_value1', 'col4_value2', 'col4_value3'],
             'col5': ['col5_value1', 'col5_value2', 'col5_value3'],
             'col6': ['col6_value1', 'col6_value2', 'col6_value3']
@@ -120,23 +115,25 @@
             'colE': ['colE_value1', 'colE_value2', 'colE_value3'],
             'colF': ['colF_value1', 'colF_value2', 'colF_value3']
         })
         self.assertTrue(target_csv_mult_df1.equals(expected_df1))
         self.assertTrue(target_csv_mult_df2.equals(expected_df2))
 
         # CSV (iterated targets)
-        target_csv_iter_df1 = pd.read_csv(Path(wkdir / 'output' / 'target_csv_iter_df1.csv'), index_col=None)
-        target_csv_iter_df2 = pd.read_csv(Path(wkdir / 'output' / 'target_csv_iter_df2.csv'), index_col=None)
+        target_csv_iter_df1 = pd.read_csv(
+            Path(wkdir / 'output' / 'target_csv_iter_df1.csv'), index_col=None
+        )
+        target_csv_iter_df2 = pd.read_csv(
+            Path(wkdir / 'output' / 'target_csv_iter_df2.csv'), index_col=None
+        )
         self.assertTrue(target_csv_iter_df1.equals(expected_df1))
         self.assertTrue(target_csv_iter_df2.equals(expected_df2))
 
-        # Remove all files in the output directory (to avoid having to commit and re-commit to Github)
+        # Remove all files in the output directory (to avoid having to commit and
+        # re-commit to Github)
         self._remove_parquet_files_in_dir(Path(wkdir / 'output' / 'target_parquet'))
 
         # Remove all compiled modules
         self._remove_compiled_dir(wkdir)
 
         # Set up wkdir for next test
         self._set_up_wkdir()
-
-
-# EOF
```

### Comparing `prism-ds-0.1.9rc2/prism/tests/unit/test_adapter_profile.py` & `prism-ds-0.2.0rc1/prism/tests/unit/test_adapter_profile.py`

 * *Files 1% similar despite different names*

```diff
@@ -30,15 +30,15 @@
 from prism.profiles import (  # noqa: F401
     meta,
     adapter,
     snowflake as prism_snowflake,
     pyspark as prism_pyspark
 )
 import prism.profiles.profile as pr
-import prism.logging
+import prism.prism_logging
 
 
 #################################
 # Test case directory and paths #
 #################################
 
 # Directory containing test cases
@@ -93,15 +93,15 @@
 
 # We need to set up the default logger so that some warnings will fire
 @dataclass
 class LoggingArgs:
     log_level: str = 'info'
 
 
-prism.logging.set_up_logger(LoggingArgs())
+prism.prism_logging.set_up_logger(LoggingArgs())
 
 
 def _remove_logs():
     if Path(Path(__file__).parent / 'logs.log').is_file():
         os.unlink(Path(__file__).parent / 'logs.log')
```

### Comparing `prism-ds-0.1.9rc2/prism/tests/unit/test_agent/prism_project.py` & `prism-ds-0.2.0rc1/prism/tests/unit/test_agent/prism_project.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/unit/test_agents.py` & `prism-ds-0.2.0rc1/prism/tests/unit/test_agents.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/unit/test_all_dag_fns.py` & `prism-ds-0.2.0rc1/prism/tests/unit/test_all_dag_fns.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/unit/test_jinja.py` & `prism-ds-0.2.0rc1/prism/tests/unit/test_jinja.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/unit/test_module_parser_cls.py` & `prism-ds-0.2.0rc1/prism/tests/unit/test_module_parser_cls.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/unit/test_module_parser_dec.py` & `prism-ds-0.2.0rc1/prism/tests/unit/test_module_parser_dec.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/unit/test_prism_project_py/bad_trigger_key.py` & `prism-ds-0.2.0rc1/prism/tests/unit/test_prism_project_py/bad_trigger_key.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/unit/test_prism_project_py/multiple_profiles.py` & `prism-ds-0.2.0rc1/prism/tests/unit/test_prism_project_py/multiple_profiles.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/unit/test_prism_project_py/no_profile.py` & `prism-ds-0.2.0rc1/prism/tests/unit/test_prism_project_py/no_profile.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/unit/test_prism_project_py/non_null_profile.py` & `prism-ds-0.2.0rc1/prism/tests/unit/test_prism_project_py/non_null_profile.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/unit/test_prism_project_py/null_profile.py` & `prism-ds-0.2.0rc1/prism/tests/unit/test_prism_project_py/null_profile.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/unit/test_prism_project_py/on_failure_triggers_only.py` & `prism-ds-0.2.0rc1/prism/tests/unit/test_prism_project_py/on_failure_triggers_only.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/unit/test_prism_project_py/on_success_triggers_only.py` & `prism-ds-0.2.0rc1/prism/tests/unit/test_prism_project_py/on_success_triggers_only.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/unit/test_prism_project_py/triggers_normal.py` & `prism-ds-0.2.0rc1/prism/tests/unit/test_prism_project_py/triggers_normal.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/unit/test_project.py` & `prism-ds-0.2.0rc1/prism/tests/unit/test_project.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/unit/test_trigger.py` & `prism-ds-0.2.0rc1/prism/tests/unit/test_trigger.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/tests/unit/test_trigger_yml/prism_project.py` & `prism-ds-0.2.0rc1/prism/tests/unit/test_trigger_yml/prism_project.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism/triggers/__init__.py` & `prism-ds-0.2.0rc1/prism/triggers/__init__.py`

 * *Files 2% similar despite different names*

```diff
@@ -10,15 +10,15 @@
 # Imports #
 ###########
 
 # Prism imports
 from prism.cli.base import TaskRunReturnResult
 from prism.event_managers.base import BaseEventManager
 import prism.exceptions
-import prism.logging
+import prism.prism_logging
 from prism.parsers import yml_parser
 from prism.infra.project import PrismProject
 from prism.constants import VALID_TRIGGER_TYPES
 
 # Standard library imports
 import jinja2
 from pathlib import Path
@@ -250,15 +250,15 @@
         # Check top-level keys
         top_level_keys = list(triggers_yml.keys())
 
         # Identify keys that are not in the expected keys
         unexpected_keys = list(set(top_level_keys) - set(expected_keys))
         if len(unexpected_keys) > 0:
             warning_events.append(
-                prism.logging.UnexpectedTriggersYmlKeysEvent(unexpected_keys)
+                prism.prism_logging.UnexpectedTriggersYmlKeysEvent(unexpected_keys)
             )
 
         # We definitely need the triggers YML to have `triggers`. The `include` key is
         # optional.
         if "triggers" not in top_level_keys:
             raise prism.exceptions.InvalidTriggerException(
                 message="could not find `triggers` key in triggers YML file"
@@ -438,15 +438,15 @@
 
             # Return warning events
             return warning_events
 
     def exec(self,
         trigger_type: str,
         full_tb: bool,
-        event_list: List[prism.logging.Event],
+        event_list: List[prism.prism_logging.Event],
         run_context: Dict[Any, Any]
     ):
         """
         Execute the triggers for `trigger_type`
 
         args:
             trigger_type: either `on_success` or `on_failure`
@@ -473,43 +473,43 @@
             event_list=event_list,
             fire_exec_events=False,
             fire_empty_line_events=False,
             run_context=run_context
         )
         event_list = setup_event_manager_output.event_list
         if setup_event_manager_output.outputs == 0:
-            event_list = prism.logging.fire_console_event(
+            event_list = prism.prism_logging.fire_console_event(
                 setup_event_manager_output.event_to_fire, event_list, log_level='error'
             )
             return TaskRunReturnResult(
                 event_list, True
             )
 
         # Warning events
         warning_events = setup_event_manager_output.outputs
 
         # Trigger header events
         triggers_to_exec = getattr(self, f"{trigger_type}_triggers")
         if len(triggers_to_exec) > 0:
-            event_list = prism.logging.fire_console_event(
-                prism.logging.TriggersHeaderEvent(),
+            event_list = prism.prism_logging.fire_console_event(
+                prism.prism_logging.TriggersHeaderEvent(),
                 event_list,
             )
 
             # Warning to indicate we defaulted to project directory
             if self.defaulted_to_project_dir:
-                event_list = prism.logging.fire_console_event(
-                    prism.logging.TriggersPathNotDefined(),
+                event_list = prism.prism_logging.fire_console_event(
+                    prism.prism_logging.TriggersPathNotDefined(),
                     event_list,
                     log_level='warn'
                 )
 
             # Fire all other warnings encountered during setup
             for ev in warning_events:
-                event_list = prism.logging.fire_console_event(
+                event_list = prism.prism_logging.fire_console_event(
                     ev,
                     event_list,
                     log_level='warn'
                 )
 
         # Execute triggers
         cb_has_error = False
@@ -528,14 +528,14 @@
             )
             event_list = cb_event_manager_output.event_list
 
             # Fire the error event. Don't return after the first error, because we want
             # to execute all triggers.
             if cb_event_manager_output.outputs == 0:
                 cb_has_error = True
-                event_list = prism.logging.fire_empty_line_event(event_list)
-                event_list = prism.logging.fire_console_event(
+                event_list = prism.prism_logging.fire_empty_line_event(event_list)
+                event_list = prism.prism_logging.fire_console_event(
                     cb_event_manager_output.event_to_fire, event_list, log_level='error'
                 )
         return TaskRunReturnResult(
             event_list, cb_has_error
         )
```

### Comparing `prism-ds-0.1.9rc2/prism/ui.py` & `prism-ds-0.2.0rc1/prism/ui.py`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/prism_ds.egg-info/PKG-INFO` & `prism-ds-0.2.0rc1/prism_ds.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: prism-ds
-Version: 0.1.9rc2
+Version: 0.2.0rc1
 Summary: The easiest way to create data pipelines in Python.
 Author: prism founders
 Author-email: hello@runprism.com
 License: Apache-2.0
 Project-URL: homepage, https://www.runprism.com
 Project-URL: documentation, https://docs.runprism.com
 Project-URL: repository, https://github.com/runprism/prism
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: prism-ds Version: 0.1.9rc2 Summary: The easiest way
+Metadata-Version: 2.1 Name: prism-ds Version: 0.2.0rc1 Summary: The easiest way
 to create data pipelines in Python. Author: prism founders Author-email:
 hello@runprism.com License: Apache-2.0 Project-URL: homepage, https://
 www.runprism.com Project-URL: documentation, https://docs.runprism.com Project-
 URL: repository, https://github.com/runprism/prism Platform: unix Platform:
 linux Platform: osx Platform: win32 Classifier: Programming Language :: Python
 :: 3 Classifier: Programming Language :: Python :: 3.7 Classifier: Programming
 Language :: Python :: 3.8 Classifier: Programming Language :: Python :: 3.9
```

### Comparing `prism-ds-0.1.9rc2/prism_ds.egg-info/SOURCES.txt` & `prism-ds-0.2.0rc1/prism_ds.egg-info/SOURCES.txt`

 * *Files 1% similar despite different names*

```diff
@@ -4,16 +4,16 @@
 pyproject.toml
 setup.cfg
 setup.py
 prism/__init__.py
 prism/admin.py
 prism/constants.py
 prism/exceptions.py
-prism/logging.py
 prism/main.py
+prism/prism_logging.py
 prism/target.py
 prism/task.py
 prism/ui.py
 prism/agents/__init__.py
 prism/agents/base.py
 prism/agents/docker_agent.py
 prism/agents/ec2.py
@@ -133,18 +133,20 @@
 prism/tests/integration/test_init.py
 prism/tests/integration/test_run.py
 prism/tests/integration/test_spark_submit.py
 prism/tests/integration/test_targets.py
 prism/tests/integration/test_projects/001_init/__init__.py
 prism/tests/integration/test_projects/001_init/prism_project.py
 prism/tests/integration/test_projects/001_init/utils.py
-prism/tests/integration/test_projects/001_init/modules/module01.py
+prism/tests/integration/test_projects/001_init/modules/class_task.py
+prism/tests/integration/test_projects/001_init/modules/decorated_task.py
 prism/tests/integration/test_projects/001a_init_minimal/__init__.py
 prism/tests/integration/test_projects/001a_init_minimal/prism_project.py
-prism/tests/integration/test_projects/001a_init_minimal/modules/module01.py
+prism/tests/integration/test_projects/001a_init_minimal/modules/class_task.py
+prism/tests/integration/test_projects/001a_init_minimal/modules/decorated_task.py
 prism/tests/integration/test_projects/002_no_project_py/__init__.py
 prism/tests/integration/test_projects/002_no_project_py/functions.py
 prism/tests/integration/test_projects/002_no_project_py/modules/module01.py
 prism/tests/integration/test_projects/002_no_project_py/modules/module02.py
 prism/tests/integration/test_projects/002_no_project_py/modules/module03.py
 prism/tests/integration/test_projects/003_project_with_cycle/__init__.py
 prism/tests/integration/test_projects/003_project_with_cycle/prism_project.py
@@ -234,14 +236,20 @@
 prism/tests/integration/test_projects/019_dec_targets/modules/extract.py
 prism/tests/integration/test_projects/019_dec_targets/modules/load.py
 prism/tests/integration/test_projects/020_dec_retries/__init__.py
 prism/tests/integration/test_projects/020_dec_retries/prism_project.py
 prism/tests/integration/test_projects/020_dec_retries/utils.py
 prism/tests/integration/test_projects/020_dec_retries/modules/extract.py
 prism/tests/integration/test_projects/020_dec_retries/modules/load.py
+prism/tests/integration/test_projects/021_no_py_in_ref/__init__.py
+prism/tests/integration/test_projects/021_no_py_in_ref/prism_project.py
+prism/tests/integration/test_projects/021_no_py_in_ref/modules/module01.py
+prism/tests/integration/test_projects/021_no_py_in_ref/modules/module02.py
+prism/tests/integration/test_projects/021_no_py_in_ref/modules/module03.py
+prism/tests/integration/test_projects/021_no_py_in_ref/modules/module04.py
 prism/tests/integration/test_projects/common/__init__.py
 prism/tests/integration/test_projects/common/functions.py
 prism/tests/unit/__init__.py
 prism/tests/unit/test_adapter_profile.py
 prism/tests/unit/test_agents.py
 prism/tests/unit/test_all_dag_fns.py
 prism/tests/unit/test_import.py
```

### Comparing `prism-ds-0.1.9rc2/prism_ds.egg-info/requires.txt` & `prism-ds-0.2.0rc1/prism_ds.egg-info/requires.txt`

 * *Files 4% similar despite different names*

```diff
@@ -7,15 +7,15 @@
 pandas>=1
 PyYAML>=6
 requests>=2
 Jinja2==3.1.2
 MarkupSafe>=2.0
 coolname>=2.2
 shortuuid>=1.0
-rich-argparse>=1.1.0
+rich_click>=1.6.1
 
 [bigquery]
 google-api-python-client>=2
 google-auth>=2
 google-cloud-bigquery>=2
 db-dtypes>=1
```

### Comparing `prism-ds-0.1.9rc2/pyproject.toml` & `prism-ds-0.2.0rc1/pyproject.toml`

 * *Files identical despite different names*

### Comparing `prism-ds-0.1.9rc2/setup.cfg` & `prism-ds-0.2.0rc1/setup.cfg`

 * *Files 4% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 [metadata]
 name = prism-ds
 description = The easiest way to create data pipelines in Python.
 long_description_content_type = text/markdown
 long_description = file: README.md
-version = 0.1.9rc2
+version = 0.2.0rc1
 author = prism founders
 author_email = hello@runprism.com
 license = Apache-2.0
 license_file = LICENSE
 platforms = unix, linux, osx, win32
 classifiers = 
 	Programming Language :: Python :: 3
@@ -33,15 +33,15 @@
 	pandas>=1
 	PyYAML>=6
 	requests>=2
 	Jinja2==3.1.2
 	MarkupSafe>=2.0
 	coolname>=2.2
 	shortuuid>=1.0
-	rich-argparse>=1.1.0
+	rich_click>=1.6.1
 python_requires = >=3.7
 zip_safe = no
 
 [options.extras_require]
 snowflake = 
 	snowflake-connector-python>=2
 	pyarrow<10.1.0,>=10.0.1
@@ -66,15 +66,15 @@
 	dbt-snowflake>=1
 	pytest>=7
 	fastparquet>=0.8,<1
 	tox>=3.24
 
 [options.entry_points]
 console_scripts = 
-	prism = prism.main:main
+	prism = prism.main:invoke
 
 [flake8]
 ignore = E124, E128
 per-file-ignores = 
 	prism/cli/init.py: W605
 	prism/spark/script.py: F401, E201, E202, F821
 	prism/logging.py: F821
```


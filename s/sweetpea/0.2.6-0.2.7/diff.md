# Comparing `tmp/sweetpea-0.2.6.tar.gz` & `tmp/sweetpea-0.2.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "sweetpea-0.2.6.tar", last modified: Thu Feb  9 22:23:14 2023, max compression
+gzip compressed data, was "sweetpea-0.2.7.tar", last modified: Wed Jun 28 13:26:02 2023, max compression
```

## Comparing `sweetpea-0.2.6.tar` & `sweetpea-0.2.7.tar`

### file list

```diff
@@ -1,114 +1,117 @@
-drwxr-xr-x   0 mflatt     (501) staff       (20)        0 2023-02-09 22:23:14.942772 sweetpea-0.2.6/
--rw-r--r--   0 mflatt     (501) staff       (20)     6102 2023-02-09 22:23:14.942644 sweetpea-0.2.6/PKG-INFO
--rw-r--r--   0 mflatt     (501) staff       (20)     4609 2022-12-03 09:35:53.000000 sweetpea-0.2.6/README.md
-drwxr-xr-x   0 mflatt     (501) staff       (20)        0 2023-02-09 22:23:14.923018 sweetpea-0.2.6/acceptance/
--rw-r--r--   0 mflatt     (501) staff       (20)     2049 2022-12-03 09:33:05.000000 sweetpea-0.2.6/acceptance/__init__.py
--rw-r--r--   0 mflatt     (501) staff       (20)      577 2021-08-23 12:23:58.000000 sweetpea-0.2.6/acceptance/conftest.py
--rw-r--r--   0 mflatt     (501) staff       (20)     1710 2023-02-09 04:40:37.000000 sweetpea-0.2.6/acceptance/test_crossed_derived_via_rejection.py
--rw-r--r--   0 mflatt     (501) staff       (20)     3120 2023-02-09 04:40:37.000000 sweetpea-0.2.6/acceptance/test_exhaust_combinatoric.py
--rw-r--r--   0 mflatt     (501) staff       (20)     3064 2022-12-03 09:33:05.000000 sweetpea-0.2.6/acceptance/test_general_window.py
--rw-r--r--   0 mflatt     (501) staff       (20)      728 2022-12-03 09:33:05.000000 sweetpea-0.2.6/acceptance/test_guided_sampling.py
--rw-r--r--   0 mflatt     (501) staff       (20)     1667 2022-12-03 09:33:05.000000 sweetpea-0.2.6/acceptance/test_implied.py
--rw-r--r--   0 mflatt     (501) staff       (20)     3289 2023-02-09 22:18:31.000000 sweetpea-0.2.6/acceptance/test_k_constraint.py
--rw-r--r--   0 mflatt     (501) staff       (20)     2265 2023-02-09 04:40:37.000000 sweetpea-0.2.6/acceptance/test_minimum_trials.py
--rw-r--r--   0 mflatt     (501) staff       (20)    10626 2023-02-09 04:40:37.000000 sweetpea-0.2.6/acceptance/test_multiple_cross.py
--rw-r--r--   0 mflatt     (501) staff       (20)     4000 2023-02-09 04:40:37.000000 sweetpea-0.2.6/acceptance/test_pin.py
--rw-r--r--   0 mflatt     (501) staff       (20)    11547 2022-12-03 09:33:05.000000 sweetpea-0.2.6/acceptance/test_reduced_crossing_with_exclude.py
--rw-r--r--   0 mflatt     (501) staff       (20)     3256 2023-02-09 04:40:37.000000 sweetpea-0.2.6/acceptance/test_sample_check.py
--rw-r--r--   0 mflatt     (501) staff       (20)     1399 2022-12-03 09:33:05.000000 sweetpea-0.2.6/acceptance/test_server.py
--rw-r--r--   0 mflatt     (501) staff       (20)     4866 2022-12-03 09:33:05.000000 sweetpea-0.2.6/acceptance/test_stroop.py
--rw-r--r--   0 mflatt     (501) staff       (20)     3894 2022-12-03 09:33:05.000000 sweetpea-0.2.6/acceptance/test_stroop_crossing_with_derived.py
--rw-r--r--   0 mflatt     (501) staff       (20)     2343 2022-12-03 09:33:05.000000 sweetpea-0.2.6/acceptance/test_task_switching_simple.py
--rw-r--r--   0 mflatt     (501) staff       (20)     2383 2022-12-03 09:33:05.000000 sweetpea-0.2.6/acceptance/test_transition_with_three_levels.py
--rw-r--r--   0 mflatt     (501) staff       (20)     1620 2022-12-03 09:33:05.000000 sweetpea-0.2.6/acceptance/test_uniform_combinatoric.py
--rw-r--r--   0 mflatt     (501) staff       (20)     4763 2023-02-09 04:40:37.000000 sweetpea-0.2.6/acceptance/test_weights.py
--rw-r--r--   0 mflatt     (501) staff       (20)     3101 2023-02-09 04:40:37.000000 sweetpea-0.2.6/acceptance/test_window_start.py
--rw-r--r--   0 mflatt     (501) staff       (20)       38 2023-02-09 22:23:14.942813 sweetpea-0.2.6/setup.cfg
--rw-r--r--   0 mflatt     (501) staff       (20)     1044 2023-02-09 22:23:09.000000 sweetpea-0.2.6/setup.py
-drwxr-xr-x   0 mflatt     (501) staff       (20)        0 2023-02-09 22:23:14.923175 sweetpea-0.2.6/sweetpea/
--rw-r--r--   0 mflatt     (501) staff       (20)      290 2022-12-02 01:18:47.000000 sweetpea-0.2.6/sweetpea/__init__.py
-drwxr-xr-x   0 mflatt     (501) staff       (20)        0 2023-02-09 22:23:14.930622 sweetpea-0.2.6/sweetpea/_internal/
--rw-r--r--   0 mflatt     (501) staff       (20)        0 2022-10-10 07:42:53.000000 sweetpea-0.2.6/sweetpea/_internal/__init__.py
--rw-r--r--   0 mflatt     (501) staff       (20)      852 2022-10-04 05:23:04.000000 sweetpea-0.2.6/sweetpea/_internal/argcheck.py
--rw-r--r--   0 mflatt     (501) staff       (20)     2544 2022-12-02 01:51:40.000000 sweetpea-0.2.6/sweetpea/_internal/backend.py
--rw-r--r--   0 mflatt     (501) staff       (20)     1860 2023-02-09 04:40:37.000000 sweetpea-0.2.6/sweetpea/_internal/base_constraint.py
--rw-r--r--   0 mflatt     (501) staff       (20)      250 2022-11-21 07:46:41.000000 sweetpea-0.2.6/sweetpea/_internal/beforestart.py
--rw-r--r--   0 mflatt     (501) staff       (20)    22431 2023-02-09 21:54:46.000000 sweetpea-0.2.6/sweetpea/_internal/block.py
--rw-r--r--   0 mflatt     (501) staff       (20)      792 2023-02-09 04:40:37.000000 sweetpea-0.2.6/sweetpea/_internal/check_mismatch.py
--rw-r--r--   0 mflatt     (501) staff       (20)    17420 2022-10-21 02:18:36.000000 sweetpea-0.2.6/sweetpea/_internal/combinatorics.py
--rw-r--r--   0 mflatt     (501) staff       (20)    34270 2023-02-09 22:17:51.000000 sweetpea-0.2.6/sweetpea/_internal/constraint.py
-drwxr-xr-x   0 mflatt     (501) staff       (20)        0 2023-02-09 22:23:14.932572 sweetpea-0.2.6/sweetpea/_internal/core/
--rw-r--r--   0 mflatt     (501) staff       (20)     2520 2022-10-03 06:13:08.000000 sweetpea-0.2.6/sweetpea/_internal/core/__init__.py
--rw-r--r--   0 mflatt     (501) staff       (20)     1078 2022-10-03 06:13:08.000000 sweetpea-0.2.6/sweetpea/_internal/core/binary.py
--rw-r--r--   0 mflatt     (501) staff       (20)    26295 2022-12-01 02:30:31.000000 sweetpea-0.2.6/sweetpea/_internal/core/cnf.py
-drwxr-xr-x   0 mflatt     (501) staff       (20)        0 2023-02-09 22:23:14.933509 sweetpea-0.2.6/sweetpea/_internal/core/generate/
--rw-r--r--   0 mflatt     (501) staff       (20)      691 2022-10-03 06:13:08.000000 sweetpea-0.2.6/sweetpea/_internal/core/generate/__init__.py
--rw-r--r--   0 mflatt     (501) staff       (20)      567 2022-10-03 06:13:08.000000 sweetpea-0.2.6/sweetpea/_internal/core/generate/is_satisfiable.py
--rw-r--r--   0 mflatt     (501) staff       (20)     2620 2022-12-01 02:32:09.000000 sweetpea-0.2.6/sweetpea/_internal/core/generate/sample_ilp.py
--rw-r--r--   0 mflatt     (501) staff       (20)     4189 2022-10-03 06:13:08.000000 sweetpea-0.2.6/sweetpea/_internal/core/generate/sample_non_uniform.py
--rw-r--r--   0 mflatt     (501) staff       (20)     2061 2022-10-03 06:13:08.000000 sweetpea-0.2.6/sweetpea/_internal/core/generate/sample_uniform.py
-drwxr-xr-x   0 mflatt     (501) staff       (20)        0 2023-02-09 22:23:14.934634 sweetpea-0.2.6/sweetpea/_internal/core/generate/tools/
--rw-r--r--   0 mflatt     (501) staff       (20)      103 2022-10-03 06:13:08.000000 sweetpea-0.2.6/sweetpea/_internal/core/generate/tools/__init__.py
--rw-r--r--   0 mflatt     (501) staff       (20)     4907 2022-10-03 06:13:08.000000 sweetpea-0.2.6/sweetpea/_internal/core/generate/tools/cryptominisat.py
--rw-r--r--   0 mflatt     (501) staff       (20)     2469 2022-10-03 06:13:08.000000 sweetpea-0.2.6/sweetpea/_internal/core/generate/tools/docker_utility.py
--rw-r--r--   0 mflatt     (501) staff       (20)    14831 2022-10-03 06:13:08.000000 sweetpea-0.2.6/sweetpea/_internal/core/generate/tools/executables.py
--rw-r--r--   0 mflatt     (501) staff       (20)      660 2022-10-03 06:13:08.000000 sweetpea-0.2.6/sweetpea/_internal/core/generate/tools/return_code.py
--rw-r--r--   0 mflatt     (501) staff       (20)      555 2022-10-03 06:13:08.000000 sweetpea-0.2.6/sweetpea/_internal/core/generate/tools/tool_error.py
--rw-r--r--   0 mflatt     (501) staff       (20)     4305 2022-11-15 05:22:44.000000 sweetpea-0.2.6/sweetpea/_internal/core/generate/tools/unigen.py
--rw-r--r--   0 mflatt     (501) staff       (20)     7111 2022-11-30 23:55:59.000000 sweetpea-0.2.6/sweetpea/_internal/core/generate/utility.py
--rw-r--r--   0 mflatt     (501) staff       (20)     4641 2022-10-03 06:13:08.000000 sweetpea-0.2.6/sweetpea/_internal/core/simple_sequence.py
--rw-r--r--   0 mflatt     (501) staff       (20)     4380 2022-10-03 06:13:08.000000 sweetpea-0.2.6/sweetpea/_internal/core/tests.py
--rw-r--r--   0 mflatt     (501) staff       (20)    25601 2023-02-09 04:40:37.000000 sweetpea-0.2.6/sweetpea/_internal/cross_block.py
--rw-r--r--   0 mflatt     (501) staff       (20)     8113 2022-12-05 02:16:56.000000 sweetpea-0.2.6/sweetpea/_internal/derivation_processor.py
--rw-r--r--   0 mflatt     (501) staff       (20)     1468 2022-12-02 01:52:33.000000 sweetpea-0.2.6/sweetpea/_internal/design_graph.py
--rw-r--r--   0 mflatt     (501) staff       (20)     3011 2023-01-09 05:00:49.000000 sweetpea-0.2.6/sweetpea/_internal/design_partition.py
--rw-r--r--   0 mflatt     (501) staff       (20)     4296 2022-12-02 03:04:51.000000 sweetpea-0.2.6/sweetpea/_internal/encoding_diagram.py
--rw-r--r--   0 mflatt     (501) staff       (20)     1762 2022-12-03 09:33:05.000000 sweetpea-0.2.6/sweetpea/_internal/iter.py
--rw-r--r--   0 mflatt     (501) staff       (20)      491 2022-12-02 01:52:08.000000 sweetpea-0.2.6/sweetpea/_internal/level.py
--rw-r--r--   0 mflatt     (501) staff       (20)    12643 2022-10-03 06:13:08.000000 sweetpea-0.2.6/sweetpea/_internal/logic.py
--rw-r--r--   0 mflatt     (501) staff       (20)    15881 2023-02-09 04:40:37.000000 sweetpea-0.2.6/sweetpea/_internal/main.py
--rw-r--r--   0 mflatt     (501) staff       (20)     1103 2022-12-02 03:17:57.000000 sweetpea-0.2.6/sweetpea/_internal/metrics.py
--rw-r--r--   0 mflatt     (501) staff       (20)    34428 2023-02-04 08:32:16.000000 sweetpea-0.2.6/sweetpea/_internal/primitive.py
--rw-r--r--   0 mflatt     (501) staff       (20)     1408 2023-02-04 08:32:16.000000 sweetpea-0.2.6/sweetpea/_internal/sample_conversion.py
-drwxr-xr-x   0 mflatt     (501) staff       (20)        0 2023-02-09 22:23:14.936935 sweetpea-0.2.6/sweetpea/_internal/sampling_strategy/
--rw-r--r--   0 mflatt     (501) staff       (20)        0 2022-10-03 05:49:02.000000 sweetpea-0.2.6/sweetpea/_internal/sampling_strategy/__init__.py
--rw-r--r--   0 mflatt     (501) staff       (20)     3364 2022-12-02 01:42:23.000000 sweetpea-0.2.6/sweetpea/_internal/sampling_strategy/base.py
--rw-r--r--   0 mflatt     (501) staff       (20)      789 2022-12-03 09:33:05.000000 sweetpea-0.2.6/sweetpea/_internal/sampling_strategy/cmsgen.py
--rw-r--r--   0 mflatt     (501) staff       (20)    10000 2022-12-02 03:09:39.000000 sweetpea-0.2.6/sweetpea/_internal/sampling_strategy/guided.py
--rw-r--r--   0 mflatt     (501) staff       (20)      819 2022-12-03 09:33:05.000000 sweetpea-0.2.6/sweetpea/_internal/sampling_strategy/iterate.py
--rw-r--r--   0 mflatt     (501) staff       (20)      968 2022-12-03 09:33:05.000000 sweetpea-0.2.6/sweetpea/_internal/sampling_strategy/iterate_ilp.py
--rw-r--r--   0 mflatt     (501) staff       (20)     1147 2022-12-03 09:33:05.000000 sweetpea-0.2.6/sweetpea/_internal/sampling_strategy/iterate_sat.py
--rw-r--r--   0 mflatt     (501) staff       (20)    34094 2023-02-09 04:40:37.000000 sweetpea-0.2.6/sweetpea/_internal/sampling_strategy/random.py
--rw-r--r--   0 mflatt     (501) staff       (20)      815 2022-12-03 09:33:05.000000 sweetpea-0.2.6/sweetpea/_internal/sampling_strategy/uniform.py
--rw-r--r--   0 mflatt     (501) staff       (20)     1143 2022-12-03 09:33:05.000000 sweetpea-0.2.6/sweetpea/_internal/sampling_strategy/unigen.py
--rw-r--r--   0 mflatt     (501) staff       (20)     1186 2022-12-02 02:00:06.000000 sweetpea-0.2.6/sweetpea/_internal/server.py
--rw-r--r--   0 mflatt     (501) staff       (20)      199 2022-12-02 01:52:57.000000 sweetpea-0.2.6/sweetpea/_internal/weight.py
-drwxr-xr-x   0 mflatt     (501) staff       (20)        0 2023-02-09 22:23:14.941256 sweetpea-0.2.6/sweetpea/tests/
--rw-r--r--   0 mflatt     (501) staff       (20)        0 2022-10-03 06:13:08.000000 sweetpea-0.2.6/sweetpea/tests/__init__.py
-drwxr-xr-x   0 mflatt     (501) staff       (20)        0 2023-02-09 22:23:14.942302 sweetpea-0.2.6/sweetpea/tests/sampling_strategies/
--rw-r--r--   0 mflatt     (501) staff       (20)        0 2021-02-05 00:23:41.000000 sweetpea-0.2.6/sweetpea/tests/sampling_strategies/__init__.py
--rw-r--r--   0 mflatt     (501) staff       (20)     5386 2022-12-03 09:33:05.000000 sweetpea-0.2.6/sweetpea/tests/sampling_strategies/test_base_strategy.py
--rw-r--r--   0 mflatt     (501) staff       (20)      291 2022-12-02 03:10:03.000000 sweetpea-0.2.6/sweetpea/tests/sampling_strategies/test_guided.py
--rw-r--r--   0 mflatt     (501) staff       (20)    10529 2022-12-02 03:11:55.000000 sweetpea-0.2.6/sweetpea/tests/sampling_strategies/test_uc_solution_enumerator.py
--rw-r--r--   0 mflatt     (501) staff       (20)     5406 2023-02-09 04:40:37.000000 sweetpea-0.2.6/sweetpea/tests/sampling_strategies/test_uniform_combinatoric.py
--rw-r--r--   0 mflatt     (501) staff       (20)      542 2022-12-02 02:44:42.000000 sweetpea-0.2.6/sweetpea/tests/test_backend.py
--rw-r--r--   0 mflatt     (501) staff       (20)    22786 2023-02-09 04:40:37.000000 sweetpea-0.2.6/sweetpea/tests/test_blocks.py
--rw-r--r--   0 mflatt     (501) staff       (20)     7228 2022-12-02 03:05:24.000000 sweetpea-0.2.6/sweetpea/tests/test_combinatorics.py
--rw-r--r--   0 mflatt     (501) staff       (20)    29016 2023-02-09 04:40:37.000000 sweetpea-0.2.6/sweetpea/tests/test_constraints.py
--rw-r--r--   0 mflatt     (501) staff       (20)     4783 2022-12-02 03:03:23.000000 sweetpea-0.2.6/sweetpea/tests/test_constraints_tss.py
--rw-r--r--   0 mflatt     (501) staff       (20)     8864 2022-12-03 09:33:05.000000 sweetpea-0.2.6/sweetpea/tests/test_derivation_processor.py
--rw-r--r--   0 mflatt     (501) staff       (20)     2444 2022-12-03 09:33:05.000000 sweetpea-0.2.6/sweetpea/tests/test_derivation_processor_multi_argument_transition.py
--rw-r--r--   0 mflatt     (501) staff       (20)     2602 2022-12-03 09:33:05.000000 sweetpea-0.2.6/sweetpea/tests/test_derivation_processor_tss.py
--rw-r--r--   0 mflatt     (501) staff       (20)     1983 2022-12-03 09:33:05.000000 sweetpea-0.2.6/sweetpea/tests/test_design_graph.py
--rw-r--r--   0 mflatt     (501) staff       (20)     1804 2022-12-02 02:52:24.000000 sweetpea-0.2.6/sweetpea/tests/test_design_partitions.py
--rw-r--r--   0 mflatt     (501) staff       (20)     7804 2022-12-03 09:33:05.000000 sweetpea-0.2.6/sweetpea/tests/test_encoding_diagram.py
--rw-r--r--   0 mflatt     (501) staff       (20)     1550 2022-12-03 09:33:05.000000 sweetpea-0.2.6/sweetpea/tests/test_internal.py
--rw-r--r--   0 mflatt     (501) staff       (20)     9902 2022-12-02 02:53:10.000000 sweetpea-0.2.6/sweetpea/tests/test_logic.py
--rw-r--r--   0 mflatt     (501) staff       (20)     8858 2022-11-08 23:49:27.000000 sweetpea-0.2.6/sweetpea/tests/test_primitives.py
--rw-r--r--   0 mflatt     (501) staff       (20)     1116 2022-12-02 03:07:13.000000 sweetpea-0.2.6/sweetpea/tests/test_sweetpea.py
-drwxr-xr-x   0 mflatt     (501) staff       (20)        0 2023-02-09 22:23:14.923855 sweetpea-0.2.6/sweetpea.egg-info/
--rw-r--r--   0 mflatt     (501) staff       (20)     6102 2023-02-09 22:23:14.000000 sweetpea-0.2.6/sweetpea.egg-info/PKG-INFO
--rw-r--r--   0 mflatt     (501) staff       (20)     3894 2023-02-09 22:23:14.000000 sweetpea-0.2.6/sweetpea.egg-info/SOURCES.txt
--rw-r--r--   0 mflatt     (501) staff       (20)        1 2023-02-09 22:23:14.000000 sweetpea-0.2.6/sweetpea.egg-info/dependency_links.txt
--rw-r--r--   0 mflatt     (501) staff       (20)       61 2023-02-09 22:23:14.000000 sweetpea-0.2.6/sweetpea.egg-info/requires.txt
--rw-r--r--   0 mflatt     (501) staff       (20)       20 2023-02-09 22:23:14.000000 sweetpea-0.2.6/sweetpea.egg-info/top_level.txt
+drwxr-xr-x   0 mflatt     (501) staff       (20)        0 2023-06-28 13:26:02.081513 sweetpea-0.2.7/
+-rw-r--r--   0 mflatt     (501) staff       (20)     6102 2023-06-28 13:26:02.081388 sweetpea-0.2.7/PKG-INFO
+-rw-r--r--   0 mflatt     (501) staff       (20)     4609 2022-12-03 09:35:53.000000 sweetpea-0.2.7/README.md
+drwxr-xr-x   0 mflatt     (501) staff       (20)        0 2023-06-28 13:26:02.062662 sweetpea-0.2.7/acceptance/
+-rw-r--r--   0 mflatt     (501) staff       (20)     2049 2022-12-03 09:33:05.000000 sweetpea-0.2.7/acceptance/__init__.py
+-rw-r--r--   0 mflatt     (501) staff       (20)      577 2021-08-23 12:23:58.000000 sweetpea-0.2.7/acceptance/conftest.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     1446 2023-05-03 06:11:31.000000 sweetpea-0.2.7/acceptance/test_auto_correlation_score.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     1710 2023-02-09 04:40:37.000000 sweetpea-0.2.7/acceptance/test_crossed_derived_via_rejection.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     3120 2023-02-09 04:40:37.000000 sweetpea-0.2.7/acceptance/test_exhaust_combinatoric.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     3064 2022-12-03 09:33:05.000000 sweetpea-0.2.7/acceptance/test_general_window.py
+-rw-r--r--   0 mflatt     (501) staff       (20)      728 2022-12-03 09:33:05.000000 sweetpea-0.2.7/acceptance/test_guided_sampling.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     1667 2022-12-03 09:33:05.000000 sweetpea-0.2.7/acceptance/test_implied.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     3289 2023-02-09 22:18:31.000000 sweetpea-0.2.7/acceptance/test_k_constraint.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     2265 2023-02-09 04:40:37.000000 sweetpea-0.2.7/acceptance/test_minimum_trials.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     6651 2023-02-12 00:02:14.000000 sweetpea-0.2.7/acceptance/test_mismatch.py
+-rw-r--r--   0 mflatt     (501) staff       (20)    10626 2023-02-09 04:40:37.000000 sweetpea-0.2.7/acceptance/test_multiple_cross.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     4000 2023-02-09 04:40:37.000000 sweetpea-0.2.7/acceptance/test_pin.py
+-rw-r--r--   0 mflatt     (501) staff       (20)    11547 2022-12-03 09:33:05.000000 sweetpea-0.2.7/acceptance/test_reduced_crossing_with_exclude.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     3256 2023-02-09 04:40:37.000000 sweetpea-0.2.7/acceptance/test_sample_check.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     1399 2022-12-03 09:33:05.000000 sweetpea-0.2.7/acceptance/test_server.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     5744 2023-06-28 12:59:51.000000 sweetpea-0.2.7/acceptance/test_stroop.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     3894 2022-12-03 09:33:05.000000 sweetpea-0.2.7/acceptance/test_stroop_crossing_with_derived.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     2343 2022-12-03 09:33:05.000000 sweetpea-0.2.7/acceptance/test_task_switching_simple.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     2383 2022-12-03 09:33:05.000000 sweetpea-0.2.7/acceptance/test_transition_with_three_levels.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     1620 2022-12-03 09:33:05.000000 sweetpea-0.2.7/acceptance/test_uniform_combinatoric.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     4763 2023-02-11 23:36:49.000000 sweetpea-0.2.7/acceptance/test_weights.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     3101 2023-02-09 04:40:37.000000 sweetpea-0.2.7/acceptance/test_window_start.py
+-rw-r--r--   0 mflatt     (501) staff       (20)       38 2023-06-28 13:26:02.081559 sweetpea-0.2.7/setup.cfg
+-rw-r--r--   0 mflatt     (501) staff       (20)     1044 2023-06-28 13:19:00.000000 sweetpea-0.2.7/setup.py
+drwxr-xr-x   0 mflatt     (501) staff       (20)        0 2023-06-28 13:26:02.062793 sweetpea-0.2.7/sweetpea/
+-rw-r--r--   0 mflatt     (501) staff       (20)      290 2022-12-02 01:18:47.000000 sweetpea-0.2.7/sweetpea/__init__.py
+drwxr-xr-x   0 mflatt     (501) staff       (20)        0 2023-06-28 13:26:02.070070 sweetpea-0.2.7/sweetpea/_internal/
+-rw-r--r--   0 mflatt     (501) staff       (20)        0 2022-10-10 07:42:53.000000 sweetpea-0.2.7/sweetpea/_internal/__init__.py
+-rw-r--r--   0 mflatt     (501) staff       (20)      852 2022-10-04 05:23:04.000000 sweetpea-0.2.7/sweetpea/_internal/argcheck.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     5287 2023-05-03 06:11:31.000000 sweetpea-0.2.7/sweetpea/_internal/auto_correlation_score.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     2544 2022-12-02 01:51:40.000000 sweetpea-0.2.7/sweetpea/_internal/backend.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     1860 2023-02-09 04:40:37.000000 sweetpea-0.2.7/sweetpea/_internal/base_constraint.py
+-rw-r--r--   0 mflatt     (501) staff       (20)      250 2022-11-21 07:46:41.000000 sweetpea-0.2.7/sweetpea/_internal/beforestart.py
+-rw-r--r--   0 mflatt     (501) staff       (20)    22431 2023-02-09 21:54:46.000000 sweetpea-0.2.7/sweetpea/_internal/block.py
+-rw-r--r--   0 mflatt     (501) staff       (20)      792 2023-02-09 04:40:37.000000 sweetpea-0.2.7/sweetpea/_internal/check_mismatch.py
+-rw-r--r--   0 mflatt     (501) staff       (20)    17420 2022-10-21 02:18:36.000000 sweetpea-0.2.7/sweetpea/_internal/combinatorics.py
+-rw-r--r--   0 mflatt     (501) staff       (20)    34251 2023-02-12 00:02:14.000000 sweetpea-0.2.7/sweetpea/_internal/constraint.py
+drwxr-xr-x   0 mflatt     (501) staff       (20)        0 2023-06-28 13:26:02.071442 sweetpea-0.2.7/sweetpea/_internal/core/
+-rw-r--r--   0 mflatt     (501) staff       (20)     2520 2022-10-03 06:13:08.000000 sweetpea-0.2.7/sweetpea/_internal/core/__init__.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     1078 2022-10-03 06:13:08.000000 sweetpea-0.2.7/sweetpea/_internal/core/binary.py
+-rw-r--r--   0 mflatt     (501) staff       (20)    26295 2022-12-01 02:30:31.000000 sweetpea-0.2.7/sweetpea/_internal/core/cnf.py
+drwxr-xr-x   0 mflatt     (501) staff       (20)        0 2023-06-28 13:26:02.072323 sweetpea-0.2.7/sweetpea/_internal/core/generate/
+-rw-r--r--   0 mflatt     (501) staff       (20)      691 2022-10-03 06:13:08.000000 sweetpea-0.2.7/sweetpea/_internal/core/generate/__init__.py
+-rw-r--r--   0 mflatt     (501) staff       (20)      567 2022-10-03 06:13:08.000000 sweetpea-0.2.7/sweetpea/_internal/core/generate/is_satisfiable.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     2620 2022-12-01 02:32:09.000000 sweetpea-0.2.7/sweetpea/_internal/core/generate/sample_ilp.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     4189 2022-10-03 06:13:08.000000 sweetpea-0.2.7/sweetpea/_internal/core/generate/sample_non_uniform.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     2061 2022-10-03 06:13:08.000000 sweetpea-0.2.7/sweetpea/_internal/core/generate/sample_uniform.py
+drwxr-xr-x   0 mflatt     (501) staff       (20)        0 2023-06-28 13:26:02.073403 sweetpea-0.2.7/sweetpea/_internal/core/generate/tools/
+-rw-r--r--   0 mflatt     (501) staff       (20)      103 2022-10-03 06:13:08.000000 sweetpea-0.2.7/sweetpea/_internal/core/generate/tools/__init__.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     4907 2022-10-03 06:13:08.000000 sweetpea-0.2.7/sweetpea/_internal/core/generate/tools/cryptominisat.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     2469 2022-10-03 06:13:08.000000 sweetpea-0.2.7/sweetpea/_internal/core/generate/tools/docker_utility.py
+-rw-r--r--   0 mflatt     (501) staff       (20)    14831 2022-10-03 06:13:08.000000 sweetpea-0.2.7/sweetpea/_internal/core/generate/tools/executables.py
+-rw-r--r--   0 mflatt     (501) staff       (20)      660 2022-10-03 06:13:08.000000 sweetpea-0.2.7/sweetpea/_internal/core/generate/tools/return_code.py
+-rw-r--r--   0 mflatt     (501) staff       (20)      555 2022-10-03 06:13:08.000000 sweetpea-0.2.7/sweetpea/_internal/core/generate/tools/tool_error.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     4305 2022-11-15 05:22:44.000000 sweetpea-0.2.7/sweetpea/_internal/core/generate/tools/unigen.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     7111 2022-11-30 23:55:59.000000 sweetpea-0.2.7/sweetpea/_internal/core/generate/utility.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     4641 2022-10-03 06:13:08.000000 sweetpea-0.2.7/sweetpea/_internal/core/simple_sequence.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     4380 2022-10-03 06:13:08.000000 sweetpea-0.2.7/sweetpea/_internal/core/tests.py
+-rw-r--r--   0 mflatt     (501) staff       (20)    25601 2023-02-09 04:40:37.000000 sweetpea-0.2.7/sweetpea/_internal/cross_block.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     8113 2022-12-05 02:16:56.000000 sweetpea-0.2.7/sweetpea/_internal/derivation_processor.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     1468 2022-12-02 01:52:33.000000 sweetpea-0.2.7/sweetpea/_internal/design_graph.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     3011 2023-01-09 05:00:49.000000 sweetpea-0.2.7/sweetpea/_internal/design_partition.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     4296 2022-12-02 03:04:51.000000 sweetpea-0.2.7/sweetpea/_internal/encoding_diagram.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     1762 2022-12-03 09:33:05.000000 sweetpea-0.2.7/sweetpea/_internal/iter.py
+-rw-r--r--   0 mflatt     (501) staff       (20)      491 2022-12-02 01:52:08.000000 sweetpea-0.2.7/sweetpea/_internal/level.py
+-rw-r--r--   0 mflatt     (501) staff       (20)    12643 2022-10-03 06:13:08.000000 sweetpea-0.2.7/sweetpea/_internal/logic.py
+-rw-r--r--   0 mflatt     (501) staff       (20)    21225 2023-06-28 12:50:19.000000 sweetpea-0.2.7/sweetpea/_internal/main.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     1103 2022-12-02 03:17:57.000000 sweetpea-0.2.7/sweetpea/_internal/metrics.py
+-rw-r--r--   0 mflatt     (501) staff       (20)    34428 2023-02-04 08:32:16.000000 sweetpea-0.2.7/sweetpea/_internal/primitive.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     1408 2023-02-04 08:32:16.000000 sweetpea-0.2.7/sweetpea/_internal/sample_conversion.py
+drwxr-xr-x   0 mflatt     (501) staff       (20)        0 2023-06-28 13:26:02.076158 sweetpea-0.2.7/sweetpea/_internal/sampling_strategy/
+-rw-r--r--   0 mflatt     (501) staff       (20)        0 2022-10-03 05:49:02.000000 sweetpea-0.2.7/sweetpea/_internal/sampling_strategy/__init__.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     3364 2022-12-02 01:42:23.000000 sweetpea-0.2.7/sweetpea/_internal/sampling_strategy/base.py
+-rw-r--r--   0 mflatt     (501) staff       (20)      789 2022-12-03 09:33:05.000000 sweetpea-0.2.7/sweetpea/_internal/sampling_strategy/cmsgen.py
+-rw-r--r--   0 mflatt     (501) staff       (20)    10000 2022-12-02 03:09:39.000000 sweetpea-0.2.7/sweetpea/_internal/sampling_strategy/guided.py
+-rw-r--r--   0 mflatt     (501) staff       (20)      819 2022-12-03 09:33:05.000000 sweetpea-0.2.7/sweetpea/_internal/sampling_strategy/iterate.py
+-rw-r--r--   0 mflatt     (501) staff       (20)      968 2022-12-03 09:33:05.000000 sweetpea-0.2.7/sweetpea/_internal/sampling_strategy/iterate_ilp.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     1147 2022-12-03 09:33:05.000000 sweetpea-0.2.7/sweetpea/_internal/sampling_strategy/iterate_sat.py
+-rw-r--r--   0 mflatt     (501) staff       (20)    34094 2023-02-09 04:40:37.000000 sweetpea-0.2.7/sweetpea/_internal/sampling_strategy/random.py
+-rw-r--r--   0 mflatt     (501) staff       (20)      815 2022-12-03 09:33:05.000000 sweetpea-0.2.7/sweetpea/_internal/sampling_strategy/uniform.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     1143 2022-12-03 09:33:05.000000 sweetpea-0.2.7/sweetpea/_internal/sampling_strategy/unigen.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     1186 2022-12-02 02:00:06.000000 sweetpea-0.2.7/sweetpea/_internal/server.py
+-rw-r--r--   0 mflatt     (501) staff       (20)      199 2022-12-02 01:52:57.000000 sweetpea-0.2.7/sweetpea/_internal/weight.py
+drwxr-xr-x   0 mflatt     (501) staff       (20)        0 2023-06-28 13:26:02.079787 sweetpea-0.2.7/sweetpea/tests/
+-rw-r--r--   0 mflatt     (501) staff       (20)        0 2022-10-03 06:13:08.000000 sweetpea-0.2.7/sweetpea/tests/__init__.py
+drwxr-xr-x   0 mflatt     (501) staff       (20)        0 2023-06-28 13:26:02.081041 sweetpea-0.2.7/sweetpea/tests/sampling_strategies/
+-rw-r--r--   0 mflatt     (501) staff       (20)        0 2021-02-05 00:23:41.000000 sweetpea-0.2.7/sweetpea/tests/sampling_strategies/__init__.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     5386 2022-12-03 09:33:05.000000 sweetpea-0.2.7/sweetpea/tests/sampling_strategies/test_base_strategy.py
+-rw-r--r--   0 mflatt     (501) staff       (20)      291 2022-12-02 03:10:03.000000 sweetpea-0.2.7/sweetpea/tests/sampling_strategies/test_guided.py
+-rw-r--r--   0 mflatt     (501) staff       (20)    10529 2022-12-02 03:11:55.000000 sweetpea-0.2.7/sweetpea/tests/sampling_strategies/test_uc_solution_enumerator.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     5406 2023-02-09 04:40:37.000000 sweetpea-0.2.7/sweetpea/tests/sampling_strategies/test_uniform_combinatoric.py
+-rw-r--r--   0 mflatt     (501) staff       (20)      542 2022-12-02 02:44:42.000000 sweetpea-0.2.7/sweetpea/tests/test_backend.py
+-rw-r--r--   0 mflatt     (501) staff       (20)    22786 2023-02-09 04:40:37.000000 sweetpea-0.2.7/sweetpea/tests/test_blocks.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     7228 2022-12-02 03:05:24.000000 sweetpea-0.2.7/sweetpea/tests/test_combinatorics.py
+-rw-r--r--   0 mflatt     (501) staff       (20)    29016 2023-02-09 04:40:37.000000 sweetpea-0.2.7/sweetpea/tests/test_constraints.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     4783 2022-12-02 03:03:23.000000 sweetpea-0.2.7/sweetpea/tests/test_constraints_tss.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     8864 2022-12-03 09:33:05.000000 sweetpea-0.2.7/sweetpea/tests/test_derivation_processor.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     2444 2022-12-03 09:33:05.000000 sweetpea-0.2.7/sweetpea/tests/test_derivation_processor_multi_argument_transition.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     2602 2022-12-03 09:33:05.000000 sweetpea-0.2.7/sweetpea/tests/test_derivation_processor_tss.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     1983 2022-12-03 09:33:05.000000 sweetpea-0.2.7/sweetpea/tests/test_design_graph.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     1804 2022-12-02 02:52:24.000000 sweetpea-0.2.7/sweetpea/tests/test_design_partitions.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     7804 2022-12-03 09:33:05.000000 sweetpea-0.2.7/sweetpea/tests/test_encoding_diagram.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     1550 2022-12-03 09:33:05.000000 sweetpea-0.2.7/sweetpea/tests/test_internal.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     9902 2022-12-02 02:53:10.000000 sweetpea-0.2.7/sweetpea/tests/test_logic.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     8858 2022-11-08 23:49:27.000000 sweetpea-0.2.7/sweetpea/tests/test_primitives.py
+-rw-r--r--   0 mflatt     (501) staff       (20)     1116 2022-12-02 03:07:13.000000 sweetpea-0.2.7/sweetpea/tests/test_sweetpea.py
+drwxr-xr-x   0 mflatt     (501) staff       (20)        0 2023-06-28 13:26:02.063470 sweetpea-0.2.7/sweetpea.egg-info/
+-rw-r--r--   0 mflatt     (501) staff       (20)     6102 2023-06-28 13:26:02.000000 sweetpea-0.2.7/sweetpea.egg-info/PKG-INFO
+-rw-r--r--   0 mflatt     (501) staff       (20)     4009 2023-06-28 13:26:02.000000 sweetpea-0.2.7/sweetpea.egg-info/SOURCES.txt
+-rw-r--r--   0 mflatt     (501) staff       (20)        1 2023-06-28 13:26:02.000000 sweetpea-0.2.7/sweetpea.egg-info/dependency_links.txt
+-rw-r--r--   0 mflatt     (501) staff       (20)       61 2023-06-28 13:26:02.000000 sweetpea-0.2.7/sweetpea.egg-info/requires.txt
+-rw-r--r--   0 mflatt     (501) staff       (20)       20 2023-06-28 13:26:02.000000 sweetpea-0.2.7/sweetpea.egg-info/top_level.txt
```

### Comparing `sweetpea-0.2.6/PKG-INFO` & `sweetpea-0.2.7/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: sweetpea
-Version: 0.2.6
+Version: 0.2.7
 Summary: A language for synthesizing randomized experimental designs
 Home-page: https://github.com/sweetpea-org/sweetpea-py
 Author: Annie Cherkaev, Ben Draut, Ahsan Sajjad Butt, Pierce Darragh, Matthew Flatt
 Author-email: annie.cherk@gmail.com, drautb@cs.utah.edu, ahsansbutt@hotmail.com, pierce.darragh@gmail.com, mflatt@cs.utah.edu
 License: UNKNOWN
 Description: SweetPea
         ========
```

### Comparing `sweetpea-0.2.6/README.md` & `sweetpea-0.2.7/README.md`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/acceptance/__init__.py` & `sweetpea-0.2.7/acceptance/__init__.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/acceptance/conftest.py` & `sweetpea-0.2.7/acceptance/conftest.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/acceptance/test_crossed_derived_via_rejection.py` & `sweetpea-0.2.7/acceptance/test_crossed_derived_via_rejection.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/acceptance/test_exhaust_combinatoric.py` & `sweetpea-0.2.7/acceptance/test_exhaust_combinatoric.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/acceptance/test_general_window.py` & `sweetpea-0.2.7/acceptance/test_general_window.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/acceptance/test_guided_sampling.py` & `sweetpea-0.2.7/acceptance/test_guided_sampling.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/acceptance/test_implied.py` & `sweetpea-0.2.7/acceptance/test_implied.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/acceptance/test_k_constraint.py` & `sweetpea-0.2.7/acceptance/test_k_constraint.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/acceptance/test_minimum_trials.py` & `sweetpea-0.2.7/acceptance/test_minimum_trials.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/acceptance/test_multiple_cross.py` & `sweetpea-0.2.7/acceptance/test_multiple_cross.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/acceptance/test_pin.py` & `sweetpea-0.2.7/acceptance/test_pin.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/acceptance/test_reduced_crossing_with_exclude.py` & `sweetpea-0.2.7/acceptance/test_reduced_crossing_with_exclude.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/acceptance/test_sample_check.py` & `sweetpea-0.2.7/acceptance/test_sample_check.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/acceptance/test_server.py` & `sweetpea-0.2.7/acceptance/test_server.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/acceptance/test_stroop.py` & `sweetpea-0.2.7/acceptance/test_stroop.py`

 * *Files 21% similar despite different names*

```diff
@@ -3,14 +3,15 @@
 
 from itertools import permutations
 
 from sweetpea import Factor, DerivedLevel, WithinTrial, Transition
 from sweetpea import AtMostKInARow, ExactlyKInARow, Exclude
 from sweetpea import IterateGen
 from sweetpea import CrossBlock, synthesize_trials, synthesize_trials
+from sweetpea import experiments_to_dicts, experiments_to_tuples
 
 # Basic setup
 color_list = ["red", "blue"]
 color = Factor("color", color_list)
 text  = Factor("text",  color_list)
 
 # Congruent Factor
@@ -37,14 +38,39 @@
     constraints = []
 
     block  = CrossBlock(design, crossing, constraints)
     experiments  = synthesize_trials(block, 100, IterateGen)
 
     assert len(experiments) == 24
 
+@pytest.mark.parametrize('design', permutations([color, text]))
+def test_conversion_to_tuples_and_dicts(design):
+    crossing = [color, text]
+    constraints = []
+
+    block  = CrossBlock(design, crossing, constraints)
+    experiments  = synthesize_trials(block, 100, IterateGen)
+
+    dicts = experiments_to_dicts(block, experiments)
+    tuples = experiments_to_tuples(block, experiments)
+
+    assert len(dicts) == 24
+    assert len(tuples) == 24
+
+    assert isinstance(dicts[0], list)
+    assert isinstance(tuples[0], list)
+
+    assert len(dicts[0]) == 4
+    assert len(tuples[0]) == 4
+
+    assert isinstance(dicts[0][0], dict)
+    assert isinstance(tuples[0][0], tuple)
+
+    assert dicts[0][0]["color"] == "red" or dicts[0][0]["color"] == "blue"
+    assert tuples[0][0][0] == "red" or tuples[0][0][0] == "blue"
 
 @pytest.mark.parametrize('design', permutations([color, text, con_factor]))
 def test_correct_solution_count_with_congruence_factor_but_unconstrained(design):
     crossing = [color, text]
     constraints = []
 
     block  = CrossBlock(design, crossing, constraints)
```

### Comparing `sweetpea-0.2.6/acceptance/test_stroop_crossing_with_derived.py` & `sweetpea-0.2.7/acceptance/test_stroop_crossing_with_derived.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/acceptance/test_task_switching_simple.py` & `sweetpea-0.2.7/acceptance/test_task_switching_simple.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/acceptance/test_transition_with_three_levels.py` & `sweetpea-0.2.7/acceptance/test_transition_with_three_levels.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/acceptance/test_uniform_combinatoric.py` & `sweetpea-0.2.7/acceptance/test_uniform_combinatoric.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/acceptance/test_weights.py` & `sweetpea-0.2.7/acceptance/test_weights.py`

 * *Files 0% similar despite different names*

```diff
@@ -59,15 +59,15 @@
 
     constraints = [MinimumTrials(4)]
     
     design       = [color, size, look]
     crossing     = [look]
 
     check_consistent_solutions(CrossBlock(design, crossing, []), 9)
-    check_consistent_solutions(Repeat(CrossBlock(design, crossing, [], constraints)), 36)
+    check_consistent_solutions(Repeat(CrossBlock(design, crossing, []), constraints), 36)
 
 def test_correct_solutions_with_transition_level_weight():
     color = Factor("color",  ["red", "blue"])
     size = Factor("size",  ["big", "small"])
 
     look = Factor("look",
                   [DerivedLevel("bolden",
```

### Comparing `sweetpea-0.2.6/acceptance/test_window_start.py` & `sweetpea-0.2.7/acceptance/test_window_start.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/setup.py` & `sweetpea-0.2.7/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import setuptools
 
 with open("README.md", "r") as fh:
     long_description = fh.read()
 
 setuptools.setup(
     name="sweetpea",
-    version="0.2.6",
+    version="0.2.7",
     author="Annie Cherkaev, Ben Draut, Ahsan Sajjad Butt, Pierce Darragh, Matthew Flatt",
     author_email="annie.cherk@gmail.com, drautb@cs.utah.edu, ahsansbutt@hotmail.com, pierce.darragh@gmail.com, mflatt@cs.utah.edu",
     description="A language for synthesizing randomized experimental designs",
     long_description=long_description,
     long_description_content_type="text/markdown",
     url="https://github.com/sweetpea-org/sweetpea-py",
     packages=setuptools.find_packages(),
```

### Comparing `sweetpea-0.2.6/sweetpea/_internal/argcheck.py` & `sweetpea-0.2.7/sweetpea/_internal/argcheck.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/backend.py` & `sweetpea-0.2.7/sweetpea/_internal/backend.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/base_constraint.py` & `sweetpea-0.2.7/sweetpea/_internal/base_constraint.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/block.py` & `sweetpea-0.2.7/sweetpea/_internal/block.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/check_mismatch.py` & `sweetpea-0.2.7/sweetpea/_internal/check_mismatch.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/combinatorics.py` & `sweetpea-0.2.7/sweetpea/_internal/combinatorics.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/constraint.py` & `sweetpea-0.2.7/sweetpea/_internal/constraint.py`

 * *Files 0% similar despite different names*

```diff
@@ -717,20 +717,20 @@
 
     def is_complex_for_combinatoric(self) -> bool:
         return False
 
     def potential_sample_conforms(self, sample: dict, block: Block) -> bool:
         # conformance by construction in combinatoric for simple factors, but
         # we have to check exlcusions based on complex factors
-        if self.factor.has_complex_window:
-            levels = sample[self.factor]
-            level = self.level
-            for l in levels:
-                if l == level:
-                    return False
+        #if self.factor.has_complex_window:
+        levels = sample[self.factor]
+        level = self.level
+        for l in levels:
+            if l == level:
+                return False
         return True
 
 class Pin(Constraint):
     def __init__(self, index, level):
         level = filter_level("Pin", level)
         self.index = index
         self.factor = level.factor
```

### Comparing `sweetpea-0.2.6/sweetpea/_internal/core/__init__.py` & `sweetpea-0.2.7/sweetpea/_internal/core/__init__.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/core/binary.py` & `sweetpea-0.2.7/sweetpea/_internal/core/binary.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/core/cnf.py` & `sweetpea-0.2.7/sweetpea/_internal/core/cnf.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/core/generate/__init__.py` & `sweetpea-0.2.7/sweetpea/_internal/core/generate/__init__.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/core/generate/is_satisfiable.py` & `sweetpea-0.2.7/sweetpea/_internal/core/generate/is_satisfiable.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/core/generate/sample_ilp.py` & `sweetpea-0.2.7/sweetpea/_internal/core/generate/sample_ilp.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/core/generate/sample_non_uniform.py` & `sweetpea-0.2.7/sweetpea/_internal/core/generate/sample_non_uniform.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/core/generate/sample_uniform.py` & `sweetpea-0.2.7/sweetpea/_internal/core/generate/sample_uniform.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/core/generate/tools/cryptominisat.py` & `sweetpea-0.2.7/sweetpea/_internal/core/generate/tools/cryptominisat.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/core/generate/tools/docker_utility.py` & `sweetpea-0.2.7/sweetpea/_internal/core/generate/tools/docker_utility.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/core/generate/tools/executables.py` & `sweetpea-0.2.7/sweetpea/_internal/core/generate/tools/executables.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/core/generate/tools/return_code.py` & `sweetpea-0.2.7/sweetpea/_internal/core/generate/tools/return_code.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/core/generate/tools/tool_error.py` & `sweetpea-0.2.7/sweetpea/_internal/core/generate/tools/tool_error.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/core/generate/tools/unigen.py` & `sweetpea-0.2.7/sweetpea/_internal/core/generate/tools/unigen.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/core/generate/utility.py` & `sweetpea-0.2.7/sweetpea/_internal/core/generate/utility.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/core/simple_sequence.py` & `sweetpea-0.2.7/sweetpea/_internal/core/simple_sequence.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/core/tests.py` & `sweetpea-0.2.7/sweetpea/_internal/core/tests.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/cross_block.py` & `sweetpea-0.2.7/sweetpea/_internal/cross_block.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/derivation_processor.py` & `sweetpea-0.2.7/sweetpea/_internal/derivation_processor.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/design_graph.py` & `sweetpea-0.2.7/sweetpea/_internal/design_graph.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/design_partition.py` & `sweetpea-0.2.7/sweetpea/_internal/design_partition.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/encoding_diagram.py` & `sweetpea-0.2.7/sweetpea/_internal/encoding_diagram.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/iter.py` & `sweetpea-0.2.7/sweetpea/_internal/iter.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/logic.py` & `sweetpea-0.2.7/sweetpea/_internal/logic.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/main.py` & `sweetpea-0.2.7/sweetpea/_internal/main.py`

 * *Files 15% similar despite different names*

```diff
@@ -1,14 +1,16 @@
 # Everything in `__all_` is exported from the `sweetpea` module.
 
 __all__ = [
     'synthesize_trials', 'sample_mismatch_experiment',
 
+    'auto_correlation_scores_sample_within', 'auto_correlation_scores_samples_between',
+
     'print_experiments', 'tabulate_experiments',
-    'save_experiments_csv', 'experiments_to_tuples',
+    'save_experiments_csv', 'experiments_to_tuples', 'experiments_to_dicts',
 
     'Block', 'CrossBlock', 'MultiCrossBlock', 'Repeat',
 
     'Factor', 'Level', 'DerivedLevel', 'ElseLevel',
 
     'Derivation', 'WithinTrial', 'Transition', 'Window',
 
@@ -47,48 +49,85 @@
 from sweetpea._internal.sampling_strategy.cmsgen import CMSGen
 from sweetpea._internal.sampling_strategy.random import RandomGen
 from sweetpea._internal.sampling_strategy.iterate_ilp import IterateILPGen
 from sweetpea._internal.server import build_cnf
 from sweetpea._internal.core.cnf import Var
 from sweetpea._internal.argcheck import argcheck, make_islistof
 
+from sweetpea._internal.auto_correlation_score import (auto_correlation_score_factor_within,
+                                                       auto_correlation_score_factor_between)
+
 
 # ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 # ~~~~~~~~~~~~~ Top-Level functions ~~~~~~~~~~~~~~~~~~~~~
 # ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 
 def _experiments_to_tuples(experiments: List[dict],
                            keys: List[str]):
-    """Converts a list of experiments into a list of lists of tuples, where
-    each tuple represents a crossing in a given experiment.
+    tuple_lists: List[List[Tuple[Any, ...]]] = []
+    for experiment in experiments:
+        tuple_lists.append(list(zip(*[experiment[key] for key in keys])))
+    return tuple_lists
+
+def _experiments_to_dicts(experiments: List[dict],
+                           keys: List[str]):
+    tuple_lists: List[List[Dict[str, Any]]] = []
+    for experiment in experiments:
+        tuple_lists.append([dict(zip(keys, values)) for values in zip(*[experiment[key] for key in keys])])
+    return tuple_lists
+
+def simplify_experiments(experiments: List[dict]) -> List[List[tuple]]:
+    """Like experiments_to_tuples, but without a block argument
+    (for backward compatibility), so the factor names are inferred from the
+    experiments.
+    """
+    return _experiments_to_tuples(experiments, list(experiments[0].keys()))
+
+def simplify_experiments_to_dicts(experiments: List[dict]) -> List[List[dict]]:
+    """Like experiments_to_tuples, but without a block argument,
+    so the factor names are inferred from the experiments.
+    """
+    return _experiments_to_dicts(experiments, list(experiments[0].keys()))
+
+def experiments_to_dicts(block: Block, experiments: List[dict]) -> List[List[dict]]:
+    """Converts a list of experiments into a list of lists of dictionaries, where
+    each dictionary represents a crossing in a given experiment.
+
+    :param block:
+        An experimental description as a :class:`.Block`.
 
     :param experiments:
         A list of experiments as :class:`dicts <dict>`. These are produced by
         calls to the synthesis function :func:`.synthesize_trials`.
 
     :returns:
-        A list of lists of tuples of strings, where each sub-list corresponds
-        to one of the ``experiments``, each tuple corresponds to a particular
+        A list of lists of dictionaries, where each sub-list corresponds
+        to one of the ``experiments``, each dictionary corresponds to a particular
         crossing, and each string is the simple surface name of a level.
     """
-    tuple_lists: List[List[Tuple[str, ...]]] = []
-    for experiment in experiments:
-        tuple_lists.append(list(zip(*[experiment[key] for key in keys])))
-    return tuple_lists
+    return _experiments_to_dicts(experiments, [cast(str, f.name) for f in __filter_hidden(block.design)])
 
+def experiments_to_tuples(block: Block, experiments: List[dict]) -> List[List[tuple]]:
+    """Converts a list of experiments into a list of lists of tuples, where
+    each tuple represents a crossing in a given experiment.
 
-def simplify_experiments(experiments: List[Dict]) -> List[List[Tuple[str, ...]]]:
-    return _experiments_to_tuples(experiments, list(experiments[0].keys()))
+    :param block:
+        An experimental description as a :class:`.Block`.
 
+    :param experiments:
+        A list of experiments as :class:`dicts <dict>`. These are produced by
+        calls to the synthesis function :func:`.synthesize_trials`.
 
-def experiments_to_tuples(block: Block,
-                          experiments: List[dict]):
+    :returns:
+        A list of lists of tuples of strings, where each sub-list corresponds
+        to one of the ``experiments``, each tuple corresponds to a particular
+        crossing, and each string is the simple surface name of a level.
+    """
     return _experiments_to_tuples(experiments, [cast(str, f.name) for f in __filter_hidden(block.design)])
 
-
 def __filter_hidden(design: List[Factor]) -> List[Factor]:
     return list(filter(lambda f: not isinstance(f.name, HiddenName), design))
 
 
 def __filter_hidden_keys(d: dict) -> dict:
     return {name: d[name] for name in filter(lambda name: not isinstance(name, HiddenName), d.keys())}
 
@@ -358,14 +397,81 @@
             res['constraints'] = constraint_errors
         crossing_errors = block.sample_mismatch_crossing(sample)
         if crossing_errors:
             res['crossings'] = crossing_errors
     return res
 
 
+def auto_correlation_scores_samples_between(samples: list, factor_names: List[str] = [],
+                                            number_trials: int = 10, starts: int = 10) -> dict:
+    """Given a number of samples given as :class:`list` of trial sets, calculates
+    a auto correlation score representing if a level can be predicted from the k
+    proceeding levels. This is done by creating a neural network that is trained on
+    predicting a factor based on the levels in all factors of the preceding trials.
+    The number of preceding trials taken into account is the minimum between number_trials
+    and half the sequence length.
+
+
+    :param samples:
+        A :class:`list` of trial sets. Each set is represented as a :class:`dictionary <dict>`
+        mapping each factor name to a list of levels, where each such list contains
+        to one level per trial.
+    :param factor_names:
+        A :class`list` of string. The factors to be tested (if None, all factors in samples are tested)
+    :param number_trials:
+        A :class int that indicates how many trials before the predicted trial to use for the prediction
+    :param starts:
+        A :class int that indicates how many times a new neural network is created. The final score is the
+        max prediction score of theses networks.
+    :returns:
+        A :class:`dict` describing the auto correlation of each factor.
+    """
+    res = {}
+    if not factor_names:
+        for f in samples[0].keys():
+            res[f] = auto_correlation_score_factor_between(samples, f, k=number_trials, starts=starts)
+    else:
+        for f in factor_names:
+            res[f] = auto_correlation_score_factor_between(samples, f, k=number_trials, starts=starts)
+    return res
+
+
+def auto_correlation_scores_sample_within(sample: dict, factor_names: List[str] = [],
+                                          number_trials: int = 10, starts: int = 10) -> dict:
+    """Given a samples given as :class:`dict` of a trial set, calculates
+    a auto correlation score representing if a level can be predicted from the k
+    proceeding levels. This is done by creating a neural network that is trained on
+    predicting a factor based on the levels in all factors of the preceding trials.
+    The number of preceding trials taken into account is the minimum between number_trials
+    and half the sequence length.
+
+
+    :param sample:
+        A :class:`dict` mapping each factor name to a list of levels, where each such list contains
+        to one level per trial.
+    :param factor_names:
+        A :class`list` of string. The factors to be tested (if None, all factors in samples are tested)
+    :param number_trials:
+        A :class int that indicates how many trials before the predicted trial to use for the prediction
+    :param starts:
+        A :class int that indicates how many times a new neural network is created. The final score is the
+        max prediction score of theses networks.
+    :returns:
+        A :class:`dict` describing the auto correlation of each factor.
+    """
+    res = {}
+    if not factor_names:
+        for f in sample.keys():
+            res[f] = auto_correlation_score_factor_within(sample, f, k=number_trials, starts=starts)
+    else:
+        for f in factor_names:
+            res[f] = auto_correlation_score_factor_within(sample, f, k=number_trials, starts=starts)
+    return res
+
+
 # TODO: This function isn't called anywhere, so it should be removed.
 def save_cnf(block: Block, filename: str):
     """Generates a CNF formula from a :class:`.Block` and then writes that CNF
     formula to the indicated file in the Unigen-specific DIMACS format.
 
     :param block:
         A description of a CNF formula as a :class:`.Block`.
```

### Comparing `sweetpea-0.2.6/sweetpea/_internal/metrics.py` & `sweetpea-0.2.7/sweetpea/_internal/metrics.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/primitive.py` & `sweetpea-0.2.7/sweetpea/_internal/primitive.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/sample_conversion.py` & `sweetpea-0.2.7/sweetpea/_internal/sample_conversion.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/sampling_strategy/base.py` & `sweetpea-0.2.7/sweetpea/_internal/sampling_strategy/base.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/sampling_strategy/cmsgen.py` & `sweetpea-0.2.7/sweetpea/_internal/sampling_strategy/cmsgen.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/sampling_strategy/guided.py` & `sweetpea-0.2.7/sweetpea/_internal/sampling_strategy/guided.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/sampling_strategy/iterate.py` & `sweetpea-0.2.7/sweetpea/_internal/sampling_strategy/iterate.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/sampling_strategy/iterate_ilp.py` & `sweetpea-0.2.7/sweetpea/_internal/sampling_strategy/iterate_ilp.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/sampling_strategy/iterate_sat.py` & `sweetpea-0.2.7/sweetpea/_internal/sampling_strategy/iterate_sat.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/sampling_strategy/random.py` & `sweetpea-0.2.7/sweetpea/_internal/sampling_strategy/random.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/sampling_strategy/uniform.py` & `sweetpea-0.2.7/sweetpea/_internal/sampling_strategy/uniform.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/sampling_strategy/unigen.py` & `sweetpea-0.2.7/sweetpea/_internal/sampling_strategy/unigen.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/_internal/server.py` & `sweetpea-0.2.7/sweetpea/_internal/server.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/tests/sampling_strategies/test_base_strategy.py` & `sweetpea-0.2.7/sweetpea/tests/sampling_strategies/test_base_strategy.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/tests/sampling_strategies/test_uc_solution_enumerator.py` & `sweetpea-0.2.7/sweetpea/tests/sampling_strategies/test_uc_solution_enumerator.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/tests/sampling_strategies/test_uniform_combinatoric.py` & `sweetpea-0.2.7/sweetpea/tests/sampling_strategies/test_uniform_combinatoric.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/tests/test_backend.py` & `sweetpea-0.2.7/sweetpea/tests/test_backend.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/tests/test_blocks.py` & `sweetpea-0.2.7/sweetpea/tests/test_blocks.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/tests/test_combinatorics.py` & `sweetpea-0.2.7/sweetpea/tests/test_combinatorics.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/tests/test_constraints.py` & `sweetpea-0.2.7/sweetpea/tests/test_constraints.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/tests/test_constraints_tss.py` & `sweetpea-0.2.7/sweetpea/tests/test_constraints_tss.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/tests/test_derivation_processor.py` & `sweetpea-0.2.7/sweetpea/tests/test_derivation_processor.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/tests/test_derivation_processor_multi_argument_transition.py` & `sweetpea-0.2.7/sweetpea/tests/test_derivation_processor_multi_argument_transition.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/tests/test_derivation_processor_tss.py` & `sweetpea-0.2.7/sweetpea/tests/test_derivation_processor_tss.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/tests/test_design_graph.py` & `sweetpea-0.2.7/sweetpea/tests/test_design_graph.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/tests/test_design_partitions.py` & `sweetpea-0.2.7/sweetpea/tests/test_design_partitions.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/tests/test_encoding_diagram.py` & `sweetpea-0.2.7/sweetpea/tests/test_encoding_diagram.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/tests/test_internal.py` & `sweetpea-0.2.7/sweetpea/tests/test_internal.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/tests/test_logic.py` & `sweetpea-0.2.7/sweetpea/tests/test_logic.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/tests/test_primitives.py` & `sweetpea-0.2.7/sweetpea/tests/test_primitives.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea/tests/test_sweetpea.py` & `sweetpea-0.2.7/sweetpea/tests/test_sweetpea.py`

 * *Files identical despite different names*

### Comparing `sweetpea-0.2.6/sweetpea.egg-info/PKG-INFO` & `sweetpea-0.2.7/sweetpea.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: sweetpea
-Version: 0.2.6
+Version: 0.2.7
 Summary: A language for synthesizing randomized experimental designs
 Home-page: https://github.com/sweetpea-org/sweetpea-py
 Author: Annie Cherkaev, Ben Draut, Ahsan Sajjad Butt, Pierce Darragh, Matthew Flatt
 Author-email: annie.cherk@gmail.com, drautb@cs.utah.edu, ahsansbutt@hotmail.com, pierce.darragh@gmail.com, mflatt@cs.utah.edu
 License: UNKNOWN
 Description: SweetPea
         ========
```

### Comparing `sweetpea-0.2.6/sweetpea.egg-info/SOURCES.txt` & `sweetpea-0.2.7/sweetpea.egg-info/SOURCES.txt`

 * *Files 6% similar despite different names*

```diff
@@ -1,18 +1,20 @@
 README.md
 setup.py
 acceptance/__init__.py
 acceptance/conftest.py
+acceptance/test_auto_correlation_score.py
 acceptance/test_crossed_derived_via_rejection.py
 acceptance/test_exhaust_combinatoric.py
 acceptance/test_general_window.py
 acceptance/test_guided_sampling.py
 acceptance/test_implied.py
 acceptance/test_k_constraint.py
 acceptance/test_minimum_trials.py
+acceptance/test_mismatch.py
 acceptance/test_multiple_cross.py
 acceptance/test_pin.py
 acceptance/test_reduced_crossing_with_exclude.py
 acceptance/test_sample_check.py
 acceptance/test_server.py
 acceptance/test_stroop.py
 acceptance/test_stroop_crossing_with_derived.py
@@ -25,14 +27,15 @@
 sweetpea.egg-info/PKG-INFO
 sweetpea.egg-info/SOURCES.txt
 sweetpea.egg-info/dependency_links.txt
 sweetpea.egg-info/requires.txt
 sweetpea.egg-info/top_level.txt
 sweetpea/_internal/__init__.py
 sweetpea/_internal/argcheck.py
+sweetpea/_internal/auto_correlation_score.py
 sweetpea/_internal/backend.py
 sweetpea/_internal/base_constraint.py
 sweetpea/_internal/beforestart.py
 sweetpea/_internal/block.py
 sweetpea/_internal/check_mismatch.py
 sweetpea/_internal/combinatorics.py
 sweetpea/_internal/constraint.py
```


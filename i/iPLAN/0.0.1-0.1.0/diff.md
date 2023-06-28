# Comparing `tmp/iPLAN-0.0.1.tar.gz` & `tmp/iPLAN-0.1.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist\iPLAN-0.0.1.tar", last modified: Tue Jun 27 19:32:55 2023, max compression
+gzip compressed data, was "dist\iPLAN-0.1.0.tar", last modified: Wed Jun 28 02:53:32 2023, max compression
```

## Comparing `iPLAN-0.0.1.tar` & `iPLAN-0.1.0.tar`

### file list

```diff
@@ -1,76 +1,38 @@
-drwxrwxrwx   0        0        0        0 2023-06-27 19:32:55.000000 iPLAN-0.0.1/
--rw-rw-rw-   0        0        0     1062 2023-06-27 19:32:36.000000 iPLAN-0.0.1/LICENSE
--rw-rw-rw-   0        0        0     7734 2023-06-27 19:32:55.000000 iPLAN-0.0.1/PKG-INFO
-drwxrwxrwx   0        0        0        0 2023-06-27 19:32:55.000000 iPLAN-0.0.1/components/
--rw-rw-rw-   0        0        0        0 2023-05-17 01:23:16.000000 iPLAN-0.0.1/components/__init__.py
--rw-rw-rw-   0        0        0     2420 2023-05-17 01:23:16.000000 iPLAN-0.0.1/components/action_selectors.py
--rw-rw-rw-   0        0        0    10894 2023-05-17 01:23:16.000000 iPLAN-0.0.1/components/episode_buffer.py
--rw-rw-rw-   0        0        0     1757 2023-05-17 01:23:16.000000 iPLAN-0.0.1/components/epsilon_schedules.py
--rw-rw-rw-   0        0        0      568 2023-05-17 01:23:16.000000 iPLAN-0.0.1/components/transforms.py
-drwxrwxrwx   0        0        0        0 2023-06-27 19:32:55.000000 iPLAN-0.0.1/highway_env/
--rw-rw-rw-   0        0        0      168 2022-10-16 08:12:13.000000 iPLAN-0.0.1/highway_env/__init__.py
-drwxrwxrwx   0        0        0        0 2023-06-27 19:32:55.000000 iPLAN-0.0.1/highway_env/envs/
--rw-rw-rw-   0        0        0      481 2022-10-16 08:12:13.000000 iPLAN-0.0.1/highway_env/envs/__init__.py
-drwxrwxrwx   0        0        0        0 2023-06-27 19:32:55.000000 iPLAN-0.0.1/highway_env/envs/common/
--rw-rw-rw-   0        0        0        0 2022-10-16 08:12:13.000000 iPLAN-0.0.1/highway_env/envs/common/__init__.py
--rw-rw-rw-   0        0        0    14150 2023-05-26 21:29:49.000000 iPLAN-0.0.1/highway_env/envs/common/abstract.py
--rw-rw-rw-   0        0        0    11804 2022-10-16 08:12:13.000000 iPLAN-0.0.1/highway_env/envs/common/action.py
--rw-rw-rw-   0        0        0     7579 2022-10-16 08:12:13.000000 iPLAN-0.0.1/highway_env/envs/common/finite_mdp.py
--rw-rw-rw-   0        0        0    10388 2022-10-16 08:12:13.000000 iPLAN-0.0.1/highway_env/envs/common/graphics.py
--rw-rw-rw-   0        0        0    28654 2023-04-01 18:17:39.000000 iPLAN-0.0.1/highway_env/envs/common/observation.py
--rw-rw-rw-   0        0        0     6843 2022-10-16 08:12:13.000000 iPLAN-0.0.1/highway_env/envs/exit_env.py
--rw-rw-rw-   0        0        0    38658 2023-06-09 03:50:48.000000 iPLAN-0.0.1/highway_env/envs/highway_env.py
--rw-rw-rw-   0        0        0    15174 2022-12-05 20:56:12.000000 iPLAN-0.0.1/highway_env/envs/intersection_env.py
--rw-rw-rw-   0        0        0     5764 2022-10-16 08:12:13.000000 iPLAN-0.0.1/highway_env/envs/lane_keeping_env.py
--rw-rw-rw-   0        0        0     5780 2022-10-16 08:12:13.000000 iPLAN-0.0.1/highway_env/envs/merge_env.py
--rw-rw-rw-   0        0        0     8787 2022-10-16 08:12:13.000000 iPLAN-0.0.1/highway_env/envs/parking_env.py
--rw-rw-rw-   0        0        0    10755 2022-10-16 08:12:13.000000 iPLAN-0.0.1/highway_env/envs/racetrack_env.py
--rw-rw-rw-   0        0        0     9430 2022-11-25 19:20:27.000000 iPLAN-0.0.1/highway_env/envs/roundabout_env.py
--rw-rw-rw-   0        0        0     5382 2022-10-16 08:12:13.000000 iPLAN-0.0.1/highway_env/envs/summon_env.py
--rw-rw-rw-   0        0        0     4797 2022-10-16 08:12:13.000000 iPLAN-0.0.1/highway_env/envs/two_way_env.py
--rw-rw-rw-   0        0        0     9510 2022-10-16 08:12:13.000000 iPLAN-0.0.1/highway_env/envs/u_turn_env.py
--rw-rw-rw-   0        0        0    12618 2022-10-16 08:12:13.000000 iPLAN-0.0.1/highway_env/interval.py
-drwxrwxrwx   0        0        0        0 2023-06-27 19:32:55.000000 iPLAN-0.0.1/highway_env/road/
--rw-rw-rw-   0        0        0        0 2022-10-16 08:12:13.000000 iPLAN-0.0.1/highway_env/road/__init__.py
--rw-rw-rw-   0        0        0    14904 2022-10-16 08:12:13.000000 iPLAN-0.0.1/highway_env/road/graphics.py
--rw-rw-rw-   0        0        0    18097 2022-10-16 08:12:13.000000 iPLAN-0.0.1/highway_env/road/lane.py
--rw-rw-rw-   0        0        0     3720 2022-10-16 08:12:13.000000 iPLAN-0.0.1/highway_env/road/regulation.py
--rw-rw-rw-   0        0        0    16679 2022-10-16 08:12:13.000000 iPLAN-0.0.1/highway_env/road/road.py
--rw-rw-rw-   0        0        0     5875 2022-10-16 08:12:13.000000 iPLAN-0.0.1/highway_env/road/spline.py
--rw-rw-rw-   0        0        0    13864 2022-10-16 08:12:13.000000 iPLAN-0.0.1/highway_env/utils.py
-drwxrwxrwx   0        0        0        0 2023-06-27 19:32:55.000000 iPLAN-0.0.1/highway_env/vehicle/
--rw-rw-rw-   0        0        0        0 2022-10-16 08:12:13.000000 iPLAN-0.0.1/highway_env/vehicle/__init__.py
--rw-rw-rw-   0        0        0    46459 2023-04-01 21:29:43.000000 iPLAN-0.0.1/highway_env/vehicle/behavior.py
--rw-rw-rw-   0        0        0    13415 2022-10-16 08:12:13.000000 iPLAN-0.0.1/highway_env/vehicle/controller.py
--rw-rw-rw-   0        0        0    10399 2023-03-25 05:37:55.000000 iPLAN-0.0.1/highway_env/vehicle/dynamics.py
--rw-rw-rw-   0        0        0     9370 2023-04-01 21:28:45.000000 iPLAN-0.0.1/highway_env/vehicle/graphics.py
--rw-rw-rw-   0        0        0     9205 2023-04-16 19:26:56.000000 iPLAN-0.0.1/highway_env/vehicle/kinematics.py
--rw-rw-rw-   0        0        0     7060 2023-04-16 19:26:56.000000 iPLAN-0.0.1/highway_env/vehicle/objects.py
-drwxrwxrwx   0        0        0        0 2023-06-27 19:32:55.000000 iPLAN-0.0.1/highway_env/vehicle/uncertainty/
--rw-rw-rw-   0        0        0        0 2022-10-16 08:12:13.000000 iPLAN-0.0.1/highway_env/vehicle/uncertainty/__init__.py
--rw-rw-rw-   0        0        0     4497 2022-10-16 08:12:13.000000 iPLAN-0.0.1/highway_env/vehicle/uncertainty/estimation.py
--rw-rw-rw-   0        0        0    19219 2022-10-16 08:12:13.000000 iPLAN-0.0.1/highway_env/vehicle/uncertainty/prediction.py
-drwxrwxrwx   0        0        0        0 2023-06-27 19:32:55.000000 iPLAN-0.0.1/iPLAN.egg-info/
--rw-rw-rw-   0        0        0     7734 2023-06-27 19:32:54.000000 iPLAN-0.0.1/iPLAN.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0     1858 2023-06-27 19:32:55.000000 iPLAN-0.0.1/iPLAN.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-27 19:32:54.000000 iPLAN-0.0.1/iPLAN.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       29 2023-06-27 19:32:54.000000 iPLAN-0.0.1/iPLAN.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-27 19:32:55.000000 iPLAN-0.0.1/setup.cfg
--rw-rw-rw-   0        0        0      738 2023-06-27 19:28:58.000000 iPLAN-0.0.1/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-27 19:32:55.000000 iPLAN-0.0.1/utils/
--rw-rw-rw-   0        0        0        0 2023-05-17 01:23:20.000000 iPLAN-0.0.1/utils/__init__.py
--rw-rw-rw-   0        0        0      132 2023-05-17 01:23:20.000000 iPLAN-0.0.1/utils/dict2namedtuple.py
--rw-rw-rw-   0        0        0     2135 2023-05-17 01:23:20.000000 iPLAN-0.0.1/utils/logging.py
-drwxrwxrwx   0        0        0        0 2023-06-27 19:32:55.000000 iPLAN-0.0.1/utils/mappo_utils/
--rw-rw-rw-   0        0        0        0 2023-05-17 01:23:20.000000 iPLAN-0.0.1/utils/mappo_utils/__init__.py
--rw-rw-rw-   0        0        0     8304 2023-05-17 01:23:20.000000 iPLAN-0.0.1/utils/mappo_utils/act.py
--rw-rw-rw-   0        0        0     3590 2023-05-17 01:23:20.000000 iPLAN-0.0.1/utils/mappo_utils/distributions.py
--rw-rw-rw-   0        0        0     1979 2023-05-17 01:23:20.000000 iPLAN-0.0.1/utils/mappo_utils/mlp.py
--rw-rw-rw-   0        0        0     3888 2023-05-17 01:23:20.000000 iPLAN-0.0.1/utils/mappo_utils/popart.py
--rw-rw-rw-   0        0        0     2910 2023-05-17 01:23:20.000000 iPLAN-0.0.1/utils/mappo_utils/rnn.py
--rw-rw-rw-   0        0        0     4505 2023-05-17 01:23:20.000000 iPLAN-0.0.1/utils/mappo_utils/separated_buffer.py
--rw-rw-rw-   0        0        0     1842 2023-05-17 01:23:20.000000 iPLAN-0.0.1/utils/mappo_utils/util.py
--rw-rw-rw-   0        0        0     3093 2023-05-17 01:23:20.000000 iPLAN-0.0.1/utils/mappo_utils/valuenorm.py
--rw-rw-rw-   0        0        0      774 2023-05-17 01:23:20.000000 iPLAN-0.0.1/utils/rl_utils.py
--rw-rw-rw-   0        0        0     1550 2023-05-17 01:23:20.000000 iPLAN-0.0.1/utils/timehelper.py
--rw-rw-rw-   0        0        0     4274 2023-05-17 01:23:20.000000 iPLAN-0.0.1/utils/vis_utils.py
+drwxrwxrwx   0        0        0        0 2023-06-28 02:53:32.000000 iPLAN-0.1.0/
+-rw-rw-rw-   0        0        0     1062 2023-06-27 19:32:36.000000 iPLAN-0.1.0/LICENSE
+-rw-rw-rw-   0        0        0     8867 2023-06-28 02:53:32.000000 iPLAN-0.1.0/PKG-INFO
+drwxrwxrwx   0        0        0        0 2023-06-28 02:53:32.000000 iPLAN-0.1.0/iPLAN/
+-rw-rw-rw-   0        0        0       14 2023-06-27 19:26:23.000000 iPLAN-0.1.0/iPLAN/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 02:53:32.000000 iPLAN-0.1.0/iPLAN/components/
+-rw-rw-rw-   0        0        0        0 2023-05-17 01:23:16.000000 iPLAN-0.1.0/iPLAN/components/__init__.py
+-rw-rw-rw-   0        0        0     2420 2023-05-17 01:23:16.000000 iPLAN-0.1.0/iPLAN/components/action_selectors.py
+-rw-rw-rw-   0        0        0    10894 2023-05-17 01:23:16.000000 iPLAN-0.1.0/iPLAN/components/episode_buffer.py
+-rw-rw-rw-   0        0        0     1757 2023-05-17 01:23:16.000000 iPLAN-0.1.0/iPLAN/components/epsilon_schedules.py
+-rw-rw-rw-   0        0        0      568 2023-05-17 01:23:16.000000 iPLAN-0.1.0/iPLAN/components/transforms.py
+-rw-rw-rw-   0        0        0     3532 2023-06-27 02:33:17.000000 iPLAN-0.1.0/iPLAN/main.py
+-rw-rw-rw-   0        0        0     7833 2023-05-17 01:23:20.000000 iPLAN-0.1.0/iPLAN/observation_wrapper.py
+-rw-rw-rw-   0        0        0    19010 2023-06-27 21:55:40.000000 iPLAN-0.1.0/iPLAN/run_ippo.py
+drwxrwxrwx   0        0        0        0 2023-06-28 02:53:32.000000 iPLAN-0.1.0/iPLAN/utils/
+-rw-rw-rw-   0        0        0        0 2023-05-17 01:23:20.000000 iPLAN-0.1.0/iPLAN/utils/__init__.py
+-rw-rw-rw-   0        0        0      132 2023-05-17 01:23:20.000000 iPLAN-0.1.0/iPLAN/utils/dict2namedtuple.py
+-rw-rw-rw-   0        0        0     2135 2023-05-17 01:23:20.000000 iPLAN-0.1.0/iPLAN/utils/logging.py
+drwxrwxrwx   0        0        0        0 2023-06-28 02:53:32.000000 iPLAN-0.1.0/iPLAN/utils/mappo_utils/
+-rw-rw-rw-   0        0        0        0 2023-05-17 01:23:20.000000 iPLAN-0.1.0/iPLAN/utils/mappo_utils/__init__.py
+-rw-rw-rw-   0        0        0     8304 2023-05-17 01:23:20.000000 iPLAN-0.1.0/iPLAN/utils/mappo_utils/act.py
+-rw-rw-rw-   0        0        0     3590 2023-05-17 01:23:20.000000 iPLAN-0.1.0/iPLAN/utils/mappo_utils/distributions.py
+-rw-rw-rw-   0        0        0     1979 2023-05-17 01:23:20.000000 iPLAN-0.1.0/iPLAN/utils/mappo_utils/mlp.py
+-rw-rw-rw-   0        0        0     3888 2023-05-17 01:23:20.000000 iPLAN-0.1.0/iPLAN/utils/mappo_utils/popart.py
+-rw-rw-rw-   0        0        0     2910 2023-05-17 01:23:20.000000 iPLAN-0.1.0/iPLAN/utils/mappo_utils/rnn.py
+-rw-rw-rw-   0        0        0     4505 2023-05-17 01:23:20.000000 iPLAN-0.1.0/iPLAN/utils/mappo_utils/separated_buffer.py
+-rw-rw-rw-   0        0        0     1842 2023-05-17 01:23:20.000000 iPLAN-0.1.0/iPLAN/utils/mappo_utils/util.py
+-rw-rw-rw-   0        0        0     3093 2023-05-17 01:23:20.000000 iPLAN-0.1.0/iPLAN/utils/mappo_utils/valuenorm.py
+-rw-rw-rw-   0        0        0      774 2023-05-17 01:23:20.000000 iPLAN-0.1.0/iPLAN/utils/rl_utils.py
+-rw-rw-rw-   0        0        0     1550 2023-05-17 01:23:20.000000 iPLAN-0.1.0/iPLAN/utils/timehelper.py
+-rw-rw-rw-   0        0        0     4274 2023-05-17 01:23:20.000000 iPLAN-0.1.0/iPLAN/utils/vis_utils.py
+drwxrwxrwx   0        0        0        0 2023-06-28 02:53:32.000000 iPLAN-0.1.0/iPLAN.egg-info/
+-rw-rw-rw-   0        0        0     8867 2023-06-28 02:53:31.000000 iPLAN-0.1.0/iPLAN.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      851 2023-06-28 02:53:32.000000 iPLAN-0.1.0/iPLAN.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 02:53:31.000000 iPLAN-0.1.0/iPLAN.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0        6 2023-06-28 02:53:31.000000 iPLAN-0.1.0/iPLAN.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 02:53:32.000000 iPLAN-0.1.0/setup.cfg
+-rw-rw-rw-   0        0        0      738 2023-06-28 02:50:24.000000 iPLAN-0.1.0/setup.py
```

### Comparing `iPLAN-0.0.1/LICENSE` & `iPLAN-0.1.0/LICENSE`

 * *Files identical despite different names*

### Comparing `iPLAN-0.0.1/PKG-INFO` & `iPLAN-0.1.0/PKG-INFO`

 * *Files 12% similar despite different names*

```diff
@@ -1,111 +1,131 @@
 Metadata-Version: 2.1
 Name: iPLAN
-Version: 0.0.1
+Version: 0.1.0
 Summary: Codebase for iPLAN: Intent-Aware Planning in Heterogeneous Traffic via Distributed Multi-Agent Reinforcement Learning
 Home-page: https://github.com/wuxiyang1996/iPLAN
 Author: Xiyang Wu
 Author-email: wuxiyang1996@gmail.com
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
-# iPLAN
+<p align="center">
+    <img src="iPLAN/animation/iPLAN_Hetero_H_5_90.0_21.81.gif"><br/>
+</p>
 
 This repository is the codebase for our paper.
 
-[iPLAN: Intent-Aware Planning in Heterogeneous Traffic via Distributed Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2306.06236)
+[**iPLAN: Intent-Aware Planning in Heterogeneous Traffic via Distributed Multi-Agent Reinforcement Learning**](https://arxiv.org/abs/2306.06236)
 
-This repository was originally forked from https://github.com/oxwhirl/pymarl and https://github.com/carolinewang01/dm2. 
-The MAPPO baseline comes from https://github.com/uoe-agents/epymarl.
+This repository was originally **forked from https://github.com/oxwhirl/pymarl** 
+and **https://github.com/carolinewang01/dm2**. 
+The MAPPO baseline comes from **https://github.com/uoe-agents/epymarl**.
 
 # Table of Contents
-- [Dependencies](#Dependencies)
-- [Running iPLAN](#Running-iPLAN)
-- [Ablation Study](#Ablation-Study)
-  - [IPPO](#Running-IPPO), [IPPO-BM](#Running-IPPO-BM), [IPPO-GAT](#Running-IPPO-GAT), 
-  [iPLAN-Hard](#Running-iPLAN-Hard), [iPLAN-FC](#Running-iPLAN-FC)
-- [Baselines](#Baselines)
-- [Helper Functions](#Helper-Functions)
-  - [Compute Navigation Metrics](#Compute-Navigation-Metrics)
-  - [Generate Animation](#Generate-Animation)
-  - [Plot Reward Curve](#Plot-Reward-Curve)
-- [Results](#Results)
-- [Animation](#Animation)
-- [Citation](#Citation)
+- [**Dependencies**](#Dependencies)
+- [**Installation**](#Installation)
+- [**Running iPLAN**](#Running-iPLAN)
+- [**Ablation Study**](#Ablation-Study)
+  - [**IPPO**](#Running-IPPO), [**IPPO-BM**](#Running-IPPO-BM), [**IPPO-GAT**](#Running-IPPO-GAT), 
+  [**iPLAN-Hard**](#Running-iPLAN-Hard), [**iPLAN-FC**](#Running-iPLAN-FC)
+- [**Baselines**](#Baselines)
+- [**Helper Functions**](#Helper-Functions)
+  - [**Compute Navigation Metrics**](#Compute-Navigation-Metrics)
+  - [**Generate Animation**](#Generate-Animation)
+  - [**Plot Reward Curve**](#Plot-Reward-Curve)
+- [**Results**](#Results)
+- [**Animation**](#Animation)
+- [**Citation**](#Citation)
 
 # Dependencies
-* [PyTorch](https://pytorch.org/) (1.13.1 + cu116) (GPU)
-* [stable-baselines3](https://github.com/DLR-RM/stable-baselines3)
-* [highway-env](https://github.com/Farama-Foundation/HighwayEnv/tree/master)
-* [scared](https://sacred.readthedocs.io/en/stable/quickstart.html)
-* [PyYAML](https://pypi.org/project/PyYAML/)
-
-**Note**: Please replace the initial [Highway-env](https://github.com/Farama-Foundation/HighwayEnv) in your compiling 
-environment with our modified Highway-env given in `highway_env` folder. Also, 
-[Multi-agent Particles](https://github.com/openai/multiagent-particle-envs) used in our repo are different. Please use 
+* [**PyTorch**](https://pytorch.org/) (1.13.1 + cu116) (GPU)
+* [**stable-baselines3**](https://github.com/DLR-RM/stable-baselines3)
+* [**Heterogeneous_Highway_Env**](https://github.com/wuxiyang1996/Heterogeneous_Highway_Env) (Forked from
+[**highway-env**](https://github.com/Farama-Foundation/HighwayEnv/tree/master))
+* [**scared**](https://sacred.readthedocs.io/en/stable/quickstart.html)
+* [**PyYAML**](https://pypi.org/project/PyYAML/)
+
+**Note**: Please our modified Highway-env given in [**Heterogeneous_Highway_Env**](https://github.com/wuxiyang1996/Heterogeneous_Highway_Env)
+as there are major changes from the initial version of [**highway-env**](https://github.com/Farama-Foundation/HighwayEnv/tree/master). Also, 
+[**Multi-agent Particles**](https://github.com/openai/multiagent-particle-envs) used in our repo are different. Please use 
 the code given in `envs/mpe` folder.
  
+# Installation
+First, install dependencies
+```angular2html
+pip install stable-baselines3[extra] pyyaml sacred
+```
+Then install our forked version of Highway-env
+```angular2html
+pip install Heterogeneous_Highway_Env
+```
+Finally, install iPLAN package
+```angular2html
+pip install iPLAN
+```
+
 # Running iPLAN
 In the configuration file `config/default.yaml`, set up environments needed for your experiment:
 * Set environment `env`: `MPE` for Non-cooperative Navigation and `highway` for Heterogeneous Highway
 * Set difficulty level `difficulty`: 
   * `easy` for easy (Non-cooperative Navigation) or mild (Heterogeneous Highway) scenario.
   * `hard` for hard (Non-cooperative Navigation) or chaotic (Heterogeneous Highway) scenario.
 * Set `Behavior_enable: True`
 * Set `GAT_enable: True` and `GAT_use_behavior: True`
 * Set `soft_update_enable: True` and `behavior_fully_connected: False`
-* Run `main.py`
+* Run `python3 main.py`
 
 Results, including printed logs, saved models and tensorboard logger, are stored in the folder `results` 
 
 # Ablation Study
 When running experiments for ablation study, please only change the hyperparameters mentioned 
+in the configuration file `config/default.yaml`
 and keep those the same as they are in the iPLAN experiment.
 ## Running IPPO
 * Set `Behavior_enable: False`
 * Set `GAT_enable: False` and `GAT_use_behavior: False`
-* Run `main.py`
+* Run `python3 main.py`
 
 ## Running IPPO-BM
 * Set `Behavior_enable: True`
 * Set `GAT_enable: False` and `GAT_use_behavior: False`
-* Run `main.py`
+* Run `python3 main.py`
 
 ## Running IPPO-GAT
 * Set `Behavior_enable: False`
 * Set `GAT_enable: True` and `GAT_use_behavior: True`
-* Run `main.py`
+* Run `python3 main.py`
 
 ## Running iPLAN-Hard
 * Set `soft_update_enable: False`
-* Run `main.py`
+* Run `python3 main.py`
 
 ## Running iPLAN-FC
 * Set `behavior_fully_connected: True`
-* Run `main.py`
+* Run `python3 main.py`
 
 # Baselines
 Baselines used in this paper could be found in the `baselines`folder, where the organization of files is 
 similar to the main directory of iPLAN. Please change the environment setting in `config/default.yaml` 
 before experiments. No extra changes need.
-* [QMIX](https://github.com/oxwhirl/pymarl) `baselines/QMIX/main.py`
-* [MAPPO](https://github.com/uoe-agents/epymarl) `baselines/MAPPO/main.py`
+* [**QMIX**](https://github.com/oxwhirl/pymarl): Run `python3 baselines/QMIX/main.py`
+* [**MAPPO**](https://github.com/uoe-agents/epymarl): Run `python3 baselines/MAPPO/main.py`
 
 # Helper Functions
 Notebooks for helper function are given in `helper` folder.
 Please follow the instructions below:
 ## Compute Navigation Metrics
 (Only for Heterogeneous Highway)
 In the configuration file `config/default.yaml`
 * Set `metrics_enable: True`
 * Set `num_test_episodes` larger than `batch_size_run`
-* Run `main.py`
+* Run `python3 main.py`
 
 Then you will get printed navigation metrics after the execution logs of each episode.
 
 To compute the navigation metrics, use the notebook `helper/RL_results_metrics.ipynb` to compute averaged navigation 
 metrics from the printed log file (usually given in `results/sacred`).
 
 ## Generate Animation
@@ -124,55 +144,58 @@
 to convert the log file into `.csv` file.
 * Use the notebook `RL Visualization Helper - Highway.ipynb` (Heterogeneous Highway) or 
 `RL Visualization Helper - MPE.ipynb` (Non-cooperative Navigation) to plot the reward curve 
 from the generated `.csv` files for each approaches and scenarios.
 
 # Results
 <p align="center">
-    <img src="figs/MPE_comb.png"><br/>
+    <img src="iPLAN/figs/MPE_comb.png"><br/>
     <em> Non-Cooperative Navigation: with 3 agents in the (left) easy and (right) hard scenarios. 50 steps/episode. </em>
 </p>
 <p align="center">
-    <img src="figs/Hetero_comb.png"><br/>
+    <img src="iPLAN/figs/Hetero_comb.png"><br/>
     <em> Heterogeneous Highway: with 5 agents in (left) mild and (right) chaotic scenarios. 90 steps/episode. </em>
 </p>
 
 # Animation
+We visually compare the performance of iPLAN
+with QMIX and MAPPO. Each baseline is tested with multiple learning agents shown in green, and each animation
+shows 5 such learning agents from their respective viewpoints. 
 <p align="center">
-    <img src="animation/iPLAN_Hetero_E_5_90.0_23.95.gif"><br/>
+    <img src="iPLAN/animation/iPLAN_Hetero_E_5_90.0_23.95.gif"><br/>
     <em> iPLAN in mild (easy) scenario of Heterogeneous Highway 
     (Num of agents succeed: 5, Avg. survival time: 90, Avg. speed: 23.95).</em>
 </p>
 
 <p align="center">
-    <img src="animation/iPLAN_Hetero_H_5_90.0_21.81.gif"><br/>
+    <img src="iPLAN/animation/iPLAN_Hetero_H_5_90.0_21.81.gif"><br/>
     <em> iPLAN in chaotic (hard) scenario of Heterogeneous Highway 
     (Num of agents succeed: 5, Avg. survival time: 90, Avg. speed: 21.81).</em>
 </p>
 
 <p align="center">
-    <img src="animation/MAPPO_Hetero_E_2_49.6_28.44.gif"><br/>
+    <img src="iPLAN/animation/MAPPO_Hetero_E_2_49.6_28.44.gif"><br/>
     <em> MAPPO in mild (easy) scenario of Heterogeneous Highway 
     (Num of agents succeed: 2, Avg. survival time: 49.6, Avg. speed: 28.44).</em>
 </p>
 
 <p align="center">
-    <img src="animation/MAPPO_Hetero_H_2_54.0_28.66.gif"><br/>
+    <img src="iPLAN/animation/MAPPO_Hetero_H_2_54.0_28.66.gif"><br/>
     <em> MAPPO in chaotic (hard) scenario of Heterogeneous Highway 
     (Num of agents succeed: 2, Avg. survival time: 54.0, Avg. speed: 28.44).</em>
 </p>
 
 <p align="center">
-    <img src="animation/QMIX_Hetero_E_4_72.6_21.2.gif"><br/>
+    <img src="iPLAN/animation/QMIX_Hetero_E_4_72.6_21.2.gif"><br/>
     <em> QMIX in mild (easy) scenario of Heterogeneous Highway 
     (Num of agents succeed: 4, Avg. survival time: 72.6, Avg. speed: 21.2).</em>
 </p>
 
 <p align="center">
-    <img src="animation/QMIX_Hetero_H_3_67.8_24.9.gif"><br/>
+    <img src="iPLAN/animation/QMIX_Hetero_H_3_67.8_24.9.gif"><br/>
     <em> QMIX in chaotic (hard) scenario of Heterogeneous Highway 
     (Num of agents succeed: 3, Avg. survival time: 67.8, Avg. speed: 24.9).</em>
 </p>
 
 # Citation
 ```
 @article{wu2023iplan,
```

### Comparing `iPLAN-0.0.1/components/action_selectors.py` & `iPLAN-0.1.0/iPLAN/components/action_selectors.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.0.1/components/episode_buffer.py` & `iPLAN-0.1.0/iPLAN/components/episode_buffer.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.0.1/components/epsilon_schedules.py` & `iPLAN-0.1.0/iPLAN/components/epsilon_schedules.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.0.1/components/transforms.py` & `iPLAN-0.1.0/iPLAN/components/transforms.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.0.1/iPLAN.egg-info/PKG-INFO` & `iPLAN-0.1.0/iPLAN.egg-info/PKG-INFO`

 * *Files 12% similar despite different names*

```diff
@@ -1,111 +1,131 @@
 Metadata-Version: 2.1
 Name: iPLAN
-Version: 0.0.1
+Version: 0.1.0
 Summary: Codebase for iPLAN: Intent-Aware Planning in Heterogeneous Traffic via Distributed Multi-Agent Reinforcement Learning
 Home-page: https://github.com/wuxiyang1996/iPLAN
 Author: Xiyang Wu
 Author-email: wuxiyang1996@gmail.com
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
-# iPLAN
+<p align="center">
+    <img src="iPLAN/animation/iPLAN_Hetero_H_5_90.0_21.81.gif"><br/>
+</p>
 
 This repository is the codebase for our paper.
 
-[iPLAN: Intent-Aware Planning in Heterogeneous Traffic via Distributed Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2306.06236)
+[**iPLAN: Intent-Aware Planning in Heterogeneous Traffic via Distributed Multi-Agent Reinforcement Learning**](https://arxiv.org/abs/2306.06236)
 
-This repository was originally forked from https://github.com/oxwhirl/pymarl and https://github.com/carolinewang01/dm2. 
-The MAPPO baseline comes from https://github.com/uoe-agents/epymarl.
+This repository was originally **forked from https://github.com/oxwhirl/pymarl** 
+and **https://github.com/carolinewang01/dm2**. 
+The MAPPO baseline comes from **https://github.com/uoe-agents/epymarl**.
 
 # Table of Contents
-- [Dependencies](#Dependencies)
-- [Running iPLAN](#Running-iPLAN)
-- [Ablation Study](#Ablation-Study)
-  - [IPPO](#Running-IPPO), [IPPO-BM](#Running-IPPO-BM), [IPPO-GAT](#Running-IPPO-GAT), 
-  [iPLAN-Hard](#Running-iPLAN-Hard), [iPLAN-FC](#Running-iPLAN-FC)
-- [Baselines](#Baselines)
-- [Helper Functions](#Helper-Functions)
-  - [Compute Navigation Metrics](#Compute-Navigation-Metrics)
-  - [Generate Animation](#Generate-Animation)
-  - [Plot Reward Curve](#Plot-Reward-Curve)
-- [Results](#Results)
-- [Animation](#Animation)
-- [Citation](#Citation)
+- [**Dependencies**](#Dependencies)
+- [**Installation**](#Installation)
+- [**Running iPLAN**](#Running-iPLAN)
+- [**Ablation Study**](#Ablation-Study)
+  - [**IPPO**](#Running-IPPO), [**IPPO-BM**](#Running-IPPO-BM), [**IPPO-GAT**](#Running-IPPO-GAT), 
+  [**iPLAN-Hard**](#Running-iPLAN-Hard), [**iPLAN-FC**](#Running-iPLAN-FC)
+- [**Baselines**](#Baselines)
+- [**Helper Functions**](#Helper-Functions)
+  - [**Compute Navigation Metrics**](#Compute-Navigation-Metrics)
+  - [**Generate Animation**](#Generate-Animation)
+  - [**Plot Reward Curve**](#Plot-Reward-Curve)
+- [**Results**](#Results)
+- [**Animation**](#Animation)
+- [**Citation**](#Citation)
 
 # Dependencies
-* [PyTorch](https://pytorch.org/) (1.13.1 + cu116) (GPU)
-* [stable-baselines3](https://github.com/DLR-RM/stable-baselines3)
-* [highway-env](https://github.com/Farama-Foundation/HighwayEnv/tree/master)
-* [scared](https://sacred.readthedocs.io/en/stable/quickstart.html)
-* [PyYAML](https://pypi.org/project/PyYAML/)
-
-**Note**: Please replace the initial [Highway-env](https://github.com/Farama-Foundation/HighwayEnv) in your compiling 
-environment with our modified Highway-env given in `highway_env` folder. Also, 
-[Multi-agent Particles](https://github.com/openai/multiagent-particle-envs) used in our repo are different. Please use 
+* [**PyTorch**](https://pytorch.org/) (1.13.1 + cu116) (GPU)
+* [**stable-baselines3**](https://github.com/DLR-RM/stable-baselines3)
+* [**Heterogeneous_Highway_Env**](https://github.com/wuxiyang1996/Heterogeneous_Highway_Env) (Forked from
+[**highway-env**](https://github.com/Farama-Foundation/HighwayEnv/tree/master))
+* [**scared**](https://sacred.readthedocs.io/en/stable/quickstart.html)
+* [**PyYAML**](https://pypi.org/project/PyYAML/)
+
+**Note**: Please our modified Highway-env given in [**Heterogeneous_Highway_Env**](https://github.com/wuxiyang1996/Heterogeneous_Highway_Env)
+as there are major changes from the initial version of [**highway-env**](https://github.com/Farama-Foundation/HighwayEnv/tree/master). Also, 
+[**Multi-agent Particles**](https://github.com/openai/multiagent-particle-envs) used in our repo are different. Please use 
 the code given in `envs/mpe` folder.
  
+# Installation
+First, install dependencies
+```angular2html
+pip install stable-baselines3[extra] pyyaml sacred
+```
+Then install our forked version of Highway-env
+```angular2html
+pip install Heterogeneous_Highway_Env
+```
+Finally, install iPLAN package
+```angular2html
+pip install iPLAN
+```
+
 # Running iPLAN
 In the configuration file `config/default.yaml`, set up environments needed for your experiment:
 * Set environment `env`: `MPE` for Non-cooperative Navigation and `highway` for Heterogeneous Highway
 * Set difficulty level `difficulty`: 
   * `easy` for easy (Non-cooperative Navigation) or mild (Heterogeneous Highway) scenario.
   * `hard` for hard (Non-cooperative Navigation) or chaotic (Heterogeneous Highway) scenario.
 * Set `Behavior_enable: True`
 * Set `GAT_enable: True` and `GAT_use_behavior: True`
 * Set `soft_update_enable: True` and `behavior_fully_connected: False`
-* Run `main.py`
+* Run `python3 main.py`
 
 Results, including printed logs, saved models and tensorboard logger, are stored in the folder `results` 
 
 # Ablation Study
 When running experiments for ablation study, please only change the hyperparameters mentioned 
+in the configuration file `config/default.yaml`
 and keep those the same as they are in the iPLAN experiment.
 ## Running IPPO
 * Set `Behavior_enable: False`
 * Set `GAT_enable: False` and `GAT_use_behavior: False`
-* Run `main.py`
+* Run `python3 main.py`
 
 ## Running IPPO-BM
 * Set `Behavior_enable: True`
 * Set `GAT_enable: False` and `GAT_use_behavior: False`
-* Run `main.py`
+* Run `python3 main.py`
 
 ## Running IPPO-GAT
 * Set `Behavior_enable: False`
 * Set `GAT_enable: True` and `GAT_use_behavior: True`
-* Run `main.py`
+* Run `python3 main.py`
 
 ## Running iPLAN-Hard
 * Set `soft_update_enable: False`
-* Run `main.py`
+* Run `python3 main.py`
 
 ## Running iPLAN-FC
 * Set `behavior_fully_connected: True`
-* Run `main.py`
+* Run `python3 main.py`
 
 # Baselines
 Baselines used in this paper could be found in the `baselines`folder, where the organization of files is 
 similar to the main directory of iPLAN. Please change the environment setting in `config/default.yaml` 
 before experiments. No extra changes need.
-* [QMIX](https://github.com/oxwhirl/pymarl) `baselines/QMIX/main.py`
-* [MAPPO](https://github.com/uoe-agents/epymarl) `baselines/MAPPO/main.py`
+* [**QMIX**](https://github.com/oxwhirl/pymarl): Run `python3 baselines/QMIX/main.py`
+* [**MAPPO**](https://github.com/uoe-agents/epymarl): Run `python3 baselines/MAPPO/main.py`
 
 # Helper Functions
 Notebooks for helper function are given in `helper` folder.
 Please follow the instructions below:
 ## Compute Navigation Metrics
 (Only for Heterogeneous Highway)
 In the configuration file `config/default.yaml`
 * Set `metrics_enable: True`
 * Set `num_test_episodes` larger than `batch_size_run`
-* Run `main.py`
+* Run `python3 main.py`
 
 Then you will get printed navigation metrics after the execution logs of each episode.
 
 To compute the navigation metrics, use the notebook `helper/RL_results_metrics.ipynb` to compute averaged navigation 
 metrics from the printed log file (usually given in `results/sacred`).
 
 ## Generate Animation
@@ -124,55 +144,58 @@
 to convert the log file into `.csv` file.
 * Use the notebook `RL Visualization Helper - Highway.ipynb` (Heterogeneous Highway) or 
 `RL Visualization Helper - MPE.ipynb` (Non-cooperative Navigation) to plot the reward curve 
 from the generated `.csv` files for each approaches and scenarios.
 
 # Results
 <p align="center">
-    <img src="figs/MPE_comb.png"><br/>
+    <img src="iPLAN/figs/MPE_comb.png"><br/>
     <em> Non-Cooperative Navigation: with 3 agents in the (left) easy and (right) hard scenarios. 50 steps/episode. </em>
 </p>
 <p align="center">
-    <img src="figs/Hetero_comb.png"><br/>
+    <img src="iPLAN/figs/Hetero_comb.png"><br/>
     <em> Heterogeneous Highway: with 5 agents in (left) mild and (right) chaotic scenarios. 90 steps/episode. </em>
 </p>
 
 # Animation
+We visually compare the performance of iPLAN
+with QMIX and MAPPO. Each baseline is tested with multiple learning agents shown in green, and each animation
+shows 5 such learning agents from their respective viewpoints. 
 <p align="center">
-    <img src="animation/iPLAN_Hetero_E_5_90.0_23.95.gif"><br/>
+    <img src="iPLAN/animation/iPLAN_Hetero_E_5_90.0_23.95.gif"><br/>
     <em> iPLAN in mild (easy) scenario of Heterogeneous Highway 
     (Num of agents succeed: 5, Avg. survival time: 90, Avg. speed: 23.95).</em>
 </p>
 
 <p align="center">
-    <img src="animation/iPLAN_Hetero_H_5_90.0_21.81.gif"><br/>
+    <img src="iPLAN/animation/iPLAN_Hetero_H_5_90.0_21.81.gif"><br/>
     <em> iPLAN in chaotic (hard) scenario of Heterogeneous Highway 
     (Num of agents succeed: 5, Avg. survival time: 90, Avg. speed: 21.81).</em>
 </p>
 
 <p align="center">
-    <img src="animation/MAPPO_Hetero_E_2_49.6_28.44.gif"><br/>
+    <img src="iPLAN/animation/MAPPO_Hetero_E_2_49.6_28.44.gif"><br/>
     <em> MAPPO in mild (easy) scenario of Heterogeneous Highway 
     (Num of agents succeed: 2, Avg. survival time: 49.6, Avg. speed: 28.44).</em>
 </p>
 
 <p align="center">
-    <img src="animation/MAPPO_Hetero_H_2_54.0_28.66.gif"><br/>
+    <img src="iPLAN/animation/MAPPO_Hetero_H_2_54.0_28.66.gif"><br/>
     <em> MAPPO in chaotic (hard) scenario of Heterogeneous Highway 
     (Num of agents succeed: 2, Avg. survival time: 54.0, Avg. speed: 28.44).</em>
 </p>
 
 <p align="center">
-    <img src="animation/QMIX_Hetero_E_4_72.6_21.2.gif"><br/>
+    <img src="iPLAN/animation/QMIX_Hetero_E_4_72.6_21.2.gif"><br/>
     <em> QMIX in mild (easy) scenario of Heterogeneous Highway 
     (Num of agents succeed: 4, Avg. survival time: 72.6, Avg. speed: 21.2).</em>
 </p>
 
 <p align="center">
-    <img src="animation/QMIX_Hetero_H_3_67.8_24.9.gif"><br/>
+    <img src="iPLAN/animation/QMIX_Hetero_H_3_67.8_24.9.gif"><br/>
     <em> QMIX in chaotic (hard) scenario of Heterogeneous Highway 
     (Num of agents succeed: 3, Avg. survival time: 67.8, Avg. speed: 24.9).</em>
 </p>
 
 # Citation
 ```
 @article{wu2023iplan,
```

### Comparing `iPLAN-0.0.1/setup.py` & `iPLAN-0.1.0/setup.py`

 * *Files 18% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import setuptools
 
 with open("README.md", "r") as fh:
     long_description = fh.read()
 
 setuptools.setup(
     name="iPLAN",
-    version="0.0.1",
+    version="0.1.0",
     author="Xiyang Wu",
     author_email="wuxiyang1996@gmail.com",
     description="Codebase for iPLAN: Intent-Aware Planning in Heterogeneous Traffic via "
                 "Distributed Multi-Agent Reinforcement Learning",
     long_description=long_description,
     long_description_content_type="text/markdown",
     url="https://github.com/wuxiyang1996/iPLAN",
```

### Comparing `iPLAN-0.0.1/utils/logging.py` & `iPLAN-0.1.0/iPLAN/utils/logging.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.0.1/utils/mappo_utils/act.py` & `iPLAN-0.1.0/iPLAN/utils/mappo_utils/act.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.0.1/utils/mappo_utils/distributions.py` & `iPLAN-0.1.0/iPLAN/utils/mappo_utils/distributions.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.0.1/utils/mappo_utils/mlp.py` & `iPLAN-0.1.0/iPLAN/utils/mappo_utils/mlp.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.0.1/utils/mappo_utils/popart.py` & `iPLAN-0.1.0/iPLAN/utils/mappo_utils/popart.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.0.1/utils/mappo_utils/rnn.py` & `iPLAN-0.1.0/iPLAN/utils/mappo_utils/rnn.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.0.1/utils/mappo_utils/separated_buffer.py` & `iPLAN-0.1.0/iPLAN/utils/mappo_utils/separated_buffer.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.0.1/utils/mappo_utils/util.py` & `iPLAN-0.1.0/iPLAN/utils/mappo_utils/util.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.0.1/utils/mappo_utils/valuenorm.py` & `iPLAN-0.1.0/iPLAN/utils/mappo_utils/valuenorm.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.0.1/utils/rl_utils.py` & `iPLAN-0.1.0/iPLAN/utils/rl_utils.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.0.1/utils/timehelper.py` & `iPLAN-0.1.0/iPLAN/utils/timehelper.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.0.1/utils/vis_utils.py` & `iPLAN-0.1.0/iPLAN/utils/vis_utils.py`

 * *Files identical despite different names*


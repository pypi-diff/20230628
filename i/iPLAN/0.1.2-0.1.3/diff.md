# Comparing `tmp/iPLAN-0.1.2.tar.gz` & `tmp/iPLAN-0.1.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist\iPLAN-0.1.2.tar", last modified: Wed Jun 28 03:18:31 2023, max compression
+gzip compressed data, was "dist\iPLAN-0.1.3.tar", last modified: Wed Jun 28 03:19:43 2023, max compression
```

## Comparing `iPLAN-0.1.2.tar` & `iPLAN-0.1.3.tar`

### file list

```diff
@@ -1,38 +1,38 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 03:18:31.000000 iPLAN-0.1.2/
--rw-rw-rw-   0        0        0     1062 2023-06-27 19:32:36.000000 iPLAN-0.1.2/LICENSE
--rw-rw-rw-   0        0        0     9069 2023-06-28 03:18:31.000000 iPLAN-0.1.2/PKG-INFO
-drwxrwxrwx   0        0        0        0 2023-06-28 03:18:31.000000 iPLAN-0.1.2/iPLAN/
--rw-rw-rw-   0        0        0       14 2023-06-27 19:26:23.000000 iPLAN-0.1.2/iPLAN/__init__.py
-drwxrwxrwx   0        0        0        0 2023-06-28 03:18:31.000000 iPLAN-0.1.2/iPLAN/components/
--rw-rw-rw-   0        0        0        0 2023-05-17 01:23:16.000000 iPLAN-0.1.2/iPLAN/components/__init__.py
--rw-rw-rw-   0        0        0     2420 2023-05-17 01:23:16.000000 iPLAN-0.1.2/iPLAN/components/action_selectors.py
--rw-rw-rw-   0        0        0    10894 2023-05-17 01:23:16.000000 iPLAN-0.1.2/iPLAN/components/episode_buffer.py
--rw-rw-rw-   0        0        0     1757 2023-05-17 01:23:16.000000 iPLAN-0.1.2/iPLAN/components/epsilon_schedules.py
--rw-rw-rw-   0        0        0      568 2023-05-17 01:23:16.000000 iPLAN-0.1.2/iPLAN/components/transforms.py
--rw-rw-rw-   0        0        0     3532 2023-06-27 02:33:17.000000 iPLAN-0.1.2/iPLAN/main.py
--rw-rw-rw-   0        0        0     7833 2023-05-17 01:23:20.000000 iPLAN-0.1.2/iPLAN/observation_wrapper.py
--rw-rw-rw-   0        0        0    19010 2023-06-27 21:55:40.000000 iPLAN-0.1.2/iPLAN/run_ippo.py
-drwxrwxrwx   0        0        0        0 2023-06-28 03:18:31.000000 iPLAN-0.1.2/iPLAN/utils/
--rw-rw-rw-   0        0        0        0 2023-05-17 01:23:20.000000 iPLAN-0.1.2/iPLAN/utils/__init__.py
--rw-rw-rw-   0        0        0      132 2023-05-17 01:23:20.000000 iPLAN-0.1.2/iPLAN/utils/dict2namedtuple.py
--rw-rw-rw-   0        0        0     2135 2023-05-17 01:23:20.000000 iPLAN-0.1.2/iPLAN/utils/logging.py
-drwxrwxrwx   0        0        0        0 2023-06-28 03:18:31.000000 iPLAN-0.1.2/iPLAN/utils/mappo_utils/
--rw-rw-rw-   0        0        0        0 2023-05-17 01:23:20.000000 iPLAN-0.1.2/iPLAN/utils/mappo_utils/__init__.py
--rw-rw-rw-   0        0        0     8304 2023-05-17 01:23:20.000000 iPLAN-0.1.2/iPLAN/utils/mappo_utils/act.py
--rw-rw-rw-   0        0        0     3590 2023-05-17 01:23:20.000000 iPLAN-0.1.2/iPLAN/utils/mappo_utils/distributions.py
--rw-rw-rw-   0        0        0     1979 2023-05-17 01:23:20.000000 iPLAN-0.1.2/iPLAN/utils/mappo_utils/mlp.py
--rw-rw-rw-   0        0        0     3888 2023-05-17 01:23:20.000000 iPLAN-0.1.2/iPLAN/utils/mappo_utils/popart.py
--rw-rw-rw-   0        0        0     2910 2023-05-17 01:23:20.000000 iPLAN-0.1.2/iPLAN/utils/mappo_utils/rnn.py
--rw-rw-rw-   0        0        0     4505 2023-05-17 01:23:20.000000 iPLAN-0.1.2/iPLAN/utils/mappo_utils/separated_buffer.py
--rw-rw-rw-   0        0        0     1842 2023-05-17 01:23:20.000000 iPLAN-0.1.2/iPLAN/utils/mappo_utils/util.py
--rw-rw-rw-   0        0        0     3093 2023-05-17 01:23:20.000000 iPLAN-0.1.2/iPLAN/utils/mappo_utils/valuenorm.py
--rw-rw-rw-   0        0        0      774 2023-05-17 01:23:20.000000 iPLAN-0.1.2/iPLAN/utils/rl_utils.py
--rw-rw-rw-   0        0        0     1550 2023-05-17 01:23:20.000000 iPLAN-0.1.2/iPLAN/utils/timehelper.py
--rw-rw-rw-   0        0        0     4274 2023-05-17 01:23:20.000000 iPLAN-0.1.2/iPLAN/utils/vis_utils.py
-drwxrwxrwx   0        0        0        0 2023-06-28 03:18:31.000000 iPLAN-0.1.2/iPLAN.egg-info/
--rw-rw-rw-   0        0        0     9069 2023-06-28 03:18:31.000000 iPLAN-0.1.2/iPLAN.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      851 2023-06-28 03:18:31.000000 iPLAN-0.1.2/iPLAN.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 03:18:31.000000 iPLAN-0.1.2/iPLAN.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0        6 2023-06-28 03:18:31.000000 iPLAN-0.1.2/iPLAN.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-28 03:18:31.000000 iPLAN-0.1.2/setup.cfg
--rw-rw-rw-   0        0        0      738 2023-06-28 03:18:28.000000 iPLAN-0.1.2/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 03:19:43.000000 iPLAN-0.1.3/
+-rw-rw-rw-   0        0        0     1062 2023-06-27 19:32:36.000000 iPLAN-0.1.3/LICENSE
+-rw-rw-rw-   0        0        0     6655 2023-06-28 03:19:43.000000 iPLAN-0.1.3/PKG-INFO
+drwxrwxrwx   0        0        0        0 2023-06-28 03:19:43.000000 iPLAN-0.1.3/iPLAN/
+-rw-rw-rw-   0        0        0       14 2023-06-27 19:26:23.000000 iPLAN-0.1.3/iPLAN/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 03:19:43.000000 iPLAN-0.1.3/iPLAN/components/
+-rw-rw-rw-   0        0        0        0 2023-05-17 01:23:16.000000 iPLAN-0.1.3/iPLAN/components/__init__.py
+-rw-rw-rw-   0        0        0     2420 2023-05-17 01:23:16.000000 iPLAN-0.1.3/iPLAN/components/action_selectors.py
+-rw-rw-rw-   0        0        0    10894 2023-05-17 01:23:16.000000 iPLAN-0.1.3/iPLAN/components/episode_buffer.py
+-rw-rw-rw-   0        0        0     1757 2023-05-17 01:23:16.000000 iPLAN-0.1.3/iPLAN/components/epsilon_schedules.py
+-rw-rw-rw-   0        0        0      568 2023-05-17 01:23:16.000000 iPLAN-0.1.3/iPLAN/components/transforms.py
+-rw-rw-rw-   0        0        0     3532 2023-06-27 02:33:17.000000 iPLAN-0.1.3/iPLAN/main.py
+-rw-rw-rw-   0        0        0     7833 2023-05-17 01:23:20.000000 iPLAN-0.1.3/iPLAN/observation_wrapper.py
+-rw-rw-rw-   0        0        0    19010 2023-06-27 21:55:40.000000 iPLAN-0.1.3/iPLAN/run_ippo.py
+drwxrwxrwx   0        0        0        0 2023-06-28 03:19:43.000000 iPLAN-0.1.3/iPLAN/utils/
+-rw-rw-rw-   0        0        0        0 2023-05-17 01:23:20.000000 iPLAN-0.1.3/iPLAN/utils/__init__.py
+-rw-rw-rw-   0        0        0      132 2023-05-17 01:23:20.000000 iPLAN-0.1.3/iPLAN/utils/dict2namedtuple.py
+-rw-rw-rw-   0        0        0     2135 2023-05-17 01:23:20.000000 iPLAN-0.1.3/iPLAN/utils/logging.py
+drwxrwxrwx   0        0        0        0 2023-06-28 03:19:43.000000 iPLAN-0.1.3/iPLAN/utils/mappo_utils/
+-rw-rw-rw-   0        0        0        0 2023-05-17 01:23:20.000000 iPLAN-0.1.3/iPLAN/utils/mappo_utils/__init__.py
+-rw-rw-rw-   0        0        0     8304 2023-05-17 01:23:20.000000 iPLAN-0.1.3/iPLAN/utils/mappo_utils/act.py
+-rw-rw-rw-   0        0        0     3590 2023-05-17 01:23:20.000000 iPLAN-0.1.3/iPLAN/utils/mappo_utils/distributions.py
+-rw-rw-rw-   0        0        0     1979 2023-05-17 01:23:20.000000 iPLAN-0.1.3/iPLAN/utils/mappo_utils/mlp.py
+-rw-rw-rw-   0        0        0     3888 2023-05-17 01:23:20.000000 iPLAN-0.1.3/iPLAN/utils/mappo_utils/popart.py
+-rw-rw-rw-   0        0        0     2910 2023-05-17 01:23:20.000000 iPLAN-0.1.3/iPLAN/utils/mappo_utils/rnn.py
+-rw-rw-rw-   0        0        0     4505 2023-05-17 01:23:20.000000 iPLAN-0.1.3/iPLAN/utils/mappo_utils/separated_buffer.py
+-rw-rw-rw-   0        0        0     1842 2023-05-17 01:23:20.000000 iPLAN-0.1.3/iPLAN/utils/mappo_utils/util.py
+-rw-rw-rw-   0        0        0     3093 2023-05-17 01:23:20.000000 iPLAN-0.1.3/iPLAN/utils/mappo_utils/valuenorm.py
+-rw-rw-rw-   0        0        0      774 2023-05-17 01:23:20.000000 iPLAN-0.1.3/iPLAN/utils/rl_utils.py
+-rw-rw-rw-   0        0        0     1550 2023-05-17 01:23:20.000000 iPLAN-0.1.3/iPLAN/utils/timehelper.py
+-rw-rw-rw-   0        0        0     4274 2023-05-17 01:23:20.000000 iPLAN-0.1.3/iPLAN/utils/vis_utils.py
+drwxrwxrwx   0        0        0        0 2023-06-28 03:19:43.000000 iPLAN-0.1.3/iPLAN.egg-info/
+-rw-rw-rw-   0        0        0     6655 2023-06-28 03:19:43.000000 iPLAN-0.1.3/iPLAN.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      851 2023-06-28 03:19:43.000000 iPLAN-0.1.3/iPLAN.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 03:19:43.000000 iPLAN-0.1.3/iPLAN.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0        6 2023-06-28 03:19:43.000000 iPLAN-0.1.3/iPLAN.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 03:19:43.000000 iPLAN-0.1.3/setup.cfg
+-rw-rw-rw-   0        0        0      738 2023-06-28 03:19:40.000000 iPLAN-0.1.3/setup.py
```

### Comparing `iPLAN-0.1.2/LICENSE` & `iPLAN-0.1.3/LICENSE`

 * *Files identical despite different names*

### Comparing `iPLAN-0.1.2/iPLAN/components/action_selectors.py` & `iPLAN-0.1.3/iPLAN/components/action_selectors.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.1.2/iPLAN/components/episode_buffer.py` & `iPLAN-0.1.3/iPLAN/components/episode_buffer.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.1.2/iPLAN/components/epsilon_schedules.py` & `iPLAN-0.1.3/iPLAN/components/epsilon_schedules.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.1.2/iPLAN/components/transforms.py` & `iPLAN-0.1.3/iPLAN/components/transforms.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.1.2/iPLAN/main.py` & `iPLAN-0.1.3/iPLAN/main.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.1.2/iPLAN/observation_wrapper.py` & `iPLAN-0.1.3/iPLAN/observation_wrapper.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.1.2/iPLAN/run_ippo.py` & `iPLAN-0.1.3/iPLAN/run_ippo.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.1.2/iPLAN/utils/logging.py` & `iPLAN-0.1.3/iPLAN/utils/logging.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.1.2/iPLAN/utils/mappo_utils/act.py` & `iPLAN-0.1.3/iPLAN/utils/mappo_utils/act.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.1.2/iPLAN/utils/mappo_utils/distributions.py` & `iPLAN-0.1.3/iPLAN/utils/mappo_utils/distributions.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.1.2/iPLAN/utils/mappo_utils/mlp.py` & `iPLAN-0.1.3/iPLAN/utils/mappo_utils/mlp.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.1.2/iPLAN/utils/mappo_utils/popart.py` & `iPLAN-0.1.3/iPLAN/utils/mappo_utils/popart.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.1.2/iPLAN/utils/mappo_utils/rnn.py` & `iPLAN-0.1.3/iPLAN/utils/mappo_utils/rnn.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.1.2/iPLAN/utils/mappo_utils/separated_buffer.py` & `iPLAN-0.1.3/iPLAN/utils/mappo_utils/separated_buffer.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.1.2/iPLAN/utils/mappo_utils/util.py` & `iPLAN-0.1.3/iPLAN/utils/mappo_utils/util.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.1.2/iPLAN/utils/mappo_utils/valuenorm.py` & `iPLAN-0.1.3/iPLAN/utils/mappo_utils/valuenorm.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.1.2/iPLAN/utils/rl_utils.py` & `iPLAN-0.1.3/iPLAN/utils/rl_utils.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.1.2/iPLAN/utils/timehelper.py` & `iPLAN-0.1.3/iPLAN/utils/timehelper.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.1.2/iPLAN/utils/vis_utils.py` & `iPLAN-0.1.3/iPLAN/utils/vis_utils.py`

 * *Files identical despite different names*

### Comparing `iPLAN-0.1.2/iPLAN.egg-info/SOURCES.txt` & `iPLAN-0.1.3/iPLAN.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `iPLAN-0.1.2/setup.py` & `iPLAN-0.1.3/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import setuptools
 
 with open("README.md", "r") as fh:
     long_description = fh.read()
 
 setuptools.setup(
     name="iPLAN",
-    version="0.1.2",
+    version="0.1.3",
     author="Xiyang Wu",
     author_email="wuxiyang1996@gmail.com",
     description="Codebase for iPLAN: Intent-Aware Planning in Heterogeneous Traffic via "
                 "Distributed Multi-Agent Reinforcement Learning",
     long_description=long_description,
     long_description_content_type="text/markdown",
     url="https://github.com/wuxiyang1996/iPLAN",
```


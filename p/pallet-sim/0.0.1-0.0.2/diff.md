# Comparing `tmp/pallet_sim-0.0.1.tar.gz` & `tmp/pallet_sim-0.0.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pallet_sim-0.0.1.tar", last modified: Wed Jun 28 07:38:08 2023, max compression
+gzip compressed data, was "pallet_sim-0.0.2.tar", last modified: Wed Jun 28 08:05:42 2023, max compression
```

## Comparing `pallet_sim-0.0.1.tar` & `pallet_sim-0.0.2.tar`

### file list

```diff
@@ -1,16 +1,9 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 07:38:08.042469 pallet_sim-0.0.1/
--rw-rw-rw-   0        0        0      134 2023-06-28 07:38:08.041692 pallet_sim-0.0.1/PKG-INFO
-drwxrwxrwx   0        0        0        0 2023-06-28 07:38:08.021007 pallet_sim-0.0.1/pallet_generator2D/
--rw-rw-rw-   0        0        0        0 2023-06-28 07:21:49.000000 pallet_sim-0.0.1/pallet_generator2D/__init__.py
--rw-rw-rw-   0        0        0   293781 2022-12-22 15:37:07.000000 pallet_sim-0.0.1/pallet_generator2D/box_offset.py
--rw-rw-rw-   0        0        0     4228 2022-12-22 15:37:26.000000 pallet_sim-0.0.1/pallet_generator2D/boxprocessing.py
--rw-rw-rw-   0        0        0     6331 2023-03-17 11:30:24.000000 pallet_sim-0.0.1/pallet_generator2D/g4algorithm.py
--rw-rw-rw-   0        0        0      945 2022-12-22 15:44:58.000000 pallet_sim-0.0.1/pallet_generator2D/lists.py
--rw-rw-rw-   0        0        0     5083 2022-12-22 15:37:13.000000 pallet_sim-0.0.1/pallet_generator2D/overlapp.py
-drwxrwxrwx   0        0        0        0 2023-06-28 07:38:08.036886 pallet_sim-0.0.1/pallet_sim.egg-info/
--rw-rw-rw-   0        0        0      134 2023-06-28 07:38:07.000000 pallet_sim-0.0.1/pallet_sim.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      337 2023-06-28 07:38:07.000000 pallet_sim-0.0.1/pallet_sim.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 07:38:07.000000 pallet_sim-0.0.1/pallet_sim.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       19 2023-06-28 07:38:07.000000 pallet_sim-0.0.1/pallet_sim.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-28 07:38:08.042583 pallet_sim-0.0.1/setup.cfg
--rw-rw-rw-   0        0        0      299 2023-06-28 07:34:00.000000 pallet_sim-0.0.1/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 08:05:42.378503 pallet_sim-0.0.2/
+-rw-rw-rw-   0        0        0      134 2023-06-28 08:05:42.377357 pallet_sim-0.0.2/PKG-INFO
+drwxrwxrwx   0        0        0        0 2023-06-28 08:05:42.376309 pallet_sim-0.0.2/pallet_sim.egg-info/
+-rw-rw-rw-   0        0        0      134 2023-06-28 08:05:42.000000 pallet_sim-0.0.2/pallet_sim.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      144 2023-06-28 08:05:42.000000 pallet_sim-0.0.2/pallet_sim.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 08:05:42.000000 pallet_sim-0.0.2/pallet_sim.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 08:05:42.000000 pallet_sim-0.0.2/pallet_sim.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 08:05:42.378717 pallet_sim-0.0.2/setup.cfg
+-rw-rw-rw-   0        0        0      299 2023-06-28 08:02:07.000000 pallet_sim-0.0.2/setup.py
```


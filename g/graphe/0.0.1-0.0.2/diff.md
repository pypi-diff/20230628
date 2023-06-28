# Comparing `tmp/graphe-0.0.1.tar.gz` & `tmp/graphe-0.0.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "graphe-0.0.1.tar", last modified: Fri Jan 13 22:54:06 2023, max compression
+gzip compressed data, was "graphe-0.0.2.tar", last modified: Wed Jun 28 11:35:05 2023, max compression
```

## Comparing `graphe-0.0.1.tar` & `graphe-0.0.2.tar`

### file list

```diff
@@ -1,63 +1,95 @@
-drwxr-xr-x   0 mortenchristensen (640641318) 14964212        0 2023-01-13 22:54:06.419871 graphe-0.0.1/
--rw-r--r--   0 mortenchristensen (640641318) 14964212       66 2023-01-05 15:40:14.000000 graphe-0.0.1/.gitignore
--rw-r--r--   0 mortenchristensen (640641318) 14964212     1316 2022-12-31 07:26:15.000000 graphe-0.0.1/LICENSE
--rw-r--r--   0 mortenchristensen (640641318) 14964212      925 2023-01-13 22:54:06.419303 graphe-0.0.1/PKG-INFO
--rw-r--r--   0 mortenchristensen (640641318) 14964212      316 2023-01-13 22:46:32.000000 graphe-0.0.1/README.md
-drwxr-xr-x   0 mortenchristensen (640641318) 14964212        0 2023-01-13 22:54:06.393452 graphe-0.0.1/data/
--rw-r--r--   0 mortenchristensen (640641318) 14964212      407 2023-01-11 15:22:52.000000 graphe-0.0.1/data/jobs.txt
--rw-r--r--   0 mortenchristensen (640641318) 14964212     9107 2022-12-26 21:16:26.000000 graphe-0.0.1/data/mediumG.txt
--rw-r--r--   0 mortenchristensen (640641318) 14964212      144 2023-01-01 21:07:05.000000 graphe-0.0.1/data/routes.txt
--rw-r--r--   0 mortenchristensen (640641318) 14964212       97 2023-01-08 12:50:20.000000 graphe-0.0.1/data/scc.txt
--rw-r--r--   0 mortenchristensen (640641318) 14964212      326 2023-01-09 11:02:29.000000 graphe-0.0.1/data/test.txt
--rw-r--r--   0 mortenchristensen (640641318) 14964212       71 2023-01-08 19:42:36.000000 graphe-0.0.1/data/tinyDAG.txt
--rw-r--r--   0 mortenchristensen (640641318) 14964212      138 2023-01-02 21:07:13.000000 graphe-0.0.1/data/tinyDG.txt
--rw-r--r--   0 mortenchristensen (640641318) 14964212       63 2022-12-26 20:07:32.000000 graphe-0.0.1/data/tinyG.txt
-drwxr-xr-x   0 mortenchristensen (640641318) 14964212        0 2023-01-13 22:54:06.394058 graphe-0.0.1/docs/
--rw-r--r--   0 mortenchristensen (640641318) 14964212   167961 2023-01-01 22:46:03.000000 graphe-0.0.1/docs/long.png
-drwxr-xr-x   0 mortenchristensen (640641318) 14964212        0 2023-01-13 22:54:06.400931 graphe-0.0.1/examples/
--rwxr-xr-x   0 mortenchristensen (640641318) 14964212      293 2023-01-13 22:46:32.000000 graphe-0.0.1/examples/bfs.py
--rwxr-xr-x   0 mortenchristensen (640641318) 14964212      359 2023-01-13 22:46:32.000000 graphe-0.0.1/examples/dfs.py
--rwxr-xr-x   0 mortenchristensen (640641318) 14964212      263 2023-01-13 22:46:32.000000 graphe-0.0.1/examples/digraph.py
--rwxr-xr-x   0 mortenchristensen (640641318) 14964212      494 2023-01-13 22:46:32.000000 graphe-0.0.1/examples/directeddfs.py
--rwxr-xr-x   0 mortenchristensen (640641318) 14964212      225 2023-01-13 22:46:32.000000 graphe-0.0.1/examples/graph.py
--rwxr-xr-x   0 mortenchristensen (640641318) 14964212      325 2023-01-13 22:46:32.000000 graphe-0.0.1/examples/node_names.py
--rwxr-xr-x   0 mortenchristensen (640641318) 14964212      993 2023-01-13 22:46:32.000000 graphe-0.0.1/examples/regex.py
--rwxr-xr-x   0 mortenchristensen (640641318) 14964212      349 2023-01-13 22:46:32.000000 graphe-0.0.1/examples/symbol_graph.py
--rwxr-xr-x   0 mortenchristensen (640641318) 14964212      467 2023-01-13 22:46:32.000000 graphe-0.0.1/examples/symbol_graph_bfs.py
--rwxr-xr-x   0 mortenchristensen (640641318) 14964212      343 2023-01-13 22:46:32.000000 graphe-0.0.1/examples/topological_sort.py
--rw-r--r--   0 mortenchristensen (640641318) 14964212      767 2023-01-13 22:48:13.000000 graphe-0.0.1/pyproject.toml
-drwxr-xr-x   0 mortenchristensen (640641318) 14964212        0 2023-01-13 22:54:06.402177 graphe-0.0.1/scripts/
--rwxr-xr-x   0 mortenchristensen (640641318) 14964212      118 2023-01-13 22:46:32.000000 graphe-0.0.1/scripts/coverage
--rwxr-xr-x   0 mortenchristensen (640641318) 14964212      103 2023-01-05 12:52:28.000000 graphe-0.0.1/scripts/publish
--rw-r--r--   0 mortenchristensen (640641318) 14964212       38 2023-01-13 22:54:06.420018 graphe-0.0.1/setup.cfg
-drwxr-xr-x   0 mortenchristensen (640641318) 14964212        0 2023-01-13 22:54:06.386146 graphe-0.0.1/src/
-drwxr-xr-x   0 mortenchristensen (640641318) 14964212        0 2023-01-13 22:54:06.403561 graphe-0.0.1/src/graphe/
--rw-r--r--   0 mortenchristensen (640641318) 14964212        0 2022-12-31 07:15:14.000000 graphe-0.0.1/src/graphe/__init__.py
-drwxr-xr-x   0 mortenchristensen (640641318) 14964212        0 2023-01-13 22:54:06.411697 graphe-0.0.1/src/graphe/digraph/
--rw-r--r--   0 mortenchristensen (640641318) 14964212        0 2023-01-11 14:39:13.000000 graphe-0.0.1/src/graphe/digraph/__init__.py
--rwxr-xr-x   0 mortenchristensen (640641318) 14964212     1132 2023-01-13 22:46:32.000000 graphe-0.0.1/src/graphe/digraph/cycle.py
--rwxr-xr-x   0 mortenchristensen (640641318) 14964212     2044 2023-01-13 22:46:32.000000 graphe-0.0.1/src/graphe/digraph/ddfo.py
--rwxr-xr-x   0 mortenchristensen (640641318) 14964212     1078 2023-01-11 22:19:37.000000 graphe-0.0.1/src/graphe/digraph/digraph.py
--rw-r--r--   0 mortenchristensen (640641318) 14964212     1296 2023-01-13 22:46:32.000000 graphe-0.0.1/src/graphe/digraph/digraphdfs.py
--rwxr-xr-x   0 mortenchristensen (640641318) 14964212     1078 2023-01-13 22:46:32.000000 graphe-0.0.1/src/graphe/digraph/ksscc.py
--rwxr-xr-x   0 mortenchristensen (640641318) 14964212     3140 2023-01-13 22:46:32.000000 graphe-0.0.1/src/graphe/digraph/regex.py
--rw-r--r--   0 mortenchristensen (640641318) 14964212     1149 2023-01-13 22:46:32.000000 graphe-0.0.1/src/graphe/digraph/symboldigraph.py
--rwxr-xr-x   0 mortenchristensen (640641318) 14964212      901 2023-01-13 22:46:32.000000 graphe-0.0.1/src/graphe/digraph/topological.py
--rwxr-xr-x   0 mortenchristensen (640641318) 14964212     1639 2023-01-13 22:52:41.000000 graphe-0.0.1/src/graphe/draw.py
-drwxr-xr-x   0 mortenchristensen (640641318) 14964212        0 2023-01-13 22:54:06.414342 graphe-0.0.1/src/graphe/graph/
--rw-r--r--   0 mortenchristensen (640641318) 14964212        0 2023-01-11 14:39:18.000000 graphe-0.0.1/src/graphe/graph/__init__.py
--rwxr-xr-x   0 mortenchristensen (640641318) 14964212      988 2023-01-05 11:11:11.000000 graphe-0.0.1/src/graphe/graph/bfs.py
--rwxr-xr-x   0 mortenchristensen (640641318) 14964212      822 2023-01-11 14:56:38.000000 graphe-0.0.1/src/graphe/graph/dfs.py
--rwxr-xr-x   0 mortenchristensen (640641318) 14964212      923 2023-01-11 16:02:31.000000 graphe-0.0.1/src/graphe/graph/graph.py
-drwxr-xr-x   0 mortenchristensen (640641318) 14964212        0 2023-01-13 22:54:06.406530 graphe-0.0.1/src/graphe.egg-info/
--rw-r--r--   0 mortenchristensen (640641318) 14964212      925 2023-01-13 22:54:06.000000 graphe-0.0.1/src/graphe.egg-info/PKG-INFO
--rw-r--r--   0 mortenchristensen (640641318) 14964212     1109 2023-01-13 22:54:06.000000 graphe-0.0.1/src/graphe.egg-info/SOURCES.txt
--rw-r--r--   0 mortenchristensen (640641318) 14964212        1 2023-01-13 22:54:06.000000 graphe-0.0.1/src/graphe.egg-info/dependency_links.txt
--rw-r--r--   0 mortenchristensen (640641318) 14964212        7 2023-01-13 22:54:06.000000 graphe-0.0.1/src/graphe.egg-info/top_level.txt
-drwxr-xr-x   0 mortenchristensen (640641318) 14964212        0 2023-01-13 22:54:06.418541 graphe-0.0.1/tests/
--rwxr-xr-x   0 mortenchristensen (640641318) 14964212      857 2023-01-13 22:46:32.000000 graphe-0.0.1/tests/test_bfs.py
--rw-r--r--   0 mortenchristensen (640641318) 14964212      634 2023-01-13 22:46:32.000000 graphe-0.0.1/tests/test_cycle.py
--rwxr-xr-x   0 mortenchristensen (640641318) 14964212      858 2023-01-13 22:46:32.000000 graphe-0.0.1/tests/test_dfs.py
--rwxr-xr-x   0 mortenchristensen (640641318) 14964212      966 2023-01-13 22:46:32.000000 graphe-0.0.1/tests/test_digraph.py
--rwxr-xr-x   0 mortenchristensen (640641318) 14964212      710 2023-01-13 22:46:32.000000 graphe-0.0.1/tests/test_digraphdfs.py
--rwxr-xr-x   0 mortenchristensen (640641318) 14964212      362 2023-01-13 22:46:32.000000 graphe-0.0.1/tests/test_graph.py
+drwxr-xr-x   0 mortenchristensen (640641318) 14964212        0 2023-06-28 11:35:05.137782 graphe-0.0.2/
+-rw-r--r--   0 mortenchristensen (640641318) 14964212       66 2023-01-05 15:40:14.000000 graphe-0.0.2/.gitignore
+-rw-r--r--   0 mortenchristensen (640641318) 14964212      742 2023-01-14 14:12:06.000000 graphe-0.0.2/.readthedocs.yaml
+-rw-r--r--   0 mortenchristensen (640641318) 14964212     1316 2022-12-31 07:26:15.000000 graphe-0.0.2/LICENSE
+-rw-r--r--   0 mortenchristensen (640641318) 14964212      934 2023-06-28 11:35:05.137102 graphe-0.0.2/PKG-INFO
+-rw-r--r--   0 mortenchristensen (640641318) 14964212      325 2023-01-14 14:07:05.000000 graphe-0.0.2/README.md
+drwxr-xr-x   0 mortenchristensen (640641318) 14964212        0 2023-06-28 11:35:05.071722 graphe-0.0.2/data/
+-rw-r--r--   0 mortenchristensen (640641318) 14964212      407 2023-01-11 15:22:52.000000 graphe-0.0.2/data/jobs.txt
+-rw-r--r--   0 mortenchristensen (640641318) 14964212     9107 2022-12-26 21:16:26.000000 graphe-0.0.2/data/mediumG.txt
+-rw-r--r--   0 mortenchristensen (640641318) 14964212       29 2023-06-28 10:06:18.000000 graphe-0.0.2/data/rosalind_tree.txt
+-rw-r--r--   0 mortenchristensen (640641318) 14964212      144 2023-01-01 21:07:05.000000 graphe-0.0.2/data/routes.txt
+-rw-r--r--   0 mortenchristensen (640641318) 14964212       97 2023-01-08 12:50:20.000000 graphe-0.0.2/data/scc.txt
+-rw-r--r--   0 mortenchristensen (640641318) 14964212      326 2023-01-09 11:02:29.000000 graphe-0.0.2/data/test.txt
+-rw-r--r--   0 mortenchristensen (640641318) 14964212       71 2023-01-08 19:42:36.000000 graphe-0.0.2/data/tinyDAG.txt
+-rw-r--r--   0 mortenchristensen (640641318) 14964212      138 2023-01-02 21:07:13.000000 graphe-0.0.2/data/tinyDG.txt
+-rw-r--r--   0 mortenchristensen (640641318) 14964212       63 2022-12-26 20:07:32.000000 graphe-0.0.2/data/tinyG.txt
+drwxr-xr-x   0 mortenchristensen (640641318) 14964212        0 2023-06-28 11:35:05.072638 graphe-0.0.2/docs/
+drwxr-xr-x   0 mortenchristensen (640641318) 14964212        0 2023-06-28 11:35:05.073767 graphe-0.0.2/docs/docs/
+-rw-r--r--   0 mortenchristensen (640641318) 14964212      638 2023-01-14 14:04:31.000000 graphe-0.0.2/docs/docs/Makefile
+-rw-r--r--   0 mortenchristensen (640641318) 14964212      804 2023-01-14 14:04:31.000000 graphe-0.0.2/docs/docs/make.bat
+drwxr-xr-x   0 mortenchristensen (640641318) 14964212        0 2023-06-28 11:35:05.080395 graphe-0.0.2/docs/docs/source/
+drwxr-xr-x   0 mortenchristensen (640641318) 14964212        0 2023-06-28 11:35:05.081162 graphe-0.0.2/docs/docs/source/_static/
+-rw-r--r--   0 mortenchristensen (640641318) 14964212       64 2023-01-14 14:04:31.000000 graphe-0.0.2/docs/docs/source/_static/custom.css
+-rw-r--r--   0 mortenchristensen (640641318) 14964212     1115 2023-01-14 14:04:31.000000 graphe-0.0.2/docs/docs/source/conf.py
+-rw-r--r--   0 mortenchristensen (640641318) 14964212     3192 2023-01-14 14:04:31.000000 graphe-0.0.2/docs/docs/source/digraph.rst
+-rw-r--r--   0 mortenchristensen (640641318) 14964212     1394 2023-01-14 14:04:31.000000 graphe-0.0.2/docs/docs/source/digraphappl.rst
+-rw-r--r--   0 mortenchristensen (640641318) 14964212     1634 2023-01-14 14:04:31.000000 graphe-0.0.2/docs/docs/source/files.rst
+-rw-r--r--   0 mortenchristensen (640641318) 14964212     2150 2023-01-14 14:04:31.000000 graphe-0.0.2/docs/docs/source/graph.rst
+-rw-r--r--   0 mortenchristensen (640641318) 14964212      117 2023-01-14 14:04:31.000000 graphe-0.0.2/docs/docs/source/graphappl.rst
+drwxr-xr-x   0 mortenchristensen (640641318) 14964212        0 2023-06-28 11:35:05.094368 graphe-0.0.2/docs/docs/source/images/
+-rw-r--r--   0 mortenchristensen (640641318) 14964212   157842 2023-01-14 14:04:31.000000 graphe-0.0.2/docs/docs/source/images/digraph_dfs.png
+-rw-r--r--   0 mortenchristensen (640641318) 14964212   117680 2023-01-14 14:04:31.000000 graphe-0.0.2/docs/docs/source/images/digraph_loop.png
+-rw-r--r--   0 mortenchristensen (640641318) 14964212   163006 2023-01-14 14:04:31.000000 graphe-0.0.2/docs/docs/source/images/graph.png
+-rw-r--r--   0 mortenchristensen (640641318) 14964212   167961 2023-01-14 14:04:31.000000 graphe-0.0.2/docs/docs/source/images/long.png
+-rw-r--r--   0 mortenchristensen (640641318) 14964212    29510 2023-01-14 14:04:31.000000 graphe-0.0.2/docs/docs/source/images/node_names.png
+-rw-r--r--   0 mortenchristensen (640641318) 14964212   164521 2023-01-14 14:04:31.000000 graphe-0.0.2/docs/docs/source/images/short.png
+-rw-r--r--   0 mortenchristensen (640641318) 14964212    29454 2023-01-14 14:04:31.000000 graphe-0.0.2/docs/docs/source/images/symbol_graph_bfs.png
+-rw-r--r--   0 mortenchristensen (640641318) 14964212    51917 2023-01-14 14:04:31.000000 graphe-0.0.2/docs/docs/source/images/symbolg.png
+-rw-r--r--   0 mortenchristensen (640641318) 14964212      910 2023-01-14 14:16:12.000000 graphe-0.0.2/docs/docs/source/index.rst
+-rw-r--r--   0 mortenchristensen (640641318) 14964212      252 2023-01-14 14:04:31.000000 graphe-0.0.2/docs/docs/source/install.rst
+-rw-r--r--   0 mortenchristensen (640641318) 14964212     3112 2023-01-14 14:04:31.000000 graphe-0.0.2/docs/docs/source/usage.rst
+-rw-r--r--   0 mortenchristensen (640641318) 14964212      985 2023-01-14 14:04:31.000000 graphe-0.0.2/docs/docs/source/utils.rst
+-rw-r--r--   0 mortenchristensen (640641318) 14964212      227 2023-01-14 14:04:31.000000 graphe-0.0.2/docs/pyproject.toml
+drwxr-xr-x   0 mortenchristensen (640641318) 14964212        0 2023-06-28 11:35:05.095839 graphe-0.0.2/docs/scripts/
+-rwxr-xr-x   0 mortenchristensen (640641318) 14964212       63 2023-01-14 14:04:31.000000 graphe-0.0.2/docs/scripts/localbuild
+-rwxr-xr-x   0 mortenchristensen (640641318) 14964212       45 2023-01-14 14:04:31.000000 graphe-0.0.2/docs/scripts/view
+drwxr-xr-x   0 mortenchristensen (640641318) 14964212        0 2023-06-28 11:35:05.107444 graphe-0.0.2/examples/
+-rwxr-xr-x   0 mortenchristensen (640641318) 14964212      293 2023-01-13 22:46:32.000000 graphe-0.0.2/examples/bfs.py
+-rw-r--r--   0 mortenchristensen (640641318) 14964212      256 2023-06-28 10:36:24.000000 graphe-0.0.2/examples/cc.py
+-rwxr-xr-x   0 mortenchristensen (640641318) 14964212      359 2023-01-13 22:46:32.000000 graphe-0.0.2/examples/dfs.py
+-rwxr-xr-x   0 mortenchristensen (640641318) 14964212      250 2023-01-13 22:56:03.000000 graphe-0.0.2/examples/digraph.py
+-rwxr-xr-x   0 mortenchristensen (640641318) 14964212      494 2023-01-13 22:46:32.000000 graphe-0.0.2/examples/directeddfs.py
+-rwxr-xr-x   0 mortenchristensen (640641318) 14964212      225 2023-01-13 22:46:32.000000 graphe-0.0.2/examples/graph.py
+-rwxr-xr-x   0 mortenchristensen (640641318) 14964212      325 2023-01-13 22:46:32.000000 graphe-0.0.2/examples/node_names.py
+-rwxr-xr-x   0 mortenchristensen (640641318) 14964212      993 2023-01-13 22:46:32.000000 graphe-0.0.2/examples/regex.py
+-rwxr-xr-x   0 mortenchristensen (640641318) 14964212      349 2023-01-13 22:46:32.000000 graphe-0.0.2/examples/symbol_graph.py
+-rwxr-xr-x   0 mortenchristensen (640641318) 14964212      467 2023-01-13 22:46:32.000000 graphe-0.0.2/examples/symbol_graph_bfs.py
+-rwxr-xr-x   0 mortenchristensen (640641318) 14964212      343 2023-01-13 22:46:32.000000 graphe-0.0.2/examples/topological_sort.py
+-rw-r--r--   0 mortenchristensen (640641318) 14964212      767 2023-06-28 09:43:09.000000 graphe-0.0.2/pyproject.toml
+drwxr-xr-x   0 mortenchristensen (640641318) 14964212        0 2023-06-28 11:35:05.108888 graphe-0.0.2/scripts/
+-rwxr-xr-x   0 mortenchristensen (640641318) 14964212      118 2023-01-13 22:46:32.000000 graphe-0.0.2/scripts/coverage
+-rwxr-xr-x   0 mortenchristensen (640641318) 14964212      134 2023-06-28 11:31:29.000000 graphe-0.0.2/scripts/publish
+-rw-r--r--   0 mortenchristensen (640641318) 14964212       38 2023-06-28 11:35:05.138019 graphe-0.0.2/setup.cfg
+drwxr-xr-x   0 mortenchristensen (640641318) 14964212        0 2023-06-28 11:35:05.061450 graphe-0.0.2/src/
+drwxr-xr-x   0 mortenchristensen (640641318) 14964212        0 2023-06-28 11:35:05.110126 graphe-0.0.2/src/graphe/
+-rw-r--r--   0 mortenchristensen (640641318) 14964212        0 2022-12-31 07:15:14.000000 graphe-0.0.2/src/graphe/__init__.py
+drwxr-xr-x   0 mortenchristensen (640641318) 14964212        0 2023-06-28 11:35:05.124498 graphe-0.0.2/src/graphe/digraph/
+-rw-r--r--   0 mortenchristensen (640641318) 14964212        0 2023-01-11 14:39:13.000000 graphe-0.0.2/src/graphe/digraph/__init__.py
+-rwxr-xr-x   0 mortenchristensen (640641318) 14964212     1132 2023-01-13 22:46:32.000000 graphe-0.0.2/src/graphe/digraph/cycle.py
+-rwxr-xr-x   0 mortenchristensen (640641318) 14964212     2044 2023-01-13 22:46:32.000000 graphe-0.0.2/src/graphe/digraph/ddfo.py
+-rwxr-xr-x   0 mortenchristensen (640641318) 14964212     1078 2023-01-11 22:19:37.000000 graphe-0.0.2/src/graphe/digraph/digraph.py
+-rw-r--r--   0 mortenchristensen (640641318) 14964212     1296 2023-01-13 22:46:32.000000 graphe-0.0.2/src/graphe/digraph/digraphdfs.py
+-rwxr-xr-x   0 mortenchristensen (640641318) 14964212     1078 2023-01-13 22:46:32.000000 graphe-0.0.2/src/graphe/digraph/ksscc.py
+-rwxr-xr-x   0 mortenchristensen (640641318) 14964212     3140 2023-01-13 22:46:32.000000 graphe-0.0.2/src/graphe/digraph/regex.py
+-rw-r--r--   0 mortenchristensen (640641318) 14964212     1149 2023-01-13 22:46:32.000000 graphe-0.0.2/src/graphe/digraph/symboldigraph.py
+-rwxr-xr-x   0 mortenchristensen (640641318) 14964212      901 2023-01-13 22:46:32.000000 graphe-0.0.2/src/graphe/digraph/topological.py
+-rwxr-xr-x   0 mortenchristensen (640641318) 14964212     1639 2023-01-13 22:52:41.000000 graphe-0.0.2/src/graphe/draw.py
+drwxr-xr-x   0 mortenchristensen (640641318) 14964212        0 2023-06-28 11:35:05.128613 graphe-0.0.2/src/graphe/graph/
+-rw-r--r--   0 mortenchristensen (640641318) 14964212        0 2023-01-11 14:39:18.000000 graphe-0.0.2/src/graphe/graph/__init__.py
+-rwxr-xr-x   0 mortenchristensen (640641318) 14964212      988 2023-01-05 11:11:11.000000 graphe-0.0.2/src/graphe/graph/bfs.py
+-rw-r--r--   0 mortenchristensen (640641318) 14964212      681 2023-06-28 10:30:58.000000 graphe-0.0.2/src/graphe/graph/cc.py
+-rwxr-xr-x   0 mortenchristensen (640641318) 14964212      822 2023-01-11 14:56:38.000000 graphe-0.0.2/src/graphe/graph/dfs.py
+-rwxr-xr-x   0 mortenchristensen (640641318) 14964212      923 2023-01-11 16:02:31.000000 graphe-0.0.2/src/graphe/graph/graph.py
+drwxr-xr-x   0 mortenchristensen (640641318) 14964212        0 2023-06-28 11:35:05.116058 graphe-0.0.2/src/graphe.egg-info/
+-rw-r--r--   0 mortenchristensen (640641318) 14964212      934 2023-06-28 11:35:04.000000 graphe-0.0.2/src/graphe.egg-info/PKG-INFO
+-rw-r--r--   0 mortenchristensen (640641318) 14964212     1894 2023-06-28 11:35:05.000000 graphe-0.0.2/src/graphe.egg-info/SOURCES.txt
+-rw-r--r--   0 mortenchristensen (640641318) 14964212        1 2023-06-28 11:35:04.000000 graphe-0.0.2/src/graphe.egg-info/dependency_links.txt
+-rw-r--r--   0 mortenchristensen (640641318) 14964212        7 2023-06-28 11:35:04.000000 graphe-0.0.2/src/graphe.egg-info/top_level.txt
+drwxr-xr-x   0 mortenchristensen (640641318) 14964212        0 2023-06-28 11:35:05.136245 graphe-0.0.2/tests/
+-rwxr-xr-x   0 mortenchristensen (640641318) 14964212      857 2023-01-13 22:46:32.000000 graphe-0.0.2/tests/test_bfs.py
+-rw-r--r--   0 mortenchristensen (640641318) 14964212      634 2023-01-13 22:46:32.000000 graphe-0.0.2/tests/test_cycle.py
+-rwxr-xr-x   0 mortenchristensen (640641318) 14964212      858 2023-01-13 22:46:32.000000 graphe-0.0.2/tests/test_dfs.py
+-rwxr-xr-x   0 mortenchristensen (640641318) 14964212      966 2023-01-13 22:46:32.000000 graphe-0.0.2/tests/test_digraph.py
+-rwxr-xr-x   0 mortenchristensen (640641318) 14964212      710 2023-01-13 22:46:32.000000 graphe-0.0.2/tests/test_digraphdfs.py
+-rwxr-xr-x   0 mortenchristensen (640641318) 14964212      362 2023-01-13 22:46:32.000000 graphe-0.0.2/tests/test_graph.py
```

### Comparing `graphe-0.0.1/LICENSE` & `graphe-0.0.2/LICENSE`

 * *Files identical despite different names*

### Comparing `graphe-0.0.1/PKG-INFO` & `graphe-0.0.2/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: graphe
-Version: 0.0.1
+Version: 0.0.2
 Summary: Collection of graph algorithms, applications and visualisations
 Author-email: Morten Jagd Christensen <mortenjc@jcaps.com>
 Project-URL: Homepage, https://github.com/mortenjc/graphe
 Project-URL: Documentation, https://graphe.readthedocs.io/en/latest/
 Project-URL: Bug Tracker, https://github.com/mortenjc/graphe/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: BSD License
@@ -14,13 +14,13 @@
 License-File: LICENSE
 
 [![PyPI version](https://badge.fury.io/py/graphe.svg)](https://badge.fury.io/py/graphe)
 
 # graphe
 A pypi package with a collection of graph algorithms and visualisations.
 
-![](https://raw.githubusercontent.com/mortenjc/pygraph/main/docs/long.png)
+![](https://raw.githubusercontent.com/mortenjc/pygraph/main/docssource/images/long.png)
 
 
 # Documentation
 
-[ReadTheDocs](https://graphe-doc.readthedocs.io/)
+[ReadTheDocs](https://graphe.readthedocs.io/)
```

### Comparing `graphe-0.0.1/data/mediumG.txt` & `graphe-0.0.2/data/mediumG.txt`

 * *Files identical despite different names*

### Comparing `graphe-0.0.1/docs/long.png` & `graphe-0.0.2/docs/docs/source/images/long.png`

 * *Files identical despite different names*

### Comparing `graphe-0.0.1/examples/regex.py` & `graphe-0.0.2/examples/regex.py`

 * *Files identical despite different names*

### Comparing `graphe-0.0.1/pyproject.toml` & `graphe-0.0.2/pyproject.toml`

 * *Files 15% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [project]
 name = "graphe"
-version = "0.0.1"
+version = "0.0.2"
 authors = [
   { name="Morten Jagd Christensen", email="mortenjc@jcaps.com" },
 ]
 description = "Collection of graph algorithms, applications and visualisations"
 readme = "README.md"
 requires-python = ">=3.7"
 classifiers = [
```

### Comparing `graphe-0.0.1/src/graphe/digraph/cycle.py` & `graphe-0.0.2/src/graphe/digraph/cycle.py`

 * *Files identical despite different names*

### Comparing `graphe-0.0.1/src/graphe/digraph/ddfo.py` & `graphe-0.0.2/src/graphe/digraph/ddfo.py`

 * *Files identical despite different names*

### Comparing `graphe-0.0.1/src/graphe/digraph/digraph.py` & `graphe-0.0.2/src/graphe/digraph/digraph.py`

 * *Files identical despite different names*

### Comparing `graphe-0.0.1/src/graphe/digraph/digraphdfs.py` & `graphe-0.0.2/src/graphe/digraph/digraphdfs.py`

 * *Files identical despite different names*

### Comparing `graphe-0.0.1/src/graphe/digraph/ksscc.py` & `graphe-0.0.2/src/graphe/digraph/ksscc.py`

 * *Files identical despite different names*

### Comparing `graphe-0.0.1/src/graphe/digraph/regex.py` & `graphe-0.0.2/src/graphe/digraph/regex.py`

 * *Files identical despite different names*

### Comparing `graphe-0.0.1/src/graphe/digraph/symboldigraph.py` & `graphe-0.0.2/src/graphe/digraph/symboldigraph.py`

 * *Files identical despite different names*

### Comparing `graphe-0.0.1/src/graphe/digraph/topological.py` & `graphe-0.0.2/src/graphe/digraph/topological.py`

 * *Files identical despite different names*

### Comparing `graphe-0.0.1/src/graphe/draw.py` & `graphe-0.0.2/src/graphe/draw.py`

 * *Files identical despite different names*

### Comparing `graphe-0.0.1/src/graphe/graph/bfs.py` & `graphe-0.0.2/src/graphe/graph/bfs.py`

 * *Files identical despite different names*

### Comparing `graphe-0.0.1/src/graphe/graph/dfs.py` & `graphe-0.0.2/src/graphe/graph/dfs.py`

 * *Files identical despite different names*

### Comparing `graphe-0.0.1/src/graphe/graph/graph.py` & `graphe-0.0.2/src/graphe/graph/graph.py`

 * *Files identical despite different names*

### Comparing `graphe-0.0.1/src/graphe.egg-info/PKG-INFO` & `graphe-0.0.2/src/graphe.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: graphe
-Version: 0.0.1
+Version: 0.0.2
 Summary: Collection of graph algorithms, applications and visualisations
 Author-email: Morten Jagd Christensen <mortenjc@jcaps.com>
 Project-URL: Homepage, https://github.com/mortenjc/graphe
 Project-URL: Documentation, https://graphe.readthedocs.io/en/latest/
 Project-URL: Bug Tracker, https://github.com/mortenjc/graphe/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: BSD License
@@ -14,13 +14,13 @@
 License-File: LICENSE
 
 [![PyPI version](https://badge.fury.io/py/graphe.svg)](https://badge.fury.io/py/graphe)
 
 # graphe
 A pypi package with a collection of graph algorithms and visualisations.
 
-![](https://raw.githubusercontent.com/mortenjc/pygraph/main/docs/long.png)
+![](https://raw.githubusercontent.com/mortenjc/pygraph/main/docssource/images/long.png)
 
 
 # Documentation
 
-[ReadTheDocs](https://graphe-doc.readthedocs.io/)
+[ReadTheDocs](https://graphe.readthedocs.io/)
```

### Comparing `graphe-0.0.1/tests/test_bfs.py` & `graphe-0.0.2/tests/test_bfs.py`

 * *Files identical despite different names*

### Comparing `graphe-0.0.1/tests/test_cycle.py` & `graphe-0.0.2/tests/test_cycle.py`

 * *Files identical despite different names*

### Comparing `graphe-0.0.1/tests/test_dfs.py` & `graphe-0.0.2/tests/test_dfs.py`

 * *Files identical despite different names*

### Comparing `graphe-0.0.1/tests/test_digraph.py` & `graphe-0.0.2/tests/test_digraph.py`

 * *Files identical despite different names*

### Comparing `graphe-0.0.1/tests/test_digraphdfs.py` & `graphe-0.0.2/tests/test_digraphdfs.py`

 * *Files identical despite different names*


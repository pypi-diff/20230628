# Comparing `tmp/MCPoly-0.5.1.1.tar.gz` & `tmp/MCPoly-0.5.1.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "MCPoly-0.5.1.1.tar", last modified: Tue Jun 27 16:01:07 2023, max compression
+gzip compressed data, was "MCPoly-0.5.1.2.tar", last modified: Wed Jun 28 14:07:49 2023, max compression
```

## Comparing `MCPoly-0.5.1.1.tar` & `MCPoly-0.5.1.2.tar`

### file list

```diff
@@ -1,69 +1,69 @@
-drwxr-xr-x   0 cxs454     (503) staff       (20)        0 2023-06-27 16:01:07.553880 MCPoly-0.5.1.1/
--rw-r--r--   0 cxs454     (503) staff       (20)     1091 2023-05-03 15:22:57.000000 MCPoly-0.5.1.1/LICENSE
--rw-r--r--   0 cxs454     (503) staff       (20)       17 2023-05-04 08:23:11.000000 MCPoly-0.5.1.1/MANIFEST.in
-drwxr-xr-x   0 cxs454     (503) staff       (20)        0 2023-06-27 16:01:07.546024 MCPoly-0.5.1.1/MCPoly/
--rw-r--r--   0 cxs454     (503) staff       (20)    12292 2023-06-27 16:00:50.000000 MCPoly-0.5.1.1/MCPoly/.DS_Store
--rw-r--r--   0 cxs454     (503) staff       (20)      178 2023-05-15 14:05:30.000000 MCPoly-0.5.1.1/MCPoly/__init__.py
-drwxr-xr-x   0 cxs454     (503) staff       (20)        0 2023-06-27 16:01:07.547924 MCPoly-0.5.1.1/MCPoly/lmpset/
--rw-r--r--   0 cxs454     (503) staff       (20)     5719 2023-06-18 16:08:00.000000 MCPoly-0.5.1.1/MCPoly/lmpset/DATAtoXYZ.py
--rw-r--r--   0 cxs454     (503) staff       (20)     4361 2023-06-12 14:51:59.000000 MCPoly-0.5.1.1/MCPoly/lmpset/DATAtomolTXT.py
--rw-r--r--   0 cxs454     (503) staff       (20)      169 2023-06-17 16:42:13.000000 MCPoly-0.5.1.1/MCPoly/lmpset/__init__.py
--rw-r--r--   0 cxs454     (503) staff       (20)    55548 2023-06-05 13:00:53.000000 MCPoly-0.5.1.1/MCPoly/lmpset/chain.py
--rw-r--r--   0 cxs454     (503) staff       (20)    16310 2023-06-03 14:28:50.000000 MCPoly-0.5.1.1/MCPoly/lmpset/infchain.py
--rw-r--r--   0 cxs454     (503) staff       (20)    53042 2023-06-18 16:59:51.000000 MCPoly-0.5.1.1/MCPoly/lmpset/mould.py
--rw-r--r--   0 cxs454     (503) staff       (20)     5402 2023-06-19 16:17:41.000000 MCPoly-0.5.1.1/MCPoly/lmpset/rebuild.py
-drwxr-xr-x   0 cxs454     (503) staff       (20)        0 2023-06-27 16:01:07.548996 MCPoly-0.5.1.1/MCPoly/moldraw/
--rw-r--r--   0 cxs454     (503) staff       (20)     8966 2023-05-26 12:59:21.000000 MCPoly-0.5.1.1/MCPoly/moldraw/C_selection.py
--rw-r--r--   0 cxs454     (503) staff       (20)      128 2023-05-29 06:59:26.000000 MCPoly-0.5.1.1/MCPoly/moldraw/__init__.py
--rw-r--r--   0 cxs454     (503) staff       (20)    64145 2023-05-26 10:41:02.000000 MCPoly-0.5.1.1/MCPoly/moldraw/bind_selection.py
--rw-r--r--   0 cxs454     (503) staff       (20)    24385 2023-05-29 07:03:41.000000 MCPoly-0.5.1.1/MCPoly/moldraw/gui.py
--rw-r--r--   0 cxs454     (503) staff       (20)   181892 2023-05-26 12:59:34.000000 MCPoly-0.5.1.1/MCPoly/moldraw/molecule.py
--rw-r--r--   0 cxs454     (503) staff       (20)    98156 2023-05-26 10:40:13.000000 MCPoly-0.5.1.1/MCPoly/moldraw/sub_selection.py
-drwxr-xr-x   0 cxs454     (503) staff       (20)        0 2023-06-27 16:01:07.550354 MCPoly-0.5.1.1/MCPoly/orcaset/
--rw-r--r--   0 cxs454     (503) staff       (20)    10729 2023-06-24 15:26:07.000000 MCPoly-0.5.1.1/MCPoly/orcaset/XYZtoINP.py
--rw-r--r--   0 cxs454     (503) staff       (20)      158 2023-05-11 15:49:25.000000 MCPoly-0.5.1.1/MCPoly/orcaset/__init__.py
--rw-r--r--   0 cxs454     (503) staff       (20)    20688 2023-06-27 14:13:27.000000 MCPoly-0.5.1.1/MCPoly/orcaset/gui.py
--rw-r--r--   0 cxs454     (503) staff       (20)     7792 2023-06-27 14:07:19.000000 MCPoly-0.5.1.1/MCPoly/orcaset/mgui.py
--rw-r--r--   0 cxs454     (503) staff       (20)     4842 2023-05-02 16:29:09.000000 MCPoly-0.5.1.1/MCPoly/orcaset/multiorca.py
--rw-r--r--   0 cxs454     (503) staff       (20)     2310 2023-06-27 14:02:40.000000 MCPoly-0.5.1.1/MCPoly/orcaset/orca.py
--rw-r--r--   0 cxs454     (503) staff       (20)    24435 2023-06-27 14:13:11.000000 MCPoly-0.5.1.1/MCPoly/orcaset/ssgui.py
--rw-r--r--   0 cxs454     (503) staff       (20)     9044 2023-06-09 09:20:04.000000 MCPoly-0.5.1.1/MCPoly/orcaset/ssorca.py
--rw-r--r--   0 cxs454     (503) staff       (20)     2145 2023-05-09 08:28:02.000000 MCPoly-0.5.1.1/MCPoly/orcaset/view3dchoose.py
-drwxr-xr-x   0 cxs454     (503) staff       (20)        0 2023-06-27 16:01:07.551447 MCPoly-0.5.1.1/MCPoly/sscurve/
--rw-r--r--   0 cxs454     (503) staff       (20)     1193 2023-05-02 16:03:26.000000 MCPoly-0.5.1.1/MCPoly/sscurve/YModulus.py
--rw-r--r--   0 cxs454     (503) staff       (20)      133 2023-06-27 15:58:50.000000 MCPoly-0.5.1.1/MCPoly/sscurve/__init__.py
--rw-r--r--   0 cxs454     (503) staff       (20)    12770 2023-06-22 12:33:27.000000 MCPoly-0.5.1.1/MCPoly/sscurve/gui.py
--rw-r--r--   0 cxs454     (503) staff       (20)    12736 2023-06-27 15:58:34.000000 MCPoly-0.5.1.1/MCPoly/sscurve/gui2.py
--rw-r--r--   0 cxs454     (503) staff       (20)     5843 2023-05-19 09:04:58.000000 MCPoly-0.5.1.1/MCPoly/sscurve/multiple.py
--rw-r--r--   0 cxs454     (503) staff       (20)     5162 2023-06-27 15:58:01.000000 MCPoly-0.5.1.1/MCPoly/sscurve/multiple2.py
--rw-r--r--   0 cxs454     (503) staff       (20)    13033 2023-06-27 15:58:20.000000 MCPoly-0.5.1.1/MCPoly/sscurve/single.py
-drwxr-xr-x   0 cxs454     (503) staff       (20)        0 2023-06-27 16:01:07.552019 MCPoly-0.5.1.1/MCPoly/status/
--rw-r--r--   0 cxs454     (503) staff       (20)       62 2023-05-18 16:46:40.000000 MCPoly-0.5.1.1/MCPoly/status/__init__.py
--rw-r--r--   0 cxs454     (503) staff       (20)     6192 2023-06-18 16:33:35.000000 MCPoly-0.5.1.1/MCPoly/status/echart.py
--rw-r--r--   0 cxs454     (503) staff       (20)    15750 2023-05-18 16:45:20.000000 MCPoly-0.5.1.1/MCPoly/status/gui.py
--rw-r--r--   0 cxs454     (503) staff       (20)    24351 2023-06-27 13:59:56.000000 MCPoly-0.5.1.1/MCPoly/status/status.py
-drwxr-xr-x   0 cxs454     (503) staff       (20)        0 2023-06-27 16:01:07.552323 MCPoly-0.5.1.1/MCPoly/version/
--rw-r--r--   0 cxs454     (503) staff       (20)       23 2023-05-04 08:03:54.000000 MCPoly-0.5.1.1/MCPoly/version/__init__.py
--rw-r--r--   0 cxs454     (503) staff       (20)       35 2023-06-27 16:00:57.000000 MCPoly-0.5.1.1/MCPoly/version/version.py
-drwxr-xr-x   0 cxs454     (503) staff       (20)        0 2023-06-27 16:01:07.552595 MCPoly-0.5.1.1/MCPoly/view3d/
--rw-r--r--   0 cxs454     (503) staff       (20)       22 2023-04-30 18:16:37.000000 MCPoly-0.5.1.1/MCPoly/view3d/__init__.py
--rw-r--r--   0 cxs454     (503) staff       (20)     1970 2023-05-09 13:30:17.000000 MCPoly-0.5.1.1/MCPoly/view3d/view3d.py
-drwxr-xr-x   0 cxs454     (503) staff       (20)        0 2023-06-27 16:01:07.552866 MCPoly-0.5.1.1/MCPoly/vis/
--rw-r--r--   0 cxs454     (503) staff       (20)       18 2023-05-15 14:05:55.000000 MCPoly-0.5.1.1/MCPoly/vis/__init__.py
--rw-r--r--   0 cxs454     (503) staff       (20)     2112 2023-06-27 13:59:22.000000 MCPoly-0.5.1.1/MCPoly/vis/vis.py
-drwxr-xr-x   0 cxs454     (503) staff       (20)        0 2023-06-27 16:01:07.546853 MCPoly-0.5.1.1/MCPoly.egg-info/
--rw-r--r--   0 cxs454     (503) staff       (20)     4137 2023-06-27 16:01:07.000000 MCPoly-0.5.1.1/MCPoly.egg-info/PKG-INFO
--rw-r--r--   0 cxs454     (503) staff       (20)     1330 2023-06-27 16:01:07.000000 MCPoly-0.5.1.1/MCPoly.egg-info/SOURCES.txt
--rw-r--r--   0 cxs454     (503) staff       (20)        1 2023-06-27 16:01:07.000000 MCPoly-0.5.1.1/MCPoly.egg-info/dependency_links.txt
--rw-r--r--   0 cxs454     (503) staff       (20)      143 2023-06-27 16:01:07.000000 MCPoly-0.5.1.1/MCPoly.egg-info/requires.txt
--rw-r--r--   0 cxs454     (503) staff       (20)        7 2023-06-27 16:01:07.000000 MCPoly-0.5.1.1/MCPoly.egg-info/top_level.txt
--rw-r--r--   0 cxs454     (503) staff       (20)     4137 2023-06-27 16:01:07.553733 MCPoly-0.5.1.1/PKG-INFO
--rw-r--r--   0 cxs454     (503) staff       (20)     3773 2023-06-19 08:22:46.000000 MCPoly-0.5.1.1/README.md
--rw-r--r--   0 cxs454     (503) staff       (20)       38 2023-06-27 16:01:07.553925 MCPoly-0.5.1.1/setup.cfg
--rw-r--r--   0 cxs454     (503) staff       (20)     1033 2023-06-27 16:00:25.000000 MCPoly-0.5.1.1/setup.py
-drwxr-xr-x   0 cxs454     (503) staff       (20)        0 2023-06-27 16:01:07.553546 MCPoly-0.5.1.1/tests/
--rw-r--r--   0 cxs454     (503) staff       (20)     9627 2023-06-18 17:38:10.000000 MCPoly-0.5.1.1/tests/test_lmpset.py
--rw-r--r--   0 cxs454     (503) staff       (20)      799 2023-05-03 10:12:20.000000 MCPoly-0.5.1.1/tests/test_moldraw.py
--rw-r--r--   0 cxs454     (503) staff       (20)     3931 2023-06-24 15:32:23.000000 MCPoly-0.5.1.1/tests/test_orcaset.py
--rw-r--r--   0 cxs454     (503) staff       (20)     3535 2023-05-19 13:19:19.000000 MCPoly-0.5.1.1/tests/test_sscurve.py
--rw-r--r--   0 cxs454     (503) staff       (20)     5241 2023-06-24 15:37:07.000000 MCPoly-0.5.1.1/tests/test_status.py
+drwxr-xr-x   0 cxs454     (503) staff       (20)        0 2023-06-28 14:07:49.044466 MCPoly-0.5.1.2/
+-rw-r--r--   0 cxs454     (503) staff       (20)     1091 2023-05-03 15:22:57.000000 MCPoly-0.5.1.2/LICENSE
+-rw-r--r--   0 cxs454     (503) staff       (20)       17 2023-05-04 08:23:11.000000 MCPoly-0.5.1.2/MANIFEST.in
+drwxr-xr-x   0 cxs454     (503) staff       (20)        0 2023-06-28 14:07:49.027628 MCPoly-0.5.1.2/MCPoly/
+-rw-r--r--   0 cxs454     (503) staff       (20)    12292 2023-06-27 16:00:50.000000 MCPoly-0.5.1.2/MCPoly/.DS_Store
+-rw-r--r--   0 cxs454     (503) staff       (20)      178 2023-05-15 14:05:30.000000 MCPoly-0.5.1.2/MCPoly/__init__.py
+drwxr-xr-x   0 cxs454     (503) staff       (20)        0 2023-06-28 14:07:49.031524 MCPoly-0.5.1.2/MCPoly/lmpset/
+-rw-r--r--   0 cxs454     (503) staff       (20)     5719 2023-06-18 16:08:00.000000 MCPoly-0.5.1.2/MCPoly/lmpset/DATAtoXYZ.py
+-rw-r--r--   0 cxs454     (503) staff       (20)     4361 2023-06-12 14:51:59.000000 MCPoly-0.5.1.2/MCPoly/lmpset/DATAtomolTXT.py
+-rw-r--r--   0 cxs454     (503) staff       (20)      169 2023-06-17 16:42:13.000000 MCPoly-0.5.1.2/MCPoly/lmpset/__init__.py
+-rw-r--r--   0 cxs454     (503) staff       (20)    55548 2023-06-05 13:00:53.000000 MCPoly-0.5.1.2/MCPoly/lmpset/chain.py
+-rw-r--r--   0 cxs454     (503) staff       (20)    16310 2023-06-03 14:28:50.000000 MCPoly-0.5.1.2/MCPoly/lmpset/infchain.py
+-rw-r--r--   0 cxs454     (503) staff       (20)    53042 2023-06-18 16:59:51.000000 MCPoly-0.5.1.2/MCPoly/lmpset/mould.py
+-rw-r--r--   0 cxs454     (503) staff       (20)     5402 2023-06-19 16:17:41.000000 MCPoly-0.5.1.2/MCPoly/lmpset/rebuild.py
+drwxr-xr-x   0 cxs454     (503) staff       (20)        0 2023-06-28 14:07:49.034328 MCPoly-0.5.1.2/MCPoly/moldraw/
+-rw-r--r--   0 cxs454     (503) staff       (20)     8966 2023-05-26 12:59:21.000000 MCPoly-0.5.1.2/MCPoly/moldraw/C_selection.py
+-rw-r--r--   0 cxs454     (503) staff       (20)      128 2023-05-29 06:59:26.000000 MCPoly-0.5.1.2/MCPoly/moldraw/__init__.py
+-rw-r--r--   0 cxs454     (503) staff       (20)    64145 2023-05-26 10:41:02.000000 MCPoly-0.5.1.2/MCPoly/moldraw/bind_selection.py
+-rw-r--r--   0 cxs454     (503) staff       (20)    24385 2023-05-29 07:03:41.000000 MCPoly-0.5.1.2/MCPoly/moldraw/gui.py
+-rw-r--r--   0 cxs454     (503) staff       (20)   181892 2023-05-26 12:59:34.000000 MCPoly-0.5.1.2/MCPoly/moldraw/molecule.py
+-rw-r--r--   0 cxs454     (503) staff       (20)    98156 2023-05-26 10:40:13.000000 MCPoly-0.5.1.2/MCPoly/moldraw/sub_selection.py
+drwxr-xr-x   0 cxs454     (503) staff       (20)        0 2023-06-28 14:07:49.037340 MCPoly-0.5.1.2/MCPoly/orcaset/
+-rw-r--r--   0 cxs454     (503) staff       (20)    10729 2023-06-24 15:26:07.000000 MCPoly-0.5.1.2/MCPoly/orcaset/XYZtoINP.py
+-rw-r--r--   0 cxs454     (503) staff       (20)      158 2023-05-11 15:49:25.000000 MCPoly-0.5.1.2/MCPoly/orcaset/__init__.py
+-rw-r--r--   0 cxs454     (503) staff       (20)    20688 2023-06-27 14:13:27.000000 MCPoly-0.5.1.2/MCPoly/orcaset/gui.py
+-rw-r--r--   0 cxs454     (503) staff       (20)     7792 2023-06-27 14:07:19.000000 MCPoly-0.5.1.2/MCPoly/orcaset/mgui.py
+-rw-r--r--   0 cxs454     (503) staff       (20)     4842 2023-05-02 16:29:09.000000 MCPoly-0.5.1.2/MCPoly/orcaset/multiorca.py
+-rw-r--r--   0 cxs454     (503) staff       (20)     2310 2023-06-27 14:02:40.000000 MCPoly-0.5.1.2/MCPoly/orcaset/orca.py
+-rw-r--r--   0 cxs454     (503) staff       (20)    24591 2023-06-28 14:04:56.000000 MCPoly-0.5.1.2/MCPoly/orcaset/ssgui.py
+-rw-r--r--   0 cxs454     (503) staff       (20)     9044 2023-06-09 09:20:04.000000 MCPoly-0.5.1.2/MCPoly/orcaset/ssorca.py
+-rw-r--r--   0 cxs454     (503) staff       (20)     2145 2023-05-09 08:28:02.000000 MCPoly-0.5.1.2/MCPoly/orcaset/view3dchoose.py
+drwxr-xr-x   0 cxs454     (503) staff       (20)        0 2023-06-28 14:07:49.039362 MCPoly-0.5.1.2/MCPoly/sscurve/
+-rw-r--r--   0 cxs454     (503) staff       (20)     1193 2023-05-02 16:03:26.000000 MCPoly-0.5.1.2/MCPoly/sscurve/YModulus.py
+-rw-r--r--   0 cxs454     (503) staff       (20)      133 2023-06-27 15:58:50.000000 MCPoly-0.5.1.2/MCPoly/sscurve/__init__.py
+-rw-r--r--   0 cxs454     (503) staff       (20)    12770 2023-06-22 12:33:27.000000 MCPoly-0.5.1.2/MCPoly/sscurve/gui.py
+-rw-r--r--   0 cxs454     (503) staff       (20)    12736 2023-06-27 15:58:34.000000 MCPoly-0.5.1.2/MCPoly/sscurve/gui2.py
+-rw-r--r--   0 cxs454     (503) staff       (20)     5843 2023-05-19 09:04:58.000000 MCPoly-0.5.1.2/MCPoly/sscurve/multiple.py
+-rw-r--r--   0 cxs454     (503) staff       (20)     5162 2023-06-27 15:58:01.000000 MCPoly-0.5.1.2/MCPoly/sscurve/multiple2.py
+-rw-r--r--   0 cxs454     (503) staff       (20)    13033 2023-06-27 15:58:20.000000 MCPoly-0.5.1.2/MCPoly/sscurve/single.py
+drwxr-xr-x   0 cxs454     (503) staff       (20)        0 2023-06-28 14:07:49.040733 MCPoly-0.5.1.2/MCPoly/status/
+-rw-r--r--   0 cxs454     (503) staff       (20)       62 2023-05-18 16:46:40.000000 MCPoly-0.5.1.2/MCPoly/status/__init__.py
+-rw-r--r--   0 cxs454     (503) staff       (20)     6192 2023-06-18 16:33:35.000000 MCPoly-0.5.1.2/MCPoly/status/echart.py
+-rw-r--r--   0 cxs454     (503) staff       (20)    15750 2023-05-18 16:45:20.000000 MCPoly-0.5.1.2/MCPoly/status/gui.py
+-rw-r--r--   0 cxs454     (503) staff       (20)    24351 2023-06-27 13:59:56.000000 MCPoly-0.5.1.2/MCPoly/status/status.py
+drwxr-xr-x   0 cxs454     (503) staff       (20)        0 2023-06-28 14:07:49.041575 MCPoly-0.5.1.2/MCPoly/version/
+-rw-r--r--   0 cxs454     (503) staff       (20)       23 2023-05-04 08:03:54.000000 MCPoly-0.5.1.2/MCPoly/version/__init__.py
+-rw-r--r--   0 cxs454     (503) staff       (20)       35 2023-06-28 14:05:03.000000 MCPoly-0.5.1.2/MCPoly/version/version.py
+drwxr-xr-x   0 cxs454     (503) staff       (20)        0 2023-06-28 14:07:49.042059 MCPoly-0.5.1.2/MCPoly/view3d/
+-rw-r--r--   0 cxs454     (503) staff       (20)       22 2023-04-30 18:16:37.000000 MCPoly-0.5.1.2/MCPoly/view3d/__init__.py
+-rw-r--r--   0 cxs454     (503) staff       (20)     1970 2023-05-09 13:30:17.000000 MCPoly-0.5.1.2/MCPoly/view3d/view3d.py
+drwxr-xr-x   0 cxs454     (503) staff       (20)        0 2023-06-28 14:07:49.042739 MCPoly-0.5.1.2/MCPoly/vis/
+-rw-r--r--   0 cxs454     (503) staff       (20)       18 2023-05-15 14:05:55.000000 MCPoly-0.5.1.2/MCPoly/vis/__init__.py
+-rw-r--r--   0 cxs454     (503) staff       (20)     2112 2023-06-27 13:59:22.000000 MCPoly-0.5.1.2/MCPoly/vis/vis.py
+drwxr-xr-x   0 cxs454     (503) staff       (20)        0 2023-06-28 14:07:49.028625 MCPoly-0.5.1.2/MCPoly.egg-info/
+-rw-r--r--   0 cxs454     (503) staff       (20)     4201 2023-06-28 14:07:49.000000 MCPoly-0.5.1.2/MCPoly.egg-info/PKG-INFO
+-rw-r--r--   0 cxs454     (503) staff       (20)     1330 2023-06-28 14:07:49.000000 MCPoly-0.5.1.2/MCPoly.egg-info/SOURCES.txt
+-rw-r--r--   0 cxs454     (503) staff       (20)        1 2023-06-28 14:07:49.000000 MCPoly-0.5.1.2/MCPoly.egg-info/dependency_links.txt
+-rw-r--r--   0 cxs454     (503) staff       (20)      143 2023-06-28 14:07:49.000000 MCPoly-0.5.1.2/MCPoly.egg-info/requires.txt
+-rw-r--r--   0 cxs454     (503) staff       (20)        7 2023-06-28 14:07:49.000000 MCPoly-0.5.1.2/MCPoly.egg-info/top_level.txt
+-rw-r--r--   0 cxs454     (503) staff       (20)     4201 2023-06-28 14:07:49.044275 MCPoly-0.5.1.2/PKG-INFO
+-rw-r--r--   0 cxs454     (503) staff       (20)     3837 2023-06-28 14:06:17.000000 MCPoly-0.5.1.2/README.md
+-rw-r--r--   0 cxs454     (503) staff       (20)       38 2023-06-28 14:07:49.044531 MCPoly-0.5.1.2/setup.cfg
+-rw-r--r--   0 cxs454     (503) staff       (20)     1033 2023-06-28 14:05:11.000000 MCPoly-0.5.1.2/setup.py
+drwxr-xr-x   0 cxs454     (503) staff       (20)        0 2023-06-28 14:07:49.043926 MCPoly-0.5.1.2/tests/
+-rw-r--r--   0 cxs454     (503) staff       (20)     9627 2023-06-18 17:38:10.000000 MCPoly-0.5.1.2/tests/test_lmpset.py
+-rw-r--r--   0 cxs454     (503) staff       (20)      799 2023-05-03 10:12:20.000000 MCPoly-0.5.1.2/tests/test_moldraw.py
+-rw-r--r--   0 cxs454     (503) staff       (20)     3931 2023-06-24 15:32:23.000000 MCPoly-0.5.1.2/tests/test_orcaset.py
+-rw-r--r--   0 cxs454     (503) staff       (20)     3535 2023-05-19 13:19:19.000000 MCPoly-0.5.1.2/tests/test_sscurve.py
+-rw-r--r--   0 cxs454     (503) staff       (20)     5241 2023-06-24 15:37:07.000000 MCPoly-0.5.1.2/tests/test_status.py
```

### Comparing `MCPoly-0.5.1.1/LICENSE` & `MCPoly-0.5.1.2/LICENSE`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/MCPoly/.DS_Store` & `MCPoly-0.5.1.2/MCPoly/.DS_Store`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/MCPoly/lmpset/DATAtoXYZ.py` & `MCPoly-0.5.1.2/MCPoly/lmpset/DATAtoXYZ.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/MCPoly/lmpset/DATAtomolTXT.py` & `MCPoly-0.5.1.2/MCPoly/lmpset/DATAtomolTXT.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/MCPoly/lmpset/chain.py` & `MCPoly-0.5.1.2/MCPoly/lmpset/chain.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/MCPoly/lmpset/infchain.py` & `MCPoly-0.5.1.2/MCPoly/lmpset/infchain.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/MCPoly/lmpset/mould.py` & `MCPoly-0.5.1.2/MCPoly/lmpset/mould.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/MCPoly/lmpset/rebuild.py` & `MCPoly-0.5.1.2/MCPoly/lmpset/rebuild.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/MCPoly/moldraw/C_selection.py` & `MCPoly-0.5.1.2/MCPoly/moldraw/C_selection.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/MCPoly/moldraw/bind_selection.py` & `MCPoly-0.5.1.2/MCPoly/moldraw/bind_selection.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/MCPoly/moldraw/gui.py` & `MCPoly-0.5.1.2/MCPoly/moldraw/gui.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/MCPoly/moldraw/molecule.py` & `MCPoly-0.5.1.2/MCPoly/moldraw/molecule.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/MCPoly/moldraw/sub_selection.py` & `MCPoly-0.5.1.2/MCPoly/moldraw/sub_selection.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/MCPoly/orcaset/XYZtoINP.py` & `MCPoly-0.5.1.2/MCPoly/orcaset/XYZtoINP.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/MCPoly/orcaset/gui.py` & `MCPoly-0.5.1.2/MCPoly/orcaset/gui.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/MCPoly/orcaset/mgui.py` & `MCPoly-0.5.1.2/MCPoly/orcaset/mgui.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/MCPoly/orcaset/multiorca.py` & `MCPoly-0.5.1.2/MCPoly/orcaset/multiorca.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/MCPoly/orcaset/orca.py` & `MCPoly-0.5.1.2/MCPoly/orcaset/orca.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/MCPoly/orcaset/ssgui.py` & `MCPoly-0.5.1.2/MCPoly/orcaset/ssgui.py`

 * *Files 1% similar despite different names*

```diff
@@ -181,19 +181,19 @@
                     XYZtoINP(file.value+'_{0:.3f}'.format(strain.value),inpname=file.value+'_{0:.3f}'.format(strain.value+forcestep[key]),\
                                  method=method.value,basis_set=bs.value,opt=True,freq=freq.value,\
                                  external_force=True,aim=[aim1.value,aim2.value],strain=strain.value+forcestep[key],maxiter=maxiter.value,maxcore=room.value*1024)
                 elif roomox.value==True and coreox.value==False:
                     XYZtoINP(file.value+'_{0:.3f}'.format(strain.value),inpname=file.value+'_{0:.3f}'.format(strain.value+forcestep[key]),\
                                  method=method.value,basis_set=bs.value,opt=True,freq=freq.value,\
                                  external_force=True,aim=[aim1.value,aim2.value],strain=strain.value+forcestep[key],maxiter=maxiter.value,corenum=corenum.value)
-                    strain.value=strain.value+forcestep[key]
+            strain.value=strain.value+forcestep[key]
             keys=[]
             if addforce.value==0:
                 raise ValueError("You can't set the force add per step zero!")
-            forcestep={strain.value:addforce.value}
+            forcestep={strain.value: addforce.value}
             if addox1.value==True:
                 if addforce2.value==0:
                     raise ValueError("You can't set the force add per step zero!")
                 forcestep={strain.value: addforce.value, strain2.value: addforce2.value}
             elif addox1.value==True and addox2.value==True:
                 if addforce3.value==0:
                     raise ValueError("You can't set the force add per step zero!")
@@ -297,15 +297,15 @@
                     force.append(strain.value)
                     display(widgets.HBox([widgets.Valid(description=file.value+'_{0:.3f}'.format(strain.value),value=True),\
                                   widgets.Label('Not Converged.'), widgets.Label('[{0}]'.format(t.ctime(t.time())))]))
                     curve.layout=widgets.Layout(width='50%')
                 with case:
                     display(widgets.Label("{0}_{1:.3f} is finished but it's not converged.\n Continue?".format(file.value,strain.value)))
                     display(widgets.HBox([stop,curve]))
-                strain.value=strain.value+forcestep[key]
+                #strain.value=strain.value+forcestep[key]
                 curve.layout=widgets.Layout(width='99%')
                 break
             if ii==0:
                 output.clear_output()
                 with output:
                     display(fromoutput)
             
@@ -364,14 +364,19 @@
     def statusresult(button):
         statusoutput.clear_output()
         with statusoutput:
             while 1:
                 if s==1:
                     break
                 t.sleep(30)
+    
+    def aashow(aa):
+        if aa==404:
+            t.sleep(30)
+            intro_status(stop)
             
     options=[]
     loc=widgets.Text(description='Location:',value='./')
     for path in os.listdir(loc.value):
         if os.path.isfile(os.path.join(loc.value, path)):
             a=re.search('.xyz', path)
             if a:
@@ -424,14 +429,15 @@
     title3=widgets.Label('Constant External Force Settings',style=dict(font_weight='bold'))
     
     addout1=widgets.interactive_output(addshow1, {'addox1': addox1})
     addout2=widgets.interactive_output(addshow2, {'addox2': addox2})
     geoout=widgets.interactive_output(geoshow, {'file': file, 'loc': loc, 'aim1': aim1, 'aim2': aim2, 'method': method, 'bs': bs})
     ssout=widgets.interactive_output(curveshow, {'curve': curve, 'file': file, 'loc': loc})
     fromout=widgets.interactive_output(showfrom, {'fromshow': fromshow, 'file': file, 'loc': loc, 'aim1': aim1, 'aim2': aim2})
+    aacontinue=widgets.interactive_output(aashow, {'aa': aa})
     
     widgets.jslink((roomox,'value'),(room,'disabled'))
     widgets.jslink((coreox,'value'),(corenum,'disabled'))
     
     box_layout1 = widgets.Layout(display='flex', flew_flow='column', overflow='scroll hidden',\
                     align_items='stretch', border='solid', height='650px', width='31%')
     box_layout2 = widgets.Layout(display='flex', flew_flow='column', overflow='scroll hidden',\
```

### Comparing `MCPoly-0.5.1.1/MCPoly/orcaset/ssorca.py` & `MCPoly-0.5.1.2/MCPoly/orcaset/ssorca.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/MCPoly/orcaset/view3dchoose.py` & `MCPoly-0.5.1.2/MCPoly/orcaset/view3dchoose.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/MCPoly/sscurve/YModulus.py` & `MCPoly-0.5.1.2/MCPoly/sscurve/YModulus.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/MCPoly/sscurve/gui.py` & `MCPoly-0.5.1.2/MCPoly/sscurve/gui.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/MCPoly/sscurve/gui2.py` & `MCPoly-0.5.1.2/MCPoly/sscurve/gui2.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/MCPoly/sscurve/multiple.py` & `MCPoly-0.5.1.2/MCPoly/sscurve/multiple.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/MCPoly/sscurve/multiple2.py` & `MCPoly-0.5.1.2/MCPoly/sscurve/multiple2.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/MCPoly/sscurve/single.py` & `MCPoly-0.5.1.2/MCPoly/sscurve/single.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/MCPoly/status/echart.py` & `MCPoly-0.5.1.2/MCPoly/status/echart.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/MCPoly/status/gui.py` & `MCPoly-0.5.1.2/MCPoly/status/gui.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/MCPoly/status/status.py` & `MCPoly-0.5.1.2/MCPoly/status/status.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/MCPoly/view3d/view3d.py` & `MCPoly-0.5.1.2/MCPoly/view3d/view3d.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/MCPoly/vis/vis.py` & `MCPoly-0.5.1.2/MCPoly/vis/vis.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/MCPoly.egg-info/PKG-INFO` & `MCPoly-0.5.1.2/MCPoly.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: MCPoly
-Version: 0.5.1.1
+Version: 0.5.1.2
 Summary: Useful tools for Computational Chemistry for polymers
 Home-page: https://github.com/Omicron-Fluor/MCPoly/
 Author: Omicron Fluor
 Author-email: cxs454@student.bham.ac.uk
 License: MIT
 Keywords: ORCA,Mechanical Property,Computational Chemistry
 Description-Content-Type: text/markdown
@@ -13,21 +13,22 @@
 # MCPoly
 Some methods to deal with some manipulation of computational chemistry, mostly about mechanical properties of polymers.
 ![](./reference/function.png)
 
 ## Overview
 `MCPoly` is a Python library to make some steps of computational chemistry easier. It includes some functions of drawing molecule structures, creating proper .xyz , .inp , .mol and .data file, which specialised for using ORCA and LAMMPS, and some functions for researching the mechanical property of some polymers.
 
-## Updated in v0.5.0(19.06.23)
+## Updated in v0.5.1.2(28.06.23)
 1. Add 'rebuild' in 'lmpset' package. You can now use it to rebuild geometry structure of LAMMPS input data now.
 2. Add 'DATAtoXYZ' in 'lmpset' package to convert LAMMPS Data File into XYZ File
 3. Add 'DATAtomolTXT' to convert LAMMPS Data File into LAMMPS Molecule Text File.
 4. All these functions can be used by lmpset.mould().XXX() now.
 5. Fix some bugs about ORCA Calculations Settings
 6. Fix some bugs about ORCA GUI display
+7. Fix some bugs about judging the maximum iteration of atoms
 
 ## Updated in v0.4.2.3(12.06.23)
 1. BIG UPDATE: Molecule Designer GUI is included in this package. You can now use it to draw molecule with 3D view at the same time.
 <img src="https://github.com/Omicron-Fluor/MCPoly/blob/main/reference/moldraw_gui.png">
 2. Add 'chain' in 'lmpset' package. You can now use it to convert periodic polymer structure input data now.
 3. Fix some bugs about ORCA Calculations
 4. Fix some bugs about calculating stress-strain curve
```

### Comparing `MCPoly-0.5.1.1/MCPoly.egg-info/SOURCES.txt` & `MCPoly-0.5.1.2/MCPoly.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/PKG-INFO` & `MCPoly-0.5.1.2/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: MCPoly
-Version: 0.5.1.1
+Version: 0.5.1.2
 Summary: Useful tools for Computational Chemistry for polymers
 Home-page: https://github.com/Omicron-Fluor/MCPoly/
 Author: Omicron Fluor
 Author-email: cxs454@student.bham.ac.uk
 License: MIT
 Keywords: ORCA,Mechanical Property,Computational Chemistry
 Description-Content-Type: text/markdown
@@ -13,21 +13,22 @@
 # MCPoly
 Some methods to deal with some manipulation of computational chemistry, mostly about mechanical properties of polymers.
 ![](./reference/function.png)
 
 ## Overview
 `MCPoly` is a Python library to make some steps of computational chemistry easier. It includes some functions of drawing molecule structures, creating proper .xyz , .inp , .mol and .data file, which specialised for using ORCA and LAMMPS, and some functions for researching the mechanical property of some polymers.
 
-## Updated in v0.5.0(19.06.23)
+## Updated in v0.5.1.2(28.06.23)
 1. Add 'rebuild' in 'lmpset' package. You can now use it to rebuild geometry structure of LAMMPS input data now.
 2. Add 'DATAtoXYZ' in 'lmpset' package to convert LAMMPS Data File into XYZ File
 3. Add 'DATAtomolTXT' to convert LAMMPS Data File into LAMMPS Molecule Text File.
 4. All these functions can be used by lmpset.mould().XXX() now.
 5. Fix some bugs about ORCA Calculations Settings
 6. Fix some bugs about ORCA GUI display
+7. Fix some bugs about judging the maximum iteration of atoms
 
 ## Updated in v0.4.2.3(12.06.23)
 1. BIG UPDATE: Molecule Designer GUI is included in this package. You can now use it to draw molecule with 3D view at the same time.
 <img src="https://github.com/Omicron-Fluor/MCPoly/blob/main/reference/moldraw_gui.png">
 2. Add 'chain' in 'lmpset' package. You can now use it to convert periodic polymer structure input data now.
 3. Fix some bugs about ORCA Calculations
 4. Fix some bugs about calculating stress-strain curve
```

### Comparing `MCPoly-0.5.1.1/README.md` & `MCPoly-0.5.1.2/README.md`

 * *Files 3% similar despite different names*

```diff
@@ -1,21 +1,22 @@
 # MCPoly
 Some methods to deal with some manipulation of computational chemistry, mostly about mechanical properties of polymers.
 ![](./reference/function.png)
 
 ## Overview
 `MCPoly` is a Python library to make some steps of computational chemistry easier. It includes some functions of drawing molecule structures, creating proper .xyz , .inp , .mol and .data file, which specialised for using ORCA and LAMMPS, and some functions for researching the mechanical property of some polymers.
 
-## Updated in v0.5.0(19.06.23)
+## Updated in v0.5.1.2(28.06.23)
 1. Add 'rebuild' in 'lmpset' package. You can now use it to rebuild geometry structure of LAMMPS input data now.
 2. Add 'DATAtoXYZ' in 'lmpset' package to convert LAMMPS Data File into XYZ File
 3. Add 'DATAtomolTXT' to convert LAMMPS Data File into LAMMPS Molecule Text File.
 4. All these functions can be used by lmpset.mould().XXX() now.
 5. Fix some bugs about ORCA Calculations Settings
 6. Fix some bugs about ORCA GUI display
+7. Fix some bugs about judging the maximum iteration of atoms
 
 ## Updated in v0.4.2.3(12.06.23)
 1. BIG UPDATE: Molecule Designer GUI is included in this package. You can now use it to draw molecule with 3D view at the same time.
 <img src="https://github.com/Omicron-Fluor/MCPoly/blob/main/reference/moldraw_gui.png">
 2. Add 'chain' in 'lmpset' package. You can now use it to convert periodic polymer structure input data now.
 3. Fix some bugs about ORCA Calculations
 4. Fix some bugs about calculating stress-strain curve
```

### Comparing `MCPoly-0.5.1.1/setup.py` & `MCPoly-0.5.1.2/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 from setuptools import setup
 
 with open('README.md') as readme_file:
     README = readme_file.read()
 
 setup_args = dict(
     name='MCPoly',
-    version='0.5.1.1',
+    version='0.5.1.2',
     description='Useful tools for Computational Chemistry for polymers',
     long_description_content_type="text/markdown",
     long_description=README,
     license="MIT",
     packages=['MCPoly','MCPoly.lmpset','MCPoly.moldraw','MCPoly.orcaset','MCPoly.sscurve','MCPoly.status','MCPoly.view3d','MCPoly.version','MCPoly.vis'],
     author='Omicron Fluor',
     author_email='cxs454@student.bham.ac.uk',
```

### Comparing `MCPoly-0.5.1.1/tests/test_lmpset.py` & `MCPoly-0.5.1.2/tests/test_lmpset.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/tests/test_moldraw.py` & `MCPoly-0.5.1.2/tests/test_moldraw.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/tests/test_orcaset.py` & `MCPoly-0.5.1.2/tests/test_orcaset.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/tests/test_sscurve.py` & `MCPoly-0.5.1.2/tests/test_sscurve.py`

 * *Files identical despite different names*

### Comparing `MCPoly-0.5.1.1/tests/test_status.py` & `MCPoly-0.5.1.2/tests/test_status.py`

 * *Files identical despite different names*


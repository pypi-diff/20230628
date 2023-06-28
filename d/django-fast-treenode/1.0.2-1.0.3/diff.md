# Comparing `tmp/django-fast-treenode-1.0.2.tar.gz` & `tmp/django-fast-treenode-1.0.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "django-fast-treenode-1.0.2.tar", last modified: Thu Jun  1 19:53:49 2023, max compression
+gzip compressed data, was "django-fast-treenode-1.0.3.tar", last modified: Wed Jun 28 09:32:50 2023, max compression
```

## Comparing `django-fast-treenode-1.0.2.tar` & `django-fast-treenode-1.0.3.tar`

### file list

```diff
@@ -1,46 +1,50 @@
-drwxrwxrwx   0        0        0        0 2023-06-01 19:53:50.000000 django-fast-treenode-1.0.2/
--rw-rw-rw-   0        0        0     1092 2023-05-31 11:13:42.000000 django-fast-treenode-1.0.2/LICENSE
--rw-rw-rw-   0        0        0      147 2023-06-01 19:36:28.000000 django-fast-treenode-1.0.2/MANIFEST.in
--rw-rw-rw-   0        0        0     1104 2023-06-01 19:53:50.000000 django-fast-treenode-1.0.2/PKG-INFO
--rw-rw-rw-   0        0        0      197 2023-06-01 19:38:06.000000 django-fast-treenode-1.0.2/README.rst
-drwxrwxrwx   0        0        0        0 2023-06-01 19:53:50.000000 django-fast-treenode-1.0.2/django_fast_treenode.egg-info/
--rw-rw-rw-   0        0        0     1104 2023-06-01 19:53:50.000000 django-fast-treenode-1.0.2/django_fast_treenode.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      915 2023-06-01 19:53:50.000000 django-fast-treenode-1.0.2/django_fast_treenode.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-01 19:53:50.000000 django-fast-treenode-1.0.2/django_fast_treenode.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       12 2023-06-01 19:53:50.000000 django-fast-treenode-1.0.2/django_fast_treenode.egg-info/requires.txt
--rw-rw-rw-   0        0        0        9 2023-06-01 19:53:50.000000 django-fast-treenode-1.0.2/django_fast_treenode.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       90 2023-05-31 11:15:42.000000 django-fast-treenode-1.0.2/pyproject.toml
--rw-rw-rw-   0        0        0      933 2023-06-01 19:53:50.000000 django-fast-treenode-1.0.2/setup.cfg
--rw-rw-rw-   0        0        0       39 2023-05-31 11:20:32.000000 django-fast-treenode-1.0.2/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-01 19:53:50.000000 django-fast-treenode-1.0.2/treenode/
--rw-rw-rw-   0        0        0      171 2022-01-20 08:49:18.000000 django-fast-treenode-1.0.2/treenode/__init__.py
--rw-rw-rw-   0        0        0     5857 2022-02-12 08:55:00.000000 django-fast-treenode-1.0.2/treenode/admin.py
--rw-rw-rw-   0        0        0      154 2022-01-18 11:38:14.000000 django-fast-treenode-1.0.2/treenode/apps.py
--rw-rw-rw-   0        0        0      185 2022-01-16 20:42:14.000000 django-fast-treenode-1.0.2/treenode/compat.py
-drwxrwxrwx   0        0        0        0 2023-06-01 19:53:50.000000 django-fast-treenode-1.0.2/treenode/docs/
--rw-rw-rw-   0        0        0    16716 2023-05-31 12:12:12.000000 django-fast-treenode-1.0.2/treenode/docs/README.txt
--rw-rw-rw-   0        0        0     1942 2022-01-22 19:52:32.000000 django-fast-treenode-1.0.2/treenode/factory.py
--rw-rw-rw-   0        0        0      907 2022-02-11 19:19:44.000000 django-fast-treenode-1.0.2/treenode/forms.py
--rw-rw-rw-   0        0        0     1590 2022-02-11 16:45:34.000000 django-fast-treenode-1.0.2/treenode/managers.py
--rw-rw-rw-   0        0        0    20004 2022-02-17 13:37:14.000000 django-fast-treenode-1.0.2/treenode/models.py
-drwxrwxrwx   0        0        0        0 2023-06-01 19:53:50.000000 django-fast-treenode-1.0.2/treenode/static/
--rw-rw-rw-   0        0        0        0 2022-02-17 13:47:48.000000 django-fast-treenode-1.0.2/treenode/static/.gitkeep
-drwxrwxrwx   0        0        0        0 2023-06-01 19:53:50.000000 django-fast-treenode-1.0.2/treenode/static/select2tree/
--rw-rw-rw-   0        0        0     4234 2022-01-23 15:49:16.000000 django-fast-treenode-1.0.2/treenode/static/select2tree/select2tree.css
--rw-rw-rw-   0        0        0     5948 2022-01-23 15:13:46.000000 django-fast-treenode-1.0.2/treenode/static/select2tree/select2tree.js
-drwxrwxrwx   0        0        0        0 2023-06-01 19:53:50.000000 django-fast-treenode-1.0.2/treenode/static/treenode/
--rw-rw-rw-   0        0        0        0 2022-02-17 13:47:48.000000 django-fast-treenode-1.0.2/treenode/static/treenode/.gitkeep
-drwxrwxrwx   0        0        0        0 2023-06-01 19:53:50.000000 django-fast-treenode-1.0.2/treenode/static/treenode/css/
--rw-rw-rw-   0        0        0     1637 2022-01-16 20:42:14.000000 django-fast-treenode-1.0.2/treenode/static/treenode/css/treenode.css
-drwxrwxrwx   0        0        0        0 2023-06-01 19:53:50.000000 django-fast-treenode-1.0.2/treenode/static/treenode/js/
--rw-rw-rw-   0        0        0     7797 2022-01-21 17:23:48.000000 django-fast-treenode-1.0.2/treenode/static/treenode/js/treenode.js
-drwxrwxrwx   0        0        0        0 2023-06-01 19:53:50.000000 django-fast-treenode-1.0.2/treenode/templates/
--rw-rw-rw-   0        0        0        0 2022-02-17 13:47:48.000000 django-fast-treenode-1.0.2/treenode/templates/.gitkeep
-drwxrwxrwx   0        0        0        0 2023-06-01 19:53:50.000000 django-fast-treenode-1.0.2/treenode/templates/widgets/
--rw-rw-rw-   0        0        0      217 2021-12-13 08:39:40.000000 django-fast-treenode-1.0.2/treenode/templates/widgets/attrs.html
--rw-rw-rw-   0        0        0      288 2021-12-13 08:37:06.000000 django-fast-treenode-1.0.2/treenode/templates/widgets/options.html
--rw-rw-rw-   0        0        0      675 2022-01-22 16:59:06.000000 django-fast-treenode-1.0.2/treenode/templates/widgets/select2tree.html
--rw-rw-rw-   0        0        0       63 2022-01-18 11:38:14.000000 django-fast-treenode-1.0.2/treenode/tests.py
--rw-rw-rw-   0        0        0       50 2022-01-23 14:09:38.000000 django-fast-treenode-1.0.2/treenode/version.py
--rw-rw-rw-   0        0        0       66 2022-02-10 10:11:48.000000 django-fast-treenode-1.0.2/treenode/views.py
--rw-rw-rw-   0        0        0     1189 2022-01-28 12:26:52.000000 django-fast-treenode-1.0.2/treenode/widgets.py
+drwxrwxrwx   0        0        0        0 2023-06-28 09:32:50.000000 django-fast-treenode-1.0.3/
+-rw-rw-rw-   0        0        0     1091 2023-06-28 08:53:50.000000 django-fast-treenode-1.0.3/LICENSE
+-rw-rw-rw-   0        0        0      147 2023-06-01 20:20:34.000000 django-fast-treenode-1.0.3/MANIFEST.in
+-rw-rw-rw-   0        0        0    17715 2023-06-28 09:32:52.000000 django-fast-treenode-1.0.3/PKG-INFO
+-rw-rw-rw-   0        0        0    16805 2023-06-01 20:22:12.000000 django-fast-treenode-1.0.3/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 09:32:50.000000 django-fast-treenode-1.0.3/django_fast_treenode.egg-info/
+-rw-rw-rw-   0        0        0    17715 2023-06-28 09:32:50.000000 django-fast-treenode-1.0.3/django_fast_treenode.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0     1062 2023-06-28 09:32:50.000000 django-fast-treenode-1.0.3/django_fast_treenode.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 09:32:50.000000 django-fast-treenode-1.0.3/django_fast_treenode.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       12 2023-06-28 09:32:50.000000 django-fast-treenode-1.0.3/django_fast_treenode.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        9 2023-06-28 09:32:50.000000 django-fast-treenode-1.0.3/django_fast_treenode.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       90 2023-05-31 11:15:42.000000 django-fast-treenode-1.0.3/pyproject.toml
+-rw-rw-rw-   0        0        0      935 2023-06-28 09:32:52.000000 django-fast-treenode-1.0.3/setup.cfg
+-rw-rw-rw-   0        0        0       39 2023-05-31 11:20:32.000000 django-fast-treenode-1.0.3/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 09:32:50.000000 django-fast-treenode-1.0.3/treenode/
+-rw-rw-rw-   0        0        0      171 2022-01-20 08:49:18.000000 django-fast-treenode-1.0.3/treenode/__init__.py
+-rw-rw-rw-   0        0        0     5857 2022-02-12 08:55:00.000000 django-fast-treenode-1.0.3/treenode/admin.py
+-rw-rw-rw-   0        0        0      154 2022-01-18 11:38:14.000000 django-fast-treenode-1.0.3/treenode/apps.py
+-rw-rw-rw-   0        0        0      185 2022-01-16 20:42:14.000000 django-fast-treenode-1.0.3/treenode/compat.py
+drwxrwxrwx   0        0        0        0 2023-06-28 09:32:50.000000 django-fast-treenode-1.0.3/treenode/docs/
+-rw-rw-rw-   0        0        0    16716 2023-05-31 12:12:12.000000 django-fast-treenode-1.0.3/treenode/docs/README.txt
+-rw-rw-rw-   0        0        0     1942 2022-01-22 19:52:32.000000 django-fast-treenode-1.0.3/treenode/factory.py
+-rw-rw-rw-   0        0        0      907 2022-02-11 19:19:44.000000 django-fast-treenode-1.0.3/treenode/forms.py
+-rw-rw-rw-   0        0        0     1590 2022-02-11 16:45:34.000000 django-fast-treenode-1.0.3/treenode/managers.py
+-rw-rw-rw-   0        0        0    20048 2023-06-28 08:50:54.000000 django-fast-treenode-1.0.3/treenode/models.py
+drwxrwxrwx   0        0        0        0 2023-06-28 09:32:50.000000 django-fast-treenode-1.0.3/treenode/static/
+-rw-rw-rw-   0        0        0        0 2022-02-17 13:47:48.000000 django-fast-treenode-1.0.3/treenode/static/.gitkeep
+drwxrwxrwx   0        0        0        0 2023-06-28 09:32:50.000000 django-fast-treenode-1.0.3/treenode/static/select2tree/
+-rw-rw-rw-   0        0        0        0 2022-02-17 13:47:48.000000 django-fast-treenode-1.0.3/treenode/static/select2tree/.gitkeep
+-rw-rw-rw-   0        0        0     4234 2022-01-23 15:49:16.000000 django-fast-treenode-1.0.3/treenode/static/select2tree/select2tree.css
+-rw-rw-rw-   0        0        0     5948 2022-01-23 15:13:46.000000 django-fast-treenode-1.0.3/treenode/static/select2tree/select2tree.js
+drwxrwxrwx   0        0        0        0 2023-06-28 09:32:50.000000 django-fast-treenode-1.0.3/treenode/static/treenode/
+-rw-rw-rw-   0        0        0        0 2022-02-17 13:47:48.000000 django-fast-treenode-1.0.3/treenode/static/treenode/.gitkeep
+drwxrwxrwx   0        0        0        0 2023-06-28 09:32:50.000000 django-fast-treenode-1.0.3/treenode/static/treenode/css/
+-rw-rw-rw-   0        0        0        0 2022-02-17 13:47:48.000000 django-fast-treenode-1.0.3/treenode/static/treenode/css/.gitkeep
+-rw-rw-rw-   0        0        0     1637 2022-01-16 20:42:14.000000 django-fast-treenode-1.0.3/treenode/static/treenode/css/treenode.css
+drwxrwxrwx   0        0        0        0 2023-06-28 09:32:50.000000 django-fast-treenode-1.0.3/treenode/static/treenode/js/
+-rw-rw-rw-   0        0        0        0 2022-02-17 13:47:48.000000 django-fast-treenode-1.0.3/treenode/static/treenode/js/.gitkeep
+-rw-rw-rw-   0        0        0     7797 2022-01-21 17:23:48.000000 django-fast-treenode-1.0.3/treenode/static/treenode/js/treenode.js
+drwxrwxrwx   0        0        0        0 2023-06-28 09:32:50.000000 django-fast-treenode-1.0.3/treenode/templates/
+-rw-rw-rw-   0        0        0        0 2022-02-17 13:47:48.000000 django-fast-treenode-1.0.3/treenode/templates/.gitkeep
+drwxrwxrwx   0        0        0        0 2023-06-28 09:32:50.000000 django-fast-treenode-1.0.3/treenode/templates/widgets/
+-rw-rw-rw-   0        0        0        0 2022-02-17 13:47:48.000000 django-fast-treenode-1.0.3/treenode/templates/widgets/.gitkeep
+-rw-rw-rw-   0        0        0      217 2021-12-13 08:39:40.000000 django-fast-treenode-1.0.3/treenode/templates/widgets/attrs.html
+-rw-rw-rw-   0        0        0      288 2021-12-13 08:37:06.000000 django-fast-treenode-1.0.3/treenode/templates/widgets/options.html
+-rw-rw-rw-   0        0        0      675 2022-01-22 16:59:06.000000 django-fast-treenode-1.0.3/treenode/templates/widgets/select2tree.html
+-rw-rw-rw-   0        0        0       63 2022-01-18 11:38:14.000000 django-fast-treenode-1.0.3/treenode/tests.py
+-rw-rw-rw-   0        0        0       50 2022-01-23 14:09:38.000000 django-fast-treenode-1.0.3/treenode/version.py
+-rw-rw-rw-   0        0        0       66 2022-02-10 10:11:48.000000 django-fast-treenode-1.0.3/treenode/views.py
+-rw-rw-rw-   0        0        0     1189 2022-01-28 12:26:52.000000 django-fast-treenode-1.0.3/treenode/widgets.py
```

### Comparing `django-fast-treenode-1.0.2/LICENSE` & `django-fast-treenode-1.0.3/LICENSE`

 * *Files 9% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 MIT License
 
-Copyright (c) 2020-2023 Timur Kadı
+Copyright (c) 2020-2023 Timur Kady
 
 Permission is hereby granted, free of charge, to any person obtaining a copy
 of this software and associated documentation files (the "Software"), to deal
 in the Software without restriction, including without limitation the rights
 to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
 copies of the Software, and to permit persons to whom the Software is
 furnished to do so, subject to the following conditions:
```

#### encoding

```diff
@@ -1 +1 @@
-utf-8
+us-ascii
```

### Comparing `django-fast-treenode-1.0.2/django_fast_treenode.egg-info/SOURCES.txt` & `django-fast-treenode-1.0.3/django_fast_treenode.egg-info/SOURCES.txt`

 * *Files 18% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 LICENSE
 MANIFEST.in
-README.rst
+README.md
 pyproject.toml
 setup.cfg
 setup.py
 django_fast_treenode.egg-info/PKG-INFO
 django_fast_treenode.egg-info/SOURCES.txt
 django_fast_treenode.egg-info/dependency_links.txt
 django_fast_treenode.egg-info/requires.txt
@@ -19,16 +19,20 @@
 treenode/models.py
 treenode/tests.py
 treenode/version.py
 treenode/views.py
 treenode/widgets.py
 treenode/docs/README.txt
 treenode/static/.gitkeep
+treenode/static/select2tree/.gitkeep
 treenode/static/select2tree/select2tree.css
 treenode/static/select2tree/select2tree.js
 treenode/static/treenode/.gitkeep
+treenode/static/treenode/css/.gitkeep
 treenode/static/treenode/css/treenode.css
+treenode/static/treenode/js/.gitkeep
 treenode/static/treenode/js/treenode.js
 treenode/templates/.gitkeep
+treenode/templates/widgets/.gitkeep
 treenode/templates/widgets/attrs.html
 treenode/templates/widgets/options.html
 treenode/templates/widgets/select2tree.html
```

### Comparing `django-fast-treenode-1.0.2/setup.cfg` & `django-fast-treenode-1.0.3/setup.cfg`

 * *Files 6% similar despite different names*

```diff
@@ -1,59 +1,59 @@
-00000000: 5b6d 6574 6164 6174 615d 0d0a 6e61 6d65  [metadata]..name
-00000010: 203d 2064 6a61 6e67 6f2d 6661 7374 2d74   = django-fast-t
-00000020: 7265 656e 6f64 650d 0a76 6572 7369 6f6e  reenode..version
-00000030: 203d 2031 2e30 2e32 0d0a 6465 7363 7269   = 1.0.2..descri
-00000040: 7074 696f 6e20 3d20 4170 706c 6963 6174  ption = Applicat
-00000050: 696f 6e20 666f 7220 7375 7070 6f72 7469  ion for supporti
-00000060: 6e67 2074 7265 6520 2868 6965 7261 7263  ng tree (hierarc
-00000070: 6869 6361 6c29 2064 6174 6120 7374 7275  hical) data stru
-00000080: 6374 7572 6520 696e 2044 6a61 6e67 6f20  cture in Django 
-00000090: 7072 6f6a 6563 7473 0d0a 6c6f 6e67 5f64  projects..long_d
-000000a0: 6573 6372 6970 7469 6f6e 5f63 6f6e 7465  escription_conte
-000000b0: 6e74 5f74 7970 6520 3d20 7465 7874 2f70  nt_type = text/p
-000000c0: 6c61 696e 0d0a 6c6f 6e67 5f64 6573 6372  lain..long_descr
-000000d0: 6970 7469 6f6e 203d 2066 696c 653a 2052  iption = file: R
-000000e0: 4541 444d 452e 7273 740d 0a75 726c 203d  EADME.rst..url =
-000000f0: 2068 7474 7073 3a2f 2f67 6974 6875 622e   https://github.
-00000100: 636f 6d2f 5469 6d75 724b 6164 792f 6661  com/TimurKady/fa
-00000110: 7374 2d74 7265 656e 6f64 650d 0a61 7574  st-treenode..aut
-00000120: 686f 7220 3d20 5469 6d75 7220 4b61 6479  hor = Timur Kady
-00000130: 0d0a 6175 7468 6f72 5f65 6d61 696c 203d  ..author_email =
-00000140: 2074 696d 7572 6b61 6479 4079 616e 6465   timurkady@yande
-00000150: 782e 636f 6d0d 0a6c 6963 656e 7365 203d  x.com..license =
-00000160: 204d 4954 0d0a 636c 6173 7369 6669 6572   MIT..classifier
-00000170: 7320 3d20 0d0a 0945 6e76 6972 6f6e 6d65  s = ...Environme
-00000180: 6e74 203a 3a20 5765 6220 456e 7669 726f  nt :: Web Enviro
-00000190: 6e6d 656e 740d 0a09 4672 616d 6577 6f72  nment...Framewor
-000001a0: 6b20 3a3a 2044 6a61 6e67 6f0d 0a09 4672  k :: Django...Fr
-000001b0: 616d 6577 6f72 6b20 3a3a 2044 6a61 6e67  amework :: Djang
-000001c0: 6f20 3a3a 2033 2e30 0d0a 0949 6e74 656e  o :: 3.0...Inten
-000001d0: 6465 6420 4175 6469 656e 6365 203a 3a20  ded Audience :: 
-000001e0: 4465 7665 6c6f 7065 7273 0d0a 094c 6963  Developers...Lic
-000001f0: 656e 7365 203a 3a20 4f53 4920 4170 7072  ense :: OSI Appr
-00000200: 6f76 6564 203a 3a20 4253 4420 4c69 6365  oved :: BSD Lice
-00000210: 6e73 650d 0a09 4f70 6572 6174 696e 6720  nse...Operating 
-00000220: 5379 7374 656d 203a 3a20 4f53 2049 6e64  System :: OS Ind
-00000230: 6570 656e 6465 6e74 0d0a 0950 726f 6772  ependent...Progr
-00000240: 616d 6d69 6e67 204c 616e 6775 6167 6520  amming Language 
-00000250: 3a3a 2050 7974 686f 6e0d 0a09 5072 6f67  :: Python...Prog
-00000260: 7261 6d6d 696e 6720 4c61 6e67 7561 6765  ramming Language
-00000270: 203a 3a20 5079 7468 6f6e 203a 3a20 330d   :: Python :: 3.
-00000280: 0a09 5072 6f67 7261 6d6d 696e 6720 4c61  ..Programming La
-00000290: 6e67 7561 6765 203a 3a20 5079 7468 6f6e  nguage :: Python
-000002a0: 203a 3a20 3320 3a3a 204f 6e6c 790d 0a09   :: 3 :: Only...
-000002b0: 5072 6f67 7261 6d6d 696e 6720 4c61 6e67  Programming Lang
-000002c0: 7561 6765 203a 3a20 5079 7468 6f6e 203a  uage :: Python :
-000002d0: 3a20 332e 380d 0a09 5072 6f67 7261 6d6d  : 3.8...Programm
-000002e0: 696e 6720 4c61 6e67 7561 6765 203a 3a20  ing Language :: 
-000002f0: 5079 7468 6f6e 203a 3a20 332e 390d 0a0d  Python :: 3.9...
-00000300: 0a5b 6f70 7469 6f6e 735d 0d0a 696e 636c  .[options]..incl
-00000310: 7564 655f 7061 636b 6167 655f 6461 7461  ude_package_data
-00000320: 203d 2074 7275 650d 0a70 6163 6b61 6765   = true..package
-00000330: 7320 3d20 6669 6e64 3a0d 0a70 7974 686f  s = find:..pytho
-00000340: 6e5f 7265 7175 6972 6573 203d 203e 3d33  n_requires = >=3
-00000350: 2e38 0d0a 696e 7374 616c 6c5f 7265 7175  .8..install_requ
-00000360: 6972 6573 203d 200d 0a09 446a 616e 676f  ires = ...Django
-00000370: 203e 3d20 332e 300d 0a0d 0a5b 6567 675f   >= 3.0....[egg_
-00000380: 696e 666f 5d0d 0a74 6167 5f62 7569 6c64  info]..tag_build
-00000390: 203d 200d 0a74 6167 5f64 6174 6520 3d20   = ..tag_date = 
-000003a0: 300d 0a0d 0a                             0....
+00000000: 5b65 6767 5f69 6e66 6f5d 0d0a 7461 675f  [egg_info]..tag_
+00000010: 6275 696c 6420 3d20 0d0a 7461 675f 6461  build = ..tag_da
+00000020: 7465 203d 2030 0d0a 0d0a 5b6d 6574 6164  te = 0....[metad
+00000030: 6174 615d 0d0a 6e61 6d65 203d 2064 6a61  ata]..name = dja
+00000040: 6e67 6f2d 6661 7374 2d74 7265 656e 6f64  ngo-fast-treenod
+00000050: 650d 0a76 6572 7369 6f6e 203d 2031 2e30  e..version = 1.0
+00000060: 2e33 0d0a 6465 7363 7269 7074 696f 6e20  .3..description 
+00000070: 3d20 4170 706c 6963 6174 696f 6e20 666f  = Application fo
+00000080: 7220 7375 7070 6f72 7469 6e67 2074 7265  r supporting tre
+00000090: 6520 2868 6965 7261 7263 6869 6361 6c29  e (hierarchical)
+000000a0: 2064 6174 6120 7374 7275 6374 7572 6520   data structure 
+000000b0: 696e 2044 6a61 6e67 6f20 7072 6f6a 6563  in Django projec
+000000c0: 7473 0d0a 6c6f 6e67 5f64 6573 6372 6970  ts..long_descrip
+000000d0: 7469 6f6e 5f63 6f6e 7465 6e74 5f74 7970  tion_content_typ
+000000e0: 6520 3d20 7465 7874 2f6d 6172 6b64 6f77  e = text/markdow
+000000f0: 6e0d 0a6c 6f6e 675f 6465 7363 7269 7074  n..long_descript
+00000100: 696f 6e20 3d20 6669 6c65 3a20 5245 4144  ion = file: READ
+00000110: 4d45 2e6d 640d 0a75 726c 203d 2068 7474  ME.md..url = htt
+00000120: 7073 3a2f 2f67 6974 6875 622e 636f 6d2f  ps://github.com/
+00000130: 5469 6d75 724b 6164 792f 6661 7374 2d74  TimurKady/fast-t
+00000140: 7265 656e 6f64 650d 0a61 7574 686f 7220  reenode..author 
+00000150: 3d20 5469 6d75 7220 4b61 6479 0d0a 6175  = Timur Kady..au
+00000160: 7468 6f72 5f65 6d61 696c 203d 2074 696d  thor_email = tim
+00000170: 7572 6b61 6479 4079 616e 6465 782e 636f  urkady@yandex.co
+00000180: 6d0d 0a6c 6963 656e 7365 203d 204d 4954  m..license = MIT
+00000190: 0d0a 636c 6173 7369 6669 6572 7320 3d20  ..classifiers = 
+000001a0: 0d0a 0945 6e76 6972 6f6e 6d65 6e74 203a  ...Environment :
+000001b0: 3a20 5765 6220 456e 7669 726f 6e6d 656e  : Web Environmen
+000001c0: 740d 0a09 4672 616d 6577 6f72 6b20 3a3a  t...Framework ::
+000001d0: 2044 6a61 6e67 6f0d 0a09 4672 616d 6577   Django...Framew
+000001e0: 6f72 6b20 3a3a 2044 6a61 6e67 6f20 3a3a  ork :: Django ::
+000001f0: 2033 2e30 0d0a 0949 6e74 656e 6465 6420   3.0...Intended 
+00000200: 4175 6469 656e 6365 203a 3a20 4465 7665  Audience :: Deve
+00000210: 6c6f 7065 7273 0d0a 094c 6963 656e 7365  lopers...License
+00000220: 203a 3a20 4f53 4920 4170 7072 6f76 6564   :: OSI Approved
+00000230: 203a 3a20 4d49 5420 4c69 6365 6e73 650d   :: MIT License.
+00000240: 0a09 4f70 6572 6174 696e 6720 5379 7374  ..Operating Syst
+00000250: 656d 203a 3a20 4f53 2049 6e64 6570 656e  em :: OS Indepen
+00000260: 6465 6e74 0d0a 0950 726f 6772 616d 6d69  dent...Programmi
+00000270: 6e67 204c 616e 6775 6167 6520 3a3a 2050  ng Language :: P
+00000280: 7974 686f 6e0d 0a09 5072 6f67 7261 6d6d  ython...Programm
+00000290: 696e 6720 4c61 6e67 7561 6765 203a 3a20  ing Language :: 
+000002a0: 5079 7468 6f6e 203a 3a20 330d 0a09 5072  Python :: 3...Pr
+000002b0: 6f67 7261 6d6d 696e 6720 4c61 6e67 7561  ogramming Langua
+000002c0: 6765 203a 3a20 5079 7468 6f6e 203a 3a20  ge :: Python :: 
+000002d0: 3320 3a3a 204f 6e6c 790d 0a09 5072 6f67  3 :: Only...Prog
+000002e0: 7261 6d6d 696e 6720 4c61 6e67 7561 6765  ramming Language
+000002f0: 203a 3a20 5079 7468 6f6e 203a 3a20 332e   :: Python :: 3.
+00000300: 380d 0a09 5072 6f67 7261 6d6d 696e 6720  8...Programming 
+00000310: 4c61 6e67 7561 6765 203a 3a20 5079 7468  Language :: Pyth
+00000320: 6f6e 203a 3a20 332e 390d 0a0d 0a5b 6f70  on :: 3.9....[op
+00000330: 7469 6f6e 735d 0d0a 696e 636c 7564 655f  tions]..include_
+00000340: 7061 636b 6167 655f 6461 7461 203d 2074  package_data = t
+00000350: 7275 650d 0a70 6163 6b61 6765 7320 3d20  rue..packages = 
+00000360: 6669 6e64 3a0d 0a70 7974 686f 6e5f 7265  find:..python_re
+00000370: 7175 6972 6573 203d 203e 3d33 2e38 0d0a  quires = >=3.8..
+00000380: 696e 7374 616c 6c5f 7265 7175 6972 6573  install_requires
+00000390: 203d 200d 0a09 446a 616e 676f 203e 3d20   = ...Django >= 
+000003a0: 332e 300d 0a0d 0a                        3.0....
```

### Comparing `django-fast-treenode-1.0.2/treenode/admin.py` & `django-fast-treenode-1.0.3/treenode/admin.py`

 * *Files identical despite different names*

### Comparing `django-fast-treenode-1.0.2/treenode/docs/README.txt` & `django-fast-treenode-1.0.3/treenode/docs/README.txt`

 * *Files identical despite different names*

### Comparing `django-fast-treenode-1.0.2/treenode/factory.py` & `django-fast-treenode-1.0.3/treenode/factory.py`

 * *Files identical despite different names*

### Comparing `django-fast-treenode-1.0.2/treenode/forms.py` & `django-fast-treenode-1.0.3/treenode/forms.py`

 * *Files identical despite different names*

### Comparing `django-fast-treenode-1.0.2/treenode/managers.py` & `django-fast-treenode-1.0.3/treenode/managers.py`

 * *Files identical despite different names*

### Comparing `django-fast-treenode-1.0.2/treenode/models.py` & `django-fast-treenode-1.0.3/treenode/models.py`

 * *Files 2% similar despite different names*

```diff
@@ -180,29 +180,29 @@
             return list(getattr(item.parent, attr) for item in qs)
         else:
             return list(item.parent for item in qs)
 
     def get_children(self):
         """Get a list containing all children"""
 
-        return list(self.tn_children.all())
+        return list(self.self.get_children_queryset())
 
     def get_children_count(self):
         """Get the children count"""
 
         return self.get_children_queryset().count()
 
     def get_children_pks(self):
         """Get the children pks list"""
 
-        return [ch.pk for ch in self.tn_children.all()]
+        return [ch.pk for ch in self.get_children_queryset()]
 
     def get_children_queryset(self):
         """Get the children queryset"""
-        return self.tn_children.all()
+        return self._meta.model.objects.filter(tn_paren=self.id)
 
     def get_depth(self):
         """Get the node depth (self, how many levels of descendants)"""
 
         depths = self._closure_model.objects.filter(parent=self).values_list(
             'depth',
             flat=True
```

### Comparing `django-fast-treenode-1.0.2/treenode/static/select2tree/select2tree.css` & `django-fast-treenode-1.0.3/treenode/static/select2tree/select2tree.css`

 * *Files identical despite different names*

### Comparing `django-fast-treenode-1.0.2/treenode/static/select2tree/select2tree.js` & `django-fast-treenode-1.0.3/treenode/static/select2tree/select2tree.js`

 * *Files identical despite different names*

### Comparing `django-fast-treenode-1.0.2/treenode/static/treenode/css/treenode.css` & `django-fast-treenode-1.0.3/treenode/static/treenode/css/treenode.css`

 * *Files identical despite different names*

### Comparing `django-fast-treenode-1.0.2/treenode/static/treenode/js/treenode.js` & `django-fast-treenode-1.0.3/treenode/static/treenode/js/treenode.js`

 * *Files identical despite different names*

### Comparing `django-fast-treenode-1.0.2/treenode/templates/widgets/select2tree.html` & `django-fast-treenode-1.0.3/treenode/templates/widgets/select2tree.html`

 * *Files identical despite different names*

### Comparing `django-fast-treenode-1.0.2/treenode/widgets.py` & `django-fast-treenode-1.0.3/treenode/widgets.py`

 * *Files identical despite different names*

